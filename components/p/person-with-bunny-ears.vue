<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZ9oqYd)"><path fill="url(#iKuP7vb)" class="b758nfkke"/><path fill="url(#iA91m9b)" class="b758nfkke"/></g><g filter="url(#ioKZDGe)"><path fill="url(#igcTZLn)" class="so_94lbpe"/><path fill="url(#iZGELGd)" class="so_94lbpe"/></g><g filter="url(#iZAooDh)"><path class="r0quhfb0s"/></g><g filter="url(#iGZTsIb)"><path class="jprjlabhx"/></g><path fill="url(#ihwmBPD)" class="mvibbjbcf"/><path fill="url(#iage9bb)" class="mvibbjbcf"/><path fill="url(#iZJeGhb)" class="boxwmm-wf"/><path fill="url(#ia4jidd)" class="boxwmm-wf"/><path fill="url(#iWnJpqd)" class="lev6n5q8c"/><path fill="url(#iHefs7d)" class="lev6n5q8c"/><path fill="url(#iZLehKd)" class="h5al9-gpg"/><path fill="url(#iZNqC6c)" class="h5al9-gpg"/><circle fill="url(#iM1YSCc)" class="dv8znbblt"/><circle fill="url(#iDEg4Pb)" class="bt436zblv"/><g filter="url(#idjKpwe)"><path clip-rule="evenodd" class="p3o9_ab-f"/></g><g filter="url(#iWQXa0g)"><path clip-rule="evenodd" class="vqz6-acsp"/></g><circle fill="url(#i9ZTklb)" transform="matrix(-1 0 0 1 12.14 16.74)" class="kr_eiac3t"/><circle fill="url(#i9ZTklb)" transform="matrix(-1 0 0 1 25.185 16.737)" class="kr_eiac3t"/><g filter="url(#i0qwGne)"><path clip-rule="evenodd" class="n__-bo9bn"/><path fill="url(#i7g6WLj)" clip-rule="evenodd" class="qe_kyxzzv"/></g><g filter="url(#ihT5CXd)"><path clip-rule="evenodd" class="x9ra_-b_q"/><path fill="url(#iEWfgmz)" clip-rule="evenodd" class="pqx_405fq"/></g><path fill="url(#iGTZvXc)" class="rlexyf32w"/><path fill="url(#i581a4j)" class="rlexyf32w"/><path fill="url(#iOiLDTc)" class="g50-kabdv"/><path fill="url(#iEf4nKd)" class="g50-kabdv"/><path class="j07d3acqi"/><path fill="url(#iSlLKje)" class="m4awiob-w"/><path class="i3u2_9omj"/><path fill="url(#iOIffeb)" class="wmhzuccfs"/><g filter="url(#iFhRkXb)"><path class="tcbf7abst"/></g><g filter="url(#iTEq5dd)"><path class="p1g0tn7rh"/></g><path fill="url(#i4oD8po)" class="xhiabvblh"/><path fill="url(#iOmnW4d)" class="xhiabvblh"/><path fill="url(#izr4rre)" class="xhiabvblh"/><path fill="url(#iwPQute)" class="xhiabvblh"/><path fill="url(#i93ujPe)" class="xhiabvblh"/><path fill="url(#iv41e0x)" class="jr4_xxmua"/><path fill="url(#iO8AHsd)" class="jr4_xxmua"/><path fill="url(#ie0lxEc)" class="jr4_xxmua"/><path fill="url(#iyplTkc)" class="jr4_xxmua"/><path fill="url(#iVT6SYV)" class="jr4_xxmua"/><path fill="url(#ih11A5L)" class="ldn4ycudz"/><path fill="url(#iyM5iMc)" class="d4n625bpg"/><path fill="url(#iWPWAGb)" class="xr6u_bcdu"/><path fill="url(#iz2USvz)" class="xr6u_bcdu"/><path fill="url(#iuWT3Hc)" class="ky97kqbhl"/><path fill="url(#ibneI4c)" class="ky97kqbhl"/><path fill="url(#ixilAfQ)" class="n-ekb-avj"/><path fill="url(#irLGinb)" class="n-ekb-avj"/><path fill="url(#iEaRkCe)" class="tw89kdb7m"/><path fill="url(#ihh4zAd)" class="tw89kdb7m"/><g filter="url(#i7Cxdcd)"><path fill="url(#iwTk6Lc)" class="o9z8ehbpf"/></g><g filter="url(#ipTHxqc)"><path fill="url(#iMd84Kc)" class="dqsrvwabk"/></g><path fill="url(#ikEeVJe)" class="o9z8ehbpf"/><path fill="url(#iBDHNOc)" class="o9z8ehbpf"/><path fill="url(#iz6wT6c)" class="o9z8ehbpf"/><path fill="url(#iec55ie)" class="o9z8ehbpf"/><path fill="url(#izaWzXc)" class="dqsrvwabk"/><path fill="url(#ikfqX6b)" class="dqsrvwabk"/><path fill="url(#idit3ke)" class="dqsrvwabk"/><path fill="url(#igBHVtc)" class="dqsrvwabk"/><g filter="url(#idbLnNd)"><path class="l6jimebln"/></g><g filter="url(#izAOGae)"><path class="ci99xl0zg"/></g><g filter="url(#iaE0ylb)"><path fill="url(#ihaPdBe)" class="ib-ru7q1z"/><path fill="url(#iFLJ92E)" class="ib-ru7q1z"/><path fill="url(#ijvUwid)" class="ib-ru7q1z"/><path fill="url(#iJf3cpb)" class="ib-ru7q1z"/></g><g filter="url(#iwYZrZP)"><path fill="url(#iVTRaLe)" class="a2debs8jv"/><path fill="url(#isMoxmc)" class="a2debs8jv"/><path fill="url(#iOwb40b)" class="a2debs8jv"/><path fill="url(#ibq65qc)" class="a2debs8jv"/></g><g filter="url(#itLYZCc)"><path stroke="url(#isJYTyb)" class="w8-yfvy3r"/></g><g filter="url(#i382E1c)"><path stroke="url(#iKV2lKb)" class="jiiug3ubc"/></g><path fill="url(#iZ4nasb)" class="qk1ct7bid"/><path fill="url(#ibceYOc)" class="expgz23kp"/><g filter="url(#iWT1rhb)"><path fill="url(#iMw2iKc)" class="lfa14t-ke"/><path fill="url(#igk8tDd)" class="lfa14t-ke"/><path fill="url(#iUevbDd)" class="lfa14t-ke"/><path fill="url(#i5DF3Xd)" class="lfa14t-ke"/><path fill="url(#ibKMFwb)" class="lfa14t-ke"/></g><g filter="url(#iYjMUeb)"><path fill="url(#iHAvwnb)" class="je3t_eb0n"/><path fill="url(#ii7VL1c)" class="je3t_eb0n"/><path fill="url(#ieV8DEj)" class="je3t_eb0n"/><path fill="url(#i6vGGfd)" class="je3t_eb0n"/><path fill="url(#iJrGiGG)" class="je3t_eb0n"/></g><g filter="url(#iTMe8Qz)"><path class="awyh_9bma"/></g><g filter="url(#iT4jbMd)"><path class="ol_ouv-hi"/></g><g filter="url(#iPKg2Ie)"><path class="rsxhsvbfc"/></g><g filter="url(#ikXf3Ud)"><path class="gs6ggpx6m"/></g><g filter="url(#iUV6qee)"><path fill="url(#iFXtGXb)" class="woynzybua"/><path fill="url(#iokHVtc)" class="woynzybua"/></g><g filter="url(#iQhvBVn)"><path fill="url(#ixwYNxu)" class="i7vp14pui"/><path fill="url(#imD6Q0T)" class="i7vp14pui"/></g><g filter="url(#ixtSDHb)"><path fill="url(#i7ZGVgd)" class="lb888hb3o"/><path fill="url(#if9phnd)" class="lb888hb3o"/><path fill="url(#iUdnt8c)" class="lb888hb3o"/><path fill="url(#iefIKne)" class="lb888hb3o"/><path fill="url(#ioDCpke)" class="lb888hb3o"/></g><g filter="url(#i05N9Uc)"><path fill="url(#i55Myrc)" class="xw85bn2ef"/><path fill="url(#iEUziTc)" class="xw85bn2ef"/><path fill="url(#i8rHXzu)" class="xw85bn2ef"/><path fill="url(#iXgKMdd)" class="xw85bn2ef"/><path fill="url(#iJUr7ne)" class="xw85bn2ef"/></g><path class="gqdgu0j6b"/><path fill="url(#iHnTpOx)" class="e1koltbiu"/><path fill="url(#iPjCwNd)" class="nq3v0pbar"/><path class="ax6pvob8b"/><g filter="url(#i7xn6LB)"><path class="zft9nkbvg"/><path fill="url(#imxUdne)" class="hspunwb8c"/></g><g filter="url(#iivV2Me)"><path class="bn_7_35gv"/><path fill="url(#iWrALkd)" class="gz9s2oe2v"/></g><g filter="url(#iOUHvlv)"><path fill="url(#iV8xFwe)" class="k0qsjnbyp"/></g><g filter="url(#ifBpXNe)"><path fill="url(#iN01gBc)" class="uc21wsnks"/></g><path class="f9mc-ob5w"/><path fill="url(#iNYgW7b)" class="fpvd-k3bq"/><path fill="url(#iefan7c)" class="yj4wxr9mo"/><path class="qm7bfbbof"/><g filter="url(#is00TKd)"><path fill="url(#iSg61Qd)" class="z60z6abmj"/></g><g filter="url(#ir2rLDO)"><path fill="url(#ieJ9lwd)" class="qny9bli6l"/></g><g filter="url(#i6NqCbb)"><ellipse transform="rotate(-27.914 7.76 7.51)" class="l8ndqab4x"/><ellipse fill="url(#igs6Vkb)" transform="rotate(-27.914 7.76 7.51)" class="qgemki93n"/></g><g filter="url(#itVPSMZ)"><ellipse transform="rotate(-27.914 20.805 7.506)" class="j-_hh500g"/><ellipse fill="url(#iUENmoN)" transform="rotate(-27.914 20.805 7.506)" class="cncrdjbxf"/></g><path fill="url(#i3rrPpd)" class="ntyljqbha"/><path fill="url(#i9JBOee)" class="ntyljqbha"/><path fill="url(#i6tO24O)" class="ntyljqbha"/><path fill="url(#izKcAYb)" class="d_byeyy6z"/><path fill="url(#iuRhcGc)" class="d_byeyy6z"/><path fill="url(#ilgEAQe)" class="d_byeyy6z"/><path fill="url(#iGRaOmc)" class="e0becjn_z"/><path fill="url(#iNTv3ta)" class="e0becjn_z"/><path fill="url(#ieY8hNc)" class="csq8y2_5z"/><path fill="url(#i63lkeE)" class="csq8y2_5z"/><g filter="url(#idF2RXc)"><path class="v7zd-lrql"/></g><g filter="url(#iZHbGme)"><path class="rpvc_qtwj"/></g><g filter="url(#ihC2cJf)"><path class="m2qjn9e2l"/></g><g filter="url(#igKyrwT)"><path class="z4l_qbmxy"/></g><g filter="url(#iBEXDHc)"><path class="p8ityucpx"/></g><g filter="url(#irHxGSN)"><path class="xlep1wb3b"/></g><g filter="url(#i8moDxb)"><path class="azo0e8bdz"/></g><g filter="url(#i6Iu10c)"><path class="oce08sbqg"/></g><g filter="url(#iiHtX3d)"><path class="drwvv_b-e"/></g><g filter="url(#ijjJUrd)"><path class="xw-0u-b6x"/></g><g filter="url(#iIDG77d)"><path class="nn3kt3d-l"/></g><g filter="url(#iAKswdd)"><path class="suuif295x"/></g><g filter="url(#iVkA7pe)"><path fill="url(#i9XcOXb)" class="o2zi9tiwu"/></g><g filter="url(#iJXBcBc)"><path fill="url(#iEy2Kld)" class="oqoxvqb7c"/></g><defs><radialGradient id="ihwmBPD" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.116)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="iage9bb" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.587 21.055)scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="iZJeGhb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.112)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="ia4jidd" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.06 34.624)scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="iWnJpqd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.203 29.866)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="iHefs7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.494 28.413)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="iZLehKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.249 29.862)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="iZNqC6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.409)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="iM1YSCc" cx="0" cy="0" r="1" gradientTransform="rotate(67.546 -9.821 12.192)scale(.82843)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="u61ql_uag"/><stop offset="1" class="x_wj4vl5i"/></radialGradient><radialGradient id="iDEg4Pb" cx="0" cy="0" r="1" gradientTransform="rotate(67.546 -3.296 21.943)scale(.82843)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="u61ql_uag"/><stop offset="1" class="x_wj4vl5i"/></radialGradient><radialGradient id="i9ZTklb" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325)scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="stug43bab"/><stop offset="1" class="kmwt4ebda"/></radialGradient><radialGradient id="i7g6WLj" cx="0" cy="0" r="1" gradientTransform="matrix(2.74585 1.47356 -.61307 1.1424 13.192 12.314)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="p_drcebab"/><stop offset="1" class="tdgu1u54k"/></radialGradient><radialGradient id="iEWfgmz" cx="0" cy="0" r="1" gradientTransform="matrix(2.74585 1.47356 -.61307 1.1424 26.237 12.31)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="p_drcebab"/><stop offset="1" class="tdgu1u54k"/></radialGradient><radialGradient id="i4oD8po" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 9.51 21.85)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="gjropwo4q"/><stop offset="1" class="agepe-_9u"/></radialGradient><radialGradient id="izr4rre" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 11.97 7.279)scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="iwPQute" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 3.761 7.839)scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="i93ujPe" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 16.5 5.69)scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="iv41e0x" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 22.556 21.846)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="gjropwo4q"/><stop offset="1" class="agepe-_9u"/></radialGradient><radialGradient id="ie0lxEc" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 18.492 3.114)scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="iyplTkc" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 10.285 10.167)scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="iVT6SYV" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 23.02 -2.038)scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="ih11A5L" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 8.334 10.272)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="cbz98_bgl"/><stop offset=".902" class="jtnx86cjw"/></radialGradient><radialGradient id="iyM5iMc" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 21.38 10.268)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="cbz98_bgl"/><stop offset=".902" class="jtnx86cjw"/></radialGradient><radialGradient id="iWPWAGb" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 2.29 8.616)scale(1.64694 1.95644)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iz2USvz" cx="0" cy="0" r="1" gradientTransform="matrix(.12617 .17303 -.14699 .10718 10.88 8.465)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iuWT3Hc" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 8.814 13.787)scale(1.64694 1.95644)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="ibneI4c" cx="0" cy="0" r="1" gradientTransform="matrix(.12617 .17303 -.14699 .10718 23.925 8.461)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="ixilAfQ" cx="0" cy="0" r="1" gradientTransform="matrix(.57339 1.68758 -.76708 .26063 6.428 8.4)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="irLGinb" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -2.391 8.794)scale(.4503 .39501)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iEaRkCe" cx="0" cy="0" r="1" gradientTransform="matrix(.57339 1.68758 -.76708 .26063 19.474 8.396)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="ihh4zAd" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 4.134 17.722)scale(.4503 .39501)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iwTk6Lc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24864 0 0 -3.97781 10.022 7.945)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iMd84Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24864 0 0 -3.97781 23.068 7.94)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="ikEeVJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.17313 2.6246 -.96491 -.06365 11.033 7.845)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iBDHNOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60814 .73217 0 7.915 7.437)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iz6wT6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.66035 .8565 0 9.885 7.26)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iec55ie" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.97384 -4.65511 0 8.835 6.625)" gradientUnits="userSpaceOnUse"><stop offset=".743" class="xhhozw94f"/><stop offset="1" class="cwn535bps"/></radialGradient><radialGradient id="izaWzXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.17313 2.6246 -.96491 -.06365 24.079 7.841)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="ikfqX6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60814 .73217 0 20.96 7.433)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="idit3ke" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.66035 .8565 0 22.93 7.256)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="igBHVtc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.97384 -4.65511 0 21.88 6.621)" gradientUnits="userSpaceOnUse"><stop offset=".743" class="xhhozw94f"/><stop offset="1" class="cwn535bps"/></radialGradient><radialGradient id="isJYTyb" cx="0" cy="0" r="1" gradientTransform="matrix(.14932 -.26644 .77535 .43454 8.33 9.36)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iKV2lKb" cx="0" cy="0" r="1" gradientTransform="matrix(.14932 -.26644 .77535 .43454 21.375 9.355)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iZ4nasb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.31 1.24724 0 8.815 9.467)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ibceYOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.31 1.24724 0 21.86 9.463)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="igk8tDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.45988 4.35842 0 6.565 7.264)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iUevbDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.5625 2.76844 0 10.905 7.264)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="i5DF3Xd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.76631 -.61973 .33005 -.94068 10.58 4.565)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="ibKMFwb" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 .746 9.467)scale(.74436 1.72359)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="ii7VL1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.45988 4.35842 0 19.61 7.26)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="ieV8DEj" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.5625 2.76844 0 23.95 7.26)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="i6vGGfd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.76631 -.61973 .33005 -.94068 23.626 4.56)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iJrGiGG" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 7.273 21.12)scale(.74436 1.72359)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iFXtGXb" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 4.068 3.03)scale(1.74078 .4845)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iokHVtc" cx="0" cy="0" r="1" gradientTransform="matrix(1.38422 -2.19169 2.42816 1.53357 6.479 6.547)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="ixwYNxu" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 10.591 4.17)scale(1.74078 .4845)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="imD6Q0T" cx="0" cy="0" r="1" gradientTransform="matrix(1.38422 -2.19169 2.42816 1.53357 19.524 6.543)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="i7ZGVgd" cx="0" cy="0" r="1" gradientTransform="matrix(1.45632 .34446 -.19264 .81447 10.372 5)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="if9phnd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 7.52 .316)scale(1.84172 1.02711)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iUdnt8c" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 7.327 .364)scale(1.1016 .78903)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iefIKne" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06393 .49516 -.53529 -2.23119 10.877 4.949)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="ioDCpke" cx="0" cy="0" r="1" gradientTransform="matrix(-.05047 .16505 -.7546 -.23073 10.3 4.895)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="i55Myrc" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -9.702 102.868)scale(1.4965 .83694)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iEUziTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.92417 -1.59306 .88843 -.5154 24.066 6.976)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="i8rHXzu" cx="0" cy="0" r="1" gradientTransform="matrix(-.56233 -.94726 .67848 -.40277 23.8 6.847)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iXgKMdd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06393 .49516 -.53529 -2.23119 23.922 4.945)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="iJUr7ne" cx="0" cy="0" r="1" gradientTransform="matrix(-.05047 .16505 -.7546 -.23073 23.345 4.891)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="iHnTpOx" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3494 -.55575 0 9.754 7.551)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iPjCwNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3494 -.55575 0 22.799 7.547)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="imxUdne" cx="0" cy="0" r="1" gradientTransform="matrix(-.09975 -.12855 .17698 -.13734 9.655 7.587)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWrALkd" cx="0" cy="0" r="1" gradientTransform="matrix(-.09975 -.12855 .17698 -.13734 22.7 7.583)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNYgW7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34941 -.55578 0 7.877 7.55)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iefan7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34941 -.55578 0 20.922 7.547)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="igs6Vkb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 7.64 .006)scale(.21254 .25549)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUENmoN" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.16 -6.417)scale(.21254 .25549)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9JBOee" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 .418 10.9)scale(1.00205 .95603)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="i6tO24O" cx="0" cy="0" r="1" gradientTransform="matrix(.33885 -.46501 .38977 .28402 10.956 7.79)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iuRhcGc" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 6.943 19.5)scale(1.00205 .95603)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="ilgEAQe" cx="0" cy="0" r="1" gradientTransform="matrix(.33885 -.46501 .38977 .28402 24.001 7.787)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iNTv3ta" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 .145 6.502)scale(.91044 .89505)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="i63lkeE" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 6.67 11.854)scale(.91044 .89505)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="iZ9oqYd" width="3.097" height="9.794" x="5.815" y="20.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.717647 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/></filter><filter id="ioKZDGe" width="3.097" height="9.794" x="18.86" y="20.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.717647 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/></filter><filter id="iZAooDh" width="7.428" height="10.091" x="8.776" y="19.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.901961 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/></filter><filter id="iGZTsIb" width="7.428" height="10.091" x="21.821" y="19.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.901961 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/></filter><filter id="idjKpwe" width="5.896" height="7.11" x="2.751" y="10.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="iWQXa0g" width="5.896" height="7.11" x="15.796" y="10.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="i0qwGne" width="5.996" height="6.96" x="9.267" y="10.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="ihT5CXd" width="5.996" height="6.96" x="22.312" y="10.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="iFhRkXb" width="9.692" height="11.056" x="4.665" y="9.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.196078 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.32549 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="iTEq5dd" width="9.692" height="11.056" x="17.71" y="9.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.196078 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.32549 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="i7Cxdcd" width="4.896" height="5.508" x="6.637" y="5.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="ipTHxqc" width="4.896" height="5.508" x="19.682" y="5.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="idbLnNd" width="2.807" height="3.247" x="7.322" y="6.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".5"/></filter><filter id="izAOGae" width="2.807" height="3.247" x="20.367" y="6.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".5"/></filter><filter id="iaE0ylb" width="1.007" height="1.447" x="8.311" y="7.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="iwYZrZP" width="1.007" height="1.447" x="21.356" y="7.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="itLYZCc" width="1.884" height=".962" x="7.873" y="8.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="i382E1c" width="1.885" height=".962" x="20.918" y="8.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="iWT1rhb" width="5.537" height="3.629" x="6.046" y="3.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="iYjMUeb" width="5.537" height="3.629" x="19.092" y="3.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="iTMe8Qz" width="1.063" height=".626" x="9.498" y="6.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/></filter><filter id="iT4jbMd" width="1.063" height=".626" x="22.544" y="6.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/></filter><filter id="iPKg2Ie" width="1.063" height=".62" x="7.238" y="6.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/></filter><filter id="ikXf3Ud" width="1.063" height=".62" x="20.282" y="6.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/></filter><filter id="iUV6qee" width="3.117" height="2.84" x="6.057" y="4.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".125"/></filter><filter id="iQhvBVn" width="3.117" height="2.84" x="19.102" y="4.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".125"/></filter><filter id="ixtSDHb" width="2.951" height="2.715" x="8.674" y="4.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".125"/></filter><filter id="i05N9Uc" width="2.951" height="2.715" x="21.719" y="4.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".125"/></filter><filter id="i7xn6LB" width=".452" height=".413" x="9.381" y="7.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="iivV2Me" width=".452" height=".413" x="22.426" y="7.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="iOUHvlv" width=".612" height=".622" x="9.685" y="7.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".1"/></filter><filter id="ifBpXNe" width=".612" height=".622" x="22.73" y="7.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".1"/></filter><filter id="is00TKd" width=".653" height=".676" x="7.774" y="7.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".1"/></filter><filter id="ir2rLDO" width=".653" height=".676" x="20.819" y="7.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".1"/></filter><filter id="i6NqCbb" width=".507" height=".417" x="7.506" y="7.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="itVPSMZ" width=".507" height=".417" x="20.551" y="7.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="idF2RXc" width=".857" height="1.309" x="6.077" y="7.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".125"/></filter><filter id="iZHbGme" width=".857" height="1.309" x="19.123" y="7.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".125"/></filter><filter id="ihC2cJf" width=".908" height="1.32" x="10.699" y="7.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".125"/></filter><filter id="igKyrwT" width=".908" height="1.32" x="23.744" y="7.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".125"/></filter><filter id="iBEXDHc" width="1.013" height=".477" x="7.214" y="6.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="irHxGSN" width="1.013" height=".477" x="20.259" y="6.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="i8moDxb" width="1.013" height=".477" x="9.484" y="6.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="i6Iu10c" width="1.013" height=".477" x="22.529" y="6.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_703" stdDeviation=".05"/></filter><filter id="iiHtX3d" width="1.73" height="2.911" x="6.683" y="1.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="ijjJUrd" width="1.73" height="2.911" x="19.728" y="1.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="iIDG77d" width="1.73" height="2.911" x="9.394" y="1.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="iAKswdd" width="1.73" height="2.911" x="22.439" y="1.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="iVkA7pe" width="4.792" height="2.36" x="6.658" y="3.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.180392 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.219608 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><filter id="iJXBcBc" width="4.792" height="2.36" x="19.703" y="3.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.180392 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_703"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.219608 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_703" result="effect2_innerShadow_4002_703"/></filter><linearGradient id="iKuP7vb" x1="5.915" x2="7.807" y1="24.131" y2="24.319" gradientUnits="userSpaceOnUse"><stop class="ffo_sl6yt"/><stop offset="1" class="c9hzilbuh"/></linearGradient><linearGradient id="iA91m9b" x1="5.807" x2="6.354" y1="24.819" y2="24.819" gradientUnits="userSpaceOnUse"><stop class="iwqqxcc-f"/><stop offset="1" class="ws-68yb9o"/></linearGradient><linearGradient id="igcTZLn" x1="18.96" x2="20.852" y1="24.128" y2="24.315" gradientUnits="userSpaceOnUse"><stop class="ffo_sl6yt"/><stop offset="1" class="c9hzilbuh"/></linearGradient><linearGradient id="iZGELGd" x1="18.852" x2="19.399" y1="24.815" y2="24.815" gradientUnits="userSpaceOnUse"><stop class="iwqqxcc-f"/><stop offset="1" class="ws-68yb9o"/></linearGradient><linearGradient id="iGTZvXc" x1="5.338" x2="6.26" y1="11.46" y2="13.392" gradientUnits="userSpaceOnUse"><stop class="f56564bqg"/><stop offset=".527" class="b7vrc56qi"/></linearGradient><linearGradient id="i581a4j" x1="5.854" x2="5.495" y1="13.178" y2="12.553" gradientUnits="userSpaceOnUse"><stop class="b9gdpcb9a"/><stop offset="1" class="exo3i6t1h"/></linearGradient><linearGradient id="iOiLDTc" x1="18.383" x2="19.305" y1="11.456" y2="13.388" gradientUnits="userSpaceOnUse"><stop class="f56564bqg"/><stop offset=".527" class="b7vrc56qi"/></linearGradient><linearGradient id="iEf4nKd" x1="18.899" x2="18.539" y1="13.175" y2="12.55" gradientUnits="userSpaceOnUse"><stop class="b9gdpcb9a"/><stop offset="1" class="exo3i6t1h"/></linearGradient><linearGradient id="iSlLKje" x1="12.088" x2="12.526" y1="13.178" y2="12.085" gradientUnits="userSpaceOnUse"><stop class="g8x7j95jh"/><stop offset="1" class="t8-ux1zkq"/></linearGradient><linearGradient id="iOIffeb" x1="25.133" x2="25.571" y1="13.174" y2="12.081" gradientUnits="userSpaceOnUse"><stop class="g8x7j95jh"/><stop offset="1" class="t8-ux1zkq"/></linearGradient><linearGradient id="iOmnW4d" x1="5.729" x2="6.401" y1="19.256" y2="19.241" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="iO8AHsd" x1="18.774" x2="19.446" y1="19.253" y2="19.237" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="ihaPdBe" x1="8.815" x2="9.182" y1="8.301" y2="8.301" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iFLJ92E" x1="8.353" x2="8.815" y1="8.234" y2="8.26" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="ijvUwid" x1="8.815" x2="8.815" y1="8.473" y2="8.839" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iJf3cpb" x1="8.815" x2="8.815" y1="7.506" y2="7.686" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iVTRaLe" x1="21.86" x2="22.228" y1="8.297" y2="8.297" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="isMoxmc" x1="21.399" x2="21.861" y1="8.23" y2="8.256" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iOwb40b" x1="21.86" x2="21.86" y1="8.469" y2="8.835" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="ibq65qc" x1="21.86" x2="21.86" y1="7.502" y2="7.682" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iMw2iKc" x1="11.122" x2="6.767" y1="5.509" y2="5.509" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iHAvwnb" x1="24.167" x2="19.813" y1="5.505" y2="5.505" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iV8xFwe" x1="10.089" x2="9.953" y1="7.574" y2="7.658" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iN01gBc" x1="23.134" x2="22.998" y1="7.57" y2="7.654" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSg61Qd" x1="8.197" x2="8.062" y1="7.574" y2="7.658" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ieJ9lwd" x1="21.242" x2="21.107" y1="7.57" y2="7.654" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3rrPpd" x1="11.583" x2="11.064" y1="7.585" y2="8.521" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="izKcAYb" x1="24.628" x2="24.109" y1="7.582" y2="8.518" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iGRaOmc" x1="6.298" x2="6.926" y1="7.888" y2="7.833" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="ieY8hNc" x1="19.344" x2="19.971" y1="7.884" y2="7.829" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="i9XcOXb" x1="10.698" x2="7.198" y1="5.21" y2="5.397" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="cgzrukeil"/></linearGradient><linearGradient id="iEy2Kld" x1="23.743" x2="20.243" y1="5.206" y2="5.393" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="cgzrukeil"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-bunny-ears" /></template>
<style>
.a2debs8jv {
  d: path("m21.696 7.633l-.229.791c-.047.163.065.325.224.325h.338c.159 0 .27-.165.224-.325l-.229-.79c-.049-.176-.277-.176-.328 0");
}

.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.agepe-_9u {
  stop-color: var(--svg-color--472263, #472263);
  stop-opacity: 0;
}

.ak32k0b7k {
  stop-color: var(--svg-color--695d73, #695D73);
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.awyh_9bma {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M10.42 6.663a.8.8 0 0 0-.295-.177c-.131-.041-.295-.052-.522-.024a.12.12 0 1 0 .03.237c.206-.026.333-.013.42.015c.085.027.143.07.21.13a.12.12 0 1 0 .157-.18");
}

.ax6pvob8b {
  fill: var(--svg-color--000, #000);
  d: path("M9.534 7.73a.22.22 0 0 1 .22-.22a.22.22 0 0 1 .196.32h-.39a.2.2 0 0 1-.026-.1m13.046-.004a.22.22 0 0 1 .22-.22a.22.22 0 0 1 .195.32h-.39a.2.2 0 0 1-.026-.1");
}

.azo0e8bdz {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.346 6.717a1 1 0 0 0-.712-.164");
}

.b758nfkke {
  d: path("m5.915 20.24l2.997.27l-1.063 7.941a1.83 1.83 0 0 1-1.812 1.584a.12.12 0 0 1-.122-.122z");
}

.b7vrc56qi {
  stop-color: var(--svg-color--5b3c65, #5B3C65);
}

.b9gdpcb9a {
  stop-color: var(--svg-color--472162, #472162);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bn_7_35gv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.771 7.423c.027.036-.03.08-.095.13c-.065.048-.113.082-.14.046s.003-.106.068-.155c.065-.048.14-.058.167-.021");
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.boxwmm-wf {
  d: path("m20.929 28.19l-.035.257a1.83 1.83 0 0 1-1.812 1.584a.12.12 0 0 1-.122-.122V28.19z");
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bt436zblv {
  cx: 18.559px;
  cy: 16.608px;
  r: 0.766px;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.c9hzilbuh {
  stop-color: var(--svg-color--ffd142, #FFD142);
}

.cbz98_bgl {
  stop-color: var(--svg-color--eb840b, #EB840B);
}

.cgzrukeil {
  stop-color: var(--svg-color--5a3e62, #5A3E62);
}

.ci99xl0zg {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m21.65 7.718l-.272.79c-.047.163.065.326.224.326h.338c.158 0 .27-.165.224-.326l-.229-.79c-.049-.175-.233-.175-.284 0");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cncrdjbxf {
  cx: 20.805px;
  cy: 7.506px;
  rx: 0.168px;
  ry: 0.085px;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.csq8y2_5z {
  d: path("M19.686 7.141a.692.692 0 0 0 .06 1.377q-.044-.689-.06-1.377");
}

.cwn535bps {
  stop-color: var(--svg-color--dd7f4e, #DD7F4E);
}

.d_byeyy6z {
  d: path("M23.977 8.518q.043-.687.08-1.373a.692.692 0 0 1-.08 1.373");
}

.d4n625bpg {
  d: path("m21.662 11.773l-.865-1.505h2.125l-.824 1.5a.25.25 0 0 1-.436.005");
}

.dqsrvwabk {
  d: path("M19.785 9.13c.11.84.825 1.465 1.671 1.465h.811c.846 0 1.561-.625 1.672-1.465c.05-.81.102-1.617.14-2.427a.623.623 0 0 0-.594-.616h-.602c-.41 0-.783-.242-.951-.62a.29.29 0 0 0-.265-.18h-.548c-.793 0-1.437.65-1.437 1.453c0 .8.05 1.588.103 2.39");
}

.drwvv_b-e {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M6.936 3.275c.222.71.522 1.166.645 1.305l.632-.242c-.013-.183-.096-.709-.324-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29");
}

.dv8znbblt {
  cx: 5.514px;
  cy: 16.612px;
  r: 0.766px;
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e0becjn_z {
  d: path("M6.64 7.145a.692.692 0 0 0 .06 1.377a34 34 0 0 1-.06-1.377");
}

.e1koltbiu {
  d: path("M9.754 7.346a.384.384 0 0 1 .37.485h-.742a.386.386 0 0 1 .372-.486");
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.exo3i6t1h {
  stop-color: var(--svg-color--472162, #472162);
  stop-opacity: 0;
}

.expgz23kp {
  d: path("M21.86 9.187c-.218 0-.424-.052-.596-.142c-.059-.03-.122.037-.085.09a.81.81 0 0 0 .68.364a.81.81 0 0 0 .682-.364c.037-.055-.026-.12-.085-.09c-.173.09-.376.142-.596.142");
}

.f56564bqg {
  stop-color: var(--svg-color--4d364f, #4D364F);
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.f9mc-ob5w {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.786 7.229a.6.6 0 0 0-.582.455a.118.118 0 0 0 .115.147h.96c.06 0 .11-.056.097-.117a.6.6 0 0 0-.59-.485m13.045-.004a.6.6 0 0 0-.582.455a.118.118 0 0 0 .115.147h.96c.06 0 .11-.056.097-.117a.6.6 0 0 0-.59-.485");
}

.ffo_sl6yt {
  stop-color: var(--svg-color--e79f2e, #E79F2E);
}

.fpvd-k3bq {
  d: path("M7.876 7.345a.384.384 0 0 0-.37.486h.742a.387.387 0 0 0-.372-.486");
}

.ft5dv1b6b {
  fill: none;
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.g50-kabdv {
  d: path("m18.306 13.388l2.827-1.586a.8.8 0 1 0-.781-1.396l-2.86 1.612z");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g8x7j95jh {
  stop-color: var(--svg-color--461e67, #461E67);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjropwo4q {
  stop-color: var(--svg-color--472263, #472263);
}

.gqdgu0j6b {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.843 7.229a.6.6 0 0 1 .583.455a.118.118 0 0 1-.115.147h-.96a.1.1 0 0 1-.097-.117a.6.6 0 0 1 .59-.485m13.044-.004a.6.6 0 0 1 .583.455a.118.118 0 0 1-.115.147h-.96a.1.1 0 0 1-.098-.117a.6.6 0 0 1 .59-.485");
}

.gs6ggpx6m {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M20.393 6.612a1.2 1.2 0 0 1 .748-.155a.12.12 0 0 1-.03.238a.95.95 0 0 0-.628.143l-.007.005h-.001a.12.12 0 0 1-.147-.188z");
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.gz9s2oe2v {
  d: path("M22.771 7.423c.027.036-.03.08-.095.13c-.065.048-.113.082-.14.046s.003-.106.068-.155c.065-.048.14-.058.167-.021");
}

.h5al9-gpg {
  d: path("M28.675 28.19h-2.142l.142.307a2.64 2.64 0 0 0 2.398 1.534c.12 0 .206-.12.166-.234z");
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hspunwb8c {
  d: path("M9.726 7.427c.027.036-.03.08-.095.13c-.065.048-.113.082-.14.045c-.028-.036.003-.105.068-.154c.065-.048.14-.058.167-.022");
}

.i3u2_9omj {
  fill: var(--svg-color--675074, #675074);
  d: path("m25.549 13.388l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.504l3.202 1.808z");
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.i7vp14pui {
  d: path("m21.96 5.525l-.029-.058a.29.29 0 0 0-.264-.18h-.548c-.794 0-1.437.65-1.437 1.453v.118c-.146-.11-.33-.346-.33-.726c0-.46.336-.694.55-.842c.061-.042.112-.077.143-.11l.043-.044c.15-.16.418-.444.886-.568q.093-.025.187-.04c.467-.077.808.342.808.815v.177z");
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ib-ru7q1z {
  d: path("m8.65 7.637l-.228.791c-.047.163.065.325.223.325h.339c.158 0 .27-.165.224-.325l-.229-.79c-.049-.176-.278-.176-.329 0");
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.iwqqxcc-f {
  stop-color: var(--svg-color--d9a14c, #D9A14C);
}

.j-_hh500g {
  cx: 20.805px;
  cy: 7.506px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.168px;
  ry: 0.085px;
}

.j07d3acqi {
  fill: var(--svg-color--675074, #675074);
  d: path("m12.504 13.392l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.505l3.202 1.809z");
}

.je3t_eb0n {
  d: path("M23.948 5.084a1.02 1.02 0 0 1 .5 1.539a.67.67 0 0 0-.117.375v.511a.75.75 0 0 0-.287-.115l.034-.69a.623.623 0 0 0-.593-.617h-.602c-.41 0-.783-.242-.951-.62a.29.29 0 0 0-.265-.18h-.548c-.793 0-1.437.65-1.437 1.453l.013.661a.7.7 0 0 0-.31.114v-.517a.67.67 0 0 0-.116-.376a1.03 1.03 0 0 1-.061-1.052c.125-.237.328-.403.559-.484c.246-.088.456-.254.595-.478a1 1 0 0 1 1.243-.392a.64.64 0 0 0 .514 0a1 1 0 0 1 1.248.406c.132.22.34.379.581.462");
}

.jiiug3ubc {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m22.54 9.135l.063.042a.135.135 0 0 0-.015-.17a.14.14 0 0 0-.166-.028a1.2 1.2 0 0 1-.562.133c-.207 0-.4-.049-.561-.133h-.001a.14.14 0 0 0-.167.028a.134.134 0 0 0-.014.17a.89.89 0 0 0 .743.397a.89.89 0 0 0 .744-.397zm0 0a.81.81 0 0 1-.68.364a.81.81 0 0 1-.681-.364c-.037-.053.026-.12.085-.09c.172.09.378.142.596.142c.22 0 .423-.052.596-.142c.059-.03.122.035.085.09Z");
}

.jprjlabhx {
  fill: var(--svg-color--ec9534, #EC9534);
  d: path("m25.774 19.94l-2.703.719l3.604 7.839a2.64 2.64 0 0 0 2.398 1.533c.121 0 .206-.12.166-.234z");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jr4_xxmua {
  d: path("M21.832 9.94a2.87 2.87 0 0 0-2.872 2.872v8.185h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.791 1.605h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.87 2.87 0 0 0-2.872-2.871");
}

.jtnx86cjw {
  stop-color: var(--svg-color--ffc737, #FFC737);
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.k0qsjnbyp {
  d: path("M10.097 7.68a.36.36 0 0 0-.1-.2l-.112.123l.05.098z");
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kmwt4ebda {
  stop-color: var(--svg-color--cf7d4f, #CF7D4F);
}

.kr_eiac3t {
  r: 0.766px;
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.ky97kqbhl {
  d: path("M23.951 8.479a.7.7 0 0 0 .39-.133v.4a.93.93 0 0 1-.578.869q.111-.235.15-.508z");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.l6jimebln {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m8.606 7.722l-.273.79c-.047.163.065.326.224.326h.338c.158 0 .27-.166.224-.326l-.229-.79c-.049-.176-.233-.176-.284 0");
}

.l8ndqab4x {
  cx: 7.76px;
  cy: 7.51px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.168px;
  ry: 0.085px;
}

.lb888hb3o {
  d: path("m11.057 6.98l-.013-.272a.63.63 0 0 0-.604-.613h-.602c-.383 0-.731-.209-.914-.542c0 0 .31-.894.824-.778c.375.084.777.217 1.085.418c.75.49.619 1.371.224 1.787");
}

.ldn4ycudz {
  d: path("m8.617 11.777l-.865-1.505h2.125l-.825 1.5a.25.25 0 0 1-.435.005");
}

.lev6n5q8c {
  d: path("M15.63 28.194h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.166-.234z");
}

.lfa14t-ke {
  d: path("M10.903 5.087a1.02 1.02 0 0 1 .5 1.539a.67.67 0 0 0-.117.376v.511a.75.75 0 0 0-.287-.115l.034-.691a.623.623 0 0 0-.593-.616h-.603a1.04 1.04 0 0 1-.95-.62a.29.29 0 0 0-.266-.18h-.547c-.794 0-1.437.65-1.437 1.453l.013.661a.7.7 0 0 0-.31.114v-.517a.67.67 0 0 0-.116-.376a1.03 1.03 0 0 1-.062-1.052c.126-.237.329-.403.56-.484c.246-.088.455-.254.595-.478A1 1 0 0 1 8.56 4.22a.64.64 0 0 0 .513 0a1 1 0 0 1 1.248.406c.132.22.34.378.582.461");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m2qjn9e2l {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("m10.949 8.242l.048-.82a.411.411 0 0 1-.048.82");
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.m4awiob-w {
  d: path("m12.504 13.392l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.505l3.202 1.809z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.mvibbjbcf {
  d: path("m7.883 28.194l-.034.257a1.83 1.83 0 0 1-1.812 1.584a.12.12 0 0 1-.122-.122v-1.719z");
}

.n__-bo9bn {
  fill: var(--svg-color--ffc93a, #FFC93A);
  fill-rule: evenodd;
  d: path("M9.369 10.718a.8.8 0 0 0 .307 1.088l3.527 1.978a.2.2 0 0 1 .035.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.918l-3.575-2.014a.8.8 0 0 0-1.088.308");
}

.n-ekb-avj {
  d: path("M6.724 8.482a.7.7 0 0 1-.39-.132v.4c0 .384.23.727.577.869a1.8 1.8 0 0 1-.148-.508z");
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nn3kt3d-l {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M10.772 3.275c-.222.71-.523 1.166-.645 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.286-.808.579-1.09.875-.996c.211.086.356.403.079 1.29");
}

.nq3v0pbar {
  d: path("M22.8 7.342a.384.384 0 0 1 .37.485h-.742a.386.386 0 0 1 .372-.486");
}

.ntyljqbha {
  d: path("M10.932 8.521q.043-.685.08-1.372a.692.692 0 0 1-.08 1.372");
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o2zi9tiwu {
  d: path("M11.048 5.753c.019.096-.101.144-.167.07c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.033 1.063c-.065.072-.183.025-.167-.07a2.231 2.231 0 0 1 4.389-.053");
}

.o9z8ehbpf {
  d: path("M6.74 9.134c.11.84.825 1.465 1.67 1.465h.812c.846 0 1.56-.625 1.672-1.465c.05-.81.101-1.617.139-2.427a.623.623 0 0 0-.593-.616h-.602c-.411 0-.783-.242-.952-.62a.29.29 0 0 0-.264-.18h-.548c-.794 0-1.437.65-1.437 1.453c0 .8.05 1.588.102 2.39");
}

.oce08sbqg {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.392 6.713a1 1 0 0 0-.713-.164");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ol_ouv-hi {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M23.466 6.66a.8.8 0 0 0-.296-.178a1.25 1.25 0 0 0-.522-.024a.12.12 0 0 0 .03.237c.206-.026.333-.013.42.015c.085.027.143.07.21.13a.12.12 0 0 0 .157-.18");
}

.oqoxvqb7c {
  d: path("M24.093 5.749c.019.096-.102.144-.167.07c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.034 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053");
}

.p_drcebab {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
}

.p1g0tn7rh {
  fill: var(--svg-color--654470, #654470);
  d: path("M21.832 9.94a2.87 2.87 0 0 0-2.872 2.872v8.185h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.791 1.605h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.87 2.87 0 0 0-2.872-2.871");
}

.p3o9_ab-f {
  fill: var(--svg-color--ffbc3b, #FFBC3B);
  fill-rule: evenodd;
  d: path("M8.395 10.718a.8.8 0 0 1-.307 1.088L4.56 13.784a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.973-1.72c-.93-.82-.855-2.148.347-2.918l3.575-2.014a.8.8 0 0 1 1.088.308");
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.p8ityucpx {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.364 6.737c.11-.08.386-.22.713-.165");
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pqx_405fq {
  fill-rule: evenodd;
  d: path("M22.414 10.714a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.191l1.974-1.72c.93-.821.855-2.149-.348-2.918l-3.574-2.015a.8.8 0 0 0-1.089.308");
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.qe_kyxzzv {
  fill-rule: evenodd;
  d: path("M9.369 10.718a.8.8 0 0 0 .307 1.088l3.527 1.978a.2.2 0 0 1 .035.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.918l-3.575-2.014a.8.8 0 0 0-1.088.308");
}

.qgemki93n {
  cx: 7.76px;
  cy: 7.51px;
  rx: 0.168px;
  ry: 0.085px;
}

.qk1ct7bid {
  d: path("M8.815 9.19a1.3 1.3 0 0 1-.596-.14c-.059-.03-.122.036-.085.09a.81.81 0 0 0 .68.363a.81.81 0 0 0 .682-.364c.037-.055-.026-.12-.085-.09c-.173.09-.376.142-.596.142");
}

.qm7bfbbof {
  fill: var(--svg-color--000, #000);
  d: path("M8.096 7.73a.22.22 0 0 0-.22-.22a.22.22 0 0 0-.196.32h.39a.2.2 0 0 0 .026-.1m13.044-.004a.22.22 0 0 0-.22-.22a.22.22 0 0 0-.195.32h.39a.2.2 0 0 0 .026-.1");
}

.qny9bli6l {
  d: path("M21.272 7.681c0-.124-.101-.207-.128-.232l-.125.12l.077.156z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0quhfb0s {
  fill: var(--svg-color--ec9534, #EC9534);
  d: path("m12.729 19.944l-2.703.719L13.63 28.5a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.167-.234z");
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rlexyf32w {
  d: path("m5.26 13.392l2.828-1.586a.8.8 0 1 0-.781-1.396l-2.86 1.612z");
}

.rpvc_qtwj {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M19.694 7.426a.412.412 0 0 0 .036.809q-.023-.405-.036-.81");
}

.rsxhsvbfc {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M7.348 6.616a1.2 1.2 0 0 1 .748-.155a.12.12 0 1 1-.03.238a.95.95 0 0 0-.628.143l-.007.005H7.43a.12.12 0 0 1-.146-.188z");
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.so_94lbpe {
  d: path("m18.96 20.237l2.997.27l-1.063 7.94a1.83 1.83 0 0 1-1.812 1.584a.12.12 0 0 1-.122-.122z");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.stug43bab {
  stop-color: var(--svg-color--ebb432, #EBB432);
}

.suuif295x {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M23.816 3.271c-.221.71-.522 1.166-.644 1.305l-.633-.242c.013-.182.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.403.078 1.29");
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t8-ux1zkq {
  stop-color: var(--svg-color--461e67, #461E67);
  stop-opacity: 0;
}

.tcbf7abst {
  fill: var(--svg-color--654470, #654470);
  d: path("M8.787 9.944a2.87 2.87 0 0 0-2.872 2.872v8.185h2.932l.207-1.551a.175.175 0 0 1 .33-.054l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.87 2.87 0 0 0-2.872-2.872");
}

.tdgu1u54k {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
  stop-opacity: 0;
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.tw89kdb7m {
  d: path("M19.769 8.479a.7.7 0 0 1-.39-.133v.4c0 .384.23.727.578.869a1.8 1.8 0 0 1-.15-.508z");
}

.u61ql_uag {
  stop-color: var(--svg-color--db8723, #DB8723);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.uc21wsnks {
  d: path("M23.142 7.676a.36.36 0 0 0-.1-.2l-.112.123l.05.099z");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v7zd-lrql {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M6.648 7.43a.412.412 0 0 0 .036.809q-.023-.405-.036-.81");
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vqz6-acsp {
  fill: var(--svg-color--ffbc3b, #FFBC3B);
  fill-rule: evenodd;
  d: path("M21.44 10.714a.8.8 0 0 1-.307 1.088l-3.527 1.978a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 0 1-1.069 1.191l-1.973-1.72c-.93-.821-.855-2.149.348-2.918l3.574-2.015a.8.8 0 0 1 1.089.308");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.w8-yfvy3r {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m9.496 9.14l.062.04a.135.135 0 0 0-.015-.17a.14.14 0 0 0-.166-.028a1.2 1.2 0 0 1-.562.134c-.207 0-.4-.05-.561-.133h-.001a.14.14 0 0 0-.167.028a.134.134 0 0 0-.014.17a.89.89 0 0 0 .743.397a.89.89 0 0 0 .744-.398zm0 0a.81.81 0 0 1-.681.363a.81.81 0 0 1-.681-.364c-.037-.053.026-.12.085-.09c.172.09.378.142.596.142c.22 0 .423-.052.596-.142c.059-.03.122.035.085.09Z");
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wmhzuccfs {
  d: path("m25.549 13.388l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.504l3.202 1.808z");
}

.woynzybua {
  d: path("m8.915 5.53l-.029-.06a.29.29 0 0 0-.264-.18h-.548c-.794 0-1.437.651-1.437 1.454v.118c-.146-.111-.33-.346-.33-.726c0-.46.336-.694.55-.842c.061-.042.112-.078.143-.11l.043-.044c.15-.16.418-.444.886-.568q.093-.025.188-.04c.466-.077.807.342.807.815v.177z");
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.ws-68yb9o {
  stop-color: var(--svg-color--f6a928, #F6A928);
  stop-opacity: 0;
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x_wj4vl5i {
  stop-color: var(--svg-color--ce7557, #CE7557);
}

.x9ra_-b_q {
  fill: var(--svg-color--ffc93a, #FFC93A);
  fill-rule: evenodd;
  d: path("M22.414 10.714a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.191l1.974-1.72c.93-.821.855-2.149-.348-2.918l-3.574-2.015a.8.8 0 0 0-1.089.308");
}

.xhhozw94f {
  stop-color: var(--svg-color--ffbf38, #FFBF38);
  stop-opacity: 0;
}

.xhiabvblh {
  d: path("M8.787 9.944a2.87 2.87 0 0 0-2.872 2.872v8.185h2.932l.207-1.551a.175.175 0 0 1 .33-.054l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.87 2.87 0 0 0-2.872-2.872");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xlep1wb3b {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M20.409 6.733c.11-.08.387-.22.713-.165");
}

.xr6u_bcdu {
  d: path("M10.906 8.482a.7.7 0 0 0 .389-.132v.4a.93.93 0 0 1-.577.869q.11-.235.149-.508z");
}

.xw-0u-b6x {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M19.982 3.271c.221.71.522 1.166.644 1.305l.633-.242c-.013-.182-.096-.709-.324-1.356c-.286-.808-.579-1.09-.875-.996c-.211.086-.356.403-.078 1.29");
}

.xw85bn2ef {
  d: path("m24.102 6.976l-.012-.272a.63.63 0 0 0-.605-.613h-.602c-.383 0-.731-.209-.914-.542c0 0 .31-.894.824-.778c.376.085.777.218 1.085.418c.75.49.619 1.372.224 1.787");
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yj4wxr9mo {
  d: path("M20.921 7.341a.384.384 0 0 0-.37.486h.742a.387.387 0 0 0-.372-.486");
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.z4l_qbmxy {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("m23.994 8.238l.048-.82a.412.412 0 0 1-.048.82");
}

.z60z6abmj {
  d: path("M8.227 7.685c0-.124-.101-.207-.129-.232l-.124.12l.076.156z");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zft9nkbvg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.726 7.427c.027.036-.03.08-.095.13c-.065.048-.113.082-.14.045c-.028-.036.003-.105.068-.154c.065-.048.14-.058.167-.022");
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
