<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iG5b4Ou)"><path fill="url(#inQ37Ad)" clip-rule="evenodd" class="tt74gnbay"/><path fill="url(#ihWTMFc)" clip-rule="evenodd" class="tt74gnbay"/><path fill="url(#ipnKeIc)" clip-rule="evenodd" class="tt74gnbay"/><path fill="url(#iAzpWFb)" clip-rule="evenodd" class="tt74gnbay"/><path fill="url(#iA9e3cc)" clip-rule="evenodd" class="tt74gnbay"/><path fill="url(#imw1Zxc)" clip-rule="evenodd" class="tt74gnbay"/><path fill="url(#ihb89pd)" clip-rule="evenodd" class="tt74gnbay"/><path fill="url(#i3FVZmd)" clip-rule="evenodd" class="tt74gnbay"/><path fill="url(#iQ6aPDb)" clip-rule="evenodd" class="tt74gnbay"/><path fill="url(#izUjPwe)" clip-rule="evenodd" class="tt74gnbay"/></g><path fill="url(#iYQxSad)" class="pd2u-vbcz"/><path fill="url(#iuHjzOc)" class="pd2u-vbcz"/><path fill="url(#id1Egtb)" class="pd2u-vbcz"/><path fill="url(#ixHp6Nm)" class="pd2u-vbcz"/><path fill="url(#ikQVGQb)" class="wsoxrs3gi"/><path fill="url(#iVoHuar)" class="wsoxrs3gi"/><path fill="url(#iMNiWyc)" class="wsoxrs3gi"/><path fill="url(#i02mmOh)" class="wsoxrs3gi"/><path fill="url(#iUul23b)" class="kkjbgdrwc"/><path fill="url(#ibKw8pC)" class="kkjbgdrwc"/><path fill="url(#iB98V0c)" class="jj4ierbpx"/><path fill="url(#iX7Ixhe)" class="jj4ierbpx"/><path fill="url(#imDwcxe)" class="jj4ierbpx"/><path fill="url(#irddMde)" class="bfc74gb5s"/><path fill="url(#iScmkTd)" class="bfc74gb5s"/><path fill="url(#iqjlpNb)" class="vzzx10boi"/><path fill="url(#iOqyJJe)" class="vzzx10boi"/><g filter="url(#iVsVzZQ)"><path fill="url(#iwkGNJb)" class="zxmbqsb2m"/><path fill="url(#ivUkobd)" class="zxmbqsb2m"/><path fill="url(#iHnJ2EI)" class="zxmbqsb2m"/><path fill="url(#iOOFv7J)" class="zxmbqsb2m"/><path fill="url(#iLO8C0c)" class="zxmbqsb2m"/></g><rect fill="url(#iQjWJeT)" class="rdz_xehft"/><rect fill="url(#iIvJppG)" class="rdz_xehft"/><g filter="url(#isIJqky)"><path fill="url(#iDxGF6b)" class="c9lqf5w-z"/></g><g filter="url(#irxuIgd)"><path fill="url(#iKkS9qm)" class="xo2uqchfb"/></g><g filter="url(#iHLaPQM)"><path fill="url(#iS7bpAe)" class="up8ccg-pp"/></g><g filter="url(#iajSecb)"><path stroke="url(#iFL3Jab)" class="yfyrxjv9q"/></g><g filter="url(#i7QNBRJ)"><path stroke="url(#iiT9yCb)" class="qnmqq7dav"/></g><g filter="url(#iiRTQde)"><path stroke="url(#iUGk6Vd)" class="cpwn7kb3z"/></g><g filter="url(#i0mLvJb)"><path fill="url(#il2reld)" class="x76jecb0k"/><path fill="url(#ikE6mNd)" class="x76jecb0k"/></g><path fill="url(#iRwqGMb)" class="z72ga7b0g"/><path fill="url(#ixoXdmR)" class="z72ga7b0g"/><path fill="url(#iqkzACL)" class="z72ga7b0g"/><path fill="url(#iK3nD2c)" class="z72ga7b0g"/><path fill="url(#iOH4d5d)" class="z72ga7b0g"/><path fill="url(#iwwHS8b)" class="esajgvata"/><path fill="url(#ivZ01iW)" class="esajgvata"/><path fill="url(#iDvnRKd)" class="esajgvata"/><path fill="url(#iRVBk4b)" class="esajgvata"/><path fill="url(#iIJkacd)" class="zjtplxbvo"/><path fill="url(#iSueZfc)" class="zjtplxbvo"/><path fill="url(#iQ4j6lC)" class="zjtplxbvo"/><path fill="url(#ifg5QUh)" class="cx9aisbwr"/><path fill="url(#iU0X8Be)" class="nu1rqmx8p"/><g filter="url(#i0XQ99b)"><path fill="url(#iB3IKbd)" class="n06kp2b3o"/></g><g filter="url(#inej5Fd)"><path fill="url(#i9k4sYb)" class="qo8f1k98w"/><path fill="url(#ia7wZQd)" class="qo8f1k98w"/></g><g filter="url(#iK9fBwb)"><path class="cv9f1acat"/><path fill="url(#iPZqatc)" class="cipwz1r7t"/></g><g filter="url(#id7qxoe)"><path class="ebdvt7t9c"/><path fill="url(#iw6uxsb)" class="bvdm99b0w"/></g><g filter="url(#iTSS0Le)"><path fill="url(#i5u7mPb)" class="ic1_b9bxz"/><path fill="url(#iRFa00P)" class="ic1_b9bxz"/><path fill="url(#ibmAnxN)" class="ic1_b9bxz"/><path fill="url(#iyrwDTc)" class="ic1_b9bxz"/><path fill="url(#i1WJNSc)" class="ic1_b9bxz"/><path fill="url(#iLQs0bd)" class="ic1_b9bxz"/><path fill="url(#iFqVE3c)" class="ic1_b9bxz"/></g><path fill="url(#igIYUGb)" class="vx0fsebqg"/><path fill="url(#i8GXfYd)" class="vx0fsebqg"/><g filter="url(#iLUrmpc)"><path class="wpu_-6rwp"/></g><g filter="url(#iu7tTpe)"><path class="gybowd-ck"/><path fill="url(#iwJdE2b)" class="xjr2n--8k"/><path fill="url(#iLj0kuc)" class="xjr2n--8k"/><path fill="url(#imInPLe)" class="xjr2n--8k"/></g><path fill="url(#iygVuCR)" class="xjr2n--8k"/><path fill="url(#id7TqMc)" class="xjr2n--8k"/><path stroke="url(#i9lu1zc)" class="j5cxqla0e"/><g filter="url(#iuWAR1b)"><path class="db9_irbnk"/></g><g filter="url(#ivegJJQ)"><path class="te31tkftr"/></g><g filter="url(#icBtkkd)"><path class="pp7iv5b6a"/></g><g filter="url(#ivPLjCd)"><path clip-rule="evenodd" class="jhmw3ubdt"/></g><path class="decsqbc1x"/><path fill="url(#iZQrfDe)" class="iv2kwqzip"/><path class="uwh7gsoty"/><g filter="url(#iy5sgde)"><path class="nrtatm23u"/><path fill="url(#ipl1WuT)" class="ld1apu_vg"/></g><g filter="url(#iDMw14c)"><path fill="url(#i6Hrtwb)" class="wueal8b-c"/></g><path class="yo0hllmvb"/><path fill="url(#i67eSIc)" class="xpw5uwbtf"/><path class="wcoikxbeb"/><g filter="url(#ikEfHzb)"><path fill="url(#iUMjh0d)" class="r0wsp3byy"/></g><g filter="url(#izJBCmd)"><ellipse transform="rotate(-27.914 13.732 10.062)" class="yqk34qwxf"/><ellipse fill="url(#itNg9ec)" transform="rotate(-27.914 13.732 10.062)" class="qi4w4rgqa"/></g><g filter="url(#inMU7qd)"><path class="fy513mbtm"/></g><g filter="url(#iIkBVQc)"><path class="f92sgt79a"/></g><g filter="url(#iTW4Gkc)"><path fill="url(#irWqPOb)" class="fds14lhux"/><path fill="url(#iwFXCsb)" class="fds14lhux"/></g><g filter="url(#i9xfLhe)"><path fill="url(#iaCpKEI)" class="z8pbalxdd"/><path fill="url(#ikErRed)" class="z8pbalxdd"/><path fill="url(#iMZOgAG)" class="z8pbalxdd"/></g><g filter="url(#issdzBU)"><path stroke="url(#iIOwJsx)" class="twg8-wyqp"/></g><defs><radialGradient id="ihWTMFc" cx="0" cy="0" r="1" gradientTransform="matrix(1.74318 -3.62044 8.25485 3.97456 20.878 16.574)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="ipnKeIc" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 3.299 11.785)scale(5.77873 5.40927)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iAzpWFb" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 4.216 9.001)scale(3.98975 4.91117)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iA9e3cc" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.816 8.438)scale(1.78101 1.61886)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="imw1Zxc" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.461 4.088)scale(2.38706 3.50899)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="ihb89pd" cx="0" cy="0" r="1" gradientTransform="matrix(2.16229 3.16788 -5.52839 3.77349 12.347 3.182)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="i3FVZmd" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.74 7.274)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iQ6aPDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.694 9.903)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="izUjPwe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15113 1.34089 -2.13644 -5.02072 23.426 12.686)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="ixHp6Nm" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.45313 -5.35592 0 16.17 16.724)" gradientUnits="userSpaceOnUse"><stop class="u4dm99tvf"/><stop offset="1" class="pzxsbj1yt"/></radialGradient><radialGradient id="ikQVGQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 5.095 30)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iVoHuar" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.943 30)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iMNiWyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.943 23.05)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="iUul23b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92413 -10.2056 2.9218 -.55086 25.322 30)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="ibKw8pC" cx="0" cy="0" r="1" gradientTransform="matrix(.55553 12.0481 -.71816 .03311 23.225 23.153)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iB98V0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.27137 -3.54923 0 16.94 16.276)" gradientUnits="userSpaceOnUse"><stop class="j4fq87b3w"/><stop offset="1" class="e5d8lm8ca"/></radialGradient><radialGradient id="iX7Ixhe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.42297 -2.45165 0 16.17 15.188)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="ukg1xnbxa"/><stop offset=".923" class="f-lk6hbga"/></radialGradient><radialGradient id="imDwcxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42187 -.53125 0 14.86 16.033)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="h-8qjbcjs"/><stop offset="1" class="wgyur5thp"/></radialGradient><radialGradient id="irddMde" cx="0" cy="0" r="1" gradientTransform="rotate(145.605 10.48 16.148)scale(2.31047 2.27126)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="iScmkTd" cx="0" cy="0" r="1" gradientTransform="rotate(-37.372 48.45 -29.225)scale(.9457 .72531)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="iqjlpNb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 26.271 24.284)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="ivUkobd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.037 25.304)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iHnJ2EI" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.037 26.599)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iOOFv7J" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.037 27.849)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iLO8C0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.037 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iQjWJeT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.717 21.46)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="il2reld" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.3125 12.819 0 16.151 23.406)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="rr16fpbgs"/><stop offset="1" class="gvd3e3nnk"/></radialGradient><radialGradient id="ikE6mNd" cx="0" cy="0" r="1" gradientTransform="rotate(-94.385 20.554 4.374)scale(10.6778 18.1021)" gradientUnits="userSpaceOnUse"><stop offset=".721" class="p3kckzh8s"/><stop offset="1" class="nqv_-mmyu"/></radialGradient><radialGradient id="iqkzACL" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.87 17.392)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="iRVBk4b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.584 17.218)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="iQ4j6lC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.35 17.468)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="i9k4sYb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.225 11.194)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="ia7wZQd" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 21.247 8.973)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iPZqatc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 41.095 -52.54)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iw6uxsb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 11.519 10.755)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="i5u7mPb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 19.044 10.217)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iRFa00P" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 18.085 10.915)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="ibmAnxN" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 14.005 17)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iyrwDTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.4375 -10.082 0 16.185 9.93)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sgt5sn5oc"/><stop offset="1" class="gxm-dc6uw"/></radialGradient><radialGradient id="i1WJNSc" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.99 6.839)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iLQs0bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 18.486 9.799)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iFqVE3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.267 9.886)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="igIYUGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.28 11.287)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="i8GXfYd" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 13.685 4.711)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iwJdE2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.97 12.013)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="id7TqMc" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.369 8.467)scale(1.57489 2.10944)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="iZQrfDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.367 10.158)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ipl1WuT" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.139 10.242)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i67eSIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 14.003 10.158)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="itNg9ec" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.966 -1.563)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irWqPOb" cx="0" cy="0" r="1" gradientTransform="matrix(1.93486 2.6818 -5.32876 3.84458 10.227 4.506)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="iwFXCsb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87735 2.48068 -1.9455 -1.47233 13.47 4.741)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iaCpKEI" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11195 4.39145 -6.24446 -3.00311 18.096 2.83)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="ikErRed" cx="0" cy="0" r="1" gradientTransform="matrix(-.8568 3.20722 -5.72497 -1.5294 18.498 4.004)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iMZOgAG" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.523 -.406)scale(7.21046 6.45439)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><linearGradient id="inQ37Ad" x1="20.878" x2="14.073" y1="3.802" y2="16.407" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iYQxSad" x1="16.172" x2="16.172" y1="15.54" y2="30.425" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="iuHjzOc" x1="23.599" x2="21.068" y1="26.593" y2="26.625" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="id1Egtb" x1="8.627" x2="10.843" y1="26.409" y2="26.409" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="i02mmOh" x1="9.091" x2="8.656" y1="28.066" y2="28.066" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iOqyJJe" x1="25.634" x2="25.662" y1="21.996" y2="22.351" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="iwkGNJb" x1="27.628" x2="23.6" y1="28.062" y2="28.062" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="nfkkf0b1d"/></linearGradient><linearGradient id="iIvJppG" x1="25.644" x2="25.644" y1="20.812" y2="21.273" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iDxGF6b" x1="17.222" x2="17.222" y1="29.603" y2="22.926" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iKkS9qm" x1="13.215" x2="13.215" y1="29.603" y2="22.926" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iS7bpAe" x1="21.209" x2="21.209" y1="29.603" y2="22.926" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iFL3Jab" x1="24.123" x2="25.832" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iiT9yCb" x1="24.045" x2="25.754" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iUGk6Vd" x1="24.123" x2="25.832" y1="28.679" y2="28.679" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iRwqGMb" x1="27.912" x2="24.537" y1="20.718" y2="20.343" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="ixoXdmR" x1="25.632" x2="25.632" y1="20.984" y2="20.468" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="iK3nD2c" x1="25.632" x2="25.632" y1="16.838" y2="17.469" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="iOH4d5d" x1="23.335" x2="24.077" y1="19.185" y2="19.185" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="iwwHS8b" x1="23.506" x2="22.209" y1="18.969" y2="18.969" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="ivZ01iW" x1="23.756" x2="23.365" y1="19.25" y2="19.25" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="iDvnRKd" x1="22.96" x2="22.96" y1="21.08" y2="20.417" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="iIJkacd" x1="29.207" x2="27.587" y1="19.417" y2="19.417" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="iSueZfc" x1="28.506" x2="28.506" y1="21.054" y2="20.531" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="ifg5QUh" x1="9" x2="23.376" y1="15.565" y2="15.565" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iU0X8Be" x1="9" x2="23.376" y1="15.534" y2="15.534" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iB3IKbd" x1="9.89" x2="12.85" y1="10.842" y2="10.842" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iLj0kuc" x1="15.139" x2="15.993" y1="12.031" y2="12.135" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="imInPLe" x1="16.185" x2="16.185" y1="12.885" y2="12.275" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iygVuCR" x1="16.263" x2="16.263" y1="12.859" y2="12.72" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="i9lu1zc" x1="15.456" x2="15.909" y1="14.362" y2="13.491" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="i6Hrtwb" x1="19.145" x2="18.831" y1="10.212" y2="10.405" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUMjh0d" x1="14.747" x2="14.433" y1="10.212" y2="10.405" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIOwJsx" x1="13.294" x2="13.839" y1="4.557" y2="5.831" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><filter id="iG5b4Ou" width="15.268" height="15.768" x="8.676" y="1.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1738"/></filter><filter id="iVsVzZQ" width="4.468" height="5.556" x="23.6" y="24.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1738"/></filter><filter id="isIJqky" width="1.192" height="6.826" x="15.589" y="23.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".125"/></filter><filter id="irxuIgd" width="1.192" height="6.826" x="11.583" y="23.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".125"/></filter><filter id="iHLaPQM" width="1.192" height="6.826" x="19.576" y="23.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".125"/></filter><filter id="iajSecb" width="2.097" height=".3" x="23.973" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".05"/></filter><filter id="i7QNBRJ" width="2.097" height=".3" x="23.895" y="27.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".05"/></filter><filter id="iiRTQde" width="2.097" height=".3" x="23.973" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".05"/></filter><filter id="i0mLvJb" width="12.911" height="8.522" x="9.695" y="15.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.756863 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1738"/></filter><filter id="i0XQ99b" width="3.368" height="3.468" x="9.89" y="9.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1738"/></filter><filter id="inej5Fd" width="3.218" height="3.468" x="19.403" y="8.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1738"/></filter><filter id="iK9fBwb" width="3.148" height="3.148" x="19.438" y="9.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".25"/></filter><filter id="id7qxoe" width="2.948" height="2.948" x="10.045" y="9.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".2"/></filter><filter id="iTSS0Le" width="10.191" height="11.127" x="11.09" y="5.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1738"/></filter><filter id="iLUrmpc" width="2.877" height="3.682" x="14.584" y="9.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".25"/></filter><filter id="iu7tTpe" width="2.377" height="3.182" x="14.996" y="9.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".125"/></filter><filter id="iuWAR1b" width="3.001" height="1.285" x="17.127" y="9.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1738"/></filter><filter id="ivegJJQ" width="3.001" height="1.285" x="12.242" y="9.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1738"/></filter><filter id="icBtkkd" width="2.453" height="1.091" x="12.377" y="7.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1738"/></filter><filter id="ivPLjCd" width="2.453" height="1.091" x="17.794" y="7.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1738"/></filter><filter id="iy5sgde" width=".787" height=".696" x="17.633" y="9.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".05"/></filter><filter id="iDMw14c" width=".891" height=".913" x="18.473" y="9.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".1"/></filter><filter id="ikEfHzb" width=".986" height="1.04" x="14.03" y="9.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".1"/></filter><filter id="izJBCmd" width=".913" height=".705" x="13.275" y="9.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".05"/></filter><filter id="inMU7qd" width="2.661" height="1.378" x="17.625" y="7.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".2"/></filter><filter id="iIkBVQc" width="2.661" height="1.378" x="12.173" y="7.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".2"/></filter><filter id="iTW4Gkc" width="4.287" height="5.25" x="9.926" y="3.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".25"/></filter><filter id="i9xfLhe" width="8.914" height="5.78" x="12.868" y="2.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".125"/></filter><filter id="issdzBU" width="1.145" height="2.31" x="12.994" y="3.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1738" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-judge-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bfc74gb5s {
  d: path("M26.959 22.932c.532 0 .959.428.959.959v2.188H26.01v-2.188a.94.94 0 0 1 .948-.959");
}

