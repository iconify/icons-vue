<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk04rybix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticker-add-outline-sharp" /></template>
<style>
.xk04rybix {
  fill: currentColor;
  d: path("M11.5 14.73q1.494 0 2.654-.922q1.16-.923 1.5-2.373L8.5 13.454q.592.627 1.367.952t1.633.325m-4.073-3.712l2.38-.673q.062-.565-.325-.985t-.991-.419q-.539 0-.919.382q-.38.381-.38.926q0 .217.072.4q.07.183.163.37m6-1.75l2.38-.674q.068-.565-.323-.985q-.392-.419-.984-.419q-.545 0-.926.382t-.382.926q0 .217.072.4q.07.183.163.37M4 20V4h10.616v1H5v14h10v-4h4V9.385h1v6.192L15.577 20zM19 7V5h-2V4h2V2h1v2h2v1h-2v2z");
}

</style>
