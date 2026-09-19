<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i1qIbOb)"><path fill="url(#ilhzsXd)" clip-rule="evenodd" class="b2omki_1p"/><path fill="url(#i0Cg9bc)" clip-rule="evenodd" class="b2omki_1p"/><path fill="url(#iQLwHdd)" clip-rule="evenodd" class="b2omki_1p"/><path fill="url(#iFq12Nc)" clip-rule="evenodd" class="b2omki_1p"/><path fill="url(#iq9nYvd)" clip-rule="evenodd" class="b2omki_1p"/><path fill="url(#iZ54eyb)" clip-rule="evenodd" class="b2omki_1p"/><path fill="url(#iWMJKJd)" clip-rule="evenodd" class="b2omki_1p"/><path fill="url(#iySdUtb)" clip-rule="evenodd" class="b2omki_1p"/><path fill="url(#idVH64A)" clip-rule="evenodd" class="b2omki_1p"/><path fill="url(#i9A2L7b)" clip-rule="evenodd" class="b2omki_1p"/></g><path fill="url(#iA8cjbb)" clip-rule="evenodd" class="b2omki_1p"/><path fill="url(#iliecgc)" class="tck06tkfd"/><path fill="url(#iDip6ec)" class="tck06tkfd"/><path fill="url(#ipHmGQd)" class="tck06tkfd"/><path fill="url(#iWdhQik)" class="tck06tkfd"/><path fill="url(#i6Xvgab)" class="t30xnnbas"/><path fill="url(#iNksLHb)" class="t30xnnbas"/><path fill="url(#iLeYRFd)" class="ev1voiawl"/><path fill="url(#iZTXQie)" class="ev1voiawl"/><path fill="url(#iICpskb)" class="ev1voiawl"/><g filter="url(#ixK8uCb)"><path fill="url(#ijHbHlO)" class="k6j35ou1o"/><path fill="url(#iRFanjd)" class="k6j35ou1o"/></g><path fill="url(#ivDlGab)" class="k6j35ou1o"/><path fill="url(#iJAC1ne)" class="k6j35ou1o"/><path fill="url(#iBvtasb)" class="k6j35ou1o"/><g filter="url(#io1k8wc)"><path fill="url(#iIcH28b)" class="pur8n-kzf"/><path fill="url(#iwgHiub)" class="pur8n-kzf"/></g><rect fill="url(#iT4KShQ)" class="jkk7rcbip"/><g filter="url(#ieImucb)"><path fill="url(#ilyf2dd)" class="yl15dvb4j"/></g><g filter="url(#ii9SNjN)"><path fill="url(#iKrmiqe)" class="fv42ynb4b"/><path fill="url(#ijStgPe)" class="fv42ynb4b"/></g><g filter="url(#ixIHTKd)"><path class="d81xwv8tc"/><path fill="url(#ir1xkUb)" class="jn8zt3bqu"/></g><g filter="url(#igfB8yc)"><path class="cpgrh2b9l"/><path fill="url(#iaeB8Td)" class="n-cu-bcbl"/></g><g filter="url(#iHs9x0x)"><path fill="url(#ijwJXSu)" class="gg7aephbq"/><path fill="url(#iy62hwb)" class="gg7aephbq"/><path fill="url(#ilb43Wc)" class="gg7aephbq"/><path fill="url(#iI22QXc)" class="gg7aephbq"/><path fill="url(#iOhb2Pd)" class="gg7aephbq"/><path fill="url(#iRq8B8d)" class="gg7aephbq"/><path fill="url(#iIwigec)" class="gg7aephbq"/></g><path fill="url(#iDg8G4Q)" class="spmz_xb-d"/><g filter="url(#iFSeLJe)"><path class="q428yby-c"/></g><g filter="url(#i8cB5Le)"><path class="dz-cm4bkw"/><path fill="url(#iXstMfd)" class="dax4f3ldk"/><path fill="url(#i1qPbVb)" class="dax4f3ldk"/><path fill="url(#ieNZ4Sy)" class="dax4f3ldk"/></g><path fill="url(#ikMsfMe)" class="dax4f3ldk"/><path fill="url(#iBqX2Sc)" class="dax4f3ldk"/><g filter="url(#iZsOR5d)"><path class="pnp327b6l"/></g><g filter="url(#iagnX7d)"><path class="w7wegkbhm"/></g><path class="qvzjkubuf"/><path fill="url(#i0PF3Bj)" class="ovuo3ob6v"/><path class="aw1m2e_5n"/><g filter="url(#ibkf9xe)"><path class="n3hk_bm4h"/><path fill="url(#iwhdlec)" class="po2k-lb4z"/></g><g filter="url(#iZP1XSc)"><path fill="url(#itpHuWd)" class="crijitpxq"/></g><path class="bsnbzebko"/><path fill="url(#i1A2Lkd)" class="w5x09tlkn"/><path class="mtz9obcbr"/><g filter="url(#ijPKPld)"><path fill="url(#ijTenlb)" class="guiqv1wxj"/></g><g filter="url(#iw1mxxd)"><ellipse transform="rotate(-27.914 13.563 10.094)" class="o68dd4hiy"/><ellipse fill="url(#iAjUDBc)" transform="rotate(-27.914 13.563 10.094)" class="guz0fpbql"/></g><g filter="url(#iTmJkga)"><path fill="url(#iVwr3fw)" class="g8_nbp65v"/><path fill="url(#ilUIg0d)" class="g8_nbp65v"/></g><g filter="url(#igqVHoc)"><path fill="url(#ikvOG0b)" class="qm_w-ybog"/><path fill="url(#iTMqCzt)" class="qm_w-ybog"/><path fill="url(#iW4wN0b)" class="qm_w-ybog"/></g><g filter="url(#iaNMAsV)"><path stroke="url(#iZWSolb)" class="ane20pbxm"/></g><g filter="url(#iMxZgPb)"><path stroke="url(#ij1P0jb)" clip-rule="evenodd" class="lik4-wbbr"/><path stroke="url(#ijq2NMc)" clip-rule="evenodd" class="lik4-wbbr"/></g><path clip-rule="evenodd" class="fnwo871rz"/><g filter="url(#ieg34xd)"><path fill="url(#iotzGho)" class="vs3tlbckf"/></g><g filter="url(#itYh1lY)"><rect class="ni7-36bpx"/></g><g filter="url(#iorciOb)"><rect class="gc8c61bim"/></g><g filter="url(#iLvrvMc)"><path class="cfh-p_e9y"/></g><g filter="url(#ih3PLFc)"><path class="vddzcofbi"/></g><defs><radialGradient id="i0Cg9bc" cx="0" cy="0" r="1" gradientTransform="matrix(1.78038 -3.69773 8.43106 4.0594 20.862 16.745)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iQLwHdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.13695 5.6493 -5.28812 -.1282 15.383 12.602)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iFq12Nc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.21838 2.4994 -3.07663 -3.96165 12.884 13.63)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iq9nYvd" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.693 8.406)scale(1.81903 1.65341)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iZ54eyb" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.358 4.11)scale(2.43801 3.5839)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iWMJKJd" cx="0" cy="0" r="1" gradientTransform="matrix(2.20844 3.2355 -5.6464 3.85404 12.148 3.067)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="iySdUtb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12985 1.23258 -1.72251 -1.57895 21.683 4.933)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="idVH64A" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88301 .54781 -1.19197 -4.0972 23.738 9.932)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="i9A2L7b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.2184 1.36951 -2.18205 -5.12789 23.464 12.773)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iA8cjbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.74992 12.3304 0 16.068 17.087)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="iu5u1ubha"/><stop offset="1" class="otbrp-jxo"/></radialGradient><radialGradient id="iliecgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.625 -11.8762 0 16.002 15.982)" gradientUnits="userSpaceOnUse"><stop class="yzdait1or"/><stop offset="1" class="fh_to2b_k"/></radialGradient><radialGradient id="iDip6ec" cx="0" cy="0" r="1" gradientTransform="rotate(-90 23.774 .83)scale(8.375)" gradientUnits="userSpaceOnUse"><stop class="we5he9b5x"/><stop offset="1" class="ry9ym0wup"/></radialGradient><radialGradient id="iWdhQik" cx="0" cy="0" r="1" gradientTransform="matrix(-5.65625 0 0 -3.18983 15.005 15.513)" gradientUnits="userSpaceOnUse"><stop offset=".225" class="pz447cbze"/><stop offset="1" class="a87a47nxn"/></radialGradient><radialGradient id="i6Xvgab" cx="0" cy="0" r="1" gradientTransform="matrix(2.13456 -.2935 1.15245 8.38143 24.387 23.786)" gradientUnits="userSpaceOnUse"><stop class="gq1qbfdiu"/><stop offset="1" class="s2jhqaccf"/></radialGradient><radialGradient id="iLeYRFd" cx="0" cy="0" r="1" gradientTransform="rotate(18.435 -63.515 28.954)scale(3.1219 5.27347)" gradientUnits="userSpaceOnUse"><stop class="thab7zb6m"/><stop offset=".965" class="w_io4zdrw"/></radialGradient><radialGradient id="iICpskb" cx="0" cy="0" r="1" gradientTransform="matrix(.17189 -4.40625 .36187 .01412 8.553 24.605)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="cv_ifqb4z"/><stop offset="1" class="lw76c5ixl"/></radialGradient><radialGradient id="ijHbHlO" cx="0" cy="0" r="1" gradientTransform="matrix(14.39625 1.34665 -.12277 1.31245 16.667 24.76)" gradientUnits="userSpaceOnUse"><stop class="vdrlp1btg"/><stop offset="1" class="ycsg7o3pv"/></radialGradient><radialGradient id="ivDlGab" cx="0" cy="0" r="1" gradientTransform="matrix(.53911 1.07078 -4.30786 2.16889 17.493 26.537)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="znz3iub6a"/><stop offset="1" class="kv03ukb5t"/></radialGradient><radialGradient id="iJAC1ne" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18419 1.99325 -.46677 -.97983 24.715 23.753)" gradientUnits="userSpaceOnUse"><stop class="oituyjrgp"/><stop offset="1" class="it3dq1b0b"/><stop offset="1" class="s4h8a-b4j"/></radialGradient><radialGradient id="iBvtasb" cx="0" cy="0" r="1" gradientTransform="rotate(-123.262 13.415 8.809)scale(4.08149 11.2931)" gradientUnits="userSpaceOnUse"><stop class="cu4c8py0z"/><stop offset=".475" class="kfs2y325k"/></radialGradient><radialGradient id="iIcH28b" cx="0" cy="0" r="1" gradientTransform="matrix(.59435 2.55245 -38.40477 8.94272 16.219 25.242)" gradientUnits="userSpaceOnUse"><stop offset=".044" class="j4-11dbix"/><stop offset=".198" class="xi0qmybrn"/></radialGradient><radialGradient id="iT4KShQ" cx="0" cy="0" r="1" gradientTransform="matrix(2.62845 2.05877 -2.5322 3.2329 15.47 16.576)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="dfas76pad"/><stop offset="1" class="yv8azmbrn"/></radialGradient><radialGradient id="iKrmiqe" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 36.065 -40.99)scale(2.79249 3.4095)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="ijStgPe" cx="0" cy="0" r="1" gradientTransform="matrix(1.01859 .29103 -.153 .53551 21.238 8.982)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="ir1xkUb" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 41.229 -52.462)scale(1.33243)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iaeB8Td" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24283 0 0 -1.18885 11.302 10.8)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="ijwJXSu" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6424 3.06303 -4.09982 -8.89074 18.989 10.252)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iy62hwb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15477 1.13974 -.96698 -1.82817 18.01 10.965)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="ilb43Wc" cx="0" cy="0" r="1" gradientTransform="matrix(.8548 -4.13148 5.24208 1.08457 13.842 17.18)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iI22QXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.05158 -8.47508 0 16.38 10.217)" gradientUnits="userSpaceOnUse"><stop offset=".46" class="o3us4w8iz"/><stop offset="1" class="zer9qlrjo"/></radialGradient><radialGradient id="iOhb2Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.85473 .78743 -1.35571 -10.08004 16.719 12.636)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iRq8B8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17533 1.68968 0 18.419 9.825)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iIwigec" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.38903 1.59192 0 14.11 9.914)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iDg8G4Q" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3757 0 0 -4.52886 21.273 11.344)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iXstMfd" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 12.998 -.325)scale(2.60146 1.48859)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iBqX2Sc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3089 .93493 -1.25227 -1.75316 16.362 11.721)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="i0PF3Bj" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82863 -1.31804 0 18.297 10.191)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iwhdlec" cx="0" cy="0" r="1" gradientTransform="matrix(-.23687 -.30524 .42024 -.3261 18.064 10.277)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1A2Lkd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82864 -1.31804 0 13.84 10.191)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iAjUDBc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.9 -1.46)scale(.50467 .60663)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVwr3fw" cx="0" cy="0" r="1" gradientTransform="matrix(1.97618 2.73904 -5.44248 3.92668 9.983 4.419)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="ilUIg0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.91742 2.53363 -1.98703 -1.50376 13.295 4.659)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="ikvOG0b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15703 4.4852 -6.37776 -3.06722 18.02 2.707)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iTMqCzt" cx="0" cy="0" r="1" gradientTransform="rotate(104.957 7.716 9.03)scale(3.39055 6.05224)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iW4wN0b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.57796 -6.43679 5.76184 -3.20279 17.387 9.487)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="ij1P0jb" cx="0" cy="0" r="1" gradientTransform="rotate(116.896 3.996 12.175)scale(.30222 .93391)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="w_-azgsyc"/><stop offset="1" class="l08io-bzd"/></radialGradient><radialGradient id="ijq2NMc" cx="0" cy="0" r="1" gradientTransform="rotate(-31.372 32.824 -19.454)scale(.18758 .22697)" gradientUnits="userSpaceOnUse"><stop class="w_-azgsyc"/><stop offset="1" class="l08io-bzd"/></radialGradient><radialGradient id="iotzGho" cx="0" cy="0" r="1" gradientTransform="matrix(.45361 -.42147 .49908 .53715 15.928 15.07)" gradientUnits="userSpaceOnUse"><stop class="dnucjl5pv"/><stop offset="1" class="q24oxbc5n"/></radialGradient><filter id="i1qIbOb" width="15.589" height="16.089" x="8.399" y="1.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4646"/></filter><filter id="ixK8uCb" width="19.161" height="7.244" x="8.163" y="22.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.427451 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4646"/></filter><filter id="io1k8wc" width="19.009" height="7.177" x="5.176" y="22.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.6 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4646"/></filter><filter id="ieImucb" width="3.437" height="3.537" x="9.639" y="9.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4646"/></filter><filter id="ii9SNjN" width="3.287" height="3.537" x="19.355" y="8.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4646"/></filter><filter id="ixIHTKd" width="3.194" height="3.194" x="19.402" y="9.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".25"/></filter><filter id="igfB8yc" width="2.994" height="2.994" x="9.805" y="9.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".2"/></filter><filter id="iHs9x0x" width="10.408" height="11.509" x="10.864" y="5.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4646"/></filter><filter id="iFSeLJe" width="2.917" height="3.739" x="14.444" y="9.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".25"/></filter><filter id="i8cB5Le" width="2.417" height="3.239" x="14.86" y="9.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".125"/></filter><filter id="iZsOR5d" width="3.061" height="1.313" x="17.035" y="9.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4646"/></filter><filter id="iagnX7d" width="3.061" height="1.313" x="12.041" y="9.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4646"/></filter><filter id="ibkf9xe" width=".799" height=".707" x="17.549" y="9.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".05"/></filter><filter id="iZP1XSc" width=".902" height=".924" x="18.409" y="9.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".1"/></filter><filter id="ijPKPld" width=".999" height="1.054" x="13.871" y="9.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".1"/></filter><filter id="iw1mxxd" width=".928" height=".715" x="13.098" y="9.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".05"/></filter><filter id="iTmJkga" width="4.357" height="5.341" x="9.686" y="3.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".25"/></filter><filter id="igqVHoc" width="9.094" height="5.893" x="12.685" y="2.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".125"/></filter><filter id="iaNMAsV" width="1.156" height="2.346" x="12.816" y="3.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".1"/></filter><filter id="iMxZgPb" width="2.698" height="1.082" x="14.766" y="13.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".05"/></filter><filter id="ieg34xd" width="1.224" height=".712" x="15.456" y="14.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".05"/></filter><filter id="itYh1lY" width="2.848" height=".741" x="12.531" y="8.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4646"/></filter><filter id="iorciOb" width="2.848" height=".741" x="17.05" y="8.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4646"/></filter><filter id="iLvrvMc" width="2.62" height=".55" x="17.123" y="8.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".075"/></filter><filter id="ih3PLFc" width="2.62" height=".55" x="12.628" y="8.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4646" stdDeviation=".075"/></filter><linearGradient id="ilhzsXd" x1="20.862" x2="13.911" y1="3.7" y2="16.574" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="ipHmGQd" x1="16.505" x2="16.505" y1="30.355" y2="26.605" gradientUnits="userSpaceOnUse"><stop class="s4ejur1-r"/><stop offset="1" class="b8m56lbmr"/></linearGradient><linearGradient id="iNksLHb" x1="22.8" x2="23.56" y1="22.852" y2="22.798" gradientUnits="userSpaceOnUse"><stop class="ks4zirblu"/><stop offset="1" class="w9135ub2z"/></linearGradient><linearGradient id="iZTXQie" x1="9.63" x2="8.474" y1="23.855" y2="23.761" gradientUnits="userSpaceOnUse"><stop class="sa_9c2b3h"/><stop offset="1" class="v0otsew1r"/></linearGradient><linearGradient id="iRFanjd" x1="17.493" x2="17.126" y1="29.909" y2="25.468" gradientUnits="userSpaceOnUse"><stop class="sod43yh1j"/><stop offset="1" class="glphqfbcr"/></linearGradient><linearGradient id="iwgHiub" x1="17.064" x2="16.095" y1="29.909" y2="25.312" gradientUnits="userSpaceOnUse"><stop class="wkf34er1g"/><stop offset="1" class="w7_ggxidt"/></linearGradient><linearGradient id="ilyf2dd" x1="9.639" x2="12.662" y1="10.89" y2="10.89" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="i1qPbVb" x1="15" x2="15.872" y1="12.104" y2="12.211" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="ieNZ4Sy" x1="16.068" x2="16.068" y1="12.977" y2="12.354" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="ikMsfMe" x1="16.148" x2="16.148" y1="12.95" y2="12.808" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="itpHuWd" x1="19.091" x2="18.771" y1="10.246" y2="10.444" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijTenlb" x1="14.599" x2="14.279" y1="10.246" y2="10.444" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZWSolb" x1="13.116" x2="13.672" y1="4.471" y2="5.772" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-pouting-medium-light" /></template>
<style>
.a87a47nxn {
  stop-color: var(--svg-color--6f3a5f, #6F3A5F);
  stop-opacity: 0;
}

.ane20pbxm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.116 4.12c.023.248.24 1.18.556 1.746");
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

.aw1m2e_5n {
  fill: var(--svg-color--000, #000);
  d: path("M17.777 10.616a.52.52 0 0 1 .522-.522a.52.52 0 0 1 .464.762h-.924a.5.5 0 0 1-.062-.24");
}

.b2omki_1p {
  fill-rule: evenodd;
  d: path("M23.407 12.241c.217-.444.33-.94.33-1.457c0-.478-.098-.925-.274-1.334h.006a3.3 3.3 0 0 0-.287-.524l-.002-.003a3.3 3.3 0 0 1-.538-1.809v-.01a3.37 3.37 0 0 0-3.37-3.37a.55.55 0 0 1-.465-.237a3.38 3.38 0 0 0-2.739-1.406c-1.127 0-2.13.558-2.739 1.406a.58.58 0 0 1-.465.238h-.087a3.37 3.37 0 0 0-3.283 3.369v.01c0 .641-.186 1.272-.537 1.81l-.002.003a3.37 3.37 0 0 0-.225 3.314a.53.53 0 0 1 0 .465a3.282 3.282 0 0 0 2.956 4.724h8.765a3.28 3.28 0 0 0 3.287-3.287a3.3 3.3 0 0 0-.331-1.437a.53.53 0 0 1 0-.465m-12.522-2.73h-.013l1.225 2.406c.126 2.863 1.243 0 3.971 0c2.729 0 3.918 3.186 4.044.324l1.16-3.265c-.054-1.272-.976-1.361-1.16-1.361h-3.288a3.95 3.95 0 0 1-3.258-1.709a.27.27 0 0 0-.471.052l-.084.198a2.35 2.35 0 0 1-1.267 1.282q-.028.013-.053.02c-.24.126-.806.5-.827 1.47l.01.313z");
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b8m56lbmr {
  stop-color: var(--svg-color--7e45bf, #7E45BF);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bsnbzebko {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.626 9.427c-.667 0-1.23.46-1.383 1.081a.28.28 0 0 0 .273.348h2.279a.235.235 0 0 0 .232-.278a1.43 1.43 0 0 0-1.4-1.151");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.cfh-p_e9y {
  stroke: var(--svg-color--976239, #976239);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.398 8.628h2.07");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpgrh2b9l {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.302 11.898a1.097 1.097 0 1 0 0-2.194a1.097 1.097 0 0 0 0 2.194");
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.crijitpxq {
  d: path("M19.11 10.496a.86.86 0 0 0-.235-.473l-.266.291l.12.233z");
}

.cu4c8py0z {
  stop-color: var(--svg-color--c49676, #C49676);
}

.cv_ifqb4z {
  stop-color: var(--svg-color--7f5b9c, #7F5B9C);
}

.d81xwv8tc {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.999 11.898a1.097 1.097 0 1 0 0-2.194a1.097 1.097 0 0 0 0 2.194");
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.dax4f3ldk {
  d: path("m15.678 10.432l-.543 1.737a.55.55 0 0 0 .532.714h.803a.552.552 0 0 0 .532-.714l-.543-1.737c-.116-.384-.66-.384-.781 0");
}

.dfas76pad {
  stop-color: var(--svg-color--b97b72, #B97B72);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dnucjl5pv {
  stop-color: var(--svg-color--cf9382, #CF9382);
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

.dz-cm4bkw {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.678 10.432l-.543 1.737a.55.55 0 0 0 .532.714h.803a.552.552 0 0 0 .532-.714l-.543-1.737c-.116-.384-.66-.384-.781 0");
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

.ev1voiawl {
  d: path("m5.251 24.853l3.847-.16l.059.182h.031v-7.109a10.5 10.5 0 0 0-3.937 7.087");
}

.fh_to2b_k {
  stop-color: var(--svg-color--9a6aba, #9A6ABA);
}

.fnwo871rz {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M16.952 14.285c-.485-.33-1.193-.33-1.673 0a.2.2 0 1 1-.226-.33c.616-.423 1.504-.423 2.124 0a.2.2 0 1 1-.225.33");
}

.ft5dv1b6b {
  fill: none;
}

.fv42ynb4b {
  d: path("M20.999 12.445a1.643 1.643 0 1 0 0-3.287a1.643 1.643 0 0 0 0 3.287");
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

.g8_nbp65v {
  d: path("M11.07 4.659c.634-.565 1.549-.57 2.063-.48l.41 1.319c-.262-.04-.496.051-.693.24c-.462 1.711-2.208 1.455-2.55 2.738c-.155-1.523-.326-2.841.77-3.817");
}

.gc8c61bim {
  width: 2.648px;
  height: 0.541px;
  x: 17.05px;
  y: 8.404px;
  fill: var(--svg-color--9f6836, #9F6836);
  rx: 0.271px;
}

.gg7aephbq {
  d: path("m10.875 9.24l-.01-.312c.02-.97.586-1.344.827-1.47q.024-.007.052-.02l.052-.021c.545-.25.985-.688 1.215-1.26l.084-.199a.27.27 0 0 1 .471-.052a3.95 3.95 0 0 0 3.258 1.709h3.289c.184 0 1.105.09 1.16 1.36l-.122 3.14c-.126 2.862-2.36 4.784-5.09 4.784c-2.728 0-4.963-1.922-5.089-4.785z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.glphqfbcr {
  stop-color: var(--svg-color--bf8088, #BF8088);
  stop-opacity: 0;
}

.gq1qbfdiu {
  stop-color: var(--svg-color--a886e6, #A886E6);
}

.guiqv1wxj {
  d: path("M14.67 10.509c0-.295-.24-.491-.304-.55l-.294.284l.18.37z");
}

.guz0fpbql {
  cx: 13.563px;
  cy: 10.094px;
  rx: 0.398px;
  ry: 0.201px;
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
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

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.it3dq1b0b {
  stop-color: var(--svg-color--aa8368, #AA8368);
  stop-opacity: 0;
}

.iu5u1ubha {
  stop-color: var(--svg-color--bd8d6e, #BD8D6E);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j4-11dbix {
  stop-color: var(--svg-color--f9c6aa, #F9C6AA);
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jkk7rcbip {
  width: 4.223px;
  height: 6.028px;
  x: 13.876px;
  y: 12.607px;
  rx: 2.111px;
}

.jn8zt3bqu {
  d: path("M20.999 11.898a1.097 1.097 0 1 0 0-2.194a1.097 1.097 0 0 0 0 2.194");
}

.k6j35ou1o {
  d: path("M26.374 28.45c.6-1.05.454-2.812.375-3.597l-3.937-.168c-.413.213-1.526.089-2.031 0l-8.898-1.406c-.617-.117-2.096-.232-2.773.133c-.766.412-1 1.192-.938 1.578c4.271 1.531 12.632 4.562 13.757 4.812c1.82.313 3.695-.039 4.445-1.351");
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kfs2y325k {
  stop-color: var(--svg-color--c49676, #C49676);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.ks4zirblu {
  stop-color: var(--svg-color--8559af, #8559AF);
}

.kv03ukb5t {
  stop-color: var(--svg-color--a2606c, #A2606C);
  stop-opacity: 0;
}

.l08io-bzd {
  stop-color: var(--svg-color--dda596, #DDA596);
  stop-opacity: 0;
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lik4-wbbr {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.952 14.285c-.485-.33-1.193-.33-1.673 0a.2.2 0 1 1-.226-.33c.616-.423 1.504-.423 2.124 0a.2.2 0 1 1-.225.33");
}

.lw76c5ixl {
  stop-color: var(--svg-color--7f5b9c, #7F5B9C);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mtz9obcbr {
  fill: var(--svg-color--000, #000);
  d: path("M14.36 10.616a.52.52 0 0 0-.522-.522a.52.52 0 0 0-.464.762h.924a.5.5 0 0 0 .062-.24");
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n-cu-bcbl {
  d: path("M11.302 11.898a1.097 1.097 0 1 0 0-2.194a1.097 1.097 0 0 0 0 2.194");
}

.n3hk_bm4h {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.232 9.897c.065.087-.07.193-.225.308s-.27.197-.334.11c-.065-.087.008-.251.162-.366c.154-.116.332-.139.397-.052");
}

.ni7-36bpx {
  width: 2.648px;
  height: 0.541px;
  x: 12.531px;
  y: 8.404px;
  fill: var(--svg-color--9f6836, #9F6836);
  rx: 0.271px;
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.o3us4w8iz {
  stop-color: var(--svg-color--dca38d, #DCA38D);
  stop-opacity: 0;
}

.o68dd4hiy {
  cx: 13.563px;
  cy: 10.094px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.398px;
  ry: 0.201px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oituyjrgp {
  stop-color: var(--svg-color--daa37d, #DAA37D);
}

.otbrp-jxo {
  stop-color: var(--svg-color--ecba98, #ECBA98);
  stop-opacity: 0;
}

.ovuo3ob6v {
  d: path("M18.299 9.704a.91.91 0 0 1 .878 1.152h-1.76a.915.915 0 0 1 .883-1.152");
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

.pnp327b6l {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.235 10.22c.27-.477.683-.853 1.57-.853c.388 0 .763.107 1.096.376c.274.222.237.506.025.612l-.568.325c-.666-.216-1.402-.245-2.123-.46");
}

.po2k-lb4z {
  d: path("M18.232 9.897c.065.087-.07.193-.225.308s-.27.197-.334.11c-.065-.087.008-.251.162-.366c.154-.116.332-.139.397-.052");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pur8n-kzf {
  d: path("M5.626 28.45c-.6-1.05-.454-2.812-.375-3.597l3.937-.168c.413.213 1.526.089 2.031 0l9.672-1.562c.617-.118 1.448-.177 2.125.187c.728.392.7.965.642 1.352a.1.1 0 0 1-.063.078c-4.286 1.54-12.404 4.813-13.524 5.062c-1.82.313-3.695-.039-4.445-1.351");
}

.pz447cbze {
  stop-color: var(--svg-color--6f3a5f, #6F3A5F);
}

.q24oxbc5n {
  stop-color: var(--svg-color--c78572, #C78572);
}

.q428yby-c {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.667 10.574l-.698 1.736a.55.55 0 0 0 .532.714h.803a.553.553 0 0 0 .532-.714l-.543-1.736c-.116-.385-.504-.385-.626 0");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qm_w-ybog {
  d: path("M15.452 2.844c-1.157-.255-2.397.976-2.517 1.404c1.576 3.698 3.994 3.345 6.677 3.047c1.606-.178 1.78.554 1.917.908c-.445-4.143-3.44-4.777-6.077-5.359");
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qvzjkubuf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.51 9.427c.667 0 1.23.46 1.384 1.081a.28.28 0 0 1-.273.348h-2.279a.235.235 0 0 1-.232-.278a1.43 1.43 0 0 1 1.4-1.151");
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.ry9ym0wup {
  stop-color: var(--svg-color--a270cc, #A270CC);
  stop-opacity: 0;
}

.s2jhqaccf {
  stop-color: var(--svg-color--9a69b9, #9A69B9);
}

.s4ejur1-r {
  stop-color: var(--svg-color--7e45bf, #7E45BF);
}

.s4h8a-b4j {
  stop-color: var(--svg-color--daa37d, #DAA37D);
  stop-opacity: 0;
}

.sa_9c2b3h {
  stop-color: var(--svg-color--754897, #754897);
}

.sod43yh1j {
  stop-color: var(--svg-color--bf8088, #BF8088);
}

.spmz_xb-d {
  d: path("M10.873 9.512h.012l-.01-.271l-.01-.313c.02-.97.586-1.344.827-1.47q.024-.007.052-.02l.052-.021c.545-.25.985-.688 1.215-1.26l.084-.199a.27.27 0 0 1 .471-.052a3.95 3.95 0 0 0 3.258 1.709h3.289c.184 0 1.105.09 1.16 1.36l-.122 3.14c-.126 2.862-2.36 4.784-5.09 4.784c-2.728 0-4.963-1.922-5.089-4.785z");
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.t30xnnbas {
  d: path("M22.925 17.856a10.48 10.48 0 0 1 3.827 7.02l-3.827-.18z");
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tck06tkfd {
  d: path("m9.157 24.67l-3.906.183c.578-5.253 5.03-9.34 10.437-9.34h.625c5.415 0 9.872 4.098 10.44 9.362l-4.378-.206v5.188H9.157z");
}

.thab7zb6m {
  stop-color: var(--svg-color--8e71af, #8E71AF);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
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

.v0otsew1r {
  stop-color: var(--svg-color--754897, #754897);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vddzcofbi {
  stroke: var(--svg-color--976239, #976239);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.903 8.628h2.07");
}

.vdrlp1btg {
  stop-color: var(--svg-color--deab99, #DEAB99);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vs3tlbckf {
  d: path("M16.58 14.955a.512.512 0 1 0-1.024 0z");
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w_-azgsyc {
  stop-color: var(--svg-color--dda596, #DDA596);
}

.w_io4zdrw {
  stop-color: var(--svg-color--795993, #795993);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w5x09tlkn {
  d: path("M13.838 9.704a.912.912 0 0 0-.879 1.152h1.761a1 1 0 0 0 .033-.24a.92.92 0 0 0-.915-.912");
}

.w7_ggxidt {
  stop-color: var(--svg-color--c07684, #C07684);
  stop-opacity: 0;
}

.w7wegkbhm {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.902 10.22c-.271-.477-.683-.853-1.57-.853c-.389 0-.763.107-1.096.376c-.275.222-.238.506-.025.612l.568.325c.666-.216 1.402-.245 2.123-.46");
}

.w9135ub2z {
  stop-color: var(--svg-color--8559af, #8559AF);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.we5he9b5x {
  stop-color: var(--svg-color--b188e7, #B188E7);
}

.wkf34er1g {
  stop-color: var(--svg-color--c07684, #C07684);
}

.xi0qmybrn {
  stop-color: var(--svg-color--f1b8a2, #F1B8A2);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.ycsg7o3pv {
  stop-color: var(--svg-color--e8b39a, #E8B39A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yl15dvb4j {
  d: path("M11.283 12.445a1.643 1.643 0 1 0 0-3.287a1.643 1.643 0 0 0 0 3.287");
}

.yv8azmbrn {
  stop-color: var(--svg-color--dea996, #DEA996);
}

.yzdait1or {
  stop-color: var(--svg-color--8755a0, #8755A0);
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zer9qlrjo {
  stop-color: var(--svg-color--b57476, #B57476);
}

.znz3iub6a {
  stop-color: var(--svg-color--a2606c, #A2606C);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
