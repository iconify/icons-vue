<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk4z11zcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-multiple-24-filled" /></template>
<style>
.pk4z11zcw {
  fill: currentColor;
  d: path("M2 7.75A4.75 4.75 0 0 1 6.75 3h10A2.25 2.25 0 0 1 19 5.25v.25H7.75A3.25 3.25 0 0 0 4.5 8.75V17h-.25A2.25 2.25 0 0 1 2 14.75zM7.75 6.5A2.25 2.25 0 0 0 5.5 8.75v9.5a2.25 2.25 0 0 0 2.25 2.25h12A2.25 2.25 0 0 0 22 18.25v-9.5a2.25 2.25 0 0 0-2.25-2.25z");
}

</style>
