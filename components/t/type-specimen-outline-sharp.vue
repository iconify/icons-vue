<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk5pmqbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:type-specimen-outline-sharp" /></template>
<style>
.zk5pmqbwk {
  fill: currentColor;
  d: path("M9.666 14.5h.946l1.03-2.608h3.727L16.4 14.5h.973l-3.554-9h-.638zm2.273-3.408l1.492-4.019h.1l1.53 4.02zM6.5 17V3h14v14zm1-1h12V4h-12zm-4 4V6.616h1V19h12.385v1zm4-16v12z");
}

</style>
