<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iP9hi2J)"><path fill="url(#i7LNuBe)" clip-rule="evenodd" class="tho3bgqqo"/><path fill="url(#il4Vtzd)" clip-rule="evenodd" class="tho3bgqqo"/><path fill="url(#ioYiUlc)" clip-rule="evenodd" class="tho3bgqqo"/><path fill="url(#iQvV7Dw)" clip-rule="evenodd" class="tho3bgqqo"/><path fill="url(#illXzcc)" clip-rule="evenodd" class="tho3bgqqo"/><path fill="url(#ie5BZpe)" clip-rule="evenodd" class="tho3bgqqo"/><path fill="url(#iGkaSnb)" clip-rule="evenodd" class="tho3bgqqo"/><path fill="url(#iR0N6cb)" clip-rule="evenodd" class="tho3bgqqo"/><path fill="url(#iDGV1jc)" clip-rule="evenodd" class="tho3bgqqo"/><path fill="url(#ihI6jDc)" clip-rule="evenodd" class="tho3bgqqo"/><path fill="url(#iEfkrMd)" clip-rule="evenodd" class="tho3bgqqo"/><path fill="url(#i0UF7Xc)" clip-rule="evenodd" class="tho3bgqqo"/></g><path fill="url(#iHNqk0X)" class="evso7acss"/><path fill="url(#imqjm9c)" class="evso7acss"/><g filter="url(#ivI7Isc)"><path fill="url(#ia8zscL)" class="i9t6f2bxc"/></g><path fill="url(#ivjsgxd)" class="jcl-2hb7f"/><path fill="url(#iod3k0b)" class="jcl-2hb7f"/><path class="hmnycxx5w"/><path fill="url(#iyhUdBG)" class="cllop4bqc"/><path fill="url(#iyeCLFd)" class="cllop4bqc"/><path fill="url(#i20rlAd)" class="cllop4bqc"/><path fill="url(#iRJv8Rc)" class="cu21d24az"/><path fill="url(#iyAgBob)" class="cu21d24az"/><path fill="url(#iLKBWPD)" class="cu21d24az"/><path fill="url(#i92uFDa)" class="cu21d24az"/><g filter="url(#ilW0ced)"><path class="pbxi84b9i"/></g><g filter="url(#itF6Ioi)"><path fill="url(#i5XOWcD)" class="z-t54tbit"/><path fill="url(#iIuGzte)" class="z-t54tbit"/></g><path fill="url(#iRR6nWc)" class="z-t54tbit"/><g filter="url(#i2q7Iuw)"><ellipse class="ijlx-8buq"/></g><g filter="url(#iuW9l3c)"><path fill="url(#ilz7GNd)" class="k7zk34bqa"/><path fill="url(#isFAYCe)" class="k7zk34bqa"/><path fill="url(#ioWJHub)" class="k7zk34bqa"/><path fill="url(#i9nPv5b)" class="k7zk34bqa"/></g><ellipse fill="url(#iKdWZUd)" class="skhx9acxb"/><ellipse fill="url(#iLpatmc)" class="skhx9acxb"/><rect fill="url(#idkBYJd)" class="qhe9mm7xm"/><path fill="url(#iCIUDTd)" class="oumjgbbsr"/><path fill="url(#i9EbKOc)" class="wdqycsape"/><g filter="url(#iBaB7qc)"><path fill="url(#iYb8uJW)" class="wivhzzb1z"/></g><g filter="url(#iaVXWZc)"><path fill="url(#iwlonRd)" class="b33bjs2vo"/><path fill="url(#itDSMac)" class="b33bjs2vo"/></g><g filter="url(#iTq722b)"><path class="u0b5hgb8f"/><path fill="url(#i6Mg3BX)" class="wrf7i3ase"/></g><g filter="url(#i4c0fqb)"><path class="vvwb2cbcm"/><path fill="url(#ijCDa2b)" class="w13b5wbfy"/></g><g filter="url(#ikzw07d)"><path fill="url(#iSAWume)" class="mhnfts14b"/><path fill="url(#iwa5GUd)" class="mhnfts14b"/><path fill="url(#itqyltb)" class="mhnfts14b"/><path fill="url(#inxwvfd)" class="mhnfts14b"/><path fill="url(#ie8HIke)" class="mhnfts14b"/><path fill="url(#ieB4O2b)" class="mhnfts14b"/><path fill="url(#imUMkHd)" class="mhnfts14b"/><path fill="url(#iTW8cnb)" class="mhnfts14b"/></g><path fill="url(#iMHMttt)" class="mhnfts14b"/><g filter="url(#ibmrSsd)"><path class="mx_j63fde"/></g><path fill="url(#ipLGSVd)" class="ul_3-64yi"/><path fill="url(#iogfT2s)" class="ul_3-64yi"/><g filter="url(#iP9n9lb)"><path class="e-kt1vcns"/><path fill="url(#iyJnlpd)" class="rcrlhkadi"/></g><g filter="url(#ibi0jJc)"><path stroke="url(#iT0G27Z)" class="pea_in86t"/></g><path class="ai6r1frov"/><g filter="url(#i7Dvv7d)"><path class="mmkp_sojq"/></g><g filter="url(#iSA3EYl)"><path class="suby1pj7r"/></g><path class="t7q_0hbld"/><path fill="url(#inOW9Yd)" class="ol-rryc7f"/><path class="e364_qkiw"/><g filter="url(#iYL3qiT)"><path class="jmi43kb6g"/><path fill="url(#iV3vzgc)" class="dr19ekrsf"/></g><g filter="url(#i6f5z7c)"><path fill="url(#iUahFWu)" class="db2c9ccim"/></g><path class="kgesynbbi"/><path fill="url(#iFS8DUc)" class="o0glw0bjm"/><path class="vv0158bin"/><g filter="url(#igFSOmQ)"><path fill="url(#iqIAZIe)" class="xs2ea2bhg"/></g><g filter="url(#if2I8lv)"><ellipse transform="rotate(-27.914 13.578 9.88)" class="kqfae6bxt"/><ellipse fill="url(#iLyujid)" transform="rotate(-27.914 13.578 9.88)" class="um9t3ebwz"/></g><g filter="url(#i6aMqwn)"><path class="fogjh3bek"/><path fill="url(#iLMBn6c)" class="l8m-iuknd"/></g><g filter="url(#i5WXrYb)"><path class="l351wccok"/><path fill="url(#i45hmEd)" class="l6ron3eli"/><path fill="url(#idoxIji)" class="l6ron3eli"/></g><g filter="url(#ip8aNrQ)"><path stroke="url(#i0w0Tdd)" class="hwu2nxbyk"/></g><g filter="url(#i9UCRTd)"><path class="ot-gr_p2e"/></g><defs><radialGradient id="il4Vtzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.73 13.074)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ioYiUlc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.914 13.342)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iQvV7Dw" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.926 8.162)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="illXzcc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.362 7.647)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ie5BZpe" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.175 11.613)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iGkaSnb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.98 6.825)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iR0N6cb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.54 9.722)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iDGV1jc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.66 7.982)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ihI6jDc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.989 -3.783)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iEfkrMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.89 9.686)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i0UF7Xc" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 2.776 7.12)scale(2.91973 2.69143)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="iHNqk0X" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.5824 -20.8203 0 16 18.372)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="gawd5obvo"/><stop offset="1" class="rn540obxc"/></radialGradient><radialGradient id="imqjm9c" cx="0" cy="0" r="1" gradientTransform="rotate(124.924 1.228 11.052)scale(12.8824 12.131)" gradientUnits="userSpaceOnUse"><stop class="y9rlcreuk"/><stop offset="1" class="xd0kopb5v"/></radialGradient><radialGradient id="ivjsgxd" cx="0" cy="0" r="1" gradientTransform="rotate(123.174 5.837 15.598)scale(11.5365 12.2083)" gradientUnits="userSpaceOnUse"><stop class="r3949-bju"/><stop offset="1" class="s9sui_61e"/></radialGradient><radialGradient id="iod3k0b" cx="0" cy="0" r="1" gradientTransform="rotate(100.184 -.325 14.065)scale(5.30229 7.65346)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="t-ehpbubw"/><stop offset="1" class="h61yu9bmy"/></radialGradient><radialGradient id="iyeCLFd" cx="0" cy="0" r="1" gradientTransform="matrix(5.4375 0 0 14.5199 23.18 29.622)" gradientUnits="userSpaceOnUse"><stop offset=".698" class="oj7ch-bkx"/><stop offset="1" class="ce13789qs"/></radialGradient><radialGradient id="i20rlAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.1762 .21924 0 23.68 29.955)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="x8ej_jb7y"/><stop offset="1" class="mjbwacbml"/></radialGradient><radialGradient id="iyAgBob" cx="0" cy="0" r="1" gradientTransform="matrix(-5.6875 0 0 -13.3438 9.555 29.779)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="wx3vdcbzg"/><stop offset="1" class="jug-l4bwb"/></radialGradient><radialGradient id="iLKBWPD" cx="0" cy="0" r="1" gradientTransform="matrix(.14062 -1.5668 5.45335 .48945 5.71 29.955)" gradientUnits="userSpaceOnUse"><stop class="x_0jnxbib"/><stop offset="1" class="wn7157b9l"/></radialGradient><radialGradient id="i92uFDa" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 0 0 -15.1051 8.383 29.955)" gradientUnits="userSpaceOnUse"><stop class="ujtti6ofv"/><stop offset="1" class="gewmlvbcg"/></radialGradient><radialGradient id="iRR6nWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.70312 .54687 -.67794 -.87163 19.711 23.404)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="l56m45bvi"/><stop offset="1" class="v2ucwt3jq"/></radialGradient><radialGradient id="isFAYCe" cx="0" cy="0" r="1" gradientTransform="rotate(111.034 1.943 12.516)scale(3.13667 4.32041)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="t6s1vnb2t"/><stop offset="1" class="zi8t_0buy"/></radialGradient><radialGradient id="ioWJHub" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53125 -3 0 20.742 15.341)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="mzeokobes"/><stop offset="1" class="qhzdg_bmj"/></radialGradient><radialGradient id="i9nPv5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.79294 -6.37953 0 19.492 15.403)" gradientUnits="userSpaceOnUse"><stop class="kuordwbwu"/><stop offset="1" class="mt9_xyb2a"/></radialGradient><radialGradient id="iKdWZUd" cx="0" cy="0" r="1" gradientTransform="rotate(126.363 3.443 13.942)scale(1.76569 1.94865)" gradientUnits="userSpaceOnUse"><stop class="su-lx9b4e"/><stop offset="1" class="fh2jv1bsu"/></radialGradient><radialGradient id="iLpatmc" cx="0" cy="0" r="1" gradientTransform="rotate(111.306 1.436 15.466)scale(1.67712 2.10568)" gradientUnits="userSpaceOnUse"><stop offset=".511" class="otqjsqgnm"/><stop offset="1" class="cz6js0bhr"/></radialGradient><radialGradient id="idkBYJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4093 2.43893 -3.68173 2.12742 15.552 16.258)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="e12r3_bhd"/><stop offset="1" class="tj_vqnqto"/></radialGradient><radialGradient id="iwlonRd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.07 11.012)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="itDSMac" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.102 8.892)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="i6Mg3BX" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.423 10.685)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="ijCDa2b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.43 10.573)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iSAWume" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.89 10.036)" gradientUnits="userSpaceOnUse"><stop class="shjvrn82k"/><stop offset=".818" class="jgtzombbj"/></radialGradient><radialGradient id="iwa5GUd" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 7.699 7.459)scale(2.25599 1.57104)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="itqyltb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0735 -3.47607 4.41049 1.36207 13.852 16.819)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="inxwvfd" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 3.755 12.462)scale(6.84714 6.88381)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="ie8HIke" cx="0" cy="0" r="1" gradientTransform="scale(6.60207 6.56691)rotate(90 .4 1.988)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="ieB4O2b" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.349 6.75)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="imUMkHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.332 9.617)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iTW8cnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.955 9.389)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iMHMttt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.127 11.105)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iyJnlpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.66477 -2.13445 .89534 -.27885 16.904 12.178)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="pq2t7lb5q"/><stop offset="1" class="flxl_4bem"/></radialGradient><radialGradient id="inOW9Yd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.213 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iV3vzgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.985 10.06)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFS8DUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.85 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iLyujid" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.8 -1.578)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLMBn6c" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.306 -4.152)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="i45hmEd" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.138 6.964)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="idoxIji" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.241 3.018)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iP9hi2J" width="15.268" height="15.768" x="8.522" y="1.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_926"/></filter><filter id="ivI7Isc" width="25.813" height="14.219" x="3.094" y="15.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".125"/></filter><filter id="ilW0ced" width="9.1" height="7.705" x="10.989" y="22.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".5"/></filter><filter id="itF6Ioi" width="7.926" height="6.427" x="12.029" y="22.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.670588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_926"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.407843 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_926" result="effect2_innerShadow_4002_926"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.317647 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_926" result="effect3_innerShadow_4002_926"/></filter><filter id="i2q7Iuw" width="3.095" height="3.11" x="14.16" y="18.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".25"/></filter><filter id="iuW9l3c" width="11.606" height="4.825" x="10.289" y="15.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.223529 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_926"/></filter><filter id="iBaB7qc" width="3.368" height="3.218" x="9.737" y="8.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_926"/></filter><filter id="iaVXWZc" width="3.218" height="3.468" x="19.25" y="8.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_926"/></filter><filter id="iTq722b" width="3.148" height="3.148" x="19.284" y="8.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".25"/></filter><filter id="i4c0fqb" width="2.648" height="2.648" x="10.041" y="9.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".125"/></filter><filter id="ikzw07d" width="10.191" height="11.027" x="10.936" y="5.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_926"/></filter><filter id="ibmrSsd" width="2.877" height="3.682" x="14.43" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".25"/></filter><filter id="iP9n9lb" width="2.047" height="2.696" x="15.158" y="10.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0941176 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_926"/></filter><filter id="ibi0jJc" width="3.702" height="1.526" x="14.18" y="12.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".05"/></filter><filter id="i7Dvv7d" width="3.001" height="1.285" x="16.973" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_926"/></filter><filter id="iSA3EYl" width="3.001" height="1.285" x="12.088" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_926"/></filter><filter id="iYL3qiT" width=".787" height=".696" x="17.479" y="9.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".05"/></filter><filter id="i6f5z7c" width=".891" height=".913" x="18.319" y="9.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".1"/></filter><filter id="igFSOmQ" width=".986" height="1.04" x="13.876" y="9.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".1"/></filter><filter id="if2I8lv" width=".913" height=".704" x="13.121" y="9.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".05"/></filter><filter id="i6aMqwn" width="4.412" height="4.713" x="9.577" y="3.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_926"/><feGaussianBlur result="effect2_foregroundBlur_4002_926" stdDeviation=".25"/></filter><filter id="i5WXrYb" width="8.767" height="5.782" x="12.861" y="2.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_926"/><feGaussianBlur result="effect2_foregroundBlur_4002_926" stdDeviation=".125"/></filter><filter id="ip8aNrQ" width="1.145" height="2.31" x="12.84" y="3.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".1"/></filter><filter id="i9UCRTd" width="6.427" height="3.372" x="15.45" y="4.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_926" stdDeviation=".375"/></filter><linearGradient id="i7LNuBe" x1="20.724" x2="13.919" y1="3.621" y2="16.225" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="ia8zscL" x1="16" x2="16" y1="16.236" y2="30.341" gradientUnits="userSpaceOnUse"><stop offset=".866" class="tyjpv6bnm"/><stop offset="1" class="xyu2htzlq"/></linearGradient><linearGradient id="iyhUdBG" x1="26.992" x2="26.773" y1="30.247" y2="27.497" gradientUnits="userSpaceOnUse"><stop class="pmf-vsdxp"/><stop offset="1" class="w6_8my7ls"/></linearGradient><linearGradient id="iRJv8Rc" x1="8.586" x2="5.336" y1="25.154" y2="25.154" gradientUnits="userSpaceOnUse"><stop offset=".183" class="annwmpbcg"/><stop offset="1" class="l85-jsb-f"/></linearGradient><linearGradient id="i5XOWcD" x1="18.555" x2="13.805" y1="23.966" y2="27.31" gradientUnits="userSpaceOnUse"><stop class="big423byp"/><stop offset="1" class="zbo4__e4e"/></linearGradient><linearGradient id="iIuGzte" x1="15.992" x2="15.992" y1="22.857" y2="24.201" gradientUnits="userSpaceOnUse"><stop class="ash9yfbkf"/><stop offset="1" class="k-dn1jb7a"/></linearGradient><linearGradient id="ilz7GNd" x1="14.773" x2="20.117" y1="19.06" y2="17.154" gradientUnits="userSpaceOnUse"><stop class="umjrh49bx"/><stop offset="1" class="d7r2s6row"/></linearGradient><linearGradient id="iCIUDTd" x1="8.847" x2="23.223" y1="15.383" y2="15.383" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i9EbKOc" x1="8.846" x2="23.222" y1="15.352" y2="15.352" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iYb8uJW" x1="9.737" x2="12.696" y1="10.661" y2="10.661" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="ipLGSVd" x1="20.403" x2="13.024" y1="10.69" y2="10.69" gradientUnits="userSpaceOnUse"><stop class="z14dz9exi"/><stop offset="1" class="o1uobmugz"/></linearGradient><linearGradient id="iogfT2s" x1="10.921" x2="12.37" y1="10.377" y2="10.377" gradientUnits="userSpaceOnUse"><stop class="f6x3qhriw"/><stop offset="1" class="onbz4ubrj"/></linearGradient><linearGradient id="iT0G27Z" x1="14.967" x2="15.428" y1="14.113" y2="13.401" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iUahFWu" x1="18.991" x2="18.677" y1="10.03" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqIAZIe" x1="14.593" x2="14.279" y1="10.03" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0w0Tdd" x1="13.14" x2="13.685" y1="4.375" y2="5.649" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-superhero-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.ai6r1frov {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M16.031 13.485c-.52 0-1.01-.125-1.421-.345c-.141-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.249 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.annwmpbcg {
  stop-color: var(--svg-color--3e80f0, #3E80F0);
}

.ash9yfbkf {
  stop-color: var(--svg-color--40a0f8, #40A0F8);
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b33bjs2vo {
  d: path("M20.859 12.182a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.big423byp {
  stop-color: var(--svg-color--47a1ff, #47A1FF);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.ce13789qs {
  stop-color: var(--svg-color--528adb, #528ADB);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cllop4bqc {
  d: path("M23.68 18.468v11.487h4.343v-.036c-.22-5.447-1.881-9.174-4.343-11.451");
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cu21d24az {
  d: path("M8.383 18.468v11.487H4.039v-.036c.22-5.447 1.882-9.174 4.344-11.451");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cz6js0bhr {
  stop-color: var(--svg-color--d79d4a, #D79D4A);
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d7r2s6row {
  stop-color: var(--svg-color--ff3656, #FF3656);
}

.db2c9ccim {
  d: path("M19.01 10.274a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dr19ekrsf {
  d: path("M18.15 9.688c.063.085-.07.189-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.e-kt1vcns {
  fill: var(--svg-color--3f2827, #3F2827);
  d: path("m15.675 10.517l-.494 1.582a.502.502 0 0 0 .484.65h.732c.343 0 .586-.33.485-.65l-.495-1.582c-.106-.35-.6-.35-.712 0");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e12r3_bhd {
  stop-color: var(--svg-color--3c212f, #3C212F);
}

.e364_qkiw {
  fill: var(--svg-color--000, #000);
  d: path("M17.704 10.392a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.235");
}

.evso7acss {
  d: path("M2.063 29.955c0-1.969.39-6.76 3.216-9.86C8.81 16.222 13.793 15.643 16 15.643s7.19.579 10.721 4.454c2.826 3.1 3.217 7.89 3.217 9.859z");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f6x3qhriw {
  stop-color: var(--svg-color--ab2d46, #AB2D46);
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fh2jv1bsu {
  stop-color: var(--svg-color--f2bb43, #F2BB43);
}

.flxl_4bem {
  stop-color: var(--svg-color--543a37, #543A37);
  stop-opacity: 0;
}

.fogjh3bek {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M10.962 4.585c.566-.6 1.636-.6 2.131-.51l.396 1.29c-.253-.04-.478.05-.668.234c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gawd5obvo {
  stop-color: var(--svg-color--ff3b9a, #FF3B9A);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gewmlvbcg {
  stop-color: var(--svg-color--2154ca, #2154CA);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h61yu9bmy {
  stop-color: var(--svg-color--3a7ad3, #3A7AD3);
  stop-opacity: 0;
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hmnycxx5w {
  fill: var(--svg-color--4e9eff, #4E9EFF);
  d: path("M23.68 18.468v11.487h4.343v-.036c-.22-5.447-1.881-9.174-4.343-11.451");
}

.hwu2nxbyk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.14 4.031c.023.243.235 1.157.545 1.71");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i9t6f2bxc {
  d: path("M3.344 29.955c0-1.887.355-6.479 2.92-9.45c3.207-3.715 7.732-4.269 9.736-4.269s6.529.554 9.736 4.269c2.565 2.971 2.92 7.563 2.92 9.45z");
}

.ijlx-8buq {
  cx: 15.708px;
  cy: 20.263px;
  fill: var(--svg-color--2f62b7, #2F62B7);
  rx: 1.048px;
  ry: 1.055px;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jcl-2hb7f {
  d: path("M16.031 15.638c-6.228 0-11.584 4.188-11.992 14.281v.036h23.984v-.036c-.408-10.093-5.764-14.28-11.992-14.28");
}

.jgtzombbj {
  stop-color: var(--svg-color--3c2727, #3C2727);
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jmi43kb6g {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.15 9.688c.063.085-.07.189-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.jug-l4bwb {
  stop-color: var(--svg-color--407dbe, #407DBE);
}

.k-dn1jb7a {
  stop-color: var(--svg-color--4392f9, #4392F9);
  stop-opacity: 0;
}

.k7zk34bqa {
  d: path("m15.992 20.435l-5.04-3.023c-.323-.2-.663-.512-.663-.98c0-.497.585-.533.885-.544l4.818-.078l4.819.078c.3.01.884.047.884.543c0 .469-.34.781-.663.98z");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kgesynbbi {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.64 9.227c-.653 0-1.205.45-1.355 1.06c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.128");
}

.kqfae6bxt {
  cx: 13.578px;
  cy: 9.88px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kuordwbwu {
  stop-color: var(--svg-color--bb1135, #BB1135);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l351wccok {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.428 2.783c-1.133-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.671-5.921-5.24z");
}

.l56m45bvi {
  stop-color: var(--svg-color--53b7ff, #53B7FF);
}

.l6ron3eli {
  d: path("M15.428 2.783c-1.133-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.671-5.921-5.24z");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l85-jsb-f {
  stop-color: var(--svg-color--3e77d8, #3E77D8);
}

.l8m-iuknd {
  d: path("M10.962 4.585c.566-.6 1.636-.6 2.131-.51l.396 1.29c-.253-.04-.478.05-.668.234c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhnfts14b {
  d: path("M10.944 9.31h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.438l.051-.02l.051-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .462-.05a3.86 3.86 0 0 0 3.189 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.122 2.802-2.31 4.684-4.982 4.684s-4.86-1.882-4.984-4.684z");
}

.mjbwacbml {
  stop-color: var(--svg-color--286adf, #286ADF);
  stop-opacity: 0;
}

.mmkp_sojq {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.173 10.004c.266-.467.67-.835 1.538-.835c.38 0 .747.105 1.072.368c.27.218.233.496.025.6l-.556.317c-.652-.21-1.373-.24-2.079-.45");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9_xyb2a {
  stop-color: var(--svg-color--bb1135, #BB1135);
  stop-opacity: 0;
}

.mx_j63fde {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.639 10.35l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.494-.376-.613 0");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mzeokobes {
  stop-color: var(--svg-color--f04451, #F04451);
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.o0glw0bjm {
  d: path("M13.847 9.5a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.o1uobmugz {
  stop-color: var(--svg-color--c31251, #C31251);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oj7ch-bkx {
  stop-color: var(--svg-color--528adb, #528ADB);
  stop-opacity: 0;
}

.ol-rryc7f {
  d: path("M18.215 9.5a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.onbz4ubrj {
  stop-color: var(--svg-color--ba3950, #BA3950);
  stop-opacity: 0;
}

.ot-gr_p2e {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.438 6.392l-1.426.263a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.844 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.otqjsqgnm {
  stop-color: var(--svg-color--f6c546, #F6C546);
  stop-opacity: 0;
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.oumjgbbsr {
  d: path("M16.386 15.353c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pbxi84b9i {
  fill: var(--svg-color--2f63d5, #2F63D5);
  d: path("M12.875 23.42a.885.885 0 0 0-.763 1.333l2.143 3.638a1.49 1.49 0 0 0 2.568 0l2.142-3.638a.885.885 0 0 0-.762-1.334z");
}

.pea_in86t {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.031 13.485c-.52 0-1.01-.125-1.421-.345c-.141-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.249 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmf-vsdxp {
  stop-color: var(--svg-color--4d87f8, #4D87F8);
}

.pq2t7lb5q {
  stop-color: var(--svg-color--543a37, #543A37);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qhe9mm7xm {
  width: 4.109px;
  height: 5.399px;
  x: 13.933px;
  y: 13.298px;
  rx: 2.055px;
}

.qhzdg_bmj {
  stop-color: var(--svg-color--f04451, #F04451);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r3949-bju {
  stop-color: var(--svg-color--4690e6, #4690E6);
}

.rcrlhkadi {
  d: path("m15.675 10.517l-.494 1.582a.502.502 0 0 0 .484.65h.732c.343 0 .586-.33.485-.65l-.495-1.582c-.106-.35-.6-.35-.712 0");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rn540obxc {
  stop-color: var(--svg-color--ee344d, #EE344D);
}

.s9sui_61e {
  stop-color: var(--svg-color--3e75e1, #3E75E1);
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.shjvrn82k {
  stop-color: var(--svg-color--513531, #513531);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.skhx9acxb {
  cx: 15.992px;
  cy: 20.17px;
  rx: 1.048px;
  ry: 1.055px;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.su-lx9b4e {
  stop-color: var(--svg-color--fff14e, #FFF14E);
}

.suby1pj7r {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.89 10.004c-.266-.467-.67-.835-1.538-.835c-.38 0-.747.105-1.073.368c-.269.218-.233.496-.024.6l.555.317c.652-.21 1.373-.24 2.08-.45");
}

.t-ehpbubw {
  stop-color: var(--svg-color--3062ac, #3062AC);
}

.t6s1vnb2t {
  stop-color: var(--svg-color--780438, #780438);
}

.t7q_0hbld {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.422 9.227c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.tho3bgqqo {
  fill-rule: evenodd;
  d: path("M23.217 11.983a3.25 3.25 0 0 0 .323-1.427a3.3 3.3 0 0 0-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.004a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.003.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.3 3.3 0 0 0-.324 1.407a3.213 3.213 0 0 0 3.218 3.218h8.582a3.213 3.213 0 0 0 2.895-4.625a.52.52 0 0 1 0-.455m-12.26-2.672h-.013l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.46.051l-.083.194a2.3 2.3 0 0 1-1.24 1.255l-.052.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.tj_vqnqto {
  stop-color: var(--svg-color--4c2d2b, #4C2D2B);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tyjpv6bnm {
  stop-color: var(--svg-color--790b2c, #790B2C);
}

.u0b5hgb8f {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.859 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ujtti6ofv {
  stop-color: var(--svg-color--2154ca, #2154CA);
}

.ul_3-64yi {
  d: path("M10.941 9.31h-.012l.077 2.01h.315q.282 0 .534.12l.247.12c.09.04.178.08.267.11l.218.07c.425.13.88.14 1.306.02l.276-.08q.167-.045.317-.12l.228-.11q.252-.12.534-.12h.346l.164-.668c.119-.39.264-.39.383 0l.094.668h.467q.282 0 .534.12l.208.1c.108.05.227.1.346.13l.307.09c.425.12.89.11 1.305-.04l.178-.06l.238-.09l.267-.12q.252-.12.534-.12h.394l.098-2.554l-.006-.106h-.387a1.55 1.55 0 0 1-.712-.24l-.05-.03a2.2 2.2 0 0 0-.554-.28c-.425-.15-.88-.16-1.305-.04l-.129.03c-.237.07-.465.17-.673.32a1.2 1.2 0 0 1-.712.22h-1.226c-.258 0-.505-.08-.713-.22l-.01-.01a2.3 2.3 0 0 0-.643-.31l-.089-.03c-.425-.12-.88-.12-1.305.02l-.04.01c-.208.07-.405.17-.593.29l-.03.03c-.218.14-.465.22-.722.22h-.288l-.003.08l.01.305z");
}

.um9t3ebwz {
  cx: 13.578px;
  cy: 9.88px;
  rx: 0.39px;
  ry: 0.197px;
}

.umjrh49bx {
  stop-color: var(--svg-color--ce1f66, #CE1F66);
}

.v2ucwt3jq {
  stop-color: var(--svg-color--49a3ff, #49A3FF);
  stop-opacity: 0;
}

.vv0158bin {
  fill: var(--svg-color--000, #000);
  d: path("M14.358 10.392a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.904a.5.5 0 0 0 .061-.235");
}

.vvwb2cbcm {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.365 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w13b5wbfy {
  d: path("M11.365 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.w6_8my7ls {
  stop-color: var(--svg-color--4b99ff, #4B99FF);
  stop-opacity: 0;
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wdqycsape {
  d: path("M16.056 15.353h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wivhzzb1z {
  d: path("M11.346 12.182a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.wn7157b9l {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
  stop-opacity: 0;
}

.wrf7i3ase {
  d: path("M20.859 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.wx3vdcbzg {
  stop-color: var(--svg-color--407dbe, #407DBE);
  stop-opacity: 0;
}

.x_0jnxbib {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.x8ej_jb7y {
  stop-color: var(--svg-color--286adf, #286ADF);
}

.xd0kopb5v {
  stop-color: var(--svg-color--bf2370, #BF2370);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xs2ea2bhg {
  d: path("M14.663 10.287c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xyu2htzlq {
  stop-color: var(--svg-color--790b2c, #790B2C);
  stop-opacity: 0;
}

.y9rlcreuk {
  stop-color: var(--svg-color--bf2370, #BF2370);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z-t54tbit {
  d: path("M13.13 22.998a.95.95 0 0 0-.818 1.432l2.302 3.907a1.6 1.6 0 0 0 2.757 0l2.301-3.907a.95.95 0 0 0-.819-1.433z");
}

.z14dz9exi {
  stop-color: var(--svg-color--ff1781, #FF1781);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zbo4__e4e {
  stop-color: var(--svg-color--3f83f1, #3F83F1);
}

.zi8t_0buy {
  stop-color: var(--svg-color--780438, #780438);
  stop-opacity: 0;
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
