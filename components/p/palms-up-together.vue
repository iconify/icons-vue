<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ioBfnld)"><path class="z_4mmabmo"/></g><path fill="url(#iyRxSbc)" class="q5ysz3o7o"/><path fill="url(#i0mVCWw)" class="q5ysz3o7o"/><path fill="url(#iYyK6hc)" class="q5ysz3o7o"/><path fill="url(#ikmRxvd)" class="q5ysz3o7o"/><path fill="url(#iqFFNdb)" class="q5ysz3o7o"/><path fill="url(#iDAmhhb)" class="j0k3dpbgv"/><path fill="url(#ingIbCc)" class="j0k3dpbgv"/><path fill="url(#i91U3Ec)" class="j0k3dpbgv"/><path fill="url(#iul5Myb)" class="j0k3dpbgv"/><path fill="url(#iEAIW1c)" class="eximagbtk"/><path fill="url(#iaR7sbd)" class="eximagbtk"/><path fill="url(#iAby7Ic)" class="eximagbtk"/><path fill="url(#i0ovoWc)" class="eximagbtk"/><path fill="url(#iKJNatb)" class="rug8kozcm"/><path fill="url(#iEmtvnc)" class="rug8kozcm"/><path fill="url(#iAVNamb)" class="rug8kozcm"/><path fill="url(#iJ7I4zc)" class="o9ljgnk8i"/><g filter="url(#i1vqHbc)"><path fill="url(#i8u4Xbd)" class="hkwkoml1o"/></g><g filter="url(#idVlnJe)"><rect fill="url(#iI4D3JN)" class="rp-87cjel"/></g><g filter="url(#i75VYqb)"><path stroke="url(#iepefed)" class="rdip9ty6g"/></g><g filter="url(#itoDEJc)"><path stroke="url(#iEinW9b)" class="k4zpylcik"/></g><g filter="url(#iEOdVvc)"><path class="rpkly2bkj"/></g><g filter="url(#i2nE6bb)"><path class="z3wih9ejo"/></g><path fill="url(#iTxjjre)" class="dn0wpv6yx"/><path fill="url(#ileJwoe)" class="dn0wpv6yx"/><path fill="url(#iAMcgec)" class="g9w5qxeju"/><path fill="url(#iyyHMyd)" class="g9w5qxeju"/><path fill="url(#iJTo17Z)" class="g9w5qxeju"/><path fill="url(#iSPhCWe)" class="g9w5qxeju"/><path fill="url(#idRjEqc)" class="tvuccgbye"/><path fill="url(#irXBmQe)" class="tvuccgbye"/><path fill="url(#imQ5Gjc)" class="tvuccgbye"/><path fill="url(#ituNWPc)" class="tvuccgbye"/><path fill="url(#iPk99pe)" class="lwx1pdbgj"/><path fill="url(#iWC2LgK)" class="lwx1pdbgj"/><path fill="url(#iQSZb2b)" class="lwx1pdbgj"/><path fill="url(#iWIXNQc)" class="k76qknbrd"/><path fill="url(#i3fkRNd)" class="a0zb82ldq"/><g filter="url(#iRZD9bc)"><path class="e7k48abbx"/></g><g filter="url(#iq6J86o)"><path fill="url(#isUvRqV)" class="ih5-i1b_q"/></g><g filter="url(#iZ836Xc)"><path fill="url(#iDqUEeb)" class="ket8q2nob"/></g><g filter="url(#impiOTd)"><path stroke="url(#iqkrWzd)" class="lzqx84bfc"/></g><defs><linearGradient id="iyRxSbc" x1="2.444" x2="4.561" y1="17.067" y2="17" gradientUnits="userSpaceOnUse"><stop class="nsbj2cccb"/><stop offset="1" class="xuboiccad"/></linearGradient><linearGradient id="i0mVCWw" x1="7.875" x2="6.183" y1="16.297" y2="16.521" gradientUnits="userSpaceOnUse"><stop class="g9i6c8s8c"/><stop offset="1" class="wzjxkuzic"/></linearGradient><linearGradient id="iqFFNdb" x1="6.921" x2="5.649" y1="20.442" y2="18.957" gradientUnits="userSpaceOnUse"><stop class="fbklg7bbk"/><stop offset="1" class="tmfce450i"/></linearGradient><linearGradient id="iDAmhhb" x1="6.193" x2="7.966" y1="14.537" y2="14.571" gradientUnits="userSpaceOnUse"><stop class="gejkdvbik"/><stop offset="1" class="bnbu0x6cl"/></linearGradient><linearGradient id="ingIbCc" x1="10.373" x2="8.922" y1="14.571" y2="14.571" gradientUnits="userSpaceOnUse"><stop class="gejkdvbik"/><stop offset="1" class="bnbu0x6cl"/></linearGradient><linearGradient id="i91U3Ec" x1="8.146" x2="7.966" y1="18.62" y2="16.933" gradientUnits="userSpaceOnUse"><stop class="fbklg7bbk"/><stop offset="1" class="tmfce450i"/></linearGradient><linearGradient id="iEAIW1c" x1="9.604" x2="11.048" y1="16.157" y2="16.16" gradientUnits="userSpaceOnUse"><stop class="gejkdvbik"/><stop offset="1" class="bnbu0x6cl"/></linearGradient><linearGradient id="iaR7sbd" x1="13.614" x2="12.222" y1="16.157" y2="16.157" gradientUnits="userSpaceOnUse"><stop class="gejkdvbik"/><stop offset="1" class="bnbu0x6cl"/></linearGradient><linearGradient id="iAby7Ic" x1="10.947" x2="11.284" y1="20.206" y2="17.605" gradientUnits="userSpaceOnUse"><stop offset=".329" class="fbklg7bbk"/><stop offset="1" class="tmfce450i"/></linearGradient><linearGradient id="iKJNatb" x1="12.012" x2="14.299" y1="18.33" y2="18.268" gradientUnits="userSpaceOnUse"><stop class="gejkdvbik"/><stop offset="1" class="bnbu0x6cl"/></linearGradient><linearGradient id="i8u4Xbd" x1="5.331" x2="6.978" y1="12.293" y2="21.982" gradientUnits="userSpaceOnUse"><stop class="adpbedben"/><stop offset="1" class="lk0z5vbzf"/></linearGradient><linearGradient id="iI4D3JN" x1="8.695" x2="10.915" y1="5.938" y2="17.913" gradientUnits="userSpaceOnUse"><stop class="tuuxhk66v"/><stop offset="1" class="v55jl0bbv"/></linearGradient><linearGradient id="iepefed" x1="13.746" x2="13.746" y1="14.58" y2="27.807" gradientUnits="userSpaceOnUse"><stop class="wvtwdjyyh"/><stop offset="1" class="ni0jqbjqt"/></linearGradient><linearGradient id="iEinW9b" x1="13.883" x2="5.886" y1="20.239" y2="19.835" gradientUnits="userSpaceOnUse"><stop class="pr-doofzj"/><stop offset="1" class="d6thrzyyy"/></linearGradient><linearGradient id="iAMcgec" x1="24.703" x2="27.089" y1="16.313" y2="16.797" gradientUnits="userSpaceOnUse"><stop class="o--thhbty"/><stop offset="1" class="p4z4awbcj"/></linearGradient><linearGradient id="iyyHMyd" x1="26.047" x2="26.672" y1="19.344" y2="17.313" gradientUnits="userSpaceOnUse"><stop class="g6yq06bei"/><stop offset="1" class="e_fkhgb0d"/></linearGradient><linearGradient id="iSPhCWe" x1="28.672" x2="27.266" y1="17.172" y2="17.094" gradientUnits="userSpaceOnUse"><stop class="q384qrg5x"/><stop offset="1" class="q3s5jnbyj"/></linearGradient><linearGradient id="idRjEqc" x1="21.704" x2="24.379" y1="14.107" y2="14.107" gradientUnits="userSpaceOnUse"><stop class="o--thhbty"/><stop offset="1" class="p4z4awbcj"/></linearGradient><linearGradient id="irXBmQe" x1="26.234" x2="24.922" y1="14.375" y2="14.281" gradientUnits="userSpaceOnUse"><stop class="o--thhbty"/><stop offset="1" class="p4z4awbcj"/></linearGradient><linearGradient id="imQ5Gjc" x1="23.293" x2="23.293" y1="18.489" y2="16.106" gradientUnits="userSpaceOnUse"><stop class="g6yq06bei"/><stop offset="1" class="e_fkhgb0d"/></linearGradient><linearGradient id="iPk99pe" x1="18.46" x2="21.026" y1="15.694" y2="15.694" gradientUnits="userSpaceOnUse"><stop class="o--thhbty"/><stop offset="1" class="p4z4awbcj"/></linearGradient><linearGradient id="iWC2LgK" x1="19.984" x2="19.984" y1="20.063" y2="17.688" gradientUnits="userSpaceOnUse"><stop class="g6yq06bei"/><stop offset="1" class="e_fkhgb0d"/></linearGradient><linearGradient id="isUvRqV" x1="18.308" x2="19.096" y1="14.307" y2="23.18" gradientUnits="userSpaceOnUse"><stop class="adpbedben"/><stop offset="1" class="lk0z5vbzf"/></linearGradient><linearGradient id="iDqUEeb" x1="21.3" x2="22.088" y1="12.167" y2="21.039" gradientUnits="userSpaceOnUse"><stop class="idobb_p2w"/><stop offset="1" class="hkdvukbgx"/></linearGradient><linearGradient id="iqkrWzd" x1="25.984" x2="17.334" y1="21.167" y2="20.921" gradientUnits="userSpaceOnUse"><stop class="pr-doofzj"/><stop offset="1" class="d6thrzyyy"/></linearGradient><radialGradient id="iYyK6hc" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -.14062 .68202 3.94055 4.75 19.39)" gradientUnits="userSpaceOnUse"><stop class="fu2fmhb6x"/><stop offset="1" class="w5ks1tb5x"/></radialGradient><radialGradient id="ikmRxvd" cx="0" cy="0" r="1" gradientTransform="rotate(118.722 -.338 7.262)scale(2.24687 2.15189)" gradientUnits="userSpaceOnUse"><stop class="mqtgdv3nd"/><stop offset="1" class="al94c9yqo"/></radialGradient><radialGradient id="iul5Myb" cx="0" cy="0" r="1" gradientTransform="rotate(122.261 2.151 7.208)scale(2.67608 4.1835)" gradientUnits="userSpaceOnUse"><stop class="ndjpbvb6z"/><stop offset="1" class="xrdy_0b-v"/></radialGradient><radialGradient id="i0ovoWc" cx="0" cy="0" r="1" gradientTransform="rotate(121.275 3.288 8.986)scale(2.63929 4.05589)" gradientUnits="userSpaceOnUse"><stop class="ndjpbvb6z"/><stop offset="1" class="xrdy_0b-v"/></radialGradient><radialGradient id="iEmtvnc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4653 -2.46318 3.85437 3.8577 12.598 21.488)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="fbklg7bbk"/><stop offset="1" class="tmfce450i"/></radialGradient><radialGradient id="iAVNamb" cx="0" cy="0" r="1" gradientTransform="rotate(121.275 4.193 10.881)scale(2.63929 4.05589)" gradientUnits="userSpaceOnUse"><stop class="ndjpbvb6z"/><stop offset="1" class="xrdy_0b-v"/></radialGradient><radialGradient id="iJ7I4zc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84374 1.09377 -1.97803 -5.14274 4.828 18.406)" gradientUnits="userSpaceOnUse"><stop offset=".007" class="mi-h41b1z"/><stop offset="1" class="b_-ym3bex"/></radialGradient><radialGradient id="iTxjjre" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21876 1.75844 -1.39364 -1.75846 31.11 17.875)" gradientUnits="userSpaceOnUse"><stop class="fracbub6q"/><stop offset="1" class="w9dq5lb5j"/></radialGradient><radialGradient id="ileJwoe" cx="0" cy="0" r="1" gradientTransform="matrix(11.59374 4.0625 -5.91453 16.87915 18.797 19.344)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="s49b2obup"/><stop offset="1" class="hwpxp6bqc"/></radialGradient><radialGradient id="iJTo17Z" cx="0" cy="0" r="1" gradientTransform="rotate(119.868 11.303 14.032)scale(3.3505 5.00699)" gradientUnits="userSpaceOnUse"><stop class="frslyvb3p"/><stop offset="1" class="z5w_yyfhv"/></radialGradient><radialGradient id="ituNWPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11789 2.60559 -4.01989 -1.72467 25.453 9.237)" gradientUnits="userSpaceOnUse"><stop class="efamoh3_s"/><stop offset="1" class="mg0fgeeql"/></radialGradient><radialGradient id="iQSZb2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 2.5973 -3.88737 -1.3096 21.86 10.84)" gradientUnits="userSpaceOnUse"><stop class="gefl94baw"/><stop offset="1" class="emywybbtm"/></radialGradient><radialGradient id="iWIXNQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.90625 -4.25334 0 17.7 12.5)" gradientUnits="userSpaceOnUse"><stop class="l35eblzvw"/><stop offset="1" class="owngmztan"/></radialGradient><radialGradient id="i3fkRNd" cx="0" cy="0" r="1" gradientTransform="matrix(1.46876 .31249 -1.0418 4.8967 26.952 19.905)" gradientUnits="userSpaceOnUse"><stop class="kigfa5b0t"/><stop offset="1" class="mm9wi-btv"/></radialGradient><filter id="ioBfnld" width="15.887" height="21.793" x="1.113" y="8.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.545098 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3832"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.486275 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3832" result="effect2_innerShadow_20020_3832"/></filter><filter id="i1vqHbc" width="2.833" height="10.003" x="4.201" y="11.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3832" stdDeviation=".25"/></filter><filter id="idVlnJe" width="2.063" height="9.793" x="7.663" y="9.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3832" stdDeviation=".25"/></filter><filter id="i75VYqb" width="6.045" height="16.977" x="10.723" y="12.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3832" stdDeviation=".625"/></filter><filter id="itoDEJc" width="11.477" height="5.166" x="4.28" y="17.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3832" stdDeviation=".625"/></filter><filter id="iEOdVvc" width="7.738" height="10.182" x="1.215" y="15.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3832" stdDeviation="1"/></filter><filter id="i2nE6bb" width="15.887" height="21.293" x="16" y="8.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.545098 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3832"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.486275 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3832" result="effect2_innerShadow_20020_3832"/></filter><filter id="iRZD9bc" width="5.961" height="9.438" x="24.297" y="16.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3832" stdDeviation=".75"/></filter><filter id="iq6J86o" width="2.219" height="8.845" x="17.359" y="13.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3832" stdDeviation=".25"/></filter><filter id="iZ836Xc" width="2.219" height="9.236" x="20.351" y="10.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3832" stdDeviation=".25"/></filter><filter id="impiOTd" width="12.094" height="6.468" x="15.766" y="17.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3832" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palms-up-together" /></template>
<style>
.a0zb82ldq {
  d: path("M30.886 18.957V18.9a1.853 1.853 0 0 0-3.677-.329h-.002l-.793 4.03l3.367 1.203c.258-.72 1.03-3.085 1.105-4.848");
}

.adpbedben {
  stop-color: var(--svg-color--ffd539, #FFD539);
}

.al94c9yqo {
  stop-color: var(--svg-color--f8c535, #F8C535);
  stop-opacity: 0;
}

.b_-ym3bex {
  stop-color: var(--svg-color--ffde2f, #FFDE2F);
  stop-opacity: 0;
}

.bnbu0x6cl {
  stop-color: var(--svg-color--e99815, #E99815);
  stop-opacity: 0;
}

.d6thrzyyy {
  stop-color: var(--svg-color--ffd145, #FFD145);
  stop-opacity: 0;
}

.dn0wpv6yx {
  d: path("M25.807 11.01a1.773 1.773 0 0 0-3.547 0v.74c-.259-.567-.862-.91-1.565-.91a1.7 1.7 0 0 0-1.7 1.701v.916c-.313-.324-.777-.51-1.294-.51a1.7 1.7 0 0 0-1.701 1.7v8.197c0 2.117.656 3.498 1.021 3.979a6.32 6.32 0 0 0 6.14 3.175c2.468-.16 3.883-1.396 4.823-2.576c.86-1.14 1.594-3.012 1.82-3.664l-.002-.012c.276-.781 1.01-3.072 1.084-4.789v-.056a1.853 1.853 0 0 0-2.097-1.837l.306-4.145a1.743 1.743 0 0 0-3.288-.925z");
}

.e_fkhgb0d {
  stop-color: var(--svg-color--ffc03f, #FFC03F);
  stop-opacity: 0;
}

.e7k48abbx {
  stroke: var(--svg-color--ec9b27, #EC9B27);
  stroke-linecap: round;
  d: path("M28.258 18.656c-.188.959-1.367 4.313-1.961 5.438");
}

.efamoh3_s {
  stop-color: var(--svg-color--ffe444, #FFE444);
}

.emywybbtm {
  stop-color: var(--svg-color--f2c330, #F2C330);
  stop-opacity: 0;
}

.eximagbtk {
  d: path("M11.305 10.84c-.94 0-1.7.613-1.7 1.552v6.456a1.7 1.7 0 0 0 2.993 1.105v-5.454c0-.422.154-.778.408-1.042v-.916a1.7 1.7 0 0 0-1.701-1.7");
}

.fbklg7bbk {
  stop-color: var(--svg-color--ffc640, #FFC640);
}

.fracbub6q {
  stop-color: var(--svg-color--ffe84a, #FFE84A);
}

.frslyvb3p {
  stop-color: var(--svg-color--ffe545, #FFE545);
}

.ft5dv1b6b {
  fill: none;
}

.fu2fmhb6x {
  stop-color: var(--svg-color--f49f0a, #F49F0A);
}

.g6yq06bei {
  stop-color: var(--svg-color--ffc03f, #FFC03F);
}

.g9i6c8s8c {
  stop-color: var(--svg-color--dc8602, #DC8602);
}

.g9w5qxeju {
  d: path("M27.485 11.053c.96.07 1.68.906 1.61 1.866l-.306 4.145c-.8.105-1.439.72-1.58 1.508h-.002l-.785 3.975c-.406-.172-1.672-.875-1.263-3.647l.46-6.237a1.743 1.743 0 0 1 1.866-1.61");
}

.gefl94baw {
  stop-color: var(--svg-color--f2c330, #F2C330);
}

.gejkdvbik {
  stop-color: var(--svg-color--e99815, #E99815);
}

.hkdvukbgx {
  stop-color: var(--svg-color--ffd037, #FFD037);
  stop-opacity: 0;
}

.hkwkoml1o {
  d: path("m5.541 20.844l-.837-8.401a.548.548 0 1 1 1.09-.108l.74 7.608z");
}

.hwpxp6bqc {
  stop-color: var(--svg-color--ffc538, #FFC538);
}

.idobb_p2w {
  stop-color: var(--svg-color--ffd037, #FFD037);
}

.ih5-i1b_q {
  d: path("M17.86 21.406v-7.843c.867-.04 1.218.617 1.218 1.218v5.438z");
}

.j0k3dpbgv {
  d: path("M6.193 11.01a1.773 1.773 0 0 1 3.547 0v.74q-.134.287-.136.642v5.493a1.774 1.774 0 0 1-2.789.667l-.434-5.89a1.7 1.7 0 0 0-.188-.668z");
}

.k4zpylcik {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M6.156 19.463c1.406-.416 4.92-.783 7.727 1.08");
}

.k76qknbrd {
  d: path("M19.402 14.499c0-.94-.762-1.552-1.701-1.552a1.7 1.7 0 0 0-1.701 1.7v4.614a1.7 1.7 0 1 0 3.402 0z");
}

.ket8q2nob {
  d: path("M20.851 19.656v-8.234c.867-.04 1.219.617 1.219 1.219v7.015z");
}

.kigfa5b0t {
  stop-color: var(--svg-color--e59318, #E59318);
}

.l35eblzvw {
  stop-color: var(--svg-color--dfa92f, #DFA92F);
}

.lk0z5vbzf {
  stop-color: var(--svg-color--ffd539, #FFD539);
  stop-opacity: 0;
}

.lwx1pdbgj {
  d: path("M20.695 10.84c.94 0 1.7.613 1.7 1.552v6.456a1.7 1.7 0 0 1-2.993 1.105v-5.454c0-.422-.154-.778-.408-1.042v-.916c0-.94.762-1.7 1.701-1.7");
}

.lzqx84bfc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M17.64 21.75c1.115-1.167 4.344-3.312 8.344-2.562");
}

.mg0fgeeql {
  stop-color: var(--svg-color--ffe444, #FFE444);
  stop-opacity: 0;
}

.mi-h41b1z {
  stop-color: var(--svg-color--ffde2f, #FFDE2F);
}

.mm9wi-btv {
  stop-color: var(--svg-color--e59318, #E59318);
  stop-opacity: 0;
}

.mqtgdv3nd {
  stop-color: var(--svg-color--f8c535, #F8C535);
}

.ndjpbvb6z {
  stop-color: var(--svg-color--ffe443, #FFE443);
}

.ni0jqbjqt {
  stop-color: var(--svg-color--ffde43, #FFDE43);
  stop-opacity: 0;
}

.nsbj2cccb {
  stop-color: var(--svg-color--e29133, #E29133);
}

.o--thhbty {
  stop-color: var(--svg-color--df9416, #DF9416);
}

.o9ljgnk8i {
  d: path("M1.114 18.957V18.9a1.853 1.853 0 0 1 3.677-.329h.002l.772 4.012l-3.346 1.22c-.258-.718-1.03-3.084-1.105-4.847");
}

.owngmztan {
  stop-color: var(--svg-color--dfa92f, #DFA92F);
  stop-opacity: 0;
}

.p4z4awbcj {
  stop-color: var(--svg-color--df9416, #DF9416);
  stop-opacity: 0;
}

.pr-doofzj {
  stop-color: var(--svg-color--ffd145, #FFD145);
}

.q384qrg5x {
  stop-color: var(--svg-color--ffdb39, #FFDB39);
}

.q3s5jnbyj {
  stop-color: var(--svg-color--ffdb39, #FFDB39);
  stop-opacity: 0;
}

.q5ysz3o7o {
  d: path("M4.515 11.053c-.96.07-1.68.906-1.61 1.866l.306 4.145c.8.105 1.439.72 1.58 1.508h.002l.785 3.975c.406-.172 1.672-.875 1.263-3.647l-.46-6.237a1.743 1.743 0 0 0-1.866-1.61");
}

.rdip9ty6g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M14.893 14.58v7.862c.011 1.226-.432 4.016-2.295 5.365");
}

.rp-87cjel {
  width: 1.063px;
  height: 8.793px;
  x: 8.163px;
  y: 10.184px;
  rx: 0.531px;
}

.rpkly2bkj {
  stroke: var(--svg-color--ffe242, #FFE242);
  stroke-linecap: round;
  d: path("m3.716 18.485l.944 3.995c.145.594.668 1.442 1.793 1.114");
}

.rug8kozcm {
  d: path("M12.598 14.499c0-.94.762-1.552 1.701-1.552s1.701.761 1.701 1.7v4.614a1.7 1.7 0 1 1-3.402 0z");
}

.s49b2obup {
  stop-color: var(--svg-color--ffc538, #FFC538);
  stop-opacity: 0;
}

.tmfce450i {
  stop-color: var(--svg-color--ffc640, #FFC640);
  stop-opacity: 0;
}

.tuuxhk66v {
  stop-color: var(--svg-color--ffe544, #FFE544);
}

.tvuccgbye {
  d: path("M25.807 11.01a1.773 1.773 0 0 0-3.547 0v.74q.134.287.136.642v5.493a1.774 1.774 0 0 0 2.789.667l.434-5.89c.018-.24.084-.466.188-.668z");
}

.v55jl0bbv {
  stop-color: var(--svg-color--ffe544, #FFE544);
  stop-opacity: 0;
}

.w5ks1tb5x {
  stop-color: var(--svg-color--f49f0a, #F49F0A);
  stop-opacity: 0;
}

.w9dq5lb5j {
  stop-color: var(--svg-color--ffe84a, #FFE84A);
  stop-opacity: 0;
}

.wvtwdjyyh {
  stop-color: var(--svg-color--ffde43, #FFDE43);
}

.wzjxkuzic {
  stop-color: var(--svg-color--dc8602, #DC8602);
  stop-opacity: 0;
}

.xrdy_0b-v {
  stop-color: var(--svg-color--ffe443, #FFE443);
  stop-opacity: 0;
}

.xuboiccad {
  stop-color: var(--svg-color--e29133, #E29133);
  stop-opacity: 0;
}

.z_4mmabmo {
  fill: var(--svg-color--ffc640, #FFC640);
  d: path("M6.193 11.01a1.773 1.773 0 0 1 3.547 0v.74c.259-.567.862-.91 1.565-.91c.94 0 1.7.762 1.7 1.701v.916c.313-.324.776-.51 1.294-.51a1.7 1.7 0 0 1 1.701 1.7v8.197c0 2.117-.656 3.498-1.021 3.979a6.32 6.32 0 0 1-6.14 3.175c-2.468-.16-3.883-1.396-4.823-2.576c-.86-1.14-1.594-3.012-1.82-3.664l.002-.012c-.276-.781-1.01-3.072-1.084-4.789v-.056a1.853 1.853 0 0 1 2.097-1.837l-.306-4.145a1.743 1.743 0 0 1 3.288-.925z");
}

.z3wih9ejo {
  fill: var(--svg-color--ffc03f, #FFC03F);
  d: path("M25.807 11.01a1.773 1.773 0 0 0-3.547 0v.74c-.259-.567-.862-.91-1.565-.91a1.7 1.7 0 0 0-1.7 1.701v.916c-.313-.324-.777-.51-1.294-.51a1.7 1.7 0 0 0-1.701 1.7v8.197c0 2.117.656 3.498 1.021 3.979a6.32 6.32 0 0 0 6.14 3.175c2.468-.16 3.883-1.396 4.823-2.576c.86-1.14 1.594-3.012 1.82-3.664l-.002-.012c.276-.781 1.01-3.072 1.084-4.789v-.056a1.853 1.853 0 0 0-2.097-1.837l.306-4.145a1.743 1.743 0 0 0-3.288-.925z");
}

.z5w_yyfhv {
  stop-color: var(--svg-color--ffe545, #FFE545);
  stop-opacity: 0;
}

</style>
