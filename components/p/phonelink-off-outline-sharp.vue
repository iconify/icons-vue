<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlite1dyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phonelink-off-outline-sharp" /></template>
<style>
.wlite1dyx {
  fill: currentColor;
  d: path("m8.85 6l-2-2H21v2zM22 19l-2-2v-7h-4v3.15l-2-2V8h8zm-2.2 3.6L17.2 20H14v-3.2l-8-8V17h6v3H2v-3h2V6.8L1.4 4.2l1.4-1.4l18.4 18.4zM18 15.075");
}

</style>
