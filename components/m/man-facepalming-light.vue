<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9Bb7Ee)"><path class="wn24yqb3m"/><path fill="url(#i8jxs8b)" class="qw5j7wbka"/></g><path fill="url(#ikdAPBc)" class="qw5j7wbka"/><path fill="url(#i5qL7Ka)" class="m5d3f0bsu"/><path fill="url(#iQqHA2D)" class="m5d3f0bsu"/><g filter="url(#iq9JYvv)"><circle fill="url(#iM5icec)" class="m7icz5ima"/></g><g filter="url(#i582c5a)"><circle fill="url(#iGFfvOd)" class="m7icz5ima"/></g><g filter="url(#iWQfrCc)"><circle fill="url(#ie92Muc)" class="itpzcoy1y"/></g><g filter="url(#iJXID3b)"><circle fill="url(#imr1U7V)" class="u5vh5gz8f"/><circle fill="url(#iAYkJKb)" class="u5vh5gz8f"/></g><g filter="url(#ifB6LWc)"><circle class="tfj2j583k"/><circle fill="url(#ivwL1Jc)" class="fe3lu-bnm"/><circle fill="url(#iPTMbce)" class="fe3lu-bnm"/></g><g filter="url(#icBAnmc)"><path fill="url(#irZcTfc)" class="vste_sqbc"/><path fill="url(#iae3vbe)" class="vste_sqbc"/><path fill="url(#iAhywLb)" class="vste_sqbc"/><path fill="url(#izJlbMd)" class="vste_sqbc"/><path fill="url(#iCiFqNd)" class="vste_sqbc"/><path fill="url(#it68Rac)" class="vste_sqbc"/></g><g filter="url(#iiMGlSA)"><path fill="url(#imi7Fbd)" class="f69ody-nj"/></g><g filter="url(#io09grd)"><path class="olroz5del"/><path fill="url(#iraAoYb)" class="kfhvuub5h"/><path fill="url(#iQL5Fee)" class="kfhvuub5h"/><path fill="url(#iDetdxd)" class="kfhvuub5h"/><path fill="url(#i9dr5he)" class="kfhvuub5h"/><path fill="url(#iyCF70c)" class="kfhvuub5h"/></g><g filter="url(#iqyqHsc)"><path class="jn723zbsp"/><path fill="url(#iWUqZYK)" class="kfhvuub5h"/><path fill="url(#iXXncdd)" class="kfhvuub5h"/><path fill="url(#ixwM06b)" class="kfhvuub5h"/><path fill="url(#iwpv1ge)" class="kfhvuub5h"/></g><g filter="url(#i17r3Cd)"><path class="ug4j93b7s"/></g><g filter="url(#iKuoRhX)"><path class="wmk8g3b6p"/></g><g filter="url(#iByWgPe)"><path stroke="url(#iwxDZGo)" class="dhctfto1o"/></g><g filter="url(#ifOArjb)"><path stroke="url(#ixJ1tFd)" class="z9whymb-f"/></g><path fill="url(#iWoY9yc)" class="qy3j4ebwn"/><path fill="url(#ibSX68b)" class="qy3j4ebwn"/><g filter="url(#iDJG1be)"><path fill="url(#ibZEGld)" class="z0449obxk"/></g><g filter="url(#i0w4wSb)"><path fill="url(#iCVy41b)" clip-rule="evenodd" class="y68js-b7g"/></g><path class="ulzz4vbrv"/><g filter="url(#iABAUgQ)"><path fill="url(#iOzPFJJ)" class="pokgrdbsn"/><path fill="url(#inlckTd)" class="pokgrdbsn"/><path fill="url(#iArQeJd)" class="pokgrdbsn"/><path fill="url(#iglGxdc)" class="pokgrdbsn"/><path fill="url(#insAsFe)" class="pokgrdbsn"/></g><path fill="url(#i19Ydvd)" class="tx_0s9b2p"/><path fill="url(#i5mrzJe)" class="tx_0s9b2p"/><path fill="url(#iD0LEad)" class="l5-ivhb1g"/><path fill="url(#iAsJltR)" class="l5-ivhb1g"/><path fill="url(#i0XsAbe)" class="l5-ivhb1g"/><path fill="url(#il8QOSc)" class="l5-ivhb1g"/><g filter="url(#iwAjdcN)"><path class="pnrttkbir"/></g><g filter="url(#iFh10vc)"><path class="daolesbqz"/></g><g filter="url(#i2MfX0H)"><path class="ko_tjjl5j"/></g><g filter="url(#iyCd0sd)"><path stroke="url(#iBh85Kd)" class="tdxkfxo2m"/></g><g filter="url(#isoHlrd)"><path stroke="url(#iyUh5rb)" class="c4srj8jyc"/></g><defs><radialGradient id="i8jxs8b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.38721 2.45336 -5.57243 -14.5076 21.385 26.387)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="yo8dvabcv"/><stop offset="1" class="yzuqint-c"/></radialGradient><radialGradient id="ikdAPBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.84375 -6.97792 0 16 18.184)" gradientUnits="userSpaceOnUse"><stop offset=".503" class="lci483bsi"/><stop offset="1" class="y0h0v45io"/></radialGradient><radialGradient id="i5qL7Ka" cx="0" cy="0" r="1" gradientTransform="matrix(2.32812 3.40625 -3.8571 2.63627 14.713 20.735)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="xwix69baw"/><stop offset=".878" class="hozz1xpgd"/></radialGradient><radialGradient id="iM5icec" cx="0" cy="0" r="1" gradientTransform="matrix(2.22444 0 0 3.89278 7.854 13.357)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iGFfvOd" cx="0" cy="0" r="1" gradientTransform="matrix(2.22444 0 0 3.89278 7.854 13.357)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iAYkJKb" cx="0" cy="0" r="1" gradientTransform="matrix(1.04792 -.76305 .87091 1.19606 22.501 13.021)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="ivwL1Jc" cx="0" cy="0" r="1" gradientTransform="matrix(1.04102 -1.91472 1.1207 .6093 21.977 14.398)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iPTMbce" cx="0" cy="0" r="1" gradientTransform="matrix(.32867 .32533 -.4194 .4237 22.03 13.357)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iae3vbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.7271 -14.5615 0 16.032 10.93)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="hj55wpbwm"/><stop offset="1" class="eten0abve"/></radialGradient><radialGradient id="iCiFqNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.65683 2.03918 0 18.963 11.745)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="it68Rac" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.76304 2.1925 0 13.185 11.703)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iraAoYb" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.458 6.852)scale(7.1063 12.0849)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iDetdxd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0847 -2.35957 1.15884 -.0416 10.673 8.977)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="i9dr5he" cx="0" cy="0" r="1" gradientTransform="matrix(1.08903 -2.49268 2.03298 .88819 21.347 11.155)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="iyCF70c" cx="0" cy="0" r="1" gradientTransform="matrix(1.25844 1.56149 -1.37869 1.11111 15.006 2.454)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iWUqZYK" cx="0" cy="0" r="1" gradientTransform="matrix(1.0113 -3.74776 1.3898 .37502 21.497 8.152)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iXXncdd" cx="0" cy="0" r="1" gradientTransform="matrix(4.8483 .44616 -.2399 2.6069 19.415 5.921)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ixwM06b" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.12849 -3.29643 0 15.989 2.454)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iwpv1ge" cx="0" cy="0" r="1" gradientTransform="matrix(3.89647 -2.85544 4.47355 6.1045 7.815 11.097)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iWoY9yc" cx="0" cy="0" r="1" gradientTransform="matrix(-.92987 3.82055 -4.53851 -1.1046 22.424 13.923)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset=".909" class="by5wrxbms"/></radialGradient><radialGradient id="ibSX68b" cx="0" cy="0" r="1" gradientTransform="matrix(.35375 .48515 -.41214 .30052 21.525 14.246)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iCVy41b" cx="0" cy="0" r="1" gradientTransform="matrix(1.60227 1.22796 -.50064 .65325 11.995 12.35)" gradientUnits="userSpaceOnUse"><stop class="ye_pt1bdn"/><stop offset="1" class="fvrh376zw"/></radialGradient><radialGradient id="iOzPFJJ" cx="0" cy="0" r="1" gradientTransform="rotate(102.826 5.824 14.48)scale(9.56418 8.44437)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="qtml67ysr"/><stop offset=".692" class="qtml67ysr"/><stop offset="1" class="ndg2zkbnv"/></radialGradient><radialGradient id="inlckTd" cx="0" cy="0" r="1" gradientTransform="matrix(1 2.48437 -.40982 .16496 15.486 11.746)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="i--8zbrku"/><stop offset="1" class="rusf7f63f"/></radialGradient><radialGradient id="iArQeJd" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 3.84375 -.63406 .16238 17.314 9.59)" gradientUnits="userSpaceOnUse"><stop class="i--8zbrku"/><stop offset="1" class="rusf7f63f"/></radialGradient><radialGradient id="iglGxdc" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 4.375 -.54534 .0818 19.595 8.778)" gradientUnits="userSpaceOnUse"><stop class="i--8zbrku"/><stop offset="1" class="rusf7f63f"/></radialGradient><radialGradient id="insAsFe" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 6.8 15.261)scale(3.93108 .49375)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="i--8zbrku"/><stop offset="1" class="rusf7f63f"/></radialGradient><radialGradient id="i19Ydvd" cx="0" cy="0" r="1" gradientTransform="rotate(165.742 9.822 11.304)scale(3.42011 2.21707)" gradientUnits="userSpaceOnUse"><stop class="jyajb3b9r"/><stop offset="1" class="ltsdp7lah"/></radialGradient><radialGradient id="iAsJltR" cx="0" cy="0" r="1" gradientTransform="matrix(2.29332 10.73456 -3.15485 .674 23.298 21.325)" gradientUnits="userSpaceOnUse"><stop class="nzzn1bz-b"/><stop offset="1" class="ec89a6biv"/></radialGradient><filter id="i9Bb7Ee" width="20.98" height="11.16" x="6.01" y="19.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.501961 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4123"/></filter><filter id="iq9JYvv" width="4.432" height="4.232" x="7.854" y="11.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4123"/></filter><filter id="i582c5a" width="4.432" height="4.232" x="7.854" y="11.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4123"/></filter><filter id="iWQfrCc" width="3.522" height="3.522" x="8.209" y="11.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4123" stdDeviation=".25"/></filter><filter id="iJXID3b" width="4.482" height="4.482" x="19.913" y="10.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4123"/></filter><filter id="ifB6LWc" width="3.522" height="3.522" x="20.268" y="11.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4123" stdDeviation=".25"/></filter><filter id="icBAnmc" width="13.149" height="15.496" x="9.451" y="6.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4123"/></filter><filter id="iiMGlSA" width="9.382" height="7.887" x="14.204" y="4.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4123" stdDeviation="1"/></filter><filter id="io09grd" width="15.973" height="10.696" x="8.002" y="1.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4123"/></filter><filter id="iqyqHsc" width="15.973" height="10.696" x="8.002" y="1.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4123"/></filter><filter id="i17r3Cd" width="3.71" height="2.267" x="17.488" y="8.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4123"/></filter><filter id="iKuoRhX" width="3.71" height="2.267" x="10.962" y="8.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4123"/></filter><filter id="iByWgPe" width="3.844" height="2.047" x="17.344" y="8.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4123" stdDeviation=".25"/></filter><filter id="ifOArjb" width="3.193" height="1.369" x="11.103" y="9.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4123" stdDeviation=".125"/></filter><filter id="iDJG1be" width="12.214" height="13.502" x="12.145" y="7.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4123" stdDeviation=".625"/></filter><filter id="i0w4wSb" width="3.412" height="1.462" x="11.792" y="12.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0980392 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4123"/></filter><filter id="iABAUgQ" width="11.547" height="12.795" x="13.464" y="7.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.662745 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4123"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.627451 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4123" result="effect2_innerShadow_4002_4123"/></filter><filter id="iwAjdcN" width="2.469" height="5.75" x="17.844" y="7.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4123" stdDeviation=".25"/></filter><filter id="iFh10vc" width="2.75" height="4.625" x="15.781" y="9.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4123" stdDeviation=".25"/></filter><filter id="i2MfX0H" width="2.844" height="3.75" x="13.969" y="11.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4123" stdDeviation=".25"/></filter><filter id="iyCd0sd" width="3.688" height="7.656" x="21.064" y="11.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4123" stdDeviation=".25"/></filter><filter id="isoHlrd" width="2.422" height="10.188" x="20.204" y="7.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4123" stdDeviation=".25"/></filter><linearGradient id="iQqHA2D" x1="13.071" x2="14.551" y1="21.531" y2="21.531" gradientUnits="userSpaceOnUse"><stop class="y0sidibnc"/><stop offset="1" class="rkdpy0b4x"/></linearGradient><linearGradient id="ie92Muc" x1="9.971" x2="9.159" y1="13.71" y2="13.71" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="imr1U7V" x1="23.407" x2="22.369" y1="11.973" y2="15.188" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="irZcTfc" x1="21.105" x2="11.425" y1="13.851" y2="15.293" gradientUnits="userSpaceOnUse"><stop class="ydq0kpc8x"/><stop offset="1" class="e-sxlzbkb"/></linearGradient><linearGradient id="iAhywLb" x1="8.837" x2="13.093" y1="15.787" y2="15.931" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="izJlbMd" x1="9.149" x2="11.534" y1="17.268" y2="17.183" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="imi7Fbd" x1="21.25" x2="15.931" y1="7.144" y2="14.081" gradientUnits="userSpaceOnUse"><stop class="qdgk9rz5g"/><stop offset="1" class="lgwcu6epc"/></linearGradient><linearGradient id="iQL5Fee" x1="9.827" x2="13.506" y1="13.018" y2="6.484" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iwxDZGo" x1="19.757" x2="19.224" y1="9.848" y2="8.76" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="ixJ1tFd" x1="13.033" x2="11.525" y1="9.686" y2="9.054" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ibZEGld" x1="18.252" x2="15.551" y1="8.503" y2="19.169" gradientUnits="userSpaceOnUse"><stop class="ev792wbyk"/><stop offset="1" class="ynngk8bxm"/></linearGradient><linearGradient id="i5mrzJe" x1="20.454" x2="20.552" y1="19.477" y2="19.84" gradientUnits="userSpaceOnUse"><stop offset=".245" class="cif2-ibcw"/><stop offset="1" class="z12oxsbsi"/></linearGradient><linearGradient id="iD0LEad" x1="19.704" x2="26.142" y1="28.168" y2="26.793" gradientUnits="userSpaceOnUse"><stop class="rx4h2ue1h"/><stop offset="1" class="n3x1ut3_u"/></linearGradient><linearGradient id="i0XsAbe" x1="18.5" x2="19.719" y1="27.84" y2="27.465" gradientUnits="userSpaceOnUse"><stop class="dfx3e9_rs"/><stop offset="1" class="gipxjq48x"/></linearGradient><linearGradient id="il8QOSc" x1="20.154" x2="20.498" y1="20.434" y2="21.872" gradientUnits="userSpaceOnUse"><stop offset=".19" class="k68bkmf2g"/><stop offset="1" class="ll1_3bc-l"/></linearGradient><linearGradient id="iBh85Kd" x1="24.109" x2="21.939" y1="12.368" y2="16.18" gradientUnits="userSpaceOnUse"><stop class="lk7dbcc7r"/><stop offset="1" class="tmqbcuz_q"/></linearGradient><linearGradient id="iyUh5rb" x1="21.832" x2="19.23" y1="8.605" y2="9.715" gradientUnits="userSpaceOnUse"><stop class="lk7dbcc7r"/><stop offset="1" class="tmqbcuz_q"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-facepalming-light" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c4srj8jyc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m21.08 8.856l.671 8.437");
}

