<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="u04-fwble"/><path class="xbzw7_6lh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ren-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u04-fwble {
  fill: var(--svg-color--16406e, #16406e);
  d: path("M24 0H0v24h24z");
}

.xbzw7_6lh {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.985 4L4.919 8.083v.133l2.024-1.109l.2.201h.014l1.182-.621l.14.28l4.31-2.504zm1.102.635L4.926 9.34v.2L6.95 8.357l.2.28l2.305-1.322l.14.28l4.333-2.476zm1.167.672L4.926 10.66v.134l2.024-1.11l.2.275h.007l3.414-2.018l.14.281l4.317-2.47zm1.11.639L4.918 11.917v.2l2.024-1.182l.2.28h.014l4.53-2.571l.14.207l4.31-2.46zm1.097.631L4.926 13.233v.147l2.024-1.115l.2.207h.007l5.645-3.207l.14.207l4.35-2.416zm1.097.632L4.926 14.496v.207L6.95 13.52l.2.273h.007l6.76-3.901l.14.28l4.339-2.482zm1.103.635L4.926 15.818v.134l2.024-1.109l.2.28l6.767-3.974l.14.28l5.024-2.859v-.484zM6.95 16.1l-1.116.695l-.214-.141l13.462-7.742v.916l-5.024 2.926l-.14-.28l-6.835 3.9zm7.108-2.024l-.14-.28L8.265 17l-.2-.274l-1.116.688l-.214-.067l12.345-7.168v.895zm-4.81 3.347l-1.183.627l-.006-.006l-.2-.067l11.222-6.48v.909l-5.023 2.926l-.134-.28l-4.543 2.65zm1.115.627l-1.182.628v-.013l-.214-.067l10.114-5.845v.976l-5.023 2.925l-.14-.28l-3.42 1.957zm-.073 1.323l-.207-.14l8.998-5.157v.909l-5.023 2.926l-.14-.281l-2.305 1.322l-.134-.273zm2.231-.067L11.405 20l-.14-.067l7.816-4.602v.976l-5.023 2.926l-.14-.281l-1.183.628z");
}

</style>
