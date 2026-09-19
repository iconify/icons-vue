<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iU0Tt8c)" class="f9luxtbjz"/><path fill="url(#iZHGuFd)" class="f9luxtbjz"/><path fill="url(#iSZbsQb)" class="f9luxtbjz"/><path fill="url(#i3wfmQc)" class="f9luxtbjz"/><g filter="url(#ivhQScc)"><path fill="url(#ilERfeb)" class="egqt0l0ru"/></g><path fill="url(#iHZVFIc)" class="smqi9qbwv"/><path fill="url(#iD21PUb)" class="smqi9qbwv"/><path fill="url(#iVQIxJc)" class="smqi9qbwv"/><g filter="url(#ihJfAjc)"><path fill="url(#i9p0x7b)" class="r_di0e9yj"/><path fill="url(#ibizxNc)" class="r_di0e9yj"/></g><g filter="url(#icjaqRc)"><path fill="url(#i7DMEIe)" class="mjgc579it"/></g><g filter="url(#iO6WoVd)"><path fill="url(#iwGyj9v)" class="ck2sytb3p"/></g><path fill="url(#iS0r7Ed)" class="ck2sytb3p"/><path fill="url(#isCt3ic)" class="ck2sytb3p"/><g filter="url(#iPhcEqd)"><path fill="url(#iWkdiAn)" class="grmpoxb1o"/></g><g filter="url(#i3zJCBe)"><path fill="url(#imcouHv)" class="fhe7wiovn"/><path fill="url(#iX1crxc)" class="fhe7wiovn"/></g><g filter="url(#i31w9Me)"><path fill="url(#iPyGEge)" class="u3-uolr6c"/><path fill="url(#iPG1ZJc)" class="u3-uolr6c"/><path fill="url(#iFND16d)" class="u3-uolr6c"/></g><g filter="url(#iYGHvZc)"><rect fill="url(#i1PI2Md)" class="eko8ufr7k"/></g><g filter="url(#iH5goee)"><rect fill="url(#ihkNLxd)" class="t20dpkbmr"/></g><g filter="url(#iaeZedT)"><rect fill="url(#izCpF8d)" class="yoyfe4-_s"/></g><g filter="url(#iWtQEqd)"><rect fill="url(#iLM8yob)" class="hht_pdbra"/></g><g filter="url(#iy9Lvse)"><path fill="url(#ilxpCCN)" class="oltnr_b2c"/></g><path fill="url(#iQ1O6Lc)" class="oltnr_b2c"/><path fill="url(#iI4UMpc)" class="oltnr_b2c"/><path fill="url(#iAC4z8b)" class="h6i9zpb8s"/><path fill="url(#isCBODb)" class="h6i9zpb8s"/><g filter="url(#ir8vcSd)"><path clip-rule="evenodd" class="cjnsn4bkz"/></g><g filter="url(#iknzmNb)"><path class="l7-wgdsae"/></g><g filter="url(#i506YBi)"><path fill="url(#i9Vnzbd)" class="hny7abccr"/><path fill="url(#ibWuvOs)" class="hny7abccr"/><path fill="url(#iFY7wSd)" class="hny7abccr"/></g><g filter="url(#iKMFNQb)"><path stroke="url(#i28eo0b)" class="ao--ay63w"/></g><g filter="url(#iijd1Nb)"><path stroke="url(#i9PyEcb)" class="g1l1jikyi"/></g></g><defs><linearGradient id="iU0Tt8c" x1="8.359" x2="3" y1="20.872" y2="20.872" gradientUnits="userSpaceOnUse"><stop offset=".069" class="rpoop2bll"/><stop offset=".283" class="vhzcczbnc"/></linearGradient><linearGradient id="iZHGuFd" x1="3" x2="3.715" y1="27.469" y2="27.469" gradientUnits="userSpaceOnUse"><stop class="wrtyyh6jw"/><stop offset="1" class="vb6lqwbtd"/></linearGradient><linearGradient id="iSZbsQb" x1="4.246" x2="4.246" y1="11.75" y2="12.242" gradientUnits="userSpaceOnUse"><stop offset=".434" class="zkc8vx7zp"/><stop offset="1" class="umvc5bb9e"/></linearGradient><linearGradient id="ilERfeb" x1="3.778" x2="7.278" y1="18.01" y2="18.01" gradientUnits="userSpaceOnUse"><stop class="j4h895cqa"/><stop offset="1" class="i16vxr2vj"/></linearGradient><linearGradient id="iHZVFIc" x1="27.371" x2="21.465" y1="20.51" y2="20.51" gradientUnits="userSpaceOnUse"><stop class="j_ge80vxv"/><stop offset="1" class="okyxwjbay"/></linearGradient><linearGradient id="iD21PUb" x1="23.643" x2="23.643" y1="11.881" y2="12.278" gradientUnits="userSpaceOnUse"><stop class="xxo9j9bcz"/><stop offset="1" class="yt8jkibkd"/></linearGradient><linearGradient id="iVQIxJc" x1="29" x2="28.366" y1="24.75" y2="24.75" gradientUnits="userSpaceOnUse"><stop class="cjulmij-n"/><stop offset="1" class="mk3umhn7m"/></linearGradient><linearGradient id="i9p0x7b" x1="16.002" x2="16.002" y1="10.007" y2="12.01" gradientUnits="userSpaceOnUse"><stop class="y81cn3bck"/><stop offset="1" class="njfzecc_u"/></linearGradient><linearGradient id="i7DMEIe" x1="6.26" x2="6.26" y1="25.5" y2="29.578" gradientUnits="userSpaceOnUse"><stop class="rdmzhkb8y"/><stop offset="1" class="tf08j1b1q"/></linearGradient><linearGradient id="iwGyj9v" x1="16" x2="16" y1="1.5" y2="30.01" gradientUnits="userSpaceOnUse"><stop class="hsts_cbib"/><stop offset="1" class="l2exuobdf"/></linearGradient><linearGradient id="iS0r7Ed" x1="14.539" x2="14.539" y1="30.803" y2="27.882" gradientUnits="userSpaceOnUse"><stop class="qd0vyqf9z"/><stop offset="1" class="ly034f_mg"/></linearGradient><linearGradient id="isCt3ic" x1="23.957" x2="23.094" y1="22.918" y2="22.918" gradientUnits="userSpaceOnUse"><stop class="r2s0i1bwe"/><stop offset="1" class="e76e_4bhx"/></linearGradient><linearGradient id="iWkdiAn" x1="25.232" x2="28" y1="18.01" y2="18.01" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="imcouHv" x1="13.002" x2="18.991" y1="26.975" y2="26.975" gradientUnits="userSpaceOnUse"><stop class="dn_h72bxs"/><stop offset="1" class="cwrj5u9cf"/></linearGradient><linearGradient id="iX1crxc" x1="13" x2="14.328" y1="28.714" y2="28.714" gradientUnits="userSpaceOnUse"><stop class="mw58gzpvt"/><stop offset="1" class="xo2-n7btn"/></linearGradient><linearGradient id="iPyGEge" x1="16.001" x2="16.001" y1="1.997" y2="4" gradientUnits="userSpaceOnUse"><stop class="y81cn3bck"/><stop offset="1" class="njfzecc_u"/></linearGradient><linearGradient id="iPG1ZJc" x1="16" x2="16" y1="1.884" y2="3" gradientUnits="userSpaceOnUse"><stop class="q_bu7ruzs"/><stop offset="1" class="z4pme-tqw"/></linearGradient><linearGradient id="i1PI2Md" x1="11.382" x2="15.053" y1="16.497" y2="16.497" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="ihkNLxd" x1="17.329" x2="21" y1="16.497" y2="16.497" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="izCpF8d" x1="11.382" x2="15.053" y1="20.462" y2="20.462" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="iLM8yob" x1="17.329" x2="21" y1="20.462" y2="20.462" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="ilxpCCN" x1="6.027" x2="10.031" y1="27.003" y2="27.003" gradientUnits="userSpaceOnUse"><stop class="y2q5-_b-y"/><stop offset="1" class="ih-oiwbuy"/></linearGradient><linearGradient id="iI4UMpc" x1="10.028" x2="9.36" y1="28.202" y2="28.202" gradientUnits="userSpaceOnUse"><stop class="u4qyohedc"/><stop offset="1" class="pi_-c0b3w"/></linearGradient><linearGradient id="i9Vnzbd" x1="18.194" x2="13.207" y1="7.561" y2="13.844" gradientUnits="userSpaceOnUse"><stop class="j_hb9zbrh"/><stop offset="1" class="mb-n0sjqv"/></linearGradient><linearGradient id="ibWuvOs" x1="11.907" x2="13.3" y1="12.99" y2="12.99" gradientUnits="userSpaceOnUse"><stop class="y_px18b2r"/><stop offset="1" class="xwn6-4jdg"/></linearGradient><filter id="ivhQScc" width="3.55" height="6.4" x="3.75" y="14.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.85098 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6232" result="effect2_innerShadow_18_6232"/></filter><filter id="ihJfAjc" width="28.25" height="2.25" x="2" y="9.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.184314 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/></filter><filter id="icjaqRc" width="5.48" height="6.078" x="3.52" y="24.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6232" stdDeviation=".5"/></filter><filter id="iO6WoVd" width="16.5" height="26.11" x="8" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.356863 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/></filter><filter id="iPhcEqd" width="3.55" height="6.4" x="24.75" y="14.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6232" result="effect2_innerShadow_18_6232"/></filter><filter id="i3zJCBe" width="6.5" height="6.565" x="12.5" y="23.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0901961 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/></filter><filter id="i31w9Me" width="18.25" height="2.25" x="7" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.184314 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/></filter><filter id="iYGHvZc" width="4.529" height="3.402" x="10.824" y="14.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6232" result="effect2_innerShadow_18_6232"/></filter><filter id="iH5goee" width="4.529" height="3.402" x="16.771" y="14.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6232" result="effect2_innerShadow_18_6232"/></filter><filter id="iaeZedT" width="4.529" height="3.402" x="10.824" y="18.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6232" result="effect2_innerShadow_18_6232"/></filter><filter id="iWtQEqd" width="4.529" height="3.402" x="16.771" y="18.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6232" result="effect2_innerShadow_18_6232"/></filter><filter id="iy9Lvse" width="4.25" height="6" x="6.028" y="24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.247059 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/></filter><filter id="ir8vcSd" width="9.535" height="9" x="11.007" y="4.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6232" stdDeviation=".25"/></filter><filter id="iknzmNb" width="2.758" height="4.667" x="17.713" y="4.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.533333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.913725 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6232" result="effect2_innerShadow_18_6232"/></filter><filter id="i506YBi" width="8.15" height="7.16" x="11.64" y="5.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.403922 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6232"/></filter><filter id="iKMFNQb" width="2.368" height="4.569" x="17.298" y="6.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6232" stdDeviation=".1"/></filter><filter id="iijd1Nb" width="2.493" height="3.287" x="13.061" y="9.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6232" stdDeviation=".1"/></filter><radialGradient id="i3wfmQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.25 2.15625 0 6.66 30.25)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="wqqjsn8cg"/><stop offset="1" class="g910h8bnu"/></radialGradient><radialGradient id="ibizxNc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68682 .67489 -1.26637 -3.16519 8.677 11.01)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="huoq88o_b"/><stop offset="1" class="kz4crsrxh"/></radialGradient><radialGradient id="iFND16d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15307 .8349 -.9044 -1.24907 25 2.165)" gradientUnits="userSpaceOnUse"><stop class="eawq8ibpn"/><stop offset="1" class="rp9v9hbtr"/></radialGradient><radialGradient id="iQ1O6Lc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.96458 1.83645 0 9.11 30)" gradientUnits="userSpaceOnUse"><stop class="h6ow0ob8b"/><stop offset="1" class="g32k5qb5i"/></radialGradient><radialGradient id="iAC4z8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.56776 0 0 .6958 7.462 25.497)" gradientUnits="userSpaceOnUse"><stop class="hb6lo3b_c"/><stop offset="1" class="jjhxjrbth"/></radialGradient><radialGradient id="isCBODb" cx="0" cy="0" r="1" gradientTransform="matrix(2.73071 0 0 1.34935 7.028 25.5)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="sm6qw3brr"/><stop offset="1" class="j01na4b8k"/></radialGradient><radialGradient id="iFY7wSd" cx="0" cy="0" r="1" gradientTransform="rotate(20.829 -25.373 41.983)scale(1.53801 .267)" gradientUnits="userSpaceOnUse"><stop class="z3m48l0qk"/><stop offset="1" class="wgspgp2hr"/></radialGradient><radialGradient id="i28eo0b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08506 .71875 -2.27509 -3.43455 19.567 8.063)" gradientUnits="userSpaceOnUse"><stop class="q9cfrhb_b"/><stop offset="1" class="cps-ncbmi"/></radialGradient><radialGradient id="i9PyEcb" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -.67187 1.92108 2.32317 13.676 11.313)" gradientUnits="userSpaceOnUse"><stop class="z47zh6bsy"/><stop offset="1" class="lgie2pkyy"/></radialGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:post-office" /></template>
<style>
.ao--ay63w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.598 6.547c.802.375 2.247 1.694 1.61 3.969");
}

