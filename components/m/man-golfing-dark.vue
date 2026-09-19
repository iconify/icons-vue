<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ii2D01b)"><path fill="url(#iyiBi5c)" clip-rule="evenodd" class="gmmtdnb-k"/></g><g filter="url(#iJE0wWb)"><path class="zhvkip9xc"/><path fill="url(#iqiF37b)" class="dp5vh--ol"/><path fill="url(#ijK0cnc)" class="dp5vh--ol"/></g><path fill="url(#iAJAZ6c)" class="dp5vh--ol"/><path fill="url(#ie703Bb)" class="smfideibo"/><path fill="url(#iXzXWsg)" class="smfideibo"/><path fill="url(#iIliYga)" class="smfideibo"/><g filter="url(#iqCpEei)"><path class="gt2iksbiy"/></g><path class="k2_no2-ti"/><path fill="url(#i3Emvyc)" class="w5cnt0b9d"/><path fill="url(#izqJQwk)" class="w5cnt0b9d"/><path fill="url(#iHj3vDO)" class="w5cnt0b9d"/><path fill="url(#iFRYFzc)" class="w5cnt0b9d"/><g filter="url(#inJXBnd)"><path class="whyx-x2rb"/></g><path fill="url(#i6N14Cb)" class="v30w_lair"/><path fill="url(#ihC0RCr)" class="v30w_lair"/><path fill="url(#injDOoe)" class="v30w_lair"/><path fill="url(#iKdtryd)" class="v30w_lair"/><path fill="url(#ijcRIOe)" class="v30w_lair"/><path fill="url(#iSwCBbb)" class="v30w_lair"/><path fill="url(#idQQBsl)" class="v30w_lair"/><path fill="url(#i6kj8hb)" class="mbn2kyb-e"/><path fill="url(#i03l18f)" class="mbn2kyb-e"/><path fill="url(#i5WGsPc)" class="mbn2kyb-e"/><path fill="url(#ichV41c)" class="mbn2kyb-e"/><path fill="url(#i5jAEXQ)" class="mbn2kyb-e"/><rect transform="rotate(-26.783 20.65 4.055)" class="duukh4bkh"/><rect fill="url(#iPvp7Je)" transform="rotate(-26.783 21.084 3.795)" class="p7fla-b3y"/><rect fill="url(#iKLWW5c)" transform="rotate(-26.783 21.603 3.549)" class="b9lnu1iwb"/><rect fill="url(#iFXxeTp)" transform="rotate(-26.783 22.173 3.295)" class="a3kzqdbbr"/><rect fill="url(#iamRwDc)" transform="rotate(60 21.976 4.326)" class="mlryu5b4g"/><g filter="url(#ip5A3ad)"><path class="srbjw6b9u"/><path fill="url(#i1M0Jse)" class="f4zimzw3l"/></g><g filter="url(#ieFCoCe)"><path fill="url(#i6rC79y)" class="kimgmsbzt"/><path fill="url(#i1a10YI)" class="kimgmsbzt"/><path fill="url(#ixbTW8d)" class="kimgmsbzt"/></g><g filter="url(#intC61b)"><path class="wkyu36bsz"/></g><g filter="url(#iUpQjJd)"><path stroke="url(#i9S1RYd)" class="fts5n54lg"/></g><g filter="url(#i3dgCkX)"><path fill="url(#iAXqFib)" class="mrhht-dbj"/></g><g filter="url(#i9MLppc)"><circle fill="url(#iXdsnsv)" transform="rotate(-28.49 16.38 5.284)" class="aq2ig4h0o"/><circle fill="url(#ioPJOcd)" transform="rotate(-28.49 16.38 5.284)" class="aq2ig4h0o"/></g><g filter="url(#i9OUWuc)"><circle transform="rotate(-28.49 16.38 5.284)" class="yh77kabjp"/><circle fill="url(#iBBZWHd)" transform="rotate(-28.49 16.38 5.284)" class="c1-0b4bsg"/><circle fill="url(#iWs52ce)" transform="rotate(-28.49 16.38 5.284)" class="c1-0b4bsg"/></g><g filter="url(#i2fu2mJ)"><circle fill="url(#ij1OwGd)" transform="rotate(-28.49 12.923 7.16)" class="wbfx56k9g"/></g><g filter="url(#iYOPNnF)"><circle fill="url(#iluzu7c)" transform="rotate(-28.49 12.923 7.16)" class="j231iobwp"/></g><path fill="url(#iiy7Qrc)" class="y5b7-3icb"/><path fill="url(#imwvtbd)" class="y5b7-3icb"/><path fill="url(#ikufAeZ)" class="y5b7-3icb"/><path fill="url(#izZhYJd)" class="y5b7-3icb"/><path fill="url(#irr5Dld)" class="y5b7-3icb"/><path fill="url(#iqrUWtd)" class="y5b7-3icb"/><path fill="url(#ib6cCdd)" class="y5b7-3icb"/><path fill="url(#iNStvhe)" class="y5b7-3icb"/><g filter="url(#i1Xdmpc)"><path class="syrcgtb4c"/></g><g filter="url(#iNAMlzc)"><path class="no3flhbcy"/><path fill="url(#i7Ng0Ie)" class="bnzv-4xpp"/><path fill="url(#iF381Cd)" class="bnzv-4xpp"/><path fill="url(#iOjVIbc)" class="bnzv-4xpp"/><path fill="url(#iS6mcLc)" class="bnzv-4xpp"/><path fill="url(#i7yOo0Q)" class="bnzv-4xpp"/></g><path stroke="url(#iTJw73b)" class="u74slacjt"/><path class="nwl71xhuy"/><path fill="url(#ikk7zEb)" class="cnoiw-b7a"/><path class="jms61nr7p"/><g filter="url(#i2TNvnd)"><path class="lyogqkadi"/><path fill="url(#iRDfDEC)" class="njmjl6b2j"/></g><g filter="url(#i4sbNGc)"><path fill="url(#iSU4yPe)" class="x1g0b-w7w"/></g><path class="z6kjlwv6e"/><path fill="url(#ipskdpd)" class="p32z24bkw"/><path class="oa1gztksx"/><g filter="url(#i0zeZ1c)"><path fill="url(#i6IBtse)" class="n1k33obob"/></g><g filter="url(#iOLnOjI)"><ellipse transform="rotate(-56.403 13.602 6.425)" class="np5o-2bpn"/><ellipse fill="url(#ifxXoXb)" transform="rotate(-56.403 13.602 6.425)" class="t7l4d-tey"/></g><g filter="url(#ilGd7Xb)"><path clip-rule="evenodd" class="epem68pfv"/></g><g filter="url(#if1hRPs)"><path clip-rule="evenodd" class="a0mesmzaf"/></g><path fill="url(#ijSglMe)" class="lmyw-ob7g"/><path fill="url(#iZxEw0b)" class="xdr4qbcbn"/><g filter="url(#irFCGEd)"><path fill="url(#ikwYf5d)" class="yp23hxdko"/><path fill="url(#iiQZNBj)" class="yp23hxdko"/></g><path fill="url(#irqfHEe)" class="qy03eqbwm"/><path fill="url(#iIO2tqb)" class="qy03eqbwm"/><path fill="url(#iK5THde)" class="qy03eqbwm"/><path fill="url(#iboQnmb)" class="qy03eqbwm"/><defs><radialGradient id="iqiF37b" cx="0" cy="0" r="1" gradientTransform="rotate(146.915 8.78 5.894)scale(4.92324 2.04943)" gradientUnits="userSpaceOnUse"><stop class="ba1yb3bji"/><stop offset="1" class="kgrhzo17p"/></radialGradient><radialGradient id="iAJAZ6c" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -.0625 .23626 5.43402 6.51 13.634)" gradientUnits="userSpaceOnUse"><stop class="wn-t5ndzy"/><stop offset="1" class="ben4f0bqs"/></radialGradient><radialGradient id="iIliYga" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .16016 -.21807 -.37232 24.841 2.888)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="i42zc8m6u"/><stop offset="1" class="dsumrvbgt"/></radialGradient><radialGradient id="izqJQwk" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 -.46876 .24583 -.45888 14.134 29.493)" gradientUnits="userSpaceOnUse"><stop class="ynlfw99ba"/><stop offset="1" class="in-vfpgwh"/></radialGradient><radialGradient id="iHj3vDO" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .85157 -1.15842 -1.0415 12.743 26.985)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="vkrof_bbk"/><stop offset="1" class="h8hiq33uv"/></radialGradient><radialGradient id="iFRYFzc" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 .15625 -.58594 3.04687 11.368 28.384)" gradientUnits="userSpaceOnUse"><stop class="ilg8l_bzj"/><stop offset="1" class="s2j02zbkr"/></radialGradient><radialGradient id="ihC0RCr" cx="0" cy="0" r="1" gradientTransform="matrix(2.71873 -2.53127 .81258 .87276 13.166 27.946)" gradientUnits="userSpaceOnUse"><stop class="pcvpzjboo"/><stop offset="1" class="qe_2d-buv"/></radialGradient><radialGradient id="injDOoe" cx="0" cy="0" r="1" gradientTransform="matrix(2.54688 -2.64063 .2894 .27913 12.275 26.29)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="kxzgmzb5t"/><stop offset="1" class="xhu8yhbcw"/></radialGradient><radialGradient id="iKdtryd" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 0 0 -5.02098 17.369 21.634)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="keljo6scd"/><stop offset="1" class="ps4m-ab9c"/></radialGradient><radialGradient id="ijcRIOe" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 -.98437 1.15192 .05485 17.619 18.305)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="w5oxhdc5r"/><stop offset="1" class="ebs2-pbbe"/></radialGradient><radialGradient id="iSwCBbb" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 0 0 7.6823 17.978 22.993)" gradientUnits="userSpaceOnUse"><stop class="j_l_30buh"/><stop offset="1" class="xi8fv135v"/></radialGradient><radialGradient id="idQQBsl" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -3.34375 1.20794 1.23052 13.666 28.009)" gradientUnits="userSpaceOnUse"><stop class="ddjhanboc"/><stop offset="1" class="uu7_gub8n"/></radialGradient><radialGradient id="i6kj8hb" cx="0" cy="0" r="1" gradientTransform="rotate(150.356 8.575 7.607)scale(4.42262 6.15908)" gradientUnits="userSpaceOnUse"><stop class="no0_3dbdi"/><stop offset="1" class="truekjbvb"/></radialGradient><radialGradient id="i03l18f" cx="0" cy="0" r="1" gradientTransform="matrix(.57404 2.73801 -4.6268 .97003 17.28 7.27)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="kdxlabb_n"/><stop offset="1" class="x9_x14ckq"/></radialGradient><radialGradient id="ichV41c" cx="0" cy="0" r="1" gradientTransform="matrix(.87501 1.59375 -2.6006 1.4278 15.29 7.977)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="v2g8x4brb"/><stop offset="1" class="we0trlbug"/></radialGradient><radialGradient id="i5jAEXQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -.01563 .0588 6.46896 13.478 10.383)" gradientUnits="userSpaceOnUse"><stop class="qg0h4w_kv"/><stop offset="1" class="iich1wbqp"/></radialGradient><radialGradient id="iPvp7Je" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 21.76 4.463)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="oh3q945eb"/><stop offset="1" class="rjt1bgbei"/></radialGradient><radialGradient id="iKLWW5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.28 4.217)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="oh3q945eb"/><stop offset="1" class="rjt1bgbei"/></radialGradient><radialGradient id="iFXxeTp" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.849 3.963)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="oh3q945eb"/><stop offset="1" class="rjt1bgbei"/></radialGradient><radialGradient id="iamRwDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.02457 .47352 -.46721 -.02424 22.37 4.478)" gradientUnits="userSpaceOnUse"><stop class="as8ywhb7j"/><stop offset="1" class="fl42xnwat"/></radialGradient><radialGradient id="i1M0Jse" cx="0" cy="0" r="1" gradientTransform="matrix(3.80388 .30087 -.62375 7.88601 17.576 5.618)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="blr_nvbkl"/><stop offset="1" class="tdu8n0tza"/></radialGradient><radialGradient id="i1a10YI" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 .21242 -.56203 4.5475 14.04 9.79)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="v__i2ebru"/><stop offset="1" class="yrm14tb3b"/></radialGradient><radialGradient id="ixbTW8d" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 .51562 -1.9883 .18075 16.181 8.774)" gradientUnits="userSpaceOnUse"><stop class="hnewum4zo"/><stop offset="1" class="j297-pbqp"/></radialGradient><radialGradient id="ioPJOcd" cx="0" cy="0" r="1" gradientTransform="matrix(.34193 -.24897 .28417 .39027 16.533 5.175)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iBBZWHd" cx="0" cy="0" r="1" gradientTransform="matrix(.33968 -.62476 .36568 .19882 16.362 5.623)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iWs52ce" cx="0" cy="0" r="1" gradientTransform="matrix(.10724 .10615 -.13685 .13825 16.38 5.284)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="ij1OwGd" cx="0" cy="0" r="1" gradientTransform="matrix(.72582 0 0 1.27019 12.233 7.16)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="ikufAeZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.4009 2.58129 -3.48919 1.89363 14.507 6.206)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="izZhYJd" cx="0" cy="0" r="1" gradientTransform="rotate(-118.489 9.203 -1.89)scale(.54028 .66217)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="irr5Dld" cx="0" cy="0" r="1" gradientTransform="rotate(-118.489 8.638 -.956)scale(.57492 .71194)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iqrUWtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16322 .30827 -.18181 -.68604 17.414 7.62)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="ib6cCdd" cx="0" cy="0" r="1" gradientTransform="rotate(104.447 6.313 8.062)scale(2.02712 2.70456)" gradientUnits="userSpaceOnUse"><stop class="zx2qd4bhl"/><stop offset="1" class="y7qcqib5l"/></radialGradient><radialGradient id="iNStvhe" cx="0" cy="0" r="1" gradientTransform="rotate(61.511 2.955 14.05)scale(1.66475 3.06167)" gradientUnits="userSpaceOnUse"><stop class="j-ef6wx1p"/><stop offset="1" class="esvo74b3k"/></radialGradient><radialGradient id="iS6mcLc" cx="0" cy="0" r="1" gradientTransform="matrix(.03885 .07158 -.22996 .1248 15.084 6.743)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="ikk7zEb" cx="0" cy="0" r="1" gradientTransform="rotate(61.511 2.992 15.633)scale(.33549 .53363)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iRDfDEC" cx="0" cy="0" r="1" gradientTransform="matrix(-.14383 -.06314 .08693 -.19802 15.24 5.622)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipskdpd" cx="0" cy="0" r="1" gradientTransform="matrix(.16003 .29488 -.46904 .25455 13.72 6.407)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ifxXoXb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 10.025 -3.415)scale(.20481 .24619)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikwYf5d" cx="0" cy="0" r="1" gradientTransform="matrix(2.69744 -1.6864 6.24912 9.99563 12.523 5.85)" gradientUnits="userSpaceOnUse"><stop class="fn7-6xayh"/><stop offset="1" class="chayuvnap"/></radialGradient><radialGradient id="iiQZNBj" cx="0" cy="0" r="1" gradientTransform="matrix(-.00103 -.6172 1.09385 -.00183 15.082 4.565)" gradientUnits="userSpaceOnUse"><stop class="sylx2mbjo"/><stop offset="1" class="nav-8e2lo"/></radialGradient><radialGradient id="irqfHEe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.46686 1.16313 -1.10899 -2.35203 14.772 3.93)" gradientUnits="userSpaceOnUse"><stop class="blekadc8f"/><stop offset="1" class="c6xk9jx7z"/></radialGradient><radialGradient id="iIO2tqb" cx="0" cy="0" r="1" gradientTransform="rotate(-86.332 9.202 -3.577)scale(2.35044 3.64174)" gradientUnits="userSpaceOnUse"><stop class="jjpmu-56c"/><stop offset="1" class="ldm9khd7d"/></radialGradient><radialGradient id="iK5THde" cx="0" cy="0" r="1" gradientTransform="matrix(-.40765 -.90969 2.01156 -.90142 13.832 4.752)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o2ca957_x"/><stop offset="1" class="a7xagmxua"/></radialGradient><radialGradient id="iboQnmb" cx="0" cy="0" r="1" gradientTransform="matrix(.3249 .52408 -2.84489 1.7637 12.842 2.918)" gradientUnits="userSpaceOnUse"><stop class="uw0kegb-q"/><stop offset="1" class="ydllxhbat"/></radialGradient><linearGradient id="iyiBi5c" x1="23.013" x2="19.956" y1="5.059" y2="11.064" gradientUnits="userSpaceOnUse"><stop class="tla-kpu2g"/><stop offset=".799" class="ky2i9gfwu"/></linearGradient><linearGradient id="ijK0cnc" x1="12.493" x2="12.822" y1="9.49" y2="9.962" gradientUnits="userSpaceOnUse"><stop offset=".349" class="lr97j31fb"/><stop offset="1" class="azn0z--js"/></linearGradient><linearGradient id="ie703Bb" x1="24.916" x2="22.775" y1="3.009" y2="4.321" gradientUnits="userSpaceOnUse"><stop class="ds3hm--8v"/><stop offset="1" class="bq7w62n5j"/></linearGradient><linearGradient id="iXzXWsg" x1="23.884" x2="23.619" y1="4.009" y2="3.477" gradientUnits="userSpaceOnUse"><stop class="seeiowbir"/><stop offset="1" class="tw6dxpb7y"/></linearGradient><linearGradient id="i3Emvyc" x1="12.697" x2="12.697" y1="30.345" y2="29.673" gradientUnits="userSpaceOnUse"><stop class="dhem-xbnm"/><stop offset="1" class="zn47ozbfv"/></linearGradient><linearGradient id="i6N14Cb" x1="20.478" x2="19.884" y1="22.884" y2="22.852" gradientUnits="userSpaceOnUse"><stop class="ieaclmdnn"/><stop offset="1" class="p3yd_be1u"/></linearGradient><linearGradient id="i5WGsPc" x1="17.279" x2="17.279" y1="16.29" y2="13.102" gradientUnits="userSpaceOnUse"><stop offset=".039" class="ptputobcp"/><stop offset="1" class="br5umybnw"/></linearGradient><linearGradient id="i6rC79y" x1="16.011" x2="16.011" y1="8.673" y2="10.883" gradientUnits="userSpaceOnUse"><stop class="bw1hkxbcb"/><stop offset="1" class="tesa8u_3j"/></linearGradient><linearGradient id="i9S1RYd" x1="19.744" x2="19.744" y1="16.915" y2="27.821" gradientUnits="userSpaceOnUse"><stop class="hd06b2knh"/><stop offset="1" class="ggughpb3d"/></linearGradient><linearGradient id="iAXqFib" x1="16.306" x2="16.306" y1="18.352" y2="24.915" gradientUnits="userSpaceOnUse"><stop class="y6ovumr8k"/><stop offset="1" class="t-eeezbdl"/></linearGradient><linearGradient id="iXdsnsv" x1="16.829" x2="16.49" y1="4.833" y2="5.882" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iluzu7c" x1="12.923" x2="12.658" y1="7.275" y2="7.275" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iiy7Qrc" x1="16.192" x2="13.652" y1="5.569" y2="7.478" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="imwvtbd" x1="13.312" x2="14.104" y1="8.4" y2="7.904" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="i7Ng0Ie" x1="14.54" x2="14.881" y1="6.776" y2="6.59" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iF381Cd" x1="15.259" x2="14.883" y1="6.537" y2="6.734" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iOjVIbc" x1="15.135" x2="15.022" y1="6.954" y2="6.745" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="i7yOo0Q" x1="14.536" x2="14.758" y1="6.018" y2="6.427" gradientUnits="userSpaceOnUse"><stop class="qiq9pubtd"/><stop offset="1" class="ip7imhbjo"/></linearGradient><linearGradient id="iTJw73b" x1="15.006" x2="15.028" y1="7.783" y2="7.447" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iSU4yPe" x1="15.599" x2="15.523" y1="5.413" y2="5.545" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6IBtse" x1="14.001" x2="13.925" y1="6.28" y2="6.412" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijSglMe" x1="12.343" x2="12.164" y1="6.345" y2="6.443" gradientUnits="userSpaceOnUse"><stop class="gfuj0ibqm"/><stop offset="1" class="jhxo97b8s"/></linearGradient><linearGradient id="iZxEw0b" x1="16.039" x2="16.218" y1="4.34" y2="4.242" gradientUnits="userSpaceOnUse"><stop offset=".548" class="j9k2-bbvj"/><stop offset="1" class="mm0r6cb0n"/></linearGradient><filter id="ii2D01b" width="8.471" height="7.176" x="16.221" y="3.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.121569 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22983"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22983" result="effect2_innerShadow_3987_22983"/></filter><filter id="iJE0wWb" width="18.187" height="14.194" x="6.907" y="2.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22983"/></filter><filter id="iqCpEei" width="4.793" height="2.27" x="18.177" y="27.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.188235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22983"/></filter><filter id="inJXBnd" width="8.989" height="12.477" x="12.161" y="15.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.635294 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22983"/></filter><filter id="ip5A3ad" width="7.553" height="7.567" x="14.351" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22983"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.14902 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22983" result="effect2_innerShadow_3987_22983"/></filter><filter id="ieFCoCe" width="3.395" height="2.909" x="14.313" y="8.423" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.4 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22983"/></filter><filter id="intC61b" width="1.789" height="3.497" x="8.087" y="12.58" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22983" stdDeviation=".125"/></filter><filter id="iUpQjJd" width="2.601" height="13.601" x="18.427" y="15.427" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22983" stdDeviation=".4"/></filter><filter id="i3dgCkX" width="2.563" height="7.453" x="15.025" y="16.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22983" stdDeviation=".375"/></filter><filter id="i9MLppc" width="1.631" height="1.631" x="15.689" y="4.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22983"/></filter><filter id="i9OUWuc" width="1.823" height="1.823" x="15.468" y="4.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22983" stdDeviation=".25"/></filter><filter id="i2fu2mJ" width="1.581" height="1.381" x="12.232" y="6.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22983"/></filter><filter id="iYOPNnF" width="1.823" height="1.823" x="12.011" y="6.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22983" stdDeviation=".25"/></filter><filter id="i1Xdmpc" width="2.237" height="2.609" x="13.765" y="5.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22983" stdDeviation=".375"/></filter><filter id="iNAMlzc" width="1.077" height="1.301" x="14.349" y="5.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22983" stdDeviation=".05"/></filter><filter id="i2TNvnd" width=".373" height=".466" x="14.972" y="5.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22983" stdDeviation=".05"/></filter><filter id="i4sbNGc" width=".614" height=".615" x="15.24" y="5.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22983" stdDeviation=".1"/></filter><filter id="i0zeZ1c" width=".665" height=".656" x="13.612" y="6.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22983" stdDeviation=".1"/></filter><filter id="iOLnOjI" width=".425" height=".484" x="13.39" y="6.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22983" stdDeviation=".05"/></filter><filter id="ilGd7Xb" width="1.33" height=".972" x="14.533" y="4.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22983"/></filter><filter id="if1hRPs" width="1.157" height="1.278" x="12.757" y="4.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22983"/></filter><filter id="irFCGEd" width="4.054" height="2.494" x="11.947" y="3.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.396078 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22983"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-golfing-dark" /></template>
<style>
.a0mesmzaf {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M13.545 5.733c-.275.118-.387.311-.408.37a.195.195 0 0 1-.37-.126c.056-.163.246-.441.624-.603a.195.195 0 1 1 .154.36");
}

.a3kzqdbbr {
  width: 0.692px;
  height: 1.157px;
  x: 22.173px;
  y: 3.295px;
  rx: 0.346px;
}

.a7xagmxua {
  stop-color: var(--svg-color--1a7ccc, #1A7CCC);
  stop-opacity: 0;
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.aq2ig4h0o {
  cx: 16.379px;
  cy: 5.284px;
  r: 0.69px;
}

.as8ywhb7j {
  stop-color: var(--svg-color--5f5150, #5F5150);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.azn0z--js {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
  stop-opacity: 0;
}

.b9lnu1iwb {
  width: 0.692px;
  height: 1.157px;
  x: 21.603px;
  y: 3.549px;
  rx: 0.346px;
}

.ba1yb3bji {
  stop-color: var(--svg-color--a99797, #A99797);
}

.ben4f0bqs {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
  stop-opacity: 0;
}

.blekadc8f {
  stop-color: var(--svg-color--30a2e5, #30A2E5);
}

.blr_nvbkl {
  stop-color: var(--svg-color--645351, #645351);
  stop-opacity: 0;
}

.bnzv-4xpp {
  d: path("m14.452 6.196l.143.722c.03.149.193.224.327.152l.285-.155a.224.224 0 0 0 .052-.357l-.529-.513c-.115-.115-.309-.01-.278.15");
}

.bq7w62n5j {
  stop-color: var(--svg-color--482a5b, #482A5B);
}

.br5umybnw {
  stop-color: var(--svg-color--366bc5, #366BC5);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bw1hkxbcb {
  stop-color: var(--svg-color--2d9de0, #2D9DE0);
}

.c1-0b4bsg {
  cx: 16.379px;
  cy: 5.284px;
  r: 0.412px;
}

.c6xk9jx7z {
  stop-color: var(--svg-color--1b96dc, #1B96DC);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.chayuvnap {
  stop-color: var(--svg-color--1d78b8, #1D78B8);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnoiw-b7a {
  d: path("M15.211 5.373a.37.37 0 0 1 .535.24l-.626.34a.37.37 0 0 1 .091-.58");
}

.ddjhanboc {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
}

.dhem-xbnm {
  stop-color: var(--svg-color--442563, #442563);
}

.dp5vh--ol {
  d: path("M8.948 12.907a.35.35 0 0 0-.125.474l.88 1.545a1 1 0 0 1-.373 1.364l-.115.065a1 1 0 0 1-1.364-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.25l.343-.196L24.386 2.55a.4.4 0 0 1 .549.14l.102.171a.4.4 0 0 1-.14.549z");
}

.ds3hm--8v {
  stop-color: var(--svg-color--533d66, #533D66);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dsumrvbgt {
  stop-color: var(--svg-color--615273, #615273);
  stop-opacity: 0;
}

.duukh4bkh {
  width: 0.692px;
  height: 1.157px;
  x: 20.651px;
  y: 4.055px;
  fill: var(--svg-color--3b2926, #3B2926);
  rx: 0.346px;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.ebs2-pbbe {
  stop-color: var(--svg-color--9c8cad, #9C8CAD);
  stop-opacity: 0;
}

.epem68pfv {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M14.837 5.032c.248-.167.472-.156.533-.14a.195.195 0 0 0 .095-.379c-.167-.042-.504-.035-.845.194a.195.195 0 0 0 .217.325");
}

.esvo74b3k {
  stop-color: var(--svg-color--2b1c2e, #2B1C2E);
  stop-opacity: 0;
}

.f4zimzw3l {
  d: path("M19.317 6.008a.5.5 0 0 0-.015-.253a5 5 0 0 0-.227-.524c-.02-.088-.025-.29.11-.39a.36.36 0 0 1 .336-.055a.45.45 0 0 1 .207-.285c.134-.072.298-.03.363 0c.018-.067.09-.209.23-.246a.52.52 0 0 1 .356.058c.04-.075.169-.224.36-.215c.238.012.374.262.41.45c.035.187.093.433.152.578s.117.605-.09 1.199h-.001c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.083a1.1 1.1 0 1 1-.193-2.192c.636-.056 1.522-.243 2.304-.744c.683-.436 1.327-1.135 1.66-2.317");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fl42xnwat {
  stop-color: var(--svg-color--3e2221, #3E2221);
}

.fn7-6xayh {
  stop-color: var(--svg-color--3e82bc, #3E82BC);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fts5n54lg {
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("m19.822 16.634l-.188 11.187");
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.ggughpb3d {
  stop-color: var(--svg-color--a599b3, #A599B3);
}

.gmmtdnb-k {
  fill-rule: evenodd;
  d: path("M20.961 7.797c.852-1.082.481-2.213.22-2.677l1.915-1.082c.467.828 1.242 3.027-.406 5.12c-.89 1.13-2.33 1.567-3.484 1.753c-1.198.193-2.37.158-2.985.134l.084-2.198c.599.023 1.583.048 2.55-.108c1.012-.164 1.746-.485 2.106-.942");
}

.gt2iksbiy {
  fill: var(--svg-color--4c3765, #4C3765);
  d: path("M18.177 30.196v-1.77h2.16c.164.157.79.551 1.504.782c.494.131.625.488.63.62v.368z");
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.h8hiq33uv {
  stop-color: var(--svg-color--271938, #271938);
  stop-opacity: 0;
}

.hd06b2knh {
  stop-color: var(--svg-color--a89eb3, #A89EB3);
}

.hnewum4zo {
  stop-color: var(--svg-color--2f89b9, #2F89B9);
}

.i42zc8m6u {
  stop-color: var(--svg-color--615273, #615273);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.ieaclmdnn {
  stop-color: var(--svg-color--a19ca8, #A19CA8);
}

.iich1wbqp {
  stop-color: var(--svg-color--56a2e0, #56A2E0);
  stop-opacity: 0;
}

.ilg8l_bzj {
  stop-color: var(--svg-color--655e6d, #655E6D);
}

.in-vfpgwh {
  stop-color: var(--svg-color--403451, #403451);
  stop-opacity: 0;
}

.ip7imhbjo {
  stop-color: var(--svg-color--432c2e, #432C2E);
  stop-opacity: 0;
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.j_l_30buh {
  stop-color: var(--svg-color--5d5467, #5D5467);
}

.j-ef6wx1p {
  stop-color: var(--svg-color--2b1c2e, #2B1C2E);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j231iobwp {
  cx: 12.923px;
  cy: 7.16px;
  r: 0.412px;
}

.j297-pbqp {
  stop-color: var(--svg-color--2f89b9, #2F89B9);
  stop-opacity: 0;
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.j9k2-bbvj {
  stop-color: var(--svg-color--252224, #252224);
}

.jhxo97b8s {
  stop-color: var(--svg-color--463f3d, #463F3D);
}

.jjpmu-56c {
  stop-color: var(--svg-color--4199e0, #4199E0);
}

.jms61nr7p {
  fill: var(--svg-color--000, #000);
  d: path("M15.202 5.798a.21.21 0 0 1 .085-.287a.21.21 0 0 1 .312.182l-.329.178a.2.2 0 0 1-.068-.073");
}

.k2_no2-ti {
  fill: var(--svg-color--47385d, #47385D);
  d: path("M11.595 27.805c0-.806.458-1.158.688-1.234l1.367 1.18v1.283a.5.5 0 0 0 .187.39l.203.163c.128.093.297.238.25.414c-.082.172-.25.195-.539.195h-1.506a.65.65 0 0 1-.65-.65z");
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kdxlabb_n {
  stop-color: var(--svg-color--3090bc, #3090BC);
}

.keljo6scd {
  stop-color: var(--svg-color--827a8b, #827A8B);
}

.kgrhzo17p {
  stop-color: var(--svg-color--a99797, #A99797);
  stop-opacity: 0;
}

.kimgmsbzt {
  d: path("M16.001 8.887c.328-.03.652-.125.848-.214l.86 2.195c-.235.121-1.716.594-2.54.43c-.824-.165-1.02-1.196-.73-1.739c.273-.609 1.118-.63 1.562-.672");
}

.kxzgmzb5t {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
}

.ky2i9gfwu {
  stop-color: var(--svg-color--422628, #422628);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldm9khd7d {
  stop-color: var(--svg-color--4199e0, #4199E0);
  stop-opacity: 0;
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmyw-ob7g {
  d: path("m12.35 6.784l-.462-.852l.434-.236c.01.06.021.21-.018.335a.5.5 0 0 0 .05.352l.274.506c-.098.052-.22.014-.278-.105");
}

.lr97j31fb {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lyogqkadi {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.226 5.453c.04.019.012.083-.021.154s-.058.122-.098.104s-.046-.091-.013-.162c.032-.072.091-.114.132-.096");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbn2kyb-e {
  d: path("M13.927 9.852c.176-1.285.703-1.862 1-2.07c.51-.358 1.664-.945 3.336 0c1.758 1.094 2.404 4.057 2.375 5.375v2.805h-6V12.72c0-.488-.105-.743-.258-.962c-.144-.257-.52-.98-.453-1.906");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mlryu5b4g {
  width: 0.737px;
  height: 1.252px;
  x: 21.976px;
  y: 4.326px;
  rx: 0.369px;
}

.mm0r6cb0n {
  stop-color: var(--svg-color--5b5a5a, #5B5A5A);
}

.mrhht-dbj {
  d: path("m16.15 23.571l-.375-5.953l1.062.5v5.453z");
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n1k33obob {
  d: path("M14.078 6.36c-.057-.106-.181-.13-.216-.138l-.05.159l.136.097z");
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.nav-8e2lo {
  stop-color: var(--svg-color--3386c4, #3386C4);
  stop-opacity: 0;
}

.njmjl6b2j {
  d: path("M15.226 5.453c.04.019.012.083-.021.154s-.058.122-.098.104s-.046-.091-.013-.162c.032-.072.091-.114.132-.096");
}

.no0_3dbdi {
  stop-color: var(--svg-color--53aff7, #53AFF7);
}

.no3flhbcy {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m14.452 6.196l.143.722c.03.149.193.224.327.152l.285-.155a.224.224 0 0 0 .052-.357l-.529-.513c-.115-.115-.309-.01-.278.15");
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.np5o-2bpn {
  cx: 13.602px;
  cy: 6.425px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.161px;
  ry: 0.082px;
}

.nwl71xhuy {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.233 5.233a.58.58 0 0 1 .701.118a.113.113 0 0 1-.03.176l-.81.44a.095.095 0 0 1-.137-.053a.58.58 0 0 1 .276-.68");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o2ca957_x {
  stop-color: var(--svg-color--1a7ccc, #1A7CCC);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.oa1gztksx {
  fill: var(--svg-color--000, #000);
  d: path("M13.987 6.457a.21.21 0 0 0-.287-.085a.21.21 0 0 0-.018.361l.329-.178a.2.2 0 0 0-.024-.098");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh3q945eb {
  stop-color: var(--svg-color--5e4f4d, #5E4F4D);
}

.p32z24bkw {
  d: path("M13.625 6.234a.37.37 0 0 0-.09.58l.626-.34a.372.372 0 0 0-.537-.24");
}

.p3yd_be1u {
  stop-color: var(--svg-color--a49faa, #A49FAA);
  stop-opacity: 0;
}

.p7fla-b3y {
  width: 0.692px;
  height: 1.157px;
  x: 21.084px;
  y: 3.795px;
  rx: 0.346px;
}

.pcvpzjboo {
  stop-color: var(--svg-color--937da8, #937DA8);
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ps4m-ab9c {
  stop-color: var(--svg-color--827a8b, #827A8B);
  stop-opacity: 0;
}

.ptputobcp {
  stop-color: var(--svg-color--366bc5, #366BC5);
}

.qe_2d-buv {
  stop-color: var(--svg-color--937da8, #937DA8);
  stop-opacity: 0;
}

.qg0h4w_kv {
  stop-color: var(--svg-color--56a2e0, #56A2E0);
}

.qiq9pubtd {
  stop-color: var(--svg-color--432c2e, #432C2E);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qy03eqbwm {
  d: path("M13.26 2.714c.522-.283 1.107-.399 1.65-.186c.418.163.857.644 1.09 1.316a2.9 2.9 0 0 0-.944-.103a3.62 3.62 0 0 0-2.682 1.455a2.8 2.8 0 0 0-.428.848c-.438-.565-.6-1.192-.509-1.631c.118-.571.534-1 1.056-1.283z");
}

.rjt1bgbei {
  stop-color: var(--svg-color--402527, #402527);
}

.s2j02zbkr {
  stop-color: var(--svg-color--655e6d, #655E6D);
  stop-opacity: 0;
}

.seeiowbir {
  stop-color: var(--svg-color--482c58, #482C58);
}

.smfideibo {
  d: path("m21.765 5.274l-.5-.866l3.122-1.859a.4.4 0 0 1 .548.14l.102.171a.4.4 0 0 1-.139.549z");
}

.srbjw6b9u {
  fill: var(--svg-color--452d2b, #452D2B);
  d: path("M19.317 6.008a.5.5 0 0 0-.015-.253a5 5 0 0 0-.227-.524c-.02-.088-.025-.29.11-.39a.36.36 0 0 1 .336-.055a.45.45 0 0 1 .207-.285c.134-.072.298-.03.363 0c.018-.067.09-.209.23-.246a.52.52 0 0 1 .356.058c.04-.075.169-.224.36-.215c.238.012.374.262.41.45c.035.187.093.433.152.578s.117.605-.09 1.199h-.001c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.083a1.1 1.1 0 1 1-.193-2.192c.636-.056 1.522-.243 2.304-.744c.683-.436 1.327-1.135 1.66-2.317");
}

.sylx2mbjo {
  stop-color: var(--svg-color--3386c4, #3386C4);
}

.syrcgtb4c {
  fill: var(--svg-color--332024, #332024);
  d: path("m14.524 6.234l.037.78c.032.147.19.225.315.157l.268-.145c.126-.068.145-.246.04-.35l-.517-.52c-.113-.116-.177-.081-.143.078");
}

.t-eeezbdl {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
  stop-opacity: 0;
}

.t7l4d-tey {
  cx: 13.602px;
  cy: 6.425px;
  rx: 0.161px;
  ry: 0.082px;
}

.tdu8n0tza {
  stop-color: var(--svg-color--645351, #645351);
}

.tesa8u_3j {
  stop-color: var(--svg-color--3083ea, #3083EA);
}

.tla-kpu2g {
  stop-color: var(--svg-color--452d30, #452D30);
}

.truekjbvb {
  stop-color: var(--svg-color--347fda, #347FDA);
}

.tw6dxpb7y {
  stop-color: var(--svg-color--482c58, #482C58);
  stop-opacity: 0;
}

.u74slacjt {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.696 7.465a1.2 1.2 0 0 0 .545-.148a1.2 1.2 0 0 0 .421-.377a.114.114 0 0 1 .129-.045c.044.014.08.056.075.115m-1.17.455l1.12-.46m-1.12.46a.11.11 0 0 0-.108.084a.11.11 0 0 0 .055.125m.053-.21l-.03.166m1.2-.62l-.05-.005m.05.005l-.05-.005m.05.005a.83.83 0 0 1-.434.659a.83.83 0 0 1-.79.005m1.175-.669a.78.78 0 0 1-.409.62a.78.78 0 0 1-.742.005m-.023.044l.023-.044m-.023.044l.023-.044");
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.uu7_gub8n {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
  stop-opacity: 0;
}

.uw0kegb-q {
  stop-color: var(--svg-color--4195cb, #4195CB);
}

.v__i2ebru {
  stop-color: var(--svg-color--579fde, #579FDE);
}

.v2g8x4brb {
  stop-color: var(--svg-color--246c9d, #246C9D);
}

.v30w_lair {
  d: path("M14.522 23.964a1 1 0 0 0 .275-.712l-.167-7.29h6.02l-.312 12.476H18.18l-.259-10.002a.255.255 0 0 0-.509-.004c-.049 1.195-.13 3.454-.13 4.584c0 1.213-.693 2.214-1.04 2.563l-2.472 2.287a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.718-.424c-.252-.225-.439-.553-.547-.795a.36.36 0 0 1 .078-.392z");
}

.vkrof_bbk {
  stop-color: var(--svg-color--271938, #271938);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w5cnt0b9d {
  d: path("M11.595 27.805c0-.806.458-1.158.688-1.234l1.367 1.18v1.283a.5.5 0 0 0 .187.39l.203.163c.128.093.297.238.25.414c-.082.172-.25.195-.539.195h-1.506a.65.65 0 0 1-.65-.65z");
}

.w5oxhdc5r {
  stop-color: var(--svg-color--7f5d9d, #7F5D9D);
}

.wbfx56k9g {
  cx: 12.923px;
  cy: 7.16px;
  r: 0.69px;
}

.we0trlbug {
  stop-color: var(--svg-color--246c9d, #246C9D);
  stop-opacity: 0;
}

.whyx-x2rb {
  fill: var(--svg-color--9785a9, #9785A9);
  d: path("M14.522 23.964a1 1 0 0 0 .275-.712l-.167-7.29h6.02l-.312 12.476H18.18l-.259-10.002a.255.255 0 0 0-.509-.004c-.049 1.195-.13 3.454-.13 4.584c0 1.213-.693 2.214-1.04 2.563l-2.472 2.287a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.718-.424c-.252-.225-.439-.553-.547-.795a.36.36 0 0 1 .078-.392z");
}

.wkyu36bsz {
  stroke: var(--svg-color--c3b8c3, #C3B8C3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.51 12.93a.53.53 0 0 0 0 .54c.13.237.718 1.277.96 1.714c.05.103.111.356-.039.543");
}

.wn-t5ndzy {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
}

.x1g0b-w7w {
  d: path("M15.654 5.498a.35.35 0 0 0-.176-.123l-.038.155l.088.06z");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x9_x14ckq {
  stop-color: var(--svg-color--3090bc, #3090BC);
  stop-opacity: 0;
}

.xdr4qbcbn {
  d: path("m16.402 4.584l-.462-.851l-.434.236a.8.8 0 0 0 .29.167a.5.5 0 0 1 .269.233l.257.515a.216.216 0 0 0 .08-.3");
}

.xhu8yhbcw {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
  stop-opacity: 0;
}

.xi8fv135v {
  stop-color: var(--svg-color--8c7e97, #8C7E97);
  stop-opacity: 0;
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y5b7-3icb {
  d: path("M12.357 6.436c-.178-.329-.254-.748-.433-1.078c-.179-.329 2.866-2.094 3.59-1.882c.251.03.56.839.627.998c.287.686.625 1.355.935 2.031c.29.675.028 1.397-.574 1.724l-1.167.633c-.622.337-1.35.153-1.758-.458c-.407-.63-.862-1.308-1.22-1.968");
}

.y6ovumr8k {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
}

.y7qcqib5l {
  stop-color: var(--svg-color--5a4340, #5A4340);
  stop-opacity: 0;
}

.ydllxhbat {
  stop-color: var(--svg-color--4195cb, #4195CB);
  stop-opacity: 0;
}

.yh77kabjp {
  cx: 16.379px;
  cy: 5.284px;
  r: 0.412px;
  fill: var(--svg-color--463133, #463133);
}

.ynlfw99ba {
  stop-color: var(--svg-color--403451, #403451);
}

.yp23hxdko {
  d: path("M12.375 5.196a2.8 2.8 0 0 0-.428.848l.249.104a.42.42 0 0 0 .514-.161c.193-.302.57-.775 1.22-1.128a3.3 3.3 0 0 1 1.61-.408a.41.41 0 0 0 .412-.341l.049-.266a2.9 2.9 0 0 0-.944-.103a3.62 3.62 0 0 0-2.683 1.455");
}

.yrm14tb3b {
  stop-color: var(--svg-color--579fde, #579FDE);
  stop-opacity: 0;
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z6kjlwv6e {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.496 6.176a.58.58 0 0 0-.283.652c.018.072.1.106.164.07l.811-.44a.095.095 0 0 0 .03-.143a.58.58 0 0 0-.722-.14");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zhvkip9xc {
  fill: var(--svg-color--afa2b8, #AFA2B8);
  d: path("M8.948 12.907a.35.35 0 0 0-.125.474l.88 1.545a1 1 0 0 1-.373 1.364l-.115.065a1 1 0 0 1-1.364-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.25l.343-.196L24.386 2.55a.4.4 0 0 1 .549.14l.102.171a.4.4 0 0 1-.14.549z");
}

.zn47ozbfv {
  stop-color: var(--svg-color--442563, #442563);
  stop-opacity: 0;
}

.zx2qd4bhl {
  stop-color: var(--svg-color--5a4340, #5A4340);
}

</style>
