<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i3gws3d)"><path class="ho8c4qv-t"/><path fill="url(#i50BqvA)" class="fshplm_qh"/></g><g filter="url(#iWBEfzd)"><rect fill="url(#iaaXdJm)" class="hr84ytb3k"/></g><rect fill="url(#i4bsQqM)" class="hr84ytb3k"/><rect fill="url(#iNcCzKe)" class="hr84ytb3k"/><g filter="url(#i2Zvg0b)"><path fill="url(#iARZmxd)" class="hnvfdb27g"/><path fill="url(#iXOpsGb)" class="hnvfdb27g"/></g><path fill="url(#iKMQc5c)" class="if_g-5baf"/><path fill="url(#itE8vrP)" class="kedqcxulx"/><g filter="url(#iiFxNEe)"><path fill="url(#i951KDb)" clip-rule="evenodd" class="kse87ebdr"/><path fill="url(#iVn1z8d)" clip-rule="evenodd" class="kse87ebdr"/><path fill="url(#idjlHVd)" clip-rule="evenodd" class="kse87ebdr"/></g><path fill="url(#ivHm1Bd)" clip-rule="evenodd" class="b22d6cc8e"/><path fill="url(#iYNDNHd)" clip-rule="evenodd" class="b22d6cc8e"/><path fill="url(#ib6tred)" clip-rule="evenodd" class="b22d6cc8e"/><path fill="url(#itOY0te)" clip-rule="evenodd" class="b22d6cc8e"/><g filter="url(#iSIENlx)"><path stroke="url(#i90C6nN)" class="jljp9ukfo"/></g><path fill="url(#iwsqjXe)" class="c_sz91bnp"/><path fill="url(#i6IBNic)" class="greddebom"/><path fill="url(#iI9ZDXb)" class="greddebom"/><path fill="url(#iV7vRXb)" class="greddebom"/><g filter="url(#iYK0dqd)"><path fill="url(#iJOV9Mc)" class="qiz6-fboa"/><path fill="url(#iAa81Bb)" class="qiz6-fboa"/></g><g filter="url(#i9i3gva)"><path fill="url(#iY6eHEb)" class="bbbxoggbv"/></g><g filter="url(#i4tNhwA)"><circle fill="url(#iqoaFvd)" class="mo33pgbcp"/><circle fill="url(#i1X4Wjd)" class="mo33pgbcp"/></g><g filter="url(#iitCb7j)"><circle stroke="url(#iLKzlOT)" class="np5cw2bez"/></g><circle class="w0d0d2ikx"/><g filter="url(#i7OLd1d)"><circle fill="url(#i04UT0c)" class="rrydd7rci"/><circle fill="url(#i9bGcic)" class="rrydd7rci"/></g><circle class="qvljnnbrk"/><g filter="url(#i23Djfb)"><circle stroke="url(#i8lif9c)" transform="rotate(6.56 23.787 26.174)" class="qlrbz4r3x"/></g><g filter="url(#ireHp7c)"><path fill="url(#iBR1vwb)" class="w7-4shbmo"/></g><g filter="url(#iNWRDid)"><path fill="url(#iccehyb)" class="hknt4lxii"/></g><path fill="url(#ip0NlrD)" class="hknt4lxii"/><g filter="url(#iUznj1d)"><circle fill="url(#i57zDWd)" class="spb8apb4j"/></g><defs><linearGradient id="i50BqvA" x1="17.586" x2="17.577" y1="19.081" y2="18.537" gradientUnits="userSpaceOnUse"><stop class="gdbuvyday"/><stop offset="1" class="nio8ltb5l"/></linearGradient><linearGradient id="iaaXdJm" x1="6.934" x2="29.871" y1="24.18" y2="24.18" gradientUnits="userSpaceOnUse"><stop class="wekl4-bzq"/><stop offset="1" class="szzxrsj_e"/></linearGradient><linearGradient id="i4bsQqM" x1="16" x2="16" y1="26.898" y2="25.336" gradientUnits="userSpaceOnUse"><stop class="tbj7vnf6p"/><stop offset="1" class="bbcswg96o"/></linearGradient><linearGradient id="iNcCzKe" x1="16" x2="16" y1="19.023" y2="20.68" gradientUnits="userSpaceOnUse"><stop class="zg8_3v7dr"/><stop offset="1" class="ibn4l8b9i"/></linearGradient><linearGradient id="iARZmxd" x1="17.992" x2="16.188" y1="9.01" y2="9.01" gradientUnits="userSpaceOnUse"><stop class="hjje1xbyl"/><stop offset="1" class="w5ehwdbzn"/></linearGradient><linearGradient id="iKMQc5c" x1="28.512" x2="30.434" y1="20.867" y2="23.367" gradientUnits="userSpaceOnUse"><stop class="icfvebv4d"/><stop offset=".359" class="ylaywebit"/></linearGradient><linearGradient id="i951KDb" x1="8.505" x2="16.648" y1="17.421" y2="17.421" gradientUnits="userSpaceOnUse"><stop class="dx_eeobol"/><stop offset="1" class="w0tgt29xo"/></linearGradient><linearGradient id="idjlHVd" x1="8.566" x2="8.711" y1="15.938" y2="16.008" gradientUnits="userSpaceOnUse"><stop class="nyqlyubpm"/><stop offset="1" class="yavpdsbxm"/></linearGradient><linearGradient id="ivHm1Bd" x1="17.559" x2="26.871" y1="19.023" y2="19.023" gradientUnits="userSpaceOnUse"><stop class="akz3g3-ln"/><stop offset=".537" class="xu2_qhbzc"/></linearGradient><linearGradient id="iYNDNHd" x1="22.762" x2="22.762" y1="12.93" y2="14.492" gradientUnits="userSpaceOnUse"><stop class="iusprebiv"/><stop offset="1" class="n4ma-nbis"/></linearGradient><linearGradient id="itOY0te" x1="25.77" x2="25.59" y1="16.633" y2="16.719" gradientUnits="userSpaceOnUse"><stop offset=".288" class="n1coscxrd"/><stop offset="1" class="zwtejebum"/></linearGradient><linearGradient id="i90C6nN" x1="4.684" x2="24.309" y1="20.68" y2="20.68" gradientUnits="userSpaceOnUse"><stop class="qixhejb-r"/><stop offset="1" class="dr43s3v8q"/></linearGradient><linearGradient id="iwsqjXe" x1="15.899" x2="17.992" y1="11.039" y2="11.039" gradientUnits="userSpaceOnUse"><stop class="y3qyz048x"/><stop offset=".555" class="pfzdqq0hx"/><stop offset=".809" class="pfzdqq0hx"/><stop offset="1" class="rwhw1cobt"/></linearGradient><linearGradient id="i6IBNic" x1="8.809" x2="25.371" y1="23.93" y2="23.867" gradientUnits="userSpaceOnUse"><stop class="cdw63ybve"/><stop offset="1" class="w-hghabud"/></linearGradient><linearGradient id="iI9ZDXb" x1="16.125" x2="16.125" y1="18.711" y2="26.898" gradientUnits="userSpaceOnUse"><stop offset=".015" class="ms_1e8btf"/><stop offset=".137" class="j8baozb5f"/><stop offset=".168" class="j8baozb5f"/><stop offset=".309" class="m5s4g3b7c"/></linearGradient><linearGradient id="iV7vRXb" x1="16.125" x2="16.125" y1="26.898" y2="25.43" gradientUnits="userSpaceOnUse"><stop class="izh-g5jly"/><stop offset="1" class="cijk75tlk"/></linearGradient><linearGradient id="iqoaFvd" x1="6.886" x2="12.131" y1="25.575" y2="25.575" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="iLKzlOT" x1="10.124" x2="7.141" y1="24.139" y2="28.258" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="i04UT0c" x1="21.886" x2="27.131" y1="25.575" y2="25.575" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="i8lif9c" x1="25.124" x2="22.141" y1="24.226" y2="28.346" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="iBR1vwb" x1="11.342" x2="9.9" y1="20.145" y2="18.751" gradientUnits="userSpaceOnUse"><stop class="tsiypwb3s"/><stop offset=".669" class="grw7vraev"/><stop offset="1" class="fb9axybsi"/></linearGradient><filter id="i3gws3d" width="22.219" height="9.797" x="5.871" y="11.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.462745 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10327"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.2" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.282353 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10327" result="effect2_innerShadow_18_10327"/></filter><filter id="iWBEfzd" width="29.742" height="8.875" x="1.129" y="18.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.172549 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10327"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.0588235 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10327" result="effect2_innerShadow_18_10327"/></filter><filter id="i2Zvg0b" width="2.065" height="2.367" x="16.027" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.313726 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10327"/></filter><filter id="iiFxNEe" width="10.085" height="6.694" x="5.899" y="12.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".8"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.490196 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10327"/></filter><filter id="iSIENlx" width="28.177" height="3" x="2.184" y="18.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10327" stdDeviation=".6"/></filter><filter id="iYK0dqd" width="7.894" height="4.417" x="19.574" y="22.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.117647 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10327"/></filter><filter id="i9i3gva" width="7.894" height="4.417" x="4.574" y="22.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.117647 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10327"/></filter><filter id="i4tNhwA" width="6.984" height="6.984" x="5.004" y="22.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10327"/></filter><filter id="iitCb7j" width="7.161" height="7.161" x="5.206" y="22.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10327" stdDeviation=".375"/></filter><filter id="i7OLd1d" width="6.984" height="6.984" x="20.004" y="22.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10327"/></filter><filter id="i23Djfb" width="7.262" height="7.262" x="20.156" y="22.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10327" stdDeviation=".375"/></filter><filter id="ireHp7c" width="3.043" height="1.666" x="8.941" y="18.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10327" stdDeviation=".125"/></filter><filter id="iNWRDid" width="2.189" height="3.156" x="9.98" y="16.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.521569 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10327"/></filter><filter id="iUznj1d" width="1.385" height="1.385" x="16.553" y="7.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10327" stdDeviation=".15"/></filter><radialGradient id="iXOpsGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.66406 .82031 0 17.379 10.438)" gradientUnits="userSpaceOnUse"><stop class="dwa-4wb5f"/><stop offset="1" class="fv92b17mc"/></radialGradient><radialGradient id="itE8vrP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59133 1.48548 0 2.573 23.647)" gradientUnits="userSpaceOnUse"><stop class="abf3gxbvj"/><stop offset="1" class="ugtpc4bzy"/></radialGradient><radialGradient id="iVn1z8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.35736 5.39313 0 14.434 19.42)" gradientUnits="userSpaceOnUse"><stop class="t2--i6m5d"/><stop offset="1" class="wy3xee6bx"/></radialGradient><radialGradient id="ib6tred" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78126 2.71874 -.63106 -.41346 24.746 12.929)" gradientUnits="userSpaceOnUse"><stop offset=".408" class="dx_eeobol"/><stop offset="1" class="ya52ogz_y"/></radialGradient><radialGradient id="iJOV9Mc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62498 3.43751 -5.5919 -2.6434 24.934 23.46)" gradientUnits="userSpaceOnUse"><stop offset=".73" class="rr_0_t_5n"/><stop offset=".961" class="rx051_bid"/></radialGradient><radialGradient id="iAa81Bb" cx="0" cy="0" r="1" gradientTransform="matrix(-.87294 -1.65156 2.9663 -1.56786 27.418 26.898)" gradientUnits="userSpaceOnUse"><stop class="qx3lq2beg"/><stop offset="1" class="fci1bbc1r"/></radialGradient><radialGradient id="iY6eHEb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62498 3.43751 -5.5919 -2.6434 9.934 23.46)" gradientUnits="userSpaceOnUse"><stop offset=".73" class="rr_0_t_5n"/><stop offset=".961" class="rx051_bid"/></radialGradient><radialGradient id="i1X4Wjd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.537 24.554 6.47)scale(1.90543 1.99016)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="i9bGcic" cx="0" cy="0" r="1" gradientTransform="matrix(.78906 -1.73437 1.8115 .82415 23.496 26.14)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="iccehyb" cx="0" cy="0" r="1" gradientTransform="rotate(-95.222 16.397 5.894)scale(5.18338 2.62089)" gradientUnits="userSpaceOnUse"><stop class="v5mr07s9w"/><stop offset="1" class="n15-f_byv"/></radialGradient><radialGradient id="ip0NlrD" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.29781 -.75394 0 12.02 16.72)" gradientUnits="userSpaceOnUse"><stop class="gx35lx4_t"/><stop offset="1" class="u326yfksf"/></radialGradient><radialGradient id="i57zDWd" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 -.63281 .8994 .644 17.293 8.75)" gradientUnits="userSpaceOnUse"><stop class="q-k0gb7jj"/><stop offset="1" class="pd2vndxzo"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:police-car" /></template>
<style>
.a2peghb2c {
  stop-color: var(--svg-color--2b1249, #2B1249);
  stop-opacity: 0;
}

.abf3gxbvj {
  stop-color: var(--svg-color--ffff76, #FFFF76);
}

.akz3g3-ln {
  stop-color: var(--svg-color--6dfeff, #6DFEFF);
}

.ariye-f8h {
  stop-color: var(--svg-color--2d114d, #2D114D);
}

.b22d6cc8e {
  fill-rule: evenodd;
  d: path("m23.93 12.93l2.736 5.536a1 1 0 0 0 .827.555l-.07.002h-8.391a1 1 0 0 1-1-1V13.93a1 1 0 0 1 1-1z");
}

.baem9ki2q {
  stop-color: var(--svg-color--34214f, #34214F);
}

.bbbxoggbv {
  d: path("M12.393 26.898H4.599a3.922 3.922 0 1 1 7.794 0");
}

.bbcswg96o {
  stop-color: var(--svg-color--27163e, #27163E);
  stop-opacity: 0;
}

.c_sz91bnp {
  d: path("M16.027 10.02h1.965v1.02h-1.965z");
}

.cdw63ybve {
  stop-color: var(--svg-color--c1bbce, #C1BBCE);
}

.cijk75tlk {
  stop-color: var(--svg-color--7a5da7, #7A5DA7);
  stop-opacity: 0;
}

.dr43s3v8q {
  stop-color: var(--svg-color--7a7a7b, #7A7A7B);
}

.dwa-4wb5f {
  stop-color: var(--svg-color--ff82a1, #FF82A1);
}

.dx_eeobol {
  stop-color: var(--svg-color--62c5ff, #62C5FF);
}

.f0k16nibb {
  stop-color: var(--svg-color--615b6b, #615B6B);
  stop-opacity: 0;
}

.fb9axybsi {
  stop-color: var(--svg-color--71707c, #71707C);
  stop-opacity: 0;
}

.fci1bbc1r {
  stop-color: var(--svg-color--36294b, #36294B);
  stop-opacity: 0;
}

.fshplm_qh {
  d: path("m10.5 12.037l-4.13 8.299h21.22l-4.043-8.183a2 2 0 0 0-1.794-1.114h-9.642a1.8 1.8 0 0 0-1.612.998");
}

.ft5dv1b6b {
  fill: none;
}

.fv92b17mc {
  stop-color: var(--svg-color--ff82a1, #FF82A1);
  stop-opacity: 0;
}

.gdbuvyday {
  stop-color: var(--svg-color--2d3136, #2D3136);
}

.greddebom {
  d: path("M24.313 26.898H7.938v-7.875h16.375z");
}

.grw7vraev {
  stop-color: var(--svg-color--71707c, #71707C);
}

.gx35lx4_t {
  stop-color: var(--svg-color--e1e0e5, #E1E0E5);
}

.hjje1xbyl {
  stop-color: var(--svg-color--f33265, #F33265);
}

.hknt4lxii {
  d: path("M9.98 18.253a1.3 1.3 0 0 1 1.3-1.3h.14a.6.6 0 0 1 .6.6v1.956a.6.6 0 0 1-.6.6h-.14a1.3 1.3 0 0 1-1.3-1.3z");
}

.hnvfdb27g {
  d: path("M16.027 10.367h1.965V8.982a.982.982 0 0 0-1.965 0z");
}

.ho8c4qv-t {
  fill: var(--svg-color--59585a, #59585A);
  d: path("m10.5 12.037l-4.13 8.299h21.22l-4.043-8.183a2 2 0 0 0-1.794-1.114h-9.642a1.8 1.8 0 0 0-1.612.998");
}

.hr84ytb3k {
  width: 27.742px;
  height: 7.875px;
  x: 2.129px;
  y: 19.023px;
  rx: 1.6px;
}

.ibn4l8b9i {
  stop-color: var(--svg-color--585859, #585859);
  stop-opacity: 0;
}

.icfvebv4d {
  stop-color: var(--svg-color--d51047, #D51047);
}

.if_g-5baf {
  d: path("M29.871 20.96v3.056h-.433a1.527 1.527 0 0 1 0-3.055z");
}

.iusprebiv {
  stop-color: var(--svg-color--1868c3, #1868C3);
}

.izh-g5jly {
  stop-color: var(--svg-color--7a5da7, #7A5DA7);
}

.j8baozb5f {
  stop-color: var(--svg-color--cfcdd4, #CFCDD4);
}

.jljp9ukfo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M3.684 20.242H28.86");
}

.kedqcxulx {
  d: path("M2.129 23.977V20.96h.93a1 1 0 0 1 1 1v1.016a1 1 0 0 1-1 1z");
}

.kse87ebdr {
  fill-rule: evenodd;
  d: path("M6.5 19.019q.045.004.094.004h8.39a1 1 0 0 0 1-1V13.93a1 1 0 0 0-1-1h-4.928L7.3 18.469a1 1 0 0 1-.8.55");
}

.m5s4g3b7c {
  stop-color: var(--svg-color--cfcdd4, #CFCDD4);
  stop-opacity: 0;
}

.mmwl-dsmc {
  stop-color: var(--svg-color--241337, #241337);
}

.mo33pgbcp {
  cx: 8.496px;
  cy: 26.453px;
  r: 3.492px;
}

.ms_1e8btf {
  stop-color: var(--svg-color--bec2c7, #BEC2C7);
}

.n15-f_byv {
  stop-color: var(--svg-color--bfbbc6, #BFBBC6);
}

.n1coscxrd {
  stop-color: var(--svg-color--88daff, #88DAFF);
}

.n4ma-nbis {
  stop-color: var(--svg-color--1868c3, #1868C3);
  stop-opacity: 0;
}

.nio8ltb5l {
  stop-color: var(--svg-color--2d3136, #2D3136);
  stop-opacity: 0;
}

.np5cw2bez {
  cx: 8.786px;
  cy: 26.087px;
  r: 2.455px;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
}

.nyqlyubpm {
  stop-color: var(--svg-color--3eaced, #3EACED);
}

.oeptinb4s {
  stop-color: var(--svg-color--615b6b, #615B6B);
}

.pd2vndxzo {
  stop-color: var(--svg-color--ff87a4, #FF87A4);
  stop-opacity: 0;
}

.pfzdqq0hx {
  stop-color: var(--svg-color--d9d8db, #D9D8DB);
}

.q-k0gb7jj {
  stop-color: var(--svg-color--ff87a4, #FF87A4);
}

.qixhejb-r {
  stop-color: var(--svg-color--7c7b7d, #7C7B7D);
}

.qiz6-fboa {
  d: path("M27.393 26.898h-7.794a3.922 3.922 0 1 1 7.794 0");
}

.qlrbz4r3x {
  cx: 23.787px;
  cy: 26.174px;
  r: 2.455px;
  stroke-width: var(--svg-stroke-width--0-85px, 0.85px);
}

.qvljnnbrk {
  cx: 23.496px;
  cy: 26.453px;
  r: 1.289px;
  fill: var(--svg-color--cec6de, #CEC6DE);
}

.qx3lq2beg {
  stop-color: var(--svg-color--36294b, #36294B);
}

.rr_0_t_5n {
  stop-color: var(--svg-color--281e38, #281E38);
}

.rrydd7rci {
  cx: 23.496px;
  cy: 26.453px;
  r: 3.492px;
}

.rwhw1cobt {
  stop-color: var(--svg-color--c1c1c1, #C1C1C1);
}

.rx051_bid {
  stop-color: var(--svg-color--433a52, #433A52);
}

.spb8apb4j {
  cx: 17.246px;
  cy: 8.662px;
  r: 0.393px;
}

.szzxrsj_e {
  stop-color: var(--svg-color--37333d, #37333D);
}

.t2--i6m5d {
  stop-color: var(--svg-color--68dfff, #68DFFF);
}

.tbj7vnf6p {
  stop-color: var(--svg-color--27163e, #27163E);
}

.tsiypwb3s {
  stop-color: var(--svg-color--6e6283, #6E6283);
}

.u326yfksf {
  stop-color: var(--svg-color--e1e0e5, #E1E0E5);
  stop-opacity: 0;
}

.ugtpc4bzy {
  stop-color: var(--svg-color--f2d061, #F2D061);
}

.v5mr07s9w {
  stop-color: var(--svg-color--8678a1, #8678A1);
}

.w-hghabud {
  stop-color: var(--svg-color--bfb9cb, #BFB9CB);
}

.w0d0d2ikx {
  cx: 8.496px;
  cy: 26.453px;
  r: 1.289px;
  fill: var(--svg-color--d2cae1, #D2CAE1);
}

.w0tgt29xo {
  stop-color: var(--svg-color--58b9ed, #58B9ED);
}

.w5ehwdbzn {
  stop-color: var(--svg-color--f41c5b, #F41C5B);
}

.w7-4shbmo {
  d: path("M11.567 20.168c-1.657.208-2.24-.759-2.376-1.137h2.543v.943c0 .098-.07.182-.167.194");
}

.wekl4-bzq {
  stop-color: var(--svg-color--423f49, #423F49);
}

.wy3xee6bx {
  stop-color: var(--svg-color--68dfff, #68DFFF);
  stop-opacity: 0;
}

.xu2_qhbzc {
  stop-color: var(--svg-color--61c5ff, #61C5FF);
}

.y3qyz048x {
  stop-color: var(--svg-color--878688, #878688);
}

.ya52ogz_y {
  stop-color: var(--svg-color--62c5ff, #62C5FF);
  stop-opacity: 0;
}

.yavpdsbxm {
  stop-color: var(--svg-color--3eaced, #3EACED);
  stop-opacity: 0;
}

.ylaywebit {
  stop-color: var(--svg-color--ff3f6d, #FF3F6D);
}

.zg8_3v7dr {
  stop-color: var(--svg-color--585859, #585859);
}

.zwtejebum {
  stop-color: var(--svg-color--88daff, #88DAFF);
  stop-opacity: 0;
}

</style>
