<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ifRJAbP)"><path fill="url(#i7hDUrd)" class="jzlt3hbam"/></g><g filter="url(#ilmtOsd)"><path fill="url(#iGH9c9Y)" class="qrfb_bcbk"/></g><path class="j6_dhrc8k"/><path fill="url(#iJL7Vby)" class="c-qvk-bxj"/><path fill="url(#iyibswc)" class="c-qvk-bxj"/><path fill="url(#im1XRjc)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#iGCpIMP)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#iQN3Twd)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#ieMXyLe)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#iGQ2lmc)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#ikXlXce)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#i7goOIs)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#i5ezOSs)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#iOxLv6d)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#i6bZwUN)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#ise5b3b)" clip-rule="evenodd" class="hdm-f6_si"/><g filter="url(#i6Nn6eW)"><path fill="url(#iZu0Ohd)" class="dvlvtp1ae"/></g><g filter="url(#ijI3D5b)"><path fill="url(#iTo2wie)" class="sb37n_b-l"/></g><g filter="url(#iH58IMc)"><path class="ij2tlcbfn"/></g><g filter="url(#iwTzJQd)"><path class="yqytfrbzb"/><path fill="url(#iVcb5Ab)" class="quxn97o8y"/><path fill="url(#iCbktCc)" class="quxn97o8y"/><path fill="url(#i5TcTne)" class="quxn97o8y"/><path fill="url(#i3X1ohd)" class="quxn97o8y"/><path fill="url(#igaXCfd)" class="quxn97o8y"/><path fill="url(#iql3Gcd)" class="quxn97o8y"/></g><g filter="url(#iAHUInc)"><path stroke="url(#iTGP5Gb)" class="m_80iabrj"/></g><path class="jojofbcnr"/><g filter="url(#iVM8upZ)"><path class="yxuku-bjv"/></g><g filter="url(#iZ0hevb)"><path class="poyosobjd"/></g><path class="pu8-ecbbp"/><path fill="url(#ii45ZWc)" class="x473prbqk"/><path class="y2w6zwvih"/><g filter="url(#iIfVdma)"><path class="tqlbelb5c"/><path fill="url(#iqY6bxb)" class="djqsox1gi"/></g><g filter="url(#iqhonKO)"><path fill="url(#its1NMc)" class="b35v_52zq"/></g><path class="h4wud4aqj"/><path fill="url(#iLKqVYc)" class="y3x9krbaf"/><path class="jpqz_bbia"/><g filter="url(#imFzMoc)"><path fill="url(#ivsx89U)" class="jnvredchk"/></g><g filter="url(#il4vezd)"><ellipse transform="rotate(-27.914 11.437 17.58)" class="twscsqg2e"/><ellipse fill="url(#imJKevd)" transform="rotate(-27.914 11.437 17.58)" class="y0-ze-bdx"/></g><g filter="url(#izickkc)"><path fill="url(#i88vPNQ)" class="fhqtnvq7p"/><path fill="url(#iFCQbvb)" class="fhqtnvq7p"/><path fill="url(#iqzv63c)" class="fhqtnvq7p"/><path fill="url(#inwG2ze)" class="fhqtnvq7p"/></g><g filter="url(#iaBWFfe)"><path clip-rule="evenodd" class="b2r8k7flo"/></g><g filter="url(#i8BlRyl)"><path clip-rule="evenodd" class="s61psh5pa"/></g><g filter="url(#ixZ4kru)"><path clip-rule="evenodd" class="semymtb9k"/><path fill="url(#iTHSi8v)" clip-rule="evenodd" class="zeler-bcd"/><path fill="url(#itopFvc)" clip-rule="evenodd" class="zeler-bcd"/><path fill="url(#i9gg5Lc)" clip-rule="evenodd" class="zeler-bcd"/></g><g filter="url(#iBn56Xc)"><path clip-rule="evenodd" class="hsqqlrbqm"/><path fill="url(#ipZTdEi)" clip-rule="evenodd" class="t880k8bxx"/><path fill="url(#iMuzt2b)" clip-rule="evenodd" class="t880k8bxx"/></g><g filter="url(#iiIh7yd)"><path class="h3k4q1bqa"/><path fill="url(#i8ISCgc)" class="da2kl3hde"/><path fill="url(#iMu5AWM)" class="da2kl3hde"/></g><path fill="url(#imD8Xgb)" class="da2kl3hde"/><g filter="url(#ixEIXJb)"><path class="nk_szybzw"/><path fill="url(#iYSUHre)" class="ocica9bdm"/><path fill="url(#i0KlXdb)" class="ocica9bdm"/></g><g filter="url(#iZ6Upkt)"><path class="bwojmyq_a"/><path fill="url(#itpDx5f)" class="wb-iyinxg"/></g><g filter="url(#iXqmmWd)"><path stroke="url(#idIIa7c)" class="w1xz_gb9i"/></g><g filter="url(#iQOX9Qf)"><path stroke="url(#i711oVd)" class="whp-6pbsd"/></g><g filter="url(#ipZ2wNb)"><path fill="url(#iAMs9Bb)" class="lq_yczzut"/><path fill="url(#iXcJqHV)" class="lq_yczzut"/></g><g filter="url(#ineJnbd)"><path fill="url(#i1Nx3we)" class="r0o24_-xm"/></g><g filter="url(#iwda9Rc)"><path fill="url(#ipd6AWc)" class="ish1_actf"/><path fill="url(#icAzjDg)" class="ish1_actf"/><path fill="url(#iO4ydXb)" class="ish1_actf"/></g><g filter="url(#iSz0ZXb)"><path fill="url(#iaDS9cb)" class="y_2jelukn"/></g><g filter="url(#iQ1lete)"><path fill="url(#i8Dv9in)" class="stacowb_v"/><path fill="url(#iUCoidd)" class="stacowb_v"/><path fill="url(#iEv0fwb)" class="stacowb_v"/></g><g filter="url(#i1uX2Ce)"><path fill="url(#ieZYL7c)" class="cvkbl7bbe"/><path fill="url(#iXmJGcM)" class="cvkbl7bbe"/></g><defs><radialGradient id="i7hDUrd" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.015 17.635)scale(4.54255 3.9894)" gradientUnits="userSpaceOnUse"><stop class="ownpgmboe"/><stop offset="1" class="d9k5ku1ib"/></radialGradient><radialGradient id="iGH9c9Y" cx="0" cy="0" r="1" gradientTransform="rotate(49.526 -18.276 14.519)scale(3.89961)" gradientUnits="userSpaceOnUse"><stop class="dhkp6ccne"/><stop offset="1" class="otnesi0ny"/></radialGradient><radialGradient id="iJL7Vby" cx="0" cy="0" r="1" gradientTransform="matrix(-15.1875 0 0 -10.125 21.381 6.337)" gradientUnits="userSpaceOnUse"><stop offset=".698" class="mzycncwxb"/><stop offset="1" class="o6ackn6vy"/></radialGradient><radialGradient id="iyibswc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6875 4.6875 -5.60964 -8.00307 25.475 4.275)" gradientUnits="userSpaceOnUse"><stop class="vn83tqcbo"/><stop offset="1" class="c47ug_iov"/></radialGradient><radialGradient id="im1XRjc" cx="0" cy="0" r="1" gradientTransform="rotate(149.208 8.394 11.1)scale(14.0258 18.7732)" gradientUnits="userSpaceOnUse"><stop class="djd_fj9xn"/><stop offset=".891" class="b75t78bji"/></radialGradient><radialGradient id="iQN3Twd" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.1368 -11.4691 0 15.942 17.841)" gradientUnits="userSpaceOnUse"><stop offset=".77" class="me1dg36fk"/><stop offset="1" class="qbhxyqjsm"/></radialGradient><radialGradient id="ieMXyLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.1368 -10.4847 0 15.935 17.838)" gradientUnits="userSpaceOnUse"><stop offset=".962" class="me1dg36fk"/><stop offset="1" class="x0h7khzay"/></radialGradient><radialGradient id="iGQ2lmc" cx="0" cy="0" r="1" gradientTransform="rotate(122.957 6.407 11.372)scale(3.38915 3.40898)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="yf61h4boy"/><stop offset="1" class="vi0ldn3_z"/></radialGradient><radialGradient id="ikXlXce" cx="0" cy="0" r="1" gradientTransform="rotate(36.703 -6.987 33.45)scale(3.21564 1.46649)" gradientUnits="userSpaceOnUse"><stop offset=".824" class="r8t5-cclp"/><stop offset="1" class="pgvxl74iv"/></radialGradient><radialGradient id="i7goOIs" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 2.03125 -.39841 .7294 22.7 13.745)" gradientUnits="userSpaceOnUse"><stop offset=".029" class="y6fkcvbrv"/><stop offset="1" class="nfjm-7uhl"/></radialGradient><radialGradient id="i5ezOSs" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1707 1.74062 -.74442 -1.7837 11.786 11.435)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="qsf2zeb3k"/><stop offset="1" class="w156j0bsh"/></radialGradient><radialGradient id="iOxLv6d" cx="0" cy="0" r="1" gradientTransform="matrix(10.65625 4.3125 -4.74072 11.71439 14.09 20.432)" gradientUnits="userSpaceOnUse"><stop offset=".875" class="qmoocornp"/><stop offset=".979" class="l9wo6zb8f"/></radialGradient><radialGradient id="i6bZwUN" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1578 -2.97711 2.70485 -1.05191 12.49 17.485)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="efkpbfb_e"/><stop offset="1" class="ivf_koo1b"/></radialGradient><radialGradient id="ise5b3b" cx="0" cy="0" r="1" gradientTransform="matrix(1.87449 -2.38905 2.31944 1.81987 20.631 17.448)" gradientUnits="userSpaceOnUse"><stop offset=".056" class="ry3pes94c"/><stop offset="1" class="h88xu6bej"/></radialGradient><radialGradient id="iZu0Ohd" cx="0" cy="0" r="1" gradientTransform="matrix(5.1875 1.28125 -1.21262 4.90965 17.788 21.119)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="xgquw9bbb"/><stop offset="1" class="mitzpmtki"/></radialGradient><radialGradient id="iTo2wie" cx="0" cy="0" r="1" gradientTransform="rotate(101.083 -2.847 15.056)scale(3.08885 4.56981)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="jmzr2xtue"/><stop offset="1" class="vv_rcrb7h"/></radialGradient><radialGradient id="iCbktCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21875 5.01769 0 15.947 22.573)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="nzxiu0rqt"/><stop offset="1" class="d33t2ybal"/></radialGradient><radialGradient id="i5TcTne" cx="0" cy="0" r="1" gradientTransform="matrix(.96093 1.53907 -.79747 .4979 17.52 20.018)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="eu764gb8n"/><stop offset="1" class="ffwwokb9r"/></radialGradient><radialGradient id="i3X1ohd" cx="0" cy="0" r="1" gradientTransform="matrix(-.85938 0 0 -.28125 16.888 21.307)" gradientUnits="userSpaceOnUse"><stop class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="iql3Gcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.67187 2.46699 0 15.947 20.869)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="tq-c03ytv"/><stop offset="1" class="ylir1ob0l"/></radialGradient><radialGradient id="ii45ZWc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23439 1.98436 -2.08903 -1.2995 20.789 17.292)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="kz8v_2b0u"/><stop offset="1" class="t_fhyk9zs"/></radialGradient><radialGradient id="iqY6bxb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.157 4.17)scale(.69518 .9571)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLKqVYc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23439 1.98437 -2.08904 -1.2995 12.763 17.292)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="kz8v_2b0u"/><stop offset="1" class="t_fhyk9zs"/></radialGradient><radialGradient id="imJKevd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01423 -.90865 1.09224 -.0171 11.41 18.16)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFCQbvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.1076 1.90987 -2.1901 -.12338 10.615 4.891)" gradientUnits="userSpaceOnUse"><stop class="o-gllcbpi"/><stop offset="1" class="op8gn6bnt"/></radialGradient><radialGradient id="iqzv63c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23266 0 0 -5.95693 7.091 18.825)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="c3098ubep"/><stop offset=".808" class="ixxpbv8hf"/></radialGradient><radialGradient id="inwG2ze" cx="0" cy="0" r="1" gradientTransform="rotate(118.957 8.488 15.254)scale(5.35726 1.55455)" gradientUnits="userSpaceOnUse"><stop class="paruexevs"/><stop offset="1" class="lcus7p0ww"/></radialGradient><radialGradient id="iTHSi8v" cx="0" cy="0" r="1" gradientTransform="rotate(131.743 -.221 11.58)scale(.68059 .35127)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="egvfrgbew"/><stop offset="1" class="i6zk_phor"/></radialGradient><radialGradient id="i9gg5Lc" cx="0" cy="0" r="1" gradientTransform="matrix(.5337 0 0 .67969 6.495 19.374)" gradientUnits="userSpaceOnUse"><stop class="du3zqdbas"/><stop offset="1" class="eo5th8odz"/></radialGradient><radialGradient id="ipZTdEi" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 -.09375 .13594 1.05353 23.6 19.51)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="yace-6bkn"/><stop offset="1" class="x6b7fvhjk"/></radialGradient><radialGradient id="i8ISCgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.80005 -1.45312 .28898 -.1591 17.68 19.025)" gradientUnits="userSpaceOnUse"><stop class="pi9myibky"/><stop offset="1" class="a4r8facys"/></radialGradient><radialGradient id="iMu5AWM" cx="0" cy="0" r="1" gradientTransform="matrix(.57813 -1.10938 .29816 .15538 14.678 19.181)" gradientUnits="userSpaceOnUse"><stop class="x6t_0e-6t"/><stop offset="1" class="n01394_5x"/></radialGradient><radialGradient id="imD8Xgb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96021 -1.0123 1.0168 -1.96892 16.225 19.572)" gradientUnits="userSpaceOnUse"><stop offset=".77" class="tygkjs-ny"/><stop offset=".937" class="lqfy3p-zi"/></radialGradient><radialGradient id="iAMs9Bb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.63619 -5.40116 1.4488 -.70713 8.006 12.854)" gradientUnits="userSpaceOnUse"><stop class="cvqywpbya"/><stop offset="1" class="do75vybld"/></radialGradient><radialGradient id="iXcJqHV" cx="0" cy="0" r="1" gradientTransform="matrix(.55304 6.50969 -3.32228 .28225 6.553 8.307)" gradientUnits="userSpaceOnUse"><stop offset=".505" class="tjn-pbcga"/><stop offset="1" class="q270rhb2n"/></radialGradient><radialGradient id="i1Nx3we" cx="0" cy="0" r="1" gradientTransform="matrix(5.54388 1.16889 -2.00192 9.49486 22.68 11.48)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="o0zfjub8g"/><stop offset=".932" class="emarm55as"/></radialGradient><radialGradient id="ipd6AWc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93356 -6.50176 2.0863 -.62045 10.645 11.72)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="hffkdxxqc"/><stop offset="1" class="pew6frnzi"/></radialGradient><radialGradient id="icAzjDg" cx="0" cy="0" r="1" gradientTransform="rotate(162.165 4.705 5.463)scale(3.24962 5.81408)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="d2xfa78kb"/><stop offset="1" class="bemgdwb7k"/></radialGradient><radialGradient id="iO4ydXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.39841 -3.90671 0 9.63 8.173)" gradientUnits="userSpaceOnUse"><stop offset=".817" class="h13c6fb3k"/><stop offset="1" class="k-7dzim-i"/></radialGradient><radialGradient id="iaDS9cb" cx="0" cy="0" r="1" gradientTransform="rotate(32.247 -3.98 40.286)scale(5.50541 6.13649)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="q63b76bcm"/><stop offset="1" class="l_nupdb1h"/></radialGradient><radialGradient id="i8Dv9in" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.34375 4.69757 0 15.819 8.618)" gradientUnits="userSpaceOnUse"><stop offset=".357" class="ea88qbbkv"/><stop offset="1" class="l_hht1tza"/></radialGradient><radialGradient id="iEv0fwb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03127 5.6875 -4.70513 -1.68042 13.663 5.806)" gradientUnits="userSpaceOnUse"><stop offset=".544" class="o8-p00v9r"/><stop offset="1" class="kpi-j7bnf"/></radialGradient><radialGradient id="ieZYL7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.78125 3.21875 0 19.847 8.931)" gradientUnits="userSpaceOnUse"><stop class="gh7w8ccdd"/><stop offset="1" class="q90nxab-j"/></radialGradient><radialGradient id="iXmJGcM" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 2.25 -3.86674 -5.58532 19.756 7.431)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="ju711jbwd"/><stop offset="1" class="ep--azv6o"/></radialGradient><filter id="ifRJAbP" width="6.033" height="6.033" x="22.017" y="15.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.129412 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/></filter><filter id="ilmtOsd" width="6.033" height="5.933" x="3.945" y="16.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/></filter><filter id="i6Nn6eW" width="8.322" height="4.297" x="15.869" y="19.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".375"/></filter><filter id="ijI3D5b" width="8.322" height="4.297" x="6.962" y="19.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".375"/></filter><filter id="iH58IMc" width="4.312" height="5.936" x="13.421" y="17.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".25"/></filter><filter id="iwTzJQd" width="3.555" height="4.778" x="14.22" y="17.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.160784 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/></filter><filter id="iAHUInc" width="6.478" height="2.472" x="12.708" y="23.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".05"/></filter><filter id="iVM8upZ" width="5.356" height="2.366" x="18.049" y="16.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0588235 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/></filter><filter id="iZ0hevb" width="5.356" height="2.366" x="8.696" y="16.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0588235 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/></filter><filter id="iIfVdma" width="1.278" height="1.112" x="18.696" y="17.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".05"/></filter><filter id="iqhonKO" width="1.303" height="1.343" x="20.326" y="17.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".1"/></filter><filter id="imFzMoc" width="1.477" height="1.577" x="12.155" y="17.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".1"/></filter><filter id="il4vezd" width="1.511" height="1.128" x="10.681" y="17.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".05"/></filter><filter id="izickkc" width="25.121" height="17.787" x="3.515" y="3.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.615686 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/></filter><filter id="iaBWFfe" width="4.251" height="1.951" x="8.893" y="13.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.364706 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/></filter><filter id="i8BlRyl" width="4.251" height="1.951" x="18.821" y="13.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.337255 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/></filter><filter id="ixZ4kru" width="2.77" height=".9" x="6.495" y="18.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.392157 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/></filter><filter id="iBn56Xc" width="2.97" height=".9" x="22.788" y="18.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.435294 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/></filter><filter id="iiIh7yd" width="3.466" height="1.925" x="14.265" y="17.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.447059 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/></filter><filter id="ixEIXJb" width="6.862" height="2.837" x="16.957" y="18.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".02" dy="-.02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.776471 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.937255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24204" result="effect2_innerShadow_3987_24204"/></filter><filter id="iZ6Upkt" width="6.862" height="2.837" x="8.05" y="18.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".02" dy="-.02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.776471 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24204"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.937255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24204" result="effect2_innerShadow_3987_24204"/></filter><filter id="iXqmmWd" width="3.891" height="1.346" x="9.038" y="13.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".125"/></filter><filter id="iQOX9Qf" width="3.891" height="1.346" x="19.032" y="13.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".125"/></filter><filter id="ipZ2wNb" width="6.389" height="9.227" x="3.959" y="6.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".25"/></filter><filter id="ineJnbd" width="6.538" height="8.968" x="21.546" y="6.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".25"/></filter><filter id="iwda9Rc" width="5.609" height="9.353" x="6.825" y="4.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".25"/></filter><filter id="iSz0ZXb" width="5.609" height="9.353" x="19.837" y="4.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".25"/></filter><filter id="iQ1lete" width="6.2" height="9.592" x="9.977" y="3.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".3"/></filter><filter id="i1uX2Ce" width="6.2" height="9.592" x="15.705" y="3.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24204" stdDeviation=".3"/></filter><linearGradient id="iGCpIMP" x1="6.762" x2="9.528" y1="21.276" y2="21.276" gradientUnits="userSpaceOnUse"><stop offset=".13" class="z8u448bed"/><stop offset="1" class="y_-3291qj"/></linearGradient><linearGradient id="iVcb5Ab" x1="17.675" x2="15.947" y1="21.026" y2="21.12" gradientUnits="userSpaceOnUse"><stop offset=".142" class="mc3aerbdu"/><stop offset="1" class="p2xodcbta"/></linearGradient><linearGradient id="igaXCfd" x1="14.35" x2="15.144" y1="20.089" y2="20.377" gradientUnits="userSpaceOnUse"><stop class="cr2tqdo3r"/><stop offset="1" class="mslb6tbmm"/></linearGradient><linearGradient id="iTGP5Gb" x1="14.605" x2="15.438" y1="25.522" y2="23.918" gradientUnits="userSpaceOnUse"><stop class="ar8tnccah"/><stop offset="1" class="y6zyajbih"/></linearGradient><linearGradient id="its1NMc" x1="21.394" x2="20.817" y1="17.855" y2="18.21" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivsx89U" x1="13.305" x2="12.728" y1="17.855" y2="18.21" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i88vPNQ" x1="26.288" x2="10.475" y1="14.712" y2="14.712" gradientUnits="userSpaceOnUse"><stop class="o1xctu8tq"/><stop offset="1" class="e3tydgbfn"/></linearGradient><linearGradient id="itopFvc" x1="7.879" x2="7.879" y1="18.943" y2="19.165" gradientUnits="userSpaceOnUse"><stop class="unozt67tp"/><stop offset="1" class="sjitiy62y"/></linearGradient><linearGradient id="iMuzt2b" x1="24.172" x2="24.172" y1="18.97" y2="19.169" gradientUnits="userSpaceOnUse"><stop class="t233yurnp"/><stop offset="1" class="dte4ogbdr"/></linearGradient><linearGradient id="iYSUHre" x1="21.35" x2="21.35" y1="21.751" y2="20.353" gradientUnits="userSpaceOnUse"><stop offset=".006" class="xcvhc4axz"/><stop offset="1" class="fl8h_cbee"/></linearGradient><linearGradient id="i0KlXdb" x1="18.795" x2="20.686" y1="19.962" y2="20.697" gradientUnits="userSpaceOnUse"><stop class="xh84v07wd"/><stop offset=".141" class="akeuncc3p"/><stop offset=".868" class="akeuncc3p"/><stop offset="1" class="xh84v07wd"/></linearGradient><linearGradient id="itpDx5f" x1="12.655" x2="10.655" y1="20.689" y2="19.845" gradientUnits="userSpaceOnUse"><stop class="p9zg-objl"/><stop offset=".141" class="yg9ra3bzd"/><stop offset=".868" class="yg9ra3bzd"/><stop offset="1" class="p9zg-objl"/></linearGradient><linearGradient id="idIIa7c" x1="12.553" x2="9.154" y1="14.241" y2="15.144" gradientUnits="userSpaceOnUse"><stop offset=".166" class="g8eaedcck"/><stop offset="1" class="jnjw33b1s"/></linearGradient><linearGradient id="i711oVd" x1="22.548" x2="18.399" y1="14.762" y2="14.464" gradientUnits="userSpaceOnUse"><stop offset=".166" class="g8eaedcck"/><stop offset="1" class="jnjw33b1s"/></linearGradient><linearGradient id="iUCoidd" x1="10.288" x2="13.073" y1="8.337" y2="8.337" gradientUnits="userSpaceOnUse"><stop class="h243fe46z"/><stop offset="1" class="w-amzpbim"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mrs-claus-dark" /></template>
<style>
.a4r8facys {
  stop-color: var(--svg-color--d8dfe2, #D8DFE2);
  stop-opacity: 0;
}

.akeuncc3p {
  stop-color: var(--svg-color--b8e1ee, #B8E1EE);
}

.ar8tnccah {
  stop-color: var(--svg-color--534245, #534245);
}

.b2r8k7flo {
  fill: var(--svg-color--7e7c80, #7E7C80);
  fill-rule: evenodd;
  d: path("M12.555 14.86c-1.511-.273-2.56.224-2.844.457a.5.5 0 1 1-.635-.772c.526-.433 1.878-.99 3.657-.669a.5.5 0 1 1-.178.984");
}

.b35v_52zq {
  d: path("M21.429 18.304a1.54 1.54 0 0 0-.425-.85l-.478.523l.216.42z");
}

.b75t78bji {
  stop-color: var(--svg-color--3e2130, #3E2130);
}

.bemgdwb7k {
  stop-color: var(--svg-color--b4b0b8, #B4B0B8);
}

.bwojmyq_a {
  fill: var(--svg-color--85d7ed, #85D7ED);
  d: path("M8.776 18.955h5.735c.232 0 .418.198.376.427c-.319 1.722-1.718 2.35-2.462 2.37l-1.922-.044c-1.425-.046-2.073-.985-2.39-1.875c-.17-.475.194-.878.663-.878");
}

.c-qvk-bxj {
  d: path("M6.038 7.525a5.5 5.5 0 0 1 5.5-5.5h8.906a5.5 5.5 0 0 1 5.5 5.5v3.125H6.038z");
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.c47ug_iov {
  stop-color: var(--svg-color--ff4f58, #FF4F58);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cr2tqdo3r {
  stop-color: var(--svg-color--352626, #352626);
}

.cvkbl7bbe {
  d: path("M21.305 9.15V5.228c-.86-.172-1.047-.79-2.383-1.125c-1.086-.195-1.594.258-2.617.64v4.625c.663 1.648 2.365 2.62 3.469 3.028c.308.115.66.039.848-.231c.605-.868.683-2.199.683-3.015");
}

.cvqywpbya {
  stop-color: var(--svg-color--b8b5bb, #B8B5BB);
}

.d2xfa78kb {
  stop-color: var(--svg-color--b4b0b8, #B4B0B8);
  stop-opacity: 0;
}

.d33t2ybal {
  stop-color: var(--svg-color--3f2230, #3F2230);
  stop-opacity: 0;
}

.d9k5ku1ib {
  stop-color: var(--svg-color--4b3133, #4B3133);
}

.da2kl3hde {
  d: path("m17.68 19.447l.001-.067a1.708 1.708 0 1 0-3.415.067h.55l-.001-.067a1.158 1.158 0 1 1 2.314.067z");
}

.dhkp6ccne {
  stop-color: var(--svg-color--352222, #352222);
}

.djd_fj9xn {
  stop-color: var(--svg-color--543735, #543735);
}

.djqsox1gi {
  d: path("M19.844 17.227c.117.156-.127.346-.405.554s-.484.354-.6.198c-.117-.157.013-.452.29-.66c.278-.207.598-.249.715-.092");
}

.do75vybld {
  stop-color: var(--svg-color--b8b5bb, #B8B5BB);
  stop-opacity: 0;
}

.dte4ogbdr {
  stop-color: var(--svg-color--c7c6ca, #C7C6CA);
  stop-opacity: 0;
}

.du3zqdbas {
  stop-color: var(--svg-color--828084, #828084);
}

.dvlvtp1ae {
  d: path("M22.735 19.936H17c-.232 0-.418.199-.375.427c.318 1.723 1.718 2.35 2.461 2.37l1.922-.043c1.425-.047 2.073-.986 2.39-1.875c.17-.476-.193-.879-.663-.879");
}

.e3tydgbfn {
  stop-color: var(--svg-color--bab9bc, #BAB9BC);
}

.ea88qbbkv {
  stop-color: var(--svg-color--f0edf4, #F0EDF4);
}

.efkpbfb_e {
  stop-color: var(--svg-color--351f26, #351F26);
}

.egvfrgbew {
  stop-color: var(--svg-color--6f7587, #6F7587);
}

.emarm55as {
  stop-color: var(--svg-color--dbd9dd, #DBD9DD);
}

.eo5th8odz {
  stop-color: var(--svg-color--828084, #828084);
  stop-opacity: 0;
}

.ep--azv6o {
  stop-color: var(--svg-color--ccc9d0, #CCC9D0);
}

.eu764gb8n {
  stop-color: var(--svg-color--311d1e, #311D1E);
}

.ffwwokb9r {
  stop-color: var(--svg-color--48302f, #48302F);
  stop-opacity: 0;
}

.fhqtnvq7p {
  d: path("M6.744 21.33a.095.095 0 0 0 .1-.09c.05-.81.162-2.752.198-3.965c.052-1.72.863-2.688 2.12-3.242a10 10 0 0 0 1.637-.796c.247-.15.44-.266.757-.384q.129-.047.32-.105c.88-.277 2.81-1.076 3.887-3.179c.085-.166.348-.156.423.014c.935 2.11 2.958 2.885 3.864 3.156q.216.064.356.114c.316.118.573.213.82.363c.799.487.839.445 1.804.84c1.82.813 1.87 1.531 1.87 3.219c.037 1.213.105 3.158.152 3.97a.094.094 0 0 0 .1.09c1.223-.08 1.912-1.706 2.106-2.529l.785-2.969c.4-1.586.55-2.42.362-3.098c-.173-.625-.655-1.313-.833-1.527c0-.072.022-.207.05-.383c.096-.581.128-1.362-.186-2.07c-.503-1.05-1.258-1.312-1.781-1.46c-.477-.071-.764-.257-1.016-.782c-.992-1.793-2.234-1.695-2.805-1.695c-.461.054-.773.054-1.289-.297c-1.312-1.094-2.637-.703-3.423-.328c-.628.3-1.016.343-1.131.328c-.116.015-.505-.028-1.137-.328c-.789-.375-2.059-.797-3.45.328c-.46.398-.701.396-1.189.338c-.393-.046-1.97-.178-2.966 1.615c-.253.525-.717.62-.949.625c-.437.031-1.436.356-1.941 1.406c-.315.708-.225 1.746-.13 2.328c.029.176.05.31.05.383c-.178.214-.528.875-.702 1.5c-.188.679.088 2.341.308 3.117l.79 2.969c.195.823.842 2.445 2.07 2.524");
}

.fl8h_cbee {
  stop-color: var(--svg-color--80cce7, #80CCE7);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g8eaedcck {
  stop-color: var(--svg-color--97949a, #97949A);
}

.gh7w8ccdd {
  stop-color: var(--svg-color--f7f5f9, #F7F5F9);
}

.h13c6fb3k {
  stop-color: var(--svg-color--b39cb2, #B39CB2);
  stop-opacity: 0;
}

.h243fe46z {
  stop-color: var(--svg-color--b6b4b8, #B6B4B8);
}

.h3k4q1bqa {
  fill: var(--svg-color--cdcad1, #CDCAD1);
  d: path("m17.68 19.447l.001-.067a1.708 1.708 0 1 0-3.415.067h.55l-.001-.067a1.158 1.158 0 1 1 2.314.067z");
}

.h4wud4aqj {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.553 16.378a2.57 2.57 0 0 0-2.494 1.95a.505.505 0 0 0 .493.626h4.106c.262 0 .47-.239.418-.5a2.58 2.58 0 0 0-2.523-2.076");
}

.h88xu6bej {
  stop-color: var(--svg-color--422729, #422729);
  stop-opacity: 0;
}

.hdm-f6_si {
  fill-rule: evenodd;
  d: path("M6.762 21.33v.023c.228 5.158 4.256 8.622 9.173 8.622s8.945-3.464 9.172-8.622l.001-.027a.1.1 0 0 1-.056-.082c-.047-.81-.115-2.756-.151-3.97c0-1.687-.05-2.406-1.871-3.218a27 27 0 0 0-.569-.226c-.462-.18-.633-.247-1.236-.614c-.242-.147-.495-.242-.803-.358l-.016-.005c-.092-.035-.212-.07-.355-.114c-.907-.271-2.93-1.045-3.865-3.156c-.075-.17-.338-.18-.423-.014c-1.077 2.103-3.006 2.902-3.887 3.178q-.191.059-.32.106a4 4 0 0 0-.757.384a10 10 0 0 1-1.636.796c-1.258.554-2.07 1.522-2.12 3.242a153 153 0 0 1-.199 3.965a.095.095 0 0 1-.082.09");
}

.hffkdxxqc {
  stop-color: var(--svg-color--c9c2d1, #C9C2D1);
}

.hsqqlrbqm {
  fill: var(--svg-color--c7c7cd, #C7C7CD);
  fill-rule: evenodd;
  d: path("M22.788 19.345c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75h-2.02a.375.375 0 0 1-.375-.375");
}

.i6zk_phor {
  stop-color: var(--svg-color--8d889f, #8D889F);
  stop-opacity: 0;
}

.ij2tlcbfn {
  fill: var(--svg-color--321e25, #321E25);
  d: path("m15.17 18.317l-1.206 3.129c-.19.643.268 1.287.92 1.287h1.386c.651 0 1.11-.654.92-1.287l-.939-3.13c-.2-.693-.87-.693-1.08 0");
}

.ish1_actf {
  d: path("M8.528 5.619c.68-.51 1.791-.438 2.297-.297l1.11 6.609a5.7 5.7 0 0 1-2.485 1.64c-1.625-.859-2.125-3.562-2.125-5.077s.297-2.196 1.203-2.875");
}

.ivf_koo1b {
  stop-color: var(--svg-color--351f26, #351F26);
  stop-opacity: 0;
}

.ixxpbv8hf {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
  stop-opacity: 0;
}

.j6_dhrc8k {
  fill: var(--svg-color--f53742, #F53742);
  d: path("M6.038 7.525a5.5 5.5 0 0 1 5.5-5.5h8.906a5.5 5.5 0 0 1 5.5 5.5v3.125H6.038z");
}

.jmzr2xtue {
  stop-color: var(--svg-color--352228, #352228);
}

.jnjw33b1s {
  stop-color: var(--svg-color--97949a, #97949A);
  stop-opacity: 0;
}

.jnvredchk {
  d: path("M13.433 18.327c0-.53-.431-.884-.548-.99l-.53.512l.326.664z");
}

.jojofbcnr {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M15.947 24.242c-.958 0-1.86-.231-2.616-.635c-.26-.134-.537.164-.374.404a3.56 3.56 0 0 0 2.99 1.634a3.56 3.56 0 0 0 2.99-1.634c.164-.25-.114-.538-.373-.404a5.55 5.55 0 0 1-2.617.635");
}

.jpqz_bbia {
  fill: var(--svg-color--000, #000);
  d: path("M12.875 18.521a.937.937 0 0 0-.941-.94a.937.937 0 0 0-.94.94a.9.9 0 0 0 .104.433h1.665a.9.9 0 0 0 .112-.433");
}

.ju711jbwd {
  stop-color: var(--svg-color--ccc9d0, #CCC9D0);
  stop-opacity: 0;
}

.jzlt3hbam {
  d: path("M24.984 21.964a2.966 2.966 0 1 0 0-5.933a2.966 2.966 0 0 0 0 5.933");
}

.k-7dzim-i {
  stop-color: var(--svg-color--b39cb2, #B39CB2);
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

.l9wo6zb8f {
  stop-color: var(--svg-color--645251, #645251);
}

.lcus7p0ww {
  stop-color: var(--svg-color--faf9fc, #FAF9FC);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lq_yczzut {
  d: path("M5.531 7.877c.969-.56 1.946-.448 2.313-.323l1.856 5.03c.126.279.45.757-.591 1.211c-1.1.48-1.704 1.302-1.938 1.768c-.05.098-.165.152-.257.09c-.843-.557-1.763-2.834-2.19-4.09c-.457-1.346-.403-2.986.807-3.686");
}

.lqfy3p-zi {
  stop-color: var(--svg-color--7a8488, #7A8488);
}

.m_80iabrj {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.947 24.242c-.958 0-1.86-.231-2.616-.635c-.26-.134-.537.164-.374.404a3.56 3.56 0 0 0 2.99 1.634a3.56 3.56 0 0 0 2.99-1.634c.164-.25-.114-.538-.373-.404a5.55 5.55 0 0 1-2.617.635Z");
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mc3aerbdu {
  stop-color: var(--svg-color--665554, #665554);
}

.me1dg36fk {
  stop-color: var(--svg-color--432843, #432843);
  stop-opacity: 0;
}

.mitzpmtki {
  stop-color: var(--svg-color--3c2324, #3C2324);
  stop-opacity: 0;
}

.mslb6tbmm {
  stop-color: var(--svg-color--352626, #352626);
  stop-opacity: 0;
}

.mzycncwxb {
  stop-color: var(--svg-color--a33337, #A33337);
  stop-opacity: 0;
}

.n01394_5x {
  stop-color: var(--svg-color--c9d2d8, #C9D2D8);
  stop-opacity: 0;
}

.nfjm-7uhl {
  stop-color: var(--svg-color--311b1e, #311B1E);
  stop-opacity: 0;
}

.nk_szybzw {
  fill: var(--svg-color--85dbf1, #85DBF1);
  d: path("M23.093 18.955h-5.735c-.232 0-.418.198-.375.427c.318 1.722 1.717 2.35 2.461 2.37l1.922-.044c1.425-.046 2.073-.985 2.39-1.875c.17-.475-.193-.878-.663-.878");
}

.nzxiu0rqt {
  stop-color: var(--svg-color--3f2230, #3F2230);
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

.ocica9bdm {
  d: path("M23.093 18.955h-5.735c-.232 0-.418.198-.375.427c.318 1.722 1.717 2.35 2.461 2.37l1.922-.044c1.425-.046 2.073-.985 2.39-1.875c.17-.475-.193-.878-.663-.878");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op8gn6bnt {
  stop-color: var(--svg-color--c3c2c2, #C3C2C2);
  stop-opacity: 0;
}

.otnesi0ny {
  stop-color: var(--svg-color--351c2d, #351C2D);
}

.ownpgmboe {
  stop-color: var(--svg-color--654f4d, #654F4D);
}

.p2xodcbta {
  stop-color: var(--svg-color--665554, #665554);
  stop-opacity: 0;
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

.pgvxl74iv {
  stop-color: var(--svg-color--372023, #372023);
  stop-opacity: 0;
}

.pi9myibky {
  stop-color: var(--svg-color--d8dfe2, #D8DFE2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poyosobjd {
  fill: var(--svg-color--252328, #252328);
  d: path("M13.852 17.808c-.488-.859-1.231-1.538-2.83-1.538c-.7 0-1.374.194-1.974.68c-.495.399-.429.91-.046 1.102l1.024.584c1.2-.387 2.526-.44 3.826-.828");
}

.pu8-ecbbp {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.348 16.378c1.202 0 2.218.83 2.494 1.95a.505.505 0 0 1-.493.626h-4.106a.424.424 0 0 1-.418-.5a2.57 2.57 0 0 1 2.523-2.076");
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

.qbhxyqjsm {
  stop-color: var(--svg-color--432843, #432843);
}

.qmoocornp {
  stop-color: var(--svg-color--4d3036, #4D3036);
  stop-opacity: 0;
}

.qrfb_bcbk {
  d: path("M6.911 21.964a2.966 2.966 0 1 0 0-5.933a2.966 2.966 0 0 0 0 5.933");
}

.qsf2zeb3k {
  stop-color: var(--svg-color--392225, #392225);
}

.quxn97o8y {
  d: path("m15.243 18.22l-.978 2.97a.992.992 0 0 0 .958 1.288h1.448a.996.996 0 0 0 .958-1.287l-.978-2.97c-.21-.694-1.188-.694-1.408 0");
}

.r0o24_-xm {
  d: path("M26.48 7.877c-.998-.56-2.004-.448-2.383-.323l-1.912 5.03c-.13.279-.436.655.673 1.019c1.1.36 1.947 1.016 2.18 1.662c.043.121.174.201.28.128c.825-.572 1.56-2.595 1.993-3.83c.471-1.346.416-2.986-.831-3.686");
}

.r8t5-cclp {
  stop-color: var(--svg-color--372023, #372023);
}

.ry3pes94c {
  stop-color: var(--svg-color--422729, #422729);
}

.s61psh5pa {
  fill: var(--svg-color--88868b, #88868B);
  fill-rule: evenodd;
  d: path("M19.41 14.86c1.51-.273 2.56.224 2.844.457a.5.5 0 1 0 .635-.772c-.526-.433-1.878-.99-3.657-.669a.5.5 0 1 0 .178.984");
}

.sb37n_b-l {
  d: path("M8.419 19.936h5.734c.232 0 .418.199.376.427c-.319 1.723-1.718 2.35-2.462 2.37l-1.921-.043c-1.426-.047-2.074-.986-2.391-1.875c-.17-.476.194-.879.664-.879");
}

.semymtb9k {
  fill: var(--svg-color--c2c0c6, #C2C0C6);
  fill-rule: evenodd;
  d: path("M6.495 19.345c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75H6.87a.375.375 0 0 1-.375-.375");
}

.sjitiy62y {
  stop-color: var(--svg-color--b4b3b5, #B4B3B5);
  stop-opacity: 0;
}

.stacowb_v {
  d: path("M10.577 9.15V5.228c.86-.172 1.047-.79 2.383-1.125c1.085-.195 1.593.258 2.617.64v4.625c-.663 1.648-2.365 2.62-3.47 3.028c-.308.115-.66.039-.848-.231c-.604-.868-.682-2.199-.682-3.015");
}

.t_fhyk9zs {
  stop-color: var(--svg-color--714c43, #714C43);
}

.t233yurnp {
  stop-color: var(--svg-color--c6c5c6, #C6C5C6);
}

.t880k8bxx {
  fill-rule: evenodd;
  d: path("M22.788 19.345c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75h-2.02a.375.375 0 0 1-.375-.375");
}

.tjn-pbcga {
  stop-color: var(--svg-color--b0a7b6, #B0A7B6);
  stop-opacity: 0;
}

.tq-c03ytv {
  stop-color: var(--svg-color--351f23, #351F23);
  stop-opacity: 0;
}

.tqlbelb5c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.844 17.227c.117.156-.127.346-.405.554s-.484.354-.6.198c-.117-.157.013-.452.29-.66c.278-.207.598-.249.715-.092");
}

.twscsqg2e {
  cx: 11.437px;
  cy: 17.581px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.717px;
  ry: 0.363px;
}

.tygkjs-ny {
  stop-color: var(--svg-color--9ca7ab, #9CA7AB);
  stop-opacity: 0;
}

.unozt67tp {
  stop-color: var(--svg-color--b4b3b5, #B4B3B5);
}

.vi0ldn3_z {
  stop-color: var(--svg-color--5a4848, #5A4848);
  stop-opacity: 0;
}

.vn83tqcbo {
  stop-color: var(--svg-color--ff4f58, #FF4F58);
}

.vv_rcrb7h {
  stop-color: var(--svg-color--352228, #352228);
  stop-opacity: 0;
}

.w-amzpbim {
  stop-color: var(--svg-color--d9d6dc, #D9D6DC);
  stop-opacity: 0;
}

.w156j0bsh {
  stop-color: var(--svg-color--392225, #392225);
  stop-opacity: 0;
}

.w1xz_gb9i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.413 14.837c.354-.255 1.478-.725 3.14-.562");
}

.wb-iyinxg {
  d: path("M8.776 18.955h5.735c.232 0 .418.198.376.427c-.319 1.722-1.718 2.35-2.462 2.37l-1.922-.044c-1.425-.046-2.073-.985-2.39-1.875c-.17-.475.194-.878.663-.878");
}

.whp-6pbsd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.548 14.762c-.354-.255-1.478-.725-3.14-.563");
}

.x0h7khzay {
  stop-color: var(--svg-color--5d4862, #5D4862);
}

.x473prbqk {
  d: path("M19.967 16.879a1.643 1.643 0 0 1 1.583 2.075h-3.173a1.7 1.7 0 0 1-.06-.433c0-.903.74-1.642 1.65-1.642");
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

.xgquw9bbb {
  stop-color: var(--svg-color--2d181d, #2D181D);
}

.xh84v07wd {
  stop-color: var(--svg-color--b8e1ee, #B8E1EE);
  stop-opacity: 0;
}

.y_-3291qj {
  stop-color: var(--svg-color--55433f, #55433F);
  stop-opacity: 0;
}

.y_2jelukn {
  d: path("M23.743 5.619c-.679-.51-1.791-.438-2.296-.297l-1.11 6.609a5.7 5.7 0 0 0 2.485 1.64c1.625-.859 2.125-3.562 2.125-5.077s-.297-2.196-1.204-2.875");
}

.y0-ze-bdx {
  cx: 11.437px;
  cy: 17.581px;
  rx: 0.717px;
  ry: 0.363px;
}

.y2w6zwvih {
  fill: var(--svg-color--000, #000);
  d: path("M19.026 18.521c0-.522.419-.94.941-.94c.523 0 .941.418.941.94a.9.9 0 0 1-.105.433h-1.665a.85.85 0 0 1-.112-.433");
}

.y3x9krbaf {
  d: path("M11.934 16.879a1.643 1.643 0 0 0-1.583 2.075h3.173c.037-.142.06-.283.06-.433a1.654 1.654 0 0 0-1.65-1.642");
}

.y6fkcvbrv {
  stop-color: var(--svg-color--311b1e, #311B1E);
}

.y6zyajbih {
  stop-color: var(--svg-color--534245, #534245);
  stop-opacity: 0;
}

.yace-6bkn {
  stop-color: var(--svg-color--e4e3e5, #E4E3E5);
}

.yf61h4boy {
  stop-color: var(--svg-color--5a4848, #5A4848);
}

.yg9ra3bzd {
  stop-color: var(--svg-color--b7e0ed, #B7E0ED);
}

.ylir1ob0l {
  stop-color: var(--svg-color--351f23, #351F23);
}

.yqytfrbzb {
  fill: var(--svg-color--47302e, #47302E);
  d: path("m15.243 18.22l-.978 2.97a.992.992 0 0 0 .958 1.288h1.448a.996.996 0 0 0 .958-1.287l-.978-2.97c-.21-.694-1.188-.694-1.408 0");
}

.yxuku-bjv {
  fill: var(--svg-color--252328, #252328);
  d: path("M18.049 17.808c.489-.859 1.231-1.538 2.83-1.538c.7 0 1.374.194 1.974.68c.495.399.429.91.046 1.102l-1.024.584c-1.2-.387-2.526-.44-3.826-.828");
}

.z8u448bed {
  stop-color: var(--svg-color--55433f, #55433F);
}

.zeler-bcd {
  fill-rule: evenodd;
  d: path("M6.495 19.345c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75H6.87a.375.375 0 0 1-.375-.375");
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

</style>
