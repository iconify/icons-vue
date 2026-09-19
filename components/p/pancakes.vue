<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iKPgDfc)" class="e4pwkac6u"/><g filter="url(#iZ7EOic)"><path fill="url(#iEvC1eh)" class="jl6ok7z_k"/></g><g filter="url(#iKT63qe)"><path fill="url(#iQbNQdb)" class="c2ctzybhd"/></g><path fill="url(#iwgUJ7H)" class="mbd0apntt"/><path fill="url(#iymX3ne)" class="deiewfb0p"/><path fill="url(#i7JcePd)" class="deiewfb0p"/><path fill="url(#iPkK7gd)" class="deiewfb0p"/><path fill="url(#ib03uAh)" class="e972tsbmt"/><path fill="url(#ig6TdMe)" class="iou-y113k"/><g filter="url(#is3eF9d)"><path fill="url(#iYIUIUd)" class="o0kr9_bai"/><path fill="url(#iiO66mb)" class="o0kr9_bai"/><path fill="url(#ihoFVjc)" class="o0kr9_bai"/></g><path fill="url(#i8vXWld)" class="exz-6mago"/><path class="ts-p6y9jk"/><path fill="url(#iL7Q4Gb)" class="exz-6mago"/><g filter="url(#ivwBZLd)"><path fill="url(#ip8Nvac)" class="l-1k2hbfo"/><path fill="url(#iv2V6ve)" class="l-1k2hbfo"/><path fill="url(#iwjrwUd)" class="l-1k2hbfo"/><path fill="url(#itiP3sd)" class="l-1k2hbfo"/><path fill="url(#ij7GZ8c)" class="l-1k2hbfo"/><path fill="url(#ihdX8Nc)" class="l-1k2hbfo"/><path fill="url(#iyeqdcd)" class="l-1k2hbfo"/></g><g filter="url(#iVuA23S)"><path class="h31mzvbec"/></g><path fill="url(#i083xbc)" class="xsic05ojx"/><path fill="url(#ierUGbC)" class="xsic05ojx"/><path fill="url(#iZ4pUCc)" class="gm-qy5baz"/><circle fill="url(#iGFxlyc)" class="vij8z2ktb"/><circle fill="url(#itvSPDy)" class="osasysb0o"/><g filter="url(#ikKLHRg)"><path fill="url(#iv6Dqvb)" class="m58z3lbwq"/></g><g filter="url(#iDuO0ac)"><path fill="url(#ic3QI8F)" class="mw_ul3bvd"/></g><g filter="url(#iY0OHQc)"><path stroke="url(#ifX7fGe)" class="utcm51rhh"/></g><g filter="url(#ij96kvc)"><path stroke="url(#i6jn0Fd)" class="gl9ydnb2i"/></g><g filter="url(#iqOvaGc)"><path stroke="url(#i01j7Ob)" class="vi95y82wx"/></g><defs><radialGradient id="i7JcePd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.34759 -13.25 0 16 15.777)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="koc2hxbjk"/><stop offset="1" class="mvks-fbxe"/></radialGradient><radialGradient id="iPkK7gd" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 0 0 2.85976 12.25 19.5)" gradientUnits="userSpaceOnUse"><stop class="wi4e9nc2z"/><stop offset="1" class="mozx20bcw"/></radialGradient><radialGradient id="iiO66mb" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 4.3125 -3.8858 4.05475 9.875 9.813)" gradientUnits="userSpaceOnUse"><stop class="ewlyvj3rs"/><stop offset=".768" class="tidere9ei"/></radialGradient><radialGradient id="ihoFVjc" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 0 0 4.25084 12.813 15.438)" gradientUnits="userSpaceOnUse"><stop class="ctbdvpbtw"/><stop offset="1" class="pkk5a946u"/></radialGradient><radialGradient id="i8vXWld" cx="0" cy="0" r="1" gradientTransform="matrix(-12.43744 5.12507 -4.74283 -11.50981 20.5 10.063)" gradientUnits="userSpaceOnUse"><stop offset=".025" class="tvs04vy4u"/><stop offset="1" class="oz5zs-viq"/></radialGradient><radialGradient id="ip8Nvac" cx="0" cy="0" r="1" gradientTransform="rotate(158.112 9.241 6.95)scale(13.1267 11.9293)" gradientUnits="userSpaceOnUse"><stop offset=".025" class="tvs04vy4u"/><stop offset="1" class="oz5zs-viq"/></radialGradient><radialGradient id="iv2V6ve" cx="0" cy="0" r="1" gradientTransform="matrix(3.45827 1.87983 -1.00439 1.84774 13.644 9)" gradientUnits="userSpaceOnUse"><stop class="lij6egb7m"/><stop offset="1" class="dv20-r3pr"/></radialGradient><radialGradient id="iwjrwUd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62501 4.18749 -4.06664 -3.5204 10.75 6.75)" gradientUnits="userSpaceOnUse"><stop class="xee8eqlnj"/><stop offset="1" class="sxyb3q7hj"/></radialGradient><radialGradient id="itiP3sd" cx="0" cy="0" r="1" gradientTransform="rotate(-165.256 10.472 7.637)scale(2.45586 1.62495)" gradientUnits="userSpaceOnUse"><stop class="chhjhwb9a"/><stop offset="1" class="n3guf8b2h"/></radialGradient><radialGradient id="ij7GZ8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.375 1.27037 0 13.156 19.875)" gradientUnits="userSpaceOnUse"><stop class="b1-p9wbnd"/><stop offset="1" class="s1xtlu6ta"/></radialGradient><radialGradient id="ihdX8Nc" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 1.09374 -.6735 -.11546 13.906 16.063)" gradientUnits="userSpaceOnUse"><stop class="zav3cacuj"/><stop offset="1" class="vplm8xbfa"/></radialGradient><radialGradient id="iyeqdcd" cx="0" cy="0" r="1" gradientTransform="matrix(-.28125 .9375 -.65123 -.19537 18.89 15.734)" gradientUnits="userSpaceOnUse"><stop class="ais0q3y0e"/><stop offset="1" class="dobmirqzh"/></radialGradient><radialGradient id="ierUGbC" cx="0" cy="0" r="1" gradientTransform="matrix(0 3 -3.44251 0 16.005 10.938)" gradientUnits="userSpaceOnUse"><stop class="jwmmjib6e"/><stop offset="1" class="ahabqhbwx"/></radialGradient><radialGradient id="iGFxlyc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.98437 0 0 -2.82658 23.577 26.922)" gradientUnits="userSpaceOnUse"><stop class="c5aqjcbql"/><stop offset=".705" class="a06ad_beq"/></radialGradient><radialGradient id="itvSPDy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07227 0 0 -1.01557 24.91 25.857)" gradientUnits="userSpaceOnUse"><stop class="c5aqjcbql"/><stop offset=".705" class="a06ad_beq"/></radialGradient><radialGradient id="iv6Dqvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.80469 -4.14003 0 20.804 13.07)" gradientUnits="userSpaceOnUse"><stop class="cgenosbsk"/><stop offset="1" class="d3g2_ih4p"/></radialGradient><radialGradient id="ifX7fGe" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -2.40626 1.27457 1.34077 25.72 14.5)" gradientUnits="userSpaceOnUse"><stop class="dpvzlabrs"/><stop offset=".449" class="t1zan_bns"/><stop offset=".988" class="amblk8f2s"/></radialGradient><radialGradient id="i6jn0Fd" cx="0" cy="0" r="1" gradientTransform="rotate(-51.506 40.303 -15.015)scale(5.62974 2.98202)" gradientUnits="userSpaceOnUse"><stop class="uif3opiqw"/><stop offset=".449" class="qkpl4_bws"/><stop offset=".988" class="kyc7b125y"/></radialGradient><radialGradient id="i01j7Ob" cx="0" cy="0" r="1" gradientTransform="matrix(2.8872 -1.6592 .824 1.43385 18.188 7.313)" gradientUnits="userSpaceOnUse"><stop class="mnl9e5y6w"/><stop offset=".449" class="cfvy88b-m"/><stop offset=".988" class="u_v-b85_i"/></radialGradient><linearGradient id="iKPgDfc" x1="2" x2="30" y1="21.125" y2="21.125" gradientUnits="userSpaceOnUse"><stop class="nug7pf77x"/><stop offset=".1" class="pw87bab_j"/><stop offset=".232" class="m2hne6bit"/><stop offset=".804" class="cadf34b2c"/><stop offset="1" class="d1_kgbbgw"/></linearGradient><linearGradient id="iEvC1eh" x1="2.813" x2="30.125" y1="20.125" y2="20.125" gradientUnits="userSpaceOnUse"><stop class="jdzc-kb6v"/><stop offset=".158" class="o_akhtf2c"/><stop offset=".485" class="l34omxbdj"/><stop offset=".822" class="bkpaywjlp"/><stop offset="1" class="uxkul1bho"/></linearGradient><linearGradient id="iQbNQdb" x1="16" x2="16" y1="14.823" y2="26.563" gradientUnits="userSpaceOnUse"><stop offset=".886" class="z4nat-bal"/><stop offset="1" class="q4yqn79gq"/></linearGradient><linearGradient id="iwgUJ7H" x1="4.011" x2="27.989" y1="19.188" y2="19.188" gradientUnits="userSpaceOnUse"><stop class="dtafgccff"/><stop offset=".156" class="zjosdbb5k"/><stop offset=".325" class="vbq8obbyj"/><stop offset=".758" class="gjdz49xwo"/><stop offset="1" class="i-op0wquf"/></linearGradient><linearGradient id="iymX3ne" x1="4.563" x2="27.989" y1="17.875" y2="17.875" gradientUnits="userSpaceOnUse"><stop class="j-ermkbgy"/><stop offset=".147" class="yahwg-zix"/><stop offset=".339" class="zr7zsdj0g"/><stop offset=".59" class="a95blbc2n"/><stop offset=".819" class="e5sb_s87h"/><stop offset="1" class="bsazttibe"/></linearGradient><linearGradient id="ib03uAh" x1="4.563" x2="27.989" y1="13.625" y2="13.625" gradientUnits="userSpaceOnUse"><stop class="kjdwtlbxl"/><stop offset=".133" class="qierc0bug"/><stop offset=".283" class="tp_qxirzs"/><stop offset=".491" class="fqt3a9nzi"/><stop offset=".592" class="szwy9ob0j"/><stop offset=".696" class="u_19pbcky"/><stop offset=".816" class="ioos1yi_w"/><stop offset="1" class="f2n26zstl"/></linearGradient><linearGradient id="ig6TdMe" x1="4.625" x2="27.989" y1="8.813" y2="8.813" gradientUnits="userSpaceOnUse"><stop class="ebcvavbfy"/><stop offset=".144" class="e4kgj988q"/><stop offset=".72" class="ucqupq89y"/><stop offset="1" class="cy8ollznp"/></linearGradient><linearGradient id="iYIUIUd" x1="7.222" x2="26.563" y1="7.965" y2="7.965" gradientUnits="userSpaceOnUse"><stop offset=".063" class="ir_nb604z"/><stop offset="1" class="so7on2z3v"/></linearGradient><linearGradient id="iL7Q4Gb" x1="9.625" x2="23.148" y1="11.875" y2="11.875" gradientUnits="userSpaceOnUse"><stop class="meg8j5w4o"/><stop offset="1" class="u93rdlpux"/></linearGradient><linearGradient id="i083xbc" x1="11.438" x2="20.717" y1="7.488" y2="7.488" gradientUnits="userSpaceOnUse"><stop class="yqhhz1byj"/><stop offset="1" class="u1dhqdhom"/></linearGradient><linearGradient id="iZ4pUCc" x1="14.398" x2="17.563" y1="2.602" y2="7.625" gradientUnits="userSpaceOnUse"><stop offset=".008" class="lnrow6zmv"/><stop offset=".085" class="ozjkh4bzx"/><stop offset=".934" class="jswq7mbdz"/></linearGradient><linearGradient id="ic3QI8F" x1="14.031" x2="17.75" y1="13.503" y2="13.503" gradientUnits="userSpaceOnUse"><stop class="e1lufbcgo"/><stop offset=".462" class="k8h_m2ido"/><stop offset=".618" class="h5vt7abxq"/></linearGradient><filter id="iZ7EOic" width="28.531" height="17.375" x="1.75" y="11.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29513" stdDeviation=".25"/></filter><filter id="iKT63qe" width="24.979" height="12.034" x="3.511" y="14.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29513" stdDeviation=".25"/></filter><filter id="is3eF9d" width="14.656" height="13.665" x="3.969" y="3.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29513" stdDeviation=".125"/></filter><filter id="ivwBZLd" width="14.641" height="16.34" x="8.703" y="5.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29513" stdDeviation=".125"/></filter><filter id="iVuA23S" width="10.053" height="4.516" x="10.979" y="6.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29513" stdDeviation=".25"/></filter><filter id="ikKLHRg" width="4.92" height="8.391" x="18.344" y="8.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29513" stdDeviation=".25"/></filter><filter id="iDuO0ac" width="5.454" height="6.547" x="13.078" y="11.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29513" stdDeviation=".375"/></filter><filter id="iY0OHQc" width="7.191" height="5.784" x="20.959" y="11.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29513" stdDeviation=".125"/></filter><filter id="ij96kvc" width="6.643" height="7.613" x="23.382" y="21.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29513" stdDeviation=".125"/></filter><filter id="iqOvaGc" width="6.238" height="3.871" x="14.858" y="4.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29513" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pancakes" /></template>
<style>
.a06ad_beq {
  stop-color: var(--svg-color--8e512e, #8E512E);
}

.a95blbc2n {
  stop-color: var(--svg-color--d68c56, #D68C56);
}

.ahabqhbwx {
  stop-color: var(--svg-color--d9a32b, #D9A32B);
  stop-opacity: 0;
}

.ais0q3y0e {
  stop-color: var(--svg-color--a67968, #A67968);
}

.amblk8f2s {
  stop-color: var(--svg-color--f0bc8f, #F0BC8F);
  stop-opacity: 0;
}

.b1-p9wbnd {
  stop-color: var(--svg-color--884b4f, #884B4F);
}

.bkpaywjlp {
  stop-color: var(--svg-color--dfd1d6, #DFD1D6);
}

.bsazttibe {
  stop-color: var(--svg-color--eaad74, #EAAD74);
}

.c2ctzybhd {
  d: path("M21.417 14.823H10.593l-6.582 1.89v2.562a6.58 6.58 0 0 0 6.582 6.582h10.814a6.58 6.58 0 0 0 6.582-6.582v-2.561z");
}

.c5aqjcbql {
  stop-color: var(--svg-color--a06740, #A06740);
}

.cadf34b2c {
  stop-color: var(--svg-color--c9a6e7, #C9A6E7);
}

.cfvy88b-m {
  stop-color: var(--svg-color--f2d359, #F2D359);
}

.cgenosbsk {
  stop-color: var(--svg-color--ad7c68, #AD7C68);
}

.chhjhwb9a {
  stop-color: var(--svg-color--8a4654, #8A4654);
}

.ctbdvpbtw {
  stop-color: var(--svg-color--af774e, #AF774E);
}

.cy8ollznp {
  stop-color: var(--svg-color--e6b27d, #E6B27D);
}

.d1_kgbbgw {
  stop-color: var(--svg-color--d8d0df, #D8D0DF);
}

.d3g2_ih4p {
  stop-color: var(--svg-color--ac7b65, #AC7B65);
  stop-opacity: 0;
}

.deiewfb0p {
  d: path("M21.417 9.195H10.593a6.58 6.58 0 0 0-6.582 6.582a6.58 6.58 0 0 0 6.582 6.583h10.814a6.58 6.58 0 0 0 6.582-6.583a6.566 6.566 0 0 0-6.572-6.582");
}

.dobmirqzh {
  stop-color: var(--svg-color--a87b68, #A87B68);
  stop-opacity: 0;
}

.dpvzlabrs {
  stop-color: var(--svg-color--efb992, #EFB992);
}

.dtafgccff {
  stop-color: var(--svg-color--b88c43, #B88C43);
}

.dv20-r3pr {
  stop-color: var(--svg-color--733e21, #733E21);
  stop-opacity: 0;
}

.e1lufbcgo {
  stop-color: var(--svg-color--a27764, #A27764);
}

.e4kgj988q {
  stop-color: var(--svg-color--d6a87a, #D6A87A);
}

.e4pwkac6u {
  d: path("M21.357 12.066H10.653C5.871 12.066 2 15.947 2 20.729a8.65 8.65 0 0 0 8.653 8.653h10.694A8.65 8.65 0 0 0 30 20.73a8.643 8.643 0 0 0-8.643-8.663");
}

.e5sb_s87h {
  stop-color: var(--svg-color--e3985d, #E3985D);
}

.e972tsbmt {
  d: path("M21.417 8.515H10.593l-6.582 1.9v2.562a6.58 6.58 0 0 0 6.582 6.582h10.814a6.58 6.58 0 0 0 6.582-6.583v-2.56z");
}

.ebcvavbfy {
  stop-color: var(--svg-color--cca275, #CCA275);
}

.ewlyvj3rs {
  stop-color: var(--svg-color--b38258, #B38258);
}

.exz-6mago {
  d: path("M19.436 6.204h-6.872a3.69 3.69 0 0 0-3.692 3.691c0 1.67 1.11 3.091 2.641 3.542c.46.14.77.57.77 1.05v5.812c0 .71.55 1.31 1.261 1.33c.72.01 1.31-.57 1.31-1.28v-5.672c0-.6.48-1.08 1.081-1.08c.6 0 1.08.48 1.08 1.08v1.65c0 .71.55 1.311 1.26 1.331a1.29 1.29 0 0 0 1.311-1.28v-1.841c0-.49.32-.93.8-1.06a3.69 3.69 0 0 0 2.762-3.572a3.714 3.714 0 0 0-3.712-3.701");
}

.f2n26zstl {
  stop-color: var(--svg-color--e5ce53, #E5CE53);
}

.fqt3a9nzi {
  stop-color: var(--svg-color--c37c28, #C37C28);
}

.ft5dv1b6b {
  fill: none;
}

.gjdz49xwo {
  stop-color: var(--svg-color--d9a734, #D9A734);
}

.gl9ydnb2i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M23.782 28.281c2.218-.593 5-2.875 5.843-6.812");
}

.gm-qy5baz {
  d: path("m15.055 2.263l-3.161 1.87c-.8.47-.8 1.63 0 2.111l3.16 1.87c.59.35 1.321.35 1.901 0l3.162-1.87c.8-.47.8-1.63 0-2.11l-3.162-1.871a1.85 1.85 0 0 0-1.9 0");
}

.h31mzvbec {
  fill: var(--svg-color--733919, #733919);
  d: path("M11.479 7.266v.375c0 .421.192.843.576 1.08l3.037 1.79c.567.36 1.269.36 1.826 0l3.037-1.79c.384-.247.576-.669.576-1.08v-.375z");
}

.h5vt7abxq {
  stop-color: var(--svg-color--6f3f2e, #6F3F2E);
}

.i-op0wquf {
  stop-color: var(--svg-color--ecd34c, #ECD34C);
}

.ioos1yi_w {
  stop-color: var(--svg-color--dea933, #DEA933);
}

.iou-y113k {
  d: path("M21.416 3.422H10.592a6.58 6.58 0 0 0-6.582 6.583a6.58 6.58 0 0 0 6.582 6.582h10.814a6.58 6.58 0 0 0 6.583-6.582c.01-3.631-2.942-6.583-6.573-6.583");
}

.ir_nb604z {
  stop-color: var(--svg-color--d4a778, #D4A778);
}

.j-ermkbgy {
  stop-color: var(--svg-color--a96e44, #A96E44);
}

.jdzc-kb6v {
  stop-color: var(--svg-color--beb4b6, #BEB4B6);
}

.jl6ok7z_k {
  d: path("M21.283 12.484H10.758c-4.701 0-8.508 3.67-8.508 8.193c0 4.521 3.807 8.182 8.508 8.182h10.515c4.702 0 8.508-3.66 8.508-8.182c.01-4.522-3.796-8.193-8.498-8.193");
}

.jswq7mbdz {
  stop-color: var(--svg-color--e7ce37, #E7CE37);
}

.jwmmjib6e {
  stop-color: var(--svg-color--dba529, #DBA529);
}

.k8h_m2ido {
  stop-color: var(--svg-color--9c6f5e, #9C6F5E);
}

.kjdwtlbxl {
  stop-color: var(--svg-color--b28c4c, #B28C4C);
}

.koc2hxbjk {
  stop-color: var(--svg-color--99512c, #99512C);
}

.kyc7b125y {
  stop-color: var(--svg-color--e8dfec, #E8DFEC);
  stop-opacity: 0;
}

.l-1k2hbfo {
  d: path("M8.953 9.805c0 1.595 1.154 2.747 2.653 3.177c.45.133.755.544.755 1.003v5.979c0 .678.538 1.236 1.234 1.255c.705.01 1.155-.369 1.155-1.047v-6.094c0-.573.599-1.031 1.187-1.031c.587 0 1.22.458 1.22 1.031v2.14c0 .679.376 1.279 1.072 1.298c.705.01 1.283-.62 1.283-1.297v-2.16c0-.468.314-.888.784-1.012c1.558-.392 2.798-1.608 2.798-3.242c0-5.946-14.14-5.858-14.14 0");
}

.l34omxbdj {
  stop-color: var(--svg-color--dfcdd2, #DFCDD2);
}

.lij6egb7m {
  stop-color: var(--svg-color--764326, #764326);
}

.lnrow6zmv {
  stop-color: var(--svg-color--cfba3a, #CFBA3A);
}

.m2hne6bit {
  stop-color: var(--svg-color--c3a0e2, #C3A0E2);
}

.m58z3lbwq {
  d: path("M19.516 13.375c.718-.625 3.468-1.453 3.234-4c-.625 1.781-1.02 2.302-2.625 2.656c-1.203.266-1.281 1.203-1.281 1.688l.11 3.047h.327c.088-.529-.1-3.1.235-3.391");
}

.mbd0apntt {
  d: path("M21.417 14.287H10.593l-6.582 1.89v2.561a6.58 6.58 0 0 0 6.582 6.583h10.814a6.58 6.58 0 0 0 6.582-6.583v-2.56z");
}

.meg8j5w4o {
  stop-color: var(--svg-color--804b33, #804B33);
}

.mnl9e5y6w {
  stop-color: var(--svg-color--f0d151, #F0D151);
}

.mozx20bcw {
  stop-color: var(--svg-color--934a28, #934A28);
  stop-opacity: 0;
}

.mvks-fbxe {
  stop-color: var(--svg-color--a6572f, #A6572F);
  stop-opacity: 0;
}

.mw_ul3bvd {
  d: path("M13.828 17.047a.25.25 0 0 0 .5 0zm3.455-2.764a.25.25 0 1 0 .5 0zm-2.955 2.764v-2.764h-.5v2.764zm0-2.764c0-.308.159-.697.44-1.012c.28-.313.65-.521 1.044-.521v-.5c-.574 0-1.07.3-1.416.688c-.344.384-.568.887-.568 1.345zm1.485-1.533c.388 0 .755.218 1.034.541c.281.326.436.716.436.992h.5c0-.428-.222-.93-.558-1.319c-.339-.392-.832-.714-1.413-.714z");
}

.n3guf8b2h {
  stop-color: var(--svg-color--8c4756, #8C4756);
  stop-opacity: 0;
}

.nug7pf77x {
  stop-color: var(--svg-color--bbb7bc, #BBB7BC);
}

.o_akhtf2c {
  stop-color: var(--svg-color--dbced5, #DBCED5);
}

.o0kr9_bai {
  d: path("M18.375 3.579h-7.688c-3.578 0-6.468 2.95-6.468 6.582c0 3.641 2.9 6.582 6.468 6.582h7.688z");
}

.osasysb0o {
  cx: 24.52px;
  cy: 25.857px;
  r: 0.536px;
}

.oz5zs-viq {
  stop-color: var(--svg-color--82523e, #82523E);
}

.ozjkh4bzx {
  stop-color: var(--svg-color--d5c137, #D5C137);
}

.pkk5a946u {
  stop-color: var(--svg-color--af774e, #AF774E);
  stop-opacity: 0;
}

.pw87bab_j {
  stop-color: var(--svg-color--ad95c2, #AD95C2);
}

.q4yqn79gq {
  stop-color: var(--svg-color--b49d9f, #B49D9F);
  stop-opacity: 0;
}

.qierc0bug {
  stop-color: var(--svg-color--b97f33, #B97F33);
}

.qkpl4_bws {
  stop-color: var(--svg-color--ebe2f0, #EBE2F0);
}

.s1xtlu6ta {
  stop-color: var(--svg-color--864453, #864453);
  stop-opacity: 0;
}

.so7on2z3v {
  stop-color: var(--svg-color--e7b27d, #E7B27D);
}

.sxyb3q7hj {
  stop-color: var(--svg-color--724c3b, #724C3B);
  stop-opacity: 0;
}

.szwy9ob0j {
  stop-color: var(--svg-color--d08726, #D08726);
}

.t1zan_bns {
  stop-color: var(--svg-color--f1bd92, #F1BD92);
}

.tidere9ei {
  stop-color: var(--svg-color--bb8f65, #BB8F65);
  stop-opacity: 0;
}

.tp_qxirzs {
  stop-color: var(--svg-color--bd7628, #BD7628);
}

.ts-p6y9jk {
  fill: var(--svg-color--884734, #884734);
  d: path("M19.436 6.204h-6.872a3.69 3.69 0 0 0-3.692 3.691c0 1.67 1.11 3.091 2.641 3.542c.46.14.77.57.77 1.05v5.812c0 .71.55 1.31 1.261 1.33c.72.01 1.31-.57 1.31-1.28v-5.672c0-.6.48-1.08 1.081-1.08c.6 0 1.08.48 1.08 1.08v1.65c0 .71.55 1.311 1.26 1.331a1.29 1.29 0 0 0 1.311-1.28v-1.841c0-.49.32-.93.8-1.06a3.69 3.69 0 0 0 2.762-3.572a3.714 3.714 0 0 0-3.712-3.701");
}

.tvs04vy4u {
  stop-color: var(--svg-color--9d623c, #9D623C);
}

.u_19pbcky {
  stop-color: var(--svg-color--d6922d, #D6922D);
}

.u_v-b85_i {
  stop-color: var(--svg-color--f3d357, #F3D357);
  stop-opacity: 0;
}

.u1dhqdhom {
  stop-color: var(--svg-color--e8c12e, #E8C12E);
}

.u93rdlpux {
  stop-color: var(--svg-color--9f5e3e, #9F5E3E);
}

.ucqupq89y {
  stop-color: var(--svg-color--e1b17c, #E1B17C);
}

.uif3opiqw {
  stop-color: var(--svg-color--ebe1f0, #EBE1F0);
}

.utcm51rhh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.36 16.438c2.39 0 5.734-1.579 6.39-4.985");
}

.uxkul1bho {
  stop-color: var(--svg-color--e3d8cd, #E3D8CD);
}

.vbq8obbyj {
  stop-color: var(--svg-color--d99f3f, #D99F3F);
}

.vi95y82wx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M20.695 5.273c0 .282-.189.665-.539.915s-2.416 1.375-3.562 2.03c-.25.143-.82.235-1.336-.124");
}

.vij8z2ktb {
  cx: 22.492px;
  cy: 26.922px;
  r: 1.492px;
}

.vplm8xbfa {
  stop-color: var(--svg-color--a57867, #A57867);
  stop-opacity: 0;
}

.wi4e9nc2z {
  stop-color: var(--svg-color--934a28, #934A28);
}

.xee8eqlnj {
  stop-color: var(--svg-color--724d3d, #724D3D);
}

.xsic05ojx {
  d: path("m17.406 5.113l-.45-.27a1.85 1.85 0 0 0-1.901 0l-.45.27h-3.312v2.1c0 .41.2.82.6 1.05l3.162 1.871c.59.35 1.32.35 1.9 0l3.162-1.87c.4-.24.6-.65.6-1.05V5.112z");
}

.yahwg-zix {
  stop-color: var(--svg-color--b8784c, #B8784C);
}

.yqhhz1byj {
  stop-color: var(--svg-color--c7a22b, #C7A22B);
}

.z4nat-bal {
  stop-color: var(--svg-color--b49d9f, #B49D9F);
}

.zav3cacuj {
  stop-color: var(--svg-color--a37665, #A37665);
}

.zjosdbb5k {
  stop-color: var(--svg-color--c69039, #C69039);
}

.zr7zsdj0g {
  stop-color: var(--svg-color--ba774b, #BA774B);
}

</style>
