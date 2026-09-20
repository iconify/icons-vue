<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":130};
const content = `<defs><linearGradient id="svgIDa" x1="-.012%" x2="100.007%" y1="50.013%" y2="50.013%"><stop offset="0%" class="b7w8gca9p"/><stop offset="9.192%" class="sfh9dkteq"/><stop offset="71.69%" class="poox_p50c"/><stop offset="100%" class="xli__uk6j"/></linearGradient><linearGradient id="svgIDb" x1="-3.884%" x2="83.237%" y1="172.005%" y2="-50.934%"><stop offset="0%" class="p-ihkibev"/><stop offset="49.43%" class="ewd7fw_8f"/><stop offset="81.9%" class="s2box9fsb"/><stop offset="100%" class="g1iz22zpg"/></linearGradient></defs><path fill="url(#svgIDa)" class="aj_dilbfq"/><path fill="url(#svgIDb)" class="s92nbubup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:torus" /></template>
<style>
.aj_dilbfq {
  d: path("M128 0C81.6 0 41 12.5 18.5 31.3c.1.5-.4 1.5-.2 2C20.9 45.7 32 57 48.8 65.4c.4.2 1.5-.4 2-.2c1.9-1.3 25.6-16.9 77.2-16.9c51.3 0 75.2 15.4 77.3 16.9c.4-.2 1.4.2 1.8.1c17.1-8.5 28.4-19.8 30.8-32.2c.1-.4-.5-1.2-.4-1.6C215 12.5 174.4 0 128 0");
}

.b7w8gca9p {
  stop-color: var(--svg-color--a34cb4, #A34CB4);
}

.ewd7fw_8f {
  stop-color: var(--svg-color--fe744a, #FE744A);
}

.g1iz22zpg {
  stop-color: var(--svg-color--fddf31, #FDDF31);
}

.p-ihkibev {
  stop-color: var(--svg-color--ff0264, #FF0264);
}

.poox_p50c {
  stop-color: var(--svg-color--3c52a1, #3C52A1);
}

.s2box9fsb {
  stop-color: var(--svg-color--fdbc39, #FDBC39);
}

.s92nbubup {
  d: path("M237.5 31.3c-4.3 27.6-51.7 49.3-109.5 49.3S22.8 58.9 18.5 31.3C6.8 41.1 0 52.6 0 64.9c0 35.8 57.3 64.9 128 64.9s128-29.1 128-64.9c0-12.3-6.8-23.8-18.5-33.6");
}

.sfh9dkteq {
  stop-color: var(--svg-color--954db2, #954DB2);
}

.xli__uk6j {
  stop-color: var(--svg-color--19549b, #19549B);
}

</style>
