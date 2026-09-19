<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iKEwaqe)" clip-rule="evenodd" class="o-879tbnr"/><path fill="url(#iwBZAKd)" clip-rule="evenodd" class="o-879tbnr"/><g filter="url(#iCOsUFd)"><path stroke="url(#iB9QeJc)" class="tbw2b8m3a"/></g><path fill="url(#iKzwR4b)" clip-rule="evenodd" class="vwgnxabip"/><path fill="url(#iWi0nhd)" clip-rule="evenodd" class="vwgnxabip"/><g filter="url(#iFETZeD)"><path stroke="url(#ifbfNyb)" class="vk1yb8b6m"/></g><path fill="url(#imnOW5b)" clip-rule="evenodd" class="w5w35bc3u"/><path fill="url(#i6PMT5c)" clip-rule="evenodd" class="w5w35bc3u"/><g filter="url(#i2dGdic)"><path stroke="url(#iqIt0pe)" class="sww5o1btl"/></g><path fill="url(#iJ2t1Ud)" clip-rule="evenodd" class="c49geqb8h"/><path fill="url(#iCXZbzd)" clip-rule="evenodd" class="c49geqb8h"/><path class="l0bl-gz3u"/><path fill="url(#izXJwnd)" class="mywofq-sw"/><path fill="url(#icm0i9c)" class="mywofq-sw"/><path fill="url(#ijH0S1J)" class="mywofq-sw"/><path fill="url(#iYBBKMc)" class="mywofq-sw"/><g filter="url(#iGkr0oc)"><path class="pbbnu-4dr"/><path fill="url(#i48vCkb)" class="bz04fzbzf"/><path fill="url(#iFaRQOb)" class="bz04fzbzf"/><path fill="url(#iw2VSkx)" class="bz04fzbzf"/></g><path fill="url(#ivEqCqb)" clip-rule="evenodd" class="zdh3sob9m"/><path fill="url(#iFKfQcd)" clip-rule="evenodd" class="zdh3sob9m"/><path fill="url(#i7zT1ze)" clip-rule="evenodd" class="zdh3sob9m"/><path fill="url(#iAP3p8c)" clip-rule="evenodd" class="zdh3sob9m"/><path fill="url(#intxV5b)" clip-rule="evenodd" class="um_m80b8n"/><path fill="url(#iMSmuKH)" clip-rule="evenodd" class="um_m80b8n"/><path fill="url(#i8V0uic)" clip-rule="evenodd" class="um_m80b8n"/><path fill="url(#iEpd2te)" clip-rule="evenodd" class="um_m80b8n"/><path fill="url(#ijSKtFe)" clip-rule="evenodd" class="gg-gbnbam"/><path fill="url(#i7QPfNd)" clip-rule="evenodd" class="gg-gbnbam"/><path fill="url(#i0GxKem)" clip-rule="evenodd" class="gg-gbnbam"/><path fill="url(#i7bxgWb)" clip-rule="evenodd" class="gg-gbnbam"/><path fill="url(#iSZeIbe)" clip-rule="evenodd" class="h4lhm5bsu"/><path fill="url(#igywyUd)" clip-rule="evenodd" class="h4lhm5bsu"/><path fill="url(#iNGm8ke)" clip-rule="evenodd" class="h4lhm5bsu"/><path fill="url(#iRj5DEb)" clip-rule="evenodd" class="h4lhm5bsu"/><g filter="url(#iS7tAmc)"><path stroke="url(#iPydh5d)" class="rjrjfgj9v"/></g><g filter="url(#iHVo72Y)"><path class="zzalqjn8m"/></g><path fill="url(#ip0mYpc)" class="pqc_l8aas"/><path fill="url(#ieKdimb)" class="pqc_l8aas"/><path fill="url(#i3ySdkd)" class="nqolesb_f"/><path fill="url(#ihGWTvi)" class="nqolesb_f"/><path fill="url(#izrvLzb)" class="nqolesb_f"/><g filter="url(#iTk3Wzc)"><path fill="url(#iVudtdc)" class="omp467bql"/><path fill="url(#iBenn6s)" class="omp467bql"/><path fill="url(#iyjvHEc)" class="omp467bql"/><path fill="url(#iunXkcc)" class="omp467bql"/><path fill="url(#iAUT9dc)" class="omp467bql"/></g><path fill="url(#i2s3Xgb)" class="xrwg8acec"/><path fill="url(#iIMfxFb)" class="xrwg8acec"/><g filter="url(#iaEbmyz)"><path class="efwmubb6g"/></g><g filter="url(#i6IdBue)"><path class="x1al7bb2v"/></g><g filter="url(#iGURCZc)"><path stroke="url(#ieqwIvI)" class="k6m70ilqg"/></g><g filter="url(#i6ZKLsd)"><path fill="url(#i8JJfZS)" class="lztfnh1yp"/></g><g filter="url(#iIqSIIe)"><circle fill="url(#inNOryB)" transform="rotate(-4.432 11.06 13.296)" class="db45cg36u"/></g><circle fill="url(#idMPxzb)" transform="rotate(-4.432 11.06 13.296)" class="db45cg36u"/><g filter="url(#ihsKNRd)"><circle fill="url(#ilVXrDd)" transform="rotate(-4.432 11.06 13.296)" class="we0-hlz5i"/></g><g filter="url(#irlscxc)"><circle fill="url(#ibXxcme)" transform="rotate(-4.432 19.912 12.61)" class="fn-50ib6u"/><circle fill="url(#iXvIzdd)" transform="rotate(-4.432 19.912 12.61)" class="fn-50ib6u"/></g><g filter="url(#iqfuXEb)"><circle transform="rotate(-4.432 19.912 12.61)" class="hommdgb3f"/><circle fill="url(#iBeNuXb)" transform="rotate(-4.432 19.912 12.61)" class="httl54v5m"/><circle fill="url(#iip90Dc)" transform="rotate(-4.432 19.912 12.61)" class="httl54v5m"/></g><g filter="url(#iRptfnc)"><path fill="url(#irtCvBF)" class="tq5y8jb5o"/><path fill="url(#iiY2m5s)" class="tq5y8jb5o"/><path fill="url(#iQvN1Dd)" class="tq5y8jb5o"/></g><path fill="url(#itsPqab)" class="i5fgn3ayo"/><path fill="url(#i3CfW3c)" class="i5fgn3ayo"/><path fill="url(#iCkgite)" class="i5fgn3ayo"/><g filter="url(#iao5etb)"><path fill="url(#id2ltid)" class="vt--vh64k"/></g><g filter="url(#iTzR02b)"><path class="v49kkfisr"/><path fill="url(#it05Kwb)" class="c5odemc6w"/><path fill="url(#iHjK3Me)" class="c5odemc6w"/><path fill="url(#i1pLxUC)" class="c5odemc6w"/><path fill="url(#iyCifkq)" class="c5odemc6w"/></g><g filter="url(#i5PtIIc)"><path class="ex4by-y-h"/></g><g filter="url(#ilFuEYc)"><path class="miiz7gbnj"/><path fill="url(#ivUepxd)" class="jikz8laue"/><path fill="url(#igdcVLb)" class="jikz8laue"/><path fill="url(#iTAwpqc)" class="jikz8laue"/><path fill="url(#iHYbrol)" class="jikz8laue"/></g><path fill="url(#izQLwFf)" class="jikz8laue"/><g filter="url(#iV4sTcZ)"><path class="by-m8fb3v"/><path fill="url(#icooveD)" class="bxqiarbwl"/></g><g filter="url(#i0UfWsb)"><path class="vjgm3lrsh"/><path fill="url(#iJX7yet)" class="oevwuybhv"/></g><path class="uffhkkadj"/><path fill="url(#izQWfwb)" class="n1td91b2u"/><path class="xbijjpcsb"/><g filter="url(#iB5AKsd)"><path class="h0n1a7h5d"/><path fill="url(#i04Ixte)" class="sca1f_z_y"/></g><g filter="url(#iQzJFAe)"><path fill="url(#iaO35Le)" class="bx26x55_k"/></g><path class="kc21rccfj"/><path fill="url(#iAsjF8X)" class="xxwl_8dkv"/><path class="s3c7c_8fj"/><g filter="url(#iwq2C8n)"><path fill="url(#ilrtqud)" class="erd1nxbhq"/></g><g filter="url(#iJFyyrc)"><ellipse transform="rotate(-32.346 13.137 12.407)" class="bmwov9vvq"/><ellipse fill="url(#iVtkUpK)" transform="rotate(-32.346 13.137 12.407)" class="s2x4eib1h"/></g><g filter="url(#ix0zJOb)"><path stroke="url(#iRPQ5lI)" class="t4l3x1b0r"/></g><g filter="url(#iBGqcHc)"><path stroke="url(#iMSEwae)" class="lwb196lua"/></g><g filter="url(#iIm3JFb)"><path stroke="url(#iKyS7xe)" class="s2173f0vf"/></g><g filter="url(#iiYEtoc)"><ellipse stroke="url(#ij586zc)" class="y3kcud5xy"/></g><ellipse class="qg12wplhp"/><defs><radialGradient id="iwBZAKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71267 1.83244 -2.48647 -.96704 5.308 12.265)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="d348e2bmq"/><stop offset="1" class="h0gi5sr7l"/></radialGradient><radialGradient id="iWi0nhd" cx="0" cy="0" r="1" gradientTransform="matrix(-.63638 2.0037 -2.32192 -.73745 4.035 12.646)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="d348e2bmq"/><stop offset="1" class="h0gi5sr7l"/></radialGradient><radialGradient id="i6PMT5c" cx="0" cy="0" r="1" gradientTransform="rotate(112.256 -2.405 8.236)scale(1.93501 2.72441)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="d348e2bmq"/><stop offset="1" class="h0gi5sr7l"/></radialGradient><radialGradient id="iCXZbzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 1.57812 -2.42466 -1.12832 4.633 14.532)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="d348e2bmq"/><stop offset="1" class="h0gi5sr7l"/></radialGradient><radialGradient id="icm0i9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.52138 .86916 -1.0215 -.61276 6.94 11.359)" gradientUnits="userSpaceOnUse"><stop class="lhs441rxk"/><stop offset="1" class="kvh590ikm"/></radialGradient><radialGradient id="iYBBKMc" cx="0" cy="0" r="1" gradientTransform="rotate(50.771 -10.196 11.995)scale(2.10408 .76124)" gradientUnits="userSpaceOnUse"><stop class="fm-ag3l1v"/><stop offset="1" class="jqoxmxa7u"/></radialGradient><radialGradient id="iFaRQOb" cx="0" cy="0" r="1" gradientTransform="matrix(.85157 -.55469 .26705 .40998 26.155 11.609)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="vpgp1b8tt"/><stop offset="1" class="uudqsyb7t"/></radialGradient><radialGradient id="iw2VSkx" cx="0" cy="0" r="1" gradientTransform="rotate(-141.546 15.343 1.888)scale(.67838 .87633)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="teu5d39go"/><stop offset="1" class="ieaa_kb0h"/></radialGradient><radialGradient id="iFKfQcd" cx="0" cy="0" r="1" gradientTransform="matrix(2.25998 .5537 -1.30788 5.3383 26.452 12.328)" gradientUnits="userSpaceOnUse"><stop offset=".575" class="iky79-blm"/><stop offset="1" class="qm-9wjixk"/></radialGradient><radialGradient id="i7zT1ze" cx="0" cy="0" r="1" gradientTransform="matrix(.83172 1.25496 -1.54431 1.02349 26.938 12.452)" gradientUnits="userSpaceOnUse"><stop class="rqxwi30ib"/><stop offset="1" class="lslkpqbsz"/></radialGradient><radialGradient id="iAP3p8c" cx="0" cy="0" r="1" gradientTransform="matrix(.56104 -.65315 .38675 .3322 28.601 11.957)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="qrv_azbvd"/><stop offset="1" class="u_7m_6tiu"/></radialGradient><radialGradient id="iMSmuKH" cx="0" cy="0" r="1" gradientTransform="matrix(.97003 2.19293 -9.2033 4.07104 28.042 12.099)" gradientUnits="userSpaceOnUse"><stop offset=".575" class="iky79-blm"/><stop offset="1" class="qm-9wjixk"/></radialGradient><radialGradient id="i8V0uic" cx="0" cy="0" r="1" gradientTransform="matrix(1.17519 1.75148 -1.61774 1.08545 27.83 12.803)" gradientUnits="userSpaceOnUse"><stop class="rqxwi30ib"/><stop offset="1" class="lslkpqbsz"/></radialGradient><radialGradient id="iEpd2te" cx="0" cy="0" r="1" gradientTransform="matrix(.5763 -.5424 .31085 .33028 29.48 12.102)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="qrv_azbvd"/><stop offset="1" class="u_7m_6tiu"/></radialGradient><radialGradient id="i7QPfNd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0562 1.95821 -9.2814 5.0061 27.9 13.094)" gradientUnits="userSpaceOnUse"><stop offset=".575" class="iky79-blm"/><stop offset="1" class="qm-9wjixk"/></radialGradient><radialGradient id="i0GxKem" cx="0" cy="0" r="1" gradientTransform="rotate(60.712 2.396 30.728)scale(1.58787 1.64819)" gradientUnits="userSpaceOnUse"><stop class="rqxwi30ib"/><stop offset="1" class="lslkpqbsz"/></radialGradient><radialGradient id="i7bxgWb" cx="0" cy="0" r="1" gradientTransform="matrix(.57695 -.63832 .3804 .34382 29.656 13.28)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="qrv_azbvd"/><stop offset="1" class="u_7m_6tiu"/></radialGradient><radialGradient id="igywyUd" cx="0" cy="0" r="1" gradientTransform="rotate(58.478 1.195 31.687)scale(2.02431 10.2344)" gradientUnits="userSpaceOnUse"><stop offset=".575" class="iky79-blm"/><stop offset="1" class="qm-9wjixk"/></radialGradient><radialGradient id="iNGm8ke" cx="0" cy="0" r="1" gradientTransform="rotate(57.47 .581 32.545)scale(1.44748 1.59652)" gradientUnits="userSpaceOnUse"><stop class="rqxwi30ib"/><stop offset="1" class="lslkpqbsz"/></radialGradient><radialGradient id="iRj5DEb" cx="0" cy="0" r="1" gradientTransform="matrix(.57812 -.5625 .3368 .34616 29.343 14.267)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="qrv_azbvd"/><stop offset="1" class="u_7m_6tiu"/></radialGradient><radialGradient id="ip0mYpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94297 -2.39063 0 26.026 16.405)" gradientUnits="userSpaceOnUse"><stop class="gqn4jccjs"/><stop offset="1" class="wjksmgbzx"/></radialGradient><radialGradient id="ihGWTvi" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.14902 -.68994 0 7.385 16.637)" gradientUnits="userSpaceOnUse"><stop class="ne51g8a0v"/><stop offset="1" class="opxc931wt"/></radialGradient><radialGradient id="iVudtdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4411 10.6867 0 19.744 29.39)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g6k-1hpjs"/><stop offset="1" class="msi6qbbpq"/></radialGradient><radialGradient id="iBenn6s" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01666 3.53393 -1.57189 -1.3418 9.635 20.004)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="k20ytgb7v"/><stop offset="1" class="mtrk0zxts"/><stop offset="1" class="jbumt9bvj"/></radialGradient><radialGradient id="iyjvHEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.46944 -4.08022 0 26.837 16.952)" gradientUnits="userSpaceOnUse"><stop class="f51--cb4u"/><stop offset="1" class="sp_au2bah"/></radialGradient><radialGradient id="iunXkcc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2344 3.40893 -.45438 -.29783 9.542 20.13)" gradientUnits="userSpaceOnUse"><stop class="o18y7cctk"/><stop offset="1" class="p8zx0emkh"/></radialGradient><radialGradient id="iAUT9dc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.68753 3.4062 -1.542 -2.57478 14.245 17.88)" gradientUnits="userSpaceOnUse"><stop offset=".066" class="ok0pekb3m"/><stop offset="1" class="l6xrk1bwj"/></radialGradient><radialGradient id="i2s3Xgb" cx="0" cy="0" r="1" gradientTransform="matrix(2.0625 2.17783 -3.3043 3.12931 15.416 18.115)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="id9ofabvx"/><stop offset="1" class="mb-6y2bmd"/></radialGradient><radialGradient id="inNOryB" cx="0" cy="0" r="1" gradientTransform="matrix(1.63771 0 0 2.86601 9.502 13.296)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="idMPxzb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 9.398 4.547)scale(1.54614)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iXvIzdd" cx="0" cy="0" r="1" gradientTransform="matrix(.77151 -.56178 .6412 .88058 20.259 12.363)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iBeNuXb" cx="0" cy="0" r="1" gradientTransform="matrix(.76643 -1.40969 .8251 .4486 19.873 13.377)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iip90Dc" cx="0" cy="0" r="1" gradientTransform="matrix(.24198 .23952 -.30878 .31194 19.912 12.61)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iiY2m5s" cx="0" cy="0" r="1" gradientTransform="matrix(-.09426 -1.21617 1.49682 -.11602 17.569 11.602)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iQvN1Dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0991 -1.27853 1.58998 -.12324 13.338 12.055)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iCkgite" cx="0" cy="0" r="1" gradientTransform="matrix(.60066 7.7492 -9.60463 .74448 15.248 11.536)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="dcym8repk"/><stop offset=".884" class="fkee40m0y"/><stop offset="1" class="an_-aznlj"/></radialGradient><radialGradient id="it05Kwb" cx="0" cy="0" r="1" gradientTransform="matrix(.5291 -2.80853 1.04149 .1962 19.224 8.82)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iHjK3Me" cx="0" cy="0" r="1" gradientTransform="matrix(3.5842 .05165 -.02777 1.9272 17.57 7.3)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="i1pLxUC" cx="0" cy="0" r="1" gradientTransform="matrix(.1211 1.56238 -2.4197 .18756 14.857 4.95)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iyCifkq" cx="0" cy="0" r="1" gradientTransform="matrix(2.6977 -2.31768 3.63104 4.2264 9.349 11.76)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iHYbrol" cx="0" cy="0" r="1" gradientTransform="rotate(85.568 .156 15.801)scale(.18375 .59038)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="icooveD" cx="0" cy="0" r="1" gradientTransform="matrix(.05344 -.56882 1.68282 .1581 17.6 10.838)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iJX7yet" cx="0" cy="0" r="1" gradientTransform="matrix(.05344 -.56882 1.6829 .15812 12.81 11.21)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="izQWfwb" cx="0" cy="0" r="1" gradientTransform="rotate(85.568 2.157 15.512)scale(.75698 1.20406)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i04Ixte" cx="0" cy="0" r="1" gradientTransform="matrix(-.23728 -.26128 .35973 -.32669 17.25 12.256)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iAsjF8X" cx="0" cy="0" r="1" gradientTransform="matrix(.0585 .75476 -1.20052 .09306 13.396 12.477)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVtkUpK" cx="0" cy="0" r="1" gradientTransform="matrix(-.00722 -.461 .55413 -.00868 13.123 12.701)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iKEwaqe" x1="3.642" x2="5.846" y1="12.252" y2="12.998" gradientUnits="userSpaceOnUse"><stop class="boexhflwz"/><stop offset="1" class="bkpp_-h3a"/></linearGradient><linearGradient id="iB9QeJc" x1="4.146" x2="6.302" y1="12.048" y2="14.197" gradientUnits="userSpaceOnUse"><stop class="aromb5itn"/><stop offset="1" class="f6ufzvbyl"/></linearGradient><linearGradient id="iKzwR4b" x1="2.547" x2="4.585" y1="12.632" y2="13.195" gradientUnits="userSpaceOnUse"><stop class="boexhflwz"/><stop offset="1" class="bkpp_-h3a"/></linearGradient><linearGradient id="ifbfNyb" x1="3.078" x2="5.489" y1="12.317" y2="14.531" gradientUnits="userSpaceOnUse"><stop class="aromb5itn"/><stop offset="1" class="f6ufzvbyl"/></linearGradient><linearGradient id="imnOW5b" x1="2.594" x2="4.835" y1="13.569" y2="14.367" gradientUnits="userSpaceOnUse"><stop class="boexhflwz"/><stop offset="1" class="bkpp_-h3a"/></linearGradient><linearGradient id="iqIt0pe" x1="3.003" x2="5.594" y1="13.309" y2="15.308" gradientUnits="userSpaceOnUse"><stop class="aromb5itn"/><stop offset="1" class="f6ufzvbyl"/></linearGradient><linearGradient id="iJ2t1Ud" x1="2.916" x2="5.091" y1="14.522" y2="15.402" gradientUnits="userSpaceOnUse"><stop class="boexhflwz"/><stop offset="1" class="bkpp_-h3a"/></linearGradient><linearGradient id="izXJwnd" x1="8.638" x2="7.797" y1="15.592" y2="15.592" gradientUnits="userSpaceOnUse"><stop offset=".005" class="ekb7ro69z"/><stop offset="1" class="opwa50pmp"/></linearGradient><linearGradient id="ijH0S1J" x1="5.734" x2="5.734" y1="17.098" y2="15.735" gradientUnits="userSpaceOnUse"><stop class="dyeknzb3w"/><stop offset="1" class="q4wygiatd"/></linearGradient><linearGradient id="i48vCkb" x1="23.678" x2="24.476" y1="15.491" y2="15.491" gradientUnits="userSpaceOnUse"><stop class="frlo14w5r"/><stop offset="1" class="sppcpbbqx"/></linearGradient><linearGradient id="ivEqCqb" x1="28.274" x2="25.581" y1="13.749" y2="13.708" gradientUnits="userSpaceOnUse"><stop class="gg02bmwvi"/><stop offset="1" class="fh9qxk96g"/></linearGradient><linearGradient id="intxV5b" x1="29.346" x2="26.803" y1="14.271" y2="14.238" gradientUnits="userSpaceOnUse"><stop class="gg02bmwvi"/><stop offset="1" class="fh9qxk96g"/></linearGradient><linearGradient id="ijSKtFe" x1="29.32" x2="26.55" y1="15.032" y2="14.988" gradientUnits="userSpaceOnUse"><stop class="gg02bmwvi"/><stop offset="1" class="fh9qxk96g"/></linearGradient><linearGradient id="iSZeIbe" x1="29.006" x2="26.231" y1="15.81" y2="15.76" gradientUnits="userSpaceOnUse"><stop class="gg02bmwvi"/><stop offset="1" class="fh9qxk96g"/></linearGradient><linearGradient id="iPydh5d" x1="3.291" x2="6.099" y1="14.336" y2="16.017" gradientUnits="userSpaceOnUse"><stop class="aromb5itn"/><stop offset="1" class="f6ufzvbyl"/></linearGradient><linearGradient id="ieKdimb" x1="23.485" x2="23.971" y1="17.387" y2="17.379" gradientUnits="userSpaceOnUse"><stop class="g15pupb2m"/><stop offset="1" class="dqcsylboi"/></linearGradient><linearGradient id="i3ySdkd" x1="6.854" x2="9.541" y1="17.095" y2="17.095" gradientUnits="userSpaceOnUse"><stop class="gy5j7812b"/><stop offset="1" class="vw_f_cbup"/></linearGradient><linearGradient id="izrvLzb" x1="6.695" x2="6.695" y1="16.405" y2="16.668" gradientUnits="userSpaceOnUse"><stop class="z96fdub7f"/><stop offset="1" class="j3txnddmt"/></linearGradient><linearGradient id="iIMfxFb" x1="12.948" x2="15.51" y1="19.793" y2="19.793" gradientUnits="userSpaceOnUse"><stop class="f0wda1gby"/><stop offset="1" class="xjqh_ibco"/></linearGradient><linearGradient id="ieqwIvI" x1="9.682" x2="12.682" y1="26.124" y2="20.468" gradientUnits="userSpaceOnUse"><stop class="zuuvnac4f"/><stop offset="1" class="bb3cu5wqs"/></linearGradient><linearGradient id="i8JJfZS" x1="25.272" x2="21.032" y1="26.209" y2="21.495" gradientUnits="userSpaceOnUse"><stop class="z108ppbpv"/><stop offset="1" class="sv_dn8bha"/></linearGradient><linearGradient id="ilVXrDd" x1="11.06" x2="10.462" y1="13.556" y2="13.556" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="ibXxcme" x1="20.925" x2="20.161" y1="11.591" y2="13.958" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="irtCvBF" x1="19.261" x2="12.237" y1="13.025" y2="14.635" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="itsPqab" x1="10.68" x2="12.425" y1="16.214" y2="16.016" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="i3CfW3c" x1="20.218" x2="19.176" y1="14.687" y2="14.677" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="id2ltid" x1="14.796" x2="22.163" y1="10.577" y2="7.277" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="ivUepxd" x1="14.749" x2="15.622" y1="13.992" y2="13.924" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="igdcVLb" x1="16.45" x2="15.494" y1="14.162" y2="14.222" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iTAwpqc" x1="15.811" x2="15.77" y1="14.906" y2="14.373" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="izQLwFf" x1="15.75" x2="15.738" y1="14.95" y2="14.794" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="iaO35Le" x1="18.183" x2="17.905" y1="12.156" y2="12.358" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilrtqud" x1="14.092" x2="13.814" y1="12.473" y2="12.676" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRPQ5lI" x1="18.044" x2="17.591" y1="10.164" y2="9.395" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iMSEwae" x1="13.099" x2="11.956" y1="10.428" y2="10.05" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iKyS7xe" x1="10.786" x2="10.941" y1="8.721" y2="10.728" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="ij586zc" x1="15.405" x2="15.722" y1="17.018" y2="15.883" gradientUnits="userSpaceOnUse"><stop class="a0m4s3xwx"/><stop offset="1" class="d73fcz0io"/></linearGradient><filter id="iCOsUFd" width="3.052" height="2.539" x="3.445" y="11.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".15"/></filter><filter id="iFETZeD" width="3.127" height="2.723" x="2.367" y="11.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".15"/></filter><filter id="i2dGdic" width="3.267" height="2.534" x="2.297" y="12.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".15"/></filter><filter id="iGkr0oc" width="3.408" height="5.156" x="23.678" y="11.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.427451 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4190"/></filter><filter id="iS7tAmc" width="3.431" height="2.258" x="2.595" y="13.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".15"/></filter><filter id="iHVo72Y" width="2.847" height=".977" x="25.146" y="15.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".15"/></filter><filter id="iTk3Wzc" width="23.107" height="13.423" x="4.447" y="16.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.396078 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4190"/></filter><filter id="iaEbmyz" width="8.199" height="8.945" x="4.932" y="16.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".75"/></filter><filter id="i6IdBue" width="7.102" height="8.493" x="20.605" y="16.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".625"/></filter><filter id="iGURCZc" width="3.956" height="6.956" x="9.032" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".25"/></filter><filter id="i6ZKLsd" width="5.986" height="5.519" x="20.232" y="21.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".4"/></filter><filter id="iIqSIIe" width="3.316" height="3.116" x="9.502" y="11.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4190"/></filter><filter id="ihsKNRd" width="2.857" height="2.857" x="9.631" y="11.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".25"/></filter><filter id="irlscxc" width="3.366" height="3.366" x="18.354" y="10.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4190"/></filter><filter id="iqfuXEb" width="2.857" height="2.857" x="18.483" y="11.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".25"/></filter><filter id="iRptfnc" width="9.698" height="11.524" x="10.528" y="7.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4190"/></filter><filter id="iao5etb" width="7.999" height="7.054" x="13.373" y="5.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation="1"/></filter><filter id="iTzR02b" width="11.732" height="8.336" x="9.289" y="4.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4190"/></filter><filter id="i5PtIIc" width="3.14" height="4.035" x="13.81" y="11.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".375"/></filter><filter id="ilFuEYc" width="2.249" height="3.026" x="14.467" y="12.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".125"/></filter><filter id="iV4sTcZ" width="2.82" height="1.687" x="16.383" y="9.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4190"/></filter><filter id="i0UfWsb" width="2.766" height="1.873" x="11.62" y="9.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4190"/></filter><filter id="iB5AKsd" width=".726" height=".688" x="16.769" y="11.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".05"/></filter><filter id="iQzJFAe" width=".87" height=".888" x="17.549" y="11.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".1"/></filter><filter id="iwq2C8n" width=".964" height="1.004" x="13.411" y="12.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".1"/></filter><filter id="iJFyyrc" width=".845" height=".698" x="12.714" y="12.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".05"/></filter><filter id="ix0zJOb" width="3.25" height="1.806" x="16.066" y="9.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".25"/></filter><filter id="iBGqcHc" width="3.26" height="2.069" x="11.247" y="9.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".25"/></filter><filter id="iIm3JFb" width=".946" height="2.182" x="10.408" y="8.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".125"/></filter><filter id="iiYEtoc" width="1.869" height="1.911" x="14.835" y="15.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4190" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-shrugging-medium" /></template>
<style>
.a0m4s3xwx {
  stop-color: var(--svg-color--af877e, #AF877E);
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.an_-aznlj {
  stop-color: var(--svg-color--7c5267, #7C5267);
}

.aromb5itn {
  stop-color: var(--svg-color--ad887b, #AD887B);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bb3cu5wqs {
  stop-color: var(--svg-color--1a7ad4, #1A7AD4);
  stop-opacity: 0;
}

.bkpp_-h3a {
  stop-color: var(--svg-color--8b6e5a, #8B6E5A);
}

.bmwov9vvq {
  cx: 13.137px;
  cy: 12.407px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.364px;
  ry: 0.184px;
}

.boexhflwz {
  stop-color: var(--svg-color--997761, #997761);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bx26x55_k {
  d: path("M18.219 12.382a.8.8 0 0 0-.249-.414l-.221.284l.126.204z");
}

.bxqiarbwl {
  d: path("m18.742 10.155l-.003-.002l-.004-.003l-.012-.008a1 1 0 0 0-.152-.088a2.4 2.4 0 0 0-.405-.166a2.64 2.64 0 0 0-1.4-.04a.498.498 0 1 0 .23.97c.366-.088.667-.043.876.021a1.4 1.4 0 0 1 .29.127l.009.005a.498.498 0 0 0 .571-.815");
}

.by-m8fb3v {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m18.742 10.155l-.003-.002l-.004-.003l-.012-.008a1 1 0 0 0-.152-.088a2.4 2.4 0 0 0-.405-.166a2.64 2.64 0 0 0-1.4-.04a.498.498 0 1 0 .23.97c.366-.088.667-.043.876.021a1.4 1.4 0 0 1 .29.127l.009.005a.498.498 0 0 0 .571-.815");
}

.bz04fzbzf {
  d: path("M26.104 11.514a.75.75 0 0 0-1.052.138l-.804 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.258v-2.698h-1.627q.054-.108.128-.204l.804-1.047a.75.75 0 0 0-.137-1.052");
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c49geqb8h {
  fill-rule: evenodd;
  d: path("M2.666 14.076a.7.7 0 0 1 .98.142c.18.242.653.84 1.872.84a.7.7 0 1 1 0 1.4c-1.827 0-2.667-.964-2.994-1.402a.7.7 0 0 1 .142-.98");
}

.c5odemc6w {
  d: path("m19.494 6.579l.415.167c.726.294 1.186 1.057 1.102 1.912l-.33 2.871c-.026.296-.204.508-.494.537l-.016.002s-.016-.848-.004-1.348c.009-.406-.07-.523-.469-.862a1.17 1.17 0 0 1-.41-.767l-.062-.794a.54.54 0 0 0-.438-.465c-.61-.103-1.877-.254-3.674-.115c-1.797.14-3.025.484-3.613.68a.485.485 0 0 0-.36.527l.061.794c.023.297-.054.603-.288.82l-.138.161c-.188.165-.265.47-.246.718c.093.542.204 1.332.204 1.332l-.046.002a.59.59 0 0 1-.591-.451l-.769-2.786c-.16-.787.177-1.612.849-2.013l.383-.23c.239-.168.473-.386.707-.604l.825-1.012a1.83 1.83 0 0 1 2.023-.456c.51.11 1.06.067 1.547-.12c.73-.306 1.594-.174 2.235.326l.806.686c.22.233.48.362.791.488");
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d348e2bmq {
  stop-color: var(--svg-color--92576f, #92576F);
  stop-opacity: 0;
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d73fcz0io {
  stop-color: var(--svg-color--af877e, #AF877E);
  stop-opacity: 0;
}

.db45cg36u {
  cx: 11.06px;
  cy: 13.296px;
  r: 1.558px;
}

.dcym8repk {
  stop-color: var(--svg-color--9b7168, #9B7168);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dqcsylboi {
  stop-color: var(--svg-color--257fbf, #257FBF);
  stop-opacity: 0;
}

.dyeknzb3w {
  stop-color: var(--svg-color--753d27, #753D27);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.efwmubb6g {
  stroke: var(--svg-color--40a1ff, #40A1FF);
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.182 18.973v3.442a1 1 0 0 0 1.567.824l1.84-1.266");
}

.ekb7ro69z {
  stop-color: var(--svg-color--896e61, #896E61);
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.erd1nxbhq {
  d: path("M14.175 12.707c-.02-.268-.253-.43-.316-.48l-.248.28l.191.324z");
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.ex4by-y-h {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.213 12.86l-.641 1.64c-.07.333.183.64.505.616l.685-.053c.322-.025.524-.373.404-.686l-.586-1.546c-.127-.342-.29-.33-.367.029");
}

.f0wda1gby {
  stop-color: var(--svg-color--8e6f6b, #8E6F6B);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f51--cb4u {
  stop-color: var(--svg-color--43beff, #43BEFF);
}

.f6ufzvbyl {
  stop-color: var(--svg-color--ad887b, #AD887B);
  stop-opacity: 0;
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fh9qxk96g {
  stop-color: var(--svg-color--b08a6f, #B08A6F);
}

.fkee40m0y {
  stop-color: var(--svg-color--8f5d78, #8F5D78);
}

.fm-ag3l1v {
  stop-color: var(--svg-color--875d53, #875D53);
}

.fn-50ib6u {
  cx: 19.912px;
  cy: 12.61px;
  r: 1.558px;
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.frlo14w5r {
  stop-color: var(--svg-color--8a6355, #8A6355);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g15pupb2m {
  stop-color: var(--svg-color--257fbf, #257FBF);
}

.g6k-1hpjs {
  stop-color: var(--svg-color--3cb2ff, #3CB2FF);
}

.gg-gbnbam {
  fill-rule: evenodd;
  d: path("M29.656 13.045a.7.7 0 0 0-.98.142l-.086.118c-.302.42-.764 1.062-1.78 1.062a.7.7 0 1 0 0 1.4c1.776 0 2.638-1.24 2.925-1.654q.037-.054.063-.088a.7.7 0 0 0-.142-.98");
}

.gg02bmwvi {
  stop-color: var(--svg-color--bb977a, #BB977A);
}

.gqn4jccjs {
  stop-color: var(--svg-color--47adf9, #47ADF9);
}

.gy5j7812b {
  stop-color: var(--svg-color--4a9ee0, #4A9EE0);
}

.h0gi5sr7l {
  stop-color: var(--svg-color--92576f, #92576F);
}

.h0n1a7h5d {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.376 11.899c.065.074-.05.18-.183.296s-.231.198-.297.123c-.065-.074-.01-.228.122-.344s.293-.15.358-.075");
}

.h4lhm5bsu {
  fill-rule: evenodd;
  d: path("M29.343 14.076a.7.7 0 0 0-.98.142c-.18.242-.653.84-1.872.84a.7.7 0 1 0 0 1.4c1.827 0 2.667-.964 2.994-1.402a.7.7 0 0 0-.142-.98");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hommdgb3f {
  cx: 19.912px;
  cy: 12.61px;
  r: 0.929px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.httl54v5m {
  cx: 19.912px;
  cy: 12.61px;
  r: 0.929px;
}

.i5fgn3ayo {
  d: path("M10.53 11.417c-.019-.248.058-.553.246-.718l.138-.16c.234-.218.311-.523.288-.821l-.062-.794a.485.485 0 0 1 .361-.527c.588-.196 1.816-.54 3.613-.68c1.797-.139 3.063.012 3.674.115a.54.54 0 0 1 .438.465l.061.794c.023.298.196.584.411.767c.493.291.478.473.469.862c-.012.5.004 1.348.004 1.348l.017-.002l.038 3.703c-.022 1.658-1.227 2.906-2.77 3.025l-2.988.232c-1.593.123-2.927-.928-3.204-2.563c-.26-1.68-.448-3.37-.734-5.046");
}

.id9ofabvx {
  stop-color: var(--svg-color--925e6d, #925E6D);
}

.ieaa_kb0h {
  stop-color: var(--svg-color--967161, #967161);
  stop-opacity: 0;
}

.iky79-blm {
  stop-color: var(--svg-color--9f6274, #9F6274);
  stop-opacity: 0;
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j3txnddmt {
  stop-color: var(--svg-color--3481c0, #3481C0);
  stop-opacity: 0;
}

.jbumt9bvj {
  stop-color: var(--svg-color--1f74b9, #1F74B9);
  stop-opacity: 0;
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jikz8laue {
  d: path("m15.102 12.716l-.372 1.62a.503.503 0 0 0 .534.612l.732-.056a.505.505 0 0 0 .434-.688l-.617-1.543c-.133-.342-.628-.304-.712.055");
}

.jqoxmxa7u {
  stop-color: var(--svg-color--875d53, #875D53);
  stop-opacity: 0;
}

.k20ytgb7v {
  stop-color: var(--svg-color--1f74b9, #1F74B9);
}

.k6m70ilqg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.682 25.655c.177-1.146.956-3.881 2.656-5.656");
}

.kc21rccfj {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.148 11.795a1.3 1.3 0 0 0-1.184 1.083a.256.256 0 0 0 .273.297l2.076-.16a.215.215 0 0 0 .192-.27a1.31 1.31 0 0 0-1.357-.95");
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.kvh590ikm {
  stop-color: var(--svg-color--9a7b65, #9A7B65);
  stop-opacity: 0;
}

.l0bl-gz3u {
  fill: var(--svg-color--8b6e5a, #8B6E5A);
  d: path("M5.896 11.514a.75.75 0 0 1 1.052.138l.804 1.047c.37.48.57 1.07.57 1.676v2.14H5.064v-2.698h1.627a1.3 1.3 0 0 0-.128-.204l-.805-1.047a.75.75 0 0 1 .138-1.052");
}

.l6xrk1bwj {
  stop-color: var(--svg-color--28699c, #28699C);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhs441rxk {
  stop-color: var(--svg-color--9a7b65, #9A7B65);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lslkpqbsz {
  stop-color: var(--svg-color--8e6854, #8E6854);
  stop-opacity: 0;
}

.lwb196lua {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.997 11.028c.284-.293.926-.628 1.76-.56");
}

.lztfnh1yp {
  d: path("m21.032 22.133l1.543 3.67c1.206.44 2.533.203 2.844 0z");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.mb-6y2bmd {
  stop-color: var(--svg-color--bc8f80, #BC8F80);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.miiz7gbnj {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.102 12.716l-.372 1.62a.503.503 0 0 0 .534.612l.732-.056a.505.505 0 0 0 .434-.688l-.617-1.543c-.133-.342-.628-.304-.712.055");
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.msi6qbbpq {
  stop-color: var(--svg-color--2d92df, #2D92DF);
}

.mtrk0zxts {
  stop-color: var(--svg-color--51aaff, #51AAFF);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.mywofq-sw {
  d: path("M5.896 11.514a.75.75 0 0 1 1.052.138l.804 1.047c.37.48.57 1.07.57 1.676v2.14H5.064v-2.698h1.627a1.3 1.3 0 0 0-.128-.204l-.805-1.047a.75.75 0 0 1 .138-1.052");
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n1td91b2u {
  d: path("M17.423 11.718a.833.833 0 0 1 .882.987l-1.604.124a.836.836 0 0 1 .722-1.111");
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.ne51g8a0v {
  stop-color: var(--svg-color--3990dd, #3990DD);
}

.nqolesb_f {
  d: path("M4.98 16.655a.25.25 0 0 1 .25-.25h2.93a.25.25 0 0 1 .25.25v1.13H4.98z");
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o-879tbnr {
  fill-rule: evenodd;
  d: path("M3.416 11.707a.7.7 0 0 1 .977.157a2 2 0 0 1 .12.192l.002.002q.048.085.105.174c.076.12.17.25.293.37c.233.228.608.468 1.267.5a.7.7 0 1 1-.068 1.398c-1.024-.05-1.718-.447-2.179-.898a3.5 3.5 0 0 1-.495-.618a6 6 0 0 1-.13-.216l-.004-.007l-.044-.075l-.001-.002a.7.7 0 0 1 .157-.977");
}

.o18y7cctk {
  stop-color: var(--svg-color--389bfa, #389BFA);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oevwuybhv {
  d: path("m11.77 10.695l.002-.002l.004-.003l.01-.01a1.4 1.4 0 0 1 .137-.111c.088-.066.214-.148.375-.227a2.64 2.64 0 0 1 1.378-.255a.498.498 0 0 1-.079.993a1.65 1.65 0 0 0-.862.158a1.4 1.4 0 0 0-.268.17l-.007.006a.498.498 0 0 1-.69-.718");
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.ok0pekb3m {
  stop-color: var(--svg-color--28699c, #28699C);
}

.omp467bql {
  d: path("M9.306 20.884a.25.25 0 0 1-.375-.217v-2.563a.6.6 0 0 0-.6-.6H5.047a.6.6 0 0 0-.6.6v4.286c-.005.85.112 2.507 1.484 3.383c1.149.733 2.5.57 3.213.347c.102-.032.21.042.21.148v3.706c0 .083.066.15.15.15h12.993a.15.15 0 0 0 .15-.15v-3.706c0-.106.107-.18.209-.148c.712.222 2.064.386 3.213-.347c1.372-.876 1.49-2.534 1.484-3.383v-4.286a.6.6 0 0 0-.6-.6H23.67a.6.6 0 0 0-.6.6v2.563a.25.25 0 0 1-.375.217L16 16.952z");
}

.opwa50pmp {
  stop-color: var(--svg-color--896e61, #896E61);
  stop-opacity: 0;
}

.opxc931wt {
  stop-color: var(--svg-color--3990dd, #3990DD);
  stop-opacity: 0;
}

.p8zx0emkh {
  stop-color: var(--svg-color--389bfa, #389BFA);
  stop-opacity: 0;
}

.pbbnu-4dr {
  fill: var(--svg-color--b08a6f, #B08A6F);
  d: path("M26.104 11.514a.75.75 0 0 0-1.052.138l-.804 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.258v-2.698h-1.627q.054-.108.128-.204l.804-1.047a.75.75 0 0 0-.137-1.052");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqc_l8aas {
  d: path("M26.915 16.655a.25.25 0 0 0-.25-.25h-2.93a.25.25 0 0 0-.25.25v1.318h3.43z");
}

.q4wygiatd {
  stop-color: var(--svg-color--753d27, #753D27);
  stop-opacity: 0;
}

.qg12wplhp {
  cx: 15.769px;
  cy: 16.263px;
  fill: var(--svg-color--87004d, #87004D);
  rx: 0.734px;
  ry: 0.755px;
}

.qm-9wjixk {
  stop-color: var(--svg-color--9f6274, #9F6274);
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qrv_azbvd {
  stop-color: var(--svg-color--c6a18a, #C6A18A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.rjrjfgj9v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M3.095 14.434c.294.452 1.122 1.258 2.432 1.258");
}

.rqxwi30ib {
  stop-color: var(--svg-color--8e6854, #8E6854);
}

.s2173f0vf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m10.913 8.804l.065.835c.003.139-.031.453-.196.597");
}

.s2x4eib1h {
  cx: 13.137px;
  cy: 12.407px;
  rx: 0.364px;
  ry: 0.184px;
}

.s3c7c_8fj {
  fill: var(--svg-color--000, #000);
  d: path("M13.9 12.826a.475.475 0 0 0-.513-.438a.475.475 0 0 0-.368.727l.841-.065a.5.5 0 0 0 .04-.224");
}

.sca1f_z_y {
  d: path("M17.376 11.899c.065.074-.05.18-.183.296s-.231.198-.297.123c-.065-.074-.01-.228.122-.344s.293-.15.358-.075");
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.sp_au2bah {
  stop-color: var(--svg-color--43beff, #43BEFF);
  stop-opacity: 0;
}

.sppcpbbqx {
  stop-color: var(--svg-color--8a6355, #8A6355);
  stop-opacity: 0;
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.sv_dn8bha {
  stop-color: var(--svg-color--1e72ff, #1E72FF);
  stop-opacity: 0;
}

.sww5o1btl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M2.797 13.383c.238.483.966 1.38 2.267 1.534");
}

.t4l3x1b0r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M16.816 10.169c.395-.101 1.177-.142 1.75.236");
}

.tbw2b8m3a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M3.946 12.093c.196.502 1.017 1.388 2.051 1.54");
}

.teu5d39go {
  stop-color: var(--svg-color--967161, #967161);
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tq5y8jb5o {
  d: path("m10.688 12.752l.046-.003s-.111-.79-.204-1.332c-.019-.248.058-.553.246-.718l.138-.16c.234-.218.311-.523.288-.821l-.062-.794a.485.485 0 0 1 .361-.527c.588-.196 1.816-.54 3.613-.68c1.797-.139 3.063.012 3.674.115a.54.54 0 0 1 .438.465l.061.794c.023.298.196.584.411.767c.493.291.478.473.469.862c-.012.5.004 1.348.004 1.348l.017-.002l.038 3.703c-.022 1.658-1.227 2.906-2.77 3.025l-2.988.232c-1.593.123-2.927-.928-3.204-2.563z");
}

.u_7m_6tiu {
  stop-color: var(--svg-color--c6a18a, #C6A18A);
  stop-opacity: 0;
}

.uffhkkadj {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.596 11.45a1.3 1.3 0 0 1 1.337.888a.256.256 0 0 1-.225.336l-2.075.16a.215.215 0 0 1-.231-.236c.07-.605.56-1.099 1.194-1.148");
}

.um_m80b8n {
  fill-rule: evenodd;
  d: path("M29.623 12.023a.7.7 0 0 0-.977.157l-.115.168c-.261.391-.92 1.113-1.733 1.46c-.355.153-.502.45-.32.876c.152.355.733.503 1.089.35c1.245-.533 1.934-1.603 2.155-1.945L29.78 13a.7.7 0 0 0-.157-.977");
}

.uudqsyb7t {
  stop-color: var(--svg-color--c5a28a, #C5A28A);
  stop-opacity: 0;
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v49kkfisr {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m19.494 6.579l.415.167c.726.294 1.186 1.057 1.102 1.912l-.33 2.871c-.026.296-.204.508-.494.537l-.016.002s-.016-.848-.004-1.348c.009-.406-.07-.523-.469-.862a1.17 1.17 0 0 1-.41-.767l-.062-.794a.54.54 0 0 0-.438-.465c-.61-.103-1.877-.254-3.674-.115c-1.797.14-3.025.484-3.613.68a.485.485 0 0 0-.36.527l.061.794c.023.297-.054.603-.288.82l-.138.161c-.188.165-.265.47-.246.718c.093.542.204 1.332.204 1.332l-.046.002a.59.59 0 0 1-.591-.451l-.769-2.786c-.16-.787.177-1.612.849-2.013l.383-.23c.239-.168.473-.386.707-.604l.825-1.012a1.83 1.83 0 0 1 2.023-.456c.51.11 1.06.067 1.547-.12c.73-.306 1.594-.174 2.235.326l.806.686c.22.233.48.362.791.488");
}

.vjgm3lrsh {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m11.77 10.695l.002-.002l.004-.003l.01-.01a1.4 1.4 0 0 1 .137-.111c.088-.066.214-.148.375-.227a2.64 2.64 0 0 1 1.378-.255a.498.498 0 0 1-.079.993a1.65 1.65 0 0 0-.862.158a1.4 1.4 0 0 0-.268.17l-.007.006a.498.498 0 0 1-.69-.718");
}

.vk1yb8b6m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M2.867 12.374c.196.501.844 1.458 2.127 1.723");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vpgp1b8tt {
  stop-color: var(--svg-color--c5a28a, #C5A28A);
}

.vt--vh64k {
  d: path("m18.76 7.434l-2.79 1.177a.977.977 0 0 0 .585 1.856l2.817-.602z");
}

.vw_f_cbup {
  stop-color: var(--svg-color--227bc3, #227BC3);
}

.vwgnxabip {
  fill-rule: evenodd;
  d: path("M2.377 12.023a.7.7 0 0 1 .977.157q.05.071.115.168c.261.391.703 1.052 1.515 1.4a.7.7 0 1 1-.55 1.287c-1.247-.534-1.935-1.604-2.156-1.946q-.038-.06-.059-.089a.7.7 0 0 1 .158-.977");
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w5w35bc3u {
  fill-rule: evenodd;
  d: path("M2.344 13.045a.7.7 0 0 1 .98.142l.086.118c.302.42.764 1.062 1.78 1.062a.7.7 0 1 1 0 1.4c-1.776 0-2.638-1.24-2.925-1.654l-.062-.088a.7.7 0 0 1 .141-.98");
}

.we0-hlz5i {
  cx: 11.06px;
  cy: 13.296px;
  r: 0.929px;
}

.wjksmgbzx {
  stop-color: var(--svg-color--308bdb, #308BDB);
}

.x1al7bb2v {
  stroke: var(--svg-color--4abeff, #4ABEFF);
  stroke-linecap: square;
  d: path("M25.957 18.393v3.99a1 1 0 0 1-1.567.824l-1.84-1.265");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xbijjpcsb {
  fill: var(--svg-color--000, #000);
  d: path("M17.012 12.585a.475.475 0 0 1 .439-.512a.475.475 0 0 1 .476.661l-.841.066a.43.43 0 0 1-.074-.215");
}

.xjqh_ibco {
  stop-color: var(--svg-color--8e6f6b, #8E6F6B);
  stop-opacity: 0;
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xrwg8acec {
  d: path("M15.848 21.058c-1.104 0-2-.95-2-1.867v-2.358c0-.918.896-1.662 2-1.662s2 .744 2 1.662v2.358c0 .917-.896 1.867-2 1.867");
}

.xxwl_8dkv {
  d: path("M13.36 12.033a.833.833 0 0 0-.719 1.111l1.604-.124a1 1 0 0 0 .013-.221a.84.84 0 0 0-.898-.766");
}

.y3kcud5xy {
  cx: 15.769px;
  cy: 16.263px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  rx: 0.734px;
  ry: 0.755px;
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z108ppbpv {
  stop-color: var(--svg-color--1e72ff, #1E72FF);
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.z96fdub7f {
  stop-color: var(--svg-color--3481c0, #3481C0);
}

.zdh3sob9m {
  fill-rule: evenodd;
  d: path("M28.584 11.707a.7.7 0 0 0-.977.157a2 2 0 0 0-.115.182l-.006.01v.002c-.035.058-.067.114-.106.174c-.076.12-.17.25-.293.37c-.233.228-.608.468-1.267.5a.7.7 0 1 0 .068 1.398c1.024-.05 1.718-.447 2.179-.898c.223-.22.382-.441.495-.618c.053-.084.097-.16.13-.216l.004-.007l.044-.075l.002-.002a.7.7 0 0 0-.158-.977");
}

.zuuvnac4f {
  stop-color: var(--svg-color--1a7ad4, #1A7AD4);
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

.zzalqjn8m {
  stroke: var(--svg-color--bf9885, #BF9885);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M25.546 15.75h1.516a.7.7 0 0 0 .53-.172");
}

</style>
