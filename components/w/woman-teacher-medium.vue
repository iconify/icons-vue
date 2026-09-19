<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4IJbqb)"><path fill="url(#iwrQrjA)" class="o7v094i2o"/></g><path fill="url(#i2HufEd)" class="w22ydwbph"/><path fill="url(#igmYp9d)" class="w22ydwbph"/><path fill="url(#iF25Xwb)" class="w22ydwbph"/><g filter="url(#i2lXXMb)"><path stroke="url(#iTnXoNb)" class="vppjnpjkd"/></g><g filter="url(#igP3ghc)"><path fill="url(#iMOEPeb)" class="d91czabbi"/><path fill="url(#iXtAkic)" class="d91czabbi"/><path fill="url(#iFQgQJb)" class="d91czabbi"/></g><g filter="url(#ixf8K7c)"><path fill="url(#iU1VAgd)" clip-rule="evenodd" class="l-g2pi05l"/><path fill="url(#iieO9Ic)" clip-rule="evenodd" class="l-g2pi05l"/><path fill="url(#iQ2yrAe)" clip-rule="evenodd" class="l-g2pi05l"/><path fill="url(#iYbue4d)" clip-rule="evenodd" class="l-g2pi05l"/><path fill="url(#i6ObRhe)" clip-rule="evenodd" class="l-g2pi05l"/><path fill="url(#iGMVhec)" clip-rule="evenodd" class="l-g2pi05l"/><path fill="url(#izBakYd)" clip-rule="evenodd" class="l-g2pi05l"/><path fill="url(#i6FUidk)" clip-rule="evenodd" class="l-g2pi05l"/><path fill="url(#iFsvdMb)" clip-rule="evenodd" class="l-g2pi05l"/><path fill="url(#i1MFcVc)" clip-rule="evenodd" class="l-g2pi05l"/><path fill="url(#iMtCK7b)" clip-rule="evenodd" class="l-g2pi05l"/><path fill="url(#iLXN6rc)" clip-rule="evenodd" class="l-g2pi05l"/></g><path fill="url(#inni3Ad)" class="tqjnefb9y"/><path fill="url(#irFdEXc)" class="tqjnefb9y"/><path fill="url(#iGED6Pb)" class="tqjnefb9y"/><path fill="url(#inyffhc)" class="oydpu3_wd"/><path fill="url(#inD8fdb)" class="oydpu3_wd"/><path fill="url(#i85nW9b)" class="oydpu3_wd"/><path fill="url(#ioWJgDe)" class="oyko61njb"/><path fill="url(#iZszKob)" class="oyko61njb"/><path fill="url(#ipzH8ye)" class="yq24ijb2l"/><g filter="url(#iW3VjCC)"><path fill="url(#itHvCDb)" class="yhs1swb5t"/><path fill="url(#ilKpyTb)" class="yhs1swb5t"/><path fill="url(#iE7nvFb)" class="yhs1swb5t"/><path fill="url(#iIPpxde)" class="yhs1swb5t"/></g><g filter="url(#i3wRoCM)"><path fill="url(#iLFhMgc)" class="kh7wstbgi"/><path fill="url(#ibsHVHc)" class="kh7wstbgi"/><path fill="url(#iAZmaYs)" class="kh7wstbgi"/><path fill="url(#i8v2tGb)" class="kh7wstbgi"/></g><path fill="url(#ikZp9Ge)" class="w674qccfv"/><g filter="url(#idCe6yd)"><path fill="url(#ihGegYD)" class="eetme5bnl"/><path fill="url(#iqkc3oc)" class="eetme5bnl"/></g><g filter="url(#iw3MzNe)"><path fill="url(#iICN7cQ)" class="xpfqoet5v"/></g><path fill="url(#i0ZXa3b)" class="scqmvqbyx"/><path clip-rule="evenodd" class="mutk-1bjh"/><path fill="url(#iBeWKkU)" clip-rule="evenodd" class="oxbta-b3s"/><g filter="url(#iJSffKJ)"><path fill="url(#iHuHvhc)" class="njlck5bzm"/><path fill="url(#i6rZ3ic)" class="njlck5bzm"/><path fill="url(#il2y5cd)" class="njlck5bzm"/><path fill="url(#i5ACqTb)" class="njlck5bzm"/><path fill="url(#ix2tPMe)" class="njlck5bzm"/></g><g filter="url(#ixSbTCx)"><path fill="url(#iORgRwb)" class="cp7-w9xso"/><path fill="url(#iFkaCMe)" class="cp7-w9xso"/><path fill="url(#iv5YNFo)" class="cp7-w9xso"/><path fill="url(#im0nHAc)" class="cp7-w9xso"/><path fill="url(#iLlBRqG)" class="cp7-w9xso"/></g><path fill="url(#iTDg9bc)" class="y0xzenb8c"/><path fill="url(#iC4ifEe)" class="d6c7jbqee"/><g filter="url(#iP93ynA)"><path stroke="url(#iciC8rd)" class="jgqht7b_r"/></g><g filter="url(#i5pBpwc)"><path stroke="url(#iNWYtXc)" class="rm4x5nmvd"/></g><g filter="url(#i1Q7IMg)"><path stroke="url(#iIPTXvd)" class="z-ux2rbwn"/></g><g filter="url(#ikWR1RG)"><path stroke="url(#iY2OATc)" class="a06_f93qf"/></g><g filter="url(#iPCVjod)"><path stroke="url(#iUpsElc)" class="l3ult-bux"/></g><g filter="url(#iAY1Rme)"><path stroke="url(#icxHfMT)" class="j90_trd3p"/></g><path class="ron0ktkfb"/><path fill="url(#ieQ7Cxb)" class="yfmbiib-j"/><path class="xp5x-qb-q"/><g filter="url(#iBGErXP)"><path class="ugcg_yb4v"/><path fill="url(#iyxoWfb)" class="roqpr3bne"/></g><g filter="url(#imQbzob)"><path fill="url(#iGD0DId)" class="ghrbucblj"/></g><path class="pvi3pkfyi"/><path fill="url(#iIIdZJQ)" class="c_ag8zdqn"/><path class="i-soxv9hv"/><g filter="url(#izkdt3c)"><path fill="url(#iQTSb0d)" class="sx3_b5s1a"/></g><g filter="url(#i39Fqad)"><ellipse transform="rotate(-27.914 13.635 9.976)" class="f_uik8b0l"/><ellipse fill="url(#iruj5ye)" transform="rotate(-27.914 13.635 9.976)" class="oj6mex0fl"/></g><g filter="url(#iKcOTAb)"><path fill="url(#igrdJOd)" class="f5iuru7lz"/></g><path fill="url(#icxEc1q)" class="f5iuru7lz"/><g filter="url(#iU87Zeu)"><path fill="url(#iNXSGkc)" class="sj-nqvb-g"/><path fill="url(#iFfU8cc)" class="sj-nqvb-g"/></g><g filter="url(#iqT3NDB)"><path class="uxa_hdbky"/><path fill="url(#iOXeMWc)" class="byefsry9f"/></g><g filter="url(#iPtAlJe)"><path class="jwmko1b9t"/><path fill="url(#ifHHZoc)" class="bpfhdng3n"/></g><g filter="url(#i1A8dae)"><path fill="url(#inEZQee)" class="ex8_771rb"/><path fill="url(#i4F5Yab)" class="ex8_771rb"/><path fill="url(#iQ0GKyc)" class="ex8_771rb"/><path fill="url(#iUCjM9b)" class="ex8_771rb"/><path fill="url(#itPCVVb)" class="ex8_771rb"/><path fill="url(#iY6u0Le)" class="ex8_771rb"/><path fill="url(#in0sK1d)" class="ex8_771rb"/><path fill="url(#iOoDcId)" class="ex8_771rb"/></g><path fill="url(#it8mjse)" class="ex8_771rb"/><g filter="url(#imRLELc)"><path class="x-xwrab1u"/></g><g filter="url(#irQXFHb)"><path class="vro5ucbrl"/><path fill="url(#ip6asVV)" class="g1svke2ui"/><path fill="url(#ihclbHk)" class="g1svke2ui"/><path fill="url(#iiV9jUb)" class="g1svke2ui"/><path fill="url(#ikr2AFc)" class="g1svke2ui"/></g><path fill="url(#idcqX8d)" class="g1svke2ui"/><path fill="url(#iuBUebr)" class="g1svke2ui"/><path stroke="url(#i3ZIjXd)" class="df57l8zxa"/><g filter="url(#i0Ck7Bb)"><path class="t409bwbwv"/></g><g filter="url(#ieq39ec)"><path class="esnv8ab-b"/></g><g filter="url(#iQYraWx)"><path class="fk19qqi6s"/></g><g filter="url(#iJniWZd)"><path clip-rule="evenodd" class="vz4-8fbvd"/></g><path class="l95syyblr"/><path fill="url(#iV8c1Ee)" class="n2qmhou7n"/><path class="tqiq0fbpr"/><g filter="url(#iu7mfde)"><path class="o246rwiju"/><path fill="url(#iNhKkXa)" class="sz3f9hbhe"/></g><g filter="url(#idXhSqc)"><path fill="url(#iCXaBtc)" class="crhgidbky"/></g><path class="yxcrn9b9x"/><path fill="url(#iEicSRc)" class="bgonu7b5i"/><path class="mhe75vbjn"/><g filter="url(#ilRAQNc)"><path fill="url(#iWrWtNc)" class="f6id2dbgm"/></g><g filter="url(#iyPtk1V)"><ellipse transform="rotate(-27.914 13.55 10.047)" class="kvpzvz4or"/><ellipse fill="url(#ibIrVBd)" transform="rotate(-27.914 13.55 10.047)" class="o-94c4bpi"/></g><g filter="url(#i7dgZJd)"><path class="c89-b0oju"/></g><g filter="url(#iaQZaNb)"><path class="bsqzvqgte"/></g><g filter="url(#iluiQlF)"><path class="pxbi5kbmz"/><path fill="url(#i5f6N8T)" class="p0ldohbpf"/><path fill="url(#iDXfSVc)" class="p0ldohbpf"/></g><g filter="url(#iyIkekB)"><path class="am5m51xfr"/><path fill="url(#ieUBCFe)" class="jp9xcb3sy"/><path fill="url(#i3zNomd)" class="jp9xcb3sy"/></g><g filter="url(#iAy4nVb)"><path stroke="url(#iV5sdne)" class="kgr-9d0ip"/></g><g filter="url(#iA6W2Jc)"><path class="kcyd_f1_k"/></g><g filter="url(#iTZK87b)"><path fill="url(#iIbtTfd)" class="gh_m_3lkg"/><path fill="url(#iPJaOrb)" class="gh_m_3lkg"/></g><defs><radialGradient id="igmYp9d" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 27.058 6.904)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="iF25Xwb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.572 25.495)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="iFQgQJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.014 4.331)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="iieO9Ic" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.703 13.24)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iQ2yrAe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.886 13.51)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iYbue4d" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.872 8.238)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="i6ObRhe" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.301 7.723)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iGMVhec" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.023 11.674)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="izBakYd" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.933 6.903)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="i6FUidk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.513 9.889)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iFsvdMb" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.636 8.064)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="i1MFcVc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.035 -3.69)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="iMtCK7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.862 9.853)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iLXN6rc" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.234 -3.835)scale(3.79787 1.37073)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="inni3Ad" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.01 15.964)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="irFdEXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.666 20.495)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="iGED6Pb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.727 19.088)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="inyffhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27.004 28.245)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="iZszKob" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.468 29.794)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="ipzH8ye" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 12.8972 15.197 19.403)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="ilKpyTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.24 19.455)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="iE7nvFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9453 -1.33595 .2433 -.17216 19.681 20.464)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="iIPpxde" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 1.125 -2.1058 1.28688 17.625 15.906)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="ibsHVHc" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.525 20.37)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="i8v2tGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .76563 -1.43312 -.58493 14.14 16.14)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="ikZp9Ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.07812 -2.78125 0 16.25 16.344)" gradientUnits="userSpaceOnUse"><stop class="h1966m73i"/><stop offset=".574" class="r7s3_bc8p"/><stop offset="1" class="kh09rtb2d"/></radialGradient><radialGradient id="ihGegYD" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.646 23.782)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="rf65-tbna"/><stop offset="1" class="olouyqb7y"/></radialGradient><radialGradient id="iqkc3oc" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.788 23.5)" gradientUnits="userSpaceOnUse"><stop class="n9nuck1yg"/><stop offset="1" class="owhpyrhoe"/></radialGradient><radialGradient id="iICN7cQ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 -.29687 .9302 -5.77708 11.103 24.024)" gradientUnits="userSpaceOnUse"><stop class="q0hc7-7mg"/><stop offset="1" class="morvzvhzu"/></radialGradient><radialGradient id="i6rZ3ic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.197 25.376)" gradientUnits="userSpaceOnUse"><stop class="u61ge8dhn"/><stop offset="1" class="jwhs8hbdr"/></radialGradient><radialGradient id="il2y5cd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.213 26.657)" gradientUnits="userSpaceOnUse"><stop class="u61ge8dhn"/><stop offset="1" class="jwhs8hbdr"/></radialGradient><radialGradient id="i5ACqTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.26 27.938)" gradientUnits="userSpaceOnUse"><stop class="u61ge8dhn"/><stop offset="1" class="jwhs8hbdr"/></radialGradient><radialGradient id="ix2tPMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.33 29.297)" gradientUnits="userSpaceOnUse"><stop class="u61ge8dhn"/><stop offset="1" class="jwhs8hbdr"/></radialGradient><radialGradient id="iFkaCMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.26 25.376)" gradientUnits="userSpaceOnUse"><stop class="du8z2ybjf"/><stop offset="1" class="da14u2f6i"/></radialGradient><radialGradient id="iv5YNFo" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.197 26.657)" gradientUnits="userSpaceOnUse"><stop class="du8z2ybjf"/><stop offset="1" class="da14u2f6i"/></radialGradient><radialGradient id="im0nHAc" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.103 27.938)" gradientUnits="userSpaceOnUse"><stop class="du8z2ybjf"/><stop offset="1" class="da14u2f6i"/></radialGradient><radialGradient id="iLlBRqG" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.963 29.297)" gradientUnits="userSpaceOnUse"><stop class="du8z2ybjf"/><stop offset="1" class="da14u2f6i"/></radialGradient><radialGradient id="ieQ7Cxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.27 10.072)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iyxoWfb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.508 .66)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIIdZJQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.907 10.072)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iruj5ye" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .5939 -.0093 13.62 10.29)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="icxEc1q" cx="0" cy="0" r="1" gradientTransform="matrix(-.6537 -1.20346 1.36368 -.74073 10.925 12.35)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iNXSGkc" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.043 11.18)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iFfU8cc" cx="0" cy="0" r="1" gradientTransform="matrix(1.20681 0 0 .5196 20.948 9.034)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iOXeMWc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.395 10.853)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="ifHHZoc" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.701 5.37)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="inEZQee" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.312 7.171)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="i4F5Yab" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.825 7.418)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iQ0GKyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.842 16.71)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iUCjM9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28468 7.37319 -9.2164 -1.60583 17.027 9.787)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="itPCVVb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.327 6.833)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iY6u0Le" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.305 9.784)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="in0sK1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.927 9.556)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iOoDcId" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.387 7.468)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="it8mjse" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.1 11.272)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="ip6asVV" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.789 11.999)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="ikr2AFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.549 12.21)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iuBUebr" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.389 8.349)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="iV8c1Ee" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.186 10.143)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iNhKkXa" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.958 10.227)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iEicSRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.822 10.143)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ibIrVBd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.868 -1.481)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5f6N8T" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.423 -4.048)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="iDXfSVc" cx="0" cy="0" r="1" gradientTransform="matrix(1.14952 -1.97524 1.06043 .61714 12.053 7.043)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="ieUBCFe" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.072 7.04)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="i3zNomd" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.213 3.186)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="iPJaOrb" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.385 10.15)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><filter id="i4IJbqb" width="27.98" height="21.09" x="2.014" y="4.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="i2lXXMb" width="27.413" height="20.785" x="2.678" y="3.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".2"/></filter><filter id="igP3ghc" width="27.91" height="20.96" x="2.014" y="4.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="ixf8K7c" width="15.268" height="15.768" x="8.495" y="1.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="iW3VjCC" width="2.797" height="14.509" x="18.064" y="15.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="i3wRoCM" width="2.797" height="14.463" x="11.157" y="15.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="idCe6yd" width="2.1" height="3.39" x="20.957" y="23.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.647059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="iw3MzNe" width="2.1" height="3.29" x="8.96" y="23.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="iJSffKJ" width="4.793" height="5.391" x="8.96" y="24.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.458824 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="ixSbTCx" width="4.793" height="5.591" x="18.464" y="24.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.309804 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.592157 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1662" result="effect2_innerShadow_4002_1662"/></filter><filter id="iP93ynA" width="2.222" height=".3" x="18.883" y="25.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".05"/></filter><filter id="i5pBpwc" width="2.222" height=".3" x="10.87" y="25.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".05"/></filter><filter id="i1Q7IMg" width="2.222" height=".3" x="18.883" y="27.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".05"/></filter><filter id="ikWR1RG" width="2.222" height=".3" x="10.87" y="27.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".05"/></filter><filter id="iPCVjod" width="2.222" height=".3" x="18.883" y="28.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".05"/></filter><filter id="iAY1Rme" width="2.222" height=".3" x="10.87" y="28.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".05"/></filter><filter id="iBGErXP" width=".787" height=".696" x="17.537" y="9.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".05"/></filter><filter id="imQbzob" width=".891" height=".913" x="18.376" y="9.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".1"/></filter><filter id="izkdt3c" width=".986" height="1.04" x="13.934" y="9.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".1"/></filter><filter id="i39Fqad" width=".913" height=".705" x="13.179" y="9.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".05"/></filter><filter id="iKcOTAb" width="3.368" height="3.218" x="9.709" y="9.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="iU87Zeu" width="3.218" height="3.468" x="19.222" y="8.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="iqT3NDB" width="3.148" height="3.148" x="19.257" y="9.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".25"/></filter><filter id="iPtAlJe" width="2.848" height="2.848" x="9.913" y="9.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".175"/></filter><filter id="i1A8dae" width="10.191" height="11.127" x="10.908" y="5.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="imRLELc" width="2.877" height="3.682" x="14.403" y="9.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".25"/></filter><filter id="irQXFHb" width="2.377" height="3.182" x="14.815" y="9.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".125"/></filter><filter id="i0Ck7Bb" width="3.001" height="1.285" x="16.946" y="9.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="ieq39ec" width="3.001" height="1.285" x="12.06" y="9.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="iQYraWx" width="2.453" height="1.091" x="12.196" y="7.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="iJniWZd" width="2.453" height="1.091" x="17.613" y="7.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/></filter><filter id="iu7mfde" width=".787" height=".696" x="17.452" y="9.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".05"/></filter><filter id="idXhSqc" width=".891" height=".913" x="18.292" y="9.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".1"/></filter><filter id="ilRAQNc" width=".986" height="1.04" x="13.849" y="9.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".1"/></filter><filter id="iyPtk1V" width=".913" height=".705" x="13.094" y="9.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".05"/></filter><filter id="i7dgZJd" width="2.661" height="1.378" x="17.443" y="7.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".2"/></filter><filter id="iaQZaNb" width="2.661" height="1.378" x="11.992" y="7.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".2"/></filter><filter id="iluiQlF" width="4.312" height="4.613" x="9.65" y="3.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/><feGaussianBlur result="effect2_foregroundBlur_4002_1662" stdDeviation=".2"/></filter><filter id="iyIkekB" width="8.767" height="5.782" x="12.834" y="2.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/><feGaussianBlur result="effect2_foregroundBlur_4002_1662" stdDeviation=".125"/></filter><filter id="iAy4nVb" width="1.145" height="2.31" x="12.813" y="3.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".1"/></filter><filter id="iA6W2Jc" width="6.427" height="3.372" x="15.422" y="4.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1662" stdDeviation=".375"/></filter><filter id="iTZK87b" width="10.29" height="4.16" x="10.894" y="8.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1662"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1662" result="effect2_innerShadow_4002_1662"/></filter><linearGradient id="iwrQrjA" x1="11.828" x2="31.271" y1="4.62" y2="22.855" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="i2HufEd" x1="30.072" x2="9.135" y1="13.308" y2="13.308" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="iTnXoNb" x1="13.447" x2="31.259" y1="3.561" y2="24.373" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="iMOEPeb" x1="-4.897" x2="28.916" y1="25.652" y2="25.652" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="iXtAkic" x1="3.103" x2="3.103" y1="5.214" y2="23.652" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="iU1VAgd" x1="20.697" x2="14.563" y1="3.788" y2="14.549" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="inD8fdb" x1="25.183" x2="25.183" y1="30.465" y2="26.648" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="i85nW9b" x1="22.416" x2="23.228" y1="29.276" y2="29.261" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="ioWJgDe" x1="7.144" x2="9.538" y1="28.158" y2="28.158" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="itHvCDb" x1="18.064" x2="20.86" y1="18.385" y2="18.385" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="iLFhMgc" x1="13.954" x2="11.157" y1="18.385" y2="18.385" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="iAZmaYs" x1="12.119" x2="12.681" y1="16.948" y2="17.167" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="i0ZXa3b" x1="21.853" x2="17.478" y1="24.808" y2="24.808" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="iBeWKkU" x1="10.324" x2="10.752" y1="23.589" y2="23.589" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="iHuHvhc" x1="12.873" x2="8.572" y1="28.027" y2="28.027" gradientUnits="userSpaceOnUse"><stop class="tplfgobyn"/><stop offset=".716" class="w6vvgpbob"/></linearGradient><linearGradient id="iORgRwb" x1="22.478" x2="18.664" y1="27.62" y2="27.62" gradientUnits="userSpaceOnUse"><stop class="jpe7sib4k"/><stop offset=".807" class="hr5lgosjh"/></linearGradient><linearGradient id="iTDg9bc" x1="10.791" x2="21.664" y1="21.964" y2="21.964" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="iC4ifEe" x1="16.41" x2="16.41" y1="21.027" y2="22.198" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="iciC8rd" x1="19.033" x2="20.861" y1="26.128" y2="26.128" gradientUnits="userSpaceOnUse"><stop class="kdu0rpbvx"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="xn5lfsbnz"/></linearGradient><linearGradient id="iNWYtXc" x1="12.942" x2="10.744" y1="26.128" y2="26.128" gradientUnits="userSpaceOnUse"><stop class="lyeznboty"/><stop offset="1" class="go3uclbeq"/></linearGradient><linearGradient id="iIPTXvd" x1="19.033" x2="20.861" y1="27.394" y2="27.394" gradientUnits="userSpaceOnUse"><stop class="kdu0rpbvx"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="xn5lfsbnz"/></linearGradient><linearGradient id="iY2OATc" x1="12.942" x2="10.744" y1="27.394" y2="27.394" gradientUnits="userSpaceOnUse"><stop class="lyeznboty"/><stop offset="1" class="go3uclbeq"/></linearGradient><linearGradient id="iUpsElc" x1="19.033" x2="20.861" y1="28.659" y2="28.659" gradientUnits="userSpaceOnUse"><stop class="kdu0rpbvx"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="xn5lfsbnz"/></linearGradient><linearGradient id="icxHfMT" x1="12.942" x2="10.744" y1="28.659" y2="28.659" gradientUnits="userSpaceOnUse"><stop class="lyeznboty"/><stop offset="1" class="go3uclbeq"/></linearGradient><linearGradient id="iGD0DId" x1="19.049" x2="18.735" y1="10.126" y2="10.319" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQTSb0d" x1="14.651" x2="14.337" y1="10.126" y2="10.319" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igrdJOd" x1="9.709" x2="11.567" y1="10.828" y2="10.828" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="ihclbHk" x1="15.065" x2="16.004" y1="12.072" y2="12.072" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iiV9jUb" x1="16.004" x2="16.004" y1="12.778" y2="12.152" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="idcqX8d" x1="16.082" x2="16.082" y1="12.844" y2="12.705" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="i3ZIjXd" x1="14.94" x2="15.4" y1="14.28" y2="13.568" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iCXaBtc" x1="18.964" x2="18.65" y1="10.197" y2="10.39" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWrWtNc" x1="14.566" x2="14.252" y1="10.197" y2="10.39" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iV5sdne" x1="12.895" x2="13.385" y1="3.788" y2="5.053" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="iIbtTfd" x1="16.089" x2="16.089" y1="9.047" y2="12.828" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-teacher-medium" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a06_f93qf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 27.316H11.02");
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.am5m51xfr {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.4 2.95c-1.132-.25-2.15.88-2.267 1.299c1.052 3.545 3.714 3.35 6.34 3.059c1.573-.175 1.744.542 1.878.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.avo9uebvh {
  stop-color: var(--svg-color--544b50, #544B50);
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bgonu7b5i {
  d: path("M13.82 9.666a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.bpfhdng3n {
  d: path("M11.338 11.815a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.bsqzvqgte {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.153 8.368c-.323-.079-1.125-.04-1.661.344");
}

.byefsry9f {
  d: path("M20.831 11.815a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.c_ag8zdqn {
  d: path("M13.905 9.595a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.c89-b0oju {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.943 8.368c.323-.079 1.125-.04 1.661.344");
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cp7-w9xso {
  d: path("M18.664 25.38a.81.81 0 0 0 .303.668a.8.8 0 0 0-.303.636c0 .267.116.503.303.637a.8.8 0 0 0-.303.636c0 .267.116.503.303.637a.84.84 0 0 0-.303.667c.01.421.32.75.685.75h2.935c.426 0 .773-.4.773-.893v-3.604c0-.493-.347-.894-.773-.894H19.44a.776.776 0 0 0-.777.76");
}

.crhgidbky {
  d: path("M18.983 10.441a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d6c7jbqee {
  d: path("M11.157 21.503c0-.384.311-.695.695-.695h9.812v1.39h-9.812a.695.695 0 0 1-.695-.695");
}

.d91czabbi {
  d: path("M29.004 24.001H3.014V5.011l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.da14u2f6i {
  stop-color: var(--svg-color--bb8c7c, #BB8C7C);
  stop-opacity: 0;
}

.df57l8zxa {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.67 13.554a.2.2 0 0 0-.02-.25a.205.205 0 0 0-.248-.041c-.404.216-.88.339-1.398.339c-.513 0-.994-.124-1.398-.339a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248m3.333 0l-.042-.027zm0 0a1.982 1.982 0 0 1-3.333 0m0 0l.041-.027m-.041.027l.041-.027m0 0a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.41.22-.895.345-1.421.345c-.52 0-1.01-.125-1.422-.345c-.14-.073-.291.089-.203.22Z");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.du8z2ybjf {
  stop-color: var(--svg-color--cfa591, #CFA591);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eetme5bnl {
  d: path("M22.057 23.119c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.esnv8ab-b {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.862 10.171c-.265-.466-.669-.835-1.537-.835c-.38 0-.747.105-1.073.369c-.27.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.ex8_771rb {
  d: path("M10.917 9.478h.012l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.118 3.073c-.124 2.803-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.f_uik8b0l {
  cx: 13.635px;
  cy: 9.976px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.f5iuru7lz {
  d: path("M11.318 12.35a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.f6id2dbgm {
  d: path("M14.635 10.454c0-.289-.234-.48-.298-.539l-.288.279l.177.361z");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.fk19qqi6s {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.606 8.963l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005a2 2 0 0 1 .148-.077c.098-.047.238-.107.41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.182z");
}

.foz7ccc1o {
  stop-color: var(--svg-color--251732, #251732);
}

.fqkeoivtf {
  stop-color: var(--svg-color--aba5a8, #ABA5A8);
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g1svke2ui {
  d: path("m15.622 10.38l-.532 1.7a.54.54 0 0 0 .52.698h.787a.54.54 0 0 0 .52-.699l-.53-1.7c-.115-.377-.646-.377-.766 0");
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gh_m_3lkg {
  d: path("M20.844 8.64h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91V9.58c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.ghrbucblj {
  d: path("M19.068 10.37a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.go3uclbeq {
  stop-color: var(--svg-color--9c6c55, #9C6C55);
  stop-opacity: 0;
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gugba3b_v {
  stop-color: var(--svg-color--33141c, #33141C);
  stop-opacity: 0;
}

.h1966m73i {
  stop-color: var(--svg-color--856353, #856353);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hr5lgosjh {
  stop-color: var(--svg-color--90605d, #90605D);
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i-soxv9hv {
  fill: var(--svg-color--000, #000);
  d: path("M14.416 10.487a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.745h.905a.5.5 0 0 0 .06-.235");
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j90_trd3p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 28.581H11.02");
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jgqht7b_r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 26.05h1.922");
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jp9xcb3sy {
  d: path("M15.4 2.95c-1.132-.25-2.15.88-2.267 1.299c1.052 3.545 3.714 3.35 6.34 3.059c1.573-.175 1.744.542 1.878.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.jpe7sib4k {
  stop-color: var(--svg-color--ca9d86, #CA9D86);
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jwhs8hbdr {
  stop-color: var(--svg-color--a97d6f, #A97D6F);
  stop-opacity: 0;
}

.jwmko1b9t {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.338 11.815a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kcyd_f1_k {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m18.41 6.56l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.kdu0rpbvx {
  stop-color: var(--svg-color--773e41, #773E41);
}

.kgr-9d0ip {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.113 4.198c.023.244.234 1.157.544 1.71");
}

.kh09rtb2d {
  stop-color: var(--svg-color--492e25, #492E25);
}

.kh7wstbgi {
  d: path("m12.684 16.012l-1.38 2.987c-.09.19.05.41.26.41l.963-.265c.422-.106.437.277.277.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V15.648z");
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kvpzvz4or {
  cx: 13.55px;
  cy: 10.047px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.l-g2pi05l {
  fill-rule: evenodd;
  d: path("M23.19 12.15c.212-.435.323-.92.323-1.427c0-.467-.096-.906-.269-1.305h.006a3 3 0 0 0-.281-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001A3.3 3.3 0 0 0 9.567 7.12v.01a3.24 3.24 0 0 1-.526 1.772l-.002.003a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.51.51 0 0 1 0-.455M10.928 9.478h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.955-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.19 1.235l-.051.02l-.051.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.l3ult-bux {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 28.581h1.922");
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l95syyblr {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.395 9.395c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.127");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.lyeznboty {
  stop-color: var(--svg-color--9c6c55, #9C6C55);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhe75vbjn {
  fill: var(--svg-color--000, #000);
  d: path("M14.33 10.559a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.morvzvhzu {
  stop-color: var(--svg-color--86645b, #86645B);
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.mutk-1bjh {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.418 30.011v-8.406h-2.094v8.406z");
}

.n2qmhou7n {
  d: path("M18.188 9.666a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.n9nuck1yg {
  stop-color: var(--svg-color--cca48e, #CCA48E);
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.njlck5bzm {
  d: path("M13.353 25.38a.81.81 0 0 1-.302.668a.8.8 0 0 1 .302.636a.77.77 0 0 1-.302.637a.8.8 0 0 1 .302.636a.77.77 0 0 1-.302.637c.187.144.302.39.302.667c-.009.421-.32.75-.685.75H9.734c-.427 0-.774-.4-.774-.893v-3.604c0-.493.347-.894.774-.894h2.842c.475 0 .77.39.777.76");
}

.o-94c4bpi {
  cx: 13.55px;
  cy: 10.047px;
  rx: 0.39px;
  ry: 0.197px;
}

.o246rwiju {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.122 9.855c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o7v094i2o {
  d: path("M29.384 25.001H2.634c-.34 0-.62-.28-.62-.62V4.631c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.oj6mex0fl {
  cx: 13.635px;
  cy: 9.976px;
  rx: 0.39px;
  ry: 0.197px;
}

.olouyqb7y {
  stop-color: var(--svg-color--865f46, #865F46);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.owhpyrhoe {
  stop-color: var(--svg-color--cca48e, #CCA48E);
  stop-opacity: 0;
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.oxbta-b3s {
  fill-rule: evenodd;
  d: path("M12.418 30.011v-8.406h-2.094v8.406z");
}

.oydpu3_wd {
  d: path("M22.684 30.01V17.767a10.98 10.98 0 0 1 4.32 8.745v3.5z");
}

.oyko61njb {
  d: path("M9.304 30.01V17.767a10.98 10.98 0 0 0-4.32 8.745v3.5z");
}

.p0ldohbpf {
  d: path("M10.935 4.752c.566-.599 1.636-.6 2.13-.51l.396 1.29c-.252-.04-.295-.001-.485.183c-.137 1.093-1.376 1.757-2.886 2.197c-.149-1.492.109-2.38.845-3.16");
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pvi3pkfyi {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.698 9.323c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.pxbi5kbmz {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M10.935 4.752c.566-.599 1.636-.6 2.13-.51l.396 1.29c-.252-.04-.295-.001-.485.183c-.137 1.093-1.376 1.757-2.886 2.197c-.149-1.492.109-2.38.845-3.16");
}

.q0hc7-7mg {
  stop-color: var(--svg-color--58382a, #58382A);
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.r7s3_bc8p {
  stop-color: var(--svg-color--775244, #775244);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rf65-tbna {
  stop-color: var(--svg-color--b78876, #B78876);
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rm4x5nmvd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 26.05H11.02");
}

.ron0ktkfb {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.48 9.323c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.roqpr3bne {
  d: path("M18.207 9.783c.064.085-.07.19-.22.302c-.151.113-.263.193-.327.108s.007-.246.158-.359s.326-.136.39-.05");
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.scqmvqbyx {
  d: path("M10.324 21.89v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.sj-nqvb-g {
  d: path("M20.831 12.35a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.sx3_b5s1a {
  d: path("M14.72 10.382c0-.288-.234-.48-.298-.538l-.288.278l.177.362z");
}

.sz3f9hbhe {
  d: path("M18.122 9.855c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t409bwbwv {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.146 10.171c.265-.466.669-.835 1.537-.835c.38 0 .747.105 1.073.369c.269.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.08-.45");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tplfgobyn {
  stop-color: var(--svg-color--b78c74, #B78C74);
}

.tqiq0fbpr {
  fill: var(--svg-color--000, #000);
  d: path("M17.677 10.559c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.tqjnefb9y {
  d: path("M16.014 15.511c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u61ge8dhn {
  stop-color: var(--svg-color--c59c8b, #C59C8B);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.ugcg_yb4v {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.207 9.783c.064.085-.07.19-.22.302c-.151.113-.263.193-.327.108s.007-.246.158-.359s.326-.136.39-.05");
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.uxa_hdbky {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.831 11.815a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vppjnpjkd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.228 4.404h26.213a.1.1 0 0 1 .1.1V24.09");
}

.vro5ucbrl {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.622 10.38l-.532 1.7a.54.54 0 0 0 .52.698h.787a.54.54 0 0 0 .52-.699l-.53-1.7c-.115-.377-.646-.377-.766 0");
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vz4-8fbvd {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m19.735 8.505l-.137.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.059A3 3 0 0 0 19 8.77a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.094-.528c.514-.09.989 0 1.329.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w22ydwbph {
  d: path("M3.014 24.001V5.011h25.99v18.99z");
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w674qccfv {
  d: path("M16.014 18.681c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.w6vvgpbob {
  stop-color: var(--svg-color--936567, #936567);
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.x-xwrab1u {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.611 10.518l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.494-.377-.613 0");
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xn5lfsbnz {
  stop-color: var(--svg-color--773e41, #773E41);
  stop-opacity: 0;
}

.xp5x-qb-q {
  fill: var(--svg-color--000, #000);
  d: path("M17.762 10.487c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.745h-.904a.46.46 0 0 1-.061-.235");
}

.xpfqoet5v {
  d: path("M9.96 23.11c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y0xzenb8c {
  d: path("M21.664 22.995V20.71c0-.388-.36-.698-.81-.698h-8.659c-1.041 0-1.871.73-1.871 1.621c0 .753.61 1.363 1.363 1.363z");
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.yfmbiib-j {
  d: path("M18.273 9.595a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.yhs1swb5t {
  d: path("M19.29 15.984L20.713 19c.09.19-.05.41-.26.41l-.964-.265c-.422-.106-.436.277-.276.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V15.6z");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yq24ijb2l {
  d: path("M18.064 15.602h-4.11V30.01h4.11z");
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.yxcrn9b9x {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.613 9.395c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.z-ux2rbwn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 27.316h1.922");
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

</style>
