<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pa33xpeva"/><path class="r19kgeb8t"/><g class="nn0wl0keo"><path class="i6jftekkr"/><circle class="y7hu6xjqb"/></g><path class="fswi04mvc"/><circle class="xjd7q6_jz"/><path class="blzrbo5qx"/><path class="td5ilbcfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:tape-cartridge" /></template>
<style>
.blzrbo5qx {
  fill: var(--svg-color--fff, #fff);
  d: path("M52.03 30.473a3.144 3.144 0 0 1-6.291 0a3.146 3.146 0 1 1 6.291 0");
}

.fswi04mvc {
  fill: var(--svg-color--fff, #fff);
  d: path("M24.682 30.473a4.807 4.807 0 0 1-9.612 0a4.806 4.806 0 0 1 9.612 0");
}

.i6jftekkr {
  d: path("M55.993 56.24c0 .449-.82.81-1.839.81H9.864c-1.021 0-1.841-.36-1.841-.81v-6.672c0-.447.819-.81 1.841-.81h44.29c1.019 0 1.839.362 1.839.81z");
}

.nn0wl0keo {
  fill: var(--svg-color--233335, #233335);
}

.pa33xpeva {
  fill: var(--svg-color--bcbec0, #bcbec0);
  d: path("M61 7.287h-5.914q.025.109.027.223l-3.64 6.117c-.505.982-1.306 1.749-2.912 1.749H37.887c-1.608 0-2.335-.707-2.914-1.749L31.335 7.51c0-.077.012-.15.027-.223H2.91a2.91 2.91 0 0 0-2.912 2.91v43.941a2.91 2.91 0 0 0 2.912 2.91H61a2.91 2.91 0 0 0 2.91-2.91V10.197A2.91 2.91 0 0 0 61 7.287");
}

.r19kgeb8t {
  fill: var(--svg-color--a7a9ac, #a7a9ac);
  d: path("M13.457 54.5V10.561a2.91 2.91 0 0 1 2.91-2.912h15.05l-.083-.137c0-.077.012-.15.027-.223H2.909a2.91 2.91 0 0 0-2.912 2.91V54.14a2.91 2.91 0 0 0 2.912 2.91h12.05a2.91 2.91 0 0 1-1.508-2.55M51.35 15.733h10.676c.817 0 1.426-.197 1.891-.52v-5.02a2.91 2.91 0 0 0-2.91-2.91h-5.914q.025.109.027.223l-3.64 6.117c-.393.764-.963 1.392-1.953 1.638c.452.296 1.027.469 1.823.469");
}

.td5ilbcfw {
  fill: var(--svg-color--233335, #233335);
  d: path("m21.245 17.871l27.642 4.309l1.543 1.696l-32.17-4.245z");
}

.xjd7q6_jz {
  cx: 48.886px;
  cy: 30.473px;
  r: 8.296px;
  fill: var(--svg-color--233335, #233335);
}

.y7hu6xjqb {
  cx: 19.877px;
  cy: 30.471px;
  r: 12.673px;
}

</style>
