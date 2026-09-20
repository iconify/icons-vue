<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="afzqcbwqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-line-horizontal-3-20-filled" /></template>
<style>
.afzqcbwqx {
  fill: currentColor;
  d: path("M10.898 2.9a1 1 0 0 0-1.794 0l-1.93 3.91l-4.317.628a1 1 0 0 0-.554 1.706l3.124 3.044l-.738 4.3a1 1 0 0 0 1.451 1.054l4.862-2.559V13.5a1.5 1.5 0 0 1 1.5-1.5a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1-.073-2.998zm1.604 7.1a.5.5 0 1 0 0 1h5a.5.5 0 1 0 0-1zm-.5-2.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m.5 5.5a.5.5 0 1 0 0 1h5a.5.5 0 1 0 0-1z");
}

</style>
