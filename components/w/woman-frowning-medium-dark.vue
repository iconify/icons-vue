<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iNWpwOd)"><path fill="url(#ip5763d)" clip-rule="evenodd" class="yhq44jdtq"/><path fill="url(#iCA9vJB)" clip-rule="evenodd" class="yhq44jdtq"/><path fill="url(#ihbIJdb)" clip-rule="evenodd" class="yhq44jdtq"/><path fill="url(#i2zCeTy)" clip-rule="evenodd" class="yhq44jdtq"/><path fill="url(#iOmrgQO)" clip-rule="evenodd" class="yhq44jdtq"/><path fill="url(#i4lhX9t)" clip-rule="evenodd" class="yhq44jdtq"/><path fill="url(#ikQbcPb)" clip-rule="evenodd" class="yhq44jdtq"/><path fill="url(#iYwGFac)" clip-rule="evenodd" class="yhq44jdtq"/><path fill="url(#ilO4NCe)" clip-rule="evenodd" class="yhq44jdtq"/><path fill="url(#i21Cp5c)" clip-rule="evenodd" class="yhq44jdtq"/><path fill="url(#iOV9Edc)" clip-rule="evenodd" class="yhq44jdtq"/></g><path fill="url(#inLHO7c)" class="fjthbnbjy"/><path fill="url(#iSjk2Oe)" class="fjthbnbjy"/><path fill="url(#imQ2QWs)" class="fjthbnbjy"/><path fill="url(#iFoQlJC)" class="fjthbnbjy"/><path fill="url(#iQd29Fe)" class="un6fbplqu"/><g filter="url(#iYA0rcc)"><path fill="url(#iMu6UAb)" class="j-haw2bkp"/></g><g filter="url(#i2LL2Nd)"><path fill="url(#iCYkUre)" class="b7mjud5zr"/><path fill="url(#ihYe51T)" class="b7mjud5zr"/></g><g filter="url(#i5mkmdd)"><path class="lj4olxlxr"/><path fill="url(#i3T0okb)" class="r93zt1bun"/></g><g filter="url(#iLxzSOb)"><path class="wxcwu7bst"/><path fill="url(#iqMFrtd)" class="simefcbpz"/></g><g filter="url(#i1XYWwc)"><path fill="url(#iQZ01Ae)" class="q39kntb8w"/><path fill="url(#i2eCDSd)" class="q39kntb8w"/><path fill="url(#iFPUghe)" class="q39kntb8w"/><path fill="url(#i7b9Vbe)" class="q39kntb8w"/><path fill="url(#iA2retd)" class="q39kntb8w"/><path fill="url(#iIbmyrc)" class="q39kntb8w"/><path fill="url(#iKMBRle)" class="q39kntb8w"/><path fill="url(#iXcE70P)" class="q39kntb8w"/><path fill="url(#iJs9J9d)" class="q39kntb8w"/></g><path fill="url(#igZFEwd)" class="q39kntb8w"/><g filter="url(#iabQ2Yb)"><path class="qp7vgrbbf"/></g><g filter="url(#iJSIY6b)"><path class="dq6c0frlo"/><path fill="url(#iixXEtb)" class="lpcfnk57t"/><path fill="url(#iAjumDb)" class="lpcfnk57t"/><path fill="url(#i4zT4tb)" class="lpcfnk57t"/><path fill="url(#iJtJtPd)" class="lpcfnk57t"/></g><path fill="url(#ilU3Hdc)" class="lpcfnk57t"/><path fill="url(#iZ2Pzdb)" class="lpcfnk57t"/><g filter="url(#iENt00c)"><path class="jo27d9dup"/></g><g filter="url(#idleaZb)"><path class="z9_-gh6mp"/></g><path class="c2lb4b6vk"/><path fill="url(#iPGdi0y)" class="di6qrcmsq"/><path class="bd7m_kblm"/><g filter="url(#iSVmyfb)"><path class="jnmxpbbsv"/><path fill="url(#iiw4Mfb)" class="teuauvbot"/></g><g filter="url(#i48FcYb)"><path fill="url(#iWrsJyd)" class="ynan09_5d"/></g><path class="rwx39rb0s"/><path fill="url(#ic01WXb)" class="jpftbm77r"/><path class="xerzhmbmv"/><g filter="url(#iDGnzrb)"><path fill="url(#iVtjcJd)" class="q5yds9sop"/></g><g filter="url(#iJ1wd0c)"><ellipse transform="rotate(-27.914 12.416 12.725)" class="z4kepib_k"/><ellipse fill="url(#iDUycue)" transform="rotate(-27.914 12.416 12.725)" class="nknvx1bjj"/></g><g filter="url(#iBr7UAe)"><path class="b-c2abccm"/><path fill="url(#iD7PBSb)" class="t252yhqqe"/></g><g filter="url(#iVWc1Be)"><path class="u3tapml4t"/><path fill="url(#ixVQzRd)" class="giq0s3-8n"/><path fill="url(#iR8s9Fb)" class="giq0s3-8n"/></g><g filter="url(#iFUIWje)"><path stroke="url(#iDBFcEe)" class="hlazmzbry"/></g><g filter="url(#iSuWHXb)"><path clip-rule="evenodd" class="unfkyktie"/></g><g filter="url(#ifndBLK)"><path class="c1r04407f"/></g><g filter="url(#ijuAV6d)"><path clip-rule="evenodd" class="f8yapwbjm"/></g><g filter="url(#iJQhcpq)"><path class="f5b-xgb1w"/></g><g filter="url(#iCSdtvc)"><path stroke="url(#iZIWE3d)" clip-rule="evenodd" class="gkocxuxzu"/><path stroke="url(#iCi7F0b)" clip-rule="evenodd" class="gkocxuxzu"/></g><path clip-rule="evenodd" class="fq8kf_e-o"/><g filter="url(#ii6Diub)"><path class="myj9jf3ep"/></g><defs><radialGradient id="iCA9vJB" cx="0" cy="0" r="1" gradientTransform="matrix(-.81504 6.15812 -7.69275 -1.01815 15.323 17.039)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ihbIJdb" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.1 10.461)scale(4.69703 6.17153)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i2zCeTy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.76592 2.3093 -1.77323 -1.35598 9.187 13.96)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iOmrgQO" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74331 2.85264 -2.00944 -1.228 9.798 11.22)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i4lhX9t" cx="0" cy="0" r="1" gradientTransform="matrix(1.8565 3.53186 -4.90276 2.5771 10.976 2.776)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ikQbcPb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.94693 1.94707 -2.721 -2.7208 23.609 5.583)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iYwGFac" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 12.045 8.099)scale(2.59355 5.40865)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="ilO4NCe" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 11.475 10.107)scale(3.9205 4.99413)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="i21Cp5c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.22167 -3.57981 2.83142 -.96627 22.123 9.223)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iOV9Edc" cx="0" cy="0" r="1" gradientTransform="matrix(2.0314 .21308 -.34526 3.29145 7.434 12.462)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="inLHO7c" cx="0" cy="0" r="1" gradientTransform="rotate(167.548 9.337 14.198)scale(15.0733 14.5482)" gradientUnits="userSpaceOnUse"><stop class="o569z9a1w"/><stop offset=".514" class="tir3d5q-g"/><stop offset=".928" class="bqsidlj4b"/></radialGradient><radialGradient id="imQ2QWs" cx="0" cy="0" r="1" gradientTransform="matrix(-14.0601 0 0 -10.457 19.437 29.349)" gradientUnits="userSpaceOnUse"><stop offset=".829" class="sw5cssher"/><stop offset="1" class="v_je8db5f"/></radialGradient><radialGradient id="iFoQlJC" cx="0" cy="0" r="1" gradientTransform="rotate(170.242 5.668 10.697)scale(6.21871 3.13729)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="fff_vbcwe"/><stop offset="1" class="vp-la-38w"/></radialGradient><radialGradient id="iQd29Fe" cx="0" cy="0" r="1" gradientTransform="matrix(3.07812 3.1875 -4.19625 4.05226 14.22 20.985)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="sxswplbur"/><stop offset=".866" class="rz4ekible"/></radialGradient><radialGradient id="iCYkUre" cx="0" cy="0" r="1" gradientTransform="matrix(3.36206 -1.52821 1.86588 4.10492 21.187 14.254)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="ihYe51T" cx="0" cy="0" r="1" gradientTransform="rotate(29.271 -10.519 48.926)scale(2.03739 .576)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="i3T0okb" cx="0" cy="0" r="1" gradientTransform="matrix(2.03947 -.1517 .1186 1.5943 21.662 13.813)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iqMFrtd" cx="0" cy="0" r="1" gradientTransform="rotate(-180 4.758 6.83)scale(1.42633)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iQZ01Ae" cx="0" cy="0" r="1" gradientTransform="matrix(-8.78464 4.05089 -5.42204 -11.75807 19.592 12.935)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="i2eCDSd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.945 1.29589 -.90243 -2.05084 18.392 14.088)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iFPUghe" cx="0" cy="0" r="1" gradientTransform="matrix(1.7413 -5.30619 6.73257 2.20939 12.81 21.725)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="i7b9Vbe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73527 9.95926 -12.44895 -2.16906 17.112 12.373)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ermiffb8a"/><stop offset="1" class="d5lrpr21j"/></radialGradient><radialGradient id="iA2retd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.46739 -8.51274 0 15.377 13.462)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="plx9t1yez"/><stop offset="1" class="tcn1mccqj"/></radialGradient><radialGradient id="iIbmyrc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.345 8.52)scale(9.50567 16.3658)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iKMBRle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.55439 1.90766 0 18.839 12.37)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iXcE70P" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.77286 2.03182 0 12.925 12.061)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iJs9J9d" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 5.26 11.362)scale(4.51419 3.61209)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="igZFEwd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73608 0 0 -8.70628 22.613 14.379)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iixXEtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.61532 -2.76092 .8509 -.18964 16.79 15.36)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iJtJtPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05277 0 0 -.29432 16.466 15.647)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iZ2Pzdb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85215 1.27157 -1.52823 -2.226 16.24 14.843)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="iPGdi0y" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09588 -1.74311 0 18.678 12.854)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="cqpaw5wjj"/></radialGradient><radialGradient id="iiw4Mfb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.36 1.986)scale(.51097 .70347)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ic01WXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09588 -1.74312 0 12.783 12.854)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="cqpaw5wjj"/></radialGradient><radialGradient id="iDUycue" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.671 .474)scale(.66743 .80227)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iD7PBSb" cx="0" cy="0" r="1" gradientTransform="rotate(-64.926 11.915 -1.354)scale(4.10923 2.13135)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ixVQzRd" cx="0" cy="0" r="1" gradientTransform="rotate(116.702 8.142 7.164)scale(6.50047 10.9231)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iR8s9Fb" cx="0" cy="0" r="1" gradientTransform="matrix(-.29092 1.80796 -4.0595 -.6532 15.848 3.598)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iZIWE3d" cx="0" cy="0" r="1" gradientTransform="rotate(-74.859 20.008 -1.537)scale(.68794 1.67216)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="n684hlzbl"/><stop offset=".581" class="kg35u-zig"/></radialGradient><radialGradient id="iCi7F0b" cx="0" cy="0" r="1" gradientTransform="matrix(.53516 -.58203 .42042 .38656 14.176 18.405)" gradientUnits="userSpaceOnUse"><stop offset=".065" class="n684hlzbl"/><stop offset=".571" class="kg35u-zig"/></radialGradient><filter id="iNWpwOd" width="20.535" height="21.036" x="5.587" y="1.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21898"/></filter><filter id="iYA0rcc" width="4.497" height="4.347" x="7.228" y="11.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21898"/></filter><filter id="i2LL2Nd" width="4.347" height="4.597" x="20.077" y="11.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21898"/></filter><filter id="i5mkmdd" width="3.902" height="3.902" x="20.3" y="11.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".25"/></filter><filter id="iLxzSOb" width="3.402" height="3.402" x="7.726" y="11.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".125"/></filter><filter id="i1XYWwc" width="13.765" height="15.092" x="8.848" y="7.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21898"/></filter><filter id="iabQ2Yb" width="3.536" height="4.622" x="13.743" y="12.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".25"/></filter><filter id="iJSIY6b" width="3.036" height="4.122" x="14.212" y="12.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".125"/></filter><filter id="iENt00c" width="3.984" height="1.736" x="17.073" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21898"/></filter><filter id="idleaZb" width="3.984" height="1.736" x="10.404" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21898"/></filter><filter id="iSVmyfb" width=".993" height=".87" x="17.721" y="12.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".05"/></filter><filter id="i48FcYb" width="1.064" height="1.093" x="18.891" y="12.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".1"/></filter><filter id="iDGnzrb" width="1.192" height="1.265" x="12.889" y="12.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".1"/></filter><filter id="iJ1wd0c" width="1.163" height=".881" x="11.835" y="12.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".05"/></filter><filter id="iBr7UAe" width="6.208" height="6.516" x="6.933" y="4.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21898"/><feGaussianBlur result="effect2_foregroundBlur_3987_21898" stdDeviation=".375"/></filter><filter id="iVWc1Be" width="12.865" height="8.485" x="10.837" y="2.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21898"/><feGaussianBlur result="effect2_foregroundBlur_3987_21898" stdDeviation=".375"/></filter><filter id="iFUIWje" width="1.336" height="2.909" x="11.525" y="4.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".1"/></filter><filter id="iSuWHXb" width="3.18" height="1.857" x="10.74" y="9.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21898"/></filter><filter id="ifndBLK" width="2.83" height="1.507" x="10.815" y="9.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".1"/></filter><filter id="ijuAV6d" width="3.18" height="1.857" x="17.74" y="9.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21898"/></filter><filter id="iJQhcpq" width="2.83" height="1.507" x="17.815" y="9.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".1"/></filter><filter id="iCSdtvc" width="3.791" height="1.496" x="13.835" y="17.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".1"/></filter><filter id="ii6Diub" width="8.107" height="4.32" x="15.037" y="5.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21898" stdDeviation=".5"/></filter><linearGradient id="ip5763d" x1="22.07" x2="12.878" y1="4.27" y2="21.295" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="iSjk2Oe" x1="15.73" x2="15.73" y1="30.329" y2="29.485" gradientUnits="userSpaceOnUse"><stop class="h094d73xa"/><stop offset="1" class="pt83qis4i"/></linearGradient><linearGradient id="iMu6UAb" x1="7.297" x2="8.972" y1="13.779" y2="13.779" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iAjumDb" x1="14.462" x2="15.73" y1="15.459" y2="15.459" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="i4zT4tb" x1="15.73" x2="15.73" y1="16.538" y2="15.714" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="ilU3Hdc" x1="15.836" x2="15.836" y1="16.503" y2="16.315" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="iWrsJyd" x1="19.728" x2="19.305" y1="12.927" y2="13.188" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVtjcJd" x1="13.788" x2="13.364" y1="12.927" y2="13.188" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDBFcEe" x1="11.825" x2="12.561" y1="5.289" y2="7.009" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-frowning-medium-dark" /></template>
<style>
.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b-c2abccm {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M9.12 5.538c.838-.747 2.048-.755 2.728-.634l.543 1.743c-.347-.053-.657.068-.917.317c-.616 1.703-2.732 2.641-3.713 2.898c-.204-2.015-.09-3.034 1.358-4.324");
}

.b7mjud5zr {
  d: path("M22.25 15.835a2.173 2.173 0 1 0 0-4.347a2.173 2.173 0 0 0 0 4.347");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bd7m_kblm {
  fill: var(--svg-color--000, #000);
  d: path("M17.99 13.416c0-.384.307-.69.69-.69a.688.688 0 0 1 .614 1.007h-1.222a.6.6 0 0 1-.082-.317");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bqsidlj4b {
  stop-color: var(--svg-color--5e4d84, #5E4D84);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c1r04407f {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.115 11.048c.52.01 1.605-.188 2.23-.906");
}

.c2lb4b6vk {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.96 11.843c.882 0 1.627.608 1.83 1.43a.37.37 0 0 1-.362.46h-3.013a.31.31 0 0 1-.307-.367a1.89 1.89 0 0 1 1.852-1.523");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqpaw5wjj {
  stop-color: var(--svg-color--664b41, #664B41);
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d5lrpr21j {
  stop-color: var(--svg-color--793e68, #793E68);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.di6qrcmsq {
  d: path("M18.68 12.21a1.206 1.206 0 0 1 1.162 1.523h-2.329a1.2 1.2 0 0 1-.044-.317a1.21 1.21 0 0 1 1.211-1.206");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dq6c0frlo {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.214 13.173l-.718 2.296a.728.728 0 0 0 .703.945h1.062a.73.73 0 0 0 .704-.945l-.718-2.296c-.154-.508-.872-.508-1.033 0");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.ermiffb8a {
  stop-color: var(--svg-color--793e68, #793E68);
  stop-opacity: 0;
}

.f5b-xgb1w {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M20.346 11.048c-.521.01-1.606-.188-2.231-.906");
}

.f8yapwbjm {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("M17.869 9.859a.375.375 0 0 0-.037.529c.37.426.864.685 1.319.836s.898.205 1.202.199a.375.375 0 0 0-.015-.75a3 3 0 0 1-.95-.16c-.375-.125-.736-.325-.99-.617a.375.375 0 0 0-.53-.037");
}

.fff_vbcwe {
  stop-color: var(--svg-color--402a66, #402A66);
}

.fjthbnbjy {
  d: path("M25.645 30.001v-.387c0-5.346-4.436-9.691-9.915-9.691s-9.915 4.335-9.915 9.691v.387z");
}

.fq8kf_e-o {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M16.912 18.301c-.958-.557-1.98-.231-2.36-.002a.275.275 0 1 1-.284-.471c.484-.291 1.729-.695 2.92-.002a.275.275 0 0 1-.276.475");
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.giq0s3-8n {
  d: path("M15.344 3.264c-1.97-.234-3.297 1.25-3.757 1.73c2.083 4.89 5.281 4.425 8.83 4.03c2.124-.236 2.354.732 2.535 1.2c-.588-5.479-4.063-6.538-7.608-6.96");
}

.gkocxuxzu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.912 18.301c-.958-.557-1.98-.231-2.36-.002a.275.275 0 1 1-.284-.471c.484-.291 1.729-.695 2.92-.002a.275.275 0 0 1-.276.475Z");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h094d73xa {
  stop-color: var(--svg-color--5f4e9d, #5F4E9D);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hlazmzbry {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.825 4.825c.031.328.317 1.562.736 2.309");
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.j-haw2bkp {
  d: path("M9.401 15.835a2.173 2.173 0 1 0 0-4.347a2.173 2.173 0 0 0 0 4.347");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jnmxpbbsv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.592 12.465c.086.115-.094.255-.298.408s-.356.26-.442.145c-.085-.115.01-.332.215-.485c.204-.152.439-.183.525-.068");
}

.jo27d9dup {
  fill: var(--svg-color--383034, #383034);
  d: path("M17.273 12.892c.358-.63.903-1.128 2.076-1.128c.514 0 1.01.142 1.45.498c.363.293.314.669.033.81l-.751.428c-.88-.285-1.854-.323-2.808-.608");
}

.jpftbm77r {
  d: path("M12.78 12.21a1.206 1.206 0 0 0-1.162 1.523h2.33q.042-.155.043-.317a1.214 1.214 0 0 0-1.21-1.206");
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kg35u-zig {
  stop-color: var(--svg-color--90696a, #90696A);
  stop-opacity: 0;
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj4olxlxr {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M22.25 15.112a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lpcfnk57t {
  d: path("m15.214 13.173l-.718 2.296a.728.728 0 0 0 .703.945h1.062a.73.73 0 0 0 .704-.945l-.718-2.296c-.154-.508-.872-.508-1.033 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.myj9jf3ep {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.811 8.099l-1.767.325a.853.853 0 1 1-.155-1.692h2.902c1.716 0 2.284 1.73 2.353 2.32a3.9 3.9 0 0 0-3.333-.953");
}

.n684hlzbl {
  stop-color: var(--svg-color--90696a, #90696A);
}

.nknvx1bjj {
  cx: 12.416px;
  cy: 12.725px;
  rx: 0.526px;
  ry: 0.266px;
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o569z9a1w {
  stop-color: var(--svg-color--917ccd, #917CCD);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plx9t1yez {
  stop-color: var(--svg-color--885485, #885485);
  stop-opacity: 0;
}

.pt83qis4i {
  stop-color: var(--svg-color--5f4e9d, #5F4E9D);
  stop-opacity: 0;
}

.q39kntb8w {
  d: path("M8.859 11.955h.016l-.013-.358l-.014-.413c.027-1.282.775-1.778 1.094-1.944q.031-.01.07-.027l.068-.028a3.1 3.1 0 0 0 1.607-1.667l.111-.262a.356.356 0 0 1 .623-.069a5.22 5.22 0 0 0 4.308 2.26h4.35c.243 0 1.461.118 1.534 1.8l-.16 4.15c-.167 3.786-3.123 6.328-6.732 6.328s-6.564-2.542-6.73-6.328z");
}

.q5yds9sop {
  d: path("M13.881 13.274c0-.39-.316-.65-.402-.728l-.39.377l.24.488z");
}

.qp7vgrbbf {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.2 13.36l-.923 2.296a.728.728 0 0 0 .703.945h1.062a.73.73 0 0 0 .703-.945l-.718-2.296c-.153-.508-.666-.508-.827 0");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r93zt1bun {
  d: path("M22.25 15.112a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rwx39rb0s {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.5 11.843c-.881 0-1.627.608-1.83 1.43a.37.37 0 0 0 .362.46h3.014a.31.31 0 0 0 .307-.367a1.89 1.89 0 0 0-1.852-1.523");
}

.rz4ekible {
  stop-color: var(--svg-color--936962, #936962);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.simefcbpz {
  d: path("M9.427 15.112a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sw5cssher {
  stop-color: var(--svg-color--6d5b88, #6D5B88);
  stop-opacity: 0;
}

.sxswplbur {
  stop-color: var(--svg-color--693844, #693844);
}

.t252yhqqe {
  d: path("M9.12 5.538c.838-.747 2.048-.755 2.728-.634l.543 1.743c-.347-.053-.657.068-.917.317c-.616 1.703-2.732 2.641-3.713 2.898c-.204-2.015-.09-3.034 1.358-4.324");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tcn1mccqj {
  stop-color: var(--svg-color--885485, #885485);
}

.teuauvbot {
  d: path("M18.592 12.465c.086.115-.094.255-.298.408s-.356.26-.442.145c-.085-.115.01-.332.215-.485c.204-.152.439-.183.525-.068");
}

.tir3d5q-g {
  stop-color: var(--svg-color--715cac, #715CAC);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u3tapml4t {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.344 3.264c-1.97-.234-3.297 1.25-3.757 1.73c2.083 4.89 5.281 4.425 8.83 4.03c2.124-.236 2.354.732 2.535 1.2c-.588-5.479-4.063-6.538-7.608-6.96");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.un6fbplqu {
  d: path("M15.73 23.594c-1.43 0-2.587-1.067-2.587-2.386v-2.821c0-1.32 1.157-2.387 2.587-2.387s2.587 1.067 2.587 2.387v2.82c0 1.32-1.156 2.387-2.587 2.387");
}

.unfkyktie {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("M13.592 9.859a.375.375 0 0 1 .036.529c-.37.426-.864.685-1.318.836a3.8 3.8 0 0 1-1.203.199a.375.375 0 1 1 .016-.75a3 3 0 0 0 .95-.16c.374-.125.735-.325.99-.617a.375.375 0 0 1 .528-.037");
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.v_je8db5f {
  stop-color: var(--svg-color--6d5b88, #6D5B88);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vp-la-38w {
  stop-color: var(--svg-color--402a66, #402A66);
  stop-opacity: 0;
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wxcwu7bst {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M9.427 15.112a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xerzhmbmv {
  fill: var(--svg-color--000, #000);
  d: path("M13.47 13.416a.69.69 0 0 0-.69-.69a.688.688 0 0 0-.614 1.007h1.222a.7.7 0 0 0 .082-.317");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yhq44jdtq {
  fill-rule: evenodd;
  d: path("M25.436 15.565a4.4 4.4 0 0 0 .437-1.927a4.4 4.4 0 0 0-.363-1.764h.007a4.3 4.3 0 0 0-.38-.693l-.002-.004a4.4 4.4 0 0 1-.711-2.392v-.014a4.457 4.457 0 0 0-4.456-4.456a.73.73 0 0 1-.615-.314a4.47 4.47 0 0 0-3.623-1.86c-1.49 0-2.816.739-3.622 1.86a.76.76 0 0 1-.616.314l-.114.002A4.457 4.457 0 0 0 7.036 8.77v.014a4.4 4.4 0 0 1-.71 2.392l-.004.005a4.46 4.46 0 0 0-.735 2.456c0 .697.164 1.34.438 1.927a.7.7 0 0 1 0 .615a4.4 4.4 0 0 0-.438 1.9a4.34 4.34 0 0 0 4.347 4.347h11.592a4.34 4.34 0 0 0 4.347-4.347c0-.683-.164-1.326-.437-1.9a.7.7 0 0 1 0-.615m-16.56-3.61h-.017l1.619 3.182c.166 3.786 1.644 0 5.252 0s5.182 4.214 5.348.428l1.535-4.318c-.073-1.682-1.291-1.8-1.535-1.8H16.73a5.22 5.22 0 0 1-4.308-2.26a.356.356 0 0 0-.623.069l-.11.262a3.1 3.1 0 0 1-1.608 1.667l-.069.028l-.07.027c-.318.166-1.066.662-1.093 1.944l.013.413z");
}

.ynan09_5d {
  d: path("M19.754 13.257a1.14 1.14 0 0 0-.312-.625l-.351.385l.158.308z");
}

.z4kepib_k {
  cx: 12.416px;
  cy: 12.725px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.526px;
  ry: 0.266px;
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z9_-gh6mp {
  fill: var(--svg-color--35292e, #35292E);
  d: path("M14.188 12.892c-.359-.63-.904-1.128-2.077-1.128c-.513 0-1.009.142-1.449.498c-.363.293-.314.669-.033.81l.751.428c.88-.285 1.854-.323 2.808-.608");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

</style>
