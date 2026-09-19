<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#inxWvUG)" class="u02a1vtwi"/><path fill="url(#i7PA8oe)" class="uohk86iby"/><rect fill="url(#iNIIucd)" class="ez24-xbem"/><rect fill="url(#iiFMa1d)" class="ez24-xbem"/><g filter="url(#i2Fq0Mb)"><path fill="url(#ijVJDcb)" class="thano8bvw"/><path fill="url(#iCN5DuE)" class="thano8bvw"/><path fill="url(#im2dXJe)" class="thano8bvw"/><path fill="url(#iC20tPb)" class="thano8bvw"/><path fill="url(#i8oomuS)" class="thano8bvw"/><path fill="url(#im3vVEl)" class="thano8bvw"/></g><path fill="url(#io4yHbe)" class="thano8bvw"/><path fill="url(#iDIqjXZ)" class="thano8bvw"/><path fill="url(#iKNGYuC)" class="thano8bvw"/><path fill="url(#igzgc1W)" class="thano8bvw"/><g filter="url(#iLXklAe)"><path class="y5df-gbld"/></g><g filter="url(#iRVfiYb)"><path class="of-acub0v"/><path fill="url(#iMNyXrb)" class="ucvon1e0f"/><path fill="url(#iUjSJtd)" class="ucvon1e0f"/><path fill="url(#i9PYjPc)" class="ucvon1e0f"/><path fill="url(#iqOzJhe)" class="ucvon1e0f"/><path fill="url(#iyZ5OEe)" class="ucvon1e0f"/><path fill="url(#iSgnx5b)" class="ucvon1e0f"/></g><g filter="url(#i6KhxrB)"><path class="qy1dvhj0u"/><path fill="url(#iQErvOc)" class="zl4550_6y"/><path fill="url(#iCnb0il)" class="zl4550_6y"/><path fill="url(#iFuwJpc)" class="zl4550_6y"/><path fill="url(#ifXRgpr)" class="zl4550_6y"/></g><g filter="url(#imQW7ow)"><path class="wb8s5lbxg"/><path fill="url(#iBlKhKb)" class="p4lcx2a4b"/><path fill="url(#iyf8efd)" class="p4lcx2a4b"/></g><g filter="url(#iqK6Atc)"><path class="v-5iy9jix"/><path fill="url(#iCOaw7b)" class="meysdsb0i"/><path fill="url(#i0kxAtd)" class="meysdsb0i"/><path fill="url(#iEFO54B)" class="meysdsb0i"/></g><path class="uj-ttlabc"/><path fill="url(#iJ11RKc)" class="c36yqwb8n"/><path class="tu_5mkbaw"/><g filter="url(#ihgS3sz)"><path class="q5texu1ss"/><path fill="url(#iB89jpc)" class="e13mj1was"/></g><g filter="url(#iUeR3Gd)"><path fill="url(#iAjsrWd)" class="rzbok0aqc"/></g><path class="qrzabx_4z"/><path fill="url(#i5DdZsd)" class="khte_tzpb"/><path class="qi0665bes"/><g filter="url(#i5woTHe)"><path fill="url(#iBhDbYc)" class="hmenlybab"/></g><g filter="url(#i3OQpjd)"><ellipse transform="rotate(-27.914 13.272 15.052)" class="fycekabph"/><ellipse fill="url(#i0xNNIe)" transform="rotate(-27.914 13.272 15.052)" class="ghg-e1bfu"/></g><path fill="url(#iHbPYFo)" class="x7ljgpqek"/><path fill="url(#i8iZ7Yd)" class="yb4penyyu"/><g filter="url(#iEkTtPb)"><path fill="url(#iJN2UEa)" class="x14xtc2ed"/></g><g filter="url(#iOIpWzd)"><path fill="url(#iBiZlFm)" class="yx2o0obdd"/></g><g filter="url(#i6MApZb)"><path clip-rule="evenodd" class="z_8l6fgjj"/></g><g filter="url(#itS8wCj)"><path stroke="url(#ixHICNe)" class="gsbxves2y"/></g><g filter="url(#iQjYMic)"><path clip-rule="evenodd" class="gmax2qb7j"/></g><g filter="url(#ixMw3Qc)"><path stroke="url(#i6V14ec)" class="fycafc3yi"/></g><path stroke="url(#ipqIf2c)" class="pxei7ubpz"/><path fill="url(#iwQT38c)" class="q973iyb6t"/><path fill="url(#ifdLrOb)" class="q973iyb6t"/><path fill="url(#icAnfpc)" class="q973iyb6t"/><path fill="url(#i4KnSQj)" class="q973iyb6t"/><path fill="url(#iCt4xDb)" class="q973iyb6t"/><path fill="url(#iQHkhdq)" class="q973iyb6t"/><path fill="url(#iJ2ilJb)" class="q973iyb6t"/><path fill="url(#im95KLb)" class="q973iyb6t"/><path fill="url(#iXyCdOe)" class="q973iyb6t"/><path fill="url(#iTQnL6P)" class="q973iyb6t"/><path fill="url(#ixdltTb)" class="q973iyb6t"/><path fill="url(#inxtE1c)" class="q973iyb6t"/><path fill="url(#ianl7tm)" class="zcyr97bop"/><path fill="url(#iAjEaoe)" class="zcyr97bop"/><path fill="url(#in9MEld)" class="yne9g-wvj"/><path fill="url(#ih2sZDn)" class="yne9g-wvj"/><path fill="url(#i4Wx5fe)" class="yne9g-wvj"/><path fill="url(#im4MyHb)" class="dkkvyqbbp"/><path fill="url(#i6PWSBe)" class="dkkvyqbbp"/><path fill="url(#iLcvzEe)" class="ebnbqcb_c"/><path fill="url(#iwgDMde)" class="ebnbqcb_c"/><g filter="url(#iNmk77b)"><path fill="url(#i4Ga0Yc)" class="wthpf-bib"/></g><g filter="url(#iqJgCNe)"><path stroke="url(#i5BgaYd)" class="yhy2k9bbo"/></g><path stroke="url(#irAgMNc)" class="pv_1ruamy"/><path stroke="url(#ik8Goae)" class="pv_1ruamy"/><path stroke="url(#icExggc)" class="jtevqibrq"/><path stroke="url(#iTHTcze)" class="jtevqibrq"/><path stroke="url(#i0KhBee)" class="jtevqibrq"/><path stroke="url(#imDTRAc)" class="jtevqibrq"/><path stroke="url(#i5CGYyb)" class="b57ou_b9t"/><path stroke="url(#iaWdnNc)" class="b57ou_b9t"/><path stroke="url(#inmW2Eb)" class="o_9_81b8h"/><path stroke="url(#iwuLD8c)" class="o_9_81b8h"/><path stroke="url(#izHBQOd)" class="o_9_81b8h"/><path stroke="url(#itUy5jd)" class="o_9_81b8h"/><path stroke="url(#icQV8JN)" class="nwoksp-my"/><path stroke="url(#iV7Ojnc)" class="nwoksp-my"/><path stroke="url(#ia6d0Oc)" class="m-g55uf3j"/><path stroke="url(#iyqXKdc)" class="m-g55uf3j"/><path stroke="url(#iubLhWc)" class="m-g55uf3j"/><path stroke="url(#iC4Wjhd)" class="m-g55uf3j"/><path stroke="url(#inzJGKd)" class="bwxbq0bkg"/><path stroke="url(#iEWm7Na)" class="bwxbq0bkg"/><path stroke="url(#i68Kjzc)" class="rjf2cql4s"/><path stroke="url(#iKgxBde)" class="rjf2cql4s"/><path stroke="url(#i9v985c)" class="rjf2cql4s"/><path stroke="url(#iDcGSec)" class="rjf2cql4s"/><path fill="url(#iFNcbHc)" class="p-_rdwbrl"/><path fill="url(#iNzGqld)" class="mjonlnn_a"/><path fill="url(#igFOeqc)" class="mjonlnn_a"/><g filter="url(#iTsCyed)"><path stroke="url(#ied00se)" class="pm_eeybbf"/></g><g filter="url(#iNdumsb)"><path stroke="url(#is71VFe)" class="wkfrpjs0r"/></g><g filter="url(#irCzdBb)"><path stroke="url(#i8LSxEb)" class="v-fcszbji"/></g><g filter="url(#iwLSMCb)"><path stroke="url(#i8ICqWZ)" class="vz10a6buo"/></g><defs><radialGradient id="inxWvUG" cx="0" cy="0" r="1" gradientTransform="matrix(-.83944 3.44902 -4.09716 -.99719 21.983 17.025)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="nuxnfxbgo"/><stop offset=".837" class="uyz7qki7u"/></radialGradient><radialGradient id="i7PA8oe" cx="0" cy="0" r="1" gradientTransform="rotate(61.079 -9.464 16.542)scale(3.51347 3.06144)" gradientUnits="userSpaceOnUse"><stop class="odf4c6bdk"/><stop offset=".6" class="z6pyd1pmi"/></radialGradient><radialGradient id="iNIIucd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9129 2.71352 -4.0321 4.32836 14.9 22.133)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="x94xl2b4t"/><stop offset=".911" class="eaofinhlm"/></radialGradient><radialGradient id="iiFMa1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.65016 -.8452 1.94561 -1.49665 17.972 24.598)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="wg1qd0b2y"/><stop offset="1" class="rxwcye7wj"/></radialGradient><radialGradient id="ijVJDcb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.5625 0 0 -9.92578 18.625 16.75)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="q-q1ykg6o"/><stop offset=".893" class="t3dxl1bdl"/></radialGradient><radialGradient id="iCN5DuE" cx="0" cy="0" r="1" gradientTransform="rotate(105.939 4.919 12.08)scale(4.69997 4.25479)" gradientUnits="userSpaceOnUse"><stop class="qk70xkspj"/><stop offset="1" class="svfkjdxef"/></radialGradient><radialGradient id="im2dXJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.69746 1.66534 0 13.579 14.5)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="bfvhuvgva"/><stop offset="1" class="cpvtdgbxl"/></radialGradient><radialGradient id="iC20tPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34636 1.59055 0 18.488 14.423)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="bwviuxbld"/><stop offset="1" class="pkw85ybvw"/></radialGradient><radialGradient id="i8oomuS" cx="0" cy="0" r="1" gradientTransform="matrix(-5.1875 -3.0625 5.38842 -9.12732 20.969 20.125)" gradientUnits="userSpaceOnUse"><stop class="hn68qzh9n"/><stop offset="1" class="oxf-njb4g"/></radialGradient><radialGradient id="im3vVEl" cx="0" cy="0" r="1" gradientTransform="matrix(.71877 -4.28096 6.57099 1.10326 14.562 22.72)" gradientUnits="userSpaceOnUse"><stop offset=".066" class="sp3oxjwoz"/><stop offset="1" class="rl-8iyuye"/></radialGradient><radialGradient id="iDIqjXZ" cx="0" cy="0" r="1" gradientTransform="rotate(60.555 -1.465 14.84)scale(3.35069 6.6748)" gradientUnits="userSpaceOnUse"><stop class="q-26v8b7m"/><stop offset="1" class="qfe9tz3ca"/></radialGradient><radialGradient id="iKNGYuC" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 6.3125 -1.34311 -.11303 10.189 15.438)" gradientUnits="userSpaceOnUse"><stop offset=".654" class="vawznp55w"/><stop offset="1" class="hy2odu_5k"/></radialGradient><radialGradient id="igzgc1W" cx="0" cy="0" r="1" gradientTransform="matrix(1.9417 -2.80617 .70622 .48866 10.227 12.088)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="hidg91biy"/><stop offset="1" class="cvqgvpbrv"/></radialGradient><radialGradient id="i9PYjPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .23468 -.91915 0 16.384 17.445)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="sqyr096qp"/><stop offset="1" class="g5p0-zbdt"/></radialGradient><radialGradient id="iQErvOc" cx="0" cy="0" r="1" gradientTransform="rotate(54.27 -1.725 14.511)scale(3.0028 7.46591)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ug-19k9el"/><stop offset="1" class="g39kyrbyk"/></radialGradient><radialGradient id="iCnb0il" cx="0" cy="0" r="1" gradientTransform="matrix(-1.77848 1.8674 -4.01797 -3.82666 19.79 7.486)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="ol4j1kbtk"/><stop offset=".905" class="ku4omo86w"/></radialGradient><radialGradient id="iFuwJpc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49955 .43561 -.73415 -4.21257 22.95 11.801)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="ylnndjfas"/><stop offset="1" class="e9-k0j__e"/></radialGradient><radialGradient id="ifXRgpr" cx="0" cy="0" r="1" gradientTransform="rotate(167.542 4.485 7.146)scale(1.37615 3.394)" gradientUnits="userSpaceOnUse"><stop offset=".386" class="al_a71bgz"/><stop offset="1" class="vhbpqvbaw"/></radialGradient><radialGradient id="iBlKhKb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.70756 0 0 -.70728 16.54 8.075)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="q_a5dub1w"/><stop offset="1" class="rt66rv9cg"/></radialGradient><radialGradient id="iyf8efd" cx="0" cy="0" r="1" gradientTransform="matrix(3.50375 -5.54762 8.14343 5.14321 10.03 12.463)" gradientUnits="userSpaceOnUse"><stop class="bpqy41_7b"/><stop offset=".288" class="a420gebgu"/></radialGradient><radialGradient id="iCOaw7b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28849 .92462 -.64714 -3.00153 21.288 9.091)" gradientUnits="userSpaceOnUse"><stop offset=".509" class="k_d05ck2j"/><stop offset="1" class="b-8t08brj"/></radialGradient><radialGradient id="i0kxAtd" cx="0" cy="0" r="1" gradientTransform="matrix(3.02827 .7705 -.33418 1.31341 19.37 9.156)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="o5xzi4bgi"/><stop offset="1" class="r8t0fyw6u"/></radialGradient><radialGradient id="iEFO54B" cx="0" cy="0" r="1" gradientTransform="rotate(143.536 9.768 8.924)scale(2.15963 3.14688)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="ttpb5jbva"/><stop offset="1" class="wxvvawbsy"/></radialGradient><radialGradient id="iJ11RKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88332 -1.40502 0 18.319 15.156)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="au361rb0r"/></radialGradient><radialGradient id="iB89jpc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2525 -.32538 .44797 -.34763 18.07 15.248)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5DdZsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88336 -1.40509 0 13.567 15.156)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="au361rb0r"/></radialGradient><radialGradient id="i0xNNIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00842 -.53793 .64661 -.01012 13.256 15.395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHbPYFo" cx="0" cy="0" r="1" gradientTransform="matrix(1.42879 0 0 1.59032 21.416 15.61)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="s7017_a0r"/><stop offset="1" class="xb-c3abcd"/></radialGradient><radialGradient id="i8iZ7Yd" cx="0" cy="0" r="1" gradientTransform="rotate(-175.776 5.516 7.749)scale(1.29257 2.20938)" gradientUnits="userSpaceOnUse"><stop offset=".534" class="ndv5zbcuf"/><stop offset="1" class="z00tjmblq"/></radialGradient><radialGradient id="iJN2UEa" cx="0" cy="0" r="1" gradientTransform="matrix(-.65365 0 0 -1.07747 10.491 15.773)" gradientUnits="userSpaceOnUse"><stop class="erdfiabun"/><stop offset="1" class="b-qr36b7t"/></radialGradient><radialGradient id="iBiZlFm" cx="0" cy="0" r="1" gradientTransform="matrix(.96094 .04287 -.03776 .84633 21.369 15.723)" gradientUnits="userSpaceOnUse"><stop class="mdi-3n_ob"/><stop offset=".809" class="qfyq-sjjj"/></radialGradient><radialGradient id="ifdLrOb" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 -1.21 15.637)scale(7.05349 6.17563)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="wtwwvnbas"/><stop offset="1" class="w7qdm2k5j"/></radialGradient><radialGradient id="icAnfpc" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.921 8.388)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="h9fb5bbiv"/><stop offset="1" class="j1090kf1c"/></radialGradient><radialGradient id="i4KnSQj" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 8.98 14.858)" gradientUnits="userSpaceOnUse"><stop class="hiycpfc4f"/><stop offset="1" class="mqq2pckgy"/></radialGradient><radialGradient id="iCt4xDb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.167 7.046)" gradientUnits="userSpaceOnUse"><stop class="ew56wjbup"/><stop offset="1" class="qd38sjb7e"/></radialGradient><radialGradient id="iQHkhdq" cx="0" cy="0" r="1" gradientTransform="rotate(123.092 2.5 5.77)scale(1.65986 2.90522)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="jbd_cz55y"/><stop offset="1" class="by6guy4wy"/></radialGradient><radialGradient id="iJ2ilJb" cx="0" cy="0" r="1" gradientTransform="rotate(158.664 4.674 10.147)scale(5.43502 6.37816)" gradientUnits="userSpaceOnUse"><stop class="vi2d-bqgl"/><stop offset="1" class="e0s8bocva"/></radialGradient><radialGradient id="im95KLb" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 .71875 -2.2725 1.03746 23.542 6.421)" gradientUnits="userSpaceOnUse"><stop class="ze5ugdbxr"/><stop offset="1" class="pr8brkb_h"/></radialGradient><radialGradient id="iXyCdOe" cx="0" cy="0" r="1" gradientTransform="rotate(-26.281 48.92 5.7)scale(5.64614 18.1367)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="aeh-ojcyt"/><stop offset="1" class="eg11r1-xe"/></radialGradient><radialGradient id="iTQnL6P" cx="0" cy="0" r="1" gradientTransform="rotate(19.44 -33.06 67.92)scale(5.63367 5.31661)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="mfg03v23s"/><stop offset="1" class="dthyi0lfx"/></radialGradient><radialGradient id="ixdltTb" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 -1.5 3.12608 5.73115 20.845 10.625)" gradientUnits="userSpaceOnUse"><stop class="r0jlw3bfn"/><stop offset="1" class="fupaa8bps"/></radialGradient><radialGradient id="inxtE1c" cx="0" cy="0" r="1" gradientTransform="matrix(3.375 1.625 -3.0178 6.26772 20.783 17.25)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="qqqjyabvn"/><stop offset="1" class="soqvob0bo"/></radialGradient><radialGradient id="ianl7tm" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 1 -2.31305 -1.3011 9.058 6.546)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="iAjEaoe" cx="0" cy="0" r="1" gradientTransform="rotate(123.118 3.043 5.766)scale(.58626 1.5796)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="qso4uy3-n"/><stop offset="1" class="b_rfybbbi"/></radialGradient><radialGradient id="in9MEld" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1 -2.31306 1.3011 23.088 6.546)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="ih2sZDn" cx="0" cy="0" r="1" gradientTransform="matrix(1.2431 1.58204 -3.03843 2.38745 24.031 5.233)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="j26seachc"/><stop offset=".74" class="rsdjdrd8e"/></radialGradient><radialGradient id="i4Wx5fe" cx="0" cy="0" r="1" gradientTransform="matrix(1.64397 -.80986 .45783 .92938 23.225 5.44)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="vj5muxz_t"/><stop offset="1" class="tdhijwbfm"/></radialGradient><radialGradient id="im4MyHb" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.23 6.14)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="cxb3glbzc"/><stop offset="1" class="t9spukb2f"/></radialGradient><radialGradient id="i6PWSBe" cx="0" cy="0" r="1" gradientTransform="matrix(.74502 .76747 -3.62255 3.5166 8.578 3.687)" gradientUnits="userSpaceOnUse"><stop class="hdbftdbag"/><stop offset="1" class="gnvn91bpk"/></radialGradient><radialGradient id="iLcvzEe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57172 2.16536 -4.16467 -4.94623 24.454 5.531)" gradientUnits="userSpaceOnUse"><stop class="rks0_83_d"/><stop offset="1" class="vua1r5-2d"/></radialGradient><radialGradient id="iwgDMde" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.105 2.124)" gradientUnits="userSpaceOnUse"><stop class="c8sl-2enp"/><stop offset="1" class="lxeh84buj"/></radialGradient><radialGradient id="i4Ga0Yc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.91736 5.03207 -2.78747 -4.38576 22.48 26.593)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="r6lo6r6nk"/><stop offset="1" class="y46jxob_z"/></radialGradient><radialGradient id="ik8Goae" cx="0" cy="0" r="1" gradientTransform="rotate(-97.239 8.019 -3.851)scale(1.45804 6.29236)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="i0KhBee" cx="0" cy="0" r="1" gradientTransform="matrix(-3.64176 1.91051 -3.15495 -6.01388 20.907 1.287)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="x6vydhb_v"/><stop offset="1" class="dqms9qb3g"/></radialGradient><radialGradient id="imDTRAc" cx="0" cy="0" r="1" gradientTransform="matrix(.1942 -1.17981 5.93354 .97672 19.44 3.51)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="iaWdnNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03264 -1.35386 5.89552 -.14215 14.056 4.057)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="izHBQOd" cx="0" cy="0" r="1" gradientTransform="rotate(136.804 9.675 4.357)scale(4.70997 8.35502)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="x6vydhb_v"/><stop offset="1" class="dqms9qb3g"/></radialGradient><radialGradient id="itUy5jd" cx="0" cy="0" r="1" gradientTransform="matrix(.10745 -1.4828 5.40082 .39136 18.493 4.227)" gradientUnits="userSpaceOnUse"><stop offset=".692" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="iV7Ojnc" cx="0" cy="0" r="1" gradientTransform="matrix(.00273 -1.05886 5.57736 .0144 13.896 4.785)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="iubLhWc" cx="0" cy="0" r="1" gradientTransform="rotate(150.94 9.17 4.153)scale(2.77209 4.18391)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="x6vydhb_v"/><stop offset="1" class="dqms9qb3g"/></radialGradient><radialGradient id="iC4Wjhd" cx="0" cy="0" r="1" gradientTransform="matrix(.09106 -1.00369 6.14439 .55743 18.344 4.713)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="iEWm7Na" cx="0" cy="0" r="1" gradientTransform="matrix(-.01775 -1.34298 3.63064 -.04798 13.469 6.04)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="i9v985c" cx="0" cy="0" r="1" gradientTransform="rotate(127.201 8.957 6.536)scale(3.51838 3.62395)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="x6vydhb_v"/><stop offset=".991" class="e0z1nhb7e"/></radialGradient><radialGradient id="iDcGSec" cx="0" cy="0" r="1" gradientTransform="matrix(.07604 -1.3001 4.12187 .24108 18.766 5.906)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="iFNcbHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07831 4.16712 -14.86837 -3.84744 20.845 2.875)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="lv-cucc-s"/><stop offset=".935" class="o2ym0bbuj"/></radialGradient><radialGradient id="iNzGqld" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9.1 -1.199)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="y8zuwqb-d"/><stop offset="1" class="de46s3h_f"/></radialGradient><radialGradient id="igFOeqc" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.559 6.825)" gradientUnits="userSpaceOnUse"><stop class="a1et2ybqq"/><stop offset="1" class="jts0ojbqo"/></radialGradient><linearGradient id="io4yHbe" x1="21.558" x2="20.421" y1="16.897" y2="16.809" gradientUnits="userSpaceOnUse"><stop class="ylfd71bno"/><stop offset="1" class="kd0rykbfj"/></linearGradient><linearGradient id="iMNyXrb" x1="17.049" x2="15.943" y1="16.468" y2="16.576" gradientUnits="userSpaceOnUse"><stop class="oilr_c32f"/><stop offset="1" class="mbjih7msd"/></linearGradient><linearGradient id="iUjSJtd" x1="16.095" x2="16.095" y1="18.047" y2="17.262" gradientUnits="userSpaceOnUse"><stop offset=".039" class="d7p1tr3sx"/><stop offset="1" class="pn---hbdu"/></linearGradient><linearGradient id="iqOzJhe" x1="14.921" x2="15.479" y1="16.929" y2="17.036" gradientUnits="userSpaceOnUse"><stop class="s3m9ggbla"/><stop offset="1" class="p0si4rb_j"/></linearGradient><linearGradient id="iyZ5OEe" x1="15.829" x2="15.829" y1="18.166" y2="17.719" gradientUnits="userSpaceOnUse"><stop offset=".138" class="i3zakx90j"/><stop offset=".491" class="e721a49jh"/></linearGradient><linearGradient id="iSgnx5b" x1="15.943" x2="15.943" y1="14.889" y2="15.508" gradientUnits="userSpaceOnUse"><stop offset=".063" class="m7-drm59n"/><stop offset="1" class="y6mqmcbpl"/></linearGradient><linearGradient id="iAjsrWd" x1="19.166" x2="18.824" y1="15.215" y2="15.425" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBhDbYc" x1="14.377" x2="14.036" y1="15.215" y2="15.425" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixHICNe" x1="12.408" x2="14.79" y1="12.813" y2="12.488" gradientUnits="userSpaceOnUse"><stop class="wy3_hg1ad"/><stop offset="1" class="kq6lih1_j"/></linearGradient><linearGradient id="i6V14ec" x1="19.478" x2="17.096" y1="12.813" y2="12.488" gradientUnits="userSpaceOnUse"><stop class="wy3_hg1ad"/><stop offset="1" class="kq6lih1_j"/></linearGradient><linearGradient id="ipqIf2c" x1="14.97" x2="15.458" y1="19.769" y2="18.887" gradientUnits="userSpaceOnUse"><stop class="fwpd_pb9t"/><stop offset=".537" class="u9tf2qgjp"/></linearGradient><linearGradient id="iwQT38c" x1="24.522" x2="10.056" y1="13.017" y2="32.866" gradientUnits="userSpaceOnUse"><stop class="c8jr--_9q"/><stop offset=".9" class="zxn8nz0ch"/></linearGradient><linearGradient id="i5BgaYd" x1="11.261" x2="7.292" y1="23.796" y2="27.921" gradientUnits="userSpaceOnUse"><stop class="d23tlbbur"/><stop offset=".582" class="eoe3ifbfq"/></linearGradient><linearGradient id="irAgMNc" x1="14.256" x2="10.73" y1="2.862" y2="4.623" gradientUnits="userSpaceOnUse"><stop offset=".632" class="ph5523b-j"/><stop offset=".827" class="shmkvjbbg"/></linearGradient><linearGradient id="icExggc" x1="19.276" x2="20.473" y1="2.606" y2="3.584" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="iTHTcze" x1="16.578" x2="21.666" y1="3.42" y2="3.964" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="i5CGYyb" x1="15.281" x2="12.229" y1="3.571" y2="4.697" gradientUnits="userSpaceOnUse"><stop offset=".805" class="ph5523b-j"/><stop offset="1" class="shmkvjbbg"/></linearGradient><linearGradient id="inmW2Eb" x1="19.719" x2="20.592" y1="3.736" y2="3.881" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="iwuLD8c" x1="15.613" x2="20.776" y1="4.552" y2="4.528" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="icQV8JN" x1="14.951" x2="12.46" y1="4.44" y2="5.551" gradientUnits="userSpaceOnUse"><stop offset=".805" class="ph5523b-j"/><stop offset="1" class="shmkvjbbg"/></linearGradient><linearGradient id="ia6d0Oc" x1="19.209" x2="19.796" y1="4.508" y2="4.672" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="iyqXKdc" x1="16.311" x2="19.955" y1="4.849" y2="4.821" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="inzJGKd" x1="14.466" x2="11.783" y1="5.402" y2="6.016" gradientUnits="userSpaceOnUse"><stop offset=".805" class="ph5523b-j"/><stop offset="1" class="shmkvjbbg"/></linearGradient><linearGradient id="i68Kjzc" x1="19.584" x2="20.211" y1="5.528" y2="5.655" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="iKgxBde" x1="16.844" x2="20.289" y1="6.156" y2="6.143" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="ied00se" x1="14.645" x2="11.594" y1="5.534" y2="6.255" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><linearGradient id="is71VFe" x1="15.116" x2="11.594" y1="4.481" y2="5.663" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><linearGradient id="i8LSxEb" x1="15.249" x2="11.729" y1="3.496" y2="4.677" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><linearGradient id="i8ICqWZ" x1="14.43" x2="11.184" y1="2.683" y2="4.707" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><filter id="i2Fq0Mb" width="11.877" height="14.137" x="10.431" y="8.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.45098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3725"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.439216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3725" result="effect2_innerShadow_4002_3725"/></filter><filter id="iLXklAe" width="4.044" height="5.157" x="13.696" y="14.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".5"/></filter><filter id="iRVfiYb" width="2.244" height="3.357" x="14.821" y="14.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".05"/></filter><filter id="i6KhxrB" width="14.015" height="9.054" x="8.935" y="5.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.701961 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3725"/></filter><filter id="imQW7ow" width="7.25" height="6.272" x="9.295" y="6.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.490196 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3725"/><feGaussianBlur result="effect2_foregroundBlur_4002_3725" stdDeviation=".15"/></filter><filter id="iqK6Atc" width="6.98" height="5.963" x="15.919" y="7.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".15"/></filter><filter id="ihgS3sz" width=".839" height=".74" x="17.528" y="14.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".05"/></filter><filter id="iUeR3Gd" width=".935" height=".959" x="18.452" y="14.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".1"/></filter><filter id="i5woTHe" width="1.038" height="1.097" x="13.615" y="14.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".1"/></filter><filter id="i3OQpjd" width=".976" height=".749" x="12.784" y="14.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".05"/></filter><filter id="iEkTtPb" width="1.402" height="2.546" x="9.397" y="14.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".125"/></filter><filter id="iOIpWzd" width="1.531" height="2.572" x="21.158" y="14.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".125"/></filter><filter id="i6MApZb" width="2.544" height="1.086" x="11.838" y="12.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3725"/></filter><filter id="itS8wCj" width="2.594" height="1.136" x="11.763" y="12.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".125"/></filter><filter id="iQjYMic" width="2.544" height="1.086" x="17.604" y="12.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3725"/></filter><filter id="ixMw3Qc" width="2.594" height="1.136" x="17.529" y="12.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".125"/></filter><filter id="iNmk77b" width="16.188" height="8.656" x="9.167" y="22.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".5"/></filter><filter id="iqJgCNe" width="4.094" height="4.656" x="7.917" y="23.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".25"/></filter><filter id="iTsCyed" width="3.508" height="1.177" x="11.47" y="5.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".125"/></filter><filter id="iNdumsb" width="4.104" height="1.115" x="11.336" y="3.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".125"/></filter><filter id="irCzdBb" width="4.104" height="1.115" x="11.47" y="3.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".125"/></filter><filter id="iwLSMCb" width="4.288" height="1.471" x="10.456" y="2.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3725" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-ok-medium-light" /></template>
<style>
.a1et2ybqq {
  stop-color: var(--svg-color--edb090, #EDB090);
}

.a420gebgu {
  stop-color: var(--svg-color--dc8e73, #DC8E73);
  stop-opacity: 0;
}

.aeh-ojcyt {
  stop-color: var(--svg-color--c7482a, #C7482A);
}

.al_a71bgz {
  stop-color: var(--svg-color--de8c6c, #DE8C6C);
}

.au361rb0r {
  stop-color: var(--svg-color--5f443e, #5F443E);
}

.b_rfybbbi {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
  stop-opacity: 0;
}

.b-8t08brj {
  stop-color: var(--svg-color--e9c091, #E9C091);
}

.b-qr36b7t {
  stop-color: var(--svg-color--c86d58, #C86D58);
}

.b57ou_b9t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.615 3.765c.43-.11 1.65-.274 2.666-.149");
}

.bfvhuvgva {
  stop-color: var(--svg-color--c78579, #C78579);
}

.bpqy41_7b {
  stop-color: var(--svg-color--dc8e73, #DC8E73);
}

.bswoa5a7i {
  stop-color: var(--svg-color--d6a184, #D6A184);
  stop-opacity: 0;
}

.bwviuxbld {
  stop-color: var(--svg-color--e3a28c, #E3A28C);
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

.c36yqwb8n {
  d: path("M18.321 14.637a.972.972 0 0 1 .936 1.227H17.38a.975.975 0 0 1 .94-1.228");
}

.c8jr--_9q {
  stop-color: var(--svg-color--ff610f, #FF610F);
}

.c8sl-2enp {
  stop-color: var(--svg-color--cca180, #CCA180);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvtdgbxl {
  stop-color: var(--svg-color--c78579, #C78579);
  stop-opacity: 0;
}

.cvqgvpbrv {
  stop-color: var(--svg-color--c56c51, #C56C51);
  stop-opacity: 0;
}

.cxb3glbzc {
  stop-color: var(--svg-color--eab594, #EAB594);
}

.cxjjb1-je {
  stop-color: var(--svg-color--d6a184, #D6A184);
}

.d23tlbbur {
  stop-color: var(--svg-color--ff6d39, #FF6D39);
}

.d7p1tr3sx {
  stop-color: var(--svg-color--ce8c82, #CE8C82);
}

.de46s3h_f {
  stop-color: var(--svg-color--d48e7a, #D48E7A);
  stop-opacity: 0;
}

.dkkvyqbbp {
  d: path("M9.51 3.359a61 61 0 0 0-1.79 1.61a.08.08 0 0 0-.027.054c-.033.574 1.968 1.625 3.038 2.013q.017.006.034.006c.941-.004 1.105-.372 1.736-.664c.727-.336 1.477-.309 1.867-.309c.391 0 .602-.218.696-.414c.063-.132.064-.316-.03-.523a.63.63 0 0 0 .442-.281a.64.64 0 0 0 .057-.625c.156-.063.336-.304.312-.649c-.037-.537-.494-.37-.713-.366l-.232-.29c.012-.55-.585-.6-.815-.574l-1.717.097a.98.98 0 0 0-.765-.132c-.432.122-1.264.338-2.094 1.047");
}

.dqms9qb3g {
  stop-color: var(--svg-color--c98b5e, #C98B5E);
}

.dthyi0lfx {
  stop-color: var(--svg-color--df5212, #DF5212);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0s8bocva {
  stop-color: var(--svg-color--d64d38, #D64D38);
  stop-opacity: 0;
}

.e0z1nhb7e {
  stop-color: var(--svg-color--cc9167, #CC9167);
}

.e13mj1was {
  d: path("M18.25 14.842c.069.093-.076.205-.24.329c-.165.123-.287.21-.356.117c-.07-.093.008-.268.172-.39c.165-.124.354-.149.424-.056");
}

.e721a49jh {
  stop-color: var(--svg-color--c9847a, #C9847A);
  stop-opacity: 0;
}

.e9-k0j__e {
  stop-color: var(--svg-color--daa982, #DAA982);
  stop-opacity: 0;
}

.eaofinhlm {
  stop-color: var(--svg-color--edaf97, #EDAF97);
}

.ebnbqcb_c {
  d: path("M22.637 3.359a61 61 0 0 1 1.79 1.61a.08.08 0 0 1 .027.054c.032.574-1.969 1.625-3.039 2.013a.1.1 0 0 1-.034.006c-.941-.004-1.105-.372-1.736-.664c-.726-.336-1.476-.309-1.867-.309c-.39 0-.602-.218-.695-.414c-.064-.132-.065-.316.029-.523a.63.63 0 0 1-.442-.281a.64.64 0 0 1-.056-.625c-.157-.063-.337-.304-.313-.649c.038-.537.592-.465.81-.46l.136-.196c-.013-.55.585-.6.814-.574l1.717.097a.98.98 0 0 1 .766-.132c.432.122 1.263.338 2.093 1.047");
}

.eg11r1-xe {
  stop-color: var(--svg-color--c7482a, #C7482A);
  stop-opacity: 0;
}

.eoe3ifbfq {
  stop-color: var(--svg-color--ff6d39, #FF6D39);
  stop-opacity: 0;
}

.erdfiabun {
  stop-color: var(--svg-color--c5684f, #C5684F);
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

.f-iegb-dq {
  stop-color: var(--svg-color--ff5930, #FF5930);
}

.ft5dv1b6b {
  fill: none;
}

.fupaa8bps {
  stop-color: var(--svg-color--da531c, #DA531C);
  stop-opacity: 0;
}

.fwpd_pb9t {
  stop-color: var(--svg-color--d2998c, #D2998C);
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

.g39kyrbyk {
  stop-color: var(--svg-color--c08356, #C08356);
  stop-opacity: 0;
}

.g5p0-zbdt {
  stop-color: var(--svg-color--eeb8a1, #EEB8A1);
  stop-opacity: 0;
}

.ghg-e1bfu {
  cx: 13.272px;
  cy: 15.052px;
  rx: 0.424px;
  ry: 0.215px;
}

.gmax2qb7j {
  fill: var(--svg-color--9b6333, #9B6333);
  fill-rule: evenodd;
  d: path("M17.922 12.899c.79-.127 1.468.194 1.69.354a.275.275 0 1 0 .323-.444c-.31-.226-1.134-.608-2.1-.453a.275.275 0 0 0 .087.543");
}

.gnvn91bpk {
  stop-color: var(--svg-color--c69a7a, #C69A7A);
  stop-opacity: 0;
}

.gsbxves2y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.113 13.03c.266-.192 1.017-.543 1.894-.403");
}

.h9fb5bbiv {
  stop-color: var(--svg-color--ffa143, #FFA143);
}

.hdbftdbag {
  stop-color: var(--svg-color--c69a7a, #C69A7A);
}

.hidg91biy {
  stop-color: var(--svg-color--c56c51, #C56C51);
}

.hiycpfc4f {
  stop-color: var(--svg-color--ff711c, #FF711C);
}

.hmenlybab {
  d: path("M14.453 15.494c0-.314-.255-.523-.324-.586l-.314.303l.193.393z");
}

.hn68qzh9n {
  stop-color: var(--svg-color--ecae94, #ECAE94);
}

.hy2odu_5k {
  stop-color: var(--svg-color--d88770, #D88770);
  stop-opacity: 0;
}

.i3zakx90j {
  stop-color: var(--svg-color--c9847a, #C9847A);
}

.i5892ackl {
  stop-color: var(--svg-color--d39869, #D39869);
  stop-opacity: 0;
}

.j1090kf1c {
  stop-color: var(--svg-color--ff6428, #FF6428);
  stop-opacity: 0;
}

.j26seachc {
  stop-color: var(--svg-color--ff8547, #FF8547);
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jtevqibrq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.07 3.46c-.68-.344-2.469-.57-3.188-.523");
}

.jts0ojbqo {
  stop-color: var(--svg-color--edb090, #EDB090);
  stop-opacity: 0;
}

.k_d05ck2j {
  stop-color: var(--svg-color--e9c091, #E9C091);
  stop-opacity: 0;
}

.kd0rykbfj {
  stop-color: var(--svg-color--e5a283, #E5A283);
  stop-opacity: 0;
}

.khte_tzpb {
  d: path("M13.565 14.637a.972.972 0 0 0-.936 1.227h1.877a1 1 0 0 0 .035-.256a.98.98 0 0 0-.976-.971");
}

.kq6lih1_j {
  stop-color: var(--svg-color--a16b41, #A16B41);
  stop-opacity: 0;
}

.ku4omo86w {
  stop-color: var(--svg-color--d0a97e, #D0A97E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lv-cucc-s {
  stop-color: var(--svg-color--ce886b, #CE886B);
  stop-opacity: 0;
}

.lxeh84buj {
  stop-color: var(--svg-color--cca180, #CCA180);
  stop-opacity: 0;
}

.m-g55uf3j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.492 4.577c-.43-.11-1.28-.203-2.296-.078");
}

.m7-drm59n {
  stop-color: var(--svg-color--dfa082, #DFA082);
}

.mbjih7msd {
  stop-color: var(--svg-color--f6c0a1, #F6C0A1);
  stop-opacity: 0;
}

.mdi-3n_ob {
  stop-color: var(--svg-color--be7460, #BE7460);
}

.meysdsb0i {
  d: path("M21.784 13.234v-.665c-.012-.831-.896-1.513-1.727-1.548h-1.525c-1.237 0-1.936-.898-2.273-1.949c-.236-.735.626-1.309 1.388-1.184c.889.145 1.886.248 3.349 1.111c2.215 1.308 1.788 3.184.788 4.235");
}

.mfg03v23s {
  stop-color: var(--svg-color--df5212, #DF5212);
}

.mjonlnn_a {
  d: path("M9.51 3.359a61 61 0 0 0-1.79 1.61a.08.08 0 0 0-.027.054c-.033.574 1.968 1.625 3.038 2.013q.017.006.034.006c.941-.004 1.105-.372 1.736-.664c.727-.336 1.477-.309 1.867-.309c.391 0 .602-.218.696-.414c.063-.132.064-.316-.03-.523a.63.63 0 0 0 .442-.281a.64.64 0 0 0 .057-.625c.156-.063.336-.304.312-.649c-.037-.537-.562-.661-.781-.656H14.9c.012-.55-.585-.6-.815-.574l-1.717.097a.98.98 0 0 0-.765-.132c-.432.122-1.264.338-2.094 1.047");
}

.mqq2pckgy {
  stop-color: var(--svg-color--ff711c, #FF711C);
  stop-opacity: 0;
}

.ndv5zbcuf {
  stop-color: var(--svg-color--cc7362, #CC7362);
}

.nt7gwkb2p {
  stop-color: var(--svg-color--d39869, #D39869);
}

.nuxnfxbgo {
  stop-color: var(--svg-color--d89d77, #D89D77);
}

.nwoksp-my {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.654 4.577c.43-.11 1.281-.203 2.297-.078");
}

.o_9_81b8h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.12 3.901c-.43-.11-2.375-.476-3.254-.265");
}

.o2ym0bbuj {
  stop-color: var(--svg-color--ce886b, #CE886B);
}

.o5xzi4bgi {
  stop-color: var(--svg-color--fffcc0, #FFFCC0);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odf4c6bdk {
  stop-color: var(--svg-color--eea57c, #EEA57C);
}

.of-acub0v {
  fill: var(--svg-color--e8aa8c, #E8AA8C);
  d: path("m15.527 15.222l-.579 2.001c-.118.412.165.824.567.824h.856c.402 0 .685-.418.567-.824l-.579-2.001c-.124-.444-.702-.444-.832 0");
}

.oilr_c32f {
  stop-color: var(--svg-color--f6c0a1, #F6C0A1);
}

.ol4j1kbtk {
  stop-color: var(--svg-color--d0a97e, #D0A97E);
}

.oxf-njb4g {
  stop-color: var(--svg-color--ecae94, #ECAE94);
  stop-opacity: 0;
}

.p-_rdwbrl {
  d: path("M22.637 3.359a61 61 0 0 1 1.79 1.61a.08.08 0 0 1 .027.054c.032.574-1.969 1.625-3.039 2.013a.1.1 0 0 1-.034.006c-.941-.004-1.105-.372-1.736-.664c-.726-.336-1.476-.309-1.867-.309c-.39 0-.602-.218-.695-.414c-.064-.132-.065-.316.029-.523a.63.63 0 0 1-.442-.281a.64.64 0 0 1-.056-.625c-.157-.063-.337-.304-.313-.649c.038-.537.563-.661.782-.656h.164c-.013-.55.585-.6.814-.574l1.717.097a.98.98 0 0 1 .766-.132c.432.122 1.263.338 2.093 1.047");
}

.p0si4rb_j {
  stop-color: var(--svg-color--ce8e6f, #CE8E6F);
  stop-opacity: 0;
}

.p4lcx2a4b {
  d: path("M16.222 9.58a3 3 0 0 1-.072-.15a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.823 1.646-3.823 3.679v.3c-.37-.283-.676-.57-.676-1.532c0-1.608 2.705-3.588 4.105-3.96a6 6 0 0 1 1.723-.177c.468.017.8.42.805.888l.016 1.391z");
}

.ph5523b-j {
  stop-color: var(--svg-color--e9b895, #E9B895);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkw85ybvw {
  stop-color: var(--svg-color--e3a28c, #E3A28C);
  stop-opacity: 0;
}

.pm_eeybbf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.845 5.835c.391-.173 1.476-.503 2.758-.41");
}

.pn---hbdu {
  stop-color: var(--svg-color--ce8c82, #CE8C82);
  stop-opacity: 0;
}

.pr8brkb_h {
  stop-color: var(--svg-color--ff7840, #FF7840);
  stop-opacity: 0;
}

.ptbyyggko {
  stop-color: var(--svg-color--d09472, #D09472);
}

.ptik26i9i {
  stop-color: var(--svg-color--c19471, #C19471);
  stop-opacity: 0;
}

.pv_1ruamy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.077 3.46c.68-.344 2.468-.57 3.187-.523");
}

.pxei7ubpz {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.446 18.606c.44.23.965.361 1.524.361c.565 0 1.084-.131 1.524-.36v-.001a.22.22 0 0 1 .263.043a.205.205 0 0 1 .023.263m-3.334-.306l3.292.278m-3.292-.278a.22.22 0 0 0-.263.045a.2.2 0 0 0-.022.26m.285-.305l-.244.278m3.578.028l-.042-.028m.042.028l-.042-.028m.042.028c-.383.58-1.05.967-1.81.967s-1.426-.387-1.81-.967m3.578-.028a2.11 2.11 0 0 1-1.768.945a2.11 2.11 0 0 1-1.768-.945m-.041.028l.04-.028m-.04.028l.04-.028");
}

.q_a5dub1w {
  stop-color: var(--svg-color--ffefba, #FFEFBA);
}

.q-26v8b7m {
  stop-color: var(--svg-color--c88162, #C88162);
}

.q-q1ykg6o {
  stop-color: var(--svg-color--f8bd97, #F8BD97);
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

.qfe9tz3ca {
  stop-color: var(--svg-color--c88162, #C88162);
  stop-opacity: 0;
}

.qfyq-sjjj {
  stop-color: var(--svg-color--be725e, #BE725E);
}

.qi0665bes {
  fill: var(--svg-color--000, #000);
  d: path("M14.122 15.608a.554.554 0 0 0-.557-.556a.554.554 0 0 0-.494.813h.985a.55.55 0 0 0 .066-.257");
}

.qk70xkspj {
  stop-color: var(--svg-color--e4ab95, #E4AB95);
}

.qp3l4dbyt {
  stop-color: var(--svg-color--c19471, #C19471);
}

.qqqjyabvn {
  stop-color: var(--svg-color--da4f1a, #DA4F1A);
}

.qrzabx_4z {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.34 14.34a1.52 1.52 0 0 0-1.475 1.153a.3.3 0 0 0 .291.371h2.43a.25.25 0 0 0 .247-.296a1.525 1.525 0 0 0-1.493-1.227");
}

.qso4uy3-n {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
}

.qy1dvhj0u {
  fill: var(--svg-color--f4d99c, #F4D99C);
  d: path("M21.229 8.768c.56.192 1.062.584 1.38 1.144a2.58 2.58 0 0 1-.116 2.75c-.19.281-.294.614-.294.952v1.294a1.9 1.9 0 0 0-.727-.292l.086-1.749a1.58 1.58 0 0 0-1.502-1.56h-1.524c-1.04 0-1.98-.612-2.408-1.57a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.638 1.646-3.638 3.678l.034 1.674c-.277.04-.566.133-.784.287v-1.306c0-.34-.104-.672-.295-.952A2.6 2.6 0 0 1 9.23 10a2.55 2.55 0 0 1 1.415-1.227c.624-.221 1.026-.607 1.378-1.173c.45-.719 1.37-1.232 2.277-1.232c.353 0 .687.045.999.173c.416.181.883.181 1.299 0c.306-.128.641-.173.994-.173c.918 0 1.72.496 2.165 1.232c.335.554.86.957 1.473 1.168");
}

.r0jlw3bfn {
  stop-color: var(--svg-color--da531c, #DA531C);
}

.r6lo6r6nk {
  stop-color: var(--svg-color--ff8748, #FF8748);
}

.r8t0fyw6u {
  stop-color: var(--svg-color--fffcc0, #FFFCC0);
  stop-opacity: 0;
}

.rjf2cql4s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.852 5.655c-.274-.101-1.102-.304-2.172-.242");
}

.rks0_83_d {
  stop-color: var(--svg-color--f5c39b, #F5C39B);
}

.rl-8iyuye {
  stop-color: var(--svg-color--be777c, #BE777C);
  stop-opacity: 0;
}

.rsdjdrd8e {
  stop-color: var(--svg-color--ff8547, #FF8547);
  stop-opacity: 0;
}

.rt66rv9cg {
  stop-color: var(--svg-color--ffefba, #FFEFBA);
  stop-opacity: 0;
}

.rxwcye7wj {
  stop-color: var(--svg-color--f0b197, #F0B197);
  stop-opacity: 0;
}

.rzbok0aqc {
  d: path("M19.186 15.48a.9.9 0 0 0-.252-.503l-.282.31l.127.248z");
}

.s3m9ggbla {
  stop-color: var(--svg-color--ce8e6f, #CE8E6F);
}

.s45c4_k9i {
  stop-color: var(--svg-color--f7cbb0, #F7CBB0);
}

.s7017_a0r {
  stop-color: var(--svg-color--cf8271, #CF8271);
}

.shmkvjbbg {
  stop-color: var(--svg-color--e9b895, #E9B895);
  stop-opacity: 0;
}

.soqvob0bo {
  stop-color: var(--svg-color--da4f1a, #DA4F1A);
  stop-opacity: 0;
}

.sp3oxjwoz {
  stop-color: var(--svg-color--be777c, #BE777C);
}

.sqyr096qp {
  stop-color: var(--svg-color--eeb8a1, #EEB8A1);
}

.svfkjdxef {
  stop-color: var(--svg-color--e4ab95, #E4AB95);
  stop-opacity: 0;
}

.t3dxl1bdl {
  stop-color: var(--svg-color--ce886f, #CE886F);
}

.t9spukb2f {
  stop-color: var(--svg-color--ddaf8a, #DDAF8A);
}

.tdhijwbfm {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
  stop-opacity: 0;
}

.thano8bvw {
  d: path("M10.69 19.01a4.26 4.26 0 0 0 4.23 3.708h2.055a4.26 4.26 0 0 0 4.23-3.708c.129-2.05.258-4.093.353-6.143a1.58 1.58 0 0 0-1.501-1.56h-1.525c-1.04 0-1.98-.612-2.408-1.57a.72.72 0 0 0-.67-.455H14.07c-2.01 0-3.638 1.646-3.638 3.678c0 2.026.126 4.02.26 6.05");
}

.ttpb5jbva {
  stop-color: var(--svg-color--bb7b56, #BB7B56);
}

.tu_5mkbaw {
  fill: var(--svg-color--000, #000);
  d: path("M17.765 15.608c0-.309.247-.556.556-.556a.554.554 0 0 1 .495.812h-.985a.5.5 0 0 1-.066-.256");
}

.u02a1vtwi {
  d: path("M21.236 17.36c.365-.011.706-.135.985-.335v1.014c0 .972-.58 1.838-1.46 2.198q.28-.594.376-1.285z");
}

.u9tf2qgjp {
  stop-color: var(--svg-color--d2998c, #D2998C);
  stop-opacity: 0;
}

.ucvon1e0f {
  d: path("m15.527 15.222l-.579 2.001c-.118.412.165.824.567.824h.856c.402 0 .685-.418.567-.824l-.579-2.001c-.124-.444-.702-.444-.832 0");
}

.ug-19k9el {
  stop-color: var(--svg-color--c08356, #C08356);
}

.uj-ttlabc {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.546 14.34c.711 0 1.312.49 1.475 1.153a.298.298 0 0 1-.291.371H17.3a.25.25 0 0 1-.247-.296a1.52 1.52 0 0 1 1.493-1.227");
}

.uohk86iby {
  d: path("M10.65 17.36a1.8 1.8 0 0 1-.984-.335v1.014c0 .972.579 1.838 1.46 2.198a4.5 4.5 0 0 1-.377-1.285z");
}

.uyz7qki7u {
  stop-color: var(--svg-color--c7785a, #C7785A);
}

.v-5iy9jix {
  fill: var(--svg-color--fee4a5, #FEE4A5);
  d: path("M21.784 13.234v-.665c-.012-.831-.896-1.513-1.727-1.548h-1.525c-1.237 0-1.936-.898-2.273-1.949c-.236-.735.626-1.309 1.388-1.184c.889.145 1.886.248 3.349 1.111c2.215 1.308 1.788 3.184.788 4.235");
}

.v-fcszbji {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.845 3.754c.46-.173 1.847-.439 3.353-.346");
}

.vawznp55w {
  stop-color: var(--svg-color--d88770, #D88770);
}

.vhbpqvbaw {
  stop-color: var(--svg-color--de8c6c, #DE8C6C);
  stop-opacity: 0;
}

.vi2d-bqgl {
  stop-color: var(--svg-color--d64d38, #D64D38);
}

.vj5muxz_t {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
}

.vua1r5-2d {
  stop-color: var(--svg-color--d5a482, #D5A482);
}

.vz10a6buo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.83 3.354c.434-.235 2.033-.622 3.539-.721");
}

.w20q0hgpg {
  stop-color: var(--svg-color--d09472, #D09472);
  stop-opacity: 0;
}

.w7qdm2k5j {
  stop-color: var(--svg-color--d64120, #D64120);
  stop-opacity: 0;
}

.wb8s5lbxg {
  fill: var(--svg-color--f5c9a2, #F5C9A2);
  d: path("M16.222 9.58a3 3 0 0 1-.072-.15a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.823 1.646-3.823 3.679v.3c-.37-.283-.676-.57-.676-1.532c0-1.608 2.705-3.588 4.105-3.96a6 6 0 0 1 1.723-.177c.468.017.8.42.805.888l.016 1.391z");
}

.wg1qd0b2y {
  stop-color: var(--svg-color--f0b197, #F0B197);
}

.wkfrpjs0r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.711 4.74c.46-.173 1.847-.439 3.354-.347");
}

.wthpf-bib {
  d: path("M23.933 27.421c-1.95-1.2-3.036-3.417-3.36-4.156c-5.174 0-9.28 1.969-10.406 6.656h14.188c0-.9-.156-1.937-.422-2.5");
}

.wtwwvnbas {
  stop-color: var(--svg-color--d64120, #D64120);
}

.wxvvawbsy {
  stop-color: var(--svg-color--d79880, #D79880);
  stop-opacity: 0;
}

.wy3_hg1ad {
  stop-color: var(--svg-color--a16b41, #A16B41);
}

.x14xtc2ed {
  d: path("M10.459 14.696a1.04 1.04 0 0 0 .09 2.046a85 85 0 0 1-.09-2.046");
}

.x6vydhb_v {
  stop-color: var(--svg-color--cc9167, #CC9167);
  stop-opacity: 0;
}

.x7ljgpqek {
  d: path("M21.302 17.46q.108-1.737.2-3.475a1.752 1.752 0 0 1-.2 3.475");
}

.x94xl2b4t {
  stop-color: var(--svg-color--ba6256, #BA6256);
}

.xb-c3abcd {
  stop-color: var(--svg-color--bc6851, #BC6851);
}

.xra9oc37j {
  stop-color: var(--svg-color--f7cbb0, #F7CBB0);
  stop-opacity: 0;
}

.y46jxob_z {
  stop-color: var(--svg-color--ff8748, #FF8748);
  stop-opacity: 0;
}

.y5df-gbld {
  fill: var(--svg-color--cb8b79, #CB8B79);
  d: path("m15.414 15.435l-.691 2.002c-.119.411.165.823.566.823h.857c.401 0 .684-.418.566-.823l-.578-2.002c-.124-.443-.59-.443-.72 0");
}

.y6mqmcbpl {
  stop-color: var(--svg-color--dfa082, #DFA082);
  stop-opacity: 0;
}

.y8zuwqb-d {
  stop-color: var(--svg-color--d48e7a, #D48E7A);
}

.yb4penyyu {
  d: path("M10.45 13.988a1.75 1.75 0 0 0-1.515 1.723c0 .935.733 1.7 1.656 1.75a84 84 0 0 1-.14-3.473");
}

.yhy2k9bbo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.667 26.952c.48-.448 1.67-1.706 2.594-3.156");
}

.ylfd71bno {
  stop-color: var(--svg-color--c98065, #C98065);
}

.ylnndjfas {
  stop-color: var(--svg-color--daa982, #DAA982);
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

.z_8l6fgjj {
  fill: var(--svg-color--9b6333, #9B6333);
  fill-rule: evenodd;
  d: path("M13.964 12.899c-.79-.127-1.468.194-1.69.354a.275.275 0 1 1-.323-.444c.31-.226 1.134-.608 2.1-.453a.275.275 0 1 1-.087.543");
}

.z00tjmblq {
  stop-color: var(--svg-color--cf7251, #CF7251);
}

.z6pyd1pmi {
  stop-color: var(--svg-color--cc7559, #CC7559);
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

.zxn8nz0ch {
  stop-color: var(--svg-color--fb5b1a, #FB5B1A);
}

</style>
