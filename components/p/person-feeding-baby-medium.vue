<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i0cXELe)" class="u472udtmk"/><path fill="url(#i9vu5ad)" class="wrfh3bbph"/><path fill="url(#i0Fsh4d)" class="ya90o75qt"/><path fill="url(#iBthpQb)" class="j81hq0key"/><g filter="url(#iu4E7Ld)"><path fill="url(#i5jsX5b)" class="by_iy321r"/><path fill="url(#i6nDCkc)" class="by_iy321r"/></g><path fill="url(#iNK1psd)" class="by_iy321r"/><path fill="url(#i9hdcMe)" class="by_iy321r"/><path fill="url(#imaDlvc)" class="by_iy321r"/><path fill="url(#iNS93cd)" class="by_iy321r"/><path fill="url(#iCbHhde)" class="by_iy321r"/><path fill="url(#iHGe4zM)" class="by_iy321r"/><path fill="url(#iW6nwHc)" class="by_iy321r"/><g filter="url(#iqo4dCh)"><path class="ml6rtcc9f"/></g><g filter="url(#inZR4Qd)"><path class="x2q6kabxm"/><path fill="url(#iBuvoGe)" class="gr5-tv_ip"/><path fill="url(#id5KCok)" class="gr5-tv_ip"/><path fill="url(#iJPnFqb)" class="gr5-tv_ip"/><path fill="url(#iU2bM0E)" class="gr5-tv_ip"/></g><g filter="url(#ix2sw5f)"><path fill="url(#iZUoWCc)" class="b4lu6q1yh"/></g><g filter="url(#iiXlKKe)"><path stroke="url(#iXIADEb)" class="sktc_abyw"/></g><path fill="url(#iqUhabJ)" class="l1yq-pooc"/><g filter="url(#iBzIy0d)"><path fill="url(#iRSzgme)" class="em_qdinnq"/></g><path fill="url(#iTJTxLe)" class="em_qdinnq"/><path fill="url(#iuH63fb)" class="em_qdinnq"/><path fill="url(#iKQCvHc)" class="em_qdinnq"/><g filter="url(#iLpd5CF)"><path class="gd3kk7bqc"/></g><g filter="url(#iMq5rEe)"><path class="jbozhyz4d"/></g><g filter="url(#ijQIsbb)"><path class="xqykxnsoa"/><path fill="url(#iLlG4id)" class="q9_ln2bph"/><path fill="url(#ighko6b)" class="q9_ln2bph"/></g><g filter="url(#iCIrXhd)"><path class="wjl4__b-c"/><path fill="url(#izUYfhc)" class="y9-rhby4w"/><path fill="url(#ipfKood)" class="y9-rhby4w"/><path fill="url(#iVWTs1d)" class="y9-rhby4w"/></g><path fill="url(#iyGHwOe)" class="m_8g56b-m"/><path fill="url(#i1SVLrc)" class="m_8g56b-m"/><path fill="url(#iyfeWJe)" class="m_8g56b-m"/><path fill="url(#i3qq2yd)" class="m_8g56b-m"/><path fill="url(#ilwCwfb)" class="v1k3r9-8r"/><path fill="url(#idIKHyd)" class="v1k3r9-8r"/><g filter="url(#iO46Jgc)"><path fill="url(#iCG8dub)" class="hagrvbcdu"/></g><g filter="url(#iSHrgWd)"><path fill="url(#iXGOcSb)" class="s9c7twvxm"/></g><g filter="url(#ihgCCNd)"><path class="vn6kfv0ms"/></g><g filter="url(#ipGRv9b)"><path class="baevlww3u"/></g><g filter="url(#irR9YNb)"><path class="cctz_6bri"/></g><path fill="url(#iYwAgxc)" class="abhde1bmv"/><path fill="url(#ioqivvd)" class="tn24eholg"/><path fill="url(#ivHtuwb)" class="tn24eholg"/><path fill="url(#iqKdPGd)" class="tn24eholg"/><path fill="url(#iuAN1md)" class="tn24eholg"/><path fill="url(#iRXOcsb)" class="tn24eholg"/><path fill="url(#iTc3xnd)" class="tn24eholg"/><g filter="url(#iboopcc)"><path fill="url(#iCAHHbb)" class="dn3lh-gct"/><path fill="url(#iDFCzZc)" class="dn3lh-gct"/><path fill="url(#ifxCHbj)" class="dn3lh-gct"/></g><path fill="url(#ibixdgb)" class="dw05-vhfv"/><g filter="url(#ifPpkvf)"><path fill="url(#ikDNvuc)" class="q1r5kqy_w"/><path fill="url(#ibeGbbe)" class="q1r5kqy_w"/></g><g filter="url(#igCkyBc)"><path class="nmy_ogamm"/><path fill="url(#iuPfaUb)" class="elwka3n6r"/><path fill="url(#i3NG4nH)" class="elwka3n6r"/><path fill="url(#iKz6PUb)" class="elwka3n6r"/><path fill="url(#iA8hGib)" class="elwka3n6r"/></g><path fill="url(#iOOocwe)" class="z2ql4irrz"/><path fill="url(#iDrF2Ab)" class="z2ql4irrz"/><path fill="url(#ig6scfc)" class="z1xr1obdf"/><path fill="url(#iinMjnV)" class="z1xr1obdf"/><path fill="url(#irgF5ud)" class="hxr33ezvb"/><path fill="url(#iLbfeNd)" class="hxr33ezvb"/><path fill="url(#i1jksIc)" class="hxr33ezvb"/><path fill="url(#iTAI3Gm)" class="hxr33ezvb"/><path fill="url(#iYzUNVB)" class="opmb0pk6u"/><path fill="url(#iICYRmd)" class="s3-m7pceq"/><path fill="url(#i4qub7c)" class="lkx4v1xdj"/><path fill="url(#iLGS8qS)" class="lkx4v1xdj"/><path fill="url(#iojtFGb)" class="lkx4v1xdj"/><g filter="url(#ijd9mdb)"><path stroke="url(#i9bybad)" class="h9uy0bb4r"/></g><path fill="url(#i2nzNyd)" class="cwtc4mbxd"/><path fill="url(#iz10SHd)" class="cwtc4mbxd"/><path fill="url(#ii2YhNc)" class="fyn2ygxce"/><g filter="url(#iQerqrQ)"><path fill="url(#iCbdX4d)" class="jz54v8b4w"/><path fill="url(#io1xCRc)" class="jz54v8b4w"/><path fill="url(#iElFXkc)" class="jz54v8b4w"/></g><path fill="url(#iWURoHe)" class="wduj-_bxv"/><path fill="url(#i9NQReb)" class="wduj-_bxv"/><path fill="url(#iH43cSb)" class="wduj-_bxv"/><path fill="url(#idJDmLc)" class="wduj-_bxv"/><path class="dz2p-le2f"/><path fill="url(#ip32fhb)" class="hv0sn0slj"/><path fill="url(#idTEYlc)" class="hv0sn0slj"/><path class="wm10atbak"/><path fill="url(#iSWCvHb)" class="h2qh2aczg"/><path fill="url(#ilq3Bsd)" class="h2qh2aczg"/><path fill="url(#iS5ptSd)" class="h2qh2aczg"/><path fill="url(#iOzlD4d)" class="ul8vz-ser"/><path fill="url(#iD0d6Mc)" class="ul8vz-ser"/><path fill="url(#iWdD7Zd)" class="ul8vz-ser"/><path fill="url(#iv7Qbic)" class="ul8vz-ser"/><path fill="url(#irzCDye)" class="o2m1utgzr"/><path fill="url(#iUgr0dd)" class="o2m1utgzr"/><path fill="url(#iHKeNwd)" class="o2m1utgzr"/><path fill="url(#iLsxaVs)" class="o2m1utgzr"/><path fill="url(#iSFWUOc)" class="o2m1utgzr"/><path fill="url(#iV0J7qc)" class="f5fsv_bdc"/><path fill="url(#i2IVTqY)" class="f5fsv_bdc"/><path fill="url(#iqnniYc)" class="f5fsv_bdc"/><path fill="url(#itr60Wb)" class="f5fsv_bdc"/><g filter="url(#iv0cywb)"><path stroke="url(#i2kOhGc)" class="c9odj9b-x"/></g><g filter="url(#iVJXfZZ)" class="mc2zb0bvp"><path class="d5ljj9b3p"/></g><g filter="url(#iqMvqie)" class="mc2zb0bvp"><path class="g_zooobib"/></g><g filter="url(#i1I7I8d)"><circle fill="url(#iNc8tfe)" class="q18fwpb8w"/></g><g filter="url(#irXWMBe)"><circle fill="url(#iA2Uspe)" class="jr7uk4opb"/></g><path fill="url(#iRcE0Rd)" class="p6vqj0gqz"/><path fill="url(#i4F7QAb)" class="vjpdbhbmu"/><g filter="url(#ivjBYze)" class="i5de26xkm"><path stroke="url(#ipnNFdc)" class="l4a0f-bsf"/><path stroke="url(#i1dOc3b)" class="l4a0f-bsf"/></g><g filter="url(#iF1GPwb)" class="i5de26xkm"><path stroke="url(#itB8rmb)" class="d17-qm-6u"/><path stroke="url(#iYSQL1d)" class="d17-qm-6u"/></g><defs><radialGradient id="i0Fsh4d" cx="0" cy="0" r="1" gradientTransform="matrix(1.07705 1.91633 -2.27645 1.27945 19.838 11.617)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iBthpQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5624 .23218 -.7163 4.82009 9.022 13.836)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="i5jsX5b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.74216 .75066 -1.32791 -8.38884 17.728 10.979)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="i6nDCkc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29702 3.1838 -2.62848 -1.07079 16.55 6.02)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="i9hdcMe" cx="0" cy="0" r="1" gradientTransform="matrix(.78488 -2.38268 6.72827 2.21637 13.795 17.369)" gradientUnits="userSpaceOnUse"><stop class="q4bkrlb2z"/><stop offset="1" class="b4563b7wv"/></radialGradient><radialGradient id="imaDlvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10938 -1.73437 19.45276 -1.22676 15.984 17.974)" gradientUnits="userSpaceOnUse"><stop class="xhu-djkme"/><stop offset="1" class="foyn8ud8a"/></radialGradient><radialGradient id="iNS93cd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.47747 1.89603 -4.8434 -21.65568 18.515 11.875)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iCbHhde" cx="0" cy="0" r="1" gradientTransform="matrix(2.9472 -3.47966 1.02783 .87055 7.617 9.755)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iHGe4zM" cx="0" cy="0" r="1" gradientTransform="rotate(86.373 5.961 14.466)scale(2.55971 1.02322)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iW6nwHc" cx="0" cy="0" r="1" gradientTransform="matrix(.13905 .87847 -1.6864 .26693 12.585 11.28)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="id5KCok" cx="0" cy="0" r="1" gradientTransform="matrix(.03895 .24607 -.77336 .12242 15.585 12.724)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iU2bM0E" cx="0" cy="0" r="1" gradientTransform="matrix(-1.586 1.02611 -1.64905 -2.54884 15.611 12.13)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iqUhabJ" cx="0" cy="0" r="1" gradientTransform="matrix(2.02839 -1.42952 5.75134 8.16072 14.98 15.156)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iTJTxLe" cx="0" cy="0" r="1" gradientTransform="rotate(-78.021 10.836 -.257)scale(7.81338 11.0871)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iuH63fb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57681 -6.36312 9.02921 -3.65647 20.317 8.641)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iKQCvHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52114 -2.2214 2.62242 -1.79574 17.17 4.708)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iLlG4id" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21885 .35123 -.13036 -.8235 14.006 4.138)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="ighko6b" cx="0" cy="0" r="1" gradientTransform="rotate(-66.719 11.302 -2.254)scale(6.15079 6.81444)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="izUYfhc" cx="0" cy="0" r="1" gradientTransform="matrix(3.09195 -3.41371 5.29052 4.79185 16.092 6.448)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="ipfKood" cx="0" cy="0" r="1" gradientTransform="matrix(2.56014 -3.14166 5.75158 4.68696 17.013 7.602)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iVWTs1d" cx="0" cy="0" r="1" gradientTransform="rotate(3.66 -84.477 251.05)scale(3.37367 1.41249)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="i1SVLrc" cx="0" cy="0" r="1" gradientTransform="rotate(65.353 2.08 20.019)scale(2.37767 2.26848)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iyfeWJe" cx="0" cy="0" r="1" gradientTransform="matrix(.62162 -1.21551 1.01884 .52104 19.858 10.272)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="i3qq2yd" cx="0" cy="0" r="1" gradientTransform="matrix(.34434 -1.65657 2.2134 .46008 20 10.427)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="idIKHyd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6716 .2646 -.29547 -1.86659 9.902 11.947)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iCG8dub" cx="0" cy="0" r="1" gradientTransform="matrix(-.89876 .30482 -.31254 -.9215 9.903 11.95)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iqKdPGd" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 3.1875 -3.62585 .24883 8.716 21.086)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="bzi-27bxc"/><stop offset="1" class="brh-pzb_h"/></radialGradient><radialGradient id="iuAN1md" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.466 19.804)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="lwl1xgbup"/><stop offset="1" class="kar3bi73q"/></radialGradient><radialGradient id="iRXOcsb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.674 30.46)" gradientUnits="userSpaceOnUse"><stop class="ijdg6fbam"/><stop offset="1" class="sjvismp2t"/></radialGradient><radialGradient id="iCAHHbb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 17.014 25.242)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iDFCzZc" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 15 10.359)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="ifxCHbj" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.185 26.18)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="ibixdgb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.038 1.01561 -1.51165 -8.987 27.348 23.29)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="ikDNvuc" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.066 12.957)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="ibeGbbe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.878 25.96)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="iuPfaUb" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -38.552 40.79)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="mu_dstxav"/><stop offset="1" class="vr5bp_bxf"/></radialGradient><radialGradient id="i3NG4nH" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 13 30.46)" gradientUnits="userSpaceOnUse"><stop class="vc2ezub_b"/><stop offset="1" class="pdof6qbxo"/></radialGradient><radialGradient id="iA8hGib" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02913 0 0 -3.40472 19.34 29.4)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="h5yda4bml"/><stop offset="1" class="xmthgnb3w"/></radialGradient><radialGradient id="iinMjnV" cx="0" cy="0" r="1" gradientTransform="rotate(168.154 12.847 14.99)scale(6.54566 1.70736)" gradientUnits="userSpaceOnUse"><stop class="kcxizyr3a"/><stop offset="1" class="uz8nvn0bw"/></radialGradient><radialGradient id="irgF5ud" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.842 20.336)" gradientUnits="userSpaceOnUse"><stop class="phzm4snim"/><stop offset="1" class="czerk-92m"/></radialGradient><radialGradient id="iLbfeNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.982 21.308)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="wyqcze2zy"/><stop offset="1" class="r6dyzpbfo"/></radialGradient><radialGradient id="i1jksIc" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.24 20.945)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="r1y6vkpka"/><stop offset="1" class="xrzwqzb7j"/></radialGradient><radialGradient id="iTAI3Gm" cx="0" cy="0" r="1" gradientTransform="rotate(153.654 1.858 11.49)scale(2.61542 2.57494)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tz2l_he6k"/><stop offset="1" class="twkrvc03o"/></radialGradient><radialGradient id="iojtFGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.086 18.936)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="i9bybad" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.388 23.477)" gradientUnits="userSpaceOnUse"><stop class="gmelrdffb"/><stop offset="1" class="khl528bkl"/></radialGradient><radialGradient id="iz10SHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.898 18.276)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="io1xCRc" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -35.627 34.651)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="i9NQReb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.531 18.923)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="i9r9kkbqw"/><stop offset="1" class="e16i7e3de"/></radialGradient><radialGradient id="iH43cSb" cx="0" cy="0" r="1" gradientTransform="rotate(119.595 -.145 11.98)scale(3.70167 1.33422)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="e7zd_qbyg"/><stop offset="1" class="sv2l0pbpa"/></radialGradient><radialGradient id="idJDmLc" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 1.04772 -1.07633 .16051 9.086 21.102)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="b1nef-bor"/><stop offset="1" class="jcycylcex"/></radialGradient><radialGradient id="ip32fhb" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.797 17.985)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="lp7kx4bze"/><stop offset="1" class="hbjsfnbqm"/></radialGradient><radialGradient id="idTEYlc" cx="0" cy="0" r="1" gradientTransform="matrix(.82031 .17968 -.24565 1.1215 9.89 16.57)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="jwxh3bbfb"/><stop offset="1" class="r6a-j5bnt"/></radialGradient><radialGradient id="iSWCvHb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.524 2.47)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="kyubtxb-o"/><stop offset="1" class="a0y-a0b2f"/></radialGradient><radialGradient id="ilq3Bsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.89 17.982)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="vhb97r3hm"/><stop offset="1" class="m9i-5tkbo"/></radialGradient><radialGradient id="iS5ptSd" cx="0" cy="0" r="1" gradientTransform="matrix(.61328 .25 -.50554 1.24016 9.605 17.43)" gradientUnits="userSpaceOnUse"><stop class="xaxho9f-m"/><stop offset="1" class="g_ars-u5d"/></radialGradient><radialGradient id="iOzlD4d" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.51562 -5.32458 -2.85442 11.219 19.234)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="bkr4sabrv"/><stop offset="1" class="vy_5_bh0s"/></radialGradient><radialGradient id="iD0d6Mc" cx="0" cy="0" r="1" gradientTransform="matrix(1.85937 1.375 -.35309 .47747 11.765 19.484)" gradientUnits="userSpaceOnUse"><stop class="or_kejb-o"/><stop offset="1" class="a-of3kbjs"/></radialGradient><radialGradient id="iWdD7Zd" cx="0" cy="0" r="1" gradientTransform="matrix(-.3672 .53142 -1.08325 -.74848 12.138 19.258)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="eh5j-nbpx"/><stop offset="1" class="ih66ipb5v"/></radialGradient><radialGradient id="iv7Qbic" cx="0" cy="0" r="1" gradientTransform="rotate(-28.035 43.187 -8.4)scale(1.16737 2.05335)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="esfed8bwd"/><stop offset="1" class="n24z6jbtl"/></radialGradient><radialGradient id="irzCDye" cx="0" cy="0" r="1" gradientTransform="matrix(1.09945 -1.69165 1.88005 1.2219 8.945 21.93)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="wi_pdjbvv"/><stop offset="1" class="g5ydalx2k"/></radialGradient><radialGradient id="iUgr0dd" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .84935 -.34383 .46806 10.844 20.484)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="y2mfwqgbt"/><stop offset="1" class="wo3blnxxa"/></radialGradient><radialGradient id="iHKeNwd" cx="0" cy="0" r="1" gradientTransform="rotate(102.218 -3.107 14.363)scale(2.03036 4.87917)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="d-e4mcb8q"/><stop offset=".962" class="cts2nkbix"/></radialGradient><radialGradient id="iLsxaVs" cx="0" cy="0" r="1" gradientTransform="matrix(.61483 -.19518 .6509 2.0503 7.878 20.954)" gradientUnits="userSpaceOnUse"><stop class="l_gp-_bkz"/><stop offset="1" class="j9v-nnbxs"/></radialGradient><radialGradient id="iSFWUOc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 -1.92189 3.39221 -2.75786 9.906 22.031)" gradientUnits="userSpaceOnUse"><stop offset=".832" class="u_sc2wgtl"/><stop offset="1" class="iwejj4bye"/></radialGradient><radialGradient id="i2IVTqY" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .895 16.057)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iqnniYc" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .776 16.534)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="itr60Wb" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.382 10.523)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="i2kOhGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.844 22.276)" gradientUnits="userSpaceOnUse"><stop class="zmq4c2bxg"/><stop offset="1" class="trma59b_r"/></radialGradient><radialGradient id="iNc8tfe" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 15.292 -4.562)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="za84p3bvp"/><stop offset=".876" class="ce24i9mgs"/></radialGradient><radialGradient id="iA2Uspe" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 16.987 -8.698)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l9fq7mbnb"/><stop offset=".535" class="lsc-rb3tr"/></radialGradient><radialGradient id="iRcE0Rd" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 11.383 11.614)" gradientUnits="userSpaceOnUse"><stop class="c60wuxbym"/><stop offset="1" class="u0tz8ubiy"/></radialGradient><radialGradient id="i4F7QAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 16.013 10.804)" gradientUnits="userSpaceOnUse"><stop class="c60wuxbym"/><stop offset="1" class="u0tz8ubiy"/></radialGradient><radialGradient id="i1dOc3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 13.555 11.248)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="f34_pj_2t"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="x-g1cc54o"/></radialGradient><radialGradient id="iYSQL1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 18.185 10.441)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="f34_pj_2t"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="x-g1cc54o"/></radialGradient><linearGradient id="i0cXELe" x1="19.3" x2="12.412" y1="19.065" y2="30.742" gradientUnits="userSpaceOnUse"><stop class="iezg62obf"/><stop offset="1" class="w444cbj2i"/></linearGradient><linearGradient id="i9vu5ad" x1="15.761" x2="17.294" y1="17.695" y2="18.679" gradientUnits="userSpaceOnUse"><stop offset=".177" class="zj6u44_3u"/><stop offset="1" class="ir2k-kbpd"/></linearGradient><linearGradient id="iNK1psd" x1="20.364" x2="17.816" y1="12.302" y2="12.706" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iBuvoGe" x1="15.85" x2="15.011" y1="11.973" y2="12.142" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iJPnFqb" x1="15.187" x2="15.113" y1="13.255" y2="12.786" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iZUoWCc" x1="14.712" x2="14.944" y1="10.307" y2="11.534" gradientUnits="userSpaceOnUse"><stop class="l69ut4_ru"/><stop offset="1" class="ep7pobc5p"/></linearGradient><linearGradient id="iXIADEb" x1="14.226" x2="14.414" y1="15.03" y2="14.138" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iRSzgme" x1="20.9" x2="9.196" y1="4.625" y2="6.478" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iyGHwOe" x1="21.252" x2="20.382" y1="9.557" y2="11.944" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="ilwCwfb" x1="8.981" x2="10.43" y1="12.227" y2="11.866" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iXGOcSb" x1="20.211" x2="20.492" y1="9.402" y2="11.175" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="iYwAgxc" x1="23.345" x2="27.191" y1="24.802" y2="29.379" gradientUnits="userSpaceOnUse"><stop class="d0ocakaur"/><stop offset="1" class="u_vqqhk3b"/></linearGradient><linearGradient id="ioqivvd" x1="9.185" x2="3.716" y1="26.773" y2="25.304" gradientUnits="userSpaceOnUse"><stop class="hbzm4jmfo"/><stop offset="1" class="hzk1ijbie"/></linearGradient><linearGradient id="ivHtuwb" x1="3.591" x2="5.404" y1="26.398" y2="27.054" gradientUnits="userSpaceOnUse"><stop class="dm21qhbor"/><stop offset="1" class="xvwmp6tlw"/></linearGradient><linearGradient id="iTc3xnd" x1="9.306" x2="8.913" y1="28.791" y2="28.666" gradientUnits="userSpaceOnUse"><stop class="icorotc4i"/><stop offset="1" class="deg8fdc9j"/></linearGradient><linearGradient id="iKz6PUb" x1="18.303" x2="17.643" y1="26.736" y2="27.631" gradientUnits="userSpaceOnUse"><stop offset=".175" class="d9x2ylwjm"/><stop offset="1" class="ow_pc7b8u"/></linearGradient><linearGradient id="iOOocwe" x1="19.471" x2="19.471" y1="27.094" y2="30.461" gradientUnits="userSpaceOnUse"><stop class="di46q3nvv"/><stop offset="1" class="bhzzakkbd"/></linearGradient><linearGradient id="iDrF2Ab" x1="19.599" x2="19.513" y1="27.023" y2="27.531" gradientUnits="userSpaceOnUse"><stop class="m9orc9b3r"/><stop offset="1" class="zegip2beb"/></linearGradient><linearGradient id="ig6scfc" x1="26.623" x2="27.06" y1="27.242" y2="30.961" gradientUnits="userSpaceOnUse"><stop class="xyrntivgr"/><stop offset="1" class="cjhyb2bbj"/></linearGradient><linearGradient id="iYzUNVB" x1="11.22" x2="11.074" y1="22.533" y2="19.89" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iICYRmd" x1="12.427" x2="12.04" y1="20.724" y2="18.742" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="i4qub7c" x1="16.154" x2="15.373" y1="18.523" y2="21.509" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="iLGS8qS" x1="15.281" x2="15.504" y1="21.729" y2="20.839" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="i2nzNyd" x1="15.029" x2="13.904" y1="17.758" y2="22.086" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="ii2YhNc" x1="15.341" x2="14.232" y1="18.132" y2="17.773" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="iCbdX4d" x1="14.529" x2="13.299" y1="17.648" y2="22.398" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="iElFXkc" x1="12.625" x2="12.844" y1="21.464" y2="20.385" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="iWURoHe" x1="8.498" x2="9.041" y1="17.148" y2="21.648" gradientUnits="userSpaceOnUse"><stop class="a79moebrw"/><stop offset="1" class="hkuv0zb-z"/></linearGradient><linearGradient id="iV0J7qc" x1="16.597" x2="16.013" y1="19.023" y2="21.523" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><linearGradient id="ipnNFdc" x1="11.477" x2="13.758" y1="11.656" y2="11.811" gradientUnits="userSpaceOnUse"><stop class="qfjvbh23z"/><stop offset="1" class="xpe1rlbew"/></linearGradient><linearGradient id="itB8rmb" x1="16.107" x2="18.388" y1="10.849" y2="11.004" gradientUnits="userSpaceOnUse"><stop class="qfjvbh23z"/><stop offset="1" class="xpe1rlbew"/></linearGradient><filter id="iu4E7Ld" width="11.906" height="12.676" x="9.306" y="5.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3538"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3538" result="effect2_innerShadow_4002_3538"/></filter><filter id="iqo4dCh" width="3.777" height="4.999" x="13.104" y="9.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".5"/></filter><filter id="inZR4Qd" width="2.308" height="3.398" x="13.951" y="10.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".1"/></filter><filter id="ix2sw5f" width="2.308" height="3.398" x="13.928" y="10.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".1"/></filter><filter id="iiXlKKe" width="3.747" height="1.84" x="13.454" y="13.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".05"/></filter><filter id="iBzIy0d" width="13.034" height="9.607" x="7.677" y="1.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3538"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3538" result="effect2_innerShadow_4002_3538"/></filter><filter id="iLpd5CF" width="2.428" height="1.048" x="15.989" y="7.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3538"/></filter><filter id="iMq5rEe" width="2.3" height="1.44" x="10.756" y="8.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3538"/></filter><filter id="ijQIsbb" width="6.432" height="6.763" x="8.074" y="3.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3538"/><feGaussianBlur result="effect2_foregroundBlur_4002_3538" stdDeviation=".125"/></filter><filter id="iCIrXhd" width="7.551" height="5.454" x="13.702" y="3.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3538"/><feGaussianBlur result="effect2_foregroundBlur_4002_3538" stdDeviation=".125"/></filter><filter id="iO46Jgc" width="1.499" height="2.382" x="8.716" y="10.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".125"/></filter><filter id="iSHrgWd" width="1.869" height="2.787" x="19.4" y="8.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".25"/></filter><filter id="ihgCCNd" width="2.358" height="1.398" x="10.675" y="8.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".125"/></filter><filter id="ipGRv9b" width="2.479" height=".982" x="15.963" y="7.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".125"/></filter><filter id="irR9YNb" width="5.572" height="2.527" x="14.946" y="3.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".375"/></filter><filter id="iboopcc" width="11.192" height="8.359" x="11.542" y="22.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3538"/></filter><filter id="ifPpkvf" width="7.407" height="8.444" x="19.124" y="19.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3538"/></filter><filter id="igCkyBc" width="8.208" height="4.667" x="12.492" y="25.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.419608 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3538"/></filter><filter id="ijd9mdb" width="3.456" height="1.701" x="7.457" y="22.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".1"/></filter><filter id="iQerqrQ" width="4.309" height="4.662" x="11.119" y="16.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3538"/></filter><filter id="iv0cywb" width="3.647" height="2.753" x="6.339" y="20.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".05"/></filter><filter id="iVJXfZZ" width="2.634" height="2.141" x="16.45" y="26.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".125"/></filter><filter id="iqMvqie" width="4.536" height="1" x="12.822" y="29.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".15"/></filter><filter id="i1I7I8d" width="3.987" height="3.987" x="10.476" y="8.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".325"/></filter><filter id="irXWMBe" width="3.987" height="3.987" x="15.065" y="7.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".325"/></filter><filter id="ivjBYze" width="2.323" height=".964" x="11.382" y="11.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".05"/></filter><filter id="iF1GPwb" width="2.323" height=".964" x="16.012" y="10.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3538" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-feeding-baby-medium" /></template>
<style>
.a-of3kbjs {
  stop-color: var(--svg-color--a87f6c, #A87F6C);
  stop-opacity: 0;
}

.a0y-a0b2f {
  stop-color: var(--svg-color--8d5c59, #8D5C59);
  stop-opacity: 0;
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.a79moebrw {
  stop-color: var(--svg-color--8e705c, #8E705C);
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.abhde1bmv {
  d: path("m29.221 25.8l-4.94-6.05l-3.16 8.57z");
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.b1nef-bor {
  stop-color: var(--svg-color--94596d, #94596D);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b4563b7wv {
  stop-color: var(--svg-color--8c5358, #8C5358);
  stop-opacity: 0;
}

.b4lu6q1yh {
  d: path("m14.376 10.676l-.243 1.938c-.049.399.274.738.646.68l.792-.126c.372-.059.573-.487.405-.845l-.83-1.769c-.18-.392-.715-.307-.77.122");
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.baevlww3u {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.067 7.965c-.288-.145-.986-.37-1.73-.12");
}

.bhzzakkbd {
  stop-color: var(--svg-color--d4453a, #D4453A);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bkr4sabrv {
  stop-color: var(--svg-color--ac866d, #AC866D);
}

.brh-pzb_h {
  stop-color: var(--svg-color--f36716, #F36716);
  stop-opacity: 0;
}

.by_iy321r {
  d: path("M10.476 14.983a3.996 3.996 0 0 0 4.46 2.813l1.901-.301a3.996 3.996 0 0 0 3.373-4.053c-.182-1.917-.361-3.827-.573-5.739a1.48 1.48 0 0 0-1.619-1.223l-1.411.223a2.47 2.47 0 0 1-2.46-1.101a.68.68 0 0 0-.686-.324l-1.283.204c-1.86.294-3.127 2.057-2.829 3.938c.297 1.876.706 3.702 1.127 5.563");
}

.bzi-27bxc {
  stop-color: var(--svg-color--f36716, #F36716);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c60wuxbym {
  stop-color: var(--svg-color--3a1f28, #3A1F28);
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.c9odj9b-x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.67 20.21c-.206.433-.32 1.45.874 2.056s1.993.148 2.243-.157");
}

.cctz_6bri {
  fill: var(--svg-color--725050, #725050);
  d: path("m18.436 5.067l-2.155.341a.506.506 0 1 1-.077-1.007c.573 0 1.335.007 1.851.052c1.168.1 1.565.598 1.713.975a1.59 1.59 0 0 0-1.332-.36");
}

.ce24i9mgs {
  stop-color: var(--svg-color--865a57, #865A57);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cjhyb2bbj {
  stop-color: var(--svg-color--ff5641, #FF5641);
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.cts2nkbix {
  stop-color: var(--svg-color--935067, #935067);
}

.cwtc4mbxd {
  d: path("m12.015 16.495l3.172.884c.43.125.744.558.627.96l-.899 3.085c-.115.396-.533.607-1.025.474l-3.129-.883z");
}

.czerk-92m {
  stop-color: var(--svg-color--cf482d, #CF482D);
}

.d-e4mcb8q {
  stop-color: var(--svg-color--935067, #935067);
  stop-opacity: 0;
}

.d0ocakaur {
  stop-color: var(--svg-color--ff3200, #FF3200);
}

.d17-qm-6u {
  d: path("M16.162 10.84c.15.14.547.37 1.062.273c.563-.106.888-.458.961-.64");
}

.d5ljj9b3p {
  stroke: var(--svg-color--c19885, #C19885);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.95 26.751l1.635 1.14");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d9x2ylwjm {
  stop-color: var(--svg-color--b99477, #B99477);
}

.deg8fdc9j {
  stop-color: var(--svg-color--ff451c, #FF451C);
  stop-opacity: 0;
}

.di46q3nvv {
  stop-color: var(--svg-color--ce5621, #CE5621);
}

.dm21qhbor {
  stop-color: var(--svg-color--d46751, #D46751);
}

.dn3lh-gct {
  d: path("M21.911 24.48c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.dw05-vhfv {
  d: path("M23.77 27.59a4.3 4.3 0 1 0 .001-8.6a4.3 4.3 0 0 0 0 8.6");
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dz2p-le2f {
  fill: var(--svg-color--a37e69, #A37E69);
  d: path("M10.175 16.922c.356.125.482.33.516.453l.445.39l2.292.363a.92.92 0 0 0 1.061-.872a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.434-.348.59");
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e16i7e3de {
  stop-color: var(--svg-color--6f3928, #6F3928);
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.e7zd_qbyg {
  stop-color: var(--svg-color--ab8870, #AB8870);
}

.eh5j-nbpx {
  stop-color: var(--svg-color--87624f, #87624F);
}

.elwka3n6r {
  d: path("M17.256 26.143a.937.937 0 0 0-1.12 1.498l.931.801a.1.1 0 0 1-.063.176l-3.643.072a.886.886 0 0 0 .017 1.77h6.06v-1l1.062-1.226z");
}

.em_qdinnq {
  d: path("M18.731 3.956a2.37 2.37 0 0 1 1.445.857a2.42 2.42 0 0 1 .297 2.564a1.6 1.6 0 0 0-.134.924l.19 1.197a1.8 1.8 0 0 0-.715-.163l-.178-1.632a1.48 1.48 0 0 0-1.618-1.224l-1.411.224a2.47 2.47 0 0 1-2.46-1.101a.68.68 0 0 0-.686-.324l-1.283.203c-1.86.295-3.127 2.058-2.829 3.939l.276 1.544c-.25.079-.504.207-.684.381l-.191-1.21a1.6 1.6 0 0 0-.412-.838a2.44 2.44 0 0 1-.535-2.442a2.4 2.4 0 0 1 1.13-1.342a2.74 2.74 0 0 0 1.218-1.34a2.37 2.37 0 0 1 2.768-1.38a1.52 1.52 0 0 0 1.203-.19a2.4 2.4 0 0 1 .89-.336a2.37 2.37 0 0 1 2.185.824c.391.464.937.76 1.534.865");
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.ep7pobc5p {
  stop-color: var(--svg-color--a2756b, #A2756B);
  stop-opacity: 0;
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.esfed8bwd {
  stop-color: var(--svg-color--947260, #947260);
}

.f34_pj_2t {
  stop-color: var(--svg-color--503a3b, #503A3B);
}

.f5fsv_bdc {
  d: path("m15.53 21.226l.227.068a.5.5 0 0 0 .492-.12l.364-.352a.13.13 0 0 1 .128-.033l.314.084a.484.484 0 0 0 .253-.936l-.303-.082a.13.13 0 0 1-.098-.109l-.069-.44a.5.5 0 0 0-.36-.404l-.26-.071z");
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.foyn8ud8a {
  stop-color: var(--svg-color--9e4c4a, #9E4C4A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.fyn2ygxce {
  d: path("m14.902 17.558l-2.636-.734l-1.073 3.895l2.6.734c.408.11.755-.065.851-.394l.78-2.703c.122-.392-.165-.694-.522-.798");
}

.g_ars-u5d {
  stop-color: var(--svg-color--997963, #997963);
  stop-opacity: 0;
}

.g_zooobib {
  stroke: var(--svg-color--ba8c83, #BA8C83);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.323 29.557h3.535");
}

.g5ydalx2k {
  stop-color: var(--svg-color--ba9374, #BA9374);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gd3kk7bqc {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M18.185 7.828c-.201-.126-.432-.257-.759-.305c-.322-.048-.71-.014-1.231.136a.283.283 0 1 0 .155.544c.476-.136.778-.152.992-.12c.21.03.362.111.542.224a.283.283 0 1 0 .3-.48");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gmelrdffb {
  stop-color: var(--svg-color--ff8040, #FF8040);
}

.gr5-tv_ip {
  d: path("m14.398 10.767l-.242 1.938c-.05.398.274.738.645.68l.793-.126c.372-.06.573-.488.404-.846l-.829-1.768c-.18-.392-.716-.308-.77.122");
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h2qh2aczg {
  d: path("M9.746 17.844c.243.25.33.526.343.633l.485.468l2.341.408a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.775-1.08c-1.09-.132-2.42-.304-2.779-.346c-.613-.07-.945.297-.64.61");
}

.h5yda4bml {
  stop-color: var(--svg-color--814c4e, #814C4E);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.h9uy0bb4r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.857 23.493c.578.14 1.919.172 2.656-.828");
}

.hagrvbcdu {
  d: path("M9.58 11.03a.975.975 0 0 0 .385 1.88a80 80 0 0 1-.384-1.88");
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbjsfnbqm {
  stop-color: var(--svg-color--936e63, #936E63);
  stop-opacity: 0;
}

.hbzm4jmfo {
  stop-color: var(--svg-color--f54c3c, #F54C3C);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hkuv0zb-z {
  stop-color: var(--svg-color--8e685c, #8E685C);
}

.hv0sn0slj {
  d: path("M10.175 16.922c.356.125.482.33.516.453l.445.39l2.292.363a.92.92 0 0 0 1.061-.872a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.434-.348.59");
}

.hxr33ezvb {
  d: path("M10.29 22.148c-.283.88-1.448 1.292-2.6.92s-1.792-1.178-1.572-2.266c.18-.888.883-1.75 2.738-1.24c1.152.372 1.718 1.705 1.434 2.585");
}

.hzk1ijbie {
  stop-color: var(--svg-color--e2492a, #E2492A);
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i5de26xkm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.i9r9kkbqw {
  stop-color: var(--svg-color--91576c, #91576C);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.icorotc4i {
  stop-color: var(--svg-color--ff451c, #FF451C);
}

.iezg62obf {
  stop-color: var(--svg-color--ff8427, #FF8427);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ih66ipb5v {
  stop-color: var(--svg-color--87624f, #87624F);
  stop-opacity: 0;
}

.ijdg6fbam {
  stop-color: var(--svg-color--fc4a51, #FC4A51);
}

.ir2k-kbpd {
  stop-color: var(--svg-color--c38265, #C38265);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iwejj4bye {
  stop-color: var(--svg-color--937160, #937160);
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j81hq0key {
  d: path("M10.197 13.462a1.67 1.67 0 0 1-.96-.167l.148.938c.142.9.806 1.618 1.674 1.822a4.2 4.2 0 0 1-.537-1.135z");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j9v-nnbxs {
  stop-color: var(--svg-color--8e655d, #8E655D);
  stop-opacity: 0;
}

.jbozhyz4d {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M10.967 8.858a2.83 2.83 0 0 1 1.696-.64a.283.283 0 0 1 .02.566a2.27 2.27 0 0 0-1.352.508a1 1 0 0 0-.083.075l-.003.003a.283.283 0 0 1-.412-.388z");
}

.jcycylcex {
  stop-color: var(--svg-color--945c6f, #945C6F);
  stop-opacity: 0;
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jr7uk4opb {
  cx: 17.059px;
  cy: 9.983px;
  r: 1.344px;
}

.jwxh3bbfb {
  stop-color: var(--svg-color--987763, #987763);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.jz54v8b4w {
  d: path("m12.243 16.925l2.635.735c.357.104.645.406.522.797l-.78 2.703c-.095.33-.442.505-.851.394l-2.6-.734z");
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.kar3bi73q {
  stop-color: var(--svg-color--d25e22, #D25E22);
  stop-opacity: 0;
}

.kcxizyr3a {
  stop-color: var(--svg-color--ff8a47, #FF8A47);
}

.khl528bkl {
  stop-color: var(--svg-color--ff8040, #FF8040);
  stop-opacity: 0;
}

.kloinabmx {
  stop-color: var(--svg-color--c26f5c, #C26F5C);
  stop-opacity: 0;
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.kyubtxb-o {
  stop-color: var(--svg-color--8d5c59, #8D5C59);
}

.l_gp-_bkz {
  stop-color: var(--svg-color--8e655d, #8E655D);
}

.l1yq-pooc {
  d: path("M15.36 14.346a3.1 3.1 0 0 1-1.45-.11c-.149-.049-.272.13-.165.242a1.93 1.93 0 0 0 1.73.6a1.93 1.93 0 0 0 1.462-1.105c.066-.145-.106-.272-.233-.18a3.05 3.05 0 0 1-1.344.553");
}

.l4a0f-bsf {
  d: path("M11.532 11.647c.15.14.547.37 1.062.273c.563-.106.888-.458.96-.64");
}

.l69ut4_ru {
  stop-color: var(--svg-color--a2756b, #A2756B);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.l9fq7mbnb {
  stop-color: var(--svg-color--c29579, #C29579);
}

.lkx4v1xdj {
  d: path("m15.606 18.326l.554.16a.15.15 0 0 1 .103.185l-.783 2.73a.15.15 0 0 1-.186.103l-.555-.16z");
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lp7kx4bze {
  stop-color: var(--svg-color--936e63, #936E63);
}

.lsc-rb3tr {
  stop-color: var(--svg-color--ae806d, #AE806D);
}

.lwl1xgbup {
  stop-color: var(--svg-color--d25e22, #D25E22);
}

.m_8g56b-m {
  d: path("M20.072 11.993q-.153-1.624-.323-3.247a1.643 1.643 0 0 1 .323 3.247");
}

.m9i-5tkbo {
  stop-color: var(--svg-color--a6816a, #A6816A);
  stop-opacity: 0;
}

.m9orc9b3r {
  stop-color: var(--svg-color--ae4614, #AE4614);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.ml6rtcc9f {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m14.41 10.967l-.302 1.948c-.042.397.263.74.609.685l.737-.117c.346-.055.53-.48.368-.84l-.792-1.774c-.171-.393-.573-.33-.62.098");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mu_dstxav {
  stop-color: var(--svg-color--905d66, #905D66);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n24z6jbtl {
  stop-color: var(--svg-color--8f6d5d, #8F6D5D);
  stop-opacity: 0;
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nmy_ogamm {
  fill: var(--svg-color--a77671, #A77671);
  d: path("M17.256 26.143a.937.937 0 0 0-1.12 1.498l.931.801a.1.1 0 0 1-.063.176l-3.643.072a.886.886 0 0 0 .017 1.77h6.06v-1l1.062-1.226z");
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o2m1utgzr {
  d: path("M8.933 21.39c-.314.22-.722.211-.906-.109c-.391-.948.721-1.58 1.5-1.598c1.168-.027 1.75.63 1.938 1.122s.226 1.476-.672 1.539c-.804.055-.848-.5-.98-.743c-.134-.242-.595-.41-.88-.21");
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.opmb0pk6u {
  d: path("m11.921 21.06l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.or_kejb-o {
  stop-color: var(--svg-color--c29c8a, #C29C8A);
}

.ow_pc7b8u {
  stop-color: var(--svg-color--b99477, #B99477);
  stop-opacity: 0;
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.p6vqj0gqz {
  d: path("M11.49 11.38c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34c-.19-.14-.11-.43.11-.47");
}

.pdof6qbxo {
  stop-color: var(--svg-color--98567e, #98567E);
  stop-opacity: 0;
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.phzm4snim {
  stop-color: var(--svg-color--ce6122, #CE6122);
}

.q18fwpb8w {
  cx: 12.47px;
  cy: 10.711px;
  r: 1.344px;
}

.q1r5kqy_w {
  d: path("M21.651 24.4a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.q4bkrlb2z {
  stop-color: var(--svg-color--8c5358, #8C5358);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q9_ln2bph {
  d: path("M14.237 5.73a3 3 0 0 1-.088-.128a.68.68 0 0 0-.687-.324l-1.284.203c-1.86.295-3.127 2.058-2.829 3.94l.044.277C9.01 9.492 8.491 9.01 8.35 8.12c-.171-1.08.53-1.751.978-2.179c.126-.12.233-.222.293-.308l.084-.122c.293-.43.815-1.194 1.866-1.659a5.6 5.6 0 0 1 1.51-.409c.468-.061.862.29.936.757l.239 1.513z");
}

.qfjvbh23z {
  stop-color: var(--svg-color--513a3b, #513A3B);
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r1y6vkpka {
  stop-color: var(--svg-color--b42c01, #B42C01);
}

.r6a-j5bnt {
  stop-color: var(--svg-color--987763, #987763);
  stop-opacity: 0;
}

.r6dyzpbfo {
  stop-color: var(--svg-color--a62302, #A62302);
  stop-opacity: 0;
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s3-m7pceq {
  d: path("M10.641 19.03c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.s9c7twvxm {
  d: path("M20.086 11.239q-.09-.894-.186-1.787c.413-.01.785.315.857.769c.077.488-.223.942-.672 1.018");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.sjvismp2t {
  stop-color: var(--svg-color--fc4a51, #FC4A51);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sktc_abyw {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.935 14.165a3 3 0 0 0 1.413.107a3 3 0 0 0 1.311-.539a.23.23 0 0 1 .28.002a.22.22 0 0 1 .066.269m-3.07.16l3.002-.191m-3.002.191h-.001a.23.23 0 0 0-.264.09a.215.215 0 0 0 .02.275m.245-.364l-.19.313m3.26-.474l-.068-.031m.068.03l-.068-.03m.068.03a2.01 2.01 0 0 1-1.518 1.15a2 2 0 0 1-1.797-.624m3.247-.556a1.93 1.93 0 0 1-1.461 1.105a1.93 1.93 0 0 1-1.731-.6m-.055.051l.055-.051m-.055.051l.055-.051");
}

.sv2l0pbpa {
  stop-color: var(--svg-color--8f715e, #8F715E);
  stop-opacity: 0;
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.tn24eholg {
  d: path("m2.277 30.46l2.93-9.156c.352-1.414 2.07-2.103 3.65-1.613s2.49 2.332 2.006 3.692L8.647 30.46z");
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.trma59b_r {
  stop-color: var(--svg-color--d1623d, #D1623D);
  stop-opacity: 0;
}

.twkrvc03o {
  stop-color: var(--svg-color--c24713, #C24713);
}

.tz2l_he6k {
  stop-color: var(--svg-color--c24713, #C24713);
  stop-opacity: 0;
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u_sc2wgtl {
  stop-color: var(--svg-color--937160, #937160);
  stop-opacity: 0;
}

.u_vqqhk3b {
  stop-color: var(--svg-color--ff9400, #FF9400);
}

.u0tz8ubiy {
  stop-color: var(--svg-color--3d2727, #3D2727);
}

.u472udtmk {
  d: path("M7.231 30.46c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ul8vz-ser {
  d: path("M8.597 18.941a.28.28 0 0 1 .133-.27c.981-.69 2.005-.304 2.383 0c.305.236 1 .79 1.363 1.082c.446.36.372.962.043 1.317c-.276.298-.751.24-.93.148l-2.097-1.312c-.055-.313-.235-.563-.48-.637c-.247-.074-.403-.133-.415-.328");
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uz8nvn0bw {
  stop-color: var(--svg-color--ff8a47, #FF8A47);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v1k3r9-8r {
  d: path("M9.516 10.353a1.656 1.656 0 0 0-1.148 1.833a1.64 1.64 0 0 0 1.79 1.377a80 80 0 0 1-.642-3.21");
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vc2ezub_b {
  stop-color: var(--svg-color--98567e, #98567E);
}

.vhb97r3hm {
  stop-color: var(--svg-color--c7a28d, #C7A28D);
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vjpdbhbmu {
  d: path("M16.12 10.57c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34a.263.263 0 0 1 .11-.47");
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vn6kfv0ms {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.05 9.134c.23-.227.824-.656 1.608-.648");
}

.vr5bp_bxf {
  stop-color: var(--svg-color--905d66, #905D66);
  stop-opacity: 0;
}

.vy_5_bh0s {
  stop-color: var(--svg-color--966464, #966464);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w444cbj2i {
  stop-color: var(--svg-color--fa362a, #FA362A);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wduj-_bxv {
  d: path("M8.207 17.703c1.03-1.086 1.919-1.37 2.32-1.375l.797.867l-.93 3.516c-.18.315-.564.996-.695 1.152c-.164.196-.735.63-1.766.239c-.887-.338-1.15-.899-1.176-1.149c.234-1.167.65-2.358 1.45-3.25");
}

.wi_pdjbvv {
  stop-color: var(--svg-color--935b6e, #935B6E);
}

.wjl4__b-c {
  fill: var(--svg-color--563936, #563936);
  d: path("m19.777 8.228l-.13-.632c-.132-.768-.869-1.302-1.644-1.213l-1.411.224a2.47 2.47 0 0 1-2.342-.931s-.089-.14-.194-.385c-.397-.922.402-1.798 1.404-1.766c1.02.032 2.207.185 3.13.598c1.94.869 1.959 2.985 1.187 4.105");
}

.wm10atbak {
  fill: var(--svg-color--a8836a, #A8836A);
  d: path("M9.746 17.844c.243.25.33.526.343.633l.485.468l2.341.408a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.775-1.08c-1.09-.132-2.42-.304-2.779-.346c-.613-.07-.945.297-.64.61");
}

.wo3blnxxa {
  stop-color: var(--svg-color--c7a08d, #C7A08D);
  stop-opacity: 0;
}

.wrfh3bbph {
  d: path("M15.761 18.99c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.wyqcze2zy {
  stop-color: var(--svg-color--a62302, #A62302);
}

.x-g1cc54o {
  stop-color: var(--svg-color--503a3b, #503A3B);
  stop-opacity: 0;
}

.x2q6kabxm {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m14.398 10.767l-.242 1.938c-.05.398.274.738.645.68l.793-.126c.372-.06.573-.488.404-.846l-.829-1.768c-.18-.392-.716-.308-.77.122");
}

.xaxho9f-m {
  stop-color: var(--svg-color--997963, #997963);
}

.xhu-djkme {
  stop-color: var(--svg-color--9e4c4a, #9E4C4A);
}

.xmthgnb3w {
  stop-color: var(--svg-color--814c4e, #814C4E);
  stop-opacity: 0;
}

.xpe1rlbew {
  stop-color: var(--svg-color--513a3b, #513A3B);
  stop-opacity: 0;
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xqykxnsoa {
  fill: var(--svg-color--533634, #533634);
  d: path("M14.237 5.73a3 3 0 0 1-.088-.128a.68.68 0 0 0-.687-.324l-1.284.203c-1.86.295-3.127 2.058-2.829 3.94l.044.277C9.01 9.492 8.491 9.01 8.35 8.12c-.171-1.08.53-1.751.978-2.179c.126-.12.233-.222.293-.308l.084-.122c.293-.43.815-1.194 1.866-1.659a5.6 5.6 0 0 1 1.51-.409c.468-.061.862.29.936.757l.239 1.513z");
}

.xrzwqzb7j {
  stop-color: var(--svg-color--b42c01, #B42C01);
  stop-opacity: 0;
}

.xvwmp6tlw {
  stop-color: var(--svg-color--e6422d, #E6422D);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xyrntivgr {
  stop-color: var(--svg-color--ff7c1e, #FF7C1E);
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y2mfwqgbt {
  stop-color: var(--svg-color--c7a08d, #C7A08D);
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y9-rhby4w {
  d: path("m19.777 8.228l-.13-.632c-.132-.768-.869-1.302-1.644-1.213l-1.411.224a2.47 2.47 0 0 1-2.342-.931s-.089-.14-.194-.385c-.397-.922.402-1.798 1.404-1.766c1.02.032 2.207.185 3.13.598c1.94.869 1.959 2.985 1.187 4.105");
}

.ya90o75qt {
  d: path("M19.996 11.91a1.67 1.67 0 0 0 .863-.455l.148.939c.143.9-.267 1.787-1.03 2.249q.173-.591.161-1.245z");
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.z1xr1obdf {
  d: path("M20.692 26.238c1.597-.23 4.566-.808 6.543-1.27c1.522-.262 2.64 1.204 2.64 2.782c0 1.371-1.022 2.236-1.746 2.618a.86.86 0 0 1-.404.093h-8.014v-3.086c0-.797.281-1 .98-1.137");
}

.z2ql4irrz {
  d: path("M19.075 27.244a.15.15 0 0 1 .15-.15h.642v3.367h-.793z");
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.za84p3bvp {
  stop-color: var(--svg-color--956f60, #956F60);
}

.zegip2beb {
  stop-color: var(--svg-color--ae4614, #AE4614);
  stop-opacity: 0;
}

.zj6u44_3u {
  stop-color: var(--svg-color--974f4f, #974F4F);
}

.zmq4c2bxg {
  stop-color: var(--svg-color--d1623d, #D1623D);
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
