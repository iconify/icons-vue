<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ii1n4Zb)" class="fpc-w8unn"/><path fill="url(#ibfv0gb)" class="fpc-w8unn"/><g filter="url(#iy0pI7c)"><path class="g2-7i-ngi"/></g><g filter="url(#iPJuvsb)"><path class="sx8bpzjax"/></g><path fill="url(#itSRADc)" class="exvucxbiq"/><path fill="url(#igJ2lEb)" class="exvucxbiq"/><path fill="url(#iYOtWUb)" class="exvucxbiq"/><path fill="url(#iE5g3gb)" class="xc6znrbjq"/><path fill="url(#i0lVWpe)" class="xc6znrbjq"/><g filter="url(#i5V4PVd)"><path fill="url(#ieGD6ac)" class="vlp0azbmu"/><path fill="url(#iZLNDad)" class="vlp0azbmu"/><path fill="url(#inid5Fe)" class="vlp0azbmu"/></g><path fill="url(#i94DaMb)" class="vlp0azbmu"/><path fill="url(#iLsRwmu)" class="vlp0azbmu"/><g filter="url(#iL31SBc)"><path fill="url(#iSZPzCb)" class="t3l2nob9f"/></g><g filter="url(#i0EAPXd)"><path class="tl0sjenli"/><path fill="url(#itkESmc)" class="yi0b9jgtv"/></g><path fill="url(#igaeQHe)" class="dem1xwbda"/><path fill="url(#iC4gGWb)" class="dem1xwbda"/><path fill="url(#iEpnpvd)" class="zmh2_lmnk"/><path fill="url(#iUMX9Yy)" class="gyd099b4k"/><path fill="url(#i8IKsne)" class="gyd099b4k"/><path fill="url(#i3dQgzj)" class="gyd099b4k"/><path fill="url(#i71Ib1b)" class="valti_bse"/><path fill="url(#i8uZmVU)" class="x3hzs9tmh"/><path fill="url(#iSl73Kj)" class="l2hsst8bw"/><g filter="url(#it4jDGd)"><path fill="url(#iDd01eb)" class="w087w3bpc"/><path fill="url(#iVbsg7c)" class="w087w3bpc"/></g><path fill="url(#izZLa6d)" class="w087w3bpc"/><path fill="url(#iNyJpXz)" class="w087w3bpc"/><path fill="url(#i2t3Y4d)" class="w087w3bpc"/><path fill="url(#iRvT8kc)" class="w087w3bpc"/><path fill="url(#igElfLd)" class="w087w3bpc"/><path fill="url(#i2pWaQe)" class="w087w3bpc"/><path fill="url(#isRJ0Cc)" class="w087w3bpc"/><path fill="url(#iJnl4bc)" class="w087w3bpc"/><g filter="url(#i8YjLLd)"><path class="uhq0gwwyn"/></g><g filter="url(#iBPmoBd)"><path class="ohfehdckv"/><path fill="url(#ipvwJne)" class="g62f-n79w"/><path fill="url(#iz5uCDd)" class="g62f-n79w"/><path fill="url(#iexylQo)" class="g62f-n79w"/><path fill="url(#ifLvhzi)" class="g62f-n79w"/><path fill="url(#i3QHWGc)" class="g62f-n79w"/></g><path fill="url(#i2k5xCl)" class="g62f-n79w"/><path fill="url(#irwIomO)" class="g62f-n79w"/><g filter="url(#i2Yegde)"><path stroke="url(#ilSI5ue)" class="v4osrdkmw"/></g><path fill="url(#iLUHVyW)" class="uihc23imt"/><g filter="url(#i3hZCpd)"><path fill="url(#icq2Jmc)" class="p1dw5abzj"/></g><path fill="url(#iFdRkyv)" class="p1dw5abzj"/><path fill="url(#iGt13je)" class="p1dw5abzj"/><path fill="url(#iS9wlBR)" class="p1dw5abzj"/><g filter="url(#iavuySd)"><path class="uhzi7gbie"/></g><g filter="url(#igaehQN)"><path class="mo8lftlng"/></g><g filter="url(#iMIreTb)"><path class="j173kr6rw"/><path fill="url(#iHzDPjd)" class="rdwqpggao"/><path fill="url(#ibjp91d)" class="rdwqpggao"/></g><g filter="url(#iJBm6Db)"><path class="f5wjdob6q"/><path fill="url(#iBA7Uhc)" class="h--7-vbqp"/><path fill="url(#iq1S3ze)" class="h--7-vbqp"/><path fill="url(#itF87Ee)" class="h--7-vbqp"/></g><path class="fz7mqmbsd"/><path fill="url(#ia4ER4v)" class="bcy2aobtr"/><path class="vcj80-e7h"/><g filter="url(#im0i2zb)"><path class="pyudvfb2c"/><path fill="url(#ipiipGd)" class="pupoqrb5v"/></g><g filter="url(#iQD7EFd)"><path fill="url(#iK5aU7q)" class="ez-5bos4p"/></g><path class="p0mqqhbpw"/><path fill="url(#iEM5nNb)" class="q6i4_kbfn"/><path class="yrghyesqm"/><g filter="url(#igN0Jdd)"><path fill="url(#iLYJsEc)" class="psxy-7s6u"/></g><g filter="url(#icf1OHc)"><ellipse transform="rotate(-27.914 13.532 9.859)" class="b_rys6b4a"/><ellipse fill="url(#im10iMM)" transform="rotate(-27.914 13.532 9.859)" class="xswnovbcd"/></g><path fill="url(#i3RPg4b)" class="xae-wqulm"/><path fill="url(#isbz7mb)" class="xae-wqulm"/><path fill="url(#iXTtMOb)" class="xae-wqulm"/><path fill="url(#i1gHszn)" class="xae-wqulm"/><path fill="url(#ipccdnm)" class="nfaftvbmv"/><path fill="url(#iht08Vc)" class="nfaftvbmv"/><g filter="url(#iwcJiEG)"><path fill="url(#i76UXEb)" class="q_pb1qt5c"/></g><g filter="url(#iyt5ZWb)"><path fill="url(#inTxsPd)" class="sgj6doz-q"/></g><g filter="url(#iJTIgqb)"><path class="y44mbrbnq"/></g><g filter="url(#ig4l9od)"><path class="gp34_acsp"/></g><g filter="url(#iug7onx)"><path class="ikfmx-b8m"/></g><defs><radialGradient id="ibfv0gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4313 6.37009 0 22.995 25.46)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="m5bm-ccxd"/><stop offset="1" class="q8ootib3t"/></radialGradient><radialGradient id="itSRADc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1215 -4.59696 0 16 23.032)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="wdy63qb5p"/><stop offset="1" class="gkzmut59n"/></radialGradient><radialGradient id="iE5g3gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3135 1.68433 0 25 29.967)" gradientUnits="userSpaceOnUse"><stop class="omh3jbc5e"/><stop offset="1" class="g1k32m_rh"/></radialGradient><radialGradient id="inid5Fe" cx="0" cy="0" r="1" gradientTransform="rotate(126.18 2.711 11.651)scale(2.59394 3.59462)" gradientUnits="userSpaceOnUse"><stop class="yfhz1ybyq"/><stop offset="1" class="kyt4h2bsk"/></radialGradient><radialGradient id="iLsRwmu" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 -.3125 .15357 .53751 11.395 19.723)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="som6k-b6q"/><stop offset="1" class="pc2b66ykc"/></radialGradient><radialGradient id="igaeQHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -4.3769 0 16 18.481)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="ft6yvtbqk"/><stop offset="1" class="i_25dj3ib"/></radialGradient><radialGradient id="iC4gGWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 6.81546 0 16 20.978)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="kx98i3bkm"/><stop offset=".876" class="mf716dhmi"/></radialGradient><radialGradient id="iUMX9Yy" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -3.45478 0 15.982 21.38)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lv0iykbih"/><stop offset=".94" class="s3tb_6b2n"/></radialGradient><radialGradient id="i71Ib1b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.42103 -1.24999 2.39752 -2.72558 17.45 17.835)" gradientUnits="userSpaceOnUse"><stop class="bue2cdcwr"/><stop offset="1" class="grvlbeqgj"/></radialGradient><radialGradient id="i8uZmVU" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.88 20.81)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iSl73Kj" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.929 12.302)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iDd01eb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 18.793 10.87)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iVbsg7c" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.545 8.137)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iNyJpXz" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.479 -11.1622 0 16.544 4.7)" gradientUnits="userSpaceOnUse"><stop offset=".659" class="iwxeu3bsl"/><stop offset=".782" class="n55pjdbhv"/><stop offset=".93" class="c939rfb8g"/></radialGradient><radialGradient id="i2t3Y4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.432 9.558)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iRvT8kc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.662 -2.065)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="igElfLd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.522 6.235)scale(8.51289 21.7462)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i2pWaQe" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.193 8.138)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="isRJ0Cc" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.144 13.777)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iJnl4bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 13.77 10.375)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iz5uCDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.451 12.231)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="ifLvhzi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 16.567 11.662)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="irwIomO" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.931 8.974)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iLUHVyW" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 15.494 14.494)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iFdRkyv" cx="0" cy="0" r="1" gradientTransform="matrix(2.7406 -7.14959 10.14519 3.88889 10.278 8.946)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iGt13je" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 14.407 -4.103)scale(6.72756 9.54634)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iS9wlBR" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 11.098 -3.714)scale(2.63838 3.11466)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iHzDPjd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.238 3.68)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="ibjp91d" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.191 -5.764)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iBA7Uhc" cx="0" cy="0" r="1" gradientTransform="matrix(3.5152 -2.83003 4.38594 5.4478 17.904 6.235)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="iq1S3ze" cx="0" cy="0" r="1" gradientTransform="matrix(2.95886 -2.64821 4.8482 5.41692 18.619 7.493)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="itF87Ee" cx="0" cy="0" r="1" gradientTransform="matrix(3.22527 .72413 -.30318 1.35036 17.755 5.672)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="ia4ER4v" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.167 9.954)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ipiipGd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.428 .626)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iEM5nNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.803 9.954)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="im10iMM" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.517 10.173)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isbz7mb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.603 9.968)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iXTtMOb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.963 10.513)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="i1gHszn" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.077 10.685)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iht08Vc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.07 10.61)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i76UXEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.07 10.613)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><linearGradient id="ii1n4Zb" x1="16" x2="16" y1="16.278" y2="31.216" gradientUnits="userSpaceOnUse"><stop class="hac9w68gp"/><stop offset="1" class="u61ykmvtc"/></linearGradient><linearGradient id="igJ2lEb" x1="18.903" x2="17.059" y1="25.278" y2="25.278" gradientUnits="userSpaceOnUse"><stop class="ugh29hhiz"/><stop offset="1" class="knib4pb5u"/></linearGradient><linearGradient id="iYOtWUb" x1="15.591" x2="15.669" y1="17.825" y2="21.716" gradientUnits="userSpaceOnUse"><stop class="ft2atdbel"/><stop offset="1" class="r8964-bmu"/></linearGradient><linearGradient id="i0lVWpe" x1="23" x2="23.744" y1="29.454" y2="29.43" gradientUnits="userSpaceOnUse"><stop offset=".276" class="alwwvg18b"/><stop offset="1" class="r8-nbsf4i"/></linearGradient><linearGradient id="ieGD6ac" x1="11.902" x2="11.902" y1="16.057" y2="29.957" gradientUnits="userSpaceOnUse"><stop class="j-er45bzw"/><stop offset=".524" class="iwz00abqx"/></linearGradient><linearGradient id="iZLNDad" x1="13.671" x2="13.05" y1="22.516" y2="22.516" gradientUnits="userSpaceOnUse"><stop class="recxkftoe"/><stop offset="1" class="btkjyionj"/></linearGradient><linearGradient id="i94DaMb" x1="11.902" x2="12.839" y1="25.933" y2="25.531" gradientUnits="userSpaceOnUse"><stop offset=".196" class="yqlqjsfuk"/><stop offset="1" class="c8t-c_brq"/></linearGradient><linearGradient id="iSZPzCb" x1="15.988" x2="15.988" y1="18.95" y2="20.934" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mu96iuqwe"/><stop offset="1" class="p-sb3ibac"/></linearGradient><linearGradient id="itkESmc" x1="18.71" x2="20.111" y1="21.564" y2="21.564" gradientUnits="userSpaceOnUse"><stop offset=".093" class="fxp5v2b6t"/><stop offset="1" class="zm9c_pbne"/></linearGradient><linearGradient id="iEpnpvd" x1="9.452" x2="7.02" y1="23.974" y2="23.974" gradientUnits="userSpaceOnUse"><stop class="rpmno-b9y"/><stop offset="1" class="a9ts2kezv"/></linearGradient><linearGradient id="i8IKsne" x1="14.606" x2="14.899" y1="24.837" y2="24.876" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="i3dQgzj" x1="17.411" x2="17.012" y1="24.653" y2="24.7" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="izZLa6d" x1="21.142" x2="18.613" y1="12.556" y2="12.556" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="ipvwJne" x1="16.823" x2="15.985" y1="11.545" y2="11.58" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iexylQo" x1="15.985" x2="15.985" y1="12.684" y2="12.22" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="i3QHWGc" x1="15.985" x2="15.985" y1="9.979" y2="10.526" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="i2k5xCl" x1="16.401" x2="16.401" y1="12.822" y2="12.63" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="ilSI5ue" x1="14.783" x2="15.102" y1="14.255" y2="13.421" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="icq2Jmc" x1="22.837" x2="11.225" y1="5.208" y2="5.208" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iK5aU7q" x1="18.945" x2="18.631" y1="10.008" y2="10.201" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLYJsEc" x1="14.547" x2="14.233" y1="10.008" y2="10.202" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3RPg4b" x1="22.421" x2="21.215" y1="10.035" y2="12.211" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="ipccdnm" x1="10.135" x2="11.594" y1="10.739" y2="10.612" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="inTxsPd" x1="21.438" x2="21.438" y1="9.726" y2="11.484" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><filter id="iy0pI7c" width="6.556" height="14.595" x="9.212" y="15.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".5"/></filter><filter id="iPJuvsb" width="3.95" height="13.362" x="17.96" y="16.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".375"/></filter><filter id="i5V4PVd" width="2.897" height="14" x="10.503" y="16.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2099"/></filter><filter id="iL31SBc" width="2.734" height="2.883" x="14.624" y="18.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2099"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2099" result="effect2_innerShadow_4002_2099"/></filter><filter id="i0EAPXd" width="2.902" height="14.05" x="18.61" y="16.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2099"/></filter><filter id="it4jDGd" width="11.22" height="12.442" x="10.922" y="4.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2099"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2099" result="effect2_innerShadow_4002_2099"/></filter><filter id="i8YjLLd" width="3.747" height="4.9" x="13.97" y="9.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".5"/></filter><filter id="iBPmoBd" width="2.277" height="3.3" x="14.846" y="9.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".1"/></filter><filter id="i2Yegde" width="3.718" height="1.573" x="14.126" y="13.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".05"/></filter><filter id="i3hZCpd" width="12.873" height="8.357" x="9.549" y="1.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2099"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2099" result="effect2_innerShadow_4002_2099"/></filter><filter id="iavuySd" width="2.339" height="1.19" x="17.574" y="7.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2099"/></filter><filter id="igaehQN" width="2.339" height="1.176" x="12.318" y="7.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2099"/></filter><filter id="iMIreTb" width="6.584" height="5.992" x="9.904" y="2.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2099"/><feGaussianBlur result="effect2_foregroundBlur_4002_2099" stdDeviation=".125"/></filter><filter id="iJBm6Db" width="7.112" height="5.986" x="15.826" y="2.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2099"/><feGaussianBlur result="effect2_foregroundBlur_4002_2099" stdDeviation=".125"/></filter><filter id="im0i2zb" width=".787" height=".696" x="17.433" y="9.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".05"/></filter><filter id="iQD7EFd" width=".891" height=".913" x="18.273" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".1"/></filter><filter id="igN0Jdd" width=".986" height="1.04" x="13.83" y="9.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".1"/></filter><filter id="icf1OHc" width=".913" height=".705" x="13.075" y="9.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".05"/></filter><filter id="iwcJiEG" width="1.329" height="2.379" x="9.904" y="9.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".125"/></filter><filter id="iyt5ZWb" width="1.806" height="2.758" x="20.535" y="9.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".25"/></filter><filter id="iJTIgqb" width="2.405" height="1.16" x="12.237" y="7.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".125"/></filter><filter id="ig4l9od" width="2.405" height="1.16" x="17.553" y="7.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".125"/></filter><filter id="iug7onx" width="5.367" height="3.046" x="17.001" y="3.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2099" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:office-worker-medium" /></template>
<style>
.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.a9ts2kezv {
  stop-color: var(--svg-color--584a7e, #584A7E);
  stop-opacity: 0;
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.alwwvg18b {
  stop-color: var(--svg-color--504176, #504176);
}

.b_rys6b4a {
  cx: 13.532px;
  cy: 9.859px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bcy2aobtr {
  d: path("M18.17 9.477a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.btkjyionj {
  stop-color: var(--svg-color--553a63, #553A63);
  stop-opacity: 0;
}

.bue2cdcwr {
  stop-color: var(--svg-color--8b645a, #8B645A);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c8t-c_brq {
  stop-color: var(--svg-color--594c7d, #594C7D);
  stop-opacity: 0;
}

.c939rfb8g {
  stop-color: var(--svg-color--904a82, #904A82);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dem1xwbda {
  d: path("M16 15.024h-2.71v4.74c0 .31.36.49.61.29L16 18.66l2.1 1.393c.25.2.61.02.61-.29v-4.74z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.exvucxbiq {
  d: path("M18.71 16.087h-5.42v13.89h5.42z");
}

.ez-5bos4p {
  d: path("M18.964 10.252a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.f5wjdob6q {
  fill: var(--svg-color--563936, #563936);
  d: path("m21.198 8.522l-.03-.632c-.01-.763-.641-1.393-1.405-1.425h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.059-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.051c1.744 1.138 1.439 3.189.52 4.155");
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fpc-w8unn {
  d: path("M16 15.467c-6.08 0-11 4.92-11 11v3.5h22v-3.5c0-6.07-4.93-11-11-11");
}

.ft2atdbel {
  stop-color: var(--svg-color--877f93, #877F93);
}

.ft5dv1b6b {
  fill: none;
}

.ft6yvtbqk {
  stop-color: var(--svg-color--cac3d3, #CAC3D3);
}

.fxp5v2b6t {
  stop-color: var(--svg-color--453d68, #453D68);
}

.fz7mqmbsd {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.376 9.206c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.371-1.127");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g1k32m_rh {
  stop-color: var(--svg-color--6d6193, #6D6193);
}

.g2-7i-ngi {
  fill: var(--svg-color--41355c, #41355C);
  d: path("M13.419 16.815c-.513 0-1.296-.029-1.77.166l-1.38 2.724c-.09.19.06.41.27.41h1.55c.24 0 .35.29.19.45l-1.78 1.343c-.26.26-.36.65-.23 1l2.912 6.5l1.587-1.116l-1.34-11.477z");
}

.g62f-n79w {
  d: path("m15.603 10.156l-.532 1.838c-.108.378.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.114-.407-.646-.407-.765 0");
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

.gkzmut59n {
  stop-color: var(--svg-color--a89cb3, #A89CB3);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gp34_acsp {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.583 8.006c-.257-.184-.897-.509-1.655-.381");
}

.grvlbeqgj {
  stop-color: var(--svg-color--7c514c, #7C514C);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gyd099b4k {
  d: path("M15.505 21.077a.25.25 0 0 0-.247.212l-1.328 8.668h4.11l-1.318-8.668a.25.25 0 0 0-.247-.212z");
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h--7-vbqp {
  d: path("m21.198 8.522l-.03-.632c-.01-.763-.641-1.393-1.405-1.425h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.059-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.051c1.744 1.138 1.439 3.189.52 4.155");
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.hac9w68gp {
  stop-color: var(--svg-color--534973, #534973);
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

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_25dj3ib {
  stop-color: var(--svg-color--a093a3, #A093A3);
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ikfmx-b8m {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.384 5.258h-2.137a.496.496 0 1 1 .079-.987c.554.088 1.29.211 1.784.334c1.114.276 1.422.819 1.508 1.206a1.55 1.55 0 0 0-1.234-.553");
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iwxeu3bsl {
  stop-color: var(--svg-color--9c6476, #9C6476);
  stop-opacity: 0;
}

.iwz00abqx {
  stop-color: var(--svg-color--5f5289, #5F5289);
}

.j-er45bzw {
  stop-color: var(--svg-color--544a76, #544A76);
}

.j173kr6rw {
  fill: var(--svg-color--533634, #533634);
  d: path("m16.218 5.255l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.098.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.806.42.806.892v1.485z");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jybxgogov {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.knib4pb5u {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kx98i3bkm {
  stop-color: var(--svg-color--837a8d, #837A8D);
  stop-opacity: 0;
}

.kyt4h2bsk {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
  stop-opacity: 0;
}

.l2hsst8bw {
  d: path("M11.124 12.12a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lv0iykbih {
  stop-color: var(--svg-color--56406d, #56406D);
}

.m5bm-ccxd {
  stop-color: var(--svg-color--7b74a6, #7B74A6);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mf716dhmi {
  stop-color: var(--svg-color--544a5f, #544A5F);
}

.mo8lftlng {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.574 7.782a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.002.002a.277.277 0 0 1-.34-.439z");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mu96iuqwe {
  stop-color: var(--svg-color--4b375e, #4B375E);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n55pjdbhv {
  stop-color: var(--svg-color--9c6476, #9C6476);
  stop-opacity: 0.56;
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nfaftvbmv {
  d: path("M10.94 9.007a1.62 1.62 0 0 0-1.391 1.598c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
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

.ohfehdckv {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.603 10.156l-.532 1.838c-.108.378.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.omh3jbc5e {
  stop-color: var(--svg-color--776d9f, #776D9F);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p-sb3ibac {
  stop-color: var(--svg-color--483b55, #483B55);
}

.p0mqqhbpw {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.594 9.206c-.653 0-1.205.45-1.355 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.p1dw5abzj {
  d: path("M20.84 4.228c.514.177.976.536 1.268 1.051A2.37 2.37 0 0 1 22 7.805a1.56 1.56 0 0 0-.27.875v1.188a1.7 1.7 0 0 0-.667-.269l.078-1.606a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.446a2.35 2.35 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.383-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.913-.188c.843 0 1.58.456 1.988 1.132c.308.51.79.88 1.353 1.073");
}

.pc2b66ykc {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.psxy-7s6u {
  d: path("M14.616 10.265c0-.288-.234-.48-.298-.539l-.288.28l.178.36z");
}

.pupoqrb5v {
  d: path("M18.104 9.666c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

.pyudvfb2c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.104 9.666c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

.q_pb1qt5c {
  d: path("M10.9 9.672a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q6i4_kbfn {
  d: path("M13.801 9.477a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q8ootib3t {
  stop-color: var(--svg-color--5f5490, #5F5490);
  stop-opacity: 0;
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r8-nbsf4i {
  stop-color: var(--svg-color--504176, #504176);
  stop-opacity: 0;
}

.r8964-bmu {
  stop-color: var(--svg-color--877f93, #877F93);
  stop-opacity: 0;
}

.rdwqpggao {
  d: path("m16.218 5.255l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.098.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.806.42.806.892v1.485z");
}

.recxkftoe {
  stop-color: var(--svg-color--3e305b, #3E305B);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rop63gbyj {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
  stop-opacity: 0;
}

.rpmno-b9y {
  stop-color: var(--svg-color--41375c, #41375C);
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s3tb_6b2n {
  stop-color: var(--svg-color--3d3247, #3D3247);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sgj6doz-q {
  d: path("M21.035 11.484q.05-.879.095-1.758c.4.054.711.426.711.876c0 .484-.36.878-.806.882");
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.som6k-b6q {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
}

.sx8bpzjax {
  fill: var(--svg-color--463d68, #463D68);
  d: path("m20.905 21.148l-1.19-.828a.23.23 0 0 1 .166-.393h.919a.252.252 0 0 0 .227-.359l-1.076-2.29a8 8 0 0 0-.646-.236h-.595v11.861l2.404-6.872a.85.85 0 0 0-.21-.883");
}

.t3l2nob9f {
  d: path("m16.01 18.294l-1.24 1.204a.15.15 0 0 0-.033.168l.547 1.26c.04.091.13.15.23.15h.952c.1 0 .19-.059.23-.15l.55-1.281a.15.15 0 0 0-.033-.166z");
}

.tl0sjenli {
  fill: var(--svg-color--605890, #605890);
  d: path("m21.22 21.087l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.u61ykmvtc {
  stop-color: var(--svg-color--584982, #584982);
}

.ugh29hhiz {
  stop-color: var(--svg-color--7a6c85, #7A6C85);
}

.uhq0gwwyn {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.584 10.352l-.591 1.838c-.101.378.141.756.484.756h.732c.343 0 .585-.384.484-.756l-.494-1.838c-.106-.408-.504-.408-.615 0");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.uhzi7gbie {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M19.718 7.89a1.85 1.85 0 0 0-.688-.41c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.uihc23imt {
  d: path("M15.985 13.767c-.507 0-.984-.12-1.385-.328c-.137-.07-.285.084-.198.209c.335.507.918.846 1.583.846s1.249-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v4osrdkmw {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.634 13.372a.23.23 0 0 0-.271.047a.21.21 0 0 0-.024.27c.349.528.956.88 1.646.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.352-.32Z");
}

.valti_bse {
  d: path("M14.045 16.856c.02.214.205.691.746 1.055c.214.143 1.213.629 1.193.619c.156-.078.807-.299 1.284-.619c.54-.364.725-.841.746-1.055l-1.985-.953z");
}

.vcj80-e7h {
  fill: var(--svg-color--000, #000);
  d: path("M17.658 10.37c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vlp0azbmu {
  d: path("M13.29 16.057h-.85c-.18.06-.36.13-.53.2l-1.27 2.69c-.09.19.06.41.27.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01v-13.9z");
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w087w3bpc {
  d: path("M11.16 13.636a3.916 3.916 0 0 0 3.886 3.405h1.886a3.916 3.916 0 0 0 3.886-3.405c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wdy63qb5p {
  stop-color: var(--svg-color--c6bbd1, #C6BBD1);
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x3hzs9tmh {
  d: path("M20.846 12.12c.336-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.34 2.02a4.1 4.1 0 0 0 .345-1.18z");
}

.xae-wqulm {
  d: path("M20.907 12.211q.1-1.596.185-3.19a1.61 1.61 0 0 1-.185 3.19");
}

.xc6znrbjq {
  d: path("M23 17.985v11.982h4v-3.5a10.98 10.98 0 0 0-4-8.482");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xswnovbcd {
  cx: 13.532px;
  cy: 9.859px;
  rx: 0.39px;
  ry: 0.197px;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y44mbrbnq {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.612 8.062c.257-.185.897-.51 1.655-.382");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yfhz1ybyq {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
}

.yi0b9jgtv {
  d: path("m21.22 21.087l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.yqlqjsfuk {
  stop-color: var(--svg-color--55477c, #55477C);
}

.yrghyesqm {
  fill: var(--svg-color--000, #000);
  d: path("M14.312 10.37a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
}

.zm9c_pbne {
  stop-color: var(--svg-color--625a91, #625A91);
  stop-opacity: 0;
}

.zmh2_lmnk {
  d: path("M7.032 29.967H8.97V18.003a11 11 0 0 0-3.656 5.842a11 11 0 0 0-.304 2.632l.02 3.49z");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
