<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbhv5-y7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-1-5x-sharp" /></template>
<style>
.lbhv5-y7y {
  fill: currentColor;
  d: path("M6 17v-2h2v2zm-3 0V9H1V7h4v10zm12.5 0l3-5l-3-5h2l2 3.325L21.5 7h2l-3 5l3 5h-2l-2-3.325l-2 3.325zM9 17v-2h3.5v-2H9V7h5.5v2H11v2h3.5v6z");
}

</style>
