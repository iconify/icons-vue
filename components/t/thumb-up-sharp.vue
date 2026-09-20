<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw921fbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thumb-up-sharp" /></template>
<style>
.kw921fbsc {
  fill: currentColor;
  d: path("M7.654 20V9l6.269-6.192l.87.869L13.665 9H22v3.17L18.696 20zM3 20V9h3.654v11z");
}

</style>
