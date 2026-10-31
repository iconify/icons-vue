<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq_9isp_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:thumb-like-24-filled" /></template>
<style>
.eq_9isp_b {
  fill: currentColor;
  d: path("M11.623 2.91c.288-1.029 1.424-1.695 2.484-1.29a2 2 0 0 1 .409.185c.211.121.48.314.743.61c.538.606.998 1.58.998 3.083c0 .796-.168 1.917-.322 2.797c-.045.253-.09.49-.13.702h.941a3.75 3.75 0 0 1 3.69 4.427l-.71 3.861a5.75 5.75 0 0 1-7.192 4.504l-6.797-1.886a3.25 3.25 0 0 1-2.326-2.54l-.356-1.925c-.308-1.663.72-3.156 2.074-3.854c4.172-2.152 5.88-6.476 6.494-8.674");
}

</style>
