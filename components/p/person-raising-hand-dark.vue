<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isnz1Kw)" class="tbcd_1bft"/><path fill="url(#iThKc4c)" class="tbcd_1bft"/><path fill="url(#i3qU7cc)" class="tbcd_1bft"/><path fill="url(#iEPaXld)" class="tbcd_1bft"/><path fill="url(#iK2PdmU)" class="tbcd_1bft"/><path fill="url(#iTt52Hd)" class="tbcd_1bft"/><path fill="url(#iboiDXb)" class="tbcd_1bft"/><path fill="url(#icVBP4b)" class="tbcd_1bft"/><path fill="url(#iLsG1ud)" class="tbcd_1bft"/><path fill="url(#i6HNiEc)" class="tbcd_1bft"/><path fill="url(#iSjU01b)" class="tbcd_1bft"/><path fill="url(#iIBMhxZ)" class="xgubwvapl"/><path fill="url(#if1Xczd)" class="xgubwvapl"/><path class="u9c_rrbwd"/><path fill="url(#ijfr65d)" class="xtq70kbcj"/><path fill="url(#ixJ9URb)" class="xtq70kbcj"/><path fill="url(#ixo6DJd)" class="zrrxx6xii"/><path fill="url(#iZdBDDb)" class="zrrxx6xii"/><path fill="url(#ig211be)" class="zrrxx6xii"/><path fill="url(#iyWTftc)" class="zrrxx6xii"/><path fill="url(#imBCM1b)" class="zrrxx6xii"/><path fill="url(#imfXgCe)" class="hmg_eabyj"/><path fill="url(#iPzp5WD)" class="hmg_eabyj"/><g filter="url(#ilfviQe)"><path stroke="url(#iEHfFmT)" class="gwk7k5bwe"/></g><g filter="url(#ihyM7zb)"><path stroke="url(#irBNVId)" class="c6-y3rb-s"/></g><g filter="url(#iltGzSd)"><path stroke="url(#iND5pVb)" class="dekbyeb3e"/></g><g filter="url(#iIhz21d)"><path stroke="url(#ibhenqk)" class="j5wacnblk"/></g><path fill="url(#iuBd4Gh)" class="qw26w4bib"/><path fill="url(#iZ20nnv)" class="v84_1vemz"/><g filter="url(#iNj4YRd)"><path fill="url(#iklFZib)" class="xnnb4wkvy"/></g><path fill="url(#iXOPsvc)" class="xnnb4wkvy"/><path fill="url(#i3hbYLc)" class="xnnb4wkvy"/><path fill="url(#i7wjXpN)" class="xnnb4wkvy"/><path fill="url(#iKe8IMh)" class="xnnb4wkvy"/><path fill="url(#iw9xcIb)" class="xnnb4wkvy"/><path fill="url(#iveRaZb)" class="xnnb4wkvy"/><path fill="url(#iKmYeMe)" class="xnnb4wkvy"/><path fill="url(#i5S0I4b)" class="xnnb4wkvy"/><path fill="url(#imMbU4b)" class="xnnb4wkvy"/><g filter="url(#ieBm1Ce)"><path class="mqr82bb3g"/></g><g filter="url(#iXnGx8c)"><path class="m-vdsbczh"/><path fill="url(#iIhzwWA)" class="hqne3dvml"/><path fill="url(#iXENRsl)" class="hqne3dvml"/><path fill="url(#ibjWK5d)" class="hqne3dvml"/><path fill="url(#i3s4vrH)" class="hqne3dvml"/><path fill="url(#ibBn0mE)" class="hqne3dvml"/></g><g filter="url(#ir2vsVb)"><path stroke="url(#iqPHJKO)" class="snc5bxbfc"/></g><path fill="url(#iK5b5Mc)" class="c291hebzp"/><g filter="url(#iCBaQdd)"><path fill="url(#iEipYWd)" class="qsghvrbrr"/><path fill="url(#iSusqQd)" class="qsghvrbrr"/><path fill="url(#i1vw5ue)" class="qsghvrbrr"/><path fill="url(#iSgSj9b)" class="qsghvrbrr"/><path fill="url(#iIwVy5c)" class="qsghvrbrr"/></g><g filter="url(#irSTxDc)"><path class="gttdiwbpu"/></g><g filter="url(#i98exPb)"><path class="pcy7xu8cs"/></g><g filter="url(#iHnrAPb)"><path class="izdg-vbmr"/><path fill="url(#id9ASgc)" class="df4ov0b1j"/><path fill="url(#ip4SNxO)" class="df4ov0b1j"/></g><g filter="url(#i4ERTJy)"><path class="mlatt2b4d"/><path fill="url(#ik2FhKu)" class="t0gx7kh4f"/></g><path class="gb9dd3bgt"/><path fill="url(#iLYLfUc)" class="o7f5t3bcv"/><path class="xf3kzvrmp"/><g filter="url(#iljxDSd)"><path class="q_sz55bis"/><path fill="url(#ix8eyjc)" class="p99zmmcea"/></g><g filter="url(#iN1o69c)"><path fill="url(#iUROKIe)" class="ld8yw_opa"/></g><path class="gr2n-7bby"/><path fill="url(#ii7xmzm)" class="x70fxwi3o"/><path class="e-lkx0p9a"/><g filter="url(#iUGrxOb)"><path fill="url(#iqiXqkb)" class="r00geccly"/></g><g filter="url(#i0huTrd)"><ellipse transform="rotate(-27.914 16.109 12.96)" class="m_fh7lbas"/><ellipse fill="url(#iKuzzvd)" transform="rotate(-27.914 16.109 12.96)" class="bjroo911k"/></g><path fill="url(#iFb79nc)" class="re6m3bbul"/><path fill="url(#ixXavtb)" class="re6m3bbul"/><path fill="url(#ijqnXic)" class="re6m3bbul"/><path fill="url(#ic9VyNb)" class="re6m3bbul"/><path fill="url(#idmhp4b)" class="r9mgzz9vk"/><path fill="url(#ifmfGQd)" class="r9mgzz9vk"/><g filter="url(#i0nS04V)"><path fill="url(#i8iH8dd)" class="lhiocgbxf"/></g><g filter="url(#izvLb7c)"><path fill="url(#iU4sGAd)" class="t1etzb3lz"/></g><g filter="url(#i8lfLzd)"><path class="w5kznrbxw"/></g><g filter="url(#ibhwatc)"><path class="y_qt1oblm"/></g><g filter="url(#i12tBSc)"><path class="xoquagb8d"/></g><g filter="url(#iIxuMUb)"><path stroke="url(#iTX0hXd)" class="j3aourbny"/></g><g filter="url(#i5JhgCb)"><path stroke="url(#iqoE1Tc)" class="z8re7kpif"/></g><g filter="url(#i9eOzQc)"><path stroke="url(#itilgCc)" class="ytkfuobvu"/></g><g filter="url(#iYqdASc)"><path stroke="url(#itilgCc)" class="ct5vobbwq"/></g><g filter="url(#i4rxybe)"><path stroke="url(#iVHfEsY)" class="hl60wpbob"/></g><g filter="url(#ixFqKQc)"><path stroke="url(#iKYC9ac)" class="ae0k27b-e"/></g><g filter="url(#i74s0hb)"><path stroke="url(#igtymkc)" class="l7lzjnb_y"/></g><defs><radialGradient id="isnz1Kw" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 5.87 11.84)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="ous3tjbxu"/><stop offset="1" class="vqxmos31w"/></radialGradient><radialGradient id="iThKc4c" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 2.787 7.299)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="nb3h23xzn"/><stop offset="1" class="av_vhzb0x"/></radialGradient><radialGradient id="iEPaXld" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 4.596 5.027)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="shvpuacoj"/><stop offset="1" class="h5rrjb2yq"/></radialGradient><radialGradient id="iK2PdmU" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 6.243 3.862)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="shvpuacoj"/><stop offset="1" class="h5rrjb2yq"/></radialGradient><radialGradient id="iTt52Hd" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 3.96875 -.56716 -.09602 8.213 3.097)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="shvpuacoj"/><stop offset="1" class="h5rrjb2yq"/></radialGradient><radialGradient id="iboiDXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 9.712 3.457)" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></radialGradient><radialGradient id="icVBP4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 7.785 2.43)" gradientUnits="userSpaceOnUse"><stop class="cmb_6ubbj"/><stop offset=".994" class="h1hyg9g1x"/></radialGradient><radialGradient id="iLsG1ud" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.59 3.917)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="sl7huzb4s"/><stop offset="1" class="akhb020hk"/></radialGradient><radialGradient id="i6HNiEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 3.97 4.246)" gradientUnits="userSpaceOnUse"><stop class="q_yfvabjb"/><stop offset="1" class="vtax1pite"/></radialGradient><radialGradient id="iSjU01b" cx="0" cy="0" r="1" gradientTransform="matrix(-.88951 .77545 -.60682 -.69608 11.752 7.097)" gradientUnits="userSpaceOnUse"><stop class="l-2lm0_-n"/><stop offset="1" class="e9-zjobdb"/></radialGradient><radialGradient id="ijfr65d" cx="0" cy="0" r="1" gradientTransform="matrix(-8.71543 2.79839 -2.98394 -9.29332 26.183 27.158)" gradientUnits="userSpaceOnUse"><stop class="ip469ff8c"/><stop offset="1" class="v0q_-i93u"/></radialGradient><radialGradient id="ixJ9URb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.62502 2.66619 0 10.916 29.956)" gradientUnits="userSpaceOnUse"><stop class="xjv40os-m"/><stop offset="1" class="yrxkt-bta"/></radialGradient><radialGradient id="iZdBDDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -5.4375 0 2.979 12.957)" gradientUnits="userSpaceOnUse"><stop class="ya78f26qa"/><stop offset="1" class="jfma4ebms"/></radialGradient><radialGradient id="ig211be" cx="0" cy="0" r="1" gradientTransform="matrix(-7.94466 -1.83797 .619 -2.67566 16.993 21.259)" gradientUnits="userSpaceOnUse"><stop class="q2kyq2xrt"/><stop offset="1" class="wogt4ot2h"/></radialGradient><radialGradient id="iyWTftc" cx="0" cy="0" r="1" gradientTransform="matrix(-.74999 4.06359 -7.9403 -1.46549 14.563 19.634)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="l24x8zb-x"/><stop offset="1" class="chnw0fb8n"/></radialGradient><radialGradient id="iPzp5WD" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92844 -1.58228 0 19.011 21.144)" gradientUnits="userSpaceOnUse"><stop class="w09d9xzqo"/><stop offset="1" class="udt4b_bui"/></radialGradient><radialGradient id="iuBd4Gh" cx="0" cy="0" r="1" gradientTransform="matrix(.88576 2.38902 -2.83797 1.05222 24.634 15.27)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iZ20nnv" cx="0" cy="0" r="1" gradientTransform="matrix(1.7466 .54892 -1.69346 5.38834 11.847 15.85)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iklFZib" cx="0" cy="0" r="1" gradientTransform="matrix(-6.18431 0 0 -10.94 22.333 14.157)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="i3hbYLc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20925 14.69643 -12.17037 -1.0014 20.882 7.161)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="i7wjXpN" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.35845 1.68108 0 21.906 12.604)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iKe8IMh" cx="0" cy="0" r="1" gradientTransform="matrix(.00465 -1.29448 1.4087 .00506 16.29 12.659)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iw9xcIb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 11.294 8.026)scale(10.0704 25.7247)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iveRaZb" cx="0" cy="0" r="1" gradientTransform="matrix(4.81817 -3.1328 1.14682 1.76378 12.543 9.04)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iKmYeMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.2776 2.95435 -1.18098 -.11097 25.57 10.705)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="i5S0I4b" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 8.61 10.304)scale(3.98535 3.29023)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iXENRsl" cx="0" cy="0" r="1" gradientTransform="matrix(0 .28876 -.90754 0 19.563 15.766)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="i3s4vrH" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 8.203 9.697)scale(1.97957 3.18132)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iK5b5Mc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.8526 3.43022 0 19.011 18.343)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iSusqQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.14191 10.4744 0 12.825 10.735)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="i1vw5ue" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 18.808 -6.813)scale(2.97528 5.27161)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iSgSj9b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.79039 -1.83524 1.34716 -2.04829 23.869 4.86)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iIwVy5c" cx="0" cy="0" r="1" gradientTransform="matrix(1.0707 1.74485 -4.04025 2.47926 17.94 2.977)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="id9ASgc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.60383 0 0 -.96638 19.311 5.65)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="ip4SNxO" cx="0" cy="0" r="1" gradientTransform="matrix(3.80699 -6.02764 6.678 4.21775 12.587 10.314)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="ik2FhKu" cx="0" cy="0" r="1" gradientTransform="matrix(3.8425 .44912 -.18804 1.60878 21.079 8.415)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iLYLfUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .95975 -1.5266 0 21.593 13.073)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ix8eyjc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.887 1.365)scale(.4475 .61609)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ii7xmzm" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9598 -1.52667 0 16.43 13.073)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iKuzzvd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00915 -.58448 .70257 -.011 16.091 13.332)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixXavtb" cx="0" cy="0" r="1" gradientTransform="matrix(.74355 2.65369 -2.53182 .7094 24.474 13.09)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="ijqnXic" cx="0" cy="0" r="1" gradientTransform="matrix(.9319 -1.2789 1.07197 .78113 24.9 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="ic9VyNb" cx="0" cy="0" r="1" gradientTransform="matrix(.6944 -1.83408 2.45058 .9278 25.035 13.938)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="ifmfGQd" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 .94 11.89)scale(2.50394 2.4616)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="i8iH8dd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08415 .1861 -.08208 -.47817 13.198 13.85)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><linearGradient id="i3qU7cc" x1="6.354" x2="6.354" y1="12.501" y2="10.797" gradientUnits="userSpaceOnUse"><stop class="vym-t7ebt"/><stop offset="1" class="jb51pmjgw"/></linearGradient><linearGradient id="iIBMhxZ" x1="4.197" x2="8.572" y1="12.519" y2="12.519" gradientUnits="userSpaceOnUse"><stop class="zmcsd8b9p"/><stop offset=".743" class="zdo6gqojl"/></linearGradient><linearGradient id="if1Xczd" x1="6.467" x2="6.467" y1="11.933" y2="12.191" gradientUnits="userSpaceOnUse"><stop class="p4ezwj49r"/><stop offset="1" class="q3td6tqwm"/></linearGradient><linearGradient id="ixo6DJd" x1="9.464" x2="11.42" y1="26.625" y2="20.34" gradientUnits="userSpaceOnUse"><stop class="b05_udben"/><stop offset="1" class="a91fxs_hx"/></linearGradient><linearGradient id="imBCM1b" x1="13.703" x2="13.313" y1="24.401" y2="23.791" gradientUnits="userSpaceOnUse"><stop offset=".312" class="b2wdmyb-l"/><stop offset="1" class="pmtca2xis"/></linearGradient><linearGradient id="imfXgCe" x1="17.322" x2="19.322" y1="20.581" y2="23.956" gradientUnits="userSpaceOnUse"><stop class="c16vk8bri"/><stop offset="1" class="kt96q-sgc"/></linearGradient><linearGradient id="iEHfFmT" x1="7.01" x2="12.76" y1="15.238" y2="23.519" gradientUnits="userSpaceOnUse"><stop class="gokcfhb1a"/><stop offset="1" class="sq9q63bos"/></linearGradient><linearGradient id="irBNVId" x1="4.844" x2="4.853" y1="5.194" y2="7.196" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="iND5pVb" x1="6.264" x2="6.291" y1="4.765" y2="7.128" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="ibhenqk" x1="8.023" x2="8.026" y1="5.365" y2="6.812" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="iXOPsvc" x1="25.112" x2="19.963" y1="16.15" y2="16.15" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="imMbU4b" x1="19.067" x2="19.067" y1="21.552" y2="20.795" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="iIhzwWA" x1="20.003" x2="19.011" y1="14.955" y2="14.996" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="ibjWK5d" x1="19.011" x2="19.011" y1="16.302" y2="15.752" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="ibBn0mE" x1="19.011" x2="19.011" y1="12.807" y2="13.749" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iqPHJKO" x1="17.59" x2="17.966" y1="18.161" y2="17.174" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iEipYWd" x1="27.117" x2="13.38" y1="7.458" y2="7.458" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iUROKIe" x1="22.513" x2="22.142" y1="13.137" y2="13.365" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqiXqkb" x1="17.31" x2="16.939" y1="13.136" y2="13.365" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFb79nc" x1="26.625" x2="25.197" y1="13.168" y2="15.743" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="idmhp4b" x1="12.091" x2="13.816" y1="14.001" y2="13.851" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iU4sGAd" x1="25.418" x2="25.418" y1="12.717" y2="14.968" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iTX0hXd" x1="3.609" x2="4.029" y1="5.307" y2="7.914" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><linearGradient id="iqoE1Tc" x1="5.672" x2="5.38" y1="3.874" y2="7.871" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><linearGradient id="itilgCc" x1="7.219" x2="6.927" y1="3.818" y2="7.815" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><linearGradient id="iVHfEsY" x1="4.746" x2="3.891" y1="7.276" y2="7.143" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><linearGradient id="iKYC9ac" x1="6.176" x2="5.612" y1="7.002" y2="6.861" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><linearGradient id="igtymkc" x1="7.635" x2="7.071" y1="6.811" y2="6.669" gradientUnits="userSpaceOnUse"><stop class="hj-mkimsp"/><stop offset="1" class="dwl3kxbcz"/></linearGradient><filter id="ilfviQe" width="9.217" height="12.757" x="5.354" y="12.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".75"/></filter><filter id="ihyM7zb" width=".423" height="2.22" x="4.45" y="5.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".05"/></filter><filter id="iltGzSd" width=".345" height="2.572" x="6.005" y="4.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".05"/></filter><filter id="iIhz21d" width=".509" height="1.681" x="7.482" y="5.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".05"/></filter><filter id="iNj4YRd" width="13.09" height="14.8" x="13.022" y="6.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3862"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3862" result="effect2_innerShadow_4002_3862"/></filter><filter id="ieBm1Ce" width="4.066" height="5.431" x="16.81" y="12.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".5"/></filter><filter id="iXnGx8c" width="2.621" height="3.831" x="17.701" y="12.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".1"/></filter><filter id="ir2vsVb" width="4.307" height="1.769" x="16.858" y="16.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".05"/></filter><filter id="iCBaQdd" width="15.228" height="9.794" x="11.397" y="3.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3862"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3862" result="effect2_innerShadow_4002_3862"/></filter><filter id="irSTxDc" width="2.748" height="1.372" x="20.891" y="9.836" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3862"/></filter><filter id="i98exPb" width="2.748" height="1.354" x="14.673" y="9.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3862"/></filter><filter id="iHnrAPb" width="8.198" height="7.497" x="11.614" y="4.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3862"/><feGaussianBlur result="effect2_foregroundBlur_4002_3862" stdDeviation=".25"/></filter><filter id="i4ERTJy" width="7.98" height="7.241" x="18.573" y="4.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3862"/><feGaussianBlur result="effect2_foregroundBlur_4002_3862" stdDeviation=".25"/></filter><filter id="iljxDSd" width=".894" height=".787" x="20.742" y="12.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".05"/></filter><filter id="iN1o69c" width=".981" height="1.007" x="21.754" y="12.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".1"/></filter><filter id="iUGrxOb" width="1.094" height="1.157" x="16.499" y="12.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".1"/></filter><filter id="i0huTrd" width="1.044" height=".797" x="15.587" y="12.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".05"/></filter><filter id="i0nS04V" width="1.481" height="2.723" x="11.864" y="12.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".125"/></filter><filter id="izvLb7c" width="2.12" height="3.252" x="24.359" y="12.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".25"/></filter><filter id="i8lfLzd" width="2.708" height="1.235" x="14.646" y="9.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".125"/></filter><filter id="ibhwatc" width="2.708" height="1.235" x="20.891" y="9.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".125"/></filter><filter id="i12tBSc" width="6.455" height="3.781" x="19.939" y="5.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".5"/></filter><filter id="iIxuMUb" width="1.556" height="3.487" x="3.316" y="4.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".2"/></filter><filter id="i5JhgCb" width="1.2" height="3.889" x="5.002" y="3.474" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".2"/></filter><filter id="i9eOzQc" width="1.488" height="4.773" x="6.549" y="2.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".2"/></filter><filter id="iYqdASc" width="2.002" height="4.299" x="7.952" y="3.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".2"/></filter><filter id="i4rxybe" width="1.413" height="1.358" x="3.606" y="6.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".1"/></filter><filter id="ixFqKQc" width="1.118" height=".999" x="5.255" y="6.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".1"/></filter><filter id="i74s0hb" width="1.312" height="1.023" x="6.52" y="6.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3862" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-raising-hand-dark" /></template>
<style>
.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a91fxs_hx {
  stop-color: var(--svg-color--ff4b54, #FF4B54);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ae0k27b-e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.073 7.013c-.13.165-.332.3-.518.4");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akhb020hk {
  stop-color: var(--svg-color--685856, #685856);
  stop-opacity: 0;
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.av_vhzb0x {
  stop-color: var(--svg-color--362024, #362024);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b05_udben {
  stop-color: var(--svg-color--ff4b54, #FF4B54);
}

.b2wdmyb-l {
  stop-color: var(--svg-color--ff611d, #FF611D);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bjroo911k {
  cx: 16.109px;
  cy: 12.96px;
  rx: 0.461px;
  ry: 0.233px;
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.c16vk8bri {
  stop-color: var(--svg-color--301619, #301619);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c291hebzp {
  d: path("M19.011 17.583c-.6 0-1.164-.141-1.639-.388c-.162-.083-.336.1-.234.247c.396.6 1.087 1 1.873 1c.787 0 1.477-.4 1.873-1c.102-.153-.072-.33-.234-.247a3.54 3.54 0 0 1-1.639.388");
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c6-y3rb-s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m4.588 5.19l.148 1.946");
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.chnw0fb8n {
  stop-color: var(--svg-color--b64318, #B64318);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmb_6ubbj {
  stop-color: var(--svg-color--695755, #695755);
}

.ct5vobbwq {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m9.36 4.01l-.813 3.406");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dekbyeb3e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m6.213 4.761l-.07 2.297");
}

.df4ov0b1j {
  d: path("M19.286 7.514a3 3 0 0 1-.078-.162a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.952 1.79-3.952 3.997v.326c-.403-.306-.909-.952-.909-1.997c0-1.268.925-1.909 1.515-2.318c.167-.115.306-.212.391-.3l.118-.123c.414-.439 1.15-1.22 2.437-1.562a6.6 6.6 0 0 1 1.932-.19c.472.022.805.43.805.903v1.905z");
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dwl3kxbcz {
  stop-color: var(--svg-color--645352, #645352);
  stop-opacity: 0;
}

.e-lkx0p9a {
  fill: var(--svg-color--000, #000);
  d: path("M17.032 13.564a.6.6 0 0 0-.604-.604a.602.602 0 0 0-.538.883h1.07a.6.6 0 0 0 .072-.279");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9-zjobdb {
  stop-color: var(--svg-color--584947, #584947);
  stop-opacity: 0;
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.gb9dd3bgt {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.84 12.187c.772 0 1.425.533 1.602 1.253a.324.324 0 0 1-.316.403h-2.64a.272.272 0 0 1-.268-.322a1.654 1.654 0 0 1 1.622-1.334");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gokcfhb1a {
  stop-color: var(--svg-color--ff7636, #FF7636);
}

.gr2n-7bby {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.183 12.187c-.773 0-1.425.533-1.603 1.253a.324.324 0 0 0 .317.403h2.64a.272.272 0 0 0 .268-.322a1.66 1.66 0 0 0-1.622-1.334");
}

.gttdiwbpu {
  fill: var(--svg-color--202020, #202020);
  d: path("M23.427 10.632c-.207-.18-.448-.372-.813-.487c-.36-.113-.81-.144-1.434-.067a.328.328 0 1 0 .08.651c.568-.07.917-.034 1.157.042c.234.074.393.193.58.356a.328.328 0 0 0 .43-.495");
}

.gwk7k5bwe {
  d: path("M7.354 13.613v6.017a2 2 0 0 0 1.38 1.901l4.182 1.363");
}

.h1hyg9g1x {
  stop-color: var(--svg-color--695755, #695755);
  stop-opacity: 0;
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h5rrjb2yq {
  stop-color: var(--svg-color--301715, #301715);
  stop-opacity: 0;
}

.hj-mkimsp {
  stop-color: var(--svg-color--645352, #645352);
}

.hl60wpbob {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M3.906 7.979c.11-.063.617-.38.813-.758");
}

.hmg_eabyj {
  d: path("M19.011 23.957c-1.268 0-2.296-.986-2.296-2.2v-2.6c0-1.215 1.028-2.2 2.296-2.2s2.296.985 2.296 2.2v2.6c0 1.214-1.028 2.2-2.296 2.2");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hqne3dvml {
  d: path("m18.56 13.311l-.63 2.175c-.128.447.18.895.616.895h.93c.437 0 .745-.455.616-.895l-.628-2.175c-.135-.482-.764-.482-.905 0");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ip469ff8c {
  stop-color: var(--svg-color--ff8045, #FF8045);
}

.izdg-vbmr {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M19.286 7.514a3 3 0 0 1-.078-.162a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.952 1.79-3.952 3.997v.326c-.403-.306-.909-.952-.909-1.997c0-1.268.925-1.909 1.515-2.318c.167-.115.306-.212.391-.3l.118-.123c.414-.439 1.15-1.22 2.437-1.562a6.6 6.6 0 0 1 1.932-.19c.472.022.805.43.805.903v1.905z");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j3aourbny {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m3.914 4.83l.36 2.633");
}

.j5wacnblk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m7.854 5.363l-.235 1.406");
}

.jb51pmjgw {
  stop-color: var(--svg-color--3d1a14, #3D1A14);
  stop-opacity: 0;
}

.jfma4ebms {
  stop-color: var(--svg-color--ff7c1f, #FF7C1F);
  stop-opacity: 0;
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k35cj8b6j {
  stop-color: var(--svg-color--685755, #685755);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kt96q-sgc {
  stop-color: var(--svg-color--533532, #533532);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l-2lm0_-n {
  stop-color: var(--svg-color--584947, #584947);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l24x8zb-x {
  stop-color: var(--svg-color--b64318, #B64318);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l7lzjnb_y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.532 6.822c-.13.164-.5.36-.712.422");
}

.l7n7uk6bh {
  stop-color: var(--svg-color--331c1a, #331C1A);
  stop-opacity: 0;
}

.ld8yw_opa {
  d: path("M22.535 13.425a1 1 0 0 0-.273-.547l-.308.337l.139.27z");
}

.lhiocgbxf {
  d: path("M12.995 12.739a1.13 1.13 0 0 0 .1 2.223a92 92 0 0 1-.1-2.223");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m_fh7lbas {
  cx: 16.109px;
  cy: 12.96px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.461px;
  ry: 0.233px;
}

.m-vdsbczh {
  fill: var(--svg-color--402929, #402929);
  d: path("m18.56 13.311l-.63 2.175c-.128.447.18.895.616.895h.93c.437 0 .745-.455.616-.895l-.628-2.175c-.135-.482-.764-.482-.905 0");
}

.m16jdvb1f {
  stop-color: var(--svg-color--685755, #685755);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mlatt2b4d {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m25.178 11.378l-.035-.747c-.012-.903-.759-1.648-1.662-1.686h-1.657a2.86 2.86 0 0 1-2.512-1.49s-.123-.286-.214-.748c-.192-.985.727-1.716 1.715-1.545c1.221.211 2.689.61 3.748 1.302c2.064 1.346 1.703 3.772.617 4.914");
}

.mqr82bb3g {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m18.536 13.543l-.699 2.175c-.119.447.168.894.574.894h.865c.406 0 .692-.454.573-.894l-.585-2.175c-.125-.482-.596-.482-.728 0");
}

.nb3h23xzn {
  stop-color: var(--svg-color--362024, #362024);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o7f5t3bcv {
  d: path("M21.595 12.509a1.056 1.056 0 0 1 1.017 1.334h-2.04a1.06 1.06 0 0 1 1.022-1.334");
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ous3tjbxu {
  stop-color: var(--svg-color--482f30, #482F30);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p4ezwj49r {
  stop-color: var(--svg-color--dd6422, #DD6422);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.p99zmmcea {
  d: path("M21.517 12.732c.076.1-.082.223-.26.357c-.18.133-.312.227-.387.127s.009-.29.187-.424c.18-.134.385-.16.46-.06");
}

.pcy7xu8cs {
  fill: var(--svg-color--202020, #202020);
  d: path("M14.976 10.503a3.28 3.28 0 0 1 2.057-.425a.328.328 0 1 1-.08.651a2.63 2.63 0 0 0-1.64.337a2 2 0 0 0-.108.07l-.004.003a.328.328 0 0 1-.401-.519z");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmtca2xis {
  stop-color: var(--svg-color--ff611d, #FF611D);
  stop-opacity: 0;
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.q_sz55bis {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.517 12.732c.076.1-.082.223-.26.357c-.18.133-.312.227-.387.127s.009-.29.187-.424c.18-.134.385-.16.46-.06");
}

.q_yfvabjb {
  stop-color: var(--svg-color--685756, #685756);
}

.q2kyq2xrt {
  stop-color: var(--svg-color--d93f13, #D93F13);
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q3td6tqwm {
  stop-color: var(--svg-color--dd6422, #DD6422);
  stop-opacity: 0;
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

.qsghvrbrr {
  d: path("M24.754 6.299a2.74 2.74 0 0 1 1.5 1.243c.552.97.47 2.132-.126 2.989c-.207.304-.32.666-.32 1.034v1.405a2.1 2.1 0 0 0-.789-.317l.093-1.9a1.715 1.715 0 0 0-1.631-1.694h-1.657a2.87 2.87 0 0 1-2.616-1.707a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.952 1.79-3.952 3.997l.036 1.819c-.3.044-.614.144-.852.312v-1.42c0-.368-.113-.73-.32-1.034a2.83 2.83 0 0 1-.17-2.894a2.77 2.77 0 0 1 1.538-1.332A3.17 3.17 0 0 0 14.89 4.99a2.75 2.75 0 0 1 3.42-1.078c.451.196.96.196 1.411 0a2.8 2.8 0 0 1 1.08-.222c.997 0 1.87.54 2.352 1.339c.364.602.935 1.04 1.6 1.268");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw26w4bib {
  d: path("M24.762 15.635a1.94 1.94 0 0 0 1.07-.365v1.102a2.57 2.57 0 0 1-1.586 2.388c.201-.43.34-.897.409-1.396z");
}

.r00geccly {
  d: path("M17.392 13.44c0-.341-.277-.568-.352-.637l-.341.33l.21.427z");
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.r9mgzz9vk {
  d: path("M13.033 11.958a1.904 1.904 0 0 0 .163 3.785a92 92 0 0 1-.163-3.785");
}

.re6m3bbul {
  d: path("M24.834 15.743q.117-1.889.218-3.775a1.904 1.904 0 0 1-.218 3.775");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.shvpuacoj {
  stop-color: var(--svg-color--301715, #301715);
}

.sl7huzb4s {
  stop-color: var(--svg-color--685856, #685856);
}

.snc5bxbfc {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.407 17.128a3.5 3.5 0 0 0 1.604.38c.595 0 1.141-.138 1.604-.38h.001a.26.26 0 0 1 .304.05a.24.24 0 0 1 .027.305l-.063-.041c-.396.6-1.086 1-1.873 1a2.24 2.24 0 0 1-1.873-1zm0 0a.26.26 0 0 0-.305.052a.24.24 0 0 0-.026.304z");
}

.sq9q63bos {
  stop-color: var(--svg-color--ff7636, #FF7636);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t0gx7kh4f {
  d: path("m25.178 11.378l-.035-.747c-.012-.903-.759-1.648-1.662-1.686h-1.657a2.86 2.86 0 0 1-2.512-1.49s-.123-.286-.214-.748c-.192-.985.727-1.716 1.715-1.545c1.221.211 2.689.61 3.748 1.302c2.064 1.346 1.703 3.772.617 4.914");
}

.t1etzb3lz {
  d: path("M24.859 14.968q.069-1.125.13-2.251a1.13 1.13 0 0 1-.13 2.251");
}

.tbcd_1bft {
  d: path("M3.291 9.204c-.125-1.922-.281-2.959-.328-3.64c-.035-.513.024-1.067.711-1.192c.598-.074.883.452.906.66c-.002-.2 0-.68 0-.805c0-.21.008-.976.86-.976c.601 0 .816.587.8.863c.01-.102.023-.413.036-.707c.018-.433.251-.99.945-.977c.598.04.793.614.766.977l-.118 1.867c.024-.187.103-.665.278-1.34s.701-.72.957-.683c.326.046.88.36.648 1.273C9.477 5.68 9.29 7.17 9.225 7.81c.324-.133.642-.412 1.002-.787c.359-.375.886-.383 1.183-.16c.34.292.522.967.12 1.37c-.463.424-2.13 2.404-2.957 3.394c-.23.291-.997.875-2.235.875c-2.203-.094-2.941-1.676-3.047-3.297");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u9c_rrbwd {
  fill: var(--svg-color--ff611d, #FF611D);
  d: path("M20.038 20.957h.973c2.5 0 7.5 3.5 7.5 9h-18v-3.5a.67.67 0 0 0-.416-.626l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.197V13.97c0-.564.425-1.014.936-1.014h4.129c.52 0 .935.46.935 1.014v3.985c0 1.303 1 1.5 1 1.5l6 1.5z");
}

.udt4b_bui {
  stop-color: var(--svg-color--3e232f, #3E232F);
  stop-opacity: 0;
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.v0q_-i93u {
  stop-color: var(--svg-color--ff8045, #FF8045);
  stop-opacity: 0;
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v84_1vemz {
  d: path("M13.26 15.635a1.94 1.94 0 0 1-1.07-.365v1.102a2.57 2.57 0 0 0 1.587 2.388a4.8 4.8 0 0 1-.41-1.396z");
}

.vqxmos31w {
  stop-color: var(--svg-color--432927, #432927);
}

.vtax1pite {
  stop-color: var(--svg-color--685756, #685756);
  stop-opacity: 0;
}

.vym-t7ebt {
  stop-color: var(--svg-color--3d1a14, #3D1A14);
}

.w09d9xzqo {
  stop-color: var(--svg-color--3e232f, #3E232F);
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

.w5kznrbxw {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.021 10.834c.304-.218 1.062-.602 1.958-.451");
}

.wogt4ot2h {
  stop-color: var(--svg-color--d93f13, #D93F13);
  stop-opacity: 0;
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x70fxwi3o {
  d: path("M16.428 12.509a1.056 1.056 0 0 0-1.018 1.334h2.04q.037-.136.038-.279a1.063 1.063 0 0 0-1.06-1.056");
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xf3kzvrmp {
  fill: var(--svg-color--000, #000);
  d: path("M20.99 13.564c0-.336.27-.604.605-.604a.602.602 0 0 1 .538.883h-1.07a.55.55 0 0 1-.073-.279");
}

.xgubwvapl {
  d: path("M4.361 12.133c0-.11.09-.2.2-.2h3.811c.11 0 .2.09.2.2v1.714h-4.21z");
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xjv40os-m {
  stop-color: var(--svg-color--ff6e45, #FF6E45);
}

.xnnb4wkvy {
  d: path("M13.304 17.427a4.63 4.63 0 0 0 4.596 4.03h2.232a4.63 4.63 0 0 0 4.596-4.03c.14-2.228.28-4.447.384-6.674a1.715 1.715 0 0 0-1.631-1.694h-1.657a2.87 2.87 0 0 1-2.616-1.707a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.952 1.79-3.952 3.997c0 2.201.137 4.367.281 6.573");
}

.xoquagb8d {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M23.971 7.534H21.51a.57.57 0 1 1 .092-1.137c.639.102 1.487.244 2.055.385c1.284.318 1.638.943 1.737 1.389a1.79 1.79 0 0 0-1.422-.637");
}

.xtq70kbcj {
  d: path("M20.038 20.957h.973c2.5 0 7.5 3.5 7.5 9h-18v-3.5a.67.67 0 0 0-.416-.626l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.197V13.97c0-.564.425-1.014.936-1.014h4.129c.52 0 .935.46.935 1.014v3.985c0 1.303 1 1.5 1 1.5l6 1.5z");
}

.y_qt1oblm {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.224 10.78c-.304-.219-1.062-.603-1.958-.452");
}

.ya78f26qa {
  stop-color: var(--svg-color--ff7c1f, #FF7C1F);
}

.yrxkt-bta {
  stop-color: var(--svg-color--ff6e45, #FF6E45);
  stop-opacity: 0;
}

.ytkfuobvu {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.438 2.963l-.29 3.944");
}

.z0iyhs38d {
  stop-color: var(--svg-color--331c1a, #331C1A);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z8re7kpif {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.602 3.874v3.089");
}

.zdo6gqojl {
  stop-color: var(--svg-color--d64d18, #D64D18);
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zmcsd8b9p {
  stop-color: var(--svg-color--e6724b, #E6724B);
}

.zrrxx6xii {
  d: path("m18.37 21.066l-7.875 5.245a.66.66 0 0 0-.4-.48l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.197V13.97c0-.564.425-1.014.936-1.014h4.129c.52 0 .935.46.935 1.014v3.985c0 1.303 1 1.5 1 1.5l6 1.5z");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
