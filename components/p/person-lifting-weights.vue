<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#icU7eqe)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#i8YqMjD)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#i1xUJud)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#is3gzJe)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#i2XYmZd)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#igK5sqX)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iieTJ2c)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#ivBLUee)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><g filter="url(#iXXCTEe)"><path fill="url(#iVAnGZb)" class="q1wg51bmi"/><path fill="url(#i0AhJLc)" class="q1wg51bmi"/><path fill="url(#i8igjWE)" class="q1wg51bmi"/><path fill="url(#il5AC0d)" class="q1wg51bmi"/></g><g filter="url(#iTDvMPe)"><rect fill="url(#iE3hHec)" class="uywq_y1iv"/><rect fill="url(#i1HNLPr)" class="uywq_y1iv"/></g><g filter="url(#iOAKbUd)"><path stroke="url(#ibRzype)" class="ijj045bhz"/></g><path fill="url(#iPLW49h)" class="g4offrb0h"/><path fill="url(#i6H6f0b)" class="nm-q8ebbk"/><path fill="url(#iercRpd)" class="z0ggixb3q"/><path fill="url(#iZ5j9Qc)" class="tzfcre5-h"/><circle fill="url(#iMHIuAb)" class="gknucfb8h"/><path fill="url(#ilRInSd)" class="y0nqeezxq"/><path fill="url(#iSDE3Fb)" class="l2at7otgu"/><path fill="url(#iExIOzc)" class="ufmuzl7ni"/><path fill="url(#izjM9gd)" class="rh3jx3c9i"/><circle fill="url(#i9Hs44c)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><g filter="url(#ioKyBLd)"><path fill="url(#i7nMPid)" class="em3ofwhyw"/><path fill="url(#isQKslc)" class="em3ofwhyw"/><path fill="url(#iFLqZSc)" class="em3ofwhyw"/></g><g filter="url(#igIA3me)"><path fill="url(#ii9TU6b)" class="qno0gyhtd"/><path fill="url(#iAW9NPa)" class="qno0gyhtd"/><path fill="url(#irsbW7b)" class="qno0gyhtd"/></g><g filter="url(#iFrMCTb)"><path fill="url(#iMd3cGY)" class="tphhgybtp"/><path fill="url(#iKoLy8d)" class="tphhgybtp"/></g><g filter="url(#i3XBVIe)"><path fill="url(#ipt2RNb)" class="x9t-2zb_r"/><path fill="url(#ijEmnZt)" class="x9t-2zb_r"/><path fill="url(#iqv6bwe)" class="x9t-2zb_r"/></g><g filter="url(#igquRkc)"><path fill="url(#i1fW1XY)" class="g5fg-5cgy"/><path fill="url(#iL5td6D)" class="g5fg-5cgy"/></g><path fill="url(#iUunFbd)" class="qc-du8bun"/><path fill="url(#ikekQ5c)" class="qc-du8bun"/><path fill="url(#iFj4Skc)" class="a_o5vet0d"/><g filter="url(#inm3Bwe)"><path fill="url(#iJtjM7d)" class="nk7yrvl0n"/></g><path fill="url(#iUz9ifb)" class="nk7yrvl0n"/><path fill="url(#ikFdccb)" class="nk7yrvl0n"/><path fill="url(#iiLojfe)" class="nk7yrvl0n"/><path fill="url(#ih4dDvc)" class="nk7yrvl0n"/><g filter="url(#ibi4trd)"><path class="f5lox4bfx"/></g><g filter="url(#ihQCbol)"><path fill="url(#ip7PIic)" class="zckte6bcc"/><path fill="url(#ilzTCUb)" class="zckte6bcc"/><path fill="url(#iV7FL3c)" class="zckte6bcc"/><path fill="url(#iGX9Nnd)" class="zckte6bcc"/></g><g filter="url(#i9FJ4we)"><path stroke="url(#iEMcQSc)" class="s_rzckb0l"/></g><path fill="url(#iHhPNle)" class="wvj5mi2jl"/><g filter="url(#i18dAid)"><path fill="url(#iRdXwkb)" class="ytom8j_wq"/><path fill="url(#iLNhxDd)" class="ytom8j_wq"/><path fill="url(#iIsezVb)" class="ytom8j_wq"/><path fill="url(#iDa1FDb)" class="ytom8j_wq"/><path fill="url(#ioxxHAb)" class="ytom8j_wq"/></g><g filter="url(#iDtLiBc)"><path fill="url(#ifw09md)" class="jb66oibkx"/><path fill="url(#itLBiqb)" class="jb66oibkx"/></g><g filter="url(#iQ0sd8c)"><path fill="url(#iNmGqfc)" class="xxpm0jbsg"/><path fill="url(#iVkqidd)" class="xxpm0jbsg"/><path fill="url(#iasrOqb)" class="xxpm0jbsg"/><path fill="url(#if4JXQb)" class="xxpm0jbsg"/><path fill="url(#i5si9Tb)" class="xxpm0jbsg"/></g><path class="cgqm6x3gl"/><path fill="url(#iV60Nee)" class="geo3bvbll"/><g filter="url(#i1fqX2d)"><path class="naef-0b8m"/></g><g filter="url(#iHOQxdd)"><path fill="url(#imrVfMc)" class="u6_y93pge"/><path fill="url(#iID6PAd)" class="u6_y93pge"/></g><g filter="url(#iRENGJd)"><path fill="url(#iQ3Ldac)" class="qd4tofb7u"/></g><g filter="url(#iyYV0te)"><path class="f0e_ytb-v"/></g><g filter="url(#iS445Ud)"><path fill="url(#ixKrPfb)" class="kv3enpo0a"/><path fill="url(#iIOJZDd)" class="kv3enpo0a"/></g><g filter="url(#i0JvOec)"><path fill="url(#imGINwe)" class="fzjqedceo"/></g><path class="cxjunsbyh"/><g filter="url(#irRxumb)"><path class="enws91hej"/><path fill="url(#iqAAbBD)" class="b6v5xyk4n"/></g><g filter="url(#iyJF4pe)"><path fill="url(#igB6vbb)" class="lf0invbbv"/></g><path class="iu5u8h_6y"/><path fill="url(#i4BZUvb)" class="a8sk7vbju"/><path class="rzqg4pcih"/><g filter="url(#iY1XegI)"><path fill="url(#iaJO8hb)" class="lfypr4h-x"/></g><g filter="url(#iXlzyew)"><ellipse transform="rotate(-27.914 14.823 12.942)" class="qd3_wbcgj"/><ellipse fill="url(#ihYnyuD)" transform="rotate(-27.914 14.823 12.942)" class="xjg0vf2hn"/></g><path fill="url(#im2igKe)" class="z3q89_0_y"/><path fill="url(#iU4DjKb)" class="z3q89_0_y"/><path fill="url(#ihRTPub)" class="z3q89_0_y"/><path fill="url(#idy6V8b)" class="yz156yb3d"/><path fill="url(#ib4vWyr)" class="yz156yb3d"/><g filter="url(#i1rcXjN)"><path class="xhiy2obba"/></g><g filter="url(#iiF9ute)"><path class="d82-57bxs"/></g><path class="bap9riz0k"/><g filter="url(#idGUfIb)"><path class="j63uryb7o"/></g><path class="qk-j-m1jy"/><g filter="url(#ioXZZVo)"><path class="m7yekxbzx"/></g><defs><radialGradient id="icU7eqe" cx="0" cy="0" r="1" gradientTransform="rotate(87.787 -.815 10.418)scale(4.85666 1.64346)" gradientUnits="userSpaceOnUse"><stop class="g77rtfbof"/><stop offset="1" class="x1baucbnz"/></radialGradient><radialGradient id="i1xUJud" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 10.04 7.769)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="tifd2nbhd"/><stop offset="1" class="o4u-l0lno"/></radialGradient><radialGradient id="is3gzJe" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.362 6.832)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="yyejvbcrw"/><stop offset="1" class="i1j-sacds"/></radialGradient><radialGradient id="i2XYmZd" cx="0" cy="0" r="1" gradientTransform="rotate(87.787 -1.122 2.973)scale(4.85666 1.64346)" gradientUnits="userSpaceOnUse"><stop class="g77rtfbof"/><stop offset="1" class="x1baucbnz"/></radialGradient><radialGradient id="iieTJ2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 2.305 .918)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="tifd2nbhd"/><stop offset="1" class="o4u-l0lno"/></radialGradient><radialGradient id="ivBLUee" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="yyejvbcrw"/><stop offset="1" class="i1j-sacds"/></radialGradient><radialGradient id="iVAnGZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.375 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="il5AC0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 17.938 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="iE3hHec" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 17.781 5.695)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="i1HNLPr" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 8.96 6.273)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="iPLW49h" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 3.991 3.074)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="i3etvmbtq"/><stop offset="1" class="v3dxsi25s"/></radialGradient><radialGradient id="i6H6f0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 8.863 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="bhv6r6bju"/><stop offset="1" class="zcsf4yb5o"/></radialGradient><radialGradient id="iercRpd" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.03 3.12)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="bhv6r6bju"/><stop offset="1" class="zcsf4yb5o"/></radialGradient><radialGradient id="iZ5j9Qc" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.687 3.116)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="bhv6r6bju"/><stop offset="1" class="zcsf4yb5o"/></radialGradient><radialGradient id="iMHIuAb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39453 .51953 -.51953 -.39453 10.781 6.84)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="m0lqw5bea"/><stop offset=".91" class="rdwyvqbpo"/></radialGradient><radialGradient id="ilRInSd" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 0 0 1.26563 23.836 5.852)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="vjv772cbv"/><stop offset="1" class="f3x0tmb2q"/></radialGradient><radialGradient id="iSDE3Fb" cx="0" cy="0" r="1" gradientTransform="rotate(176.697 11.828 3.28)scale(.90756 1.0035)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xot5t6pkw"/><stop offset="1" class="wjkbrmbdg"/></radialGradient><radialGradient id="iExIOzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8606 .05074 -.05742 -.97387 22.392 5.895)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="u521robxh"/><stop offset="1" class="wjkbrmbdg"/></radialGradient><radialGradient id="izjM9gd" cx="0" cy="0" r="1" gradientTransform="matrix(-.90871 .05556 -.06514 -1.06541 23.109 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="u521robxh"/><stop offset="1" class="wjkbrmbdg"/></radialGradient><radialGradient id="i9Hs44c" cx="0" cy="0" r="1" gradientTransform="rotate(37.439 -.33 .432)scale(.62972)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="tydx0uunk"/><stop offset=".91" class="vea9pibbt"/></radialGradient><radialGradient id="i7nMPid" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.313 18.758)" gradientUnits="userSpaceOnUse"><stop class="vv2_9vbpq"/><stop offset="1" class="moznfwbra"/></radialGradient><radialGradient id="isQKslc" cx="0" cy="0" r="1" gradientTransform="rotate(107.103 2.471 12.873)scale(2.4712 2.78644)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="omdmi4b-e"/><stop offset="1" class="jy0vqr-mu"/></radialGradient><radialGradient id="iFLqZSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 19.826 21.256)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="wx7ikuwun"/><stop offset="1" class="qljsz814e"/></radialGradient><radialGradient id="ii9TU6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.5 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iMd3cGY" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.294 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="ipt2RNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.074 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="ijEmnZt" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 2.773 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i1fW1XY" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.438 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iL5td6D" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.188 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="iUunFbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4184 1.78818 -2.12423 -.49702 18.66 13.5)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="hpm4jglxg"/><stop offset="1" class="gp_b-ccdq"/></radialGradient><radialGradient id="ikekQ5c" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -4.25 24.814)scale(.23879 .20285)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iFj4Skc" cx="0" cy="0" r="1" gradientTransform="matrix(-.83862 .01568 -.02558 -1.36836 13.878 14.094)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="q60difbqg"/><stop offset=".808" class="gwb5evzrz"/></radialGradient><radialGradient id="iJtjM7d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50743 0 0 -4.43561 17.347 13.048)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iUz9ifb" cx="0" cy="0" r="1" gradientTransform="matrix(-.19305 2.92666 -1.07596 -.07097 18.473 12.938)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="ikFdccb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 .88415 0 14.844 12.773)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iiLojfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.78125 1.0133 0 17.194 12.71)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="ih4dDvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.89099 -5.46217 0 16.023 12.117)" gradientUnits="userSpaceOnUse"><stop offset=".643" class="b7g7xod-m"/><stop offset="1" class="l9oxgcdaw"/></radialGradient><radialGradient id="iEMcQSc" cx="0" cy="0" r="1" gradientTransform="matrix(.1665 -.2971 .86458 .48455 15.434 15.004)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iHhPNle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.34569 1.39078 0 15.974 15.124)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iLNhxDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.74298 4.86002 0 13.492 12.29)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iIsezVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.74232 3.08705 0 18.331 12.29)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iDa1FDb" cx="0" cy="0" r="1" gradientTransform="rotate(-160.666 9.775 3.109)scale(2.08732 1.11163)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="ioxxHAb" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 .175 18.165)scale(.83003 1.92194)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="ifw09md" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.23 6.159)scale(1.94112 .54026)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="itLBiqb" cx="0" cy="0" r="1" gradientTransform="matrix(1.54353 -2.44392 2.70761 1.71007 13.395 11.781)" gradientUnits="userSpaceOnUse"><stop class="cjos7ebuw"/><stop offset=".233" class="cjtt9u3wq"/><stop offset="1" class="a5q134bqj"/></radialGradient><radialGradient id="iNmGqfc" cx="0" cy="0" r="1" gradientTransform="matrix(1.62392 .3841 -.21481 .9082 17.738 10.059)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iVkqidd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03053 -1.7764 .99068 -.57472 18.462 12.267)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iasrOqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.62705 -1.05628 .75657 -.44913 18.165 12.123)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="if4JXQb" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 8.56 6.084)scale(2.36677 2.55857)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="i5si9Tb" cx="0" cy="0" r="1" gradientTransform="rotate(107.002 5.15 11.504)scale(.19246 .87989)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="iV60Nee" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38913 -.61896 0 17.046 12.988)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iID6PAd" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.145 12.111)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iQ3Ldac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.406 27.992)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="iIOJZDd" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.729 15.316)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="imGINwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.719 28.54)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="iqAAbBD" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.659 2.366)scale(.18124 .24953)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4BZUvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38915 -.61899 0 14.954 12.988)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ihYnyuD" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.853 -.747)scale(.23675 .28458)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iU4DjKb" cx="0" cy="0" r="1" gradientTransform="matrix(.30147 1.07593 -1.02653 .28763 18.215 12.615)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="ihRTPub" cx="0" cy="0" r="1" gradientTransform="matrix(.37784 -.51853 .43463 .3167 18.388 12.877)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="ib4vWyr" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.528 11.878)scale(1.01522 .99805)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="iXXCTEe" width="9.5" height="4.284" x="11.172" y="21.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/></filter><filter id="iTDvMPe" width="27.875" height="1.225" x="2.063" y="5.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/></filter><filter id="iOAKbUd" width="27.781" height=".75" x="2.023" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".125"/></filter><filter id="ioKyBLd" width="10.708" height="10.353" x="10.803" y="11.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.396078 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/></filter><filter id="igIA3me" width="1.93" height="8.989" x="5.039" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/></filter><filter id="iFrMCTb" width="1.93" height="8.989" x="24.992" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/></filter><filter id="i3XBVIe" width="1.93" height="5.973" x="3.109" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/></filter><filter id="igquRkc" width="1.93" height="5.973" x="26.922" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/></filter><filter id="inm3Bwe" width="5.402" height="6.119" x="13.572" y="10.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23305" result="effect2_innerShadow_3987_23305"/></filter><filter id="ibi4trd" width="2.9" height="3.391" x="14.45" y="12.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".5"/></filter><filter id="ihQCbol" width="1.1" height="1.591" x="15.45" y="12.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".05"/></filter><filter id="i9FJ4we" width="2.044" height="1.015" x="14.953" y="14.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".05"/></filter><filter id="i18dAid" width="6.174" height="4.268" x="12.913" y="8.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.698039 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.584314 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23305" result="effect2_innerShadow_3987_23305"/></filter><filter id="iDtLiBc" width="3.118" height="2.818" x="13.103" y="9.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".05"/></filter><filter id="iQ0sd8c" width="2.933" height="2.67" x="16.024" y="9.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".05"/></filter><filter id="i1fqX2d" width="3.719" height="6.065" x="8.891" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.654902 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.631373 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23305" result="effect2_innerShadow_3987_23305"/></filter><filter id="iHOQxdd" width="4.477" height="4.023" x="8.516" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/></filter><filter id="iRENGJd" width="4.833" height="2.114" x="7.039" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/></filter><filter id="iyYV0te" width="3.719" height="5.564" x="19.922" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.654902 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.576471 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23305" result="effect2_innerShadow_3987_23305"/></filter><filter id="iS445Ud" width="4.477" height="4.023" x="19.539" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/></filter><filter id="i0JvOec" width="4.833" height="2.114" x="20.159" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23305"/></filter><filter id="irRxumb" width=".481" height=".438" x="16.642" y="12.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".05"/></filter><filter id="iyJF4pe" width=".635" height=".646" x="16.993" y="12.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".1"/></filter><filter id="iY1XegI" width=".481" height=".506" x="14.962" y="12.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".05"/></filter><filter id="iXlzyew" width=".542" height=".442" x="14.552" y="12.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".05"/></filter><filter id="i1rcXjN" width=".898" height="1.401" x="12.977" y="12.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".125"/></filter><filter id="iiF9ute" width=".954" height="1.413" x="18.13" y="12.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".125"/></filter><filter id="idGUfIb" width="1.009" height=".372" x="16.764" y="11.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".025"/></filter><filter id="ioXZZVo" width="1.009" height=".372" x="14.292" y="11.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23305" stdDeviation=".025"/></filter><linearGradient id="i8YqMjD" x1="7.163" x2="8.284" y1="7.95" y2="8.096" gradientUnits="userSpaceOnUse"><stop offset=".136" class="rysyofyzl"/><stop offset="1" class="d85j9ed1i"/></linearGradient><linearGradient id="igK5sqX" x1="-.572" x2=".549" y1="1.099" y2="1.245" gradientUnits="userSpaceOnUse"><stop offset=".136" class="rysyofyzl"/><stop offset="1" class="d85j9ed1i"/></linearGradient><linearGradient id="i0AhJLc" x1="20.313" x2="17.781" y1="25.258" y2="24.82" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="i8igjWE" x1="11.625" x2="14.438" y1="25.352" y2="24.258" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="ibRzype" x1="2.398" x2="29.867" y1="7.406" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="iAW9NPa" x1="5.039" x2="6.531" y1="7.477" y2="7.477" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="irsbW7b" x1="5.039" x2="5.313" y1="7.348" y2="7.348" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="iKoLy8d" x1="24.992" x2="26.188" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iqv6bwe" x1="2.958" x2="3.452" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="ip7PIic" x1="16" x2="16.41" y1="13.807" y2="13.807" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="ilzTCUb" x1="15.486" x2="16.001" y1="13.733" y2="13.761" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iV7FL3c" x1="16" x2="16" y1="13.999" y2="14.407" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iGX9Nnd" x1="16" x2="16" y1="12.921" y2="13.122" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iRdXwkb" x1="18.572" x2="13.717" y1="10.332" y2="10.332" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="imrVfMc" x1="12.492" x2="8.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="ixKrPfb" x1="19.539" x2="23.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="igB6vbb" x1="17.419" x2="17.269" y1="13.013" y2="13.106" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaJO8hb" x1="15.31" x2="15.159" y1="13.013" y2="13.106" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="im2igKe" x1="19.087" x2="18.508" y1="12.647" y2="13.691" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="idy6V8b" x1="13.194" x2="13.894" y1="12.985" y2="12.924" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-lifting-weights" /></template>
<style>
.a_o5vet0d {
  d: path("M13.669 13.648a.8.8 0 0 1-.434-.148v.446c0 .428.255.81.643.969a2 2 0 0 1-.166-.566z");
}

