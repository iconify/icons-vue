<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#im0wb4T)" class="m1i1rlbvk"/><g filter="url(#iDbYhRd)"><path class="u7j5qywzc"/></g><path class="m3se_ob2r"/><path fill="url(#i4RHwye)" class="zqss5obsp"/><path fill="url(#i86fP2c)" class="zqss5obsp"/><path fill="url(#izsTP5b)" class="zqss5obsp"/><path class="llp516bpm"/><path fill="url(#ioCT77d)" class="xn6dhjjio"/><path fill="url(#if8dKTc)" class="xn6dhjjio"/><path fill="url(#i77Ytid)" class="xn6dhjjio"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#i1B5pTu)" class="biuac8r4x"/><path fill="url(#iJIw8ya)" class="biuac8r4x"/><path fill="url(#iItirce)" class="dvr2s59yl"/><path fill="url(#icDYpab)" class="dvr2s59yl"/><path fill="url(#idlbkMe)" class="sp6_o9bxd"/><path fill="url(#iIvEVud)" class="sp6_o9bxd"/><path fill="url(#iXRw9pd)" class="sp6_o9bxd"/><path fill="url(#iz9xh1o)" class="sp6_o9bxd"/><path fill="url(#ixge7fe)" class="sp6_o9bxd"/><g filter="url(#iEtwXyb)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#ineVwFe)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#iSLb5ye)"><path fill="url(#iMmsJpd)" class="ylvkxrbeo"/></g><g filter="url(#iMHG9BT)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#i9sxEsb)" class="u1e8ikbzb"/></g><g filter="url(#iFvt5eb)"><path class="z5g21op2e"/></g><g filter="url(#iOV69He)"><path fill="url(#isxrVvd)" class="pimvl5kot"/><path fill="url(#i21XCBc)" class="pimvl5kot"/><path fill="url(#iHVx6iD)" class="pimvl5kot"/><path fill="url(#iUDUwCb)" class="pimvl5kot"/><path fill="url(#iFlrrrd)" class="pimvl5kot"/></g><g filter="url(#ibPhfMb)"><path stroke="url(#iPBTnvb)" class="cjq4b16bn"/></g><g filter="url(#inELGPv)"><path stroke="url(#iyRmxue)" class="luyfkt2yj"/></g><g filter="url(#iJvMFkb)"><path stroke="url(#ifwhrMe)" class="eqaszhbhb"/></g><path fill="url(#iAZnJLc)" class="qu5q6cbsz"/><path fill="url(#iUrdrdb)" class="h234brbuv"/><path fill="url(#iQCwAnb)" class="yxf-k-bxl"/><path fill="url(#i6vFIwb)" class="e2tg2cc_n"/><g filter="url(#iUBuYgb)"><path fill="url(#iH1EC2c)" class="odh-h5y9a"/></g><path fill="url(#is2D49c)" class="odh-h5y9a"/><path fill="url(#iU71pEd)" class="odh-h5y9a"/><path fill="url(#iS5kTnd)" class="odh-h5y9a"/><path fill="url(#iYplEKb)" class="odh-h5y9a"/><path fill="url(#iiLMTQb)" class="odh-h5y9a"/><path fill="url(#iCDjrMe)" class="odh-h5y9a"/><path fill="url(#iSAzPtd)" class="odh-h5y9a"/><path fill="url(#iDdHMLb)" class="odh-h5y9a"/><g filter="url(#i8LYlpb)"><path class="xs0e2yb0d"/></g><g filter="url(#ioLMH2b)"><path class="rrh--pb6v"/><path fill="url(#iH8Dyhe)" class="z76u9noeq"/><path fill="url(#i4cxKNc)" class="z76u9noeq"/><path fill="url(#i6lO8Yc)" class="z76u9noeq"/><path fill="url(#iSf56md)" class="z76u9noeq"/><path fill="url(#iCX5ZLU)" class="z76u9noeq"/></g><g filter="url(#ij2elOd)"><path stroke="url(#i8FDGgK)" class="aix4qdthi"/></g><path fill="url(#i9MND8r)" class="rv4wjf7ie"/><g filter="url(#i4160Pd)"><path class="f-7ni-7nj"/></g><g filter="url(#iaoUgTd)"><path class="ilyezcbyn"/></g><path class="t07r8bb6h"/><path fill="url(#iJFjdnc)" class="f2ycllbzk"/><path class="f1wg35b2h"/><g filter="url(#i7NR1me)"><path class="k50sudb7r"/><path fill="url(#iNOTHFc)" class="h9gcuo59e"/></g><g filter="url(#iMsVyhc)"><path fill="url(#iMkujDb)" class="vm7tgp74q"/></g><path class="lr220_bmm"/><path fill="url(#i9fqTWz)" class="ghtmfnbno"/><path class="gdt8hkb8k"/><g filter="url(#i9kvwZa)"><path fill="url(#iqSc4Sl)" class="y9ik2ccun"/></g><g filter="url(#iB6zA6d)"><ellipse transform="rotate(-27.914 13.291 9.82)" class="lmfl49mdi"/><ellipse fill="url(#iYqXJce)" transform="rotate(-27.914 13.291 9.82)" class="n3mq3mesa"/></g><path fill="url(#ixmLglc)" class="h3e2z0b-y"/><path fill="url(#i1Iyxzb)" class="h3e2z0b-y"/><path fill="url(#iXgRhwb)" class="h3e2z0b-y"/><path fill="url(#i4qxymd)" class="h3e2z0b-y"/><path fill="url(#igzGIee)" class="vfpak8x9j"/><path fill="url(#iro8L8b)" class="vfpak8x9j"/><g filter="url(#i0Rsn3c)"><path fill="url(#izemmhc)" class="b4py8r56b"/></g><g filter="url(#imSTbEd)"><path fill="url(#icAXIGb)" class="v2bzfsbql"/></g><g filter="url(#i6rgLbc)"><path class="qfyyuxb6j"/></g><g filter="url(#iQBwgLd)"><path class="dyq9-xbjc"/></g><g filter="url(#iD3l31d)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#iOJCgOd)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="izsTP5b" cx="0" cy="0" r="1" gradientTransform="rotate(131.119 3.397 11.463)scale(2.81867 4.68292)" gradientUnits="userSpaceOnUse"><stop class="qunsngokg"/><stop offset="1" class="zsyglhsdv"/></radialGradient><radialGradient id="i77Ytid" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="f7vxzf2re"/><stop offset="1" class="bjz-35bmd"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="iItirce" cx="0" cy="0" r="1" gradientTransform="rotate(154.424 11.17 15.183)scale(2.44794 2.40172)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="icDYpab" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 27.001 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="ixge7fe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.554 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="iMmsJpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.83984 -1.96094 0 15.76 16.836)" gradientUnits="userSpaceOnUse"><stop class="hq1ja919q"/><stop offset=".66" class="vgx8n2bki"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="i9sxEsb" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.838)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="i21XCBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.364 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iHVx6iD" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.364 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iUDUwCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.364 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iFlrrrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.364 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iQCwAnb" cx="0" cy="0" r="1" gradientTransform="matrix(.7535 2.0323 -2.41422 .89511 20.544 11.786)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="i6vFIwb" cx="0" cy="0" r="1" gradientTransform="matrix(1.4858 .46697 -1.44062 4.58378 9.665 12.28)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="iH1EC2c" cx="0" cy="0" r="1" gradientTransform="matrix(-5.30016 0 0 -9.30648 18.61 10.839)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iU71pEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.4591 -11.2279 0 16.664 4.132)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="ufejd3a2z"/><stop offset="1" class="dsa2ugegn"/></radialGradient><radialGradient id="iS5kTnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15561 1.44074 0 18.244 9.518)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iYplEKb" cx="0" cy="0" r="1" gradientTransform="matrix(.00398 -1.1012 1.2073 .00437 13.431 9.565)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iiLMTQb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.61348 .5398 -1.36879 -21.84145 19.243 11.833)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iCDjrMe" cx="0" cy="0" r="1" gradientTransform="matrix(3.14127 -3.29848 1.20795 1.15037 10.22 6.486)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="iSAzPtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.76727 2.90118 -2.4034 -1.46404 18.224 5.829)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iDdHMLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.05417 -5.84282 0 15.81 6.785)" gradientUnits="userSpaceOnUse"><stop class="xwvfam6la"/><stop offset="1" class="m8utmpb4e"/></radialGradient><radialGradient id="i4cxKNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24565 -.77203 0 16.23 12.208)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iSf56md" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53077 .70184 -1.12791 -2.46006 16.346 11.635)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="i9MND8r" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.7253 2.91804 0 15.76 14.4)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iJFjdnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81645 -1.29865 0 17.956 9.917)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iNOTHFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23338 -.30075 .41406 -.32131 17.726 10.002)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9fqTWz" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81649 -1.29872 0 13.564 9.917)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iYqXJce" cx="0" cy="0" r="1" gradientTransform="matrix(-.00778 -.4972 .59766 -.00936 13.276 10.137)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1Iyxzb" cx="0" cy="0" r="1" gradientTransform="matrix(.63252 2.25746 -2.1538 .60348 20.407 9.93)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iXgRhwb" cx="0" cy="0" r="1" gradientTransform="matrix(.79276 -1.08794 .9119 .6645 20.77 10.479)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="i4qxymd" cx="0" cy="0" r="1" gradientTransform="matrix(.59071 -1.56022 2.08467 .78927 20.885 10.652)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iro8L8b" cx="0" cy="0" r="1" gradientTransform="rotate(-173.036 5.729 4.96)scale(1.63543 1.75526)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="izemmhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.92227 .15831 -.19425 -1.13168 10.863 10.58)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><linearGradient id="im0wb4T" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="d__di5b1k"/><stop offset="1" class="ldn_ouzqy"/></linearGradient><linearGradient id="i4RHwye" x1="14.633" x2="13.974" y1="19.957" y2="19.239" gradientUnits="userSpaceOnUse"><stop class="ptx8-dg4d"/><stop offset="1" class="m1cydckkt"/></linearGradient><linearGradient id="i86fP2c" x1="11.699" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="zsyglhsdv"/></linearGradient><linearGradient id="ioCT77d" x1="19.938" x2="18.313" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="ul2cu2h0c"/></linearGradient><linearGradient id="if8dKTc" x1="17" x2="17.938" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="i1B5pTu" x1="23.473" x2="23.473" y1="29.782" y2="23.532" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="isxrVvd" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="iPBTnvb" x1="23.503" x2="25.212" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iyRmxue" x1="23.425" x2="25.134" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="ifwhrMe" x1="23.503" x2="25.212" y1="28.68" y2="28.68" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iAZnJLc" x1="10.073" x2="10.866" y1="8.346" y2="8.313" gradientUnits="userSpaceOnUse"><stop class="fb1dqpbpv"/><stop offset="1" class="nu57mx1sw"/></linearGradient><linearGradient id="iUrdrdb" x1="20.964" x2="20.964" y1="7.63" y2="9.202" gradientUnits="userSpaceOnUse"><stop class="hcfjk_btp"/><stop offset="1" class="p-7lm7ody"/></linearGradient><linearGradient id="is2D49c" x1="20.992" x2="16.579" y1="12.535" y2="12.535" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iH8Dyhe" x1="16.604" x2="15.76" y1="11.518" y2="11.553" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="i6lO8Yc" x1="15.76" x2="15.76" y1="12.665" y2="12.197" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iCX5ZLU" x1="15.76" x2="15.76" y1="9.813" y2="11.004" gradientUnits="userSpaceOnUse"><stop class="d3s5m_men"/><stop offset="1" class="feyw-gbnv"/></linearGradient><linearGradient id="i8FDGgK" x1="14.551" x2="14.871" y1="14.245" y2="13.405" gradientUnits="userSpaceOnUse"><stop class="rwnwb2y0z"/><stop offset="1" class="ny1jq5bdu"/></linearGradient><linearGradient id="iMkujDb" x1="18.739" x2="18.423" y1="9.971" y2="10.166" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqSc4Sl" x1="14.313" x2="13.997" y1="9.971" y2="10.166" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixmLglc" x1="22.237" x2="21.023" y1="9.998" y2="12.188" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="igzGIee" x1="9.873" x2="11.341" y1="10.707" y2="10.579" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="icAXIGb" x1="21.23" x2="21.23" y1="9.618" y2="11.533" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><filter id="iDbYhRd" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".5"/></filter><filter id="iEtwXyb" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1959"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1959" result="shape"/></filter><filter id="ineVwFe" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1959"/></filter><filter id="iSLb5ye" width="3.922" height="2.04" x="13.799" y="16.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.572549 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1959"/></filter><filter id="iMHG9BT" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1959"/></filter><filter id="iFvt5eb" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".325"/></filter><filter id="iOV69He" width="4.468" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1959"/></filter><filter id="ibPhfMb" width="2.097" height=".3" x="23.353" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".05"/></filter><filter id="inELGPv" width="2.097" height=".3" x="23.275" y="27.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".05"/></filter><filter id="iJvMFkb" width="2.097" height=".3" x="23.353" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".05"/></filter><filter id="iUBuYgb" width="11.362" height="12.62" x="10.63" y="4.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1959"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1959" result="effect2_innerShadow_4002_1959"/></filter><filter id="i8LYlpb" width="3.889" height="4.918" x="13.607" y="9.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".5"/></filter><filter id="ioLMH2b" width="2.289" height="3.318" x="14.616" y="9.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".1"/></filter><filter id="ij2elOd" width="3.639" height="1.48" x="13.941" y="13.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".05"/></filter><filter id="i4160Pd" width="2.353" height="1.197" x="17.359" y="7.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1959"/></filter><filter id="iaoUgTd" width="2.353" height="1.182" x="12.07" y="7.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1959"/></filter><filter id="i7NR1me" width=".791" height=".7" x="17.218" y="9.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".05"/></filter><filter id="iMsVyhc" width=".894" height=".917" x="18.064" y="9.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".1"/></filter><filter id="i9kvwZa" width=".99" height="1.044" x="13.593" y="9.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".1"/></filter><filter id="iB6zA6d" width=".918" height=".708" x="12.832" y="9.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".05"/></filter><filter id="i0Rsn3c" width="1.334" height="2.391" x="9.691" y="9.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".125"/></filter><filter id="imSTbEd" width="1.953" height="2.915" x="20.253" y="9.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".25"/></filter><filter id="i6rgLbc" width="2.116" height=".863" x="12.14" y="7.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".075"/></filter><filter id="iQBwgLd" width="2.116" height=".872" x="17.453" y="7.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1959" stdDeviation=".075"/></filter><filter id="iD3l31d" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1959"/></filter><filter id="iOJCgOd" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1959"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mechanic-light" /></template>
<style>
.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.aix4qdthi {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.389 13.379c.396.207.868.325 1.371.325c.508 0 .975-.119 1.371-.325a.204.204 0 0 1 .243.04a.19.19 0 0 1 .021.242m-3.006-.282l2.964.255m-2.964-.255a.204.204 0 0 0-.243.042a.19.19 0 0 0-.02.24m.263-.282l-.222.255m3.228.027l-.042-.027m.042.027l-.042-.027m.042.027a1.96 1.96 0 0 1-1.635.874c-.686 0-1.289-.35-1.635-.873m3.228-.028c-.337.51-.924.851-1.593.851s-1.256-.34-1.593-.851m-.042.028l.042-.028m-.042.028l.042-.028");
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.b4py8r56b {
  d: path("M10.691 9.634a.962.962 0 0 0 .084 1.891q-.053-.945-.084-1.891");
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.biuac8r4x {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.401-1.54-6.44-3.96-8.457");
}

.bjz-35bmd {
  stop-color: var(--svg-color--d6cbdf, #D6CBDF);
  stop-opacity: 0;
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cjq4b16bn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 25.992H25.3");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d__di5b1k {
  stop-color: var(--svg-color--d2c4ec, #D2C4EC);
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.d3s5m_men {
  stop-color: var(--svg-color--d3a6a2, #D3A6A2);
}

.dsa2ugegn {
  stop-color: var(--svg-color--cb869c, #CB869C);
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.dyq9-xbjc {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.344 8.232c-.284-.3-.904-.512-1.666-.384");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2tg2cc_n {
  d: path("M10.868 12.097a1.65 1.65 0 0 1-.91-.31v.936c0 .899.535 1.7 1.35 2.032a4.1 4.1 0 0 1-.349-1.188z");
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.eqaszhbhb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 28.602H25.3");
}

.f-7ni-7nj {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.517 8.107a1.9 1.9 0 0 0-.692-.414c-.306-.097-.69-.123-1.22-.058a.28.28 0 0 0 .067.554c.485-.06.781-.028.985.036c.2.063.335.165.493.302a.28.28 0 0 0 .367-.42");
}

.f1wg35b2h {
  fill: var(--svg-color--000, #000);
  d: path("M17.444 10.335c0-.286.228-.514.514-.514a.512.512 0 0 1 .457.75h-.91a.5.5 0 0 1-.061-.236");
}

.f2ycllbzk {
  d: path("M17.958 9.437a.898.898 0 0 1 .865 1.135h-1.735a.902.902 0 0 1 .87-1.135");
}

.f7vxzf2re {
  stop-color: var(--svg-color--8e7f98, #8E7F98);
}

.fb1dqpbpv {
  stop-color: var(--svg-color--554743, #554743);
}

.feyw-gbnv {
  stop-color: var(--svg-color--d3a6a2, #D3A6A2);
  stop-opacity: 0;
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.ft5dv1b6b {
  fill: none;
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.gdt8hkb8k {
  fill: var(--svg-color--000, #000);
  d: path("M14.076 10.335a.51.51 0 0 0-.514-.514a.512.512 0 0 0-.457.75h.91a.5.5 0 0 0 .061-.236");
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.ghtmfnbno {
  d: path("M13.562 9.437a.898.898 0 0 0-.865 1.135h1.735a1 1 0 0 0 .032-.237a.904.904 0 0 0-.902-.898");
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.h234brbuv {
  d: path("m20.48 7.284l.82-.28l.147 2.904h-.966z");
}

.h3e2z0b-y {
  d: path("M20.713 12.188q.1-1.605.186-3.211a1.62 1.62 0 0 1-.186 3.211");
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.h9gcuo59e {
  d: path("M17.892 9.627c.064.085-.07.19-.222.303c-.152.114-.265.194-.329.109s.008-.248.16-.361c.152-.114.327-.137.39-.051");
}

.hcfjk_btp {
  stop-color: var(--svg-color--363535, #363535);
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hq1ja919q {
  stop-color: var(--svg-color--e497b2, #E497B2);
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ilyezcbyn {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.328 7.99a2.8 2.8 0 0 1 1.75-.362a.28.28 0 0 1-.068.554a2.23 2.23 0 0 0-1.396.286q-.052.031-.075.049l-.017.012l-.003.002a.28.28 0 0 1-.341-.442z");
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.k50sudb7r {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.892 9.627c.064.085-.07.19-.222.303c-.152.114-.265.194-.329.109s.008-.248.16-.361c.152-.114.327-.137.39-.051");
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.ldn_ouzqy {
  stop-color: var(--svg-color--c6c4d3, #C6C4D3);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llp516bpm {
  fill: var(--svg-color--f4e6ff, #F4E6FF);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.lmfl49mdi {
  cx: 13.291px;
  cy: 9.82px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.392px;
  ry: 0.198px;
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lr220_bmm {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.354 9.163c-.657 0-1.212.453-1.363 1.066a.276.276 0 0 0 .269.343h2.245c.143 0 .258-.13.229-.274a1.41 1.41 0 0 0-1.38-1.135");
}

.luyfkt2yj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.425 27.297h1.797");
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.m1cydckkt {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
  stop-opacity: 0;
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.m3se_ob2r {
  fill: var(--svg-color--eddffd, #EDDFFD);
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.m8utmpb4e {
  stop-color: var(--svg-color--aa8099, #AA8099);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n3mq3mesa {
  cx: 13.291px;
  cy: 9.82px;
  rx: 0.392px;
  ry: 0.198px;
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.nu57mx1sw {
  stop-color: var(--svg-color--282321, #282321);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.ny1jq5bdu {
  stop-color: var(--svg-color--dfaaa1, #DFAAA1);
  stop-opacity: 0;
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odh-h5y9a {
  d: path("M10.905 13.621a3.94 3.94 0 0 0 3.91 3.428h1.898a3.94 3.94 0 0 0 3.91-3.428c.12-1.895.28-4.415.369-6.31c-.011-.771-.661-.777-1.43-.809h-1.409a2.44 2.44 0 0 1-2.226-1.452a.67.67 0 0 0-.619-.42h-1.28c-1.858 0-3.398.803-3.398 2.681c0 1.873.152 4.433.274 6.31");
}

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.p-7lm7ody {
  stop-color: var(--svg-color--272628, #272628);
}

.pimvl5kot {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.39a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.ptx8-dg4d {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qfyyuxb6j {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.366 8.27c.258-.185.903-.511 1.665-.383");
}

.qu5q6cbsz {
  d: path("m10.176 7.066l.864.218v2.624h-.967z");
}

.qunsngokg {
  stop-color: var(--svg-color--7c6987, #7C6987);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rrh--pb6v {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.375 10.12l-.534 1.85c-.11.38.152.76.523.76h.792c.37 0 .633-.386.524-.76l-.535-1.85c-.115-.41-.65-.41-.77 0");
}

.rv4wjf7ie {
  d: path("M15.76 13.754c-.51 0-.99-.12-1.394-.33c-.138-.07-.286.085-.2.21c.338.51.925.851 1.594.851c.67 0 1.256-.34 1.593-.851c.087-.13-.06-.28-.199-.21a3 3 0 0 1-1.394.33");
}

.rwnwb2y0z {
  stop-color: var(--svg-color--dfaaa1, #DFAAA1);
}

.s2-xryl0i {
  d: path("M12.045 6.26c-.68.31-1.29.74-1.89 1.31l.41.51c.31.38.85.49 1.28.25c.76-.42 2.11-.99 3.9-.99s3.14.57 3.9.99a1 1 0 0 0 1.27-.25l.41-.51c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0");
}

.s8-qpgb5g {
  stop-color: var(--svg-color--3b71d9, #3B71D9);
}

.sf2388bnl {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.sp6_o9bxd {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.102-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.t07r8bb6h {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.166 9.164c.657 0 1.213.453 1.364 1.065a.276.276 0 0 1-.27.343h-2.245a.232.232 0 0 1-.229-.274a1.406 1.406 0 0 1 1.38-1.134");
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.u7j5qywzc {
  fill: var(--svg-color--b1a1bf, #B1A1BF);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.ufejd3a2z {
  stop-color: var(--svg-color--d59c9f, #D59C9F);
  stop-opacity: 0;
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.ul2cu2h0c {
  stop-color: var(--svg-color--f0e1ff, #F0E1FF);
  stop-opacity: 0;
}

.unsdl8pjp {
  stop-color: var(--svg-color--9b80b4, #9B80B4);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v2bzfsbql {
  d: path("M20.753 11.533q.059-.957.111-1.915a.962.962 0 0 1-.11 1.915");
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.vfpak8x9j {
  d: path("M10.674 8.969a1.62 1.62 0 0 0 .14 3.22a78 78 0 0 1-.14-3.22");
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vgx8n2bki {
  stop-color: var(--svg-color--e6a4aa, #E6A4AA);
}

.vm7tgp74q {
  d: path("M18.758 10.217a.85.85 0 0 0-.233-.466l-.261.287l.117.23z");
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xn6dhjjio {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.xs0e2yb0d {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.27 10.317l-.638 1.85c-.11.38.153.76.524.76h.791c.371 0 .633-.386.524-.76l-.535-1.85c-.114-.41-.545-.41-.665 0");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xwvfam6la {
  stop-color: var(--svg-color--aa8099, #AA8099);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.y9ik2ccun {
  d: path("M14.383 10.23c0-.29-.236-.484-.3-.543l-.29.28l.178.364z");
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.ylvkxrbeo {
  d: path("M15.71 18.676c-1.524-.508-1.825-1.445-1.91-1.84h3.921c-.356 1.237-1.494 1.738-2.012 1.84");
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yxf-k-bxl {
  d: path("M20.652 12.097a1.65 1.65 0 0 0 .91-.31v.936c0 .899-.535 1.7-1.349 2.032c.171-.365.29-.763.348-1.188z");
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z76u9noeq {
  d: path("m15.375 10.12l-.534 1.85c-.11.38.152.76.523.76h.792c.37 0 .633-.386.524-.76l-.535-1.85c-.115-.41-.65-.41-.77 0");
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zqss5obsp {
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.zsyglhsdv {
  stop-color: var(--svg-color--eee0fe, #EEE0FE);
  stop-opacity: 0;
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

</style>
