<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vctw93b8d"/><path class="wk5hybmkm"/><path class="m7dafn76w"/><path class="y10rjqbxs"/><path class="z_q53wbhs"/><path class="vi3m1o-ff"/><circle class="lmtmxub8g"/><path class="avngatdzd"/><path class="el51r6xpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:woman-pouting-medium-dark-skin-tone" /></template>
<style>
.avngatdzd {
  fill: var(--svg-color--60352a, #60352a);
  d: path("M14 16a1 1 0 0 1-1-1v-1a1 1 0 0 1 2 0v1a1 1 0 0 1-1 1m8 0a1 1 0 0 1-1-1v-1a1 1 0 1 1 2 0v1a1 1 0 0 1-1 1");
}

.el51r6xpk {
  fill: var(--svg-color--915a34, #915a34);
  d: path("M19 19.5h-2a.5.5 0 0 1 0-1h2a.5.5 0 0 1 0 1");
}

.lmtmxub8g {
  cx: 18px;
  cy: 23px;
  r: 1px;
  fill: var(--svg-color--df1f32, #df1f32);
}

.m7dafn76w {
  fill: var(--svg-color--af7e57, #af7e57);
  d: path("M15 22v6a3 3 0 1 0 6 0v-6z");
}

.vctw93b8d {
  fill: var(--svg-color--60352a, #60352a);
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

.y10rjqbxs {
  fill: var(--svg-color--af7e57, #af7e57);
  d: path("M9 5v12c0 4.971 4.029 9 9 9s9-4.029 9-9V5z");
}

.z_q53wbhs {
  fill: var(--svg-color--60352a, #60352a);
  d: path("M27.999 5L26 4H8v7c6 0 6-6 6-6s2 7 14 7z");
}

</style>
