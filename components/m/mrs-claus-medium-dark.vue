<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="yp5651blu"/><path fill="url(#iEvVtnO)" class="vtcjkxbtk"/><path fill="url(#icWfG1b)" class="vtcjkxbtk"/><g filter="url(#i0yCBse)"><path fill="url(#iXf0zoa)" class="a3r2kccmb"/></g><g filter="url(#izlGTga)"><path fill="url(#imgUwjp)" class="gbi13_0do"/></g><path fill="url(#ioasHkL)" class="yabgkrbcu"/><path fill="url(#i6rOTSd)" class="yabgkrbcu"/><path fill="url(#i47mXfg)" class="yabgkrbcu"/><path fill="url(#ihUUmid)" class="yabgkrbcu"/><path fill="url(#izvaJMc)" class="yabgkrbcu"/><path fill="url(#iiba9Fd)" class="yabgkrbcu"/><path fill="url(#inTpjZo)" class="yabgkrbcu"/><path fill="url(#i3s93fc)" class="yabgkrbcu"/><path fill="url(#icCS7rd)" class="yabgkrbcu"/><path fill="url(#iptg4Pb)" class="yabgkrbcu"/><g filter="url(#igvJpgk)"><path fill="url(#igTB3Pe)" class="pmoachbcr"/></g><g filter="url(#iXmB4we)"><path fill="url(#ib02Okd)" class="h56v5fbbq"/></g><g filter="url(#iqJqIKd)"><path fill="url(#iIkzVIb)" class="tehcnqbzy"/></g><g filter="url(#iJYR5Lb)"><path class="gmmkewpxm"/><path fill="url(#ioc46Bc)" class="qt2l035us"/><path fill="url(#iz47Zqd)" class="qt2l035us"/><path fill="url(#iVEIA1c)" class="qt2l035us"/><path fill="url(#iie8RNd)" class="qt2l035us"/><path fill="url(#iMS613i)" class="qt2l035us"/><path fill="url(#iZw0atb)" class="qt2l035us"/></g><g filter="url(#iY7sPzG)"><path stroke="url(#iTOd8xb)" class="r5fjjab0i"/></g><path class="dlov_1byg"/><g filter="url(#iEtWzxb)"><path class="u9y3jsbju"/></g><g filter="url(#iwCJ22d)"><path class="t2qfweb2m"/></g><path class="itiikvylr"/><path fill="url(#iZ1Kqov)" class="xruv_mbei"/><path class="sc0yvsrxt"/><g filter="url(#iKvWzce)"><path class="tcpe2_dxj"/><path fill="url(#igzqhie)" class="tujpxbpmf"/></g><g filter="url(#iUL9Avb)"><path fill="url(#ioYsfOc)" class="nxt5vrbqi"/></g><path class="br05f6y-k"/><path fill="url(#iV0iVlb)" class="a9tgniopo"/><path class="wz_uy8j0i"/><g filter="url(#ivAk0Nx)"><path fill="url(#iGOy7Cd)" class="did2-4bxl"/></g><g filter="url(#ijzHnad)"><ellipse transform="rotate(-27.914 11.437 17.535)" class="r9mw8xbto"/><ellipse fill="url(#iSH5SLc)" transform="rotate(-27.914 11.437 17.535)" class="drn57kbac"/></g><g filter="url(#i6jAsSf)"><path fill="url(#i5oZ1uc)" class="l56-qf5ll"/><path fill="url(#il7Kveb)" class="l56-qf5ll"/><path fill="url(#ivb9gid)" class="l56-qf5ll"/><path fill="url(#iB3wbSM)" class="l56-qf5ll"/></g><g filter="url(#idftqbc)"><path clip-rule="evenodd" class="qfb_zxbhk"/></g><g filter="url(#i4dmvge)"><path clip-rule="evenodd" class="jmqb0dr9v"/></g><g filter="url(#iAELO7b)"><path clip-rule="evenodd" class="ybavvpbvb"/><path fill="url(#inUj4Kd)" clip-rule="evenodd" class="mmx3-bcfv"/><path fill="url(#i2OjXnb)" clip-rule="evenodd" class="mmx3-bcfv"/><path fill="url(#ij0QmxE)" clip-rule="evenodd" class="mmx3-bcfv"/></g><g filter="url(#iOEaJPe)"><path clip-rule="evenodd" class="i0nit7b7x"/><path fill="url(#iX7GNZb)" clip-rule="evenodd" class="j8srnhp_e"/><path fill="url(#iFaquhd)" clip-rule="evenodd" class="j8srnhp_e"/></g><g filter="url(#i18wb8b)"><path class="qnos2qb2v"/><path fill="url(#ifMRFsb)" class="rlocizbva"/><path fill="url(#iH7mcoe)" class="rlocizbva"/></g><path fill="url(#iFgZKld)" class="rlocizbva"/><g filter="url(#iOlfUUl)"><path class="jmlvqybbs"/><path fill="url(#iwnDRjd)" class="d8zao2b-x"/><path fill="url(#inlF3gb)" class="d8zao2b-x"/></g><g filter="url(#iypJvxj)"><path class="m90sntwdf"/><path fill="url(#iHw3Swe)" class="grt0uoblw"/></g><g filter="url(#i1TJrXc)"><path stroke="url(#iFzgNhe)" class="odr8zlbiv"/></g><g filter="url(#iyjv1lc)"><path stroke="url(#ivalSjd)" class="ao7ivib-g"/></g><g filter="url(#iatGfRU)"><path fill="url(#iBfTu2q)" class="vd_1e8b-h"/><path fill="url(#iHg82lb)" class="vd_1e8b-h"/></g><g filter="url(#ifCWCFi)"><path fill="url(#ie4Xmdd)" class="cgoiino6b"/></g><g filter="url(#icZvOLc)"><path fill="url(#i2YIZzb)" class="yznnuplse"/><path fill="url(#i4JTt9c)" class="yznnuplse"/><path fill="url(#ike3ZFA)" class="yznnuplse"/></g><g filter="url(#iZg2wge)"><path fill="url(#iwxRQdc)" class="qfftlvbcs"/></g><g filter="url(#i3oKpie)"><path fill="url(#iKHacKd)" class="kolcl4w5q"/><path fill="url(#inWPuvc)" class="kolcl4w5q"/><path fill="url(#iInSPAd)" class="kolcl4w5q"/></g><g filter="url(#iNekhad)"><path fill="url(#idw6mOU)" class="uj-2_e4rs"/><path fill="url(#i3Q47Fb)" class="uj-2_e4rs"/></g><defs><radialGradient id="iEvVtnO" cx="0" cy="0" r="1" gradientTransform="matrix(-15.1875 0 0 -10.125 21.381 6.292)" gradientUnits="userSpaceOnUse"><stop offset=".698" class="mzycncwxb"/><stop offset="1" class="o6ackn6vy"/></radialGradient><radialGradient id="icWfG1b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6875 4.6875 -5.60964 -8.00307 25.475 4.23)" gradientUnits="userSpaceOnUse"><stop class="vn83tqcbo"/><stop offset="1" class="c47ug_iov"/></radialGradient><radialGradient id="iXf0zoa" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.029 17.613)scale(4.54255 3.9894)" gradientUnits="userSpaceOnUse"><stop class="zwa0gtbqc"/><stop offset="1" class="ypxhk30rd"/></radialGradient><radialGradient id="imgUwjp" cx="0" cy="0" r="1" gradientTransform="rotate(49.526 -18.227 14.496)scale(3.89961)" gradientUnits="userSpaceOnUse"><stop class="avk3k4btv"/><stop offset="1" class="jl0-trvct"/></radialGradient><radialGradient id="ioasHkL" cx="0" cy="0" r="1" gradientTransform="rotate(149.208 8.4 11.077)scale(14.0258 18.7732)" gradientUnits="userSpaceOnUse"><stop class="luau5bboi"/><stop offset=".714" class="orirlba9n"/></radialGradient><radialGradient id="i6rOTSd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.90625 5.875 -4.41427 -4.43776 11.403 10.726)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="drc95usag"/><stop offset="1" class="soldpzbyh"/></radialGradient><radialGradient id="i47mXfg" cx="0" cy="0" r="1" gradientTransform="matrix(2.18792 -8.6415 22.15337 5.60896 13.748 29.93)" gradientUnits="userSpaceOnUse"><stop class="og08facuy"/><stop offset="1" class="cab1b-b0h"/></radialGradient><radialGradient id="ihUUmid" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.0727 -13.4885 0 15.935 17.538)" gradientUnits="userSpaceOnUse"><stop offset=".892" class="fkh5q1b6f"/><stop offset=".96" class="as6-d-a9a"/></radialGradient><radialGradient id="iiba9Fd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0839 -2.91528 2.89208 -1.07527 12.08 17.392)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="gqasisbix"/><stop offset="1" class="met3g2jtu"/></radialGradient><radialGradient id="inTpjZo" cx="0" cy="0" r="1" gradientTransform="rotate(88.84 4.148 20.938)scale(5.4855 .22778)" gradientUnits="userSpaceOnUse"><stop offset=".571" class="ab6j4dboq"/><stop offset="1" class="nzdgq5g3q"/></radialGradient><radialGradient id="i3s93fc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -2.90625 2.90512 1.28075 20.497 17.632)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="icCS7rd" cx="0" cy="0" r="1" gradientTransform="rotate(91.368 -3.98 10.404)scale(5.23587 1.43448)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="ic-oncu-g"/><stop offset="1" class="vi3uji6ek"/></radialGradient><radialGradient id="iptg4Pb" cx="0" cy="0" r="1" gradientTransform="matrix(5.81252 3.03122 -1.02207 1.95986 21.528 12.288)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="w8g7dlbjf"/><stop offset="1" class="wia9x5b1c"/></radialGradient><radialGradient id="igTB3Pe" cx="0" cy="0" r="1" gradientTransform="matrix(5.1875 1.28125 -1.21262 4.90965 17.788 21.073)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="n9a19t_mp"/><stop offset="1" class="lli15fbvt"/></radialGradient><radialGradient id="ib02Okd" cx="0" cy="0" r="1" gradientTransform="rotate(101.083 -2.828 15.033)scale(3.08885 4.56981)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="ajj7m_b6f"/><stop offset="1" class="hs0abnp8m"/></radialGradient><radialGradient id="iz47Zqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20313 4.95336 0 15.947 22.273)" gradientUnits="userSpaceOnUse"><stop class="oo3ogkscv"/><stop offset="1" class="zxx6y458s"/></radialGradient><radialGradient id="iVEIA1c" cx="0" cy="0" r="1" gradientTransform="matrix(.96093 1.53907 -.79747 .4979 17.52 19.973)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="mq740vtdm"/><stop offset="1" class="r73c1xbox"/></radialGradient><radialGradient id="iie8RNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.85938 0 0 -.4735 16.888 21.262)" gradientUnits="userSpaceOnUse"><stop class="kc9php6zk"/><stop offset="1" class="z65w2qfou"/></radialGradient><radialGradient id="iZw0atb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.67187 2.46699 0 15.947 20.825)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="eog-5o_9g"/><stop offset="1" class="snzwbfsph"/></radialGradient><radialGradient id="iZ1Kqov" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23439 1.98436 -2.08903 -1.2995 20.789 17.246)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="kz8v_2b0u"/><stop offset="1" class="t_fhyk9zs"/></radialGradient><radialGradient id="igzqhie" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.146 4.148)scale(.69518 .9571)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iV0iVlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23439 1.98437 -2.08904 -1.2995 12.763 17.246)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="kz8v_2b0u"/><stop offset="1" class="t_fhyk9zs"/></radialGradient><radialGradient id="iSH5SLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.01423 -.90865 1.09224 -.0171 11.41 18.114)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="il7Kveb" cx="0" cy="0" r="1" gradientTransform="matrix(-.1076 1.90987 -2.1901 -.12338 10.615 4.846)" gradientUnits="userSpaceOnUse"><stop class="o-gllcbpi"/><stop offset="1" class="op8gn6bnt"/></radialGradient><radialGradient id="ivb9gid" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23266 0 0 -5.95693 7.091 18.78)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="c3098ubep"/><stop offset=".808" class="ixxpbv8hf"/></radialGradient><radialGradient id="iB3wbSM" cx="0" cy="0" r="1" gradientTransform="rotate(118.957 8.501 15.231)scale(5.35726 1.55455)" gradientUnits="userSpaceOnUse"><stop class="paruexevs"/><stop offset="1" class="lcus7p0ww"/></radialGradient><radialGradient id="inUj4Kd" cx="0" cy="0" r="1" gradientTransform="rotate(131.743 -.21 11.557)scale(.68059 .35127)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="egvfrgbew"/><stop offset="1" class="i6zk_phor"/></radialGradient><radialGradient id="ij0QmxE" cx="0" cy="0" r="1" gradientTransform="matrix(.5337 0 0 .67969 6.495 19.328)" gradientUnits="userSpaceOnUse"><stop class="du3zqdbas"/><stop offset="1" class="eo5th8odz"/></radialGradient><radialGradient id="iX7GNZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.43383 .09524 -.1381 -.62905 25.485 19.204)" gradientUnits="userSpaceOnUse"><stop class="yace-6bkn"/><stop offset="1" class="x6b7fvhjk"/></radialGradient><radialGradient id="ifMRFsb" cx="0" cy="0" r="1" gradientTransform="matrix(-.80005 -1.45312 .28898 -.1591 17.682 18.98)" gradientUnits="userSpaceOnUse"><stop class="pi9myibky"/><stop offset="1" class="a4r8facys"/></radialGradient><radialGradient id="iH7mcoe" cx="0" cy="0" r="1" gradientTransform="matrix(.57813 -1.10938 .29816 .15538 14.678 19.136)" gradientUnits="userSpaceOnUse"><stop class="x6t_0e-6t"/><stop offset="1" class="n01394_5x"/></radialGradient><radialGradient id="iFgZKld" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96021 -1.0123 1.0168 -1.96892 16.225 19.526)" gradientUnits="userSpaceOnUse"><stop offset=".77" class="tygkjs-ny"/><stop offset=".937" class="lqfy3p-zi"/></radialGradient><radialGradient id="iBfTu2q" cx="0" cy="0" r="1" gradientTransform="matrix(-2.63619 -5.40116 1.4488 -.70713 8.006 12.808)" gradientUnits="userSpaceOnUse"><stop class="cvqywpbya"/><stop offset="1" class="do75vybld"/></radialGradient><radialGradient id="iHg82lb" cx="0" cy="0" r="1" gradientTransform="matrix(.55304 6.50969 -3.32228 .28225 6.554 8.262)" gradientUnits="userSpaceOnUse"><stop offset=".505" class="tjn-pbcga"/><stop offset="1" class="q270rhb2n"/></radialGradient><radialGradient id="ie4Xmdd" cx="0" cy="0" r="1" gradientTransform="matrix(5.54388 1.16889 -2.00192 9.49486 22.68 11.435)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="o0zfjub8g"/><stop offset=".932" class="emarm55as"/></radialGradient><radialGradient id="i2YIZzb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93356 -6.50176 2.0863 -.62045 10.645 11.675)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="hffkdxxqc"/><stop offset="1" class="pew6frnzi"/></radialGradient><radialGradient id="i4JTt9c" cx="0" cy="0" r="1" gradientTransform="rotate(162.165 4.709 5.44)scale(3.24962 5.81408)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="d2xfa78kb"/><stop offset="1" class="bemgdwb7k"/></radialGradient><radialGradient id="ike3ZFA" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.39841 -3.90671 0 9.63 8.128)" gradientUnits="userSpaceOnUse"><stop offset=".817" class="h13c6fb3k"/><stop offset="1" class="k-7dzim-i"/></radialGradient><radialGradient id="iwxRQdc" cx="0" cy="0" r="1" gradientTransform="rotate(32.247 -3.901 40.263)scale(5.50541 6.13649)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="q63b76bcm"/><stop offset="1" class="l_nupdb1h"/></radialGradient><radialGradient id="iKHacKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.34375 4.69757 0 15.819 8.573)" gradientUnits="userSpaceOnUse"><stop offset=".357" class="ea88qbbkv"/><stop offset="1" class="l_hht1tza"/></radialGradient><radialGradient id="iInSPAd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03127 5.6875 -4.70513 -1.68042 13.663 5.76)" gradientUnits="userSpaceOnUse"><stop offset=".544" class="o8-p00v9r"/><stop offset="1" class="kpi-j7bnf"/></radialGradient><radialGradient id="idw6mOU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.78125 3.21875 0 19.847 8.886)" gradientUnits="userSpaceOnUse"><stop class="gh7w8ccdd"/><stop offset="1" class="q90nxab-j"/></radialGradient><radialGradient id="i3Q47Fb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 2.25 -3.86674 -5.58532 19.756 7.386)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="ju711jbwd"/><stop offset="1" class="ep--azv6o"/></radialGradient><filter id="i0yCBse" width="6.033" height="6.033" x="22.017" y="15.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.290196 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/></filter><filter id="izlGTga" width="6.033" height="5.933" x="3.945" y="15.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.372549 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/></filter><filter id="igvJpgk" width="8.322" height="4.297" x="15.869" y="19.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".375"/></filter><filter id="iXmB4we" width="8.322" height="4.297" x="6.962" y="19.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".375"/></filter><filter id="iqJqIKd" width="4.312" height="5.936" x="13.421" y="17.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".25"/></filter><filter id="iJYR5Lb" width="3.555" height="4.778" x="14.22" y="17.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.278431 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/></filter><filter id="iY7sPzG" width="6.478" height="2.472" x="12.708" y="23.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".05"/></filter><filter id="iEtWzxb" width="5.356" height="2.366" x="18.049" y="16.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0588235 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/></filter><filter id="iwCJ22d" width="5.356" height="2.366" x="8.696" y="16.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0588235 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/></filter><filter id="iKvWzce" width="1.278" height="1.112" x="18.696" y="16.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".05"/></filter><filter id="iUL9Avb" width="1.303" height="1.343" x="20.326" y="17.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".1"/></filter><filter id="ivAk0Nx" width="1.477" height="1.577" x="12.155" y="17.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".1"/></filter><filter id="ijzHnad" width="1.511" height="1.128" x="10.681" y="16.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".05"/></filter><filter id="i6jAsSf" width="25.121" height="17.787" x="3.515" y="3.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.615686 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/></filter><filter id="idftqbc" width="4.251" height="1.951" x="8.893" y="13.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.415686 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.32549 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24205" result="effect2_innerShadow_3987_24205"/></filter><filter id="i4dmvge" width="4.251" height="1.951" x="18.821" y="13.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.415686 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.32549 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24205" result="effect2_innerShadow_3987_24205"/></filter><filter id="iAELO7b" width="2.77" height=".9" x="6.495" y="18.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.392157 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/></filter><filter id="iOEaJPe" width="2.97" height=".9" x="22.788" y="18.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.435294 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/></filter><filter id="i18wb8b" width="3.466" height="1.925" x="14.265" y="17.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.447059 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/></filter><filter id="iOlfUUl" width="6.862" height="2.837" x="16.957" y="18.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".02" dy="-.02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.776471 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.937255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24205" result="effect2_innerShadow_3987_24205"/></filter><filter id="iypJvxj" width="6.862" height="2.837" x="8.05" y="18.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".02" dy="-.02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.776471 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24205"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.937255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24205" result="effect2_innerShadow_3987_24205"/></filter><filter id="i1TJrXc" width="3.891" height="1.346" x="9.038" y="13.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".125"/></filter><filter id="iyjv1lc" width="3.891" height="1.346" x="19.032" y="13.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".125"/></filter><filter id="iatGfRU" width="6.389" height="9.227" x="3.959" y="6.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".25"/></filter><filter id="ifCWCFi" width="6.538" height="8.968" x="21.546" y="6.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".25"/></filter><filter id="icZvOLc" width="5.609" height="9.353" x="6.825" y="4.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".25"/></filter><filter id="iZg2wge" width="5.609" height="9.353" x="19.837" y="4.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".25"/></filter><filter id="i3oKpie" width="6.2" height="9.592" x="9.977" y="3.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".3"/></filter><filter id="iNekhad" width="6.2" height="9.592" x="15.705" y="3.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24205" stdDeviation=".3"/></filter><linearGradient id="izvaJMc" x1="6.762" x2="9.874" y1="20.046" y2="20.233" gradientUnits="userSpaceOnUse"><stop offset=".211" class="a36s5vqdl"/><stop offset="1" class="jnmoqubxq"/></linearGradient><linearGradient id="iIkzVIb" x1="14.376" x2="15.305" y1="21.088" y2="22.486" gradientUnits="userSpaceOnUse"><stop class="ejc3809_s"/><stop offset="1" class="fwp6n_btw"/></linearGradient><linearGradient id="ioc46Bc" x1="17.675" x2="15.947" y1="20.981" y2="21.074" gradientUnits="userSpaceOnUse"><stop offset=".282" class="vq4x1zbbl"/><stop offset="1" class="fwo8ffbnk"/></linearGradient><linearGradient id="iMS613i" x1="14.35" x2="15.144" y1="20.044" y2="20.331" gradientUnits="userSpaceOnUse"><stop class="ws7rkabdc"/><stop offset="1" class="dp5xz3njn"/></linearGradient><linearGradient id="iTOd8xb" x1="14.605" x2="15.438" y1="25.477" y2="23.872" gradientUnits="userSpaceOnUse"><stop class="u_az6f3zk"/><stop offset="1" class="ge1o9fbgx"/></linearGradient><linearGradient id="ioYsfOc" x1="21.394" x2="20.817" y1="17.81" y2="18.165" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGOy7Cd" x1="13.305" x2="12.728" y1="17.81" y2="18.165" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5oZ1uc" x1="26.288" x2="10.475" y1="14.667" y2="14.667" gradientUnits="userSpaceOnUse"><stop class="o1xctu8tq"/><stop offset="1" class="e3tydgbfn"/></linearGradient><linearGradient id="i2OjXnb" x1="7.879" x2="7.879" y1="18.897" y2="19.12" gradientUnits="userSpaceOnUse"><stop class="unozt67tp"/><stop offset="1" class="sjitiy62y"/></linearGradient><linearGradient id="iFaquhd" x1="24.172" x2="24.172" y1="18.925" y2="19.124" gradientUnits="userSpaceOnUse"><stop class="t233yurnp"/><stop offset="1" class="dte4ogbdr"/></linearGradient><linearGradient id="iwnDRjd" x1="21.35" x2="21.35" y1="21.706" y2="20.308" gradientUnits="userSpaceOnUse"><stop offset=".006" class="xcvhc4axz"/><stop offset="1" class="fl8h_cbee"/></linearGradient><linearGradient id="inlF3gb" x1="18.795" x2="20.686" y1="19.917" y2="20.651" gradientUnits="userSpaceOnUse"><stop class="xh84v07wd"/><stop offset=".141" class="akeuncc3p"/><stop offset=".868" class="akeuncc3p"/><stop offset="1" class="xh84v07wd"/></linearGradient><linearGradient id="iHw3Swe" x1="12.655" x2="10.655" y1="20.643" y2="19.8" gradientUnits="userSpaceOnUse"><stop class="p9zg-objl"/><stop offset=".141" class="yg9ra3bzd"/><stop offset=".868" class="yg9ra3bzd"/><stop offset="1" class="p9zg-objl"/></linearGradient><linearGradient id="iFzgNhe" x1="12.553" x2="9.154" y1="14.196" y2="15.099" gradientUnits="userSpaceOnUse"><stop offset=".166" class="g8eaedcck"/><stop offset="1" class="jnjw33b1s"/></linearGradient><linearGradient id="ivalSjd" x1="22.548" x2="18.399" y1="14.716" y2="14.418" gradientUnits="userSpaceOnUse"><stop offset=".166" class="g8eaedcck"/><stop offset="1" class="jnjw33b1s"/></linearGradient><linearGradient id="inWPuvc" x1="10.288" x2="13.073" y1="8.291" y2="8.291" gradientUnits="userSpaceOnUse"><stop class="h243fe46z"/><stop offset="1" class="w-amzpbim"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mrs-claus-medium-dark" /></template>
<style>
.a36s5vqdl {
  stop-color: var(--svg-color--7c5b55, #7C5B55);
}

.a3r2kccmb {
  d: path("M24.984 21.918a2.966 2.966 0 1 0 0-5.933a2.966 2.966 0 0 0 0 5.933");
}

.a4r8facys {
  stop-color: var(--svg-color--d8dfe2, #D8DFE2);
  stop-opacity: 0;
}

.a9tgniopo {
  d: path("M11.934 16.833a1.643 1.643 0 0 0-1.583 2.076h3.173a1.7 1.7 0 0 0 .06-.433a1.654 1.654 0 0 0-1.65-1.643");
}

.ab6j4dboq {
  stop-color: var(--svg-color--6b3c2f, #6B3C2F);
}

.ajj7m_b6f {
  stop-color: var(--svg-color--673e46, #673E46);
}

.akeuncc3p {
  stop-color: var(--svg-color--b8e1ee, #B8E1EE);
}

.ao7ivib-g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.548 14.716c-.354-.255-1.478-.725-3.14-.562");
}

.as6-d-a9a {
  stop-color: var(--svg-color--8a5788, #8A5788);
}

.avk3k4btv {
  stop-color: var(--svg-color--694141, #694141);
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.bemgdwb7k {
  stop-color: var(--svg-color--b4b0b8, #B4B0B8);
}

.br05f6y-k {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.553 16.333a2.57 2.57 0 0 0-2.494 1.949a.505.505 0 0 0 .493.627h4.106c.262 0 .47-.239.418-.5a2.58 2.58 0 0 0-2.523-2.076");
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.c47ug_iov {
  stop-color: var(--svg-color--ff4f58, #FF4F58);
  stop-opacity: 0;
}

.cab1b-b0h {
  stop-color: var(--svg-color--794559, #794559);
  stop-opacity: 0;
}

.cgoiino6b {
  d: path("M26.48 7.832c-.998-.56-2.004-.448-2.383-.323l-1.912 5.03c-.13.278-.436.655.673 1.018c1.1.361 1.947 1.017 2.18 1.663c.043.12.174.2.28.127c.825-.571 1.56-2.594 1.993-3.83c.471-1.345.416-2.986-.831-3.685");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cvqywpbya {
  stop-color: var(--svg-color--b8b5bb, #B8B5BB);
}

.d2xfa78kb {
  stop-color: var(--svg-color--b4b0b8, #B4B0B8);
  stop-opacity: 0;
}

.d8zao2b-x {
  d: path("M23.093 18.91h-5.735c-.232 0-.418.198-.375.426c.318 1.723 1.717 2.35 2.461 2.37l1.922-.043c1.425-.047 2.073-.986 2.39-1.875c.17-.476-.193-.879-.663-.879");
}

.did2-4bxl {
  d: path("M13.433 18.282c0-.53-.431-.884-.548-.99l-.53.512l.326.664z");
}

.dlov_1byg {
  fill: var(--svg-color--89014f, #89014F);
  d: path("M15.947 24.196c-.958 0-1.86-.23-2.616-.634c-.26-.135-.537.163-.374.404a3.56 3.56 0 0 0 2.99 1.634a3.56 3.56 0 0 0 2.99-1.634c.164-.25-.114-.539-.373-.404a5.55 5.55 0 0 1-2.617.634");
}

.do75vybld {
  stop-color: var(--svg-color--b8b5bb, #B8B5BB);
  stop-opacity: 0;
}

.dp5xz3njn {
  stop-color: var(--svg-color--684540, #684540);
  stop-opacity: 0;
}

.drc95usag {
  stop-color: var(--svg-color--724c4b, #724C4B);
}

.drn57kbac {
  cx: 11.437px;
  cy: 17.535px;
  rx: 0.717px;
  ry: 0.363px;
}

.dte4ogbdr {
  stop-color: var(--svg-color--c7c6ca, #C7C6CA);
  stop-opacity: 0;
}

.du3zqdbas {
  stop-color: var(--svg-color--828084, #828084);
}

.e3tydgbfn {
  stop-color: var(--svg-color--bab9bc, #BAB9BC);
}

.ea88qbbkv {
  stop-color: var(--svg-color--f0edf4, #F0EDF4);
}

.egvfrgbew {
  stop-color: var(--svg-color--6f7587, #6F7587);
}

.ejc3809_s {
  stop-color: var(--svg-color--663d40, #663D40);
}

.emarm55as {
  stop-color: var(--svg-color--dbd9dd, #DBD9DD);
}

.eo5th8odz {
  stop-color: var(--svg-color--828084, #828084);
  stop-opacity: 0;
}

.eog-5o_9g {
  stop-color: var(--svg-color--734744, #734744);
  stop-opacity: 0;
}

.ep--azv6o {
  stop-color: var(--svg-color--ccc9d0, #CCC9D0);
}

.fkh5q1b6f {
  stop-color: var(--svg-color--793f69, #793F69);
  stop-opacity: 0;
}

.fl8h_cbee {
  stop-color: var(--svg-color--80cce7, #80CCE7);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwo8ffbnk {
  stop-color: var(--svg-color--917470, #917470);
  stop-opacity: 0;
}

.fwp6n_btw {
  stop-color: var(--svg-color--763f53, #763F53);
}

.g8eaedcck {
  stop-color: var(--svg-color--97949a, #97949A);
}

.gbi13_0do {
  d: path("M6.911 21.918a2.966 2.966 0 1 0 0-5.933a2.966 2.966 0 0 0 0 5.933");
}

.ge1o9fbgx {
  stop-color: var(--svg-color--865f66, #865F66);
  stop-opacity: 0;
}

.gh7w8ccdd {
  stop-color: var(--svg-color--f7f5f9, #F7F5F9);
}

.gmmkewpxm {
  fill: var(--svg-color--7f5e55, #7F5E55);
  d: path("m15.243 18.175l-.978 2.97a.993.993 0 0 0 .958 1.288h1.448a.996.996 0 0 0 .958-1.288l-.978-2.97c-.21-.693-1.188-.693-1.408 0");
}

.gqasisbix {
  stop-color: var(--svg-color--6e414d, #6E414D);
}

.grt0uoblw {
  d: path("M8.776 18.91h5.735c.232 0 .418.198.376.426c-.319 1.723-1.718 2.35-2.462 2.37l-1.922-.043c-1.425-.047-2.073-.986-2.39-1.875c-.17-.476.194-.879.663-.879");
}

.h13c6fb3k {
  stop-color: var(--svg-color--b39cb2, #B39CB2);
  stop-opacity: 0;
}

.h243fe46z {
  stop-color: var(--svg-color--b6b4b8, #B6B4B8);
}

.h56v5fbbq {
  d: path("M8.419 19.89h5.734c.232 0 .418.2.376.428c-.319 1.722-1.718 2.35-2.462 2.37l-1.921-.043c-1.426-.047-2.074-.986-2.391-1.875c-.17-.476.194-.88.664-.88");
}

.hffkdxxqc {
  stop-color: var(--svg-color--c9c2d1, #C9C2D1);
}

.hs0abnp8m {
  stop-color: var(--svg-color--673e46, #673E46);
  stop-opacity: 0;
}

.i0nit7b7x {
  fill: var(--svg-color--c7c7cd, #C7C7CD);
  fill-rule: evenodd;
  d: path("M22.788 19.3c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75h-2.02a.375.375 0 0 1-.375-.375");
}

.i6zk_phor {
  stop-color: var(--svg-color--8d889f, #8D889F);
  stop-opacity: 0;
}

.ic-oncu-g {
  stop-color: var(--svg-color--603a3a, #603A3A);
}

.itiikvylr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.348 16.333c1.202 0 2.218.829 2.494 1.949a.505.505 0 0 1-.493.627h-4.106a.424.424 0 0 1-.418-.5a2.57 2.57 0 0 1 2.523-2.076");
}

.ixxpbv8hf {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
  stop-opacity: 0;
}

.j8srnhp_e {
  fill-rule: evenodd;
  d: path("M22.788 19.3c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75h-2.02a.375.375 0 0 1-.375-.375");
}

.jl0-trvct {
  stop-color: var(--svg-color--68364c, #68364C);
}

.jmlvqybbs {
  fill: var(--svg-color--85dbf1, #85DBF1);
  d: path("M23.093 18.91h-5.735c-.232 0-.418.198-.375.426c.318 1.723 1.717 2.35 2.461 2.37l1.922-.043c1.425-.047 2.073-.986 2.39-1.875c.17-.476-.193-.879-.663-.879");
}

.jmqb0dr9v {
  fill: var(--svg-color--87838b, #87838B);
  fill-rule: evenodd;
  d: path("M19.41 14.815c1.51-.273 2.56.224 2.844.457a.5.5 0 1 0 .635-.772c-.526-.433-1.878-.99-3.657-.67a.5.5 0 1 0 .178.985");
}

.jnjw33b1s {
  stop-color: var(--svg-color--97949a, #97949A);
  stop-opacity: 0;
}

.jnmoqubxq {
  stop-color: var(--svg-color--7c5b55, #7C5B55);
  stop-opacity: 0;
}

.ju711jbwd {
  stop-color: var(--svg-color--ccc9d0, #CCC9D0);
  stop-opacity: 0;
}

.k-7dzim-i {
  stop-color: var(--svg-color--b39cb2, #B39CB2);
}

.kc9php6zk {
  stop-color: var(--svg-color--92736f, #92736F);
}

.kolcl4w5q {
  d: path("M10.577 9.104V5.183c.86-.172 1.047-.79 2.383-1.125c1.085-.196 1.593.257 2.617.64v4.625c-.663 1.647-2.365 2.619-3.47 3.028c-.308.114-.66.038-.848-.232c-.604-.867-.682-2.198-.682-3.015");
}

.kpi-j7bnf {
  stop-color: var(--svg-color--b7a9bb, #B7A9BB);
}

.kz8v_2b0u {
  stop-color: var(--svg-color--825c4f, #825C4F);
}

.l_hht1tza {
  stop-color: var(--svg-color--f0edf4, #F0EDF4);
  stop-opacity: 0;
}

.l_nupdb1h {
  stop-color: var(--svg-color--d1cbd8, #D1CBD8);
}

.l56-qf5ll {
  d: path("M6.744 21.285a.095.095 0 0 0 .1-.09c.05-.81.162-2.752.198-3.966c.052-1.72.863-2.687 2.12-3.242a10 10 0 0 0 1.637-.795c.247-.15.44-.266.757-.385q.129-.046.32-.105c.88-.276 2.81-1.076 3.887-3.178c.085-.166.348-.157.423.014c.935 2.11 2.958 2.884 3.864 3.156q.216.063.356.113c.316.119.573.214.82.364c.799.487.839.445 1.804.84c1.82.812 1.87 1.53 1.87 3.218c.037 1.214.105 3.159.152 3.97a.094.094 0 0 0 .1.09c1.223-.08 1.912-1.705 2.106-2.528l.785-2.97c.4-1.585.55-2.418.362-3.097c-.173-.625-.655-1.314-.833-1.527c0-.073.022-.207.05-.383c.096-.582.128-1.362-.186-2.07c-.503-1.05-1.258-1.313-1.781-1.461c-.477-.07-.764-.256-1.016-.781c-.992-1.794-2.234-1.696-2.805-1.696c-.461.055-.773.055-1.289-.297c-1.312-1.093-2.637-.703-3.423-.328c-.628.3-1.016.344-1.131.328c-.116.016-.505-.028-1.137-.328c-.789-.375-2.059-.797-3.45.328c-.46.399-.701.396-1.189.339c-.393-.047-1.97-.179-2.966 1.615c-.253.525-.717.62-.949.625c-.437.03-1.436.356-1.941 1.406c-.315.708-.225 1.746-.13 2.328c.029.175.05.31.05.383c-.178.213-.528.875-.702 1.5c-.188.678.088 2.34.308 3.117l.79 2.969c.195.823.842 2.445 2.07 2.524");
}

.lcus7p0ww {
  stop-color: var(--svg-color--faf9fc, #FAF9FC);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lli15fbvt {
  stop-color: var(--svg-color--6b3d44, #6B3D44);
  stop-opacity: 0;
}

.lqfy3p-zi {
  stop-color: var(--svg-color--7a8488, #7A8488);
}

.luau5bboi {
  stop-color: var(--svg-color--9b7163, #9B7163);
}

.m90sntwdf {
  fill: var(--svg-color--85d7ed, #85D7ED);
  d: path("M8.776 18.91h5.735c.232 0 .418.198.376.426c-.319 1.723-1.718 2.35-2.462 2.37l-1.922-.043c-1.425-.047-2.073-.986-2.39-1.875c-.17-.476.194-.879.663-.879");
}

.met3g2jtu {
  stop-color: var(--svg-color--6e414d, #6E414D);
  stop-opacity: 0;
}

.mmx3-bcfv {
  fill-rule: evenodd;
  d: path("M6.495 19.3c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75H6.87a.375.375 0 0 1-.375-.375");
}

.mq740vtdm {
  stop-color: var(--svg-color--6e4944, #6E4944);
}

.mzycncwxb {
  stop-color: var(--svg-color--a33337, #A33337);
  stop-opacity: 0;
}

.n01394_5x {
  stop-color: var(--svg-color--c9d2d8, #C9D2D8);
  stop-opacity: 0;
}

.n9a19t_mp {
  stop-color: var(--svg-color--6b3d44, #6B3D44);
}

.nxt5vrbqi {
  d: path("M21.429 18.258a1.54 1.54 0 0 0-.425-.85l-.478.524l.216.42z");
}

.nzdgq5g3q {
  stop-color: var(--svg-color--6b3c2f, #6B3C2F);
  stop-opacity: 0;
}

.o-gllcbpi {
  stop-color: var(--svg-color--c3c2c2, #C3C2C2);
}

.o0zfjub8g {
  stop-color: var(--svg-color--dbd9dd, #DBD9DD);
  stop-opacity: 0;
}

.o1xctu8tq {
  stop-color: var(--svg-color--f8f7fa, #F8F7FA);
}

.o6ackn6vy {
  stop-color: var(--svg-color--a33337, #A33337);
}

.o8-p00v9r {
  stop-color: var(--svg-color--b7a9bb, #B7A9BB);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odr8zlbiv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.413 14.792c.354-.255 1.478-.725 3.14-.563");
}

.og08facuy {
  stop-color: var(--svg-color--7a3f6a, #7A3F6A);
}

.oo3ogkscv {
  stop-color: var(--svg-color--78415c, #78415C);
}

.op8gn6bnt {
  stop-color: var(--svg-color--c3c2c2, #C3C2C2);
  stop-opacity: 0;
}

.orirlba9n {
  stop-color: var(--svg-color--794e51, #794E51);
}

.p9zg-objl {
  stop-color: var(--svg-color--b7e0ed, #B7E0ED);
  stop-opacity: 0;
}

.paruexevs {
  stop-color: var(--svg-color--d7d3db, #D7D3DB);
}

.pew6frnzi {
  stop-color: var(--svg-color--c9c2d1, #C9C2D1);
  stop-opacity: 0;
}

.pi9myibky {
  stop-color: var(--svg-color--d8dfe2, #D8DFE2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmoachbcr {
  d: path("M22.735 19.89H17c-.232 0-.418.2-.375.428c.318 1.722 1.718 2.35 2.461 2.37l1.922-.043c1.425-.047 2.073-.986 2.39-1.875c.17-.476-.193-.88-.663-.88");
}

.q270rhb2n {
  stop-color: var(--svg-color--b0a7b6, #B0A7B6);
}

.q63b76bcm {
  stop-color: var(--svg-color--d1cbd8, #D1CBD8);
  stop-opacity: 0;
}

.q90nxab-j {
  stop-color: var(--svg-color--f7f5f9, #F7F5F9);
  stop-opacity: 0;
}

.qfb_zxbhk {
  fill: var(--svg-color--87838b, #87838B);
  fill-rule: evenodd;
  d: path("M12.555 14.815c-1.511-.273-2.56.224-2.844.457a.5.5 0 1 1-.635-.772c.526-.433 1.878-.99 3.657-.67a.5.5 0 1 1-.178.985");
}

.qfftlvbcs {
  d: path("M23.743 5.573c-.679-.51-1.791-.437-2.296-.297l-1.11 6.61a5.7 5.7 0 0 0 2.485 1.64c1.625-.86 2.125-3.562 2.125-5.078c0-1.515-.297-2.195-1.204-2.875");
}

.qnos2qb2v {
  fill: var(--svg-color--cdcad1, #CDCAD1);
  d: path("m17.68 19.401l.001-.066a1.708 1.708 0 1 0-3.415.066h.55l-.001-.066a1.158 1.158 0 1 1 2.314.066z");
}

.qt2l035us {
  d: path("m15.243 18.175l-.978 2.97a.993.993 0 0 0 .958 1.288h1.448a.996.996 0 0 0 .958-1.288l-.978-2.97c-.21-.693-1.188-.693-1.408 0");
}

.r5fjjab0i {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.947 24.196c-.958 0-1.86-.23-2.616-.634c-.26-.135-.537.163-.374.404a3.56 3.56 0 0 0 2.99 1.634a3.56 3.56 0 0 0 2.99-1.634c.164-.25-.114-.539-.373-.404a5.55 5.55 0 0 1-2.617.634Z");
}

.r73c1xbox {
  stop-color: var(--svg-color--765651, #765651);
  stop-opacity: 0;
}

.r9mw8xbto {
  cx: 11.437px;
  cy: 17.535px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.717px;
  ry: 0.363px;
}

.rlocizbva {
  d: path("m17.68 19.401l.001-.066a1.708 1.708 0 1 0-3.415.066h.55l-.001-.066a1.158 1.158 0 1 1 2.314.066z");
}

.sc0yvsrxt {
  fill: var(--svg-color--000, #000);
  d: path("M19.026 18.476c0-.523.419-.94.941-.94c.523 0 .941.417.941.94a.9.9 0 0 1-.105.433h-1.665a.85.85 0 0 1-.112-.433");
}

.sjitiy62y {
  stop-color: var(--svg-color--b4b3b5, #B4B3B5);
  stop-opacity: 0;
}

.snzwbfsph {
  stop-color: var(--svg-color--734744, #734744);
}

.soldpzbyh {
  stop-color: var(--svg-color--724c4b, #724C4B);
  stop-opacity: 0;
}

.t_fhyk9zs {
  stop-color: var(--svg-color--714c43, #714C43);
}

.t233yurnp {
  stop-color: var(--svg-color--c6c5c6, #C6C5C6);
}

.t2qfweb2m {
  fill: var(--svg-color--252328, #252328);
  d: path("M13.852 17.763c-.488-.86-1.231-1.538-2.83-1.538c-.7 0-1.374.194-1.974.679c-.495.4-.429.911-.046 1.103l1.024.584c1.2-.388 2.526-.44 3.826-.828");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tcpe2_dxj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.844 17.181c.117.157-.127.347-.405.555c-.278.207-.484.354-.6.197c-.117-.156.013-.451.29-.659c.278-.207.598-.249.715-.093");
}

.tehcnqbzy {
  d: path("m15.17 18.271l-1.206 3.13c-.19.643.268 1.287.92 1.287h1.386c.651 0 1.11-.654.92-1.288l-.939-3.129c-.2-.693-.87-.693-1.08 0");
}

.tjn-pbcga {
  stop-color: var(--svg-color--b0a7b6, #B0A7B6);
  stop-opacity: 0;
}

.tujpxbpmf {
  d: path("M19.844 17.181c.117.157-.127.347-.405.555c-.278.207-.484.354-.6.197c-.117-.156.013-.451.29-.659c.278-.207.598-.249.715-.093");
}

.tygkjs-ny {
  stop-color: var(--svg-color--9ca7ab, #9CA7AB);
  stop-opacity: 0;
}

.u_az6f3zk {
  stop-color: var(--svg-color--865f66, #865F66);
}

.u9y3jsbju {
  fill: var(--svg-color--252328, #252328);
  d: path("M18.049 17.763c.489-.86 1.231-1.538 2.83-1.538c.7 0 1.374.194 1.974.679c.495.4.429.911.046 1.103l-1.024.584c-1.2-.388-2.526-.44-3.826-.828");
}

.uj-2_e4rs {
  d: path("M21.305 9.104V5.183c-.86-.172-1.047-.79-2.383-1.125c-1.086-.196-1.594.257-2.617.64v4.625c.663 1.647 2.365 2.619 3.469 3.028c.308.114.66.038.848-.232c.605-.867.683-2.198.683-3.015");
}

.unozt67tp {
  stop-color: var(--svg-color--b4b3b5, #B4B3B5);
}

.vd_1e8b-h {
  d: path("M5.531 7.832c.969-.56 1.946-.448 2.313-.323L9.7 12.54c.126.278.45.757-.591 1.21c-1.1.48-1.704 1.303-1.938 1.768c-.05.099-.165.153-.257.092c-.843-.558-1.763-2.835-2.19-4.092c-.457-1.345-.403-2.986.807-3.685");
}

.vi3uji6ek {
  stop-color: var(--svg-color--603a3a, #603A3A);
  stop-opacity: 0;
}

.vn83tqcbo {
  stop-color: var(--svg-color--ff4f58, #FF4F58);
}

.vq4x1zbbl {
  stop-color: var(--svg-color--917470, #917470);
}

.vtcjkxbtk {
  d: path("M6.038 7.48a5.5 5.5 0 0 1 5.5-5.5h8.906a5.5 5.5 0 0 1 5.5 5.5v3.124H6.038z");
}

.w-amzpbim {
  stop-color: var(--svg-color--d9d6dc, #D9D6DC);
  stop-opacity: 0;
}

.w8g7dlbjf {
  stop-color: var(--svg-color--754341, #754341);
}

.wia9x5b1c {
  stop-color: var(--svg-color--754341, #754341);
  stop-opacity: 0;
}

.ws7rkabdc {
  stop-color: var(--svg-color--684540, #684540);
}

.wz_uy8j0i {
  fill: var(--svg-color--000, #000);
  d: path("M12.875 18.476a.937.937 0 0 0-.941-.94a.937.937 0 0 0-.94.94a.9.9 0 0 0 .104.433h1.665a.9.9 0 0 0 .112-.433");
}

.x6b7fvhjk {
  stop-color: var(--svg-color--e4e3e5, #E4E3E5);
  stop-opacity: 0;
}

.x6t_0e-6t {
  stop-color: var(--svg-color--c9d2d8, #C9D2D8);
}

.xcvhc4axz {
  stop-color: var(--svg-color--80cce7, #80CCE7);
}

.xh84v07wd {
  stop-color: var(--svg-color--b8e1ee, #B8E1EE);
  stop-opacity: 0;
}

.xruv_mbei {
  d: path("M19.967 16.833a1.643 1.643 0 0 1 1.583 2.076h-3.173a1.7 1.7 0 0 1-.06-.433c0-.903.74-1.643 1.65-1.643");
}

.yabgkrbcu {
  d: path("m6.775 21.282l.004.116c.227 5.159 4.256 8.623 9.173 8.623s8.945-3.464 9.172-8.623l.004-.11a.095.095 0 0 1-.076-.09c-.047-.81-.115-2.755-.151-3.969c0-1.687-.05-2.406-1.871-3.218a27 27 0 0 0-.569-.226c-.461-.18-.633-.247-1.236-.614c-.242-.148-.495-.242-.803-.358l-.015-.006a6 6 0 0 0-.356-.113c-.907-.272-2.93-1.046-3.865-3.156c-.075-.17-.338-.18-.423-.014c-1.077 2.102-3.006 2.902-3.887 3.178a7 7 0 0 0-.32.105c-.317.119-.51.235-.757.385a10 10 0 0 1-1.636.795c-1.258.555-2.07 1.523-2.12 3.242a153 153 0 0 1-.199 3.966a.1.1 0 0 1-.069.087");
}

.yace-6bkn {
  stop-color: var(--svg-color--e4e3e5, #E4E3E5);
}

.ybavvpbvb {
  fill: var(--svg-color--c2c0c6, #C2C0C6);
  fill-rule: evenodd;
  d: path("M6.495 19.3c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75H6.87a.375.375 0 0 1-.375-.375");
}

.yg9ra3bzd {
  stop-color: var(--svg-color--b7e0ed, #B7E0ED);
}

.yp5651blu {
  fill: var(--svg-color--f53742, #F53742);
  d: path("M6.038 7.48a5.5 5.5 0 0 1 5.5-5.5h8.906a5.5 5.5 0 0 1 5.5 5.5v3.124H6.038z");
}

.ypxhk30rd {
  stop-color: var(--svg-color--7c4d58, #7C4D58);
}

.yznnuplse {
  d: path("M8.528 5.573c.68-.51 1.791-.437 2.297-.297l1.11 6.61a5.7 5.7 0 0 1-2.485 1.64c-1.625-.86-2.125-3.562-2.125-5.078c0-1.515.297-2.195 1.203-2.875");
}

.z65w2qfou {
  stop-color: var(--svg-color--92736f, #92736F);
  stop-opacity: 0;
}

.zwa0gtbqc {
  stop-color: var(--svg-color--9f7b6e, #9F7B6E);
}

.zxx6y458s {
  stop-color: var(--svg-color--805f56, #805F56);
  stop-opacity: 0;
}

</style>
