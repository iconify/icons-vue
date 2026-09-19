<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijJeqEd)"><rect fill="url(#ihxVDoW)" transform="rotate(-45 12.963 14.245)" class="dgo6uu52h"/></g><g filter="url(#isB4K0d)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -1.997 35.922)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -1.997 35.922)" class="ffese-y7m"/><g filter="url(#iVKmpxc)"><path fill="url(#i38KqGb)" class="fcv6ycfqe"/><path fill="url(#inIgaze)" class="fcv6ycfqe"/></g><g filter="url(#ij4DxTH)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 7.602 30.155)" class="z_5s59bdn"/></g><g filter="url(#i68vOJe)"><path class="wh1uu6biy"/></g><g filter="url(#isUOHHX)"><path class="mv5v06b1s"/></g><g filter="url(#ijfACPe)"><path class="u7w80gbza"/></g><g filter="url(#ipnPZgd)"><path class="c06hlqbrn"/></g><g filter="url(#iYSWeWc)"><rect class="pd-sj-b4r"/><rect fill="url(#i1YZhJc)" class="ak6jatb9d"/></g><g filter="url(#ijIZmte)"><path fill="url(#iZ77Hxe)" class="lg4ttrbbb"/></g><path fill="url(#iznxGjb)" class="lg4ttrbbb"/><path fill="url(#iXiDYFb)" class="lg4ttrbbb"/><path fill="url(#iIWhOYd)" class="lg4ttrbbb"/><path class="kezy6kb5v"/><path fill="url(#iclZYQc)" class="ou4qbwy3s"/><path fill="url(#i6FlpWc)" class="ou4qbwy3s"/><path fill="url(#i9zp5Oc)" class="ou4qbwy3s"/><path fill="url(#iFJvMfe)" class="ou4qbwy3s"/><path fill="url(#iUfRCme)" class="ou4qbwy3s"/><path class="gdl5w8biy"/><path fill="url(#i4Hpihc)" class="r56qyu1-c"/><path fill="url(#i0Ij3Hb)" class="r56qyu1-c"/><path fill="url(#ioxM3Lb)" class="x356vlupl"/><path fill="url(#i80FzBc)" class="x356vlupl"/><path fill="url(#ieq4xab)" class="x356vlupl"/><path fill="url(#izgLr0c)" class="x356vlupl"/><path fill="url(#i5lZxcd)" class="b2nja9b7b"/><path fill="url(#iBtRO8F)" class="b2nja9b7b"/><g filter="url(#ieANCne)"><path class="xn221gbbe"/><path fill="url(#i26VQee)" class="qrmu29b8p"/><path fill="url(#ivcl6Hb)" class="qrmu29b8p"/></g><path fill="url(#ibtkiNc)" class="qrmu29b8p"/><path fill="url(#iVsSxrM)" class="zx4dgabxp"/><path fill="url(#iQBTkue)" class="zx4dgabxp"/><circle fill="url(#iRGeTdb)" class="awoe1l9jl"/><g filter="url(#icOwDVe)"><path class="kv_mew_zg"/><path fill="url(#itrIUyy)" class="mnsx7-msn"/><path fill="url(#itpAvad)" class="mnsx7-msn"/></g><g filter="url(#ixqJbwd)"><path class="stls5mbvb"/><path fill="url(#i5l9ZLd)" class="ynocd3taj"/><path fill="url(#iQ8NPBb)" class="ynocd3taj"/></g><g filter="url(#iUbcX5b)"><path class="b8crozbzq"/></g><path fill="url(#iBYIoqc)" class="y60mf7kqt"/><path fill="url(#ibq0vCe)" class="y60mf7kqt"/><path fill="url(#i5E3mBb)" class="y60mf7kqt"/><path fill="url(#iz7yqwm)" class="y60mf7kqt"/><path fill="url(#i0lamuh)" class="y60mf7kqt"/><path fill="url(#icyJa9b)" class="m0-rbh9jf"/><path fill="url(#ieiPRwd)" class="m0-rbh9jf"/><g filter="url(#iXjNhcO)"><path stroke="url(#iUgZG1d)" class="yj0hglfmq"/></g><g filter="url(#iieyz1b)"><path stroke="url(#ihPaxne)" class="nt0kyibal"/></g><g filter="url(#iGqJ43c)"><path stroke="url(#iRPZlfd)" class="nxetr6byj"/></g><path fill="url(#iSxzAOb)" class="j3z1sfbgo"/><path fill="url(#iwYDFfd)" class="byht6_bes"/><path fill="url(#iiZMF4c)" class="byht6_bes"/><path fill="url(#iwYDFfd)" class="byht6_bes"/><path fill="url(#iiZMF4c)" class="byht6_bes"/><g filter="url(#iEQWVLd)"><path fill="url(#iWtVSnJ)" class="rh0txlbwy"/></g><path fill="url(#inNkNuA)" class="rh0txlbwy"/><path fill="url(#iUpuHgI)" class="rh0txlbwy"/><path fill="url(#i6bFOkc)" class="rh0txlbwy"/><path fill="url(#ir7rrLd)" class="rh0txlbwy"/><path fill="url(#iLBncve)" class="rh0txlbwy"/><path fill="url(#iZVTIad)" class="rh0txlbwy"/><path fill="url(#iVYsTCE)" class="rh0txlbwy"/><path fill="url(#ie5RABd)" class="rh0txlbwy"/><g filter="url(#inOCveb)"><path class="a0796nkhq"/></g><g filter="url(#ir5B5yb)"><path fill="url(#iP8emmd)" class="vksxc-bek"/><path fill="url(#iWrAq9d)" class="vksxc-bek"/><path fill="url(#it7soBd)" class="vksxc-bek"/><path fill="url(#itNSEmc)" class="vksxc-bek"/></g><g filter="url(#ijFJ8Hy)"><path stroke="url(#iihRN3k)" class="u04tkobit"/></g><path fill="url(#i2V0dvd)" class="y3a7pf3-m"/><g filter="url(#iNgkChc)"><path fill="url(#ityxfGd)" class="mnm7kkbli"/><path fill="url(#iyNviJc)" class="mnm7kkbli"/><path fill="url(#iXaVs7b)" class="mnm7kkbli"/><path fill="url(#iGnCYId)" class="mnm7kkbli"/><path fill="url(#iFnrHSz)" class="mnm7kkbli"/></g><g filter="url(#ijnkj6c)"><path class="po92i-42v"/></g><g filter="url(#i4MgpRC)"><path class="mcgx9sbsh"/></g><g filter="url(#iExnMZc)"><path fill="url(#iT28XFb)" class="gicfkf46k"/><path fill="url(#iR9lovb)" class="gicfkf46k"/></g><g filter="url(#i5gIZJe)"><path fill="url(#izl0snd)" class="acqf341rt"/><path fill="url(#iijqqyc)" class="acqf341rt"/><path fill="url(#ip7DQFd)" class="acqf341rt"/><path fill="url(#iG0vMyc)" class="acqf341rt"/><path fill="url(#iDPqr4d)" class="acqf341rt"/><path fill="url(#iTCF6de)" class="acqf341rt"/></g><path class="emzzm3buo"/><path fill="url(#ix3ooZb)" class="spdcywbdl"/><path class="owpnnreuq"/><g filter="url(#i54uWfc)"><path class="a43nzluec"/><path fill="url(#irw0mMb)" class="mach7qb-k"/></g><g filter="url(#iBR7blF)"><path fill="url(#iz4yrub)" class="hkuznibjb"/></g><path class="yssjiut9l"/><path fill="url(#iPpiWYc)" class="bk9auhm_x"/><path class="lvo1d4gkc"/><g filter="url(#ib5exyc)"><path fill="url(#i2Zkikd)" class="ptd5w_bgm"/></g><g filter="url(#iHKRIic)"><ellipse transform="rotate(-27.914 14.964 8.443)" class="bm-l9fysn"/><ellipse fill="url(#iwLtsse)" transform="rotate(-27.914 14.964 8.443)" class="atk--c-_f"/></g><path fill="url(#iKWiZHd)" class="j646ep18x"/><path fill="url(#ixWUZNc)" class="j646ep18x"/><path fill="url(#iUN7ktd)" class="j646ep18x"/><path fill="url(#irouqyc)" class="sgrvt5xry"/><path fill="url(#i4olwKd)" class="sgrvt5xry"/><g filter="url(#igCftpc)"><path class="fzmpgq3ox"/></g><g filter="url(#iQtvMub)"><path class="zzvmqj-9b"/></g><defs><radialGradient id="ihxVDoW" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 22.143)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="iZ77Hxe" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.232 6.285)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="iznxGjb" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.216 3.418)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="iXiDYFb" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.402 17.528)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iIWhOYd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 4.37)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iclZYQc" cx="0" cy="0" r="1" gradientTransform="rotate(-105.819 18.008 3.252)scale(4.87202 1.60555)" gradientUnits="userSpaceOnUse"><stop class="ip469ff8c"/><stop offset="1" class="v0q_-i93u"/></radialGradient><radialGradient id="i6FlpWc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 3.125 -1.0965 .4715 17.1 20.746)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="sl-3t4bfx"/><stop offset="1" class="zeih87brn"/></radialGradient><radialGradient id="iFJvMfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.73437 .44794 -.04289 16.241 19.325)" gradientUnits="userSpaceOnUse"><stop class="c6dvfyb6s"/><stop offset="1" class="oz3_ipb8v"/></radialGradient><radialGradient id="iUfRCme" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 2.82812 -.75946 -.05455 15.241 20.808)" gradientUnits="userSpaceOnUse"><stop class="xo-vurl-f"/><stop offset="1" class="un08nrbhl"/></radialGradient><radialGradient id="ieq4xab" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 3.09375 -.85026 -.073 15.348 27.119)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="k6zy9n07l"/><stop offset="1" class="m22s2i1fh"/></radialGradient><radialGradient id="iBtRO8F" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 30.307)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="ivcl6Hb" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.80469 -.96535 .25074 19.32 21.41)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="s-dztxv8u"/><stop offset="1" class="wm2hnkwbm"/></radialGradient><radialGradient id="ibtkiNc" cx="0" cy="0" r="1" gradientTransform="matrix(.71094 .34759 -.96823 1.98037 16.606 24.586)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="dvlr87bav"/><stop offset="1" class="h2aikfbxt"/></radialGradient><radialGradient id="iQBTkue" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 28.058)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="iRGeTdb" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .1914 -.31978 .73092 6.135 16.572)" gradientUnits="userSpaceOnUse"><stop class="md09g_bwr"/><stop offset="1" class="vudwjbw9p"/></radialGradient><radialGradient id="itrIUyy" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 29.074 -.881)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="n6c_0ja6r"/><stop offset="1" class="sxlwo8bvv"/></radialGradient><radialGradient id="itpAvad" cx="0" cy="0" r="1" gradientTransform="matrix(-.94747 2.72 -.8954 -.3119 13.593 14.311)" gradientUnits="userSpaceOnUse"><stop class="p77zblbaj"/><stop offset="1" class="gvz69mboo"/></radialGradient><radialGradient id="i5l9ZLd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 15.384)" gradientUnits="userSpaceOnUse"><stop class="z1f5d8bxu"/><stop offset="1" class="s8gxoccyp"/></radialGradient><radialGradient id="iQ8NPBb" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 16.111)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="t_55psbku"/><stop offset="1" class="bwfo2x8_b"/></radialGradient><radialGradient id="i5E3mBb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92712 .2574 -.06658 -.49847 15.23 11.56)" gradientUnits="userSpaceOnUse"><stop class="hq3hkib4c"/><stop offset="1" class="k_rioyb_p"/></radialGradient><radialGradient id="iz7yqwm" cx="0" cy="0" r="1" gradientTransform="rotate(142.326 7.02 9.278)scale(1.55953 .89404)" gradientUnits="userSpaceOnUse"><stop class="ignt4ubkd"/><stop offset="1" class="hts433_5m"/></radialGradient><radialGradient id="i0lamuh" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.67188 4.0767 0 18.136 16.395)" gradientUnits="userSpaceOnUse"><stop class="xnxf0re5w"/><stop offset="1" class="utdakeidf"/></radialGradient><radialGradient id="icyJa9b" cx="0" cy="0" r="1" gradientTransform="rotate(62.33 -1.791 18.187)scale(1.17765 2.48248)" gradientUnits="userSpaceOnUse"><stop class="q_i4prb1m"/><stop offset="1" class="osml3-ahx"/></radialGradient><radialGradient id="ieiPRwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.95899 .51766 -.25276 -.46825 16.987 11.507)" gradientUnits="userSpaceOnUse"><stop class="sb6wk2byh"/><stop offset="1" class="oh250pbjd"/></radialGradient><radialGradient id="iSxzAOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26441 1.5337 -1.82192 -.3141 18.397 9.218)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iwYDFfd" cx="0" cy="0" r="1" gradientTransform="matrix(.55277 1.16372 -.52896 .25126 13.62 9.341)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iiZMF4c" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 1.611 12.738)scale(.52376 .45945)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iWtVSnJ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.26852 0 0 -4.01298 17.247 8.882)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iUpuHgI" cx="0" cy="0" r="1" gradientTransform="matrix(-.49597 5.62503 -4.6582 -.41073 16.715 6.316)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="dqi7sbofo"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="i6bFOkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58186 .72005 0 17.09 8.396)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="ir7rrLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0252 -.4788 .52104 -.02742 15.057 8.336)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iLBncve" cx="0" cy="0" r="1" gradientTransform="matrix(.52367 0 0 2.66171 13.91 9.049)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iZVTIad" cx="0" cy="0" r="1" gradientTransform="matrix(1.13462 -1.58556 .35913 .257 13.489 7.58)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iVYsTCE" cx="0" cy="0" r="1" gradientTransform="rotate(-103.259 12.196 -.994)scale(4.56644 5.03008)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="ie5RABd" cx="0" cy="0" r="1" gradientTransform="rotate(19.416 -10.694 52.603)scale(.94084 .5644)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iihRN3k" cx="0" cy="0" r="1" gradientTransform="matrix(.15064 -.2688 .7822 .43838 15.54 10.309)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="i2V0dvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.31275 1.25827 0 16.028 10.418)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iyNviJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.57631 2.79292 0 13.759 8.195)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iXaVs7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.57631 2.79292 0 18.137 8.195)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iGnCYId" cx="0" cy="0" r="1" gradientTransform="matrix(-1.411 -.53822 .28664 -.75146 17.812 5.472)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="iFnrHSz" cx="0" cy="0" r="1" gradientTransform="matrix(.39275 .64004 -1.48204 .90944 15.636 4.78)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iT28XFb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65193 .59603 -.16589 -.45977 16.137 5.406)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iR9lovb" cx="0" cy="0" r="1" gradientTransform="matrix(1.39646 -2.21106 2.44963 1.54713 13.672 7.472)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="izl0snd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4692 .3475 -.19435 .82167 17.6 5.91)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iijqqyc" cx="0" cy="0" r="1" gradientTransform="matrix(-.93234 -1.60714 .89629 -.51996 18.254 7.908)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="ip7DQFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5673 -.95564 .68448 -.40634 17.985 7.778)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iG0vMyc" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 8.708 4)scale(2.14126 2.31479)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iDPqr4d" cx="0" cy="0" r="1" gradientTransform="rotate(107.002 6.615 9.387)scale(.17412 .79607)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iTCF6de" cx="0" cy="0" r="1" gradientTransform="matrix(-.8655 1.6292 -4.20127 -2.23188 17.525 5.448)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="ix3ooZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35206 -.55998 0 16.975 8.484)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="irw0mMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10064 -.12968 .17855 -.13855 16.876 8.522)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPpiWYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35207 -.56001 0 15.082 8.484)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iwLtsse" cx="0" cy="0" r="1" gradientTransform="matrix(-.00336 -.2144 .25771 -.00404 14.957 8.58)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixWUZNc" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 3.418 16.135)scale(1.01091 .96449)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iUN7ktd" cx="0" cy="0" r="1" gradientTransform="matrix(.34184 -.46912 .39322 .28653 18.188 8.726)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="i4olwKd" cx="0" cy="0" r="1" gradientTransform="rotate(-171.679 7.267 3.88)scale(.73457 .72215)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><filter id="ijJeqEd" width="7.335" height="7.371" x="13.891" y="11.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1153" result="effect2_innerShadow_4002_1153"/></filter><filter id="isB4K0d" width="10.517" height="10.517" x="14.14" y="5.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1153" result="effect2_innerShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1153" result="effect3_innerShadow_4002_1153"/></filter><filter id="iVKmpxc" width="9.391" height="10.922" x="7.466" y="5.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1153" result="effect2_innerShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1153" result="effect3_innerShadow_4002_1153"/></filter><filter id="ij4DxTH" width="7.298" height="7.298" x="10.845" y="11.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/></filter><filter id="i68vOJe" width="3.908" height="3.642" x="9.545" y="9.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1153" result="effect2_dropShadow_4002_1153"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1153" result="shape"/></filter><filter id="isUOHHX" width="6.45" height="6.548" x="9.62" y="6.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1153" result="effect2_dropShadow_4002_1153"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1153" result="shape"/></filter><filter id="ijfACPe" width="3.908" height="3.642" x="18.631" y="9.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1153" result="effect2_dropShadow_4002_1153"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1153" result="shape"/></filter><filter id="ipnPZgd" width="6.45" height="6.548" x="16.014" y="6.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1153" result="effect2_dropShadow_4002_1153"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1153" result="shape"/></filter><filter id="iYSWeWc" width="1.003" height="4.833" x="22.341" y="5.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/></filter><filter id="ijIZmte" width="4.084" height="3.799" x="20.732" y="2.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/></filter><filter id="ieANCne" width="5.091" height="7.247" x="15.749" y="21.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.54902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/></filter><filter id="icOwDVe" width="7.578" height="5.434" x="6.015" y="11.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.505882 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.454902 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1153" result="effect2_innerShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.6 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1153" result="effect3_innerShadow_4002_1153"/></filter><filter id="ixqJbwd" width="1.692" height="1.561" x="6.722" y="15.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.537255 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/></filter><filter id="iUbcX5b" width="5.398" height="7.21" x="18.218" y="8.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.466667 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/></filter><filter id="iXjNhcO" width="4.609" height="5.161" x="19.13" y="10.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".25"/></filter><filter id="iieyz1b" width="1.248" height="2.077" x="21.759" y="9.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".1"/></filter><filter id="iGqJ43c" width=".822" height="1.445" x="22.798" y="9.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".1"/></filter><filter id="iEQWVLd" width="5.185" height="5.555" x="13.831" y="6.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1153" result="effect2_innerShadow_4002_1153"/></filter><filter id="inOCveb" width="2.761" height="3.225" x="14.531" y="7.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".5"/></filter><filter id="ir5B5yb" width="1.015" height="1.458" x="15.521" y="8.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".05"/></filter><filter id="ijFJ8Hy" width="1.897" height=".966" x="15.08" y="9.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".05"/></filter><filter id="iNgkChc" width="5.586" height="3.909" x="13.235" y="4.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1153" result="effect2_innerShadow_4002_1153"/></filter><filter id="ijnkj6c" width="1.072" height=".63" x="16.718" y="7.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/></filter><filter id="i4MgpRC" width="1.072" height=".623" x="14.437" y="7.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1153"/></filter><filter id="iExnMZc" width="2.84" height="2.561" x="13.398" y="5.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".05"/></filter><filter id="i5gIZJe" width="2.673" height="2.435" x="16.038" y="5.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".05"/></filter><filter id="i54uWfc" width=".455" height=".415" x="16.6" y="8.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".05"/></filter><filter id="iBR7blF" width=".613" height=".623" x="16.908" y="8.213" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".1"/></filter><filter id="ib5exyc" width=".654" height=".678" x="14.98" y="8.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".1"/></filter><filter id="iHKRIic" width=".509" height=".419" x="14.709" y="8.233" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".05"/></filter><filter id="igCftpc" width=".86" height="1.315" x="13.269" y="8.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".125"/></filter><filter id="iQtvMub" width=".911" height="1.326" x="17.931" y="8.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1153" stdDeviation=".125"/></filter><linearGradient id="i38KqGb" x1="8.529" x2="12.668" y1="6.685" y2="10.824" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="inIgaze" x1="11.132" x2="10.694" y1="13.808" y2="9.902" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="i1YZhJc" x1="22.918" x2="22.549" y1="6.187" y2="6.975" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="i9zp5Oc" x1="13.263" x2="14.851" y1="20.199" y2="20.199" gradientUnits="userSpaceOnUse"><stop class="x36zqabyv"/><stop offset="1" class="uktlcdafx"/></linearGradient><linearGradient id="i4Hpihc" x1="18.792" x2="16.991" y1="17.09" y2="17.09" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="i0Ij3Hb" x1="13.267" x2="15.007" y1="17.273" y2="17.273" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="ioxM3Lb" x1="15.288" x2="13.817" y1="26.105" y2="26.105" gradientUnits="userSpaceOnUse"><stop offset=".267" class="gvrh5ob2r"/><stop offset=".945" class="zx2ao6bwg"/></linearGradient><linearGradient id="i80FzBc" x1="15.46" x2="14.96" y1="27.511" y2="27.48" gradientUnits="userSpaceOnUse"><stop class="ff90ucc6c"/><stop offset="1" class="a5twm1ncx"/></linearGradient><linearGradient id="izgLr0c" x1="13.261" x2="13.692" y1="26.509" y2="26.509" gradientUnits="userSpaceOnUse"><stop class="p5rcrxbls"/><stop offset="1" class="w4_s79ciy"/></linearGradient><linearGradient id="i5lZxcd" x1="15.197" x2="13.71" y1="29.733" y2="29.733" gradientUnits="userSpaceOnUse"><stop class="htqsm-l2e"/><stop offset=".159" class="zd1r_u8ze"/><stop offset=".453" class="x09-01b7i"/><stop offset="1" class="s_f01nb2h"/></linearGradient><linearGradient id="i26VQee" x1="18.825" x2="18.351" y1="25.22" y2="24.933" gradientUnits="userSpaceOnUse"><stop class="rr5fu4pew"/><stop offset="1" class="u39dyibqi"/></linearGradient><linearGradient id="iVsSxrM" x1="15.749" x2="17.116" y1="26.823" y2="27.886" gradientUnits="userSpaceOnUse"><stop class="ilfb1o36w"/><stop offset="1" class="q6qjg9bpc"/></linearGradient><linearGradient id="iBYIoqc" x1="16.065" x2="16.065" y1="11.559" y2="16.395" gradientUnits="userSpaceOnUse"><stop class="ctgol8ben"/><stop offset="1" class="d2j7ihp4i"/></linearGradient><linearGradient id="ibq0vCe" x1="13.303" x2="15.492" y1="15.592" y2="15.592" gradientUnits="userSpaceOnUse"><stop offset=".01" class="k4svfjbzs"/><stop offset="1" class="k0oa_8bou"/></linearGradient><linearGradient id="iUgZG1d" x1="22.63" x2="20.036" y1="12.447" y2="14.291" gradientUnits="userSpaceOnUse"><stop offset=".453" class="bi_gnlatu"/><stop offset="1" class="qqsiimfct"/></linearGradient><linearGradient id="ihPaxne" x1="22.059" x2="21.755" y1="9.4" y2="11.091" gradientUnits="userSpaceOnUse"><stop class="opdu08blf"/><stop offset="1" class="t02y35b0p"/></linearGradient><linearGradient id="iRPZlfd" x1="23.07" x2="22.804" y1="9.777" y2="10.738" gradientUnits="userSpaceOnUse"><stop class="opdu08blf"/><stop offset="1" class="t02y35b0p"/></linearGradient><linearGradient id="inNkNuA" x1="18.266" x2="16.378" y1="9.613" y2="9.613" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iP8emmd" x1="16.028" x2="16.399" y1="9.241" y2="9.241" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iWrAq9d" x1="15.563" x2="16.029" y1="9.174" y2="9.2" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="it7soBd" x1="16.028" x2="16.028" y1="9.414" y2="9.784" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="itNSEmc" x1="16.028" x2="16.028" y1="8.439" y2="8.621" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="ityxfGd" x1="18.356" x2="13.963" y1="6.425" y2="6.425" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iz4yrub" x1="17.313" x2="17.176" y1="8.507" y2="8.591" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2Zkikd" x1="15.404" x2="15.268" y1="8.508" y2="8.591" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKWiZHd" x1="18.821" x2="18.297" y1="8.519" y2="9.464" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="irouqyc" x1="13.49" x2="14.123" y1="8.825" y2="8.769" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-fairy-medium-light" /></template>
<style>
.a0796nkhq {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.841 8.736l-.3.718c-.044.164.062.328.211.328h.32c.149 0 .254-.166.21-.328l-.215-.797c-.047-.177-.177-.098-.226.079");
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a43nzluec {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.948 8.359c.027.037-.03.082-.096.13c-.066.05-.114.084-.142.048s.003-.107.069-.156c.066-.05.141-.059.169-.022");
}

.a5twm1ncx {
  stop-color: var(--svg-color--dea386, #DEA386);
  stop-opacity: 0;
}

.acqf341rt {
  d: path("m18.29 7.908l-.013-.274a.637.637 0 0 0-.61-.618h-.607a1.05 1.05 0 0 1-.922-.547s.313-.902.831-.785c.38.085.785.22 1.095.422c.757.493.625 1.383.226 1.802");
}

.ak6jatb9d {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 5.839px;
  rx: 0.352px;
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.atk--c-_f {
  cx: 14.964px;
  cy: 8.443px;
  rx: 0.169px;
  ry: 0.086px;
}

.awoe1l9jl {
  cx: 6.572px;
  cy: 16.527px;
  r: 0.438px;
}

.b2nja9b7b {
  d: path("m13.312 28.94l.006 1.49c0 .169.164.288.322.231c.348-.125.845-.33 1.287-.603a.47.47 0 0 0 .215-.373l.055-.894z");
}

.b8crozbzq {
  fill: var(--svg-color--dfa286, #DFA286);
  d: path("m21.499 13.113l-3.144-1.207l-.137 2.176l3.578 1.367c.185.083.652.2 1.039 0s.516-.719.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.037.494.276.837.438.962z");
}

.bi_gnlatu {
  stop-color: var(--svg-color--f6c1a2, #F6C1A2);
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bk9auhm_x {
  d: path("M15.08 8.277a.387.387 0 0 0-.373.49h.749a.39.39 0 0 0-.375-.49");
}

.bm-l9fysn {
  cx: 14.964px;
  cy: 8.443px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.bwfo2x8_b {
  stop-color: var(--svg-color--e0aa8f, #E0AA8F);
}

.byht6_bes {
  d: path("M13.919 9.424a.7.7 0 0 1-.393-.134v.404c0 .388.231.733.582.876a1.8 1.8 0 0 1-.15-.512z");
}

.c06hlqbrn {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 7.167a.21.21 0 0 1 .418.048L20.94 8.6l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.311l4.234-3.837z");
}

.c6dvfyb6s {
  stop-color: var(--svg-color--e94a61, #E94A61);
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctgol8ben {
  stop-color: var(--svg-color--ff8328, #FF8328);
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d2j7ihp4i {
  stop-color: var(--svg-color--ff712e, #FF712E);
}

.dgo6uu52h {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 14.245px;
  rx: 2.422px;
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.dvlr87bav {
  stop-color: var(--svg-color--b88067, #B88067);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.emzzm3buo {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.066 8.16c.283 0 .523.195.588.459a.12.12 0 0 1-.116.147h-.968a.1.1 0 0 1-.1-.117c.056-.279.3-.49.596-.49");
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fcv6ycfqe {
  d: path("M8.523 11.566a3.454 3.454 0 0 1 .006-4.881a3.454 3.454 0 0 1 4.88-.006l1.19 1.19c.338.338.602.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.25v.559a2.443 2.443 0 0 1-4.17 1.727z");
}

.ff90ucc6c {
  stop-color: var(--svg-color--dea386, #DEA386);
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fzmpgq3ox {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M13.843 8.362a.415.415 0 0 0 .036.816a34 34 0 0 1-.037-.816");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gdl5w8biy {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 17.191v-.82h5.525v.82c-2.337.149-4.276.063-5.525 0");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gicfkf46k {
  d: path("m16.13 6.445l-.03-.06a.29.29 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.466v.12c-.147-.113-.333-.35-.333-.733c0-.465.34-.7.556-.85c.06-.042.112-.078.143-.11l.043-.045c.152-.161.422-.448.894-.573a2 2 0 0 1 .197-.042c.466-.075.807.344.807.817v.185z");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gvrh5ob2r {
  stop-color: var(--svg-color--f4bba1, #F4BBA1);
}

.gvz69mboo {
  stop-color: var(--svg-color--ac596b, #AC596B);
  stop-opacity: 0;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h2aikfbxt {
  stop-color: var(--svg-color--c6846b, #C6846B);
  stop-opacity: 0;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hkuznibjb {
  d: path("M17.32 8.613a.36.36 0 0 0-.1-.2l-.112.123l.05.1z");
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hq3hkib4c {
  stop-color: var(--svg-color--e0521f, #E0521F);
}

.htqsm-l2e {
  stop-color: var(--svg-color--664e86, #664E86);
}

.hts433_5m {
  stop-color: var(--svg-color--ff9842, #FF9842);
  stop-opacity: 0;
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ignt4ubkd {
  stop-color: var(--svg-color--ff9842, #FF9842);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.ilfb1o36w {
  stop-color: var(--svg-color--352b41, #352B41);
}

.ip469ff8c {
  stop-color: var(--svg-color--ff8045, #FF8045);
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j3z1sfbgo {
  d: path("M18.138 9.424a.7.7 0 0 0 .392-.134v.404a.94.94 0 0 1-.582.876q.112-.236.15-.512z");
}

.j646ep18x {
  d: path("M18.164 9.464q.044-.693.08-1.385a.698.698 0 0 1-.08 1.385");
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.k_rioyb_p {
  stop-color: var(--svg-color--e0521f, #E0521F);
  stop-opacity: 0;
}

.k0oa_8bou {
  stop-color: var(--svg-color--f36b26, #F36B26);
  stop-opacity: 0;
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.k4svfjbzs {
  stop-color: var(--svg-color--d35c1b, #D35C1B);
}

.k6zy9n07l {
  stop-color: var(--svg-color--a87973, #A87973);
}

.kezy6kb5v {
  fill: var(--svg-color--fb652d, #FB652D);
  d: path("M13.263 22.575v-5.471l5.529.056c0 .348.063.665.09.764l1.042 3.486l-2.33.484l-.865-2.222c-.132-.337-.285-.64-.504-.64c-.25 0-.356.39-.361.59l-.28 3.01z");
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kv_mew_zg {
  fill: var(--svg-color--e1ab90, #E1AB90);
  d: path("M13.28 12.12c.194-.187.29-.228.313-.226v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.469c-.132.09-.302.24-.448.377a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.026 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.805c.566-.521 1.744-1.61 1.938-1.797");
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lg4ttrbbb {
  d: path("M22.5 3.136a.22.22 0 0 1 .4 0l.413.896a.22.22 0 0 0 .175.126l.983.115a.22.22 0 0 1 .128.376l-.734.716a.22.22 0 0 0-.062.201l.185.925a.22.22 0 0 1-.32.238l-.864-.46a.22.22 0 0 0-.206 0l-.87.463a.22.22 0 0 1-.32-.236l.178-.932a.22.22 0 0 0-.062-.197l-.727-.719a.22.22 0 0 1 .13-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.lvo1d4gkc {
  fill: var(--svg-color--000, #000);
  d: path("M15.302 8.664a.22.22 0 0 0-.222-.221a.22.22 0 0 0-.197.324h.393a.2.2 0 0 0 .026-.103");
}

.m0-rbh9jf {
  d: path("M15.07 11.328v.349c0 .058.026.114.065.157c.135.147.326.443.456.87c.06.195.233.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.457-.87a.24.24 0 0 0 .065-.157v-.35z");
}

.m22s2i1fh {
  stop-color: var(--svg-color--d7a18a, #D7A18A);
  stop-opacity: 0;
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mach7qb-k {
  d: path("M16.948 8.359c.027.037-.03.082-.096.13c-.066.05-.114.084-.142.048s.003-.107.069-.156c.066-.05.141-.059.169-.022");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcgx9sbsh {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M14.548 7.541a1.2 1.2 0 0 1 .755-.156a.12.12 0 1 1-.03.24a.96.96 0 0 0-.634.144l-.007.005h-.001a.12.12 0 0 1-.148-.19z");
}

.md09g_bwr {
  stop-color: var(--svg-color--dc9f87, #DC9F87);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mnm7kkbli {
  d: path("M18.135 6c.223.076.423.232.55.455c.203.356.173.782-.046 1.097a.7.7 0 0 0-.117.379v.515a.8.8 0 0 0-.29-.116l.034-.697a.63.63 0 0 0-.598-.621h-.608c-.414 0-.79-.245-.96-.626a.29.29 0 0 0-.267-.182h-.552c-.8 0-1.45.656-1.45 1.466l.014.667a.74.74 0 0 0-.313.115V7.93a.7.7 0 0 0-.117-.38a1.04 1.04 0 0 1-.062-1.06c.126-.24.33-.408.563-.49c.249-.088.46-.256.601-.481a1.01 1.01 0 0 1 1.254-.396a.65.65 0 0 0 .518 0a1.01 1.01 0 0 1 1.259.41c.134.22.343.381.587.465");
}

.mnsx7-msn {
  d: path("M13.28 12.12c.194-.187.29-.228.313-.226v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.469c-.132.09-.302.24-.448.377a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.026 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.805c.566-.521 1.744-1.61 1.938-1.797");
}

.mv5v06b1s {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 7.167a.21.21 0 0 0-.417.048l.159 1.385l-1.024-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .282-.311l-4.235-3.837z");
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.n6c_0ja6r {
  stop-color: var(--svg-color--bc826b, #BC826B);
  stop-opacity: 0;
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nt0kyibal {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.06 9.4v.505a1 1 0 0 0 .433.824l.215.148");
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.nxetr6byj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M23.32 9.777v.258a.9.9 0 0 1-.25.617v0");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oh250pbjd {
  stop-color: var(--svg-color--df9e84, #DF9E84);
  stop-opacity: 0;
}

.opdu08blf {
  stop-color: var(--svg-color--d5a38f, #D5A38F);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.osml3-ahx {
  stop-color: var(--svg-color--e1a891, #E1A891);
}

.ou4qbwy3s {
  d: path("M13.263 22.575v-5.471l5.529.056c0 .348.063.665.09.764l1.042 3.486l-2.33.484l-.865-2.222c-.132-.337-.285-.64-.504-.64c-.25 0-.356.39-.361.59l-.28 3.01z");
}

.owpnnreuq {
  fill: var(--svg-color--000, #000);
  d: path("M16.754 8.664a.22.22 0 0 1 .222-.221a.22.22 0 0 1 .197.324h-.392a.2.2 0 0 1-.027-.103");
}

.oz3_ipb8v {
  stop-color: var(--svg-color--e94a61, #E94A61);
  stop-opacity: 0;
}

.p5rcrxbls {
  stop-color: var(--svg-color--e1a58b, #E1A58B);
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.p77zblbaj {
  stop-color: var(--svg-color--ac596b, #AC596B);
}

.pd-sj-b4r {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 5.839px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.352px;
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po92i-42v {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M17.648 7.589a.8.8 0 0 0-.298-.179c-.132-.041-.298-.052-.527-.024a.12.12 0 1 0 .03.238c.208-.025.336-.012.424.016a.6.6 0 0 1 .213.13a.12.12 0 0 0 .158-.181");
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.ptd5w_bgm {
  d: path("M15.434 8.619c0-.125-.101-.209-.129-.234l-.125.121l.077.157z");
}

.q_i4prb1m {
  stop-color: var(--svg-color--d08a70, #D08A70);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q6qjg9bpc {
  stop-color: var(--svg-color--64468a, #64468A);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qqsiimfct {
  stop-color: var(--svg-color--f6c1a2, #F6C1A2);
  stop-opacity: 0;
}

.qrmu29b8p {
  d: path("m17.672 22.117l-.082-.227l2.331-.48c.02.062.094.292.219.71c.125.42-.01.774-.094.9l-3.269 5.343c-.07.116-.233.128-.311.018c-.297-.422-.547-.975-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.033a.6.6 0 0 0 .019-.453");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r56qyu1-c {
  d: path("M13.267 17.191v-.82h5.525v.82c-2.337.149-4.276.063-5.525 0");
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rh0txlbwy {
  d: path("M13.935 10.082a1.7 1.7 0 0 0 1.686 1.477h.818a1.7 1.7 0 0 0 1.687-1.477c.05-.818.102-1.632.14-2.449a.63.63 0 0 0-.598-.621h-.608c-.414 0-.79-.245-.96-.626a.29.29 0 0 0-.266-.182h-.553c-.8 0-1.45.656-1.45 1.466c0 .808.05 1.602.104 2.412");
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr5fu4pew {
  stop-color: var(--svg-color--dba697, #DBA697);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s_f01nb2h {
  stop-color: var(--svg-color--4b3866, #4B3866);
}

.s-dztxv8u {
  stop-color: var(--svg-color--ffceac, #FFCEAC);
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s8gxoccyp {
  stop-color: var(--svg-color--edba9f, #EDBA9F);
  stop-opacity: 0;
}

.sb6wk2byh {
  stop-color: var(--svg-color--df9e84, #DF9E84);
}

.sgrvt5xry {
  d: path("M13.835 8.075a.698.698 0 0 0 .06 1.389a34 34 0 0 1-.06-1.389");
}

.sl-3t4bfx {
  stop-color: var(--svg-color--e43423, #E43423);
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.spdcywbdl {
  d: path("M16.976 8.277a.387.387 0 0 1 .373.49h-.748a.39.39 0 0 1 .375-.49");
}

.stls5mbvb {
  fill: var(--svg-color--daa788, #DAA788);
  d: path("M7.08 15.845c.177-.132.339-.264.43-.341c.416-.347.637-.218.723-.13c.1.104.145.419-.093.696c-.25.29-.51.465-.735.602c-.165.1-.46.087-.582-.063c-.238-.242-.014-.561.256-.764");
}

.sxlwo8bvv {
  stop-color: var(--svg-color--bc826b, #BC826B);
}

.t_55psbku {
  stop-color: var(--svg-color--e0aa8f, #E0AA8F);
  stop-opacity: 0;
}

.t02y35b0p {
  stop-color: var(--svg-color--d5a38f, #D5A38F);
  stop-opacity: 0;
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u04tkobit {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.462 9.93a.14.14 0 0 0-.168.028a.134.134 0 0 0-.015.17c.159.241.435.4.75.4c.314 0 .59-.16.749-.4l-.063-.041l.063.041a.135.135 0 0 0-.015-.171a.14.14 0 0 0-.168-.028a1.2 1.2 0 0 1-.567.135a1.24 1.24 0 0 1-.566-.134Z");
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u39dyibqi {
  stop-color: var(--svg-color--dba697, #DBA697);
  stop-opacity: 0;
}

.u7w80gbza {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 10.107a.21.21 0 1 1 .283.31l-1.819 1.667l.84.086a.21.21 0 1 1-.043.418l-1.211-.124l-.954.874a.21.21 0 0 1-.284-.31z");
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.uktlcdafx {
  stop-color: var(--svg-color--dd4920, #DD4920);
  stop-opacity: 0;
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.un08nrbhl {
  stop-color: var(--svg-color--ff6737, #FF6737);
  stop-opacity: 0;
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.utdakeidf {
  stop-color: var(--svg-color--ff7e38, #FF7E38);
  stop-opacity: 0;
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v0q_-i93u {
  stop-color: var(--svg-color--ff8045, #FF8045);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vksxc-bek {
  d: path("m15.862 8.572l-.23.797c-.047.164.066.329.226.329h.34c.16 0 .274-.167.227-.329l-.23-.797c-.05-.177-.281-.177-.333 0");
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.vudwjbw9p {
  stop-color: var(--svg-color--b5737a, #B5737A);
}

.vvvf-bx0b {
  stop-color: var(--svg-color--93efff, #93EFFF);
}

.vw5e4lbve {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
}

.vxhtc9kgk {
  stop-color: var(--svg-color--8bd2ff, #8BD2FF);
}

.w4_s79ciy {
  stop-color: var(--svg-color--e1a58b, #E1A58B);
  stop-opacity: 0;
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wh1uu6biy {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 10.107a.21.21 0 1 0-.284.31l1.82 1.667l-.84.086a.21.21 0 1 0 .043.418l1.21-.124l.955.874a.21.21 0 0 0 .284-.31z");
}

.wm2hnkwbm {
  stop-color: var(--svg-color--ffceac, #FFCEAC);
  stop-opacity: 0;
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x09-01b7i {
  stop-color: var(--svg-color--634689, #634689);
}

.x356vlupl {
  d: path("m13.318 30.43l-.057-7.86l2.32.062l-.438 7.053a.47.47 0 0 1-.216.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.x36zqabyv {
  stop-color: var(--svg-color--c45538, #C45538);
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.xn221gbbe {
  fill: var(--svg-color--e7ae99, #E7AE99);
  d: path("m17.672 22.117l-.082-.227l2.331-.48c.02.062.094.292.219.71c.125.42-.01.774-.094.9l-3.269 5.343c-.07.116-.233.128-.311.018c-.297-.422-.547-.975-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.033a.6.6 0 0 0 .019-.453");
}

.xnxf0re5w {
  stop-color: var(--svg-color--ff7e38, #FF7E38);
}

.xo-vurl-f {
  stop-color: var(--svg-color--ff6737, #FF6737);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3a7pf3-m {
  d: path("M16.028 10.139c-.22 0-.427-.052-.6-.143c-.06-.03-.124.037-.087.09a.82.82 0 0 0 .687.368a.82.82 0 0 0 .687-.367c.038-.056-.026-.121-.085-.09a1.3 1.3 0 0 1-.602.142");
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y60mf7kqt {
  d: path("M16.052 11.56c-.437.015-1.42.083-1.985.163c-.721.102-.764.711-.764.992v3.68h5.525v-3.68c0-.28-.044-.89-.765-.992a25 25 0 0 0-1.985-.163z");
}

.yj0hglfmq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.88 13.51l2.672 1.045a.1.1 0 0 0 .136-.085l.301-3.57");
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.ynocd3taj {
  d: path("M7.08 15.845c.177-.132.339-.264.43-.341c.416-.347.637-.218.723-.13c.1.104.145.419-.093.696c-.25.29-.51.465-.735.602c-.165.1-.46.087-.582-.063c-.238-.242-.014-.561.256-.764");
}

.yssjiut9l {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.99 8.16a.606.606 0 0 0-.587.459a.12.12 0 0 0 .116.148h.968a.1.1 0 0 0 .099-.118a.61.61 0 0 0-.595-.49");
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_5s59bdn {
  width: 4.843px;
  height: 8.244px;
  rx: 2.422px;
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z0_tnl66g {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
  stop-opacity: 0;
}

.z1f5d8bxu {
  stop-color: var(--svg-color--edba9f, #EDBA9F);
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zd1r_u8ze {
  stop-color: var(--svg-color--6a4e8f, #6A4E8F);
}

.zeih87brn {
  stop-color: var(--svg-color--e43423, #E43423);
  stop-opacity: 0;
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zx2ao6bwg {
  stop-color: var(--svg-color--d79c86, #D79C86);
}

.zx4dgabxp {
  d: path("m17.397 27.35l-.62 1.013c-.07.116-.233.128-.311.018c-.297-.422-.547-.975-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.zzvmqj-9b {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M18.181 9.181q.026-.412.048-.826a.415.415 0 0 1-.048.826");
}

</style>
