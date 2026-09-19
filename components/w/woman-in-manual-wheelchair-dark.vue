<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iBM96Ic)"><path class="fk42cj7iu"/><path fill="url(#iktp9gh)" class="f4t4j4okd"/><path fill="url(#ibrmNIe)" class="f4t4j4okd"/><path fill="url(#iE64bFt)" class="f4t4j4okd"/></g><g filter="url(#iwscEve)"><path fill="url(#ieoMeEc)" class="j6qk5yyrd"/><path fill="url(#iKgX5Hd)" class="j6qk5yyrd"/><path fill="url(#i9go6pb)" class="j6qk5yyrd"/><path fill="url(#iUfuXnb)" class="j6qk5yyrd"/><path fill="url(#iPi2lMe)" class="j6qk5yyrd"/></g><g filter="url(#iYJawye)"><path class="y0h7csylp"/></g><circle fill="url(#iRMdfoe)" class="xv1iy6bqi"/><circle fill="url(#isFS0Qd)" class="xv1iy6bqi"/><g filter="url(#iwzk0VV)"><circle fill="url(#i1i9ahd)" class="qahn3-b4x"/><circle fill="url(#iQGsxle)" class="qahn3-b4x"/></g><rect class="fxn310b7z"/><rect fill="url(#igAR1iO)" class="nvvve-trp"/><rect fill="url(#iLGSjOc)" class="nvvve-trp"/><rect fill="url(#i2YxUIe)" class="nvvve-trp"/><rect fill="url(#i333Yqe)" class="nvvve-trp"/><rect fill="url(#iYQVfcb)" class="nvvve-trp"/><rect fill="url(#ig67rbU)" class="nvvve-trp"/><rect fill="url(#iBUaE8b)" transform="rotate(-65.334 8.206 26.25)" class="jcryqpbvg"/><rect fill="url(#iJ93HVb)" transform="rotate(-65.334 8.206 26.25)" class="jcryqpbvg"/><path fill="url(#iRRX5hF)" class="bj_du5bwx"/><path fill="url(#ifikxFc)" class="bj_du5bwx"/><path fill="url(#ipdciqd)" class="bj_du5bwx"/><path fill="url(#iCuAUgb)" class="bj_du5bwx"/><path fill="url(#imFYzvc)" class="bj_du5bwx"/><path fill="url(#iVRbOae)" class="bj_du5bwx"/><g filter="url(#ixjBgsb)"><path fill="url(#iCLS41b)" clip-rule="evenodd" class="v2sjqebcr"/><path fill="url(#i6xqRfb)" clip-rule="evenodd" class="v2sjqebcr"/></g><path fill="url(#iJiXtdb)" class="mjgjl--ea"/><path fill="url(#ixFg7Sm)" class="mjgjl--ea"/><path fill="url(#ikfOXFc)" transform="rotate(16.465 20.736 11.756)" class="oxy7wbbbl"/><g filter="url(#iTcCVWd)"><rect transform="rotate(24.427 5.644 23.543)" class="q5ajh9bwz"/></g><rect fill="url(#iQq3NUe)" transform="rotate(24.427 5.644 23.543)" class="htuevgb8a"/><g filter="url(#iS4Pb1d)"><path fill="url(#ixcfjIf)" clip-rule="evenodd" class="vv-cpsbto"/><path fill="url(#i0KWNOg)" clip-rule="evenodd" class="vv-cpsbto"/><path fill="url(#iiFOP7i)" clip-rule="evenodd" class="vv-cpsbto"/></g><path fill="url(#icP5tCd)" clip-rule="evenodd" class="yv3zhzb_e"/><path fill="url(#iN9uBTc)" clip-rule="evenodd" class="yv3zhzb_e"/><path fill="url(#iDb8nFo)" clip-rule="evenodd" class="yv3zhzb_e"/><rect fill="url(#iBg29Ge)" class="e3_ffgbnu"/><rect fill="url(#ivtyylc)" class="e3_ffgbnu"/><g filter="url(#iBGj8fe)"><circle fill="url(#iSrvvee)" class="hxyodpbeo"/></g><g filter="url(#iGms3Ed)"><path clip-rule="evenodd" class="kn-keubds"/></g><path class="drzoj44th"/><path fill="url(#iUrXEce)" class="xh1d24icr"/><path fill="url(#iOzoiFY)" class="xh1d24icr"/><path fill="url(#i5kyiad)" class="xh1d24icr"/><path fill="url(#iBASmzc)" class="xh1d24icr"/><path fill="url(#iA9g6Ed)" class="xh1d24icr"/><g filter="url(#iZtMhCc)"><circle fill="url(#iiCXVmc)" class="pvvrqubct"/></g><g filter="url(#iUJSeGB)"><circle stroke="url(#idlHJsc)" class="ti0v3dbtx"/></g><g filter="url(#iM5hUcb)"><circle stroke="url(#iekrjwb)" class="iwaezgbjv"/></g><g filter="url(#iVVJipc)"><circle stroke="url(#iDCKlmb)" class="pneydfmsb"/></g><circle fill="url(#izBNoAJ)" class="tnnezftpu"/><path class="r7jrsd33e"/><g filter="url(#itINnBd)"><path class="zvdxxxvck"/></g><path class="huu9akuzg"/><path fill="url(#i1xuPNd)" class="rufkj9blr"/><path fill="url(#i5YXLxc)" class="rufkj9blr"/><path fill="url(#ik2dL6c)" class="rufkj9blr"/><path fill="url(#iTN71Oe)" class="rufkj9blr"/><g filter="url(#ihPVZ2i)"><path class="ch4mt8bkt"/></g><g filter="url(#iSVkJeb)"><path stroke="url(#ity9Fld)" class="jksniaciw"/></g><g filter="url(#iENe9ac)"><path class="xmgfgzxde"/></g><path fill="url(#izkT4fe)" class="tc0wqzile"/><g filter="url(#iWId2Nd)"><path fill="url(#i7eluLb)" class="caalgybif"/><path fill="url(#iDGHFVb)" class="caalgybif"/><path fill="url(#idHtRnr)" class="caalgybif"/><path fill="url(#iTc45Sc)" class="caalgybif"/></g><g filter="url(#i2TgCyn)"><path class="qd95gbbzt"/></g><g filter="url(#iwfN1ub)"><path class="y_tk3gbcd"/><path fill="url(#iYEawfd)" class="w1eer1bsh"/></g><path fill="url(#iaNY7mc)" class="c0ymcac9l"/><path fill="url(#iyCdTeF)" class="c0ymcac9l"/><path clip-rule="evenodd" class="mvz3giwen"/><g filter="url(#iWiIP2c)"><path clip-rule="evenodd" class="ko2yut79d"/></g><path class="ot_4vnb5m"/><path class="nr88ykboe"/><path fill="url(#iZZslRE)" class="xg-uv87bb"/><path fill="url(#iFKGlFb)" class="wcmsiyb5p"/><ellipse fill="url(#ikFAKCd)" transform="rotate(12.32 13.174 5.882)" class="wimyepb3r"/><defs><radialGradient id="iE64bFt" cx="0" cy="0" r="1" gradientTransform="matrix(.7395 -.04828 .083 1.2714 5.124 23.012)" gradientUnits="userSpaceOnUse"><stop class="bfwbq1bpl"/><stop offset="1" class="ktc-s82to"/></radialGradient><radialGradient id="iKgX5Hd" cx="0" cy="0" r="1" gradientTransform="rotate(109.319 -1.831 14.203)scale(5.76196 2.25923)" gradientUnits="userSpaceOnUse"><stop class="y3ij90b8v"/><stop offset="1" class="qb3gn8bfr"/></radialGradient><radialGradient id="i9go6pb" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 0 0 12.1563 10.998 17.13)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="yutdbcb6i"/><stop offset="1" class="sstiaym3o"/></radialGradient><radialGradient id="iUfuXnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.46875 5.125 0 16.06 18.098)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="yu7wmpb_a"/><stop offset="1" class="zzc1m6bsl"/></radialGradient><radialGradient id="isFS0Qd" cx="0" cy="0" r="1" gradientTransform="matrix(1.48438 0 0 3.64062 9.31 28.489)" gradientUnits="userSpaceOnUse"><stop class="answrebhr"/><stop offset="1" class="fzo002mry"/></radialGradient><radialGradient id="i1i9ahd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.80266 4.80004 0 11.728 29.74)" gradientUnits="userSpaceOnUse"><stop class="ja_znnx3a"/><stop offset="1" class="ildpa548e"/></radialGradient><radialGradient id="iQGsxle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71875 1.03125 0 11.529 28.192)" gradientUnits="userSpaceOnUse"><stop class="z-rtjcc0y"/><stop offset="1" class="vxrkdvuju"/></radialGradient><radialGradient id="iLGSjOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.11265 -.46567 0 12.349 24.278)" gradientUnits="userSpaceOnUse"><stop class="a9m8t591o"/><stop offset="1" class="zige1b1kr"/></radialGradient><radialGradient id="i2YxUIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9265 -.24601 0 11.107 23.464)" gradientUnits="userSpaceOnUse"><stop class="a9m8t591o"/><stop offset="1" class="zige1b1kr"/></radialGradient><radialGradient id="i333Yqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.69196 .27569 0 11.107 28.64)" gradientUnits="userSpaceOnUse"><stop class="q6suc5ubz"/><stop offset="1" class="erfrsrblk"/></radialGradient><radialGradient id="iYQVfcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.94902 .80452 0 11.728 29.13)" gradientUnits="userSpaceOnUse"><stop class="ku1djbbcg"/><stop offset="1" class="e3f4ywbbl"/></radialGradient><radialGradient id="ig67rbU" cx="0" cy="0" r="1" gradientTransform="rotate(38.089 -29.028 29.368)scale(1.46908 .76568)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n3h2abc_m"/><stop offset="1" class="rgr8nhbdi"/></radialGradient><radialGradient id="iBUaE8b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.01534 -.13834 .02815 -1.0205 13.906 27.03)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="rs99u8bqf"/><stop offset="1" class="lvn5-ac9d"/></radialGradient><radialGradient id="imFYzvc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07812 -.4219 .60152 -2.96294 17.591 19.067)" gradientUnits="userSpaceOnUse"><stop class="tis1nnbrp"/><stop offset="1" class="t9-j-pbql"/></radialGradient><radialGradient id="iVRbOae" cx="0" cy="0" r="1" gradientTransform="matrix(-.82813 0 0 -2.43007 12.81 18.286)" gradientUnits="userSpaceOnUse"><stop class="r04agib6p"/><stop offset="1" class="mz7wlj55e"/></radialGradient><radialGradient id="iJiXtdb" cx="0" cy="0" r="1" gradientTransform="matrix(1.28824 -1.596 1.52738 1.23287 15.494 9.673)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="xjmwsybmx"/><stop offset="1" class="vbd7v4bfq"/></radialGradient><radialGradient id="ikfOXFc" cx="0" cy="0" r="1" gradientTransform="matrix(.06825 -4.12415 .84696 .01402 21.263 15.704)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="w-8ci9bkh"/><stop offset="1" class="dr65abcro"/></radialGradient><radialGradient id="iQq3NUe" cx="0" cy="0" r="1" gradientTransform="matrix(.59496 -.39035 .70458 1.0739 5.74 24.71)" gradientUnits="userSpaceOnUse"><stop class="vp5ble8bb"/><stop offset="1" class="g4u-v_bhx"/></radialGradient><radialGradient id="iN9uBTc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.628 22.316)scale(5.3418)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="lfwvarbqo"/><stop offset="1" class="z4for55kd"/></radialGradient><radialGradient id="iDb8nFo" cx="0" cy="0" r="1" gradientTransform="rotate(-137.525 18.028 9.417)scale(12.5412 9.73796)" gradientUnits="userSpaceOnUse"><stop offset=".921" class="jz-3fab0l"/><stop offset="1" class="fiiks7b8f"/></radialGradient><radialGradient id="ivtyylc" cx="0" cy="0" r="1" gradientTransform="matrix(-.85938 .39452 -.43395 -.94526 25.029 11.441)" gradientUnits="userSpaceOnUse"><stop class="roww1df0l"/><stop offset="1" class="ennuonbfb"/></radialGradient><radialGradient id="iSrvvee" cx="0" cy="0" r="1" gradientTransform="matrix(4.09375 -5.53125 9.86398 7.30045 18.841 26.723)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="z3yur8boj"/><stop offset="1" class="c9gtc1bjl"/></radialGradient><radialGradient id="iUrXEce" cx="0" cy="0" r="1" gradientTransform="matrix(1.81094 4.76329 -1.81631 .69054 18.03 12.649)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="zp_517jgm"/><stop offset="1" class="p9ept44wt"/></radialGradient><radialGradient id="i5kyiad" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60922 1.60922 -4.29661 -4.29661 19.287 8.755)" gradientUnits="userSpaceOnUse"><stop class="kn42mcchn"/><stop offset="1" class="kzr6sffft"/></radialGradient><radialGradient id="iBASmzc" cx="0" cy="0" r="1" gradientTransform="matrix(.69855 5.125 -2.13812 .29143 14.691 11.234)" gradientUnits="userSpaceOnUse"><stop class="i24r0nbmv"/><stop offset="1" class="erlv03bqf"/></radialGradient><radialGradient id="iA9g6Ed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99997 -6.00933 5.11024 -1.70074 17.796 14.234)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="hagwkib2x"/><stop offset="1" class="ip5996ykk"/></radialGradient><radialGradient id="izBNoAJ" cx="0" cy="0" r="1" gradientTransform="rotate(-73.593 20.83 -2.684)scale(.73297)" gradientUnits="userSpaceOnUse"><stop class="qk81-4fqz"/><stop offset="1" class="hhbcm7nxd"/></radialGradient><radialGradient id="ik2dL6c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 -2.96876 2.35369 -1.598 18.435 11.848)" gradientUnits="userSpaceOnUse"><stop offset=".88" class="aew93sw7h"/><stop offset="1" class="a10dt2bqr"/></radialGradient><radialGradient id="iTN71Oe" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 2.03125 -.62745 .46335 18.578 10.406)" gradientUnits="userSpaceOnUse"><stop class="tnr6qjbmk"/><stop offset="1" class="c6hrvfqjf"/></radialGradient><radialGradient id="izkT4fe" cx="0" cy="0" r="1" gradientTransform="matrix(.47183 .1364 -.19252 .666 12.3 6.963)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="iDGHFVb" cx="0" cy="0" r="1" gradientTransform="rotate(170.89 7.48 3.43)scale(.766 .93391)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="idHtRnr" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00084 -4.5945 1.2455 -.27131 13.072 7.244)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="iTc45Sc" cx="0" cy="0" r="1" gradientTransform="rotate(77.71 3.023 11.469)scale(.35408 .55221)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="iYEawfd" cx="0" cy="0" r="1" gradientTransform="matrix(1.29217 -.6858 1.46616 2.76252 12.216 4.274)" gradientUnits="userSpaceOnUse"><stop class="tzf255bgc"/><stop offset="1" class="ctuud_14h"/></radialGradient><radialGradient id="iaNY7mc" cx="0" cy="0" r="1" gradientTransform="matrix(.6028 -.327 .1596 .29422 15.1 5.592)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="iZZslRE" cx="0" cy="0" r="1" gradientTransform="matrix(.24218 -.05276 .1025 .47052 13.33 6.155)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iFKGlFb" cx="0" cy="0" r="1" gradientTransform="matrix(.22115 -.04817 .10425 .47858 13.184 6.206)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iktp9gh" x1="9.114" x2="8.197" y1="24.444" y2="23.962" gradientUnits="userSpaceOnUse"><stop offset=".209" class="id-v9-mic"/><stop offset="1" class="s_nhb9bnh"/></linearGradient><linearGradient id="ibrmNIe" x1="7.875" x2="8.165" y1="24.782" y2="24.026" gradientUnits="userSpaceOnUse"><stop offset=".122" class="oqr4-mbfk"/><stop offset="1" class="s_nhb9bnh"/></linearGradient><linearGradient id="ieoMeEc" x1="9.904" x2="16.06" y1="20.692" y2="17.317" gradientUnits="userSpaceOnUse"><stop class="sa2yvrtdg"/><stop offset="1" class="bxntujdns"/></linearGradient><linearGradient id="iPi2lMe" x1="9.06" x2="9.966" y1="19.942" y2="20.005" gradientUnits="userSpaceOnUse"><stop class="d_4otnung"/><stop offset="1" class="gldbv0pab"/></linearGradient><linearGradient id="iRMdfoe" x1="11.919" x2="11.919" y1="30.333" y2="26.766" gradientUnits="userSpaceOnUse"><stop class="uqxwa8ern"/><stop offset=".596" class="qx2qyypot"/></linearGradient><linearGradient id="igAR1iO" x1="12.349" x2="11.612" y1="26.866" y2="26.866" gradientUnits="userSpaceOnUse"><stop class="g6i5vgbtc"/><stop offset="1" class="zuaxx5qad"/></linearGradient><linearGradient id="iJ93HVb" x1="11.901" x2="11.813" y1="27.831" y2="27.078" gradientUnits="userSpaceOnUse"><stop class="pyh7r6bag"/><stop offset="1" class="ym5c6ha3r"/></linearGradient><linearGradient id="iRRX5hF" x1="12.351" x2="17.259" y1="18.59" y2="18.59" gradientUnits="userSpaceOnUse"><stop class="n0w_cmcuq"/><stop offset="1" class="cjqgdpbwq"/></linearGradient><linearGradient id="ifikxFc" x1="15.747" x2="15.747" y1="17.52" y2="17.864" gradientUnits="userSpaceOnUse"><stop class="xb91u7b-b"/><stop offset="1" class="us60yytqw"/></linearGradient><linearGradient id="ipdciqd" x1="14.826" x2="14.826" y1="19.364" y2="18.317" gradientUnits="userSpaceOnUse"><stop class="x8v8a_bhe"/><stop offset="1" class="g0aomjwhv"/></linearGradient><linearGradient id="iCuAUgb" x1="11.107" x2="11.341" y1="19.13" y2="19.13" gradientUnits="userSpaceOnUse"><stop class="xudiynxns"/><stop offset="1" class="h_vbtipyr"/></linearGradient><linearGradient id="iCLS41b" x1="15.021" x2="15.021" y1="19.083" y2="26.614" gradientUnits="userSpaceOnUse"><stop class="yp_2y0bkd"/><stop offset="1" class="jli-mvbgu"/></linearGradient><linearGradient id="i6xqRfb" x1="11.107" x2="11.529" y1="21.378" y2="21.378" gradientUnits="userSpaceOnUse"><stop class="ig81yhx8p"/><stop offset="1" class="sqtinbbgr"/></linearGradient><linearGradient id="ixFg7Sm" x1="15.346" x2="15.689" y1="9.189" y2="9.036" gradientUnits="userSpaceOnUse"><stop class="ln8qc12st"/><stop offset="1" class="o-5paobui"/></linearGradient><linearGradient id="ixcfjIf" x1="13.357" x2="19.091" y1="19.348" y2="16.098" gradientUnits="userSpaceOnUse"><stop class="x3lzt0c-k"/><stop offset="1" class="cwu_shb3d"/></linearGradient><linearGradient id="i0KWNOg" x1="21.17" x2="20.147" y1="17.475" y2="17.475" gradientUnits="userSpaceOnUse"><stop class="ys8863_0j"/><stop offset="1" class="h0a-qhb0e"/></linearGradient><linearGradient id="iiFOP7i" x1="16.738" x2="16.738" y1="16.015" y2="16.348" gradientUnits="userSpaceOnUse"><stop class="io62jp_6h"/><stop offset="1" class="rg3z6xbem"/></linearGradient><linearGradient id="icP5tCd" x1="24.529" x2="16.435" y1="19.567" y2="28.63" gradientUnits="userSpaceOnUse"><stop class="v06h3pbnx"/><stop offset="1" class="lucd7-9cq"/></linearGradient><linearGradient id="iBg29Ge" x1="21.013" x2="24.896" y1="11.973" y2="11.973" gradientUnits="userSpaceOnUse"><stop class="o2t29rbsm"/><stop offset="1" class="laa0aab1b"/></linearGradient><linearGradient id="iOzoiFY" x1="15.777" x2="15.777" y1="15.528" y2="11.49" gradientUnits="userSpaceOnUse"><stop class="dntytqbyu"/><stop offset="1" class="toti2-rqa"/></linearGradient><linearGradient id="iiCXVmc" x1="21.497" x2="20.013" y1="23.083" y2="25.081" gradientUnits="userSpaceOnUse"><stop class="zax-lz03d"/><stop offset="1" class="zg7ndleiu"/></linearGradient><linearGradient id="idlHJsc" x1="21.662" x2="20.279" y1="22.919" y2="24.645" gradientUnits="userSpaceOnUse"><stop offset=".139" class="szqa4cczu"/><stop offset=".488" class="i2tkr35ot"/></linearGradient><linearGradient id="iekrjwb" x1="24.294" x2="18.169" y1="20.38" y2="28.02" gradientUnits="userSpaceOnUse"><stop offset=".066" class="u245iqdps"/><stop offset=".257" class="rijqbwbix"/><stop offset=".803" class="rijqbwbix"/><stop offset=".945" class="br5egpbia"/></linearGradient><linearGradient id="iDCKlmb" x1="24.498" x2="17.123" y1="19.305" y2="28.619" gradientUnits="userSpaceOnUse"><stop class="bgt2mc6fp"/><stop offset=".294" class="j5rtt4bpo"/><stop offset=".801" class="x4ldqjsok"/></linearGradient><linearGradient id="i1xuPNd" x1="16.591" x2="17.138" y1="11.415" y2="11.02" gradientUnits="userSpaceOnUse"><stop class="yfcml8bws"/><stop offset="1" class="p_9_i7g9o"/></linearGradient><linearGradient id="i5YXLxc" x1="18.882" x2="17.611" y1="10.283" y2="11.297" gradientUnits="userSpaceOnUse"><stop class="i_sqp4rly"/><stop offset="1" class="psznkgfrn"/></linearGradient><linearGradient id="ity9Fld" x1="9.216" x2="4.169" y1="25.708" y2="23.473" gradientUnits="userSpaceOnUse"><stop class="tlllib2dn"/><stop offset="1" class="xrnpsubav"/></linearGradient><linearGradient id="i7eluLb" x1="15.274" x2="12.773" y1="6.351" y2="7.056" gradientUnits="userSpaceOnUse"><stop class="zpg97tbto"/><stop offset="1" class="l-3q2ti-u"/></linearGradient><linearGradient id="iyCdTeF" x1="15.082" x2="15.185" y1="5.657" y2="5.649" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="ikFAKCd" x1="13.11" x2="13.278" y1="5.848" y2="5.903" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="iBM96Ic" width="4.713" height="2.925" x="5.124" y="22.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/></filter><filter id="iwscEve" width="10.328" height="8.578" x="8.638" y="15.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.501961 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/></filter><filter id="iYJawye" width="3.953" height="7.5" x="8.747" y="17.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_463" stdDeviation=".25"/></filter><filter id="iwzk0VV" width="3.602" height="3.602" x="9.927" y="26.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_463" stdDeviation=".125"/></filter><filter id="ixjBgsb" width="7.828" height="7.731" x="11.107" y="19.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.0745098 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/></filter><filter id="iTcCVWd" width="4.543" height="3.256" x="5.279" y="23.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.360784 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/></filter><filter id="iS4Pb1d" width="8.506" height="4.313" x="12.56" y="16.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.270588 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/></filter><filter id="iBGj8fe" width="8.267" height="8.267" x="16.48" y="19.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.611765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/></filter><filter id="iGms3Ed" width="9.68" height="9.83" x="15.849" y="18.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.4 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/></filter><filter id="iZtMhCc" width="3.273" height="3.273" x="18.952" y="22.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.678431 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_463"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_463" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.207843 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_463"/></filter><filter id="iUJSeGB" width="2.245" height="2.245" x="19.566" y="22.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_463" stdDeviation=".05"/></filter><filter id="iM5hUcb" width="9.402" height="9.402" x="16.122" y="19.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_463" stdDeviation=".075"/></filter><filter id="iVVJipc" width="12.217" height="12.217" x="14.674" y="17.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_463" stdDeviation=".15"/></filter><filter id="itINnBd" width="3.238" height="8.483" x="17.358" y="10.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.164706 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/></filter><filter id="ihPVZ2i" width="4.025" height="1.2" x="20.891" y="11.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_463" stdDeviation=".225"/></filter><filter id="iSVkJeb" width="4.231" height="2.622" x="5.585" y="23.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_463" stdDeviation=".2"/></filter><filter id="iENe9ac" width="2.78" height="8.181" x="17.891" y="11.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_463" stdDeviation=".25"/></filter><filter id="iWId2Nd" width="4.337" height="5.248" x="12.242" y="3.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.239216 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/></filter><filter id="i2TgCyn" width="6.997" height="6.474" x="11.567" y="2.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_463" result="effect2_innerShadow_4002_463"/></filter><filter id="iwfN1ub" width="6.997" height="6.474" x="11.567" y="2.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.266667 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0392157 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_463" result="effect2_innerShadow_4002_463"/></filter><filter id="iWiIP2c" width=".947" height=".435" x="12.866" y="4.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_463"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-manual-wheelchair-dark" /></template>
<style>
.a10dt2bqr {
  stop-color: var(--svg-color--8c6396, #8C6396);
}

.a9m8t591o {
  stop-color: var(--svg-color--5f3b5c, #5F3B5C);
}

.aew93sw7h {
  stop-color: var(--svg-color--8c6396, #8C6396);
  stop-opacity: 0;
}

.answrebhr {
  stop-color: var(--svg-color--79747b, #79747B);
}

.bfwbq1bpl {
  stop-color: var(--svg-color--615f82, #615F82);
}

.bgt2mc6fp {
  stop-color: var(--svg-color--4e4558, #4E4558);
}

.bj_du5bwx {
  d: path("M11.107 17.92a.4.4 0 0 1 .4-.4h8.881v2.508h-9.281z");
}

.br5egpbia {
  stop-color: var(--svg-color--96909f, #96909F);
}

.bxntujdns {
  stop-color: var(--svg-color--8c8181, #8C8181);
}

.c0ymcac9l {
  d: path("M15.216 6.382c-.044.01-.085-.025-.088-.07l-.087-1.13c-.004-.056.038-.105.093-.1a.659.659 0 0 1 .082 1.3");
}

.c6hrvfqjf {
  stop-color: var(--svg-color--997fd4, #997FD4);
  stop-opacity: 0;
}

.c9gtc1bjl {
  stop-color: var(--svg-color--c2b1db, #C2B1DB);
}

.caalgybif {
  d: path("M12.486 5.622c-.12-.717.035-1.109.121-1.233l3.306-.72l.666 2.79c-.358 2.047-2.683 2.638-3.181 2.034c-.498-.603-.772-2.04-.912-2.87");
}

.ch4mt8bkt {
  stroke: var(--svg-color--4c3e59, #4C3E59);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.341 11.756h3.125");
}

.cjqgdpbwq {
  stop-color: var(--svg-color--4d3659, #4D3659);
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.ctuud_14h {
  stop-color: var(--svg-color--534b49, #534B49);
  stop-opacity: 0;
}

.cwu_shb3d {
  stop-color: var(--svg-color--bf223d, #BF223D);
}

.d_4otnung {
  stop-color: var(--svg-color--948f93, #948F93);
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.dntytqbyu {
  stop-color: var(--svg-color--514576, #514576);
}

.dr65abcro {
  stop-color: var(--svg-color--b61f30, #B61F30);
}

.drzoj44th {
  fill: var(--svg-color--755ba9, #755BA9);
  d: path("M15.383 15.376c-.312-1.038-.937-3.994-.59-5.739c.438-1.445 1.743-1.46 2.376-1.39c.773.086 1.601.476 2.039 1.836c.453 1.25.58 4.08.633 5.445h-.875v-.152z");
}

.e3_ffgbnu {
  width: 4.227px;
  height: 1.211px;
  x: 20.669px;
  y: 11.231px;
  rx: 0.605px;
}

.e3f4ywbbl {
  stop-color: var(--svg-color--64487f, #64487F);
  stop-opacity: 0;
}

.ennuonbfb {
  stop-color: var(--svg-color--675a75, #675A75);
  stop-opacity: 0;
}

.erfrsrblk {
  stop-color: var(--svg-color--7a727f, #7A727F);
  stop-opacity: 0;
}

.erlv03bqf {
  stop-color: var(--svg-color--876eb4, #876EB4);
  stop-opacity: 0;
}

.f4t4j4okd {
  d: path("m6.548 22.426l2.093-.058l.997.824l-.797 1.8l-3.498-1.576c-.174-.078-.278-.274-.182-.44c.242-.42.748-.55 1.387-.55");
}

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
  stop-opacity: 0;
}

.fiiks7b8f {
  stop-color: var(--svg-color--301d2f, #301D2F);
}

.fk42cj7iu {
  fill: var(--svg-color--4d4a7f, #4D4A7F);
  d: path("m6.548 22.426l2.093-.058l.997.824l-.797 1.8l-3.498-1.576c-.174-.078-.278-.274-.182-.44c.242-.42.748-.55 1.387-.55");
}

.ft5dv1b6b {
  fill: none;
}

.fxn310b7z {
  width: 1.242px;
  height: 6.695px;
  x: 11.107px;
  y: 22.434px;
  fill: var(--svg-color--776a86, #776A86);
  rx: 0.621px;
}

.fzo002mry {
  stop-color: var(--svg-color--79747b, #79747B);
  stop-opacity: 0;
}

.g0aomjwhv {
  stop-color: var(--svg-color--49344d, #49344D);
  stop-opacity: 0;
}

.g4u-v_bhx {
  stop-color: var(--svg-color--89828d, #89828D);
  stop-opacity: 0;
}

.g6i5vgbtc {
  stop-color: var(--svg-color--7f758d, #7F758D);
}

.gldbv0pab {
  stop-color: var(--svg-color--948f93, #948F93);
  stop-opacity: 0;
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h_vbtipyr {
  stop-color: var(--svg-color--5f5168, #5F5168);
  stop-opacity: 0;
}

.h0a-qhb0e {
  stop-color: var(--svg-color--e35373, #E35373);
  stop-opacity: 0;
}

.hagwkib2x {
  stop-color: var(--svg-color--6a509b, #6A509B);
  stop-opacity: 0;
}

.hhbcm7nxd {
  stop-color: var(--svg-color--3a2422, #3A2422);
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
}

.htuevgb8a {
  width: 4.847px;
  height: 1.452px;
  x: 5.644px;
  y: 23.543px;
  rx: 0.726px;
}

.huu9akuzg {
  fill: var(--svg-color--7f5dc0, #7F5DC0);
  d: path("M16.189 10.454a1.11 1.11 0 1 1 1.813-1.283l1.483 2.107c-.871.48-1.793 1.29-1.793 1.29z");
}

.hxyodpbeo {
  cx: 20.689px;
  cy: 23.944px;
  r: 4.059px;
}

.i_sqp4rly {
  stop-color: var(--svg-color--9477bc, #9477BC);
}

.i24r0nbmv {
  stop-color: var(--svg-color--876eb4, #876EB4);
}

.i2tkr35ot {
  stop-color: var(--svg-color--524a5b, #524A5B);
  stop-opacity: 0;
}

.id-v9-mic {
  stop-color: var(--svg-color--342252, #342252);
}

.ig81yhx8p {
  stop-color: var(--svg-color--cd3945, #CD3945);
}

.ildpa548e {
  stop-color: var(--svg-color--3b3145, #3B3145);
}

.io62jp_6h {
  stop-color: var(--svg-color--c72b4c, #C72B4C);
}

.ip5996ykk {
  stop-color: var(--svg-color--432e67, #432E67);
}

.iwaezgbjv {
  cx: 20.823px;
  cy: 23.81px;
  r: 4.476px;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.j5rtt4bpo {
  stop-color: var(--svg-color--4e4558, #4E4558);
  stop-opacity: 0;
}

.j6qk5yyrd {
  d: path("M11.911 15.372h7.055v3.156h-6.844L9.716 23.7l-1.078-1.328c.156-.797.593-3.055.96-4.836c.376-1.82 1.594-2.164 2.313-2.164");
}

.ja_znnx3a {
  stop-color: var(--svg-color--423650, #423650);
}

.jcryqpbvg {
  width: 7.832px;
  height: 1.372px;
  x: 8.206px;
  y: 26.25px;
  rx: 0.686px;
}

.jksniaciw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m6.185 24.286l3.031 1.422");
}

.jli-mvbgu {
  stop-color: var(--svg-color--ca283c, #CA283C);
}

.jz-3fab0l {
  stop-color: var(--svg-color--301d2f, #301D2F);
  stop-opacity: 0;
}

.kn-keubds {
  fill: var(--svg-color--8a7e97, #8A7E97);
  fill-rule: evenodd;
  d: path("M20.689 28.784a4.84 4.84 0 1 0 0-9.68a4.84 4.84 0 0 0 0 9.68m0-.781a4.059 4.059 0 1 0 0-8.118a4.059 4.059 0 0 0 0 8.118");
}

.kn42mcchn {
  stop-color: var(--svg-color--967dc8, #967DC8);
}

.ko2yut79d {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M13.343 5.214a.7.7 0 0 0-.195.028a.136.136 0 1 1-.09-.257a1 1 0 0 1 .28-.043a.9.9 0 0 1 .395.075a.136.136 0 0 1-.112.248a.7.7 0 0 0-.279-.051");
}

.ktc-s82to {
  stop-color: var(--svg-color--615f82, #615F82);
  stop-opacity: 0;
}

.ku1djbbcg {
  stop-color: var(--svg-color--64487f, #64487F);
}

.kzr6sffft {
  stop-color: var(--svg-color--967dc8, #967DC8);
  stop-opacity: 0;
}

.l-3q2ti-u {
  stop-color: var(--svg-color--48302f, #48302F);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.laa0aab1b {
  stop-color: var(--svg-color--46295f, #46295F);
}

.lfwvarbqo {
  stop-color: var(--svg-color--1b1423, #1B1423);
}

.ln8qc12st {
  stop-color: var(--svg-color--544341, #544341);
}

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.lucd7-9cq {
  stop-color: var(--svg-color--3d2c4c, #3D2C4C);
}

.lvn5-ac9d {
  stop-color: var(--svg-color--c62f3a, #C62F3A);
}

.mjgjl--ea {
  d: path("m14.77 7.572l1.75-.896l.753 2.258l-1.77.647z");
}

.mvz3giwen {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M13.963 7.07a.113.113 0 0 1 .033.157c-.166.253-.46.372-.555.403a.113.113 0 0 1-.07-.215c.081-.027.313-.125.435-.312a.113.113 0 0 1 .157-.033");
}

.mz7wlj55e {
  stop-color: var(--svg-color--3f2245, #3F2245);
  stop-opacity: 0;
}

.n0w_cmcuq {
  stop-color: var(--svg-color--523c64, #523C64);
}

.n3h2abc_m {
  stop-color: var(--svg-color--654970, #654970);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nr88ykboe {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.088 6.228l.875-.191c-.075-.347-.333-.585-.574-.533c-.242.053-.377.377-.301.724");
}

.nvvve-trp {
  width: 1.242px;
  height: 6.695px;
  x: 11.107px;
  y: 22.434px;
  rx: 0.621px;
}

.o-5paobui {
  stop-color: var(--svg-color--544341, #544341);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o2t29rbsm {
  stop-color: var(--svg-color--37213e, #37213E);
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
}

.oqr4-mbfk {
  stop-color: var(--svg-color--332156, #332156);
}

.ot_4vnb5m {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.898 5.577c-.142-.09-.34-.075-.422-.056l.358.355c.129-.036.24-.185.064-.299");
}

.oxy7wbbbl {
  d: path("M20.736 11.756h1.162v5.449h-1.162z");
}

.p_9_i7g9o {
  stop-color: var(--svg-color--7c5cb9, #7C5CB9);
  stop-opacity: 0;
}

.p9ept44wt {
  stop-color: var(--svg-color--604098, #604098);
  stop-opacity: 0;
}

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
  stop-opacity: 0;
}

.pneydfmsb {
  cx: 20.783px;
  cy: 23.712px;
  r: 5.559px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.psznkgfrn {
  stop-color: var(--svg-color--9477bc, #9477BC);
  stop-opacity: 0;
}

.pvvrqubct {
  cx: 20.689px;
  cy: 23.944px;
  r: 1.137px;
}

.pyh7r6bag {
  stop-color: var(--svg-color--980a27, #980A27);
}

.q5ajh9bwz {
  width: 4.847px;
  height: 1.452px;
  x: 5.644px;
  y: 23.543px;
  fill: var(--svg-color--7c767d, #7C767D);
  rx: 0.726px;
}

.q6suc5ubz {
  stop-color: var(--svg-color--7a727f, #7A727F);
}

.qahn3-b4x {
  cx: 11.728px;
  cy: 28.489px;
  r: 1.551px;
}

.qb3gn8bfr {
  stop-color: var(--svg-color--8a7794, #8A7794);
  stop-opacity: 0;
}

.qd95gbbzt {
  fill: var(--svg-color--ffb629, #FFB629);
  d: path("M12.12 4.452c-.23-.33-.148-.75-.09-.9c.244-.648.86-.852 1.286-.766c.5.101.718.107 1.353-.193c.713-.338 1.72-.501 2.385.253s.315 1.847.547 2.348s.595.488.852 1.07c.335.875-.158 1.556-.594 1.781c-.437.226-1.443.24-1.923-.467c-.786-1.157-.543-1.854-.792-2.466c-.25-.613-.696-.688-1.358-.4c-.78.341-1.358.18-1.666-.26");
}

.qk81-4fqz {
  stop-color: var(--svg-color--4d3431, #4D3431);
}

.qx2qyypot {
  stop-color: var(--svg-color--2b1e2d, #2B1E2D);
}

.r04agib6p {
  stop-color: var(--svg-color--3f2245, #3F2245);
}

.r7jrsd33e {
  fill: var(--svg-color--745182, #745182);
  d: path("M17.689 12.563c.426-.11 1.248-.693 1.789-1.293c-.414.044-1.345.377-1.79 1.293");
}

.rg3z6xbem {
  stop-color: var(--svg-color--c72b4c, #C72B4C);
  stop-opacity: 0;
}

.rgr8nhbdi {
  stop-color: var(--svg-color--654970, #654970);
  stop-opacity: 0;
}

.rijqbwbix {
  stop-color: var(--svg-color--938c9b, #938C9B);
  stop-opacity: 0;
}

.roww1df0l {
  stop-color: var(--svg-color--675a75, #675A75);
}

.rs99u8bqf {
  stop-color: var(--svg-color--bb3161, #BB3161);
}

.rufkj9blr {
  d: path("M16.189 10.454a1.11 1.11 0 1 1 1.813-1.283l1.483 2.107c-.871.48-1.793 1.29-1.793 1.29z");
}

.s_nhb9bnh {
  stop-color: var(--svg-color--4e4b80, #4E4B80);
  stop-opacity: 0;
}

.sa2yvrtdg {
  stop-color: var(--svg-color--918697, #918697);
}

.sqtinbbgr {
  stop-color: var(--svg-color--cd3945, #CD3945);
  stop-opacity: 0;
}

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
}

.sstiaym3o {
  stop-color: var(--svg-color--655558, #655558);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.szqa4cczu {
  stop-color: var(--svg-color--524a5b, #524A5B);
}

.t9-j-pbql {
  stop-color: var(--svg-color--2f1f36, #2F1F36);
  stop-opacity: 0;
}

.tc0wqzile {
  d: path("M12.474 6.519a.9.9 0 0 0 .14-.455l.159-.034l.217.996c-.164.163-.44.203-.56.039c-.104-.14-.094-.346.044-.546");
}

.ti0v3dbtx {
  cx: 20.689px;
  cy: 23.944px;
  r: 0.973px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.tis1nnbrp {
  stop-color: var(--svg-color--2f1f36, #2F1F36);
}

.tlllib2dn {
  stop-color: var(--svg-color--a198a7, #A198A7);
}

.tnnezftpu {
  cx: 17.858px;
  cy: 17.846px;
  r: 0.494px;
}

.tnr6qjbmk {
  stop-color: var(--svg-color--997fd4, #997FD4);
}

.toti2-rqa {
  stop-color: var(--svg-color--685294, #685294);
  stop-opacity: 0;
}

.tzf255bgc {
  stop-color: var(--svg-color--534b49, #534B49);
}

.u245iqdps {
  stop-color: var(--svg-color--938c9b, #938C9B);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uqxwa8ern {
  stop-color: var(--svg-color--3c2053, #3C2053);
}

.us60yytqw {
  stop-color: var(--svg-color--3b223c, #3B223C);
  stop-opacity: 0;
}

.uysgu56cq {
  stop-color: var(--svg-color--48302c, #48302C);
}

.v06h3pbnx {
  stop-color: var(--svg-color--3f2c51, #3F2C51);
}

.v23x_cgsr {
  stop-color: var(--svg-color--482c2e, #482C2E);
}

.v2sjqebcr {
  fill-rule: evenodd;
  d: path("M11.107 19.88c0-.484.337-.797.82-.797h7.008v7.53h-4.726a.895.895 0 0 1-.864-.685a1.86 1.86 0 0 0-.562-.925a1.86 1.86 0 0 0-.928-.461a.896.896 0 0 1-.748-.877zm1.5.453a.25.25 0 0 0-.25.25v2.488c0 .18.12.335.288.4c.35.136.682.338.977.606c.328.297.58.647.752 1.023c.07.155.22.264.39.264h2.92v-5.031z");
}

.vbd7v4bfq {
  stop-color: var(--svg-color--26172f, #26172F);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
}

.vp5ble8bb {
  stop-color: var(--svg-color--89828d, #89828D);
}

.vv-cpsbto {
  fill-rule: evenodd;
  d: path("M14.486 17.165a.775.775 0 0 0-.776.775v2.389h-1a.15.15 0 0 1-.15-.15V17.94c0-1.063.862-1.925 1.926-1.925h6.18a.25.25 0 0 1 .25.25v2.75h-1.15v-1.85z");
}

.vxrkdvuju {
  stop-color: var(--svg-color--31223f, #31223F);
  stop-opacity: 0;
}

.w-8ci9bkh {
  stop-color: var(--svg-color--c8325e, #C8325E);
}

.w1eer1bsh {
  d: path("M12.12 4.452c-.23-.33-.148-.75-.09-.9c.244-.648.86-.852 1.286-.766c.5.101.718.107 1.353-.193c.713-.338 1.72-.501 2.385.253s.315 1.847.547 2.348s.595.488.852 1.07c.335.875-.158 1.556-.594 1.781c-.437.226-1.443.24-1.923-.467c-.786-1.157-.543-1.854-.792-2.466c-.25-.613-.696-.688-1.358-.4c-.78.341-1.358.18-1.666-.26");
}

.wcmsiyb5p {
  d: path("m13.45 6.148l-.01-.065c-.036-.164-.134-.282-.22-.263s-.127.167-.09.331q.006.033.017.063z");
}

.wimyepb3r {
  cx: 13.174px;
  cy: 5.882px;
  rx: 0.058px;
  ry: 0.079px;
}

.x3lzt0c-k {
  stop-color: var(--svg-color--d52e59, #D52E59);
}

.x4ldqjsok {
  stop-color: var(--svg-color--484151, #484151);
}

.x8v8a_bhe {
  stop-color: var(--svg-color--49344d, #49344D);
}

.xb91u7b-b {
  stop-color: var(--svg-color--3b223c, #3B223C);
}

.xg-uv87bb {
  d: path("M13.624 6.11v-.003c-.063-.283-.234-.487-.384-.454s-.222.289-.16.573v.003z");
}

.xh1d24icr {
  d: path("M15.383 15.376c-.312-1.038-.937-3.994-.59-5.739c.438-1.445 1.743-1.46 2.376-1.39c.773.086 1.601.476 2.039 1.836c.453 1.25.58 4.08.633 5.445h-.875v-.152z");
}

.xjmwsybmx {
  stop-color: var(--svg-color--3b2a2c, #3B2A2C);
}

.xmgfgzxde {
  stroke: var(--svg-color--5d4b49, #5D4B49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m18.966 11.942l.84 1.273a.98.98 0 0 1 .146.732c-.222 1.1-.717 3.27-1.36 4.776");
}

.xrnpsubav {
  stop-color: var(--svg-color--a198a7, #A198A7);
  stop-opacity: 0;
}

.xudiynxns {
  stop-color: var(--svg-color--5f5168, #5F5168);
}

.xv1iy6bqi {
  cx: 11.728px;
  cy: 28.489px;
  r: 1.723px;
}

.y_tk3gbcd {
  fill: var(--svg-color--241823, #241823);
  d: path("M12.12 4.452c-.23-.33-.148-.75-.09-.9c.244-.648.86-.852 1.286-.766c.5.101.718.107 1.353-.193c.713-.338 1.72-.501 2.385.253s.315 1.847.547 2.348s.595.488.852 1.07c.335.875-.158 1.556-.594 1.781c-.437.226-1.443.24-1.923-.467c-.786-1.157-.543-1.854-.792-2.466c-.25-.613-.696-.688-1.358-.4c-.78.341-1.358.18-1.666-.26");
}

.y0h7csylp {
  fill: var(--svg-color--553750, #553750);
  d: path("m9.247 24.176l1.922-6.5l1.032 1.75z");
}

.y3ij90b8v {
  stop-color: var(--svg-color--8a7794, #8A7794);
}

.yfcml8bws {
  stop-color: var(--svg-color--866db3, #866DB3);
}

.ym5c6ha3r {
  stop-color: var(--svg-color--980a27, #980A27);
  stop-opacity: 0;
}

.yp_2y0bkd {
  stop-color: var(--svg-color--d53155, #D53155);
}

.ys8863_0j {
  stop-color: var(--svg-color--e35373, #E35373);
}

.yu7wmpb_a {
  stop-color: var(--svg-color--4b3d47, #4B3D47);
}

.yutdbcb6i {
  stop-color: var(--svg-color--655558, #655558);
  stop-opacity: 0;
}

.yv3zhzb_e {
  fill-rule: evenodd;
  d: path("M20.689 30.212a6.268 6.268 0 1 0 0-12.536a6.268 6.268 0 0 0 0 12.536m0-1.428a4.84 4.84 0 1 0 0-9.68a4.84 4.84 0 0 0 0 9.68");
}

.z-rtjcc0y {
  stop-color: var(--svg-color--31223f, #31223F);
}

.z3yur8boj {
  stop-color: var(--svg-color--dccaee, #DCCAEE);
}

.z4for55kd {
  stop-color: var(--svg-color--1b1423, #1B1423);
  stop-opacity: 0;
}

.zax-lz03d {
  stop-color: var(--svg-color--463a52, #463A52);
}

.zg7ndleiu {
  stop-color: var(--svg-color--443850, #443850);
}

.zige1b1kr {
  stop-color: var(--svg-color--6e5c72, #6E5C72);
  stop-opacity: 0;
}

.zp_517jgm {
  stop-color: var(--svg-color--604098, #604098);
}

.zpg97tbto {
  stop-color: var(--svg-color--432b2f, #432B2F);
}

.zuaxx5qad {
  stop-color: var(--svg-color--7f758d, #7F758D);
  stop-opacity: 0;
}

.zvdxxxvck {
  fill: var(--svg-color--47302d, #47302D);
  d: path("m18.655 13.528l-1.025-1.344l1.418-1.133c.203.239.703.942 1.144 1.524c.452.595.448 1.383.352 1.734c-.232 1.052-.753 3.316-.922 3.953c-.211.797-.461.946-.938 1.055c-.476.11-1.285-.312-1.222-.93c.027-.48.387-.695.644-1.484c.218-.871.512-2.274.643-2.99a.5.5 0 0 0-.094-.385");
}

.zzc1m6bsl {
  stop-color: var(--svg-color--4b3d47, #4B3D47);
  stop-opacity: 0;
}

</style>
