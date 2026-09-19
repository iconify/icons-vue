<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iSFZDbe)" class="iew0usbao"/><path fill="url(#i7jw8Ac)" class="z1znjqbpa"/><path fill="url(#inT0zab)" class="c5jm6bc5b"/><path fill="url(#iRI2yhd)" class="g3ux3cbys"/><path fill="url(#ihnjaeb)" class="ny9_xhbeh"/><path fill="url(#iSlT4ne)" class="kff4jhirp"/><path fill="url(#iK6Pc4d)" class="kff4jhirp"/><path fill="url(#iy1LKre)" class="mp60pitjs"/><path fill="url(#iNpkCTb)" class="mp60pitjs"/><g filter="url(#iMFK5zc)"><path fill="url(#iA5kq2b)" class="zlbshaclx"/></g><path fill="url(#iOcjPde)" class="zlbshaclx"/><path fill="url(#iuutWxb)" class="zlbshaclx"/><path fill="url(#iz4UGBc)" class="zlbshaclx"/><path fill="url(#i1mGgoc)" class="zlbshaclx"/><g filter="url(#iy02UBb)"><path class="t6xf4abei"/></g><g filter="url(#iwh93fb)"><path fill="url(#ixuwDrk)" class="ma1eaibyy"/><path fill="url(#inleJUM)" class="ma1eaibyy"/><path fill="url(#iLncPkF)" class="ma1eaibyy"/><path fill="url(#iaJSz6d)" class="ma1eaibyy"/></g><g filter="url(#idwwqVd)"><path stroke="url(#iD8RBIb)" class="jcob5jtiy"/></g><path fill="url(#i8FjeSc)" class="qjbo_t1sy"/><g filter="url(#i9ljADe)"><path fill="url(#icVRMfe)" class="vxsdimbtg"/><path fill="url(#i4VVz3b)" class="vxsdimbtg"/><path fill="url(#ioTjgRd)" class="vxsdimbtg"/><path fill="url(#iXfzfeb)" class="vxsdimbtg"/><path fill="url(#iV2Fcmz)" class="vxsdimbtg"/></g><g filter="url(#idqHWId)"><path class="j_b8lac6b"/></g><g filter="url(#iz7OVBb)"><path class="hcvm4ebih"/></g><g filter="url(#iawCuEe)"><path fill="url(#iSbnxEb)" class="a97q1ib6n"/><path fill="url(#ipsynQd)" class="a97q1ib6n"/></g><g filter="url(#ikYYZ2b)"><path fill="url(#iFw6OPe)" class="po86gjbou"/><path fill="url(#iSisO8b)" class="po86gjbou"/><path fill="url(#i0MeM2b)" class="po86gjbou"/><path fill="url(#iDHvgxc)" class="po86gjbou"/><path fill="url(#ixXsVbb)" class="po86gjbou"/></g><path class="uf5rerbdy"/><path fill="url(#iV4RUJc)" class="fe8z672go"/><path class="jo8lxfo6c"/><g filter="url(#iM2TCYd)"><path class="ctni3bc2i"/><path fill="url(#iOdjxdd)" class="s0kgwh2nk"/></g><g filter="url(#i5KZjmb)"><path fill="url(#ieaxaTb)" class="l41shdc2m"/></g><path class="i6bji0ert"/><path fill="url(#iTKb2wm)" class="hzcpqjbsn"/><path class="ohwsnsbac"/><g filter="url(#iKOjGdd)"><path fill="url(#iJg10Sc)" class="p28q85_am"/></g><g filter="url(#iRzcAmf)"><ellipse transform="rotate(-27.914 13.547 9.816)" class="pdyfmt2wz"/><ellipse fill="url(#i9dastb)" transform="rotate(-27.914 13.547 9.816)" class="w2q6f6-7d"/></g><path fill="url(#iz8eIyd)" class="h6pjyd91h"/><path fill="url(#ikoQM6b)" class="h6pjyd91h"/><path fill="url(#ilcdGHe)" class="h6pjyd91h"/><path fill="url(#iiZh78b)" class="n1y7abi5d"/><path fill="url(#iepQZvc)" class="n1y7abi5d"/><g filter="url(#ip670Rb)"><path class="h-_d65bgg"/></g><g filter="url(#iugZy6d)"><path class="jgmtvzbox"/></g><g filter="url(#iqaaL0d)"><path class="p3gkg64_n"/></g><g filter="url(#iRCi5ic)"><path class="mrhh70big"/></g><g filter="url(#iNMri1c)"><path fill="url(#iHXaVce)" class="jsqgobbht"/><path fill="url(#i2BUj5L)" class="jsqgobbht"/><path fill="url(#iqtSqJd)" class="jsqgobbht"/><path fill="url(#iNN1SaK)" class="jsqgobbht"/><path fill="url(#irzSjbb)" class="jsqgobbht"/><path fill="url(#ihI2zKe)" class="jsqgobbht"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><radialGradient id="iSFZDbe" cx="0" cy="0" r="1" gradientTransform="matrix(2.78125 -.09375 .1236 3.66674 2.774 28.754)" gradientUnits="userSpaceOnUse"><stop offset=".331" class="s-eg4sb7c"/><stop offset="1" class="o1jcigu0p"/></radialGradient><radialGradient id="i7jw8Ac" cx="0" cy="0" r="1" gradientTransform="rotate(151.68 11.043 17.873)scale(3.47887 3.35016)" gradientUnits="userSpaceOnUse"><stop class="lj4kaubvr"/><stop offset="1" class="ivc92ybcq"/></radialGradient><radialGradient id="iSlT4ne" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 6.107 14.429)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iK6Pc4d" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -1.436 26.475)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iy1LKre" cx="0" cy="0" r="1" gradientTransform="matrix(1.33305 3.92345 -1.7834 .60594 10.452 11.886)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="iNpkCTb" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -2.574 13.547)scale(1.04691 .91836)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iA5kq2b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24801 18.808 10.828)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iOcjPde" cx="0" cy="0" r="1" gradientTransform="matrix(-.40256 6.10192 -2.24332 -.148 21.157 10.596)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iuutWxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.70221 0 13.909 9.647)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iz4UGBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 1.99125 0 18.489 9.236)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="i1mGgoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.3125 -15.9292 0 16.047 9.629)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="to42tqmib"/><stop offset=".838" class="ijql4yr-c"/></radialGradient><radialGradient id="iD8RBIb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.484 -5.634)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="i8FjeSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16 14.367)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i4VVz3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.71897 10.1329 0 10.77 9.246)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="ioTjgRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63265 6.43634 0 20.86 9.246)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iXfzfeb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10651 -1.44082 .76733 -2.187 20.107 2.97)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iV2Fcmz" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 15.095 1.377)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iSbnxEb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80692 1.37358 -.3823 -1.05955 16.253 2.82)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="ipsynQd" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.16 -5.799)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iFw6OPe" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 .8008 -.44786 1.89357 19.62 3.98)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iSisO8b" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.037 -1.793)scale(4.28181 2.38793)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="i0MeM2b" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 12.612 -1.696)scale(2.56111 1.83441)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iDHvgxc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.794 3.863)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="ixXsVbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.453 3.738)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="iV4RUJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 9.912)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iOdjxdd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.425 .601)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTKb2wm" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.818 9.912)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i9dastb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.53 10.13)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikoQM6b" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.618 9.925)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="ilcdGHe" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.978 10.47)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iepQZvc" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.227 9.452)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="i2BUj5L" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 31.067)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="ihI2zKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.66)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><linearGradient id="inT0zab" x1="16" x2="16" y1="6.703" y2="34.611" gradientUnits="userSpaceOnUse"><stop class="zaeth0b6d"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="iRI2yhd" x1="10.918" x2="1.428" y1="24.003" y2="24.044" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ihnjaeb" x1="22.998" x2="28.652" y1="24.02" y2="24.02" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ixuwDrk" x1="16" x2="16.855" y1="11.656" y2="11.656" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="inleJUM" x1="14.927" x2="16.002" y1="11.501" y2="11.56" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iLncPkF" x1="16" x2="16" y1="12.055" y2="12.907" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iaJSz6d" x1="16" x2="16" y1="9.808" y2="10.754" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="icVRMfe" x1="21.364" x2="11.24" y1="5.165" y2="5.165" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="ieaxaTb" x1="18.96" x2="18.646" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJg10Sc" x1="14.562" x2="14.248" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iz8eIyd" x1="22.436" x2="21.23" y1="9.992" y2="12.168" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iiZh78b" x1="10.15" x2="11.609" y1="10.696" y2="10.569" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iHXaVce" x1="7.493" x2="11.284" y1="19.754" y2="30.805" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="iqtSqJd" x1="16" x2="16" y1="16.02" y2="17.379" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="iNN1SaK" x1="5" x2="6.055" y1="24.254" y2="24.254" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="irzSjbb" x1="27" x2="25.524" y1="25.192" y2="25.192" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><filter id="iMFK5zc" width="10.72" height="12.542" x="10.937" y="4.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_690"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3_690" result="effect2_innerShadow_3_690"/></filter><filter id="iy02UBb" width="3.877" height="4.9" x="13.854" y="9.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".5"/></filter><filter id="iwh93fb" width="2.077" height="3.1" x="14.961" y="9.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".05"/></filter><filter id="idwwqVd" width="3.718" height="1.573" x="14.141" y="13.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".05"/></filter><filter id="i9ljADe" width="12.873" height="8.356" x="9.564" y="1.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_690"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3_690" result="effect2_innerShadow_3_690"/></filter><filter id="idqHWId" width="2.339" height="1.19" x="17.589" y="7.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_690"/></filter><filter id="iz7OVBb" width="2.339" height="1.176" x="12.333" y="7.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_690"/></filter><filter id="iawCuEe" width="6.584" height="5.992" x="9.919" y="2.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".125"/></filter><filter id="ikYYZ2b" width="6.361" height="5.736" x="15.841" y="3.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".125"/></filter><filter id="iM2TCYd" width=".787" height=".696" x="17.448" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".05"/></filter><filter id="i5KZjmb" width=".891" height=".913" x="18.288" y="9.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".1"/></filter><filter id="iKOjGdd" width=".986" height="1.04" x="13.845" y="9.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".1"/></filter><filter id="iRzcAmf" width=".913" height=".705" x="13.09" y="9.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".05"/></filter><filter id="ip670Rb" width="1.329" height="2.379" x="9.968" y="9.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".125"/></filter><filter id="iugZy6d" width="1.447" height="2.403" x="20.712" y="9.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".125"/></filter><filter id="iqaaL0d" width="2.405" height="1.16" x="12.252" y="7.233" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".125"/></filter><filter id="iRCi5ic" width="2.405" height="1.16" x="17.531" y="7.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_690" stdDeviation=".125"/></filter><filter id="iNMri1c" width="22" height="14.1" x="5" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_690"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:technologist" /></template>
<style>
.a-otvg7dq {
  stop-color: var(--svg-color--806b97, #806B97);
}

.a61ap5b7j {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a97q1ib6n {
  d: path("m16.233 5.212l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.012.805.42.805.893v1.485z");
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.auud8yb7i {
  stop-color: var(--svg-color--4a3261, #4A3261);
  stop-opacity: 0;
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bowxt9bwr {
  stop-color: var(--svg-color--6f5783, #6F5783);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c5jm6bc5b {
  d: path("M16 15.52c-6.07 0-11 4.92-11 11v3.5h22v-3.5c0-6.08-4.93-11-11-11");
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.ctni3bc2i {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.623c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.d9m_15bme {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

.dmu1fh1sq {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.fe8z672go {
  d: path("M18.184 9.435a.893.893 0 0 1 .86 1.127H17.32a.896.896 0 0 1 .864-1.128");
}

.ft5dv1b6b {
  fill: none;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g3ux3cbys {
  d: path("M8.98 18.02a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

.g48yfbn9k {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.gzfhb8b1n {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

.h-_d65bgg {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.963 9.63a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.h6pjyd91h {
  d: path("M20.922 12.168q.101-1.596.184-3.19a1.61 1.61 0 0 1-.184 3.19");
}

.hcvm4ebih {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.589 7.74a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.55a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hzcpqjbsn {
  d: path("M13.816 9.435a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.i6bji0ert {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.61 9.163c-.654 0-1.206.45-1.356 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.iew0usbao {
  d: path("M8.329 30.02a3.138 3.138 0 1 0-6.267 0z");
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ijql4yr-c {
  stop-color: var(--svg-color--d88630, #D88630);
}

.ivc92ybcq {
  stop-color: var(--svg-color--f8c743, #F8C743);
}

.j_b8lac6b {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M19.733 7.848a1.85 1.85 0 0 0-.687-.411c-.305-.096-.686-.122-1.213-.057a.277.277 0 1 0 .067.55c.482-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.jcob5jtiy {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m14.65 13.33l-.002-.001a.23.23 0 0 0-.27.047a.21.21 0 0 0-.024.27c.349.528.956.88 1.646.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.001c-.39.203-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.jehi2ihjx {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

.jgmtvzbox {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.962 11.518q.058-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.jo8lxfo6c {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.327c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jsqgobbht {
  d: path("M26.03 16.02H5.97a.97.97 0 0 0-.97.97v13.03h22V16.99a.97.97 0 0 0-.97-.97");
}

.k71v6_7um {
  stop-color: var(--svg-color--51366c, #51366C);
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kff4jhirp {
  d: path("M20.861 12.078c.335-.011.65-.125.905-.309v.931c0 .893-.532 1.689-1.341 2.019q.256-.546.346-1.18z");
}

.l17xqebtl {
  stop-color: var(--svg-color--594170, #594170);
}

.l294t3zvi {
  stop-color: var(--svg-color--847498, #847498);
}

.l41shdc2m {
  d: path("M18.979 10.21a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj4kaubvr {
  stop-color: var(--svg-color--ffeb48, #FFEB48);
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.ma1eaibyy {
  d: path("m15.618 10.113l-.532 1.838c-.108.378.152.757.521.757h.786c.37 0 .63-.384.521-.757l-.532-1.838c-.113-.407-.645-.407-.764 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mp60pitjs {
  d: path("M11.139 12.078a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.341 2.019a4.1 4.1 0 0 1-.346-1.18z");
}

.mrhh70big {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.561 7.973c-.257-.185-.898-.509-1.655-.382");
}

.n1y7abi5d {
  d: path("M10.946 8.969a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nonrr22es {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

.ny9_xhbeh {
  d: path("M23 18.03v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1-qqkidl {
  stop-color: var(--svg-color--78698c, #78698C);
}

.o1jcigu0p {
  stop-color: var(--svg-color--eba02a, #EBA02A);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohv650iba {
  stop-color: var(--svg-color--52376c, #52376C);
  stop-opacity: 0;
}

.ohwsnsbac {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.327a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .061-.235");
}

.p28q85_am {
  d: path("M14.631 10.222c0-.289-.234-.48-.298-.539l-.288.279l.177.361z");
}

.p3gkg64_n {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.627 8.019c.257-.185.897-.51 1.655-.382");
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.p9llu9bpa {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

.pdyfmt2wz {
  cx: 13.547px;
  cy: 9.816px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po86gjbou {
  d: path("m21.213 8.584l-.03-.63c-.01-.764-.641-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.059-.136-.12-.368c-.256-.97.671-1.713 1.656-1.522c.973.19 2.082.517 2.902 1.052c1.744 1.138 1.439 3.189.52 4.154");
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.ppwrykbzp {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q0dxfdmim {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

.qjbo_t1sy {
  d: path("M16 13.724c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.197.209c.335.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.qqk6g6zlh {
  stop-color: var(--svg-color--3d2555, #3D2555);
}

.qufyc6r7b {
  stop-color: var(--svg-color--56416b, #56416B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r1d3vkbxd {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.s-eg4sb7c {
  stop-color: var(--svg-color--fdc64d, #FDC64D);
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s0kgwh2nk {
  d: path("M18.118 9.623c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.szjcm-w7x {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

.t_w5hobcp {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

.t6xf4abei {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.514 10.309l-.635 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.383.52-.756l-.531-1.838c-.114-.407-.542-.407-.661 0");
}

.to42tqmib {
  stop-color: var(--svg-color--eda22a, #EDA22A);
  stop-opacity: 0;
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.uem0lbchq {
  stop-color: var(--svg-color--4f3568, #4F3568);
}

.uf5rerbdy {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 9.163c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.ux-m5bn7d {
  stop-color: var(--svg-color--ab9cbe, #AB9CBE);
}

.v1n2dlbml {
  stop-color: var(--svg-color--3b2b50, #3B2B50);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.vxsdimbtg {
  d: path("M20.855 4.185c.514.177.976.536 1.267 1.051a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.875v1.188a1.75 1.75 0 0 0-.667-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.445a2.35 2.35 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.383-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.913-.188c.843 0 1.58.456 1.989 1.132c.307.51.79.88 1.352 1.073");
}

.w2q6f6-7d {
  cx: 13.547px;
  cy: 9.816px;
  rx: 0.39px;
  ry: 0.197px;
}

.w6exmsbsa {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.w9bfwpbnq {
  stop-color: var(--svg-color--60407f, #60407F);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xqmtwwbyq {
  stop-color: var(--svg-color--614c77, #614C77);
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yr342ibfl {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.z1znjqbpa {
  d: path("M29.938 30.02q.004-.082.004-.163a3.138 3.138 0 1 0-6.27.162z");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zlbshaclx {
  d: path("M11.175 13.593a3.916 3.916 0 0 0 3.886 3.405h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.237-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.zt_ualb3u {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

</style>
