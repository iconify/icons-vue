<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi5eyvbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:send-square" /></template>
<style>
.fi5eyvbxn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.625 2.75h4.75q2.848 0 4.861 2.014t2.014 4.861v4.75q0 2.848-2.014 4.861t-4.861 2.014h-4.75q-2.848 0-4.861-2.014T2.75 14.375v-4.75q0-2.848 2.014-4.861T9.625 2.75m5.48 7.205L16.28 8.78q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094l-1.175 1.175q-.826-.441-1.823-.041L9.529 9.931q-.904.361-.944 1.333q-.041.972.83 1.407l1.053.526q.223.112.335.335l.526 1.053q.435.871 1.407.83q.972-.04 1.333-.944l1.077-2.692q.4-.998-.041-1.824");
}

</style>
