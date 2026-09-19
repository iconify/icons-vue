<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iXQsIHd)"><path fill="url(#iDAtgPe)" clip-rule="evenodd" class="m13calb-j"/><path fill="url(#iRIOn2d)" clip-rule="evenodd" class="m13calb-j"/><path fill="url(#ikFzYPb)" clip-rule="evenodd" class="m13calb-j"/><path fill="url(#i9jSi3b)" clip-rule="evenodd" class="m13calb-j"/><path fill="url(#iX90I5c)" clip-rule="evenodd" class="m13calb-j"/><path fill="url(#i6tbedb)" clip-rule="evenodd" class="m13calb-j"/><path fill="url(#ik0yTze)" clip-rule="evenodd" class="m13calb-j"/><path fill="url(#iQBkF8c)" clip-rule="evenodd" class="m13calb-j"/><path fill="url(#iDmO0Cb)" clip-rule="evenodd" class="m13calb-j"/><path fill="url(#iRr15Tf)" clip-rule="evenodd" class="m13calb-j"/><path fill="url(#iFOUN7b)" clip-rule="evenodd" class="m13calb-j"/><path fill="url(#iLJnnZd)" clip-rule="evenodd" class="m13calb-j"/></g><path fill="url(#ifmdVTc)" class="o5qv1ubft"/><path fill="url(#iHgxand)" class="o5qv1ubft"/><g filter="url(#i85Z2qb)"><path class="tduk5jbcq"/></g><g filter="url(#i9hMMfA)"><path class="wapsqjbxj"/></g><path fill="url(#i5XPYcb)" class="b6q3m7b1n"/><path fill="url(#irMYBIe)" class="b6q3m7b1n"/><path fill="url(#ivsTJcr)" class="b6q3m7b1n"/><path fill="url(#i9tWfJx)" class="ac75mqb3o"/><path fill="url(#ioo0F0b)" class="ac75mqb3o"/><g filter="url(#ix1UXod)"><path fill="url(#ilm7dqe)" class="gx-j7caqy"/><path fill="url(#ipTiqsC)" class="gx-j7caqy"/><path fill="url(#iYxvI8c)" class="gx-j7caqy"/></g><path fill="url(#i5gnonb)" class="gx-j7caqy"/><path fill="url(#i7ZSFhc)" class="gx-j7caqy"/><g filter="url(#ilJJKOC)"><path fill="url(#izPKVnd)" class="r14vgzc_j"/></g><g filter="url(#iXhTdle)"><path class="savt2_i-n"/><path fill="url(#i0rYidk)" class="vrv6d45wr"/></g><path fill="url(#idh0d3X)" class="jtetpbbcn"/><path fill="url(#iTYI1Ob)" class="jtetpbbcn"/><path fill="url(#iFQEr8b)" class="lzxan_pvj"/><path fill="url(#ipi0Sje)" class="analzkbin"/><path fill="url(#iQ0Gyac)" class="analzkbin"/><path fill="url(#i8vdIub)" class="analzkbin"/><path fill="url(#iqEfOnb)" class="kc8w335sj"/><path fill="url(#i7ljxLe)" class="ucvn9-6ab"/><path fill="url(#iXRYi5W)" class="gi1p71b6v"/><g filter="url(#iH9IRtc)"><path fill="url(#iY0kIue)" class="wb7ra1b6m"/></g><g filter="url(#iwGPNde)"><path fill="url(#itP4IRb)" class="pq28lk7-r"/><path fill="url(#ijjaQic)" class="pq28lk7-r"/></g><g filter="url(#igzqdON)"><path class="z0b8k11fd"/><path fill="url(#irNrY3U)" class="buvd75bqm"/></g><g filter="url(#igD9ydh)"><path class="r8fq56t3j"/><path fill="url(#i1ZAWzb)" class="c8qoseb7t"/></g><g filter="url(#iGAnYNb)"><path fill="url(#iOVLSte)" class="g1vz2lbrj"/><path fill="url(#i5m7Yqb)" class="g1vz2lbrj"/><path fill="url(#ilIS1ne)" class="g1vz2lbrj"/><path fill="url(#iWsKjid)" class="g1vz2lbrj"/><path fill="url(#iSzevUd)" class="g1vz2lbrj"/><path fill="url(#imyQyEb)" class="g1vz2lbrj"/><path fill="url(#iAdNQdh)" class="g1vz2lbrj"/><path fill="url(#ikI7fze)" class="g1vz2lbrj"/></g><path fill="url(#iKO8tJc)" class="g1vz2lbrj"/><path fill="url(#iUkCdxb)" class="g1vz2lbrj"/><g filter="url(#iQsXBxd)"><path class="ovoxkybtp"/></g><g filter="url(#iYR1xre)"><path class="ii1gzse8n"/><path fill="url(#iYbUoOb)" class="qz6r1ibtw"/><path fill="url(#iZpV1Pd)" class="qz6r1ibtw"/><path fill="url(#icgbEjb)" class="qz6r1ibtw"/><path fill="url(#iVseYco)" class="qz6r1ibtw"/></g><path fill="url(#in7rOnc)" class="qz6r1ibtw"/><path fill="url(#iboFcbb)" class="qz6r1ibtw"/><path stroke="url(#i0HLhGd)" class="xbym_sbgf"/><g filter="url(#iXgTu0b)"><path class="pz-nsnbyl"/></g><g filter="url(#i1K2Hjd)"><path class="qsjor1bam"/></g><g filter="url(#iRVMXWb)"><path class="mzpq_-ntz"/></g><g filter="url(#iNeaoCb)"><path clip-rule="evenodd" class="bk0uv1bce"/></g><path class="a1jbbtbdk"/><path fill="url(#isv9ftb)" class="qss2qfbyz"/><path class="rz5wlsboo"/><g filter="url(#izc41mz)"><path class="tzjjsybke"/><path fill="url(#iMagsnd)" class="s4zidxbeh"/></g><g filter="url(#iELgTub)"><path fill="url(#iJPycfe)" class="gp2igdb3p"/></g><path class="r_56oqb6u"/><path fill="url(#itV1Pzd)" class="wj09i6i9t"/><path class="chxgqpbqx"/><g filter="url(#iaHKkvd)"><path fill="url(#iGZTOPv)" class="l41db6bpk"/></g><g filter="url(#iBnts8b)"><ellipse transform="rotate(-27.914 13.594 10.255)" class="y4wngnyly"/><ellipse fill="url(#iuLLaDE)" transform="rotate(-27.914 13.594 10.255)" class="f3aipsb2s"/></g><g filter="url(#igMdkAZ)"><path class="kqrn-ob0w"/></g><g filter="url(#iOXHeSc)"><path class="l8_jtcb_b"/></g><g filter="url(#iOic0QG)"><path class="gwx9twkdm"/><path fill="url(#i5SgABc)" class="imdsb8byy"/></g><g filter="url(#ieGvAge)"><path class="jkpa3w30s"/><path fill="url(#iU7Q9nb)" class="lpe8-_bpf"/><path fill="url(#irVUh0R)" class="lpe8-_bpf"/></g><g filter="url(#ixZTIRc)"><path stroke="url(#iSIza3q)" class="q9-3m7r6t"/></g><g filter="url(#iHsYL4d)"><path class="lwa_30b2d"/></g><defs><radialGradient id="iRIOn2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.746 13.449)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ikFzYPb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.93 13.717)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i9jSi3b" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.842 8.353)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iX90I5c" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.265 7.839)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i6tbedb" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 3.873 11.813)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ik0yTze" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.911 7.015)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iQBkF8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.556 10.096)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iDmO0Cb" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.644 8.17)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iRr15Tf" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.13 -3.601)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iFOUN7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.905 10.06)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iLJnnZd" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 2.647 7.312)scale(2.91973 2.69143)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="iHgxand" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4313 6.37009 0 22.995 25.064)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="m5bm-ccxd"/><stop offset="1" class="q8ootib3t"/></radialGradient><radialGradient id="i5XPYcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1215 -4.59696 0 16 22.636)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="wdy63qb5p"/><stop offset="1" class="gkzmut59n"/></radialGradient><radialGradient id="i9tWfJx" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3135 1.68433 0 25 29.57)" gradientUnits="userSpaceOnUse"><stop class="omh3jbc5e"/><stop offset="1" class="g1k32m_rh"/></radialGradient><radialGradient id="iYxvI8c" cx="0" cy="0" r="1" gradientTransform="rotate(126.18 2.811 11.453)scale(2.59394 3.59462)" gradientUnits="userSpaceOnUse"><stop class="yfhz1ybyq"/><stop offset="1" class="kyt4h2bsk"/></radialGradient><radialGradient id="i7ZSFhc" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 -.3125 .15358 .53752 11.395 19.328)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="som6k-b6q"/><stop offset="1" class="pc2b66ykc"/></radialGradient><radialGradient id="idh0d3X" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -4.3769 0 16 18.085)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="ft6yvtbqk"/><stop offset="1" class="i_25dj3ib"/></radialGradient><radialGradient id="iTYI1Ob" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 6.81546 0 16 20.582)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="kx98i3bkm"/><stop offset=".876" class="mf716dhmi"/></radialGradient><radialGradient id="ipi0Sje" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -3.45478 0 15.983 20.976)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lv0iykbih"/><stop offset=".94" class="s3tb_6b2n"/></radialGradient><radialGradient id="iqEfOnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.48828 -3.72875 0 16.03 16.831)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="spf0krb0n"/><stop offset="1" class="u-xq04bhh"/></radialGradient><radialGradient id="itP4IRb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.087 11.387)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="ijjaQic" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.117 9.266)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="irNrY3U" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.439 11.06)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="i1ZAWzb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.446 10.947)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iOVLSte" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.906 10.41)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="i5m7Yqb" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 7.665 7.647)scale(2.25599 1.57104)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="ilIS1ne" cx="0" cy="0" r="1" gradientTransform="matrix(1.0735 -3.47607 4.41049 1.36207 13.867 17.192)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iWsKjid" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 3.597 12.656)scale(6.84714 6.88381)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iSzevUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.56691 -6.60207 0 15.785 10.8)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="imyQyEb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.339 6.938)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iAdNQdh" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.348 9.991)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="ikI7fze" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.97 9.763)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iKO8tJc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.142 11.479)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iUkCdxb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.829 1.57435 -1.05517 -1.22584 19.968 15.526)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iYbUoOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.831 12.205)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iVseYco" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.592 12.417)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iboFcbb" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.378 8.459)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="isv9ftb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.23 10.35)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iMagsnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18 10.434)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="itV1Pzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.865 10.35)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iuLLaDE" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.992 -1.4)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5SgABc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26205 -2.75541 1.4096 .64564 10.388 8.23)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iU7Q9nb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.029 7.157)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="irVUh0R" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.258 3.392)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iXQsIHd" width="15.268" height="15.768" x="8.538" y="1.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/></filter><filter id="i85Z2qb" width="6.556" height="14.595" x="9.212" y="15.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".5"/></filter><filter id="i9hMMfA" width="3.95" height="13.362" x="17.96" y="15.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".375"/></filter><filter id="ix1UXod" width="2.897" height="14" x="10.503" y="15.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/></filter><filter id="ilJJKOC" width="2.734" height="2.883" x="14.624" y="17.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2094" result="effect2_innerShadow_4002_2094"/></filter><filter id="iXhTdle" width="2.902" height="14.05" x="18.61" y="15.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/></filter><filter id="iH9IRtc" width="3.368" height="3.218" x="9.752" y="9.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/></filter><filter id="iwGPNde" width="3.218" height="3.468" x="19.265" y="9.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/></filter><filter id="igzqdON" width="3.148" height="3.148" x="19.3" y="9.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".25"/></filter><filter id="igD9ydh" width="2.648" height="2.648" x="10.056" y="9.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".125"/></filter><filter id="iGAnYNb" width="10.191" height="11.127" x="10.951" y="6.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/></filter><filter id="iQsXBxd" width="2.877" height="3.682" x="14.446" y="9.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".25"/></filter><filter id="iYR1xre" width="2.377" height="3.182" x="14.858" y="10.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".125"/></filter><filter id="iXgTu0b" width="3.001" height="1.285" x="16.989" y="9.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/></filter><filter id="i1K2Hjd" width="3.001" height="1.285" x="12.104" y="9.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/></filter><filter id="iRVMXWb" width="2.453" height="1.091" x="12.239" y="8.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/></filter><filter id="iNeaoCb" width="2.453" height="1.091" x="17.656" y="8.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/></filter><filter id="izc41mz" width=".787" height=".696" x="17.495" y="9.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".05"/></filter><filter id="iELgTub" width=".891" height=".913" x="18.335" y="9.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".1"/></filter><filter id="iaHKkvd" width=".986" height="1.04" x="13.892" y="9.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".1"/></filter><filter id="iBnts8b" width=".913" height=".705" x="13.137" y="9.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".05"/></filter><filter id="igMdkAZ" width="2.861" height="1.578" x="17.386" y="7.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".2"/></filter><filter id="iOXHeSc" width="2.861" height="1.578" x="11.935" y="7.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".2"/></filter><filter id="iOic0QG" width="4.412" height="4.713" x="9.593" y="3.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/><feGaussianBlur result="effect2_foregroundBlur_4002_2094" stdDeviation=".25"/></filter><filter id="ieGvAge" width="8.767" height="5.782" x="12.877" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2094"/><feGaussianBlur result="effect2_foregroundBlur_4002_2094" stdDeviation=".125"/></filter><filter id="ixZTIRc" width="1.145" height="2.31" x="12.856" y="4.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".1"/></filter><filter id="iHsYL4d" width="6.427" height="3.372" x="15.465" y="4.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2094" stdDeviation=".375"/></filter><linearGradient id="iDAtgPe" x1="20.74" x2="13.935" y1="3.995" y2="16.599" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="ifmdVTc" x1="16" x2="16" y1="15.882" y2="30.82" gradientUnits="userSpaceOnUse"><stop class="hac9w68gp"/><stop offset="1" class="u61ykmvtc"/></linearGradient><linearGradient id="irMYBIe" x1="18.903" x2="17.059" y1="24.882" y2="24.882" gradientUnits="userSpaceOnUse"><stop class="ugh29hhiz"/><stop offset="1" class="knib4pb5u"/></linearGradient><linearGradient id="ivsTJcr" x1="15.591" x2="15.669" y1="17.429" y2="21.32" gradientUnits="userSpaceOnUse"><stop class="ft2atdbel"/><stop offset="1" class="r8964-bmu"/></linearGradient><linearGradient id="ioo0F0b" x1="23" x2="23.744" y1="29.058" y2="29.034" gradientUnits="userSpaceOnUse"><stop offset=".276" class="alwwvg18b"/><stop offset="1" class="r8-nbsf4i"/></linearGradient><linearGradient id="ilm7dqe" x1="11.902" x2="11.902" y1="15.661" y2="29.561" gradientUnits="userSpaceOnUse"><stop class="j-er45bzw"/><stop offset=".524" class="iwz00abqx"/></linearGradient><linearGradient id="ipTiqsC" x1="13.671" x2="13.05" y1="22.12" y2="22.12" gradientUnits="userSpaceOnUse"><stop class="recxkftoe"/><stop offset="1" class="btkjyionj"/></linearGradient><linearGradient id="i5gnonb" x1="11.902" x2="12.839" y1="25.537" y2="25.135" gradientUnits="userSpaceOnUse"><stop offset=".196" class="yqlqjsfuk"/><stop offset="1" class="c8t-c_brq"/></linearGradient><linearGradient id="izPKVnd" x1="15.988" x2="15.988" y1="18.554" y2="20.539" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mu96iuqwe"/><stop offset="1" class="p-sb3ibac"/></linearGradient><linearGradient id="i0rYidk" x1="18.71" x2="20.111" y1="21.168" y2="21.168" gradientUnits="userSpaceOnUse"><stop offset=".093" class="fxp5v2b6t"/><stop offset="1" class="zm9c_pbne"/></linearGradient><linearGradient id="iFQEr8b" x1="9.452" x2="7.02" y1="23.578" y2="23.578" gradientUnits="userSpaceOnUse"><stop class="rpmno-b9y"/><stop offset="1" class="a9ts2kezv"/></linearGradient><linearGradient id="iQ0Gyac" x1="14.606" x2="14.899" y1="24.441" y2="24.48" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="i8vdIub" x1="17.411" x2="17.012" y1="24.257" y2="24.304" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="i7ljxLe" x1="8.862" x2="23.238" y1="15.9" y2="15.9" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iXRYi5W" x1="8.862" x2="23.238" y1="15.869" y2="15.869" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iY0kIue" x1="9.752" x2="12.711" y1="11.035" y2="11.035" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iZpV1Pd" x1="15.108" x2="16.047" y1="12.279" y2="12.279" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="icgbEjb" x1="16.047" x2="16.047" y1="13.078" y2="12.467" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="in7rOnc" x1="16.125" x2="16.125" y1="13.051" y2="12.912" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="i0HLhGd" x1="14.983" x2="15.444" y1="14.487" y2="13.775" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iJPycfe" x1="19.007" x2="18.693" y1="10.404" y2="10.598" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGZTOPv" x1="14.609" x2="14.295" y1="10.404" y2="10.598" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSIza3q" x1="13.156" x2="13.7" y1="4.749" y2="6.023" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-office-worker-dark" /></template>
<style>
.a1jbbtbdk {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.438 9.602c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.127 1.37-1.127");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a9ts2kezv {
  stop-color: var(--svg-color--584a7e, #584A7E);
  stop-opacity: 0;
}

.ac75mqb3o {
  d: path("M23 17.588v11.983h4v-3.5a10.98 10.98 0 0 0-4-8.483");
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.alwwvg18b {
  stop-color: var(--svg-color--504176, #504176);
}

.analzkbin {
  d: path("M15.505 20.68a.25.25 0 0 0-.247.213L13.93 29.56h4.11l-1.318-8.668a.25.25 0 0 0-.247-.212z");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b6q3m7b1n {
  d: path("M18.71 15.69h-5.42v13.89h5.42z");
}

.bk0uv1bce {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.779 8.712l-.138.23za.268.268 0 0 1-.276.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .559.238l.009.005l.003.002z");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.btkjyionj {
  stop-color: var(--svg-color--553a63, #553A63);
  stop-opacity: 0;
}

.buvd75bqm {
  d: path("M20.874 12.022a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.c8qoseb7t {
  d: path("M11.38 12.022a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.c8t-c_brq {
  stop-color: var(--svg-color--594c7d, #594C7D);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.chxgqpbqx {
  fill: var(--svg-color--000, #000);
  d: path("M14.374 10.766a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .06-.235");
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.f3aipsb2s {
  cx: 13.594px;
  cy: 10.255px;
  rx: 0.39px;
  ry: 0.197px;
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
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

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1k32m_rh {
  stop-color: var(--svg-color--6d6193, #6D6193);
}

.g1vz2lbrj {
  d: path("M10.96 9.685h.012l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.118 3.073c-.124 2.803-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gi1p71b6v {
  d: path("M16.072 15.87h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.gkzmut59n {
  stop-color: var(--svg-color--a89cb3, #A89CB3);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gp2igdb3p {
  d: path("M19.026 10.648a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.gwx9twkdm {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M10.978 4.96c.566-.6 1.636-.6 2.13-.512l.396 1.291c-.252-.039-.478.05-.667.235c-.449 1.26-1.99 1.955-2.704 2.145c-.149-1.492.109-2.38.845-3.16");
}

.gx-j7caqy {
  d: path("M13.29 15.66h-.85c-.18.06-.36.13-.53.2l-1.27 2.69c-.09.19.06.41.27.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01v-13.9z");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hac9w68gp {
  stop-color: var(--svg-color--534973, #534973);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i_25dj3ib {
  stop-color: var(--svg-color--a093a3, #A093A3);
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.ii1gzse8n {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.665 10.586l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.imdsb8byy {
  d: path("M10.978 4.96c.566-.6 1.636-.6 2.13-.512l.396 1.291c-.252-.039-.478.05-.667.235c-.449 1.26-1.99 1.955-2.704 2.145c-.149-1.492.109-2.38.845-3.16");
}

.iwz00abqx {
  stop-color: var(--svg-color--5f5289, #5F5289);
}

.j-er45bzw {
  stop-color: var(--svg-color--544a76, #544A76);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jkpa3w30s {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.444 3.157c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.jtetpbbcn {
  d: path("M16 14.627h-2.71v4.74c0 .31.36.49.61.29l2.1-1.392l2.1 1.392c.25.2.61.02.61-.29v-4.74z");
}

.jybxgogov {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kc8w335sj {
  d: path("M14.045 16.46c.02.214.205.691.746 1.055c.214.144 1.213.629 1.193.619c.156-.078.807-.299 1.284-.619c.54-.364.725-.841.746-1.055l-1.985-.953z");
}

.knib4pb5u {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
  stop-opacity: 0;
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.kqrn-ob0w {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.987 8.575c.322-.079 1.124-.04 1.66.344");
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

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l41db6bpk {
  d: path("M14.678 10.66c0-.288-.234-.48-.298-.538l-.288.279l.177.361z");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l8_jtcb_b {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.196 8.575c-.323-.079-1.125-.04-1.661.344");
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

.lpe8-_bpf {
  d: path("M15.444 3.157c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.lv0iykbih {
  stop-color: var(--svg-color--56406d, #56406D);
}

.lwa_30b2d {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.453 6.767l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.lzxan_pvj {
  d: path("M7.032 29.57H8.97V17.607a11 11 0 0 0-3.656 5.843a11 11 0 0 0-.304 2.632l.02 3.49z");
}

.m13calb-j {
  fill-rule: evenodd;
  d: path("M23.232 12.357c.213-.435.324-.92.324-1.427c0-.467-.096-.905-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.215 3.3v.01a3.24 3.24 0 0 1-.527 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.121-.981-.324-1.406a.51.51 0 0 1 0-.456m-12.26-2.672h-.012l1.198 2.355c.124 2.803 1.218 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.955-1.332-1.135-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.195a2.3 2.3 0 0 1-1.292 1.275c-.236.122-.79.49-.81 1.439l.01.306z");
}

.m5bm-ccxd {
  stop-color: var(--svg-color--7b74a6, #7B74A6);
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mf716dhmi {
  stop-color: var(--svg-color--544a5f, #544A5F);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mu96iuqwe {
  stop-color: var(--svg-color--4b375e, #4B375E);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mzpq_-ntz {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.65 9.17l-.005.002a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.182z");
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o5qv1ubft {
  d: path("M16 15.07c-6.08 0-11 4.92-11 11v3.5h22v-3.5c0-6.07-4.93-11-11-11");
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omh3jbc5e {
  stop-color: var(--svg-color--776d9f, #776D9F);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ovoxkybtp {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.654 10.725l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.p-sb3ibac {
  stop-color: var(--svg-color--483b55, #483B55);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pc2b66ykc {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
  stop-opacity: 0;
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pq28lk7-r {
  d: path("M20.874 12.557a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.pz-nsnbyl {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.19 10.379c.264-.467.668-.836 1.536-.836c.38 0 .747.105 1.073.369c.27.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.q8ootib3t {
  stop-color: var(--svg-color--5f5490, #5F5490);
  stop-opacity: 0;
}

.q9-3m7r6t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.156 4.406c.023.243.234 1.156.544 1.71");
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qsjor1bam {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.905 10.379c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.qss2qfbyz {
  d: path("M18.231 9.873a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qz6r1ibtw {
  d: path("m15.665 10.586l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.r_56oqb6u {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.656 9.602c-.653 0-1.205.45-1.355 1.058a.275.275 0 0 0 .268.341H14.8a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r14vgzc_j {
  d: path("m16.01 17.898l-1.24 1.204a.15.15 0 0 0-.033.168l.547 1.26c.04.092.13.15.23.15h.952c.1 0 .19-.059.23-.15l.55-1.28a.15.15 0 0 0-.033-.167z");
}

.r8-nbsf4i {
  stop-color: var(--svg-color--504176, #504176);
  stop-opacity: 0;
}

.r8964-bmu {
  stop-color: var(--svg-color--877f93, #877F93);
  stop-opacity: 0;
}

.r8fq56t3j {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.38 12.022a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.recxkftoe {
  stop-color: var(--svg-color--3e305b, #3E305B);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rop63gbyj {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
  stop-opacity: 0;
}

.rpmno-b9y {
  stop-color: var(--svg-color--41375c, #41375C);
}

.rz5wlsboo {
  fill: var(--svg-color--000, #000);
  d: path("M17.72 10.766a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.s3tb_6b2n {
  stop-color: var(--svg-color--3d3247, #3D3247);
}

.s4zidxbeh {
  d: path("M18.165 10.062c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.savt2_i-n {
  fill: var(--svg-color--605890, #605890);
  d: path("m21.22 20.69l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.som6k-b6q {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
}

.spf0krb0n {
  stop-color: var(--svg-color--331b22, #331B22);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.tduk5jbcq {
  fill: var(--svg-color--41355c, #41355C);
  d: path("M13.419 16.42c-.513 0-1.296-.03-1.77.166l-1.38 2.724c-.09.19.06.41.27.41h1.55c.24 0 .35.29.19.45l-1.78 1.342c-.26.26-.36.65-.23 1l2.912 6.5l1.587-1.115l-1.34-11.477z");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tzjjsybke {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.165 10.062c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.u-xq04bhh {
  stop-color: var(--svg-color--352121, #352121);
}

.u61ykmvtc {
  stop-color: var(--svg-color--584982, #584982);
}

.ucvn9-6ab {
  d: path("M16.402 15.87c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.ugh29hhiz {
  stop-color: var(--svg-color--7a6c85, #7A6C85);
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vrv6d45wr {
  d: path("m21.22 20.69l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wapsqjbxj {
  fill: var(--svg-color--463d68, #463D68);
  d: path("m20.905 20.752l-1.19-.828a.23.23 0 0 1 .166-.393h.919a.252.252 0 0 0 .227-.359l-1.076-2.29a8 8 0 0 0-.646-.237h-.595v11.862l2.404-6.872a.85.85 0 0 0-.21-.883");
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wb7ra1b6m {
  d: path("M11.361 12.557a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.wdy63qb5p {
  stop-color: var(--svg-color--c6bbd1, #C6BBD1);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wj09i6i9t {
  d: path("M13.863 9.873a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xbym_sbgf {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.649 13.47a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.247-.041c-.404.215-.88.339-1.398.339a3 3 0 0 1-1.398-.339Z");
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

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y4wngnyly {
  cx: 13.594px;
  cy: 10.255px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yfhz1ybyq {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
}

.yqlqjsfuk {
  stop-color: var(--svg-color--55477c, #55477C);
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z0b8k11fd {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.874 12.022a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zm9c_pbne {
  stop-color: var(--svg-color--625a91, #625A91);
  stop-opacity: 0;
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
