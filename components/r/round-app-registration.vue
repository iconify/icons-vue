<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="tl5jgnb6c"/><circle class="hntz4fq6i"/><circle class="nwrnq1tnm"/><circle class="kdxmgm20z"/><circle class="gos470f8k"/><path class="chwhx0bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-app-registration" /></template>
<style>
.chwhx0bmz {
  fill: currentColor;
  d: path("M11 18.07v1.43c0 .28.22.5.5.5h1.4c.13 0 .26-.05.35-.15l5.83-5.83l-2.12-2.12l-5.81 5.81c-.1.1-.15.23-.15.36M12.03 14L14 12.03V12c0-1.1-.9-2-2-2s-2 .9-2 2s.9 2 2 2zm8.82-2.44l-1.41-1.41c-.2-.2-.51-.2-.71 0l-1.06 1.06l2.12 2.12l1.06-1.06c.2-.2.2-.51 0-.71");
}

.gos470f8k {
  cx: 18px;
  cy: 6px;
  r: 2px;
  fill: currentColor;
}

.hntz4fq6i {
  cx: 6px;
  cy: 18px;
  r: 2px;
  fill: currentColor;
}

.kdxmgm20z {
  cx: 6px;
  cy: 6px;
  r: 2px;
  fill: currentColor;
}

.nwrnq1tnm {
  cx: 6px;
  cy: 12px;
  r: 2px;
  fill: currentColor;
}

.tl5jgnb6c {
  cx: 12px;
  cy: 6px;
  r: 2px;
  fill: currentColor;
}

</style>
