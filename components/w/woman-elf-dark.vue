<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="e4tar7-ra"/><path fill="url(#iUY80Pe)" class="ei-zmixku"/><path fill="url(#iDbYoEd)" class="ei-zmixku"/><path fill="url(#iCYhEcc)" class="ei-zmixku"/><path fill="url(#i82oxbd)" class="ei-zmixku"/><path fill="url(#ixxOx8b)" class="ei-zmixku"/><path fill="url(#irDlLPc)" class="ei-zmixku"/><path fill="url(#iA95z6d)" class="ei-zmixku"/><path fill="url(#ivHOYle)" class="ei-zmixku"/><path class="auoirjbmm"/><path fill="url(#ineK6Cd)" class="x-171ccrl"/><path fill="url(#ijnexbb)" class="x-171ccrl"/><path fill="url(#iDGT1hJ)" class="x-171ccrl"/><path class="ecbjgibqi"/><path fill="url(#inZ0nhg)" class="vgwnw8h0u"/><path fill="url(#iv1Hcvb)" class="vgwnw8h0u"/><path fill="url(#iXhtQee)" class="vgwnw8h0u"/><path fill="url(#iIhOjRc)" class="i1ujs7one"/><path fill="url(#iSrLw0d)" class="i1ujs7one"/><path fill="url(#ihFs7mi)" class="i1ujs7one"/><path fill="url(#ixDw5Zd)" class="i1ujs7one"/><path fill="url(#idq1mHc)" class="i1ujs7one"/><path fill="url(#iepOgvc)" class="i1ujs7one"/><path fill="url(#igkqS7c)" class="i1ujs7one"/><g filter="url(#iPDMdKd)"><path class="dht7arbom"/></g><g filter="url(#iBAhRmd)"><path fill="url(#iePzlxb)" class="u22r5t-xk"/></g><g filter="url(#iTc9Bsa)"><path fill="url(#is812tF)" class="u_k1hctwr"/></g><path fill="url(#iawuyjd)" class="pgd4nu3yt"/><path fill="url(#iRoTFae)" class="pgd4nu3yt"/><g filter="url(#i2nSEOd)"><path fill="url(#idkhfJc)" class="mu-4-hbzt"/></g><g filter="url(#iLXtIcb)"><path fill="url(#i7QcYLR)" class="bu7es_a0d"/></g><g filter="url(#izIoTIe)"><path fill="url(#i1cp6zw)" class="ksm3t8bap"/></g><path fill="url(#iHLr70L)" class="wctf3ibkb"/><path fill="url(#iMFD93d)" class="wctf3ibkb"/><path fill="url(#iaGAKEb)" class="e_0vl3o1i"/><path fill="url(#i0Jvrkb)" class="e_0vl3o1i"/><g filter="url(#ioAQqve)"><path class="dy4dy579a"/></g><g filter="url(#ivAJAec)"><path fill="url(#ilEmGFd)" class="xlqlhebaa"/><path fill="url(#izzmTpc)" class="xlqlhebaa"/><path fill="url(#ige5GHc)" class="xlqlhebaa"/><path fill="url(#iJSnMNe)" class="xlqlhebaa"/><path fill="url(#ie7foAb)" class="xlqlhebaa"/><path fill="url(#ibVTnRd)" class="xlqlhebaa"/></g><g filter="url(#irRSoFd)"><path class="uxj3kybir"/><path fill="url(#iwRI2Ab)" class="iethn661e"/><path fill="url(#i1yVBtc)" class="iethn661e"/><path fill="url(#iUY0yll)" class="iethn661e"/></g><g filter="url(#iGpDSod)"><path fill="url(#iNx78Vd)" class="w3laegbtn"/><path fill="url(#izVegNd)" class="w3laegbtn"/><path fill="url(#id75Jge)" class="w3laegbtn"/><path fill="url(#ik6Fxdd)" class="w3laegbtn"/><path fill="url(#iEGzNYb)" class="w3laegbtn"/></g><path fill="url(#iO6Ss8d)" class="w3laegbtn"/><path fill="url(#inVoJmX)" class="aioxy45xu"/><path fill="url(#itzjL9Z)" class="aioxy45xu"/><path fill="url(#i5pwqPb)" class="aioxy45xu"/><g filter="url(#iMlbT0K)"><path class="qf6wo7boe"/></g><g filter="url(#ix4gNCd)"><path fill="url(#ioUhQcb)" class="ghfy1iray"/><path fill="url(#iU2CpKe)" class="ghfy1iray"/><path fill="url(#ibH2Zjd)" class="ghfy1iray"/></g><path fill="url(#iayided)" class="g0xvfdbyw"/><path fill="url(#i4eHRSd)" class="g0xvfdbyw"/><path fill="url(#i1nkGac)" class="g0xvfdbyw"/><path fill="url(#iGdWf9I)" class="g0xvfdbyw"/><path fill="url(#ihhsmPe)" class="g0xvfdbyw"/><path fill="url(#iswZV0c)" class="g0xvfdbyw"/><path fill="url(#ilTtifc)" class="qneer9b8q"/><g filter="url(#iTion6b)"><path class="yc4hclv9f"/></g><g filter="url(#io0t4Be)"><path class="x3r4-kbqt"/></g><g filter="url(#ijsCsXd)"><path class="neasw5byt"/></g><g filter="url(#iTlqG5d)"><path class="b_9lgmbzy"/></g><g filter="url(#iJlHhvI)"><path class="qdd3499bj"/></g><path class="h9k5ntjep"/><path fill="url(#iw3j3rc)" class="i9lr1p25m"/><path fill="url(#iqPgoOd)" class="i9lr1p25m"/><path fill="url(#iWgOQld)" class="i9lr1p25m"/><g filter="url(#iPP3ixe)"><path stroke="url(#iXkCHGc)" class="n4-d2tb8s"/></g><path class="kfrstgbms"/><path class="sytb8pb3p"/><path class="hoq7d6bfq"/><path fill="url(#ibqtDyq)" class="m00e_ufro"/><path class="nnydhdb8x"/><g filter="url(#iKHAfvc)"><path class="vlizw1ypl"/><path fill="url(#iVaJgyd)" class="hby5gbc-p"/></g><g filter="url(#itZScgb)"><path fill="url(#irlfuVD)" class="bweh5b8qw"/></g><path class="r0rrpvpum"/><path fill="url(#imUdeEc)" class="q2nms2n3q"/><path class="zhtqcybuc"/><g filter="url(#iqmNWRF)"><path fill="url(#i0raRjd)" class="uwyi2hzqu"/></g><g filter="url(#i46jwxd)"><ellipse transform="rotate(-27.914 13.561 9.976)" class="lu3j7bbpk"/><ellipse fill="url(#igUPrxc)" transform="rotate(-27.914 13.561 9.976)" class="npvlux_im"/></g><defs><radialGradient id="iDbYoEd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -14.3438 23.142 20.686)" gradientUnits="userSpaceOnUse"><stop class="szuqc-bjo"/><stop offset="1" class="in53vxbzi"/></radialGradient><radialGradient id="iCYhEcc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.347 20.477 5.184)scale(3.59496 4.80694)" gradientUnits="userSpaceOnUse"><stop class="iy200zbbi"/><stop offset="1" class="ox6ngqb6d"/></radialGradient><radialGradient id="i82oxbd" cx="0" cy="0" r="1" gradientTransform="rotate(77.471 -3.564 20.737)scale(2.88111 5.07754)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="utz8l-hjj"/><stop offset="1" class="ssj6asr2b"/></radialGradient><radialGradient id="ixxOx8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.57813 .51562 -7.1646 -8.03319 14.554 27.46)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="im7yg7aog"/><stop offset="1" class="nz4t17rpu"/></radialGradient><radialGradient id="irDlLPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 .3125 -2.8125 16.87503 8.952 23.999)" gradientUnits="userSpaceOnUse"><stop class="fupnc-bzv"/><stop offset="1" class="fux90lb8s"/></radialGradient><radialGradient id="iA95z6d" cx="0" cy="0" r="1" gradientTransform="matrix(.313 0 0 13.5898 8.827 27.552)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="u7qedx64x"/><stop offset="1" class="l-im3ccrf"/></radialGradient><radialGradient id="ivHOYle" cx="0" cy="0" r="1" gradientTransform="matrix(-.50581 0 0 -8.83067 23.25 26.076)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="frtpxb2_e"/><stop offset="1" class="r_hbeqgkw"/></radialGradient><radialGradient id="ineK6Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-.59707 0 0 -12.1778 9.033 29.939)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="bu_chtytz"/><stop offset="1" class="n1msxeybk"/></radialGradient><radialGradient id="ijnexbb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69302 6.8777 -1.92029 -.4727 6.992 23.061)" gradientUnits="userSpaceOnUse"><stop class="tf7ikua9d"/><stop offset="1" class="xodttob3f"/></radialGradient><radialGradient id="inZ0nhg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 -10.40629 1.38016 -.21552 25.58 28.374)" gradientUnits="userSpaceOnUse"><stop offset=".455" class="f_vyractb"/><stop offset="1" class="av_zubbsw"/></radialGradient><radialGradient id="iXhtQee" cx="0" cy="0" r="1" gradientTransform="matrix(.49206 0 0 10.875 23.088 26.467)" gradientUnits="userSpaceOnUse"><stop class="mzy3c3d_u"/><stop offset="1" class="lpdsa84op"/></radialGradient><radialGradient id="ihFs7mi" cx="0" cy="0" r="1" gradientTransform="matrix(1.62231 -1.625 9.061 9.04602 15.736 29.78)" gradientUnits="userSpaceOnUse"><stop class="rbi44vm-m"/><stop offset="1" class="k-1w4_syq"/></radialGradient><radialGradient id="ixDw5Zd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.42 17.248 11.374)scale(18.1601 26.3733)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="pc9y3hbhd"/><stop offset="1" class="vhxxajp3a"/></radialGradient><radialGradient id="idq1mHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.53125 -8.40625 0 15.986 18.155)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="lm4m34bzz"/><stop offset="1" class="y78euyjzo"/></radialGradient><radialGradient id="iePzlxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.63279 -.8125 0 16.517 22.751)" gradientUnits="userSpaceOnUse"><stop class="kna63ccqu"/><stop offset="1" class="yg8va_99z"/></radialGradient><radialGradient id="is812tF" cx="0" cy="0" r="1" gradientTransform="matrix(-2.34377 1.74998 -2.39636 -3.20947 11.765 12.967)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="jiyzjrsgy"/><stop offset="1" class="u0kmbbbcj"/></radialGradient><radialGradient id="iawuyjd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25 .8711 -.92998 -2.40211 23.858 12.686)" gradientUnits="userSpaceOnUse"><stop class="xgbg8db5s"/><stop offset=".858" class="a5man1mil"/></radialGradient><radialGradient id="iRoTFae" cx="0" cy="0" r="1" gradientTransform="matrix(1.82812 .51173 -1.43377 5.12206 20.562 13.046)" gradientUnits="userSpaceOnUse"><stop class="kgl1dzb7o"/><stop offset="1" class="plxqyrsje"/></radialGradient><radialGradient id="i7QcYLR" cx="0" cy="0" r="1" gradientTransform="matrix(1.4697 -1.59165 3.40232 3.14166 8.664 10.211)" gradientUnits="userSpaceOnUse"><stop class="r6oltybkl"/><stop offset="1" class="jrlin1f0e"/></radialGradient><radialGradient id="iHLr70L" cx="0" cy="0" r="1" gradientTransform="matrix(3.42178 -4.2491 3.0025 2.4179 20.599 11.99)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="q0r0z1peg"/><stop offset="1" class="n_iuxqqkg"/></radialGradient><radialGradient id="iMFD93d" cx="0" cy="0" r="1" gradientTransform="rotate(-140.86 13.36 1.275)scale(1.81729 4.05801)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="nk03gacgg"/><stop offset=".842" class="kme6w3b3u"/></radialGradient><radialGradient id="iaGAKEb" cx="0" cy="0" r="1" gradientTransform="rotate(-143.844 7.216 3.795)scale(3.06704 1.99268)" gradientUnits="userSpaceOnUse"><stop class="au5pkhb8o"/><stop offset="1" class="rki8815qy"/></radialGradient><radialGradient id="i0Jvrkb" cx="0" cy="0" r="1" gradientTransform="matrix(1.65395 -1.20896 4.23858 5.79872 8.843 10.92)" gradientUnits="userSpaceOnUse"><stop offset=".659" class="i3p2j2s6k"/><stop offset=".837" class="uelxx39pu"/></radialGradient><radialGradient id="ilEmGFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.50781 13.8508 0 16 21.34)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="ob9xa4oph"/><stop offset="1" class="u9vkkub5w"/></radialGradient><radialGradient id="izzmTpc" cx="0" cy="0" r="1" gradientTransform="rotate(152.259 7.559 9.702)scale(9.53325 15.1141)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="ngc6h6bst"/><stop offset="1" class="o5llqtbdv"/></radialGradient><radialGradient id="ige5GHc" cx="0" cy="0" r="1" gradientTransform="matrix(6.06254 6.31246 -7.41731 7.12364 14.453 14.217)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="s1jm76o_g"/><stop offset="1" class="a0ve6ibhs"/></radialGradient><radialGradient id="iJSnMNe" cx="0" cy="0" r="1" gradientTransform="rotate(-158.513 8.323 6.627)scale(4.24838 2.76793)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="u9m-38uic"/><stop offset="1" class="dgp6vzbgz"/></radialGradient><radialGradient id="ie7foAb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.20237 6.09373 -1.19654 -.82516 20.202 14.092)" gradientUnits="userSpaceOnUse"><stop offset=".447" class="hgv4-zm2k"/><stop offset="1" class="wpf0olbav"/></radialGradient><radialGradient id="ibVTnRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.03906 -1.52344 .33915 .23132 18.398 16.702)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="wj7x2ubbg"/><stop offset="1" class="jq6-sgbpj"/></radialGradient><radialGradient id="iwRI2Ab" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36486 4.087 -1.86291 -1.07794 18.327 16.14)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="b2tykvbop"/><stop offset="1" class="yipkkxtvy"/></radialGradient><radialGradient id="i1yVBtc" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 2.60938 -4.67763 .95233 14.609 15.577)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="sifdoacrc"/><stop offset="1" class="zy0uiq7qe"/></radialGradient><radialGradient id="iUY0yll" cx="0" cy="0" r="1" gradientTransform="matrix(-3.86275 1.28759 -4.0032 -12.00957 17.243 16.343)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="h91q9_w7m"/><stop offset="1" class="ydiwmubvk"/></radialGradient><radialGradient id="iNx78Vd" cx="0" cy="0" r="1" gradientTransform="rotate(167.196 9.611 6.204)scale(7.05032 8.72135)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="lenvnubyg"/></radialGradient><radialGradient id="izVegNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.78126 -1 .8108 -.63344 13.937 9.452)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="w0kdm4lew"/><stop offset="1" class="f-grjobga"/></radialGradient><radialGradient id="id75Jge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45312 1.84375 0 18.421 9.436)" gradientUnits="userSpaceOnUse"><stop class="oqw_5nl4e"/><stop offset="1" class="ms3wpfxwq"/></radialGradient><radialGradient id="ik6Fxdd" cx="0" cy="0" r="1" gradientTransform="rotate(26.954 -2.675 30.526)scale(6.34556 4.25079)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="y_x9jlxov"/><stop offset="1" class="sbo1y7_lu"/></radialGradient><radialGradient id="iEGzNYb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.98439 2.09371 -1.13046 -2.1513 19.28 6.905)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="s69j295el"/><stop offset="1" class="y5y2xtbig"/></radialGradient><radialGradient id="iO6Ss8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0772 7.57444 -8.03074 -1.14209 17.077 9.092)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="nsqpfdcbc"/><stop offset="1" class="l-j-36qmj"/></radialGradient><radialGradient id="inVoJmX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 4.65625 -10.56138 -2.33908 19 3.249)" gradientUnits="userSpaceOnUse"><stop class="hnxb32wpu"/><stop offset="1" class="stp2v1b5t"/></radialGradient><radialGradient id="itzjL9Z" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9375 .65626 -1.24788 -3.68415 23.031 6.89)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="necrmbvul"/><stop offset="1" class="nlldxqbzj"/></radialGradient><radialGradient id="i5pwqPb" cx="0" cy="0" r="1" gradientTransform="matrix(.75769 -3.32812 2.92645 .66624 9.29 8.327)" gradientUnits="userSpaceOnUse"><stop class="rl87-gbvf"/><stop offset="1" class="bh_6wtbtg"/></radialGradient><radialGradient id="ioUhQcb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03113 3.06466 -5.29387 -1.78117 18.983 3.965)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="kl4tnqb9l"/><stop offset="1" class="zm2sgebiw"/></radialGradient><radialGradient id="iU2CpKe" cx="0" cy="0" r="1" gradientTransform="rotate(121.752 8.27 7.041)scale(4.86941 8.82412)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="n6u-hqbre"/><stop offset="1" class="xe-pwob5s"/></radialGradient><radialGradient id="ibH2Zjd" cx="0" cy="0" r="1" gradientTransform="rotate(169.223 10.87 4.312)scale(1.25343 4.89934)" gradientUnits="userSpaceOnUse"><stop offset=".076" class="necrmbvul"/><stop offset="1" class="nlldxqbzj"/></radialGradient><radialGradient id="iGdWf9I" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 0 0 -.60938 21.768 5.499)" gradientUnits="userSpaceOnUse"><stop class="ekarirbxr"/><stop offset="1" class="n81djoa0z"/></radialGradient><radialGradient id="ihhsmPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .54688 -8.71875 0 11.174 4.967)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="b4qr-wvfv"/><stop offset="1" class="yyik5z8lx"/></radialGradient><radialGradient id="iswZV0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92969 -.45312 0 15.229 5.186)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="h6i96qjvc"/><stop offset="1" class="d31bklhyx"/></radialGradient><radialGradient id="ilTtifc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.90625 2.05457 0 15.979 6.764)" gradientUnits="userSpaceOnUse"><stop class="rkzp1hbvm"/><stop offset="1" class="j5zu11bke"/></radialGradient><radialGradient id="iqPgoOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.34403 .63804 0 16.398 12.133)" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="zmkruk91v"/></radialGradient><radialGradient id="iWgOQld" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6545 2.30377 0 16 12.692)" gradientUnits="userSpaceOnUse"><stop class="dednbhwic"/><stop offset="1" class="oouvfuj_o"/></radialGradient><radialGradient id="iXkCHGc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.417 19.61 -5.633)scale(.34815 1.6378)" gradientUnits="userSpaceOnUse"><stop offset=".062" class="r_rjacble"/><stop offset="1" class="e2sd3cbvi"/></radialGradient><radialGradient id="ibqtDyq" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 6.735 9.596)scale(1.10543 1.21398)" gradientUnits="userSpaceOnUse"><stop class="qxnakxbrg"/><stop offset="1" class="egerxebfb"/></radialGradient><radialGradient id="iVaJgyd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.471 .678)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imUdeEc" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 4.553 8.527)scale(1.10548 1.21404)" gradientUnits="userSpaceOnUse"><stop class="qxnakxbrg"/><stop offset="1" class="egerxebfb"/></radialGradient><radialGradient id="igUPrxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.546 10.292)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iPDMdKd" width="2.581" height="5.008" x="14.415" y="20.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1364" stdDeviation=".25"/></filter><filter id="iBAhRmd" width="1.681" height="4.108" x="15.197" y="21.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1364"/></filter><filter id="iTc9Bsa" width="6.499" height="6.992" x="8.438" y="10.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.247059 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1364"/></filter><filter id="i2nSEOd" width="4.108" height="5.161" x="20.345" y="7.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.176471 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1364"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.101961 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1364" result="effect2_innerShadow_4002_1364"/></filter><filter id="iLXtIcb" width="3.958" height="5.111" x="7.666" y="7.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.203922 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1364"/></filter><filter id="izIoTIe" width="3.716" height="3.975" x="20.59" y="8.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1364" stdDeviation=".075"/></filter><filter id="ioAQqve" width="3.972" height="2.892" x="20.405" y="7.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1364" stdDeviation=".075"/></filter><filter id="ivAJAec" width="13.191" height="7.279" x="9.404" y="14.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.243137 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1364"/></filter><filter id="irRSoFd" width="6.278" height="4.65" x="12.723" y="15.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0784314 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1364"/></filter><filter id="iGpDSod" width="10.95" height="12.138" x="10.825" y="4.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".8"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419815 0 0 0 0 0.314298 0 0 0 0 0.290849 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1364"/></filter><filter id="iMlbT0K" width="4.248" height="5.575" x="9.651" y="3.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.313726 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1364"/><feGaussianBlur result="effect2_foregroundBlur_4002_1364" stdDeviation=".05"/></filter><filter id="ix4gNCd" width="9.815" height="5.825" x="12.74" y="2.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.341176 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1364"/><feGaussianBlur result="effect2_foregroundBlur_4002_1364" stdDeviation=".1"/></filter><filter id="iTion6b" width="2.288" height="1.093" x="17.531" y="7.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.027451 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1364"/></filter><filter id="io0t4Be" width="2.188" height=".793" x="17.581" y="7.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1364" stdDeviation=".075"/></filter><filter id="ijsCsXd" width="2.288" height="1.093" x="12.21" y="7.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.027451 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1364"/></filter><filter id="iTlqG5d" width="2.188" height=".793" x="12.261" y="7.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1364" stdDeviation=".075"/></filter><filter id="iJlHhvI" width="2.687" height="3.9" x="14.354" y="9.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1364" stdDeviation=".25"/></filter><filter id="iPP3ixe" width="3.618" height="1.473" x="14.191" y="13.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1364" stdDeviation=".05"/></filter><filter id="iKHAfvc" width=".787" height=".696" x="17.463" y="9.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1364" stdDeviation=".05"/></filter><filter id="itZScgb" width=".891" height=".913" x="18.303" y="9.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1364" stdDeviation=".1"/></filter><filter id="iqmNWRF" width=".986" height="1.04" x="13.86" y="9.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1364" stdDeviation=".1"/></filter><filter id="i46jwxd" width=".913" height=".705" x="13.105" y="9.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1364" stdDeviation=".05"/></filter><linearGradient id="iUY80Pe" x1="15.049" x2="15.049" y1="29.939" y2="20.53" gradientUnits="userSpaceOnUse"><stop class="ifj7fvbjw"/><stop offset="1" class="wz09qdb4r"/></linearGradient><linearGradient id="iDGT1hJ" x1="8.912" x2="8.912" y1="29.939" y2="26.655" gradientUnits="userSpaceOnUse"><stop class="trl24wm4t"/><stop offset="1" class="xg491tydm"/></linearGradient><linearGradient id="iv1Hcvb" x1="24.142" x2="27.327" y1="29.311" y2="21.436" gradientUnits="userSpaceOnUse"><stop offset=".116" class="bdhnfsb4c"/><stop offset=".679" class="ya66usbax"/></linearGradient><linearGradient id="iIhOjRc" x1="12.518" x2="22.705" y1="21.28" y2="30.936" gradientUnits="userSpaceOnUse"><stop class="e8j2tsbtw"/><stop offset="1" class="e6nk6fapd"/></linearGradient><linearGradient id="iSrLw0d" x1="27.198" x2="19.296" y1="30.793" y2="28.026" gradientUnits="userSpaceOnUse"><stop class="xa_7m3b4l"/><stop offset="1" class="c4ry2c6jv"/></linearGradient><linearGradient id="iepOgvc" x1="15.015" x2="15.229" y1="28.674" y2="28.469" gradientUnits="userSpaceOnUse"><stop class="xcq_ambdy"/><stop offset="1" class="zh35wab0s"/></linearGradient><linearGradient id="igkqS7c" x1="19.002" x2="18.65" y1="21.983" y2="22.342" gradientUnits="userSpaceOnUse"><stop class="i-kbbcb4w"/><stop offset="1" class="k1jzsjbfs"/></linearGradient><linearGradient id="idkhfJc" x1="22.015" x2="23.326" y1="9.342" y2="11.358" gradientUnits="userSpaceOnUse"><stop class="oy5ype34t"/><stop offset="1" class="ss2worbpp"/></linearGradient><linearGradient id="i1cp6zw" x1="20.976" x2="23.354" y1="11.952" y2="8.098" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cyvijd74w"/><stop offset="1" class="r7v-3tf1l"/></linearGradient><linearGradient id="iayided" x1="15.58" x2="17.299" y1="5.672" y2="5.672" gradientUnits="userSpaceOnUse"><stop class="z5duhrbsp"/><stop offset="1" class="qjga9kbjc"/></linearGradient><linearGradient id="i4eHRSd" x1="15.644" x2="15.644" y1="6.329" y2="5.672" gradientUnits="userSpaceOnUse"><stop class="i817agb_c"/><stop offset="1" class="tp-3hccxn"/></linearGradient><linearGradient id="i1nkGac" x1="15.969" x2="15.969" y1="4.756" y2="5.342" gradientUnits="userSpaceOnUse"><stop class="p59cvi4fc"/><stop offset="1" class="nr_-dacny"/></linearGradient><linearGradient id="iw3j3rc" x1="16.684" x2="15.738" y1="11.187" y2="11.242" gradientUnits="userSpaceOnUse"><stop class="mbakag5nz"/><stop offset="1" class="ubk11kbpm"/></linearGradient><linearGradient id="irlfuVD" x1="18.975" x2="18.661" y1="10.126" y2="10.319" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0raRjd" x1="14.576" x2="14.263" y1="10.126" y2="10.319" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-elf-dark" /></template>
<style>
.a0ve6ibhs {
  stop-color: var(--svg-color--9f6c64, #9F6C64);
}

.a5man1mil {
  stop-color: var(--svg-color--1e1520, #1E1520);
}

.aioxy45xu {
  d: path("M9.29 8.083a6.4 6.4 0 0 1 1.586 1.037v-.903c0-.412.313-.59.916-.934l.005-.003q.19-.107.419-.242c.653-.39.951-1.315 1.004-1.727c.968 1.59 2.113 2.11 3.296 2.11h3.266c.975 0 1.313.449 1.313.78l.013.907a6.4 6.4 0 0 1 1.603-1.038c-.208-.523-.256-1.047-.296-1.478l-.008-.09c-.051-.544-.25-1.343-1.145-2.078c-.632-.484-1.16-.687-1.91-.812c-.471-.079-.778-.361-1.014-.579l-.072-.066c-.286-.302-1.23-.906-2.187-.906c-1.328 0-1.934.469-2.387.906a9 9 0 0 1-.487.44c-.18.15-.404.226-.636.262c-1.018.158-1.633.527-2.209 1.127c-.699.727-.812 1.718-.875 2.5a2.2 2.2 0 0 1-.196.787");
}

.au5pkhb8o {
  stop-color: var(--svg-color--322425, #322425);
}

.auoirjbmm {
  fill: var(--svg-color--755bba, #755BBA);
  d: path("M8.912 18.302a10.9 10.9 0 0 0-3.84 8.319v3.318h3.84z");
}

.av_zubbsw {
  stop-color: var(--svg-color--9079d5, #9079D5);
  stop-opacity: 0;
}

.b_9lgmbzy {
  stroke: var(--svg-color--2f2f2f, #2F2F2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.486 8.526a2.35 2.35 0 0 1 1.737-.283");
}

.b2tykvbop {
  stop-color: var(--svg-color--4d3b3a, #4D3B3A);
}

.b4qr-wvfv {
  stop-color: var(--svg-color--949393, #949393);
}

.bdhnfsb4c {
  stop-color: var(--svg-color--7566b5, #7566B5);
}

.bh_6wtbtg {
  stop-color: var(--svg-color--54504f, #54504F);
  stop-opacity: 0;
}

.bu_chtytz {
  stop-color: var(--svg-color--5742a1, #5742A1);
}

.bu7es_a0d {
  d: path("M8.487 7.779c1.524.44 2.582 1.437 2.928 1.89l.209 2.95c-.399.018-.94.243-1.934-.467c-1.165-1.041-1.72-2.576-1.999-3.545a.67.67 0 0 1 .135-.615a.64.64 0 0 1 .66-.213");
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

.cyvijd74w {
  stop-color: var(--svg-color--675654, #675654);
}

.d31bklhyx {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
  stop-opacity: 0;
}

.dednbhwic {
  stop-color: var(--svg-color--391c29, #391C29);
}

.dgp6vzbgz {
  stop-color: var(--svg-color--613528, #613528);
  stop-opacity: 0;
}

.dht7arbom {
  fill: var(--svg-color--673c37, #673C37);
  d: path("M15.706 21.132c.264.22.79.923.79 1.906c0 1.053-.358 1.646-.701 2.06a.115.115 0 0 1-.178 0c-.343-.414-.702-1.007-.702-2.06c0-.983.527-1.685.79-1.907");
}

.dy4dy579a {
  fill: var(--svg-color--665654, #665654);
  d: path("M20.977 9.342c.05.084.176.233.289.164c.14-.086.976-1.007 2.437-1.5c.323-.089.468.113.512.261q.012.03.012.052l-.012-.052c-.028-.063-.112-.139-.309-.143c-.32-.008-1.937.64-3.351 2.453z");
}

.e_0vl3o1i {
  d: path("M11.401 11.165c-.904-1.684-2.446-2.402-3.074-2.56c.598 1.662 1.19 2.452 1.6 2.81c.44.384 1.057.369 1.293.355z");
}

.e2sd3cbvi {
  stop-color: var(--svg-color--584b4b, #584B4B);
  stop-opacity: 0;
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

.ecbjgibqi {
  fill: var(--svg-color--9172d5, #9172D5);
  d: path("M23.088 18.302a10.9 10.9 0 0 1 3.84 8.319v3.318h-3.84z");
}

.egerxebfb {
  stop-color: var(--svg-color--694c3f, #694C3F);
}

.ei-zmixku {
  d: path("M5.071 26.62c0-6.035 4.893-10.928 10.929-10.928s10.929 4.893 10.929 10.929v3.318H5.07z");
}

.ekarirbxr {
  stop-color: var(--svg-color--ede5f4, #EDE5F4);
}

.f_vyractb {
  stop-color: var(--svg-color--9079d5, #9079D5);
}

.f-grjobga {
  stop-color: var(--svg-color--361f26, #361F26);
  stop-opacity: 0;
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

.g0xvfdbyw {
  d: path("M8.85 5.672a.53.53 0 0 1 .529-.529h13.18a.53.53 0 0 1 0 1.059H9.379a.53.53 0 0 1-.53-.53");
}

.ghfy1iray {
  d: path("m21.093 7.466l1.215.39c.137-.747.062-2.563-1.383-3.227c-1.729-.73-2.453-1.127-3.292-1.586l-.372-.203c-1.024-.554-2.588-.628-3.438.297c-.437.477-.617.617-.883.617c.163 1.19.458 1.866 1.674 2.696a3.3 3.3 0 0 0 1.917.578h3.266c.656 0 1.126.204 1.296.438");
}

.h6i96qjvc {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
}

.h91q9_w7m {
  stop-color: var(--svg-color--321e22, #321E22);
  stop-opacity: 0;
}

.h9k5ntjep {
  fill: var(--svg-color--48302e, #48302E);
  d: path("m15.618 10.098l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.114-.408-.646-.408-.765 0");
}

.hby5gbc-p {
  d: path("M18.133 9.784c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.135.39-.05");
}

.hgv4-zm2k {
  stop-color: var(--svg-color--783c25, #783C25);
}

.hnxb32wpu {
  stop-color: var(--svg-color--555052, #555052);
}

.hoq7d6bfq {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.406 9.323c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.i-kbbcb4w {
  stop-color: var(--svg-color--906550, #906550);
}

.i1ujs7one {
  d: path("m16.274 29.939l-9.221-9.595a10.95 10.95 0 0 1 5.854-4.208L26.69 29.94z");
}

.i3p2j2s6k {
  stop-color: var(--svg-color--453331, #453331);
  stop-opacity: 0;
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

.j5zu11bke {
  stop-color: var(--svg-color--c2ffff, #C2FFFF);
}

.jiyzjrsgy {
  stop-color: var(--svg-color--18111c, #18111C);
}

.jq6-sgbpj {
  stop-color: var(--svg-color--804f24, #804F24);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k-1w4_syq {
  stop-color: var(--svg-color--915959, #915959);
  stop-opacity: 0;
}

.k1jzsjbfs {
  stop-color: var(--svg-color--7f4b4c, #7F4B4C);
  stop-opacity: 0;
}

.kfrstgbms {
  fill: var(--svg-color--2a0018, #2A0018);
  d: path("M16 13.709c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.129-.06-.278-.198-.209a3 3 0 0 1-1.385.33");
}

.kgl1dzb7o {
  stop-color: var(--svg-color--1d161e, #1D161E);
}

.kl4tnqb9l {
  stop-color: var(--svg-color--3a3235, #3A3235);
}

.kme6w3b3u {
  stop-color: var(--svg-color--422727, #422727);
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

.l-j-36qmj {
  stop-color: var(--svg-color--2f141c, #2F141C);
}

.lenvnubyg {
  stop-color: var(--svg-color--3d2728, #3D2728);
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

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m00e_ufro {
  d: path("M18.199 9.595a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.mbakag5nz {
  stop-color: var(--svg-color--64514e, #64514E);
}

.ms3wpfxwq {
  stop-color: var(--svg-color--4c3132, #4C3132);
  stop-opacity: 0;
}

.mu-4-hbzt {
  d: path("M23.482 7.779c-1.524.44-2.582 1.437-2.928 1.89l-.209 2.95c.399.018.94.243 1.934-.467c1.165-1.041 1.72-2.576 1.999-3.545a.67.67 0 0 0-.135-.615a.64.64 0 0 0-.66-.213");
}

.mzy3c3d_u {
  stop-color: var(--svg-color--664dad, #664DAD);
}

.n_iuxqqkg {
  stop-color: var(--svg-color--4c3635, #4C3635);
}

.n1msxeybk {
  stop-color: var(--svg-color--5b4a9b, #5B4A9B);
  stop-opacity: 0;
}

.n4-d2tb8s {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16 13.709c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.129-.06-.278-.198-.209a3 3 0 0 1-1.385.33Z");
}

.n6u-hqbre {
  stop-color: var(--svg-color--1f0d22, #1F0D22);
  stop-opacity: 0;
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

.nk03gacgg {
  stop-color: var(--svg-color--422727, #422727);
  stop-opacity: 0;
}

.nlldxqbzj {
  stop-color: var(--svg-color--555253, #555253);
  stop-opacity: 0;
}

.nnydhdb8x {
  fill: var(--svg-color--000, #000);
  d: path("M17.688 10.488a.51.51 0 0 1 .51-.512a.51.51 0 0 1 .455.747h-.904a.46.46 0 0 1-.061-.235");
}

.npvlux_im {
  cx: 13.561px;
  cy: 9.976px;
  rx: 0.39px;
  ry: 0.197px;
}

.nr_-dacny {
  stop-color: var(--svg-color--a29b98, #A29B98);
  stop-opacity: 0;
}

.nsqpfdcbc {
  stop-color: var(--svg-color--3d1b37, #3D1B37);
  stop-opacity: 0;
}

.nz4t17rpu {
  stop-color: var(--svg-color--5e45a4, #5E45A4);
  stop-opacity: 0;
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o5llqtbdv {
  stop-color: var(--svg-color--8d625b, #8D625B);
}

.ob9xa4oph {
  stop-color: var(--svg-color--975d5c, #975D5C);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oouvfuj_o {
  stop-color: var(--svg-color--391c29, #391C29);
  stop-opacity: 0;
}

.oqw_5nl4e {
  stop-color: var(--svg-color--432729, #432729);
}

.ox6ngqb6d {
  stop-color: var(--svg-color--846fc5, #846FC5);
  stop-opacity: 0;
}

.oy5ype34t {
  stop-color: var(--svg-color--4d3533, #4D3533);
}

.p59cvi4fc {
  stop-color: var(--svg-color--a29b98, #A29B98);
}

.pc9y3hbhd {
  stop-color: var(--svg-color--6e4641, #6E4641);
  stop-opacity: 0;
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

.q0r0z1peg {
  stop-color: var(--svg-color--4d3735, #4D3735);
}

.q2nms2n3q {
  d: path("M13.83 9.595a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.qdd3499bj {
  fill: var(--svg-color--341925, #341925);
  d: path("m15.447 10.293l-.57 1.839c-.098.378.136.756.467.756h.707c.331 0 .565-.384.468-.756l-.478-1.839c-.102-.407-.487-.407-.594 0");
}

.qf6wo7boe {
  fill: var(--svg-color--22191c, #22191C);
  d: path("m13.698 5.67l-.011-.028c-.186-.447-.464-1.118-.553-1.878c-.669.078-2.173.547-2.837 1.797c-.482.909-.573 1.988-.54 2.752c.489.258.81.466 1.119.726v-.902c0-.412.333-.59.973-.934l.005-.003q.202-.107.445-.243c.693-.389 1.096-1.234 1.151-1.646q.123.19.248.359");
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

.r_rjacble {
  stop-color: var(--svg-color--584b4b, #584B4B);
}

.r0rrpvpum {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.624 9.323c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.r6oltybkl {
  stop-color: var(--svg-color--332223, #332223);
}

.r7v-3tf1l {
  stop-color: var(--svg-color--675654, #675654);
  stop-opacity: 0;
}

.rbi44vm-m {
  stop-color: var(--svg-color--a85d71, #A85D71);
}

.rki8815qy {
  stop-color: var(--svg-color--342425, #342425);
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

.s69j295el {
  stop-color: var(--svg-color--4d3d3d, #4D3D3D);
}

.sbo1y7_lu {
  stop-color: var(--svg-color--271619, #271619);
  stop-opacity: 0;
}

.sifdoacrc {
  stop-color: var(--svg-color--29151b, #29151B);
}

.ss2worbpp {
  stop-color: var(--svg-color--4d3534, #4D3534);
}

.ssj6asr2b {
  stop-color: var(--svg-color--6d499b, #6D499B);
  stop-opacity: 0;
}

.stp2v1b5t {
  stop-color: var(--svg-color--190b17, #190B17);
}

.sytb8pb3p {
  fill: var(--svg-color--352e31, #352E31);
  d: path("M18.345 9.28c-.397.05-.74.302-.863.422l1.777.848l.527-.317c.194-.117.256-.378.088-.531c-.48-.44-1.116-.474-1.53-.422m-4.689 0c.398.05.741.302.863.422l-1.777.848l-.527-.317c-.194-.117-.255-.378-.088-.531c.48-.44 1.116-.474 1.53-.422");
}

.szuqc-bjo {
  stop-color: var(--svg-color--987cdc, #987CDC);
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

.u_k1hctwr {
  d: path("M8.609 11.64c-.213-.676-.182-1.334-.14-1.579h6.218v6.992l-4.312-.039c-2.39-1.406-1.97-3.648-1.766-4.148c.158-.389.148-.774 0-1.227");
}

.u0kmbbbcj {
  stop-color: var(--svg-color--1b181a, #1B181A);
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

.u9vkkub5w {
  stop-color: var(--svg-color--7c442f, #7C442F);
}

.ubk11kbpm {
  stop-color: var(--svg-color--56403e, #56403E);
  stop-opacity: 0;
}

.uelxx39pu {
  stop-color: var(--svg-color--453331, #453331);
}

.utz8l-hjj {
  stop-color: var(--svg-color--6d499b, #6D499B);
}

.uwyi2hzqu {
  d: path("M14.646 10.383c0-.289-.235-.481-.298-.54l-.288.28l.177.361z");
}

.uxj3kybir {
  fill: var(--svg-color--4a3335, #4A3335);
  d: path("m12.924 15.577l.232 1c.03.107.117.372.232.578c.136.243 1.342 2.067 2.336 2.997a.27.27 0 0 0 .37.003c.991-.897 2.221-2.758 2.357-3c.115-.206.263-.471.293-.578l.258-1z");
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

.w0kdm4lew {
  stop-color: var(--svg-color--361f26, #361F26);
}

.w3laegbtn {
  d: path("M10.827 7.622a3 3 0 0 1 2.998-3.093h4.35a3 3 0 0 1 2.999 3.085l-.118 4.144a5.052 5.052 0 0 1-10.1.014z");
}

.wctf3ibkb {
  d: path("M20.599 11.165c.904-1.684 2.446-2.402 3.074-2.56c-.598 1.662-1.19 2.452-1.6 2.81c-.44.384-1.057.369-1.293.355z");
}

.wj7x2ubbg {
  stop-color: var(--svg-color--804f24, #804F24);
}

.wpf0olbav {
  stop-color: var(--svg-color--783c25, #783C25);
  stop-opacity: 0;
}

.wz09qdb4r {
  stop-color: var(--svg-color--6651aa, #6651AA);
  stop-opacity: 0;
}

.x-171ccrl {
  d: path("M8.912 18.302a10.9 10.9 0 0 0-3.84 8.319v3.318h3.84z");
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

.xe-pwob5s {
  stop-color: var(--svg-color--1f0d22, #1F0D22);
}

.xg491tydm {
  stop-color: var(--svg-color--6655a7, #6655A7);
  stop-opacity: 0;
}

.xgbg8db5s {
  stop-color: var(--svg-color--413f40, #413F40);
}

.xlqlhebaa {
  d: path("M12.127 14.599c-.289-.031-.859-.05-1.402.312c-.703.547-1.16 1.196-1.301 2.25c-.198 1.482 1.045 3.944 6.574 4.18h.004c5.529-.236 6.772-2.698 6.574-4.18c-.14-1.054-.598-1.703-1.3-2.25c-.606-.47-1.103-.468-1.392-.437L16 14.91z");
}

.xodttob3f {
  stop-color: var(--svg-color--7f70bc, #7F70BC);
  stop-opacity: 0;
}

.y_x9jlxov {
  stop-color: var(--svg-color--271619, #271619);
}

.y5y2xtbig {
  stop-color: var(--svg-color--4d3d3d, #4D3D3D);
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

.ydiwmubvk {
  stop-color: var(--svg-color--1a0910, #1A0910);
}

.yg8va_99z {
  stop-color: var(--svg-color--eddda3, #EDDDA3);
}

.yipkkxtvy {
  stop-color: var(--svg-color--4d3b3a, #4D3B3A);
  stop-opacity: 0;
}

.yyik5z8lx {
  stop-color: var(--svg-color--949393, #949393);
  stop-opacity: 0;
}

.z5duhrbsp {
  stop-color: var(--svg-color--aba5ae, #ABA5AE);
}

.zh35wab0s {
  stop-color: var(--svg-color--7b4b52, #7B4B52);
  stop-opacity: 0;
}

.zhtqcybuc {
  fill: var(--svg-color--000, #000);
  d: path("M14.342 10.487a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.zm2sgebiw {
  stop-color: var(--svg-color--3a3235, #3A3235);
  stop-opacity: 0;
}

.zmkruk91v {
  stop-color: var(--svg-color--62504f, #62504F);
  stop-opacity: 0;
}

.zy0uiq7qe {
  stop-color: var(--svg-color--3b262a, #3B262A);
  stop-opacity: 0;
}

</style>
