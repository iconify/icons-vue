<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj793u47m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-warning-fill" /></template>
<style>
.nj793u47m {
  fill: currentColor;
  d: path("M19 6a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-5.568 4H10c-.468 0-.98-.395-1.293-.707l-5-5.001A3 3 0 0 1 5 4h6a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779A6 6 0 0 0 13.432 10M2.292 5.707l5.001 5C8.008 11.422 8.961 12 10 12h4c.521 0 1.032-.151 1.493-.389c1.033.554 2.21.887 3.388.845a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7c0-.448.099-.889.292-1.293M18.01 8a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2Z");
}

</style>
