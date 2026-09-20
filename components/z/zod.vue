<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":212};
const content = `<defs><linearGradient id="SVGTCJdNcNT" x1="50%" x2="50%" y1="100.031%" y2="0%"><stop offset="0%" class="x2mqe2bve"/><stop offset="100%" class="q2w6o2bhk"/></linearGradient><linearGradient id="SVGqyapbcsQ" x1="95.049%" x2="10.721%" y1="28.918%" y2="71.593%"><stop offset="0%" class="tb9i-5hiz"/><stop offset="30.534%" class="dc3q4xxrc"/><stop offset="100%" class="bmqf4y-5r"/></linearGradient><linearGradient id="SVGuMsE9bbK" x1="78.289%" x2="50%" y1="50%" y2="50%"><stop offset="0%" class="tb9i-5hiz"/><stop offset="100%" class="vc--wpv5i"/></linearGradient><path id="SVGZ3NJAdRW" class="dq_yyeb5x"/></defs><path fill="url(#SVGTCJdNcNT)" class="zcv_fnbbh"/><path fill="url(#SVGqyapbcsQ)" class="g4pppsbdl"/><path class="xmdmf_6yb"/><use fill="url(#SVGuMsE9bbK)" href="#SVGZ3NJAdRW"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:zod" /></template>
<style>
.bmqf4y-5r {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.4;
}

.dc3q4xxrc {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.595;
}

.dq_yyeb5x {
  d: path("M137.011 180.305a12.87 12.87 0 0 1-17 .065l-61.216-53.41h138.408z");
}

.g4pppsbdl {
  d: path("M225.397 68.751a13.695 13.695 0 0 1-5.242 16.002L98.71 161.785L58.795 126.96l153.889-93.535z");
}

.q2w6o2bhk {
  stop-color: var(--svg-color--45a9ff, #45a9ff);
}

.tb9i-5hiz {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.6;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.x2mqe2bve {
  stop-color: var(--svg-color--4669f6, #4669f6);
}

.xmdmf_6yb {
  fill: var(--svg-color--fff, #fff);
  d: path("m212.169 31.997l12.922 35.901H30.786l13.092-35.957A16.38 16.38 0 0 1 59.14 21.167h137.495a16.38 16.38 0 0 1 15.533 10.83");
}

.zcv_fnbbh {
  d: path("M50.087 0a23.97 23.97 0 0 0-22.526 15.772L1.447 87.494a23.97 23.97 0 0 0 6.828 26.32l105.542 91.458c9.088 7.876 22.606 7.799 31.604-.18l102.51-90.89a23.97 23.97 0 0 0 6.652-26.055l-26.02-72.292A23.97 23.97 0 0 0 206.007 0z");
}

</style>
