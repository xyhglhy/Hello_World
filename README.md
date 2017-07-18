# Hello_World
protected void onActivityResult(int requestCode, int resultCode, Intent data) {    super.onActivityResult(requestCode, resultCode, data);    if(requestCode==1&&resultCode==2){               String mo=     data.getStringExtra("o");        textView.setText(mo);
 protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
