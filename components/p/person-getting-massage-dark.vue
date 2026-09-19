<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iCiMiCe)"><path fill="url(#iNaJQ8d)" class="dkva-0p2a"/><path fill="url(#iSwkn4c)" class="dkva-0p2a"/></g><path class="zr454ebou"/><path fill="url(#idsG6je)" class="h26e4sgsm"/><path fill="url(#iAb6Ijc)" class="h26e4sgsm"/><g filter="url(#iI4sZCn)"><path class="j-62o8btp"/></g><path fill="url(#iFTdSre)" class="g5_ia9syq"/><circle fill="url(#iTethCc)" class="i7fnn1bcq"/><g filter="url(#it727Sb)" class="mc2zb0bvp"><circle class="v_56mwb2a"/></g><circle fill="url(#i4OcoGb)" class="srcdcl_yh"/><circle fill="url(#incFT4D)" class="srcdcl_yh"/><g filter="url(#iQxRDFr)"><circle fill="url(#ixkEV5d)" class="nnet9bbrm"/></g><g filter="url(#iRLeQWb)"><path fill="url(#iIFXOpY)" class="wkqd0hb4b"/></g><path fill="url(#ivUdZ9d)" class="wkqd0hb4b"/><g filter="url(#iXE6Q8m)"><circle fill="url(#iwf32be)" class="j0j5vybko"/></g><g filter="url(#ifGLuYd)"><path class="tsm0b8b0x"/></g><g filter="url(#iwCoqZb)"><path fill="url(#i4hQP9i)" class="ic-dvmxoa"/><path class="j4vtsjbvv"/></g><g filter="url(#iABFQte)"><path class="y5pz67bvw"/></g><g filter="url(#igS0LSc)"><path stroke="url(#iW06rJI)" class="ze6s0wf9k"/></g><g filter="url(#iPkdeNc)"><path class="yk3_9bkjh"/></g><g filter="url(#iLOBRjb)"><path stroke="url(#i7HnxNe)" class="g-lz2-rad"/></g><path stroke="url(#i75J2Tc)" class="xjyo8kbbd"/><g filter="url(#iF16RYd)"><path stroke="url(#if0QA0c)" class="wv6byccxz"/></g><path stroke="url(#id6i3Ie)" class="e4qmmebvg"/><g filter="url(#iKgDMzn)"><path stroke="url(#ihTiIAe)" class="g3cj9mbqt"/></g><g filter="url(#i9FkZdb)"><path class="whuwqfbzs"/></g><path class="mgwbr9b7z"/><path fill="url(#i8JXXHb)" class="lln5h90we"/><path fill="url(#iIwGXkc)" class="lln5h90we"/><path fill="url(#ijfXANf)" class="lln5h90we"/><g filter="url(#inVLG1c)"><path stroke="url(#iApS9Nc)" class="bnga0rw3i"/></g><path class="dbl7bjuhw"/><g filter="url(#iQ0vace)"><path class="r57wbabrk"/><path fill="url(#i3ap72h)" class="am_6_g2wh"/><path fill="url(#iJFE1zb)" class="am_6_g2wh"/></g><g filter="url(#iFBCMjb)"><path fill="url(#ic6rT3P)" class="kkqz5eb_f"/><path fill="url(#iTj3RqD)" class="kkqz5eb_f"/></g><g filter="url(#ihE9oYb)"><path fill="url(#iy6uxjZ)" class="dj4m7-bab"/><path fill="url(#iEL4vsb)" class="dj4m7-bab"/></g><g filter="url(#ingMdic)"><path class="stq2e3bfc"/><path fill="url(#iCumQnf)" class="w5a3tprnu"/></g><g filter="url(#iG5Wynb)"><path class="htw-10p4r"/><path fill="url(#i6ADrgd)" class="ajvihphfe"/></g><g filter="url(#icbeKDd)"><path class="m2_qidb8o"/></g><g filter="url(#iJF7RMd)"><path fill="url(#iEW7qfb)" class="jvs9aeb5c"/></g><g filter="url(#i2NDftj)"><path fill="url(#iVPYtBc)" class="eh43pve_h"/></g><g filter="url(#ijyL7Qx)"><path fill="url(#iBfloSd)" class="fgf4_ac8o"/><path fill="url(#iEBQIde)" class="fgf4_ac8o"/></g><defs><radialGradient id="iNaJQ8d" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -12.0938 23.481 28.558)" gradientUnits="userSpaceOnUse"><stop class="zl8nqy82h"/><stop offset="1" class="yu799baro"/></radialGradient><radialGradient id="iSwkn4c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65628 -9.43744 11.80863 -5.8262 23.606 28.683)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="dwoq6zbym"/><stop offset="1" class="qmod-43sl"/></radialGradient><radialGradient id="idsG6je" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.147 14.718)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="ydm9ddced"/><stop offset="1" class="n_nhnibbq"/></radialGradient><radialGradient id="iAb6Ijc" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.8125 -5.89395 3.25184 14.513 21.464)" gradientUnits="userSpaceOnUse"><stop class="pj2xknbvf"/><stop offset="1" class="dit5vub-g"/></radialGradient><radialGradient id="iFTdSre" cx="0" cy="0" r="1" gradientTransform="matrix(.24766 1.90842 -1.09256 .14178 21.78 16.259)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="b9796ab2x"/><stop offset="1" class="l5nmerp-e"/></radialGradient><radialGradient id="iTethCc" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.508 17.256)scale(2.88068)" gradientUnits="userSpaceOnUse"><stop class="phs3tubib"/><stop offset="1" class="grwnnnb5d"/></radialGradient><radialGradient id="i4OcoGb" cx="0" cy="0" r="1" gradientTransform="rotate(142.158 9.182 11.206)scale(1.19705 1.26073)" gradientUnits="userSpaceOnUse"><stop class="my0c8s4fp"/><stop offset="1" class="y581ksbre"/></radialGradient><radialGradient id="incFT4D" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.433 21.15)scale(2.34213)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="qtf9d8byq"/><stop offset="1" class="j9ig536pv"/></radialGradient><radialGradient id="ixkEV5d" cx="0" cy="0" r="1" gradientTransform="matrix(.69531 0 0 .82031 21.666 14.83)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="gh1umgbbt"/><stop offset="1" class="lefbu6b0u"/></radialGradient><radialGradient id="iIFXOpY" cx="0" cy="0" r="1" gradientTransform="rotate(174.491 9.403 8.468)scale(6.18482 6.87814)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="b1hc77b2b"/><stop offset="1" class="b94-l-y5w"/></radialGradient><radialGradient id="ivUdZ9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.85156 -18.8335 0 16 12.151)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="ud25m0b8k"/><stop offset=".953" class="fchmo6-wr"/></radialGradient><radialGradient id="iwf32be" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 14.187)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="bo6sve4_m"/><stop offset=".902" class="aud44laqb"/></radialGradient><radialGradient id="i4hQP9i" cx="0" cy="0" r="1" gradientTransform="matrix(.87207 1.75 -1.15013 .57314 11.06 9.714)" gradientUnits="userSpaceOnUse"><stop class="f7m1yfx-m"/><stop offset="1" class="p3lw01bbh"/></radialGradient><radialGradient id="i75J2Tc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="vk3h5kjsq"/><stop offset="1" class="dsheu9oxu"/></radialGradient><radialGradient id="id6i3Ie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="vk3h5kjsq"/><stop offset="1" class="dsheu9oxu"/></radialGradient><radialGradient id="iIwGXkc" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 17.003)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="q_3bb9b3h"/><stop offset="1" class="h65c54lsi"/></radialGradient><radialGradient id="ijfXANf" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.541 16.204)" gradientUnits="userSpaceOnUse"><stop class="x_31h1mma"/><stop offset="1" class="c7c54u04z"/></radialGradient><radialGradient id="iApS9Nc" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 -.39062 1.75486 .91253 14.92 18.59)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="j2uqjm0oz"/><stop offset="1" class="qf8pq8giw"/></radialGradient><radialGradient id="i3ap72h" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -2.65625 .92293 1.02066 11.747 6.323)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="jvoslhnfo"/><stop offset="1" class="ra_978hnp"/></radialGradient><radialGradient id="iJFE1zb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 -2.11178 1.39023 -1.15206 20.013 6.964)" gradientUnits="userSpaceOnUse"><stop class="sh2scbbge"/><stop offset="1" class="peuf8pa6k"/></radialGradient><radialGradient id="ic6rT3P" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69202 -.32813 .16397 -.8455 15.983 6.689)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="t1cyeof7i"/><stop offset="1" class="k3jqymbow"/></radialGradient><radialGradient id="iTj3RqD" cx="0" cy="0" r="1" gradientTransform="matrix(-.79689 -2.51562 5.42206 -1.71758 13.669 8.23)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="isqcarb8m"/><stop offset=".853" class="p1jebm44k"/></radialGradient><radialGradient id="iy6uxjZ" cx="0" cy="0" r="1" gradientTransform="rotate(32.574 -4.662 35.8)scale(2.67 1.26933)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="eo-2wiogo"/><stop offset="1" class="y2d334cwi"/></radialGradient><radialGradient id="iEL4vsb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8291 2.17918 -1.87822 -2.4384 19.396 6.561)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="ijglzsb6p"/><stop offset="1" class="zy380ub3a"/></radialGradient><radialGradient id="iCumQnf" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79686 -2.67189 1.32522 -.89122 11.81 10.683)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="e45b6kbci"/><stop offset="1" class="s4dmvvdkq"/></radialGradient><radialGradient id="i6ADrgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.518 1.879)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><radialGradient id="iEW7qfb" cx="0" cy="0" r="1" gradientTransform="matrix(5.8706 -6.28124 5.4446 5.08866 18.265 9.83)" gradientUnits="userSpaceOnUse"><stop class="cbx5-fbbx"/><stop offset="1" class="vfm0_vraw"/></radialGradient><radialGradient id="iBfloSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 11.01 6.36)" gradientUnits="userSpaceOnUse"><stop class="p7wwt2b_k"/><stop offset="1" class="o1syipbau"/></radialGradient><radialGradient id="iEBQIde" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.313 9.84)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="s4ff5rbng"/><stop offset="1" class="mqv57bcbp"/></radialGradient><filter id="iCiMiCe" width="21.451" height="8.965" x="5.649" y="21.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.262745 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24256"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.380392 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24256" result="effect2_innerShadow_3987_24256"/></filter><filter id="iI4sZCn" width="2.256" height="3.995" x="9.377" y="15.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.258824 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24256"/></filter><filter id="it727Sb" width="2.986" height="2.986" x="9.111" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".1"/></filter><filter id="iQxRDFr" width="2.986" height="2.986" x="19.904" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".1"/></filter><filter id="iRLeQWb" width="12.252" height="14.898" x="10.124" y="7.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.40335 0 0 0 0 0.308846 0 0 0 0 0.287845 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24256"/></filter><filter id="iXE6Q8m" width="3.829" height="3.829" x="11.609" y="11.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".25"/></filter><filter id="ifGLuYd" width="7.729" height="10.962" x="15.437" y="4.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".5"/></filter><filter id="iwCoqZb" width="7.108" height="9.773" x="8.377" y="5.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".5"/></filter><filter id="iABFQte" width="2.699" height="1.214" x="11.797" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24256"/></filter><filter id="igS0LSc" width="2.399" height=".914" x="11.847" y="12.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".075"/></filter><filter id="iPkdeNc" width="2.699" height="1.214" x="17.703" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24256"/></filter><filter id="iLOBRjb" width="2.399" height=".914" x="17.753" y="12.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".075"/></filter><filter id="iF16RYd" width="2.618" height=".92" x="12.269" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".075"/></filter><filter id="iKgDMzn" width="2.618" height=".92" x="17.16" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".075"/></filter><filter id="i9FkZdb" width="3.122" height="4.211" x="14.162" y="13.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".25"/></filter><filter id="inVLG1c" width="4.199" height="1.729" x="13.906" y="17.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".05"/></filter><filter id="iQ0vace" width="10.047" height="6.351" x="11.473" y="4.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.054902 0 0 0 0 0.0156863 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24256"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24256" result="effect2_innerShadow_3987_24256"/></filter><filter id="iFBCMjb" width="4.387" height="2.271" x="11.746" y="5.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".075"/></filter><filter id="ihE9oYb" width="4.219" height="4.689" x="15.869" y="5.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".125"/></filter><filter id="ingMdic" width="6.686" height="12.903" x="8.599" y="1.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24256"/></filter><filter id="iG5Wynb" width="6.436" height="12.953" x="17.239" y="1.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24256"/></filter><filter id="icbeKDd" width="6.436" height="12.953" x="17.239" y="1.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0784314 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24256"/></filter><filter id="iJF7RMd" width="5.843" height="12.292" x="17.83" y="2.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".25"/></filter><filter id="i2NDftj" width="2.811" height="6.368" x="8.719" y="8.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".375"/></filter><filter id="ijyL7Qx" width="5.14" height="8.355" x="9.673" y="1.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24256" stdDeviation=".25"/></filter><linearGradient id="iW06rJI" x1="14.021" x2="11.81" y1="12.289" y2="12.753" gradientUnits="userSpaceOnUse"><stop class="du3_mqevj"/><stop offset="1" class="hpzn95b1x"/></linearGradient><linearGradient id="i7HnxNe" x1="17.979" x2="20.19" y1="12.234" y2="12.698" gradientUnits="userSpaceOnUse"><stop class="du3_mqevj"/><stop offset="1" class="hpzn95b1x"/></linearGradient><linearGradient id="if0QA0c" x1="14.936" x2="12.494" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="d3bth9bgz"/><stop offset=".32" class="rulb4ox_k"/><stop offset=".794" class="rulb4ox_k"/><stop offset="1" class="omc-6wb_b"/></linearGradient><linearGradient id="ihTiIAe" x1="19.826" x2="17.385" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="d3bth9bgz"/><stop offset=".32" class="rulb4ox_k"/><stop offset=".794" class="rulb4ox_k"/><stop offset="1" class="omc-6wb_b"/></linearGradient><linearGradient id="i8JXXHb" x1="16.885" x2="15.848" y1="15.735" y2="15.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="cbx5-fbbx"/><stop offset="1" class="vfm0_vraw"/></linearGradient><linearGradient id="iVPYtBc" x1="10.124" x2="10.124" y1="13.342" y2="8.511" gradientUnits="userSpaceOnUse"><stop class="p-tc_9j4a"/><stop offset="1" class="a4q8d6dqq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-getting-massage-dark" /></template>
<style>
.a4q8d6dqq {
  stop-color: var(--svg-color--523c3c, #523C3C);
  stop-opacity: 0;
}

.ajvihphfe {
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.am_6_g2wh {
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.aud44laqb {
  stop-color: var(--svg-color--362325, #362325);
}

.b1hc77b2b {
  stop-color: var(--svg-color--4d302c, #4D302C);
}

.b94-l-y5w {
  stop-color: var(--svg-color--3c2728, #3C2728);
}

.b9796ab2x {
  stop-color: var(--svg-color--3d3b3b, #3D3B3B);
}

.bnga0rw3i {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.578c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.056.243.013.25.135a.15.15 0 0 1-.014.077c-.76 1.47-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.122.142-.192.25-.135Z");
}

.bo6sve4_m {
  stop-color: var(--svg-color--3f292a, #3F292A);
}

.c7c54u04z {
  stop-color: var(--svg-color--635150, #635150);
  stop-opacity: 0;
}

.cbx5-fbbx {
  stop-color: var(--svg-color--675553, #675553);
}

.d3bth9bgz {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
}

.dbl7bjuhw {
  fill: var(--svg-color--290118, #290118);
  d: path("M14.357 17.578c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.056.243.013.25.135a.15.15 0 0 1-.014.077c-.76 1.47-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.122.142-.192.25-.135");
}

.dit5vub-g {
  stop-color: var(--svg-color--311617, #311617);
  stop-opacity: 0;
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

.e45b6kbci {
  stop-color: var(--svg-color--2d151b, #2D151B);
}

.e4qmmebvg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.eh43pve_h {
  d: path("m9.469 9.256l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.eo-2wiogo {
  stop-color: var(--svg-color--4d484a, #4D484A);
}

.f7m1yfx-m {
  stop-color: var(--svg-color--9b4607, #9B4607);
}

.fchmo6-wr {
  stop-color: var(--svg-color--541d1d, #541D1D);
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

.g3cj9mbqt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.g5_ia9syq {
  d: path("M22.623 15.636h-2.207v3.894c.934.024 1.977-.949 2.121-2.277z");
}

.gh1umgbbt {
  stop-color: var(--svg-color--4c3938, #4C3938);
}

.grwnnnb5d {
  stop-color: var(--svg-color--301c27, #301C27);
}

.h26e4sgsm {
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.h65c54lsi {
  stop-color: var(--svg-color--3f222e, #3F222E);
  stop-opacity: 0;
}

.hpzn95b1x {
  stop-color: var(--svg-color--2c2c2d, #2C2C2D);
  stop-opacity: 0;
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

.j-62o8btp {
  fill: var(--svg-color--241e22, #241E22);
  d: path("M9.377 15.636h2.156v3.894c-.933.024-2.035-1.054-2.105-2.27z");
}

.j0j5vybko {
  cx: 13.524px;
  cy: 13.487px;
  r: 1.415px;
}

.j2uqjm0oz {
  stop-color: var(--svg-color--58494a, #58494A);
}

.j4vtsjbvv {
  fill: var(--svg-color--1a0a0d, #1A0A0D);
  d: path("M9.377 6.692h2.83v.372c0 .29.186.855.564 1.181c.31.287.904.875 1.426 1.397a.987.987 0 0 1-.022 1.416c-.374.354-.898.299-1.282-.045l-.81-.61a.435.435 0 0 0-.725.323v2.748a.99.99 0 0 1-1.981 0z");
}

.j9ig536pv {
  stop-color: var(--svg-color--47232a, #47232A);
}

.jvoslhnfo {
  stop-color: var(--svg-color--444142, #444142);
}

.jvs9aeb5c {
  d: path("m21.12 8.376l-2.021 1.488c-.245.18-.471.42-.677.196c-.22-.238-.007-.337.229-.559a52 52 0 0 1 1.99-1.786c.875-.734.85-2.108.828-2.57V2.568h1.704V13.28a.579.579 0 0 1-1.157 0V9.044c0-.403-.572-.907-.896-.668");
}

.k3jqymbow {
  stop-color: var(--svg-color--423b3e, #423B3E);
  stop-opacity: 0;
}

.kkqz5eb_f {
  d: path("M12.88 6.098a4.6 4.6 0 0 0-.984.547l.261 1.119l2.828.037a.986.986 0 1 0 .013-1.972h-.646c-.277 0-.96.054-1.472.27");
}

.l5nmerp-e {
  stop-color: var(--svg-color--252227, #252227);
}

.lefbu6b0u {
  stop-color: var(--svg-color--3c2221, #3C2221);
}

.lln5h90we {
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

.m2_qidb8o {
  fill: var(--svg-color--3f2929, #3F2929);
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mgwbr9b7z {
  fill: var(--svg-color--452e2c, #452E2C);
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

.mqv57bcbp {
  stop-color: var(--svg-color--6a5856, #6A5856);
  stop-opacity: 0;
}

.my0c8s4fp {
  stop-color: var(--svg-color--5b4645, #5B4645);
}

.n_nhnibbq {
  stop-color: var(--svg-color--59403f, #59403F);
  stop-opacity: 0;
}

.na9kkhbsz {
  stop-color: var(--svg-color--ffe041, #FFE041);
  stop-opacity: 0;
}

.nnet9bbrm {
  cx: 21.396px;
  cy: 14.61px;
  r: 1.293px;
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.omc-6wb_b {
  stop-color: var(--svg-color--2e2e2e, #2E2E2E);
}

.p-tc_9j4a {
  stop-color: var(--svg-color--523c3c, #523C3C);
}

.p1jebm44k {
  stop-color: var(--svg-color--494647, #494647);
}

.p3lw01bbh {
  stop-color: var(--svg-color--d97513, #D97513);
}

.p7wwt2b_k {
  stop-color: var(--svg-color--685654, #685654);
}

.peuf8pa6k {
  stop-color: var(--svg-color--353133, #353133);
  stop-opacity: 0;
}

.phs3tubib {
  stop-color: var(--svg-color--332122, #332122);
}

.pj2xknbvf {
  stop-color: var(--svg-color--311617, #311617);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.q_3bb9b3h {
  stop-color: var(--svg-color--3f222e, #3F222E);
}

.qf8pq8giw {
  stop-color: var(--svg-color--58494a, #58494A);
  stop-opacity: 0;
}

.qmod-43sl {
  stop-color: var(--svg-color--ff7645, #FF7645);
  stop-opacity: 0;
}

.qtf9d8byq {
  stop-color: var(--svg-color--47232a, #47232A);
  stop-opacity: 0;
}

.r57wbabrk {
  fill: var(--svg-color--261c20, #261C20);
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.ra_978hnp {
  stop-color: var(--svg-color--363133, #363133);
  stop-opacity: 0;
}

.rulb4ox_k {
  stop-color: var(--svg-color--242425, #242425);
}

.s4dmvvdkq {
  stop-color: var(--svg-color--58403c, #58403C);
  stop-opacity: 0;
}

.s4ff5rbng {
  stop-color: var(--svg-color--6a5856, #6A5856);
}

.sh2scbbge {
  stop-color: var(--svg-color--393838, #393838);
}

.srcdcl_yh {
  cx: 21.396px;
  cy: 14.61px;
  r: 1.979px;
}

.stq2e3bfc {
  fill: var(--svg-color--563c39, #563C39);
  d: path("M8.599 2.026h3.425v3.742c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.879.393v3.327a1.2 1.2 0 0 1-2.398 0z");
}

.t1cyeof7i {
  stop-color: var(--svg-color--423b3e, #423B3E);
}

.tsm0b8b0x {
  fill: var(--svg-color--211314, #211314);
  d: path("M22.166 7.572h-3.173V5.768c0 .352-.21 1.035-.633 1.43a76 76 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.714c.42.429 1.01.362 1.44-.054l.905-.74a.464.464 0 0 1 .692.043c.08.097.123.221.123.35v3.327c0 .663.497 1.2 1.11 1.2s1.111-.537 1.111-1.2z");
}

.ud25m0b8k {
  stop-color: var(--svg-color--40222e, #40222E);
  stop-opacity: 0;
}

.v_56mwb2a {
  cx: 10.604px;
  cy: 14.61px;
  r: 1.293px;
  fill: var(--svg-color--261417, #261417);
}

.vfm0_vraw {
  stop-color: var(--svg-color--675553, #675553);
  stop-opacity: 0;
}

.vk3h5kjsq {
  stop-color: var(--svg-color--140a18, #140A18);
}

.w5a3tprnu {
  d: path("M8.599 2.026h3.425v3.742c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.879.393v3.327a1.2 1.2 0 0 1-2.398 0z");
}

.whuwqfbzs {
  fill: var(--svg-color--341c22, #341C22);
  d: path("M15.872 13.956c-.163 0-.248.093-.297.254l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.16-.045-.254-.209-.254");
}

.wkqd0hb4b {
  d: path("m10.127 10.745l.203 6.485c.233 3.376 2.209 4.755 5.637 4.773h.066c3.428-.018 5.404-1.397 5.637-4.773l.203-6.485c.069-2.2-1.117-3.344-1.719-3.64h-8.308c-.602.296-1.788 1.44-1.72 3.64");
}

.wv6byccxz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.494 14.23c.146.164.536.45 1.024.468c.617.024.949-.304 1.144-.469");
}

.x_31h1mma {
  stop-color: var(--svg-color--635150, #635150);
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

.y581ksbre {
  stop-color: var(--svg-color--462b30, #462B30);
}

.y5pz67bvw {
  stroke: var(--svg-color--0c0808, #0C0808);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.072 12.753c.258-.207.883-.578 1.95-.43");
}

.ydm9ddced {
  stop-color: var(--svg-color--59403f, #59403F);
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

.ze6s0wf9k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.072 12.753c.258-.207.883-.578 1.95-.43");
}

.zl8nqy82h {
  stop-color: var(--svg-color--ff641f, #FF641F);
}

.zr454ebou {
  fill: var(--svg-color--482c2f, #482C2F);
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.zy380ub3a {
  stop-color: var(--svg-color--1c0f1e, #1C0F1E);
}

</style>
