<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wwvdswbyz"/><path class="i-hgxybuk"/><path class="cwkz_mb-l"/><path class="y8_ym_3it"/><g class="hq2-vcghy"><path class="y_u8jbj0f"/><circle class="vo_j_erkk"/></g><g class="n1mjunbsu"><path class="h_3t19g4g"/><path class="h9ektdbex"/></g><path class="kf43b1bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:rescue-workers-helmet" /></template>
<style>
.cwkz_mb-l {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M50 28h7c-1.2-9.6-8.5-17.5-18-20c5.8 3.3 10.1 10.9 11 20M25 8C15.5 10.5 8.2 18.4 7 28h7c.9-9.1 5.2-16.7 11-20");
}

.h_3t19g4g {
  d: path("M30 9h4v16h-4z");
}

.h9ektdbex {
  d: path("M24 15h16v4H24z");
}

.hq2-vcghy {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

.i-hgxybuk {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 4C16.5 4 4 16.5 4 32h56C60 16.5 47.5 4 32 4");
}

.kf43b1bqk {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M4 32h4v4H4zm52 0h4v4h-4z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.vo_j_erkk {
  cx: 32px;
  cy: 5px;
  r: 5px;
}

.wwvdswbyz {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M32 64C16.6 64 4 51.4 4 36v-4h4v4c0 13.2 10.8 24 24 24s24-10.8 24-24v-4h4v4c0 15.4-12.6 28-28 28");
}

.y_u8jbj0f {
  d: path("M58 26H6l-6 6h64z");
}

.y8_ym_3it {
  fill: var(--svg-color--594640, #594640);
  d: path("M14.7 28c.9-9 4.9-16.5 10.3-20c-7.3 3.6-12.7 11.1-14 20zm34.6 0c-1-9-4.9-16.5-10.3-20c7.3 3.6 12.7 11.1 14 20z");
}

</style>
