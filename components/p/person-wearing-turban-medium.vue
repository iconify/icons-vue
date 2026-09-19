<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iz2Aq4r)"><path fill="url(#iKtp3bd)" class="jnxizgjym"/><path fill="url(#iTNMesh)" class="jnxizgjym"/></g><path fill="url(#izsutGc)" class="jqs5mrb2n"/><path fill="url(#ivxoA0l)" class="jqs5mrb2n"/><path fill="url(#iiu50Zd)" class="jqs5mrb2n"/><path fill="url(#iJeJmOS)" class="jqs5mrb2n"/><path fill="url(#iXYUjpV)" class="jqs5mrb2n"/><path fill="url(#ijdKVId)" class="jqs5mrb2n"/><path fill="url(#iIL3exd)" class="jqs5mrb2n"/><path fill="url(#iMaEDdd)" class="jqs5mrb2n"/><g filter="url(#iMACpqh)"><path class="bvn31e4uo"/></g><g filter="url(#ixqHuqc)"><path class="jx2zvtbqq"/><path fill="url(#iZRm9Ae)" class="gtmobbk9i"/><path fill="url(#ixgayfb)" class="gtmobbk9i"/><path fill="url(#i1XB0nc)" class="gtmobbk9i"/><path fill="url(#i35WrhX)" class="gtmobbk9i"/></g><g filter="url(#iHJrqui)"><path fill="url(#i8PXACe)" class="iwg79bpyi"/></g><g filter="url(#iqjxwsd)"><path stroke="url(#iIPOjzd)" class="jh2vskc2o"/></g><path fill="url(#iJuLXeb)" class="pga49oy6q"/><g filter="url(#ijqAMtc)"><path class="cnmw0ztyt"/></g><g filter="url(#iA3ULPE)"><path class="ogdek8h1a"/></g><path class="hso5zgb1o"/><path fill="url(#iGnPcMc)" class="nr-u1ybra"/><path class="tid71jz-b"/><g filter="url(#ivvYEub)"><path class="z-wmaubks"/><path fill="url(#ikKcHvb)" class="esqjjybhw"/></g><g filter="url(#iDrr2Vc)"><path fill="url(#iuz6Jfe)" class="g-0c2yb0v"/></g><path class="ff-0vv13w"/><path fill="url(#i4b6Mdb)" class="y7cq1ga0i"/><path class="p0q8klbjo"/><g filter="url(#iJ7EXyb)"><path fill="url(#iqYRQxc)" class="kch_6zz7f"/></g><g filter="url(#igMbXJc)"><ellipse transform="rotate(-27.914 11.415 16.643)" class="v4iliwb4c"/><ellipse fill="url(#iJKcMHe)" transform="rotate(-27.914 11.415 16.643)" class="l168mt3hr"/></g><path fill="url(#iVuUXte)" class="tvk9hnoys"/><path fill="url(#ij8Xvgb)" class="tvk9hnoys"/><path fill="url(#iou9aUd)" class="tvk9hnoys"/><path fill="url(#i3OowLc)" class="tvk9hnoys"/><path fill="url(#iEQeiVW)" class="v-pwvkbrl"/><path fill="url(#iVQJNQb)" class="v-pwvkbrl"/><g filter="url(#ipooAgd)"><path fill="url(#iqlqWLd)" class="lljj_ntoi"/></g><g filter="url(#ik3amPd)"><path fill="url(#i7kObGC)" class="qm1rc5b9k"/></g><g filter="url(#ijeJ3Td)"><path class="yehorz89n"/></g><g filter="url(#irCmDob)"><path class="hc-28-bvv"/></g><path fill="url(#iGGdowe)" class="fv2bdy80c"/><path fill="url(#ikXG6ld)" class="fv2bdy80c"/><path fill="url(#igVSNEd)" class="fv2bdy80c"/><path fill="url(#iGGdowe)" class="fv2bdy80c"/><path fill="url(#ikXG6ld)" class="fv2bdy80c"/><path fill="url(#igVSNEd)" class="fv2bdy80c"/><g filter="url(#irgtlGc)"><path fill="url(#ik4cp6d)" class="adprot6ba"/><path fill="url(#ipwr0Zc)" class="adprot6ba"/></g><g filter="url(#iy7B99b)"><path fill="url(#ioWjwqc)" class="rw1r_lbur"/></g><path fill="url(#iiFcNjb)" class="rw1r_lbur"/><path fill="url(#i18kaNe)" class="rw1r_lbur"/><path fill="url(#ieiGMfc)" class="rw1r_lbur"/><g filter="url(#iNzpVHe)"><path fill="url(#iTZlAyz)" class="x5z86eb3s"/></g><path fill="url(#iaQDdkc)" class="x5z86eb3s"/><path fill="url(#i7Uohud)" class="x5z86eb3s"/><path fill="url(#iJ7zgee)" class="x5z86eb3s"/><path fill="url(#iCwANze)" class="x5z86eb3s"/><path fill="url(#iWN4afc)" class="x5z86eb3s"/><g filter="url(#i2NQosB)"><path fill="url(#isXsNHe)" class="n1mxiybya"/><path fill="url(#irYUE9m)" class="n1mxiybya"/><path fill="url(#iksQM8X)" class="n1mxiybya"/><path fill="url(#iIXFaHd)" class="n1mxiybya"/><path fill="url(#ixg6Igc)" class="n1mxiybya"/></g><g filter="url(#iysXE6c)"><path fill="url(#iENyh4d)" class="pf4hb6beg"/></g><path fill="url(#iB1t3Hb)" class="pf4hb6beg"/><path fill="url(#iVTw2Il)" class="pf4hb6beg"/><defs><radialGradient id="iKtp3bd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.79891 0 0 -17.4657 21.244 18.534)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iTNMesh" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25996 5.3875 -4.44931 -2.69227 20.532 9.23)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="ivxoA0l" cx="0" cy="0" r="1" gradientTransform="matrix(0 21.1314 -18.767 0 17.05 9.568)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="bd-wa8btn"/><stop offset=".988" class="otf1mnoto"/></radialGradient><radialGradient id="iiu50Zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14599 2.65758 0 20.581 16.08)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iJeJmOS" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 13.964 2.211)scale(2.04495 2.227)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iXYUjpV" cx="0" cy="0" r="1" gradientTransform="rotate(176.39 10.891 10.543)scale(15.92 40.6384)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="ijdKVId" cx="0" cy="0" r="1" gradientTransform="matrix(7.35714 -7.02917 2.07608 2.17295 2.278 15.006)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iIL3exd" cx="0" cy="0" r="1" gradientTransform="matrix(-.43884 4.6671 -1.86697 -.17555 26.374 13.082)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iMaEDdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.62879 -3.12906 0 11.86 17.608)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="ixgayfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .45617 -1.43367 0 16.871 21.077)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="i35WrhX" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16205 1.40176 -2.25273 -5.08167 17.088 20.012)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iJuLXeb" cx="0" cy="0" r="1" gradientTransform="rotate(-26.18 61.954 -19.78)scale(4.54372 18.2806)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iGnPcMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51616 -2.41162 0 20.078 16.822)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ikKcHvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4334 -.5585 .7689 -.59669 19.651 16.979)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4b6Mdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51624 -2.41174 0 11.922 16.821)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iJKcMHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.01446 -.92332 1.10987 -.01738 11.387 17.231)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ij8Xvgb" cx="0" cy="0" r="1" gradientTransform="matrix(1.1746 4.19213 -3.99962 1.12067 24.63 16.848)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iou9aUd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47217 -2.02032 1.69343 1.23398 25.303 17.866)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="i3OowLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.09696 -2.89737 3.87128 1.46568 25.516 18.188)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iVQJNQb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09887 0 0 -3.46033 6.814 18.046)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iqlqWLd" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 2.639 9.315)scale(1.73773 1.78171)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iGGdowe" cx="0" cy="0" r="1" gradientTransform="matrix(-.84218 3.75478 -8.78476 -1.97039 26.108 4.961)" gradientUnits="userSpaceOnUse"><stop class="s6vdf8bty"/><stop offset=".789" class="lxkykv_ud"/></radialGradient><radialGradient id="ikXG6ld" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 .53125 -1.15317 4.54483 20.574 6.594)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="q2rl-9b2o"/><stop offset="1" class="fi285-b6u"/></radialGradient><radialGradient id="igVSNEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -2.625 6.33197 3.61827 22.512 10.438)" gradientUnits="userSpaceOnUse"><stop class="p6ygghbxv"/><stop offset="1" class="ih_njzbst"/></radialGradient><radialGradient id="ik4cp6d" cx="0" cy="0" r="1" gradientTransform="matrix(.17188 2.91016 -14.53547 .85847 21.48 1.934)" gradientUnits="userSpaceOnUse"><stop class="nsg0945ca"/><stop offset="1" class="mcdrc7blw"/></radialGradient><radialGradient id="ipwr0Zc" cx="0" cy="0" r="1" gradientTransform="matrix(1.45313 0 0 5.1925 21.027 3.25)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="w7pk8_-qm"/><stop offset="1" class="wfm74pxcd"/></radialGradient><radialGradient id="iiFcNjb" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 1.71875 -3.03125 4.35398 17.918 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="hc5vad6zv"/><stop offset="1" class="m71s56bwv"/></radialGradient><radialGradient id="i18kaNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.93844 1.49148 0 24.88 14.418)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="uwloccuzy"/><stop offset="1" class="rrovopbjp"/></radialGradient><radialGradient id="ieiGMfc" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 0 0 .30337 18.98 8.594)" gradientUnits="userSpaceOnUse"><stop class="w98e9_6zv"/><stop offset="1" class="phr-zrige"/></radialGradient><radialGradient id="iTZlAyz" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28125 -.09372 .19553 -8.93238 21.793 5.5)" gradientUnits="userSpaceOnUse"><stop class="qnoj66lkr"/><stop offset="1" class="s_fkwccyi"/></radialGradient><radialGradient id="iaQDdkc" cx="0" cy="0" r="1" gradientTransform="matrix(11.55068 3.52232 -4.80864 15.76891 9.357 5.655)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="rjs9uccph"/><stop offset=".952" class="x7ia8vuzd"/></radialGradient><radialGradient id="i7Uohud" cx="0" cy="0" r="1" gradientTransform="matrix(1.11064 -4.72815 1.61144 .37853 17.068 4.512)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="zz39r5b3o"/><stop offset="1" class="wvn8vtban"/></radialGradient><radialGradient id="iJ7zgee" cx="0" cy="0" r="1" gradientTransform="matrix(-.06346 1.33277 -6.75892 -.32185 9.42 7.305)" gradientUnits="userSpaceOnUse"><stop class="biviy7bfr"/><stop offset="1" class="ednzh9b6g"/></radialGradient><radialGradient id="iCwANze" cx="0" cy="0" r="1" gradientTransform="matrix(-13.48639 2.82409 -3.69438 -17.64244 17.766 7.432)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="rq033_icj"/><stop offset="1" class="dbmxbxbzy"/></radialGradient><radialGradient id="iWN4afc" cx="0" cy="0" r="1" gradientTransform="matrix(.88851 -3.93483 2.3195 .52376 7.168 14.413)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="i65ehgbpk"/><stop offset="1" class="f_7o7vbro"/></radialGradient><radialGradient id="isXsNHe" cx="0" cy="0" r="1" gradientTransform="rotate(137.988 8.682 4.643)scale(9.89862 9.45071)" gradientUnits="userSpaceOnUse"><stop class="rnyxtsb4p"/><stop offset="1" class="isvyw7ooh"/></radialGradient><radialGradient id="irYUE9m" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -4.75 18.668 3.407)" gradientUnits="userSpaceOnUse"><stop class="dqjzd9_8e"/><stop offset="1" class="jcrjf-b8x"/></radialGradient><radialGradient id="iIXFaHd" cx="0" cy="0" r="1" gradientTransform="matrix(5.90625 .125 -.02777 1.31192 10.355 4.032)" gradientUnits="userSpaceOnUse"><stop class="qw_ssccar"/><stop offset="1" class="mvpyyqb8k"/></radialGradient><radialGradient id="ixg6Igc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -.09375 .17757 2.4268 14.355 2.376)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jdd1i0reo"/><stop offset="1" class="ixxpbv8hf"/></radialGradient><radialGradient id="iENyh4d" cx="0" cy="0" r="1" gradientTransform="matrix(-8.06249 1.65631 -3.03846 -14.79042 14.761 2.5)" gradientUnits="userSpaceOnUse"><stop class="nsmntj3ul"/><stop offset="1" class="q9wqsddqp"/></radialGradient><radialGradient id="iB1t3Hb" cx="0" cy="0" r="1" gradientTransform="matrix(8.03125 .96875 -1.11478 9.24187 7.48 3.157)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="atp4gmb-q"/><stop offset="1" class="qfleuzzqm"/></radialGradient><radialGradient id="iVTw2Il" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 -2.3259 1.71042 1.99932 4.824 7.67)" gradientUnits="userSpaceOnUse"><stop class="lo97d1z0q"/><stop offset="1" class="qt9c-0dps"/></radialGradient><filter id="iz2Aq4r" width="20.1" height="19.444" x="6.536" y="10.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3102" result="effect2_innerShadow_4002_3102"/></filter><filter id="iMACpqh" width="5.264" height="7.419" x="13.102" y="15.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".5"/></filter><filter id="ixqHuqc" width="3.908" height="5.819" x="14.046" y="16.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".1"/></filter><filter id="iHJrqui" width="3.908" height="5.819" x="14.046" y="16.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".1"/></filter><filter id="iqjxwsd" width="6.514" height="2.505" x="12.743" y="23.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".05"/></filter><filter id="ijqAMtc" width="4.284" height="2.051" x="18.97" y="11.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3102"/></filter><filter id="iA3ULPE" width="4.284" height="2.023" x="9.147" y="11.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3102"/></filter><filter id="ivvYEub" width="1.297" height="1.127" x="18.793" y="16.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".05"/></filter><filter id="iDrr2Vc" width="1.318" height="1.359" x="20.449" y="16.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".1"/></filter><filter id="iJ7EXyb" width="1.496" height="1.596" x="12.147" y="16.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".1"/></filter><filter id="igMbXJc" width="1.533" height="1.143" x="10.649" y="16.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".05"/></filter><filter id="ipooAgd" width="2.049" height="4.012" x="4.853" y="16.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".125"/></filter><filter id="ik3amPd" width="2.506" height="4.285" x="24.938" y="15.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".25"/></filter><filter id="ijeJ3Td" width="3.843" height="1.517" x="9.321" y="12.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".125"/></filter><filter id="irCmDob" width="3.843" height="1.517" x="19.256" y="12.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3102" stdDeviation=".125"/></filter><filter id="irgtlGc" width="7.307" height="5.168" x="20.645" y="1.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.8 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3102"/></filter><filter id="iy7B99b" width="12.925" height="6.714" x="14.693" y="8.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.992157 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.560784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3102" result="effect2_innerShadow_4002_3102"/></filter><filter id="iNzpVHe" width="17.006" height="13.059" x="4.334" y="1.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.45098 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3102"/></filter><filter id="i2NQosB" width="13.757" height="8.679" x="4.484" y="1.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.588235 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3102"/></filter><filter id="iysXE6c" width="10.523" height="5.986" x="4.584" y="1.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.619608 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.701961 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3102" result="effect2_innerShadow_4002_3102"/></filter><linearGradient id="izsutGc" x1="25.649" x2="20.92" y1="21.683" y2="21.683" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iZRm9Ae" x1="17.754" x2="16" y1="19.693" y2="19.86" gradientUnits="userSpaceOnUse"><stop class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="i1XB0nc" x1="16" x2="16" y1="21.924" y2="21.055" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="i8PXACe" x1="16" x2="16" y1="16.294" y2="19.547" gradientUnits="userSpaceOnUse"><stop class="gnnda7bxi"/><stop offset="1" class="kw78-b8as"/></linearGradient><linearGradient id="iIPOjzd" x1="13.754" x2="14.349" y1="24.86" y2="23.3" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iuz6Jfe" x1="21.531" x2="20.945" y1="16.923" y2="17.284" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqYRQxc" x1="13.312" x2="12.726" y1="16.922" y2="17.284" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVuUXte" x1="28.028" x2="25.773" y1="16.973" y2="21.04" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iEQeiVW" x1="5.068" x2="7.793" y1="18.288" y2="18.05" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="i7kObGC" x1="26.191" x2="26.191" y1="16.395" y2="19.68" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="ioWjwqc" x1="26.387" x2="15.636" y1="13.501" y2="13.501" gradientUnits="userSpaceOnUse"><stop class="qxbo6kk2p"/><stop offset="1" class="kkvh--b-a"/></linearGradient><linearGradient id="iksQM8X" x1="4.584" x2="8.761" y1="9.469" y2="8.501" gradientUnits="userSpaceOnUse"><stop class="d2rffhbfx"/><stop offset="1" class="m1v3gnbun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-wearing-turban-medium" /></template>
<style>
.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.adprot6ba {
  d: path("m20.645 1.934l.055 2.427c1.223-.03 3.562.083 5.578 1.227c.849.482 1.289.993 1.573 1.414c-.072-.969-.366-1.894-1.202-3.047c-.978-1.35-2.794-2.02-4.42-2.02z");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.atp4gmb-q {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
  stop-opacity: 0;
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bd-wa8btn {
  stop-color: var(--svg-color--a86f7e, #A86F7E);
  stop-opacity: 0;
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.biviy7bfr {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
}

.bvn31e4uo {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("M15.25 17.564L14.146 21c-.189.706.264 1.413.905 1.413h1.367c.641 0 1.094-.718.906-1.413l-.925-3.436c-.198-.76-.942-.76-1.15 0");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnmw0ztyt {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M22.976 12.966c-.328-.286-.708-.588-1.285-.77c-.569-.178-1.28-.226-2.266-.106a.518.518 0 0 0 .126 1.029c.9-.11 1.45-.053 1.829.066c.37.117.62.306.915.562a.518.518 0 1 0 .68-.781");
}

.d2rffhbfx {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dbmxbxbzy {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
}

.dqjzd9_8e {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ednzh9b6g {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
  stop-opacity: 0;
}

.esqjjybhw {
  d: path("M19.959 16.283c.119.159-.13.352-.412.563c-.282.212-.492.36-.61.201c-.12-.159.013-.459.295-.67c.283-.21.608-.253.727-.094");
}

.f_7o7vbro {
  stop-color: var(--svg-color--795a90, #795A90);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.ff-0vv13w {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.532 15.422A2.61 2.61 0 0 0 9 17.401a.512.512 0 0 0 .5.637h4.17a.43.43 0 0 0 .425-.508a2.62 2.62 0 0 0-2.563-2.108");
}

.fi285-b6u {
  stop-color: var(--svg-color--ece8f1, #ECE8F1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fv2bdy80c {
  d: path("M4.78 10.562c.193 2.807 1.396 3.89 1.76 4.18c0-.514-.073-1.815.476-2.635c.802-1.196 1.711-1.285 2.602-1.285h12.96c2.464 0 3.08 1.796 3.08 2.694l-.093 1.146c.217 0 .867-.237 1.115-.728c.65-1.285 1.069-3.964 1.162-5.528s.03-2.763-1.193-4.451c-.978-1.35-2.794-2.02-4.42-2.02H10.678c-3.711 0-4.678 1.406-5.42 2.8c-.594 1.114-.674 2.2-.674 2.843c0 .759.013 2.128.195 2.984");
}

.g-0c2yb0v {
  d: path("M21.567 17.379a1.57 1.57 0 0 0-.432-.865l-.486.533l.22.426z");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gnnda7bxi {
  stop-color: var(--svg-color--a97d70, #A97D70);
}

.gtmobbk9i {
  d: path("m15.285 17.198l-.993 3.436c-.202.706.284 1.413.973 1.413h1.47c.689 0 1.175-.717.973-1.413l-.994-3.436c-.212-.76-1.206-.76-1.429 0");
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.hc-28-bvv {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.724 13.18c-.48-.344-1.677-.95-3.093-.712");
}

.hc5vad6zv {
  stop-color: var(--svg-color--bfb1c9, #BFB1C9);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hso5zgb1o {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.468 15.422A2.61 2.61 0 0 1 23 17.401a.512.512 0 0 1-.5.637h-4.17a.43.43 0 0 1-.424-.508a2.61 2.61 0 0 1 2.562-2.108");
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i65ehgbpk {
  stop-color: var(--svg-color--795a90, #795A90);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ih_njzbst {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
  stop-opacity: 0;
}

.isvyw7ooh {
  stop-color: var(--svg-color--c0bbc4, #C0BBC4);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iwg79bpyi {
  d: path("m15.285 16.865l-.993 3.435c-.202.707.284 1.414.973 1.414h1.47c.689 0 1.175-.718.973-1.414l-.994-3.435c-.212-.761-1.206-.761-1.429 0");
}

.ixxpbv8hf {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jcrjf-b8x {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
  stop-opacity: 0;
}

.jdd1i0reo {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
}

.jh2vskc2o {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.446 23.267h-.001a.36.36 0 0 0-.43.074a.33.33 0 0 0-.036.425A3.61 3.61 0 0 0 16 25.38a3.61 3.61 0 0 0 3.021-1.615a.335.335 0 0 0-.037-.428a.36.36 0 0 0-.429-.07a5.5 5.5 0 0 1-2.555.605a5.54 5.54 0 0 1-2.554-.605Z");
}

.jnxizgjym {
  d: path("m6.536 14.739l.004.004v-.166c-.008-.59-.021-1.727.476-2.47c.802-1.196 1.711-1.285 2.602-1.285h12.96c2.2 0 2.927 1.43 3.058 2.377c-.158 3.376-.369 6.74-.58 10.117l-.025.385a7.32 7.32 0 0 1-7.266 6.365h-3.529A7.32 7.32 0 0 1 6.97 23.7c-.197-3.01-.386-5.971-.434-8.962");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jqs5mrb2n {
  d: path("m25.592 14.329l-.027.332h.01c-.146 2.886-.327 5.766-.508 8.655l-.024.385a7.32 7.32 0 0 1-7.267 6.365h-3.528A7.32 7.32 0 0 1 6.981 23.7c-.21-3.224-.413-6.393-.442-9.602c.013-.61.093-1.419.477-1.992c.802-1.196 1.711-1.285 2.602-1.285h12.96c2.252 0 2.96 1.5 3.066 2.444z");
}

.jx2zvtbqq {
  fill: var(--svg-color--9d7269, #9D7269);
  d: path("m15.285 17.198l-.993 3.436c-.202.706.284 1.413.973 1.413h1.47c.689 0 1.175-.717.973-1.413l-.994-3.436c-.212-.76-1.206-.76-1.429 0");
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.kch_6zz7f {
  d: path("M13.442 17.402c0-.539-.438-.898-.556-1.007l-.54.521l.332.676z");
}

.kkvh--b-a {
  stop-color: var(--svg-color--ddd6e4, #DDD6E4);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kw78-b8as {
  stop-color: var(--svg-color--a97d70, #A97D70);
  stop-opacity: 0;
}

.l168mt3hr {
  cx: 11.415px;
  cy: 16.643px;
  rx: 0.728px;
  ry: 0.368px;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lljj_ntoi {
  d: path("M6.496 16.294a1.786 1.786 0 0 0 .156 3.512c-.064-1.171-.12-2.34-.156-3.512");
}

.lo97d1z0q {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
}

.lxkykv_ud {
  stop-color: var(--svg-color--ebe6f2, #EBE6F2);
}

.m1v3gnbun {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
  stop-opacity: 0;
}

.m71s56bwv {
  stop-color: var(--svg-color--e0dae8, #E0DAE8);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcdrc7blw {
  stop-color: var(--svg-color--fafafa, #FAFAFA);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mvpyyqb8k {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
  stop-opacity: 0;
}

.n1mxiybya {
  d: path("M4.769 10.513c.457-.912 1.614-2.206 5.677-2.625c.406-.042 1.004-.06 1.673-.08c1.665-.05 3.775-.113 4.482-.594c.933-.445 1.972-3.245 1.539-5.28h-5.97L5.182 4.883c-.524 1.062-.597 2.081-.597 2.695c0 .744.012 2.076.185 2.935");
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nr-u1ybra {
  d: path("M20.082 15.93a1.668 1.668 0 0 1 1.607 2.108h-3.222a1.7 1.7 0 0 1-.06-.44c0-.917.75-1.668 1.674-1.668");
}

.nsg0945ca {
  stop-color: var(--svg-color--dbdbdc, #DBDBDC);
}

.nsmntj3ul {
  stop-color: var(--svg-color--d2d1d3, #D2D1D3);
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ogdek8h1a {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M9.626 12.762a5.2 5.2 0 0 1 3.25-.672a.518.518 0 0 1-.126 1.029a4.15 4.15 0 0 0-2.592.532a3 3 0 0 0-.171.112l-.005.004a.518.518 0 0 1-.635-.82z");
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.p0q8klbjo {
  fill: var(--svg-color--000, #000);
  d: path("M12.874 17.598a.95.95 0 0 0-.956-.955a.95.95 0 0 0-.955.955c0 .16.038.31.106.44h1.691a.95.95 0 0 0 .114-.44");
}

.p6ygghbxv {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
}

.pf4hb6beg {
  d: path("M4.584 7.67C5.142 7 6.148 6.058 7.48 5.697c1.88-.509 4.836-.733 6.07-.82c.448.025 1.556-.442 1.556-1.611c0-.433-.017-.889-.054-1.332h-4.375c-3.711 0-4.678 1.407-5.42 2.8c-.594 1.115-.674 2.201-.674 2.844z");
}

.pga49oy6q {
  d: path("M16 23.947a5.6 5.6 0 0 1-2.589-.614c-.256-.13-.531.158-.37.39A3.54 3.54 0 0 0 16 25.306a3.54 3.54 0 0 0 2.959-1.581c.161-.242-.114-.521-.37-.39c-.75.39-1.631.613-2.589.613");
}

.phr-zrige {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q2rl-9b2o {
  stop-color: var(--svg-color--cfcad4, #CFCAD4);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q9wqsddqp {
  stop-color: var(--svg-color--b5b4b6, #B5B4B6);
}

.qfleuzzqm {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qm1rc5b9k {
  d: path("M25.438 19.68q.091-1.643.176-3.285c.75.102 1.33.796 1.33 1.636c0 .906-.673 1.641-1.506 1.65");
}

.qnoj66lkr {
  stop-color: var(--svg-color--f5f4f6, #F5F4F6);
}

.qt9c-0dps {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw_ssccar {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
}

.qxbo6kk2p {
  stop-color: var(--svg-color--eee8f4, #EEE8F4);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.rjs9uccph {
  stop-color: var(--svg-color--d1cad9, #D1CAD9);
  stop-opacity: 0;
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rnyxtsb4p {
  stop-color: var(--svg-color--ddddde, #DDDDDE);
}

.rq033_icj {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
  stop-opacity: 0;
}

.rrovopbjp {
  stop-color: var(--svg-color--a186b8, #A186B8);
  stop-opacity: 0;
}

.rw1r_lbur {
  d: path("M27.218 12.402c.005-1.483-1.086-2.607-1.931-3.106c-1.34-.79-3.267-1.003-4.103-.998h-1.487l-4.954.805l.255 1.719h7.58c2.464 0 3.101 1.792 3.043 2.694l-.056 1.145c.217 0 .867-.236 1.115-.727c.203-.4.383-.937.538-1.532");
}

.s_fkwccyi {
  stop-color: var(--svg-color--cfc8d7, #CFC8D7);
}

.s6vdf8bty {
  stop-color: var(--svg-color--f8f6fb, #F8F6FB);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.tid71jz-b {
  fill: var(--svg-color--000, #000);
  d: path("M19.126 17.598c0-.53.425-.955.955-.955a.95.95 0 0 1 .849 1.395h-1.69a.86.86 0 0 1-.114-.44");
}

.tvk9hnoys {
  d: path("M25.198 21.04c.123-1.989.241-3.975.345-5.964a3.008 3.008 0 0 1-.345 5.964");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.uwloccuzy {
  stop-color: var(--svg-color--a186b8, #A186B8);
}

.v-pwvkbrl {
  d: path("M6.573 15.052a3.03 3.03 0 0 0-2.601 2.986a3.007 3.007 0 0 0 2.842 3.002q-.181-2.993-.24-5.988");
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v4iliwb4c {
  cx: 11.415px;
  cy: 16.643px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.728px;
  ry: 0.368px;
}

.w7pk8_-qm {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
}

.w98e9_6zv {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wfm74pxcd {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
  stop-opacity: 0;
}

.wvn8vtban {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
  stop-opacity: 0;
}

.x5z86eb3s {
  d: path("M21.173 1.934c.357 1.962.193 4.541-1.019 6.426c-.922 1.433-2.181 2.462-3.473 2.462H9.618c-.89 0-1.8.089-2.602 1.285c-.497.743-.484 1.88-.477 2.47l.001.166c-.364-.29-1.567-1.374-1.76-4.18c-.183-.857-.196-2.226-.196-2.985c0-.643.08-1.73.674-2.844c.742-1.393 1.709-2.8 5.42-2.8z");
}

.x7ia8vuzd {
  stop-color: var(--svg-color--f1edf4, #F1EDF4);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y7cq1ga0i {
  d: path("M11.919 15.93a1.668 1.668 0 0 0-1.607 2.108h3.222a1.7 1.7 0 0 0 .06-.44a1.68 1.68 0 0 0-1.675-1.668");
}

.yehorz89n {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.696 13.284c.48-.344 1.678-.95 3.093-.712");
}

.z-wmaubks {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.959 16.283c.119.159-.13.352-.412.563c-.282.212-.492.36-.61.201c-.12-.159.013-.459.295-.67c.283-.21.608-.253.727-.094");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zz39r5b3o {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
}

</style>
