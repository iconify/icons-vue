<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtvk-_3jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-arrow-up-sharp" /></template>
<style>
.jtvk-_3jt {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.5686 16.353C2.915 14.8839 2 12.9769 2 11C2 6.5817 6.4772 3 12 3C17.5228 3 22 6.5817 22 11C22 15.4183 17.5228 19 12 19C11.1845 19 10.3721 18.9202 9.5808 18.7624L5 21ZM12 15L12 8M8.7071 11.2929L12 8L15.2929 11.2929");
}

</style>
