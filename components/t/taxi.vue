<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ix3tpIJ)"><rect fill="url(#ihXLNWb)" class="d6qqw7ohr"/><rect fill="url(#iStdYKb)" class="d6qqw7ohr"/></g><g clip-rule="evenodd" filter="url(#iW8gErd)" class="d2kvgvbvc"><path fill="url(#it0Exvd)" class="uz8ligbrq"/><path fill="url(#iV7oove)" class="uz8ligbrq"/><path fill="url(#ipSlTsb)" class="uz8ligbrq"/><path fill="url(#iP1m3Qc)" class="uz8ligbrq"/></g><g filter="url(#ivCbM4q)"><path fill="url(#iWcr2bd)" class="caz3bds6s"/></g><path fill="url(#i3eLQNc)" class="caz3bds6s"/><path fill="url(#iWOUu7c)" class="caz3bds6s"/><path fill="url(#iech5me)" class="caz3bds6s"/><path fill="url(#itMIf6J)" class="caz3bds6s"/><g filter="url(#i63FoCe)"><path fill="url(#i0JzvAe)" class="nzs03_50f"/></g><g filter="url(#i2sIG1c)"><path fill="url(#iWoRkOU)" class="j05xa2bdh"/><path fill="url(#iGTMmWb)" class="j05xa2bdh"/></g><path fill="url(#i535tVd)" class="emdoenbei"/><path fill="url(#ifvohzd)" class="emdoenbei"/><path fill="url(#iE5eTld)" class="emdoenbei"/><path fill="url(#ipj5Zgd)" class="emdoenbei"/><path fill="url(#iwrrtbb)" class="emdoenbei"/><g filter="url(#ig5Fgpc)"><path stroke="url(#iszDnKc)" class="a3h4jabew"/></g><path fill="url(#iGJjtid)" class="pk1ukgb1q"/><g filter="url(#iDPjXnc)"><path stroke="url(#ic1h08G)" class="l8c-fooov"/></g><path fill="url(#iNr0ihe)" class="h2rmsrbsa"/><path fill="url(#iPWbITd)" class="h2rmsrbsa"/><path fill="url(#i9AbWUK)" class="guoti1bay"/><path fill="url(#ivY826d)" class="j68d9kbwi"/><path fill="url(#i0Yw8Ne)" class="hr0jyt81l"/><path fill="url(#iPJie1b)" class="gekmebblb"/><path fill="url(#ivXDXGc)" class="r8du6ccms"/><g filter="url(#igDvjfc)"><path fill="url(#iok7sRd)" class="h3r5v41cx"/><path fill="url(#iOFOt3c)" class="h3r5v41cx"/><path fill="url(#i8NhANe)" class="h3r5v41cx"/></g><path fill="url(#itK8Kgb)" class="mx9mq5jnx"/><path fill="url(#icYZYEc)" class="mwtz9m15l"/><g filter="url(#iH59ssd)"><circle fill="url(#iAjhMAc)" class="n142q1bxn"/><circle fill="url(#iH1WOLb)" class="n142q1bxn"/></g><g filter="url(#ikmEsGc)"><circle stroke="url(#iXma2gb)" class="uhe7_acfg"/></g><g filter="url(#iAVq2eb)"><circle fill="url(#iBGzUde)" class="ev8pnfo0u"/><circle fill="url(#iT7sLmc)" class="ev8pnfo0u"/></g><g filter="url(#ifE2ICd)"><circle stroke="url(#iwpfKMc)" class="iuam53brq"/></g><g filter="url(#i07nrEa)"><circle fill="url(#iLTiJly)" class="kzwjmibmq"/></g><g filter="url(#iyYswwc)"><circle fill="url(#iM5Azqd)" class="rm4wh252o"/></g><defs><linearGradient id="it0Exvd" x1="10.788" x2="24.873" y1="14.122" y2="14.122" gradientUnits="userSpaceOnUse"><stop class="g5v8gmb6k"/><stop offset="1" class="vk0fhzb9x"/></linearGradient><linearGradient id="iV7oove" x1="16.186" x2="16.186" y1="16.76" y2="12.51" gradientUnits="userSpaceOnUse"><stop class="c6ha1jl1d"/><stop offset="1" class="dvwxdb4wa"/></linearGradient><linearGradient id="ipSlTsb" x1="9.28" x2="10.936" y1="12.26" y2="13.041" gradientUnits="userSpaceOnUse"><stop class="ldblncbdo"/><stop offset="1" class="h-jdrlo9u"/></linearGradient><linearGradient id="iWcr2bd" x1="6.436" x2="30.083" y1="22.604" y2="22.604" gradientUnits="userSpaceOnUse"><stop class="chm8iebuj"/><stop offset="1" class="wvodo6bvj"/></linearGradient><linearGradient id="i3eLQNc" x1="16.025" x2="16.025" y1="26.531" y2="23.77" gradientUnits="userSpaceOnUse"><stop class="zsep25b2r"/><stop offset="1" class="obzdtjl6h"/></linearGradient><linearGradient id="iWOUu7c" x1="16.025" x2="16.025" y1="26.697" y2="25.822" gradientUnits="userSpaceOnUse"><stop class="aa1b7achm"/><stop offset="1" class="hs-71fzrv"/></linearGradient><linearGradient id="iech5me" x1="30.878" x2="29.494" y1="21.805" y2="21.805" gradientUnits="userSpaceOnUse"><stop class="uz06qkaet"/><stop offset="1" class="ns343lbbd"/></linearGradient><linearGradient id="itMIf6J" x1="1.495" x2="3.025" y1="22.97" y2="22.97" gradientUnits="userSpaceOnUse"><stop class="ntqink_qa"/><stop offset="1" class="pqyrtn_yc"/></linearGradient><linearGradient id="i0JzvAe" x1="11.214" x2="10.136" y1="17.799" y2="16.02" gradientUnits="userSpaceOnUse"><stop class="dowx9xbkh"/><stop offset=".636" class="cxqs74b7b"/><stop offset="1" class="ufzr5-bsh"/></linearGradient><linearGradient id="iWoRkOU" x1="14.967" x2="9.467" y1="15.041" y2="15.041" gradientUnits="userSpaceOnUse"><stop class="q8f8azvyx"/><stop offset="1" class="sa790kbor"/></linearGradient><linearGradient id="iGTMmWb" x1="8.748" x2="9.002" y1="13.885" y2="13.998" gradientUnits="userSpaceOnUse"><stop class="zx1--obkc"/><stop offset="1" class="m2rwxe8dt"/></linearGradient><linearGradient id="ifvohzd" x1="17.983" x2="18.337" y1="14.389" y2="14.389" gradientUnits="userSpaceOnUse"><stop class="w-hk21gox"/><stop offset="1" class="yd1z-jb2p"/></linearGradient><linearGradient id="iE5eTld" x1="22.82" x2="22.82" y1="11.807" y2="12.722" gradientUnits="userSpaceOnUse"><stop class="m72duqiee"/><stop offset="1" class="fv592s5_s"/></linearGradient><linearGradient id="iwrrtbb" x1="26.426" x2="26.28" y1="14.453" y2="14.533" gradientUnits="userSpaceOnUse"><stop offset=".169" class="q2mh2kbci"/><stop offset="1" class="t_b9qwb7n"/></linearGradient><linearGradient id="iszDnKc" x1="28.956" x2="28.956" y1="20.463" y2="23.471" gradientUnits="userSpaceOnUse"><stop class="fhzpv-mvk"/><stop offset="1" class="f_t306eyj"/></linearGradient><linearGradient id="iGJjtid" x1="28.842" x2="30.483" y1="20.385" y2="23.322" gradientUnits="userSpaceOnUse"><stop offset=".12" class="cdlninz0v"/><stop offset=".395" class="jqm2m0g5d"/><stop offset="1" class="nrezhjbtc"/></linearGradient><linearGradient id="ic1h08G" x1="3.139" x2="3.139" y1="20.538" y2="23.523" gradientUnits="userSpaceOnUse"><stop class="t6g9ypz_r"/><stop offset="1" class="bx03s09vw"/></linearGradient><linearGradient id="iPWbITd" x1="4.373" x2="3.514" y1="22.882" y2="22.882" gradientUnits="userSpaceOnUse"><stop class="csh5l3bai"/><stop offset="1" class="letre7vta"/></linearGradient><linearGradient id="i9AbWUK" x1="12.037" x2="14.06" y1="19.64" y2="19.64" gradientUnits="userSpaceOnUse"><stop class="hmll_rygi"/><stop offset="1" class="h96weobev"/></linearGradient><linearGradient id="ivY826d" x1="14.06" x2="16.082" y1="21.662" y2="21.662" gradientUnits="userSpaceOnUse"><stop class="hmll_rygi"/><stop offset="1" class="h96weobev"/></linearGradient><linearGradient id="i0Yw8Ne" x1="16.082" x2="18.105" y1="19.64" y2="19.64" gradientUnits="userSpaceOnUse"><stop class="hmll_rygi"/><stop offset="1" class="h96weobev"/></linearGradient><linearGradient id="iPJie1b" x1="18.105" x2="20.127" y1="21.662" y2="21.662" gradientUnits="userSpaceOnUse"><stop class="hmll_rygi"/><stop offset="1" class="h96weobev"/></linearGradient><linearGradient id="ivXDXGc" x1="20.127" x2="22.149" y1="19.64" y2="19.64" gradientUnits="userSpaceOnUse"><stop class="hmll_rygi"/><stop offset="1" class="h96weobev"/></linearGradient><linearGradient id="itK8Kgb" x1="10.23" x2="8.949" y1="22.03" y2="26.041" gradientUnits="userSpaceOnUse"><stop class="p2r1x6qln"/><stop offset="1" class="s_5fhi_lm"/></linearGradient><linearGradient id="icYZYEc" x1="25.248" x2="23.967" y1="22.03" y2="26.041" gradientUnits="userSpaceOnUse"><stop class="p2r1x6qln"/><stop offset="1" class="s_5fhi_lm"/></linearGradient><linearGradient id="iAjhMAc" x1="6.958" x2="12.172" y1="25.066" y2="25.066" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="iXma2gb" x1="11.271" x2="6.916" y1="24.781" y2="27.627" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="iBGzUde" x1="21.977" x2="27.19" y1="25.066" y2="25.066" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="iwpfKMc" x1="26.287" x2="21.932" y1="24.781" y2="27.627" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="iLTiJly" x1="9.839" x2="7.873" y1="24.854" y2="27.01" gradientUnits="userSpaceOnUse"><stop class="hlclzrbkp"/><stop offset="1" class="rz8ze_bgv"/></linearGradient><linearGradient id="iM5Azqd" x1="24.858" x2="22.892" y1="24.854" y2="27.01" gradientUnits="userSpaceOnUse"><stop class="hlclzrbkp"/><stop offset="1" class="rz8ze_bgv"/></linearGradient><filter id="ix3tpIJ" width="2.559" height="3.531" x="15.897" y="8.213" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.517647 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10420"/></filter><filter id="iW8gErd" width="20.057" height="6.078" x="7.6" y="10.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.729412 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10420"/></filter><filter id="ivCbM4q" width="28.616" height="11.073" x="1.967" y="16.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.611765 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10420"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.831373 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10420" result="effect2_innerShadow_18_10420"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.74902 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_10420" result="effect3_innerShadow_18_10420"/></filter><filter id="i63FoCe" width="2.88" height="3.721" x="9.189" y="14.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10420" stdDeviation=".15"/></filter><filter id="i2sIG1c" width="8.842" height="5.1" x="7.157" y="11.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".65"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.521569 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10420"/></filter><filter id="ig5Fgpc" width="2.547" height="3.608" x="27.682" y="20.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10420" stdDeviation=".1"/></filter><filter id="iDPjXnc" width="2.537" height="3.584" x="1.87" y="20.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10420" stdDeviation=".1"/></filter><filter id="igDvjfc" width="2.273" height="3.369" x="9.959" y="14.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.666667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10420"/></filter><filter id="iH59ssd" width="6.942" height="7.092" x="5.088" y="22.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10420"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10420" result="effect2_innerShadow_18_10420"/></filter><filter id="ikmEsGc" width="7.162" height="7.162" x="5.167" y="22.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10420" stdDeviation=".375"/></filter><filter id="iAVq2eb" width="6.942" height="7.092" x="20.106" y="22.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10420"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10420" result="effect2_innerShadow_18_10420"/></filter><filter id="ifE2ICd" width="7.162" height="7.162" x="20.183" y="22.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10420" stdDeviation=".375"/></filter><filter id="i07nrEa" width="2.661" height="2.661" x="7.228" y="24.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10420"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10420" result="effect2_innerShadow_18_10420"/></filter><filter id="iyYswwc" width="2.661" height="2.661" x="22.247" y="24.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10420"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10420" result="effect2_innerShadow_18_10420"/></filter><radialGradient id="ihXLNWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.24381 1.87732 0 17.365 10.663)" gradientUnits="userSpaceOnUse"><stop class="p9qonvqll"/><stop offset="1" class="ydczmrbpu"/></radialGradient><radialGradient id="iStdYKb" cx="0" cy="0" r="1" gradientTransform="rotate(117.326 6.297 9.463)scale(1.46686 1.28426)" gradientUnits="userSpaceOnUse"><stop offset=".409" class="gpczbwcmw"/><stop offset="1" class="vvco1vb9y"/></radialGradient><radialGradient id="iP1m3Qc" cx="0" cy="0" r="1" gradientTransform="matrix(-.97665 -1.25362 .86935 -.67729 24.379 12.138)" gradientUnits="userSpaceOnUse"><stop class="cgfit_qis"/><stop offset="1" class="ythc_wbkt"/></radialGradient><radialGradient id="i535tVd" cx="0" cy="0" r="1" gradientTransform="matrix(4.51565 -3.31246 3.77027 5.13974 17.982 16.79)" gradientUnits="userSpaceOnUse"><stop class="ribc63b7d"/><stop offset="1" class="vch70cblv"/></radialGradient><radialGradient id="ipj5Zgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73684 1.81003 -.64263 -.61665 25.986 11.807)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="n_k4nlcam"/><stop offset="1" class="zvk11ibix"/></radialGradient><radialGradient id="iNr0ihe" cx="0" cy="0" r="1" gradientTransform="matrix(2.49612 0 0 1.79052 2.315 22.8)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="s3ls9qadv"/></radialGradient><radialGradient id="iok7sRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0182 2.40303 -.73727 -.00558 11.708 15.36)" gradientUnits="userSpaceOnUse"><stop class="duq_qz3-z"/><stop offset=".658" class="i0ab5xypk"/></radialGradient><radialGradient id="iOFOt3c" cx="0" cy="0" r="1" gradientTransform="rotate(-118.426 11.151 5.487)scale(1.86284 2.03358)" gradientUnits="userSpaceOnUse"><stop class="aa2zsmbjk"/><stop offset="1" class="wgr8b5bue"/></radialGradient><radialGradient id="i8NhANe" cx="0" cy="0" r="1" gradientTransform="matrix(-.8567 2.28452 -2.1838 -.81892 12.07 14.389)" gradientUnits="userSpaceOnUse"><stop class="wdbakcbkt"/><stop offset="1" class="q_vo4mxru"/></radialGradient><radialGradient id="iH1WOLb" cx="0" cy="0" r="1" gradientTransform="matrix(.78426 -1.72385 1.8005 .81913 8.559 25.628)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="iT7sLmc" cx="0" cy="0" r="1" gradientTransform="matrix(.78426 -1.72385 1.8005 .81913 23.577 25.63)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:taxi" /></template>
<style>
.a2peghb2c {
  stop-color: var(--svg-color--2b1249, #2B1249);
  stop-opacity: 0;
}

.a3h4jabew {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M29.93 20.463v3.008h-.565c-.764 0-1.383-.68-1.383-1.504s.62-1.504 1.383-1.504z");
}

.aa1b7achm {
  stop-color: var(--svg-color--c76194, #C76194);
}

.aa2zsmbjk {
  stop-color: var(--svg-color--eb9948, #EB9948);
}

.ariye-f8h {
  stop-color: var(--svg-color--2d114d, #2D114D);
}

.baem9ki2q {
  stop-color: var(--svg-color--34214f, #34214F);
}

.bx03s09vw {
  stop-color: var(--svg-color--f5ba41, #F5BA41);
}

.c6ha1jl1d {
  stop-color: var(--svg-color--ffde4b, #FFDE4B);
}

.caz3bds6s {
  d: path("M7.6 16.307a1 1 0 0 1-.266.137l-3.056 1.034A3.4 3.4 0 0 0 1.967 20.7v3.18a2.5 2.5 0 0 0 2.5 2.5h23.116a2.5 2.5 0 0 0 2.5-2.5v-5.287a2.264 2.264 0 0 0-2.265-2.265a.7.7 0 0 1-.16-.02z");
}

.cdlninz0v {
  stop-color: var(--svg-color--e31c3a, #E31C3A);
}

.cgfit_qis {
  stop-color: var(--svg-color--ffeb7f, #FFEB7F);
}

.chm8iebuj {
  stop-color: var(--svg-color--ffc25a, #FFC25A);
}

.csh5l3bai {
  stop-color: var(--svg-color--e6dbdc, #E6DBDC);
}

.cxqs74b7b {
  stop-color: var(--svg-color--c78c36, #C78C36);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d6qqw7ohr {
  width: 2.359px;
  height: 3.531px;
  x: 15.897px;
  y: 8.213px;
  rx: 1.18px;
}

.dowx9xbkh {
  stop-color: var(--svg-color--d36c10, #D36C10);
}

.duq_qz3-z {
  stop-color: var(--svg-color--ffff7c, #FFFF7C);
}

.dvwxdb4wa {
  stop-color: var(--svg-color--ffde4b, #FFDE4B);
  stop-opacity: 0;
}

.emdoenbei {
  d: path("m24.948 11.807l2.303 4.185a.65.65 0 0 0 .406.315h-8.674a1 1 0 0 1-1-1v-2.5a1 1 0 0 1 1-1z");
}

.ev8pnfo0u {
  cx: 23.577px;
  cy: 25.939px;
  r: 3.471px;
}

.f_t306eyj {
  stop-color: var(--svg-color--ffd85a, #FFD85A);
}

.f0k16nibb {
  stop-color: var(--svg-color--615b6b, #615B6B);
  stop-opacity: 0;
}

.fhzpv-mvk {
  stop-color: var(--svg-color--f2a925, #F2A925);
}

.ft5dv1b6b {
  fill: none;
}

.fv592s5_s {
  stop-color: var(--svg-color--2468da, #2468DA);
  stop-opacity: 0;
}

.g5v8gmb6k {
  stop-color: var(--svg-color--ffda56, #FFDA56);
}

.gekmebblb {
  d: path("M18.105 20.451h2.022v2.022h-2.022z");
}

.gpczbwcmw {
  stop-color: var(--svg-color--ece8ef, #ECE8EF);
}

.guoti1bay {
  d: path("M12.037 18.429h2.022v2.022h-2.022z");
}

.h-jdrlo9u {
  stop-color: var(--svg-color--cea549, #CEA549);
  stop-opacity: 0;
}

.h2rmsrbsa {
  d: path("M1.967 23.523v-2.749q0-.119.008-.236h1.333a.8.8 0 0 1 .8.8v1.385a.8.8 0 0 1-.8.8z");
}

.h3r5v41cx {
  d: path("M9.96 16.052c.002-.271.075-.925.507-1.312c.316-.283.804-.276 1.172-.208c.21.039.344.229.344.438v2.164c0 .21-.135.4-.344.438c-.368.068-.856.075-1.172-.208c-.432-.386-.505-1.04-.508-1.312");
}

.h96weobev {
  stop-color: var(--svg-color--3e2f4f, #3E2F4F);
}

.hlclzrbkp {
  stop-color: var(--svg-color--d2c7de, #D2C7DE);
}

.hmll_rygi {
  stop-color: var(--svg-color--4c336b, #4C336B);
}

.hr0jyt81l {
  d: path("M16.082 18.429h2.022v2.022h-2.022z");
}

.hs-71fzrv {
  stop-color: var(--svg-color--c76194, #C76194);
  stop-opacity: 0;
}

.i0ab5xypk {
  stop-color: var(--svg-color--f6c142, #F6C142);
}

.iuam53brq {
  cx: 23.765px;
  cy: 25.749px;
  r: 2.406px;
  stroke-width: var(--svg-stroke-width--0-85px, 0.85px);
}

.j05xa2bdh {
  d: path("M7.657 16.263a1 1 0 0 0 .295.044h7.046a1 1 0 0 0 1-1v-2.5a1 1 0 0 0-1-1H9.822l-1.901 4.11a1 1 0 0 1-.264.346");
}

.j68d9kbwi {
  d: path("M14.06 20.451h2.022v2.022H14.06z");
}

.jqm2m0g5d {
  stop-color: var(--svg-color--fc4656, #FC4656);
}

.kzwjmibmq {
  cx: 8.559px;
  cy: 25.939px;
  r: 1.281px;
}

.l8c-fooov {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M2.17 23.523v-2.749q0-.119.008-.236h1.206c.4 0 .724.358.724.8v1.385c0 .442-.324.8-.724.8z");
}

.ldblncbdo {
  stop-color: var(--svg-color--cea549, #CEA549);
}

.letre7vta {
  stop-color: var(--svg-color--e6dbdc, #E6DBDC);
  stop-opacity: 0;
}

.m2rwxe8dt {
  stop-color: var(--svg-color--419fdc, #419FDC);
  stop-opacity: 0;
}

.m72duqiee {
  stop-color: var(--svg-color--2468da, #2468DA);
}

.mmwl-dsmc {
  stop-color: var(--svg-color--241337, #241337);
}

.mwtz9m15l {
  d: path("M27.461 26.38h-7.768a3.909 3.909 0 1 1 7.768 0");
}

.mx9mq5jnx {
  d: path("M12.443 26.38H4.675a3.908 3.908 0 1 1 7.768 0");
}

.n_k4nlcam {
  stop-color: var(--svg-color--63c3ff, #63C3FF);
}

.n142q1bxn {
  cx: 8.559px;
  cy: 25.939px;
  r: 3.471px;
}

.nrezhjbtc {
  stop-color: var(--svg-color--ff4c5a, #FF4C5A);
}

.ns343lbbd {
  stop-color: var(--svg-color--b8813e, #B8813E);
  stop-opacity: 0;
}

.ntqink_qa {
  stop-color: var(--svg-color--c49d5a, #C49D5A);
}

.nzs03_50f {
  d: path("M9.49 16.24c-.018-.27.178-.924.579-1.343c.292-.307.78-.338 1.152-.3c.211.023.36.202.377.41l.17 2.157a.43.43 0 0 1-.308.464c-.362.097-.848.142-1.185-.115c-.461-.351-.76-1.003-.784-1.273");
}

.obzdtjl6h {
  stop-color: var(--svg-color--d26261, #D26261);
  stop-opacity: 0;
}

.oeptinb4s {
  stop-color: var(--svg-color--615b6b, #615B6B);
}

.p2r1x6qln {
  stop-color: var(--svg-color--743515, #743515);
}

.p9qonvqll {
  stop-color: var(--svg-color--ecded0, #ECDED0);
}

.pk1ukgb1q {
  d: path("M30.083 20.463v3.008h-.609c-.824 0-1.492-.68-1.492-1.504s.668-1.504 1.492-1.504z");
}

.pqyrtn_yc {
  stop-color: var(--svg-color--c49d5a, #C49D5A);
  stop-opacity: 0;
}

.q_vo4mxru {
  stop-color: var(--svg-color--ffec3f, #FFEC3F);
  stop-opacity: 0;
}

.q2mh2kbci {
  stop-color: var(--svg-color--88dbff, #88DBFF);
}

.q8f8azvyx {
  stop-color: var(--svg-color--6be2ff, #6BE2FF);
}

.r8du6ccms {
  d: path("M20.127 18.429h2.022v2.022h-2.022z");
}

.ribc63b7d {
  stop-color: var(--svg-color--6efdff, #6EFDFF);
}

.rm4wh252o {
  cx: 23.577px;
  cy: 25.939px;
  r: 1.281px;
}

.rz8ze_bgv {
  stop-color: var(--svg-color--d1c7dd, #D1C7DD);
}

.s_5fhi_lm {
  stop-color: var(--svg-color--8a5424, #8A5424);
}

.s3ls9qadv {
  stop-color: var(--svg-color--f0d0f9, #F0D0F9);
}

.sa790kbor {
  stop-color: var(--svg-color--66c8ff, #66C8FF);
}

.t_b9qwb7n {
  stop-color: var(--svg-color--88dbff, #88DBFF);
  stop-opacity: 0;
}

.t6g9ypz_r {
  stop-color: var(--svg-color--e8a04e, #E8A04E);
}

.ufzr5-bsh {
  stop-color: var(--svg-color--c78c36, #C78C36);
  stop-opacity: 0;
}

.uhe7_acfg {
  cx: 8.748px;
  cy: 25.749px;
  r: 2.406px;
  stroke-width: var(--svg-stroke-width--0-85px, 0.85px);
}

.uz06qkaet {
  stop-color: var(--svg-color--b8813e, #B8813E);
}

.uz8ligbrq {
  d: path("M27.658 16.307H7.6a1 1 0 0 0 .32-.39l2.033-4.394a1.8 1.8 0 0 1 1.634-1.044h11.448a2 2 0 0 1 1.752 1.035l2.465 4.478a.65.65 0 0 0 .406.315");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vch70cblv {
  stop-color: var(--svg-color--64c5ff, #64C5FF);
}

.vk0fhzb9x {
  stop-color: var(--svg-color--ffd854, #FFD854);
}

.vvco1vb9y {
  stop-color: var(--svg-color--ece8ef, #ECE8EF);
  stop-opacity: 0;
}

.w-hk21gox {
  stop-color: var(--svg-color--82f4ff, #82F4FF);
}

.wdbakcbkt {
  stop-color: var(--svg-color--ffec3f, #FFEC3F);
}

.wgr8b5bue {
  stop-color: var(--svg-color--eb9948, #EB9948);
  stop-opacity: 0;
}

.wvodo6bvj {
  stop-color: var(--svg-color--ffbe59, #FFBE59);
}

.yd1z-jb2p {
  stop-color: var(--svg-color--82f4ff, #82F4FF);
  stop-opacity: 0;
}

.ydczmrbpu {
  stop-color: var(--svg-color--c7becb, #C7BECB);
}

.ythc_wbkt {
  stop-color: var(--svg-color--ffeb7f, #FFEB7F);
  stop-opacity: 0;
}

.zsep25b2r {
  stop-color: var(--svg-color--d26261, #D26261);
}

.zvk11ibix {
  stop-color: var(--svg-color--63c3ff, #63C3FF);
  stop-opacity: 0;
}

.zx1--obkc {
  stop-color: var(--svg-color--419fdc, #419FDC);
}

</style>
