<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="ck5imib7n"/><path fill="url(#SVGWTgywcDA)" class="x4gbnkbgi"/><path fill="url(#SVGWFYbYiue)" clip-rule="evenodd" class="z1g5bgbew"/></g><defs><linearGradient id="SVGWTgywcDA" x1="16.706" x2="7.294" y1="6.588" y2="17.647" gradientUnits="userSpaceOnUse"><stop class="q46w5xbaf"/><stop offset="1" class="sqeir4bkd"/></linearGradient><linearGradient id="SVGWFYbYiue" x1="14.589" x2="4.236" y1="6.353" y2="13.411" gradientUnits="userSpaceOnUse"><stop class="idq_nd_ga"/><stop offset="1" class="qc0ftvbii"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:scar-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ck5imib7n {
  fill: var(--svg-color--8c8b8a, #8c8b8a);
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.058m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.ft5dv1b6b {
  fill: none;
}

.idq_nd_ga {
  stop-color: var(--svg-color--fdfcfd, #fdfcfd);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q46w5xbaf {
  stop-color: var(--svg-color--878585, #878585);
}

.qc0ftvbii {
  stop-color: var(--svg-color--5c5b5a, #5c5b5a);
}

.sqeir4bkd {
  stop-color: var(--svg-color--010101, #010101);
}

.x4gbnkbgi {
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06");
}

.z1g5bgbew {
  fill-rule: evenodd;
  d: path("M9.177 7.294c-.565 0-.861-.626-.941-.941l1.882.47c-.08.155-.376.47-.94.47m5.647 0c-.376 0-.786-.316-.941-.47l1.882-.471c-.155.315-.564.94-.94.94m-5.176.94c-1.506 0-2.508 1.568-2.824 2.354c.565-.565 1.647-1.021 2.118-1.177C8 9.976 7.765 12 7.765 12.941l1.412 1.882V12.47c0-.235 0-1.412 2.824-1.412c2.258 0 2.823.942 2.823 1.412v2.353l1.412-1.882c0-1.694-.786-3.06-1.177-3.53c.753 0 1.728.786 2.118 1.177c-.188-1.694-2.118-2.273-3.059-2.353h-1.647v.47c0 .189-.315.391-.47.471c-.188 0-.39-.315-.47-.47v-.471zm.94 3.766c-.314 0-.94.094-.94.47h4.706c0-.155-.189-.47-.942-.47zm2.824 1.176h-3.058c.315-.155 1.082-.47 1.647-.47c.564 0 1.176.315 1.411.47m-1.411 4.941l-2.353-4.47h.94l1.413 2.823l1.411-2.823h.942zm-2.589-8l.024-.06c.122-.142.64-.175.918-.175c.315.235 1.082.706 1.647.706c.564 0 1.332-.47 1.647-.706l.706.235c-.189-.564-.706-1.176-.942-1.412c-.155.471-.658 1.412-1.411 1.412s-1.257-.94-1.412-1.412c-.537.18-.974.942-1.153 1.351a.1.1 0 0 0-.024.061");
}

</style>
