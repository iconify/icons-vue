<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iCsnECU)"><path fill="url(#i2xtBbc)" class="l1q-6fbux"/></g><g filter="url(#inAlapc)"><path stroke="url(#iUZzRld)" class="bzyf_jbhe"/></g><path class="r7u_wgbae"/><path fill="url(#iZYUcae)" class="l-tetjv6s"/><path fill="url(#imX7p3b)" class="l-tetjv6s"/><path fill="url(#imPbu3b)" class="l-tetjv6s"/><path fill="url(#in6X4hd)" class="l-tetjv6s"/><path fill="url(#iqZCt0b)" class="twib1xb4m"/><path fill="url(#iRhyRzd)" class="twib1xb4m"/><path fill="url(#i9IMA9k)" class="hj0wmxbnp"/><path fill="url(#iwdpSte)" class="hj0wmxbnp"/><path fill="url(#iHOVTqe)" class="hj0wmxbnp"/><path fill="url(#i1C2Sfb)" class="hj0wmxbnp"/><path fill="url(#ipyUHMc)" class="gt4-7hb7l"/><path fill="url(#i5QY5Cb)" class="gt4-7hb7l"/><g filter="url(#ipXIUtb)"><path fill="url(#imEE3xe)" class="ytrgwj4wy"/><path fill="url(#i26BCxl)" class="ytrgwj4wy"/><path fill="url(#inJJJBb)" class="ytrgwj4wy"/></g><g filter="url(#ioJjIRb)"><path class="fdnm0bbsl"/></g><g filter="url(#ihoHjeY)"><path fill="url(#iXfFGhe)" class="tpjw91b-f"/></g><path fill="url(#idmuyBb)" class="tpjw91b-f"/><path fill="url(#ik2i2lb)" class="tpjw91b-f"/><g filter="url(#i1HMrcb)"><path fill="url(#i9OTXzb)" class="c0i-irbov"/></g><path fill="url(#ihKxF5b)" class="c0i-irbov"/><path fill="url(#iU6zo7b)" class="c0i-irbov"/><g filter="url(#iIGd5Wd)"><path fill="url(#ilhQz6c)" class="c0vdpsbgh"/><path fill="url(#iiwJSCc)" class="c0vdpsbgh"/><path fill="url(#iKdYByd)" class="c0vdpsbgh"/></g><path fill="url(#iDM6VAd)" class="c0vdpsbgh"/><g filter="url(#iAODmRc)"><path fill="url(#iZmKZKc)" class="o7s7v2v2t"/></g><g filter="url(#iBG1I9d)"><path fill="url(#iqsfZBQ)" class="m0n71eley"/><path fill="url(#iOxlTSz)" class="m0n71eley"/></g><g filter="url(#i6VQumc)"><rect fill="url(#iE6Aiyb)" class="unfk4eblz"/></g><g filter="url(#iTrhknd)"><path stroke="url(#ik2vWOc)" class="r7p1jnbsd"/></g><g filter="url(#i238C3c)"><rect fill="url(#iQmIlQb)" class="be0jj1zgw"/></g><g filter="url(#i01gOAl)"><path stroke="url(#iYCbJld)" class="wjfbmdbuo"/></g><g filter="url(#in5pa1c)"><path class="syawyzdxd"/><path fill="url(#iYx9fwn)" class="ea3-q0vvs"/></g><defs><linearGradient id="i2xtBbc" x1="9.338" x2="20.694" y1="13.56" y2="13.56" gradientUnits="userSpaceOnUse"><stop class="g5xdx-p6a"/><stop offset="1" class="x1bwzipak"/></linearGradient><linearGradient id="iUZzRld" x1="21.4" x2="1.594" y1="11.798" y2="11.798" gradientUnits="userSpaceOnUse"><stop class="voqosiqjr"/><stop offset="1" class="vkoh1cb3h"/></linearGradient><linearGradient id="iZYUcae" x1="28.433" x2="28.433" y1="13.636" y2="15.813" gradientUnits="userSpaceOnUse"><stop class="e557sqbew"/><stop offset="1" class="p-pt5fahk"/></linearGradient><linearGradient id="imX7p3b" x1="29.029" x2="29.029" y1="21.183" y2="20.594" gradientUnits="userSpaceOnUse"><stop class="htn98bcve"/><stop offset="1" class="uiuey_7yj"/></linearGradient><linearGradient id="iqZCt0b" x1="25.87" x2="25.87" y1="17.459" y2="21.444" gradientUnits="userSpaceOnUse"><stop class="u-l9_7bkh"/><stop offset="1" class="ciszksb_r"/></linearGradient><linearGradient id="iRhyRzd" x1="25.87" x2="25.87" y1="13.473" y2="14.594" gradientUnits="userSpaceOnUse"><stop class="bqrlexbod"/><stop offset="1" class="ekv16fb4y"/></linearGradient><linearGradient id="i9IMA9k" x1="5.348" x2="5.348" y1="8.999" y2="14.28" gradientUnits="userSpaceOnUse"><stop class="nrw02kbdj"/><stop offset="1" class="cu8p_nbav"/></linearGradient><linearGradient id="iwdpSte" x1="4.913" x2="4.913" y1="14.504" y2="13.235" gradientUnits="userSpaceOnUse"><stop class="uebz5pazy"/><stop offset="1" class="wgu9qdxsw"/></linearGradient><linearGradient id="ipyUHMc" x1="3.156" x2="3.156" y1="7.866" y2="15.413" gradientUnits="userSpaceOnUse"><stop class="c6srtblcw"/><stop offset="1" class="khr-rdbks"/></linearGradient><linearGradient id="i5QY5Cb" x1="2.088" x2="3.156" y1="12.528" y2="12.528" gradientUnits="userSpaceOnUse"><stop class="j-4636inl"/><stop offset="1" class="stna4jbzo"/></linearGradient><linearGradient id="i26BCxl" x1="7.825" x2="15.7" y1="25.219" y2="18.688" gradientUnits="userSpaceOnUse"><stop offset=".495" class="b-ihjo3_v"/><stop offset="1" class="vfuxcnbdf"/></linearGradient><linearGradient id="inJJJBb" x1="16.501" x2="16.501" y1="13.473" y2="14.594" gradientUnits="userSpaceOnUse"><stop class="w11jv3m_e"/><stop offset="1" class="w1z2m7_ti"/></linearGradient><linearGradient id="iXfFGhe" x1="15.25" x2="15.25" y1="19.301" y2="23.857" gradientUnits="userSpaceOnUse"><stop class="we8c91axu"/><stop offset="1" class="t4-te6bpf"/></linearGradient><linearGradient id="idmuyBb" x1="21.919" x2="20.513" y1="20.75" y2="20.75" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ovvlnrb9b"/><stop offset="1" class="av1a4xb9a"/></linearGradient><linearGradient id="i9OTXzb" x1="10.711" x2="18.544" y1="21.063" y2="18.75" gradientUnits="userSpaceOnUse"><stop class="v7c_dlb6r"/><stop offset="1" class="x2nxhjbvs"/></linearGradient><linearGradient id="iU6zo7b" x1="10.711" x2="11.232" y1="19.5" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="nfgq6hbau"/><stop offset="1" class="t4u2nybrk"/></linearGradient><linearGradient id="ilhQz6c" x1="6.778" x2="18.388" y1="28.219" y2="28.219" gradientUnits="userSpaceOnUse"><stop class="vh3jyab5r"/><stop offset="1" class="x3t2hmtbe"/></linearGradient><linearGradient id="iiwJSCc" x1="26.224" x2="24.419" y1="27.938" y2="27.938" gradientUnits="userSpaceOnUse"><stop offset=".307" class="m4z04achx"/><stop offset="1" class="l8qf-1b8i"/></linearGradient><linearGradient id="iKdYByd" x1="26.224" x2="25.294" y1="27.938" y2="27.938" gradientUnits="userSpaceOnUse"><stop class="k175-fblc"/><stop offset="1" class="qf9yfc75k"/></linearGradient><linearGradient id="iDM6VAd" x1="6.575" x2="7.419" y1="27.385" y2="27.385" gradientUnits="userSpaceOnUse"><stop class="y_u86w_bq"/><stop offset="1" class="knx6l_bqc"/></linearGradient><linearGradient id="iZmKZKc" x1="13.979" x2="13.979" y1="26.79" y2="28.013" gradientUnits="userSpaceOnUse"><stop class="mci023eaf"/><stop offset="1" class="dzciz8fjt"/></linearGradient><linearGradient id="iqsfZBQ" x1="18.632" x2="18.632" y1="26.676" y2="28.094" gradientUnits="userSpaceOnUse"><stop class="o2r2yq75y"/><stop offset="1" class="u_2zk-b6b"/></linearGradient><linearGradient id="iE6Aiyb" x1="3.584" x2="3.584" y1="8.437" y2="14.28" gradientUnits="userSpaceOnUse"><stop offset=".416" class="xx08pfmul"/><stop offset=".627" class="qnxd2wb4e"/></linearGradient><linearGradient id="ik2vWOc" x1="25.544" x2="6.794" y1="25.906" y2="25.906" gradientUnits="userSpaceOnUse"><stop class="pn1x-fbgo"/><stop offset="1" class="izsquacnz"/></linearGradient><linearGradient id="iQmIlQb" x1="14.989" x2="12.829" y1="27.271" y2="27.271" gradientUnits="userSpaceOnUse"><stop class="s_fkwccyi"/><stop offset="1" class="cw1-tf16i"/></linearGradient><linearGradient id="iYCbJld" x1="14.544" x2="19.263" y1="20.531" y2="16.641" gradientUnits="userSpaceOnUse"><stop class="k60x0_7dv"/><stop offset=".753" class="sbiocwb9i"/></linearGradient><linearGradient id="iYx9fwn" x1="22.513" x2="22.513" y1="21.25" y2="20.609" gradientUnits="userSpaceOnUse"><stop offset=".293" class="qdosncuux"/><stop offset="1" class="u0vzjfb1t"/></linearGradient><filter id="iCsnECU" width="16.247" height="9.142" x="5.238" y="9.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.8"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.152941 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20313"/></filter><filter id="inAlapc" width="15.268" height="4.641" x="6.434" y="9.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20313" stdDeviation=".325"/></filter><filter id="ipXIUtb" width="19.834" height="12.745" x="6.584" y="13.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.709804 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20313"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.784314 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20313" result="effect2_innerShadow_18_20313"/></filter><filter id="ioJjIRb" width="2.56" height="4.37" x="20.468" y="17.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20313" stdDeviation=".2"/></filter><filter id="ihoHjeY" width="13.252" height="10.612" x="8.374" y="14.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.517647 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_20313"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_20313" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.639216 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_20313"/></filter><filter id="i1HMrcb" width="9.679" height="7.006" x="10.411" y="15.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.223529 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20313"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.235294 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20313" result="effect2_innerShadow_18_20313"/></filter><filter id="iIGd5Wd" width="20.246" height="5.435" x="6.778" y="24.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.8"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20313"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.196078 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20313" result="effect2_innerShadow_18_20313"/></filter><filter id="iAODmRc" width="2.957" height="1.523" x="12.4" y="26.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.207843 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_20313"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_20313" result="shape"/></filter><filter id="iBG1I9d" width="1.718" height="1.718" x="17.673" y="26.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.188235 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_20313"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_20313" result="shape"/></filter><filter id="i6VQumc" width="1.66" height="6.844" x="2.754" y="7.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20313" stdDeviation=".25"/></filter><filter id="iTrhknd" width="18.706" height=".8" x="7.238" y="25.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20313" stdDeviation=".15"/></filter><filter id="i238C3c" width="2.522" height=".829" x="12.768" y="26.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20313" stdDeviation=".15"/></filter><filter id="i01gOAl" width="8.725" height="5.853" x="10.988" y="16.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20313" stdDeviation=".15"/></filter><filter id="in5pa1c" width="1.96" height="3.77" x="20.926" y="17.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.921569 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20313"/></filter><radialGradient id="imPbu3b" cx="0" cy="0" r="1" gradientTransform="matrix(2.8125 0 0 1.59375 27.544 16.719)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="ngv1kkbnd"/><stop offset="1" class="p61j2ubpv"/></radialGradient><radialGradient id="in6X4hd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.64062 -.45313 0 29.529 16.75)" gradientUnits="userSpaceOnUse"><stop class="yt9ajubko"/><stop offset="1" class="yv917cyrf"/></radialGradient><radialGradient id="iHOVTqe" cx="0" cy="0" r="1" gradientTransform="matrix(3.85567 0 0 2.26295 4.05 10.957)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="bemgdwb7k"/><stop offset="1" class="zvrn08edz"/></radialGradient><radialGradient id="i1C2Sfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.76567 -.8013 0 6.15 10.974)" gradientUnits="userSpaceOnUse"><stop class="z1aaa3rcv"/><stop offset="1" class="cujzwub8z"/></radialGradient><radialGradient id="imEE3xe" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.943 -11.2696 0 16.501 14.25)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="x3swhmb1e"/><stop offset="1" class="me1jpp7ha"/></radialGradient><radialGradient id="ik2i2lb" cx="0" cy="0" r="1" gradientTransform="matrix(-.59375 .59375 -.76582 -.76582 20.762 15.094)" gradientUnits="userSpaceOnUse"><stop class="mxfq60plt"/><stop offset="1" class="he_6h0bpu"/></radialGradient><radialGradient id="ihKxF5b" cx="0" cy="0" r="1" gradientTransform="rotate(143.13 7.004 11.484)scale(.625 .88581)" gradientUnits="userSpaceOnUse"><stop class="j1qkpnxpi"/><stop offset="1" class="ockf42bpg"/></radialGradient><radialGradient id="iOxlTSz" cx="0" cy="0" r="1" gradientTransform="rotate(132.661 3.509 17.744)scale(.4462)" gradientUnits="userSpaceOnUse"><stop class="j_8ggclcv"/><stop offset="1" class="ky1usqsbu"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:video-camera" /></template>
<style>
.av1a4xb9a {
  stop-color: var(--svg-color--e5e2e9, #E5E2E9);
  stop-opacity: 0;
}

.b-ihjo3_v {
  stop-color: var(--svg-color--a59cad, #A59CAD);
}

.be0jj1zgw {
  width: 1.922px;
  height: 0.229px;
  x: 13.068px;
  y: 27.156px;
  rx: 0.115px;
}

.bemgdwb7k {
  stop-color: var(--svg-color--b4b0b8, #B4B0B8);
}

.bqrlexbod {
  stop-color: var(--svg-color--d7d7d7, #D7D7D7);
}

.bzyf_jbhe {
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M7.084 10.594h10.575c1.854 0 3.068 1.038 3.068 3.016");
}

.c0i-irbov {
  d: path("M10.71 16.998a.9.9 0 0 1 .9-.9h7.28a.9.9 0 0 1 .9.9v4.605a.9.9 0 0 1-.9.9h-7.28a.9.9 0 0 1-.9-.9z");
}

.c0vdpsbgh {
  d: path("M6.778 25.593c0-.22.18-.4.4-.4h18.646c.22 0 .4.18.4.4v1.985a2 2 0 0 1-2 2H8.778a2 2 0 0 1-2-2z");
}

.c6srtblcw {
  stop-color: var(--svg-color--58456a, #58456A);
}

.ciszksb_r {
  stop-color: var(--svg-color--ac98c1, #AC98C1);
}

.cu8p_nbav {
  stop-color: var(--svg-color--9588a2, #9588A2);
}

.cujzwub8z {
  stop-color: var(--svg-color--aba7af, #ABA7AF);
  stop-opacity: 0;
}

.cw1-tf16i {
  stop-color: var(--svg-color--cfc8d7, #CFC8D7);
  stop-opacity: 0;
}

.dzciz8fjt {
  stop-color: var(--svg-color--ab97bf, #AB97BF);
}

.e557sqbew {
  stop-color: var(--svg-color--635571, #635571);
}

.ea3-q0vvs {
  d: path("M21.126 21.085h1.36a.4.4 0 0 0 .4-.4v-2.77a.4.4 0 0 0-.4-.4h-1.36z");
}

.ekv16fb4y {
  stop-color: var(--svg-color--d7d7d7, #D7D7D7);
  stop-opacity: 0;
}

.fdnm0bbsl {
  fill: var(--svg-color--a89fb2, #A89FB2);
  d: path("M20.868 21.327h1.36a.4.4 0 0 0 .4-.4v-2.77a.4.4 0 0 0-.4-.4h-1.36z");
}

.ft5dv1b6b {
  fill: none;
}

.g5xdx-p6a {
  stop-color: var(--svg-color--5b496d, #5B496D);
}

.gt4-7hb7l {
  d: path("M2.088 8.934a1.068 1.068 0 0 1 2.135 0v5.411a1.068 1.068 0 0 1-2.135 0z");
}

.he_6h0bpu {
  stop-color: var(--svg-color--f3f0f5, #F3F0F5);
  stop-opacity: 0;
}

.hj0wmxbnp {
  d: path("M4.223 9h1.45a.8.8 0 0 1 .8.8v3.68a.8.8 0 0 1-.8.8h-1.45z");
}

.htn98bcve {
  stop-color: var(--svg-color--5c4075, #5C4075);
}

.izsquacnz {
  stop-color: var(--svg-color--624f75, #624F75);
}

.j_8ggclcv {
  stop-color: var(--svg-color--ff6384, #FF6384);
}

.j-4636inl {
  stop-color: var(--svg-color--6d6a70, #6D6A70);
}

.j1qkpnxpi {
  stop-color: var(--svg-color--6b6671, #6B6671);
}

.k175-fblc {
  stop-color: var(--svg-color--3e3a41, #3E3A41);
}

.k60x0_7dv {
  stop-color: var(--svg-color--5b4d6a, #5B4D6A);
}

.khr-rdbks {
  stop-color: var(--svg-color--3c274e, #3C274E);
}

.knx6l_bqc {
  stop-color: var(--svg-color--68587b, #68587B);
  stop-opacity: 0;
}

.ky1usqsbu {
  stop-color: var(--svg-color--ff6384, #FF6384);
  stop-opacity: 0;
}

.l-tetjv6s {
  d: path("M29.912 14.237a.6.6 0 0 0-.6-.6h-2.359v7.546h2.359a.6.6 0 0 0 .6-.6z");
}

.l1q-6fbux {
  d: path("M17.817 9.806H5.238v3.667H16.81a.5.5 0 0 1 .5.5v4.175h4.175v-4.675a3.667 3.667 0 0 0-3.668-3.667");
}

.l8qf-1b8i {
  stop-color: var(--svg-color--565558, #565558);
  stop-opacity: 0;
}

.m0n71eley {
  d: path("M19.341 27.385a.709.709 0 1 1-1.418 0a.709.709 0 0 1 1.418 0");
}

.m4z04achx {
  stop-color: var(--svg-color--565558, #565558);
}

.mci023eaf {
  stop-color: var(--svg-color--b2abb9, #B2ABB9);
}

.me1jpp7ha {
  stop-color: var(--svg-color--b7b2be, #B7B2BE);
}

.mxfq60plt {
  stop-color: var(--svg-color--f3f0f5, #F3F0F5);
}

.nfgq6hbau {
  stop-color: var(--svg-color--615470, #615470);
}

.ngv1kkbnd {
  stop-color: var(--svg-color--544b5e, #544B5E);
}

.nrw02kbdj {
  stop-color: var(--svg-color--acabad, #ACABAD);
}

.o2r2yq75y {
  stop-color: var(--svg-color--f02d55, #F02D55);
}

.o7s7v2v2t {
  d: path("M12.65 27.402c0-.338.274-.612.612-.612h1.434a.611.611 0 1 1 0 1.223h-1.434a.61.61 0 0 1-.612-.611");
}

.ockf42bpg {
  stop-color: var(--svg-color--6b6671, #6B6671);
  stop-opacity: 0;
}

.ovvlnrb9b {
  stop-color: var(--svg-color--f2edf7, #F2EDF7);
}

.p-pt5fahk {
  stop-color: var(--svg-color--635571, #635571);
  stop-opacity: 0;
}

.p61j2ubpv {
  stop-color: var(--svg-color--544b5e, #544B5E);
  stop-opacity: 0;
}

.pn1x-fbgo {
  stop-color: var(--svg-color--656566, #656566);
}

.qdosncuux {
  stop-color: var(--svg-color--dacfe5, #DACFE5);
}

.qf9yfc75k {
  stop-color: var(--svg-color--3e3a41, #3E3A41);
  stop-opacity: 0;
}

.qnxd2wb4e {
  stop-color: var(--svg-color--58565b, #58565B);
}

.r7p1jnbsd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.638 25.719h17.906");
}

.r7u_wgbae {
  fill: var(--svg-color--4c3f5b, #4C3F5B);
  d: path("M29.912 14.237a.6.6 0 0 0-.6-.6h-2.359v7.546h2.359a.6.6 0 0 0 .6-.6z");
}

.s_fkwccyi {
  stop-color: var(--svg-color--cfc8d7, #CFC8D7);
}

.sbiocwb9i {
  stop-color: var(--svg-color--68636f, #68636F);
}

.stna4jbzo {
  stop-color: var(--svg-color--4a4352, #4A4352);
  stop-opacity: 0;
}

.syawyzdxd {
  fill: var(--svg-color--eee8f6, #EEE8F6);
  d: path("M21.126 21.085h1.36a.4.4 0 0 0 .4-.4v-2.77a.4.4 0 0 0-.4-.4h-1.36z");
}

.t4-te6bpf {
  stop-color: var(--svg-color--c9b7dc, #C9B7DC);
}

.t4u2nybrk {
  stop-color: var(--svg-color--615470, #615470);
  stop-opacity: 0;
}

.tpjw91b-f {
  d: path("M9.374 15.945a1.2 1.2 0 0 1 1.2-1.2h9.352a1.2 1.2 0 0 1 1.2 1.2v6.712a1.2 1.2 0 0 1-1.2 1.2h-9.352a1.2 1.2 0 0 1-1.2-1.2z");
}

.twib1xb4m {
  d: path("M27.744 13.873a.4.4 0 0 0-.4-.4h-2.849a.5.5 0 0 0-.5.5v7.471h3.35a.4.4 0 0 0 .4-.4z");
}

.u_2zk-b6b {
  stop-color: var(--svg-color--dd1e7d, #DD1E7D);
}

.u-l9_7bkh {
  stop-color: var(--svg-color--ebe9ed, #EBE9ED);
}

.u0vzjfb1t {
  stop-color: var(--svg-color--dacfe5, #DACFE5);
  stop-opacity: 0;
}

.uebz5pazy {
  stop-color: var(--svg-color--8d73a7, #8D73A7);
}

.uiuey_7yj {
  stop-color: var(--svg-color--5c4075, #5C4075);
  stop-opacity: 0;
}

.unfk4eblz {
  width: 0.66px;
  height: 5.843px;
  x: 3.254px;
  y: 8.437px;
  rx: 0.33px;
}

.v7c_dlb6r {
  stop-color: var(--svg-color--564669, #564669);
}

.vfuxcnbdf {
  stop-color: var(--svg-color--a59cad, #A59CAD);
  stop-opacity: 0;
}

.vh3jyab5r {
  stop-color: var(--svg-color--5f4876, #5F4876);
}

.vkoh1cb3h {
  stop-color: var(--svg-color--69656e, #69656E);
  stop-opacity: 0;
}

.voqosiqjr {
  stop-color: var(--svg-color--69656e, #69656E);
}

.w11jv3m_e {
  stop-color: var(--svg-color--b3b3b4, #B3B3B4);
}

.w1z2m7_ti {
  stop-color: var(--svg-color--b3b3b4, #B3B3B4);
  stop-opacity: 0;
}

.we8c91axu {
  stop-color: var(--svg-color--e3e0e7, #E3E0E7);
}

.wgu9qdxsw {
  stop-color: var(--svg-color--8d73a7, #8D73A7);
  stop-opacity: 0;
}

.wjfbmdbuo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.438 16.64h7.525a.3.3 0 0 1 .3.3v4.654");
}

.x1bwzipak {
  stop-color: var(--svg-color--48424e, #48424E);
}

.x2nxhjbvs {
  stop-color: var(--svg-color--4c4257, #4C4257);
}

.x3swhmb1e {
  stop-color: var(--svg-color--c1bec4, #C1BEC4);
}

.x3t2hmtbe {
  stop-color: var(--svg-color--46404e, #46404E);
}

.xx08pfmul {
  stop-color: var(--svg-color--7a6e87, #7A6E87);
}

.y_u86w_bq {
  stop-color: var(--svg-color--97909f, #97909F);
}

.yt9ajubko {
  stop-color: var(--svg-color--6e6777, #6E6777);
}

.ytrgwj4wy {
  d: path("M7.084 13.973a.5.5 0 0 1 .5-.5h17.834a.5.5 0 0 1 .5.5V26.22H7.084z");
}

.yv917cyrf {
  stop-color: var(--svg-color--6e6777, #6E6777);
  stop-opacity: 0;
}

.z1aaa3rcv {
  stop-color: var(--svg-color--d3d0d6, #D3D0D6);
}

.zvrn08edz {
  stop-color: var(--svg-color--aeabb0, #AEABB0);
  stop-opacity: 0;
}

</style>
