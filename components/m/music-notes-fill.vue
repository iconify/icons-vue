<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-2dld3nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-notes-fill" /></template>
<style>
.s-2dld3nz {
  fill: currentColor;
  d: path("M8 9c0-.601.111-1.205.382-1.746c.271-.543.716-1.007 1.302-1.203l9-3c1.034-.344 2.308-.104 2.961.827c.231.33.355.719.355 1.122v11a4.001 4.001 0 1 1-2-3.465V5.017a.3.3 0 0 0-.078-.053c-.185-.092-.415-.079-.606-.015l-9 3l.003-.001c-.069.043-.114.131-.149.201c-.13.262-.17.561-.17.851v9a4.001 4.001 0 1 1-2-3.465Z");
}

</style>
