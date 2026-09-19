<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i0RQFPd)"><path fill="url(#i6jkFSG)" class="g8wq_wx5x"/><path fill="url(#ioEdHub)" class="g8wq_wx5x"/><path fill="url(#i77VLOd)" class="g8wq_wx5x"/></g><path fill="url(#ib0z3Ab)" class="g8wq_wx5x"/><path fill="url(#i2wFOgc)" class="g8wq_wx5x"/><path fill="url(#iJ6uG6d)" class="g8wq_wx5x"/><g filter="url(#iiyaMmc)"><path class="rps5mdbwf"/></g><g filter="url(#iMuCVkc)"><path class="sxe6fjbjf"/></g><rect fill="url(#iYJIFVd)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#iVW2sib)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#iOakGyd)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#idxsMwD)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#iLPgMvd)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#iCkVsMr)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#ioiljON)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#ikYDQFb)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#ikDej3d)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#iPTTLad)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#iqnkDxb)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#iQfAPAb)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#iBiyrxe)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#iGQASDb)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><rect fill="url(#isFR1me)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><rect fill="url(#iztsWvc)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><rect fill="url(#iiFriXb)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><defs><radialGradient id="ioEdHub" cx="0" cy="0" r="1" gradientTransform="rotate(90.785 -3.306 18.257)scale(6.84439 2.83792)" gradientUnits="userSpaceOnUse"><stop class="iz71evb-c"/><stop offset="1" class="ksm6foavx"/></radialGradient><radialGradient id="i77VLOd" cx="0" cy="0" r="1" gradientTransform="rotate(-63.938 22.844 -6.436)scale(7.24207 13.4771)" gradientUnits="userSpaceOnUse"><stop class="e95_-e25f"/><stop offset="1" class="xh_x769_k"/></radialGradient><radialGradient id="ib0z3Ab" cx="0" cy="0" r="1" gradientTransform="matrix(-6.09874 3.46893 -3.9808 -6.99866 24.688 7.567)" gradientUnits="userSpaceOnUse"><stop class="r_tw_ub5a"/><stop offset="1" class="ph-1oee-a"/></radialGradient><radialGradient id="i2wFOgc" cx="0" cy="0" r="1" gradientTransform="matrix(4.64396 0 0 9.96517 20.089 26.084)" gradientUnits="userSpaceOnUse"><stop class="b4u8r1bra"/><stop offset="1" class="jx6hehbgz"/></radialGradient><radialGradient id="iJ6uG6d" cx="0" cy="0" r="1" gradientTransform="scale(12.9389 20.0228)rotate(90 .42 .93)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="mmj7b4bwh"/><stop offset="1" class="jcexmac5l"/></radialGradient><radialGradient id="iOakGyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.58086 2.00356 0 10.449 28.655)" gradientUnits="userSpaceOnUse"><stop class="j4-11dbix"/><stop offset="1" class="h7dlqpbjb"/></radialGradient><radialGradient id="idxsMwD" cx="0" cy="0" r="1" gradientTransform="matrix(-.17279 -7.31561 8.00204 -.189 9.788 28.327)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="zk-r_ccij"/><stop offset="1" class="i8znvkyin"/></radialGradient><radialGradient id="iLPgMvd" cx="0" cy="0" r="1" gradientTransform="matrix(-.9313 0 0 -4.89838 11.409 24.948)" gradientUnits="userSpaceOnUse"><stop class="d0pow_blg"/><stop offset="1" class="p4nrjb94k"/></radialGradient><radialGradient id="ioiljON" cx="0" cy="0" r="1" gradientTransform="matrix(1.06838 0 0 4.40184 8.078 12.125)" gradientUnits="userSpaceOnUse"><stop class="gx15q4owu"/><stop offset="1" class="xg9-s-_ez"/></radialGradient><radialGradient id="ikYDQFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.78495 2.38236 0 10.98 14.998)" gradientUnits="userSpaceOnUse"><stop class="ec-d0i0uy"/><stop offset="1" class="w9zvizb5h"/></radialGradient><radialGradient id="ikDej3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.16817 -7.16786 7.78679 -.18269 10.01 14.978)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="ff0iiubua"/><stop offset="1" class="r1j4tvbwh"/></radialGradient><radialGradient id="iqnkDxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 0 0 5.04687 6.835 17.011)" gradientUnits="userSpaceOnUse"><stop class="fixk20q9a"/><stop offset="1" class="sb-r1x_1w"/></radialGradient><radialGradient id="iQfAPAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.68226 2.10732 0 9.43 20.227)" gradientUnits="userSpaceOnUse"><stop class="eyqrs1b7e"/><stop offset="1" class="oixbo9bdy"/></radialGradient><radialGradient id="iBiyrxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.17705 -8.21822 8.20018 -.17667 8.867 20.282)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="qh_uvdsfh"/><stop offset="1" class="fxxbvlbns"/></radialGradient><radialGradient id="isFR1me" cx="0" cy="0" r="1" gradientTransform="matrix(2.38035 0 0 7.9345 5.694 20.031)" gradientUnits="userSpaceOnUse"><stop class="w2iexv6ud"/><stop offset="1" class="a99hecb8l"/></radialGradient><radialGradient id="iztsWvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.6702 2.06121 0 9.398 24.613)" gradientUnits="userSpaceOnUse"><stop class="wzfdw2luh"/><stop offset="1" class="xznyxnbwm"/></radialGradient><radialGradient id="iiFriXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.17323 -8.18127 8.02085 -.16983 8.848 24.669)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="u52m3l7me"/><stop offset="1" class="r4wf66hbq"/></radialGradient><linearGradient id="i6jkFSG" x1="26.78" x2="12.286" y1="8.105" y2="29.819" gradientUnits="userSpaceOnUse"><stop class="z4uhibc5v"/><stop offset="1" class="dm-lxebfq"/></linearGradient><linearGradient id="iYJIFVd" x1="9.788" x2="9.788" y1="21.013" y2="30" gradientUnits="userSpaceOnUse"><stop class="dl4jivb3n"/><stop offset="1" class="v3-1z7o-g"/></linearGradient><linearGradient id="iVW2sib" x1="6.543" x2="8.42" y1="25.506" y2="25.506" gradientUnits="userSpaceOnUse"><stop class="k_lvphbuq"/><stop offset="1" class="g4mbeibfo"/></linearGradient><linearGradient id="iCkVsMr" x1="8.538" x2="10.883" y1="8.718" y2="15.823" gradientUnits="userSpaceOnUse"><stop class="ni1iqybvl"/><stop offset="1" class="hwzpyqv9l"/></linearGradient><linearGradient id="iPTTLad" x1="7.319" x2="10.194" y1="13.105" y2="21.105" gradientUnits="userSpaceOnUse"><stop class="bj0ju8b-y"/><stop offset="1" class="xyp44lb3c"/></linearGradient><linearGradient id="iGQASDb" x1="8.847" x2="8.847" y1="16.486" y2="25.515" gradientUnits="userSpaceOnUse"><stop class="i3cf6wd-b"/><stop offset="1" class="xh51j2vdf"/></linearGradient><filter id="i0RQFPd" width="18.933" height="27.637" x="9.373" y="2.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.698039 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3079"/></filter><filter id="iiyaMmc" width="12.677" height="20.87" x="5.131" y="1.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3079" stdDeviation="1"/></filter><filter id="iMuCVkc" width="12.088" height="5.26" x="12.396" y="15.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3079" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-down-medium-light" /></template>
<style>
.a99hecb8l {
  stop-color: var(--svg-color--bd7b81, #BD7B81);
  stop-opacity: 0;
}

.b4u8r1bra {
  stop-color: var(--svg-color--fdc5a5, #FDC5A5);
}

.bj0ju8b-y {
  stop-color: var(--svg-color--cb9879, #CB9879);
}

.d0pow_blg {
  stop-color: var(--svg-color--bc7761, #BC7761);
}

.dl4jivb3n {
  stop-color: var(--svg-color--c48d7b, #C48D7B);
}

.dm-lxebfq {
  stop-color: var(--svg-color--dca08e, #DCA08E);
}

.dmcp6rbjw {
  width: 5.784px;
  height: 8.988px;
  x: 6.896px;
  y: 21.013px;
  rx: 2.892px;
}

.dtv3nbcrv {
  width: 5.927px;
  height: 10.097px;
  x: 5.904px;
  y: 12.064px;
  rx: 2.91px;
}

.e95_-e25f {
  stop-color: var(--svg-color--d9998e, #D9998E);
}

.ec-d0i0uy {
  stop-color: var(--svg-color--ffd2ab, #FFD2AB);
}

.eyqrs1b7e {
  stop-color: var(--svg-color--ffd1ab, #FFD1AB);
}

.ezcfr6bsl {
  width: 5.629px;
  height: 8.806px;
  x: 7.194px;
  y: 7.81px;
  rx: 2.814px;
}

.ff0iiubua {
  stop-color: var(--svg-color--d8a385, #D8A385);
  stop-opacity: 0;
}

.fixk20q9a {
  stop-color: var(--svg-color--d59877, #D59877);
}

.ft5dv1b6b {
  fill: none;
}

.fxxbvlbns {
  stop-color: var(--svg-color--dba486, #DBA486);
}

.g4mbeibfo {
  stop-color: var(--svg-color--b67186, #B67186);
  stop-opacity: 0;
}

.g8wq_wx5x {
  d: path("M20.5 26.55a3.268 3.268 0 0 1-6.536 0v-3.76q-.001-.482.072-.96a6 6 0 0 0 .047-.35c.036-.369-.008-.85-.258-1.173l.598-.576a9.28 9.28 0 0 1-5.05-8.275c0-.979.15-1.922.43-2.808l.99-6.466h8.051v.002c4.973.107 8.962 3.35 8.962 9.272c0 3.481-1.667 6.284-4.189 7.864l.006.005c-.172.12-.374.24-.591.371l-.002.001c-.715.429-1.59.953-2.05 1.81c-.4.743-.478 1.949-.478 2.508l-.002-.001z");
}

.gx15q4owu {
  stop-color: var(--svg-color--c58c65, #C58C65);
}

.h7dlqpbjb {
  stop-color: var(--svg-color--f9c6aa, #F9C6AA);
  stop-opacity: 0;
}

.hwzpyqv9l {
  stop-color: var(--svg-color--f7c59b, #F7C59B);
}

.i3cf6wd-b {
  stop-color: var(--svg-color--c99479, #C99479);
}

.i8znvkyin {
  stop-color: var(--svg-color--dba188, #DBA188);
}

.iz71evb-c {
  stop-color: var(--svg-color--bd7b6c, #BD7B6C);
}

.j4-11dbix {
  stop-color: var(--svg-color--f9c6aa, #F9C6AA);
}

.jcexmac5l {
  stop-color: var(--svg-color--ba738b, #BA738B);
}

.jx6hehbgz {
  stop-color: var(--svg-color--fdc5a5, #FDC5A5);
  stop-opacity: 0;
}

.k_lvphbuq {
  stop-color: var(--svg-color--b67186, #B67186);
}

.ksm6foavx {
  stop-color: var(--svg-color--bd7b6c, #BD7B6C);
  stop-opacity: 0;
}

.mmj7b4bwh {
  stop-color: var(--svg-color--ba738b, #BA738B);
  stop-opacity: 0;
}

.ni1iqybvl {
  stop-color: var(--svg-color--cb9779, #CB9779);
}

.oixbo9bdy {
  stop-color: var(--svg-color--ffd1ab, #FFD1AB);
  stop-opacity: 0;
}

.p4nrjb94k {
  stop-color: var(--svg-color--bc7761, #BC7761);
  stop-opacity: 0;
}

.ph-1oee-a {
  stop-color: var(--svg-color--ffd2aa, #FFD2AA);
  stop-opacity: 0;
}

.qh_uvdsfh {
  stop-color: var(--svg-color--dba486, #DBA486);
  stop-opacity: 0;
}

.r_tw_ub5a {
  stop-color: var(--svg-color--ffd2aa, #FFD2AA);
}

.r1j4tvbwh {
  stop-color: var(--svg-color--d8a385, #D8A385);
}

.r4wf66hbq {
  stop-color: var(--svg-color--dca488, #DCA488);
}

.rps5mdbwf {
  fill: var(--svg-color--c28769, #C28769);
  d: path("M8.24 5.919c0 .468.122.907.336 1.283c-.855.428-1.445 1.34-1.445 2.394c0 .82.356 1.553.917 2.04a2.64 2.64 0 0 0-.878 1.98c0 1.039.585 1.936 1.431 2.35a2.65 2.65 0 0 0-.618 1.71c0 1.431 1.113 2.591 2.486 2.591h2.753c1.373 0 2.485-1.16 2.485-2.59a2.63 2.63 0 0 0-.89-1.988a2.63 2.63 0 0 0 .99-2.073a2.64 2.64 0 0 0-.897-1.997a2.7 2.7 0 0 0 .898-2.023c0-.728-.281-1.387-.736-1.867c.454-.458.736-1.1.736-1.81c0-1.393-1.083-2.521-2.419-2.521h-2.73c-1.337 0-2.42 1.128-2.42 2.52");
}

.s434mcboj {
  width: 5.797px;
  height: 10.051px;
  x: 5.949px;
  y: 16.486px;
  rx: 2.899px;
}

.sb-r1x_1w {
  stop-color: var(--svg-color--d59877, #D59877);
  stop-opacity: 0;
}

.sxe6fjbjf {
  fill: var(--svg-color--c9867f, #C9867F);
  d: path("M22.984 18.984c-3.643-2.241-7.3-.668-8.247 0l-.84-1.082c5.38-2.562 8.246-.36 9.087 1.081");
}

.u52m3l7me {
  stop-color: var(--svg-color--dca488, #DCA488);
  stop-opacity: 0;
}

.v3-1z7o-g {
  stop-color: var(--svg-color--edb895, #EDB895);
}

.w2iexv6ud {
  stop-color: var(--svg-color--bd7b81, #BD7B81);
}

.w9zvizb5h {
  stop-color: var(--svg-color--ffd2ab, #FFD2AB);
  stop-opacity: 0;
}

.wzfdw2luh {
  stop-color: var(--svg-color--ffd0ac, #FFD0AC);
}

.xg9-s-_ez {
  stop-color: var(--svg-color--c58c65, #C58C65);
  stop-opacity: 0;
}

.xh_x769_k {
  stop-color: var(--svg-color--d9998e, #D9998E);
  stop-opacity: 0;
}

.xh51j2vdf {
  stop-color: var(--svg-color--f7bf96, #F7BF96);
}

.xyp44lb3c {
  stop-color: var(--svg-color--fac79c, #FAC79C);
}

.xznyxnbwm {
  stop-color: var(--svg-color--ffd0ac, #FFD0AC);
  stop-opacity: 0;
}

.z4uhibc5v {
  stop-color: var(--svg-color--f8c499, #F8C499);
}

.zk-r_ccij {
  stop-color: var(--svg-color--dba188, #DBA188);
  stop-opacity: 0;
}

</style>
