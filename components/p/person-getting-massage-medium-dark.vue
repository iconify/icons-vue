<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ipbRBxd)"><path fill="url(#iNaJQ8d)" class="dkva-0p2a"/><path fill="url(#iSwkn4c)" class="dkva-0p2a"/></g><path class="o1ei7wb2z"/><path fill="url(#i42z42c)" class="h26e4sgsm"/><path fill="url(#ipp54Ie)" class="h26e4sgsm"/><g filter="url(#iJOIF8d)"><path class="vj1esr5wb"/></g><path fill="url(#iPBOMbc)" class="g5_ia9syq"/><circle fill="url(#i7LoUyc)" class="i7fnn1bcq"/><g filter="url(#iuhMiOS)" class="mc2zb0bvp"><circle class="jydgsvcms"/></g><circle fill="url(#iDPHOne)" class="srcdcl_yh"/><circle fill="url(#icS3o1d)" class="srcdcl_yh"/><g filter="url(#iFBJhBd)"><circle fill="url(#iEDGwed)" class="nnet9bbrm"/></g><g filter="url(#iNsb9tb)"><path fill="url(#isCKzRR)" class="wkqd0hb4b"/></g><path fill="url(#iBkJved)" class="wkqd0hb4b"/><g filter="url(#iZlmHrc)"><circle fill="url(#i2VPMbe)" class="j0j5vybko"/></g><g filter="url(#is5aJni)"><path class="eaevyhbaf"/></g><g filter="url(#iD7DZsJ)"><path fill="url(#i4hQP9i)" class="ic-dvmxoa"/><path class="jxphwjdmk"/></g><g filter="url(#iPQSURd)"><path class="g0i_cusgo"/></g><g filter="url(#i4BtrHs)"><path stroke="url(#imT7ZYd)" class="ze6s0wf9k"/></g><g filter="url(#inrDCzb)"><path class="ld2mc9kvg"/></g><g filter="url(#ifxbhmd)"><path stroke="url(#i2PbjGe)" class="g-lz2-rad"/></g><path stroke="url(#iMYoVKb)" class="xjyo8kbbd"/><g filter="url(#i483cKd)"><path stroke="url(#ioJoXBd)" class="wv6byccxz"/></g><path stroke="url(#i4z16cc)" class="e4qmmebvg"/><g filter="url(#ijY3hwb)"><path stroke="url(#icIOaAd)" class="g3cj9mbqt"/></g><g filter="url(#ienoI5b)"><path class="b6za14b0m"/></g><path class="sq9m-fbvs"/><path fill="url(#imTmQon)" class="lln5h90we"/><path fill="url(#iG0A0We)" class="lln5h90we"/><path fill="url(#i8bTAHb)" class="lln5h90we"/><g filter="url(#imUg1xe)"><path stroke="url(#iCx5xKe)" class="bnga0rw3i"/></g><path class="noy15ebni"/><g filter="url(#ibanyhd)"><path class="z2o3d6bto"/><path fill="url(#i5jqakE)" class="am_6_g2wh"/><path fill="url(#iilVhed)" class="am_6_g2wh"/></g><g filter="url(#i5oqQXd)"><path fill="url(#iIJbX6d)" class="kkqz5eb_f"/><path fill="url(#iOlfHTd)" class="kkqz5eb_f"/></g><g filter="url(#inUgFyd)"><path fill="url(#iwEQgOd)" class="dj4m7-bab"/><path fill="url(#igxBKIS)" class="dj4m7-bab"/></g><g filter="url(#i7P718c)"><path class="x1cyw_brl"/><path fill="url(#i3gR8Ph)" class="w5a3tprnu"/></g><g filter="url(#iX8wppd)"><path class="htw-10p4r"/><path fill="url(#i6ADrgd)" class="ajvihphfe"/></g><g filter="url(#islk0Tc)"><path class="p3p0m3wfz"/></g><g filter="url(#iv8gZod)"><path fill="url(#i44UlBb)" class="jvs9aeb5c"/></g><g filter="url(#iOZSZxc)"><path fill="url(#iDXEPWd)" class="eh43pve_h"/></g><g filter="url(#i1TycOn)"><path fill="url(#iCOQPMc)" class="fgf4_ac8o"/><path fill="url(#ioIUsuc)" class="fgf4_ac8o"/></g><defs><radialGradient id="iNaJQ8d" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -12.0938 23.481 28.558)" gradientUnits="userSpaceOnUse"><stop class="zl8nqy82h"/><stop offset="1" class="yu799baro"/></radialGradient><radialGradient id="iSwkn4c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65628 -9.43744 11.80863 -5.8262 23.606 28.683)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="dwoq6zbym"/><stop offset="1" class="qmod-43sl"/></radialGradient><radialGradient id="i42z42c" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.147 14.718)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="wzapgli4e"/><stop offset="1" class="vnuk5ibgy"/></radialGradient><radialGradient id="ipp54Ie" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.8125 -5.89395 3.25184 14.513 21.464)" gradientUnits="userSpaceOnUse"><stop class="rzvl5tbzx"/><stop offset="1" class="vonrxsbes"/></radialGradient><radialGradient id="iPBOMbc" cx="0" cy="0" r="1" gradientTransform="matrix(.24766 1.90842 -1.09256 .14178 21.78 16.259)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="qr3ucp00l"/><stop offset="1" class="kcgow9b-d"/></radialGradient><radialGradient id="i7LoUyc" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.508 17.256)scale(2.88068)" gradientUnits="userSpaceOnUse"><stop class="p236k5fti"/><stop offset="1" class="g2vlv9bfh"/></radialGradient><radialGradient id="iDPHOne" cx="0" cy="0" r="1" gradientTransform="rotate(142.158 9.182 11.206)scale(1.19705 1.26073)" gradientUnits="userSpaceOnUse"><stop class="s9x1nlbef"/><stop offset="1" class="xo4w8qb_a"/></radialGradient><radialGradient id="icS3o1d" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.433 21.15)scale(2.34213)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="w08_jhbkt"/><stop offset="1" class="etv5nzb3o"/></radialGradient><radialGradient id="iEDGwed" cx="0" cy="0" r="1" gradientTransform="matrix(.69531 0 0 .82031 21.666 14.83)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="gq6390b8n"/><stop offset="1" class="htw9qedrj"/></radialGradient><radialGradient id="isCKzRR" cx="0" cy="0" r="1" gradientTransform="rotate(174.491 9.403 8.468)scale(6.18482 6.87814)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="xrik-2bjb"/><stop offset="1" class="x6-sayl6h"/></radialGradient><radialGradient id="iBkJved" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.85156 -11.5834 0 16 12.151)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="o--r6h20j"/><stop offset=".99" class="fsq5r5bbx"/></radialGradient><radialGradient id="i2VPMbe" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 14.187)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="q_zq8lcfj"/><stop offset=".902" class="ru61jfres"/></radialGradient><radialGradient id="i4hQP9i" cx="0" cy="0" r="1" gradientTransform="matrix(.87207 1.75 -1.15013 .57314 11.06 9.714)" gradientUnits="userSpaceOnUse"><stop class="f7m1yfx-m"/><stop offset="1" class="p3lw01bbh"/></radialGradient><radialGradient id="iMYoVKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="tf917uigd"/><stop offset="1" class="e974r34pq"/></radialGradient><radialGradient id="i4z16cc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="tf917uigd"/><stop offset="1" class="e974r34pq"/></radialGradient><radialGradient id="iG0A0We" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 17.003)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="w0_gpw3io"/><stop offset="1" class="kf-afnfjo"/></radialGradient><radialGradient id="i8bTAHb" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.541 16.204)" gradientUnits="userSpaceOnUse"><stop class="cbh83mbyh"/><stop offset="1" class="hnph1r6ss"/></radialGradient><radialGradient id="iCx5xKe" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 -.39062 1.75486 .91253 14.92 18.59)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="chi8d6bxi"/><stop offset="1" class="y34pxebel"/></radialGradient><radialGradient id="i5jqakE" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -2.65625 .92293 1.02066 11.747 6.323)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="ha4j0kkdn"/><stop offset="1" class="qrqshhbsh"/></radialGradient><radialGradient id="iilVhed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 -2.11178 1.39023 -1.15206 20.013 6.964)" gradientUnits="userSpaceOnUse"><stop class="qia949zox"/><stop offset="1" class="i1e9hkboc"/></radialGradient><radialGradient id="iIJbX6d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69202 -.32813 .16397 -.8455 15.983 6.689)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="d6r-hbcax"/><stop offset="1" class="mdoiiwbdb"/></radialGradient><radialGradient id="iOlfHTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.79689 -2.51562 5.42206 -1.71758 13.669 8.23)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="cv-wl2ybc"/><stop offset=".853" class="zh07rnl4z"/></radialGradient><radialGradient id="iwEQgOd" cx="0" cy="0" r="1" gradientTransform="rotate(32.574 -4.662 35.8)scale(2.67 1.26933)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="jfx6ofbzo"/><stop offset="1" class="bll6ppbfc"/></radialGradient><radialGradient id="igxBKIS" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8291 2.17918 -1.87822 -2.4384 19.396 6.561)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="d8myuzbhd"/><stop offset="1" class="jb4y4y-he"/></radialGradient><radialGradient id="i3gR8Ph" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79686 -2.67189 1.32522 -.89122 11.81 10.683)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="l25dhacin"/><stop offset="1" class="o0smz_bvt"/></radialGradient><radialGradient id="i6ADrgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.518 1.879)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><radialGradient id="i44UlBb" cx="0" cy="0" r="1" gradientTransform="matrix(5.8706 -6.28124 5.4446 5.08866 18.265 9.83)" gradientUnits="userSpaceOnUse"><stop class="txpy_zznj"/><stop offset="1" class="vfm0_vraw"/><stop offset="1" class="l5m7qflal"/></radialGradient><radialGradient id="iCOQPMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 11.01 6.36)" gradientUnits="userSpaceOnUse"><stop class="l714dnucg"/><stop offset="1" class="mzzxgdkuh"/></radialGradient><radialGradient id="ioIUsuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.313 9.84)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="qhhfhnb7p"/><stop offset="1" class="c0ejuub7c"/></radialGradient><filter id="ipbRBxd" width="21.451" height="8.965" x="5.649" y="21.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.262745 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24259"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.380392 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24259" result="effect2_innerShadow_3987_24259"/></filter><filter id="iJOIF8d" width="2.256" height="3.995" x="9.377" y="15.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.207843 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24259"/></filter><filter id="iuhMiOS" width="2.986" height="2.986" x="9.111" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".1"/></filter><filter id="iFBJhBd" width="2.986" height="2.986" x="19.904" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".1"/></filter><filter id="iNsb9tb" width="12.252" height="14.898" x="10.124" y="7.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.380392 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24259"/></filter><filter id="iZlmHrc" width="3.829" height="3.829" x="11.609" y="11.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".25"/></filter><filter id="is5aJni" width="7.729" height="10.962" x="15.437" y="4.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".5"/></filter><filter id="iD7DZsJ" width="7.108" height="9.773" x="8.377" y="5.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".5"/></filter><filter id="iPQSURd" width="2.699" height="1.214" x="11.797" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24259"/></filter><filter id="i4BtrHs" width="2.399" height=".914" x="11.847" y="12.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".075"/></filter><filter id="inrDCzb" width="2.699" height="1.214" x="17.703" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24259"/></filter><filter id="ifxbhmd" width="2.399" height=".914" x="17.753" y="12.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".075"/></filter><filter id="i483cKd" width="2.618" height=".92" x="12.269" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".075"/></filter><filter id="ijY3hwb" width="2.618" height=".92" x="17.16" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".075"/></filter><filter id="ienoI5b" width="3.122" height="4.211" x="14.162" y="13.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".25"/></filter><filter id="imUg1xe" width="4.199" height="1.729" x="13.906" y="17.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".05"/></filter><filter id="ibanyhd" width="10.047" height="6.351" x="11.473" y="4.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.0313726 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24259"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.231373 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24259" result="effect2_innerShadow_3987_24259"/></filter><filter id="i5oqQXd" width="4.387" height="2.271" x="11.746" y="5.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".075"/></filter><filter id="inUgFyd" width="4.219" height="4.689" x="15.869" y="5.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".125"/></filter><filter id="i7P718c" width="6.686" height="12.903" x="8.599" y="1.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.27451 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24259"/></filter><filter id="iX8wppd" width="6.436" height="12.953" x="17.239" y="1.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24259"/></filter><filter id="islk0Tc" width="6.436" height="12.953" x="17.239" y="1.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.227451 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24259"/></filter><filter id="iv8gZod" width="5.843" height="12.292" x="17.83" y="2.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".25"/></filter><filter id="iOZSZxc" width="2.811" height="6.368" x="8.719" y="8.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".375"/></filter><filter id="i1TycOn" width="5.14" height="8.355" x="9.673" y="1.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24259" stdDeviation=".25"/></filter><linearGradient id="imT7ZYd" x1="14.021" x2="11.81" y1="12.289" y2="12.753" gradientUnits="userSpaceOnUse"><stop class="c-eczdzuc"/><stop offset="1" class="gwgqzlb4u"/></linearGradient><linearGradient id="i2PbjGe" x1="17.979" x2="20.19" y1="12.234" y2="12.698" gradientUnits="userSpaceOnUse"><stop class="c-eczdzuc"/><stop offset="1" class="gwgqzlb4u"/></linearGradient><linearGradient id="ioJoXBd" x1="14.936" x2="12.494" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="m97csacbr"/><stop offset=".32" class="ppgoehb9j"/><stop offset=".794" class="ppgoehb9j"/><stop offset="1" class="hxk020qex"/></linearGradient><linearGradient id="icIOaAd" x1="19.826" x2="17.385" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="m97csacbr"/><stop offset=".32" class="ppgoehb9j"/><stop offset=".794" class="ppgoehb9j"/><stop offset="1" class="hxk020qex"/></linearGradient><linearGradient id="imTmQon" x1="16.885" x2="15.848" y1="15.735" y2="15.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="gt5mw9brj"/><stop offset="1" class="wmgou6bmf"/></linearGradient><linearGradient id="iDXEPWd" x1="10.124" x2="10.124" y1="13.342" y2="8.511" gradientUnits="userSpaceOnUse"><stop class="n7gad4bzu"/><stop offset="1" class="ejsfj0d0t"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-getting-massage-medium-dark" /></template>
<style>
.ajvihphfe {
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.am_6_g2wh {
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.b6za14b0m {
  fill: var(--svg-color--76434f, #76434F);
  d: path("M15.872 13.956c-.163 0-.248.093-.297.254l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.16-.045-.254-.209-.254");
}

.bll6ppbfc {
  stop-color: var(--svg-color--433439, #433439);
  stop-opacity: 0;
}

.bnga0rw3i {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.578c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.056.243.013.25.135a.15.15 0 0 1-.014.077c-.76 1.47-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.122.142-.192.25-.135Z");
}

.c-eczdzuc {
  stop-color: var(--svg-color--453a3a, #453A3A);
}

.c0ejuub7c {
  stop-color: var(--svg-color--9a7b72, #9A7B72);
  stop-opacity: 0;
}

.cbh83mbyh {
  stop-color: var(--svg-color--97736e, #97736E);
}

.chi8d6bxi {
  stop-color: var(--svg-color--886667, #886667);
}

.cv-wl2ybc {
  stop-color: var(--svg-color--3f3739, #3F3739);
  stop-opacity: 0;
}

.d6r-hbcax {
  stop-color: var(--svg-color--3f2e34, #3F2E34);
}

.d8myuzbhd {
  stop-color: var(--svg-color--210b1d, #210B1D);
  stop-opacity: 0;
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

.e4qmmebvg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.e974r34pq {
  stop-color: var(--svg-color--392c2b, #392C2B);
}

.eaevyhbaf {
  fill: var(--svg-color--512e2f, #512E2F);
  d: path("M22.166 7.572h-3.173V5.768c0 .352-.21 1.035-.633 1.43a76 76 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.714c.42.429 1.01.362 1.44-.054l.905-.74a.464.464 0 0 1 .692.043c.08.097.123.221.123.35v3.327c0 .663.497 1.2 1.11 1.2s1.111-.537 1.111-1.2z");
}

.eh43pve_h {
  d: path("m9.469 9.256l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.ejsfj0d0t {
  stop-color: var(--svg-color--886361, #886361);
  stop-opacity: 0;
}

.etv5nzb3o {
  stop-color: var(--svg-color--7e4950, #7E4950);
}

.f7m1yfx-m {
  stop-color: var(--svg-color--9b4607, #9B4607);
}

.fgf4_ac8o {
  d: path("M10.173 5.384v-2.9h1.469V6.02a1 1 0 0 0 .28.693l2.262 2.349a.46.46 0 0 1-.636.663L11.184 7.63a3 3 0 0 1-1.011-2.246");
}

.fsq5r5bbx {
  stop-color: var(--svg-color--833945, #833945);
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

.g2vlv9bfh {
  stop-color: var(--svg-color--653747, #653747);
}

.g3cj9mbqt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.g5_ia9syq {
  d: path("M22.623 15.636h-2.207v3.894c.934.024 1.977-.949 2.121-2.277z");
}

.gq6390b8n {
  stop-color: var(--svg-color--815f57, #815F57);
}

.gt5mw9brj {
  stop-color: var(--svg-color--98746c, #98746C);
}

.gwgqzlb4u {
  stop-color: var(--svg-color--453a3a, #453A3A);
  stop-opacity: 0;
}

.h26e4sgsm {
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.ha4j0kkdn {
  stop-color: var(--svg-color--383031, #383031);
}

.hnph1r6ss {
  stop-color: var(--svg-color--97736e, #97736E);
  stop-opacity: 0;
}

.htw-10p4r {
  fill: var(--svg-color--ffb62d, #FFB62D);
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.htw9qedrj {
  stop-color: var(--svg-color--7d5047, #7D5047);
}

.hxk020qex {
  stop-color: var(--svg-color--3d3133, #3D3133);
}

.i1e9hkboc {
  stop-color: var(--svg-color--302b2d, #302B2D);
  stop-opacity: 0;
}

.i7fnn1bcq {
  cx: 10.604px;
  cy: 14.61px;
  r: 1.979px;
}

.ic-dvmxoa {
  d: path("M9.377 6.692h2.83v.372c0 .29.186.855.564 1.181c.31.287.904.875 1.426 1.397a.987.987 0 0 1-.022 1.416c-.374.354-.898.299-1.282-.045l-.81-.61a.435.435 0 0 0-.725.323v2.748a.99.99 0 0 1-1.981 0z");
}

.j0j5vybko {
  cx: 13.524px;
  cy: 13.487px;
  r: 1.415px;
}

.jb4y4y-he {
  stop-color: var(--svg-color--210b1d, #210B1D);
}

.jfx6ofbzo {
  stop-color: var(--svg-color--433439, #433439);
}

.jvs9aeb5c {
  d: path("m21.12 8.376l-2.021 1.488c-.245.18-.471.42-.677.196c-.22-.238-.007-.337.229-.559a52 52 0 0 1 1.99-1.786c.875-.734.85-2.108.828-2.57V2.568h1.704V13.28a.579.579 0 0 1-1.157 0V9.044c0-.403-.572-.907-.896-.668");
}

.jxphwjdmk {
  fill: var(--svg-color--3c1b1c, #3C1B1C);
  d: path("M9.377 6.692h2.83v.372c0 .29.186.855.564 1.181c.31.287.904.875 1.426 1.397a.987.987 0 0 1-.022 1.416c-.374.354-.898.299-1.282-.045l-.81-.61a.435.435 0 0 0-.725.323v2.748a.99.99 0 0 1-1.981 0z");
}

.jydgsvcms {
  cx: 10.604px;
  cy: 14.61px;
  r: 1.293px;
  fill: var(--svg-color--593138, #593138);
}

.kcgow9b-d {
  stop-color: var(--svg-color--231925, #231925);
}

.kf-afnfjo {
  stop-color: var(--svg-color--7e4757, #7E4757);
  stop-opacity: 0;
}

.kkqz5eb_f {
  d: path("M12.88 6.098a4.6 4.6 0 0 0-.984.547l.261 1.119l2.828.037a.986.986 0 1 0 .013-1.972h-.646c-.277 0-.96.054-1.472.27");
}

.l25dhacin {
  stop-color: var(--svg-color--673742, #673742);
}

.l5m7qflal {
  stop-color: var(--svg-color--906f68, #906F68);
  stop-opacity: 0;
}

.l714dnucg {
  stop-color: var(--svg-color--a07e73, #A07E73);
}

.ld2mc9kvg {
  stroke: var(--svg-color--322221, #322221);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.928 12.753c-.258-.207-.883-.578-1.95-.43");
}

.lln5h90we {
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

.m97csacbr {
  stop-color: var(--svg-color--44393a, #44393A);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mdoiiwbdb {
  stop-color: var(--svg-color--3f2e34, #3F2E34);
  stop-opacity: 0;
}

.mzzxgdkuh {
  stop-color: var(--svg-color--a07e73, #A07E73);
  stop-opacity: 0;
}

.n7gad4bzu {
  stop-color: var(--svg-color--886361, #886361);
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

.noy15ebni {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M14.357 17.578c.344.18.879.384 1.649.384s1.304-.204 1.648-.384c.108-.056.243.013.25.135a.15.15 0 0 1-.014.077c-.76 1.47-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.122.142-.192.25-.135");
}

.o--r6h20j {
  stop-color: var(--svg-color--784255, #784255);
  stop-opacity: 0;
}

.o0smz_bvt {
  stop-color: var(--svg-color--754d4c, #754D4C);
  stop-opacity: 0;
}

.o1ei7wb2z {
  fill: var(--svg-color--824f50, #824F50);
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.p236k5fti {
  stop-color: var(--svg-color--643e41, #643E41);
}

.p3lw01bbh {
  stop-color: var(--svg-color--d97513, #D97513);
}

.p3p0m3wfz {
  fill: var(--svg-color--764e49, #764E49);
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.ppgoehb9j {
  stop-color: var(--svg-color--3b2e30, #3B2E30);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.q_zq8lcfj {
  stop-color: var(--svg-color--724b4a, #724B4A);
}

.qhhfhnb7p {
  stop-color: var(--svg-color--9a7b72, #9A7B72);
}

.qia949zox {
  stop-color: var(--svg-color--302b2d, #302B2D);
}

.qmod-43sl {
  stop-color: var(--svg-color--ff7645, #FF7645);
  stop-opacity: 0;
}

.qr3ucp00l {
  stop-color: var(--svg-color--353132, #353132);
}

.qrqshhbsh {
  stop-color: var(--svg-color--383031, #383031);
  stop-opacity: 0;
}

.ru61jfres {
  stop-color: var(--svg-color--6c3e49, #6C3E49);
}

.rzvl5tbzx {
  stop-color: var(--svg-color--6e3737, #6E3737);
}

.s9x1nlbef {
  stop-color: var(--svg-color--93736a, #93736A);
}

.sq9m-fbvs {
  fill: var(--svg-color--7e554d, #7E554D);
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

.srcdcl_yh {
  cx: 21.396px;
  cy: 14.61px;
  r: 1.979px;
}

.tf917uigd {
  stop-color: var(--svg-color--2f182c, #2F182C);
}

.txpy_zznj {
  stop-color: var(--svg-color--906f68, #906F68);
}

.vfm0_vraw {
  stop-color: var(--svg-color--675553, #675553);
  stop-opacity: 0;
}

.vj1esr5wb {
  fill: var(--svg-color--221b1d, #221B1D);
  d: path("M9.377 15.636h2.156v3.894c-.933.024-2.035-1.054-2.105-2.27z");
}

.vnuk5ibgy {
  stop-color: var(--svg-color--9a6c63, #9A6C63);
  stop-opacity: 0;
}

.vonrxsbes {
  stop-color: var(--svg-color--6e3737, #6E3737);
  stop-opacity: 0;
}

.w0_gpw3io {
  stop-color: var(--svg-color--7e4757, #7E4757);
}

.w08_jhbkt {
  stop-color: var(--svg-color--7e4950, #7E4950);
  stop-opacity: 0;
}

.w5a3tprnu {
  d: path("M8.599 2.026h3.425v3.742c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.879.393v3.327a1.2 1.2 0 0 1-2.398 0z");
}

.wkqd0hb4b {
  d: path("m10.127 10.745l.203 6.485c.233 3.376 2.209 4.755 5.637 4.773h.066c3.428-.018 5.404-1.397 5.637-4.773l.203-6.485c.069-2.2-1.117-3.344-1.719-3.64h-8.308c-.602.296-1.788 1.44-1.72 3.64");
}

.wmgou6bmf {
  stop-color: var(--svg-color--98746c, #98746C);
  stop-opacity: 0;
}

.wv6byccxz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.494 14.23c.146.164.536.45 1.024.468c.617.024.949-.304 1.144-.469");
}

.wzapgli4e {
  stop-color: var(--svg-color--9a6c63, #9A6C63);
}

.x1cyw_brl {
  fill: var(--svg-color--845a56, #845A56);
  d: path("M8.599 2.026h3.425v3.742c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.879.393v3.327a1.2 1.2 0 0 1-2.398 0z");
}

.x6-sayl6h {
  stop-color: var(--svg-color--734c49, #734C49);
}

.xjyo8kbbd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 14.23c.146.164.536.45 1.024.468c.617.024.949-.304 1.144-.469");
}

.xo4w8qb_a {
  stop-color: var(--svg-color--815457, #815457);
}

.xrik-2bjb {
  stop-color: var(--svg-color--93655a, #93655A);
}

.y34pxebel {
  stop-color: var(--svg-color--886667, #886667);
  stop-opacity: 0;
}

.yu799baro {
  stop-color: var(--svg-color--ff5026, #FF5026);
}

.z2o3d6bto {
  fill: var(--svg-color--36262b, #36262B);
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.ze6s0wf9k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.072 12.753c.258-.207.883-.578 1.95-.43");
}

.zh07rnl4z {
  stop-color: var(--svg-color--3f3739, #3F3739);
}

.zl8nqy82h {
  stop-color: var(--svg-color--ff641f, #FF641F);
}

</style>
