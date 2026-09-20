<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="u3f2d07bf"/><path clip-rule="evenodd" class="yixekrj5k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rsc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u3f2d07bf {
  fill: var(--svg-color--4f53f6, #4f53f6);
  d: path("M24 0H0v24h24z");
}

.yixekrj5k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.684 4.667a.68.68 0 0 1-.685.666a.675.675 0 0 1-.684-.666c0-.37.311-.667.684-.667c.378 0 .685.298.685.667M10.666 7.11a.889.889 0 1 1-1.778 0a.889.889 0 0 1 1.778 0m3.555.89a.889.889 0 1 0 0-1.777a.889.889 0 0 0 0 1.777m-3.786 1.778a1.3 1.3 0 0 1-.373-.014c-.267-.066-.4-.133-.4-.462c0-.275.328-.418.622-.413h3.409c.262 0 .662.142.648.462c-.013.458-.64.445-.95.422a.05.05 0 0 0-.04.014a.05.05 0 0 0-.018.035v2.898q0 .092.053.178a313 313 0 0 1 3.711 5.613c.129.191.244.418.236.649c-.023.671-.61.84-1.191.84H7.848c-.369 0-.755-.053-.986-.325a.7.7 0 0 1-.178-.635q.058-.306.204-.533l1.4-2.107a600 600 0 0 0 2.329-3.52a.3.3 0 0 0 .044-.16V9.822a.04.04 0 0 0 0-.019l-.008-.016a.05.05 0 0 0-.036-.014h-.182zM9.653 16l-.014-.004l-.013-.014a.03.03 0 0 1 0-.026l1.929-2.89V9.779h.889l.004 3.289l1.92 2.889l.007.01a.03.03 0 0 1-.005.026l-.01.008z");
}

</style>
