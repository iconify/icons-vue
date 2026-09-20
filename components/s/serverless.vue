<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":204};
const content = `<path class="uyft4cg7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:serverless" /></template>
<style>
.uyft4cg7i {
  fill: var(--svg-color--f26d61, #f26d61);
  d: path("M0 161.202h45.312l-14.039 42.396H0zM0 80.6h72l-14.036 42.396H0zM0 0h98.692l-14.04 42.395H0zm143.349 0H256v42.395H129.312zM116.66 80.6H256v42.397H102.622zm-26.69 80.602H256v42.396H75.933z");
}

</style>
