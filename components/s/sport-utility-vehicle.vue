<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iB6Gekc)" class="urizi4z9f"/><path fill="url(#iCUhdvc)" class="urizi4z9f"/><path fill="url(#iG7dwOI)" class="urizi4z9f"/><path fill="url(#i5drZGI)" class="w6bruhbqq"/><path fill="url(#iU3htGb)" class="h-i7qkb7x"/><path fill="url(#ifkQ4ne)" class="irzbceozn"/><path fill="url(#ifAO1tc)" class="irzbceozn"/><path fill="url(#iC8NL5b)" class="irzbceozn"/><path fill="url(#iFfqbYc)" class="dohadmbkv"/><path fill="url(#iq0SSNr)" class="w_rdembmv"/><path fill="url(#iJ0lnEU)" class="vpbxmjbhw"/><path fill="url(#iHjNUrl)" class="vpbxmjbhw"/><path fill="url(#iQqZBib)" class="vpbxmjbhw"/><g filter="url(#i3TljRd)"><path stroke="url(#iSnOvYd)" class="tdco28z3x"/></g><g filter="url(#izHcphb)"><path fill="url(#iIn1cud)" clip-rule="evenodd" class="q-tit6owl"/></g><path fill="url(#iyCdfqb)" class="hm39t_bvx"/><path fill="url(#iAB65Ae)" class="hm39t_bvx"/><path fill="url(#ipfoAlb)" class="hm39t_bvx"/><g filter="url(#itiIX9x)"><path stroke="url(#izzKPyb)" class="gvb1prbhz"/></g><path fill="url(#is14YGd)" class="xy2m52gpe"/><path fill="url(#iHqcfKY)" class="xy2m52gpe"/><g filter="url(#ikg5ubc)"><path fill="url(#i8dLzLF)" class="lr4hy5mvm"/><path fill="url(#iR0oANe)" class="lr4hy5mvm"/></g><g filter="url(#iEsUn5c)"><path stroke="url(#iu5LUZO)" class="ifzq-cb-g"/></g><g filter="url(#i5tkMQd)"><path class="eknwvzbam"/></g><g filter="url(#i4xHdWd)"><path fill="url(#iwtf2Ld)" class="zqxissixt"/><path fill="url(#iulrIad)" class="zqxissixt"/></g><g filter="url(#irpsmke)"><path class="vlaf3zbli"/></g><g filter="url(#i6xSGqb)"><path stroke="url(#im58Bzc)" class="wqpsnotos"/></g><path fill="url(#ik1Elce)" class="ct8xv2pis"/><path fill="url(#iJ0G90d)" class="ct8xv2pis"/><path fill="url(#iIQzQ6k)" class="ct8xv2pis"/><path fill="url(#iDpo6ee)" class="a-yymcc9i"/><path fill="url(#i4LsBPv)" class="a-yymcc9i"/><path fill="url(#iVZ34Jc)" class="a-yymcc9i"/><path fill="url(#ioAU7Wc)" class="a-yymcc9i"/><g filter="url(#iRFCL7c)"><path stroke="url(#ioczlFc)" class="we_4yceiw"/></g><path fill="url(#iRCm8bc)" class="suhfdvqdu"/><g filter="url(#iIFEFOe)"><path fill="url(#ijbIZLd)" class="dvqju6b-r"/><path fill="url(#iMVuK9b)" class="dvqju6b-r"/></g><g filter="url(#i70Ikae)"><path fill="url(#iXEyFZb)" class="b9uxenb-x"/><path fill="url(#iVmoEld)" class="b9uxenb-x"/></g><path fill="url(#ijHtZtb)" class="irdv1gcrv"/><path fill="url(#iaoo7eb)" class="f7539-b8r"/><path fill="url(#i7aqseb)" class="f7539-b8r"/><path fill="url(#iF6S1ze)" class="h6oz-gzel"/><path fill="url(#iw3FWee)" class="x0rb78w3d"/><path fill="url(#iZMScKa)" class="zo6q6xbjo"/><path fill="url(#igSzCEc)" class="iuijv4b4f"/><g filter="url(#iIvqrFd)"><path stroke="url(#ilupUWb)" class="u6bl05q2o"/></g><g filter="url(#iupAo8V)"><path stroke="url(#iymEUid)" class="yiwb9d3rs"/></g><path fill="url(#iIDyOed)" clip-rule="evenodd" class="dsj9mwt1u"/><path fill="url(#iK9PnTF)" clip-rule="evenodd" class="dsj9mwt1u"/><defs><linearGradient id="iB6Gekc" x1="25.985" x2="12.985" y1="8.005" y2="8.005" gradientUnits="userSpaceOnUse"><stop class="bvs036byu"/><stop offset="1" class="m9a774bcn"/></linearGradient><linearGradient id="iG7dwOI" x1="21.145" x2="21.145" y1="9" y2="8.516" gradientUnits="userSpaceOnUse"><stop class="cxy9orbrk"/><stop offset="1" class="k7w7hfhbs"/></linearGradient><linearGradient id="i5drZGI" x1="28.485" x2="28.485" y1="15" y2="20.406" gradientUnits="userSpaceOnUse"><stop class="nmpozru3h"/><stop offset="1" class="mnd9as4iy"/></linearGradient><linearGradient id="iU3htGb" x1="27.885" x2="3.316" y1="18.005" y2="18.005" gradientUnits="userSpaceOnUse"><stop offset=".285" class="c-32s6bme"/><stop offset=".519" class="siqzotbsj"/><stop offset="1" class="wt3yaebzp"/></linearGradient><linearGradient id="ifkQ4ne" x1="3.128" x2="21.323" y1="25.505" y2="25.505" gradientUnits="userSpaceOnUse"><stop class="zlhk43_mm"/><stop offset="1" class="ny_loeylj"/></linearGradient><linearGradient id="ifAO1tc" x1="15.49" x2="15.49" y1="27.374" y2="26.306" gradientUnits="userSpaceOnUse"><stop class="b24cptbav"/><stop offset="1" class="gn167j5ch"/></linearGradient><linearGradient id="iC8NL5b" x1="15.49" x2="15.49" y1="24" y2="24.625" gradientUnits="userSpaceOnUse"><stop class="mn84b941k"/><stop offset="1" class="bsz8-9bvf"/></linearGradient><linearGradient id="iFfqbYc" x1="21.348" x2="22.48" y1="22.781" y2="27.017" gradientUnits="userSpaceOnUse"><stop class="lzhl070xf"/><stop offset="1" class="ftxfdsb2g"/></linearGradient><linearGradient id="iq0SSNr" x1="7.348" x2="8.48" y1="22.781" y2="27.017" gradientUnits="userSpaceOnUse"><stop class="lzhl070xf"/><stop offset="1" class="ftxfdsb2g"/></linearGradient><linearGradient id="iJ0lnEU" x1="18.285" x2="18.285" y1="17.05" y2="16.844" gradientUnits="userSpaceOnUse"><stop class="rxdd0ubxl"/><stop offset="1" class="qlzr_t7ht"/></linearGradient><linearGradient id="iQqZBib" x1="16.332" x2="16.332" y1="8.812" y2="9.344" gradientUnits="userSpaceOnUse"><stop class="vcwz30bwy"/><stop offset="1" class="v_6t4qbio"/></linearGradient><linearGradient id="iSnOvYd" x1="26.879" x2="5.078" y1="18.5" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="f200wfbcg"/><stop offset="1" class="o1x0ufa2d"/></linearGradient><linearGradient id="iIn1cud" x1="11.41" x2="9.91" y1="18.313" y2="16.422" gradientUnits="userSpaceOnUse"><stop class="zqbegfblh"/><stop offset="1" class="gavv5didm"/></linearGradient><linearGradient id="iyCdfqb" x1="14.952" x2="7.871" y1="10.05" y2="17.05" gradientUnits="userSpaceOnUse"><stop class="gvyrb3b_b"/><stop offset="1" class="t65kw7bvq"/></linearGradient><linearGradient id="iAB65Ae" x1="15.329" x2="13.579" y1="14.255" y2="14.255" gradientUnits="userSpaceOnUse"><stop class="y3zrdktlc"/><stop offset="1" class="ovh723kad"/></linearGradient><linearGradient id="ipfoAlb" x1="10.997" x2="10.997" y1="10.292" y2="12.206" gradientUnits="userSpaceOnUse"><stop class="dpdo3fblg"/><stop offset="1" class="kgqt2xflq"/></linearGradient><linearGradient id="izzKPyb" x1="4.483" x2="3.764" y1="19" y2="22.218" gradientUnits="userSpaceOnUse"><stop class="qb2ub23kl"/><stop offset="1" class="eomn1hbuj"/></linearGradient><linearGradient id="iHqcfKY" x1="2.77" x2="3.254" y1="20.578" y2="20.578" gradientUnits="userSpaceOnUse"><stop class="uh5obib7l"/><stop offset="1" class="scr87jbed"/></linearGradient><linearGradient id="i8dLzLF" x1="6.866" x2="12.123" y1="25.62" y2="25.62" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="iu5LUZO" x1="9.903" x2="6.96" y1="24.26" y2="28.323" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="iwtf2Ld" x1="20.866" x2="26.123" y1="25.62" y2="25.62" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="im58Bzc" x1="23.878" x2="20.935" y1="24.26" y2="28.323" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="ik1Elce" x1="22.949" x2="16.164" y1="10.05" y2="15.104" gradientUnits="userSpaceOnUse"><stop class="gvyrb3b_b"/><stop offset="1" class="t65kw7bvq"/></linearGradient><linearGradient id="iJ0G90d" x1="23.233" x2="21.915" y1="14.255" y2="14.255" gradientUnits="userSpaceOnUse"><stop class="y3zrdktlc"/><stop offset="1" class="ovh723kad"/></linearGradient><linearGradient id="iIQzQ6k" x1="19.969" x2="19.969" y1="10.292" y2="13.55" gradientUnits="userSpaceOnUse"><stop class="dpdo3fblg"/><stop offset="1" class="kgqt2xflq"/></linearGradient><linearGradient id="iDpo6ee" x1="27.984" x2="23.329" y1="10.05" y2="11.796" gradientUnits="userSpaceOnUse"><stop class="gvyrb3b_b"/><stop offset="1" class="t65kw7bvq"/></linearGradient><linearGradient id="i4LsBPv" x1="28.128" x2="27.464" y1="14.255" y2="14.255" gradientUnits="userSpaceOnUse"><stop class="y3zrdktlc"/><stop offset="1" class="ovh723kad"/></linearGradient><linearGradient id="iVZ34Jc" x1="26.484" x2="26.484" y1="10.292" y2="13.55" gradientUnits="userSpaceOnUse"><stop class="dpdo3fblg"/><stop offset="1" class="kgqt2xflq"/></linearGradient><linearGradient id="ioczlFc" x1="27.358" x2="26.979" y1="19" y2="22" gradientUnits="userSpaceOnUse"><stop class="r60u_abbi"/><stop offset="1" class="b07kd_a9m"/></linearGradient><linearGradient id="iRCm8bc" x1="27.98" x2="26.979" y1="21.784" y2="19.656" gradientUnits="userSpaceOnUse"><stop class="wglbgwhhr"/><stop offset="1" class="rzt9y3bhu"/></linearGradient><linearGradient id="ijbIZLd" x1="13.985" x2="15.985" y1="18.505" y2="18.505" gradientUnits="userSpaceOnUse"><stop class="qt5bomqit"/><stop offset="1" class="iiowmabcs"/></linearGradient><linearGradient id="iMVuK9b" x1="16.066" x2="15.395" y1="18.828" y2="18.828" gradientUnits="userSpaceOnUse"><stop class="th4jfwb5i"/><stop offset="1" class="ogge8abas"/></linearGradient><linearGradient id="iXEyFZb" x1="18.985" x2="20.985" y1="18.505" y2="18.505" gradientUnits="userSpaceOnUse"><stop class="qt5bomqit"/><stop offset="1" class="iiowmabcs"/></linearGradient><linearGradient id="iVmoEld" x1="21.066" x2="20.395" y1="18.828" y2="18.828" gradientUnits="userSpaceOnUse"><stop class="th4jfwb5i"/><stop offset="1" class="ogge8abas"/></linearGradient><linearGradient id="ijHtZtb" x1="14.332" x2="14.332" y1="8.125" y2="7" gradientUnits="userSpaceOnUse"><stop class="sk-8o1bjo"/><stop offset="1" class="w9udafb7u"/></linearGradient><linearGradient id="iaoo7eb" x1="15.985" x2="16.985" y1="7.505" y2="7.505" gradientUnits="userSpaceOnUse"><stop class="qzooa0bqp"/><stop offset="1" class="wae-w0imf"/></linearGradient><linearGradient id="i7aqseb" x1="16.332" x2="16.332" y1="8.125" y2="7" gradientUnits="userSpaceOnUse"><stop class="sk-8o1bjo"/><stop offset="1" class="w9udafb7u"/></linearGradient><linearGradient id="iF6S1ze" x1="18.332" x2="18.332" y1="8.125" y2="7" gradientUnits="userSpaceOnUse"><stop class="sk-8o1bjo"/><stop offset="1" class="w9udafb7u"/></linearGradient><linearGradient id="iw3FWee" x1="20.332" x2="20.332" y1="8.125" y2="7" gradientUnits="userSpaceOnUse"><stop class="sk-8o1bjo"/><stop offset="1" class="w9udafb7u"/></linearGradient><linearGradient id="iZMScKa" x1="22.332" x2="22.332" y1="8.125" y2="7" gradientUnits="userSpaceOnUse"><stop class="sk-8o1bjo"/><stop offset="1" class="w9udafb7u"/></linearGradient><linearGradient id="igSzCEc" x1="24.332" x2="24.332" y1="8.125" y2="7" gradientUnits="userSpaceOnUse"><stop class="sk-8o1bjo"/><stop offset="1" class="w9udafb7u"/></linearGradient><linearGradient id="ilupUWb" x1="27.379" x2="11.754" y1="9.563" y2="9.563" gradientUnits="userSpaceOnUse"><stop class="s2d8kn7il"/><stop offset="1" class="d5hdwgbmx"/></linearGradient><linearGradient id="iymEUid" x1="29.513" x2="29.513" y1="20.238" y2="15.363" gradientUnits="userSpaceOnUse"><stop class="ffp54mxzv"/><stop offset="1" class="kot4vvbqi"/></linearGradient><linearGradient id="iK9PnTF" x1="11.664" x2="11.98" y1="16.794" y2="16.794" gradientUnits="userSpaceOnUse"><stop class="dqvrw5att"/><stop offset="1" class="cw1262_od"/></linearGradient><filter id="i3TljRd" width="24.969" height="2.5" x="3.566" y="17.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10637" stdDeviation=".5"/></filter><filter id="izHcphb" width="2.523" height="3.601" x="9.465" y="14.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10637" stdDeviation=".125"/></filter><filter id="itiIX9x" width="2.267" height="3.4" x="2.913" y="18.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10637" stdDeviation=".05"/></filter><filter id="ikg5ubc" width="7" height="7.15" x="4.98" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10637"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10637" result="effect2_innerShadow_18_10637"/></filter><filter id="iEsUn5c" width="7.194" height="7.194" x="4.986" y="22.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10637" stdDeviation=".375"/></filter><filter id="i5tkMQd" width="2.6" height="2.6" x="7.18" y="25.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10637"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10637" result="effect2_innerShadow_18_10637"/></filter><filter id="i4xHdWd" width="7" height="7.15" x="18.98" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10637"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10637" result="effect2_innerShadow_18_10637"/></filter><filter id="irpsmke" width="2.6" height="2.6" x="21.18" y="25.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10637"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10637" result="effect2_innerShadow_18_10637"/></filter><filter id="i6xSGqb" width="7.194" height="7.194" x="18.961" y="22.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10637" stdDeviation=".375"/></filter><filter id="iRFCL7c" width="2.279" height="3.4" x="25.778" y="18.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10637" stdDeviation=".05"/></filter><filter id="iIFEFOe" width="2.15" height="1.25" x="13.83" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.423529 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10637"/></filter><filter id="i70Ikae" width="2.15" height="1.25" x="18.83" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.423529 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10637"/></filter><filter id="iIvqrFd" width="16.563" height=".75" x="11.191" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10637" stdDeviation=".15"/></filter><filter id="iupAo8V" width=".6" height="6.895" x="29.213" y="15.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10637" stdDeviation=".1"/></filter><radialGradient id="iCUhdvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.73672 .94191 -.74476 -.58252 25.749 7.058)" gradientUnits="userSpaceOnUse"><stop class="obbxj3bab"/><stop offset="1" class="srhi0ve7t"/></radialGradient><radialGradient id="iHjNUrl" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 4.62499 -7.29807 -10.94713 28.441 9)" gradientUnits="userSpaceOnUse"><stop class="cbx3vnm4y"/><stop offset="1" class="nq75wvvul"/></radialGradient><radialGradient id="is14YGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.77856 2.2146 0 3.669 21.567)" gradientUnits="userSpaceOnUse"><stop class="v3z9mjbbd"/><stop offset="1" class="da212kbkd"/></radialGradient><radialGradient id="iR0oANe" cx="0" cy="0" r="1" gradientTransform="matrix(.79083 -1.73826 1.81555 .826 8.48 26.187)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="iulrIad" cx="0" cy="0" r="1" gradientTransform="matrix(.79083 -1.73826 1.81555 .826 22.48 26.187)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="ioAU7Wc" cx="0" cy="0" r="1" gradientTransform="rotate(118.376 11.101 13.911)scale(3.17681 1.10968)" gradientUnits="userSpaceOnUse"><stop class="ew82xebmp"/><stop offset="1" class="enzy9fbqm"/></radialGradient><radialGradient id="iIDyOed" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 -1.30468 3.4823 3.33637 10.786 17.484)" gradientUnits="userSpaceOnUse"><stop class="lr8ppcpdr"/><stop offset="1" class="zls24xfrf"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sport-utility-vehicle" /></template>
<style>
.a-yymcc9i {
  d: path("M27.98 10.05h-2.04a.96.96 0 0 0-.96.96v5.08c0 .53.43.96.96.96h2.04z");
}

.a2peghb2c {
  stop-color: var(--svg-color--2b1249, #2B1249);
  stop-opacity: 0;
}

.ariye-f8h {
  stop-color: var(--svg-color--2d114d, #2D114D);
}

.b07kd_a9m {
  stop-color: var(--svg-color--4797c1, #4797C1);
}

.b24cptbav {
  stop-color: var(--svg-color--9556c3, #9556C3);
}

.b9uxenb-x {
  d: path("M20.48 19h-1c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h1c.28 0 .5.22.5.5s-.22.5-.5.5");
}

.baem9ki2q {
  stop-color: var(--svg-color--34214f, #34214F);
}

.bsz8-9bvf {
  stop-color: var(--svg-color--b2aec1, #B2AEC1);
  stop-opacity: 0;
}

.bvs036byu {
  stop-color: var(--svg-color--4f4e50, #4F4E50);
}

.c-32s6bme {
  stop-color: var(--svg-color--4a8fd6, #4A8FD6);
}

.cbx3vnm4y {
  stop-color: var(--svg-color--5fc0ea, #5FC0EA);
}

.ct8xv2pis {
  d: path("M21.98 17.05h-4.04a.96.96 0 0 1-.96-.96v-5.08c0-.53.43-.96.96-.96h4.04c.53 0 .96.43.96.96v5.08c0 .53-.43.96-.96.96");
}

.cw1262_od {
  stop-color: var(--svg-color--30334d, #30334D);
}

.cxy9orbrk {
  stop-color: var(--svg-color--4c465f, #4C465F);
}

.d5hdwgbmx {
  stop-color: var(--svg-color--6bd7f0, #6BD7F0);
  stop-opacity: 0;
}

.da212kbkd {
  stop-color: var(--svg-color--dfbf4e, #DFBF4E);
}

.dohadmbkv {
  d: path("M26.32 27.017v-.842h-.001c-.065-2.064-1.76-3.646-3.839-3.646c-2.08 0-3.774 1.582-3.839 3.646h-.002v.841z");
}

.dpdo3fblg {
  stop-color: var(--svg-color--0369da, #0369DA);
}

.dqvrw5att {
  stop-color: var(--svg-color--30334d, #30334D);
  stop-opacity: 0;
}

.dsj9mwt1u {
  fill-rule: evenodd;
  d: path("M9.957 16.55c.005-.291.07-.949.492-1.297c.272-.224.704-.274 1.058-.246c.295.024.473.286.473.573v1.94c0 .288-.178.55-.473.574c-.354.028-.786-.022-1.058-.246c-.422-.348-.487-1.005-.492-1.297");
}

.dvqju6b-r {
  d: path("M15.48 19h-1c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h1c.28 0 .5.22.5.5s-.22.5-.5.5");
}

.eknwvzbam {
  fill: var(--svg-color--ddc7f3, #DDC7F3);
  d: path("M8.48 27.75a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5");
}

.enzy9fbqm {
  stop-color: var(--svg-color--3296f0, #3296F0);
  stop-opacity: 0;
}

.eomn1hbuj {
  stop-color: var(--svg-color--4283d7, #4283D7);
}

.ew82xebmp {
  stop-color: var(--svg-color--3296f0, #3296F0);
}

.f0k16nibb {
  stop-color: var(--svg-color--615b6b, #615B6B);
  stop-opacity: 0;
}

.f200wfbcg {
  stop-color: var(--svg-color--5ab3db, #5AB3DB);
}

.f7539-b8r {
  d: path("M16.98 7h-1v1h1z");
}

.ffp54mxzv {
  stop-color: var(--svg-color--675b75, #675B75);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftxfdsb2g {
  stop-color: var(--svg-color--26439e, #26439E);
}

.gavv5didm {
  stop-color: var(--svg-color--122773, #122773);
  stop-opacity: 0;
}

.gn167j5ch {
  stop-color: var(--svg-color--9556c3, #9556C3);
  stop-opacity: 0;
}

.gvb1prbhz {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M4.98 20c0-.55-.42-1-.933-1h-.934v3h.934c.513 0 .933-.45.933-1z");
}

.gvyrb3b_b {
  stop-color: var(--svg-color--41b8f6, #41B8F6);
}

.h-i7qkb7x {
  d: path("M27.03 9H11.57c-.36 0-.69.21-.85.53l-3.67 7.51H4.88a1.9 1.9 0 0 0-1.9 1.9V27h25V9.95a.95.95 0 0 0-.95-.95");
}

.h6oz-gzel {
  d: path("M18.98 7h-1v1h1z");
}

.hm39t_bvx {
  d: path("M14.94 16.09v-5.08a.96.96 0 0 0-.96-.96h-3.53l-3.42 7h6.95c.53 0 .96-.43.96-.96");
}

.ifzq-cb-g {
  stroke-width: var(--svg-stroke-width--0-85px, 0.85px);
  d: path("M8.583 28.603a2.422 2.422 0 1 0 0-4.844a2.422 2.422 0 0 0 0 4.844Z");
}

.iiowmabcs {
  stop-color: var(--svg-color--b9b4bf, #B9B4BF);
}

.irdv1gcrv {
  d: path("M14.98 7h-1v1h1z");
}

.irzbceozn {
  d: path("M28.12 24H2.86a.87.87 0 0 0-.87.87v1.26c0 .48.39.87.87.87h25.26c.48 0 .87-.39.87-.87v-1.26a.877.877 0 0 0-.87-.87");
}

.iuijv4b4f {
  d: path("M24.98 7h-1v1h1z");
}

.k7w7hfhbs {
  stop-color: var(--svg-color--4c465f, #4C465F);
  stop-opacity: 0;
}

.kgqt2xflq {
  stop-color: var(--svg-color--0369da, #0369DA);
  stop-opacity: 0;
}

.kot4vvbqi {
  stop-color: var(--svg-color--675b75, #675B75);
}

.lr4hy5mvm {
  d: path("M8.48 30a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.lr8ppcpdr {
  stop-color: var(--svg-color--2d253a, #2D253A);
}

.lzhl070xf {
  stop-color: var(--svg-color--131d7e, #131D7E);
}

.m9a774bcn {
  stop-color: var(--svg-color--35313e, #35313E);
}

.mmwl-dsmc {
  stop-color: var(--svg-color--241337, #241337);
}

.mn84b941k {
  stop-color: var(--svg-color--b2aec1, #B2AEC1);
}

.mnd9as4iy {
  stop-color: var(--svg-color--1e1528, #1E1528);
}

.nmpozru3h {
  stop-color: var(--svg-color--665a78, #665A78);
}

.nq75wvvul {
  stop-color: var(--svg-color--5fc0ea, #5FC0EA);
  stop-opacity: 0;
}

.ny_loeylj {
  stop-color: var(--svg-color--b9a0d2, #B9A0D2);
}

.o1x0ufa2d {
  stop-color: var(--svg-color--5190e3, #5190E3);
}

.obbxj3bab {
  stop-color: var(--svg-color--535354, #535354);
}

.oeptinb4s {
  stop-color: var(--svg-color--615b6b, #615B6B);
}

.ogge8abas {
  stop-color: var(--svg-color--80778a, #80778A);
  stop-opacity: 0;
}

.ovh723kad {
  stop-color: var(--svg-color--2cb6e5, #2CB6E5);
  stop-opacity: 0;
}

.q-tit6owl {
  fill-rule: evenodd;
  d: path("M9.715 16.762c.005-.292.07-.95.492-1.297c.272-.225.704-.275 1.058-.246c.295.023.473.286.473.573v1.94c0 .287-.178.55-.473.573c-.354.029-.786-.021-1.058-.246c-.421-.348-.487-1.005-.492-1.297");
}

.qb2ub23kl {
  stop-color: var(--svg-color--355fc4, #355FC4);
}

.qlzr_t7ht {
  stop-color: var(--svg-color--52a2de, #52A2DE);
  stop-opacity: 0;
}

.qt5bomqit {
  stop-color: var(--svg-color--c6c2cb, #C6C2CB);
}

.qzooa0bqp {
  stop-color: var(--svg-color--9b9b9b, #9B9B9B);
}

.r60u_abbi {
  stop-color: var(--svg-color--3a74be, #3A74BE);
}

.rxdd0ubxl {
  stop-color: var(--svg-color--52a2de, #52A2DE);
}

.rzt9y3bhu {
  stop-color: var(--svg-color--d11f58, #D11F58);
}

.s2d8kn7il {
  stop-color: var(--svg-color--6bd7f0, #6BD7F0);
}

.scr87jbed {
  stop-color: var(--svg-color--c3a558, #C3A558);
  stop-opacity: 0;
}

.siqzotbsj {
  stop-color: var(--svg-color--4377da, #4377DA);
}

.sk-8o1bjo {
  stop-color: var(--svg-color--c6bfd3, #C6BFD3);
}

.srhi0ve7t {
  stop-color: var(--svg-color--535354, #535354);
  stop-opacity: 0;
}

.suhfdvqdu {
  d: path("M27.98 19h-.5c-.85 0-1.54.71-1.5 1.57c.04.81.74 1.43 1.55 1.43h.45z");
}

.t65kw7bvq {
  stop-color: var(--svg-color--59f5ff, #59F5FF);
}

.tdco28z3x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M4.816 18.313h22.47");
}

.th4jfwb5i {
  stop-color: var(--svg-color--80778a, #80778A);
}

.u6bl05q2o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M11.566 9.375H27.38");
}

.uh5obib7l {
  stop-color: var(--svg-color--c3a558, #C3A558);
}

.urizi4z9f {
  d: path("M24.98 7h-11c-.55 0-1 .45-1 1v1h1V8h11v1h1V8c0-.55-.44-1-1-1");
}

.v_6t4qbio {
  stop-color: var(--svg-color--3c6fa9, #3C6FA9);
  stop-opacity: 0;
}

.v3z9mjbbd {
  stop-color: var(--svg-color--fff783, #FFF783);
}

.vcwz30bwy {
  stop-color: var(--svg-color--3c6fa9, #3C6FA9);
}

.vlaf3zbli {
  fill: var(--svg-color--d9c3f0, #D9C3F0);
  d: path("M22.48 27.75a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5");
}

.vpbxmjbhw {
  d: path("M27.98 17.05H4.684q.097-.01.196-.01h2.17l3.67-7.51c.16-.32.49-.53.85-.53h15.46c.53 0 .95.43.95.95z");
}

.w_rdembmv {
  d: path("M12.32 27.017v-.842h-.001c-.065-2.064-1.76-3.646-3.839-3.646c-2.08 0-3.774 1.582-3.839 3.646H4.64v.841z");
}

.w6bruhbqq {
  d: path("M29.48 23h-2.49v-8h2.49c.28 0 .51.23.51.51v6.98c-.01.29-.23.51-.51.51");
}

.w9udafb7u {
  stop-color: var(--svg-color--d9d7dc, #D9D7DC);
}

.wae-w0imf {
  stop-color: var(--svg-color--d3d3d3, #D3D3D3);
}

.we_4yceiw {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M27.858 19h-.378c-.85 0-1.54.71-1.5 1.57c.04.81.74 1.43 1.55 1.43h.328z");
}

.wglbgwhhr {
  stop-color: var(--svg-color--f83d69, #F83D69);
}

.wqpsnotos {
  stroke-width: var(--svg-stroke-width--0-85px, 0.85px);
  d: path("M22.558 28.603a2.422 2.422 0 1 0 0-4.844a2.422 2.422 0 0 0 0 4.844Z");
}

.wt3yaebzp {
  stop-color: var(--svg-color--4379d8, #4379D8);
}

.x0rb78w3d {
  d: path("M20.98 7h-1v1h1z");
}

.xy2m52gpe {
  d: path("M4.98 20c0-.55-.45-1-1-1h-1v3h1c.55 0 1-.45 1-1z");
}

.y3zrdktlc {
  stop-color: var(--svg-color--2cb6e5, #2CB6E5);
}

.yiwb9d3rs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M29.513 15.545v6.294");
}

.zlhk43_mm {
  stop-color: var(--svg-color--ab9dbb, #AB9DBB);
}

.zls24xfrf {
  stop-color: var(--svg-color--5e526a, #5E526A);
}

.zo6q6xbjo {
  d: path("M22.98 7h-1v1h1z");
}

.zqbegfblh {
  stop-color: var(--svg-color--122773, #122773);
}

.zqxissixt {
  d: path("M22.48 30a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

</style>
