<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="xyxx6zbrf"/><path fill="url(#iVgSZEE)" class="pmraj33xm"/><path fill="url(#ihM4l4c)" class="pmraj33xm"/><path fill="url(#iia0POe)" class="pmraj33xm"/><path class="v70k75fly"/><path fill="url(#iQMtoGb)" class="bryt2ei0m"/><path fill="url(#iK9NRYc)" class="bryt2ei0m"/><path fill="url(#ishN0vC)" class="bryt2ei0m"/><path fill="url(#i2z4Teb)" class="bryt2ei0m"/><g filter="url(#im8Vfad)"><rect fill="url(#iq9KG4c)" class="xactr_l1t"/></g><g filter="url(#ifML8Rd)"><rect fill="url(#ixDhM1c)" class="vdopfjrcr"/></g><g filter="url(#iQCwGje)"><rect fill="url(#iiXUzdk)" class="z32z9ccdf"/></g><g filter="url(#iPV6oKb)"><rect fill="url(#izBiOoc)" class="m69j3uu9d"/></g><g filter="url(#isOQ4bd)"><rect fill="url(#ild1beb)" class="tuz3l7b2d"/></g><g filter="url(#iSgo21c)"><rect fill="url(#iQp3EHe)" class="idl50bbvi"/></g><g filter="url(#i3i3Y2d)"><path fill="url(#iOA268b)" class="tvbzl6bbf"/><path fill="url(#ibZbjKd)" class="tvbzl6bbf"/><path fill="url(#i8uAg8c)" class="tvbzl6bbf"/><path fill="url(#is4cxzb)" class="tvbzl6bbf"/></g><path fill="url(#i4HAVuc)" class="tvbzl6bbf"/><g filter="url(#i97tWqc)"><path fill="url(#iNPAqUb)" class="nlsldob4b"/><path fill="url(#iH64qRK)" class="nlsldob4b"/></g><g filter="url(#iMjkqvn)"><rect fill="url(#i90wj8u)" class="laml73bzh"/></g><g filter="url(#imaZD6H)"><rect fill="url(#iMGZEOB)" class="o9hs-xx8i"/></g><g filter="url(#iXiQKpt)"><rect fill="url(#iPNWyCe)" class="idck9bxum"/></g><g filter="url(#innTBpb)"><rect fill="url(#iqBzNye)" class="op1f-vb-w"/></g><g filter="url(#i5qtr5m)"><rect fill="url(#i3YbLae)" class="gb7cmiwvk"/></g><rect class="snrrr9ehg"/><g filter="url(#iDGEkXV)"><rect fill="url(#iUqLCoe)" class="mzp2pfusp"/></g><g filter="url(#ii3VuRK)"><rect fill="url(#iUgABlb)" class="bxc5m3b9m"/></g><g filter="url(#i6I4gBj)"><rect fill="url(#i1an2xe)" class="u5t_tobhv"/></g><defs><linearGradient id="iVgSZEE" x1="6.566" x2="4.646" y1="22.221" y2="22.221" gradientUnits="userSpaceOnUse"><stop class="asryy7f1p"/><stop offset="1" class="ailvalh-c"/></linearGradient><linearGradient id="ihM4l4c" x1="6.883" x2="6.883" y1="6.468" y2="9.674" gradientUnits="userSpaceOnUse"><stop class="afjlfybqu"/><stop offset="1" class="bfgxzgb-n"/></linearGradient><linearGradient id="iia0POe" x1="1.995" x2="3.174" y1="23.257" y2="23.257" gradientUnits="userSpaceOnUse"><stop class="ue9gfrbpl"/><stop offset="1" class="z4436pbzm"/></linearGradient><linearGradient id="iQMtoGb" x1="25.832" x2="26.488" y1="24.41" y2="24.41" gradientUnits="userSpaceOnUse"><stop class="ki7634obb"/><stop offset="1" class="rfitzpjug"/></linearGradient><linearGradient id="iK9NRYc" x1="26.02" x2="26.02" y1="6.91" y2="8.223" gradientUnits="userSpaceOnUse"><stop class="fp3alf6vp"/><stop offset="1" class="aojkp-mii"/></linearGradient><linearGradient id="ishN0vC" x1="30.332" x2="28.332" y1="23.035" y2="23.035" gradientUnits="userSpaceOnUse"><stop class="xbdsddcti"/><stop offset="1" class="vww8zkucj"/></linearGradient><linearGradient id="iq9KG4c" x1="24.336" x2="28.012" y1="12.552" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="ixDhM1c" x1="4.287" x2="7.962" y1="12.552" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="zyxsl87jb"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="iiXUzdk" x1="24.336" x2="28.012" y1="17.496" y2="17.496" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="izBiOoc" x1="4.287" x2="7.962" y1="17.496" y2="17.496" gradientUnits="userSpaceOnUse"><stop class="zyxsl87jb"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="ild1beb" x1="24.336" x2="28.012" y1="22.45" y2="22.45" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="iQp3EHe" x1="4.287" x2="7.962" y1="22.45" y2="22.45" gradientUnits="userSpaceOnUse"><stop class="zyxsl87jb"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="iOA268b" x1="7.773" x2="23.024" y1="27.489" y2="27.489" gradientUnits="userSpaceOnUse"><stop class="fhollguvy"/><stop offset="1" class="mwr8z6bhy"/></linearGradient><linearGradient id="ibZbjKd" x1="15.995" x2="15.995" y1="1.784" y2="4.433" gradientUnits="userSpaceOnUse"><stop class="hl13olbdo"/><stop offset="1" class="u1j38e0xa"/></linearGradient><linearGradient id="i8uAg8c" x1="25.995" x2="23.812" y1="17.823" y2="17.823" gradientUnits="userSpaceOnUse"><stop class="ynooidbeb"/><stop offset="1" class="c9lfs4a7h"/></linearGradient><linearGradient id="iNPAqUb" x1="12.995" x2="19.484" y1="27.538" y2="27.538" gradientUnits="userSpaceOnUse"><stop class="gh1q_wbaw"/><stop offset="1" class="xg07xyb7b"/></linearGradient><linearGradient id="iH64qRK" x1="13.225" x2="14.162" y1="30.035" y2="30.035" gradientUnits="userSpaceOnUse"><stop class="zucckfbiu"/><stop offset="1" class="ox-sinb4l"/></linearGradient><linearGradient id="i90wj8u" x1="11.304" x2="14.979" y1="6.568" y2="6.568" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="iMGZEOB" x1="11.304" x2="14.979" y1="11.517" y2="11.517" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="iPNWyCe" x1="11.304" x2="14.979" y1="16.466" y2="16.466" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="iqBzNye" x1="11.304" x2="14.979" y1="21.567" y2="21.567" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="i3YbLae" x1="17.288" x2="20.963" y1="6.568" y2="6.568" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="iUqLCoe" x1="17.288" x2="20.963" y1="11.517" y2="11.517" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="iUgABlb" x1="17.288" x2="20.963" y1="16.466" y2="16.466" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="i1an2xe" x1="17.288" x2="20.963" y1="21.567" y2="21.567" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><filter id="im8Vfad" width="4.234" height="3.242" x="23.778" y="11.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/></filter><filter id="ifML8Rd" width="4.234" height="3.242" x="3.728" y="11.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/></filter><filter id="iQCwGje" width="4.234" height="3.242" x="23.778" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/></filter><filter id="iPV6oKb" width="4.234" height="3.242" x="3.728" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/></filter><filter id="isOQ4bd" width="4.234" height="3.242" x="23.778" y="20.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/></filter><filter id="iSgo21c" width="4.234" height="3.242" x="3.728" y="20.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/></filter><filter id="i3i3Y2d" width="21" height="28.1" x="5.995" y="2.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/></filter><filter id="i97tWqc" width="6.41" height="5.4" x="12.595" y="25.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.101961 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/></filter><filter id="iMjkqvn" width="4.534" height="3.392" x="10.745" y="4.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6142" result="effect2_innerShadow_18_6142"/></filter><filter id="imaZD6H" width="4.534" height="3.392" x="10.745" y="9.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6142" result="effect2_innerShadow_18_6142"/></filter><filter id="iXiQKpt" width="4.384" height="3.392" x="10.745" y="14.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6142" result="effect2_innerShadow_18_6142"/></filter><filter id="innTBpb" width="4.534" height="3.392" x="10.745" y="19.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6142" result="effect2_innerShadow_18_6142"/></filter><filter id="i5qtr5m" width="4.534" height="3.392" x="16.729" y="4.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6142" result="effect2_innerShadow_18_6142"/></filter><filter id="iDGEkXV" width="4.534" height="3.392" x="16.729" y="9.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6142" result="effect2_innerShadow_18_6142"/></filter><filter id="ii3VuRK" width="4.534" height="3.392" x="16.729" y="14.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6142" result="effect2_innerShadow_18_6142"/></filter><filter id="i6I4gBj" width="4.534" height="3.392" x="16.729" y="19.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6142" result="effect2_innerShadow_18_6142"/></filter><radialGradient id="i2z4Teb" cx="0" cy="0" r="1" gradientTransform="rotate(138.18 13.497 9.367)scale(2.39017 2.18697)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="t7yn_n7en"/><stop offset="1" class="l2pky23_p"/></radialGradient><radialGradient id="is4cxzb" cx="0" cy="0" r="1" gradientTransform="rotate(136.93 12.793 6.224)scale(3.77359 2.7774)" gradientUnits="userSpaceOnUse"><stop class="vro8t3wmz"/><stop offset="1" class="qxxprpbwd"/></radialGradient><radialGradient id="i4HAVuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.65588 8.85508 0 15.995 30.035)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="gbxwk7bmg"/><stop offset="1" class="uak8ynbvv"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:office-building" /></template>
<style>
.afjlfybqu {
  stop-color: var(--svg-color--959595, #959595);
}

.ailvalh-c {
  stop-color: var(--svg-color--605965, #605965);
  stop-opacity: 0;
}

.aojkp-mii {
  stop-color: var(--svg-color--b3b3b3, #B3B3B3);
  stop-opacity: 0;
}

.asryy7f1p {
  stop-color: var(--svg-color--605965, #605965);
}

.bfgxzgb-n {
  stop-color: var(--svg-color--959595, #959595);
  stop-opacity: 0;
}

.bryt2ei0m {
  d: path("M29.995 30.035h-18v-20.7a2.3 2.3 0 0 1 2.3-2.3h13.4a2.3 2.3 0 0 1 2.3 2.3z");
}

.bxc5m3b9m {
  width: 3.984px;
  height: 2.992px;
  x: 16.979px;
  y: 14.97px;
  rx: 0.5px;
}

.c9lfs4a7h {
  stop-color: var(--svg-color--e0dde2, #E0DDE2);
  stop-opacity: 0;
}

.fhollguvy {
  stop-color: var(--svg-color--aca3b3, #ACA3B3);
}

.fp3alf6vp {
  stop-color: var(--svg-color--b3b3b3, #B3B3B3);
}

.ft5dv1b6b {
  fill: none;
}

.gb7cmiwvk {
  width: 3.984px;
  height: 2.992px;
  x: 16.979px;
  y: 5.072px;
  rx: 0.5px;
}

.gbxwk7bmg {
  stop-color: var(--svg-color--afa5b7, #AFA5B7);
}

.gh1q_wbaw {
  stop-color: var(--svg-color--4e405b, #4E405B);
}

.hl13olbdo {
  stop-color: var(--svg-color--b8b7b8, #B8B7B8);
}

.idck9bxum {
  width: 3.984px;
  height: 2.992px;
  x: 10.995px;
  y: 14.97px;
  rx: 0.5px;
}

.idl50bbvi {
  width: 3.984px;
  height: 2.992px;
  x: 3.978px;
  y: 20.954px;
  rx: 0.5px;
}

.ki7634obb {
  stop-color: var(--svg-color--a59fa9, #A59FA9);
}

.l2pky23_p {
  stop-color: var(--svg-color--d7d6d8, #D7D6D8);
  stop-opacity: 0;
}

.laml73bzh {
  width: 3.984px;
  height: 2.992px;
  x: 10.995px;
  y: 5.072px;
  rx: 0.5px;
}

.m69j3uu9d {
  width: 3.984px;
  height: 2.992px;
  x: 3.978px;
  y: 16px;
  rx: 0.5px;
}

.mwr8z6bhy {
  stop-color: var(--svg-color--beb3c4, #BEB3C4);
}

.mzp2pfusp {
  width: 3.984px;
  height: 2.992px;
  x: 16.979px;
  y: 10.021px;
  rx: 0.5px;
}

.nlsldob4b {
  d: path("M18.995 30.035h-6v-3.75c0-.69.56-1.25 1.25-1.25h3.5c.69 0 1.26.56 1.26 1.26v3.74z");
}

.o9hs-xx8i {
  width: 3.984px;
  height: 2.992px;
  x: 10.995px;
  y: 10.021px;
  rx: 0.5px;
}

.op1f-vb-w {
  width: 3.984px;
  height: 2.992px;
  x: 10.995px;
  y: 20.071px;
  rx: 0.5px;
}

.ox-sinb4l {
  stop-color: var(--svg-color--574c64, #574C64);
  stop-opacity: 0;
}

.pmraj33xm {
  d: path("M19.995 30.035h-18v-20.7a2.3 2.3 0 0 1 2.3-2.3h12.78c1.61 0 2.92 1.31 2.92 2.92z");
}

.qxxprpbwd {
  stop-color: var(--svg-color--e8e7e9, #E8E7E9);
  stop-opacity: 0;
}

.rfitzpjug {
  stop-color: var(--svg-color--a59fa9, #A59FA9);
  stop-opacity: 0;
}

.snrrr9ehg {
  width: 3.984px;
  height: 2.992px;
  x: 16.979px;
  y: 10.021px;
  fill: var(--svg-color--fb4eff, #FB4EFF);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 0.5px;
}

.t7yn_n7en {
  stop-color: var(--svg-color--d7d6d8, #D7D6D8);
}

.ttzh61lgu {
  stop-color: var(--svg-color--58e6ff, #58E6FF);
}

.tuz3l7b2d {
  width: 3.984px;
  height: 2.992px;
  x: 24.028px;
  y: 20.954px;
  rx: 0.5px;
}

.tvbzl6bbf {
  d: path("M25.995 30.035h-20V4.495c0-1.36 1.1-2.46 2.46-2.46h15.08c1.36 0 2.46 1.1 2.46 2.46z");
}

.u1j38e0xa {
  stop-color: var(--svg-color--b8b7b8, #B8B7B8);
  stop-opacity: 0;
}

.u5t_tobhv {
  width: 3.984px;
  height: 2.992px;
  x: 16.979px;
  y: 20.071px;
  rx: 0.5px;
}

.uak8ynbvv {
  stop-color: var(--svg-color--afa5b7, #AFA5B7);
  stop-opacity: 0;
}

.ue9gfrbpl {
  stop-color: var(--svg-color--7b777e, #7B777E);
}

.v70k75fly {
  fill: var(--svg-color--b5aeba, #B5AEBA);
  d: path("M29.995 30.035h-18v-20.7a2.3 2.3 0 0 1 2.3-2.3h13.4a2.3 2.3 0 0 1 2.3 2.3z");
}

.vdopfjrcr {
  width: 3.984px;
  height: 2.992px;
  x: 3.978px;
  y: 11.056px;
  rx: 0.5px;
}

.vro8t3wmz {
  stop-color: var(--svg-color--e8e7e9, #E8E7E9);
}

.vww8zkucj {
  stop-color: var(--svg-color--d2cfd4, #D2CFD4);
  stop-opacity: 0;
}

.w3s_subrj {
  stop-color: var(--svg-color--44b8ff, #44B8FF);
}

.xactr_l1t {
  width: 3.984px;
  height: 2.992px;
  x: 24.028px;
  y: 11.056px;
  rx: 0.5px;
}

.xbdsddcti {
  stop-color: var(--svg-color--d2cfd4, #D2CFD4);
}

.xg07xyb7b {
  stop-color: var(--svg-color--3f324c, #3F324C);
}

.xyxx6zbrf {
  fill: var(--svg-color--99919f, #99919F);
  d: path("M19.995 30.035h-18v-20.7a2.3 2.3 0 0 1 2.3-2.3h12.78c1.61 0 2.92 1.31 2.92 2.92z");
}

.ynooidbeb {
  stop-color: var(--svg-color--e0dde2, #E0DDE2);
}

.z32z9ccdf {
  width: 3.984px;
  height: 2.992px;
  x: 24.028px;
  y: 16px;
  rx: 0.5px;
}

.z4436pbzm {
  stop-color: var(--svg-color--7b777e, #7B777E);
  stop-opacity: 0;
}

.zucckfbiu {
  stop-color: var(--svg-color--574c64, #574C64);
}

.zyxsl87jb {
  stop-color: var(--svg-color--47abe5, #47ABE5);
}

</style>
