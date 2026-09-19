<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iqorGir)" clip-rule="evenodd" class="zdtgd2jja"/><path fill="url(#iC9Mosc)" clip-rule="evenodd" class="zdtgd2jja"/><g filter="url(#igVj7md)"><path stroke="url(#ihCBmXb)" class="r4hwau21e"/></g><path fill="url(#iEjF5ud)" clip-rule="evenodd" class="fdouacc8b"/><path fill="url(#ihweIJe)" clip-rule="evenodd" class="fdouacc8b"/><g filter="url(#inUxH8c)"><path stroke="url(#ihPWpZb)" class="rcm4jyv6c"/></g><path fill="url(#ipmrrpc)" clip-rule="evenodd" class="avsbxl_7i"/><path fill="url(#iwFRgGe)" clip-rule="evenodd" class="avsbxl_7i"/><g filter="url(#itkqyKb)"><path stroke="url(#iyU4HGe)" class="dzezh-eno"/></g><path fill="url(#iQVUmZc)" clip-rule="evenodd" class="z8aicjn7g"/><path fill="url(#i5yxDIc)" clip-rule="evenodd" class="z8aicjn7g"/><path class="n8p7o9f4r"/><path fill="url(#iqBaokb)" class="m6ohn2s-t"/><path fill="url(#inVsQCb)" class="m6ohn2s-t"/><path fill="url(#iBCAwHe)" class="m6ohn2s-t"/><path fill="url(#icGyDQc)" class="m6ohn2s-t"/><g filter="url(#iPZcHdH)"><path class="vtr0yklkc"/><path fill="url(#iTv7ZPB)" class="po_pxuzrh"/><path fill="url(#iJ4nBZn)" class="po_pxuzrh"/></g><path fill="url(#inEELwd)" clip-rule="evenodd" class="g5-tshirv"/><path fill="url(#iWvNRsc)" clip-rule="evenodd" class="g5-tshirv"/><path fill="url(#iaPwZyR)" clip-rule="evenodd" class="g5-tshirv"/><path fill="url(#ioJ3Cfe)" clip-rule="evenodd" class="g5-tshirv"/><path fill="url(#i7Ar4fe)" clip-rule="evenodd" class="vlstqlbst"/><path fill="url(#iTHRc0d)" clip-rule="evenodd" class="vlstqlbst"/><path fill="url(#iagytLe)" clip-rule="evenodd" class="vlstqlbst"/><path fill="url(#iDZlNse)" clip-rule="evenodd" class="vlstqlbst"/><path fill="url(#iwWEx0d)" clip-rule="evenodd" class="n7mx21thj"/><path fill="url(#iJhnXWc)" clip-rule="evenodd" class="n7mx21thj"/><path fill="url(#iPtc6th)" clip-rule="evenodd" class="n7mx21thj"/><path fill="url(#iyOd4Vb)" clip-rule="evenodd" class="n7mx21thj"/><path fill="url(#ixST6Jb)" clip-rule="evenodd" class="r9zbgw02g"/><path fill="url(#ies6qib)" clip-rule="evenodd" class="r9zbgw02g"/><path fill="url(#iPxkVvc)" clip-rule="evenodd" class="r9zbgw02g"/><path fill="url(#iqDB3gk)" clip-rule="evenodd" class="r9zbgw02g"/><path fill="url(#i4ouwad)" class="buagh_b2g"/><path fill="url(#i4Tqhuc)" class="dw7rkubkg"/><g filter="url(#iL1Ethb)"><path fill="url(#ieD3RNc)" class="az79hwb6r"/><path fill="url(#iIwp5cd)" class="az79hwb6r"/><path fill="url(#imS1QXW)" class="az79hwb6r"/><path fill="url(#irDOrTd)" class="az79hwb6r"/><path fill="url(#iDjJxUd)" class="az79hwb6r"/><path fill="url(#iUHqUwe)" class="az79hwb6r"/></g><path fill="url(#i2e1vmd)" class="oy-bjdb4l"/><path fill="url(#iyeb8ne)" class="iwmsipbyi"/><path fill="url(#iJv4lKc)" class="rzmbtdl4c"/><path fill="url(#iopQswe)" class="rzmbtdl4c"/><g filter="url(#iTD7xve)"><path fill="url(#iUL9e8c)" class="m1u9pgbwn"/></g><path fill="url(#iY9kAdR)" class="m1u9pgbwn"/><path fill="url(#iJQPfwr)" class="m1u9pgbwn"/><path fill="url(#imAOH6C)" class="m1u9pgbwn"/><path fill="url(#iRucGdc)" class="m1u9pgbwn"/><path fill="url(#iK4N7Td)" class="m1u9pgbwn"/><path fill="url(#iRU9knd)" class="m1u9pgbwn"/><path fill="url(#iO7qACd)" class="m1u9pgbwn"/><path fill="url(#iJKsrCd)" class="m1u9pgbwn"/><g filter="url(#irfZoHd)"><path class="fds4yd4ht"/></g><g filter="url(#iItNQps)"><path fill="url(#itWucLZ)" class="m6knzmbvc"/><path fill="url(#iyASV4c)" class="m6knzmbvc"/><path fill="url(#iVjEpLc)" class="m6knzmbvc"/><path fill="url(#ivYYuNb)" class="m6knzmbvc"/></g><path fill="url(#itUJ43c)" class="m6knzmbvc"/><path fill="url(#iCCiWWb)" class="m6knzmbvc"/><g filter="url(#icKFaCe)"><path fill="url(#i9SAfbG)" class="g98ji6enx"/><path fill="url(#iddKqyv)" class="g98ji6enx"/><path fill="url(#ih9lUDe)" class="g98ji6enx"/><path fill="url(#iAmT8fb)" class="g98ji6enx"/><path fill="url(#ilsLFrd)" class="g98ji6enx"/></g><g filter="url(#iV4OEpI)"><path class="wsq8b2bdn"/></g><g filter="url(#iVA462b)"><path class="be1dcehns"/></g><g filter="url(#iPsqTFd)"><path fill="url(#iAjatke)" class="c5kvt8p1h"/><path fill="url(#iRJFWde)" class="c5kvt8p1h"/></g><g filter="url(#iUrrMCd)"><path fill="url(#iU2Rkre)" class="igpgsacmg"/><path fill="url(#iJmb3He)" class="igpgsacmg"/><path fill="url(#ikfvfLc)" class="igpgsacmg"/><path fill="url(#iQKCKQb)" class="igpgsacmg"/><path fill="url(#iiiAGPQ)" class="igpgsacmg"/><path fill="url(#i2SS17b)" class="igpgsacmg"/></g><path class="w2-ufizde"/><path fill="url(#iP8xkrd)" class="mj2rsfbdi"/><path class="ujoylbbsx"/><g filter="url(#i2erJyA)"><path class="g7f0b-9ed"/><path fill="url(#imdTteb)" class="wrv1zf4oz"/></g><g filter="url(#i4h0sce)"><path fill="url(#iGmN27d)" class="g0ppexbky"/></g><path class="kcb-zebvi"/><path fill="url(#iT01m8d)" class="jp7u36bby"/><path class="m8q4dvb9z"/><g filter="url(#i2m68Ht)"><path fill="url(#i0E1iRc)" class="emo1hubkw"/></g><g filter="url(#iP3KAuk)"><ellipse transform="rotate(-32.532 13.25 12.543)" class="ywswr-y1s"/><ellipse fill="url(#isy7Ryd)" transform="rotate(-32.532 13.25 12.543)" class="pnu47pbah"/></g><path fill="url(#ih9XiEc)" class="lso1_vbso"/><path fill="url(#i6aBSee)" class="lso1_vbso"/><path fill="url(#imSklpc)" class="lso1_vbso"/><path fill="url(#iEveZvb)" class="lfijyebbp"/><path fill="url(#i7TVfUb)" class="lfijyebbp"/><g filter="url(#iLsmY4m)"><path class="r70awwbve"/></g><g filter="url(#iREE9Pd)"><path class="dkf5o985m"/></g><g filter="url(#iwXw2yb)"><path class="h6a5-kjll"/></g><g filter="url(#iWuKxAc)"><path class="k_s1uxbby"/></g><g filter="url(#ix9S4yd)"><path stroke="url(#iEqxoVc)" class="g35jyabao"/></g><g filter="url(#iKavNKb)"><ellipse stroke="url(#itXtitd)" class="sfqolabyf"/></g><ellipse class="j3foh4beb"/><g filter="url(#ibjmFec)"><path stroke="url(#iNnMR9c)" class="pptea1vyv"/></g><defs><radialGradient id="iC9Mosc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6217 1.72506 -3.88088 -1.39866 4.928 12.866)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="ye-2zryyr"/><stop offset=".85" class="d8xtj4b7u"/></radialGradient><radialGradient id="ihweIJe" cx="0" cy="0" r="1" gradientTransform="rotate(106.399 -3.133 8.024)scale(1.96628 3.75623)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="ye-2zryyr"/><stop offset=".85" class="d8xtj4b7u"/></radialGradient><radialGradient id="iwFRgGe" cx="0" cy="0" r="1" gradientTransform="rotate(110.767 -2.93 8.439)scale(1.80306 4.21624)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="ye-2zryyr"/><stop offset=".85" class="d8xtj4b7u"/></radialGradient><radialGradient id="i5yxDIc" cx="0" cy="0" r="1" gradientTransform="rotate(113.326 -2.835 8.925)scale(1.61789 4.14912)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="ye-2zryyr"/><stop offset=".85" class="d8xtj4b7u"/></radialGradient><radialGradient id="inVsQCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.52138 .86916 -1.0215 -.61276 6.787 11.449)" gradientUnits="userSpaceOnUse"><stop class="i2dy_3bdc"/><stop offset="1" class="s_o7_jesn"/></radialGradient><radialGradient id="iBCAwHe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.70312 0 0 -.65716 6.644 16.605)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="wj8c2lbyu"/><stop offset="1" class="yn5ij1ffp"/></radialGradient><radialGradient id="icGyDQc" cx="0" cy="0" r="1" gradientTransform="rotate(35.102 -19.492 14.62)scale(1.67111 2.71046)" gradientUnits="userSpaceOnUse"><stop class="e490wkn-s"/><stop offset="1" class="bn4os6vdu"/></radialGradient><radialGradient id="iTv7ZPB" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 -1.22657 .626 .09968 25.862 13.414)" gradientUnits="userSpaceOnUse"><stop class="j2l239u6e"/><stop offset="1" class="a3e1obbdc"/></radialGradient><radialGradient id="iJ4nBZn" cx="0" cy="0" r="1" gradientTransform="matrix(.60156 -.63281 .3758 .35725 25.87 11.766)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="jsiezd-_e"/><stop offset="1" class="wr4xjslhr"/></radialGradient><radialGradient id="iWvNRsc" cx="0" cy="0" r="1" gradientTransform="matrix(1.18749 1.5 -2.61214 2.06791 26.425 12.548)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="i9k-0jbxt"/><stop offset="1" class="d8_6n5bpd"/></radialGradient><radialGradient id="iaPwZyR" cx="0" cy="0" r="1" gradientTransform="matrix(.66176 -.53537 .3309 .40903 28.225 11.975)" gradientUnits="userSpaceOnUse"><stop class="nhxwftdxc"/><stop offset="1" class="axz4ivbcr"/></radialGradient><radialGradient id="ioJ3Cfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.06322 1.21875 -1.34641 1.1746 26.862 12.5)" gradientUnits="userSpaceOnUse"><stop class="i9x98ebrr"/><stop offset="1" class="yk15gqvvr"/></radialGradient><radialGradient id="iTHRc0d" cx="0" cy="0" r="1" gradientTransform="rotate(74.107 5.332 24.717)scale(2.45789 3.78855)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="i9k-0jbxt"/><stop offset="1" class="d8_6n5bpd"/></radialGradient><radialGradient id="iagytLe" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.58594 .36956 .3942 29.292 12.32)" gradientUnits="userSpaceOnUse"><stop class="nhxwftdxc"/><stop offset="1" class="axz4ivbcr"/></radialGradient><radialGradient id="iDZlNse" cx="0" cy="0" r="1" gradientTransform="matrix(.82807 .89964 -1.70806 1.57218 27.878 13.063)" gradientUnits="userSpaceOnUse"><stop class="i9x98ebrr"/><stop offset="1" class="yk15gqvvr"/></radialGradient><radialGradient id="iJhnXWc" cx="0" cy="0" r="1" gradientTransform="rotate(70.854 4.078 26.187)scale(2.23451 4.05178)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="i9k-0jbxt"/><stop offset="1" class="d8_6n5bpd"/></radialGradient><radialGradient id="iPtc6th" cx="0" cy="0" r="1" gradientTransform="matrix(.42197 -.61719 .33958 .23217 29.362 13.399)" gradientUnits="userSpaceOnUse"><stop class="nhxwftdxc"/><stop offset="1" class="axz4ivbcr"/></radialGradient><radialGradient id="iyOd4Vb" cx="0" cy="0" r="1" gradientTransform="rotate(55.566 1.114 33.45)scale(.98095 1.76017)" gradientUnits="userSpaceOnUse"><stop class="i9x98ebrr"/><stop offset="1" class="yk15gqvvr"/></radialGradient><radialGradient id="ies6qib" cx="0" cy="0" r="1" gradientTransform="matrix(.73437 1.86015 -3.71825 1.46794 27.162 14.688)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="i9k-0jbxt"/><stop offset="1" class="d8_6n5bpd"/></radialGradient><radialGradient id="iPxkVvc" cx="0" cy="0" r="1" gradientTransform="rotate(-36.12 36.726 -37.517)scale(.69635 .37124)" gradientUnits="userSpaceOnUse"><stop class="nhxwftdxc"/><stop offset="1" class="axz4ivbcr"/></radialGradient><radialGradient id="iqDB3gk" cx="0" cy="0" r="1" gradientTransform="matrix(.42188 .76563 -.90043 .49616 27.862 14.39)" gradientUnits="userSpaceOnUse"><stop class="i9x98ebrr"/><stop offset="1" class="yk15gqvvr"/></radialGradient><radialGradient id="i4ouwad" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59375 0 0 -2.7696 26.255 16.938)" gradientUnits="userSpaceOnUse"><stop class="oliv2bcuo"/><stop offset="1" class="k1yfa1pxl"/></radialGradient><radialGradient id="i4Tqhuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32031 0 6.99 16.524)" gradientUnits="userSpaceOnUse"><stop class="byn2s1bln"/><stop offset="1" class="gno4tuy0h"/></radialGradient><radialGradient id="ieD3RNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.75 8.9375 0 19.568 29.266)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="finomov8p"/><stop offset="1" class="qfj8esbtd"/></radialGradient><radialGradient id="iIwp5cd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1875 3.5231 -.87474 -.79141 9.63 19.891)" gradientUnits="userSpaceOnUse"><stop class="xo_dbbcrk"/><stop offset="1" class="fipf36vin"/></radialGradient><radialGradient id="imS1QXW" cx="0" cy="0" r="1" gradientTransform="matrix(5.31253 3.28121 -.93453 1.51307 19.786 20.297)" gradientUnits="userSpaceOnUse"><stop class="zk2mfu__s"/><stop offset="1" class="xx0si6etu"/></radialGradient><radialGradient id="irDOrTd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50001 -3.65624 1.29065 -.8825 24.13 26.11)" gradientUnits="userSpaceOnUse"><stop class="wz_ov4j-l"/><stop offset="1" class="a7wya1e_a"/><stop offset="1" class="khy4tkbbd"/></radialGradient><radialGradient id="iDjJxUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.46944 -4.08022 0 26.662 16.828)" gradientUnits="userSpaceOnUse"><stop class="tg0z2qhwd"/><stop offset="1" class="hpe9ehb7d"/></radialGradient><radialGradient id="iUHqUwe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.96875 2.34375 -1.44391 -2.44503 13.38 18.36)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="fni_1r5pr"/><stop offset="1" class="rx-90_bsr"/></radialGradient><radialGradient id="iyeb8ne" cx="0" cy="0" r="1" gradientTransform="rotate(94.109 4.073 16.502)scale(2.69357 3.19975)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iJv4lKc" cx="0" cy="0" r="1" gradientTransform="matrix(1.40118 2.42441 -1.102 .6369 10.499 14.724)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iopQswe" cx="0" cy="0" r="1" gradientTransform="matrix(.2592 1.1085 -.97239 .22737 11.237 14.471)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iUL9e8c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.91463 .39698 -.70225 -8.69394 18.274 13.095)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iJQPfwr" cx="0" cy="0" r="1" gradientTransform="matrix(-.09018 12.27317 -10.16363 -.07468 16.672 7.629)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="zgchiqbcj"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="imAOH6C" cx="0" cy="0" r="1" gradientTransform="matrix(-.10182 -1.26056 1.55995 -.126 17.85 12.069)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iRucGdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.13837 -1.03288 1.12402 -.15058 13.435 12.296)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iK4N7Td" cx="0" cy="0" r="1" gradientTransform="matrix(1.13452 -.09164 .46577 5.76647 11.075 14.04)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iRU9knd" cx="0" cy="0" r="1" gradientTransform="matrix(2.18065 -3.6336 .82301 .49392 9.904 10.93)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iO7qACd" cx="0" cy="0" r="1" gradientTransform="rotate(-107.877 14.143 2.822)scale(9.92521 10.9329)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iJKsrCd" cx="0" cy="0" r="1" gradientTransform="matrix(1.9771 .52228 -.31331 1.18604 17.066 8.1)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iCCiWWb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5903 1.86114 -1.18295 -1.0108 16.587 13.159)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="iddKqyv" cx="0" cy="0" r="1" gradientTransform="matrix(-.27584 -3.415 6.05072 -.48874 10.598 12.217)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="ih9lUDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.27584 -3.415 6.05072 -.48874 20.084 11.451)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iAmT8fb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15106 -.9191 .48949 -1.67815 18.898 5.608)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="ilsLFrd" cx="0" cy="0" r="1" gradientTransform="matrix(.9629 1.3179 -3.05162 2.2296 14.065 4.492)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iAjatke" cx="0" cy="0" r="1" gradientTransform="rotate(155.542 7.01 4.493)scale(3.81706 1.06238)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iRJFWde" cx="0" cy="0" r="1" gradientTransform="matrix(2.63845 -5.03453 5.57774 2.92313 10.268 10.586)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iU2Rkre" cx="0" cy="0" r="1" gradientTransform="matrix(3.18765 .50029 -.28427 1.81126 18.485 6.48)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iJmb3He" cx="0" cy="0" r="1" gradientTransform="rotate(-124.297 12.94 .004)scale(4.02059 2.22228)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="ikfvfLc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37462 -1.97282 1.4009 -.97612 19.632 10.46)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iQKCKQb" cx="0" cy="0" r="1" gradientTransform="rotate(161.658 9.273 4.72)scale(4.57654 5.02626)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iiiAGPQ" cx="0" cy="0" r="1" gradientTransform="rotate(102.101 6.624 10.534)scale(.37789 1.7023)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="i2SS17b" cx="0" cy="0" r="1" gradientTransform="rotate(112.942 7.303 8.791)scale(3.99432 10.1971)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iP8xkrd" cx="0" cy="0" r="1" gradientTransform="matrix(.0616 .76271 -1.21318 .098 17.616 12.28)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="imdTteb" cx="0" cy="0" r="1" gradientTransform="matrix(-.24011 -.26268 .36165 -.33058 17.407 12.377)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iT01m8d" cx="0" cy="0" r="1" gradientTransform="rotate(85.382 -.08 13.63)scale(.76523 1.2172)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="isy7Ryd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.938 -.095)scale(.46489 .5588)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6aBSee" cx="0" cy="0" r="1" gradientTransform="matrix(.76121 2.06115 -1.9665 .72626 19.906 12.109)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="imSklpc" cx="0" cy="0" r="1" gradientTransform="matrix(.6585 -1.07615 .90203 .55195 20.287 12.594)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="i7TVfUb" cx="0" cy="0" r="1" gradientTransform="rotate(-176.298 5.714 6.541)scale(1.59659 1.5696)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="itXtitd" cx="0" cy="0" r="1" gradientTransform="matrix(.41255 -.92529 .86435 .38538 15.335 16.855)" gradientUnits="userSpaceOnUse"><stop class="i-j5225_d"/><stop offset="1" class="i8x8j-rud"/></radialGradient><linearGradient id="iqorGir" x1="3.687" x2="6.401" y1="13.03" y2="13.03" gradientUnits="userSpaceOnUse"><stop class="a0zgi_bwh"/><stop offset="1" class="jnwaoyb2q"/></linearGradient><linearGradient id="ihCBmXb" x1="3.993" x2="6.149" y1="12.138" y2="14.287" gradientUnits="userSpaceOnUse"><stop class="aa675bbim"/><stop offset="1" class="ocrbm8rzk"/></linearGradient><linearGradient id="iEjF5ud" x1="2.571" x2="4.995" y1="13.474" y2="13.474" gradientUnits="userSpaceOnUse"><stop class="a0zgi_bwh"/><stop offset="1" class="jnwaoyb2q"/></linearGradient><linearGradient id="ihPWpZb" x1="2.926" x2="5.336" y1="12.408" y2="14.621" gradientUnits="userSpaceOnUse"><stop class="aa675bbim"/><stop offset="1" class="ocrbm8rzk"/></linearGradient><linearGradient id="ipmrrpc" x1="2.645" x2="5.436" y1="14.331" y2="14.331" gradientUnits="userSpaceOnUse"><stop class="a0zgi_bwh"/><stop offset="1" class="jnwaoyb2q"/></linearGradient><linearGradient id="iyU4HGe" x1="2.85" x2="5.442" y1="13.399" y2="15.398" gradientUnits="userSpaceOnUse"><stop class="aa675bbim"/><stop offset="1" class="ocrbm8rzk"/></linearGradient><linearGradient id="iQVUmZc" x1="2.959" x2="5.755" y1="15.204" y2="15.204" gradientUnits="userSpaceOnUse"><stop class="a0zgi_bwh"/><stop offset="1" class="jnwaoyb2q"/></linearGradient><linearGradient id="iqBaokb" x1="8.486" x2="7.645" y1="15.682" y2="15.682" gradientUnits="userSpaceOnUse"><stop offset=".005" class="vh9-3hb_g"/><stop offset="1" class="av75tqbdq"/></linearGradient><linearGradient id="inEELwd" x1="28.122" x2="25.428" y1="13.839" y2="13.798" gradientUnits="userSpaceOnUse"><stop class="fgtz1bcwy"/><stop offset="1" class="qx0aig_op"/></linearGradient><linearGradient id="i7Ar4fe" x1="29.194" x2="26.65" y1="14.361" y2="14.328" gradientUnits="userSpaceOnUse"><stop class="fgtz1bcwy"/><stop offset="1" class="qx0aig_op"/></linearGradient><linearGradient id="iwWEx0d" x1="29.167" x2="26.398" y1="15.122" y2="15.078" gradientUnits="userSpaceOnUse"><stop class="fgtz1bcwy"/><stop offset="1" class="qx0aig_op"/></linearGradient><linearGradient id="ixST6Jb" x1="28.853" x2="26.078" y1="15.9" y2="15.85" gradientUnits="userSpaceOnUse"><stop class="fgtz1bcwy"/><stop offset="1" class="qx0aig_op"/></linearGradient><linearGradient id="i2e1vmd" x1="14.818" x2="16.752" y1="19.61" y2="21.226" gradientUnits="userSpaceOnUse"><stop class="mrdwr2nvn"/><stop offset="1" class="fg3-p40eh"/></linearGradient><linearGradient id="iY9kAdR" x1="20.61" x2="16.518" y1="14.501" y2="14.831" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="itWucLZ" x1="15.697" x2="16.501" y1="14.087" y2="14.022" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iyASV4c" x1="14.677" x2="15.691" y1="14.022" y2="13.996" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iVjEpLc" x1="15.727" x2="15.792" y1="14.462" y2="15.263" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="ivYYuNb" x1="15.557" x2="15.589" y1="12.349" y2="12.743" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="itUJ43c" x1="15.902" x2="15.897" y1="15.085" y2="15.03" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="i9SAfbG" x1="20.246" x2="10.729" y1="7.577" y2="8.346" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iGmN27d" x1="18.351" x2="18.071" y1="12.273" y2="12.478" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0E1iRc" x1="14.215" x2="13.936" y1="12.606" y2="12.811" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ih9XiEc" x1="21.621" x2="20.652" y1="12.034" y2="14.171" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iEveZvb" x1="10.125" x2="11.486" y1="13.629" y2="13.398" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="iEqxoVc" x1="3.139" x2="5.946" y1="14.426" y2="16.107" gradientUnits="userSpaceOnUse"><stop class="aa675bbim"/><stop offset="1" class="ocrbm8rzk"/></linearGradient><linearGradient id="iNnMR9c" x1="9.349" x2="12.349" y1="26.079" y2="20.422" gradientUnits="userSpaceOnUse"><stop class="uwc1wf0xf"/><stop offset="1" class="mpi5j3bwz"/></linearGradient><filter id="igVj7md" width="3.652" height="3.139" x="2.993" y="11.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".25"/></filter><filter id="inUxH8c" width="3.727" height="3.323" x="1.914" y="11.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".25"/></filter><filter id="itkqyKb" width="3.867" height="3.135" x="1.845" y="12.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".25"/></filter><filter id="iPZcHdH" width="3.508" height="5.156" x="23.526" y="11.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.607843 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4191"/></filter><filter id="iL1Ethb" width="23.107" height="13.423" x="4.271" y="16.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.294118 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4191"/></filter><filter id="iTD7xve" width="10.486" height="11.854" x="10.652" y="7.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4191" result="effect2_innerShadow_4002_4191"/></filter><filter id="irfZoHd" width="3.768" height="4.763" x="13.668" y="11.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".5"/></filter><filter id="iItNQps" width="1.968" height="2.959" x="14.748" y="12.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".05"/></filter><filter id="icKFaCe" width="12.116" height="8.445" x="9.241" y="4.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4191" result="effect2_innerShadow_4002_4191"/></filter><filter id="iV4OEpI" width="2.237" height="1.051" x="16.886" y="9.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4191"/></filter><filter id="iVA462b" width="2.176" height="1.231" x="11.976" y="9.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4191"/></filter><filter id="iPsqTFd" width="6.618" height="6.502" x="9.312" y="5.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".25"/></filter><filter id="iUrrMCd" width="6.572" height="5.584" x="14.79" y="5.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".25"/></filter><filter id="i2erJyA" width=".729" height=".693" x="16.922" y="11.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".05"/></filter><filter id="i4h0sce" width=".875" height=".893" x="17.712" y="11.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".1"/></filter><filter id="i2m68Ht" width=".97" height="1.009" x="13.53" y="12.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".1"/></filter><filter id="iP3KAuk" width=".85" height=".703" x="12.825" y="12.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".05"/></filter><filter id="iLsmY4m" width="1.354" height="2.26" x="9.925" y="12.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".125"/></filter><filter id="iREE9Pd" width="1.361" height="2.298" x="20.061" y="11.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".125"/></filter><filter id="iwXw2yb" width="2.277" height="1.241" x="11.875" y="10.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".125"/></filter><filter id="iWuKxAc" width="2.335" height="1.043" x="16.805" y="9.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".125"/></filter><filter id="ix9S4yd" width="4.031" height="2.858" x="2.143" y="13.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".25"/></filter><filter id="iKavNKb" width="1.88" height="1.863" x="14.878" y="15.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".05"/></filter><filter id="ibjmFec" width="4.656" height="7.656" x="8.349" y="18.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4191" stdDeviation=".4"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-shrugging-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a0zgi_bwh {
  stop-color: var(--svg-color--d39d7f, #D39D7F);
}

.a3e1obbdc {
  stop-color: var(--svg-color--c89678, #C89678);
  stop-opacity: 0;
}

.a7wya1e_a {
  stop-color: var(--svg-color--ff4412, #FF4412);
  stop-opacity: 0;
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.aa675bbim {
  stop-color: var(--svg-color--dda991, #DDA991);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.av75tqbdq {
  stop-color: var(--svg-color--c48f75, #C48F75);
  stop-opacity: 0;
}

.avsbxl_7i {
  fill-rule: evenodd;
  d: path("M2.192 13.135a.7.7 0 0 1 .98.142l.086.119c.301.419.763 1.06 1.779 1.06a.7.7 0 1 1 0 1.4c-1.776 0-2.637-1.24-2.925-1.653l-.062-.088a.7.7 0 0 1 .142-.98");
}

.axz4ivbcr {
  stop-color: var(--svg-color--eabca1, #EABCA1);
  stop-opacity: 0;
}

.az79hwb6r {
  d: path("M9.13 20.76a.25.25 0 0 1-.375-.217V17.68a.6.6 0 0 0-.6-.6H4.871a.6.6 0 0 0-.6.6v4.587c-.005.849.112 2.507 1.484 3.383c1.149.733 2.501.57 3.214.347a.16.16 0 0 1 .208.148v3.706c0 .083.067.15.15.15h12.994a.15.15 0 0 0 .15-.15v-3.706c0-.106.108-.18.209-.148c.713.222 2.064.386 3.213-.347c1.372-.876 1.49-2.534 1.485-3.383V17.68a.6.6 0 0 0-.6-.6h-3.285a.6.6 0 0 0-.6.6v2.864a.25.25 0 0 1-.375.217l-6.694-3.932z");
}

.be1dcehns {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M12.193 10.663a2.6 2.6 0 0 1 1.607-.47a.262.262 0 1 1-.021.523a2.1 2.1 0 0 0-1.282.373a1 1 0 0 0-.082.063l-.002.002a.262.262 0 0 1-.353-.386z");
}

.bn4os6vdu {
  stop-color: var(--svg-color--cc9b7b, #CC9B7B);
  stop-opacity: 0;
}

.buagh_b2g {
  d: path("M26.916 16.641a.25.25 0 0 0-.25-.25h-2.93a.25.25 0 0 0-.25.25v.844h3.43z");
}

.byn2s1bln {
  stop-color: var(--svg-color--d45533, #D45533);
}

.c5kvt8p1h {
  d: path("M15.412 7.932a2 2 0 0 1-.073-.124a.63.63 0 0 0-.61-.347l-1.197.097c-1.735.14-3.026 1.676-2.884 3.43l.02.26c-.339-.218-.782-.699-.85-1.53c-.08-1.007.613-1.576 1.056-1.938c.125-.103.23-.189.291-.264q.04-.047.086-.106c.3-.375.836-1.043 1.836-1.397c.471-.167.956-.24 1.359-.267c.472-.03.837.35.875.821l.11 1.35z");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d8_6n5bpd {
  stop-color: var(--svg-color--cd8b81, #CD8B81);
}

.d8xtj4b7u {
  stop-color: var(--svg-color--c78078, #C78078);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dkf5o985m {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.351 13.58q-.018-.9-.04-1.798a.901.901 0 0 1 .04 1.798");
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

.dw7rkubkg {
  d: path("M4.779 16.641a.25.25 0 0 1 .25-.25h2.93a.25.25 0 0 1 .25.25v.844h-3.43z");
}

.dzezh-eno {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M2.645 13.473c.238.483.966 1.38 2.267 1.534");
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e490wkn-s {
  stop-color: var(--svg-color--cc9b7b, #CC9B7B);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.emo1hubkw {
  d: path("M14.3 12.841c-.022-.27-.256-.433-.32-.482l-.25.283l.194.325z");
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

.fdouacc8b {
  fill-rule: evenodd;
  d: path("M2.224 12.113a.7.7 0 0 1 .978.157q.051.071.114.168c.262.391.704 1.052 1.516 1.4a.7.7 0 0 1-.551 1.287c-1.246-.534-1.935-1.603-2.156-1.946l-.058-.089a.7.7 0 0 1 .157-.977");
}

.fds4yd4ht {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.138 12.857l-.458 1.776c-.073.364.2.7.547.672l.74-.06c.346-.028.562-.409.432-.75l-.64-1.688c-.138-.375-.54-.342-.621.05");
}

.fg3-p40eh {
  stop-color: var(--svg-color--f4b193, #F4B193);
}

.fgtz1bcwy {
  stop-color: var(--svg-color--ddab88, #DDAB88);
}

.finomov8p {
  stop-color: var(--svg-color--ff7e34, #FF7E34);
}

.fipf36vin {
  stop-color: var(--svg-color--ff6f3a, #FF6F3A);
  stop-opacity: 0;
}

.fni_1r5pr {
  stop-color: var(--svg-color--c94829, #C94829);
}

.ft5dv1b6b {
  fill: none;
}

.g0ppexbky {
  d: path("M18.388 12.5a.8.8 0 0 0-.253-.417l-.223.288l.128.205z");
}

.g35jyabao {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M2.943 14.524c.293.452 1.122 1.258 2.431 1.258");
}

.g5-tshirv {
  fill-rule: evenodd;
  d: path("M28.432 11.797a.7.7 0 0 0-.977.157a2 2 0 0 0-.115.183q-.005.004-.006.01l-.001.001c-.034.058-.066.114-.105.174c-.077.12-.17.25-.294.37c-.232.228-.607.468-1.267.5a.7.7 0 0 0 .069 1.398c1.024-.05 1.717-.446 2.178-.898a3.4 3.4 0 0 0 .495-.618a5 5 0 0 0 .13-.216l.004-.006c.029-.05.04-.07.045-.076l.001-.002a.7.7 0 0 0-.157-.977");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g7f0b-9ed {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.533 12.015c.066.075-.051.182-.184.3s-.232.2-.299.125s-.011-.23.122-.348s.295-.152.36-.077");
}

.g98ji6enx {
  d: path("M19.694 6.694c.497.128.958.43 1.271.892c.501.736.511 1.664.092 2.383a1.47 1.47 0 0 0-.188.843l.09 1.117a1.65 1.65 0 0 0-.647-.202l-.048-1.516a1.367 1.367 0 0 0-1.405-1.242l-1.317.107a2.29 2.29 0 0 1-2.188-1.189a.63.63 0 0 0-.61-.346l-1.197.096c-1.735.14-3.026 1.676-2.885 3.43l.146 1.444a1.6 1.6 0 0 0-.657.302l-.091-1.128a1.47 1.47 0 0 0-.32-.802a2.26 2.26 0 0 1-.321-2.288a2.2 2.2 0 0 1 1.136-1.158a2.53 2.53 0 0 0 1.217-1.148a2.19 2.19 0 0 1 2.648-1.077c.372.127.775.095 1.122-.09c.255-.133.539-.222.843-.246a2.19 2.19 0 0 1 1.956.912c.328.456.81.767 1.353.906");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gno4tuy0h {
  stop-color: var(--svg-color--cc4525, #CC4525);
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

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h6a5-kjll {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.25 10.923c.227-.193.805-.546 1.527-.484");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hpe9ehb7d {
  stop-color: var(--svg-color--ff8a36, #FF8A36);
  stop-opacity: 0;
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i-j5225_d {
  stop-color: var(--svg-color--d8a197, #D8A197);
}

.i2dy_3bdc {
  stop-color: var(--svg-color--d0a07f, #D0A07F);
}

.i8x8j-rud {
  stop-color: var(--svg-color--d8a197, #D8A197);
  stop-opacity: 0;
}

.i9k-0jbxt {
  stop-color: var(--svg-color--cd8b81, #CD8B81);
  stop-opacity: 0;
}

.i9x98ebrr {
  stop-color: var(--svg-color--cc936c, #CC936C);
}

.igpgsacmg {
  d: path("m20.341 10.687l-.075-.59a1.38 1.38 0 0 0-1.416-1.235l-1.302.105a2.26 2.26 0 0 1-2.072-1.025s-.046-.086-.104-.24c-.359-.938.513-1.746 1.503-1.576c.862.148 1.826.414 2.586.831c1.71.939 1.661 2.754.88 3.73");
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.iwmsipbyi {
  d: path("M20.3 14.114c.313-.036.6-.167.826-.36l.07.876a2.05 2.05 0 0 1-1.107 2q.2-.532.236-1.136z");
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j2l239u6e {
  stop-color: var(--svg-color--c89678, #C89678);
}

.j3foh4beb {
  cx: 15.818px;
  cy: 16.304px;
  fill: var(--svg-color--87004d, #87004D);
  rx: 0.74px;
  ry: 0.732px;
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jnwaoyb2q {
  stop-color: var(--svg-color--c69675, #C69675);
}

.jp7u36bby {
  d: path("M13.475 12.164a.842.842 0 0 0-.723 1.125l1.621-.13a.847.847 0 0 0-.898-.995");
}

.jsiezd-_e {
  stop-color: var(--svg-color--eabc9e, #EABC9E);
}

.k_s1uxbby {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.765 10.353c-.256-.153-.882-.41-1.585-.232");
}

.k1yfa1pxl {
  stop-color: var(--svg-color--dc4724, #DC4724);
}

.kcb-zebvi {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.26 11.924a1.32 1.32 0 0 0-1.193 1.098a.26.26 0 0 0 .277.3l2.098-.17a.217.217 0 0 0 .193-.272a1.32 1.32 0 0 0-1.375-.956");
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.khy4tkbbd {
  stop-color: var(--svg-color--fb4b61, #FB4B61);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lfijyebbp {
  d: path("M10.742 11.944a1.518 1.518 0 0 0 .373 2.998a72 72 0 0 1-.373-2.998");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lso1_vbso {
  d: path("M20.363 14.195q-.027-1.508-.069-3.014a1.518 1.518 0 0 1 .069 3.014");
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m1u9pgbwn {
  d: path("M11.308 16.273a3.69 3.69 0 0 0 3.912 2.907l1.773-.143a3.69 3.69 0 0 0 3.395-3.497c-.033-1.78-.063-3.552-.124-5.329a1.367 1.367 0 0 0-1.405-1.242l-1.317.107a2.29 2.29 0 0 1-2.188-1.189a.63.63 0 0 0-.61-.346l-1.197.096c-1.735.14-3.026 1.676-2.885 3.43c.142 1.75.39 3.462.646 5.206");
}

.m6knzmbvc {
  d: path("m15.22 12.665l-.36 1.769c-.073.363.2.7.547.671l.74-.06c.346-.028.562-.408.432-.75l-.64-1.688c-.138-.374-.637-.334-.719.058");
}

.m6ohn2s-t {
  d: path("M5.744 11.604a.75.75 0 0 1 1.051.138l.805 1.047c.37.48.57 1.07.57 1.676v2.14H4.911v-2.448a.25.25 0 0 1 .25-.25h1.376a1.3 1.3 0 0 0-.127-.204l-.805-1.047a.75.75 0 0 1 .138-1.052");
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.m8q4dvb9z {
  fill: var(--svg-color--000, #000);
  d: path("M14.023 12.964a.48.48 0 0 0-.519-.441a.48.48 0 0 0-.37.736l.85-.069a.5.5 0 0 0 .04-.226");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mj2rsfbdi {
  d: path("M17.582 11.832a.842.842 0 0 1 .894.995l-1.621.131a.845.845 0 0 1 .727-1.126");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mpi5j3bwz {
  stop-color: var(--svg-color--c13318, #C13318);
  stop-opacity: 0;
}

.mrdwr2nvn {
  stop-color: var(--svg-color--bc716b, #BC716B);
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n7mx21thj {
  fill-rule: evenodd;
  d: path("M29.503 13.135a.7.7 0 0 0-.98.142l-.086.119c-.301.419-.763 1.159-1.779 1.159c-.386 0-.7.215-.7.602a.7.7 0 0 0 .7.7c1.776 0 2.637-1.24 2.925-1.654l.062-.088a.7.7 0 0 0-.142-.98");
}

.n8p7o9f4r {
  fill: var(--svg-color--c69675, #C69675);
  d: path("M5.744 11.604a.75.75 0 0 1 1.051.138l.805 1.047c.37.48.57 1.07.57 1.676v2.14H4.911v-2.448a.25.25 0 0 1 .25-.25h1.376a1.3 1.3 0 0 0-.127-.204l-.805-1.047a.75.75 0 0 1 .138-1.052");
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.nhxwftdxc {
  stop-color: var(--svg-color--eabca1, #EABCA1);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.ocrbm8rzk {
  stop-color: var(--svg-color--dda991, #DDA991);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oliv2bcuo {
  stop-color: var(--svg-color--fe7047, #FE7047);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.oy-bjdb4l {
  d: path("M15.818 20.852c-1.104 0-2-.802-2-1.79v-2.115c0-.988.896-1.79 2-1.79s2 .802 2 1.79v2.115c0 .988-.896 1.79-2 1.79");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnu47pbah {
  cx: 13.25px;
  cy: 12.543px;
  rx: 0.367px;
  ry: 0.186px;
}

.po_pxuzrh {
  d: path("M25.951 11.604a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.259v-2.698h-1.627q.053-.107.128-.204l.804-1.047a.75.75 0 0 0-.138-1.052");
}

.pptea1vyv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.35 25.61c.176-1.146.955-3.881 2.655-5.656");
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

.qfj8esbtd {
  stop-color: var(--svg-color--f05419, #F05419);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qx0aig_op {
  stop-color: var(--svg-color--e7b690, #E7B690);
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r4hwau21e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M3.793 12.184c.196.501 1.018 1.387 2.052 1.539");
}

.r70awwbve {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.808 12.564a.902.902 0 0 0 .221 1.76a73 73 0 0 1-.221-1.76");
}

.r9zbgw02g {
  fill-rule: evenodd;
  d: path("M29.19 14.166a.7.7 0 0 0-.979.142c-.18.242-.653.84-1.873.84a.7.7 0 1 0 0 1.4c1.828 0 2.668-.964 2.995-1.402a.7.7 0 0 0-.142-.98");
}

.rcm4jyv6c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M2.715 12.464c.196.501.844 1.458 2.127 1.723");
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rx-90_bsr {
  stop-color: var(--svg-color--c94829, #C94829);
  stop-opacity: 0;
}

.rzmbtdl4c {
  d: path("M11.159 14.852a1.55 1.55 0 0 1-.874-.221l.07.875c.069.84.63 1.547 1.415 1.796a3.9 3.9 0 0 1-.415-1.083z");
}

.s_o7_jesn {
  stop-color: var(--svg-color--d0a07f, #D0A07F);
  stop-opacity: 0;
}

.sfqolabyf {
  cx: 15.818px;
  cy: 16.304px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  rx: 0.74px;
  ry: 0.732px;
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.tg0z2qhwd {
  stop-color: var(--svg-color--ff8a36, #FF8A36);
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.ujoylbbsx {
  fill: var(--svg-color--000, #000);
  d: path("M17.169 12.71a.48.48 0 0 1 .441-.52a.48.48 0 0 1 .484.668l-.85.069a.44.44 0 0 1-.075-.217");
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uwc1wf0xf {
  stop-color: var(--svg-color--c13318, #C13318);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vh9-3hb_g {
  stop-color: var(--svg-color--c48f75, #C48F75);
}

.vlstqlbst {
  fill-rule: evenodd;
  d: path("M29.471 12.113a.7.7 0 0 0-.977.157q-.05.071-.115.168c-.262.391-.921 1.114-1.733 1.461c-.355.152-.503.449-.32.875c.152.355.733.503 1.088.35c1.246-.533 1.935-1.602 2.156-1.945l.058-.089a.7.7 0 0 0-.157-.977");
}

.vtr0yklkc {
  fill: var(--svg-color--e7b690, #E7B690);
  d: path("M25.951 11.604a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.259v-2.698h-1.627q.053-.107.128-.204l.804-1.047a.75.75 0 0 0-.138-1.052");
}

.w2-ufizde {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.756 11.561a1.32 1.32 0 0 1 1.354.893a.26.26 0 0 1-.226.34l-2.098.17a.217.217 0 0 1-.234-.239a1.32 1.32 0 0 1 1.204-1.164");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wj8c2lbyu {
  stop-color: var(--svg-color--c27b54, #C27B54);
}

.wr4xjslhr {
  stop-color: var(--svg-color--eabc9e, #EABC9E);
  stop-opacity: 0;
}

.wrv1zf4oz {
  d: path("M17.533 12.015c.066.075-.051.182-.184.3s-.232.2-.299.125s-.011-.23.122-.348s.295-.152.36-.077");
}

.wsq8b2bdn {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M18.917 10.223a1.75 1.75 0 0 0-.677-.334c-.294-.067-.654-.063-1.145.038a.261.261 0 1 0 .106.513c.447-.092.727-.086.922-.041c.191.043.325.128.483.245a.261.261 0 1 0 .311-.42");
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wz_ov4j-l {
  stop-color: var(--svg-color--fb4b61, #FB4B61);
}

.xo_dbbcrk {
  stop-color: var(--svg-color--ff6f3a, #FF6F3A);
}

.xx0si6etu {
  stop-color: var(--svg-color--ff7e32, #FF7E32);
  stop-opacity: 0;
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

.ye-2zryyr {
  stop-color: var(--svg-color--c78078, #C78078);
  stop-opacity: 0;
}

.yk15gqvvr {
  stop-color: var(--svg-color--cc936c, #CC936C);
  stop-opacity: 0;
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yn5ij1ffp {
  stop-color: var(--svg-color--c27b54, #C27B54);
  stop-opacity: 0;
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.ywswr-y1s {
  cx: 13.25px;
  cy: 12.543px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.367px;
  ry: 0.186px;
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

.z8aicjn7g {
  fill-rule: evenodd;
  d: path("M2.504 14.166a.7.7 0 0 1 .98.142c.181.242.653.84 1.873.84a.7.7 0 1 1 0 1.4c-1.827 0-2.668-.964-2.994-1.402a.7.7 0 0 1 .141-.98");
}

.zdtgd2jja {
  fill-rule: evenodd;
  d: path("M3.263 11.797a.7.7 0 0 1 .978.157a2 2 0 0 1 .12.192l.001.002q.05.086.105.174c.077.12.17.25.294.37c.233.228.608.468 1.267.5a.7.7 0 0 1-.068 1.398c-1.025-.05-1.718-.446-2.179-.898a3.5 3.5 0 0 1-.495-.618a6 6 0 0 1-.13-.216l-.004-.006c-.029-.05-.04-.07-.045-.076v-.002a.7.7 0 0 1 .156-.977");
}

.zgchiqbcj {
  stop-color: var(--svg-color--b36e91, #B36E91);
  stop-opacity: 0;
}

.zk2mfu__s {
  stop-color: var(--svg-color--ff7e32, #FF7E32);
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

</style>
