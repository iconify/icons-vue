<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iilXOUd" class="v88cgvkze"/></defs><g class="ft5dv1b6b"><g filter="url(#ihzZ4AQ)"><path fill="url(#iOGf5Il)" clip-rule="evenodd" class="d8uv54b2x"/><path fill="url(#il4Vtzd)" clip-rule="evenodd" class="d8uv54b2x"/><path fill="url(#ioYiUlc)" clip-rule="evenodd" class="d8uv54b2x"/><path fill="url(#iQvV7Dw)" clip-rule="evenodd" class="d8uv54b2x"/><path fill="url(#illXzcc)" clip-rule="evenodd" class="d8uv54b2x"/><path fill="url(#ie5BZpe)" clip-rule="evenodd" class="d8uv54b2x"/><path fill="url(#iGkaSnb)" clip-rule="evenodd" class="d8uv54b2x"/><path fill="url(#iR0N6cb)" clip-rule="evenodd" class="d8uv54b2x"/><path fill="url(#iDGV1jc)" clip-rule="evenodd" class="d8uv54b2x"/><path fill="url(#ihI6jDc)" clip-rule="evenodd" class="d8uv54b2x"/><path fill="url(#iEfkrMd)" clip-rule="evenodd" class="d8uv54b2x"/></g><path fill="url(#iHNqk0X)" class="evso7acss"/><path fill="url(#imqjm9c)" class="evso7acss"/><g filter="url(#iZOopLg)"><path fill="url(#ia8zscL)" class="meop8wekz"/></g><path fill="url(#ivjsgxd)" class="jcl-2hb7f"/><path fill="url(#iod3k0b)" class="jcl-2hb7f"/><path class="hmnycxx5w"/><path fill="url(#iyhUdBG)" class="cllop4bqc"/><path fill="url(#iyeCLFd)" class="cllop4bqc"/><path fill="url(#i20rlAd)" class="cllop4bqc"/><path fill="url(#iRJv8Rc)" class="cu21d24az"/><path fill="url(#iyAgBob)" class="cu21d24az"/><path fill="url(#iLKBWPD)" class="cu21d24az"/><path fill="url(#i92uFDa)" class="cu21d24az"/><g filter="url(#iDUewyd)"><path class="pbxi84b9i"/></g><g filter="url(#iQEpKHb)"><path fill="url(#i5XOWcD)" class="z-t54tbit"/><path fill="url(#iIuGzte)" class="z-t54tbit"/></g><path fill="url(#iRR6nWc)" class="z-t54tbit"/><g filter="url(#ij9BaJb)"><ellipse class="ijlx-8buq"/></g><g filter="url(#i5JvS1H)"><path fill="url(#ilz7GNd)" class="k7zk34bqa"/><path fill="url(#isFAYCe)" class="k7zk34bqa"/><path fill="url(#ioWJHub)" class="k7zk34bqa"/><path fill="url(#i9nPv5b)" class="k7zk34bqa"/></g><ellipse fill="url(#iKdWZUd)" class="kfesl3bzn"/><ellipse fill="url(#iLpatmc)" class="kfesl3bzn"/><rect fill="url(#i2VQXKd)" class="qhe9mm7xm"/><rect fill="url(#iUBOkbs)" class="qhe9mm7xm"/><path fill="url(#iCIUDTd)" class="oumjgbbsr"/><path fill="url(#i9EbKOc)" class="wdqycsape"/><g filter="url(#i5vkQ3b)"><path fill="url(#iqO29Ed)" class="s_7wpwboy"/></g><g filter="url(#irtCovd)"><path fill="url(#iJ2WNAd)" class="b33bjs2vo"/><path fill="url(#i6QDCxe)" class="b33bjs2vo"/></g><g filter="url(#i0l8awc)"><path class="r3e74cczy"/><path fill="url(#i9Zob5p)" class="wrf7i3ase"/></g><g filter="url(#imEshGh)"><path class="n1s_bubxl"/><path fill="url(#iVUcgce)" class="w13b5wbfy"/></g><g filter="url(#i6uKkKe)"><path fill="url(#iwutFNS)" class="mhnfts14b"/><path fill="url(#ix3nFKe)" class="mhnfts14b"/><path fill="url(#iJYD7Jb)" class="mhnfts14b"/><path fill="url(#idKxf2K)" class="mhnfts14b"/><path fill="url(#icWkQ2T)" class="mhnfts14b"/><path fill="url(#iYzmKoc)" class="mhnfts14b"/><path fill="url(#iRaGSOe)" class="mhnfts14b"/><path fill="url(#iqUcIye)" class="mhnfts14b"/></g><path fill="url(#i72bzSd)" class="mhnfts14b"/><path fill="url(#iVdPifd)" class="mhnfts14b"/><g filter="url(#iYcGj7O)"><path class="nfyrauyka"/></g><path fill="url(#iGsV84d)" class="nwgo2jboh"/><path fill="url(#iVyKaUb)" class="nwgo2jboh"/><g filter="url(#inF4qtd)"><path class="uwyaafbnv"/><path fill="url(#iB1Fffc)" class="l-fx-bc4i"/></g><g filter="url(#ilvq4yd)"><use href="#iilXOUd"/><path stroke="url(#iua60PE)" class="p0ux8fbne"/></g><use href="#iilXOUd"/><g filter="url(#iPTMbZd)"><path class="pn3_klbyd"/></g><g filter="url(#iT8HNWd)"><path class="zypb88bgi"/></g><path class="t7q_0hbld"/><path fill="url(#inOW9Yd)" class="ol-rryc7f"/><path class="e364_qkiw"/><g filter="url(#ispMYJd)"><path class="s4p84bb8g"/><path fill="url(#iV3vzgc)" class="yh1zq-bfb"/></g><g filter="url(#iRwww7c)"><path fill="url(#iUahFWu)" class="db2c9ccim"/></g><path class="kgesynbbi"/><path fill="url(#iFS8DUc)" class="o0glw0bjm"/><path class="vv0158bin"/><g filter="url(#iOdFSyE)"><path fill="url(#iqIAZIe)" class="xs2ea2bhg"/></g><g filter="url(#iEDHJce)"><ellipse transform="rotate(-27.914 13.578 9.88)" class="kqfae6bxt"/><ellipse fill="url(#iLyujid)" transform="rotate(-27.914 13.578 9.88)" class="um9t3ebwz"/></g><g filter="url(#iL3Oxlb)"><path class="wwtjf56yr"/><path fill="url(#iLMBn6c)" class="l8m-iuknd"/></g><g filter="url(#iMn3PTb)"><path class="xvvg0mbfp"/><path fill="url(#i45hmEd)" class="l6ron3eli"/><path fill="url(#idoxIji)" class="l6ron3eli"/></g><g filter="url(#iXyh7le)"><path stroke="url(#i0w0Tdd)" class="hwu2nxbyk"/></g><g filter="url(#idSqwhc)"><path class="b23vv_bnd"/></g><defs><radialGradient id="il4Vtzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.73 13.074)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ioYiUlc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.914 13.342)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iQvV7Dw" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.926 8.162)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="illXzcc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.362 7.647)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ie5BZpe" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.175 11.613)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iGkaSnb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.98 6.825)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iR0N6cb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.54 9.722)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iDGV1jc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.66 7.982)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ihI6jDc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.989 -3.783)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iEfkrMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.89 9.686)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iHNqk0X" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.5824 -20.8203 0 16 18.372)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="gawd5obvo"/><stop offset="1" class="rn540obxc"/></radialGradient><radialGradient id="imqjm9c" cx="0" cy="0" r="1" gradientTransform="rotate(124.924 1.228 11.052)scale(12.8824 12.131)" gradientUnits="userSpaceOnUse"><stop class="y9rlcreuk"/><stop offset="1" class="xd0kopb5v"/></radialGradient><radialGradient id="ivjsgxd" cx="0" cy="0" r="1" gradientTransform="rotate(123.174 5.837 15.598)scale(11.5365 12.2083)" gradientUnits="userSpaceOnUse"><stop class="r3949-bju"/><stop offset="1" class="s9sui_61e"/></radialGradient><radialGradient id="iod3k0b" cx="0" cy="0" r="1" gradientTransform="rotate(100.184 -.325 14.065)scale(5.30229 7.65346)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="t-ehpbubw"/><stop offset="1" class="h61yu9bmy"/></radialGradient><radialGradient id="iyeCLFd" cx="0" cy="0" r="1" gradientTransform="matrix(5.4375 0 0 14.5199 23.18 29.622)" gradientUnits="userSpaceOnUse"><stop offset=".698" class="oj7ch-bkx"/><stop offset="1" class="ce13789qs"/></radialGradient><radialGradient id="i20rlAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.1762 .21924 0 23.68 29.955)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="x8ej_jb7y"/><stop offset="1" class="mjbwacbml"/></radialGradient><radialGradient id="iyAgBob" cx="0" cy="0" r="1" gradientTransform="matrix(-5.6875 0 0 -13.3438 9.555 29.779)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="wx3vdcbzg"/><stop offset="1" class="jug-l4bwb"/></radialGradient><radialGradient id="iLKBWPD" cx="0" cy="0" r="1" gradientTransform="matrix(.14062 -1.5668 5.45335 .48945 5.71 29.955)" gradientUnits="userSpaceOnUse"><stop class="x_0jnxbib"/><stop offset="1" class="wn7157b9l"/></radialGradient><radialGradient id="i92uFDa" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 0 0 -15.1051 8.383 29.955)" gradientUnits="userSpaceOnUse"><stop class="ujtti6ofv"/><stop offset="1" class="gewmlvbcg"/></radialGradient><radialGradient id="iRR6nWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.70312 .54687 -.67794 -.87163 19.711 23.404)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="l56m45bvi"/><stop offset="1" class="v2ucwt3jq"/></radialGradient><radialGradient id="isFAYCe" cx="0" cy="0" r="1" gradientTransform="rotate(111.034 1.943 12.516)scale(3.13667 4.32041)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="t6s1vnb2t"/><stop offset="1" class="zi8t_0buy"/></radialGradient><radialGradient id="ioWJHub" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53125 -3 0 20.742 15.341)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="mzeokobes"/><stop offset="1" class="qhzdg_bmj"/></radialGradient><radialGradient id="i9nPv5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.79294 -6.37953 0 19.492 15.403)" gradientUnits="userSpaceOnUse"><stop class="kuordwbwu"/><stop offset="1" class="mt9_xyb2a"/></radialGradient><radialGradient id="iKdWZUd" cx="0" cy="0" r="1" gradientTransform="rotate(126.363 3.443 13.942)scale(1.76569 1.94865)" gradientUnits="userSpaceOnUse"><stop class="su-lx9b4e"/><stop offset="1" class="fh2jv1bsu"/></radialGradient><radialGradient id="iLpatmc" cx="0" cy="0" r="1" gradientTransform="rotate(111.306 1.436 15.466)scale(1.67712 2.10568)" gradientUnits="userSpaceOnUse"><stop offset=".511" class="otqjsqgnm"/><stop offset="1" class="cz6js0bhr"/></radialGradient><radialGradient id="i2VQXKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.25001 1.79325 -2.57261 1.79328 15.711 16.903)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="wszl1wbzf"/><stop offset="1" class="pij655hmh"/></radialGradient><radialGradient id="iUBOkbs" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 .60936 -.75278 -3.39724 16.586 17.122)" gradientUnits="userSpaceOnUse"><stop offset=".555" class="sii6nfq-p"/><stop offset="1" class="k-b7nnodh"/></radialGradient><radialGradient id="iJ2WNAd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.07 11.012)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="i6QDCxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.102 8.892)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="i9Zob5p" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.423 10.686)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iVUcgce" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.715 5.287)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iwutFNS" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.89 10.036)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="ix3nFKe" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.856 7.338)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iJYD7Jb" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.87 16.543)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="idKxf2K" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.7332 -6.25618 0 16.031 9.81)" gradientUnits="userSpaceOnUse"><stop offset=".835" class="mg10me7tz"/><stop offset="1" class="e5l3gf6aw"/></radialGradient><radialGradient id="icWkQ2T" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.349 6.75)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iYzmKoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.332 9.617)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iRaGSOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.955 9.389)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iqUcIye" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.415 7.301)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="i72bzSd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.127 11.105)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iVdPifd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -1.56249 1.85525 2.0779 11.995 15.764)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="iB1Fffc" cx="0" cy="0" r="1" gradientTransform="matrix(-.66477 -2.13446 .89534 -.27885 16.904 12.178)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="a90zvcbfo"/><stop offset="1" class="p47czub_x"/></radialGradient><radialGradient id="inOW9Yd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.213 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iV3vzgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.985 10.06)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFS8DUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.85 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iLyujid" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.8 -1.578)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLMBn6c" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.306 -4.152)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="i45hmEd" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.138 6.964)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="idoxIji" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.241 3.018)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="ihzZ4AQ" width="15.268" height="15.768" x="8.522" y="1.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_929"/></filter><filter id="iZOopLg" width="25.813" height="14.219" x="3.094" y="15.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".125"/></filter><filter id="iDUewyd" width="9.1" height="7.705" x="10.989" y="22.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".5"/></filter><filter id="iQEpKHb" width="7.926" height="6.427" x="12.029" y="22.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.670588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_929"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.407843 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_929" result="effect2_innerShadow_4002_929"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.317647 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_929" result="effect3_innerShadow_4002_929"/></filter><filter id="ij9BaJb" width="3.095" height="3.11" x="14.16" y="18.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".25"/></filter><filter id="i5JvS1H" width="11.606" height="4.825" x="10.289" y="15.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.223529 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_929"/></filter><filter id="i5vkQ3b" width="3.368" height="3.218" x="9.737" y="8.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_929"/></filter><filter id="irtCovd" width="3.218" height="3.468" x="19.25" y="8.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_929"/></filter><filter id="i0l8awc" width="3.148" height="3.148" x="19.284" y="8.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".25"/></filter><filter id="imEshGh" width="2.648" height="2.648" x="10.041" y="9.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".125"/></filter><filter id="i6uKkKe" width="10.191" height="11.127" x="10.936" y="5.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_929"/></filter><filter id="iYcGj7O" width="2.877" height="3.682" x="14.43" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".25"/></filter><filter id="inF4qtd" width="2.047" height="2.696" x="15.158" y="10.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.25098 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_929"/></filter><filter id="ilvq4yd" width="3.702" height="1.526" x="14.18" y="12.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".05"/></filter><filter id="iPTMbZd" width="3.001" height="1.285" x="16.973" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_929"/></filter><filter id="iT8HNWd" width="3.001" height="1.285" x="12.088" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_929"/></filter><filter id="ispMYJd" width=".787" height=".696" x="17.479" y="9.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".05"/></filter><filter id="iRwww7c" width=".891" height=".913" x="18.319" y="9.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".1"/></filter><filter id="iOdFSyE" width=".986" height="1.04" x="13.876" y="9.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".1"/></filter><filter id="iEDHJce" width=".913" height=".704" x="13.121" y="9.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".05"/></filter><filter id="iL3Oxlb" width="4.312" height="4.613" x="9.677" y="3.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_929"/><feGaussianBlur result="effect2_foregroundBlur_4002_929" stdDeviation=".2"/></filter><filter id="iMn3PTb" width="8.767" height="5.782" x="12.861" y="2.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_929"/><feGaussianBlur result="effect2_foregroundBlur_4002_929" stdDeviation=".125"/></filter><filter id="iXyh7le" width="1.145" height="2.31" x="12.84" y="3.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".1"/></filter><filter id="idSqwhc" width="6.927" height="3.872" x="15.2" y="4.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_929" stdDeviation=".5"/></filter><linearGradient id="iOGf5Il" x1="20.724" x2="13.919" y1="3.621" y2="16.225" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="ia8zscL" x1="16" x2="16" y1="16.236" y2="30.341" gradientUnits="userSpaceOnUse"><stop offset=".866" class="tyjpv6bnm"/><stop offset="1" class="xyu2htzlq"/></linearGradient><linearGradient id="iyhUdBG" x1="26.992" x2="26.773" y1="30.247" y2="27.497" gradientUnits="userSpaceOnUse"><stop class="pmf-vsdxp"/><stop offset="1" class="w6_8my7ls"/></linearGradient><linearGradient id="iRJv8Rc" x1="8.586" x2="5.336" y1="25.154" y2="25.154" gradientUnits="userSpaceOnUse"><stop offset=".183" class="annwmpbcg"/><stop offset="1" class="l85-jsb-f"/></linearGradient><linearGradient id="i5XOWcD" x1="18.555" x2="13.805" y1="23.966" y2="27.31" gradientUnits="userSpaceOnUse"><stop class="big423byp"/><stop offset="1" class="zbo4__e4e"/></linearGradient><linearGradient id="iIuGzte" x1="15.992" x2="15.992" y1="22.857" y2="24.201" gradientUnits="userSpaceOnUse"><stop class="ash9yfbkf"/><stop offset="1" class="k-dn1jb7a"/></linearGradient><linearGradient id="ilz7GNd" x1="14.773" x2="20.117" y1="19.06" y2="17.154" gradientUnits="userSpaceOnUse"><stop class="umjrh49bx"/><stop offset="1" class="d7r2s6row"/></linearGradient><linearGradient id="iCIUDTd" x1="8.847" x2="23.223" y1="15.383" y2="15.383" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i9EbKOc" x1="8.846" x2="23.222" y1="15.352" y2="15.352" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iqO29Ed" x1="9.788" x2="11.028" y1="10.66" y2="10.66" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iGsV84d" x1="20.418" x2="13.039" y1="10.692" y2="10.692" gradientUnits="userSpaceOnUse"><stop class="z14dz9exi"/><stop offset="1" class="o1uobmugz"/></linearGradient><linearGradient id="iVyKaUb" x1="10.936" x2="12.385" y1="10.38" y2="10.38" gradientUnits="userSpaceOnUse"><stop class="f6x3qhriw"/><stop offset="1" class="onbz4ubrj"/></linearGradient><linearGradient id="iua60PE" x1="14.967" x2="15.428" y1="14.113" y2="13.401" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iUahFWu" x1="18.991" x2="18.677" y1="10.03" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqIAZIe" x1="14.593" x2="14.279" y1="10.03" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0w0Tdd" x1="13.14" x2="13.685" y1="4.375" y2="5.649" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-superhero-medium-dark" /></template>
<style>
.a90zvcbfo {
  stop-color: var(--svg-color--90685e, #90685E);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.annwmpbcg {
  stop-color: var(--svg-color--3e80f0, #3E80F0);
}

.ash9yfbkf {
  stop-color: var(--svg-color--40a0f8, #40A0F8);
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b23vv_bnd {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m18.438 6.392l-1.426.262a.688.688 0 1 1-.125-1.364h2.34c1.385 0 1.844 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.b33bjs2vo {
  d: path("M20.859 12.182a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.big423byp {
  stop-color: var(--svg-color--47a1ff, #47A1FF);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
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

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
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

.d7r2s6row {
  stop-color: var(--svg-color--ff3656, #FF3656);
}

.d8uv54b2x {
  fill-rule: evenodd;
  d: path("M23.217 11.983c.212-.435.323-.92.323-1.427a3.3 3.3 0 0 0-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.004a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.003.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.895-4.625a.52.52 0 0 1 0-.455m-12.26-2.672h-.013l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.46.051l-.083.194c-.226.561-.656.99-1.19 1.235l-.05.02l-.052.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.db2c9ccim {
  d: path("M19.01 10.274a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e364_qkiw {
  fill: var(--svg-color--000, #000);
  d: path("M17.704 10.392a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.235");
}

.e5l3gf6aw {
  stop-color: var(--svg-color--643343, #643343);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.evso7acss {
  d: path("M2.063 29.955c0-1.969.39-6.76 3.216-9.86C8.81 16.222 13.793 15.643 16 15.643s7.19.579 10.721 4.454c2.826 3.1 3.217 7.89 3.217 9.859z");
}

.f6x3qhriw {
  stop-color: var(--svg-color--ab2d46, #AB2D46);
}

.fh2jv1bsu {
  stop-color: var(--svg-color--f2bb43, #F2BB43);
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
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

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
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

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hmnycxx5w {
  fill: var(--svg-color--4e9eff, #4E9EFF);
  d: path("M23.68 18.468v11.487h4.343v-.036c-.22-5.447-1.881-9.174-4.343-11.451");
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hwu2nxbyk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.14 4.031c.023.243.235 1.157.545 1.71");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
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

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jug-l4bwb {
  stop-color: var(--svg-color--407dbe, #407DBE);
}

.k-b7nnodh {
  stop-color: var(--svg-color--5c2f30, #5C2F30);
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

.kfesl3bzn {
  cx: 15.992px;
  cy: 20.169px;
  rx: 1.048px;
  ry: 1.055px;
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

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l-fx-bc4i {
  d: path("m15.675 10.517l-.494 1.582a.502.502 0 0 0 .484.65h.732c.343 0 .586-.33.485-.65l-.495-1.582c-.106-.351-.6-.351-.712 0");
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
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

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meop8wekz {
  d: path("M3.344 29.955c0-1.887.355-6.48 2.92-9.45c3.207-3.715 7.732-4.269 9.736-4.269s6.529.554 9.736 4.268c2.565 2.972 2.92 7.564 2.92 9.45z");
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mhnfts14b {
  d: path("M10.944 9.31h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.438l.051-.02l.051-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .462-.05a3.86 3.86 0 0 0 3.189 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.122 2.802-2.31 4.684-4.982 4.684s-4.86-1.882-4.984-4.684z");
}

.mjbwacbml {
  stop-color: var(--svg-color--286adf, #286ADF);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9_xyb2a {
  stop-color: var(--svg-color--bb1135, #BB1135);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mzeokobes {
  stop-color: var(--svg-color--f04451, #F04451);
}

.n1s_bubxl {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.365 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.nfyrauyka {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.639 10.35l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.494-.376-.613 0");
}

.nwgo2jboh {
  d: path("M10.956 9.313h-.012l.077 2.01h.315q.282 0 .534.12l.247.12c.09.04.178.08.267.11l.218.07c.425.13.88.14 1.306.02l.277-.08c.108-.03.217-.07.316-.12l.228-.11q.252-.12.534-.12h.346l.164-.669c.12-.39.265-.39.383 0l.094.668h.467q.282 0 .534.12l.208.1c.109.05.227.1.346.13l.307.09c.425.12.89.11 1.305-.04l.178-.06l.238-.09l.267-.12q.252-.12.534-.12h.394l.099-2.554l-.007-.106h-.387a1.55 1.55 0 0 1-.712-.24l-.05-.03a2.2 2.2 0 0 0-.554-.28c-.425-.15-.88-.16-1.305-.04l-.129.03c-.237.07-.465.17-.672.32s-.456.22-.713.22h-1.226c-.258 0-.505-.08-.713-.22l-.01-.01a2.3 2.3 0 0 0-.642-.31l-.09-.03c-.425-.12-.88-.12-1.305.02l-.04.01c-.207.07-.405.17-.593.29l-.03.03c-.217.14-.465.22-.722.22h-.288l-.003.08l.01.306z");
}

.o0glw0bjm {
  d: path("M13.847 9.5a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.o1uobmugz {
  stop-color: var(--svg-color--c31251, #C31251);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.oj7ch-bkx {
  stop-color: var(--svg-color--528adb, #528ADB);
  stop-opacity: 0;
}

.ol-rryc7f {
  d: path("M18.215 9.5a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.onbz4ubrj {
  stop-color: var(--svg-color--ba3950, #BA3950);
  stop-opacity: 0;
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
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

.p0ux8fbne {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.031 13.485a3 3 0 0 1-1.421-.345c-.141-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.249 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.p47czub_x {
  stop-color: var(--svg-color--90685e, #90685E);
  stop-opacity: 0;
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pbxi84b9i {
  fill: var(--svg-color--2f63d5, #2F63D5);
  d: path("M12.875 23.42a.885.885 0 0 0-.763 1.333l2.143 3.638a1.49 1.49 0 0 0 2.568 0l2.142-3.638a.885.885 0 0 0-.762-1.334z");
}

.pij655hmh {
  stop-color: var(--svg-color--895956, #895956);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmf-vsdxp {
  stop-color: var(--svg-color--4d87f8, #4D87F8);
}

.pn3_klbyd {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.173 10.004c.266-.467.67-.835 1.538-.835c.38 0 .747.105 1.072.368c.27.218.233.495.025.6l-.556.317c-.652-.21-1.373-.24-2.079-.45");
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

.r3e74cczy {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.859 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.rn540obxc {
  stop-color: var(--svg-color--ee344d, #EE344D);
}

.s_7wpwboy {
  d: path("M11.346 12.182a1.609 1.609 0 1 0 0-3.218a1.609 1.609 0 0 0 0 3.218");
}

.s4p84bb8g {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.15 9.688c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.s9sui_61e {
  stop-color: var(--svg-color--3e75e1, #3E75E1);
}

.sii6nfq-p {
  stop-color: var(--svg-color--5c2f30, #5C2F30);
  stop-opacity: 0;
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.su-lx9b4e {
  stop-color: var(--svg-color--fff14e, #FFF14E);
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

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tyjpv6bnm {
  stop-color: var(--svg-color--790b2c, #790B2C);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.ujtti6ofv {
  stop-color: var(--svg-color--2154ca, #2154CA);
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

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uwyaafbnv {
  fill: var(--svg-color--80554c, #80554C);
  d: path("m15.675 10.517l-.494 1.582a.502.502 0 0 0 .484.65h.732c.343 0 .586-.33.485-.65l-.495-1.582c-.106-.351-.6-.351-.712 0");
}

.v2ucwt3jq {
  stop-color: var(--svg-color--49a3ff, #49A3FF);
  stop-opacity: 0;
}

.v88cgvkze {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16.031 13.485a3 3 0 0 1-1.421-.345c-.141-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.249 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vv0158bin {
  fill: var(--svg-color--000, #000);
  d: path("M14.358 10.392a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.904a.5.5 0 0 0 .061-.235");
}

.w13b5wbfy {
  d: path("M11.365 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.w6_8my7ls {
  stop-color: var(--svg-color--4b99ff, #4B99FF);
  stop-opacity: 0;
}

.wdqycsape {
  d: path("M16.056 15.353h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wn7157b9l {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
  stop-opacity: 0;
}

.wrf7i3ase {
  d: path("M20.859 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wszl1wbzf {
  stop-color: var(--svg-color--713c53, #713C53);
}

.wwtjf56yr {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M10.962 4.585c.566-.6 1.636-.6 2.131-.51l.396 1.29c-.253-.04-.478.05-.668.234c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.wx3vdcbzg {
  stop-color: var(--svg-color--407dbe, #407DBE);
  stop-opacity: 0;
}

.x_0jnxbib {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
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

.xs2ea2bhg {
  d: path("M14.663 10.287c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.xvvg0mbfp {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.428 2.783c-1.133-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.671-5.921-5.24z");
}

.xyu2htzlq {
  stop-color: var(--svg-color--790b2c, #790B2C);
  stop-opacity: 0;
}

.y9rlcreuk {
  stop-color: var(--svg-color--bf2370, #BF2370);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yh1zq-bfb {
  d: path("M18.15 9.688c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.z-t54tbit {
  d: path("M13.13 22.998a.95.95 0 0 0-.818 1.432l2.302 3.907a1.6 1.6 0 0 0 2.757 0l2.301-3.907a.95.95 0 0 0-.819-1.433z");
}

.z14dz9exi {
  stop-color: var(--svg-color--ff1781, #FF1781);
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zbo4__e4e {
  stop-color: var(--svg-color--3f83f1, #3F83F1);
}

.zi8t_0buy {
  stop-color: var(--svg-color--780438, #780438);
  stop-opacity: 0;
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zypb88bgi {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.89 10.004c-.266-.467-.67-.835-1.538-.835c-.38 0-.747.105-1.073.368c-.269.218-.233.495-.024.6l.555.317c.652-.21 1.373-.24 2.08-.45");
}

</style>
