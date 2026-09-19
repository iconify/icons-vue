<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igtPXve)" class="m1i1rlbvk"/><g filter="url(#iQAARuc)"><path class="xk18tyb3e"/></g><path class="m3se_ob2r"/><path fill="url(#i4RHwye)" class="zqss5obsp"/><path fill="url(#i86fP2c)" class="zqss5obsp"/><path fill="url(#i23ntQe)" class="zqss5obsp"/><path class="jse2phbtg"/><path fill="url(#i2nIhZb)" class="om0oq7b1v"/><path fill="url(#ivP9Jjb)" class="om0oq7b1v"/><path fill="url(#i77Ytid)" class="om0oq7b1v"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#iTdOGsd)" class="vqc4qgzhu"/><path fill="url(#iJIw8ya)" class="vqc4qgzhu"/><path fill="url(#i1AZebc)" class="dvr2s59yl"/><path fill="url(#iX9JgNb)" class="dvr2s59yl"/><path fill="url(#idlbkMe)" class="rom2yrbwh"/><path fill="url(#iIvEVud)" class="rom2yrbwh"/><path fill="url(#iXRw9pd)" class="rom2yrbwh"/><path fill="url(#iz9xh1o)" class="rom2yrbwh"/><path fill="url(#i6G3R0c)" class="rom2yrbwh"/><g filter="url(#iuVg6sc)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#i9wDzDc)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#i8uRBOb)"><path fill="url(#iazukPe)" class="clmvkjbnc"/></g><g filter="url(#iLkTjeD)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#ixaGDYd)" class="u1e8ikbzb"/></g><g filter="url(#ioQNM4c)"><path class="z5g21op2e"/></g><g filter="url(#iksD7Mc)"><path fill="url(#ifKU5mc)" class="pv8cx5b7o"/><path fill="url(#iSwnSae)" class="pv8cx5b7o"/><path fill="url(#iWwBHGd)" class="pv8cx5b7o"/><path fill="url(#iviU92d)" class="pv8cx5b7o"/><path fill="url(#iJJBG7d)" class="pv8cx5b7o"/></g><g filter="url(#iZBDx9d)"><path stroke="url(#iBO8D2b)" class="cjq4b16bn"/></g><g filter="url(#iOBKU4c)"><path stroke="url(#ijHs0Pe)" class="luyfkt2yj"/></g><g filter="url(#idEWk8c)"><path stroke="url(#i9Ji0Wc)" class="eqaszhbhb"/></g><g filter="url(#iecS7Ic)"><circle fill="url(#iFXEwHe)" class="i9l3p-bcq"/></g><g filter="url(#iRHPcQj)"><circle fill="url(#iSJVN2c)" class="aw8cw698d"/></g><g filter="url(#ikx9KTd)"><circle fill="url(#iPvXZbb)" class="zv9da-f4x"/><circle fill="url(#ilB3Uze)" class="zv9da-f4x"/></g><g filter="url(#ijz1XGe)"><circle class="f6fcfpb9v"/><circle fill="url(#ioF1Bqe)" class="stjis0jjr"/><circle fill="url(#iPpoyrd)" class="stjis0jjr"/></g><g filter="url(#idYYfAb)"><path fill="url(#i4ZTtFd)" class="rivwc6bvt"/><path fill="url(#i0UwqJc)" class="rivwc6bvt"/><path fill="url(#iNd2Yeb)" class="rivwc6bvt"/></g><path fill="url(#icbQRAr)" class="rivwc6bvt"/><path fill="url(#ipNh5ed)" class="rivwc6bvt"/><path fill="url(#iQ3tSje)" class="rivwc6bvt"/><path fill="url(#i3inFBc)" class="rivwc6bvt"/><g filter="url(#iIH34we)"><path class="mg1-gdc7o"/></g><g filter="url(#iCzDGwb)"><path class="kbmw7jb_w"/><path fill="url(#iEDNsCG)" class="wh9pisbrr"/><path fill="url(#i9sVnyc)" class="wh9pisbrr"/><path fill="url(#iPq4Sqd)" class="wh9pisbrr"/><path fill="url(#i13YWFa)" class="wh9pisbrr"/><path fill="url(#iBTgode)" class="wh9pisbrr"/></g><path stroke="url(#ieepKub)" class="ka15ouboj"/><path class="tzpchacdd"/><path fill="url(#ioIXvQV)" class="r5twurbft"/><path class="h8kb9yuhi"/><g filter="url(#iadVQFb)"><path class="f4216ljgk"/><path fill="url(#iQVSHhG)" class="t7nurg72w"/></g><g filter="url(#iUDtKrc)"><path fill="url(#iOu45be)" class="cgtc6ibqv"/></g><path class="v_jlg2buc"/><path fill="url(#i9bTT5d)" class="ghtfcxbsg"/><path class="cd8x4v99k"/><g filter="url(#iUuV92b)"><path fill="url(#iXNhPVt)" class="x5z4x3bnt"/></g><g filter="url(#iI4LnFc)"><ellipse transform="rotate(-27.914 13.238 9.987)" class="hbqpu6bzl"/><ellipse fill="url(#i3FScab)" transform="rotate(-27.914 13.238 9.987)" class="zvz4a-ufu"/></g><g filter="url(#im90CXb)"><path clip-rule="evenodd" class="fmkj8mujh"/></g><g filter="url(#iYlN5tc)"><path clip-rule="evenodd" class="sgo8b74bs"/></g><path fill="url(#iSTZ2xM)" class="uzuk-gbcn"/><path fill="url(#iC0oeWc)" class="r0_bjvbtd"/><g filter="url(#iGBDCBc)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#iFCI3de)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="i23ntQe" cx="0" cy="0" r="1" gradientTransform="rotate(135.74 4.223 11.079)scale(3.58199 4.84976)" gradientUnits="userSpaceOnUse"><stop class="qunsngokg"/><stop offset="1" class="zsyglhsdv"/></radialGradient><radialGradient id="i77Ytid" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="f7vxzf2re"/><stop offset="1" class="bjz-35bmd"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="i1AZebc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 27.592 23.749)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="iX9JgNb" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 27.001 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="i6G3R0c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.553 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="iazukPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53799 -3.27844 0 15.76 17.138)" gradientUnits="userSpaceOnUse"><stop class="e01fo_2bv"/><stop offset="1" class="tkr9c33ir"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="ixaGDYd" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.839)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="iSwnSae" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.364 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iWwBHGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.364 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iviU92d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.364 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iJJBG7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.364 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iFXEwHe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.273 10.765)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="ilB3Uze" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 20.838 10.5)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="ioF1Bqe" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.425 11.588)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iPpoyrd" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.466 10.765)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="i0UwqJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.60345 0 18.057 9.493)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iNd2Yeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.70324 0 13.514 9.627)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iQ3tSje" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.33632 -10.2888 0 15.59 9.23)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="fr9spbcmd"/><stop offset="1" class="ijq7q5b1d"/></radialGradient><radialGradient id="i3inFBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -7.20568 0 15.747 6.775)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="snxda1bhi"/><stop offset="1" class="y8wlns7wu"/></radialGradient><radialGradient id="i13YWFa" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.023 12.374)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="ioIXvQV" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 17.877 10.083)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iQVSHhG" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.648 10.168)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9bTT5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.51 10.083)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i3FScab" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.683 -1.358)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><linearGradient id="igtPXve" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="hzctbo64o"/><stop offset="1" class="ncpoyrbpw"/></linearGradient><linearGradient id="i4RHwye" x1="14.633" x2="13.974" y1="19.957" y2="19.239" gradientUnits="userSpaceOnUse"><stop class="ptx8-dg4d"/><stop offset="1" class="m1cydckkt"/></linearGradient><linearGradient id="i86fP2c" x1="11.699" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="zsyglhsdv"/></linearGradient><linearGradient id="i2nIhZb" x1="19.937" x2="18.312" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="ul2cu2h0c"/></linearGradient><linearGradient id="ivP9Jjb" x1="17" x2="17.937" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="iTdOGsd" x1="23.473" x2="23.473" y1="29.781" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="ifKU5mc" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="iBO8D2b" x1="23.503" x2="25.212" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ijHs0Pe" x1="23.425" x2="25.134" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i9Ji0Wc" x1="23.503" x2="25.212" y1="28.68" y2="28.68" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iSJVN2c" x1="10.944" x2="10.303" y1="11.044" y2="11.044" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iPvXZbb" x1="21.553" x2="20.734" y1="9.673" y2="12.212" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="i4ZTtFd" x1="19.741" x2="12.128" y1="11.155" y2="12.285" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="icbQRAr" x1="10.34" x2="12.215" y1="13.854" y2="13.787" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="ipNh5ed" x1="20.623" x2="19.514" y1="13.012" y2="12.915" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iEDNsCG" x1="14.831" x2="15.77" y1="11.815" y2="11.815" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="i9sVnyc" x1="16.635" x2="15.609" y1="12.138" y2="12.123" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iPq4Sqd" x1="15.891" x2="15.891" y1="12.881" y2="12.307" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iBTgode" x1="15.696" x2="15.696" y1="10.197" y2="11.345" gradientUnits="userSpaceOnUse"><stop offset=".183" class="g_dowhdoc"/><stop offset="1" class="pbz77hbwx"/></linearGradient><linearGradient id="ieepKub" x1="14.658" x2="15.093" y1="14.498" y2="13.809" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iOu45be" x1="18.655" x2="18.342" y1="10.137" y2="10.33" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXNhPVt" x1="14.254" x2="13.94" y1="10.137" y2="10.33" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSTZ2xM" x1="10.651" x2="10.158" y1="8.668" y2="8.668" gradientUnits="userSpaceOnUse"><stop class="gfuj0ibqm"/><stop offset="1" class="jhxo97b8s"/></linearGradient><linearGradient id="iC0oeWc" x1="20.833" x2="21.326" y1="8.668" y2="8.668" gradientUnits="userSpaceOnUse"><stop offset=".548" class="j9k2-bbvj"/><stop offset="1" class="mm0r6cb0n"/></linearGradient><filter id="iQAARuc" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".5"/></filter><filter id="iuVg6sc" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1955"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1955" result="shape"/></filter><filter id="i9wDzDc" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1955"/></filter><filter id="i8uRBOb" width="3.922" height="2.04" x="13.799" y="16.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.392157 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1955"/></filter><filter id="iLkTjeD" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1955"/></filter><filter id="ioQNM4c" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".325"/></filter><filter id="iksD7Mc" width="4.468" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1955"/></filter><filter id="iZBDx9d" width="2.097" height=".3" x="23.353" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".05"/></filter><filter id="iOBKU4c" width="2.097" height=".3" x="23.275" y="27.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".05"/></filter><filter id="idEWk8c" width="2.097" height=".3" x="23.353" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".05"/></filter><filter id="iecS7Ic" width="3.542" height="3.342" x="9.273" y="9.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1955"/></filter><filter id="iRHPcQj" width="2.992" height="2.992" x="9.448" y="9.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".25"/></filter><filter id="ikx9KTd" width="3.592" height="3.592" x="18.795" y="8.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1955"/></filter><filter id="ijz1XGe" width="2.992" height="2.992" x="18.97" y="9.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".25"/></filter><filter id="idYYfAb" width="10.34" height="12.189" x="10.577" y="5.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1955"/></filter><filter id="iIH34we" width="3.262" height="4.184" x="13.826" y="9.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".375"/></filter><filter id="iCzDGwb" width="2.379" height="3.184" x="14.507" y="9.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".125"/></filter><filter id="iadVQFb" width=".787" height=".697" x="17.142" y="9.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".05"/></filter><filter id="iUDtKrc" width=".892" height=".914" x="17.983" y="9.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".1"/></filter><filter id="iUuV92b" width=".987" height="1.041" x="13.537" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".1"/></filter><filter id="iI4LnFc" width=".914" height=".705" x="12.781" y="9.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1955" stdDeviation=".05"/></filter><filter id="im90CXb" width="2.854" height="1.798" x="16.961" y="7.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1955"/></filter><filter id="iYlN5tc" width="2.854" height="1.798" x="11.827" y="7.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1955"/></filter><filter id="iGBDCBc" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1955"/></filter><filter id="iFCI3de" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1955"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-mechanic-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.aw8cw698d {
  cx: 10.944px;
  cy: 10.765px;
  r: 0.996px;
}

