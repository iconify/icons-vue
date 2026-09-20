<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGzKhWQbYE)" clip-rule="evenodd" class="c8imxnemx"/></g><defs><radialGradient id="SVGzKhWQbYE" cx="0" cy="0" r="1" gradientTransform="matrix(0 8 -8 0 12 12)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="e_2-umb1f"/><stop offset=".247" class="uhpfn7b0c"/><stop offset=".344" class="mg2moo9so"/><stop offset=".488" class="i79ik-y1l"/><stop offset=".66" class="a83se-jqe"/><stop offset=".76" class="miyjgdbpq"/><stop offset=".871" class="fdjww1bxa"/><stop offset="1" class="kjqhrdxca"/></radialGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:telos-background" /></template>
<style>
.a83se-jqe {
  stop-color: var(--svg-color--954494, #954494);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.c8imxnemx {
  fill-rule: evenodd;
  d: path("M12 17.333a5.333 5.333 0 1 0 0-10.666a5.333 5.333 0 0 0 0 10.666M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.e_2-umb1f {
  stop-color: var(--svg-color--42a0b9, #42a0b9);
}

.fdjww1bxa {
  stop-color: var(--svg-color--7256ab, #7256ab);
}

.ft5dv1b6b {
  fill: none;
}

.i79ik-y1l {
  stop-color: var(--svg-color--3b74ce, #3b74ce);
}

.kjqhrdxca {
  stop-color: var(--svg-color--3d7dc7, #3d7dc7);
}

.mg2moo9so {
  stop-color: var(--svg-color--6fc68f, #6fc68f);
}

.miyjgdbpq {
  stop-color: var(--svg-color--9a4290, #9a4290);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uhpfn7b0c {
  stop-color: var(--svg-color--70c38d, #70c38d);
}

</style>
