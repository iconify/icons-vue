<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i0Z4Bwd)"><path class="ij6q1eb-i"/><path fill="url(#iV608xe)" class="f5pkipbfo"/></g><path fill="url(#iTkswTb)" class="f5pkipbfo"/><path fill="url(#iRCgeFc)" class="gv4weqbqp"/><path fill="url(#ixpg8Zd)" class="gv4weqbqp"/><g filter="url(#ib1E5Me)"><circle fill="url(#iikDmOc)" class="s403b1bme"/></g><g filter="url(#iWGqOfd)"><circle fill="url(#iWDKqUm)" class="s403b1bme"/></g><g filter="url(#iXY5Znt)"><circle class="yd52whbyv"/><circle fill="url(#iPQQrsv)" class="jzip52bwx"/></g><g filter="url(#imJ3pAd)"><circle fill="url(#iiCbEmV)" class="cy10wjbrz"/><circle fill="url(#iM6y2mc)" class="cy10wjbrz"/></g><g filter="url(#i4qWI6d)"><circle class="t5zfaupib"/><circle fill="url(#iHn20Sc)" class="ff2pzkbkw"/><circle fill="url(#iLicuBe)" class="ff2pzkbkw"/></g><g filter="url(#idvK7Pb)"><path fill="url(#i62ywKc)" class="ka5_isbaj"/><path fill="url(#iRBPnXd)" class="ka5_isbaj"/><path fill="url(#idq2nze)" class="ka5_isbaj"/><path fill="url(#i8rSBKc)" class="ka5_isbaj"/><path fill="url(#igqE1id)" class="ka5_isbaj"/><path fill="url(#iVlPnkb)" class="ka5_isbaj"/><path fill="url(#iAvXryd)" class="ka5_isbaj"/></g><path fill="url(#iqbpZvd)" class="por9u0bvi"/><g filter="url(#i3rczgj)"><path fill="url(#iRwVZEc)" class="vysy7tb9y"/></g><g filter="url(#i3d8DHI)"><path class="u31c_ufnl"/><path fill="url(#i2I1qFe)" class="jx_dj9b9h"/><path fill="url(#irXm1Id)" class="jx_dj9b9h"/><path fill="url(#i2ZKCud)" class="jx_dj9b9h"/><path fill="url(#iK0cdQF)" class="jx_dj9b9h"/><path fill="url(#iYTnIKs)" class="jx_dj9b9h"/></g><path fill="url(#idBUdBd)" class="jx_dj9b9h"/><path fill="url(#i6BTLFI)" class="jx_dj9b9h"/><g filter="url(#iUFafey)"><path class="dwlpxobei"/><path fill="url(#iN8NhRd)" class="pof8zwb8o"/></g><g filter="url(#ihQ3Sec)"><path class="ywaigjb4j"/></g><g filter="url(#iGYRWne)"><path stroke="url(#ilVkRAd)" class="gz_ds4bnu"/></g><g filter="url(#i4TQAPx)"><path stroke="url(#iPxiSGd)" class="plhjfjbok"/></g><path fill="url(#iMM2SFb)" class="n5zw29vdc"/><path fill="url(#iefNkDm)" class="n5zw29vdc"/><g filter="url(#i0TsA7d)"><path fill="url(#ix21Ape)" class="b3df21bsr"/></g><g filter="url(#i78wS1c)"><path fill="url(#itaxOqc)" clip-rule="evenodd" class="g8u3x98mu"/></g><path class="auroitb_k"/><g filter="url(#iV7590b)"><path fill="url(#ift1uPe)" class="ek3xe5bet"/><path fill="url(#ivX3g9c)" class="ek3xe5bet"/><path fill="url(#i2u6ylz)" class="ek3xe5bet"/><path fill="url(#imDxMLb)" class="ek3xe5bet"/><path fill="url(#irigmSb)" class="ek3xe5bet"/></g><path fill="url(#ifo2Hne)" class="qkmymyboo"/><path fill="url(#ivulC4c)" class="qkmymyboo"/><path fill="url(#ilQUo5b)" class="g22dp_xol"/><path fill="url(#ivUPDTb)" class="g22dp_xol"/><path fill="url(#immj7eb)" class="g22dp_xol"/><path fill="url(#iLMoqZc)" class="g22dp_xol"/><g filter="url(#iZDyxlc)"><path class="mdwb7mbos"/></g><g filter="url(#ir3PDWM)"><path class="cwdjdi31a"/></g><g filter="url(#iyQhqnd)"><path class="h0l-_6byw"/></g><g filter="url(#ik6VGpd)"><path stroke="url(#iesvLPW)" class="bnad76bsg"/></g><g filter="url(#iYbPfMc)"><path stroke="url(#infxEAd)" class="ef-qo4aif"/></g><defs><radialGradient id="iV608xe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.38721 2.45336 -5.57243 -14.5076 21.385 26.447)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="yo8dvabcv"/><stop offset="1" class="yzuqint-c"/></radialGradient><radialGradient id="iTkswTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.84375 -6.97792 0 16 18.244)" gradientUnits="userSpaceOnUse"><stop offset=".503" class="lci483bsi"/><stop offset="1" class="y0h0v45io"/></radialGradient><radialGradient id="iRCgeFc" cx="0" cy="0" r="1" gradientTransform="matrix(2.32812 3.40625 -3.8571 2.63627 14.712 20.796)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="tni2q-bze"/><stop offset=".878" class="i0dwzz3lc"/></radialGradient><radialGradient id="iikDmOc" cx="0" cy="0" r="1" gradientTransform="matrix(2.22444 0 0 3.89278 7.854 13.417)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iPQQrsv" cx="0" cy="0" r="1" gradientTransform="matrix(-1.42883 0 0 -1.36676 9.97 13.417)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iM6y2mc" cx="0" cy="0" r="1" gradientTransform="matrix(1.04792 -.76305 .87091 1.19606 22.501 13.081)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iHn20Sc" cx="0" cy="0" r="1" gradientTransform="matrix(1.04102 -1.91472 1.1207 .6093 21.977 14.458)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iLicuBe" cx="0" cy="0" r="1" gradientTransform="matrix(.32867 .32533 -.4194 .4237 22.03 13.417)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="i62ywKc" cx="0" cy="0" r="1" gradientTransform="rotate(153.392 8.39 8.537)scale(9.38575 13.2295)" gradientUnits="userSpaceOnUse"><stop class="f8ymi5bsh"/><stop offset=".778" class="vt7vi2b6n"/></radialGradient><radialGradient id="iRBPnXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.72223 1.56421 -1.3871 -2.41398 18.477 13.39)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="idq2nze" cx="0" cy="0" r="1" gradientTransform="rotate(-79.217 19.85 2.976)scale(5.77211 6.78413)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="i8rSBKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.8213 -13.0873 0 16.648 10.125)" gradientUnits="userSpaceOnUse"><stop offset=".597" class="ld8ox30ss"/><stop offset="1" class="e1cwwpb2d"/></radialGradient><radialGradient id="igqE1id" cx="0" cy="0" r="1" gradientTransform="rotate(171.687 7.854 8.454)scale(7.47512 13.9365)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iVlPnkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.61307 2.13466 0 18.995 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iAvXryd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.90636 2.01116 0 13.55 11.948)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iqbpZvd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.738 0 0 -6.21557 22.6 13.91)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="i2I1qFe" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.443 6.882)scale(7.1063 12.0849)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="i2ZKCud" cx="0" cy="0" r="1" gradientTransform="matrix(-.0847 -2.35957 1.15884 -.0416 10.673 9.037)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iK0cdQF" cx="0" cy="0" r="1" gradientTransform="matrix(1.08903 -2.49268 2.03298 .88819 21.347 11.216)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="iYTnIKs" cx="0" cy="0" r="1" gradientTransform="matrix(1.25844 1.56149 -1.37869 1.11111 15.006 2.514)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="idBUdBd" cx="0" cy="0" r="1" gradientTransform="matrix(.2299 .99278 -1.63213 .37797 16.87 2.514)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="i6BTLFI" cx="0" cy="0" r="1" gradientTransform="rotate(51.044 .313 13.328)scale(1.4627 3.27736)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="iN8NhRd" cx="0" cy="0" r="1" gradientTransform="rotate(-80.201 15.94 -5.945)scale(.77601 2.29578)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iMM2SFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92987 3.82055 -4.53851 -1.1046 22.424 13.983)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset=".909" class="by5wrxbms"/></radialGradient><radialGradient id="iefNkDm" cx="0" cy="0" r="1" gradientTransform="matrix(.35375 .48515 -.41214 .30052 21.524 14.307)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="itaxOqc" cx="0" cy="0" r="1" gradientTransform="matrix(1.60227 1.22796 -.50064 .65325 11.995 12.41)" gradientUnits="userSpaceOnUse"><stop class="jjxkzzqcm"/><stop offset="1" class="d60chicaf"/></radialGradient><radialGradient id="ift1uPe" cx="0" cy="0" r="1" gradientTransform="rotate(104.051 5.905 14.326)scale(10.3219 9.11334)" gradientUnits="userSpaceOnUse"><stop offset=".542" class="u50afqb1a"/><stop offset=".858" class="qvwzixbvn"/></radialGradient><radialGradient id="ivX3g9c" cx="0" cy="0" r="1" gradientTransform="matrix(.98633 2.57228 -.42433 .1627 15.499 11.718)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="bxj8_irob"/><stop offset="1" class="tn7fpxbgu"/></radialGradient><radialGradient id="i2u6ylz" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 3.84375 -.63406 .16238 17.314 9.65)" gradientUnits="userSpaceOnUse"><stop class="bxj8_irob"/><stop offset="1" class="tn7fpxbgu"/></radialGradient><radialGradient id="imDxMLb" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 4.375 -.54534 .0818 19.595 8.838)" gradientUnits="userSpaceOnUse"><stop class="bxj8_irob"/><stop offset="1" class="tn7fpxbgu"/></radialGradient><radialGradient id="irigmSb" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 6.773 15.291)scale(3.93108 .49375)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="bxj8_irob"/><stop offset="1" class="tn7fpxbgu"/></radialGradient><radialGradient id="ifo2Hne" cx="0" cy="0" r="1" gradientTransform="rotate(165.742 9.818 11.335)scale(3.42011 2.21707)" gradientUnits="userSpaceOnUse"><stop class="jyajb3b9r"/><stop offset="1" class="ltsdp7lah"/></radialGradient><radialGradient id="ivUPDTb" cx="0" cy="0" r="1" gradientTransform="matrix(2.29332 10.73456 -3.15485 .674 23.298 21.385)" gradientUnits="userSpaceOnUse"><stop class="nzzn1bz-b"/><stop offset="1" class="ec89a6biv"/></radialGradient><filter id="i0Z4Bwd" width="20.98" height="11.16" x="6.01" y="19.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.501961 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4120"/></filter><filter id="ib1E5Me" width="4.432" height="4.232" x="7.854" y="11.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4120"/></filter><filter id="iWGqOfd" width="4.382" height="4.482" x="7.854" y="11.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4120"/></filter><filter id="iXY5Znt" width="3.322" height="3.322" x="8.309" y="11.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4120" stdDeviation=".2"/></filter><filter id="imJ3pAd" width="4.482" height="4.482" x="19.913" y="11.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4120"/></filter><filter id="i4qWI6d" width="3.522" height="3.522" x="20.268" y="11.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4120" stdDeviation=".25"/></filter><filter id="idvK7Pb" width="13.149" height="15.646" x="9.451" y="6.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4120"/></filter><filter id="i3rczgj" width="9.382" height="7.887" x="14.204" y="4.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4120" stdDeviation="1"/></filter><filter id="i3d8DHI" width="15.973" height="10.696" x="8.002" y="2.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4120"/></filter><filter id="iUFafey" width="3.71" height="2.267" x="17.488" y="8.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4120"/></filter><filter id="ihQ3Sec" width="3.71" height="2.267" x="10.962" y="8.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4120"/></filter><filter id="iGYRWne" width="3.844" height="2.047" x="17.344" y="8.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4120" stdDeviation=".25"/></filter><filter id="i4TQAPx" width="3.943" height="2.119" x="10.728" y="9.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4120" stdDeviation=".25"/></filter><filter id="i0TsA7d" width="12.214" height="13.502" x="12.145" y="7.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4120" stdDeviation=".625"/></filter><filter id="i78wS1c" width="3.412" height="1.462" x="11.792" y="12.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.235294 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4120"/></filter><filter id="iV7590b" width="11.547" height="12.796" x="13.464" y="7.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.584314 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4120"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.52549 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4120" result="effect2_innerShadow_4002_4120"/></filter><filter id="iZDyxlc" width="2.469" height="5.75" x="17.844" y="8.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4120" stdDeviation=".25"/></filter><filter id="ir3PDWM" width="2.75" height="4.625" x="15.781" y="9.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4120" stdDeviation=".25"/></filter><filter id="iyQhqnd" width="2.844" height="3.75" x="13.969" y="11.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4120" stdDeviation=".25"/></filter><filter id="ik6VGpd" width="3.688" height="7.656" x="21.064" y="11.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4120" stdDeviation=".25"/></filter><filter id="iYbPfMc" width="2.422" height="10.188" x="20.204" y="8.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4120" stdDeviation=".25"/></filter><linearGradient id="ixpg8Zd" x1="13.071" x2="14.551" y1="21.592" y2="21.592" gradientUnits="userSpaceOnUse"><stop class="h_yxfzbce"/><stop offset="1" class="t_2v37bum"/></linearGradient><linearGradient id="iWDKqUm" x1="7.854" x2="11.746" y1="13.532" y2="13.532" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iiCbEmV" x1="23.407" x2="22.369" y1="12.033" y2="15.248" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iRwVZEc" x1="15.315" x2="25.639" y1="10.127" y2="6.431" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="irXm1Id" x1="9.827" x2="13.506" y1="13.079" y2="6.544" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="ilVkRAd" x1="19.757" x2="19.224" y1="9.909" y2="8.82" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iPxiSGd" x1="13.033" x2="11.525" y1="9.747" y2="9.115" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="ix21Ape" x1="18.252" x2="15.551" y1="8.563" y2="19.229" gradientUnits="userSpaceOnUse"><stop class="v6g2nzb8z"/><stop offset="1" class="hktd39bvl"/></linearGradient><linearGradient id="ivulC4c" x1="20.454" x2="20.552" y1="19.537" y2="19.901" gradientUnits="userSpaceOnUse"><stop offset=".245" class="cif2-ibcw"/><stop offset="1" class="z12oxsbsi"/></linearGradient><linearGradient id="ilQUo5b" x1="19.704" x2="26.142" y1="28.229" y2="26.854" gradientUnits="userSpaceOnUse"><stop class="rx4h2ue1h"/><stop offset="1" class="n3x1ut3_u"/></linearGradient><linearGradient id="immj7eb" x1="18.5" x2="19.719" y1="27.901" y2="27.526" gradientUnits="userSpaceOnUse"><stop class="dfx3e9_rs"/><stop offset="1" class="gipxjq48x"/></linearGradient><linearGradient id="iLMoqZc" x1="20.154" x2="20.498" y1="20.494" y2="21.932" gradientUnits="userSpaceOnUse"><stop offset=".19" class="k68bkmf2g"/><stop offset="1" class="ll1_3bc-l"/></linearGradient><linearGradient id="iesvLPW" x1="22.908" x2="22.908" y1="12.604" y2="18.51" gradientUnits="userSpaceOnUse"><stop offset=".452" class="wff136bxr"/><stop offset="1" class="aq9f4p8od"/></linearGradient><linearGradient id="infxEAd" x1="21.415" x2="21.415" y1="8.916" y2="17.354" gradientUnits="userSpaceOnUse"><stop offset=".452" class="wff136bxr"/><stop offset="1" class="aq9f4p8od"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-facepalming-medium-light" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aq9f4p8od {
  stop-color: var(--svg-color--f0c19f, #F0C19F);
  stop-opacity: 0;
}

.auroitb_k {
  fill: var(--svg-color--87004c, #87004C);
  d: path("M18.191 18.013a2.47 2.47 0 0 0-2.06-1.12c-.861 0-1.618.45-2.059 1.12c-.095.143.039.316.192.297h3.726c.164 0 .297-.144.201-.297");
}

.b3df21bsr {
  d: path("M17.44 8.58a.946.946 0 0 1 1.108.75l.356 1.849l-.086-1.383a.946.946 0 1 1 1.888-.117l.197 3.17l.327-.675a.989.989 0 1 1 1.78.863l-.817 1.684c-.174.42-.182.807-.19 1.218c-.009.374-.017.767-.152 1.221c-.236.796-.707 1.433-.913 1.653l-2.634.752c-2.028-.497-2.646-1.652-2.982-2.62a14 14 0 0 0-.658-1.585l-1.162-2.238a.946.946 0 1 1 1.678-.871l.194.371l-.463-1.348a.946.946 0 0 1 1.79-.614l.404 1.18l-.415-2.152a.946.946 0 0 1 .75-1.108");
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bnad76bsg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m23.876 12.604l-.937 1.89a3.56 3.56 0 0 0-.36 1.782c.079.968-.265 1.828-.64 2.234");
}

.bxj8_irob {
  stop-color: var(--svg-color--ba7e5c, #BA7E5C);
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.cif2-ibcw {
  stop-color: var(--svg-color--1b7db4, #1B7DB4);
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cwdjdi31a {
  stroke: var(--svg-color--edc1a4, #EDC1A4);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m16.656 10.699l1 2.875");
}

.cy10wjbrz {
  cx: 22.029px;
  cy: 13.417px;
  r: 2.116px;
}

.d60chicaf {
  stop-color: var(--svg-color--713a2b, #713A2B);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dfx3e9_rs {
  stop-color: var(--svg-color--3476ba, #3476BA);
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.dwlpxobei {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m20.704 9.97l-.002-.002l-.002-.002l-.006-.005l-.015-.012l-.045-.034a3.3 3.3 0 0 0-.683-.369a3.6 3.6 0 0 0-1.892-.2a.677.677 0 0 0 .21 1.336c.505-.08.909.013 1.184.122a2 2 0 0 1 .38.202l.01.008a.677.677 0 0 0 .86-1.045");
}

.e1cwwpb2d {
  stop-color: var(--svg-color--8f6479, #8F6479);
}

.ec89a6biv {
  stop-color: var(--svg-color--1c9ae9, #1C9AE9);
  stop-opacity: 0;
}

.ef-qo4aif {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m21.08 8.916l.671 8.438");
}

.ek3xe5bet {
  d: path("M18.168 7.781a1.1 1.1 0 0 1 1.288.872l.415 2.15l-.1-1.608a1.1 1.1 0 1 1 2.195-.136l.23 3.687l.38-.785a1.15 1.15 0 1 1 2.07 1.004l-.95 1.957c-.203.489-.212.94-.222 1.417c-.01.435-.019.893-.176 1.42c-.275.926-.823 1.668-1.062 1.923l-3.063.875c-2.36-.578-3.078-1.922-3.468-3.047c-.313-.9-.641-1.604-.766-1.844l-1.351-2.602a1.1 1.1 0 0 1 1.952-1.014l.225.432l-.539-1.568a1.1 1.1 0 0 1 2.082-.714l.47 1.372l-.482-2.503a1.1 1.1 0 0 1 .872-1.288");
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.f5pkipbfo {
  d: path("M25.99 30.044v-.39c0-5.39-4.47-9.77-9.99-9.77c-5.52.01-9.99 4.38-9.99 9.77v.39z");
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f8ymi5bsh {
  stop-color: var(--svg-color--fccba2, #FCCBA2);
}

.ff2pzkbkw {
  cx: 22.029px;
  cy: 13.417px;
  r: 1.261px;
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g22dp_xol {
  d: path("M17.317 22.614a1 1 0 0 1 .723-1.221l5.303-1.339a1 1 0 0 1 1.213.718l2.414 9.289h-7.719z");
}

.g8u3x98mu {
  fill-rule: evenodd;
  d: path("M15.065 12.613c.15.11.184.32.074.47a2.02 2.02 0 0 1-1.641.828a2.05 2.05 0 0 1-1.639-.824a.336.336 0 0 1 .538-.403c.256.34.656.555 1.1.555c.457 0 .855-.216 1.099-.552a.337.337 0 0 1 .47-.074");
}

.gipxjq48x {
  stop-color: var(--svg-color--3476ba, #3476BA);
  stop-opacity: 0;
}

.gv4weqbqp {
  d: path("M16.025 23.405c-1.438 0-2.605-.605-2.605-1.969v-3.375c0-1.364 1.167-2.47 2.605-2.47c1.439 0 2.605 1.106 2.605 2.47v3.375c0 1.364-1.166 1.969-2.605 1.969");
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gz_ds4bnu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.094 9.786c.545-.095 1.608-.068 2.344.504");
}

.h_yxfzbce {
  stop-color: var(--svg-color--a97767, #A97767);
}

.h0l-_6byw {
  stroke: var(--svg-color--edc1a4, #EDC1A4);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m14.844 12.73l1.094 2");
}

.hktd39bvl {
  stop-color: var(--svg-color--a16871, #A16871);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.i0dwzz3lc {
  stop-color: var(--svg-color--b2897e, #B2897E);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.ij6q1eb-i {
  fill: var(--svg-color--1d79c4, #1D79C4);
  d: path("M25.99 30.044v-.39c0-5.39-4.47-9.77-9.99-9.77c-5.52.01-9.99 4.38-9.99 9.77v.39z");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jjxkzzqcm {
  stop-color: var(--svg-color--956138, #956138);
}

.jx_dj9b9h {
  d: path("m22.097 5.206l.544.27c.952.474 1.496 1.555 1.292 2.705l-.748 3.853c-.066.398-.33.666-.725.676h-.023s.068-1.15.136-1.825c.055-.55-.04-.717-.544-1.217c-.272-.27-.476-.676-.476-1.082V7.505c0-.338-.272-.609-.544-.677c-.816-.202-2.515-.54-4.963-.54s-4.147.338-4.963.54c-.34.068-.544.338-.544.677v1.081c0 .406-.136.811-.476 1.082l-.204.203c-.272.202-.408.608-.408.946c.068.744.136 1.826.136 1.826q-.032 0-.062-.003a.8.8 0 0 1-.754-.674l-.748-3.853c-.136-1.082.408-2.163 1.36-2.637l.544-.27c.34-.203.68-.473 1.02-.744l1.223-1.284c.748-.676 1.836-.879 2.788-.406c.68.203 1.428.203 2.108 0c1.02-.338 2.176-.067 2.992.676l1.02 1.014c.271.338.611.541 1.02.744");
}

.jyajb3b9r {
  stop-color: var(--svg-color--489ed5, #489ED5);
}

.jzip52bwx {
  cx: 9.971px;
  cy: 13.417px;
  r: 1.261px;
}

.k68bkmf2g {
  stop-color: var(--svg-color--0792d5, #0792D5);
}

.ka5_isbaj {
  d: path("m9.524 12.64l.063.002s-.068-1.081-.136-1.825c0-.338.136-.744.408-.946l.204-.203c.34-.27.476-.676.476-1.082V7.504c0-.338.204-.608.543-.676c.816-.202 2.516-.54 4.964-.54s4.148.338 4.963.54c.272.068.544.338.544.676v1.082c0 .406.204.811.476 1.082c.637.446.597.691.544 1.217a59 59 0 0 0-.136 1.825h.023l-.337 5.017c-.203 2.244-1.967 3.807-4.07 3.807h-4.069c-2.17 0-3.866-1.563-4.07-3.806z");
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.lci483bsi {
  stop-color: var(--svg-color--115284, #115284);
}

.ld8ox30ss {
  stop-color: var(--svg-color--ac7179, #AC7179);
  stop-opacity: 0;
}

.ll1_3bc-l {
  stop-color: var(--svg-color--0792d5, #0792D5);
  stop-opacity: 0;
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.ltsdp7lah {
  stop-color: var(--svg-color--20669e, #20669E);
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.mdwb7mbos {
  stroke: var(--svg-color--edc1a4, #EDC1A4);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m18.719 8.918l.718 4");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.n3x1ut3_u {
  stop-color: var(--svg-color--45aaed, #45AAED);
}

.n5zw29vdc {
  d: path("M21.596 14.355a2 2 0 0 0 1.09-.372v1.123a2.62 2.62 0 0 1-1.616 2.435c.205-.437.346-.914.417-1.423z");
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nzzn1bz-b {
  stop-color: var(--svg-color--47c9ff, #47C9FF);
}

.plhjfjbok {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.478 10.443c.415-.366 1.32-.752 2.443-.573");
}

.pof8zwb8o {
  d: path("m20.704 9.97l-.002-.002l-.002-.002l-.006-.005l-.015-.012l-.045-.034a3.3 3.3 0 0 0-.683-.369a3.6 3.6 0 0 0-1.892-.2a.677.677 0 0 0 .21 1.336c.505-.08.909.013 1.184.122a2 2 0 0 1 .38.202l.01.008a.677.677 0 0 0 .86-1.045");
}

.por9u0bvi {
  d: path("M9.45 10.817c0-.338.137-.744.409-.946l.204-.203c.34-.27.476-.676.476-1.082V7.504c0-.338.204-.608.543-.676c.816-.202 2.516-.54 4.964-.54s4.148.338 4.963.54c.272.068.544.338.544.676v1.082c0 .406.204.811.476 1.082c.637.446.597.691.544 1.217a59 59 0 0 0-.136 1.825h.023l-.337 5.017c-.203 2.244-1.967 3.807-4.07 3.807h-4.069c-2.17 0-3.866-1.563-4.07-3.806c-.176-2.303-.253-4.612-.463-6.91");
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.qkmymyboo {
  d: path("M17.88 20.54a.25.25 0 0 1 .182-.302l4.733-1.205a.25.25 0 0 1 .305.184l.274 1.13l-5.229 1.267z");
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvwzixbvn {
  stop-color: var(--svg-color--ce8e86, #CE8E86);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.rx4h2ue1h {
  stop-color: var(--svg-color--2474c2, #2474C2);
}

.s403b1bme {
  cx: 9.971px;
  cy: 13.417px;
  r: 2.116px;
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t_2v37bum {
  stop-color: var(--svg-color--a97767, #A97767);
  stop-opacity: 0;
}

.t5zfaupib {
  cx: 22.029px;
  cy: 13.417px;
  r: 1.261px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.tn7fpxbgu {
  stop-color: var(--svg-color--ba7e5c, #BA7E5C);
  stop-opacity: 0;
}

.tni2q-bze {
  stop-color: var(--svg-color--99656b, #99656B);
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.u31c_ufnl {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m22.097 5.206l.544.27c.952.474 1.496 1.555 1.292 2.705l-.748 3.853c-.066.398-.33.666-.725.676h-.023s.068-1.15.136-1.825c.055-.55-.04-.717-.544-1.217c-.272-.27-.476-.676-.476-1.082V7.505c0-.338-.272-.609-.544-.677c-.816-.202-2.515-.54-4.963-.54s-4.147.338-4.963.54c-.34.068-.544.338-.544.677v1.081c0 .406-.136.811-.476 1.082l-.204.203c-.272.202-.408.608-.408.946c.068.744.136 1.826.136 1.826q-.032 0-.062-.003a.8.8 0 0 1-.754-.674l-.748-3.853c-.136-1.082.408-2.163 1.36-2.637l.544-.27c.34-.203.68-.473 1.02-.744l1.223-1.284c.748-.676 1.836-.879 2.788-.406c.68.203 1.428.203 2.108 0c1.02-.338 2.176-.067 2.992.676l1.02 1.014c.271.338.611.541 1.02.744");
}

.u50afqb1a {
  stop-color: var(--svg-color--e8b096, #E8B096);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.v6g2nzb8z {
  stop-color: var(--svg-color--a26441, #A26441);
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vt7vi2b6n {
  stop-color: var(--svg-color--c18b75, #C18B75);
}

.vysy7tb9y {
  d: path("m21.013 6.288l-3.9 1.3a1.328 1.328 0 0 0 .595 2.575l3.879-.52z");
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wff136bxr {
  stop-color: var(--svg-color--f0c19f, #F0C19F);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.y0h0v45io {
  stop-color: var(--svg-color--115284, #115284);
  stop-opacity: 0;
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yd52whbyv {
  cx: 9.971px;
  cy: 13.417px;
  r: 1.261px;
  fill: var(--svg-color--b47a6c, #B47A6C);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yo8dvabcv {
  stop-color: var(--svg-color--1d6fc7, #1D6FC7);
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.ywaigjb4j {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M11.206 9.97h.002l.002-.003l.006-.005l.015-.012a2 2 0 0 1 .196-.136c.126-.079.306-.177.532-.267a3.6 3.6 0 0 1 1.892-.2a.676.676 0 1 1-.21 1.336a2.24 2.24 0 0 0-1.184.122a2 2 0 0 0-.391.21a.676.676 0 0 1-.86-1.044");
}

.yzuqint-c {
  stop-color: var(--svg-color--1d6fc7, #1D6FC7);
  stop-opacity: 0;
}

.z12oxsbsi {
  stop-color: var(--svg-color--1b7db4, #1B7DB4);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
