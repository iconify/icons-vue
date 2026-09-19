<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iod8h7b)"><path fill="url(#iYNa1dc)" clip-rule="evenodd" class="zksl5ybvj"/></g><g filter="url(#iDJlQ8a)"><path class="joiz9mbyc"/><path fill="url(#iBvu5Sb)" class="cms6m9u9x"/><path fill="url(#iaTMtZd)" class="cms6m9u9x"/></g><path fill="url(#iOXUFee)" class="cms6m9u9x"/><path fill="url(#iHJ2Bqd)" class="vm3938bqq"/><path fill="url(#ie0uH1d)" class="vm3938bqq"/><path fill="url(#isG7eBe)" class="vm3938bqq"/><g filter="url(#io2kCEn)"><path class="x6ukpnq0x"/></g><path class="t37supbyn"/><path fill="url(#iEKUpld)" class="nyvmdac6c"/><path fill="url(#i8jrcoe)" class="nyvmdac6c"/><path fill="url(#i2vw38b)" class="nyvmdac6c"/><path fill="url(#inbdIwd)" class="nyvmdac6c"/><g filter="url(#iLTpvxc)"><path class="mtjlhkzpv"/></g><path fill="url(#iDtCmec)" class="t0x3luqrl"/><path fill="url(#iKKQBub)" class="t0x3luqrl"/><path fill="url(#i7h3s9d)" class="t0x3luqrl"/><path fill="url(#iymsGTc)" class="t0x3luqrl"/><path fill="url(#iexbn3b)" class="t0x3luqrl"/><path fill="url(#i5W57Pb)" class="t0x3luqrl"/><path fill="url(#iLQz2ae)" class="t0x3luqrl"/><path fill="url(#ioAwGkc)" class="y123f7bnt"/><path fill="url(#i14zSJc)" class="y123f7bnt"/><path fill="url(#iqc24Fc)" class="y123f7bnt"/><path fill="url(#iMpLeOe)" class="y123f7bnt"/><path fill="url(#ipJlgpB)" class="y123f7bnt"/><rect transform="rotate(-26.783 21.988 4.133)" class="j74nwzkwd"/><rect fill="url(#iaGGNgc)" transform="rotate(-26.783 22.422 3.873)" class="x2-43ybrg"/><rect fill="url(#i1nCO8G)" transform="rotate(-26.783 22.94 3.627)" class="biiy2vbjw"/><rect fill="url(#iUEpfmc)" transform="rotate(-26.783 23.51 3.373)" class="x2horqbll"/><rect fill="url(#iRkcN7d)" transform="rotate(60 23.314 4.404)" class="ajgu03mkq"/><g filter="url(#igdrE2d)"><path class="m8axnuzwu"/><path fill="url(#iZM1b4t)" class="lhwrmw8_g"/></g><g filter="url(#it67JZX)"><path fill="url(#iW9sR7c)" class="my1tdgbin"/><path fill="url(#i1IeNNb)" class="my1tdgbin"/><path fill="url(#iZG6lpa)" class="my1tdgbin"/></g><g filter="url(#i4VHrMe)"><path class="injufkbna"/></g><g filter="url(#ikpM8Pc)"><path stroke="url(#iBO2Klc)" class="v_rk8pcnx"/></g><g filter="url(#iyyFqDc)"><path fill="url(#iki1Occ)" class="czem1g9ht"/></g><g filter="url(#ikLeuDc)"><circle fill="url(#ik5Et0b)" transform="rotate(-30 14.224 7.268)" class="ehevujb0f"/></g><g filter="url(#iHAJGOd)"><circle fill="url(#ixCLg8d)" transform="rotate(-30 14.224 7.268)" class="z09wjwb_u"/></g><g filter="url(#iMoGted)"><circle fill="url(#iHIc3Ac)" transform="rotate(-30 17.724 5.248)" class="ouoib-wwx"/><circle fill="url(#iI8pooe)" transform="rotate(-30 17.724 5.248)" class="ouoib-wwx"/></g><g filter="url(#ixysILe)"><circle transform="rotate(-30 17.724 5.247)" class="dkqztxbmt"/><circle fill="url(#ijqvMNd)" transform="rotate(-30 17.724 5.247)" class="rgvdret3u"/><circle fill="url(#i40RSTc)" transform="rotate(-30 17.724 5.247)" class="rgvdret3u"/></g><path fill="url(#iw8eRzd)" class="w0po07knh"/><path fill="url(#iDR4Sed)" class="w0po07knh"/><path fill="url(#iyppMye)" class="w0po07knh"/><path fill="url(#iVMQ35b)" class="w0po07knh"/><path fill="url(#ib7CnNd)" class="w0po07knh"/><path fill="url(#ig8z9Le)" class="w0po07knh"/><g filter="url(#iX2mIkb)"><path class="lbg18dbij"/></g><g filter="url(#iCHo8Ge)"><path class="nzyye1byl"/><path fill="url(#i8q73fc)" class="v8crsob7z"/><path fill="url(#itp1pHe)" class="v8crsob7z"/><path fill="url(#inhrmmb)" class="v8crsob7z"/><path fill="url(#iZektoc)" class="v8crsob7z"/></g><path stroke="url(#i9W6p9b)" class="x0q6gbiik"/><path class="stmatkb5e"/><path fill="url(#iw9OlgQ)" class="w-05y9s8i"/><path class="acuzwsbvu"/><g filter="url(#iX2Vepd)"><path class="xk1kgabub"/><path fill="url(#ifGrpCb)" class="a14qj5b2p"/></g><g filter="url(#iGNWKhe)"><path fill="url(#iNyhtUc)" class="ag8ecac8l"/></g><path class="eu9ex6b_l"/><path fill="url(#iyk6rhc)" class="jy7-vab8i"/><path class="h4wmweawy"/><g filter="url(#iilWDab)"><path fill="url(#iNnYWxc)" class="mhb206blg"/></g><g filter="url(#i1ZHOZc)"><ellipse transform="rotate(-57.914 14.902 6.495)" class="gx_ogt9nw"/><ellipse fill="url(#ix4PQyb)" transform="rotate(-57.914 14.902 6.495)" class="bpaiimy_w"/></g><g filter="url(#ikvIUQJ)"><path clip-rule="evenodd" class="m3zm84h0u"/></g><g filter="url(#iUnsbsb)"><path clip-rule="evenodd" class="o_lkstboy"/></g><path fill="url(#i96765b)" class="hg53hdc5j"/><path fill="url(#iBBZZqb)" class="kvw1hrrrt"/><g filter="url(#iv9mSLd)"><path fill="url(#i6qn3YN)" class="uoxjyextx"/><path fill="url(#iuOhSTb)" class="uoxjyextx"/></g><path fill="url(#iZZHSlb)" class="irk4y6bhp"/><path fill="url(#iZPk0md)" class="irk4y6bhp"/><path fill="url(#illnp8c)" class="irk4y6bhp"/><path fill="url(#iWkv0jp)" class="irk4y6bhp"/><defs><radialGradient id="iBvu5Sb" cx="0" cy="0" r="1" gradientTransform="rotate(146.915 9.437 6.132)scale(4.92324 2.04943)" gradientUnits="userSpaceOnUse"><stop class="ba1yb3bji"/><stop offset="1" class="kgrhzo17p"/></radialGradient><radialGradient id="iOXUFee" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -.0625 .23626 5.43402 7.847 13.711)" gradientUnits="userSpaceOnUse"><stop class="wn-t5ndzy"/><stop offset="1" class="ben4f0bqs"/></radialGradient><radialGradient id="isG7eBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .16016 -.21807 -.37232 26.179 2.965)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="i42zc8m6u"/><stop offset="1" class="dsumrvbgt"/></radialGradient><radialGradient id="i8jrcoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 -.46876 .24583 -.45888 15.472 29.57)" gradientUnits="userSpaceOnUse"><stop class="ynlfw99ba"/><stop offset="1" class="in-vfpgwh"/></radialGradient><radialGradient id="i2vw38b" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .85157 -1.15842 -1.0415 14.081 27.063)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="vkrof_bbk"/><stop offset="1" class="h8hiq33uv"/></radialGradient><radialGradient id="inbdIwd" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 .15625 -.58594 3.04687 12.706 28.461)" gradientUnits="userSpaceOnUse"><stop class="ilg8l_bzj"/><stop offset="1" class="s2j02zbkr"/></radialGradient><radialGradient id="iKKQBub" cx="0" cy="0" r="1" gradientTransform="matrix(2.71873 -2.53127 .81258 .87276 14.504 28.024)" gradientUnits="userSpaceOnUse"><stop class="pcvpzjboo"/><stop offset="1" class="qe_2d-buv"/></radialGradient><radialGradient id="i7h3s9d" cx="0" cy="0" r="1" gradientTransform="matrix(2.54688 -2.64063 .2894 .27913 13.613 26.368)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="kxzgmzb5t"/><stop offset="1" class="xhu8yhbcw"/></radialGradient><radialGradient id="iymsGTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 0 0 -5.02098 18.706 21.711)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="keljo6scd"/><stop offset="1" class="ps4m-ab9c"/></radialGradient><radialGradient id="iexbn3b" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 -.98437 1.15192 .05485 18.956 18.383)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="w5oxhdc5r"/><stop offset="1" class="ebs2-pbbe"/></radialGradient><radialGradient id="i5W57Pb" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 0 0 7.6823 19.316 23.07)" gradientUnits="userSpaceOnUse"><stop class="j_l_30buh"/><stop offset="1" class="xi8fv135v"/></radialGradient><radialGradient id="iLQz2ae" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -3.34375 1.20794 1.23052 15.003 28.086)" gradientUnits="userSpaceOnUse"><stop class="ddjhanboc"/><stop offset="1" class="uu7_gub8n"/></radialGradient><radialGradient id="ioAwGkc" cx="0" cy="0" r="1" gradientTransform="rotate(150.356 9.234 7.823)scale(4.42262 6.15908)" gradientUnits="userSpaceOnUse"><stop class="no0_3dbdi"/><stop offset="1" class="truekjbvb"/></radialGradient><radialGradient id="i14zSJc" cx="0" cy="0" r="1" gradientTransform="matrix(.57404 2.73801 -4.6268 .97003 18.617 7.348)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="kdxlabb_n"/><stop offset="1" class="x9_x14ckq"/></radialGradient><radialGradient id="iMpLeOe" cx="0" cy="0" r="1" gradientTransform="matrix(.87501 1.59375 -2.6006 1.4278 16.628 8.055)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="v2g8x4brb"/><stop offset="1" class="we0trlbug"/></radialGradient><radialGradient id="ipJlgpB" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -.01563 .0588 6.46896 14.816 10.461)" gradientUnits="userSpaceOnUse"><stop class="qg0h4w_kv"/><stop offset="1" class="iich1wbqp"/></radialGradient><radialGradient id="iaGGNgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 23.098 4.541)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="afeoc7jzt"/><stop offset="1" class="eupzhi8eb"/></radialGradient><radialGradient id="i1nCO8G" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 23.617 4.295)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="afeoc7jzt"/><stop offset="1" class="eupzhi8eb"/></radialGradient><radialGradient id="iUEpfmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 24.186 4.041)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="afeoc7jzt"/><stop offset="1" class="eupzhi8eb"/></radialGradient><radialGradient id="iRkcN7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.02457 .47352 -.46721 -.02424 23.707 4.557)" gradientUnits="userSpaceOnUse"><stop class="zr-3xsbrq"/><stop offset="1" class="n9y8__b1h"/></radialGradient><radialGradient id="iZM1b4t" cx="0" cy="0" r="1" gradientTransform="matrix(3.80388 .30087 -.62375 7.88601 18.914 5.696)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="fka-wz-bu"/><stop offset="1" class="vlsksmbwa"/></radialGradient><radialGradient id="i1IeNNb" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 .21242 -.56203 4.5475 15.378 9.868)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="v__i2ebru"/><stop offset="1" class="yrm14tb3b"/></radialGradient><radialGradient id="iZG6lpa" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 .51562 -1.9883 .18075 17.519 8.852)" gradientUnits="userSpaceOnUse"><stop class="hnewum4zo"/><stop offset="1" class="j297-pbqp"/></radialGradient><radialGradient id="ik5Et0b" cx="0" cy="0" r="1" gradientTransform="matrix(.74551 0 0 1.30466 13.515 7.268)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iI8pooe" cx="0" cy="0" r="1" gradientTransform="matrix(.3512 -.25573 .29189 .40086 17.882 5.135)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="ijqvMNd" cx="0" cy="0" r="1" gradientTransform="matrix(.34861 -.6412 .3753 .20404 17.706 5.596)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="i40RSTc" cx="0" cy="0" r="1" gradientTransform="matrix(.11006 .10895 -.14045 .14188 17.725 5.247)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iDR4Sed" cx="0" cy="0" r="1" gradientTransform="rotate(60 3.455 15.836)scale(4.53299 4.31258)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="gbmz9tkck"/><stop offset=".952" class="nbba5kb5p"/></radialGradient><radialGradient id="iVMQ35b" cx="0" cy="0" r="1" gradientTransform="rotate(-120 9.812 -2.137)scale(.55528 .68055)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="ib7CnNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.29544 -.51172 .63368 -.36586 14.892 6.243)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="ig8z9Le" cx="0" cy="0" r="1" gradientTransform="rotate(60 3.41 15.548)scale(1.93644 3.91079)" gradientUnits="userSpaceOnUse"><stop class="qh4fa-z4p"/><stop offset="1" class="n4g176b3c"/></radialGradient><radialGradient id="iw9OlgQ" cx="0" cy="0" r="1" gradientTransform="matrix(.17216 .29818 -.4743 .27384 16.627 5.547)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ifGrpCb" cx="0" cy="0" r="1" gradientTransform="rotate(-157.811 8.832 1.19)scale(.16054 .22102)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iyk6rhc" cx="0" cy="0" r="1" gradientTransform="rotate(60 1.906 16.246)scale(.34433 .54769)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ix4PQyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00328 -.20968 .25204 -.00395 14.896 6.629)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6qn3YN" cx="0" cy="0" r="1" gradientTransform="rotate(-33.523 16.768 -19.913)scale(3.26953 12.1156)" gradientUnits="userSpaceOnUse"><stop class="fn7-6xayh"/><stop offset="1" class="chayuvnap"/></radialGradient><radialGradient id="iuOhSTb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01778 -.63409 1.12377 -.03151 16.381 4.559)" gradientUnits="userSpaceOnUse"><stop class="sylx2mbjo"/><stop offset="1" class="nav-8e2lo"/></radialGradient><radialGradient id="iZZHSlb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50297 1.26182 -1.20308 -2.38645 16.046 3.916)" gradientUnits="userSpaceOnUse"><stop class="blekadc8f"/><stop offset="1" class="c6xk9jx7z"/></radialGradient><radialGradient id="iZPk0md" cx="0" cy="0" r="1" gradientTransform="rotate(-87.842 9.804 -4.006)scale(2.41569 3.74284)" gradientUnits="userSpaceOnUse"><stop class="jjpmu-56c"/><stop offset="1" class="ldm9khd7d"/></radialGradient><radialGradient id="illnp8c" cx="0" cy="0" r="1" gradientTransform="rotate(-115.648 9.056 -2.358)scale(1.02453 2.2655)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o2ca957_x"/><stop offset="1" class="a7xagmxua"/></radialGradient><radialGradient id="iWkv0jp" cx="0" cy="0" r="1" gradientTransform="matrix(.34801 .52964 -2.87504 1.8891 14.035 2.927)" gradientUnits="userSpaceOnUse"><stop class="uw0kegb-q"/><stop offset="1" class="ydllxhbat"/></radialGradient><linearGradient id="iYNa1dc" x1="24.351" x2="21.294" y1="5.137" y2="11.142" gradientUnits="userSpaceOnUse"><stop class="d1gs3_bfs"/><stop offset=".799" class="dl4ua154c"/></linearGradient><linearGradient id="iaTMtZd" x1="13.831" x2="14.159" y1="9.568" y2="10.04" gradientUnits="userSpaceOnUse"><stop offset=".349" class="lr97j31fb"/><stop offset="1" class="azn0z--js"/></linearGradient><linearGradient id="iHJ2Bqd" x1="26.253" x2="24.113" y1="3.086" y2="4.399" gradientUnits="userSpaceOnUse"><stop class="ds3hm--8v"/><stop offset="1" class="bq7w62n5j"/></linearGradient><linearGradient id="ie0uH1d" x1="25.222" x2="24.956" y1="4.086" y2="3.555" gradientUnits="userSpaceOnUse"><stop class="seeiowbir"/><stop offset="1" class="tw6dxpb7y"/></linearGradient><linearGradient id="iEKUpld" x1="14.034" x2="14.034" y1="30.422" y2="29.75" gradientUnits="userSpaceOnUse"><stop class="dhem-xbnm"/><stop offset="1" class="zn47ozbfv"/></linearGradient><linearGradient id="iDtCmec" x1="21.816" x2="21.222" y1="22.961" y2="22.93" gradientUnits="userSpaceOnUse"><stop class="ieaclmdnn"/><stop offset="1" class="p3yd_be1u"/></linearGradient><linearGradient id="iqc24Fc" x1="18.617" x2="18.617" y1="16.368" y2="13.18" gradientUnits="userSpaceOnUse"><stop offset=".039" class="ptputobcp"/><stop offset="1" class="br5umybnw"/></linearGradient><linearGradient id="iW9sR7c" x1="17.348" x2="17.348" y1="8.75" y2="10.961" gradientUnits="userSpaceOnUse"><stop class="bw1hkxbcb"/><stop offset="1" class="tesa8u_3j"/></linearGradient><linearGradient id="iBO2Klc" x1="21.081" x2="21.081" y1="16.993" y2="27.899" gradientUnits="userSpaceOnUse"><stop class="hd06b2knh"/><stop offset="1" class="ggughpb3d"/></linearGradient><linearGradient id="iki1Occ" x1="17.644" x2="17.644" y1="18.43" y2="24.993" gradientUnits="userSpaceOnUse"><stop class="y6ovumr8k"/><stop offset="1" class="t-eeezbdl"/></linearGradient><linearGradient id="ixCLg8d" x1="14.224" x2="13.952" y1="7.387" y2="7.387" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iHIc3Ac" x1="18.186" x2="17.838" y1="4.784" y2="5.861" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iw8eRzd" x1="17.541" x2="14.982" y1="5.545" y2="7.576" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iyppMye" x1="14.658" x2="15.441" y1="8.532" y2="7.932" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="i8q73fc" x1="15.876" x2="16.221" y1="6.829" y2="6.63" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="itp1pHe" x1="16.607" x2="16.227" y1="6.565" y2="6.777" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="inhrmmb" x1="16.491" x2="16.369" y1="6.996" y2="6.785" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iZektoc" x1="15.85" x2="16.135" y1="6.051" y2="6.544" gradientUnits="userSpaceOnUse"><stop class="gyzb8obwr"/><stop offset="1" class="wu_f8xbqm"/></linearGradient><linearGradient id="i9W6p9b" x1="16.381" x2="16.395" y1="7.852" y2="7.507" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iNyhtUc" x1="16.924" x2="16.85" y1="5.401" y2="5.537" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iNnYWxc" x1="15.308" x2="15.233" y1="6.335" y2="6.472" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i96765b" x1="13.614" x2="13.433" y1="6.462" y2="6.566" gradientUnits="userSpaceOnUse"><stop class="omvi_7b8z"/><stop offset="1" class="sdnv1bbye"/></linearGradient><linearGradient id="iBBZZqb" x1="17.358" x2="17.539" y1="4.301" y2="4.196" gradientUnits="userSpaceOnUse"><stop offset=".548" class="mgndy_7wh"/><stop offset="1" class="d17gwbfhj"/></linearGradient><filter id="iod8h7b" width="8.471" height="7.176" x="17.558" y="3.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.517647 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22979"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.619608 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22979" result="effect2_innerShadow_3987_22979"/></filter><filter id="iDJlQ8a" width="18.187" height="14.194" x="8.244" y="2.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22979"/></filter><filter id="io2kCEn" width="4.793" height="2.27" x="19.515" y="28.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.188235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22979"/></filter><filter id="iLTpvxc" width="8.989" height="12.477" x="13.498" y="16.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.635294 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22979"/></filter><filter id="igdrE2d" width="7.553" height="7.567" x="15.688" y="3.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.556863 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22979"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.556863 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22979" result="effect2_innerShadow_3987_22979"/></filter><filter id="it67JZX" width="3.395" height="2.909" x="15.65" y="8.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.4 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22979"/></filter><filter id="i4VHrMe" width="1.789" height="3.497" x="9.424" y="12.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22979" stdDeviation=".125"/></filter><filter id="ikpM8Pc" width="2.601" height="13.601" x="19.765" y="15.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22979" stdDeviation=".4"/></filter><filter id="iyyFqDc" width="2.563" height="7.453" x="16.362" y="16.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22979" stdDeviation=".375"/></filter><filter id="ikLeuDc" width="1.619" height="1.419" x="13.515" y="6.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22979"/></filter><filter id="iHAJGOd" width="1.845" height="1.845" x="13.301" y="6.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22979" stdDeviation=".25"/></filter><filter id="iMoGted" width="1.669" height="1.669" x="17.015" y="4.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22979"/></filter><filter id="ixysILe" width="1.845" height="1.845" x="16.801" y="4.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22979" stdDeviation=".25"/></filter><filter id="iX2mIkb" width="2.275" height="2.632" x="15.082" y="5.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22979" stdDeviation=".375"/></filter><filter id="iCHo8Ge" width="1.115" height="1.325" x="15.665" y="5.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22979" stdDeviation=".05"/></filter><filter id="iX2Vepd" width=".373" height=".474" x="16.291" y="5.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22979" stdDeviation=".05"/></filter><filter id="iGNWKhe" width=".617" height=".617" x="16.565" y="5.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22979" stdDeviation=".1"/></filter><filter id="iilWDab" width=".671" height=".659" x="14.917" y="6.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22979" stdDeviation=".1"/></filter><filter id="i1ZHOZc" width=".426" height=".494" x="14.689" y="6.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22979" stdDeviation=".05"/></filter><filter id="ikvIUQJ" width="1.354" height=".852" x="15.758" y="4.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.211765 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22979"/></filter><filter id="iUnsbsb" width="1.167" height="1.164" x="13.963" y="5.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.211765 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22979"/></filter><filter id="iv9mSLd" width="4.106" height="2.64" x="13.2" y="3.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.396078 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22979"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-golfing-medium-light" /></template>
<style>
.a14qj5b2p {
  d: path("M16.543 5.454c.041.018.014.084-.017.157c-.032.074-.056.127-.098.11c-.04-.018-.049-.093-.017-.166c.031-.074.09-.119.132-.101");
}

.a7xagmxua {
  stop-color: var(--svg-color--1a7ccc, #1A7CCC);
  stop-opacity: 0;
}

.acuzwsbvu {
  fill: var(--svg-color--000, #000);
  d: path("M16.528 5.806a.216.216 0 0 1 .08-.295a.216.216 0 0 1 .324.177l-.331.192a.2.2 0 0 1-.073-.074");
}

.afeoc7jzt {
  stop-color: var(--svg-color--daa994, #DAA994);
}

.ag8ecac8l {
  d: path("M16.982 5.486a.35.35 0 0 0-.182-.12l-.035.159l.091.058z");
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.ajgu03mkq {
  width: 0.737px;
  height: 1.252px;
  x: 23.314px;
  y: 4.404px;
  rx: 0.369px;
}

.azn0z--js {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
  stop-opacity: 0;
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.ba1yb3bji {
  stop-color: var(--svg-color--a99797, #A99797);
}

.ben4f0bqs {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
  stop-opacity: 0;
}

.biiy2vbjw {
  width: 0.692px;
  height: 1.157px;
  x: 22.941px;
  y: 3.627px;
  rx: 0.346px;
}

.blekadc8f {
  stop-color: var(--svg-color--30a2e5, #30A2E5);
}

.bpaiimy_w {
  cx: 14.902px;
  cy: 6.495px;
  rx: 0.165px;
  ry: 0.084px;
}

.bq7w62n5j {
  stop-color: var(--svg-color--482a5b, #482A5B);
}

.br5umybnw {
  stop-color: var(--svg-color--366bc5, #366BC5);
  stop-opacity: 0;
}

.bw1hkxbcb {
  stop-color: var(--svg-color--2d9de0, #2D9DE0);
}

.c6xk9jx7z {
  stop-color: var(--svg-color--1b96dc, #1B96DC);
}

.chayuvnap {
  stop-color: var(--svg-color--1d78b8, #1D78B8);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cms6m9u9x {
  d: path("M10.286 12.985a.35.35 0 0 0-.125.474l.88 1.545a1 1 0 0 1-.374 1.364l-.115.065a1 1 0 0 1-1.363-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.25l.342-.196l16.304-9.709a.4.4 0 0 1 .548.14l.102.171a.4.4 0 0 1-.139.548z");
}

.czem1g9ht {
  d: path("m17.487 23.649l-.375-5.953l1.063.5v5.453z");
}

.d17gwbfhj {
  stop-color: var(--svg-color--ffdbac, #FFDBAC);
}

.d1gs3_bfs {
  stop-color: var(--svg-color--d8ab92, #D8AB92);
}

.ddjhanboc {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
}

.dhem-xbnm {
  stop-color: var(--svg-color--442563, #442563);
}

.dkqztxbmt {
  cx: 17.724px;
  cy: 5.247px;
  r: 0.422px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.dl4ua154c {
  stop-color: var(--svg-color--cd917e, #CD917E);
}

.ds3hm--8v {
  stop-color: var(--svg-color--533d66, #533D66);
}

.dsumrvbgt {
  stop-color: var(--svg-color--615273, #615273);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ebs2-pbbe {
  stop-color: var(--svg-color--9c8cad, #9C8CAD);
  stop-opacity: 0;
}

.ehevujb0f {
  cx: 14.224px;
  cy: 7.268px;
  r: 0.709px;
}

.eu9ex6b_l {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.786 6.242a.59.59 0 0 0-.273.677c.02.073.105.106.17.068l.82-.473a.098.098 0 0 0 .026-.148a.595.595 0 0 0-.743-.124");
}

.eupzhi8eb {
  stop-color: var(--svg-color--cf9a7f, #CF9A7F);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.fka-wz-bu {
  stop-color: var(--svg-color--e4b79d, #E4B79D);
  stop-opacity: 0;
}

.fn7-6xayh {
  stop-color: var(--svg-color--3e82bc, #3E82BC);
}

.ft5dv1b6b {
  fill: none;
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gbmz9tkck {
  stop-color: var(--svg-color--cb8e88, #CB8E88);
  stop-opacity: 0;
}

.ggughpb3d {
  stop-color: var(--svg-color--a599b3, #A599B3);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx_ogt9nw {
  cx: 14.902px;
  cy: 6.495px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.165px;
  ry: 0.084px;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.gyzb8obwr {
  stop-color: var(--svg-color--cf9b89, #CF9B89);
}

.h4wmweawy {
  fill: var(--svg-color--000, #000);
  d: path("M15.297 6.518a.216.216 0 0 0-.296-.08a.216.216 0 0 0-.009.37l.332-.191a.2.2 0 0 0-.027-.1");
}

.h8hiq33uv {
  stop-color: var(--svg-color--271938, #271938);
  stop-opacity: 0;
}

.hd06b2knh {
  stop-color: var(--svg-color--a89eb3, #A89EB3);
}

.hg53hdc5j {
  d: path("m13.633 6.911l-.497-.86l.44-.255a.8.8 0 0 1-.01.344a.5.5 0 0 0 .06.36l.295.511c-.098.057-.224.02-.288-.1");
}

.hnewum4zo {
  stop-color: var(--svg-color--2f89b9, #2F89B9);
}

.i42zc8m6u {
  stop-color: var(--svg-color--615273, #615273);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
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

.injufkbna {
  stroke: var(--svg-color--c3b8c3, #C3B8C3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M9.847 13.008a.53.53 0 0 0 0 .54c.131.237.719 1.277.96 1.714c.05.103.112.356-.038.543");
}

.irk4y6bhp {
  d: path("M14.458 2.707c.53-.306 1.128-.44 1.692-.237c.433.157.898.639 1.155 1.323a3 3 0 0 0-.972-.08a3.72 3.72 0 0 0-2.717 1.568a2.9 2.9 0 0 0-.416.882c-.466-.569-.649-1.208-.568-1.662c.106-.59.521-1.04 1.05-1.346z");
}

.j_l_30buh {
  stop-color: var(--svg-color--5d5467, #5D5467);
}

.j297-pbqp {
  stop-color: var(--svg-color--2f89b9, #2F89B9);
  stop-opacity: 0;
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j74nwzkwd {
  width: 0.692px;
  height: 1.157px;
  x: 21.988px;
  y: 4.133px;
  fill: var(--svg-color--c69270, #C69270);
  rx: 0.346px;
}

.jjpmu-56c {
  stop-color: var(--svg-color--4199e0, #4199E0);
}

.joiz9mbyc {
  fill: var(--svg-color--afa2b8, #AFA2B8);
  d: path("M10.286 12.985a.35.35 0 0 0-.125.474l.88 1.545a1 1 0 0 1-.374 1.364l-.115.065a1 1 0 0 1-1.363-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.25l.342-.196l16.304-9.709a.4.4 0 0 1 .548.14l.102.171a.4.4 0 0 1-.139.548z");
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jy7-vab8i {
  d: path("M14.92 6.298a.38.38 0 0 0-.076.597l.633-.366a.38.38 0 0 0-.557-.231");
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
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

.kvw1hrrrt {
  d: path("m17.737 4.542l-.497-.861l-.44.254a.8.8 0 0 0 .303.163a.5.5 0 0 1 .282.232l.277.521a.22.22 0 0 0 .075-.31");
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzgmzb5t {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lbg18dbij {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.844 6.273l.059.8c.037.15.2.226.328.153l.27-.157c.128-.073.142-.255.032-.36l-.544-.52c-.12-.115-.184-.078-.145.084");
}

.ldm9khd7d {
  stop-color: var(--svg-color--4199e0, #4199E0);
  stop-opacity: 0;
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhwrmw8_g {
  d: path("M20.655 6.086a.5.5 0 0 0-.015-.253a5 5 0 0 0-.227-.524c-.02-.088-.025-.29.11-.39a.36.36 0 0 1 .335-.055a.45.45 0 0 1 .207-.285c.135-.072.298-.03.364 0c.018-.067.09-.209.23-.246a.52.52 0 0 1 .356.058c.04-.075.168-.224.359-.215c.238.012.375.262.41.45c.035.187.094.433.152.578c.059.144.118.605-.09 1.199c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.082a1.1 1.1 0 1 1-.193-2.191c.636-.056 1.522-.243 2.304-.744c.682-.437 1.327-1.135 1.659-2.317");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lr97j31fb {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.m3zm84h0u {
  fill: var(--svg-color--6f3e2f, #6F3E2F);
  fill-rule: evenodd;
  d: path("M16.074 4.925c.25-.177.48-.172.543-.158a.2.2 0 0 0 .088-.391c-.173-.039-.519-.022-.863.222a.2.2 0 0 0 .232.327");
}

.m8axnuzwu {
  fill: var(--svg-color--d5a284, #D5A284);
  d: path("M20.655 6.086a.5.5 0 0 0-.015-.253a5 5 0 0 0-.227-.524c-.02-.088-.025-.29.11-.39a.36.36 0 0 1 .335-.055a.45.45 0 0 1 .207-.285c.135-.072.298-.03.364 0c.018-.067.09-.209.23-.246a.52.52 0 0 1 .356.058c.04-.075.168-.224.359-.215c.238.012.375.262.41.45c.035.187.094.433.152.578c.059.144.118.605-.09 1.199c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.082a1.1 1.1 0 1 1-.193-2.191c.636-.056 1.522-.243 2.304-.744c.682-.437 1.327-1.135 1.659-2.317");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgndy_7wh {
  stop-color: var(--svg-color--fdcb9e, #FDCB9E);
}

.mhb206blg {
  d: path("M15.388 6.414c-.062-.106-.189-.127-.224-.135l-.047.164l.142.095z");
}

.mtjlhkzpv {
  fill: var(--svg-color--9785a9, #9785A9);
  d: path("M15.86 24.042a1 1 0 0 0 .274-.712l-.166-7.29h6.02l-.313 12.476H19.52l-.26-10.002a.255.255 0 0 0-.508-.005c-.05 1.196-.13 3.455-.13 4.585c0 1.213-.693 2.214-1.04 2.563l-2.472 2.287a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.719-.424c-.252-.225-.438-.553-.546-.795a.36.36 0 0 1 .077-.392z");
}

.my1tdgbin {
  d: path("M17.339 8.965a2.8 2.8 0 0 0 .847-.215l.86 2.196c-.235.12-1.715.594-2.54.43c-.824-.165-1.019-1.196-.73-1.739c.274-.61 1.118-.63 1.563-.672");
}

.n4g176b3c {
  stop-color: var(--svg-color--b5827d, #B5827D);
  stop-opacity: 0;
}

.n9y8__b1h {
  stop-color: var(--svg-color--cf9b80, #CF9B80);
}

.nav-8e2lo {
  stop-color: var(--svg-color--3386c4, #3386C4);
  stop-opacity: 0;
}

.nbba5kb5p {
  stop-color: var(--svg-color--ac6061, #AC6061);
}

.no0_3dbdi {
  stop-color: var(--svg-color--53aff7, #53AFF7);
}

.nyvmdac6c {
  d: path("M12.933 27.883c0-.806.458-1.159.687-1.234l1.367 1.18v1.283a.5.5 0 0 0 .188.39l.203.163c.127.093.297.238.25.414c-.082.171-.25.195-.54.195h-1.505a.65.65 0 0 1-.65-.65z");
}

.nzyye1byl {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.77 6.236l.165.738a.23.23 0 0 0 .34.146l.289-.167a.23.23 0 0 0 .043-.367l-.556-.512c-.122-.114-.317-.002-.281.162");
}

.o_lkstboy {
  fill: var(--svg-color--6f3e2f, #6F3E2F);
  fill-rule: evenodd;
  d: path("M14.763 5.682c-.278.128-.389.329-.408.39a.2.2 0 1 1-.383-.119c.053-.168.24-.46.624-.636a.2.2 0 1 1 .167.365");
}

.o2ca957_x {
  stop-color: var(--svg-color--1a7ccc, #1A7CCC);
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omvi_7b8z {
  stop-color: var(--svg-color--e4ad8a, #E4AD8A);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.ouoib-wwx {
  cx: 17.724px;
  cy: 5.248px;
  r: 0.709px;
}

.p3yd_be1u {
  stop-color: var(--svg-color--a49faa, #A49FAA);
  stop-opacity: 0;
}

.pcvpzjboo {
  stop-color: var(--svg-color--937da8, #937DA8);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
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

.qh4fa-z4p {
  stop-color: var(--svg-color--9e7282, #9E7282);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rgvdret3u {
  cx: 17.724px;
  cy: 5.247px;
  r: 0.422px;
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s2j02zbkr {
  stop-color: var(--svg-color--655e6d, #655E6D);
  stop-opacity: 0;
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sdnv1bbye {
  stop-color: var(--svg-color--f1ba95, #F1BA95);
}

.seeiowbir {
  stop-color: var(--svg-color--482c58, #482C58);
}

.stmatkb5e {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.545 5.227a.59.59 0 0 1 .723.101a.116.116 0 0 1-.026.182l-.82.474a.098.098 0 0 1-.142-.052a.59.59 0 0 1 .265-.705");
}

.sylx2mbjo {
  stop-color: var(--svg-color--3386c4, #3386C4);
}

.t-eeezbdl {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
  stop-opacity: 0;
}

.t0x3luqrl {
  d: path("M15.86 24.042a1 1 0 0 0 .274-.712l-.166-7.29h6.02l-.313 12.476H19.52l-.26-10.002a.255.255 0 0 0-.508-.005c-.05 1.196-.13 3.455-.13 4.585c0 1.213-.693 2.214-1.04 2.563l-2.472 2.287a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.719-.424c-.252-.225-.438-.553-.546-.795a.36.36 0 0 1 .077-.392z");
}

.t37supbyn {
  fill: var(--svg-color--47385d, #47385D);
  d: path("M12.933 27.883c0-.806.458-1.159.687-1.234l1.367 1.18v1.283a.5.5 0 0 0 .188.39l.203.163c.127.093.297.238.25.414c-.082.171-.25.195-.54.195h-1.505a.65.65 0 0 1-.65-.65z");
}

.tesa8u_3j {
  stop-color: var(--svg-color--3083ea, #3083EA);
}

.truekjbvb {
  stop-color: var(--svg-color--347fda, #347FDA);
}

.tw6dxpb7y {
  stop-color: var(--svg-color--482c58, #482C58);
  stop-opacity: 0;
}

.uoxjyextx {
  d: path("M13.617 5.28a2.9 2.9 0 0 0-.417.883l.259.1a.43.43 0 0 0 .523-.179c.19-.315.566-.811 1.224-1.191a3.4 3.4 0 0 1 1.643-.464a.425.425 0 0 0 .414-.361l.042-.275a3 3 0 0 0-.972-.08a3.72 3.72 0 0 0-2.716 1.568");
}

.uu7_gub8n {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
  stop-opacity: 0;
}

.uw0kegb-q {
  stop-color: var(--svg-color--4195cb, #4195CB);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v__i2ebru {
  stop-color: var(--svg-color--579fde, #579FDE);
}

.v_rk8pcnx {
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M21.16 16.711L20.971 27.9");
}

.v2g8x4brb {
  stop-color: var(--svg-color--246c9d, #246C9D);
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v8crsob7z {
  d: path("m15.77 6.236l.165.738a.23.23 0 0 0 .34.146l.289-.167a.23.23 0 0 0 .043-.367l-.556-.512c-.122-.114-.317-.002-.281.162");
}

.vkrof_bbk {
  stop-color: var(--svg-color--271938, #271938);
}

.vlsksmbwa {
  stop-color: var(--svg-color--e4b79d, #E4B79D);
}

.vm3938bqq {
  d: path("m23.103 5.352l-.5-.866l3.121-1.859a.4.4 0 0 1 .548.14l.103.171a.4.4 0 0 1-.14.548z");
}

.w-05y9s8i {
  d: path("M16.527 5.37a.38.38 0 0 1 .555.232l-.634.366a.38.38 0 0 1 .078-.598");
}

.w0po07knh {
  d: path("M13.624 6.54c-.057-.099-.127-.264-.082-.369L13.47 6c.054-.136.178-.111.11-.229l-.182-.314a.22.22 0 0 1 .045-.287a7 7 0 0 1 1.35-.989c.71-.41 1.26-.597 1.531-.675a.244.244 0 0 1 .271.105l.182.314c.068.118-.185-.519-.06-.486c.259.023.668.821.74.982c.315.697.68 1.376 1.017 2.062c.317.685.067 1.434-.543 1.787l-1.181.682c-.63.363-1.385.194-1.82-.423c-.435-.637-.92-1.32-1.306-1.99");
}

.w5oxhdc5r {
  stop-color: var(--svg-color--7f5d9d, #7F5D9D);
}

.we0trlbug {
  stop-color: var(--svg-color--246c9d, #246C9D);
  stop-opacity: 0;
}

.wn-t5ndzy {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
}

.wu_f8xbqm {
  stop-color: var(--svg-color--cf9b89, #CF9B89);
  stop-opacity: 0;
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x0q6gbiik {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.243 7.034a.11.11 0 0 0-.08-.114a.115.115 0 0 0-.13.05a1.2 1.2 0 0 1-.422.398c-.18.104-.373.159-.557.167a.115.115 0 0 0-.107.089a.11.11 0 0 0 .06.125m1.236-.715l-.05-.003zm0 0a.85.85 0 0 1-.428.688a.85.85 0 0 1-.809.027m0 0l.022-.045m-.022.045l.022-.045m0 0a.8.8 0 0 0 .762-.025a.8.8 0 0 0 .403-.648c.004-.066-.082-.09-.117-.035a1.3 1.3 0 0 1-.44.415a1.3 1.3 0 0 1-.58.174c-.065.003-.086.091-.028.119Z");
}

.x2-43ybrg {
  width: 0.692px;
  height: 1.157px;
  x: 22.422px;
  y: 3.873px;
  rx: 0.346px;
}

.x2horqbll {
  width: 0.692px;
  height: 1.157px;
  x: 23.51px;
  y: 3.373px;
  rx: 0.346px;
}

.x6ukpnq0x {
  fill: var(--svg-color--4c3765, #4C3765);
  d: path("M19.515 30.274v-1.77h2.16c.164.157.789.551 1.504.782c.494.13.625.488.629.62v.368z");
}

.x9_x14ckq {
  stop-color: var(--svg-color--3090bc, #3090BC);
  stop-opacity: 0;
}

.xhu8yhbcw {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
  stop-opacity: 0;
}

.xi8fv135v {
  stop-color: var(--svg-color--8c7e97, #8C7E97);
  stop-opacity: 0;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xk1kgabub {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.543 5.454c.041.018.014.084-.017.157c-.032.074-.056.127-.098.11c-.04-.018-.049-.093-.017-.166c.031-.074.09-.119.132-.101");
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y123f7bnt {
  d: path("M15.265 9.93c.175-1.285.703-1.862 1-2.07c.51-.358 1.664-.945 3.336 0c1.757 1.094 2.403 4.057 2.375 5.375v2.805h-6v-3.243c0-.487-.106-.742-.258-.96c-.145-.258-.52-.981-.453-1.907");
}

.y6ovumr8k {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ydllxhbat {
  stop-color: var(--svg-color--4195cb, #4195CB);
  stop-opacity: 0;
}

.ynlfw99ba {
  stop-color: var(--svg-color--403451, #403451);
}

.yrm14tb3b {
  stop-color: var(--svg-color--579fde, #579FDE);
  stop-opacity: 0;
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z09wjwb_u {
  cx: 14.224px;
  cy: 7.268px;
  r: 0.422px;
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zksl5ybvj {
  fill-rule: evenodd;
  d: path("M22.299 7.875c.852-1.082.48-2.214.219-2.678l1.915-1.081c.468.828 1.242 3.027-.406 5.12c-.89 1.13-2.33 1.566-3.484 1.752c-1.198.194-2.37.159-2.985.135l.085-2.198c.598.023 1.583.047 2.55-.109c1.012-.163 1.746-.484 2.106-.941");
}

.zn47ozbfv {
  stop-color: var(--svg-color--442563, #442563);
  stop-opacity: 0;
}

.zr-3xsbrq {
  stop-color: var(--svg-color--d6a791, #D6A791);
}

</style>
