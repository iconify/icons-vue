<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iX2OXXb)"><path class="glftuivdf"/><path fill="url(#ix97Wbd)" class="rctl957xn"/></g><path fill="url(#iMZtDPc)" class="rctl957xn"/><path fill="url(#iWfo7zc)" class="dx7d4nf8g"/><path fill="url(#i4bqlod)" class="dx7d4nf8g"/><g filter="url(#inwbObS)"><circle fill="url(#imtGEue)" class="mjqbpu-6s"/></g><g filter="url(#iJJcjOe)"><circle fill="url(#izi3b7c)" class="bmkb5mb3q"/></g><g filter="url(#i0o7W9d)"><circle fill="url(#iRLU66b)" class="w1vhr8rhq"/><circle fill="url(#i5jpxAb)" class="w1vhr8rhq"/></g><g filter="url(#iHYTVee)"><circle class="dtaf_80qv"/><circle fill="url(#i90DAPd)" class="ohk97qlmg"/><circle fill="url(#izysxYh)" class="ohk97qlmg"/></g><g filter="url(#i0sECqb)"><path fill="url(#i2mMFUc)" class="qmdyylb5p"/><path fill="url(#iHQK4yA)" class="qmdyylb5p"/><path fill="url(#ihDylYb)" class="qmdyylb5p"/></g><path fill="url(#iDSB6Ie)" class="uu2konbaf"/><path fill="url(#icldMqc)" class="uu2konbaf"/><path fill="url(#iLYAVdd)" class="uu2konbaf"/><g filter="url(#iyvnLQc)"><path fill="url(#iQwVx0d)" class="mj66r_03k"/></g><g filter="url(#iMbkqSb)"><path class="rpomofb4p"/><path fill="url(#ittP1td)" class="f5wpeh-ig"/><path fill="url(#iOdzSGb)" class="f5wpeh-ig"/><path fill="url(#iL6IMbe)" class="f5wpeh-ig"/><path fill="url(#iyy2VGO)" class="f5wpeh-ig"/></g><g filter="url(#icQdqRc)"><path class="fbzsnyb1i"/></g><g filter="url(#i5gHGFb)"><path class="tfuwq2aer"/></g><g filter="url(#iawSV6b)"><path stroke="url(#iqfFR8c)" class="hy9gs9bfn"/></g><g filter="url(#idk5evc)"><path stroke="url(#isWRApb)" class="a01d8l9dy"/></g><path fill="url(#iprBwSc)" class="k82asi0_o"/><path fill="url(#i3avztb)" class="k82asi0_o"/><g filter="url(#iwJYLAd)"><path fill="url(#i1ZEOUd)" class="qjrvhp1vp"/></g><g filter="url(#it9H8kb)"><path fill="url(#iHW38Jb)" clip-rule="evenodd" class="ecfor_b_e"/></g><path class="ws7xvdb5p"/><g filter="url(#iMdTYlb)"><path class="b4wf3p8du"/><path fill="url(#iVtMPJQ)" class="d_hm17cvw"/><path fill="url(#iW5UtTc)" class="d_hm17cvw"/><path fill="url(#iaUO3Kc)" class="d_hm17cvw"/><path fill="url(#idCbwWd)" class="d_hm17cvw"/></g><g filter="url(#iYlEJse)"><path fill="url(#iuEEgIe)" class="d_hm17cvw"/><path fill="url(#i46ZGGe)" class="d_hm17cvw"/><path fill="url(#iBZc33b)" class="d_hm17cvw"/><path fill="url(#i61SEOO)" class="d_hm17cvw"/><path fill="url(#iiINBYd)" class="d_hm17cvw"/><path fill="url(#ixNdY7N)" class="d_hm17cvw"/></g><path fill="url(#ivH69Oc)" class="tcqyysbeq"/><path fill="url(#i94fTKe)" class="tcqyysbeq"/><path fill="url(#iixV33h)" class="n4-umrbiw"/><path fill="url(#ilSCjye)" class="n4-umrbiw"/><path fill="url(#iIGXJXb)" class="n4-umrbiw"/><path fill="url(#iOhkWTc)" class="n4-umrbiw"/><g filter="url(#iPZP9KE)"><path class="pbftjdbhn"/></g><g filter="url(#iNLQsMb)"><path class="rjjq6jj_j"/></g><g filter="url(#iUfvnGe)"><path class="oxjtcmbhj"/></g><g filter="url(#ic1NqCc)"><path stroke="url(#iXEdKFd)" class="erg45peay"/></g><g filter="url(#iG76jof)"><path stroke="url(#iBf8ntd)" class="ri1-v9b0j"/></g><defs><radialGradient id="ix97Wbd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.38721 2.45336 -5.57243 -14.5076 20.895 26.37)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="yo8dvabcv"/><stop offset="1" class="yzuqint-c"/></radialGradient><radialGradient id="iMZtDPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.84375 -6.97792 0 15.51 18.166)" gradientUnits="userSpaceOnUse"><stop offset=".503" class="lci483bsi"/><stop offset="1" class="y0h0v45io"/></radialGradient><radialGradient id="iWfo7zc" cx="0" cy="0" r="1" gradientTransform="matrix(2.32812 3.40625 -3.8571 2.63627 14.197 20.354)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="u2-h40_zt"/><stop offset=".878" class="xvg6ahjwu"/></radialGradient><radialGradient id="imtGEue" cx="0" cy="0" r="1" gradientTransform="matrix(2.22889 0 0 3.90057 7.348 12.942)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="i5jpxAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.05001 -.76457 .87266 1.19846 22.024 12.605)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="i90DAPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0431 -1.91855 1.12294 .61053 21.5 13.985)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="izysxYh" cx="0" cy="0" r="1" gradientTransform="matrix(.32932 .32599 -.42024 .42454 21.552 12.942)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iHQK4yA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.66015 2.04326 0 18.479 11.327)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="ihDylYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.74528 2.17042 0 12.69 11.497)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iLYAVdd" cx="0" cy="0" r="1" gradientTransform="scale(11.7308 10.3866)rotate(90 .13 1.159)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="ch_bgqxqt"/><stop offset="1" class="w_ll5vb1y"/></radialGradient><radialGradient id="ittP1td" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 15.553 -9.857)scale(3.88958 1.44238)" gradientUnits="userSpaceOnUse"><stop class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iOdzSGb" cx="0" cy="0" r="1" gradientTransform="matrix(4.858 .44705 -.24038 2.61211 18.931 5.491)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iL6IMbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.13275 -3.30303 0 15.499 2.017)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iyy2VGO" cx="0" cy="0" r="1" gradientTransform="matrix(3.90428 -2.86115 4.48249 6.11673 7.308 10.677)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iprBwSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.92987 3.82055 -4.53851 -1.1046 21.934 13.905)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset=".909" class="by5wrxbms"/></radialGradient><radialGradient id="i3avztb" cx="0" cy="0" r="1" gradientTransform="matrix(.35375 .48515 -.41214 .30052 21.035 14.229)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iHW38Jb" cx="0" cy="0" r="1" gradientTransform="matrix(1.60227 1.22796 -.50064 .65325 11.504 11.996)" gradientUnits="userSpaceOnUse"><stop class="ydnv7dmcb"/><stop offset="1" class="z7b6pmupf"/></radialGradient><radialGradient id="iVtMPJQ" cx="0" cy="0" r="1" gradientTransform="matrix(1 2.48437 -.40982 .16496 14.996 11.729)" gradientUnits="userSpaceOnUse"><stop class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="iW5UtTc" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 3.84375 -.63406 .16238 16.824 9.572)" gradientUnits="userSpaceOnUse"><stop class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="iaUO3Kc" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 4.375 -.54534 .0818 19.105 8.76)" gradientUnits="userSpaceOnUse"><stop class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="idCbwWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.29552 3.9685 -.3574 -.02661 22.12 10.62)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="iuEEgIe" cx="0" cy="0" r="1" gradientTransform="rotate(104.051 5.69 14.096)scale(10.3219 9.11334)" gradientUnits="userSpaceOnUse"><stop offset=".542" class="dy3bcxe9s"/><stop offset="1" class="mghihr2mt"/></radialGradient><radialGradient id="i46ZGGe" cx="0" cy="0" r="1" gradientTransform="matrix(.98633 2.57228 -.42433 .1627 15.01 11.64)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="mkzsocckt"/><stop offset="1" class="peh2v9b4z"/></radialGradient><radialGradient id="iBZc33b" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 3.84375 -.63406 .16238 16.824 9.572)" gradientUnits="userSpaceOnUse"><stop class="j35ckxhbd"/><stop offset="1" class="ryim261uk"/></radialGradient><radialGradient id="i61SEOO" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 4.375 -.54534 .0818 19.105 8.76)" gradientUnits="userSpaceOnUse"><stop class="j35ckxhbd"/><stop offset="1" class="ryim261uk"/></radialGradient><radialGradient id="iiINBYd" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 6.562 15.04)scale(3.93108 .49375)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="ujux3mbty"/><stop offset="1" class="aqew1kb2z"/></radialGradient><radialGradient id="ixNdY7N" cx="0" cy="0" r="1" gradientTransform="rotate(-175.482 11.064 7.22)scale(.97177 2.30137)" gradientUnits="userSpaceOnUse"><stop class="fvbl5pb0w"/><stop offset="1" class="my72jwxuh"/></radialGradient><radialGradient id="ivH69Oc" cx="0" cy="0" r="1" gradientTransform="rotate(165.742 9.578 11.265)scale(3.42011 2.21707)" gradientUnits="userSpaceOnUse"><stop class="jyajb3b9r"/><stop offset="1" class="ltsdp7lah"/></radialGradient><radialGradient id="ilSCjye" cx="0" cy="0" r="1" gradientTransform="matrix(2.29332 10.73456 -3.15485 .674 22.808 21.307)" gradientUnits="userSpaceOnUse"><stop class="nzzn1bz-b"/><stop offset="1" class="ec89a6biv"/></radialGradient><filter id="iX2OXXb" width="20.98" height="11.16" x="5.52" y="19.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.501961 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4114"/></filter><filter id="inwbObS" width="4.441" height="4.241" x="7.348" y="10.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4114"/></filter><filter id="iJJcjOe" width="3.527" height="3.527" x="7.705" y="11.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4114" stdDeviation=".25"/></filter><filter id="i0o7W9d" width="4.491" height="4.491" x="19.431" y="10.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4114"/></filter><filter id="iHYTVee" width="3.527" height="3.527" x="19.788" y="11.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4114" stdDeviation=".25"/></filter><filter id="i0sECqb" width="13.176" height="15.527" x="8.948" y="5.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4114"/></filter><filter id="iyvnLQc" width="9.393" height="7.895" x="13.715" y="3.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4114" stdDeviation="1"/></filter><filter id="iMbkqSb" width="16.006" height="10.716" x="7.496" y="1.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4114"/></filter><filter id="icQdqRc" width="3.717" height="2.271" x="17" y="8.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0784314 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4114"/></filter><filter id="i5gHGFb" width="3.717" height="2.271" x="10.462" y="8.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0784314 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4114"/></filter><filter id="iawSV6b" width="3.948" height="2.12" x="10.229" y="8.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4114" stdDeviation=".25"/></filter><filter id="idk5evc" width="1.078" height="2.68" x="9.039" y="6.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4114" stdDeviation=".125"/></filter><filter id="iwJYLAd" width="12.214" height="13.502" x="11.655" y="7.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4114" stdDeviation=".625"/></filter><filter id="it9H8kb" width="3.412" height="1.462" x="11.302" y="12.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.0235294 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4114"/></filter><filter id="iMdTYlb" width="12.047" height="12.796" x="12.974" y="7.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.607843 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4114"/></filter><filter id="iYlEJse" width="11.547" height="12.796" x="12.974" y="7.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4114"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.321569 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4114" result="effect2_innerShadow_4002_4114"/></filter><filter id="iPZP9KE" width="2.469" height="5.75" x="17.354" y="7.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4114" stdDeviation=".25"/></filter><filter id="iNLQsMb" width="2.75" height="4.625" x="15.291" y="9.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4114" stdDeviation=".25"/></filter><filter id="iUfvnGe" width="2.844" height="3.75" x="13.479" y="11.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4114" stdDeviation=".25"/></filter><filter id="ic1NqCc" width="3.688" height="7.656" x="20.574" y="11.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4114" stdDeviation=".25"/></filter><filter id="iG76jof" width="2.422" height="10.188" x="19.715" y="7.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4114" stdDeviation=".25"/></filter><linearGradient id="i4bqlod" x1="12.556" x2="14.036" y1="21.15" y2="21.15" gradientUnits="userSpaceOnUse"><stop class="k33vgbb-x"/><stop offset="1" class="l-1_6cczr"/></linearGradient><linearGradient id="izi3b7c" x1="9.469" x2="8.655" y1="13.296" y2="13.296" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iRLU66b" x1="22.931" x2="21.892" y1="11.555" y2="14.777" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="i2mMFUc" x1="20.625" x2="10.925" y1="13.436" y2="14.882" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iDSB6Ie" x1="9.338" x2="11.035" y1="16.825" y2="16.776" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="icldMqc" x1="21.677" x2="20.336" y1="15.796" y2="15.669" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iQwVx0d" x1="14.824" x2="25.168" y1="9.645" y2="5.942" gradientUnits="userSpaceOnUse"><stop class="y3qu8-b1b"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iqfFR8c" x1="13.057" x2="11.308" y1="9.185" y2="8.329" gradientUnits="userSpaceOnUse"><stop class="f8mbax1sz"/><stop offset="1" class="yziabsbik"/></linearGradient><linearGradient id="isWRApb" x1="9.578" x2="9.578" y1="6.705" y2="9.445" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="i1ZEOUd" x1="17.762" x2="15.061" y1="8.485" y2="19.151" gradientUnits="userSpaceOnUse"><stop class="l69eqvkgu"/><stop offset="1" class="qywc1dh7o"/></linearGradient><linearGradient id="i94fTKe" x1="19.964" x2="20.062" y1="19.459" y2="19.823" gradientUnits="userSpaceOnUse"><stop offset=".245" class="cif2-ibcw"/><stop offset="1" class="z12oxsbsi"/></linearGradient><linearGradient id="iixV33h" x1="19.214" x2="25.652" y1="28.151" y2="26.776" gradientUnits="userSpaceOnUse"><stop class="rx4h2ue1h"/><stop offset="1" class="n3x1ut3_u"/></linearGradient><linearGradient id="iIGXJXb" x1="18.01" x2="19.229" y1="27.823" y2="27.448" gradientUnits="userSpaceOnUse"><stop class="dfx3e9_rs"/><stop offset="1" class="gipxjq48x"/></linearGradient><linearGradient id="iOhkWTc" x1="19.664" x2="20.008" y1="20.416" y2="21.854" gradientUnits="userSpaceOnUse"><stop offset=".19" class="k68bkmf2g"/><stop offset="1" class="ll1_3bc-l"/></linearGradient><linearGradient id="iXEdKFd" x1="23.863" x2="21.925" y1="12.795" y2="17.439" gradientUnits="userSpaceOnUse"><stop class="jrsz9e89j"/><stop offset="1" class="lf-s-qkac"/></linearGradient><linearGradient id="iBf8ntd" x1="21.427" x2="18.04" y1="9.223" y2="11.193" gradientUnits="userSpaceOnUse"><stop class="jrsz9e89j"/><stop offset="1" class="lf-s-qkac"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-facepalming-medium-dark" /></template>
<style>
.a01d8l9dy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.742 6.83v1.14c-.01.19-.09.612-.328.79");
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.aqew1kb2z {
  stop-color: var(--svg-color--663a29, #663A29);
  stop-opacity: 0;
}

.b4wf3p8du {
  fill: var(--svg-color--ffca3d, #FFCA3D);
  d: path("M17.678 7.703a1.1 1.1 0 0 1 1.288.872l.415 2.15l-.1-1.608a1.1 1.1 0 1 1 2.195-.136l.23 3.687l.38-.785a1.15 1.15 0 1 1 2.07 1.004l-.95 1.957c-.203.489-.212.94-.222 1.417c-.01.435-.019.893-.176 1.42c-.275.926-.823 1.667-1.062 1.923l-3.063.875c-2.36-.578-3.078-1.922-3.469-3.047a15.5 15.5 0 0 0-.765-1.844l-1.351-2.602a1.1 1.1 0 0 1 1.952-1.014l.225.432l-.539-1.568a1.1 1.1 0 0 1 2.081-.714l.471 1.372l-.482-2.503a1.1 1.1 0 0 1 .872-1.288");
}

.bmkb5mb3q {
  cx: 9.469px;
  cy: 12.942px;
  r: 1.264px;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.ch_bgqxqt {
  stop-color: var(--svg-color--613a44, #613A44);
  stop-opacity: 0;
}

.cif2-ibcw {
  stop-color: var(--svg-color--1b7db4, #1B7DB4);
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d_hm17cvw {
  d: path("M17.678 7.703a1.1 1.1 0 0 1 1.288.872l.415 2.15l-.1-1.608a1.1 1.1 0 1 1 2.195-.136l.23 3.687l.38-.785a1.15 1.15 0 1 1 2.07 1.004l-.95 1.957c-.203.489-.212.94-.222 1.417c-.01.435-.019.893-.176 1.42c-.275.926-.823 1.667-1.062 1.923l-3.063.875c-2.36-.578-3.078-1.922-3.469-3.047a15.5 15.5 0 0 0-.765-1.844l-1.351-2.602a1.1 1.1 0 0 1 1.952-1.014l.225.432l-.539-1.568a1.1 1.1 0 0 1 2.081-.714l.471 1.372l-.482-2.503a1.1 1.1 0 0 1 .872-1.288");
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dfx3e9_rs {
  stop-color: var(--svg-color--3476ba, #3476BA);
}

.dtaf_80qv {
  cx: 21.552px;
  cy: 12.942px;
  r: 1.264px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.dx7d4nf8g {
  d: path("M15.51 22.963c-1.438 0-2.605-.604-2.605-1.969V17.62c0-1.364 1.167-2.471 2.605-2.471s2.605 1.107 2.605 2.47v3.375c0 1.365-1.167 1.97-2.605 1.97");
}

.dy3bcxe9s {
  stop-color: var(--svg-color--8d635e, #8D635E);
}

.ec89a6biv {
  stop-color: var(--svg-color--1c9ae9, #1C9AE9);
  stop-opacity: 0;
}

.ecfor_b_e {
  fill-rule: evenodd;
  d: path("M14.575 12.2c.15.108.184.319.074.469a2.02 2.02 0 0 1-1.641.828a2.05 2.05 0 0 1-1.639-.824a.336.336 0 1 1 .538-.404c.256.341.656.556 1.1.556c.457 0 .855-.216 1.099-.552a.337.337 0 0 1 .47-.074");
}

.erg45peay {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m23.386 12.526l-.937 1.89a3.56 3.56 0 0 0-.36 1.781c.079.97-.265 1.829-.64 2.235");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f5wpeh-ig {
  d: path("m21.62 4.714l.544.271c.954.474 1.5 1.558 1.295 2.71l-.75 3.861c-.066.399-.33.667-.726.677h-.023s.068-1.151.136-1.829c.056-.55-.04-.718-.545-1.219c-.272-.27-.477-.677-.477-1.084V7.017c0-.338-.272-.61-.545-.677c-.817-.203-2.52-.542-4.973-.542s-4.156.339-4.973.542c-.341.068-.545.339-.545.677v1.084c0 .407-.137.813-.477 1.084l-.205.203c-.272.203-.408.61-.408.949c.068.745.136 1.829.136 1.829l-.063-.002a.804.804 0 0 1-.755-.676l-.75-3.861c-.135-1.084.41-2.168 1.363-2.642l.545-.27c.341-.204.682-.475 1.022-.746l1.227-1.287c.75-.677 1.84-.88 2.793-.406c.681.203 1.43.203 2.112 0c1.022-.34 2.18-.068 2.998.677l1.021 1.016c.273.339.614.542 1.022.745");
}

.f8mbax1sz {
  stop-color: var(--svg-color--413737, #413737);
}

.fbzsnyb1i {
  fill: var(--svg-color--2b1627, #2B1627);
  d: path("m20.223 9.487l-.001-.001l-.003-.002l-.005-.005l-.016-.012a2 2 0 0 0-.196-.136a3.3 3.3 0 0 0-.533-.268a3.6 3.6 0 0 0-1.896-.201a.678.678 0 1 0 .211 1.339c.505-.08.91.013 1.186.123a2 2 0 0 1 .392.21a.678.678 0 0 0 .861-1.047");
}

.ft5dv1b6b {
  fill: none;
}

.fvbl5pb0w {
  stop-color: var(--svg-color--a17b72, #A17B72);
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gipxjq48x {
  stop-color: var(--svg-color--3476ba, #3476BA);
  stop-opacity: 0;
}

.glftuivdf {
  fill: var(--svg-color--1d79c4, #1D79C4);
  d: path("M25.5 29.966v-.39c0-5.39-4.47-9.77-9.99-9.77c-5.52.01-9.99 4.38-9.99 9.77v.39z");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hy9gs9bfn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M10.979 9.962c.415-.367 1.323-.754 2.447-.575");
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.j35ckxhbd {
  stop-color: var(--svg-color--66453c, #66453C);
}

.jrsz9e89j {
  stop-color: var(--svg-color--8f7770, #8F7770);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jyajb3b9r {
  stop-color: var(--svg-color--489ed5, #489ED5);
}

.k33vgbb-x {
  stop-color: var(--svg-color--5a3c3b, #5A3C3B);
}

.k68bkmf2g {
  stop-color: var(--svg-color--0792d5, #0792D5);
}

.k82asi0_o {
  d: path("M21.106 14.277c.404-.013.783-.15 1.09-.372v1.123a2.62 2.62 0 0 1-1.616 2.435c.205-.437.346-.914.417-1.423z");
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l-1_6cczr {
  stop-color: var(--svg-color--5a3c3b, #5A3C3B);
  stop-opacity: 0;
}

.l69eqvkgu {
  stop-color: var(--svg-color--4a2921, #4A2921);
}

.lci483bsi {
  stop-color: var(--svg-color--115284, #115284);
}

.lf-s-qkac {
  stop-color: var(--svg-color--8f7770, #8F7770);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.ll1_3bc-l {
  stop-color: var(--svg-color--0792d5, #0792D5);
  stop-opacity: 0;
}

.ltsdp7lah {
  stop-color: var(--svg-color--20669e, #20669E);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mghihr2mt {
  stop-color: var(--svg-color--7a4a3d, #7A4A3D);
}

.mj66r_03k {
  d: path("m20.533 5.798l-3.908 1.303a1.33 1.33 0 0 0 .597 2.58l3.886-.52z");
}

.mjqbpu-6s {
  cx: 9.469px;
  cy: 12.942px;
  r: 2.12px;
}

.mkzsocckt {
  stop-color: var(--svg-color--664239, #664239);
}

.my72jwxuh {
  stop-color: var(--svg-color--a17b72, #A17B72);
  stop-opacity: 0;
}

.n3x1ut3_u {
  stop-color: var(--svg-color--45aaed, #45AAED);
}

.n4-umrbiw {
  d: path("M16.827 22.536a1 1 0 0 1 .723-1.221l5.303-1.339a1 1 0 0 1 1.213.718l2.414 9.289h-7.719z");
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nl6pfdccl {
  stop-color: var(--svg-color--f69202, #F69202);
}

.noux9m6yk {
  stop-color: var(--svg-color--f69202, #F69202);
  stop-opacity: 0;
}

.nzzn1bz-b {
  stop-color: var(--svg-color--47c9ff, #47C9FF);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.ohk97qlmg {
  cx: 21.552px;
  cy: 12.942px;
  r: 1.264px;
}

.oxjtcmbhj {
  stroke: var(--svg-color--8f7770, #8F7770);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m14.354 12.652l1.094 2");
}

.pbftjdbhn {
  stroke: var(--svg-color--8f7770, #8F7770);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m18.229 8.84l.719 4");
}

.peh2v9b4z {
  stop-color: var(--svg-color--664239, #664239);
  stop-opacity: 0;
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.qjrvhp1vp {
  d: path("M16.95 8.502a.946.946 0 0 1 1.108.75l.356 1.849l-.086-1.383a.946.946 0 1 1 1.888-.117l.197 3.17l.327-.675a.989.989 0 0 1 1.78.863l-.817 1.683c-.174.42-.182.808-.19 1.219c-.009.374-.017.767-.152 1.221c-.236.796-.707 1.433-.913 1.653l-2.634.752c-2.028-.497-2.646-1.652-2.982-2.62a13 13 0 0 0-.659-1.585l-1.161-2.238a.946.946 0 1 1 1.678-.872l.194.372l-.463-1.349a.946.946 0 1 1 1.79-.613l.404 1.18l-.414-2.152a.946.946 0 0 1 .75-1.108");
}

.qmdyylb5p {
  d: path("M9.084 12.166s-.068-1.084-.136-1.83c0-.338.136-.745.408-.948l.205-.203c.34-.271.477-.677.477-1.084V7.017c0-.338.204-.61.545-.677c.817-.203 2.52-.542 4.973-.542s4.156.339 4.974.542c.272.068.544.339.544.677v1.084c0 .407.205.813.477 1.084c.638.447.598.693.545 1.22a59 59 0 0 0-.136 1.828h.023l-.338 5.028c-.203 2.247-1.97 3.814-4.077 3.814H13.49c-2.174 0-3.873-1.567-4.077-3.814a2008 2008 0 0 0-.33-5.095");
}

.qywc1dh7o {
  stop-color: var(--svg-color--5e3742, #5E3742);
}

.rctl957xn {
  d: path("M25.5 29.966v-.39c0-5.39-4.47-9.77-9.99-9.77c-5.52.01-9.99 4.38-9.99 9.77v.39z");
}

.ri1-v9b0j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m20.59 8.838l.671 8.438");
}

.rjjq6jj_j {
  stroke: var(--svg-color--8f7770, #8F7770);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m16.166 10.621l1 2.875");
}

.rpomofb4p {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m21.62 4.714l.544.271c.954.474 1.5 1.558 1.295 2.71l-.75 3.861c-.066.399-.33.667-.726.677h-.023s.068-1.151.136-1.829c.056-.55-.04-.718-.545-1.219c-.272-.27-.477-.677-.477-1.084V7.017c0-.338-.272-.61-.545-.677c-.817-.203-2.52-.542-4.973-.542s-4.156.339-4.973.542c-.341.068-.545.339-.545.677v1.084c0 .407-.137.813-.477 1.084l-.205.203c-.272.203-.408.61-.408.949c.068.745.136 1.829.136 1.829l-.063-.002a.804.804 0 0 1-.755-.676l-.75-3.861c-.135-1.084.41-2.168 1.363-2.642l.545-.27c.341-.204.682-.475 1.022-.746l1.227-1.287c.75-.677 1.84-.88 2.793-.406c.681.203 1.43.203 2.112 0c1.022-.34 2.18-.068 2.998.677l1.021 1.016c.273.339.614.542 1.022.745");
}

.rx4h2ue1h {
  stop-color: var(--svg-color--2474c2, #2474C2);
}

.ryim261uk {
  stop-color: var(--svg-color--66453c, #66453C);
  stop-opacity: 0;
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.tcqyysbeq {
  d: path("M17.39 20.462a.25.25 0 0 1 .182-.302l4.733-1.205a.25.25 0 0 1 .305.184l.274 1.13l-5.229 1.267z");
}

.tfuwq2aer {
  fill: var(--svg-color--2b1627, #2B1627);
  d: path("m10.706 9.487l.002-.001l.002-.002l.006-.005l.015-.012a2 2 0 0 1 .197-.136c.127-.08.306-.178.533-.268a3.6 3.6 0 0 1 1.896-.201a.678.678 0 0 1-.211 1.339c-.506-.08-.91.013-1.187.123a2 2 0 0 0-.39.21a.678.678 0 0 1-.863-1.047");
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.u2-h40_zt {
  stop-color: var(--svg-color--58303d, #58303D);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ujux3mbty {
  stop-color: var(--svg-color--663a29, #663A29);
}

.uu2konbaf {
  d: path("M8.948 10.337c0-.34.136-.746.408-.949l.205-.203c.34-.271.477-.677.477-1.084V7.017c0-.338.204-.61.545-.677c.817-.203 2.52-.542 4.973-.542s4.156.339 4.974.542c.272.068.544.339.544.677v1.084c0 .407.205.813.477 1.084c.638.447.598.693.545 1.22a59 59 0 0 0-.136 1.828h.023l-.338 5.028c-.203 2.247-1.97 3.814-4.077 3.814H13.49c-2.174 0-3.873-1.567-4.077-3.814c-.177-2.307-.255-4.621-.465-6.924");
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w_ll5vb1y {
  stop-color: var(--svg-color--583a56, #583A56);
}

.w1vhr8rhq {
  cx: 21.552px;
  cy: 12.942px;
  r: 2.12px;
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.ws7xvdb5p {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M17.701 17.525a2.47 2.47 0 0 0-2.06-1.12c-.861 0-1.618.45-2.059 1.12c-.095.144.039.317.192.297H17.5c.164 0 .297-.143.201-.297");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xvg6ahjwu {
  stop-color: var(--svg-color--624649, #624649);
}

.y0h0v45io {
  stop-color: var(--svg-color--115284, #115284);
  stop-opacity: 0;
}

.y3qu8-b1b {
  stop-color: var(--svg-color--a27b71, #A27B71);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ydnv7dmcb {
  stop-color: var(--svg-color--3c3133, #3C3133);
}

.yo8dvabcv {
  stop-color: var(--svg-color--1d6fc7, #1D6FC7);
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.yziabsbik {
  stop-color: var(--svg-color--413737, #413737);
  stop-opacity: 0;
}

.yzuqint-c {
  stop-color: var(--svg-color--1d6fc7, #1D6FC7);
  stop-opacity: 0;
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z12oxsbsi {
  stop-color: var(--svg-color--1b7db4, #1B7DB4);
  stop-opacity: 0;
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z7b6pmupf {
  stop-color: var(--svg-color--22141e, #22141E);
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

</style>
