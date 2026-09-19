<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#irwwttb)"><path fill="url(#iEWRaud)" clip-rule="evenodd" class="wn_idr65v"/><path fill="url(#iGpSgjc)" clip-rule="evenodd" class="wn_idr65v"/><path fill="url(#ilPgDdd)" clip-rule="evenodd" class="wn_idr65v"/><path fill="url(#ia5kUeb)" clip-rule="evenodd" class="wn_idr65v"/><path fill="url(#i5EBjAm)" clip-rule="evenodd" class="wn_idr65v"/><path fill="url(#iNbRYfe)" clip-rule="evenodd" class="wn_idr65v"/><path fill="url(#iINCewe)" clip-rule="evenodd" class="wn_idr65v"/><path fill="url(#iXLzQYb)" clip-rule="evenodd" class="wn_idr65v"/><path fill="url(#iga48oe)" clip-rule="evenodd" class="wn_idr65v"/><path fill="url(#iPOOand)" clip-rule="evenodd" class="wn_idr65v"/><path fill="url(#iIgxlKc)" clip-rule="evenodd" class="wn_idr65v"/></g><path fill="url(#i4cX3ub)" class="zvvx29b3a"/><path fill="url(#it9pf1s)" class="zvvx29b3a"/><g filter="url(#iF6n9oe)"><path class="mqs7o2bnn"/></g><g filter="url(#iF5wOZd)"><path class="kmq3_bbmh"/></g><path fill="url(#ivPn6qc)" class="cho8x9bqp"/><path fill="url(#iJ17IGb)" class="cho8x9bqp"/><path fill="url(#iup2Oab)" class="cho8x9bqp"/><path fill="url(#iDnE1ae)" class="pagefvi7k"/><path fill="url(#iLp5qte)" class="pagefvi7k"/><g filter="url(#iFdHnxH)"><path fill="url(#i90cFFb)" class="ym90ysber"/><path fill="url(#iWv4KGe)" class="ym90ysber"/><path fill="url(#i4omEXd)" class="ym90ysber"/></g><path fill="url(#iBhXxcI)" class="ym90ysber"/><path fill="url(#iIwLmve)" class="ym90ysber"/><g filter="url(#ir3FzqM)"><path fill="url(#iy6VchF)" class="l06e93bca"/></g><g filter="url(#i5AhxGc)"><path class="oou4fxxcq"/><path fill="url(#iJiQQFc)" class="j-1m-y7it"/></g><path fill="url(#iCCkCPe)" class="msod-5bzd"/><path fill="url(#iipiZdd)" class="msod-5bzd"/><path fill="url(#iLexqUb)" class="vhf08lbkn"/><path fill="url(#iTY9itb)" class="j-3h25m7h"/><path fill="url(#i9s8iwe)" class="j-3h25m7h"/><path fill="url(#irnvbJb)" class="j-3h25m7h"/><path fill="url(#iWDaaab)" class="d8npuof1g"/><path fill="url(#iVDZQ0c)" class="sgl1asp0z"/><path fill="url(#iG6p9Eb)" class="cyqispo_i"/><g filter="url(#if2pCcb)"><path fill="url(#i3PHA8I)" class="z72oadczb"/></g><g filter="url(#iw2NYce)"><path fill="url(#imLD0ed)" class="ccr6o7bqr"/><path fill="url(#ixIuT8X)" class="ccr6o7bqr"/></g><g filter="url(#ioyZHrc)"><path class="g4wi6gddi"/><path fill="url(#iMGEelu)" class="ifsrrmuqt"/></g><g filter="url(#iISKOFb)"><path class="t1jnqlbxn"/><path fill="url(#iOMfPDb)" class="zgkix-53c"/></g><g filter="url(#iCpk3cl)"><path fill="url(#iszLAyb)" class="zl3z80qcv"/><path fill="url(#iZfXskc)" class="zl3z80qcv"/><path fill="url(#iYcYEgD)" class="zl3z80qcv"/><path fill="url(#ijE9mre)" class="zl3z80qcv"/><path fill="url(#i01tOPb)" class="zl3z80qcv"/><path fill="url(#i878hle)" class="zl3z80qcv"/><path fill="url(#ikLmfkW)" class="zl3z80qcv"/></g><path fill="url(#ilQxECH)" class="zl3z80qcv"/><path fill="url(#iuo9ixe)" class="zl3z80qcv"/><g filter="url(#iTRVHwd)"><path class="idggc37ct"/></g><g filter="url(#ioWDDpt)"><path class="csqw4-28q"/><path fill="url(#i2j5hqe)" class="nj166n02i"/><path fill="url(#iGziFmb)" class="nj166n02i"/><path fill="url(#idu7dGR)" class="nj166n02i"/><path fill="url(#iNPhIFc)" class="nj166n02i"/></g><path fill="url(#i4xXJEc)" class="nj166n02i"/><path fill="url(#iVAVxqb)" class="nj166n02i"/><path stroke="url(#iPsye0d)" class="hwqc8s6cj"/><g filter="url(#iM0FJMd)"><path class="q35o5nbax"/></g><g filter="url(#iJddhvc)"><path class="sebnpqbxu"/></g><g filter="url(#ictFlyc)"><path class="d_iqknbvq"/></g><g filter="url(#ieGjb8b)"><path clip-rule="evenodd" class="dk_rexb0w"/></g><path class="pj6fmxxss"/><path fill="url(#iSBw1nc)" class="erw_h94je"/><path class="anv355o3r"/><g filter="url(#itqQOwb)"><path class="ebfi_gblr"/><path fill="url(#ixN1GFb)" class="gu8xo7toj"/></g><g filter="url(#iS2daWd)"><path fill="url(#i9a8nuc)" class="lovk48bju"/></g><path class="e1n1g8gyb"/><path fill="url(#iPCShte)" class="ir0l7gb9v"/><path class="noozichez"/><g filter="url(#iJtl6Zb)"><path fill="url(#iPood6Q)" class="y72bh29go"/></g><g filter="url(#i6Nw3hb)"><ellipse transform="rotate(-27.914 13.537 10.227)" class="jk63qxbcl"/><ellipse fill="url(#i6409Jb)" transform="rotate(-27.914 13.537 10.227)" class="icxc77_wy"/></g><g filter="url(#ijhnNVb)"><path class="buebd8i1n"/></g><g filter="url(#iujMBAe)"><path class="twdgiactz"/></g><g filter="url(#i4twtrc)"><path class="stwaw694b"/><path fill="url(#imPvWXX)" class="bl8vocbbf"/></g><g filter="url(#ibtTHGA)"><path class="mk0gy856t"/><path fill="url(#iGrlWob)" class="lq7rmabig"/><path fill="url(#iWIK2wO)" class="lq7rmabig"/></g><g filter="url(#idDaJac)"><path stroke="url(#ik2ayld)" class="bwj03-b0r"/></g><g filter="url(#ij04xze)"><path class="u8nlhyb2v"/></g><defs><radialGradient id="iGpSgjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 15.69 13.42)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ilPgDdd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.873 13.689)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ia5kUeb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.82 8.325)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i5EBjAm" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.244 7.81)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iNbRYfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 12.471 2.861)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iINCewe" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.889 6.99)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iXLzQYb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 23.5 10.069)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iga48oe" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.618 8.153)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iPOOand" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.092 -3.595)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iIgxlKc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.849 10.032)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="it9pf1s" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4313 6.37009 0 22.995 25.091)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="m5bm-ccxd"/><stop offset="1" class="q8ootib3t"/></radialGradient><radialGradient id="ivPn6qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1215 -4.59696 0 16 22.663)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="wdy63qb5p"/><stop offset="1" class="gkzmut59n"/></radialGradient><radialGradient id="iDnE1ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3135 1.68433 0 25 29.598)" gradientUnits="userSpaceOnUse"><stop class="omh3jbc5e"/><stop offset="1" class="g1k32m_rh"/></radialGradient><radialGradient id="i4omEXd" cx="0" cy="0" r="1" gradientTransform="rotate(126.18 2.804 11.467)scale(2.59394 3.59462)" gradientUnits="userSpaceOnUse"><stop class="yfhz1ybyq"/><stop offset="1" class="kyt4h2bsk"/></radialGradient><radialGradient id="iIwLmve" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 -.3125 .15358 .53752 11.395 19.355)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="som6k-b6q"/><stop offset="1" class="pc2b66ykc"/></radialGradient><radialGradient id="iCCkCPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -4.3769 0 16 18.113)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="ft6yvtbqk"/><stop offset="1" class="i_25dj3ib"/></radialGradient><radialGradient id="iipiZdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 6.81546 0 16 20.61)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="kx98i3bkm"/><stop offset=".876" class="mf716dhmi"/></radialGradient><radialGradient id="iTY9itb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -3.45478 0 15.983 21.003)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lv0iykbih"/><stop offset=".94" class="s3tb_6b2n"/></radialGradient><radialGradient id="iWDaaab" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3026 -2.71576 0 16.03 16.859)" gradientUnits="userSpaceOnUse"><stop class="omyqhdc3g"/><stop offset="1" class="s-2x0fj8v"/></radialGradient><radialGradient id="imLD0ed" cx="0" cy="0" r="1" gradientTransform="matrix(1.82698 -2.0365 2.48647 2.23066 20.5 11.896)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="ixIuT8X" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 21.061 9.239)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iMGEelu" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.382 11.032)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iOMfPDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.39 10.92)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iszLAyb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -4.01413 -8.70492 18.85 10.383)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iZfXskc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 19.243 11.745)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iYcYEgD" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.61 17.712)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="ijE9mre" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -7.78405 0 15.99 10.165)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="z_fy1nb8g"/><stop offset="1" class="zs13mzbvi"/></radialGradient><radialGradient id="i01tOPb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.312 6.922)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="i878hle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.292 9.964)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="ikLmfkW" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.914 9.735)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ilQxECH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.086 11.452)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iuo9ixe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 13.806 4.384)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="i2j5hqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.776 12.18)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iNPhIFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.536 12.39)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iVAVxqb" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.354 8.436)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="iSBw1nc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.173 10.323)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ixN1GFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.945 10.407)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPCShte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.809 10.323)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i6409Jb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.95 -1.385)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imPvWXX" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.556 -3.948)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iGrlWob" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.01 7.125)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iWIK2wO" cx="0" cy="0" r="1" gradientTransform="matrix(-.21034 1.3672 -2.94144 -.45253 16.201 3.365)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="irwwttb" width="15.268" height="15.768" x="8.482" y="1.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/></filter><filter id="iF6n9oe" width="6.556" height="14.595" x="9.212" y="15.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".5"/></filter><filter id="iF5wOZd" width="3.95" height="13.362" x="17.96" y="15.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".375"/></filter><filter id="iFdHnxH" width="2.897" height="14" x="10.503" y="15.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/></filter><filter id="ir3FzqM" width="2.734" height="2.883" x="14.624" y="17.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2106" result="effect2_innerShadow_4002_2106"/></filter><filter id="i5AhxGc" width="2.902" height="14.05" x="18.61" y="15.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/></filter><filter id="if2pCcb" width="3.368" height="3.218" x="9.696" y="9.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/></filter><filter id="iw2NYce" width="3.218" height="3.468" x="19.209" y="9.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/></filter><filter id="ioyZHrc" width="3.148" height="3.148" x="19.244" y="9.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".25"/></filter><filter id="iISKOFb" width="2.948" height="2.948" x="9.85" y="9.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".2"/></filter><filter id="iCpk3cl" width="10.191" height="11.277" x="10.896" y="6.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/></filter><filter id="iTRVHwd" width="2.877" height="3.682" x="14.39" y="9.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".25"/></filter><filter id="ioWDDpt" width="2.377" height="3.182" x="14.802" y="10.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".125"/></filter><filter id="iM0FJMd" width="3.001" height="1.285" x="16.933" y="9.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/></filter><filter id="iJddhvc" width="3.001" height="1.285" x="12.048" y="9.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/></filter><filter id="ictFlyc" width="2.453" height="1.091" x="12.183" y="8.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/></filter><filter id="ieGjb8b" width="2.453" height="1.091" x="17.6" y="8.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/></filter><filter id="itqQOwb" width=".787" height=".696" x="17.439" y="9.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".05"/></filter><filter id="iS2daWd" width=".891" height=".913" x="18.279" y="9.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".1"/></filter><filter id="iJtl6Zb" width=".986" height="1.04" x="13.836" y="9.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".1"/></filter><filter id="i6Nw3hb" width=".913" height=".705" x="13.081" y="9.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".05"/></filter><filter id="ijhnNVb" width="2.261" height=".978" x="17.63" y="8.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".1"/></filter><filter id="iujMBAe" width="2.261" height=".978" x="12.179" y="8.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".1"/></filter><filter id="i4twtrc" width="4.212" height="4.513" x="9.736" y="4.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/><feGaussianBlur result="effect2_foregroundBlur_4002_2106" stdDeviation=".15"/></filter><filter id="ibtTHGA" width="8.767" height="5.782" x="12.821" y="2.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2106"/><feGaussianBlur result="effect2_foregroundBlur_4002_2106" stdDeviation=".125"/></filter><filter id="idDaJac" width="1.145" height="2.31" x="12.8" y="4.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".1"/></filter><filter id="ij04xze" width="6.427" height="3.372" x="15.409" y="4.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2106" stdDeviation=".375"/></filter><linearGradient id="iEWRaud" x1="20.684" x2="13.879" y1="3.967" y2="16.572" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="i4cX3ub" x1="16" x2="16" y1="15.91" y2="30.847" gradientUnits="userSpaceOnUse"><stop class="hac9w68gp"/><stop offset="1" class="u61ykmvtc"/></linearGradient><linearGradient id="iJ17IGb" x1="18.903" x2="17.059" y1="24.91" y2="24.91" gradientUnits="userSpaceOnUse"><stop class="ugh29hhiz"/><stop offset="1" class="knib4pb5u"/></linearGradient><linearGradient id="iup2Oab" x1="15.591" x2="15.669" y1="17.457" y2="21.347" gradientUnits="userSpaceOnUse"><stop class="ft2atdbel"/><stop offset="1" class="r8964-bmu"/></linearGradient><linearGradient id="iLp5qte" x1="23" x2="23.744" y1="29.085" y2="29.062" gradientUnits="userSpaceOnUse"><stop offset=".276" class="alwwvg18b"/><stop offset="1" class="r8-nbsf4i"/></linearGradient><linearGradient id="i90cFFb" x1="11.902" x2="11.902" y1="15.688" y2="29.588" gradientUnits="userSpaceOnUse"><stop class="j-er45bzw"/><stop offset=".524" class="iwz00abqx"/></linearGradient><linearGradient id="iWv4KGe" x1="13.671" x2="13.05" y1="22.148" y2="22.148" gradientUnits="userSpaceOnUse"><stop class="recxkftoe"/><stop offset="1" class="btkjyionj"/></linearGradient><linearGradient id="iBhXxcI" x1="11.902" x2="12.839" y1="25.564" y2="25.163" gradientUnits="userSpaceOnUse"><stop offset=".196" class="yqlqjsfuk"/><stop offset="1" class="c8t-c_brq"/></linearGradient><linearGradient id="iy6VchF" x1="15.988" x2="15.988" y1="18.582" y2="20.566" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mu96iuqwe"/><stop offset="1" class="p-sb3ibac"/></linearGradient><linearGradient id="iJiQQFc" x1="18.71" x2="20.111" y1="21.195" y2="21.195" gradientUnits="userSpaceOnUse"><stop offset=".093" class="fxp5v2b6t"/><stop offset="1" class="zm9c_pbne"/></linearGradient><linearGradient id="iLexqUb" x1="9.452" x2="7.02" y1="23.606" y2="23.606" gradientUnits="userSpaceOnUse"><stop class="rpmno-b9y"/><stop offset="1" class="a9ts2kezv"/></linearGradient><linearGradient id="i9s8iwe" x1="14.606" x2="14.899" y1="24.468" y2="24.507" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="irnvbJb" x1="17.411" x2="17.012" y1="24.285" y2="24.332" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="iVDZQ0c" x1="8.862" x2="23.238" y1="15.927" y2="15.927" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iG6p9Eb" x1="8.862" x2="23.238" y1="15.897" y2="15.897" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i3PHA8I" x1="9.696" x2="12.655" y1="11.007" y2="11.007" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iGziFmb" x1="15.052" x2="15.991" y1="12.251" y2="12.251" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="idu7dGR" x1="15.991" x2="15.991" y1="13.05" y2="12.44" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="i4xXJEc" x1="16.069" x2="16.069" y1="13.024" y2="12.884" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="iPsye0d" x1="14.927" x2="15.387" y1="14.46" y2="13.748" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="i9a8nuc" x1="18.951" x2="18.637" y1="10.377" y2="10.57" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPood6Q" x1="14.553" x2="14.239" y1="10.377" y2="10.57" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ik2ayld" x1="13.1" x2="13.644" y1="4.722" y2="5.996" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-office-worker-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a9ts2kezv {
  stop-color: var(--svg-color--584a7e, #584A7E);
  stop-opacity: 0;
}

