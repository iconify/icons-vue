<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVGiTjLsdoV" cx="93.693" cy="76.866" r="84.756" gradientTransform="rotate(179.131 .043 59.533)scale(-1 .83927)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="xpauntbyw"/><stop offset=".611" class="zlpqyqb4g"/><stop offset=".99" class="hpw74qx4z"/></radialGradient><path fill="url(#SVGiTjLsdoV)" class="qe7gt5x_i"/><radialGradient id="SVGTODChbSq" cx="89.043" cy="70.877" r="100.167" gradientTransform="rotate(179.577 .009 61.802)scale(-1 .90047)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="ejcm0cb-j"/><stop offset="1" class="qnirhxb1m"/></radialGradient><path fill="url(#SVGTODChbSq)" class="qe7gt5x_i"/><circle class="wpuffsbfc"/><radialGradient id="SVG1Jtm3ctU" cx="91.925" cy="44.186" r="27.06" gradientTransform="translate(4.33 .22)scale(.96284)" gradientUnits="userSpaceOnUse"><stop offset=".395" class="a8eimobnc"/><stop offset="1" class="plkww03jq"/></radialGradient><circle fill="url(#SVG1Jtm3ctU)" class="ofqu7uaks"/><defs><path id="SVG7mOtjoji" class="qe7gt5x_i"/></defs><clipPath id="SVGKKt7seFS"><use href="#SVG7mOtjoji"/></clipPath><g clip-path="url(#SVGKKt7seFS)"><path class="kcre4o40q"/><linearGradient id="SVGpA5m6e6q" x1="43.433" x2="43.433" y1="24.795" y2="108.019" gradientUnits="userSpaceOnUse"><stop offset="0" class="l0wujmbzo"/><stop offset=".376" class="ru_7bipye"/><stop offset="1" class="o_ekzbb4g"/></linearGradient><path fill="url(#SVGpA5m6e6q)" class="g2nqk7-0g"/><path class="d6exgvb5b"/><linearGradient id="SVGXreYVcaJ" x1="13.955" x2="13.955" y1="24.795" y2="108.019" gradientUnits="userSpaceOnUse"><stop offset="0" class="l0wujmbzo"/><stop offset=".376" class="ru_7bipye"/><stop offset="1" class="o_ekzbb4g"/></linearGradient><path fill="url(#SVGXreYVcaJ)" class="yep4n95vh"/><path class="rhog21b5k"/><path class="q8oxuj8fl"/><path class="ll24jlevn"/><path class="ihgshacap"/><path class="etn65b-re"/><path class="fr51qhbfk"/><path class="oin9zdbgo"/><path class="d3691g_rn"/><path class="tl4a9bb3n"/><path class="e53dh9d6c"/><radialGradient id="SVGa9YGJRJT" cx="72.295" cy="30.158" r="113.837" gradientUnits="userSpaceOnUse"><stop offset=".51" class="nec1ikk0v"/><stop offset=".934" class="fl5g7gv2m"/></radialGradient><path fill="url(#SVGa9YGJRJT)" class="bzllnacar"/><path class="m_y3ou99l"/><path class="tpk5mzh5z"/><path class="f-2as9bzv"/><path class="iqglo-ray"/><path class="mx1tgmk-o"/><path class="i79sewxop"/><path class="vsxb8qb6r"/><path class="drosjqyda"/><path class="bpg9f2bdm"/><path class="l1f1v8b3e"/><path class="mzfop08ff"/><path class="peg-irbpk"/><linearGradient id="SVGYWUPXdrk" x1="39.822" x2="39.822" y1="74.111" y2="132.241" gradientUnits="userSpaceOnUse"><stop offset="0" class="a8eimobnc"/><stop offset="1" class="t7ce5xbfu"/></linearGradient><path fill="url(#SVGYWUPXdrk)" class="q9cw-dbcy"/><path fill="url(#SVGa9YGJRJT)" class="rjhvf2b8i"/><path class="l5cgf7bdt"/><path class="er5p4fbbr"/><path class="v3l7i5mmy"/><path class="swity2w_h"/><path class="g0_rvyb_o"/><path class="ej_ilyb5j"/><path class="txhvnya0j"/><path class="o26dm62wy"/><path class="bi5jrbcol"/><path class="ffjjo3a4h"/><path class="skx8xfbot"/><path class="iqczb8bns"/><path fill="url(#SVGa9YGJRJT)" class="qrw9ehwif"/><path class="hqaf43bgv"/><path class="mqxt4_bmz"/><path class="kmsa35b6o"/><path class="qfmdf-j_h"/><path class="tz5mepbik"/><path class="o7kq2wbsl"/><path fill="url(#SVGa9YGJRJT)" class="cwsxm3bpo"/><linearGradient id="SVGESShfdyw" x1="113.024" x2="113.024" y1="62.215" y2="130.703" gradientUnits="userSpaceOnUse"><stop offset="0" class="a8eimobnc"/><stop offset="1" class="t7ce5xbfu"/></linearGradient><path fill="url(#SVGESShfdyw)" class="z1sunsx7y"/><linearGradient id="SVGP8VPLcVT" x1="64.732" x2="64.732" y1="74.111" y2="132.241" gradientUnits="userSpaceOnUse"><stop offset="0" class="a8eimobnc"/><stop offset="1" class="t7ce5xbfu"/></linearGradient><path fill="url(#SVGP8VPLcVT)" class="vxy56wlmg"/></g><path class="vdif_1bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:sunset" /></template>
<style>
.a8eimobnc {
  stop-color: var(--svg-color--fff6b2, #fff6b2);
}

.bi5jrbcol {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M29.816 89.932h4.087v6.947h-4.087z");
}

.bpg9f2bdm {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M59.09 91.463h2.541v4.79H59.09z");
}

.bzllnacar {
  d: path("M46.109 29.793h18.783v94.467H46.109z");
}

.cwsxm3bpo {
  d: path("M115.452 33.835h14.303v96.125h-14.303z");
}

.d3691g_rn {
  fill: var(--svg-color--bc5235, #bc5235);
  d: path("M86.733 60.689h30.762v72.381H86.733z");
}

.d6exgvb5b {
  fill: var(--svg-color--ffe066, #ffe066);
  d: path("M31.785 24.572h2.541v7.537h-2.541zm5.188 0h2.541v7.537h-2.541zm5.189 0h2.541v7.537h-2.541zm5.189 0h2.541v7.537h-2.541zm5.188 0h2.541v7.537h-2.541zM31.785 36.627h2.541v7.537h-2.541zm5.188 0h2.541v7.537h-2.541zm5.189 0h2.541v7.537h-2.541zM31.785 48.682h2.541v7.537h-2.541zm5.188 0h2.541v7.537h-2.541zm5.189 0h2.541v7.537h-2.541z");
}

.drosjqyda {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M49.369 91.463h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541z");
}

.e53dh9d6c {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M103.669 95.853h3.269v4.605h-3.269zm0 7.723h3.269v4.605h-3.269zm0 7.723h3.269v4.605h-3.269z");
}

.ej_ilyb5j {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M29.816 78.025h4.087v6.947h-4.087z");
}

.ejcm0cb-j {
  stop-color: var(--svg-color--a62b60, #a62b60);
  stop-opacity: 0;
}

.er5p4fbbr {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M14.257 66.119h4.087v6.947h-4.087zm7.779 0h4.087v6.947h-4.087z");
}

.etn65b-re {
  fill: var(--svg-color--ff9c7d, #ff9c7d);
  d: path("M11.695 56.22h1.457v3.112h-1.457z");
}

.f-2as9bzv {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M49.369 42.583h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09zm-9.721 8.147h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09zm-9.721 8.146h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09zm-9.721 8.147h2.541v4.79h-2.541z");
}

.ffjjo3a4h {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M6.477 101.839h4.087v6.947H6.477zm7.78 0h4.087v6.947h-4.087zm7.779 0h4.087v6.947h-4.087zm7.78 0h4.087v6.947h-4.087zM6.477 113.746h4.087v6.947H6.477z");
}

.fl5g7gv2m {
  stop-color: var(--svg-color--6d0c36, #6d0c36);
}

.fr51qhbfk {
  fill: var(--svg-color--ffe066, #ffe066);
  d: path("M14.869 56.22h1.457v3.112h-1.457z");
}

.g0_rvyb_o {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M22.036 78.025h4.087v6.947h-4.087z");
}

.g2nqk7-0g {
  d: path("M27.727 18.885h31.411V129.72H27.727z");
}

.hpw74qx4z {
  stop-color: var(--svg-color--a94463, #a94463);
}

.hqaf43bgv {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M75.615 58.087h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143z");
}

.i79sewxop {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M49.369 75.17h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09zm-9.721 8.146h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541z");
}

.ihgshacap {
  fill: var(--svg-color--ffe066, #ffe066);
  d: path("M8.52 56.22h1.457v3.112H8.52z");
}

.iqczb8bns {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M22.036 113.746h4.087v6.947h-4.087zm7.78 0h4.087v6.947h-4.087z");
}

.iqglo-ray {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M54.229 67.023h2.541v4.79h-2.541z");
}

.kcre4o40q {
  fill: var(--svg-color--bc5235, #bc5235);
  d: path("M61.631 76.335h20.72v54.17h-20.72z");
}

.kmsa35b6o {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M83.617 69.565h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zM75.615 81.044h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143z");
}

.l0wujmbzo {
  stop-color: var(--svg-color--f2835c, #f2835c);
}

.l1f1v8b3e {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M49.369 99.61h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541z");
}

.l5cgf7bdt {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M6.477 66.119h4.087v6.947H6.477z");
}

.ll24jlevn {
  fill: var(--svg-color--ff9c7d, #ff9c7d);
  d: path("M11.695 50.677h1.457v3.112h-1.457zm3.174 0h1.457v3.112h-1.457zm3.175 0h1.457v3.112h-1.457z");
}

.m_y3ou99l {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M49.369 34.436h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09z");
}

.mqxt4_bmz {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M75.615 69.565h3.143v4.621h-3.143z");
}

.mx1tgmk-o {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M59.09 67.023h2.541v4.79H59.09z");
}

.mzfop08ff {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M59.09 99.61h2.541v4.79H59.09zm-9.721 8.146h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541z");
}

.nec1ikk0v {
  stop-color: var(--svg-color--911f4e, #911f4e);
}

.o_ekzbb4g {
  stop-color: var(--svg-color--d15d57, #d15d57);
}

.o26dm62wy {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M22.036 89.932h4.087v6.947h-4.087z");
}

.o7kq2wbsl {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M91.619 92.523h3.143v4.621h-3.143zm-16.004 11.478h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zM75.615 115.48h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143z");
}

.ofqu7uaks {
  cx: 92.839px;
  cy: 42.764px;
  r: 36.251px;
  opacity: var(--svg-opacity--0-63, 0.63);
}

.oin9zdbgo {
  fill: var(--svg-color--ff9c7d, #ff9c7d);
  d: path("M18.044 56.22h1.457v3.112h-1.457z");
}

.peg-irbpk {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M59.09 107.756h2.541v4.79H59.09z");
}

.plkww03jq {
  stop-color: var(--svg-color--fff6b2, #fff6b2);
  stop-opacity: 0;
}

.q8oxuj8fl {
  fill: var(--svg-color--ffe066, #ffe066);
  d: path("M8.52 50.677h1.457v3.112H8.52z");
}

.q9cw-dbcy {
  d: path("M37.07 60.397h5.505v63.863H37.07z");
}

.qe7gt5x_i {
  d: path("M116.62 124.26H11.32c-4.15 0-7.52-3.37-7.52-7.52V11.44c0-4.15 3.37-7.52 7.52-7.52h105.3c4.15 0 7.52 3.37 7.52 7.52v105.3c.01 4.15-3.36 7.52-7.52 7.52");
}

.qfmdf-j_h {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M75.615 92.523h3.143v4.621h-3.143z");
}

.qnirhxb1m {
  stop-color: var(--svg-color--a62b60, #a62b60);
  stop-opacity: 0.8;
}

.qrw9ehwif {
  d: path("M69.807 51.879h30.762v72.381H69.807z");
}

.rhog21b5k {
  fill: var(--svg-color--a84d35, #a84d35);
  d: path("M21.461 117.22h2.619V50.045l-2.619-2.672z");
}

.rjhvf2b8i {
  d: path("M3.889 60.397h35.145v63.863H3.889z");
}

.ru_7bipye {
  stop-color: var(--svg-color--d17757, #d17757);
}

.skx8xfbot {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M14.257 113.746h4.087v6.947h-4.087z");
}

.swity2w_h {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M6.477 78.025h4.087v6.947H6.477zm7.78 0h4.087v6.947h-4.087z");
}

.t7ce5xbfu {
  stop-color: var(--svg-color--fe7a47, #fe7a47);
}

.tl4a9bb3n {
  fill: var(--svg-color--fcb95a, #fcb95a);
  d: path("M103.669 64.961h3.269v4.605h-3.269zm0 7.723h3.269v4.605h-3.269zm0 7.723h3.269v4.605h-3.269zm0 7.723h3.269v4.605h-3.269z");
}

.tpk5mzh5z {
  fill: var(--svg-color--fe7a47, #fe7a47);
  d: path("M49.369 115.903h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09z");
}

.txhvnya0j {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M6.477 89.932h4.087v6.947H6.477zm7.78 0h4.087v6.947h-4.087z");
}

.tz5mepbik {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M83.617 92.523h3.143v4.621h-3.143z");
}

.v3l7i5mmy {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M29.816 66.119h4.087v6.947h-4.087z");
}

.vdif_1bqq {
  fill: var(--svg-color--fff6b2, #fff6b2);
  d: path("M59.138 18.885h2.713v10.908h-2.713z");
}

.vsxb8qb6r {
  fill: var(--svg-color--fff685, #fff685);
  d: path("M59.09 83.316h2.541v4.79H59.09z");
}

.vxy56wlmg {
  d: path("M63.891 29.793h1.682v94.401h-1.682z");
}

.wpuffsbfc {
  cx: 92.839px;
  cy: 42.764px;
  r: 14.072px;
  fill: var(--svg-color--fef7b2, #fef7b2);
}

.xpauntbyw {
  stop-color: var(--svg-color--ffc152, #ffc152);
}

.yep4n95vh {
  d: path("M6.448 47.373h15.013v69.847H6.448z");
}

.z1sunsx7y {
  d: path("m115.452 129.96l-4.857-3.633V38.33l4.857-4.495z");
}

.zlpqyqb4g {
  stop-color: var(--svg-color--dd7242, #dd7242);
}

</style>
