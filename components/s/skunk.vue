<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="d87d_3bci"/><path fill="url(#iI8n1ke)" class="arvntq_tq"/><path fill="url(#ilCZo3b)" class="arvntq_tq"/><path fill="url(#iwUYuzc)" class="arvntq_tq"/><path class="qanzjxbew"/><path fill="url(#ii5O7nb)" class="eka8wc3bt"/><path fill="url(#ijZv2TX)" class="eka8wc3bt"/><path fill="url(#iMxozUd)" class="eka8wc3bt"/><path fill="url(#iyc4hHd)" class="sfsdku10n"/><path fill="url(#iv8dtId)" class="sfsdku10n"/><path fill="url(#i9Nt34b)" class="sfsdku10n"/><path fill="url(#itevISb)" class="kx531wbet"/><path fill="url(#ifpzfye)" class="kx531wbet"/><g filter="url(#ioGnMsD)"><path class="ma2hbb_qv"/><path fill="url(#iGIkADd)" class="tup3r7btw"/><path fill="url(#iYQ7qdc)" class="tup3r7btw"/><path fill="url(#iIfRaLc)" class="tup3r7btw"/></g><path fill="url(#iiOGYWb)" class="tup3r7btw"/><path fill="url(#iNUJ1Pd)" class="tup3r7btw"/><path fill="url(#iiY9une)" class="tup3r7btw"/><path fill="url(#iUSJFQR)" class="tup3r7btw"/><path fill="url(#i11U8qd)" class="tup3r7btw"/><path fill="url(#i14sMed)" class="tup3r7btw"/><path fill="url(#iEkwPQc)" class="tup3r7btw"/><path fill="url(#isn6rJe)" class="m7qsgow5w"/><path fill="url(#iWx8PLd)" class="m7qsgow5w"/><path fill="url(#iRqZ86b)" class="m7qsgow5w"/><path fill="url(#iUfHGSO)" class="m7qsgow5w"/><g filter="url(#ioB3nid)"><path fill="url(#iksI6Ld)" class="cek1-tbbh"/></g><path fill="url(#izMjPvb)" class="jptt0ub7i"/><path fill="url(#iDQcaXd)" class="jptt0ub7i"/><path fill="url(#ixKJZId)" stroke="url(#i8qnfLe)" class="ms_9-577w"/><rect fill="url(#isEcy4c)" class="m_r9bcbks"/><rect fill="url(#iM11y2d)" class="m_r9bcbks"/><g filter="url(#i86yEZd)"><rect class="m1fu4s7xo"/></g><rect fill="url(#iIAxjob)" class="wja1myrqf"/><rect fill="url(#ijmz5Ud)" class="wja1myrqf"/><g filter="url(#ilC57re)"><path stroke="url(#itgVzpe)" class="a5zmhyyzz"/></g><g filter="url(#iaRjpfc)"><path fill="url(#iAiYi7b)" class="auwilvqet"/></g><g filter="url(#iEmICAb)"><path stroke="url(#iTEd9wb)" class="hcvktz4um"/></g><g filter="url(#iHSoTMb)"><path stroke="url(#iUsc3Sb)" class="sqazpp91q"/></g><g filter="url(#itFSkHe)"><path class="woh0v9bxj"/></g><g filter="url(#ihKKeLX)"><path stroke="url(#ifXqoxd)" class="fw4lk8bus"/></g><defs><radialGradient id="ilCZo3b" cx="0" cy="0" r="1" gradientTransform="rotate(73.501 3.164 10.793)scale(4.33486 14.7907)" gradientUnits="userSpaceOnUse"><stop class="pvxs_0bri"/><stop offset="1" class="e5mivgixs"/></radialGradient><radialGradient id="iwUYuzc" cx="0" cy="0" r="1" gradientTransform="matrix(.63928 2.50318 -11.76266 3.00406 12.634 5.308)" gradientUnits="userSpaceOnUse"><stop class="zekaiwv8e"/><stop offset=".313" class="qivwlr5pk"/></radialGradient><radialGradient id="ii5O7nb" cx="0" cy="0" r="1" gradientTransform="matrix(.16712 -2.60672 11.46636 .7351 16.296 11.976)" gradientUnits="userSpaceOnUse"><stop class="jaib3cxes"/><stop offset="1" class="ci27cvbxl"/></radialGradient><radialGradient id="ijZv2TX" cx="0" cy="0" r="1" gradientTransform="matrix(3.07752 .04028 -.0519 3.96461 8.016 8.285)" gradientUnits="userSpaceOnUse"><stop class="tsazivyyb"/><stop offset=".673" class="l0o0mnbdi"/></radialGradient><radialGradient id="iMxozUd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.0271 -3.49565 4.50328 -5.18792 27.611 16.961)" gradientUnits="userSpaceOnUse"><stop class="tsazivyyb"/><stop offset="1" class="l0o0mnbdi"/></radialGradient><radialGradient id="iyc4hHd" cx="0" cy="0" r="1" gradientTransform="rotate(67.204 -13.585 24.734)scale(7.69029 6.00473)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="mv8wnxbln"/><stop offset="1" class="see4are_m"/></radialGradient><radialGradient id="itevISb" cx="0" cy="0" r="1" gradientTransform="matrix(-.70105 5.06616 -3.05328 -.4225 20.641 27.99)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="mv8wnxbln"/><stop offset="1" class="see4are_m"/></radialGradient><radialGradient id="iGIkADd" cx="0" cy="0" r="1" gradientTransform="matrix(7.01074 0 0 10.7223 3.859 22.105)" gradientUnits="userSpaceOnUse"><stop class="pq0edbs4l"/><stop offset="1" class="mucg6vbuz"/></radialGradient><radialGradient id="iYQ7qdc" cx="0" cy="0" r="1" gradientTransform="matrix(2.03813 -5.95763 2.75902 .94387 5.978 24.723)" gradientUnits="userSpaceOnUse"><stop class="pq0edbs4l"/><stop offset="1" class="mucg6vbuz"/></radialGradient><radialGradient id="iIfRaLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.12298 .8988 -.52706 .65852 3.765 19.774)" gradientUnits="userSpaceOnUse"><stop class="s0ef5bcsc"/><stop offset="1" class="ky4cw3bcu"/></radialGradient><radialGradient id="iiOGYWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.10571 7.75281 0 17.488 26.26)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="jekr324it"/><stop offset=".966" class="nf-f63h5r"/></radialGradient><radialGradient id="iNUJ1Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.86263 -7.49466 5.65172 -3.6669 17.458 29.31)" gradientUnits="userSpaceOnUse"><stop class="jekr324it"/><stop offset="1" class="nf-f63h5r"/></radialGradient><radialGradient id="iiY9une" cx="0" cy="0" r="1" gradientTransform="rotate(-42.047 47.31 -14.942)scale(2.64014 4.87178)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="jekr324it"/><stop offset=".764" class="nf-f63h5r"/></radialGradient><radialGradient id="iUSJFQR" cx="0" cy="0" r="1" gradientTransform="rotate(-140.164 11.254 11.856)scale(2.97784 5.49493)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="jekr324it"/><stop offset=".764" class="nf-f63h5r"/></radialGradient><radialGradient id="i14sMed" cx="0" cy="0" r="1" gradientTransform="matrix(-5.00293 4.02807 -5.41797 -6.72922 28 18.239)" gradientUnits="userSpaceOnUse"><stop class="vdf1tub8p"/><stop offset=".841" class="pz3vqjzri"/></radialGradient><radialGradient id="iEkwPQc" cx="0" cy="0" r="1" gradientTransform="rotate(102.848 -1.227 12.511)scale(2.58499 2.972)" gradientUnits="userSpaceOnUse"><stop class="zss20nhdv"/><stop offset="1" class="qt9m90hul"/></radialGradient><radialGradient id="iRqZ86b" cx="0" cy="0" r="1" gradientTransform="matrix(1.41443 1.14276 -1.51227 1.87178 3.716 18.211)" gradientUnits="userSpaceOnUse"><stop class="tpb-yyoya"/><stop offset=".631" class="tapjwcczf"/></radialGradient><radialGradient id="iUfHGSO" cx="0" cy="0" r="1" gradientTransform="matrix(1.39761 .90075 -1.61124 2.5 4.702 17.501)" gradientUnits="userSpaceOnUse"><stop class="anu5iqb9o"/><stop offset=".729" class="pr7q9y59r"/></radialGradient><radialGradient id="iDQcaXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82128 .99787 -1.14487 -2.08959 10.821 16.173)" gradientUnits="userSpaceOnUse"><stop offset=".765" class="qa4yvi0lx"/><stop offset="1" class="zgej3rbwh"/></radialGradient><radialGradient id="ixKJZId" cx="0" cy="0" r="1" gradientTransform="matrix(.54349 -.63147 .60349 .5194 10.289 16.743)" gradientUnits="userSpaceOnUse"><stop class="ymr91-b9m"/><stop offset="1" class="s22v9qb2n"/></radialGradient><linearGradient id="iI8n1ke" x1="26.913" x2="28.544" y1="17.99" y2="11.46" gradientUnits="userSpaceOnUse"><stop class="pch7eybtv"/><stop offset="1" class="e5mivgixs"/></linearGradient><linearGradient id="iv8dtId" x1="13.555" x2="13.555" y1="27.487" y2="25.547" gradientUnits="userSpaceOnUse"><stop class="mx7bevkfq"/><stop offset="1" class="see4are_m"/></linearGradient><linearGradient id="i9Nt34b" x1="15.019" x2="15.019" y1="30.245" y2="29.058" gradientUnits="userSpaceOnUse"><stop class="bafmcyb5s"/><stop offset="1" class="yl6oo94_l"/></linearGradient><linearGradient id="ifpzfye" x1="21.445" x2="21.445" y1="27.487" y2="24.621" gradientUnits="userSpaceOnUse"><stop class="mx7bevkfq"/><stop offset="1" class="see4are_m"/></linearGradient><linearGradient id="i11U8qd" x1="10.014" x2="10.014" y1="30.608" y2="28.596" gradientUnits="userSpaceOnUse"><stop class="jekr324it"/><stop offset="1" class="nf-f63h5r"/></linearGradient><linearGradient id="isn6rJe" x1="5.054" x2="10.749" y1="17.501" y2="17.501" gradientUnits="userSpaceOnUse"><stop class="nb0431bup"/><stop offset="1" class="shgb7aclg"/></linearGradient><linearGradient id="iWx8PLd" x1="10.063" x2="6.609" y1="15.001" y2="15.001" gradientUnits="userSpaceOnUse"><stop class="vkg168b_w"/><stop offset="1" class="tnf3hxohd"/></linearGradient><linearGradient id="iksI6Ld" x1="16.91" x2="28.861" y1="15.501" y2="15.501" gradientUnits="userSpaceOnUse"><stop class="nb0431bup"/><stop offset="1" class="shgb7aclg"/></linearGradient><linearGradient id="izMjPvb" x1="10.5" x2="10.5" y1="15.396" y2="18.001" gradientUnits="userSpaceOnUse"><stop class="f-oyqltpo"/><stop offset="1" class="q080c0bvt"/></linearGradient><linearGradient id="i8qnfLe" x1="9.808" x2="10.652" y1="17.555" y2="16.501" gradientUnits="userSpaceOnUse"><stop class="hz4v_5b4c"/><stop offset=".752" class="vjwu2ubwu"/></linearGradient><linearGradient id="isEcy4c" x1="2.887" x2="2.373" y1="19.715" y2="19.715" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iM11y2d" x1="3.025" x2="3.025" y1="20.278" y2="19.758" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iIAxjob" x1="8.28" x2="7.723" y1="18.862" y2="18.862" gradientUnits="userSpaceOnUse"><stop offset=".268" class="dyysy0bzo"/><stop offset="1" class="opkksdiub"/></linearGradient><linearGradient id="ijmz5Ud" x1="8.432" x2="8.432" y1="20.226" y2="19.393" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset=".86" class="jqmybnbeu"/></linearGradient><linearGradient id="itgVzpe" x1="27.185" x2="23.759" y1="3.445" y2="6.342" gradientUnits="userSpaceOnUse"><stop offset=".182" class="j7_eyt_dc"/><stop offset="1" class="aw2fuh2hg"/></linearGradient><linearGradient id="iAiYi7b" x1="11.412" x2="14.151" y1="7.016" y2="7.016" gradientUnits="userSpaceOnUse"><stop class="d_e73fwcy"/><stop offset="1" class="szx2-lc4a"/></linearGradient><linearGradient id="iTEd9wb" x1="15.783" x2="15.783" y1="26.54" y2="30.108" gradientUnits="userSpaceOnUse"><stop class="cr22jpbxn"/><stop offset=".384" class="c25monb7j"/><stop offset="1" class="cr22jpbxn"/></linearGradient><linearGradient id="iUsc3Sb" x1="22.688" x2="20.479" y1="27.185" y2="31.123" gradientUnits="userSpaceOnUse"><stop class="c25monb7j"/><stop offset="1" class="cr22jpbxn"/></linearGradient><linearGradient id="ifXqoxd" x1="26.091" x2="26.091" y1="28.197" y2="22.826" gradientUnits="userSpaceOnUse"><stop class="yj9r1xbix"/><stop offset="1" class="knkzzl4xt"/></linearGradient><filter id="ioGnMsD" width="26.2" height="17" x="2" y="13.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.54902 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4409"/></filter><filter id="ioB3nid" width="17.21" height="5.25" x="10.5" y="13.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.663809 0 0 0 0 0.649167 0 0 0 0 0.683333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4409"/></filter><filter id="i86yEZd" width="1.972" height="3.015" x="6.622" y="17.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4409" stdDeviation=".25"/></filter><filter id="ilC57re" width="10.046" height="11.83" x="20.196" y="1.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4409" stdDeviation=".625"/></filter><filter id="iaRjpfc" width="6.076" height="4.26" x="9.477" y="4.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4409" stdDeviation=".5"/></filter><filter id="iEmICAb" width="1.6" height="4.124" x="14.483" y="25.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4409" stdDeviation=".3"/></filter><filter id="iHSoTMb" width="2.896" height="3.855" x="19.891" y="26.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4409" stdDeviation=".3"/></filter><filter id="itFSkHe" width="1.822" height="1.452" x="10.154" y="14.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4409" stdDeviation=".125"/></filter><filter id="ihKKeLX" width="2" height="8.002" x="26" y="21.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4409" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:skunk" /></template>
<style>
.a5zmhyyzz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M21.82 3.096c2.434.292 7.194 2.417 6.77 8.58");
}

