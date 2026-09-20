<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="k5wafr62f"/><circle class="wwvhbmbrc"/><path class="z96crlb5n"/><circle class="fet5ypbbg"/><path class="xbgwkgxpy"/><path class="dcv24rb5f"/><path class="oomzy5b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:radioactive" /></template>
<style>
.dcv24rb5f {
  d: path("m58.26 53.46l-16.4-28.2a1.817 1.817 0 0 0-2.49-.61l-.01.01a47.28 47.28 0 0 0-21.9 37.8a1.88 1.88 0 0 0 1.8 1.9h32.7c.88 0 1.64-.63 1.8-1.5c.41-2.75 1.84-5.25 4-7c.69-.59.9-1.58.5-2.4");
}

.fet5ypbbg {
  cx: 64.46px;
  cy: 64.36px;
  r: 7.2px;
}

.k5wafr62f {
  cx: 64.46px;
  cy: 63.96px;
  r: 60px;
  fill: var(--svg-color--f2a600, #f2a600);
}

.oomzy5b2p {
  fill: var(--svg-color--fff, #fff);
  d: path("M24.46 29.66c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5a44.64 44.64 0 0 0-23 17.4c-2 3-5 11.3-8.7 9.2c-3.9-2.3-3.1-9.5 2.6-18.3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.wwvhbmbrc {
  cx: 60.56px;
  cy: 63.06px;
  r: 56.1px;
  fill: var(--svg-color--ffcc32, #ffcc32);
}

.xbgwkgxpy {
  fill: var(--svg-color--fff170, #fff170);
  d: path("M24.46 29.66c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5a44.64 44.64 0 0 0-23 17.4c-2 3-5 11.3-8.7 9.2c-3.9-2.3-3.1-9.5 2.6-18.3");
  opacity: var(--svg-opacity--0-65, 0.65);
}

.z96crlb5n {
  d: path("M76.96 64.36h32.7a1.88 1.88 0 0 0 1.8-1.9a46.92 46.92 0 0 0-21.8-37.8c-.83-.53-1.94-.28-2.47.55c-.01.02-.02.03-.03.05l-16.5 28.3c-.46.78-.24 1.78.5 2.3c2.16 1.75 3.59 4.25 4 7c.15.87.91 1.51 1.8 1.5m-12.5 10.8c-1.4-.01-2.79-.29-4.1-.8a1.78 1.78 0 0 0-2.2.8l-16.3 28.3c-.5.87-.2 1.98.67 2.48c.01.01.02.01.03.02a47.3 47.3 0 0 0 21.9 5.4c7.6.04 15.1-1.82 21.8-5.4c.88-.49 1.2-1.59.72-2.47c-.01-.01-.01-.02-.02-.03l-16.3-28.3a1.78 1.78 0 0 0-2.2-.8c-1.27.53-2.63.8-4 .8");
}

</style>
