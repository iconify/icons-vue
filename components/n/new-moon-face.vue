<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iDgJtFc)"><circle fill="url(#io5G63c)" class="t_3aqrb6f"/><circle fill="url(#itm9GVn)" class="t_3aqrb6f"/><circle fill="url(#i1rHXjd)" class="t_3aqrb6f"/></g><path fill="url(#i69Tgac)" class="uwrl8-bdq"/><path fill="url(#idpf1Ti)" class="c3wt19kpr"/><g filter="url(#iVxK2Gb)"><path stroke="url(#iisUNUc)" class="j_a3zb8ef"/></g><path fill="url(#iSJ39Ed)" class="x8f9z44sf"/><path fill="url(#iEsmXuc)" class="x8f9z44sf"/><path fill="url(#iEKbqvW)" class="x8f9z44sf"/><g filter="url(#iXXcPhe)"><path stroke="url(#iXzcW7U)" class="t4kly7nao"/></g><path fill="url(#io7qvyd)" class="yawvdpb6z"/><path fill="url(#icSUxne)" class="yawvdpb6z"/><path fill="url(#iOXTuub)" class="yawvdpb6z"/><path fill="url(#iJzsyye)" class="yawvdpb6z"/><path fill="url(#iX7Yohd)" class="yawvdpb6z"/><g filter="url(#iGnTaCb)"><path stroke="url(#iZ6tu0b)" class="fg2y4kboq"/></g><path fill="url(#iQt65dd)" class="nda4_nbxw"/><path fill="url(#iZ9bBkd)" class="nda4_nbxw"/><path fill="url(#iUYCMwe)" class="nda4_nbxw"/><path class="q-fi78b9v"/><g filter="url(#iypujDb)"><path stroke="url(#inslkXb)" class="hzlukwbtw"/></g><path fill="url(#iAMf2kd)" class="xijkheb_k"/><path fill="url(#iOCUTFb)" class="xijkheb_k"/><path fill="url(#i1rl57d)" class="xijkheb_k"/><path fill="url(#izWcSsd)" class="xijkheb_k"/><path fill="url(#ilO72EG)" class="xijkheb_k"/><g clip-rule="evenodd" filter="url(#i36oQ5d)" class="d2kvgvbvc"><path fill="url(#ixuH4ce)" class="auva9bbhi"/><path fill="url(#iUX1zQb)" class="auva9bbhi"/></g><g clip-rule="evenodd" filter="url(#ihiuydW)" class="d2kvgvbvc"><path fill="url(#igWCmHu)" class="z73u9eb1f"/><path fill="url(#iw1LJCe)" class="z73u9eb1f"/></g><g clip-rule="evenodd" filter="url(#ifH8yIc)" class="d2kvgvbvc"><path fill="url(#iXVf4Ld)" class="spxyxuvuh"/><path fill="url(#iohm3kc)" class="spxyxuvuh"/></g><g clip-rule="evenodd" filter="url(#iD3fGEe)" class="d2kvgvbvc"><path fill="url(#i36WnIe)" class="pbe0wtcwc"/><path fill="url(#iI7mHUc)" class="pbe0wtcwc"/></g><g clip-rule="evenodd" filter="url(#isCfzYc)" class="d2kvgvbvc"><path class="eft8crbxd"/><path fill="url(#i9fYMMe)" class="fsy8nnbto"/><path fill="url(#iXvpAxb)" class="fsy8nnbto"/></g><g filter="url(#iYIvrke)"><path stroke="url(#iOEL93c)" class="wbcbm6bxq"/></g><g filter="url(#i6EuYIe)"><path stroke="url(#iP0ah2c)" class="g9syu8bub"/></g><g filter="url(#iDQ86Jb)"><path stroke="url(#i82f7Mb)" class="wvdncebfp"/></g><g filter="url(#ikXknsc)"><path stroke="url(#iiZYKZb)" class="o0aghtbvl"/></g><g filter="url(#isKGvfb)"><path stroke="url(#iBS37wb)" class="k58qjccse"/></g><defs><radialGradient id="io5G63c" cx="0" cy="0" r="1" gradientTransform="rotate(139.682 8.515 9.833)scale(20.5747 21.3794)" gradientUnits="userSpaceOnUse"><stop class="n0wdc0bol"/><stop offset="1" class="q7f2lrb3g"/></radialGradient><radialGradient id="itm9GVn" cx="0" cy="0" r="1" gradientTransform="matrix(-19.12496 2.84698 -4.5721 -30.71366 21.869 16.1)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="dl-15acrl"/><stop offset="1" class="c_qn-zg1g"/></radialGradient><radialGradient id="i1rHXjd" cx="0" cy="0" r="1" gradientTransform="rotate(-14.58 84.588 .63)scale(12.6303)" gradientUnits="userSpaceOnUse"><stop class="m2-5oep3n"/><stop offset="1" class="ccrpxv2mv"/></radialGradient><radialGradient id="i69Tgac" cx="0" cy="0" r="1" gradientTransform="translate(9.129 16.09)scale(2.9559)" gradientUnits="userSpaceOnUse"><stop class="leq1teb8m"/><stop offset="1" class="mzu7n7btv"/></radialGradient><radialGradient id="idpf1Ti" cx="0" cy="0" r="1" gradientTransform="translate(22.357 16.09)scale(2.9559)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="cm-t7oizl"/><stop offset="1" class="de2z6kbee"/></radialGradient><radialGradient id="iEsmXuc" cx="0" cy="0" r="1" gradientTransform="matrix(4.00155 0 0 3.81306 14.035 5.637)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="t4bit3zab"/><stop offset="1" class="rso1h0q-e"/></radialGradient><radialGradient id="iEKbqvW" cx="0" cy="0" r="1" gradientTransform="matrix(-3.19628 0 0 -3.18451 15.925 5.637)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="cd9ndob9s"/><stop offset="1" class="zpr8dpbig"/></radialGradient><radialGradient id="io7qvyd" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -1.5 1.60317 3.87434 2.4 19.103)" gradientUnits="userSpaceOnUse"><stop class="c0nx6hbog"/><stop offset="1" class="v81tmzddb"/></radialGradient><radialGradient id="icSUxne" cx="0" cy="0" r="1" gradientTransform="rotate(168.69 1.609 9.536)scale(3.02754 8.62298)" gradientUnits="userSpaceOnUse"><stop offset=".721" class="ujtpm2dyq"/><stop offset="1" class="cnv_atlwx"/></radialGradient><radialGradient id="iOXTuub" cx="0" cy="0" r="1" gradientTransform="rotate(168.257 1.573 9.546)scale(2.93646 8.36357)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="d6jdsbcln"/><stop offset="1" class="qcpbn1bcs"/></radialGradient><radialGradient id="iJzsyye" cx="0" cy="0" r="1" gradientTransform="matrix(1.01565 -3.85936 3.80653 1.00175 2.963 19.071)" gradientUnits="userSpaceOnUse"><stop offset=".934" class="rqlhfwblr"/><stop offset="1" class="r73rspbvb"/></radialGradient><radialGradient id="iX7Yohd" cx="0" cy="0" r="1" gradientTransform="matrix(.49692 4.94445 -3.96583 .39857 3.578 17.474)" gradientUnits="userSpaceOnUse"><stop offset=".876" class="czoatnmuu"/><stop offset="1" class="azt9wvbdd"/></radialGradient><radialGradient id="iZ9bBkd" cx="0" cy="0" r="1" gradientTransform="matrix(.22342 3.43637 -2.70757 .17604 13.396 23.273)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="xkfar2juy"/><stop offset="1" class="n4b5rw9mm"/></radialGradient><radialGradient id="iUYCMwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50384 -2.63193 2.28318 -1.30458 13.396 24.918)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="ba5oodbik"/><stop offset="1" class="uo5xmqg7m"/></radialGradient><radialGradient id="iAMf2kd" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 1.03125 -.66395 1.56935 26.9 18.79)" gradientUnits="userSpaceOnUse"><stop class="t1my-jkru"/><stop offset="1" class="ojxfok0hk"/></radialGradient><radialGradient id="iOCUTFb" cx="0" cy="0" r="1" gradientTransform="matrix(2.40625 .5625 -1.43639 6.14456 27.04 18.9)" gradientUnits="userSpaceOnUse"><stop offset=".874" class="xn2q_fbvd"/><stop offset="1" class="bzxpps3ig"/></radialGradient><radialGradient id="i1rl57d" cx="0" cy="0" r="1" gradientTransform="rotate(14.591 -60.014 114.804)scale(2.54295 5.71902)" gradientUnits="userSpaceOnUse"><stop offset=".95" class="xn2q_fbvd"/><stop offset="1" class="iym4u5bee"/></radialGradient><radialGradient id="izWcSsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00783 2.82812 -2.58016 -.91946 29.29 19.165)" gradientUnits="userSpaceOnUse"><stop offset=".9" class="doyedtd6q"/><stop offset="1" class="jf91fjb0w"/></radialGradient><radialGradient id="ilO72EG" cx="0" cy="0" r="1" gradientTransform="matrix(-.75782 -2.98438 2.84576 -.72263 29.181 20.212)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="r8fx88vfp"/><stop offset="1" class="p48q02qmd"/></radialGradient><radialGradient id="iUX1zQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.78393 .3056 -.24266 -.62244 10.921 7.516)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="q9jjd6bdy"/><stop offset="1" class="nvuf-9b9f"/></radialGradient><radialGradient id="iw1LJCe" cx="0" cy="0" r="1" gradientTransform="rotate(-122.305 15.271 -1.143)scale(1.57656 1.25181)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="q9jjd6bdy"/><stop offset="1" class="nvuf-9b9f"/></radialGradient><radialGradient id="iohm3kc" cx="0" cy="0" r="1" gradientTransform="rotate(168.151 6.493 5.934)scale(1.10698 .52195)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="q9jjd6bdy"/><stop offset="1" class="nvuf-9b9f"/></radialGradient><radialGradient id="iI7mHUc" cx="0" cy="0" r="1" gradientTransform="rotate(168.151 10.803 6.381)scale(1.10698 .52195)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="q9jjd6bdy"/><stop offset="1" class="nvuf-9b9f"/></radialGradient><linearGradient id="iisUNUc" x1="17.858" x2="13.306" y1="5.322" y2="6.509" gradientUnits="userSpaceOnUse"><stop class="km_q2lbxa"/><stop offset="1" class="xt3a-7b-m"/></linearGradient><linearGradient id="iSJ39Ed" x1="12.864" x2="17.4" y1="5.637" y2="5.637" gradientUnits="userSpaceOnUse"><stop class="dtybmrolq"/><stop offset="1" class="omu45-bjd"/><stop offset="1" class="iazzg2gxf"/></linearGradient><linearGradient id="iXzcW7U" x1="5.713" x2="2.525" y1="20.603" y2="14.447" gradientUnits="userSpaceOnUse"><stop class="plduchygk"/><stop offset="1" class="v2wlanx_c"/></linearGradient><linearGradient id="iZ6tu0b" x1="14.431" x2="12.4" y1="22.54" y2="25.837" gradientUnits="userSpaceOnUse"><stop class="x9zc6mbhz"/><stop offset="1" class="famouub2h"/></linearGradient><linearGradient id="iQt65dd" x1="11.275" x2="15.869" y1="23.009" y2="25.415" gradientUnits="userSpaceOnUse"><stop class="fhae0h78w"/><stop offset="1" class="pibt6tmlg"/></linearGradient><linearGradient id="inslkXb" x1="28.24" x2="28.24" y1="17.134" y2="22.053" gradientUnits="userSpaceOnUse"><stop class="ivv9fry2w"/><stop offset="1" class="s8nrb-4cp"/></linearGradient><linearGradient id="ixuH4ce" x1="10.572" x2="6.881" y1="7.004" y2="10.695" gradientUnits="userSpaceOnUse"><stop class="hqkoo6b7j"/><stop offset="1" class="e8-_3e3el"/></linearGradient><linearGradient id="igWCmHu" x1="23.932" x2="20.241" y1="7.004" y2="10.695" gradientUnits="userSpaceOnUse"><stop class="hqkoo6b7j"/><stop offset="1" class="e8-_3e3el"/></linearGradient><linearGradient id="iXVf4Ld" x1="13.583" x2="11.292" y1="10.028" y2="14.285" gradientUnits="userSpaceOnUse"><stop class="hqkoo6b7j"/><stop offset="1" class="e8-_3e3el"/></linearGradient><linearGradient id="i36WnIe" x1="22.203" x2="19.912" y1="10.028" y2="14.285" gradientUnits="userSpaceOnUse"><stop class="hqkoo6b7j"/><stop offset="1" class="e8-_3e3el"/></linearGradient><linearGradient id="i9fYMMe" x1="10.681" x2="11.525" y1="16.494" y2="17.134" gradientUnits="userSpaceOnUse"><stop class="h4zlmybgq"/><stop offset="1" class="fxgul7bfa"/></linearGradient><linearGradient id="iXvpAxb" x1="20.65" x2="20.056" y1="16.665" y2="17.322" gradientUnits="userSpaceOnUse"><stop class="li2cssbvi"/><stop offset="1" class="lgbpkob7v"/></linearGradient><linearGradient id="iOEL93c" x1="20.525" x2="19.05" y1="17.009" y2="20.402" gradientUnits="userSpaceOnUse"><stop class="cw-beyb7l"/><stop offset="1" class="nqzzw9dub"/></linearGradient><linearGradient id="iP0ah2c" x1="9.155" x2="8.219" y1="7.686" y2="10.826" gradientUnits="userSpaceOnUse"><stop class="s4f1sytth"/><stop offset="1" class="sv4xgjb8e"/></linearGradient><linearGradient id="i82f7Mb" x1="24.181" x2="19.975" y1="10.665" y2="9.721" gradientUnits="userSpaceOnUse"><stop class="sv4xgjb8e"/><stop offset=".379" class="s4f1sytth"/><stop offset=".74" class="sv4xgjb8e"/></linearGradient><linearGradient id="iiZYKZb" x1="7.869" x2="9.065" y1="11.646" y2="8.851" gradientUnits="userSpaceOnUse"><stop class="s4f1sytth"/><stop offset="1" class="sv4xgjb8e"/></linearGradient><linearGradient id="iBS37wb" x1="16.327" x2="17.523" y1="11.646" y2="8.851" gradientUnits="userSpaceOnUse"><stop class="s4f1sytth"/><stop offset="1" class="sv4xgjb8e"/></linearGradient><filter id="iDgJtFc" width="27.999" height="28.249" x="1.869" y="1.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.396078 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14537"/></filter><filter id="iVxK2Gb" width="5.744" height="5.744" x="12.489" y="2.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14537" stdDeviation=".125"/></filter><filter id="iXXcPhe" width="5.318" height="8.049" x="1.745" y="14.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14537" stdDeviation=".15"/></filter><filter id="iGnTaCb" width="5.367" height="5.19" x="10.712" y="21.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14537" stdDeviation=".15"/></filter><filter id="iypujDb" width="3.625" height="5.655" x="26.257" y="16.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14537" stdDeviation=".125"/></filter><filter id="i36oQ5d" width="4.78" height="4.78" x="6.659" y="6.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.0862745 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_14537"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_14537" result="shape"/></filter><filter id="ihiuydW" width="4.58" height="4.58" x="20.019" y="7.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.0862745 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_14537"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_14537" result="shape"/></filter><filter id="ifH8yIc" width="6.3" height="3.76" x="8.129" y="9.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.0862745 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_14537"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_14537" result="shape"/></filter><filter id="iD3fGEe" width="6.3" height="3.76" x="16.749" y="9.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.0862745 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_14537"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_14537" result="shape"/></filter><filter id="isCfzYc" width="12.87" height="5.838" x="9.059" y="15.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.133333 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_14537"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_14537" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.101961 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_14537"/></filter><filter id="iYIvrke" width="10.162" height="2.977" x="10.694" y="16.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14537" stdDeviation=".15"/></filter><filter id="i6EuYIe" width="2.75" height="3.633" x="7.119" y="7.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14537" stdDeviation=".125"/></filter><filter id="iDQ86Jb" width="4.047" height="3.556" x="20.431" y="7.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14537" stdDeviation=".125"/></filter><filter id="ikXknsc" width="5.744" height="2.876" x="8.7" y="10.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14537" stdDeviation=".2"/></filter><filter id="isKGvfb" width="5.744" height="2.876" x="17.158" y="10.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14537" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:new-moon-face" /></template>
<style>
.auva9bbhi {
  d: path("M10.539 8.174a2.48 2.48 0 0 0-2.48 2.48a.5.5 0 0 1-1 0a3.48 3.48 0 0 1 3.48-3.48a.5.5 0 1 1 0 1");
}

.azt9wvbdd {
  stop-color: var(--svg-color--57545c, #57545C);
}

.ba5oodbik {
  stop-color: var(--svg-color--4f2d6e, #4F2D6E);
  stop-opacity: 0;
}

.bzxpps3ig {
  stop-color: var(--svg-color--a385c1, #A385C1);
}

.c_qn-zg1g {
  stop-color: var(--svg-color--544269, #544269);
}

.c0nx6hbog {
  stop-color: var(--svg-color--524262, #524262);
}

.c3wt19kpr {
  d: path("M22.354 19.054a2.96 2.96 0 1 0 0-5.92a2.96 2.96 0 0 0 0 5.92");
  opacity: var(--svg-opacity--0-44, 0.44);
}

.ccrpxv2mv {
  stop-color: var(--svg-color--453c50, #453C50);
  stop-opacity: 0;
}

.cd9ndob9s {
  stop-color: var(--svg-color--a87acf, #A87ACF);
  stop-opacity: 0;
}

.cm-t7oizl {
  stop-color: var(--svg-color--e35387, #E35387);
}

.cnv_atlwx {
  stop-color: var(--svg-color--6a6373, #6A6373);
}

.cw-beyb7l {
  stop-color: var(--svg-color--4c3c59, #4C3C59);
}

.czoatnmuu {
  stop-color: var(--svg-color--57545c, #57545C);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d6jdsbcln {
  stop-color: var(--svg-color--5b5167, #5B5167);
  stop-opacity: 0;
}

.de2z6kbee {
  stop-color: var(--svg-color--e35387, #E35387);
  stop-opacity: 0;
}

.dl-15acrl {
  stop-color: var(--svg-color--544269, #544269);
  stop-opacity: 0;
}

.doyedtd6q {
  stop-color: var(--svg-color--af8dcf, #AF8DCF);
  stop-opacity: 0;
}

.dtybmrolq {
  stop-color: var(--svg-color--996bbf, #996BBF);
}

.e8-_3e3el {
  stop-color: var(--svg-color--231f26, #231F26);
}

.eft8crbxd {
  fill: var(--svg-color--352046, #352046);
  d: path("M10.779 16.714a.75.75 0 0 1 1.06 0a5.52 5.52 0 0 0 7.81 0a.75.75 0 0 1 1.06 1.06a7.02 7.02 0 0 1-9.93 0a.75.75 0 0 1 0-1.06");
}

.famouub2h {
  stop-color: var(--svg-color--52336b, #52336B);
}

.fg2y4kboq {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.658 22.749c1.05.822 1.337 2.211.64 3.102c-.697.89-2.114.945-3.165.123c-1.05-.823-1.336-2.211-.64-3.102c.698-.89 2.115-.946 3.165-.123Z");
}

.fhae0h78w {
  stop-color: var(--svg-color--583676, #583676);
}

.fsy8nnbto {
  d: path("M10.779 16.714a.75.75 0 0 1 1.06 0a5.52 5.52 0 0 0 7.81 0a.75.75 0 0 1 1.06 1.06a7.02 7.02 0 0 1-9.93 0a.75.75 0 0 1 0-1.06");
}

.ft5dv1b6b {
  fill: none;
}

.fxgul7bfa {
  stop-color: var(--svg-color--211928, #211928);
  stop-opacity: 0;
}

.g9syu8bub {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.369 7.954c-.495.26-1.633 1.047-1.75 2.633");
}

.h4zlmybgq {
  stop-color: var(--svg-color--211928, #211928);
}

.hqkoo6b7j {
  stop-color: var(--svg-color--28212f, #28212F);
}

.hzlukwbtw {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M29.604 17.175a2.497 2.497 0 0 0-1.25 4.823");
}

.iazzg2gxf {
  stop-color: var(--svg-color--7b569b, #7B569B);
}

.ivv9fry2w {
  stop-color: var(--svg-color--8059ac, #8059AC);
}

.iym4u5bee {
  stop-color: var(--svg-color--9a72bf, #9A72BF);
}

.j_a3zb8ef {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.361 8.134a2.497 2.497 0 1 0 0-4.994a2.497 2.497 0 0 0 0 4.994Z");
}

.jf91fjb0w {
  stop-color: var(--svg-color--af8dcf, #AF8DCF);
}

.k58qjccse {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M17.858 12.29c.104-.531.963-1.569 2.313-1.469s1.885.959 2.031 1.47");
}

.km_q2lbxa {
  stop-color: var(--svg-color--6d4993, #6D4993);
}

.leq1teb8m {
  stop-color: var(--svg-color--d8585d, #D8585D);
}

.lgbpkob7v {
  stop-color: var(--svg-color--584b64, #584B64);
  stop-opacity: 0;
}

.li2cssbvi {
  stop-color: var(--svg-color--584b64, #584B64);
}

.m2-5oep3n {
  stop-color: var(--svg-color--453c50, #453C50);
}

.mzu7n7btv {
  stop-color: var(--svg-color--d8585d, #D8585D);
  stop-opacity: 0;
}

.n0wdc0bol {
  stop-color: var(--svg-color--a27ace, #A27ACE);
}

.n4b5rw9mm {
  stop-color: var(--svg-color--674f7d, #674F7D);
}

.nda4_nbxw {
  d: path("M14.658 22.749c1.05.822 1.337 2.211.64 3.102c-.697.89-2.114.945-3.165.123c-1.05-.823-1.336-2.211-.64-3.102c.698-.89 2.115-.946 3.165-.123");
}

.nqzzw9dub {
  stop-color: var(--svg-color--3d3645, #3D3645);
}

.nvuf-9b9f {
  stop-color: var(--svg-color--48424f, #48424F);
  stop-opacity: 0;
}

.o0aghtbvl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M9.4 12.29c.104-.531.963-1.569 2.313-1.469s1.885.959 2.03 1.47");
}

.ojxfok0hk {
  stop-color: var(--svg-color--9c77bf, #9C77BF);
}

.omu45-bjd {
  stop-color: var(--svg-color--996bbf, #996BBF);
  stop-opacity: 0;
}

.p48q02qmd {
  stop-color: var(--svg-color--7f59a4, #7F59A4);
}

.pbe0wtcwc {
  d: path("M20.079 11.654a1.37 1.37 0 0 0-1.282.864a.75.75 0 1 1-1.396-.548a2.87 2.87 0 0 1 2.678-1.816c1.272 0 2.354.826 2.732 1.975a.75.75 0 0 1-1.424.47c-.182-.55-.7-.945-1.308-.945");
}

.pibt6tmlg {
  stop-color: var(--svg-color--5e407c, #5E407C);
}

.plduchygk {
  stop-color: var(--svg-color--3e3744, #3E3744);
}

.q-fi78b9v {
  fill: var(--svg-color--6b438b, #6B438B);
  d: path("M26.026 25.733a14 14 0 0 1-6.224 3.806a3.651 3.651 0 0 1 6.224-3.806");
}

.q7f2lrb3g {
  stop-color: var(--svg-color--60348c, #60348C);
}

.q9jjd6bdy {
  stop-color: var(--svg-color--48424f, #48424F);
}

.qcpbn1bcs {
  stop-color: var(--svg-color--5b5167, #5B5167);
}

.r73rspbvb {
  stop-color: var(--svg-color--624c7a, #624C7A);
}

.r8fx88vfp {
  stop-color: var(--svg-color--7f59a4, #7F59A4);
  stop-opacity: 0;
}

.rqlhfwblr {
  stop-color: var(--svg-color--624c7a, #624C7A);
  stop-opacity: 0;
}

.rso1h0q-e {
  stop-color: var(--svg-color--64487e, #64487E);
}

.s4f1sytth {
  stop-color: var(--svg-color--3f3a44, #3F3A44);
  stop-opacity: 0;
}

.s8nrb-4cp {
  stop-color: var(--svg-color--9169be, #9169BE);
}

.spxyxuvuh {
  d: path("M11.459 11.654a1.37 1.37 0 0 0-1.282.864a.75.75 0 0 1-1.396-.548a2.87 2.87 0 0 1 2.678-1.816c1.272 0 2.354.826 2.732 1.975a.75.75 0 0 1-1.424.47c-.182-.55-.7-.945-1.308-.945");
}

.sv4xgjb8e {
  stop-color: var(--svg-color--3f3a44, #3F3A44);
}

.t_3aqrb6f {
  cx: 15.868px;
  cy: 16.1px;
  r: 13.999px;
}

.t1my-jkru {
  stop-color: var(--svg-color--9d6bc8, #9D6BC8);
}

.t4bit3zab {
  stop-color: var(--svg-color--64487e, #64487E);
  stop-opacity: 0;
}

.t4kly7nao {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M2.07 15.257q.451-.121.942-.123a3.651 3.651 0 0 1 .617 7.25");
}

.ujtpm2dyq {
  stop-color: var(--svg-color--6a6373, #6A6373);
  stop-opacity: 0;
}

.uo5xmqg7m {
  stop-color: var(--svg-color--4f2d6e, #4F2D6E);
}

.uwrl8-bdq {
  d: path("M9.134 19.054a2.96 2.96 0 1 0 0-5.92a2.96 2.96 0 0 0 0 5.92");
  opacity: var(--svg-opacity--0-44, 0.44);
}

.v2wlanx_c {
  stop-color: var(--svg-color--504163, #504163);
}

.v81tmzddb {
  stop-color: var(--svg-color--4a395d, #4A395D);
}

.wbcbm6bxq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.244 17.197c1.51 1.416 5.437 3.4 9.062 0");
}

.wvdncebfp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M20.931 7.603c.844-.073 2.772.272 3.047 2.547");
}

.x8f9z44sf {
  d: path("M15.361 8.134a2.497 2.497 0 1 0 0-4.994a2.497 2.497 0 0 0 0 4.994");
}

.x9zc6mbhz {
  stop-color: var(--svg-color--563775, #563775);
}

.xijkheb_k {
  d: path("M29.823 17.225a13.9 13.9 0 0 1-1.28 4.828a2.498 2.498 0 1 1 1.28-4.828");
}

.xkfar2juy {
  stop-color: var(--svg-color--674f7d, #674F7D);
  stop-opacity: 0;
}

.xn2q_fbvd {
  stop-color: var(--svg-color--a385c1, #A385C1);
  stop-opacity: 0;
}

.xt3a-7b-m {
  stop-color: var(--svg-color--8d61b9, #8D61B9);
}

.yawvdpb6z {
  d: path("M1.89 15.31q.532-.174 1.122-.176a3.651 3.651 0 0 1 .36 7.285a13.94 13.94 0 0 1-1.481-7.11");
}

.z73u9eb1f {
  d: path("M20.419 7.674a.5.5 0 0 1 .5-.5a3.48 3.48 0 0 1 3.48 3.48a.5.5 0 1 1-1 0a2.48 2.48 0 0 0-2.48-2.48a.5.5 0 0 1-.5-.5");
}

.zpr8dpbig {
  stop-color: var(--svg-color--a87acf, #A87ACF);
}

</style>
