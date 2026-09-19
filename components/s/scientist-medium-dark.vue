<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#infafKe)" class="v8t7qqb3k"/><path fill="url(#iqR00lb)" class="e0ic6ye9p"/><path fill="url(#idUU07c)" class="e0ic6ye9p"/><path fill="url(#iCaEb1g)" class="joac4q8ub"/><path fill="url(#iqLjkod)" class="joac4q8ub"/><path fill="url(#inBaqgz)" class="joac4q8ub"/><path fill="url(#iRgUtob)" class="joac4q8ub"/><path fill="url(#igfIcWY)" class="fpr9x3i5x"/><path fill="url(#iZ2Sy2b)" class="fpr9x3i5x"/><path fill="url(#idujfdb)" class="fpr9x3i5x"/><path fill="url(#iBL5orc)" class="fpr9x3i5x"/><g filter="url(#izFCG3d)"><path fill="url(#idadFGd)" class="j0b0ctbat"/></g><g filter="url(#iGPPZse)"><path fill="url(#iTXGYfe)" class="lrzv_7qmv"/></g><g filter="url(#iEnp7jC)"><path fill="url(#itvOike)" class="idxtw4bed"/></g><path fill="url(#iFYU9re)" class="g7v1ug-qx"/><path fill="url(#ic0n5iY)" class="g7v1ug-qx"/><path fill="url(#i8vxTde)" class="g7v1ug-qx"/><path fill="url(#iYqmoHb)" class="g7v1ug-qx"/><path fill="url(#iKKRX8d)" class="g7v1ug-qx"/><path fill="url(#iRN8Uyc)" class="aimjkru3c"/><path fill="url(#iVX15je)" class="aimjkru3c"/><path fill="url(#iITWRgd)" class="aimjkru3c"/><path fill="url(#iZzQKlc)" class="aimjkru3c"/><path fill="url(#ipIwrgd)" class="lrzv_7qmv"/><path fill="url(#iapouwe)" class="ecseti46o"/><path fill="url(#igzWKyb)" class="ecseti46o"/><path fill="url(#infafKe)" class="v8t7qqb3k"/><path fill="url(#iuRSGxb)" class="f17fs0b3r"/><path fill="url(#ihQib1c)" class="f17fs0b3r"/><path fill="url(#id1HOJd)" class="pl_8-ibln"/><path fill="url(#iohQ2Yc)" class="pl_8-ibln"/><path fill="url(#iIAQNVt)" class="fjwmopz8c"/><path fill="url(#icUXfec)" class="fjwmopz8c"/><path fill="url(#iQTgDwa)" class="fjwmopz8c"/><g filter="url(#ikElYrd)"><rect class="ds3fxcllo"/><rect fill="url(#i0bnr8c)" class="t2plsrbxa"/><rect fill="url(#iZzNWte)" class="t2plsrbxa"/><rect fill="url(#ifyID8d)" class="t2plsrbxa"/></g><path fill="url(#i60xnLe)" class="pn0j59qyb"/><path fill="url(#iF7EoLb)" class="pn0j59qyb"/><path fill="url(#i38bXAc)" class="pn0j59qyb"/><path fill="url(#i5dokic)" class="pn0j59qyb"/><path fill="url(#ifyIudd)" class="e603gvblx"/><path fill="url(#iwlC1kj)" class="n4ufdcvis"/><g filter="url(#iaX5Twb)"><path fill="url(#iF6qiQd)" class="rfhufdblf"/><path fill="url(#ic5Eqgd)" class="rfhufdblf"/><path fill="url(#i7GT1Wb)" class="rfhufdblf"/><path fill="url(#in76fZb)" class="rfhufdblf"/><path fill="url(#icjjNde)" class="rfhufdblf"/></g><g filter="url(#inBVEoc)"><path stroke="url(#i0kuKpb)" class="oj8_9hbse"/></g><g filter="url(#ikpL7De)"><path stroke="url(#iejUzme)" class="bv91x78so"/></g><g filter="url(#iKrvwOd)"><path stroke="url(#iAGPV4c)" class="c7dra70nl"/></g><path fill="url(#ifgXGlQ)" class="ilx2_dmnm"/><path fill="url(#iULbyEc)" class="h77ktzbrw"/><g filter="url(#i5bbZHg)"><path fill="url(#iWchHyd)" class="mcy82v73v"/><path fill="url(#iFxt1Mc)" class="mcy82v73v"/></g><path fill="url(#i4xXQYb)" class="mcy82v73v"/><path fill="url(#iaZJZOe)" class="mcy82v73v"/><path fill="url(#iqIkXSd)" class="mcy82v73v"/><path fill="url(#i5tpMwb)" class="mcy82v73v"/><path fill="url(#iaZ3QxU)" class="mcy82v73v"/><path fill="url(#i1xRVGk)" class="mcy82v73v"/><path fill="url(#i7DNKGd)" class="mcy82v73v"/><g filter="url(#iAOM3Be)"><path class="dp0ufylpx"/></g><g filter="url(#iPPmTKb)"><path class="ozpse8b_b"/><path fill="url(#i3Zomud)" class="cev6tjbqa"/><path fill="url(#izGlcNb)" class="cev6tjbqa"/><path fill="url(#iTlCNDa)" class="cev6tjbqa"/><path fill="url(#iNgSXAe)" class="cev6tjbqa"/><path fill="url(#ilKvDEO)" class="cev6tjbqa"/></g><path fill="url(#isWSx4c)" class="cev6tjbqa"/><path fill="url(#iyhqVMf)" class="cev6tjbqa"/><g filter="url(#iobxRce)"><path stroke="url(#i0Wqkfd)" class="mltk0ybzo"/></g><path fill="url(#imHvnid)" class="agnbwqbjz"/><g filter="url(#icvskwb)"><path fill="url(#iYX6C4E)" class="l1-yf0bcl"/><path fill="url(#ioUtkPd)" class="l1-yf0bcl"/><path fill="url(#iqm8A6d)" class="l1-yf0bcl"/><path fill="url(#ig9z2Pc)" class="l1-yf0bcl"/><path fill="url(#iVwXj2b)" class="l1-yf0bcl"/></g><g filter="url(#itTgd6z)"><path class="brxfjy2mb"/></g><g filter="url(#iuP92Dd)"><path class="ka83facpt"/></g><g filter="url(#i6v6Eve)"><path class="nur--6opj"/><path fill="url(#ili3Ngb)" class="dz_vpd3gx"/><path fill="url(#itdu3sc)" class="dz_vpd3gx"/></g><g filter="url(#icSCFEw)"><path class="vf0j42l_x"/><path fill="url(#i7fYYyc)" class="v738tzjuw"/><path fill="url(#iMphvMF)" class="v738tzjuw"/></g><path class="qkh2hv07m"/><path fill="url(#idefiMc)" class="xjjuhqpsr"/><path class="omvy-9vyz"/><g filter="url(#ibphBib)"><path class="ue-wtrbtm"/><path fill="url(#iweDEIb)" class="bek01tbnw"/></g><g filter="url(#iBzJKBb)"><path fill="url(#iXSSNoo)" class="dn9a10x6b"/></g><path class="t_gd5_bru"/><path fill="url(#ijXE5Sc)" class="n647v0b3f"/><path class="usjdiybcp"/><g filter="url(#iwbT7zb)"><path fill="url(#itgeQ7c)" class="i2b55vb_g"/></g><g filter="url(#inRYINe)"><ellipse transform="rotate(-27.914 12.972 10.111)" class="tgk30abvz"/><ellipse fill="url(#ix3In2b)" transform="rotate(-27.914 12.972 10.111)" class="l276g_hlf"/></g><path fill="url(#i45RhQd)" class="t-jmrltmm"/><path fill="url(#ip3mBxb)" class="t-jmrltmm"/><path fill="url(#iQVjtBx)" class="t-jmrltmm"/><path fill="url(#iTFI0Rr)" class="t-jmrltmm"/><path fill="url(#iVlJtyd)" class="b9xih1b2n"/><path fill="url(#iLT0gTd)" class="b9xih1b2n"/><g filter="url(#iGVOuud)"><path fill="url(#idI2hEe)" class="z0a0cvbpi"/></g><g filter="url(#i9bTcJc)"><path fill="url(#i5k9HKb)" class="t5g_fcvfk"/></g><g filter="url(#ixfxBNb)"><path class="xc0_t5b5a"/></g><g filter="url(#ie5Gvzc)"><path class="a7s_b96uw"/></g><g filter="url(#icDOvTc)"><path class="sp4mxqbag"/></g><g filter="url(#iOaGsXY)" class="z4n2hhy8u"><path fill="url(#iS6ZXZN)" class="zu47lac-j"/></g><g filter="url(#iB3Zcmd)"><path clip-rule="evenodd" class="ytud2rban"/></g><defs><radialGradient id="iqR00lb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.446 18.318)" gradientUnits="userSpaceOnUse"><stop class="e2ig5yb1x"/><stop offset="1" class="rsfdnufmx"/></radialGradient><radialGradient id="idUU07c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.318)" gradientUnits="userSpaceOnUse"><stop class="eol9ugodk"/><stop offset="1" class="e080jybbb"/></radialGradient><radialGradient id="iCaEb1g" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.493 14.562)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="hy6proxed"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="iRgUtob" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.411)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="igfIcWY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.286)" gradientUnits="userSpaceOnUse"><stop class="lj5m7ucmi"/><stop offset="1" class="d3a6h5dbs"/></radialGradient><radialGradient id="iZ2Sy2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.536)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iTXGYfe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.911)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="iFYU9re" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.693)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="ic0n5iY" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.309 -.254)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="i8vxTde" cx="0" cy="0" r="1" gradientTransform="matrix(-.73439 2.1875 -3.93465 -1.32095 19.943 15.99)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="xpzhm0iru"/><stop offset="1" class="jqs3afbfy"/></radialGradient><radialGradient id="iRN8Uyc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.114)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iITWRgd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.97)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="ipIwrgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1 2.84375 -3.2172 -1.13131 12.552 16.068)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="fbqio7b7r"/><stop offset="1" class="txsyviqti"/></radialGradient><radialGradient id="iapouwe" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.88)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="iuRSGxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.44587 -2.36879 0 15.426 17.173)" gradientUnits="userSpaceOnUse"><stop class="id89gdi-x"/><stop offset="1" class="eaxvbacai"/></radialGradient><radialGradient id="ihQib1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.45312 -1.20313 0 13.666 16.767)" gradientUnits="userSpaceOnUse"><stop class="sa-gczbrr"/><stop offset="1" class="jncd64beg"/></radialGradient><radialGradient id="id1HOJd" cx="0" cy="0" r="1" gradientTransform="rotate(140.55 9.491 16.736)scale(2.18272 2.14492)" gradientUnits="userSpaceOnUse"><stop offset=".354" class="b5vuh20co"/><stop offset="1" class="hrswh-pmg"/></radialGradient><radialGradient id="iohQ2Yc" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .32018 .41998 27.206 23.467)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wyf8ygbxi"/><stop offset="1" class="i6hs9gb9s"/></radialGradient><radialGradient id="iQTgDwa" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.38)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="i0bnr8c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.068)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iZzNWte" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.006 18.92)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="ifyID8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.279)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="i5dokic" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.224)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="ic5Eqgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.294)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i7GT1Wb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.589)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="in76fZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.839)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="icjjNde" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.19)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ifgXGlQ" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.61 20.401)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iULbyEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 9.37 12.29)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iWchHyd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.233 10.858)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iFxt1Mc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.269 7.973)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iaZJZOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 10 -13.4886 0 15.473 7.33)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="a8oq1yb9o"/><stop offset="1" class="lwggnabgn"/></radialGradient><radialGradient id="iqIkXSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 17.873 9.545)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="i5tpMwb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.376 -1.79)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iaZ3QxU" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 18.858 11.846)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="i1xRVGk" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 8.634 8.125)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="i7DNKGd" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 6.87 13.516)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="izGlcNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 15.892 12.304)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iNgSXAe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.008 11.735)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iyhqVMf" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.637 8.899)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="imHvnid" cx="0" cy="0" r="1" gradientTransform="matrix(2.18199 -1.07272 4.31584 8.77868 14.935 14.48)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ioUtkPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.196 7.966)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iqm8A6d" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 14.996 -5.976)scale(2.51513 4.45632)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="ig9z2Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 19.532 3)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iVwXj2b" cx="0" cy="0" r="1" gradientTransform="matrix(.67168 1.19822 -2.77451 1.5553 14.52 1.407)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="ili3Ngb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 15.68 3.666)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="itdu3sc" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 11.9 -5.263)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="i7fYYyc" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90406 18.06 7.48)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iMphvMF" cx="0" cy="0" r="1" gradientTransform="matrix(3.24822 .37966 -.15896 1.35997 17.173 6.004)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="idefiMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 17.608 10.207)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iweDEIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.38 10.291)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijXE5Sc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.244 10.207)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ix3In2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 12.957 10.425)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ip3mBxb" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.043 9.955)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iQVjtBx" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.404 10.5)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iTFI0Rr" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.518 10.672)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iLT0gTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 10.51 10.597)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="idI2hEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 10.51 10.599)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><linearGradient id="infafKe" x1="8.23" x2="22.659" y1="15.298" y2="15.298" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iqLjkod" x1="11.239" x2="11.239" y1="30.411" y2="29.099" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="inBaqgz" x1="15.177" x2="14.208" y1="29.099" y2="29.099" gradientUnits="userSpaceOnUse"><stop offset=".129" class="dx1e6jb0z"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="idujfdb" x1="19.74" x2="19.74" y1="30.411" y2="29.099" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iBL5orc" x1="15.802" x2="16.505" y1="27.974" y2="27.974" gradientUnits="userSpaceOnUse"><stop class="bx23o8bkx"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="idadFGd" x1="10.677" x2="12.896" y1="17.943" y2="24.63" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="itvOike" x1="20.45" x2="18.099" y1="18.972" y2="23.673" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="iYqmoHb" x1="18.958" x2="17.552" y1="24.099" y2="22.599" gradientUnits="userSpaceOnUse"><stop class="p2mir8bpk"/><stop offset="1" class="ifg4wbcuq"/></linearGradient><linearGradient id="iKKRX8d" x1="17.146" x2="17.974" y1="18.88" y2="19.224" gradientUnits="userSpaceOnUse"><stop offset=".081" class="ea_0ewlyw"/><stop offset="1" class="z_a2ribdx"/></linearGradient><linearGradient id="iVX15je" x1="6.567" x2="6.567" y1="30.354" y2="29.22" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iZzQKlc" x1="8.38" x2="7.935" y1="29.388" y2="29.385" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="igzWKyb" x1="22.753" x2="23.162" y1="27.661" y2="27.646" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="iIAQNVt" x1="23.825" x2="26.529" y1="20.849" y2="20.849" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="icUXfec" x1="26.529" x2="26.18" y1="20.833" y2="20.833" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="i60xnLe" x1="26.529" x2="25.177" y1="23.161" y2="23.161" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iF7EoLb" x1="26.529" x2="26.129" y1="23.31" y2="23.31" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="i38bXAc" x1="23.696" x2="24.227" y1="23.31" y2="23.31" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="ifyIudd" x1="24.782" x2="23.892" y1="21.802" y2="21.802" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iwlC1kj" x1="24.782" x2="23.892" y1="23.583" y2="23.583" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iF6qiQd" x1="27.165" x2="23.137" y1="28.052" y2="28.052" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="i0kuKpb" x1="23.754" x2="25.463" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iejUzme" x1="23.676" x2="25.385" y1="27.374" y2="27.374" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iAGPV4c" x1="23.754" x2="25.463" y1="28.679" y2="28.679" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i4xXQYb" x1="20.583" x2="18.054" y1="12.543" y2="12.543" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="i3Zomud" x1="16.264" x2="15.426" y1="11.618" y2="11.653" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iTlCNDa" x1="15.426" x2="15.426" y1="12.758" y2="12.293" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="ilKvDEO" x1="15.426" x2="15.426" y1="10.053" y2="10.599" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="isWSx4c" x1="15.841" x2="15.841" y1="12.896" y2="12.703" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="i0Wqkfd" x1="14.224" x2="14.542" y1="14.243" y2="13.408" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iYX6C4E" x1="22.278" x2="10.665" y1="5.195" y2="5.195" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iXSSNoo" x1="18.386" x2="18.072" y1="10.261" y2="10.454" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itgeQ7c" x1="13.988" x2="13.674" y1="10.261" y2="10.454" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i45RhQd" x1="21.862" x2="20.655" y1="10.022" y2="12.199" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iVlJtyd" x1="9.576" x2="11.034" y1="10.726" y2="10.599" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="i5k9HKb" x1="20.842" x2="20.842" y1="9.641" y2="11.544" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="iS6ZXZN" x1="10.917" x2="22.177" y1="9.729" y2="9.729" gradientUnits="userSpaceOnUse"><stop offset=".257" class="rpclz5w3y"/><stop offset="1" class="mu-ox6b5f"/></linearGradient><filter id="izFCG3d" width="7.023" height="11.703" x="8.591" y="15.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".375"/></filter><filter id="iGPPZse" width="5.673" height="10.453" x="9.475" y="15.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2169"/></filter><filter id="iEnp7jC" width="6.388" height="10.529" x="15.499" y="16.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".375"/></filter><filter id="ikElYrd" width="4.008" height=".781" x="23.173" y="18.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2169"/></filter><filter id="iaX5Twb" width="4.468" height="5.556" x="23.137" y="24.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2169"/></filter><filter id="inBVEoc" width="2.097" height=".3" x="23.604" y="25.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".05"/></filter><filter id="ikpL7De" width="2.097" height=".3" x="23.526" y="27.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".05"/></filter><filter id="iKrvwOd" width="2.097" height=".3" x="23.604" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".05"/></filter><filter id="i5bbZHg" width="11.22" height="12.542" x="10.362" y="4.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2169"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2169" result="effect2_innerShadow_4002_2169"/></filter><filter id="iAOM3Be" width="3.747" height="4.9" x="13.41" y="9.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".5"/></filter><filter id="iPPmTKb" width="2.277" height="3.3" x="14.287" y="9.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".1"/></filter><filter id="iobxRce" width="3.718" height="1.573" x="13.566" y="13.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".05"/></filter><filter id="icvskwb" width="12.873" height="8.357" x="8.989" y="1.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2169"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2169" result="effect2_innerShadow_4002_2169"/></filter><filter id="itTgd6z" width="2.339" height="1.19" x="17.015" y="7.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2169"/></filter><filter id="iuP92Dd" width="2.339" height="1.176" x="11.758" y="7.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2169"/></filter><filter id="i6v6Eve" width="6.584" height="5.992" x="9.345" y="2.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2169"/><feGaussianBlur result="effect2_foregroundBlur_4002_2169" stdDeviation=".125"/></filter><filter id="icSCFEw" width="6.319" height="5.711" x="15.267" y="3.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".125"/></filter><filter id="ibphBib" width=".787" height=".696" x="16.874" y="9.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".05"/></filter><filter id="iBzJKBb" width=".891" height=".913" x="17.713" y="9.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".1"/></filter><filter id="iwbT7zb" width=".986" height="1.04" x="13.271" y="9.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".1"/></filter><filter id="inRYINe" width=".913" height=".705" x="12.516" y="9.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".05"/></filter><filter id="iGVOuud" width="1.329" height="2.379" x="9.345" y="9.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".125"/></filter><filter id="i9bTcJc" width="1.947" height="2.903" x="19.869" y="9.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".25"/></filter><filter id="ixfxBNb" width="2.405" height="1.16" x="11.678" y="7.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".125"/></filter><filter id="ie5Gvzc" width="2.405" height="1.16" x="16.956" y="7.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".125"/></filter><filter id="icDOvTc" width="5.266" height="3.006" x="16.305" y="3.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2169" stdDeviation=".375"/></filter><filter id="iOaGsXY" width="10.729" height="5.624" x="10.061" y="6.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.239216 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2169"/></filter><filter id="iB3Zcmd" width="11.479" height="6.324" x="9.611" y="5.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.494118 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2169"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.752941 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2169" result="effect2_innerShadow_4002_2169"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:scientist-medium-dark" /></template>
<style>
.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.a7s_b96uw {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.987 8.147c-.257-.184-.898-.509-1.656-.381");
}

