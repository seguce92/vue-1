<template>
<div>
    <h3>Image Before Text</h3>
<table>
    <tr>
        <td>Image Left/Text Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'left'" value=''
                :textImageRelation="'imageBeforeText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Left/Text Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'center'" 
                :textImageRelation="'imageBeforeText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Left/Text Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'right'" 
                :textImageRelation="'imageBeforeText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
    </tr>
    <tr>
        <td>Image Center/Text Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'left'" 
                :textImageRelation="'imageBeforeText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Center/Text Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'center'" 
                :textImageRelation="'imageBeforeText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Center/Text Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'right'" 
                :textImageRelation="'imageBeforeText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
    </tr>
    <tr>
        <td>Image Right/Text Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'left'" 
                :textImageRelation="'imageBeforeText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Right/Text Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'center'" 
                :textImageRelation="'imageBeforeText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Right/Text Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'right'" 
                :textImageRelation="'imageBeforeText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
    </tr>
</table>
<h3>Text Before Image</h3>
<table>
    <tr>
        <td>Text Left/Image Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'left'" 
                :textImageRelation="'textBeforeImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Left/Image Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'left'" 
                :textImageRelation="'textBeforeImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Left/Image Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'left'" 
                :textImageRelation="'textBeforeImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
    </tr>
    <tr>
        <td>Text Center/Image Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'center'" 
                :textImageRelation="'textBeforeImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Center/Image Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'center'" 
                :textImageRelation="'textBeforeImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Center/Image Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'center'" 
                :textImageRelation="'textBeforeImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
    </tr>
    <tr>
        <td>Text Right/Image Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'right'" 
                :textImageRelation="'textBeforeImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Right/Image Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'right'" 
                :textImageRelation="'textBeforeImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Right/Image Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'right'" 
                :textImageRelation="'textBeforeImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
    </tr>
</table>
<h3>Image Above Text</h3>
<table>
    <tr>
        <td>Image Left/Text Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'left'" 
                :textImageRelation="'imageAboveText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Left/Text Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'left'" 
                :textImageRelation="'imageAboveText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Left/Text Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'right'" 
                :textImageRelation="'imageAboveText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
    </tr>
    <tr>
        <td>Image Center/Text Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'left'" 
                :textImageRelation="'imageAboveText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Center/Text Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'center'" 
                :textImageRelation="'imageAboveText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Center/Text Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'right'" 
                :textImageRelation="'imageAboveText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
    </tr>
    <tr>
        <td>Image Right/Text Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'left'" 
                :textImageRelation="'imageAboveText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Right/Text Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'center'" 
                :textImageRelation="'imageAboveText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Right/Text Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'right'" 
                :textImageRelation="'imageAboveText'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
    </tr>
</table>
<h3>Text Above Image</h3>
<table>
    <tr>
        <td>Text Left/Image Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'top'" 
                :textImageRelation="'textAboveImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Left/Image Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'left'" 
                :textImageRelation="'textAboveImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Left/Image Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'left'" 
                :textImageRelation="'textAboveImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
    </tr>
    <tr>
        <td>Text Center/Image Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'center'" 
                :textImageRelation="'textAboveImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Center/Image Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'center'" 
                :textImageRelation="'textAboveImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Center/Image Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'center'" 
                :textImageRelation="'textAboveImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
    </tr>
    <tr>
        <td>Text Right/Image Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'right'" 
                :textImageRelation="'textAboveImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Right/Image Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'right'" 
                :textImageRelation="'textAboveImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
        <td>Text Right/Image Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'right'" 
                :textImageRelation="'textAboveImage'" :imgSrc="'https://www.jqwidgets.com/vue/images/twitter.png'">
              Button
            </JqxButton>
        </td>
    </tr>
</table>
<h3>Overlay(Text and Image can be one over another)</h3>
<table>
    <tr>
        <td>Image Left/Text Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'left'" 
                :textImageRelation="'overlay'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Left/Text Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'center'" 
                :textImageRelation="'overlay'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Left/Text Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'left'" :textPosition="'right'" 
                :textImageRelation="'overlay'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
    </tr>
    <tr>
        <td>Image Center/Text Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'left'" 
                :textImageRelation="'overlay'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
            </td>
        <td>Image Center/Text Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'center'" 
                :textImageRelation="'overlay'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Center/Text Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'center'" :textPosition="'right'" 
                :textImageRelation="'overlay'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
    </tr>
    <tr>
        <td>Image Right/Text Left</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'left'" 
                :textImageRelation="'overlay'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
            </td>
        <td>Image Right/Text Center</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'center'" 
                :textImageRelation="'overlay'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
        <td>Image Right/Text Right</td>
        <td>
            <JqxButton :theme="'material'" :width="120" :imgPosition="'right'" :textPosition="'right'" 
                :textImageRelation="'overlay'" :imgSrc="'https://www.jqwidgets.com/vue/images/facebook.png'">
              Button
            </JqxButton>
        </td>
    </tr>
</table>
</div>
</template>

    <script>
    import JqxButton from 'jqwidgets-scripts/jqwidgets-vue/vue_jqxbuttons.vue';

    export default {
        components: {
            JqxButton
        }
    }
</script>

<style>
     
  
</style>