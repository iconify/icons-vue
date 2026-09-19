<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dilah8bdb"/><path class="tb-chnxgd"/><circle class="riy14phkf"/><circle class="tnadvnpqb"/><path class="qtj3w1cir"/><circle class="xrvvu0fts"/><circle class="j13jwwbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-settings-input-svideo" /></template>
<style>
.dilah8bdb {
  fill: currentColor;
  d: path("M12 3c-4.96 0-9 4.04-9 9s4.04 9 9 9s9-4.04 9-9s-4.04-9-9-9m-7 8.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5S7.33 13 6.5 13S5 12.33 5 11.5M8.5 18c-.83 0-1.5-.67-1.5-1.5S7.67 15 8.5 15s1.5.67 1.5 1.5S9.33 18 8.5 18m2-10C9.67 8 9 7.33 9 6.5S9.67 5 10.5 5h3c.83 0 1.5.67 1.5 1.5S14.33 8 13.5 8zm5 10c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5m2-5c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.j13jwwbjy {
  cx: 8.5px;
  cy: 16.5px;
  r: 1.5px;
  fill: currentColor;
}

.qtj3w1cir {
  fill: currentColor;
  d: path("M12 1C5.93 1 1 5.93 1 12s4.93 11 11 11s11-4.93 11-11S18.07 1 12 1m0 20c-4.96 0-9-4.04-9-9s4.04-9 9-9s9 4.04 9 9s-4.04 9-9 9");
}

.riy14phkf {
  cx: 15.5px;
  cy: 16.5px;
  r: 1.5px;
  fill: currentColor;
}

.tb-chnxgd {
  fill: currentColor;
  d: path("M15 6.5c0-.83-.67-1.5-1.5-1.5h-3C9.67 5 9 5.67 9 6.5S9.67 8 10.5 8h3c.83 0 1.5-.67 1.5-1.5");
}

.tnadvnpqb {
  cx: 17.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: currentColor;
}

.xrvvu0fts {
  cx: 6.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
