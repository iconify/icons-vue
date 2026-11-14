<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5gj5xb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:newborn-screening" /></template>
<style>
.t5gj5xb0q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 4.75q-1.5 0-1.5 1.5q-.5-.5-1.5-.5q-2 0-2 2t2 2t2-2q0-.143-.01-.276q.367.276 1.01.276q.551 0 .9-.202q.324.702 1.35.702q.276 0 .501-.051l-.001.051q0 1.25 1.25 1.25T15 8.25T13.75 7q-.139 0-.263.016q.013-.127.013-.266q0-1.5-1.5-1.5q-.551 0-.9.202q-.324-.702-1.35-.702m-2.423 6.02q-2.577.527-2.577 2.98q0 1.077.772 2.826q.613 1.391.728 2.225q.027 2.714 2.877 3.189q1.432.239 2.41-.479q.964-.707 1.203-2.138q.01-.061.01-.123q0-.497.409-1.677q.741-2.142.591-3.614q-.019-2.429-2.212-3.226q-1.738-.632-4.211.037m10.749 1.75Q20.5 15.428 20.5 17q0 3.25-3 3.25t-3-3.25q0-1.572 2.424-4.48q.047-.057.105-.103q.057-.047.122-.081q.066-.034.137-.055t.144-.028q.074-.007.147.001q.074.008.144.03q.071.022.136.057q.064.036.121.083q.053.043.096.096");
}

</style>
