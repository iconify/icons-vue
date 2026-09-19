<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isCB3Tb)"><path fill="url(#iFeFBme)" class="z5gkcf-av"/></g><path fill="url(#i9AuqTc)" class="z5gkcf-av"/><path fill="url(#iJOdMpd)" class="z5gkcf-av"/><g filter="url(#iM1iD0b)"><rect fill="url(#iIXoNZb)" class="kgq1yxb-w"/></g><g filter="url(#isLZpdJ)"><path class="s4hyevbxp"/></g><rect fill="url(#iSQG12z)" class="yqrsv_hxq"/><rect fill="url(#iwEADpd)" class="yqrsv_hxq"/><rect fill="url(#iE446mT)" class="yqrsv_hxq"/><rect fill="url(#i5JduCe)" class="yqrsv_hxq"/><path fill="url(#i7rI83d)" class="oz9fqcisu"/><path fill="url(#igduBoJ)" class="oz9fqcisu"/><path fill="url(#igQ2apd)" class="oz9fqcisu"/><path fill="url(#isdmmpc)" class="oz9fqcisu"/><path fill="url(#itAx8ze)" class="oz9fqcisu"/><rect class="q1vclbzpe"/><rect fill="url(#ivJ5Mtd)" class="tcvr7tulc"/><rect fill="url(#iWucXTc)" class="tcvr7tulc"/><rect fill="url(#icq2HLe)" class="tcvr7tulc"/><rect fill="url(#iIFSqBT)" class="tcvr7tulc"/><path fill="url(#iXBAMtd)" class="e599lnq0o"/><path fill="url(#iq9Rpnn)" class="e599lnq0o"/><path fill="url(#i721Nhb)" class="e599lnq0o"/><path fill="url(#isbI6zd)" class="e599lnq0o"/><path fill="url(#iRYp1ec)" class="e599lnq0o"/><path fill="url(#ipMeuYb)" class="e599lnq0o"/><path fill="url(#isoLmOb)" class="k0zn1ebow"/><path fill="url(#iaZIDne)" class="k0zn1ebow"/><path fill="url(#iV5gLKk)" class="k0zn1ebow"/><path fill="url(#infNqcb)" class="k0zn1ebow"/><g filter="url(#icJn3On)"><path stroke="url(#ia3UVIe)" class="nq9o5_b-r"/></g><defs><radialGradient id="iFeFBme" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3034 -15.1439 0 16 17.516)" gradientUnits="userSpaceOnUse"><stop class="kqi4_2zev"/><stop offset="1" class="kmo462q3f"/></radialGradient><radialGradient id="i9AuqTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.0399 -20.6277 0 16 18.075)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="dd9iqwbqy"/><stop offset="1" class="ne4uvs7co"/></radialGradient><radialGradient id="iJOdMpd" cx="0" cy="0" r="1" gradientTransform="rotate(136.801 4.779 12.054)scale(14.2398 19.6064)" gradientUnits="userSpaceOnUse"><stop offset=".779" class="y71t_3b5f"/><stop offset="1" class="w_6rk9g3u"/></radialGradient><radialGradient id="iSQG12z" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86026 0 0 -6.52072 8.233 10.438)" gradientUnits="userSpaceOnUse"><stop class="tha4aebnq"/><stop offset="1" class="gebfavb2s"/></radialGradient><radialGradient id="iwEADpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.80979 -6.7763 0 6.885 7.064)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="bhmvtcqcb"/><stop offset="1" class="o5t1rxbfx"/></radialGradient><radialGradient id="iE446mT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67954 0 0 -10.0187 9.663 10.126)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="rsdyx2plm"/><stop offset="1" class="jdtbhlbis"/></radialGradient><radialGradient id="i5JduCe" cx="0" cy="0" r="1" gradientTransform="matrix(1.22807 1.63545 -3.19277 2.39747 4.202 5.531)" gradientUnits="userSpaceOnUse"><stop class="pizvzlbar"/><stop offset="1" class="zrt_8wbir"/></radialGradient><radialGradient id="i7rI83d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86026 0 0 -7.46434 13.49 9.752)" gradientUnits="userSpaceOnUse"><stop class="tha4aebnq"/><stop offset="1" class="gebfavb2s"/></radialGradient><radialGradient id="igduBoJ" cx="0" cy="0" r="1" gradientTransform="matrix(.97058 9.2143 -6.98425 .73568 12.142 5.89)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="bhmvtcqcb"/><stop offset="1" class="o5t1rxbfx"/></radialGradient><radialGradient id="igQ2apd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7514 0 0 -11.9592 15.537 9.394)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="rsdyx2plm"/><stop offset="1" class="jdtbhlbis"/></radialGradient><radialGradient id="isdmmpc" cx="0" cy="0" r="1" gradientTransform="matrix(1.57034 0 0 10.7229 8.177 9.394)" gradientUnits="userSpaceOnUse"><stop offset=".089" class="rsdyx2plm"/><stop offset="1" class="jdtbhlbis"/></radialGradient><radialGradient id="itAx8ze" cx="0" cy="0" r="1" gradientTransform="rotate(56.736 .901 10.826)scale(2.23897 4.17494)" gradientUnits="userSpaceOnUse"><stop class="pizvzlbar"/><stop offset="1" class="zrt_8wbir"/></radialGradient><radialGradient id="ivJ5Mtd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86026 0 0 -7.77671 25.776 8.92)" gradientUnits="userSpaceOnUse"><stop class="m9s3l41cu"/><stop offset="1" class="yfq_4er5h"/></radialGradient><radialGradient id="iWucXTc" cx="0" cy="0" r="1" gradientTransform="matrix(.89774 11.336 -8.25444 .6537 24.428 4.897)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="bhmvtcqcb"/><stop offset="1" class="o5t1rxbfx"/></radialGradient><radialGradient id="icq2HLe" cx="0" cy="0" r="1" gradientTransform="matrix(1.36406 0 0 10.9671 21.361 8.548)" gradientUnits="userSpaceOnUse"><stop class="rsdyx2plm"/><stop offset="1" class="jdtbhlbis"/></radialGradient><radialGradient id="iIFSqBT" cx="0" cy="0" r="1" gradientTransform="rotate(57.804 8.094 21.228)scale(2.30488 4.22527)" gradientUnits="userSpaceOnUse"><stop class="pizvzlbar"/><stop offset="1" class="zrt_8wbir"/></radialGradient><radialGradient id="iXBAMtd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.69201 0 0 -8.04356 19.73 8.951)" gradientUnits="userSpaceOnUse"><stop class="kkoj0ryaq"/><stop offset="1" class="tqg0g5mfs"/></radialGradient><radialGradient id="iq9Rpnn" cx="0" cy="0" r="1" gradientTransform="rotate(84.743 6.324 12.434)scale(10.4391 6.92894)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="bhmvtcqcb"/><stop offset="1" class="o5t1rxbfx"/></radialGradient><radialGradient id="i721Nhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92538 0 0 -7.23475 21.693 8.951)" gradientUnits="userSpaceOnUse"><stop class="rsdyx2plm"/><stop offset="1" class="jdtbhlbis"/></radialGradient><radialGradient id="isbI6zd" cx="0" cy="0" r="1" gradientTransform="matrix(1.54732 0 0 12.0971 14.219 8.951)" gradientUnits="userSpaceOnUse"><stop offset=".089" class="rsdyx2plm"/><stop offset="1" class="jdtbhlbis"/></radialGradient><radialGradient id="iRYp1ec" cx="0" cy="0" r="1" gradientTransform="rotate(60.19 5.138 14.865)scale(2.43413 4.26884)" gradientUnits="userSpaceOnUse"><stop class="pizvzlbar"/><stop offset="1" class="zrt_8wbir"/></radialGradient><radialGradient id="ipMeuYb" cx="0" cy="0" r="1" gradientTransform="rotate(-103.591 13.127 -.605)scale(3.99078 4.11014)" gradientUnits="userSpaceOnUse"><stop class="hbzb5ybhq"/><stop offset="1" class="y64lorndh"/></radialGradient><radialGradient id="isoLmOb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0336 5.97998 -11.68396 -2.0195 24.445 11.974)" gradientUnits="userSpaceOnUse"><stop class="qlllb_b3i"/><stop offset="1" class="juxl-vb0u"/></radialGradient><radialGradient id="iaZIDne" cx="0" cy="0" r="1" gradientTransform="matrix(3.22676 -6.40043 7.33582 3.69833 25.283 21.525)" gradientUnits="userSpaceOnUse"><stop class="x-yefcbjg"/><stop offset="1" class="mghph-bar"/></radialGradient><radialGradient id="iV5gLKk" cx="0" cy="0" r="1" gradientTransform="matrix(3.74677 0 0 5.4251 14.24 13.267)" gradientUnits="userSpaceOnUse"><stop class="nsys4yhhm"/><stop offset="1" class="f1rqhz8he"/></radialGradient><radialGradient id="infNqcb" cx="0" cy="0" r="1" gradientTransform="matrix(1.14015 -.98439 1.64762 1.90833 15.307 15.661)" gradientUnits="userSpaceOnUse"><stop class="d4e41kbji"/><stop offset="1" class="ke9c0vb6e"/></radialGradient><filter id="isCB3Tb" width="25.02" height="20.828" x="3.49" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.211765 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3140"/></filter><filter id="iM1iD0b" width="18.678" height="12.194" x="7.28" y="9.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3140" stdDeviation="1.5"/></filter><filter id="isLZpdJ" width="24.653" height="14.935" x="3.21" y="3.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3140" stdDeviation="1"/></filter><filter id="icJn3On" width="12.76" height="8.553" x="17.128" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3140" stdDeviation=".85"/></filter><linearGradient id="iIXoNZb" x1="20.393" x2="8.571" y1="17.241" y2="21.196" gradientUnits="userSpaceOnUse"><stop class="nhul3ib1x"/><stop offset="1" class="d5809ga2c"/></linearGradient><linearGradient id="ia3UVIe" x1="19.828" x2="31.13" y1="12.402" y2="16.093" gradientUnits="userSpaceOnUse"><stop class="qf0idjn-o"/><stop offset="1" class="eoju1fbkk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-fist-medium-dark" /></template>
<style>
.bhmvtcqcb {
  stop-color: var(--svg-color--703e53, #703E53);
  stop-opacity: 0;
}

.d4e41kbji {
  stop-color: var(--svg-color--775050, #775050);
}

.d5809ga2c {
  stop-color: var(--svg-color--4e2a2f, #4E2A2F);
  stop-opacity: 0;
}

.dd9iqwbqy {
  stop-color: var(--svg-color--824b7b, #824B7B);
  stop-opacity: 0;
}

.e599lnq0o {
  d: path("M14.78 5.675c0-1.847 1.498-3.166 3.345-3.166a3.345 3.345 0 0 1 3.346 3.346v6.192a3.345 3.345 0 0 1-6.69 0z");
}

.eoju1fbkk {
  stop-color: var(--svg-color--9e786f, #9E786F);
  stop-opacity: 0;
}

.f1rqhz8he {
  stop-color: var(--svg-color--68463a, #68463A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gebfavb2s {
  stop-color: var(--svg-color--794f3e, #794F3E);
}

.hbzb5ybhq {
  stop-color: var(--svg-color--62443c, #62443C);
}

.jdtbhlbis {
  stop-color: var(--svg-color--653f32, #653F32);
  stop-opacity: 0;
}

.juxl-vb0u {
  stop-color: var(--svg-color--743e55, #743E55);
}

.k0zn1ebow {
  d: path("M18.339 9.797c-1.965 0-3.559 1.507-3.559 3.365s1.594 3.365 3.559 3.365h2.602c1.168 0 2.115.896 2.115 2v2.998h.2c3.464 0 5.254-3.02 5.254-5.765c0-3.293-2.823-5.963-6.306-5.963z");
}

.ke9c0vb6e {
  stop-color: var(--svg-color--775050, #775050);
  stop-opacity: 0;
}

.kgq1yxb-w {
  width: 12.678px;
  height: 6.195px;
  x: 10.28px;
  y: 12.903px;
  rx: 3.097px;
}

.kkoj0ryaq {
  stop-color: var(--svg-color--94746e, #94746E);
}

.kmo462q3f {
  stop-color: var(--svg-color--7e4f57, #7E4F57);
}

.kqi4_2zev {
  stop-color: var(--svg-color--6d4747, #6D4747);
}

.m9s3l41cu {
  stop-color: var(--svg-color--a58074, #A58074);
}

.mghph-bar {
  stop-color: var(--svg-color--774d51, #774D51);
  stop-opacity: 0;
}

.ne4uvs7co {
  stop-color: var(--svg-color--894278, #894278);
}

.nhul3ib1x {
  stop-color: var(--svg-color--4e2a2f, #4E2A2F);
}

.nq9o5_b-r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.828 12.25h2.14c3.187-.131 4.706 1.01 5.22 3.143");
}

.nsys4yhhm {
  stop-color: var(--svg-color--68463a, #68463A);
}

.o5t1rxbfx {
  stop-color: var(--svg-color--703e53, #703E53);
}

.oz9fqcisu {
  d: path("M8.747 7.08c0-2.35 1.52-3.396 3.395-3.396a3.395 3.395 0 0 1 3.395 3.395v4.509c0 1.875-1.52 3.516-3.395 3.516s-3.395-1.085-3.395-3.516z");
}

.pizvzlbar {
  stop-color: var(--svg-color--7c665e, #7C665E);
}

.q1vclbzpe {
  width: 6.79px;
  height: 11.898px;
  x: 21.033px;
  y: 2.599px;
  fill: var(--svg-color--7dde5b, #7DDE5B);
  fill-opacity: var(--svg-fill-opacity--0-55, 0.55);
  rx: 3.395px;
}

.qf0idjn-o {
  stop-color: var(--svg-color--9e786f, #9E786F);
}

.qlllb_b3i {
  stop-color: var(--svg-color--986f5e, #986F5E);
}

.rsdyx2plm {
  stop-color: var(--svg-color--643e2f, #643E2F);
}

.s4hyevbxp {
  fill: var(--svg-color--3e1d26, #3E1D26);
  d: path("M15.024 14.283c-.504.868-1.422 1.472-2.47 1.472c-.93 0-1.757-.314-2.283-.987a2.882 2.882 0 0 1-5.06-1.886v-2.704a2.882 2.882 0 0 1 4.61-2.306c.383-1.244 1.462-1.81 2.733-1.81c.936 0 1.768.447 2.294 1.138c.26-1.272 1.408-2.135 2.785-2.135a2.84 2.84 0 0 1 2.674 1.884a2.882 2.882 0 0 1 5.556 1.074v4.335a2.882 2.882 0 0 1-5.44 1.327a2.84 2.84 0 0 1-5.4.598");
}

.tcvr7tulc {
  width: 6.79px;
  height: 11.898px;
  x: 21.033px;
  y: 2.599px;
  rx: 3.395px;
}

.tha4aebnq {
  stop-color: var(--svg-color--896b65, #896B65);
}

.tqg0g5mfs {
  stop-color: var(--svg-color--815644, #815644);
}

.w_6rk9g3u {
  stop-color: var(--svg-color--846058, #846058);
}

.x-yefcbjg {
  stop-color: var(--svg-color--774d51, #774D51);
}

.y64lorndh {
  stop-color: var(--svg-color--62443c, #62443C);
  stop-opacity: 0;
}

.y71t_3b5f {
  stop-color: var(--svg-color--846058, #846058);
  stop-opacity: 0;
}

.yfq_4er5h {
  stop-color: var(--svg-color--8b5f4b, #8B5F4B);
}

.yqrsv_hxq {
  width: 6.79px;
  height: 9.976px;
  x: 3.49px;
  y: 5.138px;
  rx: 3.395px;
}

.z5gkcf-av {
  d: path("M27.823 9.479H3.49v9.328c0 6.351 5.149 11.5 11.5 11.5h1.333c2.153 0 4.168-.592 5.89-1.621l.005.018c2.518-1.454 5.089-4.099 5.904-7.358c.83-3.325.134-5.707-.3-6.552z");
}

.zrt_8wbir {
  stop-color: var(--svg-color--7c665e, #7C665E);
  stop-opacity: 0;
}

</style>
