<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik3lv8y0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-0-5x-outline-sharp" /></template>
<style>
.ik3lv8y0g {
  fill: currentColor;
  d: path("M3 17v-2h2v2zm10 0l3-5l-3-5h2l2 3.325L19 7h2l-3 5l3 5h-2l-2-3.325L15 17zm-7 0v-2h4v-2H6V7h6v2H8v2h4v6z");
}

</style>
