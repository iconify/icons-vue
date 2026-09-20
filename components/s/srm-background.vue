<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="re-3l8bki"/><path class="l3dttcccm"/><path class="ni4n-rbah"/><path class="nnm24-bxv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:srm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l3dttcccm {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 17.176c-2.294 0-4.155-1.97-4.155-4.4c0-2.365 3.752-6.536 3.907-6.7l.187-.23l.185.23c.155.165 4 4.336 4 6.7c.032 2.43-1.829 4.4-4.124 4.4M11.97 6.7a25 25 0 0 0-1.706 2.168c-1.209 1.707-1.86 3.053-1.86 3.907c0 2.102 1.612 3.81 3.596 3.81c1.985 0 3.597-1.708 3.597-3.81c0-.854-.65-2.2-1.891-3.907c-.682-.953-1.396-1.774-1.737-2.168");
}

.ni4n-rbah {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 18.589c-3.038 0-5.488-2.594-5.488-5.813c0-3.12 4.124-7.486 4.31-7.684a.31.31 0 0 1 .403 0a.36.36 0 0 1 0 .427c-.062.033-4.155 4.368-4.155 7.258s2.201 5.22 4.93 5.22c2.73 0 4.93-2.33 4.93-5.22c0-1.183-.713-2.825-2.077-4.73a27 27 0 0 0-2.108-2.593c-.125-.1-.125-.296 0-.427c.093-.132.278-.132.402 0c.187.197 4.373 4.63 4.373 7.75c-.031 3.218-2.481 5.812-5.52 5.812");
}

.nnm24-bxv {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20c-3.659 0-6.666-3.185-6.666-7.06c0-1.609.775-3.58 2.263-5.878a28 28 0 0 1 2.264-2.956c.093-.131.279-.131.403 0c.124.1.124.296 0 .427c0 0-1.117 1.215-2.202 2.89c-1.426 2.168-2.17 4.072-2.17 5.55c0 3.579 2.76 6.469 6.108 6.469c3.349 0 6.109-2.956 6.109-6.502c0-1.478-.744-3.383-2.17-5.55c-1.086-1.641-2.202-2.856-2.202-2.89a.36.36 0 0 1 0-.426a.31.31 0 0 1 .403 0c.155.23 4.527 5.024 4.527 8.866C18.667 16.815 15.69 20 12 20");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.re-3l8bki {
  fill: var(--svg-color--71e0ec, #71e0ec);
  d: path("M24 0H0v24h24z");
}

</style>
