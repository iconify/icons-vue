<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#iQ3r34c)"><path fill="url(#i0H1N3b)" class="po22h47tj"/><path fill="url(#ipP6blc)" class="po22h47tj"/><path fill="url(#i0NvKhc)" class="po22h47tj"/><g filter="url(#iONPTzd)"><path stroke="url(#i3VgKfe)" class="rw6f76b7v"/></g><path fill="url(#ipANKwS)" class="r39rrxavz"/><path fill="url(#iduncnb)" class="r39rrxavz"/><path fill="url(#i52BkJl)" class="v-kohzdic"/><path fill="url(#iTIy7TG)" class="v-kohzdic"/><path fill="url(#iQk8MXd)" class="v-kohzdic"/><path fill="url(#iEMnSxb)" class="v-kohzdic"/><path fill="url(#io9EX1c)" class="v-kohzdic"/><path fill="url(#iRjdJUd)" class="v-kohzdic"/><path fill="url(#iNHTqEd)" class="v-kohzdic"/><path fill="url(#ifWkI4H)" class="u8sszmidn"/><path fill="url(#ikI3Lsb)" class="s6s7k9o5p"/><path fill="url(#idIeMLu)" class="s6s7k9o5p"/><path fill="url(#iHKYQgd)" class="s6s7k9o5p"/><path fill="url(#i2hZYvd)" class="s6s7k9o5p"/><path fill="url(#iwQDZgc)" class="m6sz4ibdl"/><path fill="url(#i69ur5d)" class="m6sz4ibdl"/><path fill="url(#i3BGjjg)" class="m6sz4ibdl"/><path fill="url(#i5gdhve)" class="m6sz4ibdl"/><path fill="url(#iuf0qXb)" class="yh0p6k80b"/><path fill="url(#ifQxZBc)" class="yot2q5bvo"/><g filter="url(#iM4v87b)"><path fill="url(#iHBMCKd)" class="r58yyfb3a"/></g><path fill="url(#i7YjxBb)" class="wenkkkbbv"/><path fill="url(#iIa9ske)" class="wenkkkbbv"/><path fill="url(#iwa5h1c)" class="wenkkkbbv"/><g filter="url(#io7M5un)"><path fill="url(#i1hx5xN)" class="ix-q49bry"/></g><g filter="url(#ilfONdY)"><path stroke="url(#i3mu5pc)" class="kshwmnclg"/></g><path fill="url(#ilGEJVw)" class="w34dz5r3e"/><path fill="url(#iRcOlld)" class="w34dz5r3e"/><path fill="url(#iPf9nAc)" class="w34dz5r3e"/><path fill="url(#iFMqgmb)" class="w34dz5r3e"/><g filter="url(#ikpqvKb)"><path stroke="url(#ipIlKOd)" class="jfaswyv6m"/></g><g filter="url(#ihA9Xfb)"><path fill="url(#i1TFbxj)" class="wnq_-w5el"/></g><g filter="url(#iyJEb1c)"><path fill="url(#isLCeWb)" class="pea45mv7l"/></g></g><defs><radialGradient id="ipP6blc" cx="0" cy="0" r="1" gradientTransform="rotate(-111.871 15.15 -3.354)scale(7.17249 8.86849)" gradientUnits="userSpaceOnUse"><stop offset=".948" class="qxgvukb_r"/><stop offset=".985" class="d6f68ab6r"/></radialGradient><radialGradient id="iduncnb" cx="0" cy="0" r="1" gradientTransform="rotate(144.911 7.305 11.687)scale(3.01708 3.50509)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="w0wt2fbfc"/><stop offset="1" class="tzbua2bzz"/></radialGradient><radialGradient id="iTIy7TG" cx="0" cy="0" r="1" gradientTransform="matrix(4.46875 -3.5625 6.06663 7.60991 8.968 24.348)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="lp3q81nwq"/><stop offset=".789" class="sp6f_e7dj"/></radialGradient><radialGradient id="iQk8MXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.90625 2.80938 0 13.937 30.285)" gradientUnits="userSpaceOnUse"><stop class="dve8itqeg"/><stop offset="1" class="auy00-80c"/></radialGradient><radialGradient id="iEMnSxb" cx="0" cy="0" r="1" gradientTransform="matrix(4.625 -7.4375 9.8299 6.11272 5.312 15.816)" gradientUnits="userSpaceOnUse"><stop class="lpo0f90hq"/><stop offset="1" class="tfeon_28v"/></radialGradient><radialGradient id="io9EX1c" cx="0" cy="0" r="1" gradientTransform="translate(12.844 27.066)scale(1.59375)" gradientUnits="userSpaceOnUse"><stop class="tpce5r8no"/><stop offset="1" class="vjihlqiwj"/></radialGradient><radialGradient id="iRjdJUd" cx="0" cy="0" r="1" gradientTransform="matrix(.20313 1.01563 -.49916 .09983 23.828 11.207)" gradientUnits="userSpaceOnUse"><stop class="zz39r5b3o"/><stop offset="1" class="wvn8vtban"/></radialGradient><radialGradient id="iNHTqEd" cx="0" cy="0" r="1" gradientTransform="rotate(122.433 13.25 8.909)scale(7.10881 15.8441)" gradientUnits="userSpaceOnUse"><stop class="zz39r5b3o"/><stop offset="1" class="wvn8vtban"/></radialGradient><radialGradient id="i2hZYvd" cx="0" cy="0" r="1" gradientTransform="matrix(6.25 -3.375 2.31402 4.28523 19.062 19.32)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="ct_-h8nim"/><stop offset="1" class="owqi18l4x"/></radialGradient><radialGradient id="iwQDZgc" cx="0" cy="0" r="1" gradientTransform="rotate(53.326 -9.663 31.347)scale(3.66252 5.55394)" gradientUnits="userSpaceOnUse"><stop offset=".454" class="omgbpenkr"/><stop offset="1" class="vn22o53em"/></radialGradient><radialGradient id="i69ur5d" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 -.39063 .83742 4.68956 21.344 13.515)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="hhrbmjdcy"/><stop offset=".781" class="msgdqmbxl"/></radialGradient><radialGradient id="i3BGjjg" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 15.875 -17.08432 2.28688 17.75 11.812)" gradientUnits="userSpaceOnUse"><stop offset=".846" class="auy00-80c"/><stop offset="1" class="dve8itqeg"/></radialGradient><radialGradient id="i5gdhve" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.54688 1.76013 2.56474 17.68 26.586)" gradientUnits="userSpaceOnUse"><stop class="i0_c9jbef"/><stop offset="1" class="k0lznpblw"/></radialGradient><radialGradient id="i7YjxBb" cx="0" cy="0" r="1" gradientTransform="rotate(125.838 2.673 8.104)scale(1.38773 1.23721)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iIa9ske" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 .48437 -.42613 -.46737 10.884 10.754)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="ilGEJVw" cx="0" cy="0" r="1" gradientTransform="matrix(-.35156 -5.4375 2.93313 -.18964 23.476 14.254)" gradientUnits="userSpaceOnUse"><stop class="l1m7hy97j"/><stop offset="1" class="jhb_tsyzt"/></radialGradient><radialGradient id="iRcOlld" cx="0" cy="0" r="1" gradientTransform="rotate(151.719 10.006 8.73)scale(3.03403 5.44154)" gradientUnits="userSpaceOnUse"><stop offset=".751" class="rxyh94_nu"/><stop offset="1" class="tsk4adpya"/></radialGradient><radialGradient id="iPf9nAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.23438 -3.07998 0 22.828 9.597)" gradientUnits="userSpaceOnUse"><stop offset=".894" class="rxyh94_nu"/><stop offset="1" class="tsk4adpya"/></radialGradient><radialGradient id="iFMqgmb" cx="0" cy="0" r="1" gradientTransform="rotate(-55.265 21.408 -12.92)scale(1.42599 .5312)" gradientUnits="userSpaceOnUse"><stop class="q_t8gxb3t"/><stop offset="1" class="w1s1_e3do"/></radialGradient><linearGradient id="i0H1N3b" x1="23.125" x2="26" y1="7.941" y2="2" gradientUnits="userSpaceOnUse"><stop class="oehw_srdc"/><stop offset="1" class="rhawsfb0z"/></linearGradient><linearGradient id="i0NvKhc" x1="26.187" x2="23.5" y1="7.191" y2="7.191" gradientUnits="userSpaceOnUse"><stop class="uo9xqqnno"/><stop offset="1" class="uyp-k0bze"/></linearGradient><linearGradient id="i3VgKfe" x1="25.461" x2="25.461" y1="2.965" y2="8.121" gradientUnits="userSpaceOnUse"><stop class="xrrl-ubkg"/><stop offset="1" class="dxe7ozppf"/></linearGradient><linearGradient id="ipANKwS" x1="18.496" x2="18.496" y1="16.16" y2="19.097" gradientUnits="userSpaceOnUse"><stop class="lje_2vbxt"/><stop offset="1" class="q9uogdbtp"/></linearGradient><linearGradient id="i52BkJl" x1="8.947" x2="29.881" y1="10.998" y2="25.894" gradientUnits="userSpaceOnUse"><stop class="hu5mk_s-h"/><stop offset="1" class="ydf10x06l"/></linearGradient><linearGradient id="ifWkI4H" x1="16.227" x2="16.227" y1="12.999" y2="23.479" gradientUnits="userSpaceOnUse"><stop class="x7hzf_bmt"/><stop offset="1" class="ctwhdocdd"/></linearGradient><linearGradient id="ikI3Lsb" x1="17.823" x2="17.823" y1="19.445" y2="11.065" gradientUnits="userSpaceOnUse"><stop offset=".165" class="ct_-h8nim"/><stop offset="1" class="owqi18l4x"/></linearGradient><linearGradient id="idIeMLu" x1="27.437" x2="24.906" y1="17.789" y2="14.101" gradientUnits="userSpaceOnUse"><stop class="l2_7b7baf"/><stop offset="1" class="dcwg_p5bw"/></linearGradient><linearGradient id="iHKYQgd" x1="27.64" x2="24" y1="14.461" y2="16.258" gradientUnits="userSpaceOnUse"><stop class="gjmns-b8w"/><stop offset="1" class="dcwg_p5bw"/></linearGradient><linearGradient id="iuf0qXb" x1="15.495" x2="15.495" y1="9.685" y2="12.916" gradientUnits="userSpaceOnUse"><stop class="pwn5iheqp"/><stop offset="1" class="b7cyikb-t"/></linearGradient><linearGradient id="ifQxZBc" x1="17.495" x2="17.495" y1="9.685" y2="12.916" gradientUnits="userSpaceOnUse"><stop class="pwn5iheqp"/><stop offset="1" class="b7cyikb-t"/></linearGradient><linearGradient id="iHBMCKd" x1="9.802" x2="10.135" y1="10.789" y2="11.881" gradientUnits="userSpaceOnUse"><stop offset=".006" class="x_1tpjbqt"/><stop offset="1" class="yqf_2yism"/></linearGradient><linearGradient id="iwa5h1c" x1="10.313" x2="9.626" y1="10.218" y2="9.781" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="i1hx5xN" x1="14.125" x2="7.812" y1="20.222" y2="24.254" gradientUnits="userSpaceOnUse"><stop class="ol_ezvbit"/><stop offset="1" class="xnqfq4bbf"/></linearGradient><linearGradient id="i3mu5pc" x1="19.484" x2="19.484" y1="20.203" y2="17.875" gradientUnits="userSpaceOnUse"><stop class="xrrl-ubkg"/><stop offset="1" class="dxe7ozppf"/></linearGradient><linearGradient id="ipIlKOd" x1="23.312" x2="23.312" y1="14.238" y2="11.269" gradientUnits="userSpaceOnUse"><stop class="emb4en2je"/><stop offset="1" class="f_kr4dbyl"/></linearGradient><linearGradient id="i1TFbxj" x1="26.916" x2="33.865" y1="8.754" y2="18.795" gradientUnits="userSpaceOnUse"><stop class="zz39r5b3o"/><stop offset="1" class="wvn8vtban"/></linearGradient><linearGradient id="isLCeWb" x1="25.156" x2="23.907" y1="10.37" y2="6.996" gradientUnits="userSpaceOnUse"><stop class="zz39r5b3o"/><stop offset="1" class="wvn8vtban"/></linearGradient><filter id="iONPTzd" width="1.094" height="5.156" x="24.933" y="2.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6084" stdDeviation=".1"/></filter><filter id="iM4v87b" width="2.941" height="2.941" x="8.75" y="9.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6084" stdDeviation=".25"/></filter><filter id="io7M5un" width="7.683" height="6.5" x="8.937" y="18.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6084" stdDeviation=".5"/></filter><filter id="ilfONdY" width=".747" height="2.998" x="19.271" y="16.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6084" stdDeviation=".1"/></filter><filter id="ikpqvKb" width=".763" height="3.522" x="22.747" y="11.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6084" stdDeviation=".1"/></filter><filter id="ihA9Xfb" width="6.832" height="11.188" x="23.5" y="7.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6084" stdDeviation=".5"/></filter><filter id="iyJEb1c" width="9.563" height="3.829" x="18.156" y="8.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6084" stdDeviation=".5"/></filter><clipPath id="iQ3r34c"><path class="e8ww0933x"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:shark" /></template>
<style>
.auy00-80c {
  stop-color: var(--svg-color--8d6fa8, #8D6FA8);
  stop-opacity: 0;
}

.b7cyikb-t {
  stop-color: var(--svg-color--867f8f, #867F8F);
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.ct_-h8nim {
  stop-color: var(--svg-color--947cab, #947CAB);
}

.ctwhdocdd {
  stop-color: var(--svg-color--e1d9eb, #E1D9EB);
  stop-opacity: 0;
}

.d6f68ab6r {
  stop-color: var(--svg-color--8c8b8d, #8C8B8D);
}

.dcwg_p5bw {
  stop-color: var(--svg-color--c8c3cf, #C8C3CF);
  stop-opacity: 0;
}

.dve8itqeg {
  stop-color: var(--svg-color--8d6fa8, #8D6FA8);
}

.dxe7ozppf {
  stop-color: var(--svg-color--b8b7ba, #B8B7BA);
  stop-opacity: 0;
}

.e8ww0933x {
  fill: var(--svg-color--fff, #fff);
  d: path("M2 2h28v28H2z");
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.emb4en2je {
  stop-color: var(--svg-color--cbc8ce, #CBC8CE);
}

.f_kr4dbyl {
  stop-color: var(--svg-color--cbc8ce, #CBC8CE);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gjmns-b8w {
  stop-color: var(--svg-color--d7d0e0, #D7D0E0);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hhrbmjdcy {
  stop-color: var(--svg-color--8b779e, #8B779E);
}

.hu5mk_s-h {
  stop-color: var(--svg-color--9e9da0, #9E9DA0);
}

.i0_c9jbef {
  stop-color: var(--svg-color--adaaaf, #ADAAAF);
}

.ix-q49bry {
  d: path("M13.75 21.144c-1.043-1.39-2.844-1.349-3.813-1.39c1.725.3 2.235 1.093 2.875 1.843l1.853 2.442a.54.54 0 0 0 .433.215a.507.507 0 0 0 .412-.822c-.5-.648-1.184-1.52-1.76-2.288");
}

.jfaswyv6m {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M23.234 11.27v2.609c0 .097.031.412-.281.437");
}

.jhb_tsyzt {
  stop-color: var(--svg-color--b5b2b9, #B5B2B9);
  stop-opacity: 0;
}

.k0lznpblw {
  stop-color: var(--svg-color--adaaaf, #ADAAAF);
  stop-opacity: 0;
}

.kshwmnclg {
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("M19.781 17.156v2.125c0 .11-.06.35-.297.438");
}

.l1m7hy97j {
  stop-color: var(--svg-color--b5b2b9, #B5B2B9);
}

.l2_7b7baf {
  stop-color: var(--svg-color--c8c3cf, #C8C3CF);
}

.lje_2vbxt {
  stop-color: var(--svg-color--5c5069, #5C5069);
}

.lp3q81nwq {
  stop-color: var(--svg-color--8b7b9b, #8B7B9B);
}

.lpo0f90hq {
  stop-color: var(--svg-color--857c90, #857C90);
}

.m6sz4ibdl {
  d: path("M27.636 22.434c.628-1.494.842-3.21.718-5.049c-.203-3.006-2.14-5.39-4.547-6.304c-.21-.05-.32.036-.32.226v2.579c0 1.187-1.086.859-1.54.617c-1.095-.708-1.671-1.925-1.671-3.237a.27.27 0 0 0-.27-.271h-7.123c-2.71 0-5.34.974-7.4 2.752l-1.417 1.217C5.59 16.231 7.556 17 9.51 17h12.21c1.23 0 2.27.97 2.3 2.2c.01.64-.24 1.23-.66 1.64a11.5 11.5 0 0 1-4.52 2.65v.01c-.255.076-2.583.673-2.84.734l2.073 2.86A.8.8 0 0 1 18.45 27c.13 0 .26 0 .39-.01a11.56 11.56 0 0 0 8.796-4.556");
}

.msgdqmbxl {
  stop-color: var(--svg-color--8b779e, #8B779E);
  stop-opacity: 0;
}

.oehw_srdc {
  stop-color: var(--svg-color--959397, #959397);
}

.ol_ezvbit {
  stop-color: var(--svg-color--cecad3, #CECAD3);
}

.omgbpenkr {
  stop-color: var(--svg-color--89868d, #89868D);
}

.owqi18l4x {
  stop-color: var(--svg-color--947cab, #947CAB);
  stop-opacity: 0;
}

.pea45mv7l {
  d: path("M25.906 11.285c-1.65-1.3-5.187-1.48-6.75-1.406c3.8-1.125 6.625.26 7.563 1.093z");
}

.po22h47tj {
  d: path("M26 3.004c0-.59-.5-1.05-1.09-1c-4.43.41-8.9 3.24-8.9 6.7c0 3.74 5.23 6.78 9.99 6.78z");
}

.pwn5iheqp {
  stop-color: var(--svg-color--908d94, #908D94);
}

.q_t8gxb3t {
  stop-color: var(--svg-color--959199, #959199);
}

.q9uogdbtp {
  stop-color: var(--svg-color--827b8a, #827B8A);
}

.qxgvukb_r {
  stop-color: var(--svg-color--8c8b8d, #8C8B8D);
  stop-opacity: 0;
}

.r39rrxavz {
  d: path("M17 14.674v2.13c0 1.3.73 2.49 1.89 3.08l.09.05a.7.7 0 0 0 1.02-.63v-4.62h-3z");
}

.r58yyfb3a {
  d: path("M10.22 12.144a.97.97 0 1 0 0-1.942a.97.97 0 0 0 0 1.942");
}

.rhawsfb0z {
  stop-color: var(--svg-color--96939b, #96939B);
}

.rw6f76b7v {
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("M25.133 2.261c.207 0 .656.192.656.81v3.91");
}

.rxyh94_nu {
  stop-color: var(--svg-color--8a8193, #8A8193);
  stop-opacity: 0;
}

.s6s7k9o5p {
  d: path("m28.303 16.952l-4.305 2.996l-.066-.006c.06-.213.091-.44.088-.672c-.03-1.23-1.07-2.2-2.3-2.2H9.51c-1.953 0-3.92-.769-5.444-2.035l1.417-1.218a11.33 11.33 0 0 1 7.4-2.752h7.123c.15 0 .27.12.27.271c0 1.312.569 2.468 1.665 3.176c.453.242 1.546.527 1.546-.575v-2.56c0-.19.11-.276.32-.226c2.27.863 4.123 3.033 4.496 5.8");
}

.sp6f_e7dj {
  stop-color: var(--svg-color--8b7b9b, #8B7B9B);
  stop-opacity: 0;
}

.tfeon_28v {
  stop-color: var(--svg-color--857c90, #857C90);
  stop-opacity: 0;
}

.tpce5r8no {
  stop-color: var(--svg-color--948e9a, #948E9A);
}

.tsk4adpya {
  stop-color: var(--svg-color--8a8193, #8A8193);
}

.tzbua2bzz {
  stop-color: var(--svg-color--6f617d, #6F617D);
}

.u8sszmidn {
  d: path("M27.636 22.5c.628-1.493.842-3.21.718-5.048c-.203-3.007-2.14-5.39-4.547-6.305c-.21-.05-.32.036-.32.227v2.578c0 1.099-1.089.802-1.542.56c-1.094-.7-1.669-1.868-1.669-3.18a.27.27 0 0 0-.27-.27h-7.123c-2.71 0-5.34.973-7.4 2.751l-1.417 1.218c1.524 1.266 3.49 2.035 5.444 2.035h12.21c1.23 0 2.27.97 2.3 2.2c.01.64-.24 1.23-.66 1.64a11.5 11.5 0 0 1-4.52 2.65v.01q-.382.115-.767.207v3.387a.8.8 0 0 1 .377-.094c.13 0 .26 0 .39-.01a11.56 11.56 0 0 0 8.796-4.556");
}

.uo9xqqnno {
  stop-color: var(--svg-color--959297, #959297);
}

.uyp-k0bze {
  stop-color: var(--svg-color--959297, #959297);
  stop-opacity: 0;
}

.v-kohzdic {
  d: path("M18.42 3.906h-1.61c-5.54 0-11.12 2.61-14.45 7.04c-.44.58-.48 1.38-.1 2c1.48 2.46 4.38 4.12 7.25 4.12h12.21c1.23 0 2.27.97 2.3 2.2c.01.64-.24 1.23-.66 1.64a11.5 11.5 0 0 1-4.52 2.65v.01c-.47.14-.94.26-1.42.34a.8.8 0 0 1-.75-.28l-1.76-2.2a6.28 6.28 0 0 0-4.89-2.36H8.77c-.31 0-.49.35-.3.6l5.23 6.97c.19.25.2.6.02.87l-1.32 1.98c-.15.25.03.58.32.58h1.62c1.04 0 2.02-.52 2.6-1.39l.85-1.26a.79.79 0 0 1 .66-.35c.13 0 .26 0 .39-.01c6.2-.22 11.16-5.31 11.16-11.57c0-6.4-5.18-11.58-11.58-11.58");
}

.vjihlqiwj {
  stop-color: var(--svg-color--948e9a, #948E9A);
  stop-opacity: 0;
}

.vn22o53em {
  stop-color: var(--svg-color--89868d, #89868D);
  stop-opacity: 0;
}

.w0wt2fbfc {
  stop-color: var(--svg-color--6f617d, #6F617D);
  stop-opacity: 0;
}

.w1s1_e3do {
  stop-color: var(--svg-color--959199, #959199);
  stop-opacity: 0;
}

.w34dz5r3e {
  d: path("M23.476 8.816h-3.195v2.668c.06 1.23.63 2.353 1.667 3.023c.427.228 1.416.532 1.528-.427z");
}

.wenkkkbbv {
  d: path("M10.51 12.004a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.wnq_-w5el {
  d: path("M24.5 10.41c.52.25 1.572.394 2.172.094c.707-.354.789-1.485.246-2.19c1.218 1.434 3.205 4.27 2.082 9.065c-.266-2.297-1.175-5.32-4.5-6.97");
}

.wvn8vtban {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
  stop-opacity: 0;
}

.x_1tpjbqt {
  stop-color: var(--svg-color--706977, #706977);
}

.x7hzf_bmt {
  stop-color: var(--svg-color--e1d9eb, #E1D9EB);
}

.xnqfq4bbf {
  stop-color: var(--svg-color--cecad3, #CECAD3);
  stop-opacity: 0;
}

.xrrl-ubkg {
  stop-color: var(--svg-color--b8b7ba, #B8B7BA);
}

.ydf10x06l {
  stop-color: var(--svg-color--b5b2b8, #B5B2B8);
}

.yh0p6k80b {
  d: path("M15.5 12.504c-.28 0-.5-.22-.5-.5v-2.01c0-.28.22-.5.5-.5s.5.23.5.5v2.01c0 .28-.23.5-.5.5");
}

.yot2q5bvo {
  d: path("M17.5 12.504c-.28 0-.5-.22-.5-.5v-2.01c0-.28.22-.5.5-.5s.5.22.5.5v2.01c0 .28-.23.5-.5.5");
}

.yqf_2yism {
  stop-color: var(--svg-color--a594af, #A594AF);
}

.zz39r5b3o {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
}

</style>
