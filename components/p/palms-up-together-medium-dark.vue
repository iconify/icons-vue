<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ioMlaVd)"><path class="kfu40lb5u"/></g><path fill="url(#ihJe94b)" class="bmpatcbho"/><path fill="url(#ipp9E5b)" class="bsvlz-bbs"/><path fill="url(#iJHi2Me)" class="bsvlz-bbs"/><path fill="url(#iT3nHHe)" class="bsvlz-bbs"/><path fill="url(#iC9H3gD)" class="bsvlz-bbs"/><path fill="url(#iacU86c)" class="bsvlz-bbs"/><path fill="url(#ipCUshe)" class="bsvlz-bbs"/><path fill="url(#iNY8p2D)" class="lgbd-k7ej"/><path fill="url(#imJ9Gze)" class="lgbd-k7ej"/><path fill="url(#iqQ7WNe)" class="lgbd-k7ej"/><path fill="url(#i0n9Hic)" class="lgbd-k7ej"/><path fill="url(#iLwkUsb)" class="jw00e5bpm"/><path fill="url(#ijmKnfe)" class="jw00e5bpm"/><path fill="url(#iEqBihc)" class="jw00e5bpm"/><path fill="url(#iFLCm6b)" class="jw00e5bpm"/><path fill="url(#iiURYyw)" class="kwe384bnh"/><path fill="url(#iD2Xplc)" class="kwe384bnh"/><path fill="url(#i3Bpmcb)" class="kwe384bnh"/><path fill="url(#iUR4zXc)" class="kwe384bnh"/><path fill="url(#iJHFIHc)" class="ujhqir03i"/><path fill="url(#iYFVVqj)" class="ujhqir03i"/><g filter="url(#iUEGjpb)"><path fill="url(#iQTqqVq)" class="g16yvvb2b"/></g><g filter="url(#iFdScGd)"><rect fill="url(#iDYOr8c)" class="wp3fp9bsg"/></g><g filter="url(#io7tZxd)"><path stroke="url(#ivCvJIc)" class="xm0z3ccpp"/></g><g filter="url(#iFkwo3d)"><path stroke="url(#iyZlKnd)" class="awp5c0tzb"/></g><g filter="url(#igauFUc)"><path class="dvi97wb5g"/></g><g filter="url(#ilVHaWb)"><path stroke="url(#iXZajAe)" class="w4t3qsb6h"/></g><g filter="url(#i45lNKb)"><path stroke="url(#isGwJQc)" class="v51fq4b0y"/></g><g filter="url(#irmUV0d)"><path class="fjon2sbyo"/></g><path fill="url(#ihadiSb)" class="lwjej9mny"/><path fill="url(#iVjAwae)" class="lwjej9mny"/><path fill="url(#iDeckhe)" class="lwjej9mny"/><path fill="url(#i3RBBZb)" class="soqxlnoxv"/><path fill="url(#iy8ctmb)" class="soqxlnoxv"/><path fill="url(#ivZmftY)" class="soqxlnoxv"/><path fill="url(#iXgaYTd)" class="soqxlnoxv"/><path fill="url(#iNNJMDc)" class="soqxlnoxv"/><path fill="url(#iPOupzd)" class="nqfo7ub1d"/><path fill="url(#ih8hBae)" class="nqfo7ub1d"/><path fill="url(#i7muZZc)" class="nqfo7ub1d"/><path fill="url(#ib3u7Fb)" class="nqfo7ub1d"/><path fill="url(#iYyyvje)" class="o14407o9p"/><path fill="url(#iY187Ad)" class="o14407o9p"/><path fill="url(#iyF5Svb)" class="o14407o9p"/><path fill="url(#iNHxYja)" class="o14407o9p"/><path fill="url(#i7hLvUd)" class="qhs9-n4dm"/><path fill="url(#izpSeJc)" class="qhs9-n4dm"/><path fill="url(#iFC0AtJ)" class="dbs6_713q"/><g filter="url(#i2ddoBd)"><path class="u7z2ewbgy"/></g><g filter="url(#ibeiuzb)"><path fill="url(#id4I4Xd)" class="cv8923b0m"/></g><g filter="url(#iQadagb)"><path fill="url(#inMDmzS)" class="bw_o2dbrt"/></g><g filter="url(#imW2MVc)"><path stroke="url(#iSDDdWd)" class="ab6ade43t"/></g><g filter="url(#i8kr94b)"><path stroke="url(#ip6VwGc)" class="w3viicb9w"/></g><defs><linearGradient id="ipp9E5b" x1="3.174" x2="5.377" y1="16.891" y2="16.706" gradientUnits="userSpaceOnUse"><stop class="elk1kyryc"/><stop offset="1" class="yo26ssb6x"/></linearGradient><linearGradient id="iJHi2Me" x1="3.174" x2="3.629" y1="16.891" y2="16.871" gradientUnits="userSpaceOnUse"><stop class="m6r91ebpn"/><stop offset="1" class="h8xqjrllq"/></linearGradient><linearGradient id="iT3nHHe" x1="7.875" x2="6.111" y1="16.206" y2="16.361" gradientUnits="userSpaceOnUse"><stop class="wq1a24byi"/><stop offset="1" class="k3nqw-s9c"/></linearGradient><linearGradient id="ipCUshe" x1="7.106" x2="5.649" y1="19.599" y2="18.866" gradientUnits="userSpaceOnUse"><stop class="mjp1bebtp"/><stop offset="1" class="ma8dpybum"/></linearGradient><linearGradient id="iNY8p2D" x1="6.193" x2="8.219" y1="14.519" y2="14.519" gradientUnits="userSpaceOnUse"><stop class="fe9u10bzb"/><stop offset="1" class="cz-9tgook"/></linearGradient><linearGradient id="imJ9Gze" x1="10.254" x2="8.922" y1="14.479" y2="14.479" gradientUnits="userSpaceOnUse"><stop class="ix-dcgb-s"/><stop offset="1" class="rsje90ejm"/></linearGradient><linearGradient id="iqQ7WNe" x1="8.146" x2="8.146" y1="18.528" y2="16.512" gradientUnits="userSpaceOnUse"><stop class="mjp1bebtp"/><stop offset="1" class="ma8dpybum"/></linearGradient><linearGradient id="iLwkUsb" x1="9.604" x2="11.048" y1="16.065" y2="16.068" gradientUnits="userSpaceOnUse"><stop class="ar-k52bcm"/><stop offset="1" class="ovri9mfqo"/></linearGradient><linearGradient id="ijmKnfe" x1="13.245" x2="12.069" y1="16.093" y2="16.093" gradientUnits="userSpaceOnUse"><stop class="q1bvx8bxq"/><stop offset="1" class="hdm6t55jw"/></linearGradient><linearGradient id="iEqBihc" x1="10.947" x2="10.889" y1="20.114" y2="16.481" gradientUnits="userSpaceOnUse"><stop offset=".46" class="mjp1bebtp"/><stop offset="1" class="ma8dpybum"/></linearGradient><linearGradient id="iiURYyw" x1="12.474" x2="14.51" y1="18.172" y2="18.176" gradientUnits="userSpaceOnUse"><stop class="ygrzwlwzo"/><stop offset="1" class="e0ueib9kf"/></linearGradient><linearGradient id="iD2Xplc" x1="16.608" x2="15.216" y1="18.172" y2="18.172" gradientUnits="userSpaceOnUse"><stop class="v28ykubce"/><stop offset="1" class="emdmbl5aq"/></linearGradient><linearGradient id="iQTqqVq" x1="5.331" x2="6.978" y1="12.202" y2="21.89" gradientUnits="userSpaceOnUse"><stop class="i2chtgb5b"/><stop offset="1" class="xp3pqab_w"/></linearGradient><linearGradient id="iDYOr8c" x1="8.695" x2="10.188" y1="9.904" y2="17.956" gradientUnits="userSpaceOnUse"><stop class="wou2uab_w"/><stop offset="1" class="rr79kcfyw"/></linearGradient><linearGradient id="ivCvJIc" x1="15.875" x2="12.598" y1="15.534" y2="27.346" gradientUnits="userSpaceOnUse"><stop class="c3i1aoblk"/><stop offset="1" class="j3224ie7b"/></linearGradient><linearGradient id="iyZlKnd" x1="13.883" x2="5.886" y1="20.148" y2="19.743" gradientUnits="userSpaceOnUse"><stop class="olqdqsbnv"/><stop offset="1" class="m35m8eo0n"/></linearGradient><linearGradient id="iXZajAe" x1="7.129" x2="6.894" y1="18.562" y2="20.983" gradientUnits="userSpaceOnUse"><stop class="q_7f0ky7a"/><stop offset="1" class="e13jpvkcz"/></linearGradient><linearGradient id="isGwJQc" x1="12.725" x2="12.579" y1="19.331" y2="19.754" gradientUnits="userSpaceOnUse"><stop class="q_7f0ky7a"/><stop offset="1" class="e13jpvkcz"/></linearGradient><linearGradient id="i3RBBZb" x1="24.703" x2="27.089" y1="16.221" y2="16.706" gradientUnits="userSpaceOnUse"><stop class="ln2ja-boi"/><stop offset="1" class="wf90xkmls"/></linearGradient><linearGradient id="iy8ctmb" x1="26.047" x2="26.672" y1="19.252" y2="17.221" gradientUnits="userSpaceOnUse"><stop class="cr1m--qed"/><stop offset="1" class="yq-_nn8pm"/></linearGradient><linearGradient id="iXgaYTd" x1="28.672" x2="27.266" y1="17.08" y2="17.002" gradientUnits="userSpaceOnUse"><stop class="qaxjt3bvn"/><stop offset="1" class="mv47md2vd"/></linearGradient><linearGradient id="iPOupzd" x1="21.704" x2="24.379" y1="14.015" y2="14.015" gradientUnits="userSpaceOnUse"><stop class="wgorrrbcv"/><stop offset="1" class="h018b2btt"/></linearGradient><linearGradient id="ih8hBae" x1="26.234" x2="24.781" y1="14.284" y2="14.188" gradientUnits="userSpaceOnUse"><stop class="wx8nb9blg"/><stop offset="1" class="hu_2uf5ts"/></linearGradient><linearGradient id="i7muZZc" x1="23.293" x2="23.293" y1="18.397" y2="16.015" gradientUnits="userSpaceOnUse"><stop class="cr1m--qed"/><stop offset="1" class="yq-_nn8pm"/></linearGradient><linearGradient id="iYyyvje" x1="18.46" x2="21.026" y1="15.603" y2="15.603" gradientUnits="userSpaceOnUse"><stop class="tur--yjix"/><stop offset="1" class="l-dot2bsz"/></linearGradient><linearGradient id="iY187Ad" x1="19.984" x2="19.984" y1="19.971" y2="17.596" gradientUnits="userSpaceOnUse"><stop class="cr1m--qed"/><stop offset="1" class="yq-_nn8pm"/></linearGradient><linearGradient id="id4I4Xd" x1="17.859" x2="19.1" y1="13.745" y2="22.988" gradientUnits="userSpaceOnUse"><stop class="pqyz0absy"/><stop offset="1" class="m4p32_y1a"/></linearGradient><linearGradient id="inMDmzS" x1="21.3" x2="22.088" y1="12.075" y2="20.948" gradientUnits="userSpaceOnUse"><stop class="ifw347z9v"/><stop offset="1" class="s1vs0cc2q"/></linearGradient><linearGradient id="iSDDdWd" x1="25.984" x2="17.334" y1="21.076" y2="20.829" gradientUnits="userSpaceOnUse"><stop class="yycb43boa"/><stop offset="1" class="nuppr-bkj"/></linearGradient><linearGradient id="ip6VwGc" x1="9.706" x2="9.651" y1="18.818" y2="19.323" gradientUnits="userSpaceOnUse"><stop class="q_7f0ky7a"/><stop offset="1" class="e13jpvkcz"/></linearGradient><radialGradient id="ihJe94b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69948 16.869 -11.98364 -1.2073 10.954 14.105)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="x8qf5nthx"/><stop offset="1" class="i-knb0djz"/></radialGradient><radialGradient id="iC9H3gD" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 -.125 .49576 4.58576 4.5 19.594)" gradientUnits="userSpaceOnUse"><stop class="svlwqobaf"/><stop offset="1" class="onzu-erzg"/></radialGradient><radialGradient id="iacU86c" cx="0" cy="0" r="1" gradientTransform="matrix(-.28574 2.59375 -2.48411 -.27366 4.91 10.156)" gradientUnits="userSpaceOnUse"><stop class="xqdj4b39a"/><stop offset="1" class="x4fcyacrp"/></radialGradient><radialGradient id="i0n9Hic" cx="0" cy="0" r="1" gradientTransform="rotate(122.261 2.176 7.163)scale(2.67608 4.1835)" gradientUnits="userSpaceOnUse"><stop class="q6jrxcc7q"/><stop offset="1" class="lgp37cc6w"/></radialGradient><radialGradient id="iFLCm6b" cx="0" cy="0" r="1" gradientTransform="rotate(108.681 2.332 9.593)scale(2.69033 2.49995)" gradientUnits="userSpaceOnUse"><stop class="l662yvdfg"/><stop offset="1" class="ha5jxh3sd"/></radialGradient><radialGradient id="i3Bpmcb" cx="0" cy="0" r="1" gradientTransform="rotate(-49.148 29.119 -3.34)scale(4.04834 6.33482)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ot1vq2b4o"/><stop offset="1" class="f6ekcgg0m"/></radialGradient><radialGradient id="iUR4zXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.58526 2.25577 -1.30627 -.918 15.884 12.855)" gradientUnits="userSpaceOnUse"><stop class="m1_xat9ce"/><stop offset="1" class="ar8b2mbjf"/></radialGradient><radialGradient id="iJHFIHc" cx="0" cy="0" r="1" gradientTransform="rotate(161.655 .935 9.547)scale(2.33228 4.21779)" gradientUnits="userSpaceOnUse"><stop offset=".007" class="qzw1o6bdd"/><stop offset="1" class="qqqcpbm9x"/></radialGradient><radialGradient id="iYFVVqj" cx="0" cy="0" r="1" gradientTransform="matrix(2.89136 -2.98366 4.84233 4.69254 1.505 20.06)" gradientUnits="userSpaceOnUse"><stop offset=".696" class="vsj_tyu0c"/><stop offset="1" class="hl27kjgub"/></radialGradient><radialGradient id="ihadiSb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99618 1.49687 -.76417 -1.01907 30.887 18.045)" gradientUnits="userSpaceOnUse"><stop class="xfue8_sgp"/><stop offset=".767" class="iwnvb510f"/></radialGradient><radialGradient id="iVjAwae" cx="0" cy="0" r="1" gradientTransform="matrix(11.59374 4.0625 -5.91453 16.87915 18.797 19.252)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="oqor4i64r"/><stop offset="1" class="vxks8w3rp"/></radialGradient><radialGradient id="iDeckhe" cx="0" cy="0" r="1" gradientTransform="matrix(-11.6961 14.86203 -11.99609 -9.44067 28.924 15.076)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="x8qf5nthx"/><stop offset="1" class="i-knb0djz"/></radialGradient><radialGradient id="ivZmftY" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 .625 -.32493 -.7636 28.875 11.969)" gradientUnits="userSpaceOnUse"><stop class="ayvqo3bhc"/><stop offset="1" class="njccxgbdt"/></radialGradient><radialGradient id="iNNJMDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.82844 3.47633 -1.72718 -.4116 27.612 19.462)" gradientUnits="userSpaceOnUse"><stop class="yqzfmehed"/><stop offset="1" class="a9en4zbqi"/></radialGradient><radialGradient id="ib3u7Fb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9104 1.45892 -.88699 -1.16148 25.807 9.614)" gradientUnits="userSpaceOnUse"><stop class="uq71djbfa"/><stop offset="1" class="cf2dfabjy"/></radialGradient><radialGradient id="iyF5Svb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.46839 3.88383 0 20.695 19.934)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="l7yoraclh"/><stop offset="1" class="tr4d1cbsg"/></radialGradient><radialGradient id="iNHxYja" cx="0" cy="0" r="1" gradientTransform="rotate(132.113 8.486 10.565)scale(1.96669 1.26799)" gradientUnits="userSpaceOnUse"><stop class="ifw347z9v"/><stop offset="1" class="s1vs0cc2q"/></radialGradient><radialGradient id="i7hLvUd" cx="0" cy="0" r="1" gradientTransform="matrix(.44 3.2784 -4.5721 .61364 17.7 12.254)" gradientUnits="userSpaceOnUse"><stop class="gh-jb31jf"/><stop offset="1" class="j8vgg1bhe"/></radialGradient><radialGradient id="izpSeJc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.27068 1.29423 -.92672 -.90986 19.143 13.473)" gradientUnits="userSpaceOnUse"><stop class="onfq42btt"/><stop offset="1" class="to1afybpb"/></radialGradient><radialGradient id="iFC0AtJ" cx="0" cy="0" r="1" gradientTransform="rotate(20.056 -42.317 84.917)scale(1.57817 4.28098)" gradientUnits="userSpaceOnUse"><stop class="wt_pgmbce"/><stop offset="1" class="fymftbbov"/></radialGradient><filter id="ioMlaVd" width="15.887" height="21.793" x="1.113" y="8.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.278431 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3881"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.364706 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3881" result="effect2_innerShadow_20020_3881"/></filter><filter id="iUEGjpb" width="2.833" height="10.003" x="4.201" y="11.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation=".25"/></filter><filter id="iFdScGd" width="2.063" height="9.793" x="7.663" y="9.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation=".25"/></filter><filter id="io7tZxd" width="6.045" height="16.977" x="10.723" y="12.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation=".625"/></filter><filter id="iFkwo3d" width="11.477" height="5.166" x="4.28" y="17.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation=".625"/></filter><filter id="igauFUc" width="7.738" height="10.182" x=".766" y="16.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation="1"/></filter><filter id="ilVHaWb" width="2.012" height="2.673" x="5.305" y="18.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation=".125"/></filter><filter id="i45lNKb" width="3.141" height="1.381" x="9.958" y="18.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation=".125"/></filter><filter id="irmUV0d" width="15.887" height="21.293" x="16" y="8.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.219608 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3881"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.219608 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3881" result="effect2_innerShadow_20020_3881"/></filter><filter id="i2ddoBd" width="5.961" height="9.438" x="24.297" y="16.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation=".75"/></filter><filter id="ibeiuzb" width="2.219" height="8.57" x="17.359" y="13.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation=".25"/></filter><filter id="iQadagb" width="2.219" height="9.236" x="20.351" y="10.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation=".25"/></filter><filter id="imW2MVc" width="12.094" height="6.468" x="15.766" y="17.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation=".625"/></filter><filter id="i8kr94b" width="2.751" height="1.405" x="7.205" y="18.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3881" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palms-up-together-medium-dark" /></template>
<style>
.a9en4zbqi {
  stop-color: var(--svg-color--5d312c, #5D312C);
  stop-opacity: 0;
}

.ab6ade43t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M17.64 21.659c1.115-1.167 4.344-3.313 8.344-2.563");
}

.ar-k52bcm {
  stop-color: var(--svg-color--6d4038, #6D4038);
}

.ar8b2mbjf {
  stop-color: var(--svg-color--8e6f5f, #8E6F5F);
  stop-opacity: 0;
}

.awp5c0tzb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M6.156 19.372c1.406-.416 4.92-.783 7.727 1.08");
}

.ayvqo3bhc {
  stop-color: var(--svg-color--a17f71, #A17F71);
}

.bmpatcbho {
  d: path("M6.193 10.919a1.773 1.773 0 1 1 3.547 0v.739c.259-.566.862-.91 1.565-.91c.94 0 1.7.762 1.7 1.702v.915c.313-.324.776-.51 1.294-.51A1.7 1.7 0 0 1 16 14.556v8.196c0 2.118-.656 3.498-1.021 3.98a6.32 6.32 0 0 1-6.14 3.175c-2.468-.161-3.883-1.396-4.823-2.577c-.86-1.14-1.594-3.011-1.82-3.664l.002-.011c-.276-.782-1.01-3.072-1.084-4.79v-.055a1.853 1.853 0 0 1 2.097-1.837l-.306-4.145a1.743 1.743 0 0 1 3.288-.925z");
}

.bsvlz-bbs {
  d: path("M4.515 10.961c-.96.071-1.68.907-1.61 1.867l.306 4.145c.8.105 1.439.72 1.58 1.508h.002l.785 3.974c.406-.171 1.672-.875 1.263-3.647l-.46-6.237a1.743 1.743 0 0 0-1.866-1.61");
}

.bw_o2dbrt {
  d: path("M20.851 19.565V11.33c.867-.039 1.219.618 1.219 1.22v7.015z");
}

.c3i1aoblk {
  stop-color: var(--svg-color--9c7c71, #9C7C71);
}

.cf2dfabjy {
  stop-color: var(--svg-color--a17f73, #A17F73);
  stop-opacity: 0;
}

.cr1m--qed {
  stop-color: var(--svg-color--8c605d, #8C605D);
}

.cv8923b0m {
  d: path("M17.86 21.315v-7.569c.867-.037 1.218.596 1.218 1.176v5.247z");
}

.cz-9tgook {
  stop-color: var(--svg-color--805554, #805554);
  stop-opacity: 0;
}

.dbs6_713q {
  d: path("M30.886 18.866v-.056a1.853 1.853 0 0 0-3.677-.33h-.002l-.793 4.03l3.367 1.203c.258-.719 1.03-3.085 1.105-4.847");
}

.dvi97wb5g {
  stroke: var(--svg-color--9f776f, #9F776F);
  stroke-linecap: round;
  d: path("m3.266 18.531l.944 3.996c.145.593.668 1.441 1.793 1.113");
}

.e0ueib9kf {
  stop-color: var(--svg-color--835758, #835758);
  stop-opacity: 0;
}

.e13jpvkcz {
  stop-color: var(--svg-color--94716a, #94716A);
  stop-opacity: 0;
}

.elk1kyryc {
  stop-color: var(--svg-color--734b47, #734B47);
}

.emdmbl5aq {
  stop-color: var(--svg-color--6b4540, #6B4540);
  stop-opacity: 0;
}

.f6ekcgg0m {
  stop-color: var(--svg-color--916461, #916461);
  stop-opacity: 0;
}

.fe9u10bzb {
  stop-color: var(--svg-color--673a2e, #673A2E);
}

.fjon2sbyo {
  fill: var(--svg-color--8c605d, #8C605D);
  d: path("M25.807 10.919a1.773 1.773 0 1 0-3.547 0v.739c-.259-.566-.862-.91-1.565-.91a1.7 1.7 0 0 0-1.7 1.702v.915c-.313-.324-.777-.51-1.294-.51A1.7 1.7 0 0 0 16 14.556v8.196c0 2.118.656 3.498 1.021 3.98a6.32 6.32 0 0 0 6.14 3.175c2.468-.161 3.883-1.396 4.823-2.577c.86-1.14 1.594-3.011 1.82-3.664l-.002-.011c.276-.782 1.01-3.072 1.084-4.79v-.055a1.853 1.853 0 0 0-2.097-1.837l.306-4.145a1.743 1.743 0 0 0-3.288-.925z");
}

.ft5dv1b6b {
  fill: none;
}

.fymftbbov {
  stop-color: var(--svg-color--663d3b, #663D3B);
  stop-opacity: 0;
}

.g16yvvb2b {
  d: path("m5.541 20.752l-.837-8.4a.548.548 0 1 1 1.09-.108l.74 7.607z");
}

.gh-jb31jf {
  stop-color: var(--svg-color--7b5c4e, #7B5C4E);
}

.h018b2btt {
  stop-color: var(--svg-color--7f5455, #7F5455);
  stop-opacity: 0;
}

.h8xqjrllq {
  stop-color: var(--svg-color--815e53, #815E53);
  stop-opacity: 0;
}

.ha5jxh3sd {
  stop-color: var(--svg-color--937060, #937060);
  stop-opacity: 0;
}

.hdm6t55jw {
  stop-color: var(--svg-color--72473a, #72473A);
  stop-opacity: 0;
}

.hl27kjgub {
  stop-color: var(--svg-color--8c6555, #8C6555);
}

.hu_2uf5ts {
  stop-color: var(--svg-color--6e4139, #6E4139);
  stop-opacity: 0;
}

.i-knb0djz {
  stop-color: var(--svg-color--7a3f67, #7A3F67);
}

.i2chtgb5b {
  stop-color: var(--svg-color--9a7a70, #9A7A70);
}

.ifw347z9v {
  stop-color: var(--svg-color--97786f, #97786F);
}

.iwnvb510f {
  stop-color: var(--svg-color--a17d73, #A17D73);
  stop-opacity: 0;
}

.ix-dcgb-s {
  stop-color: var(--svg-color--7c5244, #7C5244);
}

.j3224ie7b {
  stop-color: var(--svg-color--9c7c71, #9C7C71);
  stop-opacity: 0;
}

.j8vgg1bhe {
  stop-color: var(--svg-color--7b5c4e, #7B5C4E);
  stop-opacity: 0;
}

.jw00e5bpm {
  d: path("M11.305 10.749c-.94 0-1.7.612-1.7 1.551v6.456a1.7 1.7 0 0 0 2.993 1.105v-5.454c0-.422.154-.778.408-1.042v-.915a1.7 1.7 0 0 0-1.701-1.701");
}

.k3nqw-s9c {
  stop-color: var(--svg-color--764a42, #764A42);
  stop-opacity: 0;
}

.kfu40lb5u {
  fill: var(--svg-color--906361, #906361);
  d: path("M6.193 10.919a1.773 1.773 0 1 1 3.547 0v.739c.259-.566.862-.91 1.565-.91c.94 0 1.7.762 1.7 1.702v.915c.313-.324.776-.51 1.294-.51A1.7 1.7 0 0 1 16 14.556v8.196c0 2.118-.656 3.498-1.021 3.98a6.32 6.32 0 0 1-6.14 3.175c-2.468-.161-3.883-1.396-4.823-2.577c-.86-1.14-1.594-3.011-1.82-3.664l.002-.011c-.276-.782-1.01-3.072-1.084-4.79v-.055a1.853 1.853 0 0 1 2.097-1.837l-.306-4.145a1.743 1.743 0 0 1 3.288-.925z");
}

.kwe384bnh {
  d: path("M12.598 14.407c0-.94.762-1.552 1.701-1.552S16 13.617 16 14.556v4.613a1.7 1.7 0 1 1-3.402 0z");
}

.l-dot2bsz {
  stop-color: var(--svg-color--7e5252, #7E5252);
  stop-opacity: 0;
}

.l662yvdfg {
  stop-color: var(--svg-color--937060, #937060);
}

.l7yoraclh {
  stop-color: var(--svg-color--7c5c4e, #7C5C4E);
  stop-opacity: 0;
}

.lgbd-k7ej {
  d: path("M6.193 10.919a1.773 1.773 0 1 1 3.547 0v.739q-.134.286-.136.643v5.492a1.774 1.774 0 0 1-2.789.668l-.434-5.89a1.7 1.7 0 0 0-.188-.668z");
}

.lgp37cc6w {
  stop-color: var(--svg-color--916e5f, #916E5F);
  stop-opacity: 0;
}

.ln2ja-boi {
  stop-color: var(--svg-color--6f403c, #6F403C);
}

.lwjej9mny {
  d: path("M25.807 10.919a1.773 1.773 0 1 0-3.547 0v.739c-.259-.566-.862-.91-1.565-.91a1.7 1.7 0 0 0-1.7 1.702v.915c-.313-.324-.777-.51-1.294-.51A1.7 1.7 0 0 0 16 14.556v8.196c0 2.118.656 3.498 1.021 3.98a6.32 6.32 0 0 0 6.14 3.175c2.468-.161 3.883-1.396 4.823-2.577c.86-1.14 1.594-3.011 1.82-3.664l-.002-.011c.276-.782 1.01-3.072 1.084-4.79v-.055a1.853 1.853 0 0 0-2.097-1.837l.306-4.145a1.743 1.743 0 0 0-3.288-.925z");
}

.m1_xat9ce {
  stop-color: var(--svg-color--8e6f5f, #8E6F5F);
}

.m35m8eo0n {
  stop-color: var(--svg-color--956d67, #956D67);
  stop-opacity: 0;
}

.m4p32_y1a {
  stop-color: var(--svg-color--8f6662, #8F6662);
  stop-opacity: 0;
}

.m6r91ebpn {
  stop-color: var(--svg-color--815e53, #815E53);
}

.ma8dpybum {
  stop-color: var(--svg-color--906361, #906361);
  stop-opacity: 0;
}

.mjp1bebtp {
  stop-color: var(--svg-color--906361, #906361);
}

.mv47md2vd {
  stop-color: var(--svg-color--936e5f, #936E5F);
  stop-opacity: 0;
}

.njccxgbdt {
  stop-color: var(--svg-color--a17f71, #A17F71);
  stop-opacity: 0;
}

.nqfo7ub1d {
  d: path("M25.807 10.919a1.773 1.773 0 1 0-3.547 0v.739q.134.286.136.643v5.492a1.774 1.774 0 0 0 2.789.668l.434-5.89c.018-.24.084-.466.188-.668z");
}

.nuppr-bkj {
  stop-color: var(--svg-color--86625a, #86625A);
  stop-opacity: 0;
}

.o14407o9p {
  d: path("M20.695 10.749c.94 0 1.7.612 1.7 1.551v6.456a1.7 1.7 0 0 1-2.993 1.105v-5.454c0-.422-.154-.778-.408-1.042v-.915a1.7 1.7 0 0 1 1.701-1.701");
}

.olqdqsbnv {
  stop-color: var(--svg-color--956d67, #956D67);
}

.onfq42btt {
  stop-color: var(--svg-color--997a71, #997A71);
}

.onzu-erzg {
  stop-color: var(--svg-color--6c4134, #6C4134);
  stop-opacity: 0;
}

.oqor4i64r {
  stop-color: var(--svg-color--91665f, #91665F);
  stop-opacity: 0;
}

.ot1vq2b4o {
  stop-color: var(--svg-color--916461, #916461);
}

.ovri9mfqo {
  stop-color: var(--svg-color--7e5353, #7E5353);
  stop-opacity: 0;
}

.pqyz0absy {
  stop-color: var(--svg-color--997970, #997970);
}

.q_7f0ky7a {
  stop-color: var(--svg-color--94716a, #94716A);
}

.q1bvx8bxq {
  stop-color: var(--svg-color--72473a, #72473A);
}

.q6jrxcc7q {
  stop-color: var(--svg-color--916e5f, #916E5F);
}

.qaxjt3bvn {
  stop-color: var(--svg-color--936e5f, #936E5F);
}

.qhs9-n4dm {
  d: path("M19.402 14.407c0-.94-.762-1.552-1.701-1.552A1.7 1.7 0 0 0 16 14.556v4.613a1.7 1.7 0 1 0 3.402 0z");
}

.qqqcpbm9x {
  stop-color: var(--svg-color--9f776d, #9F776D);
  stop-opacity: 0;
}

.qzw1o6bdd {
  stop-color: var(--svg-color--9f776d, #9F776D);
}

.rr79kcfyw {
  stop-color: var(--svg-color--a07d73, #A07D73);
  stop-opacity: 0;
}

.rsje90ejm {
  stop-color: var(--svg-color--7c5244, #7C5244);
  stop-opacity: 0;
}

.s1vs0cc2q {
  stop-color: var(--svg-color--97786f, #97786F);
  stop-opacity: 0;
}

.soqxlnoxv {
  d: path("M27.485 10.961c.96.071 1.68.907 1.61 1.867l-.306 4.145c-.8.105-1.439.72-1.58 1.508h-.002l-.785 3.974c-.406-.171-1.672-.875-1.263-3.647l.46-6.237c.071-.96.907-1.68 1.866-1.61");
}

.svlwqobaf {
  stop-color: var(--svg-color--6c4134, #6C4134);
}

.to1afybpb {
  stop-color: var(--svg-color--997a71, #997A71);
  stop-opacity: 0;
}

.tr4d1cbsg {
  stop-color: var(--svg-color--7c5c4e, #7C5C4E);
}

.tur--yjix {
  stop-color: var(--svg-color--6d4036, #6D4036);
}

.u7z2ewbgy {
  stroke: var(--svg-color--73494a, #73494A);
  stroke-linecap: round;
  d: path("M28.258 18.565c-.188.958-1.367 4.312-1.961 5.437");
}

.ujhqir03i {
  d: path("M1.114 18.866v-.056a1.853 1.853 0 0 1 3.677-.33h.002l.772 4.012l-3.346 1.221c-.258-.719-1.03-3.085-1.105-4.847");
}

.uq71djbfa {
  stop-color: var(--svg-color--a17f73, #A17F73);
}

.v28ykubce {
  stop-color: var(--svg-color--6b4540, #6B4540);
}

.v51fq4b0y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M10.458 18.83c.27.146 1.078.425 2.14.375");
}

.vsj_tyu0c {
  stop-color: var(--svg-color--8c6555, #8C6555);
  stop-opacity: 0;
}

.vxks8w3rp {
  stop-color: var(--svg-color--91665f, #91665F);
}

.w3viicb9w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.705 18.981a2.38 2.38 0 0 0 1.751-.365");
}

.w4t3qsb6h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.817 18.835c-.065.266-.358.973-1.012 1.673");
}

.wf90xkmls {
  stop-color: var(--svg-color--6f403c, #6F403C);
  stop-opacity: 0;
}

.wgorrrbcv {
  stop-color: var(--svg-color--6c3f36, #6C3F36);
}

.wou2uab_w {
  stop-color: var(--svg-color--a07d73, #A07D73);
}

.wp3fp9bsg {
  width: 1.063px;
  height: 8.793px;
  x: 8.163px;
  y: 10.093px;
  rx: 0.531px;
}

.wq1a24byi {
  stop-color: var(--svg-color--764a42, #764A42);
}

.wt_pgmbce {
  stop-color: var(--svg-color--663d3b, #663D3B);
}

.wx8nb9blg {
  stop-color: var(--svg-color--6e4139, #6E4139);
}

.x4fcyacrp {
  stop-color: var(--svg-color--856658, #856658);
  stop-opacity: 0;
}

.x8qf5nthx {
  stop-color: var(--svg-color--7a3f67, #7A3F67);
  stop-opacity: 0;
}

.xfue8_sgp {
  stop-color: var(--svg-color--a17d73, #A17D73);
}

.xm0z3ccpp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M14.893 14.489v7.862c.011 1.226-.432 4.015-2.295 5.365");
}

.xp3pqab_w {
  stop-color: var(--svg-color--9a7a70, #9A7A70);
  stop-opacity: 0;
}

.xqdj4b39a {
  stop-color: var(--svg-color--856658, #856658);
}

.ygrzwlwzo {
  stop-color: var(--svg-color--73433c, #73433C);
}

.yo26ssb6x {
  stop-color: var(--svg-color--734b47, #734B47);
  stop-opacity: 0;
}

.yq-_nn8pm {
  stop-color: var(--svg-color--8c605d, #8C605D);
  stop-opacity: 0;
}

.yqzfmehed {
  stop-color: var(--svg-color--5d312c, #5D312C);
}

.yycb43boa {
  stop-color: var(--svg-color--86625a, #86625A);
}

</style>
