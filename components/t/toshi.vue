<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGInWAxctY)" class="z54hpqbfo"/><path fill="url(#SVGQWJ1ydJy)" class="np69zdbdc"/><path fill="url(#SVGigpVDGQK)" class="urxjbxb7y"/><defs><linearGradient id="SVGInWAxctY" x1="3.9" x2="20.628" y1="7.31" y2="6.995" gradientUnits="userSpaceOnUse"><stop class="jadp8hbtx"/><stop offset=".43" class="nzbo6_o9j"/><stop offset=".75" class="lnkjy5but"/><stop offset=".93" class="l72ulrbnc"/><stop offset="1" class="kbtb4mb-r"/></linearGradient><linearGradient id="SVGQWJ1ydJy" x1="3" x2="9.432" y1="9.675" y2="22.03" gradientUnits="userSpaceOnUse"><stop class="x6j39p1ip"/><stop offset="1" class="qv8r1ubyt"/></linearGradient><linearGradient id="SVGigpVDGQK" x1="14.605" x2="14.605" y1="10.664" y2="19.342" gradientUnits="userSpaceOnUse"><stop class="v_pky4bfx"/><stop offset=".3" class="pbnpudxul"/><stop offset=".48" class="q6qt_ybka"/><stop offset="1" class="xdqm3bc4k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:toshi" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jadp8hbtx {
  stop-color: var(--svg-color--380d78, #380d78);
}

.kbtb4mb-r {
  stop-color: var(--svg-color--a7acc2, #a7acc2);
}

.l72ulrbnc {
  stop-color: var(--svg-color--8fd5b8, #8fd5b8);
}

.lnkjy5but {
  stop-color: var(--svg-color--7bf29e, #7bf29e);
}

.np69zdbdc {
  d: path("m7.263 15.05l.975-4.386l1.535 3.723l-.355 1.516l2.108 2.179v1.26z");
}

.nzbo6_o9j {
  stop-color: var(--svg-color--56758a, #56758a);
}

.pbnpudxul {
  stop-color: var(--svg-color--84e7ae, #84e7ae);
}

.q6qt_ybka {
  stop-color: var(--svg-color--70d78f, #70d78f);
}

.qv8r1ubyt {
  stop-color: var(--svg-color--77e397, #77e397);
}

.urxjbxb7y {
  d: path("m16.737 15.05l-.976-4.386l-1.534 3.723l.355 1.516l-2.108 2.179v1.26z");
}

.v_pky4bfx {
  stop-color: var(--svg-color--a69bd7, #a69bd7);
}

.x6j39p1ip {
  stop-color: var(--svg-color--24153e, #24153e);
}

.xdqm3bc4k {
  stop-color: var(--svg-color--3d5f5e, #3d5f5e);
}

.z54hpqbfo {
  d: path("M3 4.658v1.904l1.843 1.824l4.016 1.09v.852l1.616 3.998v1.322l1.51 1.672v.033l.015-.014l.014.014v-.033l1.511-1.672v-1.326l1.61-3.998V9.47l4.027-1.09L21 6.562V4.658l-.488 1.322l-1.355.815l-4.017.696l-3.126-.692v-.004h-.028v.004l-3.127.692l-4.016-.696l-1.355-.815z");
}

</style>