.a8oq1yb9o {
  stop-color: var(--svg-color--7e495d, #7E495D);
  stop-opacity: 0;
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.agnbwqbjz {
  d: path("M15.426 13.754c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.085-.198.209c.335.508.919.846 1.584.846c.664 0 1.248-.338 1.583-.846c.086-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.aimjkru3c {
  d: path("M8.226 29.99V18.2c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b5vuh20co {
  stop-color: var(--svg-color--8b655b, #8B655B);
}

.b9xih1b2n {
  d: path("M10.381 8.994a1.62 1.62 0 0 0-1.392 1.598c0 .86.673 1.561 1.521 1.607a78 78 0 0 1-.129-3.205");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bek01tbnw {
  d: path("M17.544 9.919c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.359c.15-.113.325-.135.388-.05");
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.brxfjy2mb {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M19.158 8.022a1.85 1.85 0 0 0-.687-.411c-.304-.096-.685-.122-1.213-.057a.277.277 0 0 0 .068.55c.481-.058.776-.028.978.036c.199.062.333.163.49.3a.277.277 0 1 0 .364-.418");
}

.bv91x78so {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.296h1.797");
}

.bx23o8bkx {
  stop-color: var(--svg-color--b28598, #B28598);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.c7dra70nl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.6h1.797");
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cev6tjbqa {
  d: path("m15.043 10.229l-.531 1.838c-.109.378.152.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.d3a6h5dbs {
  stop-color: var(--svg-color--ccb8e5, #CCB8E5);
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dn9a10x6b {
  d: path("M18.405 10.505a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.dp0ufylpx {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.024 10.425l-.59 1.838c-.101.378.14.756.484.756h.732c.343 0 .585-.383.484-.756l-.495-1.838c-.106-.407-.504-.407-.615 0");
}

.ds3fxcllo {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.677px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dx1e6jb0z {
  stop-color: var(--svg-color--be9bb3, #BE9BB3);
}

.dz_vpd3gx {
  d: path("m15.658 5.242l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.804-.767-1.688c0-1.071.781-1.613 1.28-1.959c.14-.097.26-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e080jybbb {
  stop-color: var(--svg-color--ed5030, #ED5030);
  stop-opacity: 0;
}

.e0ic6ye9p {
  d: path("M15.466 15.35c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.015c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e2ig5yb1x {
  stop-color: var(--svg-color--e07221, #E07221);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e603gvblx {
  d: path("M23.825 22.036v-.468h.805a.234.234 0 0 1 0 .468z");
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.ea_0ewlyw {
  stop-color: var(--svg-color--c79f97, #C79F97);
}

.eaxvbacai {
  stop-color: var(--svg-color--613933, #613933);
}

.ecseti46o {
  d: path("M22.753 29.99V18.2c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.eol9ugodk {
  stop-color: var(--svg-color--ed5030, #ED5030);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f17fs0b3r {
  d: path("M15.426 18.62a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fbqio7b7r {
  stop-color: var(--svg-color--a27d98, #A27D98);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fjwmopz8c {
  d: path("M23.825 19.458h2.703v5.938h-2.703z");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.fpr9x3i5x {
  d: path("M19.865 16.282a10.5 10.5 0 0 1 2.878 1.917v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98V23.47z");
}

.ft5dv1b6b {
  fill: none;
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g7v1ug-qx {
  d: path("m21.37 17.113l.132 1.733a.6.6 0 0 1-.494.637l-.48.084a.15.15 0 0 0-.085.249l.626.69a.5.5 0 0 1-.014.687l-4.732 4.808a.2.2 0 0 1-.343-.14v-3.38a2 2 0 0 1 .175-.82l2.606-5.803c.929.298 1.807.722 2.61 1.255");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h77ktzbrw {
  d: path("M10.564 12.108a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hrswh-pmg {
  stop-color: var(--svg-color--673a32, #673A32);
}

.hy6proxed {
  stop-color: var(--svg-color--e1d2f9, #E1D2F9);
}

.i2b55vb_g {
  d: path("M14.057 10.518c0-.289-.235-.481-.298-.54l-.288.28l.177.361z");
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6hs9gb9s {
  stop-color: var(--svg-color--997c73, #997C73);
  stop-opacity: 0;
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.id89gdi-x {
  stop-color: var(--svg-color--703d4a, #703D4A);
}

.idxtw4bed {
  d: path("m21.02 18.143l.115 1.534a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.076.22l.554.611a.44.44 0 0 1-.012.607l-4.188 4.255a.177.177 0 0 1-.303-.124v-2.992c0-.25.053-.496.155-.724l2.306-5.136c.822.264 1.599.64 2.31 1.111");
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.ilx2_dmnm {
  d: path("M20.287 12.108c.335-.011.65-.125.905-.309v.931c0 .893-.533 1.689-1.341 2.02q.256-.547.346-1.18z");
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.j0b0ctbat {
  d: path("m9.474 17.722l-.131 1.733a.6.6 0 0 0 .494.636l.479.085a.15.15 0 0 1 .085.248l-.626.691a.5.5 0 0 0 .014.687l4.733 4.807a.2.2 0 0 0 .342-.14v-3.38a2 2 0 0 0-.175-.82l-2.606-5.803a10.6 10.6 0 0 0-2.61 1.256");
}

.jncd64beg {
  stop-color: var(--svg-color--6f4440, #6F4440);
  stop-opacity: 0;
}

.joac4q8ub {
  d: path("M11.114 16.282a10.5 10.5 0 0 0-2.878 1.917v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453V23.47z");
}

.jqs3afbfy {
  stop-color: var(--svg-color--ece2e9, #ECE2E9);
  stop-opacity: 0;
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.ka83facpt {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M12.015 7.913a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.068.552a2.22 2.22 0 0 0-1.386.284a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l1-yf0bcl {
  d: path("M20.28 4.215a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.875v1.188a1.75 1.75 0 0 0-.668-.268l.079-1.607a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379l.031 1.537c-.254.038-.52.123-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.445a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.187.912-.187c.843 0 1.58.455 1.989 1.131c.308.51.79.88 1.352 1.073");
}

.l276g_hlf {
  cx: 12.972px;
  cy: 10.111px;
  rx: 0.39px;
  ry: 0.197px;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj5m7ucmi {
  stop-color: var(--svg-color--bea0dc, #BEA0DC);
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lrzv_7qmv {
  d: path("m9.608 17.113l-.13 1.733a.6.6 0 0 0 .493.637l.48.084a.15.15 0 0 1 .084.249l-.626.69a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.298-1.807.722-2.61 1.255");
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lwggnabgn {
  stop-color: var(--svg-color--7f3d72, #7F3D72);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcy82v73v {
  d: path("M10.6 13.623a3.916 3.916 0 0 0 3.886 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.513-3.342 3.38c0 1.86.117 3.69.239 5.556");
}

.mltk0ybzo {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.075 13.36a.23.23 0 0 0-.272.046a.21.21 0 0 0-.023.27c.349.529.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.002c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.351-.32Z");
}

.mu-ox6b5f {
  stop-color: var(--svg-color--97c1a5, #97C1A5);
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n4ufdcvis {
  d: path("M23.825 23.818v-.47h.805a.234.234 0 1 1 0 .47z");
}

.n647v0b3f {
  d: path("M13.242 9.73a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nur--6opj {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m15.658 5.242l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.804-.767-1.688c0-1.071.781-1.613 1.28-1.959c.14-.097.26-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oj8_9hbse {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 25.992h1.797");
}

.omvy-9vyz {
  fill: var(--svg-color--000, #000);
  d: path("M17.099 10.623a.51.51 0 0 1 .51-.512a.51.51 0 0 1 .455.747h-.904a.46.46 0 0 1-.061-.236");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.ozpse8b_b {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.043 10.229l-.531 1.838c-.109.378.152.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p2mir8bpk {
  stop-color: var(--svg-color--d2b4ed, #D2B4ED);
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pl_8-ibln {
  d: path("M26.434 22.96c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.pn0j59qyb {
  d: path("M26.529 21.224v4.172h-2.704v-4.172z");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.qkh2hv07m {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.817 9.458c.653 0 1.204.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rfhufdblf {
  d: path("M23.137 25.315c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.388a.735.735 0 0 1 0-1.315a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rpclz5w3y {
  stop-color: var(--svg-color--679078, #679078);
}

.rsfdnufmx {
  stop-color: var(--svg-color--b64118, #B64118);
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sa-gczbrr {
  stop-color: var(--svg-color--6f4440, #6F4440);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sp4mxqbag {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M19.619 5.198h-2.081a.483.483 0 1 1 .077-.962c.54.087 1.257.206 1.737.326c1.085.269 1.385.797 1.469 1.174a1.51 1.51 0 0 0-1.202-.538");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_gd5_bru {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.035 9.458c-.653 0-1.205.45-1.355 1.06a.274.274 0 0 0 .268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t-jmrltmm {
  d: path("M20.348 12.199q.1-1.596.184-3.192a1.61 1.61 0 0 1-.184 3.192");
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.t2plsrbxa {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.677px;
  rx: 0.391px;
}

.t5g_fcvfk {
  d: path("M20.369 11.544q.058-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.tgk30abvz {
  cx: 12.972px;
  cy: 10.111px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.txsyviqti {
  stop-color: var(--svg-color--aa9fa6, #AA9FA6);
  stop-opacity: 0;
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.ue-wtrbtm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.544 9.919c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.359c.15-.113.325-.135.388-.05");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.usjdiybcp {
  fill: var(--svg-color--000, #000);
  d: path("M13.753 10.623a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .06-.236");
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.v738tzjuw {
  d: path("m20.638 8.509l-.029-.631c-.01-.764-.642-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.671-1.706 1.65-1.488c.94.209 2.004.559 2.815 1.088c1.745 1.137 1.532 3.12.613 4.085");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.v8t7qqb3k {
  d: path("M15.466 15.3h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.vf0j42l_x {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m20.638 8.509l-.029-.631c-.01-.764-.642-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.671-1.706 1.65-1.488c.94.209 2.004.559 2.815 1.088c1.745 1.137 1.532 3.12.613 4.085");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wyf8ygbxi {
  stop-color: var(--svg-color--997c73, #997C73);
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xc0_t5b5a {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.053 8.193c.256-.184.897-.509 1.655-.381");
}

.xjjuhqpsr {
  d: path("M17.61 9.73a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xpzhm0iru {
  stop-color: var(--svg-color--cec5ca, #CEC5CA);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.ytud2rban {
  fill: var(--svg-color--9f9ba5, #9F9BA5);
  fill-rule: evenodd;
  d: path("M9.761 9.17c.011-1.675 1.389-3.004 3.047-3.004h5.275a3.01 3.01 0 0 1 3.007 3.04c-.022 1.568-1.339 2.918-2.907 2.974h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.066-.09-.076-.112-.076s-.067.01-.112.075a3.08 3.08 0 0 1-2.549 1.353a3.02 3.02 0 0 1-3.017-3.017zm.6.004a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.436 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.608.34h.001a2.46 2.46 0 0 0 2.114 1.078c1.248-.044 2.31-1.133 2.328-2.382a2.41 2.41 0 0 0-2.407-2.432h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.z_a2ribdx {
  stop-color: var(--svg-color--e7d3df, #E7D3DF);
  stop-opacity: 0;
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z0a0cvbpi {
  d: path("M10.34 9.66a.956.956 0 0 0 .084 1.879a78 78 0 0 1-.084-1.88");
}

.z4n2hhy8u {
  opacity: var(--svg-opacity--0-6, 0.6);
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zu47lac-j {
  d: path("M18.083 6.466h-5.275c-1.497 0-2.737 1.2-2.747 2.707a2.72 2.72 0 0 0 2.717 2.717c.942 0 1.814-.486 2.3-1.22c.189-.278.533-.278.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.27 2.618-2.678a2.71 2.71 0 0 0-2.707-2.736");
}

</style>
