<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnkkxmv_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-wifi-gale-sharp" /></template>
<style>
.cnkkxmv_t {
  fill: currentColor;
  d: path("m5 20l-.325-1H4.15q-.875 0-1.462-.625q-.588-.625-.538-1.5l.725-11q.05-.8.625-1.338Q4.075 4 4.875 4h14.25q.8 0 1.375.537q.575.538.625 1.338l.725 11q.05.875-.538 1.5q-.587.625-1.462.625h-.525L19 20Zm-.4-10h14.8l-.275-4H4.875Zm-.45 7h15.7l-.325-5H4.475l-.325 5Z");
}

</style>
