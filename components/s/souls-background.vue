<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGlzcg8c1t)" class="p6rvw__dh"/><path fill="url(#SVGcsaNH4Ow)" class="aqkp49pbc"/><path fill="url(#SVGu5KZwbOr)" class="tg_lhouie"/></g><defs><linearGradient id="SVGlzcg8c1t" x1="7.66" x2="12.302" y1="6.63" y2="17.8" gradientUnits="userSpaceOnUse"><stop class="ch3te8b7i"/><stop offset="1" class="p_ie96dog"/></linearGradient><linearGradient id="SVGcsaNH4Ow" x1="6.188" x2="18.017" y1="10.511" y2="16.881" gradientUnits="userSpaceOnUse"><stop class="durztpqia"/><stop offset=".55" class="y52-jv0cz"/><stop offset="1" class="mli-usb-d"/></linearGradient><linearGradient id="SVGu5KZwbOr" x1="9.719" x2="15.914" y1="8.065" y2="15.006" gradientUnits="userSpaceOnUse"><stop class="ztbpv6b4l"/><stop offset=".55" class="aphr_7b6f"/><stop offset="1" class="i4p4y4vdv"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:souls-background" /></template>
<style>
.aphr_7b6f {
  stop-color: var(--svg-color--85e7ff, #85e7ff);
}

.aqkp49pbc {
  d: path("M9.878 7.704c1.235-.942 2.08-3.05 2.08-3.704c.225.33.673 1.353.673 2.835a3.2 3.2 0 0 1-1.573 2.711c-.393.32-1.18 1.093-1.18 1.647c0 .69.435 1.225 1.28 1.225c.837 0 2.561-1.953 2.753-2.163l.005-.005c.164-.182.969-1.143 1.737-1.143c.618 0 1.162.503 1.358.755c.462.594 1.39 2.185 1.39 3.74c0 3.073-1.7 4.77-3.283 5.66c-1.262.71-3.178.778-3.978.723l1.875-1.948c.398-.315 1.184-1.079 1.184-1.614c0-.672-.347-1.207-1.34-1.207c-.987 0-1.98 1.427-2.688 2.213c-.713.791-1.358 1.043-1.619 1.043c-.256 0-1.125.137-2.135-1.83c-.805-1.572-.869-2.505-.796-2.77c0-4.015 2.712-4.998 4.257-6.173z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ch3te8b7i {
  stop-color: var(--svg-color--8976ff, #8976ff);
}

.durztpqia {
  stop-color: var(--svg-color--0ff, #0ff);
}

.ft5dv1b6b {
  fill: none;
}

.i4p4y4vdv {
  stop-color: var(--svg-color--d0f0ff, #d0f0ff);
}

.mli-usb-d {
  stop-color: var(--svg-color--78f, #78f);
}

.p_ie96dog {
  stop-color: var(--svg-color--662d91, #662d91);
}

.p6rvw__dh {
  d: path("M10.742 10.964c-.164-.503.019-1.166.128-1.436l-.832.298c-.302.84-.914 2.55-.928 2.633c-.014.082 1.17 2.62 1.76 3.878c.39-.215 1.345-.53 2.063-.078c.717.457.484 1.4.278 1.81l.714-.388c.06-.037.736-.631 1.065-.928l-1.91-5.473c-1.189.667-2.135.32-2.337-.316");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tg_lhouie {
  d: path("M7.702 10.63c.686-1.623 3.04-3.064 4.133-3.58c0 .81-2.35 3.1-2.35 4.48c0 1.372.339 1.702 1.729 1.702s2.331-1.482 2.793-1.998c.467-.517 1.194-1.084 1.82-1.084c.622 0 1.815.585 1.815 3.735c0 3.156-2.441 4.911-3.187 5.167c-.75.261-1.39-.013-.731-.343c.658-.324 1.477-1.289 1.477-2.684c0-1.399-.517-2.14-1.656-2.14c-1.143 0-2.153 1.089-2.848 1.775c-.695.69-1.463 1.76-2.172 1.76c-.713 0-1.28-.983-1.532-2.053c-.251-1.065-.142-2.698.713-4.733z");
}

.y52-jv0cz {
  stop-color: var(--svg-color--25dbff, #25dbff);
}

.ztbpv6b4l {
  stop-color: var(--svg-color--62ffff, #62ffff);
}

</style>
