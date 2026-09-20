<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s16m4-bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-edit-16-filled" /></template>
<style>
.s16m4-bct {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5V5h3V2zM6 2v3h4V2zM5 6H2v4h3zm1 4V6h4v.944L6.944 10zm-1 1H2v.5A2.5 2.5 0 0 0 4.5 14H5zm9-6v-.5A2.5 2.5 0 0 0 11.5 2H11v3zm-7.02 6.377l4.83-4.83a1.87 1.87 0 1 1 2.644 2.646l-4.83 4.829a2.2 2.2 0 0 1-1.02.578l-1.498.374a.89.89 0 0 1-1.079-1.078l.375-1.498a2.2 2.2 0 0 1 .578-1.02");
}

</style>
