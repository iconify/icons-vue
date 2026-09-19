<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iVFNlCb)" class="c3vm8kt4c"/><g filter="url(#iYYDyJb)"><circle fill="url(#iQUlG6c)" class="n73l6to2h"/></g><g filter="url(#iVzAPyu)"><circle fill="url(#iTt8vEc)" class="jvwpinbbf"/><circle fill="url(#iw62rKa)" class="jvwpinbbf"/></g><g filter="url(#iOKdwhc)"><circle class="hesy95r-g"/><circle fill="url(#iynzOrb)" class="xq483lxba"/><circle fill="url(#i8VnHYO)" class="xq483lxba"/></g><path fill="url(#i0Xywfd)" class="u4uwu8b1h"/><path fill="url(#iTt0z8q)" class="u4uwu8b1h"/><path fill="url(#iRzo41b)" class="u4uwu8b1h"/><path fill="url(#i1iTOFe)" class="u4uwu8b1h"/><path fill="url(#iVdXWPd)" class="u4uwu8b1h"/><path fill="url(#ihKy9Vc)" class="u4uwu8b1h"/><g filter="url(#iosPMwd)"><path class="g1f4gom4l"/><path fill="url(#isOFCDZ)" class="l9lz842fh"/><path fill="url(#iyIcAJe)" class="l9lz842fh"/><path fill="url(#i18tdJe)" class="l9lz842fh"/><path fill="url(#iZ86lle)" class="l9lz842fh"/><path fill="url(#ij3rSBe)" class="l9lz842fh"/><path fill="url(#iuEkdCe)" class="l9lz842fh"/></g><path fill="url(#iex4dkc)" class="yp92-xskm"/><path fill="url(#ioAcHFe)" class="yp92-xskm"/><path fill="url(#iopg8wd)" class="yp92-xskm"/><g filter="url(#iGlA7ae)"><path class="abkzm39fd"/></g><g filter="url(#iE954qf)"><path class="p2zchrbfq"/><path fill="url(#iYnoQDb)" class="bdg888bzf"/><path fill="url(#iKQaUzH)" class="bdg888bzf"/><path fill="url(#iu9NsHd)" class="bdg888bzf"/></g><path fill="url(#ib9yrwb)" class="bdg888bzf"/><path stroke="url(#iq30cve)" class="n1ha83bmb"/><g filter="url(#iG6DaRb)"><path class="khd-okbzs"/></g><g filter="url(#iv4A7ve)"><path class="n9e7duxny"/></g><path class="pdv4ldbpr"/><path fill="url(#i0o1nfc)" class="m8cdxvtli"/><path class="heacg5ncs"/><g filter="url(#iv5JiMd)"><path class="vxy28rbkx"/><path fill="url(#iO48bjt)" class="y1c__-95e"/></g><g filter="url(#i1xGBqI)"><path fill="url(#ikMrDfd)" class="i_ux49j5u"/></g><path class="l6wzmlbrw"/><path fill="url(#i4phFUc)" class="pymlyd-1i"/><path class="uozffyiai"/><g filter="url(#in25Tzb)"><path fill="url(#itFLHzb)" class="sow05c3ou"/></g><g filter="url(#i3yGk5d)"><ellipse transform="rotate(-27.914 11.367 16.608)" class="xk1wlybvw"/><ellipse fill="url(#ivdEdNn)" transform="rotate(-27.914 11.367 16.608)" class="bz40dzb6n"/></g><g filter="url(#iZKt3tb)"><path stroke="url(#izv8Yhc)" class="khbuz0hlc"/></g><g filter="url(#iS3J8uH)"><path stroke="url(#iJlHw4Z)" class="ut7qi9bnx"/></g><g filter="url(#i33Y9hc)"><path fill="url(#imQrqgb)" class="yhs1xt3sb"/></g><path fill="url(#irTQ1Mc)" class="yhs1xt3sb"/><path fill="url(#iFi5Itd)" class="yhs1xt3sb"/><path fill="url(#iP6U6YC)" class="yhs1xt3sb"/><path fill="url(#iadqIVc)" class="yhs1xt3sb"/><defs><radialGradient id="iVFNlCb" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.059)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="p8hteacus"/><stop offset="1" class="o-h9r8b6m"/></radialGradient><radialGradient id="iw62rKa" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.527 17.564)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iynzOrb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.59)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="i8VnHYO" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.54 39.223)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iRzo41b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.625 16 -21.71914 -3.5633 18.009 15.563)" gradientUnits="userSpaceOnUse"><stop offset=".643" class="z9h1phlew"/><stop offset="1" class="fblnsmbke"/></radialGradient><radialGradient id="i1iTOFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 3 0 20.321 15.688)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iVdXWPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 3.22556 0 11.821 15.625)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="ihKy9Vc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7537 21.8125 0 16 18.785)" gradientUnits="userSpaceOnUse"><stop offset=".907" class="ghelm4bvv"/><stop offset=".983" class="a98zplbyd"/></radialGradient><radialGradient id="isOFCDZ" cx="0" cy="0" r="1" gradientTransform="matrix(-6.4087 8.25997 -14.04691 -10.89865 22.832 3.675)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="i18tdJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.12461 -3.47136 1.70486 -.0612 8.127 11.615)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iZ86lle" cx="0" cy="0" r="1" gradientTransform="matrix(1.60216 -3.6672 2.99087 1.30668 23.829 14.818)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="ij3rSBe" cx="0" cy="0" r="1" gradientTransform="matrix(1.85139 2.29723 -2.0283 1.63465 14.5 2.019)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iuEkdCe" cx="0" cy="0" r="1" gradientTransform="matrix(2.70588 -5.66099 1.95595 .93492 23.758 10.19)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iex4dkc" cx="0" cy="0" r="1" gradientTransform="rotate(76.961 7.351 11.855)scale(1.4992 2.4647)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="r29nd_sam"/><stop offset="1" class="p8ymub_2v"/></radialGradient><radialGradient id="ioAcHFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.35294 1.67337 -3.7494 3.03145 7.843 5.242)" gradientUnits="userSpaceOnUse"><stop class="pb3_oi83v"/><stop offset="1" class="mmcwxbbos"/></radialGradient><radialGradient id="iopg8wd" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 -2.7685 4.33733 1.07709 6.375 17.018)" gradientUnits="userSpaceOnUse"><stop class="tk45-bcbs"/><stop offset="1" class="myx9rg30e"/></radialGradient><radialGradient id="i0o1nfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.01 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iO48bjt" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.941 3.676)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4phFUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 11.873 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ivdEdNn" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.134 3.016)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iP6U6YC" cx="0" cy="0" r="1" gradientTransform="rotate(124.509 -.69 14.14)scale(1.98373 .8875)" gradientUnits="userSpaceOnUse"><stop offset=".431" class="um_rl4c9u"/><stop offset="1" class="sp5fkq8qu"/></radialGradient><linearGradient id="iQUlG6c" x1="7.092" x2="5.898" y1="18.578" y2="18.578" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iTt8vEc" x1="26.859" x2="25.332" y1="16.023" y2="20.753" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="i0Xywfd" x1="23.473" x2="9.231" y1="18.785" y2="20.907" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset="1" class="x2e45tbep"/></linearGradient><linearGradient id="iTt0z8q" x1="5.884" x2="10.196" y1="23.813" y2="23.25" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iyIcAJe" x1="6.881" x2="12.293" y1="17.56" y2="7.947" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iYnoQDb" x1="14.335" x2="16.084" y1="20.014" y2="20.014" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iKQaUzH" x1="17.696" x2="15.784" y1="20.616" y2="20.588" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iu9NsHd" x1="16.309" x2="16.309" y1="22" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="ib9yrwb" x1="16.181" x2="16.181" y1="22.078" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="iq30cve" x1="14.715" x2="15.453" y1="25.366" y2="23.913" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="ikMrDfd" x1="21.46" x2="20.875" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itFLHzb" x1="13.26" x2="12.675" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izv8Yhc" x1="21.489" x2="20.706" y1="12.897" y2="11.296" gradientUnits="userSpaceOnUse"><stop class="rd2dtjb_d"/><stop offset="1" class="ugw3yibbz"/></linearGradient><linearGradient id="iJlHw4Z" x1="11.829" x2="10.231" y1="12.852" y2="11.809" gradientUnits="userSpaceOnUse"><stop offset=".456" class="rd2dtjb_d"/><stop offset="1" class="ugw3yibbz"/></linearGradient><linearGradient id="imQrqgb" x1="8.628" x2="23.068" y1="28.303" y2="24.217" gradientUnits="userSpaceOnUse"><stop offset=".314" class="k8gi__bag"/><stop offset="1" class="tsee1rbmp"/></linearGradient><linearGradient id="irTQ1Mc" x1="6.493" x2="8.409" y1="24.183" y2="23.976" gradientUnits="userSpaceOnUse"><stop offset=".346" class="wh046-wtn"/><stop offset="1" class="s8o9betix"/></linearGradient><linearGradient id="iFi5Itd" x1="25.486" x2="23.477" y1="25.272" y2="25.068" gradientUnits="userSpaceOnUse"><stop class="q-kh4g8am"/><stop offset="1" class="nfvocfb7w"/></linearGradient><linearGradient id="iadqIVc" x1="15.954" x2="15.954" y1="30.016" y2="28.536" gradientUnits="userSpaceOnUse"><stop class="u6m_i4bld"/><stop offset="1" class="j7p81ul3f"/></linearGradient><filter id="iYYDyJb" width="4.911" height="4.911" x="4.637" y="15.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19849" stdDeviation=".3"/></filter><filter id="iVzAPyu" width="6.477" height="6.477" x="21.72" y="14.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19849"/></filter><filter id="iOKdwhc" width="4.711" height="4.711" x="22.478" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19849" stdDeviation=".25"/></filter><filter id="iosPMwd" width="23.5" height="15.5" x="4.196" y="1.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19849"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_19849" result="effect2_innerShadow_3987_19849"/></filter><filter id="iGlA7ae" width="4.782" height="6.5" x="13.11" y="16.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19849" stdDeviation=".375"/></filter><filter id="iE954qf" width="4" height="5.5" x="13.946" y="16.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19849" stdDeviation=".125"/></filter><filter id="iG6DaRb" width="5.34" height="3.147" x="18.151" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.243137 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19849"/></filter><filter id="iv4A7ve" width="5.341" height="3.147" x="8.551" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.243137 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19849"/></filter><filter id="iv5JiMd" width="1.294" height="1.125" x="18.727" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19849" stdDeviation=".05"/></filter><filter id="i1xGBqI" width="1.316" height="1.357" x="20.38" y="16.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19849" stdDeviation=".1"/></filter><filter id="in25Tzb" width="1.493" height="1.594" x="12.097" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19849" stdDeviation=".1"/></filter><filter id="i3yGk5d" width="1.529" height="1.141" x="10.603" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19849" stdDeviation=".05"/></filter><filter id="iZKt3tb" width="4.949" height="2.304" x="18.293" y="11.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19849" stdDeviation=".25"/></filter><filter id="iS3J8uH" width="5.094" height="2.41" x="8.56" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19849" stdDeviation=".25"/></filter><filter id="i33Y9hc" width="20.186" height="16.516" x="5.736" y="13.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.388235 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19849"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.615686 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_19849" result="effect2_innerShadow_3987_19849"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.458824 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_19849" result="effect3_innerShadow_3987_19849"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-beard" /></template>
<style>
.a98zplbyd {
  stop-color: var(--svg-color--fe9708, #FE9708);
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.abkzm39fd {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("M15.433 17.83L13.903 21c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.bdg888bzf {
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.bz40dzb6n {
  cx: 11.367px;
  cy: 16.608px;
  rx: 0.726px;
  ry: 0.368px;
}

.c3vm8kt4c {
  cx: 7.092px;
  cy: 18.059px;
  r: 3.113px;
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

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
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

.g1f4gom4l {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m24.933 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.201-.299-3.702-.796-7.303-.796s-6.102.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.026.29.07 2.217.07 2.688c-.558-.038-.976-.431-1.07-.998l-1.101-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.ghelm4bvv {
  stop-color: var(--svg-color--fe9708, #FE9708);
  stop-opacity: 0;
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.heacg5ncs {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 17.561c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.hesy95r-g {
  cx: 24.833px;
  cy: 18.059px;
  r: 1.855px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i_ux49j5u {
  d: path("M21.496 17.342a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.j7p81ul3f {
  stop-color: var(--svg-color--c95957, #C95957);
  stop-opacity: 0;
}

.jvwpinbbf {
  cx: 24.833px;
  cy: 18.059px;
  r: 3.113px;
}

.k8gi__bag {
  stop-color: var(--svg-color--d96c36, #D96C36);
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.khbuz0hlc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.717c.802-.14 2.366-.1 3.449.742");
}

.khd-okbzs {
  fill: var(--svg-color--c85c2f, #C85C2F);
  d: path("m22.883 12.986l-.002-.002l-.004-.002l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l6wzmlbrw {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.39c-1.218 0-2.247.84-2.526 1.975a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.l9lz842fh {
  d: path("m24.933 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.201-.299-3.702-.796-7.303-.796s-6.102.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.026.29.07 2.217.07 2.688c-.558-.038-.976-.431-1.07-.998l-1.101-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m8cdxvtli {
  d: path("M20.013 15.897A1.664 1.664 0 0 1 21.617 18h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.664");
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

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.myx9rg30e {
  stop-color: var(--svg-color--d06b2d, #D06B2D);
  stop-opacity: 0;
}

.n1ha83bmb {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.569 23.604a.315.315 0 0 0-.376.065a.29.29 0 0 0-.031.37a3.33 3.33 0 0 0 2.784 1.487a3.33 3.33 0 0 0 2.786-1.488a.29.29 0 0 0-.033-.373a.32.32 0 0 0-.375-.061a5.1 5.1 0 0 1-2.378.563c-.871 0-1.69-.205-2.377-.563Z");
}

.n73l6to2h {
  cx: 7.092px;
  cy: 18.059px;
  r: 1.855px;
}

.n9e7duxny {
  fill: var(--svg-color--c85c2f, #C85C2F);
  d: path("m8.91 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.nfvocfb7w {
  stop-color: var(--svg-color--e49e67, #E49E67);
  stop-opacity: 0;
}

.o-h9r8b6m {
  stop-color: var(--svg-color--c97a3b, #C97A3B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p2zchrbfq {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
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

.pdv4ldbpr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.39c1.217 0 2.245.84 2.525 1.975a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.pymlyd-1i {
  d: path("M11.87 15.897A1.664 1.664 0 0 0 10.266 18h3.214c.038-.144.061-.287.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.q-kh4g8am {
  stop-color: var(--svg-color--e49e67, #E49E67);
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

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s8o9betix {
  stop-color: var(--svg-color--bf876c, #BF876C);
  stop-opacity: 0;
}

.sow05c3ou {
  d: path("M13.39 17.366c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.sp5fkq8qu {
  stop-color: var(--svg-color--d06c1e, #D06C1E);
  stop-opacity: 0;
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tk45-bcbs {
  stop-color: var(--svg-color--d06b2d, #D06B2D);
}

.tsee1rbmp {
  stop-color: var(--svg-color--f99444, #F99444);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.u4uwu8b1h {
  d: path("M6.384 16.919c-.057-1.067-.026-2.349-.057-2.685c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.36c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034L24.97 24.4c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6z");
}

.u6m_i4bld {
  stop-color: var(--svg-color--c96a98, #C96A98);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.ugw3yibbz {
  stop-color: var(--svg-color--cf715d, #CF715D);
  stop-opacity: 0;
}

.um_rl4c9u {
  stop-color: var(--svg-color--d06c1e, #D06C1E);
}

.uozffyiai {
  fill: var(--svg-color--000, #000);
  d: path("M12.823 17.561a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.ut7qi9bnx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.31 13.684c.61-.54 1.942-1.107 3.593-.844");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vxy28rbkx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.359-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wh046-wtn {
  stop-color: var(--svg-color--bf876c, #BF876C);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x2e45tbep {
  stop-color: var(--svg-color--ffac1b, #FFAC1B);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xk1wlybvw {
  cx: 11.367px;
  cy: 16.608px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.xq483lxba {
  cx: 24.833px;
  cy: 18.059px;
  r: 1.855px;
}

.y1c__-95e {
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.359-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.yhs1xt3sb {
  d: path("m25.672 14.15l-.703 10.2c-.301 3.3-2.51 5.666-6.023 5.666h-6.024C9.41 30.016 7.2 27.65 6.9 24.35l-.663-9.345l3.072 8.045c.1.5.703.6 1.004.3l.803-.7c.703-.6 1.506-.8 2.31-.8h5.019c.903 0 1.706.2 2.309.8l.803.7c.301.3.903.1 1.004-.3zm-12.75 11.7c0 .9.803 1.7 1.807 1.7c.201 0 .301-.2.301-.3v-.1c0-.5.402-.9.904-.9s.903.4.903.9v.1c0 .2.201.3.302.3c.903 0 1.807-.7 1.807-1.7v-1.5c0-.5-.347-.9-1.004-.9h-4.016c-.636 0-1.004.4-1.004.9z");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yp92-xskm {
  d: path("m24.933 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.201-.299-3.702-.796-7.303-.796s-6.102.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.615.967-.615 1.464c.026.29.085 2.145.085 2.616c-.558-.038-.976-.431-1.07-.998l-1.101-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.z9h1phlew {
  stop-color: var(--svg-color--d87753, #D87753);
  stop-opacity: 0;
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
