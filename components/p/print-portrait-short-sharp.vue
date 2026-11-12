<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flah4ol6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-portrait-short-sharp" /></template>
<style>
.flah4ol6h {
  fill: currentColor;
  d: path("m2.45 17l-.775-1.225Q3.05 12.725 3.9 9.537T4.925 3h2.05V2h3v1H14V2h3v1h1l1 1q-.225 3.475-1.3 6.75T14.85 17zm2.525 4v-2h11.15q.825-1.475 1.525-2.937T19 13.125V21z");
}

</style>
