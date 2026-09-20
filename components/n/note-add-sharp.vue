<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgu8azdcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:note-add-sharp" /></template>
<style>
.cgu8azdcn {
  fill: currentColor;
  d: path("M11 18h2v-3h3v-2h-3v-3h-2v3H8v2h3zm-7 4V2h10l6 6v14zm9-13h5l-5-5z");
}

</style>
