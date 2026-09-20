<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGa5NnB0UA)" class="r4i437pya"/><path clip-rule="evenodd" class="nza6o4bqa"/></g><defs><linearGradient id="SVGa5NnB0UA" x1="9.176" x2="16.47" y1="5.177" y2="18.117" gradientUnits="userSpaceOnUse"><stop class="gpf-2w8wt"/><stop offset=".29" class="qm22leivd"/><stop offset=".74" class="fw9rmq_4v"/><stop offset="1" class="ixtlykb5l"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sphere-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fw9rmq_4v {
  stop-color: var(--svg-color--cd26b5, #cd26b5);
}

.gpf-2w8wt {
  stop-color: var(--svg-color--f9cb32, #f9cb32);
}

.ixtlykb5l {
  stop-color: var(--svg-color--13b3eb, #13b3eb);
}

.nza6o4bqa {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20c-4.452 0-8-3.294-8-7.53C4 8.02 7.294 4 12 4c4.428 0 8.155 3.878 7.995 8.296C20.122 16.508 16.028 20 12 20m-2.353-2.353c-.819-.005-2.372-.4-2.372-.4a6.98 6.98 0 0 0 8.452.724a1.31 1.31 0 0 0 .659-1.247c-.08-.658-.66-1.43-1.327-1.43c-.57 0-1.083.4-1.52.739c-.104.08-.203.16-.302.226c-1.12.8-2.192 1.397-3.59 1.388m7.708-1.082c.894-1.036 1.704-2.212 1.704-3.624c0-.988-.015-2.042-.306-2.998c-.165.88-1.106 1.586-2.047 1.586c-1.177 0-2.01-.659-2.494-1.482c-.975-1.656-2.367-2.767-4.33-2.753c-2.894.024-4.94 2.353-4.94 5.176c0 2.509 2.314 4.273 4.705 4.236c1.412-.024 2.499-.8 3.605-1.605c.503-.372 1.162-.748 1.807-.748c1.072 0 2.117 1.223 2.296 2.211m-2.376-7.06c.306.532.786 1.083 1.727 1.083c1.882 0 .94-3.092-.25-4.061A7.4 7.4 0 0 0 12 4.927c-1.685-.019-3.595.857-4.701 1.807c-.085.07-.076.09.028.047a6.6 6.6 0 0 1 2.555-.428c2.278.052 3.953 1.205 5.097 3.158zM8.235 11.53a.941.941 0 1 0 0-1.882a.941.941 0 0 0 0 1.882m0 .941a1.88 1.88 0 0 0 1.883-1.882a1.882 1.882 0 1 1-1.883 1.882m0-3.764a1.88 1.88 0 0 1 1.638.95l.245-.009a2.824 2.824 0 1 1-2.815 2.579a1.882 1.882 0 0 1 .932-3.52");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qm22leivd {
  stop-color: var(--svg-color--ea1881, #ea1881);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
