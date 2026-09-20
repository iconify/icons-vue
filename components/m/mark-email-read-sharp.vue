<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngiadpgun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-email-read-sharp" /></template>
<style>
.ngiadpgun {
  fill: currentColor;
  d: path("m15.489 21.27l-3.558-3.558l.708-.708l2.85 2.85l5.688-5.688l.708.707zM3 19V5h18v6.542l-5.506 5.487l-2.855-2.856l-3.533 3.533L10.4 19zm9-6.884l8-5.231L19.692 6L12 11L4.308 6L4 6.885z");
}

</style>
