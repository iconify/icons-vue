<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skhf5d_4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:view-orthographic" /></template>
<style>
.skhf5d_4b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.509 2.916l6.375 3.187q.561.28.953.665q-.09.02-.172.061L12 11.161L3.335 6.829q-.082-.041-.172-.061q.392-.385.953-.665l6.375-3.187q1.509-.755 3.018 0m7.826 5.255q.145-.072.247-.198q.168.523.168 1.149v5.756q0 2.086-1.866 3.019l-6.375 3.187q-.435.218-.871.31q.112-.181.112-.394v-8.536zM11.25 12.464L2.665 8.171q-.145-.072-.247-.198q-.168.523-.168 1.149v5.756q0 2.086 1.866 3.019l6.375 3.187q.435.218.871.31q-.112-.181-.112-.394z");
}

</style>
