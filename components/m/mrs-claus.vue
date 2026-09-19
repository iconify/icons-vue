<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLGZu6l)"><path fill="url(#iTBX5yd)" class="jzlt3hbam"/></g><g filter="url(#isqJcee)"><path fill="url(#ixZLPKb)" class="qrfb_bcbk"/></g><path class="j6_dhrc8k"/><path fill="url(#iJL7Vby)" class="c-qvk-bxj"/><path fill="url(#iyibswc)" class="c-qvk-bxj"/><path fill="url(#iEY4bJr)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#iBIMfDO)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#i2RBv1d)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#iAJoLds)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#ifG3FVb)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#icrguYd)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#iN878td)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#iFy8lOb)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#iuVthld)" clip-rule="evenodd" class="hdm-f6_si"/><path fill="url(#ijXkuld)" clip-rule="evenodd" class="hdm-f6_si"/><g filter="url(#iGPDkDc)"><path fill="url(#i1jCeHc)" class="dvlvtp1ae"/></g><g filter="url(#iclwxHe)"><path fill="url(#i2Z5vDK)" class="sb37n_b-l"/></g><g filter="url(#istitAq)"><path class="vplq6ab9m"/></g><g filter="url(#ifOnTGe)"><path class="b53ib0bpl"/><path fill="url(#iOv8pub)" class="quxn97o8y"/><path fill="url(#im5bWki)" class="quxn97o8y"/><path fill="url(#iDYhTse)" class="quxn97o8y"/><path fill="url(#ihUqkSc)" class="quxn97o8y"/><path fill="url(#ihuzLlb)" class="quxn97o8y"/><path fill="url(#iaKDenc)" class="quxn97o8y"/><path fill="url(#iZtpqFe)" class="quxn97o8y"/></g><g filter="url(#imkacsc)"><path stroke="url(#iKtxuud)" class="m_80iabrj"/></g><path class="auondfbkv"/><g filter="url(#iFhKIdd)"><path class="rs5mt5byp"/></g><g filter="url(#igkxwoe)"><path class="d57p1zxcu"/></g><path class="pu8-ecbbp"/><path fill="url(#iZC6JOe)" class="x473prbqk"/><path class="y2w6zwvih"/><g filter="url(#iFGAEMe)"><path class="tqlbelb5c"/><path fill="url(#iqY6bxb)" class="djqsox1gi"/></g><g filter="url(#i8ShE8A)"><path fill="url(#its1NMc)" class="b35v_52zq"/></g><path class="h4wud4aqj"/><path fill="url(#iLxB0Wc)" class="y3x9krbaf"/><path class="jpqz_bbia"/><g filter="url(#iDT4Gzd)"><path fill="url(#ivsx89U)" class="jnvredchk"/></g><g filter="url(#iFTm2Cb)"><ellipse transform="rotate(-27.914 11.437 17.58)" class="twscsqg2e"/><ellipse fill="url(#imJKevd)" transform="rotate(-27.914 11.437 17.58)" class="y0-ze-bdx"/></g><g filter="url(#ic2ZC3Q)"><path fill="url(#i88vPNQ)" class="fhqtnvq7p"/><path fill="url(#iFCQbvb)" class="fhqtnvq7p"/><path fill="url(#iqzv63c)" class="fhqtnvq7p"/><path fill="url(#inwG2ze)" class="fhqtnvq7p"/></g><g filter="url(#iJwv0Bb)"><path clip-rule="evenodd" class="ffgouqs4m"/></g><g filter="url(#irbQY7d)"><path clip-rule="evenodd" class="tswyyqb1t"/></g><g filter="url(#iQKSXNQ)"><path clip-rule="evenodd" class="pt72-1b2e"/><path fill="url(#ij9ubPd)" clip-rule="evenodd" class="zeler-bcd"/><path fill="url(#iY8M7yc)" clip-rule="evenodd" class="zeler-bcd"/><path fill="url(#ibqUPLd)" clip-rule="evenodd" class="zeler-bcd"/></g><g filter="url(#ieB9EQe)"><path clip-rule="evenodd" class="d7d551b-w"/><path fill="url(#iLhJmcc)" clip-rule="evenodd" class="t880k8bxx"/><path fill="url(#inTB0lc)" clip-rule="evenodd" class="t880k8bxx"/></g><g filter="url(#icQzdEc)"><path class="xjhwnjvbs"/><path fill="url(#iOFGcGd)" class="da2kl3hde"/><path fill="url(#igKHZjb)" class="da2kl3hde"/></g><path fill="url(#iJyBL6c)" class="da2kl3hde"/><g filter="url(#iGZAw2A)"><path class="xemgfjg4k"/><path fill="url(#ipMhPoO)" class="ocica9bdm"/><path fill="url(#i7XyqWe)" class="ocica9bdm"/></g><g filter="url(#i15kWlr)"><path class="o5-xr0bzd"/><path fill="url(#iOh3Oac)" class="wb-iyinxg"/></g><g filter="url(#in23Twb)"><path stroke="url(#i3LxYad)" class="w1xz_gb9i"/></g><g filter="url(#ilPT77d)"><path stroke="url(#ihbbIMe)" class="kda60bcml"/></g><g filter="url(#iX4YJyd)"><path fill="url(#iAMs9Bb)" class="lq_yczzut"/><path fill="url(#iXcJqHV)" class="lq_yczzut"/></g><g filter="url(#iNY2MNb)"><path fill="url(#i1Nx3we)" class="r0o24_-xm"/></g><g filter="url(#iNT73ec)"><path fill="url(#ipd6AWc)" class="ish1_actf"/><path fill="url(#icAzjDg)" class="ish1_actf"/><path fill="url(#iO4ydXb)" class="ish1_actf"/></g><g filter="url(#il3h3Kb)"><path fill="url(#iaDS9cb)" class="y_2jelukn"/></g><g filter="url(#ihIya5d)"><path fill="url(#i8Dv9in)" class="stacowb_v"/><path fill="url(#iUCoidd)" class="stacowb_v"/><path fill="url(#iEv0fwb)" class="stacowb_v"/></g><g filter="url(#iWEbHqm)"><path fill="url(#ieZYL7c)" class="cvkbl7bbe"/><path fill="url(#iXmJGcM)" class="cvkbl7bbe"/></g><defs><radialGradient id="iTBX5yd" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.015 17.635)scale(4.54255 3.9894)" gradientUnits="userSpaceOnUse"><stop class="fgz6lbb_q"/><stop offset="1" class="d8k8tnbvi"/></radialGradient><radialGradient id="ixZLPKb" cx="0" cy="0" r="1" gradientTransform="rotate(49.526 -18.276 14.519)scale(3.89961)" gradientUnits="userSpaceOnUse"><stop class="o3d-vqb8m"/><stop offset="1" class="hh1o4kbzd"/></radialGradient><radialGradient id="iJL7Vby" cx="0" cy="0" r="1" gradientTransform="matrix(-15.1875 0 0 -10.125 21.381 6.337)" gradientUnits="userSpaceOnUse"><stop offset=".698" class="mzycncwxb"/><stop offset="1" class="o6ackn6vy"/></radialGradient><radialGradient id="iyibswc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6875 4.6875 -5.60964 -8.00307 25.475 4.275)" gradientUnits="userSpaceOnUse"><stop class="vn83tqcbo"/><stop offset="1" class="c47ug_iov"/></radialGradient><radialGradient id="iEY4bJr" cx="0" cy="0" r="1" gradientTransform="rotate(149.208 8.394 11.1)scale(14.0258 18.7732)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset=".891" class="m45oyzb-o"/></radialGradient><radialGradient id="iBIMfDO" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 7.33 12.053)scale(4.393 3.72715)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="i2RBv1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.54047 -7.44559 9.44707 1.95457 11.935 30.482)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iAJoLds" cx="0" cy="0" r="1" gradientTransform="scale(21.752 13.6954)rotate(90 -.27 .98)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="ifG3FVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.1027 -11.9253 0 16.1 17.118)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="ajxs5ri3z"/><stop offset="1" class="ranbhobii"/></radialGradient><radialGradient id="iN878td" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.11815 2.59954 0 20.183 17.227)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iFy8lOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.50326 2.86891 0 12.416 17.388)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iuVthld" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 2.03125 -.95409 1.37975 18.444 10.806)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="cg2_chy4c"/><stop offset="1" class="nof37jbpk"/></radialGradient><radialGradient id="ijXkuld" cx="0" cy="0" r="1" gradientTransform="rotate(45.774 -4.568 35.952)scale(3.27067 1.0116)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="hdy_q_bzt"/><stop offset="1" class="cs601bbso"/></radialGradient><radialGradient id="i1jCeHc" cx="0" cy="0" r="1" gradientTransform="matrix(5.1875 1.28125 -1.21262 4.90965 17.788 21.119)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="qg-xfqbii"/><stop offset="1" class="sms6wwikh"/></radialGradient><radialGradient id="i2Z5vDK" cx="0" cy="0" r="1" gradientTransform="rotate(101.083 -2.847 15.056)scale(3.08885 4.56981)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="af-no4ehh"/><stop offset="1" class="lrs4p2b0y"/></radialGradient><radialGradient id="iOv8pub" cx="0" cy="0" r="1" gradientTransform="rotate(-108.165 16.588 4.525)scale(4.85113 2.64879)" gradientUnits="userSpaceOnUse"><stop class="e1qh__bvr"/><stop offset="1" class="fjchnz9qq"/></radialGradient><radialGradient id="im5bWki" cx="0" cy="0" r="1" gradientTransform="matrix(-.85936 3.14063 -4.19983 -1.14918 16.522 19.51)" gradientUnits="userSpaceOnUse"><stop offset=".494" class="kpx0wlblb"/><stop offset=".979" class="ryb7lnbbf"/></radialGradient><radialGradient id="iDYhTse" cx="0" cy="0" r="1" gradientTransform="rotate(16.917 -59.35 59.322)scale(.86558 3.32753)" gradientUnits="userSpaceOnUse"><stop offset=".099" class="qca1hdbtf"/><stop offset="1" class="m0kmulbnd"/></radialGradient><radialGradient id="ihUqkSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.71875 2.29358 0 15.947 21.962)" gradientUnits="userSpaceOnUse"><stop offset=".861" class="mnq4wlb5s"/><stop offset="1" class="ygwqxfbcf"/></radialGradient><radialGradient id="ihuzLlb" cx="0" cy="0" r="1" gradientTransform="rotate(-112.797 15.352 4.998)scale(1.16948 .89981)" gradientUnits="userSpaceOnUse"><stop class="e1qh__bvr"/><stop offset="1" class="fjchnz9qq"/></radialGradient><radialGradient id="iaKDenc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.776 14.135 5.8)scale(2.37217 1.38355)" gradientUnits="userSpaceOnUse"><stop offset=".48" class="c7h44xb-q"/><stop offset="1" class="gw_xw44-e"/></radialGradient><radialGradient id="iZC6JOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49333 -2.37531 0 19.963 17.757)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iqY6bxb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.157 4.17)scale(.69518 .9571)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLxB0Wc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49334 -2.37533 0 11.937 17.757)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="imJKevd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01423 -.90865 1.09224 -.0171 11.41 18.16)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFCQbvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.1076 1.90987 -2.1901 -.12338 10.615 4.891)" gradientUnits="userSpaceOnUse"><stop class="o-gllcbpi"/><stop offset="1" class="op8gn6bnt"/></radialGradient><radialGradient id="iqzv63c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23266 0 0 -5.95693 7.091 18.825)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="c3098ubep"/><stop offset=".808" class="ixxpbv8hf"/></radialGradient><radialGradient id="inwG2ze" cx="0" cy="0" r="1" gradientTransform="rotate(118.957 8.488 15.254)scale(5.35726 1.55455)" gradientUnits="userSpaceOnUse"><stop class="paruexevs"/><stop offset="1" class="lcus7p0ww"/></radialGradient><radialGradient id="ij9ubPd" cx="0" cy="0" r="1" gradientTransform="rotate(131.743 -.221 11.58)scale(.68059 .35127)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="cu6-vrj2i"/><stop offset="1" class="c9zlqrb3t"/></radialGradient><radialGradient id="ibqUPLd" cx="0" cy="0" r="1" gradientTransform="matrix(.47656 .44531 -.60932 .65208 6.538 19.025)" gradientUnits="userSpaceOnUse"><stop class="hhpz10b5r"/><stop offset="1" class="dvj22vbfw"/></radialGradient><radialGradient id="iLhJmcc" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 -.09375 .13594 1.05353 23.6 19.51)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="r5eaa9byw"/><stop offset=".997" class="s2xj5ccle"/></radialGradient><radialGradient id="iOFGcGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.80005 -1.45312 .28898 -.1591 17.68 19.025)" gradientUnits="userSpaceOnUse"><stop class="t9zwr_bju"/><stop offset="1" class="yalq5sf5a"/></radialGradient><radialGradient id="igKHZjb" cx="0" cy="0" r="1" gradientTransform="matrix(.57813 -1.10938 .29816 .15538 14.678 19.181)" gradientUnits="userSpaceOnUse"><stop class="im9wvj10u"/><stop offset="1" class="mr4rayb4t"/></radialGradient><radialGradient id="iJyBL6c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96021 -1.0123 1.0168 -1.96892 16.225 19.572)" gradientUnits="userSpaceOnUse"><stop offset=".77" class="l-b5gabta"/><stop offset=".937" class="gp3ifxaea"/></radialGradient><radialGradient id="iAMs9Bb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.63619 -5.40116 1.4488 -.70713 8.006 12.854)" gradientUnits="userSpaceOnUse"><stop class="cvqywpbya"/><stop offset="1" class="do75vybld"/></radialGradient><radialGradient id="iXcJqHV" cx="0" cy="0" r="1" gradientTransform="matrix(.55304 6.50969 -3.32228 .28225 6.553 8.307)" gradientUnits="userSpaceOnUse"><stop offset=".505" class="tjn-pbcga"/><stop offset="1" class="q270rhb2n"/></radialGradient><radialGradient id="i1Nx3we" cx="0" cy="0" r="1" gradientTransform="matrix(5.54388 1.16889 -2.00192 9.49486 22.68 11.48)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="o0zfjub8g"/><stop offset=".932" class="emarm55as"/></radialGradient><radialGradient id="ipd6AWc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93356 -6.50176 2.0863 -.62045 10.645 11.72)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="hffkdxxqc"/><stop offset="1" class="pew6frnzi"/></radialGradient><radialGradient id="icAzjDg" cx="0" cy="0" r="1" gradientTransform="rotate(162.165 4.705 5.463)scale(3.24962 5.81408)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="d2xfa78kb"/><stop offset="1" class="bemgdwb7k"/></radialGradient><radialGradient id="iO4ydXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.39841 -3.90671 0 9.63 8.173)" gradientUnits="userSpaceOnUse"><stop offset=".817" class="h13c6fb3k"/><stop offset="1" class="k-7dzim-i"/></radialGradient><radialGradient id="iaDS9cb" cx="0" cy="0" r="1" gradientTransform="rotate(32.247 -3.98 40.286)scale(5.50541 6.13649)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="q63b76bcm"/><stop offset="1" class="l_nupdb1h"/></radialGradient><radialGradient id="i8Dv9in" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.34375 4.69757 0 15.819 8.618)" gradientUnits="userSpaceOnUse"><stop offset=".357" class="ea88qbbkv"/><stop offset="1" class="l_hht1tza"/></radialGradient><radialGradient id="iEv0fwb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03127 5.6875 -4.70513 -1.68042 13.663 5.806)" gradientUnits="userSpaceOnUse"><stop offset=".544" class="o8-p00v9r"/><stop offset="1" class="kpi-j7bnf"/></radialGradient><radialGradient id="ieZYL7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.78125 3.21875 0 19.847 8.931)" gradientUnits="userSpaceOnUse"><stop class="gh7w8ccdd"/><stop offset="1" class="q90nxab-j"/></radialGradient><radialGradient id="iXmJGcM" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 2.25 -3.86674 -5.58532 19.756 7.431)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="ju711jbwd"/><stop offset="1" class="ep--azv6o"/></radialGradient><filter id="iLGZu6l" width="6.033" height="6.033" x="22.017" y="15.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.556863 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/></filter><filter id="isqJcee" width="6.033" height="6.133" x="3.945" y="16.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.635294 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/></filter><filter id="iGPDkDc" width="8.322" height="4.297" x="15.869" y="19.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".375"/></filter><filter id="iclwxHe" width="8.322" height="4.297" x="6.962" y="19.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".375"/></filter><filter id="istitAq" width="4.312" height="5.936" x="13.421" y="17.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".25"/></filter><filter id="ifOnTGe" width="3.555" height="4.778" x="14.22" y="17.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.533333 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/></filter><filter id="imkacsc" width="6.478" height="2.472" x="12.708" y="23.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".05"/></filter><filter id="iFhKIdd" width="5.356" height="2.366" x="17.849" y="16.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/></filter><filter id="igkxwoe" width="5.356" height="2.366" x="8.696" y="16.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/></filter><filter id="iFGAEMe" width="1.278" height="1.112" x="18.696" y="17.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".05"/></filter><filter id="i8ShE8A" width="1.303" height="1.343" x="20.326" y="17.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".1"/></filter><filter id="iDT4Gzd" width="1.477" height="1.577" x="12.155" y="17.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".1"/></filter><filter id="iFTm2Cb" width="1.511" height="1.128" x="10.681" y="17.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".05"/></filter><filter id="ic2ZC3Q" width="25.121" height="17.787" x="3.515" y="3.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.615686 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/></filter><filter id="iJwv0Bb" width="4.251" height="1.951" x="8.893" y="13.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.392157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/></filter><filter id="irbQY7d" width="4.251" height="1.951" x="18.821" y="13.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.454902 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/></filter><filter id="iQKSXNQ" width="2.77" height=".9" x="6.495" y="18.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.470588 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/></filter><filter id="ieB9EQe" width="2.97" height=".9" x="22.788" y="18.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.486275 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/></filter><filter id="icQzdEc" width="3.466" height="1.925" x="14.265" y="17.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.541176 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/></filter><filter id="iGZAw2A" width="6.862" height="2.837" x="16.957" y="18.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".02" dy="-.02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.776471 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.937255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24203" result="effect2_innerShadow_3987_24203"/></filter><filter id="i15kWlr" width="6.862" height="2.837" x="8.05" y="18.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".02" dy="-.02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.776471 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24203"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".01"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.937255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24203" result="effect2_innerShadow_3987_24203"/></filter><filter id="in23Twb" width="3.891" height="1.346" x="9.038" y="13.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".125"/></filter><filter id="ilPT77d" width="3.891" height="1.346" x="18.921" y="13.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".125"/></filter><filter id="iX4YJyd" width="6.389" height="9.227" x="3.959" y="6.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".25"/></filter><filter id="iNY2MNb" width="6.538" height="8.968" x="21.546" y="6.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".25"/></filter><filter id="iNT73ec" width="5.609" height="9.353" x="6.825" y="4.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".25"/></filter><filter id="il3h3Kb" width="5.609" height="9.353" x="19.837" y="4.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".25"/></filter><filter id="ihIya5d" width="6.2" height="9.592" x="9.977" y="3.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".3"/></filter><filter id="iWEbHqm" width="6.2" height="9.592" x="15.705" y="3.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24203" stdDeviation=".3"/></filter><linearGradient id="icrguYd" x1="8.913" x2="6.569" y1="20.025" y2="20.025" gradientUnits="userSpaceOnUse"><stop class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></linearGradient><linearGradient id="iZtpqFe" x1="15.947" x2="15.947" y1="22.697" y2="22.15" gradientUnits="userSpaceOnUse"><stop class="p8la00r3a"/><stop offset="1" class="mk5ra_bmm"/></linearGradient><linearGradient id="iKtxuud" x1="14.605" x2="15.438" y1="25.522" y2="23.918" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="its1NMc" x1="21.394" x2="20.817" y1="17.855" y2="18.21" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivsx89U" x1="13.305" x2="12.728" y1="17.855" y2="18.21" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i88vPNQ" x1="26.288" x2="10.475" y1="14.712" y2="14.712" gradientUnits="userSpaceOnUse"><stop class="o1xctu8tq"/><stop offset="1" class="e3tydgbfn"/></linearGradient><linearGradient id="iY8M7yc" x1="7.879" x2="7.879" y1="18.943" y2="19.165" gradientUnits="userSpaceOnUse"><stop class="eoj5wqblu"/><stop offset="1" class="h7ahknhja"/></linearGradient><linearGradient id="inTB0lc" x1="24.172" x2="24.172" y1="18.97" y2="19.169" gradientUnits="userSpaceOnUse"><stop class="k4sbv61nf"/><stop offset="1" class="hdgtw1puh"/></linearGradient><linearGradient id="ipMhPoO" x1="21.35" x2="21.35" y1="21.751" y2="20.353" gradientUnits="userSpaceOnUse"><stop offset=".006" class="oyh60775y"/><stop offset="1" class="jfie-p4xp"/></linearGradient><linearGradient id="i7XyqWe" x1="18.795" x2="20.686" y1="19.962" y2="20.697" gradientUnits="userSpaceOnUse"><stop class="uf-5mtb-c"/><stop offset=".141" class="bgel09j3s"/><stop offset=".868" class="bgel09j3s"/><stop offset="1" class="uf-5mtb-c"/></linearGradient><linearGradient id="iOh3Oac" x1="12.655" x2="10.655" y1="20.689" y2="19.845" gradientUnits="userSpaceOnUse"><stop class="uf-5mtb-c"/><stop offset=".141" class="bgel09j3s"/><stop offset=".868" class="bgel09j3s"/><stop offset="1" class="uf-5mtb-c"/></linearGradient><linearGradient id="i3LxYad" x1="12.647" x2="8.741" y1="14.241" y2="15.087" gradientUnits="userSpaceOnUse"><stop class="dv12edcsa"/><stop offset="1" class="yg4-1othp"/></linearGradient><linearGradient id="ihbbIMe" x1="22.436" x2="18.288" y1="14.837" y2="14.539" gradientUnits="userSpaceOnUse"><stop offset=".166" class="dv12edcsa"/><stop offset="1" class="yg4-1othp"/></linearGradient><linearGradient id="iUCoidd" x1="10.288" x2="13.073" y1="8.337" y2="8.337" gradientUnits="userSpaceOnUse"><stop class="h243fe46z"/><stop offset="1" class="w-amzpbim"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mrs-claus" /></template>
<style>
.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.af-no4ehh {
  stop-color: var(--svg-color--ca882b, #CA882B);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.auondfbkv {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.947 24.242c-.958 0-1.86-.231-2.616-.635c-.26-.134-.537.164-.374.404a3.56 3.56 0 0 0 2.99 1.634a3.56 3.56 0 0 0 2.99-1.634c.164-.25-.114-.538-.373-.404a5.55 5.55 0 0 1-2.617.635");
}

.b35v_52zq {
  d: path("M21.429 18.304a1.54 1.54 0 0 0-.425-.85l-.478.523l.216.42z");
}

.b53ib0bpl {
  fill: var(--svg-color--ffbf2b, #FFBF2B);
  d: path("m15.243 18.22l-.978 2.97a.992.992 0 0 0 .958 1.288h1.448a.996.996 0 0 0 .958-1.287l-.978-2.97c-.21-.694-1.188-.694-1.408 0");
}

.bemgdwb7k {
  stop-color: var(--svg-color--b4b0b8, #B4B0B8);
}

.bgel09j3s {
  stop-color: var(--svg-color--e3f8ff, #E3F8FF);
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

.c7h44xb-q {
  stop-color: var(--svg-color--d9a027, #D9A027);
}

.c9zlqrb3t {
  stop-color: var(--svg-color--d7b0d4, #D7B0D4);
  stop-opacity: 0;
}

.cg2_chy4c {
  stop-color: var(--svg-color--f6a032, #F6A032);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cs601bbso {
  stop-color: var(--svg-color--d49726, #D49726);
  stop-opacity: 0;
}

.cu6-vrj2i {
  stop-color: var(--svg-color--a77ac5, #A77AC5);
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

.d57p1zxcu {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M13.852 17.808c-.488-.859-1.231-1.538-2.83-1.538c-.7 0-1.374.194-1.974.68c-.495.399-.429.91-.046 1.102l1.024.584c1.2-.387 2.526-.44 3.826-.828");
}

.d7d551b-w {
  fill: var(--svg-color--f0deed, #F0DEED);
  fill-rule: evenodd;
  d: path("M22.788 19.345c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75h-2.02a.375.375 0 0 1-.375-.375");
}

.d8k8tnbvi {
  stop-color: var(--svg-color--eeaa36, #EEAA36);
}

.da2kl3hde {
  d: path("m17.68 19.447l.001-.067a1.708 1.708 0 1 0-3.415.067h.55l-.001-.067a1.158 1.158 0 1 1 2.314.067z");
}

.djqsox1gi {
  d: path("M19.844 17.227c.117.156-.127.346-.405.554s-.484.354-.6.198c-.117-.157.013-.452.29-.66c.278-.207.598-.249.715-.092");
}

.do75vybld {
  stop-color: var(--svg-color--b8b5bb, #B8B5BB);
  stop-opacity: 0;
}

.dv12edcsa {
  stop-color: var(--svg-color--aa98a3, #AA98A3);
}

.dvj22vbfw {
  stop-color: var(--svg-color--e4c0d6, #E4C0D6);
  stop-opacity: 0;
}

.dvlvtp1ae {
  d: path("M22.735 19.936H17c-.232 0-.418.199-.375.427c.318 1.723 1.718 2.35 2.461 2.37l1.922-.043c1.425-.047 2.073-.986 2.39-1.875c.17-.476-.193-.879-.663-.879");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e1qh__bvr {
  stop-color: var(--svg-color--ffd342, #FFD342);
}

.e3tydgbfn {
  stop-color: var(--svg-color--bab9bc, #BAB9BC);
}

.ea88qbbkv {
  stop-color: var(--svg-color--f0edf4, #F0EDF4);
}

.emarm55as {
  stop-color: var(--svg-color--dbd9dd, #DBD9DD);
}

.eoj5wqblu {
  stop-color: var(--svg-color--c7afab, #C7AFAB);
}

.ep--azv6o {
  stop-color: var(--svg-color--ccc9d0, #CCC9D0);
}

.ffgouqs4m {
  fill: var(--svg-color--938285, #938285);
  fill-rule: evenodd;
  d: path("M12.555 14.86c-1.511-.273-2.56.224-2.844.457a.5.5 0 1 1-.635-.772c.526-.433 1.878-.99 3.657-.669a.5.5 0 1 1-.178.984");
}

.fgz6lbb_q {
  stop-color: var(--svg-color--ffe948, #FFE948);
}

.fhqtnvq7p {
  d: path("M6.744 21.33a.095.095 0 0 0 .1-.09c.05-.81.162-2.752.198-3.965c.052-1.72.863-2.688 2.12-3.242a10 10 0 0 0 1.637-.796c.247-.15.44-.266.757-.384q.129-.047.32-.105c.88-.277 2.81-1.076 3.887-3.179c.085-.166.348-.156.423.014c.935 2.11 2.958 2.885 3.864 3.156q.216.064.356.114c.316.118.573.213.82.363c.799.487.839.445 1.804.84c1.82.813 1.87 1.531 1.87 3.219c.037 1.213.105 3.158.152 3.97a.094.094 0 0 0 .1.09c1.223-.08 1.912-1.706 2.106-2.529l.785-2.969c.4-1.586.55-2.42.362-3.098c-.173-.625-.655-1.313-.833-1.527c0-.072.022-.207.05-.383c.096-.581.128-1.362-.186-2.07c-.503-1.05-1.258-1.312-1.781-1.46c-.477-.071-.764-.257-1.016-.782c-.992-1.793-2.234-1.695-2.805-1.695c-.461.054-.773.054-1.289-.297c-1.312-1.094-2.637-.703-3.423-.328c-.628.3-1.016.343-1.131.328c-.116.015-.505-.028-1.137-.328c-.789-.375-2.059-.797-3.45.328c-.46.398-.701.396-1.189.338c-.393-.046-1.97-.178-2.966 1.615c-.253.525-.717.62-.949.625c-.437.031-1.436.356-1.941 1.406c-.315.708-.225 1.746-.13 2.328c.029.176.05.31.05.383c-.178.214-.528.875-.702 1.5c-.188.679.088 2.341.308 3.117l.79 2.969c.195.823.842 2.445 2.07 2.524");
}

.fjchnz9qq {
  stop-color: var(--svg-color--ffd342, #FFD342);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gh7w8ccdd {
  stop-color: var(--svg-color--f7f5f9, #F7F5F9);
}

.gp3ifxaea {
  stop-color: var(--svg-color--b09991, #B09991);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gw_xw44-e {
  stop-color: var(--svg-color--f8b42c, #F8B42C);
  stop-opacity: 0;
}

.h13c6fb3k {
  stop-color: var(--svg-color--b39cb2, #B39CB2);
  stop-opacity: 0;
}

.h243fe46z {
  stop-color: var(--svg-color--b6b4b8, #B6B4B8);
}

.h4wud4aqj {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.553 16.378a2.57 2.57 0 0 0-2.494 1.95a.505.505 0 0 0 .493.626h4.106c.262 0 .47-.239.418-.5a2.58 2.58 0 0 0-2.523-2.076");
}

.h7ahknhja {
  stop-color: var(--svg-color--e6c4d6, #E6C4D6);
  stop-opacity: 0;
}

.hdgtw1puh {
  stop-color: var(--svg-color--f1deed, #F1DEED);
  stop-opacity: 0;
}

.hdm-f6_si {
  fill-rule: evenodd;
  d: path("M6.762 21.33v.023c.228 5.158 4.256 8.622 9.173 8.622s8.945-3.464 9.172-8.622l.001-.027a.1.1 0 0 1-.056-.082c-.047-.81-.115-2.756-.151-3.97c0-1.687-.05-2.406-1.871-3.218a27 27 0 0 0-.569-.226c-.462-.18-.633-.247-1.236-.614c-.242-.147-.495-.242-.803-.358l-.016-.005c-.092-.035-.212-.07-.355-.114c-.907-.271-2.93-1.045-3.865-3.156c-.075-.17-.338-.18-.423-.014c-1.077 2.103-3.006 2.902-3.887 3.178q-.191.059-.32.106a4 4 0 0 0-.757.384a10 10 0 0 1-1.636.796c-1.258.554-2.07 1.522-2.12 3.242a153 153 0 0 1-.199 3.965a.095.095 0 0 1-.082.09");
}

.hdy_q_bzt {
  stop-color: var(--svg-color--d49726, #D49726);
}

.hffkdxxqc {
  stop-color: var(--svg-color--c9c2d1, #C9C2D1);
}

.hh1o4kbzd {
  stop-color: var(--svg-color--ca783d, #CA783D);
}

.hhpz10b5r {
  stop-color: var(--svg-color--b79c9c, #B79C9C);
}

.im9wvj10u {
  stop-color: var(--svg-color--e0dae0, #E0DAE0);
}

.ish1_actf {
  d: path("M8.528 5.619c.68-.51 1.791-.438 2.297-.297l1.11 6.609a5.7 5.7 0 0 1-2.485 1.64c-1.625-.859-2.125-3.562-2.125-5.077s.297-2.196 1.203-2.875");
}

.ixxpbv8hf {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
  stop-opacity: 0;
}

.j6_dhrc8k {
  fill: var(--svg-color--f53742, #F53742);
  d: path("M6.038 7.525a5.5 5.5 0 0 1 5.5-5.5h8.906a5.5 5.5 0 0 1 5.5 5.5v3.125H6.038z");
}

.jfie-p4xp {
  stop-color: var(--svg-color--9cddff, #9CDDFF);
  stop-opacity: 0;
}

.jnvredchk {
  d: path("M13.433 18.327c0-.53-.431-.884-.548-.99l-.53.512l.326.664z");
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

.k4sbv61nf {
  stop-color: var(--svg-color--d8c6c2, #D8C6C2);
}

.kda60bcml {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.437 14.837c-.355-.255-1.479-.725-3.141-.562");
}

.kpi-j7bnf {
  stop-color: var(--svg-color--b7a9bb, #B7A9BB);
}

.kpx0wlblb {
  stop-color: var(--svg-color--ffb930, #FFB930);
  stop-opacity: 0;
}

.l_hht1tza {
  stop-color: var(--svg-color--f0edf4, #F0EDF4);
  stop-opacity: 0;
}

.l_nupdb1h {
  stop-color: var(--svg-color--d1cbd8, #D1CBD8);
}

.l-b5gabta {
  stop-color: var(--svg-color--f0cfe3, #F0CFE3);
  stop-opacity: 0;
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

.lrs4p2b0y {
  stop-color: var(--svg-color--ca882b, #CA882B);
  stop-opacity: 0;
}

.m_80iabrj {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.947 24.242c-.958 0-1.86-.231-2.616-.635c-.26-.134-.537.164-.374.404a3.56 3.56 0 0 0 2.99 1.634a3.56 3.56 0 0 0 2.99-1.634c.164-.25-.114-.538-.373-.404a5.55 5.55 0 0 1-2.617.635Z");
}

.m0kmulbnd {
  stop-color: var(--svg-color--fbb532, #FBB532);
  stop-opacity: 0;
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mk5ra_bmm {
  stop-color: var(--svg-color--df7f33, #DF7F33);
  stop-opacity: 0;
}

.mnq4wlb5s {
  stop-color: var(--svg-color--f09e24, #F09E24);
  stop-opacity: 0;
}

.mr4rayb4t {
  stop-color: var(--svg-color--e0dae0, #E0DAE0);
  stop-opacity: 0;
}

.mzycncwxb {
  stop-color: var(--svg-color--a33337, #A33337);
  stop-opacity: 0;
}

.nof37jbpk {
  stop-color: var(--svg-color--f6a032, #F6A032);
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

.o3d-vqb8m {
  stop-color: var(--svg-color--de8d2b, #DE8D2B);
}

.o5-xr0bzd {
  fill: var(--svg-color--a6eaff, #A6EAFF);
  d: path("M8.776 18.955h5.735c.232 0 .418.198.376.427c-.319 1.722-1.718 2.35-2.462 2.37l-1.922-.044c-1.425-.046-2.073-.985-2.39-1.875c-.17-.475.194-.878.663-.878");
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

.oyh60775y {
  stop-color: var(--svg-color--9cddff, #9CDDFF);
}

.p8la00r3a {
  stop-color: var(--svg-color--df7f33, #DF7F33);
}

.paruexevs {
  stop-color: var(--svg-color--d7d3db, #D7D3DB);
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pew6frnzi {
  stop-color: var(--svg-color--c9c2d1, #C9C2D1);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pt72-1b2e {
  fill: var(--svg-color--e9c7d5, #E9C7D5);
  fill-rule: evenodd;
  d: path("M6.495 19.345c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75H6.87a.375.375 0 0 1-.375-.375");
}

.pu8-ecbbp {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.348 16.378c1.202 0 2.218.83 2.494 1.95a.505.505 0 0 1-.493.626h-4.106a.424.424 0 0 1-.418-.5a2.57 2.57 0 0 1 2.523-2.076");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
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

.qca1hdbtf {
  stop-color: var(--svg-color--c8931e, #C8931E);
}

.qg-xfqbii {
  stop-color: var(--svg-color--dc9524, #DC9524);
}

.qrfb_bcbk {
  d: path("M6.911 21.964a2.966 2.966 0 1 0 0-5.933a2.966 2.966 0 0 0 0 5.933");
}

.quxn97o8y {
  d: path("m15.243 18.22l-.978 2.97a.992.992 0 0 0 .958 1.288h1.448a.996.996 0 0 0 .958-1.287l-.978-2.97c-.21-.694-1.188-.694-1.408 0");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0o24_-xm {
  d: path("M26.48 7.877c-.998-.56-2.004-.448-2.383-.323l-1.912 5.03c-.13.279-.436.655.673 1.019c1.1.36 1.947 1.016 2.18 1.662c.043.121.174.201.28.128c.825-.572 1.56-2.595 1.993-3.83c.471-1.346.416-2.986-.831-3.686");
}

.r5eaa9byw {
  stop-color: var(--svg-color--ddd9dc, #DDD9DC);
}

.ranbhobii {
  stop-color: var(--svg-color--d87c7a, #D87C7A);
}

.rs5mt5byp {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M18.049 17.808c.489-.859 1.231-1.538 2.83-1.538c.7 0 1.374.194 1.974.68c.495.399.429.91.046 1.102l-1.024.584c-1.2-.387-2.526-.44-3.826-.828");
}

.ryb7lnbbf {
  stop-color: var(--svg-color--e88c3c, #E88C3C);
}

.s2xj5ccle {
  stop-color: var(--svg-color--ddd9dc, #DDD9DC);
  stop-opacity: 0;
}

.sb37n_b-l {
  d: path("M8.419 19.936h5.734c.232 0 .418.199.376.427c-.319 1.723-1.718 2.35-2.462 2.37l-1.921-.043c-1.426-.047-2.074-.986-2.391-1.875c-.17-.476.194-.879.664-.879");
}

.sms6wwikh {
  stop-color: var(--svg-color--e5a927, #E5A927);
  stop-opacity: 0;
}

.stacowb_v {
  d: path("M10.577 9.15V5.228c.86-.172 1.047-.79 2.383-1.125c1.085-.195 1.593.258 2.617.64v4.625c-.663 1.648-2.365 2.62-3.47 3.028c-.308.115-.66.039-.848-.231c-.604-.868-.682-2.199-.682-3.015");
}

.t880k8bxx {
  fill-rule: evenodd;
  d: path("M22.788 19.345c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75h-2.02a.375.375 0 0 1-.375-.375");
}

.t9zwr_bju {
  stop-color: var(--svg-color--ebe8ea, #EBE8EA);
}

.tjn-pbcga {
  stop-color: var(--svg-color--b0a7b6, #B0A7B6);
  stop-opacity: 0;
}

.tqlbelb5c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.844 17.227c.117.156-.127.346-.405.554s-.484.354-.6.198c-.117-.157.013-.452.29-.66c.278-.207.598-.249.715-.092");
}

.tswyyqb1t {
  fill: var(--svg-color--9a8e91, #9A8E91);
  fill-rule: evenodd;
  d: path("M19.41 14.86c1.51-.273 2.56.224 2.844.457a.5.5 0 1 0 .635-.772c-.526-.433-1.878-.99-3.657-.669a.5.5 0 1 0 .178.984");
}

.twscsqg2e {
  cx: 11.437px;
  cy: 17.581px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.717px;
  ry: 0.363px;
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.uf-5mtb-c {
  stop-color: var(--svg-color--e3f8ff, #E3F8FF);
  stop-opacity: 0;
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vn83tqcbo {
  stop-color: var(--svg-color--ff4f58, #FF4F58);
}

.vplq6ab9m {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.17 18.317l-1.206 3.129c-.19.643.268 1.287.92 1.287h1.386c.651 0 1.11-.654.92-1.287l-.939-3.13c-.2-.693-.87-.693-1.08 0");
}

.w-amzpbim {
  stop-color: var(--svg-color--d9d6dc, #D9D6DC);
  stop-opacity: 0;
}

.w1xz_gb9i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.413 14.837c.354-.255 1.478-.725 3.14-.562");
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wb-iyinxg {
  d: path("M8.776 18.955h5.735c.232 0 .418.198.376.427c-.319 1.722-1.718 2.35-2.462 2.37l-1.922-.044c-1.425-.046-2.073-.985-2.39-1.875c-.17-.475.194-.878.663-.878");
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x473prbqk {
  d: path("M19.967 16.879a1.643 1.643 0 0 1 1.583 2.075h-3.173a1.7 1.7 0 0 1-.06-.433c0-.903.74-1.642 1.65-1.642");
}

.xemgfjg4k {
  fill: var(--svg-color--a6eaff, #A6EAFF);
  d: path("M23.093 18.955h-5.735c-.232 0-.418.198-.375.427c.318 1.722 1.717 2.35 2.461 2.37l1.922-.044c1.425-.046 2.073-.985 2.39-1.875c.17-.475-.193-.878-.663-.878");
}

.xjhwnjvbs {
  fill: var(--svg-color--efcee2, #EFCEE2);
  d: path("m17.68 19.447l.001-.067a1.708 1.708 0 1 0-3.415.067h.55l-.001-.067a1.158 1.158 0 1 1 2.314.067z");
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

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yalq5sf5a {
  stop-color: var(--svg-color--ebe8ea, #EBE8EA);
  stop-opacity: 0;
}

.yg4-1othp {
  stop-color: var(--svg-color--aa98a3, #AA98A3);
  stop-opacity: 0;
}

.ygwqxfbcf {
  stop-color: var(--svg-color--f09e24, #F09E24);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.zeler-bcd {
  fill-rule: evenodd;
  d: path("M6.495 19.345c0-.207.168-.375.375-.375h2.02a.375.375 0 0 1 0 .75H6.87a.375.375 0 0 1-.375-.375");
}

</style>
