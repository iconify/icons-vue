<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="n8hgs9bpc"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rocket-vertical-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n8hgs9bpc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M16.1186 11.4966C16.1083 11.7974 16.0867 12.0978 16.0539 12.397L9.2143 5.5575C9.2592 5.4703 9.3052 5.3837 9.3523 5.2976L8.4748 4.818C9.2127 3.468 10.1834 2.259 11.3421 1.2468C11.5243 1.0876 11.758 0.9999 12 0.9999C12.242 0.9999 12.4757 1.0876 12.6579 1.2468C15.4969 3.7271 17.1257 7.313 17.1257 11.0828C17.1257 11.2321 17.1231 11.3814 17.118 11.5307L16.1186 11.4966ZM7.3886 15.194L6.2355 16.3471L8.2083 19.9755L7.3886 15.194ZM15.7917 19.9756L17.1242 17.525L18.8812 18.4804L16.7077 22.4777C16.5327 22.7996 16.1956 23 15.8292 23C15.564 23 15.3096 22.8946 15.1221 22.7071L14.2206 21.8056L9.7794 21.8056L8.8779 22.7071C8.6904 22.8946 8.436 23 8.1708 23C7.8044 23 7.4673 22.7996 7.2923 22.4777L4.1215 16.6461C4.0418 16.4995 4 16.3353 4 16.1684C4 15.9032 4.1054 15.6488 4.2929 15.4613L6.9838 12.7703C6.9109 12.2107 6.8743 11.647 6.8743 11.0826C6.8743 10.0378 6.9997 8.9967 7.2477 7.9817L9.1905 8.4565C9.1416 8.6566 9.0983 8.8581 9.0606 9.0606L15.5378 15.5379L16.5235 15.7069L15.7917 19.9756Z");
  stroke: none;
}

</style>
