<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGmyJbfcta)" class="r4i437pya"/><path class="juj2nfbsz"/></g><defs><linearGradient id="SVGmyJbfcta" x1="5.794" x2="17.461" y1="6.715" y2="18.004" gradientUnits="userSpaceOnUse"><stop class="j6m073z_r"/><stop offset="1" class="cj75hsuzg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sxp-background" /></template>
<style>
.cj75hsuzg {
  stop-color: var(--svg-color--ee8533, #ee8533);
}

.ft5dv1b6b {
  fill: none;
}

.j6m073z_r {
  stop-color: var(--svg-color--eb5756, #eb5756);
}

.juj2nfbsz {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.955 4.001q-.226 0-.46.03a3.17 3.17 0 0 0-1.899.915l-1.125 1.13l-.58.575l-.61.6l-.559.564l-.875.87l-.664.695c-.13.135-.27.26-.395.4a3.4 3.4 0 0 0-.785 2.319c-.02.37.13.85.35 1.3c.12.25.285.47.44.69c.11.15.185.15.33.034l.075-.075l.42-.435l.614-.63l.63-.67c.1-.1.21-.2.31-.31l.65-.684c.21-.22.43-.43.65-.65l.704-.74l.67-.664c.29-.29.57-.595.86-.89l.53-.53l.72-.73c.204-.21.42-.41.629-.614l1.385-1.39l.085-.1c.11-.135.12-.17-.02-.27c-.22-.155-.44-.32-.685-.435c-.44-.205-.9-.3-1.375-.3h-.02zm3.56 2.895c-.43.014-.806.15-1.085.5l-.075.07l-.75.724l-.77.77l-.64.635c-.22.22-.435.45-.66.67l-.704.684l-.845.84l-1.555 1.554l-2.059 2.06c-.13.13-.135.15 0 .285l.99 1c.2.2.445.34.725.39c.27.05.544.05.81-.026c.194-.06.38-.14.53-.285l.814-.784c.19-.18.385-.36.575-.55l1.124-1.115l.935-.9l1.275-1.244l1.2-1.165c.174-.17.34-.15.469.05c.225.365.355.76.3 1.2a1.7 1.7 0 0 1-.425.98c-.3.314-.61.61-.92.914l-.66.645l-.839.84c-.045.05-.085.1-.13.14l-.275.284l-.625.62c-.22.22-.435.45-.65.675l-.065.05l-.7.69c-.114.105-.22.215-.33.325c-.184.184-.374.37-.554.564c-.11.115-.11.185.02.275c.22.16.445.32.685.435c.45.21.915.3 1.4.3h.004a3.1 3.1 0 0 0 2.22-.81c.36-.314.684-.674 1.024-1.014l.755-.76l.71-.71c.215-.22.43-.44.65-.65c.24-.245.49-.474.734-.714c.25-.25.49-.495.73-.75a3.49 3.49 0 0 0 1.095-3a3.4 3.4 0 0 0-.52-1.359c-.15-.235-.23-.335-.69-.784c-.675-.675-1.355-1.35-2.02-2.04a1.55 1.55 0 0 0-1.229-.51");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
