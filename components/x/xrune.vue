<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg9bohboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xrune" /></template>
<style>
.gg9bohboc {
  fill: var(--svg-color--28dbd1, #28dbd1);
  d: path("M7.765 13.059L15.722 3l-3.198 7.941h3.711L8.352 21l3.171-7.941z");
}

</style>
