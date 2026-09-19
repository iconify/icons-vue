<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y3_zz1b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:newsdigest" /></template>
<style>
.y3_zz1b5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.905 19.793l13.179 22.826H13.251l-10.75-18.62l10.75-18.62l8.321 14.413H4.93m30.165 8.415L21.916 5.381h12.833l10.75 18.62l-10.75 18.62l-8.321-14.413H43.07");
}

</style>
