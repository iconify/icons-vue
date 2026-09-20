<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jui462bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-pencil-outline-sharp" /></template>
<style>
.jui462bxk {
  fill: currentColor;
  d: path("M6.923 15.308L11.346 4h1.289l4.423 11.308zm1.458-1H15.6L12 5.128zm0 0H15.6zM5 20l.827-2.308h12.346L19 20z");
}

</style>
