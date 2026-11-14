<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr15r711t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:medical-cross-shield" /></template>
<style>
.xr15r711t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.779 4.804l-7.5-3Q12.144 1.75 12 1.75t-.279.054l-7.5 3q-.104.041-.191.112q-.088.07-.151.164q-.063.093-.096.2t-.033.22V11q0 7.709 7.949 11.187q.144.063.301.063t.301-.063Q20.25 18.709 20.25 11V5.5q0-.112-.033-.22q-.033-.107-.096-.2t-.151-.164q-.087-.071-.191-.112M12 6.25q2.25 0 2.25 2.25q0 .75.75.75q2.25 0 2.25 2.25T15 13.75q-.75 0-.75.75q0 2.25-2.25 2.25T9.75 14.5q0-.75-.75-.75q-2.25 0-2.25-2.25T9 9.25q.75 0 .75-.75q0-2.25 2.25-2.25");
}

</style>
