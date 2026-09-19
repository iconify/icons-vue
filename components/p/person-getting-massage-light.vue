<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i97BTdd)"><path fill="url(#iNaJQ8d)" class="dkva-0p2a"/><path fill="url(#iSwkn4c)" class="dkva-0p2a"/></g><path class="twlg_mncz"/><path fill="url(#iolAmdb)" class="h26e4sgsm"/><path fill="url(#idT7utc)" class="h26e4sgsm"/><g filter="url(#ifxhBrG)"><path class="j-62o8btp"/></g><path fill="url(#iFTdSre)" class="g5_ia9syq"/><circle fill="url(#iQQFsOd)" class="i7fnn1bcq"/><g filter="url(#inGErYd)" class="mc2zb0bvp"><circle class="vldko8p5h"/></g><circle fill="url(#imUwO3b)" class="srcdcl_yh"/><g filter="url(#i1iYjjy)"><circle fill="url(#iqfeGUc)" class="nnet9bbrm"/></g><g filter="url(#iMOfXgd)"><path fill="url(#i8PBP1d)" class="wkqd0hb4b"/></g><path fill="url(#iuaxsVd)" class="wkqd0hb4b"/><g filter="url(#i3JDz1d)"><circle fill="url(#ifxvGNd)" class="j0j5vybko"/></g><g filter="url(#ieOr2qb)"><path fill="url(#iy4Gzqn)" class="vlr6nmb6w"/></g><g filter="url(#i7KSZqe)"><path fill="url(#ivPeUpB)" class="ic-dvmxoa"/></g><g filter="url(#ifA5Hdb)"><path class="y5pz67bvw"/></g><g filter="url(#iIUIcbd)"><path stroke="url(#iW06rJI)" class="ze6s0wf9k"/></g><g filter="url(#iDFzvje)"><path class="yk3_9bkjh"/></g><g filter="url(#ib8pgGc)"><path stroke="url(#i7HnxNe)" class="g-lz2-rad"/></g><path stroke="url(#i75J2Tc)" class="xjyo8kbbd"/><g filter="url(#iPU7rNd)"><path stroke="url(#if0QA0c)" class="wv6byccxz"/></g><path stroke="url(#id6i3Ie)" class="e4qmmebvg"/><g filter="url(#iNoySQd)"><path stroke="url(#ihTiIAe)" class="g3cj9mbqt"/></g><g filter="url(#ifP3hue)"><path class="rddlmgx_v"/></g><path class="vu9e7rb-l"/><path fill="url(#ie8xFZd)" class="lln5h90we"/><path fill="url(#ijsjRje)" class="lln5h90we"/><path fill="url(#iVx7Sxb)" class="lln5h90we"/><g filter="url(#ivVriAe)"><path stroke="url(#igBdwEc)" class="bnga0rw3i"/></g><path class="vda454bvu"/><g filter="url(#ihby8Ec)"><path class="r57wbabrk"/><path fill="url(#i3ap72h)" class="am_6_g2wh"/><path fill="url(#iJFE1zb)" class="am_6_g2wh"/></g><g filter="url(#if3nDSb)"><path fill="url(#ic6rT3P)" class="kkqz5eb_f"/><path fill="url(#iTj3RqD)" class="kkqz5eb_f"/></g><g filter="url(#iICmqtd)"><path fill="url(#iy6uxjZ)" class="dj4m7-bab"/><path fill="url(#iEL4vsb)" class="dj4m7-bab"/></g><g filter="url(#i0IQQFd)"><path class="l1ix5w79a"/><path fill="url(#iKhcZsc)" class="w5a3tprnu"/></g><g filter="url(#imfAOKP)"><path class="htw-10p4r"/><path fill="url(#i6ADrgd)" class="ajvihphfe"/></g><g filter="url(#iwo2TUd)"><path class="iuo2wf4gg"/></g><g filter="url(#iDvTFic)"><path fill="url(#inb2igd)" class="jvs9aeb5c"/></g><g filter="url(#iiQZ1Rb)"><path fill="url(#iVVr7pd)" class="eh43pve_h"/></g><g filter="url(#iM4jJic)"><path fill="url(#iyLbuae)" class="fgf4_ac8o"/><path fill="url(#ijl0tTK)" class="fgf4_ac8o"/></g><defs><radialGradient id="iNaJQ8d" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -12.0938 23.481 28.558)" gradientUnits="userSpaceOnUse"><stop class="zl8nqy82h"/><stop offset="1" class="yu799baro"/></radialGradient><radialGradient id="iSwkn4c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65628 -9.43744 11.80863 -5.8262 23.606 28.683)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="dwoq6zbym"/><stop offset="1" class="qmod-43sl"/></radialGradient><radialGradient id="iolAmdb" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.147 14.718)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="ae44x1guz"/><stop offset="1" class="f5cdxibyd"/></radialGradient><radialGradient id="idT7utc" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.8125 -5.89395 3.25184 14.513 21.464)" gradientUnits="userSpaceOnUse"><stop class="gtwzsrbll"/><stop offset="1" class="jq1jlp4qg"/></radialGradient><radialGradient id="iFTdSre" cx="0" cy="0" r="1" gradientTransform="matrix(.24766 1.90842 -1.09256 .14178 21.78 16.259)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="b9796ab2x"/><stop offset="1" class="l5nmerp-e"/></radialGradient><radialGradient id="iQQFsOd" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.508 17.256)scale(2.88068)" gradientUnits="userSpaceOnUse"><stop class="e7bgiqbpe"/><stop offset="1" class="y5enf2lbe"/></radialGradient><radialGradient id="imUwO3b" cx="0" cy="0" r="1" gradientTransform="rotate(142.158 9.182 11.206)scale(1.19705 1.26073)" gradientUnits="userSpaceOnUse"><stop class="k06as4b5x"/><stop offset="1" class="y8ctrfbhv"/></radialGradient><radialGradient id="iqfeGUc" cx="0" cy="0" r="1" gradientTransform="matrix(.69531 0 0 .82031 21.666 14.83)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="l30itz4xv"/><stop offset="1" class="e55xysc8j"/></radialGradient><radialGradient id="i8PBP1d" cx="0" cy="0" r="1" gradientTransform="rotate(174.491 9.403 8.468)scale(6.18482 6.87814)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="km865zb8r"/><stop offset="1" class="deyujzbbk"/></radialGradient><radialGradient id="iuaxsVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.85156 -18.8335 0 16 12.151)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="g0bmjf6fv"/><stop offset="1" class="qnvbwcclr"/></radialGradient><radialGradient id="ifxvGNd" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 14.187)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="ppxf2wb8c"/><stop offset=".902" class="o8xc6acii"/></radialGradient><radialGradient id="iy4Gzqn" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09373 4.4375 -2.83652 -.69913 20.823 8.956)" gradientUnits="userSpaceOnUse"><stop class="fa_fs_x-q"/><stop offset="1" class="ae1yswm3l"/></radialGradient><radialGradient id="ivPeUpB" cx="0" cy="0" r="1" gradientTransform="matrix(1 5.875 -3.86118 .65722 11.198 9.613)" gradientUnits="userSpaceOnUse"><stop class="jzb-3db0i"/><stop offset="1" class="kht_rqe3g"/></radialGradient><radialGradient id="i75J2Tc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="vk3h5kjsq"/><stop offset="1" class="dsheu9oxu"/></radialGradient><radialGradient id="id6i3Ie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="vk3h5kjsq"/><stop offset="1" class="dsheu9oxu"/></radialGradient><radialGradient id="ijsjRje" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 17.003)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="cs32zggkd"/><stop offset="1" class="dcjgnwb2v"/></radialGradient><radialGradient id="iVx7Sxb" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.541 16.204)" gradientUnits="userSpaceOnUse"><stop class="yg-4rg1sf"/><stop offset="1" class="un62bb-pj"/></radialGradient><radialGradient id="igBdwEc" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 -.39062 1.75486 .91253 14.92 18.59)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="ngif3bbvk"/><stop offset="1" class="m-1tuk47l"/></radialGradient><radialGradient id="i3ap72h" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -2.65625 .92293 1.02066 11.747 6.323)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="jvoslhnfo"/><stop offset="1" class="ra_978hnp"/></radialGradient><radialGradient id="iJFE1zb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 -2.11178 1.39023 -1.15206 20.013 6.964)" gradientUnits="userSpaceOnUse"><stop class="sh2scbbge"/><stop offset="1" class="peuf8pa6k"/></radialGradient><radialGradient id="ic6rT3P" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69202 -.32813 .16397 -.8455 15.983 6.689)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="t1cyeof7i"/><stop offset="1" class="k3jqymbow"/></radialGradient><radialGradient id="iTj3RqD" cx="0" cy="0" r="1" gradientTransform="matrix(-.79689 -2.51562 5.42206 -1.71758 13.669 8.23)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="isqcarb8m"/><stop offset=".853" class="p1jebm44k"/></radialGradient><radialGradient id="iy6uxjZ" cx="0" cy="0" r="1" gradientTransform="rotate(32.574 -4.662 35.8)scale(2.67 1.26933)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="eo-2wiogo"/><stop offset="1" class="y2d334cwi"/></radialGradient><radialGradient id="iEL4vsb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8291 2.17918 -1.87822 -2.4384 19.396 6.561)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="ijglzsb6p"/><stop offset="1" class="zy380ub3a"/></radialGradient><radialGradient id="iKhcZsc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79686 -2.67189 1.32522 -.89122 11.81 10.683)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="d66hexbdz"/><stop offset="1" class="byqhg5beh"/></radialGradient><radialGradient id="i6ADrgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.518 1.879)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><radialGradient id="inb2igd" cx="0" cy="0" r="1" gradientTransform="matrix(5.8706 -6.28124 5.4446 5.08866 18.265 9.83)" gradientUnits="userSpaceOnUse"><stop class="w4lyng61b"/><stop offset="1" class="zynodvyrc"/></radialGradient><radialGradient id="iyLbuae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 11.01 6.36)" gradientUnits="userSpaceOnUse"><stop class="zjgm0sbfy"/><stop offset="1" class="kkhw_2bmh"/></radialGradient><radialGradient id="ijl0tTK" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.313 9.84)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="hti255bkb"/><stop offset="1" class="u0_qivupy"/></radialGradient><filter id="i97BTdd" width="21.451" height="8.965" x="5.649" y="21.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.262745 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24268"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.380392 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24268" result="effect2_innerShadow_3987_24268"/></filter><filter id="ifxhBrG" width="2.256" height="3.995" x="9.377" y="15.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.258824 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24268"/></filter><filter id="inGErYd" width="2.986" height="2.986" x="9.111" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".1"/></filter><filter id="i1iYjjy" width="2.986" height="2.986" x="19.904" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".1"/></filter><filter id="iMOfXgd" width="12.252" height="14.898" x="10.124" y="7.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.658824 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24268"/></filter><filter id="i3JDz1d" width="3.829" height="3.829" x="11.609" y="11.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".25"/></filter><filter id="ieOr2qb" width="7.729" height="10.962" x="15.437" y="4.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".5"/></filter><filter id="i7KSZqe" width="7.108" height="9.773" x="8.377" y="5.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".5"/></filter><filter id="ifA5Hdb" width="2.699" height="1.214" x="11.797" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24268"/></filter><filter id="iIUIcbd" width="2.399" height=".914" x="11.847" y="12.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".075"/></filter><filter id="iDFzvje" width="2.699" height="1.214" x="17.703" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24268"/></filter><filter id="ib8pgGc" width="2.399" height=".914" x="17.753" y="12.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".075"/></filter><filter id="iPU7rNd" width="2.618" height=".92" x="12.269" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".075"/></filter><filter id="iNoySQd" width="2.618" height=".92" x="17.16" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".075"/></filter><filter id="ifP3hue" width="3.122" height="4.211" x="14.162" y="13.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".25"/></filter><filter id="ivVriAe" width="4.199" height="1.729" x="13.906" y="17.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".05"/></filter><filter id="ihby8Ec" width="10.047" height="6.351" x="11.473" y="4.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.054902 0 0 0 0 0.0156863 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24268"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24268" result="effect2_innerShadow_3987_24268"/></filter><filter id="if3nDSb" width="4.387" height="2.271" x="11.746" y="5.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".075"/></filter><filter id="iICmqtd" width="4.219" height="4.689" x="15.869" y="5.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".125"/></filter><filter id="i0IQQFd" width="6.686" height="12.903" x="8.599" y="1.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.662745 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24268"/></filter><filter id="imfAOKP" width="6.436" height="12.953" x="17.239" y="1.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24268"/></filter><filter id="iwo2TUd" width="6.436" height="12.953" x="17.239" y="1.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.588235 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24268"/></filter><filter id="iDvTFic" width="5.843" height="12.292" x="17.83" y="2.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".25"/></filter><filter id="iiQZ1Rb" width="2.811" height="6.368" x="8.719" y="8.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".375"/></filter><filter id="iM4jJic" width="5.14" height="8.355" x="9.673" y="1.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24268" stdDeviation=".25"/></filter><linearGradient id="iW06rJI" x1="14.021" x2="11.81" y1="12.289" y2="12.753" gradientUnits="userSpaceOnUse"><stop class="du3_mqevj"/><stop offset="1" class="hpzn95b1x"/></linearGradient><linearGradient id="i7HnxNe" x1="17.979" x2="20.19" y1="12.234" y2="12.698" gradientUnits="userSpaceOnUse"><stop class="du3_mqevj"/><stop offset="1" class="hpzn95b1x"/></linearGradient><linearGradient id="if0QA0c" x1="14.936" x2="12.494" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="d3bth9bgz"/><stop offset=".32" class="rulb4ox_k"/><stop offset=".794" class="rulb4ox_k"/><stop offset="1" class="omc-6wb_b"/></linearGradient><linearGradient id="ihTiIAe" x1="19.826" x2="17.385" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="d3bth9bgz"/><stop offset=".32" class="rulb4ox_k"/><stop offset=".794" class="rulb4ox_k"/><stop offset="1" class="omc-6wb_b"/></linearGradient><linearGradient id="ie8xFZd" x1="16.885" x2="15.848" y1="15.735" y2="15.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="z2ocpzy1c"/><stop offset="1" class="ez54n3brs"/></linearGradient><linearGradient id="iVVr7pd" x1="10.124" x2="10.124" y1="13.342" y2="8.511" gradientUnits="userSpaceOnUse"><stop class="ow0nrh1za"/><stop offset="1" class="rmft38b6n"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-getting-massage-light" /></template>
<style>
.ae1yswm3l {
  stop-color: var(--svg-color--db9883, #DB9883);
}

.ae44x1guz {
  stop-color: var(--svg-color--ffc6ae, #FFC6AE);
}

.ajvihphfe {
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.am_6_g2wh {
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.b9796ab2x {
  stop-color: var(--svg-color--3d3b3b, #3D3B3B);
}

.bnga0rw3i {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.578c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.056.243.013.25.135a.15.15 0 0 1-.014.077c-.76 1.47-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.122.142-.192.25-.135Z");
}

.byqhg5beh {
  stop-color: var(--svg-color--dfaa9c, #DFAA9C);
  stop-opacity: 0;
}

.cs32zggkd {
  stop-color: var(--svg-color--dea097, #DEA097);
}

.d3bth9bgz {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
}

.d66hexbdz {
  stop-color: var(--svg-color--c6857e, #C6857E);
}

.dcjgnwb2v {
  stop-color: var(--svg-color--dea097, #DEA097);
  stop-opacity: 0;
}

.deyujzbbk {
  stop-color: var(--svg-color--de9e8b, #DE9E8B);
}

.dj4m7-bab {
  d: path("M16.507 8.493c.547.846 1.51 1.29 1.847 1.279l1.484-2.327c-.861-2.406-2.462-1.924-3.028-1.562c-.694.444-.986 1.554-.303 2.61");
}

.dkva-0p2a {
  d: path("M5.65 29.974h20.7c-.494-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.665");
}

.dsheu9oxu {
  stop-color: var(--svg-color--0c0b0b, #0C0B0B);
}

.du3_mqevj {
  stop-color: var(--svg-color--2c2c2d, #2C2C2D);
}

.dwoq6zbym {
  stop-color: var(--svg-color--ff7645, #FF7645);
}

.e4qmmebvg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.e55xysc8j {
  stop-color: var(--svg-color--f1b69c, #F1B69C);
}

.e7bgiqbpe {
  stop-color: var(--svg-color--d09281, #D09281);
}

.eh43pve_h {
  d: path("m9.469 9.256l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.eo-2wiogo {
  stop-color: var(--svg-color--4d484a, #4D484A);
}

.ez54n3brs {
  stop-color: var(--svg-color--ffd3bd, #FFD3BD);
  stop-opacity: 0;
}

.f5cdxibyd {
  stop-color: var(--svg-color--ffc6ae, #FFC6AE);
  stop-opacity: 0;
}

.fa_fs_x-q {
  stop-color: var(--svg-color--b4725c, #B4725C);
}

.fgf4_ac8o {
  d: path("M10.173 5.384v-2.9h1.469V6.02a1 1 0 0 0 .28.693l2.262 2.349a.46.46 0 0 1-.636.663L11.184 7.63a3 3 0 0 1-1.011-2.246");
}

.ft5dv1b6b {
  fill: none;
}

.g-lz2-rad {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.928 12.698c-.258-.207-.883-.578-1.95-.43");
}

.g0bmjf6fv {
  stop-color: var(--svg-color--ce9091, #CE9091);
  stop-opacity: 0;
}

.g3cj9mbqt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.g5_ia9syq {
  d: path("M22.623 15.636h-2.207v3.894c.934.024 1.977-.949 2.121-2.277z");
}

.gtwzsrbll {
  stop-color: var(--svg-color--dd847c, #DD847C);
}

.h26e4sgsm {
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.hpzn95b1x {
  stop-color: var(--svg-color--2c2c2d, #2C2C2D);
  stop-opacity: 0;
}

.hti255bkb {
  stop-color: var(--svg-color--fed1be, #FED1BE);
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

.ijglzsb6p {
  stop-color: var(--svg-color--1c0f1e, #1C0F1E);
  stop-opacity: 0;
}

.isqcarb8m {
  stop-color: var(--svg-color--494647, #494647);
  stop-opacity: 0;
}

.iuo2wf4gg {
  fill: var(--svg-color--eab5a1, #EAB5A1);
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.j-62o8btp {
  fill: var(--svg-color--241e22, #241E22);
  d: path("M9.377 15.636h2.156v3.894c-.933.024-2.035-1.054-2.105-2.27z");
}

.j0j5vybko {
  cx: 13.524px;
  cy: 13.487px;
  r: 1.415px;
}

.jq1jlp4qg {
  stop-color: var(--svg-color--dd847c, #DD847C);
  stop-opacity: 0;
}

.jvoslhnfo {
  stop-color: var(--svg-color--444142, #444142);
}

.jvs9aeb5c {
  d: path("m21.12 8.376l-2.021 1.488c-.245.18-.471.42-.677.196c-.22-.238-.007-.337.229-.559a52 52 0 0 1 1.99-1.786c.875-.734.85-2.108.828-2.57V2.568h1.704V13.28a.579.579 0 0 1-1.157 0V9.044c0-.403-.572-.907-.896-.668");
}

.jzb-3db0i {
  stop-color: var(--svg-color--a8624e, #A8624E);
}

.k06as4b5x {
  stop-color: var(--svg-color--fccbb6, #FCCBB6);
}

.k3jqymbow {
  stop-color: var(--svg-color--423b3e, #423B3E);
  stop-opacity: 0;
}

.kht_rqe3g {
  stop-color: var(--svg-color--e19a83, #E19A83);
}

.kkhw_2bmh {
  stop-color: var(--svg-color--ffdbc3, #FFDBC3);
  stop-opacity: 0;
}

.kkqz5eb_f {
  d: path("M12.88 6.098a4.6 4.6 0 0 0-.984.547l.261 1.119l2.828.037a.986.986 0 1 0 .013-1.972h-.646c-.277 0-.96.054-1.472.27");
}

.km865zb8r {
  stop-color: var(--svg-color--ffd2b9, #FFD2B9);
}

.l1ix5w79a {
  fill: var(--svg-color--eebaa4, #EEBAA4);
  d: path("M8.599 2.026h3.425v3.742c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.879.393v3.327a1.2 1.2 0 0 1-2.398 0z");
}

.l30itz4xv {
  stop-color: var(--svg-color--f3baa1, #F3BAA1);
}

.l5nmerp-e {
  stop-color: var(--svg-color--252227, #252227);
}

.lln5h90we {
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

.m-1tuk47l {
  stop-color: var(--svg-color--e2aea5, #E2AEA5);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.na9kkhbsz {
  stop-color: var(--svg-color--ffe041, #FFE041);
  stop-opacity: 0;
}

.ngif3bbvk {
  stop-color: var(--svg-color--e2aea5, #E2AEA5);
}

.nnet9bbrm {
  cx: 21.396px;
  cy: 14.61px;
  r: 1.293px;
}

.o8xc6acii {
  stop-color: var(--svg-color--d5988c, #D5988C);
}

.omc-6wb_b {
  stop-color: var(--svg-color--2e2e2e, #2E2E2E);
}

.ow0nrh1za {
  stop-color: var(--svg-color--f2beb0, #F2BEB0);
}

.p1jebm44k {
  stop-color: var(--svg-color--494647, #494647);
}

.peuf8pa6k {
  stop-color: var(--svg-color--353133, #353133);
  stop-opacity: 0;
}

.ppxf2wb8c {
  stop-color: var(--svg-color--e3a998, #E3A998);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.qmod-43sl {
  stop-color: var(--svg-color--ff7645, #FF7645);
  stop-opacity: 0;
}

.qnvbwcclr {
  stop-color: var(--svg-color--d97878, #D97878);
}

.r57wbabrk {
  fill: var(--svg-color--261c20, #261C20);
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.ra_978hnp {
  stop-color: var(--svg-color--363133, #363133);
  stop-opacity: 0;
}

.rddlmgx_v {
  fill: var(--svg-color--dc9f93, #DC9F93);
  d: path("M15.872 13.956c-.163 0-.248.093-.297.254l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.16-.045-.254-.209-.254");
}

.rmft38b6n {
  stop-color: var(--svg-color--f2beb0, #F2BEB0);
  stop-opacity: 0;
}

.rulb4ox_k {
  stop-color: var(--svg-color--242425, #242425);
}

.sh2scbbge {
  stop-color: var(--svg-color--393838, #393838);
}

.srcdcl_yh {
  cx: 21.396px;
  cy: 14.61px;
  r: 1.979px;
}

.t1cyeof7i {
  stop-color: var(--svg-color--423b3e, #423B3E);
}

.twlg_mncz {
  fill: var(--svg-color--fdb1a3, #FDB1A3);
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.u0_qivupy {
  stop-color: var(--svg-color--fed1be, #FED1BE);
  stop-opacity: 0;
}

.un62bb-pj {
  stop-color: var(--svg-color--ffd0be, #FFD0BE);
  stop-opacity: 0;
}

.vda454bvu {
  fill: var(--svg-color--87014d, #87014D);
  d: path("M14.357 17.578c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.056.243.013.25.135a.15.15 0 0 1-.014.077c-.76 1.47-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.122.142-.192.25-.135");
}

.vk3h5kjsq {
  stop-color: var(--svg-color--140a18, #140A18);
}

.vldko8p5h {
  cx: 10.604px;
  cy: 14.61px;
  r: 1.293px;
  fill: var(--svg-color--c88773, #C88773);
}

.vlr6nmb6w {
  d: path("M22.166 7.572h-3.173V5.768c0 .352-.21 1.035-.633 1.43a76 76 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.714c.42.429 1.01.362 1.44-.054l.905-.74a.464.464 0 0 1 .692.043c.08.097.123.221.123.35v3.327c0 .663.497 1.2 1.11 1.2s1.111-.537 1.111-1.2z");
}

.vu9e7rb-l {
  fill: var(--svg-color--edb7a0, #EDB7A0);
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

.w4lyng61b {
  stop-color: var(--svg-color--f8cab8, #F8CAB8);
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

.xjyo8kbbd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 14.23c.146.164.536.45 1.024.468c.617.024.949-.304 1.144-.469");
}

.y2d334cwi {
  stop-color: var(--svg-color--4d484a, #4D484A);
  stop-opacity: 0;
}

.y5enf2lbe {
  stop-color: var(--svg-color--cf8b7b, #CF8B7B);
}

.y5pz67bvw {
  stroke: var(--svg-color--0c0808, #0C0808);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.072 12.753c.258-.207.883-.578 1.95-.43");
}

.y8ctrfbhv {
  stop-color: var(--svg-color--edb3a0, #EDB3A0);
}

.yg-4rg1sf {
  stop-color: var(--svg-color--ffd0be, #FFD0BE);
}

.yk3_9bkjh {
  stroke: var(--svg-color--0c0808, #0C0808);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.928 12.753c-.258-.207-.883-.578-1.95-.43");
}

.yu799baro {
  stop-color: var(--svg-color--ff5026, #FF5026);
}

.z2ocpzy1c {
  stop-color: var(--svg-color--ffd3bd, #FFD3BD);
}

.ze6s0wf9k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.072 12.753c.258-.207.883-.578 1.95-.43");
}

.zjgm0sbfy {
  stop-color: var(--svg-color--ffdbc3, #FFDBC3);
}

.zl8nqy82h {
  stop-color: var(--svg-color--ff641f, #FF641F);
}

.zy380ub3a {
  stop-color: var(--svg-color--1c0f1e, #1C0F1E);
}

.zynodvyrc {
  stop-color: var(--svg-color--f8cab8, #F8CAB8);
  stop-opacity: 0;
}

</style>
