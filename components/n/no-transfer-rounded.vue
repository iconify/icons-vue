<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_qmf5_op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-transfer-rounded" /></template>
<style>
.b_qmf5_op {
  fill: currentColor;
  d: path("M7.77 18v1.385q0 .26-.179.437q-.178.178-.437.178q-.26 0-.438-.178t-.178-.437v-1.781q-.488-.212-1.013-.901T5 15.115V6.421L2.408 3.83q-.146-.146-.156-.347t.156-.366t.357-.166t.356.166l18.193 18.192q.146.146.155.344t-.155.364t-.357.165t-.357-.165l-4.53-4.525h1.426v1.876q0 .266-.183.45q-.184.183-.45.183q-.265 0-.449-.184q-.183-.183-.183-.449V18zm10.205-2.842l-3.133-3.133q-.292-.292-.133-.659q.158-.366.562-.366H18V6.539h-7.973q-.323 0-.628-.131t-.522-.348L7.439 4.62q-.298-.298-.196-.714q.103-.416.507-.528q.823-.217 1.876-.298T12 3q3.762 0 5.38.694T19 6v8.729q0 .404-.366.562q-.367.159-.659-.133m-8.682.135q.322-.322.322-.793t-.322-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323M6 11h3.579L6 7.421z");
}

</style>
