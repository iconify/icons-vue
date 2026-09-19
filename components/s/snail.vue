<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r-uea8bmp"/><g class="yoja4rbfy"><ellipse class="awqu09bxj"/><ellipse class="t4yjf6_hh"/><ellipse class="falvotyyb"/><ellipse class="q3abfv1pk"/></g><path class="j2_qy_b1w"/><path class="u7zl5jz4e"/><g class="d5tby4k2u"><path class="axa6mib8q"/><path class="y4ddtjjar"/></g><path class="ephd1wbis"/><path class="nt3--_13f"/><g class="xilmpyx4r"><path class="ohjqpnbbq"/><path class="k205x7ntd"/></g><path class="reyde-wlu"/><ellipse class="f4w2jsoiq"/><path class="maxw5sv6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:snail" /></template>
<style>
.awqu09bxj {
  cx: 27.8px;
  cy: 39.8px;
  rx: 3.9px;
  ry: 6.7px;
}

.axa6mib8q {
  d: path("m14.5 24.2l-2.6.9l-2.5-6.9l2.6-.9zm5.8 2.6l-2.5-1.1l3.1-6.7l2.5 1.2z");
}

.d5tby4k2u {
  fill: var(--svg-color--94d82a, #94d82a);
}

.ephd1wbis {
  fill: var(--svg-color--fcfcfa, #fcfcfa);
  d: path("M15.4 13c0 3.7-2.9 6.6-6.4 6.6c-3.6 0-6.4-3-6.4-6.6c0-3.7 2.9-6.6 6.4-6.6s6.4 3 6.4 6.6");
}

.f4w2jsoiq {
  cx: 22.7px;
  cy: 13.1px;
  fill: var(--svg-color--fcfcfa, #fcfcfa);
  rx: 7.4px;
  ry: 7.6px;
}

.falvotyyb {
  cx: 22.5px;
  cy: 48.5px;
  rx: 1.8px;
  ry: 3.1px;
}

.j2_qy_b1w {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M9.6 26.1c0 1.2.4 2.3 1.1 2.9c.3.3.7.5 1.1.7c.2.1.4.1.6.1h.7c.9 0 1.8-.3 2.5-.9s1.2-1.6 1.6-2.8c.4 1.2.4 2.6-.4 3.8s-2.3 1.9-3.7 1.9h-.5c-.2 0-.3 0-.5-.1c-.4-.1-.7-.2-1.1-.3c-.7-.3-1.3-.8-1.6-1.5c-.7-1.2-.6-2.8.2-3.8");
}

.k205x7ntd {
  d: path("M58.9 42.3c-.7.9-1.6 1.6-2.6 2.2s-2.1 1-3.4 1.1c-1.2.1-2.5-.3-3.6-1S47.4 43 46.7 42c-1.4-2-1.9-4.7-1.6-7.1s1.4-4.8 3.1-6.6c.9-.9 1.9-1.7 3.2-2.1c1.2-.5 2.6-.6 3.9-.2c1.4.4 2.5 1.4 3.1 2.5c.6 1.2.9 2.5.8 3.8s-.5 2.6-1.5 3.5c-.9 1-2.5 1.5-3.8.8s-1.9-2.1-1.6-3.4q.3-1.05 1.2-1.5c.3-.1.7-.2 1 0c.3.1.5.3.7.6c-1-.9-2 .3-2.1 1.1c-.1.9.5 1.9 1.3 2.2c.4.2.8.1 1.3 0c.4-.1.8-.4 1.1-.7c.6-.7.9-1.7.9-2.7s-.2-2-.7-2.8s-1.2-1.4-2.1-1.6c-1.8-.5-3.8.4-5.2 1.9c-2.8 2.9-3.7 7.9-1.6 11.5c1 1.8 2.7 3.3 4.8 3.4s4.3-1 6-2.3");
}

.maxw5sv6r {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M29.3 13.1c0 2.9-2.3 5.3-5.1 5.3s-5.1-2.4-5.1-5.3s2.3-5.3 5.1-5.3s5.1 2.4 5.1 5.3");
}

.nt3--_13f {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M14.6 13c0 2.5-2 4.6-4.4 4.6s-4.4-2-4.4-4.6c0-2.5 2-4.6 4.4-4.6c2.5.1 4.4 2.1 4.4 4.6");
}

.ohjqpnbbq {
  d: path("M41.1 50.7c-1.9-2.9-3.3-6.2-4-9.6c-.7-3.5-.7-7.1.1-10.6s2.5-6.9 5.3-9.3c1.4-1.2 3.1-2 4.9-2.3s3.6 0 5.2.8c-1.7-.4-3.4-.4-5 .1s-2.9 1.4-4.1 2.5c-1.1 1.1-2.1 2.5-2.8 4s-1.3 3-1.6 4.6c-.8 3.2-.9 6.6-.5 9.9c.5 3.4 1.3 6.7 2.5 9.9");
}

.q3abfv1pk {
  cx: 20.2px;
  cy: 36.4px;
  rx: 1.4px;
  ry: 2.1px;
}

.r-uea8bmp {
  fill: var(--svg-color--94d82a, #94d82a);
  d: path("M29.6 42.8S24.9 22 16.5 22C1.4 22 1 49.8 11.2 59c3.1 2.8 16.1 2.8 43.5 0c2.9-.3 1.8-3.1-2.3-5c-2.7-1.3-15.8-3.7-22.8-11.2");
}

.reyde-wlu {
  fill: var(--svg-color--94d82a, #94d82a);
  d: path("M34.3 12.7c0 5.4-4.4 9.7-9.8 9.7s-9.8-4.4-9.8-9.7c0-5.4 4.4-9.7 9.8-9.7s9.8 4.4 9.8 9.7");
}

.t4yjf6_hh {
  cx: 31.5px;
  cy: 53.4px;
  rx: 2.4px;
  ry: 2.7px;
}

.u7zl5jz4e {
  fill: var(--svg-color--e08828, #e08828);
  d: path("M58.9 42.3c3.4-4.3 3.9-11.2 2-15.4c-2.8-6.2-8.3-7.1-8.3-7.1c-7.4-11.9-27.8-11.9-34 2.7c5.3 3.1 8.3 11.8 10 16.5c1.6 6.3 4.7 12 9.8 13.5c2.2.6 2.6-1.7 2.6-1.7c1.4 2 4.3 3.4 6.9 2.7c9.7-2.8 11-11.2 11-11.2");
}

.xilmpyx4r {
  fill: var(--svg-color--93603b, #93603b);
}

.y4ddtjjar {
  d: path("M19 12.7c0 4.7-3.8 8.5-8.5 8.5S2 17.4 2 12.7s3.8-8.5 8.5-8.5c4.7.1 8.5 3.9 8.5 8.5");
}

.yoja4rbfy {
  fill: var(--svg-color--769e2a, #769e2a);
}

</style>
