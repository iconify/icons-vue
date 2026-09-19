<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iUIr9Td)"><path fill="url(#iJAyzme)" clip-rule="evenodd" class="wv7rdbbew"/><path fill="url(#ifGQ7Me)" clip-rule="evenodd" class="wv7rdbbew"/><path fill="url(#iss8eFb)" clip-rule="evenodd" class="wv7rdbbew"/><path fill="url(#iit04ne)" clip-rule="evenodd" class="wv7rdbbew"/><path fill="url(#iObZu1b)" clip-rule="evenodd" class="wv7rdbbew"/><path fill="url(#i4YDSNb)" clip-rule="evenodd" class="wv7rdbbew"/><path fill="url(#iUfRAlb)" clip-rule="evenodd" class="wv7rdbbew"/><path fill="url(#iC5GLde)" clip-rule="evenodd" class="wv7rdbbew"/><path fill="url(#i5O5cDd)" clip-rule="evenodd" class="wv7rdbbew"/><path fill="url(#i5I59Wc)" clip-rule="evenodd" class="wv7rdbbew"/><path fill="url(#ilr4bjd)" clip-rule="evenodd" class="wv7rdbbew"/></g><g filter="url(#i1HMAge)"><path fill="url(#i9hWbMl)" class="kmjyd7vjj"/></g><g filter="url(#i804VQb)"><path fill="url(#io543Ce)" class="yzd5z8uce"/><path fill="url(#izItjEe)" class="yzd5z8uce"/></g><g filter="url(#i9FMgge)"><path class="d6dehtb8a"/><path fill="url(#iOtgqYd)" class="bxgp1vcjo"/></g><g filter="url(#iKn6X0c)"><path class="r7bjwqbfo"/><path fill="url(#i7qEhsc)" class="ik8xyobfx"/></g><g filter="url(#id7sF6j)"><path fill="url(#idcbMHb)" class="bi9-s6bdb"/><path fill="url(#icMOY6x)" class="bi9-s6bdb"/><path fill="url(#ieSQIjd)" class="bi9-s6bdb"/><path fill="url(#ic8MDbb)" class="bi9-s6bdb"/><path fill="url(#iPGVo5c)" class="bi9-s6bdb"/><path fill="url(#iwKhzce)" class="bi9-s6bdb"/><path fill="url(#iVlWG1b)" class="bi9-s6bdb"/><path fill="url(#iFDcVge)" class="bi9-s6bdb"/><path fill="url(#i8DoIgc)" class="bi9-s6bdb"/></g><path fill="url(#iNaKVuc)" class="bi9-s6bdb"/><g filter="url(#if5NlCc)"><path class="xc2ytjbdf"/></g><g filter="url(#iH0H0xb)"><path class="x2-ozkb9d"/><path fill="url(#iAjlB2c)" class="r24llbcyh"/><path fill="url(#ixPxQcc)" class="r24llbcyh"/><path fill="url(#iu3PBZc)" class="r24llbcyh"/><path fill="url(#iNF8dyW)" class="r24llbcyh"/></g><path fill="url(#i5fgmeb)" class="r24llbcyh"/><path fill="url(#iU0IJeb)" class="r24llbcyh"/><g filter="url(#ixovyQc)"><path class="lynvfkb0g"/></g><g filter="url(#i4WRH7R)"><path class="gdx-nch-q"/></g><path class="v3mt48bos"/><path fill="url(#i3f5dsb)" class="sqvk0-wgn"/><path class="fuemwebza"/><g filter="url(#ibVXrKd)"><path class="sdcu1vzsq"/><path fill="url(#igkebib)" class="xrzqrcaow"/></g><g filter="url(#i1syESb)"><path fill="url(#iYS6une)" class="kc75r1hvm"/></g><path class="bq8cukg2p"/><path fill="url(#i30iaVc)" class="unsg_9i7n"/><path class="lhlux4ccg"/><g filter="url(#ioKzrRc)"><path fill="url(#iAcJBac)" class="ssdt-h3mg"/></g><g filter="url(#ioWXoPc)"><ellipse transform="rotate(-27.914 13.09 11.79)" class="cbta_5bhs"/><ellipse fill="url(#iamCTqc)" transform="rotate(-27.914 13.09 11.79)" class="vcr2dvbcg"/></g><g filter="url(#iKp5SOd)"><path class="vzfpe-bfh"/><path fill="url(#iR0E2Re)" class="a57nbacxk"/></g><g filter="url(#i7wtoLD)"><path class="o7mz4obus"/><path fill="url(#iEbigGc)" class="pxck8xtyd"/><path fill="url(#iCM0Jec)" class="pxck8xtyd"/></g><g filter="url(#ifLqNHe)"><path stroke="url(#iChWLBe)" class="gh06i_bwj"/></g><g filter="url(#inSmZMd)"><path class="e1ydf8eom"/></g><g filter="url(#iVPFk0b)"><path class="wa8_3edge"/></g><g filter="url(#iUK6zgc)"><path class="djm7mmlof"/></g><g filter="url(#iV5szFb)"><path class="uz7egszvt"/></g><g filter="url(#imD43qb)"><path class="pgte_nz8r"/></g><path class="ysj89xb8s"/><path fill="url(#iC9kixd)" class="xdsxl7bjo"/><path fill="url(#iv8DsMc)" class="xdsxl7bjo"/><path fill="url(#iVJV0Ee)" class="xdsxl7bjo"/><path fill="url(#itX3d8d)" class="v16-52b6b"/><path fill="url(#iVXnGYr)" class="lgmacdb2q"/><path fill="url(#iSvb6ea)" class="lgmacdb2q"/><path fill="url(#ipcj6zy)" class="lgmacdb2q"/><path fill="url(#iO5Zesb)" class="lgmacdb2q"/><path fill="url(#iLzGgnd)" class="lgmacdb2q"/><path fill="url(#iw2wvqb)" class="lgmacdb2q"/><path fill="url(#i6WA3cc)" class="lgmacdb2q"/><path fill="url(#iy9kUmb)" class="teox85xlx"/><path fill="url(#iue3YqJ)" class="teox85xlx"/><path fill="url(#iiy6aQe)" class="ane5tobnb"/><path fill="url(#ii44AZA)" class="ane5tobnb"/><path fill="url(#icStzfb)" class="ane5tobnb"/><path fill="url(#iwWaYJb)" class="ane5tobnb"/><path fill="url(#ioqgBae)" class="dx0hs4dxz"/><path fill="url(#iPZbDld)" class="dx0hs4dxz"/><path fill="url(#iygVzxd)" class="dx0hs4dxz"/><path fill="url(#i8DuMSb)" class="k5ll9tbuz"/><path fill="url(#ibIYpGe)" class="k5ll9tbuz"/><path fill="url(#iboJCme)" class="hy-4xod4o"/><path fill="url(#ikOnTcb)" class="hy-4xod4o"/><path fill="url(#ib40kNb)" class="hy-4xod4o"/><g filter="url(#i4ZYnFi)"><path fill="url(#iiitaSb)" class="dzgr7t_nc"/><path fill="url(#iqoxCcc)" class="dzgr7t_nc"/></g><path fill="url(#iZlSLFb)" class="dzgr7t_nc"/><g filter="url(#iKtVdje)"><path fill="url(#ifmspbb)" class="in_62fc8y"/></g><defs><radialGradient id="ifGQ7Me" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 .971 14.83)scale(5.79283 7.23642)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iss8eFb" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.659 9.949)scale(4.38021 5.75526)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iit04ne" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.842 8.962)scale(2.71103 2.0817)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iObZu1b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62572 2.66023 -1.8739 -1.14518 10.65 10.387)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i4YDSNb" cx="0" cy="0" r="1" gradientTransform="matrix(1.73125 3.29364 -4.57208 2.40325 11.748 2.513)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iUfRAlb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 10.702 7.438)scale(2.56774 3.58838)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iC5GLde" cx="0" cy="0" r="1" gradientTransform="matrix(-2.32233 .67562 -1.40896 -4.84304 25.64 11.59)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i5O5cDd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 11.461 9.48)scale(3.65605 4.65727)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="i5I59Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.12 -3.658)scale(3.52739 2.78996)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ilr4bjd" cx="0" cy="0" r="1" gradientTransform="matrix(1.89438 .1987 -.32196 3.06944 8.445 11.545)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="io543Ce" cx="0" cy="0" r="1" gradientTransform="matrix(3.13528 -1.42513 1.74002 3.82804 21.27 13.217)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="izItjEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.65737 .92898 -.26264 .46856 22.568 10.546)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iOtgqYd" cx="0" cy="0" r="1" gradientTransform="matrix(1.9019 -.14147 .1106 1.48676 21.713 12.805)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="i7qEhsc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52014 0 0 -1.1992 10.386 12.663)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="idcbMHb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.576 8.164)scale(9.02114 12.0746)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="icMOY6x" cx="0" cy="0" r="1" gradientTransform="matrix(-2.56516 1.2228 -.85154 -1.78634 18.483 13.048)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="ieSQIjd" cx="0" cy="0" r="1" gradientTransform="rotate(-72.838 20.631 1.16)scale(4.5826 5.81447)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="ic8MDbb" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 3.015 13.587)scale(8.62486 8.67105)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iPGVo5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.27186 -8.31616 0 15.852 12.478)" gradientUnits="userSpaceOnUse"><stop offset=".858" class="l-0cbacrb"/><stop offset="1" class="tetwumyrr"/></radialGradient><radialGradient id="iwKhzce" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.542 7.98)scale(8.86449 15.2619)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iVlWG1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44954 1.77899 0 19.08 11.46)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iFDcVge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.65328 1.89477 0 13.566 11.171)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="i8DoIgc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.41247 3.84373 -3.07777 -1.93173 18.594 8.313)" gradientUnits="userSpaceOnUse"><stop offset=".471" class="ilch2lbja"/><stop offset="1" class="nt58yqb6u"/></radialGradient><radialGradient id="iNaKVuc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61898 0 0 -8.11903 22.6 13.333)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iAjlB2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.57381 -2.5747 .7935 -.17684 17.17 14.248)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iNF8dyW" cx="0" cy="0" r="1" gradientTransform="matrix(-.98176 0 0 -.27447 16.867 14.515)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iU0IJeb" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.193 9.466)scale(2.09509 2.51797)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="i3f5dsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02196 -1.62554 0 18.93 11.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="igkebib" cx="0" cy="0" r="1" gradientTransform="matrix(-.29213 -.37645 .51828 -.4022 18.643 12.017)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i30iaVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02196 -1.62555 0 13.433 11.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iamCTqc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00974 -.62233 .74807 -.01171 13.071 12.188)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iR0E2Re" cx="0" cy="0" r="1" gradientTransform="matrix(1.58969 -3.47082 1.77558 .81324 9.054 9.24)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iEbigGc" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.451 7.184)scale(6.13805 10.0354)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iCM0Jec" cx="0" cy="0" r="1" gradientTransform="matrix(-.26494 1.72216 -3.70514 -.57001 16.446 3.147)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iC9kixd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.8125 10.4384 0 16.688 30.264)" gradientUnits="userSpaceOnUse"><stop class="gfj1348zm"/><stop offset=".714" class="vqiy7zq_f"/></radialGradient><radialGradient id="iv8DsMc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.563 22.299)" gradientUnits="userSpaceOnUse"><stop class="uatqp3rks"/><stop offset="1" class="oln0s8bds"/></radialGradient><radialGradient id="iVJV0Ee" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.188 21.08)" gradientUnits="userSpaceOnUse"><stop class="leds28lfi"/><stop offset="1" class="x0hvtbbrr"/></radialGradient><radialGradient id="itX3d8d" cx="0" cy="0" r="1" gradientTransform="matrix(2.6551 1.32154 -2.0509 4.12044 8.47 17.102)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="xjoxl1baz"/><stop offset="1" class="xm7oxtb8r"/></radialGradient><radialGradient id="iVXnGYr" cx="0" cy="0" r="1" gradientTransform="matrix(16.5217 8.52358 -2.95327 5.72447 15.039 18.518)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="fupnc-bzv"/><stop offset="1" class="h4nid6imp"/></radialGradient><radialGradient id="iSvb6ea" cx="0" cy="0" r="1" gradientTransform="matrix(-5.125 2.06252 -1.29855 -3.22666 31.125 24.063)" gradientUnits="userSpaceOnUse"><stop class="qomb6ec0x"/><stop offset="1" class="ha79_8bui"/></radialGradient><radialGradient id="ipcj6zy" cx="0" cy="0" r="1" gradientTransform="rotate(116.107 1.715 13.253)scale(4.96085 7.77144)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="vxxihotpt"/><stop offset="1" class="amuq4_bzy"/></radialGradient><radialGradient id="iLzGgnd" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.264 -3.362)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="fjifp0bsg"/><stop offset="1" class="wn5ytjbyn"/></radialGradient><radialGradient id="i6WA3cc" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -3 .29081 .6725 18.281 24.342)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="zlawngbku"/><stop offset="1" class="oc_o5xbok"/></radialGradient><radialGradient id="iy9kUmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 .59375 -1.31526 -3.21892 23.531 17.67)" gradientUnits="userSpaceOnUse"><stop class="y0cud7bhd"/><stop offset="1" class="irfgqiu-v"/></radialGradient><radialGradient id="iiy6aQe" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.438 18.736)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y0d2ypbdf"/><stop offset="1" class="tmdmcl4vt"/></radialGradient><radialGradient id="ioqgBae" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08762 1.06609 -.43646 -.85468 29.165 17.297)" gradientUnits="userSpaceOnUse"><stop class="thafvacgt"/><stop offset=".615" class="n42kk7pqk"/></radialGradient><radialGradient id="i8DuMSb" cx="0" cy="0" r="1" gradientTransform="rotate(-165.54 4.95 9.054)scale(1.96996 1.63501)" gradientUnits="userSpaceOnUse"><stop class="camp3gbri"/><stop offset=".697" class="d-rprdjqx"/></radialGradient><radialGradient id="ibIYpGe" cx="0" cy="0" r="1" gradientTransform="matrix(.74865 .58312 -.61233 .78615 6.048 17.987)" gradientUnits="userSpaceOnUse"><stop class="lqt9uqtub"/><stop offset="1" class="off4cm2_g"/></radialGradient><radialGradient id="iboJCme" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.346 6.274)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="sq5l9g8_d"/><stop offset="1" class="sst8orbli"/></radialGradient><radialGradient id="ikOnTcb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07812 .5625 -.19373 -.37132 30.126 13.127)" gradientUnits="userSpaceOnUse"><stop class="kbuu85jbe"/><stop offset="1" class="q59v_vbuo"/></radialGradient><radialGradient id="iqoxCcc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.71 18.14)" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="gxtn60bqm"/></radialGradient><radialGradient id="iZlSLFb" cx="0" cy="0" r="1" gradientTransform="matrix(1.05293 -.08258 .27016 3.4445 4.46 17.866)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="ryyyekfgi"/><stop offset="1" class="bhv0cwbcf"/></radialGradient><filter id="iUIr9Td" width="19.167" height="19.667" x="6.723" y="1.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24795"/></filter><filter id="i1HMAge" width="4.204" height="4.054" x="8.252" y="10.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24795"/></filter><filter id="i804VQb" width="4.054" height="4.304" x="20.235" y="10.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24795"/></filter><filter id="i9FMgge" width="3.706" height="3.706" x="20.409" y="10.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".25"/></filter><filter id="iKn6X0c" width="3.206" height="3.206" x="8.7" y="11.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".125"/></filter><filter id="id7sF6j" width="12.837" height="13.801" x="9.763" y="6.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24795"/></filter><filter id="if5NlCc" width="3.365" height="4.378" x="14.295" y="11.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".25"/></filter><filter id="iH0H0xb" width="2.865" height="3.878" x="14.749" y="11.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".125"/></filter><filter id="ixovyQc" width="3.729" height="1.619" x="17.42" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24795"/></filter><filter id="i4WRH7R" width="3.729" height="1.619" x="11.214" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24795"/></filter><filter id="ibVXrKd" width=".939" height=".825" x="18.031" y="11.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".05"/></filter><filter id="i1syESb" width="1.019" height="1.047" x="19.115" y="11.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".1"/></filter><filter id="ioKzrRc" width="1.139" height="1.206" x="13.519" y="11.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".1"/></filter><filter id="ioWXoPc" width="1.098" height=".835" x="12.542" y="11.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".05"/></filter><filter id="iKp5SOd" width="5.198" height="5.578" x="8.281" y="4.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24795"/><feGaussianBlur result="effect2_foregroundBlur_3987_24795" stdDeviation=".2"/></filter><filter id="i7wtoLD" width="10.901" height="7.153" x="12.266" y="2.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24795"/><feGaussianBlur result="effect2_foregroundBlur_3987_24795" stdDeviation=".125"/></filter><filter id="ifLqNHe" width="1.286" height="2.754" x="12.239" y="4.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".1"/></filter><filter id="inSmZMd" width="9.706" height="5.858" x="14.643" y="4.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".875"/></filter><filter id="iVPFk0b" width="2.884" height="1.34" x="11.502" y="8.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.027451 0 0 0 0 0.0117647 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24795"/></filter><filter id="iUK6zgc" width="2.884" height="1.34" x="18.065" y="8.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.027451 0 0 0 0 0.0117647 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24795"/></filter><filter id="iV5szFb" width="2.717" height="1.234" x="11.612" y="8.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".125"/></filter><filter id="imD43qb" width="2.717" height="1.234" x="18.022" y="8.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".125"/></filter><filter id="i4ZYnFi" width="7.3" height="8.016" x="2.126" y="12.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.137255 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24795"/></filter><filter id="iKtVdje" width="5.538" height="5.423" x="24.323" y="13.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24795" stdDeviation=".2"/></filter><linearGradient id="iJAyzme" x1="22.093" x2="13.521" y1="3.906" y2="19.783" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="i9hWbMl" x1="8.252" x2="11.98" y1="12.773" y2="12.773" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="ixPxQcc" x1="14.999" x2="16.181" y1="14.34" y2="14.34" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iu3PBZc" x1="16.181" x2="16.181" y1="15.347" y2="14.578" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="i5fgmeb" x1="16.28" x2="16.28" y1="15.314" y2="15.138" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="iYS6une" x1="19.91" x2="19.515" y1="11.979" y2="12.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAcJBac" x1="14.37" x2="13.974" y1="11.979" y2="12.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iChWLBe" x1="12.539" x2="13.226" y1="4.856" y2="6.46" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iO5Zesb" x1="9.282" x2="10.611" y1="18.361" y2="18.985" gradientUnits="userSpaceOnUse"><stop class="x0-05wb5o"/><stop offset="1" class="b_wdx7bxu"/></linearGradient><linearGradient id="iw2wvqb" x1="17.608" x2="18.032" y1="26.567" y2="25.611" gradientUnits="userSpaceOnUse"><stop class="jbvrfolcv"/><stop offset=".46" class="byl3sfbil"/></linearGradient><linearGradient id="iue3YqJ" x1="24.234" x2="24.094" y1="18.172" y2="18.238" gradientUnits="userSpaceOnUse"><stop class="zb0hqnb-l"/><stop offset="1" class="sqzs4ozft"/></linearGradient><linearGradient id="ii44AZA" x1="15.071" x2="14.357" y1="27.005" y2="25.398" gradientUnits="userSpaceOnUse"><stop class="na3bqccxs"/><stop offset="1" class="tndlebqua"/></linearGradient><linearGradient id="icStzfb" x1="23.094" x2="21.938" y1="18.531" y2="19.094" gradientUnits="userSpaceOnUse"><stop class="fp2c12bya"/><stop offset="1" class="xyqac8gqa"/></linearGradient><linearGradient id="iwWaYJb" x1="3.357" x2="6.643" y1="28.148" y2="26.541" gradientUnits="userSpaceOnUse"><stop class="m_3r9vbdq"/><stop offset="1" class="iioqnhb4d"/></linearGradient><linearGradient id="iPZbDld" x1="28.38" x2="27.916" y1="18.308" y2="17.881" gradientUnits="userSpaceOnUse"><stop offset=".198" class="jkm4jmgye"/><stop offset="1" class="svnghenix"/></linearGradient><linearGradient id="iygVzxd" x1="26.54" x2="27.158" y1="17.954" y2="18.375" gradientUnits="userSpaceOnUse"><stop offset=".353" class="mfwhtqbpf"/><stop offset="1" class="f2y_cno1u"/></linearGradient><linearGradient id="ib40kNb" x1="25.615" x2="26.123" y1="14.143" y2="15.042" gradientUnits="userSpaceOnUse"><stop class="xlrzicczw"/><stop offset="1" class="ikzehdbwc"/></linearGradient><linearGradient id="iiitaSb" x1="8.126" x2="4.501" y1="15.611" y2="19.861" gradientUnits="userSpaceOnUse"><stop offset=".206" class="gbpxfde5c"/><stop offset="1" class="fz359gsqc"/></linearGradient><linearGradient id="ifmspbb" x1="29.343" x2="24.2" y1="14.707" y2="17.575" gradientUnits="userSpaceOnUse"><stop class="ept1d-nvv"/><stop offset="1" class="z2eb7q_dp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-no-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a57nbacxk {
  d: path("M9.796 5.12c.713-.754 2.061-.756 2.684-.643l.498 1.626c-.318-.05-.602.063-.84.295c-.565 1.588-2.506 2.463-3.406 2.703c-.187-1.88.137-2.998 1.064-3.98");
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.amuq4_bzy {
  stop-color: var(--svg-color--9771d7, #9771D7);
  stop-opacity: 0;
}

.ane5tobnb {
  d: path("M20.566 15.96L5.159 23.132a3.53 3.53 0 0 0-1.7 4.691a3.516 3.516 0 0 0 4.679 1.705l15.407-7.183c.503-.232.724-.837.483-1.341l-2.123-4.57a1.003 1.003 0 0 0-1.339-.475");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b_wdx7bxu {
  stop-color: var(--svg-color--62429a, #62429A);
  stop-opacity: 0;
}

.bhv0cwbcf {
  stop-color: var(--svg-color--53403d, #53403D);
  stop-opacity: 0;
}

.bi9-s6bdb {
  d: path("M9.773 11.073h.016l-.013-.334l-.013-.386c.026-1.195.723-1.658 1.02-1.812l.065-.026q.035-.015.065-.025a2.9 2.9 0 0 0 1.498-1.555l.103-.245a.332.332 0 0 1 .582-.064a4.87 4.87 0 0 0 4.017 2.108h4.056c.227 0 1.363.11 1.43 1.678l-.149 3.87c-.155 3.53-2.912 5.901-6.277 5.901s-6.122-2.37-6.277-5.9z");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bq8cukg2p {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.17 10.968a1.76 1.76 0 0 0-1.707 1.334a.345.345 0 0 0 .337.429h2.81a.29.29 0 0 0 .287-.342a1.765 1.765 0 0 0-1.727-1.421");
}

.bxgp1vcjo {
  d: path("M22.262 14.016a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.byl3sfbil {
  stop-color: var(--svg-color--684c9e, #684C9E);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.camp3gbri {
  stop-color: var(--svg-color--402f2d, #402F2D);
}

.cbta_5bhs {
  cx: 13.091px;
  cy: 11.791px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.491px;
  ry: 0.248px;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
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

.d-rprdjqx {
  stop-color: var(--svg-color--311a22, #311A22);
}

.d6dehtb8a {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M22.262 14.016a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.djm7mmlof {
  fill: var(--svg-color--101010, #101010);
  d: path("M20.837 10.045a.35.35 0 0 0-.25-.426l-2.086-.543a.349.349 0 1 0-.175.676l2.086.542a.35.35 0 0 0 .425-.25");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dx0hs4dxz {
  d: path("M24.876 19.664a.885.885 0 0 1 .35-1.203l2.609-1.427a.899.899 0 1 1 .856 1.58l-2.621 1.404a.885.885 0 0 1-1.194-.354");
}

.dzgr7t_nc {
  d: path("m9.126 15.931l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1ydf8eom {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m19.212 7.397l-1.795.33a.867.867 0 1 1-.158-1.72h2.949c1.744 0 2.321 1.758 2.392 2.359a3.96 3.96 0 0 0-3.388-.969");
}

.ept1d-nvv {
  stop-color: var(--svg-color--655351, #655351);
}

.f2y_cno1u {
  stop-color: var(--svg-color--33211e, #33211E);
  stop-opacity: 0;
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fjifp0bsg {
  stop-color: var(--svg-color--745b8c, #745B8C);
}

.fp2c12bya {
  stop-color: var(--svg-color--a680df, #A680DF);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.fuemwebza {
  fill: var(--svg-color--000, #000);
  d: path("M18.289 12.435a.64.64 0 0 1 .643-.644a.64.64 0 0 1 .573.94h-1.14a.6.6 0 0 1-.076-.296");
}

.fupnc-bzv {
  stop-color: var(--svg-color--8066bd, #8066BD);
}

.fz359gsqc {
  stop-color: var(--svg-color--391d25, #391D25);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gbpxfde5c {
  stop-color: var(--svg-color--4f312d, #4F312D);
}

.gdx-nch-q {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.743 11.947c-.334-.588-.843-1.053-1.937-1.053c-.478 0-.94.133-1.35.465c-.34.273-.294.623-.032.754l.7.4c.821-.265 1.73-.301 2.619-.566");
}

.gfj1348zm {
  stop-color: var(--svg-color--6547af, #6547AF);
}

.gh06i_bwj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.54 4.423c.029.306.295 1.457.686 2.154");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gxtn60bqm {
  stop-color: var(--svg-color--635251, #635251);
  stop-opacity: 0;
}

.h4nid6imp {
  stop-color: var(--svg-color--593b97, #593B97);
}

.ha79_8bui {
  stop-color: var(--svg-color--8e7cc9, #8E7CC9);
  stop-opacity: 0;
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hy-4xod4o {
  d: path("m23.126 15.931l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.iioqnhb4d {
  stop-color: var(--svg-color--604c85, #604C85);
  stop-opacity: 0;
}

.ik8xyobfx {
  d: path("M10.303 14.016a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.ikzehdbwc {
  stop-color: var(--svg-color--3a221f, #3A221F);
  stop-opacity: 0;
}

.ilch2lbja {
  stop-color: var(--svg-color--4c3b3b, #4C3B3B);
}

.in_62fc8y {
  d: path("M26.817 15.484c.527-.847 1.795-1.665 2.462-1.988a.13.13 0 0 1 .152.034a.132.132 0 0 1-.033.197c-2.06 1.272-1.875 1.784-2.645 3.096c-.355.605-1.177 1.113-1.556 1.284l-.474-.899c.53-.28 1.463-.711 2.094-1.724");
}

.irfgqiu-v {
  stop-color: var(--svg-color--58448e, #58448E);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jbvrfolcv {
  stop-color: var(--svg-color--684c9e, #684C9E);
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jkm4jmgye {
  stop-color: var(--svg-color--3e2124, #3E2124);
}

.k5ll9tbuz {
  d: path("M7.372 19.634a.885.885 0 0 0-.351-1.203l-2.553-1.398a.899.899 0 1 0-.855 1.581l2.565 1.374a.885.885 0 0 0 1.194-.354");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kbuu85jbe {
  stop-color: var(--svg-color--624e4c, #624E4C);
}

.kc75r1hvm {
  d: path("M19.934 12.287a1.06 1.06 0 0 0-.292-.583l-.327.359l.148.287z");
}

.kmjyd7vjj {
  d: path("M10.28 14.69a2.027 2.027 0 1 0 0-4.053a2.027 2.027 0 0 0 0 4.053");
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

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.leds28lfi {
  stop-color: var(--svg-color--785e96, #785E96);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lgmacdb2q {
  d: path("m11.686 15.96l15.407 7.177a3.53 3.53 0 0 1 1.7 4.687a3.517 3.517 0 0 1-4.679 1.704L8.707 22.341A1 1 0 0 1 8.224 21l2.123-4.567a1.004 1.004 0 0 1 1.339-.474");
}

.lhlux4ccg {
  fill: var(--svg-color--000, #000);
  d: path("M14.074 12.435a.64.64 0 0 0-.644-.644a.64.64 0 0 0-.572.94h1.14a.64.64 0 0 0 .076-.296");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lqt9uqtub {
  stop-color: var(--svg-color--210f10, #210F10);
}

.lynvfkb0g {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.62 11.947c.334-.588.842-1.053 1.936-1.053c.48 0 .941.133 1.352.465c.338.273.293.623.03.754l-.7.4c-.82-.265-1.729-.301-2.618-.566");
}

.m_3r9vbdq {
  stop-color: var(--svg-color--604c85, #604C85);
  stop-opacity: 0.939;
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfwhtqbpf {
  stop-color: var(--svg-color--33211e, #33211E);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n42kk7pqk {
  stop-color: var(--svg-color--472c31, #472C31);
}

.na3bqccxs {
  stop-color: var(--svg-color--6a44b0, #6A44B0);
}

.nt58yqb6u {
  stop-color: var(--svg-color--4c3b3b, #4C3B3B);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o7mz4obus {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.421 2.85c-1.426-.315-2.707 1.108-2.855 1.636c1.324 4.466 4.677 4.221 7.986 3.853c1.98-.22 2.195.683 2.364 1.12c0-4.954-4.212-5.884-7.459-6.601z");
}

.oc_o5xbok {
  stop-color: var(--svg-color--5d3ca0, #5D3CA0);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.off4cm2_g {
  stop-color: var(--svg-color--210f10, #210F10);
  stop-opacity: 0;
}

.oln0s8bds {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
  stop-opacity: 0;
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pgte_nz8r {
  stroke: var(--svg-color--343434, #343434);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.39 9.864l-2.018-.533");
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxck8xtyd {
  d: path("M15.421 2.85c-1.426-.315-2.707 1.108-2.855 1.636c1.324 4.466 4.677 4.221 7.986 3.853c1.98-.22 2.195.683 2.364 1.12c0-4.954-4.212-5.884-7.459-6.601z");
}

.q59v_vbuo {
  stop-color: var(--svg-color--624e4c, #624E4C);
  stop-opacity: 0;
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qomb6ec0x {
  stop-color: var(--svg-color--8e7cc9, #8E7CC9);
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

.r24llbcyh {
  d: path("m15.7 12.208l-.67 2.142a.68.68 0 0 0 .656.88h.99a.68.68 0 0 0 .656-.88l-.669-2.142c-.143-.474-.813-.474-.963 0");
}

.r7bjwqbfo {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M10.303 14.016a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.ryyyekfgi {
  stop-color: var(--svg-color--53403d, #53403D);
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdcu1vzsq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.85 11.548c.08.107-.088.238-.278.38s-.331.242-.412.135s.01-.309.2-.451s.41-.171.49-.064");
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sq5l9g8_d {
  stop-color: var(--svg-color--533836, #533836);
}

.sqvk0-wgn {
  d: path("M18.933 11.31a1.124 1.124 0 0 1 1.083 1.42h-2.172a1.13 1.13 0 0 1 1.088-1.42");
}

.sqzs4ozft {
  stop-color: var(--svg-color--8071aa, #8071AA);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.ssdt-h3mg {
  d: path("M14.457 12.303c0-.364-.295-.606-.375-.68l-.363.352l.223.455z");
}

.sst8orbli {
  stop-color: var(--svg-color--432e2b, #432E2B);
}

.svnghenix {
  stop-color: var(--svg-color--3e2124, #3E2124);
  stop-opacity: 0;
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.teox85xlx {
  d: path("m25.316 20.431l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.tetwumyrr {
  stop-color: var(--svg-color--5c4761, #5C4761);
}

.thafvacgt {
  stop-color: var(--svg-color--655452, #655452);
}

.tmdmcl4vt {
  stop-color: var(--svg-color--69569a, #69569A);
}

.tndlebqua {
  stop-color: var(--svg-color--6a44b0, #6A44B0);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.uatqp3rks {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
}

.unsg_9i7n {
  d: path("M13.43 11.31a1.124 1.124 0 0 0-1.083 1.42h2.172q.039-.143.04-.295a1.13 1.13 0 0 0-1.129-1.125");
}

.uz7egszvt {
  stroke: var(--svg-color--343434, #343434);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.962 9.864l2.017-.533");
}

.v16-52b6b {
  d: path("m6.936 20.431l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v3mt48bos {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.193 10.968a1.76 1.76 0 0 1 1.707 1.334a.345.345 0 0 1-.337.429h-2.81a.29.29 0 0 1-.287-.342a1.76 1.76 0 0 1 1.727-1.42");
}

.vcr2dvbcg {
  cx: 13.091px;
  cy: 11.791px;
  rx: 0.491px;
  ry: 0.248px;
}

.vqiy7zq_f {
  stop-color: var(--svg-color--53329c, #53329C);
}

.vxxihotpt {
  stop-color: var(--svg-color--9771d7, #9771D7);
}

.vzfpe-bfh {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M9.796 5.12c.713-.754 2.061-.756 2.684-.643l.498 1.626c-.318-.05-.602.063-.84.295c-.565 1.588-2.506 2.463-3.406 2.703c-.187-1.88.137-2.998 1.064-3.98");
}

.wa8_3edge {
  fill: var(--svg-color--101010, #101010);
  d: path("M11.514 10.045a.35.35 0 0 1 .25-.426l2.086-.543a.349.349 0 1 1 .175.676l-2.086.542a.35.35 0 0 1-.425-.25");
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wn5ytjbyn {
  stop-color: var(--svg-color--745b8c, #745B8C);
  stop-opacity: 0;
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.wv7rdbbew {
  fill-rule: evenodd;
  d: path("M25.232 14.44c.268-.549.408-1.16.408-1.798a4.1 4.1 0 0 0-.338-1.645h.006a4 4 0 0 0-.354-.646l-.002-.004a4.1 4.1 0 0 1-.663-2.23v-.013a4.156 4.156 0 0 0-4.156-4.156a.68.68 0 0 1-.574-.293a4.16 4.16 0 0 0-3.378-1.734c-1.39 0-2.626.688-3.378 1.734a.71.71 0 0 1-.574.293l-.107.001a4.156 4.156 0 0 0-4.048 4.155v.012c0 .79-.23 1.568-.663 2.231l-.003.005a4.16 4.16 0 0 0-.277 4.087a.65.65 0 0 1 0 .574a4.1 4.1 0 0 0-.408 1.772a4.05 4.05 0 0 0 4.053 4.053h10.81a4.05 4.05 0 0 0 4.054-4.053a4.1 4.1 0 0 0-.408-1.772a.65.65 0 0 1 0-.574M9.789 11.072h-.016l1.51 2.967c.155 3.53 1.533 0 4.898 0s4.833 3.93 4.988.4l1.43-4.028c-.067-1.568-1.203-1.678-1.43-1.678h-4.056a4.87 4.87 0 0 1-4.017-2.108a.332.332 0 0 0-.582.064l-.103.245a2.9 2.9 0 0 1-1.563 1.58q-.035.016-.065.026c-.297.154-.994.617-1.02 1.812l.013.386z");
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x0-05wb5o {
  stop-color: var(--svg-color--62429a, #62429A);
}

.x0hvtbbrr {
  stop-color: var(--svg-color--785e96, #785E96);
  stop-opacity: 0;
}

.x2-ozkb9d {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.7 12.208l-.67 2.142a.68.68 0 0 0 .656.88h.99a.68.68 0 0 0 .656-.88l-.669-2.142c-.143-.474-.813-.474-.963 0");
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xc2ytjbdf {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.687 12.383l-.861 2.141a.68.68 0 0 0 .656.881h.99a.68.68 0 0 0 .656-.88l-.67-2.142c-.143-.474-.62-.474-.771 0");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xdsxl7bjo {
  d: path("M25.626 29.861h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xjoxl1baz {
  stop-color: var(--svg-color--76679f, #76679F);
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xlrzicczw {
  stop-color: var(--svg-color--3a221f, #3A221F);
}

.xm7oxtb8r {
  stop-color: var(--svg-color--433169, #433169);
}

.xrzqrcaow {
  d: path("M18.85 11.548c.08.107-.088.238-.278.38s-.331.242-.412.135s.01-.309.2-.451s.41-.171.49-.064");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xyqac8gqa {
  stop-color: var(--svg-color--a680df, #A680DF);
  stop-opacity: 0;
}

.y0cud7bhd {
  stop-color: var(--svg-color--705f9f, #705F9F);
}

.y0d2ypbdf {
  stop-color: var(--svg-color--8b64ce, #8B64CE);
}

.ysj89xb8s {
  fill: var(--svg-color--280018, #280018);
  d: path("M16.115 19.312c.791 0 1.433-.689 1.433-1.538s-.642-1.538-1.433-1.538s-1.433.688-1.433 1.538c0 .849.641 1.537 1.433 1.537");
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yzd5z8uce {
  d: path("M22.262 14.69a2.027 2.027 0 1 0 0-4.053a2.027 2.027 0 0 0 0 4.053");
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z2eb7q_dp {
  stop-color: var(--svg-color--655351, #655351);
  stop-opacity: 0;
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zb0hqnb-l {
  stop-color: var(--svg-color--8071aa, #8071AA);
}

.zlawngbku {
  stop-color: var(--svg-color--5d3ca0, #5D3CA0);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
