<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGfJlvgtde)" class="r4i437pya"/><path clip-rule="evenodd" class="iw38s2ghe"/><path clip-rule="evenodd" class="uzxluhb4n"/><path class="jnea8zigt"/><path class="zuzbk6zbc"/></g><defs><linearGradient id="SVGfJlvgtde" x1="8.751" x2="15.669" y1="5.82" y2="17.968" gradientUnits="userSpaceOnUse"><stop class="oljlq8oco"/><stop offset="1" class="y77mn86yk"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vxv-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iw38s2ghe {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.722 8.23L12 4.447L5.278 8.23v7.542L12 19.551l6.721-3.78zm-6.503-4.172a.45.45 0 0 0-.439 0l-6.722 3.78a.45.45 0 0 0-.228.391v7.542c0 .162.087.311.228.39l6.722 3.781a.45.45 0 0 0 .44 0l6.721-3.78a.45.45 0 0 0 .229-.391V8.229a.45.45 0 0 0-.229-.39z");
}

.jnea8zigt {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.76 12.129l-.792-.464l1.214-.705l.765.47z");
}

.oljlq8oco {
  stop-color: var(--svg-color--dcdcdc, #dcdcdc);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.uzxluhb4n {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m12.278 17.226l4.817-8.238c.196-.336-.182-.713-.522-.52l-4.56 2.588l-4.547-2.587c-.34-.194-.719.184-.523.52l4.805 8.237a.308.308 0 0 0 .53 0m-.02-1.438l3.042-5.37c.076-.134-.075-.283-.21-.206l-3.092 1.763l.007.015l-1.853 1.056l1.573 2.744a.308.308 0 0 0 .533-.002m-2.505-3.437l1.456-.826l-2.393-1.382c-.135-.078-.288.072-.21.207z");
}

.y77mn86yk {
  stop-color: var(--svg-color--585858, #585858);
}

.zuzbk6zbc {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.73 11.248l3.176 1.83l.535-.581l-3.14-1.845z");
}

</style>
