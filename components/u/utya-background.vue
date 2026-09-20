<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="p39xqz5jw"/><path class="c1jpldlum"/><path class="o0j7kiupo"/><path class="nfzsmdbiy"/><path class="lzhvx6bzg"/><path class="qswr6oz0m"/><path class="qy5u3rj_q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:utya-background" /></template>
<style>
.c1jpldlum {
  fill: var(--svg-color--ffd300, #ffd300);
  d: path("M6.93 16.706c0-2.404 2.404-3.562 5.609-3.562c4.096 0 7.257 1.514 7.257 3.295c0 2.047-2.983 3.561-7.168 3.561c-3.65 0-5.698-1.247-5.698-3.294");
}

.ft5dv1b6b {
  fill: none;
}

.lzhvx6bzg {
  fill: var(--svg-color--fd4b03, #fd4b03);
  d: path("M12.272 10.384a1.85 1.85 0 0 1 1.38.846c.757 0 1.47.133 1.825.668c.134.534-.267 1.068-1.068 1.424c-.713.356-1.603.49-2.093.445c-.667 0-1.647-.178-2.27-.534c-.579-.356-.801-.89-.579-1.38c.312-.445 1.024-.623 1.692-.623c.312-.49.668-.802 1.113-.846");
}

.nfzsmdbiy {
  fill: var(--svg-color--ffd300, #ffd300);
  d: path("M12.397 4a6.313 6.313 0 1 1 0 12.625a6.313 6.313 0 1 1 0-12.625");
}

.o0j7kiupo {
  fill: var(--svg-color--ffd300, #ffd300);
  d: path("M6.663 11.898c.445.712.979 1.78 1.602 2.76c.712 1.068.178 2.67-1.068 2.315c-.713-.178-1.425-.802-1.959-1.603c-.712-1.068-1.202-2.137-.98-2.938c.268-.89 1.514-.98 2.405-.534");
}

.p39xqz5jw {
  fill: var(--svg-color--0096dd, #0096dd);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qswr6oz0m {
  fill: var(--svg-color--c41800, #c41800);
  d: path("M9.779 12.565c1.514.624 4.007.58 5.342-.044c-.133.49-.534.668-.712.801c-.713.356-1.603.49-2.093.445c-.667 0-1.647-.178-2.27-.534c-.267-.178-.356-.445-.267-.668");
}

.qy5u3rj_q {
  fill: var(--svg-color--000, #000);
  d: path("M9.868 9.048a.757.935 0 1 1 0 1.87a.757.935 0 1 1 0-1.87m4.719-.222a.757.935 0 1 1 0 1.87a.757.935 0 1 1 0-1.87");
}

</style>
