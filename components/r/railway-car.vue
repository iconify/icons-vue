<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iMGy66c" class="fza5w6blg"/></defs><g class="ft5dv1b6b"><g filter="url(#ixGW1ob)"><path fill="url(#ikDbltc)" class="o7oqkyrpt"/></g><g filter="url(#i12IbWc)"><path fill="url(#ioAjdCd)" class="b77po707m"/></g><path fill="url(#igmUoCe)" class="pwx7_gbfx"/><path fill="url(#iRXn6ud)" class="pwx7_gbfx"/><path fill="url(#iZ8mtQd)" class="pwx7_gbfx"/><path fill="url(#iviOk9d)" class="pwx7_gbfx"/><path fill="url(#idZUODc)" class="pwx7_gbfx"/><path fill="url(#i86IVHb)" class="pwx7_gbfx"/><g filter="url(#i1jzAzc)"><path fill="url(#idiSFeA)" clip-rule="evenodd" class="z7cptabsg"/></g><path fill="url(#i7LdzFb)" clip-rule="evenodd" class="z7cptabsg"/><g filter="url(#i7lyKCe)"><path stroke="url(#ihivHdc)" class="pfmgngbwj"/></g><g filter="url(#innAZec)"><path stroke="url(#i67YIDb)" class="tq8y3446b"/></g><g filter="url(#i4j7Woc)"><path fill="url(#iB2ITdL)" class="din_jw39f"/></g><path fill="url(#iTd5mrj)" class="din_jw39f"/><g filter="url(#irTSGMe)"><path fill="url(#iG083Ee)" class="nbrdrbbnx"/><path fill="url(#i4oHrxc)" class="nbrdrbbnx"/></g><g filter="url(#iEBnQqe)"><path stroke="url(#i26idXb)" class="o14l7lb8x"/></g><path fill="url(#iBeypzc)" class="juc9gobzt"/><path fill="url(#iMh19XE)" class="juc9gobzt"/><path fill="url(#iz51yAe)" class="juc9gobzt"/><g filter="url(#ipY0gdd)"><path stroke="url(#iBdhSop)" class="outpr4b2k"/></g><g filter="url(#ikmGdde)"><path fill="url(#iy5xhPc)" class="p8vxosb4r"/><path fill="url(#i5fmisc)" class="p8vxosb4r"/></g><g filter="url(#iUJcXgd)"><path stroke="url(#igkjihK)" class="hvgiq9rka"/></g><g filter="url(#iXm4ARc)"><path fill="url(#izrUEWb)" class="ffg6fcc-q"/></g><g filter="url(#iWD8hgc)"><path stroke="url(#ieiAw6d)" class="n7z1y9sbs"/></g><g filter="url(#i32bNnd)"><path fill="url(#iUj7Y2d)" class="zl6genb3b"/></g><g filter="url(#ifKw6Oe)"><path fill="url(#iiDxsnp)" class="b6jvotbvk"/></g><path fill="url(#iemTdde)" clip-rule="evenodd" class="vw5syu5st"/><path fill="url(#i8Skydd)" clip-rule="evenodd" class="vw5syu5st"/><path fill="url(#ihutrNb)" clip-rule="evenodd" class="vw5syu5st"/><path fill="url(#ijFBFMt)" clip-rule="evenodd" class="vw5syu5st"/><path fill="url(#iZvtRib)" clip-rule="evenodd" class="vw5syu5st"/><g filter="url(#iqBOFMe)"><path stroke="url(#ifi9Qle)" class="fy8_v9-pv"/></g><g filter="url(#iwcs7nd)"><path stroke="url(#ig47iCe)" class="i6m30lbyf"/></g><g filter="url(#iZhp3ye)"><use href="#iMGy66c"/></g><g filter="url(#iPTVIJd)"><use href="#iMGy66c"/></g><path fill="url(#iTN1Kxe)" class="tauy1bbeu"/><defs><linearGradient id="ikDbltc" x1="22.062" x2="22.062" y1="27.587" y2="29.021" gradientUnits="userSpaceOnUse"><stop class="olcww3buq"/><stop offset="1" class="nn_d8qbth"/></linearGradient><linearGradient id="ioAjdCd" x1="10.056" x2="10.056" y1="27.588" y2="29.018" gradientUnits="userSpaceOnUse"><stop class="olcww3buq"/><stop offset="1" class="nn_d8qbth"/></linearGradient><linearGradient id="igmUoCe" x1="6.087" x2="27.056" y1="28" y2="28" gradientUnits="userSpaceOnUse"><stop class="cez_pnbfz"/><stop offset="1" class="xmv3_lblk"/></linearGradient><linearGradient id="iZ8mtQd" x1="16.057" x2="16.057" y1="25.947" y2="26.262" gradientUnits="userSpaceOnUse"><stop class="azm5e7afa"/><stop offset="1" class="y410z-b5s"/></linearGradient><linearGradient id="idZUODc" x1="16.057" x2="16.057" y1="28.153" y2="27.387" gradientUnits="userSpaceOnUse"><stop class="g03-hq_oj"/><stop offset="1" class="d6417sbth"/></linearGradient><linearGradient id="i86IVHb" x1="5.059" x2="6.554" y1="27.2" y2="27.2" gradientUnits="userSpaceOnUse"><stop class="kchxs-spv"/><stop offset="1" class="nrqb1q2xi"/></linearGradient><linearGradient id="idiSFeA" x1="21.877" x2="9.622" y1="6.539" y2="6.539" gradientUnits="userSpaceOnUse"><stop class="bvr577byw"/><stop offset="1" class="v51qg7trj"/></linearGradient><linearGradient id="i7LdzFb" x1="18.25" x2="13.684" y1="9.907" y2="3.222" gradientUnits="userSpaceOnUse"><stop class="zxd_fyb_s"/><stop offset="1" class="mu2ajvbzw"/></linearGradient><linearGradient id="ihivHdc" x1="22.854" x2="19.167" y1="9.249" y2="10.409" gradientUnits="userSpaceOnUse"><stop class="cdx8_7uoq"/><stop offset="1" class="ykszwfj2m"/></linearGradient><linearGradient id="i67YIDb" x1="10.255" x2="11.111" y1="5.874" y2="8.97" gradientUnits="userSpaceOnUse"><stop class="smuqz5b4e"/><stop offset="1" class="i8rjt71vj"/></linearGradient><linearGradient id="iB2ITdL" x1="16.053" x2="16.053" y1="7.994" y2="10.382" gradientUnits="userSpaceOnUse"><stop class="ra19axbdw"/><stop offset="1" class="ang3p5hca"/></linearGradient><linearGradient id="iTd5mrj" x1="16.053" x2="16.053" y1="7.994" y2="8.437" gradientUnits="userSpaceOnUse"><stop class="car3btb1d"/><stop offset="1" class="jsyw4i05b"/></linearGradient><linearGradient id="iG083Ee" x1="16.058" x2="16.058" y1="10" y2="13.294" gradientUnits="userSpaceOnUse"><stop class="gb5wo06fx"/><stop offset="1" class="kfkl73-ej"/></linearGradient><linearGradient id="i4oHrxc" x1="3.742" x2="11.475" y1="15.013" y2="10" gradientUnits="userSpaceOnUse"><stop class="fhc8pt1md"/><stop offset="1" class="s9-t5iurb"/></linearGradient><linearGradient id="i26idXb" x1="25.683" x2="2.307" y1="9.25" y2="16" gradientUnits="userSpaceOnUse"><stop offset=".035" class="qlx4r-auh"/><stop offset=".485" class="tjphb4b-p"/><stop offset="1" class="l6ck1jb0y"/></linearGradient><linearGradient id="iBeypzc" x1="2.055" x2="14.571" y1="22.096" y2="22.096" gradientUnits="userSpaceOnUse"><stop class="pqqpf9bwm"/><stop offset="1" class="idibcljtc"/></linearGradient><linearGradient id="iMh19XE" x1="1.739" x2="4.621" y1="24" y2="24" gradientUnits="userSpaceOnUse"><stop class="aso8ombfu"/><stop offset=".343" class="i_y9pybez"/><stop offset="1" class="n27p4fbpl"/></linearGradient><linearGradient id="iz51yAe" x1="30.527" x2="27.251" y1="20.944" y2="20.944" gradientUnits="userSpaceOnUse"><stop class="mvqyt7bpa"/><stop offset="1" class="er3apzjdq"/></linearGradient><linearGradient id="iBdhSop" x1="22.056" x2="28.056" y1="18.708" y2="18.708" gradientUnits="userSpaceOnUse"><stop class="r27hd1bts"/><stop offset="1" class="zkluhub5k"/></linearGradient><linearGradient id="iy5xhPc" x1="22.056" x2="28.707" y1="23.37" y2="14" gradientUnits="userSpaceOnUse"><stop class="qtruv094h"/><stop offset="1" class="brg2tkgdu"/></linearGradient><linearGradient id="i5fmisc" x1="22.056" x2="22.917" y1="21.736" y2="21.736" gradientUnits="userSpaceOnUse"><stop class="acgrlfbkw"/><stop offset="1" class="u6slzqdib"/></linearGradient><linearGradient id="igkjihK" x1="5.248" x2="8.026" y1="19.64" y2="17.171" gradientUnits="userSpaceOnUse"><stop class="r27hd1bts"/><stop offset="1" class="zkluhub5k"/></linearGradient><linearGradient id="izrUEWb" x1="8.736" x2="5.062" y1="16.417" y2="20.635" gradientUnits="userSpaceOnUse"><stop class="d8a511b8h"/><stop offset="1" class="s7zmy3bbc"/></linearGradient><linearGradient id="ieiAw6d" x1="14.242" x2="17.02" y1="19.64" y2="17.171" gradientUnits="userSpaceOnUse"><stop class="r27hd1bts"/><stop offset="1" class="zkluhub5k"/></linearGradient><linearGradient id="iUj7Y2d" x1="17.73" x2="14.056" y1="16.417" y2="20.635" gradientUnits="userSpaceOnUse"><stop class="d8a511b8h"/><stop offset="1" class="s7zmy3bbc"/></linearGradient><linearGradient id="iiDxsnp" x1="26.724" x2="23.05" y1="16.417" y2="20.635" gradientUnits="userSpaceOnUse"><stop class="d8a511b8h"/><stop offset="1" class="s7zmy3bbc"/></linearGradient><linearGradient id="iemTdde" x1="16.057" x2="16.057" y1="24" y2="27.123" gradientUnits="userSpaceOnUse"><stop class="d10fx2-we"/><stop offset="1" class="k5z_hqbkf"/></linearGradient><linearGradient id="i8Skydd" x1="31.577" x2="28.738" y1="22.729" y2="25" gradientUnits="userSpaceOnUse"><stop offset=".843" class="z8jcilbiv"/><stop offset="1" class="db9swob3z"/></linearGradient><linearGradient id="ihutrNb" x1=".292" x2="3.057" y1="23.688" y2="25.594" gradientUnits="userSpaceOnUse"><stop offset=".838" class="bow-uhbki"/><stop offset="1" class="w2zrvsbfn"/></linearGradient><linearGradient id="ifi9Qle" x1="23.187" x2="19.109" y1="6.792" y2="8.006" gradientUnits="userSpaceOnUse"><stop class="cdx8_7uoq"/><stop offset="1" class="ykszwfj2m"/></linearGradient><linearGradient id="ig47iCe" x1="8.759" x2="12.838" y1="6.792" y2="8.006" gradientUnits="userSpaceOnUse"><stop class="igtkub0ki"/><stop offset="1" class="rhiqvbz0f"/></linearGradient><filter id="ixGW1ob" width="4.262" height="4.262" x="20.056" y="25.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.145098 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9104"/></filter><filter id="i12IbWc" width="4.25" height="4.25" x="8.056" y="25.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.145098 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9104"/></filter><filter id="i1jzAzc" width="12.756" height="6.983" x="9.622" y="2.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.168627 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9104"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.352941 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9104" result="effect2_innerShadow_18_9104"/></filter><filter id="i7lyKCe" width="4.972" height="3.066" x="17.114" y="5.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9104" stdDeviation=".1"/></filter><filter id="innAZec" width="5.718" height="3.505" x="9.66" y="5.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9104" stdDeviation=".2"/></filter><filter id="i4j7Woc" width="10.805" height="4.006" x="10.651" y="7.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.341176 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9104"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.160784 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9104" result="effect2_innerShadow_18_9104"/></filter><filter id="irTSGMe" width="29.004" height="6.588" x="2.056" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.627451 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9104"/></filter><filter id="iEBnQqe" width="29.677" height="9.087" x="1.368" y="9.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9104" stdDeviation=".75"/></filter><filter id="ipY0gdd" width="7" height="12.149" x="21.556" y="13.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9104" stdDeviation=".15"/></filter><filter id="ikmGdde" width="6.25" height="11.399" x="21.806" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.219608 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9104"/></filter><filter id="iUJcXgd" width="4.694" height="4.7" x="4.712" y="15.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9104" stdDeviation=".1"/></filter><filter id="iXm4ARc" width="4.294" height="4.3" x="4.762" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.337255 0 0 0 0 0.921569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9104"/></filter><filter id="iWD8hgc" width="4.694" height="4.7" x="13.706" y="15.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9104" stdDeviation=".1"/></filter><filter id="i32bNnd" width="4.294" height="4.3" x="13.756" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.337255 0 0 0 0 0.921569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9104"/></filter><filter id="ifKw6Oe" width="4.294" height="4.3" x="22.75" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.337255 0 0 0 0 0.921569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9104"/></filter><filter id="iqBOFMe" width="4.901" height="3.372" x="17.257" y="2.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9104" stdDeviation=".1"/></filter><filter id="iwcs7nd" width="4.901" height="3.372" x="9.789" y="2.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9104" stdDeviation=".1"/></filter><filter id="iZhp3ye" width="4.398" height="2.395" x="14.058" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.137255 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9104"/></filter><filter id="iPTVIJd" width="4.798" height="2.795" x="13.658" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.282353 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9104"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.137255 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9104" result="effect2_innerShadow_18_9104"/></filter><radialGradient id="iRXn6ud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.04685 17 0 13.432 28)" gradientUnits="userSpaceOnUse"><stop class="w6o-bkbvf"/><stop offset="1" class="uqdtcuiil"/></radialGradient><radialGradient id="iviOk9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68745 -2.22601 0 26.598 25.546)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="svm2a8s_i"/><stop offset="1" class="lba7icbgi"/></radialGradient><radialGradient id="ijFBFMt" cx="0" cy="0" r="1" gradientTransform="matrix(6.7663 -.21595 .03761 1.17847 2.85 26.406)" gradientUnits="userSpaceOnUse"><stop class="g4ad44bvo"/><stop offset="1" class="pk0pmabuh"/></radialGradient><radialGradient id="iZvtRib" cx="0" cy="0" r="1" gradientTransform="rotate(-179.293 14.572 13.185)scale(7.77465 1.5497)" gradientUnits="userSpaceOnUse"><stop class="g4ad44bvo"/><stop offset="1" class="pk0pmabuh"/></radialGradient><radialGradient id="iTN1Kxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.85603 .39534 -.39189 -.84855 18.056 2.392)" gradientUnits="userSpaceOnUse"><stop class="gts9kibhf"/><stop offset="1" class="ifjk4vb0i"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:railway-car" /></template>
<style>
.acgrlfbkw {
  stop-color: var(--svg-color--ff913f, #FF913F);
}

.ang3p5hca {
  stop-color: var(--svg-color--333637, #333637);
}

.aso8ombfu {
  stop-color: var(--svg-color--b36a4d, #B36A4D);
}

.azm5e7afa {
  stop-color: var(--svg-color--553b73, #553B73);
}

.b6jvotbvk {
  d: path("M23.05 16.75a.75.75 0 0 1 .75-.75h2.494a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-.75.75H23.8a.75.75 0 0 1-.75-.75z");
}

.b77po707m {
  d: path("M12.056 28a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

.bow-uhbki {
  stop-color: var(--svg-color--4d9e80, #4D9E80);
}

.brg2tkgdu {
  stop-color: var(--svg-color--ff6648, #FF6648);
}

.bvr577byw {
  stop-color: var(--svg-color--69646f, #69646F);
}

.car3btb1d {
  stop-color: var(--svg-color--323232, #323232);
}

.cdx8_7uoq {
  stop-color: var(--svg-color--68626f, #68626F);
  stop-opacity: 0;
}

.cez_pnbfz {
  stop-color: var(--svg-color--524667, #524667);
}

.d10fx2-we {
  stop-color: var(--svg-color--43c59d, #43C59D);
}

.d6417sbth {
  stop-color: var(--svg-color--7d47a5, #7D47A5);
  stop-opacity: 0;
}

.d8a511b8h {
  stop-color: var(--svg-color--3f7eff, #3F7EFF);
}

.db9swob3z {
  stop-color: var(--svg-color--4bf19a, #4BF19A);
  stop-opacity: 0;
}

.din_jw39f {
  d: path("M11.05 8.994a1 1 0 0 1 1-1h8.006a1 1 0 0 1 1 1V11a1 1 0 0 1-1 1H12.05a1 1 0 0 1-1-1z");
}

.er3apzjdq {
  stop-color: var(--svg-color--ffff59, #FFFF59);
  stop-opacity: 0;
}

.ffg6fcc-q {
  d: path("M5.062 16.75a.75.75 0 0 1 .75-.75h2.494a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-.75.75H5.812a.75.75 0 0 1-.75-.75z");
}

.fhc8pt1md {
  stop-color: var(--svg-color--5be6b3, #5BE6B3);
}

.ft5dv1b6b {
  fill: none;
}

.fy8_v9-pv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m17.557 3.201l4.3 2.772");
}

.fza5w6blg {
  fill: var(--svg-color--3e3746, #3E3746);
  d: path("M14.058 2.998c0-.551.447-.998.998-.998h2.002a.998.998 0 1 1 0 1.995h-2.002a1 1 0 0 1-.998-.997");
}

.g03-hq_oj {
  stop-color: var(--svg-color--7d47a5, #7D47A5);
}

.g4ad44bvo {
  stop-color: var(--svg-color--7696d5, #7696D5);
}

.gb5wo06fx {
  stop-color: var(--svg-color--33dc7a, #33DC7A);
}

.gts9kibhf {
  stop-color: var(--svg-color--6b5f77, #6B5F77);
}

.hvgiq9rka {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M5.062 16.75a.75.75 0 0 1 .75-.75h2.494a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-.75.75H5.812a.75.75 0 0 1-.75-.75z");
}

.i_y9pybez {
  stop-color: var(--svg-color--e08d38, #E08D38);
}

.i6m30lbyf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m14.39 3.201l-4.301 2.772");
}

.i8rjt71vj {
  stop-color: var(--svg-color--7c787f, #7C787F);
}

.idibcljtc {
  stop-color: var(--svg-color--ffe15b, #FFE15B);
}

.ifjk4vb0i {
  stop-color: var(--svg-color--6b5f77, #6B5F77);
  stop-opacity: 0;
}

.igtkub0ki {
  stop-color: var(--svg-color--70627f, #70627F);
  stop-opacity: 0;
}

.jsyw4i05b {
  stop-color: var(--svg-color--323232, #323232);
  stop-opacity: 0;
}

.juc9gobzt {
  d: path("M2.055 12.97H30.06V24H2.055z");
}

.k5z_hqbkf {
  stop-color: var(--svg-color--3a7c92, #3A7C92);
}

.kchxs-spv {
  stop-color: var(--svg-color--4d4863, #4D4863);
}

.kfkl73-ej {
  stop-color: var(--svg-color--41d291, #41D291);
}

.l6ck1jb0y {
  stop-color: var(--svg-color--5de5b5, #5DE5B5);
}

.lba7icbgi {
  stop-color: var(--svg-color--2c2639, #2C2639);
  stop-opacity: 0;
}

.mu2ajvbzw {
  stop-color: var(--svg-color--47444b, #47444B);
  stop-opacity: 0;
}

.mvqyt7bpa {
  stop-color: var(--svg-color--ffff59, #FFFF59);
}

.n27p4fbpl {
  stop-color: var(--svg-color--e08d38, #E08D38);
  stop-opacity: 0;
}

.n7z1y9sbs {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M14.056 16.75a.75.75 0 0 1 .75-.75H17.3a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-.75.75h-2.494a.75.75 0 0 1-.75-.75z");
}

.nbrdrbbnx {
  d: path("M2.056 13.294A3.294 3.294 0 0 1 5.35 10h21.416a3.294 3.294 0 0 1 0 6.588H5.35a3.294 3.294 0 0 1-3.294-3.294");
}

.nn_d8qbth {
  stop-color: var(--svg-color--463655, #463655);
}

.nrqb1q2xi {
  stop-color: var(--svg-color--4d4863, #4D4863);
  stop-opacity: 0;
}

.o14l7lb8x {
  d: path("M3.62 13.545v-.16l-.092-.13c-.213-.3-.23-.845.055-1.376c.273-.508.763-.878 1.38-.878h22.063c.69 0 1.212.283 1.552.716c.346.441.525 1.068.451 1.775l-.003.026v.026c0 .646-.366 1.276-.97 1.763c-.605.487-1.39.781-2.105.781H6.164a2.544 2.544 0 0 1-2.543-2.544Z");
}

.o7oqkyrpt {
  d: path("M24.068 28a2.006 2.006 0 1 1-4.012 0a2.006 2.006 0 0 1 4.011 0");
}

.olcww3buq {
  stop-color: var(--svg-color--311b43, #311B43);
}

.outpr4b2k {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M22.056 14.75a.75.75 0 0 1 .75-.75h4.5a.75.75 0 0 1 .75.75v9.649a.75.75 0 0 1-.75.75h-4.5a.75.75 0 0 1-.75-.75z");
}

.p8vxosb4r {
  d: path("M22.056 14.75a.75.75 0 0 1 .75-.75h4.5a.75.75 0 0 1 .75.75v9.649a.75.75 0 0 1-.75.75h-4.5a.75.75 0 0 1-.75-.75z");
}

.pfmgngbwj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m17.414 8.42l4.372-2.467");
}

.pk0pmabuh {
  stop-color: var(--svg-color--7696d5, #7696D5);
  stop-opacity: 0;
}

.pqqpf9bwm {
  stop-color: var(--svg-color--ffc856, #FFC856);
}

.pwx7_gbfx {
  d: path("M5.059 24.453a.5.5 0 0 1 .5-.5h20.997a.5.5 0 0 1 .5.5V27.5a.5.5 0 0 1-.5.5H5.559a.5.5 0 0 1-.5-.5z");
}

.qlx4r-auh {
  stop-color: var(--svg-color--51f993, #51F993);
}

.qtruv094h {
  stop-color: var(--svg-color--ff8b4b, #FF8B4B);
}

.r27hd1bts {
  stop-color: var(--svg-color--fff858, #FFF858);
}

.ra19axbdw {
  stop-color: var(--svg-color--3d3b40, #3D3B40);
}

.rhiqvbz0f {
  stop-color: var(--svg-color--70627f, #70627F);
}

.s7zmy3bbc {
  stop-color: var(--svg-color--37a4ff, #37A4FF);
}

.s9-t5iurb {
  stop-color: var(--svg-color--5be6b3, #5BE6B3);
  stop-opacity: 0;
}

.smuqz5b4e {
  stop-color: var(--svg-color--7c787f, #7C787F);
  stop-opacity: 0;
}

.svm2a8s_i {
  stop-color: var(--svg-color--2c2639, #2C2639);
}

.tauy1bbeu {
  d: path("M14.058 2.998c0-.551.447-.998.998-.998h2.002a.998.998 0 1 1 0 1.995h-2.002a1 1 0 0 1-.998-.997");
}

.tjphb4b-p {
  stop-color: var(--svg-color--51f993, #51F993);
  stop-opacity: 0;
}

.tq8y3446b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.878 8.458L10.16 5.953");
}

.u6slzqdib {
  stop-color: var(--svg-color--ff913f, #FF913F);
  stop-opacity: 0;
}

.uqdtcuiil {
  stop-color: var(--svg-color--7c6595, #7C6595);
  stop-opacity: 0;
}

.v51qg7trj {
  stop-color: var(--svg-color--807a87, #807A87);
}

.vw5syu5st {
  fill-rule: evenodd;
  d: path("M2.055 24v1a1 1 0 0 0 1 1H29.06a1 1 0 0 0 1-1v-1z");
}

.w2zrvsbfn {
  stop-color: var(--svg-color--4d9e80, #4D9E80);
  stop-opacity: 0;
}

.w6o-bkbvf {
  stop-color: var(--svg-color--7d6496, #7D6496);
}

.xmv3_lblk {
  stop-color: var(--svg-color--45434b, #45434B);
}

.y410z-b5s {
  stop-color: var(--svg-color--553b73, #553B73);
  stop-opacity: 0;
}

.ykszwfj2m {
  stop-color: var(--svg-color--68626f, #68626F);
}

.z7cptabsg {
  fill-rule: evenodd;
  d: path("M14.32 2.727a.5.5 0 0 1 .27-.08h2.958a.5.5 0 0 1 .277.084l4.33 2.872a.5.5 0 0 1-.043.858l-5.106 2.711a.5.5 0 0 1-.235.059h-1.364a.5.5 0 0 1-.228-.056l-5.285-2.71a.5.5 0 0 1-.042-.866zm.418.92L11.342 5.83a.15.15 0 0 0 .012.26l4.174 2.14h1.119l4.032-2.14a.15.15 0 0 0 .012-.257l-3.293-2.186z");
}

.z8jcilbiv {
  stop-color: var(--svg-color--4bf19a, #4BF19A);
}

.zkluhub5k {
  stop-color: var(--svg-color--eeb542, #EEB542);
}

.zl6genb3b {
  d: path("M14.056 16.75a.75.75 0 0 1 .75-.75H17.3a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-.75.75h-2.494a.75.75 0 0 1-.75-.75z");
}

.zxd_fyb_s {
  stop-color: var(--svg-color--47444b, #47444B);
}

</style>
