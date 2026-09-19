<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iPh3GNc)" class="qcgh4gb9v"/><path fill="url(#ihpw7QE)" class="qcgh4gb9v"/><path fill="url(#i87r91c)" class="qcgh4gb9v"/><path fill="url(#ik91kmb)" class="qcgh4gb9v"/><rect fill="url(#iCrcB2b)" class="gmo09s50p"/><rect fill="url(#i08HGgG)" class="gmo09s50p"/><g filter="url(#iWikz1R)"><path class="dc1uu9b2m"/><path fill="url(#iSbEbdb)" class="pufzettfr"/><path fill="url(#iBM3hJb)" class="pufzettfr"/><path class="i4sqjslmc"/></g><g filter="url(#iV7vyKb)"><path fill="url(#i49HgBU)" class="jhda4212k"/><path fill="url(#i7k1Gte)" class="jhda4212k"/><path fill="url(#izNJdBb)" class="jhda4212k"/></g><g filter="url(#i7v0Dme)"><path clip-rule="evenodd" class="flr3dlbpr"/><path fill="url(#inyiHGe)" clip-rule="evenodd" class="ptj8svxtg"/><path fill="url(#iFx4vpb)" clip-rule="evenodd" class="ptj8svxtg"/><path fill="url(#iLD4thc)" clip-rule="evenodd" class="ptj8svxtg"/></g><g filter="url(#i7EzuTb)"><path clip-rule="evenodd" class="wr_e2zbwe"/><path fill="url(#iQe0aNd)" clip-rule="evenodd" class="djszrn9ws"/><path fill="url(#i3BA2Ld)" clip-rule="evenodd" class="djszrn9ws"/><path fill="url(#iIPovlb)" clip-rule="evenodd" class="djszrn9ws"/></g><g filter="url(#iZwyitb)"><path clip-rule="evenodd" class="g2ptt7gzz"/><path fill="url(#iegJ1eb)" clip-rule="evenodd" class="nbzkw-med"/><path fill="url(#iuOI9Vb)" clip-rule="evenodd" class="nbzkw-med"/><path fill="url(#iluSSpM)" clip-rule="evenodd" class="nbzkw-med"/></g><g filter="url(#iMqXOZb)"><path clip-rule="evenodd" class="fwnss0e3m"/><path fill="url(#iQ40Cye)" clip-rule="evenodd" class="dc_-el2vm"/><path fill="url(#iGrRhND)" clip-rule="evenodd" class="dc_-el2vm"/><path fill="url(#ipRsbRb)" clip-rule="evenodd" class="dc_-el2vm"/></g><g filter="url(#i5SzkYd)"><path class="y5a1r2bum"/><path fill="url(#iyLTQec)" class="furegib2d"/><path fill="url(#iN8kiKd)" class="furegib2d"/><path fill="url(#iaAfXNd)" class="furegib2d"/></g><path fill="url(#iLjgpVe)" class="ukh84abxq"/><path fill="url(#iZ3DeVc)" class="ukh84abxq"/><g filter="url(#iMv5mEe)"><path fill="url(#ioNwhty)" class="xm7l4wblc"/><path fill="url(#iQXMFWc)" class="xm7l4wblc"/><path fill="url(#idHYAXb)" class="xm7l4wblc"/><path fill="url(#iVrOIWp)" class="xm7l4wblc"/></g><g filter="url(#ijk0wee)"><path stroke="url(#iPOoaac)" class="m0opo6bbh"/></g><g filter="url(#ipMrMld)"><circle fill="url(#isqLGZc)" class="jo9kslbvg"/></g><circle fill="url(#iqhKbED)" class="jo9kslbvg"/><g filter="url(#iqcyE1c)"><circle fill="url(#iDKr8se)" class="a1oixybvc"/></g><g filter="url(#iJVAuUd)"><circle fill="url(#iJYTgGe)" class="c0-_whbvj"/><circle fill="url(#i6myMsE)" class="c0-_whbvj"/></g><g filter="url(#ioLBwld)"><circle class="q-wyds55n"/><circle fill="url(#iSPKO1b)" class="fv-l3eb9p"/><circle fill="url(#iqWGCAe)" class="fv-l3eb9p"/></g><g filter="url(#iI7aNGu)"><path fill="url(#iLCBkPb)" class="c6l8th9lj"/><path fill="url(#iydFXee)" class="c6l8th9lj"/><path fill="url(#iFLtAzc)" class="c6l8th9lj"/></g><path fill="url(#ibY4jUd)" class="m3lpobbkf"/><path fill="url(#itNY9hL)" class="m3lpobbkf"/><path fill="url(#irZXemc)" class="m3lpobbkf"/><g filter="url(#ifUg7kc)"><path fill="url(#i2rBWJe)" class="myd1dnvgq"/></g><g filter="url(#i9g0H3c)"><path class="v04krhwzu"/><path fill="url(#ir8zMOS)" class="x-ga_webx"/><path fill="url(#iXMR7Xz)" class="x-ga_webx"/><path fill="url(#iUk3AIe)" class="x-ga_webx"/><path fill="url(#ibWkUdA)" class="x-ga_webx"/></g><g filter="url(#iDMKI5a)"><path class="ci-4jqbmt"/></g><g filter="url(#iG49Aoe)"><path class="c1k5k3b0s"/><path fill="url(#icZMsLb)" class="wom4lqbtj"/><path fill="url(#iGR9awb)" class="wom4lqbtj"/><path fill="url(#iWiRpWd)" class="wom4lqbtj"/><path fill="url(#ieZnV1d)" class="wom4lqbtj"/></g><path fill="url(#iNik2gV)" class="wom4lqbtj"/><path stroke="url(#iBG83xb)" class="ac5fyukrd"/><g filter="url(#iBIQVbb)"><path class="ili4hf98k"/><path fill="url(#iNRp74d)" class="m4jvb4lbj"/></g><g filter="url(#iDPKx6b)"><path class="mng6_sbqs"/><path fill="url(#igidiGS)" class="y2hx42boj"/></g><path class="lsm4wo0il"/><path fill="url(#i3KdFZb)" class="sbt-tumyu"/><path class="is-__hh9o"/><g filter="url(#izz3XNb)"><path class="nqt07ssya"/><path fill="url(#iO0krGd)" class="kg26iac7f"/></g><g filter="url(#iHtpPMc)"><path fill="url(#ioc3Cqc)" class="m5fjdpbci"/></g><path class="gojugjv6o"/><path fill="url(#im9URkc)" class="q-h41ezkf"/><path class="ulfybv1yg"/><g filter="url(#iRweI7b)"><path fill="url(#iPMHfcd)" class="au4n6sbel"/></g><g filter="url(#ic8F8ae)"><ellipse transform="rotate(-27.914 9.263 11.907)" class="u7ohzz30e"/><ellipse fill="url(#ioEq83F)" transform="rotate(-27.914 9.263 11.907)" class="cgp3v0siv"/></g><g filter="url(#iyP2zGc)"><path stroke="url(#iW2IJob)" class="o28tdfdvf"/></g><g filter="url(#iO3i0Pe)"><path stroke="url(#i8jgqie)" class="zycvbibcr"/></g><g filter="url(#izL87Bd)"><path stroke="url(#ioOB0Ob)" class="zkx31tb-j"/></g><defs><radialGradient id="ihpw7QE" cx="0" cy="0" r="1" gradientTransform="rotate(-128.9 17.743 9.605)scale(14.3752 17.7454)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="g-y53hltx"/><stop offset="1" class="v7mnt2b-x"/></radialGradient><radialGradient id="i87r91c" cx="0" cy="0" r="1" gradientTransform="rotate(80.311 -5.866 15.826)scale(6.49895 15.3845)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="g0t89xbpg"/><stop offset="1" class="k_v_c_b6y"/><stop offset="1" class="n7kcl4y1w"/></radialGradient><radialGradient id="ik91kmb" cx="0" cy="0" r="1" gradientTransform="rotate(-120.904 18.925 8.746)scale(9.57741 4.6091)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="iirf6bcfg"/><stop offset="1" class="qef24vbmi"/></radialGradient><radialGradient id="iCrcB2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.21875 -4.41943 0 12.394 20.633)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="awc29pfeb"/><stop offset="1" class="rs939fpht"/></radialGradient><radialGradient id="i08HGgG" cx="0" cy="0" r="1" gradientTransform="rotate(65.11 -10.246 19.087)scale(4.82627 5.58433)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="bo3c15bma"/><stop offset=".914" class="czlx86s7a"/></radialGradient><radialGradient id="iSbEbdb" cx="0" cy="0" r="1" gradientTransform="rotate(173.116 12.151 9.16)scale(.49483 .58088)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="iBM3hJb" cx="0" cy="0" r="1" gradientTransform="matrix(.00796 .06217 -.74977 .09602 24.356 16.492)" gradientUnits="userSpaceOnUse"><stop class="zou-tybqy"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="e0ixrbbzo"/></radialGradient><radialGradient id="i49HgBU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.42187 1.4375 -.43294 -.42823 24.034 13.063)" gradientUnits="userSpaceOnUse"><stop class="s8lp15btp"/><stop offset="1" class="f3rvvbc1q"/></radialGradient><radialGradient id="i7k1Gte" cx="0" cy="0" r="1" gradientTransform="matrix(-.37263 .08503 -.18186 -.797 24.345 14.189)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="izNJdBb" cx="0" cy="0" r="1" gradientTransform="matrix(1.12934 .73823 -1.10747 1.6942 21.148 13.79)" gradientUnits="userSpaceOnUse"><stop class="razeofbhj"/><stop offset="1" class="ei3uyjb-y"/></radialGradient><radialGradient id="inyiHGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.58754 .06566 -.07147 -.63952 29.686 14.595)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="iFx4vpb" cx="0" cy="0" r="1" gradientTransform="matrix(.07825 .46522 -6.05348 1.01824 28.297 13.318)" gradientUnits="userSpaceOnUse"><stop class="zou-tybqy"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="e0ixrbbzo"/></radialGradient><radialGradient id="iLD4thc" cx="0" cy="0" r="1" gradientTransform="matrix(1.78068 .57009 -.54226 1.69375 24.647 14.287)" gradientUnits="userSpaceOnUse"><stop class="razeofbhj"/><stop offset="1" class="ei3uyjb-y"/></radialGradient><radialGradient id="iQe0aNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.58467 .06405 -.06838 -.62413 30.264 14.895)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="i3BA2Ld" cx="0" cy="0" r="1" gradientTransform="matrix(.07787 .4538 -6.0172 1.03254 28.882 13.65)" gradientUnits="userSpaceOnUse"><stop class="zou-tybqy"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="e0ixrbbzo"/></radialGradient><radialGradient id="iIPovlb" cx="0" cy="0" r="1" gradientTransform="matrix(1.77198 .5561 -.5204 1.65823 25.25 14.595)" gradientUnits="userSpaceOnUse"><stop class="razeofbhj"/><stop offset="1" class="ei3uyjb-y"/></radialGradient><radialGradient id="iegJ1eb" cx="0" cy="0" r="1" gradientTransform="matrix(-.58658 .06175 -.0634 -.60226 29.983 15.34)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="iuOI9Vb" cx="0" cy="0" r="1" gradientTransform="matrix(.07813 .4375 -6.0225 1.07545 28.596 14.14)" gradientUnits="userSpaceOnUse"><stop class="zou-tybqy"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="e0ixrbbzo"/></radialGradient><radialGradient id="iluSSpM" cx="0" cy="0" r="1" gradientTransform="matrix(1.77775 .53612 -.48545 1.6097 24.952 15.051)" gradientUnits="userSpaceOnUse"><stop class="razeofbhj"/><stop offset="1" class="ei3uyjb-y"/></radialGradient><radialGradient id="iQ40Cye" cx="0" cy="0" r="1" gradientTransform="rotate(169.423 13.843 9.188)scale(.90027 1.06791)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="iGrRhND" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 4.84 23.437)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="iyLTQec" cx="0" cy="0" r="1" gradientTransform="matrix(-.96409 .10438 -.11015 -1.0174 29.216 15.74)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="iN8kiKd" cx="0" cy="0" r="1" gradientTransform="matrix(.01563 .10937 -1.46562 .20938 27.337 15.203)" gradientUnits="userSpaceOnUse"><stop class="zou-tybqy"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="e0ixrbbzo"/></radialGradient><radialGradient id="iaAfXNd" cx="0" cy="0" r="1" gradientTransform="rotate(17.232 -39.85 76.747)scale(3.05919 2.83525)" gradientUnits="userSpaceOnUse"><stop class="razeofbhj"/><stop offset="1" class="ei3uyjb-y"/></radialGradient><radialGradient id="iLjgpVe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05458 -2.63643 0 24.104 17.387)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="b4neizb2f"/><stop offset="1" class="w_-1espii"/></radialGradient><radialGradient id="idHYAXb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1875 0 0 -.57813 24.721 19.227)" gradientUnits="userSpaceOnUse"><stop class="rj7t3yb7a"/><stop offset="1" class="j6_oc_gyi"/></radialGradient><radialGradient id="isqLGZc" cx="0" cy="0" r="1" gradientTransform="matrix(2.22935 0 0 3.90139 4.23 12.895)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iqhKbED" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 7.086 5.854)scale(2.1047)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="i6myMsE" cx="0" cy="0" r="1" gradientTransform="matrix(1.05023 -.76473 .87284 1.1987 18.91 12.559)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iSPKO1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.04333 -1.91895 1.12316 .61067 18.384 13.939)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iqWGCAe" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -6.46 28.864)scale(.46348 .59749)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iydFXee" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.6605 2.04368 0 15.363 11.28)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iFLtAzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.74565 2.17087 0 9.572 11.45)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="irZXemc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.5803 -13.1136 0 12.22 10.947)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="dcym8repk"/><stop offset=".884" class="fkee40m0y"/><stop offset="1" class="an_-aznlj"/></radialGradient><radialGradient id="ir8zMOS" cx="0" cy="0" r="1" gradientTransform="matrix(1.01354 -3.75605 1.39286 .37585 17.903 7.679)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iXMR7Xz" cx="0" cy="0" r="1" gradientTransform="matrix(4.859 .44715 -.24043 2.61266 15.816 5.443)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iUk3AIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1332 -3.30372 0 12.383 1.969)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="ibWkUdA" cx="0" cy="0" r="1" gradientTransform="matrix(3.9051 -2.86175 4.48342 6.118 4.19 10.63)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="ieZnV1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25014 -.80364 0 12.798 14.936)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iNRp74d" cx="0" cy="0" r="1" gradientTransform="matrix(.13237 -.76638 2.26728 .3916 15.486 10.248)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="igidiGS" cx="0" cy="0" r="1" gradientTransform="matrix(.13238 -.76638 2.2674 .39165 8.946 10.248)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i3KdFZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03045 -1.63905 0 15.15 12.029)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iO0krGd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 10.402 2.429)scale(.48046 .66148)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="im9URkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.0305 -1.63913 0 9.608 12.029)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ioEq83F" cx="0" cy="0" r="1" gradientTransform="matrix(-.00983 -.62753 .75432 -.01181 9.244 12.307)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iWikz1R" width="4.015" height="2.316" x="21.258" y="15.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="iV7vyKb" width="3.045" height="3.19" x="21.269" y="12.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="i7v0Dme" width="4.802" height="2.532" x="24.837" y="13.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="i7EzuTb" width="4.778" height="2.477" x="25.438" y="13.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="iZwyitb" width="4.794" height="2.399" x="25.141" y="13.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="iMqXOZb" width="7.879" height="3.847" x="21.258" y="13.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.603922 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="i5SzkYd" width="7.879" height="3.847" x="21.258" y="13.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="iMv5mEe" width="6.491" height="11.844" x="20.116" y="18.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.482353 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="ijk0wee" width="5.75" height="1.328" x="23" y="15.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".125"/></filter><filter id="ipMrMld" width="4.442" height="4.242" x="4.23" y="10.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="iqcyE1c" width="3.528" height="3.528" x="4.587" y="11.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".25"/></filter><filter id="iJVAuUd" width="4.492" height="4.492" x="16.316" y="10.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="ioLBwld" width="3.528" height="3.528" x="16.672" y="11.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".25"/></filter><filter id="iI7aNGu" width="13.179" height="15.53" x="5.83" y="5.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="ifUg7kc" width="9.394" height="7.896" x="10.598" y="3.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation="1"/></filter><filter id="i9g0H3c" width="16.009" height="10.718" x="4.378" y="1.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="iDMKI5a" width="3.736" height="4.906" x="10.211" y="11.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".375"/></filter><filter id="iG49Aoe" width="2.884" height="3.906" x="10.94" y="11.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".125"/></filter><filter id="iBIQVbb" width="3.718" height="2.271" x="13.884" y="8.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="iDPKx6b" width="3.718" height="2.271" x="7.345" y="8.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3797"/></filter><filter id="izz3XNb" width=".945" height=".83" x="14.245" y="11.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".05"/></filter><filter id="iHtpPMc" width="1.024" height="1.052" x="15.339" y="11.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".1"/></filter><filter id="iRweI7b" width="1.145" height="1.213" x="9.696" y="11.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".1"/></filter><filter id="ic8F8ae" width="1.106" height=".841" x="8.71" y="11.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".05"/></filter><filter id="iyP2zGc" width="3.849" height="2.048" x="13.742" y="8.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".25"/></filter><filter id="iO3i0Pe" width="3.948" height="2.12" x="7.111" y="8.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".25"/></filter><filter id="izL87Bd" width="1.078" height="2.68" x="5.921" y="6.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3797" stdDeviation=".125"/></filter><linearGradient id="iPh3GNc" x1="12.382" x2="12.382" y1="30.602" y2="25.695" gradientUnits="userSpaceOnUse"><stop class="yyvoflbon"/><stop offset="1" class="a17t51bmy"/></linearGradient><linearGradient id="ipRsbRb" x1="24.588" x2="26.182" y1="16.84" y2="16.527" gradientUnits="userSpaceOnUse"><stop offset=".585" class="oc3fsgi2c"/><stop offset="1" class="v-pv693fm"/></linearGradient><linearGradient id="iZ3DeVc" x1="23.483" x2="23.483" y1="18.338" y2="18.164" gradientUnits="userSpaceOnUse"><stop offset=".316" class="t67vcgb3p"/><stop offset="1" class="aygc7mb2y"/></linearGradient><linearGradient id="ioNwhty" x1="24.354" x2="24.354" y1="19.402" y2="38.715" gradientUnits="userSpaceOnUse"><stop class="j-_n76q-e"/><stop offset=".621" class="fo4wibbqd"/></linearGradient><linearGradient id="iQXMFWc" x1="27.768" x2="22.341" y1="28.93" y2="28.93" gradientUnits="userSpaceOnUse"><stop class="q6r_-7b5d"/><stop offset=".458" class="wfemjwbrc"/><stop offset="1" class="q6r_-7b5d"/></linearGradient><linearGradient id="iVrOIWp" x1="23.312" x2="23.312" y1="18.243" y2="19.277" gradientUnits="userSpaceOnUse"><stop offset=".366" class="txyof8k0f"/><stop offset="1" class="cd6uw5bqs"/></linearGradient><linearGradient id="iPOoaac" x1="28.027" x2="23.189" y1="15.842" y2="16.394" gradientUnits="userSpaceOnUse"><stop class="fxqi8abqb"/><stop offset="1" class="u1zz4n4nv"/></linearGradient><linearGradient id="iDKr8se" x1="6.351" x2="5.537" y1="13.249" y2="13.249" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iJYTgGe" x1="19.817" x2="18.777" y1="11.509" y2="14.731" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iLCBkPb" x1="17.51" x2="7.808" y1="13.39" y2="14.836" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="ibY4jUd" x1="5.528" x2="7.918" y1="16.815" y2="16.73" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="itNY9hL" x1="18.634" x2="17.221" y1="15.746" y2="15.623" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="i2rBWJe" x1="11.707" x2="22.053" y1="9.598" y2="5.894" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="icZMsLb" x1="11.285" x2="12.477" y1="14.228" y2="14.228" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iGR9awb" x1="13.575" x2="12.272" y1="14.637" y2="14.619" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iWiRpWd" x1="12.63" x2="12.63" y1="15.58" y2="14.852" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iNik2gV" x1="12.542" x2="12.542" y1="15.634" y2="15.421" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="iBG83xb" x1="11.065" x2="11.618" y1="17.632" y2="16.759" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ioc3Cqc" x1="16.139" x2="15.74" y1="12.097" y2="12.343" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPMHfcd" x1="10.553" x2="10.154" y1="12.097" y2="12.343" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iW2IJob" x1="16.159" x2="15.625" y1="9.379" y2="8.288" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="i8jgqie" x1="9.42" x2="7.909" y1="9.217" y2="8.583" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="ioOB0Ob" x1="6.46" x2="6.46" y1="6.658" y2="9.398" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-tipping-hand-medium" /></template>
<style>
.a17t51bmy {
  stop-color: var(--svg-color--1388c7, #1388C7);
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a1oixybvc {
  cx: 6.351px;
  cy: 12.895px;
  r: 1.264px;
}

.ac5fyukrd {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.646 16.41a.244.244 0 0 0-.291.05a.224.224 0 0 0-.025.288a2.46 2.46 0 0 0 2.053 1.096c.861 0 1.618-.438 2.052-1.096a.23.23 0 0 0-.025-.29a.245.245 0 0 0-.29-.048a3.75 3.75 0 0 1-1.737.412c-.637 0-1.235-.15-1.737-.412Z");
}

.adnp-y-dh {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
  stop-opacity: 0;
}

.an_-aznlj {
  stop-color: var(--svg-color--7c5267, #7C5267);
}

.au4n6sbel {
  d: path("M10.64 12.424c0-.367-.297-.611-.377-.685l-.367.354l.226.46z");
}

.awc29pfeb {
  stop-color: var(--svg-color--855169, #855169);
}

.ax8207b9e {
  stop-color: var(--svg-color--e4b833, #E4B833);
  stop-opacity: 0;
}

.aygc7mb2y {
  stop-color: var(--svg-color--327aa5, #327AA5);
  stop-opacity: 0;
}

.b4neizb2f {
  stop-color: var(--svg-color--4a9fe0, #4A9FE0);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bo3c15bma {
  stop-color: var(--svg-color--907374, #907374);
  stop-opacity: 0;
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c0-_whbvj {
  cx: 18.436px;
  cy: 12.895px;
  r: 2.121px;
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c1k5k3b0s {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m11.897 12.533l-.675 2.16a.685.685 0 0 0 .661.887h.999a.687.687 0 0 0 .661-.888l-.675-2.159c-.145-.478-.82-.478-.971 0");
}

.c6l8th9lj {
  d: path("m5.904 12.117l.062.002s-.068-1.084-.136-1.83c0-.338.136-.745.409-.948l.204-.203c.34-.271.477-.678.477-1.084V6.97c0-.339.205-.61.545-.678c.818-.203 2.522-.542 4.975-.542s4.156.339 4.974.542c.273.068.545.339.545.678v1.084c0 .406.205.813.477 1.084c.638.447.598.693.545 1.22c-.068.677-.136 1.829-.136 1.829h.023l-.338 5.028c-.204 2.248-1.97 3.815-4.078 3.815h-4.078c-2.176 0-3.875-1.567-4.079-3.815z");
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
}

.cd6uw5bqs {
  stop-color: var(--svg-color--20a5e9, #20A5E9);
  stop-opacity: 0;
}

.cgp3v0siv {
  cx: 9.263px;
  cy: 11.907px;
  rx: 0.495px;
  ry: 0.25px;
}

.ci-4jqbmt {
  fill: var(--svg-color--87565c, #87565C);
  d: path("M12.033 12.74L10.99 14.9c-.13.444.18.888.62.888h.936c.44 0 .75-.451.62-.889l-.633-2.159c-.135-.478-.36-.478-.501 0");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.czlx86s7a {
  stop-color: var(--svg-color--907374, #907374);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dc_-el2vm {
  fill-rule: evenodd;
  d: path("M25.57 14.017c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.248c.917-.102 1.759-.206 2.235-.308a.825.825 0 0 0-.346-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.dc1uu9b2m {
  fill: var(--svg-color--bd9679, #BD9679);
  d: path("M21.258 15.789h4.015v2.016h-4.015z");
}

.dcym8repk {
  stop-color: var(--svg-color--9b7168, #9B7168);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.djszrn9ws {
  fill-rule: evenodd;
  d: path("M30.203 14.51a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693c1.02-.096 1.89-.259 2.552-.383l.459-.084a.85.85 0 0 1 .984.69");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0ixrbbzo {
  stop-color: var(--svg-color--ab876c, #AB876C);
  stop-opacity: 0;
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.ei3uyjb-y {
  stop-color: var(--svg-color--956f58, #956F58);
  stop-opacity: 0;
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f3rvvbc1q {
  stop-color: var(--svg-color--ab866a, #AB866A);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fkee40m0y {
  stop-color: var(--svg-color--8f5d78, #8F5D78);
}

.flr3dlbpr {
  fill: var(--svg-color--bd9679, #BD9679);
  fill-rule: evenodd;
  d: path("M29.625 14.181a.85.85 0 0 1-.69.985a21 21 0 0 0-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.083.715-.142a.85.85 0 0 1 .985.69");
}

.fo4wibbqd {
  stop-color: var(--svg-color--1f98e9, #1F98E9);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.furegib2d {
  d: path("M25.57 14.017c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.874-.095 1.183-.192c.242-.077.5-.219.96-.306c.916-.102 1.758-.206 2.233-.308a.825.825 0 0 0-.345-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.fv-l3eb9p {
  cx: 18.436px;
  cy: 12.895px;
  r: 1.264px;
}

.fwnss0e3m {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M25.57 14.017c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.248c.917-.102 1.759-.206 2.235-.308a.825.825 0 0 0-.346-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.fxqi8abqb {
  stop-color: var(--svg-color--c9a38d, #C9A38D);
}

.g-y53hltx {
  stop-color: var(--svg-color--3da2ef, #3DA2EF);
}

.g0t89xbpg {
  stop-color: var(--svg-color--13669b, #13669B);
}

.g2ptt7gzz {
  fill: var(--svg-color--bd9679, #BD9679);
  fill-rule: evenodd;
  d: path("M29.932 15.067a.85.85 0 0 1-.772.921c-.322.029-.74.088-1.26.162l-.03.004a53 53 0 0 1-1.788.231a.85.85 0 1 1-.182-1.69c.622-.067 1.205-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.gmo09s50p {
  width: 4.898px;
  height: 6.68px;
  x: 9.944px;
  y: 17.009px;
  rx: 2.449px;
}

.gojugjv6o {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.343 11.078c-.83 0-1.53.572-1.721 1.345a.348.348 0 0 0 .34.432h2.834c.18 0 .324-.164.288-.345a1.78 1.78 0 0 0-1.741-1.432");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.i4sqjslmc {
  fill: var(--svg-color--a36a70, #A36A70);
  d: path("M21.258 15.789h4.015v2.016h-4.015z");
}

.iirf6bcfg {
  stop-color: var(--svg-color--0355ad, #0355AD);
}

.ili4hf98k {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m17.108 9.44l-.002-.001l-.002-.002l-.006-.005l-.015-.012a2 2 0 0 0-.197-.137a3.3 3.3 0 0 0-.533-.267a3.6 3.6 0 0 0-1.896-.201a.678.678 0 0 0 .211 1.34c.506-.08.91.013 1.187.122a2 2 0 0 1 .381.202l.01.008a.678.678 0 0 0 .862-1.047");
}

.is-__hh9o {
  fill: var(--svg-color--000, #000);
  d: path("M14.504 12.557c0-.361.289-.65.65-.65a.646.646 0 0 1 .576.948h-1.149a.6.6 0 0 1-.077-.298");
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j-_n76q-e {
  stop-color: var(--svg-color--2e9fed, #2E9FED);
}

.j6_oc_gyi {
  stop-color: var(--svg-color--4bb5fd, #4BB5FD);
  stop-opacity: 0;
}

.jc2cbvyjw {
  stop-color: var(--svg-color--886658, #886658);
  stop-opacity: 0;
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jhda4212k {
  d: path("M22.03 13.876c-.554.648-.74 1.417-.761 1.758l1.847-.102l.887-1.183c.29-.383.54-1.02-.035-1.442c-.466-.342-.945-.066-1.102.106a28 28 0 0 0-.836.863");
}

.jo9kslbvg {
  cx: 6.351px;
  cy: 12.895px;
  r: 2.121px;
}

.k_v_c_b6y {
  stop-color: var(--svg-color--2094e3, #2094E3);
  stop-opacity: 0;
}

.kg26iac7f {
  d: path("M15.07 11.663c.08.108-.088.24-.28.383s-.334.245-.415.136s.01-.312.201-.455c.192-.143.413-.172.494-.064");
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmvunqbvz {
  stop-color: var(--svg-color--cba68f, #CBA68F);
  stop-opacity: 0;
}

.lsm4wo0il {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.416 11.078c.83 0 1.53.572 1.72 1.345a.348.348 0 0 1-.34.432h-2.833a.292.292 0 0 1-.288-.345a1.775 1.775 0 0 1 1.741-1.432");
}

.m0opo6bbh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.375 16.42c.984-.047 3.363-.228 5-.578");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m3lpobbkf {
  d: path("M5.83 10.29c0-.339.136-.746.409-.949l.204-.203c.34-.271.477-.678.477-1.084V6.97c0-.339.205-.61.545-.678c.818-.203 2.522-.542 4.975-.542s4.156.339 4.974.542c.273.068.545.339.545.678v1.084c0 .406.205.813.477 1.084c.638.447.598.693.545 1.22c-.068.677-.136 1.829-.136 1.829h.023l-.338 5.028c-.204 2.248-1.97 3.815-4.078 3.815h-4.078c-2.176 0-3.875-1.567-4.079-3.815c-.177-2.307-.255-4.622-.465-6.925");
}

.m4jvb4lbj {
  d: path("m17.108 9.44l-.002-.001l-.002-.002l-.006-.005l-.015-.012a2 2 0 0 0-.197-.137a3.3 3.3 0 0 0-.533-.267a3.6 3.6 0 0 0-1.896-.201a.678.678 0 0 0 .211 1.34c.506-.08.91.013 1.187.122a2 2 0 0 1 .381.202l.01.008a.678.678 0 0 0 .862-1.047");
}

.m5fjdpbci {
  d: path("M16.163 12.407a1.07 1.07 0 0 0-.294-.587l-.33.362l.149.29z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mng6_sbqs {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m7.589 9.44l.002-.001l.002-.002l.006-.005l.015-.012a2 2 0 0 1 .197-.137c.126-.079.306-.178.533-.267a3.6 3.6 0 0 1 1.896-.201a.678.678 0 0 1-.211 1.34c-.506-.08-.91.013-1.186.122a2 2 0 0 0-.392.21a.678.678 0 0 1-.862-1.047");
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.myd1dnvgq {
  d: path("m17.418 5.75l-3.91 1.304a1.33 1.33 0 0 0 .598 2.58l3.887-.52z");
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n7kcl4y1w {
  stop-color: var(--svg-color--13669b, #13669B);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nbzkw-med {
  fill-rule: evenodd;
  d: path("M29.932 15.067a.85.85 0 0 1-.772.921c-.322.029-.74.088-1.26.162l-.03.004a53 53 0 0 1-1.788.231a.85.85 0 1 1-.182-1.69c.622-.067 1.205-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.nqt07ssya {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.07 11.663c.08.108-.088.24-.28.383s-.334.245-.415.136s.01-.312.201-.455c.192-.143.413-.172.494-.064");
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o28tdfdvf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.492 9.256c.547-.095 1.612-.068 2.35.506");
}

.oc3fsgi2c {
  stop-color: var(--svg-color--ffca38, #FFCA38);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ptj8svxtg {
  fill-rule: evenodd;
  d: path("M29.625 14.181a.85.85 0 0 1-.69.985a21 21 0 0 0-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.083.715-.142a.85.85 0 0 1 .985.69");
}

.pufzettfr {
  d: path("M21.258 15.789h4.015v2.016h-4.015z");
}

.q-h41ezkf {
  d: path("M9.605 11.423a1.134 1.134 0 0 0-1.092 1.432h2.19a1.2 1.2 0 0 0 .04-.298a1.14 1.14 0 0 0-1.138-1.134");
}

.q-wyds55n {
  cx: 18.436px;
  cy: 12.895px;
  r: 1.264px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.q6r_-7b5d {
  stop-color: var(--svg-color--4ab6fe, #4AB6FE);
  stop-opacity: 0;
}

.qcgh4gb9v {
  d: path("M12.382 20.036c-5.523 0-10 4.477-10 10v.05h20v-.05c0-5.523-4.477-10-10-10");
}

.qef24vbmi {
  stop-color: var(--svg-color--2770bb, #2770BB);
  stop-opacity: 0;
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.razeofbhj {
  stop-color: var(--svg-color--956f58, #956F58);
}

.rj7t3yb7a {
  stop-color: var(--svg-color--4bb5fd, #4BB5FD);
}

.rs939fpht {
  stop-color: var(--svg-color--7b585c, #7B585C);
}

.rtamvw1ka {
  stop-color: var(--svg-color--e4b833, #E4B833);
}

.s8lp15btp {
  stop-color: var(--svg-color--c29e83, #C29E83);
}

.sbt-tumyu {
  d: path("M15.153 11.423a1.134 1.134 0 0 1 1.092 1.432h-2.19a1.138 1.138 0 0 1 1.098-1.432");
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.sn-83pben {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t67vcgb3p {
  stop-color: var(--svg-color--327aa5, #327AA5);
}

.tnzljqbeq {
  stop-color: var(--svg-color--cba68f, #CBA68F);
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.txyof8k0f {
  stop-color: var(--svg-color--20a5e9, #20A5E9);
}

.u1zz4n4nv {
  stop-color: var(--svg-color--c9a38d, #C9A38D);
  stop-opacity: 0;
}

.u7ohzz30e {
  cx: 9.263px;
  cy: 11.907px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.495px;
  ry: 0.25px;
}

.ukh84abxq {
  d: path("M21.015 17.548a.25.25 0 0 1 .25-.25h4.093a.25.25 0 0 1 .25.25v1.64h-4.593z");
}

.ulfybv1yg {
  fill: var(--svg-color--000, #000);
  d: path("M10.255 12.557c0-.361-.29-.65-.65-.65a.647.647 0 0 0-.577.948h1.15a.64.64 0 0 0 .076-.298");
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v-pv693fm {
  stop-color: var(--svg-color--ffca38, #FFCA38);
  stop-opacity: 0;
}

.v04krhwzu {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m18.505 4.666l.545.271c.954.474 1.499 1.559 1.294 2.71l-.75 3.862c-.066.4-.33.668-.726.678h-.023s.068-1.152.137-1.83c.055-.55-.041-.718-.546-1.22c-.272-.27-.477-.677-.477-1.083V6.97c0-.339-.272-.61-.545-.678c-.818-.203-2.521-.542-4.974-.542s-4.157.339-4.975.542c-.34.068-.545.339-.545.678v1.084c0 .406-.136.813-.477 1.084l-.204.203c-.273.203-.41.61-.41.949c.069.745.137 1.83.137 1.83l-.062-.003a.805.805 0 0 1-.756-.675l-.75-3.862c-.135-1.084.41-2.169 1.364-2.643l.545-.27c.34-.204.681-.475 1.022-.746l1.227-1.287c.75-.678 1.84-.881 2.794-.407a3.74 3.74 0 0 0 2.112 0c1.022-.339 2.18-.068 2.998.678l1.022 1.016c.273.339.614.542 1.023.745");
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v7mnt2b-x {
  stop-color: var(--svg-color--3da2ef, #3DA2EF);
  stop-opacity: 0;
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.w_-1espii {
  stop-color: var(--svg-color--4084b3, #4084B3);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.wfemjwbrc {
  stop-color: var(--svg-color--4ab6fe, #4AB6FE);
}

.wom4lqbtj {
  d: path("m11.897 12.533l-.675 2.16a.685.685 0 0 0 .661.887h.999a.687.687 0 0 0 .661-.888l-.675-2.159c-.145-.478-.82-.478-.971 0");
}

.wr_e2zbwe {
  fill: var(--svg-color--bd9679, #BD9679);
  fill-rule: evenodd;
  d: path("M30.203 14.51a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693c1.02-.096 1.89-.259 2.552-.383l.459-.084a.85.85 0 0 1 .984.69");
}

.x-ga_webx {
  d: path("m18.505 4.666l.545.271c.954.474 1.499 1.559 1.294 2.71l-.75 3.862c-.066.4-.33.668-.726.678h-.023s.068-1.152.137-1.83c.055-.55-.041-.718-.546-1.22c-.272-.27-.477-.677-.477-1.083V6.97c0-.339-.272-.61-.545-.678c-.818-.203-2.521-.542-4.974-.542s-4.157.339-4.975.542c-.34.068-.545.339-.545.678v1.084c0 .406-.136.813-.477 1.084l-.204.203c-.273.203-.41.61-.41.949c.069.745.137 1.83.137 1.83l-.062-.003a.805.805 0 0 1-.756-.675l-.75-3.862c-.135-1.084.41-2.169 1.364-2.643l.545-.27c.34-.204.681-.475 1.022-.746l1.227-1.287c.75-.678 1.84-.881 2.794-.407a3.74 3.74 0 0 0 2.112 0c1.022-.339 2.18-.068 2.998.678l1.022 1.016c.273.339.614.542 1.023.745");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xm7l4wblc {
  d: path("M20.116 19.043a.8.8 0 0 1 .8-.8h4.791a.8.8 0 0 1 .8.8v11.044h-6.39z");
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.y2hx42boj {
  d: path("m7.589 9.44l.002-.001l.002-.002l.006-.005l.015-.012a2 2 0 0 1 .197-.137c.126-.079.306-.178.533-.267a3.6 3.6 0 0 1 1.896-.201a.678.678 0 0 1-.211 1.34c-.506-.08-.91.013-1.186.122a2 2 0 0 0-.392.21a.678.678 0 0 1-.862-1.047");
}

.y5a1r2bum {
  fill: var(--svg-color--bd9679, #BD9679);
  d: path("M25.57 14.017c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.874-.095 1.183-.192c.242-.077.5-.219.96-.306c.916-.102 1.758-.206 2.233-.308a.825.825 0 0 0-.345-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.yyvoflbon {
  stop-color: var(--svg-color--2499ea, #2499EA);
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zkx31tb-j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M6.624 6.783v1.14c-.01.19-.09.612-.328.79");
}

.zou-tybqy {
  stop-color: var(--svg-color--ab876c, #AB876C);
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

.zycvbibcr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.861 9.915c.416-.367 1.324-.754 2.449-.575");
}

</style>
