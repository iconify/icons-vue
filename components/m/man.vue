<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#i7cNDsq)" class="y6h4mvbgz"/><g filter="url(#iwFCSOc)"><circle fill="url(#iz76EDe)" class="jfk3ysbzo"/></g><g filter="url(#iX39Oie)"><circle fill="url(#iF5VKvc)" class="xamti8bbo"/><circle fill="url(#iSUu2Oe)" class="xamti8bbo"/></g><g filter="url(#iUu7Kvc)"><circle class="s8p-pop4c"/><circle fill="url(#iExvfDb)" class="rwz2nk4bz"/><circle fill="url(#i9mFvud)" class="rwz2nk4bz"/></g><path fill="url(#imSQrJd)" class="ced-wvd9h"/><path fill="url(#iyxEUhd)" class="ced-wvd9h"/><path fill="url(#i4mde2w)" class="ced-wvd9h"/><path fill="url(#ipfpPtd)" class="ced-wvd9h"/><path fill="url(#i5GqAVc)" class="ced-wvd9h"/><g filter="url(#iAVVW8d)"><path class="jdfky4brk"/><path fill="url(#i0L56he)" class="hn7v3_r_d"/><path fill="url(#i9PiGld)" class="hn7v3_r_d"/><path fill="url(#ipmhMmd)" class="hn7v3_r_d"/><path fill="url(#i1ZYILc)" class="hn7v3_r_d"/><path fill="url(#ixrVilb)" class="hn7v3_r_d"/><path fill="url(#iOQ7wyd)" class="hn7v3_r_d"/></g><path fill="url(#i3lgjWj)" class="hn7v3_r_d"/><path fill="url(#iCKtQOd)" class="hn7v3_r_d"/><path fill="url(#iQiQ4xc)" class="hn7v3_r_d"/><g filter="url(#iqF1Cve)"><path class="bonao4btp"/></g><g filter="url(#iMVvpKd)"><path class="f0r3-ownf"/><path fill="url(#ivM33iT)" class="svl3smbra"/><path fill="url(#i7WME6c)" class="svl3smbra"/><path fill="url(#ijptcje)" class="svl3smbra"/></g><path fill="url(#i7zGE5c)" class="svl3smbra"/><path stroke="url(#iA8lpMd)" class="gruk0vban"/><g filter="url(#iABjomc)"><path class="thpp33bxp"/></g><g filter="url(#iHsShud)"><path class="f-mttnbii"/></g><path class="s2axe1clu"/><path fill="url(#iHCkH0b)" class="amhd2acsm"/><path class="mmg9bcbxv"/><g filter="url(#ihWxqac)"><path class="x11ft_07j"/><path fill="url(#idAmIWb)" class="glk_20k3g"/></g><g filter="url(#iSwTdie)"><path fill="url(#iVWNYHB)" class="n6naizbxd"/></g><path class="dn-3kccjq"/><path fill="url(#ieVl6dc)" class="aatijorde"/><path class="bq197y77p"/><g filter="url(#i9NOS3C)"><path fill="url(#iGu0AZc)" class="wjr8unmmj"/></g><g filter="url(#iHGPThe)"><ellipse transform="rotate(-27.914 11.537 16.608)" class="o6qdzjmyx"/><ellipse fill="url(#ipW6Iee)" transform="rotate(-27.914 11.537 16.608)" class="r1m62ccor"/></g><g filter="url(#iptd0xm)"><path stroke="url(#ienLaee)" class="zy4y66vli"/></g><g filter="url(#iYcVnge)"><path stroke="url(#iaNRsjD)" class="gl7lir6wx"/></g><defs><radialGradient id="i7cNDsq" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 4.149 18.059)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iSUu2Oe" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.697 17.565)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iExvfDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.926 19.59)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="i9mFvud" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.455 39.43)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="i4mde2w" cx="0" cy="0" r="1" gradientTransform="matrix(-2.625 16 -21.71914 -3.5633 18.179 15.563)" gradientUnits="userSpaceOnUse"><stop offset=".643" class="z9h1phlew"/><stop offset="1" class="fblnsmbke"/></radialGradient><radialGradient id="ipfpPtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 3 0 20.491 15.688)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="i5GqAVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 3.22556 0 11.991 15.625)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="i0L56he" cx="0" cy="0" r="1" gradientTransform="matrix(-6.4087 8.25997 -14.04691 -10.89865 23.002 3.675)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="ipmhMmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.12461 -3.47136 1.70486 -.0612 8.298 11.615)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="i1ZYILc" cx="0" cy="0" r="1" gradientTransform="matrix(1.60216 -3.6672 2.99087 1.30668 24 14.818)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="ixrVilb" cx="0" cy="0" r="1" gradientTransform="matrix(1.85139 2.29723 -2.0283 1.63465 14.67 2.019)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iOQ7wyd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70588 -5.66099 1.95595 .93492 23.928 10.19)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="i3lgjWj" cx="0" cy="0" r="1" gradientTransform="rotate(76.961 7.436 11.962)scale(1.4992 2.4647)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="r29nd_sam"/><stop offset="1" class="p8ymub_2v"/></radialGradient><radialGradient id="iCKtQOd" cx="0" cy="0" r="1" gradientTransform="matrix(1.35294 1.67337 -3.7494 3.03145 8.013 5.242)" gradientUnits="userSpaceOnUse"><stop class="pb3_oi83v"/><stop offset="1" class="mmcwxbbos"/></radialGradient><radialGradient id="iHCkH0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.18 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="idAmIWb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.026 3.634)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ieVl6dc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 12.043 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ipW6Iee" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.219 2.932)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iz76EDe" x1="7.262" x2="6.068" y1="18.578" y2="18.578" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iF5VKvc" x1="27.029" x2="25.502" y1="16.023" y2="20.753" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="imSQrJd" x1="23.643" x2="9.401" y1="18.785" y2="20.907" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset="1" class="x2e45tbep"/></linearGradient><linearGradient id="iyxEUhd" x1="6.054" x2="10.366" y1="23.813" y2="23.25" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="i9PiGld" x1="7.051" x2="12.463" y1="17.56" y2="7.947" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iQiQ4xc" x1="6.223" x2="6.807" y1="17.473" y2="14.552" gradientUnits="userSpaceOnUse"><stop class="w-ivvz0lu"/><stop offset="1" class="t1ro5ib2e"/></linearGradient><linearGradient id="ivM33iT" x1="14.505" x2="16.254" y1="20.014" y2="20.014" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="i7WME6c" x1="17.866" x2="15.954" y1="20.616" y2="20.588" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="ijptcje" x1="16.479" x2="16.479" y1="22" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="i7zGE5c" x1="16.351" x2="16.351" y1="22.078" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="iA8lpMd" x1="14.792" x2="15.585" y1="25.131" y2="23.568" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iVWNYHB" x1="21.63" x2="21.045" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGu0AZc" x1="13.43" x2="12.845" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ienLaee" x1="21.66" x2="20.876" y1="12.897" y2="11.296" gradientUnits="userSpaceOnUse"><stop class="rd2dtjb_d"/><stop offset="1" class="ugw3yibbz"/></linearGradient><linearGradient id="iaNRsjD" x1="11.999" x2="10.401" y1="12.852" y2="11.809" gradientUnits="userSpaceOnUse"><stop offset=".456" class="rd2dtjb_d"/><stop offset="1" class="ugw3yibbz"/></linearGradient><filter id="iwFCSOc" width="4.711" height="4.711" x="4.907" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_66" stdDeviation=".25"/></filter><filter id="iX39Oie" width="6.477" height="6.477" x="21.89" y="14.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_66"/></filter><filter id="iUu7Kvc" width="4.711" height="4.711" x="22.648" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_66" stdDeviation=".25"/></filter><filter id="iAVVW8d" width="23.5" height="15.5" x="4.366" y="1.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_66"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_1800_66" result="effect2_innerShadow_1800_66"/></filter><filter id="iqF1Cve" width="4.782" height="6.5" x="13.28" y="16.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_66" stdDeviation=".375"/></filter><filter id="iMVvpKd" width="4" height="5.5" x="14.116" y="16.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_66" stdDeviation=".125"/></filter><filter id="iABjomc" width="5.34" height="3.147" x="18.321" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.243137 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_66"/></filter><filter id="iHsShud" width="5.341" height="3.147" x="8.721" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.243137 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_66"/></filter><filter id="ihWxqac" width="1.294" height="1.125" x="18.897" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_66" stdDeviation=".05"/></filter><filter id="iSwTdie" width="1.316" height="1.357" x="20.55" y="16.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_66" stdDeviation=".1"/></filter><filter id="i9NOS3C" width="1.493" height="1.594" x="12.267" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_66" stdDeviation=".1"/></filter><filter id="iHGPThe" width="1.529" height="1.141" x="10.773" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_66" stdDeviation=".05"/></filter><filter id="iptd0xm" width="4.949" height="2.304" x="18.463" y="11.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_66" stdDeviation=".25"/></filter><filter id="iYcVnge" width="5.094" height="2.41" x="8.73" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_66" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man" /></template>
<style>
.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.aatijorde {
  d: path("M12.04 15.897A1.664 1.664 0 0 0 10.436 18h3.215a1.7 1.7 0 0 0 .06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.amhd2acsm {
  d: path("M20.184 15.897A1.664 1.664 0 0 1 21.787 18h-3.214a1.7 1.7 0 0 1-.061-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.bonao4btp {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("M15.603 17.83L14.073 21c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.bq197y77p {
  fill: var(--svg-color--000, #000);
  d: path("M12.993 17.561a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.ced-wvd9h {
  d: path("M6.606 16.916q.045.003.091.003s-.1-1.591-.2-2.685c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.36c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034L25.14 24.4c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6z");
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dn-3kccjq {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.654 15.39c-1.218 0-2.247.84-2.526 1.975a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f-mttnbii {
  fill: var(--svg-color--c85c2f, #C85C2F);
  d: path("m9.08 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05a4 4 0 0 1 .222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.f0r3-ownf {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.404 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.426 0");
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fblnsmbke {
  stop-color: var(--svg-color--d87753, #D87753);
}

.ft5dv1b6b {
  fill: none;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gl7lir6wx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.48 13.684c.61-.54 1.942-1.107 3.593-.844");
}

.glk_20k3g {
  d: path("M20.061 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.gruk0vban {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.557 23.239h-.001a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.22-2.56-.606Z");
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hn7v3_r_d {
  d: path("m25.103 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.2-.299-3.702-.796-7.303-.796s-6.101.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685q-.047 0-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89C11.599 2 13.2 1.703 14.6 2.399c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.jdfky4brk {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m25.103 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.2-.299-3.702-.796-7.303-.796s-6.101.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685q-.047 0-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89C11.599 2 13.2 1.703 14.6 2.399c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.jfk3ysbzo {
  cx: 7.262px;
  cy: 18.059px;
  r: 1.855px;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mmcwxbbos {
  stop-color: var(--svg-color--c9993e, #C9993E);
  stop-opacity: 0;
}

.mmg9bcbxv {
  fill: var(--svg-color--000, #000);
  d: path("M19.23 17.561c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.105.439h-1.687a.86.86 0 0 1-.114-.439");
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.n6naizbxd {
  d: path("M21.666 17.342a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.o6qdzjmyx {
  cx: 11.537px;
  cy: 16.608px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.p8ymub_2v {
  stop-color: var(--svg-color--dcb85c, #DCB85C);
  stop-opacity: 0;
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r1m62ccor {
  cx: 11.537px;
  cy: 16.608px;
  rx: 0.726px;
  ry: 0.368px;
}

.r29nd_sam {
  stop-color: var(--svg-color--dcb85c, #DCB85C);
}

.rd2dtjb_d {
  stop-color: var(--svg-color--cf715d, #CF715D);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rwz2nk4bz {
  cx: 25.003px;
  cy: 18.059px;
  r: 1.855px;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s2axe1clu {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.57 15.39c1.217 0 2.246.84 2.525 1.975a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s8p-pop4c {
  cx: 25.003px;
  cy: 18.059px;
  r: 1.855px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.svl3smbra {
  d: path("m15.404 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.426 0");
}

.t1ro5ib2e {
  stop-color: var(--svg-color--d66b2a, #D66B2A);
  stop-opacity: 0;
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.thpp33bxp {
  fill: var(--svg-color--c85c2f, #C85C2F);
  d: path("m23.053 12.986l-.003-.002l-.003-.002l-.008-.007l-.023-.018a3 3 0 0 0-.288-.2a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a3 3 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.ugw3yibbz {
  stop-color: var(--svg-color--cf715d, #CF715D);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.w-ivvz0lu {
  stop-color: var(--svg-color--d66b2a, #D66B2A);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wjr8unmmj {
  d: path("M13.56 17.366c0-.538-.437-.896-.556-1.005l-.537.52l.33.674z");
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x11ft_07j {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.061 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.x2e45tbep {
  stop-color: var(--svg-color--ffac1b, #FFAC1B);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xamti8bbo {
  cx: 25.003px;
  cy: 18.059px;
  r: 3.113px;
}

.y6h4mvbgz {
  cx: 7.262px;
  cy: 18.059px;
  r: 3.113px;
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.z9h1phlew {
  stop-color: var(--svg-color--d87753, #D87753);
  stop-opacity: 0;
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zy4y66vli {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.213 12.717c.802-.14 2.366-.1 3.449.742");
}

</style>
