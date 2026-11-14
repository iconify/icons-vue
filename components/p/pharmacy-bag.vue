<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gehyrub1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pharmacy-bag" /></template>
<style>
.gehyrub1a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.5 2.25h-13q-.07 0-.138.013q-.069.013-.134.038t-.124.062t-.11.084t-.094.103t-.072.118q-.031.062-.05.13q-.019.067-.025.136l-.365 4.132q.052-.073.12-.132t.148-.1t.167-.063T5 6.75h14q.09 0 .177.021t.167.063t.148.1t.12.132l-.365-4.132q-.006-.069-.025-.136q-.019-.068-.05-.13q-.03-.063-.072-.118q-.042-.056-.094-.103q-.051-.047-.11-.084t-.124-.062t-.134-.038t-.138-.013m1.178 5.57q-.045.097-.116.177q-.07.079-.161.136q-.09.058-.192.087q-.102.03-.209.03H5q-.107 0-.209-.03t-.192-.087t-.161-.136q-.071-.08-.116-.177L3.253 19.934q-.003.033-.003.066q0 2.25 2.25 2.25h13q2.25 0 2.25-2.25q0-.033-.003-.066z");
}

</style>
