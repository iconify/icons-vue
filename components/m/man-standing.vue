<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ue0agu5fo"/><path class="icc-r_0id"/><path class="ljik48r2g"/><path fill="url(#iyEIrjb)" class="odqcnzb0c"/><path fill="url(#iq4IYHd)" class="odqcnzb0c"/><path fill="url(#iWrIvmx)" class="odqcnzb0c"/><path class="nn3ohcb_q"/><path fill="url(#iH6Wxdd)" class="emyk1_bxk"/><path fill="url(#iW9UZKd)" class="emyk1_bxk"/><path fill="url(#i2jl2dd)" class="emyk1_bxk"/><path class="kslw22v2b"/><path fill="url(#inleMte)" class="ngzhb0v7m"/><path fill="url(#ibHBQce)" class="ngzhb0v7m"/><path fill="url(#iK9e36d)" class="ngzhb0v7m"/><path fill="url(#iB2o2YY)" class="ngzhb0v7m"/><path class="wlgb1ybte"/><path fill="url(#iqvB94b)" class="usf570xbl"/><path fill="url(#iPksmkd)" class="usf570xbl"/><g filter="url(#iF5dU3c)"><path class="ysc9p8b8r"/></g><path fill="url(#ia0yYOe)" class="watupz9-y"/><path fill="url(#i8lfBJV)" class="watupz9-y"/><path fill="url(#i32R5Mb)" class="watupz9-y"/><path fill="url(#idwS4MP)" class="watupz9-y"/><path fill="url(#iXz3vrb)" class="watupz9-y"/><g filter="url(#iLp9VYc)"><path fill="url(#id16WMQ)" class="wlb86evkf"/><path fill="url(#ij99UJc)" class="wlb86evkf"/></g><path fill="url(#iQroCMb)" class="wlb86evkf"/><path fill="url(#iwz7qPd)" class="wlb86evkf"/><path fill="url(#i7SYsTT)" class="wlb86evkf"/><path fill="url(#iZ4lAIc)" class="fh-keibgh"/><g filter="url(#iLuuLud)"><path class="vj5a1pvgv"/></g><path fill="url(#imRULNe)" class="hcfkhfbam"/><path fill="url(#im5cNsq)" class="hcfkhfbam"/><g filter="url(#iEA5T6b)"><path class="i56lkcbai"/></g><circle fill="url(#iKY7wCk)" class="dns40t2iq"/><g filter="url(#iQaM4Kd)"><circle fill="url(#iEJFpMb)" class="fmsfl3b1e"/></g><g filter="url(#iCpF64Y)"><circle fill="url(#iPDYDtb)" class="o_f5ygx5j"/><circle fill="url(#iQk3eRb)" class="o_f5ygx5j"/></g><g filter="url(#iakB88O)"><circle class="dihkr88ks"/><circle fill="url(#iqFFd8c)" class="hdadrn3gp"/><circle fill="url(#iQbfije)" class="hdadrn3gp"/></g><path fill="url(#isRwzcg)" class="tagqwwb3h"/><path fill="url(#iuLSLBb)" class="tagqwwb3h"/><path fill="url(#isQvVne)" class="tagqwwb3h"/><path fill="url(#iTOArFc)" class="tagqwwb3h"/><path fill="url(#iwT3xxd)" class="tagqwwb3h"/><g filter="url(#iLYhmyQ)"><path class="itnjzqb2f"/><path fill="url(#iRVEcpc)" class="t3yr9bcfj"/><path fill="url(#ilrTqQO)" class="t3yr9bcfj"/><path fill="url(#i0RgJDd)" class="t3yr9bcfj"/><path fill="url(#iGlJuFe)" class="t3yr9bcfj"/><path fill="url(#i420ohe)" class="t3yr9bcfj"/><path fill="url(#injXUld)" class="t3yr9bcfj"/></g><path fill="url(#iEoLtud)" class="t3yr9bcfj"/><path fill="url(#iMToSed)" class="t3yr9bcfj"/><path fill="url(#iwumWBb)" class="t3yr9bcfj"/><g filter="url(#i9S4P0d)"><path class="dxeea6y2q"/></g><g filter="url(#i6kNG2Z)"><path class="effbwdddq"/><path fill="url(#iQAypqc)" class="zz--umh6c"/><path fill="url(#igscGYf)" class="zz--umh6c"/><path fill="url(#i4fACLe)" class="zz--umh6c"/></g><g filter="url(#iMAo5Hb)"><path stroke="url(#iSZXiAb)" class="uj-6rp65l"/></g><path class="fytgjzb6p"/><path class="vg_8ylb1l"/><path fill="url(#inRgwSv)" class="ngx3mhurl"/><path class="xptiw3b8x"/><g filter="url(#iz3LMQe)"><path class="rje4efc_o"/><path fill="url(#iiSnnTd)" class="wb0tzzbaz"/></g><g filter="url(#i5ytxid)"><path fill="url(#i0GThEZ)" class="j9fk5lb4i"/></g><path class="jljg3yblm"/><path fill="url(#iL4Zszd)" class="eenp9_yme"/><path class="j_25cdcei"/><g filter="url(#izBZCoe)"><path fill="url(#i64dkbe)" class="rfb9bmbce"/></g><g filter="url(#iqQeX3c)"><ellipse transform="rotate(-27.914 14.84 5.49)" class="vhyja5bxs"/><ellipse fill="url(#iTJXLDy)" transform="rotate(-27.914 14.84 5.49)" class="y87fjnb3x"/></g><g filter="url(#iroJ9Fb)"><path fill="url(#iDPFZBc)" clip-rule="evenodd" class="zh74_rzkv"/></g><g filter="url(#i3qIL8c)"><path class="pqs46qb_p"/></g><g filter="url(#iHM1VWd)"><path fill="url(#ip9JqEc)" clip-rule="evenodd" class="rjwn9sp_s"/></g><g filter="url(#iTDz2Rb)"><path class="sd876-pul"/></g><defs><radialGradient id="iyEIrjb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.482 16.556)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="s4ybxqbsv"/><stop offset="1" class="cmc78g0rw"/></radialGradient><radialGradient id="iq4IYHd" cx="0" cy="0" r="1" gradientTransform="matrix(.125 3.21875 -.73141 .0284 13.404 16.823)" gradientUnits="userSpaceOnUse"><stop offset=".022" class="se31mfapw"/><stop offset="1" class="j7o0jsb0d"/></radialGradient><radialGradient id="iWrIvmx" cx="0" cy="0" r="1" gradientTransform="rotate(-104.351 14.46 5.11)scale(2.04829 1.02534)" gradientUnits="userSpaceOnUse"><stop class="ef54lsb2t"/><stop offset="1" class="ekf73n8ha"/></radialGradient><radialGradient id="iH6Wxdd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.809 16.556)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="qmcri2bad"/><stop offset="1" class="ff44j1kme"/></radialGradient><radialGradient id="iW9UZKd" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 0 0 4.57812 18.606 17.073)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="vkmdc3sjj"/><stop offset="1" class="cw7ntv66c"/></radialGradient><radialGradient id="i2jl2dd" cx="0" cy="0" r="1" gradientTransform="rotate(-71.25 23.742 -2.998)scale(1.79857 .49047)" gradientUnits="userSpaceOnUse"><stop class="yn315pfzg"/><stop offset="1" class="le_psun2r"/></radialGradient><radialGradient id="inleMte" cx="0" cy="0" r="1" gradientTransform="rotate(-168.523 7.497 5.762)scale(2.27735 4.86372)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="rsfoz3blw"/><stop offset="1" class="nwf629gla"/></radialGradient><radialGradient id="ibHBQce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.498 8.757)" gradientUnits="userSpaceOnUse"><stop class="pm40e6_le"/><stop offset="1" class="asa-ks78a"/></radialGradient><radialGradient id="iB2o2YY" cx="0" cy="0" r="1" gradientTransform="matrix(-.35938 2.17188 -.8973 -.14848 13.183 11.636)" gradientUnits="userSpaceOnUse"><stop class="d5ei9kbfm"/><stop offset="1" class="a7wdambul"/></radialGradient><radialGradient id="iqvB94b" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.3125 1.2963 3.62963 18.73 11.901)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="to0orccvb"/><stop offset="1" class="tb5vgbckn"/></radialGradient><radialGradient id="i32R5Mb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 15.936 18.026)" gradientUnits="userSpaceOnUse"><stop class="rwlxembxd"/><stop offset="1" class="oig4whb0o"/></radialGradient><radialGradient id="idwS4MP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.012 28.39)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iXz3vrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.73 28.48)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="ij99UJc" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.408 8.178)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="u_3hhfbdm"/><stop offset="1" class="wz3lzhbxc"/></radialGradient><radialGradient id="i7SYsTT" cx="0" cy="0" r="1" gradientTransform="matrix(.23437 1.1172 -3.2104 .6735 15.213 8.394)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="p56j8ub-b"/><stop offset="1" class="lw7z9gbtl"/></radialGradient><radialGradient id="iZ4lAIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.11133 -1.40894 0 15.936 8.411)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="z6i8ir-zt"/><stop offset="1" class="s-0zn45fr"/></radialGradient><radialGradient id="im5cNsq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.502 29.339)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><radialGradient id="iKY7wCk" cx="0" cy="0" r="1" gradientTransform="matrix(.78004 0 0 1.36507 13.08 5.836)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iQk3eRb" cx="0" cy="0" r="1" gradientTransform="matrix(.36747 -.26758 .3054 .41942 18.216 5.718)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iqFFd8c" cx="0" cy="0" r="1" gradientTransform="matrix(.36505 -.67143 .393 .21367 18.032 6.201)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iQbfije" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 1.93 24.865)scale(.16217 .20906)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="isQvVne" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.81632 -4.35754 0 16.15 5.129)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="iTOArFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.581 .71507 0 16.975 5.271)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iwT3xxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.61824 .76884 0 14.949 5.256)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iRVEcpc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52757 1.96884 -3.3482 -2.59778 17.574 2.408)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="i0RgJDd" cx="0" cy="0" r="1" gradientTransform="matrix(-.082 -.88567 .43497 -.04027 14.094 4.219)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iGlJuFe" cx="0" cy="0" r="1" gradientTransform="matrix(.38189 -.8741 .7129 .31146 17.811 5.064)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="i420ohe" cx="0" cy="0" r="1" gradientTransform="matrix(.4413 .54757 -.48346 .38963 15.588 2.013)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="injXUld" cx="0" cy="0" r="1" gradientTransform="matrix(.64497 -1.34935 .46622 .22285 17.794 3.96)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iEoLtud" cx="0" cy="0" r="1" gradientTransform="matrix(.11609 .45113 -.74167 .19086 16.241 2.013)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iMToSed" cx="0" cy="0" r="1" gradientTransform="matrix(.49204 .71073 -1.479 1.02392 13.985 2.573)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="iwumWBb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.20373 1.4433 -1.806 -4.00878 16.445 3.896)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iSZXiAb" cx="0" cy="0" r="1" gradientTransform="matrix(.01093 -.27882 .83647 .0328 15.895 7.62)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="inRgwSv" cx="0" cy="0" r="1" gradientTransform="matrix(0 .40145 -.47502 0 16.9 5.681)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iiSnnTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10306 -.13281 .18285 -.1419 16.8 5.57)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iL4Zszd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .40147 -.47505 0 14.962 5.681)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iTJXLDy" cx="0" cy="0" r="1" gradientTransform="matrix(-.00344 -.21957 .26393 -.00413 14.834 5.63)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDPFZBc" cx="0" cy="0" r="1" gradientTransform="matrix(.08747 -.36083 .7916 .1919 17.022 4.86)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="ip9JqEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.08747 -.36083 .7916 -.1919 14.843 4.859)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><filter id="iF5dU3c" width="6.169" height="12.453" x="12.952" y="15.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.360784 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_169"/></filter><filter id="iLp9VYc" width="6.517" height="7.994" x="12.878" y="8.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.560784 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_169"/></filter><filter id="iLuuLud" width="3.316" height="1.848" x="12.37" y="28.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_169"/></filter><filter id="iEA5T6b" width="6.594" height="13.766" x="12.777" y="15.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".5"/></filter><filter id="iQaM4Kd" width="1.285" height="1.285" x="13.18" y="5.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".1"/></filter><filter id="iCpF64Y" width="1.734" height="1.734" x="17.308" y="4.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_169"/></filter><filter id="iakB88O" width="1.285" height="1.285" x="17.408" y="5.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".1"/></filter><filter id="iLYhmyQ" width="5.601" height="3.675" x="13.132" y="1.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_169"/></filter><filter id="i9S4P0d" width="2.282" height="2.692" x="14.685" y="4.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".375"/></filter><filter id="i6kNG2Z" width="1.034" height="1.392" x="15.415" y="5.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".05"/></filter><filter id="iMAo5Hb" width="1.83" height=".877" x="15.017" y="6.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".05"/></filter><filter id="iz3LMQe" width=".461" height=".42" x="16.519" y="5.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".05"/></filter><filter id="i5ytxid" width=".618" height=".628" x="16.837" y="5.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".1"/></filter><filter id="izBZCoe" width=".661" height=".685" x="14.862" y="5.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".1"/></filter><filter id="iqQeX3c" width=".517" height=".424" x="14.582" y="5.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".05"/></filter><filter id="iroJ9Fb" width="1.157" height=".871" x="16.494" y="4.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_169"/></filter><filter id="i3qIL8c" width="1.037" height=".501" x="16.554" y="4.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".05"/></filter><filter id="iHM1VWd" width="1.157" height=".871" x="14.214" y="4.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_169"/></filter><filter id="iTDz2Rb" width="1.037" height=".501" x="14.274" y="4.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_169" stdDeviation=".05"/></filter><linearGradient id="iK9e36d" x1="12.402" x2="12.402" y1="12.706" y2="12.554" gradientUnits="userSpaceOnUse"><stop class="sc4il2d7k"/><stop offset="1" class="m85-u4b_v"/></linearGradient><linearGradient id="iPksmkd" x1="19.683" x2="19.683" y1="12.792" y2="12.089" gradientUnits="userSpaceOnUse"><stop class="bowp4_b2y"/><stop offset="1" class="kl0728zpw"/></linearGradient><linearGradient id="ia0yYOe" x1="13.277" x2="13.504" y1="24.151" y2="24.143" gradientUnits="userSpaceOnUse"><stop class="yaaat27jw"/><stop offset="1" class="jursh_bcv"/></linearGradient><linearGradient id="i8lfBJV" x1="15.936" x2="15.936" y1="15.936" y2="16.37" gradientUnits="userSpaceOnUse"><stop class="j3c7jv70r"/><stop offset="1" class="y3uayvb5s"/></linearGradient><linearGradient id="id16WMQ" x1="15.936" x2="15.936" y1="9.026" y2="15.987" gradientUnits="userSpaceOnUse"><stop class="dp48kcpaa"/><stop offset="1" class="mwrvsh4-t"/></linearGradient><linearGradient id="iQroCMb" x1="17.542" x2="17.542" y1="15.987" y2="13.87" gradientUnits="userSpaceOnUse"><stop class="voaf13bac"/><stop offset="1" class="tpb8kfbdc"/></linearGradient><linearGradient id="iwz7qPd" x1="17.167" x2="17.167" y1="15.94" y2="15.651" gradientUnits="userSpaceOnUse"><stop class="nb4vlrbxr"/><stop offset="1" class="f7w9xyx3p"/></linearGradient><linearGradient id="imRULNe" x1="18.183" x2="16.436" y1="29.651" y2="29.448" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient><linearGradient id="iEJFpMb" x1="13.822" x2="13.537" y1="5.96" y2="5.96" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iPDYDtb" x1="18.534" x2="18.17" y1="5.351" y2="6.478" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="isRwzcg" x1="17.726" x2="14.332" y1="6.009" y2="6.515" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iuLSLBb" x1="13.534" x2="14.562" y1="7.208" y2="7.074" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="ilrTqQO" x1="13.772" x2="15.062" y1="5.717" y2="3.426" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iQAypqc" x1="15.548" x2="15.965" y1="6.302" y2="6.302" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="igscGYf" x1="16.349" x2="15.894" y1="6.446" y2="6.439" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="i4fACLe" x1="16.019" x2="16.019" y1="6.776" y2="6.521" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="i0GThEZ" x1="17.247" x2="17.107" y1="5.557" y2="5.643" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i64dkbe" x1="15.292" x2="15.153" y1="5.557" y2="5.643" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-standing" /></template>
<style>
.a7wdambul {
  stop-color: var(--svg-color--257ad3, #257AD3);
  stop-opacity: 0;
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.asa-ks78a {
  stop-color: var(--svg-color--3a87b0, #3A87B0);
  stop-opacity: 0;
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.bowp4_b2y {
  stop-color: var(--svg-color--4e73c8, #4E73C8);
}

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmc78g0rw {
  stop-color: var(--svg-color--b87405, #B87405);
  stop-opacity: 0;
}

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.cw7ntv66c {
  stop-color: var(--svg-color--d0910c, #D0910C);
  stop-opacity: 0;
}

.d5ei9kbfm {
  stop-color: var(--svg-color--257ad3, #257AD3);
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dihkr88ks {
  cx: 18.05px;
  cy: 5.836px;
  r: 0.442px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.dns40t2iq {
  cx: 13.822px;
  cy: 5.836px;
  r: 0.742px;
}

.dp48kcpaa {
  stop-color: var(--svg-color--46a3f0, #46A3F0);
}

.dxeea6y2q {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.81 5.782l-.365.755c-.045.156.064.311.217.311h.328c.154 0 .262-.158.217-.31l-.222-.756c-.047-.168-.125-.168-.175 0");
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.eenp9_yme {
  d: path("M14.96 5.32a.397.397 0 0 0-.382.502h.767a.4.4 0 0 0-.384-.501");
}

.ef54lsb2t {
  stop-color: var(--svg-color--c2821c, #C2821C);
}

.effbwdddq {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.763 5.71l-.237.755a.24.24 0 0 0 .232.31h.35a.24.24 0 0 0 .23-.31l-.236-.756c-.05-.167-.287-.167-.34 0");
}

.ekf73n8ha {
  stop-color: var(--svg-color--eda82d, #EDA82D);
  stop-opacity: 0;
}

.emyk1_bxk {
  d: path("M19.825 20.366c.938-1.982.768-6.26.487-7.824H18.64c.072 2.425-.155 5.254-.294 6.522a.29.29 0 0 0 .555.15l.117-.262a.184.184 0 0 1 .225-.1a.176.176 0 0 1 .12.201c-.061.3-.172.678-.264.973a.42.42 0 0 0 .238.513c.186.076.402.008.488-.174");
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f7w9xyx3p {
  stop-color: var(--svg-color--4475d1, #4475D1);
  stop-opacity: 0;
}

.ff44j1kme {
  stop-color: var(--svg-color--dca61c, #DCA61C);
  stop-opacity: 0;
}

.fh-keibgh {
  d: path("M15.065 7.3h1.742v1.35a.871.871 0 0 1-1.742 0z");
}

.fmsfl3b1e {
  cx: 13.822px;
  cy: 5.836px;
  r: 0.442px;
}

.ft5dv1b6b {
  fill: none;
}

.fytgjzb6p {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.933 7.227c-.226 0-.438-.053-.616-.146c-.061-.03-.127.038-.088.093a.84.84 0 0 0 .704.376a.84.84 0 0 0 .703-.376c.038-.057-.027-.124-.088-.093a1.3 1.3 0 0 1-.615.146");
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.hcfkhfbam {
  d: path("M19.503 29.745v.242h-3.067V28.39h1.992c.102.367.575.753.817.914c.186.123.258.3.258.441");
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hdadrn3gp {
  cx: 18.05px;
  cy: 5.836px;
  r: 0.442px;
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i56lkcbai {
  fill: var(--svg-color--ac99aa, #AC99AA);
  d: path("m13.778 16.308l.468 11.765h.813v-10.61h2.203v10.61h.672l.437-11.765z");
}

.icc-r_0id {
  fill: var(--svg-color--c78e18, #C78E18);
  d: path("M19.269 19.085a.22.22 0 0 0 .043-.238h.437l-.32.996c-.262.078-.54.05-.59-.114a.32.32 0 0 1 .074-.3c.084-.077.271-.253.356-.344");
}

.itnjzqb2f {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m18.074 2.957l.191.095a.874.874 0 0 1 .453.948l-.262 1.351c-.023.14-.116.234-.254.237c.015-.224.03-.585.036-.642c.02-.192-.01-.25-.187-.425a.56.56 0 0 1-.167-.379v-.38a.26.26 0 0 0-.191-.236a7.3 7.3 0 0 0-1.74-.19c-.859 0-1.455.119-1.741.19a.23.23 0 0 0-.19.237v.38a.47.47 0 0 1-.168.378l-.071.071c-.096.072-.144.22-.144.339c.007.069.016.467.027.633a.28.28 0 0 1-.265-.237l-.262-1.35a.91.91 0 0 1 .477-.925c.45-.198.615-.498.977-.807a.87.87 0 0 1 .978-.142c.238.071.5.071.74 0a1.07 1.07 0 0 1 1.048.237l.358.356c.095.118.214.19.357.26");
}

.j_25cdcei {
  fill: var(--svg-color--000, #000);
  d: path("M15.188 5.718a.226.226 0 0 0-.227-.228a.226.226 0 0 0-.202.332h.402a.2.2 0 0 0 .027-.104");
}

.j3c7jv70r {
  stop-color: var(--svg-color--966d92, #966D92);
}

.j7o0jsb0d {
  stop-color: var(--svg-color--d58816, #D58816);
  stop-opacity: 0;
}

.j9fk5lb4i {
  d: path("M17.255 5.665a.37.37 0 0 0-.103-.205l-.115.126l.052.102z");
}

.jljg3yblm {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.869 5.2a.62.62 0 0 0-.602.47c-.02.078.04.152.119.152h.991a.102.102 0 0 0 .101-.12a.62.62 0 0 0-.61-.502");
}

.jursh_bcv {
  stop-color: var(--svg-color--a5949b, #A5949B);
  stop-opacity: 0;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.kl0728zpw {
  stop-color: var(--svg-color--3686df, #3686DF);
  stop-opacity: 0;
}

.kslw22v2b {
  fill: var(--svg-color--3b97db, #3B97DB);
  d: path("M11.469 12.586c.486-2.254 1.628-3.334 3.03-3.83v3.95h-2.933a.1.1 0 0 1-.097-.12");
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.le_psun2r {
  stop-color: var(--svg-color--cc952b, #CC952B);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljik48r2g {
  fill: var(--svg-color--eaae34, #EAAE34);
  d: path("M12.237 20.366c-.937-1.982-.768-6.26-.487-7.824h1.672c-.072 2.425.04 5.243.178 6.511c.011.103.083.214 0 .276a.29.29 0 0 1-.439-.115l-.117-.262a.184.184 0 0 0-.225-.1a.176.176 0 0 0-.12.201c.061.3.172.678.264.973a.42.42 0 0 1-.238.513c-.186.076-.402.008-.488-.174");
}

.lw7z9gbtl {
  stop-color: var(--svg-color--499de8, #499DE8);
  stop-opacity: 0;
}

.m85-u4b_v {
  stop-color: var(--svg-color--2c7cd5, #2C7CD5);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.mwrvsh4-t {
  stop-color: var(--svg-color--3b70d0, #3B70D0);
}

.nb4vlrbxr {
  stop-color: var(--svg-color--4656b3, #4656B3);
}

.ngx3mhurl {
  d: path("M16.902 5.321a.397.397 0 0 1 .382.501h-.766a.398.398 0 0 1 .384-.501");
}

.ngzhb0v7m {
  d: path("M11.469 12.586c.486-2.254 1.628-3.334 3.03-3.83v3.95h-2.933a.1.1 0 0 1-.097-.12");
}

.nn3ohcb_q {
  fill: var(--svg-color--ffcc2d, #FFCC2D);
  d: path("M19.825 20.366c.938-1.982.768-6.26.487-7.824H18.64c.072 2.425-.155 5.254-.294 6.522a.29.29 0 0 0 .555.15l.117-.262a.184.184 0 0 1 .225-.1a.176.176 0 0 1 .12.201c-.061.3-.172.678-.264.973a.42.42 0 0 0 .238.513c.186.076.402.008.488-.174");
}

.nwf629gla {
  stop-color: var(--svg-color--5ba1d3, #5BA1D3);
}

.o_f5ygx5j {
  cx: 18.05px;
  cy: 5.836px;
  r: 0.742px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odqcnzb0c {
  d: path("M12.237 20.366c-.937-1.982-.768-6.26-.487-7.824h1.672c-.072 2.425.04 5.243.178 6.511c.011.103.083.214 0 .276a.29.29 0 0 1-.439-.115l-.117-.262a.184.184 0 0 0-.225-.1a.176.176 0 0 0-.12.201c.061.3.172.678.264.973a.42.42 0 0 1-.238.513c-.186.076-.402.008-.488-.174");
}

.oig4whb0o {
  stop-color: var(--svg-color--867081, #867081);
  stop-opacity: 0;
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p56j8ub-b {
  stop-color: var(--svg-color--39779b, #39779B);
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm40e6_le {
  stop-color: var(--svg-color--3a87b0, #3A87B0);
}

.pqs46qb_p {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.44 4.793c-.092-.086-.356-.231-.736-.195");
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qmcri2bad {
  stop-color: var(--svg-color--b58009, #B58009);
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rfb9bmbce {
  d: path("M15.323 5.671c0-.128-.104-.214-.133-.24l-.128.124l.08.161z");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rje4efc_o {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.873 5.405c.028.038-.031.084-.098.134s-.117.085-.146.048s.004-.11.07-.16c.068-.05.145-.06.174-.022");
}

.rjwn9sp_s {
  fill-rule: evenodd;
  d: path("M15.141 4.856c-.32-.03-.525.095-.575.14a.21.21 0 1 1-.284-.308c.136-.126.458-.291.898-.25a.21.21 0 1 1-.039.418");
}

.rsfoz3blw {
  stop-color: var(--svg-color--5ba1d3, #5BA1D3);
  stop-opacity: 0;
}

.rwlxembxd {
  stop-color: var(--svg-color--8560a3, #8560A3);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s-0zn45fr {
  stop-color: var(--svg-color--f7b724, #F7B724);
}

.s4ybxqbsv {
  stop-color: var(--svg-color--b87405, #B87405);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sc4il2d7k {
  stop-color: var(--svg-color--3270c8, #3270C8);
}

.sd876-pul {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.424 4.793c.093-.086.357-.231.737-.195");
}

.se31mfapw {
  stop-color: var(--svg-color--ad6605, #AD6605);
}

.t3yr9bcfj {
  d: path("m18.074 2.957l.191.095a.874.874 0 0 1 .453.948l-.262 1.351c-.023.14-.116.234-.254.237c.015-.224.03-.585.036-.642c.02-.192-.01-.25-.187-.425a.56.56 0 0 1-.167-.379v-.38a.26.26 0 0 0-.191-.236a7.3 7.3 0 0 0-1.74-.19c-.859 0-1.455.119-1.741.19a.23.23 0 0 0-.19.237v.38a.47.47 0 0 1-.168.378l-.071.071c-.096.072-.144.22-.144.339c.007.069.016.467.027.633a.28.28 0 0 1-.265-.237l-.262-1.35a.91.91 0 0 1 .477-.925c.45-.198.615-.498.977-.807a.87.87 0 0 1 .978-.142c.238.071.5.071.74 0a1.07 1.07 0 0 1 1.048.237l.358.356c.095.118.214.19.357.26");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tagqwwb3h {
  d: path("M13.665 5.564a13 13 0 0 1-.025-.64c0-.118.047-.26.143-.331l.071-.072a.47.47 0 0 0 .167-.379v-.38a.23.23 0 0 1 .19-.236c.287-.071.883-.19 1.741-.19s1.455.119 1.74.19a.255.255 0 0 1 .192.237v.38c0 .141.071.284.166.378c.224.157.21.243.191.427c-.006.057-.024.531-.04.64l-.118 1.76c-.071.786-.69 1.334-1.427 1.334H15.23c-.76 0-1.355-.548-1.427-1.334z");
}

.tb5vgbckn {
  stop-color: var(--svg-color--2680e1, #2680E1);
  stop-opacity: 0;
}

.to0orccvb {
  stop-color: var(--svg-color--2680e1, #2680E1);
}

.tpb8kfbdc {
  stop-color: var(--svg-color--3b70cf, #3B70CF);
  stop-opacity: 0;
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.u_3hhfbdm {
  stop-color: var(--svg-color--4db7f8, #4DB7F8);
}

.ue0agu5fo {
  fill: var(--svg-color--bf8011, #BF8011);
  d: path("M12.604 19.085a.22.22 0 0 1-.043-.238h-.438l.32.996c.262.078.54.05.59-.114a.32.32 0 0 0-.074-.3a9 9 0 0 1-.355-.344");
}

.uj-6rp65l {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.933 7.227c-.226 0-.438-.053-.616-.146c-.061-.03-.127.038-.088.093a.84.84 0 0 0 .704.376a.84.84 0 0 0 .703-.376c.038-.057-.027-.124-.088-.093a1.3 1.3 0 0 1-.615.146Z");
}

.usf570xbl {
  d: path("M20.404 12.586c-.486-2.254-1.629-3.334-3.03-3.83v3.95h2.933a.1.1 0 0 0 .097-.12");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vg_8ylb1l {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.994 5.2c.29 0 .535.2.602.47a.122.122 0 0 1-.12.152h-.99a.102.102 0 0 1-.102-.12a.62.62 0 0 1 .61-.502");
}

.vhyja5bxs {
  cx: 14.841px;
  cy: 5.49px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.173px;
  ry: 0.088px;
}

.vj5a1pvgv {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.37 29.745v.242h3.066V28.39h-1.992c-.102.367-.574.753-.816.914a.54.54 0 0 0-.258.441");
}

.vkmdc3sjj {
  stop-color: var(--svg-color--bc7a0b, #BC7A0B);
}

.voaf13bac {
  stop-color: var(--svg-color--3b70cf, #3B70CF);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.watupz9-y {
  d: path("m12.952 15.936l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.wb0tzzbaz {
  d: path("M16.873 5.405c.028.038-.031.084-.098.134s-.117.085-.146.048s.004-.11.07-.16c.068-.05.145-.06.174-.022");
}

.wlb86evkf {
  d: path("M12.878 11.452a3.059 3.059 0 1 1 6.117 0v4.441a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.093-.094z");
}

.wlgb1ybte {
  fill: var(--svg-color--4fa0f0, #4FA0F0);
  d: path("M20.404 12.586c-.486-2.254-1.629-3.334-3.03-3.83v3.95h2.933a.1.1 0 0 0 .097-.12");
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.wz3lzhbxc {
  stop-color: var(--svg-color--49a1f7, #49A1F7);
  stop-opacity: 0;
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xptiw3b8x {
  fill: var(--svg-color--000, #000);
  d: path("M16.674 5.718c0-.127.101-.228.228-.228a.226.226 0 0 1 .201.332h-.402a.2.2 0 0 1-.027-.104");
}

.y3uayvb5s {
  stop-color: var(--svg-color--966d92, #966D92);
  stop-opacity: 0;
}

.y87fjnb3x {
  cx: 14.841px;
  cy: 5.49px;
  rx: 0.173px;
  ry: 0.088px;
}

.yaaat27jw {
  stop-color: var(--svg-color--a5949b, #A5949B);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yn315pfzg {
  stop-color: var(--svg-color--cc952b, #CC952B);
}

.ysc9p8b8r {
  fill: var(--svg-color--a2859a, #A2859A);
  d: path("m12.952 15.936l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.z6i8ir-zt {
  stop-color: var(--svg-color--d89424, #D89424);
}

.zh74_rzkv {
  fill-rule: evenodd;
  d: path("M16.723 4.856c.32-.03.526.095.575.14a.21.21 0 0 0 .285-.308c-.136-.126-.459-.291-.899-.25a.21.21 0 0 0 .04.418");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zz--umh6c {
  d: path("m15.763 5.71l-.237.755a.24.24 0 0 0 .232.31h.35a.24.24 0 0 0 .23-.31l-.236-.756c-.05-.167-.287-.167-.34 0");
}

</style>
