<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVGrXGE14ny" cx="70.609" cy="12.982" r="126.191" gradientTransform="matrix(1 0 0 -.88277 0 126.478)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="fctacgbhb"/><stop offset=".581" class="qn_10yb5l"/><stop offset=".739" class="rgb4r4ebl"/><stop offset=".821" class="o8txv1thc"/><stop offset=".912" class="n1zmeyb_e"/><stop offset="1" class="tl4yd794x"/></radialGradient><path fill="url(#SVGrXGE14ny)" class="qe7gt5x_i"/><defs><path id="SVG7mOtjoji" class="qe7gt5x_i"/></defs><clipPath id="SVGKKt7seFS"><use href="#SVG7mOtjoji"/></clipPath><g clip-path="url(#SVGKKt7seFS)"><path class="xb4ly6b4n"/><path class="aci0t9aec"/><path class="ogamwtwca"/><path class="ckifjnbsi"/><path class="dhanvmbsd"/><path class="hdg0nqbrx"/><path class="xcni6vjzc"/><radialGradient id="SVGudCSUdJh" cx="60.992" cy="27.456" r="105.033" gradientUnits="userSpaceOnUse"><stop offset=".005" class="hroevv_ba"/><stop offset=".472" class="t2msxznwt"/><stop offset="1" class="otcrbgbop"/></radialGradient><path fill="url(#SVGudCSUdJh)" class="fijimdgmc"/><radialGradient id="SVGucSNxeng" cx="61.487" cy="21.166" r="100.37" gradientTransform="matrix(0 1 -1.2714 0 88.398 -40.32)" gradientUnits="userSpaceOnUse"><stop offset=".005" class="hroevv_ba"/><stop offset=".472" class="t2msxznwt"/><stop offset="1" class="otcrbgbop"/></radialGradient><path fill="url(#SVGucSNxeng)" class="g2nqk7-0g"/><path class="r9okcfn5m"/><radialGradient id="SVG39sCNXcG" cx="61.487" cy="21.166" r="128.652" gradientUnits="userSpaceOnUse"><stop offset=".005" class="hroevv_ba"/><stop offset=".472" class="t2msxznwt"/><stop offset="1" class="otcrbgbop"/></radialGradient><path fill="url(#SVG39sCNXcG)" class="yep4n95vh"/><path class="hl-3ckb-m"/><path class="gf-_ajijj"/><path class="rut3j7fkd"/><path class="wu0h7cb4e"/><path class="o0thobclg"/><path class="ht6mywepf"/><path fill="url(#SVG39sCNXcG)" class="mhnm9wskp"/><path class="ws1wz5b4m"/><path class="ac0z2tbol"/><path class="xvo1tna6d"/><path class="gq4-z9bxq"/><path class="o2jvckbhm"/><linearGradient id="SVGi0mDPe5m" x1="55.5" x2="55.5" y1="18.714" y2="108.619" gradientUnits="userSpaceOnUse"><stop offset=".039" class="kbuc-abdt"/><stop offset=".378" class="b3rmviiyx"/><stop offset=".622" class="lp9rfm2nh"/><stop offset=".835" class="g9ywwpbfe"/><stop offset="1" class="xyntvku7r"/></linearGradient><path fill="url(#SVGi0mDPe5m)" class="bzllnacar"/><path class="icezccbgo"/><path class="o842bqbtt"/><path class="jsuzddbdh"/><path class="g7padumco"/><path class="o3qbkmgvi"/><path class="rhqcyy30y"/><path class="ajovaeb-l"/><path class="j0u7b2pee"/><path class="y8g_qvbon"/><path class="ve0mw3dre"/><path class="y9j_0rb6l"/><path class="upr7r0bcn"/><path class="oqemujbxv"/><path class="quk3ybc1z"/><path class="wyfecq4bn"/><path class="s9-ufkfgc"/><path class="k-0nn9bzp"/><linearGradient id="SVGVs2I7btY" x1="21.461" x2="21.461" y1="18.714" y2="108.619" gradientUnits="userSpaceOnUse"><stop offset=".039" class="kbuc-abdt"/><stop offset=".378" class="b3rmviiyx"/><stop offset=".622" class="lp9rfm2nh"/><stop offset=".835" class="g9ywwpbfe"/><stop offset="1" class="xyntvku7r"/></linearGradient><path fill="url(#SVGVs2I7btY)" class="rjhvf2b8i"/><path class="ev-gqwbis"/><path class="ulkc_jeyp"/><path class="y5aliub8k"/><path class="fgu-i-u9a"/><path class="e3armtbno"/><path class="vmzibs5st"/><path class="g4funh7lz"/><path class="vtedy-abx"/><path class="q2ryodbev"/><path class="xt3y5ubzq"/><path class="w1mbd8xqx"/><linearGradient id="SVGQQwDwu1P" x1="85.188" x2="85.188" y1="18.714" y2="108.619" gradientUnits="userSpaceOnUse"><stop offset=".039" class="kbuc-abdt"/><stop offset=".378" class="b3rmviiyx"/><stop offset=".622" class="lp9rfm2nh"/><stop offset=".835" class="g9ywwpbfe"/><stop offset="1" class="xyntvku7r"/></linearGradient><path fill="url(#SVGQQwDwu1P)" class="qrw9ehwif"/><path class="v5ezpjbon"/><path class="fik8s2boi"/><path class="nqkafm_tj"/><path class="umio-ccka"/><path class="v4x_giooz"/><path class="o35x59zrs"/><linearGradient id="SVGBcUtRc8u" x1="122.604" x2="122.604" y1="18.714" y2="108.619" gradientUnits="userSpaceOnUse"><stop offset=".039" class="kbuc-abdt"/><stop offset=".378" class="b3rmviiyx"/><stop offset=".622" class="lp9rfm2nh"/><stop offset=".835" class="g9ywwpbfe"/><stop offset="1" class="xyntvku7r"/></linearGradient><path fill="url(#SVGBcUtRc8u)" class="cwsxm3bpo"/><path class="mh5p-1bok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:night-with-stars" /></template>
<style>
.ac0z2tbol {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M103.669 72.684h3.269v4.605h-3.269z");
}

