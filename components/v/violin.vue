<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iTMeMGh)" class="o63-e6lxl"/><path fill="url(#iGNtKKe)" class="o63-e6lxl"/><path fill="url(#i6Tr5hb)" class="o63-e6lxl"/><path fill="url(#ina8eKd)" class="o63-e6lxl"/><path fill="url(#iIBhqfb)" class="o63-e6lxl"/><path fill="url(#i6OeH7R)" class="i_9k33b9z"/><path fill="url(#iKDYLxH)" class="i_9k33b9z"/><path fill="url(#iEyzQYd)" class="i_9k33b9z"/><path fill="url(#iO9Pz4c)" class="i_9k33b9z"/><path fill="url(#iO1ESid)" class="i_9k33b9z"/><path fill="url(#iU7VfYd)" class="ie_hakb4r"/><path fill="url(#i6saPwe)" class="i_9k33b9z"/><path fill="url(#iymigVG)" class="i_9k33b9z"/><path fill="url(#isL4kmA)" class="i_9k33b9z"/><path fill="url(#i7njRrb)" class="i_9k33b9z"/><path fill="url(#iLfAnre)" class="i_9k33b9z"/><path fill="url(#iiaO9td)" class="o63-e6lxl"/><path fill="url(#iIn0L9d)" class="i_9k33b9z"/><path fill="url(#ivGTphI)" class="i_9k33b9z"/><path fill="url(#i2gkj8c)" class="i_9k33b9z"/><path fill="url(#iKdKsvc)" class="i_9k33b9z"/><path fill="url(#iJQJzue)" class="i_9k33b9z"/><path fill="url(#iyo782t)" class="yu1p-m-2u"/><path fill="url(#iJ1LHCb)" class="yu1p-m-2u"/><path fill="url(#iP3bnGc)" class="i_9k33b9z"/><path fill="url(#i4P6T4b)" class="i_9k33b9z"/><path fill="url(#iMSZW9c)" class="i_9k33b9z"/><path fill="url(#iUEZycW)" class="yr3hmpb_j"/><path fill="url(#idlmWUd)" class="yr3hmpb_j"/><path fill="url(#irePGBc)" class="fh_3ts_vy"/><path fill="url(#ipQn3Gb)" class="fh_3ts_vy"/><path fill="url(#iO1FDgL)" class="fh_3ts_vy"/><path class="mqx81yb3y"/><path fill="url(#iy3qHjc)" class="mev6j7btg"/><path fill="url(#iz0UFOr)" class="mev6j7btg"/><path fill="url(#iIVflJc)" class="mev6j7btg"/><path fill="url(#iXL5rlb)" class="mev6j7btg"/><circle fill="url(#iUzsV2c)" class="wm5dwv3sm"/><circle fill="url(#iBZTjXb)" class="wm5dwv3sm"/><circle fill="url(#i9HqGxd)" class="p9rl6ybsj"/><circle fill="url(#iYgn47d)" class="p9rl6ybsj"/><circle fill="url(#iNl6kMc)" class="cim4b15lc"/><circle fill="url(#izDQuNe)" class="cim4b15lc"/><circle fill="url(#ieyz0od)" class="c_c84--om"/><circle fill="url(#ilHjWBe)" class="c_c84--om"/><path fill="url(#iJoA3Vc)" class="i9us3gb5k"/><path fill="url(#ieNfKye)" class="p5b51wb7o"/><path fill="url(#i4I5RXb)" class="p5b51wb7o"/><path fill="url(#ieNfKye)" class="p5b51wb7o"/><path fill="url(#i4I5RXb)" class="p5b51wb7o"/><path fill="url(#iD9aPLd)" class="p5b51wb7o"/><path fill="url(#iRAhItd)" class="bd4ej7bid"/><path fill="url(#ipitlpd)" class="bd4ej7bid"/><path fill="url(#idxzTGt)" class="mzq55bcit"/><path fill="url(#ixHf81d)" class="vfw7wibex"/><path class="u_vueng6g"/><path fill="url(#izTWy2Y)" class="xor-r7znr"/><path fill="url(#ieebPqb)" class="xor-r7znr"/><path fill="url(#ic8EZgd)" class="xor-r7znr"/><path fill="url(#iPIEqXb)" class="xor-r7znr"/><path fill="url(#iJa8lJe)" class="xor-r7znr"/><path fill="url(#ibkCIkp)" class="xor-r7znr"/><path fill="url(#iIWwi3b)" class="xor-r7znr"/><path fill="url(#ib8NAzt)" class="xor-r7znr"/><path fill="url(#iPD6Xre)" class="xor-r7znr"/><path fill="url(#iVGrEve)" class="xor-r7znr"/><path fill="url(#immABBE)" class="xor-r7znr"/><path class="ixb165b7e"/><path fill="url(#icI7pvY)" class="tb-pvwb4y"/><path fill="url(#iZ8v1Eb)" class="tb-pvwb4y"/><path fill="url(#iZIyGqc)" class="tb-pvwb4y"/><path fill="url(#iI5Tqcb)" class="tb-pvwb4y"/><path fill="url(#imeSHSc)" class="tb-pvwb4y"/><path fill="url(#ib5V9dd)" class="tb-pvwb4y"/><path fill="url(#irg2Opc)" class="tb-pvwb4y"/><path fill="url(#iohylsK)" class="tb-pvwb4y"/><path fill="url(#iPCs4Kb)" class="tb-pvwb4y"/><path fill="url(#iKTEx4Q)" class="tb-pvwb4y"/><path fill="url(#ixoRFMO)" class="tb-pvwb4y"/><path fill="url(#i2UOkhc)" clip-rule="evenodd" class="gv0g39bjx"/><path fill="url(#i5vjNOe)" clip-rule="evenodd" class="qnybe4zuj"/><path fill="url(#ietfmkd)" clip-rule="evenodd" class="qnybe4zuj"/><path fill="url(#isKKYZb)" clip-rule="evenodd" class="qnybe4zuj"/><path fill="url(#iBdu35P)" clip-rule="evenodd" class="qnybe4zuj"/><path fill="url(#ivnlWZb)" clip-rule="evenodd" class="qnybe4zuj"/><path fill="url(#iQ91oce)" clip-rule="evenodd" class="stinhv2fm"/><path fill="url(#igBGjJd)" clip-rule="evenodd" class="pqj9m7bxs"/><path fill="url(#iUHYhSc)" class="m9ox-0b4q"/><path fill="url(#i8d0fwt)" class="m9ox-0b4q"/><path fill="url(#iCVwIie)" class="m9ox-0b4q"/><path fill="url(#i5l8fMd)" class="m9ox-0b4q"/><path fill="url(#iSg1mHs)" class="m9ox-0b4q"/><circle fill="url(#idVIujb)" class="drbg0xbwn"/><defs><radialGradient id="iGNtKKe" cx="0" cy="0" r="1" gradientTransform="matrix(6.93227 -3.96357 3.71119 6.49086 17.687 21.089)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="ao13v-5ag"/><stop offset=".264" class="be3qfpbdf"/></radialGradient><radialGradient id="iKDYLxH" cx="0" cy="0" r="1" gradientTransform="matrix(2.86028 3.01116 -20.01054 19.00789 22.255 17.652)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="v8mlxjbcn"/><stop offset=".192" class="zjv1z1bua"/></radialGradient><radialGradient id="iEyzQYd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5902 -2.51526 31.97277 -32.92543 13.796 10.562)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="x90qjmfpc"/><stop offset=".132" class="be3qfpbdf"/></radialGradient><radialGradient id="iO9Pz4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23726 -2.60825 33.15483 -15.72747 15.234 9.14)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="x90qjmfpc"/><stop offset=".233" class="be3qfpbdf"/></radialGradient><radialGradient id="iiaO9td" cx="0" cy="0" r="1" gradientTransform="matrix(3.08914 -8.14047 7.00114 2.65679 10.908 14.673)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="ao13v-5ag"/><stop offset=".264" class="be3qfpbdf"/></radialGradient><radialGradient id="iIn0L9d" cx="0" cy="0" r="1" gradientTransform="rotate(-32.493 27.867 -8.875)scale(4.01756 6.4351)" gradientUnits="userSpaceOnUse"><stop offset=".445" class="xg0n-aciq"/><stop offset=".589" class="r4nrlwb3b"/><stop offset=".724" class="a1ulhobsg"/></radialGradient><radialGradient id="ivGTphI" cx="0" cy="0" r="1" gradientTransform="matrix(2.3558 -.58967 .87202 3.48383 16.68 22.084)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="xg0n-aciq"/><stop offset=".597" class="r4nrlwb3b"/><stop offset=".724" class="a1ulhobsg"/></radialGradient><radialGradient id="i2gkj8c" cx="0" cy="0" r="1" gradientTransform="matrix(1.5462 -.4541 .67154 2.28657 17.478 23.828)" gradientUnits="userSpaceOnUse"><stop offset=".367" class="xg0n-aciq"/><stop offset="1" class="a1ulhobsg"/></radialGradient><radialGradient id="iKdKsvc" cx="0" cy="0" r="1" gradientTransform="matrix(3.5448 2.0541 -5.7464 9.91666 5.385 25.609)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="teiod1bfq"/><stop offset=".243" class="nafbtxmel"/></radialGradient><radialGradient id="iJQJzue" cx="0" cy="0" r="1" gradientTransform="matrix(2.06407 3.38371 -15.77533 9.62296 6.588 27.066)" gradientUnits="userSpaceOnUse"><stop offset=".059" class="c7op0obuz"/><stop offset=".271" class="be3qfpbdf"/></radialGradient><radialGradient id="iyo782t" cx="0" cy="0" r="1" gradientTransform="rotate(35.949 -33.773 21.642)scale(2.84812 6.59951)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="teiod1bfq"/><stop offset=".275" class="nafbtxmel"/></radialGradient><radialGradient id="iJ1LHCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15272 1.19542 -2.59707 2.50432 6.514 23.345)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="xaxqf_btu"/><stop offset=".275" class="nafbtxmel"/></radialGradient><radialGradient id="iP3bnGc" cx="0" cy="0" r="1" gradientTransform="rotate(136.501 -.855 13.634)scale(2.89829 6.42657)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="w267ym0pr"/><stop offset=".337" class="n7q9albsa"/></radialGradient><radialGradient id="i4P6T4b" cx="0" cy="0" r="1" gradientTransform="rotate(135.275 -.367 13.447)scale(1.54872 5.40803)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="l5u7n8b8x"/><stop offset=".513" class="mgw4zyboo"/></radialGradient><radialGradient id="iMSZW9c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73812 .79778 -.81266 -2.78921 8.545 25.31)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="ploac4y7y"/><stop offset=".38" class="n7q9albsa"/></radialGradient><radialGradient id="iy3qHjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.93749 .92188 -1.9737 -2.00712 28.484 4.36)" gradientUnits="userSpaceOnUse"><stop class="up5zi985n"/><stop offset="1" class="g0abp1bzn"/></radialGradient><radialGradient id="iUzsV2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.92188 .85156 0 27.817 8.153)" gradientUnits="userSpaceOnUse"><stop class="r18z41bwj"/><stop offset="1" class="f5rm10bfs"/></radialGradient><radialGradient id="iBZTjXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 .4414 -.4414 -.39844 28.157 7.52)" gradientUnits="userSpaceOnUse"><stop class="d5nvfy4qv"/><stop offset="1" class="lx_q5wadl"/></radialGradient><radialGradient id="i9HqGxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.92188 .85156 0 24.273 4.547)" gradientUnits="userSpaceOnUse"><stop class="r18z41bwj"/><stop offset="1" class="f5rm10bfs"/></radialGradient><radialGradient id="iYgn47d" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 .4414 -.4414 -.39844 24.613 3.915)" gradientUnits="userSpaceOnUse"><stop class="d5nvfy4qv"/><stop offset="1" class="lx_q5wadl"/></radialGradient><radialGradient id="iNl6kMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.92188 .85156 0 29.309 7.012)" gradientUnits="userSpaceOnUse"><stop class="r18z41bwj"/><stop offset="1" class="f5rm10bfs"/></radialGradient><radialGradient id="izDQuNe" cx="0" cy="0" r="1" gradientTransform="rotate(132.072 13.407 9.78)scale(.59463)" gradientUnits="userSpaceOnUse"><stop class="d5nvfy4qv"/><stop offset="1" class="lx_q5wadl"/></radialGradient><radialGradient id="ieyz0od" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.92188 .85156 0 25.39 3.083)" gradientUnits="userSpaceOnUse"><stop class="r18z41bwj"/><stop offset="1" class="f5rm10bfs"/></radialGradient><radialGradient id="ilHjWBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 .4414 -.4414 -.39844 25.73 2.45)" gradientUnits="userSpaceOnUse"><stop class="d5nvfy4qv"/><stop offset="1" class="lx_q5wadl"/></radialGradient><radialGradient id="izTWy2Y" cx="0" cy="0" r="1" gradientTransform="matrix(.18276 .63813 -.63679 .18238 14.019 19.916)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="arsswr3-s"/><stop offset=".829" class="pemjq-bzw"/></radialGradient><radialGradient id="ieebPqb" cx="0" cy="0" r="1" gradientTransform="matrix(.14441 .06215 -.49368 1.14717 14.523 21.031)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="arsswr3-s"/><stop offset=".652" class="pemjq-bzw"/></radialGradient><radialGradient id="ic8EZgd" cx="0" cy="0" r="1" gradientTransform="matrix(.53856 -.57188 1.25474 1.18165 14.153 23.755)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="arsswr3-s"/><stop offset=".349" class="pemjq-bzw"/></radialGradient><radialGradient id="iPIEqXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2534 -.60558 .6043 -.25287 14.639 23.714)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="arsswr3-s"/><stop offset=".829" class="pemjq-bzw"/></radialGradient><radialGradient id="iJa8lJe" cx="0" cy="0" r="1" gradientTransform="matrix(.63119 .36447 -1.36347 2.36123 14.243 21.82)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="arsswr3-s"/><stop offset=".397" class="pemjq-bzw"/></radialGradient><radialGradient id="ibkCIkp" cx="0" cy="0" r="1" gradientTransform="matrix(.73736 -.02372 .06458 2.00787 13.805 23.052)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="arsswr3-s"/><stop offset=".349" class="pemjq-bzw"/></radialGradient><radialGradient id="iIWwi3b" cx="0" cy="0" r="1" gradientTransform="matrix(.63292 .14631 -.4826 2.08768 13.898 22.543)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="arsswr3-s"/><stop offset=".349" class="pemjq-bzw"/></radialGradient><radialGradient id="ib8NAzt" cx="0" cy="0" r="1" gradientTransform="rotate(-29.745 50.89 -14.627)scale(.27782 .75651)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="arsswr3-s"/><stop offset=".463" class="pemjq-bzw"/></radialGradient><radialGradient id="iPD6Xre" cx="0" cy="0" r="1" gradientTransform="matrix(.50781 .09375 -.2713 1.46957 14.734 20.808)" gradientUnits="userSpaceOnUse"><stop offset=".37" class="arsswr3-s"/><stop offset=".472" class="pemjq-bzw"/></radialGradient><radialGradient id="iVGrEve" cx="0" cy="0" r="1" gradientTransform="matrix(.51172 -.34375 .68694 1.0226 14.55 20.047)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="arsswr3-s"/><stop offset=".439" class="pemjq-bzw"/></radialGradient><radialGradient id="immABBE" cx="0" cy="0" r="1" gradientTransform="matrix(.38322 -.03915 .13727 1.34358 14.66 20.465)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="arsswr3-s"/><stop offset=".439" class="pemjq-bzw"/></radialGradient><radialGradient id="icI7pvY" cx="0" cy="0" r="1" gradientTransform="matrix(-.6401 -.17577 .1754 -.63875 12.195 18.064)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="arsswr3-s"/><stop offset=".829" class="pemjq-bzw"/></radialGradient><radialGradient id="iZ8v1Eb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06372 -.14373 1.1417 -.50617 11.074 17.574)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="arsswr3-s"/><stop offset=".652" class="pemjq-bzw"/></radialGradient><radialGradient id="iZIyGqc" cx="0" cy="0" r="1" gradientTransform="rotate(-43.907 26.473 -1.377)scale(.78555 1.72356)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="arsswr3-s"/><stop offset=".349" class="pemjq-bzw"/></radialGradient><radialGradient id="iI5Tqcb" cx="0" cy="0" r="1" gradientTransform="matrix(.6083 .24677 -.24625 .60702 8.39 17.488)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="arsswr3-s"/><stop offset=".829" class="pemjq-bzw"/></radialGradient><radialGradient id="imeSHSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.37134 -.62717 2.34622 -1.38916 10.29 17.863)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="arsswr3-s"/><stop offset=".397" class="pemjq-bzw"/></radialGradient><radialGradient id="ib5V9dd" cx="0" cy="0" r="1" gradientTransform="matrix(.01566 -.73757 2.00846 .04264 9.062 18.314)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="arsswr3-s"/><stop offset=".349" class="pemjq-bzw"/></radialGradient><radialGradient id="irg2Opc" cx="0" cy="0" r="1" gradientTransform="rotate(-103.642 11.947 5.345)scale(.64961 2.14273)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="arsswr3-s"/><stop offset=".349" class="pemjq-bzw"/></radialGradient><radialGradient id="iohylsK" cx="0" cy="0" r="1" gradientTransform="matrix(.1352 -.2427 .6609 .36814 8.791 18.16)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="arsswr3-s"/><stop offset=".463" class="pemjq-bzw"/></radialGradient><radialGradient id="iPCs4Kb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0993 -.50676 1.46651 -.28735 11.295 17.36)" gradientUnits="userSpaceOnUse"><stop offset=".37" class="arsswr3-s"/><stop offset=".472" class="pemjq-bzw"/></radialGradient><radialGradient id="iKTEx4Q" cx="0" cy="0" r="1" gradientTransform="matrix(.33814 -.51544 1.03004 .67573 12.059 17.535)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="arsswr3-s"/><stop offset=".439" class="pemjq-bzw"/></radialGradient><radialGradient id="ixoRFMO" cx="0" cy="0" r="1" gradientTransform="matrix(.03496 -.38362 1.345 .12259 11.64 17.43)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="arsswr3-s"/><stop offset=".439" class="pemjq-bzw"/></radialGradient><radialGradient id="isKKYZb" cx="0" cy="0" r="1" gradientTransform="rotate(93.929 -.546 6.552)scale(2.82271)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="xu2ww1b_p"/><stop offset=".393" class="cr31n-kyp"/></radialGradient><radialGradient id="iBdu35P" cx="0" cy="0" r="1" gradientTransform="matrix(.9971 2.33812 -3.6143 1.54133 4.763 8.023)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="kfjdjwb0k"/><stop offset=".393" class="ffyp55b1y"/></radialGradient><radialGradient id="iSg1mHs" cx="0" cy="0" r="1" gradientTransform="matrix(.83269 .76074 -.49064 .53705 22.79 24.946)" gradientUnits="userSpaceOnUse"><stop offset=".303"/><stop offset=".851" class="k05n1gbkm"/></radialGradient><radialGradient id="idVIujb" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.002 24.918)scale(.43408)" gradientUnits="userSpaceOnUse"><stop class="t0bcq0m-q"/><stop offset="1" class="mtl3kpbcv"/></radialGradient><linearGradient id="iTMeMGh" x1="21.718" x2="7.094" y1="12.422" y2="28.422" gradientUnits="userSpaceOnUse"><stop class="q0f7ujb8h"/><stop offset="1" class="ls3aagdqy"/></linearGradient><linearGradient id="i6Tr5hb" x1="21.718" x2="20.332" y1="12.422" y2="13.809" gradientUnits="userSpaceOnUse"><stop offset=".074" class="s-u0-oblt"/><stop offset=".391" class="r25rm6qxi"/></linearGradient><linearGradient id="ina8eKd" x1="23.216" x2="19.822" y1="13.894" y2="14.573" gradientUnits="userSpaceOnUse"><stop offset=".116" class="s-u0-oblt"/><stop offset=".253" class="r25rm6qxi"/></linearGradient><linearGradient id="iIBhqfb" x1="23.216" x2="20.93" y1="16.084" y2="15.224" gradientUnits="userSpaceOnUse"><stop offset=".134" class="s-u0-oblt"/><stop offset=".408" class="r25rm6qxi"/></linearGradient><linearGradient id="i6OeH7R" x1="16.525" x2="16.494" y1="8.491" y2="12.155" gradientUnits="userSpaceOnUse"><stop offset=".174" class="s-u0-oblt"/><stop offset=".408" class="r25rm6qxi"/></linearGradient><linearGradient id="iO1ESid" x1="2.869" x2="7.545" y1="28.258" y2="23.336" gradientUnits="userSpaceOnUse"><stop offset=".396" class="v7r5qej8k"/><stop offset=".486" class="vjg0vy6ru"/></linearGradient><linearGradient id="iU7VfYd" x1="14.174" x2="10.133" y1="31.204" y2="27.268" gradientUnits="userSpaceOnUse"><stop offset=".47" class="shsyngm7m"/><stop offset=".538" class="x5z9dtbxc"/></linearGradient><linearGradient id="i6saPwe" x1="8.828" x2="10.133" y1="31.067" y2="27.268" gradientUnits="userSpaceOnUse"><stop offset=".396" class="v7r5qej8k"/><stop offset=".541" class="vjg0vy6ru"/></linearGradient><linearGradient id="iymigVG" x1="10.528" x2="10.133" y1="31.208" y2="27.268" gradientUnits="userSpaceOnUse"><stop offset=".396" class="v7r5qej8k"/><stop offset=".55" class="vjg0vy6ru"/></linearGradient><linearGradient id="isL4kmA" x1="2.755" x2="5.666" y1="17.307" y2="20.12" gradientUnits="userSpaceOnUse"><stop offset=".47" class="jkpcega_x"/><stop offset=".538" class="wy09p1bjj"/></linearGradient><linearGradient id="i7njRrb" x1="1.796" x2="4.443" y1="23.629" y2="22.816" gradientUnits="userSpaceOnUse"><stop offset=".333" class="v7r5qej8k"/><stop offset=".55" class="vjg0vy6ru"/></linearGradient><linearGradient id="iLfAnre" x1="2.114" x2="4.087" y1="20.612" y2="21.006" gradientUnits="userSpaceOnUse"><stop offset=".333" class="v7r5qej8k"/><stop offset=".55" class="vjg0vy6ru"/></linearGradient><linearGradient id="iUEZycW" x1="18.343" x2="23.687" y1="14.297" y2="8.672" gradientUnits="userSpaceOnUse"><stop class="ac37ogrln"/><stop offset="1" class="eqeajtbej"/></linearGradient><linearGradient id="idlmWUd" x1="25.711" x2="25.015" y1="6.454" y2="7.141" gradientUnits="userSpaceOnUse"><stop offset=".179" class="xn1-q8bch"/><stop offset="1" class="lpu2jgp6a"/></linearGradient><linearGradient id="irePGBc" x1="24.418" x2="22.685" y1="10.216" y2="8.64" gradientUnits="userSpaceOnUse"><stop offset=".226" class="xn1-q8bch"/><stop offset=".451" class="lpu2jgp6a"/></linearGradient><linearGradient id="ipQn3Gb" x1="21.478" x2="23.555" y1="7.559" y2="9.75" gradientUnits="userSpaceOnUse"><stop offset=".271" class="xn1-q8bch"/><stop offset=".461" class="lpu2jgp6a"/></linearGradient><linearGradient id="iO1FDgL" x1="16.265" x2="19.431" y1="15.511" y2="12.01" gradientUnits="userSpaceOnUse"><stop offset=".247" class="xn1-q8bch"/><stop offset=".38" class="lpu2jgp6a"/></linearGradient><linearGradient id="iz0UFOr" x1="24.534" x2="27.093" y1="3.516" y2="4.924" gradientUnits="userSpaceOnUse"><stop offset=".133" class="t-7intbbv"/><stop offset="1" class="jzedgabbo"/></linearGradient><linearGradient id="iIVflJc" x1="25.351" x2="27.091" y1="6.665" y2="4.921" gradientUnits="userSpaceOnUse"><stop offset=".133" class="kn--bvqax"/><stop offset=".625" class="jzedgabbo"/></linearGradient><linearGradient id="iXL5rlb" x1="28.853" x2="27.094" y1="7.24" y2="4.924" gradientUnits="userSpaceOnUse"><stop offset=".133" class="kn--bvqax"/><stop offset=".625" class="jzedgabbo"/></linearGradient><linearGradient id="iJoA3Vc" x1="9.469" x2="10.094" y1="20.829" y2="24.086" gradientUnits="userSpaceOnUse"><stop class="upspb_5gk"/><stop offset="1" class="bd61101ba"/></linearGradient><linearGradient id="ieNfKye" x1="8.343" x2="5.062" y1="24.204" y2="27.422" gradientUnits="userSpaceOnUse"><stop offset=".527" class="oi-gdiboo"/><stop offset="1" class="r20yrqb7j"/></linearGradient><linearGradient id="i4I5RXb" x1="8.39" x2="8.089" y1="23.985" y2="24.278" gradientUnits="userSpaceOnUse"><stop offset=".452" class="e2hetvvjv"/><stop offset="1" class="ul2smacci"/></linearGradient><linearGradient id="iD9aPLd" x1="8.828" x2="8.136" y1="23.434" y2="24.113" gradientUnits="userSpaceOnUse"><stop offset=".652" class="xn1-q8bch"/><stop offset=".856" class="lpu2jgp6a"/></linearGradient><linearGradient id="iRAhItd" x1="8.9" x2="7.424" y1="26.41" y2="24.416" gradientUnits="userSpaceOnUse"><stop offset=".26" class="w2mohub-r"/><stop offset=".337" class="lpu2jgp6a"/></linearGradient><linearGradient id="ipitlpd" x1="5.519" x2="7.77" y1="23.287" y2="25.012" gradientUnits="userSpaceOnUse"><stop offset=".271" class="lrqxabc_t"/><stop offset=".343" class="lpu2jgp6a"/></linearGradient><linearGradient id="idxzTGt" x1="7.221" x2="7.016" y1="22.68" y2="23.948" gradientUnits="userSpaceOnUse"><stop offset=".207" class="qp_fmpbiu"/><stop offset=".394" class="lpu2jgp6a"/></linearGradient><linearGradient id="ixHf81d" x1="9.577" x2="8.086" y1="25.077" y2="24.742" gradientUnits="userSpaceOnUse"><stop offset=".16" class="qp_fmpbiu"/><stop offset=".394" class="lpu2jgp6a"/></linearGradient><linearGradient id="i2UOkhc" x1="13.523" x2="12.816" y1="15.704" y2="16.412" gradientUnits="userSpaceOnUse"><stop offset=".078" class="olo361bga"/><stop offset=".273" class="cu_f7fbgl"/><stop offset="1" class="ldvnj3nyu"/></linearGradient><linearGradient id="i5vjNOe" x1="18.197" x2="14.8" y1="14.592" y2="17.989" gradientUnits="userSpaceOnUse"><stop offset=".435" class="qzdhotmts"/><stop offset=".463" class="ryklx6b2y"/><stop offset=".491" class="ryklx6b2y"/><stop offset=".501" class="ryklx6b2y"/><stop offset=".54" class="biwqmmbun"/><stop offset=".566" class="zw__is7tg"/><stop offset=".596" class="zw__is7tg"/><stop offset=".635" class="m3uher0go"/><stop offset=".648" class="fgum-vw7h"/></linearGradient><linearGradient id="ietfmkd" x1="5.142" x2="7.617" y1="5.892" y2="6.86" gradientUnits="userSpaceOnUse"><stop class="jf48uxb1h"/><stop offset="1" class="smyp-yriu"/></linearGradient><linearGradient id="ivnlWZb" x1="3.789" x2="5.688" y1="8.023" y2="6.706" gradientUnits="userSpaceOnUse"><stop offset=".194" class="sqccn578p"/><stop offset=".403" class="dla9rvbtj"/></linearGradient><linearGradient id="iQ91oce" x1="23.423" x2="22.715" y1="22.792" y2="23.499" gradientUnits="userSpaceOnUse"><stop class="sbbmuvdsn"/><stop offset=".232" class="ql9zsy1zs"/><stop offset=".315" class="ql9zsy1zs"/><stop offset="1" class="pjre46zdk"/></linearGradient><linearGradient id="igBGjJd" x1="24.588" x2="23.881" y1="23.943" y2="24.651" gradientUnits="userSpaceOnUse"><stop class="w_haij-xw"/><stop offset=".083" class="jdph8nbex"/><stop offset=".249" class="cu8te_b2r"/><stop offset=".632" class="kro0frsly"/><stop offset="1" class="u7d_5ybfg"/></linearGradient><linearGradient id="iUHYhSc" x1="24.741" x2="22.932" y1="25.104" y2="26.901" gradientUnits="userSpaceOnUse"><stop offset=".106" class="wv6fp90wj"/><stop offset=".201" class="dx5a5ccof"/><stop offset=".735" class="clkd2vbdb"/><stop offset="1" class="bci9subzp"/></linearGradient><linearGradient id="i8d0fwt" x1="24.434" x2="23.953" y1="26.604" y2="26.123" gradientUnits="userSpaceOnUse"><stop offset=".216" class="i1lnhobhh"/><stop offset=".799" class="o_ckynb2l"/></linearGradient><linearGradient id="iCVwIie" x1="23.107" x2="23.953" y1="26.969" y2="26.123" gradientUnits="userSpaceOnUse"><stop offset=".216" class="i1lnhobhh"/><stop offset=".538" class="o_ckynb2l"/></linearGradient><linearGradient id="i5l8fMd" x1="22.295" x2="23.757" y1="24.279" y2="25.902" gradientUnits="userSpaceOnUse"><stop offset=".216" class="i1lnhobhh"/><stop offset=".538" class="o_ckynb2l"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:violin" /></template>
<style>
.a1ulhobsg {
  stop-color: var(--svg-color--8a5955, #8A5955);
  stop-opacity: 0;
}

.ac37ogrln {
  stop-color: var(--svg-color--433e4a, #433E4A);
}

.ao13v-5ag {
  stop-color: var(--svg-color--6b464f, #6B464F);
}

.arsswr3-s {
  stop-color: var(--svg-color--332c3a, #332C3A);
}

.bci9subzp {
  stop-color: var(--svg-color--31243c, #31243C);
}

.bd4ej7bid {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M6.612 23.07a.5.5 0 0 1 .754-.05l1.765 1.786a.5.5 0 0 1-.061.756l-3.138 2.291a.4.4 0 0 1-.518-.04L4.3 26.7a.4.4 0 0 1-.036-.524z");
}

.bd61101ba {
  stop-color: var(--svg-color--f1be92, #F1BE92);
}

.be3qfpbdf {
  stop-color: var(--svg-color--83595b, #83595B);
  stop-opacity: 0;
}

.biwqmmbun {
  stop-color: var(--svg-color--5b4141, #5B4141);
}

.c_c84--om {
  cx: 25.456px;
  cy: 2.512px;
  r: 0.66px;
}

.c7op0obuz {
  stop-color: var(--svg-color--5a393b, #5A393B);
}

.cim4b15lc {
  cx: 29.375px;
  cy: 6.442px;
  r: 0.66px;
}

.clkd2vbdb {
  stop-color: var(--svg-color--38323f, #38323F);
}

.cr31n-kyp {
  stop-color: var(--svg-color--513144, #513144);
  stop-opacity: 0;
}

.cu_f7fbgl {
  stop-color: var(--svg-color--f0bfaa, #F0BFAA);
}

.cu8te_b2r {
  stop-color: var(--svg-color--575757, #575757);
}

.d5nvfy4qv {
  stop-color: var(--svg-color--655d6e, #655D6E);
}

.dla9rvbtj {
  stop-color: var(--svg-color--523a4a, #523A4A);
  stop-opacity: 0;
}

.drbg0xbwn {
  cx: 23.916px;
  cy: 25.919px;
  r: 0.382px;
}

.dx5a5ccof {
  stop-color: var(--svg-color--39333f, #39333F);
}

.e2hetvvjv {
  stop-color: var(--svg-color--6f5f7b, #6F5F7B);
}

.eqeajtbej {
  stop-color: var(--svg-color--554269, #554269);
}

.f5rm10bfs {
  stop-color: var(--svg-color--3c2943, #3C2943);
}

.ffyp55b1y {
  stop-color: var(--svg-color--573346, #573346);
  stop-opacity: 0;
}

.fgum-vw7h {
  stop-color: var(--svg-color--593452, #593452);
}

.fh_3ts_vy {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("m24.93 5.329l1.71 1.695l-7.878 8.729a.75.75 0 0 1-1.078.036l-1.455-1.407a.75.75 0 0 1 .014-1.092z");
}

.ft5dv1b6b {
  fill: none;
}

.g0abp1bzn {
  stop-color: var(--svg-color--a37062, #A37062);
  stop-opacity: 0;
}

.gv0g39bjx {
  fill-rule: evenodd;
  d: path("M3.977 6.866a.5.5 0 0 1 .707 0L23.44 25.622a.5.5 0 0 1-.707.707L3.977 7.573a.5.5 0 0 1 0-.707");
}

.i_9k33b9z {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M14.438 9.88a3.25 3.25 0 0 1 4.596-.041l3.12 3.064a3.25 3.25 0 0 1 .043 4.596l-2.774 2.825a.4.4 0 0 1-.566.005l-.285-.28A1.944 1.944 0 0 0 16.1 23.03h-.007l.697.685c.296.29.3.765.01 1.06l-3.35 3.412a4.75 4.75 0 0 1-6.717.061L3.91 25.476a4.75 4.75 0 0 1-.062-6.717l3.35-3.412a.75.75 0 0 1 1.06-.01l.738.725l.002-.005a1.946 1.946 0 0 0 2.955-2.507l-.285-.28a.4.4 0 0 1-.005-.566z");
}

.i1lnhobhh {
  stop-color: var(--svg-color--201728, #201728);
}

.i9us3gb5k {
  d: path("M8.19 20.788a.793.793 0 0 1 1.12 0l1.946 1.945a.793.793 0 1 1-1.122 1.121L8.19 21.909a.793.793 0 0 1 0-1.121");
}

.ie_hakb4r {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.438 9.88a3.25 3.25 0 0 1 4.596-.041l3.12 3.064a3.25 3.25 0 0 1 .043 4.596l-2.774 2.825a.4.4 0 0 1-.566.005l-.285-.28A1.944 1.944 0 0 0 16.1 23.03h-.007l.697.685c.296.29.3.765.01 1.06l-3.35 3.412a4.75 4.75 0 0 1-6.717.061L3.91 25.476a4.75 4.75 0 0 1-.062-6.717l3.35-3.412a.75.75 0 0 1 1.06-.01l.738.725l.002-.005a1.946 1.946 0 0 0 2.955-2.507l-.285-.28a.4.4 0 0 1-.005-.566z");
}

.ixb165b7e {
  fill: var(--svg-color--2c2630, #2C2630);
  d: path("M11.702 17.664c.036.008.047.051.025.08a.576.576 0 1 0 1.044.33a.7.7 0 0 0-.095-.317c-.058-.098-.166-.285-.33-.426c-.222-.192-.535-.311-.986-.286c-.188.01-.37.075-.532.151a5 5 0 0 0-.483.275l-.12.075c-.274.174-.508.323-.723.391c-.26.083-.517.102-.71.037c-.018-.006-.022-.03-.008-.044a.576.576 0 1 0-.977-.408c.007.558.436.9.794 1.021c.362.122.76.069 1.083-.034c.295-.094.604-.29.868-.459l.112-.071a4 4 0 0 1 .42-.24a.9.9 0 0 1 .309-.095q.189-.009.31.02");
}

.jdph8nbex {
  stop-color: var(--svg-color--5e5e5e, #5E5E5E);
}

.jf48uxb1h {
  stop-color: var(--svg-color--594343, #594343);
}

.jkpcega_x {
  stop-color: var(--svg-color--7d5251, #7D5251);
}

.jzedgabbo {
  stop-color: var(--svg-color--7d4e49, #7D4E49);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.kfjdjwb0k {
  stop-color: var(--svg-color--563346, #563346);
}

.kn--bvqax {
  stop-color: var(--svg-color--562c26, #562C26);
  stop-opacity: 0.71;
}

.kro0frsly {
  stop-color: var(--svg-color--30243a, #30243A);
}

.l5u7n8b8x {
  stop-color: var(--svg-color--82544f, #82544F);
}

.ldvnj3nyu {
  stop-color: var(--svg-color--d6a098, #D6A098);
}

.lpu2jgp6a {
  stop-color: var(--svg-color--504060, #504060);
  stop-opacity: 0;
}

.lrqxabc_t {
  stop-color: var(--svg-color--473752, #473752);
}

.ls3aagdqy {
  stop-color: var(--svg-color--7b4e49, #7B4E49);
}

.lx_q5wadl {
  stop-color: var(--svg-color--655d6e, #655D6E);
  stop-opacity: 0;
}

.m3uher0go {
  stop-color: var(--svg-color--523546, #523546);
}

.m9ox-0b4q {
  d: path("M23.382 25.473c.18-.193-.06-.565-.271-.85a.296.296 0 0 1 .444-.39l1.316 1.297a.27.27 0 0 1 .002.383l-1.093 1.093a.267.267 0 0 1-.377 0l-1.29-1.29a.307.307 0 0 1 0-.435c.115-.115.3-.12.432-.023c.285.206.663.401.837.215");
}

.mev6j7btg {
  d: path("M25.774 2.997a1.25 1.25 0 0 1 1.92-.17l1.38 1.4a1.25 1.25 0 0 1-.174 1.904l-1.616 1.126a.75.75 0 0 1-.966-.091l-1.57-1.612a.75.75 0 0 1-.082-.949z");
}

.mgw4zyboo {
  stop-color: var(--svg-color--82544f, #82544F);
  stop-opacity: 0;
}

.mqx81yb3y {
  fill: var(--svg-color--825250, #825250);
  d: path("M25.774 2.997a1.25 1.25 0 0 1 1.92-.17l1.38 1.4a1.25 1.25 0 0 1-.174 1.904l-1.616 1.126a.75.75 0 0 1-.966-.091l-1.57-1.612a.75.75 0 0 1-.082-.949z");
}

.mtl3kpbcv {
  stop-color: var(--svg-color--ffec56, #FFEC56);
}

.mzq55bcit {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.612 23.07a.5.5 0 0 1 .754-.05l1.765 1.786a.5.5 0 0 1-.061.756l-3.138 2.291a.4.4 0 0 1-.518-.04L4.3 26.7a.4.4 0 0 1-.036-.524z");
}

.n7q9albsa {
  stop-color: var(--svg-color--5a393b, #5A393B);
  stop-opacity: 0;
}

.nafbtxmel {
  stop-color: var(--svg-color--382022, #382022);
  stop-opacity: 0;
}

.o_ckynb2l {
  stop-color: var(--svg-color--3b3244, #3B3244);
  stop-opacity: 0;
}

.o63-e6lxl {
  d: path("M14.438 9.88a3.25 3.25 0 0 1 4.596-.041l3.12 3.064a3.25 3.25 0 0 1 .043 4.596l-2.774 2.825a.4.4 0 0 1-.566.005l-.285-.28A1.944 1.944 0 0 0 16.1 23.03h-.007l.697.685c.296.29.3.765.01 1.06l-3.35 3.412a4.75 4.75 0 0 1-6.717.061L3.91 25.476a4.75 4.75 0 0 1-.062-6.717l3.35-3.412a.75.75 0 0 1 1.06-.01l.738.725l.002-.005a1.946 1.946 0 0 0 2.955-2.507l-.285-.28a.4.4 0 0 1-.005-.566z");
}

.oi-gdiboo {
  stop-color: var(--svg-color--685779, #685779);
}

.olo361bga {
  stop-color: var(--svg-color--e3b09a, #E3B09A);
}

.p5b51wb7o {
  d: path("M6.612 23.07a.5.5 0 0 1 .754-.05l1.765 1.786a.5.5 0 0 1-.061.756l-3.138 2.291a.4.4 0 0 1-.518-.04L4.3 26.7a.4.4 0 0 1-.036-.524z");
}

.p9rl6ybsj {
  cx: 24.339px;
  cy: 3.977px;
  r: 0.66px;
}

.pemjq-bzw {
  stop-color: var(--svg-color--332c3a, #332C3A);
  stop-opacity: 0;
}

.pjre46zdk {
  stop-color: var(--svg-color--c89779, #C89779);
}

.ploac4y7y {
  stop-color: var(--svg-color--5a393b, #5A393B);
  stop-opacity: 0.68;
}

.pqj9m7bxs {
  fill-rule: evenodd;
  d: path("m25.391 26.16l-2.57-2.57l.707-.707l2.57 2.57z");
}

.q0f7ujb8h {
  stop-color: var(--svg-color--9a6460, #9A6460);
}

.ql9zsy1zs {
  stop-color: var(--svg-color--f8d49a, #F8D49A);
}

.qnybe4zuj {
  fill-rule: evenodd;
  d: path("m7.17 6.575l19.804 19.752a.5.5 0 1 1-.708.707L6.488 7.328c-.348-.347-.933-.26-1.308.059c-.263.223-.585.384-.917.282c-.712-.22-1.412-1.376-1.103-1.48c.155-.051.91-.18 1.62-.295a2.94 2.94 0 0 1 2.39.681");
}

.qp_fmpbiu {
  stop-color: var(--svg-color--37234a, #37234A);
  stop-opacity: 0.79;
}

.qzdhotmts {
  stop-color: var(--svg-color--563b37, #563B37);
}

.r18z41bwj {
  stop-color: var(--svg-color--3e2455, #3E2455);
}

.r20yrqb7j {
  stop-color: var(--svg-color--43384e, #43384E);
}

.r25rm6qxi {
  stop-color: var(--svg-color--98635f, #98635F);
  stop-opacity: 0;
}

.r4nrlwb3b {
  stop-color: var(--svg-color--bd8f85, #BD8F85);
  stop-opacity: 0.08;
}

.ryklx6b2y {
  stop-color: var(--svg-color--6d5b58, #6D5B58);
}

.s-u0-oblt {
  stop-color: var(--svg-color--a97d73, #A97D73);
}

.sbbmuvdsn {
  stop-color: var(--svg-color--eccb92, #ECCB92);
}

.shsyngm7m {
  stop-color: var(--svg-color--a6786f, #A6786F);
}

.smyp-yriu {
  stop-color: var(--svg-color--594343, #594343);
  stop-opacity: 0;
}

.sqccn578p {
  stop-color: var(--svg-color--4f3242, #4F3242);
}

.stinhv2fm {
  fill-rule: evenodd;
  d: path("m23.423 24.206l-1.768-1.767l.707-.707l1.768 1.767a.5.5 0 0 1-.707.707");
}

.t-7intbbv {
  stop-color: var(--svg-color--562c26, #562C26);
}

.t0bcq0m-q {
  stop-color: var(--svg-color--f9b744, #F9B744);
}

.tb-pvwb4y {
  d: path("M11.702 17.664c.036.008.047.051.025.08a.576.576 0 1 0 1.044.33a.7.7 0 0 0-.095-.317c-.058-.098-.166-.285-.33-.426c-.222-.192-.535-.311-.986-.286c-.188.01-.37.075-.532.151a5 5 0 0 0-.483.275l-.12.075c-.274.174-.508.323-.723.391c-.26.083-.517.102-.71.037c-.018-.006-.022-.03-.008-.044a.576.576 0 1 0-.977-.408c.007.558.436.9.794 1.021c.362.122.76.069 1.083-.034c.295-.094.604-.29.868-.459l.112-.071a4 4 0 0 1 .42-.24a.9.9 0 0 1 .309-.095q.189-.009.31.02");
}

.teiod1bfq {
  stop-color: var(--svg-color--382022, #382022);
}

.u_vueng6g {
  fill: var(--svg-color--2c2630, #2C2630);
  d: path("M14.426 20.405c-.008-.036-.052-.046-.08-.025a.576.576 0 1 1-.342-1.04c.1 0 .23.041.318.092c.1.056.287.163.43.326c.194.22.317.531.297.982c-.008.188-.07.37-.146.534s-.174.33-.269.486l-.074.12c-.171.277-.317.512-.383.728c-.08.261-.096.517-.03.71c.007.018.031.022.045.007a.575.575 0 0 1 .995.396a.576.576 0 0 1-.576.576c-.558 0-.906-.425-1.03-.782c-.125-.36-.077-.758.022-1.083c.091-.296.284-.607.45-.873l.07-.113c.094-.153.176-.293.235-.422a.9.9 0 0 0 .092-.31a1.1 1.1 0 0 0-.024-.31");
}

.u7d_5ybfg {
  stop-color: var(--svg-color--48354f, #48354F);
}

.ul2smacci {
  stop-color: var(--svg-color--6f5f7b, #6F5F7B);
  stop-opacity: 0;
}

.up5zi985n {
  stop-color: var(--svg-color--b08378, #B08378);
}

.upspb_5gk {
  stop-color: var(--svg-color--df935d, #DF935D);
}

.v7r5qej8k {
  stop-color: var(--svg-color--68454e, #68454E);
}

.v8mlxjbcn {
  stop-color: var(--svg-color--a0736c, #A0736C);
}

.vfw7wibex {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M6.612 23.07a.5.5 0 0 1 .754-.05l1.765 1.786a.5.5 0 0 1-.061.756l-3.138 2.291a.4.4 0 0 1-.518-.04L4.3 26.7a.4.4 0 0 1-.036-.524z");
}

.vjg0vy6ru {
  stop-color: var(--svg-color--68454e, #68454E);
  stop-opacity: 0;
}

.w_haij-xw {
  stop-color: var(--svg-color--484138, #484138);
}

.w267ym0pr {
  stop-color: var(--svg-color--4a2c2f, #4A2C2F);
}

.w2mohub-r {
  stop-color: var(--svg-color--4e3262, #4E3262);
}

.wm5dwv3sm {
  cx: 27.882px;
  cy: 7.583px;
  r: 0.66px;
}

.wv6fp90wj {
  stop-color: var(--svg-color--413e44, #413E44);
}

.wy09p1bjj {
  stop-color: var(--svg-color--7d5251, #7D5251);
  stop-opacity: 0;
}

.x5z9dtbxc {
  stop-color: var(--svg-color--a6786f, #A6786F);
  stop-opacity: 0;
}

.x90qjmfpc {
  stop-color: var(--svg-color--83595b, #83595B);
}

.xaxqf_btu {
  stop-color: var(--svg-color--533235, #533235);
  stop-opacity: 0.81;
}

.xg0n-aciq {
  stop-color: var(--svg-color--bd8f85, #BD8F85);
}

.xn1-q8bch {
  stop-color: var(--svg-color--37234a, #37234A);
}

.xor-r7znr {
  d: path("M14.426 20.405c-.008-.036-.052-.046-.08-.025a.576.576 0 1 1-.342-1.04c.1 0 .23.041.318.092c.1.056.287.163.43.326c.194.22.317.531.297.982c-.008.188-.07.37-.146.534s-.174.33-.269.486l-.074.12c-.171.277-.317.512-.383.728c-.08.261-.096.517-.03.71c.007.018.031.022.045.007a.575.575 0 0 1 .995.396a.576.576 0 0 1-.576.576c-.558 0-.906-.425-1.03-.782c-.125-.36-.077-.758.022-1.083c.091-.296.284-.607.45-.873l.07-.113c.094-.153.176-.293.235-.422a.9.9 0 0 0 .092-.31a1.1 1.1 0 0 0-.024-.31");
}

.xu2ww1b_p {
  stop-color: var(--svg-color--523045, #523045);
}

.yr3hmpb_j {
  d: path("m24.93 5.329l1.71 1.695l-7.878 8.729a.75.75 0 0 1-1.078.036l-1.455-1.407a.75.75 0 0 1 .014-1.092z");
}

.yu1p-m-2u {
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M14.438 9.88a3.25 3.25 0 0 1 4.596-.041l3.12 3.064a3.25 3.25 0 0 1 .043 4.596l-2.774 2.825a.4.4 0 0 1-.566.005l-.285-.28A1.944 1.944 0 0 0 16.1 23.03h-.007l.697.685c.296.29.3.765.01 1.06l-3.35 3.412a4.75 4.75 0 0 1-6.717.061L3.91 25.476a4.75 4.75 0 0 1-.062-6.717l3.35-3.412a.75.75 0 0 1 1.06-.01l.738.725l.002-.005a1.946 1.946 0 0 0 2.955-2.507l-.285-.28a.4.4 0 0 1-.005-.566z");
}

.zjv1z1bua {
  stop-color: var(--svg-color--a0736c, #A0736C);
  stop-opacity: 0;
}

.zw__is7tg {
  stop-color: var(--svg-color--4f3243, #4F3243);
}

</style>
