<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ibk7fWb)"><circle fill="url(#ihfasrb)" class="c3vm8kt4c"/></g><g filter="url(#i2BmjOu)"><circle fill="url(#ipHuckZ)" class="c3vm8kt4c"/></g><g filter="url(#ijtaqje)"><circle fill="url(#i24UPXb)" class="n73l6to2h"/></g><g filter="url(#iUcYSkc)"><circle fill="url(#iMuxcAb)" class="jvwpinbbf"/><circle fill="url(#iy6nEBe)" class="jvwpinbbf"/></g><g filter="url(#iL6ipAd)"><circle class="kvqr6ibur"/><circle fill="url(#ix0BsIb)" class="xq483lxba"/><circle fill="url(#iPcIxte)" class="xq483lxba"/></g><g filter="url(#iR2sk2d)"><path fill="url(#i6baZyd)" class="bhop8fbem"/><path fill="url(#io1b3lb)" class="bhop8fbem"/><path fill="url(#igdTUSb)" class="bhop8fbem"/><path fill="url(#i4m5PWc)" class="bhop8fbem"/><path fill="url(#iGbzu7d)" class="bhop8fbem"/><path fill="url(#iBBKoyG)" class="bhop8fbem"/><path fill="url(#iqyi1Lc)" class="bhop8fbem"/></g><g filter="url(#i6AUUGc)"><path fill="url(#i2yqulj)" class="y7d3--b_f"/></g><g filter="url(#ilugsoe)"><path fill="url(#ivTlGhc)" class="ynsl3-bvt"/><path fill="url(#ip9zZuZ)" class="ynsl3-bvt"/><path fill="url(#iflIIIb)" class="ynsl3-bvt"/></g><path fill="url(#iDFsrBs)" class="ynsl3-bvt"/><path fill="url(#iLK8Hcd)" class="ynsl3-bvt"/><path fill="url(#i8cjQEo)" class="ynsl3-bvt"/><g filter="url(#ih1bqze)"><path class="akr3r0vgi"/></g><g filter="url(#iJiFKfe)"><path class="vmk-6kbkw"/><path fill="url(#im5cPgo)" class="bdg888bzf"/><path fill="url(#ihlnvRc)" class="bdg888bzf"/><path fill="url(#iA3cYtc)" class="bdg888bzf"/></g><path fill="url(#iJyQttb)" class="bdg888bzf"/><path stroke="url(#ipuu4vu)" class="j6ynxe8oa"/><g filter="url(#iU5y7lc)"><path class="m60s1rxmf"/></g><g filter="url(#iSUKPIv)"><path class="k66hz199k"/></g><path class="pdv4ldbpr"/><path fill="url(#iT72KYv)" class="ysuyqjbga"/><path class="heacg5ncs"/><g filter="url(#iqaHvWc)"><path class="z98s40bed"/><path fill="url(#iO48bjt)" class="z20bumf_j"/></g><g filter="url(#iWKSXWa)"><path fill="url(#ikMrDfd)" class="i_ux49j5u"/></g><path class="l6wzmlbrw"/><path fill="url(#igY4D7c)" class="pymlyd-1i"/><path class="uozffyiai"/><g filter="url(#i5WKCae)"><path fill="url(#itFLHzb)" class="sow05c3ou"/></g><g filter="url(#iCTKxEc)"><ellipse transform="rotate(-27.914 11.367 16.608)" class="xk1wlybvw"/><ellipse fill="url(#ivdEdNn)" transform="rotate(-27.914 11.367 16.608)" class="bz40dzb6n"/></g><g filter="url(#iCGTWdu)"><path stroke="url(#iaklsDd)" class="khbuz0hlc"/></g><g filter="url(#iJ5g1Dc)"><path stroke="url(#iPVdAvL)" class="ut7qi9bnx"/></g><defs><radialGradient id="ihfasrb" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.059)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="ipHuckZ" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.059)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iy6nEBe" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.527 17.564)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="ix0BsIb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.59)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iPcIxte" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.54 39.223)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="i6baZyd" cx="0" cy="0" r="1" gradientTransform="matrix(-14.1844 0 0 -27.6939 24.188 20.375)" gradientUnits="userSpaceOnUse"><stop class="o9dsjhw-b"/><stop offset="1" class="s9z7ffb2b"/></radialGradient><radialGradient id="igdTUSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.3495 -27.7163 0 17.216 14.246)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="jzlzzob9a"/><stop offset=".955" class="u-k7t7b5n"/></radialGradient><radialGradient id="i4m5PWc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9969 0 0 -3.02146 18.111 17.688)" gradientUnits="userSpaceOnUse"><stop class="g4c4tt79s"/><stop offset="1" class="vkuhkbmvu"/></radialGradient><radialGradient id="iGbzu7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 2.93253 0 20.321 15.75)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="d5r5ryf-n"/><stop offset="1" class="r-xlfacgk"/></radialGradient><radialGradient id="iBBKoyG" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 3.22556 0 11.821 15.625)" gradientUnits="userSpaceOnUse"><stop class="gbu1-19ef"/><stop offset="1" class="gink60bky"/></radialGradient><radialGradient id="iqyi1Lc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.16694 4.8677 -4.19823 -7.04371 26.313 10.25)" gradientUnits="userSpaceOnUse"><stop class="a5yngybsj"/><stop offset="1" class="y5103r3-p"/></radialGradient><radialGradient id="ip9zZuZ" cx="0" cy="0" r="1" gradientTransform="rotate(-169.032 11.112 3.065)scale(8.21251 6.30254)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="ha7uidbhc"/><stop offset="1" class="hob4k4jlt"/></radialGradient><radialGradient id="iflIIIb" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -.8125 2.32033 8.3889 3.813 11.563)" gradientUnits="userSpaceOnUse"><stop class="v2ghvibho"/><stop offset="1" class="hclt60hnj"/></radialGradient><radialGradient id="iDFsrBs" cx="0" cy="0" r="1" gradientTransform="matrix(24.13471 5.30512 -8.3114 37.8112 4.196 9.166)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="m-q5of__w"/><stop offset="1" class="bsxl5bcor"/></radialGradient><radialGradient id="iLK8Hcd" cx="0" cy="0" r="1" gradientTransform="matrix(-14.54976 3.51915 -5.51336 -22.79472 19.507 10.689)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="s1378pb0u"/><stop offset="1" class="vt_gtsn-n"/></radialGradient><radialGradient id="i8cjQEo" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -5.21875 2.62621 .01573 24.281 12.156)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="objjc_bxi"/><stop offset="1" class="v16nj1e9y"/></radialGradient><radialGradient id="iT72KYv" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.01 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="e0-rnofaa"/><stop offset="1" class="qh547r7uu"/></radialGradient><radialGradient id="iO48bjt" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.941 3.676)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igY4D7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 11.873 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="e0-rnofaa"/><stop offset="1" class="qh547r7uu"/></radialGradient><radialGradient id="ivdEdNn" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.134 3.016)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ibk7fWb" width="6.427" height="6.227" x="3.979" y="14.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20062"/></filter><filter id="i2BmjOu" width="6.427" height="6.227" x="3.979" y="14.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20062"/></filter><filter id="ijtaqje" width="4.711" height="4.711" x="4.737" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20062" stdDeviation=".25"/></filter><filter id="iUcYSkc" width="6.477" height="6.477" x="21.72" y="14.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20062"/></filter><filter id="iL6ipAd" width="4.711" height="4.711" x="22.478" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20062" stdDeviation=".25"/></filter><filter id="iR2sk2d" width="19.345" height="22.73" x="6.327" y="7.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.486275 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20062"/></filter><filter id="i6AUUGc" width="11.918" height="9.719" x="15.009" y="5.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20062" stdDeviation="1"/></filter><filter id="ilugsoe" width="24" height="15.65" x="4.196" y="1.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.717647 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20062"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.658824 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_20062" result="effect2_innerShadow_3987_20062"/></filter><filter id="ih1bqze" width="4.782" height="6.5" x="13.11" y="16.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20062" stdDeviation=".375"/></filter><filter id="iJiFKfe" width="4" height="5.5" x="13.946" y="16.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20062" stdDeviation=".125"/></filter><filter id="iU5y7lc" width="5.34" height="3.147" x="18.151" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.596078 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20062"/></filter><filter id="iSUKPIv" width="5.341" height="3.147" x="8.551" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.596078 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20062"/></filter><filter id="iqaHvWc" width="1.294" height="1.125" x="18.727" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20062" stdDeviation=".05"/></filter><filter id="iWKSXWa" width="1.316" height="1.357" x="20.38" y="16.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20062" stdDeviation=".1"/></filter><filter id="i5WKCae" width="1.493" height="1.594" x="12.097" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20062" stdDeviation=".1"/></filter><filter id="iCTKxEc" width="1.529" height="1.141" x="10.603" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20062" stdDeviation=".05"/></filter><filter id="iCGTWdu" width="4.949" height="2.304" x="18.293" y="11.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20062" stdDeviation=".25"/></filter><filter id="iJ5g1Dc" width="5.094" height="2.41" x="8.56" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20062" stdDeviation=".25"/></filter><linearGradient id="i24UPXb" x1="7.092" x2="5.898" y1="18.578" y2="18.578" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iMuxcAb" x1="26.859" x2="25.332" y1="16.023" y2="20.753" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="io1b3lb" x1="5.688" x2="9.469" y1="23.188" y2="23" gradientUnits="userSpaceOnUse"><stop offset=".323" class="anb8kgfjc"/><stop offset="1" class="frvwzos0n"/></linearGradient><linearGradient id="i2yqulj" x1="15.701" x2="30.889" y1="13.219" y2="7.781" gradientUnits="userSpaceOnUse"><stop class="md_nv2yaz"/><stop offset="1" class="affo-kbuc"/></linearGradient><linearGradient id="ivTlGhc" x1="6.875" x2="28.817" y1="11.365" y2="11.365" gradientUnits="userSpaceOnUse"><stop class="b-ormlbtu"/><stop offset=".259" class="sgf6zbc8i"/><stop offset="1" class="vsch1zb0k"/></linearGradient><linearGradient id="im5cPgo" x1="14.335" x2="16.084" y1="20.014" y2="20.014" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="ihlnvRc" x1="17.696" x2="15.784" y1="20.616" y2="20.588" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iA3cYtc" x1="16.309" x2="16.309" y1="22" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iJyQttb" x1="16.181" x2="16.181" y1="22.078" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="ipuu4vu" x1="14.012" x2="14.824" y1="25.012" y2="23.73" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="ikMrDfd" x1="21.46" x2="20.875" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itFLHzb" x1="13.26" x2="12.675" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaklsDd" x1="21.489" x2="20.706" y1="12.897" y2="11.296" gradientUnits="userSpaceOnUse"><stop class="xuhudn71p"/><stop offset="1" class="vohu6nbta"/></linearGradient><linearGradient id="iPVdAvL" x1="11.597" x2="9.379" y1="12.659" y2="11.729" gradientUnits="userSpaceOnUse"><stop class="xuhudn71p"/><stop offset="1" class="vohu6nbta"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-white-hair-medium-light" /></template>
<style>
.a5yngybsj {
  stop-color: var(--svg-color--ebb494, #EBB494);
}

.affo-kbuc {
  stop-color: var(--svg-color--fcc8a7, #FCC8A7);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.akr3r0vgi {
  fill: var(--svg-color--c68378, #C68378);
  d: path("M15.433 17.83L13.903 21c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.anb8kgfjc {
  stop-color: var(--svg-color--d99e83, #D99E83);
}

.b-ormlbtu {
  stop-color: var(--svg-color--bbb3ba, #BBB3BA);
}

.bdg888bzf {
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.bhop8fbem {
  d: path("M6.327 14.234c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.36c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034L24.97 24.4c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6c-.26-3.387-.373-6.785-.683-10.166");
}

.bsxl5bcor {
  stop-color: var(--svg-color--cdc9cb, #CDC9CB);
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

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d5r5ryf-n {
  stop-color: var(--svg-color--e1a08b, #E1A08B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.frvwzos0n {
  stop-color: var(--svg-color--d99e83, #D99E83);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g4c4tt79s {
  stop-color: var(--svg-color--ffc7a1, #FFC7A1);
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gbu1-19ef {
  stop-color: var(--svg-color--c1827a, #C1827A);
}

.gink60bky {
  stop-color: var(--svg-color--c1827a, #C1827A);
  stop-opacity: 0;
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.ha7uidbhc {
  stop-color: var(--svg-color--fff7f6, #FFF7F6);
}

.hclt60hnj {
  stop-color: var(--svg-color--aea6ae, #AEA6AE);
  stop-opacity: 0;
}

.heacg5ncs {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 17.561c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.hob4k4jlt {
  stop-color: var(--svg-color--fff7f6, #FFF7F6);
  stop-opacity: 0;
}

.i_ux49j5u {
  d: path("M21.496 17.342a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j6ynxe8oa {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.386 23.239a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.22-2.56-.606Z");
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jvwpinbbf {
  cx: 24.833px;
  cy: 18.059px;
  r: 3.113px;
}

.jzlzzob9a {
  stop-color: var(--svg-color--c8878c, #C8878C);
  stop-opacity: 0;
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k66hz199k {
  fill: var(--svg-color--d2cacd, #D2CACD);
  d: path("m8.91 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.khbuz0hlc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.717c.802-.14 2.366-.1 3.449.742");
}

.kvqr6ibur {
  cx: 24.833px;
  cy: 18.059px;
  r: 1.855px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.l6wzmlbrw {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.39c-1.218 0-2.247.84-2.526 1.975a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m-q5of__w {
  stop-color: var(--svg-color--d8d1de, #D8D1DE);
  stop-opacity: 0;
}

.m60s1rxmf {
  fill: var(--svg-color--d2cacd, #D2CACD);
  d: path("m22.883 12.986l-.002-.002l-.004-.002l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.md_nv2yaz {
  stop-color: var(--svg-color--fcc8a7, #FCC8A7);
}

.n73l6to2h {
  cx: 7.092px;
  cy: 18.059px;
  r: 1.855px;
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.o9dsjhw-b {
  stop-color: var(--svg-color--fdc3a0, #FDC3A0);
}

.objjc_bxi {
  stop-color: var(--svg-color--eee8f3, #EEE8F3);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.pdv4ldbpr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.39c1.217 0 2.245.84 2.525 1.975a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pymlyd-1i {
  d: path("M11.87 15.897A1.664 1.664 0 0 0 10.266 18h3.214c.038-.144.061-.287.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.qh547r7uu {
  stop-color: var(--svg-color--5e433e, #5E433E);
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.r-xlfacgk {
  stop-color: var(--svg-color--e1a08b, #E1A08B);
  stop-opacity: 0;
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s1378pb0u {
  stop-color: var(--svg-color--a89fa9, #A89FA9);
  stop-opacity: 0;
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s9z7ffb2b {
  stop-color: var(--svg-color--c8907d, #C8907D);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sgf6zbc8i {
  stop-color: var(--svg-color--dbd4d9, #DBD4D9);
}

.sow05c3ou {
  d: path("M13.39 17.366c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.u-k7t7b5n {
  stop-color: var(--svg-color--b36e90, #B36E90);
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

.v16nj1e9y {
  stop-color: var(--svg-color--eee8f3, #EEE8F3);
  stop-opacity: 0;
}

.v2ghvibho {
  stop-color: var(--svg-color--aea6ae, #AEA6AE);
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.vkuhkbmvu {
  stop-color: var(--svg-color--ffc7a1, #FFC7A1);
  stop-opacity: 0;
}

.vmk-6kbkw {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.vohu6nbta {
  stop-color: var(--svg-color--e5e1e7, #E5E1E7);
  stop-opacity: 0;
}

.vsch1zb0k {
  stop-color: var(--svg-color--ede9f1, #EDE9F1);
}

.vt_gtsn-n {
  stop-color: var(--svg-color--a89fa9, #A89FA9);
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
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

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xuhudn71p {
  stop-color: var(--svg-color--e5e1e7, #E5E1E7);
}

.y5103r3-p {
  stop-color: var(--svg-color--ebb494, #EBB494);
  stop-opacity: 0;
}

.y7d3--b_f {
  d: path("m24.084 7.57l-5.739 1.913a1.953 1.953 0 0 0 .877 3.788l5.706-.764z");
}

.ynsl3-bvt {
  d: path("m24.933 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.201-.299-3.702-.796-7.303-.796s-6.102.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1.03.513 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.ysuyqjbga {
  d: path("M20.013 15.898A1.664 1.664 0 0 1 21.617 18h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.663");
}

.z20bumf_j {
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.z98s40bed {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

</style>
