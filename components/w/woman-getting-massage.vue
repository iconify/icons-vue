<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iGqEDmJ" class="k0led5buk"/></defs><g class="ft5dv1b6b"><g filter="url(#ivOfJFe)"><path fill="url(#i7fl4Ub)" class="fsuatq1-u"/><path fill="url(#iAuIhcd)" class="fsuatq1-u"/></g><path fill="url(#i0Syq1c)" class="fsuatq1-u"/><path fill="url(#iftXPqc)" class="fsuatq1-u"/><g filter="url(#id91NTd)"><path fill="url(#ivBW4hb)" class="p6uz8ubkb"/><path fill="url(#iLgBQdK)" class="p6uz8ubkb"/></g><g filter="url(#iy8dEHq)"><path fill="url(#iFofX8c)" class="oelw8ib5n"/></g><path fill="url(#iNrs6bc)" class="oelw8ib5n"/><path fill="url(#i5HCHIe)" class="oelw8ib5n"/><circle fill="url(#io3Bgmc)" class="rnpd_y0iu"/><g filter="url(#iD639Ee)" class="mc2zb0bvp"><circle class="ee3mn7b4s"/></g><circle fill="url(#iUBqFQb)" class="oj5myrpqa"/><circle fill="url(#imAWhJc)" class="oj5myrpqa"/><g filter="url(#iYvP7Fc)"><circle class="ujvo-nb1v"/></g><g filter="url(#iGcv7Ec)"><circle fill="url(#inbcl1c)" class="uj9pdvsyv"/></g><path class="bpzdz3q1w"/><path fill="url(#iTopYkc)" class="a9r_rhbce"/><path fill="url(#i9TidNb)" class="a9r_rhbce"/><g filter="url(#iu6wuwd)"><rect fill="url(#iWnR7qb)" class="d3q0pzbia"/></g><rect fill="url(#iCjmrZd)" class="d3q0pzbia"/><rect fill="url(#i46Nrpe)" class="d3q0pzbia"/><g filter="url(#i3kgwnd)"><path fill="url(#i7o4xde)" class="u7iwsbb9m"/><path fill="url(#iUrRNDc)" class="u7iwsbb9m"/></g><g filter="url(#iHKqD6c)"><path fill="url(#iaupgCc)" class="ma08wxbns"/></g><g filter="url(#ii2KLXc)"><path fill="url(#iPfP3Xb)" class="ihclt-v2y"/><path fill="url(#iQwwrbe)" class="ihclt-v2y"/><path fill="url(#inFvdSc)" class="ihclt-v2y"/><path fill="url(#iJpZHAR)" class="ihclt-v2y"/></g><g filter="url(#iB8EVAb)"><path fill="url(#iXa46gb)" class="bmc1y-ezx"/><path fill="url(#ijaHk7c)" class="bmc1y-ezx"/></g><g filter="url(#ijygJnz)"><circle fill="url(#iXCPZ0c)" class="vfen6w6fz"/></g><g filter="url(#irfXmRd)"><path class="oggs7wb0o"/></g><g filter="url(#imT1Dtc)"><path stroke="url(#ifhQ5sh)" class="xw2-3acug"/></g><g filter="url(#iIy0vRc)"><path class="gpmwkmbvk"/></g><g filter="url(#imLeJ9d)"><path stroke="url(#iKoRkUb)" class="myrtd-bfw"/></g><path stroke="url(#iOcUZCd)" class="me4cmnnbt"/><g filter="url(#iTwegFe)"><path stroke="url(#iqZMtxd)" class="vy4bnb43g"/></g><path stroke="url(#iAeGCZe)" class="vqnj7hhwz"/><g filter="url(#iMnZPSa)"><path stroke="url(#iA2LLyb)" class="gk5ny2bsn"/></g><g filter="url(#imERtlE)"><path class="hxgqgkbof"/></g><path class="wz5dhy52n"/><path fill="url(#iqtupOb)" class="v1vlmzb3z"/><path fill="url(#ijcoKse)" class="v1vlmzb3z"/><g filter="url(#i6iZ8mc)"><path stroke="url(#imEhC1b)" class="e_hhqfp0c"/></g><path class="nq7lirltb"/><g filter="url(#iWFlJld)"><path class="vkcyyxb3b"/><path fill="url(#iHjpCSd)" class="j5d-p-qvc"/><path fill="url(#iqtWejc)" class="j5d-p-qvc"/></g><g filter="url(#itmsMie)"><use href="#iGqEDmJ"/><path fill="url(#iZzdGwd)" class="jj-4sebrf"/></g><g filter="url(#itmsMie)"><use href="#iGqEDmJ"/><path fill="url(#iZzdGwd)" class="jj-4sebrf"/></g><g filter="url(#iSzxbGb)"><path fill="url(#i8MBbBb)" class="ab_0q75ef"/></g><g filter="url(#i7lkFkd)"><path fill="url(#ifu1BsH)" class="he4rjee5h"/></g><g filter="url(#iil8HHb)"><path class="ar3j2pbeq"/></g><defs><radialGradient id="i7fl4Ub" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -12.0938 23.481 28.329)" gradientUnits="userSpaceOnUse"><stop class="oof-goujs"/><stop offset=".832" class="y-z81-bua"/></radialGradient><radialGradient id="iAuIhcd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.16617 -7.1847 8.98984 -5.2129 23.982 28.265)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="r-5ctobwv"/><stop offset="1" class="b2cgmuy3t"/></radialGradient><radialGradient id="i0Syq1c" cx="0" cy="0" r="1" gradientTransform="rotate(155.64 5.704 11.337)scale(10.8979 4.51152)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="rc0rszb3u"/><stop offset="1" class="k4lo-hb9q"/></radialGradient><radialGradient id="iftXPqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.5924 15.2389 0 16 30.329)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="xxerewdbl"/><stop offset=".977" class="rjclg2bzq"/></radialGradient><radialGradient id="ivBW4hb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.56244 7.87504 -7.63171 -5.39056 25.318 13.891)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xitcw8bap"/><stop offset="1" class="p_ukq-bjv"/></radialGradient><radialGradient id="iLgBQdK" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0625 .53125 -1.29828 -5.04041 24.756 17.079)" gradientUnits="userSpaceOnUse"><stop class="rrdo8bckr"/><stop offset="1" class="fvb5ljbqc"/></radialGradient><radialGradient id="iFofX8c" cx="0" cy="0" r="1" gradientTransform="rotate(152.281 3.897 10.468)scale(4.87131 9.06872)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="iu2c2hjkx"/><stop offset="1" class="gm7csc62e"/></radialGradient><radialGradient id="iNrs6bc" cx="0" cy="0" r="1" gradientTransform="matrix(1.78475 1.03515 -2.16852 3.73884 8.598 11.304)" gradientUnits="userSpaceOnUse"><stop class="bb3wbnbfg"/><stop offset="1" class="t_e5mbckj"/></radialGradient><radialGradient id="i5HCHIe" cx="0" cy="0" r="1" gradientTransform="rotate(128.784 1.788 10.148)scale(2.245 2.60126)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="dnja8ltqt"/><stop offset="1" class="h41hxoaeu"/></radialGradient><radialGradient id="io3Bgmc" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.242 17.142)scale(2.88068)" gradientUnits="userSpaceOnUse"><stop class="g0xv48b6h"/><stop offset="1" class="r6ifw9b5e"/></radialGradient><radialGradient id="iUBqFQb" cx="0" cy="0" r="1" gradientTransform="rotate(120.672 7.602 13.59)scale(2.63415 1.68373)" gradientUnits="userSpaceOnUse"><stop class="pg81w39ph"/><stop offset=".908" class="dmanwfbnw"/></radialGradient><radialGradient id="imAWhJc" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.582 21.035)scale(2.34213)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="n3i3hq-br"/><stop offset="1" class="qca9cgb6f"/></radialGradient><radialGradient id="inbcl1c" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.367 13.959)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cibck0b0g"/><stop offset=".902" class="ghvr_e1bi"/></radialGradient><radialGradient id="iTopYkc" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.186 14.604)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="dubz53-6i"/><stop offset="1" class="rawot7b-t"/></radialGradient><radialGradient id="i9TidNb" cx="0" cy="0" r="1" gradientTransform="matrix(1.41333 2.53125 -8.23121 4.59592 14.1 20.516)" gradientUnits="userSpaceOnUse"><stop class="ye7u2hbjz"/><stop offset="1" class="m5pfi3anb"/></radialGradient><radialGradient id="iWnR7qb" cx="0" cy="0" r="1" gradientTransform="rotate(174.247 9.377 7.954)scale(6.06562 7.0411)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="isb53_mmq"/><stop offset="1" class="b1hif_bph"/></radialGradient><radialGradient id="iCjmrZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.0892 -11.8947 0 16 10.99)" gradientUnits="userSpaceOnUse"><stop offset=".678" class="yg-qo1umn"/><stop offset="1" class="jlfms8b5j"/></radialGradient><radialGradient id="i46Nrpe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15626 4.78125 -12.88264 -3.11545 17.35 8.829)" gradientUnits="userSpaceOnUse"><stop class="gyw7vvbbr"/><stop offset="1" class="kegnawh0e"/></radialGradient><radialGradient id="i7o4xde" cx="0" cy="0" r="1" gradientTransform="matrix(1.05598 2.75833 -1.5163 .5805 11.308 7.185)" gradientUnits="userSpaceOnUse"><stop class="f7m1yfx-m"/><stop offset="1" class="p3lw01bbh"/></radialGradient><radialGradient id="iUrRNDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.11352 -5.07335 3.05801 -.06842 11.005 14.425)" gradientUnits="userSpaceOnUse"><stop class="km7u9bcta"/><stop offset="1" class="rf_171bfc"/></radialGradient><radialGradient id="iaupgCc" cx="0" cy="0" r="1" gradientTransform="matrix(.0704 7.01754 -5.71616 .05734 20.358 7.09)" gradientUnits="userSpaceOnUse"><stop class="p97qg-b4a"/><stop offset="1" class="vukz93b8e"/></radialGradient><radialGradient id="iPfP3Xb" cx="0" cy="0" r="1" gradientTransform="rotate(-156.125 10.589 2.047)scale(6.25391 3.63898)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="eurnqk27z"/><stop offset="1" class="p9wfp42yy"/></radialGradient><radialGradient id="iQwwrbe" cx="0" cy="0" r="1" gradientTransform="matrix(2.0625 -1.6875 2.89382 3.5369 10.818 10.204)" gradientUnits="userSpaceOnUse"><stop class="gr2fu0gnc"/><stop offset="1" class="cpsescblj"/></radialGradient><radialGradient id="inFvdSc" cx="0" cy="0" r="1" gradientTransform="rotate(-144.811 12.394 1.874)scale(2.98253 5.11462)" gradientUnits="userSpaceOnUse"><stop class="qfb1b_nis"/><stop offset="1" class="fs8190bqd"/></radialGradient><radialGradient id="iJpZHAR" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 -2.5625 .76061 .94612 12.13 6.672)" gradientUnits="userSpaceOnUse"><stop class="icpnccptv"/><stop offset="1" class="pwu8-qxpb"/></radialGradient><radialGradient id="iXa46gb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62502 -4.71512 4.31184 -1.48603 17.13 9.704)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="n-u20jcue"/><stop offset="1" class="rul9zob_o"/></radialGradient><radialGradient id="ijaHk7c" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 -3.96876 11.53736 7.0859 17.006 9.61)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="mnbqkjntq"/><stop offset=".952" class="tcuhfk5hu"/></radialGradient><radialGradient id="iXCPZ0c" cx="0" cy="0" r="1" gradientTransform="rotate(-62.753 18.263 -4.122)scale(1.90544 2.10594)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cibck0b0g"/><stop offset=".902" class="ghvr_e1bi"/></radialGradient><radialGradient id="iOcUZCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.594)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="zbl0hn4uu"/><stop offset="1" class="a4w7cpbiw"/></radialGradient><radialGradient id="iAeGCZe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.594)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="zbl0hn4uu"/><stop offset="1" class="a4w7cpbiw"/></radialGradient><radialGradient id="ijcoKse" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 16.774)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="lydnq_bqp"/><stop offset="1" class="mw3_h25bb"/></radialGradient><radialGradient id="imEhC1b" cx="0" cy="0" r="1" gradientTransform="rotate(-62.526 22.58 -3.107)scale(.44028 1.97794)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="ugyr8nbyy"/><stop offset="1" class="xh5cq3bwm"/></radialGradient><radialGradient id="iHjpCSd" cx="0" cy="0" r="1" gradientTransform="matrix(3.15625 8.25793 -4.21158 1.6097 12.419 3.25)" gradientUnits="userSpaceOnUse"><stop class="r871ksz2k"/><stop offset="1" class="m5-y-pbea"/></radialGradient><radialGradient id="iqtWejc" cx="0" cy="0" r="1" gradientTransform="rotate(-124.889 8.671 2.22)scale(3.14147 1.04527)" gradientUnits="userSpaceOnUse"><stop class="s165-bbuq"/><stop offset="1" class="kyulx_bkd"/></radialGradient><radialGradient id="iZzdGwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.99577 -1.29371 0 22.519 2.113)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><filter id="ivOfJFe" width="21.451" height="8.965" x="5.649" y="20.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.27451 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24254"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.376471 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24254" result="effect2_innerShadow_3987_24254"/></filter><filter id="id91NTd" width="8.434" height="11.989" x="16.543" y="9.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.27451 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24254"/></filter><filter id="iy8dEHq" width="8.784" height="12.039" x="7.173" y="9.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.54902 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24254"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.254902 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24254" result="effect2_innerShadow_3987_24254"/></filter><filter id="iD639Ee" width="2.986" height="2.986" x="9.111" y="12.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".1"/></filter><filter id="iYvP7Fc" width="2.986" height="2.986" x="19.904" y="12.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".1"/></filter><filter id="iGcv7Ec" width="3.829" height="3.829" x="11.609" y="11.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".25"/></filter><filter id="iu6wuwd" width="12.021" height="15.258" x="10.24" y="5.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.607843 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24254"/></filter><filter id="i3kgwnd" width="8.186" height="14.251" x="8.271" y="1.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".5"/></filter><filter id="iHKqD6c" width="8.186" height="10.454" x="15.46" y="5.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".5"/></filter><filter id="ii2KLXc" width="11.186" height="6.923" x="10.508" y="4.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.466667 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24254"/></filter><filter id="iB8EVAb" width="8.715" height="5.797" x="11.935" y="4.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".125"/></filter><filter id="ijygJnz" width="3.66" height="3.66" x="11.885" y="11.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".25"/></filter><filter id="irfXmRd" width="2.699" height="1.214" x="11.797" y="11.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.27451 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24254"/></filter><filter id="imT1Dtc" width="2.399" height=".914" x="11.847" y="11.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".075"/></filter><filter id="iIy0vRc" width="2.699" height="1.214" x="17.703" y="11.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.282353 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24254"/></filter><filter id="imLeJ9d" width="2.399" height=".914" x="17.753" y="11.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".075"/></filter><filter id="iTwegFe" width="2.618" height=".92" x="12.269" y="13.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".075"/></filter><filter id="iMnZPSa" width="2.618" height=".92" x="17.16" y="13.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".075"/></filter><filter id="imERtlE" width="3.122" height="4.211" x="14.162" y="13.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".25"/></filter><filter id="i6iZ8mc" width="4.199" height="1.729" x="13.906" y="17.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".05"/></filter><filter id="iWFlJld" width="6.686" height="12.451" x="8.599" y="2.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.556863 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24254"/></filter><filter id="itmsMie" width="6.436" height="12.501" x="17.239" y="2.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24254"/></filter><filter id="iSzxbGb" width="6.909" height="12.89" x="17.106" y="1.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".5"/></filter><filter id="i7lkFkd" width="2.811" height="6.368" x="8.719" y="8.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".375"/></filter><filter id="iil8HHb" width="5.64" height="8.855" x="9.423" y="1.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24254" stdDeviation=".375"/></filter><linearGradient id="ifhQ5sh" x1="14.021" x2="11.81" y1="12.06" y2="12.524" gradientUnits="userSpaceOnUse"><stop class="h41615boj"/><stop offset="1" class="smh61-b0a"/></linearGradient><linearGradient id="iKoRkUb" x1="19.989" x2="17.81" y1="12.407" y2="11.922" gradientUnits="userSpaceOnUse"><stop class="h41615boj"/><stop offset="1" class="smh61-b0a"/></linearGradient><linearGradient id="iqZMtxd" x1="14.936" x2="12.494" y1="14.001" y2="14.001" gradientUnits="userSpaceOnUse"><stop offset=".045" class="di1p0_b3t"/><stop offset=".32" class="g8-pnsbec"/><stop offset=".794" class="g8-pnsbec"/><stop offset="1" class="di1p0_b3t"/></linearGradient><linearGradient id="iA2LLyb" x1="19.826" x2="17.385" y1="14.001" y2="14.001" gradientUnits="userSpaceOnUse"><stop offset=".045" class="di1p0_b3t"/><stop offset=".32" class="g8-pnsbec"/><stop offset=".794" class="g8-pnsbec"/><stop offset="1" class="di1p0_b3t"/></linearGradient><linearGradient id="iqtupOb" x1="17.061" x2="15.162" y1="15.485" y2="15.672" gradientUnits="userSpaceOnUse"><stop offset=".218" class="p_drcebab"/><stop offset="1" class="tdgu1u54k"/></linearGradient><linearGradient id="i8MBbBb" x1="22.016" x2="22.016" y1="3.198" y2="14.57" gradientUnits="userSpaceOnUse"><stop offset=".786" class="r245klenb"/><stop offset="1" class="qs8hc0yqa"/></linearGradient><linearGradient id="ifu1BsH" x1="10.124" x2="10.124" y1="13.113" y2="8.282" gradientUnits="userSpaceOnUse"><stop class="n6_y6k2_m"/><stop offset="1" class="bd1m8wbbp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-getting-massage" /></template>
<style>
.a4w7cpbiw {
  stop-color: var(--svg-color--b54919, #B54919);
}

.a9r_rhbce {
  d: path("M13.75 20.016a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.ab_0q75ef {
  d: path("m21.075 8.653l-2.021 1.435a.61.61 0 0 1-.791-.073a.554.554 0 0 1 .027-.8a51 51 0 0 1 1.99-1.723c.876-.707 1.051-1.773 1.03-2.218V2.788h1.705V13.12a.57.57 0 0 1-.58.558a.57.57 0 0 1-.578-.559V9.035c0-.388-.458-.612-.782-.381");
}

.ar3j2pbeq {
  fill: var(--svg-color--ffdf38, #FFDF38);
  d: path("M10.173 5.155v-2.9h1.469V5.79a1 1 0 0 0 .28.693l2.262 2.349a.46.46 0 0 1-.636.663L11.184 7.4a3 3 0 0 1-1.011-2.246");
}

.b1hif_bph {
  stop-color: var(--svg-color--fda828, #FDA828);
}

.b2cgmuy3t {
  stop-color: var(--svg-color--9574dd, #9574DD);
  stop-opacity: 0;
}

.bb3wbnbfg {
  stop-color: var(--svg-color--cd9640, #CD9640);
}

.bd1m8wbbp {
  stop-color: var(--svg-color--ffcb3b, #FFCB3B);
  stop-opacity: 0;
}

.bmc1y-ezx {
  d: path("M13.135 6.297c-.313.207-.83.467-.95.438c1.038 3.687 4.893 3.74 6.59 3.437L20.4 8.61V6.735c-1.164-.57-3.218-1.828-4.671-1.742s-2.204 1.047-2.594 1.304");
}

.bpzdz3q1w {
  fill: var(--svg-color--ffad20, #FFAD20);
  d: path("M13.75 20.016a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.cibck0b0g {
  stop-color: var(--svg-color--ffb129, #FFB129);
}

.cpsescblj {
  stop-color: var(--svg-color--e77421, #E77421);
  stop-opacity: 0;
}

.d3q0pzbia {
  width: 11.521px;
  height: 15.258px;
  x: 10.24px;
  y: 5.822px;
  rx: 5.76px;
}

.di1p0_b3t {
  stop-color: var(--svg-color--bf6a57, #BF6A57);
}

.dmanwfbnw {
  stop-color: var(--svg-color--fdb530, #FDB530);
}

.dnja8ltqt {
  stop-color: var(--svg-color--c26117, #C26117);
}

.dubz53-6i {
  stop-color: var(--svg-color--ffd73e, #FFD73E);
}

.e_hhqfp0c {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.349c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.056.243.013.25.135a.15.15 0 0 1-.014.077c-.76 1.47-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.122.142-.192.25-.135Z");
}

.ee3mn7b4s {
  cx: 10.604px;
  cy: 14.381px;
  r: 1.293px;
  fill: var(--svg-color--d07d1c, #D07D1C);
}

.eurnqk27z {
  stop-color: var(--svg-color--ffd52b, #FFD52B);
}

.f7m1yfx-m {
  stop-color: var(--svg-color--9b4607, #9B4607);
}

.fs8190bqd {
  stop-color: var(--svg-color--f49512, #F49512);
  stop-opacity: 0;
}

.fsuatq1-u {
  d: path("M5.65 29.745h20.7c-.494-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.665");
}

.ft5dv1b6b {
  fill: none;
}

.fvb5ljbqc {
  stop-color: var(--svg-color--ffce3b, #FFCE3B);
  stop-opacity: 0;
}

.g0xv48b6h {
  stop-color: var(--svg-color--d88f27, #D88F27);
}

.g8-pnsbec {
  stop-color: var(--svg-color--93534a, #93534A);
}

.ghvr_e1bi {
  stop-color: var(--svg-color--f39423, #F39423);
}

.gk5ny2bsn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 14c.146.165.536.45 1.023.47c.617.023.95-.305 1.145-.47");
}

.gm7csc62e {
  stop-color: var(--svg-color--ee861f, #EE861F);
}

.gpmwkmbvk {
  stroke: var(--svg-color--ba3d44, #BA3D44);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.928 12.524c-.258-.207-.883-.578-1.95-.43");
}

.gr2fu0gnc {
  stop-color: var(--svg-color--e77421, #E77421);
}

.gyw7vvbbr {
  stop-color: var(--svg-color--f4962b, #F4962B);
}

.h41615boj {
  stop-color: var(--svg-color--cd6f5c, #CD6F5C);
}

.h41hxoaeu {
  stop-color: var(--svg-color--c26117, #C26117);
  stop-opacity: 0;
}

.he4rjee5h {
  d: path("m9.469 9.027l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.hxgqgkbof {
  fill: var(--svg-color--f4982a, #F4982A);
  d: path("M15.872 13.727c-.163 0-.248.093-.297.254l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.16-.045-.254-.209-.254");
}

.icpnccptv {
  stop-color: var(--svg-color--bf9a3b, #BF9A3B);
}

.ihclt-v2y {
  d: path("M13.209 8.506c-.782 1.248-2.158 2.114-2.7 2.314V6.672c.265 0 1.576-.142 2.168-.515c.694-.437 1.337-1.637 3.352-1.637c1.071 0 1.808.377 2.923 1.337c.882.652 2.182.697 2.743.652v4.534c-.517-.373-1.428-.41-1.846-.428h-3.375c-1.744 0-2.934-1.39-3.265-2.11");
}

.isb53_mmq {
  stop-color: var(--svg-color--ffdd41, #FFDD41);
}

.iu2c2hjkx {
  stop-color: var(--svg-color--df711c, #DF711C);
}

.j5d-p-qvc {
  d: path("M8.599 2.255h3.425v3.609c0 .34.227.998.684 1.38a78 78 0 0 1 1.727 1.631c.476.46.463 1.207-.026 1.653c-.454.413-1.088.35-1.553-.052l-.98-.714a.54.54 0 0 0-.746.042a.5.5 0 0 0-.133.337v3.21c0 .638-.537 1.156-1.2 1.156S8.6 13.989 8.6 13.35z");
}

.jj-4sebrf {
  d: path("M23.425 2.255h-3.426v3.609c0 .34-.226.998-.683 1.38a78 78 0 0 0-1.727 1.631a1.124 1.124 0 0 0 .026 1.653c.453.413 1.09.35 1.554-.052l.978-.714a.54.54 0 0 1 .747.042a.5.5 0 0 1 .133.337v3.21c0 .638.537 1.156 1.199 1.156s1.199-.518 1.199-1.157z");
}

.jlfms8b5j {
  stop-color: var(--svg-color--cd791e, #CD791E);
}

.k0led5buk {
  fill: var(--svg-color--ffb62d, #FFB62D);
  d: path("M23.425 2.255h-3.426v3.609c0 .34-.226.998-.683 1.38a78 78 0 0 0-1.727 1.631a1.124 1.124 0 0 0 .026 1.653c.453.413 1.09.35 1.554-.052l.978-.714a.54.54 0 0 1 .747.042a.5.5 0 0 1 .133.337v3.21c0 .638.537 1.156 1.199 1.156s1.199-.518 1.199-1.157z");
}

.k4lo-hb9q {
  stop-color: var(--svg-color--7c4fa2, #7C4FA2);
  stop-opacity: 0;
}

.kegnawh0e {
  stop-color: var(--svg-color--f4962b, #F4962B);
  stop-opacity: 0;
}

.km7u9bcta {
  stop-color: var(--svg-color--cd8135, #CD8135);
}

.kyulx_bkd {
  stop-color: var(--svg-color--ffa92e, #FFA92E);
  stop-opacity: 0;
}

.lydnq_bqp {
  stop-color: var(--svg-color--ed8f30, #ED8F30);
}

.m5-y-pbea {
  stop-color: var(--svg-color--ffdf3b, #FFDF3B);
  stop-opacity: 0;
}

.m5pfi3anb {
  stop-color: var(--svg-color--d37f20, #D37F20);
  stop-opacity: 0;
}

.ma08wxbns {
  d: path("M22.646 8.266H19.22l-.684-1.812c0 .352.457.528 0 .923a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.428 1.09.362 1.554-.055l.978-.74a.527.527 0 0 1 .88.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.me4cmnnbt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 14c.146.165.536.45 1.024.47c.617.023.949-.305 1.144-.47");
}

.mnbqkjntq {
  stop-color: var(--svg-color--ffb91d, #FFB91D);
  stop-opacity: 0;
}

.mw3_h25bb {
  stop-color: var(--svg-color--ffb520, #FFB520);
  stop-opacity: 0;
}

.myrtd-bfw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.928 12.47c-.258-.208-.883-.579-1.95-.43");
}

.n-u20jcue {
  stop-color: var(--svg-color--fbba28, #FBBA28);
  stop-opacity: 0;
}

.n3i3hq-br {
  stop-color: var(--svg-color--eb992f, #EB992F);
  stop-opacity: 0;
}

.n6_y6k2_m {
  stop-color: var(--svg-color--ffca3e, #FFCA3E);
}

.na9kkhbsz {
  stop-color: var(--svg-color--ffe041, #FFE041);
  stop-opacity: 0;
}

.nq7lirltb {
  fill: var(--svg-color--89004e, #89004E);
  d: path("M14.357 17.349c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.056.243.013.25.135a.15.15 0 0 1-.014.077c-.76 1.47-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.122.142-.192.25-.135");
}

.oelw8ib5n {
  d: path("M8.154 11.892c.56-.982.53-1.722.638-2.036l6.665 2.824v8.915h-3.72c-2.443 0-3.523-1.02-4.003-2.22s-.28-2.132-.06-2.794a1.54 1.54 0 0 0-.03-.999c-.452-1.252-.176-2.49.51-3.69");
}

.oggs7wb0o {
  stroke: var(--svg-color--b73e46, #B73E46);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.072 12.524c.258-.207.883-.578 1.95-.43");
}

.oj5myrpqa {
  cx: 21.396px;
  cy: 14.381px;
  r: 1.979px;
}

.oof-goujs {
  stop-color: var(--svg-color--936dd4, #936DD4);
}

.p_drcebab {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
}

.p_ukq-bjv {
  stop-color: var(--svg-color--f28e2a, #F28E2A);
}

.p3lw01bbh {
  stop-color: var(--svg-color--d97513, #D97513);
}

.p6uz8ubkb {
  d: path("M23.846 11.892c-.56-.982-.53-1.722-.639-2.036l-6.664 2.824v8.915h3.72c2.443 0 3.523-1.02 4.003-2.22s.28-2.132.06-2.794a1.54 1.54 0 0 1 .03-.999c.452-1.252.176-2.49-.51-3.69");
}

.p97qg-b4a {
  stop-color: var(--svg-color--b95a08, #B95A08);
}

.p9wfp42yy {
  stop-color: var(--svg-color--ffb611, #FFB611);
}

.pg81w39ph {
  stop-color: var(--svg-color--ffd742, #FFD742);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.pwu8-qxpb {
  stop-color: var(--svg-color--bf9a3b, #BF9A3B);
  stop-opacity: 0;
}

.qca9cgb6f {
  stop-color: var(--svg-color--eb992f, #EB992F);
}

.qfb1b_nis {
  stop-color: var(--svg-color--f49512, #F49512);
}

.qs8hc0yqa {
  stop-color: var(--svg-color--ffdf40, #FFDF40);
  stop-opacity: 0;
}

.r-5ctobwv {
  stop-color: var(--svg-color--9574dd, #9574DD);
}

.r245klenb {
  stop-color: var(--svg-color--ffdf40, #FFDF40);
}

.r6ifw9b5e {
  stop-color: var(--svg-color--d27f2e, #D27F2E);
}

.r871ksz2k {
  stop-color: var(--svg-color--ffdf3b, #FFDF3B);
}

.rawot7b-t {
  stop-color: var(--svg-color--ffae20, #FFAE20);
  stop-opacity: 0;
}

.rc0rszb3u {
  stop-color: var(--svg-color--6a3874, #6A3874);
}

.rf_171bfc {
  stop-color: var(--svg-color--cd8135, #CD8135);
  stop-opacity: 0;
}

.rjclg2bzq {
  stop-color: var(--svg-color--402452, #402452);
}

.rnpd_y0iu {
  cx: 10.604px;
  cy: 14.381px;
  r: 1.979px;
}

.rrdo8bckr {
  stop-color: var(--svg-color--ffce3b, #FFCE3B);
}

.rul9zob_o {
  stop-color: var(--svg-color--fbba28, #FBBA28);
}

.s165-bbuq {
  stop-color: var(--svg-color--c96a05, #C96A05);
}

.smh61-b0a {
  stop-color: var(--svg-color--cd6f5c, #CD6F5C);
  stop-opacity: 0;
}

.t_e5mbckj {
  stop-color: var(--svg-color--cd9640, #CD9640);
  stop-opacity: 0;
}

.tcuhfk5hu {
  stop-color: var(--svg-color--c08d3e, #C08D3E);
}

.tdgu1u54k {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
  stop-opacity: 0;
}

.u7iwsbb9m {
  d: path("m9.271 2.421l1.516 5.892l1.938-.904c0 .34.199-.38.656 0a78 78 0 0 1 1.727 1.632c.476.46.463 1.207-.027 1.653c-.453.413-1.088.35-1.552-.053l-.98-.713a.54.54 0 0 0-.747.042a.5.5 0 0 0-.132.337v3.209c0 .639-.537 1.156-1.2 1.156s-1.199-.517-1.199-1.156z");
}

.ugyr8nbyy {
  stop-color: var(--svg-color--ffb333, #FFB333);
}

.uj9pdvsyv {
  cx: 13.524px;
  cy: 13.258px;
  r: 1.415px;
}

.ujvo-nb1v {
  cx: 21.396px;
  cy: 14.381px;
  r: 1.293px;
  fill: var(--svg-color--ffc12d, #FFC12D);
}

.v1vlmzb3z {
  d: path("M16 13.641a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.262");
}

.vfen6w6fz {
  cx: 13.715px;
  cy: 13.342px;
  r: 1.33px;
}

.vkcyyxb3b {
  fill: var(--svg-color--ffb52d, #FFB52D);
  d: path("M8.599 2.255h3.425v3.609c0 .34.227.998.684 1.38a78 78 0 0 1 1.727 1.631c.476.46.463 1.207-.026 1.653c-.454.413-1.088.35-1.553-.052l-.98-.714a.54.54 0 0 0-.746.042a.5.5 0 0 0-.133.337v3.21c0 .638-.537 1.156-1.2 1.156S8.6 13.989 8.6 13.35z");
}

.vqnj7hhwz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 14c.146.165.536.45 1.023.47c.617.023.95-.305 1.145-.47");
}

.vukz93b8e {
  stop-color: var(--svg-color--fba42d, #FBA42D);
}

.vy4bnb43g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.494 14c.146.165.536.45 1.024.47c.617.023.949-.305 1.144-.47");
}

.wz5dhy52n {
  fill: var(--svg-color--ffb31f, #FFB31F);
  d: path("M16 13.641a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.262");
}

.xh5cq3bwm {
  stop-color: var(--svg-color--ffb333, #FFB333);
  stop-opacity: 0;
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xw2-3acug {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.072 12.524c.258-.207.883-.578 1.95-.43");
}

.xxerewdbl {
  stop-color: var(--svg-color--623e81, #623E81);
  stop-opacity: 0;
}

.y-z81-bua {
  stop-color: var(--svg-color--725698, #725698);
}

.ye7u2hbjz {
  stop-color: var(--svg-color--d37f20, #D37F20);
}

.yg-qo1umn {
  stop-color: var(--svg-color--ec9433, #EC9433);
  stop-opacity: 0;
}

.zbl0hn4uu {
  stop-color: var(--svg-color--8a374b, #8A374B);
}

</style>