.cif2-ibcw {
  stop-color: var(--svg-color--1b7db4, #1B7DB4);
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.daolesbqz {
  stroke: var(--svg-color--ffd6bf, #FFD6BF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m16.656 10.639l1 2.875");
}

.dfx3e9_rs {
  stop-color: var(--svg-color--3476ba, #3476BA);
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dhctfto1o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.094 9.726c.545-.096 1.608-.068 2.344.504");
}

.e-sxlzbkb {
  stop-color: var(--svg-color--daa594, #DAA594);
}

.ec89a6biv {
  stop-color: var(--svg-color--1c9ae9, #1C9AE9);
  stop-opacity: 0;
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.eten0abve {
  stop-color: var(--svg-color--947187, #947187);
}

.ev792wbyk {
  stop-color: var(--svg-color--c47f5c, #C47F5C);
}

.f69ody-nj {
  d: path("m21.013 6.227l-3.9 1.3a1.328 1.328 0 0 0 .595 2.576l3.879-.52z");
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fe3lu-bnm {
  cx: 22.029px;
  cy: 13.357px;
  r: 1.261px;
}

.ft5dv1b6b {
  fill: none;
}

.fvrh376zw {
  stop-color: var(--svg-color--191017, #191017);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gipxjq48x {
  stop-color: var(--svg-color--3476ba, #3476BA);
  stop-opacity: 0;
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.hj55wpbwm {
  stop-color: var(--svg-color--ca9288, #CA9288);
  stop-opacity: 0;
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hozz1xpgd {
  stop-color: var(--svg-color--c19b96, #C19B96);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.i--8zbrku {
  stop-color: var(--svg-color--d79a81, #D79A81);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.itpzcoy1y {
  cx: 9.971px;
  cy: 13.357px;
  r: 1.261px;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.jn723zbsp {
  fill: var(--svg-color--242324, #242324);
  d: path("m22.097 5.146l.544.27c.952.473 1.496 1.555 1.292 2.704l-.748 3.854c-.066.398-.33.666-.725.676h-.023s.068-1.15.136-1.825c.055-.55-.04-.717-.544-1.217c-.272-.27-.476-.676-.476-1.082V7.444c0-.338-.272-.608-.544-.676c-.816-.203-2.515-.54-4.963-.54s-4.147.337-4.963.54c-.34.068-.544.338-.544.676v1.082c0 .406-.136.811-.476 1.082l-.204.202c-.272.203-.408.609-.408.947a81 81 0 0 1 .136 1.825q-.032 0-.062-.002a.8.8 0 0 1-.754-.674l-.748-3.853c-.136-1.082.408-2.164 1.36-2.637l.544-.27c.34-.203.68-.474 1.02-.744l1.223-1.284c.748-.677 1.836-.88 2.788-.406c.68.203 1.428.203 2.108 0c1.02-.338 2.176-.068 2.992.676l1.02 1.014c.271.338.611.54 1.02.744");
}

.jyajb3b9r {
  stop-color: var(--svg-color--489ed5, #489ED5);
}

.k68bkmf2g {
  stop-color: var(--svg-color--0792d5, #0792D5);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kfhvuub5h {
  d: path("m22.097 5.146l.544.27c.952.473 1.496 1.555 1.292 2.704l-.748 3.854c-.066.398-.33.666-.725.676h-.023s.068-1.15.136-1.825c.055-.55-.04-.717-.544-1.217c-.272-.27-.476-.676-.476-1.082V7.444c0-.338-.272-.608-.544-.676c-.816-.203-2.515-.54-4.963-.54s-4.147.337-4.963.54c-.34.068-.544.338-.544.676v1.082c0 .406-.136.811-.476 1.082l-.204.202c-.272.203-.408.609-.408.947a81 81 0 0 1 .136 1.825q-.032 0-.062-.002a.8.8 0 0 1-.754-.674l-.748-3.853c-.136-1.082.408-2.164 1.36-2.637l.544-.27c.34-.203.68-.474 1.02-.744l1.223-1.284c.748-.677 1.836-.88 2.788-.406c.68.203 1.428.203 2.108 0c1.02-.338 2.176-.068 2.992.676l1.02 1.014c.271.338.611.54 1.02.744");
}

.ko_tjjl5j {
  stroke: var(--svg-color--ffd6bf, #FFD6BF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m14.844 12.67l1.094 2");
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.l5-ivhb1g {
  d: path("M17.317 22.553a1 1 0 0 1 .723-1.22l5.303-1.34a1 1 0 0 1 1.213.719L26.97 30h-7.719z");
}

.lci483bsi {
  stop-color: var(--svg-color--115284, #115284);
}

.lgwcu6epc {
  stop-color: var(--svg-color--ffe3c4, #FFE3C4);
  stop-opacity: 0;
}

.lk7dbcc7r {
  stop-color: var(--svg-color--ffd6bf, #FFD6BF);
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

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.m5d3f0bsu {
  d: path("M16.025 23.345c-1.438 0-2.605-.605-2.605-1.97v-3.374c0-1.364 1.167-2.47 2.605-2.47c1.439 0 2.605 1.106 2.605 2.47v3.375c0 1.364-1.166 1.968-2.605 1.968");
}

.m7icz5ima {
  cx: 9.971px;
  cy: 13.357px;
  r: 2.116px;
}

.n3x1ut3_u {
  stop-color: var(--svg-color--45aaed, #45AAED);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.ndg2zkbnv {
  stop-color: var(--svg-color--d3918e, #D3918E);
}

.nzzn1bz-b {
  stop-color: var(--svg-color--47c9ff, #47C9FF);
}

.olroz5del {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m22.097 5.146l.544.27c.952.473 1.496 1.555 1.292 2.704l-.748 3.854c-.066.398-.33.666-.725.676h-.023s.068-1.15.136-1.825c.055-.55-.04-.717-.544-1.217c-.272-.27-.476-.676-.476-1.082V7.444c0-.338-.272-.608-.544-.676c-.816-.203-2.515-.54-4.963-.54s-4.147.337-4.963.54c-.34.068-.544.338-.544.676v1.082c0 .406-.136.811-.476 1.082l-.204.202c-.272.203-.408.609-.408.947a81 81 0 0 1 .136 1.825q-.032 0-.062-.002a.8.8 0 0 1-.754-.674l-.748-3.853c-.136-1.082.408-2.164 1.36-2.637l.544-.27c.34-.203.68-.474 1.02-.744l1.223-1.284c.748-.677 1.836-.88 2.788-.406c.68.203 1.428.203 2.108 0c1.02-.338 2.176-.068 2.992.676l1.02 1.014c.271.338.611.54 1.02.744");
}

.pnrttkbir {
  stroke: var(--svg-color--ffd6bf, #FFD6BF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m18.719 8.857l.718 4");
}

.pokgrdbsn {
  d: path("M18.168 7.721a1.1 1.1 0 0 1 1.288.872l.415 2.15l-.1-1.608a1.1 1.1 0 1 1 2.195-.136l.23 3.686l.38-.784a1.15 1.15 0 1 1 2.07 1.004l-.95 1.957c-.203.489-.212.94-.222 1.417c-.01.435-.019.892-.176 1.42c-.275.926-.823 1.667-1.062 1.922l-3.063.875c-2.36-.578-3.078-1.921-3.468-3.046c-.313-.9-.641-1.605-.766-1.844l-1.351-2.603a1.1 1.1 0 0 1 1.952-1.014l.225.433l-.539-1.569a1.1 1.1 0 0 1 2.082-.713l.47 1.372l-.482-2.503a1.1 1.1 0 0 1 .872-1.288");
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qdgk9rz5g {
  stop-color: var(--svg-color--ffe3c4, #FFE3C4);
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qtml67ysr {
  stop-color: var(--svg-color--fecab5, #FECAB5);
}

.qw5j7wbka {
  d: path("M25.99 29.984v-.39c0-5.39-4.47-9.77-9.99-9.77c-5.52.01-9.99 4.38-9.99 9.77v.39z");
}

.qy3j4ebwn {
  d: path("M21.596 14.295a2 2 0 0 0 1.09-.372v1.123a2.62 2.62 0 0 1-1.616 2.435q.309-.658.417-1.423z");
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rkdpy0b4x {
  stop-color: var(--svg-color--b9887b, #B9887B);
  stop-opacity: 0;
}

.rusf7f63f {
  stop-color: var(--svg-color--d79a81, #D79A81);
  stop-opacity: 0;
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rx4h2ue1h {
  stop-color: var(--svg-color--2474c2, #2474C2);
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

.tdxkfxo2m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m23.876 12.543l-.937 1.891a3.56 3.56 0 0 0-.36 1.781c.079.969-.265 1.828-.64 2.235");
}

.tfj2j583k {
  cx: 22.029px;
  cy: 13.357px;
  r: 1.261px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.tmqbcuz_q {
  stop-color: var(--svg-color--ffd6bf, #FFD6BF);
  stop-opacity: 0;
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.tx_0s9b2p {
  d: path("M17.88 20.48a.25.25 0 0 1 .182-.303l4.733-1.204a.25.25 0 0 1 .305.183l.274 1.13l-5.229 1.268z");
}

.u5vh5gz8f {
  cx: 22.029px;
  cy: 13.357px;
  r: 2.116px;
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.ug4j93b7s {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m20.704 9.909l-.002-.001l-.002-.002l-.006-.005l-.015-.012l-.045-.034a3.3 3.3 0 0 0-.683-.369a3.6 3.6 0 0 0-1.892-.201a.677.677 0 0 0 .21 1.336c.505-.08.909.014 1.184.123a2 2 0 0 1 .38.202l.01.007a.677.677 0 0 0 .86-1.044");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ulzz4vbrv {
  fill: var(--svg-color--87004c, #87004C);
  d: path("M18.191 17.952a2.47 2.47 0 0 0-2.06-1.12c-.861 0-1.618.45-2.059 1.12c-.095.144.039.316.192.297h3.726c.164 0 .297-.143.201-.297");
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vste_sqbc {
  d: path("M9.524 12.58q.032.003.063.002s-.068-1.082-.136-1.825c0-.338.136-.744.408-.947l.204-.202c.34-.27.476-.676.476-1.082V7.444c0-.338.204-.608.543-.676c.816-.203 2.516-.54 4.964-.54s4.148.337 4.963.54c.272.068.544.338.544.676v1.082c0 .406.204.811.476 1.082c.637.445.597.69.544 1.217a59 59 0 0 0-.136 1.825h.023l-.337 5.017c-.203 2.243-1.967 3.807-4.07 3.807h-4.069c-2.17 0-3.866-1.564-4.07-3.807z");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wmk8g3b6p {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.206 9.91l.002-.001l.002-.002l.006-.005l.015-.012a2 2 0 0 1 .196-.136c.126-.08.306-.178.532-.267a3.6 3.6 0 0 1 1.892-.201a.676.676 0 1 1-.21 1.336a2.24 2.24 0 0 0-1.184.123a2 2 0 0 0-.381.202l-.01.007a.676.676 0 0 1-.86-1.044");
}

.wn24yqb3m {
  fill: var(--svg-color--1d79c4, #1D79C4);
  d: path("M25.99 29.984v-.39c0-5.39-4.47-9.77-9.99-9.77c-5.52.01-9.99 4.38-9.99 9.77v.39z");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xwix69baw {
  stop-color: var(--svg-color--a5777f, #A5777F);
}

.y0h0v45io {
  stop-color: var(--svg-color--115284, #115284);
  stop-opacity: 0;
}

.y0sidibnc {
  stop-color: var(--svg-color--b9887b, #B9887B);
}

.y68js-b7g {
  fill-rule: evenodd;
  d: path("M15.065 12.553c.15.11.184.32.074.47a2.02 2.02 0 0 1-1.641.827a2.05 2.05 0 0 1-1.639-.824a.336.336 0 0 1 .538-.403a1.373 1.373 0 0 0 2.199.005a.336.336 0 0 1 .47-.075");
}

.ydq0kpc8x {
  stop-color: var(--svg-color--ffdac0, #FFDAC0);
}

.ye_pt1bdn {
  stop-color: var(--svg-color--242323, #242323);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ynngk8bxm {
  stop-color: var(--svg-color--c5887d, #C5887D);
}

.yo8dvabcv {
  stop-color: var(--svg-color--1d6fc7, #1D6FC7);
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.yzuqint-c {
  stop-color: var(--svg-color--1d6fc7, #1D6FC7);
  stop-opacity: 0;
}

.z0449obxk {
  d: path("M17.44 8.52a.946.946 0 0 1 1.108.75l.356 1.848l-.086-1.382a.946.946 0 1 1 1.888-.118l.197 3.17l.327-.674a.989.989 0 1 1 1.78.863l-.817 1.683c-.174.42-.182.808-.19 1.219c-.009.374-.017.767-.152 1.221c-.236.795-.707 1.433-.913 1.653l-2.634.752c-2.028-.497-2.646-1.653-2.982-2.62a13 13 0 0 0-.658-1.585l-1.162-2.238a.946.946 0 1 1 1.678-.872l.194.372l-.463-1.349a.946.946 0 0 1 1.79-.613l.404 1.18l-.415-2.152a.946.946 0 0 1 .75-1.108");
}

.z12oxsbsi {
  stop-color: var(--svg-color--1b7db4, #1B7DB4);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z9whymb-f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.478 10.383c.415-.366 1.32-.752 2.443-.574");
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
