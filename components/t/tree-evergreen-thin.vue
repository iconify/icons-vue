<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mg1ls72hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tree-evergreen-thin" /></template>
<style>
.mg1ls72hm {
  fill: currentColor;
  d: path("m227.16 189.54l-51-65.54H208a4 4 0 0 0 3.17-6.44l-80-104a4 4 0 0 0-6.34 0l-80 104A4 4 0 0 0 48 124h31.82l-51 65.54A4 4 0 0 0 32 196h92v44a4 4 0 0 0 8 0v-44h92a4 4 0 0 0 3.16-6.46M40.18 188l51-65.54A4 4 0 0 0 88 116H56.12L128 22.56L199.88 116H168a4 4 0 0 0-3.16 6.46l51 65.54Z");
}

</style>
