<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lyisnlb7e"/><path class="buay-r8-u"/><path class="ec5z-f3bt"/><path class="cq7r1cz2x"/><g class="zz11bubsg"><path class="ixm_dt9_l"/><path class="j3x07wb1w"/></g><g class="yq-9_bl5f"><path class="nklm2acof"/><path class="phhjntb5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:package" /></template>
<style>
.buay-r8-u {
  fill: var(--svg-color--a4805e, #a4805e);
  d: path("m58.46 15.956l-.27 28.424l-24.85 19.24l.272-28.42z");
}

.cq7r1cz2x {
  fill: var(--svg-color--8a5f3d, #8a5f3d);
  d: path("M33.612 35.2L9.224 19.783L34.07.543l24.39 15.413z");
}

.ec5z-f3bt {
  fill: var(--svg-color--c19d84, #c19d84);
  d: path("M32 33.99v28.96l1.2.67l1.04-.743l.434-28.627z");
}

.ixm_dt9_l {
  d: path("m50.16 28l-7.84 6.25l-2.16-10.09l9.08-1.15z");
}

.j3x07wb1w {
  d: path("m48.966 23.31l-5.926 4.592l-23.404-16.177l5.883-4.561z");
}

.lyisnlb7e {
  fill: var(--svg-color--8c6d53, #8c6d53);
  d: path("M33.34 63.62L8.95 48.21l.274-28.427L33.612 35.2z");
}

.nklm2acof {
  d: path("m47.27 24.627l-6.08 4.704L17.894 13.07l5.886-4.552z");
}

.phhjntb5v {
  d: path("m47.593 24.591l.887 4.826l-6.845 5l-.923-5.03z");
}

.yq-9_bl5f {
  fill: var(--svg-color--b6c9ce, #b6c9ce);
}

.zz11bubsg {
  fill: var(--svg-color--d6e8ed, #d6e8ed);
}

</style>