.aci0t9aec {
  fill: var(--svg-color--ffd420, #ffd420);
  d: path("M98.897 15.353c.155.36 3.137.686 3.137.686s1.087 2.942 1.43 3.015c.58.139 1.806-2.712 1.806-2.712s2.99-.041 3.162-.409c.302-.645-1.92-2.59-1.92-2.59s1.372-2.802.792-3.145c-.588-.343-3.154 1.005-3.154 1.005s-2.549-2.239-3.03-1.945c-.662.409.138 3.472.138 3.472s-2.622 1.994-2.36 2.623M9.784 9.477c-.206.188.47 2.36.47 2.36s-1.628 1.756-1.573 2.001c.072.306 2.354.522 2.354.522s1.063 2.081 1.346 2.063c.394-.02 1.147-2.096 1.147-2.096s2.583-.471 2.638-.702c.066-.295-1.772-1.83-1.772-1.83s.537-2.316.188-2.516c-.322-.189-2.343 1.17-2.343 1.17s-2.103-1.294-2.455-.972M9.099 32.7c-.185.149.282 1.915.282 1.915s-1.544 1.343-1.517 1.555c.043.362 2.026.447 2.026.447s.585 1.747.83 1.782c.284.04 1.181-1.575 1.181-1.575s1.833-.12 1.912-.346c.074-.239-1.238-1.58-1.238-1.58s.712-1.776.465-2.018c-.212-.211-2.01.633-2.01.633s-1.668-1.025-1.931-.814");
}

.ajovaeb-l {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M54.229 50.73h2.541v4.79h-2.541z");
}

.b3rmviiyx {
  stop-color: var(--svg-color--163284, #163284);
}

.bzllnacar {
  d: path("M46.109 29.793h18.783v94.467H46.109z");
}

.ckifjnbsi {
  fill: var(--svg-color--ffd420, #ffd420);
  d: path("M73.226 41.329c-.184.15.282 1.916.282 1.916s-1.544 1.342-1.517 1.554c.043.362 2.027.447 2.027.447s.585 1.748.83 1.782c.284.04 1.18-1.574 1.18-1.574s1.833-.121 1.912-.347c.074-.238-1.237-1.579-1.237-1.579s.712-1.777.464-2.018c-.212-.212-2.01.632-2.01.632s-1.667-1.025-1.93-.813");
}

.cwsxm3bpo {
  d: path("M115.452 33.835h14.303v96.125h-14.303z");
}

.dhanvmbsd {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M66.992 19.889c-.185.15.281 1.916.281 1.916s-1.543 1.342-1.516 1.554c.043.362 2.026.447 2.026.447s.585 1.748.83 1.782c.284.04 1.181-1.574 1.181-1.574s1.832-.121 1.912-.347c.074-.238-1.238-1.579-1.238-1.579s.712-1.777.465-2.018c-.213-.212-2.011.632-2.011.632s-1.667-1.025-1.93-.813");
}

.e3armtbno {
  fill: var(--svg-color--4c989e, #4c989e);
  d: path("M22.036 89.932h4.087v6.947h-4.087z");
}

.ev-gqwbis {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M6.477 66.119h4.087v6.947H6.477z");
}

.fctacgbhb {
  stop-color: var(--svg-color--a8d793, #a8d793);
}

.fgu-i-u9a {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M14.257 89.932h4.087v6.947h-4.087z");
}

.fijimdgmc {
  d: path("M61.631 76.335h20.72v54.17h-20.72z");
}

.fik8s2boi {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M75.615 69.565h3.143v4.621h-3.143z");
}

.g2nqk7-0g {
  d: path("M27.727 18.885h31.411V129.72H27.727z");
}

.g4funh7lz {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M6.477 101.839h4.087v6.947H6.477zm7.78 0h4.087v6.947h-4.087zm7.779 0h4.087v6.947h-4.087z");
}

.g7padumco {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M49.369 42.583h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541z");
}

.g9ywwpbfe {
  stop-color: var(--svg-color--182e6b, #182e6b);
}

.gf-_ajijj {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M8.52 50.677h1.457v3.112H8.52zm3.175 0h1.457v3.112h-1.457zm3.174 0h1.457v3.112h-1.457zm3.175 0h1.457v3.112h-1.457z");
}

.gq4-z9bxq {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M103.669 88.13h3.269v4.605h-3.269z");
}

.hdg0nqbrx {
  fill: var(--svg-color--ffd420, #ffd420);
  d: path("M54.813 7.255c-.284.028-.98 2.107-.98 2.107s-2.432.33-2.545.56c-.195.391 1.738 1.783 1.738 1.783s-.564 2.138-.341 2.334c.258.227 2.221-.801 2.221-.801s1.918 1.085 2.146.911c.231-.19-.201-2.398-.201-2.398s1.884-1.314 1.796-1.719c-.074-.352-2.434-.69-2.434-.69s-.997-2.126-1.4-2.087");
}

.hl-3ckb-m {
  fill: var(--svg-color--257072, #257072);
  d: path("M21.461 117.22h2.619V50.045l-2.619-2.672z");
}

.hroevv_ba {
  stop-color: var(--svg-color--98e3f2, #98e3f2);
}

.ht6mywepf {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M18.044 56.22h1.457v3.112h-1.457z");
}

.icezccbgo {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M49.369 34.436h2.541v4.79h-2.541z");
}

.j0u7b2pee {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M59.09 50.73h2.541v4.79H59.09zm-9.721 8.146h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09z");
}

.jsuzddbdh {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M59.09 115.903h2.541v4.79H59.09z");
}

.k-0nn9bzp {
  fill: var(--svg-color--397f84, #397f84);
  d: path("M37.07 60.397h5.505v63.863H37.07z");
}

.kbuc-abdt {
  stop-color: var(--svg-color--163387, #163387);
}

.lp9rfm2nh {
  stop-color: var(--svg-color--17317b, #17317b);
}

.mh5p-1bok {
  fill: var(--svg-color--12607c, #12607c);
  d: path("m115.452 129.96l-5.857-3.633V38.33l5.857-4.495z");
}

.mhnm9wskp {
  d: path("M86.733 60.689h30.762v72.381H86.733z");
}

.n1zmeyb_e {
  stop-color: var(--svg-color--326c8f, #326c8f);
}

.nqkafm_tj {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M83.617 69.565h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143z");
}

.o0thobclg {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M14.869 56.22h1.457v3.112h-1.457z");
}

.o2jvckbhm {
  fill: var(--svg-color--397f84, #397f84);
  d: path("M103.669 95.853h3.269v4.605h-3.269zm0 7.723h3.269v4.605h-3.269zm0 7.723h3.269v4.605h-3.269z");
}

.o35x59zrs {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M83.617 92.523h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zm-16.004 11.478h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zM75.615 115.48h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143z");
}

.o3qbkmgvi {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M59.09 42.583h2.541v4.79H59.09z");
}

.o842bqbtt {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M54.229 34.436h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09zm-9.721 81.467h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541z");
}

.o8txv1thc {
  stop-color: var(--svg-color--457986, #457986);
}

.ogamwtwca {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M113.711 24.093c-.184.15.282 1.916.282 1.916s-1.544 1.343-1.517 1.555c.044.362 2.027.447 2.027.447s.585 1.747.83 1.782c.284.04 1.18-1.575 1.18-1.575s1.833-.12 1.912-.346c.074-.239-1.237-1.58-1.237-1.58s.712-1.776.465-2.018c-.213-.211-2.011.633-2.011.633s-1.667-1.025-1.93-.814");
}

.oqemujbxv {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M54.229 83.316h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09zm-9.721 8.147h2.541v4.79h-2.541z");
}

.otcrbgbop {
  stop-color: var(--svg-color--6ba3ae, #6ba3ae);
}

.q2ryodbev {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M6.477 113.746h4.087v6.947H6.477z");
}

.qe7gt5x_i {
  d: path("M116.62 124.26H11.32c-4.15 0-7.52-3.37-7.52-7.52V11.44c0-4.15 3.37-7.52 7.52-7.52h105.3c4.15 0 7.52 3.37 7.52 7.52v105.3c.01 4.15-3.36 7.52-7.52 7.52");
}

.qn_10yb5l {
  stop-color: var(--svg-color--7dad8b, #7dad8b);
}

.qrw9ehwif {
  d: path("M69.807 51.879h30.762v72.381H69.807z");
}

.quk3ybc1z {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M54.229 91.463h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09zm-9.721 8.147h2.541v4.79h-2.541zm4.86 0h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09zm-9.721 8.146h2.541v4.79h-2.541z");
}

.r9okcfn5m {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M31.785 24.572h2.541v7.537h-2.541zm5.188 0h2.541v7.537h-2.541zm5.189 0h2.541v7.537h-2.541zm5.189 0h2.541v7.537h-2.541zm5.188 0h2.541v7.537h-2.541zM31.785 36.627h2.541v7.537h-2.541zm5.188 0h2.541v7.537h-2.541zm5.189 0h2.541v7.537h-2.541zM31.785 48.682h2.541v7.537h-2.541zm5.188 0h2.541v7.537h-2.541zm5.189 0h2.541v7.537h-2.541z");
}

.rgb4r4ebl {
  stop-color: var(--svg-color--4c7d82, #4c7d82);
}

.rhqcyy30y {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M49.369 50.73h2.541v4.79h-2.541z");
}

.rjhvf2b8i {
  d: path("M3.889 60.397h35.145v63.863H3.889z");
}

.rut3j7fkd {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M8.52 56.22h1.457v3.112H8.52z");
}

.s9-ufkfgc {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M59.09 107.756h2.541v4.79H59.09z");
}

.t2msxznwt {
  stop-color: var(--svg-color--73bbc9, #73bbc9);
}

.tl4yd794x {
  stop-color: var(--svg-color--185b9d, #185b9d);
}

.ulkc_jeyp {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M14.257 66.119h4.087v6.947h-4.087zm7.779 0h4.087v6.947h-4.087zm7.78 0h4.087v6.947h-4.087zM6.477 78.025h4.087v6.947H6.477zm7.78 0h4.087v6.947h-4.087zm7.779 0h4.087v6.947h-4.087zm7.78 0h4.087v6.947h-4.087z");
}

.umio-ccka {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M75.615 81.044h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143z");
}

.upr7r0bcn {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M49.369 83.316h2.541v4.79h-2.541z");
}

.v4x_giooz {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M75.615 92.523h3.143v4.621h-3.143z");
}

.v5ezpjbon {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M75.615 58.087h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143zm8.002 0h3.143v4.621h-3.143z");
}

.ve0mw3dre {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M54.229 67.023h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09zm-9.721 8.147h2.541v4.79h-2.541z");
}

.vmzibs5st {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M29.816 89.932h4.087v6.947h-4.087z");
}

.vtedy-abx {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M29.816 101.839h4.087v6.947h-4.087z");
}

.w1mbd8xqx {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M22.036 113.746h4.087v6.947h-4.087zm7.78 0h4.087v6.947h-4.087z");
}

.ws1wz5b4m {
  fill: var(--svg-color--397f84, #397f84);
  d: path("M103.669 64.961h3.269v4.605h-3.269z");
}

.wu0h7cb4e {
  fill: var(--svg-color--4d868e, #4d868e);
  d: path("M11.695 56.22h1.457v3.112h-1.457z");
}

.wyfecq4bn {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M54.229 107.756h2.541v4.79h-2.541z");
}

.xb4ly6b4n {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M78.312 21.38c-2.28 5.56-.93 12.12 2.87 16.14c3.91 4.14 11 6.36 18.23 2.54c4.63-2.45 5.58-6.95 5.46-7.16c-.29-.5-3.55 1.64-8.46 1.77c-6.53.17-12.02-4.32-12.17-11.34c-.11-5.23 1.65-9.1 1.26-9.18c-.46-.09-4.79 1.4-7.19 7.23");
}

.xcni6vjzc {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M17.877 22.18c-.236.03-.771 1.777-.771 1.777s-2.02.327-2.108.521c-.155.33 1.486 1.449 1.486 1.449s-.425 1.793-.235 1.951c.22.184 1.834-.715 1.834-.715s1.62.864 1.807.714c.188-.164-.22-1.994-.22-1.994s1.543-1.135 1.46-1.47c-.069-.292-2.042-.523-2.042-.523s-.876-1.75-1.211-1.71");
}

.xt3y5ubzq {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M14.257 113.746h4.087v6.947h-4.087z");
}

.xvo1tna6d {
  fill: var(--svg-color--397f84, #397f84);
  d: path("M103.669 80.407h3.269v4.605h-3.269z");
}

.xyntvku7r {
  stop-color: var(--svg-color--1a2b59, #1a2b59);
}

.y5aliub8k {
  fill: var(--svg-color--4c989e, #4c989e);
  d: path("M6.477 89.932h4.087v6.947H6.477z");
}

.y8g_qvbon {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M49.369 67.023h2.541v4.79h-2.541z");
}

.y9j_0rb6l {
  fill: var(--svg-color--fff18f, #fff18f);
  d: path("M54.229 75.17h2.541v4.79h-2.541zm4.861 0h2.541v4.79H59.09z");
}

.yep4n95vh {
  d: path("M6.448 47.373h15.013v69.847H6.448z");
}

</style>
