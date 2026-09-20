<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q76ose0bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:volume-mute-rounded" /></template>
<style>
.q76ose0bx {
  fill: currentColor;
  d: path("M11 15H8q-.425 0-.712-.288T7 14v-4q0-.425.288-.712T8 9h3l3.3-3.3q.475-.475 1.088-.213t.612.938v11.15q0 .675-.612.938T14.3 18.3z");
}

</style>
