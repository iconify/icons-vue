<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="wa7b88b9s"/><path fill="url(#ibtqH1c)" class="vfjdlkb1p"/><g filter="url(#iH1WZRb)"><path class="te6qkzd7t"/><path fill="url(#ilEOlXD)" class="m89_8d6bn"/><path fill="url(#igadzYb)" class="m89_8d6bn"/><path fill="url(#iGIKvdb)" class="m89_8d6bn"/><path fill="url(#iuD1c4F)" class="m89_8d6bn"/><path fill="url(#iIzEH5b)" class="m89_8d6bn"/></g><path class="uhkx7vb2m"/><path fill="url(#iehCSHc)" class="wzofkz0xc"/><path fill="url(#iALRiec)" class="wzofkz0xc"/><path fill="url(#ioxHbyd)" class="wzofkz0xc"/><path fill="url(#iZPfXhy)" class="wzofkz0xc"/><path fill="url(#iLGL5ke)" class="wzofkz0xc"/><path fill="url(#i19gT8d)" class="rdxah9m0p"/><g filter="url(#ifENlLc)"><path stroke="url(#i4zTR5c)" class="aalom_-lr"/></g><path fill="url(#iQBlTgY)" class="arog1ofog"/><path fill="url(#ibjUGxe)" class="arog1ofog"/><g filter="url(#irPhfad)"><path fill="url(#itt502A)" class="ewg6g6bkh"/></g><g filter="url(#is9r57L)"><path fill="url(#is5HSSi)" class="wy56it9pj"/></g><g filter="url(#iUi178c)"><path fill="url(#iXiasUd)" class="gfveo9bef"/></g><path fill="url(#iTKNced)" class="vnl8evqia"/><path class="jk_iytadn"/><path fill="url(#ifM76dc)" class="mykig9nlm"/><path fill="url(#iKbqUxb)" class="spdk_uktp"/><g filter="url(#i1tTtYb)"><ellipse class="xcxys-b8q"/></g><defs><radialGradient id="ibtqH1c" cx="0" cy="0" r="1" gradientTransform="matrix(-5.62506 10 -10 -5.62506 21 12)" gradientUnits="userSpaceOnUse"><stop class="s8n_ddctx"/><stop offset=".452" class="t7aq-xbix"/><stop offset="1" class="r56pieb5r"/></radialGradient><radialGradient id="ilEOlXD" cx="0" cy="0" r="1" gradientTransform="rotate(129.523 8.673 8.825)scale(12.9639 14.3163)" gradientUnits="userSpaceOnUse"><stop class="pq_yz7wsr"/><stop offset=".451" class="ekwe_l5on"/><stop offset="1" class="uq7tfac1y"/></radialGradient><radialGradient id="iGIKvdb" cx="0" cy="0" r="1" gradientTransform="rotate(140.793 10.043 11.746)scale(6.1301 2.87771)" gradientUnits="userSpaceOnUse"><stop class="ime36tbxo"/><stop offset="1" class="ua0iqtbgc"/></radialGradient><radialGradient id="iuD1c4F" cx="0" cy="0" r="1" gradientTransform="matrix(5.5 0 0 8.8125 10.5 16.375)" gradientUnits="userSpaceOnUse"><stop offset=".466" class="l7pdxfb7x"/><stop offset=".545" class="bet18vuvv"/></radialGradient><radialGradient id="iehCSHc" cx="0" cy="0" r="1" gradientTransform="rotate(129.523 8.762 8.637)scale(12.9639 14.3163)" gradientUnits="userSpaceOnUse"><stop class="pq_yz7wsr"/><stop offset=".451" class="ekwe_l5on"/><stop offset="1" class="uq7tfac1y"/></radialGradient><radialGradient id="ioxHbyd" cx="0" cy="0" r="1" gradientTransform="rotate(140.793 10.11 11.559)scale(6.1301 2.87771)" gradientUnits="userSpaceOnUse"><stop class="ime36tbxo"/><stop offset="1" class="ua0iqtbgc"/></radialGradient><radialGradient id="iZPfXhy" cx="0" cy="0" r="1" gradientTransform="matrix(5.5 0 0 8.8125 10.5 16)" gradientUnits="userSpaceOnUse"><stop offset=".466" class="l7pdxfb7x"/><stop offset=".545" class="bet18vuvv"/></radialGradient><radialGradient id="iLGL5ke" cx="0" cy="0" r="1" gradientTransform="matrix(4.9375 0 0 8.07417 21.688 15.563)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="f6tol7b5z"/><stop offset=".509" class="bet18vuvv"/></radialGradient><radialGradient id="iQBlTgY" cx="0" cy="0" r="1" gradientTransform="matrix(11.75 -7.25 14.10245 22.85567 10.875 25.25)" gradientUnits="userSpaceOnUse"><stop offset=".137" class="v-hbcx7uu"/><stop offset=".416" class="rkhf_ll_l"/><stop offset=".68" class="u9j3i8tex"/><stop offset="1" class="cmqxpg37l"/></radialGradient><radialGradient id="itt502A" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 .53946 -.50007 -.9994 13.203 5.618)" gradientUnits="userSpaceOnUse"><stop class="qu7t_nscv"/><stop offset="1" class="t0_lblbis"/></radialGradient><radialGradient id="is5HSSi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 .53946 -.50007 -.9994 11.203 6.697)" gradientUnits="userSpaceOnUse"><stop class="qu7t_nscv"/><stop offset="1" class="t0_lblbis"/></radialGradient><radialGradient id="iXiasUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 .53946 -.50007 -.9994 13.203 7.68)" gradientUnits="userSpaceOnUse"><stop offset=".084" class="yphlmqbru"/><stop offset="1" class="t0_lblbis"/></radialGradient><radialGradient id="iTKNced" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 .7606 -.7606 -.5 13.719 5.297)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="xvo9clb-v"/><stop offset=".855" class="c-tzvyb-w"/></radialGradient><radialGradient id="ifM76dc" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 .7606 -.7606 -.5 11.734 6.281)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="xvo9clb-v"/><stop offset=".855" class="c-tzvyb-w"/></radialGradient><radialGradient id="iKbqUxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 .7606 -.7606 -.5 13.719 7.349)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="xvo9clb-v"/><stop offset=".855" class="c-tzvyb-w"/></radialGradient><linearGradient id="igadzYb" x1="16" x2="10" y1="2.375" y2="17.125" gradientUnits="userSpaceOnUse"><stop offset=".399" class="nzcixnn4b"/><stop offset=".953" class="o71l59bmg"/></linearGradient><linearGradient id="iIzEH5b" x1="22" x2="8.779" y1="13.188" y2="13.188" gradientUnits="userSpaceOnUse"><stop class="oxwwndfsy"/><stop offset=".889" class="lylbn6dfa"/></linearGradient><linearGradient id="iALRiec" x1="16" x2="10" y1="2" y2="16.75" gradientUnits="userSpaceOnUse"><stop offset=".399" class="nzcixnn4b"/><stop offset=".953" class="o71l59bmg"/></linearGradient><linearGradient id="i19gT8d" x1="20.063" x2="24.875" y1="18" y2="8" gradientUnits="userSpaceOnUse"><stop class="hfgelgu-f"/><stop offset="1" class="thxal-b2p"/></linearGradient><linearGradient id="i4zTR5c" x1="25.188" x2="20.406" y1="9.438" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="jy2gxibjv"/><stop offset="1" class="pqca5r3ox"/></linearGradient><linearGradient id="ibjUGxe" x1="20.813" x2="19.875" y1="23.313" y2="22.688" gradientUnits="userSpaceOnUse"><stop offset=".138" class="wx-01ob2u"/><stop offset="1" class="p3trr-bza"/></linearGradient><filter id="iH1WZRb" width="18.314" height="10.639" x="7.779" y="6.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28637" stdDeviation=".5"/></filter><filter id="ifENlLc" width="6.969" height="11.813" x="19.437" y="7.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28637" stdDeviation=".375"/></filter><filter id="irPhfad" width="1.908" height="1.579" x="12.172" y="4.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28637" stdDeviation=".125"/></filter><filter id="is9r57L" width="1.908" height="1.579" x="10.172" y="5.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28637" stdDeviation=".125"/></filter><filter id="iUi178c" width="1.908" height="1.579" x="12.172" y="6.89" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28637" stdDeviation=".125"/></filter><filter id="i1tTtYb" width="1.648" height="1.688" x="24.625" y="7.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28637" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:shaved-ice" /></template>
<style>
.aalom_-lr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m20.563 18.469l4.718-9.563");
}

