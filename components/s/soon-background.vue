<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGw0S1eeAN)" class="r4i437pya"/><path class="rmriyhe0x"/></g><defs><linearGradient id="SVGw0S1eeAN" x1="4.499" x2="19.022" y1="14.87" y2="16.316" gradientUnits="userSpaceOnUse"><stop class="noctw6bft"/><stop offset=".47" class="mf8_4uqak"/><stop offset="1" class="ppr190bnu"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:soon-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mf8_4uqak {
  stop-color: var(--svg-color--c2daa8, #c2daa8);
}

.noctw6bft {
  stop-color: var(--svg-color--e3bf9f, #e3bf9f);
}

.ppr190bnu {
  stop-color: var(--svg-color--61b2c8, #61b2c8);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rmriyhe0x {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.15 4.145c-.894-.295-2.014-.15-3.47.515l-.025.01l-.02.015l-.1.06a.4.4 0 0 1-.1.03c-.125.02-.34.03-.785.03c-.45 0-1.825.02-3.2.44c-1.334.41-2.744 1.225-3.214 2.835l-.06.035c-.265.15-.485.28-.65.42c-.22.2-.34.415-.42.74c-.03.11-.05.265.015.41c.09.18.265.235.405.235c.125 0 .26-.04.385-.09c.12-.05.26-.12.41-.205a13.7 13.7 0 0 1 2.235-.35q.795-.044 1.26.085a5.7 5.7 0 0 0 1.03 2.1c.184.215.41.415.67.49c.07.02.15.036.22.04c.064 0 .164 0 .26-.055a.4.4 0 0 0 .18-.24a.6.6 0 0 0 .014-.204a2 2 0 0 0-.05-.3l-.01-.08a5 5 0 0 1-.064-.496a19 19 0 0 1-.006-1.26c3.066.51 5.29 2.055 6.705 4.645c.02.03.07.1.17.14a.31.31 0 0 0 .27-.035c.05-.035.08-.075.096-.095a.4.4 0 0 0 .034-.06c.025-.06.05-.14.065-.22c.035-.165.065-.41.085-.705c.035-.6.015-1.434-.17-2.35v-.015l-.01-.02a9.7 9.7 0 0 0-1.2-2.535a11.5 11.5 0 0 0-2-2.055l-.18-.155l.12-.135c.095-.1.2-.195.3-.29l.15-.14c.125-.08.22-.155.3-.22l.04-.035c.085-.07.18-.14.35-.22a.7.7 0 0 0 .14-.09a.35.35 0 0 0 .13-.255a.34.34 0 0 0-.134-.285a.6.6 0 0 0-.17-.085zm-11.835 7.05a.361.361 0 1 0-.715-.1c-.05.35-.1.93-.1 1.305c0 4.3 3.325 7.6 7.565 7.6c3.01 0 5.56-1.93 6.82-4.44a.355.355 0 0 0-.165-.48a.36.36 0 0 0-.485.16c-1.155 2.315-3.48 4.045-6.17 4.045A6.763 6.763 0 0 1 5.22 12.4c0-.33.05-.875.095-1.205");
}

</style>