.cjnsn4bkz {
  fill: var(--svg-color--755e70, #755E70);
  fill-rule: evenodd;
  d: path("M19.289 7.177c0-.66.254-1.3.713-1.77c.088-.09.02-.26-.107-.27l-2.2.01a.151.151 0 0 0-.107.26c.45.46.712 1.084.723 1.73a3.4 3.4 0 0 0-2.415-1.01c-1.886 0-3.421 1.57-3.421 3.51c0 .98.39 1.87 1.046 2.5h-1.525a.496.496 0 0 0-.49.5c0 .28.226.5.49.5l3.91-.01c.166 0 .333-.01.489-.04c1.506-.21 2.689-1.44 2.894-2.97c.03-.16.039-.33.039-.5a4 4 0 0 0-.04-.5zm-5.837 2.46c0 1.38 1.105 2.5 2.454 2.5s2.444-1.13 2.444-2.51s-1.104-2.5-2.454-2.5c-1.349 0-2.444 1.13-2.444 2.51");
}

.cjulmij-n {
  stop-color: var(--svg-color--dfdbe1, #DFDBE1);
}

.ck2sytb3p {
  d: path("M8 4v26.01h16V4z");
}

.cps-ncbmi {
  stop-color: var(--svg-color--fffe7b, #FFFE7B);
  stop-opacity: 0;
}

.cwrj5u9cf {
  stop-color: var(--svg-color--473d4f, #473D4F);
}

.dn_h72bxs {
  stop-color: var(--svg-color--524163, #524163);
}

.e76e_4bhx {
  stop-color: var(--svg-color--d9d4db, #D9D4DB);
  stop-opacity: 0;
}

.eawq8ibpn {
  stop-color: var(--svg-color--ffad6b, #FFAD6B);
}

.egqt0l0ru {
  d: path("M6.39 21.01H4.61c-.34 0-.61-.27-.61-.61v-4.78c0-.34.27-.61.61-.61h1.78c.34 0 .61.27.61.61v4.78c0 .34-.27.61-.61.61");
}

.eko8ufr7k {
  width: 3.979px;
  height: 3.002px;
  x: 11.074px;
  y: 14.997px;
  rx: 0.5px;
}

.f9luxtbjz {
  d: path("M21 11.01H3v19h18z");
}

.fhe7wiovn {
  d: path("M18.99 30.01H13v-4.68c0-.768.609-1.385 1.368-1.385h3.254A1.39 1.39 0 0 1 19 25.34v4.67z");
}

.ft5dv1b6b {
  fill: none;
}

.g1l1jikyi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.364 9.422c-.037.666.29 2.137 1.89 2.687");
}

.g32k5qb5i {
  stop-color: var(--svg-color--ff874d, #FF874D);
  stop-opacity: 0;
}

.g910h8bnu {
  stop-color: var(--svg-color--78637c, #78637C);
  stop-opacity: 0;
}

.grmpoxb1o {
  d: path("M27.39 21.01h-1.78c-.34 0-.61-.27-.61-.61v-4.78c0-.34.27-.61.61-.61h1.78c.34 0 .61.27.61.61v4.78c0 .34-.27.61-.61.61");
}

.h6i9zpb8s {
  d: path("M8.528 26h-1c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h1c.28 0 .5.22.5.5s-.22.5-.5.5");
}

.h6ow0ob8b {
  stop-color: var(--svg-color--ff874d, #FF874D);
}

.hb6lo3b_c {
  stop-color: var(--svg-color--6a567a, #6A567A);
}

.hht_pdbra {
  width: 3.979px;
  height: 3.002px;
  x: 17.021px;
  y: 18.961px;
  rx: 0.5px;
}

.hny7abccr {
  d: path("M18.63 7.02a3.506 3.506 0 0 0-6 2.47c0 .98.4 1.87 1.07 2.5h-1.56c-.28 0-.5.23-.5.5c0 .28.23.5.5.5l4-.01c.17 0 .34-.01.5-.04a3.48 3.48 0 0 0 2.96-2.97c.03-.16.04-.33.04-.5a3.54 3.54 0 0 0-1.01-2.45m-2.49 4.97a2.51 2.51 0 0 1-2.51-2.5a2.51 2.51 0 0 1 2.5-2.51a2.51 2.51 0 0 1 2.51 2.5a2.51 2.51 0 0 1-2.5 2.51");
}

.hsts_cbib {
  stop-color: var(--svg-color--af9faa, #AF9FAA);
}

.huoq88o_b {
  stop-color: var(--svg-color--a33f2c, #A33F2C);
}

.i16vxr2vj {
  stop-color: var(--svg-color--3c99e4, #3C99E4);
}

.ih-oiwbuy {
  stop-color: var(--svg-color--ff854c, #FF854C);
}

.j_ge80vxv {
  stop-color: var(--svg-color--bfb6c6, #BFB6C6);
}

.j_hb9zbrh {
  stop-color: var(--svg-color--ffd959, #FFD959);
}

.j01na4b8k {
  stop-color: var(--svg-color--1d1624, #1D1624);
}

.j4h895cqa {
  stop-color: var(--svg-color--50c5ff, #50C5FF);
}

.jjhxjrbth {
  stop-color: var(--svg-color--3e2a4e, #3E2A4E);
}

.kz4crsrxh {
  stop-color: var(--svg-color--a33f2c, #A33F2C);
  stop-opacity: 0;
}

.l2exuobdf {
  stop-color: var(--svg-color--bcb1c2, #BCB1C2);
}

.l7-wgdsae {
  fill: var(--svg-color--ffca4a, #FFCA4A);
  d: path("M20.33 5.26c-.47.47-.73 1.11-.73 1.77v2.627l-.99-.778l-.01-1.849c0-.66-.27-1.3-.74-1.77a.15.15 0 0 1 .11-.26l2.25-.01c.13.01.2.18.11.27");
}

.lgie2pkyy {
  stop-color: var(--svg-color--ffd26b, #FFD26B);
  stop-opacity: 0;
}

.ly034f_mg {
  stop-color: var(--svg-color--b8adc0, #B8ADC0);
  stop-opacity: 0;
}

.mb-n0sjqv {
  stop-color: var(--svg-color--f5aa4a, #F5AA4A);
}

.mjgc579it {
  d: path("M8 29.578v-2.364c0-.472-.191-.9-.505-1.217A1.78 1.78 0 0 0 6.26 25.5c-.957 0-1.74.762-1.74 1.713v2.365z");
}

.mk3umhn7m {
  stop-color: var(--svg-color--dfdbe1, #DFDBE1);
  stop-opacity: 0;
}

.mw58gzpvt {
  stop-color: var(--svg-color--66507e, #66507E);
}

.njfzecc_u {
  stop-color: var(--svg-color--e23f3c, #E23F3C);
}

.okyxwjbay {
  stop-color: var(--svg-color--a297a0, #A297A0);
}

.oltnr_b2c {
  d: path("M10.028 26v4h-1v-.45c0-.3-.25-.55-.55-.55h-.9c-.3 0-.55.25-.55.55V30h-1v-4a2 2 0 0 1 2-2c.55 0 1.05.22 1.42.58c.36.37.58.87.58 1.42");
}

.pi_-c0b3w {
  stop-color: var(--svg-color--ffa658, #FFA658);
  stop-opacity: 0;
}

.q_bu7ruzs {
  stop-color: var(--svg-color--ff9853, #FF9853);
}

.q9cfrhb_b {
  stop-color: var(--svg-color--fffe7b, #FFFE7B);
}

.qd0vyqf9z {
  stop-color: var(--svg-color--b8adc0, #B8ADC0);
}

.r_di0e9yj {
  d: path("M2 11.01c0-.55.45-1 1-1h26c.55 0 1 .45 1 1s-.45 1-1 1H3c-.55 0-1-.45-1-1");
}

.r2s0i1bwe {
  stop-color: var(--svg-color--d9d4db, #D9D4DB);
}

.rdmzhkb8y {
  stop-color: var(--svg-color--6e5d70, #6E5D70);
}

.rp9v9hbtr {
  stop-color: var(--svg-color--ffad6b, #FFAD6B);
  stop-opacity: 0;
}

.rpoop2bll {
  stop-color: var(--svg-color--645768, #645768);
}

.sm6qw3brr {
  stop-color: var(--svg-color--1d1624, #1D1624);
  stop-opacity: 0;
}

.smqi9qbwv {
  d: path("M29 11.01H11v19h18z");
}

.t20dpkbmr {
  width: 3.979px;
  height: 3.002px;
  x: 17.021px;
  y: 14.997px;
  rx: 0.5px;
}

.tf08j1b1q {
  stop-color: var(--svg-color--77637d, #77637D);
}

.ttzh61lgu {
  stop-color: var(--svg-color--58e6ff, #58E6FF);
}

.u3-uolr6c {
  d: path("M7 3c0-.55.45-1 1-1h16c.55 0 1 .45 1 1s-.45 1-1 1H8c-.55 0-1-.44-1-1");
}

.u4qyohedc {
  stop-color: var(--svg-color--ffa658, #FFA658);
}

.umvc5bb9e {
  stop-color: var(--svg-color--714960, #714960);
  stop-opacity: 0;
}

.vb6lqwbtd {
  stop-color: var(--svg-color--79757d, #79757D);
  stop-opacity: 0;
}

.vhzcczbnc {
  stop-color: var(--svg-color--978d9b, #978D9B);
}

.w3s_subrj {
  stop-color: var(--svg-color--44b8ff, #44B8FF);
}

.wgspgp2hr {
  stop-color: var(--svg-color--b66e1b, #B66E1B);
  stop-opacity: 0;
}

.wqqjsn8cg {
  stop-color: var(--svg-color--78637c, #78637C);
}

.wrtyyh6jw {
  stop-color: var(--svg-color--79757d, #79757D);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xo2-n7btn {
  stop-color: var(--svg-color--66507e, #66507E);
  stop-opacity: 0;
}

.xwn6-4jdg {
  stop-color: var(--svg-color--f1a443, #F1A443);
  stop-opacity: 0;
}

.xxo9j9bcz {
  stop-color: var(--svg-color--875c74, #875C74);
}

.y_px18b2r {
  stop-color: var(--svg-color--f1a443, #F1A443);
}

.y2q5-_b-y {
  stop-color: var(--svg-color--ff5d4e, #FF5D4E);
}

.y81cn3bck {
  stop-color: var(--svg-color--ff8946, #FF8946);
}

.yoyfe4-_s {
  width: 3.979px;
  height: 3.002px;
  x: 11.074px;
  y: 18.961px;
  rx: 0.5px;
}

.yt8jkibkd {
  stop-color: var(--svg-color--875c74, #875C74);
  stop-opacity: 0;
}

.z3m48l0qk {
  stop-color: var(--svg-color--b66e1b, #B66E1B);
}

.z47zh6bsy {
  stop-color: var(--svg-color--ffd26b, #FFD26B);
}

.z4pme-tqw {
  stop-color: var(--svg-color--ff9853, #FF9853);
  stop-opacity: 0;
}

.zkc8vx7zp {
  stop-color: var(--svg-color--714960, #714960);
}

</style>
