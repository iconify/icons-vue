<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9C1dsb)"><path fill="url(#iEfCROd)" clip-rule="evenodd" class="fxebzcbao"/><path fill="url(#ix5kqdI)" clip-rule="evenodd" class="fxebzcbao"/><path fill="url(#isAFsIb)" clip-rule="evenodd" class="fxebzcbao"/><path fill="url(#iXQS0Be)" clip-rule="evenodd" class="fxebzcbao"/><path fill="url(#iE4yuCb)" clip-rule="evenodd" class="fxebzcbao"/><path fill="url(#i6sVCLb)" clip-rule="evenodd" class="fxebzcbao"/><path fill="url(#itnZRWd)" clip-rule="evenodd" class="fxebzcbao"/><path fill="url(#iLT3MBc)" clip-rule="evenodd" class="fxebzcbao"/><path fill="url(#iANNb5d)" clip-rule="evenodd" class="fxebzcbao"/><path fill="url(#ilPVh5b)" clip-rule="evenodd" class="fxebzcbao"/><path fill="url(#iZRn9ac)" clip-rule="evenodd" class="fxebzcbao"/></g><path fill="url(#ipvcy7b)" class="jp58o3bhq"/><path fill="url(#ib1sGud)" class="jp58o3bhq"/><path fill="url(#iWRumQE)" class="jp58o3bhq"/><path fill="url(#i6XyzKG)" class="jp58o3bhq"/><rect fill="url(#iujuxmd)" class="pxr8kjbqc"/><path class="k6ummzbci"/><path fill="url(#iEyAqle)" class="ts_wq_bxu"/><path fill="url(#idvTSFb)" class="ts_wq_bxu"/><path fill="url(#iGQHJad)" class="ts_wq_bxu"/><path clip-rule="evenodd" class="o4v243bdo"/><path fill="url(#iZEuWrb)" clip-rule="evenodd" class="nwwtj9q3g"/><path fill="url(#i9SjLic)" clip-rule="evenodd" class="nwwtj9q3g"/><path fill="url(#iDIrcnb)" clip-rule="evenodd" class="nwwtj9q3g"/><path clip-rule="evenodd" class="fp5lppsnk"/><path fill="url(#iq5j2KY)" clip-rule="evenodd" class="g6-zffq2b"/><path fill="url(#itJvQgd)" clip-rule="evenodd" class="g6-zffq2b"/><path fill="url(#i32CDZc)" clip-rule="evenodd" class="g6-zffq2b"/><path clip-rule="evenodd" class="akzuo5bpr"/><path fill="url(#i2Njsbg)" clip-rule="evenodd" class="mwnrq4ake"/><path fill="url(#iQZ1Ltb)" clip-rule="evenodd" class="mwnrq4ake"/><path fill="url(#ixRFciv)" clip-rule="evenodd" class="mwnrq4ake"/><g filter="url(#ivdbyjb)"><path clip-rule="evenodd" class="b2eqz1d3z"/><path fill="url(#i08dOCY)" clip-rule="evenodd" class="r0gqz1bbx"/><path fill="url(#iXvTPle)" clip-rule="evenodd" class="r0gqz1bbx"/><path fill="url(#ixmRBsc)" clip-rule="evenodd" class="r0gqz1bbx"/></g><g filter="url(#iNoa5Lb)"><path class="i6257ybpa"/><path fill="url(#iOskFCV)" class="djjsb4buj"/><path fill="url(#iALYrkD)" class="djjsb4buj"/><path fill="url(#iLGGpme)" class="djjsb4buj"/><path fill="url(#itGQmke)" class="djjsb4buj"/></g><path fill="url(#ii1Thgc)" class="g49-w_nhp"/><path fill="url(#iGBmING)" class="g49-w_nhp"/><g filter="url(#iNN4Zwe)"><path fill="url(#iEgorTc)" class="y_0marbfe"/><path fill="url(#iguEwpc)" class="y_0marbfe"/><path fill="url(#iW1EUrb)" class="y_0marbfe"/><path fill="url(#ia5CaNb)" class="y_0marbfe"/></g><g filter="url(#iihXrdd)"><path fill="url(#iwiifzO)" class="x67e85bvm"/></g><g filter="url(#iexLNgd)"><path fill="url(#isp3Yhb)" class="pn7htbb7a"/><path fill="url(#ijsAxvd)" class="pn7htbb7a"/></g><g filter="url(#iRPNHac)"><path class="m5uf-i3dg"/><path fill="url(#iSIPj6R)" class="dmbx2gb4h"/></g><g filter="url(#iyzECic)"><path class="ut3yglbrm"/><path fill="url(#ieDKS5K)" class="vvslhvb1i"/></g><g filter="url(#i2nQi2c)"><path fill="url(#iznXREd)" class="g-g5nmzrm"/><path fill="url(#izc1YJb)" class="g-g5nmzrm"/><path fill="url(#iAg6gqb)" class="g-g5nmzrm"/><path fill="url(#iK4mYId)" class="g-g5nmzrm"/><path fill="url(#ie2Maee)" class="g-g5nmzrm"/><path fill="url(#iBLkerf)" class="g-g5nmzrm"/><path fill="url(#iSCTnvN)" class="g-g5nmzrm"/></g><path fill="url(#i8nE91b)" class="g-g5nmzrm"/><g filter="url(#i0RmtDb)"><path class="eu5swu2pg"/></g><g filter="url(#i6OBXJd)"><path class="yuznx_b3m"/><path fill="url(#iEhwnmq)" class="w7gj2-b-j"/><path fill="url(#i6XZLje)" class="w7gj2-b-j"/><path fill="url(#idr9z4b)" class="w7gj2-b-j"/><path fill="url(#ieAbU4F)" class="w7gj2-b-j"/></g><path fill="url(#iWrMeOb)" class="w7gj2-b-j"/><path fill="url(#iLhKirb)" class="w7gj2-b-j"/><path stroke="url(#ijNzpAd)" class="qph1s-bus"/><g filter="url(#iOpWA8b)"><path class="alvmdcn_t"/></g><g filter="url(#iNSWpLb)"><path class="jj87csbbd"/></g><g filter="url(#i1UWXqc)"><path class="eat-7mbvm"/></g><g filter="url(#ia5CIUb)"><path clip-rule="evenodd" class="ax8f3oeat"/></g><path class="jx1phikud"/><path fill="url(#iMgzk6b)" class="s4dp04b5n"/><path class="lfwtzo3vy"/><g filter="url(#iSHCJFe)"><path class="wjtr_8b7m"/><path fill="url(#iRRBuwd)" class="earyz3b5b"/></g><g filter="url(#i0jJoRc)"><path fill="url(#iDnl1HB)" class="ypgiaqbyr"/></g><path class="itu1ejepq"/><path fill="url(#iJKyluY)" class="t_zqg3fll"/><path class="nadp_sbad"/><g filter="url(#iCZy95d)"><path fill="url(#irKIPne)" class="l85qmfbkp"/></g><g filter="url(#ichkrzq)"><ellipse transform="rotate(-27.914 9.326 12.714)" class="s36s2jwkm"/><ellipse fill="url(#iO1aoib)" transform="rotate(-27.914 9.326 12.714)" class="c91iod8ya"/></g><g filter="url(#i4tNrlc)"><path class="r-jpxq6hk"/></g><g filter="url(#i7Wxyye)"><path class="zhzwipsai"/></g><g filter="url(#iU6sOBc)"><path class="en-b23ayd"/><path fill="url(#iWbIZeb)" class="esx6k-igw"/></g><g filter="url(#iSGhJ8b)"><path class="su7t1tb8b"/><path fill="url(#ib3fI6b)" class="qvim8gwnv"/><path fill="url(#iOa2EVi)" class="qvim8gwnv"/></g><g filter="url(#iRXVEVc)"><path stroke="url(#ifFi9ze)" class="fi-v8hbme"/></g><g filter="url(#i104GQU)"><path class="apk8zabre"/></g><defs><radialGradient id="ix5kqdI" cx="0" cy="0" r="1" gradientTransform="matrix(-.77696 5.8704 -7.33332 -.97058 12.096 16.827)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="isAFsIb" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 1.61 9.88)scale(4.47758 5.88319)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iXQS0Be" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68341 2.20141 -1.69038 -1.29263 6.247 13.892)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iE4yuCb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 .252 7.555)scale(3.18696 2.24493)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i6sVCLb" cx="0" cy="0" r="1" gradientTransform="matrix(1.76974 3.36685 -4.67371 2.45667 7.952 3.23)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="itnZRWd" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.774 7.094)scale(2.62482 3.66815)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iLT3MBc" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 10.185 7.834)scale(2.47237 5.15595)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iANNb5d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62572 .90648 -1.15472 -4.61864 21.377 16.913)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ilPVh5b" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.643 -1.957)scale(3.6058 2.85198)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iZRn9ac" cx="0" cy="0" r="1" gradientTransform="matrix(1.93649 .20312 -.32912 3.13768 4.576 12.463)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ib1sGud" cx="0" cy="0" r="1" gradientTransform="rotate(-128.9 17.85 9.715)scale(14.3752 17.7454)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="prklqobcj"/><stop offset="1" class="ff_veq9dp"/></radialGradient><radialGradient id="iWRumQE" cx="0" cy="0" r="1" gradientTransform="rotate(80.311 -5.976 16.011)scale(6.49895 15.3845)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="qt4ap0b2z"/><stop offset="1" class="f46_0ydpi"/></radialGradient><radialGradient id="i6XyzKG" cx="0" cy="0" r="1" gradientTransform="rotate(-120.904 19.045 8.851)scale(9.57741 4.33562)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="kptn98y8b"/><stop offset="1" class="xy2mpdbhe"/></radialGradient><radialGradient id="iujuxmd" cx="0" cy="0" r="1" gradientTransform="matrix(1.97059 3.60967 -4.23023 2.30936 12.194 20.61)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="t_wx1ic7w"/><stop offset=".826" class="vv2uuzbhk"/></radialGradient><radialGradient id="iEyAqle" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14487 1.17029 -.21646 -.21176 24.027 13.361)" gradientUnits="userSpaceOnUse"><stop class="bo9hvcbia"/><stop offset="1" class="oaq7jebib"/></radialGradient><radialGradient id="idvTSFb" cx="0" cy="0" r="1" gradientTransform="rotate(-70.927 22.554 -8.51)scale(3.10812 1.58159)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="xi-m2-bbj"/><stop offset="1" class="k6zvonvjc"/></radialGradient><radialGradient id="iGQHJad" cx="0" cy="0" r="1" gradientTransform="matrix(-.10937 .79688 -1.21512 -.16677 23.927 14.919)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="wbqt2qbli"/><stop offset="1" class="dne0v_i-i"/></radialGradient><radialGradient id="iZEuWrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.69262 .16923 -.21445 -.87773 29.73 14.425)" gradientUnits="userSpaceOnUse"><stop class="mndo9dbtd"/><stop offset="1" class="v_r0ckpor"/></radialGradient><radialGradient id="iDIrcnb" cx="0" cy="0" r="1" gradientTransform="matrix(.06006 .3203 -3.15066 .59077 27.269 13.903)" gradientUnits="userSpaceOnUse"><stop class="rw_zxacrw"/><stop offset="1" class="rbdoa8bvc"/></radialGradient><radialGradient id="iq5j2KY" cx="0" cy="0" r="1" gradientTransform="matrix(-.68924 .16508 -.20552 -.85808 30.307 14.736)" gradientUnits="userSpaceOnUse"><stop class="mndo9dbtd"/><stop offset="1" class="v_r0ckpor"/></radialGradient><radialGradient id="i32CDZc" cx="0" cy="0" r="1" gradientTransform="matrix(.04435 .29983 -3.0061 .44465 27.874 14.164)" gradientUnits="userSpaceOnUse"><stop class="rw_zxacrw"/><stop offset="1" class="rbdoa8bvc"/></radialGradient><radialGradient id="i2Njsbg" cx="0" cy="0" r="1" gradientTransform="matrix(-.69149 .15913 -.19118 -.83072 30.026 15.198)" gradientUnits="userSpaceOnUse"><stop class="mndo9dbtd"/><stop offset="1" class="v_r0ckpor"/></radialGradient><radialGradient id="ixRFciv" cx="0" cy="0" r="1" gradientTransform="matrix(.0445 .28907 -3.01051 .46342 27.584 14.645)" gradientUnits="userSpaceOnUse"><stop class="rw_zxacrw"/><stop offset="1" class="rbdoa8bvc"/></radialGradient><radialGradient id="i08dOCY" cx="0" cy="0" r="1" gradientTransform="rotate(169.423 13.876 9.323)scale(.90027 1.06791)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="iXvTPle" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 4.734 23.621)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="iOskFCV" cx="0" cy="0" r="1" gradientTransform="matrix(-.96409 .10438 -.11015 -1.0174 29.307 16.002)" gradientUnits="userSpaceOnUse"><stop class="gt1tn_3fh"/><stop offset="1" class="vow3367aq"/></radialGradient><radialGradient id="iALYrkD" cx="0" cy="0" r="1" gradientTransform="matrix(.01563 .10937 -1.46562 .20938 27.428 15.465)" gradientUnits="userSpaceOnUse"><stop class="cfjqw6b0c"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="dnevgg8-j"/></radialGradient><radialGradient id="iLGGpme" cx="0" cy="0" r="1" gradientTransform="rotate(17.232 -40.67 77.179)scale(3.05919 2.83525)" gradientUnits="userSpaceOnUse"><stop class="afpbwtbex"/><stop offset="1" class="oax9jn75q"/></radialGradient><radialGradient id="itGQmke" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 .37501 -.25742 -1.71607 26.378 15.2)" gradientUnits="userSpaceOnUse"><stop class="y7cm8rbzs"/><stop offset="1" class="qvei5-bgn"/></radialGradient><radialGradient id="ii1Thgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05458 -3.66708 0 24.195 17.65)" gradientUnits="userSpaceOnUse"><stop offset=".441" class="sipuclb6i"/><stop offset="1" class="su4gzg9-j"/></radialGradient><radialGradient id="iW1EUrb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1875 0 0 -.57813 24.812 19.489)" gradientUnits="userSpaceOnUse"><stop class="ow11_7b9u"/><stop offset="1" class="n-9oslbsi"/></radialGradient><radialGradient id="isp3Yhb" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 25.796 -13.059)scale(3.52284 4.30122)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="ijsAxvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.69421 .94962 -.26847 .47898 19.013 11.442)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iSIPj6R" cx="0" cy="0" r="1" gradientTransform="matrix(1.94418 -.14462 .11305 1.51981 18.14 13.751)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="ieDKS5K" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55393 0 0 -1.22586 6.56 13.607)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iznXREd" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 6.666 8.231)scale(9.22168 12.3431)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="izc1YJb" cx="0" cy="0" r="1" gradientTransform="rotate(172.574 7.86 7.875)scale(4.49439 4.96102)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iAg6gqb" cx="0" cy="0" r="1" gradientTransform="matrix(1.68342 -4.87761 6.18879 2.13595 9.42 22.352)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iK4mYId" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.90376 -9.14889 0 12.654 13.39)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="osxrdxcsn"/><stop offset="1" class="jlnwlmbay"/></radialGradient><radialGradient id="ie2Maee" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 6.672 8.292)scale(9.06154 15.6012)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iBLkerf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.48177 1.81853 0 15.448 12.376)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iSCTnvN" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.69003 1.93689 0 9.81 12.081)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="i8nE91b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65497 0 0 -8.29951 19.046 14.291)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iEhwnmq" cx="0" cy="0" r="1" gradientTransform="matrix(-.58657 -2.63193 .81114 -.18078 13.495 15.227)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="ieAbU4F" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00358 0 0 -.28057 13.186 15.5)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iLhKirb" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 4.2 9.378)scale(2.14166 2.57394)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="iMgzk6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04467 -1.66167 0 15.294 12.838)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iRRBuwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.29862 -.38482 .5298 -.41113 15 12.946)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJKyluY" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04468 -1.66168 0 9.675 12.838)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iO1aoib" cx="0" cy="0" r="1" gradientTransform="matrix(-.00996 -.63617 .7647 -.01197 9.306 13.12)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWbIZeb" cx="0" cy="0" r="1" gradientTransform="matrix(1.62502 -3.54797 1.81505 .83132 5.2 10.107)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ib3fI6b" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.403 6.4)scale(6.27449 10.2584)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iOa2EVi" cx="0" cy="0" r="1" gradientTransform="matrix(-.27083 1.76044 -3.7875 -.58269 12.755 3.878)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="i9C1dsb" width="19.588" height="20.088" x="2.816" y="1.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/></filter><filter id="ivdbyjb" width="7.879" height="3.847" x="21.349" y="13.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.603922 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/></filter><filter id="iNoa5Lb" width="7.879" height="3.847" x="21.349" y="13.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.67451 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/></filter><filter id="iNN4Zwe" width="6.491" height="11.844" x="20.207" y="18.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/></filter><filter id="iihXrdd" width="4.294" height="4.144" x="4.379" y="11.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/></filter><filter id="iexLNgd" width="4.144" height="4.394" x="16.628" y="11.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/></filter><filter id="iRPNHac" width="3.766" height="3.766" x="16.817" y="11.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".25"/></filter><filter id="iyzECic" width="3.566" height="3.566" x="4.693" y="11.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".2"/></filter><filter id="i2nQi2c" width="13.122" height="14.405" x="5.924" y="7.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/></filter><filter id="i0RmtDb" width="3.417" height="4.453" x="10.567" y="12.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".25"/></filter><filter id="i6OBXJd" width="2.917" height="3.953" x="11.026" y="12.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".125"/></filter><filter id="iOpWA8b" width="3.807" height="1.655" x="13.755" y="11.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/></filter><filter id="iNSWpLb" width="3.807" height="1.655" x="7.407" y="11.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/></filter><filter id="i1UWXqc" width="3.101" height="1.347" x="7.581" y="10.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/></filter><filter id="ia5CIUb" width="3.101" height="1.347" x="14.557" y="10.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/></filter><filter id="iSHCJFe" width=".956" height=".839" x="14.378" y="12.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".05"/></filter><filter id="i0jJoRc" width="1.033" height="1.061" x="15.488" y="12.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".1"/></filter><filter id="iCZy95d" width="1.155" height="1.224" x="9.767" y="12.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".1"/></filter><filter id="ichkrzq" width="1.118" height=".85" x="8.766" y="12.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".05"/></filter><filter id="i4tNrlc" width="2.738" height="1.086" x="14.682" y="10.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".1"/></filter><filter id="i7Wxyye" width="2.738" height="1.086" x="7.662" y="10.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".1"/></filter><filter id="iU6sOBc" width="5.193" height="5.581" x="4.518" y="4.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/><feGaussianBlur result="effect2_foregroundBlur_4002_3802" stdDeviation=".15"/></filter><filter id="iSGhJ8b" width="11.131" height="7.301" x="8.489" y="3.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3802"/><feGaussianBlur result="effect2_foregroundBlur_4002_3802" stdDeviation=".125"/></filter><filter id="iRXVEVc" width="1.301" height="2.801" x="8.462" y="4.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".1"/></filter><filter id="i104GQU" width="8.344" height="4.41" x="11.701" y="5.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3802" stdDeviation=".5"/></filter><linearGradient id="iEfCROd" x1="18.528" x2="9.765" y1="4.654" y2="20.884" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="ipvcy7b" x1="12.473" x2="12.473" y1="30.864" y2="25.958" gradientUnits="userSpaceOnUse"><stop class="actv8ccua"/><stop offset="1" class="g60esfuqb"/></linearGradient><linearGradient id="i9SjLic" x1="27.732" x2="27.599" y1="15.973" y2="14.716" gradientUnits="userSpaceOnUse"><stop offset=".217" class="sym6onb1o"/><stop offset="1" class="a94kt-bpo"/></linearGradient><linearGradient id="itJvQgd" x1="28.643" x2="28.192" y1="16.309" y2="15.024" gradientUnits="userSpaceOnUse"><stop offset=".217" class="sym6onb1o"/><stop offset="1" class="a94kt-bpo"/></linearGradient><linearGradient id="iQZ1Ltb" x1="28.032" x2="27.914" y1="16.652" y2="15.47" gradientUnits="userSpaceOnUse"><stop offset=".217" class="sym6onb1o"/><stop offset="1" class="a94kt-bpo"/></linearGradient><linearGradient id="ixmRBsc" x1="24.679" x2="26.273" y1="17.102" y2="16.79" gradientUnits="userSpaceOnUse"><stop offset=".585" class="oc3fsgi2c"/><stop offset="1" class="v-pv693fm"/></linearGradient><linearGradient id="iGBmING" x1="23.574" x2="23.574" y1="18.601" y2="18.426" gradientUnits="userSpaceOnUse"><stop offset=".316" class="gublzhv6p"/><stop offset="1" class="crzqbdcxn"/></linearGradient><linearGradient id="iEgorTc" x1="24.445" x2="24.445" y1="19.665" y2="38.977" gradientUnits="userSpaceOnUse"><stop class="eh67o3baq"/><stop offset=".621" class="fhdfn3b2i"/></linearGradient><linearGradient id="iguEwpc" x1="27.859" x2="22.432" y1="29.192" y2="29.192" gradientUnits="userSpaceOnUse"><stop class="p82q4v34p"/><stop offset=".458" class="aw40h5l5c"/><stop offset="1" class="p82q4v34p"/></linearGradient><linearGradient id="ia5CaNb" x1="23.403" x2="23.403" y1="18.505" y2="19.54" gradientUnits="userSpaceOnUse"><stop offset=".366" class="kj63bk6ym"/><stop offset="1" class="weadzoqrn"/></linearGradient><linearGradient id="iwiifzO" x1="4.379" x2="8.19" y1="13.719" y2="13.719" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="i6XZLje" x1="11.276" x2="12.485" y1="15.321" y2="15.321" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="idr9z4b" x1="12.485" x2="12.485" y1="16.349" y2="15.564" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iWrMeOb" x1="12.585" x2="12.585" y1="16.316" y2="16.136" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="ijNzpAd" x1="11.114" x2="11.708" y1="18.165" y2="17.247" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iDnl1HB" x1="16.296" x2="15.892" y1="12.907" y2="13.156" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irKIPne" x1="10.633" x2="10.229" y1="12.907" y2="13.156" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifFi9ze" x1="8.762" x2="9.463" y1="5.625" y2="7.266" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-tipping-hand-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a94kt-bpo {
  stop-color: var(--svg-color--d79e92, #D79E92);
  stop-opacity: 0;
}

.actv8ccua {
  stop-color: var(--svg-color--9069d4, #9069D4);
}

.adnp-y-dh {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
  stop-opacity: 0;
}

.afpbwtbex {
  stop-color: var(--svg-color--e9b091, #E9B091);
}

.akzuo5bpr {
  fill: var(--svg-color--f1c1a6, #F1C1A6);
  fill-rule: evenodd;
  d: path("M30.023 15.33a.85.85 0 0 1-.773.92a28 28 0 0 0-1.26.162l-.03.005c-.525.074-1.133.16-1.787.23a.85.85 0 1 1-.182-1.69a50 50 0 0 0 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.alvmdcn_t {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M13.955 12.874c.342-.601.862-1.076 1.98-1.076c.49 0 .962.136 1.381.475c.346.28.3.637.032.771l-.716.41c-.84-.272-1.767-.309-2.677-.58");
}

.apk8zabre {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m15.583 8.223l-1.835.338a.886.886 0 1 1-.161-1.758H16.6c1.783 0 2.373 1.797 2.445 2.41a4.05 4.05 0 0 0-3.463-.99");
}

.aw40h5l5c {
  stop-color: var(--svg-color--9f77e5, #9F77E5);
}

.ax8207b9e {
  stop-color: var(--svg-color--e4b833, #E4B833);
  stop-opacity: 0;
}

.ax8f3oeat {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m17.29 10.728l-.178.296za.345.345 0 0 1-.356.593l-.005-.004l-.028-.015l-.118-.06a4 4 0 0 0-.44-.174c-.374-.119-.867-.208-1.381-.118a.345.345 0 0 1-.12-.68c.66-.117 1.273 0 1.71.14a4 4 0 0 1 .72.308l.012.007l.003.002h.002z");
}

.b2eqz1d3z {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M25.66 14.279c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.247c.917-.103 1.759-.207 2.234-.31a.825.825 0 0 0-.345-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.493.05");
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bo9hvcbia {
  stop-color: var(--svg-color--ffd6bb, #FFD6BB);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.c91iod8ya {
  cx: 9.326px;
  cy: 12.714px;
  rx: 0.502px;
  ry: 0.254px;
}

.cfjqw6b0c {
  stop-color: var(--svg-color--e9b4a0, #E9B4A0);
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

.crzqbdcxn {
  stop-color: var(--svg-color--533b7c, #533B7C);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.djjsb4buj {
  d: path("M25.66 14.279c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.873-.095 1.181-.192c.243-.076.5-.218.96-.305c.917-.103 1.759-.207 2.234-.31a.825.825 0 0 0-.345-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.493.05");
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dmbx2gb4h {
  d: path("M18.7 14.99a1.383 1.383 0 1 0 0-2.766a1.383 1.383 0 0 0 0 2.766");
}

.dne0v_i-i {
  stop-color: var(--svg-color--fdceb3, #FDCEB3);
  stop-opacity: 0;
}

.dnevgg8-j {
  stop-color: var(--svg-color--e9b4a0, #E9B4A0);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.earyz3b5b {
  d: path("M15.213 12.466c.081.11-.09.243-.284.389c-.195.145-.34.248-.421.138c-.082-.11.01-.316.204-.461s.419-.175.5-.066");
}

.eat-7mbvm {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m8.11 11.317l-.006.003a.345.345 0 0 1-.355-.592l.002-.001l.004-.002l.012-.007l.042-.024a4 4 0 0 1 .677-.284c.438-.14 1.05-.257 1.71-.14a.345.345 0 1 1-.12.68c-.513-.09-1.006 0-1.38.119a3.5 3.5 0 0 0-.586.248");
}

.eh67o3baq {
  stop-color: var(--svg-color--8860cb, #8860CB);
}

.en-b23ayd {
  fill: var(--svg-color--232121, #232121);
  d: path("M5.958 5.896c.728-.772 2.106-.773 2.743-.658l.51 1.662c-.326-.05-.616.065-.86.302c-.577 1.623-2.562 2.518-3.482 2.763c-.19-1.921.14-3.065 1.088-4.07");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.esx6k-igw {
  d: path("M5.958 5.896c.728-.772 2.106-.773 2.743-.658l.51 1.662c-.326-.05-.616.065-.86.302c-.577 1.623-2.562 2.518-3.482 2.763c-.19-1.921.14-3.065 1.088-4.07");
}

.eu5swu2pg {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m11.98 13.32l-.88 2.189c-.14.45.195.9.67.9h1.012c.475 0 .81-.457.67-.9l-.684-2.19c-.147-.484-.635-.484-.789 0");
}

.f46_0ydpi {
  stop-color: var(--svg-color--8460bf, #8460BF);
  stop-opacity: 0;
}

.ff_veq9dp {
  stop-color: var(--svg-color--8e6bd1, #8E6BD1);
  stop-opacity: 0;
}

.fhdfn3b2i {
  stop-color: var(--svg-color--8560c7, #8560C7);
}

.fi-v8hbme {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.762 5.183c.03.313.302 1.49.701 2.201");
}

.fp5lppsnk {
  fill: var(--svg-color--f1c1a6, #F1C1A6);
  fill-rule: evenodd;
  d: path("M30.294 14.772a.85.85 0 0 1-.689.985q-.18.031-.413.076a30 30 0 0 1-2.733.41a.85.85 0 0 1-.16-1.693a27 27 0 0 0 2.552-.383l.459-.085a.85.85 0 0 1 .984.69");
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fxebzcbao {
  fill-rule: evenodd;
  d: path("M21.737 15.422c.273-.56.417-1.186.417-1.838a4.2 4.2 0 0 0-.346-1.68h.007a4 4 0 0 0-.363-.661l-.002-.004a4.17 4.17 0 0 1-.678-2.28v-.014a4.25 4.25 0 0 0-4.248-4.248a.7.7 0 0 1-.586-.3a4.26 4.26 0 0 0-3.453-1.772c-1.42 0-2.685.704-3.454 1.773a.73.73 0 0 1-.586.3h-.11a4.25 4.25 0 0 0-4.138 4.247v.013a4.17 4.17 0 0 1-.678 2.28l-.003.006a4.25 4.25 0 0 0-.283 4.178a.66.66 0 0 1 0 .586a4.2 4.2 0 0 0-.417 1.812a4.14 4.14 0 0 0 4.144 4.143h11.05a4.14 4.14 0 0 0 4.144-4.143c0-.652-.157-1.265-.417-1.812a.66.66 0 0 1 0-.586M5.95 11.98h-.016l1.544 3.033c.158 3.608 1.567 0 5.007 0s4.94 4.016 5.098.408l1.463-4.117c-.07-1.603-1.231-1.715-1.463-1.715h-4.146A4.97 4.97 0 0 1 9.33 7.435a.34.34 0 0 0-.594.066l-.105.25a2.97 2.97 0 0 1-1.598 1.615l-.066.027c-.304.157-1.017.63-1.043 1.852l.013.394z");
}

.g-g5nmzrm {
  d: path("M5.934 11.98h.016l-.013-.34l-.013-.395c.026-1.222.739-1.695 1.043-1.852l.066-.027l.066-.026A2.97 2.97 0 0 0 8.63 7.75l.106-.25a.34.34 0 0 1 .594-.065a4.97 4.97 0 0 0 4.107 2.155h4.146c.232 0 1.394.112 1.463 1.715l-.153 3.957c-.159 3.608-2.977 6.032-6.417 6.032S6.218 18.87 6.06 15.262z");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g49-w_nhp {
  d: path("M21.106 17.81a.25.25 0 0 1 .25-.25h4.093a.25.25 0 0 1 .25.25v1.64h-4.593z");
}

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g6-zffq2b {
  fill-rule: evenodd;
  d: path("M30.294 14.772a.85.85 0 0 1-.689.985q-.18.031-.413.076a30 30 0 0 1-2.733.41a.85.85 0 0 1-.16-1.693a27 27 0 0 0 2.552-.383l.459-.085a.85.85 0 0 1 .984.69");
}

.g60esfuqb {
  stop-color: var(--svg-color--8d66ce, #8D66CE);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gt1tn_3fh {
  stop-color: var(--svg-color--ffd3bf, #FFD3BF);
}

.gublzhv6p {
  stop-color: var(--svg-color--533b7c, #533B7C);
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

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i6257ybpa {
  fill: var(--svg-color--f4c2ab, #F4C2AB);
  d: path("M25.66 14.279c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.873-.095 1.181-.192c.243-.076.5-.218.96-.305c.917-.103 1.759-.207 2.234-.31a.825.825 0 0 0-.345-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.493.05");
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.itu1ejepq {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.406 11.874a1.8 1.8 0 0 0-1.745 1.363a.353.353 0 0 0 .345.439h2.873a.296.296 0 0 0 .292-.35a1.804 1.804 0 0 0-1.765-1.453");
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jc2cbvyjw {
  stop-color: var(--svg-color--886658, #886658);
  stop-opacity: 0;
}

.jj87csbbd {
  fill: var(--svg-color--272528, #272528);
  d: path("M11.014 12.874c-.341-.601-.86-1.076-1.98-1.076c-.489 0-.96.136-1.38.475c-.347.28-.3.637-.032.771l.716.41c.839-.272 1.767-.309 2.676-.58");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jlnwlmbay {
  stop-color: var(--svg-color--b87c8d, #B87C8D);
}

.jp58o3bhq {
  d: path("M12.473 20.298c-5.523 0-10 4.478-10 10v.051h20v-.05c0-5.523-4.477-10-10-10");
}

.jx1phikud {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.563 11.874c.841 0 1.552.58 1.745 1.363a.353.353 0 0 1-.345.439H14.09a.296.296 0 0 1-.292-.35a1.8 1.8 0 0 1 1.765-1.453");
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k6ummzbci {
  fill: var(--svg-color--eaaf9f, #EAAF9F);
  d: path("M21.349 16.052h4.015v2.016h-4.015z");
}

.k6zvonvjc {
  stop-color: var(--svg-color--dea689, #DEA689);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kj63bk6ym {
  stop-color: var(--svg-color--8d67cd, #8D67CD);
}

.kptn98y8b {
  stop-color: var(--svg-color--613ea5, #613EA5);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l85qmfbkp {
  d: path("M10.722 13.238c0-.372-.302-.62-.383-.694l-.372.36l.229.464z");
}

.lfwtzo3vy {
  fill: var(--svg-color--000, #000);
  d: path("M14.639 13.373c0-.366.292-.659.658-.659a.655.655 0 0 1 .585.962h-1.165a.6.6 0 0 1-.078-.303");
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

.m5uf-i3dg {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M18.7 14.99a1.383 1.383 0 1 0 0-2.766a1.383 1.383 0 0 0 0 2.766");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mndo9dbtd {
  stop-color: var(--svg-color--ffd4bc, #FFD4BC);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mwnrq4ake {
  fill-rule: evenodd;
  d: path("M30.023 15.33a.85.85 0 0 1-.773.92a28 28 0 0 0-1.26.162l-.03.005c-.525.074-1.133.16-1.787.23a.85.85 0 1 1-.182-1.69a50 50 0 0 0 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n-9oslbsi {
  stop-color: var(--svg-color--a681e6, #A681E6);
  stop-opacity: 0;
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.nadp_sbad {
  fill: var(--svg-color--000, #000);
  d: path("M10.33 13.373a.655.655 0 0 0-.658-.659a.655.655 0 0 0-.585.962h1.165a.65.65 0 0 0 .079-.303");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.nwwtj9q3g {
  fill-rule: evenodd;
  d: path("M29.716 14.444a.85.85 0 0 1-.69.984q-.222.04-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 1 1-.16-1.693c.909-.086 1.678-.246 2.317-.38q.39-.082.716-.142a.85.85 0 0 1 .985.69");
}

.o4v243bdo {
  fill: var(--svg-color--f1c1a6, #F1C1A6);
  fill-rule: evenodd;
  d: path("M29.716 14.444a.85.85 0 0 1-.69.984q-.222.04-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 1 1-.16-1.693c.909-.086 1.678-.246 2.317-.38q.39-.082.716-.142a.85.85 0 0 1 .985.69");
}

.oaq7jebib {
  stop-color: var(--svg-color--ebb99c, #EBB99C);
}

.oax9jn75q {
  stop-color: var(--svg-color--e9b091, #E9B091);
  stop-opacity: 0;
}

.oc3fsgi2c {
  stop-color: var(--svg-color--ffca38, #FFCA38);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.osxrdxcsn {
  stop-color: var(--svg-color--cd949b, #CD949B);
  stop-opacity: 0;
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ow11_7b9u {
  stop-color: var(--svg-color--a681e6, #A681E6);
}

.p82q4v34p {
  stop-color: var(--svg-color--9f77e5, #9F77E5);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn7htbb7a {
  d: path("M18.7 15.679a2.072 2.072 0 1 0 0-4.144a2.072 2.072 0 0 0 0 4.143");
}

.prklqobcj {
  stop-color: var(--svg-color--8e6bd1, #8E6BD1);
}

.pxr8kjbqc {
  width: 4.898px;
  height: 6.68px;
  x: 10.035px;
  y: 17.271px;
  rx: 2.449px;
}

.qph1s-bus {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.678 16.868a.25.25 0 0 0-.302.053a.24.24 0 0 0-.025.3a2.538 2.538 0 0 0 4.268 0a.24.24 0 0 0-.026-.303a.25.25 0 0 0-.3-.05h-.001a3.8 3.8 0 0 1-1.807.438a3.84 3.84 0 0 1-1.807-.439Z");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qt4ap0b2z {
  stop-color: var(--svg-color--503876, #503876);
}

.qvei5-bgn {
  stop-color: var(--svg-color--ffd2b6, #FFD2B6);
  stop-opacity: 0;
}

.qvim8gwnv {
  d: path("M11.708 3.575c-1.459-.322-2.768 1.133-2.92 1.673c1.355 4.564 4.782 4.314 8.164 3.939c2.025-.225 2.245.697 2.418 1.143c0-5.063-4.307-6.014-7.625-6.747z");
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

.r-jpxq6hk {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.982 10.552c.415-.101 1.448-.051 2.139.443");
}

.r0gqz1bbx {
  fill-rule: evenodd;
  d: path("M25.66 14.279c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.247c.917-.103 1.759-.207 2.234-.31a.825.825 0 0 0-.345-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.493.05");
}

.rbdoa8bvc {
  stop-color: var(--svg-color--dda695, #DDA695);
  stop-opacity: 0;
}

.rtamvw1ka {
  stop-color: var(--svg-color--e4b833, #E4B833);
}

.rw_zxacrw {
  stop-color: var(--svg-color--dda695, #DDA695);
}

.s36s2jwkm {
  cx: 9.326px;
  cy: 12.714px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.502px;
  ry: 0.254px;
}

.s4dp04b5n {
  d: path("M15.297 12.224a1.15 1.15 0 0 1 1.107 1.452h-2.22a1.154 1.154 0 0 1 1.113-1.452");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sipuclb6i {
  stop-color: var(--svg-color--7c65a2, #7C65A2);
}

.sn-83pben {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.su4gzg9-j {
  stop-color: var(--svg-color--604789, #604789);
}

.su7t1tb8b {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M11.708 3.575c-1.459-.322-2.768 1.133-2.92 1.673c1.355 4.564 4.782 4.314 8.164 3.939c2.025-.225 2.245.697 2.418 1.143c0-5.063-4.307-6.014-7.625-6.747z");
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.sym6onb1o {
  stop-color: var(--svg-color--d79e92, #D79E92);
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.t_wx1ic7w {
  stop-color: var(--svg-color--c48983, #C48983);
}

.t_zqg3fll {
  d: path("M9.672 12.224a1.15 1.15 0 0 0-1.107 1.452h2.22q.04-.148.042-.303a1.157 1.157 0 0 0-1.155-1.15");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.ts_wq_bxu {
  d: path("M22.121 14.138c-.554.649-.74 1.417-.761 1.758l1.847-.102l.887-1.183c.29-.383.54-1.02-.035-1.442c-.466-.342-.946-.066-1.102.106c-.062.057-.248.245-.836.863");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ut3yglbrm {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M6.476 14.99a1.383 1.383 0 1 0 0-2.766a1.383 1.383 0 0 0 0 2.766");
}

.v_r0ckpor {
  stop-color: var(--svg-color--ffd4bc, #FFD4BC);
  stop-opacity: 0;
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v-pv693fm {
  stop-color: var(--svg-color--ffca38, #FFCA38);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vow3367aq {
  stop-color: var(--svg-color--ffd3bf, #FFD3BF);
  stop-opacity: 0;
}

.vv2uuzbhk {
  stop-color: var(--svg-color--e7b2a4, #E7B2A4);
}

.vvslhvb1i {
  d: path("M6.476 14.99a1.383 1.383 0 1 0 0-2.766a1.383 1.383 0 0 0 0 2.766");
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w7gj2-b-j {
  d: path("m11.992 13.141l-.684 2.19c-.14.45.196.9.67.9h1.013c.475 0 .81-.457.67-.9l-.684-2.19c-.147-.485-.83-.485-.985 0");
}

.wbqt2qbli {
  stop-color: var(--svg-color--fdceb3, #FDCEB3);
}

.weadzoqrn {
  stop-color: var(--svg-color--8d67cd, #8D67CD);
  stop-opacity: 0;
}

.wjtr_8b7m {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.213 12.466c.081.11-.09.243-.284.389c-.195.145-.34.248-.421.138c-.082-.11.01-.316.204-.461s.419-.175.5-.066");
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.x67e85bvm {
  d: path("M6.451 15.679a2.072 2.072 0 1 0 0-4.144a2.072 2.072 0 0 0 0 4.143");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xi-m2-bbj {
  stop-color: var(--svg-color--dea689, #DEA689);
  stop-opacity: 0;
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xy2mpdbhe {
  stop-color: var(--svg-color--6c4da8, #6C4DA8);
  stop-opacity: 0;
}

.y_0marbfe {
  d: path("M20.207 19.305a.8.8 0 0 1 .8-.8h4.79a.8.8 0 0 1 .8.8V30.35h-6.39z");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y7cm8rbzs {
  stop-color: var(--svg-color--ffd2b6, #FFD2B6);
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.ypgiaqbyr {
  d: path("M16.32 13.221a1.1 1.1 0 0 0-.297-.595l-.335.367l.151.294z");
}

.yuznx_b3m {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m11.992 13.141l-.684 2.19c-.14.45.196.9.67.9h1.013c.475 0 .81-.457.67-.9l-.684-2.19c-.147-.485-.83-.485-.985 0");
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zhzwipsai {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.1 10.552c-.415-.101-1.447-.051-2.138.443");
}

</style>
