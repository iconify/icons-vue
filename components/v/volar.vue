<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":224};
const content = `<defs><linearGradient id="SVGw8v50d0C" x1="105.885%" x2="-.485%" y1="16.567%" y2="62.101%"><stop offset="0%" class="vl1-y-bzn"/><stop offset="100%" class="oh21bfbri"/></linearGradient><path id="SVGqSYaKbhR" class="r0t412b_q"/></defs><path fill="url(#SVGw8v50d0C)" class="e8q55zbih"/><g transform="translate(28.616 45.423)"><mask id="SVGeevAkcwP" class="n1mjunbsu"><use href="#SVGqSYaKbhR"/></mask><path mask="url(#SVGeevAkcwP)" class="r_s-dvooe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:volar" /></template>
<style>
.e8q55zbih {
  d: path("M134.247 220.01c-2.777 4.809-9.718 4.809-12.494 0L.977 10.82C-1.799 6.011 1.671 0 7.224 0h241.552c5.553 0 9.023 6.011 6.247 10.82z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.oh21bfbri {
  stop-color: var(--svg-color--3ddcff, #3ddcff);
}

.r_s-dvooe {
  fill: var(--svg-color--001aff, #001aff);
  d: path("M105.63 174.587c-2.776 4.81-9.717 4.81-12.493 0L-27.64-34.603c-2.777-4.808.694-10.82 6.247-10.82H220.16c5.553 0 9.023 6.012 6.246 10.82z");
}

.r0t412b_q {
  d: path("M110.204 12.886C71.297-14.28 21.28 8.106 0 20.072l99.384 168.085l92.185-157.935c-15.254 4.202-45.89 7.433-81.365-17.336");
}

.vl1-y-bzn {
  stop-color: var(--svg-color--7a85ec, #7a85ec);
}

</style>
