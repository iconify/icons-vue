<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9x_oe3oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:request-page" /></template>
<style>
.u9x_oe3oe {
  fill: currentColor;
  d: path("M11.5 17.5h1v-1H14q.213 0 .356-.144T14.5 16v-3q0-.213-.144-.356T14 12.5h-3.5v-2h4v-1h-2v-1h-1v1H10q-.213 0-.356.144T9.5 10v3q0 .213.144.356T10 13.5h3.5v2h-4v1h2zM6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h6.961L19 8.423v10.962q0 .69-.462 1.153T17.384 21z");
}

</style>
