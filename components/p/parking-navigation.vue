<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w61f46jbk"/><path class="xt92dubnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parking-navigation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w61f46jbk {
  d: path("M12.227 18.676A32 32 0 0 1 11 20S4.5 13.5 4.5 9q0-.16.008-.319t.023-.318q.016-.159.039-.317q.024-.158.055-.314q.031-.157.07-.311q.039-.155.085-.308t.1-.303t.115-.297q.061-.148.129-.292t.144-.285q.075-.141.157-.278t.17-.269q.089-.133.184-.261t.196-.252q.102-.123.209-.241t.22-.231t.231-.22t.241-.209t.252-.196t.261-.184q.132-.088.269-.17t.278-.157t.285-.144t.292-.129t.297-.115t.303-.1t.308-.085t.311-.07t.314-.055t.317-.039t.318-.023T11 2.5t.319.008t.318.023t.317.039t.314.055t.311.07t.308.085t.303.1t.297.115t.292.129t.285.144q.141.075.278.157t.269.17t.261.184t.252.196q.123.102.241.209t.231.22t.22.231t.209.241t.196.252t.184.261q.088.132.17.269t.157.278t.144.285t.129.292t.115.297t.1.303t.085.308t.07.311t.055.314q.023.158.039.317q.015.159.023.318T17.5 9c0 2.098-1.413 4.631-2.921 6.737");
}

.xt92dubnj {
  d: path("M9 13V5.5h2.5a2.5 2.5 0 0 1 0 5H9m6 8h6m-2.75-2.75L21 18.5l-2.75 2.75");
}

</style>
