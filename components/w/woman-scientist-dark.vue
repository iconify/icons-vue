<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ilK2z7c)"><path fill="url(#ipPWqCe)" clip-rule="evenodd" class="k2-oqvygh"/><path fill="url(#iyRYAqe)" clip-rule="evenodd" class="k2-oqvygh"/><path fill="url(#iLkKQWc)" clip-rule="evenodd" class="k2-oqvygh"/><path fill="url(#iZzY7ee)" clip-rule="evenodd" class="k2-oqvygh"/><path fill="url(#ipE5nIb)" clip-rule="evenodd" class="k2-oqvygh"/><path fill="url(#iSCwh1d)" clip-rule="evenodd" class="k2-oqvygh"/><path fill="url(#iI2OUrd)" clip-rule="evenodd" class="k2-oqvygh"/><path fill="url(#iftab7Q)" clip-rule="evenodd" class="k2-oqvygh"/><path fill="url(#iA4TjPh)" clip-rule="evenodd" class="k2-oqvygh"/><path fill="url(#ir6qgHp)" clip-rule="evenodd" class="k2-oqvygh"/><path fill="url(#iO9Hivc)" clip-rule="evenodd" class="k2-oqvygh"/><path fill="url(#iEJIJdb)" clip-rule="evenodd" class="k2-oqvygh"/></g><path fill="url(#iU8OreY)" class="wmoe38bcw"/><path fill="url(#i80UNyF)" class="e35whsbac"/><path fill="url(#iKvL0ad)" class="e35whsbac"/><path fill="url(#iqQd05C)" class="u0i2txb_m"/><path fill="url(#iEbjg4b)" class="u0i2txb_m"/><path fill="url(#iYvBV0p)" class="u0i2txb_m"/><path fill="url(#iR3AfUd)" class="u0i2txb_m"/><path fill="url(#isYkfRc)" class="nk4g_bcbl"/><path fill="url(#imcN5iR)" class="nk4g_bcbl"/><path fill="url(#iZCVgIb)" class="nk4g_bcbl"/><path fill="url(#iVGz0wc)" class="nk4g_bcbl"/><g filter="url(#ieTz4Oc)"><path fill="url(#iDT9Tpf)" class="p-lk43bls"/></g><g filter="url(#iI1fvye)"><path fill="url(#i7g3o9c)" class="j7vqxwjtw"/></g><g filter="url(#i9XDdne)"><path fill="url(#i9E0HSw)" class="xyt5u_bsm"/></g><path fill="url(#ic9D06l)" class="uvcfm_3sz"/><path fill="url(#ihp65kb)" class="uvcfm_3sz"/><path fill="url(#iRikR1M)" class="uvcfm_3sz"/><path fill="url(#i6Ilh4c)" class="uvcfm_3sz"/><path fill="url(#iaeGMXb)" class="uvcfm_3sz"/><path fill="url(#iuSgGHb)" class="mpfi5wb3o"/><path fill="url(#itx7vie)" class="mpfi5wb3o"/><path fill="url(#iTZPFxd)" class="mpfi5wb3o"/><path fill="url(#iuXZp7i)" class="mpfi5wb3o"/><path fill="url(#iv1Yf1c)" class="j7vqxwjtw"/><path fill="url(#iIbqNte)" class="hv1xy1b4f"/><path fill="url(#imWOU0c)" class="hv1xy1b4f"/><path fill="url(#iU8OreY)" class="wmoe38bcw"/><g filter="url(#iVHD6Yd)"><path fill="url(#i5yngde)" class="mf98ki1lw"/><path fill="url(#iikXNfa)" class="mf98ki1lw"/></g><path fill="url(#i9MSO2S)" class="b5yhvnbfs"/><path fill="url(#ie6ITEb)" class="b5yhvnbfs"/><path fill="url(#ijxvAte)" class="h5ekbbbij"/><path fill="url(#iv2MtJd)" class="h5ekbbbij"/><path fill="url(#iGtTgfc)" class="h5ekbbbij"/><g filter="url(#i73ZEOe)"><rect class="m36bl-xzp"/><rect fill="url(#iE91Ewe)" class="g0v5xv26o"/><rect fill="url(#iIBhgFe)" class="g0v5xv26o"/><rect fill="url(#i0Wknwc)" class="g0v5xv26o"/></g><path fill="url(#iPwqvvc)" class="elug4ib2p"/><path fill="url(#iTzgFke)" class="elug4ib2p"/><path fill="url(#ixWPIkI)" class="elug4ib2p"/><path fill="url(#ikQcqUd)" class="elug4ib2p"/><path fill="url(#i38IrPb)" class="o2gqjcckt"/><path fill="url(#iX4WJlb)" class="wkncf3j-v"/><g filter="url(#ihvaC5d)"><path fill="url(#iYvzLpb)" class="m3t7pactc"/><path fill="url(#iJBuOLb)" class="m3t7pactc"/><path fill="url(#igcdawe)" class="m3t7pactc"/><path fill="url(#iYRB7wb)" class="m3t7pactc"/><path fill="url(#id7iiRc)" class="m3t7pactc"/></g><g filter="url(#iELQbOe)"><path stroke="url(#iRvIhMe)" class="ih2uysbls"/></g><g filter="url(#i8Fwkio)"><path stroke="url(#iL62ZWb)" class="g4qo_rdhw"/></g><g filter="url(#ip7JoVc)"><path stroke="url(#iGgcEdQ)" class="bcxlwr27n"/></g><path fill="url(#iEYiXBd)" class="sprcjgfur"/><path fill="url(#iA7lwUd)" class="z3itxhbjk"/><g filter="url(#iBaxB1b)"><path fill="url(#iiqBOJL)" class="k-c2wqbxs"/></g><g filter="url(#ihXrfuQ)"><path fill="url(#iJcAO9c)" class="z4m0-bobm"/><path fill="url(#iQi09db)" class="z4m0-bobm"/></g><g filter="url(#iFJctJc)"><path class="t1_gw3q7o"/><path fill="url(#iwcLqrc)" class="d9tr4ab2j"/></g><g filter="url(#im7QNeb)"><path class="zzwkb2klc"/><path fill="url(#imULfDe)" class="v-7zmcr6h"/></g><g filter="url(#iy6t5Lb)"><path fill="url(#iXKGP9x)" class="bpjxo1muy"/><path fill="url(#ig0QGLc)" class="bpjxo1muy"/><path fill="url(#ir8nHmk)" class="bpjxo1muy"/><path fill="url(#iAgS3hb)" class="bpjxo1muy"/><path fill="url(#i9JXABb)" class="bpjxo1muy"/><path fill="url(#iVbpvpb)" class="bpjxo1muy"/><path fill="url(#iDmpBbd)" class="bpjxo1muy"/><path fill="url(#iznzylM)" class="bpjxo1muy"/></g><path fill="url(#iAP4N4c)" class="bpjxo1muy"/><path fill="url(#ijy0pKc)" class="bpjxo1muy"/><g filter="url(#iXKcvKd)"><path class="cebxepb-r"/></g><g filter="url(#iOLzZme)"><path class="ljwmioblb"/><path fill="url(#iVXgrxc)" class="i0scxb85m"/><path fill="url(#i9kHT7d)" class="i0scxb85m"/><path fill="url(#iVctsEc)" class="i0scxb85m"/><path fill="url(#iqHTL3b)" class="i0scxb85m"/></g><path fill="url(#i18KRGc)" class="i0scxb85m"/><path fill="url(#ikrLgfc)" class="i0scxb85m"/><path stroke="url(#iDooVtc)" class="xrnwqo_wb"/><g filter="url(#iogvJVc)"><path class="lbe1adjeo"/></g><g filter="url(#izzpEKe)"><path class="miy-ehbrw"/></g><g filter="url(#iiqd7Cd)"><path class="r19rmpj_u"/></g><g filter="url(#iEzW0yd)"><path clip-rule="evenodd" class="d1dyntb7l"/></g><path class="n-q8vgipj"/><path fill="url(#iwBepIj)" class="sq4uekb8r"/><path class="urssg85lp"/><g filter="url(#iUQLyWc)"><path class="l4sh1lbdx"/><path fill="url(#itbPw1c)" class="ydluasyhy"/></g><g filter="url(#i8Cqozd)"><path fill="url(#iGyAhEc)" class="gg5uaibhn"/></g><path class="qprur-bzz"/><path fill="url(#iL5lWab)" class="fx7trzutq"/><path class="sh1gujbmo"/><g filter="url(#iHCL16d)"><path fill="url(#i8tkQVd)" class="c80rpu6rc"/></g><g filter="url(#iVlQYtc)"><ellipse transform="rotate(-27.914 12.992 9.81)" class="n-4vobbjw"/><ellipse fill="url(#ixFqYNd)" transform="rotate(-27.914 12.992 9.81)" class="pozwzzb5z"/></g><g filter="url(#iGY22GA)"><path class="z6c3arb_n"/></g><g filter="url(#iDV3Yrb)"><path class="zc00f1bun"/></g><g filter="url(#iHwR8wb)"><path class="lh32rd8ly"/><path fill="url(#iMkoukb)" class="kxb2oxqri"/></g><g filter="url(#iX8khfc)"><path class="wl0fntbcj"/><path fill="url(#imLMp2J)" class="r485lvrsd"/><path fill="url(#iHIC61c)" class="r485lvrsd"/></g><g filter="url(#imvGIAe)"><path stroke="url(#iFoiHud)" class="b20m8jbxc"/></g><g filter="url(#iOZlsEb)"><path class="w3_7lxdea"/></g><path fill="url(#i53vmFc)" class="vib8s5k_w"/><g filter="url(#idzP4le)"><path clip-rule="evenodd" class="rea-pebih"/></g><defs><radialGradient id="iyRYAqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.144 13.004)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iLkKQWc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.328 13.273)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iZzY7ee" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.651 7.982)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="ipE5nIb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.088 7.448)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iSCwh1d" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 3.94 11.093)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iI2OUrd" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.703 6.669)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iftab7Q" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 22.955 9.652)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iA4TjPh" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.371 7.912)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ir6qgHp" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.671 -3.608)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iO9Hivc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.304 9.616)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iEJIJdb" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 2.509 6.87)scale(2.91973 2.69143)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="i80UNyF" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.45 18.356)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="do28bmb5k"/><stop offset="1" class="egj-02bls"/></radialGradient><radialGradient id="iKvL0ad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.353)" gradientUnits="userSpaceOnUse"><stop class="bfl4-fbqr"/><stop offset="1" class="frstvbc2m"/></radialGradient><radialGradient id="iqQd05C" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.49 14.58)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="iR3AfUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.446)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="isYkfRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.321)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="imcN5iR" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.571)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="i7g3o9c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.946)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="ic9D06l" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.728)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="ihp65kb" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.336 -.236)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="iRikR1M" cx="0" cy="0" r="1" gradientTransform="rotate(111.826 5.226 14.398)scale(3.56729 6.41649)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="ycu0bme2d"/><stop offset="1" class="zt127j5os"/></radialGradient><radialGradient id="iuSgGHb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.149)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iTZPFxd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 29.005)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="iv1Yf1c" cx="0" cy="0" r="1" gradientTransform="rotate(114.365 1.77 11.841)scale(4.20765 8.70789)" gradientUnits="userSpaceOnUse"><stop class="zqbntluns"/><stop offset="1" class="v6bhjtbbk"/></radialGradient><radialGradient id="iIbqNte" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.915)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="i5yngde" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.05068 -2.55638 0 15.426 16.604)" gradientUnits="userSpaceOnUse"><stop class="mcxximbde"/><stop offset=".632" class="ixy9j6b2x"/></radialGradient><radialGradient id="iikXNfa" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -.875 0 13.766 15.965)" gradientUnits="userSpaceOnUse"><stop class="b84tk6_fn"/><stop offset="1" class="ow2za2qas"/></radialGradient><radialGradient id="i9MSO2S" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7802 1.77747 -2.19627 -2.19964 27.55 23.273)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="ie6ITEb" cx="0" cy="0" r="1" gradientTransform="rotate(-37.321 48.4 -28.529)scale(1.01093 .52811)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="iGtTgfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.415)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="iE91Ewe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.103)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iIBhgFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.006 18.954)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="i0Wknwc" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.314)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="ikQcqUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.259)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="iJBuOLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.329)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="igcdawe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.623)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iYRB7wb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.873)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="id7iiRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.225)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iJcAO9c" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 19.485 10.943)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iQi09db" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 20.516 8.823)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iwcLqrc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 19.837 10.616)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="imULfDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 10.845 10.504)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iXKGP9x" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.305 9.966)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="ig0QGLc" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 7.414 7.358)scale(2.25599 1.57104)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="ir8nHmk" cx="0" cy="0" r="1" gradientTransform="matrix(1.0735 -3.47607 4.41049 1.36207 13.266 16.749)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iAgS3hb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11412 -7.15221 0 15.184 9.809)" gradientUnits="userSpaceOnUse"><stop offset=".611" class="jp81kzb2a"/><stop offset="1" class="s_ga92bpp"/></radialGradient><radialGradient id="i9JXABb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.56691 -6.60207 0 15.184 10.356)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="iVbpvpb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.06 6.687)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iDmpBbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 17.747 9.548)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iznzylM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.37 9.32)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iAP4N4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 20.541 11.035)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="ijy0pKc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.829 1.57435 -1.05517 -1.22584 19.367 15.082)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iVXgrxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.231 12.086)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iqHTL3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 15.99 12.298)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="ikrLgfc" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.096 8.306)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="iwBepIj" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.628 9.907)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="itbPw1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.4 9.99)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iL5lWab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.264 9.907)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ixFqYNd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.473 -1.325)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMkoukb" cx="0" cy="0" r="1" gradientTransform="matrix(1.26205 -2.75541 1.4096 .64564 9.788 7.786)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="imLMp2J" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.868 6.746)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iHIC61c" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 15.656 2.949)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><linearGradient id="ipPWqCe" x1="20.139" x2="13.334" y1="3.551" y2="16.155" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iU8OreY" x1="8.23" x2="22.659" y1="15.333" y2="15.333" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iEbjg4b" x1="11.239" x2="11.239" y1="30.446" y2="29.134" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iYvBV0p" x1="15.177" x2="14.208" y1="29.134" y2="29.134" gradientUnits="userSpaceOnUse"><stop offset=".129" class="hu0w8ibzb"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iZCVgIb" x1="19.74" x2="19.74" y1="30.446" y2="29.134" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iVGz0wc" x1="15.802" x2="16.505" y1="28.009" y2="28.009" gradientUnits="userSpaceOnUse"><stop class="o77zymbyt"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iDT9Tpf" x1="10.458" x2="12.677" y1="18.066" y2="24.753" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="i9E0HSw" x1="20.633" x2="18.282" y1="19.116" y2="23.817" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="i6Ilh4c" x1="18.958" x2="17.552" y1="24.134" y2="22.634" gradientUnits="userSpaceOnUse"><stop class="dhui3nlqd"/><stop offset="1" class="ifg4wbcuq"/><stop offset="1" class="kzdc46tfj"/></linearGradient><linearGradient id="iaeGMXb" x1="17.146" x2="17.974" y1="18.915" y2="19.259" gradientUnits="userSpaceOnUse"><stop offset=".081" class="foy77stiz"/><stop offset="1" class="i3p8g97ol"/></linearGradient><linearGradient id="itx7vie" x1="6.567" x2="6.567" y1="30.389" y2="29.255" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iuXZp7i" x1="8.38" x2="7.935" y1="29.423" y2="29.42" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="imWOU0c" x1="22.753" x2="23.162" y1="27.696" y2="27.681" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="ijxvAte" x1="23.825" x2="26.529" y1="20.884" y2="20.884" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iv2MtJd" x1="26.529" x2="26.18" y1="20.868" y2="20.868" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="iPwqvvc" x1="26.529" x2="25.177" y1="23.196" y2="23.196" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iTzgFke" x1="26.529" x2="26.129" y1="23.345" y2="23.345" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="ixWPIkI" x1="23.696" x2="24.227" y1="23.345" y2="23.345" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="i38IrPb" x1="24.782" x2="23.892" y1="21.837" y2="21.837" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iX4WJlb" x1="24.782" x2="23.892" y1="23.618" y2="23.618" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iYvzLpb" x1="27.165" x2="23.137" y1="28.087" y2="28.087" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iRvIhMe" x1="23.754" x2="25.463" y1="26.105" y2="26.105" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iL62ZWb" x1="23.676" x2="25.385" y1="27.409" y2="27.409" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iGgcEdQ" x1="23.754" x2="25.463" y1="28.714" y2="28.714" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iEYiXBd" x1="8.261" x2="22.637" y1="15.313" y2="15.313" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iA7lwUd" x1="8.261" x2="22.637" y1="15.283" y2="15.283" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iiqBOJL" x1="9.151" x2="12.11" y1="10.591" y2="10.591" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="i9kHT7d" x1="14.507" x2="15.446" y1="12.159" y2="12.159" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iVctsEc" x1="15.446" x2="15.446" y1="12.958" y2="12.348" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="i18KRGc" x1="15.524" x2="15.524" y1="12.932" y2="12.792" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="iDooVtc" x1="14.381" x2="14.842" y1="14.044" y2="13.331" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iGyAhEc" x1="18.406" x2="18.092" y1="9.96" y2="10.154" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8tkQVd" x1="14.008" x2="13.694" y1="9.96" y2="10.154" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFoiHud" x1="12.555" x2="13.099" y1="4.305" y2="5.579" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="i53vmFc" x1="10.917" x2="22.177" y1="9.764" y2="9.764" gradientUnits="userSpaceOnUse"><stop offset=".367" class="ib-sbqbsv"/><stop offset="1" class="exke9fbuy"/></linearGradient><filter id="ilK2z7c" width="15.268" height="15.768" x="7.937" y="1.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="ieTz4Oc" width="7.023" height="11.703" x="8.372" y="15.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".375"/></filter><filter id="iI1fvye" width="5.673" height="10.453" x="9.475" y="15.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="i9XDdne" width="6.388" height="10.529" x="15.682" y="16.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".375"/></filter><filter id="iVHD6Yd" width="4.22" height="3.75" x="13.316" y="14.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.121569 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="i73ZEOe" width="4.008" height=".781" x="23.173" y="18.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="ihvaC5d" width="4.468" height="5.556" x="23.137" y="24.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="iELQbOe" width="2.097" height=".3" x="23.604" y="25.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".05"/></filter><filter id="i8Fwkio" width="2.097" height=".3" x="23.526" y="27.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".05"/></filter><filter id="ip7JoVc" width="2.097" height=".3" x="23.604" y="28.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".05"/></filter><filter id="iBaxB1b" width="3.368" height="3.218" x="9.151" y="8.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="ihXrfuQ" width="3.218" height="3.468" x="18.664" y="8.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="iFJctJc" width="3.148" height="3.148" x="18.699" y="8.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".25"/></filter><filter id="im7QNeb" width="2.648" height="2.648" x="9.455" y="9.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".125"/></filter><filter id="iy6t5Lb" width="10.191" height="11.127" x="10.35" y="5.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="iXKcvKd" width="2.877" height="3.682" x="13.845" y="9.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".25"/></filter><filter id="iOLzZme" width="2.377" height="3.182" x="14.257" y="9.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".125"/></filter><filter id="iogvJVc" width="3.001" height="1.285" x="16.388" y="9.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="izzpEKe" width="3.001" height="1.285" x="11.502" y="9.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="iiqd7Cd" width="2.453" height="1.091" x="11.638" y="7.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="iEzW0yd" width="2.453" height="1.091" x="17.055" y="7.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/></filter><filter id="iUQLyWc" width=".787" height=".696" x="16.894" y="9.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".05"/></filter><filter id="i8Cqozd" width=".891" height=".913" x="17.734" y="9.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".1"/></filter><filter id="iHCL16d" width=".986" height="1.04" x="13.291" y="9.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".1"/></filter><filter id="iVlQYtc" width=".913" height=".705" x="12.536" y="9.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".05"/></filter><filter id="iGY22GA" width="2.111" height=".828" x="17.16" y="7.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".075"/></filter><filter id="iDV3Yrb" width="2.361" height="1.078" x="11.584" y="7.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".075"/></filter><filter id="iHwR8wb" width="4.412" height="4.713" x="8.991" y="3.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/><feGaussianBlur result="effect2_foregroundBlur_4002_2167" stdDeviation=".25"/></filter><filter id="iX8khfc" width="8.767" height="5.782" x="12.275" y="2.427" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/><feGaussianBlur result="effect2_foregroundBlur_4002_2167" stdDeviation=".125"/></filter><filter id="imvGIAe" width="1.145" height="2.31" x="12.255" y="3.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".1"/></filter><filter id="iOZlsEb" width="6.427" height="3.372" x="14.864" y="4.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2167" stdDeviation=".375"/></filter><filter id="idzP4le" width="11.479" height="6.324" x="9.611" y="6.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.498039 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2167"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.741176 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2167" result="effect2_innerShadow_4002_2167"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-scientist-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b20m8jbxc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.555 3.962c.023.243.234 1.156.544 1.71");
}

