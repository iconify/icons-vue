<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#ik0iUJd)" class="l8cum4sxr"/><rect fill="url(#ivA4fle)" class="l8cum4sxr"/><path stroke="url(#iFZFXle)" class="nvsfs5b2l"/><path stroke="url(#iQOlTMc)" class="nvsfs5b2l"/><g filter="url(#ihkDznd)"><path stroke="url(#ioxybsc)" class="hq6iscb8l"/></g><g filter="url(#ixyVGZb)"><rect class="zf05a8q1v"/><rect fill="url(#izzlGqd)" class="cb_008w7x"/><rect fill="url(#iQcgB1M)" class="cb_008w7x"/></g><rect fill="url(#i8h1tCb)" class="mf-5aeb2x"/><rect fill="url(#ikWDk3b)" class="mf-5aeb2x"/><g filter="url(#iDWaPDR)"><rect class="r61ssl6-a"/><rect fill="url(#ihPMZBb)" class="e33pozb1o"/><rect fill="url(#i0IKkwG)" class="e33pozb1o"/></g><g filter="url(#iYDONGv)"><circle fill="url(#icxlOic)" class="a9b89d7so"/></g><g filter="url(#iiCZCZd)"><rect fill="url(#iUhg7Od)" class="tx-w95bbw"/><rect fill="url(#ipOGitc)" class="tx-w95bbw"/></g><g filter="url(#iXEg4sY)" class="arv8vqxqi"><rect stroke="url(#ilSQ6rb)" class="ibvva4bsu"/><rect stroke="url(#iQpOsdx)" class="ibvva4bsu"/></g><g filter="url(#iSqYpId)"><path stroke="url(#i5q6cSb)" class="d0v6baccz"/></g><g filter="url(#iSqYpId)" class="z6cgjeu-u"><path stroke="url(#i5q6cSb)" class="azpvhrbnp"/><path stroke="url(#iyGaw7b)" class="azpvhrbnp"/></g><g filter="url(#ikuY9ae)" class="z6cgjeu-u"><path stroke="url(#icmsRdK)" class="wrt700b-e"/><path stroke="url(#ijvoagb)" class="wrt700b-e"/></g><g filter="url(#ifFkUGb)" class="z6cgjeu-u"><path stroke="url(#iHGsrpd)" class="gajms78jv"/><path stroke="url(#iGv0foP)" class="gajms78jv"/></g><g filter="url(#iWl22Pd)" class="z6cgjeu-u"><path stroke="url(#iLd55IQ)" class="ay0wur3sp"/><path stroke="url(#i4hlXve)" class="ay0wur3sp"/></g><g filter="url(#iUn7qEb)" class="z6cgjeu-u"><path stroke="url(#iyxlfNc)" class="n948od8rs"/><path stroke="url(#i8oMEee)" class="n948od8rs"/></g><g filter="url(#iNS7fWd)"><path fill="url(#imbayBd)" class="lsmjfbfxv"/></g><g filter="url(#i1NVumf)"><path fill="url(#irDJ20c)" class="byvfl01ci"/></g><g filter="url(#ipAbYpd)"><path fill="url(#iPD0dFc)" class="a8q0gc12f"/></g><g filter="url(#iCVwtPy)"><path fill="url(#itbmJ8d)" class="ohhqm-i_b"/></g><g filter="url(#ipxbyOc)"><path fill="url(#iEXk1tb)" class="f8t6zybdm"/></g><g filter="url(#is7YIFd)"><rect fill="url(#iyT12hb)" class="ibvva4bsu"/><rect fill="url(#iBeQbCe)" class="ibvva4bsu"/></g><path fill="url(#ilvT7ke)" class="p3g7swbvj"/><g filter="url(#ipvMNfj)"><circle fill="url(#iNZBh0c)" class="e5r4tkuoe"/></g><g filter="url(#ihj3ZFB)"><circle class="gunu-ub0l"/></g><g filter="url(#i6iFpyb)"><circle fill="url(#iJcWuNb)" class="uqaik-rfg"/></g><g filter="url(#i8UZyZc)"><circle class="x8o6aibfu"/></g><g filter="url(#iXR3DAe)"><circle fill="url(#iZOumVd)" class="bbq1o_1pz"/></g><g filter="url(#iPdOGyb)"><circle class="jm91ibb8u"/></g><g filter="url(#imxgdrd)"><circle fill="url(#ieLlWQc)" class="xqe81l56g"/></g><g filter="url(#iDafRWb)"><circle class="gvskrr_ao"/></g><circle fill="url(#icpAFYd)" class="e2nqc3b9w"/><circle fill="url(#ik79yce)" class="e2nqc3b9w"/><defs><linearGradient id="ik0iUJd" x1="6.909" x2="5.253" y1="29.25" y2="29.25" gradientUnits="userSpaceOnUse"><stop class="f-mzv3bsj"/><stop offset="1" class="njwa_9bvj"/></linearGradient><linearGradient id="ivA4fle" x1="6.445" x2="6.445" y1="27.531" y2="28.689" gradientUnits="userSpaceOnUse"><stop offset=".393" class="hoghk3b6d"/><stop offset="1" class="xx31eob4m"/></linearGradient><linearGradient id="iFZFXle" x1="10.847" x2="25.566" y1="9.281" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="q2fy04bfd"/><stop offset="1" class="ftsn9eb1w"/></linearGradient><linearGradient id="ioxybsc" x1="11.159" x2="25.734" y1="9.031" y2="5.906" gradientUnits="userSpaceOnUse"><stop class="kpf9k5tdf"/><stop offset="1" class="xp31vug9r"/></linearGradient><linearGradient id="iQcgB1M" x1="6.445" x2="6.445" y1="27.531" y2="28.437" gradientUnits="userSpaceOnUse"><stop offset=".393" class="hoghk3b6d"/><stop offset="1" class="xx31eob4m"/></linearGradient><linearGradient id="i8h1tCb" x1="25.932" x2="24.276" y1="29.25" y2="29.25" gradientUnits="userSpaceOnUse"><stop class="f-mzv3bsj"/><stop offset="1" class="njwa_9bvj"/></linearGradient><linearGradient id="ikWDk3b" x1="25.468" x2="25.468" y1="27.531" y2="28.689" gradientUnits="userSpaceOnUse"><stop offset=".393" class="hoghk3b6d"/><stop offset="1" class="xx31eob4m"/></linearGradient><linearGradient id="i0IKkwG" x1="25.468" x2="25.468" y1="27.531" y2="28.437" gradientUnits="userSpaceOnUse"><stop offset=".393" class="hoghk3b6d"/><stop offset="1" class="xx31eob4m"/></linearGradient><linearGradient id="iUhg7Od" x1="29.938" x2="5.154" y1="21.794" y2="21.794" gradientUnits="userSpaceOnUse"><stop class="n75uffspr"/><stop offset="1" class="ufgly3b4r"/></linearGradient><linearGradient id="ipOGitc" x1="17.627" x2="17.627" y1="27.523" y2="25.053" gradientUnits="userSpaceOnUse"><stop class="p5r0ob3nv"/><stop offset="1" class="wkmyl-b6s"/></linearGradient><linearGradient id="ilSQ6rb" x1="22.391" x2="22.391" y1="13.383" y2="21.063" gradientUnits="userSpaceOnUse"><stop class="gs6wamrpu"/><stop offset="1" class="hj4wxbt4g"/></linearGradient><linearGradient id="i5q6cSb" x1="10.051" x2="10.051" y1="13.383" y2="14.742" gradientUnits="userSpaceOnUse"><stop class="ch40kpb8t"/><stop offset="1" class="ss6cgdcdo"/></linearGradient><linearGradient id="icmsRdK" x1="10.051" x2="10.051" y1="15.883" y2="17.242" gradientUnits="userSpaceOnUse"><stop class="ch40kpb8t"/><stop offset="1" class="ss6cgdcdo"/></linearGradient><linearGradient id="iHGsrpd" x1="10.051" x2="10.051" y1="18.383" y2="19.742" gradientUnits="userSpaceOnUse"><stop class="ch40kpb8t"/><stop offset="1" class="ss6cgdcdo"/></linearGradient><linearGradient id="iLd55IQ" x1="10.051" x2="10.051" y1="20.883" y2="22.242" gradientUnits="userSpaceOnUse"><stop class="ch40kpb8t"/><stop offset="1" class="ss6cgdcdo"/></linearGradient><linearGradient id="iyxlfNc" x1="10.051" x2="10.051" y1="23.383" y2="24.742" gradientUnits="userSpaceOnUse"><stop class="ch40kpb8t"/><stop offset="1" class="ss6cgdcdo"/></linearGradient><linearGradient id="imbayBd" x1="6.097" x2="18.441" y1="14.531" y2="14.531" gradientUnits="userSpaceOnUse"><stop class="mcx-20r5v"/><stop offset="1" class="o_7jxmbic"/></linearGradient><linearGradient id="irDJ20c" x1="6.097" x2="18.441" y1="17.031" y2="17.031" gradientUnits="userSpaceOnUse"><stop class="mcx-20r5v"/><stop offset="1" class="o_7jxmbic"/></linearGradient><linearGradient id="iPD0dFc" x1="6.097" x2="18.441" y1="19.531" y2="19.531" gradientUnits="userSpaceOnUse"><stop class="mcx-20r5v"/><stop offset="1" class="o_7jxmbic"/></linearGradient><linearGradient id="itbmJ8d" x1="6.097" x2="18.441" y1="22.031" y2="22.031" gradientUnits="userSpaceOnUse"><stop class="mcx-20r5v"/><stop offset="1" class="o_7jxmbic"/></linearGradient><linearGradient id="iEXk1tb" x1="6.097" x2="18.441" y1="24.531" y2="24.531" gradientUnits="userSpaceOnUse"><stop class="mcx-20r5v"/><stop offset="1" class="o_7jxmbic"/></linearGradient><linearGradient id="iyT12hb" x1="22.391" x2="22.391" y1="14.438" y2="20.594" gradientUnits="userSpaceOnUse"><stop class="evf5x89oy"/><stop offset="1" class="o4-0ubczr"/></linearGradient><linearGradient id="iBeQbCe" x1="30.284" x2="24.628" y1="20.813" y2="20.813" gradientUnits="userSpaceOnUse"><stop class="wv_0q8btm"/><stop offset="1" class="m6cyogbvs"/></linearGradient><linearGradient id="ilvT7ke" x1="19.5" x2="20.766" y1="19.594" y2="19.594" gradientUnits="userSpaceOnUse"><stop class="qkz8bcboa"/><stop offset="1" class="uecn5sgvb"/></linearGradient><linearGradient id="iNZBh0c" x1="20.904" x2="18.657" y1="21.95" y2="24.695" gradientUnits="userSpaceOnUse"><stop offset=".585" class="ulz1rmdql"/><stop offset="1" class="f9-1h0b8w"/></linearGradient><linearGradient id="iJcWuNb" x1="26.427" x2="24.18" y1="21.95" y2="24.695" gradientUnits="userSpaceOnUse"><stop offset=".585" class="ulz1rmdql"/><stop offset="1" class="f9-1h0b8w"/></linearGradient><linearGradient id="iZOumVd" x1="20.628" x2="18.878" y1="22.469" y2="24.699" gradientUnits="userSpaceOnUse"><stop class="uvxqw-7gi"/><stop offset="1" class="syr9dobky"/></linearGradient><linearGradient id="ieLlWQc" x1="26.151" x2="24.401" y1="22.469" y2="24.699" gradientUnits="userSpaceOnUse"><stop class="uvxqw-7gi"/><stop offset="1" class="syr9dobky"/></linearGradient><filter id="ihkDznd" width="18.378" height="4.417" x="7.631" y="5.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".125"/></filter><filter id="ixyVGZb" width="2.413" height="4.244" x="5.239" y="25.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".15"/></filter><filter id="iDWaPDR" width="2.413" height="4.244" x="24.262" y="25.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".15"/></filter><filter id="iYDONGv" width="4.281" height="4.281" x="4.789" y="8.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.8 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18417"/></filter><filter id="iiCZCZd" width="28.675" height="18.238" x="1.663" y="10.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.835294 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18417"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.670588 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18417" result="effect2_innerShadow_18_18417"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.529412 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_18417" result="effect3_innerShadow_18_18417"/></filter><filter id="iXEg4sY" width="12.169" height="9.161" x="16.306" y="12.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".3"/></filter><filter id="iSqYpId" width="11.983" height="2.459" x="4.059" y="12.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".15"/></filter><filter id="ikuY9ae" width="11.983" height="2.459" x="4.059" y="15.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".15"/></filter><filter id="ifFkUGb" width="11.983" height="2.459" x="4.059" y="17.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".15"/></filter><filter id="iWl22Pd" width="11.983" height="2.459" x="4.059" y="20.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".15"/></filter><filter id="iUn7qEb" width="11.983" height="2.459" x="4.059" y="22.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".15"/></filter><filter id="iNS7fWd" width="10.883" height="1.509" x="4.609" y="13.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18417"/></filter><filter id="i1NVumf" width="10.883" height="1.509" x="4.609" y="15.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18417"/></filter><filter id="ipAbYpd" width="10.883" height="1.509" x="4.609" y="18.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18417"/></filter><filter id="iCVwtPy" width="10.883" height="1.509" x="4.609" y="20.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18417"/></filter><filter id="ipxbyOc" width="10.883" height="1.509" x="4.609" y="23.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18417"/></filter><filter id="is7YIFd" width="10.519" height="7.511" x="16.981" y="13.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.517647 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18417"/></filter><filter id="ipvMNfj" width="3.887" height="3.887" x="17.869" y="21.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".15"/></filter><filter id="ihj3ZFB" width="3.193" height="3.193" x="18.216" y="21.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".125"/></filter><filter id="i6iFpyb" width="3.887" height="3.887" x="23.392" y="21.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".15"/></filter><filter id="i8UZyZc" width="3.193" height="3.193" x="23.739" y="21.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".125"/></filter><filter id="iXR3DAe" width="2.406" height="2.406" x="18.609" y="22.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.686275 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18417"/></filter><filter id="iPdOGyb" width="2.406" height="2.406" x="18.609" y="22.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".125"/></filter><filter id="imxgdrd" width="2.406" height="2.406" x="24.133" y="22.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.686275 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18417"/></filter><filter id="iDafRWb" width="2.406" height="2.406" x="24.133" y="22.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18417" stdDeviation=".125"/></filter><radialGradient id="iQOlTMc" cx="0" cy="0" r="1" gradientTransform="rotate(170.538 12.372 4.123)scale(1.14052 3.02854)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="iwh5llgvp"/><stop offset="1" class="aaedd4b6h"/></radialGradient><radialGradient id="izzlGqd" cx="0" cy="0" r="1" gradientTransform="matrix(1.35938 0 0 1.71875 6.081 28.234)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="z5jjkqbho"/><stop offset=".954" class="ch6-c780x"/></radialGradient><radialGradient id="ihPMZBb" cx="0" cy="0" r="1" gradientTransform="matrix(1.35938 0 0 1.71875 25.104 28.234)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="z5jjkqbho"/><stop offset=".954" class="ch6-c780x"/></radialGradient><radialGradient id="icxlOic" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8125 .9375 -.75938 -2.27812 8.16 9.781)" gradientUnits="userSpaceOnUse"><stop class="basn47wnw"/><stop offset=".817" class="uk0oujenw"/></radialGradient><radialGradient id="iQpOsdx" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1.625 5.33572 10.97922 16.566 20.125)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="nj578kbnq"/><stop offset="1" class="nsr-ftbsg"/></radialGradient><radialGradient id="iyGaw7b" cx="0" cy="0" r="1" gradientTransform="rotate(-48.86 18.634 2.07)scale(.9025 3.16679)" gradientUnits="userSpaceOnUse"><stop class="p9qmafbcm"/><stop offset="1" class="mq4tp-0hn"/></radialGradient><radialGradient id="ijvoagb" cx="0" cy="0" r="1" gradientTransform="rotate(-48.86 21.386 3.32)scale(.9025 3.16679)" gradientUnits="userSpaceOnUse"><stop class="p9qmafbcm"/><stop offset="1" class="mq4tp-0hn"/></radialGradient><radialGradient id="iGv0foP" cx="0" cy="0" r="1" gradientTransform="rotate(-48.86 24.138 4.57)scale(.9025 3.16679)" gradientUnits="userSpaceOnUse"><stop class="p9qmafbcm"/><stop offset="1" class="mq4tp-0hn"/></radialGradient><radialGradient id="i4hlXve" cx="0" cy="0" r="1" gradientTransform="rotate(-48.86 26.89 5.82)scale(.9025 3.16679)" gradientUnits="userSpaceOnUse"><stop class="p9qmafbcm"/><stop offset="1" class="mq4tp-0hn"/></radialGradient><radialGradient id="i8oMEee" cx="0" cy="0" r="1" gradientTransform="rotate(-48.86 29.641 7.07)scale(.9025 3.16679)" gradientUnits="userSpaceOnUse"><stop class="p9qmafbcm"/><stop offset="1" class="mq4tp-0hn"/></radialGradient><radialGradient id="icpAFYd" cx="0" cy="0" r="1" gradientTransform="rotate(155.469 12.636 5.562)scale(2.10746)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="v_z3c7b3e"/><stop offset="1" class="l009febdb"/></radialGradient><radialGradient id="ik79yce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08994 .28125 -.13065 -.50633 26.702 5.218)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="ipeblpo2q"/><stop offset="1" class="gzwpog2ac"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:radio" /></template>
<style>
.a8q0gc12f {
  d: path("M4.61 19.063a.68.68 0 0 1 .68-.68h9.523a.68.68 0 1 1 0 1.36H5.289a.68.68 0 0 1-.68-.68");
}

