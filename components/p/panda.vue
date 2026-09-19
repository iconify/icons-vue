<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iJzfgJe)" class="bv3kjqung"/><path fill="url(#iBZ7vhc)" class="bv3kjqung"/><path fill="url(#igId7QW)" class="bv3kjqung"/><path fill="url(#i7hQcub)" class="bv3kjqung"/><path fill="url(#iNm4crc)" class="bv3kjqung"/><path fill="url(#inRhDDc)" class="kfv2ntbxs"/><g filter="url(#iwKVpwe)"><path stroke="url(#ivKxPGb)" class="g8smzcklu"/></g><g filter="url(#iDzpRQO)"><path stroke="url(#iAOl1Hb)" class="c8cw4hbel"/></g><g filter="url(#ibo1vgp)"><path fill="url(#ieFHAYc)" class="ayejg7zhn"/><path fill="url(#iXQeSFe)" class="ayejg7zhn"/></g><path fill="url(#iqg3FHe)" class="ayejg7zhn"/><path fill="url(#iBZkm1b)" class="ayejg7zhn"/><path fill="url(#iLmz1Oc)" class="ayejg7zhn"/><path fill="url(#icidTIe)" class="gf_bcjr-d"/><path fill="url(#iMi01ub)" class="gf_bcjr-d"/><path fill="url(#iiWadzd)" class="argt23bhs"/><path fill="url(#iNMkjJd)" class="argt23bhs"/><g filter="url(#iJxhQql)"><path class="ityabbclb"/></g><path fill="url(#igiKgJc)" class="pixlyqoup"/><path fill="url(#iiIZAxe)" class="pixlyqoup"/><path fill="url(#id1fiic)" class="pixlyqoup"/><path fill="url(#iGF37jH)" class="pixlyqoup"/><path fill="url(#iQd0lBS)" class="pixlyqoup"/><g filter="url(#i0eGUQc)"><rect class="h4lw7lb1g"/></g><g filter="url(#iHaqfrd)"><rect class="a09rbyi7b"/></g><rect fill="url(#iMUie3b)" class="hdfeml-gx"/><rect fill="url(#inoFmXe)" class="hdfeml-gx"/><rect fill="url(#iOtkQ3c)" transform="matrix(-1 0 0 1 20.722 14.96)" class="lhnqa3sxn"/><rect fill="url(#iqpoyCz)" transform="matrix(-1 0 0 1 20.722 14.96)" class="lhnqa3sxn"/><g filter="url(#ik4746d)"><path clip-rule="evenodd" class="i9-12bcno"/></g><path stroke="url(#iPgJHkB)" class="p4zxw29sj"/><path stroke="url(#i3zGehb)" class="ahy-6aczx"/><g filter="url(#i2mq4bc)"><path stroke="url(#i7fWyFb)" class="znpx77bhc"/></g><g filter="url(#idVSzae)"><rect class="wr3aow-0r"/></g><g filter="url(#i0E0VWd)"><rect class="op476abrm"/></g><defs><linearGradient id="iJzfgJe" x1="4.61" x2="9.922" y1="11.429" y2="4.554" gradientUnits="userSpaceOnUse"><stop class="hlfgozbwx"/><stop offset="1" class="fr_xrgbwn"/></linearGradient><linearGradient id="iBZ7vhc" x1="8.922" x2="8.079" y1="9.515" y2="4.086" gradientUnits="userSpaceOnUse"><stop offset=".549" class="vaomm_byr"/><stop offset="1" class="hircosu7l"/></linearGradient><linearGradient id="igId7QW" x1="7.079" x2="6.157" y1="9.664" y2="8.898" gradientUnits="userSpaceOnUse"><stop class="uee69bc2u"/><stop offset="1" class="y7mi9klsn"/></linearGradient><linearGradient id="inRhDDc" x1="21.329" x2="29.164" y1="7.961" y2="8.336" gradientUnits="userSpaceOnUse"><stop class="hlfgozbwx"/><stop offset="1" class="fr_xrgbwn"/></linearGradient><linearGradient id="ivKxPGb" x1="28.751" x2="21.938" y1="11.601" y2="5.492" gradientUnits="userSpaceOnUse"><stop class="nvw_35bqd"/><stop offset=".378" class="kbkd0lbzx"/><stop offset="1" class="nvw_35bqd"/></linearGradient><linearGradient id="iAOl1Hb" x1="11.908" x2="5.095" y1="11.601" y2="5.492" gradientUnits="userSpaceOnUse"><stop class="nvw_35bqd"/><stop offset=".378" class="kbkd0lbzx"/><stop offset="1" class="nvw_35bqd"/></linearGradient><linearGradient id="iBZkm1b" x1="31.11" x2="26.547" y1="25.211" y2="23.773" gradientUnits="userSpaceOnUse"><stop class="ljfjt5shb"/><stop offset="1" class="qp07sgb8l"/></linearGradient><linearGradient id="icidTIe" x1="10.499" x2="10.499" y1="13.105" y2="19.555" gradientUnits="userSpaceOnUse"><stop class="xt8tsubzf"/><stop offset="1" class="cctdiwbjb"/></linearGradient><linearGradient id="iiWadzd" x1="21.491" x2="21.491" y1="12.987" y2="22.023" gradientUnits="userSpaceOnUse"><stop class="xt8tsubzf"/><stop offset="1" class="cctdiwbjb"/></linearGradient><linearGradient id="igiKgJc" x1="15.864" x2="16.283" y1="18.117" y2="21.582" gradientUnits="userSpaceOnUse"><stop class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="iiIZAxe" x1="15.764" x2="15.764" y1="19.631" y2="18.427" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ueu24dben"/><stop offset=".873" class="vylhu7i4w"/></linearGradient><linearGradient id="id1fiic" x1="15.161" x2="15.161" y1="21.651" y2="19.83" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset=".714" class="jqmybnbeu"/></linearGradient><linearGradient id="iMUie3b" x1="12.657" x2="11.813" y1="16.586" y2="16.586" gradientUnits="userSpaceOnUse"><stop class="dyysy0bzo"/><stop offset="1" class="bhuvpx2ny"/></linearGradient><linearGradient id="inoFmXe" x1="12.966" x2="12.966" y1="18.273" y2="17.211" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iOtkQ3c" x1="-.091" x2=".894" y1="1.302" y2="1.302" gradientUnits="userSpaceOnUse"><stop class="dyysy0bzo"/><stop offset="1" class="bhuvpx2ny"/></linearGradient><linearGradient id="iqpoyCz" x1="1.698" x2="1.698" y1="2.977" y2="2.063" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="i7fWyFb" x1="12.322" x2="19.838" y1="23.103" y2="23.103" gradientUnits="userSpaceOnUse"><stop class="rj14edb9i"/><stop offset=".289" class="zkps8y4ss"/><stop offset=".445" class="zkps8y4ss"/><stop offset=".534" class="rj14edb9i"/><stop offset="1" class="zkps8y4ss"/></linearGradient><radialGradient id="i7hQcub" cx="0" cy="0" r="1" gradientTransform="matrix(-8.65618 5.62504 -2.5718 -3.95766 12.079 5.93)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="y7mi9klsn"/><stop offset="1" class="uee69bc2u"/></radialGradient><radialGradient id="iNm4crc" cx="0" cy="0" r="1" gradientTransform="rotate(153.909 5.47 4.408)scale(3.83693 5.37999)" gradientUnits="userSpaceOnUse"><stop class="rez373ifa"/><stop offset="1" class="hyfbt3btq"/></radialGradient><radialGradient id="ieFHAYc" cx="0" cy="0" r="1" gradientTransform="rotate(90 2.99 13.245)scale(18.3932)" gradientUnits="userSpaceOnUse"><stop class="f8fib8bhj"/><stop offset="1" class="k1zvhqbgt"/></radialGradient><radialGradient id="iXQeSFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.025 31.318 0 16.235 28.836)" gradientUnits="userSpaceOnUse"><stop class="u0dgzxinl"/><stop offset="1" class="jrv-u9byp"/></radialGradient><radialGradient id="iqg3FHe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.81252 4.24998 -10.8821 -12.32249 26.422 11.586)" gradientUnits="userSpaceOnUse"><stop class="b-2k86b_r"/><stop offset="1" class="fly8uzaif"/></radialGradient><radialGradient id="iLmz1Oc" cx="0" cy="0" r="1" gradientTransform="rotate(23.798 -30.758 27.044)scale(24.3176 18.5159)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="upkeozbze"/><stop offset=".992" class="dxzcax2ia"/></radialGradient><radialGradient id="iMi01ub" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8125 0 0 -5.39683 14.985 16.968)" gradientUnits="userSpaceOnUse"><stop offset=".014" class="ohfnw2bor"/><stop offset="1" class="njgnrtcml"/></radialGradient><radialGradient id="iNMkjJd" cx="0" cy="0" r="1" gradientTransform="matrix(3.33249 -2.18067 3.08688 4.71735 17.485 19.148)" gradientUnits="userSpaceOnUse"><stop offset=".014" class="ohfnw2bor"/><stop offset="1" class="njgnrtcml"/></radialGradient><radialGradient id="iGF37jH" cx="0" cy="0" r="1" gradientTransform="matrix(4.24468 -1.44104 .64706 1.90597 13.86 20.755)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="lm-pdjb-m"/><stop offset=".935" class="z17z3-a-u"/></radialGradient><radialGradient id="iQd0lBS" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25613 .78093 -.28093 -.45188 17.699 19.304)" gradientUnits="userSpaceOnUse"><stop class="xbybj_nwx"/><stop offset=".808" class="unvvv2nza"/></radialGradient><radialGradient id="iPgJHkB" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.71875 -3.74337 0 14.244 22.976)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="e9ucyqbno"/><stop offset="1" class="pzx_di4zn"/></radialGradient><radialGradient id="i3zGehb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.62922 -2.82735 0 17.734 23.55)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="e9ucyqbno"/><stop offset="1" class="pzx_di4zn"/></radialGradient><filter id="iwKVpwe" width="9.482" height="9.482" x="19.869" y="4.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4211" stdDeviation=".3"/></filter><filter id="iDzpRQO" width="9.282" height="9.282" x="3.126" y="4.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4211" stdDeviation=".25"/></filter><filter id="ibo1vgp" width="29" height="25.38" x="2.235" y="4.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.584314 0 0 0 0 0.643137 0 0 0 0.6 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4211"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.490196 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_4211" result="effect2_innerShadow_28327_4211"/></filter><filter id="iJxhQql" width="4.251" height="3.456" x="13.588" y="18.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4211" stdDeviation=".25"/></filter><filter id="i0eGUQc" width="2.469" height="3.805" x="10.353" y="14.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4211" stdDeviation=".25"/></filter><filter id="iHaqfrd" width="2.469" height="3.805" x="18.384" y="14.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4211" stdDeviation=".25"/></filter><filter id="ik4746d" width="8.555" height="3.743" x="11.563" y="22.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4211" stdDeviation=".25"/></filter><filter id="i2mq4bc" width="7.719" height="2.484" x="12.135" y="22.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4211" stdDeviation=".125"/></filter><filter id="idVSzae" width="1.353" height="2.844" x="11.586" y="14.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4211" stdDeviation=".25"/></filter><filter id="i0E0VWd" width="1.353" height="2.844" x="19.555" y="14.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4211" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:panda" /></template>
<style>
.a09rbyi7b {
  width: 1.469px;
  height: 2.805px;
  x: 18.884px;
  y: 15.367px;
  fill: var(--svg-color--45366a, #45366A);
  rx: 0.734px;
}

.ahy-6aczx {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M19.48 22.603c0 1.045-.78 1.894-1.74 1.894S16 23.648 16 22.603");
}

.argt23bhs {
  d: path("M19.054 19.797c1.602 1.601 3.735 1.468 5.047 0c1.508-1.602.726-3.617-.719-5.188c-1.617-1.758-2.803-2.212-4.273-.742s-1.525 4.46-.055 5.93");
}

.ayejg7zhn {
  d: path("M30.235 19.87c0 7.73-6.27 9.88-14 9.88s-14-2.15-14-9.88s6.27-14 14-14s14 6.26 14 14");
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b-2k86b_r {
  stop-color: var(--svg-color--f4f2f8, #F4F2F8);
}

.bhuvpx2ny {
  stop-color: var(--svg-color--413039, #413039);
}

.bv3kjqung {
  d: path("M7.767 14.07a4.555 4.555 0 1 0 0-9.11a4.555 4.555 0 0 0 0 9.11");
}

.c8cw4hbel {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.783 9.515a4.016 4.016 0 1 1-8.032 0a4.016 4.016 0 0 1 8.032 0Z");
}

.cctdiwbjb {
  stop-color: var(--svg-color--604685, #604685);
}

.dxzcax2ia {
  stop-color: var(--svg-color--bab0c7, #BAB0C7);
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e9ucyqbno {
  stop-color: var(--svg-color--423539, #423539);
}

.f8fib8bhj {
  stop-color: var(--svg-color--ebe3f5, #EBE3F5);
}

.fly8uzaif {
  stop-color: var(--svg-color--f4f2f8, #F4F2F8);
  stop-opacity: 0;
}

.fr_xrgbwn {
  stop-color: var(--svg-color--5a4a8a, #5A4A8A);
}

.ft5dv1b6b {
  fill: none;
}

.fwtna0oas {
  stop-color: var(--svg-color--2e2127, #2E2127);
}

.g8smzcklu {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M28.6 9.515a3.99 3.99 0 1 1-7.981 0a3.99 3.99 0 0 1 7.982 0Z");
}

.gf_bcjr-d {
  d: path("M12.936 19.797c-1.602 1.601-3.735 1.468-5.047 0c-1.508-1.602-.726-3.617.719-5.188c1.617-1.758 2.803-2.212 4.273-.742s1.525 4.46.055 5.93");
}

.h4lw7lb1g {
  width: 1.469px;
  height: 2.805px;
  x: 10.853px;
  y: 15.367px;
  fill: var(--svg-color--45366a, #45366A);
  rx: 0.734px;
}

.hdfeml-gx {
  width: 1.469px;
  height: 2.977px;
  x: 11.268px;
  y: 14.961px;
  rx: 0.734px;
}

.hircosu7l {
  stop-color: var(--svg-color--4d4175, #4D4175);
}

.hlfgozbwx {
  stop-color: var(--svg-color--6363a2, #6363A2);
}

.hyfbt3btq {
  stop-color: var(--svg-color--5a4482, #5A4482);
  stop-opacity: 0;
}

.i9-12bcno {
  fill: var(--svg-color--a081bc, #A081BC);
  fill-rule: evenodd;
  d: path("M13.011 23.019a.474.474 0 1 0-.947 0c0 1.214.914 2.27 2.123 2.27c.682 0 1.27-.337 1.654-.848c.383.51.972.847 1.654.847c1.209 0 2.124-1.055 2.124-2.27a.474.474 0 1 0-.948 0c0 .768-.565 1.322-1.176 1.322s-1.175-.554-1.175-1.321a.474.474 0 0 0-.474-.474h-.01a.474.474 0 0 0-.474.474c0 .767-.564 1.321-1.175 1.321s-1.176-.554-1.176-1.321");
}

.ityabbclb {
  fill: var(--svg-color--a081bc, #A081BC);
  d: path("M14.865 19.255h1.697c.655 0 .98.694.642 1.233c-.391.626-.94 1.02-.94 1.02a.92.92 0 0 1-.55.203a.92.92 0 0 1-.55-.203s-.55-.394-.941-1.02c-.338-.54-.012-1.233.642-1.233");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jrv-u9byp {
  stop-color: var(--svg-color--c7b0de, #C7B0DE);
  stop-opacity: 0;
}

.k1zvhqbgt {
  stop-color: var(--svg-color--dac8ed, #DAC8ED);
}

.kbkd0lbzx {
  stop-color: var(--svg-color--a997cf, #A997CF);
}

.kfv2ntbxs {
  d: path("M24.61 14.07a4.555 4.555 0 1 0 0-9.11a4.555 4.555 0 0 0 0 9.11");
}

.lhnqa3sxn {
  width: 1.469px;
  height: 2.977px;
  rx: 0.734px;
}

.ljfjt5shb {
  stop-color: var(--svg-color--e1d3f1, #E1D3F1);
}

.lm-pdjb-m {
  stop-color: var(--svg-color--5c5458, #5C5458);
  stop-opacity: 0;
}

.njgnrtcml {
  stop-color: var(--svg-color--5f4e87, #5F4E87);
  stop-opacity: 0;
}

.nvw_35bqd {
  stop-color: var(--svg-color--9a8bbd, #9A8BBD);
  stop-opacity: 0;
}

.ohfnw2bor {
  stop-color: var(--svg-color--5f4e87, #5F4E87);
}

.op476abrm {
  width: 0.353px;
  height: 1.844px;
  x: 20.055px;
  y: 15.406px;
  fill: var(--svg-color--665a5c, #665A5C);
  rx: 0.177px;
}

.p4zxw29sj {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M15.99 22.603c0 1.045-.78 1.894-1.74 1.894s-1.74-.849-1.74-1.894");
}

.p6vd50w9p {
  stop-color: var(--svg-color--5f5254, #5F5254);
}

.pixlyqoup {
  d: path("M15.113 18.958h1.774c.683 0 1.023.725.67 1.289a4.2 4.2 0 0 1-.982 1.065a.96.96 0 0 1-.575.212a.96.96 0 0 1-.575-.212s-.574-.411-.982-1.065c-.353-.564-.013-1.289.67-1.289");
}

.pzx_di4zn {
  stop-color: var(--svg-color--472849, #472849);
}

.qp07sgb8l {
  stop-color: var(--svg-color--e1d3f1, #E1D3F1);
  stop-opacity: 0;
}

.rez373ifa {
  stop-color: var(--svg-color--5a4482, #5A4482);
}

.rj14edb9i {
  stop-color: var(--svg-color--5f5356, #5F5356);
}

.u0dgzxinl {
  stop-color: var(--svg-color--c7b0de, #C7B0DE);
}

.uee69bc2u {
  stop-color: var(--svg-color--4e4b84, #4E4B84);
}

.ueu24dben {
  stop-color: var(--svg-color--34222c, #34222C);
  stop-opacity: 0;
}

.unvvv2nza {
  stop-color: var(--svg-color--6a5c5e, #6A5C5E);
  stop-opacity: 0;
}

.upkeozbze {
  stop-color: var(--svg-color--bab0c7, #BAB0C7);
  stop-opacity: 0;
}

.vaomm_byr {
  stop-color: var(--svg-color--4d4175, #4D4175);
  stop-opacity: 0;
}

.vh3k8hojv {
  stop-color: var(--svg-color--492847, #492847);
}

.vylhu7i4w {
  stop-color: var(--svg-color--34222c, #34222C);
}

.wr3aow-0r {
  width: 0.353px;
  height: 1.844px;
  x: 12.086px;
  y: 15.406px;
  fill: var(--svg-color--665a5c, #665A5C);
  rx: 0.177px;
}

.xbybj_nwx {
  stop-color: var(--svg-color--6a5c5e, #6A5C5E);
}

.xt8tsubzf {
  stop-color: var(--svg-color--706aa5, #706AA5);
}

.y7mi9klsn {
  stop-color: var(--svg-color--4e4b84, #4E4B84);
  stop-opacity: 0;
}

.z17z3-a-u {
  stop-color: var(--svg-color--5c5458, #5C5458);
}

.zkps8y4ss {
  stop-color: var(--svg-color--5f5356, #5F5356);
  stop-opacity: 0;
}

.znpx77bhc {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.51 22.603c.042.521.534 1.581 1.61 1.656c1.343.094 1.812-.968 1.859-1.656c-.026.552.578 1.735 1.844 1.735c1.087 0 1.599-1.183 1.656-1.735");
}

</style>
