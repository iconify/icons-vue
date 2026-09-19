<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tzz05bbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:red-triangle-pointed-down" /></template>
<style>
.tzz05bbsl {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M1.543 9.192c9.107 16.636 18.215 33.26 27.32 49.898a3.575 3.575 0 0 0 6.327 0c9.108-16.636 18.215-33.26 27.32-49.898c1.409-2.571-.387-5.902-3.163-5.902H4.698c-1.54 0-2.571.828-3.111 1.949c-.676 1.068-.859 2.488-.052 3.953");
}

</style>
