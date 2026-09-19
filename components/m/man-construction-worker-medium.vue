<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iEGGwpd)" class="kkb_itbhc"/><path fill="url(#iO2O1lb)" class="kkb_itbhc"/><path fill="url(#iq534Dd)" class="dixgp5b2c"/><path fill="url(#ibUWNwd)" class="dixgp5b2c"/><path fill="url(#iLSmNXc)" class="dixgp5b2c"/><path fill="url(#ixKKiko)" class="zv2tyvbtc"/><path fill="url(#iqIvJAb)" class="zv2tyvbtc"/><path fill="url(#i59HMpb)" class="ui5t8ob3c"/><path fill="url(#ioFe7rc)" class="ui5t8ob3c"/><path fill="url(#iPeOANc)" class="ui5t8ob3c"/><path fill="url(#iDPM1Fd)" class="zhjfgetmo"/><path fill="url(#idGrQzb)" class="zhjfgetmo"/><path class="k6kn8iijv"/><path fill="url(#i1KV55d)" class="zn_-1ab3y"/><path fill="url(#is4Tk2d)" class="uzho3hgph"/><path fill="url(#i72FXBc)" class="uzho3hgph"/><path fill="url(#iOhUSec)" class="erhy-ybfe"/><path fill="url(#iJRY4fb)" class="erhy-ybfe"/><path fill="url(#iO7EKec)" class="vvol17nke"/><path fill="url(#iGoycPc)" class="vvol17nke"/><path fill="url(#irawi4d)" class="ti35gzbvb"/><path fill="url(#iHU9Tub)" class="ti35gzbvb"/><path fill="url(#i8nXVzd)" class="ti35gzbvb"/><g filter="url(#i3FdBpe)"><ellipse class="as8s4rb-o"/></g><g filter="url(#ix9nzEo)"><circle fill="url(#ilZwOpf)" class="qf_gujz1v"/></g><circle fill="url(#isbtJLe)" class="qf_gujz1v"/><g filter="url(#iPFsOed)"><circle fill="url(#iW4a2Ie)" class="dp3gyk76q"/></g><g filter="url(#ikHEdQe)"><circle fill="url(#iEZmq4d)" class="e1g6j_bte"/><circle fill="url(#iLV8bIF)" class="e1g6j_bte"/></g><g filter="url(#ieSwwSc)"><circle class="zfs9czbcm"/><circle fill="url(#iBaQ8zZ)" class="j1z_ju40f"/><circle fill="url(#iIJM7Cs)" class="j1z_ju40f"/></g><path fill="url(#ieUhnse)" class="o6zm4yb7a"/><path fill="url(#iQGXUlU)" class="o6zm4yb7a"/><path fill="url(#ij6LKrb)" class="o6zm4yb7a"/><path fill="url(#ioQKZGd)" class="o6zm4yb7a"/><path fill="url(#i5ZH1Ob)" class="o6zm4yb7a"/><path fill="url(#ibQi87c)" class="o6zm4yb7a"/><g filter="url(#iMXWRbd)"><path class="n6bjuibny"/></g><g filter="url(#iCZty0p)"><path class="ey8y_bb1m"/><path fill="url(#iH3BCvg)" class="biazsp7_r"/><path fill="url(#iSW3AWt)" class="biazsp7_r"/><path fill="url(#iAVBHRz)" class="biazsp7_r"/><path fill="url(#it8AHLc)" class="biazsp7_r"/></g><g filter="url(#i8pYH3c)"><path fill="url(#iYcSe6d)" class="bn25grbif"/></g><g filter="url(#iOPVN4c)"><path stroke="url(#i0NvSOc)" class="o-et01bco"/></g><path class="kdl02_47q"/><path class="tv66fhb7s"/><path fill="url(#irEz8nd)" class="o75stkbfd"/><path class="b4my04b1d"/><g filter="url(#iOIV3Lb)"><path class="o2x6ypbvp"/><path fill="url(#iUtarue)" class="g9vj387rc"/></g><g filter="url(#iHsPr8z)"><path fill="url(#icGoTkq)" class="y7gl90b6e"/></g><path class="z6wg67l9n"/><path fill="url(#iMf2rCd)" class="w4ikutt9a"/><path class="z37e75ohw"/><g filter="url(#iSsaAKM)"><path fill="url(#iSsqOIc)" class="jnmrq9bof"/></g><g filter="url(#iW2C9Fb)"><ellipse transform="rotate(-27.914 13.341 13.035)" class="x6h3n-bkl"/><ellipse fill="url(#i2jEaSb)" transform="rotate(-27.914 13.341 13.035)" class="ak_9foead"/></g><path fill="url(#iwvsKLc)" class="c71e6bi8d"/><path fill="url(#iT8EgXc)" class="ioz_ulooi"/><path fill="url(#icYCTvd)" class="v737-kb8e"/><path fill="url(#i1gk2NX)" class="v737-kb8e"/><path fill="url(#i33Kzde)" class="v737-kb8e"/><path fill="url(#iOYFGrc)" class="v737-kb8e"/><path fill="url(#ii0WgBc)" class="v737-kb8e"/><path fill="url(#iY6OXhc)" class="v737-kb8e"/><path fill="url(#iudKbLd)" class="v737-kb8e"/><path fill="url(#iwqMSGd)" class="v737-kb8e"/><g filter="url(#iXsnFhd)"><path fill="url(#ityS7Me)" class="g1t2lzbov"/><path fill="url(#itwpfTc)" class="g1t2lzbov"/><path fill="url(#iHRIIYb)" class="g1t2lzbov"/><path fill="url(#ixGweCe)" class="g1t2lzbov"/></g><path fill="url(#ib2lrXd)" class="g2i6l-0tu"/><path fill="url(#iHJ6XLr)" class="g2i6l-0tu"/><path fill="url(#iP0gY5b)" class="g2i6l-0tu"/><path fill="url(#im5cwBe)" class="g2i6l-0tu"/><g filter="url(#ifp8jQd)"><ellipse class="jq7ez9q1u"/></g><defs><radialGradient id="iEGGwpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.25 -8.82215 0 16.011 16.61)" gradientUnits="userSpaceOnUse"><stop class="l9-nibb6i"/><stop offset="1" class="yfct4t52m"/></radialGradient><radialGradient id="iO2O1lb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9049 0 0 -8.83091 18.677 26.142)" gradientUnits="userSpaceOnUse"><stop class="b601vwbxd"/><stop offset="1" class="g__icmf-v"/></radialGradient><radialGradient id="iq534Dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.721 24.533)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="ibUWNwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.721 26.2)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="iLSmNXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.208 20.006)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="ixKKiko" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.042 20.235)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="iqIvJAb" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.279 27.354)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="ioFe7rc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.416 28.855)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="iPeOANc" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.341 29.9)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="iDPM1Fd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.659 22.513)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="idGrQzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.659 27.907)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="i1KV55d" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.462 10.106)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="i72FXBc" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.24 25.33)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="iOhUSec" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.471 28.86)" gradientUnits="userSpaceOnUse"><stop class="fanogvbyi"/><stop offset="1" class="a0y7_lb_e"/></radialGradient><radialGradient id="iJRY4fb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.28125 0 0 -15.3733 9.022 29.673)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="mhpw6_ebm"/><stop offset="1" class="nh1zhnb8g"/></radialGradient><radialGradient id="iO7EKec" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 -8.13268 2.48004 -.42883 25.677 29.9)" gradientUnits="userSpaceOnUse"><stop class="jlteq3ywp"/><stop offset="1" class="ud4d3yb8t"/></radialGradient><radialGradient id="iGoycPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .62514 0 23.659 29.9)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="kqqjbhbza"/><stop offset="1" class="g8lpdoqap"/></radialGradient><radialGradient id="irawi4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.968 0 16.021 20.657)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="e6b_v3oow"/><stop offset=".88" class="dwvgclbly"/></radialGradient><radialGradient id="iHU9Tub" cx="0" cy="0" r="1" gradientTransform="rotate(125.503 3.83 15.16)scale(3.01336 1.49475)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="r0oe3abav"/><stop offset="1" class="ktbu0qmwq"/></radialGradient><radialGradient id="i8nXVzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.66902 -2.3468 0 16.02 19.424)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="fcs9sgbmm"/><stop offset="1" class="kbpksibjr"/></radialGradient><radialGradient id="ilZwOpf" cx="0" cy="0" r="1" gradientTransform="matrix(1.90132 0 0 3.32732 9.049 13.878)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="isbtJLe" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 9.513 5.016)scale(1.795)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iLV8bIF" cx="0" cy="0" r="1" gradientTransform="matrix(.8957 -.6522 .7444 1.02232 21.568 13.59)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iBaQ8zZ" cx="0" cy="0" r="1" gradientTransform="matrix(.8898 -1.6366 .9579 .5208 21.12 14.768)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iIJM7Cs" cx="0" cy="0" r="1" gradientTransform="matrix(.28093 .27808 -.35848 .36215 21.165 13.878)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="ieUhnse" cx="0" cy="0" r="1" gradientTransform="rotate(173.44 9.67 8.387)scale(6.29119 7.49476)" gradientUnits="userSpaceOnUse"><stop class="u05m3mb1z"/><stop offset="1" class="hkboptbis"/></radialGradient><radialGradient id="iQGXUlU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41616 1.74297 0 18.543 12.5)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="ij6LKrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.48879 1.85144 0 13.605 12.646)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="i5ZH1Ob" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.99071 -20.6276 0 15.863 12.216)" gradientUnits="userSpaceOnUse"><stop offset=".694" class="aycfmccps"/><stop offset=".99" class="w-lwpijvp"/></radialGradient><radialGradient id="ibQi87c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.43657 -7.11188 0 16.033 11.864)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="lv_ot6htn"/><stop offset="1" class="oqp4lznyx"/></radialGradient><radialGradient id="it8AHLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21333 -.68539 0 16.356 15.618)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="irEz8nd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87882 -1.39787 0 18.362 13.139)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iUtarue" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.297 2.179)scale(.40976 .56415)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMf2rCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87887 -1.39794 0 13.635 13.139)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i2jEaSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00838 -.5352 .64333 -.01007 13.325 13.376)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwvsKLc" cx="0" cy="0" r="1" gradientTransform="matrix(.16294 1.43904 -.60098 .06805 10.379 12.14)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="l455clhzf"/><stop offset="1" class="o_6cpw3af"/></radialGradient><radialGradient id="iT8EgXc" cx="0" cy="0" r="1" gradientTransform="matrix(.68394 .16058 -.54394 2.31675 21.48 12.575)" gradientUnits="userSpaceOnUse"><stop class="b0rle0boe"/><stop offset=".933" class="ofjcs8bae"/></radialGradient><radialGradient id="icYCTvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5625 -2.88065 0 19.794 6.827)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="i1gk2NX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 12.044 9.89)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="i33Kzde" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.45 10.327)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iOYFGrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.388 6.499)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="ii0WgBc" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.513 2.733)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iY6OXhc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.95 9.733)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="iwqMSGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 11.17 10.124)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="iHRIIYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.67 9.89)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="ixGweCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.544 9.952)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="im5cwBe" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.909 8.966)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><linearGradient id="i59HMpb" x1="9.158" x2="9.158" y1="21.169" y2="29.899" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="is4Tk2d" x1="21.034" x2="21.034" y1="19.705" y2="29.899" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="iW4a2Ie" x1="10.857" x2="10.163" y1="14.18" y2="14.18" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iEZmq4d" x1="22.342" x2="21.455" y1="12.695" y2="15.443" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="ioQKZGd" x1="10.796" x2="12.194" y1="17.176" y2="17.148" gradientUnits="userSpaceOnUse"><stop offset=".229" class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iH3BCvg" x1="15.065" x2="16.082" y1="15.014" y2="15.014" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iSW3AWt" x1="17.018" x2="15.907" y1="15.363" y2="15.348" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iAVBHRz" x1="16.212" x2="16.212" y1="16.168" y2="15.547" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iYcSe6d" x1="16.002" x2="16.002" y1="13.233" y2="14.201" gradientUnits="userSpaceOnUse"><stop class="te2-7tu1s"/><stop offset="1" class="zf5wn7b2i"/></linearGradient><linearGradient id="i0NvSOc" x1="14.878" x2="15.349" y1="17.918" y2="17.173" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="icGoTkq" x1="19.205" x2="18.865" y1="13.197" y2="13.407" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSsqOIc" x1="14.441" x2="14.101" y1="13.197" y2="13.407" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iudKbLd" x1="9.982" x2="10.794" y1="9.265" y2="9.265" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="ityS7Me" x1="16.021" x2="16.021" y1="2.101" y2="10.528" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="itwpfTc" x1="16.021" x2="16.021" y1="2.101" y2="4.702" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="ib2lrXd" x1="21.997" x2="5.369" y1="11.273" y2="11.273" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="iHJ6XLr" x1="15.798" x2="15.798" y1="9.872" y2="10.186" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="iP0gY5b" x1="16.716" x2="16.716" y1="12.178" y2="10.926" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient><filter id="i3FdBpe" width="8.369" height="2.215" x="15.115" y="9.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".375"/></filter><filter id="ix9nzEo" width="3.818" height="3.618" x="9.049" y="12.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2956"/></filter><filter id="iPFsOed" width="3.156" height="3.156" x="9.279" y="12.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".25"/></filter><filter id="ikHEdQe" width="3.868" height="3.868" x="19.356" y="11.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2956"/></filter><filter id="ieSwwSc" width="3.156" height="3.156" x="19.587" y="12.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".25"/></filter><filter id="iMXWRbd" width="3.407" height="4.405" x="14.039" y="12.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".375"/></filter><filter id="iCZty0p" width="2.533" height="3.405" x="14.735" y="13.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".125"/></filter><filter id="i8pYH3c" width="2.533" height="3.405" x="14.735" y="12.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".125"/></filter><filter id="iOPVN4c" width="3.886" height="1.562" x="14.058" y="16.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".05"/></filter><filter id="iOIV3Lb" width=".836" height=".738" x="17.575" y="12.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".05"/></filter><filter id="iHsPr8z" width=".932" height=".956" x="18.493" y="12.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".1"/></filter><filter id="iSsaAKM" width="1.035" height="1.093" x="13.681" y="12.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".1"/></filter><filter id="iW2C9Fb" width=".972" height=".747" x="12.855" y="12.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".05"/></filter><filter id="iXsnFhd" width="5.791" height="8.428" x="13.126" y="2.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2956"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2956" result="effect2_innerShadow_4002_2956"/></filter><filter id="ifp8jQd" width="7.654" height="2.528" x="15.713" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2956" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-construction-worker-medium" /></template>
<style>
.a0y7_lb_e {
  stop-color: var(--svg-color--469bc8, #469BC8);
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.ak_9foead {
  cx: 13.341px;
  cy: 13.035px;
  rx: 0.422px;
  ry: 0.214px;
}

.as8s4rb-o {
  cx: 19.299px;
  cy: 10.826px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 3.435px;
  ry: 0.358px;
}

.aycfmccps {
  stop-color: var(--svg-color--9b6275, #9B6275);
  stop-opacity: 0;
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.b0rle0boe {
  stop-color: var(--svg-color--190a1c, #190A1C);
}

.b4my04b1d {
  fill: var(--svg-color--000, #000);
  d: path("M17.81 13.589c0-.308.247-.554.554-.554a.55.55 0 0 1 .492.809h-.98a.5.5 0 0 1-.065-.255");
}

.b601vwbxd {
  stop-color: var(--svg-color--3fb7ff, #3FB7FF);
}

.biazsp7_r {
  d: path("m15.587 13.569l-.575 1.841a.584.584 0 0 0 .564.758h.851c.4 0 .682-.385.564-.758l-.575-1.841c-.124-.408-.7-.408-.829 0");
}

.bn25grbif {
  d: path("m15.587 13.539l-.575 1.841a.584.584 0 0 0 .564.758h.851c.4 0 .682-.385.564-.758l-.575-1.841c-.124-.408-.7-.408-.829 0");
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c71e6bi8d {
  d: path("m10.558 13.38l-.078-1.332l-.844-.117c.026.084.117.368.27.824s.51.615.652.625");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
}

.dixgp5b2c {
  d: path("M13.721 19.168c-.608.134-1.196.31-1.763.537V29.9h1.763z");
}

.dp3gyk76q {
  cx: 10.857px;
  cy: 13.878px;
  r: 1.078px;
}

.dr2x31jzv {
  stop-color: var(--svg-color--ff7446, #FF7446);
}

.dwvgclbly {
  stop-color: var(--svg-color--a36976, #A36976);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1g6j_bte {
  cx: 21.165px;
  cy: 13.878px;
  r: 1.809px;
}

.e3j7-mb6u {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
  stop-opacity: 0;
}

.e6b_v3oow {
  stop-color: var(--svg-color--98596f, #98596F);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.erhy-ybfe {
  d: path("M4.601 29.9c.14-.946.34-1.882.62-2.787a11.56 11.56 0 0 1 3.12-5.018V29.9z");
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.ex-0zhc5k {
  stop-color: var(--svg-color--e1926f, #E1926F);
}

.ey8y_bb1m {
  fill: var(--svg-color--9a6e66, #9A6E66);
  d: path("m15.587 13.569l-.575 1.841a.584.584 0 0 0 .564.758h.851c.4 0 .682-.385.564-.758l-.575-1.841c-.124-.408-.7-.408-.829 0");
}

.ez-c7ubrp {
  stop-color: var(--svg-color--da4708, #DA4708);
}

.f2js-baog {
  stop-color: var(--svg-color--cd963a, #CD963A);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fanogvbyi {
  stop-color: var(--svg-color--3baeff, #3BAEFF);
}

.fcs9sgbmm {
  stop-color: var(--svg-color--75384b, #75384B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g__icmf-v {
  stop-color: var(--svg-color--3fb7ff, #3FB7FF);
  stop-opacity: 0;
}

.g1t2lzbov {
  d: path("M14.826 2.1h2.39c.829 0 1.5.603 1.5 1.633v6.796h-5.39V3.732c0-1.03.671-1.632 1.5-1.632");
}

.g2i6l-0tu {
  d: path("M22.477 9.872H9.883a1.153 1.153 0 1 0 0 2.307h12.594c.642 0 1.153-.521 1.153-1.154a1.147 1.147 0 0 0-1.153-1.153");
}

.g4-w6ccdn {
  stop-color: var(--svg-color--eecd67, #EECD67);
  stop-opacity: 0;
}

.g8lpdoqap {
  stop-color: var(--svg-color--199dea, #199DEA);
  stop-opacity: 0;
}

.g9vj387rc {
  d: path("M18.293 12.827c.07.092-.075.204-.239.326s-.285.209-.353.117c-.07-.092.007-.266.171-.389c.164-.122.352-.146.421-.054");
}

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.grpyt1-9k {
  stop-color: var(--svg-color--ff7523, #FF7523);
}

.gt-qelr6u {
  stop-color: var(--svg-color--ff905a, #FF905A);
}

.hb0fg9dnu {
  stop-color: var(--svg-color--c3a852, #C3A852);
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hkboptbis {
  stop-color: var(--svg-color--976c64, #976C64);
}

.htellnhxv {
  stop-color: var(--svg-color--ffcf4c, #FFCF4C);
}

.ioz_ulooi {
  d: path("m21.48 13.356l.043-1.308l.844-.117c-.026.084-.117.368-.27.824s-.475.591-.617.601");
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.j1z_ju40f {
  cx: 21.165px;
  cy: 13.878px;
  r: 1.078px;
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.jlteq3ywp {
  stop-color: var(--svg-color--58d2ff, #58D2FF);
}

.jnmrq9bof {
  d: path("M14.516 13.475c0-.312-.254-.52-.323-.583l-.312.302l.192.391z");
}

.jq7ez9q1u {
  cx: 19.54px;
  cy: 10.886px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 2.827px;
  ry: 0.264px;
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.k6kn8iijv {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.975 20.739v9.16h1.983V19.705c-.698.28-1.355.62-1.983 1.034");
}

.kbpksibjr {
  stop-color: var(--svg-color--75384b, #75384B);
}

.kdl02_47q {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.002 17.269a3.26 3.26 0 0 1-1.501-.356c-.149-.075-.308.092-.215.227c.363.55.995.916 1.716.916c.72 0 1.352-.367 1.715-.916c.093-.14-.066-.302-.215-.227a3.24 3.24 0 0 1-1.5.356");
}

.kkb_itbhc {
  d: path("M16.021 19.29c-.78 0-1.55.08-2.3.23V29.9h4.58V19.52c-.74-.15-1.5-.23-2.28-.23");
}

.kqqjbhbza {
  stop-color: var(--svg-color--199dea, #199DEA);
}

.ktbu0qmwq {
  stop-color: var(--svg-color--b78276, #B78276);
  stop-opacity: 0;
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.l455clhzf {
  stop-color: var(--svg-color--130718, #130718);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9-nibb6i {
  stop-color: var(--svg-color--3086e2, #3086E2);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmg939n4j {
  stop-color: var(--svg-color--e3b438, #E3B438);
}

.lsejgobiz {
  stop-color: var(--svg-color--e9b840, #E9B840);
}

.lv_ot6htn {
  stop-color: var(--svg-color--8b555b, #8B555B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgd_z41tu {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
  stop-opacity: 0;
}

.mhpw6_ebm {
  stop-color: var(--svg-color--4188d0, #4188D0);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.ms43e0vsz {
  stop-color: var(--svg-color--cdac54, #CDAC54);
}

.ms9ao5bgb {
  stop-color: var(--svg-color--d7a439, #D7A439);
}

.mzrwpxbna {
  stop-color: var(--svg-color--dc5314, #DC5314);
  stop-opacity: 0;
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n6bjuibny {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.703 13.745l-.889 1.842c-.11.379.155.757.53.757h.798c.375 0 .639-.384.529-.757l-.54-1.842c-.116-.407-.307-.407-.428 0");
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nh1zhnb8g {
  stop-color: var(--svg-color--4188d0, #4188D0);
  stop-opacity: 0;
}

.npjjoacns {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
  stop-opacity: 0;
}

.nrsb-h28d {
  stop-color: var(--svg-color--c4a966, #C4A966);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o_6cpw3af {
  stop-color: var(--svg-color--474241, #474241);
}

.o-et01bco {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.002 17.269a3.26 3.26 0 0 1-1.501-.356c-.149-.075-.308.092-.215.227c.363.55.995.916 1.716.916c.72 0 1.352-.367 1.715-.916c.093-.14-.066-.302-.215-.227a3.24 3.24 0 0 1-1.5.356Z");
}

.o043sbvrw {
  stop-color: var(--svg-color--fd4, #FD4);
}

.o2jd-jggt {
  stop-color: var(--svg-color--ffce64, #FFCE64);
}

.o2x6ypbvp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.293 12.827c.07.092-.075.204-.239.326s-.285.209-.353.117c-.07-.092.007-.266.171-.389c.164-.122.352-.146.421-.054");
}

.o5ewjjbtz {
  stop-color: var(--svg-color--f9b14d, #F9B14D);
  stop-opacity: 0;
}

.o6zm4yb7a {
  d: path("M10.413 11.656c0-.29.116-.636.349-.81l.174-.173c.29-.23.407-.577.407-.924v-.925c0-.289.174-.52.465-.578c.697-.173 2.15-.462 4.242-.462s3.545.29 4.243.462c.232.058.465.29.465.578v.925c0 .347.174.693.407.924c.544.382.51.591.464 1.04c-.195 1.941-.254 3.903-.384 5.85c-.174 1.917-1.681 3.253-3.479 3.253h-3.478c-1.855 0-3.304-1.336-3.478-3.254c-.151-1.968-.217-3.942-.397-5.906");
}

.o75stkbfd {
  d: path("M18.364 12.622a.967.967 0 0 1 .932 1.222h-1.868a.97.97 0 0 1 .936-1.222");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjcs8bae {
  stop-color: var(--svg-color--4d4b4c, #4D4B4C);
}

.omeu62b7c {
  stop-color: var(--svg-color--ff6f4e, #FF6F4E);
}

.oobbay99s {
  stop-color: var(--svg-color--c3a852, #C3A852);
  stop-opacity: 0;
}

.oqp4lznyx {
  stop-color: var(--svg-color--8b555b, #8B555B);
  stop-opacity: 0;
}

.ououd5b1f {
  stop-color: var(--svg-color--f9cd2e, #F9CD2E);
}

.p-n74xx1h {
  stop-color: var(--svg-color--fb684a, #FB684A);
}

.pj-kb0bjs {
  stop-color: var(--svg-color--f0bc33, #F0BC33);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.qf_gujz1v {
  cx: 10.857px;
  cy: 13.878px;
  r: 1.809px;
}

.qf92jxbjd {
  stop-color: var(--svg-color--fe713a, #FE713A);
  stop-opacity: 0;
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo0y3qb-y {
  stop-color: var(--svg-color--f46d40, #F46D40);
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qq6id-bgn {
  stop-color: var(--svg-color--ffee61, #FFEE61);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r0oe3abav {
  stop-color: var(--svg-color--b78276, #B78276);
}

.rrfndackx {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t_t6-ha7d {
  stop-color: var(--svg-color--ffd131, #FFD131);
  stop-opacity: 0;
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.te2-7tu1s {
  stop-color: var(--svg-color--946161, #946161);
}

.thq31dj-g {
  stop-color: var(--svg-color--fe713a, #FE713A);
}

.ti35gzbvb {
  d: path("M13.81 20.376c.06.76.585 2.281 2.211 2.281s2.151-1.52 2.211-2.281z");
}

.tl7x7-b-x {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
}

.tv66fhb7s {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.589 12.328c.707 0 1.305.487 1.467 1.147a.297.297 0 0 1-.29.369H17.35a.25.25 0 0 1-.246-.295a1.514 1.514 0 0 1 1.485-1.221");
}

.u05m3mb1z {
  stop-color: var(--svg-color--c7977f, #C7977F);
}

.u14do7mcv {
  stop-color: var(--svg-color--e6743e, #E6743E);
}

.ud4d3yb8t {
  stop-color: var(--svg-color--54b9f0, #54B9F0);
}

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.ui5t8ob3c {
  d: path("M8.389 21.987a.15.15 0 0 0-.048.11v7.802h1.634v-9.16c-.56.37-1.092.79-1.586 1.248");
}

.uzho3hgph {
  d: path("M22.025 20.739v9.16h-1.983V19.705c.698.28 1.355.62 1.983 1.034");
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.v737-kb8e {
  d: path("M9.982 7.208a4.1 4.1 0 0 1 4.1-4.1h3.988a4.1 4.1 0 0 1 4.1 4.1V9.89H9.981z");
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vvol17nke {
  d: path("M27.399 29.9c-.14-.946-.34-1.882-.62-2.787a11.56 11.56 0 0 0-3.12-5.018V29.9z");
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w-lwpijvp {
  stop-color: var(--svg-color--995383, #995383);
}

.w4ikutt9a {
  d: path("M13.633 12.622a.967.967 0 0 0-.932 1.222h1.868a1 1 0 0 0 .035-.255a.973.973 0 0 0-.971-.967");
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x6h3n-bkl {
  cx: 13.341px;
  cy: 13.035px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.422px;
  ry: 0.214px;
}

.x8to7on4z {
  stop-color: var(--svg-color--b59741, #B59741);
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xmtd48u_j {
  stop-color: var(--svg-color--ff7955, #FF7955);
}

.xnbb4159v {
  stop-color: var(--svg-color--cc6e42, #CC6E42);
}

.xr07nxbnn {
  stop-color: var(--svg-color--ffe550, #FFE550);
  stop-opacity: 0;
}

.xsg9vwb1s {
  stop-color: var(--svg-color--ffd131, #FFD131);
}

.y7gl90b6e {
  d: path("M19.226 13.462a.9.9 0 0 0-.251-.502l-.282.31l.127.247z");
}

.yfct4t52m {
  stop-color: var(--svg-color--41baff, #41BAFF);
}

.yrdgovb8a {
  stop-color: var(--svg-color--fdbf28, #FDBF28);
  stop-opacity: 0;
}

.z37e75ohw {
  fill: var(--svg-color--000, #000);
  d: path("M14.187 13.589a.55.55 0 0 0-.554-.554a.55.55 0 0 0-.492.809h.98a.55.55 0 0 0 .066-.255");
}

.z6wg67l9n {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.409 12.328c-.708 0-1.306.487-1.468 1.147a.297.297 0 0 0 .29.369h2.417a.25.25 0 0 0 .246-.295a1.52 1.52 0 0 0-1.485-1.221");
}

.zf5wn7b2i {
  stop-color: var(--svg-color--946161, #946161);
  stop-opacity: 0;
}

.zfs9czbcm {
  cx: 21.165px;
  cy: 13.878px;
  r: 1.078px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.zhjfgetmo {
  d: path("M23.659 22.032V29.9h-1.634v-9.16c.578.382 1.126.816 1.634 1.292");
}

.zn_-1ab3y {
  d: path("M9.975 20.739v9.16h1.983V19.705c-.698.28-1.355.62-1.983 1.034");
}

.zv2tyvbtc {
  d: path("M18.279 19.168c.608.134 1.195.31 1.763.537V29.9H18.28z");
}

</style>
