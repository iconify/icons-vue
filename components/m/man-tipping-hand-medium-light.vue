<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#idh2fsd)" class="qcgh4gb9v"/><path fill="url(#inBwZuc)" class="qcgh4gb9v"/><path fill="url(#irHdxCe)" class="qcgh4gb9v"/><path fill="url(#izX8uTd)" class="qcgh4gb9v"/><rect fill="url(#iOzoq4c)" class="gmo09s50p"/><rect fill="url(#in8qXkb)" class="gmo09s50p"/><path class="aya26o47f"/><path fill="url(#iV1qGJe)" class="jhda4212k"/><path fill="url(#iZOBBeb)" class="jhda4212k"/><path clip-rule="evenodd" class="nycnkg-cp"/><path fill="url(#i7ro5ne)" clip-rule="evenodd" class="ptj8svxtg"/><path fill="url(#i6MpWTd)" clip-rule="evenodd" class="ptj8svxtg"/><path fill="url(#icslLRc)" clip-rule="evenodd" class="ptj8svxtg"/><path clip-rule="evenodd" class="r6b0mzudl"/><path fill="url(#iHSveMc)" clip-rule="evenodd" class="djszrn9ws"/><path fill="url(#iBJRYNT)" clip-rule="evenodd" class="djszrn9ws"/><path fill="url(#iru7qhw)" clip-rule="evenodd" class="djszrn9ws"/><path clip-rule="evenodd" class="rgelk8b2a"/><path fill="url(#i34uX0d)" clip-rule="evenodd" class="nbzkw-med"/><path fill="url(#ii0AJgc)" clip-rule="evenodd" class="nbzkw-med"/><path fill="url(#islwMsd)" clip-rule="evenodd" class="nbzkw-med"/><g filter="url(#iGSVp0V)"><path clip-rule="evenodd" class="fwnss0e3m"/><path fill="url(#iQ40Cye)" clip-rule="evenodd" class="dc_-el2vm"/><path fill="url(#iGrRhND)" clip-rule="evenodd" class="dc_-el2vm"/><path fill="url(#ipRsbRb)" clip-rule="evenodd" class="dc_-el2vm"/></g><g filter="url(#i41IBOc)"><path class="zlv0xcc8i"/><path fill="url(#iq9eskc)" class="furegib2d"/><path fill="url(#iu30Jvd)" class="furegib2d"/><path fill="url(#isVyl7s)" class="furegib2d"/></g><path fill="url(#iEWwjKb)" class="ukh84abxq"/><path fill="url(#iBjVL9d)" class="ukh84abxq"/><g filter="url(#iEZbbbd)"><path fill="url(#i2tvtje)" class="xm7l4wblc"/><path fill="url(#ixyVNac)" class="xm7l4wblc"/><path fill="url(#iJmU0Ke)" class="xm7l4wblc"/><path fill="url(#ibQWfRc)" class="xm7l4wblc"/></g><g filter="url(#ijsyNcc)"><path stroke="url(#iGCBfwb)" class="m0opo6bbh"/></g><g filter="url(#it2SDYc)"><circle fill="url(#iodnurd)" class="jo9kslbvg"/></g><g filter="url(#iatXJwc)"><circle fill="url(#iF0sLad)" class="a1oixybvc"/></g><g filter="url(#iBHVgLb)"><circle fill="url(#i0FWTLc)" class="c0-_whbvj"/><circle fill="url(#iw6ldOl)" class="c0-_whbvj"/></g><g filter="url(#izIXqwd)"><circle class="ptt1l_01g"/><circle fill="url(#ivG46ie)" class="fv-l3eb9p"/><circle fill="url(#irq2ACb)" class="fv-l3eb9p"/></g><g filter="url(#i4sNehb)"><path fill="url(#iJODNib)" class="c6l8th9lj"/><path fill="url(#iwp8x8d)" class="c6l8th9lj"/><path fill="url(#ipC7G6N)" class="c6l8th9lj"/><path fill="url(#iQfF2Ug)" class="c6l8th9lj"/><path fill="url(#iEevQYd)" class="c6l8th9lj"/></g><g filter="url(#i6nkfud)"><path class="ll4x9cbml"/><path fill="url(#iMf3CAe)" class="x-ga_webx"/><path fill="url(#iSRKOJd)" class="x-ga_webx"/><path fill="url(#iBWzKbb)" class="x-ga_webx"/><path fill="url(#iIDfhmg)" class="x-ga_webx"/><path fill="url(#id6Pyed)" class="x-ga_webx"/></g><path fill="url(#ivzw1sb)" class="x-ga_webx"/><path fill="url(#ixFWlVd)" class="x-ga_webx"/><g filter="url(#iVZiFAc)"><path class="zgxkbfbem"/></g><g filter="url(#iK2Twlc)"><path class="xzax2hcxn"/><path fill="url(#iWvr2Td)" class="wom4lqbtj"/><path fill="url(#i784nNO)" class="wom4lqbtj"/><path fill="url(#iKQd3Pd)" class="wom4lqbtj"/></g><path fill="url(#iN27kDe)" class="wom4lqbtj"/><path stroke="url(#iiSAyAa)" class="ac5fyukrd"/><g filter="url(#irpNjOd)"><path class="yp2ng6blh"/></g><g filter="url(#i99r3Zb)"><path class="k87it816j"/></g><path class="lsm4wo0il"/><path fill="url(#iEVq5tb)" class="sbt-tumyu"/><path class="is-__hh9o"/><g filter="url(#iLIiUee)"><path class="nqt07ssya"/><path fill="url(#iO0krGd)" class="kg26iac7f"/></g><g filter="url(#ixkIhwc)"><path fill="url(#ioc3Cqc)" class="m5fjdpbci"/></g><path class="gojugjv6o"/><path fill="url(#iaH0m6L)" class="q-h41ezkf"/><path class="ulfybv1yg"/><g filter="url(#iy5T0ke)"><path fill="url(#iPMHfcd)" class="au4n6sbel"/></g><g filter="url(#iPqOjWb)"><ellipse transform="rotate(-27.914 9.263 11.907)" class="u7ohzz30e"/><ellipse fill="url(#ioEq83F)" transform="rotate(-27.914 9.263 11.907)" class="cgp3v0siv"/></g><g filter="url(#ii8wdSd)"><path stroke="url(#ile5rCe)" class="o28tdfdvf"/></g><g filter="url(#i6jsK7R)"><path stroke="url(#i7j9ZOe)" class="zycvbibcr"/></g><defs><radialGradient id="inBwZuc" cx="0" cy="0" r="1" gradientTransform="rotate(-128.9 17.743 9.605)scale(14.3752 17.7454)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="qttx_q5hd"/><stop offset="1" class="jj70p7yrg"/></radialGradient><radialGradient id="irHdxCe" cx="0" cy="0" r="1" gradientTransform="rotate(80.311 -5.866 15.826)scale(6.49895 15.3845)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y57vb-6vx"/><stop offset="1" class="k_v_c_b6y"/></radialGradient><radialGradient id="izX8uTd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.91897 -8.2177 4.4235 -2.64783 21.14 29.476)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="htrw0pbkw"/><stop offset="1" class="hsbr_ca-x"/></radialGradient><radialGradient id="iOzoq4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.21875 -4.41943 0 12.394 20.633)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="f_gwqccqg"/><stop offset="1" class="ywfp1px4j"/></radialGradient><radialGradient id="in8qXkb" cx="0" cy="0" r="1" gradientTransform="rotate(65.11 -10.246 19.087)scale(4.82627 5.58433)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="zhvue1b_t"/><stop offset=".914" class="rq0vvgb8y"/></radialGradient><radialGradient id="iV1qGJe" cx="0" cy="0" r="1" gradientTransform="rotate(131.424 8.912 12.022)scale(2.12546 1.04757)" gradientUnits="userSpaceOnUse"><stop class="d47_3hb-i"/><stop offset=".836" class="a3oso8z0y"/></radialGradient><radialGradient id="iZOBBeb" cx="0" cy="0" r="1" gradientTransform="rotate(-70.927 22.324 -8.577)scale(3.10812 1.58159)" gradientUnits="userSpaceOnUse"><stop offset=".854" class="f7n3i4bhd"/><stop offset="1" class="szdg8rbev"/></radialGradient><radialGradient id="i7ro5ne" cx="0" cy="0" r="1" gradientTransform="matrix(-.89575 .18001 -.22857 -1.13739 29.64 14.163)" gradientUnits="userSpaceOnUse"><stop class="xzb70-bgi"/><stop offset="1" class="ciwrelrrj"/></radialGradient><radialGradient id="icslLRc" cx="0" cy="0" r="1" gradientTransform="rotate(83.723 6.01 21.973)scale(.39776 3.06956)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="lknsjyjnn"/><stop offset="1" class="lno0m-9jy"/></radialGradient><radialGradient id="iHSveMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.89138 .1756 -.21889 -1.11118 30.216 14.472)" gradientUnits="userSpaceOnUse"><stop class="xzb70-bgi"/><stop offset="1" class="ciwrelrrj"/></radialGradient><radialGradient id="iru7qhw" cx="0" cy="0" r="1" gradientTransform="matrix(.04834 .30469 -2.39683 .38026 27.779 14.023)" gradientUnits="userSpaceOnUse"><stop offset=".431" class="lknsjyjnn"/><stop offset="1" class="lno0m-9jy"/></radialGradient><radialGradient id="i34uX0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.89428 .16927 -.20335 -1.07433 29.935 14.935)" gradientUnits="userSpaceOnUse"><stop class="xzb70-bgi"/><stop offset="1" class="ciwrelrrj"/></radialGradient><radialGradient id="islwMsd" cx="0" cy="0" r="1" gradientTransform="matrix(.0434 .28906 -2.36234 .35465 27.495 14.402)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="lknsjyjnn"/><stop offset="1" class="lno0m-9jy"/></radialGradient><radialGradient id="iQ40Cye" cx="0" cy="0" r="1" gradientTransform="rotate(169.423 13.843 9.188)scale(.90027 1.06791)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="iGrRhND" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 4.84 23.437)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="iq9eskc" cx="0" cy="0" r="1" gradientTransform="rotate(169.423 13.843 9.188)scale(.90027 1.06791)" gradientUnits="userSpaceOnUse"><stop class="apy9n4beb"/><stop offset="1" class="nmfv5s6hy"/></radialGradient><radialGradient id="iu30Jvd" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 4.84 23.437)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="zgnc2ob4f"/><stop offset="1" class="ql8ba7bmn"/></radialGradient><radialGradient id="iEWwjKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05458 -2.63643 0 24.104 17.387)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="agu36v23f"/><stop offset="1" class="iguvvnbvp"/></radialGradient><radialGradient id="iJmU0Ke" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1875 0 0 -.57813 24.721 19.227)" gradientUnits="userSpaceOnUse"><stop class="plpsytzme"/><stop offset="1" class="r1ahmww7a"/></radialGradient><radialGradient id="iodnurd" cx="0" cy="0" r="1" gradientTransform="matrix(2.22935 0 0 3.90139 4.23 12.895)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iw6ldOl" cx="0" cy="0" r="1" gradientTransform="matrix(1.05023 -.76473 .87284 1.1987 18.91 12.559)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="ivG46ie" cx="0" cy="0" r="1" gradientTransform="matrix(1.04333 -1.91895 1.12316 .61067 18.384 13.939)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="irq2ACb" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -6.46 28.864)scale(.46348 .59749)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iwp8x8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41492 13.36913 -12.77286 -1.35181 13.834 9.43)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="mx6r32s2r"/><stop offset=".835" class="a-e0cj8zq"/><stop offset="1" class="j61mf2btk"/></radialGradient><radialGradient id="iQfF2Ug" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.6605 2.04368 0 15.363 11.28)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iEevQYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.76694 2.19734 0 9.572 11.238)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iMf3CAe" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 7.778 5.73)scale(7.122 12.1116)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iBWzKbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.08489 -2.36479 1.1614 -.0417 7.056 8.506)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iIDfhmg" cx="0" cy="0" r="1" gradientTransform="matrix(1.09144 -2.49818 2.03747 .89016 17.752 10.688)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="id6Pyed" cx="0" cy="0" r="1" gradientTransform="matrix(1.26122 1.56495 -1.38173 1.11357 11.398 1.969)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="ivzw1sb" cx="0" cy="0" r="1" gradientTransform="matrix(.23042 .99497 -1.63573 .37881 13.265 1.969)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="ixFWlVd" cx="0" cy="0" r="1" gradientTransform="matrix(.92166 1.13995 -2.55421 2.0651 6.862 4.164)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="iEVq5tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.14735 -1.35762 0 15.15 12.453)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iO0krGd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 10.402 2.429)scale(.48046 .66148)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iaH0m6L" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.14741 -1.35769 0 9.608 12.453)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ioEq83F" cx="0" cy="0" r="1" gradientTransform="matrix(-.00983 -.62753 .75432 -.01181 9.244 12.307)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="idh2fsd" x1="12.382" x2="12.382" y1="30.602" y2="25.695" gradientUnits="userSpaceOnUse"><stop class="oeqqncchi"/><stop offset="1" class="rmb_a4bif"/></linearGradient><linearGradient id="i6MpWTd" x1="28.123" x2="27.512" y1="15.5" y2="14.29" gradientUnits="userSpaceOnUse"><stop offset=".217" class="ocrnwfbjy"/><stop offset="1" class="hc6nasj2l"/></linearGradient><linearGradient id="iBJRYNT" x1="28.537" x2="28.101" y1="16.055" y2="14.761" gradientUnits="userSpaceOnUse"><stop offset=".217" class="ocrnwfbjy"/><stop offset="1" class="hc6nasj2l"/></linearGradient><linearGradient id="ii0AJgc" x1="27.941" x2="27.823" y1="16.39" y2="15.207" gradientUnits="userSpaceOnUse"><stop offset=".217" class="ocrnwfbjy"/><stop offset="1" class="hc6nasj2l"/></linearGradient><linearGradient id="ipRsbRb" x1="24.588" x2="26.182" y1="16.84" y2="16.527" gradientUnits="userSpaceOnUse"><stop offset=".585" class="oc3fsgi2c"/><stop offset="1" class="v-pv693fm"/></linearGradient><linearGradient id="isVyl7s" x1="20.756" x2="25.197" y1="16.813" y2="16.469" gradientUnits="userSpaceOnUse"><stop class="rmvak_xfq"/><stop offset="1" class="kzyqjmbts"/></linearGradient><linearGradient id="iBjVL9d" x1="23.483" x2="23.483" y1="18.338" y2="18.164" gradientUnits="userSpaceOnUse"><stop offset=".316" class="jydl9dbrr"/><stop offset="1" class="aygc7mb2y"/><stop offset="1" class="h9u6zibfw"/></linearGradient><linearGradient id="i2tvtje" x1="24.354" x2="24.354" y1="19.402" y2="38.715" gradientUnits="userSpaceOnUse"><stop class="uu1puyblk"/><stop offset=".621" class="je7mxqbyx"/></linearGradient><linearGradient id="ixyVNac" x1="27.768" x2="22.341" y1="28.93" y2="28.93" gradientUnits="userSpaceOnUse"><stop class="kd-yr7fuk"/><stop offset=".458" class="ks-d0_bdl"/><stop offset="1" class="kd-yr7fuk"/></linearGradient><linearGradient id="ibQWfRc" x1="23.312" x2="23.312" y1="18.243" y2="19.277" gradientUnits="userSpaceOnUse"><stop offset=".366" class="m9y_tybxe"/><stop offset="1" class="iq0cs8i_e"/></linearGradient><linearGradient id="iGCBfwb" x1="28.027" x2="23.189" y1="15.842" y2="16.394" gradientUnits="userSpaceOnUse"><stop class="ag1s7-b0v"/><stop offset="1" class="s8wjd1bww"/></linearGradient><linearGradient id="iF0sLad" x1="6.351" x2="5.537" y1="13.249" y2="13.249" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="i0FWTLc" x1="19.817" x2="18.777" y1="11.509" y2="14.731" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iJODNib" x1="17.51" x2="7.808" y1="13.39" y2="14.836" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="ipC7G6N" x1="5.528" x2="8.465" y1="16.815" y2="16.432" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iSRKOJd" x1="6.207" x2="9.894" y1="12.556" y2="6.007" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iWvr2Td" x1="11.285" x2="12.477" y1="14.228" y2="14.228" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="i784nNO" x1="13.575" x2="12.272" y1="14.637" y2="14.619" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iKQd3Pd" x1="12.63" x2="12.63" y1="15.58" y2="14.852" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iN27kDe" x1="12.542" x2="12.542" y1="15.634" y2="15.421" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="iiSAyAa" x1="11.065" x2="11.618" y1="17.632" y2="16.759" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="ioc3Cqc" x1="16.139" x2="15.74" y1="12.097" y2="12.343" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPMHfcd" x1="10.553" x2="10.154" y1="12.097" y2="12.343" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ile5rCe" x1="16.159" x2="15.625" y1="9.379" y2="8.288" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="i7j9ZOe" x1="9.42" x2="7.909" y1="9.217" y2="8.583" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><filter id="iGSVp0V" width="7.879" height="3.847" x="21.258" y="13.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.603922 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3800"/></filter><filter id="i41IBOc" width="7.879" height="3.847" x="21.258" y="13.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.545098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3800"/></filter><filter id="iEZbbbd" width="6.491" height="11.844" x="20.116" y="18.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.541176 0 0 0 0 0.819608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3800"/></filter><filter id="ijsyNcc" width="5.75" height="1.328" x="23" y="15.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3800" stdDeviation=".125"/></filter><filter id="it2SDYc" width="4.442" height="4.242" x="4.23" y="10.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3800"/></filter><filter id="iatXJwc" width="3.528" height="3.528" x="4.587" y="11.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3800" stdDeviation=".25"/></filter><filter id="iBHVgLb" width="4.492" height="4.492" x="16.316" y="10.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3800"/></filter><filter id="izIXqwd" width="3.528" height="3.528" x="16.672" y="11.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3800" stdDeviation=".25"/></filter><filter id="i4sNehb" width="13.179" height="15.53" x="5.83" y="5.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3800"/></filter><filter id="i6nkfud" width="16.009" height="10.718" x="4.378" y="1.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3800"/></filter><filter id="iVZiFAc" width="3.736" height="4.906" x="10.211" y="11.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3800" stdDeviation=".375"/></filter><filter id="iK2Twlc" width="2.884" height="3.906" x="10.94" y="11.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3800" stdDeviation=".125"/></filter><filter id="irpNjOd" width="3.718" height="2.271" x="13.884" y="8.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3800"/></filter><filter id="i99r3Zb" width="3.718" height="2.271" x="7.345" y="8.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3800"/></filter><filter id="iLIiUee" width=".945" height=".83" x="14.245" y="11.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3800" stdDeviation=".05"/></filter><filter id="ixkIhwc" width="1.024" height="1.052" x="15.339" y="11.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3800" stdDeviation=".1"/></filter><filter id="iy5T0ke" width="1.145" height="1.213" x="9.696" y="11.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3800" stdDeviation=".1"/></filter><filter id="iPqOjWb" width="1.106" height=".841" x="8.71" y="11.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3800" stdDeviation=".05"/></filter><filter id="ii8wdSd" width="3.849" height="2.048" x="13.742" y="8.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3800" stdDeviation=".25"/></filter><filter id="i6jsK7R" width="3.948" height="2.12" x="7.111" y="8.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3800" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-tipping-hand-medium-light" /></template>
<style>
.a-e0cj8zq {
  stop-color: var(--svg-color--ba7e80, #BA7E80);
}

.a1oixybvc {
  cx: 6.351px;
  cy: 12.895px;
  r: 1.264px;
}

.a3oso8z0y {
  stop-color: var(--svg-color--e6b086, #E6B086);
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.ac5fyukrd {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.646 16.41a.244.244 0 0 0-.291.05a.224.224 0 0 0-.025.288a2.46 2.46 0 0 0 2.053 1.096c.861 0 1.618-.438 2.052-1.096a.23.23 0 0 0-.025-.29a.245.245 0 0 0-.29-.048a3.75 3.75 0 0 1-1.737.412c-.637 0-1.235-.15-1.737-.412Z");
}

.adnp-y-dh {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
  stop-opacity: 0;
}

.ag1s7-b0v {
  stop-color: var(--svg-color--fcd3b7, #FCD3B7);
}

.agu36v23f {
  stop-color: var(--svg-color--499cd4, #499CD4);
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.apy9n4beb {
  stop-color: var(--svg-color--f0c2a7, #F0C2A7);
}

.au4n6sbel {
  d: path("M10.64 12.424c0-.367-.297-.611-.377-.685l-.367.354l.226.46z");
}

.ax8207b9e {
  stop-color: var(--svg-color--e4b833, #E4B833);
  stop-opacity: 0;
}

.aya26o47f {
  fill: var(--svg-color--d7927e, #D7927E);
  d: path("M21.258 15.789h4.015v2.016h-4.015z");
}

.aygc7mb2y {
  stop-color: var(--svg-color--327aa5, #327AA5);
  stop-opacity: 0;
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.c0-_whbvj {
  cx: 18.436px;
  cy: 12.895px;
  r: 2.121px;
}

.c6l8th9lj {
  d: path("m5.904 12.117l.062.002s-.068-1.084-.136-1.83c0-.338.136-.745.409-.948l.204-.203c.34-.271.477-.678.477-1.084V6.97c0-.339.205-.61.545-.678c.818-.203 2.522-.542 4.975-.542s4.156.339 4.974.542c.273.068.545.339.545.678v1.084c0 .406.205.813.477 1.084c.638.447.598.693.545 1.22c-.068.677-.136 1.829-.136 1.829h.023l-.338 5.028c-.204 2.248-1.97 3.815-4.078 3.815h-4.078c-2.176 0-3.875-1.567-4.079-3.815z");
}

.cgp3v0siv {
  cx: 9.263px;
  cy: 11.907px;
  rx: 0.495px;
  ry: 0.25px;
}

.ciwrelrrj {
  stop-color: var(--svg-color--f0c4a6, #F0C4A6);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d47_3hb-i {
  stop-color: var(--svg-color--f2c29d, #F2C29D);
}

.dc_-el2vm {
  fill-rule: evenodd;
  d: path("M25.57 14.017c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.248c.917-.102 1.759-.206 2.235-.308a.825.825 0 0 0-.346-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.djszrn9ws {
  fill-rule: evenodd;
  d: path("M30.203 14.51a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693c1.02-.096 1.89-.259 2.552-.383l.459-.084a.85.85 0 0 1 .984.69");
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f_gwqccqg {
  stop-color: var(--svg-color--ab747c, #AB747C);
}

.f7n3i4bhd {
  stop-color: var(--svg-color--dfa377, #DFA377);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.furegib2d {
  d: path("M25.57 14.017c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.874-.095 1.183-.192c.242-.077.5-.219.96-.306c.916-.102 1.758-.206 2.233-.308a.825.825 0 0 0-.345-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.fv-l3eb9p {
  cx: 18.436px;
  cy: 12.895px;
  r: 1.264px;
}

.fwnss0e3m {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M25.57 14.017c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.248c.917-.102 1.759-.206 2.235-.308a.825.825 0 0 0-.346-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gmo09s50p {
  width: 4.898px;
  height: 6.68px;
  x: 9.944px;
  y: 17.009px;
  rx: 2.449px;
}

.gojugjv6o {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.343 11.078c-.83 0-1.53.572-1.721 1.345a.348.348 0 0 0 .34.432h2.834c.18 0 .324-.164.288-.345a1.78 1.78 0 0 0-1.741-1.432");
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.h9u6zibfw {
  stop-color: var(--svg-color--166599, #166599);
  stop-opacity: 0;
}

.hc6nasj2l {
  stop-color: var(--svg-color--c58780, #C58780);
  stop-opacity: 0;
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hsbr_ca-x {
  stop-color: var(--svg-color--1b79d5, #1B79D5);
  stop-opacity: 0;
}

.htrw0pbkw {
  stop-color: var(--svg-color--055bde, #055BDE);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.iguvvnbvp {
  stop-color: var(--svg-color--2e76ab, #2E76AB);
}

.iq0cs8i_e {
  stop-color: var(--svg-color--1fa0ec, #1FA0EC);
  stop-opacity: 0;
}

.is-__hh9o {
  fill: var(--svg-color--000, #000);
  d: path("M14.504 12.557c0-.361.289-.65.65-.65a.646.646 0 0 1 .576.948h-1.149a.6.6 0 0 1-.077-.298");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j61mf2btk {
  stop-color: var(--svg-color--9b7287, #9B7287);
}

.je7mxqbyx {
  stop-color: var(--svg-color--269eff, #269EFF);
}

.jhda4212k {
  d: path("M22.03 13.876c-.554.648-.74 1.417-.761 1.758l1.847-.102l.887-1.183c.29-.383.54-1.02-.035-1.442c-.466-.342-.945-.066-1.102.106a28 28 0 0 0-.836.863");
}

.jj70p7yrg {
  stop-color: var(--svg-color--3797ff, #3797FF);
  stop-opacity: 0;
}

.jo9kslbvg {
  cx: 6.351px;
  cy: 12.895px;
  r: 2.121px;
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jydl9dbrr {
  stop-color: var(--svg-color--166599, #166599);
}

.k_v_c_b6y {
  stop-color: var(--svg-color--2094e3, #2094E3);
  stop-opacity: 0;
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k87it816j {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m7.589 9.44l.002-.001l.002-.002l.006-.005l.015-.012a2 2 0 0 1 .197-.137c.126-.079.306-.178.533-.267a3.6 3.6 0 0 1 1.896-.201a.678.678 0 0 1-.211 1.34c-.506-.08-.91.013-1.186.122a2 2 0 0 0-.392.21a.678.678 0 0 1-.862-1.047");
}

.kd-yr7fuk {
  stop-color: var(--svg-color--3ab3ff, #3AB3FF);
  stop-opacity: 0;
}

.kg26iac7f {
  d: path("M15.07 11.663c.08.108-.088.24-.28.383s-.334.245-.415.136s.01-.312.201-.455c.192-.143.413-.172.494-.064");
}

.ks-d0_bdl {
  stop-color: var(--svg-color--3ab3ff, #3AB3FF);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.kzyqjmbts {
  stop-color: var(--svg-color--e39e77, #E39E77);
  stop-opacity: 0;
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lknsjyjnn {
  stop-color: var(--svg-color--dcb18d, #DCB18D);
}

.ll4x9cbml {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m18.505 4.666l.545.271c.954.474 1.499 1.559 1.294 2.71l-.75 3.862c-.066.4-.33.668-.726.678h-.023s.068-1.152.137-1.83c.055-.55-.041-.718-.546-1.22c-.272-.27-.477-.677-.477-1.083V6.97c0-.339-.272-.61-.545-.678c-.818-.203-2.521-.542-4.974-.542s-4.157.339-4.975.542c-.34.068-.545.339-.545.678v1.084c0 .406-.136.813-.477 1.084l-.204.203c-.273.203-.41.61-.41.949c.069.745.137 1.83.137 1.83l-.062-.003a.805.805 0 0 1-.756-.675l-.75-3.862c-.135-1.084.41-2.169 1.364-2.643l.545-.27c.34-.204.681-.475 1.022-.746l1.227-1.287c.75-.678 1.84-.881 2.794-.407a3.74 3.74 0 0 0 2.112 0c1.022-.339 2.18-.068 2.998.678l1.022 1.016c.273.339.614.542 1.023.745");
}

.lno0m-9jy {
  stop-color: var(--svg-color--dcb18d, #DCB18D);
  stop-opacity: 0;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lsm4wo0il {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.416 11.078c.83 0 1.53.572 1.72 1.345a.348.348 0 0 1-.34.432h-2.833a.292.292 0 0 1-.288-.345a1.775 1.775 0 0 1 1.741-1.432");
}

.m0opo6bbh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.375 16.42c.984-.047 3.363-.228 5-.578");
}

.m5fjdpbci {
  d: path("M16.163 12.407a1.07 1.07 0 0 0-.294-.587l-.33.362l.149.29z");
}

.m9y_tybxe {
  stop-color: var(--svg-color--1fa0ec, #1FA0EC);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mx6r32s2r {
  stop-color: var(--svg-color--d19984, #D19984);
  stop-opacity: 0;
}

.nbzkw-med {
  fill-rule: evenodd;
  d: path("M29.932 15.067a.85.85 0 0 1-.772.921c-.322.029-.74.088-1.26.162l-.03.004a53 53 0 0 1-1.788.231a.85.85 0 1 1-.182-1.69c.622-.067 1.205-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.nmfv5s6hy {
  stop-color: var(--svg-color--f0c2a7, #F0C2A7);
  stop-opacity: 0;
}

.nqt07ssya {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.07 11.663c.08.108-.088.24-.28.383s-.334.245-.415.136s.01-.312.201-.455c.192-.143.413-.172.494-.064");
}

.nycnkg-cp {
  fill: var(--svg-color--eeb992, #EEB992);
  fill-rule: evenodd;
  d: path("M29.625 14.181a.85.85 0 0 1-.69.985a21 21 0 0 0-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.083.715-.142a.85.85 0 0 1 .985.69");
}

.o28tdfdvf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.492 9.256c.547-.095 1.612-.068 2.35.506");
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.oc3fsgi2c {
  stop-color: var(--svg-color--ffca38, #FFCA38);
}

.ocrnwfbjy {
  stop-color: var(--svg-color--c58780, #C58780);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oeqqncchi {
  stop-color: var(--svg-color--2c9cff, #2C9CFF);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plpsytzme {
  stop-color: var(--svg-color--48b5ff, #48B5FF);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.ptj8svxtg {
  fill-rule: evenodd;
  d: path("M29.625 14.181a.85.85 0 0 1-.69.985a21 21 0 0 0-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.083.715-.142a.85.85 0 0 1 .985.69");
}

.ptt1l_01g {
  cx: 18.436px;
  cy: 12.895px;
  r: 1.264px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.q-h41ezkf {
  d: path("M9.605 11.423a1.134 1.134 0 0 0-1.092 1.432h2.19a1.2 1.2 0 0 0 .04-.298a1.14 1.14 0 0 0-1.138-1.134");
}

.qcgh4gb9v {
  d: path("M12.382 20.036c-5.523 0-10 4.477-10 10v.05h20v-.05c0-5.523-4.477-10-10-10");
}

.ql8ba7bmn {
  stop-color: var(--svg-color--f1bf98, #F1BF98);
  stop-opacity: 0;
}

.qttx_q5hd {
  stop-color: var(--svg-color--3797ff, #3797FF);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r1ahmww7a {
  stop-color: var(--svg-color--48b5ff, #48B5FF);
  stop-opacity: 0;
}

.r6b0mzudl {
  fill: var(--svg-color--eeb992, #EEB992);
  fill-rule: evenodd;
  d: path("M30.203 14.51a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693c1.02-.096 1.89-.259 2.552-.383l.459-.084a.85.85 0 0 1 .984.69");
}

.rgelk8b2a {
  fill: var(--svg-color--eeb992, #EEB992);
  fill-rule: evenodd;
  d: path("M29.932 15.067a.85.85 0 0 1-.772.921c-.322.029-.74.088-1.26.162l-.03.004a53 53 0 0 1-1.788.231a.85.85 0 1 1-.182-1.69c.622-.067 1.205-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.rmb_a4bif {
  stop-color: var(--svg-color--1d8fdf, #1D8FDF);
}

.rmvak_xfq {
  stop-color: var(--svg-color--e39e77, #E39E77);
}

.rq0vvgb8y {
  stop-color: var(--svg-color--d39f86, #D39F86);
}

.rtamvw1ka {
  stop-color: var(--svg-color--e4b833, #E4B833);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s8wjd1bww {
  stop-color: var(--svg-color--fcd3b7, #FCD3B7);
  stop-opacity: 0;
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sbt-tumyu {
  d: path("M15.153 11.423a1.134 1.134 0 0 1 1.092 1.432h-2.19a1.138 1.138 0 0 1 1.098-1.432");
}

.sn-83pben {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
}

.szdg8rbev {
  stop-color: var(--svg-color--dfa377, #DFA377);
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.u7ohzz30e {
  cx: 9.263px;
  cy: 11.907px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.495px;
  ry: 0.25px;
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.ukh84abxq {
  d: path("M21.015 17.548a.25.25 0 0 1 .25-.25h4.093a.25.25 0 0 1 .25.25v1.64h-4.593z");
}

.ulfybv1yg {
  fill: var(--svg-color--000, #000);
  d: path("M10.255 12.557c0-.361-.29-.65-.65-.65a.647.647 0 0 0-.577.948h1.15a.64.64 0 0 0 .076-.298");
}

.uu1puyblk {
  stop-color: var(--svg-color--2595fb, #2595FB);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v-pv693fm {
  stop-color: var(--svg-color--ffca38, #FFCA38);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.wom4lqbtj {
  d: path("m11.897 12.533l-.675 2.16a.685.685 0 0 0 .661.887h.999a.687.687 0 0 0 .661-.888l-.675-2.159c-.145-.478-.82-.478-.971 0");
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x-ga_webx {
  d: path("m18.505 4.666l.545.271c.954.474 1.499 1.559 1.294 2.71l-.75 3.862c-.066.4-.33.668-.726.678h-.023s.068-1.152.137-1.83c.055-.55-.041-.718-.546-1.22c-.272-.27-.477-.677-.477-1.083V6.97c0-.339-.272-.61-.545-.678c-.818-.203-2.521-.542-4.974-.542s-4.157.339-4.975.542c-.34.068-.545.339-.545.678v1.084c0 .406-.136.813-.477 1.084l-.204.203c-.273.203-.41.61-.41.949c.069.745.137 1.83.137 1.83l-.062-.003a.805.805 0 0 1-.756-.675l-.75-3.862c-.135-1.084.41-2.169 1.364-2.643l.545-.27c.34-.204.681-.475 1.022-.746l1.227-1.287c.75-.678 1.84-.881 2.794-.407a3.74 3.74 0 0 0 2.112 0c1.022-.339 2.18-.068 2.998.678l1.022 1.016c.273.339.614.542 1.023.745");
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xm7l4wblc {
  d: path("M20.116 19.043a.8.8 0 0 1 .8-.8h4.791a.8.8 0 0 1 .8.8v11.044h-6.39z");
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xzax2hcxn {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m11.897 12.533l-.675 2.16a.685.685 0 0 0 .661.887h.999a.687.687 0 0 0 .661-.888l-.675-2.159c-.145-.478-.82-.478-.971 0");
}

.xzb70-bgi {
  stop-color: var(--svg-color--f0c4a6, #F0C4A6);
}

.y57vb-6vx {
  stop-color: var(--svg-color--1a74ad, #1A74AD);
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.yp2ng6blh {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m17.108 9.44l-.002-.001l-.002-.002l-.006-.005l-.015-.012a2 2 0 0 0-.197-.137a3.3 3.3 0 0 0-.533-.267a3.6 3.6 0 0 0-1.896-.201a.678.678 0 0 0 .211 1.34c.506-.08.91.013 1.187.122a2 2 0 0 1 .381.202l.01.008a.678.678 0 0 0 .862-1.047");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.ywfp1px4j {
  stop-color: var(--svg-color--b78178, #B78178);
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zgnc2ob4f {
  stop-color: var(--svg-color--d8a983, #D8A983);
}

.zgxkbfbem {
  fill: var(--svg-color--c68378, #C68378);
  d: path("M12.033 12.74L10.99 14.9c-.13.444.18.888.62.888h.936c.44 0 .75-.451.62-.889l-.633-2.159c-.135-.478-.36-.478-.501 0");
}

.zhvue1b_t {
  stop-color: var(--svg-color--d39f86, #D39F86);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zlv0xcc8i {
  fill: var(--svg-color--f0be97, #F0BE97);
  d: path("M25.57 14.017c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.874-.095 1.183-.192c.242-.077.5-.219.96-.306c.916-.102 1.758-.206 2.233-.308a.825.825 0 0 0-.345-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.zycvbibcr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.861 9.915c.416-.367 1.324-.754 2.449-.575");
}

</style>
