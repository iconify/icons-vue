<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nguythbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-new-right-sharp" /></template>
<style>
.nguythbhf {
  fill: currentColor;
  d: path("m19 22.289l-.688-.689l2.055-2.1H15.5v-1h4.867l-2.056-2.1l.689-.688L22.288 19zM4 20V4h16v9.427q-.236-.06-.49-.09t-.516-.03q-2.365 0-4.026 1.661T13.308 19q0 .263.03.513t.089.487zm7.5-3.5h1v-4h4v-1h-4v-4h-1v4h-4v1h4z");
}

</style>
