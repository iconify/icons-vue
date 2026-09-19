<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iOyAjwd)"><path fill="url(#iISwNoe)" class="hq22c7puo"/></g><g filter="url(#iRT068b)"><path class="cmpcghbvb"/></g><path fill="url(#i0TxvOd)" class="j__2dbl8c"/><path fill="url(#iu3z7he)" class="j__2dbl8c"/><path fill="url(#iLmfKPc)" class="j__2dbl8c"/><path fill="url(#ivuq8vb)" class="dmtae9baw"/><path fill="url(#iPPjVqc)" class="nkpfttkgw"/><circle fill="url(#iOAC5Zc)" class="premirkyr"/><g filter="url(#isc3lbd)"><circle class="bmish6baq"/></g><circle class="g1q7d35fl"/><circle class="a7xn7xp5a"/><path class="wdb575bva"/><path fill="url(#isfOSoE)" class="y8i67ogpw"/><g filter="url(#iEzbvdb)"><path fill="url(#iTvoJId)" class="dpz5gdc6p"/><path fill="url(#iE69o6b)" class="dpz5gdc6p"/><path fill="url(#iM6WT7d)" class="dpz5gdc6p"/></g><g filter="url(#i2jB29b)"><path fill="url(#iKTFDec)" class="hz8z6ybug"/></g><g filter="url(#i16Zvhd)"><circle stroke="url(#iNZrAwd)" class="t_ahmacni"/></g><circle class="vxe9t70ou"/><g filter="url(#id73X0O)"><path class="o93tjvquy"/></g><g filter="url(#iFaDrNb)"><path class="edr6l6bzl"/><path fill="url(#iqx6nad)" class="ur6owyxzy"/></g><path fill="url(#iIWkcQd)" transform="rotate(45.489 14.576 13.488)" class="d1op3cbdr"/><path fill="url(#iUtlsMc)" transform="rotate(45.489 14.576 13.488)" class="d1op3cbdr"/><path fill="url(#iuzVIQb)" class="fly774cjk"/><path fill="url(#iCMC03d)" class="fly774cjk"/><path fill="url(#iLGLmee)" class="fly774cjk"/><path class="j4b-oob_t"/><path fill="url(#iFvkxde)" class="kxj511w9c"/><path fill="url(#iC9b4cY)" class="kxj511w9c"/><path fill="url(#iHKSPCe)" class="kxj511w9c"/><path fill="url(#isGz7gF)" stroke="url(#iSiFHHd)" class="vis-xac5m"/><path clip-rule="evenodd" class="q0mle0b1f"/><g filter="url(#iz2iAtc)"><path clip-rule="evenodd" class="vtuno087z"/></g><path fill="url(#itKwUQb)" stroke="url(#ioFFsHe)" class="k35g_fb-z"/><path clip-rule="evenodd" class="oz7ue17ow"/><g filter="url(#iH0jU0b)"><path stroke="url(#iCTe8gQ)" clip-rule="evenodd" class="fz2afrwxr"/></g><path fill="url(#ig9aAvb)" class="dbn-9aclh"/><path fill="url(#iTXL05c)" class="dbn-9aclh"/><path fill="url(#i8D91fc)" class="dbn-9aclh"/><path fill="url(#imrDwLb)" class="dbn-9aclh"/><path fill="url(#iCxoOwe)" clip-rule="evenodd" class="cffu0ybpx"/><path clip-rule="evenodd" class="as2gxw_cw"/><path fill="url(#imi18od)" clip-rule="evenodd" class="p40y1eg2v"/><path clip-rule="evenodd" class="j7pyjjb5o"/><path fill="url(#iCce9yc)" clip-rule="evenodd" class="jced6l6qw"/><path clip-rule="evenodd" class="el0nx2bgz"/><path fill="url(#ivWUmIc)" clip-rule="evenodd" class="ln4e9ebwd"/><g filter="url(#iPHjZne)"><path clip-rule="evenodd" class="mqgdv6roa"/></g><path fill="url(#iy5Cvse)" class="rg2z0enhu"/><g filter="url(#itQqwMc)"><path class="pupx3gbsj"/></g><defs><radialGradient id="i0TxvOd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.55405 -7.26436 11.24805 -3.95466 24.764 22.247)" gradientUnits="userSpaceOnUse"><stop class="yi44m24qf"/><stop offset="1" class="n84teibwv"/></radialGradient><radialGradient id="iu3z7he" cx="0" cy="0" r="1" gradientTransform="matrix(5.40625 1.9375 -3.91835 10.93347 16.64 17.686)" gradientUnits="userSpaceOnUse"><stop class="krf-kcben"/><stop offset="1" class="vu2z42ehc"/></radialGradient><radialGradient id="iLmfKPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 .59375 -4.82693 -1.65131 22.031 14.904)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="rt88_hbzi"/><stop offset="1" class="ohhy_ccoa"/></radialGradient><radialGradient id="ivuq8vb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 .61718 -2.20347 -1.8967 13.602 18.826)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="gpjywxbbc"/><stop offset="1" class="rhjfe48sn"/></radialGradient><radialGradient id="iPPjVqc" cx="0" cy="0" r="1" gradientTransform="rotate(-42.975 26.397 -17.65)scale(.63033 .94222)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="a5ff04bjp"/><stop offset="1" class="bpmg42uyh"/></radialGradient><radialGradient id="iOAC5Zc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01562 .92188 -.5107 -.56264 18.655 11.266)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="nxwyz4bhr"/><stop offset="1" class="b5e11ac5g"/></radialGradient><radialGradient id="iE69o6b" cx="0" cy="0" r="1" gradientTransform="matrix(1.84375 5.88499 -6.78343 2.12523 15.36 14.06)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="q55noc2it"/><stop offset="1" class="cvbc4ozwb"/></radialGradient><radialGradient id="iM6WT7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.43751 1.34374 -1.37698 1.47307 15.888 13.25)" gradientUnits="userSpaceOnUse"><stop offset=".277" class="j9zy7hbht"/><stop offset="1" class="zy0uiq7qe"/></radialGradient><radialGradient id="iqx6nad" cx="0" cy="0" r="1" gradientTransform="rotate(135.14 5.032 10.976)scale(.85969 .22297)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="p03ir8b6c"/><stop offset="1" class="vf734srhg"/></radialGradient><radialGradient id="iUtlsMc" cx="0" cy="0" r="1" gradientTransform="rotate(90.613 .817 14.107)scale(.28732 .60402)" gradientUnits="userSpaceOnUse"><stop offset=".649" class="wjyjhxryd"/><stop offset="1" class="y01zyrbyt"/></radialGradient><radialGradient id="iFvkxde" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 .29687 -.34413 -.53431 11.951 16.243)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="y84i3jbqp"/><stop offset="1" class="mn36x_bue"/></radialGradient><radialGradient id="iSiFHHd" cx="0" cy="0" r="1" gradientTransform="rotate(133.409 5.773 9.603)scale(1.9895 1.30599)" gradientUnits="userSpaceOnUse"><stop class="y_4rzacqk"/><stop offset=".96" class="td_1nybnc"/></radialGradient><radialGradient id="ioFFsHe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0078 1.59375 -1.27162 -.8041 13.74 14.868)" gradientUnits="userSpaceOnUse"><stop class="y_4rzacqk"/><stop offset="1" class="psw8g7_uy"/></radialGradient><radialGradient id="ig9aAvb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 -2.62501 3.8318 -4.01424 14.203 11.78)" gradientUnits="userSpaceOnUse"><stop class="taiuw254n"/><stop offset="1" class="wk7-7rb8w"/></radialGradient><radialGradient id="iTXL05c" cx="0" cy="0" r="1" gradientTransform="rotate(-157.729 8.547 4.793)scale(6.59658 10.6884)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="g4b5macvs"/><stop offset="1" class="s4_cj8byh"/></radialGradient><radialGradient id="i8D91fc" cx="0" cy="0" r="1" gradientTransform="matrix(.20313 -1.98437 .81115 .08303 8.766 13.623)" gradientUnits="userSpaceOnUse"><stop class="mo87chbhx"/><stop offset="1" class="bbj4eu2oj"/></radialGradient><radialGradient id="imi18od" cx="0" cy="0" r="1" gradientTransform="rotate(146.787 3.54 4.27)scale(3.43755 1.60167)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="mhuz5bc6e"/><stop offset="1" class="ys3ttgv6u"/></radialGradient><radialGradient id="iCce9yc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.21274 2.13195 -.99864 -1.5049 8.962 7.027)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="mhuz5bc6e"/><stop offset="1" class="ys3ttgv6u"/></radialGradient><radialGradient id="ivWUmIc" cx="0" cy="0" r="1" gradientTransform="rotate(144.615 3.362 5.186)scale(3.29193 1.58011)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="mhuz5bc6e"/><stop offset="1" class="ys3ttgv6u"/></radialGradient><radialGradient id="iy5Cvse" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 .375 -.21772 2.97553 10.642 4.1)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="nih21rkyj"/><stop offset="1" class="irx6ulbbo"/></radialGradient><linearGradient id="iISwNoe" x1="26.833" x2="2.047" y1="16.555" y2="16.555" gradientUnits="userSpaceOnUse"><stop class="q8sgc5k5k"/><stop offset="1" class="o5v952b3t"/></linearGradient><linearGradient id="isfOSoE" x1="16.656" x2="16.93" y1="10.295" y2="10.826" gradientUnits="userSpaceOnUse"><stop offset=".18" class="o5x7ihb3q"/><stop offset=".592" class="kgrbxd6rk"/></linearGradient><linearGradient id="iTvoJId" x1="19.016" x2="14.391" y1="13.811" y2="19.311" gradientUnits="userSpaceOnUse"><stop class="cj1s4nyzm"/><stop offset=".886" class="m7ycihb2x"/></linearGradient><linearGradient id="iKTFDec" x1="26.833" x2="2.047" y1="23.617" y2="23.617" gradientUnits="userSpaceOnUse"><stop class="t8k4gwbbc"/><stop offset="1" class="kpw0uhrkg"/></linearGradient><linearGradient id="iNZrAwd" x1="17.219" x2="17.188" y1="17.623" y2="15.717" gradientUnits="userSpaceOnUse"><stop class="wlhz9nb6r"/><stop offset="1" class="uq8mvlbhp"/></linearGradient><linearGradient id="iIWkcQd" x1="14.945" x2="14.954" y1="13.662" y2="14.611" gradientUnits="userSpaceOnUse"><stop class="uhfoyqb3x"/><stop offset="1" class="eb0haibji"/></linearGradient><linearGradient id="iuzVIQb" x1="16.334" x2="17.49" y1="11.383" y2="11.172" gradientUnits="userSpaceOnUse"><stop class="nd7thpbgb"/><stop offset="1" class="fs5c4ebko"/></linearGradient><linearGradient id="iCMC03d" x1="16.734" x2="16.848" y1="10.686" y2="10.764" gradientUnits="userSpaceOnUse"><stop offset=".354" class="r7rn_bcmx"/><stop offset="1" class="ht-1xqb8g"/></linearGradient><linearGradient id="iLGLmee" x1="17.383" x2="17.301" y1="11.104" y2="11.048" gradientUnits="userSpaceOnUse"><stop class="hb9tx9b6i"/><stop offset="1" class="ppgh7wbyg"/></linearGradient><linearGradient id="iC9b4cY" x1="11.422" x2="11.305" y1="17.029" y2="16.846" gradientUnits="userSpaceOnUse"><stop offset=".145" class="u8ol5ho1k"/><stop offset="1" class="bbcrpz64i"/></linearGradient><linearGradient id="iHKSPCe" x1="10.984" x2="11.027" y1="16.4" y2="16.471" gradientUnits="userSpaceOnUse"><stop class="bwf4x3cld"/><stop offset="1" class="a5orf1efs"/></linearGradient><linearGradient id="isGz7gF" x1="16.467" x2="15.279" y1="12.11" y2="13.344" gradientUnits="userSpaceOnUse"><stop class="z1dq245it"/><stop offset="1" class="jzcp_rb0i"/></linearGradient><linearGradient id="itKwUQb" x1="13.678" x2="12.49" y1="14.868" y2="16.102" gradientUnits="userSpaceOnUse"><stop class="z1dq245it"/><stop offset="1" class="jzcp_rb0i"/></linearGradient><linearGradient id="iCTe8gQ" x1="14.269" x2="12.127" y1="14.615" y2="16.661" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qi1y9bzby"/><stop offset=".322" class="f-nlkoezi"/><stop offset=".768" class="qi1y9bzby"/></linearGradient><linearGradient id="imrDwLb" x1="13.703" x2="13.641" y1="12.408" y2="12.35" gradientUnits="userSpaceOnUse"><stop class="d1-v2bc1s"/><stop offset="1" class="lt8u35u8x"/></linearGradient><linearGradient id="iCxoOwe" x1="8.172" x2="10.923" y1="3.833" y2="3.574" gradientUnits="userSpaceOnUse"><stop class="fbovgw07t"/><stop offset="1" class="ir1yjg4tb"/></linearGradient><filter id="iOyAjwd" width="28.306" height="9.762" x="1.847" y="12.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23150"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.584314 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23150" result="effect2_innerShadow_3987_23150"/></filter><filter id="iRT068b" width="19.969" height="19.969" x="10.642" y="1.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.137255 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23150"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.2 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23150" result="effect2_innerShadow_3987_23150"/></filter><filter id="isc3lbd" width="2.053" height="2.053" x="16.759" y="10.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23150" stdDeviation=".075"/></filter><filter id="iEzbvdb" width="11.327" height="11.381" x="8.984" y="8.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.152941 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23150"/></filter><filter id="i2jB29b" width="28.306" height="9.762" x="1.847" y="19.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.580392 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23150"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.482353 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23150" result="effect2_innerShadow_3987_23150"/></filter><filter id="i16Zvhd" width="2.217" height="2.217" x="15.887" y="15.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23150" stdDeviation=".1"/></filter><filter id="id73X0O" width="3.106" height="3.164" x="13.726" y="13.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23150" stdDeviation=".25"/></filter><filter id="iFaDrNb" width="2.203" height="2.458" x="14.338" y="13.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.113725 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23150"/><feGaussianBlur result="effect2_foregroundBlur_3987_23150" stdDeviation=".05"/></filter><filter id="iz2iAtc" width="2.872" height="2.874" x="14.46" y="11.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23150" stdDeviation=".075"/></filter><filter id="iH0jU0b" width="2.872" height="2.874" x="11.68" y="14.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23150" stdDeviation=".075"/></filter><filter id="iPHjZne" width="4.333" height="3.319" x="7.677" y="5.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.188235 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23150"/></filter><filter id="itQqwMc" width="10.371" height="13.323" x="17.499" y="4.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23150" stdDeviation=".35"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-swimming-dark" /></template>
<style>
.a5ff04bjp {
  stop-color: var(--svg-color--424141, #424141);
}

.a5orf1efs {
  stop-color: var(--svg-color--504b5b, #504B5B);
  stop-opacity: 0;
}

.a7xn7xp5a {
  cx: 12.201px;
  cy: 17.514px;
  r: 0.822px;
  fill: var(--svg-color--25141e, #25141E);
}

.as2gxw_cw {
  fill: var(--svg-color--3b2726, #3B2726);
  fill-rule: evenodd;
  d: path("M11.266 3.945a.663.663 0 0 1-.608.714c-1.395.11-2.487 1.076-3.036 1.863a.662.662 0 1 1-1.087-.758c.678-.972 2.085-2.272 4.018-2.426a.663.663 0 0 1 .713.607");
}

.b5e11ac5g {
  stop-color: var(--svg-color--493430, #493430);
}

.bbcrpz64i {
  stop-color: var(--svg-color--443873, #443873);
  stop-opacity: 0;
}

.bbj4eu2oj {
  stop-color: var(--svg-color--dd617e, #DD617E);
  stop-opacity: 0;
}

.bmish6baq {
  cx: 17.785px;
  cy: 11.925px;
  r: 0.877px;
  fill: var(--svg-color--3a1f1e, #3A1F1E);
}

.bpmg42uyh {
  stop-color: var(--svg-color--060d1b, #060D1B);
}

.bwf4x3cld {
  stop-color: var(--svg-color--504b5b, #504B5B);
}

.cffu0ybpx {
  fill-rule: evenodd;
  d: path("M9.936 4.448c-.557.043-1.037.102-1.262.16a.66.66 0 0 1-.804-.489a.673.673 0 0 1 .48-.816c.836-.213 1.78-.266 2.642-.266c.366 0 .647.287.647.659c0 .371.106.686-.26.686c-.345 0-.9.024-1.443.066");
}

.cj1s4nyzm {
  stop-color: var(--svg-color--65504e, #65504E);
}

.cmpcghbvb {
  fill: var(--svg-color--5a413e, #5A413E);
  d: path("M10.642 7.037h4.828a4 4 0 0 1 3.602 2.26l6.164 12.459l4.125-.594l-6.687-13.604a8 8 0 0 0-7.204-4.52h-4.43z");
}

.cvbc4ozwb {
  stop-color: var(--svg-color--2c1421, #2C1421);
}

.d1-v2bc1s {
  stop-color: var(--svg-color--f64a6a, #F64A6A);
}

.d1op3cbdr {
  d: path("M14.576 13.488h.758v1.123h-.758z");
}

.dbn-9aclh {
  d: path("M9.475 15.723c-1.367-1.367-1.202-3.538.236-5.17l1.21-1.203c1.556-1.414 3.79-1.595 5.156-.229l.317.318a.2.2 0 0 1 0 .283l-6.319 6.318a.2.2 0 0 1-.282 0z");
}

.dmtae9baw {
  d: path("m12.973 19.28l-.614-.571l.235-.937l2.14 1.87c-.937.266-1.493-.13-1.761-.363");
}

.dpz5gdc6p {
  d: path("m8.984 14.816l6.11-6.101l4.26 4.74a3.15 3.15 0 0 1-.079 4.296l-1.195 1.235a3.15 3.15 0 0 1-4.39.134z");
}

.eb0haibji {
  stop-color: var(--svg-color--413251, #413251);
}

.edr6l6bzl {
  fill: var(--svg-color--4a3230, #4A3230);
  d: path("m15.22 16.015l-.782-1.556l.29-.281l1.51.852a.4.4 0 0 1 .084.634l-.465.457a.4.4 0 0 1-.638-.106");
}

.el0nx2bgz {
  fill: var(--svg-color--3b2726, #3B2726);
  fill-rule: evenodd;
  d: path("M11.37 5.501a.663.663 0 0 1-.635.69c-1.184.05-2.098.941-2.665 1.871a.662.662 0 1 1-1.131-.69c.65-1.067 1.893-2.427 3.74-2.505a.663.663 0 0 1 .69.634");
}

.f-nlkoezi {
  stop-color: var(--svg-color--5f5669, #5F5669);
  stop-opacity: 0;
}

.fbovgw07t {
  stop-color: var(--svg-color--402e2b, #402E2B);
}

.fly774cjk {
  d: path("M17.065 10.246a.1.1 0 0 1 .139-.027l.439.298a.1.1 0 0 1 .027.139l-.84 1.239l-.605-.41z");
}

.fs5c4ebko {
  stop-color: var(--svg-color--4c4055, #4C4055);
}

.ft5dv1b6b {
  fill: none;
}

.fz2afrwxr {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.077 14.604c-.364-.373-1-.41-1.373-.046l-.56.547c-.372.363-.34.99.024 1.362s.977.43 1.35.067l.559-.546c.372-.364.363-1.012 0-1.384Z");
}

.g1q7d35fl {
  cx: 12.201px;
  cy: 17.514px;
  r: 1.296px;
  fill: var(--svg-color--2f1929, #2F1929);
}

.g4b5macvs {
  stop-color: var(--svg-color--ad525e, #AD525E);
  stop-opacity: 0;
}

.gpjywxbbc {
  stop-color: var(--svg-color--140a1e, #140A1E);
}

.hb9tx9b6i {
  stop-color: var(--svg-color--574e60, #574E60);
}

.hq22c7puo {
  d: path("M3.922 12.139c-.975 0-1.656.49-1.875.734V21.9h27.906v-8.87l-.003-.004c-.623-.545-1.015-.887-2.2-.887c-.906 0-1.67.67-2.05 1.003c-.261.225-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.734-1.914-.734c-.963 0-1.857.666-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.468-1.907.78c-.367.313-1.006.891-2.093.891c-.985 0-1.585-.5-1.915-.774l-.007-.007c-.276-.297-1.072-.89-2.047-.89");
}

.ht-1xqb8g {
  stop-color: var(--svg-color--403044, #403044);
  stop-opacity: 0;
}

.hz8z6ybug {
  d: path("M3.922 19.201c-.975 0-1.656.49-1.875.735v9.027h27.906v-8.871l-.003-.003c-.623-.545-1.015-.888-2.2-.888c-.906 0-1.67.67-2.05 1.003v.001c-.261.224-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.735-1.914-.735c-.963 0-1.857.667-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.469-1.907.781s-1.006.891-2.093.891c-.985 0-1.585-.5-1.915-.775l-.007-.006c-.276-.297-1.072-.89-2.047-.89");
}

.ir1yjg4tb {
  stop-color: var(--svg-color--3d2d35, #3D2D35);
}

.irx6ulbbo {
  stop-color: var(--svg-color--3b2726, #3B2726);
  stop-opacity: 0;
}

.j__2dbl8c {
  d: path("M17.313 16.56c-1.688 1.15-3.224 3.25-3.782 4.157c3.25 2.162 7.927 2.172 9.86 1.906l6.53-2.266c-.765-1.304-2.036-2.52-2.53-3l-5.407-2.375c-.937 0-2.562.141-4.672 1.579");
}

.j4b-oob_t {
  fill: var(--svg-color--4e496a, #4E496A);
  d: path("M10.925 17.319a.1.1 0 0 1-.138-.03l-.29-.444a.1.1 0 0 1 .03-.139l1.253-.817l.4.612z");
}

.j7pyjjb5o {
  fill: var(--svg-color--3b2726, #3B2726);
  fill-rule: evenodd;
  d: path("M11.67 4.727a.663.663 0 0 1-.607.713c-.639.05-1.95.359-2.427.803c-.482.448-.861 1.004-1.156 1.487a.663.663 0 1 1-1.131-.69c.314-.516.769-1.195 1.385-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.243.713.608");
}

.j9zy7hbht {
  stop-color: var(--svg-color--3b262a, #3B262A);
}

.jced6l6qw {
  fill-rule: evenodd;
  d: path("M11.67 4.727a.663.663 0 0 1-.607.713c-.639.05-1.95.359-2.427.803c-.482.448-.861 1.004-1.156 1.487a.663.663 0 1 1-1.131-.69c.314-.516.769-1.195 1.385-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.243.713.608");
}

.jzcp_rb0i {
  stop-color: var(--svg-color--4893e1, #4893E1);
}

.k35g_fb-z {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m13.805 15.802l-.488.476a.696.696 0 0 1-.973-.997l.488-.476a.696.696 0 1 1 .973.997Z");
}

.kgrbxd6rk {
  stop-color: var(--svg-color--0a010d, #0A010D);
}

.kpw0uhrkg {
  stop-color: var(--svg-color--4184e7, #4184E7);
}

.krf-kcben {
  stop-color: var(--svg-color--2d1a1e, #2D1A1E);
}

.kxj511w9c {
  d: path("M10.925 17.319a.1.1 0 0 1-.138-.03l-.29-.444a.1.1 0 0 1 .03-.139l1.253-.817l.4.612z");
}

.ln4e9ebwd {
  fill-rule: evenodd;
  d: path("M11.37 5.501a.663.663 0 0 1-.635.69c-1.184.05-2.098.941-2.665 1.871a.662.662 0 1 1-1.131-.69c.65-1.067 1.893-2.427 3.74-2.505a.663.663 0 0 1 .69.634");
}

.lt8u35u8x {
  stop-color: var(--svg-color--f64a6a, #F64A6A);
  stop-opacity: 0;
}

.m7ycihb2x {
  stop-color: var(--svg-color--381f30, #381F30);
}

.mhuz5bc6e {
  stop-color: var(--svg-color--31182a, #31182A);
}

.mn36x_bue {
  stop-color: var(--svg-color--483e5b, #483E5B);
  stop-opacity: 0;
}

.mo87chbhx {
  stop-color: var(--svg-color--dd617e, #DD617E);
}

.mqgdv6roa {
  fill: var(--svg-color--442b2d, #442B2D);
  fill-rule: evenodd;
  d: path("M11.348 7.037c-.585 0-1.22.253-1.659.552c-.31.21-.668.602-.82.805a.662.662 0 1 1-1.058-.8c.202-.266.661-.78 1.133-1.1c.63-.429 1.52-.756 2.404-.756c.366 0 .662.297.662.662s-.296.637-.662.637");
}

.n84teibwv {
  stop-color: var(--svg-color--4a312f, #4A312F);
}

.nd7thpbgb {
  stop-color: var(--svg-color--574c62, #574C62);
}

.nih21rkyj {
  stop-color: var(--svg-color--3b2726, #3B2726);
}

.nkpfttkgw {
  d: path("m19.598 12.725l-.614-.668l-.785.73l1.664 1.91c.375-.843.047-1.632-.265-1.972");
}

.nxwyz4bhr {
  stop-color: var(--svg-color--655654, #655654);
}

.o5v952b3t {
  stop-color: var(--svg-color--3ea5fe, #3EA5FE);
}

.o5x7ihb3q {
  stop-color: var(--svg-color--312b2d, #312B2D);
}

.o93tjvquy {
  fill: var(--svg-color--351a29, #351A29);
  d: path("m15.047 16.282l-.821-1.636l.304-.296l1.588.896a.42.42 0 0 1 .088.666l-.488.481a.42.42 0 0 1-.67-.111");
}

.ohhy_ccoa {
  stop-color: var(--svg-color--291315, #291315);
  stop-opacity: 0;
}

.oz7ue17ow {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m14.144 16.149l-.488.476a1.181 1.181 0 1 1-1.65-1.69l.487-.477a1.181 1.181 0 1 1 1.65 1.69m-.238-1.42a.82.82 0 0 0-1.162-.013l-.487.476a.821.821 0 0 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.162");
}

.p03ir8b6c {
  stop-color: var(--svg-color--645452, #645452);
}

.p40y1eg2v {
  fill-rule: evenodd;
  d: path("M11.266 3.945a.663.663 0 0 1-.608.714c-1.395.11-2.487 1.076-3.036 1.863a.662.662 0 1 1-1.087-.758c.678-.972 2.085-2.272 4.018-2.426a.663.663 0 0 1 .713.607");
}

.ppgh7wbyg {
  stop-color: var(--svg-color--574e60, #574E60);
  stop-opacity: 0;
}

.premirkyr {
  cx: 17.785px;
  cy: 11.925px;
  r: 1.296px;
}

.psw8g7_uy {
  stop-color: var(--svg-color--2c6fb5, #2C6FB5);
}

.pupx3gbsj {
  fill: var(--svg-color--645352, #645352);
  d: path("M20.637 7.47c-.675-1.476-1.907-1.97-2.438-2.032c1.469-.156 2.672.789 3.156 1.656l5.815 10.25l-2.533-1.281c-1.052-2.25-3.325-7.119-4-8.594");
}

.q0mle0b1f {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m16.933 13.39l-.488.477a1.181 1.181 0 0 1-1.65-1.69l.487-.477a1.182 1.182 0 0 1 1.65 1.69m-.238-1.418a.82.82 0 0 0-1.162-.014l-.487.476a.821.821 0 0 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.161");
}

.q55noc2it {
  stop-color: var(--svg-color--2c1421, #2C1421);
  stop-opacity: 0;
}

.q8sgc5k5k {
  stop-color: var(--svg-color--40aafe, #40AAFE);
}

.qi1y9bzby {
  stop-color: var(--svg-color--5f5669, #5F5669);
}

.r7rn_bcmx {
  stop-color: var(--svg-color--403044, #403044);
}

.rg2z0enhu {
  d: path("M10.642 7.037h4.828a4 4 0 0 1 3.602 2.26l6.164 12.459l4.125-.594l-6.687-13.604a8 8 0 0 0-7.204-4.52h-4.457z");
}

.rhjfe48sn {
  stop-color: var(--svg-color--262442, #262442);
}

.rt88_hbzi {
  stop-color: var(--svg-color--291315, #291315);
}

.s4_cj8byh {
  stop-color: var(--svg-color--ad525e, #AD525E);
}

.t_ahmacni {
  cx: 16.996px;
  cy: 16.693px;
  r: 0.809px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.t8k4gwbbc {
  stop-color: var(--svg-color--3f90f0, #3F90F0);
}

.taiuw254n {
  stop-color: var(--svg-color--fb5684, #FB5684);
}

.td_1nybnc {
  stop-color: var(--svg-color--1f64c4, #1F64C4);
}

.u8ol5ho1k {
  stop-color: var(--svg-color--443873, #443873);
}

.uhfoyqb3x {
  stop-color: var(--svg-color--52475d, #52475D);
}

.uq8mvlbhp {
  stop-color: var(--svg-color--4a2b36, #4A2B36);
}

.ur6owyxzy {
  d: path("m15.22 16.015l-.782-1.556l.29-.281l1.51.852a.4.4 0 0 1 .084.634l-.465.457a.4.4 0 0 1-.638-.106");
}

.vf734srhg {
  stop-color: var(--svg-color--645452, #645452);
  stop-opacity: 0;
}

.vis-xac5m {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m16.594 13.044l-.488.476a.696.696 0 1 1-.973-.997l.488-.476a.696.696 0 0 1 .973.997Z");
}

.vtuno087z {
  stroke: var(--svg-color--5c4c6d, #5C4C6D);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.857 11.809c-.364-.372-1-.409-1.373-.045l-.559.546c-.373.364-.34.99.024 1.362c.363.372.976.431 1.348.067l.56-.546c.372-.363.364-1.012 0-1.384Z");
}

.vu2z42ehc {
  stop-color: var(--svg-color--2d1a1e, #2D1A1E);
  stop-opacity: 0;
}

.vxe9t70ou {
  cx: 16.996px;
  cy: 16.693px;
  r: 0.809px;
  fill: var(--svg-color--2a0219, #2A0219);
}

.wdb575bva {
  fill: var(--svg-color--241a3a, #241A3A);
  d: path("m10.762 16.732l-.84-.714l.293-.555l1.137.887z");
}

.wjyjhxryd {
  stop-color: var(--svg-color--453b50, #453B50);
}

.wk7-7rb8w {
  stop-color: var(--svg-color--e12e6e, #E12E6E);
}

.wlhz9nb6r {
  stop-color: var(--svg-color--544446, #544446);
}

.y_4rzacqk {
  stop-color: var(--svg-color--54abec, #54ABEC);
}

.y01zyrbyt {
  stop-color: var(--svg-color--453b50, #453B50);
  stop-opacity: 0;
}

.y84i3jbqp {
  stop-color: var(--svg-color--483e5b, #483E5B);
}

.y8i67ogpw {
  d: path("m17.133 10.4l-.758-.742l-.844.301c.401.427 1.206 1.277 1.215 1.258z");
}

.yi44m24qf {
  stop-color: var(--svg-color--5c4a4a, #5C4A4A);
}

.ys3ttgv6u {
  stop-color: var(--svg-color--31182a, #31182A);
  stop-opacity: 0;
}

.z1dq245it {
  stop-color: var(--svg-color--479ded, #479DED);
}

.zy0uiq7qe {
  stop-color: var(--svg-color--3b262a, #3B262A);
  stop-opacity: 0;
}

</style>
