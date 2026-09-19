<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="a5n2d0brj"/><path fill="url(#iAlKUYw)" class="l4za3cbte"/><path fill="url(#itbtQzd)" class="l4za3cbte"/><path fill="url(#iZmm8Xd)" class="l4za3cbte"/><path fill="url(#iOgfppd)" class="l4za3cbte"/><path fill="url(#iGx7x8c)" class="l4za3cbte"/><path class="t9v2librs"/><path fill="url(#iYQZt5g)" class="cej917bjj"/><path fill="url(#ig9e68k)" class="cej917bjj"/><path fill="url(#iHdaBGb)" class="cej917bjj"/><g filter="url(#i3v0mYd)"><path class="ejbroxbcy"/></g><path fill="url(#i27EXBe)" class="g7gmqhncd"/><path fill="url(#izXeBwc)" class="g7gmqhncd"/><path fill="url(#i39ExJd)" class="g7gmqhncd"/><path fill="url(#iftm7Hc)" class="by194g1ei"/><path fill="url(#i43VwXd)" class="by194g1ei"/><g filter="url(#ieMKvtc)"><path fill="url(#i20eBKe)" class="dszt5lbif"/></g><path fill="url(#iOeoa4b)" class="vi7fu79ul"/><path fill="url(#im9eHqM)" class="vi7fu79ul"/><path fill="url(#i90VaHb)" class="vi7fu79ul"/><path fill="url(#i8KloTQ)" class="c9_6a4bgu"/><path fill="url(#idhUOce)" class="c9_6a4bgu"/><path fill="url(#iEpqGnc)" class="c9_6a4bgu"/><path fill="url(#iHu3LFd)" class="c9_6a4bgu"/><path fill="url(#iP6c0ue)" class="c9_6a4bgu"/><path class="c6vmhn63l"/><path fill="url(#iY8ko2d)" class="a38uvfb5u"/><path fill="url(#iOkMYsd)" class="a38uvfb5u"/><path fill="url(#i9ghADd)" class="a38uvfb5u"/><path fill="url(#ira2lKd)" class="a38uvfb5u"/><path fill="url(#iknlR1o)" class="a38uvfb5u"/><path fill="url(#ijvNHSb)" class="j-ut2xl5o"/><path fill="url(#iciiQUb)" class="j-ut2xl5o"/><g filter="url(#iH1sRgd)"><path fill="url(#i9VYgXa)" class="l-8-g4b2m"/><path fill="url(#ixKBBIe)" class="l-8-g4b2m"/><path fill="url(#iA7Jkfc)" class="l-8-g4b2m"/><path fill="url(#imEendb)" class="l-8-g4b2m"/><path fill="url(#isZI5dk)" class="l-8-g4b2m"/></g><g filter="url(#iRaEqNd)"><path fill="url(#iSfw5wd)" class="we1vuebip"/><path fill="url(#iiIvpQb)" class="we1vuebip"/><path fill="url(#isUiL6c)" class="we1vuebip"/><path fill="url(#iPij2KA)" class="we1vuebip"/></g><path fill="url(#iM1R3Fc)" class="gfuyog18w"/><path fill="url(#iRBbalc)" class="gfuyog18w"/><rect fill="url(#iz2Begd)" class="erhkeibcy"/><rect fill="url(#iWBccNc)" class="erhkeibcy"/><rect fill="url(#ih9GmGc)" class="erhkeibcy"/><rect fill="url(#iJ8MAGd)" class="erhkeibcy"/><g filter="url(#iJzVwoe)"><circle class="k7e504bil"/></g><circle fill="url(#iU1hsCv)" class="vd-u4acdq"/><circle fill="url(#i5Fhu0c)" class="vd-u4acdq"/><g filter="url(#iItt0zd)"><path fill="url(#iIrRcKb)" clip-rule="evenodd" class="fqmktcbay"/></g><rect fill="url(#is19MEd)" transform="rotate(-30 25.512 15.977)" class="tjiypub2l"/><g filter="url(#iAbikRd)"><path fill="url(#iu7H9kd)" class="a_x07cg6a"/><path fill="url(#i262erJ)" class="a_x07cg6a"/><path fill="url(#iouU5Pe)" class="a_x07cg6a"/><path fill="url(#iBAG5rd)" class="a_x07cg6a"/><path fill="url(#io15mxc)" class="a_x07cg6a"/></g><g filter="url(#icUmTuK)"><path stroke="url(#iYZYxvc)" class="dps1g2b4b"/></g><g filter="url(#iA6Puue)"><path stroke="url(#iCU2nPr)" class="wsj2g07-c"/></g><g filter="url(#ihV9qVm)"><path stroke="url(#iigSvwc)" class="bc7i0ongh"/></g><g filter="url(#if1QXVb)"><circle fill="url(#if9gQTb)" class="mh39h7hpm"/></g><g filter="url(#iK41Hne)"><circle fill="url(#i11ZMHc)" class="ep1m_ub9u"/></g><g filter="url(#iUGHQXd)"><circle class="fpaeo7bek"/><circle fill="url(#iwjZT4d)" class="n0h_63bcp"/><circle fill="url(#iRF3n9N)" class="n0h_63bcp"/></g><g filter="url(#imWBdrb)"><circle fill="url(#ioB6g2p)" class="cenqke63g"/></g><g filter="url(#isD5VJd)"><path fill="url(#iRBomQc)" class="w20yp5bum"/><path fill="url(#ibeRF7d)" class="w20yp5bum"/></g><path fill="url(#iILVuRd)" class="w20yp5bum"/><path fill="url(#iNhOhWd)" class="w20yp5bum"/><path fill="url(#ivn9Pjb)" class="w20yp5bum"/><path fill="url(#iK706Mb)" class="w20yp5bum"/><path fill="url(#i9g3oJe)" class="w20yp5bum"/><g filter="url(#iy6pgId)"><path class="kwu50z17h"/></g><g filter="url(#iVmZwlb)"><path class="w4qudxuvg"/><path fill="url(#i5wLMLb)" class="e3735f7vp"/><path fill="url(#i1Hqbkb)" class="e3735f7vp"/><path fill="url(#iPgCBUb)" class="e3735f7vp"/></g><g filter="url(#ilW3nmb)"><path fill="url(#ivl5Rsn)" class="kdvr4u58b"/></g><g filter="url(#iityX1b)"><path stroke="url(#i75PZGc)" class="h2syrhw0m"/></g><path class="tei_ukbxq"/><path class="dty2zclqi"/><path fill="url(#iyOGulJ)" class="cxpxnn5gd"/><path class="rrgrst12i"/><g filter="url(#imwGdfc)"><path class="p9_jm0xvg"/><path fill="url(#icmYJFc)" class="mijx23bkm"/></g><g filter="url(#iXFEcSd)"><path fill="url(#iE5JQae)" class="f-gl8-mln"/></g><path class="xh__ycc9a"/><path fill="url(#i18vOii)" class="l6qykxbvl"/><path class="mibx7d57r"/><g filter="url(#i1IE9nb)"><path fill="url(#iN3jgZV)" class="sjbfjtb6o"/></g><g filter="url(#iO1mxKb)"><ellipse transform="rotate(-27.914 11.99 11.986)" class="y-v21bc8n"/><ellipse fill="url(#iFbcshM)" transform="rotate(-27.914 11.99 11.986)" class="ljhgv1b3v"/></g><path fill="url(#ibKP0ab)" class="hd4jb3bqf"/><path fill="url(#iOT8O4d)" class="hd4jb3bqf"/><path fill="url(#iyzPw8d)" class="cn00uybdf"/><g filter="url(#izc2dCi)"><path fill="url(#i8gh6Fe)" class="i13oh1ffm"/></g><path fill="url(#iBfj5Pd)" class="i13oh1ffm"/><path fill="url(#ieAjMmb)" class="i13oh1ffm"/><g filter="url(#idNYYnb)"><path fill="url(#iodu1md)" class="e8-mlobfh"/></g><path fill="url(#iQFwsnd)" class="e8m6ucbjc"/><path fill="url(#iAJlZRd)" class="e8m6ucbjc"/><path fill="url(#iLKj4pc)" class="e8m6ucbjc"/><path fill="url(#iAYhuWd)" class="e8m6ucbjc"/><defs><radialGradient id="iAlKUYw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90625 -2.3125 0 6.773 21.813)" gradientUnits="userSpaceOnUse"><stop class="zy5dj18nw"/><stop offset="1" class="ol5y5gj7m"/></radialGradient><radialGradient id="itbtQzd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.646 14.441 11.476)scale(11.587 1.53635)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cj2gegbdf"/><stop offset="1" class="cw9lwsb0z"/></radialGradient><radialGradient id="iOgfppd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -2.5 0 22.836 22.156)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="j05e95eeg"/><stop offset="1" class="i7g4iz6bw"/></radialGradient><radialGradient id="iGx7x8c" cx="0" cy="0" r="1" gradientTransform="rotate(20.493 -65.416 66.252)scale(3.30276 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fchl8077b"/><stop offset="1" class="nig76no1i"/></radialGradient><radialGradient id="ig9e68k" cx="0" cy="0" r="1" gradientTransform="rotate(103.743 .522 17.985)scale(2.95973 1.64796)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="z_k8o-57c"/><stop offset="1" class="rxpl4qnie"/></radialGradient><radialGradient id="iHdaBGb" cx="0" cy="0" r="1" gradientTransform="matrix(.8422 3.48214 -1.84594 .44646 11.586 20.884)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="gi2uz_g9v"/><stop offset="1" class="qasiqcczj"/></radialGradient><radialGradient id="i27EXBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3594 4.25 0 6.367 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="kvzrrwynu"/><stop offset="1" class="nf2o-hpjm"/></radialGradient><radialGradient id="izXeBwc" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 -2.544 12.698)scale(4.44498 4.85494)" gradientUnits="userSpaceOnUse"><stop class="k1zgefb2d"/><stop offset="1" class="lg14abbip"/></radialGradient><radialGradient id="i39ExJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7344 2.803 0 7.023 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nzffxlbem"/><stop offset="1" class="pb1ehqpec"/></radialGradient><radialGradient id="iftm7Hc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45316 -3.24716 0 24.875 23.469)" gradientUnits="userSpaceOnUse"><stop class="j11nupb8y"/><stop offset="1" class="c_gtmdbzk"/></radialGradient><radialGradient id="i43VwXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.96327 -.27323 1.61732 11.6211 22.726 29.92)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="k9h8bsbwk"/><stop offset="1" class="xtl5dn5fo"/></radialGradient><radialGradient id="i20eBKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.2093 -2.72578 0 14.859 22.654)" gradientUnits="userSpaceOnUse"><stop class="fisd__bqs"/><stop offset="1" class="wss6y3b2p"/></radialGradient><radialGradient id="iOeoa4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -.95313 0 14.851 24.782)" gradientUnits="userSpaceOnUse"><stop class="op_u9g8uj"/><stop offset="1" class="asvjbc-zd"/></radialGradient><radialGradient id="i8KloTQ" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18748 2.46878 -3.8188 -6.47736 14.398 20.969)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="e9sv_2buc"/><stop offset="1" class="altutfb8x"/></radialGradient><radialGradient id="iEpqGnc" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 -1.196 14.246)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="iHu3LFd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.274 12.135 8.129)scale(.4746 3.14325)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iP6c0ue" cx="0" cy="0" r="1" gradientTransform="matrix(-.64914 .713 -1.62712 -1.4814 14.048 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iY8ko2d" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 3.20313 -4.95471 3.77041 15.586 20.469)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="o58_qgbus"/><stop offset="1" class="l9k3lrq7u"/></radialGradient><radialGradient id="i9ghADd" cx="0" cy="0" r="1" gradientTransform="rotate(75.964 -3.372 20.582)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="ira2lKd" cx="0" cy="0" r="1" gradientTransform="matrix(.31925 -.35118 2.32584 2.11435 15.467 22.576)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iknlR1o" cx="0" cy="0" r="1" gradientTransform="matrix(.64914 .71299 -1.62712 1.4814 15.7 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="ijvNHSb" cx="0" cy="0" r="1" gradientTransform="matrix(3.6691 1.75022 -1.69627 3.55598 13.456 19.388)" gradientUnits="userSpaceOnUse"><stop class="bnrxbfbky"/><stop offset=".433" class="o6jqa8bjh"/><stop offset=".66" class="jglb--p4a"/><stop offset="1" class="ich4l_bvh"/></radialGradient><radialGradient id="iciiQUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7579 -2.58664 0 14.875 19.84)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="nfkpkr9uv"/><stop offset="1" class="ialim-79v"/></radialGradient><radialGradient id="iA7Jkfc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.011 8.397 8.282)scale(8.72259 3.48034)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="mw9gk7bly"/><stop offset="1" class="dv70acbut"/></radialGradient><radialGradient id="isZI5dk" cx="0" cy="0" r="1" gradientTransform="rotate(33.19 -29.317 21.252)scale(2.48324 .7466)" gradientUnits="userSpaceOnUse"><stop class="foejprbbc"/><stop offset="1" class="kpssiabxl"/></radialGradient><radialGradient id="isUiL6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.20501 -2.78125 1.73626 2.0008 17.148 23.25)" gradientUnits="userSpaceOnUse"><stop class="f87czphzs"/><stop offset="1" class="pwa97nbfq"/></radialGradient><radialGradient id="iPij2KA" cx="0" cy="0" r="1" gradientTransform="rotate(149.744 8.39 12.982)scale(1.73656 .44089)" gradientUnits="userSpaceOnUse"><stop class="mx64gfpes"/><stop offset="1" class="xqc8z1bhj"/></radialGradient><radialGradient id="iM1R3Fc" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.76 15.925)scale(2.55551 2.50931)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="j1n1ygxtd"/><stop offset="1" class="mdv9qbyfi"/></radialGradient><radialGradient id="iRBbalc" cx="0" cy="0" r="1" gradientTransform="matrix(.8321 -.63357 .48552 .63766 28.001 22.854)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="jt362mrmb"/><stop offset="1" class="yfkzyxbts"/></radialGradient><radialGradient id="ih9GmGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38281 .60155 -.43729 -1.00521 25.539 20.227)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bslse1b3i"/><stop offset="1" class="t11-a9gub"/></radialGradient><radialGradient id="iJ8MAGd" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .42875 26.523 21.266)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="bc2ld5biv"/><stop offset="1" class="a6yy9-nlq"/></radialGradient><radialGradient id="iU1hsCv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.91576 4.34721 -4.19506 -3.7787 28.15 15.25)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="ig92uxq3u"/><stop offset="1" class="thvbr9biq"/></radialGradient><radialGradient id="i5Fhu0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.157 -2.3893 4.6402 4.18907 23.372 19.73)" gradientUnits="userSpaceOnUse"><stop class="k5i52n_gm"/><stop offset="1" class="vsqgrkwbb"/></radialGradient><radialGradient id="is19MEd" cx="0" cy="0" r="1" gradientTransform="matrix(.07693 -2.02477 3.711 .141 26.096 18.118)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="lcqew7b7f"/><stop offset="1" class="e6z7sjb6l"/></radialGradient><radialGradient id="i262erJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8752 -1.60814 0 26.025 24.796)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iouU5Pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93815 -1.72383 0 26.025 26.21)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iBAG5rd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78463 -1.44175 0 26.025 27.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="io15mxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87265 -2.05091 0 26.025 29.05)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="if9gQTb" cx="0" cy="0" r="1" gradientTransform="rotate(83.775 -2.496 11.44)scale(1.9296)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="gsf_3mapv"/><stop offset="1" class="k-34bbczy"/></radialGradient><radialGradient id="i11ZMHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.56385 0 0 -1.00365 8.997 12.72)" gradientUnits="userSpaceOnUse"><stop class="lk3ugac1n"/><stop offset="1" class="im-nu1b_s"/></radialGradient><radialGradient id="iwjZT4d" cx="0" cy="0" r="1" gradientTransform="rotate(150.173 9.425 8.78)scale(1.41063 1.31947)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="tw93opnhd"/><stop offset="1" class="ybx8c08_o"/></radialGradient><radialGradient id="iRF3n9N" cx="0" cy="0" r="1" gradientTransform="matrix(1.2564 -.84872 .734 1.08658 20.68 14.598)" gradientUnits="userSpaceOnUse"><stop class="ojl7ynbtd"/><stop offset="1" class="ne453misf"/></radialGradient><radialGradient id="ioB6g2p" cx="0" cy="0" r="1" gradientTransform="matrix(.93042 0 0 .9847 20.5 12.761)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="mk8ahybcp"/><stop offset="1" class="khpardbxn"/></radialGradient><radialGradient id="iRBomQc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09082 4.20865 -6.92602 -8.37778 19.115 14.801)" gradientUnits="userSpaceOnUse"><stop class="ycvscybwl"/><stop offset="1" class="tiyakobla"/></radialGradient><radialGradient id="ibeRF7d" cx="0" cy="0" r="1" gradientTransform="rotate(25.039 -32.4 39.347)scale(3.53387 3.49856)" gradientUnits="userSpaceOnUse"><stop class="df4s9hbin"/><stop offset="1" class="u2w_l1bed"/></radialGradient><radialGradient id="iILVuRd" cx="0" cy="0" r="1" gradientTransform="scale(9.08038 7.71703)rotate(90 .02 1.616)" gradientUnits="userSpaceOnUse"><stop offset=".697" class="d8ho5ibbx"/><stop offset="1" class="chh2vjbzz"/></radialGradient><radialGradient id="iNhOhWd" cx="0" cy="0" r="1" gradientTransform="rotate(157.172 7.104 6.336)scale(9.55811 5.00232)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="mndtykbcd"/><stop offset="1" class="ub4yxzbiu"/></radialGradient><radialGradient id="ivn9Pjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.79462 -1.91111 0 20.804 11.15)" gradientUnits="userSpaceOnUse"><stop class="xmwni0bou"/><stop offset="1" class="w1a3e9bkq"/></radialGradient><radialGradient id="iK706Mb" cx="0" cy="0" r="1" gradientTransform="rotate(141.373 3.952 8.06)scale(2.47951 1.88304)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="qlmxj_uev"/><stop offset="1" class="cvjtgdb2q"/></radialGradient><radialGradient id="i9g3oJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42608 -2.01711 0 17.577 12.273)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="n0g6o9q3d"/><stop offset="1" class="pxopwiwar"/></radialGradient><radialGradient id="i5wLMLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.87264 0 0 -.32232 15.421 14.504)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="kldze1b9y"/><stop offset="1" class="j554sh0mc"/></radialGradient><radialGradient id="i1Hqbkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58672 2.45524 0 14.811 15.182)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gho_wacxp"/><stop offset="1" class="n_u2l52pq"/></radialGradient><radialGradient id="i75PZGc" cx="0" cy="0" r="1" gradientTransform="rotate(-57.512 22.14 -3.79)scale(.81257 2.98595)" gradientUnits="userSpaceOnUse"><stop class="vn1l7s8zo"/><stop offset=".615" class="r4yjzls_o"/></radialGradient><radialGradient id="iyOGulJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03773 -1.22791 0 17.314 12.479)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="mrtz5_gxn"/><stop offset="1" class="um4p__bni"/></radialGradient><radialGradient id="icmYJFc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 11.512 1.92)scale(.43456 .59827)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i18vOii" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03779 -1.22797 0 12.301 12.479)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="mrtz5_gxn"/><stop offset="1" class="um4p__bni"/></radialGradient><radialGradient id="iFbcshM" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.064 .28)scale(.56764 .68234)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOT8O4d" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 .74219 -.13122 -.03315 21.407 11.326)" gradientUnits="userSpaceOnUse"><stop class="ipq9-xbsh"/><stop offset="1" class="rubo83wtt"/></radialGradient><radialGradient id="iyzPw8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.77386 .0032 -.00524 -1.2664 8.844 11.57)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="tro7l0cbh"/><stop offset=".687" class="ub7ncfbla"/></radialGradient><radialGradient id="i8gh6Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90342 3.34379 -2.24881 -4.64278 20.958 3.094)" gradientUnits="userSpaceOnUse"><stop class="ld92_g1my"/><stop offset="1" class="dvhbibcqh"/></radialGradient><radialGradient id="iBfj5Pd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -.4375 1.025 7.6143 8.492 6.125)" gradientUnits="userSpaceOnUse"><stop class="t0ozsbnai"/><stop offset="1" class="iqoe-4pvq"/></radialGradient><radialGradient id="ieAjMmb" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.89873 -3.57306 1.35256 11.648 2.078)" gradientUnits="userSpaceOnUse"><stop class="uvo3wxbsr"/><stop offset="1" class="vjaj-kz7h"/></radialGradient><radialGradient id="iQFwsnd" cx="0" cy="0" r="1" gradientTransform="rotate(179.635 9.633 3.609)scale(4.90635 4.18652)" gradientUnits="userSpaceOnUse"><stop class="c77y5fbir"/><stop offset="1" class="a4oc_-5ds"/></radialGradient><linearGradient id="iZmm8Xd" x1="6.988" x2="7.195" y1="29.406" y2="29.406" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x84cwhbna"/><stop offset="1" class="fk1gregde"/></linearGradient><linearGradient id="iYQZt5g" x1="16.932" x2="14.847" y1="28.545" y2="28.12" gradientUnits="userSpaceOnUse"><stop offset=".045" class="o8gobxb3n"/><stop offset="1" class="q-14d3boa"/></linearGradient><linearGradient id="im9eHqM" x1="13.726" x2="14.226" y1="26.766" y2="26.813" gradientUnits="userSpaceOnUse"><stop class="i78i3vbiy"/><stop offset="1" class="la8vvmbhh"/></linearGradient><linearGradient id="i90VaHb" x1="16.414" x2="15.153" y1="29.07" y2="29.122" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bt46k-bry"/><stop offset="1" class="d-k16gi6m"/></linearGradient><linearGradient id="idhUOce" x1="11.675" x2="12.612" y1="21.649" y2="21.469" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="iOkMYsd" x1="18.074" x2="17.137" y1="21.649" y2="21.469" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="i9VYgXa" x1="12.219" x2="9.392" y1="26.169" y2="26.806" gradientUnits="userSpaceOnUse"><stop class="rcslxcb9f"/><stop offset="1" class="arpepeb0z"/></linearGradient><linearGradient id="ixKBBIe" x1="9.392" x2="11.085" y1="16.976" y2="22.375" gradientUnits="userSpaceOnUse"><stop class="oh_d1sh7z"/><stop offset="1" class="x2herp8_d"/></linearGradient><linearGradient id="imEendb" x1="12.268" x2="12.268" y1="29.922" y2="24.699" gradientUnits="userSpaceOnUse"><stop class="nw6o4wclj"/><stop offset="1" class="q8ppcjbus"/></linearGradient><linearGradient id="iSfw5wd" x1="18.023" x2="21.304" y1="29.125" y2="16.976" gradientUnits="userSpaceOnUse"><stop offset=".452" class="t-s_cxb3y"/><stop offset="1" class="zpb-61ddc"/></linearGradient><linearGradient id="iiIvpQb" x1="17" x2="17.152" y1="26.539" y2="26.57" gradientUnits="userSpaceOnUse"><stop class="njrd_tayg"/><stop offset="1" class="d1xnqxb5m"/></linearGradient><linearGradient id="iz2Begd" x1="26.981" x2="24.992" y1="21.782" y2="21.782" gradientUnits="userSpaceOnUse"><stop class="x26s0_r_n"/><stop offset="1" class="x__1z6aoh"/></linearGradient><linearGradient id="iWBccNc" x1="26.336" x2="26.336" y1="25.469" y2="22.563" gradientUnits="userSpaceOnUse"><stop class="zuvzebcmo"/><stop offset="1" class="fjaxvnbiy"/></linearGradient><linearGradient id="iIrRcKb" x1="28.179" x2="23.367" y1="14.344" y2="19.782" gradientUnits="userSpaceOnUse"><stop class="tnc_xbdtt"/><stop offset="1" class="n3pyssb7u"/></linearGradient><linearGradient id="iu7H9kd" x1="27.914" x2="23.547" y1="27.807" y2="27.891" gradientUnits="userSpaceOnUse"><stop offset=".146" class="yrzi8mt9l"/><stop offset="1" class="rncji_bbq"/></linearGradient><linearGradient id="iYZYxvc" x1="23.699" x2="25.565" y1="25.61" y2="25.61" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iCU2nPr" x1="23.614" x2="25.48" y1="27.033" y2="27.033" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iigSvwc" x1="23.699" x2="25.565" y1="28.458" y2="28.458" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iPgCBUb" x1="15.786" x2="15.049" y1="13.838" y2="13.993" gradientUnits="userSpaceOnUse"><stop class="yjxmx4bbz"/><stop offset="1" class="du-h41r7a"/></linearGradient><linearGradient id="ivl5Rsn" x1="14.811" x2="14.949" y1="12.039" y2="13.58" gradientUnits="userSpaceOnUse"><stop class="v2sibmb_y"/><stop offset="1" class="yv_7k4c8b"/></linearGradient><linearGradient id="iE5JQae" x1="18.208" x2="17.848" y1="12.158" y2="12.38" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iN3jgZV" x1="13.156" x2="12.795" y1="12.158" y2="12.38" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibKP0ab" x1="21.212" x2="20.677" y1="11.586" y2="11.609" gradientUnits="userSpaceOnUse"><stop class="qxybu3s-p"/><stop offset="1" class="zo9leke9p"/></linearGradient><linearGradient id="iodu1md" x1="23.304" x2="6.367" y1="9.438" y2="9.753" gradientUnits="userSpaceOnUse"><stop class="damj_nbgh"/><stop offset=".519" class="bpzzcwljp"/><stop offset=".98" class="fpxhxfble"/></linearGradient><linearGradient id="iAJlZRd" x1="8.554" x2="9.992" y1="6.877" y2="7.063" gradientUnits="userSpaceOnUse"><stop class="s_d1fy10v"/><stop offset="1" class="gn4fmf85p"/></linearGradient><linearGradient id="iLKj4pc" x1="15.461" x2="15.461" y1="7.93" y2="7.727" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="iAYhuWd" x1="15.507" x2="15.507" y1="5.848" y2="5.985" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><filter id="i3v0mYd" width="7.346" height="5.139" x="11.201" y="19.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".25"/></filter><filter id="ieMKvtc" width="3.106" height="2.966" x="13.406" y="21.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.133333 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2761"/></filter><filter id="iH1sRgd" width="8.299" height="13.046" x="5.292" y="16.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.396078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2761"/></filter><filter id="iRaEqNd" width="8.299" height="13.046" x="16.153" y="16.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2761"/></filter><filter id="iJzVwoe" width="6.656" height="6.656" x="22.367" y="13.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".125"/></filter><filter id="iItt0zd" width="7.206" height="7.206" x="22.067" y="13.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.27451 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2761"/></filter><filter id="iAbikRd" width="5.277" height="6.052" x="23.131" y="23.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.486275 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2761"/></filter><filter id="icUmTuK" width="2.262" height=".3" x="23.549" y="25.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".05"/></filter><filter id="iA6Puue" width="2.262" height=".3" x="23.464" y="26.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".05"/></filter><filter id="ihV9qVm" width="2.262" height=".3" x="23.549" y="28.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".05"/></filter><filter id="if1QXVb" width="3.936" height="3.836" x="7.437" y="10.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.6 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2761"/></filter><filter id="iK41Hne" width="2.786" height="2.786" x="7.962" y="11.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".125"/></filter><filter id="iUGHQXd" width="3.886" height="3.886" x="18.318" y="10.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.72549 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2761"/></filter><filter id="imWBdrb" width="2.786" height="2.786" x="18.893" y="11.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".125"/></filter><filter id="isD5VJd" width="12.519" height="13.82" x="8.884" y="6.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".8"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.611765 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2761"/></filter><filter id="iy6pgId" width="3.022" height="4.081" x="13.025" y="11.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".25"/></filter><filter id="iVmZwlb" width="2.656" height="3.581" x="13.483" y="12.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.482353 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2761"/><feGaussianBlur result="effect2_foregroundBlur_4002_2761" stdDeviation=".125"/></filter><filter id="ilW3nmb" width="2.656" height="3.581" x="13.483" y="11.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".125"/></filter><filter id="iityX1b" width="4.097" height="1.632" x="12.762" y="15.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".05"/></filter><filter id="imwGdfc" width=".874" height=".77" x="16.486" y="11.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".05"/></filter><filter id="iXFEcSd" width=".964" height=".99" x="17.466" y="11.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".1"/></filter><filter id="i1IE9nb" width="1.074" height="1.135" x="12.362" y="11.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".1"/></filter><filter id="iO1mxKb" width="1.019" height=".78" x="11.48" y="11.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2761" stdDeviation=".05"/></filter><filter id="izc2dCi" width="12.369" height="3.947" x="8.798" y="2.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2761"/></filter><filter id="idNYYnb" width="19.912" height="4.003" x="4.916" y="7.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.447059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2761"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.372549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2761" result="effect2_innerShadow_4002_2761"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-detective-medium-light" /></template>
<style>
.a_x07cg6a {
  d: path("M23.132 24.82c0-.439.355-.8.793-.8h3.023c.724 0 1.31.587 1.31 1.31v3.5c0 .603-.488 1.092-1.091 1.092h-3.242a.798.798 0 0 1-.349-1.516a.802.802 0 0 1 0-1.435a.802.802 0 0 1 0-1.434a.8.8 0 0 1-.445-.718");
}

