<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6cak4bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-hand-left-off-sharp" /></template>
<style>
.t6cak4bti {
  fill: currentColor;
  d: path("M20.84 22.78L19.06 21h-6.844l3.046-3.798l-1.714-1.714l-3.852 4.845q-.275.35-.658.508q-.384.159-.815.159h-.992q-1.25 0-2.125-.875T4.23 18v-7.48l2.177-2.178l-4.785-4.784l.708-.708l19.223 19.223zM19 16.72L7.923 5.661V3H19zm-4.999-9.642q.23-.23.23-.54T14 6t-.54-.23q-.309 0-.539.23t-.23.54t.23.539q.23.23.54.23t.539-.23m-5.847 9.48l4.335-2.13l-4.335-4.34z");
}

</style>
