<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltfq-m6hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:type-specimen-sharp" /></template>
<style>
.ltfq-m6hv {
  fill: currentColor;
  d: path("M9.666 14.5h.946l1.03-2.608h3.727L16.4 14.5h.973l-3.554-9h-.638zm2.273-3.408l1.492-4.019h.1l1.53 4.02zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
