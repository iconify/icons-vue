<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kwpve0h2z"/><g class="al7hx3ugy"><path class="im9ngcc3c"/><path class="cniid3uzs"/></g><path class="rmv1p30ti"/><path class="vi4ylqb3r"/><path class="k1ogjkbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:pen" /></template>
<style>
.al7hx3ugy {
  fill: var(--svg-color--42ade2, #42ade2);
}

.cniid3uzs {
  d: path("m9.372 46.795l19.729-19.728l7.778 7.778L17.15 54.573z");
}

.im9ngcc3c {
  d: path("m28.3 26.3l9.4 9.4l23.4-25l-7.8-7.8z");
}

.k1ogjkbwg {
  fill: var(--svg-color--c7d3d8, #c7d3d8);
  d: path("m51.953 3.748l1.414-1.414l8.344 8.344l-1.414 1.414z");
}

.kwpve0h2z {
  fill: var(--svg-color--93a2aa, #93a2aa);
  d: path("M36.6 15.1c-1.7 2.6-6.1 5.3-10 7.3c.2.2.6.8.8.8c1.1-.5 2.2-.9 3.3-1.4c2.2-1 4.4-2.3 6.4-3.8c4-3.2 5.5-12.8 8.4-13c1.7 0 3.3 2.5 4.5 3.6l1.7-1.7c.1-.1-1.3-1.4-1.4-1.5c-1.7-1.7-3.7-3.5-6.4-2.5c-3.6 1.4-5.3 9.3-7.3 12.2m9.3-10s.1 0 0 0m-1.3.2q-.15 0 0 0M2.3 60.9c-.3.4-.4.8-.2 1s.7.1 1-.2L5.5 60L4 58.5z");
}

.rmv1p30ti {
  fill: var(--svg-color--c7d3d8, #c7d3d8);
  d: path("m3.2 57.7l3.1 3.1l10.9-6.2l-7.8-7.8zm28-34.3l9.4 9.4l-2.9 2.9l-9.4-9.4z");
}

.vi4ylqb3r {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("m53.8 3.4l6.8 6.8c1.9-1.9 1.9-4.9 0-6.8s-4.9-1.9-6.8 0");
}

</style>
