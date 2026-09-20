<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="eh6t7yo8h"/><path fill="url(#SVGQPzsMdtA)" class="dbkvujb1h"/></g><defs><linearGradient id="SVGQPzsMdtA" x1="3.991" x2="20" y1="8.613" y2="8.613" gradientUnits="userSpaceOnUse"><stop class="zyonc-b7m"/><stop offset="1" class="fjy_msbkq"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:phonon-background" /></template>
<style>
.dbkvujb1h {
  d: path("M9.333 17.716c1.023.253 2.08-.303 2.356-1.245l2.978-10.187c-1.023-.253-2.08.303-2.356 1.245zm-.546-2.125a1.734 1.734 0 0 1-2.12 1.236l1.88-7.085a1.733 1.733 0 0 1 2.12-1.235zm6.666-.889a1.734 1.734 0 0 1-2.12 1.236l1.88-7.085a1.73 1.73 0 0 1 2.12-1.235zm3.645-3.067c-.254.903-1.245 1.436-2.21 1.196l.899-3.133c.258-.903 1.249-1.436 2.213-1.196l-.898 3.133zM4 15.498c.964.24 1.956-.294 2.213-1.196l.898-3.133c-.964-.24-1.955.293-2.213 1.195z");
}

.eh6t7yo8h {
  fill: var(--svg-color--4d4d4d, #4d4d4d);
  d: path("m16.152 9.595l.737 3.223l1.143-2.334l-.698-2.866zm-10.156 3.84l.671 3.378l1.125-2.591l-.68-3.049l-1.116 2.267zm3.338 4.28l.782-.066l.551-2.41V8.507l-1.333 2.956zm4-1.777l.782-.578l.551-2.4V6.284l-1.333 2.89z");
}

.fjy_msbkq {
  stop-color: var(--svg-color--00e2b0, #00e2b0);
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zyonc-b7m {
  stop-color: var(--svg-color--f8a8fd, #f8a8fd);
}

</style>
