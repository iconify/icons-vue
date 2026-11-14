<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxbg9wbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:role-editor" /></template>
<style>
.hxbg9wbmk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.818 5.068Q4.5 6.386 4.5 8.25t1.318 3.182T9 12.75t3.182-1.318T13.5 8.25t-1.318-3.182T9 3.75T5.818 5.068M3.5 21.75q-1.75 0-1.75-1.75q0-2.427 2.213-4.015Q6.03 14.5 9 14.5q2.094 0 3.614.844q.088.049.16.119t.122.157t.078.183Q13 15.9 13 16v5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014zm10.881-1.843l.061-.489q.095-.766.642-1.312l2.761-2.761q.582-.583 1.405-.583t1.406.583t.582 1.405t-.583 1.406l-2.761 2.76q-.546.547-1.312.642l-.489.061q-.744.093-1.275-.437q-.53-.531-.437-1.275");
}

</style>
