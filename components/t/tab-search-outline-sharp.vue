<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwpendbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-search-outline-sharp" /></template>
<style>
.pwpendbjc {
  fill: currentColor;
  d: path("M3 19V5h18v4.885h-7.23V6H4v12h6.75v1zm1-1V9.77v1.115V6zm17.292 3l-2.661-2.642q-.454.286-.977.464T16.577 19q-1.413 0-2.418-1.005t-1.005-2.418t1.005-2.418t2.418-1.005t2.418 1.005T20 15.577q0 .554-.159 1.087q-.158.532-.503.967L22 20.292zm-2.998-3.706q.706-.706.706-1.717t-.706-1.717t-1.717-.706t-1.718.706t-.705 1.717t.705 1.717q.707.706 1.718.706t1.717-.706");
}

</style>
