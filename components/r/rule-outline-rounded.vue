<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oab0d8bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rule-outline-rounded" /></template>
<style>
.oab0d8bio {
  fill: currentColor;
  d: path("m16.712 16.4l-2.266 2.266q-.14.14-.334.13q-.195-.01-.335-.15t-.14-.344t.14-.344l2.246-2.246l-2.265-2.266q-.14-.14-.131-.344t.15-.344t.344-.14t.344.14l2.247 2.265l2.265-2.265q.14-.14.344-.14t.344.14t.14.344t-.14.344L17.4 15.712l2.266 2.265q.14.14.14.335t-.14.334t-.345.14t-.344-.14zm-.631-7.129l3.896-3.896q.146-.146.354-.153t.354.159q.14.146.14.353q0 .208-.14.354l-4.014 4.02q-.242.242-.565.242t-.566-.242l-1.938-1.939q-.14-.14-.13-.344q.009-.204.15-.344t.344-.14t.344.14zM3.5 15.116h7q.214 0 .357.143t.143.357t-.143.356t-.357.144h-7q-.213 0-.357-.144Q3 15.829 3 15.616q0-.214.143-.357t.357-.143m0-7.231h7q.214 0 .357.143t.143.357t-.143.356t-.357.144h-7q-.213 0-.357-.144T3 8.385t.143-.357q.144-.144.357-.144");
}

</style>
