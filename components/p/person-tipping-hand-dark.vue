<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iIUFVGc)" class="cxzhkxbuv"/><path fill="url(#imIzwGb)" class="cxzhkxbuv"/><path fill="url(#icKCTfe)" class="cxzhkxbuv"/><rect fill="url(#i11wEOc)" class="javqacc3k"/><path class="p3ziwhb9q"/><path fill="url(#i3AOkKd)" class="du4kig3ov"/><path fill="url(#i7WEule)" class="du4kig3ov"/><path clip-rule="evenodd" class="gki0s6b2a"/><path fill="url(#iEjqyPV)" clip-rule="evenodd" class="igyf75bxe"/><path fill="url(#imC7Hce)" clip-rule="evenodd" class="igyf75bxe"/><path fill="url(#i3ehxDO)" clip-rule="evenodd" class="igyf75bxe"/><path clip-rule="evenodd" class="lz4e7hb7r"/><path fill="url(#iIqiojb)" clip-rule="evenodd" class="mwt29lbuz"/><path fill="url(#iAR93uc)" clip-rule="evenodd" class="mwt29lbuz"/><path fill="url(#iibu57d)" clip-rule="evenodd" class="mwt29lbuz"/><path clip-rule="evenodd" class="xyj2y_0yr"/><path fill="url(#isqey2c)" clip-rule="evenodd" class="ycbp9gizk"/><path fill="url(#i9Fkrte)" clip-rule="evenodd" class="ycbp9gizk"/><path fill="url(#iNiuJ5v)" clip-rule="evenodd" class="ycbp9gizk"/><g filter="url(#icgwOLb)"><path class="ajf4f4e7i"/><path fill="url(#i76RUWb)" class="q0a5xac1f"/><path fill="url(#irZBWlb)" class="q0a5xac1f"/><path fill="url(#iciIvOd)" class="q0a5xac1f"/><path fill="url(#ivfZt5b)" class="q0a5xac1f"/></g><path fill="url(#iVGz4dN)" class="h7qd-yz4i"/><path fill="url(#imXNWSE)" class="h7qd-yz4i"/><path fill="url(#i6W39Bd)" class="y48d6ebxt"/><path fill="url(#iPWlegb)" class="y48d6ebxt"/><path fill="url(#irEYaRb)" class="y48d6ebxt"/><path fill="url(#ilnaKpN)" class="emqx9pqag"/><path fill="url(#iQY8UTV)" class="wf3_gcc9s"/><g filter="url(#iM5nyke)"><path fill="url(#iaTARtd)" class="pjfcxrj0f"/></g><path fill="url(#iuiR1Tb)" class="pjfcxrj0f"/><path fill="url(#imSjNGv)" class="pjfcxrj0f"/><path fill="url(#i4ADrdE)" class="pjfcxrj0f"/><path fill="url(#iautWNc)" class="pjfcxrj0f"/><path fill="url(#i0qfvad)" class="pjfcxrj0f"/><path fill="url(#ibdmsje)" class="pjfcxrj0f"/><path fill="url(#i0Nz2He)" class="pjfcxrj0f"/><path fill="url(#iCU6DKP)" class="pjfcxrj0f"/><path fill="url(#iQkuQUb)" class="pjfcxrj0f"/><g filter="url(#iYMQozd)"><path class="w4uu1soap"/></g><g filter="url(#iJOwMhe)"><path class="wpyfiqb4o"/><path fill="url(#imqSvxb)" class="zt4lf7b2y"/><path fill="url(#i1BDPUc)" class="zt4lf7b2y"/><path fill="url(#iVIpMxe)" class="zt4lf7b2y"/><path fill="url(#ispWsLd)" class="zt4lf7b2y"/><path fill="url(#iNiB1xd)" class="zt4lf7b2y"/></g><g filter="url(#iFWG88y)"><path stroke="url(#iCoSAue)" class="wmrlrdbfz"/></g><path fill="url(#i1JKCgm)" class="yujqq5-iy"/><g filter="url(#iiVcwzd)"><path fill="url(#iE7Qucd)" class="rr06i0p7e"/><path fill="url(#iTOgnbd)" class="rr06i0p7e"/><path fill="url(#iuO3Avd)" class="rr06i0p7e"/><path fill="url(#ieZJXYd)" class="rr06i0p7e"/><path fill="url(#i7dxXId)" class="rr06i0p7e"/></g><g filter="url(#iHlbTRd)"><path class="g7d3phb7y"/></g><g filter="url(#i03pGsL)"><path class="f72h3jkbj"/></g><g filter="url(#i4ZQjvb)"><path class="a6g-43b-p"/><path fill="url(#i1kylTm)" class="cis39obud"/><path fill="url(#ipnGuxw)" class="cis39obud"/></g><g filter="url(#iPr3cic)"><path class="ai6m5ac0v"/><path fill="url(#iuNExhS)" class="dm_q_zbtq"/></g><path class="xp5ouwjaz"/><path fill="url(#idAPySc)" class="m44ch2tvk"/><path class="ngewc8b9f"/><g filter="url(#iD42Wpb)"><path class="fhsv0pbxv"/><path fill="url(#iwbJKgd)" class="sb03dpbcb"/></g><g filter="url(#ibRmUzd)"><path fill="url(#iByLD6x)" class="ci83lezyt"/></g><path class="z96bu-bfz"/><path fill="url(#izsCf4c)" class="a389bxb8p"/><path class="igmwwqbex"/><g filter="url(#i1VHc0c)"><path fill="url(#iv0m4Sd)" class="r9vrlfe_i"/></g><g filter="url(#iJ9enOb)"><ellipse transform="rotate(-27.914 9.474 12.082)" class="i2ptbhbwe"/><ellipse fill="url(#ijEJYic)" transform="rotate(-27.914 9.474 12.082)" class="xbehvsbpe"/></g><path fill="url(#ippSPde)" class="umvladcex"/><path fill="url(#icWPCYJ)" class="umvladcex"/><path fill="url(#if1hmEb)" class="umvladcex"/><path fill="url(#iovM6Gd)" class="umvladcex"/><path fill="url(#ijQSEXd)" class="a3_8g7bjd"/><path fill="url(#iXlqIIc)" class="a3_8g7bjd"/><g filter="url(#in9vSzb)"><path fill="url(#iUOVBAb)" class="m_qlwg22u"/></g><g filter="url(#iNnXDkb)"><path fill="url(#ijYLs7b)" class="owk-c0thp"/></g><g filter="url(#i2nfead)"><path class="ifxikqb-q"/></g><g filter="url(#ibpzwQe)"><path class="jyto-pf4q"/></g><g filter="url(#ianFj9c)"><path class="btyhst1ne"/></g><g filter="url(#iJdvsab)"><path stroke="url(#ihbnrWc)" class="b04edgqea"/></g><defs><radialGradient id="imIzwGb" cx="0" cy="0" r="1" gradientTransform="matrix(.49622 4.67882 -8.74603 .92758 11.719 19.2)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="yitnujsmh"/><stop offset="1" class="p9u6z5b-m"/></radialGradient><radialGradient id="icKCTfe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.60995 -7.279 2.80725 -1.7779 22.035 30.087)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="jc9tt1bnq"/><stop offset="1" class="vq1hgac7r"/></radialGradient><radialGradient id="i11wEOc" cx="0" cy="0" r="1" gradientTransform="matrix(2.81734 3.45124 -5.56183 4.54028 11.438 20.507)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="c0tn-pbdx"/><stop offset=".826" class="bzu9ssjnw"/></radialGradient><radialGradient id="i3AOkKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14487 1.17029 -.21646 -.21176 24.118 13.1)" gradientUnits="userSpaceOnUse"><stop class="rg6_aq5bn"/><stop offset="1" class="egknc6bjy"/></radialGradient><radialGradient id="i7WEule" cx="0" cy="0" r="1" gradientTransform="rotate(-70.927 22.415 -8.705)scale(3.10812 1.58159)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="ey9rc4x8g"/><stop offset="1" class="h_m9gybkg"/></radialGradient><radialGradient id="iEjqyPV" cx="0" cy="0" r="1" gradientTransform="matrix(-.69262 .16923 -.21445 -.87773 29.82 14.163)" gradientUnits="userSpaceOnUse"><stop class="zc8f0vuwq"/><stop offset="1" class="qpnffl78t"/></radialGradient><radialGradient id="i3ehxDO" cx="0" cy="0" r="1" gradientTransform="matrix(.04347 .30737 -2.37215 .33545 27.375 13.597)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="kaydztigo"/><stop offset="1" class="ojt9l7bfl"/></radialGradient><radialGradient id="iIqiojb" cx="0" cy="0" r="1" gradientTransform="matrix(-.68924 .16508 -.20552 -.85808 30.398 14.474)" gradientUnits="userSpaceOnUse"><stop class="zc8f0vuwq"/><stop offset="1" class="qpnffl78t"/></radialGradient><radialGradient id="iibu57d" cx="0" cy="0" r="1" gradientTransform="rotate(81.791 5.946 23.106)scale(.30294 2.38305)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="kaydztigo"/><stop offset="1" class="ojt9l7bfl"/></radialGradient><radialGradient id="isqey2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.69149 .15913 -.19118 -.83072 30.116 14.935)" gradientUnits="userSpaceOnUse"><stop class="zc8f0vuwq"/><stop offset="1" class="qpnffl78t"/></radialGradient><radialGradient id="iNiuJ5v" cx="0" cy="0" r="1" gradientTransform="matrix(.0523 .34914 -3.63628 .54474 27.668 14.292)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="kaydztigo"/><stop offset="1" class="ojt9l7bfl"/></radialGradient><radialGradient id="i76RUWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.96409 .10438 -.0402 -.37127 29.398 15.74)" gradientUnits="userSpaceOnUse"><stop class="ckhvlybux"/><stop offset="1" class="ncljgdjmn"/></radialGradient><radialGradient id="irZBWlb" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 4.931 23.543)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="c7v8k2b1p"/><stop offset="1" class="j-921gbzo"/></radialGradient><radialGradient id="iciIvOd" cx="0" cy="0" r="1" gradientTransform="matrix(.92109 -.74564 1.75363 2.16625 21.985 16.898)" gradientUnits="userSpaceOnUse"><stop class="px5vhfjeq"/><stop offset="1" class="moi_eqb0y"/></radialGradient><radialGradient id="iVGz4dN" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.17059 -4.07047 0 24.286 17.387)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="fs0lcjope"/><stop offset="1" class="tlllf-zgd"/><stop offset="1" class="omr_ktb6b"/></radialGradient><radialGradient id="iPWlegb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.75 -3.6875 0 25.849 17.715)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="tu7zelskj"/><stop offset="1" class="h4j2h-grr"/></radialGradient><radialGradient id="ilnaKpN" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -1.175 20.602)scale(2.71243 3.22216)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iQY8UTV" cx="0" cy="0" r="1" gradientTransform="matrix(1.85934 .58437 -1.8028 5.7362 4.937 15.16)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iaTARtd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.58356 0 0 -11.6463 16.1 13.357)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="imSjNGv" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28737 15.64522 -12.95611 -1.0661 14.555 5.91)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="i4ADrdE" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44615 1.78961 0 15.646 11.703)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iautWNc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 10.736 1.03)scale(1.37806 1.49965)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="i0qfvad" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.213 7.567)scale(10.7205 27.3855)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="ibdmsje" cx="0" cy="0" r="1" gradientTransform="rotate(-33.032 16.177 -5.62)scale(6.11814 2.23967)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="i0Nz2He" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 5.365 13.74)scale(3.15894 1.26276)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iCU6DKP" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1952 3.63057 -2.99734 -1.81232 15.62 7.086)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="i1BDPUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3074 -.96613 0 13.151 15.07)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="ispWsLd" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 5.082 8.628)scale(2.10736 3.3867)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i1JKCgm" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.90764 3.65167 0 12.564 17.814)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iTOgnbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.4093 11.1506 0 5.978 9.714)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iuO3Avd" cx="0" cy="0" r="1" gradientTransform="matrix(.14362 -3.16411 5.60618 .25446 18.685 11.364)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="ieZJXYd" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 9.386 -.925)scale(3.55544 2.60987)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="i7dxXId" cx="0" cy="0" r="1" gradientTransform="matrix(1.13983 1.8575 -4.3011 2.6393 11.424 1.455)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="i1kylTm" cx="0" cy="0" r="1" gradientTransform="matrix(-2.77193 0 0 -1.02877 12.883 4.3)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="ipnGuxw" cx="0" cy="0" r="1" gradientTransform="matrix(4.05272 -6.41682 7.10917 4.49 5.725 9.265)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iuNExhS" cx="0" cy="0" r="1" gradientTransform="matrix(4.09056 .47814 -.20019 1.71264 14.766 7.244)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="idAPySc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02171 -1.62515 0 15.312 12.203)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iwbJKgd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 10.526 2.475)scale(.47639 .65587)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izsCf4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02177 -1.62523 0 9.816 12.203)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ijEJYic" cx="0" cy="0" r="1" gradientTransform="matrix(-.00974 -.62221 .74792 -.01171 9.455 12.479)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="icWPCYJ" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.132 18.228)scale(2.93381 2.79908)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="if1hmEb" cx="0" cy="0" r="1" gradientTransform="matrix(.99207 -1.36146 1.14118 .83156 18.833 12.906)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iovM6Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73922 -1.95249 2.6088 .9877 18.977 13.123)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iXlqIIc" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -2.133 8.651)scale(2.66559 2.62052)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iUOVBAb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15414 .19811 -.08738 -.50904 6.375 13.03)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><linearGradient id="iIUFVGc" x1="12.564" x2="12.564" y1="30.087" y2="25.061" gradientUnits="userSpaceOnUse"><stop class="ht3cpt4fm"/><stop offset="1" class="kd5wnje_y"/></linearGradient><linearGradient id="imC7Hce" x1="27.823" x2="27.69" y1="15.71" y2="14.454" gradientUnits="userSpaceOnUse"><stop offset=".217" class="gm2kw57qc"/><stop offset="1" class="g0b8l_b3k"/></linearGradient><linearGradient id="iAR93uc" x1="28.41" x2="28.284" y1="15.984" y2="14.758" gradientUnits="userSpaceOnUse"><stop offset=".217" class="gm2kw57qc"/><stop offset="1" class="g0b8l_b3k"/></linearGradient><linearGradient id="i9Fkrte" x1="28.123" x2="28.005" y1="16.39" y2="15.207" gradientUnits="userSpaceOnUse"><stop offset=".217" class="gm2kw57qc"/><stop offset="1" class="g0b8l_b3k"/></linearGradient><linearGradient id="ivfZt5b" x1="24.211" x2="24.365" y1="13.966" y2="15.089" gradientUnits="userSpaceOnUse"><stop class="ddkf-bcrd"/><stop offset="1" class="edu27viuq"/></linearGradient><linearGradient id="imXNWSE" x1="23.665" x2="23.665" y1="18.703" y2="18.079" gradientUnits="userSpaceOnUse"><stop offset=".316" class="f3g2sacre"/><stop offset="1" class="wyf_7nbxp"/></linearGradient><linearGradient id="i6W39Bd" x1="24.536" x2="24.536" y1="19.402" y2="38.715" gradientUnits="userSpaceOnUse"><stop class="xx_iqybrp"/><stop offset=".621" class="t57nv_-5z"/></linearGradient><linearGradient id="irEYaRb" x1="23.494" x2="23.494" y1="18.243" y2="19.277" gradientUnits="userSpaceOnUse"><stop offset=".366" class="tu7zelskj"/><stop offset="1" class="h4j2h-grr"/></linearGradient><linearGradient id="iuiR1Tb" x1="19.058" x2="13.577" y1="15.479" y2="15.479" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iQkuQUb" x1="12.623" x2="12.623" y1="21.23" y2="20.424" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="imqSvxb" x1="13.62" x2="12.564" y1="14.206" y2="14.25" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iVIpMxe" x1="12.564" x2="12.564" y1="15.641" y2="15.055" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iNiB1xd" x1="12.564" x2="12.564" y1="11.92" y2="12.923" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iCoSAue" x1="11.051" x2="11.452" y1="17.619" y2="16.568" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iE7Qucd" x1="21.193" x2="6.569" y1="6.225" y2="6.225" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iByLD6x" x1="16.292" x2="15.897" y1="12.271" y2="12.514" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iv0m4Sd" x1="10.753" x2="10.358" y1="12.271" y2="12.514" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ippSPde" x1="20.669" x2="19.15" y1="12.305" y2="15.045" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="ijQSEXd" x1="5.197" x2="7.034" y1="13.191" y2="13.031" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="ijYLs7b" x1="19.385" x2="19.385" y1="11.824" y2="14.221" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="ihbnrWc" x1="28.417" x2="23.596" y1="15.8" y2="16.307" gradientUnits="userSpaceOnUse"><stop class="ew0-bx6ou"/><stop offset="1" class="ww6mb0bgh"/></linearGradient><filter id="icgwOLb" width="7.879" height="3.847" x="21.44" y="13.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.137255 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3789"/></filter><filter id="iM5nyke" width="13.871" height="15.742" x="6.188" y="5.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3789"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3789" result="effect2_innerShadow_4002_3789"/></filter><filter id="iYMQozd" width="4.2" height="5.652" x="10.285" y="11.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".5"/></filter><filter id="iJOwMhe" width="2.764" height="4.052" x="11.182" y="11.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".1"/></filter><filter id="iFWG88y" width="4.553" height="1.851" x="10.287" y="16.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".05"/></filter><filter id="iiVcwzd" width="16.211" height="10.394" x="4.458" y="1.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3789"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3789" result="effect2_innerShadow_4002_3789"/></filter><filter id="iHlbTRd" width="2.919" height="1.447" x="14.565" y="8.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3789"/></filter><filter id="i03pGsL" width="2.919" height="1.429" x="7.946" y="8.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3789"/></filter><filter id="i4ZQjvb" width="8.662" height="7.916" x="4.721" y="2.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3789"/><feGaussianBlur result="effect2_foregroundBlur_4002_3789" stdDeviation=".25"/></filter><filter id="iPr3cic" width="8.444" height="7.66" x="12.116" y="3.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3789"/><feGaussianBlur result="effect2_foregroundBlur_4002_3789" stdDeviation=".25"/></filter><filter id="iD42Wpb" width=".939" height=".825" x="14.413" y="11.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".05"/></filter><filter id="ibRmUzd" width="1.019" height="1.047" x="15.497" y="11.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".1"/></filter><filter id="i1VHc0c" width="1.138" height="1.206" x="9.902" y="11.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".1"/></filter><filter id="iJ9enOb" width="1.098" height=".835" x="8.925" y="11.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".05"/></filter><filter id="in9vSzb" width="1.544" height="2.867" x="4.971" y="11.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".125"/></filter><filter id="iNnXDkb" width="2.192" height="3.397" x="18.289" y="11.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".25"/></filter><filter id="i2nfead" width="2.834" height="1.267" x="7.941" y="8.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".125"/></filter><filter id="ibpzwQe" width="2.834" height="1.267" x="14.589" y="8.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".125"/></filter><filter id="ianFj9c" width="6.742" height="3.896" x="13.616" y="4.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".5"/></filter><filter id="iJdvsab" width="5.722" height="1.374" x="23.416" y="15.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3789" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-tipping-hand-dark" /></template>
<style>
.a3_8g7bjd {
  d: path("M6.2 11.016a2.027 2.027 0 0 0 .174 4.03a98 98 0 0 1-.175-4.03");
}

.a389bxb8p {
  d: path("M9.814 11.602a1.124 1.124 0 0 0-1.083 1.42h2.17a1.2 1.2 0 0 0 .042-.296a1.13 1.13 0 0 0-1.13-1.124");
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a6g-43b-p {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M12.857 6.285a3 3 0 0 1-.084-.173a.84.84 0 0 0-.774-.527h-1.604c-2.324 0-4.207 1.905-4.207 4.256v.346c-.429-.326-.967-1.013-.967-2.125c0-1.35.984-2.032 1.612-2.467c.178-.123.327-.226.417-.32l.125-.131C7.815 4.677 8.6 3.845 9.97 3.48c.757-.2 1.526-.23 2.11-.2c.471.025.804.433.804.906v2.08z");
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ai6m5ac0v {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m19.128 10.399l-.036-.795c-.014-.962-.808-1.755-1.77-1.796h-1.763a3.05 3.05 0 0 1-2.675-1.586s-.151-.35-.248-.907c-.17-.989.745-1.717 1.735-1.553c1.32.22 2.941.648 4.102 1.405c2.196 1.433 1.812 4.015.655 5.232");
}

.ajf4f4e7i {
  fill: var(--svg-color--4f3632, #4F3632);
  d: path("M25.752 14.017c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.877-.118 1.186-.216c.242-.076.496-.195.955-.282c.917-.102 1.759-.206 2.235-.308a.825.825 0 0 0-.346-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b04edgqea {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.79 16.424c.85-.058 3.032-.264 4.973-.624");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.btyhst1ne {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M17.844 6.306h-2.62a.61.61 0 1 1 .097-1.21c.68.108 1.583.26 2.187.41c1.367.338 1.745 1.004 1.85 1.478a1.9 1.9 0 0 0-1.514-.678");
}

.bzu9ssjnw {
  stop-color: var(--svg-color--472420, #472420);
}

.c0tn-pbdx {
  stop-color: var(--svg-color--32171c, #32171C);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c7v8k2b1p {
  stop-color: var(--svg-color--5d4b48, #5D4B48);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ci83lezyt {
  d: path("M16.316 12.578a1.06 1.06 0 0 0-.292-.583l-.327.36l.148.287z");
}

.cis39obud {
  d: path("M12.857 6.285a3 3 0 0 1-.084-.173a.84.84 0 0 0-.774-.527h-1.604c-2.324 0-4.207 1.905-4.207 4.256v.346c-.429-.326-.967-1.013-.967-2.125c0-1.35.984-2.032 1.612-2.467c.178-.123.327-.226.417-.32l.125-.131C7.815 4.677 8.6 3.845 9.97 3.48c.757-.2 1.526-.23 2.11-.2c.471.025.804.433.804.906v2.08z");
}

.ckhvlybux {
  stop-color: var(--svg-color--6a5957, #6A5957);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cxzhkxbuv {
  d: path("M12.564 20.036c-5.523 0-10 4.477-10 10v.05h20v-.05c0-5.523-4.477-10-10-10");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.ddkf-bcrd {
  stop-color: var(--svg-color--504645, #504645);
}

.dm_q_zbtq {
  d: path("m19.128 10.399l-.036-.795c-.014-.962-.808-1.755-1.77-1.796h-1.763a3.05 3.05 0 0 1-2.675-1.586s-.151-.35-.248-.907c-.17-.989.745-1.717 1.735-1.553c1.32.22 2.941.648 4.102 1.405c2.196 1.433 1.812 4.015.655 5.232");
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.du4kig3ov {
  d: path("M22.212 13.876c-.554.648-.74 1.417-.761 1.758l1.847-.102l.887-1.183c.29-.383.54-1.02-.035-1.442c-.466-.342-.945-.066-1.102.106a28 28 0 0 0-.836.863");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.edu27viuq {
  stop-color: var(--svg-color--504645, #504645);
  stop-opacity: 0;
}

.egknc6bjy {
  stop-color: var(--svg-color--4c3330, #4C3330);
}

.emqx9pqag {
  d: path("M18.686 14.93a2.07 2.07 0 0 0 1.14-.388v1.172c0 1.125-.67 2.127-1.69 2.543q.324-.687.436-1.486z");
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ew0-bx6ou {
  stop-color: var(--svg-color--5e4a49, #5E4A49);
}

.ey9rc4x8g {
  stop-color: var(--svg-color--3e2f2d, #3E2F2D);
  stop-opacity: 0;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f3g2sacre {
  stop-color: var(--svg-color--b33f0e, #B33F0E);
}

.f72h3jkbj {
  fill: var(--svg-color--202020, #202020);
  d: path("M8.269 9.467a3.5 3.5 0 0 1 2.19-.453a.35.35 0 1 1-.085.694a2.8 2.8 0 0 0-1.747.358a2 2 0 0 0-.115.075l-.004.003a.35.35 0 0 1-.427-.552z");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fhsv0pbxv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.232 11.84c.08.107-.087.237-.278.38c-.19.142-.331.242-.411.135s.009-.31.2-.452c.19-.142.409-.17.489-.063");
}

.fs0lcjope {
  stop-color: var(--svg-color--f26f40, #F26F40);
}

.ft5dv1b6b {
  fill: none;
}

.g0b8l_b3k {
  stop-color: var(--svg-color--3f2534, #3F2534);
  stop-opacity: 0;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g7d3phb7y {
  fill: var(--svg-color--202020, #202020);
  d: path("M17.265 9.604c-.22-.192-.477-.396-.866-.518c-.383-.12-.863-.153-1.527-.072a.35.35 0 1 0 .085.694c.606-.075.977-.036 1.232.044c.25.079.42.206.617.379a.35.35 0 0 0 .459-.527");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gki0s6b2a {
  fill: var(--svg-color--4b3330, #4B3330);
  fill-rule: evenodd;
  d: path("M29.807 14.181a.85.85 0 0 1-.69.985a21 21 0 0 0-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.083.716-.142a.85.85 0 0 1 .984.69");
}

.gm2kw57qc {
  stop-color: var(--svg-color--3f2534, #3F2534);
}

.h_m9gybkg {
  stop-color: var(--svg-color--3e2f2d, #3E2F2D);
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h4j2h-grr {
  stop-color: var(--svg-color--fa9319, #FA9319);
  stop-opacity: 0;
}

.h7qd-yz4i {
  d: path("M21.197 17.548a.25.25 0 0 1 .25-.25h4.094a.25.25 0 0 1 .25.25v1.64h-4.594z");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.ht3cpt4fm {
  stop-color: var(--svg-color--da5129, #DA5129);
}

.i2ptbhbwe {
  cx: 9.474px;
  cy: 12.082px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.491px;
  ry: 0.248px;
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ifxikqb-q {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.316 9.82c.324-.233 1.13-.642 2.085-.481");
}

.igmwwqbex {
  fill: var(--svg-color--000, #000);
  d: path("M10.457 12.726a.64.64 0 0 0-.643-.644a.64.64 0 0 0-.573.94h1.14a.64.64 0 0 0 .076-.296");
}

.igyf75bxe {
  fill-rule: evenodd;
  d: path("M29.807 14.181a.85.85 0 0 1-.69.985a21 21 0 0 0-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.083.716-.142a.85.85 0 0 1 .984.69");
}

.j-921gbzo {
  stop-color: var(--svg-color--5d4b48, #5D4B48);
  stop-opacity: 0;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.javqacc3k {
  width: 4.898px;
  height: 6.68px;
  x: 10.127px;
  y: 17.009px;
  rx: 2.449px;
}

.jc9tt1bnq {
  stop-color: var(--svg-color--a62807, #A62807);
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jyto-pf4q {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.049 9.761c-.324-.232-1.13-.64-2.085-.48");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kaydztigo {
  stop-color: var(--svg-color--695856, #695856);
}

.kd5wnje_y {
  stop-color: var(--svg-color--e57129, #E57129);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.lz4e7hb7r {
  fill: var(--svg-color--4b3330, #4B3330);
  fill-rule: evenodd;
  d: path("M30.385 14.51a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693c1.02-.096 1.89-.259 2.552-.383l.459-.084a.85.85 0 0 1 .984.69");
}

.m_qlwg22u {
  d: path("M6.16 11.847a1.204 1.204 0 0 0 .105 2.367q-.067-1.184-.105-2.367");
}

.m44ch2tvk {
  d: path("M15.315 11.602a1.124 1.124 0 0 1 1.083 1.42h-2.172a1.128 1.128 0 0 1 1.088-1.42");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.moi_eqb0y {
  stop-color: var(--svg-color--4a3838, #4A3838);
  stop-opacity: 0;
}

.mwt29lbuz {
  fill-rule: evenodd;
  d: path("M30.385 14.51a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693c1.02-.096 1.89-.259 2.552-.383l.459-.084a.85.85 0 0 1 .984.69");
}

.ncljgdjmn {
  stop-color: var(--svg-color--6a5957, #6A5957);
  stop-opacity: 0;
}

.ngewc8b9f {
  fill: var(--svg-color--000, #000);
  d: path("M14.67 12.726c0-.358.287-.644.645-.644a.64.64 0 0 1 .572.94h-1.14a.6.6 0 0 1-.076-.296");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojt9l7bfl {
  stop-color: var(--svg-color--695856, #695856);
  stop-opacity: 0;
}

.omr_ktb6b {
  stop-color: var(--svg-color--bf4617, #BF4617);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.owk-c0thp {
  d: path("M18.789 14.22q.072-1.197.14-2.396a1.203 1.203 0 0 1-.14 2.397");
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p3ziwhb9q {
  fill: var(--svg-color--452a32, #452A32);
  d: path("M21.44 15.789h4.015v2.016H21.44z");
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.p9u6z5b-m {
  stop-color: var(--svg-color--a25018, #A25018);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pjfcxrj0f {
  d: path("M6.488 16.839a4.93 4.93 0 0 0 4.893 4.289h2.376a4.93 4.93 0 0 0 4.893-4.29c.149-2.372.298-4.734.409-7.105a1.825 1.825 0 0 0-1.737-1.804h-1.763a3.05 3.05 0 0 1-2.786-1.817a.84.84 0 0 0-.774-.527h-1.603c-2.325 0-4.208 1.905-4.208 4.256c0 2.343.146 4.648.3 6.998");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.px5vhfjeq {
  stop-color: var(--svg-color--4a3838, #4A3838);
}

.q0a5xac1f {
  d: path("M25.752 14.017c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.877-.118 1.186-.216c.242-.076.496-.195.955-.282c.917-.102 1.759-.206 2.235-.308a.825.825 0 0 0-.346-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qpnffl78t {
  stop-color: var(--svg-color--6a5857, #6A5857);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.r9vrlfe_i {
  d: path("M10.84 12.594c0-.363-.295-.605-.375-.679l-.363.352l.224.455z");
}

.rg6_aq5bn {
  stop-color: var(--svg-color--695855, #695855);
}

.rr06i0p7e {
  d: path("M18.678 4.991a2.92 2.92 0 0 1 1.596 1.324a2.98 2.98 0 0 1-.134 3.181c-.22.325-.34.71-.34 1.101v1.497a2.2 2.2 0 0 0-.84-.338l.098-2.023a1.825 1.825 0 0 0-1.736-1.804h-1.763a3.05 3.05 0 0 1-2.786-1.817a.84.84 0 0 0-.774-.527h-1.603c-2.325 0-4.208 1.905-4.208 4.256l.038 1.936c-.32.047-.654.154-.907.332v-1.512c0-.391-.12-.776-.34-1.1a3.01 3.01 0 0 1-.18-3.08a2.95 2.95 0 0 1 1.636-1.42A3.38 3.38 0 0 0 8.178 3.6a2.93 2.93 0 0 1 3.64-1.149c.481.21 1.022.21 1.503 0a3 3 0 0 1 1.149-.236a2.93 2.93 0 0 1 2.505 1.425a3.18 3.18 0 0 0 1.703 1.351");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.sb03dpbcb {
  d: path("M15.232 11.84c.08.107-.087.237-.278.38c-.19.142-.331.242-.411.135s.009-.31.2-.452c.19-.142.409-.17.489-.063");
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t57nv_-5z {
  stop-color: var(--svg-color--d36028, #D36028);
}

.tlllf-zgd {
  stop-color: var(--svg-color--bb5028, #BB5028);
}

.tu7zelskj {
  stop-color: var(--svg-color--fa9319, #FA9319);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.umvladcex {
  d: path("M18.762 15.045q.126-2.01.233-4.019a2.027 2.027 0 0 1-.233 4.02");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vq1hgac7r {
  stop-color: var(--svg-color--a62807, #A62807);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w4uu1soap {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m12.059 12.703l-.744 2.315c-.128.476.177.953.61.953h.921c.432 0 .737-.484.61-.953l-.623-2.315c-.133-.513-.635-.513-.774 0");
}

.wf3_gcc9s {
  d: path("M6.442 14.93a2.07 2.07 0 0 1-1.139-.388v1.172c0 1.125.67 2.127 1.689 2.543a5.2 5.2 0 0 1-.436-1.486z");
}

.wmrlrdbfz {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M10.854 16.524a3.7 3.7 0 0 0 1.71.405a3.7 3.7 0 0 0 1.71-.405a.27.27 0 0 1 .319.052a.25.25 0 0 1 .027.32l-.062-.042a2.38 2.38 0 0 1-1.994 1.065a2.38 2.38 0 0 1-1.994-1.065zm0 0a.27.27 0 0 0-.32.055a.25.25 0 0 0-.026.317z");
}

.wpyfiqb4o {
  fill: var(--svg-color--402929, #402929);
  d: path("m12.083 12.457l-.67 2.315c-.136.476.192.952.656.952h.99c.465 0 .793-.483.656-.952l-.67-2.315c-.143-.513-.812-.513-.962 0");
}

.ww6mb0bgh {
  stop-color: var(--svg-color--5e4a49, #5E4A49);
  stop-opacity: 0;
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyf_7nbxp {
  stop-color: var(--svg-color--b33f0e, #B33F0E);
  stop-opacity: 0;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbehvsbpe {
  cx: 9.474px;
  cy: 12.082px;
  rx: 0.491px;
  ry: 0.248px;
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xp5ouwjaz {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.575 11.26c.823 0 1.517.567 1.706 1.333a.345.345 0 0 1-.337.43h-2.81a.29.29 0 0 1-.286-.343a1.76 1.76 0 0 1 1.727-1.42");
}

.xx_iqybrp {
  stop-color: var(--svg-color--e88222, #E88222);
}

.xyj2y_0yr {
  fill: var(--svg-color--4b3330, #4B3330);
  fill-rule: evenodd;
  d: path("M30.114 15.067a.85.85 0 0 1-.773.921a28 28 0 0 0-1.26.162l-.03.004a53 53 0 0 1-1.786.231a.85.85 0 1 1-.183-1.69c.622-.067 1.205-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.y48d6ebxt {
  d: path("M20.298 19.043a.8.8 0 0 1 .8-.8h4.791a.8.8 0 0 1 .8.8v11.044h-6.39z");
}

.ycbp9gizk {
  fill-rule: evenodd;
  d: path("M30.114 15.067a.85.85 0 0 1-.773.921a28 28 0 0 0-1.26.162l-.03.004a53 53 0 0 1-1.786.231a.85.85 0 1 1-.183-1.69c.622-.067 1.205-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.yitnujsmh {
  stop-color: var(--svg-color--a25018, #A25018);
}

.yujqq5-iy {
  d: path("M12.564 17.004c-.64 0-1.24-.15-1.745-.413c-.172-.088-.358.106-.249.263a2.38 2.38 0 0 0 1.994 1.065c.837 0 1.572-.426 1.994-1.065c.109-.163-.077-.351-.25-.263a3.76 3.76 0 0 1-1.744.413");
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z96bu-bfz {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.553 11.26a1.76 1.76 0 0 0-1.706 1.333c-.056.22.112.43.337.43h2.81a.29.29 0 0 0 .286-.343a1.765 1.765 0 0 0-1.727-1.42");
}

.zc8f0vuwq {
  stop-color: var(--svg-color--6a5857, #6A5857);
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zt4lf7b2y {
  d: path("m12.083 12.457l-.67 2.315c-.136.476.192.952.656.952h.99c.465 0 .793-.483.656-.952l-.67-2.315c-.143-.513-.812-.513-.962 0");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
