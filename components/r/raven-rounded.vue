<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgs_2sser"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:raven-rounded" /></template>
<style>
.cgs_2sser {
  fill: currentColor;
  d: path("M5.807 5.807q-.21.21-.21.52t.21.52t.52.21t.52-.21t.21-.52t-.21-.52t-.52-.21t-.52.21m4 11.424l-1.39 3.305q-.073.183-.268.26t-.378.002t-.268-.268t-.012-.378l1.286-3.061q-2.535-.47-4.156-2.437T3 10.116V6.327q0-1.38.973-2.354Q4.946 3 6.327 3q.377 0 .733.091q.356.092.702.234l3.967 1.662q.248.105.245.366q-.003.26-.27.366l-2.05.8v1.943l7.33 4.923h-7.08q-1.09 0-1.852-.739q-.762-.738-.79-1.823q-.018-.196-.158-.33q-.14-.135-.343-.135q-.213 0-.356.143t-.144.357q0 .596.223 1.16q.224.565.568.992q.512.65 1.241 1.012t1.61.363H18.5l1.942 1.327l.449 2.617q.055.271-.111.471t-.438.2h-.196q-.179 0-.321-.099t-.21-.247l-.596-1.423h-5.615V20.5q0 .214-.143.357t-.357.143t-.357-.143t-.143-.357v-3.27z");
}

</style>
