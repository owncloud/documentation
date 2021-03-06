=======================
Apply Finishing Touches
=======================

Now, the only thing left is to style the textarea in a nicer fashion. 
To do that open ``ownnotes/css/style.css`` and replace the content with the following :doc:`CSS <../fundamentals/css>` code:

.. code-block:: css

    #app-content-wrapper {
        height: 100%;
    }

    #editor {
        height: 100%;
        width: 100%;
    }

    #editor .input {
        height: calc(100% - 51px);
        width: 100%;
    }

    #editor .save {
        height: 50px;
        width: 100%;
        text-align: center;
        border-top: 1px solid #ccc;
        background-color: #fafafa;
    }

    #editor textarea {
        height: 100%;
        width: 100%;
        border: 0;
        margin: 0;
        border-radius: 0;
        overflow-y: auto;
    }

    #editor button {
        height: 44px;
    }

Congratulations! 
You've written your first ownCloud app. 
You can now either try to further improve the tutorial notes app or start writing your own app.