.a38uvfb5u {
  d: path("m17.77 22.746l.814-3.777h-1.852l-1.867 2.484v.438l1.96 1.781c.097.084.327.214.477.07c.15-.143.35-.484.467-.996");
}

.a4oc_-5ds {
  stop-color: var(--svg-color--372153, #372153);
}

.a5n2d0brj {
  fill: var(--svg-color--655d95, #655D95);
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.41-12.142-11.41S3.125 23.555 2.727 29.923");
}

.a6yy9-nlq {
  stop-color: var(--svg-color--46446d, #46446D);
  stop-opacity: 0;
}

.altutfb8x {
  stop-color: var(--svg-color--ab9ca0, #AB9CA0);
}

.arpepeb0z {
  stop-color: var(--svg-color--665c8a, #665C8A);
}

.asvjbc-zd {
  stop-color: var(--svg-color--b4366c, #B4366C);
}

.bc2ld5biv {
  stop-color: var(--svg-color--46446d, #46446D);
}

.bc7i0ongh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.7 28.38h1.96");
}

.bcp6zybsw {
  stop-color: var(--svg-color--7c707d, #7C707D);
}

.bnrxbfbky {
  stop-color: var(--svg-color--a7736c, #A7736C);
}

.bpzzcwljp {
  stop-color: var(--svg-color--5b537a, #5B537A);
}

.bslse1b3i {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
}

.bt46k-bry {
  stop-color: var(--svg-color--810937, #810937);
}

.by194g1ei {
  d: path("M22.727 29.922h4.296a12.16 12.16 0 0 0-4.296-8.538z");
}

.c_gtmdbzk {
  stop-color: var(--svg-color--5e5775, #5E5775);
}

.c6vmhn63l {
  fill: var(--svg-color--f7a936, #F7A936);
  d: path("m17.77 22.746l.814-3.777h-1.852l-1.867 2.484v.438l1.96 1.781c.097.084.327.214.477.07c.15-.143.35-.484.467-.996");
}

.c77y5fbir {
  stop-color: var(--svg-color--574069, #574069);
}

.c9_6a4bgu {
  d: path("m11.972 22.727l-.806-3.758h1.851l1.867 2.488v.434l-1.96 1.781c-.097.084-.327.214-.477.07c-.15-.143-.357-.504-.475-1.015");
}

.cej917bjj {
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.293l-2.281 10.863z");
}

.cenqke63g {
  cx: 20.286px;
  cy: 12.681px;
  r: 1.143px;
}

.chh2vjbzz {
  stop-color: var(--svg-color--a26b74, #A26B74);
}

.cj2gegbdf {
  stop-color: var(--svg-color--4f4376, #4F4376);
}

.cjc9cqblk {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn00uybdf {
  d: path("m8.07 10.762l.198.814c.058.35.357.6.701.623c-.014-.226-.046-.63-.058-.978l-.017-.459z");
}

.cvjtgdb2q {
  stop-color: var(--svg-color--a77262, #A77262);
  stop-opacity: 0;
}

.cw9lwsb0z {
  stop-color: var(--svg-color--4f4376, #4F4376);
  stop-opacity: 0;
}

.cxpxnn5gd {
  d: path("M17.317 11.548a1.025 1.025 0 0 1 .988 1.295h-1.98a1.03 1.03 0 0 1 .992-1.296");
}

.d-k16gi6m {
  stop-color: var(--svg-color--b6376a, #B6376A);
  stop-opacity: 0;
}

.d1xnqxb5m {
  stop-color: var(--svg-color--573a60, #573A60);
  stop-opacity: 0;
}

.d8ho5ibbx {
  stop-color: var(--svg-color--c08285, #C08285);
  stop-opacity: 0;
}

.damj_nbgh {
  stop-color: var(--svg-color--7577a1, #7577A1);
}

.df4s9hbin {
  stop-color: var(--svg-color--c08385, #C08385);
}

.dps1g2b4b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.7 25.532h1.96");
}

.dszt5lbif {
  d: path("m14.098 24.35l-.692-1.334l1.453-1.352l1.453 1.352l-.662 1.33a.15.15 0 0 1-.134.084h-1.285a.15.15 0 0 1-.133-.08");
}

.dty2zclqi {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.555 11.236c.75 0 1.384.517 1.556 1.216a.315.315 0 0 1-.308.391h-2.562a.264.264 0 0 1-.261-.312a1.606 1.606 0 0 1 1.575-1.295");
}

.du-h41r7a {
  stop-color: var(--svg-color--cd9d87, #CD9D87);
  stop-opacity: 0;
}

.dv70acbut {
  stop-color: var(--svg-color--534971, #534971);
  stop-opacity: 0;
}

.dvhbibcqh {
  stop-color: var(--svg-color--625783, #625783);
}

.e3735f7vp {
  d: path("m14.372 12.622l-.61 1.952a.62.62 0 0 0 .597.804h.904a.62.62 0 0 0 .598-.804l-.61-1.952c-.132-.433-.742-.433-.88 0");
}

.e6z7sjb6l {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
}

.e8-mlobfh {
  d: path("M6.386 7.88c-.26-.016-.991.034-1.316.359c-.358.357-.055 1.073.508 1.652c.539.555 2.335 1.738 5.18 1.738h8.167c2.873 0 4.689-1.183 5.234-1.738c.568-.579.874-1.295.513-1.652c-.328-.325-1.067-.375-1.33-.36z");
}

.e8m6ucbjc {
  d: path("M8.126 7.748a.1.1 0 0 0 .095.131h13.287a.1.1 0 0 0 .094-.133l-.192-.559l-.429-1.245a.1.1 0 0 0-.094-.067H8.829a.1.1 0 0 0-.095.068c-.19.553-.38 1.12-.531 1.574z");
}

.e9sv_2buc {
  stop-color: var(--svg-color--dbc8d7, #DBC8D7);
}

.ejbroxbcy {
  fill: var(--svg-color--927d95, #927D95);
  d: path("m11.701 19.668l.69 3.215c.1.438.278.746.407.869s.325.01.407-.06l1.67-1.517l1.669 1.517c.082.07.28.183.408.06s.299-.415.4-.853l.696-3.231h-1.584l-1.59 2.116l-1.588-2.116z");
}

.ep1m_ub9u {
  cx: 9.356px;
  cy: 12.681px;
  r: 1.143px;
}

.erhkeibcy {
  width: 2.572px;
  height: 5.438px;
  x: 24.409px;
  y: 20.227px;
  rx: 1.286px;
}

.f-gl8-mln {
  d: path("M18.23 12.438a.97.97 0 0 0-.266-.532l-.298.328l.134.262z");
}

.f87czphzs {
  stop-color: var(--svg-color--5b4361, #5B4361);
}

.fchl8077b {
  stop-color: var(--svg-color--4e4270, #4E4270);
}

.fisd__bqs {
  stop-color: var(--svg-color--ce3657, #CE3657);
}

.fjaxvnbiy {
  stop-color: var(--svg-color--4c3156, #4C3156);
  stop-opacity: 0;
}

.fk1gregde {
  stop-color: var(--svg-color--57497f, #57497F);
  stop-opacity: 0;
}

.foejprbbc {
  stop-color: var(--svg-color--767290, #767290);
}

.fpaeo7bek {
  cx: 20.286px;
  cy: 12.68px;
  r: 1.918px;
  fill: var(--svg-color--d5a289, #D5A289);
}

.fpxhxfble {
  stop-color: var(--svg-color--5c4b6c, #5C4B6C);
}

.fqmktcbay {
  fill-rule: evenodd;
  d: path("M25.695 20.672a3.578 3.578 0 1 0 0-7.156a3.578 3.578 0 0 0 0 7.156m0-.594a2.984 2.984 0 1 0 0-5.968a2.984 2.984 0 0 0 0 5.968");
}

.ft5dv1b6b {
  fill: none;
}

.g7gmqhncd {
  d: path("M7.023 29.922H2.727a12.16 12.16 0 0 1 4.296-8.538z");
}

.gfuyog18w {
  d: path("M27.203 22.328c.58 0 1.055.475 1.055 1.056v2.418h-2.111v-2.418c.01-.58.475-1.056 1.056-1.056");
}

.gho_wacxp {
  stop-color: var(--svg-color--c48986, #C48986);
}

.gi2uz_g9v {
  stop-color: var(--svg-color--514c59, #514C59);
}

.gn4fmf85p {
  stop-color: var(--svg-color--3e3058, #3E3058);
  stop-opacity: 0;
}

.gsf_3mapv {
  stop-color: var(--svg-color--bc7c6e, #BC7C6E);
}

.h2syrhw0m {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.81 16.4c-.582 0-1.13-.137-1.59-.377c-.158-.08-.327.097-.228.24a2.17 2.17 0 0 0 1.819.971c.764 0 1.434-.388 1.819-.971c.099-.149-.07-.32-.228-.24a3.4 3.4 0 0 1-1.591.377Z");
}

.hd4jb3bqf {
  d: path("m20.76 10.762l-.02.389c-.018.345-.04.777-.063 1.1c.358-.01.597-.253.657-.614l.23-.875z");
}

.i13oh1ffm {
  d: path("M8.803 5.743a.1.1 0 0 0 .095.132h11.92a.1.1 0 0 0 .094-.132a87 87 0 0 0-.639-1.79c-.469-1.25-1.637-1.875-2.297-1.875c-.735-.016-1.259.318-1.65.567l-.194.121c-.578.344-.808.398-1.277.398c-.371 0-.762-.148-1.184-.367q-.11-.058-.247-.142c-.436-.26-1.078-.642-1.905-.526c-.956.135-1.66.93-2.097 1.946a29 29 0 0 0-.619 1.668");
}

.i78i3vbiy {
  stop-color: var(--svg-color--ad254b, #AD254B);
}

.i7g4iz6bw {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
  stop-opacity: 0;
}

.ialim-79v {
  stop-color: var(--svg-color--ac7074, #AC7074);
  stop-opacity: 0;
}

.ich4l_bvh {
  stop-color: var(--svg-color--cb9e8a, #CB9E8A);
}

.ig92uxq3u {
  stop-color: var(--svg-color--50d5fa, #50D5FA);
}

.im-nu1b_s {
  stop-color: var(--svg-color--ba7963, #BA7963);
}

.ipq9-xbsh {
  stop-color: var(--svg-color--e8c29c, #E8C29C);
}

.iqoe-4pvq {
  stop-color: var(--svg-color--766c87, #766C87);
  stop-opacity: 0;
}

.j-ut2xl5o {
  d: path("M12.625 19.547c.026.292.262.988.999 1.438c.736.45 1.14.63 1.25.664c.11-.034.515-.214 1.251-.664c.737-.45.973-1.146 1-1.438z");
}

.j05e95eeg {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
}

.j11nupb8y {
  stop-color: var(--svg-color--696284, #696284);
}

.j1n1ygxtd {
  stop-color: var(--svg-color--e3ac86, #E3AC86);
}

.j554sh0mc {
  stop-color: var(--svg-color--d1a090, #D1A090);
  stop-opacity: 0;
}

.jglb--p4a {
  stop-color: var(--svg-color--b57a7c, #B57A7C);
}

.jt362mrmb {
  stop-color: var(--svg-color--f8c7a5, #F8C7A5);
}

.k-34bbczy {
  stop-color: var(--svg-color--be826d, #BE826D);
}

.k1zgefb2d {
  stop-color: var(--svg-color--605a74, #605A74);
}

.k5i52n_gm {
  stop-color: var(--svg-color--2683c8, #2683C8);
}

.k7e504bil {
  cx: 25.695px;
  cy: 17.094px;
  r: 3.078px;
  fill: var(--svg-color--3e2657, #3E2657);
}

.k9h8bsbwk {
  stop-color: var(--svg-color--403357, #403357);
}

.kdvr4u58b {
  d: path("m14.372 12.364l-.61 1.953a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.433-.742-.433-.88 0");
}

.khpardbxn {
  stop-color: var(--svg-color--d49b75, #D49B75);
}

.kldze1b9y {
  stop-color: var(--svg-color--d1a090, #D1A090);
}

.kpssiabxl {
  stop-color: var(--svg-color--5c5178, #5C5178);
  stop-opacity: 0;
}

.kte-0sm3k {
  stop-color: var(--svg-color--cfbdc9, #CFBDC9);
  stop-opacity: 0;
}

.kvzrrwynu {
  stop-color: var(--svg-color--6a5e90, #6A5E90);
}

.kwu50z17h {
  fill: var(--svg-color--ba8072, #BA8072);
  d: path("m14.495 12.81l-.943 1.952c-.117.402.164.803.56.803h.848c.397 0 .678-.407.56-.803l-.572-1.953c-.123-.432-.325-.432-.453 0");
}

.l-8-g4b2m {
  d: path("m10.75 16.977l2.742 12.945h-1.797a1571 1571 0 0 1-4.625-7.734c-.422-.735-.219-.907-.14-1.032c.077-.125.374-.36.671-.468c.238-.088.328-.204.344-.25c.057-.068.069-.3-.344-.688c-.412-.387-1.307-1.068-1.703-1.36c-.234-.187-.652-.609-.602-.984s.652-.435.766-.43z");
}

.l4za3cbte {
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.41-12.142-11.41S3.125 23.555 2.727 29.923");
}

.l6qykxbvl {
  d: path("M12.3 11.548a1.025 1.025 0 0 0-.989 1.295h1.98q.037-.131.038-.27a1.03 1.03 0 0 0-1.03-1.025");
}

.l9k3lrq7u {
  stop-color: var(--svg-color--d1c0d6, #D1C0D6);
}

.la8vvmbhh {
  stop-color: var(--svg-color--ad254b, #AD254B);
  stop-opacity: 0;
}

.lcqew7b7f {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
  stop-opacity: 0;
}

.ld92_g1my {
  stop-color: var(--svg-color--7f81b2, #7F81B2);
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lg14abbip {
  stop-color: var(--svg-color--605a74, #605A74);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljhgv1b3v {
  cx: 11.99px;
  cy: 11.986px;
  rx: 0.448px;
  ry: 0.227px;
}

.lk3ugac1n {
  stop-color: var(--svg-color--b97961, #B97961);
}

.m5pcs-93k {
  stop-color: var(--svg-color--2c1840, #2C1840);
  stop-opacity: 0;
}

.mdv9qbyfi {
  stop-color: var(--svg-color--d69368, #D69368);
}

.mh39h7hpm {
  cx: 9.356px;
  cy: 12.68px;
  r: 1.918px;
}

.mibx7d57r {
  fill: var(--svg-color--000, #000);
  d: path("M12.886 12.573a.585.585 0 0 0-.587-.587a.585.585 0 0 0-.522.857h1.04a.6.6 0 0 0 .07-.27");
}

.mijx23bkm {
  d: path("M17.242 11.764c.072.098-.08.217-.254.347c-.173.13-.302.22-.375.123s.008-.282.182-.412c.173-.13.373-.155.446-.058");
}

.mk8ahybcp {
  stop-color: var(--svg-color--d69f80, #D69F80);
}

.mndtykbcd {
  stop-color: var(--svg-color--a8716e, #A8716E);
}

.mrtz5_gxn {
  stop-color: var(--svg-color--5a3c37, #5A3C37);
}

.mw9gk7bly {
  stop-color: var(--svg-color--3f3050, #3F3050);
}

.mx64gfpes {
  stop-color: var(--svg-color--6a6385, #6A6385);
}

.n_u2l52pq {
  stop-color: var(--svg-color--c48986, #C48986);
  stop-opacity: 0;
}

.n0g6o9q3d {
  stop-color: var(--svg-color--c18e76, #C18E76);
}

.n0h_63bcp {
  cx: 20.286px;
  cy: 12.68px;
  r: 1.918px;
}

.n3pyssb7u {
  stop-color: var(--svg-color--452053, #452053);
}

.ne453misf {
  stop-color: var(--svg-color--c28d74, #C28D74);
  stop-opacity: 0;
}

.nf2o-hpjm {
  stop-color: var(--svg-color--857da2, #857DA2);
}

.nfkpkr9uv {
  stop-color: var(--svg-color--a4656d, #A4656D);
}

.nig76no1i {
  stop-color: var(--svg-color--4e4270, #4E4270);
  stop-opacity: 0;
}

.njrd_tayg {
  stop-color: var(--svg-color--573a60, #573A60);
}

.nw6o4wclj {
  stop-color: var(--svg-color--624c7f, #624C7F);
}

.nzffxlbem {
  stop-color: var(--svg-color--4f456a, #4F456A);
}

.o58_qgbus {
  stop-color: var(--svg-color--dcc8d0, #DCC8D0);
}

.o6jqa8bjh {
  stop-color: var(--svg-color--af7477, #AF7477);
}

.o8gobxb3n {
  stop-color: var(--svg-color--897b8e, #897B8E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_d1sh7z {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
}

.ojl7ynbtd {
  stop-color: var(--svg-color--c28d74, #C28D74);
}

.ol5y5gj7m {
  stop-color: var(--svg-color--69638b, #69638B);
  stop-opacity: 0;
}

.op_u9g8uj {
  stop-color: var(--svg-color--c03660, #C03660);
}

.p9_jm0xvg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.242 11.764c.072.098-.08.217-.254.347c-.173.13-.302.22-.375.123s.008-.282.182-.412c.173-.13.373-.155.446-.058");
}

.pb1ehqpec {
  stop-color: var(--svg-color--4f456a, #4F456A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pwa97nbfq {
  stop-color: var(--svg-color--5b4361, #5B4361);
  stop-opacity: 0;
}

.pxopwiwar {
  stop-color: var(--svg-color--c18e76, #C18E76);
  stop-opacity: 0;
}

.q-14d3boa {
  stop-color: var(--svg-color--8c7c93, #8C7C93);
  stop-opacity: 0;
}

.q8ppcjbus {
  stop-color: var(--svg-color--624c7f, #624C7F);
  stop-opacity: 0;
}

.qasiqcczj {
  stop-color: var(--svg-color--837a8e, #837A8E);
  stop-opacity: 0;
}

.qlmxj_uev {
  stop-color: var(--svg-color--a77262, #A77262);
}

.qxybu3s-p {
  stop-color: var(--svg-color--e6bc97, #E6BC97);
}

.r4yjzls_o {
  stop-color: var(--svg-color--c9938e, #C9938E);
  stop-opacity: 0;
}

.rc26n1b9i {
  stop-color: var(--svg-color--2c1840, #2C1840);
}

.rcslxcb9f {
  stop-color: var(--svg-color--675685, #675685);
}

.rncji_bbq {
  stop-color: var(--svg-color--c18880, #C18880);
}

.rrgrst12i {
  fill: var(--svg-color--000, #000);
  d: path("M16.73 12.573c0-.326.26-.587.587-.587a.585.585 0 0 1 .522.857h-1.04a.53.53 0 0 1-.07-.27");
}

.rubo83wtt {
  stop-color: var(--svg-color--e8c29c, #E8C29C);
  stop-opacity: 0;
}

.rxpl4qnie {
  stop-color: var(--svg-color--4e4854, #4E4854);
  stop-opacity: 0;
}

.s_d1fy10v {
  stop-color: var(--svg-color--4c4364, #4C4364);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sjbfjtb6o {
  d: path("M13.236 12.453c0-.332-.27-.553-.343-.62l-.33.321l.203.415z");
}

.t-s_cxb3y {
  stop-color: var(--svg-color--5b4373, #5B4373);
}

.t0ozsbnai {
  stop-color: var(--svg-color--766c87, #766C87);
}

.t11-a9gub {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
  stop-opacity: 0;
}

.t9v2librs {
  fill: var(--svg-color--beb2c3, #BEB2C3);
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.293l-2.281 10.863z");
}

.tei_ukbxq {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M14.81 16.4c-.582 0-1.13-.137-1.59-.377c-.158-.08-.327.097-.228.24a2.17 2.17 0 0 0 1.819.971c.764 0 1.434-.388 1.819-.971c.099-.149-.07-.32-.228-.24a3.4 3.4 0 0 1-1.591.377");
}

.thvbr9biq {
  stop-color: var(--svg-color--27a8e3, #27A8E3);
}

.tiyakobla {
  stop-color: var(--svg-color--c28c7d, #C28C7D);
}

.tjiypub2l {
  width: 1.769px;
  height: 2.205px;
  x: 25.512px;
  y: 15.977px;
  rx: 0.885px;
}

.tnc_xbdtt {
  stop-color: var(--svg-color--202d61, #202D61);
}

.tro7l0cbh {
  stop-color: var(--svg-color--d59979, #D59979);
}

.tw93opnhd {
  stop-color: var(--svg-color--e7bb9e, #E7BB9E);
}

.u2w_l1bed {
  stop-color: var(--svg-color--c08385, #C08385);
  stop-opacity: 0;
}

.ub4yxzbiu {
  stop-color: var(--svg-color--a87362, #A87362);
  stop-opacity: 0;
}

.ub7ncfbla {
  stop-color: var(--svg-color--ebb492, #EBB492);
}

.um4p__bni {
  stop-color: var(--svg-color--442e33, #442E33);
}

.uvo3wxbsr {
  stop-color: var(--svg-color--5f577e, #5F577E);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.v2sibmb_y {
  stop-color: var(--svg-color--a9726f, #A9726F);
}

.vd-u4acdq {
  cx: 25.695px;
  cy: 17.094px;
  r: 2.984px;
}

.vi7fu79ul {
  d: path("m13.289 29.922l.854-5.408a.1.1 0 0 1 .098-.084h1.247a.1.1 0 0 1 .099.085l.827 5.407z");
}

.vjaj-kz7h {
  stop-color: var(--svg-color--5f577e, #5F577E);
  stop-opacity: 0;
}

.vn1l7s8zo {
  stop-color: var(--svg-color--c9938e, #C9938E);
}

.vsqgrkwbb {
  stop-color: var(--svg-color--2bace5, #2BACE5);
  stop-opacity: 0;
}

.w1a3e9bkq {
  stop-color: var(--svg-color--dfb08c, #DFB08C);
  stop-opacity: 0;
}

.w20yp5bum {
  d: path("M8.951 11.977c-.03-.36-.067-1.389-.067-1.653c0-.306.124-.674.37-.858l.185-.184c.308-.245.432-.613.432-.98v-.98c0-.307.184-.552.493-.614c.74-.184 2.28-.49 4.499-.49s3.76.306 4.499.49c.246.062.493.307.493.613v.98c0 .368.185.736.431.981c.577.404.541.627.493 1.103c-.014.148-.061 1.373-.102 1.655l-.305 4.548c-.185 2.033-1.783 3.45-3.69 3.45h-3.688c-1.967 0-3.504-1.417-3.689-3.45z");
}

.w4qudxuvg {
  fill: var(--svg-color--bf8b79, #BF8B79);
  d: path("m14.372 12.622l-.61 1.952a.62.62 0 0 0 .597.804h.904a.62.62 0 0 0 .598-.804l-.61-1.952c-.132-.433-.742-.433-.88 0");
}

.we1vuebip {
  d: path("m18.996 16.977l-2.743 12.945h1.797c1.401-2.333 4.288-7.147 4.625-7.734c.422-.735.219-.907.14-1.032c-.077-.125-.374-.36-.671-.468c-.238-.088-.328-.204-.344-.25c-.057-.068-.069-.3.344-.688c.412-.387 1.307-1.068 1.703-1.36c.234-.187.652-.609.602-.984s-.651-.435-.766-.43z");
}

.wsj2g07-c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.614 26.955h1.962");
}

.wss6y3b2p {
  stop-color: var(--svg-color--b41945, #B41945);
}

.x__1z6aoh {
  stop-color: var(--svg-color--39304b, #39304B);
}

.x26s0_r_n {
  stop-color: var(--svg-color--443665, #443665);
}

.x2herp8_d {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
  stop-opacity: 0;
}

.x84cwhbna {
  stop-color: var(--svg-color--57497f, #57497F);
}

.xh__ycc9a {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.061 11.236c-.75 0-1.384.517-1.556 1.216c-.052.2.102.391.307.391h2.563a.264.264 0 0 0 .261-.312a1.61 1.61 0 0 0-1.575-1.295");
}

.xmwni0bou {
  stop-color: var(--svg-color--dfb08c, #DFB08C);
}

.xqc8z1bhj {
  stop-color: var(--svg-color--6a6385, #6A6385);
  stop-opacity: 0;
}

.xtl5dn5fo {
  stop-color: var(--svg-color--403357, #403357);
  stop-opacity: 0;
}

.y-v21bc8n {
  cx: 11.99px;
  cy: 11.986px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.448px;
  ry: 0.227px;
}

.ybx8c08_o {
  stop-color: var(--svg-color--e7bb9e, #E7BB9E);
  stop-opacity: 0;
}

.ycvscybwl {
  stop-color: var(--svg-color--e9b597, #E9B597);
}

.yfkzyxbts {
  stop-color: var(--svg-color--f8c7a5, #F8C7A5);
  stop-opacity: 0;
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yjxmx4bbz {
  stop-color: var(--svg-color--cd9d87, #CD9D87);
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.yrzi8mt9l {
  stop-color: var(--svg-color--fdc6a0, #FDC6A0);
}

.yv_7k4c8b {
  stop-color: var(--svg-color--a9726f, #A9726F);
  stop-opacity: 0;
}

.z_k8o-57c {
  stop-color: var(--svg-color--4e4854, #4E4854);
}

.z_rbfc5vy {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
}

.zo9leke9p {
  stop-color: var(--svg-color--e1b086, #E1B086);
}

.zpb-61ddc {
  stop-color: var(--svg-color--645d7e, #645D7E);
}

.zqbz6fbvb {
  stop-color: var(--svg-color--988b89, #988B89);
  stop-opacity: 0;
}

.zuvzebcmo {
  stop-color: var(--svg-color--4c3156, #4C3156);
}

.zy5dj18nw {
  stop-color: var(--svg-color--69638b, #69638B);
}

</style>
