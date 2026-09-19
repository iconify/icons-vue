<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNXG1Zb)" class="u02a1vtwi"/><path fill="url(#iKtgbud)" class="uohk86iby"/><rect fill="url(#inDsD1i)" class="ez24-xbem"/><rect fill="url(#i0oHKBb)" class="ez24-xbem"/><g filter="url(#ibgnkPc)"><path fill="url(#i1zmePF)" class="thano8bvw"/><path fill="url(#it6gSee)" class="thano8bvw"/><path fill="url(#iQqrOmG)" class="thano8bvw"/><path fill="url(#iwNoqDe)" class="thano8bvw"/><path fill="url(#iQaEZpc)" class="thano8bvw"/><path fill="url(#idgL5bc)" class="thano8bvw"/><path fill="url(#iRwaRCe)" class="thano8bvw"/></g><path fill="url(#i25FFtc)" class="thano8bvw"/><path fill="url(#iJ6kX0W)" class="thano8bvw"/><path fill="url(#ieMNGNd)" class="thano8bvw"/><path fill="url(#isj65tb)" class="thano8bvw"/><g filter="url(#irKMh7b)"><path class="d2zfpbyds"/></g><g filter="url(#iLA8tdb)"><path fill="url(#iLVpXWc)" class="ucvon1e0f"/><path fill="url(#i2CLU5c)" class="ucvon1e0f"/><path fill="url(#iKfQLQO)" class="ucvon1e0f"/><path fill="url(#imlMEEb)" class="ucvon1e0f"/><path fill="url(#iVGj2Lb)" class="ucvon1e0f"/><path fill="url(#i59Pwse)" class="ucvon1e0f"/><path fill="url(#iA7H0Md)" class="ucvon1e0f"/></g><g filter="url(#iPaYUDe)"><path class="rzr27zurw"/><path fill="url(#iYfqVsD)" class="zl4550_6y"/><path fill="url(#icg68Ec)" class="zl4550_6y"/><path fill="url(#iOZZ6wd)" class="zl4550_6y"/></g><g filter="url(#iTWWa7b)"><path class="ctebkkhca"/><path fill="url(#iaIp10b)" class="p4lcx2a4b"/><path fill="url(#ivLMw2c)" class="p4lcx2a4b"/></g><g filter="url(#iYzKGkd)"><path class="j4pghpbnq"/><path fill="url(#iWivgvd)" class="stu3d4b7y"/><path fill="url(#iHqHYWc)" class="stu3d4b7y"/></g><path class="uj-ttlabc"/><path fill="url(#iJ11RKc)" class="c36yqwb8n"/><path class="tu_5mkbaw"/><g filter="url(#iCCKRId)"><path class="q5texu1ss"/><path fill="url(#iB89jpc)" class="e13mj1was"/></g><g filter="url(#iGMtDyG)"><path fill="url(#iAjsrWd)" class="rzbok0aqc"/></g><path class="qrzabx_4z"/><path fill="url(#i5DdZsd)" class="khte_tzpb"/><path class="qi0665bes"/><g filter="url(#iiwP7de)"><path fill="url(#iBhDbYc)" class="hmenlybab"/></g><g filter="url(#iuOcO6b)"><ellipse transform="rotate(-27.914 13.272 15.052)" class="fycekabph"/><ellipse fill="url(#i0xNNIe)" transform="rotate(-27.914 13.272 15.052)" class="ghg-e1bfu"/></g><path fill="url(#isGltJc)" class="x7ljgpqek"/><path fill="url(#iDvuxsc)" class="yb4penyyu"/><g filter="url(#i17pmNc)"><path fill="url(#iJoXTpb)" class="x14xtc2ed"/></g><g filter="url(#ixTDDPe)"><path fill="url(#iLVkIPb)" class="yx2o0obdd"/></g><g filter="url(#ittBlNb)"><path clip-rule="evenodd" class="nb0xkbc5s"/></g><g filter="url(#iEyBPOe)"><path stroke="url(#iO33JDd)" class="gsbxves2y"/></g><g filter="url(#itzjWne)"><path clip-rule="evenodd" class="e-tyzrmey"/></g><g filter="url(#itRGS5x)"><path stroke="url(#iXmMBBo)" class="fycafc3yi"/></g><path stroke="url(#icvYwTb)" class="urahr5ysp"/><path fill="url(#ilvNJVu)" class="q973iyb6t"/><path fill="url(#i011zJu)" class="q973iyb6t"/><path fill="url(#icAnfpc)" class="q973iyb6t"/><path fill="url(#i4KnSQj)" class="q973iyb6t"/><path fill="url(#iCt4xDb)" class="q973iyb6t"/><path fill="url(#iQHkhdq)" class="q973iyb6t"/><path fill="url(#ienxIPc)" class="q973iyb6t"/><path fill="url(#im95KLb)" class="q973iyb6t"/><path fill="url(#iXyCdOe)" class="q973iyb6t"/><path fill="url(#ix8r1Bc)" class="q973iyb6t"/><path fill="url(#iRuWwXc)" class="q973iyb6t"/><path fill="url(#iIxKEEd)" class="q973iyb6t"/><path fill="url(#ianl7tm)" class="zcyr97bop"/><path fill="url(#iAjEaoe)" class="zcyr97bop"/><path fill="url(#in9MEld)" class="yne9g-wvj"/><path fill="url(#ih2sZDn)" class="yne9g-wvj"/><path fill="url(#i4Wx5fe)" class="yne9g-wvj"/><path fill="url(#iVytu2b)" class="dkkvyqbbp"/><path fill="url(#i97JRac)" class="dkkvyqbbp"/><path fill="url(#ihGNt9r)" class="ebnbqcb_c"/><path fill="url(#iGyQx8d)" class="ebnbqcb_c"/><g filter="url(#iUxb5Sd)"><path fill="url(#icmYSIb)" class="wthpf-bib"/></g><g filter="url(#ieUTEUb)"><path stroke="url(#i9QzLKe)" class="yhy2k9bbo"/></g><path stroke="url(#iuMpIUd)" class="pv_1ruamy"/><path stroke="url(#ihV1hFc)" class="pv_1ruamy"/><path stroke="url(#iGxVyUb)" class="pv_1ruamy"/><path stroke="url(#ixjabce)" class="jtevqibrq"/><path stroke="url(#iguAwPv)" class="jtevqibrq"/><path stroke="url(#ikSaAoe)" class="jtevqibrq"/><path stroke="url(#iCXMSTb)" class="jtevqibrq"/><path stroke="url(#iXHReae)" class="b57ou_b9t"/><path stroke="url(#i324Zzd)" class="b57ou_b9t"/><path stroke="url(#ik7jzUd)" class="b57ou_b9t"/><path stroke="url(#i4Poovh)" class="o_9_81b8h"/><path stroke="url(#ieW5cId)" class="o_9_81b8h"/><path stroke="url(#i5UxMMe)" class="o_9_81b8h"/><path stroke="url(#iKhIFkd)" class="o_9_81b8h"/><path stroke="url(#iWqBPXc)" class="nwoksp-my"/><path stroke="url(#iAIr5jU)" class="nwoksp-my"/><path stroke="url(#iHf8wmT)" class="nwoksp-my"/><path stroke="url(#iVXvlDY)" class="m-g55uf3j"/><path stroke="url(#iroVxeQ)" class="m-g55uf3j"/><path stroke="url(#iI4Fcud)" class="m-g55uf3j"/><path stroke="url(#iXSR1Qb)" class="m-g55uf3j"/><path stroke="url(#ikNgKGb)" class="bwxbq0bkg"/><path stroke="url(#iiQfQjc)" class="bwxbq0bkg"/><path stroke="url(#iQmpx9d)" class="rjf2cql4s"/><path stroke="url(#iqlphle)" class="rjf2cql4s"/><path stroke="url(#icXRAhd)" class="rjf2cql4s"/><path stroke="url(#i0pQHze)" class="rjf2cql4s"/><path fill="url(#i40TVzb)" class="p-_rdwbrl"/><path fill="url(#iTTizpc)" class="mjonlnn_a"/><path fill="url(#itp1FHl)" class="mjonlnn_a"/><g filter="url(#iZkrl9d)"><path stroke="url(#iRTLnJe)" class="pm_eeybbf"/></g><g filter="url(#iD9ZQZa)"><path stroke="url(#isezRKd)" class="wkfrpjs0r"/></g><g filter="url(#igzDtxd)"><path stroke="url(#ivOTmHr)" class="v-fcszbji"/></g><g filter="url(#inqDbVb)"><path stroke="url(#iX7DEhe)" class="vz10a6buo"/></g><defs><radialGradient id="iNXG1Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-.83944 3.44902 -4.09716 -.99719 21.983 17.025)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="enp78gnvj"/><stop offset=".837" class="zqzqzsbzu"/></radialGradient><radialGradient id="iKtgbud" cx="0" cy="0" r="1" gradientTransform="matrix(1.12646 -.03884 .11746 3.40643 9.608 18.326)" gradientUnits="userSpaceOnUse"><stop class="qkq4f9buv"/><stop offset=".944" class="kf7k4hbsb"/></radialGradient><radialGradient id="inDsD1i" cx="0" cy="0" r="1" gradientTransform="rotate(45 -19.267 29.052)scale(3.69687 4.54701)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="jq7m5akyh"/><stop offset="1" class="ny-jsdbat"/></radialGradient><radialGradient id="i0oHKBb" cx="0" cy="0" r="1" gradientTransform="rotate(-114.444 17.674 6.936)scale(4.24281 2.54131)" gradientUnits="userSpaceOnUse"><stop class="a7lv1ybzm"/><stop offset="1" class="lda3x_b4r"/></radialGradient><radialGradient id="i1zmePF" cx="0" cy="0" r="1" gradientTransform="rotate(-179.193 8.217 8.536)scale(4.43794 7.38131)" gradientUnits="userSpaceOnUse"><stop class="y1ra82bkx"/><stop offset="1" class="snr48fb6s"/></radialGradient><radialGradient id="it6gSee" cx="0" cy="0" r="1" gradientTransform="rotate(105.939 4.919 12.08)scale(4.69997 4.25479)" gradientUnits="userSpaceOnUse"><stop class="dk116n8kk"/><stop offset="1" class="ve2ly-bfr"/></radialGradient><radialGradient id="iQqrOmG" cx="0" cy="0" r="1" gradientTransform="rotate(118.339 4.311 13.725)scale(2.37944 1.97046)" gradientUnits="userSpaceOnUse"><stop class="cexw7pbgs"/><stop offset="1" class="jd3h1p_cf"/></radialGradient><radialGradient id="iwNoqDe" cx="0" cy="0" r="1" gradientTransform="matrix(.95363 -3.30372 9.09666 2.62579 14.12 22.18)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="ah2l1obip"/><stop offset="1" class="golbtmbys"/></radialGradient><radialGradient id="iQaEZpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.69746 1.66534 0 13.579 14.5)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="ekpp6jgni"/><stop offset="1" class="jv53r67zu"/></radialGradient><radialGradient id="idgL5bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34636 1.7402 0 18.488 14.423)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="k_4cqj2sv"/><stop offset="1" class="rhx-o-b8q"/></radialGradient><radialGradient id="iRwaRCe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.1875 -3.0625 5.38842 -9.12732 20.969 20.125)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="nswj93bty"/><stop offset="1" class="bhqqd7bcd"/></radialGradient><radialGradient id="iJ6kX0W" cx="0" cy="0" r="1" gradientTransform="rotate(60.555 -1.465 14.84)scale(3.35069 6.6748)" gradientUnits="userSpaceOnUse"><stop class="m4u9ezbad"/><stop offset="1" class="p5xde80ny"/></radialGradient><radialGradient id="ieMNGNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 6.3125 -1.34311 -.11303 10.189 15.438)" gradientUnits="userSpaceOnUse"><stop offset=".654" class="j_cg2wc4l"/><stop offset="1" class="nlhhwjb1r"/></radialGradient><radialGradient id="isj65tb" cx="0" cy="0" r="1" gradientTransform="matrix(1.9417 -2.80617 .56113 .38826 10.227 12.088)" gradientUnits="userSpaceOnUse"><stop class="hpjidqofk"/><stop offset="1" class="a0opghbrh"/></radialGradient><radialGradient id="imlMEEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .23468 -.91915 0 16.384 17.445)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="cuyeqyb9v"/><stop offset="1" class="a3aywi70u"/></radialGradient><radialGradient id="iYfqVsD" cx="0" cy="0" r="1" gradientTransform="rotate(59.323 -.69 13.428)scale(3.14567 7.82114)" gradientUnits="userSpaceOnUse"><stop class="nyi6_naly"/><stop offset="1" class="pw9q04bxy"/></radialGradient><radialGradient id="icg68Ec" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 9.593 6.72)scale(2.52844 5.44031)" gradientUnits="userSpaceOnUse"><stop offset=".42" class="fr8wppbrf"/><stop offset=".905" class="ntnujibcy"/></radialGradient><radialGradient id="iOZZ6wd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49955 .43561 -.73415 -4.21257 22.95 11.801)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="byra0jsyn"/><stop offset="1" class="ch9vaeb5u"/></radialGradient><radialGradient id="iaIp10b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.70756 0 0 -.70728 16.54 8.075)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="as1mkr9ou"/><stop offset="1" class="w67-oq7ms"/></radialGradient><radialGradient id="ivLMw2c" cx="0" cy="0" r="1" gradientTransform="matrix(3.50375 -5.54762 8.14343 5.14321 10.03 12.463)" gradientUnits="userSpaceOnUse"><stop class="f0ompqbwt"/><stop offset=".288" class="apk6h_s6w"/></radialGradient><radialGradient id="iWivgvd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.03126 .584 -.63293 -5.45279 21.288 9.091)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="f0kf0_3nd"/><stop offset="1" class="f_fss5bgi"/></radialGradient><radialGradient id="iHqHYWc" cx="0" cy="0" r="1" gradientTransform="matrix(3.02827 .7705 -.33418 1.31341 19.37 9.156)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="wnyjcjb4k"/><stop offset="1" class="aubonyh_z"/></radialGradient><radialGradient id="iJ11RKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88332 -1.40502 0 18.319 15.156)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="au361rb0r"/></radialGradient><radialGradient id="iB89jpc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2525 -.32538 .44797 -.34763 18.07 15.248)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5DdZsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88336 -1.40509 0 13.567 15.156)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="au361rb0r"/></radialGradient><radialGradient id="i0xNNIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00842 -.53793 .64661 -.01012 13.256 15.395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isGltJc" cx="0" cy="0" r="1" gradientTransform="matrix(1.42879 0 0 1.59032 21.416 15.61)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="iiuwv9vea"/><stop offset="1" class="rdmu-zisu"/></radialGradient><radialGradient id="iDvuxsc" cx="0" cy="0" r="1" gradientTransform="rotate(-175.776 5.516 7.749)scale(1.29257 2.20938)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="qo-e1l5lk"/><stop offset="1" class="f3emps4bt"/></radialGradient><radialGradient id="iJoXTpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.65365 0 0 -1.07747 10.491 15.773)" gradientUnits="userSpaceOnUse"><stop class="l9hx93vcp"/><stop offset="1" class="xxptsowmw"/></radialGradient><radialGradient id="iLVkIPb" cx="0" cy="0" r="1" gradientTransform="matrix(.96094 .04287 -.03776 .84633 21.369 15.723)" gradientUnits="userSpaceOnUse"><stop class="xpsaw3m9c"/><stop offset=".809" class="rzk9brbsy"/></radialGradient><radialGradient id="i011zJu" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 -1.21 15.637)scale(7.05349 6.17563)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="m_2922ixt"/><stop offset="1" class="a-2r3fbgq"/></radialGradient><radialGradient id="icAnfpc" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.921 8.388)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="h9fb5bbiv"/><stop offset="1" class="j1090kf1c"/></radialGradient><radialGradient id="i4KnSQj" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 8.98 14.858)" gradientUnits="userSpaceOnUse"><stop class="hiycpfc4f"/><stop offset="1" class="mqq2pckgy"/></radialGradient><radialGradient id="iCt4xDb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.167 7.046)" gradientUnits="userSpaceOnUse"><stop class="ew56wjbup"/><stop offset="1" class="qd38sjb7e"/></radialGradient><radialGradient id="iQHkhdq" cx="0" cy="0" r="1" gradientTransform="rotate(123.092 2.5 5.77)scale(1.65986 2.90522)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="jbd_cz55y"/><stop offset="1" class="by6guy4wy"/></radialGradient><radialGradient id="ienxIPc" cx="0" cy="0" r="1" gradientTransform="rotate(158.664 4.674 10.147)scale(5.43502 6.37816)" gradientUnits="userSpaceOnUse"><stop class="bps78hksv"/><stop offset="1" class="fh1_5ac_k"/></radialGradient><radialGradient id="im95KLb" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 .71875 -2.2725 1.03746 23.542 6.421)" gradientUnits="userSpaceOnUse"><stop class="ze5ugdbxr"/><stop offset="1" class="pr8brkb_h"/></radialGradient><radialGradient id="iXyCdOe" cx="0" cy="0" r="1" gradientTransform="rotate(-26.281 48.92 5.7)scale(5.64614 18.1367)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="aeh-ojcyt"/><stop offset="1" class="eg11r1-xe"/></radialGradient><radialGradient id="ix8r1Bc" cx="0" cy="0" r="1" gradientTransform="rotate(19.44 -33.06 67.92)scale(5.63367 5.31661)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="g1bdywbbk"/><stop offset="1" class="woz3hacrx"/></radialGradient><radialGradient id="iRuWwXc" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 -1.5 3.12608 5.73115 20.845 10.625)" gradientUnits="userSpaceOnUse"><stop class="g1bdywbbk"/><stop offset="1" class="woz3hacrx"/></radialGradient><radialGradient id="iIxKEEd" cx="0" cy="0" r="1" gradientTransform="matrix(3.375 1.625 -3.0178 6.26772 20.783 17.25)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="g1bdywbbk"/><stop offset="1" class="woz3hacrx"/></radialGradient><radialGradient id="ianl7tm" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 1 -2.31305 -1.3011 9.058 6.546)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="iAjEaoe" cx="0" cy="0" r="1" gradientTransform="rotate(123.118 3.043 5.766)scale(.58626 1.5796)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="qso4uy3-n"/><stop offset="1" class="b_rfybbbi"/></radialGradient><radialGradient id="in9MEld" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1 -2.31306 1.3011 23.088 6.546)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="ih2sZDn" cx="0" cy="0" r="1" gradientTransform="matrix(1.2431 1.58204 -3.03843 2.38745 24.031 5.233)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="j26seachc"/><stop offset=".74" class="rsdjdrd8e"/></radialGradient><radialGradient id="i4Wx5fe" cx="0" cy="0" r="1" gradientTransform="matrix(1.64397 -.80986 .45783 .92938 23.225 5.44)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="vj5muxz_t"/><stop offset="1" class="tdhijwbfm"/></radialGradient><radialGradient id="iVytu2b" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.23 6.14)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="b9m3k9r2b"/><stop offset="1" class="mkc39zb9h"/></radialGradient><radialGradient id="i97JRac" cx="0" cy="0" r="1" gradientTransform="matrix(.59766 .66937 -3.1595 2.82105 8.725 3.786)" gradientUnits="userSpaceOnUse"><stop class="wyik6iche"/><stop offset="1" class="g2x2jxbfq"/></radialGradient><radialGradient id="ihGNt9r" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57172 2.16536 -4.16467 -4.94623 24.454 5.531)" gradientUnits="userSpaceOnUse"><stop class="c2k9t5bpp"/><stop offset="1" class="y1r1v2b6d"/></radialGradient><radialGradient id="iGyQx8d" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.105 2.124)" gradientUnits="userSpaceOnUse"><stop class="h4ehjy6dd"/><stop offset="1" class="bj832jb3d"/></radialGradient><radialGradient id="icmYSIb" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.167 16.74)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop class="y1z543b6m"/><stop offset="1" class="qetg81_po"/></radialGradient><radialGradient id="ihV1hFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.1096 -1.29967 5.61008 -.47306 12.85 3.618)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="iGxVyUb" cx="0" cy="0" r="1" gradientTransform="rotate(-154.592 7.914 .072)scale(1.08537 1.14754)" gradientUnits="userSpaceOnUse"><stop class="k84rzffkc"/><stop offset="1" class="f63cqv7mt"/></radialGradient><radialGradient id="ikSaAoe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.56426 2.0201 -2.31983 -4.09312 20.907 1.625)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="iCXMSTb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.888 11.894 -9.526)scale(1.42374 5.9709)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="ow_pc7b8u"/><stop offset=".979" class="d9x2ylwjm"/></radialGradient><radialGradient id="i324Zzd" cx="0" cy="0" r="1" gradientTransform="matrix(.01226 -1.01716 4.43025 .05338 14.076 3.949)" gradientUnits="userSpaceOnUse"><stop offset=".747" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="ik7jzUd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.878 8.977 -1.511)scale(1.11775 .93295)" gradientUnits="userSpaceOnUse"><stop class="k84rzffkc"/><stop offset="1" class="f63cqv7mt"/></radialGradient><radialGradient id="i5UxMMe" cx="0" cy="0" r="1" gradientTransform="rotate(130.332 9.644 5.017)scale(5.09325 5.91748)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="iKhIFkd" cx="0" cy="0" r="1" gradientTransform="matrix(.09206 -1.68795 4.97536 .27136 18.493 4.532)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="dk1glybfm"/><stop offset=".979" class="a0yyvkbzn"/></radialGradient><radialGradient id="iAIr5jU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21324 6.39051 0 13.802 4.892)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="iHf8wmT" cx="0" cy="0" r="1" gradientTransform="rotate(-130.37 8.898 -.855)scale(1.0406 .9935)" gradientUnits="userSpaceOnUse"><stop class="k84rzffkc"/><stop offset="1" class="f63cqv7mt"/></radialGradient><radialGradient id="iI4Fcud" cx="0" cy="0" r="1" gradientTransform="rotate(146.114 9.095 4.59)scale(3.02405 3.27841)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="iXSR1Qb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.13777 3.28035 0 18.344 4.84)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="dk1glybfm"/><stop offset=".979" class="a0yyvkbzn"/></radialGradient><radialGradient id="iiQfQjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.01775 -1.34298 3.63064 -.04798 13.469 6.04)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="icXRAhd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23453 3.00551 -3.33751 -2.48137 19.578 3.354)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="i0pQHze" cx="0" cy="0" r="1" gradientTransform="matrix(.10954 -1.26306 4.00443 .3473 18.766 5.906)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="dk1glybfm"/><stop offset=".829" class="a0yyvkbzn"/></radialGradient><radialGradient id="i40TVzb" cx="0" cy="0" r="1" gradientTransform="rotate(99.386 9.203 10.279)scale(4.22369 15.0701)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="e9zt1qbrs"/><stop offset="1" class="tenu6ccuh"/></radialGradient><radialGradient id="iTTizpc" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9.1 -1.199)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="n-vzpx_le"/><stop offset="1" class="g15wokvee"/></radialGradient><radialGradient id="itp1FHl" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.559 6.825)" gradientUnits="userSpaceOnUse"><stop class="ui8aeifuz"/><stop offset="1" class="xok7o2bsm"/></radialGradient><linearGradient id="i25FFtc" x1="21.428" x2="20.881" y1="16.843" y2="16.816" gradientUnits="userSpaceOnUse"><stop class="a6h4eccro"/><stop offset="1" class="hc39pg7fn"/></linearGradient><linearGradient id="iLVpXWc" x1="16.308" x2="16.308" y1="17.84" y2="13.871" gradientUnits="userSpaceOnUse"><stop offset=".741" class="lvid0bb9o"/><stop offset="1" class="gjpwdip4m"/></linearGradient><linearGradient id="i2CLU5c" x1="17.049" x2="15.943" y1="16.468" y2="16.576" gradientUnits="userSpaceOnUse"><stop class="rdbtoejba"/><stop offset="1" class="a2z1fpb9n"/></linearGradient><linearGradient id="iKfQLQO" x1="16.095" x2="16.095" y1="18.047" y2="17.262" gradientUnits="userSpaceOnUse"><stop offset=".101" class="keod60bpm"/><stop offset="1" class="qj9ew8b_c"/></linearGradient><linearGradient id="iVGj2Lb" x1="14.921" x2="15.479" y1="16.929" y2="17.036" gradientUnits="userSpaceOnUse"><stop class="znmb3fb4r"/><stop offset="1" class="to12_j7al"/></linearGradient><linearGradient id="i59Pwse" x1="15.829" x2="15.829" y1="18.172" y2="17.719" gradientUnits="userSpaceOnUse"><stop offset=".138" class="c3ge4lhvs"/><stop offset=".655" class="fl-4fwrbl"/></linearGradient><linearGradient id="iA7H0Md" x1="15.943" x2="15.943" y1="14.889" y2="15.508" gradientUnits="userSpaceOnUse"><stop offset=".063" class="n02jzkb8e"/><stop offset="1" class="f_l1a6bdh"/></linearGradient><linearGradient id="iAjsrWd" x1="19.166" x2="18.824" y1="15.215" y2="15.425" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBhDbYc" x1="14.377" x2="14.036" y1="15.215" y2="15.425" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iO33JDd" x1="13.883" x2="11.425" y1="12.595" y2="13.405" gradientUnits="userSpaceOnUse"><stop class="t94urlgya"/><stop offset="1" class="rmx9trbgz"/></linearGradient><linearGradient id="iXmMBBo" x1="19.478" x2="17.096" y1="12.813" y2="12.488" gradientUnits="userSpaceOnUse"><stop class="t94urlgya"/><stop offset="1" class="rmx9trbgz"/></linearGradient><linearGradient id="icvYwTb" x1="14.97" x2="15.458" y1="19.769" y2="18.887" gradientUnits="userSpaceOnUse"><stop class="u66tsvb2y"/><stop offset=".537" class="f-iusn0xx"/></linearGradient><linearGradient id="ilvNJVu" x1="24.522" x2="10.056" y1="13.017" y2="32.866" gradientUnits="userSpaceOnUse"><stop class="eod5jnblz"/><stop offset="1" class="afa9xwbaj"/></linearGradient><linearGradient id="i9QzLKe" x1="11.261" x2="7.292" y1="23.796" y2="27.921" gradientUnits="userSpaceOnUse"><stop class="j2t7368de"/><stop offset=".582" class="x05lq4b2v"/></linearGradient><linearGradient id="iuMpIUd" x1="14.256" x2="10.73" y1="2.862" y2="4.623" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="ixjabce" x1="19.026" x2="21.096" y1="2.862" y2="3.308" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="iguAwPv" x1="16.578" x2="21.666" y1="3.42" y2="3.964" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="iXHReae" x1="15.281" x2="12.229" y1="3.571" y2="4.697" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="i4Poovh" x1="18.493" x2="20.12" y1="3.571" y2="3.901" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="ieW5cId" x1="15.613" x2="20.776" y1="4.552" y2="4.528" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="iWqBPXc" x1="14.951" x2="12.46" y1="4.44" y2="5.551" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="iVXvlDY" x1="18.344" x2="19.909" y1="4.44" y2="4.508" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="iroVxeQ" x1="16.311" x2="19.955" y1="4.849" y2="4.821" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="ikNgKGb" x1="14.466" x2="11.783" y1="5.402" y2="6.016" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="iQmpx9d" x1="19.584" x2="20.211" y1="5.528" y2="5.655" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="iqlphle" x1="16.844" x2="20.289" y1="6.156" y2="6.143" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="iRTLnJe" x1="14.645" x2="11.594" y1="5.534" y2="6.255" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient><linearGradient id="isezRKd" x1="15.116" x2="11.594" y1="4.481" y2="5.663" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient><linearGradient id="ivOTmHr" x1="15.249" x2="11.729" y1="3.496" y2="4.677" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient><linearGradient id="iX7DEhe" x1="14.43" x2="11.184" y1="2.683" y2="4.707" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient><filter id="ibgnkPc" width="11.877" height="14.137" x="10.431" y="8.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.309804 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3722"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.290196 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3722" result="effect2_innerShadow_4002_3722"/></filter><filter id="irKMh7b" width="4.044" height="5.157" x="13.696" y="14.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".5"/></filter><filter id="iLA8tdb" width="2.244" height="3.357" x="14.821" y="14.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".05"/></filter><filter id="iPaYUDe" width="14.015" height="9.054" x="8.935" y="5.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.12549 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3722"/></filter><filter id="iTWWa7b" width="7.25" height="6.272" x="9.295" y="6.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.239216 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3722"/><feGaussianBlur result="effect2_foregroundBlur_4002_3722" stdDeviation=".15"/></filter><filter id="iYzKGkd" width="6.779" height="6.015" x="15.919" y="7.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.192157 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3722"/><feGaussianBlur result="effect2_foregroundBlur_4002_3722" stdDeviation=".15"/></filter><filter id="iCCKRId" width=".839" height=".74" x="17.528" y="14.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".05"/></filter><filter id="iGMtDyG" width=".935" height=".959" x="18.452" y="14.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".1"/></filter><filter id="iiwP7de" width="1.038" height="1.097" x="13.615" y="14.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".1"/></filter><filter id="iuOcO6b" width=".976" height=".749" x="12.784" y="14.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".05"/></filter><filter id="i17pmNc" width="1.402" height="2.546" x="9.397" y="14.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".125"/></filter><filter id="ixTDDPe" width="1.531" height="2.572" x="21.158" y="14.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".125"/></filter><filter id="ittBlNb" width="2.544" height="1.086" x="11.838" y="12.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.12549 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3722"/></filter><filter id="iEyBPOe" width="2.594" height="1.136" x="11.763" y="12.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".125"/></filter><filter id="itzjWne" width="2.544" height="1.086" x="17.604" y="12.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.12549 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3722"/></filter><filter id="itRGS5x" width="2.594" height="1.136" x="17.529" y="12.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".125"/></filter><filter id="iUxb5Sd" width="16.188" height="8.656" x="9.167" y="22.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".5"/></filter><filter id="ieUTEUb" width="4.094" height="4.656" x="7.917" y="23.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".25"/></filter><filter id="iZkrl9d" width="3.508" height="1.177" x="11.47" y="5.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".125"/></filter><filter id="iD9ZQZa" width="4.104" height="1.115" x="11.336" y="3.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".125"/></filter><filter id="igzDtxd" width="4.104" height="1.115" x="11.47" y="3.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".125"/></filter><filter id="inqDbVb" width="4.288" height="1.471" x="10.456" y="2.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3722" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-ok-medium" /></template>
<style>
.a-2r3fbgq {
  stop-color: var(--svg-color--9d4635, #9D4635);
  stop-opacity: 0;
}

.a0opghbrh {
  stop-color: var(--svg-color--6a3431, #6A3431);
  stop-opacity: 0;
}

.a0yyvkbzn {
  stop-color: var(--svg-color--a48369, #A48369);
}

.a2z1fpb9n {
  stop-color: var(--svg-color--c79d85, #C79D85);
  stop-opacity: 0;
}

.a3aywi70u {
  stop-color: var(--svg-color--c79e8c, #C79E8C);
  stop-opacity: 0;
}

.a6h4eccro {
  stop-color: var(--svg-color--986757, #986757);
}

.a7lv1ybzm {
  stop-color: var(--svg-color--be8c80, #BE8C80);
}

.aeh-ojcyt {
  stop-color: var(--svg-color--c7482a, #C7482A);
}

.afa9xwbaj {
  stop-color: var(--svg-color--db4f17, #DB4F17);
}

.ah2l1obip {
  stop-color: var(--svg-color--935768, #935768);
}

.apk6h_s6w {
  stop-color: var(--svg-color--3f2030, #3F2030);
  stop-opacity: 0;
}

.as1mkr9ou {
  stop-color: var(--svg-color--664747, #664747);
}

.au361rb0r {
  stop-color: var(--svg-color--5f443e, #5F443E);
}

.aubonyh_z {
  stop-color: var(--svg-color--6a4b49, #6A4B49);
  stop-opacity: 0;
}

.b_rfybbbi {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
  stop-opacity: 0;
}

.b57ou_b9t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.615 3.765c.43-.11 1.65-.274 2.666-.149");
}

.b9m3k9r2b {
  stop-color: var(--svg-color--ae8671, #AE8671);
}

.bhqqd7bcd {
  stop-color: var(--svg-color--bd897a, #BD897A);
  stop-opacity: 0;
}

.bj832jb3d {
  stop-color: var(--svg-color--9a7d65, #9A7D65);
  stop-opacity: 0;
}

.bps78hksv {
  stop-color: var(--svg-color--942d01, #942D01);
}

.bwxbq0bkg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.295 5.655c.273-.101 1.101-.304 2.171-.242");
}

.by6guy4wy {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
  stop-opacity: 0;
}

.byra0jsyn {
  stop-color: var(--svg-color--4a3839, #4A3839);
}

.c2k9t5bpp {
  stop-color: var(--svg-color--c9a083, #C9A083);
}

.c36yqwb8n {
  d: path("M18.321 14.637a.972.972 0 0 1 .936 1.227H17.38a.975.975 0 0 1 .94-1.228");
}

.c3ge4lhvs {
  stop-color: var(--svg-color--905464, #905464);
}

.cexw7pbgs {
  stop-color: var(--svg-color--bd8f73, #BD8F73);
}

.ch9vaeb5u {
  stop-color: var(--svg-color--4a3839, #4A3839);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctebkkhca {
  fill: var(--svg-color--4f2c33, #4F2C33);
  d: path("M16.222 9.58a3 3 0 0 1-.072-.15a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.823 1.646-3.823 3.679v.3c-.37-.283-.676-.57-.676-1.532c0-1.608 2.705-3.588 4.105-3.96a6 6 0 0 1 1.723-.177c.468.017.8.42.805.888l.016 1.391z");
}

.cuyeqyb9v {
  stop-color: var(--svg-color--c79e8c, #C79E8C);
}

.d2zfpbyds {
  fill: var(--svg-color--8d5a5e, #8D5A5E);
  d: path("m15.414 15.435l-.691 2.002c-.119.411.165.823.566.823h.857c.401 0 .684-.418.566-.823l-.578-2.002c-.124-.443-.59-.443-.72 0");
}

.d9x2ylwjm {
  stop-color: var(--svg-color--b99477, #B99477);
}

.dk116n8kk {
  stop-color: var(--svg-color--b58c7f, #B58C7F);
}

.dk1glybfm {
  stop-color: var(--svg-color--a48369, #A48369);
  stop-opacity: 0;
}

.dkkvyqbbp {
  d: path("M9.51 3.359a61 61 0 0 0-1.79 1.61a.08.08 0 0 0-.027.054c-.033.574 1.968 1.625 3.038 2.013q.017.006.034.006c.941-.004 1.105-.372 1.736-.664c.727-.336 1.477-.309 1.867-.309c.391 0 .602-.218.696-.414c.063-.132.064-.316-.03-.523a.63.63 0 0 0 .442-.281a.64.64 0 0 0 .057-.625c.156-.063.336-.304.312-.649c-.037-.537-.494-.37-.713-.366l-.232-.29c.012-.55-.585-.6-.815-.574l-1.717.097a.98.98 0 0 0-.765-.132c-.432.122-1.264.338-2.094 1.047");
}

.dvyrp5bps {
  stop-color: var(--svg-color--916855, #916855);
}

.dz3ns1n_g {
  stop-color: var(--svg-color--c39d8a, #C39D8A);
  stop-opacity: 0;
}

.e-tyzrmey {
  fill: var(--svg-color--4b312f, #4B312F);
  fill-rule: evenodd;
  d: path("M17.922 12.899c.79-.127 1.468.194 1.69.354a.275.275 0 1 0 .323-.444c-.31-.226-1.134-.608-2.1-.453a.275.275 0 0 0 .087.543");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e13mj1was {
  d: path("M18.25 14.842c.069.093-.076.205-.24.329c-.165.123-.287.21-.356.117c-.07-.093.008-.268.172-.39c.165-.124.354-.149.424-.056");
}

.e4s700vze {
  stop-color: var(--svg-color--764b4b, #764B4B);
}

.e9zt1qbrs {
  stop-color: var(--svg-color--9e6d71, #9E6D71);
  stop-opacity: 0;
}

.ebnbqcb_c {
  d: path("M22.637 3.359a61 61 0 0 1 1.79 1.61a.08.08 0 0 1 .027.054c.032.574-1.969 1.625-3.039 2.013a.1.1 0 0 1-.034.006c-.941-.004-1.105-.372-1.736-.664c-.726-.336-1.476-.309-1.867-.309c-.39 0-.602-.218-.695-.414c-.064-.132-.065-.316.029-.523a.63.63 0 0 1-.442-.281a.64.64 0 0 1-.056-.625c-.157-.063-.337-.304-.313-.649c.038-.537.592-.465.81-.46l.136-.196c-.013-.55.585-.6.814-.574l1.717.097a.98.98 0 0 1 .766-.132c.432.122 1.263.338 2.093 1.047");
}

.eg11r1-xe {
  stop-color: var(--svg-color--c7482a, #C7482A);
  stop-opacity: 0;
}

.ekpp6jgni {
  stop-color: var(--svg-color--915b65, #915B65);
}

.enp78gnvj {
  stop-color: var(--svg-color--3b2e2d, #3B2E2D);
}

.eod5jnblz {
  stop-color: var(--svg-color--ff5918, #FF5918);
}

.ew56wjbup {
  stop-color: var(--svg-color--ff7532, #FF7532);
}

.ez24-xbem {
  width: 4.615px;
  height: 6.587px;
  x: 13.663px;
  y: 18.26px;
  rx: 2.307px;
}

.f_fss5bgi {
  stop-color: var(--svg-color--432033, #432033);
}

.f_l1a6bdh {
  stop-color: var(--svg-color--a47571, #A47571);
  stop-opacity: 0;
}

.f-iegb-dq {
  stop-color: var(--svg-color--ff5930, #FF5930);
}

.f-iusn0xx {
  stop-color: var(--svg-color--aa817a, #AA817A);
  stop-opacity: 0;
}

.f0kf0_3nd {
  stop-color: var(--svg-color--432033, #432033);
  stop-opacity: 0;
}

.f0ompqbwt {
  stop-color: var(--svg-color--3f2030, #3F2030);
}

.f3emps4bt {
  stop-color: var(--svg-color--81474f, #81474F);
}

.f63cqv7mt {
  stop-color: var(--svg-color--82594c, #82594C);
  stop-opacity: 0;
}

.fh1_5ac_k {
  stop-color: var(--svg-color--942d01, #942D01);
  stop-opacity: 0;
}

.fjos8cb-d {
  stop-color: var(--svg-color--764b4b, #764B4B);
  stop-opacity: 0;
}

.fl-4fwrbl {
  stop-color: var(--svg-color--905464, #905464);
  stop-opacity: 0;
}

.fr8wppbrf {
  stop-color: var(--svg-color--60504f, #60504F);
}

.ft5dv1b6b {
  fill: none;
}

.fycafc3yi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.773 13.03c-.266-.192-1.017-.543-1.894-.403");
}

.fycekabph {
  cx: 13.272px;
  cy: 15.052px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.424px;
  ry: 0.215px;
}

.g15wokvee {
  stop-color: var(--svg-color--925a61, #925A61);
  stop-opacity: 0;
}

.g1bdywbbk {
  stop-color: var(--svg-color--ad4002, #AD4002);
}

.g2x2jxbfq {
  stop-color: var(--svg-color--907664, #907664);
  stop-opacity: 0;
}

.ghg-e1bfu {
  cx: 13.272px;
  cy: 15.052px;
  rx: 0.424px;
  ry: 0.215px;
}

.gjpwdip4m {
  stop-color: var(--svg-color--a97f6f, #A97F6F);
  stop-opacity: 0;
}

.golbtmbys {
  stop-color: var(--svg-color--935768, #935768);
  stop-opacity: 0;
}

.gsbxves2y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.113 13.03c.266-.192 1.017-.543 1.894-.403");
}

.h-qwb4b2p {
  stop-color: var(--svg-color--947061, #947061);
  stop-opacity: 0;
}

.h4ehjy6dd {
  stop-color: var(--svg-color--9a7d65, #9A7D65);
}

.h9fb5bbiv {
  stop-color: var(--svg-color--ffa143, #FFA143);
}

.hc39pg7fn {
  stop-color: var(--svg-color--986757, #986757);
  stop-opacity: 0;
}

.hiycpfc4f {
  stop-color: var(--svg-color--ff711c, #FF711C);
}

.hmenlybab {
  d: path("M14.453 15.494c0-.314-.255-.523-.324-.586l-.314.303l.193.393z");
}

.hpjidqofk {
  stop-color: var(--svg-color--6a3431, #6A3431);
}

.i-v4lm-fq {
  stop-color: var(--svg-color--99755e, #99755E);
  stop-opacity: 0;
}

.i4aahzyol {
  stop-color: var(--svg-color--99755e, #99755E);
}

.iiuwv9vea {
  stop-color: var(--svg-color--885557, #885557);
}

.j_cg2wc4l {
  stop-color: var(--svg-color--93665c, #93665C);
}

.j1090kf1c {
  stop-color: var(--svg-color--ff6428, #FF6428);
  stop-opacity: 0;
}

.j26seachc {
  stop-color: var(--svg-color--ff8547, #FF8547);
}

.j2t7368de {
  stop-color: var(--svg-color--ef6736, #EF6736);
}

.j4pghpbnq {
  fill: var(--svg-color--503039, #503039);
  d: path("m21.618 13.26l-.032-.687c-.011-.831-.698-1.517-1.53-1.552h-1.524c-1.237 0-1.936-.898-2.273-1.949c-.236-.735.631-1.32 1.395-1.214c.905.125 1.914.21 3.342 1.141c1.899 1.239 1.622 3.21.622 4.261");
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jd3h1p_cf {
  stop-color: var(--svg-color--bd8f73, #BD8F73);
  stop-opacity: 0;
}

.jjmtttbid {
  stop-color: var(--svg-color--916b60, #916B60);
}

.jq7m5akyh {
  stop-color: var(--svg-color--7d403e, #7D403E);
}

.jtevqibrq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.07 3.46c-.68-.344-2.469-.57-3.188-.523");
}

.jv53r67zu {
  stop-color: var(--svg-color--915b65, #915B65);
  stop-opacity: 0;
}

.k_4cqj2sv {
  stop-color: var(--svg-color--ab7670, #AB7670);
}

.k84rzffkc {
  stop-color: var(--svg-color--82594c, #82594C);
}

.keod60bpm {
  stop-color: var(--svg-color--9b5f70, #9B5F70);
}

.kf7k4hbsb {
  stop-color: var(--svg-color--210a0d, #210A0D);
}

.khte_tzpb {
  d: path("M13.565 14.637a.972.972 0 0 0-.936 1.227h1.877a1 1 0 0 0 .035-.256a.98.98 0 0 0-.976-.971");
}

.l9hx93vcp {
  stop-color: var(--svg-color--7c4446, #7C4446);
}

.lda3x_b4r {
  stop-color: var(--svg-color--be8c80, #BE8C80);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lvid0bb9o {
  stop-color: var(--svg-color--a97f6f, #A97F6F);
}

.m_2922ixt {
  stop-color: var(--svg-color--9d4635, #9D4635);
}

.m-g55uf3j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.492 4.577c-.43-.11-1.28-.203-2.296-.078");
}

.m4u9ezbad {
  stop-color: var(--svg-color--6b453e, #6B453E);
}

.mgz6y4bsd {
  stop-color: var(--svg-color--ab8570, #AB8570);
}

.mjonlnn_a {
  d: path("M9.51 3.359a61 61 0 0 0-1.79 1.61a.08.08 0 0 0-.027.054c-.033.574 1.968 1.625 3.038 2.013q.017.006.034.006c.941-.004 1.105-.372 1.736-.664c.727-.336 1.477-.309 1.867-.309c.391 0 .602-.218.696-.414c.063-.132.064-.316-.03-.523a.63.63 0 0 0 .442-.281a.64.64 0 0 0 .057-.625c.156-.063.336-.304.312-.649c-.037-.537-.562-.661-.781-.656H14.9c.012-.55-.585-.6-.815-.574l-1.717.097a.98.98 0 0 0-.765-.132c-.432.122-1.264.338-2.094 1.047");
}

.mkc39zb9h {
  stop-color: var(--svg-color--a58268, #A58268);
}

.mqq2pckgy {
  stop-color: var(--svg-color--ff711c, #FF711C);
  stop-opacity: 0;
}

.n-vzpx_le {
  stop-color: var(--svg-color--925a61, #925A61);
}

.n02jzkb8e {
  stop-color: var(--svg-color--a47571, #A47571);
}

.nb0xkbc5s {
  fill: var(--svg-color--4b312f, #4B312F);
  fill-rule: evenodd;
  d: path("M13.964 12.899c-.79-.127-1.468.194-1.69.354a.275.275 0 1 1-.323-.444c.31-.226 1.134-.608 2.1-.453a.275.275 0 1 1-.087.543");
}

.nlhhwjb1r {
  stop-color: var(--svg-color--93665c, #93665C);
  stop-opacity: 0;
}

.nswj93bty {
  stop-color: var(--svg-color--bd897a, #BD897A);
}

.ntnujibcy {
  stop-color: var(--svg-color--60504f, #60504F);
  stop-opacity: 0;
}

.nwoksp-my {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.654 4.577c.43-.11 1.281-.203 2.297-.078");
}

.ny-jsdbat {
  stop-color: var(--svg-color--a16353, #A16353);
}

.nyi6_naly {
  stop-color: var(--svg-color--4d3b39, #4D3B39);
}

.o_9_81b8h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.12 3.901c-.43-.11-2.375-.476-3.254-.265");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ow_pc7b8u {
  stop-color: var(--svg-color--b99477, #B99477);
  stop-opacity: 0;
}

.p-_rdwbrl {
  d: path("M22.637 3.359a61 61 0 0 1 1.79 1.61a.08.08 0 0 1 .027.054c.032.574-1.969 1.625-3.039 2.013a.1.1 0 0 1-.034.006c-.941-.004-1.105-.372-1.736-.664c-.726-.336-1.476-.309-1.867-.309c-.39 0-.602-.218-.695-.414c-.064-.132-.065-.316.029-.523a.63.63 0 0 1-.442-.281a.64.64 0 0 1-.056-.625c-.157-.063-.337-.304-.313-.649c.038-.537.563-.661.782-.656h.164c-.013-.55.585-.6.814-.574l1.717.097a.98.98 0 0 1 .766-.132c.432.122 1.263.338 2.093 1.047");
}

.p4lcx2a4b {
  d: path("M16.222 9.58a3 3 0 0 1-.072-.15a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.823 1.646-3.823 3.679v.3c-.37-.283-.676-.57-.676-1.532c0-1.608 2.705-3.588 4.105-3.96a6 6 0 0 1 1.723-.177c.468.017.8.42.805.888l.016 1.391z");
}

.p5xde80ny {
  stop-color: var(--svg-color--6b453e, #6B453E);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm_eeybbf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.845 5.835c.391-.173 1.476-.503 2.758-.41");
}

.pr8brkb_h {
  stop-color: var(--svg-color--ff7840, #FF7840);
  stop-opacity: 0;
}

.pv_1ruamy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.077 3.46c.68-.344 2.468-.57 3.187-.523");
}

.pw9q04bxy {
  stop-color: var(--svg-color--4d3b39, #4D3B39);
  stop-opacity: 0;
}

.q5texu1ss {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.25 14.842c.069.093-.076.205-.24.329c-.165.123-.287.21-.356.117c-.07-.093.008-.268.172-.39c.165-.124.354-.149.424-.056");
}

.q973iyb6t {
  d: path("M7.307 5.64c-.203-.058-.677-.155-.945-.086c-.336.086-.594.328-.813.687a958 958 0 0 0-2.094 3.54c-.562.822-1.625 3.087-1.375 5.562c.1 1.662.782 3.339 1.11 3.969l4.132 7.854c.173.33.187.719.08 1.076c-.157.529-.322 1.28-.322 2.023h17.828c0-.743-.164-1.494-.322-2.023a1.43 1.43 0 0 1 .08-1.076l4.133-7.854c.328-.63 1.01-2.307 1.11-3.97c.25-2.474-.813-4.739-1.375-5.562a915 915 0 0 0-2.094-3.539c-.219-.359-.477-.601-.813-.687c-.268-.069-.742.028-.945.086l-3.188 2.164c-.351.414-.19.966-.054 1.18l2.075 3.511a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a14 14 0 0 0-1.12-.483a4.3 4.3 0 0 1-.775.336v.023a2.307 2.307 0 0 1-4.614 0v-.009a4.3 4.3 0 0 1-.782-.329c-.395.155-.762.312-1.064.462a.37.37 0 0 1-.493-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382l2.075-3.511c.136-.214.297-.766-.055-1.18z");
}

.qd38sjb7e {
  stop-color: var(--svg-color--ff7532, #FF7532);
  stop-opacity: 0;
}

.qetg81_po {
  stop-color: var(--svg-color--ff8543, #FF8543);
  stop-opacity: 0;
}

.qi0665bes {
  fill: var(--svg-color--000, #000);
  d: path("M14.122 15.608a.554.554 0 0 0-.557-.556a.554.554 0 0 0-.494.813h.985a.55.55 0 0 0 .066-.257");
}

.qj9ew8b_c {
  stop-color: var(--svg-color--9b5f70, #9B5F70);
  stop-opacity: 0;
}

.qkq4f9buv {
  stop-color: var(--svg-color--473633, #473633);
}

.qo-e1l5lk {
  stop-color: var(--svg-color--8b4c45, #8B4C45);
}

.qrzabx_4z {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.34 14.34a1.52 1.52 0 0 0-1.475 1.153a.3.3 0 0 0 .291.371h2.43a.25.25 0 0 0 .247-.296a1.525 1.525 0 0 0-1.493-1.227");
}

.qso4uy3-n {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
}

.rdbtoejba {
  stop-color: var(--svg-color--c79d85, #C79D85);
}

.rdmu-zisu {
  stop-color: var(--svg-color--88564c, #88564C);
}

.re3qjtb0n {
  stop-color: var(--svg-color--916855, #916855);
  stop-opacity: 0;
}

.rhx-o-b8q {
  stop-color: var(--svg-color--ab7670, #AB7670);
  stop-opacity: 0;
}

.rjf2cql4s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.852 5.655c-.274-.101-1.102-.304-2.172-.242");
}

.rmx9trbgz {
  stop-color: var(--svg-color--584141, #584141);
  stop-opacity: 0;
}

.rsdjdrd8e {
  stop-color: var(--svg-color--ff8547, #FF8547);
  stop-opacity: 0;
}

.rzbok0aqc {
  d: path("M19.186 15.48a.9.9 0 0 0-.252-.503l-.282.31l.127.248z");
}

.rzk9brbsy {
  stop-color: var(--svg-color--7f4c4c, #7F4C4C);
}

.rzr27zurw {
  fill: var(--svg-color--543532, #543532);
  d: path("M21.229 8.768c.56.192 1.062.584 1.38 1.144a2.58 2.58 0 0 1-.116 2.75c-.19.281-.294.614-.294.952v1.294a1.9 1.9 0 0 0-.727-.292l.086-1.749a1.58 1.58 0 0 0-1.502-1.56h-1.524c-1.04 0-1.98-.612-2.408-1.57a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.638 1.646-3.638 3.678l.034 1.674c-.277.04-.566.133-.784.287v-1.306c0-.34-.104-.672-.295-.952A2.6 2.6 0 0 1 9.23 10a2.55 2.55 0 0 1 1.415-1.227c.624-.221 1.026-.607 1.378-1.173c.45-.719 1.37-1.232 2.277-1.232c.353 0 .687.045.999.173c.416.181.883.181 1.299 0c.306-.128.641-.173.994-.173c.918 0 1.72.496 2.165 1.232c.335.554.86.957 1.473 1.168");
}

.snr48fb6s {
  stop-color: var(--svg-color--9b6d63, #9B6D63);
}

.stu3d4b7y {
  d: path("m21.618 13.26l-.032-.687c-.011-.831-.698-1.517-1.53-1.552h-1.524c-1.237 0-1.936-.898-2.273-1.949c-.236-.735.631-1.32 1.395-1.214c.905.125 1.914.21 3.342 1.141c1.899 1.239 1.622 3.21.622 4.261");
}

.t94urlgya {
  stop-color: var(--svg-color--584141, #584141);
}

.tdhijwbfm {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
  stop-opacity: 0;
}

.tenu6ccuh {
  stop-color: var(--svg-color--6a4046, #6A4046);
}

.thano8bvw {
  d: path("M10.69 19.01a4.26 4.26 0 0 0 4.23 3.708h2.055a4.26 4.26 0 0 0 4.23-3.708c.129-2.05.258-4.093.353-6.143a1.58 1.58 0 0 0-1.501-1.56h-1.525c-1.04 0-1.98-.612-2.408-1.57a.72.72 0 0 0-.67-.455H14.07c-2.01 0-3.638 1.646-3.638 3.678c0 2.026.126 4.02.26 6.05");
}

.to12_j7al {
  stop-color: var(--svg-color--8e5d4e, #8E5D4E);
  stop-opacity: 0;
}

.tu_5mkbaw {
  fill: var(--svg-color--000, #000);
  d: path("M17.765 15.608c0-.309.247-.556.556-.556a.554.554 0 0 1 .495.812h-.985a.5.5 0 0 1-.066-.256");
}

.u02a1vtwi {
  d: path("M21.236 17.36c.365-.011.706-.135.985-.335v1.014c0 .972-.58 1.838-1.46 2.198q.28-.594.376-1.285z");
}

.u66tsvb2y {
  stop-color: var(--svg-color--aa817a, #AA817A);
}

.ucvon1e0f {
  d: path("m15.527 15.222l-.579 2.001c-.118.412.165.824.567.824h.856c.402 0 .685-.418.567-.824l-.579-2.001c-.124-.444-.702-.444-.832 0");
}

.ui8aeifuz {
  stop-color: var(--svg-color--b48376, #B48376);
}

.uj-ttlabc {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.546 14.34c.711 0 1.312.49 1.475 1.153a.298.298 0 0 1-.291.371H17.3a.25.25 0 0 1-.247-.296a1.52 1.52 0 0 1 1.493-1.227");
}

.uohk86iby {
  d: path("M10.65 17.36a1.8 1.8 0 0 1-.984-.335v1.014c0 .972.579 1.838 1.46 2.198a4.5 4.5 0 0 1-.377-1.285z");
}

.urahr5ysp {
  fill: var(--svg-color--88004e, #88004E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.446 18.606c.44.23.965.361 1.524.361c.565 0 1.084-.131 1.524-.36v-.001a.22.22 0 0 1 .263.043a.205.205 0 0 1 .023.263m-3.334-.306l3.292.278m-3.292-.278a.22.22 0 0 0-.263.045a.2.2 0 0 0-.022.26m.285-.305l-.244.278m3.578.028l-.042-.028m.042.028l-.042-.028m.042.028c-.383.58-1.05.967-1.81.967s-1.426-.387-1.81-.967m3.578-.028a2.11 2.11 0 0 1-1.768.945a2.11 2.11 0 0 1-1.768-.945m-.041.028l.04-.028m-.04.028l.04-.028");
}

.v-fcszbji {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.845 3.754c.46-.173 1.847-.439 3.353-.346");
}

.ve2ly-bfr {
  stop-color: var(--svg-color--b58c7f, #B58C7F);
  stop-opacity: 0;
}

.vj5muxz_t {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
}

.vz10a6buo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.83 3.354c.434-.235 2.033-.622 3.539-.721");
}

.w67-oq7ms {
  stop-color: var(--svg-color--664747, #664747);
  stop-opacity: 0;
}

.wjf3cr6ec {
  stop-color: var(--svg-color--c39d8a, #C39D8A);
}

.wkfrpjs0r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.711 4.74c.46-.173 1.847-.439 3.354-.347");
}

.wnyjcjb4k {
  stop-color: var(--svg-color--6a4b49, #6A4B49);
}

.woz3hacrx {
  stop-color: var(--svg-color--ad4002, #AD4002);
  stop-opacity: 0;
}

.wthpf-bib {
  d: path("M23.933 27.421c-1.95-1.2-3.036-3.417-3.36-4.156c-5.174 0-9.28 1.969-10.406 6.656h14.188c0-.9-.156-1.937-.422-2.5");
}

.wyik6iche {
  stop-color: var(--svg-color--907664, #907664);
}

.x05lq4b2v {
  stop-color: var(--svg-color--ef6736, #EF6736);
  stop-opacity: 0;
}

.x14xtc2ed {
  d: path("M10.459 14.696a1.04 1.04 0 0 0 .09 2.046a85 85 0 0 1-.09-2.046");
}

.x7ljgpqek {
  d: path("M21.302 17.46q.108-1.737.2-3.475a1.752 1.752 0 0 1-.2 3.475");
}

.xok7o2bsm {
  stop-color: var(--svg-color--b48376, #B48376);
  stop-opacity: 0;
}

.xpsaw3m9c {
  stop-color: var(--svg-color--845755, #845755);
}

.xxptsowmw {
  stop-color: var(--svg-color--763e40, #763E40);
}

.y1r1v2b6d {
  stop-color: var(--svg-color--97735c, #97735C);
}

.y1ra82bkx {
  stop-color: var(--svg-color--ad7e7a, #AD7E7A);
}

.y1z543b6m {
  stop-color: var(--svg-color--ff8543, #FF8543);
}

.yb4penyyu {
  d: path("M10.45 13.988a1.75 1.75 0 0 0-1.515 1.723c0 .935.733 1.7 1.656 1.75a84 84 0 0 1-.14-3.473");
}

.yhy2k9bbo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.667 26.952c.48-.448 1.67-1.706 2.594-3.156");
}

.ym0brebyc {
  stop-color: var(--svg-color--ff6a31, #FF6A31);
}

.yne9g-wvj {
  d: path("m24.755 4.91l.428.665a.24.24 0 0 1-.01.279c-.9 1.155-2.374 1.8-3.283 2.087a.244.244 0 0 1-.281-.108a20 20 0 0 1-.409-.69c-.069-.13.029-.231.086-.265L24.3 5.05l-.124-.274c.35-.106.53.045.578.133");
}

.yx2o0obdd {
  d: path("M21.408 16.759q.063-1.037.12-2.072a1.04 1.04 0 0 1-.12 2.072");
}

.zcyr97bop {
  d: path("m7.392 4.91l-.428.665a.24.24 0 0 0 .01.279c.898 1.155 2.373 1.8 3.283 2.087a.244.244 0 0 0 .28-.108c.151-.247.354-.584.41-.69c.068-.13-.03-.231-.086-.265L7.845 5.05l.125-.274c-.35-.106-.531.045-.578.133");
}

.ze5ugdbxr {
  stop-color: var(--svg-color--ff7840, #FF7840);
}

.zl4550_6y {
  d: path("M21.229 8.768c.56.192 1.062.584 1.38 1.144a2.58 2.58 0 0 1-.116 2.75c-.19.281-.294.614-.294.952v1.294a1.9 1.9 0 0 0-.727-.292l.086-1.749a1.58 1.58 0 0 0-1.502-1.56h-1.524c-1.04 0-1.98-.612-2.408-1.57a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.638 1.646-3.638 3.678l.034 1.674c-.277.04-.566.133-.784.287v-1.306c0-.34-.104-.672-.295-.952A2.6 2.6 0 0 1 9.23 10a2.55 2.55 0 0 1 1.415-1.227c.624-.221 1.026-.607 1.378-1.173c.45-.719 1.37-1.232 2.277-1.232c.353 0 .687.045.999.173c.416.181.883.181 1.299 0c.306-.128.641-.173.994-.173c.918 0 1.72.496 2.165 1.232c.335.554.86.957 1.473 1.168");
}

.znmb3fb4r {
  stop-color: var(--svg-color--8e5d4e, #8E5D4E);
}

.zpfboqufv {
  stop-color: var(--svg-color--ab8570, #AB8570);
  stop-opacity: 0;
}

.zqzqzsbzu {
  stop-color: var(--svg-color--230a0c, #230A0C);
}

</style>
