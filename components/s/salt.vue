<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="hfyubhbzx"/><path fill="url(#itKu8ne)" class="u2ur8o6zf"/><path fill="url(#iwoqx5b)" class="u2ur8o6zf"/><path fill="url(#idtwnjc)" class="u2ur8o6zf"/><path fill="url(#ituB6Od)" class="ja7fmvvgv"/><path fill="url(#iFhIBHb)" class="ja7fmvvgv"/><path fill="url(#iHOcJqe)" class="ja7fmvvgv"/><path fill="url(#iRzBR0b)" class="xeif48lyt"/><path fill="url(#iAIOtec)" class="xeif48lyt"/><path fill="url(#iH1w5Kd)" class="xeif48lyt"/><path fill="url(#ic4KCzd)" class="xeif48lyt"/><path fill="url(#ig9xQnb)" class="xeif48lyt"/><path fill="url(#ilFaMpe)" class="xeif48lyt"/><path fill="url(#iBIH8uD)" class="hv3q1gb4f"/><path fill="url(#i4gifUc)" class="hv3q1gb4f"/><path fill="url(#ivLywQb)" class="evw9lrb2c"/><path fill="url(#iaB3Lfe)" class="frurhebat"/><path fill="url(#iyhFCKc)" class="qs671pi4g"/><path fill="url(#iRi3lKd)" class="q88m2rbqg"/><path fill="url(#i3dEkac)" class="wk1yj_btb"/><path fill="url(#iBoo1Gj)" class="qmodwfave"/><defs><linearGradient id="iwoqx5b" x1="23.438" x2="20.938" y1="18.813" y2="19.25" gradientUnits="userSpaceOnUse"><stop offset=".267" class="gs652endz"/><stop offset=".66" class="jmq0vfawt"/></linearGradient><linearGradient id="idtwnjc" x1="8.938" x2="11.313" y1="18.188" y2="18.625" gradientUnits="userSpaceOnUse"><stop offset=".329" class="lel4g8bgd"/><stop offset=".703" class="jmq0vfawt"/></linearGradient><linearGradient id="ituB6Od" x1="10.488" x2="21.528" y1="11.35" y2="11.35" gradientUnits="userSpaceOnUse"><stop class="re37s34-s"/><stop offset=".086" class="lxiwh0bka"/><stop offset=".375" class="zk2f58bry"/><stop offset=".703" class="aufjqh7sx"/><stop offset=".913" class="g51ftqbre"/><stop offset="1" class="hewo_90ja"/></linearGradient><linearGradient id="iFhIBHb" x1="16.008" x2="16.008" y1="7.58" y2="11.35" gradientUnits="userSpaceOnUse"><stop class="ul6-snb8k"/><stop offset=".128" class="a82ynac9n"/></linearGradient><linearGradient id="iHOcJqe" x1="16.008" x2="16.008" y1="11.35" y2="9.465" gradientUnits="userSpaceOnUse"><stop class="ul6-snb8k"/><stop offset=".128" class="a82ynac9n"/></linearGradient><linearGradient id="iRzBR0b" x1="8.85" x2="23.155" y1="7.58" y2="7.58" gradientUnits="userSpaceOnUse"><stop class="husvxkx4k"/><stop offset="1" class="srrrmmbue"/></linearGradient><linearGradient id="iAIOtec" x1="14.063" x2="14.063" y1="7.938" y2="5.844" gradientUnits="userSpaceOnUse"><stop class="fe80ltizx"/><stop offset="1" class="eyjq49g1y"/></linearGradient><linearGradient id="ilFaMpe" x1="15.563" x2="15.563" y1="8.125" y2="6.938" gradientUnits="userSpaceOnUse"><stop offset=".342" class="dh1o876_e"/><stop offset="1" class="ao498gb8s"/></linearGradient><linearGradient id="iBIH8uD" x1="10.405" x2="21.25" y1="22.223" y2="22.223" gradientUnits="userSpaceOnUse"><stop class="n11_fr6pn"/><stop offset=".308" class="t5slif2yb"/><stop offset=".729" class="a-yc9pr1r"/><stop offset="1" class="jrexj_sot"/></linearGradient><linearGradient id="i4gifUc" x1="15.25" x2="15.25" y1="28.188" y2="25.313" gradientUnits="userSpaceOnUse"><stop offset=".163" class="s5ncjibek"/><stop offset="1" class="n4hic08er"/></linearGradient><linearGradient id="iBoo1Gj" x1="18.625" x2="20.813" y1="13.25" y2="27.375" gradientUnits="userSpaceOnUse"><stop offset=".428" class="vc--wpv5i"/><stop offset=".871" class="stui2mbih"/></linearGradient><radialGradient id="itKu8ne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25001 21.24997 -6.11655 -.3598 10.875 17.875)" gradientUnits="userSpaceOnUse"><stop class="mckbojb_j"/><stop offset="1" class="hya05bbcg"/></radialGradient><radialGradient id="iH1w5Kd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.0625 -9.96954 0 16.003 8.625)" gradientUnits="userSpaceOnUse"><stop class="oc2unibjv"/><stop offset="1" class="u9j63hbxv"/></radialGradient><radialGradient id="ic4KCzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.125 -5.44775 0 19.688 4.438)" gradientUnits="userSpaceOnUse"><stop class="y-48gnbsq"/><stop offset="1" class="nu_9sxbsr"/></radialGradient><radialGradient id="ig9xQnb" cx="0" cy="0" r="1" gradientTransform="rotate(116.933 3.874 5.674)scale(4.96753 4.335)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="lsx6_qg6n"/><stop offset="1" class="zrqqztbxo"/></radialGradient><radialGradient id="ivLywQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.08 -.54 .54 1.08 12.448 4.08)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="enl7lwbqz"/><stop offset="1" class="sdn1pouvt"/></radialGradient><radialGradient id="iaB3Lfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.08 -.54 .54 1.08 15.488 4.08)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="enl7lwbqz"/><stop offset="1" class="sdn1pouvt"/></radialGradient><radialGradient id="iyhFCKc" cx="0" cy="0" r="1" gradientTransform="matrix(1.08 -.54 .54 1.08 18.528 4.08)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="enl7lwbqz"/><stop offset="1" class="sdn1pouvt"/></radialGradient><radialGradient id="iRi3lKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.08 -.54 .54 1.08 14.038 6)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="enl7lwbqz"/><stop offset="1" class="sdn1pouvt"/></radialGradient><radialGradient id="i3dEkac" cx="0" cy="0" r="1" gradientTransform="matrix(1.08 -.54 .54 1.08 16.928 6)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="enl7lwbqz"/><stop offset="1" class="sdn1pouvt"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:salt" /></template>
<style>
.a-yc9pr1r {
  stop-color: var(--svg-color--dee5eb, #DEE5EB);
}

.a82ynac9n {
  stop-color: var(--svg-color--708c9e, #708C9E);
  stop-opacity: 0;
}

.ao498gb8s {
  stop-color: var(--svg-color--9cc0d6, #9CC0D6);
  stop-opacity: 0;
}

.aufjqh7sx {
  stop-color: var(--svg-color--c0cdd6, #C0CDD6);
}

.dh1o876_e {
  stop-color: var(--svg-color--9cc0d6, #9CC0D6);
}

.enl7lwbqz {
  stop-color: var(--svg-color--95989c, #95989C);
}

.evw9lrb2c {
  d: path("M12.988 4.08a.54.54 0 1 0 0-1.08a.54.54 0 0 0 0 1.08");
}

.eyjq49g1y {
  stop-color: var(--svg-color--839baa, #839BAA);
  stop-opacity: 0;
}

.fe80ltizx {
  stop-color: var(--svg-color--8699a7, #8699A7);
}

.frurhebat {
  d: path("M16.568 3.54a.54.54 0 1 1-1.08 0a.54.54 0 0 1 1.08 0");
}

.ft5dv1b6b {
  fill: none;
}

.g51ftqbre {
  stop-color: var(--svg-color--c4d0d8, #C4D0D8);
}

.gs652endz {
  stop-color: var(--svg-color--bce2fd, #BCE2FD);
}

.hewo_90ja {
  stop-color: var(--svg-color--b1b8bd, #B1B8BD);
}

.hfyubhbzx {
  fill: var(--svg-color--d6f9ff, #D6F9FF);
  d: path("M20.598 29.98h-9.19c-2.1 0-3.71-1.89-3.36-3.96l2.44-14.66h11.03l2.44 14.65c.34 2.08-1.26 3.97-3.36 3.97");
}

.husvxkx4k {
  stop-color: var(--svg-color--949496, #949496);
}

.hv3q1gb4f {
  d: path("M19.708 17.86h-7.41c-.38 0-.71.28-.77.65l-1.09 6.54c-.24 1.45.88 2.77 2.35 2.77h6.43c1.47 0 2.59-1.32 2.35-2.77l-1.09-6.54a.79.79 0 0 0-.77-.65");
}

.hya05bbcg {
  stop-color: var(--svg-color--cbebff, #CBEBFF);
  stop-opacity: 0;
}

.ja7fmvvgv {
  d: path("M21.528 7.58h-11.04v3.77h11.04z");
}

.jmq0vfawt {
  stop-color: var(--svg-color--c6e4fa, #C6E4FA);
  stop-opacity: 0;
}

.jrexj_sot {
  stop-color: var(--svg-color--eaeff5, #EAEFF5);
}

.lel4g8bgd {
  stop-color: var(--svg-color--c1d9f0, #C1D9F0);
}

.lsx6_qg6n {
  stop-color: var(--svg-color--b8c0c7, #B8C0C7);
}

.lxiwh0bka {
  stop-color: var(--svg-color--a1adb5, #A1ADB5);
}

.mckbojb_j {
  stop-color: var(--svg-color--b9e5fc, #B9E5FC);
}

.n11_fr6pn {
  stop-color: var(--svg-color--cbd0d5, #CBD0D5);
}

.n4hic08er {
  stop-color: var(--svg-color--bedff5, #BEDFF5);
  stop-opacity: 0;
}

.nu_9sxbsr {
  stop-color: var(--svg-color--dbe0e6, #DBE0E6);
  stop-opacity: 0;
}

.oc2unibjv {
  stop-color: var(--svg-color--8cafc5, #8CAFC5);
}

.q88m2rbqg {
  d: path("M15.118 5.46a.54.54 0 1 1-1.08 0a.54.54 0 0 1 1.08 0");
}

.qmodwfave {
  d: path("M17.728 14.064a1.037 1.037 0 0 1 2.05-.325l2.084 13.147a1.037 1.037 0 1 1-2.05.325z");
}

.qs671pi4g {
  d: path("M19.068 4.08a.54.54 0 1 0 0-1.08a.54.54 0 0 0 0 1.08");
}

.re37s34-s {
  stop-color: var(--svg-color--949ba0, #949BA0);
}

.s5ncjibek {
  stop-color: var(--svg-color--c0dff3, #C0DFF3);
}

.sdn1pouvt {
  stop-color: var(--svg-color--616a71, #616A71);
}

.srrrmmbue {
  stop-color: var(--svg-color--c0c2c5, #C0C2C5);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t5slif2yb {
  stop-color: var(--svg-color--c3cad1, #C3CAD1);
}

.u2ur8o6zf {
  d: path("M20.598 29.98h-9.19c-2.1 0-3.71-1.89-3.36-3.96l2.44-14.66h11.03l2.44 14.65c.34 2.08-1.26 3.97-3.36 3.97");
}

.u9j63hbxv {
  stop-color: var(--svg-color--9abdd2, #9ABDD2);
  stop-opacity: 0;
}

.ul6-snb8k {
  stop-color: var(--svg-color--879eae, #879EAE);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wk1yj_btb {
  d: path("M18.008 5.46a.54.54 0 1 1-1.08 0a.54.54 0 0 1 1.08 0");
}

.xeif48lyt {
  d: path("M19.508 2h-7.02c-2.31 0-4.03 2.12-3.56 4.38c.15.7.76 1.2 1.48 1.2h11.19c.71 0 1.33-.5 1.48-1.2c.47-2.26-1.26-4.38-3.57-4.38");
}

.y-48gnbsq {
  stop-color: var(--svg-color--d9dee3, #D9DEE3);
}

.zk2f58bry {
  stop-color: var(--svg-color--92a3af, #92A3AF);
}

.zrqqztbxo {
  stop-color: var(--svg-color--acb2b7, #ACB2B7);
  stop-opacity: 0;
}

</style>
