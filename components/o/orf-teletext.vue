<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iky7rgbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:orf-teletext" /></template>
<style>
.iky7rgbby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.775 35.616h6.665V42.5h-6.665zm.222-15.023h6.666v6.884h-6.666zm-.136-14.886h6.661v6.884h-6.661zM6.764 5.5h6.665v6.884H6.764zm27.807.25h6.665v6.884h-6.665z");
}

</style>
