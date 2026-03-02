import java.util.ArrayList;

public class FlashcardSet {
    private ArrayList<Flashcard> list;
    private String name;
    private String type;

    public FlashcardSet(String n, String t)
    {
        list = new ArrayList<>();
        name = n;
        type = t;
    }

    public void addFlashcard(Flashcard card){
        list.add(card);
    }

    public int getSize(){
        return list.size();
    }

    public void getList()
    {
        for (int i = 0; i < list.size(); i++)
        {
            System.out.println(list.get(i));
        }
    }

    public String getName(){
        return name;
    }

    public String getType(){
        return type;
    }

    public void setName(String n){
        name = n;
    }

    public void setType(String t){
        type = t;
    }
}
