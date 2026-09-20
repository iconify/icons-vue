<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi8woqdbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:notifications-unread-sharp" /></template>
<style>
.xi8woqdbk {
  fill: currentColor;
  d: path("M12 22q-.825 0-1.412-.587T10 20h4q0 .825-.587 1.413T12 22m-8-3v-2h2v-7q0-2.075 1.25-3.687T10.5 4.2V2h3v1.825q-.25.5-.375 1.05T13 6q0 2.075 1.463 3.538T18 11v6h2v2zM15.875 8.125Q15 7.25 15 6t.875-2.125T18 3t2.125.875T21 6t-.875 2.125T18 9t-2.125-.875");
}

</style>
