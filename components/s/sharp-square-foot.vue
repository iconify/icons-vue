<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_ufxvwmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-square-foot" /></template>
<style>
.f_ufxvwmy {
  fill: currentColor;
  d: path("m17.66 17.66l-1.06 1.06l-.71-.71l1.06-1.06l-1.94-1.94l-1.06 1.06l-.71-.71l1.06-1.06l-1.94-1.94l-1.06 1.06l-.71-.71l1.06-1.06L9.7 9.7l-1.06 1.06l-.71-.71l1.06-1.06l-1.94-1.94l-1.06 1.06l-.71-.71l1.06-1.06L4 4v16h16zM7 17v-5.76L12.76 17z");
}

</style>
