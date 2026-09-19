<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iEIoQKD)" clip-rule="evenodd" class="l501wpbht"/><path fill="url(#ih6iLgb)" clip-rule="evenodd" class="l501wpbht"/><g filter="url(#iJAcc6P)"><path stroke="url(#iUkIVSb)" class="llqxe3bem"/></g><path fill="url(#iPV0H8x)" clip-rule="evenodd" class="yenur026f"/><path fill="url(#ioTnq8b)" clip-rule="evenodd" class="yenur026f"/><g filter="url(#iAxXgjd)"><path stroke="url(#iX81ljj)" class="dp-pe5xra"/></g><path fill="url(#iVceCfd)" clip-rule="evenodd" class="nw6x2sbzm"/><path fill="url(#ieGDqte)" clip-rule="evenodd" class="nw6x2sbzm"/><g filter="url(#ityLeqb)"><path stroke="url(#iqbek6b)" class="plknl7b1w"/></g><path fill="url(#iTe9lMb)" clip-rule="evenodd" class="hu3s1qbxb"/><path fill="url(#iFmvnfd)" clip-rule="evenodd" class="hu3s1qbxb"/><path class="xjy_9rbsx"/><path fill="url(#iL9u69b)" class="plq4hrpyc"/><path fill="url(#iqYcg6b)" class="plq4hrpyc"/><path fill="url(#iwScDjd)" class="plq4hrpyc"/><path fill="url(#itf1R7b)" class="plq4hrpyc"/><g filter="url(#ikJNPZb)"><path class="tvdh3pi4i"/><path fill="url(#iZBOZec)" class="m6msjkbjj"/><path fill="url(#i6S3SZd)" class="m6msjkbjj"/><path fill="url(#iUByAJe)" class="m6msjkbjj"/></g><path fill="url(#iCwkACc)" clip-rule="evenodd" class="w16pczbvt"/><path fill="url(#iFV0fVb)" clip-rule="evenodd" class="w16pczbvt"/><path fill="url(#iacsCPc)" clip-rule="evenodd" class="w16pczbvt"/><path fill="url(#iO2e5db)" clip-rule="evenodd" class="w16pczbvt"/><path fill="url(#i134RNb)" clip-rule="evenodd" class="dop1c2kyt"/><path fill="url(#i7leHKe)" clip-rule="evenodd" class="dop1c2kyt"/><path fill="url(#iLT8Vve)" clip-rule="evenodd" class="dop1c2kyt"/><path fill="url(#iccD7ac)" clip-rule="evenodd" class="dop1c2kyt"/><path fill="url(#iAQtl3m)" clip-rule="evenodd" class="gg2qh5btd"/><path fill="url(#iFAAqve)" clip-rule="evenodd" class="gg2qh5btd"/><path fill="url(#ilVGuab)" clip-rule="evenodd" class="gg2qh5btd"/><path fill="url(#iLj9czc)" clip-rule="evenodd" class="gg2qh5btd"/><path fill="url(#iZZveFb)" clip-rule="evenodd" class="yaxmr2k5m"/><path fill="url(#iG2G5yd)" clip-rule="evenodd" class="yaxmr2k5m"/><path fill="url(#iBL5ZEc)" clip-rule="evenodd" class="yaxmr2k5m"/><path fill="url(#icwAnbd)" clip-rule="evenodd" class="yaxmr2k5m"/><path fill="url(#iOZM4Yd)" class="lf6x2hczr"/><path fill="url(#ijDEcHr)" class="pqi97va-m"/><g filter="url(#iFpxGTc)"><path fill="url(#iLvpkgd)" class="c0we-jd3m"/><path fill="url(#iCN9ybc)" class="c0we-jd3m"/><path fill="url(#iRty4Je)" class="c0we-jd3m"/><path fill="url(#ivrwDHd)" class="c0we-jd3m"/><path fill="url(#ixKG0Ie)" class="c0we-jd3m"/><path fill="url(#iwjPQWv)" class="c0we-jd3m"/></g><path fill="url(#imojtbd)" class="bsbwju02k"/><path fill="url(#iyMTxBb)" class="bsbwju02k"/><path fill="url(#iXeTg2c)" class="gktx2cc_x"/><path fill="url(#iIZ20Bc)" class="jtrcqfs1u"/><g filter="url(#i7QzU4c)"><path fill="url(#iX4rAke)" class="xgt3psbhd"/><path fill="url(#iuy8cym)" class="xgt3psbhd"/></g><path fill="url(#iFgzOcc)" class="xgt3psbhd"/><path fill="url(#iP7xejb)" class="xgt3psbhd"/><path fill="url(#iw8cqQb)" class="xgt3psbhd"/><path fill="url(#i9NQNFl)" class="xgt3psbhd"/><path fill="url(#iDUBV9b)" class="xgt3psbhd"/><path fill="url(#i4vTDyc)" class="xgt3psbhd"/><path fill="url(#icc2Jnc)" class="xgt3psbhd"/><path fill="url(#iCafujb)" class="xgt3psbhd"/><path fill="url(#izShIgd)" class="xgt3psbhd"/><g filter="url(#iYW1c5d)"><path class="nu0upxjqp"/></g><g filter="url(#id8ko0c)"><path class="vc_133bog"/><path fill="url(#iYnwDsc)" class="qm_p1qb1x"/><path fill="url(#iGgPtme)" class="qm_p1qb1x"/><path fill="url(#i2IneHe)" class="qm_p1qb1x"/><path fill="url(#igCehvb)" class="qm_p1qb1x"/><path fill="url(#iH6TWTs)" class="qm_p1qb1x"/></g><path fill="url(#ioz6pVb)" class="qm_p1qb1x"/><path fill="url(#iUAp1te)" class="qm_p1qb1x"/><g filter="url(#iAPuZqc)"><path fill="url(#i2fUMdu)" class="aonrc8zob"/></g><path fill="url(#iofAmDb)" class="aonrc8zob"/><path fill="url(#iEVl32d)" class="aonrc8zob"/><path fill="url(#i5VmTKc)" class="aonrc8zob"/><g filter="url(#iOGPcsb)"><path class="nsvw3qbwe"/></g><g filter="url(#i7RIMbb)"><path class="htnuayb0e"/></g><g filter="url(#iZeq8Sd)"><path class="wrz93t-rl"/><path fill="url(#iMFpLRc)" class="t1g9ceb8j"/><path fill="url(#iP06rid)" class="t1g9ceb8j"/></g><g filter="url(#iFs0ioe)"><path class="bsgi7geqg"/><path fill="url(#idbmCae)" class="edi105b3p"/><path fill="url(#iG7hqPP)" class="edi105b3p"/><path fill="url(#igC2rKd)" class="edi105b3p"/></g><path class="t4gnjqvlq"/><path fill="url(#iQLms4N)" class="fv5uflvts"/><path class="h85_nzbgf"/><g filter="url(#ijboCRd)"><path class="l38hnxbpk"/><path fill="url(#iNidyed)" class="ro-sdi-ns"/></g><g filter="url(#iSZPYQd)"><path fill="url(#iyy8ACc)" class="kxvovqbaa"/></g><path class="ph51elbbd"/><path fill="url(#id19zHc)" class="roca9nbvr"/><path class="sa81twb1r"/><g filter="url(#ik6gOJb)"><path fill="url(#icdR21d)" class="suj071bwa"/></g><g filter="url(#iu8DrTo)"><ellipse transform="rotate(-32.532 13.25 13.06)" class="fyhob6bpk"/><ellipse fill="url(#iGaKLFV)" transform="rotate(-32.532 13.25 13.06)" class="kmr9t_apu"/></g><path fill="url(#ibsD8rb)" class="hnslz--nu"/><path fill="url(#ibq4qQc)" class="hnslz--nu"/><path fill="url(#i1sA7ke)" class="hnslz--nu"/><path fill="url(#i4x7PUb)" class="hnslz--nu"/><path fill="url(#irUd7Td)" class="j5oh69t0z"/><path fill="url(#iqGYT0c)" class="j5oh69t0z"/><g filter="url(#i78vfBb)"><path fill="url(#iAYA04b)" class="lcvkdjbxr"/></g><g filter="url(#iyyGAId)"><path fill="url(#ixKYt1b)" class="xw4oh8inu"/></g><g filter="url(#ix4YVPe)"><path class="c6gsbc5ms"/></g><g filter="url(#ibbhOxF)"><path class="xt2-624jk"/></g><g filter="url(#ieGWRDd)"><path stroke="url(#iE0EJKd)" class="r-dr48byv"/></g><g filter="url(#id4lf0u)"><ellipse stroke="url(#imJAmob)" class="evf191haz"/></g><ellipse class="ktwlew6wq"/><g filter="url(#iTcFj2c)"><path stroke="url(#i2FpN8d)" class="eqno0223k"/></g><g filter="url(#iMlhIRx)"><path class="rlyk3nhtu"/></g><g filter="url(#ikJE2qh)"><path stroke="url(#iLy4DCD)" class="x_u-3jb7a"/></g><g filter="url(#iUZ2Svc)"><path class="knz139bll"/></g><defs><radialGradient id="ih6iLgb" cx="0" cy="0" r="1" gradientTransform="matrix(-.71267 1.83244 -2.48647 -.96704 5.155 12.872)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="d348e2bmq"/><stop offset="1" class="h0gi5sr7l"/></radialGradient><radialGradient id="ioTnq8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.63638 2.0037 -2.32192 -.73745 3.883 13.253)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="d348e2bmq"/><stop offset="1" class="h0gi5sr7l"/></radialGradient><radialGradient id="ieGDqte" cx="0" cy="0" r="1" gradientTransform="rotate(112.256 -2.685 8.489)scale(1.93501 2.72441)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="d348e2bmq"/><stop offset="1" class="h0gi5sr7l"/></radialGradient><radialGradient id="iFmvnfd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 1.57812 -2.42466 -1.12832 4.48 15.14)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="d348e2bmq"/><stop offset="1" class="h0gi5sr7l"/></radialGradient><radialGradient id="iqYcg6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.52138 .86916 -1.0215 -.61276 6.787 11.966)" gradientUnits="userSpaceOnUse"><stop class="lhs441rxk"/><stop offset="1" class="kvh590ikm"/></radialGradient><radialGradient id="itf1R7b" cx="0" cy="0" r="1" gradientTransform="rotate(50.771 -10.912 12.138)scale(2.10408 .76124)" gradientUnits="userSpaceOnUse"><stop class="fm-ag3l1v"/><stop offset="1" class="jqoxmxa7u"/></radialGradient><radialGradient id="i6S3SZd" cx="0" cy="0" r="1" gradientTransform="rotate(-33.079 33.57 -37.673)scale(1.01629 .48928)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="vpgp1b8tt"/><stop offset="1" class="uudqsyb7t"/></radialGradient><radialGradient id="iUByAJe" cx="0" cy="0" r="1" gradientTransform="rotate(-141.546 15.372 2.218)scale(.67838 .87633)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="teu5d39go"/><stop offset="1" class="ieaa_kb0h"/></radialGradient><radialGradient id="iFV0fVb" cx="0" cy="0" r="1" gradientTransform="matrix(2.25998 .5537 -1.30788 5.3383 26.3 12.935)" gradientUnits="userSpaceOnUse"><stop offset=".575" class="iky79-blm"/><stop offset="1" class="qm-9wjixk"/></radialGradient><radialGradient id="iacsCPc" cx="0" cy="0" r="1" gradientTransform="matrix(.83172 1.25496 -1.54431 1.02349 26.785 13.06)" gradientUnits="userSpaceOnUse"><stop class="rqxwi30ib"/><stop offset="1" class="lslkpqbsz"/></radialGradient><radialGradient id="iO2e5db" cx="0" cy="0" r="1" gradientTransform="matrix(.56104 -.65315 .38675 .3322 28.45 12.563)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="qrv_azbvd"/><stop offset="1" class="u_7m_6tiu"/></radialGradient><radialGradient id="i7leHKe" cx="0" cy="0" r="1" gradientTransform="matrix(.97003 2.19293 -9.2033 4.07104 27.89 12.707)" gradientUnits="userSpaceOnUse"><stop offset=".575" class="iky79-blm"/><stop offset="1" class="qm-9wjixk"/></radialGradient><radialGradient id="iLT8Vve" cx="0" cy="0" r="1" gradientTransform="matrix(1.17519 1.75148 -1.61774 1.08545 27.678 13.41)" gradientUnits="userSpaceOnUse"><stop class="rqxwi30ib"/><stop offset="1" class="lslkpqbsz"/></radialGradient><radialGradient id="iccD7ac" cx="0" cy="0" r="1" gradientTransform="matrix(.5763 -.5424 .31085 .33028 29.328 12.709)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="qrv_azbvd"/><stop offset="1" class="u_7m_6tiu"/></radialGradient><radialGradient id="iFAAqve" cx="0" cy="0" r="1" gradientTransform="matrix(1.0562 1.95821 -9.2814 5.0061 27.746 13.7)" gradientUnits="userSpaceOnUse"><stop offset=".575" class="iky79-blm"/><stop offset="1" class="qm-9wjixk"/></radialGradient><radialGradient id="ilVGuab" cx="0" cy="0" r="1" gradientTransform="rotate(60.712 1.802 30.901)scale(1.58787 1.64819)" gradientUnits="userSpaceOnUse"><stop class="rqxwi30ib"/><stop offset="1" class="lslkpqbsz"/></radialGradient><radialGradient id="iLj9czc" cx="0" cy="0" r="1" gradientTransform="matrix(.57695 -.63832 .3804 .34382 29.504 13.887)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="qrv_azbvd"/><stop offset="1" class="u_7m_6tiu"/></radialGradient><radialGradient id="iG2G5yd" cx="0" cy="0" r="1" gradientTransform="rotate(58.478 .576 31.855)scale(2.02431 10.2344)" gradientUnits="userSpaceOnUse"><stop offset=".575" class="iky79-blm"/><stop offset="1" class="qm-9wjixk"/></radialGradient><radialGradient id="iBL5ZEc" cx="0" cy="0" r="1" gradientTransform="rotate(57.47 -.048 32.71)scale(1.44748 1.59652)" gradientUnits="userSpaceOnUse"><stop class="rqxwi30ib"/><stop offset="1" class="lslkpqbsz"/></radialGradient><radialGradient id="icwAnbd" cx="0" cy="0" r="1" gradientTransform="matrix(.57812 -.5625 .3368 .34616 29.19 14.874)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="qrv_azbvd"/><stop offset="1" class="u_7m_6tiu"/></radialGradient><radialGradient id="iOZM4Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59375 0 0 -2.7696 26.255 17.455)" gradientUnits="userSpaceOnUse"><stop class="oliv2bcuo"/><stop offset="1" class="k1yfa1pxl"/></radialGradient><radialGradient id="ijDEcHr" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32031 0 6.99 17.041)" gradientUnits="userSpaceOnUse"><stop class="byn2s1bln"/><stop offset="1" class="gno4tuy0h"/></radialGradient><radialGradient id="iLvpkgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.75 8.9375 0 19.568 29.783)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="finomov8p"/><stop offset="1" class="qfj8esbtd"/></radialGradient><radialGradient id="iCN9ybc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1875 3.5231 -.87474 -.79141 9.63 20.408)" gradientUnits="userSpaceOnUse"><stop class="xo_dbbcrk"/><stop offset="1" class="fipf36vin"/></radialGradient><radialGradient id="iRty4Je" cx="0" cy="0" r="1" gradientTransform="matrix(5.31253 3.28121 -.93453 1.51307 19.787 20.814)" gradientUnits="userSpaceOnUse"><stop class="zk2mfu__s"/><stop offset="1" class="xx0si6etu"/></radialGradient><radialGradient id="ivrwDHd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50001 -3.65624 1.29065 -.8825 24.13 26.627)" gradientUnits="userSpaceOnUse"><stop class="wz_ov4j-l"/><stop offset="1" class="a7wya1e_a"/><stop offset="1" class="khy4tkbbd"/></radialGradient><radialGradient id="ixKG0Ie" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.46944 -4.08022 0 26.662 17.345)" gradientUnits="userSpaceOnUse"><stop class="tg0z2qhwd"/><stop offset="1" class="hpe9ehb7d"/></radialGradient><radialGradient id="iwjPQWv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.96875 2.34375 -1.44391 -2.44503 13.38 18.877)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="fni_1r5pr"/><stop offset="1" class="rx-90_bsr"/></radialGradient><radialGradient id="iyMTxBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -1.60078 0 15.818 19.296)" gradientUnits="userSpaceOnUse"><stop class="fv3u9nbaa"/><stop offset="1" class="crjf7pa5p"/></radialGradient><radialGradient id="iXeTg2c" cx="0" cy="0" r="1" gradientTransform="rotate(65.039 -1.166 22.996)scale(2.03143 2.41318)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iIZ20Bc" cx="0" cy="0" r="1" gradientTransform="matrix(1.42324 .32412 -.99992 4.3908 10.05 15.63)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iX4rAke" cx="0" cy="0" r="1" gradientTransform="matrix(-4.42314 .35728 -.63202 -7.8245 18.274 13.612)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iuy8cym" cx="0" cy="0" r="1" gradientTransform="rotate(116.541 5.999 9.902)scale(3.17745 2.62325)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iP7xejb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01763 11.75679 -9.73604 -.0146 16.672 8.146)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="iw8cqQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0872 -1.07955 1.33594 -.10791 17.836 12.406)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="i9NQNFl" cx="0" cy="0" r="1" gradientTransform="rotate(-94.412 12.617 .213)scale(1.03207 1.12314)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iDUBV9b" cx="0" cy="0" r="1" gradientTransform="rotate(171.77 8.947 7.928)scale(8.02893 20.5099)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i4vTDyc" cx="0" cy="0" r="1" gradientTransform="matrix(2.96148 -2.99883 .8858 .87477 9.042 11.771)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="icc2Jnc" cx="0" cy="0" r="1" gradientTransform="rotate(90.75 5.051 15.51)scale(2.36583 .94572)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iCafujb" cx="0" cy="0" r="1" gradientTransform="matrix(.06618 .81937 -1.57296 .12705 13.514 13.527)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="izShIgd" cx="0" cy="0" r="1" gradientTransform="matrix(.29057 7.3125 -13.1704 .52334 16.147 12.375)" gradientUnits="userSpaceOnUse"><stop offset=".903" class="t1v6xpbve"/><stop offset="1" class="d1q6mib3z"/></radialGradient><radialGradient id="iGgPtme" cx="0" cy="0" r="1" gradientTransform="matrix(.01854 .22948 -.72122 .05825 16.176 15.069)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="igCehvb" cx="0" cy="0" r="1" gradientTransform="rotate(151.474 6.275 9.327)scale(1.74565 2.80539)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iUAp1te" cx="0" cy="0" r="1" gradientTransform="rotate(131.723 4.843 10.735)scale(1.6716 2.41253)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iofAmDb" cx="0" cy="0" r="1" gradientTransform="rotate(-73.644 13.375 -.535)scale(7.22156 10.2473)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iEVl32d" cx="0" cy="0" r="1" gradientTransform="rotate(-107.67 14.667 -1.79)scale(6.34509 9.00362)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="i5VmTKc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24517 -2.15444 2.54336 -1.46995 18.203 7.794)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iMFpLRc" cx="0" cy="0" r="1" gradientTransform="rotate(175.382 7.515 3.792)scale(2.07599 .77048)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iP06rid" cx="0" cy="0" r="1" gradientTransform="matrix(2.63845 -5.03453 5.57774 2.92313 10.268 11.104)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="idbmCae" cx="0" cy="0" r="1" gradientTransform="matrix(3.03146 -2.9227 4.54609 4.71527 17.09 9.304)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="iG7hqPP" cx="0" cy="0" r="1" gradientTransform="matrix(2.53148 -2.71027 4.97078 4.64288 17.845 10.433)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="igC2rKd" cx="0" cy="0" r="1" gradientTransform="matrix(3.0336 .44017 -.18727 1.29064 16.91 8.785)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iQLms4N" cx="0" cy="0" r="1" gradientTransform="matrix(.0616 .76271 -1.21318 .098 17.616 12.798)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="q-01web3x"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="igen-76bd"/></radialGradient><radialGradient id="iNidyed" cx="0" cy="0" r="1" gradientTransform="matrix(-.24011 -.26268 .36165 -.33058 17.407 12.894)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="id19zHc" cx="0" cy="0" r="1" gradientTransform="rotate(85.382 -.36 13.889)scale(.76523 1.2172)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="q-01web3x"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="igen-76bd"/></radialGradient><radialGradient id="iGaKLFV" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.192 .163)scale(.46489 .5588)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibq4qQc" cx="0" cy="0" r="1" gradientTransform="matrix(.76121 2.06115 -1.9665 .72626 19.907 12.626)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="i1sA7ke" cx="0" cy="0" r="1" gradientTransform="matrix(.6585 -1.07615 .90203 .55195 20.287 13.11)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="i4x7PUb" cx="0" cy="0" r="1" gradientTransform="matrix(.4341 -1.5021 2.00702 .58002 20.407 13.264)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iqGYT0c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5589 .12592 -.1404 -1.73816 10.994 13.955)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iAYA04b" cx="0" cy="0" r="1" gradientTransform="rotate(165.641 4.641 7.671)scale(.87702 .89922)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="imJAmob" cx="0" cy="0" r="1" gradientTransform="matrix(.29255 -1.0537 .61294 .17017 15.455 17.501)" gradientUnits="userSpaceOnUse"><stop class="r0ugjwbbg"/><stop offset="1" class="a0ne21apb"/></radialGradient><linearGradient id="iEIoQKD" x1="3.489" x2="5.693" y1="12.859" y2="13.605" gradientUnits="userSpaceOnUse"><stop class="boexhflwz"/><stop offset="1" class="bkpp_-h3a"/></linearGradient><linearGradient id="iUkIVSb" x1="3.993" x2="6.149" y1="12.655" y2="14.804" gradientUnits="userSpaceOnUse"><stop class="aromb5itn"/><stop offset="1" class="f6ufzvbyl"/></linearGradient><linearGradient id="iPV0H8x" x1="2.395" x2="4.433" y1="13.239" y2="13.802" gradientUnits="userSpaceOnUse"><stop class="boexhflwz"/><stop offset="1" class="bkpp_-h3a"/></linearGradient><linearGradient id="iX81ljj" x1="2.926" x2="5.336" y1="12.925" y2="15.139" gradientUnits="userSpaceOnUse"><stop class="aromb5itn"/><stop offset="1" class="f6ufzvbyl"/></linearGradient><linearGradient id="iVceCfd" x1="2.441" x2="4.683" y1="14.176" y2="14.974" gradientUnits="userSpaceOnUse"><stop class="boexhflwz"/><stop offset="1" class="bkpp_-h3a"/></linearGradient><linearGradient id="iqbek6b" x1="2.85" x2="5.442" y1="13.916" y2="15.915" gradientUnits="userSpaceOnUse"><stop class="aromb5itn"/><stop offset="1" class="f6ufzvbyl"/></linearGradient><linearGradient id="iTe9lMb" x1="2.764" x2="4.938" y1="15.129" y2="16.009" gradientUnits="userSpaceOnUse"><stop class="boexhflwz"/><stop offset="1" class="bkpp_-h3a"/></linearGradient><linearGradient id="iL9u69b" x1="8.486" x2="7.645" y1="16.199" y2="16.199" gradientUnits="userSpaceOnUse"><stop offset=".005" class="ekb7ro69z"/><stop offset="1" class="opwa50pmp"/></linearGradient><linearGradient id="iwScDjd" x1="5.581" x2="5.581" y1="17.122" y2="16.342" gradientUnits="userSpaceOnUse"><stop class="dyeknzb3w"/><stop offset="1" class="q4wygiatd"/></linearGradient><linearGradient id="iZBOZec" x1="23.526" x2="24.323" y1="16.098" y2="16.098" gradientUnits="userSpaceOnUse"><stop class="frlo14w5r"/><stop offset="1" class="sppcpbbqx"/></linearGradient><linearGradient id="iCwkACc" x1="28.122" x2="25.428" y1="14.356" y2="14.315" gradientUnits="userSpaceOnUse"><stop class="gg02bmwvi"/><stop offset="1" class="fh9qxk96g"/></linearGradient><linearGradient id="i134RNb" x1="29.194" x2="26.65" y1="14.878" y2="14.845" gradientUnits="userSpaceOnUse"><stop class="gg02bmwvi"/><stop offset="1" class="fh9qxk96g"/></linearGradient><linearGradient id="iAQtl3m" x1="29.167" x2="26.398" y1="15.639" y2="15.594" gradientUnits="userSpaceOnUse"><stop class="gg02bmwvi"/><stop offset="1" class="fh9qxk96g"/></linearGradient><linearGradient id="iZZveFb" x1="28.853" x2="26.078" y1="16.417" y2="16.367" gradientUnits="userSpaceOnUse"><stop class="gg02bmwvi"/><stop offset="1" class="fh9qxk96g"/></linearGradient><linearGradient id="imojtbd" x1="14.869" x2="17.387" y1="20.148" y2="22.254" gradientUnits="userSpaceOnUse"><stop class="wqky8cckq"/><stop offset="1" class="jqm256bpp"/></linearGradient><linearGradient id="iFgzOcc" x1="20.61" x2="18.233" y1="15.018" y2="15.21" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iYnwDsc" x1="16.473" x2="15.688" y1="14.396" y2="14.492" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="i2IneHe" x1="15.772" x2="15.737" y1="15.53" y2="15.093" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iH6TWTs" x1="15.566" x2="15.608" y1="12.987" y2="13.501" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="ioz6pVb" x1="16.173" x2="16.159" y1="15.628" y2="15.447" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="i2fUMdu" x1="21.646" x2="10.729" y1="7.981" y2="8.863" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iyy8ACc" x1="18.351" x2="18.071" y1="12.789" y2="12.995" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icdR21d" x1="14.215" x2="13.936" y1="13.123" y2="13.328" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibsD8rb" x1="21.621" x2="20.652" y1="12.551" y2="14.688" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="irUd7Td" x1="10.125" x2="11.486" y1="14.148" y2="13.917" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="ixKYt1b" x1="20.651" x2="20.796" y1="12.271" y2="14.061" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="iE0EJKd" x1="3.139" x2="5.946" y1="14.943" y2="16.625" gradientUnits="userSpaceOnUse"><stop class="aromb5itn"/><stop offset="1" class="f6ufzvbyl"/></linearGradient><linearGradient id="i2FpN8d" x1="9.349" x2="12.349" y1="26.596" y2="20.939" gradientUnits="userSpaceOnUse"><stop class="uwc1wf0xf"/><stop offset="1" class="mpi5j3bwz"/></linearGradient><linearGradient id="iLy4DCD" x1="7.972" x2="7.183" y1="16.45" y2="15.403" gradientUnits="userSpaceOnUse"><stop class="jxjajz9tl"/><stop offset="1" class="kaca80g6a"/></linearGradient><filter id="iJAcc6P" width="3.052" height="2.539" x="3.293" y="12.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".15"/></filter><filter id="iAxXgjd" width="3.127" height="2.723" x="2.215" y="12.481" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".15"/></filter><filter id="ityLeqb" width="3.267" height="2.534" x="2.145" y="13.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".15"/></filter><filter id="ikJNPZb" width="3.408" height="5.156" x="23.526" y="11.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.427451 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4188"/></filter><filter id="iFpxGTc" width="23.107" height="13.423" x="4.271" y="17.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.294118 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4188"/></filter><filter id="i7QzU4c" width="10.736" height="11.854" x="10.652" y="8.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4188"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4188" result="effect2_innerShadow_4002_4188"/></filter><filter id="iYW1c5d" width="3.768" height="4.763" x="13.668" y="12.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".5"/></filter><filter id="id8ko0c" width="2.168" height="3.159" x="14.649" y="12.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".1"/></filter><filter id="iAPuZqc" width="12.116" height="8.445" x="9.241" y="4.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4188"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4188" result="effect2_innerShadow_4002_4188"/></filter><filter id="iOGPcsb" width="2.237" height="1.051" x="16.886" y="10.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4188"/></filter><filter id="i7RIMbb" width="2.176" height="1.231" x="11.976" y="10.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4188"/></filter><filter id="iZeq8Sd" width="6.618" height="6.502" x="9.312" y="5.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4188"/><feGaussianBlur result="effect2_foregroundBlur_4002_4188" stdDeviation=".25"/></filter><filter id="iFs0ioe" width="7.072" height="5.584" x="14.79" y="6.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4188"/><feGaussianBlur result="effect2_foregroundBlur_4002_4188" stdDeviation=".25"/></filter><filter id="ijboCRd" width=".729" height=".693" x="16.922" y="12.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".05"/></filter><filter id="iSZPYQd" width=".875" height=".893" x="17.712" y="12.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".1"/></filter><filter id="ik6gOJb" width=".97" height="1.009" x="13.53" y="12.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".1"/></filter><filter id="iu8DrTo" width=".85" height=".703" x="12.825" y="12.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".05"/></filter><filter id="i78vfBb" width="1.354" height="2.26" x="9.925" y="12.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".125"/></filter><filter id="iyyGAId" width="1.861" height="2.798" x="19.811" y="11.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".25"/></filter><filter id="ix4YVPe" width="2.277" height="1.241" x="11.886" y="10.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".125"/></filter><filter id="ibbhOxF" width="2.335" height="1.043" x="16.805" y="10.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".125"/></filter><filter id="ieGWRDd" width="3.431" height="2.258" x="2.443" y="14.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".15"/></filter><filter id="id4lf0u" width="1.88" height="1.863" x="14.878" y="15.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".05"/></filter><filter id="iTcFj2c" width="4.656" height="7.656" x="8.349" y="19.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".4"/></filter><filter id="iMlhIRx" width="5.216" height="2.806" x="15.825" y="6.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".3"/></filter><filter id="ikJE2qh" width="2.543" height="1.191" x="5.62" y="15.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".15"/></filter><filter id="iUZ2Svc" width="2.847" height=".977" x="24.994" y="15.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4188" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-shrugging-medium" /></template>
<style>
.a0ne21apb {
  stop-color: var(--svg-color--af867f, #AF867F);
  stop-opacity: 0;
}

.a7wya1e_a {
  stop-color: var(--svg-color--ff4412, #FF4412);
  stop-opacity: 0;
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.aonrc8zob {
  d: path("M19.694 7.211c.497.128.958.43 1.271.892c.501.736.511 1.664.092 2.383c-.145.256-.211.55-.188.843l.09 1.117a1.65 1.65 0 0 0-.647-.202l-.048-1.516a1.367 1.367 0 0 0-1.405-1.242l-1.317.107a2.29 2.29 0 0 1-2.188-1.189a.63.63 0 0 0-.61-.346l-1.197.096c-1.735.14-3.026 1.676-2.885 3.43l.146 1.444a1.6 1.6 0 0 0-.657.302l-.091-1.128a1.47 1.47 0 0 0-.32-.802a2.26 2.26 0 0 1-.321-2.288a2.2 2.2 0 0 1 1.136-1.157a2.53 2.53 0 0 0 1.217-1.15A2.19 2.19 0 0 1 14.42 5.73c.372.127.775.095 1.122-.09c.255-.133.539-.222.843-.246a2.19 2.19 0 0 1 1.956.913c.328.455.81.766 1.353.905");
}

.aromb5itn {
  stop-color: var(--svg-color--ad887b, #AD887B);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bkpp_-h3a {
  stop-color: var(--svg-color--8b6e5a, #8B6E5A);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.boexhflwz {
  stop-color: var(--svg-color--997761, #997761);
}

.bsbwju02k {
  d: path("M15.818 21.37c-1.104 0-2-.803-2-1.79v-2.115c0-.989.896-1.79 2-1.79s2 .801 2 1.79v2.114c0 .988-.896 1.79-2 1.79");
}

.bsgi7geqg {
  fill: var(--svg-color--563936, #563936);
  d: path("m20.341 11.205l-.075-.592A1.38 1.38 0 0 0 18.85 9.38l-1.302.105a2.26 2.26 0 0 1-2.072-1.025s-.046-.086-.104-.24c-.359-.938.513-1.746 1.503-1.576c.862.149 1.826.414 2.586.831c1.71.939 1.661 2.754.88 3.73");
}

.byn2s1bln {
  stop-color: var(--svg-color--d45533, #D45533);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c0we-jd3m {
  d: path("M9.13 21.277a.25.25 0 0 1-.375-.217v-2.864a.6.6 0 0 0-.6-.6H4.871a.6.6 0 0 0-.6.6v4.587c-.005.85.112 2.507 1.484 3.383c1.149.733 2.501.57 3.214.347a.16.16 0 0 1 .208.148v3.706c0 .083.067.15.15.15h12.994a.15.15 0 0 0 .15-.15v-3.706c0-.106.108-.18.209-.148c.713.222 2.064.386 3.213-.347c1.372-.876 1.49-2.534 1.485-3.383v-4.587a.6.6 0 0 0-.6-.6h-3.285a.6.6 0 0 0-.6.6v2.864a.25.25 0 0 1-.375.217l-6.694-3.932z");
}

.c6gsbc5ms {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.261 11.43c.228-.193.805-.547 1.527-.485");
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crjf7pa5p {
  stop-color: var(--svg-color--915466, #915466);
  stop-opacity: 0;
}

.d1q6mib3z {
  stop-color: var(--svg-color--9a515f, #9A515F);
}

.d348e2bmq {
  stop-color: var(--svg-color--92576f, #92576F);
  stop-opacity: 0;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dop1c2kyt {
  fill-rule: evenodd;
  d: path("M29.471 12.63a.7.7 0 0 0-.977.157q-.05.071-.115.168c-.262.391-.921 1.113-1.733 1.46c-.355.153-.503.45-.32.876c.152.355.733.503 1.088.35c1.246-.533 1.935-1.602 2.156-1.945l.058-.089a.7.7 0 0 0-.157-.977");
}

.dp-pe5xra {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M2.715 12.98c.196.502.844 1.46 2.127 1.724");
}

.dyeknzb3w {
  stop-color: var(--svg-color--753d27, #753D27);
}

.edi105b3p {
  d: path("m20.341 11.205l-.075-.592A1.38 1.38 0 0 0 18.85 9.38l-1.302.105a2.26 2.26 0 0 1-2.072-1.025s-.046-.086-.104-.24c-.359-.938.513-1.746 1.503-1.576c.862.149 1.826.414 2.586.831c1.71.939 1.661 2.754.88 3.73");
}

.ekb7ro69z {
  stop-color: var(--svg-color--896e61, #896E61);
}

.eqno0223k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.35 26.127c.176-1.146.955-3.881 2.655-5.656");
}

.evf191haz {
  cx: 15.818px;
  cy: 16.821px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  rx: 0.74px;
  ry: 0.732px;
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.f6ufzvbyl {
  stop-color: var(--svg-color--ad887b, #AD887B);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fh9qxk96g {
  stop-color: var(--svg-color--b08a6f, #B08A6F);
}

.finomov8p {
  stop-color: var(--svg-color--ff7e34, #FF7E34);
}

.fipf36vin {
  stop-color: var(--svg-color--ff6f3a, #FF6F3A);
  stop-opacity: 0;
}

.fm-ag3l1v {
  stop-color: var(--svg-color--875d53, #875D53);
}

.fni_1r5pr {
  stop-color: var(--svg-color--c94829, #C94829);
}

.frlo14w5r {
  stop-color: var(--svg-color--8a6355, #8A6355);
}

.ft5dv1b6b {
  fill: none;
}

.fv3u9nbaa {
  stop-color: var(--svg-color--915466, #915466);
}

.fv5uflvts {
  d: path("M17.582 12.35a.842.842 0 0 1 .894.994l-1.621.13a.845.845 0 0 1 .727-1.126");
}

.fyhob6bpk {
  cx: 13.25px;
  cy: 13.06px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.367px;
  ry: 0.186px;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
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

.gg02bmwvi {
  stop-color: var(--svg-color--bb977a, #BB977A);
}

.gg2qh5btd {
  fill-rule: evenodd;
  d: path("M29.503 13.652a.7.7 0 0 0-.98.142l-.086.118c-.301.42-.763 1.062-1.779 1.062a.7.7 0 1 0 0 1.4c1.776 0 2.637-1.24 2.925-1.654l.062-.088a.7.7 0 0 0-.142-.98");
}

.gktx2cc_x {
  d: path("M20.3 14.63c.313-.035.6-.166.826-.358l.07.875a2.05 2.05 0 0 1-1.107 2q.2-.532.236-1.135z");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gno4tuy0h {
  stop-color: var(--svg-color--cc4525, #CC4525);
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

.h0gi5sr7l {
  stop-color: var(--svg-color--92576f, #92576F);
}

.h85_nzbgf {
  fill: var(--svg-color--000, #000);
  d: path("M17.169 13.227a.48.48 0 0 1 .441-.52a.48.48 0 0 1 .484.668l-.85.069a.44.44 0 0 1-.075-.217");
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hnslz--nu {
  d: path("M20.363 14.712q-.027-1.508-.069-3.015a1.518 1.518 0 0 1 .069 3.015");
}

.hpe9ehb7d {
  stop-color: var(--svg-color--ff8a36, #FF8A36);
  stop-opacity: 0;
}

.htnuayb0e {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.193 11.18a2.6 2.6 0 0 1 1.607-.47a.262.262 0 1 1-.021.523a2.1 2.1 0 0 0-1.282.373l-.067.05l-.015.013l-.002.002a.262.262 0 0 1-.353-.386z");
}

.hu3s1qbxb {
  fill-rule: evenodd;
  d: path("M2.513 14.683a.7.7 0 0 1 .98.142c.181.242.653.84 1.873.84a.7.7 0 1 1 0 1.4c-1.827 0-2.668-.965-2.994-1.402a.7.7 0 0 1 .141-.98");
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.ieaa_kb0h {
  stop-color: var(--svg-color--967161, #967161);
  stop-opacity: 0;
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.igen-76bd {
  stop-color: var(--svg-color--694a44, #694A44);
}

.iky79-blm {
  stop-color: var(--svg-color--9f6274, #9F6274);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j5oh69t0z {
  d: path("M10.742 12.461a1.518 1.518 0 0 0 .373 2.998a72 72 0 0 1-.373-2.998");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jqm256bpp {
  stop-color: var(--svg-color--c58c75, #C58C75);
}

.jqoxmxa7u {
  stop-color: var(--svg-color--875d53, #875D53);
  stop-opacity: 0;
}

.jtrcqfs1u {
  d: path("M11.159 15.37a1.55 1.55 0 0 1-.874-.222l.07.875c.069.84.63 1.547 1.415 1.796a3.9 3.9 0 0 1-.415-1.083z");
}

.jxjajz9tl {
  stop-color: var(--svg-color--946f66, #946F66);
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k1yfa1pxl {
  stop-color: var(--svg-color--dc4724, #DC4724);
}

.kaca80g6a {
  stop-color: var(--svg-color--946f66, #946F66);
  stop-opacity: 0;
}

.khy4tkbbd {
  stop-color: var(--svg-color--fb4b61, #FB4B61);
  stop-opacity: 0;
}

.kmr9t_apu {
  cx: 13.25px;
  cy: 13.06px;
  rx: 0.367px;
  ry: 0.186px;
}

.knz139bll {
  stroke: var(--svg-color--bf9885, #BF9885);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M25.394 16.357h1.515a.7.7 0 0 0 .532-.172");
}

.ktwlew6wq {
  cx: 15.818px;
  cy: 16.821px;
  fill: var(--svg-color--87004d, #87004D);
  rx: 0.74px;
  ry: 0.732px;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kvh590ikm {
  stop-color: var(--svg-color--9a7b65, #9A7B65);
  stop-opacity: 0;
}

.kxvovqbaa {
  d: path("M18.388 13.017a.8.8 0 0 0-.253-.417l-.223.288l.128.205z");
}

.l38hnxbpk {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.533 12.532c.066.075-.051.182-.184.3s-.232.2-.299.125s-.011-.23.122-.348s.295-.152.36-.077");
}

.l501wpbht {
  fill-rule: evenodd;
  d: path("M3.263 12.314a.7.7 0 0 1 .978.157c.044.061.088.136.115.182l.005.01l.001.002q.05.086.105.174c.077.12.17.25.294.37c.233.228.608.468 1.267.5a.7.7 0 1 1-.068 1.398c-1.025-.05-1.718-.447-2.179-.898a3.5 3.5 0 0 1-.495-.618a6 6 0 0 1-.13-.216l-.004-.007l-.045-.075v-.002a.7.7 0 0 1 .156-.978");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lcvkdjbxr {
  d: path("M10.808 13.081a.902.902 0 0 0 .221 1.76a73 73 0 0 1-.221-1.76");
}

.lf6x2hczr {
  d: path("M26.916 17.158a.25.25 0 0 0-.25-.25h-2.93a.25.25 0 0 0-.25.25v.844h3.43z");
}

.lhs441rxk {
  stop-color: var(--svg-color--9a7b65, #9A7B65);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llqxe3bem {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M3.793 12.7c.196.502 1.018 1.388 2.052 1.54");
}

.lslkpqbsz {
  stop-color: var(--svg-color--8e6854, #8E6854);
  stop-opacity: 0;
}

.m6msjkbjj {
  d: path("M25.951 12.121a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.259v-2.698h-1.627a1.3 1.3 0 0 1 .128-.204l.804-1.047a.75.75 0 0 0-.138-1.052");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mpi5j3bwz {
  stop-color: var(--svg-color--c13318, #C13318);
  stop-opacity: 0;
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nsvw3qbwe {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M18.917 10.74a1.75 1.75 0 0 0-.677-.334c-.294-.067-.654-.062-1.145.038a.262.262 0 0 0 .106.513c.447-.092.727-.086.922-.041c.191.043.325.128.483.245a.261.261 0 1 0 .311-.42");
}

.nu0upxjqp {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.138 13.374l-.458 1.776c-.073.364.2.7.547.672l.74-.06c.346-.028.562-.409.432-.75l-.64-1.688c-.138-.374-.54-.342-.621.05");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nw6x2sbzm {
  fill-rule: evenodd;
  d: path("M2.192 13.652a.7.7 0 0 1 .98.142l.086.118c.301.42.763 1.062 1.779 1.062a.7.7 0 1 1 0 1.4c-1.776 0-2.637-1.24-2.925-1.654l-.062-.088a.7.7 0 0 1 .142-.98");
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.oliv2bcuo {
  stop-color: var(--svg-color--fe7047, #FE7047);
}

.opwa50pmp {
  stop-color: var(--svg-color--896e61, #896E61);
  stop-opacity: 0;
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.ph51elbbd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.26 12.441a1.32 1.32 0 0 0-1.193 1.098a.26.26 0 0 0 .277.3l2.098-.169a.217.217 0 0 0 .193-.273a1.32 1.32 0 0 0-1.375-.956");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plknl7b1w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M2.645 13.99c.238.483.966 1.38 2.267 1.534");
}

.plq4hrpyc {
  d: path("M5.744 12.121a.75.75 0 0 1 1.051.138l.805 1.047c.37.48.57 1.07.57 1.676v2.14H4.911v-2.698h1.626a1.3 1.3 0 0 0-.127-.204l-.805-1.047a.75.75 0 0 1 .138-1.052");
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.pqi97va-m {
  d: path("M4.779 17.158a.25.25 0 0 1 .25-.25h2.93a.25.25 0 0 1 .25.25v.844h-3.43z");
}

.q-01web3x {
  stop-color: var(--svg-color--7e574a, #7E574A);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q4wygiatd {
  stop-color: var(--svg-color--753d27, #753D27);
  stop-opacity: 0;
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qfj8esbtd {
  stop-color: var(--svg-color--f05419, #F05419);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qm_p1qb1x {
  d: path("m15.22 13.182l-.36 1.769c-.073.363.2.7.547.671l.74-.06c.346-.028.562-.408.432-.75l-.64-1.688c-.138-.374-.637-.334-.719.058");
}

.qm-9wjixk {
  stop-color: var(--svg-color--9f6274, #9F6274);
}

.qrv_azbvd {
  stop-color: var(--svg-color--c6a18a, #C6A18A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-dr48byv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M2.943 15.041c.293.452 1.122 1.258 2.431 1.258");
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r0ugjwbbg {
  stop-color: var(--svg-color--af867f, #AF867F);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rlyk3nhtu {
  fill: var(--svg-color--6c4a4b, #6C4A4B);
  d: path("M19.159 8.218h-2.22a.515.515 0 1 1 .083-1.025c.576.092 1.34.22 1.852.347c1.158.287 1.478.85 1.567 1.253a1.61 1.61 0 0 0-1.282-.575");
}

.ro-sdi-ns {
  d: path("M17.533 12.532c.066.075-.051.182-.184.3s-.232.2-.299.125s-.011-.23.122-.348s.295-.152.36-.077");
}

.roca9nbvr {
  d: path("M13.475 12.68a.842.842 0 0 0-.723 1.126l1.621-.13a.847.847 0 0 0-.898-.995");
}

.rqxwi30ib {
  stop-color: var(--svg-color--8e6854, #8E6854);
}

.rx-90_bsr {
  stop-color: var(--svg-color--c94829, #C94829);
  stop-opacity: 0;
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.sa81twb1r {
  fill: var(--svg-color--000, #000);
  d: path("M14.023 13.481a.48.48 0 0 0-.519-.442a.48.48 0 0 0-.37.736l.85-.068a.5.5 0 0 0 .04-.226");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sppcpbbqx {
  stop-color: var(--svg-color--8a6355, #8A6355);
  stop-opacity: 0;
}

.suj071bwa {
  d: path("M14.3 13.358c-.022-.27-.256-.433-.32-.482l-.25.283l.194.325z");
}

.t1g9ceb8j {
  d: path("M15.412 8.449a2 2 0 0 1-.073-.124a.63.63 0 0 0-.61-.347l-1.197.097c-1.735.14-3.026 1.676-2.884 3.43l.02.26c-.339-.218-.782-.699-.85-1.53c-.08-1.007.613-1.576 1.056-1.938c.125-.103.23-.189.291-.264q.04-.047.086-.106c.3-.375.836-1.043 1.836-1.397c.471-.166.956-.24 1.359-.267c.472-.03.837.35.875.821l.11 1.35z");
}

.t1v6xpbve {
  stop-color: var(--svg-color--9a515f, #9A515F);
  stop-opacity: 0;
}

.t4gnjqvlq {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.756 12.078a1.32 1.32 0 0 1 1.354.892a.26.26 0 0 1-.226.341l-2.098.17a.217.217 0 0 1-.234-.239a1.32 1.32 0 0 1 1.204-1.164");
}

.teu5d39go {
  stop-color: var(--svg-color--967161, #967161);
}

.tg0z2qhwd {
  stop-color: var(--svg-color--ff8a36, #FF8A36);
}

.tvdh3pi4i {
  fill: var(--svg-color--b08a6f, #B08A6F);
  d: path("M25.951 12.121a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.259v-2.698h-1.627a1.3 1.3 0 0 1 .128-.204l.804-1.047a.75.75 0 0 0-.138-1.052");
}

.u_7m_6tiu {
  stop-color: var(--svg-color--c6a18a, #C6A18A);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uudqsyb7t {
  stop-color: var(--svg-color--c5a28a, #C5A28A);
  stop-opacity: 0;
}

.uwc1wf0xf {
  stop-color: var(--svg-color--c13318, #C13318);
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vc_133bog {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.22 13.182l-.36 1.769c-.073.363.2.7.547.671l.74-.06c.346-.028.562-.408.432-.75l-.64-1.688c-.138-.374-.637-.334-.719.058");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vpgp1b8tt {
  stop-color: var(--svg-color--c5a28a, #C5A28A);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w16pczbvt {
  fill-rule: evenodd;
  d: path("M28.432 12.314a.7.7 0 0 0-.977.157a2 2 0 0 0-.115.182l-.006.01l-.001.002a5 5 0 0 1-.105.174a2 2 0 0 1-.294.37c-.232.228-.607.468-1.267.5a.7.7 0 1 0 .069 1.398c1.024-.05 1.717-.447 2.178-.898a3.4 3.4 0 0 0 .495-.618a5 5 0 0 0 .13-.216l.004-.007l.045-.075l.001-.002a.7.7 0 0 0-.157-.978");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wqky8cckq {
  stop-color: var(--svg-color--864e53, #864E53);
}

.wrz93t-rl {
  fill: var(--svg-color--533634, #533634);
  d: path("M15.412 8.449a2 2 0 0 1-.073-.124a.63.63 0 0 0-.61-.347l-1.197.097c-1.735.14-3.026 1.676-2.884 3.43l.02.26c-.339-.218-.782-.699-.85-1.53c-.08-1.007.613-1.576 1.056-1.938c.125-.103.23-.189.291-.264q.04-.047.086-.106c.3-.375.836-1.043 1.836-1.397c.471-.166.956-.24 1.359-.267c.472-.03.837.35.875.821l.11 1.35z");
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.wz_ov4j-l {
  stop-color: var(--svg-color--fb4b61, #FB4B61);
}

.x_u-3jb7a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.12 16.45h.998c.227 0 .444.09.604.25v0");
}

.xgt3psbhd {
  d: path("M11.308 16.79a3.69 3.69 0 0 0 3.912 2.907l1.773-.143a3.69 3.69 0 0 0 3.395-3.497c-.033-1.78-.063-3.552-.124-5.329a1.367 1.367 0 0 0-1.405-1.241l-1.317.106a2.29 2.29 0 0 1-2.188-1.189a.63.63 0 0 0-.61-.346l-1.197.096c-1.735.14-3.026 1.676-2.885 3.43c.142 1.75.39 3.462.646 5.207");
}

.xjy_9rbsx {
  fill: var(--svg-color--8b6e5a, #8B6E5A);
  d: path("M5.744 12.121a.75.75 0 0 1 1.051.138l.805 1.047c.37.48.57 1.07.57 1.676v2.14H4.911v-2.698h1.626a1.3 1.3 0 0 0-.127-.204l-.805-1.047a.75.75 0 0 1 .138-1.052");
}

.xo_dbbcrk {
  stop-color: var(--svg-color--ff6f3a, #FF6F3A);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xt2-624jk {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.765 10.87c-.256-.153-.882-.41-1.585-.232");
}

.xw4oh8inu {
  d: path("M20.351 14.097q-.018-.9-.04-1.798a.901.901 0 0 1 .04 1.798");
}

.xx0si6etu {
  stop-color: var(--svg-color--ff7e32, #FF7E32);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yaxmr2k5m {
  fill-rule: evenodd;
  d: path("M29.19 14.683a.7.7 0 0 0-.979.142c-.18.242-.653.84-1.873.84a.7.7 0 1 0 0 1.4c1.828 0 2.668-.965 2.995-1.402a.7.7 0 0 0-.142-.98");
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yenur026f {
  fill-rule: evenodd;
  d: path("M2.224 12.63a.7.7 0 0 1 .978.157q.051.071.114.168c.262.391.704 1.052 1.516 1.4a.7.7 0 1 1-.551 1.286c-1.246-.533-1.935-1.602-2.156-1.945l-.058-.089a.7.7 0 0 1 .157-.977");
}

.zk2mfu__s {
  stop-color: var(--svg-color--ff7e32, #FF7E32);
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