.arog1ofog {
  d: path("m8 18l7.41 11.68a.7.7 0 0 0 1.18 0L24 18z");
}

.bet18vuvv {
  stop-color: var(--svg-color--de60c3, #DE60C3);
  stop-opacity: 0;
}

.c-tzvyb-w {
  stop-color: var(--svg-color--e2c9e5, #E2C9E5);
}

.cmqxpg37l {
  stop-color: var(--svg-color--5fd4ff, #5FD4FF);
}

.ekwe_l5on {
  stop-color: var(--svg-color--ff97e4, #FF97E4);
}

.ewg6g6bkh {
  d: path("M13.296 6.156c.295 0 .534-.181.534-.476s-.239-.602-.534-.602c-.294 0-.874.518-.874.813s.58.265.874.265");
}

.f6tol7b5z {
  stop-color: var(--svg-color--ff67cc, #FF67CC);
}

.ft5dv1b6b {
  fill: none;
}

.gfveo9bef {
  d: path("M13.296 8.218c.295 0 .534-.182.534-.476c0-.295-.239-.602-.534-.602c-.294 0-.874.517-.874.812s.58.266.874.266");
}

.hfgelgu-f {
  stop-color: var(--svg-color--2e9cf8, #2E9CF8);
}

.ime36tbxo {
  stop-color: var(--svg-color--ff74de, #FF74DE);
}

.jk_iytadn {
  fill: var(--svg-color--e5d6eb, #E5D6EB);
  d: path("M11.5 7.042a.534.534 0 1 0 0-1.068a.534.534 0 0 0 0 1.068");
}

.jy2gxibjv {
  stop-color: var(--svg-color--5ac6ff, #5AC6FF);
}

.l7pdxfb7x {
  stop-color: var(--svg-color--db62c1, #DB62C1);
}

.lylbn6dfa {
  stop-color: var(--svg-color--c9939b, #C9939B);
}

.m89_8d6bn {
  d: path("M8.81 13.595c.23-.74.92-1.22 1.68-1.22s1.842.49 2.073 1.21c.51 1.62 1.627 2.134 3.417 2.134s2.947-.514 3.457-2.124c.23-.73 1.273-1.21 2.033-1.21h.04c.76 0 1.729.114 1.959.834c.34 1.07.615 1.415 1.625 1.875C23.524 2.9 8 6.469 8.81 13.595");
}

.mykig9nlm {
  d: path("M11.5 7.042a.534.534 0 1 0 0-1.068a.534.534 0 0 0 0 1.068");
}

.nzcixnn4b {
  stop-color: var(--svg-color--ff80e1, #FF80E1);
  stop-opacity: 0;
}

.o71l59bmg {
  stop-color: var(--svg-color--e153bb, #E153BB);
}

.oxwwndfsy {
  stop-color: var(--svg-color--e9b4af, #E9B4AF);
}

.p3trr-bza {
  stop-color: var(--svg-color--64b6ff, #64B6FF);
  stop-opacity: 0;
}

.pq_yz7wsr {
  stop-color: var(--svg-color--ffbaea, #FFBAEA);
}

.pqca5r3ox {
  stop-color: var(--svg-color--3facff, #3FACFF);
}

.qu7t_nscv {
  stop-color: var(--svg-color--cd7ba2, #CD7BA2);
}

.r56pieb5r {
  stop-color: var(--svg-color--d8aebd, #D8AEBD);
  stop-opacity: 0;
}

.rdxah9m0p {
  d: path("M25.1 8c.66 0 1.09.69.8 1.28L21.65 18h-1.98l4.63-9.5c.15-.31.47-.5.8-.5");
}

.rkhf_ll_l {
  stop-color: var(--svg-color--60bcff, #60BCFF);
}

.s8n_ddctx {
  stop-color: var(--svg-color--ffede4, #FFEDE4);
}

.spdk_uktp {
  d: path("M13.484 8.11a.534.534 0 1 0 0-1.068a.534.534 0 0 0 0 1.067");
}

.t0_lblbis {
  stop-color: var(--svg-color--cd7ba2, #CD7BA2);
  stop-opacity: 0;
}

.t7aq-xbix {
  stop-color: var(--svg-color--ffdbdf, #FFDBDF);
}

.te6qkzd7t {
  fill: var(--svg-color--e17ca3, #E17CA3);
  d: path("M8.81 13.595c.23-.74.92-1.22 1.68-1.22s1.842.49 2.073 1.21c.51 1.62 1.627 2.134 3.417 2.134s2.947-.514 3.457-2.124c.23-.73 1.273-1.21 2.033-1.21h.04c.76 0 1.729.114 1.959.834c.34 1.07.615 1.415 1.625 1.875C23.524 2.9 8 6.469 8.81 13.595");
}

.thxal-b2p {
  stop-color: var(--svg-color--42b6f8, #42B6F8);
}

.u9j3i8tex {
  stop-color: var(--svg-color--62d2ff, #62D2FF);
}

.ua0iqtbgc {
  stop-color: var(--svg-color--ff73db, #FF73DB);
  stop-opacity: 0;
}

.uhkx7vb2m {
  fill: var(--svg-color--e17ca3, #E17CA3);
  d: path("M16 2C10.48 2 6 6.48 6 12c0 1.28.24 2.5.68 3.63a4 4 0 0 0 2.13-2.41c.23-.74.92-1.22 1.68-1.22s1.45.49 1.68 1.21A3.99 3.99 0 0 0 15.98 16c1.79 0 3.3-1.17 3.81-2.78c.23-.73.92-1.21 1.68-1.21h.04c.76 0 1.45.49 1.68 1.21a3.98 3.98 0 0 0 2.13 2.41c.44-1.13.68-2.35.68-3.63c-.01-5.52-4.48-10-10-10");
}

.uq7tfac1y {
  stop-color: var(--svg-color--ff83e1, #FF83E1);
  stop-opacity: 0;
}

.v-hbcx7uu {
  stop-color: var(--svg-color--518ef4, #518EF4);
}

.vfjdlkb1p {
  d: path("M16 22c5.523 0 10-4.477 10-10S21.523 2 16 2S6 6.477 6 12s4.477 10 10 10");
}

.vnl8evqia {
  d: path("M13.484 6.057a.534.534 0 1 0 0-1.067a.534.534 0 0 0 0 1.067");
}

.wa7b88b9s {
  fill: var(--svg-color--cda3af, #CDA3AF);
  d: path("M16 22c5.523 0 10-4.477 10-10S21.523 2 16 2S6 6.477 6 12s4.477 10 10 10");
}

.wx-01ob2u {
  stop-color: var(--svg-color--64bdff, #64BDFF);
}

.wy56it9pj {
  d: path("M11.296 7.235c.295 0 .534-.181.534-.476s-.239-.602-.534-.602c-.294 0-.874.518-.874.813s.58.265.874.265");
}

.wzofkz0xc {
  d: path("M16 2C10.48 2 6 6.48 6 12c0 1.28.24 2.5.68 3.63a4 4 0 0 0 2.13-2.41c.23-.74.92-1.22 1.68-1.22s1.45.49 1.68 1.21A3.99 3.99 0 0 0 15.98 16c1.79 0 3.3-1.17 3.81-2.78c.23-.73.92-1.21 1.68-1.21h.04c.76 0 1.45.49 1.68 1.21a3.98 3.98 0 0 0 2.13 2.41c.44-1.13.68-2.35.68-3.63c-.01-5.52-4.48-10-10-10");
}

.xcxys-b8q {
  cx: 25.449px;
  cy: 8.656px;
  fill: var(--svg-color--74d8ff, #74D8FF);
  rx: 0.324px;
  ry: 0.344px;
}

.xvo9clb-v {
  stop-color: var(--svg-color--fbedfd, #FBEDFD);
}

.yphlmqbru {
  stop-color: var(--svg-color--cb71ae, #CB71AE);
}

</style>
