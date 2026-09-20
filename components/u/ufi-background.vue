<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGiRa5Gcpj)" class="pf4bhlb3h"/></g><defs><linearGradient id="SVGiRa5Gcpj" x1="18.812" x2="5.355" y1="16.609" y2="7.22" gradientUnits="userSpaceOnUse"><stop class="eb3dhob6x"/><stop offset=".49" class="zr29kub0k"/><stop offset="1" class="lbbflt1mw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ufi-background" /></template>
<style>
.eb3dhob6x {
  stop-color: var(--svg-color--7000ff, #7000ff);
}

.ft5dv1b6b {
  fill: none;
}

.lbbflt1mw {
  stop-color: var(--svg-color--ffbf1c, #ffbf1c);
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.pf4bhlb3h {
  d: path("m9.274 4.476l7.919 8.648l-9.429-7.923l-.385.26l9.529 7.998L6.11 6.576c-.105.11-.2.22-.3.34l10.858 6.918L4.875 8.335c-.07.13-.13.26-.195.4l11.798 5.5L4.155 10.35l-.08.44l12.273 3.87L4 12.49l.04.454l12.228 2.16l-11.858-.52c.05.15.11.305.17.45l11.668.515l-10.883.95l.3.42l10.623-.93l-9.498 2.11c.15.12.3.24.45.35l9.148-2.025l-7.799 2.84c.2.09.4.174.61.25l7.339-2.67l-5.884 3.064q.389.06.785.09l5.299-2.76l-3.9 2.735c.35-.035.69-.1 1.025-.175l3.135-2.2l-2 1.835c.595-.24 1.15-.55 1.66-.915l.64-.59l-.225.27a7.99 7.99 0 0 0 2.6-8.448l-.1 2.325l-.296-3.39c-.15-.34-.33-.665-.53-.975l.385 4.4l-1.22-5.49c-.184-.2-.38-.4-.58-.58l1.366 6.17l-2.57-7.06a7 7 0 0 0-.59-.324l2.74 7.534l-4.205-8.09c-.19-.049-.38-.089-.57-.129l4.38 8.424L11.889 4q-.262.001-.525.025l6.159 8.799l-7.789-8.5q-.234.069-.46.15");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zr29kub0k {
  stop-color: var(--svg-color--00ffd1, #00ffd1);
}

</style>
