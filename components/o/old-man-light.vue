<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iTbocjc)"><path fill="url(#iEj82Sb)" class="rd1lgnbgu"/><path fill="url(#iKwPdvc)" class="rd1lgnbgu"/></g><g filter="url(#iB9Kknc)"><path class="j1pbg-y0o"/><path fill="url(#iS96CyE)" class="swrbo5bva"/><path fill="url(#i1SSCLY)" class="swrbo5bva"/></g><g filter="url(#ilkRghe)"><path fill="url(#iTgZVle)" class="d249agblw"/></g><g filter="url(#iWU1JOd)"><path fill="url(#i0qwQZb)" class="d249agblw"/></g><g filter="url(#ic4Pope)"><path fill="url(#i4FjGIb)" class="luj9r7ihb"/></g><g filter="url(#iSlVvec)"><path fill="url(#iCdYPZd)" class="i98wr_osw"/><path fill="url(#ic5xwxd)" class="i98wr_osw"/><path fill="url(#i31XIte)" class="i98wr_osw"/><path fill="url(#iejJwFc)" class="i98wr_osw"/><path fill="url(#ikdv9Eb)" class="i98wr_osw"/><path fill="url(#i6qiD9c)" class="i98wr_osw"/><path fill="url(#icnEWje)" class="i98wr_osw"/><path fill="url(#iqKyFdd)" class="i98wr_osw"/></g><path fill="url(#iqdDrvd)" class="i98wr_osw"/><g filter="url(#ibP5bXc)"><path fill="url(#iRajSWc)" class="cy3rzv3dr"/></g><g filter="url(#i4uFEzc)"><path class="axz1sth2m"/></g><g filter="url(#iFEtQfb)"><path class="njqwu5b_v"/><path fill="url(#igPequb)" class="k0o8-qb-w"/><path fill="url(#idMzbST)" class="k0o8-qb-w"/><path fill="url(#iY3ylEe)" class="k0o8-qb-w"/><path fill="url(#i7xGCqd)" class="k0o8-qb-w"/></g><path class="ukllx6bof"/><path fill="url(#iS65Xwn)" class="w0clelb6x"/><path fill="url(#ibZtuRd)" class="w0clelb6x"/><g filter="url(#i6zBbPd)"><path class="tojnlacke"/><path fill="url(#iGCYGse)" class="r-_4l3gaj"/><path fill="url(#iUMT2WA)" class="r-_4l3gaj"/><path fill="url(#iS4wkgc)" class="r-_4l3gaj"/></g><path stroke="url(#ioKMG6d)" class="tfp97iq8b"/><path class="junw82b_w"/><path class="pbm0lc9zc"/><rect fill="url(#iF1IUQd)" class="m3oll1eyr"/><rect fill="url(#iLa7rPb)" class="mztxcmb0e"/><path class="uyybkkvov"/><path fill="url(#i4FmUqb)" class="z5_zot-mh"/><path class="gp0t4lb2y"/><g filter="url(#i9hboQd)"><path fill="url(#iINItsd)" class="qts6si7xs"/></g><g filter="url(#imFxMce)"><ellipse transform="rotate(-27.914 11.516 16.758)" class="vwj4lsbpo"/><ellipse fill="url(#iAZ4yQb)" transform="rotate(-27.914 11.516 16.758)" class="trz0vabsu"/></g><path class="cby3ndbnw"/><path fill="url(#ivCbssc)" class="ywf9dqbmv"/><path class="fn7u4ccnc"/><g filter="url(#iAWrlOb)"><path class="hlnmfvh-z"/><path fill="url(#inbHoee)" class="zntt4qbzj"/></g><g filter="url(#iIai85c)"><path fill="url(#iBgAnkv)" class="u6f-n_p2q"/></g><g filter="url(#iwZ3yFb)"><path class="hlk1gdb2k"/></g><g filter="url(#iPkW3kb)"><path stroke="url(#it8mAbd)" class="yo7295swp"/></g><g filter="url(#itSrfXb)"><path class="iuetnrbgr"/></g><g filter="url(#iQW1kHc)"><path stroke="url(#iPulIvb)" class="f9sec7bct"/></g><defs><radialGradient id="iKwPdvc" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 39.768 -30.641)scale(1.93052 2.20343)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iS96CyE" cx="0" cy="0" r="1" gradientTransform="matrix(1.64694 -3.0292 1.773 .96396 24.87 19.685)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="i1SSCLY" cx="0" cy="0" r="1" gradientTransform="matrix(.51997 .5147 -.66351 .67031 24.954 18.038)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iTgZVle" cx="0" cy="0" r="1" gradientTransform="matrix(3.31277 0 0 5.79738 4.067 18.038)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="i0qwQZb" cx="0" cy="0" r="1" gradientTransform="matrix(3.31277 0 0 5.79738 4.067 18.038)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iCdYPZd" cx="0" cy="0" r="1" gradientTransform="rotate(152.026 9.34 10.265)scale(17.0552 31.3253)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="am3a9544w"/><stop offset=".84" class="ny0rq0bux"/></radialGradient><radialGradient id="ic5xwxd" cx="0" cy="0" r="1" gradientTransform="rotate(158.66 12.369 6.737)scale(9.9616 12.7935)" gradientUnits="userSpaceOnUse"><stop class="ond3vobfw"/><stop offset="1" class="zwal6gbmi"/></radialGradient><radialGradient id="i31XIte" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.625 3.09375 0 20.935 15.73)" gradientUnits="userSpaceOnUse"><stop class="r1yj9uj4s"/><stop offset="1" class="lx46sjo9a"/></radialGradient><radialGradient id="iejJwFc" cx="0" cy="0" r="1" gradientTransform="rotate(-90 13.88 2.13)scale(3.3125)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="qj8d7fbft"/><stop offset="1" class="fp9zhfbup"/></radialGradient><radialGradient id="ikdv9Eb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35307 -1.63196 1.28997 -1.85996 24.971 10.296)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="zjd19o14z"/><stop offset="1" class="e228jkbci"/></radialGradient><radialGradient id="i6qiD9c" cx="0" cy="0" r="1" gradientTransform="rotate(127.136 .721 6.978)scale(2.8667 2.49422)" gradientUnits="userSpaceOnUse"><stop offset=".476" class="tjym-5l3w"/><stop offset="1" class="sr4_y0b3u"/></radialGradient><radialGradient id="icnEWje" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.75 -4.63513 0 17.688 4.074)" gradientUnits="userSpaceOnUse"><stop class="w10zyd4pa"/><stop offset="1" class="s5wzj_xqm"/></radialGradient><radialGradient id="iqKyFdd" cx="0" cy="0" r="1" gradientTransform="matrix(3.97576 4.25652 -7.55572 7.05734 9.467 6.181)" gradientUnits="userSpaceOnUse"><stop class="vhcqxbc_l"/><stop offset="1" class="oq7tb3b3n"/></radialGradient><radialGradient id="iqdDrvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.8125 26.0906 0 16.125 29.95)" gradientUnits="userSpaceOnUse"><stop class="cz7k6-b_c"/><stop offset="1" class="kqf-u0b-m"/></radialGradient><radialGradient id="i7xGCqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36044 -1.11102 0 16.745 21.03)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="iS65Xwn" cx="0" cy="0" r="1" gradientTransform="rotate(139.273 2.463 6.005)scale(4.16691 7.99724)" gradientUnits="userSpaceOnUse"><stop class="rlhs-hbwc"/><stop offset="1" class="xi80kbc0k"/></radialGradient><radialGradient id="ibZtuRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.04688 -.9516 0 7.09 14.793)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="l9fk14bxd"/><stop offset="1" class="uyez41bsl"/></radialGradient><radialGradient id="iGCYGse" cx="0" cy="0" r="1" gradientTransform="matrix(1.98438 -2.09375 .72837 .69032 24.622 13.23)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="aq7827bba"/><stop offset="1" class="tco_4qs8v"/></radialGradient><radialGradient id="iUMT2WA" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 2.625 -2.01353 -1.12662 25.904 9.074)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="wgw2105cx"/><stop offset="1" class="fj_enu3ru"/></radialGradient><radialGradient id="iS4wkgc" cx="0" cy="0" r="1" gradientTransform="matrix(.32886 -4.54687 .85753 .06202 26.841 16.324)" gradientUnits="userSpaceOnUse"><stop class="bddxqszam"/><stop offset="1" class="bwtw0srgi"/></radialGradient><radialGradient id="i4FmUqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 12.021 17.558)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="zs1u76b3p"/></radialGradient><radialGradient id="iAZ4yQb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.281 3.018)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivCbssc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.158 17.558)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="zs1u76b3p"/></radialGradient><radialGradient id="inbHoee" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.052 3.714)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iTbocjc" width="6.553" height="6.553" x="21.802" y="14.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20093"/></filter><filter id="iB9Kknc" width="4.991" height="4.991" x="22.459" y="15.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20093" stdDeviation=".25"/></filter><filter id="ilkRghe" width="6.503" height="6.303" x="4.067" y="14.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20093"/></filter><filter id="iWU1JOd" width="6.503" height="6.303" x="4.067" y="14.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20093"/></filter><filter id="ic4Pope" width="4.991" height="4.991" x="4.723" y="15.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20093" stdDeviation=".25"/></filter><filter id="iSlVvec" width="20.793" height="25.5" x="6.104" y="4.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.678431 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20093"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.870588 0 0 0 0 0.745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_20093" result="effect2_innerShadow_3987_20093"/></filter><filter id="ibP5bXc" width="11.918" height="9.719" x="15.036" y="6.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20093" stdDeviation="1"/></filter><filter id="i4uFEzc" width="4.796" height="6.408" x="13.272" y="16.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20093" stdDeviation=".375"/></filter><filter id="iFEtQfb" width="3.796" height="5.408" x="14.272" y="16.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20093" stdDeviation=".125"/></filter><filter id="i6zBbPd" width="4.3" height="9.2" x="23.17" y="7.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.568627 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20093"/></filter><filter id="i9hboQd" width="1.493" height="1.594" x="12.245" y="16.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20093" stdDeviation=".1"/></filter><filter id="imFxMce" width="1.529" height="1.141" x="10.751" y="16.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20093" stdDeviation=".05"/></filter><filter id="iAWrlOb" width="1.294" height="1.125" x="18.875" y="16.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20093" stdDeviation=".05"/></filter><filter id="iIai85c" width="1.316" height="1.357" x="20.528" y="16.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20093" stdDeviation=".1"/></filter><filter id="iwZ3yFb" width="5.214" height="3" x="18.514" y="11.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20093"/></filter><filter id="iPkW3kb" width="4.458" height="2.061" x="18.789" y="12.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20093" stdDeviation=".2"/></filter><filter id="itSrfXb" width="5.214" height="3" x="8.912" y="11.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20093"/></filter><filter id="iQW1kHc" width="4.458" height="2.061" x="9.093" y="12.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20093" stdDeviation=".2"/></filter><linearGradient id="iEj82Sb" x1="27.005" x2="25.459" y1="15.978" y2="20.766" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="i4FjGIb" x1="7.218" x2="5.934" y1="18.597" y2="18.597" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iRajSWc" x1="15.727" x2="30.915" y1="14.168" y2="8.73" gradientUnits="userSpaceOnUse"><stop class="yxv2rcevr"/><stop offset="1" class="krb9qn5ow"/></linearGradient><linearGradient id="igPequb" x1="14.652" x2="16.3" y1="20.008" y2="20.008" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="idMzbST" x1="17.818" x2="16.017" y1="20.599" y2="20.574" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iY3ylEe" x1="16.512" x2="16.512" y1="21.957" y2="20.909" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="ioKMG6d" x1="14.236" x2="15.047" y1="24.898" y2="23.616" gradientUnits="userSpaceOnUse"><stop class="qk9uw01xk"/><stop offset=".663" class="itkl-szhz"/></linearGradient><linearGradient id="iF1IUQd" x1="13.17" x2="17.938" y1="8.093" y2="8.093" gradientUnits="userSpaceOnUse"><stop class="wpkc23bgv"/><stop offset="1" class="jbk5tgbif"/></linearGradient><linearGradient id="iLa7rPb" x1="13.313" x2="18.431" y1="10.472" y2="10.472" gradientUnits="userSpaceOnUse"><stop class="wszgbkbyl"/><stop offset="1" class="ql2vfvfmz"/></linearGradient><linearGradient id="iINItsd" x1="13.408" x2="12.823" y1="17.036" y2="17.397" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBgAnkv" x1="21.608" x2="21.023" y1="17.036" y2="17.397" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="it8mAbd" x1="22.646" x2="19.154" y1="13.488" y2="13.488" gradientUnits="userSpaceOnUse"><stop class="kwz2g5lgk"/><stop offset="1" class="mv5v459od"/></linearGradient><linearGradient id="iPulIvb" x1="13.147" x2="9.693" y1="12.627" y2="13.97" gradientUnits="userSpaceOnUse"><stop class="kwz2g5lgk"/><stop offset="1" class="mv5v459od"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:old-man-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.am3a9544w {
  stop-color: var(--svg-color--ffdcc1, #FFDCC1);
}

.aq7827bba {
  stop-color: var(--svg-color--8f8286, #8F8286);
}

.axz1sth2m {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.638 17.833l-1.571 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.9-3.1c-.227-.655-.429-.7-.729 0");
}

.bddxqszam {
  stop-color: var(--svg-color--b1adb0, #B1ADB0);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.bwtw0srgi {
  stop-color: var(--svg-color--b1adb0, #B1ADB0);
  stop-opacity: 0;
}

.cby3ndbnw {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.547 15.54c1.218 0 2.247.84 2.526 1.974a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cy3rzv3dr {
  d: path("m24.11 8.519l-5.739 1.913a1.953 1.953 0 0 0 .877 3.788l5.706-.764z");
}

.cz7k6-b_c {
  stop-color: var(--svg-color--b57997, #B57997);
}

.d249agblw {
  d: path("M7.218 21.19a3.152 3.152 0 1 0 0-6.303a3.152 3.152 0 0 0 0 6.303");
}

.e228jkbci {
  stop-color: var(--svg-color--efb699, #EFB699);
  stop-opacity: 0;
}

.f9sec7bct {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.951 12.645c-.883-.07-2.195.039-3.258.843");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fj_enu3ru {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
  stop-opacity: 0;
}

.fn7u4ccnc {
  fill: var(--svg-color--000, #000);
  d: path("M19.209 17.71c0-.529.423-.952.953-.952s.953.423.953.953a.94.94 0 0 1-.106.438h-1.687a.86.86 0 0 1-.113-.439");
}

.fp9zhfbup {
  stop-color: var(--svg-color--d0958e, #D0958E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.gp0t4lb2y {
  fill: var(--svg-color--000, #000);
  d: path("M12.97 17.71a.95.95 0 0 0-.952-.952a.95.95 0 0 0-.953.953c0 .158.037.31.106.438h1.686a.95.95 0 0 0 .114-.438");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hlk1gdb2k {
  stroke: var(--svg-color--8a8a8a, #8A8A8A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("M19.389 12.95c.71-.095 2.086-.079 3.164.812");
}

.hlnmfvh-z {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.04 16.398c.118.159-.13.352-.412.563s-.49.359-.609.2s.014-.458.296-.668s.606-.253.724-.095");
}

.i98wr_osw {
  d: path("M15.27 4.45c-5.2 0-9.2 4.4-8.9 9.5l.8 10.4c.3 3.3 2.8 5.6 6 5.6h6c3.1 0 5.7-2.3 6-5.6l.7-10.4c.4-5.2-3.7-9.5-8.9-9.5z");
}

.itkl-szhz {
  stop-color: var(--svg-color--e5afa6, #E5AFA6);
  stop-opacity: 0;
}

.iuetnrbgr {
  stroke: var(--svg-color--8a8a8a, #8A8A8A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("M12.951 12.95c-.71-.095-2.086-.079-3.164.812");
}

.j1pbg-y0o {
  fill: var(--svg-color--e4af9a, #E4AF9A);
  d: path("M24.954 20.034a1.995 1.995 0 1 0 0-3.991a1.995 1.995 0 0 0 0 3.99");
}

.jbk5tgbif {
  stop-color: var(--svg-color--f5b6a1, #F5B6A1);
}

.junw82b_w {
  fill: var(--svg-color--ffbcae, #FFBCAE);
  d: path("M18.11 18.733a.5.5 0 0 1 .706.039c.195.218.377.37.612.474c.24.106.575.18 1.095.18a.5.5 0 1 1 0 1c-.612 0-1.094-.087-1.499-.266c-.409-.18-.701-.44-.954-.721a.5.5 0 0 1 .04-.706");
}

.k0o8-qb-w {
  d: path("m15.567 17.557l-1 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.956-3.1c-.226-.654-.944-.7-1.244 0");
}

.kqf-u0b-m {
  stop-color: var(--svg-color--d49b9d, #D49B9D);
  stop-opacity: 0;
}

.krb9qn5ow {
  stop-color: var(--svg-color--fcc7a6, #FCC7A6);
  stop-opacity: 0;
}

.kwz2g5lgk {
  stop-color: var(--svg-color--a8a7a9, #A8A7A9);
}

.l9fk14bxd {
  stop-color: var(--svg-color--735551, #735551);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.luj9r7ihb {
  d: path("M7.218 20.034a1.995 1.995 0 1 0 0-3.991a1.995 1.995 0 0 0 0 3.99");
}

.lx46sjo9a {
  stop-color: var(--svg-color--f4b7a7, #F4B7A7);
  stop-opacity: 0;
}

.m3oll1eyr {
  width: 6px;
  height: 1px;
  x: 13.17px;
  y: 7.093px;
  rx: 0.5px;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mv5v459od {
  stop-color: var(--svg-color--a8a7a9, #A8A7A9);
  stop-opacity: 0;
}

.mztxcmb0e {
  width: 10px;
  height: 1px;
  x: 11.126px;
  y: 9.472px;
  rx: 0.5px;
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.njqwu5b_v {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.567 17.557l-1 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.956-3.1c-.226-.654-.944-.7-1.244 0");
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ond3vobfw {
  stop-color: var(--svg-color--ffe0bf, #FFE0BF);
}

.oq7tb3b3n {
  stop-color: var(--svg-color--d5a68b, #D5A68B);
  stop-opacity: 0;
}

.pbm0lc9zc {
  fill: var(--svg-color--e09b93, #E09B93);
  d: path("M13.335 18.76a.5.5 0 0 1 .724.69l-.001.001l-.002.002l-.004.004l-.011.012l-.038.036q-.047.046-.13.115a3.56 3.56 0 0 1-2.255.806a.5.5 0 1 1-.001-1a2.56 2.56 0 0 0 1.718-.666");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qj8d7fbft {
  stop-color: var(--svg-color--d0958e, #D0958E);
}

.qk9uw01xk {
  stop-color: var(--svg-color--e5afa6, #E5AFA6);
}

.ql2vfvfmz {
  stop-color: var(--svg-color--f7b9a7, #F7B9A7);
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qts6si7xs {
  d: path("M13.538 17.515c0-.538-.437-.896-.556-1.005l-.537.52l.33.674z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-_4l3gaj {
  d: path("M23.904 11.498a2 2 0 1 1 3.246-1.26l-.409 5.714c-.04.562-.508.997-1.071.997v-3.526a1 1 0 0 0-.366-.774L23.9 11.5z");
}

.r1yj9uj4s {
  stop-color: var(--svg-color--f4b7a7, #F4B7A7);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rd1lgnbgu {
  d: path("M24.954 21.19a3.152 3.152 0 1 0 0-6.303a3.152 3.152 0 0 0 0 6.303");
}

.rlhs-hbwc {
  stop-color: var(--svg-color--bbb6b3, #BBB6B3);
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.s5wzj_xqm {
  stop-color: var(--svg-color--eec5a9, #EEC5A9);
  stop-opacity: 0;
}

.sr4_y0b3u {
  stop-color: var(--svg-color--c38c7c, #C38C7C);
  stop-opacity: 0;
}

.swrbo5bva {
  d: path("M24.954 20.034a1.995 1.995 0 1 0 0-3.991a1.995 1.995 0 0 0 0 3.99");
}

.tco_4qs8v {
  stop-color: var(--svg-color--8f8286, #8F8286);
  stop-opacity: 0;
}

.tfp97iq8b {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.61 23.126a.335.335 0 0 0-.4.069a.305.305 0 0 0-.034.392a3.58 3.58 0 0 0 2.994 1.6a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607a5.54 5.54 0 0 1-2.56-.607Z");
}

.tjym-5l3w {
  stop-color: var(--svg-color--c38c7c, #C38C7C);
}

.tojnlacke {
  fill: var(--svg-color--9f9aa1, #9F9AA1);
  d: path("M23.904 11.498a2 2 0 1 1 3.246-1.26l-.409 5.714c-.04.562-.508.997-1.071.997v-3.526a1 1 0 0 0-.366-.774L23.9 11.5z");
}

.trz0vabsu {
  cx: 11.516px;
  cy: 16.758px;
  rx: 0.726px;
  ry: 0.368px;
}

.u6f-n_p2q {
  d: path("M21.644 17.491a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.ukllx6bof {
  fill: var(--svg-color--7f7680, #7F7680);
  d: path("M8.356 11.498a2 2 0 1 0-3.245-1.26l.407 5.714c.04.562.508.99 1.072.99v-3.52a1 1 0 0 1 .366-.773l1.403-1.15z");
}

.uyez41bsl {
  stop-color: var(--svg-color--735551, #735551);
  stop-opacity: 0;
}

.uyybkkvov {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.632 15.54c-1.218 0-2.246.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.vhcqxbc_l {
  stop-color: var(--svg-color--d5a68b, #D5A68B);
}

.vwj4lsbpo {
  cx: 11.516px;
  cy: 16.758px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.w0clelb6x {
  d: path("M8.356 11.498a2 2 0 1 0-3.245-1.26l.407 5.714c.04.562.508.99 1.072.99v-3.52a1 1 0 0 1 .366-.773l1.403-1.15z");
}

.w10zyd4pa {
  stop-color: var(--svg-color--eec5a9, #EEC5A9);
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wgw2105cx {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
}

.wpkc23bgv {
  stop-color: var(--svg-color--e1a592, #E1A592);
}

.wszgbkbyl {
  stop-color: var(--svg-color--da9d8e, #DA9D8E);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xi80kbc0k {
  stop-color: var(--svg-color--807680, #807680);
  stop-opacity: 0;
}

.yo7295swp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.389 12.645c.883-.07 2.195.039 3.258.843");
}

.ywf9dqbmv {
  d: path("M20.162 16.047a1.664 1.664 0 0 1 1.603 2.102h-3.214a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.67-1.663");
}

.yxv2rcevr {
  stop-color: var(--svg-color--fcc7a6, #FCC7A6);
}

.z5_zot-mh {
  d: path("M12.018 16.046a1.664 1.664 0 0 0-1.604 2.103h3.215a1.7 1.7 0 0 0 .06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zjd19o14z {
  stop-color: var(--svg-color--efb699, #EFB699);
}

.zntt4qbzj {
  d: path("M20.04 16.398c.118.159-.13.352-.412.563s-.49.359-.609.2s.014-.458.296-.668s.606-.253.724-.095");
}

.zs1u76b3p {
  stop-color: var(--svg-color--5d4139, #5D4139);
}

.zwal6gbmi {
  stop-color: var(--svg-color--ffe0bf, #FFE0BF);
  stop-opacity: 0;
}

</style>
