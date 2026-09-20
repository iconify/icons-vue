<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="avfd7xbix"/><path class="tvse-9b4a"/><path class="km43hbbfr"/><path class="b2iu3cb9v"/><path class="o_s0uzbis"/><path class="l14f79bbw"/><path class="ndr-znbxk"/><path class="k6glzgm7s"/><path class="xl2_4vb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:snowman-without-snow" /></template>
<style>
.avfd7xbix {
  cx: 18px;
  cy: 26px;
  r: 10px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

.b2iu3cb9v {
  fill: var(--svg-color--231f20, #231f20);
  d: path("M25 7a1 1 0 0 1-1 1H12a1 1 0 0 1 0-2h12a1 1 0 0 1 1 1");
}

.k6glzgm7s {
  fill: var(--svg-color--414042, #414042);
  d: path("M16 10a1 1 0 1 1-2 0a1 1 0 0 1 2 0m6 0a1 1 0 1 1-2 0a1 1 0 1 1 2 0");
}

.km43hbbfr {
  fill: var(--svg-color--414042, #414042);
  d: path("M23 6a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2V2a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2z");
}

.l14f79bbw {
  fill: var(--svg-color--414042, #414042);
  d: path("M19 24a1 1 0 1 1-1.998.002A1 1 0 0 1 19 24m0 5a1 1 0 1 1-1.998.002A1 1 0 0 1 19 29");
}

.ndr-znbxk {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M19 12a1 1 0 1 1-1.998.002A1 1 0 0 1 19 12");
}

.o_s0uzbis {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M22.5 15h-9a1.495 1.495 0 0 0-.5 2.908V25a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-7h6.5a1.5 1.5 0 1 0 0-3");
}

.tvse-9b4a {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M12 11a6 6 0 1 1 12 0a6 6 0 0 1-12 0");
}

.xl2_4vb5z {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("m10.394 20.081l-3.452-1.479l-.547-2.866a1 1 0 0 0-1.965.375l.294 1.54l-1.33-.57a.999.999 0 1 0-.788 1.838l.743.318l-1.056 1.056a.999.999 0 1 0 1.414 1.414l1.621-1.621l4.278 1.833a.999.999 0 1 0 .788-1.838m22.922-3.03l-1.465-.488l.855-.855a.999.999 0 1 0-1.414-1.414l-.751.751l-.572-2.287a.999.999 0 1 0-1.939.486l.862 3.45l-3.6 3.6a.999.999 0 1 0 1.415 1.413l3.563-3.563l2.413.805q.16.052.317.051a.999.999 0 0 0 .316-1.949");
}

</style>
