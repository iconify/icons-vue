<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iP5uS0c)"><path fill="url(#iBLebJe)" class="vvxgj6bpi"/><path fill="url(#i6ataMe)" class="vvxgj6bpi"/></g><path fill="url(#iYqpaEd)" class="vvxgj6bpi"/><path fill="url(#ixAyHpb)" class="vvxgj6bpi"/><g filter="url(#iLvpgJe)"><path fill="url(#iJ5LWAd)" class="ig-n-yctu"/><path fill="url(#iLMuarb)" class="ig-n-yctu"/></g><g filter="url(#iv0EjQX)"><path fill="url(#ixDQBGd)" class="d3j_vxdji"/><path fill="url(#iBJY7nI)" class="d3j_vxdji"/></g><circle fill="url(#ifvx0ie)" class="nserplb1x"/><g filter="url(#i7kqt7t)" class="mc2zb0bvp"><circle class="pycm4bbqu"/></g><circle fill="url(#ipJ8xLb)" class="f-z1ozvrb"/><circle fill="url(#iBCB6Ge)" class="f-z1ozvrb"/><g filter="url(#iHoH5ie)"><circle fill="url(#i1u3qEb)" class="i4ojxgbvw"/></g><g filter="url(#ihRNkcL)"><circle fill="url(#i3y1Erb)" class="m__z0mykh"/></g><path class="zjt_glb7d"/><path fill="url(#iVExysb)" class="q6gx3quyt"/><path fill="url(#i1TAJsb)" class="q6gx3quyt"/><g filter="url(#i2NnhXb)"><rect fill="url(#ilf37lc)" class="j8z-42s7e"/></g><rect fill="url(#i6UeCiQ)" class="j8z-42s7e"/><g filter="url(#iFcHV5b)"><path fill="url(#iE0NOqb)" class="wvp0mabjb"/></g><g filter="url(#iJVmtYb)"><path fill="url(#iIHX4Lc)" class="xnnyhy2ap"/></g><g filter="url(#izMZFTb)"><path fill="url(#ier5e4d)" class="q7vyx3bsm"/><path fill="url(#i3ixksc)" class="q7vyx3bsm"/><path fill="url(#iHdTNvb)" class="q7vyx3bsm"/><path fill="url(#ixKDCsd)" class="q7vyx3bsm"/></g><g filter="url(#iJ39XRd)"><path fill="url(#iXyFuzc)" class="z_1jymb2l"/><path fill="url(#iFgKxqb)" class="z_1jymb2l"/></g><g filter="url(#iNsECdd)"><circle fill="url(#i9rEhpc)" class="l_flc0gwk"/></g><g filter="url(#i40LAId)"><path class="tdq-64bsc"/></g><g filter="url(#iL3Z0Xd)"><path stroke="url(#iJAuGCd)" class="gti-w2qfb"/></g><g filter="url(#iYEXEqd)"><path class="abk3uwbod"/></g><g filter="url(#iNYAsMc)"><path stroke="url(#i42yLGe)" class="e2arxx8zo"/></g><path stroke="url(#ihcxsrb)" class="df2hh16wk"/><g filter="url(#injekXc)"><path stroke="url(#i6yIr7b)" class="lplgdxbdh"/></g><path stroke="url(#iXcWuad)" class="q_3fqdbeg"/><g filter="url(#iIPKADc)"><path stroke="url(#iHoQ0cd)" class="f1zc5ekne"/></g><g filter="url(#iF7nptG)"><path class="fmviwlb7j"/></g><path class="gh97iwbkc"/><path fill="url(#ilVhyqe)" class="bnm8uzbww"/><path fill="url(#iquqWJe)" class="bnm8uzbww"/><path fill="url(#iMV0zge)" class="bnm8uzbww"/><g filter="url(#iK09Aks)"><path stroke="url(#iUBlM2a)" class="sr4z9jbkj"/></g><path class="eqqtw8bje"/><g filter="url(#i9wp12L)"><path fill="url(#iswkPyc)" class="j9i9zyb7u"/></g><g filter="url(#i57ljOe)"><path class="q4bd_uhlb"/><path fill="url(#i9zugJb)" class="vod-dschj"/></g><g filter="url(#imulFNc)"><path class="lt5krob8g"/></g><g filter="url(#iA3y0je)"><path fill="url(#iuq5v6b)" class="ievfp3btw"/></g><g filter="url(#i7Ubdgb)"><path fill="url(#icjDSMp)" class="r7917jlmh"/></g><g filter="url(#iq5YdJb)"><path fill="url(#iCceSye)" class="vf_3ecbae"/><path fill="url(#i7pFytd)" class="vf_3ecbae"/></g><defs><radialGradient id="iBLebJe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -12.0938 23.481 28.313)" gradientUnits="userSpaceOnUse"><stop class="oof-goujs"/><stop offset=".832" class="y-z81-bua"/></radialGradient><radialGradient id="i6ataMe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.16617 -7.1847 8.98984 -5.2129 23.982 28.248)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="r-5ctobwv"/><stop offset="1" class="b2cgmuy3t"/></radialGradient><radialGradient id="iYqpaEd" cx="0" cy="0" r="1" gradientTransform="rotate(155.64 5.706 11.329)scale(10.8979 4.51152)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="rc0rszb3u"/><stop offset="1" class="k4lo-hb9q"/></radialGradient><radialGradient id="ixAyHpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.5924 15.2389 0 16 30.313)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="xxerewdbl"/><stop offset=".977" class="rjclg2bzq"/></radialGradient><radialGradient id="iJ5LWAd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.56244 7.87504 -7.63171 -5.39056 25.318 13.875)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="mzkqj9diq"/><stop offset="1" class="pi95o6_xg"/><stop offset="1" class="gxmoj2a2w"/></radialGradient><radialGradient id="iLMuarb" cx="0" cy="0" r="1" gradientTransform="rotate(147.139 10.128 11.737)scale(2.75089 2.7814)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="ixDQBGd" cx="0" cy="0" r="1" gradientTransform="rotate(152.281 3.899 10.46)scale(4.87131 9.06872)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="rw8jbub0d"/><stop offset="1" class="hc0-o8aul"/></radialGradient><radialGradient id="iBJY7nI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82006 6.3586 -4.4708 -1.2797 9.243 10.892)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="dz7lmqc8k"/><stop offset="1" class="ou1bzhb5f"/></radialGradient><radialGradient id="ifvx0ie" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.223 17.133)scale(2.88068)" gradientUnits="userSpaceOnUse"><stop class="m2q2vh2sa"/><stop offset="1" class="he4p8yb1z"/></radialGradient><radialGradient id="ipJ8xLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7615 .75741 -.7977 -.802 23.307 14.178)" gradientUnits="userSpaceOnUse"><stop class="k377ck8jo"/><stop offset="1" class="x101rabpv"/></radialGradient><radialGradient id="iBCB6Ge" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.592 21.027)scale(2.34213)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="o4bfrybwl"/><stop offset="1" class="k3si3xnlp"/></radialGradient><radialGradient id="i1u3qEb" cx="0" cy="0" r="1" gradientTransform="matrix(.69531 0 0 .82031 21.666 14.584)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="k87xpnbmx"/><stop offset="1" class="nk_-g356a"/></radialGradient><radialGradient id="i3y1Erb" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 13.942)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cibck0b0g"/><stop offset=".902" class="ghvr_e1bi"/></radialGradient><radialGradient id="iVExysb" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.189 14.596)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="lpu_4e3zg"/><stop offset="1" class="bk2ujv-xu"/></radialGradient><radialGradient id="i1TAJsb" cx="0" cy="0" r="1" gradientTransform="matrix(1.38245 2.7263 -8.86547 4.4955 14.13 20.305)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="srb0dp7as"/><stop offset="1" class="n_0ffbr5z"/></radialGradient><radialGradient id="ilf37lc" cx="0" cy="0" r="1" gradientTransform="rotate(174.247 9.378 7.946)scale(6.06562 7.0411)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="c_0yu_b0g"/><stop offset="1" class="apsq0tbar"/></radialGradient><radialGradient id="i6UeCiQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.0892 -11.3554 0 16 10.975)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="cmnx7-cem"/><stop offset="1" class="ssxx1yhos"/></radialGradient><radialGradient id="iE0NOqb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03943 7.79525 -3.98358 .53118 11.325 6.861)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="ou2-vlbjv"/><stop offset="1" class="nz0j9tb8x"/></radialGradient><radialGradient id="iIHX4Lc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49705 3.59654 -3.30365 -2.2937 21.297 10.477)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="v8wjp2hus"/><stop offset="1" class="u3cxmmb4z"/></radialGradient><radialGradient id="ier5e4d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37502 5.34375 -6.41397 -1.6504 17.88 4.74)" gradientUnits="userSpaceOnUse"><stop class="plx67l2yn"/><stop offset=".722" class="p0ctn-b9v"/></radialGradient><radialGradient id="i3ixksc" cx="0" cy="0" r="1" gradientTransform="matrix(2.06252 -1.68749 2.8938 3.53691 10.819 10.187)" gradientUnits="userSpaceOnUse"><stop class="e2w8wgkwd"/><stop offset="1" class="bz501rp8q"/></radialGradient><radialGradient id="iHdTNvb" cx="0" cy="0" r="1" gradientTransform="rotate(-144.811 12.391 1.866)scale(2.98253 5.11462)" gradientUnits="userSpaceOnUse"><stop class="uwosa3bcc"/><stop offset="1" class="eekdaj38l"/></radialGradient><radialGradient id="ixKDCsd" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -1.96875 .58437 .85337 11.224 6.752)" gradientUnits="userSpaceOnUse"><stop class="aar72_bag"/><stop offset="1" class="a5m4qeq5q"/></radialGradient><radialGradient id="iXyFuzc" cx="0" cy="0" r="1" gradientTransform="rotate(-58.443 17.078 -10.404)scale(4.65751 13.5396)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="unym9abbi"/><stop offset="1" class="l8w71gbix"/></radialGradient><radialGradient id="iFgKxqb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36877 -1.375 .63373 -1.09174 18.662 9.522)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="zedeq5w8l"/><stop offset="1" class="szcfc8bri"/></radialGradient><radialGradient id="i9rEhpc" cx="0" cy="0" r="1" gradientTransform="rotate(-62.753 18.25 -4.13)scale(1.90544 2.10594)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cltcdpbpn"/><stop offset=".902" class="av0tm7_uc"/></radialGradient><radialGradient id="ihcxsrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.578)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="g9mjpo7pf"/><stop offset="1" class="o2l1ytrej"/></radialGradient><radialGradient id="iXcWuad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.578)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="g9mjpo7pf"/><stop offset="1" class="o2l1ytrej"/></radialGradient><radialGradient id="iquqWJe" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 16.758)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ay0sr9bls"/><stop offset="1" class="ytd3ey6so"/></radialGradient><radialGradient id="iMV0zge" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.542 15.959)" gradientUnits="userSpaceOnUse"><stop class="o5qf-ej6a"/><stop offset="1" class="ilt16x1zy"/></radialGradient><radialGradient id="iUBlM2a" cx="0" cy="0" r="1" gradientTransform="rotate(-62.526 22.567 -3.115)scale(.44028 1.97794)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="qdxirobsy"/><stop offset="1" class="fjwf4gbrh"/></radialGradient><radialGradient id="i9zugJb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.468 8.78 2.243)scale(3.17497 1.5867)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="iclvvachy"/><stop offset="1" class="bc2wedbnb"/></radialGradient><radialGradient id="iuq5v6b" cx="0" cy="0" r="1" gradientTransform="matrix(5.87065 -6.2812 5.44456 5.0887 18.354 9.816)" gradientUnits="userSpaceOnUse"><stop class="k3jnt_bvt"/><stop offset="1" class="khh_otzli"/></radialGradient><radialGradient id="iCceSye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 11.1 6.347)" gradientUnits="userSpaceOnUse"><stop class="b5e_facvp"/><stop offset="1" class="wj0_vcbzm"/></radialGradient><radialGradient id="i7pFytd" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.402 9.826)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="hfhn00bef"/><stop offset="1" class="ws75vab8k"/></radialGradient><filter id="iP5uS0c" width="21.451" height="8.965" x="5.649" y="20.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.27451 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24263"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.376471 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24263" result="effect2_innerShadow_3987_24263"/></filter><filter id="iLvpgJe" width="8.434" height="11.989" x="16.543" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24263"/></filter><filter id="iv0EjQX" width="8.784" height="12.039" x="7.173" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.0627451 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24263"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.0156863 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24263" result="effect2_innerShadow_3987_24263"/></filter><filter id="i7kqt7t" width="2.986" height="2.986" x="9.111" y="12.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".1"/></filter><filter id="iHoH5ie" width="2.986" height="2.986" x="19.904" y="12.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".1"/></filter><filter id="ihRNkcL" width="3.829" height="3.829" x="11.609" y="11.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".25"/></filter><filter id="i2NnhXb" width="12.021" height="15.258" x="10.24" y="5.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.380392 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24263"/></filter><filter id="iFcHV5b" width="8.186" height="14.251" x="8.271" y="1.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".5"/></filter><filter id="iJVmtYb" width="8.186" height="10.454" x="15.46" y="5.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".5"/></filter><filter id="izMZFTb" width="11.186" height="6.923" x="10.508" y="4.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.117647 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24263"/></filter><filter id="iJ39XRd" width="8.715" height="5.797" x="11.935" y="4.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".125"/></filter><filter id="iNsECdd" width="3.66" height="3.66" x="11.885" y="11.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".25"/></filter><filter id="i40LAId" width="2.699" height="1.214" x="11.797" y="11.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.12549 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24263"/></filter><filter id="iL3Z0Xd" width="2.399" height=".914" x="11.847" y="11.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".075"/></filter><filter id="iYEXEqd" width="2.699" height="1.214" x="17.703" y="11.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.12549 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24263"/></filter><filter id="iNYAsMc" width="2.399" height=".914" x="17.753" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".075"/></filter><filter id="injekXc" width="2.618" height=".92" x="12.269" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".075"/></filter><filter id="iIPKADc" width="2.618" height=".92" x="17.16" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".075"/></filter><filter id="iF7nptG" width="3.122" height="4.211" x="14.162" y="13.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".25"/></filter><filter id="iK09Aks" width="4.199" height="1.729" x="13.906" y="17.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".05"/></filter><filter id="i9wp12L" width="2.811" height="6.368" x="8.719" y="8.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".375"/></filter><filter id="i57ljOe" width="6.686" height="12.645" x="8.688" y="2.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.407843 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24263"/></filter><filter id="imulFNc" width="6.436" height="12.695" x="17.329" y="2.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.309804 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24263"/></filter><filter id="iA3y0je" width="5.843" height="12.292" x="17.92" y="2.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".25"/></filter><filter id="i7Ubdgb" width="2.811" height="6.368" x="8.808" y="8.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".375"/></filter><filter id="iq5YdJb" width="5.14" height="8.355" x="9.763" y="1.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24263" stdDeviation=".25"/></filter><linearGradient id="iJAuGCd" x1="14.271" x2="12.072" y1="12.276" y2="12.344" gradientUnits="userSpaceOnUse"><stop class="jf-udwbdg"/><stop offset="1" class="v66a_wbdu"/></linearGradient><linearGradient id="i42yLGe" x1="17.729" x2="19.928" y1="12.221" y2="12.289" gradientUnits="userSpaceOnUse"><stop class="jf-udwbdg"/><stop offset="1" class="v66a_wbdu"/></linearGradient><linearGradient id="i6yIr7b" x1="14.936" x2="12.494" y1="13.984" y2="13.984" gradientUnits="userSpaceOnUse"><stop offset=".045" class="t94urlgya"/><stop offset=".32" class="zhq7idx2s"/><stop offset=".794" class="r8us_1bpp"/><stop offset="1" class="zfzr_2buk"/></linearGradient><linearGradient id="iHoQ0cd" x1="19.826" x2="17.385" y1="13.984" y2="13.984" gradientUnits="userSpaceOnUse"><stop offset=".045" class="t94urlgya"/><stop offset=".32" class="zhq7idx2s"/><stop offset=".794" class="r8us_1bpp"/><stop offset="1" class="zfzr_2buk"/></linearGradient><linearGradient id="ilVhyqe" x1="16.886" x2="15.849" y1="15.49" y2="15.54" gradientUnits="userSpaceOnUse"><stop offset=".106" class="usxz2na_s"/><stop offset="1" class="n0s808buc"/></linearGradient><linearGradient id="iswkPyc" x1="10.124" x2="10.124" y1="13.097" y2="8.266" gradientUnits="userSpaceOnUse"><stop class="n6_y6k2_m"/><stop offset="1" class="bd1m8wbbp"/></linearGradient><linearGradient id="icjDSMp" x1="10.214" x2="10.214" y1="13.329" y2="8.498" gradientUnits="userSpaceOnUse"><stop class="k1tnctvtk"/><stop offset="1" class="ejsfj0d0t"/><stop offset="1" class="hlfpu6bzn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-getting-massage-medium" /></template>
<style>
.a5m4qeq5q {
  stop-color: var(--svg-color--5a4b49, #5A4B49);
  stop-opacity: 0;
}

.aar72_bag {
  stop-color: var(--svg-color--5a4b49, #5A4B49);
}

.abk3uwbod {
  stroke: var(--svg-color--4a2f2d, #4A2F2D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.928 12.508c-.258-.207-.883-.578-1.95-.43");
}

.apsq0tbar {
  stop-color: var(--svg-color--926762, #926762);
}

.av0tm7_uc {
  stop-color: var(--svg-color--8a5960, #8A5960);
}

.ay0sr9bls {
  stop-color: var(--svg-color--985c6e, #985C6E);
}

.b2cgmuy3t {
  stop-color: var(--svg-color--9574dd, #9574DD);
  stop-opacity: 0;
}

.b5e_facvp {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
}

.bc2wedbnb {
  stop-color: var(--svg-color--986c68, #986C68);
  stop-opacity: 0;
}

.bd1m8wbbp {
  stop-color: var(--svg-color--ffcb3b, #FFCB3B);
  stop-opacity: 0;
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bk2ujv-xu {
  stop-color: var(--svg-color--cc957d, #CC957D);
  stop-opacity: 0;
}

.bnm8uzbww {
  d: path("M16 13.625a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.262");
}

.bz501rp8q {
  stop-color: var(--svg-color--39182b, #39182B);
  stop-opacity: 0;
}

.c_0yu_b0g {
  stop-color: var(--svg-color--bd9076, #BD9076);
}

.cibck0b0g {
  stop-color: var(--svg-color--ffb129, #FFB129);
}

.cltcdpbpn {
  stop-color: var(--svg-color--996e64, #996E64);
}

.cmnx7-cem {
  stop-color: var(--svg-color--925e6b, #925E6B);
  stop-opacity: 0;
}

.d3j_vxdji {
  d: path("M8.154 11.876c.56-.982.53-1.722.638-2.036l6.665 2.824v8.915h-3.72c-2.443 0-3.523-1.02-4.003-2.22s-.28-2.133-.06-2.795a1.54 1.54 0 0 0-.03-.998c-.452-1.252-.176-2.49.51-3.69");
}

.df2hh16wk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 13.984c.146.164.536.45 1.024.47c.617.023.949-.306 1.144-.47");
}

.dz7lmqc8k {
  stop-color: var(--svg-color--564340, #564340);
}

.e2arxx8zo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.928 12.453c-.258-.207-.883-.578-1.95-.43");
}

.e2w8wgkwd {
  stop-color: var(--svg-color--39182b, #39182B);
}

.eekdaj38l {
  stop-color: var(--svg-color--4e2d33, #4E2D33);
  stop-opacity: 0;
}

.ejsfj0d0t {
  stop-color: var(--svg-color--886361, #886361);
  stop-opacity: 0;
}

.eqqtw8bje {
  fill: var(--svg-color--88004e, #88004E);
  d: path("M14.357 17.333c.344.18.879.383 1.649.384c.77 0 1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135");
}

.f-z1ozvrb {
  cx: 21.396px;
  cy: 14.365px;
  r: 1.979px;
}

.f1zc5ekne {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 13.984c.146.164.536.45 1.023.47c.617.023.95-.306 1.145-.47");
}

.fjwf4gbrh {
  stop-color: var(--svg-color--aa827c, #AA827C);
  stop-opacity: 0;
}

.fmviwlb7j {
  fill: var(--svg-color--8d5e5f, #8D5E5F);
  d: path("M15.872 13.71c-.163 0-.248.094-.297.255l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.161-.045-.254-.209-.254");
}

.ft5dv1b6b {
  fill: none;
}

.g9mjpo7pf {
  stop-color: var(--svg-color--452537, #452537);
}

.gh97iwbkc {
  fill: var(--svg-color--a57d6b, #A57D6B);
  d: path("M16 13.625a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.262");
}

.ghvr_e1bi {
  stop-color: var(--svg-color--f39423, #F39423);
}

.gti-w2qfb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.072 12.508c.258-.207.883-.578 1.95-.43");
}

.gxmoj2a2w {
  stop-color: var(--svg-color--3e2c35, #3E2C35);
}

.hc0-o8aul {
  stop-color: var(--svg-color--2b1c22, #2B1C22);
}

.he4p8yb1z {
  stop-color: var(--svg-color--824d5a, #824D5A);
}

.hfhn00bef {
  stop-color: var(--svg-color--c29b87, #C29B87);
}

.hlfpu6bzn {
  stop-color: var(--svg-color--b78b7f, #B78B7F);
  stop-opacity: 0;
}

.i4ojxgbvw {
  cx: 21.396px;
  cy: 14.365px;
  r: 1.293px;
}

.iclvvachy {
  stop-color: var(--svg-color--7d4755, #7D4755);
}

.ievfp3btw {
  d: path("M21.21 8.363L19.187 9.85c-.244.18-.47.42-.676.196c-.22-.238-.007-.337.229-.56a52 52 0 0 1 1.99-1.785c.875-.734.85-2.109.828-2.57V2.554h1.704v10.713a.579.579 0 0 1-1.158 0V9.03c0-.402-.571-.906-.896-.667");
}

.ig-n-yctu {
  d: path("M23.846 11.876c-.56-.982-.53-1.722-.639-2.036l-6.664 2.824v8.915h3.72c2.443 0 3.523-1.02 4.003-2.22s.28-2.133.06-2.795a1.54 1.54 0 0 1 .03-.998c.452-1.252.176-2.49-.51-3.69");
}

.ilt16x1zy {
  stop-color: var(--svg-color--be9586, #BE9586);
  stop-opacity: 0;
}

.j8z-42s7e {
  width: 11.521px;
  height: 15.258px;
  x: 10.24px;
  y: 5.806px;
  rx: 5.76px;
}

.j9i9zyb7u {
  d: path("m9.469 9.011l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.jf-udwbdg {
  stop-color: var(--svg-color--533c3f, #533C3F);
  stop-opacity: 0;
}

.k1tnctvtk {
  stop-color: var(--svg-color--b78b7f, #B78B7F);
}

.k377ck8jo {
  stop-color: var(--svg-color--c19883, #C19883);
}

.k3jnt_bvt {
  stop-color: var(--svg-color--bf9886, #BF9886);
}

.k3si3xnlp {
  stop-color: var(--svg-color--9e625e, #9E625E);
}

.k4lo-hb9q {
  stop-color: var(--svg-color--7c4fa2, #7C4FA2);
  stop-opacity: 0;
}

.k87xpnbmx {
  stop-color: var(--svg-color--ae8472, #AE8472);
}

.khh_otzli {
  stop-color: var(--svg-color--bf9886, #BF9886);
  stop-opacity: 0;
}

.l_flc0gwk {
  cx: 13.715px;
  cy: 13.326px;
  r: 1.33px;
}

.l8w71gbix {
  stop-color: var(--svg-color--614f4d, #614F4D);
}

.lplgdxbdh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.494 13.984c.146.164.536.45 1.024.47c.617.023.949-.306 1.144-.47");
}

.lpu_4e3zg {
  stop-color: var(--svg-color--cc957d, #CC957D);
}

.lt5krob8g {
  fill: var(--svg-color--a47a6f, #A47A6F);
  d: path("M23.515 2.271h-3.426v3.484c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.714c.454.429 1.09.362 1.555-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.m__z0mykh {
  cx: 13.524px;
  cy: 13.242px;
  r: 1.415px;
}

.m2q2vh2sa {
  stop-color: var(--svg-color--825856, #825856);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mzkqj9diq {
  stop-color: var(--svg-color--5b4341, #5B4341);
}

.n_0ffbr5z {
  stop-color: var(--svg-color--8d4c57, #8D4C57);
  stop-opacity: 0;
}

.n0s808buc {
  stop-color: var(--svg-color--c59e88, #C59E88);
  stop-opacity: 0;
}

.n6_y6k2_m {
  stop-color: var(--svg-color--ffca3e, #FFCA3E);
}

.nk_-g356a {
  stop-color: var(--svg-color--a57460, #A57460);
}

.nserplb1x {
  cx: 10.604px;
  cy: 14.365px;
  r: 1.979px;
}

.nz0j9tb8x {
  stop-color: var(--svg-color--855b55, #855B55);
}

.o2l1ytrej {
  stop-color: var(--svg-color--4b302e, #4B302E);
}

.o4bfrybwl {
  stop-color: var(--svg-color--9e625e, #9E625E);
  stop-opacity: 0;
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5qf-ej6a {
  stop-color: var(--svg-color--be9586, #BE9586);
}

.oof-goujs {
  stop-color: var(--svg-color--936dd4, #936DD4);
}

.ou1bzhb5f {
  stop-color: var(--svg-color--564340, #564340);
  stop-opacity: 0;
}

.ou2-vlbjv {
  stop-color: var(--svg-color--4e2c2d, #4E2C2D);
}

.p0ctn-b9v {
  stop-color: var(--svg-color--4c2f2f, #4C2F2F);
}

.pi95o6_xg {
  stop-color: var(--svg-color--231828, #231828);
}

.plx67l2yn {
  stop-color: var(--svg-color--644c49, #644C49);
}

.pycm4bbqu {
  cx: 10.604px;
  cy: 14.365px;
  r: 1.293px;
  fill: var(--svg-color--734743, #734743);
}

.q_3fqdbeg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 13.984c.146.164.536.45 1.023.47c.617.023.95-.306 1.145-.47");
}

.q4bd_uhlb {
  fill: var(--svg-color--a47b6d, #A47B6D);
  d: path("M8.688 2.271h3.426v3.484c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.88.393v3.327a1.2 1.2 0 1 1-2.398 0z");
}

.q6gx3quyt {
  d: path("M13.75 20a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.q7vyx3bsm {
  d: path("M13.209 8.49c-.782 1.248-2.158 2.114-2.7 2.314V6.655c.265 0 1.576-.141 2.168-.514c.694-.437 1.337-1.637 3.352-1.637c1.071 0 1.808.377 2.923 1.337c.882.652 2.182.697 2.743.652v4.534c-.517-.373-1.428-.41-1.846-.428h-3.375c-1.744 0-2.934-1.39-3.265-2.11");
}

.qdxirobsy {
  stop-color: var(--svg-color--aa827c, #AA827C);
}

.r-5ctobwv {
  stop-color: var(--svg-color--9574dd, #9574DD);
}

.r7917jlmh {
  d: path("m9.558 9.243l1.311.78v3.433a.655.655 0 1 1-1.31 0z");
}

.r8us_1bpp {
  stop-color: var(--svg-color--4b3135, #4B3135);
}

.rc0rszb3u {
  stop-color: var(--svg-color--6a3874, #6A3874);
}

.rjclg2bzq {
  stop-color: var(--svg-color--402452, #402452);
}

.rw8jbub0d {
  stop-color: var(--svg-color--281820, #281820);
}

.sr4z9jbkj {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.333c.344.18.879.383 1.649.384c.77 0 1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135Z");
}

.srb0dp7as {
  stop-color: var(--svg-color--8d4c57, #8D4C57);
}

.ssxx1yhos {
  stop-color: var(--svg-color--885166, #885166);
}

.szcfc8bri {
  stop-color: var(--svg-color--614545, #614545);
  stop-opacity: 0;
}

.t94urlgya {
  stop-color: var(--svg-color--584141, #584141);
}

.tdq-64bsc {
  stroke: var(--svg-color--4a2f2d, #4A2F2D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.072 12.508c.258-.207.883-.578 1.95-.43");
}

.u3cxmmb4z {
  stop-color: var(--svg-color--7a4d53, #7A4D53);
}

.unym9abbi {
  stop-color: var(--svg-color--614f4d, #614F4D);
  stop-opacity: 0;
}

.usxz2na_s {
  stop-color: var(--svg-color--c59e88, #C59E88);
}

.uwosa3bcc {
  stop-color: var(--svg-color--4e2d33, #4E2D33);
}

.v66a_wbdu {
  stop-color: var(--svg-color--533c3f, #533C3F);
}

.v8wjp2hus {
  stop-color: var(--svg-color--563233, #563233);
}

.vf_3ecbae {
  d: path("M10.263 5.37V2.472h1.468v3.534a1 1 0 0 0 .28.694l2.263 2.349a.46.46 0 0 1-.636.663l-2.364-2.094a3 3 0 0 1-1.011-2.246");
}

.vod-dschj {
  d: path("M8.688 2.271h3.426v3.484c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.88.393v3.327a1.2 1.2 0 1 1-2.398 0z");
}

.vvxgj6bpi {
  d: path("M5.65 29.729h20.7c-.494-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.665");
}

.wj0_vcbzm {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
  stop-opacity: 0;
}

.ws75vab8k {
  stop-color: var(--svg-color--c29b87, #C29B87);
  stop-opacity: 0;
}

.wvp0mabjb {
  d: path("m9.271 2.405l1.516 5.892l1.938-.904c0 .34.199-.381.656 0a78 78 0 0 1 1.727 1.632c.476.46.463 1.207-.027 1.653c-.453.413-1.088.349-1.552-.053l-.98-.713a.54.54 0 0 0-.747.042a.5.5 0 0 0-.132.337V13.5c0 .639-.537 1.156-1.2 1.156s-1.199-.518-1.199-1.156z");
}

.x101rabpv {
  stop-color: var(--svg-color--b28278, #B28278);
}

.xnnyhy2ap {
  d: path("M22.646 8.25H19.22l-.684-1.812c0 .352.457.528 0 .923a79 79 0 0 0-1.727 1.691a1.195 1.195 0 0 0 .027 1.715c.453.428 1.09.362 1.554-.055l.978-.74a.527.527 0 0 1 .88.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.xxerewdbl {
  stop-color: var(--svg-color--623e81, #623E81);
  stop-opacity: 0;
}

.y-z81-bua {
  stop-color: var(--svg-color--725698, #725698);
}

.ytd3ey6so {
  stop-color: var(--svg-color--985c6e, #985C6E);
  stop-opacity: 0;
}

.z_1jymb2l {
  d: path("M13.135 6.281c-.313.207-.83.466-.95.438c1.038 3.687 4.893 3.74 6.59 3.437L20.4 8.594V6.719c-1.164-.57-3.218-1.828-4.671-1.742s-2.204 1.046-2.594 1.304");
}

.zedeq5w8l {
  stop-color: var(--svg-color--614545, #614545);
}

.zfzr_2buk {
  stop-color: var(--svg-color--564040, #564040);
}

.zhq7idx2s {
  stop-color: var(--svg-color--503839, #503839);
}

.zjt_glb7d {
  fill: var(--svg-color--aa746e, #AA746E);
  d: path("M13.75 20a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

</style>
