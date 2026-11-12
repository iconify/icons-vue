<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rsrhfac5n"/><path class="e_tokccvb"/><path class="a9thqaciu"/><path class="spd299bvi"/><path class="wnncpz6rd"/><path class="jwbtv1a5i"/><path class="zj2p4py0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-off-linear" /></template>
<style>
.a9thqaciu {
  d: path("M5.33301 12.295C7.78006 9.65377 11.2376 8.76794 14.3625 9.63754");
}

.e_tokccvb {
  d: path("M12.959 14.5085C13.8293 14.7027 14.6585 15.1642 15.3339 15.8931");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwbtv1a5i {
  d: path("M20.3213 7.14575C20.9083 7.60795 21.4698 8.12503 21.9997 8.69699");
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.spd299bvi {
  d: path("M16.7617 10.7053C17.4418 11.1355 18.0826 11.6654 18.666 12.2951");
}

.wnncpz6rd {
  d: path("M2 8.69694C6.38843 3.96024 12.9434 2.98729 18.2219 5.77811");
}

.zj2p4py0y {
  stroke-linejoin: round;
  d: path("M12.0176 19.4644H12.0177");
}

</style>
