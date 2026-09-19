<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iIyl9Ie)" class="ll39o_7de"/><path fill="url(#i5LqDUI)" class="ll39o_7de"/><path fill="url(#iHAfSEe)" class="ll39o_7de"/><path class="up8ywcc5j"/><path fill="url(#iO3hjnP)" class="t_uq6pn2h"/><path fill="url(#iZ40ErT)" class="t_uq6pn2h"/><path class="tx662bcvj"/><path fill="url(#iXY1gts)" class="l4-zx3buw"/><path fill="url(#iYWGfDc)" class="l4-zx3buw"/><path fill="url(#ip6mf6V)" class="l4-zx3buw"/><path fill="url(#ioyJnrb)" class="w3llp9bwu"/><path fill="url(#ifN2P3c)" class="w3llp9bwu"/><path fill="url(#ipSSMPb)" class="w3llp9bwu"/><path fill="url(#iwLUFcb)" class="w3llp9bwu"/><g filter="url(#iouTNNG)"><path class="koldj1bih"/><path fill="url(#iHnpHlc)" class="q06v_ac2t"/></g><path clip-rule="evenodd" class="wmtydzqlk"/><path fill="url(#ixfpLCg)" clip-rule="evenodd" class="wzmt_shlt"/><path fill="url(#iB22kBc)" clip-rule="evenodd" class="wzmt_shlt"/><path fill="url(#iakuMAR)" clip-rule="evenodd" class="wzmt_shlt"/><path fill="url(#iS1MiWb)" transform="rotate(-23.31 14.437 7.554)" class="j30pdwb9j"/><path class="kw0qok4ha"/><path fill="url(#iXWaNod)" class="vcgc_7n5n"/><path fill="url(#isshO3a)" class="vcgc_7n5n"/><path fill="url(#iL8Qr8b)" class="vcgc_7n5n"/><path fill="url(#i41ENic)" class="vcgc_7n5n"/><path fill="url(#ii9sBBb)" class="vcgc_7n5n"/><path fill="url(#iZ7CWhd)" class="vcgc_7n5n"/><path fill="url(#iWcypnb)" class="ojo9_8bou"/><path fill="url(#i9Q31Hc)" class="ojo9_8bou"/><path fill="url(#ioyc22G)" class="ojo9_8bou"/><path fill="url(#iRoPwKd)" class="ojo9_8bou"/><path class="d3202nbxn"/><path fill="url(#iPy177d)" class="b5peujhov"/><path fill="url(#iO1RVye)" class="b5peujhov"/><path fill="url(#iBNWcJe)" class="b5peujhov"/><path class="k_wr30omb"/><path fill="url(#iBXFkDc)" class="k21xm4zsk"/><path fill="url(#iYrXpQb)" class="k21xm4zsk"/><path fill="url(#iYJzBXT)" class="k21xm4zsk"/><path fill="url(#ibHSNxc)" class="k21xm4zsk"/><path fill="url(#iHEyDic)" class="k21xm4zsk"/><g filter="url(#ibK94id)"><path clip-rule="evenodd" class="e_-bj170m"/></g><path fill="url(#iFt6x1c)" clip-rule="evenodd" class="xd3kcnojh"/><path fill="url(#ilvIgCe)" clip-rule="evenodd" class="xd3kcnojh"/><path class="hjkyp5bbk"/><path fill="url(#i79bYhb)" class="t2q7syb4f"/><path fill="url(#iq2RKGf)" class="t2q7syb4f"/><path fill="url(#i8Bfipd)" class="t2q7syb4f"/><rect fill="url(#iMHzPBi)" transform="rotate(16.21 22.95 4.932)" class="afl3mih6w"/><path fill="url(#ibbWftc)" class="fwmix8k-g"/><path fill="url(#iYIKPjd)" class="zkare186v"/><path fill="url(#iPmttud)" class="zkare186v"/><path fill="url(#ieRdUjb)" class="a3v1zdu3p"/><path fill="url(#ihVdzwc)" class="a3v1zdu3p"/><path fill="url(#iOkV2Ab)" class="sndh5ym9k"/><path fill="url(#iIFebbd)" class="ml_xz_dbm"/><path fill="url(#iIzKpoc)" class="ml_xz_dbm"/><path fill="url(#itIoHjd)" class="ml_xz_dbm"/><path fill="url(#iaUquye)" class="ml_xz_dbm"/><path fill="url(#i7USqqc)" class="ml_xz_dbm"/><g filter="url(#iZg4Hec)"><rect class="tilkd6bdy"/></g><path fill="url(#itvgxbp)" class="v-e6yx7ro"/><path fill="url(#iOM1Rxd)" class="v-e6yx7ro"/><g filter="url(#iz7164b)"><path fill="url(#i4FWAIe)" class="sslsiw24o"/><path fill="url(#iSLVUAd)" class="sslsiw24o"/><path fill="url(#iG6Mu8c)" class="sslsiw24o"/><path fill="url(#iYyfRpb)" class="sslsiw24o"/></g><g filter="url(#ilNJiac)"><path fill="url(#i6H74eb)" class="uhaouyb-v"/><path fill="url(#i7i9iVd)" class="uhaouyb-v"/><path fill="url(#ibqA7bd)" class="uhaouyb-v"/><path fill="url(#ieze68c)" class="uhaouyb-v"/></g><path fill="url(#iHF8JQd)" class="hl593uytm"/><path fill="url(#i0OcYHd)" class="hl593uytm"/><path fill="url(#iSgSz7b)" class="hl593uytm"/><path clip-rule="evenodd" class="kwjnhuu0c"/><g filter="url(#iq89d7c)"><path clip-rule="evenodd" class="i1bg25y_h"/></g><path class="xa1w23e0e"/><path fill="url(#iMNozgc)" class="apo6xfo9z"/><path fill="url(#iSHJoNU)" class="hlg689dcp"/><ellipse fill="url(#iENZmVd)" transform="rotate(24.61 13.275 5.526)" class="p7bl-gb0a"/><g filter="url(#iGbRVkp)"><path fill="url(#iEhYjUb)" class="ap4pzg46p"/></g><defs><radialGradient id="iXY1gts" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 1.76562 -1.4243 .35293 19.387 21.335)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="q1pop7b3p"/><stop offset="1" class="hprqurbri"/></radialGradient><radialGradient id="iYWGfDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 19.34 21.82)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="yh8khw6sg"/><stop offset="1" class="oatqfqb0v"/></radialGradient><radialGradient id="ip6mf6V" cx="0" cy="0" r="1" gradientTransform="matrix(.60156 2.5625 -1.184 .27795 17.004 22.023)" gradientUnits="userSpaceOnUse"><stop class="k5h4lpbsq"/><stop offset="1" class="rk193sb3z"/></radialGradient><radialGradient id="ioyJnrb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 13.286 19.055)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="xyj5utbpv"/><stop offset="1" class="q0o1m355n"/></radialGradient><radialGradient id="ifN2P3c" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 11.068 7.893)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wwwuk1sex"/><stop offset="1" class="eigwz2byp"/></radialGradient><radialGradient id="ipSSMPb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.574 21.336)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="omib1tb9q"/><stop offset="1" class="z-vlbvbbc"/></radialGradient><radialGradient id="iHnpHlc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 17.074 19.323)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="ixfpLCg" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.67 4.112)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="pjqvhnbjs"/><stop offset="1" class="wcx06_c5w"/><stop offset="1" class="ffhvjce4r"/></radialGradient><radialGradient id="iB22kBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 11.386 11.352)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="zvwwfcbef"/><stop offset=".952" class="hiik07xes"/></radialGradient><radialGradient id="iakuMAR" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 11.09 11.305)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="wvbuym-2v"/><stop offset="1" class="w8z0zbc1w"/></radialGradient><radialGradient id="iS1MiWb" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 15.426 8.883)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="c7ppc0bow"/><stop offset=".811" class="yia_fgb_n"/></radialGradient><radialGradient id="iXWaNod" cx="0" cy="0" r="1" gradientTransform="matrix(.0293 -5.32953 3.38376 .0186 15.275 17.011)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="ioo6anwhf"/><stop offset="1" class="vly_b_ldb"/></radialGradient><radialGradient id="isshO3a" cx="0" cy="0" r="1" gradientTransform="rotate(102.351 2.148 11.58)scale(5.84509 2.29049)" gradientUnits="userSpaceOnUse"><stop class="d66h0_v2y"/><stop offset="1" class="d3t9wcc9u"/></radialGradient><radialGradient id="iL8Qr8b" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 9.19 7.328)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="yx3aab4wz"/><stop offset="1" class="d2ptywb0c"/></radialGradient><radialGradient id="i41ENic" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.868 10.11)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="e_wvtt-qm"/><stop offset="1" class="f0_sezbyw"/></radialGradient><radialGradient id="ii9sBBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.68752 -3.28125 6.32584 -1.32545 16.043 16.805)" gradientUnits="userSpaceOnUse"><stop class="c1n-4t3te"/><stop offset="1" class="uol2-ibpf"/></radialGradient><radialGradient id="iZ7CWhd" cx="0" cy="0" r="1" gradientTransform="rotate(-27.758 30.486 -29.765)scale(2.0129 1.58718)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="pk-0hnbkq"/><stop offset="1" class="ng31r5btx"/></radialGradient><radialGradient id="i9Q31Hc" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 7.135 29.479)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iRoPwKd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.522 11.83)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iBXFkDc" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.584 16.871)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="iYrXpQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.895 22.343)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iYJzBXT" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.633 17.667)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="iHEyDic" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 14.164 16.883)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="ilvIgCe" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 12.092 6.931)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="aneywjt_w"/><stop offset="1" class="idx-0ob_q"/></radialGradient><radialGradient id="iq2RKGf" cx="0" cy="0" r="1" gradientTransform="rotate(22.667 -16.766 42.798)scale(1.2949 2.1866)" gradientUnits="userSpaceOnUse"><stop class="hhyc553gq"/><stop offset="1" class="ss0-anvgm"/></radialGradient><radialGradient id="i8Bfipd" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 20.116 9.46)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gtma0og_l"/><stop offset="1" class="yf8z_2acj"/></radialGradient><radialGradient id="iOkV2Ab" cx="0" cy="0" r="1" gradientTransform="matrix(1 .46565 -.39135 .84043 8.25 11.938)" gradientUnits="userSpaceOnUse"><stop class="bs8v5pbps"/><stop offset="1" class="cegpmmg6d"/></radialGradient><radialGradient id="iIFebbd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 12.064 .165)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="iIzKpoc" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.696 -9.846)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="itIoHjd" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 21.027 3.79)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iaUquye" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.322 3.997)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="i7USqqc" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.835 -4.007)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><radialGradient id="itvgxbp" cx="0" cy="0" r="1" gradientTransform="matrix(.51083 .27635 -.39008 .72106 11.993 6.554)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="hymklqb8k"/><stop offset=".684" class="s2f2c_bct"/></radialGradient><radialGradient id="iOM1Rxd" cx="0" cy="0" r="1" gradientTransform="rotate(-112.383 8.522 -.714)scale(.33794 .50719)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="iSLVUAd" cx="0" cy="0" r="1" gradientTransform="matrix(-.90443 -.05025 .06126 -1.10268 15.918 5.8)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="iG6Mu8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.56055 2.16057 0 12.814 7.073)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="iYyfRpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .41872 -.653 0 13.701 5.85)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="i6H74eb" cx="0" cy="0" r="1" gradientTransform="matrix(2.57995 -2.08801 3.17416 3.922 15.012 4.776)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="i7i9iVd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28677 -.93793 1.50895 2.07017 12.582 3.154)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="ibqA7bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.56108 .1591 -.07818 -.27568 17.763 6.738)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="ieze68c" cx="0" cy="0" r="1" gradientTransform="matrix(.95467 -.2261 .60583 2.55794 15.686 5.147)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="iHF8JQd" cx="0" cy="0" r="1" gradientTransform="matrix(.77881 -.2261 .11036 .38013 15.678 5.675)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="i0OcYHd" cx="0" cy="0" r="1" gradientTransform="matrix(.24222 1.26458 -1.31776 .2524 15.712 5.353)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="iMNozgc" cx="0" cy="0" r="1" gradientTransform="matrix(.2931 0 0 .56945 13.385 5.88)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iSHJoNU" cx="0" cy="0" r="1" gradientTransform="matrix(.26798 0 0 .57992 13.205 5.903)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iIyl9Ie" x1="11.824" x2="10.137" y1="25.648" y2="25.898" gradientUnits="userSpaceOnUse"><stop class="pw3cm8ghn"/><stop offset="1" class="ebr2vqbrv"/></linearGradient><linearGradient id="i5LqDUI" x1="9.391" x2="10.125" y1="23.959" y2="23.818" gradientUnits="userSpaceOnUse"><stop offset=".237" class="hc9rgac9d"/><stop offset="1" class="ax0qocbyt"/></linearGradient><linearGradient id="iHAfSEe" x1="11.746" x2="11.316" y1="22.25" y2="22.352" gradientUnits="userSpaceOnUse"><stop class="m8_menbco"/><stop offset="1" class="t1w1jyb_t"/></linearGradient><linearGradient id="iO3hjnP" x1="23.277" x2="23.219" y1="24.141" y2="22.918" gradientUnits="userSpaceOnUse"><stop class="altl0jb1l"/><stop offset="1" class="frv3_c41o"/></linearGradient><linearGradient id="iZ40ErT" x1="22.656" x2="22.656" y1="21.992" y2="22.902" gradientUnits="userSpaceOnUse"><stop class="ucfba_b5g"/><stop offset="1" class="u745z8b-f"/></linearGradient><linearGradient id="iwLUFcb" x1="11.12" x2="11.12" y1="18.172" y2="19.492" gradientUnits="userSpaceOnUse"><stop class="f_4kl0b7z"/><stop offset="1" class="h30nofb2x"/></linearGradient><linearGradient id="iWcypnb" x1="10.324" x2="11.855" y1="28.461" y2="28.461" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="ioyc22G" x1="9.887" x2="9.887" y1="29.479" y2="29.156" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="iPy177d" x1="25.813" x2="26.409" y1="21.609" y2="22.727" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="iO1RVye" x1="26.062" x2="26.756" y1="24.559" y2="23.693" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="iBNWcJe" x1="27.776" x2="27.384" y1="23.693" y2="23.867" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ibHSNxc" x1="13.796" x2="14.246" y1="16.939" y2="18.006" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="iFt6x1c" x1="21.824" x2="21.637" y1="10.57" y2="9.633" gradientUnits="userSpaceOnUse"><stop offset=".076" class="moe8lybvx"/><stop offset="1" class="gm-u32b5v"/></linearGradient><linearGradient id="i79bYhb" x1="18.667" x2="17.908" y1="11.718" y2="9.008" gradientUnits="userSpaceOnUse"><stop class="r1i9tc3bx"/><stop offset="1" class="c__hzybex"/></linearGradient><linearGradient id="iMHzPBi" x1="25.473" x2="23.476" y1="5.758" y2="5.828" gradientUnits="userSpaceOnUse"><stop class="dks6vbcwf"/><stop offset="1" class="jl_acuvtz"/></linearGradient><linearGradient id="ibbWftc" x1="4.703" x2="8.29" y1="10.969" y2="10.977" gradientUnits="userSpaceOnUse"><stop class="d_zsx_qwu"/><stop offset=".588" class="bq8is6bem"/></linearGradient><linearGradient id="iYIKPjd" x1="4.696" x2="7.259" y1="11.417" y2="11.417" gradientUnits="userSpaceOnUse"><stop class="d_zsx_qwu"/><stop offset=".588" class="bq8is6bem"/></linearGradient><linearGradient id="iPmttud" x1="5.614" x2="5.614" y1="12.05" y2="11.604" gradientUnits="userSpaceOnUse"><stop class="uy_o1rblt"/><stop offset="1" class="sj9ku07pk"/></linearGradient><linearGradient id="ieRdUjb" x1="5.105" x2="7.199" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="d_zsx_qwu"/><stop offset=".547" class="bq8is6bem"/></linearGradient><linearGradient id="ihVdzwc" x1="5.855" x2="5.855" y1="12.633" y2="12.188" gradientUnits="userSpaceOnUse"><stop class="uy_o1rblt"/><stop offset="1" class="sj9ku07pk"/></linearGradient><linearGradient id="i4FWAIe" x1="15.584" x2="12.515" y1="6.596" y2="6.78" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="iSgSz7b" x1="15.619" x2="15.778" y1="5.748" y2="5.761" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="iENZmVd" x1="13.198" x2="13.398" y1="5.485" y2="5.55" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iEhYjUb" x1="16.99" x2="17.467" y1="5.246" y2="2.139" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><filter id="iouTNNG" width="4.141" height="6.811" x="16.361" y="15.474" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23785"/></filter><filter id="ibK94id" width="9.915" height="8.775" x="15.953" y="2.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.533333 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23785"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.635294 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23785" result="effect2_innerShadow_3987_23785"/></filter><filter id="iZg4Hec" width="2.065" height=".799" x="5.024" y="11.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23785" stdDeviation=".15"/></filter><filter id="iz7164b" width="4.748" height="5.612" x="12.315" y="3.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.611765 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23785"/></filter><filter id="ilNJiac" width="5.899" height="5.884" x="12.582" y="1.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23785"/></filter><filter id="iq89d7c" width="1.079" height=".601" x="13.124" y="4.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23785"/></filter><filter id="iGbRVkp" width="2.352" height="3.646" x="16.004" y="2.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23785" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-playing-handball-light" /></template>
<style>
.a3v1zdu3p {
  d: path("M4.955 12.121a.44.44 0 0 1 .44-.44H6.93v.48a.4.4 0 0 1-.4.4H5.395a.44.44 0 0 1-.44-.44");
}

.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.afl3mih6w {
  width: 2.533px;
  height: 1.362px;
  x: 22.95px;
  y: 4.932px;
  rx: 0.2px;
}

.altl0jb1l {
  stop-color: var(--svg-color--c38697, #C38697);
}

.aneywjt_w {
  stop-color: var(--svg-color--f2c9b3, #F2C9B3);
}

.ap4pzg46p {
  d: path("M16.561 4.01c.167.681.265 1.334.297 1.63c.676-.619.932-1.38.995-2.006c.054-.534-.617-.811-1.071-.525c-.328.206-.313.524-.221.901");
}

.apo6xfo9z {
  d: path("M13.737 5.903V5.9c0-.344-.147-.622-.329-.622c-.181 0-.328.278-.328.622v.004z");
}

.ax0qocbyt {
  stop-color: var(--svg-color--fbc0ae, #FBC0AE);
  stop-opacity: 0;
}

.b3jcjo1jv {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
  stop-opacity: 0;
}

.b5peujhov {
  d: path("m26.408 21.575l-1.295.558l.035 1.71c.33.29 1.104 1.066 1.808 1.602c.46.35.894.356 1.192.296c.226-.046.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.118");
}

.bc_6ftbdd {
  stop-color: var(--svg-color--ddd9e2, #DDD9E2);
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.bq8is6bem {
  stop-color: var(--svg-color--e2a493, #E2A493);
}

.bs8v5pbps {
  stop-color: var(--svg-color--d0662d, #D0662D);
}

.c__hzybex {
  stop-color: var(--svg-color--ff813d, #FF813D);
  stop-opacity: 0;
}

.c1n-4t3te {
  stop-color: var(--svg-color--f14a2d, #F14A2D);
}

.c2ukjabcr {
  stop-color: var(--svg-color--4d318d, #4D318D);
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.c7ppc0bow {
  stop-color: var(--svg-color--ce8868, #CE8868);
}

.cegpmmg6d {
  stop-color: var(--svg-color--ca502d, #CA502D);
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.d_zsx_qwu {
  stop-color: var(--svg-color--ffc5af, #FFC5AF);
}

.d2ptywb0c {
  stop-color: var(--svg-color--ff8750, #FF8750);
  stop-opacity: 0;
}

.d3202nbxn {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m26.408 21.575l-1.295.558l.035 1.71c.33.29 1.104 1.066 1.808 1.602c.46.35.894.356 1.192.296c.226-.046.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.118");
}

.d3t9wcc9u {
  stop-color: var(--svg-color--ff9056, #FF9056);
  stop-opacity: 0;
}

.d66h0_v2y {
  stop-color: var(--svg-color--ff9056, #FF9056);
}

.dks6vbcwf {
  stop-color: var(--svg-color--ea8521, #EA8521);
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxjajos_o {
  stop-color: var(--svg-color--f0b5a2, #F0B5A2);
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.e_-bj170m {
  fill: var(--svg-color--e6b6a7, #E6B6A7);
  fill-rule: evenodd;
  d: path("M24.776 3.014c.612.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 0 1-.435-2.26l4.232-.814a1.85 1.85 0 0 0 1.433-1.322l.81-2.916a1.15 1.15 0 0 1 1.415-.8");
}

.e_wvtt-qm {
  stop-color: var(--svg-color--eb784b, #EB784B);
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.ebr2vqbrv {
  stop-color: var(--svg-color--f8bead, #F8BEAD);
}

.eigwz2byp {
  stop-color: var(--svg-color--cf433f, #CF433F);
  stop-opacity: 0;
}

.f_4kl0b7z {
  stop-color: var(--svg-color--d76322, #D76322);
}

.f0_sezbyw {
  stop-color: var(--svg-color--eb784b, #EB784B);
  stop-opacity: 0;
}

.ffhvjce4r {
  stop-color: var(--svg-color--d78c77, #D78C77);
  stop-opacity: 0;
}

.frv3_c41o {
  stop-color: var(--svg-color--e0a8a5, #E0A8A5);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwmix8k-g {
  d: path("M5.084 11.098a.44.44 0 0 1 .44-.44h1.374c.112 0 .54.008.899.147l.11.34l-.404.393H5.524a.44.44 0 0 1-.44-.44");
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gm-u32b5v {
  stop-color: var(--svg-color--d79f9b, #D79F9B);
  stop-opacity: 0;
}

.gtma0og_l {
  stop-color: var(--svg-color--ff985a, #FF985A);
}

.gu4uskbqq {
  stop-color: var(--svg-color--fac1a8, #FAC1A8);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h-bh2_bpf {
  stop-color: var(--svg-color--454143, #454143);
}

.h30nofb2x {
  stop-color: var(--svg-color--d76322, #D76322);
  stop-opacity: 0;
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.hc9rgac9d {
  stop-color: var(--svg-color--ffd2bc, #FFD2BC);
}

.hhyc553gq {
  stop-color: var(--svg-color--ff9459, #FF9459);
}

.hiik07xes {
  stop-color: var(--svg-color--c9878b, #C9878B);
}

.hjkyp5bbk {
  fill: var(--svg-color--ff832d, #FF832D);
  d: path("m20.192 11.138l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
}

.hl593uytm {
  d: path("m15.515 6.61l.214-1.542a.779.779 0 0 1-.214 1.543");
}

.hlg689dcp {
  d: path("m13.528 5.903l.004-.077c0-.2-.085-.36-.188-.36c-.105 0-.189.16-.189.36q0 .04.004.077z");
}

.hprqurbri {
  stop-color: var(--svg-color--ff7839, #FF7839);
  stop-opacity: 0;
}

.hq1ekobkc {
  stop-color: var(--svg-color--e7a792, #E7A792);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.hymklqb8k {
  stop-color: var(--svg-color--ffd4b7, #FFD4B7);
}

.i1bg25y_h {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M13.638 4.796a.8.8 0 0 0-.233-.017a.16.16 0 0 1-.04-.319c.076-.01.2-.006.336.02c.136.028.297.083.437.186a.16.16 0 0 1-.191.259a.8.8 0 0 0-.31-.129");
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.idx-0ob_q {
  stop-color: var(--svg-color--e4b3a0, #E4B3A0);
  stop-opacity: 0;
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.ioo6anwhf {
  stop-color: var(--svg-color--fb643e, #FB643E);
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.j23k_cb2p {
  stop-color: var(--svg-color--9c959a, #9C959A);
  stop-opacity: 0;
}

.j2u_3dtev {
  stop-color: var(--svg-color--908582, #908582);
  stop-opacity: 0;
}

.j30pdwb9j {
  d: path("M14.437 7.554h2.217v3.3h-2.217z");
}

.j96xv6b5h {
  stop-color: var(--svg-color--917ea3, #917EA3);
  stop-opacity: 0;
}

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
}

.jjj62-byh {
  stop-color: var(--svg-color--66638b, #66638B);
}

.jl_acuvtz {
  stop-color: var(--svg-color--d97031, #D97031);
}

.k_wr30omb {
  fill: var(--svg-color--918996, #918996);
  d: path("M18.76 15.154s-4.632 1.786-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.199.277c1.085-.571 2.044-1.03 3.182-1.725c2.04-1.245 1.784-2.567 1.663-3.264c-.105-.605-.491-1.323-.683-1.704");
}

.k21xm4zsk {
  d: path("M18.76 15.154s-4.632 1.786-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.199.277c1.085-.571 2.044-1.03 3.182-1.725c2.04-1.245 1.784-2.567 1.663-3.264c-.105-.605-.491-1.323-.683-1.704");
}

.k5h4lpbsq {
  stop-color: var(--svg-color--e76637, #E76637);
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
}

.koldj1bih {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M17.01 22.285s-.464-1.23-.64-2.274s2.337-4.437 2.337-4.437c.95 1.49 1.295 2.635 1.64 4.012c.209.833.265 1.08-.203 1.539c-.638.568-2.491.982-3.134 1.16");
}

.kw0qok4ha {
  fill: var(--svg-color--f76c2c, #F76C2C);
  d: path("m15.953 8.941l.674-.169c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.255l-4.897 2.074c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.kwjnhuu0c {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.887 7.097a.134.134 0 0 1-.002.19c-.255.25-.624.314-.742.326a.134.134 0 1 1-.027-.267c.1-.01.393-.066.582-.251a.134.134 0 0 1 .19.002");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l4-zx3buw {
  d: path("m17.402 23.516l-.398-1.297l2.906-1.383l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.013-.301.057-.914.125c-1.412.225-2.062-.718-2.21-1.218");
}

.l7mbhnbzh {
  stop-color: var(--svg-color--eeb298, #EEB298);
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.ll39o_7de {
  d: path("m10.074 27.266l-1-5.18l2.57-.477v6.36z");
}

.m5_tnryam {
  stop-color: var(--svg-color--66638b, #66638B);
  stop-opacity: 0;
}

.m8_menbco {
  stop-color: var(--svg-color--d99f98, #D99F98);
}

.mge9r1s9g {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
  stop-opacity: 0;
}

.ml_xz_dbm {
  d: path("M25.013 3.665a2.063 2.063 0 1 1-4.125 0a2.063 2.063 0 0 1 4.125 0");
}

.moe8lybvx {
  stop-color: var(--svg-color--c0858e, #C0858E);
}

.n8gqlhnrc {
  stop-color: var(--svg-color--9583a6, #9583A6);
  stop-opacity: 0;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ne985-vqe {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
  stop-opacity: 0;
}

.ng31r5btx {
  stop-color: var(--svg-color--eb5f1d, #EB5F1D);
  stop-opacity: 0;
}

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
}

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
}

.oatqfqb0v {
  stop-color: var(--svg-color--d74b53, #D74B53);
}

.ojo9_8bou {
  d: path("m7.863 28.188l2.215-1.072l1.574.752l-.014 1.34a.253.253 0 0 1-.251.248l-3.855.023c-.221.001-.418-.15-.395-.37c.046-.452.333-.736.726-.921");
}

.omib1tb9q {
  stop-color: var(--svg-color--fb7640, #FB7640);
  stop-opacity: 0;
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.p7bl-gb0a {
  cx: 13.275px;
  cy: 5.526px;
  rx: 0.069px;
  ry: 0.094px;
}

.pf-fc7btu {
  stop-color: var(--svg-color--454143, #454143);
  stop-opacity: 0;
}

.pjqvhnbjs {
  stop-color: var(--svg-color--d78c77, #D78C77);
}

.pk-0hnbkq {
  stop-color: var(--svg-color--eb5f1d, #EB5F1D);
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.pw3cm8ghn {
  stop-color: var(--svg-color--efbaab, #EFBAAB);
}

.q06v_ac2t {
  d: path("M17.01 22.285s-.464-1.23-.64-2.274s2.337-4.437 2.337-4.437c.95 1.49 1.295 2.635 1.64 4.012c.209.833.265 1.08-.203 1.539c-.638.568-2.491.982-3.134 1.16");
}

.q0o1m355n {
  stop-color: var(--svg-color--fc672b, #FC672B);
}

.q1pop7b3p {
  stop-color: var(--svg-color--ff7839, #FF7839);
}

.q1yj_xkrc {
  stop-color: var(--svg-color--504b8a, #504B8A);
}

.q8c7r9fut {
  stop-color: var(--svg-color--4a4970, #4A4970);
  stop-opacity: 0;
}

.qh9tdvimg {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
}

.qmcjcvbdo {
  stop-color: var(--svg-color--adaaad, #ADAAAD);
  stop-opacity: 0;
}

.r1i9tc3bx {
  stop-color: var(--svg-color--f05c24, #F05C24);
}

.rk193sb3z {
  stop-color: var(--svg-color--e76637, #E76637);
  stop-opacity: 0;
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.s-7nhybnh {
  stop-color: var(--svg-color--a5a3a3, #A5A3A3);
}

.s2f2c_bct {
  stop-color: var(--svg-color--ffc4a7, #FFC4A7);
}

.sew1y7bbn {
  stop-color: var(--svg-color--514d8b, #514D8B);
  stop-opacity: 0;
}

.sj9ku07pk {
  stop-color: var(--svg-color--e7a79b, #E7A79B);
  stop-opacity: 0;
}

.sndh5ym9k {
  d: path("M8.288 11.128a.197.197 0 0 1 .258-.09c.244.112.694.325.974.496c.084.052.107.16.06.246l-1.028 1.907a.186.186 0 0 1-.223.09a4 4 0 0 1-.974-.494a.19.19 0 0 1-.058-.247z");
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.ss0-anvgm {
  stop-color: var(--svg-color--ff9459, #FF9459);
  stop-opacity: 0;
}

.sslsiw24o {
  d: path("M12.545 5.052c.041-.859.32-1.273.45-1.394h4.001l.067 3.391c-.928 2.275-3.764 2.372-4.187 1.55c-.423-.823-.379-2.553-.33-3.547");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t_uq6pn2h {
  d: path("m25.207 23.836l-4.773.703l-.329-2.547l5.215.149z");
}

.t1w1jyb_t {
  stop-color: var(--svg-color--ebb3a8, #EBB3A8);
  stop-opacity: 0;
}

.t2q7syb4f {
  d: path("m20.192 11.138l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
}

.t54cbcb-z {
  stop-color: var(--svg-color--bab6bd, #BAB6BD);
}

.tbe0sc-ij {
  stop-color: var(--svg-color--4a4970, #4A4970);
}

.tilkd6bdy {
  width: 1.465px;
  height: 0.199px;
  x: 5.324px;
  y: 11.813px;
  fill: var(--svg-color--f3baa7, #F3BAA7);
  rx: 0.099px;
}

.tx662bcvj {
  fill: var(--svg-color--ec5d25, #EC5D25);
  d: path("m17.402 23.516l-.398-1.297l2.906-1.383l.203 1.125h.258c.163.9.172 2.14.156 2.648c-.041.013-.301.057-.914.125c-1.412.225-2.062-.718-2.21-1.218");
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.u745z8b-f {
  stop-color: var(--svg-color--e7b8a0, #E7B8A0);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ucfba_b5g {
  stop-color: var(--svg-color--e7b8a0, #E7B8A0);
}

.uhaouyb-v {
  d: path("M12.707 2.53a1.1 1.1 0 0 1 1.055-.62c.921.05 1.047.37 1.88.197c.88-.181 1.315-.129 1.692.042l.007.004c.372.168 1.14.518 1.14 2.09c0 1.449-.516 2.214-.766 2.487l.049.018c.248.09.35.353.26.602c-.076.211-.344.333-.682.28c-.386-.06-.67-.113-.891-.157a.266.266 0 0 1-.214-.262V6.018c0-.502-.355-.802-.511-.892c-.017-.519-.176-.757-.435-.883c-.43-.208-.564-.105-1.592-.168c-1.034-.062-1.31-.891-.992-1.545");
}

.uol2-ibpf {
  stop-color: var(--svg-color--f14a2d, #F14A2D);
  stop-opacity: 0;
}

.up8ywcc5j {
  fill: var(--svg-color--f1bcb0, #F1BCB0);
  d: path("m25.207 23.836l-4.773.703l-.329-2.547l5.215.149z");
}

.uy_o1rblt {
  stop-color: var(--svg-color--e7a79b, #E7A79B);
}

.v-e6yx7ro {
  d: path("M12.305 6.085c.168-.157.254-.392.277-.49h.192v1.206c-.23.147-.56.124-.657-.096c-.084-.189-.021-.423.188-.62");
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vcgc_7n5n {
  d: path("m15.953 8.941l.674-.169c.233-.058.476-.068.713-.03l1.531 2.195c-.643 1.685-.595 3.034-.098 4.255l-4.897 2.074c-.856-2.918-.666-5.398 0-6.556c.597-1.12 1.425-1.581 2.077-1.769");
}

.vly_b_ldb {
  stop-color: var(--svg-color--fb643e, #FB643E);
  stop-opacity: 0;
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vuvc8_ujh {
  stop-color: var(--svg-color--444367, #444367);
  stop-opacity: 0;
}

.vx88q5bse {
  stop-color: var(--svg-color--484083, #484083);
  stop-opacity: 0;
}

.w3llp9bwu {
  d: path("m10.66 18.617l1.016-.445l1.61 2.836l-1.563.469v.421l-2.68.258c-.072-.398-.2-1.251.102-2.015c.335-.849 1.149-1.362 1.516-1.524");
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.w8z0zbc1w {
  stop-color: var(--svg-color--dca489, #DCA489);
  stop-opacity: 0;
}

.wcectbccf {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
}

.wcx06_c5w {
  stop-color: var(--svg-color--ca8571, #CA8571);
  stop-opacity: 0;
}

.wmtydzqlk {
  fill: var(--svg-color--e2a493, #E2A493);
  fill-rule: evenodd;
  d: path("M6.495 11.217a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.406 1.382 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.375-.47-.93-.095-1.441");
}

.wvbuym-2v {
  stop-color: var(--svg-color--dca489, #DCA489);
}

.wwwuk1sex {
  stop-color: var(--svg-color--cf433f, #CF433F);
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
}

.wzmt_shlt {
  fill-rule: evenodd;
  d: path("M6.495 11.217a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.406 1.382 5.633.316a1.15 1.15 0 1 1 .992 2.075c-3.032 1.45-6.187.804-8.137-.703c-.512-.375-.47-.93-.095-1.441");
}

.xa1w23e0e {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.088 5.903h1.06c0-.42-.238-.76-.53-.76s-.53.34-.53.76");
}

.xd3kcnojh {
  fill-rule: evenodd;
  d: path("M24.776 3.014c.612.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 0 1-.435-2.26l4.232-.814a1.85 1.85 0 0 0 1.433-1.322l.81-2.916a1.15 1.15 0 0 1 1.415-.8");
}

.xktf9pbat {
  stop-color: var(--svg-color--564c49, #564C49);
  stop-opacity: 0;
}

.xyj5utbpv {
  stop-color: var(--svg-color--ef6923, #EF6923);
}

.ycb1huo4n {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
}

.yf8z_2acj {
  stop-color: var(--svg-color--ff985a, #FF985A);
  stop-opacity: 0;
}

.yh8khw6sg {
  stop-color: var(--svg-color--d74b53, #D74B53);
  stop-opacity: 0;
}

.yia_fgb_n {
  stop-color: var(--svg-color--daaa94, #DAAA94);
}

.yx3aab4wz {
  stop-color: var(--svg-color--ff8750, #FF8750);
}

.z-vlbvbbc {
  stop-color: var(--svg-color--fb7640, #FB7640);
}

.zkare186v {
  d: path("M4.512 11.538a.44.44 0 0 1 .44-.44H6.93v.88H4.95a.44.44 0 0 1-.44-.44");
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

.zvwwfcbef {
  stop-color: var(--svg-color--db988d, #DB988D);
  stop-opacity: 0;
}

</style>
