<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iu2tWvb)"><path fill="url(#iNaJQ8d)" class="dkva-0p2a"/><path fill="url(#iSwkn4c)" class="dkva-0p2a"/></g><path class="zoi6eqh_q"/><path fill="url(#iMh4s0d)" class="h26e4sgsm"/><path fill="url(#imLXQNe)" class="h26e4sgsm"/><g filter="url(#iFpH98d)"><path class="qmli3gaft"/></g><path fill="url(#izYC2bb)" class="g5_ia9syq"/><circle fill="url(#iXVqDMd)" class="i7fnn1bcq"/><g filter="url(#ia9O8bb)" class="mc2zb0bvp"><circle class="plmsrlygi"/></g><circle fill="url(#iHGSrBd)" class="srcdcl_yh"/><circle fill="url(#iKkf6wc)" class="srcdcl_yh"/><g filter="url(#iFicvrd)"><circle fill="url(#if52vnd)" class="nnet9bbrm"/></g><g filter="url(#i2f53ds)"><path fill="url(#iB4kyie)" class="wkqd0hb4b"/></g><path fill="url(#iIfzz8c)" class="wkqd0hb4b"/><g filter="url(#iJuXoub)"><circle fill="url(#iKUyYVq)" class="j0j5vybko"/></g><g filter="url(#inLLXYb)"><path fill="url(#ifun3Wb)" class="vlr6nmb6w"/></g><g filter="url(#if5rtTd)"><path fill="url(#izKXPPc)" class="ic-dvmxoa"/></g><g filter="url(#i71DeDb)"><path class="g0i_cusgo"/></g><g filter="url(#iEq3zcN)"><path stroke="url(#i5ehQye)" class="ze6s0wf9k"/></g><g filter="url(#if2tPRb)"><path class="tdfbvnd8s"/></g><g filter="url(#i1d0Xre)"><path stroke="url(#imITkoC)" class="g-lz2-rad"/></g><path stroke="url(#irpmfLe)" class="xjyo8kbbd"/><g filter="url(#iQ0sCKd)"><path stroke="url(#i3YMDSb)" class="wv6byccxz"/></g><path stroke="url(#izeyfpd)" class="e4qmmebvg"/><g filter="url(#iZKbCkc)"><path stroke="url(#iViLW3b)" class="g3cj9mbqt"/></g><g filter="url(#iM40o7c)"><path class="rc1c54gsu"/></g><path class="n_z_r4bmy"/><path fill="url(#izxoiUd)" class="lln5h90we"/><path fill="url(#ikPOH3c)" class="lln5h90we"/><path fill="url(#ileKbvc)" class="lln5h90we"/><g filter="url(#iICpoDd)"><path stroke="url(#irf29sc)" class="p4t0ota3q"/></g><path class="imx5w3bkl"/><g filter="url(#iMMxY9L)"><path class="zdsnodkhx"/><path fill="url(#i5xukab)" class="am_6_g2wh"/><path fill="url(#iLcznBd)" class="am_6_g2wh"/></g><g filter="url(#iv5AGjm)"><path fill="url(#iStHWZd)" class="kkqz5eb_f"/><path fill="url(#iec6Ele)" class="kkqz5eb_f"/></g><g filter="url(#iB8bj3d)"><path fill="url(#ikxJevc)" class="dj4m7-bab"/><path fill="url(#ivRKpMd)" class="dj4m7-bab"/></g><g filter="url(#ioKoGfb)"><path class="qha1dzbbj"/><path fill="url(#iR0xbxb)" class="w5a3tprnu"/></g><g filter="url(#io3LJRd)"><path class="htw-10p4r"/><path fill="url(#i6ADrgd)" class="ajvihphfe"/></g><g filter="url(#iH9tRGL)"><path class="ogehumy5z"/></g><g filter="url(#irokq1d)"><path fill="url(#iTaXUad)" class="jvs9aeb5c"/></g><g filter="url(#iMqOsJc)"><path fill="url(#iStWd7b)" class="eh43pve_h"/></g><g filter="url(#iMaA4WZ)"><path fill="url(#isG56rh)" class="fgf4_ac8o"/><path fill="url(#iFGCQRR)" class="fgf4_ac8o"/></g><defs><radialGradient id="iNaJQ8d" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -12.0938 23.481 28.558)" gradientUnits="userSpaceOnUse"><stop class="zl8nqy82h"/><stop offset="1" class="yu799baro"/></radialGradient><radialGradient id="iSwkn4c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65628 -9.43744 11.80863 -5.8262 23.606 28.683)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="dwoq6zbym"/><stop offset="1" class="qmod-43sl"/></radialGradient><radialGradient id="iMh4s0d" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.147 14.718)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="lpu_4e3zg"/><stop offset="1" class="bk2ujv-xu"/></radialGradient><radialGradient id="imLXQNe" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.8125 -5.89395 3.25184 14.513 21.464)" gradientUnits="userSpaceOnUse"><stop class="srb0dp7as"/><stop offset="1" class="n_0ffbr5z"/></radialGradient><radialGradient id="izYC2bb" cx="0" cy="0" r="1" gradientTransform="matrix(.24766 1.90842 -1.09256 .14178 21.78 16.259)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="ubdc0bcrp"/><stop offset="1" class="jpj59wv-o"/></radialGradient><radialGradient id="iXVqDMd" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.508 17.256)scale(2.88068)" gradientUnits="userSpaceOnUse"><stop class="m2q2vh2sa"/><stop offset="1" class="he4p8yb1z"/></radialGradient><radialGradient id="iHGSrBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7615 .75741 -.7977 -.802 23.307 14.423)" gradientUnits="userSpaceOnUse"><stop class="k377ck8jo"/><stop offset="1" class="x101rabpv"/></radialGradient><radialGradient id="iKkf6wc" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.433 21.15)scale(2.34213)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="o4bfrybwl"/><stop offset="1" class="k3si3xnlp"/></radialGradient><radialGradient id="if52vnd" cx="0" cy="0" r="1" gradientTransform="matrix(.69531 0 0 .82031 21.666 14.83)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="k87xpnbmx"/><stop offset="1" class="nk_-g356a"/></radialGradient><radialGradient id="iB4kyie" cx="0" cy="0" r="1" gradientTransform="rotate(174.491 9.403 8.468)scale(6.18482 6.87814)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="c_0yu_b0g"/><stop offset="1" class="apsq0tbar"/></radialGradient><radialGradient id="iIfzz8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.85156 -11.5834 0 16 12.151)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="moytht6jc"/><stop offset="1" class="m6gudr5ml"/></radialGradient><radialGradient id="iKUyYVq" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 14.187)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cltcdpbpn"/><stop offset=".902" class="av0tm7_uc"/></radialGradient><radialGradient id="ifun3Wb" cx="0" cy="0" r="1" gradientTransform="rotate(121.239 7.63 10.913)scale(4.45901 3.87689)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="v8wjp2hus"/><stop offset="1" class="u3cxmmb4z"/></radialGradient><radialGradient id="izKXPPc" cx="0" cy="0" r="1" gradientTransform="matrix(.8584 4.94563 -3.25037 .56416 11.073 9.519)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="ou2-vlbjv"/><stop offset="1" class="nz0j9tb8x"/></radialGradient><radialGradient id="irpmfLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="g9mjpo7pf"/><stop offset="1" class="o2l1ytrej"/></radialGradient><radialGradient id="izeyfpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="g9mjpo7pf"/><stop offset="1" class="o2l1ytrej"/></radialGradient><radialGradient id="ikPOH3c" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 17.003)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ay0sr9bls"/><stop offset="1" class="ytd3ey6so"/></radialGradient><radialGradient id="ileKbvc" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.541 16.204)" gradientUnits="userSpaceOnUse"><stop class="o5qf-ej6a"/><stop offset="1" class="ilt16x1zy"/></radialGradient><radialGradient id="irf29sc" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 -.39063 1.75487 .91251 14.92 18.59)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="qdxirobsy"/><stop offset="1" class="fjwf4gbrh"/></radialGradient><radialGradient id="i5xukab" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -2.65625 .92293 1.02066 11.747 6.323)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="kkmfbvbin"/><stop offset="1" class="qrqshhbsh"/><stop offset="1" class="phfukacxx"/></radialGradient><radialGradient id="iLcznBd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 -2.11178 1.39023 -1.15206 20.013 6.964)" gradientUnits="userSpaceOnUse"><stop class="k0atq8toa"/><stop offset="1" class="gtgogdx4d"/></radialGradient><radialGradient id="iStHWZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69202 -.32813 .16397 -.8455 15.983 6.689)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="e3300gryr"/><stop offset="1" class="riww-ub9k"/></radialGradient><radialGradient id="iec6Ele" cx="0" cy="0" r="1" gradientTransform="matrix(-.79689 -2.51562 5.42206 -1.71758 13.669 8.23)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="ou1bzhb5f"/><stop offset=".853" class="dz7lmqc8k"/></radialGradient><radialGradient id="ikxJevc" cx="0" cy="0" r="1" gradientTransform="rotate(32.574 -4.662 35.8)scale(2.67 1.26933)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="g9tapqbwj"/><stop offset="1" class="pzm4junat"/></radialGradient><radialGradient id="ivRKpMd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8291 2.17918 -1.87822 -2.4384 19.396 6.561)" gradientUnits="userSpaceOnUse"><stop offset=".516" class="t9amzwbzu"/><stop offset="1" class="zy2malvpv"/></radialGradient><radialGradient id="iR0xbxb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79686 -2.67189 1.32522 -.89122 11.81 10.683)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="iclvvachy"/><stop offset="1" class="bc2wedbnb"/></radialGradient><radialGradient id="i6ADrgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.518 1.879)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><radialGradient id="iTaXUad" cx="0" cy="0" r="1" gradientTransform="matrix(5.8706 -6.28124 5.4446 5.08866 18.265 9.83)" gradientUnits="userSpaceOnUse"><stop class="k3jnt_bvt"/><stop offset="1" class="khh_otzli"/></radialGradient><radialGradient id="isG56rh" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 11.01 6.36)" gradientUnits="userSpaceOnUse"><stop class="b5e_facvp"/><stop offset="1" class="wj0_vcbzm"/></radialGradient><radialGradient id="iFGCQRR" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.313 9.84)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="hfhn00bef"/><stop offset="1" class="ws75vab8k"/></radialGradient><filter id="iu2tWvb" width="21.451" height="8.965" x="5.649" y="21.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.262745 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24262"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.380392 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24262" result="effect2_innerShadow_3987_24262"/></filter><filter id="iFpH98d" width="2.256" height="3.995" x="9.377" y="15.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.243137 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24262"/></filter><filter id="ia9O8bb" width="2.986" height="2.986" x="9.111" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".1"/></filter><filter id="iFicvrd" width="2.986" height="2.986" x="19.904" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".1"/></filter><filter id="i2f53ds" width="12.252" height="14.898" x="10.124" y="7.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.380392 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24262"/></filter><filter id="iJuXoub" width="3.829" height="3.829" x="11.609" y="11.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".25"/></filter><filter id="inLLXYb" width="7.729" height="10.962" x="15.437" y="4.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".5"/></filter><filter id="if5rtTd" width="7.108" height="9.773" x="8.377" y="5.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".5"/></filter><filter id="i71DeDb" width="2.699" height="1.214" x="11.797" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.12549 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24262"/></filter><filter id="iEq3zcN" width="2.399" height=".914" x="11.847" y="12.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".075"/></filter><filter id="if2tPRb" width="2.699" height="1.214" x="17.703" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.12549 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24262"/></filter><filter id="i1d0Xre" width="2.399" height=".914" x="17.753" y="12.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".075"/></filter><filter id="iQ0sCKd" width="2.618" height=".92" x="12.269" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".075"/></filter><filter id="iZKbCkc" width="2.618" height=".92" x="17.16" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".075"/></filter><filter id="iM40o7c" width="3.122" height="4.211" x="14.162" y="13.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".25"/></filter><filter id="iICpoDd" width="4.199" height="1.729" x="13.906" y="17.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".05"/></filter><filter id="iMMxY9L" width="10.047" height="6.351" x="11.473" y="4.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.109804 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24262"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24262" result="effect2_innerShadow_3987_24262"/></filter><filter id="iv5AGjm" width="4.387" height="2.271" x="11.746" y="5.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".075"/></filter><filter id="iB8bj3d" width="4.219" height="4.689" x="15.869" y="5.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".125"/></filter><filter id="ioKoGfb" width="6.686" height="12.903" x="8.599" y="1.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.407843 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24262"/></filter><filter id="io3LJRd" width="6.436" height="12.953" x="17.239" y="1.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24262"/></filter><filter id="iH9tRGL" width="6.436" height="12.953" x="17.239" y="1.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.309804 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24262"/></filter><filter id="irokq1d" width="5.843" height="12.292" x="17.83" y="2.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".25"/></filter><filter id="iMqOsJc" width="2.811" height="6.368" x="8.719" y="8.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".375"/></filter><filter id="iMaA4WZ" width="5.14" height="8.355" x="9.673" y="1.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24262" stdDeviation=".25"/></filter><linearGradient id="i5ehQye" x1="12.198" x2="14.021" y1="12.831" y2="12.081" gradientUnits="userSpaceOnUse"><stop class="jf-udwbdg"/><stop offset="1" class="v66a_wbdu"/></linearGradient><linearGradient id="imITkoC" x1="17.729" x2="19.928" y1="12.466" y2="12.534" gradientUnits="userSpaceOnUse"><stop class="jf-udwbdg"/><stop offset="1" class="v66a_wbdu"/></linearGradient><linearGradient id="i3YMDSb" x1="14.936" x2="12.494" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="t94urlgya"/><stop offset=".32" class="zhq7idx2s"/><stop offset=".794" class="r8us_1bpp"/><stop offset="1" class="zfzr_2buk"/></linearGradient><linearGradient id="iViLW3b" x1="19.826" x2="17.385" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="t94urlgya"/><stop offset=".32" class="zhq7idx2s"/><stop offset=".794" class="r8us_1bpp"/><stop offset="1" class="zfzr_2buk"/></linearGradient><linearGradient id="izxoiUd" x1="16.885" x2="15.848" y1="15.735" y2="15.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="usxz2na_s"/><stop offset="1" class="n0s808buc"/></linearGradient><linearGradient id="iStWd7b" x1="10.124" x2="10.124" y1="13.342" y2="8.511" gradientUnits="userSpaceOnUse"><stop class="k1tnctvtk"/><stop offset="1" class="ejsfj0d0t"/><stop offset="1" class="hlfpu6bzn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-getting-massage-medium" /></template>
<style>
.ajvihphfe {
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.am_6_g2wh {
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.apsq0tbar {
  stop-color: var(--svg-color--926762, #926762);
}

.av0tm7_uc {
  stop-color: var(--svg-color--8a5960, #8A5960);
}

.ay0sr9bls {
  stop-color: var(--svg-color--985c6e, #985C6E);
}

.b5e_facvp {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
}

.bc2wedbnb {
  stop-color: var(--svg-color--986c68, #986C68);
  stop-opacity: 0;
}

.bk2ujv-xu {
  stop-color: var(--svg-color--cc957d, #CC957D);
  stop-opacity: 0;
}

.c_0yu_b0g {
  stop-color: var(--svg-color--bd9076, #BD9076);
}

.cltcdpbpn {
  stop-color: var(--svg-color--996e64, #996E64);
}

.dj4m7-bab {
  d: path("M16.507 8.493c.547.846 1.51 1.29 1.847 1.279l1.484-2.327c-.861-2.406-2.462-1.924-3.028-1.562c-.694.444-.986 1.554-.303 2.61");
}

.dkva-0p2a {
  d: path("M5.65 29.974h20.7c-.494-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.665");
}

.dwoq6zbym {
  stop-color: var(--svg-color--ff7645, #FF7645);
}

.dz7lmqc8k {
  stop-color: var(--svg-color--564340, #564340);
}

.e3300gryr {
  stop-color: var(--svg-color--654646, #654646);
}

.e4qmmebvg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.eh43pve_h {
  d: path("m9.469 9.256l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.ejsfj0d0t {
  stop-color: var(--svg-color--886361, #886361);
  stop-opacity: 0;
}

.fgf4_ac8o {
  d: path("M10.173 5.384v-2.9h1.469V6.02a1 1 0 0 0 .28.693l2.262 2.349a.46.46 0 0 1-.636.663L11.184 7.63a3 3 0 0 1-1.011-2.246");
}

.fjwf4gbrh {
  stop-color: var(--svg-color--aa827c, #AA827C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g-lz2-rad {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.928 12.698c-.258-.207-.883-.578-1.95-.43");
}

.g0i_cusgo {
  stroke: var(--svg-color--322221, #322221);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.072 12.753c.258-.207.883-.578 1.95-.43");
}

.g3cj9mbqt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.g5_ia9syq {
  d: path("M22.623 15.636h-2.207v3.894c.934.024 1.977-.949 2.121-2.277z");
}

.g9mjpo7pf {
  stop-color: var(--svg-color--452537, #452537);
}

.g9tapqbwj {
  stop-color: var(--svg-color--644747, #644747);
}

.gtgogdx4d {
  stop-color: var(--svg-color--563e3b, #563E3B);
  stop-opacity: 0;
}

.h26e4sgsm {
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.he4p8yb1z {
  stop-color: var(--svg-color--824d5a, #824D5A);
}

.hfhn00bef {
  stop-color: var(--svg-color--c29b87, #C29B87);
}

.hlfpu6bzn {
  stop-color: var(--svg-color--b78b7f, #B78B7F);
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

.iclvvachy {
  stop-color: var(--svg-color--7d4755, #7D4755);
}

.ilt16x1zy {
  stop-color: var(--svg-color--be9586, #BE9586);
  stop-opacity: 0;
}

.imx5w3bkl {
  fill: var(--svg-color--88004e, #88004E);
  d: path("M14.357 17.578c.344.18.879.383 1.649.384c.77 0 1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.457-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135");
}

.j0j5vybko {
  cx: 13.524px;
  cy: 13.487px;
  r: 1.415px;
}

.jf-udwbdg {
  stop-color: var(--svg-color--533c3f, #533C3F);
  stop-opacity: 0;
}

.jpj59wv-o {
  stop-color: var(--svg-color--331e2b, #331E2B);
}

.jvs9aeb5c {
  d: path("m21.12 8.376l-2.021 1.488c-.245.18-.471.42-.677.196c-.22-.238-.007-.337.229-.559a52 52 0 0 1 1.99-1.786c.875-.734.85-2.108.828-2.57V2.568h1.704V13.28a.579.579 0 0 1-1.157 0V9.044c0-.403-.572-.907-.896-.668");
}

.k0atq8toa {
  stop-color: var(--svg-color--423534, #423534);
}

.k1tnctvtk {
  stop-color: var(--svg-color--b78b7f, #B78B7F);
}

.k377ck8jo {
  stop-color: var(--svg-color--c19883, #C19883);
}

.k3jnt_bvt {
  stop-color: var(--svg-color--bf9886, #BF9886);
}

.k3si3xnlp {
  stop-color: var(--svg-color--9e625e, #9E625E);
}

.k87xpnbmx {
  stop-color: var(--svg-color--ae8472, #AE8472);
}

.khh_otzli {
  stop-color: var(--svg-color--bf9886, #BF9886);
  stop-opacity: 0;
}

.kkmfbvbin {
  stop-color: var(--svg-color--503e3b, #503E3B);
}

.kkqz5eb_f {
  d: path("M12.88 6.098a4.6 4.6 0 0 0-.984.547l.261 1.119l2.828.037a.986.986 0 1 0 .013-1.972h-.646c-.277 0-.96.054-1.472.27");
}

.lln5h90we {
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

.lpu_4e3zg {
  stop-color: var(--svg-color--cc957d, #CC957D);
}

.m2q2vh2sa {
  stop-color: var(--svg-color--825856, #825856);
}

.m6gudr5ml {
  stop-color: var(--svg-color--a55361, #A55361);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.moytht6jc {
  stop-color: var(--svg-color--9d6171, #9D6171);
  stop-opacity: 0;
}

.n_0ffbr5z {
  stop-color: var(--svg-color--8d4c57, #8D4C57);
  stop-opacity: 0;
}

.n_z_r4bmy {
  fill: var(--svg-color--a57d6b, #A57D6B);
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

.n0s808buc {
  stop-color: var(--svg-color--c59e88, #C59E88);
  stop-opacity: 0;
}

.na9kkhbsz {
  stop-color: var(--svg-color--ffe041, #FFE041);
  stop-opacity: 0;
}

.nk_-g356a {
  stop-color: var(--svg-color--a57460, #A57460);
}

.nnet9bbrm {
  cx: 21.396px;
  cy: 14.61px;
  r: 1.293px;
}

.nz0j9tb8x {
  stop-color: var(--svg-color--855b55, #855B55);
}

.o2l1ytrej {
  stop-color: var(--svg-color--4b302e, #4B302E);
}

.o4bfrybwl {
  stop-color: var(--svg-color--9e625e, #9E625E);
  stop-opacity: 0;
}

.o5qf-ej6a {
  stop-color: var(--svg-color--be9586, #BE9586);
}

.ogehumy5z {
  fill: var(--svg-color--a47a6f, #A47A6F);
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.ou1bzhb5f {
  stop-color: var(--svg-color--564340, #564340);
  stop-opacity: 0;
}

.ou2-vlbjv {
  stop-color: var(--svg-color--4e2c2d, #4E2C2D);
}

.p4t0ota3q {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.578c.344.18.879.383 1.649.384c.77 0 1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.457-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135Z");
}

.phfukacxx {
  stop-color: var(--svg-color--503e3b, #503E3B);
  stop-opacity: 0;
}

.plmsrlygi {
  cx: 10.604px;
  cy: 14.61px;
  r: 1.293px;
  fill: var(--svg-color--734743, #734743);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.pzm4junat {
  stop-color: var(--svg-color--644747, #644747);
  stop-opacity: 0;
}

.qdxirobsy {
  stop-color: var(--svg-color--aa827c, #AA827C);
}

.qha1dzbbj {
  fill: var(--svg-color--a47b6d, #A47B6D);
  d: path("M8.599 2.026h3.425v3.742c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.879.393v3.327a1.2 1.2 0 0 1-2.398 0z");
}

.qmli3gaft {
  fill: var(--svg-color--2e2024, #2E2024);
  d: path("M9.377 15.636h2.156v3.894c-.933.024-2.035-1.054-2.105-2.27z");
}

.qmod-43sl {
  stop-color: var(--svg-color--ff7645, #FF7645);
  stop-opacity: 0;
}

.qrqshhbsh {
  stop-color: var(--svg-color--383031, #383031);
  stop-opacity: 0;
}

.r8us_1bpp {
  stop-color: var(--svg-color--4b3135, #4B3135);
}

.rc1c54gsu {
  fill: var(--svg-color--8d5e5f, #8D5E5F);
  d: path("M15.872 13.956c-.163 0-.248.093-.297.254l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.16-.045-.254-.209-.254");
}

.riww-ub9k {
  stop-color: var(--svg-color--55333c, #55333C);
  stop-opacity: 0;
}

.srb0dp7as {
  stop-color: var(--svg-color--8d4c57, #8D4C57);
}

.srcdcl_yh {
  cx: 21.396px;
  cy: 14.61px;
  r: 1.979px;
}

.t94urlgya {
  stop-color: var(--svg-color--584141, #584141);
}

.t9amzwbzu {
  stop-color: var(--svg-color--4d2c38, #4D2C38);
  stop-opacity: 0;
}

.tdfbvnd8s {
  stroke: var(--svg-color--4a2f2d, #4A2F2D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.928 12.753c-.258-.207-.883-.578-1.95-.43");
}

.u3cxmmb4z {
  stop-color: var(--svg-color--7a4d53, #7A4D53);
}

.ubdc0bcrp {
  stop-color: var(--svg-color--463939, #463939);
}

.usxz2na_s {
  stop-color: var(--svg-color--c59e88, #C59E88);
}

.v66a_wbdu {
  stop-color: var(--svg-color--533c3f, #533C3F);
}

.v8wjp2hus {
  stop-color: var(--svg-color--563233, #563233);
}

.vlr6nmb6w {
  d: path("M22.166 7.572h-3.173V5.768c0 .352-.21 1.035-.633 1.43a76 76 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.714c.42.429 1.01.362 1.44-.054l.905-.74a.464.464 0 0 1 .692.043c.08.097.123.221.123.35v3.327c0 .663.497 1.2 1.11 1.2s1.111-.537 1.111-1.2z");
}

.w5a3tprnu {
  d: path("M8.599 2.026h3.425v3.742c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.879.393v3.327a1.2 1.2 0 0 1-2.398 0z");
}

.wj0_vcbzm {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
  stop-opacity: 0;
}

.wkqd0hb4b {
  d: path("m10.127 10.745l.203 6.485c.233 3.376 2.209 4.755 5.637 4.773h.066c3.428-.018 5.404-1.397 5.637-4.773l.203-6.485c.069-2.2-1.117-3.344-1.719-3.64h-8.308c-.602.296-1.788 1.44-1.72 3.64");
}

.ws75vab8k {
  stop-color: var(--svg-color--c29b87, #C29B87);
  stop-opacity: 0;
}

.wv6byccxz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.494 14.23c.146.164.536.45 1.024.468c.617.024.949-.304 1.144-.469");
}

.x101rabpv {
  stop-color: var(--svg-color--b28278, #B28278);
}

.xjyo8kbbd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 14.23c.146.164.536.45 1.024.468c.617.024.949-.304 1.144-.469");
}

.ytd3ey6so {
  stop-color: var(--svg-color--985c6e, #985C6E);
  stop-opacity: 0;
}

.yu799baro {
  stop-color: var(--svg-color--ff5026, #FF5026);
}

.zdsnodkhx {
  fill: var(--svg-color--59403d, #59403D);
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.ze6s0wf9k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.072 12.753c.258-.207.883-.578 1.95-.43");
}

.zfzr_2buk {
  stop-color: var(--svg-color--564040, #564040);
}

.zhq7idx2s {
  stop-color: var(--svg-color--503839, #503839);
}

.zl8nqy82h {
  stop-color: var(--svg-color--ff641f, #FF641F);
}

.zoi6eqh_q {
  fill: var(--svg-color--aa746e, #AA746E);
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.zy2malvpv {
  stop-color: var(--svg-color--3d1e29, #3D1E29);
}

</style>
