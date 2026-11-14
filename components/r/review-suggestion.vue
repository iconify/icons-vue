<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xed7gccuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:review-suggestion" /></template>
<style>
.xed7gccuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.675 16.5H7.5V15c-2.5-1.5-4-4-4-6.5q0-.16.008-.319t.023-.318t.039-.317t.055-.314q.031-.157.07-.311q.039-.155.085-.308t.1-.303t.115-.297q.061-.148.129-.292t.144-.285q.075-.141.157-.278t.17-.269q.089-.133.184-.261t.196-.252q.102-.123.209-.241t.22-.231t.231-.22t.241-.209t.252-.196t.261-.184q.132-.088.269-.17t.278-.157t.285-.144t.292-.129t.297-.115q.15-.054.303-.1t.308-.085q.154-.039.311-.07q.156-.031.314-.055q.158-.023.317-.039q.159-.015.318-.023T10 2t.319.008t.318.023t.317.039t.314.055t.311.07t.308.085t.303.1t.297.115t.292.129t.285.144q.141.075.278.157t.269.17t.261.184t.252.196q.123.102.241.209t.231.22t.22.231t.209.241t.196.252t.184.261q.088.132.17.269t.157.278q.076.141.144.285t.129.292t.115.297q.054.15.1.303t.085.308t.07.311t.055.314t.039.317t.023.318t.008.319c0 .765-.141 1.531-.407 2.267m-3.17 3.963a10 10 0 0 1-.423.27v.325M8 19.5h3.6m4.9-5L14 18l2.5 3.5m3-7L22 18l-2.5 3.5");
}

</style>
