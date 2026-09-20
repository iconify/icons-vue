<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf_x0deki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-slight-right-rounded" /></template>
<style>
.xf_x0deki {
  fill: currentColor;
  d: path("M9.643 19.626q-.143-.144-.143-.357v-6.517q0-.332.13-.632t.349-.518L15.6 6h-2.48q-.213 0-.357-.144t-.144-.357t.144-.356t.356-.143h3.362q.343 0 .575.232t.233.576v3.361q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356V6.69l-5.616 5.596q-.096.096-.134.202t-.039.22v6.562q0 .213-.144.357t-.357.143t-.356-.143");
}

</style>
