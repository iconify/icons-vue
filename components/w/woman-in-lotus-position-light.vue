<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#ixoNXTd)" class="d2kvgvbvc"><path fill="url(#iPeAgEb)" class="la27w1gfo"/><path fill="url(#iR54OOA)" class="la27w1gfo"/><path fill="url(#iD8i6gl)" class="la27w1gfo"/><path fill="url(#iSR7Glb)" class="la27w1gfo"/><path fill="url(#iSuRTtb)" class="la27w1gfo"/><path fill="url(#iSIMc7U)" class="la27w1gfo"/><path fill="url(#i8VPQye)" class="la27w1gfo"/><path fill="url(#i4HayEc)" class="la27w1gfo"/><path fill="url(#iLNmDGQ)" class="la27w1gfo"/><path fill="url(#ikHIfNd)" class="la27w1gfo"/><path fill="url(#iCn7mte)" class="la27w1gfo"/></g><path fill="url(#iRDOnIb)" clip-rule="evenodd" class="a03e9pb6i"/><path fill="url(#iCZ2Hpu)" clip-rule="evenodd" class="sq6qddbed"/><g filter="url(#iqzGHpe)"><path fill="url(#i5yfUMc)" class="r6t5fdb5z"/><path fill="url(#iSgtjHd)" class="r6t5fdb5z"/></g><path fill="url(#iA96PzE)" class="pr4ditbsi"/><path fill="url(#iKu4zId)" class="pr4ditbsi"/><g filter="url(#iLdMENe)"><path class="dlop932ty"/></g><path fill="url(#i7HROGc)" class="qldr0kbme"/><path fill="url(#itiSbzd)" class="qldr0kbme"/><path fill="url(#iyhaOFe)" class="qldr0kbme"/><path fill="url(#iP40qfe)" class="sn5e1_b6a"/><path fill="url(#i8M2ibb)" class="sn5e1_b6a"/><path fill="url(#iISRgKb)" class="sn5e1_b6a"/><path fill="url(#iMzXytv)" class="bvc6mfb7j"/><path fill="url(#ixtAAry)" class="bvc6mfb7j"/><path fill="url(#ihQGM2b)" class="bvc6mfb7j"/><path class="q5ek91bxz"/><path fill="url(#iIzS8Qb)" class="m3g9c93kt"/><path fill="url(#iPoJlVb)" class="m3g9c93kt"/><path fill="url(#ifBJ4Ug)" class="m3g9c93kt"/><g filter="url(#inzXvLb)"><path class="adjv9ubcq"/><path fill="url(#ip9rHpc)" class="s2exfcbyx"/><path fill="url(#irngmHd)" class="s2exfcbyx"/><path fill="url(#i78r8Sc)" class="s2exfcbyx"/></g><g filter="url(#idwOped)"><path fill="url(#ixclxhc)" class="hvkhdmfad"/></g><g filter="url(#i2I4upI)"><path fill="url(#i7VR6Ry)" class="t6ernuw5h"/><path fill="url(#i9Ozx6d)" class="t6ernuw5h"/></g><path fill="url(#iFRyJpb)" class="srj3oq2hf"/><path fill="url(#i0Cd4sb)" class="srj3oq2hf"/><path fill="url(#ivVE2Kd)" class="srj3oq2hf"/><path clip-rule="evenodd" class="dob5rviuo"/><path fill="url(#iNCc64l)" clip-rule="evenodd" class="x3hc4tb4e"/><path clip-rule="evenodd" class="nb1t54bir"/><path fill="url(#iviKZSX)" clip-rule="evenodd" class="gbcyzr76l"/><path clip-rule="evenodd" class="jlleovb-o"/><path fill="url(#i9ky2ne)" clip-rule="evenodd" class="jk4gd0bdm"/><path clip-rule="evenodd" class="otw__cbjw"/><path fill="url(#iTtxXdb)" clip-rule="evenodd" class="cd_2jstni"/><path clip-rule="evenodd" class="gyhpocb3d"/><path fill="url(#i7rFGII)" clip-rule="evenodd" class="jz-6pkbmo"/><path clip-rule="evenodd" class="x40ln-bnj"/><path fill="url(#inQw6Oe)" clip-rule="evenodd" class="nayex6koj"/><path clip-rule="evenodd" class="cm7234atb"/><path fill="url(#iTWRHAb)" clip-rule="evenodd" class="t-vc93b3o"/><path fill="url(#i5mA3oe)" clip-rule="evenodd" class="a4i5n45nj"/><path fill="url(#iiU4zIz)" clip-rule="evenodd" class="a4i5n45nj"/><g filter="url(#iaqFvbc)"><path class="x09w1trwj"/></g><g filter="url(#im77E7y)"><path stroke="url(#icnQwfe)" class="tbpujzqai"/></g><g filter="url(#iVjREns)"><path class="eczhn6bte"/></g><g filter="url(#i5JIIsc)"><path stroke="url(#iW3DxZb)" class="u_pil8u_l"/></g><g filter="url(#iK5Dh6p)"><path class="mp5pacluc"/></g><g filter="url(#isWgKBd)"><path stroke="url(#itlXw6d)" class="dlmr9bcyu"/></g><g filter="url(#isFTO5b)"><path class="uokd_kbwg"/></g><g filter="url(#iGQs7Nc)"><path stroke="url(#iDcX5Qb)" class="b0ry09b4q"/></g><g filter="url(#iZIPvTc)"><path fill="url(#iIZBaqb)" class="xyv86i6rr"/></g><g filter="url(#iQu3LJe)"><path fill="url(#iVl1I9d)" class="f5k7byw5f"/><path fill="url(#iRB4xOe)" class="f5k7byw5f"/></g><g filter="url(#iRec1GS)"><path class="y2xpzibik"/><path fill="url(#ibgF3iS)" class="cpd04gb_d"/></g><g filter="url(#iWXtrgd)"><path class="vz0iqbcsc"/><path fill="url(#iD4J87S)" class="fx1lyxs2a"/></g><g filter="url(#i0Nf7VO)"><path fill="url(#imWB1bb)" class="c6s6khboc"/><path fill="url(#iiup4wk)" class="c6s6khboc"/><path fill="url(#iGQjawc)" class="c6s6khboc"/><path fill="url(#iOVulqe)" class="c6s6khboc"/><path fill="url(#iD1SpWb)" class="c6s6khboc"/><path fill="url(#iHflLid)" class="c6s6khboc"/><path fill="url(#iHWPNxc)" class="c6s6khboc"/></g><path fill="url(#icwzNeK)" class="c6s6khboc"/><path fill="url(#iYcP0Yc)" class="c6s6khboc"/><g filter="url(#isGHXYT)"><path class="oyrh9eprn"/></g><g filter="url(#iOouPhc)"><path class="qfc59fbmm"/><path fill="url(#il12e7b)" class="iwdhkcbmk"/><path fill="url(#iXlv96W)" class="iwdhkcbmk"/><path fill="url(#ig5Xncd)" class="iwdhkcbmk"/><path fill="url(#isqs1me)" class="iwdhkcbmk"/></g><g filter="url(#iINep2d)"><path stroke="url(#itL8jAb)" class="exu9ep_8j"/></g><path class="qyby9eehb"/><g filter="url(#iZILxfe)"><path class="a8liujjia"/></g><g filter="url(#ivORm1b)"><path clip-rule="evenodd" class="fj3_5achs"/></g><g filter="url(#iqLKoQb)"><path class="uxuve9blo"/></g><g filter="url(#itBXGhb)"><path class="jyrzspbah"/></g><g filter="url(#iMGYxpF)"><path class="q_d3v4bll"/><path fill="url(#iyQdtab)" class="i5mi7_b2a"/><path fill="url(#i24VsZc)" class="i5mi7_b2a"/></g><g filter="url(#iF8j2Ub)"><path class="yfooxwfal"/></g><path class="g7tzrok9x"/><g filter="url(#iIE5Frb)"><path class="wpo7vfbqs"/></g><path class="ovwybtw7l"/><g filter="url(#iJ3dYLI)"><path class="umoqnbb7f"/></g><defs><radialGradient id="iR54OOA" cx="0" cy="0" r="1" gradientTransform="matrix(-.3817 2.88392 -3.6026 -.47681 15.829 9.23)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iD8i6gl" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8237 1.22992 -1.61602 -2.3962 14.047 9.4)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iSR7Glb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 4.553 7.095)scale(1.36144 1.0454)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iSuRTtb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 4.797 6.965)scale(1.56564 1.10286)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iSIMc7U" cx="0" cy="0" r="1" gradientTransform="matrix(.86941 1.65402 -2.29603 1.20688 13.793 2.55)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i8VPQye" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.054 6.014)scale(1.28948 1.80203)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="i4HayEc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16624 .33929 -.70756 -2.4321 20.77 7.109)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iLNmDGQ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7812 .44532 -.56727 -2.26897 20.388 9.272)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ikHIfNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57212 -1.67647 1.326 -.45252 19.013 5.57)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iCn7mte" cx="0" cy="0" r="1" gradientTransform="matrix(.95133 .0998 -.16171 1.54143 12.136 7.087)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iRDOnIb" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.343 13.073)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="lsnfobzbz"/><stop offset="1" class="gf6fosb8y"/></radialGradient><radialGradient id="iCZ2Hpu" cx="0" cy="0" r="1" gradientTransform="rotate(174.454 13.31 11.969)scale(.83202 .3356)" gradientUnits="userSpaceOnUse"><stop class="cxkykm1df"/><stop offset="1" class="pgvvb0b4v"/></radialGradient><radialGradient id="i5yfUMc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.158)" gradientUnits="userSpaceOnUse"><stop class="ihlvscyun"/><stop offset="1" class="jr2ezs63s"/></radialGradient><radialGradient id="iSgtjHd" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -6.844 31.605)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="w_0x8cbdi"/><stop offset="1" class="u_uylxu0j"/></radialGradient><radialGradient id="iA96PzE" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.502)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="kaew0_2pl"/><stop offset="1" class="a-cjnzu_f"/></radialGradient><radialGradient id="iKu4zId" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.142)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="z260igbpj"/><stop offset="1" class="qcf9xbgxm"/></radialGradient><radialGradient id="i7HROGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .21875 -.60896 -2.43587 21.294 25.835)" gradientUnits="userSpaceOnUse"><stop class="s_ql7obry"/><stop offset="1" class="zpmzd2b_c"/></radialGradient><radialGradient id="itiSbzd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.7705 1.76305 5.29137 5.576 25.71)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="f7iqbccaz"/><stop offset="1" class="ygetoyo1j"/></radialGradient><radialGradient id="iyhaOFe" cx="0" cy="0" r="1" gradientTransform="matrix(.67187 .90625 -1.49816 1.1107 7.232 23.845)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="jvt0tewya"/><stop offset="1" class="lpv9r5l0o"/></radialGradient><radialGradient id="iP40qfe" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.064)" gradientUnits="userSpaceOnUse"><stop class="w20zx1b6w"/><stop offset="1" class="njjkphbnd"/></radialGradient><radialGradient id="iMzXytv" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 22.79)" gradientUnits="userSpaceOnUse"><stop class="bcwu99b2k"/><stop offset="1" class="ikuj7j5dl"/></radialGradient><radialGradient id="iIzS8Qb" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.158 23.465)" gradientUnits="userSpaceOnUse"><stop class="nh2d_e3ja"/><stop offset="1" class="s1mkhyyat"/></radialGradient><radialGradient id="ifBJ4Ug" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 19.97)" gradientUnits="userSpaceOnUse"><stop class="k_38rrb4p"/><stop offset="1" class="jq958cc5h"/></radialGradient><radialGradient id="irngmHd" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.232 7.517)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="rx794hb8i"/><stop offset="1" class="jh2mh4wye"/></radialGradient><radialGradient id="i78r8Sc" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.064)" gradientUnits="userSpaceOnUse"><stop class="j2u72qbdb"/><stop offset="1" class="r2rd1hnwy"/></radialGradient><radialGradient id="ixclxhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.064)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="i7VR6Ry" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.06 2.384)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="epy_aimha"/><stop offset="1" class="p6bgw4n9x"/></radialGradient><radialGradient id="i9Ozx6d" cx="0" cy="0" r="1" gradientTransform="rotate(118.757 4.549 9.672)scale(3.02046 3.40652)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="tx5q7hblx"/><stop offset="1" class="iu30sbc6i"/></radialGradient><radialGradient id="iFRyJpb" cx="0" cy="0" r="1" gradientTransform="matrix(.48635 10.50004 -6.22624 .2884 17.69 13.252)" gradientUnits="userSpaceOnUse"><stop offset=".056" class="q9yk7oosj"/><stop offset="1" class="ddgxe2b5l"/></radialGradient><radialGradient id="i0Cd4sb" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.582 10.737)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="xz9f7bbos"/><stop offset="1" class="auvxm7b4e"/></radialGradient><radialGradient id="ivVE2Kd" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 11.783)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="gd3w__bkb"/><stop offset="1" class="gz75fzb0l"/></radialGradient><radialGradient id="iNCc64l" cx="0" cy="0" r="1" gradientTransform="matrix(.11328 .6422 -3.96388 .69921 4.51 23.017)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="iviKZSX" cx="0" cy="0" r="1" gradientTransform="matrix(-.11328 .6422 -3.96388 -.69922 27.49 23.017)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="i9ky2ne" cx="0" cy="0" r="1" gradientTransform="matrix(.12686 .83746 -4.47454 .67782 4.517 23.642)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="iTtxXdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.12686 .83746 -4.47454 -.67782 27.483 23.642)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="i7rFGII" cx="0" cy="0" r="1" gradientTransform="matrix(.11226 .95131 -3.99486 .47143 5 24.197)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="inQw6Oe" cx="0" cy="0" r="1" gradientTransform="rotate(96.73 2.745 24.099)scale(.95791 4.02259)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="iTWRHAb" cx="0" cy="0" r="1" gradientTransform="rotate(84.646 -10.42 15.45)scale(1.07328 3.59749)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="iiU4zIz" cx="0" cy="0" r="1" gradientTransform="rotate(95.537 1.963 24.072)scale(.99219 3.43822)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="iVl1I9d" cx="0" cy="0" r="1" gradientTransform="matrix(1.1557 -1.28823 1.57286 1.41104 18.872 8.265)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iRB4xOe" cx="0" cy="0" r="1" gradientTransform="matrix(.8323 .46652 -.1319 .2353 19.227 6.584)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="ibgF3iS" cx="0" cy="0" r="1" gradientTransform="matrix(.9551 -.07105 .05554 .74663 18.797 7.719)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iD4J87S" cx="0" cy="0" r="1" gradientTransform="matrix(-.7634 0 0 -.60222 13.109 7.648)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="imWB1bb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.11395 1.89708 -2.5392 -5.50645 17.828 7.308)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iiup4wk" cx="0" cy="0" r="1" gradientTransform="rotate(172.574 8.773 4.671)scale(2.20794 2.43717)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iGQjawc" cx="0" cy="0" r="1" gradientTransform="rotate(-70.959 15.636 -4.21)scale(2.5349 3.21632)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iOVulqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.25381 -4.92394 0 16.02 7.17)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="iD1SpWb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.174 5.035)scale(4.45162 7.66432)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iHflLid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72794 .89338 0 17.475 7.043)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iHWPNxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.83025 .95153 0 14.706 6.898)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="icwzNeK" cx="0" cy="0" r="1" gradientTransform="matrix(-.81303 0 0 -4.07726 19.243 7.984)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iYcP0Yc" cx="0" cy="0" r="1" gradientTransform="rotate(71.834 4.894 11.86)scale(2.663 4.63927)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="il12e7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.28816 -1.29298 .39848 -.0888 16.516 8.444)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="isqs1me" cx="0" cy="0" r="1" gradientTransform="matrix(-.49302 0 0 -.13784 16.364 8.577)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iyQdtab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33595 2.77789 -4.54169 -2.1842 17.228 2.635)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="i24VsZc" cx="0" cy="0" r="1" gradientTransform="matrix(-.13305 .86484 -1.86067 -.28625 16.152 2.868)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="ixoNXTd" width="9.75" height="10.25" x="11.27" y="1.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/></filter><filter id="iqzGHpe" width="9.729" height="6.156" x="17.627" y="21.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.521569 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23998" result="effect2_innerShadow_3987_23998"/></filter><filter id="iLdMENe" width="17.213" height="8.245" x="5.751" y="21.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.658824 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.537255 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23998" result="effect2_innerShadow_3987_23998"/></filter><filter id="inzXvLb" width="7.621" height="12.797" x="19.836" y="11.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.54902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/></filter><filter id="idwOped" width="8.502" height="3.19" x="11.869" y="21.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/></filter><filter id="i2I4upI" width="5.834" height="4.108" x="13.158" y="10.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.643137 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/></filter><filter id="iaqFvbc" width="1.684" height="1.255" x="5.351" y="23.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".075"/></filter><filter id="im77E7y" width="1.684" height="1.255" x="24.965" y="23.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".075"/></filter><filter id="iVjREns" width="2.04" height="1.095" x="4.237" y="23.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".075"/></filter><filter id="i5JIIsc" width="2.04" height="1.095" x="25.723" y="23.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".075"/></filter><filter id="iK5Dh6p" width="2.223" height=".888" x="3.593" y="23.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".075"/></filter><filter id="isWgKBd" width="2.223" height=".888" x="26.184" y="23.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".075"/></filter><filter id="isFTO5b" width="2.031" height=".566" x="3.653" y="22.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".075"/></filter><filter id="iGQs7Nc" width="2.031" height=".566" x="26.317" y="22.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".075"/></filter><filter id="iZIPvTc" width="2.186" height="2.036" x="12.038" y="6.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/></filter><filter id="iQu3LJe" width="2.036" height="2.286" x="18.055" y="6.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/></filter><filter id="iRec1GS" width="2.359" height="2.359" x="17.894" y="6.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".25"/></filter><filter id="iWXtrgd" width="2.159" height="2.159" x="11.988" y="6.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".2"/></filter><filter id="i0Nf7VO" width="6.446" height="7.28" x="12.796" y="4.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/></filter><filter id="isGHXYT" width="2.188" height="2.696" x="14.823" y="6.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".25"/></filter><filter id="iOouPhc" width="1.488" height="1.996" x="15.276" y="7.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".075"/></filter><filter id="iINep2d" width="2.489" height="1.112" x="14.775" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".05"/></filter><filter id="iZILxfe" width="1.625" height=".764" x="13.61" y="5.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/></filter><filter id="ivORm1b" width="1.625" height=".764" x="17.038" y="5.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/></filter><filter id="iqLKoQb" width="1.351" height=".539" x="17.097" y="5.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".05"/></filter><filter id="itBXGhb" width="1.351" height=".539" x="13.648" y="5.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".05"/></filter><filter id="iMGYxpF" width="5.698" height="3.741" x="13.904" y="2.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23998"/><feGaussianBlur result="effect2_foregroundBlur_3987_23998" stdDeviation=".1"/></filter><filter id="iF8j2Ub" width="4.617" height="2.684" x="15.376" y="3.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".375"/></filter><filter id="iIE5Frb" width="1.628" height=".644" x="13.82" y="7.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".05"/></filter><filter id="iJ3dYLI" width="1.628" height=".644" x="16.609" y="7.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23998" stdDeviation=".05"/></filter><linearGradient id="iPeAgEb" x1="18.988" x2="14.684" y1="3.25" y2="11.223" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="i8M2ibb" x1="21.525" x2="21.525" y1="21.002" y2="22.158" gradientUnits="userSpaceOnUse"><stop class="h58pkjbsd"/><stop offset="1" class="pub21ekls"/></linearGradient><linearGradient id="iISRgKb" x1="18.658" x2="19.892" y1="24.286" y2="24.689" gradientUnits="userSpaceOnUse"><stop offset=".106" class="l2-xyub4i"/><stop offset="1" class="yi9dofbqv"/></linearGradient><linearGradient id="ixtAAry" x1="10.822" x2="10.822" y1="21.002" y2="22.158" gradientUnits="userSpaceOnUse"><stop class="w9r_6_bym"/><stop offset="1" class="v6lc275im"/></linearGradient><linearGradient id="ihQGM2b" x1="13.689" x2="12.455" y1="24.286" y2="24.689" gradientUnits="userSpaceOnUse"><stop offset=".106" class="d934ondjd"/><stop offset="1" class="vcwi5gbcl"/></linearGradient><linearGradient id="iPoJlVb" x1="12.24" x2="10.033" y1="20.607" y2="20.417" gradientUnits="userSpaceOnUse"><stop offset=".184" class="sl8i30onx"/><stop offset="1" class="b39l_ob7e"/></linearGradient><linearGradient id="ip9rHpc" x1="19.835" x2="22.042" y1="20.607" y2="20.417" gradientUnits="userSpaceOnUse"><stop offset=".184" class="bvjkc1dux"/><stop offset="1" class="im_-qcomr"/></linearGradient><linearGradient id="i5mA3oe" x1="26.505" x2="25.169" y1="25.217" y2="24.061" gradientUnits="userSpaceOnUse"><stop offset=".569" class="s_h949kal"/><stop offset="1" class="f-865jbco"/></linearGradient><linearGradient id="icnQwfe" x1="26.516" x2="25.268" y1="25.084" y2="24.957" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="iW3DxZb" x1="27.656" x2="26.075" y1="24.764" y2="24.504" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="itlXw6d" x1="28.314" x2="26.645" y1="24.018" y2="24.114" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="iDcX5Qb" x1="28.24" x2="26.724" y1="23.243" y2="23.181" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="iIZBaqb" x1="12.038" x2="13.91" y1="7.703" y2="7.703" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iXlv96W" x1="15.426" x2="16.02" y1="8.49" y2="8.49" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="ig5Xncd" x1="16.02" x2="16.02" y1="8.995" y2="8.609" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="itL8jAb" x1="15.346" x2="15.638" y1="9.887" y2="9.436" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-lotus-position-light" /></template>
<style>
.a-cjnzu_f {
  stop-color: var(--svg-color--c38390, #C38390);
}

.a03e9pb6i {
  fill-rule: evenodd;
  d: path("M6.76 22.928a.5.5 0 0 1-.5.5c-.632 0-1.257-.194-1.501-.269l-.04-.012a.5.5 0 1 1 .293-.956l.029.009c.246.075.743.227 1.219.227a.5.5 0 0 1 .5.5");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a4i5n45nj {
  fill-rule: evenodd;
  d: path("M25.276 24.143c-.14.17-.273.304-.102.444c.566.463.85.628 1.109.76l.072.036a.4.4 0 0 0 .367-.71l-.075-.039c-.242-.123-.38-.122-.879-.532c-.17-.14-.352-.13-.492.041");
}

.a8liujjia {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m13.87 6.523l-.003.002a.17.17 0 0 1-.174-.291v-.001l.003-.001l.006-.004l.094-.048c.062-.03.15-.068.259-.102c.215-.07.516-.127.84-.07a.17.17 0 0 1-.059.335c-.252-.045-.494 0-.678.058a2 2 0 0 0-.274.114z");
}

.adjv9ubcq {
  fill: var(--svg-color--f0b99e, #F0B99E);
  d: path("M22.32 16.051c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315V19.6c.25.651.719 1.329 1.125 1.652c0 0 .867.814 4.172 3.303c1.325-.184 2.094-1.093 2.073-1.703c-.874-.5-3.37-2.968-4.01-3.606c-.538-.535-.641-1.215-.876-3.196");
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.auvxm7b4e {
  stop-color: var(--svg-color--422d70, #422D70);
}

.b0ry09b4q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.122 23.236c-.398 0-.893.047-1.58-.11");
}

.b39l_ob7e {
  stop-color: var(--svg-color--df947d, #DF947D);
  stop-opacity: 0;
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.bcwu99b2k {
  stop-color: var(--svg-color--f2b59c, #F2B59C);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bvc6mfb7j {
  d: path("M13.83 21.294H7.814v2.692c2.531.352 6.016.297 6.016.297z");
}

.bvjkc1dux {
  stop-color: var(--svg-color--dc8368, #DC8368);
}

.c6s6khboc {
  d: path("M12.802 6.849h.007l-.006-.168l-.007-.194c.013-.6.364-.832.513-.91l.032-.012l.033-.013c.337-.155.61-.426.752-.781l.052-.123a.167.167 0 0 1 .292-.032a2.44 2.44 0 0 0 2.017 1.058h2.037c.114 0 .685.056.719.843l-.075 1.944c-.078 1.773-1.463 2.963-3.153 2.963s-3.074-1.19-3.152-2.963z");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cd_2jstni {
  fill-rule: evenodd;
  d: path("M26.175 23.496a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 1 0 0-.8a3.6 3.6 0 0 1-1.466-.365a.4.4 0 0 0-.537.18");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.cm7234atb {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M6.818 24.142c.14.171.272.304.101.444a6 6 0 0 1-1.265.82a.4.4 0 1 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.175");
}

.cpd04gb_d {
  d: path("M19.073 8.327a.68.68 0 1 0 0-1.359a.68.68 0 0 0 0 1.359");
}

.cxkykm1df {
  stop-color: var(--svg-color--efc3ad, #EFC3AD);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d934ondjd {
  stop-color: var(--svg-color--b17369, #B17369);
}

.ddgxe2b5l {
  stop-color: var(--svg-color--7455b7, #7455B7);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dlmr9bcyu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 23.986a3.8 3.8 0 0 1-1.773-.437");
}

.dlop932ty {
  fill: var(--svg-color--fdcab1, #FDCAB1);
  d: path("M10.236 27.908c-2.93 0-4.281-1.917-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086c.426 0 .804.268.944.67c.407 1.17.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.dob5rviuo {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M5.697 23.017a.4.4 0 0 1-.266.5c-.536.164-1.099.146-1.367.137q-.082-.003-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.002c.286.008.656.017 1.045-.102a.4.4 0 0 1 .5.265");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0us9sblp {
  stop-color: var(--svg-color--eec0af, #EEC0AF);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.eczhn6bte {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.717c.41-.067 1.204-.313 1.59-.645");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.epy_aimha {
  stop-color: var(--svg-color--ffceb8, #FFCEB8);
}

.exu9ep_8j {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.02 9.49c-.33 0-.64-.08-.9-.219c-.089-.046-.184.056-.128.14a1.222 1.222 0 0 0 2.055 0c.056-.087-.04-.186-.128-.14c-.26.14-.567.218-.9.218Z");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f-865jbco {
  stop-color: var(--svg-color--da9982, #DA9982);
}

.f5k7byw5f {
  d: path("M19.073 8.665a1.018 1.018 0 1 0 0-2.035a1.018 1.018 0 0 0 0 2.035");
}

.f7iqbccaz {
  stop-color: var(--svg-color--ffcab4, #FFCAB4);
}

.fj3_5achs {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m18.38 6.234l-.087.145za.17.17 0 0 1-.174.29l-.003-.001l-.072-.037a2 2 0 0 0-.216-.085a1.44 1.44 0 0 0-.678-.058a.17.17 0 0 1-.06-.335c.325-.057.626 0 .841.07a2 2 0 0 1 .353.15l.006.004z");
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fx1lyxs2a {
  d: path("M13.068 8.327a.68.68 0 1 0 0-1.359a.68.68 0 0 0 0 1.359");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g7tzrok9x {
  stroke: var(--svg-color--4b3833, #4B3833);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.97 7.274a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.gbcyzr76l {
  fill-rule: evenodd;
  d: path("M26.304 23.017a.4.4 0 0 0 .265.5c.536.164 1.099.146 1.367.137q.082-.003.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.002c-.286.008-.656.017-1.045-.102a.4.4 0 0 0-.5.265");
}

.gd3w__bkb {
  stop-color: var(--svg-color--785684, #785684);
}

.gf6fosb8y {
  stop-color: var(--svg-color--ffc2a4, #FFC2A4);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gsv8efolz {
  stop-color: var(--svg-color--6e6773, #6E6773);
}

.gyhpocb3d {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M6.099 23.918a.4.4 0 0 1-.044.563c-.34.29-.628.457-.903.55a2.5 2.5 0 0 1-.655.113l-.037.003a.4.4 0 0 1-.057-.798l.018-.002c.19-.013.32-.022.475-.074c.155-.053.356-.158.639-.4a.4.4 0 0 1 .564.044");
}

.gz75fzb0l {
  stop-color: var(--svg-color--735ea4, #735EA4);
  stop-opacity: 0;
}

.h58pkjbsd {
  stop-color: var(--svg-color--b66c55, #B66C55);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hvkhdmfad {
  d: path("m13.447 24.283l-1.578-2.99h8.301l-1.551 2.99z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i5mi7_b2a {
  d: path("M15.638 2.72c-.717-.159-1.36.556-1.434.821c.665 2.243 2.348 2.12 4.01 1.935c.995-.11 1.103.343 1.188.562c0-2.488-2.116-2.955-3.746-3.314z");
}

.ihlvscyun {
  stop-color: var(--svg-color--e2b3a5, #E2B3A5);
}

.ikuj7j5dl {
  stop-color: var(--svg-color--ce927d, #CE927D);
}

.im_-qcomr {
  stop-color: var(--svg-color--dc8368, #DC8368);
  stop-opacity: 0;
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iu30sbc6i {
  stop-color: var(--svg-color--e6ab90, #E6AB90);
  stop-opacity: 0;
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.iwdhkcbmk {
  d: path("m15.778 7.42l-.337 1.074a.34.34 0 0 0 .33.443h.497a.342.342 0 0 0 .33-.443L16.26 7.42c-.072-.238-.408-.238-.483 0");
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j2u72qbdb {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
}

.jh2mh4wye {
  stop-color: var(--svg-color--f1c0a6, #F1C0A6);
  stop-opacity: 0;
}

.jk4gd0bdm {
  fill-rule: evenodd;
  d: path("M5.825 23.496a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 1 1 0-.8c.226 0 .852-.06 1.466-.365a.4.4 0 0 1 .537.18");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jlleovb-o {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M5.825 23.496a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 1 1 0-.8c.226 0 .852-.06 1.466-.365a.4.4 0 0 1 .537.18");
}

.jq958cc5h {
  stop-color: var(--svg-color--d2826a, #D2826A);
  stop-opacity: 0;
}

.jr2ezs63s {
  stop-color: var(--svg-color--f1b9a0, #F1B9A0);
}

.jvt0tewya {
  stop-color: var(--svg-color--f3a98c, #F3A98C);
}

.jyrzspbah {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.849 6.147c-.204-.05-.712-.025-1.05.218");
}

.jz-6pkbmo {
  fill-rule: evenodd;
  d: path("M6.099 23.918a.4.4 0 0 1-.044.563c-.34.29-.628.457-.903.55a2.5 2.5 0 0 1-.655.113l-.037.003a.4.4 0 0 1-.057-.798l.018-.002c.19-.013.32-.022.475-.074c.155-.053.356-.158.639-.4a.4.4 0 0 1 .564.044");
}

.k_38rrb4p {
  stop-color: var(--svg-color--ac5d47, #AC5D47);
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.kaew0_2pl {
  stop-color: var(--svg-color--dc9fa1, #DC9FA1);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l2-xyub4i {
  stop-color: var(--svg-color--af7875, #AF7875);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.la27w1gfo {
  d: path("M20.565 8.54a2.06 2.06 0 0 0 .204-.903c0-.296-.06-.573-.17-.826h.004a2 2 0 0 0-.178-.325l-.001-.002a2.05 2.05 0 0 1-.333-1.12v-.006a2.087 2.087 0 0 0-2.087-2.087a.34.34 0 0 1-.288-.147a2.09 2.09 0 0 0-3.393 0a.36.36 0 0 1-.288.147a2.087 2.087 0 0 0-2.087 2.087v.006c0 .397-.115.788-.333 1.12l-.001.003a2.09 2.09 0 0 0-.14 2.052a.33.33 0 0 1 0 .288a2.033 2.033 0 0 0 1.83 2.926h5.43a2.033 2.033 0 0 0 1.83-2.926a.33.33 0 0 1 0-.288m-7.756-1.691h-.007l.758 1.49c.078 1.773.77 0 2.46 0s2.426 1.973 2.504.2l.719-2.022c-.034-.787-.605-.843-.719-.843h-2.037a2.44 2.44 0 0 1-2.017-1.058a.167.167 0 0 0-.292.032l-.052.123a1.46 1.46 0 0 1-.752.78l-.033.014l-.032.012c-.15.078-.5.31-.513.91l.007.194z");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lpv9r5l0o {
  stop-color: var(--svg-color--f3a98c, #F3A98C);
  stop-opacity: 0;
}

.lsnfobzbz {
  stop-color: var(--svg-color--fdc3a2, #FDC3A2);
}

.m3g9c93kt {
  d: path("M9.755 16.051c.22-1.858 1.605-3.58 2.152-4.041l.332.315V19.6c-.25.651-.719 1.329-1.125 1.652c0 0-.867.814-4.171 3.303c-1.325-.184-2.095-1.093-2.074-1.703c.875-.5 3.37-2.968 4.011-3.606c.537-.535.64-1.215.875-3.196");
}

.m69lyob2q {
  stop-color: var(--svg-color--d69f8f, #D69F8F);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mp5pacluc {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.818 23.986c.398 0 1.015-.055 1.773-.437");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n6m3gkbee {
  stop-color: var(--svg-color--e0a6a7, #E0A6A7);
  stop-opacity: 0;
}

.nayex6koj {
  fill-rule: evenodd;
  d: path("M25.902 23.918a.4.4 0 0 0 .043.563c.34.29.628.457.903.55c.254.085.478.1.655.113l.037.003a.4.4 0 0 0 .057-.798l-.018-.002a1.8 1.8 0 0 1-.474-.074c-.156-.053-.357-.158-.64-.4a.4.4 0 0 0-.564.044");
}

.nb1t54bir {
  fill: var(--svg-color--e2af9a, #E2AF9A);
  fill-rule: evenodd;
  d: path("M26.304 23.017a.4.4 0 0 0 .265.5c.536.164 1.099.146 1.367.137q.082-.003.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.002c-.286.008-.656.017-1.045-.102a.4.4 0 0 0-.5.265");
}

.nh2d_e3ja {
  stop-color: var(--svg-color--f3bea3, #F3BEA3);
}

.njjkphbnd {
  stop-color: var(--svg-color--ce8c76, #CE8C76);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.otw__cbjw {
  fill: var(--svg-color--e2af9a, #E2AF9A);
  fill-rule: evenodd;
  d: path("M26.175 23.496a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 1 0 0-.8a3.6 3.6 0 0 1-1.466-.365a.4.4 0 0 0-.537.18");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ovwybtw7l {
  stroke: var(--svg-color--4b3833, #4B3833);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.76 7.274a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.oyrh9eprn {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.771 7.507l-.432 1.075a.34.34 0 0 0 .33.442h.497a.342.342 0 0 0 .329-.442l-.336-1.075c-.072-.238-.312-.238-.388 0");
}

.p6bgw4n9x {
  stop-color: var(--svg-color--f5bca5, #F5BCA5);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pgvvb0b4v {
  stop-color: var(--svg-color--eabfa6, #EABFA6);
}

.pr4ditbsi {
  d: path("M13.22 24.283h-1.429a1 1 0 0 0-.943.67c-.408 1.17-.96 2.765-1.032 3.002c-.11.36-.25 1.453.875 1.766c.757.21 1.48-.872 2.057-1.735l.052-.078h.42z");
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.pub21ekls {
  stop-color: var(--svg-color--cd846b, #CD846B);
  stop-opacity: 0;
}

.q_d3v4bll {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.638 2.72c-.717-.159-1.36.556-1.434.821c.665 2.243 2.348 2.12 4.01 1.935c.995-.11 1.103.343 1.188.562c0-2.488-2.116-2.955-3.746-3.314z");
}

.q5ek91bxz {
  fill: var(--svg-color--fabc9f, #FABC9F);
  d: path("M9.755 16.051c.22-1.858 1.605-3.58 2.152-4.041l.332.315V19.6c-.25.651-.719 1.329-1.125 1.652c0 0-.867.814-4.171 3.303c-1.325-.184-2.095-1.093-2.074-1.703c.875-.5 3.37-2.968 4.011-3.606c.537-.535.64-1.215.875-3.196");
}

.q9yk7oosj {
  stop-color: var(--svg-color--987fd3, #987FD3);
}

.qcf9xbgxm {
  stop-color: var(--svg-color--f9bcae, #F9BCAE);
}

.qfc59fbmm {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.778 7.42l-.337 1.074a.34.34 0 0 0 .33.443h.497a.342.342 0 0 0 .33-.443L16.26 7.42c-.072-.238-.408-.238-.483 0");
}

.qldr0kbme {
  d: path("M10.236 27.908c-2.93 0-4.281-1.917-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086c.426 0 .804.268.944.67c.407 1.17.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qyby9eehb {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.02 9.49c-.33 0-.64-.08-.9-.219c-.089-.046-.184.056-.128.14a1.222 1.222 0 0 0 2.055 0c.056-.087-.04-.186-.128-.14c-.26.14-.567.218-.9.218");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r2rd1hnwy {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
  stop-opacity: 0;
}

.r6t5fdb5z {
  d: path("M17.627 27.908h4.244c2.93 0 4.28-1.917 4.484-2.828l-2.531-2.328l-3.62 1.422l-2.578.109z");
}

.rx794hb8i {
  stop-color: var(--svg-color--f0c1ae, #F0C1AE);
}

.s_h949kal {
  stop-color: var(--svg-color--e4b6a0, #E4B6A0);
}

.s_ql7obry {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
}

.s1mkhyyat {
  stop-color: var(--svg-color--efba94, #EFBA94);
  stop-opacity: 0;
}

.s2exfcbyx {
  d: path("M22.32 16.051c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315V19.6c.25.651.719 1.329 1.125 1.652c0 0 .867.814 4.172 3.303c1.325-.184 2.094-1.093 2.073-1.703c-.874-.5-3.37-2.968-4.01-3.606c-.538-.535-.641-1.215-.876-3.196");
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s86ss6vyf {
  stop-color: var(--svg-color--d69f8f, #D69F8F);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sl8i30onx {
  stop-color: var(--svg-color--df947d, #DF947D);
}

.sn5e1_b6a {
  d: path("M18.517 21.294h6.016v2.692c-2.532.352-6.016.297-6.016.297z");
}

.sq6qddbed {
  fill-rule: evenodd;
  d: path("M25.316 22.928a.5.5 0 0 0 .5.5c.632 0 1.257-.194 1.5-.269l.04-.012a.5.5 0 1 0-.292-.956l-.03.009c-.246.075-.743.227-1.218.227a.5.5 0 0 0-.5.5");
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.srj3oq2hf {
  d: path("M18.892 11.124v.721a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.723a6.5 6.5 0 0 0-1.27.896v9.276h8.289v-9.276c-.198-.2-.662-.56-1.285-.895");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.t-vc93b3o {
  fill-rule: evenodd;
  d: path("M6.818 24.142c.14.171.272.304.101.444a6 6 0 0 1-1.265.82a.4.4 0 1 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.175");
}

.t6ernuw5h {
  d: path("M18.892 11.124v.721a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.723c.763-.417 1.77-.784 2.914-.784c1.05 0 2.055.374 2.82.786");
}

.tbpujzqai {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.424 25.025c-.25-.146-.847-.51-1.234-.804");
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

.tx5q7hblx {
  stop-color: var(--svg-color--de9b7b, #DE9B7B);
}

.u_pil8u_l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M27.538 24.717c-.41-.067-1.204-.313-1.59-.645");
}

.u_uylxu0j {
  stop-color: var(--svg-color--d08c76, #D08C76);
  stop-opacity: 0;
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.umoqnbb7f {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.76 7.274a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.uokd_kbwg {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.878 23.236c.398 0 .893.047 1.58-.11");
}

.uxuve9blo {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.247 6.147c.204-.05.711-.025 1.05.218");
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v6lc275im {
  stop-color: var(--svg-color--c5856f, #C5856F);
  stop-opacity: 0;
}

.vcwi5gbcl {
  stop-color: var(--svg-color--c98e79, #C98E79);
  stop-opacity: 0;
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vz0iqbcsc {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M13.068 8.327a.68.68 0 1 0 0-1.359a.68.68 0 0 0 0 1.359");
}

.w_0x8cbdi {
  stop-color: var(--svg-color--d08c76, #D08C76);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w20zx1b6w {
  stop-color: var(--svg-color--ce9b8a, #CE9B8A);
}

.w9r_6_bym {
  stop-color: var(--svg-color--b3715e, #B3715E);
}

.wp12h1b1k {
  stop-color: var(--svg-color--eec0af, #EEC0AF);
  stop-opacity: 0;
}

.wpo7vfbqs {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.274a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.x09w1trwj {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.576 25.025c.25-.146.847-.51 1.234-.804");
}

.x3hc4tb4e {
  fill-rule: evenodd;
  d: path("M5.697 23.017a.4.4 0 0 1-.266.5c-.536.164-1.099.146-1.367.137q-.082-.003-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.002c.286.008.656.017 1.045-.102a.4.4 0 0 1 .5.265");
}

.x40ln-bnj {
  fill: var(--svg-color--e2af9a, #E2AF9A);
  fill-rule: evenodd;
  d: path("M25.902 23.918a.4.4 0 0 0 .043.563c.34.29.628.457.903.55c.254.085.478.1.655.113l.037.003a.4.4 0 0 0 .057-.798l-.018-.002a1.8 1.8 0 0 1-.474-.074c-.156-.053-.357-.158-.64-.4a.4.4 0 0 0-.564.044");
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

.xyv86i6rr {
  d: path("M13.056 8.665a1.018 1.018 0 1 0 0-2.035a1.018 1.018 0 0 0 0 2.035");
}

.xz9f7bbos {
  stop-color: var(--svg-color--644e9f, #644E9F);
  stop-opacity: 0;
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y2xpzibik {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M19.073 8.327a.68.68 0 1 0 0-1.359a.68.68 0 0 0 0 1.359");
}

.yfooxwfal {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.542 5.003l-.902.166a.435.435 0 1 1-.079-.864h1.48c.876 0 1.166.883 1.202 1.184a1.99 1.99 0 0 0-1.701-.486");
}

.ygetoyo1j {
  stop-color: var(--svg-color--ffcab4, #FFCAB4);
  stop-opacity: 0;
}

.yi9dofbqv {
  stop-color: var(--svg-color--c79383, #C79383);
  stop-opacity: 0;
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z260igbpj {
  stop-color: var(--svg-color--f9bcae, #F9BCAE);
  stop-opacity: 0;
}

.zk-sr297c {
  stop-color: var(--svg-color--e0a6a7, #E0A6A7);
}

.zpmzd2b_c {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
  stop-opacity: 0;
}

</style>
