<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="esxisibaw"/><path class="ejfpiglxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:women-bold-duotone" /></template>
<style>
.ejfpiglxl {
  fill: currentColor;
  d: path("M11.25 15.9603V17.75H9.5C9.08579 17.75 8.75 18.0858 8.75 18.5C8.75 18.9142 9.08579 19.25 9.5 19.25H11.25V22C11.25 22.4142 11.5858 22.75 12 22.75C12.4142 22.75 12.75 22.4142 12.75 22V19.25H14.5C14.9142 19.25 15.25 18.9142 15.25 18.5C15.25 18.0858 14.9142 17.75 14.5 17.75L12.75 17.75V15.9603C12.5036 15.9866 12.2534 16 12 16C11.7466 16 11.4964 15.9866 11.25 15.9603Z");
}

.esxisibaw {
  cx: 12px;
  cy: 9px;
  r: 7px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
