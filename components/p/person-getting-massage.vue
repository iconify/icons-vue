<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="ieTxk5c" class="htw-10p4r"/></defs><g class="ft5dv1b6b"><g filter="url(#iRMtacD)"><path fill="url(#iNaJQ8d)" class="dkva-0p2a"/><path fill="url(#iSwkn4c)" class="dkva-0p2a"/></g><path class="cormdhbic"/><path fill="url(#iUjTu5d)" class="h26e4sgsm"/><path fill="url(#iTHw1oc)" class="h26e4sgsm"/><g filter="url(#iDNZyhc)"><path class="s2ml3ezpk"/></g><path fill="url(#iShfI1k)" class="g5_ia9syq"/><circle fill="url(#i2NH4Gj)" class="i7fnn1bcq"/><g filter="url(#ilN5uqe)" class="mc2zb0bvp"><circle class="zl4ivbczp"/></g><circle fill="url(#icyp7Ec)" class="srcdcl_yh"/><circle fill="url(#iO8yQGc)" class="srcdcl_yh"/><g filter="url(#iDuxp7b)"><circle class="vyr2a4cvu"/></g><g filter="url(#igISbQQ)"><path fill="url(#ibMoX8c)" class="wkqd0hb4b"/></g><path fill="url(#iAuaryc)" class="wkqd0hb4b"/><g filter="url(#iiyHiOe)"><circle fill="url(#i0inB6f)" class="j0j5vybko"/></g><g filter="url(#isuaRjc)"><path fill="url(#iqaPHyd)" class="vlr6nmb6w"/></g><g filter="url(#i82MRsc)"><path fill="url(#i4hQP9i)" class="ic-dvmxoa"/><path fill="url(#imGqRCb)" class="ic-dvmxoa"/></g><g filter="url(#iqUROSK)"><path class="l_g0anb2h"/></g><g filter="url(#iWePxea)"><path stroke="url(#ieBafvZ)" class="ze6s0wf9k"/></g><g filter="url(#izs4knd)"><path class="spdu_ub0r"/></g><g filter="url(#iiIxpgb)"><path stroke="url(#idYTf5a)" class="g-lz2-rad"/></g><path stroke="url(#igra60d)" class="xjyo8kbbd"/><g filter="url(#i1Ce5yb)"><path stroke="url(#igkDmjd)" class="wv6byccxz"/></g><path stroke="url(#iBufREd)" class="e4qmmebvg"/><g filter="url(#iELUJId)"><path stroke="url(#i9FN5xd)" class="g3cj9mbqt"/></g><g filter="url(#iM5ymSc)"><path class="f89d2gb3s"/></g><path class="zs9fux51i"/><path fill="url(#iUwNikc)" class="lln5h90we"/><path fill="url(#ibR2UMd)" class="lln5h90we"/><g filter="url(#ijUZXlb)"><path stroke="url(#ir2dlud)" class="bnga0rw3i"/></g><path class="ixhl7zbse"/><g filter="url(#i443S7b)"><path class="ef5q3dktp"/><path fill="url(#iZYAvnc)" class="am_6_g2wh"/><path fill="url(#i8pqkBd)" class="am_6_g2wh"/></g><g filter="url(#ifIWbQd)"><path fill="url(#it9DaUb)" class="kkqz5eb_f"/><path fill="url(#iMFUoZb)" class="kkqz5eb_f"/></g><g filter="url(#iAuCyUv)"><path fill="url(#inIvRad)" class="dj4m7-bab"/><path fill="url(#isRU0Td)" class="dj4m7-bab"/></g><g filter="url(#iRXINcd)"><path class="mkrl710xm"/><path fill="url(#izpHk6b)" class="w5a3tprnu"/><path fill="url(#iAJrL8e)" class="w5a3tprnu"/></g><g filter="url(#iFlOJGb)"><use href="#ieTxk5c"/><path fill="url(#i6ADrgd)" class="ajvihphfe"/></g><g filter="url(#iFlOJGb)"><use href="#ieTxk5c"/><path fill="url(#i6ADrgd)" class="ajvihphfe"/></g><g filter="url(#iIIQROe)"><path fill="url(#iScd9be)" class="e-hur3b5h"/></g><g filter="url(#iABugec)"><path fill="url(#iE2DYxc)" class="eh43pve_h"/></g><g filter="url(#iDQBrAa)"><path class="snss982bp"/></g><defs><radialGradient id="iNaJQ8d" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -12.0938 23.481 28.558)" gradientUnits="userSpaceOnUse"><stop class="zl8nqy82h"/><stop offset="1" class="yu799baro"/></radialGradient><radialGradient id="iSwkn4c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65628 -9.43744 11.80863 -5.8262 23.606 28.683)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="dwoq6zbym"/><stop offset="1" class="qmod-43sl"/></radialGradient><radialGradient id="iUjTu5d" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.147 14.718)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="dubz53-6i"/><stop offset="1" class="rawot7b-t"/></radialGradient><radialGradient id="iTHw1oc" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.8125 -5.89395 3.25184 14.513 21.464)" gradientUnits="userSpaceOnUse"><stop class="imh20i61g"/><stop offset="1" class="xwyn-4b4p"/></radialGradient><radialGradient id="iShfI1k" cx="0" cy="0" r="1" gradientTransform="matrix(-.93066 2.91053 -1.89558 -.60612 22.45 16.62)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="a45_0ccwr"/><stop offset="1" class="ktc_ygwze"/></radialGradient><radialGradient id="i2NH4Gj" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.508 17.256)scale(2.88068)" gradientUnits="userSpaceOnUse"><stop class="g0xv48b6h"/><stop offset="1" class="r6ifw9b5e"/></radialGradient><radialGradient id="icyp7Ec" cx="0" cy="0" r="1" gradientTransform="rotate(120.672 7.537 13.705)scale(2.63415 1.68373)" gradientUnits="userSpaceOnUse"><stop class="pg81w39ph"/><stop offset=".908" class="dmanwfbnw"/></radialGradient><radialGradient id="iO8yQGc" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.433 21.15)scale(2.34213)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="n3i3hq-br"/><stop offset="1" class="qca9cgb6f"/></radialGradient><radialGradient id="ibMoX8c" cx="0" cy="0" r="1" gradientTransform="rotate(174.491 9.403 8.468)scale(6.18482 6.87814)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="isb53_mmq"/><stop offset="1" class="b1hif_bph"/></radialGradient><radialGradient id="iAuaryc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.85156 -12.1336 0 16 12.151)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="nxgp55bqh"/><stop offset="1" class="b0zoldb5a"/></radialGradient><radialGradient id="i0inB6f" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 14.187)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cibck0b0g"/><stop offset=".902" class="ghvr_e1bi"/></radialGradient><radialGradient id="iqaPHyd" cx="0" cy="0" r="1" gradientTransform="rotate(89.246 5.356 14.764)scale(4.95122 5.29384)" gradientUnits="userSpaceOnUse"><stop class="p97qg-b4a"/><stop offset="1" class="vukz93b8e"/></radialGradient><radialGradient id="i4hQP9i" cx="0" cy="0" r="1" gradientTransform="matrix(.87207 1.75 -1.15013 .57314 11.06 9.714)" gradientUnits="userSpaceOnUse"><stop class="f7m1yfx-m"/><stop offset="1" class="p3lw01bbh"/></radialGradient><radialGradient id="imGqRCb" cx="0" cy="0" r="1" gradientTransform="rotate(-91.668 12.353 1.904)scale(3.22012 2.52563)" gradientUnits="userSpaceOnUse"><stop class="km7u9bcta"/><stop offset="1" class="rf_171bfc"/></radialGradient><radialGradient id="igra60d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="zbl0hn4uu"/><stop offset="1" class="a4w7cpbiw"/></radialGradient><radialGradient id="iBufREd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="zbl0hn4uu"/><stop offset="1" class="a4w7cpbiw"/></radialGradient><radialGradient id="ibR2UMd" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 17.003)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="lydnq_bqp"/><stop offset="1" class="mw3_h25bb"/></radialGradient><radialGradient id="ir2dlud" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 -.39062 1.75486 .91253 14.92 18.59)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="ugyr8nbyy"/><stop offset="1" class="xh5cq3bwm"/></radialGradient><radialGradient id="iZYAvnc" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -2.65625 .92293 1.02066 11.747 6.323)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="trlelnb5m"/><stop offset="1" class="law49dbwc"/></radialGradient><radialGradient id="i8pqkBd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 -2.11178 1.39023 -1.15206 20.013 6.964)" gradientUnits="userSpaceOnUse"><stop class="nb89kabuq"/><stop offset="1" class="gsjysn-ad"/></radialGradient><radialGradient id="it9DaUb" cx="0" cy="0" r="1" gradientTransform="rotate(175.489 7.867 3.484)scale(3.57565 1.56262)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="k7fvrbbpb"/><stop offset="1" class="bt0a1m7qj"/></radialGradient><radialGradient id="iMFUoZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79689 -2.51562 5.42206 -1.71758 13.669 8.23)" gradientUnits="userSpaceOnUse"><stop offset=".634" class="tsxuovbau"/><stop offset="1" class="uez_1nbbl"/></radialGradient><radialGradient id="inIvRad" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4219 -3.33016 1.58318 -1.15139 19.252 8.393)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="k7fvrbbpb"/><stop offset="1" class="bt0a1m7qj"/></radialGradient><radialGradient id="isRU0Td" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8291 2.17918 -1.87822 -2.4384 19.396 6.561)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="poirxd2tf"/><stop offset="1" class="gczok8zqy"/></radialGradient><radialGradient id="izpHk6b" cx="0" cy="0" r="1" gradientTransform="rotate(69.766 4.017 10.436)scale(9.1257 4.52893)" gradientUnits="userSpaceOnUse"><stop class="r871ksz2k"/><stop offset="1" class="m5-y-pbea"/></radialGradient><radialGradient id="iAJrL8e" cx="0" cy="0" r="1" gradientTransform="rotate(-123.921 8.75 2.196)scale(3.21989 1.05742)" gradientUnits="userSpaceOnUse"><stop class="s165-bbuq"/><stop offset="1" class="kyulx_bkd"/></radialGradient><radialGradient id="i6ADrgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.518 1.879)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><filter id="iRMtacD" width="21.451" height="8.965" x="5.649" y="21.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.262745 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24253"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.380392 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24253" result="effect2_innerShadow_3987_24253"/></filter><filter id="iDNZyhc" width="2.256" height="3.995" x="9.377" y="15.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.509804 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24253"/></filter><filter id="ilN5uqe" width="2.986" height="2.986" x="9.111" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".1"/></filter><filter id="iDuxp7b" width="2.986" height="2.986" x="19.904" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".1"/></filter><filter id="igISbQQ" width="12.252" height="14.898" x="10.124" y="7.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.607843 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24253"/></filter><filter id="iiyHiOe" width="3.829" height="3.829" x="11.609" y="11.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".25"/></filter><filter id="isuaRjc" width="7.729" height="10.962" x="15.437" y="4.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".5"/></filter><filter id="i82MRsc" width="7.108" height="9.773" x="8.377" y="5.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".5"/></filter><filter id="iqUROSK" width="2.699" height="1.214" x="11.797" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.27451 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24253"/></filter><filter id="iWePxea" width="2.399" height=".914" x="11.847" y="12.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".075"/></filter><filter id="izs4knd" width="2.699" height="1.214" x="17.703" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.282353 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24253"/></filter><filter id="iiIxpgb" width="2.399" height=".914" x="17.753" y="12.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".075"/></filter><filter id="i1Ce5yb" width="2.618" height=".92" x="12.269" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".075"/></filter><filter id="iELUJId" width="2.618" height=".92" x="17.16" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".075"/></filter><filter id="iM5ymSc" width="3.122" height="4.211" x="14.162" y="13.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".25"/></filter><filter id="ijUZXlb" width="4.199" height="1.729" x="13.906" y="17.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".05"/></filter><filter id="i443S7b" width="10.047" height="6.351" x="11.473" y="4.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.529412 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24253"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.713726 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24253" result="effect2_innerShadow_3987_24253"/></filter><filter id="ifIWbQd" width="4.387" height="2.271" x="11.746" y="5.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".075"/></filter><filter id="iAuCyUv" width="4.219" height="4.689" x="15.869" y="5.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".125"/></filter><filter id="iRXINcd" width="6.686" height="12.903" x="8.599" y="1.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.556863 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24253"/></filter><filter id="iFlOJGb" width="6.436" height="12.953" x="17.239" y="1.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24253"/></filter><filter id="iIIQROe" width="6.909" height="13.292" x="17.265" y="1.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".5"/></filter><filter id="iABugec" width="2.811" height="6.368" x="8.719" y="8.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".375"/></filter><filter id="iDQBrAa" width="5.64" height="8.855" x="9.423" y="1.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24253" stdDeviation=".375"/></filter><linearGradient id="ieBafvZ" x1="14.021" x2="11.81" y1="12.289" y2="12.753" gradientUnits="userSpaceOnUse"><stop class="h41615boj"/><stop offset="1" class="smh61-b0a"/></linearGradient><linearGradient id="idYTf5a" x1="19.989" x2="17.81" y1="12.636" y2="12.151" gradientUnits="userSpaceOnUse"><stop class="h41615boj"/><stop offset="1" class="smh61-b0a"/></linearGradient><linearGradient id="igkDmjd" x1="14.936" x2="12.494" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="di1p0_b3t"/><stop offset=".32" class="g8-pnsbec"/><stop offset=".794" class="g8-pnsbec"/><stop offset="1" class="di1p0_b3t"/></linearGradient><linearGradient id="i9FN5xd" x1="19.826" x2="17.385" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="di1p0_b3t"/><stop offset=".32" class="g8-pnsbec"/><stop offset=".794" class="g8-pnsbec"/><stop offset="1" class="di1p0_b3t"/></linearGradient><linearGradient id="iUwNikc" x1="17.061" x2="15.455" y1="15.714" y2="15.878" gradientUnits="userSpaceOnUse"><stop class="p_drcebab"/><stop offset="1" class="tdgu1u54k"/></linearGradient><linearGradient id="iScd9be" x1="22.175" x2="22.175" y1="2.993" y2="14.783" gradientUnits="userSpaceOnUse"><stop offset=".786" class="r245klenb"/><stop offset="1" class="qs8hc0yqa"/></linearGradient><linearGradient id="iE2DYxc" x1="10.124" x2="10.124" y1="13.342" y2="8.511" gradientUnits="userSpaceOnUse"><stop class="n6_y6k2_m"/><stop offset="1" class="bd1m8wbbp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-getting-massage" /></template>
<style>
.a45_0ccwr {
  stop-color: var(--svg-color--ffbe36, #FFBE36);
}

.a4w7cpbiw {
  stop-color: var(--svg-color--b54919, #B54919);
}

.ajvihphfe {
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.am_6_g2wh {
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.b0zoldb5a {
  stop-color: var(--svg-color--ee7506, #EE7506);
}

.b1hif_bph {
  stop-color: var(--svg-color--fda828, #FDA828);
}

.bd1m8wbbp {
  stop-color: var(--svg-color--ffcb3b, #FFCB3B);
  stop-opacity: 0;
}

.bnga0rw3i {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.578c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.056.243.013.25.135a.15.15 0 0 1-.014.077c-.76 1.47-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.122.142-.192.25-.135Z");
}

.bt0a1m7qj {
  stop-color: var(--svg-color--ffd033, #FFD033);
  stop-opacity: 0;
}

.cibck0b0g {
  stop-color: var(--svg-color--ffb129, #FFB129);
}

.cormdhbic {
  fill: var(--svg-color--ffad20, #FFAD20);
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.di1p0_b3t {
  stop-color: var(--svg-color--bf6a57, #BF6A57);
}

.dj4m7-bab {
  d: path("M16.507 8.493c.547.846 1.51 1.29 1.847 1.279l1.484-2.327c-.861-2.406-2.462-1.924-3.028-1.562c-.694.444-.986 1.554-.303 2.61");
}

.dkva-0p2a {
  d: path("M5.65 29.974h20.7c-.494-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.665");
}

.dmanwfbnw {
  stop-color: var(--svg-color--fdb530, #FDB530);
}

.dubz53-6i {
  stop-color: var(--svg-color--ffd73e, #FFD73E);
}

.dwoq6zbym {
  stop-color: var(--svg-color--ff7645, #FF7645);
}

.e-hur3b5h {
  d: path("m21.234 8.648l-2.021 1.488a.595.595 0 0 1-.791-.076a.59.59 0 0 1 .027-.828a52 52 0 0 1 1.99-1.787c.875-.733 1.051-1.838 1.03-2.3V2.568h1.705V13.28a.579.579 0 0 1-1.158 0V9.044a.491.491 0 0 0-.782-.396");
}

.e4qmmebvg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.ef5q3dktp {
  fill: var(--svg-color--f4bb2c, #F4BB2C);
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.eh43pve_h {
  d: path("m9.469 9.256l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.f7m1yfx-m {
  stop-color: var(--svg-color--9b4607, #9B4607);
}

.f89d2gb3s {
  fill: var(--svg-color--f4982a, #F4982A);
  d: path("M15.872 13.956c-.163 0-.248.093-.297.254l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.16-.045-.254-.209-.254");
}

.ft5dv1b6b {
  fill: none;
}

.g-lz2-rad {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.928 12.698c-.258-.207-.883-.578-1.95-.43");
}

.g0xv48b6h {
  stop-color: var(--svg-color--d88f27, #D88F27);
}

.g3cj9mbqt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.g5_ia9syq {
  d: path("M22.623 15.636h-2.207v3.894c.934.024 1.977-.949 2.121-2.277z");
}

.g8-pnsbec {
  stop-color: var(--svg-color--93534a, #93534A);
}

.gczok8zqy {
  stop-color: var(--svg-color--fe9c0b, #FE9C0B);
}

.ghvr_e1bi {
  stop-color: var(--svg-color--f39423, #F39423);
}

.gsjysn-ad {
  stop-color: var(--svg-color--dea631, #DEA631);
  stop-opacity: 0;
}

.h26e4sgsm {
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.h41615boj {
  stop-color: var(--svg-color--cd6f5c, #CD6F5C);
}

.htw-10p4r {
  fill: var(--svg-color--ffb62d, #FFB62D);
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.i7fnn1bcq {
  cx: 10.604px;
  cy: 14.61px;
  r: 1.979px;
}

.ic-dvmxoa {
  d: path("M9.377 6.692h2.83v.372c0 .29.186.855.564 1.181c.31.287.904.875 1.426 1.397a.987.987 0 0 1-.022 1.416c-.374.354-.898.299-1.282-.045l-.81-.61a.435.435 0 0 0-.725.323v2.748a.99.99 0 0 1-1.981 0z");
}

.imh20i61g {
  stop-color: var(--svg-color--e27c01, #E27C01);
}

.isb53_mmq {
  stop-color: var(--svg-color--ffdd41, #FFDD41);
}

.ixhl7zbse {
  fill: var(--svg-color--89004e, #89004E);
  d: path("M14.357 17.578c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.056.243.013.25.135a.15.15 0 0 1-.014.077c-.76 1.47-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.122.142-.192.25-.135");
}

.j0j5vybko {
  cx: 13.524px;
  cy: 13.487px;
  r: 1.415px;
}

.k7fvrbbpb {
  stop-color: var(--svg-color--ffd033, #FFD033);
}

.kkqz5eb_f {
  d: path("M12.88 6.098a4.6 4.6 0 0 0-.984.547l.261 1.119l2.828.037a.986.986 0 1 0 .013-1.972h-.646c-.277 0-.96.054-1.472.27");
}

.km7u9bcta {
  stop-color: var(--svg-color--cd8135, #CD8135);
}

.ktc_ygwze {
  stop-color: var(--svg-color--f9862d, #F9862D);
}

.kyulx_bkd {
  stop-color: var(--svg-color--ffa92e, #FFA92E);
  stop-opacity: 0;
}

.l_g0anb2h {
  stroke: var(--svg-color--b73e46, #B73E46);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.072 12.753c.258-.207.883-.578 1.95-.43");
}

.law49dbwc {
  stop-color: var(--svg-color--f5b62a, #F5B62A);
  stop-opacity: 0;
}

.lln5h90we {
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

.lydnq_bqp {
  stop-color: var(--svg-color--ed8f30, #ED8F30);
}

.m5-y-pbea {
  stop-color: var(--svg-color--ffdf3b, #FFDF3B);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mkrl710xm {
  fill: var(--svg-color--ffb52d, #FFB52D);
  d: path("M8.599 2.026h3.425v3.742c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.879.393v3.327a1.2 1.2 0 0 1-2.398 0z");
}

.mw3_h25bb {
  stop-color: var(--svg-color--ffb520, #FFB520);
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

.nb89kabuq {
  stop-color: var(--svg-color--c0812e, #C0812E);
}

.nxgp55bqh {
  stop-color: var(--svg-color--f89e38, #F89E38);
  stop-opacity: 0;
}

.p_drcebab {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
}

.p3lw01bbh {
  stop-color: var(--svg-color--d97513, #D97513);
}

.p97qg-b4a {
  stop-color: var(--svg-color--b95a08, #B95A08);
}

.pg81w39ph {
  stop-color: var(--svg-color--ffd742, #FFD742);
}

.poirxd2tf {
  stop-color: var(--svg-color--fe9c0b, #FE9C0B);
  stop-opacity: 0;
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.qca9cgb6f {
  stop-color: var(--svg-color--eb992f, #EB992F);
}

.qmod-43sl {
  stop-color: var(--svg-color--ff7645, #FF7645);
  stop-opacity: 0;
}

.qs8hc0yqa {
  stop-color: var(--svg-color--ffdf40, #FFDF40);
  stop-opacity: 0;
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

.rf_171bfc {
  stop-color: var(--svg-color--cd8135, #CD8135);
  stop-opacity: 0;
}

.s165-bbuq {
  stop-color: var(--svg-color--c96a05, #C96A05);
}

.s2ml3ezpk {
  fill: var(--svg-color--db7028, #DB7028);
  d: path("M9.377 15.636h2.156v3.894c-.933.024-2.035-1.054-2.105-2.27z");
}

.smh61-b0a {
  stop-color: var(--svg-color--cd6f5c, #CD6F5C);
  stop-opacity: 0;
}

.snss982bp {
  fill: var(--svg-color--ffdf38, #FFDF38);
  d: path("M10.173 5.384v-2.9h1.469V6.02a1 1 0 0 0 .28.693l2.262 2.349a.46.46 0 0 1-.636.663L11.184 7.63a3 3 0 0 1-1.011-2.246");
}

.spdu_ub0r {
  stroke: var(--svg-color--ba3d44, #BA3D44);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.928 12.753c-.258-.207-.883-.578-1.95-.43");
}

.srcdcl_yh {
  cx: 21.396px;
  cy: 14.61px;
  r: 1.979px;
}

.tdgu1u54k {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
  stop-opacity: 0;
}

.trlelnb5m {
  stop-color: var(--svg-color--c29832, #C29832);
}

.tsxuovbau {
  stop-color: var(--svg-color--e6a839, #E6A839);
  stop-opacity: 0;
}

.uez_1nbbl {
  stop-color: var(--svg-color--e6a839, #E6A839);
}

.ugyr8nbyy {
  stop-color: var(--svg-color--ffb333, #FFB333);
}

.vlr6nmb6w {
  d: path("M22.166 7.572h-3.173V5.768c0 .352-.21 1.035-.633 1.43a76 76 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.714c.42.429 1.01.362 1.44-.054l.905-.74a.464.464 0 0 1 .692.043c.08.097.123.221.123.35v3.327c0 .663.497 1.2 1.11 1.2s1.111-.537 1.111-1.2z");
}

.vukz93b8e {
  stop-color: var(--svg-color--fba42d, #FBA42D);
}

.vyr2a4cvu {
  cx: 21.396px;
  cy: 14.61px;
  r: 1.293px;
  fill: var(--svg-color--ffc12d, #FFC12D);
}

.w5a3tprnu {
  d: path("M8.599 2.026h3.425v3.742c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.879.393v3.327a1.2 1.2 0 0 1-2.398 0z");
}

.wkqd0hb4b {
  d: path("m10.127 10.745l.203 6.485c.233 3.376 2.209 4.755 5.637 4.773h.066c3.428-.018 5.404-1.397 5.637-4.773l.203-6.485c.069-2.2-1.117-3.344-1.719-3.64h-8.308c-.602.296-1.788 1.44-1.72 3.64");
}

.wv6byccxz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.494 14.23c.146.164.536.45 1.024.468c.617.024.949-.304 1.144-.469");
}

.xh5cq3bwm {
  stop-color: var(--svg-color--ffb333, #FFB333);
  stop-opacity: 0;
}

.xjyo8kbbd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 14.23c.146.164.536.45 1.024.468c.617.024.949-.304 1.144-.469");
}

.xwyn-4b4p {
  stop-color: var(--svg-color--e27c01, #E27C01);
  stop-opacity: 0;
}

.yu799baro {
  stop-color: var(--svg-color--ff5026, #FF5026);
}

.zbl0hn4uu {
  stop-color: var(--svg-color--8a374b, #8A374B);
}

.ze6s0wf9k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.072 12.753c.258-.207.883-.578 1.95-.43");
}

.zl4ivbczp {
  cx: 10.604px;
  cy: 14.61px;
  r: 1.293px;
  fill: var(--svg-color--d07d1c, #D07D1C);
}

.zl8nqy82h {
  stop-color: var(--svg-color--ff641f, #FF641F);
}

.zs9fux51i {
  fill: var(--svg-color--ffb31f, #FFB31F);
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

</style>
