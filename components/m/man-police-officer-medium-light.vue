<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="upydt32_o"/><path fill="url(#i3b9cme)" class="ir5uabcyf"/><path fill="url(#iT6XAqe)" class="ir5uabcyf"/><path fill="url(#iTFqkvb)" class="ir5uabcyf"/><path fill="url(#i6dLLtb)" class="ir5uabcyf"/><g filter="url(#iRnMu8b)"><path class="skgxszbhw"/></g><path fill="url(#iVk8ZRb)" class="thtcysb5g"/><path fill="url(#iySxojc)" class="thtcysb5g"/><path fill="url(#iBT0Egc)" class="yvy6tz2sx"/><path fill="url(#iSWq0Oc)" class="yvy6tz2sx"/><g filter="url(#iIvRdIe)"><path fill="url(#iPxdGmJ)" class="gfcus0k-b"/><path fill="url(#icUCMXd)" class="gfcus0k-b"/><path fill="url(#iDtHPwb)" class="gfcus0k-b"/><path fill="url(#ikLUynd)" class="gfcus0k-b"/></g><path fill="url(#iXh9ybH)" class="ckyg--8tq"/><path fill="url(#iaSWI7d)" class="ckyg--8tq"/><path fill="url(#ihSlXYc)" class="ckyg--8tq"/><g filter="url(#iINetge)"><path class="g0x0s6b7k"/><path fill="url(#ie1yCCd)" class="zstiy-bhq"/></g><path fill="url(#iJ1vlub)" class="zstiy-bhq"/><g filter="url(#ihs7vQm)"><path class="trkjkfbvt"/><path fill="url(#i4K7vYT)" class="jdcv0xbln"/><path fill="url(#i7KLMve)" class="jdcv0xbln"/></g><path fill="url(#i8sDatb)" class="jdcv0xbln"/><g filter="url(#ioOYGAe)"><path fill="url(#iI6PXQi)" class="frts9nbwi"/><path fill="url(#iIGWG6j)" class="frts9nbwi"/></g><g filter="url(#i2FVafe)"><path fill="url(#iF5yRae)" class="oigr0yrty"/></g><g filter="url(#iOCdD2R)"><rect fill="url(#i8yzP5c)" class="f5rlg0klg"/></g><g filter="url(#iGmilDd)"><circle fill="url(#iPJJDwd)" class="jhlam1b5t"/></g><g filter="url(#iCGFJCa)"><circle fill="url(#iQTwFob)" class="noi50fbya"/></g><g filter="url(#iy5Nmji)"><circle fill="url(#is7s2pd)" class="q_tju-qsy"/><circle fill="url(#iS1wa4d)" class="q_tju-qsy"/></g><g filter="url(#irKAQqc)"><circle class="i82ua78fp"/><circle fill="url(#iAZUoae)" class="t0v_yxg9a"/><circle fill="url(#iaOOAgc)" class="t0v_yxg9a"/></g><g filter="url(#iF5mUue)"><path fill="url(#ilhWRnd)" class="du2krcctp"/></g><path fill="url(#i7hUaDe)" class="du2krcctp"/><path fill="url(#ijKwhvJ)" class="du2krcctp"/><path fill="url(#iYkydPc)" class="du2krcctp"/><path fill="url(#i78mOue)" class="du2krcctp"/><path fill="url(#ilzrL8e)" class="du2krcctp"/><path fill="url(#ioVTgHe)" class="du2krcctp"/><path fill="url(#i8Kgz7b)" class="du2krcctp"/><path fill="url(#itcTPIe)" class="du2krcctp"/><path fill="url(#iBDmrRc)" class="du2krcctp"/><g filter="url(#ig09IDb)"><path class="lu2nl3b4z"/><path fill="url(#iK08wdb)" class="lenz4noze"/><path fill="url(#iI2xMab)" class="lenz4noze"/><path fill="url(#i3b2Scd)" class="lenz4noze"/><path fill="url(#i8kQZQd)" class="lenz4noze"/><path fill="url(#ioIAInc)" class="lenz4noze"/></g><path fill="url(#iqeyEKc)" class="lenz4noze"/><path fill="url(#iIjwtjb)" class="lenz4noze"/><g filter="url(#iOguYKd)"><path class="uqbs6jb_n"/></g><g filter="url(#i52l8wt)"><path class="lz2s8578j"/><path fill="url(#iyXxqPe)" class="qk0uucc4g"/><path fill="url(#iJOW6Jb)" class="qk0uucc4g"/><path fill="url(#iVgXBMe)" class="qk0uucc4g"/></g><g filter="url(#iWUzZRc)"><path fill="url(#iDbWXDc)" class="ma-141o8x"/></g><g filter="url(#ionxt0c)"><path stroke="url(#iNUL32c)" class="khinnqi3v"/></g><path class="oo1rz0b9x"/><path class="muvillb0h"/><path fill="url(#isXX4yb)" class="xtdwx6-mz"/><path class="jttazbbuk"/><g filter="url(#ixCiZBb)"><path class="gndnptf7z"/><path fill="url(#i7czpBb)" class="hbys9mw7f"/></g><g filter="url(#imASZwd)"><path fill="url(#iUGXRAb)" class="z3jt8_bjd"/></g><path class="jm8r61woq"/><path fill="url(#iRBVY3b)" class="uksv4cbwr"/><path class="x639olrpy"/><g filter="url(#iPgL57c)"><path fill="url(#ihiIZqj)" class="v_zil8baw"/></g><g filter="url(#it4jODe)"><ellipse transform="rotate(-27.914 12.997 11.96)" class="wh6fmbcdq"/><ellipse fill="url(#iUyBvQN)" transform="rotate(-27.914 12.997 11.96)" class="aqk68syot"/></g><g filter="url(#irOdRac)"><path fill="url(#isLM7wb)" class="kotk-bqfm"/><path fill="url(#imyeZ8d)" class="kotk-bqfm"/></g><path fill="url(#iizJfPb)" class="kotk-bqfm"/><g filter="url(#i2hH0ad)"><path class="vbnpoccjx"/></g><g filter="url(#iyIPWJb)"><path fill="url(#iagoo5c)" class="kbhhadb_j"/></g><g filter="url(#i9o4EPf)"><path fill="url(#iIgw5Lc)" class="m8dz_mblr"/><path fill="url(#iTf5cKc)" class="m8dz_mblr"/></g><g filter="url(#iMEbzhe)"><path clip-rule="evenodd" class="z6a5p4bqu"/></g><g filter="url(#iJezDXd)"><path fill="url(#igpewSb)" clip-rule="evenodd" class="sw0blobad"/></g><path fill="url(#iiEONhS)" clip-rule="evenodd" class="sw0blobad"/><path fill="url(#i0rO5Pe)" clip-rule="evenodd" class="sw0blobad"/><defs><radialGradient id="i3b9cme" cx="0" cy="0" r="1" gradientTransform="matrix(.59372 6.27271 -11.9943 1.13527 13.662 18.032)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ewagz7_9h"/><stop offset="1" class="a8t42xt1y"/></radialGradient><radialGradient id="iT6XAqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 0 0 14.4101 8.099 29.934)" gradientUnits="userSpaceOnUse"><stop class="vg5w9dbzr"/><stop offset="1" class="r9aql0tfq"/></radialGradient><radialGradient id="iTFqkvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -12.1562 24.005 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="bglf8cb8f"/><stop offset="1" class="f1vhuirkb"/></radialGradient><radialGradient id="iVk8ZRb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -6.93362 3.8209 .51663 6.443 29.934)" gradientUnits="userSpaceOnUse"><stop class="ff-z7nbub"/><stop offset="1" class="qt_mg48rg"/></radialGradient><radialGradient id="iySxojc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -13.7094 8.287 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="a2jurmb2n"/><stop offset="1" class="xsu_qdbmh"/></radialGradient><radialGradient id="iBT0Egc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 -8.02737 2.31779 -.47822 26.443 29.934)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="f69-7cs4d"/><stop offset="1" class="xf9qqcbnz"/></radialGradient><radialGradient id="iSWq0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.36307 0 0 13.6894 23.945 29.71)" gradientUnits="userSpaceOnUse"><stop offset=".034" class="qjgh28b1y"/><stop offset=".8" class="humbo4erb"/></radialGradient><radialGradient id="iPxdGmJ" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 3.525 14.988)scale(2.34396 3.58278)" gradientUnits="userSpaceOnUse"><stop class="ni0htxbur"/><stop offset="1" class="xsp7-kwpz"/></radialGradient><radialGradient id="icUCMXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 -1.10937 1.05865 1.5358 15.474 24.031)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nlnhxpbkx"/><stop offset="1" class="qk56hfspl"/></radialGradient><radialGradient id="iXh9ybH" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71487 -1.3158 0 15.915 25.22)" gradientUnits="userSpaceOnUse"><stop class="e9hbkmbux"/><stop offset="1" class="fqfyucbrl"/></radialGradient><radialGradient id="ie1yCCd" cx="0" cy="0" r="1" gradientTransform="matrix(.6593 -2.21967 2.48774 .73893 14.283 23.669)" gradientUnits="userSpaceOnUse"><stop class="zy2fe0b7g"/><stop offset="1" class="kdz8adazd"/></radialGradient><radialGradient id="iJ1vlub" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.49506 -2.22013 -.51048 14.005 19.953)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="cxc4ijbrr"/><stop offset="1" class="sjzaf5e-a"/></radialGradient><radialGradient id="i7KLMve" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 .42188 -1.25086 1.38985 17.037 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="bzog60bkg"/><stop offset=".902" class="et8zn2bag"/></radialGradient><radialGradient id="i8sDatb" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 .875 -2.39996 2.31425 17.787 19.906)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="wt_jecb6v"/><stop offset="1" class="tp8jvfpml"/></radialGradient><radialGradient id="iI6PXQi" cx="0" cy="0" r="1" gradientTransform="rotate(148.065 5.885 12.705)scale(2.68809 2.30164)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="xmkjq1brc"/><stop offset="1" class="qooaqh4_d"/></radialGradient><radialGradient id="iIGWG6j" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42188 .20312 -.04646 -.55397 15.349 20)" gradientUnits="userSpaceOnUse"><stop class="of_6980ch"/><stop offset="1" class="ad6u3u09p"/></radialGradient><radialGradient id="iPJJDwd" cx="0" cy="0" r="1" gradientTransform="matrix(2.01634 0 0 3.52861 8.445 12.853)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iS1wa4d" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 30.136 -27.092)scale(1.17502 1.34113)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iAZUoae" cx="0" cy="0" r="1" gradientTransform="matrix(.94363 -1.7356 1.01585 .55231 21.246 13.796)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iaOOAgc" cx="0" cy="0" r="1" gradientTransform="matrix(.29792 .2949 -.38016 .38406 21.294 12.853)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="ilhWRnd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.09687 0 0 -10.3558 19.071 13.3)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="ijKwhvJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.147 -16.3506 0 15.851 6.39)" gradientUnits="userSpaceOnUse"><stop offset=".832" class="a9torj7vm"/><stop offset=".988" class="rwuy40buq"/></radialGradient><radialGradient id="iYkydPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.50153 1.9352 0 18.65 12.046)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="i78mOue" cx="0" cy="0" r="1" gradientTransform="rotate(-93.137 12.222 -.296)scale(1.23742 1.40213)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="ilzrL8e" cx="0" cy="0" r="1" gradientTransform="matrix(1.40742 0 0 6.86873 10.104 13.73)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="ioVTgHe" cx="0" cy="0" r="1" gradientTransform="matrix(3.04942 -4.09166 .9383 .6993 8.97 9.94)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="i8Kgz7b" cx="0" cy="0" r="1" gradientTransform="rotate(-103.789 14.812 2.806)scale(11.8103 13.4888)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="itcTPIe" cx="0" cy="0" r="1" gradientTransform="matrix(2.3848 .80707 -.46892 1.3856 18.08 7.274)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iBDmrRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.99353 -6.26187 0 15.851 10.699)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="pmx6s8bth"/><stop offset="1" class="c9az5fbdm"/></radialGradient><radialGradient id="iK08wdb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.94866 5.0893 -8.65477 -6.71503 20.06 3.99)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="i3b2Scd" cx="0" cy="0" r="1" gradientTransform="matrix(-.07678 -2.13883 1.05043 -.0377 11 8.882)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="i8kQZQd" cx="0" cy="0" r="1" gradientTransform="matrix(.98715 -2.25948 1.84278 .8051 20.675 10.857)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="ioIAInc" cx="0" cy="0" r="1" gradientTransform="rotate(51.134 4.36 17.086)scale(1.81786 1.60504)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iqeyEKc" cx="0" cy="0" r="1" gradientTransform="matrix(.2084 .8999 -1.47944 .3426 16.617 2.97)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iIjwtjb" cx="0" cy="0" r="1" gradientTransform="matrix(.8336 1.03103 -2.31015 1.86779 10.825 4.955)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="isXX4yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03772 -1.2279 0 18.322 12.452)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="u5b_qpb1y"/><stop offset="1" class="n4wew7txz"/></radialGradient><radialGradient id="i7czpBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26641 -.3433 .47265 -.36678 18.062 12.166)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRBVY3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03778 -1.22796 0 13.309 12.452)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="u5b_qpb1y"/><stop offset="1" class="n4wew7txz"/></radialGradient><radialGradient id="iUyBvQN" cx="0" cy="0" r="1" gradientTransform="matrix(-.00889 -.56757 .68224 -.01068 12.98 12.321)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isLM7wb" cx="0" cy="0" r="1" gradientTransform="rotate(153.716 9.95 5.24)scale(8.88768 11.3119)" gradientUnits="userSpaceOnUse"><stop class="b5oikgndb"/><stop offset="1" class="aiodo62qb"/></radialGradient><radialGradient id="iizJfPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56249 1.8125 -5.67441 -1.76097 20.88 4.125)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="lwjbbq_rp"/><stop offset="1" class="c0fdt7b4z"/></radialGradient><radialGradient id="iIgw5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(-141.454 12.31 1.781)scale(8.75158 12.2726)" gradientUnits="userSpaceOnUse"><stop class="hg7hxmbra"/><stop offset="1" class="i8a3pvbms"/></radialGradient><radialGradient id="iTf5cKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.33594 10.5987 0 15.97 11.563)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="e3kv8ccww"/><stop offset=".917" class="t9xlhbbtl"/></radialGradient><radialGradient id="iiEONhS" cx="0" cy="0" r="1" gradientTransform="rotate(101.822 7.538 11.83)scale(1.37287 11.6524)" gradientUnits="userSpaceOnUse"><stop class="q-4mmubff"/><stop offset="1" class="z_4nico_h"/></radialGradient><radialGradient id="i0rO5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(137.81 10.052 8.132)scale(2.38738 2.66614)" gradientUnits="userSpaceOnUse"><stop class="q3vx93ufn"/><stop offset="1" class="ojnx9kp9k"/></radialGradient><filter id="iRnMu8b" width="7.365" height="6.01" x="12.146" y="19.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".25"/></filter><filter id="iIvRdIe" width="4.12" height="2.78" x="13.959" y="21.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.321569 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/></filter><filter id="iINetge" width="3.58" height="4.539" x="12.543" y="19.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/></filter><filter id="ihs7vQm" width="3.6" height="4.539" x="15.879" y="19.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.701961 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/></filter><filter id="ioOYGAe" width="4.352" height="2.805" x="13.739" y="19.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.431373 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/></filter><filter id="i2FVafe" width="3.063" height="3.733" x="18.679" y="24.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2688" result="effect2_innerShadow_4002_2688"/></filter><filter id="iOCdD2R" width="4.306" height="1.334" x="8.789" y="25.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2688" result="effect2_innerShadow_4002_2688"/></filter><filter id="iGmilDd" width="4.036" height="3.836" x="8.445" y="10.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/></filter><filter id="iCGFJCa" width="3.286" height="3.286" x="8.72" y="11.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".25"/></filter><filter id="iy5Nmji" width="4.086" height="4.086" x="19.376" y="10.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/></filter><filter id="irKAQqc" width="3.286" height="3.286" x="19.651" y="11.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".25"/></filter><filter id="iF5mUue" width="12.669" height="14.02" x="9.892" y="6.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2688" result="effect2_innerShadow_4002_2688"/></filter><filter id="ig09IDb" width="14.479" height="9.742" x="8.579" y="2.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/></filter><filter id="iOguYKd" width="3.522" height="4.581" x="13.783" y="11.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".375"/></filter><filter id="i52l8wt" width="2.656" height="3.581" x="14.49" y="11.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".125"/></filter><filter id="iWUzZRc" width="2.656" height="3.581" x="14.49" y="11.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".125"/></filter><filter id="ionxt0c" width="4.097" height="1.632" x="13.77" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".05"/></filter><filter id="ixCiZBb" width=".874" height=".77" x="17.494" y="11.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".05"/></filter><filter id="imASZwd" width=".964" height=".99" x="18.473" y="11.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".1"/></filter><filter id="iPgL57c" width="1.074" height="1.135" x="13.37" y="11.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".1"/></filter><filter id="it4jODe" width="1.019" height=".78" x="12.488" y="11.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".05"/></filter><filter id="irOdRac" width="16.56" height="6.934" x="7.72" y="2.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.537255 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/></filter><filter id="i2hH0ad" width="2.674" height="2.948" x="14.589" y="3.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".075"/></filter><filter id="iyIPWJb" width="2.624" height="2.748" x="14.643" y="3.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2688" result="effect2_innerShadow_4002_2688"/></filter><filter id="i9o4EPf" width="13.155" height="4.088" x="9.342" y="7.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.313726 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.207843 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2688" result="effect2_innerShadow_4002_2688"/></filter><filter id="iMEbzhe" width="13.899" height="3.448" x="9.147" y="5.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2688" stdDeviation=".25"/></filter><filter id="iJezDXd" width="14.033" height="2.72" x="9.028" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2688"/></filter><linearGradient id="i6dLLtb" x1="7.926" x2="8.205" y1="28.477" y2="28.477" gradientUnits="userSpaceOnUse"><stop offset=".229" class="kdpeaetya"/><stop offset="1" class="rvybbdrcw"/></linearGradient><linearGradient id="iDtHPwb" x1="15.193" x2="15.498" y1="22.422" y2="22.766" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="ikLUynd" x1="16.404" x2="16.185" y1="22.258" y2="22.555" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a565onb9e"/><stop offset="1" class="hg3it7oev"/></linearGradient><linearGradient id="iaSWI7d" x1="17.411" x2="16.474" y1="27.875" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ahgk2rx2r"/><stop offset="1" class="nx2bsjb_t"/></linearGradient><linearGradient id="ihSlXYc" x1="14.677" x2="15.915" y1="27.11" y2="27.125" gradientUnits="userSpaceOnUse"><stop class="yvnwtvbdk"/><stop offset="1" class="gd56libvg"/></linearGradient><linearGradient id="i4K7vYT" x1="18.787" x2="17.247" y1="22.422" y2="22.102" gradientUnits="userSpaceOnUse"><stop class="bxeumjbad"/><stop offset="1" class="c8b-jsd8k"/></linearGradient><linearGradient id="iF5yRae" x1="21.325" x2="18.829" y1="26.246" y2="26.246" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="i8yzP5c" x1="13.095" x2="8.763" y1="26.863" y2="26.863" gradientUnits="userSpaceOnUse"><stop class="gxnbt7b-w"/><stop offset="1" class="vhpcois2a"/></linearGradient><linearGradient id="iQTwFob" x1="10.363" x2="9.627" y1="13.173" y2="13.173" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="is7s2pd" x1="22.542" x2="21.602" y1="11.599" y2="14.513" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="i7hUaDe" x1="21.811" x2="16.735" y1="15.188" y2="15.188" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iI2xMab" x1="10.233" x2="13.567" y1="12.546" y2="6.623" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iyXxqPe" x1="14.825" x2="15.903" y1="14.058" y2="14.058" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iJOW6Jb" x1="16.897" x2="15.718" y1="14.428" y2="14.412" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iVgXBMe" x1="16.042" x2="16.042" y1="15.281" y2="14.623" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iDbWXDc" x1="15.818" x2="15.951" y1="12.121" y2="13.4" gradientUnits="userSpaceOnUse"><stop class="jnlvqv3gx"/><stop offset="1" class="yb51f6w_n"/></linearGradient><linearGradient id="iNUL32c" x1="14.627" x2="15.127" y1="17.137" y2="16.347" gradientUnits="userSpaceOnUse"><stop class="h6igylbxq"/><stop offset=".663" class="ir1yl2q7y"/></linearGradient><linearGradient id="iUGXRAb" x1="19.216" x2="18.855" y1="12.131" y2="12.353" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihiIZqj" x1="14.163" x2="13.803" y1="12.131" y2="12.353" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imyeZ8d" x1="7.318" x2="13.13" y1="7.656" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="ylhb00l1u"/><stop offset="1" class="r_91d457c"/></linearGradient><linearGradient id="iagoo5c" x1="16.899" x2="14.793" y1="4.541" y2="4.541" gradientUnits="userSpaceOnUse"><stop class="jo3nm0bcx"/><stop offset="1" class="j3cbwjknw"/></linearGradient><linearGradient id="igpewSb" x1="10.974" x2="21.755" y1="7.7" y2="7.7" gradientUnits="userSpaceOnUse"><stop class="ilj7ybc1n"/><stop offset="1" class="p_hknfval"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-police-officer-medium-light" /></template>
<style>
.a2jurmb2n {
  stop-color: var(--svg-color--3183ce, #3183CE);
}

.a565onb9e {
  stop-color: var(--svg-color--33488b, #33488B);
}

.a8t42xt1y {
  stop-color: var(--svg-color--36a5fc, #36A5FC);
  stop-opacity: 0;
}

.a9torj7vm {
  stop-color: var(--svg-color--c7898e, #C7898E);
  stop-opacity: 0;
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.ad6u3u09p {
  stop-color: var(--svg-color--af798d, #AF798D);
  stop-opacity: 0;
}

.ahgk2rx2r {
  stop-color: var(--svg-color--4a88df, #4A88DF);
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.aiodo62qb {
  stop-color: var(--svg-color--328fdd, #328FDD);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.aqk68syot {
  cx: 12.997px;
  cy: 11.959px;
  rx: 0.448px;
  ry: 0.227px;
}

.b5oikgndb {
  stop-color: var(--svg-color--48a8fb, #48A8FB);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bglf8cb8f {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
}

.bxeumjbad {
  stop-color: var(--svg-color--8be8ff, #8BE8FF);
}

.bzog60bkg {
  stop-color: var(--svg-color--639be0, #639BE0);
}

.c0fdt7b4z {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
  stop-opacity: 0;
}

.c8b-jsd8k {
  stop-color: var(--svg-color--75c1ff, #75C1FF);
  stop-opacity: 0;
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.c9az5fbdm {
  stop-color: var(--svg-color--a56c6a, #A56C6A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckyg--8tq {
  d: path("m17.577 29.934l-.927-5.201a.15.15 0 0 0-.147-.124h-1.078a.15.15 0 0 0-.147.12l-1.025 5.205z");
}

.cxc4ijbrr {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.du2krcctp {
  d: path("m9.959 12.149l.056.002s-.062-.981-.123-1.655c0-.306.123-.674.37-.858l.184-.184c.309-.245.432-.613.432-.98v-.98c0-.307.185-.552.493-.614c.74-.183 2.28-.49 4.5-.49c2.218 0 3.759.307 4.498.49c.247.062.493.307.493.613v.98c0 .368.185.736.432.981c.577.404.54.627.493 1.103c-.062.613-.123 1.655-.123 1.655h.02l-.305 4.548c-.185 2.033-1.783 3.45-3.689 3.45h-3.689c-1.967 0-3.504-1.417-3.688-3.45z");
}

.e3kv8ccww {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
  stop-opacity: 0;
}

.e9hbkmbux {
  stop-color: var(--svg-color--3f7cd5, #3F7CD5);
}

.et8zn2bag {
  stop-color: var(--svg-color--639be0, #639BE0);
  stop-opacity: 0;
}

.ewagz7_9h {
  stop-color: var(--svg-color--3a84b9, #3A84B9);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f1vhuirkb {
  stop-color: var(--svg-color--5bcdff, #5BCDFF);
  stop-opacity: 0;
}

.f5rlg0klg {
  width: 4.156px;
  height: 1.234px;
  x: 8.939px;
  y: 25.977px;
  rx: 0.15px;
}

.f69-7cs4d {
  stop-color: var(--svg-color--55d2ff, #55D2FF);
}

.ff-z7nbub {
  stop-color: var(--svg-color--3bafff, #3BAFFF);
}

.fqfyucbrl {
  stop-color: var(--svg-color--3872d8, #3872D8);
}

.frts9nbwi {
  d: path("M13.74 19.832c.21.57.812 1.582 2.206 2.223c1.454-.75 1.934-1.653 2.145-2.223l-2.145-.332z");
}

.ft5dv1b6b {
  fill: none;
}

.g0x0s6b7k {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gd56libvg {
  stop-color: var(--svg-color--3169c8, #3169C8);
  stop-opacity: 0;
}

.gfcus0k-b {
  d: path("M16.749 24.47a.25.25 0 0 1-.224.139h-1.097a.25.25 0 0 1-.223-.139l-1.246-2.491h4.02z");
}

.gndnptf7z {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.249 11.738c.073.098-.08.217-.253.347c-.174.13-.303.22-.376.123c-.073-.098.009-.282.182-.412c.174-.13.374-.156.447-.058");
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.gxnbt7b-w {
  stop-color: var(--svg-color--ffd04c, #FFD04C);
}

.h6igylbxq {
  stop-color: var(--svg-color--e1ab9c, #E1AB9C);
}

.hbys9mw7f {
  d: path("M18.249 11.738c.073.098-.08.217-.253.347c-.174.13-.303.22-.376.123c-.073-.098.009-.282.182-.412c.174-.13.374-.156.447-.058");
}

.hg3it7oev {
  stop-color: var(--svg-color--1b54be, #1B54BE);
  stop-opacity: 0;
}

.hg7hxmbra {
  stop-color: var(--svg-color--574a69, #574A69);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.humbo4erb {
  stop-color: var(--svg-color--189cf0, #189CF0);
  stop-opacity: 0;
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i82ua78fp {
  cx: 21.294px;
  cy: 12.853px;
  r: 1.143px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.i8a3pvbms {
  stop-color: var(--svg-color--46395b, #46395B);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.ilj7ybc1n {
  stop-color: var(--svg-color--73b8f6, #73B8F6);
}

.ir1yl2q7y {
  stop-color: var(--svg-color--e1ab9c, #E1AB9C);
  stop-opacity: 0;
}

.ir5uabcyf {
  d: path("M3.862 29.934h24.276c-.466-6.297-5.723-11.26-12.138-11.26S4.328 23.638 3.862 29.934");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j3cbwjknw {
  stop-color: var(--svg-color--ffd24b, #FFD24B);
}

.jdcv0xbln {
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.jhlam1b5t {
  cx: 10.363px;
  cy: 12.853px;
  r: 1.918px;
}

.jm8r61woq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.069 11.209c-.75 0-1.384.517-1.557 1.216c-.05.2.103.392.308.392h2.563c.163 0 .294-.15.261-.312a1.61 1.61 0 0 0-1.575-1.296");
}

.jnlvqv3gx {
  stop-color: var(--svg-color--bd8378, #BD8378);
}

.jo3nm0bcx {
  stop-color: var(--svg-color--ffd44c, #FFD44C);
}

.jttazbbuk {
  fill: var(--svg-color--000, #000);
  d: path("M17.737 12.547c0-.327.261-.588.587-.588a.585.585 0 0 1 .522.858h-1.039a.53.53 0 0 1-.07-.27");
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.kbhhadb_j {
  d: path("M14.793 3.756v.922a1.187 1.187 0 0 0 2.374 0v-.923a.2.2 0 0 0-.308-.169l-.252.16a.1.1 0 0 1-.134-.025l-.295-.401a.25.25 0 0 0-.403 0l-.292.4a.1.1 0 0 1-.135.026l-.247-.158a.2.2 0 0 0-.308.168");
}

.kdpeaetya {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
}

.kdz8adazd {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
  stop-opacity: 0;
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.khinnqi3v {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.818 16.449a3.45 3.45 0 0 1-1.591-.377c-.158-.08-.327.097-.228.24a2.17 2.17 0 0 0 1.82.971c.763 0 1.434-.388 1.818-.971c.1-.149-.07-.32-.227-.24c-.46.24-1.003.377-1.592.377Z");
}

.kotk-bqfm {
  d: path("M8.797 4.266c-.625.257-1.356 1.025-.969 2.375s.526 1.802.547 1.859c.04.167.223.5.633.5h.39a.45.45 0 0 0 .301-.133c.142-.135 2.254-1.597 5.827-1.718c3.645.121 6.633 1.583 6.775 1.718a.45.45 0 0 0 .3.133h.391c.41 0 .593-.333.633-.5c.02-.057.16-.51.547-1.86s-.344-2.117-.969-2.374l-5.21-1.853a6 6 0 0 0-4.032.004z");
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lenz4noze {
  d: path("m21.355 5.41l.493.245c.863.429 1.356 1.41 1.171 2.451l-.678 3.493c-.06.36-.299.604-.657.612h-.02s.061-1.041.123-1.654c.05-.498-.037-.65-.493-1.103c-.247-.245-.432-.613-.432-.98v-.98c0-.307-.246-.552-.493-.614c-.74-.184-2.28-.49-4.499-.49s-3.76.306-4.5.49a.6.6 0 0 0-.492.613v.98c0 .368-.123.736-.432.981l-.184.184c-.247.184-.37.552-.37.858c.061.674.123 1.654.123 1.654q-.029 0-.056-.002a.73.73 0 0 1-.684-.61l-.678-3.493c-.123-.98.37-1.961 1.233-2.39l.493-.245c.308-.184.617-.43.925-.674l1.109-1.165c.678-.613 1.664-.796 2.527-.367a3.4 3.4 0 0 0 1.91 0c.925-.307 1.973-.062 2.712.612l.925.92c.246.306.554.49.924.674");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lu2nl3b4z {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m21.355 5.41l.493.245c.863.429 1.356 1.41 1.171 2.451l-.678 3.493c-.06.36-.299.604-.657.612h-.02s.061-1.041.123-1.654c.05-.498-.037-.65-.493-1.103c-.247-.245-.432-.613-.432-.98v-.98c0-.307-.246-.552-.493-.614c-.74-.184-2.28-.49-4.499-.49s-3.76.306-4.5.49a.6.6 0 0 0-.492.613v.98c0 .368-.123.736-.432.981l-.184.184c-.247.184-.37.552-.37.858c.061.674.123 1.654.123 1.654q-.029 0-.056-.002a.73.73 0 0 1-.684-.61l-.678-3.493c-.123-.98.37-1.961 1.233-2.39l.493-.245c.308-.184.617-.43.925-.674l1.109-1.165c.678-.613 1.664-.796 2.527-.367a3.4 3.4 0 0 0 1.91 0c.925-.307 1.973-.062 2.712.612l.925.92c.246.306.554.49.924.674");
}

.lwjbbq_rp {
  stop-color: var(--svg-color--47b7fb, #47B7FB);
}

.lz2s8578j {
  fill: var(--svg-color--d49c84, #D49C84);
  d: path("m15.38 12.525l-.611 1.953a.62.62 0 0 0 .598.803h.903a.62.62 0 0 0 .598-.803l-.61-1.953c-.131-.433-.742-.433-.879 0");
}

.m8dz_mblr {
  d: path("M9.442 8.703c.396.844 1.515 2.461 3.97 2.461h5.115c2.454 0 3.573-1.617 3.97-2.46c-2.254-1.05-5.29-1.423-6.528-1.477c-1.237.054-4.274.426-6.527 1.476");
}

.ma-141o8x {
  d: path("m15.38 12.446l-.611 1.952a.62.62 0 0 0 .598.804h.903a.62.62 0 0 0 .598-.804l-.61-1.953c-.131-.432-.742-.432-.879 0");
}

.muvillb0h {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.562 11.209c.75 0 1.384.517 1.556 1.216a.315.315 0 0 1-.307.392h-2.563a.265.265 0 0 1-.261-.313a1.606 1.606 0 0 1 1.575-1.295");
}

.n4wew7txz {
  stop-color: var(--svg-color--553830, #553830);
}

.ni0htxbur {
  stop-color: var(--svg-color--407ccf, #407CCF);
}

.nlnhxpbkx {
  stop-color: var(--svg-color--4681d4, #4681D4);
  stop-opacity: 0;
}

.noi50fbya {
  cx: 10.363px;
  cy: 12.853px;
  r: 1.143px;
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nx2bsjb_t {
  stop-color: var(--svg-color--4a88df, #4A88DF);
  stop-opacity: 0;
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_6980ch {
  stop-color: var(--svg-color--af798d, #AF798D);
}

.oigr0yrty {
  d: path("M18.83 24.93a.5.5 0 0 1 .5-.5h1.812a.5.5 0 0 1 .5.5v1.726a1.406 1.406 0 1 1-2.813 0z");
}

.ojnx9kp9k {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
  stop-opacity: 0;
}

.oo1rz0b9x {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.818 16.449a3.45 3.45 0 0 1-1.591-.377c-.158-.08-.327.097-.228.24a2.17 2.17 0 0 0 1.82.971c.763 0 1.434-.388 1.818-.971c.1-.149-.07-.32-.227-.24c-.46.24-1.003.377-1.592.377");
}

.p_hknfval {
  stop-color: var(--svg-color--81d0ff, #81D0FF);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmx6s8bth {
  stop-color: var(--svg-color--a56c6a, #A56C6A);
}

.q_tju-qsy {
  cx: 21.294px;
  cy: 12.853px;
  r: 1.918px;
}

.q-4mmubff {
  stop-color: var(--svg-color--87ddff, #87DDFF);
}

.q3vx93ufn {
  stop-color: var(--svg-color--8ae0ff, #8AE0FF);
}

.qjgh28b1y {
  stop-color: var(--svg-color--189cf0, #189CF0);
}

.qk0uucc4g {
  d: path("m15.38 12.525l-.611 1.953a.62.62 0 0 0 .598.803h.903a.62.62 0 0 0 .598-.803l-.61-1.953c-.131-.433-.742-.433-.879 0");
}

.qk56hfspl {
  stop-color: var(--svg-color--4681d4, #4681D4);
}

.qooaqh4_d {
  stop-color: var(--svg-color--a97980, #A97980);
}

.qt_mg48rg {
  stop-color: var(--svg-color--409ed2, #409ED2);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r_91d457c {
  stop-color: var(--svg-color--4389d1, #4389D1);
  stop-opacity: 0;
}

.r9aql0tfq {
  stop-color: var(--svg-color--30acff, #30ACFF);
  stop-opacity: 0;
}

.rvybbdrcw {
  stop-color: var(--svg-color--1b89dc, #1B89DC);
  stop-opacity: 0;
}

.rwuy40buq {
  stop-color: var(--svg-color--b37a98, #B37A98);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sjzaf5e-a {
  stop-color: var(--svg-color--5d8cde, #5D8CDE);
  stop-opacity: 0;
}

.skgxszbhw {
  fill: var(--svg-color--2389d6, #2389D6);
  d: path("m12.646 19.685l.763 3.8a.41.41 0 0 0 .662.242l.452-.364l.601 1.204c.04.078.12.128.208.128h1.021c.089 0 .17-.05.21-.13l.586-1.187l.437.349a.41.41 0 0 0 .661-.242l.764-3.8z");
}

.sw0blobad {
  fill-rule: evenodd;
  d: path("M21.92 8.962c-5.062-1.855-9.999-.764-11.82-.011a.775.775 0 0 1-.592-1.433c2.085-.861 7.432-2.031 12.945-.011a.775.775 0 1 1-.533 1.455");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t0v_yxg9a {
  cx: 21.294px;
  cy: 12.853px;
  r: 1.143px;
}

.t9xlhbbtl {
  stop-color: var(--svg-color--1d1b3e, #1D1B3E);
}

.thtcysb5g {
  d: path("M8.055 29.934H3.862a12.15 12.15 0 0 1 4.193-8.309z");
}

.tp8jvfpml {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.trkjkfbvt {
  fill: var(--svg-color--73c0ff, #73C0FF);
  d: path("M15.879 21.209v.79l1.97 1.57c.26.21.64.07.71-.26l.82-4.08z");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u5b_qpb1y {
  stop-color: var(--svg-color--734d45, #734D45);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.uksv4cbwr {
  d: path("M13.307 11.521a1.025 1.025 0 0 0-.989 1.295H14.3a1 1 0 0 0 .037-.27a1.03 1.03 0 0 0-1.03-1.025");
}

.upydt32_o {
  fill: var(--svg-color--3fb3ff, #3FB3FF);
  d: path("M3.862 29.934h24.276c-.466-6.297-5.723-11.26-12.138-11.26S4.328 23.638 3.862 29.934");
}

.uqbs6jb_n {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.502 12.713l-.943 1.953c-.116.401.164.803.561.803h.847c.398 0 .678-.408.561-.803l-.572-1.953c-.123-.433-.325-.433-.454 0");
}

.v_zil8baw {
  d: path("M14.243 12.426c0-.331-.27-.552-.342-.619l-.331.32l.204.416z");
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.vbnpoccjx {
  fill: var(--svg-color--297ecb, #297ECB);
  d: path("M14.74 3.8v.922a1.187 1.187 0 1 0 2.373 0v-.924a.2.2 0 0 0-.307-.168l-.253.16a.1.1 0 0 1-.134-.025l-.294-.402a.25.25 0 0 0-.404 0l-.292.401a.1.1 0 0 1-.135.026l-.247-.159a.2.2 0 0 0-.308.169");
}

.vg5w9dbzr {
  stop-color: var(--svg-color--30acff, #30ACFF);
}

.vhpcois2a {
  stop-color: var(--svg-color--ffcd47, #FFCD47);
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.wh6fmbcdq {
  cx: 12.997px;
  cy: 11.959px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.448px;
  ry: 0.227px;
}

.wt_jecb6v {
  stop-color: var(--svg-color--5fa3ec, #5FA3EC);
}

.x639olrpy {
  fill: var(--svg-color--000, #000);
  d: path("M13.894 12.547a.585.585 0 0 0-.588-.588a.585.585 0 0 0-.521.858h1.039a.6.6 0 0 0 .07-.27");
}

.xf9qqcbnz {
  stop-color: var(--svg-color--4eb9f4, #4EB9F4);
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xmkjq1brc {
  stop-color: var(--svg-color--b58893, #B58893);
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xsp7-kwpz {
  stop-color: var(--svg-color--3c73d6, #3C73D6);
}

.xsu_qdbmh {
  stop-color: var(--svg-color--4188d4, #4188D4);
  stop-opacity: 0;
}

.xtdwx6-mz {
  d: path("M18.324 11.521a1.025 1.025 0 0 1 .988 1.295h-1.98a1.03 1.03 0 0 1 .993-1.295");
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.yb51f6w_n {
  stop-color: var(--svg-color--bd8378, #BD8378);
  stop-opacity: 0;
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.ylhb00l1u {
  stop-color: var(--svg-color--4389d1, #4389D1);
}

.yvnwtvbdk {
  stop-color: var(--svg-color--3169c8, #3169C8);
}

.yvy6tz2sx {
  d: path("M23.945 29.934h4.193a12.15 12.15 0 0 0-4.193-8.309z");
}

.z_4nico_h {
  stop-color: var(--svg-color--7dc8fc, #7DC8FC);
  stop-opacity: 0;
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z3jt8_bjd {
  d: path("M19.238 12.411a.97.97 0 0 0-.266-.531l-.299.327l.135.263z");
}

.z6a5p4bqu {
  fill: var(--svg-color--247dbd, #247DBD);
  fill-rule: evenodd;
  d: path("M21.582 8.636c-4.687-1.717-9.257-.77-10.943-.072a.717.717 0 1 1-.548-1.326c1.93-.798 6.88-1.82 11.984.05a.717.717 0 1 1-.493 1.348");
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zstiy-bhq {
  d: path("M16.023 21.209v.79l-1.95 1.57a.44.44 0 0 1-.71-.26l-.82-4.08z");
}

.zy2fe0b7g {
  stop-color: var(--svg-color--76c4ff, #76C4FF);
}

</style>
