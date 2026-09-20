<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snsj9wp7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-home-24-filled" /></template>
<style>
.snsj9wp7t {
  fill: currentColor;
  d: path("M16.524 12.36a1.5 1.5 0 0 1 1.952 0l4 3.427c.332.285.524.7.524 1.139V22a1 1 0 0 1-1 1h-1.667a1 1 0 0 1-1-1v-3a1 1 0 0 0-1-1h-1.666a1 1 0 0 0-1 1v3a1 1 0 0 1-1 1H13a1 1 0 0 1-1-1v-5.074a1.5 1.5 0 0 1 .524-1.139zm-4.65 2.667A2.5 2.5 0 0 0 11 16.926v5.039c-2.916-.194-5.098-1.253-6.485-3.2a2.75 2.75 0 0 1-.511-1.596v-.92A2.25 2.25 0 0 1 6.253 14h6.82zM12 2.005a5 5 0 1 1 0 10a5 5 0 0 1 0-10");
}

</style>
