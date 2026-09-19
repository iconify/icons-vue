<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iERWeKe)"><path fill="url(#iiUWJwd)" clip-rule="evenodd" class="aq9438b-n"/><path fill="url(#i5ChVtb)" clip-rule="evenodd" class="aq9438b-n"/><path fill="url(#iW5LfVZ)" clip-rule="evenodd" class="aq9438b-n"/><path fill="url(#ii4194d)" clip-rule="evenodd" class="aq9438b-n"/><path fill="url(#ih75Wrc)" clip-rule="evenodd" class="aq9438b-n"/><path fill="url(#i9YIQ4b)" clip-rule="evenodd" class="aq9438b-n"/><path fill="url(#iDXn2Sd)" clip-rule="evenodd" class="aq9438b-n"/><path fill="url(#i2ENOMh)" clip-rule="evenodd" class="aq9438b-n"/><path fill="url(#iOGRHGb)" clip-rule="evenodd" class="aq9438b-n"/><path fill="url(#itTBi8m)" clip-rule="evenodd" class="aq9438b-n"/></g><path fill="url(#iKCxBFc)" clip-rule="evenodd" class="aq9438b-n"/><path fill="url(#iVKvHpd)" clip-rule="evenodd" class="aq9438b-n"/><path fill="url(#imo41Ac)" clip-rule="evenodd" class="aq9438b-n"/><g filter="url(#ifaPWue)"><path fill="url(#i1gsgse)" class="wxfwszbys"/><path fill="url(#i8XiPOe)" class="wxfwszbys"/><path fill="url(#iJls1sc)" class="wxfwszbys"/><path fill="url(#iKpeIKe)" class="wxfwszbys"/><path fill="url(#iW1L1sc)" class="wxfwszbys"/><path fill="url(#iUkKPae)" class="wxfwszbys"/><path fill="url(#is3wVfe)" class="wxfwszbys"/><path fill="url(#isUixxc)" class="wxfwszbys"/></g><g filter="url(#izTvlDz)"><path fill="url(#iMgi8Bd)" class="oj983wuvi"/></g><g filter="url(#iqsQBwc)"><path class="ipzmhfxzs"/><path fill="url(#iEaER3b)" class="b9v1u1-_l"/></g><path fill="url(#iq5gNhe)" class="alphoubkv"/><path fill="url(#i6eNipw)" class="alphoubkv"/><g filter="url(#iQCDofc)"><path fill="url(#imaEE9b)" class="pp54f-29q"/></g><g filter="url(#iaJkzpe)"><path fill="url(#i18nY5d)" class="pu9u9k2rp"/></g><g filter="url(#iQBjWcb)"><path stroke="url(#iGhuaVR)" class="tl8qpbpot"/></g><g filter="url(#iergBfb)"><path stroke="url(#ivyf0Yb)" class="raxopjbju"/></g><g filter="url(#i4Ik08d)"><path stroke="url(#ia9Xs4h)" class="tt72geb2m"/></g><path fill="url(#iQbJMEb)" class="e_-jof7ml"/><path fill="url(#i19yhLx)" class="m_1u_6brl"/><g filter="url(#i8PSOqc)"><path fill="url(#iMlZagb)" class="nte9-tbqd"/></g><g filter="url(#iy8nbJb)"><path fill="url(#ibIdkDc)" class="mltizig3o"/></g><g filter="url(#iGNE9Rb)"><path fill="url(#iWXTwPf)" class="bl4ekh57d"/><path fill="url(#ioRZxMd)" class="bl4ekh57d"/></g><g filter="url(#iJJRCzd)"><path class="jci5uhbmn"/><path fill="url(#iWnLPxb)" class="o9xuojmag"/></g><g filter="url(#iEQXqAc)"><path class="kspdwq88h"/><path fill="url(#iDdXcbc)" class="yoj1htbxp"/></g><g filter="url(#iQUB66K)"><path fill="url(#iecVHQY)" class="h5p3r6p8s"/><path fill="url(#ik0rRWb)" class="h5p3r6p8s"/><path fill="url(#iVuOSHb)" class="h5p3r6p8s"/><path fill="url(#iHFyGqd)" class="h5p3r6p8s"/><path fill="url(#iAUiysc)" class="h5p3r6p8s"/><path fill="url(#ionbUIV)" class="h5p3r6p8s"/><path fill="url(#iAgXbUc)" class="h5p3r6p8s"/></g><path fill="url(#i4Znxec)" class="lzwbf3bxk"/><path fill="url(#iUBe9LJ)" class="lzwbf3bxk"/><g filter="url(#iOcVeGh)"><path class="psox_sbvx"/></g><g filter="url(#i2TI17c)"><path class="ujtedzbaf"/><path fill="url(#iwJ78Vc)" class="bn1ilc5ze"/><path fill="url(#ilEYc5c)" class="bn1ilc5ze"/><path fill="url(#iMlgdsc)" class="bn1ilc5ze"/></g><g filter="url(#inUE9ce)"><path stroke="url(#iCpxGCd)" class="i2lbcbbob"/></g><path class="xyfahlb3n"/><g filter="url(#iChn6ni)"><path class="vp-eqebay"/></g><g filter="url(#iURC2CN)"><path class="ewoysi9vh"/></g><g filter="url(#iR0n2ic)"><path class="nw0ip4b-d"/></g><g filter="url(#iDpeKZd)"><path clip-rule="evenodd" class="tc029nbmi"/></g><path class="cmjixrfdv"/><path fill="url(#ieOUrHc)" class="w270qkb5v"/><path class="rhkp4jvnd"/><g filter="url(#ipgzP5c)"><path class="xckf85eqw"/><path fill="url(#ic0BPtd)" class="kj0gkk02b"/></g><g filter="url(#iw58asb)"><path fill="url(#ijgb1Pb)" class="huvgmobvs"/></g><path class="dvdov_bqj"/><path fill="url(#ixrnnad)" class="wtf0g401w"/><path class="njw83hasq"/><g filter="url(#iI1yxOH)"><path fill="url(#it4gQYb)" class="k8vkv0beg"/></g><g filter="url(#i0hVT5b)"><ellipse transform="rotate(-27.914 16.063 8.885)" class="si1cfpbnk"/><ellipse fill="url(#iWFkSnd)" transform="rotate(-27.914 16.063 8.885)" class="mn-ke3wbb"/></g><g filter="url(#i1JuWIe)"><path class="us6butbbp"/></g><g filter="url(#iqdaVjb)"><path class="om93qlvyw"/></g><g filter="url(#iDZQRHc)"><path fill="url(#iMD41LK)" class="hvdam5ygl"/><path fill="url(#izqcgNd)" class="hvdam5ygl"/></g><g filter="url(#int8Wfb)"><path fill="url(#iH03EHj)" class="bschqpbud"/><path fill="url(#iyCVx1b)" class="bschqpbud"/><path fill="url(#i0gSAmI)" class="bschqpbud"/></g><g filter="url(#i5sFEwc)"><path stroke="url(#iF9STDG)" class="a8v6ombcy"/></g><defs><radialGradient id="i5ChVtb" cx="0" cy="0" r="1" gradientTransform="matrix(1.52538 -3.16811 7.22351 3.47798 22.317 14.584)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iW5LfVZ" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 4.882 11.794)scale(5.05675 4.73345)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="ii4194d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75743 2.14142 -2.63598 -3.39424 15.482 11.915)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="ih75Wrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.89477 1.27606 -1.15987 -.8133 13.971 9.686)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="i9YIQ4b" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 7.682 3.395)scale(2.08883 3.07059)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iDXn2Sd" cx="0" cy="0" r="1" gradientTransform="matrix(1.89214 2.7721 -4.8377 3.30203 14.851 2.866)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="i2ENOMh" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 10.529 7.296)scale(1.43259 2.00202)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iOGRHGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61332 .46935 -1.02125 -3.51036 24.781 8.747)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="itTBi8m" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75744 1.17336 -1.86952 -4.39344 24.547 11.182)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iKCxBFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15623 8.78126 -13.88327 -1.82801 20.195 7.886)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="l6yuh0bov"/><stop offset="1" class="s304qo8pr"/></radialGradient><radialGradient id="iVKvHpd" cx="0" cy="0" r="1" gradientTransform="rotate(-173.618 8.421 6.463)scale(4.77962)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="v5dmk1bjv"/><stop offset="1" class="h249pabun"/></radialGradient><radialGradient id="imo41Ac" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 1.8125 -2.17328 2.54798 21.228 11.948)" gradientUnits="userSpaceOnUse"><stop class="nim9nbcjd"/><stop offset="1" class="mh5_habnf"/></radialGradient><radialGradient id="iJls1sc" cx="0" cy="0" r="1" gradientTransform="rotate(143.412 5.637 14.178)scale(5.96846 3.36558)" gradientUnits="userSpaceOnUse"><stop class="s2ayxoxhu"/><stop offset="1" class="j6izx0btu"/></radialGradient><radialGradient id="iKpeIKe" cx="0" cy="0" r="1" gradientTransform="rotate(117.506 5.31 14.348)scale(10.2174 6.6572)" gradientUnits="userSpaceOnUse"><stop class="c9qnqxb4v"/><stop offset="1" class="f6lyc94ec"/></radialGradient><radialGradient id="iW1L1sc" cx="0" cy="0" r="1" gradientTransform="rotate(133.238 6.288 9.66)scale(4.31097 4.07134)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="abn8efjgi"/><stop offset="1" class="v46c2zbrf"/></radialGradient><radialGradient id="iUkKPae" cx="0" cy="0" r="1" gradientTransform="rotate(-144.77 15.76 10.464)scale(4.37936 1.86088)" gradientUnits="userSpaceOnUse"><stop class="jhjy8fbuk"/><stop offset="1" class="eb_-_cbgw"/></radialGradient><radialGradient id="is3wVfe" cx="0" cy="0" r="1" gradientTransform="rotate(-140.774 9.446 11.601)scale(.98834 .87647)" gradientUnits="userSpaceOnUse"><stop class="ui2onhbah"/><stop offset="1" class="r9xs6qbkj"/></radialGradient><radialGradient id="isUixxc" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 .23438 -.1603 .3847 13.134 19.474)" gradientUnits="userSpaceOnUse"><stop class="i5_a4vbjv"/><stop offset="1" class="qromo9b3v"/></radialGradient><radialGradient id="iEaER3b" cx="0" cy="0" r="1" gradientTransform="rotate(-111.297 16.984 9.897)scale(2.70865 13.4771)" gradientUnits="userSpaceOnUse"><stop class="l76admb0l"/><stop offset="1" class="a5hmpnbrm"/></radialGradient><radialGradient id="iq5gNhe" cx="0" cy="0" r="1" gradientTransform="rotate(172.312 10.097 13.634)scale(15.1472 14.3188)" gradientUnits="userSpaceOnUse"><stop offset=".843" class="scrkzqu2m"/><stop offset="1" class="s6nfrsifu"/></radialGradient><radialGradient id="i6eNipw" cx="0" cy="0" r="1" gradientTransform="matrix(.7947 5.8325 -18.0625 2.46109 12.114 24.358)" gradientUnits="userSpaceOnUse"><stop offset=".774" class="f7iiwgzmp"/><stop offset=".947" class="nd4n0ub4q"/></radialGradient><radialGradient id="iWXTwPf" cx="0" cy="0" r="1" gradientTransform="matrix(2.17808 -.99004 1.2088 2.65933 21.745 9.876)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="ioRZxMd" cx="0" cy="0" r="1" gradientTransform="matrix(.8727 .24934 -.13109 .45881 22.64 7.933)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iWnLPxb" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 38.209 -57.24)scale(1.14159)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iDdXcbc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06483 0 0 -1.01858 14.127 9.492)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iecVHQY" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 9.366 6.784)scale(6.26698 8.38824)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="ik0rRWb" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 8.741 7.282)scale(2.0885 1.77194)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iVuOSHb" cx="0" cy="0" r="1" gradientTransform="matrix(.73234 -3.53975 4.49129 .9292 16.303 14.957)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iHFyGqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.23985 -8.4585 0 18.21 8.77)" gradientUnits="userSpaceOnUse"><stop offset=".634" class="sj0rfhbsa"/><stop offset="1" class="gwipw-6fe"/></radialGradient><radialGradient id="iAUiysc" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 9.013 6.16)scale(5.06135 8.71409)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="ionbUIV" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.007 1.44767 0 20.224 8.655)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iAgXbUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.19009 1.36392 0 16.532 8.732)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="i4Znxec" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17867 0 0 -3.88021 22.67 9.957)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iUBe9LJ" cx="0" cy="0" r="1" gradientTransform="matrix(1.01179 3.69167 -7.62865 2.09081 16.023 4.204)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iwJ78Vc" cx="0" cy="0" r="1" gradientTransform="matrix(-.61032 -2.14367 1.22664 -.34923 18.897 10.593)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="ieOUrHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .70995 -1.12926 0 20.12 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ic0BPtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.20294 -.26151 .36005 -.27941 19.92 9.042)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixrnnad" cx="0" cy="0" r="1" gradientTransform="matrix(0 .70996 -1.12927 0 16.3 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iWFkSnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00677 -.43233 .51968 -.00814 16.05 9.161)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMD41LK" cx="0" cy="0" r="1" gradientTransform="matrix(1.69314 2.34674 -4.66297 3.36428 12.997 4.024)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="izqcgNd" cx="0" cy="0" r="1" gradientTransform="rotate(127.118 6.865 6.052)scale(2.7223 2.135)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iH03EHj" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 9.137 7.529)scale(4.2641 6.06337)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iyCVx1b" cx="0" cy="0" r="1" gradientTransform="rotate(104.957 8.741 9.561)scale(2.90494 5.1854)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="i0gSAmI" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 12.13 -1.506)scale(6.30961 5.648)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><filter id="iERWeKe" width="13.392" height="13.892" x="11.639" y="1.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3483"/></filter><filter id="ifaPWue" width="15.898" height="17.05" x="7.699" y="13.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.345098 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3483"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.396078 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3483" result="effect2_innerShadow_4002_3483"/></filter><filter id="izTvlDz" width="15.258" height="14.494" x="7.185" y="15.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".25"/></filter><filter id="iqsQBwc" width="14.977" height="12.277" x="7.219" y="17.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.443137 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3483"/></filter><filter id="iQCDofc" width="4.354" height="4.526" x="18.596" y="15.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.27451 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3483"/></filter><filter id="iaJkzpe" width="3.759" height="5.328" x="19.426" y="15.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".5"/></filter><filter id="iQBjWcb" width="1.206" height=".37" x="7.769" y="26.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".05"/></filter><filter id="iergBfb" width="1.261" height=".3" x="7.535" y="27.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".05"/></filter><filter id="i4Ik08d" width="1.206" height=".3" x="7.945" y="28.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".05"/></filter><filter id="i8PSOqc" width="4.908" height="6.063" x="16.822" y="19.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".25"/></filter><filter id="iy8nbJb" width="2.966" height="3.066" x="12.702" y="8.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3483"/></filter><filter id="iGNE9Rb" width="2.816" height="3.066" x="21.026" y="7.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3483"/></filter><filter id="iJJRCzd" width="2.88" height="2.88" x="20.994" y="8.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".25"/></filter><filter id="iEQXqAc" width="2.68" height="2.68" x="12.787" y="8.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".2"/></filter><filter id="iQUB66K" width="8.918" height="9.768" x="13.752" y="5.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3483"/></filter><filter id="iOcVeGh" width="2.643" height="3.347" x="16.747" y="8.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".25"/></filter><filter id="i2TI17c" width="2.143" height="2.847" x="17.139" y="8.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".125"/></filter><filter id="inUE9ce" width="3.29" height="1.385" x="16.565" y="11.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".05"/></filter><filter id="iChn6ni" width="2.651" height="1.125" x="19.01" y="8.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3483"/></filter><filter id="iURC2CN" width="2.651" height="1.125" x="14.76" y="8.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3483"/></filter><filter id="iR0n2ic" width="2.171" height=".98" x="14.878" y="6.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3483"/></filter><filter id="iDpeKZd" width="2.171" height=".98" x="19.618" y="6.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3483"/></filter><filter id="ipgzP5c" width=".714" height=".635" x="19.465" y="8.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".05"/></filter><filter id="iw58asb" width=".83" height=".849" x="20.187" y="8.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".1"/></filter><filter id="iI1yxOH" width=".913" height=".96" x="16.299" y="8.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".1"/></filter><filter id="i0hVT5b" width=".824" height=".641" x="15.651" y="8.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".05"/></filter><filter id="i1JuWIe" width="2.053" height=".931" x="19.607" y="7.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".1"/></filter><filter id="iqdaVjb" width="2.053" height=".931" x="14.837" y="7.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".1"/></filter><filter id="iDZQRHc" width="3.876" height="4.719" x="12.67" y="3.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".25"/></filter><filter id="int8Wfb" width="7.863" height="5.121" x="15.276" y="2.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".125"/></filter><filter id="i5sFEwc" width="1.077" height="2.096" x="15.38" y="3.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3483" stdDeviation=".1"/></filter><linearGradient id="iiUWJwd" x1="22.317" x2="16.362" y1="3.408" y2="14.438" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="i1gsgse" x1="20.114" x2="12.395" y1="27.89" y2="19.39" gradientUnits="userSpaceOnUse"><stop class="pokolfbgc"/><stop offset="1" class="b3y8h4ksz"/></linearGradient><linearGradient id="i8XiPOe" x1="16.52" x2="16.52" y1="29.971" y2="27.26" gradientUnits="userSpaceOnUse"><stop class="ckcj4hbsb"/><stop offset="1" class="q93oiybtq"/></linearGradient><linearGradient id="iMgi8Bd" x1="19.165" x2="11.447" y1="17.603" y2="26.103" gradientUnits="userSpaceOnUse"><stop class="tts0ot_3n"/><stop offset="1" class="luw3gnblf"/></linearGradient><linearGradient id="imaEE9b" x1="21.848" x2="18.973" y1="18.202" y2="18.046" gradientUnits="userSpaceOnUse"><stop class="a_ut7cc2e"/><stop offset="1" class="cyj659bzg"/></linearGradient><linearGradient id="i18nY5d" x1="21.317" x2="20.614" y1="16.452" y2="20.952" gradientUnits="userSpaceOnUse"><stop class="gla1f_2eg"/><stop offset="1" class="fx7b7_wnc"/></linearGradient><linearGradient id="iGhuaVR" x1="7.919" x2="9.075" y1="27.132" y2="27.202" gradientUnits="userSpaceOnUse"><stop class="oqrg77bvf"/><stop offset="1" class="gvz2879-v"/></linearGradient><linearGradient id="ivyf0Yb" x1="7.685" x2="8.915" y1="28.116" y2="28.122" gradientUnits="userSpaceOnUse"><stop class="oqrg77bvf"/><stop offset="1" class="gvz2879-v"/></linearGradient><linearGradient id="ia9Xs4h" x1="8.095" x2="9.255" y1="29.03" y2="29.035" gradientUnits="userSpaceOnUse"><stop class="oqrg77bvf"/><stop offset="1" class="gvz2879-v"/></linearGradient><linearGradient id="iQbJMEb" x1="11.931" x2="24.522" y1="13.699" y2="13.699" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i19yhLx" x1="11.931" x2="24.521" y1="13.672" y2="13.672" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iMlZagb" x1="20.447" x2="16.056" y1="20.166" y2="26.244" gradientUnits="userSpaceOnUse"><stop class="v8w30xk6h"/><stop offset="1" class="rfxv-bsin"/></linearGradient><linearGradient id="ibIdkDc" x1="12.702" x2="15.291" y1="9.568" y2="9.568" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="ilEYc5c" x1="17.295" x2="18.042" y1="10.608" y2="10.7" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iMlgdsc" x1="18.21" x2="18.21" y1="11.356" y2="10.822" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iCpxGCd" x1="17.572" x2="17.968" y1="12.648" y2="11.886" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="ijgb1Pb" x1="20.8" x2="20.526" y1="9.017" y2="9.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="it4gQYb" x1="16.952" x2="16.677" y1="9.016" y2="9.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iF9STDG" x1="15.68" x2="16.157" y1="4.067" y2="5.182" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pregnant-woman-medium-light" /></template>
<style>
.a_ut7cc2e {
  stop-color: var(--svg-color--8e6acb, #8E6ACB);
}

.a5hmpnbrm {
  stop-color: var(--svg-color--d69b98, #D69B98);
  stop-opacity: 0;
}

.a8v6ombcy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.68 3.767c.02.212.206 1.012.477 1.496");
}

.abn8efjgi {
  stop-color: var(--svg-color--513091, #513091);
}

.alphoubkv {
  d: path("M11.891 26.235c4.56-1.156 6.422-4.828 6.851-6.558l3.454.302c-.664 2.752-2.039 5.192-4.976 7.466c-3.972 2.752-8.54 2.498-8.75 2.498s-.575-.105-.63-.432a.45.45 0 0 1 .182-.46c-.127 0-.47-.02-.576-.406a.49.49 0 0 1 .161-.512a.48.48 0 0 1-.386-.546c.037-.425.427-.483.64-.474c-.259-.097-.282-.37-.254-.532c.023-.131.195-.512.761-.395a6 6 0 0 0 1.07.106a6 6 0 0 1-.271-.317a.55.55 0 0 1 .05-.742a.55.55 0 0 1 .793.026c.113.126.24.27.369.42c.42.488.702.702 1.512.556");
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aq9438b-n {
  fill-rule: evenodd;
  d: path("M24.498 10.726a2.84 2.84 0 0 0 .283-1.25a2.9 2.9 0 0 0-.235-1.141h.005a3 3 0 0 0-.246-.45l-.002-.002c-.301-.46-.46-1-.46-1.55v-.009a2.887 2.887 0 0 0-2.888-2.887a.47.47 0 0 1-.398-.203a2.9 2.9 0 0 0-2.347-1.205c-.965 0-1.824.478-2.347 1.205a.5.5 0 0 1-.398.203l-.075.001a2.89 2.89 0 0 0-2.812 2.886v.01c0 .548-.16 1.088-.46 1.549l-.003.003a2.89 2.89 0 0 0-.192 2.84a.45.45 0 0 1 0 .398a2.812 2.812 0 0 0 2.533 4.047h7.509a2.812 2.812 0 0 0 2.533-4.047a.45.45 0 0 1 0-.398M13.769 8.387h-.01l1.048 2.061c.108 2.453 1.065 0 3.403 0s3.357 2.73 3.465.278l.994-2.798c-.047-1.09-.836-1.166-.994-1.166h-2.818a3.38 3.38 0 0 1-2.79-1.464a.23.23 0 0 0-.404.045l-.072.17a2.02 2.02 0 0 1-1.13 1.115c-.207.107-.692.429-.71 1.26l.01.267z");
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.b3y8h4ksz {
  stop-color: var(--svg-color--7657b1, #7657B1);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b9v1u1-_l {
  d: path("M11.891 26.235c4.56-1.156 6.422-4.828 6.851-6.558l2.703-2.005l.75 2.307c-.663 2.752-2.038 5.192-4.975 7.466c-3.972 2.752-8.54 2.498-8.75 2.498s-.575-.105-.63-.433a.45.45 0 0 1 .182-.46c-.127 0-.47-.02-.576-.405a.49.49 0 0 1 .161-.512a.48.48 0 0 1-.386-.547c.037-.424.427-.483.64-.473c-.259-.098-.282-.37-.254-.532c.023-.131.195-.512.761-.395a6 6 0 0 0 1.07.106a6 6 0 0 1-.271-.317a.55.55 0 0 1 .05-.742a.55.55 0 0 1 .793.026c.113.126.24.27.369.42c.42.488.702.702 1.512.556");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bl4ekh57d {
  d: path("M22.434 10.9a1.408 1.408 0 1 0 0-2.816a1.408 1.408 0 0 0 0 2.816");
}

.bn1ilc5ze {
  d: path("m17.876 9.176l-.465 1.488a.472.472 0 0 0 .455.611h.688c.323 0 .55-.31.456-.611l-.465-1.488c-.1-.33-.565-.33-.67 0");
}

.bschqpbud {
  d: path("M17.682 2.674c-.99-.219-2.053.836-2.156 1.203c1.35 3.168 3.422 2.866 5.72 2.61c1.377-.152 1.526.475 1.643.778c-.381-3.55-2.948-4.092-5.207-4.59");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c9qnqxb4v {
  stop-color: var(--svg-color--9c7cd3, #9C7CD3);
}

.ckcj4hbsb {
  stop-color: var(--svg-color--5d4097, #5D4097);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmjixrfdv {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.303 8.313c.571 0 1.054.394 1.185.927a.24.24 0 0 1-.234.298H19.3a.2.2 0 0 1-.198-.238c.11-.56.603-.987 1.2-.987");
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cyj659bzg {
  stop-color: var(--svg-color--7555ae, #7555AE);
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvdov_bqj {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.118 8.313c-.571 0-1.054.394-1.186.927a.24.24 0 0 0 .235.298h1.952a.2.2 0 0 0 .199-.238a1.226 1.226 0 0 0-1.2-.987");
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.e_-jof7ml {
  d: path("M18.534 13.673q.331.015.675.044a17 17 0 0 0-.675-.044");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.eb_-_cbgw {
  stop-color: var(--svg-color--6f56b0, #6F56B0);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.ewoysi9vh {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.211 8.994c-.232-.409-.585-.731-1.345-.731a1.45 1.45 0 0 0-.939.322c-.235.19-.204.434-.022.525l.487.278c.57-.185 1.201-.21 1.819-.394");
}

.f6lyc94ec {
  stop-color: var(--svg-color--8563c2, #8563C2);
  stop-opacity: 0;
}

.f7iiwgzmp {
  stop-color: var(--svg-color--ba7b89, #BA7B89);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx7b7_wnc {
  stop-color: var(--svg-color--a281e0, #A281E0);
  stop-opacity: 0;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
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

.gla1f_2eg {
  stop-color: var(--svg-color--a281e0, #A281E0);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gvz2879-v {
  stop-color: var(--svg-color--b88367, #B88367);
  stop-opacity: 0;
}

.gwipw-6fe {
  stop-color: var(--svg-color--ae707f, #AE707F);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h249pabun {
  stop-color: var(--svg-color--b37e68, #B37E68);
  stop-opacity: 0;
}

.h5p3r6p8s {
  d: path("m13.76 8.155l-.008-.268c.017-.83.502-1.152.708-1.259q.022-.006.045-.018l.045-.017a2.02 2.02 0 0 0 1.041-1.08l.072-.17a.23.23 0 0 1 .404-.045a3.38 3.38 0 0 0 2.79 1.464h2.818c.158 0 .947.077.994 1.166l-.104 2.689c-.108 2.452-2.023 4.1-4.36 4.1s-4.253-1.648-4.361-4.1z");
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

.huvgmobvs {
  d: path("M20.817 9.23a.74.74 0 0 0-.202-.405l-.228.25l.103.2z");
}

.hvdam5ygl {
  d: path("M13.928 4.23c.543-.485 1.327-.49 1.767-.411l.352 1.13a.69.69 0 0 0-.594.204C15.057 6.62 13.56 6.4 13.267 7.5c-.132-1.305-.278-2.435.66-3.27");
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i2lbcbbob {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.21 12.04a2.65 2.65 0 0 1-1.244-.302c-.123-.064-.255.078-.177.192a1.69 1.69 0 0 0 2.843 0c.077-.119-.055-.256-.178-.192c-.36.192-.784.302-1.244.302Z");
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i5_a4vbjv {
  stop-color: var(--svg-color--725e92, #725E92);
}

.ipzmhfxzs {
  fill: var(--svg-color--e1ad91, #E1AD91);
  d: path("M11.891 26.235c4.56-1.156 6.422-4.828 6.851-6.558l2.703-2.005l.75 2.307c-.663 2.752-2.038 5.192-4.975 7.466c-3.972 2.752-8.54 2.498-8.75 2.498s-.575-.105-.63-.433a.45.45 0 0 1 .182-.46c-.127 0-.47-.02-.576-.405a.49.49 0 0 1 .161-.512a.48.48 0 0 1-.386-.547c.037-.424.427-.483.64-.473c-.259-.098-.282-.37-.254-.532c.023-.131.195-.512.761-.395a6 6 0 0 0 1.07.106a6 6 0 0 1-.271-.317a.55.55 0 0 1 .05-.742a.55.55 0 0 1 .793.026c.113.126.24.27.369.42c.42.488.702.702 1.512.556");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j6izx0btu {
  stop-color: var(--svg-color--755fa5, #755FA5);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jci5uhbmn {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M22.434 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.jhjy8fbuk {
  stop-color: var(--svg-color--7a63b9, #7A63B9);
}

.k8vkv0beg {
  d: path("M17.012 9.241c0-.252-.205-.42-.26-.471l-.253.244l.156.316z");
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kj0gkk02b {
  d: path("M20.064 8.717c.056.075-.06.165-.193.264c-.132.099-.23.169-.286.094c-.056-.074.007-.215.139-.314c.132-.098.284-.118.34-.044");
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kspdwq88h {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M14.127 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l6yuh0bov {
  stop-color: var(--svg-color--dfa990, #DFA990);
  stop-opacity: 0;
}

.l76admb0l {
  stop-color: var(--svg-color--d69b98, #D69B98);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.luw3gnblf {
  stop-color: var(--svg-color--584487, #584487);
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lzwbf3bxk {
  d: path("M13.759 8.387h.01l-.009-.232l-.008-.268c.017-.83.502-1.152.708-1.259q.022-.006.045-.018l.045-.017a2.02 2.02 0 0 0 1.041-1.08l.072-.17a.23.23 0 0 1 .404-.045a3.38 3.38 0 0 0 2.79 1.464h2.818c.158 0 .947.077.994 1.166l-.104 2.689c-.108 2.452-2.023 4.1-4.36 4.1s-4.253-1.648-4.361-4.1z");
}

.m_1u_6brl {
  d: path("M18.245 13.673h-.035c.088 0 .167 0 .254.009c-.07-.01-.149-.01-.219-.01");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mh5_habnf {
  stop-color: var(--svg-color--dda98e, #DDA98E);
  stop-opacity: 0;
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mltizig3o {
  d: path("M14.11 10.9a1.408 1.408 0 1 0 0-2.816a1.408 1.408 0 0 0 0 2.816");
}

.mn-ke3wbb {
  cx: 16.063px;
  cy: 8.885px;
  rx: 0.341px;
  ry: 0.173px;
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.nd4n0ub4q {
  stop-color: var(--svg-color--ba7b89, #BA7B89);
}

.nim9nbcjd {
  stop-color: var(--svg-color--dda98e, #DDA98E);
}

.njw83hasq {
  fill: var(--svg-color--000, #000);
  d: path("M16.746 9.333a.445.445 0 0 0-.447-.447a.445.445 0 0 0-.397.653h.791a.44.44 0 0 0 .053-.206");
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nte9-tbqd {
  d: path("M20.355 20.166c-.463 2.15-2.257 4.287-3.033 5.063c2.637-1.776 3.746-4.13 3.908-5.063z");
}

.nw0ip4b-d {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m15.237 7.935l-.004.003a.235.235 0 0 1-.241-.403h.001l.003-.002l.008-.005a2 2 0 0 1 .13-.067c.086-.041.21-.094.359-.142a2.45 2.45 0 0 1 1.162-.095a.235.235 0 1 1-.081.462c-.35-.062-.684 0-.938.08a2.4 2.4 0 0 0-.399.17");
}

.o9xuojmag {
  d: path("M22.434 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oj983wuvi {
  d: path("M20.339 16.167c-.568-.03-1.704.276-1.704 1.75c0 .752-.283 1.867-.424 2.33h.059c-.527 1.723-2.32 4.875-6.387 5.905c-.765.139-1.032-.064-1.428-.525a27 27 0 0 0-.348-.396a.52.52 0 0 0-.747-.024a.52.52 0 0 0-.049.7c.093.115.187.227.256.299a5.5 5.5 0 0 1-1.01-.1c-.534-.11-.697.249-.718.373c-.026.153 1.516.324 1.76.416c-.201-.009-.569.046-.604.447a.455.455 0 0 0 .364.516c-.069.054-1.741.317-1.672.57c.1.363.424.382.543.382a.43.43 0 0 0-.17.434c.05.31.396.409.594.409h.048c.52.015 4.622.128 8.21-2.358c2.773-2.147 4.072-4.422 4.698-7.02l-.287-.027h.287a9.8 9.8 0 0 0 .332-2.23c.046-1.308-.848-1.85-1.603-1.85");
}

.om93qlvyw {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.59 7.415c-.282-.069-.984-.034-1.453.301");
}

.oqrg77bvf {
  stop-color: var(--svg-color--b88367, #B88367);
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pokolfbgc {
  stop-color: var(--svg-color--7a61b9, #7A61B9);
}

.pp54f-29q {
  d: path("M19.045 17.51c0-1.56 1.203-1.886 1.805-1.854c.8 0 1.747.576 1.698 1.962a10.4 10.4 0 0 1-.351 2.362h-3.601c.15-.492.449-1.673.449-2.47");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.psox_sbvx {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m17.867 9.297l-.598 1.488a.472.472 0 0 0 .455.612h.688c.323 0 .55-.311.456-.612l-.465-1.488c-.1-.33-.432-.33-.536 0");
}

.pu9u9k2rp {
  d: path("M20.704 17.171a36 36 0 0 1-.278 2.61h1.5a23 23 0 0 0 .259-2.58a.72.72 0 0 0-.726-.749a.764.764 0 0 0-.756.72");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.q93oiybtq {
  stop-color: var(--svg-color--5d4097, #5D4097);
  stop-opacity: 0;
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qromo9b3v {
  stop-color: var(--svg-color--725e92, #725E92);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r9xs6qbkj {
  stop-color: var(--svg-color--423363, #423363);
  stop-opacity: 0;
}

.raxopjbju {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.685 28.116h.96");
}

.rfxv-bsin {
  stop-color: var(--svg-color--e5b79f, #E5B79F);
  stop-opacity: 0;
}

.rhkp4jvnd {
  fill: var(--svg-color--000, #000);
  d: path("M19.674 9.333c0-.248.199-.447.447-.447a.445.445 0 0 1 .398.653h-.792a.4.4 0 0 1-.053-.206");
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.s2ayxoxhu {
  stop-color: var(--svg-color--755fa5, #755FA5);
}

.s304qo8pr {
  stop-color: var(--svg-color--b37f75, #B37F75);
}

.s6nfrsifu {
  stop-color: var(--svg-color--c4907f, #C4907F);
}

.scrkzqu2m {
  stop-color: var(--svg-color--c4907f, #C4907F);
  stop-opacity: 0;
}

.si1cfpbnk {
  cx: 16.063px;
  cy: 8.885px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.341px;
  ry: 0.173px;
}

.sj0rfhbsa {
  stop-color: var(--svg-color--cf928e, #CF928E);
  stop-opacity: 0;
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tc029nbmi {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m21.476 7.535l-.121.201za.235.235 0 0 1-.24.402l-.005-.003l-.019-.01l-.08-.04a2.4 2.4 0 0 0-.3-.119a2 2 0 0 0-.937-.08a.235.235 0 1 1-.082-.462c.45-.08.865 0 1.162.095a3 3 0 0 1 .49.209l.008.005l.002.001z");
}

.tl8qpbpot {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.92 27.132c.174.013.6.045.906.07");
}

.tt72geb2m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M8.095 29.03h.906");
}

.tts0ot_3n {
  stop-color: var(--svg-color--553697, #553697);
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.ui2onhbah {
  stop-color: var(--svg-color--423363, #423363);
}

.ujtedzbaf {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m17.876 9.176l-.465 1.488a.472.472 0 0 0 .455.611h.688c.323 0 .55-.31.456-.611l-.465-1.488c-.1-.33-.565-.33-.67 0");
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.us6butbbp {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.907 7.415c.283-.069.985-.034 1.454.301");
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v46c2zbrf {
  stop-color: var(--svg-color--785cad, #785CAD);
  stop-opacity: 0;
}

.v5dmk1bjv {
  stop-color: var(--svg-color--b37e68, #B37E68);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v8w30xk6h {
  stop-color: var(--svg-color--e5b79f, #E5B79F);
}

.vp-eqebay {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M19.21 8.994c.232-.409.585-.731 1.345-.731c.333 0 .654.092.939.322c.235.19.204.434.021.525l-.486.278c-.57-.185-1.201-.21-1.82-.394");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.w270qkb5v {
  d: path("M20.122 8.552a.78.78 0 0 1 .752.987h-1.509a.784.784 0 0 1 .756-.987");
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wtf0g401w {
  d: path("M16.299 8.552a.78.78 0 0 0-.752.987h1.508a.786.786 0 0 0-.756-.987");
}

.wxfwszbys {
  d: path("M13.488 16.186c.688-.874 2.474-2.374 3.281-3.015h3.266c2.15.587 2.562 2.625 2.562 3.625v11.328c0 1.563-1.208 1.88-1.812 1.844h-9.89c-2.282 0-4.094-3.188-2.72-6.61c1.265-2.63 3.503-3.447 4.787-3.74a.16.16 0 0 0 .094-.243c-.981-1.43-.39-2.141.432-3.189");
}

.xckf85eqw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.064 8.717c.056.075-.06.165-.193.264c-.132.099-.23.169-.286.094c-.056-.074.007-.215.139-.314c.132-.098.284-.118.34-.044");
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xyfahlb3n {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M18.21 12.04a2.65 2.65 0 0 1-1.244-.302c-.123-.064-.255.078-.177.192a1.69 1.69 0 0 0 2.843 0c.077-.119-.055-.256-.178-.192c-.36.192-.784.302-1.244.302");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yoj1htbxp {
  d: path("M14.127 10.432a.94.94 0 1 0 0-1.88a.94.94 0 0 0 0 1.88");
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
