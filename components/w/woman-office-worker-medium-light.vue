<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHnTEkc)"><path fill="url(#ijj1hQc)" clip-rule="evenodd" class="z3yvuwo_p"/><path fill="url(#iUuPZfe)" clip-rule="evenodd" class="z3yvuwo_p"/><path fill="url(#iBuvIge)" clip-rule="evenodd" class="z3yvuwo_p"/><path fill="url(#irL41Ad)" clip-rule="evenodd" class="z3yvuwo_p"/><path fill="url(#i4feX3d)" clip-rule="evenodd" class="z3yvuwo_p"/><path fill="url(#iHfcBjc)" clip-rule="evenodd" class="z3yvuwo_p"/><path fill="url(#ihGOIRd)" clip-rule="evenodd" class="z3yvuwo_p"/><path fill="url(#ilA3rpe)" clip-rule="evenodd" class="z3yvuwo_p"/><path fill="url(#iZxSjOb)" clip-rule="evenodd" class="z3yvuwo_p"/><path fill="url(#ivZNgop)" clip-rule="evenodd" class="z3yvuwo_p"/></g><path fill="url(#i4cX3ub)" class="zvvx29b3a"/><path fill="url(#it7b6fc)" class="zvvx29b3a"/><g filter="url(#i0ECtLN)"><path class="mqs7o2bnn"/></g><g filter="url(#ilPLRPb)"><path class="yxq4dmbrn"/></g><path fill="url(#ivPn6qc)" class="cho8x9bqp"/><path fill="url(#iJ17IGb)" class="cho8x9bqp"/><path fill="url(#iup2Oab)" class="cho8x9bqp"/><path fill="url(#iDnE1ae)" class="pagefvi7k"/><path fill="url(#iqJSihd)" class="pagefvi7k"/><g filter="url(#iSFMRgc)"><path fill="url(#i90cFFb)" class="ym90ysber"/><path fill="url(#iWv4KGe)" class="ym90ysber"/><path fill="url(#i4omEXd)" class="ym90ysber"/></g><path fill="url(#iBhXxcI)" class="ym90ysber"/><path fill="url(#iIwLmve)" class="ym90ysber"/><g filter="url(#iCjwIec)"><path fill="url(#id8yNzd)" class="jlhav--js"/></g><g filter="url(#ihz6Umc)"><path class="oou4fxxcq"/><path fill="url(#iJiQQFc)" class="j-1m-y7it"/></g><path fill="url(#iCCkCPe)" class="msod-5bzd"/><path fill="url(#iipiZdd)" class="msod-5bzd"/><path fill="url(#i9cP0Je)" class="vhf08lbkn"/><path fill="url(#iTY9itb)" class="j-3h25m7h"/><path fill="url(#i9s8iwe)" class="j-3h25m7h"/><path fill="url(#irnvbJb)" class="j-3h25m7h"/><path fill="url(#iNJnJpb)" class="pzoizbbeg"/><path fill="url(#iVDZQ0c)" class="sgl1asp0z"/><path fill="url(#iG6p9Eb)" class="cyqispo_i"/><g filter="url(#ifNNR9V)"><path fill="url(#iisaO2d)" class="x7dftb6-n"/></g><g filter="url(#iBqT7ve)"><path fill="url(#iEiHBAe)" class="g4lqugsoo"/><path fill="url(#iyiOvSd)" class="g4lqugsoo"/></g><g filter="url(#iLysloY)"><path class="fi0xkwyti"/><path fill="url(#iLUopcd)" class="n-m3p4b6s"/></g><g filter="url(#iS8Ybwn)"><path class="bwlh3lbtn"/><path fill="url(#i7sk5qb)" class="cxvol-cmc"/></g><g filter="url(#iaunZRj)"><path fill="url(#ihVsCAe)" class="twkg8g_iz"/><path fill="url(#injJAqh)" class="twkg8g_iz"/><path fill="url(#iH5oVcb)" class="twkg8g_iz"/><path fill="url(#i7Kj1rd)" class="twkg8g_iz"/><path fill="url(#iezFoIc)" class="twkg8g_iz"/><path fill="url(#i3LRtYc)" class="twkg8g_iz"/><path fill="url(#iHr3Std)" class="twkg8g_iz"/></g><path fill="url(#iqk5YGc)" class="cc30shb7x"/><path fill="url(#iKl9Arc)" class="cc30shb7x"/><g filter="url(#ifSc3rc)"><path class="wtjgu_36z"/></g><g filter="url(#iOYoehb)"><path class="vue0stbmb"/><path fill="url(#i4Wfesd)" class="f73do2b6q"/><path fill="url(#iOOsXgZ)" class="f73do2b6q"/><path fill="url(#iM0zP3d)" class="f73do2b6q"/></g><path fill="url(#iHZibbc)" class="f73do2b6q"/><path fill="url(#iBIdPhd)" class="f73do2b6q"/><path stroke="url(#i5RbHue)" class="iky_hac6b"/><g filter="url(#ixWieIc)"><path class="n9gcyccdk"/></g><g filter="url(#iT9N0uf)"><path class="mlxug5yba"/></g><g filter="url(#iTPWJgc)"><path class="rnb-cpd_b"/></g><g filter="url(#ix9mCjd)"><path clip-rule="evenodd" class="x567axvgs"/></g><path class="dqq-jeb1v"/><path fill="url(#ifv7Cqd)" class="e-ajp5bsi"/><path class="xh097abjo"/><g filter="url(#iaj3vDc)"><path class="cho1n8glu"/><path fill="url(#iV0WuVc)" class="l_qjyjicn"/></g><g filter="url(#iPrDTNd)"><path fill="url(#iSDF4rb)" class="yh5oskbpk"/></g><path class="n3xrbm4jh"/><path fill="url(#iKO5gob)" class="a8hzucc1j"/><path class="qb5qlvtvm"/><g filter="url(#iDCqIJd)"><path fill="url(#im9QwZc)" class="w9nfyvbnp"/></g><g filter="url(#imEzmMe)"><ellipse transform="rotate(-27.914 13.344 10.227)" class="hzv7idbzu"/><ellipse fill="url(#iJNU6Dc)" transform="rotate(-27.914 13.344 10.227)" class="u5wq8tb-s"/></g><g filter="url(#ibjjEoe)"><path class="f-i4vtbib"/></g><g filter="url(#iWYF8ac)"><path class="q5g88fluk"/></g><g filter="url(#ia2kbIe)"><path fill="url(#iZ6Xrqg)" class="nnzdxtq9c"/><path fill="url(#ikrf1Oe)" class="nnzdxtq9c"/></g><g filter="url(#iYX8cNs)"><path fill="url(#iAZlYUc)" class="lq4zr4vgf"/><path fill="url(#iGJI8fe)" class="lq4zr4vgf"/><path fill="url(#iECM9md)" class="lq4zr4vgf"/></g><g filter="url(#i6THZnd)"><path stroke="url(#ixcaMAb)" class="h5kq2lb5r"/></g><defs><radialGradient id="iUuPZfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.74318 -3.62044 8.25485 3.97456 20.49 16.74)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iBuvIge" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 3.046 11.73)scale(5.77873 5.40927)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="irL41Ad" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 3.994 9.017)scale(3.98975 4.91117)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="i4feX3d" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.579 8.42)scale(1.78101 1.61886)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iHfcBjc" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.276 4.192)scale(2.38706 3.50899)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="ihGOIRd" cx="0" cy="0" r="1" gradientTransform="matrix(2.16229 3.16788 -5.52839 3.77349 11.959 3.347)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="ilA3rpe" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.51 7.271)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iZxSjOb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.306 10.069)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="ivZNgop" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15113 1.34089 -2.13644 -5.02072 23.038 12.85)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="it7b6fc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4313 6.37009 0 22.995 25.09)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="m5bm-ccxd"/><stop offset="1" class="q8ootib3t"/></radialGradient><radialGradient id="ivPn6qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1215 -4.59696 0 16 22.663)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="wdy63qb5p"/><stop offset="1" class="gkzmut59n"/></radialGradient><radialGradient id="iDnE1ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3135 1.68433 0 25 29.598)" gradientUnits="userSpaceOnUse"><stop class="omh3jbc5e"/><stop offset="1" class="g1k32m_rh"/></radialGradient><radialGradient id="i4omEXd" cx="0" cy="0" r="1" gradientTransform="rotate(126.18 2.804 11.467)scale(2.59394 3.59462)" gradientUnits="userSpaceOnUse"><stop class="yfhz1ybyq"/><stop offset="1" class="kyt4h2bsk"/></radialGradient><radialGradient id="iIwLmve" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 -.3125 .15358 .53752 11.395 19.355)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="som6k-b6q"/><stop offset="1" class="pc2b66ykc"/></radialGradient><radialGradient id="iCCkCPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -4.3769 0 16 18.113)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="ft6yvtbqk"/><stop offset="1" class="i_25dj3ib"/></radialGradient><radialGradient id="iipiZdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 6.81546 0 16 20.61)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="kx98i3bkm"/><stop offset=".876" class="mf716dhmi"/></radialGradient><radialGradient id="iTY9itb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -3.45478 0 15.983 21.003)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lv0iykbih"/><stop offset=".94" class="s3tb_6b2n"/></radialGradient><radialGradient id="iNJnJpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3026 -2.71576 0 16.03 16.859)" gradientUnits="userSpaceOnUse"><stop class="ne16de0uk"/><stop offset="1" class="zto3p_lef"/></radialGradient><radialGradient id="iEiHBAe" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 19.837 11.359)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iyiOvSd" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 20.859 9.138)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iLUopcd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 41.36 -51.374)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="i7sk5qb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 11.13 10.92)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="ihVsCAe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.656 10.383)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="injJAqh" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.697 11.08)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iH5oVcb" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.618 17.165)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="i7Kj1rd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.4375 -10.082 0 15.797 10.095)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="xzv8str6f"/><stop offset=".944" class="kr3293b1o"/></radialGradient><radialGradient id="iezFoIc" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.791 6.908)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="i3LRtYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 18.098 9.964)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iHr3Std" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 13.879 10.051)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iqk5YGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 20.892 11.452)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iKl9Arc" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 13.297 4.877)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="i4Wfesd" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.581 12.178)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iBIdPhd" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.148 8.488)scale(1.57489 2.10944)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="ifv7Cqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.98 10.323)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iV0WuVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.75 10.407)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKO5gob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.615 10.323)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iJNU6Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.853 -1.29)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZ6Xrqg" cx="0" cy="0" r="1" gradientTransform="matrix(1.93486 2.6818 -5.32876 3.84458 9.84 4.671)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="ikrf1Oe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87735 2.48068 -1.9455 -1.47233 13.082 4.906)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iAZlYUc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11195 4.39145 -6.24446 -3.00311 17.708 2.995)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iGJI8fe" cx="0" cy="0" r="1" gradientTransform="matrix(-.8568 3.20722 -5.72497 -1.5294 18.11 4.168)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iECM9md" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.377 -.21)scale(7.21046 6.45439)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><filter id="iHnTEkc" width="15.268" height="15.768" x="8.288" y="1.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2103"/></filter><filter id="i0ECtLN" width="6.556" height="14.595" x="9.212" y="15.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".5"/></filter><filter id="ilPLRPb" width="3.95" height="13.362" x="17.96" y="15.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".375"/></filter><filter id="iSFMRgc" width="2.897" height="14" x="10.503" y="15.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2103"/></filter><filter id="iCjwIec" width="2.734" height="2.883" x="14.624" y="17.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2103"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2103" result="effect2_innerShadow_4002_2103"/></filter><filter id="ihz6Umc" width="2.902" height="14.05" x="18.61" y="15.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2103"/></filter><filter id="ifNNR9V" width="3.368" height="3.468" x="9.502" y="9.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2103"/></filter><filter id="iBqT7ve" width="3.218" height="3.468" x="19.015" y="9.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2103"/></filter><filter id="iLysloY" width="3.148" height="3.148" x="19.05" y="9.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".25"/></filter><filter id="iS8Ybwn" width="2.948" height="2.948" x="9.657" y="9.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".2"/></filter><filter id="iaunZRj" width="10.191" height="11.127" x="10.701" y="6.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2103"/></filter><filter id="ifSc3rc" width="2.877" height="3.682" x="14.196" y="9.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".25"/></filter><filter id="iOYoehb" width="2.377" height="3.182" x="14.608" y="10.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".125"/></filter><filter id="ixWieIc" width="3.001" height="1.285" x="16.739" y="9.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2103"/></filter><filter id="iT9N0uf" width="3.001" height="1.285" x="11.854" y="9.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2103"/></filter><filter id="iTPWJgc" width="2.453" height="1.091" x="11.989" y="8.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2103"/></filter><filter id="ix9mCjd" width="2.453" height="1.091" x="17.406" y="8.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2103"/></filter><filter id="iaj3vDc" width=".787" height=".696" x="17.245" y="9.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".05"/></filter><filter id="iPrDTNd" width=".891" height=".913" x="18.085" y="9.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".1"/></filter><filter id="iDCqIJd" width=".986" height="1.04" x="13.642" y="9.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".1"/></filter><filter id="imEzmMe" width=".913" height=".705" x="12.887" y="9.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".05"/></filter><filter id="ibjjEoe" width="2.661" height="1.378" x="17.236" y="8.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".2"/></filter><filter id="iWYF8ac" width="2.661" height="1.378" x="11.785" y="8.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".2"/></filter><filter id="ia2kbIe" width="4.287" height="5.25" x="9.538" y="3.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".25"/></filter><filter id="iYX8cNs" width="8.914" height="5.78" x="12.48" y="2.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".125"/></filter><filter id="i6THZnd" width="1.145" height="2.31" x="12.606" y="4.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2103" stdDeviation=".1"/></filter><linearGradient id="ijj1hQc" x1="20.49" x2="13.685" y1="3.967" y2="16.572" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="i4cX3ub" x1="16" x2="16" y1="15.91" y2="30.847" gradientUnits="userSpaceOnUse"><stop class="hac9w68gp"/><stop offset="1" class="u61ykmvtc"/></linearGradient><linearGradient id="iJ17IGb" x1="18.903" x2="17.059" y1="24.91" y2="24.91" gradientUnits="userSpaceOnUse"><stop class="ugh29hhiz"/><stop offset="1" class="knib4pb5u"/></linearGradient><linearGradient id="iup2Oab" x1="15.591" x2="15.669" y1="17.457" y2="21.347" gradientUnits="userSpaceOnUse"><stop class="ft2atdbel"/><stop offset="1" class="r8964-bmu"/></linearGradient><linearGradient id="iqJSihd" x1="23" x2="23.744" y1="29.085" y2="29.061" gradientUnits="userSpaceOnUse"><stop offset=".276" class="alwwvg18b"/><stop offset="1" class="r8-nbsf4i"/></linearGradient><linearGradient id="i90cFFb" x1="11.902" x2="11.902" y1="15.688" y2="29.588" gradientUnits="userSpaceOnUse"><stop class="j-er45bzw"/><stop offset=".524" class="iwz00abqx"/></linearGradient><linearGradient id="iWv4KGe" x1="13.671" x2="13.05" y1="22.148" y2="22.148" gradientUnits="userSpaceOnUse"><stop class="recxkftoe"/><stop offset="1" class="btkjyionj"/></linearGradient><linearGradient id="iBhXxcI" x1="11.902" x2="12.839" y1="25.564" y2="25.163" gradientUnits="userSpaceOnUse"><stop offset=".196" class="yqlqjsfuk"/><stop offset="1" class="c8t-c_brq"/></linearGradient><linearGradient id="id8yNzd" x1="15.988" x2="15.988" y1="18.581" y2="20.566" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mu96iuqwe"/><stop offset="1" class="p-sb3ibac"/></linearGradient><linearGradient id="iJiQQFc" x1="18.71" x2="20.111" y1="21.195" y2="21.195" gradientUnits="userSpaceOnUse"><stop offset=".093" class="fxp5v2b6t"/><stop offset="1" class="zm9c_pbne"/></linearGradient><linearGradient id="i9cP0Je" x1="9.452" x2="7.02" y1="23.605" y2="23.605" gradientUnits="userSpaceOnUse"><stop class="rpmno-b9y"/><stop offset="1" class="a9ts2kezv"/></linearGradient><linearGradient id="i9s8iwe" x1="14.606" x2="14.899" y1="24.468" y2="24.507" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="irnvbJb" x1="17.411" x2="17.012" y1="24.285" y2="24.332" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="iVDZQ0c" x1="8.862" x2="23.238" y1="15.927" y2="15.927" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iG6p9Eb" x1="8.862" x2="23.238" y1="15.897" y2="15.897" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iisaO2d" x1="9.502" x2="12.461" y1="11.007" y2="11.007" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iOOsXgZ" x1="14.751" x2="15.605" y1="12.196" y2="12.3" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iM0zP3d" x1="15.797" x2="15.797" y1="13.05" y2="12.44" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iHZibbc" x1="15.875" x2="15.875" y1="13.024" y2="12.884" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="i5RbHue" x1="15.068" x2="15.521" y1="14.527" y2="13.655" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="iSDF4rb" x1="18.757" x2="18.443" y1="10.377" y2="10.57" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="im9QwZc" x1="14.359" x2="14.045" y1="10.377" y2="10.57" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixcaMAb" x1="12.906" x2="13.45" y1="4.722" y2="5.995" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-office-worker-medium-light" /></template>
<style>
.a8hzucc1j {
  d: path("M13.613 9.846a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.a9ts2kezv {
  stop-color: var(--svg-color--584a7e, #584A7E);
  stop-opacity: 0;
}

.alwwvg18b {
  stop-color: var(--svg-color--504176, #504176);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.btkjyionj {
  stop-color: var(--svg-color--553a63, #553A63);
  stop-opacity: 0;
}

.bwlh3lbtn {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.13 11.994a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c8t-c_brq {
  stop-color: var(--svg-color--594c7d, #594C7D);
  stop-opacity: 0;
}

.cc30shb7x {
  d: path("M10.71 9.657h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439q.024-.008.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.082.088 1.135 1.333l-.118 3.073c-.124 2.802-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.cho1n8glu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.915 10.034c.064.085-.069.19-.22.302c-.151.113-.263.193-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.cho8x9bqp {
  d: path("M18.71 15.718h-5.42v13.89h5.42z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cxvol-cmc {
  d: path("M11.13 11.994a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.cyqispo_i {
  d: path("M16.072 15.898h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dqq-jeb1v {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.188 9.574c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.e-ajp5bsi {
  d: path("M17.981 9.846a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.f-i4vtbib {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.737 8.547c.322-.078 1.124-.039 1.66.345");
}

.f73do2b6q {
  d: path("m15.415 10.559l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.fi0xkwyti {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.624 11.994a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ft2atdbel {
  stop-color: var(--svg-color--877f93, #877F93);
}

.ft5dv1b6b {
  fill: none;
}

.ft6yvtbqk {
  stop-color: var(--svg-color--cac3d3, #CAC3D3);
}

.fxp5v2b6t {
  stop-color: var(--svg-color--453d68, #453D68);
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g1k32m_rh {
  stop-color: var(--svg-color--6d6193, #6D6193);
}

.g4lqugsoo {
  d: path("M20.624 12.529a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gkzmut59n {
  stop-color: var(--svg-color--a89cb3, #A89CB3);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h5kq2lb5r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.906 4.378c.023.243.234 1.156.544 1.71");
}

.hac9w68gp {
  stop-color: var(--svg-color--534973, #534973);
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.hzv7idbzu {
  cx: 13.344px;
  cy: 10.227px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.i_25dj3ib {
  stop-color: var(--svg-color--a093a3, #A093A3);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.iky_hac6b {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.399 13.443a3 3 0 0 0 1.398.338c.518 0 .994-.123 1.398-.338a.205.205 0 0 1 .247.04c.059.063.08.16.022.25m-3.065-.29l3.023.263m-3.023-.263a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248m.268-.291l-.227.263m3.292.027l-.042-.027m.042.027l-.042-.027m.042.027a1.982 1.982 0 0 1-3.333 0m3.29-.027a1.932 1.932 0 0 1-3.249 0m-.041.028l.041-.028m-.041.028l.041-.028");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iwz00abqx {
  stop-color: var(--svg-color--5f5289, #5F5289);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j-1m-y7it {
  d: path("m21.22 20.718l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.j-3h25m7h {
  d: path("M15.505 20.708a.25.25 0 0 0-.247.212l-1.328 8.668h4.11l-1.318-8.667a.25.25 0 0 0-.247-.213z");
}

.j-er45bzw {
  stop-color: var(--svg-color--544a76, #544A76);
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jlhav--js {
  d: path("m16.01 17.925l-1.24 1.204a.15.15 0 0 0-.033.168l.547 1.26a.25.25 0 0 0 .23.151h.952c.1 0 .19-.06.23-.151l.55-1.28a.15.15 0 0 0-.033-.167z");
}

.jybxgogov {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.knib4pb5u {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
  stop-opacity: 0;
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.kr3293b1o {
  stop-color: var(--svg-color--aa6189, #AA6189);
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kx98i3bkm {
  stop-color: var(--svg-color--837a8d, #837A8D);
  stop-opacity: 0;
}

.kyt4h2bsk {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
  stop-opacity: 0;
}

.l_qjyjicn {
  d: path("M17.915 10.034c.064.085-.069.19-.22.302c-.151.113-.263.193-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lq4zr4vgf {
  d: path("M15.194 3.13c-1.133-.25-2.347.955-2.464 1.374c1.542 3.62 3.91 3.275 6.537 2.983c1.572-.175 1.743.542 1.877.889c-.436-4.057-3.37-4.677-5.95-5.247");
}

.lv0iykbih {
  stop-color: var(--svg-color--56406d, #56406D);
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.m5bm-ccxd {
  stop-color: var(--svg-color--7b74a6, #7B74A6);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mf716dhmi {
  stop-color: var(--svg-color--544a5f, #544A5F);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mlxug5yba {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.655 10.35c-.265-.466-.669-.835-1.537-.835c-.38 0-.747.106-1.073.37c-.269.216-.233.494-.025.598l.556.318c.652-.21 1.373-.24 2.079-.45");
}

.mqs7o2bnn {
  fill: var(--svg-color--41355c, #41355C);
  d: path("M13.419 16.447c-.513 0-1.296-.03-1.77.166l-1.38 2.724c-.09.19.06.41.27.41h1.55c.24 0 .35.29.19.45l-1.78 1.343c-.26.26-.36.65-.23 1l2.912 6.5l1.587-1.116l-1.34-11.477z");
}

.msod-5bzd {
  d: path("M16 14.655h-2.71v4.74c0 .31.36.49.61.29l2.1-1.392l2.1 1.392c.25.2.61.02.61-.29v-4.74z");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mu96iuqwe {
  stop-color: var(--svg-color--4b375e, #4B375E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n-m3p4b6s {
  d: path("M20.624 11.994a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.n3xrbm4jh {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.406 9.574c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.n9gcyccdk {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.94 10.35c.264-.466.668-.835 1.536-.835c.38 0 .747.106 1.073.37c.27.216.233.494.025.598l-.556.318c-.652-.21-1.373-.24-2.079-.45");
}

.ne16de0uk {
  stop-color: var(--svg-color--ad7270, #AD7270);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nnzdxtq9c {
  d: path("M10.903 4.906c.62-.553 1.517-.559 2.02-.47l.402 1.291c-.257-.039-.486.05-.679.235c-.453 1.676-2.162 1.425-2.498 2.682c-.15-1.492-.318-2.783.755-3.738");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omh3jbc5e {
  stop-color: var(--svg-color--776d9f, #776D9F);
}

.oou4fxxcq {
  fill: var(--svg-color--605890, #605890);
  d: path("m21.22 20.718l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.p-sb3ibac {
  stop-color: var(--svg-color--483b55, #483B55);
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pagefvi7k {
  d: path("M23 17.616v11.982h4v-3.5a10.98 10.98 0 0 0-4-8.482");
}

.pc2b66ykc {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pzoizbbeg {
  d: path("M14.045 16.488c.02.213.205.69.746 1.055c.214.143 1.213.628 1.193.618c.156-.078.807-.298 1.284-.619c.54-.363.725-.84.746-1.054l-1.985-.953z");
}

.q5g88fluk {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.946 8.547c-.323-.078-1.125-.039-1.661.345");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.q8ootib3t {
  stop-color: var(--svg-color--5f5490, #5F5490);
  stop-opacity: 0;
}

.qb5qlvtvm {
  fill: var(--svg-color--000, #000);
  d: path("M14.124 10.738a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.745h.904a.5.5 0 0 0 .06-.235");
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r8-nbsf4i {
  stop-color: var(--svg-color--504176, #504176);
  stop-opacity: 0;
}

.r8964-bmu {
  stop-color: var(--svg-color--877f93, #877F93);
  stop-opacity: 0;
}

.recxkftoe {
  stop-color: var(--svg-color--3e305b, #3E305B);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rnb-cpd_b {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.4 9.142l-.005.003a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.01-.006a2 2 0 0 1 .147-.076a3 3 0 0 1 .41-.162c.34-.109.816-.2 1.329-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.rop63gbyj {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
  stop-opacity: 0;
}

.rpmno-b9y {
  stop-color: var(--svg-color--41375c, #41375C);
}

.s3tb_6b2n {
  stop-color: var(--svg-color--3d3247, #3D3247);
}

.sgl1asp0z {
  d: path("M16.402 15.898c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.som6k-b6q {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.t5ewf8b-q {
  stop-color: var(--svg-color--ce9591, #CE9591);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.twkg8g_iz {
  d: path("m10.712 9.392l-.01-.306c.02-.949.574-1.316.81-1.439q.024-.008.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.082.088 1.135 1.333l-.118 3.073c-.124 2.802-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.u5wq8tb-s {
  cx: 13.344px;
  cy: 10.227px;
  rx: 0.39px;
  ry: 0.197px;
}

.u61ykmvtc {
  stop-color: var(--svg-color--584982, #584982);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.ugh29hhiz {
  stop-color: var(--svg-color--7a6c85, #7A6C85);
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vhf08lbkn {
  d: path("M7.032 29.598H8.97V17.634a11 11 0 0 0-3.656 5.843a11 11 0 0 0-.304 2.631l.02 3.49z");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vue0stbmb {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.415 10.559l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w9nfyvbnp {
  d: path("M14.428 10.634c0-.289-.234-.481-.298-.54l-.288.28l.177.36z");
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wdy63qb5p {
  stop-color: var(--svg-color--c6bbd1, #C6BBD1);
}

.wtjgu_36z {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.404 10.697l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.x567axvgs {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m19.529 8.685l-.138.23za.268.268 0 0 1-.276.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.109a3.3 3.3 0 0 1 .526.22l.033.018l.009.006l.003.002z");
}

.x7dftb6-n {
  d: path("M11.111 12.529a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.xh097abjo {
  fill: var(--svg-color--000, #000);
  d: path("M17.47 10.738c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.745h-.904a.46.46 0 0 1-.061-.235");
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xzv8str6f {
  stop-color: var(--svg-color--bf7e8a, #BF7E8A);
  stop-opacity: 0;
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yfhz1ybyq {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
}

.yh5oskbpk {
  d: path("M18.776 10.62a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.ym90ysber {
  d: path("M13.29 15.688h-.85c-.18.06-.36.13-.53.2l-1.27 2.69c-.09.19.06.41.27.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01v-13.9z");
}

.yqlqjsfuk {
  stop-color: var(--svg-color--55477c, #55477C);
}

.yxq4dmbrn {
  fill: var(--svg-color--463d68, #463D68);
  d: path("m20.905 20.78l-1.19-.829a.23.23 0 0 1 .166-.393h.919a.252.252 0 0 0 .227-.358l-1.076-2.291a8 8 0 0 0-.646-.236h-.595v11.862l2.404-6.872a.85.85 0 0 0-.21-.884");
}

.z3yvuwo_p {
  fill-rule: evenodd;
  d: path("M22.982 12.33c.213-.435.324-.921.324-1.427c0-.468-.096-.906-.268-1.306h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.77V7.3A3.3 3.3 0 0 0 18.934 4a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001A3.3 3.3 0 0 0 9.36 7.3v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.51.51 0 0 1 0-.455m-12.26-2.673h-.012l1.198 2.356c.124 2.802 1.218 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197C20.84 7.888 19.938 7.8 19.757 7.8h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.292 1.275c-.236.123-.79.49-.81 1.439l.01.306z");
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zm9c_pbne {
  stop-color: var(--svg-color--625a91, #625A91);
  stop-opacity: 0;
}

.zto3p_lef {
  stop-color: var(--svg-color--b68375, #B68375);
}

.zvvx29b3a {
  d: path("M16 15.098c-6.08 0-11 4.92-11 11v3.5h22v-3.5c0-6.07-4.93-11-11-11");
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
