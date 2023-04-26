public class ListasEncadeadas
{
    //Atributos
    private int valor;
    private Noh proxNoh;
    //Construtor
    public Noh(){
        this.valor = 0;
        this.proxNoh = null;
    }
    public Noh(int v){
        this.valor = v;
        this.proxNoh = null;
    }
    //Gets e Sets
    public int getValor(){
        return valor;
    }
    public void setValor(int Valor){
        this.valor = valor;
    }
    public Noh getProxNoh(){
        return proxNoh;
    }
    public void setProxNoh(){
        this.proxNoh = proxNoh
    }
    //Imprime
    public void imprimeNoh(){
        System.out.println("["+ this.valor + "]");
    }
    public String getNoh(){
        return "[" + this.valor + "]";
    }

}

