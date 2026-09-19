<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iw2D6Ed)" transform="rotate(26.961 19.37 13.548)" class="r0vw11bdr"/><g filter="url(#i3WHNUb)"><path class="gtyh6ggoj"/></g><circle fill="url(#ijnR7Ic)" class="w7fgfxdxb"/><circle fill="url(#iH0M0wc)" class="w7fgfxdxb"/><circle fill="url(#i9ukPWC)" class="w7fgfxdxb"/><circle fill="url(#itda3Ik)" class="w7fgfxdxb"/><g filter="url(#idJxYIb)"><path fill="url(#i4ytGgd)" class="je3yqb3rl"/></g><path fill="url(#iBffckb)" class="fch2rehin"/><path fill="url(#ioR8HQe)" class="fch2rehin"/><path fill="url(#i9AuISi)" class="tauz4jbvh"/><path fill="url(#ij4y0ub)" class="tauz4jbvh"/><g filter="url(#iMmdDeb)"><path fill="url(#i0uIMHq)" class="j4jq8pbvm"/><path fill="url(#ihRPIum)" class="j4jq8pbvm"/><path fill="url(#im7GHGd)" class="j4jq8pbvm"/></g><g filter="url(#iIHH8rd)"><path fill="url(#iHtl7ke)" class="vbdc_xshv"/><path fill="url(#iNUXkRb)" class="vbdc_xshv"/></g><path fill="url(#ijS69mz)" class="qeucmabph"/><path fill="url(#itrhaDd)" class="qeucmabph"/><path fill="url(#iymlizp)" class="bst9xlugs"/><path fill="url(#iaBTS1c)" class="bst9xlugs"/><path fill="url(#izP40ze)" class="bst9xlugs"/><path fill="url(#ijP7FWd)" class="bst9xlugs"/><path class="djo2rnbvz"/><path fill="url(#ibtzeBd)" class="qi1gvpbfs"/><path fill="url(#iCsToDc)" class="qi1gvpbfs"/><path fill="url(#ilfiiOe)" class="qi1gvpbfs"/><g filter="url(#iWNIapd)"><path class="fui8_lxaa"/><path fill="url(#iVqn3qe)" class="zz7vj7ast"/><path fill="url(#iugcTDb)" class="zz7vj7ast"/><path fill="url(#iyPibSd)" class="zz7vj7ast"/></g><g filter="url(#iLHTNwe)"><path fill="url(#iW4cOSb)" class="ytgbc1bym"/><path fill="url(#io3xyxc)" class="ytgbc1bym"/></g><g filter="url(#iH7Gxxd)"><path fill="url(#iVP0mSb)" class="t5la5lbpi"/><path fill="url(#iZXSCee)" class="t5la5lbpi"/></g><g filter="url(#iAFDxUb)"><path fill="url(#iCMiEme)" clip-rule="evenodd" class="hk1tbwbom"/></g><path class="u0p11tbls"/><path fill="url(#iTLdttb)" class="e98-lbc1o"/><path fill="url(#iE6s7xc)" class="e98-lbc1o"/><path clip-rule="evenodd" class="f4rdpkxoa"/><path fill="url(#iIpjcEe)" clip-rule="evenodd" class="h94ut87sa"/><path clip-rule="evenodd" class="tgr2b-bcj"/><path fill="url(#irSpAhc)" clip-rule="evenodd" class="ujy8zd5-j"/><path clip-rule="evenodd" class="lj5xkabwf"/><path fill="url(#ikGasxc)" clip-rule="evenodd" class="ovup1jtjs"/><path clip-rule="evenodd" class="z7-d67b4g"/><path fill="url(#i5s9Gdv)" clip-rule="evenodd" class="cc59g4bjw"/><path fill="url(#im2MwFb)" clip-rule="evenodd" class="ui7cvhb9w"/><g filter="url(#iP5nyhb)"><path fill="url(#iBIEalF)" class="ae_bl0bid"/><path fill="url(#irmTzlb)" class="ae_bl0bid"/></g><path fill="url(#isBGfld)" class="ae_bl0bid"/><path fill="url(#ianMqLs)" clip-rule="evenodd" class="hk1tbwbom"/><g filter="url(#iTvtNLb)"><circle fill="url(#iVPYW9d)" class="yv4dwbb4u"/></g><g filter="url(#iPFehmc)"><circle fill="url(#iuVKltc)" class="pmnz3gbfs"/></g><g filter="url(#i1E0zac)"><circle fill="url(#iJ2vMiu)" class="srtmu2bot"/><circle fill="url(#iKD1LCb)" class="srtmu2bot"/></g><g filter="url(#iqWbfmc)"><circle class="wfdnkebtg"/><circle fill="url(#i8WOIxd)" class="le1uqea2d"/><circle fill="url(#ii7Icld)" class="le1uqea2d"/></g><g filter="url(#ibINL5d)"><path fill="url(#iWv01pd)" class="ltf8apbje"/><path fill="url(#iykZdQe)" class="ltf8apbje"/><path fill="url(#ilcZTrd)" class="ltf8apbje"/><path fill="url(#i4j1TMe)" class="ltf8apbje"/><path fill="url(#iUKP2Fb)" class="ltf8apbje"/><path fill="url(#i4UUsze)" class="ltf8apbje"/></g><g filter="url(#i7YydFc)"><path fill="url(#iEoGQYt)" class="ay6ikexen"/></g><g filter="url(#iPhrLXc)"><path class="uos7o8bqs"/><path fill="url(#ik6eMTw)" class="m1jzj8bnh"/><path fill="url(#iOaOuxb)" class="m1jzj8bnh"/><path fill="url(#i7jDemd)" class="m1jzj8bnh"/><path fill="url(#i45J5UE)" class="m1jzj8bnh"/></g><g filter="url(#i7Hq3Ub)"><path class="dmicqd2wr"/></g><g filter="url(#ifZTwwe)"><path class="ua0uxhbgx"/><path fill="url(#iWTsJee)" class="azhn6xomt"/><path fill="url(#i6Lr1xc)" class="azhn6xomt"/><path fill="url(#itumlAH)" class="azhn6xomt"/><path fill="url(#iSQtVdc)" class="azhn6xomt"/></g><path stroke="url(#ieqtqls)" class="ql_8d6ybp"/><g filter="url(#iCkBT0E)"><path class="t7fiiubot"/></g><g filter="url(#ixiiLQb)"><path class="n4kkwntyb"/></g><path class="tzy-rrl6x"/><path fill="url(#ieZrVqc)" class="uenn69vfb"/><path class="ao-ewgblu"/><g filter="url(#izNEjce)"><path class="w7u9uib5e"/><path fill="url(#ihr2TJc)" class="gjchzobrl"/></g><g filter="url(#ibNHtuU)"><path fill="url(#ivGbYFg)" class="t97qt2oly"/></g><path class="twinm15ua"/><path fill="url(#i4kTW1c)" class="b14r6kbai"/><path class="xm0zmbcso"/><g filter="url(#icAcujb)"><path fill="url(#iLTOjnd)" class="pchnx-2ll"/></g><g filter="url(#iAC1HAb)"><ellipse transform="rotate(-27.914 11.728 5.657)" class="qp3n9xbtk"/><ellipse fill="url(#iqdiY4x)" transform="rotate(-27.914 11.728 5.657)" class="edtb58d5s"/></g><g filter="url(#ichKPpd)"><path stroke="url(#iew60IV)" class="e6-ri-bkl"/></g><g filter="url(#iwhgCte)"><path stroke="url(#ivcrVVc)" class="lb-qo6bzf"/></g><g filter="url(#ipmRF4c)"><path stroke="url(#iEZqkxI)" class="ff2k9ab3p"/></g><path fill="url(#iruwEsb)" class="slj2zwboj"/><path fill="url(#i7gl65d)" class="slj2zwboj"/><path fill="url(#iLb7Xed)" class="slj2zwboj"/><path fill="url(#iPfCEAd)" class="slj2zwboj"/><g filter="url(#iEP4E0d)"><path class="rh-d7wbrr"/></g><g filter="url(#ixk3vkd)"><path class="vyejfk3nj"/><path fill="url(#ibxQN0c)" class="kjzpdrbue"/></g><defs><radialGradient id="iw2D6Ed" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.104)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="e8oc6bywr"/><stop offset="1" class="wzf1pcvjw"/></radialGradient><radialGradient id="iH0M0wc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.338 18.439)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="i9ukPWC" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.31 9.583)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="itda3Ik" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.16)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i4ytGgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.917)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="iBffckb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -4.625 2.23622 .45329 11.556 25.19)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="erkbt9b7m"/><stop offset="1" class="zb0z-k-8t"/></radialGradient><radialGradient id="ioR8HQe" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.784)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ne1zjtblh"/><stop offset="1" class="y1q425b6v"/></radialGradient><radialGradient id="i0uIMHq" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.68)" gradientUnits="userSpaceOnUse"><stop class="vhhvj2t-s"/><stop offset="1" class="so34edl-m"/></radialGradient><radialGradient id="ihRPIum" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.635)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="im7GHGd" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.929 22.587)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="ijS69mz" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.333 12.663)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="vmzfl5bmw"/><stop offset="1" class="kf-rak19e"/></radialGradient><radialGradient id="iymlizp" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.522 12.366)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="izP40ze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.19)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="ijP7FWd" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.854 17.765)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="ibtzeBd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.91)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="iCsToDc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.222)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="ilfiiOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.831)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="iVqn3qe" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 21.003)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="iugcTDb" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.73 2.305)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iyPibSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.925)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="iW4cOSb" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.453 11.58)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="xu1e5_bcz"/><stop offset="1" class="jixz69llq"/></radialGradient><radialGradient id="iCMiEme" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -1.28125 .6632 1.76315 6.712 14.003)" gradientUnits="userSpaceOnUse"><stop class="euv_c6bft"/><stop offset="1" class="zkdorr-qw"/></radialGradient><radialGradient id="iTLdttb" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.128)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="oaslx4bco"/><stop offset="1" class="y1haz_b5t"/></radialGradient><radialGradient id="iE6s7xc" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 10.013)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="zx3oawgbb"/><stop offset=".945" class="xc4yriomg"/></radialGradient><radialGradient id="iIpjcEe" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.21 7.615)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="yssh7b0_e"/><stop offset="1" class="nwlgi0bip"/></radialGradient><radialGradient id="irSpAhc" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .793 7.968)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="yssh7b0_e"/><stop offset="1" class="nwlgi0bip"/></radialGradient><radialGradient id="ikGasxc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 15.008)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="yssh7b0_e"/><stop offset="1" class="nwlgi0bip"/></radialGradient><radialGradient id="i5s9Gdv" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .69 8.409)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="yssh7b0_e"/><stop offset="1" class="nwlgi0bip"/></radialGradient><radialGradient id="im2MwFb" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.139 8.962)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="nn8u2ibbq"/><stop offset="1" class="rq9thmbis"/></radialGradient><radialGradient id="iBIEalF" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12494 8.57033 -5.82186 -2.12278 16.9 7.558)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="uqxno_b8g"/><stop offset=".81" class="d4a71bwtp"/></radialGradient><radialGradient id="irmTzlb" cx="0" cy="0" r="1" gradientTransform="rotate(-104.504 15.389 1.258)scale(8.36833 2.71135)" gradientUnits="userSpaceOnUse"><stop class="g_v4sglua"/><stop offset="1" class="o67susxgp"/></radialGradient><radialGradient id="isBGfld" cx="0" cy="0" r="1" gradientTransform="rotate(112.005 5.245 9.035)scale(4.08677 4.31955)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="ip3ktqbqy"/><stop offset="1" class="whspc9bgn"/></radialGradient><radialGradient id="ianMqLs" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.3)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="w_a146b3e"/><stop offset="1" class="w8yk26t7j"/></radialGradient><radialGradient id="iVPYW9d" cx="0" cy="0" r="1" gradientTransform="matrix(.81293 0 0 1.42264 9.892 6.017)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iKD1LCb" cx="0" cy="0" r="1" gradientTransform="matrix(.38297 -.27886 .31828 .4371 15.245 5.894)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="i8WOIxd" cx="0" cy="0" r="1" gradientTransform="rotate(-61.467 12.907 -9.46)scale(.79648 .46618)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="ii7Icld" cx="0" cy="0" r="1" gradientTransform="matrix(.12011 .1189 -.15327 .15484 15.073 6.017)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="ilcZTrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.29142 -4.46793 0 12.725 5.925)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="i4j1TMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6055 .74523 0 13.952 5.428)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iUKP2Fb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.64431 .80126 0 11.84 5.413)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="i4UUsze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3161 -.31818 .18695 -.7733 14.842 8.87)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="ik6eMTw" cx="0" cy="0" r="1" gradientTransform="matrix(.36959 -1.36964 .5079 .13705 14.878 4.115)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iOaOuxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.77183 .16305 -.08767 .9527 14.117 3.3)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="i7jDemd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .77787 -1.2047 0 12.865 2.033)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="i45J5UE" cx="0" cy="0" r="1" gradientTransform="matrix(1.42399 -1.04353 1.63487 2.23092 9.878 5.191)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iSQtVdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .09121 -.29304 0 13.017 6.761)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="ieZrVqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37533 -.597 0 13.874 5.7)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ihr2TJc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 8.29 -.502)scale(.175 .24094)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4kTW1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37535 -.59703 0 11.853 5.7)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iqdiY4x" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 8.717 -2.868)scale(.2286 .27479)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iruwEsb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.07783 14.333 3.812)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="e3m1knbgu"/><stop offset="1" class="o-iz-vbwp"/></radialGradient><radialGradient id="iPfCEAd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16797 0 0 -.11719 15.162 3.28)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jy7vazb8a"/><stop offset="1" class="oha5hfbwc"/></radialGradient><radialGradient id="ibxQN0c" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.326 -14.098)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><filter id="i3WHNUb" width="7.486" height="8.65" x="14.87" y="7.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.113725 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="idJxYIb" width="5.439" height="5.49" x="2.462" y="16.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="iMmdDeb" width="6.264" height="4.296" x="4.74" y="25.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.505882 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="iIHH8rd" width="5.105" height="3.176" x="4.74" y="26.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="iWNIapd" width="7.339" height="5.547" x="11.424" y="16.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="iLHTNwe" width="5.437" height="5.553" x="22.676" y="16.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.4 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="iH7Gxxd" width="2.689" height="5.353" x="25.224" y="16.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="iAFDxUb" width="8.098" height="6.294" x="5.657" y="8.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.129412 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.14902 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23225" result="effect2_innerShadow_3987_23225"/></filter><filter id="iP5nyhb" width="7.636" height="9.986" x="11.582" y="7.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.34902 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="iTvtNLb" width="1.747" height="1.547" x="9.892" y="5.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="iPFehmc" width="1.922" height="1.922" x="9.705" y="5.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".25"/></filter><filter id="i1E0zac" width="1.797" height="1.797" x="14.299" y="4.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="iqWbfmc" width="1.922" height="1.922" x="14.112" y="5.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".25"/></filter><filter id="ibINL5d" width="4.806" height="5.722" x="10.476" y="3.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="i7YydFc" width="3.467" height="2.921" x="12.194" y="2.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".375"/></filter><filter id="iPhrLXc" width="5.838" height="3.826" x="9.946" y="1.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="i7Hq3Ub" width="2.315" height="2.742" x="11.597" y="5.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".375"/></filter><filter id="ifZTwwe" width="1.069" height="1.442" x="12.331" y="5.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".05"/></filter><filter id="iCkBT0E" width="1.514" height="1.082" x="13.413" y="4.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="ixiiLQb" width="1.515" height="1.082" x="11.028" y="4.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><filter id="izNEjce" width=".471" height=".43" x="13.481" y="5.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".05"/></filter><filter id="ibNHtuU" width=".627" height=".638" x="13.816" y="5.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".1"/></filter><filter id="icAcujb" width=".671" height=".696" x="11.759" y="5.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".1"/></filter><filter id="iAC1HAb" width=".53" height=".433" x="11.463" y="5.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".05"/></filter><filter id="ichKPpd" width="1.156" height=".499" x="13.485" y="4.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".05"/></filter><filter id="iwhgCte" width="1.192" height=".526" x="11.066" y="4.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".05"/></filter><filter id="ipmRF4c" width=".869" height="1.453" x="10.271" y="3.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".125"/></filter><filter id="iEP4E0d" width="2.625" height="5.367" x="19.763" y="9.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23225" stdDeviation=".25"/></filter><filter id="ixk3vkd" width="3.404" height="3.248" x="18.396" y="8.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23225"/></filter><linearGradient id="ijnR7Ic" x1="4.743" x2="6.868" y1="19.066" y2="21.191" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="i9AuISi" x1="11.118" x2="8.993" y1="26.378" y2="25.628" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="ij4y0ub" x1="8.915" x2="10.134" y1="25.378" y2="25.842" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="iHtl7ke" x1="5.181" x2="9.845" y1="27.284" y2="29.816" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iNUXkRb" x1="7.524" x2="7.466" y1="28.214" y2="28.319" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="itrhaDd" x1="21.97" x2="21.54" y1="21.206" y2="20.433" gradientUnits="userSpaceOnUse"><stop class="z-3d4acgs"/><stop offset="1" class="h60oztn5g"/></linearGradient><linearGradient id="iaBTS1c" x1="23.368" x2="23.009" y1="20.487" y2="19.753" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="io3xyxc" x1="26.313" x2="26.114" y1="18.917" y2="19.003" gradientUnits="userSpaceOnUse"><stop offset=".244" class="jylqepbzd"/><stop offset="1" class="v2dwqfdba"/><stop offset="1" class="byifs8b3c"/></linearGradient><linearGradient id="iVP0mSb" x1="27.532" x2="25.439" y1="21.228" y2="16.351" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iZXSCee" x1="26.269" x2="26.38" y1="19.046" y2="19" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="iuVKltc" x1="10.666" x2="10.369" y1="6.146" y2="6.146" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iJ2vMiu" x1="15.576" x2="15.197" y1="5.511" y2="6.686" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iWv01pd" x1="14.735" x2="11.197" y1="6.197" y2="6.725" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iykZdQe" x1="10.366" x2="11.415" y1="7.446" y2="7.381" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iEoGQYt" x1="13.31" x2="17.301" y1="4.633" y2="3.259" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="iWTsJee" x1="12.465" x2="12.899" y1="6.503" y2="6.503" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="i6Lr1xc" x1="13.3" x2="12.825" y1="6.652" y2="6.645" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="itumlAH" x1="12.955" x2="12.955" y1="6.996" y2="6.731" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="ieqtqls" x1="12.385" x2="12.586" y1="7.744" y2="7.426" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="ivGbYFg" x1="14.235" x2="14.089" y1="5.726" y2="5.815" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLTOjnd" x1="12.198" x2="12.053" y1="5.726" y2="5.815" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iew60IV" x1="14.242" x2="14.047" y1="4.735" y2="4.337" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ivcrVVc" x1="11.784" x2="11.234" y1="4.676" y2="4.445" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iEZqkxI" x1="10.706" x2="10.706" y1="3.743" y2="4.741" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="i7gl65d" x1="9.716" x2="13.427" y1="3.999" y2="3.999" gradientUnits="userSpaceOnUse"><stop class="uul9_ttvm"/><stop offset="1" class="hwrqknt4x"/></linearGradient><linearGradient id="iLb7Xed" x1="13.49" x2="13.49" y1="4.343" y2="4.226" gradientUnits="userSpaceOnUse"><stop class="g0kn9gb3f"/><stop offset="1" class="nqhicrryp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-bouncing-ball-dark" /></template>
<style>
.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ae_bl0bid {
  d: path("M11.884 8.99c.147.243.5.622 1.02.622c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.ao-ewgblu {
  fill: var(--svg-color--000, #000);
  d: path("M13.639 5.893c0-.131.105-.236.236-.236a.235.235 0 0 1 .21.345h-.418a.2.2 0 0 1-.028-.109");
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.ay6ikexen {
  d: path("m14.701 3.412l-1.425.475a.485.485 0 0 0 .217.94l1.418-.189z");
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.azhn6xomt {
  d: path("m12.688 5.885l-.246.787a.25.25 0 0 0 .241.324h.364a.25.25 0 0 0 .242-.324l-.247-.787c-.052-.175-.299-.175-.354 0");
}

.b14r6kbai {
  d: path("M11.852 5.48a.413.413 0 0 0-.398.522h.798a.416.416 0 0 0-.4-.522");
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.bst9xlugs {
  d: path("m22.282 20.943l.03-.017l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.byifs8b3c {
  stop-color: var(--svg-color--ff6937, #FF6937);
  stop-opacity: 0;
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.cc59g4bjw {
  fill-rule: evenodd;
  d: path("M6.293 14.857c-.79-.083-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 0 1-.088.825");
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.d4a71bwtp {
  stop-color: var(--svg-color--3b8be5, #3B8BE5);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.djo2rnbvz {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.738c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.dmicqd2wr {
  fill: var(--svg-color--332024, #332024);
  d: path("m12.738 5.96l-.38.788c-.048.162.066.324.226.324h.341c.16 0 .273-.165.226-.324l-.23-.788c-.05-.174-.132-.174-.183 0");
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3m1knbgu {
  stop-color: var(--svg-color--e7dff1, #E7DFF1);
}

.e6-ri-bkl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.635 4.69c.199-.035.587-.025.855.184");
}

.e8oc6bywr {
  stop-color: var(--svg-color--382525, #382525);
}

.e98-lbc1o {
  d: path("M11.657 11.784c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.edtb58d5s {
  cx: 11.728px;
  cy: 5.657px;
  rx: 0.18px;
  ry: 0.091px;
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.erkbt9b7m {
  stop-color: var(--svg-color--4d3235, #4D3235);
}

.euv_c6bft {
  stop-color: var(--svg-color--442c2d, #442C2D);
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f4rdpkxoa {
  fill: var(--svg-color--483230, #483230);
  fill-rule: evenodd;
  d: path("M6.322 13.764c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fch2rehin {
  d: path("m11 20.683l.673-.75l2.336 1.86c-.07.046-.328.207-.797.476c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.977-.969c.326-.86 1.06-2.837 1.391-3.875s.81-1.646 1.008-1.82");
}

.ff2k9ab3p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.765 3.788v.416c-.003.068-.032.222-.12.287");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.ft5dv1b6b {
  fill: none;
}

.fui8_lxaa {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.534c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.g_v4sglua {
  stop-color: var(--svg-color--5290df, #5290DF);
}

.g0kn9gb3f {
  stop-color: var(--svg-color--b391c2, #B391C2);
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.gc9u7lbfl {
  stop-color: var(--svg-color--53adfa, #53ADFA);
  stop-opacity: 0;
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gjchzobrl {
  d: path("M13.845 5.568c.03.039-.032.087-.102.14c-.07.052-.122.088-.151.049c-.03-.04.003-.114.073-.166s.15-.063.18-.023");
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.gtyh6ggoj {
  fill: var(--svg-color--4b3230, #4B3230);
  d: path("M15.216 10.105q.558-.014 1.474.058c.827.065 1.691.196 2.138.531c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.148c.082.02.14.016.22.009q.044-.005.1-.008a.14.14 0 0 1 .117.06c.041.057.095.12.2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.298.121-.476c.098-.417.25-.822.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.h60oztn5g {
  stop-color: var(--svg-color--432836, #432836);
  stop-opacity: 0;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.h94ut87sa {
  fill-rule: evenodd;
  d: path("M6.322 13.764c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.hk1tbwbom {
  fill-rule: evenodd;
  d: path("m11.974 9.075l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.hwrqknt4x {
  stop-color: var(--svg-color--d3c9dc, #D3C9DC);
  stop-opacity: 0;
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.ip3ktqbqy {
  stop-color: var(--svg-color--39bbf9, #39BBF9);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j4jq8pbvm {
  d: path("m9.12 25.868l.482.612a.27.27 0 0 0 .399.058c.12-.108.433-.271.71-.058c.279.212.195.578.118.734L9.797 29.72a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.105-.425l.326-.506a.53.53 0 0 1 .643-.193c1.414.556 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.104-.165.353-.202.473-.049");
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.je3yqb3rl {
  d: path("M5.527 16.726a2.52 2.52 0 0 0 .598 1.588l.897-.892q.093.085.176.178l-.9.895a2.23 2.23 0 0 0 1.586.621q.014.123.017.25h-.065a2.48 2.48 0 0 1-1.716-.695l-.777.773l1.754 1.913q-.088.088-.185.168L5.166 19.62l-.77.765c.422.461.689 1.08.714 1.761a3 3 0 0 1-.25-.018a2.5 2.5 0 0 0-.64-1.567l-.877.872a3 3 0 0 1-.177-.178l.876-.87a2.23 2.23 0 0 0-1.556-.575a3 3 0 0 1-.024-.25l.091-.001c.638 0 1.22.245 1.666.65l.778-.773l-1.758-1.918q.088-.09.184-.17l1.751 1.911l.774-.769a2.77 2.77 0 0 1-.671-1.784q.127.005.25.02");
}

.jixz69llq {
  stop-color: var(--svg-color--3c93f1, #3C93F1);
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jy7vazb8a {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
}

.jylqepbzd {
  stop-color: var(--svg-color--4079dd, #4079DD);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kf-rak19e {
  stop-color: var(--svg-color--402531, #402531);
}

.kjzpdrbue {
  d: path("M19.324 8.383a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.265.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lb-qo6bzf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.217 4.93c.15-.133.481-.274.891-.21");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.le1uqea2d {
  cx: 15.073px;
  cy: 6.017px;
  r: 0.461px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj5xkabwf {
  fill: var(--svg-color--483230, #483230);
  fill-rule: evenodd;
  d: path("M5.125 14.676c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 1 1-.042.829a1.74 1.74 0 0 0-1.078.313");
}

.ltf8apbje {
  d: path("m10.503 5.733l.022.001s-.024-.395-.05-.667c0-.124.05-.272.15-.346l.074-.074a.49.49 0 0 0 .174-.395v-.396a.24.24 0 0 1 .2-.247c.297-.074.918-.197 1.813-.197s1.516.123 1.814.197c.1.025.199.124.199.247v.396c0 .148.074.296.174.395c.232.163.218.253.198.445c-.024.247-.05.667-.05.667h.01l-.124 1.833c-.074.82-.719 1.391-1.487 1.391h-1.487c-.794 0-1.413-.57-1.488-1.39z");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m1jzj8bnh {
  d: path("m15.098 3.016l.198.1c.348.172.547.567.473.987l-.274 1.409c-.024.145-.12.243-.265.247h-.008s.025-.42.05-.667c.02-.201-.015-.262-.2-.445a.58.58 0 0 1-.173-.395v-.396c0-.123-.1-.222-.199-.247c-.298-.074-.92-.197-1.814-.197s-1.516.123-1.814.197a.24.24 0 0 0-.199.247v.396a.49.49 0 0 1-.174.395l-.074.074c-.1.074-.15.222-.15.346c.026.272.05.667.05.667h-.022a.29.29 0 0 1-.276-.247l-.273-1.408a.95.95 0 0 1 .497-.964l.199-.099c.124-.074.248-.173.372-.272l.448-.469a.91.91 0 0 1 1.018-.148c.249.074.522.074.77 0a1.12 1.12 0 0 1 1.094.247l.373.37c.1.124.223.198.373.272");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n4kkwntyb {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.117 4.757l.002-.001l.002-.002l.005-.004l.072-.05a1.3 1.3 0 0 1 .886-.17a.247.247 0 0 1-.077.487a.82.82 0 0 0-.546.102l-.026.017l-.003.003a.247.247 0 0 1-.315-.382");
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ne1zjtblh {
  stop-color: var(--svg-color--3d2231, #3D2231);
  stop-opacity: 0;
}

.nn8u2ibbq {
  stop-color: var(--svg-color--655453, #655453);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nqhicrryp {
  stop-color: var(--svg-color--b391c2, #B391C2);
  stop-opacity: 0;
}

.nwlgi0bip {
  stop-color: var(--svg-color--3b2425, #3B2425);
  stop-opacity: 0;
}

.o-iz-vbwp {
  stop-color: var(--svg-color--b7a8c2, #B7A8C2);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o67susxgp {
  stop-color: var(--svg-color--51b1ff, #51B1FF);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.oaslx4bco {
  stop-color: var(--svg-color--311c1c, #311C1C);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oha5hfbwc {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
  stop-opacity: 0;
}

.ovup1jtjs {
  fill-rule: evenodd;
  d: path("M5.125 14.676c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 1 1-.042.829a1.74 1.74 0 0 0-1.078.313");
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.pchnx-2ll {
  d: path("M12.23 5.845c0-.134-.109-.223-.138-.25l-.133.13l.082.167z");
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmnz3gbfs {
  cx: 10.666px;
  cy: 6.017px;
  r: 0.461px;
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qeucmabph {
  d: path("M19.267 22.534c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.561 2.437-4.773 2.527");
}

.qi1gvpbfs {
  d: path("M18.292 22.738c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.ql_8d6ybp {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.64 7.44a.114.114 0 0 0-.013-.146a.12.12 0 0 0-.143-.024a1.34 1.34 0 0 1-.619.147c-.227 0-.44-.053-.618-.146a.12.12 0 0 0-.144.024a.11.11 0 0 0-.012.145m1.55 0l-.043-.028zm0 0a.93.93 0 0 1-.776.414a.93.93 0 0 1-.774-.414m0 0l.04-.028m-.04.028l.04-.028m0 0a.88.88 0 0 0 .734.392a.88.88 0 0 0 .733-.392c.04-.06-.028-.13-.091-.097a1.4 1.4 0 0 1-.642.152c-.235 0-.456-.055-.641-.152c-.064-.032-.132.04-.092.097Z");
}

.qp3n9xbtk {
  cx: 11.728px;
  cy: 5.657px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.18px;
  ry: 0.091px;
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0vw11bdr {
  width: 0.659px;
  height: 1.111px;
  x: 19.37px;
  y: 13.548px;
  rx: 0.33px;
}

.rh-d7wbrr {
  fill: var(--svg-color--614e4d, #614E4D);
  d: path("M20.857 14.248c.475-1.675-.198-3.354-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.618z");
}

.rq9thmbis {
  stop-color: var(--svg-color--482c2f, #482C2F);
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.slj2zwboj {
  d: path("M9.716 3.38a.1.1 0 0 1 .1-.1h5.925a.1.1 0 0 1 .1.1v.863a.1.1 0 0 1-.1.1H9.816a.1.1 0 0 1-.1-.1z");
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.so34edl-m {
  stop-color: var(--svg-color--3d94fa, #3D94FA);
}

.srtmu2bot {
  cx: 15.073px;
  cy: 6.017px;
  r: 0.773px;
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5la5lbpi {
  d: path("M25.282 16.633a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.062a.15.15 0 0 1-.187-.084z");
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.t7fiiubot {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m14.588 4.757l-.001-.001l-.002-.002l-.006-.004l-.071-.05a1.3 1.3 0 0 0-.886-.17a.247.247 0 1 0 .077.487a.82.82 0 0 1 .546.102l.03.02a.247.247 0 0 0 .313-.382");
}

.t97qt2oly {
  d: path("M14.244 5.839a.4.4 0 0 0-.107-.214l-.12.132l.053.105z");
}

.tauz4jbvh {
  d: path("m11.432 25.23l-.853 2.117l-1.977-.969c.176-.463.47-1.25.755-2.041z");
}

.tgr2b-bcj {
  fill: var(--svg-color--483230, #483230);
  fill-rule: evenodd;
  d: path("M5.23 14.184c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.twinm15ua {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.757 5.354a.65.65 0 0 0-.628.49a.128.128 0 0 0 .124.159h1.034c.065 0 .118-.06.105-.126a.65.65 0 0 0-.635-.523");
}

.tzy-rrl6x {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.971 5.354c.303 0 .558.209.628.49a.127.127 0 0 1-.124.158h-1.033a.107.107 0 0 1-.106-.125a.65.65 0 0 1 .635-.523");
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u0p11tbls {
  fill: var(--svg-color--6a5856, #6A5856);
  d: path("M11.657 11.784c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.ua0uxhbgx {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m12.688 5.885l-.246.787a.25.25 0 0 0 .241.324h.364a.25.25 0 0 0 .242-.324l-.247-.787c-.052-.175-.299-.175-.354 0");
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.uenn69vfb {
  d: path("M13.875 5.48a.413.413 0 0 1 .398.522h-.798a.414.414 0 0 1 .4-.522");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.ui7cvhb9w {
  fill-rule: evenodd;
  d: path("M7.132 14.012a.415.415 0 0 1 .118.575a8 8 0 0 1-.913 1.13a.415.415 0 1 1-.602-.57l.005-.005c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.ujy8zd5-j {
  fill-rule: evenodd;
  d: path("M5.23 14.184c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uos7o8bqs {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m15.098 3.016l.198.1c.348.172.547.567.473.987l-.274 1.409c-.024.145-.12.243-.265.247h-.008s.025-.42.05-.667c.02-.201-.015-.262-.2-.445a.58.58 0 0 1-.173-.395v-.396c0-.123-.1-.222-.199-.247c-.298-.074-.92-.197-1.814-.197s-1.516.123-1.814.197a.24.24 0 0 0-.199.247v.396a.49.49 0 0 1-.174.395l-.074.074c-.1.074-.15.222-.15.346c.026.272.05.667.05.667h-.022a.29.29 0 0 1-.276-.247l-.273-1.408a.95.95 0 0 1 .497-.964l.199-.099c.124-.074.248-.173.372-.272l.448-.469a.91.91 0 0 1 1.018-.148c.249.074.522.074.77 0a1.12 1.12 0 0 1 1.094.247l.373.37c.1.124.223.198.373.272");
}

.uqxno_b8g {
  stop-color: var(--svg-color--3da9fd, #3DA9FD);
}

.uul9_ttvm {
  stop-color: var(--svg-color--98919c, #98919C);
}

.v2dwqfdba {
  stop-color: var(--svg-color--4079dd, #4079DD);
  stop-opacity: 0;
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.vbdc_xshv {
  d: path("M9.794 29.497a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.vhhvj2t-s {
  stop-color: var(--svg-color--3e98f5, #3E98F5);
}

.vmzfl5bmw {
  stop-color: var(--svg-color--462928, #462928);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.vyejfk3nj {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.383a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.265.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.w_a146b3e {
  stop-color: var(--svg-color--4b3532, #4B3532);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w7fgfxdxb {
  cx: 5.18px;
  cy: 19.425px;
  r: 2.721px;
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.w7u9uib5e {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.845 5.568c.03.039-.032.087-.102.14c-.07.052-.122.088-.151.049c-.03-.04.003-.114.073-.166s.15-.063.18-.023");
}

.w8yk26t7j {
  stop-color: var(--svg-color--4b3532, #4B3532);
  stop-opacity: 0;
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wfdnkebtg {
  cx: 15.073px;
  cy: 6.017px;
  r: 0.461px;
  fill: var(--svg-color--463133, #463133);
}

.wg6epmg7n {
  stop-color: var(--svg-color--53adfa, #53ADFA);
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.whspc9bgn {
  stop-color: var(--svg-color--39bbf9, #39BBF9);
  stop-opacity: 0;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wzf1pcvjw {
  stop-color: var(--svg-color--33151d, #33151D);
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xc4yriomg {
  stop-color: var(--svg-color--533938, #533938);
}

.xm0zmbcso {
  fill: var(--svg-color--000, #000);
  d: path("M12.089 5.893a.235.235 0 0 0-.237-.236a.235.235 0 0 0-.21.345h.419a.23.23 0 0 0 .028-.109");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xu1e5_bcz {
  stop-color: var(--svg-color--3c92ef, #3C92EF);
}

.y1haz_b5t {
  stop-color: var(--svg-color--311c1c, #311C1C);
  stop-opacity: 0;
}

.y1q425b6v {
  stop-color: var(--svg-color--3d2231, #3D2231);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.yssh7b0_e {
  stop-color: var(--svg-color--3b2425, #3B2425);
}

.ytgbc1bym {
  d: path("M23.563 19.899v-.779a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.312-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.256");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yv4dwbb4u {
  cx: 10.666px;
  cy: 6.017px;
  r: 0.773px;
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z-3d4acgs {
  stop-color: var(--svg-color--432836, #432836);
}

.z7-d67b4g {
  fill: var(--svg-color--483230, #483230);
  fill-rule: evenodd;
  d: path("M6.293 14.857c-.79-.083-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 0 1-.088.825");
}

.zb0z-k-8t {
  stop-color: var(--svg-color--3f2522, #3F2522);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zkdorr-qw {
  stop-color: var(--svg-color--442229, #442229);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zx3oawgbb {
  stop-color: var(--svg-color--533938, #533938);
  stop-opacity: 0;
}

.zz7vj7ast {
  d: path("M12.962 17.534c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

</style>
