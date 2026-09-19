<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="e4tar7-ra"/><path fill="url(#iUY80Pe)" class="ei-zmixku"/><path fill="url(#iDbYoEd)" class="ei-zmixku"/><path fill="url(#iCYhEcc)" class="ei-zmixku"/><path fill="url(#i82oxbd)" class="ei-zmixku"/><path fill="url(#ixxOx8b)" class="ei-zmixku"/><path fill="url(#irDlLPc)" class="ei-zmixku"/><path fill="url(#iA95z6d)" class="ei-zmixku"/><path fill="url(#ivHOYle)" class="ei-zmixku"/><path class="auoirjbmm"/><path fill="url(#ineK6Cd)" class="x-171ccrl"/><path fill="url(#ijnexbb)" class="x-171ccrl"/><path fill="url(#iDGT1hJ)" class="x-171ccrl"/><path class="ecbjgibqi"/><path fill="url(#inZ0nhg)" class="vgwnw8h0u"/><path fill="url(#iv1Hcvb)" class="vgwnw8h0u"/><path fill="url(#iXhtQee)" class="vgwnw8h0u"/><path fill="url(#iIhOjRc)" class="i1ujs7one"/><path fill="url(#iSrLw0d)" class="i1ujs7one"/><path fill="url(#ihFs7mi)" class="i1ujs7one"/><path fill="url(#ixDw5Zd)" class="i1ujs7one"/><path fill="url(#idq1mHc)" class="i1ujs7one"/><path fill="url(#iepOgvc)" class="i1ujs7one"/><path fill="url(#igkqS7c)" class="i1ujs7one"/><g filter="url(#ifKNBwe)"><path class="dht7arbom"/></g><g filter="url(#ilIgjed)"><path fill="url(#iePzlxb)" class="u22r5t-xk"/></g><g filter="url(#idH2F0q)"><path fill="url(#ijTQesd)" class="u_k1hctwr"/></g><path fill="url(#iqvCc8c)" class="pgd4nu3yt"/><path fill="url(#iRoTFae)" class="pgd4nu3yt"/><g filter="url(#iR9rfhd)"><path class="cu-wpbcgj"/></g><g filter="url(#iE6aeFe)"><path fill="url(#i2M18Ac)" class="bu7es_a0d"/><path fill="url(#iWOguze)" class="bu7es_a0d"/></g><g filter="url(#i9SP0ne)"><path fill="url(#iOZ3Ead)" class="ksm3t8bap"/></g><g filter="url(#iBxEsje)"><path fill="url(#iHI8c6l)" class="wctf3ibkb"/><path fill="url(#iLqvWBd)" class="wctf3ibkb"/></g><path fill="url(#iOwbiLd)" class="e_0vl3o1i"/><path fill="url(#imPWj0d)" class="e_0vl3o1i"/><g filter="url(#ihGoR7d)"><path class="azp_74bds"/></g><g filter="url(#ioFMtwX)"><path fill="url(#iZ9erpc)" class="xlqlhebaa"/><path fill="url(#izzmTpc)" class="xlqlhebaa"/><path fill="url(#ige5GHc)" class="xlqlhebaa"/><path fill="url(#iJSnMNe)" class="xlqlhebaa"/><path fill="url(#iUyFiFc)" class="xlqlhebaa"/></g><g filter="url(#i1oQXeb)"><path class="as7n8dhke"/><path fill="url(#ilsx18e)" class="iethn661e"/><path fill="url(#iIqYMmb)" class="iethn661e"/><path fill="url(#iHIACdy)" class="iethn661e"/></g><g filter="url(#iRoorsX)"><path fill="url(#iyaA5Cd)" class="w3laegbtn"/><path fill="url(#i8m0Kkc)" class="w3laegbtn"/><path fill="url(#i9I8vtd)" class="w3laegbtn"/><path fill="url(#iQaJWRc)" class="w3laegbtn"/><path fill="url(#it0Apgb)" class="w3laegbtn"/><path fill="url(#i9DI4Wy)" class="w3laegbtn"/><path fill="url(#iOwXTDe)" class="w3laegbtn"/></g><path fill="url(#iPuuVpc)" class="w3laegbtn"/><path fill="url(#i3H8Lhr)" class="aioxy45xu"/><path fill="url(#itzjL9Z)" class="aioxy45xu"/><path fill="url(#i5pwqPb)" class="aioxy45xu"/><g filter="url(#iXqu6Td)"><path class="a_r6pkbfn"/></g><g filter="url(#i6akhNe)"><path fill="url(#ic7bwvc)" class="ghfy1iray"/><path fill="url(#iieFrYO)" class="ghfy1iray"/><path fill="url(#ibH2Zjd)" class="ghfy1iray"/></g><path fill="url(#iayided)" class="g0xvfdbyw"/><path fill="url(#i4eHRSd)" class="g0xvfdbyw"/><path fill="url(#i1nkGac)" class="g0xvfdbyw"/><path fill="url(#iGdWf9I)" class="g0xvfdbyw"/><path fill="url(#ihhsmPe)" class="g0xvfdbyw"/><path fill="url(#iswZV0c)" class="g0xvfdbyw"/><path fill="url(#ilTtifc)" class="qneer9b8q"/><g filter="url(#ihOUYdP)"><path class="yc4hclv9f"/></g><g filter="url(#ikq5sue)"><path class="x3r4-kbqt"/></g><g filter="url(#ivZ1PBb)"><path class="neasw5byt"/></g><g filter="url(#iErjQEe)"><path class="b_9lgmbzy"/></g><g filter="url(#izqpIze)"><path class="k_s71_y0x"/></g><path class="mm3_yebkl"/><path fill="url(#i5bnkAb)" class="i9lr1p25m"/><path fill="url(#iTv9Djc)" class="i9lr1p25m"/><g filter="url(#i0WTCoc)"><path stroke="url(#iBQBf6d)" class="zmk93obal"/></g><path class="npgenebms"/><path class="sytb8pb3p"/><path class="hoq7d6bfq"/><path fill="url(#ibqtDyq)" class="m00e_ufro"/><path class="dm4l5vbzb"/><g filter="url(#iMCHfIc)"><path class="vlizw1ypl"/><path fill="url(#iVaJgyd)" class="hby5gbc-p"/></g><g filter="url(#iovAvUb)"><path fill="url(#irlfuVD)" class="bweh5b8qw"/></g><path class="r0rrpvpum"/><path fill="url(#imUdeEc)" class="q2nms2n3q"/><path class="zhtqcybuc"/><g filter="url(#iEsrEgd)"><path fill="url(#i0raRjd)" class="uwyi2hzqu"/></g><g filter="url(#i1sJJJK)"><ellipse transform="rotate(-27.914 13.561 9.976)" class="lu3j7bbpk"/><ellipse fill="url(#igUPrxc)" transform="rotate(-27.914 13.561 9.976)" class="npvlux_im"/></g><defs><radialGradient id="iDbYoEd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -14.3438 23.142 20.686)" gradientUnits="userSpaceOnUse"><stop class="szuqc-bjo"/><stop offset="1" class="in53vxbzi"/></radialGradient><radialGradient id="iCYhEcc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.347 20.477 5.184)scale(3.59496 4.80694)" gradientUnits="userSpaceOnUse"><stop class="iy200zbbi"/><stop offset="1" class="ox6ngqb6d"/></radialGradient><radialGradient id="i82oxbd" cx="0" cy="0" r="1" gradientTransform="rotate(77.471 -3.564 20.737)scale(2.88111 5.07754)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="utz8l-hjj"/><stop offset="1" class="ssj6asr2b"/></radialGradient><radialGradient id="ixxOx8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.57813 .51562 -7.1646 -8.03319 14.554 27.46)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="im7yg7aog"/><stop offset="1" class="nz4t17rpu"/></radialGradient><radialGradient id="irDlLPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 .3125 -2.8125 16.87503 8.952 23.999)" gradientUnits="userSpaceOnUse"><stop class="fupnc-bzv"/><stop offset="1" class="fux90lb8s"/></radialGradient><radialGradient id="iA95z6d" cx="0" cy="0" r="1" gradientTransform="matrix(.313 0 0 13.5898 8.827 27.552)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="u7qedx64x"/><stop offset="1" class="l-im3ccrf"/></radialGradient><radialGradient id="ivHOYle" cx="0" cy="0" r="1" gradientTransform="matrix(-.50581 0 0 -8.83067 23.25 26.076)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="frtpxb2_e"/><stop offset="1" class="r_hbeqgkw"/></radialGradient><radialGradient id="ineK6Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-.59707 0 0 -12.1778 9.033 29.939)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="bu_chtytz"/><stop offset="1" class="n1msxeybk"/></radialGradient><radialGradient id="ijnexbb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69302 6.8777 -1.92029 -.4727 6.992 23.061)" gradientUnits="userSpaceOnUse"><stop class="tf7ikua9d"/><stop offset="1" class="xodttob3f"/></radialGradient><radialGradient id="inZ0nhg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 -10.40629 1.38016 -.21552 25.58 28.374)" gradientUnits="userSpaceOnUse"><stop offset=".455" class="f_vyractb"/><stop offset="1" class="av_zubbsw"/></radialGradient><radialGradient id="iXhtQee" cx="0" cy="0" r="1" gradientTransform="matrix(.49206 0 0 10.875 23.088 26.467)" gradientUnits="userSpaceOnUse"><stop class="mzy3c3d_u"/><stop offset="1" class="lpdsa84op"/></radialGradient><radialGradient id="ihFs7mi" cx="0" cy="0" r="1" gradientTransform="matrix(1.62231 -1.625 9.061 9.04602 15.736 29.78)" gradientUnits="userSpaceOnUse"><stop class="rbi44vm-m"/><stop offset="1" class="k-1w4_syq"/></radialGradient><radialGradient id="ixDw5Zd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.42 17.248 11.374)scale(18.1601 26.3733)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="pc9y3hbhd"/><stop offset="1" class="vhxxajp3a"/></radialGradient><radialGradient id="idq1mHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.53125 -8.40625 0 15.986 18.155)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="lm4m34bzz"/><stop offset="1" class="y78euyjzo"/></radialGradient><radialGradient id="iePzlxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.63279 -.8125 0 16.517 22.751)" gradientUnits="userSpaceOnUse"><stop class="kna63ccqu"/><stop offset="1" class="yg8va_99z"/></radialGradient><radialGradient id="ijTQesd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.34377 1.74998 -2.39636 -3.20947 11.765 12.967)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="j5u713b4n"/><stop offset="1" class="frf3e3y1o"/></radialGradient><radialGradient id="iqvCc8c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25 .8711 -.92998 -2.40211 23.858 12.686)" gradientUnits="userSpaceOnUse"><stop class="bor4_sboz"/><stop offset=".858" class="nqhgyubjs"/></radialGradient><radialGradient id="iRoTFae" cx="0" cy="0" r="1" gradientTransform="matrix(1.82812 .51173 -1.43377 5.12206 20.562 13.046)" gradientUnits="userSpaceOnUse"><stop class="kgl1dzb7o"/><stop offset="1" class="plxqyrsje"/></radialGradient><radialGradient id="i2M18Ac" cx="0" cy="0" r="1" gradientTransform="matrix(1.4697 -1.59165 3.40232 3.14166 8.664 10.211)" gradientUnits="userSpaceOnUse"><stop class="bv99tyb-i"/><stop offset="1" class="ynhkn8blf"/></radialGradient><radialGradient id="iWOguze" cx="0" cy="0" r="1" gradientTransform="rotate(71.741 -.52 9.97)scale(5.60855 3.99461)" gradientUnits="userSpaceOnUse"><stop offset=".707" class="z5yb85rdc"/><stop offset="1" class="ho-6bmb3r"/></radialGradient><radialGradient id="iHI8c6l" cx="0" cy="0" r="1" gradientTransform="matrix(2.96202 -3.23123 2.01258 1.8449 21.246 11.537)" gradientUnits="userSpaceOnUse"><stop class="wpgp5neaw"/><stop offset="1" class="hqd78q26u"/></radialGradient><radialGradient id="iLqvWBd" cx="0" cy="0" r="1" gradientTransform="rotate(-143.457 13.268 1.623)scale(1.81797 6.41679)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="bua-ombap"/><stop offset="1" class="xf7z99bbu"/></radialGradient><radialGradient id="iOwbiLd" cx="0" cy="0" r="1" gradientTransform="rotate(-143.844 7.216 3.795)scale(3.06704 1.99268)" gradientUnits="userSpaceOnUse"><stop class="hdaq7kcyr"/><stop offset="1" class="b9kp-9dwr"/></radialGradient><radialGradient id="imPWj0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.14395 -1.05015 3.68181 4.01068 9.353 10.762)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="t8no4c6dx"/><stop offset="1" class="kk_u40bcq"/></radialGradient><radialGradient id="iZ9erpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.50781 13.8508 0 16 21.34)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="g9gcawu6z"/><stop offset="1" class="hpb-k7b_o"/></radialGradient><radialGradient id="izzmTpc" cx="0" cy="0" r="1" gradientTransform="rotate(152.259 7.559 9.702)scale(9.53325 15.1141)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="ngc6h6bst"/><stop offset="1" class="o5llqtbdv"/></radialGradient><radialGradient id="ige5GHc" cx="0" cy="0" r="1" gradientTransform="matrix(6.06254 6.31246 -7.41731 7.12364 14.453 14.217)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="s1jm76o_g"/><stop offset="1" class="a0ve6ibhs"/></radialGradient><radialGradient id="iJSnMNe" cx="0" cy="0" r="1" gradientTransform="rotate(-158.513 8.323 6.627)scale(4.24838 2.76793)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="u9m-38uic"/><stop offset="1" class="dgp6vzbgz"/></radialGradient><radialGradient id="iUyFiFc" cx="0" cy="0" r="1" gradientTransform="rotate(119.709 5.81 12.606)scale(7.34431 2.43451)" gradientUnits="userSpaceOnUse"><stop offset=".447" class="pf0n6ab7v"/><stop offset="1" class="xu2rljbva"/></radialGradient><radialGradient id="ilsx18e" cx="0" cy="0" r="1" gradientTransform="rotate(120.055 4.51 13.354)scale(4.72188 1.12313)" gradientUnits="userSpaceOnUse"><stop class="dffvlvchu"/><stop offset="1" class="d-40emb9q"/></radialGradient><radialGradient id="iIqYMmb" cx="0" cy="0" r="1" gradientTransform="matrix(.65627 2.79296 -5.00674 1.17644 14.609 15.577)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="fk-fr5fnl"/><stop offset="1" class="jo1qw0kfh"/></radialGradient><radialGradient id="iHIACdy" cx="0" cy="0" r="1" gradientTransform="rotate(160.918 7.248 9.62)scale(4.1924 13.0345)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="e8lijgb2o"/><stop offset="1" class="slbri3bvg"/></radialGradient><radialGradient id="iyaA5Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.79307 0 0 -11.5323 19.456 10.598)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="jd4fmybad"/><stop offset=".659" class="ydfqssp1e"/></radialGradient><radialGradient id="i8m0Kkc" cx="0" cy="0" r="1" gradientTransform="rotate(-107.819 10.348 -.213)scale(1.37863 1.69321)" gradientUnits="userSpaceOnUse"><stop class="tugc9tb5e"/><stop offset="1" class="gq9yj-bjj"/></radialGradient><radialGradient id="i9I8vtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.30788 -1.5 1.64003 -.33662 18.633 9.06)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="ubg-tcb5j"/><stop offset="1" class="zb2dc7btu"/></radialGradient><radialGradient id="iQaJWRc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.253 2.33685 -1.65515 -.88748 18.022 6.029)" gradientUnits="userSpaceOnUse"><stop class="n7gad4bzu"/><stop offset="1" class="ejsfj0d0t"/></radialGradient><radialGradient id="it0Apgb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03908 1.3579 -1.79032 1.36997 14.599 5.429)" gradientUnits="userSpaceOnUse"><stop class="lh3mafbyp"/><stop offset="1" class="aob-g0oqu"/></radialGradient><radialGradient id="iOwXTDe" cx="0" cy="0" r="1" gradientTransform="matrix(5.0625 2.75 -1.92972 3.55245 14.233 5.307)" gradientUnits="userSpaceOnUse"><stop class="fw1-gacwi"/><stop offset="1" class="i1rn8sbbi"/></radialGradient><radialGradient id="iPuuVpc" cx="0" cy="0" r="1" gradientTransform="rotate(95.789 4.105 12.278)scale(7.27168 8.96983)" gradientUnits="userSpaceOnUse"><stop offset=".668" class="afm29ab6e"/><stop offset=".988" class="bvm8nhbqg"/></radialGradient><radialGradient id="i3H8Lhr" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 4.65625 -10.56138 -2.33908 19 3.249)" gradientUnits="userSpaceOnUse"><stop class="kg11p55iw"/><stop offset="1" class="f-lmuxb9l"/></radialGradient><radialGradient id="itzjL9Z" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9375 .65626 -1.24788 -3.68415 23.031 6.89)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="necrmbvul"/><stop offset="1" class="nlldxqbzj"/></radialGradient><radialGradient id="i5pwqPb" cx="0" cy="0" r="1" gradientTransform="matrix(.75769 -3.32812 2.92645 .66624 9.29 8.327)" gradientUnits="userSpaceOnUse"><stop class="rl87-gbvf"/><stop offset="1" class="bh_6wtbtg"/></radialGradient><radialGradient id="ic7bwvc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03113 3.06466 -5.29387 -1.78117 18.983 3.965)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="mtkhizwsu"/><stop offset="1" class="te6fenbjd"/></radialGradient><radialGradient id="iieFrYO" cx="0" cy="0" r="1" gradientTransform="rotate(121.752 8.27 7.041)scale(4.86941 8.82412)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="j3e98qkfc"/><stop offset="1" class="eh4-6ib5z"/></radialGradient><radialGradient id="ibH2Zjd" cx="0" cy="0" r="1" gradientTransform="rotate(169.223 10.87 4.312)scale(1.25343 4.89934)" gradientUnits="userSpaceOnUse"><stop offset=".076" class="necrmbvul"/><stop offset="1" class="nlldxqbzj"/></radialGradient><radialGradient id="iGdWf9I" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 0 0 -.60938 21.768 5.499)" gradientUnits="userSpaceOnUse"><stop class="ekarirbxr"/><stop offset="1" class="n81djoa0z"/></radialGradient><radialGradient id="ihhsmPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .54688 -8.71875 0 11.174 4.967)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="b4qr-wvfv"/><stop offset="1" class="yyik5z8lx"/></radialGradient><radialGradient id="iswZV0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92969 -.45312 0 15.229 5.186)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="h6i96qjvc"/><stop offset="1" class="d31bklhyx"/></radialGradient><radialGradient id="ilTtifc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.90625 2.05457 0 15.979 6.764)" gradientUnits="userSpaceOnUse"><stop class="rkzp1hbvm"/><stop offset="1" class="j5zu11bke"/></radialGradient><radialGradient id="iBQBf6d" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 -.625 1.875 .98437 14.614 14.155)" gradientUnits="userSpaceOnUse"><stop class="v7a_kmutk"/><stop offset="1" class="wiz5gzb0p"/></radialGradient><radialGradient id="ibqtDyq" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 6.735 9.596)scale(1.10543 1.21398)" gradientUnits="userSpaceOnUse"><stop class="qxnakxbrg"/><stop offset="1" class="egerxebfb"/></radialGradient><radialGradient id="iVaJgyd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.471 .678)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imUdeEc" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 4.553 8.527)scale(1.10548 1.21404)" gradientUnits="userSpaceOnUse"><stop class="qxnakxbrg"/><stop offset="1" class="egerxebfb"/></radialGradient><radialGradient id="igUPrxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.546 10.292)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ifKNBwe" width="2.581" height="5.008" x="14.415" y="20.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".25"/></filter><filter id="ilIgjed" width="1.681" height="4.108" x="15.197" y="21.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1367"/></filter><filter id="idH2F0q" width="6.499" height="6.992" x="8.438" y="10.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.247059 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1367"/></filter><filter id="iR9rfhd" width="4.058" height="5.011" x="20.345" y="7.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.25098 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1367"/></filter><filter id="iE6aeFe" width="3.958" height="5.111" x="7.666" y="7.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.14902 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1367"/></filter><filter id="i9SP0ne" width="3.716" height="3.975" x="20.59" y="8.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".075"/></filter><filter id="iBxEsje" width="3.274" height="3.37" x="20.499" y="8.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".05"/></filter><filter id="ihGoR7d" width="4.072" height="2.992" x="20.355" y="7.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".1"/></filter><filter id="ioFMtwX" width="13.191" height="7.279" x="9.404" y="14.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.243137 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1367"/></filter><filter id="i1oQXeb" width="6.278" height="4.65" x="12.723" y="15.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.207843 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1367"/></filter><filter id="iRoorsX" width="10.85" height="12.138" x="10.825" y="4.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.352941 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1367"/></filter><filter id="iXqu6Td" width="4.248" height="5.575" x="9.651" y="3.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.313726 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1367"/><feGaussianBlur result="effect2_foregroundBlur_4002_1367" stdDeviation=".05"/></filter><filter id="i6akhNe" width="9.815" height="5.825" x="12.74" y="2.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.254902 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1367"/><feGaussianBlur result="effect2_foregroundBlur_4002_1367" stdDeviation=".1"/></filter><filter id="ihOUYdP" width="2.288" height="1.093" x="17.531" y="7.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.027451 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1367"/></filter><filter id="ikq5sue" width="2.188" height=".793" x="17.581" y="7.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".075"/></filter><filter id="ivZ1PBb" width="2.288" height="1.093" x="12.21" y="7.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.027451 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1367"/></filter><filter id="iErjQEe" width="2.188" height=".793" x="12.261" y="7.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".075"/></filter><filter id="izqpIze" width="3.187" height="4.4" x="14.104" y="9.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".375"/></filter><filter id="i0WTCoc" width="3.668" height="1.523" x="14.166" y="13.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".075"/></filter><filter id="iMCHfIc" width=".787" height=".696" x="17.463" y="9.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".05"/></filter><filter id="iovAvUb" width=".891" height=".913" x="18.303" y="9.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".1"/></filter><filter id="iEsrEgd" width=".986" height="1.04" x="13.86" y="9.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".1"/></filter><filter id="i1sJJJK" width=".913" height=".705" x="13.105" y="9.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1367" stdDeviation=".05"/></filter><linearGradient id="iUY80Pe" x1="15.049" x2="15.049" y1="29.939" y2="20.53" gradientUnits="userSpaceOnUse"><stop class="ifj7fvbjw"/><stop offset="1" class="wz09qdb4r"/></linearGradient><linearGradient id="iDGT1hJ" x1="8.912" x2="8.912" y1="29.939" y2="26.655" gradientUnits="userSpaceOnUse"><stop class="trl24wm4t"/><stop offset="1" class="xg491tydm"/></linearGradient><linearGradient id="iv1Hcvb" x1="24.142" x2="27.327" y1="29.311" y2="21.436" gradientUnits="userSpaceOnUse"><stop offset=".116" class="bdhnfsb4c"/><stop offset=".679" class="ya66usbax"/></linearGradient><linearGradient id="iIhOjRc" x1="12.518" x2="22.705" y1="21.28" y2="30.936" gradientUnits="userSpaceOnUse"><stop class="e8j2tsbtw"/><stop offset="1" class="e6nk6fapd"/></linearGradient><linearGradient id="iSrLw0d" x1="27.198" x2="19.296" y1="30.793" y2="28.026" gradientUnits="userSpaceOnUse"><stop class="xa_7m3b4l"/><stop offset="1" class="c4ry2c6jv"/></linearGradient><linearGradient id="iepOgvc" x1="15.015" x2="15.229" y1="28.674" y2="28.469" gradientUnits="userSpaceOnUse"><stop class="xcq_ambdy"/><stop offset="1" class="zh35wab0s"/></linearGradient><linearGradient id="igkqS7c" x1="19.002" x2="18.65" y1="21.983" y2="22.342" gradientUnits="userSpaceOnUse"><stop class="i-kbbcb4w"/><stop offset="1" class="k1jzsjbfs"/></linearGradient><linearGradient id="iOZ3Ead" x1="21.912" x2="23.611" y1="11.545" y2="8.32" gradientUnits="userSpaceOnUse"><stop offset=".667" class="x0jcpybzt"/><stop offset="1" class="qfss9c9ub"/></linearGradient><linearGradient id="i9DI4Wy" x1="21.353" x2="19.764" y1="10.987" y2="10.928" gradientUnits="userSpaceOnUse"><stop offset=".267" class="umoaa6lxl"/><stop offset="1" class="uwpc4fbqq"/></linearGradient><linearGradient id="iayided" x1="15.58" x2="17.299" y1="5.672" y2="5.672" gradientUnits="userSpaceOnUse"><stop class="z5duhrbsp"/><stop offset="1" class="qjga9kbjc"/></linearGradient><linearGradient id="i4eHRSd" x1="15.644" x2="15.644" y1="6.329" y2="5.672" gradientUnits="userSpaceOnUse"><stop class="i817agb_c"/><stop offset="1" class="tp-3hccxn"/></linearGradient><linearGradient id="i1nkGac" x1="15.969" x2="15.969" y1="4.756" y2="5.342" gradientUnits="userSpaceOnUse"><stop class="p59cvi4fc"/><stop offset="1" class="nr_-dacny"/></linearGradient><linearGradient id="i5bnkAb" x1="16.939" x2="15.707" y1="11.463" y2="11.655" gradientUnits="userSpaceOnUse"><stop offset=".117" class="yzp1s7u9s"/><stop offset=".685" class="gtx7mebkb"/></linearGradient><linearGradient id="iTv9Djc" x1="15.832" x2="15.832" y1="12.692" y2="12.069" gradientUnits="userSpaceOnUse"><stop offset=".072" class="hhom56_-y"/><stop offset="1" class="k4oea-brf"/></linearGradient><linearGradient id="irlfuVD" x1="18.975" x2="18.661" y1="10.126" y2="10.319" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0raRjd" x1="14.576" x2="14.263" y1="10.126" y2="10.319" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-elf-medium-dark" /></template>
<style>
.a_r6pkbfn {
  fill: var(--svg-color--21101d, #21101D);
  d: path("m13.698 5.67l-.011-.028c-.186-.447-.464-1.118-.553-1.878c-.669.078-2.173.547-2.837 1.797c-.482.909-.573 1.988-.54 2.752c.489.258.81.466 1.119.726v-.902c0-.412.333-.59.973-.934l.005-.003q.202-.107.445-.243c.693-.389 1.096-1.234 1.151-1.646q.123.19.248.359");
}

.a0ve6ibhs {
  stop-color: var(--svg-color--9f6c64, #9F6C64);
}

.afm29ab6e {
  stop-color: var(--svg-color--794659, #794659);
  stop-opacity: 0;
}

.aioxy45xu {
  d: path("M9.29 8.083a6.4 6.4 0 0 1 1.586 1.037v-.903c0-.412.313-.59.916-.934l.005-.003q.19-.107.419-.242c.653-.39.951-1.315 1.004-1.727c.968 1.59 2.113 2.11 3.296 2.11h3.266c.975 0 1.313.449 1.313.78l.013.907a6.4 6.4 0 0 1 1.603-1.038c-.208-.523-.256-1.047-.296-1.478l-.008-.09c-.051-.544-.25-1.343-1.145-2.078c-.632-.484-1.16-.687-1.91-.812c-.471-.079-.778-.361-1.014-.579l-.072-.066c-.286-.302-1.23-.906-2.187-.906c-1.328 0-1.934.469-2.387.906a9 9 0 0 1-.487.44c-.18.15-.404.226-.636.262c-1.018.158-1.633.527-2.209 1.127c-.699.727-.812 1.718-.875 2.5a2.2 2.2 0 0 1-.196.787");
}

.aob-g0oqu {
  stop-color: var(--svg-color--663c42, #663C42);
  stop-opacity: 0;
}

.as7n8dhke {
  fill: var(--svg-color--7d5a51, #7D5A51);
  d: path("m12.924 15.577l.232 1c.03.107.117.372.232.578c.136.243 1.342 2.067 2.336 2.997a.27.27 0 0 0 .37.003c.991-.897 2.221-2.758 2.357-3c.115-.206.263-.471.293-.578l.258-1z");
}

.auoirjbmm {
  fill: var(--svg-color--755bba, #755BBA);
  d: path("M8.912 18.302a10.9 10.9 0 0 0-3.84 8.319v3.318h3.84z");
}

.av_zubbsw {
  stop-color: var(--svg-color--9079d5, #9079D5);
  stop-opacity: 0;
}

.azp_74bds {
  fill: var(--svg-color--92766e, #92766E);
  d: path("M20.977 9.342c.05.084.176.233.289.164c.14-.086.976-1.007 2.437-1.5c.323-.089.468.113.512.261q.012.03.012.052l-.012-.052c-.028-.063-.112-.139-.309-.143c-.32-.008-1.937.64-3.351 2.453z");
}

.b_9lgmbzy {
  stroke: var(--svg-color--2f2f2f, #2F2F2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.486 8.526a2.35 2.35 0 0 1 1.737-.283");
}

.b4qr-wvfv {
  stop-color: var(--svg-color--949393, #949393);
}

.b9kp-9dwr {
  stop-color: var(--svg-color--634645, #634645);
}

.bdhnfsb4c {
  stop-color: var(--svg-color--7566b5, #7566B5);
}

.bh_6wtbtg {
  stop-color: var(--svg-color--54504f, #54504F);
  stop-opacity: 0;
}

.bor4_sboz {
  stop-color: var(--svg-color--31282b, #31282B);
}

.bu_chtytz {
  stop-color: var(--svg-color--5742a1, #5742A1);
}

.bu7es_a0d {
  d: path("M8.487 7.779c1.524.44 2.582 1.437 2.928 1.89l.209 2.95c-.399.018-.94.243-1.934-.467c-1.165-1.041-1.72-2.576-1.999-3.545a.67.67 0 0 1 .135-.615a.64.64 0 0 1 .66-.213");
}

.bua-ombap {
  stop-color: var(--svg-color--7a524c, #7A524C);
  stop-opacity: 0;
}

.bv99tyb-i {
  stop-color: var(--svg-color--614141, #614141);
}

.bvm8nhbqg {
  stop-color: var(--svg-color--663541, #663541);
}

.bweh5b8qw {
  d: path("M18.994 10.37a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.c4ry2c6jv {
  stop-color: var(--svg-color--b3776e, #B3776E);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-wpbcgj {
  fill: var(--svg-color--826159, #826159);
  d: path("M23.482 7.779c-1.524.44-2.582 1.437-2.928 1.89l-.209 2.95c.399.018.94.243 1.934-.467c1.165-1.041 1.72-2.576 1.999-3.545a.67.67 0 0 0-.135-.615a.64.64 0 0 0-.66-.213");
}

.d-40emb9q {
  stop-color: var(--svg-color--775c56, #775C56);
  stop-opacity: 0;
}

.d31bklhyx {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
  stop-opacity: 0;
}

.dffvlvchu {
  stop-color: var(--svg-color--775c56, #775C56);
}

.dgp6vzbgz {
  stop-color: var(--svg-color--613528, #613528);
  stop-opacity: 0;
}

.dht7arbom {
  fill: var(--svg-color--673c37, #673C37);
  d: path("M15.706 21.132c.264.22.79.923.79 1.906c0 1.053-.358 1.646-.701 2.06a.115.115 0 0 1-.178 0c-.343-.414-.702-1.007-.702-2.06c0-.983.527-1.685.79-1.907");
}

.dm4l5vbzb {
  fill: var(--svg-color--000, #000);
  d: path("M17.688 10.487a.51.51 0 0 1 .51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.e_0vl3o1i {
  d: path("M11.401 11.165c-.904-1.684-2.446-2.402-3.074-2.56c.598 1.662 1.19 2.452 1.6 2.81c.44.384 1.057.369 1.293.355z");
}

.e4tar7-ra {
  fill: var(--svg-color--8868c9, #8868C9);
  d: path("M5.071 26.62c0-6.035 4.893-10.928 10.929-10.928s10.929 4.893 10.929 10.929v3.318H5.07z");
}

.e6nk6fapd {
  stop-color: var(--svg-color--a16162, #A16162);
}

.e8j2tsbtw {
  stop-color: var(--svg-color--714743, #714743);
}

.e8lijgb2o {
  stop-color: var(--svg-color--4d2d30, #4D2D30);
  stop-opacity: 0;
}

.ecbjgibqi {
  fill: var(--svg-color--9172d5, #9172D5);
  d: path("M23.088 18.302a10.9 10.9 0 0 1 3.84 8.319v3.318h-3.84z");
}

.egerxebfb {
  stop-color: var(--svg-color--694c3f, #694C3F);
}

.eh4-6ib5z {
  stop-color: var(--svg-color--271020, #271020);
}

.ei-zmixku {
  d: path("M5.071 26.62c0-6.035 4.893-10.928 10.929-10.928s10.929 4.893 10.929 10.929v3.318H5.07z");
}

.ejsfj0d0t {
  stop-color: var(--svg-color--886361, #886361);
  stop-opacity: 0;
}

.ekarirbxr {
  stop-color: var(--svg-color--ede5f4, #EDE5F4);
}

.f_vyractb {
  stop-color: var(--svg-color--9079d5, #9079D5);
}

.f-lmuxb9l {
  stop-color: var(--svg-color--220f20, #220F20);
}

.fk-fr5fnl {
  stop-color: var(--svg-color--573031, #573031);
}

.frf3e3y1o {
  stop-color: var(--svg-color--1a1319, #1A1319);
}

.frtpxb2_e {
  stop-color: var(--svg-color--795dc2, #795DC2);
}

.ft5dv1b6b {
  fill: none;
}

.fupnc-bzv {
  stop-color: var(--svg-color--8066bd, #8066BD);
}

.fux90lb8s {
  stop-color: var(--svg-color--715cb9, #715CB9);
  stop-opacity: 0;
}

.fw1-gacwi {
  stop-color: var(--svg-color--513331, #513331);
}

.g0xvfdbyw {
  d: path("M8.85 5.672a.53.53 0 0 1 .529-.529h13.18a.53.53 0 0 1 0 1.059H9.379a.53.53 0 0 1-.53-.53");
}

.g9gcawu6z {
  stop-color: var(--svg-color--9f6561, #9F6561);
}

.ghfy1iray {
  d: path("m21.093 7.466l1.215.39c.137-.747.062-2.563-1.383-3.227c-1.729-.73-2.453-1.127-3.292-1.586l-.372-.203c-1.024-.554-2.588-.628-3.438.297c-.437.477-.617.617-.883.617c.163 1.19.458 1.866 1.674 2.696a3.3 3.3 0 0 0 1.917.578h3.266c.656 0 1.126.204 1.296.438");
}

.gq9yj-bjj {
  stop-color: var(--svg-color--664040, #664040);
  stop-opacity: 0;
}

.gtx7mebkb {
  stop-color: var(--svg-color--9b7971, #9B7971);
  stop-opacity: 0;
}

.h6i96qjvc {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
}

.hby5gbc-p {
  d: path("M18.133 9.784c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.135.39-.05");
}

.hdaq7kcyr {
  stop-color: var(--svg-color--5d4241, #5D4241);
}

.hhom56_-y {
  stop-color: var(--svg-color--6e3f44, #6E3F44);
}

.ho-6bmb3r {
  stop-color: var(--svg-color--59373e, #59373E);
}

.hoq7d6bfq {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.406 9.323c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.hpb-k7b_o {
  stop-color: var(--svg-color--6b3f38, #6B3F38);
}

.hqd78q26u {
  stop-color: var(--svg-color--7d5b55, #7D5B55);
}

.i-kbbcb4w {
  stop-color: var(--svg-color--906550, #906550);
}

.i1rn8sbbi {
  stop-color: var(--svg-color--513331, #513331);
  stop-opacity: 0;
}

.i1ujs7one {
  d: path("m16.274 29.939l-9.221-9.595a10.95 10.95 0 0 1 5.854-4.208L26.69 29.94z");
}

.i817agb_c {
  stop-color: var(--svg-color--9777b8, #9777B8);
}

.i9lr1p25m {
  d: path("m15.618 10.098l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.114-.408-.646-.408-.765 0");
}

.iethn661e {
  d: path("m12.924 15.577l.232 1c.03.107.117.372.232.578c.136.243 1.342 2.067 2.336 2.997a.27.27 0 0 0 .37.003c.991-.897 2.221-2.758 2.357-3c.115-.206.263-.471.293-.578l.258-1z");
}

.ifj7fvbjw {
  stop-color: var(--svg-color--6651aa, #6651AA);
}

.im7yg7aog {
  stop-color: var(--svg-color--5e45a4, #5E45A4);
}

.in53vxbzi {
  stop-color: var(--svg-color--8666c7, #8666C7);
  stop-opacity: 0;
}

.iy200zbbi {
  stop-color: var(--svg-color--846fc5, #846FC5);
}

.j3e98qkfc {
  stop-color: var(--svg-color--271020, #271020);
  stop-opacity: 0;
}

.j5u713b4n {
  stop-color: var(--svg-color--191019, #191019);
}

.j5zu11bke {
  stop-color: var(--svg-color--c2ffff, #C2FFFF);
}

.jd4fmybad {
  stop-color: var(--svg-color--946a59, #946A59);
}

.jo1qw0kfh {
  stop-color: var(--svg-color--573031, #573031);
  stop-opacity: 0;
}

.k_s71_y0x {
  fill: var(--svg-color--744449, #744449);
  d: path("m15.447 10.293l-.57 1.839c-.098.378.136.756.467.756h.707c.331 0 .565-.384.468-.756l-.478-1.839c-.102-.407-.487-.407-.594 0");
}

.k-1w4_syq {
  stop-color: var(--svg-color--915959, #915959);
  stop-opacity: 0;
}

.k1jzsjbfs {
  stop-color: var(--svg-color--7f4b4c, #7F4B4C);
  stop-opacity: 0;
}

.k4oea-brf {
  stop-color: var(--svg-color--7b4653, #7B4653);
  stop-opacity: 0;
}

.kg11p55iw {
  stop-color: var(--svg-color--4a3c40, #4A3C40);
}

.kgl1dzb7o {
  stop-color: var(--svg-color--1d161e, #1D161E);
}

.kk_u40bcq {
  stop-color: var(--svg-color--674b49, #674B49);
}

.kna63ccqu {
  stop-color: var(--svg-color--fffbb9, #FFFBB9);
}

.ksm3t8bap {
  d: path("M20.74 11.524c.904-1.683 2.423-2.885 3.415-3.064c-.598 1.662-1.53 2.956-1.94 3.314c-.44.385-1.058.37-1.294.355z");
}

.l-im3ccrf {
  stop-color: var(--svg-color--624ca8, #624CA8);
  stop-opacity: 0;
}

.lh3mafbyp {
  stop-color: var(--svg-color--663c42, #663C42);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lm4m34bzz {
  stop-color: var(--svg-color--421d1e, #421D1E);
}

.lpdsa84op {
  stop-color: var(--svg-color--6951ad, #6951AD);
  stop-opacity: 0;
}

.lu3j7bbpk {
  cx: 13.561px;
  cy: 9.976px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.m00e_ufro {
  d: path("M18.199 9.595a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.mm3_yebkl {
  fill: var(--svg-color--755145, #755145);
  d: path("m15.618 10.098l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.114-.408-.646-.408-.765 0");
}

.mtkhizwsu {
  stop-color: var(--svg-color--402d32, #402D32);
}

.mzy3c3d_u {
  stop-color: var(--svg-color--664dad, #664DAD);
}

.n1msxeybk {
  stop-color: var(--svg-color--5b4a9b, #5B4A9B);
  stop-opacity: 0;
}

.n7gad4bzu {
  stop-color: var(--svg-color--886361, #886361);
}

.n81djoa0z {
  stop-color: var(--svg-color--cfc9e2, #CFC9E2);
  stop-opacity: 0;
}

.neasw5byt {
  stroke: var(--svg-color--19191a, #19191A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.486 8.526a2.35 2.35 0 0 1 1.737-.283");
}

.necrmbvul {
  stop-color: var(--svg-color--555253, #555253);
}

.ngc6h6bst {
  stop-color: var(--svg-color--8d625b, #8D625B);
  stop-opacity: 0;
}

.nlldxqbzj {
  stop-color: var(--svg-color--555253, #555253);
  stop-opacity: 0;
}

.npgenebms {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16 13.709c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.129-.06-.278-.198-.209a3 3 0 0 1-1.385.33");
}

.npvlux_im {
  cx: 13.561px;
  cy: 9.976px;
  rx: 0.39px;
  ry: 0.197px;
}

.nqhgyubjs {
  stop-color: var(--svg-color--1f131d, #1F131D);
}

.nr_-dacny {
  stop-color: var(--svg-color--a29b98, #A29B98);
  stop-opacity: 0;
}

.nz4t17rpu {
  stop-color: var(--svg-color--5e45a4, #5E45A4);
  stop-opacity: 0;
}

.o5llqtbdv {
  stop-color: var(--svg-color--8d625b, #8D625B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ox6ngqb6d {
  stop-color: var(--svg-color--846fc5, #846FC5);
  stop-opacity: 0;
}

.p59cvi4fc {
  stop-color: var(--svg-color--a29b98, #A29B98);
}

.pc9y3hbhd {
  stop-color: var(--svg-color--6e4641, #6E4641);
  stop-opacity: 0;
}

.pf0n6ab7v {
  stop-color: var(--svg-color--55302a, #55302A);
}

.pgd4nu3yt {
  d: path("M23.391 11.64c.213-.676.183-1.334.141-1.579h-6.219v6.992l4.277-.066c2.382-1.426 2.005-3.621 1.801-4.121c-.157-.389-.148-.774 0-1.227");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plxqyrsje {
  stop-color: var(--svg-color--1d161e, #1D161E);
  stop-opacity: 0;
}

.q2nms2n3q {
  d: path("M13.83 9.595a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.qfss9c9ub {
  stop-color: var(--svg-color--8f756d, #8F756D);
  stop-opacity: 0;
}

.qjga9kbjc {
  stop-color: var(--svg-color--cdc7e1, #CDC7E1);
}

.qneer9b8q {
  d: path("M15.907 3.644a.104.104 0 0 1 .144 0c.268.257.693.872.693 1.702c0 .974-.346 1.524-.678 1.907a.115.115 0 0 1-.174 0c-.332-.383-.679-.933-.679-1.907c0-.83.425-1.445.694-1.702");
}

.qxnakxbrg {
  stop-color: var(--svg-color--795646, #795646);
}

.r_hbeqgkw {
  stop-color: var(--svg-color--795dc2, #795DC2);
  stop-opacity: 0;
}

.r0rrpvpum {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.624 9.323c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.rbi44vm-m {
  stop-color: var(--svg-color--a85d71, #A85D71);
}

.rkzp1hbvm {
  stop-color: var(--svg-color--6fe9ff, #6FE9FF);
}

.rl87-gbvf {
  stop-color: var(--svg-color--54504f, #54504F);
}

.s1jm76o_g {
  stop-color: var(--svg-color--8b5548, #8B5548);
  stop-opacity: 0;
}

.slbri3bvg {
  stop-color: var(--svg-color--391a20, #391A20);
}

.ssj6asr2b {
  stop-color: var(--svg-color--6d499b, #6D499B);
  stop-opacity: 0;
}

.sytb8pb3p {
  fill: var(--svg-color--352e31, #352E31);
  d: path("M18.345 9.28c-.397.05-.74.302-.863.422l1.777.848l.527-.317c.194-.117.256-.378.088-.531c-.48-.44-1.116-.474-1.53-.422m-4.689 0c.398.05.741.302.863.422l-1.777.848l-.527-.317c-.194-.117-.255-.378-.088-.531c.48-.44 1.116-.474 1.53-.422");
}

.szuqc-bjo {
  stop-color: var(--svg-color--987cdc, #987CDC);
}

.t8no4c6dx {
  stop-color: var(--svg-color--674b49, #674B49);
  stop-opacity: 0;
}

.te6fenbjd {
  stop-color: var(--svg-color--402d32, #402D32);
  stop-opacity: 0;
}

.tf7ikua9d {
  stop-color: var(--svg-color--8a73c8, #8A73C8);
}

.tp-3hccxn {
  stop-color: var(--svg-color--9777b8, #9777B8);
  stop-opacity: 0;
}

.trl24wm4t {
  stop-color: var(--svg-color--6655a7, #6655A7);
}

.tugc9tb5e {
  stop-color: var(--svg-color--664040, #664040);
}

.u_k1hctwr {
  d: path("M8.609 11.64c-.213-.676-.182-1.334-.14-1.579h6.218v6.992l-4.312-.039c-2.39-1.406-1.97-3.648-1.766-4.148c.158-.389.148-.774 0-1.227");
}

.u22r5t-xk {
  d: path("M15.988 21.314c.264.22.79.924.79 1.906c0 1.053-.358 1.646-.701 2.06a.115.115 0 0 1-.178 0c-.343-.414-.702-1.007-.702-2.06c0-.982.528-1.685.791-1.906");
}

.u7qedx64x {
  stop-color: var(--svg-color--624ca8, #624CA8);
}

.u9m-38uic {
  stop-color: var(--svg-color--4c200c, #4C200C);
}

.ubg-tcb5j {
  stop-color: var(--svg-color--81554c, #81554C);
}

.umoaa6lxl {
  stop-color: var(--svg-color--987061, #987061);
}

.utz8l-hjj {
  stop-color: var(--svg-color--6d499b, #6D499B);
}

.uwpc4fbqq {
  stop-color: var(--svg-color--9a6c5e, #9A6C5E);
  stop-opacity: 0;
}

.uwyi2hzqu {
  d: path("M14.646 10.383c0-.289-.235-.481-.298-.54l-.288.28l.177.361z");
}

.v7a_kmutk {
  stop-color: var(--svg-color--856163, #856163);
}

.vgwnw8h0u {
  d: path("M23.088 18.302a10.9 10.9 0 0 1 3.84 8.319v3.318h-3.84z");
}

.vhxxajp3a {
  stop-color: var(--svg-color--6e4641, #6E4641);
}

.vlizw1ypl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.133 9.784c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.135.39-.05");
}

.w3laegbtn {
  d: path("M10.827 7.622a3 3 0 0 1 2.998-3.093h4.35a3 3 0 0 1 2.999 3.085l-.118 4.144a5.052 5.052 0 0 1-10.1.014z");
}

.wctf3ibkb {
  d: path("M20.599 11.165c.904-1.684 2.446-2.402 3.074-2.56c-.598 1.662-1.19 2.452-1.6 2.81c-.44.384-1.057.369-1.293.355z");
}

.wiz5gzb0p {
  stop-color: var(--svg-color--856163, #856163);
  stop-opacity: 0;
}

.wpgp5neaw {
  stop-color: var(--svg-color--7d5d56, #7D5D56);
}

.wz09qdb4r {
  stop-color: var(--svg-color--6651aa, #6651AA);
  stop-opacity: 0;
}

.x-171ccrl {
  d: path("M8.912 18.302a10.9 10.9 0 0 0-3.84 8.319v3.318h3.84z");
}

.x0jcpybzt {
  stop-color: var(--svg-color--8f756d, #8F756D);
}

.x3r4-kbqt {
  stroke: var(--svg-color--2f2f2f, #2F2F2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.544 8.526a2.35 2.35 0 0 0-1.738-.283");
}

.xa_7m3b4l {
  stop-color: var(--svg-color--bb8274, #BB8274);
}

.xcq_ambdy {
  stop-color: var(--svg-color--7b4b52, #7B4B52);
}

.xf7z99bbu {
  stop-color: var(--svg-color--7a524c, #7A524C);
}

.xg491tydm {
  stop-color: var(--svg-color--6655a7, #6655A7);
  stop-opacity: 0;
}

.xlqlhebaa {
  d: path("M12.127 14.599c-.289-.031-.859-.05-1.402.312c-.703.547-1.16 1.196-1.301 2.25c-.198 1.482 1.045 3.944 6.574 4.18h.004c5.529-.236 6.772-2.698 6.574-4.18c-.14-1.054-.598-1.703-1.3-2.25c-.606-.47-1.103-.468-1.392-.437L16 14.91z");
}

.xodttob3f {
  stop-color: var(--svg-color--7f70bc, #7F70BC);
  stop-opacity: 0;
}

.xu2rljbva {
  stop-color: var(--svg-color--55302a, #55302A);
  stop-opacity: 0;
}

.y78euyjzo {
  stop-color: var(--svg-color--603739, #603739);
  stop-opacity: 0;
}

.ya66usbax {
  stop-color: var(--svg-color--7566b5, #7566B5);
  stop-opacity: 0;
}

.yc4hclv9f {
  stroke: var(--svg-color--19191a, #19191A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.544 8.526a2.35 2.35 0 0 0-1.738-.283");
}

.ydfqssp1e {
  stop-color: var(--svg-color--704d45, #704D45);
}

.yg8va_99z {
  stop-color: var(--svg-color--eddda3, #EDDDA3);
}

.ynhkn8blf {
  stop-color: var(--svg-color--593c3c, #593C3C);
}

.yyik5z8lx {
  stop-color: var(--svg-color--949393, #949393);
  stop-opacity: 0;
}

.yzp1s7u9s {
  stop-color: var(--svg-color--9b7971, #9B7971);
}

.z5duhrbsp {
  stop-color: var(--svg-color--aba5ae, #ABA5AE);
}

.z5yb85rdc {
  stop-color: var(--svg-color--694a4c, #694A4C);
  stop-opacity: 0;
}

.zb2dc7btu {
  stop-color: var(--svg-color--81554c, #81554C);
  stop-opacity: 0;
}

.zh35wab0s {
  stop-color: var(--svg-color--7b4b52, #7B4B52);
  stop-opacity: 0;
}

.zhtqcybuc {
  fill: var(--svg-color--000, #000);
  d: path("M14.342 10.487a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.zmk93obal {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16 13.709c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.129-.06-.278-.198-.209a3 3 0 0 1-1.385.33Z");
}

</style>
