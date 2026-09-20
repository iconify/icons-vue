<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfwnp9b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pen-size-2-outline" /></template>
<style>
.cfwnp9b4p {
  fill: currentColor;
  d: path("M5.314 18q0-.29.198-.488l12.019-12q.198-.204.466-.214q.269-.01.492.214q.197.198.197.488t-.198.489l-12 12q-.198.198-.488.198t-.489-.198T5.313 18");
}

</style>
