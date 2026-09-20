<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="v2og2eb4g"/><path class="idkm32ymh"/><circle class="bu--3-bhs"/><circle class="dc7_brbhp"/><circle class="b1-2bjl1h"/><circle class="c494ejb7y"/><circle class="j0p6cdzge"/><circle class="dd4w8hwwa"/><circle class="cdodtwbzn"/><circle class="o6wr86bln"/><circle class="y9st8ny3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:waxing-gibbous-moon" /></template>
<style>
.b1-2bjl1h {
  cx: 14.5px;
  cy: 27.5px;
  r: 3.5px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.bu--3-bhs {
  cx: 25.5px;
  cy: 8.5px;
  r: 3.5px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.c494ejb7y {
  cx: 15px;
  cy: 6px;
  r: 2px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.cdodtwbzn {
  cx: 21px;
  cy: 31px;
  r: 1px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.dc7_brbhp {
  cx: 16px;
  cy: 16px;
  r: 3px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.dd4w8hwwa {
  cx: 6px;
  cy: 9px;
  r: 1px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.idkm32ymh {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M7 18C7 9.669 11.239 2.607 17.13.044C7.596.501 0 8.353 0 18s7.594 17.498 17.128 17.956C11.238 33.391 7 26.331 7 18");
}

.j0p6cdzge {
  cx: 33px;
  cy: 18px;
  r: 1px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.o6wr86bln {
  cx: 4px;
  cy: 19px;
  r: 2px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.v2og2eb4g {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M36 18c0 9.941-8.059 18-18 18c-.294 0-.58-.029-.87-.043C11.239 33.393 7 26.332 7 18C7 9.669 11.239 2.607 17.13.044C17.42.03 17.706 0 18 0c9.941 0 18 8.059 18 18");
}

.y9st8ny3n {
  cx: 26px;
  cy: 23px;
  r: 2px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

</style>
