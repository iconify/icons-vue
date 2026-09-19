<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijs2uYc)"><circle fill="url(#iGqm4pS)" class="v-30-7x4s"/></g><g filter="url(#ijNazQe)"><circle fill="url(#iYFRMIb)" class="s1mz5y7pt"/></g><g filter="url(#ilSqxrc)"><circle fill="url(#iczHVRb)" class="s72pw74ms"/><circle fill="url(#ij5UWFc)" class="s72pw74ms"/></g><g filter="url(#iruzuGc)"><circle class="njwzlgczn"/><circle fill="url(#ijCKbEe)" class="pbw_1oblv"/><circle fill="url(#iS7wcNc)" class="pbw_1oblv"/></g><g filter="url(#iGv2kQb)"><path fill="url(#iRimGPd)" class="ervnud-eh"/><path fill="url(#id3Po5d)" class="ervnud-eh"/><path fill="url(#iIjgK1o)" class="ervnud-eh"/><path fill="url(#i23B9cA)" class="ervnud-eh"/><path fill="url(#ikwcXdM)" class="ervnud-eh"/><path fill="url(#ihqOWwc)" class="ervnud-eh"/><path fill="url(#ibhJBNe)" class="ervnud-eh"/></g><g filter="url(#i3H1kvc)"><path fill="url(#ikSlLqe)" class="ll5bq8b7t"/></g><g filter="url(#i6w43yc)"><path class="dmchf5lbi"/><path fill="url(#ixlHnIb)" class="nex-x_hxk"/><path fill="url(#iSR2EFe)" class="nex-x_hxk"/><path fill="url(#iruZTBb)" class="nex-x_hxk"/><path fill="url(#inNIEAb)" class="nex-x_hxk"/><path fill="url(#ikN0qwK)" class="nex-x_hxk"/></g><path fill="url(#i8nxrhd)" class="nex-x_hxk"/><path fill="url(#iQy5Txe)" class="nex-x_hxk"/><g filter="url(#iwcUcgL)"><path class="gqf0l8njo"/></g><g filter="url(#igOmxzd)"><path class="qpcy-h2oe"/><path fill="url(#is5Sozc)" class="cbq1t5_me"/><path fill="url(#imh6jsd)" class="cbq1t5_me"/><path fill="url(#iYynUue)" class="cbq1t5_me"/><path fill="url(#i2T16wd)" class="cbq1t5_me"/></g><path fill="url(#iXD3HFr)" class="cbq1t5_me"/><path stroke="url(#iY4Sn2c)" class="abrtj0d9f"/><g filter="url(#iR4Vxdd)"><path class="kkwq74x3v"/><path fill="url(#iBzSdOR)" class="ro9l-sbza"/></g><g filter="url(#iUJB60c)"><path class="mpyfm7hgs"/><path fill="url(#iMtwfpb)" class="s_gvjrbyd"/></g><path class="f6czxtz5j"/><path fill="url(#isyUQzd)" class="syqh2sbqs"/><path class="ay9cq0d1l"/><g filter="url(#inmhpkc)"><path class="pu69_yu4m"/><path fill="url(#iVJu1Dc)" class="hh__2aceo"/></g><g filter="url(#i7t2epM)"><path fill="url(#iBI2wxd)" class="z5h7u4bip"/></g><path class="v3rmoybey"/><path fill="url(#ivCBzZc)" class="ampf59_zk"/><path class="w5wsyh14x"/><g filter="url(#iMTrmHd)"><path fill="url(#ih7Js6z)" class="labizxbgi"/></g><g filter="url(#i3m4Yce)"><ellipse transform="rotate(-27.914 11.367 16.599)" class="e9gbg1d-u"/><ellipse fill="url(#ius6L4b)" transform="rotate(-27.914 11.367 16.599)" class="oufadibrx"/></g><g filter="url(#iS1rvRd)"><path stroke="url(#i0IEUxe)" class="ca06pugdq"/></g><g filter="url(#idt25Ed)"><path stroke="url(#igIZlMb)" class="n-zw6k8dv"/></g><defs><radialGradient id="iGqm4pS" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.05)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="ij5UWFc" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.527 17.555)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="ijCKbEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.58)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iS7wcNc" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.529 39.219)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iRimGPd" cx="0" cy="0" r="1" gradientTransform="matrix(-13.4375 0 0 -26.2357 24.188 20.366)" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="h_9hnv22m"/></radialGradient><radialGradient id="iIjgK1o" cx="0" cy="0" r="1" gradientTransform="matrix(-2.29 14.96874 -20.3193 -3.10856 18.009 15.553)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="sja-phb9i"/><stop offset="1" class="c55g5jb0d"/></radialGradient><radialGradient id="i23B9cA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 2.4599 0 20.321 15.74)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="uvgug6b6x"/><stop offset="1" class="g-mco4ren"/></radialGradient><radialGradient id="ikwcXdM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 3.22556 0 11.821 15.616)" gradientUnits="userSpaceOnUse"><stop class="lqb4cab_v"/><stop offset="1" class="y8_3z_b1m"/></radialGradient><radialGradient id="ihqOWwc" cx="0" cy="0" r="1" gradientTransform="rotate(149.494 11.76 8.708)scale(10.5441 9.09392)" gradientUnits="userSpaceOnUse"><stop class="emzxsb-3z"/><stop offset="1" class="x6hdpsbbh"/></radialGradient><radialGradient id="ixlHnIb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.4087 8.25997 -14.04691 -10.89865 22.832 3.666)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iruZTBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.12461 -3.47136 1.70486 -.0612 8.127 11.605)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="inNIEAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.60216 -3.6672 2.99087 1.30668 23.828 14.81)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="ikN0qwK" cx="0" cy="0" r="1" gradientTransform="matrix(1.85139 2.29723 -2.0283 1.63465 14.5 2.01)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="i8nxrhd" cx="0" cy="0" r="1" gradientTransform="rotate(76.961 7.357 11.85)scale(1.4992 2.4647)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iQy5Txe" cx="0" cy="0" r="1" gradientTransform="matrix(1.35294 1.67337 -3.7494 3.03145 7.843 5.232)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="i2T16wd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36719 -1.17969 0 16.556 21.045)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iBzSdOR" cx="0" cy="0" r="1" gradientTransform="rotate(-80.201 18.66 -5.092)scale(1.14166 3.3775)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iMtwfpb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 13.86 .608)scale(1.14166 3.37768)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="isyUQzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.01 17.4)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iVJu1Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.939 3.671)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivCBzZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 11.873 17.4)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ius6L4b" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.13 3.012)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ijs2uYc" width="6.427" height="6.227" x="3.979" y="14.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19889"/></filter><filter id="ijNazQe" width="4.711" height="4.711" x="4.737" y="15.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19889" stdDeviation=".25"/></filter><filter id="ilSqxrc" width="6.477" height="6.477" x="21.72" y="14.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19889"/></filter><filter id="iruzuGc" width="4.711" height="4.711" x="22.478" y="15.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19889" stdDeviation=".25"/></filter><filter id="iGv2kQb" width="19.345" height="22.63" x="6.327" y="7.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.247059 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19889"/></filter><filter id="i3H1kvc" width="11.918" height="9.719" x="15.009" y="5.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19889" stdDeviation="1"/></filter><filter id="i6w43yc" width="23.5" height="15.5" x="4.196" y="1.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.737255 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19889"/></filter><filter id="iwcUcgL" width="4.782" height="6.5" x="13.11" y="16.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19889" stdDeviation=".375"/></filter><filter id="igOmxzd" width="4" height="5.5" x="13.946" y="16.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19889" stdDeviation=".125"/></filter><filter id="iR4Vxdd" width="5.34" height="3.147" x="18.151" y="11.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19889"/></filter><filter id="iUJB60c" width="5.341" height="3.147" x="8.551" y="11.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19889"/></filter><filter id="inmhpkc" width="1.294" height="1.125" x="18.727" y="16.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19889" stdDeviation=".05"/></filter><filter id="i7t2epM" width="1.316" height="1.357" x="20.38" y="16.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19889" stdDeviation=".1"/></filter><filter id="iMTrmHd" width="1.493" height="1.594" x="12.097" y="16.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19889" stdDeviation=".1"/></filter><filter id="i3m4Yce" width="1.529" height="1.141" x="10.603" y="16.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19889" stdDeviation=".05"/></filter><filter id="iS1rvRd" width="4.949" height="2.304" x="18.293" y="11.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19889" stdDeviation=".25"/></filter><filter id="idt25Ed" width="5.094" height="2.41" x="8.56" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19889" stdDeviation=".25"/></filter><linearGradient id="iYFRMIb" x1="7.092" x2="5.898" y1="18.569" y2="18.569" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iczHVRb" x1="26.859" x2="25.332" y1="16.014" y2="20.744" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="id3Po5d" x1="6.327" x2="9.469" y1="23.397" y2="22.991" gradientUnits="userSpaceOnUse"><stop class="wosf13tnn"/><stop offset="1" class="bt0evo0bz"/></linearGradient><linearGradient id="ibhJBNe" x1="15.438" x2="15.438" y1="30.397" y2="29.428" gradientUnits="userSpaceOnUse"><stop class="d12sgnb8w"/><stop offset="1" class="kgug1ekqe"/></linearGradient><linearGradient id="ikSlLqe" x1="15.701" x2="30.889" y1="13.21" y2="7.772" gradientUnits="userSpaceOnUse"><stop class="o28oy5bdi"/><stop offset="1" class="lserk9bsd"/></linearGradient><linearGradient id="iSR2EFe" x1="6.881" x2="12.293" y1="17.551" y2="7.938" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="is5Sozc" x1="14.335" x2="16.084" y1="20.005" y2="20.005" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="imh6jsd" x1="17.696" x2="15.784" y1="20.606" y2="20.579" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iYynUue" x1="16.309" x2="16.309" y1="21.991" y2="20.922" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iXD3HFr" x1="16.181" x2="16.181" y1="22.069" y2="21.756" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="iY4Sn2c" x1="14.012" x2="14.824" y1="25.003" y2="23.72" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iBI2wxd" x1="21.46" x2="20.875" y1="16.878" y2="17.238" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ih7Js6z" x1="13.26" x2="12.675" y1="16.878" y2="17.238" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0IEUxe" x1="21.489" x2="20.706" y1="12.888" y2="11.287" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="igIZlMb" x1="11.597" x2="9.379" y1="12.65" y2="11.72" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-blonde-hair-medium-dark" /></template>
<style>
.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.abrtj0d9f {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.386 23.23a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.22-2.56-.606Z");
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.ampf59_zk {
  d: path("M11.87 15.888a1.664 1.664 0 0 0-1.604 2.103h3.214c.038-.144.061-.288.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.ay9cq0d1l {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 17.552c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.9.9 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bt0evo0bz {
  stop-color: var(--svg-color--83615a, #83615A);
  stop-opacity: 0;
}

.c55g5jb0d {
  stop-color: var(--svg-color--773d63, #773D63);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.ca06pugdq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.707c.802-.14 2.366-.1 3.449.742");
}

.cbq1t5_me {
  d: path("m15.234 17.517l-.991 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d12sgnb8w {
  stop-color: var(--svg-color--8e5a8e, #8E5A8E);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dmchf5lbi {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m24.933 5.97l.8.397c1.4.696 2.2 2.288 1.9 3.978l-1.1 5.67c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.592V9.351c0-.497-.4-.895-.8-.995c-1.201-.298-3.702-.795-7.303-.795s-6.102.497-7.302.795c-.5.1-.8.498-.8.995v1.591c0 .597-.2 1.194-.7 1.592l-.3.298c-.4.298-.6.895-.6 1.392c.1 1.094.2 2.686.2 2.686q-.047 0-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.183 2-3.879l.8-.398c.5-.298 1-.696 1.501-1.094l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1 .298 2.1.298 3.1 0c1.501-.498 3.202-.1 4.402.994l1.5 1.492c.4.497.9.796 1.5 1.094");
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.e9gbg1d-u {
  cx: 11.367px;
  cy: 16.599px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.emzxsb-3z {
  stop-color: var(--svg-color--987062, #987062);
}

.ervnud-eh {
  d: path("M6.436 16.907q.045.003.091.003s-.1-1.592-.2-2.686c0-.497.2-1.094.6-1.392l.3-.299c.5-.397.7-.994.7-1.59V9.35c0-.497.301-.895.801-.995c1.2-.298 3.701-.795 7.302-.795s6.102.497 7.302.795c.4.1.8.498.8.995v1.591c0 .597.3 1.194.7 1.592c.937.656.879 1.016.801 1.79c-.1.994-.2 2.685-.2 2.685h.034l-.496 7.382c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6z");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f6czxtz5j {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.381c1.217 0 2.245.84 2.525 1.974a.51.51 0 0 1-.499.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.103");
}

.ft5dv1b6b {
  fill: none;
}

.g-mco4ren {
  stop-color: var(--svg-color--865353, #865353);
  stop-opacity: 0;
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gqf0l8njo {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.433 17.822l-1.53 3.169c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.702-.527-.702-.736 0");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.h_9hnv22m {
  stop-color: var(--svg-color--734b4a, #734B4A);
}

.hh__2aceo {
  d: path("M19.891 16.24c.119.158-.13.352-.41.562c-.283.211-.492.36-.61.2c-.119-.158.014-.457.295-.668c.282-.21.607-.253.725-.094");
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.kgug1ekqe {
  stop-color: var(--svg-color--8e5a8e, #8E5A8E);
  stop-opacity: 0;
}

.kkwq74x3v {
  fill: var(--svg-color--352827, #352827);
  d: path("m22.883 12.977l-.002-.002l-.004-.003l-.008-.007l-.023-.017l-.067-.051a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.393a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.966a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.298q.011.009.015.01a.995.995 0 0 0 1.265-1.536");
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.labizxbgi {
  d: path("M13.39 17.357c0-.538-.438-.897-.556-1.005l-.537.52l.33.674z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll5bq8b7t {
  d: path("m24.084 7.56l-5.739 1.914a1.953 1.953 0 0 0 .877 3.788l5.706-.764z");
}

.lqb4cab_v {
  stop-color: var(--svg-color--70414e, #70414E);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lserk9bsd {
  stop-color: var(--svg-color--9d756d, #9D756D);
  stop-opacity: 0;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mpyfm7hgs {
  fill: var(--svg-color--352827, #352827);
  d: path("M8.91 12.978v-.002h.002l.004-.004l.008-.007l.022-.017l.067-.051q.083-.062.222-.15c.186-.116.45-.261.783-.393a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.966a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.298l-.015.01a.995.995 0 0 1-1.266-1.535");
}

.n-zw6k8dv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.31 13.674c.61-.539 1.942-1.107 3.593-.843");
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nex-x_hxk {
  d: path("m24.933 5.97l.8.397c1.4.696 2.2 2.288 1.9 3.978l-1.1 5.67c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.592V9.351c0-.497-.4-.895-.8-.995c-1.201-.298-3.702-.795-7.303-.795s-6.102.497-7.302.795c-.5.1-.8.498-.8.995v1.591c0 .597-.2 1.194-.7 1.592l-.3.298c-.4.298-.6.895-.6 1.392c.1 1.094.2 2.686.2 2.686q-.047 0-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.183 2-3.879l.8-.398c.5-.298 1-.696 1.501-1.094l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1 .298 2.1.298 3.1 0c1.501-.498 3.202-.1 4.402.994l1.5 1.492c.4.497.9.796 1.5 1.094");
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.njwzlgczn {
  cx: 24.833px;
  cy: 18.049px;
  r: 1.855px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.o28oy5bdi {
  stop-color: var(--svg-color--9d756d, #9D756D);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oufadibrx {
  cx: 11.367px;
  cy: 16.599px;
  rx: 0.726px;
  ry: 0.368px;
}

.pbw_1oblv {
  cx: 24.833px;
  cy: 18.049px;
  r: 1.855px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pu69_yu4m {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.24c.119.158-.13.352-.41.562c-.283.211-.492.36-.61.2c-.119-.158.014-.457.295-.668c.282-.21.607-.253.725-.094");
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qpcy-h2oe {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.234 17.517l-.991 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.ro9l-sbza {
  d: path("m22.883 12.977l-.002-.002l-.004-.003l-.008-.007l-.023-.017l-.067-.051a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.393a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.966a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.298q.011.009.015.01a.995.995 0 0 0 1.265-1.536");
}

.s_gvjrbyd {
  d: path("M8.91 12.978v-.002h.002l.004-.004l.008-.007l.022-.017l.067-.051q.083-.062.222-.15c.186-.116.45-.261.783-.393a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.966a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.298l-.015.01a.995.995 0 0 1-1.266-1.535");
}

.s1mz5y7pt {
  cx: 7.092px;
  cy: 18.049px;
  r: 1.855px;
}

.s72pw74ms {
  cx: 24.833px;
  cy: 18.049px;
  r: 3.113px;
}

.sja-phb9i {
  stop-color: var(--svg-color--773d63, #773D63);
  stop-opacity: 0;
}

.syqh2sbqs {
  d: path("M20.013 15.888a1.664 1.664 0 0 1 1.604 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uvgug6b6x {
  stop-color: var(--svg-color--865353, #865353);
}

.v-30-7x4s {
  cx: 7.092px;
  cy: 18.049px;
  r: 3.113px;
}

.v3rmoybey {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.381c-1.218 0-2.247.84-2.526 1.974a.51.51 0 0 0 .499.636h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.103");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w5wsyh14x {
  fill: var(--svg-color--000, #000);
  d: path("M12.823 17.552a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .159.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wosf13tnn {
  stop-color: var(--svg-color--83615a, #83615A);
}

.x6hdpsbbh {
  stop-color: var(--svg-color--987062, #987062);
  stop-opacity: 0;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y8_3z_b1m {
  stop-color: var(--svg-color--70414e, #70414E);
  stop-opacity: 0;
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z5h7u4bip {
  d: path("M21.496 17.333a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.425z");
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

</style>