.a9b89d7so {
  cx: 6.93px;
  cy: 10.555px;
  r: 2.141px;
}

.aaedd4b6h {
  stop-color: var(--svg-color--939096, #939096);
  stop-opacity: 0;
}

.arv8vqxqi {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
}

.ay0wur3sp {
  d: path("M4.61 21.563a.68.68 0 0 1 .68-.68h9.523a.68.68 0 1 1 0 1.36H5.289a.68.68 0 0 1-.68-.68Z");
}

.azpvhrbnp {
  d: path("M4.61 14.063a.68.68 0 0 1 .68-.68h9.523a.68.68 0 1 1 0 1.36H5.289a.68.68 0 0 1-.68-.68Z");
}

.basn47wnw {
  stop-color: var(--svg-color--eee, #EEE);
}

.bbq1o_1pz {
  cx: 19.813px;
  cy: 23.496px;
  r: 1.203px;
}

.byvfl01ci {
  d: path("M4.61 16.563a.68.68 0 0 1 .68-.68h9.523a.68.68 0 1 1 0 1.36H5.289a.68.68 0 0 1-.68-.68");
}

.cb_008w7x {
  width: 1.813px;
  height: 3.644px;
  x: 5.539px;
  y: 25.709px;
  rx: 0.906px;
}

.ch40kpb8t {
  stop-color: var(--svg-color--9d90ab, #9D90AB);
}

.ch6-c780x {
  stop-color: var(--svg-color--614d78, #614D78);
}

.d0v6baccz {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M4.61 14.063a.68.68 0 0 1 .68-.68h9.523a.68.68 0 1 1 0 1.36H5.289a.68.68 0 0 1-.68-.68Z");
}

.e2nqc3b9w {
  cx: 25.613px;
  cy: 5.617px;
  r: 1.09px;
}

.e33pozb1o {
  width: 1.813px;
  height: 3.644px;
  x: 24.562px;
  y: 25.709px;
  rx: 0.906px;
}

.e5r4tkuoe {
  cx: 19.813px;
  cy: 23.496px;
  r: 1.644px;
}

.evf5x89oy {
  stop-color: var(--svg-color--56d3ff, #56D3FF);
}

.f-mzv3bsj {
  stop-color: var(--svg-color--56307a, #56307A);
}

.f8t6zybdm {
  d: path("M4.61 24.063a.68.68 0 0 1 .68-.68h9.523a.68.68 0 1 1 0 1.36H5.289a.68.68 0 0 1-.68-.68");
}

.f9-1h0b8w {
  stop-color: var(--svg-color--cdc7d3, #CDC7D3);
}

.ft5dv1b6b {
  fill: none;
}

.ftsn9eb1w {
  stop-color: var(--svg-color--929095, #929095);
}

.gajms78jv {
  d: path("M4.61 19.063a.68.68 0 0 1 .68-.68h9.523a.68.68 0 1 1 0 1.36H5.289a.68.68 0 0 1-.68-.68Z");
}

.gs6wamrpu {
  stop-color: var(--svg-color--9f94b4, #9F94B4);
}

.gunu-ub0l {
  cx: 19.813px;
  cy: 23.496px;
  r: 1.347px;
  fill: var(--svg-color--9f98a7, #9F98A7);
}

.gvskrr_ao {
  cx: 25.336px;
  cy: 23.496px;
  r: 0.953px;
  fill: var(--svg-color--e4daef, #E4DAEF);
}

.gzwpog2ac {
  stop-color: var(--svg-color--d3d1d4, #D3D1D4);
  stop-opacity: 0;
}

.hj4wxbt4g {
  stop-color: var(--svg-color--a39eaf, #A39EAF);
}

.hoghk3b6d {
  stop-color: var(--svg-color--4e366a, #4E366A);
}

.hq6iscb8l {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.906 9.281L25.734 5.61");
}

.ibvva4bsu {
  width: 10.219px;
  height: 7.211px;
  x: 17.281px;
  y: 13.383px;
  rx: 1.25px;
}

.ipeblpo2q {
  stop-color: var(--svg-color--d3d1d4, #D3D1D4);
}

.iwh5llgvp {
  stop-color: var(--svg-color--939096, #939096);
}

.jm91ibb8u {
  cx: 19.813px;
  cy: 23.496px;
  r: 0.953px;
  fill: var(--svg-color--e4daef, #E4DAEF);
}

.kpf9k5tdf {
  stop-color: var(--svg-color--b8b8b8, #B8B8B8);
}

.l009febdb {
  stop-color: var(--svg-color--918e95, #918E95);
}

.l8cum4sxr {
  width: 2.672px;
  height: 4.656px;
  x: 5.109px;
  y: 25.203px;
  rx: 1.336px;
}

.lsmjfbfxv {
  d: path("M4.61 14.063a.68.68 0 0 1 .68-.68h9.523a.68.68 0 1 1 0 1.36H5.289a.68.68 0 0 1-.68-.68");
}

.m6cyogbvs {
  stop-color: var(--svg-color--3898d8, #3898D8);
  stop-opacity: 0;
}

.mcx-20r5v {
  stop-color: var(--svg-color--40314e, #40314E);
}

.mf-5aeb2x {
  width: 2.672px;
  height: 4.656px;
  x: 24.133px;
  y: 25.203px;
  rx: 1.336px;
}

.mq4tp-0hn {
  stop-color: var(--svg-color--c9c5ce, #C9C5CE);
  stop-opacity: 0;
}

.n75uffspr {
  stop-color: var(--svg-color--b9b3bf, #B9B3BF);
}

.n948od8rs {
  d: path("M4.61 24.063a.68.68 0 0 1 .68-.68h9.523a.68.68 0 1 1 0 1.36H5.289a.68.68 0 0 1-.68-.68Z");
}

.nj578kbnq {
  stop-color: var(--svg-color--cecbd6, #CECBD6);
}

.njwa_9bvj {
  stop-color: var(--svg-color--57446d, #57446D);
}

.nsr-ftbsg {
  stop-color: var(--svg-color--cecbd6, #CECBD6);
  stop-opacity: 0;
}

.nvsfs5b2l {
  d: path("M7.906 9.281L25.734 5.61");
}

.o_7jxmbic {
  stop-color: var(--svg-color--232026, #232026);
}

.o4-0ubczr {
  stop-color: var(--svg-color--3aacf3, #3AACF3);
}

.ohhqm-i_b {
  d: path("M4.61 21.563a.68.68 0 0 1 .68-.68h9.523a.68.68 0 1 1 0 1.36H5.289a.68.68 0 0 1-.68-.68");
}

.p3g7swbvj {
  d: path("M20.766 20.594H19.14v-3.375a.813.813 0 1 1 1.625 0z");
}

.p5r0ob3nv {
  stop-color: var(--svg-color--baafc6, #BAAFC6);
}

.p9qmafbcm {
  stop-color: var(--svg-color--c9c5ce, #C9C5CE);
}

.q2fy04bfd {
  stop-color: var(--svg-color--aaa, #AAA);
}

.qkz8bcboa {
  stop-color: var(--svg-color--ed3e4e, #ED3E4E);
}

.r61ssl6-a {
  width: 1.813px;
  height: 3.644px;
  x: 24.562px;
  y: 25.709px;
  fill: var(--svg-color--5c4773, #5C4773);
  rx: 0.906px;
}

.ss6cgdcdo {
  stop-color: var(--svg-color--c6c1cb, #C6C1CB);
}

.syr9dobky {
  stop-color: var(--svg-color--c2b3d3, #C2B3D3);
}

.tx-w95bbw {
  width: 27.875px;
  height: 17.438px;
  x: 2.063px;
  y: 10.438px;
  rx: 2.5px;
}

.uecn5sgvb {
  stop-color: var(--svg-color--f03a87, #F03A87);
}

.ufgly3b4r {
  stop-color: var(--svg-color--b9b2c0, #B9B2C0);
}

.uk0oujenw {
  stop-color: var(--svg-color--cfcfcf, #CFCFCF);
}

.ulz1rmdql {
  stop-color: var(--svg-color--aca1b9, #ACA1B9);
}

.uqaik-rfg {
  cx: 25.336px;
  cy: 23.496px;
  r: 1.644px;
}

.uvxqw-7gi {
  stop-color: var(--svg-color--f0ebf7, #F0EBF7);
}

.v_z3c7b3e {
  stop-color: var(--svg-color--bebdbf, #BEBDBF);
}

.wkmyl-b6s {
  stop-color: var(--svg-color--b8acc5, #B8ACC5);
  stop-opacity: 0;
}

.wrt700b-e {
  d: path("M4.61 16.563a.68.68 0 0 1 .68-.68h9.523a.68.68 0 1 1 0 1.36H5.289a.68.68 0 0 1-.68-.68Z");
}

.wv_0q8btm {
  stop-color: var(--svg-color--3898d8, #3898D8);
}

.x8o6aibfu {
  cx: 25.336px;
  cy: 23.496px;
  r: 1.347px;
  fill: var(--svg-color--9f98a7, #9F98A7);
}

.xp31vug9r {
  stop-color: var(--svg-color--b8b8b8, #B8B8B8);
  stop-opacity: 0;
}

.xqe81l56g {
  cx: 25.336px;
  cy: 23.496px;
  r: 1.203px;
}

.xx31eob4m {
  stop-color: var(--svg-color--4e366a, #4E366A);
  stop-opacity: 0;
}

.z5jjkqbho {
  stop-color: var(--svg-color--614d78, #614D78);
  stop-opacity: 0;
}

.z6cgjeu-u {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.zf05a8q1v {
  width: 1.813px;
  height: 3.644px;
  x: 5.539px;
  y: 25.709px;
  fill: var(--svg-color--5c4773, #5C4773);
  rx: 0.906px;
}

</style>
