<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ftl7v8b_s"/><path class="krgpugb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mountains-bold-duotone" /></template>
<style>
.ftl7v8b_s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.80833 19.7125C2.80833 19.7125 1.90833 18.2125 3.00833 15.4125L6.10833 7.21248C7.60833 3.31248 10.7083 3.31248 12.2083 7.21248L13.0083 9.31248C13.6083 10.8125 14.6083 10.8125 15.3083 9.41248C16.4083 7.31248 18.5083 7.41248 19.5083 10.1125L21.1083 15.5125C22.0083 18.2125 21.1083 19.7125 18.2083 19.7125H5.80833Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.krgpugb-b {
  fill: currentColor;
  d: path("M6.10938 7.21224C7.60937 3.31253 10.709 3.31258 12.209 7.21224L12.5518 8.11165L12.5078 8.11263C11.4078 8.51263 10.3072 7.61263 9.40723 8.61263C8.50725 9.61237 7.30748 9.7121 5.80762 8.21224L5.73047 8.21126L6.10938 7.21224Z");
}

</style>
