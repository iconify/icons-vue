<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l20cockhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mark-as-unread-sharp" /></template>
<style>
.l20cockhd {
  fill: currentColor;
  d: path("M2 17V6.25L10.5 2l9.8 5h-4.375L10.5 4.25L4 7.475V17zm3 4V8h17v13zm8.5-5.65L20 12v-2l-6.5 3.35L7 10v2z");
}

</style>
