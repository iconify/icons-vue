<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw770wiyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:variable-rate-mortgage" /></template>
<style>
.yw770wiyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm11.469 6.897q-.016-.086-.039-.17q-.022-.084-.052-.166t-.067-.16q-.037-.079-.081-.155q-.044-.075-.094-.146q-.05-.072-.106-.138t-.118-.129q-.062-.061-.129-.117q-.066-.056-.138-.106q-.071-.05-.147-.093q-.075-.044-.154-.08t-.161-.067q-.082-.03-.166-.052q-.085-.023-.17-.038t-.173-.022q-.087-.008-.174-.008q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194t-.01.196t.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01l.072-.001M3 15L15 3m1 18.5V15m-1.5 1.5L16 15l1.5 1.5M20 15v6.5M18.5 20l1.5 1.5l1.5-1.5");
}

</style>
