<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhru11l-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:south-west-outline-rounded" /></template>
<style>
.dhru11l-r {
  fill: currentColor;
  d: path("M6 19q-.425 0-.712-.288T5 18v-8q0-.425.288-.712T6 9t.713.288T7 10v5.6L17.9 4.7q.275-.275.7-.275t.7.275t.275.7t-.275.7L8.4 17H14q.425 0 .713.288T15 18t-.288.713T14 19z");
}

</style>
