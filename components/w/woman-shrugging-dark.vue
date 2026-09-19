<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iHHNzUb)" clip-rule="evenodd" class="gfod2bbij"/><g filter="url(#ik7gJ7d)"><path stroke="url(#iLIQ7fe)" class="plpm3y40t"/></g><path fill="url(#iRhavzp)" clip-rule="evenodd" class="so47whbnh"/><g filter="url(#iJmuK8b)"><path stroke="url(#il2nHBb)" class="vg-mzkb2l"/></g><path fill="url(#iAVO6pa)" clip-rule="evenodd" class="l533ei3qo"/><g filter="url(#ioPeASa)"><path stroke="url(#iG8bcKe)" class="aq2vj0bqy"/></g><path fill="url(#iQeRWfd)" clip-rule="evenodd" class="nhigy-yiu"/><path class="b_2l31nzi"/><path fill="url(#idslX4b)" class="mxpwktbey"/><path fill="url(#iaw0Gkd)" class="mxpwktbey"/><g filter="url(#ibFDOce)"><path class="otknywvoi"/><path fill="url(#iPrvWzb)" class="pb1uanbce"/><path fill="url(#iScnnfe)" class="pb1uanbce"/></g><path fill="url(#iVU3DLe)" clip-rule="evenodd" class="atps5cgtr"/><path fill="url(#ibvYt5D)" clip-rule="evenodd" class="atps5cgtr"/><path fill="url(#ihyipfd)" clip-rule="evenodd" class="atps5cgtr"/><path fill="url(#iQToV7O)" clip-rule="evenodd" class="atps5cgtr"/><path fill="url(#iUUxJVb)" clip-rule="evenodd" class="w_4_3bbcu"/><path fill="url(#iFbh2vw)" clip-rule="evenodd" class="w_4_3bbcu"/><path fill="url(#iVwWHYd)" clip-rule="evenodd" class="w_4_3bbcu"/><path fill="url(#ijPE46d)" clip-rule="evenodd" class="w_4_3bbcu"/><path fill="url(#iPMRSzv)" clip-rule="evenodd" class="m7s27ibhr"/><path fill="url(#i39HZvy)" clip-rule="evenodd" class="m7s27ibhr"/><path fill="url(#iRqj0kb)" clip-rule="evenodd" class="m7s27ibhr"/><path fill="url(#iJ1GVQd)" clip-rule="evenodd" class="m7s27ibhr"/><path fill="url(#iRmRpmc)" clip-rule="evenodd" class="ho71ipbar"/><path fill="url(#iETSitb)" clip-rule="evenodd" class="ho71ipbar"/><g filter="url(#irjlQ1d)"><path stroke="url(#iOyo40d)" class="gfpc_b4dg"/></g><g filter="url(#iBBwDze)"><path stroke="url(#iqLmHPe)" class="p_s_z07gj"/></g><g filter="url(#iZarSAd)"><path class="v33ia2knp"/></g><g filter="url(#iUWzU2b)"><path fill="url(#ihHO6Fc)" clip-rule="evenodd" class="hd1_19zwc"/><path fill="url(#i3pBrbc)" clip-rule="evenodd" class="hd1_19zwc"/><path fill="url(#icNaEPc)" clip-rule="evenodd" class="hd1_19zwc"/><path fill="url(#igAm3tc)" clip-rule="evenodd" class="hd1_19zwc"/><path fill="url(#iYUKs3c)" clip-rule="evenodd" class="hd1_19zwc"/><path fill="url(#iYsPKPd)" clip-rule="evenodd" class="hd1_19zwc"/><path fill="url(#i3nZrgn)" clip-rule="evenodd" class="hd1_19zwc"/><path fill="url(#inyiuRc)" clip-rule="evenodd" class="hd1_19zwc"/><path fill="url(#iGhQRme)" clip-rule="evenodd" class="hd1_19zwc"/><path fill="url(#ibQlgte)" clip-rule="evenodd" class="hd1_19zwc"/><path fill="url(#i9REQQc)" clip-rule="evenodd" class="hd1_19zwc"/></g><path fill="url(#i3BpiBd)" class="okhmxbclb"/><path fill="url(#iXJ3kCd)" class="okhmxbclb"/><path fill="url(#i8phwYc)" class="w1pfz9iya"/><g filter="url(#iNP6LPK)"><path fill="url(#ioSF9ve)" class="imzqxgplv"/><path fill="url(#i2LiaOc)" class="imzqxgplv"/><path fill="url(#i8fIPse)" class="imzqxgplv"/><path fill="url(#iswHC3b)" class="imzqxgplv"/><path fill="url(#ius8wHd)" class="imzqxgplv"/><path fill="url(#ixeLFse)" class="imzqxgplv"/><path fill="url(#iXXzjGe)" class="imzqxgplv"/></g><path fill="url(#i9E4wnk)" class="s-9lc-blc"/><g filter="url(#iPss7te)"><path class="jsb3wkbzc"/></g><g filter="url(#iwVWnMd)"><path class="golfcqbxg"/></g><g filter="url(#iUUKvcd)"><path stroke="url(#iDQACLO)" class="l93r40bgi"/></g><g filter="url(#i6YKPso)"><path fill="url(#iKGOuEd)" class="y87h-bcxa"/></g><g filter="url(#iNoPMfd)"><path fill="url(#iCamPGc)" class="d-hvev_it"/><path fill="url(#iRHnQKe)" class="d-hvev_it"/></g><g filter="url(#ibh1jve)"><path class="p6pttubsq"/><path fill="url(#i71jrxc)" class="w9bmuwbwu"/></g><g filter="url(#iLohmre)"><path class="fzkncnb-q"/><path fill="url(#ilhyRSc)" class="lv2o39i_t"/></g><g filter="url(#iD3XYve)"><path fill="url(#isdsf7x)" class="yed-8cx0y"/><path fill="url(#iBHS6he)" class="yed-8cx0y"/><path fill="url(#ijlwWFc)" class="yed-8cx0y"/><path fill="url(#ihHZp4b)" class="yed-8cx0y"/><path fill="url(#iSrcsPe)" class="yed-8cx0y"/><path fill="url(#i1GY3Sb)" class="yed-8cx0y"/><path fill="url(#is63eUb)" class="yed-8cx0y"/><path fill="url(#i9D1aYQ)" class="yed-8cx0y"/></g><path fill="url(#i9MxJFc)" class="yed-8cx0y"/><g filter="url(#iQ7sIDc)"><path class="m7cwrybrd"/></g><g filter="url(#ixBTyPc)"><path class="dcsgtkbzx"/><path fill="url(#iA3fMSd)" class="eqysr1ben"/><path fill="url(#iT3skWc)" class="eqysr1ben"/><path fill="url(#iSNUwPd)" class="eqysr1ben"/><path fill="url(#iR4OKud)" class="eqysr1ben"/></g><path fill="url(#iofGnlb)" class="eqysr1ben"/><path fill="url(#iILDoJb)" class="eqysr1ben"/><g filter="url(#ioctRvP)"><path class="j5s7e9vux"/></g><g filter="url(#iiith8c)"><path class="sy-i5vrnl"/></g><g filter="url(#i0CkVZX)"><path class="w30p1jble"/></g><g filter="url(#iMjFRGb)"><path clip-rule="evenodd" class="gso_3nbbg"/></g><path class="j2xk3ackf"/><path fill="url(#iQUqjjO)" class="oifg47bvk"/><path class="y8fls1pkq"/><g filter="url(#icqRvIU)"><path class="tb4wryb1h"/><path fill="url(#iVfVdbd)" class="mgujedcpg"/></g><g filter="url(#iM0bnwd)"><path fill="url(#ipe92Ee)" class="i7_2bobbl"/></g><path class="nxxy5ib6i"/><path fill="url(#iv8kUUN)" class="ftfq3_y5k"/><path class="xxdsqkpot"/><g filter="url(#iKMhPTb)"><path fill="url(#iRV0XYX)" class="z5em5hh2o"/></g><g filter="url(#i0CZfVd)"><ellipse transform="rotate(-32.704 13.527 12.029)" class="gc1ou3b7p"/><ellipse fill="url(#ilLwHOd)" transform="rotate(-32.704 13.527 12.029)" class="ushk2fb9i"/></g><g filter="url(#ikD8aud)"><path class="dke60rb2j"/></g><g filter="url(#ie6EW4b)"><path class="vy1fepq3p"/></g><g filter="url(#i04C6Ee)"><path class="aoh6fdm0m"/><path fill="url(#iiDq1se)" class="ft8nx4t0e"/><path fill="url(#iNXEGDe)" class="ft8nx4t0e"/></g><g filter="url(#ivxl4wo)"><path class="sl65zcqrd"/><path fill="url(#ix7jm6b)" class="b60zzincu"/><path fill="url(#iPtZhEe)" class="b60zzincu"/></g><g filter="url(#iTBcoWd)"><path stroke="url(#i2qcXae)" class="qis5bdcfc"/></g><g filter="url(#iH89a0b)"><path class="tb7ah0bdp"/></g><g filter="url(#i7pnVln)"><ellipse stroke="url(#iEVVKie)" class="nt-ywibkx"/></g><ellipse class="uxkjixbpm"/><defs><radialGradient id="iaw0Gkd" cx="0" cy="0" r="1" gradientTransform="matrix(-.52138 .86916 -1.0215 -.61276 7.016 11.13)" gradientUnits="userSpaceOnUse"><stop class="zvb7pjbrz"/><stop offset="1" class="zk7ulfu0q"/></radialGradient><radialGradient id="iScnnfe" cx="0" cy="0" r="1" gradientTransform="matrix(.85157 -.55469 .26705 .40998 26.232 11.38)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="mc3aerbdu"/><stop offset="1" class="p2xodcbta"/></radialGradient><radialGradient id="ibvYt5D" cx="0" cy="0" r="1" gradientTransform="matrix(1.0788 .95928 -3.2774 3.68572 26.918 12.581)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="r8nvtjbrg"/><stop offset="1" class="w_txxk5nx"/></radialGradient><radialGradient id="ihyipfd" cx="0" cy="0" r="1" gradientTransform="rotate(-136.326 16.57 .982)scale(1.45051 1.63903)" gradientUnits="userSpaceOnUse"><stop class="twf01ac1b"/><stop offset="1" class="zg5ree2ok"/></radialGradient><radialGradient id="iQToV7O" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 -.60937 .35181 .2616 28.552 11.63)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="mc3aerbdu"/><stop offset="1" class="p2xodcbta"/></radialGradient><radialGradient id="iFbh2vw" cx="0" cy="0" r="1" gradientTransform="rotate(45.859 -1.347 39.684)scale(1.46299 5.0306)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="r8nvtjbrg"/><stop offset="1" class="w_txxk5nx"/></radialGradient><radialGradient id="iVwWHYd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.109 17.511 .377)scale(1.4777 1.66303)" gradientUnits="userSpaceOnUse"><stop class="twf01ac1b"/><stop offset="1" class="zg5ree2ok"/></radialGradient><radialGradient id="ijPE46d" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -.54688 .3157 .37883 29.63 11.99)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="mc3aerbdu"/><stop offset="1" class="p2xodcbta"/></radialGradient><radialGradient id="i39HZvy" cx="0" cy="0" r="1" gradientTransform="matrix(1.10937 .9375 -3.17994 3.76294 27.922 13.885)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="r8nvtjbrg"/><stop offset="1" class="w_txxk5nx"/></radialGradient><radialGradient id="iRqj0kb" cx="0" cy="0" r="1" gradientTransform="rotate(-137.781 17.238 1.633)scale(1.45679 1.64014)" gradientUnits="userSpaceOnUse"><stop class="twf01ac1b"/><stop offset="1" class="zg5ree2ok"/></radialGradient><radialGradient id="iJ1GVQd" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 -.47656 .27377 .30518 29.74 13.013)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="mc3aerbdu"/><stop offset="1" class="p2xodcbta"/></radialGradient><radialGradient id="iETSitb" cx="0" cy="0" r="1" gradientTransform="matrix(.54297 -.42187 .23663 .30456 29.435 14.036)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="mc3aerbdu"/><stop offset="1" class="p2xodcbta"/></radialGradient><radialGradient id="i3pBrbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.20803 4.3309 -5.41017 -.25987 15.801 14.86)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="icNaEPc" cx="0" cy="0" r="1" gradientTransform="rotate(141.214 3.89 9.986)scale(3.27856 4.30777)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="igAm3tc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09372 1.70921 -1.31244 -.83982 11.353 13.076)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iYUKs3c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04632 2.08582 -1.46928 -.73704 11.619 11.135)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iYsPKPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.49717 2.34845 -3.26 2.0783 11.945 5.192)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i3nZrgn" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24076 1.46778 -2.0512 -1.73394 20.896 6.408)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="inyiuRc" cx="0" cy="0" r="1" gradientTransform="rotate(158.989 10.409 7.669)scale(1.81031 3.77527)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iGhQRme" cx="0" cy="0" r="1" gradientTransform="rotate(161.174 10.099 9.05)scale(2.73653 3.48593)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ibQlgte" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0584 -2.4188 1.91313 -.83714 20.075 9.027)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i9REQQc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4254 .02981 -.0483 2.30955 10.046 12.136)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i3BpiBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94297 -2.39063 0 26.203 16.095)" gradientUnits="userSpaceOnUse"><stop class="j0u7-u3qa"/><stop offset="1" class="w06d_xbwd"/></radialGradient><radialGradient id="i8phwYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.24766 -2.29189 0 7.369 16.228)" gradientUnits="userSpaceOnUse"><stop class="hk2gombwq"/><stop offset="1" class="zgf54gbaa"/></radialGradient><radialGradient id="ioSF9ve" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4411 10.6867 0 19.921 29.08)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="bfh6fzlxi"/><stop offset="1" class="lea4hbl2x"/></radialGradient><radialGradient id="i2LiaOc" cx="0" cy="0" r="1" gradientTransform="rotate(130.485 .365 12.11)scale(4.64639 1.15364)" gradientUnits="userSpaceOnUse"><stop class="k9011xajc"/><stop offset="1" class="upmwye1mi"/></radialGradient><radialGradient id="i8fIPse" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5323 -4.48916 1.47345 -.83116 24.516 26.757)" gradientUnits="userSpaceOnUse"><stop class="jlublfbcv"/><stop offset="1" class="h3d7w4j4j"/></radialGradient><radialGradient id="iswHC3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.46944 -4.08022 0 27.015 16.642)" gradientUnits="userSpaceOnUse"><stop class="vio74z7fz"/><stop offset="1" class="ey8rcibsm"/></radialGradient><radialGradient id="ius8wHd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2344 3.40893 -.52728 -.3456 9.719 19.82)" gradientUnits="userSpaceOnUse"><stop class="cgtm3g8-v"/><stop offset="1" class="dol2bxb1e"/></radialGradient><radialGradient id="ixeLFse" cx="0" cy="0" r="1" gradientTransform="matrix(-5.37502 3.24997 -1.62756 -2.69176 14.594 16.969)" gradientUnits="userSpaceOnUse"><stop class="p1da4obcx"/><stop offset="1" class="rqpemmbby"/></radialGradient><radialGradient id="iXXzjGe" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 6.13908 -2.38453 1.00746 22.625 16.642)" gradientUnits="userSpaceOnUse"><stop class="xy4qbsbbs"/><stop offset="1" class="loe_0kbli"/></radialGradient><radialGradient id="i9E4wnk" cx="0" cy="0" r="1" gradientTransform="matrix(3.09375 2.20253 -3.34177 4.69396 14.578 17.945)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="wvuv-xbkf"/><stop offset="1" class="k5q7nrb-t"/></radialGradient><radialGradient id="iCamPGc" cx="0" cy="0" r="1" gradientTransform="matrix(2.24948 -1.25893 1.5371 2.7465 19.717 12.58)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iRHnQKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.29426 .58931 -.1666 .3659 20.518 10.508)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="i71jrxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.40975 -.2244 .17541 1.10203 20.022 12.246)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="ilhyRSc" cx="0" cy="0" r="1" gradientTransform="rotate(175.21 5.513 6.666)scale(1.13781 .8976)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="isdsf7x" cx="0" cy="0" r="1" gradientTransform="rotate(150.454 7.715 8.322)scale(6.75226 9.03779)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="iBHS6he" cx="0" cy="0" r="1" gradientTransform="rotate(149.723 7.105 8.7)scale(2.127 1.48121)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="ijlwWFc" cx="0" cy="0" r="1" gradientTransform="rotate(-77.628 18.68 .356)scale(3.43005 4.35209)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="ihHZp4b" cx="0" cy="0" r="1" gradientTransform="rotate(91.937 2.34 13.953)scale(6.45565 6.49022)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iSrcsPe" cx="0" cy="0" r="1" gradientTransform="matrix(.517 6.1698 -6.20285 .51977 15.63 12.369)" gradientUnits="userSpaceOnUse"><stop offset=".858" class="l-0cbacrb"/><stop offset="1" class="tetwumyrr"/></radialGradient><radialGradient id="i1GY3Sb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.38139 1.81694 -3.1282 -10.98674 17.681 13.465)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="is63eUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0906 -1.08118 1.3269 -.11119 17.973 11.406)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="i9D1aYQ" cx="0" cy="0" r="1" gradientTransform="rotate(-94.79 12.227 -.597)scale(1.23747 1.41822)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="i9MxJFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20756 .10119 -.50746 -6.05582 20.716 12.585)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iA3fMSd" cx="0" cy="0" r="1" gradientTransform="matrix(-.58889 -1.88455 .5808 -.18149 16.722 13.606)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iR4OKud" cx="0" cy="0" r="1" gradientTransform="matrix(-.73227 .06136 -.01715 -.20472 16.514 13.825)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iILDoJb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21418 .99242 -1.19273 -1.45925 16.31 13.279)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="iQUqjjO" cx="0" cy="0" r="1" gradientTransform="rotate(85.21 2.555 15.603)scale(.76493 1.2167)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVfVdbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.24117 -.26226 .36107 -.33204 17.682 11.85)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iv8kUUN" cx="0" cy="0" r="1" gradientTransform="matrix(.06387 .76226 -1.21246 .1016 13.79 12.097)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ilLwHOd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.823 -.489)scale(.46539 .55942)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iiDq1se" cx="0" cy="0" r="1" gradientTransform="matrix(.96879 -2.68817 1.3752 .4956 10.357 10.379)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iNXEGDe" cx="0" cy="0" r="1" gradientTransform="rotate(-115.336 9.35 .814)scale(3.23672 5.29569)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="t7u3qkefj"/><stop offset=".93" class="w4h8bubsi"/></radialGradient><radialGradient id="ix7jm6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6385 4.29218 -7.01745 -2.67886 17.058 4.89)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iPtZhEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.08998 1.30108 -2.79921 -.1936 15.49 5.371)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iEVVKie" cx="0" cy="0" r="1" gradientTransform="matrix(.141 -.95434 .42047 .06212 16.072 16.316)" gradientUnits="userSpaceOnUse"><stop class="ivr_znbwj"/><stop offset="1" class="sp9mtjk7r"/></radialGradient><filter id="ik7gJ7d" width="3.052" height="2.539" x="3.522" y="11.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".15"/></filter><filter id="iJmuK8b" width="3.127" height="2.723" x="2.444" y="11.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".15"/></filter><filter id="ioPeASa" width="3.267" height="2.534" x="2.374" y="12.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".15"/></filter><filter id="ibFDOce" width="3.408" height="5.156" x="23.755" y="11.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.227451 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4183"/></filter><filter id="irjlQ1d" width="3.431" height="2.258" x="2.672" y="13.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".15"/></filter><filter id="iBBwDze" width="2.543" height="1.191" x="5.849" y="15.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".15"/></filter><filter id="iZarSAd" width="2.847" height=".977" x="25.223" y="14.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".15"/></filter><filter id="iUWzU2b" width="14.641" height="15.22" x="8.819" y="3.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4183"/></filter><filter id="iNP6LPK" width="23.107" height="13.423" x="4.624" y="16.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.278431 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4183"/></filter><filter id="iPss7te" width="8.199" height="8.945" x="5.11" y="16.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".75"/></filter><filter id="iwVWnMd" width="7.102" height="7.913" x="20.462" y="16.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".625"/></filter><filter id="iUUKvcd" width="3.956" height="6.956" x="9.209" y="19.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".25"/></filter><filter id="i6YKPso" width="3.184" height="3.034" x="9.967" y="11.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4183"/></filter><filter id="iNoPMfd" width="3.034" height="3.284" x="18.905" y="10.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4183"/></filter><filter id="ibh1jve" width="3.026" height="3.025" x="18.909" y="10.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".25"/></filter><filter id="iLohmre" width="2.526" height="2.525" x="10.24" y="11.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".125"/></filter><filter id="iD3XYve" width="9.717" height="10.229" x="10.951" y="8.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4183"/></filter><filter id="iQ7sIDc" width="2.767" height="3.559" x="14.48" y="11.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".25"/></filter><filter id="ixBTyPc" width="2.267" height="3.054" x="14.871" y="11.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".125"/></filter><filter id="ioctRvP" width="2.823" height="1.172" x="16.715" y="10.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4183"/></filter><filter id="iiith8c" width="2.843" height="1.26" x="12.126" y="11.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4183"/></filter><filter id="i0CkVZX" width="2.293" height="1.151" x="12.15" y="9.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4183"/></filter><filter id="iMjFRGb" width="2.344" height=".942" x="17.215" y="9.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4183"/></filter><filter id="icqRvIU" width=".729" height=".695" x="17.197" y="11.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".05"/></filter><filter id="iM0bnwd" width=".875" height=".893" x="17.987" y="11.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".1"/></filter><filter id="iKMhPTb" width=".971" height="1.01" x="13.807" y="11.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".1"/></filter><filter id="i0CZfVd" width=".85" height=".705" x="13.102" y="11.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".05"/></filter><filter id="ikD8aud" width="2.187" height=".859" x="17.222" y="9.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".1"/></filter><filter id="ie6EW4b" width="2.133" height="1.066" x="12.127" y="10.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".1"/></filter><filter id="i04C6Ee" width="3.895" height="4.493" x="9.593" y="6.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".2"/></filter><filter id="ivxl4wo" width="8.581" height="4.973" x="12.379" y="4.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4183"/><feGaussianBlur result="effect2_foregroundBlur_4002_4183" stdDeviation=".125"/></filter><filter id="iTBcoWd" width="1.246" height="2.163" x="12.355" y="6.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".1"/></filter><filter id="iH89a0b" width="6.725" height="3.616" x="14.681" y="6.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".5"/></filter><filter id="i7pnVln" width="1.709" height="1.724" x="15.421" y="14.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4183" stdDeviation=".05"/></filter><linearGradient id="iHHNzUb" x1="3.916" x2="6.63" y1="12.711" y2="12.711" gradientUnits="userSpaceOnUse"><stop class="j4wzxsb6s"/><stop offset="1" class="o9qbcmbqu"/></linearGradient><linearGradient id="iLIQ7fe" x1="4.222" x2="6.378" y1="11.819" y2="13.968" gradientUnits="userSpaceOnUse"><stop class="adq__h_ba"/><stop offset="1" class="xbm4if2ao"/></linearGradient><linearGradient id="iRhavzp" x1="2.8" x2="5.224" y1="13.155" y2="13.155" gradientUnits="userSpaceOnUse"><stop class="j4wzxsb6s"/><stop offset="1" class="o9qbcmbqu"/></linearGradient><linearGradient id="il2nHBb" x1="3.155" x2="5.565" y1="12.088" y2="14.302" gradientUnits="userSpaceOnUse"><stop class="adq__h_ba"/><stop offset="1" class="xbm4if2ao"/></linearGradient><linearGradient id="iAVO6pa" x1="2.874" x2="5.665" y1="14.012" y2="14.012" gradientUnits="userSpaceOnUse"><stop class="j4wzxsb6s"/><stop offset="1" class="o9qbcmbqu"/></linearGradient><linearGradient id="iG8bcKe" x1="3.079" x2="5.671" y1="13.08" y2="15.079" gradientUnits="userSpaceOnUse"><stop class="adq__h_ba"/><stop offset="1" class="xbm4if2ao"/></linearGradient><linearGradient id="iQeRWfd" x1="3.188" x2="5.984" y1="14.885" y2="14.885" gradientUnits="userSpaceOnUse"><stop class="j4wzxsb6s"/><stop offset="1" class="o9qbcmbqu"/></linearGradient><linearGradient id="idslX4b" x1="8.715" x2="7.874" y1="15.363" y2="15.363" gradientUnits="userSpaceOnUse"><stop offset=".005" class="dllwv2bqg"/><stop offset="1" class="lfy25fb4x"/></linearGradient><linearGradient id="iPrvWzb" x1="23.755" x2="24.552" y1="15.262" y2="15.262" gradientUnits="userSpaceOnUse"><stop class="g73nf-b6l"/><stop offset="1" class="t8bvpsbnn"/></linearGradient><linearGradient id="iVU3DLe" x1="28.351" x2="25.657" y1="13.52" y2="13.479" gradientUnits="userSpaceOnUse"><stop class="yludslbit"/><stop offset="1" class="c7b16qb0g"/></linearGradient><linearGradient id="iUUxJVb" x1="29.423" x2="26.879" y1="14.042" y2="14.009" gradientUnits="userSpaceOnUse"><stop class="yludslbit"/><stop offset="1" class="c7b16qb0g"/></linearGradient><linearGradient id="iPMRSzv" x1="29.396" x2="26.627" y1="14.803" y2="14.758" gradientUnits="userSpaceOnUse"><stop class="yludslbit"/><stop offset="1" class="c7b16qb0g"/></linearGradient><linearGradient id="iRmRpmc" x1="29.082" x2="26.307" y1="15.582" y2="15.531" gradientUnits="userSpaceOnUse"><stop class="uluqtabwc"/><stop offset="1" class="wgkuwteff"/></linearGradient><linearGradient id="iOyo40d" x1="3.368" x2="6.176" y1="14.107" y2="15.788" gradientUnits="userSpaceOnUse"><stop class="adq__h_ba"/><stop offset="1" class="xbm4if2ao"/></linearGradient><linearGradient id="iqLmHPe" x1="8.201" x2="7.412" y1="15.614" y2="14.567" gradientUnits="userSpaceOnUse"><stop class="adq__h_ba"/><stop offset="1" class="xbm4if2ao"/></linearGradient><linearGradient id="ihHO6Fc" x1="19.749" x2="14.348" y1="5.585" y2="17.963" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iXJ3kCd" x1="23.662" x2="24.149" y1="17.078" y2="17.069" gradientUnits="userSpaceOnUse"><stop class="ccx8jtb2j"/><stop offset="1" class="p1-vnac8k"/></linearGradient><linearGradient id="iDQACLO" x1="9.86" x2="12.86" y1="25.814" y2="20.158" gradientUnits="userSpaceOnUse"><stop class="g8oi3mbhp"/><stop offset="1" class="ynqid7b9h"/></linearGradient><linearGradient id="iKGOuEd" x1="9.98" x2="12.76" y1="13.064" y2="12.831" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iT3skWc" x1="15.11" x2="15.992" y1="13.811" y2="13.737" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iSNUwPd" x1="16.055" x2="16.006" y1="14.488" y2="13.914" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iofGnlb" x1="16.126" x2="16.115" y1="14.457" y2="14.326" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="ipe92Ee" x1="18.625" x2="18.345" y1="11.743" y2="11.949" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRV0XYX" x1="14.492" x2="14.213" y1="12.089" y2="12.295" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2qcXae" x1="12.682" x2="13.294" y1="6.89" y2="8.044" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-shrugging-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.adq__h_ba {
  stop-color: var(--svg-color--5b4b4b, #5B4B4B);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.aoh6fdm0m {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M10.653 7.26c.484-.608 1.49-.693 1.962-.648l.473 1.181c-.24-.017-.445.085-.609.273c-.322 1.22-1.715 1.994-2.371 2.229c-.257-1.39-.085-2.245.545-3.036");
}

.aq2vj0bqy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M2.874 13.154c.238.483.966 1.38 2.267 1.534");
}