.a5q134bqj {
  stop-color: var(--svg-color--db8823, #DB8823);
  stop-opacity: 0;
}

.a8sk7vbju {
  d: path("M14.953 12.759a.428.428 0 0 0-.413.54h.827a.43.43 0 0 0-.414-.54");
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
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

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.b6v5xyk4n {
  d: path("M17.016 12.85c.03.04-.034.09-.106.144s-.126.092-.157.052c-.03-.041.004-.118.076-.172c.073-.054.156-.065.187-.024");
}

.b7g7xod-m {
  stop-color: var(--svg-color--ffb72a, #FFB72A);
  stop-opacity: 0;
}

.bap9riz0k {
  stroke: var(--svg-color--bf4540, #BF4540);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.864 12.16a1.3 1.3 0 0 1 .809-.164");
}

.bhv6r6bju {
  stop-color: var(--svg-color--ffd83f, #FFD83F);
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

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.cgqm6x3gl {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.147 12.629a.67.67 0 0 1 .65.507a.13.13 0 0 1-.128.164h-1.07a.11.11 0 0 1-.11-.13a.67.67 0 0 1 .658-.541");
}

.cjos7ebuw {
  stop-color: var(--svg-color--c46d13, #C46D13);
}

.cjtt9u3wq {
  stop-color: var(--svg-color--db8823, #DB8823);
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

.cxjunsbyh {
  fill: var(--svg-color--000, #000);
  d: path("M16.802 13.187c0-.136.11-.245.245-.245a.244.244 0 0 1 .218.358h-.434a.2.2 0 0 1-.029-.113");
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.d82-57bxs {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M18.38 13.379q.029-.457.053-.913a.458.458 0 0 1-.053.913");
}

.d85j9ed1i {
  stop-color: var(--svg-color--af7222, #AF7222);
  stop-opacity: 0;
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e4y-1lbum {
  r: 0.398px;
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.em3ofwhyw {
  d: path("m10.948 13.026l2.396-1.12l2.578 3.399l2.469-3.563l2.729 1.318a.25.25 0 0 1 .113.34l-1.194 2.303a1 1 0 0 0-.112.482l.12 5.76h-7.985v-5.788a1 1 0 0 0-.098-.433l-1.136-2.363a.25.25 0 0 1 .12-.335");
}

.enws91hej {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.016 12.85c.03.04-.034.09-.106.144s-.126.092-.157.052c-.03-.041.004-.118.076-.172c.073-.054.156-.065.187-.024");
}

.f0e_ytb-v {
  fill: var(--svg-color--ffdf41, #FFDF41);
  d: path("m22.668 28.448l.473-5.464h-3.22l.479 5.464z");
}

.f3x0tmb2q {
  stop-color: var(--svg-color--ad8518, #AD8518);
}

.f5lox4bfx {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.767 13.161l-.305.882c-.052.181.073.363.25.363h.377c.177 0 .302-.185.25-.363l-.255-.882c-.055-.195-.26-.195-.317 0");
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.ft5dv1b6b {
  fill: none;
}

.fzjqedceo {
  d: path("M24.992 29.53v.376H20.36v-1.914h2.352c.383.377 1.215.73 1.836.941c.398.169.445.442.445.597");
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g4offrb0h {
  d: path("M7.5 5.71a.399.399 0 1 1 .797-.034v.46a.38.38 0 0 1-.758.032z");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g5fg-5cgy {
  d: path("M28.852 4.402a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.g77rtfbof {
  stop-color: var(--svg-color--ffdf3f, #FFDF3F);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.geo3bvbll {
  d: path("M17.047 12.759a.428.428 0 0 1 .413.54h-.827a.43.43 0 0 1 .414-.54");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gknucfb8h {
  cx: 10.586px;
  cy: 7px;
  r: 0.398px;
}

.gp_b-ccdq {
  stop-color: var(--svg-color--f38e15, #F38E15);
}

.gwb5evzrz {
  stop-color: var(--svg-color--d25a0b, #D25A0B);
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hpm4jglxg {
  stop-color: var(--svg-color--ffb124, #FFB124);
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.i1j-sacds {
  stop-color: var(--svg-color--efad2e, #EFAD2E);
  stop-opacity: 0;
}

.i3etvmbtq {
  stop-color: var(--svg-color--ffc935, #FFC935);
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
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

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ijj045bhz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.398 6.406H29.43");
}

.iu5u8h_6y {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.853 12.629a.67.67 0 0 0-.65.507a.13.13 0 0 0 .129.164h1.07a.11.11 0 0 0 .109-.13a.67.67 0 0 0-.658-.541");
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.j63uryb7o {
  stroke: var(--svg-color--c25e51, #C25E51);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.864 12.16a1.3 1.3 0 0 1 .809-.164");
}

.jb66oibkx {
  d: path("m16.112 10.646l-.032-.066a.32.32 0 0 0-.295-.2h-.61c-.886 0-1.604.725-1.604 1.62v.133c-.162-.124-.368-.386-.368-.81c0-.514.375-.774.615-.94a1 1 0 0 0 .158-.121l.048-.05c.168-.178.466-.495.988-.633q.152-.04.302-.059c.469-.06.808.357.808.83v.29z");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.jy0vqr-mu {
  stop-color: var(--svg-color--ff6129, #FF6129);
  stop-opacity: 0;
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

.kv3enpo0a {
  d: path("M23.516 21.066a1.988 1.988 0 0 0-3.977 0v1.686c0 .193.157.35.35.35h3.277a.35.35 0 0 0 .35-.35z");
}

.l097mcblv {
  stop-color: var(--svg-color--433f49, #433F49);
}

.l2at7otgu {
  d: path("M23.823 5.627a.422.422 0 1 0-.843-.033v.584a.4.4 0 0 0 .798.031z");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.l9oxgcdaw {
  stop-color: var(--svg-color--d37a1c, #D37A1C);
}

.lf0invbbv {
  d: path("M17.429 13.13a.4.4 0 0 0-.111-.221l-.125.136l.056.11z");
}

.lfypr4h-x {
  d: path("M15.343 13.136c0-.138-.112-.23-.143-.258l-.138.134l.085.173z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.m0lqw5bea {
  stop-color: var(--svg-color--ffd741, #FFD741);
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.m7yekxbzx {
  stroke: var(--svg-color--c25e51, #C25E51);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.2 12.16a1.3 1.3 0 0 0-.808-.164");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.moznfwbra {
  stop-color: var(--svg-color--ff6621, #FF6621);
}

.naef-0b8m {
  fill: var(--svg-color--ffdf41, #FFDF41);
  d: path("m9.404 28.878l-.513-5.894h3.218l-.533 5.966z");
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nk7yrvl0n {
  d: path("M13.686 14.374c.123.937.92 1.634 1.864 1.634h.904c.944 0 1.74-.697 1.864-1.634c.057-.903.113-1.803.155-2.706a.695.695 0 0 0-.66-.687h-.672c-.458 0-.873-.27-1.061-.692a.32.32 0 0 0-.295-.2h-.61c-.886 0-1.604.725-1.604 1.62c0 .893.056 1.77.115 2.665");
}

.nm-q8ebbk {
  d: path("M8.16 5.627a.422.422 0 1 1 .844-.033v.584a.4.4 0 0 1-.798.031z");
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o4u-l0lno {
  stop-color: var(--svg-color--eca42a, #ECA42A);
  stop-opacity: 0;
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omdmi4b-e {
  stop-color: var(--svg-color--e5471c, #E5471C);
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.psru50bbi {
  d: path("M7.735 6.851h2.46v7.269h-2.46z");
}

.pty90zojz {
  stop-color: var(--svg-color--7b7784, #7B7784);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q-vr2ac-v {
  stop-color: var(--svg-color--5c447a, #5C447A);
}

.q1wg51bmi {
  d: path("M16 25.93c-2.363 0-4.203-.72-4.828-1.078v-2.907h9.5v3.016c-.573.323-2.31.969-4.672.969");
}

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.q60difbqg {
  stop-color: var(--svg-color--dd781d, #DD781D);
}

.qc-du8bun {
  d: path("M18.332 13.648a.8.8 0 0 0 .433-.148v.446c0 .428-.255.81-.643.969q.123-.262.166-.566z");
}

.qd3_wbcgj {
  cx: 14.823px;
  cy: 12.942px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.187px;
  ry: 0.094px;
}

.qd4tofb7u {
  d: path("M7.04 29.53v.376h4.632v-1.914H9.32c-.383.377-1.215.73-1.836.941c-.398.169-.445.442-.445.597");
}

.qk-j-m1jy {
  stroke: var(--svg-color--bf4540, #BF4540);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.2 12.16a1.3 1.3 0 0 0-.808-.164");
}

.qljsz814e {
  stop-color: var(--svg-color--ff8d41, #FF8D41);
  stop-opacity: 0;
}

.qno0gyhtd {
  d: path("M5.04 2.894a.8.8 0 0 1 .8-.8h.329a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
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

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rdwyvqbpo {
  stop-color: var(--svg-color--d69025, #D69025);
}

.rh3jx3c9i {
  d: path("M23.108 5.588a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.015z");
}

.rysyofyzl {
  stop-color: var(--svg-color--825426, #825426);
}

.rzqg4pcih {
  fill: var(--svg-color--000, #000);
  d: path("M15.198 13.187a.244.244 0 0 0-.246-.245a.244.244 0 0 0-.217.358h.433a.24.24 0 0 0 .03-.113");
}

.s_rzckb0l {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.345 14.592c.18.094.398.149.63.149c.234 0 .448-.055.63-.15a.15.15 0 0 1 .175.03a.14.14 0 0 1 .016.179m-1.451-.209l1.389.167m-1.39-.166a.15.15 0 0 0-.176.03a.14.14 0 0 0-.015.178m.192-.209l-.13.167m1.581.042l-.062-.042m.062.042l-.062-.042m.062.042a.98.98 0 0 1-.822.439a.98.98 0 0 1-.821-.439m1.58-.042a.91.91 0 0 1-.759.406a.91.91 0 0 1-.759-.406m-.062.042v.001l.062-.043m-.062.042l.062-.042");
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.tifd2nbhd {
  stop-color: var(--svg-color--ba760f, #BA760F);
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tphhgybtp {
  d: path("M26.922 2.894a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.ty2qe1a3m {
  stop-color: var(--svg-color--97959c, #97959C);
}

.tydx0uunk {
  stop-color: var(--svg-color--f2b927, #F2B927);
}

.tzfcre5-h {
  d: path("M8.876 5.588a.424.424 0 1 1 .847-.016v.661a.411.411 0 0 1-.823.015z");
}

.u-rrnxf4y {
  stop-color: var(--svg-color--51435f, #51435F);
  stop-opacity: 0;
}

.u521robxh {
  stop-color: var(--svg-color--fdc632, #FDC632);
}

.u6_y93pge {
  d: path("M8.516 21.066a1.988 1.988 0 1 1 3.976 0v1.686a.35.35 0 0 1-.35.35H8.866a.35.35 0 0 1-.35-.35z");
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ufmuzl7ni {
  d: path("M22.392 5.626a.401.401 0 1 0-.803-.014v.575a.391.391 0 0 0 .783.013z");
}

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.up_0b0b8w {
  stop-color: var(--svg-color--8d8c90, #8D8C90);
}

.utuf8geyx {
  stop-color: var(--svg-color--cabed2, #CABED2);
  stop-opacity: 0;
}

.uywq_y1iv {
  width: 27.875px;
  height: 1.025px;
  x: 2.063px;
  y: 5.975px;
  rx: 0.2px;
}

.v3dxsi25s {
  stop-color: var(--svg-color--ae7a16, #AE7A16);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vea9pibbt {
  stop-color: var(--svg-color--cc8e21, #CC8E21);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vjv772cbv {
  stop-color: var(--svg-color--e1a82d, #E1A82D);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.vv2_9vbpq {
  stop-color: var(--svg-color--ff9347, #FF9347);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wjkbrmbdg {
  stop-color: var(--svg-color--d08d1f, #D08D1F);
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wvj5mi2jl {
  d: path("M15.974 14.816a1.44 1.44 0 0 1-.664-.158c-.066-.033-.136.04-.095.1c.16.244.44.406.76.406a.91.91 0 0 0 .759-.406c.041-.062-.03-.133-.095-.1c-.192.1-.419.158-.665.158");
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wx7ikuwun {
  stop-color: var(--svg-color--c04203, #C04203);
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.x1baucbnz {
  stop-color: var(--svg-color--eba32a, #EBA32A);
}

.x9t-2zb_r {
  d: path("M3.11 4.402a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.xhiy2obba {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M13.584 12.474a.458.458 0 0 0 .04.901q-.025-.45-.04-.901");
}

.xjg0vf2hn {
  cx: 14.823px;
  cy: 12.942px;
  rx: 0.187px;
  ry: 0.094px;
}

.xot5t6pkw {
  stop-color: var(--svg-color--e9b430, #E9B430);
}

.xxpm0jbsg {
  d: path("m18.502 12.267l-.014-.303c-.005-.366.067-.683-.674-.683h-.671c-.427 0-.816-.233-1.02-.604c0 0 .346-.998.92-.869c.418.095.866.243 1.21.467c.836.545.69 1.529.25 1.992");
}

.y0nqeezxq {
  d: path("M24.483 5.71a.399.399 0 1 0-.796-.034v.46a.38.38 0 0 0 .758.032z");
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.ytom8j_wq {
  d: path("M18.328 9.862a1.137 1.137 0 0 1 .557 1.716a.75.75 0 0 0-.13.42v.569a.8.8 0 0 0-.32-.129l.038-.77c-.005-.368-.295-.371-.661-.387h-.672c-.457 0-.872-.27-1.06-.692a.32.32 0 0 0-.295-.2h-.61c-.886 0-1.604.425-1.604 1.32l.015.737a.8.8 0 0 0-.345.127v-.576a.75.75 0 0 0-.13-.42a1.15 1.15 0 0 1-.069-1.172c.14-.265.367-.45.624-.54c.274-.098.508-.283.663-.533a1.115 1.115 0 0 1 1.387-.437c.183.08.39.08.572 0a1.115 1.115 0 0 1 1.391.453c.148.244.38.421.65.514");
}

.yyejvbcrw {
  stop-color: var(--svg-color--d48a23, #D48A23);
}

.yz156yb3d {
  d: path("M13.576 12.157a.772.772 0 0 0 .066 1.534a37 37 0 0 1-.066-1.534");
}

.z0ggixb3q {
  d: path("M9.592 5.626a.401.401 0 1 1 .803-.014v.575a.391.391 0 0 1-.783.013z");
}

.z3q89_0_y {
  d: path("M18.36 13.691q.049-.765.09-1.53a.772.772 0 0 1-.09 1.53");
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zckte6bcc {
  d: path("m15.817 13.067l-.255.882c-.052.181.072.363.25.363h.377c.177 0 .301-.184.25-.363l-.256-.882a.188.188 0 0 0-.366 0");
}

.zcsf4yb5o {
  stop-color: var(--svg-color--e0a20c, #E0A20C);
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
