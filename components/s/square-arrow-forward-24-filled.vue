<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-cl81h4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-arrow-forward-24-filled" /></template>
<style>
.i-cl81h4t {
  fill: currentColor;
  d: path("M6.25 3A3.25 3.25 0 0 0 3 6.25v11.5A3.25 3.25 0 0 0 6.25 21h5.772A6.5 6.5 0 0 1 21 12.022V6.25A3.25 3.25 0 0 0 17.75 3zM12 17.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 0 0-11 0m6.646-2.146a.5.5 0 0 1 .708-.708l1.5 1.5a.5.5 0 0 1 0 .708l-1.5 1.5a.5.5 0 0 1-.708-.708l.647-.646H17.25A2.25 2.25 0 0 0 15 19.25v.25a.5.5 0 0 1-1 0v-.25A3.25 3.25 0 0 1 17.25 16h2.043z");
}

</style>
