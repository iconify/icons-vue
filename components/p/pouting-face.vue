<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="kqs4u17rs"/><path class="syoli854m"/><path class="dcfxe1bvs"/><path class="svb_ol5ln"/><path class="rmup32b4f"/><ellipse class="z3zonn88j"/><path class="ocvzl3bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:pouting-face" /></template>
<style>
.dcfxe1bvs {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M38.4 31.6c0 2.816 1.88 5.1 4.205 5.1c2.324 0 4.204-2.283 4.204-5.1s-1.88-5.1-4.204-5.1c-2.325 0-4.205 2.283-4.205 5.1");
}

.kqs4u17rs {
  cx: 31.981px;
  cy: 31.981px;
  r: 31.981px;
  fill: var(--svg-color--df394c, #df394c);
}

.ocvzl3bdg {
  fill: var(--svg-color--681624, #681624);
  d: path("M29.04 27.13c-1.882-6.693-10.438-10.232-16.815-10.304c-1.862-.021-2.287 2.886-.397 2.905c5.368.061 12.857 2.251 14.473 7.997c.513 1.821 3.246 1.203 2.739-.598m-7.612 24.573c-.63.719-.241 1.919.796 1.919c1.197 0 5.495-1.812 9.757-1.812c4.771 0 9.496 1.812 9.756 1.812c1.037 0 1.418-1.2.802-1.919c-5.718-6.593-15.403-6.593-21.11 0");
}

.rmup32b4f {
  fill: var(--svg-color--fff, #fff);
  d: path("M27.369 31.27c0 5.378-2.909 9.732-6.5 9.732s-6.5-4.354-6.5-9.732c0-5.375 2.909-9.732 6.5-9.732s6.5 4.356 6.5 9.732");
}

.svb_ol5ln {
  fill: var(--svg-color--681624, #681624);
  d: path("M34.432 27.462c1.882-6.693 10.438-10.232 16.814-10.303c1.863-.022 2.287 2.885.397 2.905c-5.368.061-12.857 2.251-14.473 7.997c-.513 1.82-3.246 1.202-2.738-.599");
}

.syoli854m {
  fill: var(--svg-color--fff, #fff);
  d: path("M36.11 31.6c0 5.378 2.909 9.732 6.5 9.732c3.59 0 6.499-4.354 6.499-9.732c0-5.376-2.909-9.733-6.499-9.733s-6.5 4.357-6.5 9.733");
}

.z3zonn88j {
  cx: 20.87px;
  cy: 31.27px;
  fill: var(--svg-color--25333a, #25333a);
  rx: 4.205px;
  ry: 5.1px;
}

</style>
