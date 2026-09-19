<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#irqDdYc)"><path fill="url(#ieXZqTd)" class="x9v96ly8v"/><path fill="url(#ipgr2Nv)" class="x9v96ly8v"/></g><path fill="url(#i65lb5l)" class="x9v96ly8v"/><path fill="url(#iVhm3mh)" class="zq9lh2bgc"/><path fill="url(#isdIZOe)" class="zq9lh2bgc"/><path fill="url(#isXv3Fc)" class="zq9lh2bgc"/><path fill="url(#iym4Rxb)" class="cnsxe7brl"/><path fill="url(#iXN7FQc)" class="cnsxe7brl"/><path fill="url(#ibjP0fd)" class="nz6bv55fi"/><g filter="url(#iHcDQmN)"><path fill="url(#iP1Vb3b)" class="vvczn4bvj"/><path fill="url(#i8icXvd)" class="vvczn4bvj"/></g><path fill="url(#i3qwk1d)" class="j_kfgabci"/><path fill="url(#ieU0UMt)" class="j_kfgabci"/><path fill="url(#iHrkJXb)" class="j_kfgabci"/><g filter="url(#iAjRBnb)"><path fill="url(#iTkJEKL)" class="kjwzoe57o"/></g><g filter="url(#iwNxQ9d)"><path fill="url(#igRR3hf)" class="j9bno4ccl"/></g><path fill="url(#iQmJzpd)" class="j9bno4ccl"/><path fill="url(#iZflYkb)" class="j9bno4ccl"/><path fill="url(#iqQvDBc)" class="j9bno4ccl"/><g filter="url(#iLVRPgc)"><path class="k46-_vbrq"/></g><g filter="url(#ia2d1ob)"><path class="kvdfpnb7q"/></g><g filter="url(#ihPZ47d)"><path class="viikyxbuj"/><path fill="url(#iggFikd)" class="gvuf4911p"/><path fill="url(#izKkIPc)" class="gvuf4911p"/></g><g filter="url(#irFZhlb)"><path class="fy5wnxo1s"/><path fill="url(#iLJo0Tb)" class="qw1kf7aop"/><path fill="url(#iF2UlOd)" class="qw1kf7aop"/><path fill="url(#iMVDUpd)" class="qw1kf7aop"/></g><path fill="url(#iZAhnOd)" class="hgn43q4bl"/><path fill="url(#iKP0Vxc)" class="mmuiuek2r"/><path fill="url(#iFCVqtd)" class="mmuiuek2r"/><g filter="url(#itjepLb)"><path fill="url(#iyyNyye)" class="dux4llbgw"/></g><g filter="url(#i5OpGAc)"><path class="j0n1gtbwv"/></g><g filter="url(#i44jYcb)"><path class="wi07b7b8m"/></g><g filter="url(#ihnJeKs)"><path clip-rule="evenodd" class="kqv-upbgw"/></g><path class="gyaquebqb"/><g filter="url(#iX5sLse)"><path fill="url(#iPGGzgd)" class="yhaojnv4g"/><path fill="url(#ipuwNhZ)" class="yhaojnv4g"/><path fill="url(#ibT2jCb)" class="yhaojnv4g"/><path fill="url(#ia2RnDT)" class="yhaojnv4g"/><path fill="url(#iCqzCCd)" class="yhaojnv4g"/></g><path fill="url(#iCXrJCe)" class="yhaojnv4g"/><path fill="url(#iLw9b7d)" class="yhaojnv4g"/><path fill="url(#ipjnYrd)" class="yhaojnv4g"/><path fill="url(#iEm6JlP)" class="yhaojnv4g"/><path fill="url(#iYWDHdc)" class="yhaojnv4g"/><path fill="url(#ijxbwRP)" class="ixauhdbcg"/><path fill="url(#imAoE8C)" class="ixauhdbcg"/><path fill="url(#iLvEARh)" class="w3a5fpbpu"/><path fill="url(#iO0UBRH)" class="w3a5fpbpu"/><g filter="url(#iNPqwme)"><path class="oongucbzz"/></g><g filter="url(#i3eOrbD)"><path class="i46_e0bpv"/></g><g filter="url(#iM3ijye)"><path class="akfc94qds"/></g><g filter="url(#iXCVdee)"><path stroke="url(#irn7L5b)" class="wqom9qbxf"/></g><g filter="url(#ikAYwRb)"><path stroke="url(#ijSokhe)" class="rjcfxpbyi"/></g><g filter="url(#iyDiTub)"><path class="h-gnhvnys"/></g><defs><radialGradient id="ipgr2Nv" cx="0" cy="0" r="1" gradientTransform="rotate(161.322 8.308 14.989)scale(5.27798 10.393)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="f8_tgzbue"/><stop offset="1" class="v_-r5lbgt"/></radialGradient><radialGradient id="i65lb5l" cx="0" cy="0" r="1" gradientTransform="matrix(-6.07686 2.88187 -1.88528 -3.9754 14.768 19.413)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="vzyrucblm"/><stop offset="1" class="a2i8hds4q"/></radialGradient><radialGradient id="iVhm3mh" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.93285 -1.52074 0 15.583 19.709)" gradientUnits="userSpaceOnUse"><stop offset=".277" class="nbh_shx5m"/><stop offset=".857" class="t43qj-_pv"/></radialGradient><radialGradient id="isdIZOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.17187 -.58594 0 13.188 20.529)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="kfihxnbkq"/><stop offset="1" class="gufu7pbjh"/></radialGradient><radialGradient id="iym4Rxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92987 3.82055 -4.53851 -1.1046 22.284 14.052)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset=".909" class="by5wrxbms"/></radialGradient><radialGradient id="iXN7FQc" cx="0" cy="0" r="1" gradientTransform="matrix(.35375 .48515 -.41214 .30052 21.384 14.376)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="ibjP0fd" cx="0" cy="0" r="1" gradientTransform="matrix(1.78065 .55963 -1.7265 5.49342 8.289 14.644)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="i8icXvd" cx="0" cy="0" r="1" gradientTransform="rotate(120.76 6.993 8.865)scale(4.96207 3.38219)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="awu_febek"/><stop offset="1" class="d--borblg"/></radialGradient><radialGradient id="i3qwk1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.70515 2.05291 0 13.07 11.493)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="sywpedbjh"/><stop offset="1" class="e8d7wsook"/></radialGradient><radialGradient id="ieU0UMt" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -3.6875 .88887 .86627 9 8.577)" gradientUnits="userSpaceOnUse"><stop class="riwtl0knh"/><stop offset="1" class="d4h8kcbpy"/><stop offset="1" class="bt66ftb3q"/></radialGradient><radialGradient id="iHrkJXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.01648 18.5784 0 16 20.892)" gradientUnits="userSpaceOnUse"><stop class="v87iijbot"/><stop offset=".247" class="rhklvibly"/><stop offset=".847" class="c62z8sbxm"/></radialGradient><radialGradient id="iQmJzpd" cx="0" cy="0" r="1" gradientTransform="rotate(-69.027 12.06 -1.035)scale(9.23435 13.1035)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iZflYkb" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 15.456 -3.58)scale(8.1136 11.5131)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iqQvDBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.36525 -2.87418 3.39302 -1.6117 19.488 5.495)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iggFikd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65461 0 0 -.98523 15.899 4.244)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="izKkIPc" cx="0" cy="0" r="1" gradientTransform="matrix(3.88123 -6.1452 6.80825 4.3 9.044 8.998)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iLJo0Tb" cx="0" cy="0" r="1" gradientTransform="matrix(4.23941 -3.41309 5.28955 6.57018 17.907 7.454)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="iF2UlOd" cx="0" cy="0" r="1" gradientTransform="matrix(3.56845 -3.19382 5.84706 6.53292 18.77 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iMVDUpd" cx="0" cy="0" r="1" gradientTransform="rotate(12.654 -21.686 83.331)scale(3.98659 1.66911)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iFCVqtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99989 0 0 -2.21994 9.665 12.614)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iyyNyye" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1053 .18973 -.19453 -1.13328 9.638 12.614)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iPGGzgd" cx="0" cy="0" r="1" gradientTransform="rotate(104.051 5.808 14.306)scale(10.3219 9.11334)" gradientUnits="userSpaceOnUse"><stop offset=".542" class="zoks--egt"/><stop offset="1" class="mghihr2mt"/><stop offset="1" class="ly0wlabmf"/></radialGradient><radialGradient id="ipuwNhZ" cx="0" cy="0" r="1" gradientTransform="matrix(.98633 2.57228 -.42433 .1627 15.36 11.788)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="usgpx-brv"/><stop offset="1" class="r380vabcz"/></radialGradient><radialGradient id="ibT2jCb" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 3.84375 -.63406 .16238 17.174 9.72)" gradientUnits="userSpaceOnUse"><stop class="usgpx-brv"/><stop offset="1" class="r380vabcz"/></radialGradient><radialGradient id="ia2RnDT" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 4.375 -.54534 .0818 19.455 8.907)" gradientUnits="userSpaceOnUse"><stop class="usgpx-brv"/><stop offset="1" class="r380vabcz"/></radialGradient><radialGradient id="iCqzCCd" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 6.673 15.265)scale(3.93108 .49375)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="usgpx-brv"/><stop offset="1" class="r380vabcz"/></radialGradient><radialGradient id="iCXrJCe" cx="0" cy="0" r="1" gradientTransform="matrix(.48147 1.11737 -1.40148 .6039 13.829 11.659)" gradientUnits="userSpaceOnUse"><stop class="jw32s4bqj"/><stop offset="1" class="zjw5n53pb"/></radialGradient><radialGradient id="iLw9b7d" cx="0" cy="0" r="1" gradientTransform="matrix(.41788 1.87137 -2.47438 .55253 15.609 9.225)" gradientUnits="userSpaceOnUse"><stop offset=".038" class="jw32s4bqj"/><stop offset="1" class="zjw5n53pb"/></radialGradient><radialGradient id="ipjnYrd" cx="0" cy="0" r="1" gradientTransform="matrix(.2362 1.81686 -2.40232 .3123 17.99 7.517)" gradientUnits="userSpaceOnUse"><stop offset=".038" class="jw32s4bqj"/><stop offset="1" class="zjw5n53pb"/></radialGradient><radialGradient id="iEm6JlP" cx="0" cy="0" r="1" gradientTransform="matrix(.19985 1.9622 -2.76485 .2816 20.86 7.68)" gradientUnits="userSpaceOnUse"><stop offset=".038" class="jw32s4bqj"/><stop offset="1" class="zjw5n53pb"/></radialGradient><radialGradient id="iYWDHdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.79943 1.34447 -1.89442 -1.12644 24.294 11.223)" gradientUnits="userSpaceOnUse"><stop offset=".038" class="jw32s4bqj"/><stop offset="1" class="zjw5n53pb"/></radialGradient><radialGradient id="ijxbwRP" cx="0" cy="0" r="1" gradientTransform="matrix(-3.96874 1.06253 -.45292 -1.69174 22.94 19.704)" gradientUnits="userSpaceOnUse"><stop class="yzag7e8_g"/><stop offset="1" class="tgllzx6xq"/></radialGradient><radialGradient id="iO0UBRH" cx="0" cy="0" r="1" gradientTransform="rotate(76.973 -1.913 25.291)scale(8.17927 4.47567)" gradientUnits="userSpaceOnUse"><stop class="awna98bfd"/><stop offset="1" class="i4docjyne"/></radialGradient><filter id="irqDdYc" width="20.98" height="11.177" x="5.603" y="19.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.423529 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4115"/></filter><filter id="iHcDQmN" width="13.076" height="15.613" x="9.487" y="5.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.290196 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4115"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.439216 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4115" result="effect2_innerShadow_4002_4115"/></filter><filter id="iAjRBnb" width="12.214" height="13.502" x="12.005" y="7.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4115" stdDeviation=".625"/></filter><filter id="iwNxQ9d" width="15.525" height="9.975" x="7.831" y="1.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4115"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4115" result="effect2_innerShadow_4002_4115"/></filter><filter id="iLVRPgc" width="2.8" height="1.394" x="17.51" y="8.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4115"/></filter><filter id="ia2d1ob" width="2.8" height="1.377" x="11.17" y="8.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4115"/></filter><filter id="ihPZ47d" width="8.338" height="7.623" x="8.061" y="2.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4115"/><feGaussianBlur result="effect2_foregroundBlur_4002_4115" stdDeviation=".25"/></filter><filter id="irFZhlb" width="8.62" height="7.368" x="15.151" y="3.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4115"/><feGaussianBlur result="effect2_foregroundBlur_4002_4115" stdDeviation=".25"/></filter><filter id="itjepLb" width="1.5" height="2.767" x="8.283" y="11.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4115" stdDeviation=".125"/></filter><filter id="i5OpGAc" width="2.051" height="3.216" x="21.118" y="10.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4115" stdDeviation=".15"/></filter><filter id="i44jYcb" width="2.746" height="1.245" x="11.15" y="9.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4115" stdDeviation=".125"/></filter><filter id="ihnJeKs" width="3.511" height="1.562" x="11.244" y="12.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4115"/></filter><filter id="iX5sLse" width="11.547" height="12.796" x="13.324" y="7.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.341176 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4115"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.415686 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4115" result="effect2_innerShadow_4002_4115"/></filter><filter id="iNPqwme" width="2.467" height="5.606" x="17.564" y="7.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4115" stdDeviation=".25"/></filter><filter id="i3eOrbD" width="2.78" height="4.622" x="15.346" y="9.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4115" stdDeviation=".25"/></filter><filter id="iM3ijye" width="2.438" height="3.281" x="13.906" y="11.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4115" stdDeviation=".25"/></filter><filter id="iXCVdee" width="3.688" height="7.656" x="20.862" y="11.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4115" stdDeviation=".25"/></filter><filter id="ikAYwRb" width="2.422" height="10.188" x="20.064" y="8.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4115" stdDeviation=".25"/></filter><filter id="iyDiTub" width="6.867" height="3.946" x="16.454" y="3.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4115" stdDeviation=".5"/></filter><linearGradient id="ieXZqTd" x1="20.291" x2="5.914" y1="27.216" y2="30.121" gradientUnits="userSpaceOnUse"><stop class="ee6wyldiv"/><stop offset="1" class="lrdcrkb9v"/></linearGradient><linearGradient id="isXv3Fc" x1="18.738" x2="16.984" y1="21.66" y2="21.66" gradientUnits="userSpaceOnUse"><stop class="nuo6v0y8p"/><stop offset="1" class="x25vd92ds"/></linearGradient><linearGradient id="iP1Vb3b" x1="15.65" x2="15.65" y1="5.475" y2="20.888" gradientUnits="userSpaceOnUse"><stop class="z1t73abos"/><stop offset=".438" class="b62nnl78i"/></linearGradient><linearGradient id="iTkJEKL" x1="18.112" x2="14.76" y1="8.632" y2="16.297" gradientUnits="userSpaceOnUse"><stop class="s26rbk4iz"/><stop offset="1" class="p3zzfcc3p"/></linearGradient><linearGradient id="igRR3hf" x1="23.857" x2="9.852" y1="6.088" y2="6.088" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iZAhnOd" x1="23.355" x2="21.9" y1="11.91" y2="14.534" gradientUnits="userSpaceOnUse"><stop class="z5pgo-b6k"/><stop offset=".274" class="yx3oq0bow"/></linearGradient><linearGradient id="iKP0Vxc" x1="8.538" x2="10.297" y1="12.769" y2="12.615" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="imAoE8C" x1="20.314" x2="20.396" y1="19.606" y2="19.899" gradientUnits="userSpaceOnUse"><stop offset=".245" class="f8osbx-ej"/><stop offset="1" class="oxk0gpbzd"/></linearGradient><linearGradient id="iLvEARh" x1="19.564" x2="26.002" y1="28.298" y2="26.923" gradientUnits="userSpaceOnUse"><stop class="uu8x24bjn"/><stop offset="1" class="gmelrdffb"/></linearGradient><linearGradient id="irn7L5b" x1="22.706" x2="22.706" y1="12.655" y2="18.561" gradientUnits="userSpaceOnUse"><stop class="byhli_5xc"/><stop offset="1" class="lgjj-eqbb"/></linearGradient><linearGradient id="ijSokhe" x1="21.275" x2="21.275" y1="8.985" y2="17.423" gradientUnits="userSpaceOnUse"><stop class="byhli_5xc"/><stop offset="1" class="lgjj-eqbb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-facepalming-medium" /></template>
<style>
.a2i8hds4q {
  stop-color: var(--svg-color--9f3b09, #9F3B09);
  stop-opacity: 0;
}

.akfc94qds {
  stroke: var(--svg-color--be9988, #BE9988);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m14.781 12.466l.688 1.531");
}

.awna98bfd {
  stop-color: var(--svg-color--ff9946, #FF9946);
}

.awu_febek {
  stop-color: var(--svg-color--a27b73, #A27B73);
}

.b62nnl78i {
  stop-color: var(--svg-color--916066, #916066);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bt66ftb3q {
  stop-color: var(--svg-color--603d3c, #603D3C);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.byhli_5xc {
  stop-color: var(--svg-color--be9988, #BE9988);
}

.c62z8sbxm {
  stop-color: var(--svg-color--90506b, #90506B);
  stop-opacity: 0;
}

.cnsxe7brl {
  d: path("M21.456 14.425c.404-.014.783-.15 1.09-.373v1.123a2.62 2.62 0 0 1-1.616 2.435a5 5 0 0 0 .417-1.423z");
}

.d--borblg {
  stop-color: var(--svg-color--a27b73, #A27B73);
  stop-opacity: 0;
}

.d4h8kcbpy {
  stop-color: var(--svg-color--502b29, #502B29);
  stop-opacity: 0;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dux4llbgw {
  d: path("M9.432 11.48a1.153 1.153 0 0 0 .1 2.267a94 94 0 0 1-.1-2.267");
}

.e8d7wsook {
  stop-color: var(--svg-color--a0746d, #A0746D);
  stop-opacity: 0;
}

.ee6wyldiv {
  stop-color: var(--svg-color--f84d1b, #F84D1B);
}

.f8_tgzbue {
  stop-color: var(--svg-color--ff5016, #FF5016);
}

.f8osbx-ej {
  stop-color: var(--svg-color--d74a13, #D74A13);
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fy5wnxo1s {
  fill: var(--svg-color--563936, #563936);
  d: path("m21.88 10.211l-.035-.76c-.013-.922-.774-1.681-1.695-1.72h-1.69a2.92 2.92 0 0 1-2.561-1.52s-.132-.304-.225-.795c-.185-.986.732-1.717 1.721-1.548c1.252.214 2.765.622 3.855 1.333c2.104 1.373 1.736 3.846.629 5.01");
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gmelrdffb {
  stop-color: var(--svg-color--ff8040, #FF8040);
}

.gufu7pbjh {
  stop-color: var(--svg-color--9e6963, #9E6963);
  stop-opacity: 0;
}

.gvuf4911p {
  d: path("M15.873 6.144a3 3 0 0 1-.08-.165a.8.8 0 0 0-.741-.504h-1.535c-2.226 0-4.03 1.824-4.03 4.075v.332c-.41-.312-.926-.97-.926-2.035c0-1.293.943-1.947 1.544-2.363c.17-.118.312-.217.399-.306l.12-.126c.422-.447 1.173-1.244 2.484-1.592a6.7 6.7 0 0 1 1.986-.193c.472.022.805.43.805.903v1.958z");
}

.gyaquebqb {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M17.643 17.574a2.47 2.47 0 0 0-2.06-1.12c-.862 0-1.618.45-2.059 1.12c-.096.144.038.316.192.297h3.726c.153.039.296-.143.2-.297");
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h-gnhvnys {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.767 6.088h-2.69a.626.626 0 1 1 .1-1.242c.698.111 1.625.266 2.246.42c1.403.348 1.79 1.031 1.898 1.518a1.96 1.96 0 0 0-1.554-.696");
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.hgn43q4bl {
  d: path("M21.529 14.534q.121-1.924.223-3.849a1.941 1.941 0 0 1-.223 3.85");
}

.i46_e0bpv {
  stroke: var(--svg-color--be9988, #BE9988);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m16.22 10.282l1.03 2.871");
}

.i4docjyne {
  stop-color: var(--svg-color--ff9946, #FF9946);
  stop-opacity: 0;
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.ixauhdbcg {
  d: path("M17.74 20.609a.25.25 0 0 1 .182-.302l4.733-1.205a.25.25 0 0 1 .305.184l.274 1.13l-5.229 1.267z");
}

.j_kfgabci {
  d: path("M9.774 16.784a4.72 4.72 0 0 0 4.686 4.108h2.276a4.72 4.72 0 0 0 4.686-4.108c.142-2.272.285-5.067.39-7.337A1.75 1.75 0 0 0 20.15 7.72h-1.69a2.92 2.92 0 0 1-2.667-1.74a.8.8 0 0 0-.742-.505h-1.535c-2.226 0-4.03 1.824-4.03 4.075c0 2.244.14 4.984.287 7.234");
}

.j0n1gtbwv {
  stroke: var(--svg-color--bb8c7a, #BB8C7A);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.577 13.75q.07-1.149.133-2.296a1.152 1.152 0 0 1-.133 2.295Z");
}

.j9bno4ccl {
  d: path("M21.448 4.906a2.8 2.8 0 0 1 1.529 1.268c.563.99.48 2.173-.128 3.046a1.9 1.9 0 0 0-.326 1.055v1.432a2.1 2.1 0 0 0-.805-.323l.095-1.937A1.75 1.75 0 0 0 20.15 7.72h-1.69a2.92 2.92 0 0 1-2.666-1.74a.8.8 0 0 0-.742-.505h-1.536c-2.226 0-4.03 1.824-4.03 4.075l.038 1.854c-.307.045-.627.148-.869.318v-1.447A1.9 1.9 0 0 0 8.33 9.22a2.88 2.88 0 0 1-.173-2.95a2.83 2.83 0 0 1 1.567-1.358a3.23 3.23 0 0 0 1.67-1.339a2.804 2.804 0 0 1 3.486-1.1c.46.201.979.201 1.44 0c.338-.142.71-.226 1.1-.226c1.016 0 1.905.55 2.398 1.365a3.05 3.05 0 0 0 1.631 1.294");
}

.jw32s4bqj {
  stop-color: var(--svg-color--86634e, #86634E);
}

.k46-_vbrq {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M20.095 9.695c-.211-.184-.457-.379-.83-.496c-.366-.115-.826-.146-1.462-.068a.334.334 0 1 0 .082.664c.58-.071.936-.035 1.18.042c.24.076.4.198.59.363a.335.335 0 0 0 .44-.505");
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kfihxnbkq {
  stop-color: var(--svg-color--9e6963, #9E6963);
}

.kjwzoe57o {
  d: path("M17.3 8.65a.946.946 0 0 1 1.108.75l.356 1.848l-.086-1.383a.946.946 0 0 1 1.888-.117l.197 3.17l.327-.675a.989.989 0 1 1 1.78.863l-.817 1.684c-.174.42-.182.807-.19 1.218c-.008.374-.017.767-.152 1.222c-.236.795-.707 1.433-.913 1.652l-2.634.752c-2.028-.497-2.646-1.652-2.982-2.62a13 13 0 0 0-.659-1.585l-1.161-2.238a.946.946 0 0 1 1.678-.871l.194.371l-.463-1.348a.946.946 0 0 1 1.79-.614l.404 1.18l-.415-2.152a.946.946 0 0 1 .75-1.108");
}

.kqv-upbgw {
  fill: var(--svg-color--462d2b, #462D2B);
  fill-rule: evenodd;
  d: path("M14.517 12.346c.15.11.183.32.074.47a2.02 2.02 0 0 1-1.641.828a2.05 2.05 0 0 1-1.639-.824a.336.336 0 1 1 .538-.404c.255.341.656.556 1.1.556c.457 0 .854-.216 1.098-.551c.11-.15.32-.184.47-.075");
}

.kvdfpnb7q {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M11.48 9.564a3.35 3.35 0 0 1 2.097-.433a.335.335 0 0 1-.082.663a2.68 2.68 0 0 0-1.672.344a2 2 0 0 0-.11.072l-.004.002a.335.335 0 0 1-.41-.528z");
}

.lgjj-eqbb {
  stop-color: var(--svg-color--be9988, #BE9988);
  stop-opacity: 0;
}

.lrdcrkb9v {
  stop-color: var(--svg-color--e5571e, #E5571E);
}

.ly0wlabmf {
  stop-color: var(--svg-color--9f7070, #9F7070);
}

.mghihr2mt {
  stop-color: var(--svg-color--7a4a3d, #7A4A3D);
}

.mmuiuek2r {
  d: path("M9.516 10.693c-.943.133-1.685.925-1.685 1.904a1.94 1.94 0 0 0 1.834 1.938a93 93 0 0 1-.15-3.842");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.nbh_shx5m {
  stop-color: var(--svg-color--954a63, #954A63);
}

.nuo6v0y8p {
  stop-color: var(--svg-color--b3716b, #B3716B);
}

.nz6bv55fi {
  d: path("M9.73 14.425a2 2 0 0 1-1.09-.373v1.123a2.62 2.62 0 0 0 1.616 2.435a5 5 0 0 1-.417-1.423z");
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.oongucbzz {
  stroke: var(--svg-color--be9988, #BE9988);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m18.44 8.61l.716 3.856");
}

.oxk0gpbzd {
  stop-color: var(--svg-color--d74a13, #D74A13);
  stop-opacity: 0;
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p3zzfcc3p {
  stop-color: var(--svg-color--804f59, #804F59);
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qw1kf7aop {
  d: path("m21.88 10.211l-.035-.76c-.013-.922-.774-1.681-1.695-1.72h-1.69a2.92 2.92 0 0 1-2.561-1.52s-.132-.304-.225-.795c-.185-.986.732-1.717 1.721-1.548c1.252.214 2.765.622 3.855 1.333c2.104 1.373 1.736 3.846.629 5.01");
}

.r380vabcz {
  stop-color: var(--svg-color--814f4f, #814F4F);
  stop-opacity: 0;
}

.rhklvibly {
  stop-color: var(--svg-color--9e4b71, #9E4B71);
}

.riwtl0knh {
  stop-color: var(--svg-color--603d3c, #603D3C);
}

.rjcfxpbyi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m20.94 8.985l.671 8.438");
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s26rbk4iz {
  stop-color: var(--svg-color--7a4153, #7A4153);
}

.sywpedbjh {
  stop-color: var(--svg-color--905a6a, #905A6A);
}

.t43qj-_pv {
  stop-color: var(--svg-color--955562, #955562);
}

.tgllzx6xq {
  stop-color: var(--svg-color--d54625, #D54625);
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.usgpx-brv {
  stop-color: var(--svg-color--814f4f, #814F4F);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uu8x24bjn {
  stop-color: var(--svg-color--e5562d, #E5562D);
}

.v_-r5lbgt {
  stop-color: var(--svg-color--ff5016, #FF5016);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v87iijbot {
  stop-color: var(--svg-color--a94c85, #A94C85);
}

.viikyxbuj {
  fill: var(--svg-color--533634, #533634);
  d: path("M15.873 6.144a3 3 0 0 1-.08-.165a.8.8 0 0 0-.741-.504h-1.535c-2.226 0-4.03 1.824-4.03 4.075v.332c-.41-.312-.926-.97-.926-2.035c0-1.293.943-1.947 1.544-2.363c.17-.118.312-.217.399-.306l.12-.126c.422-.447 1.173-1.244 2.484-1.592a6.7 6.7 0 0 1 1.986-.193c.472.022.805.43.805.903v1.958z");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vvczn4bvj {
  d: path("M9.771 16.78a4.72 4.72 0 0 0 4.686 4.108h2.276a4.72 4.72 0 0 0 4.686-4.108c.142-2.272.288-5.063.394-7.333A1.75 1.75 0 0 0 20.15 7.72h-1.69a2.92 2.92 0 0 1-2.667-1.74a.8.8 0 0 0-.742-.505h-1.535c-2.226 0-4.03 1.824-4.03 4.075c0 2.244.137 4.98.284 7.23");
}

.vzyrucblm {
  stop-color: var(--svg-color--9f3b09, #9F3B09);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w3a5fpbpu {
  d: path("M17.177 22.683a1 1 0 0 1 .723-1.221l5.303-1.339a1 1 0 0 1 1.213.718l2.414 9.289h-7.719z");
}

.wi07b7b8m {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.525 9.901c.31-.222 1.082-.613 1.996-.46");
}

.wqom9qbxf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m23.675 12.655l-.938 1.89a3.56 3.56 0 0 0-.36 1.782c.08.969-.265 1.828-.64 2.234");
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x25vd92ds {
  stop-color: var(--svg-color--b3716b, #B3716B);
  stop-opacity: 0;
}

.x9v96ly8v {
  d: path("M25.583 30.13v-.39c0-5.4-4.47-9.787-9.99-9.787c-5.52.01-9.99 4.387-9.99 9.786v.391z");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yhaojnv4g {
  d: path("M18.028 7.85a1.1 1.1 0 0 1 1.289.872l.414 2.15l-.1-1.608a1.1 1.1 0 0 1 2.195-.136l.23 3.687l.38-.785a1.15 1.15 0 1 1 2.07 1.004l-.95 1.957c-.203.49-.212.94-.222 1.417c-.01.435-.019.893-.176 1.421c-.275.925-.823 1.667-1.062 1.922l-3.063.875c-2.36-.578-3.078-1.922-3.469-3.047a15.5 15.5 0 0 0-.765-1.844l-1.351-2.602a1.1 1.1 0 0 1 1.952-1.014l.225.432l-.539-1.568a1.1 1.1 0 0 1 2.081-.714l.471 1.372l-.482-2.502a1.1 1.1 0 0 1 .872-1.289");
}

.yx3oq0bow {
  stop-color: var(--svg-color--ad716e, #AD716E);
}

.yzag7e8_g {
  stop-color: var(--svg-color--ff764c, #FF764C);
}

.z1t73abos {
  stop-color: var(--svg-color--a27a6b, #A27A6B);
}

.z5pgo-b6k {
  stop-color: var(--svg-color--bc9679, #BC9679);
}

.zjw5n53pb {
  stop-color: var(--svg-color--86634e, #86634E);
  stop-opacity: 0;
}

.zoks--egt {
  stop-color: var(--svg-color--b6867c, #B6867C);
}

.zq9lh2bgc {
  d: path("M15.583 22.954c-1.46 0-2.64-.912-2.64-2.04v-2.41c0-1.129 1.18-2.04 2.64-2.04s2.64.911 2.64 2.04v2.41c0 1.128-1.18 2.04-2.64 2.04");
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