.b5yhvnbfs {
  d: path("M26.434 22.994c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.b84tk6_fn {
  stop-color: var(--svg-color--432c2c, #432C2C);
}

.bcxlwr27n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.636h1.797");
}

.bfl4-fbqr {
  stop-color: var(--svg-color--5f4786, #5F4786);
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bpjxo1muy {
  d: path("M10.359 9.241h.012l-.01-.265l-.01-.306c.02-.95.574-1.317.81-1.439l.05-.02q.029-.013.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.119 3.073c-.123 2.803-2.311 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.c80rpu6rc {
  d: path("M14.077 10.217c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.cebxepb-r {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.053 10.605l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
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

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d1dyntb7l {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.177 8.268l-.137.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.d9tr4ab2j {
  d: path("M20.273 11.578a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.dhui3nlqd {
  stop-color: var(--svg-color--d6baf6, #D6BAF6);
}

.do28bmb5k {
  stop-color: var(--svg-color--755b9f, #755B9F);
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e35whsbac {
  d: path("M15.466 15.384c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.egj-02bls {
  stop-color: var(--svg-color--482f73, #482F73);
}

.elug4ib2p {
  d: path("M26.529 21.259v4.172h-2.704v-4.172z");
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.exke9fbuy {
  stop-color: var(--svg-color--5fb390, #5FB390);
  stop-opacity: 0.5;
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.foy77stiz {
  stop-color: var(--svg-color--9f98a7, #9F98A7);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.frstvbc2m {
  stop-color: var(--svg-color--5f4786, #5F4786);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx7trzutq {
  d: path("M13.262 9.43a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g0v5xv26o {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.712px;
  rx: 0.391px;
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g4qo_rdhw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.331h1.797");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gg5uaibhn {
  d: path("M18.425 10.205a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h5ekbbbij {
  d: path("M23.825 19.493h2.703v5.938h-2.703z");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hu0w8ibzb {
  stop-color: var(--svg-color--b5a2c9, #B5A2C9);
}

.hv1xy1b4f {
  d: path("M22.753 30.024v-11.79c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i0scxb85m {
  d: path("m15.064 10.466l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.i3p8g97ol {
  stop-color: var(--svg-color--e2d6f0, #E2D6F0);
  stop-opacity: 0;
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.ib-sbqbsv {
  stop-color: var(--svg-color--335c55, #335C55);
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.ih2uysbls {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 26.027h1.797");
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.ixy9j6b2x {
  stop-color: var(--svg-color--42272a, #42272A);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j7vqxwjtw {
  d: path("m9.608 17.148l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .084.249l-.626.69a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.298-1.807.722-2.61 1.255");
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jp81kzb2a {
  stop-color: var(--svg-color--3b1d30, #3B1D30);
  stop-opacity: 0;
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.k-c2wqbxs {
  d: path("M10.76 12.113a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.k2-oqvygh {
  fill-rule: evenodd;
  d: path("M22.631 11.913c.213-.435.324-.92.324-1.427c0-.467-.096-.905-.269-1.305h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.215 3.299v.01a3.24 3.24 0 0 1-.526 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.121-.981-.324-1.406a.51.51 0 0 1 0-.456m-12.26-2.672h-.012l1.198 2.356c.124 2.802 1.217 0 3.889 0s3.836 3.119 3.96.316l1.135-3.197c-.053-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.673a.264.264 0 0 0-.461.05l-.082.195A2.3 2.3 0 0 1 11.16 7.23c-.236.122-.79.49-.81 1.439l.01.306z");
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kxb2oxqri {
  d: path("M10.377 4.515c.565-.599 1.636-.6 2.13-.51l.396 1.29c-.253-.039-.478.05-.667.235c-.449 1.26-1.99 1.955-2.704 2.145c-.149-1.492.109-2.38.845-3.16");
}

.kzdc46tfj {
  stop-color: var(--svg-color--e7cfff, #E7CFFF);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l4sh1lbdx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.564 9.618c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lbe1adjeo {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M16.588 9.935c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.269.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.08-.45");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lh32rd8ly {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M10.377 4.515c.565-.599 1.636-.6 2.13-.51l.396 1.29c-.253-.039-.478.05-.667.235c-.449 1.26-1.99 1.955-2.704 2.145c-.149-1.492.109-2.38.845-3.16");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljwmioblb {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.064 10.466l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.m36bl-xzp {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.712px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.m3t7pactc {
  d: path("M23.137 25.35c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcxximbde {
  stop-color: var(--svg-color--371a2d, #371A2D);
}

.mf98ki1lw {
  d: path("M15.426 18.654a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.miy-ehbrw {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.304 9.935c-.266-.467-.67-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.27.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.mpfi5wb3o {
  d: path("M8.226 30.025v-11.79c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n-4vobbjw {
  cx: 12.992px;
  cy: 9.811px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.n-q8vgipj {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.837 9.158c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nk4g_bcbl {
  d: path("M19.865 16.317a10.5 10.5 0 0 1 2.878 1.917v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.519z");
}

.o2gqjcckt {
  d: path("M23.825 22.071v-.468h.805a.234.234 0 1 1 0 .468z");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o77zymbyt {
  stop-color: var(--svg-color--a588b8, #A588B8);
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ow2za2qas {
  stop-color: var(--svg-color--432c2c, #432C2C);
  stop-opacity: 0;
}

.p-lk43bls {
  d: path("m9.255 17.845l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .084.248l-.626.691a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.381a2 2 0 0 0-.176-.82l-2.605-5.803a10.6 10.6 0 0 0-2.61 1.256");
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pozwzzb5z {
  cx: 12.992px;
  cy: 9.811px;
  rx: 0.39px;
  ry: 0.197px;
}

.q-fl22tnr {
  stop-color: var(--svg-color--cfbce6, #CFBCE6);
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qprur-bzz {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.055 9.158c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r19rmpj_u {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.048 8.726l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.003l.009-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.816-.2 1.329-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.182z");
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.r485lvrsd {
  d: path("M14.843 2.713c-1.133-.25-2.15.88-2.268 1.3c1.052 3.544 3.714 3.35 6.34 3.058c1.573-.175 1.744.542 1.878.888c0-3.932-3.344-4.67-5.922-5.24z");
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rea-pebih {
  fill: var(--svg-color--9b94a2, #9B94A2);
  fill-rule: evenodd;
  d: path("M9.761 9.206C9.773 7.53 11.15 6.2 12.808 6.2h5.275a3.01 3.01 0 0 1 3.007 3.04c-.022 1.568-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.341c-.045-.066-.09-.076-.112-.076s-.067.01-.112.075a3.08 3.08 0 0 1-2.549 1.353a3.02 3.02 0 0 1-3.017-3.017zm.6.003a2.42 2.42 0 0 0 2.417 2.415c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34a.74.74 0 0 1 .609.34v.002a2.46 2.46 0 0 0 2.114 1.077c1.248-.045 2.31-1.133 2.328-2.382a2.41 2.41 0 0 0-2.407-2.432h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s_ga92bpp {
  stop-color: var(--svg-color--411d40, #411D40);
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.sh1gujbmo {
  fill: var(--svg-color--000, #000);
  d: path("M13.773 10.322a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sprcjgfur {
  d: path("M15.8 15.284c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.sq4uekb8r {
  d: path("M17.63 9.43a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.t1_gw3q7o {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.273 11.578a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.u0i2txb_m {
  d: path("M11.114 16.317a10.5 10.5 0 0 0-2.878 1.917v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.519z");
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.urssg85lp {
  fill: var(--svg-color--000, #000);
  d: path("M17.119 10.322c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.uvcfm_3sz {
  d: path("m21.37 17.148l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.249l.626.69a.5.5 0 0 1-.014.687l-4.732 4.808a.2.2 0 0 1-.343-.14v-3.38a2 2 0 0 1 .175-.82l2.606-5.803c.929.298 1.807.722 2.61 1.255");
}

.v-7zmcr6h {
  d: path("M10.78 11.578a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v6bhjtbbk {
  stop-color: var(--svg-color--a8a1ad, #A8A1AD);
  stop-opacity: 0;
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.vib8s5k_w {
  d: path("M18.083 6.5h-5.275c-1.497 0-2.737 1.2-2.747 2.708a2.72 2.72 0 0 0 2.717 2.717c.942 0 1.814-.486 2.3-1.22c.189-.278.533-.278.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.27 2.618-2.678a2.71 2.71 0 0 0-2.707-2.736");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w3_7lxdea {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.852 6.323l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wkncf3j-v {
  d: path("M23.825 23.853v-.47h.805a.234.234 0 1 1 0 .47z");
}

.wl0fntbcj {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M14.843 2.713c-1.133-.25-2.15.88-2.268 1.3c1.052 3.544 3.714 3.35 6.34 3.058c1.573-.175 1.744.542 1.878.888c0-3.932-3.344-4.67-5.922-5.24z");
}

.wmoe38bcw {
  d: path("M15.466 15.334h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
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

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xrnwqo_wb {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.048 13.026a.204.204 0 0 0-.248.044a.196.196 0 0 0-.02.247a1.982 1.982 0 0 0 3.332 0a.2.2 0 0 0-.02-.25a.205.205 0 0 0-.248-.04c-.404.215-.88.338-1.398.338a3 3 0 0 1-1.398-.339Z");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.xyt5u_bsm {
  d: path("m21.202 18.288l.116 1.533a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.075.22l.554.611a.44.44 0 0 1-.013.608l-4.188 4.254a.177.177 0 0 1-.303-.124v-2.991c0-.25.053-.497.155-.725l2.306-5.136a9.4 9.4 0 0 1 2.31 1.112");
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.ycu0bme2d {
  stop-color: var(--svg-color--c2bfc3, #C2BFC3);
}

.ydluasyhy {
  d: path("M17.564 9.618c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z3itxhbjk {
  d: path("M15.47 15.284h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.z4m0-bobm {
  d: path("M20.273 12.113a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z6c3arb_n {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 8.131c.323-.078 1.125-.04 1.661.345");
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zc00f1bun {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.595 8.131c-.323-.078-1.125-.04-1.661.345");
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zqbntluns {
  stop-color: var(--svg-color--746e77, #746E77);
}

.zt127j5os {
  stop-color: var(--svg-color--ddd8e2, #DDD8E2);
  stop-opacity: 0;
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

.zzwkb2klc {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M10.78 11.578a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

</style>
