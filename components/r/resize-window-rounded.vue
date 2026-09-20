<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w79lowova"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:resize-window-rounded" /></template>
<style>
.w79lowova {
  fill: currentColor;
  d: path("M20.3 20.3q-.3.3-.712.3t-.713-.3L3.7 5.125q-.3-.3-.3-.712t.3-.713t.712-.3t.713.3L20.3 18.875q.3.3.3.713t-.3.712m-10 0q-.3.3-.712.3t-.713-.3L3.7 15.125q-.3-.3-.3-.712t.3-.713t.713-.3t.712.3l5.175 5.175q.3.3.3.713t-.3.712");
}

</style>
