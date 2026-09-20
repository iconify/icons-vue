<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7-k-rg-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thumb-down" /></template>
<style>
.a7-k-rg-z {
  fill: currentColor;
  d: path("M6 3h10v13l-7 7l-1.25-1.25q-.175-.175-.288-.475T7.35 20.7v-.35L8.45 16H3q-.8 0-1.4-.6T1 14v-2q0-.175.037-.375t.113-.375l3-7.05q.225-.5.75-.85T6 3m12 13V3h4v13z");
}

</style>
