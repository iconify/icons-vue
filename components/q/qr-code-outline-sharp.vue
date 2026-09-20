<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apng0ewuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:qr-code-outline-sharp" /></template>
<style>
.apng0ewuu {
  fill: currentColor;
  d: path("M3 11V3h8v8zm2-2h4V5H5zM3 21v-8h8v8zm2-2h4v-4H5zm8-8V3h8v8zm2-2h4V5h-4zm4 12v-2h2v2zm-6-6v-2h2v2zm2 2v-2h2v2zm-2 2v-2h2v2zm2 2v-2h2v2zm2-2v-2h2v2zm0-4v-2h2v2zm2 2v-2h2v2z");
}

</style>