.bjz-35bmd {
  stop-color: var(--svg-color--d6cbdf, #D6CBDF);
  stop-opacity: 0;
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cd8x4v99k {
  fill: var(--svg-color--000, #000);
  d: path("M14.02 10.499a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.235");
}

.cgtc6ibqv {
  d: path("M18.675 10.381a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
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

.clmvkjbnc {
  d: path("M15.71 18.676c-1.524-.508-1.825-1.445-1.91-1.84h3.92c-.355 1.237-1.492 1.738-2.01 1.84");
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e01fo_2bv {
  stop-color: var(--svg-color--a16273, #A16273);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.eqaszhbhb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 28.602H25.3");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f4216ljgk {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.813 9.794c.064.086-.069.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f6fcfpb9v {
  cx: 20.466px;
  cy: 10.765px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.f7vxzf2re {
  stop-color: var(--svg-color--8e7f98, #8E7F98);
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fmkj8mujh {
  fill: var(--svg-color--261629, #261629);
  fill-rule: evenodd;
  d: path("M17.478 8.43c.72-.067 1.182.214 1.294.317a.473.473 0 1 0 .64-.695c-.306-.282-1.032-.656-2.022-.563a.473.473 0 1 0 .087.941");
}

.fr9spbcmd {
  stop-color: var(--svg-color--95616d, #95616D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g_dowhdoc {
  stop-color: var(--svg-color--8f666b, #8F666B);
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.ghtfcxbsg {
  d: path("M13.508 9.605a.893.893 0 0 0-.86 1.13h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.894");
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.h8kb9yuhi {
  fill: var(--svg-color--000, #000);
  d: path("M17.368 10.499a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.906a.46.46 0 0 1-.06-.235");
}

.hbqpu6bzl {
  cx: 13.238px;
  cy: 9.987px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.hzctbo64o {
  stop-color: var(--svg-color--d6c6ed, #D6C6ED);
}

.i9l3p-bcq {
  cx: 10.944px;
  cy: 10.765px;
  r: 1.671px;
}

.ijq7q5b1d {
  stop-color: var(--svg-color--844552, #844552);
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j9k2-bbvj {
  stop-color: var(--svg-color--252224, #252224);
}

.jhxo97b8s {
  stop-color: var(--svg-color--463f3d, #463F3D);
}

.jse2phbtg {
  fill: var(--svg-color--f4e6ff, #F4E6FF);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.ka15ouboj {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.333 13.525c.393.206.863.323 1.363.323c.505 0 .97-.117 1.363-.323a.204.204 0 0 1 .242.04a.19.19 0 0 1 .021.242m-2.99-.282l2.948.254m-2.947-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.21.028l-.041-.028m.041.028l-.041-.028m.041.028a1.95 1.95 0 0 1-1.626.868a1.95 1.95 0 0 1-1.626-.868m3.21-.028c-.335.508-.919.847-1.584.847s-1.25-.34-1.584-.847m-.042.028l.042-.028m-.042.028l.042-.028");
}

.kbmw7jb_w {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.313 10.48l-.531 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
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

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mg1-gdc7o {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.42 10.643l-.82 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.378-.284-.378-.396 0");
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mm0r6cb0n {
  stop-color: var(--svg-color--5b5a5a, #5B5A5A);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.ncpoyrbpw {
  stop-color: var(--svg-color--cdb2d2, #CDB2D2);
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.om0oq7b1v {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.pbz77hbwx {
  stop-color: var(--svg-color--8f666b, #8F666B);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.ptx8-dg4d {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
}

.pv8cx5b7o {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qunsngokg {
  stop-color: var(--svg-color--7c6987, #7C6987);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r0_bjvbtd {
  d: path("M21.325 9.608V7.265h-1.198c.048.138.199.47.425.689c.227.219.302.595.302.807l-.047 1.392c.268 0 .53-.223.518-.545");
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.r5twurbft {
  d: path("M17.88 9.605a.893.893 0 0 1 .86 1.129h-1.726a.897.897 0 0 1 .865-1.129");
}

.rivwc6bvt {
  d: path("M10.577 8.571c0-.267.052-.688.266-.848l.057-.434c.268-.214.492-.018.492-.338v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.053.43.267.43.534v.854c0 .32.16.64.375.854c.502.352.471.546.43.96c-.18 1.792-.235 3.608-.356 5.404c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.713 0-3.052-1.235-3.213-3.006c-.14-1.811-.323-3.779-.323-5.598");
}

.rom2yrbwh {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.101-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
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

.sgo8b74bs {
  fill: var(--svg-color--261629, #261629);
  fill-rule: evenodd;
  d: path("M13.915 8.43c-.72-.067-1.183.214-1.295.317a.473.473 0 1 1-.64-.695c.306-.282 1.032-.656 2.023-.563a.473.473 0 1 1-.088.941");
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.snxda1bhi {
  stop-color: var(--svg-color--6b4a68, #6B4A68);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.stjis0jjr {
  cx: 20.466px;
  cy: 10.765px;
  r: 0.996px;
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.t7nurg72w {
  d: path("M17.813 9.794c.064.086-.069.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.tkr9c33ir {
  stop-color: var(--svg-color--9f6d72, #9F6D72);
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.tzpchacdd {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.086 9.334c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.341h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
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

.uzuk-gbcn {
  d: path("M10.16 9.608V7.265h1.196c-.047.138-.198.47-.425.689s-.302.595-.302.807v1.392c-.268 0-.482-.223-.47-.545");
}

.v_jlg2buc {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.3 9.334c-.653 0-1.205.45-1.355 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272A1.4 1.4 0 0 0 13.3 9.334");
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vqc4qgzhu {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.402-1.54-6.44-3.96-8.457");
}

.wh9pisbrr {
  d: path("m15.313 10.48l-.531 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.x5z4x3bnt {
  d: path("M14.324 10.394c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xk18tyb3e {
  fill: var(--svg-color--caadc8, #CAADC8);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.y8wlns7wu {
  stop-color: var(--svg-color--7f5663, #7F5663);
  stop-opacity: 0;
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zqss5obsp {
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.zsyglhsdv {
  stop-color: var(--svg-color--eee0fe, #EEE0FE);
  stop-opacity: 0;
}

.zv9da-f4x {
  cx: 20.466px;
  cy: 10.765px;
  r: 1.671px;
}

.zvz4a-ufu {
  cx: 13.238px;
  cy: 9.987px;
  rx: 0.39px;
  ry: 0.197px;
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

</style>
