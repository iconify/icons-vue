<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iL2DNYc)"><path class="y2re8hl9w"/></g><path fill="url(#iG0ULnb)" class="g-tfz_but"/><g filter="url(#ifYkZ8d)"><path fill="url(#iIGJP1L)" class="zyosecbvv"/></g><g filter="url(#i5MfrUY)"><path stroke="url(#iAtGVxc)" class="jsw61abqz"/></g><g filter="url(#iJouGlo)"><path stroke="url(#ihBNZOe)" class="lh1-bz9_s"/></g><g filter="url(#i3kxEib)"><path stroke="url(#ic5T6Vd)" class="p--a0qx0q"/></g><g filter="url(#ikAYE6c)"><path class="fkps2fbrt"/><path fill="url(#ifQRrXD)" class="ntl62r8nt"/><path fill="url(#iCNPpqb)" class="ntl62r8nt"/><path fill="url(#i90RSNd)" class="ntl62r8nt"/><path fill="url(#icDflSc)" class="ntl62r8nt"/></g><path fill="url(#iklUbIc)" class="q6gsdgb-z"/><path fill="url(#iIHMn7d)" class="q6gsdgb-z"/><path fill="url(#iK6AIvd)" class="q6gsdgb-z"/><path fill="url(#itQ4WOb)" class="q6gsdgb-z"/><g filter="url(#idZpqNM)"><rect class="lk2vrruzb"/><rect fill="url(#i7PesYb)" class="ew294b97m"/></g><g filter="url(#ihb0Z8P)"><path fill="url(#i1IwF5T)" class="grojetr5t"/><path fill="url(#iqt4QYd)" class="grojetr5t"/><path fill="url(#iH9kDkd)" class="grojetr5t"/></g><g filter="url(#imIAo0c)"><path fill="url(#iPHCsKe)" class="ow01cbczd"/><path fill="url(#iDniRrb)" class="ow01cbczd"/><path fill="url(#i80S5gc)" class="ow01cbczd"/><path fill="url(#i9IpNKe)" class="ow01cbczd"/></g><path fill="url(#ie3ZJpb)" class="xyzuznb3l"/><path fill="url(#iPtifZd)" class="z6e6mw_8y"/><path fill="url(#ieWXsZc)" class="z6e6mw_8y"/><g filter="url(#i4uwKvQ)"><path fill="url(#iRz5TTd)" class="ok4jdvb8r"/><path fill="url(#imrGLfb)" class="ok4jdvb8r"/></g><path fill="url(#iACUcWd)" class="dty9fjfoc"/><path fill="url(#iGzoKrb)" class="dty9fjfoc"/><path fill="url(#i6xoLGe)" class="dty9fjfoc"/><path fill="url(#iAexbhc)" class="dty9fjfoc"/><g filter="url(#iNIBl8b)"><path stroke="url(#idMleyc)" class="ehj5k_bqv"/></g><g filter="url(#inp5sse)"><path stroke="url(#iPZVedb)" class="t_l-40b1y"/></g><g filter="url(#irptZsd)"><path fill="url(#i3byVbd)" class="uktosabkt"/></g><g filter="url(#ifIeW1d)"><path stroke="url(#i1bgYrc)" class="pqitq_btv"/></g><g filter="url(#ih0AYIe)"><path stroke="url(#i0hmnFe)" class="k-il9ub1q"/></g><circle fill="url(#i1Rwmxe)" class="qct52e6cd"/><g filter="url(#iq9drfH)"><circle fill="url(#iCsAWdb)" class="h5yhgbd1b"/></g><g filter="url(#irQ6CIc)"><circle fill="url(#iAwlMQd)" class="cpmh20bsf"/><circle fill="url(#iwj7Hsi)" class="cpmh20bsf"/></g><g filter="url(#iE1JKEc)"><circle class="tm-f6fwhm"/><circle fill="url(#inh258b)" class="osxm7thcc"/><circle fill="url(#ioT4xxc)" class="osxm7thcc"/></g><path fill="url(#idMFILe)" class="swsncabgk"/><path fill="url(#iVet5Pc)" class="swsncabgk"/><path fill="url(#ir7b6Nd)" class="swsncabgk"/><path fill="url(#i0ggIce)" class="swsncabgk"/><path fill="url(#iYnRvte)" class="swsncabgk"/><g filter="url(#ib6mk9d)"><path class="r02p8ubqo"/><path fill="url(#in1CX1c)" class="yntatvzjv"/><path fill="url(#iFw76ev)" class="yntatvzjv"/><path fill="url(#i2n1FPe)" class="yntatvzjv"/><path fill="url(#imYQfjc)" class="yntatvzjv"/><path fill="url(#ij2q9Od)" class="yntatvzjv"/><path fill="url(#iVxIuLb)" class="yntatvzjv"/></g><path fill="url(#iMQ8N2c)" class="yntatvzjv"/><path fill="url(#i2Ixh9f)" class="yntatvzjv"/><path fill="url(#iSSHRgb)" class="yntatvzjv"/><g filter="url(#iWKenAc)"><path class="jt23f0b3k"/></g><path class="s2817ub-i"/><path fill="url(#iORC9gc)" class="mmqokxbcz"/><path fill="url(#iwCPiVc)" class="mmqokxbcz"/><g filter="url(#ihVaGpb)"><path stroke="url(#ihDtSiZ)" class="szy7o-f_b"/></g><path class="s4jilbbng"/><path class="h_88v9z9m"/><path fill="url(#ivbQ26c)" class="ytc7mhb5z"/><path class="d_y07ubvt"/><g filter="url(#i1BDbxd)"><path class="h_vbz1byx"/><path fill="url(#iwY0mJd)" class="n-3g919bq"/></g><g filter="url(#in5UjCL)"><path fill="url(#iCtb9pC)" class="va3lhtbnh"/></g><path class="c4d2fsb7x"/><path fill="url(#iJZR9Bb)" class="a8pcdzbbi"/><path class="rrhclt3xn"/><g filter="url(#iRLnZDo)"><path fill="url(#i9W4CCb)" class="j_v36nbwh"/></g><g filter="url(#iHJdV1a)"><ellipse transform="rotate(-27.914 13.435 6.553)" class="e1610wluy"/><ellipse fill="url(#ibfXpub)" transform="rotate(-27.914 13.435 6.553)" class="r7873db9t"/></g><g filter="url(#iubb7Rc)"><path fill="url(#i595vKe)" clip-rule="evenodd" class="ce3469l3k"/></g><g filter="url(#imxmf8J)"><path class="asxi2vb-v"/></g><g filter="url(#i1fEdfT)"><path fill="url(#iEtOOGe)" clip-rule="evenodd" class="ohaqjn6tw"/></g><g filter="url(#ifkCnSy)"><path class="zl8do3b6h"/></g><defs><radialGradient id="iG0ULnb" cx="0" cy="0" r="1" gradientTransform="matrix(12.502 -3.897 4.76721 15.29373 8.201 25.085)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="iIGJP1L" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 20.046 20.614)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="ifQRrXD" cx="0" cy="0" r="1" gradientTransform="matrix(3.28125 3 -1.21254 1.32622 18.288 11.52)" gradientUnits="userSpaceOnUse"><stop class="vj4m2tb3q"/><stop offset="1" class="hottnizrg"/></radialGradient><radialGradient id="iCNPpqb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57033 -4.1875 1.15118 -.7066 19.288 15.708)" gradientUnits="userSpaceOnUse"><stop class="tp4a5acim"/><stop offset="1" class="ke65wb71h"/></radialGradient><radialGradient id="i90RSNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15781 0 0 -1.66611 24.765 15.488)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="z3ywhob_s"/><stop offset="1" class="g-k6bqb8y"/></radialGradient><radialGradient id="icDflSc" cx="0" cy="0" r="1" gradientTransform="matrix(2.8125 .3125 -.14177 1.27592 21.288 13.458)" gradientUnits="userSpaceOnUse"><stop class="p--zv6bvm"/><stop offset="1" class="a1-19nbvs"/></radialGradient><radialGradient id="iklUbIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.5273 1.08984 0 24.823 29.934)" gradientUnits="userSpaceOnUse"><stop class="vj07kubhl"/><stop offset="1" class="keqz-8g7v"/></radialGradient><radialGradient id="iIHMn7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -17.8945 2.43359 0 24.823 28.302)" gradientUnits="userSpaceOnUse"><stop offset=".906" class="sy7qt-bzl"/><stop offset="1" class="i8gxpdlwn"/></radialGradient><radialGradient id="iK6AIvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.3125 -1.10912 0 24.823 15.802)" gradientUnits="userSpaceOnUse"><stop class="ti8dkw8jh"/><stop offset="1" class="uw8wenb6w"/></radialGradient><radialGradient id="i7PesYb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31815 0 0 -1.07813 26.163 9.848)" gradientUnits="userSpaceOnUse"><stop class="jk8wwdkvh"/><stop offset="1" class="kt1qsbbol"/></radialGradient><radialGradient id="i1IwF5T" cx="0" cy="0" r="1" gradientTransform="rotate(108.771 12.738 11.764)scale(5.04985 5.80366)" gradientUnits="userSpaceOnUse"><stop class="l1mhifosa"/><stop offset="1" class="nwr0ulaka"/></radialGradient><radialGradient id="iqt4QYd" cx="0" cy="0" r="1" gradientTransform="matrix(2 8.14203 -5.28875 1.29912 23.35 2.066)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="tfpize5dt"/><stop offset="1" class="udxjy24sj"/></radialGradient><radialGradient id="iH9kDkd" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 1 -.64044 -.57039 23.148 2.364)" gradientUnits="userSpaceOnUse"><stop offset=".048" class="ozaj1r-nb"/><stop offset="1" class="pkl3f-q-p"/></radialGradient><radialGradient id="iDniRrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.82813 0 0 -.23438 26.07 13.88)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="zmvijm-xp"/><stop offset="1" class="xlsa3ib-s"/></radialGradient><radialGradient id="i80S5gc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 0 0 -.10156 26.007 14.59)" gradientUnits="userSpaceOnUse"><stop class="p4gb2ru0v"/><stop offset="1" class="fm7uiddyf"/></radialGradient><radialGradient id="i9IpNKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.42688 0 0 -.21875 26.117 15.348)" gradientUnits="userSpaceOnUse"><stop class="y759xzbwp"/><stop offset="1" class="ht3r2np2u"/></radialGradient><radialGradient id="iPtifZd" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -.26562 .64937 1.60434 4.241 16.723)" gradientUnits="userSpaceOnUse"><stop class="os1l35bms"/><stop offset="1" class="k396ay83y"/></radialGradient><radialGradient id="iRz5TTd" cx="0" cy="0" r="1" gradientTransform="rotate(-24.677 39.34 -2.714)scale(7.63473 2.90408)" gradientUnits="userSpaceOnUse"><stop class="cz5i0kbhu"/><stop offset="1" class="o9z9v7bzx"/></radialGradient><radialGradient id="imrGLfb" cx="0" cy="0" r="1" gradientTransform="rotate(138.102 3.523 9.153)scale(4.49229 1.70257)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="e_lkicm0r"/><stop offset="1" class="bc4d3sv8x"/></radialGradient><radialGradient id="iACUcWd" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 8.28125 -6.68817 1.3124 17.32 12.052)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="x3htwqbtq"/><stop offset="1" class="stlhbac-j"/></radialGradient><radialGradient id="iGzoKrb" cx="0" cy="0" r="1" gradientTransform="rotate(-164.999 9.016 6.151)scale(4.94995 8.7933)" gradientUnits="userSpaceOnUse"><stop offset=".606" class="qag7llucc"/><stop offset="1" class="gwan6obls"/></radialGradient><radialGradient id="i6xoLGe" cx="0" cy="0" r="1" gradientTransform="rotate(-23.146 41.897 -24.59)scale(5.56514 10.9767)" gradientUnits="userSpaceOnUse"><stop offset=".765" class="gx_q8ibzf"/><stop offset=".973" class="h7p61gvke"/></radialGradient><radialGradient id="iAexbhc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49805 1.0781 -.58371 -1.3525 14.849 10.098)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zo19yuphz"/><stop offset="1" class="ux31pqfvx"/></radialGradient><radialGradient id="i3byVbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42187 .23438 -.46507 -.83711 25.304 2.794)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="nvk-74bwn"/><stop offset="1" class="f1ri06bus"/></radialGradient><radialGradient id="i1Rwmxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.00642 0 0 1.76124 11.164 6.999)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iwj7Hsi" cx="0" cy="0" r="1" gradientTransform="matrix(.47412 -.34523 .39404 .54114 17.79 6.847)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="inh258b" cx="0" cy="0" r="1" gradientTransform="matrix(.471 -.8663 .50705 .27568 17.553 7.47)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="ioT4xxc" cx="0" cy="0" r="1" gradientTransform="matrix(.1487 .14719 -.18975 .1917 17.576 6.998)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="ir7b6Nd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.92388 -5.62218 0 15.125 6.086)" gradientUnits="userSpaceOnUse"><stop offset=".659" class="l58-idrcp"/><stop offset=".958" class="c262ymbst"/></radialGradient><radialGradient id="i0ggIce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.74962 .9226 0 16.19 6.27)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iYnRvte" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.79767 .99197 0 13.575 6.25)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="in1CX1c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9709 2.54023 -4.3199 -3.3517 16.96 2.575)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="i2n1FPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.1058 -1.14271 .56121 -.05196 12.471 4.912)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="imYQfjc" cx="0" cy="0" r="1" gradientTransform="rotate(-66.4 13.22 -10.192)scale(1.23072 1.00375)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="ij2q9Od" cx="0" cy="0" r="1" gradientTransform="matrix(.56936 .70648 -.62377 .50271 14.398 2.066)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iVxIuLb" cx="0" cy="0" r="1" gradientTransform="rotate(-64.453 12.254 -11.39)scale(1.9296 .66671)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iMQ8N2c" cx="0" cy="0" r="1" gradientTransform="matrix(.14978 .58206 -.95691 .24625 15.242 2.065)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="i2Ixh9f" cx="0" cy="0" r="1" gradientTransform="rotate(55.305 3.504 13.16)scale(1.1153 2.32092)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="iSSHRgb" cx="0" cy="0" r="1" gradientTransform="rotate(155.748 7.27 3.913)scale(4.53361 5.67284)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iORC9gc" cx="0" cy="0" r="1" gradientTransform="rotate(170.864 7.387 4.415)scale(.69448 2.20778)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="izfe3kb7l"/><stop offset="1" class="jqineqbnv"/></radialGradient><radialGradient id="iwCPiVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.40139 1.35609 0 14.844 8.21)" gradientUnits="userSpaceOnUse"><stop class="e-v9_qbao"/><stop offset="1" class="gw-pmo7eh"/></radialGradient><radialGradient id="ihDtSiZ" cx="0" cy="0" r="1" gradientTransform="matrix(.0141 -.35974 1.07922 .04232 14.795 9.3)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="ivbQ26c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .51796 -.61288 0 16.093 6.799)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iwY0mJd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 9.61 -.581)scale(.21639 .2979)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJZR9Bb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .51799 -.61291 0 13.591 6.799)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ibfXpub" cx="0" cy="0" r="1" gradientTransform="matrix(-.00442 -.28262 .33972 -.00532 13.426 6.733)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i595vKe" cx="0" cy="0" r="1" gradientTransform="matrix(.11286 -.46555 1.02134 .2476 16.25 5.737)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iEtOOGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.11286 -.46555 1.02135 -.2476 13.438 5.737)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><filter id="iL2DNYc" width="16.97" height="13.626" x="4.983" y="16.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1289"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1289" result="effect2_innerShadow_4002_1289"/></filter><filter id="ifYkZ8d" width="8.803" height="12.453" x="12.427" y="15.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".5"/></filter><filter id="i5MfrUY" width="11.112" height="3.615" x="8.173" y="25.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".2"/></filter><filter id="iJouGlo" width="3.297" height="3.17" x="5.589" y="23.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".2"/></filter><filter id="i3kxEib" width="3.085" height="3.032" x="8.851" y="23.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".2"/></filter><filter id="ikAYE6c" width="8.453" height="5.978" x="16.718" y="9.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.65098 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1289"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.545098 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1289" result="effect2_innerShadow_4002_1289"/></filter><filter id="idZpqNM" width="2.963" height="1.158" x="23.363" y="9.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.541176 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1289"/></filter><filter id="ihb0Z8P" width="8.438" height="7.534" x="20.669" y="1.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.517647 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1289"/></filter><filter id="imIAo0c" width="1.765" height="3.013" x="24.69" y="12.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.607843 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1289"/></filter><filter id="i4uwKvQ" width="10.053" height="7.208" x="2.993" y="10.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.552941 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1289"/></filter><filter id="iNIBl8b" width="2.209" height="5.708" x="26.777" y="3.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".1"/></filter><filter id="inp5sse" width="1.759" height="1.3" x="26.569" y="2.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".1"/></filter><filter id="irptZsd" width="1.189" height="1.345" x="24.572" y="2.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".1"/></filter><filter id="ifIeW1d" width="2.586" height="5.952" x="24.656" y="3.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".1"/></filter><filter id="ih0AYIe" width="2.948" height="6.859" x="20.962" y="2.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".1"/></filter><filter id="iq9drfH" width="2.141" height="2.141" x="11.05" y="5.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".25"/></filter><filter id="irQ6CIc" width="2.165" height="2.165" x="16.619" y="5.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1289"/></filter><filter id="iE1JKEc" width="2.141" height="2.141" x="16.506" y="5.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".25"/></filter><filter id="ib6mk9d" width="7.227" height="4.713" x="11.229" y="1.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1289"/></filter><filter id="iWKenAc" width="1.746" height="2.338" x="13.802" y="6.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".2"/></filter><filter id="ihVaGpb" width="2.045" height=".815" x="13.821" y="8.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".025"/></filter><filter id="i1BDbxd" width=".536" height=".484" x="15.63" y="6.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".05"/></filter><filter id="in5UjCL" width=".681" height=".693" x="16.069" y="6.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".1"/></filter><filter id="iRLnZDo" width=".735" height=".766" x="13.521" y="6.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".1"/></filter><filter id="iHJdV1a" width=".608" height=".489" x="13.131" y="6.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".05"/></filter><filter id="iubb7Rc" width="1.492" height="1.051" x="15.569" y="4.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1289"/></filter><filter id="imxmf8J" width="1.451" height=".759" x="15.589" y="5.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".1"/></filter><filter id="i1fEdfT" width="1.492" height="1.051" x="12.627" y="4.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1289"/></filter><filter id="ifkCnSy" width="1.451" height=".759" x="12.648" y="5.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1289" stdDeviation=".1"/></filter><linearGradient id="iAtGVxc" x1="9.112" x2="18.219" y1="27.012" y2="28.855" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="ihBNZOe" x1="7.862" x2="5.547" y1="25.805" y2="25.433" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="ic5T6Vd" x1="11.357" x2="10.826" y1="24.142" y2="26.252" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="itQ4WOb" x1="25.417" x2="25.113" y1="20.645" y2="20.645" gradientUnits="userSpaceOnUse"><stop class="y_8gxtivd"/><stop offset="1" class="rtj1uebvi"/></linearGradient><linearGradient id="iPHCsKe" x1="25.472" x2="25.472" y1="13.184" y2="15.997" gradientUnits="userSpaceOnUse"><stop class="g_m2j6vsw"/><stop offset="1" class="rj2co3mwz"/></linearGradient><linearGradient id="ie3ZJpb" x1="24.195" x2="25.702" y1="13.917" y2="13.917" gradientUnits="userSpaceOnUse"><stop offset=".342" class="wvd2c67nn"/><stop offset="1" class="csun_suuu"/></linearGradient><linearGradient id="ieWXsZc" x1="4.021" x2="4.289" y1="16.825" y2="16.802" gradientUnits="userSpaceOnUse"><stop class="mvpa0lyup"/><stop offset="1" class="cici83huw"/></linearGradient><linearGradient id="idMleyc" x1="27.226" x2="28.976" y1="3.645" y2="9.38" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset="1" class="msr886b7s"/></linearGradient><linearGradient id="iPZVedb" x1="27.437" x2="27.067" y1="2.778" y2="2.994" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset="1" class="msr886b7s"/></linearGradient><linearGradient id="i1bgYrc" x1="25.17" x2="27.718" y1="3.731" y2="13.101" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset=".765" class="msr886b7s"/></linearGradient><linearGradient id="i0hmnFe" x1="21.517" x2="24.201" y1="3.112" y2="13.663" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset=".765" class="msr886b7s"/></linearGradient><linearGradient id="iCsAWdb" x1="12.121" x2="11.754" y1="7.158" y2="7.158" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iAwlMQd" x1="18.2" x2="17.73" y1="6.373" y2="7.827" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="idMFILe" x1="17.159" x2="12.779" y1="7.222" y2="7.875" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iVet5Pc" x1="11.749" x2="13.076" y1="8.768" y2="8.595" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iFw76ev" x1="12.055" x2="13.72" y1="6.845" y2="3.889" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iCtb9pC" x1="16.539" x2="16.359" y1="6.638" y2="6.748" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9W4CCb" x1="14.017" x2="13.838" y1="6.638" y2="6.748" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-merpeople" /></template>
<style>
.a1-19nbvs {
  stop-color: var(--svg-color--ffc82b, #FFC82B);
  stop-opacity: 0;
}

.a8pcdzbbi {
  d: path("M13.59 6.334a.512.512 0 0 0-.493.647h.989a.515.515 0 0 0-.495-.647");
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.asxi2vb-v {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.79 5.653c-.12-.11-.46-.298-.95-.253");
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.bc4d3sv8x {
  stop-color: var(--svg-color--f8af28, #F8AF28);
  stop-opacity: 0;
}

.c262ymbst {
  stop-color: var(--svg-color--e0912d, #E0912D);
}

.c4d2fsb7x {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.472 6.178a.8.8 0 0 0-.777.607c-.026.1.05.195.153.195h1.28a.132.132 0 0 0 .13-.155a.8.8 0 0 0-.786-.647");
}

.ce3469l3k {
  fill-rule: evenodd;
  d: path("M15.865 5.734c.412-.039.677.122.741.181a.27.27 0 1 0 .367-.398c-.175-.162-.591-.376-1.159-.323a.27.27 0 0 0 .05.54");
}

.cici83huw {
  stop-color: var(--svg-color--d58d21, #D58D21);
  stop-opacity: 0;
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpmh20bsf {
  cx: 17.577px;
  cy: 6.999px;
  r: 0.957px;
}

.csun_suuu {
  stop-color: var(--svg-color--ffd044, #FFD044);
}

.cz5i0kbhu {
  stop-color: var(--svg-color--ffb630, #FFB630);
}

.d_y07ubvt {
  fill: var(--svg-color--000, #000);
  d: path("M15.802 6.846c0-.163.13-.294.293-.294a.292.292 0 0 1 .26.428h-.519a.3.3 0 0 1-.034-.134");
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dty9fjfoc {
  d: path("M12.966 10.41c-.475.529-1.424 2.02-1.424 3.765v3.051c0 .359.291.65.65.65h5.314a.65.65 0 0 0 .65-.65v-3.051c0-1.744-.95-3.236-1.424-3.764z");
}

.e_lkicm0r {
  stop-color: var(--svg-color--e49023, #E49023);
}

.e-v9_qbao {
  stop-color: var(--svg-color--f3a22b, #F3A22B);
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e1610wluy {
  cx: 13.435px;
  cy: 6.553px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.223px;
  ry: 0.113px;
}

.ehj5k_bqv {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M27.077 3.395c0 .383.117.883.602 1.453c.669.788 1.008 1.22 1.008 1.844c0 .399-.118 1.305-1.008 1.93");
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ew294b97m {
  width: 2.963px;
  height: 0.908px;
  x: 23.363px;
  y: 9.499px;
  rx: 0.454px;
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f1ri06bus {
  stop-color: var(--svg-color--f2be56, #F2BE56);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fkps2fbrt {
  fill: var(--svg-color--ffb732, #FFB732);
  d: path("m20.813 13.33l-2.18-2.114c-.68-.61-1.462-.703-1.915-.836l.945 3.59c.22.184.953.847 1.586 1.453c.578.488 1.254.535 1.61.535h4.312v-2.125c-.426-.06-2.951-.279-4.12-.393a.4.4 0 0 1-.238-.11");
}

.fm7uiddyf {
  stop-color: var(--svg-color--eebe28, #EEBE28);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g_m2j6vsw {
  stop-color: var(--svg-color--fed044, #FED044);
}

.g-k6bqb8y {
  stop-color: var(--svg-color--e28c20, #E28C20);
  stop-opacity: 0;
}

.g-tfz_but {
  d: path("M10.7 19.134c0-1.425.76-2.102 1.16-2.243l5.66-.34c1.61.72 2.954 2.782 3.141 5.282c.188 2.5-.203 4.953-2.265 6.562c-1.65 1.288-3.959 1.552-4.938 1.532h-2.472c-2.625 0-3.246-1.891-3.356-2.297a11 11 0 0 0-.184-.599a.43.43 0 0 0-.221-.26c-.528-.243-1.52-.486-1.946-1.387a3.1 3.1 0 0 1-.28-1.63c.021-.214.231-.345.44-.297c.52.119.95.253 1.57.567a3.4 3.4 0 0 1 1.237 1.227c.065.11.238.111.304.002c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.766-.747 2.275-1.198 2.513c-.288.132-.62.278-.865.388c-.14.063-.209.223-.141.36c.474.957 1.468.87 2.858.87c1.851 0 2.96-1.325 2.844-2.723c-.063-1.813-1.563-2.516-2.57-3.149c-.524-.328-2.055-1.144-2.055-2.925");
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
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

.grojetr5t {
  d: path("m24.646 2.167l-.753 1.02a.2.2 0 0 0 .163.318l.21-.002a.15.15 0 0 1 .152.15v3.855a1 1 0 0 1-1 1h-.032c-.902 0-1.538-.624-1.71-1.227c-.105-.37-.112-.645-.033-.906c.082-.27.275-.58.67-.983c.862-.882.866-1.887.87-3.02v-.04a.15.15 0 0 0-.243-.117l-1.3 1.025a.15.15 0 0 0 .092.268h.37c.085 0 .153.071.137.155a2.13 2.13 0 0 1-.584 1.086c-.446.455-.75.889-.892 1.358c-.146.48-.109.943.028 1.425A2.76 2.76 0 0 0 23.452 9.5h2.772a2.76 2.76 0 0 0 2.661-1.967c.137-.482.175-.945.029-1.425c-.143-.47-.447-.903-.892-1.358a2.14 2.14 0 0 1-.585-1.086c-.015-.084.053-.155.138-.155h.37a.15.15 0 0 0 .092-.268l-1.3-1.025a.15.15 0 0 0-.243.118v.04c.004 1.132.008 2.137.87 3.019c.395.404.587.712.67.983c.079.26.072.536-.034.906c-.171.603-.798 1.227-1.776 1.227a.95.95 0 0 1-.951-.951V3.644a.15.15 0 0 1 .148-.15l.213-.002a.2.2 0 0 0 .159-.32l-.745-1.005a.25.25 0 0 0-.402 0");
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.gw-pmo7eh {
  stop-color: var(--svg-color--f3a22b, #F3A22B);
  stop-opacity: 0;
}

.gwan6obls {
  stop-color: var(--svg-color--f3a51f, #F3A51F);
}

.gx_q8ibzf {
  stop-color: var(--svg-color--fec131, #FEC131);
  stop-opacity: 0;
}

.h_88v9z9m {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.213 6.178a.8.8 0 0 1 .777.607a.157.157 0 0 1-.153.196h-1.28a.132.132 0 0 1-.13-.156a.8.8 0 0 1 .786-.647");
}

.h_vbz1byx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.056 6.442c.037.05-.04.108-.126.173s-.15.11-.187.061c-.036-.048.004-.14.09-.205c.087-.064.187-.077.223-.029");
}

.h5yhgbd1b {
  cx: 12.121px;
  cy: 6.999px;
  r: 0.571px;
}

.h7p61gvke {
  stop-color: var(--svg-color--fec131, #FEC131);
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.ht3r2np2u {
  stop-color: var(--svg-color--eaa130, #EAA130);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i8gxpdlwn {
  stop-color: var(--svg-color--d6803e, #D6803E);
}

.izfe3kb7l {
  stop-color: var(--svg-color--ffd13b, #FFD13B);
}

.j_v36nbwh {
  d: path("M14.056 6.784c0-.164-.134-.274-.17-.307l-.165.159l.102.206z");
}

.jk8wwdkvh {
  stop-color: var(--svg-color--ebaf51, #EBAF51);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jqineqbnv {
  stop-color: var(--svg-color--ffd13b, #FFD13B);
  stop-opacity: 0;
}

.jsw61abqz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.773 26.906c-.007.65.436 1.949 2.266 1.949h3.177c1.01-.014 3.317-.517 4.469-2.415");
}

.jt23f0b3k {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m14.655 6.929l-.44.974c-.055.2.076.401.262.401h.396c.186 0 .317-.203.262-.4l-.268-.975c-.057-.216-.152-.216-.212 0");
}

.k-il9ub1q {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.953 2.552c0 .984-.058 1.818-.946 2.718c-1.11 1.125-.686 2.145-.562 2.422c.226.508.812 1.219 2.265 1.219");
}

.k396ay83y {
  stop-color: var(--svg-color--ca7f13, #CA7F13);
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.ke65wb71h {
  stop-color: var(--svg-color--faa71f, #FAA71F);
  stop-opacity: 0;
}

.keqz-8g7v {
  stop-color: var(--svg-color--e49c45, #E49C45);
}

.kt1qsbbol {
  stop-color: var(--svg-color--ebaf51, #EBAF51);
  stop-opacity: 0;
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l1mhifosa {
  stop-color: var(--svg-color--f0b438, #F0B438);
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.lh1-bz9_s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.189 24.47c.41.163 1.402.785 2.097 1.97");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk2vrruzb {
  width: 2.963px;
  height: 0.908px;
  x: 23.363px;
  y: 9.499px;
  fill: var(--svg-color--eca63f, #ECA63F);
  rx: 0.454px;
}

.luqq4ccam {
  stop-color: var(--svg-color--f6c059, #F6C059);
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

.mmqokxbcz {
  d: path("m14.625 6.835l-.305.975a.31.31 0 0 0 .298.4h.451a.31.31 0 0 0 .299-.4l-.305-.975c-.065-.216-.37-.216-.438 0");
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.msr886b7s {
  stop-color: var(--svg-color--f6c059, #F6C059);
  stop-opacity: 0;
}

.mvpa0lyup {
  stop-color: var(--svg-color--d6a04a, #D6A04A);
}

.n-3g919bq {
  d: path("M16.056 6.442c.037.05-.04.108-.126.173s-.15.11-.187.061c-.036-.048.004-.14.09-.205c.087-.064.187-.077.223-.029");
}

.ntl62r8nt {
  d: path("m20.813 13.33l-2.18-2.114c-.68-.61-1.462-.703-1.915-.836l.945 3.59c.22.184.953.847 1.586 1.453c.578.488 1.254.535 1.61.535h4.312v-2.125c-.426-.06-2.951-.279-4.12-.393a.4.4 0 0 1-.238-.11");
}

.nvk-74bwn {
  stop-color: var(--svg-color--f2be56, #F2BE56);
}

.nwr0ulaka {
  stop-color: var(--svg-color--f0a23f, #F0A23F);
}

.o9z9v7bzx {
  stop-color: var(--svg-color--f4ab25, #F4AB25);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohaqjn6tw {
  fill-rule: evenodd;
  d: path("M13.823 5.734c-.412-.039-.677.122-.741.181a.27.27 0 1 1-.368-.398c.176-.162.592-.376 1.16-.323a.27.27 0 1 1-.05.54");
}

.ok4jdvb8r {
  d: path("M10.933 11.333c.775-.75 1.746-.925 2.113-.914v4.054h-1.422c-.112-.13-.218-.09-.258-.054c-.502.424-1.62 1.371-2.07 1.765s-1.208.498-1.531.5H6.13a.4.4 0 0 0-.273.108l-.472.44a.537.537 0 0 1-.748-.769l.358-.363a.102.102 0 0 0-.022-.161l-.068-.038a.32.32 0 0 0-.391.058l-.65.68a.506.506 0 0 1-.754-.674l.788-.944a.8.8 0 0 1 .518-.28l3.203-.37a.3.3 0 0 0 .172-.08c.758-.72 2.284-2.198 3.142-2.958");
}

.os1l35bms {
  stop-color: var(--svg-color--d89328, #D89328);
}

.osxm7thcc {
  cx: 17.577px;
  cy: 6.999px;
  r: 0.571px;
}

.ow01cbczd {
  d: path("M25.256 13.184a.34.34 0 0 0-.338.338v.018c0 .129.072.24.178.298c.017.01.017.04 0 .049a.34.34 0 0 0-.178.297v.019c0 .13.073.242.18.298c.007.004.005.015-.003.015a.405.405 0 0 0-.143.785c.019.007.022.04.005.052a.349.349 0 0 0 .186.644h.762a.35.35 0 0 0 .2-.636c-.035-.024-.041-.11-.01-.137a.404.404 0 0 0-.036-.633c-.026-.019-.022-.081.005-.097a.34.34 0 0 0 .166-.291v-.019a.34.34 0 0 0-.168-.292c-.026-.015-.029-.065-.005-.082a.34.34 0 0 0 .133-.27v-.018a.34.34 0 0 0-.338-.338z");
}

.ozaj1r-nb {
  stop-color: var(--svg-color--f1c057, #F1C057);
}

.p--a0qx0q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.336 23.952c-.308.353-1.133 1.101-1.885 1.832");
}

.p--zv6bvm {
  stop-color: var(--svg-color--ffc82b, #FFC82B);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p4gb2ru0v {
  stop-color: var(--svg-color--eebe28, #EEBE28);
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

.pkl3f-q-p {
  stop-color: var(--svg-color--f1c057, #F1C057);
  stop-opacity: 0;
}

.pqitq_btv {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M24.96 3.473v4.22c-.026.213.05.798.625 1.085c.575.288 1.211.078 1.422 0");
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q6gsdgb-z {
  d: path("M24.359 10.407h.93v19.377a.15.15 0 0 1-.15.15h-.63a.15.15 0 0 1-.15-.15z");
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qag7llucc {
  stop-color: var(--svg-color--f3a51f, #F3A51F);
  stop-opacity: 0;
}

.qct52e6cd {
  cx: 12.121px;
  cy: 6.999px;
  r: 0.957px;
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r02p8ubqo {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m17.607 3.284l.246.122c.43.214.676.703.584 1.223L18.1 6.373c-.03.18-.15.301-.328.306c.02-.29.04-.755.047-.829c.025-.248-.014-.321-.242-.548a.72.72 0 0 1-.215-.49v-.489a.33.33 0 0 0-.247-.305c-.369-.092-1.138-.245-2.245-.245s-1.877.153-2.246.245a.3.3 0 0 0-.246.305v.49a.6.6 0 0 1-.215.49l-.093.091c-.123.092-.185.283-.185.436c.008.09.02.603.034.817a.36.36 0 0 1-.34-.305l-.34-1.743c-.06-.49.185-.979.616-1.193c.582-.255.793-.642 1.261-1.04c.339-.306.83-.398 1.262-.184c.307.092.646.092.953 0c.462-.153.985-.03 1.354.306l.461.459c.123.153.277.245.462.337");
}

.r7873db9t {
  cx: 13.435px;
  cy: 6.553px;
  rx: 0.223px;
  ry: 0.113px;
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rj2co3mwz {
  stop-color: var(--svg-color--eaa22b, #EAA22B);
}

.rrhclt3xn {
  fill: var(--svg-color--000, #000);
  d: path("M13.883 6.846a.29.29 0 0 0-.293-.294a.292.292 0 0 0-.26.428h.518a.3.3 0 0 0 .035-.134");
}

.rtj1uebvi {
  stop-color: var(--svg-color--e69440, #E69440);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s2817ub-i {
  fill: var(--svg-color--ffb827, #FFB827);
  d: path("m14.625 6.835l-.305.975a.31.31 0 0 0 .298.4h.451a.31.31 0 0 0 .299-.4l-.305-.975c-.065-.216-.37-.216-.438 0");
}

.s4jilbbng {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M14.844 8.794c-.291 0-.565-.069-.795-.189c-.078-.04-.163.049-.113.12c.192.291.527.485.908.485c.38 0 .716-.194.908-.485c.05-.074-.035-.16-.114-.12c-.23.12-.5.189-.794.189");
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.stlhbac-j {
  stop-color: var(--svg-color--fcb02c, #FCB02C);
}

.swsncabgk {
  d: path("M11.92 6.647c-.016-.18-.034-.693-.034-.825c0-.153.061-.336.184-.428l.093-.092a.6.6 0 0 0 .215-.49v-.488c0-.153.092-.276.246-.306c.37-.092 1.138-.245 2.246-.245c1.107 0 1.876.153 2.245.245a.33.33 0 0 1 .247.306v.489a.72.72 0 0 0 .215.49c.288.201.27.312.246.55c-.008.074-.03.685-.051.826l-.153 2.27c-.092 1.015-.89 1.722-1.84 1.722h-1.842c-.982 0-1.75-.707-1.841-1.722z");
}

.sy7qt-bzl {
  stop-color: var(--svg-color--d6803e, #D6803E);
  stop-opacity: 0;
}

.szy7o-f_b {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.844 8.794c-.291 0-.565-.069-.795-.189c-.078-.04-.163.049-.113.12c.192.291.527.485.908.485c.38 0 .716-.194.908-.485c.05-.074-.035-.16-.114-.12c-.23.12-.5.189-.794.189Z");
}

.t_l-40b1y {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m26.827 2.56l.993.718h-.72");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tfpize5dt {
  stop-color: var(--svg-color--ebad2f, #EBAD2F);
}

.ti8dkw8jh {
  stop-color: var(--svg-color--d77735, #D77735);
}

.tm-f6fwhm {
  cx: 17.577px;
  cy: 6.999px;
  r: 0.571px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.tp4a5acim {
  stop-color: var(--svg-color--faa71f, #FAA71F);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.udxjy24sj {
  stop-color: var(--svg-color--ebad2f, #EBAD2F);
  stop-opacity: 0;
}

.uktosabkt {
  d: path("m25.562 3.2l-.617-.945l-.173.945z");
}

.uw8wenb6w {
  stop-color: var(--svg-color--d77735, #D77735);
  stop-opacity: 0;
}

.ux31pqfvx {
  stop-color: var(--svg-color--dd8f15, #DD8F15);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.va3lhtbnh {
  d: path("M16.55 6.777a.5.5 0 0 0-.133-.264l-.148.163l.067.13z");
}

.vj07kubhl {
  stop-color: var(--svg-color--f8a33e, #F8A33E);
}

.vj4m2tb3q {
  stop-color: var(--svg-color--ffd336, #FFD336);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wvd2c67nn {
  stop-color: var(--svg-color--ffb732, #FFB732);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x3htwqbtq {
  stop-color: var(--svg-color--ffd32f, #FFD32F);
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xlsa3ib-s {
  stop-color: var(--svg-color--eebc29, #EEBC29);
  stop-opacity: 0;
}

.xyzuznb3l {
  d: path("M24.808 12.993h-.5c-.53 0-.779.382-.887.863l.848.266l.042-.177a.1.1 0 0 1 .11-.076l.2.027c.078.01.136.077.136.156v.316a.473.473 0 1 0 .945 0v-.453c0-.258-.027-.461-.304-.692a1 1 0 0 0-.59-.23");
}

.y_8gxtivd {
  stop-color: var(--svg-color--cc802a, #CC802A);
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y2re8hl9w {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M10.7 19.134c0-1.425.76-2.102 1.16-2.243l5.66-.34c1.61.72 2.954 2.782 3.141 5.282c.188 2.5-.203 4.953-2.265 6.562c-1.65 1.288-3.959 1.552-4.938 1.532h-2.472c-2.625 0-3.246-1.891-3.356-2.297a11 11 0 0 0-.184-.599a.43.43 0 0 0-.221-.26c-.528-.243-1.52-.486-1.946-1.387a3.1 3.1 0 0 1-.28-1.63c.021-.214.231-.345.44-.297c.52.119.95.253 1.57.567a3.4 3.4 0 0 1 1.237 1.227c.065.11.238.111.304.002c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.766-.747 2.275-1.198 2.513c-.288.132-.62.278-.865.388c-.14.063-.209.223-.141.36c.474.957 1.468.87 2.858.87c1.851 0 2.96-1.325 2.844-2.723c-.063-1.813-1.563-2.516-2.57-3.149c-.524-.328-2.055-1.144-2.055-2.925");
}

.y759xzbwp {
  stop-color: var(--svg-color--eaa130, #EAA130);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yntatvzjv {
  d: path("m17.607 3.284l.246.122c.43.214.676.703.584 1.223L18.1 6.373c-.03.18-.15.301-.328.306c.02-.29.04-.755.047-.829c.025-.248-.014-.321-.242-.548a.72.72 0 0 1-.215-.49v-.489a.33.33 0 0 0-.247-.305c-.369-.092-1.138-.245-2.245-.245s-1.877.153-2.246.245a.3.3 0 0 0-.246.305v.49a.6.6 0 0 1-.215.49l-.093.091c-.123.092-.185.283-.185.436c.008.09.02.603.034.817a.36.36 0 0 1-.34-.305l-.34-1.743c-.06-.49.185-.979.616-1.193c.582-.255.793-.642 1.261-1.04c.339-.306.83-.398 1.262-.184c.307.092.646.092.953 0c.462-.153.985-.03 1.354.306l.461.459c.123.153.277.245.462.337");
}

.ytc7mhb5z {
  d: path("M16.095 6.334a.512.512 0 0 1 .493.647h-.989a.514.514 0 0 1 .495-.647");
}

.z3ywhob_s {
  stop-color: var(--svg-color--e28c20, #E28C20);
}

.z6e6mw_8y {
  d: path("M4.022 15.975a.517.517 0 0 1 1.033-.063l.052.87a.517.517 0 0 1-1.033.062z");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zl8do3b6h {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.898 5.653c.12-.11.46-.298.95-.253");
}

.zmvijm-xp {
  stop-color: var(--svg-color--eebc29, #EEBC29);
}

.zo19yuphz {
  stop-color: var(--svg-color--b36301, #B36301);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zyosecbvv {
  d: path("M18.661 26.708c0-5.344-3.922-7.969-5.234-9l3.25-1.453c1.125.52 3.035 2.357 3.453 5.109c.485 3.188-.927 4.927-1.469 5.344");
}

</style>
