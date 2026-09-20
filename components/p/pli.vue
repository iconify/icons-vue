<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG8Oq7McYq)" class="od2kjzb_k"/><path fill="url(#SVGZyKsqb4I)" class="x20s81txu"/><path fill="url(#SVGl2xiyd8X)" class="j7nzf1g7p"/><path fill="url(#SVG25vEud1k)" class="xeq0nlggu"/><path fill="url(#SVGsLBAJZHm)" class="cliqvlbjd"/><path fill="url(#SVG2LVvHdFi)" class="tr4mh0bcx"/><path class="k1dekrb2q"/><path class="o1gmsdhgu"/><defs><linearGradient id="SVG8Oq7McYq" x1="5.533" x2="17.287" y1="11.998" y2="11.998" gradientUnits="userSpaceOnUse"><stop class="zxs2vo8ub"/><stop offset="1" class="dp7urk11k"/></linearGradient><linearGradient id="SVGZyKsqb4I" x1="5.201" x2="18.757" y1="5.606" y2="13.399" gradientUnits="userSpaceOnUse"><stop class="zxs2vo8ub"/><stop offset="1" class="dp7urk11k"/></linearGradient><linearGradient id="SVGl2xiyd8X" x1="5.472" x2="8.261" y1="6.803" y2="20.519" gradientUnits="userSpaceOnUse"><stop class="zxs2vo8ub"/><stop offset="1" class="dp7urk11k"/></linearGradient><linearGradient id="SVG25vEud1k" x1="18.467" x2="6.713" y1="11.998" y2="11.998" gradientUnits="userSpaceOnUse"><stop class="zxs2vo8ub"/><stop offset="1" class="dp7urk11k"/></linearGradient><linearGradient id="SVGsLBAJZHm" x1="18.799" x2="5.244" y1="5.606" y2="13.399" gradientUnits="userSpaceOnUse"><stop class="zxs2vo8ub"/><stop offset="1" class="dp7urk11k"/></linearGradient><linearGradient id="SVG2LVvHdFi" x1="18.512" x2="15.72" y1="6.803" y2="20.518" gradientUnits="userSpaceOnUse"><stop class="zxs2vo8ub"/><stop offset="1" class="dp7urk11k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pli" /></template>
<style>
.cliqvlbjd {
  d: path("M16.018 9.585a5.2 5.2 0 0 0 2.123-2.276a4.8 4.8 0 0 0-3.012.714a6.14 6.14 0 0 0-2.314 2.415c.53.031 1.917-.096 3.203-.847z");
}

.dp7urk11k {
  stop-color: var(--svg-color--ffdf1a, #ffdf1a);
}

.ft5dv1b6b {
  fill: none;
}

.j7nzf1g7p {
  d: path("M9.882 7.913a3.9 3.9 0 0 1-.45-2.266c.302.106 1.213.636 1.748 1.573c.529.942.434 1.842.402 2.213c-.334-.175-1.186-.604-1.705-1.52z");
}

.k1dekrb2q {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M3 15.705v2.647h1.588v-1.059h2.98c.986 0 1.785-1.038 1.785-2.118s-.8-2.117-1.784-2.117H4.016L3 14.646h4.257c.296 0 .508.206.508.53c0 .322-.212.529-.508.529zm8.47 2.647v-5.294h1.589v3.706h3.706l-.985 1.588z");
}

.o1gmsdhgu {
  fill: var(--svg-color--fe620d, #fe620d);
  d: path("M18.883 18.352v-5.294h1.588v5.294z");
}

.od2kjzb_k {
  d: path("M6.727 12.002A7.04 7.04 0 0 1 3 11.022c.44-.333 1.8-1 3.727-1a8.4 8.4 0 0 1 4.024 1.005a8.8 8.8 0 0 1-4.024.975");
}

.tr4mh0bcx {
  d: path("M14.118 7.913c.524-.91.497-1.937.45-2.266c-.302.106-1.213.636-1.748 1.573c-.529.942-.434 1.842-.402 2.213c.334-.175 1.186-.604 1.705-1.52z");
}

.x20s81txu {
  d: path("M7.982 9.585A5.2 5.2 0 0 1 5.86 7.31a4.8 4.8 0 0 1 3.013.714a6.13 6.13 0 0 1 2.313 2.415c-.529.031-1.916-.096-3.203-.847z");
}

.xeq0nlggu {
  d: path("M17.273 12.002a7.04 7.04 0 0 0 3.727-.98c-.44-.333-1.8-1-3.727-1a8.4 8.4 0 0 0-4.024 1.005c.561.318 2.155.975 4.024.975");
}

.zxs2vo8ub {
  stop-color: var(--svg-color--f36511, #f36511);
}

</style>
