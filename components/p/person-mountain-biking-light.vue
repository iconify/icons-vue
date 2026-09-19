<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLRYhtb)"><path fill="url(#imFdBxd)" class="m2hzjbyuc"/><path fill="url(#i1mHagd)" class="m2hzjbyuc"/></g><g filter="url(#iuU2NJd)"><path fill="url(#iAlBXgd)" class="rj3xdun2l"/></g><path fill="url(#imlGzRc)" class="rj3xdun2l"/><g filter="url(#ioDDbbc)"><path class="rknt09byu"/><path fill="url(#iTtKmlb)" class="z5z2pubmg"/></g><g filter="url(#ien906c)"><path fill="url(#iBVNdPB)" clip-rule="evenodd" class="ue1cg0jtk"/></g><g filter="url(#iJEqZKd)"><circle stroke="url(#iMqUPPc)" class="f2dg1pymm"/></g><path fill="url(#iYNxjOc)" class="hk_2rww3p"/><path class="sidw1obfr"/><path fill="url(#iAUidTI)" class="g7aqyha-f"/><path fill="url(#ipimVNe)" class="g7aqyha-f"/><path fill="url(#ikI6zud)" clip-rule="evenodd" class="mvvhg6bob"/><path fill="url(#ioqA6Ec)" clip-rule="evenodd" class="mvvhg6bob"/><path fill="url(#iByKjmc)" clip-rule="evenodd" class="fuvqv0efx"/><path fill="url(#ilystOc)" clip-rule="evenodd" class="g8r6p49_s"/><path fill="url(#isottie)" clip-rule="evenodd" class="g8r6p49_s"/><g filter="url(#i4QzKzc)"><path fill="url(#iXjYTba)" clip-rule="evenodd" class="pfbx1ib6q"/><path fill="url(#iWYSLge)" clip-rule="evenodd" class="pfbx1ib6q"/></g><path fill="url(#iDeh7Jb)" clip-rule="evenodd" class="nrp3vkbjq"/><path fill="url(#i7VZLSd)" clip-rule="evenodd" class="wjs_nsbuh"/><path fill="url(#iAoLEke)" clip-rule="evenodd" class="wjs_nsbuh"/><path fill="url(#iX1cArb)" clip-rule="evenodd" class="wjs_nsbuh"/><path fill="url(#iJaVwYc)" class="b3q5ubbch"/><path fill="url(#i7cXxOe)" class="b3q5ubbch"/><path fill="url(#i5ctrhH)" class="b3q5ubbch"/><path fill="url(#i8GpRbG)" class="h-r_c9b7x"/><path fill="url(#iqttsuc)" class="h-r_c9b7x"/><g filter="url(#iV1xYqe)"><path fill="url(#iv0gtpe)" class="wm4p2nf6o"/><path fill="url(#iUb7kZR)" class="wm4p2nf6o"/></g><circle fill="url(#iliKE4b)" class="rrfczgbhc"/><circle fill="url(#iNgFFMe)" class="rrfczgbhc"/><g filter="url(#isMfPOe)"><path class="hz6yw06qq"/><path fill="url(#iQhym4p)" class="um4kzybeo"/><path fill="url(#iCW6Pzb)" class="um4kzybeo"/></g><path fill="url(#icrPDJi)" transform="rotate(-55.397 13.554 7.913)" class="czabn_xgs"/><path fill="url(#ism98nc)" transform="rotate(-55.397 13.554 7.913)" class="czabn_xgs"/><g filter="url(#id5gW8c)"><path fill="url(#iBXRDpd)" class="o0tyh0b-k"/><path fill="url(#inGQSHc)" class="o0tyh0b-k"/></g><g filter="url(#is36ucd)"><path fill="url(#iLd5sqb)" class="e_--_59xk"/><path fill="url(#iATYDXc)" class="e_--_59xk"/></g><g filter="url(#i3GYEBM)"><path fill="url(#iTbdw3c)" class="hla563ezk"/></g><g filter="url(#iNtZmBB)"><path class="pzip1rpvk"/><path fill="url(#i0P2tWc)" class="iy0i0xbqt"/></g><g filter="url(#iojA1ue)"><path clip-rule="evenodd" class="u3_kb5fuo"/></g><g filter="url(#iaI35pe)"><path clip-rule="evenodd" class="z140-2b1b"/><path fill="url(#inMqOXb)" clip-rule="evenodd" class="cpzd76x5u"/></g><path fill="url(#i0s27me)" clip-rule="evenodd" class="s2qrn4tqf"/><path fill="url(#intKVPb)" clip-rule="evenodd" class="s2qrn4tqf"/><g filter="url(#iQUjkmc)"><path fill="url(#iYiWRhd)" class="qc8cprh-k"/></g><path fill="url(#imHztos)" clip-rule="evenodd" class="pypniyb9c"/><path fill="url(#i7p9Vrc)" clip-rule="evenodd" class="pypniyb9c"/><path fill="url(#iKi6aoE)" clip-rule="evenodd" class="mx2mcdbpf"/><path fill="url(#iDURrje)" clip-rule="evenodd" class="mx2mcdbpf"/><g filter="url(#ioViyMc)"><circle class="vlgj1odqb"/></g><path fill="url(#ivA23Hc)" class="yozietovn"/><g filter="url(#ihuyTEc)"><path fill="url(#iNOTUAc)" class="npgm2vb6k"/><path fill="url(#iUfkemd)" class="npgm2vb6k"/><path fill="url(#iJfcGfb)" class="npgm2vb6k"/><path fill="url(#iow5L4c)" class="npgm2vb6k"/></g><path clip-rule="evenodd" class="ibpqkjjwa"/><g filter="url(#iRrf0Le)"><path class="x8yh06lcj"/><path fill="url(#i5SVlRc)" class="zfr_gp_ns"/></g><path class="gfge3-bpx"/><path class="l084ily_a"/><path fill="url(#iWw2H8d)" class="t51spjdji"/><circle transform="rotate(-64.992 11.086 6.871)" class="v911bvqyx"/><circle fill="url(#iwjr5Zd)" transform="rotate(-64.992 13.447 5.77)" class="dks8srluc"/><circle fill="url(#iKD8Zye)" transform="rotate(-64.992 13.447 5.77)" class="dks8srluc"/><path clip-rule="evenodd" class="ea3nwpb8j"/><path fill="url(#iNWakNd)" clip-rule="evenodd" class="j2lckmjxn"/><path fill="url(#i7LqO5O)" clip-rule="evenodd" class="j2lckmjxn"/><path fill="url(#i9OB2kd)" clip-rule="evenodd" class="j2lckmjxn"/><g filter="url(#i1PeLid)"><path fill="url(#irGb8te)" class="bks5srb3y"/></g><g filter="url(#i5nKIMd)"><path fill="url(#iqhu6Vd)" class="b9ukjpb0p"/></g><defs><radialGradient id="imlGzRc" cx="0" cy="0" r="1" gradientTransform="rotate(150.331 11.813 6.023)scale(3.70975 8.36641)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="l4_q8ccja"/><stop offset="1" class="fy0gg3b4w"/></radialGradient><radialGradient id="iTtKmlb" cx="0" cy="0" r="1" gradientTransform="matrix(4.42529 4.18325 -2.33905 2.47438 19.748 26.757)" gradientUnits="userSpaceOnUse"><stop class="qfj7itbso"/><stop offset="1" class="p1dkvx0ja"/></radialGradient><radialGradient id="iBVNdPB" cx="0" cy="0" r="1" gradientTransform="rotate(126.943 -.1 13.106)scale(9.77501 9.43553)" gradientUnits="userSpaceOnUse"><stop class="y16t4y92n"/><stop offset="1" class="hqorccbwh"/></radialGradient><radialGradient id="ipimVNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53127 2.45312 -.44454 -.27749 20.346 20.953)" gradientUnits="userSpaceOnUse"><stop class="m3q9izqvj"/><stop offset="1" class="gxtng2bih"/></radialGradient><radialGradient id="ioqA6Ec" cx="0" cy="0" r="1" gradientTransform="rotate(-68.026 17.608 .423)scale(2.88119 .32513)" gradientUnits="userSpaceOnUse"><stop class="f-r3ld20z"/><stop offset="1" class="qnv5cwbcc"/></radialGradient><radialGradient id="ilystOc" cx="0" cy="0" r="1" gradientTransform="matrix(6.71875 4.82813 -1.31599 1.83131 10.22 18.516)" gradientUnits="userSpaceOnUse"><stop class="zo6cprbov"/><stop offset="1" class="cc9670aeb"/></radialGradient><radialGradient id="iXjYTba" cx="0" cy="0" r="1" gradientTransform="rotate(134.451 10.034 17.078)scale(9.80603 9.46548)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="msqk4cb8o"/><stop offset="1" class="wc0bxtmli"/></radialGradient><radialGradient id="iAoLEke" cx="0" cy="0" r="1" gradientTransform="rotate(103.707 3.238 16.627)scale(4.61583 .44083)" gradientUnits="userSpaceOnUse"><stop class="rgol9fpyb"/><stop offset="1" class="jk5eocp2v"/></radialGradient><radialGradient id="iX1cArb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.0625 1.65481 -.04867 18.502 23.75)" gradientUnits="userSpaceOnUse"><stop class="d-6jagb2y"/><stop offset="1" class="zd8v8x_xx"/></radialGradient><radialGradient id="iJaVwYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.28125 3.99268 -5.05379 -.356 15.415 15.187)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="hwlgdac9v"/><stop offset=".868" class="o83duvb6p"/></radialGradient><radialGradient id="i7cXxOe" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .45313 -.35 .94138 15.783 17.156)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="t0xl0mbii"/><stop offset="1" class="d9lnsac_l"/></radialGradient><radialGradient id="i5ctrhH" cx="0" cy="0" r="1" gradientTransform="rotate(-167.255 8.833 7.73)scale(2.69131 3.58612)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="brfhj2bpt"/><stop offset="1" class="p0n-v6bwi"/><stop offset="1" class="yt4h0-bzj"/></radialGradient><radialGradient id="i8GpRbG" cx="0" cy="0" r="1" gradientTransform="rotate(143.881 6.994 9.938)scale(2.86275 1.23215)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="o5ujuoler"/><stop offset="1" class="cvi6_hb_e"/></radialGradient><radialGradient id="iUb7kZR" cx="0" cy="0" r="1" gradientTransform="matrix(-.86719 0 0 -.96875 25.62 24.813)" gradientUnits="userSpaceOnUse"><stop class="nus19y6ts"/><stop offset="1" class="aiqsdtepb"/></radialGradient><radialGradient id="iliKE4b" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 -.65625 .66797 1.5904 17.72 25.172)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="v5ts0ibjo"/><stop offset="1" class="huz3s4d_a"/></radialGradient><radialGradient id="iNgFFMe" cx="0" cy="0" r="1" gradientTransform="rotate(151.189 6.29 14.782)scale(1.78324)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="da9xf6l5p"/><stop offset="1" class="cbgow0bwo"/></radialGradient><radialGradient id="iCW6Pzb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1094 -2 6.41983 -3.56106 16.3 25.516)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="egxex7b7c"/><stop offset=".943" class="hs-_dnasa"/></radialGradient><radialGradient id="ism98nc" cx="0" cy="0" r="1" gradientTransform="matrix(.03133 1.4211 -.52543 .01158 14.98 8.897)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="gcjq1zqgn"/><stop offset="1" class="aflx5ac8k"/></radialGradient><radialGradient id="iBXRDpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 -8.78125 2.52881 -.21598 17.94 23.906)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="iqlq1pbje"/><stop offset="1" class="o2gu83zjq"/></radialGradient><radialGradient id="inGQSHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6875 .0625 -.11168 -3.01554 18.846 17.625)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="slryrmbbo"/><stop offset="1" class="dpi-7sbrv"/></radialGradient><radialGradient id="iLd5sqb" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -4.9297 2.6132 2.71672 16.815 15.531)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="zwrak1b2j"/><stop offset="1" class="zvme7yb8w"/></radialGradient><radialGradient id="iATYDXc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -.09375 .01804 .49916 18.237 13.813)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="aw4amab0f"/><stop offset="1" class="jqhw67baa"/></radialGradient><radialGradient id="iTbdw3c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.49999 -4.06251 1.70908 -1.47243 21.127 11.5)" gradientUnits="userSpaceOnUse"><stop class="sc_kwfbiq"/><stop offset="1" class="cj8r45ujx"/></radialGradient><radialGradient id="i0P2tWc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25232 0 0 1.29925 10.078 12.938)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="qktpib9mi"/><stop offset="1" class="ms8ncfh9g"/></radialGradient><radialGradient id="inMqOXb" cx="0" cy="0" r="1" gradientTransform="rotate(158.559 7.971 6.041)scale(1.11134 1.23837)" gradientUnits="userSpaceOnUse"><stop class="fze29cbbv"/><stop offset="1" class="mp1bj4bkr"/><stop offset="1" class="af2e8qwjk"/></radialGradient><radialGradient id="i0s27me" cx="0" cy="0" r="1" gradientTransform="matrix(1.70877 .92892 -1.02417 1.884 7.029 12.767)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="fqxr12j4i"/><stop offset="1" class="j9bmo4yzb"/></radialGradient><radialGradient id="intKVPb" cx="0" cy="0" r="1" gradientTransform="rotate(-169.577 4.854 6.554)scale(1.33255 2.06198)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="xal9k3bum"/><stop offset="1" class="p_o38mbkb"/></radialGradient><radialGradient id="iYiWRhd" cx="0" cy="0" r="1" gradientTransform="matrix(5.5 -1.4375 2.00475 7.67032 17.377 14.688)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f6rwhfb_k"/><stop offset=".905" class="aw8cj7bar"/></radialGradient><radialGradient id="imHztos" cx="0" cy="0" r="1" gradientTransform="matrix(1.04759 .75841 -1.02541 1.4164 7.404 13.45)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="fqxr12j4i"/><stop offset="1" class="j9bmo4yzb"/></radialGradient><radialGradient id="i7p9Vrc" cx="0" cy="0" r="1" gradientTransform="rotate(-167.973 4.888 6.752)scale(.83427 1.78585)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="xal9k3bum"/><stop offset="1" class="p_o38mbkb"/></radialGradient><radialGradient id="iKi6aoE" cx="0" cy="0" r="1" gradientTransform="matrix(1.01589 .59884 -.82449 1.39869 7.737 13.758)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="fqxr12j4i"/><stop offset="1" class="j9bmo4yzb"/></radialGradient><radialGradient id="iDURrje" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 -.07813 .17332 -1.6638 8.598 14.53)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="xal9k3bum"/><stop offset="1" class="p_o38mbkb"/></radialGradient><radialGradient id="ivA23Hc" cx="0" cy="0" r="1" gradientTransform="matrix(.67465 .4547 -.3568 .5294 10.77 7.747)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="jxqufcbzg"/><stop offset="1" class="cuptu7i6i"/></radialGradient><radialGradient id="iNOTUAc" cx="0" cy="0" r="1" gradientTransform="matrix(3.1322 -1.19524 1.23966 3.24861 11.53 7.862)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="tnn6d9lnt"/><stop offset="1" class="w0i7s3bkp"/></radialGradient><radialGradient id="iUfkemd" cx="0" cy="0" r="1" gradientTransform="rotate(54.276 1.591 15.23)scale(1.93173 1.55877)" gradientUnits="userSpaceOnUse"><stop class="ur7lpnbek"/><stop offset="1" class="ja_424b_z"/></radialGradient><radialGradient id="iJfcGfb" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 3.25 -3.86524 .9663 12.415 6.458)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="byihu8b7s"/><stop offset="1" class="x91_06blc"/></radialGradient><radialGradient id="iow5L4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.84374 1.9375 -2.02084 -.88003 14.603 5.895)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="hihpobcpj"/><stop offset="1" class="vn5o04bza"/></radialGradient><radialGradient id="i5SVlRc" cx="0" cy="0" r="1" gradientTransform="rotate(154.691 6.984 4.578)scale(1.16004 .36852)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jsa0_reur"/><stop offset="1" class="l-nb061ot"/></radialGradient><radialGradient id="iwjr5Zd" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 3.607 10.299)scale(.96789)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="dhib36bjr"/><stop offset="1" class="uucs6l1bh"/></radialGradient><radialGradient id="iKD8Zye" cx="0" cy="0" r="1" gradientTransform="rotate(-142.244 8.096 .69)scale(.59749)" gradientUnits="userSpaceOnUse"><stop class="wo2pnnbfa"/><stop offset="1" class="d0b6sb66h"/></radialGradient><radialGradient id="i9OB2kd" cx="0" cy="0" r="1" gradientTransform="matrix(.19017 -.09008 .52803 1.11467 13.399 6.395)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="irGb8te" cx="0" cy="0" r="1" gradientTransform="rotate(64.701 3.39 10.95)scale(2.40655 2.82856)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="iqhu6Vd" cx="0" cy="0" r="1" gradientTransform="matrix(-.30242 -.62082 1.59202 -.77552 12.36 4.981)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><filter id="iLRYhtb" width="28.938" height="27.87" x="2.031" y="3.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.658824 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="iuU2NJd" width="8.378" height="5.198" x="17.771" y="3.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.705882 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="ioDDbbc" width="27.922" height="3.388" x="2.047" y="26.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.258824 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="ien906c" width="9.938" height="9.938" x="2.104" y="20.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.156863 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="iJEqZKd" width="10.409" height="10.409" x="1.868" y="19.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23493" stdDeviation=".25"/></filter><filter id="i4QzKzc" width="10.037" height="10.037" x="20.049" y="19.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.0862745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="iV1xYqe" width="9.188" height="4.077" x="16.682" y="22.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.341176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.490196 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23493" result="effect2_innerShadow_3987_23493"/></filter><filter id="isMfPOe" width="4.034" height="2.181" x="13.544" y="23.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.188235 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="id5gW8c" width="3.572" height="8.62" x="15.217" y="15.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.709804 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="is36ucd" width="6.668" height="7.67" x="16.596" y="10.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.360784 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="i3GYEBM" width="7.971" height="5.869" x="15.054" y="7.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.286275 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="iNtZmBB" width="6.005" height="4.259" x="6.951" y="11.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.505882 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="iojA1ue" width="3.137" height="2.915" x="6.951" y="12.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.117647 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="iaI35pe" width="10.272" height="6.937" x="7.828" y="7.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.545098 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="iQUjkmc" width="5.496" height="6.372" x="17.742" y="10.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23493" stdDeviation=".3"/></filter><filter id="ioViyMc" width="2.969" height="2.969" x="7.756" y="11.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23493" stdDeviation=".3"/></filter><filter id="ihuyTEc" width="5.609" height="5.114" x="10.274" y="4.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.745098 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="iRrf0Le" width="2.792" height="2.561" x="13.374" y="4.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0156863 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="i1PeLid" width="5.987" height="5.122" x="9.213" y="1.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><filter id="i5nKIMd" width="2.02" height="1.392" x="11.195" y="3.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23493"/></filter><linearGradient id="imFdBxd" x1="9.65" x2="27.955" y1="21.004" y2="8.814" gradientUnits="userSpaceOnUse"><stop class="jk9sxjbtz"/><stop offset="1" class="bsmaek8tk"/></linearGradient><linearGradient id="i1mHagd" x1="29.363" x2="25.903" y1="11.992" y2="14.406" gradientUnits="userSpaceOnUse"><stop offset=".164" class="lc4-hmwkn"/><stop offset="1" class="jvv3w_k0n"/></linearGradient><linearGradient id="iAlBXgd" x1="21.156" x2="24.898" y1="7.004" y2="4.912" gradientUnits="userSpaceOnUse"><stop class="tw0q1w8vf"/><stop offset="1" class="icj8g3w8l"/></linearGradient><linearGradient id="iMqUPPc" x1="9.283" x2="3.252" y1="21.313" y2="28.344" gradientUnits="userSpaceOnUse"><stop class="aqhis8bfy"/><stop offset="1" class="dicaxrbsa"/></linearGradient><linearGradient id="iYNxjOc" x1="17.752" x2="18.721" y1="20.516" y2="19.51" gradientUnits="userSpaceOnUse"><stop offset=".573" class="js-d6kbwq"/><stop offset="1" class="ujlly7xsd"/></linearGradient><linearGradient id="iAUidTI" x1="22.268" x2="17.674" y1="22.084" y2="21.625" gradientUnits="userSpaceOnUse"><stop offset=".891" class="eper2rg6p"/><stop offset="1" class="btv0f_swr"/></linearGradient><linearGradient id="ikI6zud" x1="11.549" x2="10.674" y1="14.906" y2="14.625" gradientUnits="userSpaceOnUse"><stop class="b32taybyq"/><stop offset="1" class="cq_k1jhvn"/></linearGradient><linearGradient id="iByKjmc" x1="9.783" x2="8.502" y1="19.86" y2="19.375" gradientUnits="userSpaceOnUse"><stop offset=".146" class="l2qa6pp5f"/><stop offset="1" class="j4w4r7dqg"/></linearGradient><linearGradient id="isottie" x1="13.002" x2="13.393" y1="21.906" y2="21.406" gradientUnits="userSpaceOnUse"><stop class="xlcjgwbhs"/><stop offset="1" class="xdbcf5brc"/><stop offset="1" class="dkvvw7m1c"/></linearGradient><linearGradient id="iWYSLge" x1="20.049" x2="27.804" y1="27.417" y2="24.977" gradientUnits="userSpaceOnUse"><stop class="qkrvzzbyd"/><stop offset="1" class="zaq2lsbln"/></linearGradient><linearGradient id="iDeh7Jb" x1="23.83" x2="22.768" y1="21.844" y2="22.594" gradientUnits="userSpaceOnUse"><stop class="ikszdii2u"/><stop offset="1" class="li38i4ecv"/></linearGradient><linearGradient id="i7VZLSd" x1="19.627" x2="18.612" y1="20.617" y2="20.469" gradientUnits="userSpaceOnUse"><stop class="wjlh8kb9f"/><stop offset="1" class="pf-dzrbda"/></linearGradient><linearGradient id="iqttsuc" x1="16.635" x2="17.002" y1="13.742" y2="14.273" gradientUnits="userSpaceOnUse"><stop class="oqmso-c_s"/><stop offset="1" class="s2g06frqj"/></linearGradient><linearGradient id="iv0gtpe" x1="25.346" x2="16.682" y1="24.977" y2="24.977" gradientUnits="userSpaceOnUse"><stop class="jk12cqb2p"/><stop offset="1" class="bjfaebcql"/></linearGradient><linearGradient id="iQhym4p" x1="17.479" x2="16.721" y1="24.844" y2="24.844" gradientUnits="userSpaceOnUse"><stop class="z_jgx_kqm"/><stop offset="1" class="ktkvjmbcj"/></linearGradient><linearGradient id="icrPDJi" x1="15.565" x2="13.52" y1="9.375" y2="9.458" gradientUnits="userSpaceOnUse"><stop class="xqbtjumcc"/><stop offset="1" class="odf7_hbpj"/></linearGradient><linearGradient id="iWw2H8d" x1="11.108" x2="11.347" y1="7.228" y2="7.082" gradientUnits="userSpaceOnUse"><stop offset=".242" class="qrd5snbhi"/><stop offset=".667" class="ywpul_b7i"/></linearGradient><linearGradient id="iNWakNd" x1="13.774" x2="13.352" y1="6.58" y2="6.802" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="i7LqO5O" x1="13.64" x2="14.17" y1="8.418" y2="8.093" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-mountain-biking-light" /></template>
<style>
.af2e8qwjk {
  stop-color: var(--svg-color--fcceb9, #FCCEB9);
  stop-opacity: 0;
}

.aflx5ac8k {
  stop-color: var(--svg-color--f0b8a2, #F0B8A2);
  stop-opacity: 0;
}

.aiqsdtepb {
  stop-color: var(--svg-color--ffd359, #FFD359);
  stop-opacity: 0;
}

.aqhis8bfy {
  stop-color: var(--svg-color--302a5b, #302A5B);
}

.aw4amab0f {
  stop-color: var(--svg-color--736e75, #736E75);
}

.aw8cj7bar {
  stop-color: var(--svg-color--afa6a9, #AFA6A9);
}

.b32taybyq {
  stop-color: var(--svg-color--bfa8c7, #BFA8C7);
}

.b3q5ubbch {
  d: path("m14.015 15.445l1.34-.836l1.038 1.04l-.765 3.53a200 200 0 0 0-1.688-1.241c-.148-.102-.66-.543-.653-1.239c.008-.71.477-1.071.727-1.254");
}

.b9ukjpb0p {
  d: path("M11.235 5.178a.357.357 0 0 1 .153-.482l1.305-.677a.357.357 0 1 1 .329.635l-1.305.677a.357.357 0 0 1-.482-.153");
}

.bjfaebcql {
  stop-color: var(--svg-color--e8774d, #E8774D);
}

.bks5srb3y {
  d: path("M15.049 4.342L10.336 6.89a.263.263 0 0 1-.345-.071c-.17-.241-.41-.65-.602-1.137c-.574-1.453.429-2.297.56-2.426c.19-.188.713-.653 1.85-1.099c1.335-.522 2.202.057 2.63.604c.27.344.568.863.742 1.214a.28.28 0 0 1-.122.368");
}

.brfhj2bpt {
  stop-color: var(--svg-color--ecb19f, #ECB19F);
  stop-opacity: 0;
}

.bsmaek8tk {
  stop-color: var(--svg-color--36c571, #36C571);
}

.btv0f_swr {
  stop-color: var(--svg-color--615f76, #615F76);
}

.byihu8b7s {
  stop-color: var(--svg-color--dba096, #DBA096);
  stop-opacity: 0;
}

.cbgow0bwo {
  stop-color: var(--svg-color--e2dfe5, #E2DFE5);
}

.cc9670aeb {
  stop-color: var(--svg-color--932145, #932145);
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.cj8r45ujx {
  stop-color: var(--svg-color--ff6030, #FF6030);
}

.cpzd76x5u {
  fill-rule: evenodd;
  d: path("M17.142 8.274c.479.327.601.98.274 1.46c-.783 1.144-3.152 4.302-7.933 4.787c-.577.059-1.594-.319-1.653-.896s.865-1.134 1.441-1.193c3.844-.39 5.741-2.904 6.412-3.884a1.05 1.05 0 0 1 1.459-.274");
}

.cq_k1jhvn {
  stop-color: var(--svg-color--908590, #908590);
}

.cuptu7i6i {
  stop-color: var(--svg-color--e8ac93, #E8AC93);
}

.cvi6_hb_e {
  stop-color: var(--svg-color--564a5a, #564A5A);
}

.czabn_xgs {
  d: path("M13.554 7.913h2.154v2.668h-2.154z");
}

.d-6jagb2y {
  stop-color: var(--svg-color--ac2735, #AC2735);
}

.d0b6sb66h {
  stop-color: var(--svg-color--eabcb1, #EABCB1);
  stop-opacity: 0;
}

.d9lnsac_l {
  stop-color: var(--svg-color--c88d7e, #C88D7E);
  stop-opacity: 0;
}

.da9xf6l5p {
  stop-color: var(--svg-color--e2dfe5, #E2DFE5);
  stop-opacity: 0;
}

.dhib36bjr {
  stop-color: var(--svg-color--cf9f9d, #CF9F9D);
}

.dicaxrbsa {
  stop-color: var(--svg-color--302a5b, #302A5B);
  stop-opacity: 0;
}

.dks8srluc {
  cx: 13.447px;
  cy: 5.769px;
  r: 0.661px;
}

.dkvvw7m1c {
  stop-color: var(--svg-color--9c2649, #9C2649);
  stop-opacity: 0;
}

.dpi-7sbrv {
  stop-color: var(--svg-color--c78490, #C78490);
  stop-opacity: 0;
}

.e_--_59xk {
  d: path("m18.38 13.777l-.636-.699l4.032-2.476c1.422 1.867 1.5 3.21.836 4.273s-1.582 2.05-2.618 2.945c-.271.235-.802.362-1.359-.18c-.707-.687-1.578-1.578-2.04-2.113l1.778-1.608a.1.1 0 0 0 .007-.142");
}

.ea3nwpb8j {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M12.668 5.058a.296.296 0 0 1 .394.141l1.574 3.34a.296.296 0 0 1-.537.252l-1.573-3.339a.296.296 0 0 1 .142-.394");
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.egxex7b7c {
  stop-color: var(--svg-color--5c4f86, #5C4F86);
  stop-opacity: 0;
}

.eper2rg6p {
  stop-color: var(--svg-color--615f76, #615F76);
  stop-opacity: 0;
}

.f-r3ld20z {
  stop-color: var(--svg-color--baa3b9, #BAA3B9);
}

.f2dg1pymm {
  cx: 7.072px;
  cy: 24.977px;
  r: 4.555px;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
}

.f6rwhfb_k {
  stop-color: var(--svg-color--afa6a9, #AFA6A9);
  stop-opacity: 0;
}

.fqxr12j4i {
  stop-color: var(--svg-color--d29b92, #D29B92);
}

.ft5dv1b6b {
  fill: none;
}

.fuvqv0efx {
  fill-rule: evenodd;
  d: path("M10.57 16.335a.55.55 0 0 1 .3.718l-3.289 8a.55.55 0 0 1-1.017-.418l3.289-8a.55.55 0 0 1 .718-.3");
}

.fy0gg3b4w {
  stop-color: var(--svg-color--d9d1df, #D9D1DF);
  stop-opacity: 0;
}

.fze29cbbv {
  stop-color: var(--svg-color--fcceb9, #FCCEB9);
}

.g7aqyha-f {
  d: path("m17.898 20.866l-.3 1.98c-.067.476-.04.888.364 1.168c.102.07.238.03.307-.072l1.964-2.901a.2.2 0 0 0-.054-.278l-.952-.644z");
}

.g8r6p49_s {
  fill-rule: evenodd;
  d: path("M9.647 18.563c.101-.223.43-.466.672-.282l6.25 4.75a.55.55 0 0 1-.665.876l-6.081-4.61c-.242-.184-.305-.453-.176-.735");
}

.gcjq1zqgn {
  stop-color: var(--svg-color--f0b8a2, #F0B8A2);
}

.gfge3-bpx {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.969 6.763c-.067.232.075.46.15.576l.888-.546c-.542-.59-.947-.345-1.038-.03");
}

.gxtng2bih {
  stop-color: var(--svg-color--5d5c7e, #5D5C7E);
  stop-opacity: 0;
}

.h-r_c9b7x {
  d: path("m15.295 14.645l2.64-1.61l1.208.63l-2.727 2.476c-.268-.232-.84-1.051-1.12-1.496");
}

.hihpobcpj {
  stop-color: var(--svg-color--ecbaaa, #ECBAAA);
}

.hk_2rww3p {
  d: path("m19.204 20.133l-1.827-1.988l-.423 2.058l1 .706z");
}

.hla563ezk {
  d: path("M16.112 11.156c.664.625 1.363 1.586 1.671 1.969l4.243-2.18c-.586-.976-2.07-2.53-3.54-3.359c-1.718-.813-2.672 0-3.305 1.07c-.413.852.259 1.781.93 2.5");
}

.hqorccbwh {
  stop-color: var(--svg-color--3c2150, #3C2150);
}

.hs-_dnasa {
  stop-color: var(--svg-color--493b63, #493B63);
}

.huz3s4d_a {
  stop-color: var(--svg-color--c5bfcb, #C5BFCB);
}

.hwlgdac9v {
  stop-color: var(--svg-color--c68c7c, #C68C7C);
}

.hz6yw06qq {
  fill: var(--svg-color--5b4e85, #5B4E85);
  d: path("m16.115 23.226l-1.809.861c-.43.212-.756.465-.762.956c0 .124.108.214.231.214h3.504a.2.2 0 0 0 .2-.2v-1.15z");
}

.ibpqkjjwa {
  fill: var(--svg-color--86014d, #86014D);
  fill-rule: evenodd;
  d: path("M11.898 8.67a.12.12 0 0 1 .038-.163c.102-.064.236-.218.305-.539a.118.118 0 1 1 .231.05c-.078.366-.24.584-.411.69a.12.12 0 0 1-.163-.038");
}

.icj8g3w8l {
  stop-color: var(--svg-color--e2dce7, #E2DCE7);
}

.ikszdii2u {
  stop-color: var(--svg-color--fd5a60, #FD5A60);
}

.iqlq1pbje {
  stop-color: var(--svg-color--f3c0b0, #F3C0B0);
}

.iy0i0xbqt {
  d: path("M12.955 11.61a.575.575 0 0 0-.575-.576H9.33a2.13 2.13 0 0 0 0 4.26h.183a.575.575 0 1 0 0-1.15H9.33a.98.98 0 1 1 0-1.96h3.05a.575.575 0 0 0 .575-.575");
}

.j2lckmjxn {
  fill-rule: evenodd;
  d: path("M12.668 5.058a.296.296 0 0 1 .394.141l1.574 3.34a.296.296 0 0 1-.537.252l-1.573-3.339a.296.296 0 0 1 .142-.394");
}

.j4w4r7dqg {
  stop-color: var(--svg-color--973c50, #973C50);
}

.j9bmo4yzb {
  stop-color: var(--svg-color--c7898c, #C7898C);
}

.ja_424b_z {
  stop-color: var(--svg-color--b27d80, #B27D80);
  stop-opacity: 0;
}

.jk12cqb2p {
  stop-color: var(--svg-color--f7b14e, #F7B14E);
}

.jk5eocp2v {
  stop-color: var(--svg-color--e44354, #E44354);
  stop-opacity: 0;
}

.jk9sxjbtz {
  stop-color: var(--svg-color--37c173, #37C173);
}

.jqhw67baa {
  stop-color: var(--svg-color--736e75, #736E75);
  stop-opacity: 0;
}

.js-d6kbwq {
  stop-color: var(--svg-color--cb8983, #CB8983);
}

.jsa0_reur {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
}

.jvv3w_k0n {
  stop-color: var(--svg-color--36c871, #36C871);
  stop-opacity: 0;
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.jxqufcbzg {
  stop-color: var(--svg-color--dfaf96, #DFAF96);
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.ktkvjmbcj {
  stop-color: var(--svg-color--605c92, #605C92);
  stop-opacity: 0;
}

.l-nb061ot {
  stop-color: var(--svg-color--1d191c, #1D191C);
  stop-opacity: 0;
}

.l084ily_a {
  fill: var(--svg-color--654b4b, #654B4B);
  d: path("m11.617 7.032l-.03-.048c-.166-.249-.409-.378-.543-.289s-.108.364.057.612l.02.03z");
}

.l2qa6pp5f {
  stop-color: var(--svg-color--d4385b, #D4385B);
}

.l4_q8ccja {
  stop-color: var(--svg-color--ebeaed, #EBEAED);
}

.lc4-hmwkn {
  stop-color: var(--svg-color--4cdd80, #4CDD80);
}

.li38i4ecv {
  stop-color: var(--svg-color--af253c, #AF253C);
}

.m2hzjbyuc {
  d: path("m3.898 16.711l-1.867 1.938v11.28H29.97V13.4l-6.14-9.306a2.3 2.3 0 0 0-3.841.003l-8.916 13.548a.5.5 0 0 1-.715.127L8.31 16.255c-1.32-.98-3.2-.8-4.41.457");
}

.m3q9izqvj {
  stop-color: var(--svg-color--5d5c7e, #5D5C7E);
}

.mp1bj4bkr {
  stop-color: var(--svg-color--ebbca0, #EBBCA0);
  stop-opacity: 0;
}

.ms8ncfh9g {
  stop-color: var(--svg-color--8c5ea8, #8C5EA8);
  stop-opacity: 0;
}

.msqk4cb8o {
  stop-color: var(--svg-color--373c67, #373C67);
}

.mvvhg6bob {
  fill-rule: evenodd;
  d: path("M12.505 11.6a.5.5 0 0 1 .271.653l-2.54 6.247a.5.5 0 0 1-.924-.381l2.54-6.247a.5.5 0 0 1 .653-.272");
}

.mx2mcdbpf {
  fill-rule: evenodd;
  d: path("M8.974 13.516a.33.33 0 0 1 0 .402c-.151.126-.343.39-.372.594a.35.35 0 1 1-.693-.101a1.4 1.4 0 0 1 .155-.429c.08-.147.196-.312.354-.443c.148-.123.433-.172.556-.023");
}

.npgm2vb6k {
  d: path("M12.017 9.203c-.8-.736-1.473-1.93-1.742-2.396l3.457-2.178l1.901 1.663a5.3 5.3 0 0 1-.908 1.947c-.7.91-1.657 1.93-2.708.964");
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nrp3vkbjq {
  fill-rule: evenodd;
  d: path("M19.756 16.62a.55.55 0 0 0-.172.76l4.719 7.476a.55.55 0 1 0 .93-.587l-4.719-7.477a.55.55 0 0 0-.758-.171");
}

.nus19y6ts {
  stop-color: var(--svg-color--ffd359, #FFD359);
}

.o0tyh0b-k {
  d: path("m16.096 16l.553-.514l2.04 1.916c-.273.154-.886.464-1.03.582c-.11.091-.11.235-.11.329l-.046 5.593l-1.407-.672c-.138-.794-.42-2.708-.769-4.3c-.395-1.801.376-2.593.77-2.934");
}

.o2gu83zjq {
  stop-color: var(--svg-color--e4af9f, #E4AF9F);
}

.o5ujuoler {
  stop-color: var(--svg-color--4f414e, #4F414E);
}

.o83duvb6p {
  stop-color: var(--svg-color--cd8b8b, #CD8B8B);
}

.odf7_hbpj {
  stop-color: var(--svg-color--c6817c, #C6817C);
}

.oqmso-c_s {
  stop-color: var(--svg-color--72696b, #72696B);
}

.p_o38mbkb {
  stop-color: var(--svg-color--dba398, #DBA398);
}

.p0n-v6bwi {
  stop-color: var(--svg-color--dca28a, #DCA28A);
}

.p1dkvx0ja {
  stop-color: var(--svg-color--8a4c56, #8A4C56);
  stop-opacity: 0;
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pf-dzrbda {
  stop-color: var(--svg-color--a62f2f, #A62F2F);
}

.pfbx1ib6q {
  fill-rule: evenodd;
  d: path("M25.018 21.008a3.969 3.969 0 1 0 0 7.937a3.969 3.969 0 0 0 0-7.937m-4.969 3.969a4.969 4.969 0 1 1 9.938 0a4.969 4.969 0 0 1-9.938 0");
}

.pypniyb9c {
  fill-rule: evenodd;
  d: path("M8.827 13.457a.35.35 0 0 1-.227.44a.6.6 0 0 0-.406.457a.35.35 0 1 1-.683-.152c.05-.223.235-.767.876-.972a.35.35 0 0 1 .44.227");
}

.pzip1rpvk {
  fill: var(--svg-color--c0b9bc, #C0B9BC);
  d: path("M12.955 11.61a.575.575 0 0 0-.575-.576H9.33a2.13 2.13 0 0 0 0 4.26h.183a.575.575 0 1 0 0-1.15H9.33a.98.98 0 1 1 0-1.96h3.05a.575.575 0 0 0 .575-.575");
}

.qc8cprh-k {
  d: path("m21.006 12.895l-.523-.863l1.125-.656c.968 1.312 1.343 2.296.734 2.875c-.487.462-2.87 1.723-4 2.296l2.503-2.414a1 1 0 0 0 .161-1.238");
}

.qfj7itbso {
  stop-color: var(--svg-color--8a4c56, #8A4C56);
}

.qkrvzzbyd {
  stop-color: var(--svg-color--352542, #352542);
}

.qktpib9mi {
  stop-color: var(--svg-color--8c5ea8, #8C5EA8);
}

.qnv5cwbcc {
  stop-color: var(--svg-color--baa3b9, #BAA3B9);
  stop-opacity: 0;
}

.qrd5snbhi {
  stop-color: var(--svg-color--5f5451, #5F5451);
}

.rgol9fpyb {
  stop-color: var(--svg-color--e44354, #E44354);
}

.rj3xdun2l {
  d: path("m17.771 7.463l2.247-1.314a.4.4 0 0 1 .511.09l1.07 1.3a.6.6 0 0 0 .927 0l1.067-1.296a.4.4 0 0 1 .515-.089L25.9 7.231l-2.07-3.138a2.3 2.3 0 0 0-3.841.003z");
}

.rknt09byu {
  fill: var(--svg-color--97595f, #97595F);
  d: path("m5.663 27.116l-3.616 2.158v.671h27.922v-.671l-3.532-2.15a2.4 2.4 0 0 0-2.429-.04l-.817.461a2 2 0 0 1-1.838.068l-1.319-.623a2.25 2.25 0 0 0-1.965.021l-1.176.587a2 2 0 0 1-1.823-.02l-1.126-.591a2 2 0 0 0-1.783-.039l-1.42.67a2 2 0 0 1-1.825-.062l-.855-.477a2.4 2.4 0 0 0-2.398.037");
}

.rrfczgbhc {
  cx: 18.389px;
  cy: 24.977px;
  r: 1.027px;
}

.s2g06frqj {
  stop-color: var(--svg-color--72696b, #72696B);
  stop-opacity: 0;
}

.s2qrn4tqf {
  fill-rule: evenodd;
  d: path("M9.337 12.922a.35.35 0 0 1-.35.35c-.173 0-.436.042-.663.15c-.226.106-.37.252-.415.438a.35.35 0 1 1-.68-.166c.113-.466.462-.748.796-.906c.334-.157.7-.216.962-.216a.35.35 0 0 1 .35.35");
}

.sc_kwfbiq {
  stop-color: var(--svg-color--ff8e59, #FF8E59);
}

.sidw1obfr {
  fill: var(--svg-color--413354, #413354);
  d: path("m17.898 20.866l-.3 1.98c-.067.476-.04.888.364 1.168c.102.07.238.03.307-.072l1.964-2.901a.2.2 0 0 0-.054-.278l-.952-.644z");
}

.slryrmbbo {
  stop-color: var(--svg-color--c78490, #C78490);
}

.t0xl0mbii {
  stop-color: var(--svg-color--c08175, #C08175);
}

.t51spjdji {
  d: path("M11.426 7.15a1 1 0 0 0-.05-.093c-.092-.138-.225-.21-.298-.163c-.072.049-.056.2.036.338a1 1 0 0 0 .058.073z");
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tnn6d9lnt {
  stop-color: var(--svg-color--ddac9a, #DDAC9A);
}

.tw0q1w8vf {
  stop-color: var(--svg-color--d7cfdf, #D7CFDF);
}

.u3_kb5fuo {
  fill: var(--svg-color--2b174f, #2B174F);
  fill-rule: evenodd;
  d: path("M8.35 13.223V13.2a.572.572 0 1 0-1.145 0v.022h-.004a2.13 2.13 0 0 0 2.13 2.07h.182a.575.575 0 0 0 0-1.15H9.33a.98.98 0 0 1-.978-.92z");
}

.ue1cg0jtk {
  fill-rule: evenodd;
  d: path("M7.073 21.008a3.969 3.969 0 1 0 0 7.937a3.969 3.969 0 0 0 0-7.937m-4.97 3.969a4.969 4.969 0 1 1 9.938 0a4.969 4.969 0 0 1-9.937 0");
}

.ujlly7xsd {
  stop-color: var(--svg-color--d5a595, #D5A595);
}

.um4kzybeo {
  d: path("m16.115 23.226l-1.809.861c-.43.212-.756.465-.762.956c0 .124.108.214.231.214h3.504a.2.2 0 0 0 .2-.2v-1.15z");
}

.ur7lpnbek {
  stop-color: var(--svg-color--b27d80, #B27D80);
}

.uucs6l1bh {
  stop-color: var(--svg-color--c58284, #C58284);
}

.v5ts0ibjo {
  stop-color: var(--svg-color--d8cfe2, #D8CFE2);
}

.v911bvqyx {
  cx: 11.086px;
  cy: 6.871px;
  r: 0.085px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.vlgj1odqb {
  cx: 9.24px;
  cy: 13.424px;
  r: 0.885px;
  fill: var(--svg-color--e3b3a0, #E3B3A0);
}

.vn5o04bza {
  stop-color: var(--svg-color--ecbaaa, #ECBAAA);
  stop-opacity: 0;
}

.w0i7s3bkp {
  stop-color: var(--svg-color--d79f9b, #D79F9B);
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wc0bxtmli {
  stop-color: var(--svg-color--38144f, #38144F);
}

.wjlh8kb9f {
  stop-color: var(--svg-color--e5435f, #E5435F);
}

.wjs_nsbuh {
  fill-rule: evenodd;
  d: path("M20.06 16.541a.55.55 0 0 1 .417.657l-1.579 7.078a.55.55 0 0 1-1.073-.24l1.578-7.078a.55.55 0 0 1 .657-.417");
}

.wm4p2nf6o {
  d: path("M18.93 26.8a1.863 1.863 0 1 1 .018-3.643l5.898.906a.927.927 0 0 1-.086 1.837z");
}

.wo2pnnbfa {
  stop-color: var(--svg-color--eabcb1, #EABCB1);
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x8yh06lcj {
  fill: var(--svg-color--1b131d, #1B131D);
  d: path("m14.598 6.331l-1.224-1.21l1.77-.946c.224.364.24 1.062.202 1.32a.516.516 0 0 1 .668.408c.026.196-.141.599-.598.712c-.366.092-.697-.151-.818-.284");
}

.x91_06blc {
  stop-color: var(--svg-color--cb8583, #CB8583);
}

.xal9k3bum {
  stop-color: var(--svg-color--dba398, #DBA398);
  stop-opacity: 0;
}

.xdbcf5brc {
  stop-color: var(--svg-color--96275e, #96275E);
  stop-opacity: 0;
}

.xlcjgwbhs {
  stop-color: var(--svg-color--96275e, #96275E);
}

.xqbtjumcc {
  stop-color: var(--svg-color--ebbda6, #EBBDA6);
}

.y16t4y92n {
  stop-color: var(--svg-color--32295b, #32295B);
}

.yozietovn {
  d: path("M10.811 8.457c-.206-.137-.213-.298-.152-.658a.83.83 0 0 0-.073-.54l.838.989c-.105.226-.406.346-.613.21");
}

.yt4h0-bzj {
  stop-color: var(--svg-color--ecb19f, #ECB19F);
}

.ywpul_b7i {
  stop-color: var(--svg-color--383838, #383838);
}

.z_jgx_kqm {
  stop-color: var(--svg-color--605c92, #605C92);
}

.z140-2b1b {
  fill: var(--svg-color--e7b6a2, #E7B6A2);
  fill-rule: evenodd;
  d: path("M17.142 8.274c.479.327.601.98.274 1.46c-.783 1.144-3.152 4.302-7.933 4.787c-.577.059-1.594-.319-1.653-.896s.865-1.134 1.441-1.193c3.844-.39 5.741-2.904 6.412-3.884a1.05 1.05 0 0 1 1.459-.274");
}

.z5z2pubmg {
  d: path("m5.663 27.116l-3.616 2.158v.671h27.922v-.671l-3.532-2.15a2.4 2.4 0 0 0-2.429-.04l-.817.461a2 2 0 0 1-1.838.068l-1.319-.623a2.25 2.25 0 0 0-1.965.021l-1.176.587a2 2 0 0 1-1.823-.02l-1.126-.591a2 2 0 0 0-1.783-.039l-1.42.67a2 2 0 0 1-1.825-.062l-.855-.477a2.4 2.4 0 0 0-2.398.037");
}

.zaq2lsbln {
  stop-color: var(--svg-color--352542, #352542);
  stop-opacity: 0;
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zd8v8x_xx {
  stop-color: var(--svg-color--ac2735, #AC2735);
  stop-opacity: 0;
}

.zfr_gp_ns {
  d: path("m14.598 6.331l-1.224-1.21l1.77-.946c.224.364.24 1.062.202 1.32a.516.516 0 0 1 .668.408c.026.196-.141.599-.598.712c-.366.092-.697-.151-.818-.284");
}

.zo6cprbov {
  stop-color: var(--svg-color--ce3d5e, #CE3D5E);
}

.zvme7yb8w {
  stop-color: var(--svg-color--a3a1a2, #A3A1A2);
}

.zwrak1b2j {
  stop-color: var(--svg-color--726b71, #726B71);
}

</style>
