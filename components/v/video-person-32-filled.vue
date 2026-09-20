<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zovmttbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-person-32-filled" /></template>
<style>
.zovmttbtz {
  fill: currentColor;
  d: path("M2 7.25A3.25 3.25 0 0 1 5.25 4h21.5A3.25 3.25 0 0 1 30 7.25v17.5A3.25 3.25 0 0 1 26.75 28H5.25A3.25 3.25 0 0 1 2 24.75zM5.25 6C4.56 6 4 6.56 4 7.25v17.5c0 .69.56 1.25 1.25 1.25H8v-3.5a2.5 2.5 0 0 1 2.5-2.5h11a2.5 2.5 0 0 1 2.5 2.5V26h2.75c.69 0 1.25-.56 1.25-1.25V7.25C28 6.56 27.44 6 26.75 6zM16 18a5 5 0 1 0 0-10a5 5 0 0 0 0 10");
}

</style>
