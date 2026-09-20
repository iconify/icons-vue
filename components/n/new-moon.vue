<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="os1k34biv"/><g class="k2u_fybwn"><circle class="qkqe84bny"/><circle class="aq22w3bqw"/><circle class="cwptaxw_w"/><circle class="wl724qjef"/><circle class="l-elexbss"/><circle class="ho4lh1bfe"/><circle class="of3reof2o"/><circle class="g5q-qcc2j"/><circle class="ynx9hebhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:new-moon" /></template>
<style>
.aq22w3bqw {
  cx: 20px;
  cy: 16px;
  r: 3px;
}

.cwptaxw_w {
  cx: 21.5px;
  cy: 27.5px;
  r: 3.5px;
}

.g5q-qcc2j {
  cx: 32px;
  cy: 19px;
  r: 2px;
}

.ho4lh1bfe {
  cx: 30px;
  cy: 9px;
  r: 1px;
}

.k2u_fybwn {
  fill: var(--svg-color--5b6876, #5b6876);
}

.l-elexbss {
  cx: 3px;
  cy: 18px;
  r: 1px;
}

.of3reof2o {
  cx: 15px;
  cy: 31px;
  r: 1px;
}

.os1k34biv {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--66757f, #66757f);
}

.qkqe84bny {
  cx: 10.5px;
  cy: 8.5px;
  r: 3.5px;
}

.wl724qjef {
  cx: 21px;
  cy: 6px;
  r: 2px;
}

.ynx9hebhd {
  cx: 10px;
  cy: 23px;
  r: 2px;
}

</style>
