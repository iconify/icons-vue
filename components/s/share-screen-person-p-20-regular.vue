<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hj53ok8au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-screen-person-p-20-regular" /></template>
<style>
.hj53ok8au {
  fill: currentColor;
  d: path("M2 6.75A2.75 2.75 0 0 1 4.75 4h10.5A2.75 2.75 0 0 1 18 6.75v3.591a3 3 0 0 0-1-.94V6.75A1.75 1.75 0 0 0 15.25 5H4.75A1.75 1.75 0 0 0 3 6.75v6.5c0 .966.784 1.75 1.75 1.75h6.75a2.5 2.5 0 0 0-.45 1h-6.3A2.75 2.75 0 0 1 2 13.25zM15.5 14a2 2 0 1 0 0-4a2 2 0 0 0 0 4m0 5c2.5 0 3.5-1.255 3.5-2.5a1.5 1.5 0 0 0-1.5-1.5h-4a1.5 1.5 0 0 0-1.5 1.5c0 1.25 1 2.5 3.5 2.5m-9-12a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 1 0V11h1a2 2 0 1 0 0-4zM8 10H7V8h1a1 1 0 0 1 0 2");
}

</style>