.alwwvg18b {
  stop-color: var(--svg-color--504176, #504176);
}

.anv355o3r {
  fill: var(--svg-color--000, #000);
  d: path("M17.664 10.738c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bl8vocbbf {
  d: path("M10.922 4.932c.566-.6 1.636-.6 2.13-.511l.396 1.29c-.253-.039-.478.05-.667.235c-.449 1.26-1.99 1.956-2.704 2.146c-.149-1.492.109-2.38.845-3.16");
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.btkjyionj {
  stop-color: var(--svg-color--553a63, #553A63);
  stop-opacity: 0;
}

.buebd8i1n {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.93 8.547c.323-.078 1.125-.039 1.661.345");
}

.bwj03-b0r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.1 4.378c.023.243.234 1.157.544 1.71");
}

.c8t-c_brq {
  stop-color: var(--svg-color--594c7d, #594C7D);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ccr6o7bqr {
  d: path("M20.818 12.53a1.61 1.61 0 1 0 0-3.22a1.61 1.61 0 0 0 0 3.22");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cho8x9bqp {
  d: path("M18.71 15.718h-5.42v13.89h5.42z");
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.csqw4-28q {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.609 10.559l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyqispo_i {
  d: path("M16.072 15.898h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.d_iqknbvq {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.593 9.142l-.004.003a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077c.098-.047.238-.107.41-.162c.34-.108.815-.2 1.328-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d8npuof1g {
  d: path("M14.045 16.488c.02.213.205.69.746 1.055c.214.143 1.213.628 1.193.619c.156-.079.807-.3 1.284-.62c.54-.363.725-.84.746-1.054l-1.985-.953z");
}

.dk_rexb0w {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.722 8.685l-.137.23za.268.268 0 0 1-.275.46l-.005-.003l-.022-.012l-.09-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.109a3.3 3.3 0 0 1 .558.239l.01.005z");
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1n1g8gyb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.6 9.574c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271A1.4 1.4 0 0 0 13.6 9.574");
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.ebfi_gblr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.11 10.035c.063.085-.07.188-.221.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.erw_h94je {
  d: path("M18.175 9.846a.892.892 0 0 1 .86 1.128H17.31a.896.896 0 0 1 .864-1.128");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
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

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
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

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.g4wi6gddi {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.818 11.994a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gkzmut59n {
  stop-color: var(--svg-color--a89cb3, #A89CB3);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gu8xo7toj {
  d: path("M18.11 10.035c.063.085-.07.188-.221.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
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

.hwqc8s6cj {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.593 13.443a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.246-.041h-.001c-.404.215-.88.339-1.398.339a3 3 0 0 1-1.398-.34Z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i_25dj3ib {
  stop-color: var(--svg-color--a093a3, #A093A3);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.icxc77_wy {
  cx: 13.537px;
  cy: 10.227px;
  rx: 0.39px;
  ry: 0.197px;
}

.idggc37ct {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.598 10.697l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.ifsrrmuqt {
  d: path("M20.818 11.994a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.ir0l7gb9v {
  d: path("M13.807 9.846a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.iwz00abqx {
  stop-color: var(--svg-color--5f5289, #5F5289);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
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

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jk63qxbcl {
  cx: 13.537px;
  cy: 10.227px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.jybxgogov {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kmq3_bbmh {
  fill: var(--svg-color--463d68, #463D68);
  d: path("m20.905 20.78l-1.19-.828a.23.23 0 0 1 .166-.394h.919a.252.252 0 0 0 .227-.358l-1.076-2.29a8 8 0 0 0-.646-.237h-.595v11.862l2.404-6.872a.85.85 0 0 0-.21-.883");
}

.knib4pb5u {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
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

.l06e93bca {
  d: path("m16.01 17.925l-1.24 1.205a.15.15 0 0 0-.033.167l.547 1.26a.25.25 0 0 0 .23.151h.952c.1 0 .19-.06.23-.151l.55-1.28a.15.15 0 0 0-.033-.167z");
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
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

.lovk48bju {
  d: path("M18.97 10.62a.84.84 0 0 0-.232-.462l-.26.285l.118.229z");
}

.lq7rmabig {
  d: path("M15.388 3.13c-1.133-.25-2.15.88-2.267 1.298c1.051 3.545 3.713 3.351 6.34 3.06c1.572-.175 1.743.541 1.877.888c0-3.933-3.344-4.671-5.922-5.24z");
}

.lv0iykbih {
  stop-color: var(--svg-color--56406d, #56406D);
}

.m5bm-ccxd {
  stop-color: var(--svg-color--7b74a6, #7B74A6);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mf716dhmi {
  stop-color: var(--svg-color--544a5f, #544A5F);
}

.mk0gy856t {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.388 3.13c-1.133-.25-2.15.88-2.267 1.298c1.051 3.545 3.713 3.351 6.34 3.06c1.572-.175 1.743.541 1.877.888c0-3.933-3.344-4.671-5.922-5.24z");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mqs7o2bnn {
  fill: var(--svg-color--41355c, #41355C);
  d: path("M13.419 16.447c-.513 0-1.296-.03-1.77.166l-1.38 2.724c-.09.19.06.41.27.41h1.55c.24 0 .35.29.19.45l-1.78 1.343c-.26.26-.36.65-.23 1l2.912 6.5l1.587-1.116l-1.34-11.477z");
}

.msod-5bzd {
  d: path("M16 14.655h-2.71v4.74c0 .31.36.49.61.29l2.1-1.392l2.1 1.392c.25.2.61.02.61-.29v-4.74z");
}

.mu96iuqwe {
  stop-color: var(--svg-color--4b375e, #4B375E);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.nj166n02i {
  d: path("m15.609 10.559l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.noozichez {
  fill: var(--svg-color--000, #000);
  d: path("M14.318 10.738a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omh3jbc5e {
  stop-color: var(--svg-color--776d9f, #776D9F);
}

.omyqhdc3g {
  stop-color: var(--svg-color--bc818c, #BC818C);
}

.oou4fxxcq {
  fill: var(--svg-color--605890, #605890);
  d: path("m21.22 20.718l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p-sb3ibac {
  stop-color: var(--svg-color--483b55, #483B55);
}

.pagefvi7k {
  d: path("M23 17.616v11.982h4v-3.5a10.98 10.98 0 0 0-4-8.482");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pc2b66ykc {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
  stop-opacity: 0;
}

.pj6fmxxss {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.382 9.574c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q35o5nbax {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.133 10.351c.265-.467.669-.836 1.537-.836c.38 0 .747.106 1.073.37c.269.216.233.494.025.598l-.556.318c-.652-.21-1.373-.24-2.079-.45");
}

.q8ootib3t {
  stop-color: var(--svg-color--5f5490, #5F5490);
  stop-opacity: 0;
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
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

.rop63gbyj {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
  stop-opacity: 0;
}

.rpmno-b9y {
  stop-color: var(--svg-color--41375c, #41375C);
}

.s-2x0fj8v {
  stop-color: var(--svg-color--c79290, #C79290);
}

.s3tb_6b2n {
  stop-color: var(--svg-color--3d3247, #3D3247);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.sebnpqbxu {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.849 10.351c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.106-1.073.37c-.269.216-.233.494-.025.598l.556.318c.652-.21 1.373-.24 2.079-.45");
}

.sgl1asp0z {
  d: path("M16.402 15.898c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.som6k-b6q {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.stwaw694b {
  fill: var(--svg-color--232121, #232121);
  d: path("M10.922 4.932c.566-.6 1.636-.6 2.13-.511l.396 1.29c-.253-.039-.478.05-.667.235c-.449 1.26-1.99 1.956-2.704 2.146c-.149-1.492.109-2.38.845-3.16");
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.t1jnqlbxn {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.325 11.994a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.twdgiactz {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.14 8.547c-.323-.078-1.125-.039-1.661.345");
}

.u61ykmvtc {
  stop-color: var(--svg-color--584982, #584982);
}

.u8nlhyb2v {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("M18.397 6.74L16.972 7a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.396 1.9 1.872a3.15 3.15 0 0 0-2.69-.769");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ugh29hhiz {
  stop-color: var(--svg-color--7a6c85, #7A6C85);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vhf08lbkn {
  d: path("M7.032 29.598H8.97V17.634a11 11 0 0 0-3.656 5.843a11 11 0 0 0-.304 2.631l.02 3.49z");
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.wdy63qb5p {
  stop-color: var(--svg-color--c6bbd1, #C6BBD1);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wn_idr65v {
  fill-rule: evenodd;
  d: path("M23.176 12.33c.213-.435.324-.921.324-1.427a3.3 3.3 0 0 0-.269-1.306h.006a3 3 0 0 0-.281-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.77V7.3A3.3 3.3 0 0 0 19.128 4a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001A3.3 3.3 0 0 0 9.554 7.3v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455A3.213 3.213 0 0 0 11.7 17.41h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.122-.982-.324-1.407a.52.52 0 0 1 0-.455m-12.26-2.673h-.012l1.198 2.356c.124 2.802 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197C21.033 7.888 20.131 7.8 19.95 7.8h-3.22a3.86 3.86 0 0 1-3.189-1.673a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.19 1.235l-.051.02l-.051.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y72bh29go {
  d: path("M14.622 10.634c0-.289-.234-.481-.298-.54l-.288.28l.177.36z");
}

.yfhz1ybyq {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
}

.ym90ysber {
  d: path("M13.29 15.688h-.85c-.18.06-.36.13-.53.2l-1.27 2.69c-.09.19.06.41.27.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01v-13.9z");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yqlqjsfuk {
  stop-color: var(--svg-color--55477c, #55477C);
}

.z_fy1nb8g {
  stop-color: var(--svg-color--c58998, #C58998);
  stop-opacity: 0;
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z72oadczb {
  d: path("M11.305 12.53a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.218");
}

.zgkix-53c {
  d: path("M11.325 11.994a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.zl3z80qcv {
  d: path("M10.904 9.657h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439l.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.082.088 1.135 1.333l-.118 3.073c-.124 2.802-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.zm9c_pbne {
  stop-color: var(--svg-color--625a91, #625A91);
  stop-opacity: 0;
}

.zs13mzbvi {
  stop-color: var(--svg-color--af6d91, #AF6D91);
}

.zvvx29b3a {
  d: path("M16 15.098c-6.08 0-11 4.92-11 11v3.5h22v-3.5c0-6.07-4.93-11-11-11");
}

</style>
