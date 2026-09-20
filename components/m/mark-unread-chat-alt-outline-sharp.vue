<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp4t71imn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-unread-chat-alt-outline-sharp" /></template>
<style>
.kp4t71imn {
  fill: currentColor;
  d: path("M6.5 13.5h7v-1h-7zm0-3h11v-1h-11zm0-3h9.942v-.023q-.367-.18-.639-.418t-.495-.559H6.5zM3 20.077V3h11.6q-.061.25-.071.49t-.006.51H4v13.644L5.65 16H20V8.342q.287-.067.527-.155q.24-.087.473-.225V17H6.077zM4 4.616v12.769V4zm13.23 1.117q-.73-.728-.73-1.77t.729-1.77t1.769-.731t1.771.728t.731 1.77t-.728 1.77t-1.77.732t-1.771-.729");
}

</style>
