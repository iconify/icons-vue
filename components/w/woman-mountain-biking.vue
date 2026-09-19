<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i29Mg6d)"><path fill="url(#iirSqfd)" class="q11jy6bfa"/><path fill="url(#ibMllOc)" class="q11jy6bfa"/></g><g filter="url(#iVXO5he)"><path fill="url(#iGELW5d)" class="tm9a1_b0b"/></g><path fill="url(#iC2qype)" class="tm9a1_b0b"/><g filter="url(#iwz3m9b)"><path class="zqha2ybmm"/><path fill="url(#iHu57Zb)" class="ulnr6-8rs"/></g><g filter="url(#iHVdVQm)"><path fill="url(#iBVNdPB)" clip-rule="evenodd" class="ue1cg0jtk"/></g><g filter="url(#iotQfDb)"><circle stroke="url(#iMqUPPc)" class="f2dg1pymm"/></g><path fill="url(#i2e3rqe)" class="i09bgfv6r"/><path class="sidw1obfr"/><path fill="url(#iAUidTI)" class="g7aqyha-f"/><path fill="url(#ipimVNe)" class="g7aqyha-f"/><path fill="url(#ikI6zud)" clip-rule="evenodd" class="mvvhg6bob"/><path fill="url(#ioqA6Ec)" clip-rule="evenodd" class="mvvhg6bob"/><path fill="url(#iByKjmc)" clip-rule="evenodd" class="fuvqv0efx"/><path fill="url(#ilystOc)" clip-rule="evenodd" class="g8r6p49_s"/><path fill="url(#isottie)" clip-rule="evenodd" class="g8r6p49_s"/><g filter="url(#ifefhIe)"><path fill="url(#iXjYTba)" clip-rule="evenodd" class="pfbx1ib6q"/><path fill="url(#iWYSLge)" clip-rule="evenodd" class="pfbx1ib6q"/></g><path fill="url(#iDeh7Jb)" clip-rule="evenodd" class="nrp3vkbjq"/><path fill="url(#i7VZLSd)" clip-rule="evenodd" class="wjs_nsbuh"/><path fill="url(#iAoLEke)" clip-rule="evenodd" class="wjs_nsbuh"/><path fill="url(#iX1cArb)" clip-rule="evenodd" class="wjs_nsbuh"/><path fill="url(#iNPU4ge)" class="b3q5ubbch"/><path fill="url(#igrGXyb)" class="b3q5ubbch"/><path fill="url(#i26uiic)" class="b3q5ubbch"/><path fill="url(#iV9pPFc)" class="h-r_c9b7x"/><path fill="url(#i1M6eLc)" class="h-r_c9b7x"/><g filter="url(#i52O6Zd)"><path fill="url(#iv0gtpe)" class="wm4p2nf6o"/><path fill="url(#iUb7kZR)" class="wm4p2nf6o"/></g><circle fill="url(#iliKE4b)" class="rrfczgbhc"/><circle fill="url(#iNgFFMe)" class="rrfczgbhc"/><g filter="url(#iaj4j8d)"><path class="hz6yw06qq"/><path fill="url(#iQhym4p)" class="um4kzybeo"/><path fill="url(#iCW6Pzb)" class="um4kzybeo"/></g><path fill="url(#iAItS9d)" transform="rotate(-55.397 13.554 7.913)" class="czabn_xgs"/><g filter="url(#iaSw04x)"><path fill="url(#ivWkqce)" class="o0tyh0b-k"/><path fill="url(#iLvavoe)" class="o0tyh0b-k"/></g><g filter="url(#iIBGcqb)"><path fill="url(#i07SVib)" class="e_--_59xk"/><path fill="url(#ixRFUzd)" class="e_--_59xk"/></g><g filter="url(#igEBCte)"><path fill="url(#iJeQlac)" class="hla563ezk"/></g><g filter="url(#ismlpKc)"><path class="pzip1rpvk"/><path fill="url(#iAMUXHd)" class="iy0i0xbqt"/></g><g filter="url(#ifpJRug)"><path clip-rule="evenodd" class="u3_kb5fuo"/></g><g filter="url(#iNj31Jb)"><path clip-rule="evenodd" class="l13xg_5qx"/><path fill="url(#iPK9Ufb)" clip-rule="evenodd" class="cpzd76x5u"/></g><path fill="url(#iPpbfwe)" clip-rule="evenodd" class="s2qrn4tqf"/><g filter="url(#iluMUXc)"><path fill="url(#iYiWRhd)" class="qc8cprh-k"/></g><path fill="url(#iRAoTvb)" clip-rule="evenodd" class="ep0khpbhu"/><path fill="url(#iUfsrsd)" clip-rule="evenodd" class="biur58u6f"/><g filter="url(#iavqCmc)"><circle fill="url(#imV7zdw)" class="ofnkd-b6m"/></g><path fill="url(#iYLO7DO)" class="yy0ulywkr"/><g filter="url(#iOwXEEd)"><path fill="url(#ioEo4Tc)" class="kre6dibsw"/><path fill="url(#iyILqAe)" class="kre6dibsw"/></g><path class="hv1jutayr"/><path clip-rule="evenodd" class="py22frtcc"/><path class="vsnbcxbze"/><path fill="url(#iHeurNc)" class="e8wau1-op"/><path class="pm89cjb4a"/><circle transform="rotate(-63.437 11.132 6.807)" class="tygrts44k"/><g filter="url(#iGuNkTi)"><path fill="url(#itlefpd)" class="meyl3ibku"/></g><circle fill="url(#i0UbsKN)" transform="rotate(-63.437 13.47 5.792)" class="v1b11fqgs"/><path clip-rule="evenodd" class="kbuneegfe"/><path fill="url(#i14mXtc)" clip-rule="evenodd" class="p-_-lbbjz"/><path fill="url(#iAESIIe)" clip-rule="evenodd" class="p-_-lbbjz"/><path fill="url(#isBplse)" clip-rule="evenodd" class="p-_-lbbjz"/><g filter="url(#ilMPmWc)"><path fill="url(#i1mMFAc)" class="jlxn3mbju"/></g><g filter="url(#iutL0Ob)"><path fill="url(#iWPtRDb)" class="fv7k0--yw"/></g><defs><radialGradient id="iC2qype" cx="0" cy="0" r="1" gradientTransform="rotate(150.331 11.85 6.032)scale(3.70975 8.36641)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="l4_q8ccja"/><stop offset="1" class="fy0gg3b4w"/></radialGradient><radialGradient id="iHu57Zb" cx="0" cy="0" r="1" gradientTransform="matrix(4.42529 4.18325 -2.33905 2.47438 19.82 26.757)" gradientUnits="userSpaceOnUse"><stop class="qfj7itbso"/><stop offset="1" class="p1dkvx0ja"/></radialGradient><radialGradient id="iBVNdPB" cx="0" cy="0" r="1" gradientTransform="rotate(126.943 -.1 13.106)scale(9.77501 9.43553)" gradientUnits="userSpaceOnUse"><stop class="y16t4y92n"/><stop offset="1" class="hqorccbwh"/></radialGradient><radialGradient id="ipimVNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53127 2.45312 -.44454 -.27749 20.346 20.953)" gradientUnits="userSpaceOnUse"><stop class="m3q9izqvj"/><stop offset="1" class="gxtng2bih"/></radialGradient><radialGradient id="ioqA6Ec" cx="0" cy="0" r="1" gradientTransform="rotate(-68.026 17.608 .423)scale(2.88119 .32513)" gradientUnits="userSpaceOnUse"><stop class="f-r3ld20z"/><stop offset="1" class="qnv5cwbcc"/></radialGradient><radialGradient id="ilystOc" cx="0" cy="0" r="1" gradientTransform="matrix(6.71875 4.82813 -1.31599 1.83131 10.22 18.516)" gradientUnits="userSpaceOnUse"><stop class="zo6cprbov"/><stop offset="1" class="cc9670aeb"/></radialGradient><radialGradient id="iXjYTba" cx="0" cy="0" r="1" gradientTransform="rotate(134.451 10.034 17.078)scale(9.80603 9.46548)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="msqk4cb8o"/><stop offset="1" class="wc0bxtmli"/></radialGradient><radialGradient id="iAoLEke" cx="0" cy="0" r="1" gradientTransform="rotate(103.707 3.238 16.627)scale(4.61583 .44083)" gradientUnits="userSpaceOnUse"><stop class="rgol9fpyb"/><stop offset="1" class="jk5eocp2v"/></radialGradient><radialGradient id="iX1cArb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.0625 1.65481 -.04867 18.502 23.75)" gradientUnits="userSpaceOnUse"><stop class="d-6jagb2y"/><stop offset="1" class="zd8v8x_xx"/></radialGradient><radialGradient id="iNPU4ge" cx="0" cy="0" r="1" gradientTransform="matrix(2.1836 .4375 -.55377 2.76392 13.287 16.75)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="d8tqbz4fd"/><stop offset="1" class="v0nd3lbsl"/></radialGradient><radialGradient id="igrGXyb" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .45313 -.35 .94138 15.783 17.156)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="t18ofc-lq"/><stop offset="1" class="lyr5_abqg"/></radialGradient><radialGradient id="iV9pPFc" cx="0" cy="0" r="1" gradientTransform="rotate(143.881 6.994 9.938)scale(2.86275 1.23215)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="lj25sbc6e"/><stop offset="1" class="aqi57yb6w"/></radialGradient><radialGradient id="iUb7kZR" cx="0" cy="0" r="1" gradientTransform="matrix(-.86719 0 0 -.96875 25.62 24.813)" gradientUnits="userSpaceOnUse"><stop class="nus19y6ts"/><stop offset="1" class="aiqsdtepb"/></radialGradient><radialGradient id="iliKE4b" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 -.65625 .66797 1.5904 17.72 25.172)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="v5ts0ibjo"/><stop offset="1" class="huz3s4d_a"/></radialGradient><radialGradient id="iNgFFMe" cx="0" cy="0" r="1" gradientTransform="rotate(151.189 6.29 14.782)scale(1.78324)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="da9xf6l5p"/><stop offset="1" class="cbgow0bwo"/></radialGradient><radialGradient id="iCW6Pzb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1094 -2 6.41983 -3.56106 16.3 25.516)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="egxex7b7c"/><stop offset=".943" class="hs-_dnasa"/></radialGradient><radialGradient id="ivWkqce" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 -8.78125 2.52881 -.21598 17.94 23.906)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="o0qinnbwl"/><stop offset="1" class="t2hb3292i"/></radialGradient><radialGradient id="iLvavoe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6875 .0625 -.11168 -3.01554 18.846 17.625)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="d2b7azbtt"/><stop offset="1" class="j3wv83dcq"/></radialGradient><radialGradient id="i07SVib" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -4.9297 2.6132 2.71672 16.815 15.531)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="wfj_w2bhm"/><stop offset="1" class="zvme7yb8w"/></radialGradient><radialGradient id="ixRFUzd" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -.09375 .01804 .49916 18.237 13.813)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="evhu2k4sq"/><stop offset="1" class="p1krpu8fj"/></radialGradient><radialGradient id="iJeQlac" cx="0" cy="0" r="1" gradientTransform="matrix(-3.49999 -4.06251 1.70908 -1.47243 21.127 11.5)" gradientUnits="userSpaceOnUse"><stop class="yveukea-t"/><stop offset="1" class="cv8uymbkh"/></radialGradient><radialGradient id="iAMUXHd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25232 0 0 1.29925 10.078 12.938)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="d5hggqbjo"/><stop offset="1" class="codspw7xm"/></radialGradient><radialGradient id="iPK9Ufb" cx="0" cy="0" r="1" gradientTransform="rotate(158.559 7.971 6.041)scale(1.11134 1.23837)" gradientUnits="userSpaceOnUse"><stop class="rl39bhb3g"/><stop offset="1" class="yw3hdmr2n"/></radialGradient><radialGradient id="iYiWRhd" cx="0" cy="0" r="1" gradientTransform="matrix(5.5 -1.4375 2.00475 7.67032 17.377 14.688)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f6rwhfb_k"/><stop offset=".905" class="aw8cj7bar"/></radialGradient><radialGradient id="iUfsrsd" cx="0" cy="0" r="1" gradientTransform="matrix(.85938 -1.30714 1.0714 .7044 8.143 14.922)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="xkuwgzbmp"/><stop offset="1" class="wsobq_b1u"/></radialGradient><radialGradient id="imV7zdw" cx="0" cy="0" r="1" gradientTransform="rotate(48.659 -9.797 16.076)scale(1.90423)" gradientUnits="userSpaceOnUse"><stop class="q1us6i3dm"/><stop offset="1" class="rrdxh2bld"/></radialGradient><radialGradient id="iYLO7DO" cx="0" cy="0" r="1" gradientTransform="matrix(.67648 .33823 -.42548 .85098 10.773 7.78)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="b-0qxxbtd"/><stop offset="1" class="ql-kjsbnq"/></radialGradient><radialGradient id="ioEo4Tc" cx="0" cy="0" r="1" gradientTransform="matrix(3.09473 -1.08576 1.12611 3.20974 11.538 7.788)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="epfp24bqk"/><stop offset="1" class="l8ufshbax"/></radialGradient><radialGradient id="iyILqAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.06136 1.56356 -1.26168 .85644 13.077 5.074)" gradientUnits="userSpaceOnUse"><stop class="n4-no9-8p"/><stop offset="1" class="vq765rbep"/></radialGradient><radialGradient id="itlefpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.91995 2.44075 -3.51977 -1.32664 15.838 4.46)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="j8nsw2bmy"/><stop offset="1" class="ixfvn-b4t"/></radialGradient><radialGradient id="i0UbsKN" cx="0" cy="0" r="1" gradientTransform="rotate(-140.407 8.076 .554)scale(.68332 .77276)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="zu2bq3b1p"/><stop offset="1" class="lq9yn9biw"/></radialGradient><radialGradient id="isBplse" cx="0" cy="0" r="1" gradientTransform="matrix(.18836 -.08305 .4868 1.10407 13.405 6.403)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="i1mMFAc" cx="0" cy="0" r="1" gradientTransform="matrix(.94797 2.15497 -2.53286 1.11421 11.967 3.243)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="iWPtRDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.27953 -.6157 1.57892 -.71683 12.429 4.993)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><linearGradient id="iirSqfd" x1="9.723" x2="28.027" y1="21.004" y2="8.814" gradientUnits="userSpaceOnUse"><stop class="jk9sxjbtz"/><stop offset="1" class="bsmaek8tk"/></linearGradient><linearGradient id="ibMllOc" x1="29.436" x2="25.976" y1="11.992" y2="14.406" gradientUnits="userSpaceOnUse"><stop offset=".164" class="lc4-hmwkn"/><stop offset="1" class="jvv3w_k0n"/></linearGradient><linearGradient id="iGELW5d" x1="21.229" x2="24.97" y1="7.004" y2="4.912" gradientUnits="userSpaceOnUse"><stop class="tw0q1w8vf"/><stop offset="1" class="icj8g3w8l"/></linearGradient><linearGradient id="iMqUPPc" x1="9.283" x2="3.252" y1="21.313" y2="28.344" gradientUnits="userSpaceOnUse"><stop class="aqhis8bfy"/><stop offset="1" class="dicaxrbsa"/></linearGradient><linearGradient id="i2e3rqe" x1="17.752" x2="18.721" y1="20.516" y2="19.51" gradientUnits="userSpaceOnUse"><stop class="hwwjun9wx"/><stop offset="1" class="cyvhl4h-y"/></linearGradient><linearGradient id="iAUidTI" x1="22.268" x2="17.674" y1="22.084" y2="21.625" gradientUnits="userSpaceOnUse"><stop offset=".891" class="eper2rg6p"/><stop offset="1" class="btv0f_swr"/></linearGradient><linearGradient id="ikI6zud" x1="11.549" x2="10.674" y1="14.906" y2="14.625" gradientUnits="userSpaceOnUse"><stop class="b32taybyq"/><stop offset="1" class="cq_k1jhvn"/></linearGradient><linearGradient id="iByKjmc" x1="9.783" x2="8.502" y1="19.86" y2="19.375" gradientUnits="userSpaceOnUse"><stop offset=".146" class="l2qa6pp5f"/><stop offset="1" class="j4w4r7dqg"/></linearGradient><linearGradient id="isottie" x1="13.002" x2="13.393" y1="21.906" y2="21.406" gradientUnits="userSpaceOnUse"><stop class="xlcjgwbhs"/><stop offset="1" class="xdbcf5brc"/><stop offset="1" class="dkvvw7m1c"/></linearGradient><linearGradient id="iWYSLge" x1="20.049" x2="27.804" y1="27.417" y2="24.977" gradientUnits="userSpaceOnUse"><stop class="qkrvzzbyd"/><stop offset="1" class="zaq2lsbln"/></linearGradient><linearGradient id="iDeh7Jb" x1="23.83" x2="22.768" y1="21.844" y2="22.594" gradientUnits="userSpaceOnUse"><stop class="ikszdii2u"/><stop offset="1" class="li38i4ecv"/></linearGradient><linearGradient id="i7VZLSd" x1="19.627" x2="18.612" y1="20.617" y2="20.469" gradientUnits="userSpaceOnUse"><stop class="wjlh8kb9f"/><stop offset="1" class="pf-dzrbda"/></linearGradient><linearGradient id="i26uiic" x1="14.565" x2="14.987" y1="14.875" y2="15.563" gradientUnits="userSpaceOnUse"><stop class="m9vj6ebef"/><stop offset="1" class="f1fjk6_xs"/></linearGradient><linearGradient id="i1M6eLc" x1="16.635" x2="17.002" y1="13.742" y2="14.273" gradientUnits="userSpaceOnUse"><stop class="i4-r1q74d"/><stop offset="1" class="vr76p9bug"/></linearGradient><linearGradient id="iv0gtpe" x1="25.346" x2="16.682" y1="24.977" y2="24.977" gradientUnits="userSpaceOnUse"><stop class="jk12cqb2p"/><stop offset="1" class="bjfaebcql"/></linearGradient><linearGradient id="iQhym4p" x1="17.479" x2="16.721" y1="24.844" y2="24.844" gradientUnits="userSpaceOnUse"><stop class="z_jgx_kqm"/><stop offset="1" class="ktkvjmbcj"/></linearGradient><linearGradient id="iAItS9d" x1="15.733" x2="13.401" y1="9.27" y2="8.999" gradientUnits="userSpaceOnUse"><stop class="zy6pn1hgj"/><stop offset="1" class="r136ynjzb"/></linearGradient><linearGradient id="iPpbfwe" x1="7.88" x2="8.81" y1="13.656" y2="12.682" gradientUnits="userSpaceOnUse"><stop class="au1th23gc"/><stop offset="1" class="q1us6i3dm"/></linearGradient><linearGradient id="iRAoTvb" x1="7.94" x2="9.026" y1="14.188" y2="13.406" gradientUnits="userSpaceOnUse"><stop class="au1th23gc"/><stop offset="1" class="mikglz6lt"/></linearGradient><linearGradient id="iHeurNc" x1="11.445" x2="11.12" y1="7.1" y2="6.619" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="i14mXtc" x1="13.768" x2="13.349" y1="6.594" y2="6.8" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="iAESIIe" x1="13.588" x2="14.114" y1="8.387" y2="8.084" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><filter id="i29Mg6d" width="28.938" height="27.87" x="2.104" y="3.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.658824 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="iVXO5he" width="8.378" height="5.198" x="17.844" y="3.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.705882 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="iwz3m9b" width="27.922" height="3.388" x="2.119" y="26.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.258824 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="iHVdVQm" width="9.938" height="9.938" x="2.104" y="20.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.156863 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="iotQfDb" width="10.409" height="10.409" x="1.868" y="19.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23479" stdDeviation=".25"/></filter><filter id="ifefhIe" width="10.037" height="10.037" x="20.049" y="19.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.0862745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="i52O6Zd" width="9.188" height="4.077" x="16.682" y="22.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.341176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.490196 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23479" result="effect2_innerShadow_3987_23479"/></filter><filter id="iaj4j8d" width="4.034" height="2.181" x="13.544" y="23.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.188235 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="iaSw04x" width="3.572" height="8.62" x="15.217" y="15.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.611765 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="iIBGcqb" width="6.668" height="7.67" x="16.596" y="10.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.372549 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="igEBCte" width="7.971" height="5.869" x="15.054" y="7.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.27451 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="ismlpKc" width="6.005" height="4.259" x="6.951" y="11.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.501961 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="ifpJRug" width="3.137" height="2.915" x="6.951" y="12.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.117647 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="iNj31Jb" width="10.272" height="6.937" x="7.828" y="7.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.517647 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="iluMUXc" width="5.496" height="6.372" x="17.742" y="10.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23479" stdDeviation=".3"/></filter><filter id="iavqCmc" width="2.969" height="2.969" x="7.756" y="11.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23479" stdDeviation=".3"/></filter><filter id="iOwXEEd" width="5.504" height="5.083" x="10.089" y="4.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.54902 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="iGuNkTi" width="4.432" height="3.754" x="12.992" y="3.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.419608 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="ilMPmWc" width="5.874" height="4.944" x="9.353" y="1.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter><filter id="iutL0Ob" width="1.996" height="1.328" x="11.287" y="4.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23479"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-mountain-biking" /></template>
<style>
.aiqsdtepb {
  stop-color: var(--svg-color--ffd359, #FFD359);
  stop-opacity: 0;
}

.aqhis8bfy {
  stop-color: var(--svg-color--302a5b, #302A5B);
}

.aqi57yb6w {
  stop-color: var(--svg-color--7b5c60, #7B5C60);
}

.au1th23gc {
  stop-color: var(--svg-color--d38e33, #D38E33);
}

.aw8cj7bar {
  stop-color: var(--svg-color--afa6a9, #AFA6A9);
}

.b-0qxxbtd {
  stop-color: var(--svg-color--ebab2a, #EBAB2A);
}

.b32taybyq {
  stop-color: var(--svg-color--bfa8c7, #BFA8C7);
}

.b3q5ubbch {
  d: path("m14.015 15.445l1.34-.836l1.038 1.04l-.765 3.53a200 200 0 0 0-1.688-1.241c-.148-.102-.66-.543-.653-1.239c.008-.71.477-1.071.727-1.254");
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.biur58u6f {
  fill-rule: evenodd;
  d: path("M9.088 13.707a.33.33 0 0 1 0 .402c-.151.126-.342.39-.372.594a.35.35 0 0 1-.693-.101a1.4 1.4 0 0 1 .155-.429c.08-.148.196-.313.354-.443c.148-.123.433-.172.556-.023");
}

.bjfaebcql {
  stop-color: var(--svg-color--e8774d, #E8774D);
}

.bsmaek8tk {
  stop-color: var(--svg-color--36c571, #36C571);
}

.btv0f_swr {
  stop-color: var(--svg-color--615f76, #615F76);
}

.cbgow0bwo {
  stop-color: var(--svg-color--e2dfe5, #E2DFE5);
}

.cc9670aeb {
  stop-color: var(--svg-color--932145, #932145);
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.codspw7xm {
  stop-color: var(--svg-color--b7a6a6, #B7A6A6);
  stop-opacity: 0;
}

.cpzd76x5u {
  fill-rule: evenodd;
  d: path("M17.142 8.274c.479.327.601.98.274 1.46c-.783 1.144-3.152 4.302-7.933 4.787c-.577.059-1.594-.319-1.653-.896s.865-1.134 1.441-1.193c3.844-.39 5.741-2.904 6.412-3.884a1.05 1.05 0 0 1 1.459-.274");
}

.cq_k1jhvn {
  stop-color: var(--svg-color--908590, #908590);
}

.cv8uymbkh {
  stop-color: var(--svg-color--8459ac, #8459AC);
}

.cyvhl4h-y {
  stop-color: var(--svg-color--d7aa3d, #D7AA3D);
}

.czabn_xgs {
  d: path("M13.554 7.913h2.154v2.668h-2.154z");
}

.d-6jagb2y {
  stop-color: var(--svg-color--ac2735, #AC2735);
}

.d2b7azbtt {
  stop-color: var(--svg-color--c57c28, #C57C28);
}

.d5hggqbjo {
  stop-color: var(--svg-color--90757e, #90757E);
}

.d8tqbz4fd {
  stop-color: var(--svg-color--df9e37, #DF9E37);
}

.da9xf6l5p {
  stop-color: var(--svg-color--e2dfe5, #E2DFE5);
  stop-opacity: 0;
}

.dicaxrbsa {
  stop-color: var(--svg-color--302a5b, #302A5B);
  stop-opacity: 0;
}

.dkvvw7m1c {
  stop-color: var(--svg-color--9c2649, #9C2649);
  stop-opacity: 0;
}

.e_--_59xk {
  d: path("m18.38 13.777l-.636-.699l4.032-2.476c1.422 1.867 1.5 3.21.836 4.273s-1.582 2.05-2.618 2.945c-.271.235-.802.362-1.359-.18c-.707-.687-1.578-1.578-2.04-2.113l1.778-1.608a.1.1 0 0 0 .007-.142");
}

.e8wau1-op {
  d: path("m11.646 6.98l-.029-.049c-.155-.247-.39-.38-.523-.297s-.115.353.04.6l.02.03z");
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.egxex7b7c {
  stop-color: var(--svg-color--5c4f86, #5C4F86);
  stop-opacity: 0;
}

.ep0khpbhu {
  fill-rule: evenodd;
  d: path("M8.851 13.448a.35.35 0 0 1-.227.44a.6.6 0 0 0-.405.457a.35.35 0 1 1-.684-.151c.05-.224.235-.768.877-.973a.35.35 0 0 1 .44.227");
}

.eper2rg6p {
  stop-color: var(--svg-color--615f76, #615F76);
  stop-opacity: 0;
}

.epfp24bqk {
  stop-color: var(--svg-color--f5b63d, #F5B63D);
}

.evhu2k4sq {
  stop-color: var(--svg-color--8c7675, #8C7675);
}

.f-r3ld20z {
  stop-color: var(--svg-color--baa3b9, #BAA3B9);
}

.f1fjk6_xs {
  stop-color: var(--svg-color--c79639, #C79639);
  stop-opacity: 0;
}

.f2dg1pymm {
  cx: 7.072px;
  cy: 24.977px;
  r: 4.555px;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
}

.f6rwhfb_k {
  stop-color: var(--svg-color--afa6a9, #AFA6A9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuvqv0efx {
  fill-rule: evenodd;
  d: path("M10.57 16.335a.55.55 0 0 1 .3.718l-3.289 8a.55.55 0 0 1-1.017-.418l3.289-8a.55.55 0 0 1 .718-.3");
}

.fv7k0--yw {
  d: path("M11.322 5.155a.35.35 0 0 1 .162-.467l1.296-.628a.35.35 0 0 1 .305.63l-1.296.628a.35.35 0 0 1-.467-.163");
}

.fwnzc4ctw {
  stop-color: var(--svg-color--5a332d, #5A332D);
}

.fy0gg3b4w {
  stop-color: var(--svg-color--d9d1df, #D9D1DF);
  stop-opacity: 0;
}

.g7aqyha-f {
  d: path("m17.898 20.866l-.3 1.98c-.067.476-.04.888.364 1.168c.102.07.238.03.307-.072l1.964-2.901a.2.2 0 0 0-.054-.278l-.952-.644z");
}

.g8r6p49_s {
  fill-rule: evenodd;
  d: path("M9.647 18.563c.101-.223.43-.466.672-.282l6.25 4.75a.55.55 0 0 1-.665.876l-6.081-4.61c-.242-.184-.305-.453-.176-.735");
}

.gxtng2bih {
  stop-color: var(--svg-color--5d5c7e, #5D5C7E);
  stop-opacity: 0;
}

.h-r_c9b7x {
  d: path("m15.295 14.645l2.64-1.61l1.208.63l-2.727 2.476c-.268-.232-.84-1.051-1.12-1.496");
}

.hla563ezk {
  d: path("M16.112 11.156c.664.625 1.363 1.586 1.671 1.969l4.243-2.18c-.586-.976-2.07-2.53-3.54-3.359c-1.718-.813-2.672 0-3.305 1.07c-.413.852.259 1.781.93 2.5");
}

.hqorccbwh {
  stop-color: var(--svg-color--3c2150, #3C2150);
}

.hs-_dnasa {
  stop-color: var(--svg-color--493b63, #493B63);
}

.huz3s4d_a {
  stop-color: var(--svg-color--c5bfcb, #C5BFCB);
}

.hv1jutayr {
  fill: var(--svg-color--414141, #414141);
  d: path("M11.878 6.446a.8.8 0 0 0-.58-.042c.267.168.302.402.46.396c.204-.008.309-.26.12-.354");
}

.hwwjun9wx {
  stop-color: var(--svg-color--bf7a28, #BF7A28);
}

.hz6yw06qq {
  fill: var(--svg-color--5b4e85, #5B4E85);
  d: path("m16.115 23.226l-1.809.861c-.43.212-.756.465-.762.956c0 .124.108.214.231.214h3.504a.2.2 0 0 0 .2-.2v-1.15z");
}

.i09bgfv6r {
  d: path("m19.204 20.133l-1.827-1.988l-.423 2.058l.923.672z");
}

.i4-r1q74d {
  stop-color: var(--svg-color--796867, #796867);
}

.icj8g3w8l {
  stop-color: var(--svg-color--e2dce7, #E2DCE7);
}

.ikszdii2u {
  stop-color: var(--svg-color--fd5a60, #FD5A60);
}

.ixfvn-b4t {
  stop-color: var(--svg-color--ffae28, #FFAE28);
}

.iy0i0xbqt {
  d: path("M12.955 11.61a.575.575 0 0 0-.575-.576H9.33a2.13 2.13 0 0 0 0 4.26h.183a.575.575 0 1 0 0-1.15H9.33a.98.98 0 1 1 0-1.96h3.05a.575.575 0 0 0 .575-.575");
}

.j3wv83dcq {
  stop-color: var(--svg-color--e59e31, #E59E31);
  stop-opacity: 0;
}

.j4w4r7dqg {
  stop-color: var(--svg-color--973c50, #973C50);
}

.j8nsw2bmy {
  stop-color: var(--svg-color--ffc727, #FFC727);
}

.jk12cqb2p {
  stop-color: var(--svg-color--f7b14e, #F7B14E);
}

.jk5eocp2v {
  stop-color: var(--svg-color--e44354, #E44354);
  stop-opacity: 0;
}

.jk9sxjbtz {
  stop-color: var(--svg-color--37c173, #37C173);
}

.jlxn3mbju {
  d: path("m15.073 4.44l-4.676 2.365a.257.257 0 0 1-.335-.079a5.6 5.6 0 0 1-.559-1.128c-.522-1.436.48-2.234.612-2.357c.19-.179.715-.62 1.839-1.025c1.319-.476 2.15.113 2.556.66c.255.344.532.86.693 1.207a.27.27 0 0 1-.13.357");
}

.jvv3w_k0n {
  stop-color: var(--svg-color--36c871, #36C871);
  stop-opacity: 0;
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kbuneegfe {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M12.726 5.076a.29.29 0 0 1 .382.149l1.45 3.307a.29.29 0 1 1-.531.233l-1.45-3.307a.29.29 0 0 1 .149-.382");
}

.kre6dibsw {
  d: path("M11.98 9.112c-.764-.74-1.39-1.926-1.641-2.39l3.439-2.037l1.815 1.677a5.2 5.2 0 0 1-.94 1.88c-.709.87-1.671 1.843-2.674.87");
}

.ktkvjmbcj {
  stop-color: var(--svg-color--605c92, #605C92);
  stop-opacity: 0;
}

.l13xg_5qx {
  fill: var(--svg-color--ffc435, #FFC435);
  fill-rule: evenodd;
  d: path("M17.142 8.274c.479.327.601.98.274 1.46c-.783 1.144-3.152 4.302-7.933 4.787c-.577.059-1.594-.319-1.653-.896s.865-1.134 1.441-1.193c3.844-.39 5.741-2.904 6.412-3.884a1.05 1.05 0 0 1 1.459-.274");
}

.l2qa6pp5f {
  stop-color: var(--svg-color--d4385b, #D4385B);
}

.l4_q8ccja {
  stop-color: var(--svg-color--ebeaed, #EBEAED);
}

.l8ufshbax {
  stop-color: var(--svg-color--eaa131, #EAA131);
}

.lc4-hmwkn {
  stop-color: var(--svg-color--4cdd80, #4CDD80);
}

.li38i4ecv {
  stop-color: var(--svg-color--af253c, #AF253C);
}

.lj25sbc6e {
  stop-color: var(--svg-color--705050, #705050);
}

.lq9yn9biw {
  stop-color: var(--svg-color--eca92d, #ECA92D);
}

.lyr5_abqg {
  stop-color: var(--svg-color--d88c28, #D88C28);
  stop-opacity: 0;
}

.m3q9izqvj {
  stop-color: var(--svg-color--5d5c7e, #5D5C7E);
}

.m9vj6ebef {
  stop-color: var(--svg-color--c79639, #C79639);
}

.meyl3ibku {
  d: path("m14.482 7.185l-.968-1.06l-.522-.92l2.236-1.05c.062.099.315.334.83.486c.644.19.932.648 1.057.883c.126.235.495 1.3-.644 1.957c-.91.525-1.705.022-1.989-.296");
}

.mikglz6lt {
  stop-color: var(--svg-color--f7b935, #F7B935);
}

.msqk4cb8o {
  stop-color: var(--svg-color--373c67, #373C67);
}

.mvvhg6bob {
  fill-rule: evenodd;
  d: path("M12.505 11.6a.5.5 0 0 1 .271.653l-2.54 6.247a.5.5 0 0 1-.924-.381l2.54-6.247a.5.5 0 0 1 .653-.272");
}

.n4-no9-8p {
  stop-color: var(--svg-color--ca7d27, #CA7D27);
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nrp3vkbjq {
  fill-rule: evenodd;
  d: path("M19.756 16.62a.55.55 0 0 0-.172.76l4.719 7.476a.55.55 0 1 0 .93-.587l-4.719-7.477a.55.55 0 0 0-.758-.171");
}

.nus19y6ts {
  stop-color: var(--svg-color--ffd359, #FFD359);
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o0tyh0b-k {
  d: path("m16.096 16l.553-.514l2.04 1.916c-.273.154-.886.464-1.03.582c-.11.091-.11.235-.11.329l-.046 5.593l-1.407-.672c-.138-.794-.42-2.708-.769-4.3c-.395-1.801.376-2.593.77-2.934");
}

.ofnkd-b6m {
  cx: 9.24px;
  cy: 13.424px;
  r: 0.885px;
}

.p-_-lbbjz {
  fill-rule: evenodd;
  d: path("M12.726 5.076a.29.29 0 0 1 .382.149l1.45 3.307a.29.29 0 1 1-.531.233l-1.45-3.307a.29.29 0 0 1 .149-.382");
}

.p1dkvx0ja {
  stop-color: var(--svg-color--8a4c56, #8A4C56);
  stop-opacity: 0;
}

.p1krpu8fj {
  stop-color: var(--svg-color--9c8f8e, #9C8F8E);
  stop-opacity: 0;
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pf-dzrbda {
  stop-color: var(--svg-color--a62f2f, #A62F2F);
}

.pfbx1ib6q {
  fill-rule: evenodd;
  d: path("M25.018 21.008a3.969 3.969 0 1 0 0 7.937a3.969 3.969 0 0 0 0-7.937m-4.969 3.969a4.969 4.969 0 1 1 9.938 0a4.969 4.969 0 0 1-9.938 0");
}

.pm89cjb4a {
  fill: var(--svg-color--414141, #414141);
  d: path("M11.457 7.088a.5.5 0 0 0-.047-.091c-.086-.138-.215-.213-.287-.168c-.072.046-.06.194.026.332a1 1 0 0 0 .055.073z");
}

.py22frtcc {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M11.877 8.588a.116.116 0 0 1 .042-.159c.101-.059.236-.206.312-.518a.116.116 0 0 1 .225.055c-.086.356-.25.565-.42.664a.116.116 0 0 1-.159-.042");
}

.pzip1rpvk {
  fill: var(--svg-color--c0b9bc, #C0B9BC);
  d: path("M12.955 11.61a.575.575 0 0 0-.575-.576H9.33a2.13 2.13 0 0 0 0 4.26h.183a.575.575 0 1 0 0-1.15H9.33a.98.98 0 1 1 0-1.96h3.05a.575.575 0 0 0 .575-.575");
}

.q11jy6bfa {
  d: path("m3.971 16.711l-1.867 1.938v11.28H30.04V13.4L23.9 4.094a2.3 2.3 0 0 0-3.84.003l-8.917 13.548a.5.5 0 0 1-.715.127L8.38 16.255c-1.32-.98-3.2-.8-4.41.457");
}

.q1us6i3dm {
  stop-color: var(--svg-color--ffc435, #FFC435);
}

.qc8cprh-k {
  d: path("m21.006 12.895l-.523-.863l1.125-.656c.968 1.312 1.343 2.296.734 2.875c-.487.462-2.87 1.723-4 2.296l2.503-2.414a1 1 0 0 0 .161-1.238");
}

.qfj7itbso {
  stop-color: var(--svg-color--8a4c56, #8A4C56);
}

.qkrvzzbyd {
  stop-color: var(--svg-color--352542, #352542);
}

.ql-kjsbnq {
  stop-color: var(--svg-color--eaa630, #EAA630);
}

.qnv5cwbcc {
  stop-color: var(--svg-color--baa3b9, #BAA3B9);
  stop-opacity: 0;
}

.r136ynjzb {
  stop-color: var(--svg-color--b3642e, #B3642E);
}

.rgol9fpyb {
  stop-color: var(--svg-color--e44354, #E44354);
}

.rl39bhb3g {
  stop-color: var(--svg-color--ffda43, #FFDA43);
}

.rrdxh2bld {
  stop-color: var(--svg-color--ffc435, #FFC435);
  stop-opacity: 0;
}

.rrfczgbhc {
  cx: 18.389px;
  cy: 24.977px;
  r: 1.027px;
}

.s2qrn4tqf {
  fill-rule: evenodd;
  d: path("M9.337 12.922a.35.35 0 0 1-.35.35c-.173 0-.436.042-.663.15c-.226.106-.37.252-.415.438a.35.35 0 1 1-.68-.166c.113-.466.462-.748.796-.906c.334-.157.7-.216.962-.216a.35.35 0 0 1 .35.35");
}

.sidw1obfr {
  fill: var(--svg-color--413354, #413354);
  d: path("m17.898 20.866l-.3 1.98c-.067.476-.04.888.364 1.168c.102.07.238.03.307-.072l1.964-2.901a.2.2 0 0 0-.054-.278l-.952-.644z");
}

.t18ofc-lq {
  stop-color: var(--svg-color--ca7e1e, #CA7E1E);
}

.t2hb3292i {
  stop-color: var(--svg-color--eda82b, #EDA82B);
}

.tm9a1_b0b {
  d: path("M17.844 7.463L20.09 6.15a.4.4 0 0 1 .51.09l1.07 1.3a.6.6 0 0 0 .927 0l1.068-1.296a.4.4 0 0 1 .515-.089l1.79 1.077l-2.07-3.138a2.3 2.3 0 0 0-3.841.003z");
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tw0q1w8vf {
  stop-color: var(--svg-color--d7cfdf, #D7CFDF);
}

.tygrts44k {
  cx: 11.132px;
  cy: 6.807px;
  r: 0.084px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.u3_kb5fuo {
  fill: var(--svg-color--2b174f, #2B174F);
  fill-rule: evenodd;
  d: path("M8.35 13.223V13.2a.572.572 0 1 0-1.145 0v.022h-.004a2.13 2.13 0 0 0 2.13 2.07h.182a.575.575 0 0 0 0-1.15H9.33a.98.98 0 0 1-.978-.92z");
}

.ue1cg0jtk {
  fill-rule: evenodd;
  d: path("M7.073 21.008a3.969 3.969 0 1 0 0 7.937a3.969 3.969 0 0 0 0-7.937m-4.97 3.969a4.969 4.969 0 1 1 9.938 0a4.969 4.969 0 0 1-9.937 0");
}

.ulnr6-8rs {
  d: path("m5.736 27.116l-3.617 2.158v.671h27.922v-.671l-3.531-2.15a2.4 2.4 0 0 0-2.43-.04l-.817.461a2 2 0 0 1-1.838.068l-1.318-.623a2.25 2.25 0 0 0-1.965.021l-1.177.587a2 2 0 0 1-1.822-.02l-1.126-.591a2 2 0 0 0-1.783-.039l-1.42.67a2 2 0 0 1-1.826-.062l-.855-.477a2.4 2.4 0 0 0-2.397.037");
}

.um4kzybeo {
  d: path("m16.115 23.226l-1.809.861c-.43.212-.756.465-.762.956c0 .124.108.214.231.214h3.504a.2.2 0 0 0 .2-.2v-1.15z");
}

.v0nd3lbsl {
  stop-color: var(--svg-color--d68b27, #D68B27);
}

.v1b11fqgs {
  cx: 13.47px;
  cy: 5.792px;
  r: 0.648px;
}

.v5ts0ibjo {
  stop-color: var(--svg-color--d8cfe2, #D8CFE2);
}

.vq765rbep {
  stop-color: var(--svg-color--ca7d27, #CA7D27);
  stop-opacity: 0;
}

.vr76p9bug {
  stop-color: var(--svg-color--7c5c60, #7C5C60);
  stop-opacity: 0;
}

.vsnbcxbze {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.02 6.699c-.072.225.06.452.13.566l.883-.51c-.514-.59-.917-.362-1.014-.056");
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wc0bxtmli {
  stop-color: var(--svg-color--38144f, #38144F);
}

.wfj_w2bhm {
  stop-color: var(--svg-color--927876, #927876);
}

.wjlh8kb9f {
  stop-color: var(--svg-color--e5435f, #E5435F);
}

.wjs_nsbuh {
  fill-rule: evenodd;
  d: path("M20.06 16.541a.55.55 0 0 1 .417.657l-1.579 7.078a.55.55 0 0 1-1.073-.24l1.578-7.078a.55.55 0 0 1 .657-.417");
}

.wm4p2nf6o {
  d: path("M18.93 26.8a1.863 1.863 0 1 1 .018-3.643l5.898.906a.927.927 0 0 1-.086 1.837z");
}

.wsobq_b1u {
  stop-color: var(--svg-color--f2b135, #F2B135);
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.xdbcf5brc {
  stop-color: var(--svg-color--96275e, #96275E);
  stop-opacity: 0;
}

.xkuwgzbmp {
  stop-color: var(--svg-color--d48d33, #D48D33);
}

.xlcjgwbhs {
  stop-color: var(--svg-color--96275e, #96275E);
}

.y16t4y92n {
  stop-color: var(--svg-color--32295b, #32295B);
}

.yveukea-t {
  stop-color: var(--svg-color--a382d4, #A382D4);
}

.yw3hdmr2n {
  stop-color: var(--svg-color--ffda43, #FFDA43);
  stop-opacity: 0;
}

.yy0ulywkr {
  d: path("M10.82 8.351c-.198-.14-.2-.297-.13-.648a.8.8 0 0 0-.057-.53l.794.99c-.11.219-.408.328-.606.188");
}

.z_jgx_kqm {
  stop-color: var(--svg-color--605c92, #605C92);
}

.zaq2lsbln {
  stop-color: var(--svg-color--352542, #352542);
  stop-opacity: 0;
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zd8v8x_xx {
  stop-color: var(--svg-color--ac2735, #AC2735);
  stop-opacity: 0;
}

.zo6cprbov {
  stop-color: var(--svg-color--ce3d5e, #CE3D5E);
}

.zqha2ybmm {
  fill: var(--svg-color--97595f, #97595F);
  d: path("m5.736 27.116l-3.617 2.158v.671h27.922v-.671l-3.531-2.15a2.4 2.4 0 0 0-2.43-.04l-.817.461a2 2 0 0 1-1.838.068l-1.318-.623a2.25 2.25 0 0 0-1.965.021l-1.177.587a2 2 0 0 1-1.822-.02l-1.126-.591a2 2 0 0 0-1.783-.039l-1.42.67a2 2 0 0 1-1.826-.062l-.855-.477a2.4 2.4 0 0 0-2.397.037");
}

.zu2bq3b1p {
  stop-color: var(--svg-color--fec940, #FEC940);
}

.zvme7yb8w {
  stop-color: var(--svg-color--a3a1a2, #A3A1A2);
}

.zy6pn1hgj {
  stop-color: var(--svg-color--ffd03c, #FFD03C);
}

</style>