.anu5iqb9o {
  stop-color: var(--svg-color--d2ced5, #D2CED5);
}

.arvntq_tq {
  d: path("M21.63 2.001c-1.99-.03-3.83.63-5.29 1.75c-1.89 1.45-4.2 2.25-6.57 2.25c-.43 0-.77.34-.77.77c0 2.27 1.78 4.12 4.02 4.23v.01h7.69a3.28 3.28 0 0 1 3.29 3.28c0 1.81-1.47 3.29-3.29 3.29H16.8a8.46 8.46 0 0 0 4.71 1.42c4.71 0 8.53-3.84 8.5-8.56c-.04-4.61-3.78-8.37-8.38-8.44");
}

.auwilvqet {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.553 8.146c-2.547 0-3.779-.822-4.076-1.233c2.24.202 3.65-.6 4.076-1.027z");
}

.aw2fuh2hg {
  stop-color: var(--svg-color--838284, #838284);
  stop-opacity: 0;
}

.bafmcyb5s {
  stop-color: var(--svg-color--583971, #583971);
}

.c25monb7j {
  stop-color: var(--svg-color--746f79, #746F79);
  stop-opacity: 0;
}

.cek1-tbbh {
  d: path("M21 13.001c-1.96 0-3.73.81-5 2.1c-.1.1-.2.21-.3.32c-1.8 1.85-3.33 1.45-4.63.44c-.17-.14-.36-.27-.55-.38l-.02.02v1.25l1.53.76c.64.32 1.35.49 2.06.49c1.22 0 2.4-.49 3.26-1.35l.11-.11a5.26 5.26 0 0 1 3.72-1.54c1.76 0 3.4.88 4.38 2.34c.28.41.74.66 1.23.66h.92c-.86-2.89-3.54-5-6.71-5");
}

.ci27cvbxl {
  stop-color: var(--svg-color--aa93c1, #AA93C1);
  stop-opacity: 0;
}

.cr22jpbxn {
  stop-color: var(--svg-color--746f79, #746F79);
}

.d_e73fwcy {
  stop-color: var(--svg-color--6a686f, #6A686F);
}

.d87d_3bci {
  fill: var(--svg-color--625c68, #625C68);
  d: path("M21.63 2.001c-1.99-.03-3.83.63-5.29 1.75c-1.89 1.45-4.2 2.25-6.57 2.25c-.43 0-.77.34-.77.77c0 2.27 1.78 4.12 4.02 4.23v.01h7.69a3.28 3.28 0 0 1 3.29 3.28c0 1.81-1.47 3.29-3.29 3.29H16.8a8.46 8.46 0 0 0 4.71 1.42c4.71 0 8.53-3.84 8.5-8.56c-.04-4.61-3.78-8.37-8.38-8.44");
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e5mivgixs {
  stop-color: var(--svg-color--5c5662, #5C5662);
  stop-opacity: 0;
}

.eka8wc3bt {
  d: path("M22.61 16.961H27v-2.54c0-3-2.43-5.43-5.43-5.43h-7.75c-1.81 0-3.54-.72-4.82-2c.12 2.16 1.86 3.934 4.02 4.034c.859 0 6.613.01 7.69.01c1.81.01 3.29 1.436 3.29 3.256c0 1.1-.55 2.08-1.39 2.67");
}

.f-oyqltpo {
  stop-color: var(--svg-color--605c65, #605C65);
}

.ft5dv1b6b {
  fill: none;
}

.fw4lk8bus {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M27 28.828v-6.002");
}

.hcvktz4um {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.283 26.54v2.924");
}

.hz4v_5b4c {
  stop-color: var(--svg-color--807d84, #807D84);
}

.j7_eyt_dc {
  stop-color: var(--svg-color--989898, #989898);
}

.jaib3cxes {
  stop-color: var(--svg-color--aa93c1, #AA93C1);
}

.jekr324it {
  stop-color: var(--svg-color--593a71, #593A71);
}

.jptt0ub7i {
  d: path("M10.5 18.001a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.knkzzl4xt {
  stop-color: var(--svg-color--7b787e, #7B787E);
  stop-opacity: 0;
}

.kx531wbet {
  d: path("m23.89 25.691l-2.55 4.02a.63.63 0 0 1-.53.29h-1.5c-.17 0-.31-.14-.31-.31v-5.07z");
}

.ky4cw3bcu {
  stop-color: var(--svg-color--716b77, #716B77);
  stop-opacity: 0;
}

.l0o0mnbdi {
  stop-color: var(--svg-color--cec9d4, #CEC9D4);
  stop-opacity: 0;
}

.m_r9bcbks {
  width: 0.887px;
  height: 1.09px;
  x: 2px;
  y: 19.238px;
  rx: 0.443px;
}

.m1fu4s7xo {
  width: 0.972px;
  height: 2.015px;
  x: 7.122px;
  y: 18.087px;
  fill: var(--svg-color--443d4c, #443D4C);
  rx: 0.486px;
}

.m7qsgow5w {
  d: path("M10.2 16.001s-.09-.34-.21-.76q-.615-.24-1.32-.24c-1.27 0-2.45.64-3.15 1.7l-1.2 1.84c-.3.46-.82.74-1.38.74h-.4c-.3 0-.54.24-.54.54v.18h1.46c.97 0 1.88-.46 2.46-1.23l1.15-1.54c.59-.77 1.5-1.23 2.47-1.23z");
}

.ma2hbb_qv {
  fill: var(--svg-color--625c68, #625C68);
  d: path("M21 13.001c3.87 0 7 3.13 7 7v9.38c0 .34-.28.62-.62.62h-2.41c-.22 0-.42-.11-.53-.29l-1.98-3.13c-.23-.36-.63-.58-1.06-.58h-8.16c-.36 0-.71.16-.95.44l-2.73 3.23c-.18.21-.44.33-.72.33H6.63c-.24 0-.39-.24-.29-.45l1.51-3.02c.21-.41.19-.9-.05-1.29l-1.57-2.47c-.31-.52-.76-.77-1.36-.77H3.9c-1.63 0-1.9-1.28-1.9-2.18c0-.3.24-.54.54-.54h.4c.56 0 1.08-.28 1.38-.74l1.2-1.84c.7-1.06 1.88-1.7 3.15-1.7a3.75 3.75 0 0 1 2.4.863v-.003c1.296 1.012 2.824 1.407 4.62-.424A6.98 6.98 0 0 1 21 13.002");
}

.ms_9-577w {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M10.5 17.386a.885.885 0 1 0 0-1.77a.885.885 0 0 0 0 1.77Z");
}

.mucg6vbuz {
  stop-color: var(--svg-color--4b4453, #4B4453);
  stop-opacity: 0;
}

.mv8wnxbln {
  stop-color: var(--svg-color--53485f, #53485F);
}

.mx7bevkfq {
  stop-color: var(--svg-color--282130, #282130);
  stop-opacity: 0;
}

.nb0431bup {
  stop-color: var(--svg-color--bab4c0, #BAB4C0);
}

.nf-f63h5r {
  stop-color: var(--svg-color--593a71, #593A71);
  stop-opacity: 0;
}

.opkksdiub {
  stop-color: var(--svg-color--3d2b34, #3D2B34);
}

.pch7eybtv {
  stop-color: var(--svg-color--5c5662, #5C5662);
}

.pq0edbs4l {
  stop-color: var(--svg-color--4b4453, #4B4453);
}

.pr7q9y59r {
  stop-color: var(--svg-color--d2ced5, #D2CED5);
  stop-opacity: 0;
}

.pvxs_0bri {
  stop-color: var(--svg-color--45404a, #45404A);
}

.pz3vqjzri {
  stop-color: var(--svg-color--7c7a7e, #7C7A7E);
  stop-opacity: 0;
}

.q080c0bvt {
  stop-color: var(--svg-color--584b65, #584B65);
}

.qa4yvi0lx {
  stop-color: var(--svg-color--48444c, #48444C);
  stop-opacity: 0;
}

.qanzjxbew {
  fill: var(--svg-color--baafc6, #BAAFC6);
  d: path("M22.61 16.961H27v-2.54c0-3-2.43-5.43-5.43-5.43h-7.75c-1.81 0-3.54-.72-4.82-2c.12 2.16 1.86 3.934 4.02 4.034c.859 0 6.613.01 7.69.01c1.81.01 3.29 1.436 3.29 3.256c0 1.1-.55 2.08-1.39 2.67");
}

.qivwlr5pk {
  stop-color: var(--svg-color--6e6e6e, #6E6E6E);
  stop-opacity: 0;
}

.qt9m90hul {
  stop-color: var(--svg-color--6d6873, #6D6873);
  stop-opacity: 0;
}

.s0ef5bcsc {
  stop-color: var(--svg-color--716b77, #716B77);
}

.s22v9qb2n {
  stop-color: var(--svg-color--39343e, #39343E);
}

.see4are_m {
  stop-color: var(--svg-color--282130, #282130);
}

.sfsdku10n {
  d: path("m11.11 25.691l2.55 4.02c.11.18.31.29.53.29h1.5c.17 0 .31-.14.31-.31v-5.07z");
}

.shgb7aclg {
  stop-color: var(--svg-color--e4deea, #E4DEEA);
}

.sqazpp91q {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m22.012 26.897l-1.346 2.464");
}

.szx2-lc4a {
  stop-color: var(--svg-color--6a686f, #6A686F);
  stop-opacity: 0;
}

.tapjwcczf {
  stop-color: var(--svg-color--d4d1d8, #D4D1D8);
  stop-opacity: 0;
}

.tnf3hxohd {
  stop-color: var(--svg-color--b8b4bc, #B8B4BC);
  stop-opacity: 0;
}

.tpb-yyoya {
  stop-color: var(--svg-color--d4d1d8, #D4D1D8);
}

.tsazivyyb {
  stop-color: var(--svg-color--cec9d4, #CEC9D4);
}

.tup3r7btw {
  d: path("M21 13.001c3.87 0 7 3.13 7 7v9.38c0 .34-.28.62-.62.62h-2.41c-.22 0-.42-.11-.53-.29l-1.98-3.13c-.23-.36-.63-.58-1.06-.58h-8.16c-.36 0-.71.16-.95.44l-2.73 3.23c-.18.21-.44.33-.72.33H6.63c-.24 0-.39-.24-.29-.45l1.51-3.02c.21-.41.19-.9-.05-1.29l-1.57-2.47c-.31-.52-.76-.77-1.36-.77H3.9c-1.63 0-1.9-1.28-1.9-2.18c0-.3.24-.54.54-.54h.4c.56 0 1.08-.28 1.38-.74l1.2-1.84c.7-1.06 1.88-1.7 3.15-1.7a3.75 3.75 0 0 1 2.4.863v-.003c1.296 1.012 2.824 1.407 4.62-.424A6.98 6.98 0 0 1 21 13.002");
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.vdf1tub8p {
  stop-color: var(--svg-color--7c7a7e, #7C7A7E);
}

.vh3k8hojv {
  stop-color: var(--svg-color--492847, #492847);
}

.vjwu2ubwu {
  stop-color: var(--svg-color--767379, #767379);
  stop-opacity: 0;
}

.vkg168b_w {
  stop-color: var(--svg-color--aea7b5, #AEA7B5);
}

.wja1myrqf {
  width: 0.972px;
  height: 2.015px;
  x: 7.308px;
  y: 17.981px;
  rx: 0.486px;
}

.woh0v9bxj {
  stroke: var(--svg-color--847f8b, #847F8B);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.407 15.294c.327-.02 1.038.128 1.27.886");
}

.yj9r1xbix {
  stop-color: var(--svg-color--7b787e, #7B787E);
}

.yl6oo94_l {
  stop-color: var(--svg-color--583971, #583971);
  stop-opacity: 0;
}

.ymr91-b9m {
  stop-color: var(--svg-color--5c595f, #5C595F);
}

.zekaiwv8e {
  stop-color: var(--svg-color--6e6e6e, #6E6E6E);
}

.zgej3rbwh {
  stop-color: var(--svg-color--48444c, #48444C);
}

.zss20nhdv {
  stop-color: var(--svg-color--6d6873, #6D6873);
}

</style>