.atps5cgtr {
  fill-rule: evenodd;
  d: path("M28.661 11.478a.7.7 0 0 0-.977.157c-.045.061-.088.136-.116.183l-.005.01l-.001.001c-.034.058-.066.114-.105.174c-.077.12-.17.25-.294.37c-.232.228-.607.468-1.267.5a.7.7 0 1 0 .069 1.398c1.024-.05 1.718-.447 2.178-.898a3.4 3.4 0 0 0 .495-.618a5 5 0 0 0 .13-.216l.004-.006c.029-.05.04-.07.045-.076l.001-.002a.7.7 0 0 0-.157-.978");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b_2l31nzi {
  fill: var(--svg-color--40302f, #40302F);
  d: path("M5.973 11.285a.75.75 0 0 1 1.052.138l.804 1.047c.37.48.57 1.07.57 1.676v2.14H5.14v-2.698h1.626a1.3 1.3 0 0 0-.127-.204l-.805-1.047a.75.75 0 0 1 .138-1.052");
}

.b60zzincu {
  d: path("M14.707 5.214c-1.084-.145-1.95.996-2.028 1.4c1.267 3.247 3.752 2.855 6.198 2.374c1.463-.288 1.68.372 1.833.687c-.31-3.695-3.51-4.125-5.976-4.457z");
}

.bfh6fzlxi {
  stop-color: var(--svg-color--a27be8, #A27BE8);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.c7b16qb0g {
  stop-color: var(--svg-color--4e3533, #4E3533);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.ccx8jtb2j {
  stop-color: var(--svg-color--493577, #493577);
}

.cgtm3g8-v {
  stop-color: var(--svg-color--9a71e1, #9A71E1);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.d-hvev_it {
  d: path("M20.549 13.618a1.517 1.517 0 1 0-.253-3.023a1.517 1.517 0 0 0 .253 3.023");
}

.dcsgtkbzx {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.5 12.177l-.366 1.64a.508.508 0 0 0 .544.615l.739-.062a.51.51 0 0 0 .434-.698l-.633-1.555c-.137-.345-.636-.303-.719.06");
}

.dke60rb2j {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.522 10.105c.297-.1 1.054-.126 1.588.192");
}

.dllwv2bqg {
  stop-color: var(--svg-color--4d4342, #4D4342);
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dol2bxb1e {
  stop-color: var(--svg-color--9a71e1, #9A71E1);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eqysr1ben {
  d: path("m15.5 12.177l-.366 1.64a.508.508 0 0 0 .544.615l.739-.062a.51.51 0 0 0 .434-.698l-.633-1.555c-.137-.345-.636-.303-.719.06");
}

.ey8rcibsm {
  stop-color: var(--svg-color--a980f0, #A980F0);
  stop-opacity: 0;
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.ft8nx4t0e {
  d: path("M10.653 7.26c.484-.608 1.49-.693 1.962-.648l.473 1.181c-.24-.017-.445.085-.609.273c-.322 1.22-1.715 1.994-2.371 2.229c-.257-1.39-.085-2.245.545-3.036");
}

.ftfq3_y5k {
  d: path("M13.75 11.65a.842.842 0 0 0-.719 1.127l1.62-.136a1 1 0 0 0 .012-.224a.847.847 0 0 0-.913-.768");
}

.fzkncnb-q {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.587 13.863a1.013 1.013 0 1 0-.169-2.018a1.013 1.013 0 0 0 .17 2.018");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g73nf-b6l {
  stop-color: var(--svg-color--382020, #382020);
}

.g8oi3mbhp {
  stop-color: var(--svg-color--7346c5, #7346C5);
}

.gc1ou3b7p {
  cx: 13.527px;
  cy: 12.029px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.367px;
  ry: 0.186px;
}

.gfod2bbij {
  fill-rule: evenodd;
  d: path("M3.492 11.478a.7.7 0 0 1 .978.157a2 2 0 0 1 .12.192l.002.002q.048.085.104.174c.077.12.171.25.294.37c.233.228.608.468 1.267.5a.7.7 0 1 1-.068 1.398c-1.025-.05-1.718-.447-2.179-.898a3.5 3.5 0 0 1-.495-.618a6 6 0 0 1-.13-.216l-.004-.006l-.044-.076l-.002-.002a.7.7 0 0 1 .157-.978");
}

.gfpc_b4dg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M3.172 14.205c.293.452 1.122 1.258 2.431 1.258");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.golfcqbxg {
  stroke: var(--svg-color--a57cec, #A57CEC);
  stroke-linecap: square;
  d: path("M25.814 18.695v3.41a1 1 0 0 1-1.567.824l-1.84-1.266");
}

.gso_3nbbg {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.217 10.093l-.112.227za.253.253 0 0 1-.223.454l-.005-.003l-.02-.01l-.09-.035a3 3 0 0 0-.333-.1a2.14 2.14 0 0 0-1.014-.002a.253.253 0 1 1-.13-.49a2.64 2.64 0 0 1 1.257-.001a3 3 0 0 1 .544.18l.01.004l.002.002z");
}

.h3d7w4j4j {
  stop-color: var(--svg-color--783edb, #783EDB);
  stop-opacity: 0;
}

.hd1_19zwc {
  fill-rule: evenodd;
  d: path("M22.749 13.245c.165-.425.231-.89.191-1.366a3.1 3.1 0 0 0-.355-1.205h.005a3 3 0 0 0-.304-.46l-.002-.003a3.05 3.05 0 0 1-.634-1.623l-.001-.01a3.11 3.11 0 0 0-3.36-2.84a.51.51 0 0 1-.446-.182a3.12 3.12 0 0 0-2.628-1.082a3.12 3.12 0 0 0-2.411 1.504a.53.53 0 0 1-.41.255l-.08.008a3.11 3.11 0 0 0-2.76 3.351l.001.01c.05.59-.073 1.184-.355 1.705l-.001.004a3.11 3.11 0 0 0 .048 3.066a.49.49 0 0 1 .036.428a3.03 3.03 0 0 0 3.083 4.117l8.063-.676a3.03 3.03 0 0 0 2.355-4.573a.49.49 0 0 1-.035-.428M11.019 11.7h-.011l1.311 2.12c.337 2.623 1.144-.096 3.654-.307c2.51-.21 3.85 2.629 3.745-.014l.815-3.093c-.148-1.165-1.003-1.176-1.172-1.162l-3.025.253c-1.195.1-2.37-.39-3.128-1.32a.249.249 0 0 0-.43.084l-.062.188a2.17 2.17 0 0 1-1.113 1.3c-.212.134-.703.522-.648 1.415l.034.287z");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hk2gombwq {
  stop-color: var(--svg-color--8364b6, #8364B6);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.ho71ipbar {
  fill-rule: evenodd;
  d: path("M29.42 13.847a.7.7 0 0 0-.98.142c-.18.242-.653.84-1.873.84a.7.7 0 1 0 0 1.4c1.828 0 2.668-.964 2.995-1.402a.7.7 0 0 0-.142-.98");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.i7_2bobbl {
  d: path("M18.662 11.97a.8.8 0 0 0-.254-.416l-.221.288l.128.205z");
}

.imzqxgplv {
  d: path("M9.484 20.574a.25.25 0 0 1-.375-.216v-2.564a.6.6 0 0 0-.6-.6H5.224a.6.6 0 0 0-.6.6v4.286c-.005.85.112 2.507 1.485 3.383c1.148.733 2.5.57 3.213.347c.101-.031.208.042.208.148v3.707c0 .082.068.15.15.15h12.994a.15.15 0 0 0 .15-.15v-3.707c0-.106.108-.18.209-.148c.713.223 2.065.386 3.213-.347c1.373-.876 1.49-2.534 1.485-3.383v-4.286a.6.6 0 0 0-.6-.6h-3.285a.6.6 0 0 0-.6.6v2.564a.25.25 0 0 1-.375.216l-6.694-3.932z");
}

.ivr_znbwj {
  stop-color: var(--svg-color--5b4e4e, #5B4E4E);
}

.j0u7-u3qa {
  stop-color: var(--svg-color--9d7ad7, #9D7AD7);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j2xk3ackf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.027 11.034a1.32 1.32 0 0 1 1.357.888a.258.258 0 0 1-.225.341l-2.096.176a.217.217 0 0 1-.235-.238a1.32 1.32 0 0 1 1.2-1.167");
}

.j4wzxsb6s {
  stop-color: var(--svg-color--422d2b, #422D2B);
}

.j5s7e9vux {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M16.915 11.862c.213-.46.563-.838 1.379-.906c.357-.03.71.04 1.037.262c.27.183.257.447.07.561l-.497.342c-.63-.147-1.309-.117-1.989-.259");
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jlublfbcv {
  stop-color: var(--svg-color--783edb, #783EDB);
}

.jsb3wkbzc {
  stroke: var(--svg-color--9465e3, #9465E3);
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.36 18.663v3.442a1 1 0 0 0 1.566.824l1.84-1.266");
}

.k5q7nrb-t {
  stop-color: var(--svg-color--503535, #503535);
}

.k9011xajc {
  stop-color: var(--svg-color--895fc7, #895FC7);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.l-0cbacrb {
  stop-color: var(--svg-color--5c4761, #5C4761);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l533ei3qo {
  fill-rule: evenodd;
  d: path("M2.421 12.816a.7.7 0 0 1 .98.142l.086.118c.301.42.763 1.062 1.779 1.062a.7.7 0 1 1 0 1.4c-1.776 0-2.637-1.24-2.925-1.654q-.037-.055-.062-.088a.7.7 0 0 1 .142-.98");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l93r40bgi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.86 25.345c.177-1.146.956-3.881 2.656-5.656");
}

.lea4hbl2x {
  stop-color: var(--svg-color--7954b7, #7954B7);
}

.lfy25fb4x {
  stop-color: var(--svg-color--4d4342, #4D4342);
  stop-opacity: 0;
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.loe_0kbli {
  stop-color: var(--svg-color--563a92, #563A92);
  stop-opacity: 0;
}

.lv2o39i_t {
  d: path("M11.587 13.863a1.013 1.013 0 1 0-.169-2.018a1.013 1.013 0 0 0 .17 2.018");
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.m7cwrybrd {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.5 12.308l-.508 1.651a.508.508 0 0 0 .544.616l.74-.062a.51.51 0 0 0 .433-.698l-.633-1.555c-.137-.345-.493-.315-.575.048");
}

.m7s27ibhr {
  fill-rule: evenodd;
  d: path("M29.732 12.816a.7.7 0 0 0-.98.142l-.086.118c-.301.42-.763 1.062-1.778 1.062a.7.7 0 1 0 0 1.4c1.775 0 2.636-1.24 2.924-1.654l.062-.088a.7.7 0 0 0-.142-.98");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mc3aerbdu {
  stop-color: var(--svg-color--665554, #665554);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mgujedcpg {
  d: path("M17.807 11.488c.066.075-.05.183-.183.3c-.133.118-.232.202-.298.127c-.067-.075-.013-.231.12-.349s.295-.153.36-.078");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mxpwktbey {
  d: path("M5.973 11.285a.75.75 0 0 1 1.052.138l.804 1.047c.37.48.57 1.07.57 1.676v2.14H5.14v-2.698h1.626a1.3 1.3 0 0 0-.127-.204l-.805-1.047a.75.75 0 0 1 .138-1.052");
}

.nhigy-yiu {
  fill-rule: evenodd;
  d: path("M2.733 13.847a.7.7 0 0 1 .98.142c.181.242.653.84 1.873.84a.7.7 0 1 1 0 1.4c-1.827 0-2.668-.964-2.994-1.402a.7.7 0 0 1 .141-.98");
}

.nt-ywibkx {
  cx: 16.275px;
  cy: 15.7px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  rx: 0.654px;
  ry: 0.662px;
}

.nxxy5ib6i {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.535 11.41a1.32 1.32 0 0 0-1.19 1.102a.258.258 0 0 0 .278.299l2.097-.176a.217.217 0 0 0 .191-.273a1.32 1.32 0 0 0-1.376-.952");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o9qbcmbqu {
  stop-color: var(--svg-color--40302f, #40302F);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oifg47bvk {
  d: path("M17.854 11.305a.84.84 0 0 1 .897.992l-1.62.136a.845.845 0 0 1 .723-1.128");
}

.okhmxbclb {
  d: path("M27.092 16.345a.25.25 0 0 0-.25-.25h-2.93a.25.25 0 0 0-.25.25v1.318h3.43z");
}

.otknywvoi {
  fill: var(--svg-color--4b3230, #4B3230);
  d: path("M26.18 11.285a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.259v-2.698h-1.627q.054-.107.128-.204l.804-1.047a.75.75 0 0 0-.138-1.052");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p_s_z07gj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.35 15.614h.997c.227 0 .444.09.604.25v0");
}

.p1-vnac8k {
  stop-color: var(--svg-color--493577, #493577);
  stop-opacity: 0;
}

.p1da4obcx {
  stop-color: var(--svg-color--362457, #362457);
}

.p2xodcbta {
  stop-color: var(--svg-color--665554, #665554);
  stop-opacity: 0;
}

.p6pttubsq {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.507 13.116a1.013 1.013 0 1 0-.17-2.019a1.013 1.013 0 0 0 .17 2.019");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pb1uanbce {
  d: path("M26.18 11.285a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.259v-2.698h-1.627q.054-.107.128-.204l.804-1.047a.75.75 0 0 0-.138-1.052");
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plpm3y40t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M4.022 11.865c.196.501 1.018 1.387 2.052 1.538");
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qis5bdcfc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.655 6.568c.041.226.312 1.068.647 1.563");
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r8nvtjbrg {
  stop-color: var(--svg-color--3d2625, #3D2625);
  stop-opacity: 0;
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rqpemmbby {
  stop-color: var(--svg-color--362457, #362457);
  stop-opacity: 0;
}

.s-9lc-blc {
  d: path("M15.994 20.147c-1.105 0-2-.744-2-1.661v-1.963c0-.917.895-1.661 2-1.661s2 .744 2 1.661v1.963c0 .917-.896 1.661-2 1.661");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sl65zcqrd {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M14.707 5.214c-1.084-.145-1.95.996-2.028 1.4c1.267 3.247 3.752 2.855 6.198 2.374c1.463-.288 1.68.372 1.833.687c-.31-3.695-3.51-4.125-5.976-4.457z");
}

.so47whbnh {
  fill-rule: evenodd;
  d: path("M2.453 11.794a.7.7 0 0 1 .978.157q.05.071.115.168c.261.391.703 1.052 1.515 1.4a.7.7 0 1 1-.551 1.287c-1.246-.534-1.935-1.603-2.156-1.946l-.058-.089a.7.7 0 0 1 .157-.977");
}

.sp9mtjk7r {
  stop-color: var(--svg-color--5b4e4e, #5B4E4E);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sy-i5vrnl {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.77 12.042c-.287-.418-.695-.733-1.511-.664a1.57 1.57 0 0 0-.979.43c-.235.226-.18.484.024.566l.547.254c.596-.25 1.271-.333 1.918-.586");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t7u3qkefj {
  stop-color: var(--svg-color--545253, #545253);
  stop-opacity: 0;
}

.t8bvpsbnn {
  stop-color: var(--svg-color--382020, #382020);
  stop-opacity: 0;
}

.tb4wryb1h {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.807 11.488c.066.075-.05.183-.183.3c-.133.118-.232.202-.298.127c-.067-.075-.013-.231.12-.349s.295-.153.36-.078");
}

.tb7ah0bdp {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.818 8.369l-1.318.358a.649.649 0 1 1-.225-1.272l2.2-.184c1.3-.11 1.84 1.165 1.93 1.609a2.97 2.97 0 0 0-2.587-.511");
}

.tetwumyrr {
  stop-color: var(--svg-color--5c4761, #5C4761);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.twf01ac1b {
  stop-color: var(--svg-color--33201d, #33201D);
}

.uluqtabwc {
  stop-color: var(--svg-color--503734, #503734);
}

.upmwye1mi {
  stop-color: var(--svg-color--8358c9, #8358C9);
  stop-opacity: 0;
}

.ushk2fb9i {
  cx: 13.527px;
  cy: 12.029px;
  rx: 0.367px;
  ry: 0.186px;
}

.uxkjixbpm {
  cx: 16.275px;
  cy: 15.7px;
  fill: var(--svg-color--290118, #290118);
  rx: 0.654px;
  ry: 0.662px;
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v33ia2knp {
  stroke: var(--svg-color--635150, #635150);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M25.623 15.52h1.515a.7.7 0 0 0 .532-.171");
}

.vg-mzkb2l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M2.944 12.145c.196.501.844 1.458 2.127 1.723");
}

.vio74z7fz {
  stop-color: var(--svg-color--a980f0, #A980F0);
}

.vy1fepq3p {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.96 10.403c-.309-.048-1.06.052-1.533.454");
}

.w_4_3bbcu {
  fill-rule: evenodd;
  d: path("M29.7 11.794a.7.7 0 0 0-.977.157q-.05.071-.115.168c-.262.391-.921 1.114-1.733 1.46c-.355.153-.503.45-.32.876c.152.355.733.503 1.088.35c1.246-.533 1.935-1.602 2.156-1.945l.058-.089a.7.7 0 0 0-.157-.977");
}

.w_txxk5nx {
  stop-color: var(--svg-color--3d2625, #3D2625);
}

.w06d_xbwd {
  stop-color: var(--svg-color--6745a2, #6745A2);
}

.w1pfz9iya {
  d: path("M5.158 16.345a.25.25 0 0 1 .25-.25h2.93a.25.25 0 0 1 .25.25v1.13h-3.43z");
}

.w30p1jble {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.555 11.083l-.004.003a.253.253 0 0 1-.296-.41h.001v-.001l.003-.002l.009-.006a2 2 0 0 1 .133-.084c.09-.052.216-.12.373-.184c.31-.129.75-.252 1.24-.207a.253.253 0 0 1-.047.503a2.14 2.14 0 0 0-1 .171a2.6 2.6 0 0 0-.393.204z");
}

.w4h8bubsi {
  stop-color: var(--svg-color--545253, #545253);
}

.w9bmuwbwu {
  d: path("M20.507 13.116a1.013 1.013 0 1 0-.17-2.019a1.013 1.013 0 0 0 .17 2.019");
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgkuwteff {
  stop-color: var(--svg-color--4b3330, #4B3330);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.wvuv-xbkf {
  stop-color: var(--svg-color--362126, #362126);
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xbm4if2ao {
  stop-color: var(--svg-color--5b4b4b, #5B4B4B);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xxdsqkpot {
  fill: var(--svg-color--000, #000);
  d: path("M14.3 12.447a.48.48 0 0 0-.52-.44a.48.48 0 0 0-.368.737l.85-.071a.5.5 0 0 0 .038-.226");
}

.xy4qbsbbs {
  stop-color: var(--svg-color--563a92, #563A92);
}

.y87h-bcxa {
  d: path("M11.611 14.367a1.517 1.517 0 1 0-.253-3.023a1.517 1.517 0 0 0 .253 3.023");
}

.y8fls1pkq {
  fill: var(--svg-color--000, #000);
  d: path("M17.444 12.184a.48.48 0 0 1 .44-.52a.48.48 0 0 1 .485.665l-.85.07a.44.44 0 0 1-.075-.215");
}

.yed-8cx0y {
  d: path("M11.008 11.7h.011l-.03-.249l-.034-.286c-.055-.893.436-1.282.648-1.416l.046-.023l.047-.023a2.17 2.17 0 0 0 1.02-1.254l.062-.188a.249.249 0 0 1 .43-.085a3.64 3.64 0 0 0 3.128 1.321l3.025-.253c.17-.014 1.024-.003 1.172 1.162l.13 2.897c.105 2.642-1.803 4.583-4.312 4.793s-4.715-1.385-5.051-4.009z");
}

.yludslbit {
  stop-color: var(--svg-color--4b3230, #4B3230);
}

.ynqid7b9h {
  stop-color: var(--svg-color--7346c5, #7346C5);
  stop-opacity: 0;
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z5em5hh2o {
  d: path("M14.578 12.325c-.023-.271-.258-.433-.322-.483l-.249.285l.195.325z");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zg5ree2ok {
  stop-color: var(--svg-color--33201d, #33201D);
  stop-opacity: 0;
}

.zgf54gbaa {
  stop-color: var(--svg-color--614396, #614396);
}

.zk7ulfu0q {
  stop-color: var(--svg-color--4d3e3c, #4D3E3C);
  stop-opacity: 0;
}

.zvb7pjbrz {
  stop-color: var(--svg-color--4d3e3c, #4D3E3C);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
