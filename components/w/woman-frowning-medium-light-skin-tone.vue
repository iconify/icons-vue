<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ufal6wbyt"/><path class="wk5hybmkm"/><path class="lgw-g5bfw"/><path class="k3j-3c05w"/><path class="ztzaorepf"/><path class="vi3m1o-ff"/><path class="f0-ky2uky"/><path class="k62kjac6v"/><path class="y0wifzfpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:woman-frowning-medium-light-skin-tone" /></template>
<style>
.f0-ky2uky {
  fill: var(--svg-color--662113, #662113);
  d: path("M14 17a1 1 0 0 1-1-1v-1a1 1 0 0 1 2 0v1a1 1 0 0 1-1 1m8 0a1 1 0 0 1-1-1v-1a1 1 0 1 1 2 0v1a1 1 0 0 1-1 1");
}

.k3j-3c05w {
  fill: var(--svg-color--f3d2a2, #f3d2a2);
  d: path("M9 5v12c0 4.971 4.029 9 9 9s9-4.029 9-9V5z");
}

.k62kjac6v {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M19 20.5h-2a.5.5 0 0 1 0-1h2a.5.5 0 0 1 0 1");
}

.lgw-g5bfw {
  fill: var(--svg-color--f3d2a2, #f3d2a2);
  d: path("M15 22v6a3 3 0 1 0 6 0v-6z");
}

.ufal6wbyt {
  fill: var(--svg-color--ffe51e, #ffe51e);
  d: path("M19 0c-1.721 0-3.343.406-4.793 1.111A7 7 0 0 0 13 1a7 7 0 0 0-7 7v12h.018C6.201 26.467 11.489 31.656 18 31.656S29.799 26.467 29.982 20H30v-9c0-6.075-4.925-11-11-11");
}

.vi3m1o-ff {
  fill: var(--svg-color--7450a8, #7450a8);
  d: path("M9 32h1v4H9zm17 0h1v4h-1z");
}

.wk5hybmkm {
  fill: var(--svg-color--9268ca, #9268ca);
  d: path("M27 27H9a4 4 0 0 0-4 4v5h26v-5a4 4 0 0 0-4-4");
}

.y0wifzfpx {
  fill: var(--svg-color--df1f32, #df1f32);
  d: path("M15 24s1.001-2 3-2s3 2 3 2z");
}

.ztzaorepf {
  fill: var(--svg-color--ffe51e, #ffe51e);
  d: path("M27 4H9v1H8v6c6 0 6-6 6-6s2 7 14 7V5z");
}

</style>
