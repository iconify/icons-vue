<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3VvExe)" class="nxkajtbcb"/><path fill="url(#iKH3Neb)" class="nxkajtbcb"/><path fill="url(#iyv2Lzd)" class="nxkajtbcb"/><path fill="url(#ihtpwpb)" class="nxkajtbcb"/><path fill="url(#iEE61uc)" class="nxkajtbcb"/><path fill="url(#ifA47ke)" class="nxkajtbcb"/><path fill="url(#inSDHub)" class="nxkajtbcb"/><path fill="url(#i4esu8F)" class="nxkajtbcb"/><path fill="url(#iOreGSm)" class="nxkajtbcb"/><path fill="url(#il7PIdc)" class="nxkajtbcb"/><path fill="url(#ikhYhGb)" class="nxkajtbcb"/><path fill="url(#i772blR)" class="cxe48lb_z"/><path fill="url(#iNlRzPc)" class="cxe48lb_z"/><path class="ucms-5btk"/><path fill="url(#iTOBlge)" class="bstpv-bhs"/><path fill="url(#iKxrrFQ)" class="bstpv-bhs"/><path fill="url(#iQeLLne)" class="wwqc60d-y"/><path fill="url(#ixDbUWb)" class="wwqc60d-y"/><path fill="url(#iU655Ec)" class="wwqc60d-y"/><path fill="url(#iD97qlc)" class="wwqc60d-y"/><path fill="url(#itZuqEb)" class="lo-gs9dac"/><path fill="url(#imb9wge)" class="lo-gs9dac"/><path fill="url(#iTOps8c)" class="u-d4s4bdt"/><path fill="url(#iRs3E4b)" class="u-d4s4bdt"/><path fill="url(#iObpPFb)" class="g5an-sbwv"/><path fill="url(#i7qPi6b)" class="g5an-sbwv"/><g filter="url(#i6wKsXb)"><path fill="url(#iiqXuLH)" class="wvtv-xasy"/></g><path fill="url(#i06jpDe)" class="wvtv-xasy"/><path fill="url(#i0wHJWc)" class="wvtv-xasy"/><path fill="url(#ioWjLfc)" class="wvtv-xasy"/><path fill="url(#iSk2fIy)" class="wvtv-xasy"/><g filter="url(#i3P8A9d)"><path class="mi59_y10o"/></g><g filter="url(#iXfoeKc)"><path fill="url(#i3tiu4d)" class="v-7tk2b_j"/><path fill="url(#iWiTmvU)" class="v-7tk2b_j"/><path fill="url(#ipxZQ3s)" class="v-7tk2b_j"/><path fill="url(#iLkDyIb)" class="v-7tk2b_j"/></g><g filter="url(#iqRKtve)"><path stroke="url(#ikYFcGc)" class="z9_rqvvaq"/></g><path fill="url(#iK2ah7d)" class="e-ldqeb8i"/><g filter="url(#iR9dTCb)"><path fill="url(#iZ4dxxr)" class="gmqj_xbtp"/><path fill="url(#iHbRS7d)" class="gmqj_xbtp"/><path fill="url(#iNY6mfc)" class="gmqj_xbtp"/><path fill="url(#iM9gZhd)" class="gmqj_xbtp"/><path fill="url(#iS9ndXb)" class="gmqj_xbtp"/></g><g filter="url(#isDi5Rc)"><path class="ueyu2dboe"/></g><g filter="url(#iZfWrHc)"><path class="b4k1jibsk"/></g><g filter="url(#iAQCRGb)"><path fill="url(#izO17Nb)" class="z8-kq75ul"/><path fill="url(#i8bhh4c)" class="z8-kq75ul"/></g><g filter="url(#inGKvGe)"><path fill="url(#inxyzWb)" class="srkb94biz"/><path fill="url(#iNIFqCe)" class="srkb94biz"/><path fill="url(#ilpwFUb)" class="srkb94biz"/><path fill="url(#i6yNkXd)" class="srkb94biz"/><path fill="url(#i1jCOzs)" class="srkb94biz"/></g><path class="euzc7j3gp"/><path fill="url(#i3Lj15c)" class="tbc4r9bem"/><path class="n09qpobxv"/><g filter="url(#iqxXxkd)"><path class="j_6dos1tq"/><path fill="url(#ifMpVrb)" class="nos_wub9n"/></g><g filter="url(#iZKMLXE)"><path fill="url(#iZkDaCc)" class="na42z7pyh"/></g><path class="y-8a9ebxe"/><path fill="url(#inMjAAd)" class="z53-fccwe"/><path class="rpo29iblg"/><g filter="url(#iHb7CWc)"><path fill="url(#iT5kQoA)" class="fjg5psbub"/></g><g filter="url(#iHfIFNb)"><ellipse transform="rotate(-27.914 16.6 12.997)" class="hn1aitb-c"/><ellipse fill="url(#iWutqrX)" transform="rotate(-27.914 16.6 12.997)" class="wem6qfvha"/></g><path fill="url(#ieVtYmC)" class="f3m4g1bzs"/><path fill="url(#iD3pOgb)" class="f3m4g1bzs"/><path fill="url(#icCkDsb)" class="f3m4g1bzs"/><path fill="url(#i7sNsFb)" class="ed7o1ee4q"/><path fill="url(#iqwMs5m)" class="ed7o1ee4q"/><g filter="url(#i8k7lMd)"><path class="ubkqzsjyf"/></g><g filter="url(#iOOguHe)"><path class="zbilkeb4d"/></g><g filter="url(#ixmiJfb)"><path class="idrz6l3rr"/></g><g filter="url(#i1ky0nb)"><path class="l7xcc7bbb"/></g><g filter="url(#ibiN6nd)"><path stroke="url(#iSzNbCT)" class="qzq3pc74b"/></g><g filter="url(#iukFw5c)"><path stroke="url(#iAaNbJd)" class="o84wv822i"/></g><g filter="url(#ibudoTb)"><path stroke="url(#i1QNrcc)" class="t-rdkjm1g"/></g><g filter="url(#iJAAzwk)"><path stroke="url(#inCrPtd)" class="pfpp9kb0x"/></g><defs><radialGradient id="i3VvExe" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 6.36 11.885)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="wkdez3bsl"/><stop offset="1" class="uovxktaxm"/><stop offset="1" class="ptqby1bwa"/></radialGradient><radialGradient id="iKH3Neb" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 3.021 7.434)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="qqqtnz_cz"/><stop offset="1" class="tljjnprhh"/></radialGradient><radialGradient id="ihtpwpb" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 5.085 5.072)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="gk2jlbbkx"/><stop offset="1" class="q-_hp3b8x"/></radialGradient><radialGradient id="iEE61uc" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 6.734 3.908)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="gk2jlbbkx"/><stop offset="1" class="q-_hp3b8x"/></radialGradient><radialGradient id="ifA47ke" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 3.96875 -.56716 -.09602 8.702 3.142)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gk2jlbbkx"/><stop offset="1" class="q-_hp3b8x"/></radialGradient><radialGradient id="inSDHub" cx="0" cy="0" r="1" gradientTransform="matrix(-.89063 .84376 -.848 -.8951 10.046 3.69)" gradientUnits="userSpaceOnUse"><stop class="v3jqojv9j"/><stop offset="1" class="oih2nzbsq"/></radialGradient><radialGradient id="i4esu8F" cx="0" cy="0" r="1" gradientTransform="rotate(138.965 3.627 2.944)scale(1.11858 .93215)" gradientUnits="userSpaceOnUse"><stop class="v3jqojv9j"/><stop offset="1" class="oih2nzbsq"/></radialGradient><radialGradient id="iOreGSm" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 .71876 -.65233 -.42542 6.172 3.345)" gradientUnits="userSpaceOnUse"><stop class="v3jqojv9j"/><stop offset="1" class="oih2nzbsq"/></radialGradient><radialGradient id="il7PIdc" cx="0" cy="0" r="1" gradientTransform="rotate(129.369 1.202 3.4)scale(.78825 .71541)" gradientUnits="userSpaceOnUse"><stop class="v3jqojv9j"/><stop offset="1" class="oih2nzbsq"/></radialGradient><radialGradient id="ikhYhGb" cx="0" cy="0" r="1" gradientTransform="rotate(85.723 -.505 5.09)scale(2.30438 .44699)" gradientUnits="userSpaceOnUse"><stop class="z_yn3vbua"/><stop offset="1" class="j6lbcibwa"/></radialGradient><radialGradient id="iTOBlge" cx="0" cy="0" r="1" gradientTransform="matrix(-8.71543 2.79839 -2.98394 -9.29332 26.672 27.203)" gradientUnits="userSpaceOnUse"><stop class="ip469ff8c"/><stop offset="1" class="v0q_-i93u"/></radialGradient><radialGradient id="iKxrrFQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.62502 2.66619 0 11.405 30.002)" gradientUnits="userSpaceOnUse"><stop class="xjv40os-m"/><stop offset="1" class="yrxkt-bta"/></radialGradient><radialGradient id="ixDbUWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -5.4375 0 3.467 13.002)" gradientUnits="userSpaceOnUse"><stop class="ya78f26qa"/><stop offset="1" class="jfma4ebms"/></radialGradient><radialGradient id="iU655Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-7.94466 -1.83797 .619 -2.67566 17.482 21.304)" gradientUnits="userSpaceOnUse"><stop class="q2kyq2xrt"/><stop offset="1" class="wogt4ot2h"/></radialGradient><radialGradient id="imb9wge" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.15625 -2.61254 0 19.5 21.19)" gradientUnits="userSpaceOnUse"><stop class="jt0cc3bxg"/><stop offset="1" class="kq1evibhh"/></radialGradient><radialGradient id="iTOps8c" cx="0" cy="0" r="1" gradientTransform="rotate(103.679 7.015 17.89)scale(3.85344 4.57759)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset=".909" class="by5wrxbms"/></radialGradient><radialGradient id="iRs3E4b" cx="0" cy="0" r="1" gradientTransform="matrix(.34668 .47545 -.4039 .2945 25.176 15.623)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iObpPFb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5056 3.16964 -1.44074 .68436 12.943 15.443)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="i7qPi6b" cx="0" cy="0" r="1" gradientTransform="matrix(.3764 1.17871 -1.03397 .33018 13.724 15.434)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iiqXuLH" cx="0" cy="0" r="1" gradientTransform="matrix(-6.17882 0 0 -10.9303 22.818 14.193)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="i06jpDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.00172 15.5671 0 19.27 21.68)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="bkz_cdc-o"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="i0wHJWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.47573 7.2119 -2.6514 -.1749 25.594 13.918)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="ioWjLfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.67105 2.01185 0 17.028 12.797)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iSk2fIy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.81451 2.35348 0 22.441 12.311)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="ikYFcGc" cx="0" cy="0" r="1" gradientTransform="matrix(.41032 -.73213 2.1305 1.19402 18.168 18.08)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iK2ah7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.85184 3.42718 0 19.5 18.376)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iHbRS7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.75928 11.9761 0 13.32 12.323)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iNY6mfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.29345 7.60715 0 25.245 12.323)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iM9gZhd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8432 -1.46596 .78072 -2.04675 24.354 4.905)" gradientUnits="userSpaceOnUse"><stop class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iS9ndXb" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.514 17.978)scale(2.04536 4.73609)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="izO17Nb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.49941 1.62344 -.45184 -1.2523 19.8 4.728)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="i8bhh4c" cx="0" cy="0" r="1" gradientTransform="matrix(3.80361 -6.0223 6.67209 4.21401 13.08 10.353)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="inxyzWb" cx="0" cy="0" r="1" gradientTransform="matrix(4.00168 .9465 -.52935 2.238 23.78 6.099)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iNIFqCe" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 16.105 -1.59)scale(5.0607 2.82231)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="ilpwFUb" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 15.599 -1.474)scale(3.02699 2.16811)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="i6yNkXd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.67129 1.36061 -1.47087 -6.13088 25.166 5.96)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="i1jCOzs" cx="0" cy="0" r="1" gradientTransform="matrix(-.13868 .45353 -2.07349 -.634 23.581 5.813)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="i3Lj15c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9589 -1.52524 0 22.079 13.11)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ifMpVrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2741 -.35322 .4863 -.37738 21.81 13.21)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="inMjAAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .95895 -1.52532 0 16.921 13.11)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iWutqrX" cx="0" cy="0" r="1" gradientTransform="matrix(-.00914 -.58396 .70194 -.01099 16.583 13.369)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iD3pOgb" cx="0" cy="0" r="1" gradientTransform="matrix(.74289 2.65134 -2.52958 .70877 24.958 13.126)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="icCkDsb" cx="0" cy="0" r="1" gradientTransform="matrix(.93108 -1.27776 1.07102 .78043 25.384 13.77)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iqwMs5m" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.172 12.111)scale(2.50172 2.45942)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="i6wKsXb" width="12.829" height="14.787" x="13.516" y="6.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3859"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3859" result="effect2_innerShadow_4002_3859"/></filter><filter id="i3P8A9d" width="4.219" height="5.428" x="17.146" y="12.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".5"/></filter><filter id="iXfoeKc" width="2.419" height="3.628" x="18.291" y="12.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".05"/></filter><filter id="iqRKtve" width="4.304" height="1.768" x="17.348" y="16.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".05"/></filter><filter id="iR9dTCb" width="15.214" height="9.786" x="11.893" y="3.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3859"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3859" result="effect2_innerShadow_4002_3859"/></filter><filter id="isDi5Rc" width="2.746" height="1.371" x="21.378" y="9.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3859"/></filter><filter id="iZfWrHc" width="2.746" height="1.353" x="15.166" y="9.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3859"/></filter><filter id="iAQCRGb" width="8.191" height="7.491" x="12.108" y="4.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".25"/></filter><filter id="inGKvGe" width="7.974" height="7.235" x="19.062" y="4.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".25"/></filter><filter id="iqxXxkd" width=".894" height=".787" x="21.23" y="12.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".05"/></filter><filter id="iZKMLXE" width=".981" height="1.007" x="22.24" y="12.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".1"/></filter><filter id="iHb7CWc" width="1.093" height="1.157" x="16.989" y="12.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".1"/></filter><filter id="iHfIFNb" width="1.043" height=".796" x="16.079" y="12.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".05"/></filter><filter id="i8k7lMd" width="1.48" height="2.721" x="12.416" y="12.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".125"/></filter><filter id="iOOguHe" width="1.619" height="2.75" x="25.114" y="12.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".125"/></filter><filter id="ixmiJfb" width="2.706" height="1.235" x="15.138" y="10.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".125"/></filter><filter id="i1ky0nb" width="2.706" height="1.235" x="21.378" y="9.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".125"/></filter><filter id="ibiN6nd" width="9.217" height="12.757" x="5.842" y="12.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".75"/></filter><filter id="iukFw5c" width=".423" height="2.22" x="4.939" y="5.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".05"/></filter><filter id="ibudoTb" width=".345" height="2.572" x="6.525" y="4.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".05"/></filter><filter id="iJAAzwk" width=".509" height="1.681" x="7.971" y="5.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3859" stdDeviation=".05"/></filter><linearGradient id="iyv2Lzd" x1="6.842" x2="6.842" y1="12.546" y2="10.843" gradientUnits="userSpaceOnUse"><stop class="oeyur9bet"/><stop offset="1" class="wez3-gbsw"/></linearGradient><linearGradient id="i772blR" x1="4.686" x2="9.061" y1="12.564" y2="12.564" gradientUnits="userSpaceOnUse"><stop class="zmcsd8b9p"/><stop offset=".743" class="zdo6gqojl"/></linearGradient><linearGradient id="iNlRzPc" x1="6.956" x2="6.956" y1="11.978" y2="12.236" gradientUnits="userSpaceOnUse"><stop class="p4ezwj49r"/><stop offset="1" class="q3td6tqwm"/></linearGradient><linearGradient id="iQeLLne" x1="9.953" x2="11.909" y1="26.67" y2="20.385" gradientUnits="userSpaceOnUse"><stop class="b05_udben"/><stop offset="1" class="a91fxs_hx"/></linearGradient><linearGradient id="iD97qlc" x1="14.046" x2="13.483" y1="24.361" y2="23.299" gradientUnits="userSpaceOnUse"><stop offset=".133" class="b2wdmyb-l"/><stop offset="1" class="pmtca2xis"/></linearGradient><linearGradient id="itZuqEb" x1="17.811" x2="19.811" y1="20.627" y2="24.002" gradientUnits="userSpaceOnUse"><stop class="z-nk_efhm"/><stop offset="1" class="xbhzvqb7t"/></linearGradient><linearGradient id="i3tiu4d" x1="19.5" x2="20.51" y1="15.172" y2="15.172" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iWiTmvU" x1="18.232" x2="19.502" y1="14.988" y2="15.058" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="ipxZQ3s" x1="19.5" x2="19.5" y1="15.643" y2="16.65" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iLkDyIb" x1="19.5" x2="19.5" y1="12.987" y2="13.483" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iZ4dxxr" x1="25.839" x2="13.874" y1="7.5" y2="7.5" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iZkDaCc" x1="22.998" x2="22.628" y1="13.174" y2="13.402" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iT5kQoA" x1="17.8" x2="17.429" y1="13.174" y2="13.402" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ieVtYmC" x1="27.107" x2="25.681" y1="13.205" y2="15.777" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="i7sNsFb" x1="12.586" x2="14.31" y1="14.037" y2="13.887" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iSzNbCT" x1="7.499" x2="13.249" y1="15.283" y2="23.564" gradientUnits="userSpaceOnUse"><stop class="gokcfhb1a"/><stop offset="1" class="sq9q63bos"/></linearGradient><linearGradient id="iAaNbJd" x1="5.151" x2="5.151" y1="5.236" y2="7.182" gradientUnits="userSpaceOnUse"><stop class="a0xr95bdm"/><stop offset="1" class="y2zvm24uz"/></linearGradient><linearGradient id="i1QNrcc" x1="6.784" x2="6.811" y1="4.264" y2="6.627" gradientUnits="userSpaceOnUse"><stop class="a0xr95bdm"/><stop offset="1" class="y2zvm24uz"/></linearGradient><linearGradient id="inCrPtd" x1="8.417" x2="8.444" y1="4.49" y2="6.853" gradientUnits="userSpaceOnUse"><stop class="a0xr95bdm"/><stop offset="1" class="y2zvm24uz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-raising-hand" /></template>
<style>
.a0xr95bdm {
  stop-color: var(--svg-color--b36b00, #B36B00);
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a91fxs_hx {
  stop-color: var(--svg-color--ff4b54, #FF4B54);
  stop-opacity: 0;
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

.b05_udben {
  stop-color: var(--svg-color--ff4b54, #FF4B54);
}

.b2wdmyb-l {
  stop-color: var(--svg-color--ff611d, #FF611D);
}

.b4k1jibsk {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M15.469 10.542a3.28 3.28 0 0 1 2.055-.425a.328.328 0 1 1-.08.651a2.62 2.62 0 0 0-1.639.337a2 2 0 0 0-.108.07l-.003.003a.328.328 0 0 1-.402-.519z");
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

.bkz_cdc-o {
  stop-color: var(--svg-color--e27426, #E27426);
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bstpv-bhs {
  d: path("M20.527 21.002h.973c2.5 0 7.5 3.5 7.5 9H11v-3.5a.67.67 0 0 0-.416-.625L7.5 24.502c-2.5-1-3.5-3.5-3.5-5.198v-5.288c0-.563.425-1.014.935-1.014h4.13c.52 0 .935.461.935 1.014v3.986c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
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

.cxe48lb_z {
  d: path("M4.85 12.178c0-.11.09-.2.2-.2h3.811c.11 0 .2.09.2.2v1.714h-4.21z");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e-ldqeb8i {
  d: path("M19.5 17.616c-.6 0-1.164-.141-1.637-.388c-.162-.082-.336.1-.234.247c.395.6 1.085 1 1.871 1s1.476-.4 1.871-1c.102-.153-.072-.33-.233-.247a3.5 3.5 0 0 1-1.638.388");
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.ed7o1ee4q {
  d: path("M13.527 11.996a1.902 1.902 0 0 0 .163 3.782a92 92 0 0 1-.163-3.782");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.euzc7j3gp {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.326 12.225a1.65 1.65 0 0 1 1.601 1.251a.324.324 0 0 1-.316.403h-2.637a.272.272 0 0 1-.268-.321a1.65 1.65 0 0 1 1.62-1.333");
}

.f3m4g1bzs {
  d: path("M25.317 15.778q.119-1.887.218-3.772a1.902 1.902 0 0 1-.218 3.771");
}

.fjg5psbub {
  d: path("M17.882 13.477c0-.341-.277-.568-.352-.637l-.34.33l.21.427z");
}

.ft5dv1b6b {
  fill: none;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g5an-sbwv {
  d: path("M13.754 15.67a1.94 1.94 0 0 1-1.069-.365v1.1a2.57 2.57 0 0 0 1.585 2.387a4.8 4.8 0 0 1-.409-1.395z");
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gk2jlbbkx {
  stop-color: var(--svg-color--eaaa15, #EAAA15);
}

.gmqj_xbtp {
  d: path("M25.238 6.341c.608.21 1.153.634 1.498 1.243c.552.97.47 2.13-.125 2.986a1.84 1.84 0 0 0-.32 1.033v1.404a2.1 2.1 0 0 0-.788-.317l.092-1.898a1.713 1.713 0 0 0-1.63-1.693h-1.654a2.86 2.86 0 0 1-2.614-1.705a.785.785 0 0 0-.728-.495h-1.504c-2.181 0-3.95 1.788-3.95 3.994l.037 1.817c-.3.044-.614.144-.851.312v-1.419a1.84 1.84 0 0 0-.32-1.033a2.83 2.83 0 0 1-.17-2.89a2.77 2.77 0 0 1 1.537-1.332a3.17 3.17 0 0 0 1.636-1.312A2.75 2.75 0 0 1 18.8 3.958c.451.196.96.196 1.41 0a2.8 2.8 0 0 1 1.079-.222c.996 0 1.868.539 2.35 1.338a2.98 2.98 0 0 0 1.599 1.267");
}

.gokcfhb1a {
  stop-color: var(--svg-color--ff7636, #FF7636);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hn1aitb-c {
  cx: 16.6px;
  cy: 12.997px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.46px;
  ry: 0.233px;
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

.idrz6l3rr {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.513 10.873c.304-.218 1.061-.601 1.956-.451");
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ip469ff8c {
  stop-color: var(--svg-color--ff8045, #FF8045);
}

.j_6dos1tq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.004 12.769c.075.1-.082.223-.26.357c-.18.133-.312.227-.387.127s.009-.29.187-.424c.179-.134.385-.16.46-.06");
}

.j6lbcibwa {
  stop-color: var(--svg-color--ffcc3d, #FFCC3D);
  stop-opacity: 0;
}

.jfma4ebms {
  stop-color: var(--svg-color--ff7c1f, #FF7C1F);
  stop-opacity: 0;
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jt0cc3bxg {
  stop-color: var(--svg-color--e97e36, #E97E36);
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

.kq1evibhh {
  stop-color: var(--svg-color--e97e36, #E97E36);
  stop-opacity: 0;
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.l7xcc7bbb {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.709 10.818c-.304-.218-1.061-.601-1.956-.45");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo-gs9dac {
  d: path("M19.5 24.002c-1.268 0-2.296-.986-2.296-2.2v-2.6c0-1.215 1.028-2.2 2.296-2.2s2.296.985 2.296 2.2v2.6c0 1.214-1.028 2.2-2.296 2.2");
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

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mi59_y10o {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m18.926 13.58l-.751 2.172c-.128.447.18.894.615.894h.93c.436 0 .743-.454.615-.894l-.628-2.173c-.135-.48-.64-.48-.782 0");
}

.n09qpobxv {
  fill: var(--svg-color--000, #000);
  d: path("M21.477 13.6c0-.335.269-.603.604-.603a.602.602 0 0 1 .537.882H21.55a.55.55 0 0 1-.072-.278");
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.na42z7pyh {
  d: path("M23.02 13.462a1 1 0 0 0-.273-.547l-.307.337l.139.27z");
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nos_wub9n {
  d: path("M22.004 12.769c.075.1-.082.223-.26.357c-.18.133-.312.227-.387.127s.009-.29.187-.424c.179-.134.385-.16.46-.06");
}

.nxkajtbcb {
  d: path("M3.78 9.25c-.125-1.923-.281-2.96-.328-3.642c-.035-.512.023-1.066.711-1.19c.598-.075.883.45.906.66c-.002-.201 0-.68 0-.805c0-.211.008-.977.86-.977c.6 0 .816.587.8.863c.01-.101.023-.413.036-.707c.018-.433.251-.989.945-.976c.597.039.793.613.765.976L8.358 5.32c.024-.187.103-.664.278-1.34c.175-.674.701-.72.957-.683c.326.046.88.36.648 1.273c-.275 1.157-.462 2.645-.527 3.286c.32-.131.605-.43.957-.797l.015-.016c.36-.375.934-.332 1.172-.105c.364.234.563.937.16 1.34c-.462.424-2.128 2.404-2.957 3.394c-.229.292-.996.875-2.234.875c-2.203-.094-2.941-1.676-3.047-3.297");
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o84wv822i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m5.077 5.236l.148 1.946");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oeyur9bet {
  stop-color: var(--svg-color--c77505, #C77505);
}

.oih2nzbsq {
  stop-color: var(--svg-color--ffdc45, #FFDC45);
  stop-opacity: 0;
}

.p4ezwj49r {
  stop-color: var(--svg-color--dd6422, #DD6422);
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pfpp9kb0x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m8.342 5.408l-.234 1.406");
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmtca2xis {
  stop-color: var(--svg-color--ff611d, #FF611D);
  stop-opacity: 0;
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.ptqby1bwa {
  stop-color: var(--svg-color--eeb32a, #EEB32A);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q-_hp3b8x {
  stop-color: var(--svg-color--eaaa15, #EAAA15);
  stop-opacity: 0;
}

.q2kyq2xrt {
  stop-color: var(--svg-color--d93f13, #D93F13);
}

.q3td6tqwm {
  stop-color: var(--svg-color--dd6422, #DD6422);
  stop-opacity: 0;
}

.qqqtnz_cz {
  stop-color: var(--svg-color--d27c28, #D27C28);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzq3pc74b {
  d: path("M7.842 13.658v6.017a2 2 0 0 0 1.38 1.902l4.183 1.362");
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

.rpo29iblg {
  fill: var(--svg-color--000, #000);
  d: path("M17.523 13.6a.6.6 0 0 0-.604-.603a.602.602 0 0 0-.537.882h1.069a.6.6 0 0 0 .072-.278");
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.sq9q63bos {
  stop-color: var(--svg-color--ff7636, #FF7636);
  stop-opacity: 0;
}

.srkb94biz {
  d: path("m25.66 11.541l-.034-.746c-.012-.902-.758-1.647-1.66-1.685H22.31a2.86 2.86 0 0 1-2.51-1.488s-.124-.285-.214-.746c-.192-.985.726-1.716 1.715-1.545c1.22.211 2.685.61 3.743 1.3c2.062 1.345 1.701 3.769.616 4.91");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t-rdkjm1g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m6.733 4.26l-.07 2.297");
}

.tbc4r9bem {
  d: path("M22.081 12.546a1.055 1.055 0 0 1 1.017 1.333H21.06a1.06 1.06 0 0 1 1.021-1.333");
}

.tljjnprhh {
  stop-color: var(--svg-color--e9aa33, #E9AA33);
  stop-opacity: 0;
}

.u-d4s4bdt {
  d: path("M25.246 15.67a1.94 1.94 0 0 0 1.069-.365v1.1a2.57 2.57 0 0 1-1.585 2.387a4.8 4.8 0 0 0 .409-1.395z");
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ubkqzsjyf {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M13.547 12.777a1.13 1.13 0 0 0 .098 2.221q-.062-1.11-.098-2.22");
}

.ucms-5btk {
  fill: var(--svg-color--ff611d, #FF611D);
  d: path("M20.527 21.002h.973c2.5 0 7.5 3.5 7.5 9H11v-3.5a.67.67 0 0 0-.416-.625L7.5 24.502c-2.5-1-3.5-3.5-3.5-5.198v-5.288c0-.563.425-1.014.935-1.014h4.13c.52 0 .935.461.935 1.014v3.986c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.ueyu2dboe {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M23.912 10.671c-.207-.18-.448-.371-.813-.486c-.36-.114-.81-.144-1.433-.068a.328.328 0 0 0 .08.651c.569-.07.917-.033 1.157.042c.234.074.392.193.578.355a.328.328 0 0 0 .431-.494");
}

.uovxktaxm {
  stop-color: var(--svg-color--f2b830, #F2B830);
}

.v-7tk2b_j {
  d: path("m19.048 13.348l-.628 2.173c-.128.447.18.894.615.894h.93c.436 0 .743-.454.615-.894l-.628-2.173c-.135-.481-.763-.481-.904 0");
}

.v0q_-i93u {
  stop-color: var(--svg-color--ff8045, #FF8045);
  stop-opacity: 0;
}

.v3jqojv9j {
  stop-color: var(--svg-color--ffdc45, #FFDC45);
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

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wem6qfvha {
  cx: 16.6px;
  cy: 12.997px;
  rx: 0.46px;
  ry: 0.233px;
}

.wez3-gbsw {
  stop-color: var(--svg-color--efb234, #EFB234);
  stop-opacity: 0;
}

.wkdez3bsl {
  stop-color: var(--svg-color--f4b937, #F4B937);
}

.wogt4ot2h {
  stop-color: var(--svg-color--d93f13, #D93F13);
  stop-opacity: 0;
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wvtv-xasy {
  d: path("M13.797 17.46a4.63 4.63 0 0 0 4.593 4.026h2.23a4.63 4.63 0 0 0 4.592-4.025c.14-2.227.28-4.444.383-6.67a1.713 1.713 0 0 0-1.63-1.692h-1.654a2.86 2.86 0 0 1-2.614-1.705a.785.785 0 0 0-.728-.495h-1.504c-2.181 0-3.95 1.788-3.95 3.994c0 2.2.138 4.363.282 6.568");
}

.wwqc60d-y {
  d: path("m18.858 21.111l-7.874 5.246a.66.66 0 0 0-.4-.48L7.5 24.502c-2.5-1-3.5-3.5-3.5-5.198v-5.288c0-.563.425-1.014.935-1.014h4.13c.52 0 .935.461.935 1.014v3.986c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.xbhzvqb7t {
  stop-color: var(--svg-color--ffc436, #FFC436);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xjv40os-m {
  stop-color: var(--svg-color--ff6e45, #FF6E45);
}

.y-8a9ebxe {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.674 12.225a1.65 1.65 0 0 0-1.601 1.251a.324.324 0 0 0 .316.403h2.637a.272.272 0 0 0 .269-.321a1.656 1.656 0 0 0-1.62-1.333");
}

.y2zvm24uz {
  stop-color: var(--svg-color--edad18, #EDAD18);
}

.ya78f26qa {
  stop-color: var(--svg-color--ff7c1f, #FF7C1F);
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.yrxkt-bta {
  stop-color: var(--svg-color--ff6e45, #FF6E45);
  stop-opacity: 0;
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.z_yn3vbua {
  stop-color: var(--svg-color--ffcc3d, #FFCC3D);
}

.z-nk_efhm {
  stop-color: var(--svg-color--d16c15, #D16C15);
}

.z53-fccwe {
  d: path("M16.919 12.546a1.055 1.055 0 0 0-1.017 1.333h2.038q.037-.135.038-.278a1.06 1.06 0 0 0-1.06-1.055");
}

.z8-kq75ul {
  d: path("M19.775 7.556a3 3 0 0 1-.078-.162a.785.785 0 0 0-.728-.495h-1.504c-2.181 0-3.95 1.788-3.95 3.994v.325c-.401-.306-.907-.95-.907-1.994c0-1.267.925-1.908 1.514-2.316c.166-.115.306-.212.39-.3l.118-.123c.414-.438 1.15-1.22 2.435-1.56a6.5 6.5 0 0 1 1.93-.19c.472.021.805.43.805.902V7.54z");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.z9_rqvvaq {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.897 17.162a.26.26 0 0 0-.305.052a.24.24 0 0 0-.025.303A2.31 2.31 0 0 0 19.5 18.55c.812 0 1.524-.413 1.934-1.033a.24.24 0 0 0-.027-.306a.26.26 0 0 0-.303-.05h-.001a3.46 3.46 0 0 1-1.603.38a3.5 3.5 0 0 1-1.603-.38Z");
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zbilkeb4d {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M25.364 15.008q.07-1.125.131-2.25a1.13 1.13 0 0 1-.13 2.25");
}

.zdo6gqojl {
  stop-color: var(--svg-color--d64d18, #D64D18);
}

.zmcsd8b9p {
  stop-color: var(--svg-color--e6724b, #E6724B);
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
