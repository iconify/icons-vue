<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ie0DIOb)" class="odq2frbdh"/><path fill="url(#iik7kQo)" class="odq2frbdh"/><path fill="url(#iO2aVKU)" class="odq2frbdh"/><rect fill="url(#idJOUxd)" class="o9uu_2vuf"/><rect fill="url(#i60Fxdc)" class="o9uu_2vuf"/><path fill="url(#iFHmW8d)" class="lpley2bsg"/><path fill="url(#ifbmyGd)" class="pz8_28qcs"/><path fill="url(#iNp5okb)" class="pz8_28qcs"/><g filter="url(#il9ONST)"><path fill="url(#iHp4mYb)" class="ixbfuabjj"/></g><path fill="url(#ibbCVHc)" class="ixbfuabjj"/><path fill="url(#iznVBXd)" class="ixbfuabjj"/><path fill="url(#ionan1b)" class="ixbfuabjj"/><path fill="url(#iBumctb)" class="ixbfuabjj"/><g filter="url(#ic01VyJ)"><path fill="url(#iUZRlhj)" class="h2xwtmsbp"/></g><path fill="url(#iarKPDe)" class="h2xwtmsbp"/><path fill="url(#iXuO5le)" class="typsz0bol"/><path fill="url(#i0X1xSO)" class="typsz0bol"/><path fill="url(#iZryelb)" class="ucn3t8bax"/><path fill="url(#iFmBYxe)" class="ucn3t8bax"/><g filter="url(#iu9MgkW)"><path fill="url(#iKRmxYi)" class="waa-du_vw"/></g><path fill="url(#iFwvaSb)" class="waa-du_vw"/><path fill="url(#iQqKrnb)" class="waa-du_vw"/><path fill="url(#isXTwJd)" class="waa-du_vw"/><path fill="url(#i0fHJUS)" class="waa-du_vw"/><path fill="url(#iH96sPp)" class="waa-du_vw"/><path fill="url(#iDiQtyb)" class="waa-du_vw"/><path fill="url(#ikHxfsc)" class="waa-du_vw"/><path fill="url(#iZj6TXd)" class="waa-du_vw"/><g filter="url(#iGTzQye)"><path fill="url(#ignQWqe)" class="lfngynbrp"/><path fill="url(#iGqWLYc)" class="lfngynbrp"/></g><g filter="url(#iMbYtve)"><path class="uc3b21bfi"/></g><g filter="url(#iDndRAc)"><path fill="url(#iaasmod)" class="bodi9cbuz"/><path fill="url(#iJmBB6b)" class="bodi9cbuz"/><path fill="url(#iRkUeod)" class="bodi9cbuz"/><path fill="url(#iqdEEKA)" class="bodi9cbuz"/></g><path fill="url(#iZXvHee)" class="bodi9cbuz"/><path fill="url(#iQgDxxc)" class="bodi9cbuz"/><g filter="url(#i6zAYJd)"><path fill="url(#iqNBPSd)" class="b8nnexb5p"/><path fill="url(#iy5QjJd)" class="b8nnexb5p"/><path fill="url(#ipaWSVc)" class="b8nnexb5p"/><path fill="url(#i2MI43b)" class="b8nnexb5p"/><path fill="url(#in8skcc)" class="b8nnexb5p"/></g><g filter="url(#iaBFyoe)"><path fill="url(#ihXfyfb)" class="zzea4bbqx"/><path fill="url(#iUnOwoZ)" class="zzea4bbqx"/></g><g filter="url(#ih0z9wd)"><path fill="url(#in3p8Hc)" class="cw071zyqa"/><path fill="url(#isOJFgH)" class="cw071zyqa"/><path fill="url(#iXMQLlb)" class="cw071zyqa"/><path fill="url(#ilWChfc)" class="cw071zyqa"/><path fill="url(#if3saab)" class="cw071zyqa"/><path fill="url(#irw74Jd)" class="cw071zyqa"/></g><path class="t2b1-wbzj"/><path fill="url(#ihq7HXb)" class="o42d_2bna"/><path class="d5ugpc7em"/><g filter="url(#i7PscNc)"><path class="higcaqbpi"/><path fill="url(#i3D3vQX)" class="cxhyadbjn"/></g><g filter="url(#iJA77rc)"><path fill="url(#ioL4jnd)" class="o4juuzb9t"/></g><path class="bc3kv3p-z"/><path fill="url(#ie0tN5d)" class="uduws1bzt"/><path class="j3f_wvu9s"/><g filter="url(#iDOHBbe)"><path fill="url(#iBqszhQ)" class="o2sp2tsmp"/></g><g filter="url(#ivEuCZb)"><ellipse transform="rotate(-27.914 13.593 9.823)" class="jpy7iebfx"/><ellipse fill="url(#iR6oeQk)" transform="rotate(-27.914 13.593 9.823)" class="idrb2tbum"/></g><path fill="url(#i9P3SVc)" class="ea7ahmb_f"/><path fill="url(#i85yAbr)" class="ea7ahmb_f"/><path fill="url(#iqrFrzd)" class="ea7ahmb_f"/><path fill="url(#iBoubnc)" class="fjtc1u_ge"/><path fill="url(#i1XcVve)" class="fjtc1u_ge"/><g filter="url(#iUAFBDc)"><path class="mdvrtgbgb"/></g><g filter="url(#i36ZEue)"><path class="flszi8b0x"/></g><path class="pc1egccfa"/><path stroke="url(#imurK4b)" class="ckbs2ta8j"/><path stroke="url(#iyvBiqb)" class="ckbs2ta8j"/><g filter="url(#i7XGYQB)"><rect class="fp2dmrb-a"/></g><g filter="url(#iLE4JJJ)"><rect class="h1hxgyi4v"/></g><g filter="url(#iF5sqIc)"><path stroke="url(#iUshx8b)" class="hble2nbkw"/></g><g filter="url(#io4vUkd)"><path stroke="url(#i5wl30b)" class="sm0cbnoxy"/></g><defs><radialGradient id="ie0DIOb" cx="0" cy="0" r="1" gradientTransform="matrix(2.02197 9.09668 -14.16842 3.14929 14.022 14.59)" gradientUnits="userSpaceOnUse"><stop class="khj8zwb0j"/><stop offset=".674" class="dt2jwkbti"/></radialGradient><radialGradient id="iik7kQo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.71875 9.5625 0 21.73 24.313)" gradientUnits="userSpaceOnUse"><stop class="osixu2bon"/><stop offset="1" class="bh4gs6bci"/></radialGradient><radialGradient id="idJOUxd" cx="0" cy="0" r="1" gradientTransform="rotate(52.035 -8.964 24.325)scale(2.78619 3.42691)" gradientUnits="userSpaceOnUse"><stop offset=".538" class="b58g3-6da"/><stop offset="1" class="ysjgknbtw"/></radialGradient><radialGradient id="i60Fxdc" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 1 -1.28354 1.60442 13.918 16.625)" gradientUnits="userSpaceOnUse"><stop class="zk54m10rq"/><stop offset="1" class="ywf36c2jd"/></radialGradient><radialGradient id="iNp5okb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -9.0144 10.168 23.313)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="pyz9maawt"/><stop offset="1" class="j5lcx07ey"/></radialGradient><radialGradient id="iHp4mYb" cx="0" cy="0" r="1" gradientTransform="matrix(14.39624 1.34674 -.26918 2.87749 16.71 24.842)" gradientUnits="userSpaceOnUse"><stop class="x_9jb4iuy"/><stop offset="1" class="cfq47bcav"/></radialGradient><radialGradient id="iznVBXd" cx="0" cy="0" r="1" gradientTransform="rotate(65.433 -11.819 26.48)scale(1.97537 5.884)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="is-0rhbbm"/><stop offset="1" class="fck5k55yv"/></radialGradient><radialGradient id="ionan1b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.4754 2.06133 -.26488 -.8321 28.572 23.91)" gradientUnits="userSpaceOnUse"><stop class="sy10t1blt"/><stop offset=".823" class="uoc50wrxw"/></radialGradient><radialGradient id="iBumctb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.255 12.758 9.535)scale(3.73328 6.83692)" gradientUnits="userSpaceOnUse"><stop class="y9563heqw"/><stop offset=".499" class="ro3n8bb9m"/></radialGradient><radialGradient id="iUZRlhj" cx="0" cy="0" r="1" gradientTransform="matrix(.71233 3.34406 -18.37025 3.9131 16.143 24.53)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="klmwqzbpd"/><stop offset=".676" class="k9fw32bwy"/></radialGradient><radialGradient id="iarKPDe" cx="0" cy="0" r="1" gradientTransform="matrix(2.50774 .0418 -.1419 8.51383 4.806 26.265)" gradientUnits="userSpaceOnUse"><stop class="ua64_qbcm"/><stop offset="1" class="tx6k9cbae"/></radialGradient><radialGradient id="iXuO5le" cx="0" cy="0" r="1" gradientTransform="rotate(103.679 6.167 14.37)scale(3.25769 3.86989)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="g_go8-i7v"/><stop offset="1" class="t6hj3nbht"/></radialGradient><radialGradient id="i0X1xSO" cx="0" cy="0" r="1" gradientTransform="rotate(40.236 -6.175 34.627)scale(.4278 .55097)" gradientUnits="userSpaceOnUse"><stop class="ic7m27p6x"/><stop offset="1" class="a8f8wslpf"/></radialGradient><radialGradient id="iZryelb" cx="0" cy="0" r="1" gradientTransform="matrix(1.27281 2.6796 -1.218 .57855 10.5 11.892)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iFmBYxe" cx="0" cy="0" r="1" gradientTransform="matrix(.17916 1.19265 -1.0462 .15716 11.3 11.687)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iKRmxYi" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22357 0 0 -9.24044 18.85 10.834)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iQqKrnb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14205 12.95235 -10.72609 -.94575 17.624 4.926)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="zgchiqbcj"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="isXTwJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.33981 1.65801 0 18.49 9.715)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="i0fHJUS" cx="0" cy="0" r="1" gradientTransform="matrix(-.05801 -1.1025 1.19977 -.06313 13.807 9.578)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iH96sPp" cx="0" cy="0" r="1" gradientTransform="matrix(1.20583 0 0 6.12894 11.167 11.219)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iDiQtyb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6126 -3.651 .82695 .59176 10.196 7.836)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="ikHxfsc" cx="0" cy="0" r="1" gradientTransform="rotate(-103.259 13.845 1.161)scale(10.5149 11.5824)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iZj6TXd" cx="0" cy="0" r="1" gradientTransform="matrix(2.0432 .72015 -.43201 1.2257 18 5.457)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iQgDxxc" cx="0" cy="0" r="1" gradientTransform="rotate(135.131 6.31 8.901)scale(2.59348 1.64842)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="iy5QjJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.62968 6.43107 0 10.819 9.254)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="ipaWSVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.62968 6.43107 0 20.9 9.254)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="i2MI43b" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 10.348 -.365)scale(3.47737 1.85193)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="in8skcc" cx="0" cy="0" r="1" gradientTransform="matrix(.90437 1.47379 -3.4126 2.0941 15.14 1.391)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="ihXfyfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8038 1.37245 -.38199 -1.05869 16.297 2.832)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iUnOwoZ" cx="0" cy="0" r="1" gradientTransform="matrix(3.21553 -5.09127 5.6406 3.56248 10.618 7.588)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="in3p8Hc" cx="0" cy="0" r="1" gradientTransform="matrix(3.383 .80017 -.44751 1.89202 19.662 3.992)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="isOJFgH" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.059 -1.8)scale(4.2783 2.38598)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="iXMQLlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3063 -2.20048 1.57611 -.93564 20.55 8.293)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="ilWChfc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79449 1.15026 -1.24348 -5.18303 20.834 3.875)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="if3saab" cx="0" cy="0" r="1" gradientTransform="rotate(107.002 8.36 9.087)scale(.40094 1.83304)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="irw74Jd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99293 3.75147 -9.67396 -5.13919 19.49 2.928)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="ihq7HXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81066 -1.28944 0 18.224 9.919)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i3D3vQX" cx="0" cy="0" r="1" gradientTransform="matrix(-.23173 -.29861 .41112 -.31903 17.996 10.003)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ie0tN5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8107 -1.2895 0 13.864 9.919)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iR6oeQk" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49368 .59342 -.0093 13.58 10.138)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i85yAbr" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 3.78 18.587)scale(2.32776 2.22086)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iqrFrzd" cx="0" cy="0" r="1" gradientTransform="matrix(.78713 -1.08022 .90544 .65978 21.018 10.477)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="i1XcVve" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67364 -.24475 .24062 -1.64535 11.133 10.576)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="imurK4b" cx="0" cy="0" r="1" gradientTransform="matrix(.1551 -.37929 .9046 .36994 16.805 14.13)" gradientUnits="userSpaceOnUse"><stop class="b-3kupbsz"/><stop offset="1" class="s0jns0b-x"/></radialGradient><radialGradient id="iyvBiqb" cx="0" cy="0" r="1" gradientTransform="matrix(.22073 -.23925 .16376 .15108 14.842 14.13)" gradientUnits="userSpaceOnUse"><stop class="b-3kupbsz"/><stop offset="1" class="s0jns0b-x"/></radialGradient><linearGradient id="iO2aVKU" x1="17.426" x2="17.426" y1="30.357" y2="26.753" gradientUnits="userSpaceOnUse"><stop class="s9luuo8wr"/><stop offset="1" class="mw-dyzb9n"/></linearGradient><linearGradient id="iFHmW8d" x1="22.967" x2="24.881" y1="22.469" y2="22.469" gradientUnits="userSpaceOnUse"><stop offset=".17" class="h-4-uqb4q"/><stop offset="1" class="k-xmaur5i"/></linearGradient><linearGradient id="ifbmyGd" x1="8.98" x2="6.915" y1="23.313" y2="22.849" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ev32s2_gl"/><stop offset="1" class="p1zhkctql"/></linearGradient><linearGradient id="ibbCVHc" x1="16.051" x2="16.387" y1="29.707" y2="25.82" gradientUnits="userSpaceOnUse"><stop class="ctxk_2lah"/><stop offset="1" class="jds31ob1y"/></linearGradient><linearGradient id="iFwvaSb" x1="21.197" x2="16.848" y1="12.518" y2="12.518" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="ignQWqe" x1="15.537" x2="16.333" y1="14.385" y2="14.188" gradientUnits="userSpaceOnUse"><stop class="ily6j2bos"/><stop offset=".522" class="kvpu6ac4h"/></linearGradient><linearGradient id="iGqWLYc" x1="16.096" x2="16.096" y1="14.771" y2="14.419" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iwyvod12c"/><stop offset="1" class="pufnejoro"/></linearGradient><linearGradient id="iaasmod" x1="16.044" x2="16.898" y1="11.662" y2="11.662" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iJmBB6b" x1="14.972" x2="16.045" y1="11.507" y2="11.566" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iRkUeod" x1="16.044" x2="16.044" y1="12.061" y2="12.912" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iqdEEKA" x1="16.044" x2="16.044" y1="9.815" y2="10.234" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iZXvHee" x1="16.175" x2="16.175" y1="12.734" y2="12.675" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="iqNBPSd" x1="21.403" x2="11.288" y1="5.176" y2="5.176" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="ioL4jnd" x1="19.002" x2="18.688" y1="9.973" y2="10.166" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBqszhQ" x1="14.607" x2="14.294" y1="9.973" y2="10.166" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9P3SVc" x1="22.475" x2="21.269" y1="9.999" y2="12.174" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iBoubnc" x1="10.199" x2="11.656" y1="10.703" y2="10.576" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="iUshx8b" x1="19.475" x2="16.657" y1="8.711" y2="8.711" gradientUnits="userSpaceOnUse"><stop offset=".333" class="t-ltb0bxu"/><stop offset="1" class="mycwy9ulq"/></linearGradient><linearGradient id="i5wl30b" x1="14.968" x2="12.151" y1="8.711" y2="8.711" gradientUnits="userSpaceOnUse"><stop offset=".333" class="t-ltb0bxu"/><stop offset="1" class="mycwy9ulq"/></linearGradient><filter id="il9ONST" width="19.161" height="7.244" x="8.205" y="22.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.435294 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4644"/></filter><filter id="ic01VyJ" width="19.009" height="7.177" x="5.218" y="22.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.470588 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4644"/></filter><filter id="iu9MgkW" width="10.962" height="12.532" x="10.985" y="4.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4644"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13036_4644" result="effect2_innerShadow_13036_4644"/></filter><filter id="iGTzQye" width="1.224" height=".712" x="15.437" y="14.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".05"/></filter><filter id="iMbYtve" width="3.753" height="4.821" x="13.899" y="9.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".5"/></filter><filter id="iDndRAc" width="2.076" height="3.098" x="15.006" y="9.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".05"/></filter><filter id="i6zAYJd" width="12.862" height="8.35" x="9.613" y="1.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4644"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13036_4644" result="effect2_innerShadow_13036_4644"/></filter><filter id="iaBFyoe" width="7.079" height="6.487" x="9.718" y="2.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".25"/></filter><filter id="ih0z9wd" width="6.856" height="6.231" x="15.635" y="2.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".25"/></filter><filter id="i7PscNc" width=".786" height=".696" x="17.491" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".05"/></filter><filter id="iJA77rc" width=".891" height=".913" x="18.33" y="9.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".1"/></filter><filter id="iDOHBbe" width=".986" height="1.04" x="13.891" y="9.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".1"/></filter><filter id="ivEuCZb" width=".912" height=".704" x="13.137" y="9.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".05"/></filter><filter id="iUAFBDc" width="1.328" height="2.378" x="10.016" y="9.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".125"/></filter><filter id="i36ZEue" width="1.446" height="2.402" x="20.752" y="9.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".125"/></filter><filter id="i7XGYQB" width="2.748" height=".641" x="12.456" y="8.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.282353 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4644"/></filter><filter id="iLE4JJJ" width="2.748" height=".641" x="16.975" y="8.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.282353 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4644"/></filter><filter id="iF5sqIc" width="2.77" height=".7" x="16.984" y="8.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".125"/></filter><filter id="io4vUkd" width="2.77" height=".7" x="12.477" y="8.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4644" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-pouting-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.a8f8wslpf {
  stop-color: var(--svg-color--e6b489, #E6B489);
  stop-opacity: 0;
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.b-3kupbsz {
  stop-color: var(--svg-color--e7b19e, #E7B19E);
}

.b58g3-6da {
  stop-color: var(--svg-color--cb705b, #CB705B);
}

.b8nnexb5p {
  d: path("M20.895 4.197a2.32 2.32 0 0 1 1.267 1.05c.466.82.397 1.8-.106 2.524a1.56 1.56 0 0 0-.27.874v1.187a1.7 1.7 0 0 0-.667-.268l.078-1.605a1.45 1.45 0 0 0-1.378-1.43H18.42a2.42 2.42 0 0 1-2.21-1.443a.66.66 0 0 0-.615-.418h-1.271c-1.844 0-3.339 1.512-3.339 3.377l.03 1.536a1.7 1.7 0 0 0-.719.263V8.645c0-.31-.095-.616-.27-.874a2.39 2.39 0 0 1-.143-2.443a2.34 2.34 0 0 1 1.298-1.126a2.68 2.68 0 0 0 1.383-1.11a2.32 2.32 0 0 1 2.889-.91c.381.166.81.166 1.192 0a2.4 2.4 0 0 1 .911-.188c.843 0 1.58.456 1.988 1.131c.307.51.79.879 1.351 1.072");
}

.bc3kv3p-z {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.655 9.17c-.652 0-1.204.45-1.354 1.058c-.044.175.09.34.268.34h2.23a.23.23 0 0 0 .226-.27a1.4 1.4 0 0 0-1.37-1.128");
}

.bh4gs6bci {
  stop-color: var(--svg-color--ff6646, #FF6646);
  stop-opacity: 0;
}

.bodi9cbuz {
  d: path("m15.662 10.12l-.531 1.837c-.108.378.152.756.52.756h.786c.368 0 .628-.384.52-.756l-.53-1.837c-.115-.407-.646-.407-.765 0");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cfq47bcav {
  stop-color: var(--svg-color--e8b39b, #E8B39B);
}

.ckbs2ta8j {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.197 14.13c.488-.335 1.211-.336 1.705 0a.28.28 0 0 0 .314-.46c-.682-.466-1.656-.466-2.335 0a.28.28 0 0 0 .316.46");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctxk_2lah {
  stop-color: var(--svg-color--b97586, #B97586);
}

.cw071zyqa {
  d: path("m21.253 8.593l-.03-.631c-.01-.763-.64-1.392-1.404-1.424H18.42a2.42 2.42 0 0 1-2.122-1.259s-.058-.135-.12-.366c-.256-.97.671-1.713 1.656-1.522c.972.189 2.08.517 2.898 1.05c1.743 1.138 1.438 3.187.52 4.152");
}

.cxhyadbjn {
  d: path("M18.16 9.63c.064.086-.069.19-.22.302c-.15.113-.263.192-.326.107c-.064-.085.007-.245.158-.358s.325-.135.389-.05");
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d5ugpc7em {
  fill: var(--svg-color--000, #000);
  d: path("M17.716 10.334c0-.284.227-.51.51-.51a.51.51 0 0 1 .454.745h-.904a.46.46 0 0 1-.06-.235");
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dt2jwkbti {
  stop-color: var(--svg-color--fc4a2b, #FC4A2B);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.ea7ahmb_f {
  d: path("M20.962 12.174q.101-1.594.184-3.189a1.608 1.608 0 0 1-.184 3.189");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ev32s2_gl {
  stop-color: var(--svg-color--ff5437, #FF5437);
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

.fck5k55yv {
  stop-color: var(--svg-color--a7666b, #A7666B);
  stop-opacity: 0;
}

.fjtc1u_ge {
  d: path("M10.994 8.977a1.608 1.608 0 0 0 .139 3.197a78 78 0 0 1-.139-3.197");
}

.flszi8b0x {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M21.002 11.524q.058-.951.11-1.902a.955.955 0 0 1-.11 1.902");
}

.fp2dmrb-a {
  width: 2.648px;
  height: 0.541px;
  x: 12.456px;
  y: 8.487px;
  fill: var(--svg-color--945e2e, #945E2E);
  rx: 0.271px;
}

.ft5dv1b6b {
  fill: none;
}

.g_go8-i7v {
  stop-color: var(--svg-color--ffdcaf, #FFDCAF);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
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

.h-4-uqb4q {
  stop-color: var(--svg-color--ff491d, #FF491D);
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h1hxgyi4v {
  width: 2.648px;
  height: 0.541px;
  x: 16.975px;
  y: 8.487px;
  fill: var(--svg-color--935d2c, #935D2C);
  rx: 0.271px;
}

.h2xwtmsbp {
  d: path("M5.668 28.531c-.6-1.05-.453-2.812-.375-3.597l3.937-.168c.413.212 1.527.088 2.032 0l9.672-1.563c.617-.117 1.448-.177 2.125.188c.728.392.7.965.642 1.352a.1.1 0 0 1-.064.077c-4.285 1.54-12.404 4.814-13.524 5.063c-1.82.312-3.695-.04-4.445-1.352");
}

.hble2nbkw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.334 8.71h2.07");
}

.higcaqbpi {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.16 9.63c.064.086-.069.19-.22.302c-.15.113-.263.192-.326.107c-.064-.085.007-.245.158-.358s.325-.135.389-.05");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.ic7m27p6x {
  stop-color: var(--svg-color--e6b489, #E6B489);
}

.idrb2tbum {
  cx: 13.593px;
  cy: 9.823px;
  rx: 0.389px;
  ry: 0.197px;
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.ily6j2bos {
  stop-color: var(--svg-color--d89e89, #D89E89);
}

.is-0rhbbm {
  stop-color: var(--svg-color--a7666b, #A7666B);
}

.iwyvod12c {
  stop-color: var(--svg-color--dfa78b, #DFA78B);
}

.ixbfuabjj {
  d: path("M26.417 28.531c.6-1.05.453-2.812.375-3.597l-3.938-.168c-.412.212-1.526.088-2.03 0l-8.898-1.407c-.617-.117-2.097-.231-2.774.133c-.765.412-1 1.193-.937 1.578c4.27 1.532 12.632 4.563 13.757 4.813c1.82.312 3.695-.04 4.445-1.352");
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j3f_wvu9s {
  fill: var(--svg-color--000, #000);
  d: path("M14.373 10.334a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.745h.904a.5.5 0 0 0 .06-.235");
}

.j5lcx07ey {
  stop-color: var(--svg-color--e45b4e, #E45B4E);
}

.jds31ob1y {
  stop-color: var(--svg-color--b97586, #B97586);
  stop-opacity: 0;
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jpy7iebfx {
  cx: 13.593px;
  cy: 9.823px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.k-xmaur5i {
  stop-color: var(--svg-color--ff6747, #FF6747);
}

.k9fw32bwy {
  stop-color: var(--svg-color--eaad9f, #EAAD9F);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.khj8zwb0j {
  stop-color: var(--svg-color--a72503, #A72503);
}

.klmwqzbpd {
  stop-color: var(--svg-color--fac5a7, #FAC5A7);
}

.kvpu6ac4h {
  stop-color: var(--svg-color--d39278, #D39278);
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lfngynbrp {
  d: path("M16.56 14.641a.512.512 0 0 0-1.023 0z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lpley2bsg {
  d: path("M22.967 17.937a10.48 10.48 0 0 1 3.827 7.019l-3.827-.18z");
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdvrtgbgb {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M11.011 9.637a.955.955 0 0 0 .083 1.878a78 78 0 0 1-.083-1.878");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mw-dyzb9n {
  stop-color: var(--svg-color--d73726, #D73726);
  stop-opacity: 0;
}

.mycwy9ulq {
  stop-color: var(--svg-color--a26e44, #A26E44);
  stop-opacity: 0;
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.o2sp2tsmp {
  d: path("M14.677 10.23c0-.29-.235-.481-.298-.54l-.288.28l.177.36z");
}

.o42d_2bna {
  d: path("M18.226 9.442a.892.892 0 0 1 .86 1.127h-1.723a.895.895 0 0 1 .863-1.127");
}

.o4juuzb9t {
  d: path("M19.02 10.216a.84.84 0 0 0-.23-.462l-.26.285l.117.228z");
}

.o9uu_2vuf {
  width: 4.223px;
  height: 6.028px;
  x: 13.918px;
  y: 12.688px;
  rx: 2.111px;
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

.odq2frbdh {
  d: path("m9.2 24.75l-3.906.183c.577-5.253 5.03-9.34 10.436-9.34h.625c5.415 0 9.872 4.099 10.44 9.363l-4.378-.206v5.188H9.2z");
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.osixu2bon {
  stop-color: var(--svg-color--ff6547, #FF6547);
}

.p1zhkctql {
  stop-color: var(--svg-color--ff3a19, #FF3A19);
}

.pc1egccfa {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M15.197 14.13c.488-.335 1.211-.336 1.705 0a.28.28 0 0 0 .314-.46c-.682-.466-1.656-.466-2.335 0a.28.28 0 0 0 .316.46");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pufnejoro {
  stop-color: var(--svg-color--dfa78b, #DFA78B);
  stop-opacity: 0;
}

.pyz9maawt {
  stop-color: var(--svg-color--e45b4e, #E45B4E);
  stop-opacity: 0;
}

.pz8_28qcs {
  d: path("m5.294 24.934l3.847-.16l.058.182h.031v-7.109a10.5 10.5 0 0 0-3.936 7.086");
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
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

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.ro3n8bb9m {
  stop-color: var(--svg-color--c99575, #C99575);
  stop-opacity: 0;
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.s0jns0b-x {
  stop-color: var(--svg-color--e7b19e, #E7B19E);
  stop-opacity: 0;
}

.s9luuo8wr {
  stop-color: var(--svg-color--d73726, #D73726);
}

.sm0cbnoxy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.827 8.71h2.07");
}

.sy10t1blt {
  stop-color: var(--svg-color--efbc96, #EFBC96);
}

.t-ltb0bxu {
  stop-color: var(--svg-color--a26e44, #A26E44);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t2b1-wbzj {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.433 9.17c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.268.34H17.29a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.126");
}

.t6hj3nbht {
  stop-color: var(--svg-color--d89e98, #D89E98);
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tx6k9cbae {
  stop-color: var(--svg-color--d49c7d, #D49C7D);
  stop-opacity: 0;
}

.typsz0bol {
  d: path("M20.901 12.083c.335-.01.649-.124.904-.308v.93a2.17 2.17 0 0 1-1.34 2.017c.17-.362.288-.757.346-1.179z");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.ua64_qbcm {
  stop-color: var(--svg-color--d49c7d, #D49C7D);
}

.uc3b21bfi {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.614 10.498l-.692 1.655c-.1.377.142.755.486.755h.735c.344 0 .587-.383.486-.755l-.496-1.837c-.107-.407-.408-.225-.52.182");
}

.ucn3t8bax {
  d: path("M11.187 12.083a1.64 1.64 0 0 1-.904-.308v.93a2.17 2.17 0 0 0 1.34 2.017a4 4 0 0 1-.346-1.179z");
}

.uduws1bzt {
  d: path("M13.862 9.442a.892.892 0 0 0-.86 1.127h1.723a1 1 0 0 0 .033-.235a.9.9 0 0 0-.896-.892");
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uoc50wrxw {
  stop-color: var(--svg-color--efbc96, #EFBC96);
  stop-opacity: 0;
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.waa-du_vw {
  d: path("M11.223 13.597A3.91 3.91 0 0 0 15.106 17h1.885a3.91 3.91 0 0 0 3.882-3.403c.118-1.882.237-3.757.324-5.638a1.45 1.45 0 0 0-1.378-1.43H18.42a2.42 2.42 0 0 1-2.21-1.443a.66.66 0 0 0-.615-.418h-1.271c-1.845 0-3.339 1.512-3.339 3.377c0 1.859.116 3.688.238 5.552");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x_9jb4iuy {
  stop-color: var(--svg-color--e1af9c, #E1AF9C);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y9563heqw {
  stop-color: var(--svg-color--c99575, #C99575);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.ysjgknbtw {
  stop-color: var(--svg-color--f2a07f, #F2A07F);
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.ywf36c2jd {
  stop-color: var(--svg-color--c77457, #C77457);
  stop-opacity: 0;
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zgchiqbcj {
  stop-color: var(--svg-color--b36e91, #B36E91);
  stop-opacity: 0;
}

.zk54m10rq {
  stop-color: var(--svg-color--c77457, #C77457);
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

.zzea4bbqx {
  d: path("M16.276 5.223a2 2 0 0 1-.066-.137a.66.66 0 0 0-.615-.418h-1.271c-1.844 0-3.339 1.512-3.339 3.377v.275c-.34-.259-.767-.804-.767-1.687c0-1.07.781-1.612 1.28-1.957c.14-.098.258-.18.33-.253l.1-.105c.349-.37.97-1.03 2.057-1.319a5.5 5.5 0 0 1 1.506-.165c.473.011.806.42.806.893V5.21z");
}

</style>
