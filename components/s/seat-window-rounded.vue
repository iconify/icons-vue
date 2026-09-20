<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwdfuvbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:seat-window-rounded" /></template>
<style>
.xwdfuvbne {
  fill: currentColor;
  d: path("M14.175 9q-.28 0-.479-.163t-.279-.428l-1.27-4.384q-.106-.385.13-.705t.646-.32h5.94q.28 0 .479.163q.2.163.28.428l1.27 4.384q.106.385-.13.705t-.646.32zM5.846 7.577q-.698 0-1.195-.497t-.497-1.196t.497-1.195t1.195-.497t1.195.497t.498 1.195q0 .699-.498 1.196q-.497.497-1.195.497M6.012 20q-.69 0-1.244-.443q-.552-.443-.69-1.134L2.11 8.585q-.061-.226.092-.405T2.608 8q.179 0 .31.112q.13.11.167.284l2.011 9.989q.039.23.27.423q.23.192.461.192h5.635q.212 0 .356.144t.144.357t-.144.356t-.356.143zm8.473-2h-7.22q-.551 0-.945-.332t-.505-.845l-1.177-5.62q-.211-1.026.47-1.75q.68-.722 1.592-.722q.702 0 1.288.421t.75 1.144L9.955 16h3.711q.39 0 .726.198q.334.198.551.571l2.712 4.683q.104.177.047.382t-.232.305t-.378.043t-.303-.23z");
}

</style>
