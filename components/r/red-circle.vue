<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="kj73mib-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:red-circle" /></template>
<style>
.kj73mib-f {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

</style>
