<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGxz2vbdrA)" class="r4i437pya"/><path clip-rule="evenodd" class="jq5nvsqxo"/><path class="rymr17nbh"/></g><defs><linearGradient id="SVGxz2vbdrA" x1="5.92" x2="4.178" y1="7.651" y2="8.913" gradientUnits="userSpaceOnUse"><stop class="xv04xflyp"/><stop offset="1" class="kb-1tpocz"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:space-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jq5nvsqxo {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.057 17.425c1.326-.384 2.446-1.55 3.072-2.679a5.9 5.9 0 0 0 .676-3.337a2.3 2.3 0 0 0-.114-.526c-.027-.091.206-.402.297-.525l.028-.037q.842-1.154 1.664-2.322q.144-.184.247-.393l.06-.055q.034-.042-.02-.037q-1.465.061-2.993.178q-.502.04-1.024.032a.4.4 0 0 1-.106-.013a.1.1 0 0 1-.05-.037c-.79-1-3.602-1.71-5.284-1.243a6.04 6.04 0 0 0-3.85 3.113a5.9 5.9 0 0 0-.475 3.56c.165 1.011-.731 1.92-1.495 2.698c-.256.26-.502.503-.68.731q-.027.048.022.041q.76-.044 1.518-.114c.8-.073 1.6-.142 2.404-.137c.096 0 .16.055.215.11l.078.068a6.72 6.72 0 0 0 5.81.924m-5.531-2.761c.192.018.329.05.47.196a4.206 4.206 0 0 0 6.053-.132a4.16 4.16 0 0 0 .896-3.804c-.046-.123-.091-.26-.046-.347l.659-1.17a.04.04 0 0 0-.032-.023q-.766.068-1.312-.037c-.183-.036-.284-.146-.394-.26a4.36 4.36 0 0 0-4.068-.979c-.1.028-.187.069-.279.11l-.16.073c-1.783.69-2.706 2.597-2.436 4.389c.009.078.032.16.054.242c.05.201.106.416.037.594c-.15.388-.351.754-.599 1.088a.05.05 0 0 0 .028.046c.004.01.018.01.027.01c.38-.037.745-.033 1.106 0z");
}

.kb-1tpocz {
  stop-color: var(--svg-color--21e8ff, #21e8ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rymr17nbh {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.143 9.485a1.143 1.143 0 1 0 0-2.286a1.143 1.143 0 0 0 0 2.286");
}

.xv04xflyp {
  stop-color: var(--svg-color--3119ff, #3119ff);
}

</style>
