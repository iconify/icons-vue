<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i6JQJ2d)" class="n8aj_hshk"/><path fill="url(#iTZBYxB)" class="n8aj_hshk"/><path fill="url(#iNoxQ2b)" class="n8aj_hshk"/><path fill="url(#iYAuMcc)" class="n8aj_hshk"/><path fill="url(#iYEFWyc)" class="n8aj_hshk"/><path fill="url(#iixjPwc)" class="n8aj_hshk"/><path fill="url(#iKVf9Xb)" class="n8aj_hshk"/><path fill="url(#iTLlvfb)" class="n8aj_hshk"/><path fill="url(#ibNKrRc)" class="n8aj_hshk"/><path fill="url(#iqLhPRb)" class="b-4p19ayv"/><path fill="url(#ignCB0b)" clip-rule="evenodd" class="shsqtoboh"/><path fill="url(#i8bvvzy)" clip-rule="evenodd" class="shsqtoboh"/><path fill="url(#iJspkGb)" clip-rule="evenodd" class="bdzfi6bsx"/><path fill="url(#ilaPspe)" clip-rule="evenodd" class="bdzfi6bsx"/><path fill="url(#i8T6pMd)" clip-rule="evenodd" class="meaaiev1f"/><path fill="url(#iGEnk7i)" clip-rule="evenodd" class="meaaiev1f"/><path fill="url(#i4nSAXb)" clip-rule="evenodd" class="meaaiev1f"/><path fill="url(#iSsfxPd)" clip-rule="evenodd" class="meaaiev1f"/><path fill="url(#iKM2BFe)" clip-rule="evenodd" class="meaaiev1f"/><path fill="url(#ivHjFtd)" clip-rule="evenodd" class="meaaiev1f"/><path fill="url(#i4HwPOc)" clip-rule="evenodd" class="meaaiev1f"/><path fill="url(#iPBFSdd)" clip-rule="evenodd" class="d7qzr7bxc"/><path fill="url(#isZRi5f)" clip-rule="evenodd" class="d7qzr7bxc"/><path fill="url(#iMKMghb)" clip-rule="evenodd" class="d7qzr7bxc"/><path fill="url(#iZ8G4pp)" clip-rule="evenodd" class="d7qzr7bxc"/><path fill="url(#iRdmRve)" clip-rule="evenodd" class="d7qzr7bxc"/><path fill="url(#idB28Wc)" clip-rule="evenodd" class="d7qzr7bxc"/><path fill="url(#iSmuuGu)" clip-rule="evenodd" class="d7qzr7bxc"/><path fill="url(#iNjRMkb)" clip-rule="evenodd" class="zc6_-8ssr"/><path fill="url(#iKWU05c)" clip-rule="evenodd" class="zc6_-8ssr"/><path fill="url(#iOGbYcU)" clip-rule="evenodd" class="j8u4ivbhv"/><path fill="url(#i0sXMyc)" clip-rule="evenodd" class="j8u4ivbhv"/><path clip-rule="evenodd" class="kem5zbbfn"/><path fill="url(#ihmcUrc)" clip-rule="evenodd" class="j20w3r7rl"/><path fill="url(#ihXiOIc)" clip-rule="evenodd" class="ipe7dgnyt"/><path fill="url(#iyKhkIe)" clip-rule="evenodd" class="ipe7dgnyt"/><path fill="url(#idMUd0c)" clip-rule="evenodd" class="ipe7dgnyt"/><path fill="url(#i8IXKXd)" clip-rule="evenodd" class="ipe7dgnyt"/><path fill="url(#ix5qIud)" clip-rule="evenodd" class="ipe7dgnyt"/><path fill="url(#ifJxlae)" clip-rule="evenodd" class="ipe7dgnyt"/><path fill="url(#ipusERb)" clip-rule="evenodd" class="ipe7dgnyt"/><path fill="url(#iGOxIci)" clip-rule="evenodd" class="m3k5m890u"/><path fill="url(#ifwZAni)" clip-rule="evenodd" class="xwlc_9lhs"/><path fill="url(#imBZdmc)" clip-rule="evenodd" class="xwlc_9lhs"/><path fill="url(#iSMKcBb)" clip-rule="evenodd" class="xwlc_9lhs"/><path fill="url(#iGKX3Ec)" clip-rule="evenodd" class="rx1_7okpd"/><path fill="url(#igrw9tb)" clip-rule="evenodd" class="rx1_7okpd"/><path fill="url(#iPrcHse)" clip-rule="evenodd" class="rx1_7okpd"/><path fill="url(#irEE6Sc)" clip-rule="evenodd" class="wqb8ysb6u"/><path fill="url(#ioaSVye)" clip-rule="evenodd" class="rx1_7okpd"/><path fill="url(#ii2ffMe)" clip-rule="evenodd" class="rx1_7okpd"/><path fill="url(#iNV1c0d)" clip-rule="evenodd" class="rx1_7okpd"/><path fill="url(#iSXavIe)" clip-rule="evenodd" class="hnqm-cc4o"/><path fill="url(#iT9zPNb)" clip-rule="evenodd" class="hnqm-cc4o"/><path fill="url(#iTCc3gb)" clip-rule="evenodd" class="hnqm-cc4o"/><path fill="url(#irJTCKd)" clip-rule="evenodd" class="zj_ouqbux"/><path fill="url(#irdL8Sm)" clip-rule="evenodd" class="hnqm-cc4o"/><path fill="url(#iHBgCDe)" clip-rule="evenodd" class="hnqm-cc4o"/><path fill="url(#icjFNnz)" clip-rule="evenodd" class="hnqm-cc4o"/><path fill="url(#iN3PMFb)" clip-rule="evenodd" class="racfucc-y"/><path fill="url(#iKWU05c)" clip-rule="evenodd" class="racfucc-y"/><path clip-rule="evenodd" class="dpkfnkbyb"/><path fill="url(#ivz7ltb)" clip-rule="evenodd" class="btd2pfthl"/><path fill="url(#ixAAqLB)" clip-rule="evenodd" class="gxisrlbso"/><path fill="url(#iWX7rDi)" clip-rule="evenodd" class="gxisrlbso"/><path fill="url(#iZgcegc)" clip-rule="evenodd" class="gxisrlbso"/><path fill="url(#iMryMFb)" clip-rule="evenodd" class="gxisrlbso"/><path fill="url(#i5mLrHd)" clip-rule="evenodd" class="gxisrlbso"/><path fill="url(#i9ygIpd)" clip-rule="evenodd" class="uekfm8bvw"/><path fill="url(#iWIs75V)" clip-rule="evenodd" class="stwh_5b1l"/><path fill="url(#i27qzHb)" clip-rule="evenodd" class="kiuexrbol"/><path fill="url(#iYeiXLm)" clip-rule="evenodd" class="kiuexrbol"/><path fill="url(#iI041kc)" clip-rule="evenodd" class="kiuexrbol"/><path fill="url(#iY8lqSd)" clip-rule="evenodd" class="kiuexrbol"/><path fill="url(#ilt5k2d)" clip-rule="evenodd" class="kiuexrbol"/><path fill="url(#iGIy4Tb)" class="e6_6_rbmq"/><path fill="url(#iSHWDYb)" class="k7ub3vbdl"/><defs><linearGradient id="i6JQJ2d" x1="8.336" x2="6.517" y1="17.619" y2="24.526" gradientUnits="userSpaceOnUse"><stop class="hxg69ubid"/><stop offset="1" class="zgp-phxqx"/></linearGradient><linearGradient id="iTZBYxB" x1="6.875" x2="6.875" y1="24.565" y2="25.594" gradientUnits="userSpaceOnUse"><stop class="fcmawhgup"/><stop offset=".4" class="gh40ckx_b"/><stop offset="1" class="gc4slbvhn"/></linearGradient><linearGradient id="iNoxQ2b" x1="6.875" x2="6.875" y1="26.566" y2="27.502" gradientUnits="userSpaceOnUse"><stop class="fcmawhgup"/><stop offset=".4" class="gh40ckx_b"/><stop offset="1" class="gc4slbvhn"/></linearGradient><linearGradient id="iYAuMcc" x1="6.875" x2="6.875" y1="21.424" y2="22.675" gradientUnits="userSpaceOnUse"><stop class="q442f7cej"/><stop offset=".425" class="g1vbzac3k"/><stop offset="1" class="q442f7cej"/></linearGradient><linearGradient id="iYEFWyc" x1="6.875" x2="6.875" y1="19.663" y2="20.633" gradientUnits="userSpaceOnUse"><stop class="q442f7cej"/><stop offset=".415" class="mjl8vs3xo"/><stop offset="1" class="q442f7cej"/></linearGradient><linearGradient id="iixjPwc" x1="6.875" x2="6.875" y1="16.556" y2="17.548" gradientUnits="userSpaceOnUse"><stop class="q442f7cej"/><stop offset=".415" class="hmqokvbzv"/><stop offset="1" class="q442f7cej"/></linearGradient><linearGradient id="iKVf9Xb" x1="6.07" x2="6.07" y1="14.724" y2="15.551" gradientUnits="userSpaceOnUse"><stop class="q442f7cej"/><stop offset=".415" class="hmqokvbzv"/><stop offset="1" class="q442f7cej"/></linearGradient><linearGradient id="iTLlvfb" x1="10.694" x2="8.764" y1="24.138" y2="24.138" gradientUnits="userSpaceOnUse"><stop class="d3k_-dbrm"/><stop offset=".513" class="d3k_-dbrm"/><stop offset="1" class="n2uiqhbik"/></linearGradient><linearGradient id="ibNKrRc" x1="9.739" x2="11.434" y1="21.301" y2="21.301" gradientUnits="userSpaceOnUse"><stop offset=".521" class="gb2ozeb2s"/><stop offset=".727" class="fo31sswjx"/><stop offset="1" class="kyr-5xbts"/></linearGradient><linearGradient id="iqLhPRb" x1="18.309" x2="18.309" y1="10.008" y2="30" gradientUnits="userSpaceOnUse"><stop class="kelsrsb5y"/><stop offset=".047" class="gb3h6t4sp"/><stop offset=".241" class="gb3h6t4sp"/><stop offset=".444" class="pzjnu0b9e"/><stop offset=".456" class="smh0gzbmq"/><stop offset=".482" class="qbpm-6b2v"/><stop offset=".522" class="xxue105dr"/><stop offset=".593" class="xxue105dr"/><stop offset=".791" class="l2_7b7baf"/></linearGradient><linearGradient id="ignCB0b" x1="21.402" x2="16.686" y1="13.209" y2="15.227" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></linearGradient><linearGradient id="i8bvvzy" x1="18.582" x2="14.377" y1="7.448" y2="11.046" gradientUnits="userSpaceOnUse"><stop/><stop offset="1" class="k05n1gbkm"/></linearGradient><linearGradient id="i8T6pMd" x1="2.424" x2="3.888" y1="7.726" y2="7.726" gradientUnits="userSpaceOnUse"><stop class="eju9i5idu"/><stop offset="1" class="qnb9ftkop"/></linearGradient><linearGradient id="iGEnk7i" x1="2" x2="2.328" y1="7.281" y2="7.281" gradientUnits="userSpaceOnUse"><stop class="ztlaxabxa"/><stop offset="1" class="vq65mp4ee"/></linearGradient><linearGradient id="i4nSAXb" x1="3.919" x2="3.032" y1="7.272" y2="7.281" gradientUnits="userSpaceOnUse"><stop class="n3pn47jlk"/><stop offset=".209" class="glb8v4bxi"/><stop offset="1" class="n3pn47jlk"/></linearGradient><linearGradient id="iSsfxPd" x1="2.227" x2="3.119" y1="7.43" y2="7.43" gradientUnits="userSpaceOnUse"><stop class="hqmw6ibqw"/><stop offset=".408" class="yl8d5_b_g"/><stop offset=".606" class="yl8d5_b_g"/><stop offset="1" class="hqmw6ibqw"/></linearGradient><linearGradient id="iKM2BFe" x1="5.604" x2="7.47" y1="7.726" y2="7.726" gradientUnits="userSpaceOnUse"><stop class="u8m4tviwt"/><stop offset=".286" class="eju9i5idu"/><stop offset=".544" class="nyxyulb7w"/><stop offset="1" class="qnb9ftkop"/></linearGradient><linearGradient id="ivHjFtd" x1="5.701" x2="6.272" y1="7.281" y2="7.281" gradientUnits="userSpaceOnUse"><stop class="vq65mp4ee"/><stop offset=".345" class="mzkehobnl"/><stop offset="1" class="vq65mp4ee"/></linearGradient><linearGradient id="i4HwPOc" x1="6.311" x2="7.763" y1="7.43" y2="7.429" gradientUnits="userSpaceOnUse"><stop class="hqmw6ibqw"/><stop offset=".357" class="gaumlhb_z"/><stop offset=".513" class="px8--zbuq"/><stop offset=".877" class="hqmw6ibqw"/></linearGradient><linearGradient id="iPBFSdd" x1="8.588" x2="10.052" y1="7.782" y2="7.782" gradientUnits="userSpaceOnUse"><stop class="eju9i5idu"/><stop offset="1" class="qnb9ftkop"/></linearGradient><linearGradient id="isZRi5f" x1="8.164" x2="8.492" y1="7.317" y2="7.317" gradientUnits="userSpaceOnUse"><stop class="ztlaxabxa"/><stop offset="1" class="vq65mp4ee"/></linearGradient><linearGradient id="iMKMghb" x1="10.083" x2="9.196" y1="7.308" y2="7.316" gradientUnits="userSpaceOnUse"><stop class="n3pn47jlk"/><stop offset=".209" class="glb8v4bxi"/><stop offset="1" class="n3pn47jlk"/></linearGradient><linearGradient id="iZ8G4pp" x1="8.39" x2="9.283" y1="7.473" y2="7.473" gradientUnits="userSpaceOnUse"><stop class="hqmw6ibqw"/><stop offset=".408" class="yl8d5_b_g"/><stop offset=".606" class="yl8d5_b_g"/><stop offset="1" class="hqmw6ibqw"/></linearGradient><linearGradient id="iRdmRve" x1="11.768" x2="13.634" y1="7.782" y2="7.782" gradientUnits="userSpaceOnUse"><stop class="u8m4tviwt"/><stop offset=".286" class="eju9i5idu"/><stop offset=".544" class="nyxyulb7w"/><stop offset="1" class="qnb9ftkop"/></linearGradient><linearGradient id="idB28Wc" x1="11.798" x2="12.516" y1="7.317" y2="7.317" gradientUnits="userSpaceOnUse"><stop class="vq65mp4ee"/><stop offset=".291" class="crgsm-d3w"/><stop offset="1" class="y2wj3r46h"/></linearGradient><linearGradient id="iSmuuGu" x1="12.475" x2="13.927" y1="7.473" y2="7.472" gradientUnits="userSpaceOnUse"><stop class="hqmw6ibqw"/><stop offset=".357" class="ih_s3nbjx"/><stop offset=".513" class="zuz9txb9k"/><stop offset=".877" class="hqmw6ibqw"/></linearGradient><linearGradient id="iNjRMkb" x1="25.888" x2="27.484" y1="25.085" y2="24.396" gradientUnits="userSpaceOnUse"><stop class="sqzotjq3d"/><stop offset=".216" class="eyvys0o3y"/><stop offset=".358" class="f7agtibhr"/><stop offset=".622" class="akmbvc3to"/><stop offset=".744" class="f0cnrab-y"/><stop offset="1" class="yke67ebue"/></linearGradient><linearGradient id="iKWU05c" x1="38.419" x2="38.181" y1="27.33" y2="32.195" gradientUnits="userSpaceOnUse"><stop class="s_uyuvb6l"/><stop offset="1" class="fa9w-xbfx"/></linearGradient><linearGradient id="i0sXMyc" x1="13.509" x2="15.014" y1="9.625" y2="10.859" gradientUnits="userSpaceOnUse"><stop class="klsz48bpa"/><stop offset="1" class="tei9ccciq"/></linearGradient><linearGradient id="ihXiOIc" x1="19.646" x2="19.646" y1="17.509" y2="19.016" gradientUnits="userSpaceOnUse"><stop class="r0_-y78pg"/><stop offset="1" class="q4a2vc2lm"/></linearGradient><linearGradient id="iyKhkIe" x1="21.132" x2="19.845" y1="18.262" y2="18.262" gradientUnits="userSpaceOnUse"><stop class="krqxb8xzb"/><stop offset="1" class="sq19-mbin"/></linearGradient><linearGradient id="idMUd0c" x1="18.578" x2="19.035" y1="18.343" y2="18.143" gradientUnits="userSpaceOnUse"><stop class="d7kyprbbf"/><stop offset="1" class="nyu434b0b"/></linearGradient><linearGradient id="ipusERb" x1="19.705" x2="19.705" y1="18.359" y2="19.016" gradientUnits="userSpaceOnUse"><stop class="f7qilnbph"/><stop offset="1" class="qvydrzbes"/></linearGradient><linearGradient id="iGOxIci" x1="17.267" x2="18.627" y1="14.948" y2="14.355" gradientUnits="userSpaceOnUse"><stop class="f_3tuabnq"/><stop offset=".216" class="q3l0vfbth"/><stop offset=".358" class="ld3xfxbsb"/><stop offset=".622" class="xua1_ccst"/><stop offset=".744" class="d5qymqbxp"/><stop offset="1" class="h02fxub1p"/></linearGradient><linearGradient id="ifwZAni" x1="2" x2="3.501" y1="19.692" y2="19.692" gradientUnits="userSpaceOnUse"><stop class="m2hvvg4js"/><stop offset=".216" class="cuqw80bxu"/><stop offset=".358" class="cuqw80bxu"/><stop offset=".622" class="iaejpurix"/><stop offset=".744" class="iaejpurix"/><stop offset="1" class="t6hq24f3l"/></linearGradient><linearGradient id="imBZdmc" x1="5.517" x2="2" y1="24.567" y2="33.027" gradientUnits="userSpaceOnUse"><stop class="s_uyuvb6l"/><stop offset="1" class="fa9w-xbfx"/></linearGradient><linearGradient id="iN3PMFb" x1="15.997" x2="17.808" y1="26.308" y2="25.414" gradientUnits="userSpaceOnUse"><stop class="sqzotjq3d"/><stop offset=".216" class="eyvys0o3y"/><stop offset=".358" class="f7agtibhr"/><stop offset=".622" class="akmbvc3to"/><stop offset=".744" class="f0cnrab-y"/><stop offset="1" class="yke67ebue"/></linearGradient><linearGradient id="ixAAqLB" x1="10.031" x2="10.031" y1="19.001" y2="20.516" gradientUnits="userSpaceOnUse"><stop class="r0_-y78pg"/><stop offset="1" class="q4a2vc2lm"/></linearGradient><linearGradient id="iWX7rDi" x1="11.657" x2="10.249" y1="19.758" y2="19.758" gradientUnits="userSpaceOnUse"><stop class="krqxb8xzb"/><stop offset="1" class="sq19-mbin"/></linearGradient><linearGradient id="iZgcegc" x1="8.863" x2="9.349" y1="19.839" y2="19.609" gradientUnits="userSpaceOnUse"><stop class="d7kyprbbf"/><stop offset="1" class="nyu434b0b"/></linearGradient><linearGradient id="i9ygIpd" x1="7.105" x2="8.707" y1="15.717" y2="15.008" gradientUnits="userSpaceOnUse"><stop class="f_3tuabnq"/><stop offset=".216" class="q3l0vfbth"/><stop offset=".358" class="ld3xfxbsb"/><stop offset=".622" class="xua1_ccst"/><stop offset=".744" class="d5qymqbxp"/><stop offset="1" class="h02fxub1p"/></linearGradient><linearGradient id="i27qzHb" x1="3.501" x2="2.751" y1="9.529" y2="10.296" gradientUnits="userSpaceOnUse"><stop class="zf0vyacpo"/><stop offset=".808" class="d6eyafb2h"/></linearGradient><linearGradient id="iYeiXLm" x1="2" x2="2.372" y1="9.479" y2="9.479" gradientUnits="userSpaceOnUse"><stop class="c61r5oqkr"/><stop offset="1" class="etnccbb8l"/></linearGradient><linearGradient id="iGIy4Tb" x1="11.026" x2="9.346" y1="23.379" y2="23.379" gradientUnits="userSpaceOnUse"><stop offset=".682" class="gb2ozeb2s"/><stop offset=".925" class="fo31sswjx"/><stop offset="1" class="kyr-5xbts"/></linearGradient><linearGradient id="iSHWDYb" x1="11.026" x2="9.342" y1="28.37" y2="28.37" gradientUnits="userSpaceOnUse"><stop offset=".682" class="gb2ozeb2s"/><stop offset=".925" class="fo31sswjx"/><stop offset="1" class="kyr-5xbts"/></linearGradient><radialGradient id="iJspkGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .756 -2.62159 0 10.85 9.672)" gradientUnits="userSpaceOnUse"><stop class="kzck80b3b"/><stop offset="1" class="epbausbor"/></radialGradient><radialGradient id="ilaPspe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71966 -1.30044 0 7.74 9.7)" gradientUnits="userSpaceOnUse"><stop class="kzck80b3b"/><stop offset="1" class="epbausbor"/></radialGradient><radialGradient id="iOGbYcU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.41418 6.24192 0 12.71 11.982)" gradientUnits="userSpaceOnUse"><stop offset=".504" class="f_3tuabnq"/><stop offset=".562" class="q3l0vfbth"/><stop offset=".596" class="ld3xfxbsb"/><stop offset=".67" class="xua1_ccst"/><stop offset=".729" class="d5qymqbxp"/><stop offset=".777" class="h02fxub1p"/></radialGradient><radialGradient id="ihmcUrc" cx="0" cy="0" r="1" gradientTransform="rotate(-55.063 31.041 -9.724)scale(4.02554 4.20009)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="sqzotjq3d"/><stop offset=".717" class="eyvys0o3y"/><stop offset=".793" class="f7agtibhr"/><stop offset=".889" class="akmbvc3to"/><stop offset=".932" class="f0cnrab-y"/><stop offset="1" class="yke67ebue"/></radialGradient><radialGradient id="i8IXKXd" cx="0" cy="0" r="1" gradientTransform="matrix(.51259 .81448 -.52378 .32963 19.538 17.51)" gradientUnits="userSpaceOnUse"><stop class="i06g-hged"/><stop offset="1" class="rartw4dye"/></radialGradient><radialGradient id="ix5qIud" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67667 0 0 -.6279 21.132 17.772)" gradientUnits="userSpaceOnUse"><stop class="j2hmk31ff"/><stop offset="1" class="jroz-8rdm"/></radialGradient><radialGradient id="ifJxlae" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89553 -3.8086 0 20.845 18.77)" gradientUnits="userSpaceOnUse"><stop class="d64z7uusn"/><stop offset="1" class="nwwez3pjt"/></radialGradient><radialGradient id="iSMKcBb" cx="0" cy="0" r="1" gradientTransform="rotate(66 -6.102 7.9)scale(1.94618 .85073)" gradientUnits="userSpaceOnUse"><stop class="s9l9xxrdi"/><stop offset="1" class="ivl3lg_km"/></radialGradient><radialGradient id="iGKX3Ec" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.99 5.66)scale(2.6645)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="guf7q7bwd"/><stop offset=".609" class="qfzpzvm_u"/><stop offset=".859" class="ke9bp7nmm"/><stop offset=".901" class="ke9bp7nmm"/><stop offset="1" class="cusbkac1x"/></radialGradient><radialGradient id="igrw9tb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09215 1.12736 -2.66468 -2.58144 7.003 4.681)" gradientUnits="userSpaceOnUse"><stop class="jlfdjjbwu"/><stop offset="1" class="t9sgi5ngg"/></radialGradient><radialGradient id="iPrcHse" cx="0" cy="0" r="1" gradientTransform="rotate(42.893 -4.188 6.359)scale(3.38483 7.63184)" gradientUnits="userSpaceOnUse"><stop class="qnb9ftkop"/><stop offset="1" class="l1fenp9nq"/></radialGradient><radialGradient id="irEE6Sc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.137 6.77)scale(1.69422)" gradientUnits="userSpaceOnUse"><stop class="qnb9ftkop"/><stop offset="1" class="l1fenp9nq"/></radialGradient><radialGradient id="ioaSVye" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.922 5.594)scale(1.76555)" gradientUnits="userSpaceOnUse"><stop class="glb8v4bxi"/><stop offset="1" class="n3pn47jlk"/></radialGradient><radialGradient id="ii2ffMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.94344 4.08098 -3.76122 -.86952 5.615 6.759)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="xl_dgy_5v"/><stop offset="1" class="pv7g7bb-m"/></radialGradient><radialGradient id="iNV1c0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.12461 -2.67179 0 4.672 6.157)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="f0h9xebhl"/><stop offset=".403" class="ska6gybxy"/></radialGradient><radialGradient id="iSXavIe" cx="0" cy="0" r="1" gradientTransform="rotate(90 2.093 8.743)scale(2.6645)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="guf7q7bwd"/><stop offset=".609" class="qfzpzvm_u"/><stop offset=".859" class="ke9bp7nmm"/><stop offset=".901" class="ke9bp7nmm"/><stop offset="1" class="cusbkac1x"/></radialGradient><radialGradient id="iT9zPNb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09215 1.12736 -2.66468 -2.58144 13.167 4.681)" gradientUnits="userSpaceOnUse"><stop class="mg5_yl_5l"/><stop offset="1" class="t9sgi5ngg"/></radialGradient><radialGradient id="iTCc3gb" cx="0" cy="0" r="1" gradientTransform="rotate(42.893 -1.106 14.205)scale(3.38483 7.63184)" gradientUnits="userSpaceOnUse"><stop class="qnb9ftkop"/><stop offset="1" class="l1fenp9nq"/></radialGradient><radialGradient id="irJTCKd" cx="0" cy="0" r="1" gradientTransform="rotate(90 2.944 9.853)scale(1.69422)" gradientUnits="userSpaceOnUse"><stop class="qnb9ftkop"/><stop offset="1" class="l1fenp9nq"/></radialGradient><radialGradient id="irdL8Sm" cx="0" cy="0" r="1" gradientTransform="rotate(90 2.16 8.676)scale(1.76555)" gradientUnits="userSpaceOnUse"><stop class="glb8v4bxi"/><stop offset="1" class="n3pn47jlk"/></radialGradient><radialGradient id="iHBgCDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.94344 4.08098 -3.76122 -.86952 11.78 6.759)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="xl_dgy_5v"/><stop offset="1" class="pv7g7bb-m"/></radialGradient><radialGradient id="icjFNnz" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.12461 -2.67179 0 10.836 6.157)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="f0h9xebhl"/><stop offset=".403" class="ska6gybxy"/></radialGradient><radialGradient id="ivz7ltb" cx="0" cy="0" r="1" gradientTransform="rotate(-63.722 26.145 3.547)scale(6.34153 5.57048)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="sqzotjq3d"/><stop offset=".662" class="eyvys0o3y"/><stop offset=".793" class="f7agtibhr"/><stop offset=".903" class="akmbvc3to"/><stop offset=".932" class="f0cnrab-y"/><stop offset="1" class="yke67ebue"/></radialGradient><radialGradient id="iMryMFb" cx="0" cy="0" r="1" gradientTransform="matrix(.56084 .819 -.54465 .37297 9.913 19)" gradientUnits="userSpaceOnUse"><stop class="i06g-hged"/><stop offset="1" class="rartw4dye"/></radialGradient><radialGradient id="i5mLrHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.547 .00705 -.0038 -.83385 11.712 19.353)" gradientUnits="userSpaceOnUse"><stop class="j2hmk31ff"/><stop offset="1" class="jroz-8rdm"/></radialGradient><radialGradient id="iWIs75V" cx="0" cy="0" r="1" gradientTransform="matrix(1.41094 -1.46393 2.86294 2.7593 4.087 11.108)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="f_3tuabnq"/><stop offset=".519" class="q3l0vfbth"/><stop offset=".656" class="ld3xfxbsb"/><stop offset=".826" class="xua1_ccst"/><stop offset=".896" class="d5qymqbxp"/><stop offset="1" class="h02fxub1p"/></radialGradient><radialGradient id="iI041kc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.51215 .53866 0 3.041 10.393)" gradientUnits="userSpaceOnUse"><stop class="iaejpurix"/><stop offset="1" class="yg7rlwbml"/></radialGradient><radialGradient id="iY8lqSd" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 .37891 -.37891 -.84375 3.527 8.777)" gradientUnits="userSpaceOnUse"><stop class="cot0fszbx"/><stop offset="1" class="g6z6e9ovw"/></radialGradient><radialGradient id="ilt5k2d" cx="0" cy="0" r="1" gradientTransform="rotate(163.466 1.066 5.263)scale(.87148 .80057)" gradientUnits="userSpaceOnUse"><stop class="s9l9xxrdi"/><stop offset="1" class="ivl3lg_km"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:playground-slide" /></template>
<style>
.akmbvc3to {
  stop-color: var(--svg-color--f25f6c, #F25F6C);
}

.b-4p19ayv {
  d: path("M16.242 12.408C15.607 10.946 14.594 9.5 13 9.5l-1 .5H9.661l-.752-.296l-.743.296H7.23l-.669-.296l-.676.296H5.11l4.26 9.254c.489 1.064 1.553.808 2.724.808s2.371.799 2.693 1.54L18.437 30h10.645l-4.259-9.24c-.49-1.063-1.959-2.158-3.13-2.158h-1.776A1 1 0 0 1 19 18z");
}

.bdzfi6bsx {
  fill-rule: evenodd;
  d: path("M13 9.5c1.594 0 2.607 1.446 3.242 2.908L19 18a1 1 0 0 0 .917.602h1.777c.436 0 .914.152 1.367.398H9.252L5.11 10h.775l.676-.296l.669.296h.936l.743-.296l.752.296H12z");
}

.btd2pfthl {
  fill-rule: evenodd;
  d: path("M11.39 19v1.516h.235c1.17 0 2.432 1.17 2.922 2.234l.117.25h1.656l-.41-.878C15.173 20.527 13.38 19 11.624 19z");
}

.c61r5oqkr {
  stop-color: var(--svg-color--d06c7b, #D06C7B);
}

.cot0fszbx {
  stop-color: var(--svg-color--f75290, #F75290);
}

.crgsm-d3w {
  stop-color: var(--svg-color--388ef5, #388EF5);
}

.cuqw80bxu {
  stop-color: var(--svg-color--d7305c, #D7305C);
}

.cusbkac1x {
  stop-color: var(--svg-color--29b2ff, #29B2FF);
}

.d3k_-dbrm {
  stop-color: var(--svg-color--bc2a53, #BC2A53);
}

.d5qymqbxp {
  stop-color: var(--svg-color--fa5c9a, #FA5C9A);
}

.d64z7uusn {
  stop-color: var(--svg-color--df2f50, #DF2F50);
}

.d6eyafb2h {
  stop-color: var(--svg-color--d8305d, #D8305D);
}

.d7kyprbbf {
  stop-color: var(--svg-color--e7296a, #E7296A);
}

.d7qzr7bxc {
  fill-rule: evenodd;
  d: path("M8.17 6.489q-.006.09-.006.183V10h1.5V6.672q0-.094.014-.183zm3.823 0q.015.09.015.183V10s.894-.047 1.5.16V6.672q0-.093-.007-.183z");
}

.dpkfnkbyb {
  fill: var(--svg-color--d9d9d9, #D9D9D9);
  fill-rule: evenodd;
  d: path("M11.39 19v1.516h.235c1.17 0 2.432 1.17 2.922 2.234l.117.25h1.656l-.41-.878C15.173 20.527 13.38 19 11.624 19z");
}

.e6_6_rbmq {
  d: path("M9.483 22.033h1.502v2.948H9.483z");
}

.eju9i5idu {
  stop-color: var(--svg-color--3dacf5, #3DACF5);
}

.epbausbor {
  stop-color: var(--svg-color--c2c5ca, #C2C5CA);
  stop-opacity: 0;
}

.etnccbb8l {
  stop-color: var(--svg-color--d06779, #D06779);
  stop-opacity: 0;
}

.eyvys0o3y {
  stop-color: var(--svg-color--de2e4f, #DE2E4F);
}

.f_3tuabnq {
  stop-color: var(--svg-color--e62869, #E62869);
}

.f0cnrab-y {
  stop-color: var(--svg-color--f35f6b, #F35F6B);
}

.f0h9xebhl {
  stop-color: var(--svg-color--4774f1, #4774F1);
}

.f7agtibhr {
  stop-color: var(--svg-color--e13756, #E13756);
}

.f7qilnbph {
  stop-color: var(--svg-color--d2435a, #D2435A);
  stop-opacity: 0;
}

.fa9w-xbfx {
  stop-color: var(--svg-color--da3147, #DA3147);
}

.fcmawhgup {
  stop-color: var(--svg-color--bc3a42, #BC3A42);
  stop-opacity: 0;
}

.fo31sswjx {
  stop-color: var(--svg-color--9f2a39, #9F2A39);
}

.ft5dv1b6b {
  fill: none;
}

.g1vbzac3k {
  stop-color: var(--svg-color--ac1845, #AC1845);
}

.g6z6e9ovw {
  stop-color: var(--svg-color--f75290, #F75290);
  stop-opacity: 0;
}

.gaumlhb_z {
  stop-color: var(--svg-color--49c7ff, #49C7FF);
}

.gb2ozeb2s {
  stop-color: var(--svg-color--bb2a53, #BB2A53);
  stop-opacity: 0;
}

.gb3h6t4sp {
  stop-color: var(--svg-color--dad9dc, #DAD9DC);
}

.gc4slbvhn {
  stop-color: var(--svg-color--be2635, #BE2635);
  stop-opacity: 0;
}

.gh40ckx_b {
  stop-color: var(--svg-color--be2635, #BE2635);
}

.glb8v4bxi {
  stop-color: var(--svg-color--377ff4, #377FF4);
}

.guf7q7bwd {
  stop-color: var(--svg-color--377cec, #377CEC);
}

.gxisrlbso {
  fill-rule: evenodd;
  d: path("M11.657 20.516V19H8.534l.397.913a1 1 0 0 0 .918.602z");
}

.h02fxub1p {
  stop-color: var(--svg-color--ef5994, #EF5994);
}

.hmqokvbzv {
  stop-color: var(--svg-color--a00e3b, #A00E3B);
}

.hnqm-cc4o {
  fill-rule: evenodd;
  d: path("M12.007 6.65a1.172 1.172 0 0 0-2.343 0h-1.5a2.672 2.672 0 0 1 5.344 0z");
}

.hqmw6ibqw {
  stop-color: var(--svg-color--3eb8fe, #3EB8FE);
  stop-opacity: 0;
}

.hxg69ubid {
  stop-color: var(--svg-color--ac1f53, #AC1F53);
}

.i06g-hged {
  stop-color: var(--svg-color--fa5d9a, #FA5D9A);
}

.iaejpurix {
  stop-color: var(--svg-color--e85079, #E85079);
}

.ih_s3nbjx {
  stop-color: var(--svg-color--4bc9ff, #4BC9FF);
}

.ipe7dgnyt {
  fill-rule: evenodd;
  d: path("m19.913 17.509l.003.007h1.216v1.5h-1.544a1 1 0 0 1-.918-.602l-.392-.905z");
}

.ivl3lg_km {
  stop-color: var(--svg-color--e6286a, #E6286A);
  stop-opacity: 0;
}

.j20w3r7rl {
  fill-rule: evenodd;
  d: path("M20.5 17.516h.864a4.5 4.5 0 0 1 4.087 2.616l.126.273h-1.682a3 3 0 0 0-2.531-1.39H20.5z");
}

.j2hmk31ff {
  stop-color: var(--svg-color--f3606c, #F3606C);
}

.j8u4ivbhv {
  fill-rule: evenodd;
  d: path("M12.067 9.998V10h.328q.063 0 .125.002a6 6 0 0 0-.453-.004m1.384.144a4 4 0 0 0-.516-.105c.175.022.354.055.516.105m.057.016V8.614a5.5 5.5 0 0 1 3.932 3.197l.306.705h-1.635l-.047-.108a4 4 0 0 0-2.556-2.25");
}

.jlfdjjbwu {
  stop-color: var(--svg-color--52dcff, #52DCFF);
}

.jroz-8rdm {
  stop-color: var(--svg-color--f3606c, #F3606C);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7ub3vbdl {
  d: path("M9.479 27h1.506v3H9.479z");
}

.ke9bp7nmm {
  stop-color: var(--svg-color--5dddff, #5DDDFF);
}

.kelsrsb5y {
  stop-color: var(--svg-color--cbccd3, #CBCCD3);
}

.kem5zbbfn {
  fill: var(--svg-color--d9d9d9, #D9D9D9);
  fill-rule: evenodd;
  d: path("M20.5 17.516h.864a4.5 4.5 0 0 1 4.087 2.616l.126.273h-1.682a3 3 0 0 0-2.531-1.39H20.5z");
}

.kiuexrbol {
  fill-rule: evenodd;
  d: path("M3.5 10.296H2V10c0-.828.684-1.52 1.482-1.296l.02.006v1.584H3.5z");
}

.klsz48bpa {
  stop-color: var(--svg-color--d73b85, #D73B85);
}

.krqxb8xzb {
  stop-color: var(--svg-color--e13555, #E13555);
}

.kyr-5xbts {
  stop-color: var(--svg-color--bd2e4c, #BD2E4C);
  stop-opacity: 0;
}

.kzck80b3b {
  stop-color: var(--svg-color--8a98ae, #8A98AE);
}

.l1fenp9nq {
  stop-color: var(--svg-color--34afff, #34AFFF);
  stop-opacity: 0;
}

.l2_7b7baf {
  stop-color: var(--svg-color--c8c3cf, #C8C3CF);
}

.ld3xfxbsb {
  stop-color: var(--svg-color--ef377f, #EF377F);
}

.m2hvvg4js {
  stop-color: var(--svg-color--cf6e7c, #CF6E7C);
}

.m3k5m890u {
  fill-rule: evenodd;
  d: path("M15.677 11.713h1.72q.023.048.043.098l2.476 5.705H18.28l-2.217-5.108a4 4 0 0 0-.387-.695");
}

.meaaiev1f {
  fill-rule: evenodd;
  d: path("M2.006 6.489Q2 6.579 2 6.672V10h1.5V6.672q0-.094.014-.183zm3.824 0q.014.09.014.183V10h1.5V6.672q0-.093-.006-.183z");
}

.mg5_yl_5l {
  stop-color: var(--svg-color--b5f0ff, #B5F0FF);
}

.mjl8vs3xo {
  stop-color: var(--svg-color--ab1644, #AB1644);
}

.mzkehobnl {
  stop-color: var(--svg-color--3793f7, #3793F7);
}

.n2uiqhbik {
  stop-color: var(--svg-color--bc2d4b, #BC2D4B);
  stop-opacity: 0;
}

.n3pn47jlk {
  stop-color: var(--svg-color--377ff4, #377FF4);
  stop-opacity: 0;
}

.n8aj_hshk {
  d: path("M10.984 30V14.419L9.484 14v1.047H2.766v2.015h6.718v2.954H2.766v2.015h6.718v2.953H2.766V27h6.718v3z");
}

.nwwez3pjt {
  stop-color: var(--svg-color--de3050, #DE3050);
  stop-opacity: 0;
}

.nyu434b0b {
  stop-color: var(--svg-color--e7296a, #E7296A);
  stop-opacity: 0;
}

.nyxyulb7w {
  stop-color: var(--svg-color--3db9ff, #3DB9FF);
}

.pv7g7bb-m {
  stop-color: var(--svg-color--2693ea, #2693EA);
}

.px8--zbuq {
  stop-color: var(--svg-color--4dcbff, #4DCBFF);
}

.pzjnu0b9e {
  stop-color: var(--svg-color--c4c1c4, #C4C1C4);
}

.q3l0vfbth {
  stop-color: var(--svg-color--ed3174, #ED3174);
}

.q442f7cej {
  stop-color: var(--svg-color--b61a4a, #B61A4A);
  stop-opacity: 0;
}

.q4a2vc2lm {
  stop-color: var(--svg-color--dc3251, #DC3251);
}

.qbpm-6b2v {
  stop-color: var(--svg-color--c7c7c7, #C7C7C7);
}

.qfzpzvm_u {
  stop-color: var(--svg-color--38b4ff, #38B4FF);
}

.qnb9ftkop {
  stop-color: var(--svg-color--34afff, #34AFFF);
}

.qvydrzbes {
  stop-color: var(--svg-color--cd485c, #CD485C);
}

.r0_-y78pg {
  stop-color: var(--svg-color--ee3275, #EE3275);
}

.racfucc-y {
  fill-rule: evenodd;
  d: path("m19.601 30l-3.692-7.878a5.3 5.3 0 0 0-.477-.823h-2.013c.488.417.895.946 1.128 1.451L17.95 30z");
}

.rartw4dye {
  stop-color: var(--svg-color--fa5d9a, #FA5D9A);
  stop-opacity: 0;
}

.rx1_7okpd {
  fill-rule: evenodd;
  d: path("M5.844 6.65a1.172 1.172 0 0 0-2.344 0H2a2.672 2.672 0 0 1 5.344 0z");
}

.s_uyuvb6l {
  stop-color: var(--svg-color--da3147, #DA3147);
  stop-opacity: 0;
}

.s9l9xxrdi {
  stop-color: var(--svg-color--e6286a, #E6286A);
}

.shsqtoboh {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  fill-rule: evenodd;
  d: path("M13 9.5c1.594 0 2.607 1.446 3.242 2.908L19 18a1 1 0 0 0 .917.602h1.777c.436 0 .914.152 1.367.398H9.252L5.11 10h.775l.676-.296l.669.296h.936l.743-.296l.752.296H12z");
}

.ska6gybxy {
  stop-color: var(--svg-color--4774f1, #4774F1);
  stop-opacity: 0;
}

.smh0gzbmq {
  stop-color: var(--svg-color--afa0a3, #AFA0A3);
}

.sq19-mbin {
  stop-color: var(--svg-color--e23656, #E23656);
  stop-opacity: 0;
}

.sqzotjq3d {
  stop-color: var(--svg-color--cf465b, #CF465B);
}

.stwh_5b1l {
  fill-rule: evenodd;
  d: path("M3.501 10.294V8.71a5.5 5.5 0 0 1 3.28 2.58H4.939a4 4 0 0 0-1.437-.996");
}

.t6hq24f3l {
  stop-color: var(--svg-color--d5466e, #D5466E);
}

.t9sgi5ngg {
  stop-color: var(--svg-color--52dcff, #52DCFF);
  stop-opacity: 0;
}

.tei9ccciq {
  stop-color: var(--svg-color--d73b85, #D73B85);
  stop-opacity: 0;
}

.u8m4tviwt {
  stop-color: var(--svg-color--3dacf5, #3DACF5);
  stop-opacity: 0;
}

.uekfm8bvw {
  fill-rule: evenodd;
  d: path("M6.782 11.29H4.938c.298.323.546.7.728 1.118l2.87 6.596h3.121V19h-1.48l-3.135-7.19a6 6 0 0 0-.26-.52");
}

.vq65mp4ee {
  stop-color: var(--svg-color--309cf0, #309CF0);
  stop-opacity: 0;
}

.wqb8ysb6u {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  fill-rule: evenodd;
  d: path("M5.844 6.65a1.172 1.172 0 0 0-2.344 0H2a2.672 2.672 0 0 1 5.344 0z");
}

.xl_dgy_5v {
  stop-color: var(--svg-color--3e91e7, #3E91E7);
  stop-opacity: 0;
}

.xua1_ccst {
  stop-color: var(--svg-color--f95c96, #F95C96);
}

.xwlc_9lhs {
  fill-rule: evenodd;
  d: path("M2 10v20h1.5V10.293l.001.001V10z");
}

.xxue105dr {
  stop-color: var(--svg-color--e5e2e5, #E5E2E5);
}

.y2wj3r46h {
  stop-color: var(--svg-color--3890f5, #3890F5);
  stop-opacity: 0;
}

.yg7rlwbml {
  stop-color: var(--svg-color--e85079, #E85079);
  stop-opacity: 0;
}

.yke67ebue {
  stop-color: var(--svg-color--e24954, #E24954);
}

.yl8d5_b_g {
  stop-color: var(--svg-color--3eb8fe, #3EB8FE);
}

.zc6_-8ssr {
  fill-rule: evenodd;
  d: path("M24.85 19.17c.237.29.44.612.6.962L30 30h-1.652l-4.26-9.24a3 3 0 0 0-1.773-1.59z");
}

.zf0vyacpo {
  stop-color: var(--svg-color--eb2e70, #EB2E70);
}

.zgp-phxqx {
  stop-color: var(--svg-color--cc3752, #CC3752);
}

.zj_ouqbux {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M12.007 6.65a1.172 1.172 0 0 0-2.343 0h-1.5a2.672 2.672 0 0 1 5.344 0z");
}

.ztlaxabxa {
  stop-color: var(--svg-color--309cf0, #309CF0);
}

.zuz9txb9k {
  stop-color: var(--svg-color--53d2ff, #53D2FF);
}

</style>
