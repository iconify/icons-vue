<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGgqJ0yd6B)" class="r4i437pya"/><path class="hly0anbmg"/><path clip-rule="evenodd" class="ubh98c8di"/></g><defs><linearGradient id="SVGgqJ0yd6B" x1="5.892" x2="17.586" y1="6.993" y2="17.111" gradientUnits="userSpaceOnUse"><stop class="r16g1s91z"/><stop offset=".24" class="tzu85x_zk"/><stop offset=".5" class="je9vfvbrf"/><stop offset="1" class="ey1rutbhh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:si-background" /></template>
<style>
.ey1rutbhh {
  stop-color: var(--svg-color--2ac4e6, #2ac4e6);
}

.ft5dv1b6b {
  fill: none;
}

.hly0anbmg {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.22 12.617q-.889-.375-2.117-.523a.6.6 0 0 0-.198.014a9 9 0 0 1-1.459.283c-.988.122-1.764 0-2.338-.349a1.63 1.63 0 0 1-.791-1.242c-.104-.772.141-1.365.744-1.783a3.5 3.5 0 0 1 1.134-.5c1.063-.268 2.41-.348 4.037-.23c1.148.085 2.24.235 3.285.447c.028 0 .038.019.033.047l-.043.207q-.07.404-.155.574a.66.66 0 0 1-.414.377a.9.9 0 0 1-.367 0a21.3 21.3 0 0 0-4.442-.32a10 10 0 0 0-1.035.085q-.828.112-1.055.508a.7.7 0 0 0-.033.659q.133.296.457.48c.23.131.423.22.57.277a8.6 8.6 0 0 0 1.74.41c.08.014.16.01.231-.01a10.6 10.6 0 0 1 2.085-.324c.512-.04 1.026.04 1.5.235a1.67 1.67 0 0 1 1.031 1.082c.128.452.113.861-.051 1.243c-.165.376-.452.663-.861.875q-.629.319-1.384.447a13.7 13.7 0 0 1-2.635.174a28 28 0 0 1-4.363-.485q-.032-.006-.023-.042l.028-.16q.079-.411.165-.584a.67.67 0 0 1 .437-.367a1.5 1.5 0 0 1 .575.029c.343.066.687.113 1.035.15q1.665.171 3.346.123q.541-.016 1.082-.095q1.223-.182 1.026-1.007a.8.8 0 0 0-.32-.442a2 2 0 0 0-.457-.263");
}

.je9vfvbrf {
  stop-color: var(--svg-color--8af34e, #8af34e);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r16g1s91z {
  stop-color: var(--svg-color--3d56c6, #3d56c6);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tzu85x_zk {
  stop-color: var(--svg-color--dc52f4, #dc52f4);
}

.ubh98c8di {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.941a7.06 7.06 0 1 0 0-14.12a7.06 7.06 0 0 0 0 14.12");
}

</style>
