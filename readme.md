# CSS Flex Box

## Necessary display properties value for everyday of css developer life

    1. flex
    2. grid
    3. inline-block
    4. block
    5. inline-flex


-  flex - One dimensional Layout methods.


    - flex direction - choose dimensional  with this properties

    1. flex direction : column, row , row-reverse, column-reverse;
        ```css
          flex-direction :row; defualt
          flex-direction: column;
          flex-direction : row-reverse; // revesing the row
          flex-direction :  column-reverse // reversing the column 
        ```
 
    3. Items And Justify alignments :

    - I. align-items for aligning items vertically eg. Y Axis

      ```css
          align-items :center;
          align-items: start;
          align-items:end;
        ```

    - II. justify-content for aligning items horizontally eg. x axis

      ```css
      justify-content: center;
      justify-content: space-between;
      justify-content: space-evenly;
      justify-content: space-around;
      ```

    4. flex box grow or shirnk

    - I. Flex grow - it adds more with with compare to other items

    ```css
    flex-grow :1 , you can add custom value as well
    flex-grow:2;
    flex-grow:3;

    ```

    custom

    ```css
    flex-grow : 0.4;
    ```


    - flex shirnk - it reduces more  width compare to other items

    ```css
    flex-shirnk : 1;
    flex-shirnk: 2;

    ```


    5. flex wrap - flex wrap adjusting all the items width if there is no remain space

    ```css
    flex-wrap:wrap;
    flex-wrap:no-wrap;
    ```

    # best of Luck Fahim,Amjad,Tanim :)
