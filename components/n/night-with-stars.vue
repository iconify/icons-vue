<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iVJe0jh)" class="mn0__lb4b"/><rect fill="url(#iTXQg4b)" class="mn0__lb4b"/><rect fill="url(#iCGuYSd)" class="mn0__lb4b"/><rect fill="url(#ifMacqd)" class="mn0__lb4b"/><rect fill="url(#iDOcv5d)" class="mn0__lb4b"/><g filter="url(#iJgM4Ud)"><path class="y69afwdzs"/><path fill="url(#ireQW9c)" class="nyh1nkygr"/></g><path fill="url(#iZEgBJu)" class="nyh1nkygr"/><g filter="url(#iN0kKqe)"><path class="cfrap032b"/><path fill="url(#iDhkUud)" class="g2ofzhvyu"/></g><g filter="url(#i2v7aAe)"><path fill="url(#ibGwIez)" class="ya9z74exs"/></g><g filter="url(#i1HfaQd)"><path fill="url(#ixsCXQc)" class="ya9z74exs"/></g><path fill="url(#iV8oaxc)" class="ya9z74exs"/><g filter="url(#impmcGc)"><path fill="url(#ibwR77d)" class="bee-6rosf"/></g><path fill="url(#i2E5Jdd)" class="bee-6rosf"/><g filter="url(#igkVL9d)"><path fill="url(#iDSGMQD)" class="mtzh38b2z"/></g><path fill="url(#inIiJNT)" class="mtzh38b2z"/><g filter="url(#iQOgwSd)"><path fill="url(#iyVewjb)" clip-rule="evenodd" class="o8otte4_c"/></g><g filter="url(#iXjB6Be)"><path fill="url(#iMJzjHd)" class="bvlieo7qp"/></g><g filter="url(#iQcw1ed)"><rect fill="url(#iqCGX1c)" class="zdn1_pbxs"/></g><g filter="url(#iLFYFLQ)"><rect fill="url(#i0RL6md)" class="ll2nlkpid"/></g><g filter="url(#iey7D1d)"><rect fill="url(#i9jsawb)" class="thl0nrbdf"/></g><g filter="url(#iH92Bie)"><rect fill="url(#imYHRCc)" class="ojv64lb1v"/></g><g filter="url(#iY1rK6d)"><rect fill="url(#ikXHMkd)" class="wvm97sbpo"/></g><g filter="url(#ikhVaml)"><rect fill="url(#iGpvkvc)" class="mykvhwbcv"/></g><g filter="url(#iLF6Kme)"><rect fill="url(#i3lmLxb)" class="rkifkdfdq"/></g><g filter="url(#ik33aHe)"><rect fill="url(#i4Zb7mx)" class="g5915-bbs"/></g><g filter="url(#i4o27sd)"><rect fill="url(#ioP5dMd)" class="lgqg-gwkg"/></g><g filter="url(#iqrRH3b)"><rect fill="url(#ibrmR5d)" class="ikdmrxbaa"/></g><g filter="url(#i2z2kWd)"><rect fill="url(#ibqeVvp)" class="efqgpbbei"/></g><g filter="url(#i89LTee)"><path class="geb5gwbcy"/></g><path fill="url(#iULukYd)" class="i93drfblv"/><path fill="url(#iov2Olc)" class="i93drfblv"/><g filter="url(#ikcgdBc)"><path class="s0ldn7b5d"/></g><path fill="url(#iLsao3o)" class="hnoijsb5p"/><path fill="url(#ijLR8me)" class="hnoijsb5p"/><g filter="url(#iirJMMb)"><path class="rwb7kk9ge"/></g><path fill="url(#i37bzGc)" class="m_ve1lbmq"/><path fill="url(#i0p5ZWc)" class="m_ve1lbmq"/><g filter="url(#iQov6jd)"><path class="mdgmueqwx"/></g><path fill="url(#iqJv1Xr)" class="ig-_488tu"/><path fill="url(#i4q5DLx)" class="ig-_488tu"/><g filter="url(#idIF98d)"><path fill="url(#i21DRVb)" class="rwmnsvpuw"/></g><path fill="url(#iVXy40c)" class="rwmnsvpuw"/><defs><linearGradient id="iVJe0jh" x1="2.563" x2="30" y1="17.75" y2="17.75" gradientUnits="userSpaceOnUse"><stop class="nxyxwnnrd"/><stop offset="1" class="af7vv-bre"/></linearGradient><linearGradient id="iTXQg4b" x1="2" x2="5.938" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="yv2zx3bpq"/><stop offset="1" class="znffzdlbu"/></linearGradient><linearGradient id="iCGuYSd" x1="16" x2="16" y1="1.75" y2="3.437" gradientUnits="userSpaceOnUse"><stop class="ituairbft"/><stop offset="1" class="uflxtrb1e"/></linearGradient><linearGradient id="ifMacqd" x1="30" x2="26.438" y1="12.813" y2="12.813" gradientUnits="userSpaceOnUse"><stop class="jwj80jb4m"/><stop offset="1" class="mssst3b2h"/></linearGradient><linearGradient id="ireQW9c" x1="21.063" x2="21.051" y1="28.845" y2="19.662" gradientUnits="userSpaceOnUse"><stop class="u3slurbpy"/><stop offset=".517" class="ozsun7bpp"/><stop offset="1" class="e_uc7cc8m"/></linearGradient><linearGradient id="iZEgBJu" x1="23" x2="23" y1="16" y2="16.437" gradientUnits="userSpaceOnUse"><stop class="ezppaz4nj"/><stop offset="1" class="upnupc_1v"/></linearGradient><linearGradient id="iDhkUud" x1="6.795" x2="6.642" y1="25.759" y2="12.278" gradientUnits="userSpaceOnUse"><stop class="u3slurbpy"/><stop offset=".517" class="ozsun7bpp"/><stop offset="1" class="e_uc7cc8m"/></linearGradient><linearGradient id="ibGwIez" x1="27.083" x2="27.083" y1="19" y2="25.866" gradientUnits="userSpaceOnUse"><stop class="e_07aebim"/><stop offset="1" class="mnfo30bxy"/></linearGradient><linearGradient id="ixsCXQc" x1="27.083" x2="27.083" y1="19" y2="25.866" gradientUnits="userSpaceOnUse"><stop class="qwso1d1bn"/><stop offset="1" class="nr4fh8abe"/></linearGradient><linearGradient id="iV8oaxc" x1="26.5" x2="26.5" y1="19" y2="19.239" gradientUnits="userSpaceOnUse"><stop class="gz563zttl"/><stop offset="1" class="p_giqabjt"/></linearGradient><linearGradient id="ibwR77d" x1="4.917" x2="4.917" y1="14" y2="23.987" gradientUnits="userSpaceOnUse"><stop class="qwso1d1bn"/><stop offset="1" class="nr4fh8abe"/></linearGradient><linearGradient id="i2E5Jdd" x1="4.5" x2="4.5" y1="14" y2="14.348" gradientUnits="userSpaceOnUse"><stop class="gz563zttl"/><stop offset="1" class="p_giqabjt"/></linearGradient><linearGradient id="iDSGMQD" x1="16" x2="16" y1="11" y2="22.86" gradientUnits="userSpaceOnUse"><stop class="qwso1d1bn"/><stop offset="1" class="nr4fh8abe"/></linearGradient><linearGradient id="inIiJNT" x1="15" x2="15" y1="11" y2="11.413" gradientUnits="userSpaceOnUse"><stop class="gz563zttl"/><stop offset="1" class="p_giqabjt"/></linearGradient><linearGradient id="iyVewjb" x1="27" x2="27" y1="25.556" y2="27" gradientUnits="userSpaceOnUse"><stop class="pn2m63b6s"/><stop offset="1" class="zbvfvqb0f"/></linearGradient><linearGradient id="iMJzjHd" x1="27" x2="27" y1="21.556" y2="23" gradientUnits="userSpaceOnUse"><stop class="pn2m63b6s"/><stop offset="1" class="zbvfvqb0f"/></linearGradient><linearGradient id="iqCGX1c" x1="16.98" x2="15.02" y1="13.016" y2="14.976" gradientUnits="userSpaceOnUse"><stop class="see4are_m"/><stop offset="1" class="ut9n0nb5i"/></linearGradient><linearGradient id="i0RL6md" x1="12.98" x2="11.375" y1="13.433" y2="14.976" gradientUnits="userSpaceOnUse"><stop class="rarmbzbtc"/><stop offset="1" class="opcoxub0t"/></linearGradient><linearGradient id="i9jsawb" x1="4.98" x2="3.02" y1="16.02" y2="17.98" gradientUnits="userSpaceOnUse"><stop class="see4are_m"/><stop offset="1" class="ut9n0nb5i"/></linearGradient><linearGradient id="imYHRCc" x1="4.98" x2="3.375" y1="20.438" y2="21.98" gradientUnits="userSpaceOnUse"><stop class="rarmbzbtc"/><stop offset="1" class="opcoxub0t"/></linearGradient><linearGradient id="ikXHMkd" x1="4.98" x2="3.375" y1="24.438" y2="25.98" gradientUnits="userSpaceOnUse"><stop class="rarmbzbtc"/><stop offset="1" class="opcoxub0t"/></linearGradient><linearGradient id="iGpvkvc" x1="16.98" x2="15.375" y1="17.438" y2="18.98" gradientUnits="userSpaceOnUse"><stop class="rarmbzbtc"/><stop offset="1" class="opcoxub0t"/></linearGradient><linearGradient id="i3lmLxb" x1="16.98" x2="15.375" y1="21.442" y2="22.984" gradientUnits="userSpaceOnUse"><stop class="rarmbzbtc"/><stop offset="1" class="opcoxub0t"/></linearGradient><linearGradient id="i4Zb7mx" x1="16.98" x2="15.02" y1="25.029" y2="26.989" gradientUnits="userSpaceOnUse"><stop class="see4are_m"/><stop offset="1" class="ut9n0nb5i"/></linearGradient><linearGradient id="ioP5dMd" x1="12.98" x2="11.375" y1="17.438" y2="18.98" gradientUnits="userSpaceOnUse"><stop class="rarmbzbtc"/><stop offset="1" class="opcoxub0t"/></linearGradient><linearGradient id="ibrmR5d" x1="12.98" x2="11.02" y1="21.024" y2="22.984" gradientUnits="userSpaceOnUse"><stop class="see4are_m"/><stop offset="1" class="ut9n0nb5i"/></linearGradient><linearGradient id="ibqeVvp" x1="12.98" x2="11.375" y1="25.446" y2="26.989" gradientUnits="userSpaceOnUse"><stop class="rarmbzbtc"/><stop offset="1" class="opcoxub0t"/></linearGradient><linearGradient id="i21DRVb" x1="21.5" x2="26.794" y1="10.75" y2="5.72" gradientUnits="userSpaceOnUse"><stop class="sksjlpb7i"/><stop offset="1" class="hv8fe20mo"/></linearGradient><filter id="iJgM4Ud" width="10.4" height="14.4" x="17.8" y="15.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.266667 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0509804 0 0 0 0 0.027451 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7696" result="effect2_innerShadow_18_7696"/></filter><filter id="iN0kKqe" width="9.4" height="24.4" x="3.8" y="5.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.266667 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0509804 0 0 0 0 0.027451 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7696" result="effect2_innerShadow_18_7696"/></filter><filter id="i2v7aAe" width="7.2" height="11" x="23" y="19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.501961 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="i1HfaQd" width="7.4" height="11" x="22.8" y="19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.329412 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.133333 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7696" result="effect2_innerShadow_18_7696"/></filter><filter id="impmcGc" width="5.4" height="16" x="1.8" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.329412 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.133333 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7696" result="effect2_innerShadow_18_7696"/></filter><filter id="igkVL9d" width="12.4" height="19" x="8.8" y="11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.329412 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.133333 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7696" result="effect2_innerShadow_18_7696"/></filter><filter id="iQOgwSd" width="6.1" height="2.2" x="24" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.580392 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="iXjB6Be" width="6.1" height="2.2" x="24" y="21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.580392 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="iQcw1ed" width="2.161" height="2.16" x="14.819" y="13.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.0196078 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="iLFYFLQ" width="2.161" height="2.16" x="10.819" y="13.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.572549 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="iey7D1d" width="2.161" height="2.16" x="2.82" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.0196078 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="iH92Bie" width="2.161" height="2.16" x="2.82" y="20.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.572549 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="iY1rK6d" width="2.161" height="2.16" x="2.82" y="24.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.572549 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="ikhVaml" width="2.161" height="2.16" x="14.819" y="17.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.572549 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="iLF6Kme" width="2.161" height="2.16" x="14.819" y="21.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.572549 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="ik33aHe" width="2.161" height="2.16" x="14.819" y="25.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.0196078 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="i4o27sd" width="2.161" height="2.16" x="10.819" y="17.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.572549 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="iqrRH3b" width="2.161" height="2.16" x="10.819" y="21.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.0196078 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="i2z2kWd" width="2.161" height="2.16" x="10.819" y="25.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.572549 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><filter id="i89LTee" width="2.682" height="2.682" x="26.159" y="11.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.603922 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7696" result="effect2_innerShadow_18_7696"/></filter><filter id="ikcgdBc" width="2.682" height="2.682" x="20.159" y="3.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.603922 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7696" result="effect2_innerShadow_18_7696"/></filter><filter id="iirJMMb" width="3.682" height="3.682" x="14.659" y="5.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.603922 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7696" result="effect2_innerShadow_18_7696"/></filter><filter id="iQov6jd" width="2.682" height="2.682" x="4.159" y="3.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.603922 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7696" result="effect2_innerShadow_18_7696"/></filter><filter id="idIF98d" width="6.734" height="6.372" x="20.416" y="4.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.192157 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7696"/></filter><radialGradient id="iDOcv5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43748 2.31252 -2.70261 -2.84866 29.313 3.125)" gradientUnits="userSpaceOnUse"><stop class="qtlb7fwbg"/><stop offset="1" class="lnwltjb1t"/></radialGradient><radialGradient id="iULukYd" cx="0" cy="0" r="1" gradientTransform="matrix(.58053 .54118 -.6915 .7418 26.585 11.546)" gradientUnits="userSpaceOnUse"><stop class="j7-oznl0a"/><stop offset="1" class="e6bsmcb6t"/></radialGradient><radialGradient id="iov2Olc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46246 -.51165 .63412 -.57315 28.366 13.415)" gradientUnits="userSpaceOnUse"><stop class="j7-oznl0a"/><stop offset="1" class="e6bsmcb6t"/></radialGradient><radialGradient id="iLsao3o" cx="0" cy="0" r="1" gradientTransform="matrix(.58053 .54118 -.6915 .7418 20.585 3.546)" gradientUnits="userSpaceOnUse"><stop class="j7-oznl0a"/><stop offset="1" class="e6bsmcb6t"/></radialGradient><radialGradient id="ijLR8me" cx="0" cy="0" r="1" gradientTransform="matrix(-.46246 -.51165 .63412 -.57315 22.366 5.414)" gradientUnits="userSpaceOnUse"><stop class="j7-oznl0a"/><stop offset="1" class="e6bsmcb6t"/></radialGradient><radialGradient id="i37bzGc" cx="0" cy="0" r="1" gradientTransform="matrix(.77405 .72157 -.922 .98906 15.28 6.227)" gradientUnits="userSpaceOnUse"><stop class="j7-oznl0a"/><stop offset="1" class="e6bsmcb6t"/></radialGradient><radialGradient id="i0p5ZWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.61662 -.6822 .8455 -.7642 17.654 8.72)" gradientUnits="userSpaceOnUse"><stop class="j7-oznl0a"/><stop offset="1" class="e6bsmcb6t"/></radialGradient><radialGradient id="iqJv1Xr" cx="0" cy="0" r="1" gradientTransform="matrix(.46094 .42969 -.54904 .58898 4.773 3.742)" gradientUnits="userSpaceOnUse"><stop class="j7-oznl0a"/><stop offset="1" class="e6bsmcb6t"/></radialGradient><radialGradient id="i4q5DLx" cx="0" cy="0" r="1" gradientTransform="matrix(-.36719 -.40625 .50349 -.45508 6.188 5.227)" gradientUnits="userSpaceOnUse"><stop class="j7-oznl0a"/><stop offset="1" class="e6bsmcb6t"/></radialGradient><radialGradient id="iVXy40c" cx="0" cy="0" r="1" gradientTransform="matrix(4.55624 -1.71394 1.81369 4.82141 22.444 7.975)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="fnn0v5m3t"/><stop offset="1" class="hm3kombhi"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:night-with-stars" /></template>
<style>
.af7vv-bre {
  stop-color: var(--svg-color--544380, #544380);
}

.bee-6rosf {
  d: path("M2 14v12a4 4 0 0 0 4 4h1V15.25C7 14.56 6.44 14 5.75 14z");
}

.bvlieo7qp {
  d: path("M24 22a1 1 0 0 1 1-1h5v2h-5a1 1 0 0 1-1-1");
}

.cfrap032b {
  fill: var(--svg-color--2d2934, #2D2934);
  d: path("M6 30h7V7.25C13 6.56 12.44 6 11.75 6h-1.5C9.56 6 9 6.56 9 7.25V8H5.25C4.56 8 4 8.56 4 9.25v20.215c.588.34 1.271.535 2 .535");
}

.e_07aebim {
  stop-color: var(--svg-color--4791cd, #4791CD);
}

.e_uc7cc8m {
  stop-color: var(--svg-color--180d25, #180D25);
  stop-opacity: 0;
}

.e6bsmcb6t {
  stop-color: var(--svg-color--a097a2, #A097A2);
  stop-opacity: 0;
}

.efqgpbbei {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 25.029px;
  rx: 0.3px;
}

.ezppaz4nj {
  stop-color: var(--svg-color--1f1b26, #1F1B26);
}

.fnn0v5m3t {
  stop-color: var(--svg-color--fffb8a, #FFFB8A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g2ofzhvyu {
  d: path("M6 30h7V7.25C13 6.56 12.44 6 11.75 6h-1.5C9.56 6 9 6.56 9 7.25V8H5.25C4.56 8 4 8.56 4 9.25v20.215c.588.34 1.271.535 2 .535");
}

.g5915-bbs {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 25.029px;
  rx: 0.3px;
}

.geb5gwbcy {
  fill: var(--svg-color--d9cedd, #D9CEDD);
  d: path("m27.075 11.85l.201-.403a.25.25 0 0 1 .448 0l.201.404a.5.5 0 0 0 .224.223l.404.202a.25.25 0 0 1 0 .448l-.404.201a.5.5 0 0 0-.224.224l-.201.404a.25.25 0 0 1-.448 0l-.201-.404a.5.5 0 0 0-.224-.223l-.404-.202a.25.25 0 0 1 0-.448l.404-.201a.5.5 0 0 0 .224-.224");
}

.gz563zttl {
  stop-color: var(--svg-color--3e2c51, #3E2C51);
}

.hm3kombhi {
  stop-color: var(--svg-color--fffb8a, #FFFB8A);
}

.hnoijsb5p {
  d: path("m21.075 3.85l.201-.403a.25.25 0 0 1 .448 0l.201.404a.5.5 0 0 0 .224.224l.404.201a.25.25 0 0 1 0 .448l-.404.201a.5.5 0 0 0-.224.224l-.201.404a.25.25 0 0 1-.448 0l-.201-.404a.5.5 0 0 0-.224-.224l-.404-.201a.25.25 0 0 1 0-.448l.404-.201a.5.5 0 0 0 .224-.224");
}

.hv8fe20mo {
  stop-color: var(--svg-color--ebc364, #EBC364);
}

.i93drfblv {
  d: path("m27.075 11.85l.201-.403a.25.25 0 0 1 .448 0l.201.404a.5.5 0 0 0 .224.223l.404.202a.25.25 0 0 1 0 .448l-.404.201a.5.5 0 0 0-.224.224l-.201.404a.25.25 0 0 1-.448 0l-.201-.404a.5.5 0 0 0-.224-.223l-.404-.202a.25.25 0 0 1 0-.448l.404-.201a.5.5 0 0 0 .224-.224");
}

.ig-_488tu {
  d: path("m5.075 3.851l.201-.404a.25.25 0 0 1 .448 0l.201.404a.5.5 0 0 0 .224.224l.404.201a.25.25 0 0 1 0 .448l-.404.202a.5.5 0 0 0-.224.223l-.201.404a.25.25 0 0 1-.448 0l-.201-.404a.5.5 0 0 0-.224-.223l-.404-.202a.25.25 0 0 1 0-.448l.404-.201a.5.5 0 0 0 .224-.224");
}

.ikdmrxbaa {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 21.024px;
  rx: 0.3px;
}

.ituairbft {
  stop-color: var(--svg-color--44315d, #44315D);
}

.j7-oznl0a {
  stop-color: var(--svg-color--a097a2, #A097A2);
}

.jwj80jb4m {
  stop-color: var(--svg-color--624d82, #624D82);
}

.lgqg-gwkg {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 17.02px;
  rx: 0.3px;
}

.ll2nlkpid {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 13.016px;
  rx: 0.3px;
}

.lnwltjb1t {
  stop-color: var(--svg-color--634d82, #634D82);
  stop-opacity: 0;
}

.m_ve1lbmq {
  d: path("m15.908 6.684l.368-.737a.25.25 0 0 1 .448 0l.368.737a.5.5 0 0 0 .224.224l.737.368a.25.25 0 0 1 0 .448l-.737.368a.5.5 0 0 0-.224.224l-.368.737a.25.25 0 0 1-.448 0l-.368-.737a.5.5 0 0 0-.224-.224l-.737-.368a.25.25 0 0 1 0-.448l.737-.368a.5.5 0 0 0 .224-.224");
}

.mdgmueqwx {
  fill: var(--svg-color--d9cedd, #D9CEDD);
  d: path("m5.075 3.851l.201-.404a.25.25 0 0 1 .448 0l.201.404a.5.5 0 0 0 .224.224l.404.201a.25.25 0 0 1 0 .448l-.404.202a.5.5 0 0 0-.224.223l-.201.404a.25.25 0 0 1-.448 0l-.201-.404a.5.5 0 0 0-.224-.223l-.404-.202a.25.25 0 0 1 0-.448l.404-.201a.5.5 0 0 0 .224-.224");
}

.mn0__lb4b {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 2px;
  rx: 4px;
}

.mnfo30bxy {
  stop-color: var(--svg-color--a1a0b4, #A1A0B4);
}

.mssst3b2h {
  stop-color: var(--svg-color--624d82, #624D82);
  stop-opacity: 0;
}

.mtzh38b2z {
  d: path("M9 30h12v-5.75c0-.69-.56-1.25-1.25-1.25H19V12.25c0-.69-.56-1.25-1.25-1.25h-7.5C9.56 11 9 11.56 9 12.25z");
}

.mykvhwbcv {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 17.02px;
  rx: 0.3px;
}

.nr4fh8abe {
  stop-color: var(--svg-color--43364f, #43364F);
}

.nxyxwnnrd {
  stop-color: var(--svg-color--503b75, #503B75);
}

.nyh1nkygr {
  d: path("M18 30h8c.729 0 1.412-.195 2-.535V17.25c0-.69-.56-1.25-1.25-1.25h-7.5c-.69 0-1.25.56-1.25 1.25z");
}

.o8otte4_c {
  fill-rule: evenodd;
  d: path("M30 25h-5a1 1 0 1 0 0 2h4.874A4 4 0 0 0 30 26z");
}

.ojv64lb1v {
  width: 1.961px;
  height: 1.96px;
  x: 3.02px;
  y: 20.02px;
  rx: 0.3px;
}

.opcoxub0t {
  stop-color: var(--svg-color--ffff7d, #FFFF7D);
}

.ozsun7bpp {
  stop-color: var(--svg-color--180d25, #180D25);
}

.p_giqabjt {
  stop-color: var(--svg-color--3e2c51, #3E2C51);
  stop-opacity: 0;
}

.pn2m63b6s {
  stop-color: var(--svg-color--ffd77a, #FFD77A);
}

.qtlb7fwbg {
  stop-color: var(--svg-color--634d82, #634D82);
}

.qwso1d1bn {
  stop-color: var(--svg-color--533d69, #533D69);
}

.rarmbzbtc {
  stop-color: var(--svg-color--f2bc6c, #F2BC6C);
}

.rkifkdfdq {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 21.024px;
  rx: 0.3px;
}

.rwb7kk9ge {
  fill: var(--svg-color--d9cedd, #D9CEDD);
  d: path("m15.908 6.684l.368-.737a.25.25 0 0 1 .448 0l.368.737a.5.5 0 0 0 .224.224l.737.368a.25.25 0 0 1 0 .448l-.737.368a.5.5 0 0 0-.224.224l-.368.737a.25.25 0 0 1-.448 0l-.368-.737a.5.5 0 0 0-.224-.224l-.737-.368a.25.25 0 0 1 0-.448l.737-.368a.5.5 0 0 0 .224-.224");
}

.rwmnsvpuw {
  d: path("M22.012 9.336a3.49 3.49 0 0 0 3.492-3.492c0-.296-.032-.527-.102-.801c-.036-.145.122-.23.235-.145C26.473 5.536 27 6.461 27 7.594a3.492 3.492 0 0 1-6.566 1.658c-.068-.125.072-.253.203-.197c.422.18.887.28 1.375.28");
}

.s0ldn7b5d {
  fill: var(--svg-color--d9cedd, #D9CEDD);
  d: path("m21.075 3.85l.201-.403a.25.25 0 0 1 .448 0l.201.404a.5.5 0 0 0 .224.224l.404.201a.25.25 0 0 1 0 .448l-.404.201a.5.5 0 0 0-.224.224l-.201.404a.25.25 0 0 1-.448 0l-.201-.404a.5.5 0 0 0-.224-.224l-.404-.201a.25.25 0 0 1 0-.448l.404-.201a.5.5 0 0 0 .224-.224");
}

.see4are_m {
  stop-color: var(--svg-color--282130, #282130);
}

.sksjlpb7i {
  stop-color: var(--svg-color--e6a947, #E6A947);
}

.thl0nrbdf {
  width: 1.961px;
  height: 1.96px;
  x: 3.02px;
  y: 16.02px;
  rx: 0.3px;
}

.u3slurbpy {
  stop-color: var(--svg-color--210b39, #210B39);
}

.uflxtrb1e {
  stop-color: var(--svg-color--44315d, #44315D);
  stop-opacity: 0;
}

.upnupc_1v {
  stop-color: var(--svg-color--1f1b26, #1F1B26);
  stop-opacity: 0;
}

.ut9n0nb5i {
  stop-color: var(--svg-color--383739, #383739);
}

.wvm97sbpo {
  width: 1.961px;
  height: 1.96px;
  x: 3.02px;
  y: 24.02px;
  rx: 0.3px;
}

.y69afwdzs {
  fill: var(--svg-color--2d2934, #2D2934);
  d: path("M18 30h8c.729 0 1.412-.195 2-.535V17.25c0-.69-.56-1.25-1.25-1.25h-7.5c-.69 0-1.25.56-1.25 1.25z");
}

.ya9z74exs {
  d: path("M23 30h3a4 4 0 0 0 4-4v-7h-5.75c-.69 0-1.25.56-1.25 1.25z");
}

.yv2zx3bpq {
  stop-color: var(--svg-color--211438, #211438);
}

.zbvfvqb0f {
  stop-color: var(--svg-color--fff670, #FFF670);
}

.zdn1_pbxs {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 13.016px;
  rx: 0.3px;
}

.znffzdlbu {
  stop-color: var(--svg-color--211438, #211438);
  stop-opacity: 0;
}

</style>
