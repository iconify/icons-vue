<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iWN4Sfc)" class="d7cydccmc"/><path fill="url(#i5elQvc)" class="d7cydccmc"/><path fill="url(#i7hWpce)" class="d7cydccmc"/><path fill="url(#i0f2vge)" class="z6_fct6lh"/><path fill="url(#ifCCrHe)" class="z6_fct6lh"/><path fill="url(#iPEeqjN)" class="z6_fct6lh"/><path fill="url(#iiCiV1A)" class="sxsuk1blc"/><path fill="url(#iCHWUko)" class="sxsuk1blc"/><path fill="url(#ihcCgTf)" class="sxsuk1blc"/><path fill="url(#iysHjQb)" class="wsr13_byj"/><path fill="url(#iVplQEc)" class="wsr13_byj"/><path fill="url(#iTJHU0d)" class="ej-qbfntw"/><path fill="url(#iea7pDc)" class="ej-qbfntw"/><path fill="url(#ipOAjVd)" class="o5h2uacjl"/><path fill="url(#iAzgqRd)" class="o5h2uacjl"/><path fill="url(#io9PJmc)" class="gn11tcy3b"/><path fill="url(#iSgoWuc)" class="gn11tcy3b"/><path fill="url(#irhrKJd)" class="afkbj2bpi"/><path fill="url(#iCx0Tte)" class="afkbj2bpi"/><path fill="url(#ineSSqd)" class="j6lc18p3u"/><path fill="url(#iccF5db)" class="j6lc18p3u"/><path fill="url(#iRdPPIe)" class="f-t1dub-m"/><path fill="url(#i2DeBNd)" class="f-t1dub-m"/><g filter="url(#iCATzbd)"><path fill="url(#iBQ8bPK)" class="ake9zwv9x"/></g><path fill="url(#iFNCXFd)" class="ake9zwv9x"/><path fill="url(#i7KQLYc)" class="ake9zwv9x"/><g filter="url(#i4iaLRq)"><path fill="url(#ihRbYMe)" class="mumsttbgm"/><path fill="url(#iLJWATd)" class="mumsttbgm"/><path fill="url(#iGxisId)" class="mumsttbgm"/></g><g filter="url(#iPdGfDb)"><path fill="url(#ijo2C8d)" class="frkl8qbse"/><path fill="url(#i7fgAGd)" class="frkl8qbse"/><path fill="url(#iXEGpdb)" class="frkl8qbse"/></g><g filter="url(#ih1cuNO)"><path fill="url(#idiDjBc)" class="m-685zble"/><path fill="url(#iHHz0lC)" class="m-685zble"/><path fill="url(#i1S8d8d)" class="m-685zble"/></g><g filter="url(#imvda9b)"><path fill="url(#itnMJcc)" class="hiyqxbtjr"/><path fill="url(#iSjgh9d)" class="hiyqxbtjr"/></g><g filter="url(#iKwCafb)"><path fill="url(#iriG3Ce)" class="yh2b13b_m"/><path fill="url(#iSB1L4b)" class="yh2b13b_m"/></g><g filter="url(#iFuANcb)"><path fill="url(#iEnfONd)" class="ri4-1bcjk"/><path fill="url(#id1FYXi)" class="ri4-1bcjk"/></g><g filter="url(#iaS3vIB)"><path fill="url(#iULeWQd)" class="by3jo0bqp"/><path fill="url(#irRLyMc)" class="by3jo0bqp"/></g><g filter="url(#isc1h1q)"><path fill="url(#iIpC4EE)" class="bgykamudo"/><path fill="url(#iVPsq8E)" class="bgykamudo"/></g><g filter="url(#i1AvAhd)"><path fill="url(#i3ZZwee)" class="efly_tm8r"/><path fill="url(#ioCZa5d)" class="efly_tm8r"/></g><path fill="url(#iKjgdSP)" class="b-sd8ybpz"/><path fill="url(#iDvMUic)" class="wgg8antiz"/><path fill="url(#iCqS2bc)" class="pahyyrbmv"/><defs><linearGradient id="iWN4Sfc" x1="2.502" x2="2.502" y1="29.436" y2="20.563" gradientUnits="userSpaceOnUse"><stop offset=".078" class="moqgq3t1e"/><stop offset="1" class="trlipgzlf"/></linearGradient><linearGradient id="i5elQvc" x1="1.895" x2="2.5" y1="27.452" y2="27.452" gradientUnits="userSpaceOnUse"><stop class="s3hekpbut"/><stop offset="1" class="i3rpc-b1d"/></linearGradient><linearGradient id="i0f2vge" x1="5.502" x2="5.502" y1="29.436" y2="21.442" gradientUnits="userSpaceOnUse"><stop offset=".078" class="moqgq3t1e"/><stop offset="1" class="trlipgzlf"/></linearGradient><linearGradient id="ifCCrHe" x1="4.895" x2="5.5" y1="27.649" y2="27.649" gradientUnits="userSpaceOnUse"><stop class="s3hekpbut"/><stop offset="1" class="i3rpc-b1d"/></linearGradient><linearGradient id="iiCiV1A" x1="8.502" x2="8.502" y1="29.436" y2="21.442" gradientUnits="userSpaceOnUse"><stop offset=".078" class="moqgq3t1e"/><stop offset="1" class="trlipgzlf"/></linearGradient><linearGradient id="iCHWUko" x1="7.895" x2="8.5" y1="27.649" y2="27.649" gradientUnits="userSpaceOnUse"><stop class="s3hekpbut"/><stop offset="1" class="i3rpc-b1d"/></linearGradient><linearGradient id="iysHjQb" x1="11.502" x2="11.502" y1="29.436" y2="20.293" gradientUnits="userSpaceOnUse"><stop offset=".078" class="moqgq3t1e"/><stop offset=".746" class="trlipgzlf"/><stop offset="1" class="okmp_jbqp"/></linearGradient><linearGradient id="iVplQEc" x1="10.895" x2="11.5" y1="27.392" y2="27.392" gradientUnits="userSpaceOnUse"><stop class="s3hekpbut"/><stop offset="1" class="i3rpc-b1d"/></linearGradient><linearGradient id="iTJHU0d" x1="14.502" x2="14.5" y1="29.435" y2="19.156" gradientUnits="userSpaceOnUse"><stop offset=".078" class="moqgq3t1e"/><stop offset=".669" class="trlipgzlf"/><stop offset="1" class="okmp_jbqp"/></linearGradient><linearGradient id="iea7pDc" x1="13.895" x2="14.5" y1="26.978" y2="26.978" gradientUnits="userSpaceOnUse"><stop class="s3hekpbut"/><stop offset="1" class="i3rpc-b1d"/></linearGradient><linearGradient id="ipOAjVd" x1="17.502" x2="17.499" y1="29.434" y2="16.314" gradientUnits="userSpaceOnUse"><stop offset=".078" class="moqgq3t1e"/><stop offset=".669" class="trlipgzlf"/><stop offset="1" class="bqrosnb4b"/></linearGradient><linearGradient id="iAzgqRd" x1="16.895" x2="17.5" y1="26.297" y2="26.297" gradientUnits="userSpaceOnUse"><stop class="s3hekpbut"/><stop offset="1" class="i3rpc-b1d"/></linearGradient><linearGradient id="io9PJmc" x1="20.502" x2="20.498" y1="29.432" y2="13.5" gradientUnits="userSpaceOnUse"><stop offset=".078" class="moqgq3t1e"/><stop offset=".596" class="trlipgzlf"/><stop offset="1" class="x105v95_h"/></linearGradient><linearGradient id="iSgoWuc" x1="19.895" x2="20.5" y1="25.623" y2="25.623" gradientUnits="userSpaceOnUse"><stop class="s3hekpbut"/><stop offset="1" class="i3rpc-b1d"/></linearGradient><linearGradient id="irhrKJd" x1="23.502" x2="23.497" y1="29.431" y2="10.602" gradientUnits="userSpaceOnUse"><stop offset=".078" class="moqgq3t1e"/><stop offset=".596" class="trlipgzlf"/><stop offset="1" class="x105v95_h"/></linearGradient><linearGradient id="iCx0Tte" x1="22.895" x2="23.5" y1="24.929" y2="24.929" gradientUnits="userSpaceOnUse"><stop class="s3hekpbut"/><stop offset="1" class="i3rpc-b1d"/></linearGradient><linearGradient id="ineSSqd" x1="26.502" x2="26.495" y1="29.43" y2="7.844" gradientUnits="userSpaceOnUse"><stop offset=".078" class="moqgq3t1e"/><stop offset=".596" class="trlipgzlf"/><stop offset="1" class="x105v95_h"/></linearGradient><linearGradient id="iccF5db" x1="25.895" x2="26.714" y1="24.269" y2="24.269" gradientUnits="userSpaceOnUse"><stop class="s3hekpbut"/><stop offset="1" class="i3rpc-b1d"/></linearGradient><linearGradient id="iRdPPIe" x1="29.502" x2="29.494" y1="29.429" y2="6.068" gradientUnits="userSpaceOnUse"><stop offset=".078" class="moqgq3t1e"/><stop offset=".596" class="trlipgzlf"/><stop offset="1" class="x314i0b3r"/></linearGradient><linearGradient id="i2DeBNd" x1="28.895" x2="29.718" y1="23.844" y2="23.844" gradientUnits="userSpaceOnUse"><stop class="p88ao9bgr"/><stop offset="1" class="i3rpc-b1d"/></linearGradient><linearGradient id="iBQ8bPK" x1="7.162" x2="30" y1="21.165" y2="4.041" gradientUnits="userSpaceOnUse"><stop class="uhavagayn"/><stop offset="1" class="lnjtmnhja"/></linearGradient><linearGradient id="iFNCXFd" x1="30.327" x2="26.831" y1="4.681" y2="6.583" gradientUnits="userSpaceOnUse"><stop class="o_upf54xn"/><stop offset="1" class="a6kdbo2ek"/></linearGradient><linearGradient id="i7KQLYc" x1="1.59" x2="3.955" y1="21.182" y2="21.696" gradientUnits="userSpaceOnUse"><stop class="kqrstabpc"/><stop offset="1" class="cu1e7r0sm"/></linearGradient><linearGradient id="ihRbYMe" x1="14.75" x2="11.897" y1="14.345" y2="16.941" gradientUnits="userSpaceOnUse"><stop class="mt447n9gl"/><stop offset="1" class="r-kncdbtk"/></linearGradient><linearGradient id="ijo2C8d" x1="19.115" x2="16.262" y1="9.98" y2="12.577" gradientUnits="userSpaceOnUse"><stop class="mt447n9gl"/><stop offset="1" class="r-kncdbtk"/></linearGradient><linearGradient id="idiDjBc" x1="23.517" x2="20.664" y1="5.597" y2="8.193" gradientUnits="userSpaceOnUse"><stop class="mt447n9gl"/><stop offset="1" class="r-kncdbtk"/></linearGradient><linearGradient id="itnMJcc" x1="14.729" x2="16.296" y1="14.896" y2="14.896" gradientUnits="userSpaceOnUse"><stop class="xr-bdcc4w"/><stop offset="1" class="fs0jh2bua"/></linearGradient><linearGradient id="iriG3Ce" x1="19.094" x2="20.661" y1="10.531" y2="10.531" gradientUnits="userSpaceOnUse"><stop class="xr-bdcc4w"/><stop offset="1" class="fs0jh2bua"/></linearGradient><linearGradient id="iEnfONd" x1="23.496" x2="25.063" y1="6.148" y2="6.148" gradientUnits="userSpaceOnUse"><stop class="xr-bdcc4w"/><stop offset="1" class="fs0jh2bua"/></linearGradient><linearGradient id="iULeWQd" x1="12.859" x2="14.426" y1="16.766" y2="16.766" gradientUnits="userSpaceOnUse"><stop class="xr-bdcc4w"/><stop offset="1" class="fs0jh2bua"/></linearGradient><linearGradient id="iIpC4EE" x1="17.224" x2="18.791" y1="12.401" y2="12.401" gradientUnits="userSpaceOnUse"><stop class="xr-bdcc4w"/><stop offset="1" class="fs0jh2bua"/></linearGradient><linearGradient id="i3ZZwee" x1="21.626" x2="23.193" y1="8.018" y2="8.018" gradientUnits="userSpaceOnUse"><stop class="xr-bdcc4w"/><stop offset="1" class="fs0jh2bua"/></linearGradient><linearGradient id="iKjgdSP" x1="15.573" x2="20.3" y1="13.136" y2="8.409" gradientUnits="userSpaceOnUse"><stop class="aa_-lupwk"/><stop offset=".297" class="bkr41wgxu"/><stop offset=".543" class="bkr41wgxu"/><stop offset="1" class="irzzoht0t"/></linearGradient><linearGradient id="iDvMUic" x1="11.22" x2="15.947" y1="17.511" y2="12.784" gradientUnits="userSpaceOnUse"><stop class="aa_-lupwk"/><stop offset=".297" class="bkr41wgxu"/><stop offset=".543" class="bkr41wgxu"/><stop offset="1" class="irzzoht0t"/></linearGradient><linearGradient id="iCqS2bc" x1="19.978" x2="24.705" y1="8.751" y2="4.025" gradientUnits="userSpaceOnUse"><stop class="aa_-lupwk"/><stop offset=".297" class="bkr41wgxu"/><stop offset=".543" class="bkr41wgxu"/><stop offset="1" class="irzzoht0t"/></linearGradient><radialGradient id="i7hWpce" cx="0" cy="0" r="1" gradientTransform="rotate(-46.572 31.876 15.97)scale(7.60892 5.044)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="lg0mssbev"/><stop offset=".969" class="t2g9f8bvt"/></radialGradient><radialGradient id="iPEeqjN" cx="0" cy="0" r="1" gradientTransform="matrix(5.23065 -4.97831 3.3011 3.46842 1.366 28.27)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="lg0mssbev"/><stop offset=".969" class="t2g9f8bvt"/></radialGradient><radialGradient id="ihcCgTf" cx="0" cy="0" r="1" gradientTransform="rotate(-50.06 32.928 9.383)scale(7.66575 5.08313)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="lg0mssbev"/><stop offset=".969" class="t2g9f8bvt"/></radialGradient><radialGradient id="iLJWATd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10816 .72388 -.6425 -.096 13.624 16.98)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="m2np4rh_j"/><stop offset="1" class="notd3ablm"/></radialGradient><radialGradient id="iGxisId" cx="0" cy="0" r="1" gradientTransform="matrix(-.22237 .76015 -.67468 -.19737 15.52 15.15)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="wropj44af"/><stop offset="1" class="v7f5krbhf"/></radialGradient><radialGradient id="i7fgAGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10816 .72388 -.6425 -.096 17.988 12.615)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="m2np4rh_j"/><stop offset="1" class="notd3ablm"/></radialGradient><radialGradient id="iXEGpdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.22237 .76015 -.67468 -.19737 19.886 10.784)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="wropj44af"/><stop offset="1" class="v7f5krbhf"/></radialGradient><radialGradient id="iHHz0lC" cx="0" cy="0" r="1" gradientTransform="matrix(-.10816 .72388 -.6425 -.096 22.39 8.232)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="m2np4rh_j"/><stop offset="1" class="notd3ablm"/></radialGradient><radialGradient id="i1S8d8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.22237 .76015 -.67468 -.19737 24.287 6.401)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="wropj44af"/><stop offset="1" class="v7f5krbhf"/></radialGradient><radialGradient id="iSjgh9d" cx="0" cy="0" r="1" gradientTransform="matrix(1.19858 -.04672 .03863 .9909 14.976 14.942)" gradientUnits="userSpaceOnUse"><stop offset=".806" class="mw3n4_weu"/><stop offset="1" class="h09ap-boe"/></radialGradient><radialGradient id="iSB1L4b" cx="0" cy="0" r="1" gradientTransform="matrix(1.19858 -.04672 .03863 .9909 19.34 10.578)" gradientUnits="userSpaceOnUse"><stop offset=".806" class="mw3n4_weu"/><stop offset="1" class="h09ap-boe"/></radialGradient><radialGradient id="id1FYXi" cx="0" cy="0" r="1" gradientTransform="matrix(1.19858 -.04672 .03863 .9909 23.743 6.195)" gradientUnits="userSpaceOnUse"><stop offset=".806" class="mw3n4_weu"/><stop offset="1" class="h09ap-boe"/></radialGradient><radialGradient id="irRLyMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.19858 -.04672 .03863 .99091 13.106 16.812)" gradientUnits="userSpaceOnUse"><stop offset=".806" class="mw3n4_weu"/><stop offset="1" class="h09ap-boe"/></radialGradient><radialGradient id="iVPsq8E" cx="0" cy="0" r="1" gradientTransform="matrix(1.19858 -.04672 .03863 .99091 17.47 12.448)" gradientUnits="userSpaceOnUse"><stop offset=".806" class="mw3n4_weu"/><stop offset="1" class="h09ap-boe"/></radialGradient><radialGradient id="ioCZa5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.19858 -.04672 .03863 .99091 21.873 8.065)" gradientUnits="userSpaceOnUse"><stop offset=".806" class="mw3n4_weu"/><stop offset="1" class="h09ap-boe"/></radialGradient><filter id="iCATzbd" width="28" height="19.53" x="2" y="3.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.258824 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.184314 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8705" result="effect2_innerShadow_18_8705"/></filter><filter id="i4iaLRq" width="5.15" height="5.15" x="11.186" y="12.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.341176 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8705"/></filter><filter id="iPdGfDb" width="5.15" height="5.15" x="15.551" y="7.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.341176 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8705"/></filter><filter id="ih1cuNO" width="5.15" height="5.15" x="19.953" y="3.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.341176 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8705"/></filter><filter id="imvda9b" width="1.32" height="1.32" x="14.976" y="14.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.0784314 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8705"/></filter><filter id="iKwCafb" width="1.32" height="1.32" x="19.341" y="9.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.0784314 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8705"/></filter><filter id="iFuANcb" width="1.32" height="1.32" x="23.743" y="5.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.0784314 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8705"/></filter><filter id="iaS3vIB" width="1.32" height="1.32" x="13.106" y="16.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.0784314 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8705"/></filter><filter id="isc1h1q" width="1.32" height="1.32" x="17.471" y="11.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.0784314 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8705"/></filter><filter id="i1AvAhd" width="1.32" height="1.32" x="21.873" y="7.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.0784314 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8705"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:roller-coaster" /></template>
<style>
.a6kdbo2ek {
  stop-color: var(--svg-color--f87c3f, #F87C3F);
  stop-opacity: 0;
}

.aa_-lupwk {
  stop-color: var(--svg-color--b88028, #B88028);
}

.afkbj2bpi {
  d: path("M23 9.29h1v20.15h-1z");
}

.ake9zwv9x {
  d: path("M24.67 6.8L13.31 18.16c-3 3-7.54 3.74-11.31 1.93v2.16c1.39.54 2.84.82 4.28.82c3.08 0 6.13-1.2 8.44-3.5L26.08 8.21A7.9 7.9 0 0 1 30 6.07V4.04a9.76 9.76 0 0 0-5.33 2.76");
}

.b-sd8ybpz {
  d: path("M15.67 12.344c.06.13.127.25.238.36s.248.209.378.269l4.27-4.282a1.26 1.26 0 0 0-.627-.61z");
}

.bgykamudo {
  d: path("M18.13 13.061a.66.66 0 1 0 0-1.32a.66.66 0 0 0 0 1.32");
}

.bkr41wgxu {
  stop-color: var(--svg-color--f3bd41, #F3BD41);
}

.bqrosnb4b {
  stop-color: var(--svg-color--999299, #999299);
}

.by3jo0bqp {
  d: path("M13.766 17.426a.66.66 0 1 0 0-1.32a.66.66 0 0 0 0 1.32");
}

.cu1e7r0sm {
  stop-color: var(--svg-color--f5503e, #F5503E);
  stop-opacity: 0;
}

.d7cydccmc {
  d: path("M2 20.56h1v8.88H2z");
}

.efly_tm8r {
  d: path("M22.533 8.678a.66.66 0 1 0 0-1.32a.66.66 0 0 0 0 1.32");
}

.ej-qbfntw {
  d: path("M14 18.44h1v11h-1z");
}

.f-t1dub-m {
  d: path("M29 4.44h1v25h-1z");
}

.frkl8qbse {
  d: path("m20.31 10.221l-2.5 2.5c-.52.52-1.35.52-1.87 0s-.52-1.35 0-1.87l2.5-2.5c.52-.52 1.35-.52 1.87 0c.52.51.52 1.35 0 1.87");
}

.fs0jh2bua {
  stop-color: var(--svg-color--3b325e, #3B325E);
}

.ft5dv1b6b {
  fill: none;
}

.gn11tcy3b {
  d: path("M20 12.39h1v17.05h-1z");
}

.h09ap-boe {
  stop-color: var(--svg-color--3e3d66, #3E3D66);
}

.hiyqxbtjr {
  d: path("M15.636 15.556a.66.66 0 1 0 0-1.32a.66.66 0 0 0 0 1.32");
}

.i3rpc-b1d {
  stop-color: var(--svg-color--706c72, #706C72);
  stop-opacity: 0;
}

.irzzoht0t {
  stop-color: var(--svg-color--ff7449, #FF7449);
}

.j6lc18p3u {
  d: path("M26 6.34h1v23.1h-1z");
}

.kqrstabpc {
  stop-color: var(--svg-color--f5503e, #F5503E);
}

.lg0mssbev {
  stop-color: var(--svg-color--6f4e62, #6F4E62);
  stop-opacity: 0;
}

.lnjtmnhja {
  stop-color: var(--svg-color--f8783e, #F8783E);
}

.m-685zble {
  d: path("m24.713 5.838l-2.5 2.5c-.52.52-1.35.52-1.87 0s-.52-1.35 0-1.87l2.5-2.5c.52-.52 1.35-.52 1.87 0c.52.51.52 1.35 0 1.87");
}

.m2np4rh_j {
  stop-color: var(--svg-color--8b381a, #8B381A);
}

.moqgq3t1e {
  stop-color: var(--svg-color--d8cede, #D8CEDE);
}

.mt447n9gl {
  stop-color: var(--svg-color--ed4a30, #ED4A30);
}

.mumsttbgm {
  d: path("m15.946 14.586l-2.5 2.5c-.52.52-1.35.52-1.87 0s-.52-1.35 0-1.87l2.5-2.5c.52-.52 1.35-.52 1.87 0c.52.51.52 1.35 0 1.87");
}

.mw3n4_weu {
  stop-color: var(--svg-color--3e3d66, #3E3D66);
  stop-opacity: 0;
}

.notd3ablm {
  stop-color: var(--svg-color--8b381a, #8B381A);
  stop-opacity: 0;
}

.o_upf54xn {
  stop-color: var(--svg-color--f87c3f, #F87C3F);
}

.o5h2uacjl {
  d: path("M17 15.4h1v14.04h-1z");
}

.okmp_jbqp {
  stop-color: var(--svg-color--998d96, #998D96);
}

.p88ao9bgr {
  stop-color: var(--svg-color--5e565e, #5E565E);
}

.pahyyrbmv {
  d: path("M20.074 7.96c.06.13.128.249.238.359s.25.21.38.27l4.269-4.282a1.26 1.26 0 0 0-.627-.61z");
}

.r-kncdbtk {
  stop-color: var(--svg-color--d77226, #D77226);
}

.ri4-1bcjk {
  d: path("M24.403 6.808a.66.66 0 1 0 0-1.32a.66.66 0 0 0 0 1.32");
}

.s3hekpbut {
  stop-color: var(--svg-color--706c72, #706C72);
}

.sxsuk1blc {
  d: path("M8 21.44h1v8H8z");
}

.t2g9f8bvt {
  stop-color: var(--svg-color--6f4e62, #6F4E62);
}

.trlipgzlf {
  stop-color: var(--svg-color--a091a0, #A091A0);
}

.uhavagayn {
  stop-color: var(--svg-color--f24d3b, #F24D3B);
}

.v7f5krbhf {
  stop-color: var(--svg-color--8b110a, #8B110A);
  stop-opacity: 0;
}

.wgg8antiz {
  d: path("M11.316 16.719c.06.13.129.25.239.36s.249.209.379.269l4.27-4.282a1.26 1.26 0 0 0-.628-.61z");
}

.wropj44af {
  stop-color: var(--svg-color--8b110a, #8B110A);
}

.wsr13_byj {
  d: path("M11 20.29h1v9.15h-1z");
}

.x105v95_h {
  stop-color: var(--svg-color--8a7d87, #8A7D87);
}

.x314i0b3r {
  stop-color: var(--svg-color--8d858d, #8D858D);
}

.xr-bdcc4w {
  stop-color: var(--svg-color--412654, #412654);
}

.yh2b13b_m {
  d: path("M20 11.191a.66.66 0 1 0 0-1.32a.66.66 0 0 0 0 1.32");
}

.z6_fct6lh {
  d: path("M5 21.44h1v8H5z");
}

</style>
