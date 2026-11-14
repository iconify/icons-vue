<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_i9wbd5a"/><path class="o-w-scbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marker-selected" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o-w-scbqh {
  d: path("M8.5 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m6.25 8.5l2 2L21 15.75");
}

.w_i9wbd5a {
  d: path("M12.333 19.407c-.501.592-.96 1.127-1.333 1.593c-2-2.5-6.5-7-6.5-11.5q0-.16.008-.319t.023-.318q.016-.159.039-.317q.024-.158.055-.314q.031-.157.07-.311q.039-.155.085-.308t.1-.303t.115-.297q.061-.148.129-.292t.144-.285q.075-.141.157-.278t.17-.269q.089-.133.184-.261t.196-.252q.102-.123.209-.241t.22-.231t.231-.22t.241-.209q.124-.101.252-.196t.261-.184q.132-.088.269-.17t.278-.157t.285-.144t.292-.129t.297-.115t.303-.1t.308-.085t.311-.07t.314-.055q.158-.023.317-.039q.159-.015.318-.023T11 3t.319.008t.318.023t.317.039t.314.055t.311.07t.308.085t.303.1t.297.115t.292.129t.285.144q.141.075.278.157t.269.17q.133.089.261.184t.252.196q.123.102.241.209t.231.22t.22.231t.209.241t.196.252t.184.261q.088.132.17.269t.157.278t.144.285t.129.292t.115.297t.1.303t.085.308t.07.311t.055.314q.023.158.039.317q.015.159.023.318t.008.319c0 1.975-.867 3.951-2.009 5.757");
}

</style>