.bvdm99b0w {
  d: path("M11.519 11.83a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c9lqf5w-z {
  d: path("M15.839 23.543h.692v6.326h-.692z");
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.cipwz1r7t {
  d: path("M21.012 11.83a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpwn7kb3z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.123 28.601h1.797");
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cv9f1acat {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M21.012 11.83a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
}

.cx9aisbwr {
  d: path("M16.54 15.535c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.db9_irbnk {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.327 10.186c.266-.467.67-.836 1.538-.836c.38 0 .747.106 1.072.37c.27.216.233.494.025.598l-.556.318c-.652-.21-1.373-.24-2.079-.45");
}

.decsqbc1x {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.576 9.41c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
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

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.e5d8lm8ca {
  stop-color: var(--svg-color--d19b81, #D19B81);
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.ebdvt7t9c {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.519 11.83a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.esajgvata {
  d: path("M23.178 16.955h-.613a.505.505 0 0 0-.504.503v3.022c0 .272.222.504.504.504h.613a.505.505 0 0 0 .503-.504v-3.022a.51.51 0 0 0-.503-.503");
}

.f-lk6hbga {
  stop-color: var(--svg-color--a86f4a, #A86F4A);
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.f92sgt79a {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.334 8.382c-.323-.078-1.125-.039-1.661.345");
}

.fds14lhux {
  d: path("M11.29 4.741c.622-.553 1.518-.559 2.02-.47l.403 1.291c-.257-.039-.486.05-.679.235c-.453 1.676-2.162 1.425-2.498 2.682c-.15-1.492-.318-2.782.755-3.738");
}

.ft5dv1b6b {
  fill: none;
}

.fy513mbtm {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.125 8.382c.322-.078 1.124-.039 1.66.345");
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
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

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gvd3e3nnk {
  stop-color: var(--svg-color--bdb2af, #BDB2AF);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.gxm-dc6uw {
  stop-color: var(--svg-color--a46e69, #A46E69);
}

.gybowd-ck {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.803 10.394l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-8qjbcjs {
  stop-color: var(--svg-color--bf8c7c, #BF8C7C);
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.ic1_b9bxz {
  d: path("m11.1 9.227l-.01-.306c.02-.949.574-1.316.81-1.439l.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.082.088 1.136 1.333l-.12 3.073c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iv2kwqzip {
  d: path("M18.37 9.68a.892.892 0 0 1 .86 1.129h-1.725a.896.896 0 0 1 .864-1.128");
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j4fq87b3w {
  stop-color: var(--svg-color--c2877e, #C2877E);
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.j5cxqla0e {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.787 13.278a3 3 0 0 0 1.398.338c.518 0 .994-.123 1.398-.338a.205.205 0 0 1 .248.04a.2.2 0 0 1 .02.25m-3.064-.29l3.023.263m-3.023-.263a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248m.268-.291l-.227.263m3.292.027l-.042-.027m.042.027l-.042-.027m.042.027a1.982 1.982 0 0 1-3.333 0m3.29-.027a1.932 1.932 0 0 1-3.249 0m-.041.028l.041-.028m-.041.028l.041-.028");
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jhmw3ubdt {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m19.917 8.52l-.138.23za.268.268 0 0 1-.276.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.09.988 0 1.328.109a3.3 3.3 0 0 1 .559.238l.009.006l.003.002z");
}

.jj4ierbpx {
  d: path("M16.17 18.548a2.07 2.07 0 0 1-2.075-2.075v-2.579a2.07 2.07 0 0 1 2.075-2.065c1.149 0 2.075.927 2.075 2.075v2.579a2.083 2.083 0 0 1-2.075 2.065");
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kkjbgdrwc {
  d: path("M23.398 30V18.198c2.355 2.01 3.848 4.986 3.848 8.31V29a1 1 0 0 1-1 1z");
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.ld1apu_vg {
  d: path("M18.304 9.87c.063.085-.07.188-.221.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.389-.05");
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
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

.n06kp2b3o {
  d: path("M11.5 12.364a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.nfkkf0b1d {
  stop-color: var(--svg-color--c4907c, #C4907C);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nqv_-mmyu {
  stop-color: var(--svg-color--5f5c5d, #5F5C5D);
}

.nrtatm23u {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.304 9.87c.063.085-.07.188-.221.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.389-.05");
}

.nu1rqmx8p {
  d: path("M16.21 15.535h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p3kckzh8s {
  stop-color: var(--svg-color--9b999b, #9B999B);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pd2u-vbcz {
  d: path("M16.094 15.718c-6.115 0-10.999 4.728-10.999 10.791V30h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.063-5.037-10.79-11.151-10.79");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp7iv5b6a {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.788 8.977l-.005.003a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.01-.006a2 2 0 0 1 .148-.076c.098-.047.239-.108.41-.162c.34-.109.815-.2 1.328-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.pzxsbj1yt {
  stop-color: var(--svg-color--1a121e, #1A121E);
  stop-opacity: 0;
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qi4w4rgqa {
  cx: 13.732px;
  cy: 10.062px;
  rx: 0.39px;
  ry: 0.197px;
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qnmqq7dav {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.045 27.296h1.797");
}

.qo8f1k98w {
  d: path("M21.012 12.364a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r0wsp3byy {
  d: path("M14.816 10.469c0-.289-.234-.481-.298-.54l-.288.28l.178.36z");
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.rdz_xehft {
  width: 2.773px;
  height: 1.082px;
  x: 24.257px;
  y: 20.984px;
  rx: 0.541px;
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rr16fpbgs {
  stop-color: var(--svg-color--ddd3e4, #DDD3E4);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sgt5sn5oc {
  stop-color: var(--svg-color--bd8381, #BD8381);
  stop-opacity: 0;
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
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

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.te31tkftr {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.043 10.186c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.106-1.073.37c-.269.216-.233.494-.025.598l.556.318c.652-.21 1.373-.24 2.08-.45");
}

.tt74gnbay {
  fill-rule: evenodd;
  d: path("M23.37 12.165c.213-.435.324-.921.324-1.427c0-.468-.096-.906-.268-1.306h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.77v-.011a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004A3.3 3.3 0 0 0 9 12.165a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.455M11.11 9.492h-.012l1.198 2.356c.124 2.802 1.218 0 3.889 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.333-1.136-1.333h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.24 1.255l-.052.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.twg8-wyqp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.294 4.213c.023.243.234 1.157.545 1.71");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u4dm99tvf {
  stop-color: var(--svg-color--1a121e, #1A121E);
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.ukg1xnbxa {
  stop-color: var(--svg-color--a86f4a, #A86F4A);
  stop-opacity: 0;
}

.up8ccg-pp {
  d: path("M19.826 23.543h.692v6.326h-.692z");
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uwh7gsoty {
  fill: var(--svg-color--000, #000);
  d: path("M17.858 10.573c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.236");
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
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

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vx0fsebqg {
  d: path("M11.098 9.492h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439l.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.082.088 1.136 1.333l-.12 3.073c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.vzzx10boi {
  d: path("M24.879 21.07v6.427h1.51V21.07z");
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wcoikxbeb {
  fill: var(--svg-color--000, #000);
  d: path("M14.512 10.573a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.236");
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wgyur5thp {
  stop-color: var(--svg-color--bf8c7c, #BF8C7C);
  stop-opacity: 0;
}

.wpu_-6rwp {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.793 10.532l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.494-.376-.613 0");
}

.wsoxrs3gi {
  d: path("M8.943 30V18.198c-2.356 2.01-3.848 4.986-3.848 8.31V30z");
}

.wueal8b-c {
  d: path("M19.164 10.456a.84.84 0 0 0-.231-.463l-.26.285l.117.229z");
}

.x76jecb0k {
  d: path("M13.237 16.079a.196.196 0 0 0-.221-.176c-1.073.162-1.98.713-2.909 1.243c-.195.112-.357.286-.392.508q-.02.121-.02.248c0 .599.333 1.12.824 1.389c.057.03.076.105.041.159a1.582 1.582 0 0 0 1.419 2.43a.114.114 0 0 1 .119.121l-.004.112a1.582 1.582 0 0 0 2.498 1.29a.114.114 0 0 1 .166.038a1.582 1.582 0 0 0 2.786 0a.114.114 0 0 1 .166-.039a1.582 1.582 0 0 0 2.495-1.401a.114.114 0 0 1 .118-.12l.084.001a1.582 1.582 0 0 0 1.335-2.432a.113.113 0 0 1 .04-.16a1.58 1.58 0 0 0 .805-1.636c-.035-.222-.197-.396-.392-.508c-.928-.53-1.836-1.08-2.909-1.243a.196.196 0 0 0-.221.176c-.19 1.636-1.06 3.258-2.914 3.268c-1.854-.01-2.725-1.632-2.914-3.268");
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjr2n--8k {
  d: path("m15.803 10.394l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xo2uqchfb {
  d: path("M11.833 23.543h.692v6.326h-.692z");
}

.xpw5uwbtf {
  d: path("M14.001 9.68a.893.893 0 0 0-.86 1.129h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yfyrxjv9q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.123 25.992h1.797");
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yo0hllmvb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.794 9.41c-.653 0-1.205.45-1.355 1.058c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.yqk34qwxf {
  cx: 13.732px;
  cy: 10.062px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.z72ga7b0g {
  d: path("M27.083 16.955h-2.901a.505.505 0 0 0-.504.503v3.022c0 .272.222.504.504.504h2.9a.505.505 0 0 0 .505-.504v-3.022a.51.51 0 0 0-.504-.503");
}

.z8pbalxdd {
  d: path("M15.582 2.964c-1.133-.25-2.347.956-2.464 1.375c1.542 3.62 3.91 3.275 6.537 2.983c1.572-.174 1.743.542 1.877.889c-.436-4.056-3.37-4.677-5.95-5.247");
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zjtplxbvo {
  d: path("M28.704 16.955h-.614a.505.505 0 0 0-.503.503v3.022c0 .272.221.504.503.504h.613a.505.505 0 0 0 .504-.504v-3.022a.51.51 0 0 0-.504-.503");
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

.zxmbqsb2m {
  d: path("M23.6 25.325c0-.401.325-.732.726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.39a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
