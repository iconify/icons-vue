<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xtrnmlb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:medal-20-regular" /></template>
<style>
.xtrnmlb4s {
  fill: currentColor;
  d: path("M13.867 2a2.5 2.5 0 0 1 2.145 1.214l.632 1.054c.233.388.356.833.356 1.286v.09a2.5 2.5 0 0 1-.42 1.387l-3.21 4.815a4 4 0 1 1-6.74.001L3.42 7.03A2.5 2.5 0 0 1 3 5.645v-.091a2.5 2.5 0 0 1 .356-1.286l.632-1.054A2.5 2.5 0 0 1 6.133 2zM10 11a3 3 0 1 0 0 6a3 3 0 0 0 0-6M5.002 3.517q-.086.097-.156.212l-.632 1.053A1.5 1.5 0 0 0 4 5.554v.09c0 .297.088.586.252.833L7.3 11.049a4 4 0 0 1 1.829-.953L5.245 4.27a1.46 1.46 0 0 1-.243-.753m9.995 0a1.46 1.46 0 0 1-.242.753l-3.886 5.826a4 4 0 0 1 1.83.952l3.049-4.571A1.5 1.5 0 0 0 16 5.645v-.091a1.5 1.5 0 0 0-.214-.772l-.632-1.053a1.5 1.5 0 0 0-.157-.212M10 9.599L12.4 6H7.6zM6.46 3a.46.46 0 0 0-.383.715l.86 1.29L7 5h6q.03 0 .062.006l.86-1.291A.461.461 0 0 0 13.54 3z");
}

</style>
