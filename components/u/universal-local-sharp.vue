<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d171mkqfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:universal-local-sharp" /></template>
<style>
.d171mkqfg {
  fill: currentColor;
  d: path("M3 19V5h18v14zm8.422-7.23q-.23-.23-.23-.578t.23-.577t.578-.23t.578.23t.23.577q0 .349-.23.578q-.23.23-.578.23t-.578-.23M12 16.038q1.621-1.379 2.426-2.572t.805-2.193q0-1.529-.972-2.42q-.972-.892-2.259-.892t-2.259.892t-.972 2.42q0 1 .805 2.193T12 16.04");
}

</style>
