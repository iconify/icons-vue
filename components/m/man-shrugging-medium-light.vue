<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#imHC7fb)" clip-rule="evenodd" class="pmvuw6bxy"/><path fill="url(#i1LrTbe)" clip-rule="evenodd" class="pmvuw6bxy"/><g filter="url(#ijch4kd)"><path stroke="url(#ipCEfHN)" class="q3u2-ob7j"/></g><path fill="url(#izGYPVc)" clip-rule="evenodd" class="o9mwykjzf"/><path fill="url(#iI1JRBd)" clip-rule="evenodd" class="o9mwykjzf"/><g filter="url(#iM2G0sc)"><path stroke="url(#i63iC1c)" class="cw0en3yrc"/></g><path fill="url(#iTwGCZb)" clip-rule="evenodd" class="hhcl8xbac"/><path fill="url(#iYJUStb)" clip-rule="evenodd" class="hhcl8xbac"/><g filter="url(#iZnonPB)"><path stroke="url(#ijk12Kb)" class="pg859nb_v"/></g><path fill="url(#iov1WpW)" clip-rule="evenodd" class="h-z618biu"/><path fill="url(#iaATKge)" clip-rule="evenodd" class="h-z618biu"/><path class="mskv0-bok"/><path fill="url(#iQxWp7b)" class="u1__hxdnm"/><path fill="url(#i0VvDZb)" class="u1__hxdnm"/><path fill="url(#iQVKtPz)" class="u1__hxdnm"/><path fill="url(#iTjd43d)" class="u1__hxdnm"/><g filter="url(#i2yw5Jd)"><path class="r-mgr_bxp"/><path fill="url(#ivVgICc)" class="h_73z-b9e"/><path fill="url(#icbuouw)" class="h_73z-b9e"/></g><path fill="url(#ir24Uwc)" clip-rule="evenodd" class="l7-82eghs"/><path fill="url(#ik4vtRD)" clip-rule="evenodd" class="l7-82eghs"/><path fill="url(#ilD5eYd)" clip-rule="evenodd" class="l7-82eghs"/><path fill="url(#izlcQsc)" clip-rule="evenodd" class="l7-82eghs"/><path fill="url(#i6GUvFg)" clip-rule="evenodd" class="hsmz9_6vn"/><path fill="url(#ihZgeWP)" clip-rule="evenodd" class="hsmz9_6vn"/><path fill="url(#i8cfNqi)" clip-rule="evenodd" class="hsmz9_6vn"/><path fill="url(#iQBsmnd)" clip-rule="evenodd" class="hsmz9_6vn"/><path fill="url(#ii4euLb)" clip-rule="evenodd" class="lii4b5bpn"/><path fill="url(#ipv5YRc)" clip-rule="evenodd" class="lii4b5bpn"/><path fill="url(#iEpihgb)" clip-rule="evenodd" class="lii4b5bpn"/><path fill="url(#its4DFe)" clip-rule="evenodd" class="lii4b5bpn"/><path fill="url(#i1qC8sb)" clip-rule="evenodd" class="b_bzxih3c"/><path fill="url(#illRgPe)" clip-rule="evenodd" class="b_bzxih3c"/><path fill="url(#iPHX82W)" clip-rule="evenodd" class="b_bzxih3c"/><path fill="url(#iHc35Ib)" clip-rule="evenodd" class="b_bzxih3c"/><g filter="url(#ipuGhfd)"><path stroke="url(#iCtm8zd)" class="ou9iweytm"/></g><path fill="url(#ilTwhlc)" class="o5kh6zbhk"/><path fill="url(#iIaYETc)" class="o5kh6zbhk"/><path fill="url(#iCQJnXb)" class="zap_rqapx"/><path fill="url(#iQvhDPw)" class="zap_rqapx"/><path fill="url(#iiJOS0d)" class="zap_rqapx"/><g filter="url(#ijIjMpc)"><path fill="url(#i6Augzc)" class="u8buv18hy"/><path fill="url(#iBKkgsc)" class="u8buv18hy"/><path fill="url(#ivlcVJd)" class="u8buv18hy"/><path fill="url(#iw2ab0b)" class="u8buv18hy"/><path fill="url(#iOeoofd)" class="u8buv18hy"/></g><path fill="url(#izjFSjd)" class="iyp7p_joe"/><path fill="url(#iu1Gsqb)" class="iyp7p_joe"/><g filter="url(#i21lUAe)"><path class="h_f8hwhpp"/></g><g filter="url(#igucmVc)"><path class="mdcg8dd5q"/></g><g filter="url(#iHnFYyc)"><path stroke="url(#iY8frCc)" class="sjzxdti2m"/></g><g filter="url(#isln1Le)"><path fill="url(#iVngfqd)" class="uvwg3fmlf"/></g><g filter="url(#iN9hYcc)"><circle fill="url(#iNWyIAd)" transform="rotate(-4.496 11.135 13.127)" class="eg4b6ojxi"/></g><g filter="url(#iXswpie)"><circle fill="url(#inoWP6I)" transform="rotate(-4.496 11.135 13.127)" class="z1-d-2bfy"/></g><g filter="url(#isrIoTv)"><circle fill="url(#iipcyVa)" transform="rotate(-4.496 19.98 12.432)" class="paumsgmxe"/><circle fill="url(#iRD1v4d)" transform="rotate(-4.496 19.98 12.432)" class="paumsgmxe"/></g><g filter="url(#iqxiA5b)"><circle transform="rotate(-4.496 19.98 12.432)" class="mh71_3bcu"/><circle fill="url(#i7g8FUb)" transform="rotate(-4.496 19.98 12.432)" class="d76z83bvl"/><circle fill="url(#ik9SMwd)" transform="rotate(-4.496 19.98 12.432)" class="d76z83bvl"/></g><g filter="url(#iW4o94b)"><path fill="url(#illm6Pd)" class="hzf9jo3eo"/><path fill="url(#iywQR2c)" class="hzf9jo3eo"/><path fill="url(#it3Zn9N)" class="hzf9jo3eo"/><path fill="url(#i6bUw7b)" class="hzf9jo3eo"/><path fill="url(#iSTEWde)" class="hzf9jo3eo"/></g><g filter="url(#i9737De)"><path class="k-no2b-rk"/><path fill="url(#i2Ux35B)" class="elmbrlbch"/><path fill="url(#idxu1Vc)" class="elmbrlbch"/><path fill="url(#iMEEoiq)" class="elmbrlbch"/><path fill="url(#ip1mVhd)" class="elmbrlbch"/><path fill="url(#iRHBONd)" class="elmbrlbch"/></g><path fill="url(#ij2X0Bc)" class="elmbrlbch"/><path fill="url(#iDmYMXd)" class="elmbrlbch"/><g filter="url(#isUrlRb)"><path class="z53i_7bit"/></g><g filter="url(#iYhJ2mc)"><path class="k3un0nv9d"/><path fill="url(#ibS2jOb)" class="a9-olubxk"/><path fill="url(#ionNNfc)" class="a9-olubxk"/><path fill="url(#ifKMtmd)" class="a9-olubxk"/></g><path fill="url(#i0n8Jed)" class="a9-olubxk"/><g filter="url(#igJhzid)"><path class="uvndg_buj"/></g><g filter="url(#iK2FfEb)"><path class="cj-j-xbpi"/></g><path class="f-m-__64y"/><path fill="url(#iBDDlIe)" class="aqh32r1du"/><path class="svn8oxbdh"/><g filter="url(#iPWGQAb)"><path class="xbebtfb5z"/><path fill="url(#iEFoM6d)" class="kzn56abzk"/></g><g filter="url(#isOrxfe)"><path fill="url(#ifAxpjd)" class="i44w2qbjz"/></g><path class="of_s6zb_u"/><path fill="url(#iq0aFFb)" class="zt97zgsgs"/><path class="rfdt237zi"/><g filter="url(#ijgObOc)"><path fill="url(#ihCwD3X)" class="jiqirubjz"/></g><g filter="url(#iM7u1Pb)"><ellipse transform="rotate(-32.41 13.21 12.237)" class="sesnm-bka"/><ellipse fill="url(#ima31qd)" transform="rotate(-32.41 13.21 12.237)" class="l2gakx84d"/></g><g filter="url(#i5PewKb)"><path stroke="url(#im2MHlb)" class="ltkp3rbye"/></g><g filter="url(#iPpYlIc)"><path stroke="url(#iEwNbmc)" class="y-po_4ueh"/></g><g filter="url(#iMoXlve)"><ellipse stroke="url(#iyYVwZI)" class="oxwoqzt3c"/></g><ellipse class="zis_ubcvg"/><defs><radialGradient id="i1LrTbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.6217 1.72506 -3.88088 -1.39866 5.197 12.664)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="ye-2zryyr"/><stop offset=".85" class="d8xtj4b7u"/></radialGradient><radialGradient id="iI1JRBd" cx="0" cy="0" r="1" gradientTransform="rotate(106.399 -2.923 8.023)scale(1.96628 3.75623)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="ye-2zryyr"/><stop offset=".85" class="d8xtj4b7u"/></radialGradient><radialGradient id="iYJUStb" cx="0" cy="0" r="1" gradientTransform="rotate(110.767 -2.726 8.43)scale(1.80306 4.21624)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="ye-2zryyr"/><stop offset=".85" class="d8xtj4b7u"/></radialGradient><radialGradient id="iaATKge" cx="0" cy="0" r="1" gradientTransform="matrix(-.64062 1.48565 -3.81 -1.6429 4.507 14.86)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="ye-2zryyr"/><stop offset=".85" class="d8xtj4b7u"/></radialGradient><radialGradient id="i0VvDZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.52138 .86916 -1.0215 -.61276 7.056 11.246)" gradientUnits="userSpaceOnUse"><stop class="i2dy_3bdc"/><stop offset="1" class="s_o7_jesn"/></radialGradient><radialGradient id="iQVKtPz" cx="0" cy="0" r="1" gradientTransform="matrix(-2.70312 0 0 -.65716 6.913 16.403)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="wj8c2lbyu"/><stop offset="1" class="yn5ij1ffp"/></radialGradient><radialGradient id="iTjd43d" cx="0" cy="0" r="1" gradientTransform="matrix(1.36718 .96094 -1.5586 2.2175 5.132 13.665)" gradientUnits="userSpaceOnUse"><stop class="e490wkn-s"/><stop offset="1" class="bn4os6vdu"/></radialGradient><radialGradient id="ivVgICc" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 -1.22657 .626 .09968 26.132 13.211)" gradientUnits="userSpaceOnUse"><stop class="j2l239u6e"/><stop offset="1" class="a3e1obbdc"/></radialGradient><radialGradient id="icbuouw" cx="0" cy="0" r="1" gradientTransform="matrix(.60156 -.63281 .3758 .35725 26.14 11.563)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="jsiezd-_e"/><stop offset="1" class="wr4xjslhr"/></radialGradient><radialGradient id="ik4vtRD" cx="0" cy="0" r="1" gradientTransform="matrix(1.18749 1.5 -2.61214 2.06791 26.695 12.344)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="i9k-0jbxt"/><stop offset="1" class="d8_6n5bpd"/></radialGradient><radialGradient id="ilD5eYd" cx="0" cy="0" r="1" gradientTransform="matrix(.66176 -.53537 .3309 .40903 28.495 11.772)" gradientUnits="userSpaceOnUse"><stop class="nhxwftdxc"/><stop offset="1" class="axz4ivbcr"/></radialGradient><radialGradient id="izlcQsc" cx="0" cy="0" r="1" gradientTransform="matrix(1.06322 1.21875 -1.34641 1.1746 27.131 12.297)" gradientUnits="userSpaceOnUse"><stop class="i9x98ebrr"/><stop offset="1" class="yk15gqvvr"/></radialGradient><radialGradient id="ihZgeWP" cx="0" cy="0" r="1" gradientTransform="rotate(74.107 5.6 24.794)scale(2.45789 3.78855)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="i9k-0jbxt"/><stop offset="1" class="d8_6n5bpd"/></radialGradient><radialGradient id="i8cfNqi" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.58594 .36956 .3942 29.562 12.118)" gradientUnits="userSpaceOnUse"><stop class="nhxwftdxc"/><stop offset="1" class="axz4ivbcr"/></radialGradient><radialGradient id="iQBsmnd" cx="0" cy="0" r="1" gradientTransform="matrix(.82807 .89964 -1.70806 1.57218 28.148 12.86)" gradientUnits="userSpaceOnUse"><stop class="i9x98ebrr"/><stop offset="1" class="yk15gqvvr"/></radialGradient><radialGradient id="ipv5YRc" cx="0" cy="0" r="1" gradientTransform="rotate(70.854 4.355 26.275)scale(2.23451 4.05178)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="i9k-0jbxt"/><stop offset="1" class="d8_6n5bpd"/></radialGradient><radialGradient id="iEpihgb" cx="0" cy="0" r="1" gradientTransform="matrix(.42197 -.61719 .33958 .23217 29.632 13.196)" gradientUnits="userSpaceOnUse"><stop class="nhxwftdxc"/><stop offset="1" class="axz4ivbcr"/></radialGradient><radialGradient id="its4DFe" cx="0" cy="0" r="1" gradientTransform="rotate(55.566 1.44 33.605)scale(.98095 1.76017)" gradientUnits="userSpaceOnUse"><stop class="i9x98ebrr"/><stop offset="1" class="yk15gqvvr"/></radialGradient><radialGradient id="illRgPe" cx="0" cy="0" r="1" gradientTransform="matrix(.73437 1.86015 -3.71825 1.46794 27.431 14.485)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="i9k-0jbxt"/><stop offset="1" class="d8_6n5bpd"/></radialGradient><radialGradient id="iPHX82W" cx="0" cy="0" r="1" gradientTransform="rotate(-36.12 36.55 -38.032)scale(.69635 .37124)" gradientUnits="userSpaceOnUse"><stop class="nhxwftdxc"/><stop offset="1" class="axz4ivbcr"/></radialGradient><radialGradient id="iHc35Ib" cx="0" cy="0" r="1" gradientTransform="matrix(.42188 .76563 -.90043 .49616 28.132 14.188)" gradientUnits="userSpaceOnUse"><stop class="i9x98ebrr"/><stop offset="1" class="yk15gqvvr"/></radialGradient><radialGradient id="ilTwhlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94297 -2.39063 0 26.203 16.232)" gradientUnits="userSpaceOnUse"><stop class="gqn4jccjs"/><stop offset="1" class="wjksmgbzx"/></radialGradient><radialGradient id="iQvhDPw" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.14902 -.68994 0 7.563 16.463)" gradientUnits="userSpaceOnUse"><stop class="ne51g8a0v"/><stop offset="1" class="opxc931wt"/></radialGradient><radialGradient id="i6Augzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4411 10.6867 0 19.921 29.217)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g6k-1hpjs"/><stop offset="1" class="msi6qbbpq"/></radialGradient><radialGradient id="iBKkgsc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01666 3.53393 -1.57189 -1.3418 9.813 19.831)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="k20ytgb7v"/><stop offset="1" class="mtrk0zxts"/><stop offset="1" class="jbumt9bvj"/></radialGradient><radialGradient id="ivlcVJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.46944 -4.08022 0 27.015 16.779)" gradientUnits="userSpaceOnUse"><stop class="f51--cb4u"/><stop offset="1" class="sp_au2bah"/></radialGradient><radialGradient id="iw2ab0b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2344 3.40893 -.45438 -.29783 9.719 19.956)" gradientUnits="userSpaceOnUse"><stop class="o18y7cctk"/><stop offset="1" class="p8zx0emkh"/></radialGradient><radialGradient id="iOeoofd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.68753 3.4062 -1.542 -2.57478 14.422 17.706)" gradientUnits="userSpaceOnUse"><stop offset=".066" class="ok0pekb3m"/><stop offset="1" class="l6xrk1bwj"/></radialGradient><radialGradient id="izjFSjd" cx="0" cy="0" r="1" gradientTransform="matrix(2.0625 2.17783 -3.3043 3.12931 15.594 17.942)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="id9ofabvx"/><stop offset="1" class="mb-6y2bmd"/></radialGradient><radialGradient id="iNWyIAd" cx="0" cy="0" r="1" gradientTransform="matrix(1.63652 0 0 2.86393 9.578 13.127)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iRD1v4d" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 28.88 -25.131)scale(.95368 1.0885)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="i7g8FUb" cx="0" cy="0" r="1" gradientTransform="matrix(.7659 -1.40866 .8245 .44828 19.94 13.199)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="ik9SMwd" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -5.126 30.509)scale(.34023 .4386)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iywQR2c" cx="0" cy="0" r="1" gradientTransform="rotate(91.545 3.261 13.068)scale(9.8688 9.4287)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="mx6r32s2r"/><stop offset=".835" class="a-e0cj8zq"/><stop offset="1" class="j61mf2btk"/></radialGradient><radialGradient id="i6bUw7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.09555 -1.21519 1.49561 -.1176 17.638 11.425)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iSTEWde" cx="0" cy="0" r="1" gradientTransform="rotate(-94.496 12.12 -.328)scale(1.29707 1.61303)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="i2Ux35B" cx="0" cy="0" r="1" gradientTransform="rotate(123.31 7.769 7.638)scale(5.22812 8.89088)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iMEEoiq" cx="0" cy="0" r="1" gradientTransform="matrix(-.1982 -1.72571 .84754 -.09734 11.399 9.874)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="ip1mVhd" cx="0" cy="0" r="1" gradientTransform="matrix(.65498 -1.89103 1.54228 .53418 19.351 10.856)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="iRHBONd" cx="0" cy="0" r="1" gradientTransform="matrix(1.01305 1.07267 -.9471 .89445 14.2 4.84)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="ij2X0Bc" cx="0" cy="0" r="1" gradientTransform="rotate(72.465 4.554 12.988)scale(.74971 1.23255)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iDmYMXd" cx="0" cy="0" r="1" gradientTransform="matrix(.7401 .7812 -1.75037 1.65828 11.007 6.708)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="iBDDlIe" cx="0" cy="0" r="1" gradientTransform="rotate(85.504 2.124 15.64)scale(.84225 .9966)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iEFoM6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.2374 -.26082 .3591 -.32686 17.32 12.081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iq0aFFb" cx="0" cy="0" r="1" gradientTransform="matrix(.06603 .8397 -.99358 .07813 13.493 12.616)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ima31qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00721 -.46066 .55373 -.00867 13.196 12.53)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="imHC7fb" x1="3.956" x2="6.671" y1="12.827" y2="12.827" gradientUnits="userSpaceOnUse"><stop class="a0zgi_bwh"/><stop offset="1" class="jnwaoyb2q"/></linearGradient><linearGradient id="ipCEfHN" x1="4.263" x2="6.419" y1="11.935" y2="14.085" gradientUnits="userSpaceOnUse"><stop class="aa675bbim"/><stop offset="1" class="ocrbm8rzk"/></linearGradient><linearGradient id="izGYPVc" x1="2.841" x2="5.265" y1="13.271" y2="13.271" gradientUnits="userSpaceOnUse"><stop class="a0zgi_bwh"/><stop offset="1" class="jnwaoyb2q"/></linearGradient><linearGradient id="i63iC1c" x1="3.195" x2="5.606" y1="12.205" y2="14.419" gradientUnits="userSpaceOnUse"><stop class="aa675bbim"/><stop offset="1" class="ocrbm8rzk"/></linearGradient><linearGradient id="iTwGCZb" x1="2.914" x2="5.705" y1="14.128" y2="14.128" gradientUnits="userSpaceOnUse"><stop class="a0zgi_bwh"/><stop offset="1" class="jnwaoyb2q"/></linearGradient><linearGradient id="ijk12Kb" x1="3.12" x2="5.711" y1="13.197" y2="15.195" gradientUnits="userSpaceOnUse"><stop class="aa675bbim"/><stop offset="1" class="ocrbm8rzk"/></linearGradient><linearGradient id="iov1WpW" x1="3.228" x2="6.025" y1="15.001" y2="15.001" gradientUnits="userSpaceOnUse"><stop class="a0zgi_bwh"/><stop offset="1" class="jnwaoyb2q"/></linearGradient><linearGradient id="iQxWp7b" x1="8.755" x2="7.914" y1="15.479" y2="15.479" gradientUnits="userSpaceOnUse"><stop offset=".005" class="vh9-3hb_g"/><stop offset="1" class="av75tqbdq"/></linearGradient><linearGradient id="ir24Uwc" x1="28.391" x2="25.698" y1="13.636" y2="13.596" gradientUnits="userSpaceOnUse"><stop class="fgtz1bcwy"/><stop offset="1" class="qx0aig_op"/></linearGradient><linearGradient id="i6GUvFg" x1="29.464" x2="26.92" y1="14.158" y2="14.125" gradientUnits="userSpaceOnUse"><stop class="fgtz1bcwy"/><stop offset="1" class="qx0aig_op"/></linearGradient><linearGradient id="ii4euLb" x1="29.437" x2="26.667" y1="14.919" y2="14.875" gradientUnits="userSpaceOnUse"><stop class="fgtz1bcwy"/><stop offset="1" class="qx0aig_op"/></linearGradient><linearGradient id="i1qC8sb" x1="29.123" x2="26.348" y1="15.698" y2="15.648" gradientUnits="userSpaceOnUse"><stop class="fgtz1bcwy"/><stop offset="1" class="qx0aig_op"/></linearGradient><linearGradient id="iCtm8zd" x1="3.408" x2="6.216" y1="14.224" y2="15.905" gradientUnits="userSpaceOnUse"><stop class="aa675bbim"/><stop offset="1" class="ocrbm8rzk"/></linearGradient><linearGradient id="iIaYETc" x1="23.662" x2="24.149" y1="17.214" y2="17.206" gradientUnits="userSpaceOnUse"><stop class="g15pupb2m"/><stop offset="1" class="dqcsylboi"/></linearGradient><linearGradient id="iCQJnXb" x1="7.031" x2="9.719" y1="16.922" y2="16.922" gradientUnits="userSpaceOnUse"><stop class="gy5j7812b"/><stop offset="1" class="vw_f_cbup"/></linearGradient><linearGradient id="iiJOS0d" x1="6.873" x2="6.873" y1="16.232" y2="16.495" gradientUnits="userSpaceOnUse"><stop class="z96fdub7f"/><stop offset="1" class="j3txnddmt"/></linearGradient><linearGradient id="iu1Gsqb" x1="13.125" x2="15.688" y1="19.62" y2="19.62" gradientUnits="userSpaceOnUse"><stop class="f0wda1gby"/><stop offset="1" class="xjqh_ibco"/></linearGradient><linearGradient id="iY8frCc" x1="9.86" x2="12.86" y1="25.951" y2="20.294" gradientUnits="userSpaceOnUse"><stop class="zuuvnac4f"/><stop offset="1" class="bb3cu5wqs"/></linearGradient><linearGradient id="iVngfqd" x1="25.449" x2="21.21" y1="26.036" y2="21.322" gradientUnits="userSpaceOnUse"><stop class="z108ppbpv"/><stop offset="1" class="sv_dn8bha"/></linearGradient><linearGradient id="inoWP6I" x1="11.135" x2="10.538" y1="13.387" y2="13.387" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iipcyVa" x1="20.993" x2="20.229" y1="11.414" y2="13.779" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="illm6Pd" x1="19.33" x2="12.313" y1="12.847" y2="14.463" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="it3Zn9N" x1="10.758" x2="12.886" y1="16.043" y2="15.594" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="idxu1Vc" x1="11.011" x2="13.332" y1="12.887" y2="7.883" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="ibS2jOb" x1="14.823" x2="15.695" y1="13.818" y2="13.75" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="ionNNfc" x1="16.522" x2="15.567" y1="13.986" y2="14.048" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="ifKMtmd" x1="15.885" x2="15.843" y1="14.731" y2="14.198" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="i0n8Jed" x1="15.824" x2="15.812" y1="14.775" y2="14.619" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="ifAxpjd" x1="18.252" x2="17.975" y1="11.98" y2="12.183" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihCwD3X" x1="14.164" x2="13.887" y1="12.302" y2="12.504" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="im2MHlb" x1="18.11" x2="17.657" y1="9.99" y2="9.222" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iEwNbmc" x1="13.169" x2="12.027" y1="10.259" y2="9.882" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iyYVwZI" x1="15.582" x2="15.899" y1="16.845" y2="15.71" gradientUnits="userSpaceOnUse"><stop class="nc5-uvlcd"/><stop offset="1" class="bcmj28bxb"/></linearGradient><filter id="ijch4kd" width="3.652" height="3.139" x="3.263" y="11.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".25"/></filter><filter id="iM2G0sc" width="3.727" height="3.323" x="2.184" y="11.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".25"/></filter><filter id="iZnonPB" width="3.867" height="3.135" x="2.114" y="12.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".25"/></filter><filter id="i2yw5Jd" width="3.508" height="5.156" x="23.795" y="11.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.607843 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4193"/></filter><filter id="ipuGhfd" width="4.031" height="2.858" x="2.412" y="13.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".25"/></filter><filter id="ijIjMpc" width="23.107" height="13.423" x="4.624" y="16.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.396078 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4193"/></filter><filter id="i21lUAe" width="8.199" height="8.945" x="5.11" y="16.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".75"/></filter><filter id="igucmVc" width="7.102" height="8.493" x="20.783" y="16.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".625"/></filter><filter id="iHnFYyc" width="3.956" height="6.956" x="9.209" y="19.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".25"/></filter><filter id="isln1Le" width="5.986" height="5.519" x="20.41" y="21.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".4"/></filter><filter id="iN9hYcc" width="3.314" height="3.114" x="9.578" y="11.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4193"/></filter><filter id="iXswpie" width="2.856" height="2.856" x="9.707" y="11.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".25"/></filter><filter id="isrIoTv" width="3.364" height="3.364" x="18.423" y="10.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4193"/></filter><filter id="iqxiA5b" width="2.856" height="2.856" x="18.552" y="11.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".25"/></filter><filter id="iW4o94b" width="9.696" height="11.519" x="10.601" y="7.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4193"/></filter><filter id="i9737De" width="11.723" height="8.337" x="9.361" y="4.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4193"/></filter><filter id="isUrlRb" width="3.139" height="4.033" x="13.885" y="11.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".375"/></filter><filter id="iYhJ2mc" width="2.248" height="3.025" x="14.54" y="12.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".125"/></filter><filter id="igJhzid" width="2.818" height="1.685" x="16.451" y="9.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4193"/></filter><filter id="iK2FfEb" width="2.763" height="1.873" x="11.692" y="9.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4193"/></filter><filter id="iPWGQAb" width=".725" height=".688" x="16.839" y="11.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".05"/></filter><filter id="isOrxfe" width=".869" height=".888" x="17.618" y="11.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".1"/></filter><filter id="ijgObOc" width=".964" height="1.003" x="13.484" y="11.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".1"/></filter><filter id="iM7u1Pb" width=".844" height=".698" x="12.788" y="11.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".05"/></filter><filter id="i5PewKb" width="2.998" height="1.555" x="16.259" y="9.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".25"/></filter><filter id="iPpYlIc" width="3.009" height="1.82" x="11.444" y="9.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".25"/></filter><filter id="iMoXlve" width="1.869" height="1.911" x="15.012" y="15.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4193" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-shrugging-medium-light" /></template>
<style>
.a-e0cj8zq {
  stop-color: var(--svg-color--ba7e80, #BA7E80);
}

.a0zgi_bwh {
  stop-color: var(--svg-color--d39d7f, #D39D7F);
}

.a3e1obbdc {
  stop-color: var(--svg-color--c89678, #C89678);
  stop-opacity: 0;
}

.a9-olubxk {
  d: path("m15.173 12.543l-.37 1.619a.503.503 0 0 0 .535.612l.731-.058a.504.504 0 0 0 .433-.688l-.618-1.541c-.133-.342-.627-.303-.71.056");
}

.aa675bbim {
  stop-color: var(--svg-color--dda991, #DDA991);
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.aqh32r1du {
  d: path("M17.492 11.543a.832.832 0 0 1 .882.986l-1.602.126a.835.835 0 0 1 .72-1.111");
}

.av75tqbdq {
  stop-color: var(--svg-color--c48f75, #C48F75);
  stop-opacity: 0;
}

.axz4ivbcr {
  stop-color: var(--svg-color--eabca1, #EABCA1);
  stop-opacity: 0;
}

.b_bzxih3c {
  fill-rule: evenodd;
  d: path("M29.46 13.964a.7.7 0 0 0-.98.141c-.18.243-.653.84-1.872.84a.7.7 0 1 0 0 1.4c1.827 0 2.667-.964 2.994-1.401a.7.7 0 0 0-.142-.98");
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb3cu5wqs {
  stop-color: var(--svg-color--1a7ad4, #1A7AD4);
  stop-opacity: 0;
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bcmj28bxb {
  stop-color: var(--svg-color--daa69a, #DAA69A);
  stop-opacity: 0;
}

.bn4os6vdu {
  stop-color: var(--svg-color--cc9b7b, #CC9B7B);
  stop-opacity: 0;
}

.cj-j-xbpi {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m11.842 10.528l.002-.002l.001-.001l.004-.004l.01-.01l.032-.027q.038-.034.105-.084a2.4 2.4 0 0 1 .374-.226a2.64 2.64 0 0 1 1.377-.257a.498.498 0 1 1-.078.993a1.65 1.65 0 0 0-.861.158a1.4 1.4 0 0 0-.268.17l-.006.006a.498.498 0 0 1-.692-.716");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cw0en3yrc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M2.984 12.261c.196.502.844 1.459 2.127 1.723");
}

.d76z83bvl {
  cx: 19.98px;
  cy: 12.432px;
  r: 0.928px;
}

.d8_6n5bpd {
  stop-color: var(--svg-color--cd8b81, #CD8B81);
}

.d8xtj4b7u {
  stop-color: var(--svg-color--c78078, #C78078);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.dqcsylboi {
  stop-color: var(--svg-color--257fbf, #257FBF);
  stop-opacity: 0;
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.e490wkn-s {
  stop-color: var(--svg-color--cc9b7b, #CC9B7B);
}

.eg4b6ojxi {
  cx: 11.135px;
  cy: 13.127px;
  r: 1.557px;
}

.elmbrlbch {
  d: path("m19.556 6.406l.414.167c.726.292 1.187 1.054 1.104 1.908l-.326 2.87c-.026.296-.204.507-.493.537l-.017.002s-.016-.847-.005-1.347c.008-.406-.072-.523-.47-.86a1.17 1.17 0 0 1-.411-.767l-.062-.793c-.02-.248-.235-.43-.438-.465c-.61-.101-1.877-.251-3.672-.11s-3.022.487-3.61.683a.485.485 0 0 0-.36.527l.063.793c.024.298-.053.603-.286.821l-.138.16c-.188.165-.264.47-.245.719c.093.541.205 1.33.205 1.33l-.046.003a.59.59 0 0 1-.591-.451L9.4 9.35c-.162-.786.174-1.61.845-2.013l.383-.23c.238-.168.472-.386.706-.604l.823-1.012a1.83 1.83 0 0 1 2.021-.459c.51.11 1.06.067 1.546-.121c.729-.307 1.592-.175 2.234.323l.806.685c.219.232.48.361.79.487");
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f-m-__64y {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.665 11.276a1.3 1.3 0 0 1 1.337.885a.256.256 0 0 1-.224.336l-2.074.163a.215.215 0 0 1-.231-.236a1.3 1.3 0 0 1 1.192-1.148");
}

.f0wda1gby {
  stop-color: var(--svg-color--8e6f6b, #8E6F6B);
}

.f51--cb4u {
  stop-color: var(--svg-color--43beff, #43BEFF);
}

.fgtz1bcwy {
  stop-color: var(--svg-color--ddab88, #DDAB88);
}

.ft5dv1b6b {
  fill: none;
}

.g15pupb2m {
  stop-color: var(--svg-color--257fbf, #257FBF);
}

.g6k-1hpjs {
  stop-color: var(--svg-color--3cb2ff, #3CB2FF);
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gqn4jccjs {
  stop-color: var(--svg-color--47adf9, #47ADF9);
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

.gy5j7812b {
  stop-color: var(--svg-color--4a9ee0, #4A9EE0);
}

.h_73z-b9e {
  d: path("M26.22 11.402a.75.75 0 0 0-1.05.137l-.805 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.258v-2.697h-1.627a1.3 1.3 0 0 1 .128-.205l.805-1.047a.75.75 0 0 0-.138-1.051");
}

.h_f8hwhpp {
  stroke: var(--svg-color--40a1ff, #40A1FF);
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.36 18.8v3.442a1 1 0 0 0 1.566.823l1.84-1.265");
}

.h-z618biu {
  fill-rule: evenodd;
  d: path("M2.774 13.964a.7.7 0 0 1 .98.141c.18.243.653.84 1.872.84a.7.7 0 1 1 0 1.4c-1.827 0-2.667-.964-2.994-1.401a.7.7 0 0 1 .142-.98");
}

.hhcl8xbac {
  fill-rule: evenodd;
  d: path("M2.461 12.933a.7.7 0 0 1 .98.141q.042.056.086.119c.302.42.764 1.061 1.78 1.061a.7.7 0 1 1 0 1.4c-1.776 0-2.638-1.24-2.925-1.654l-.062-.088a.7.7 0 0 1 .141-.98");
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hsmz9_6vn {
  fill-rule: evenodd;
  d: path("M29.74 11.91a.7.7 0 0 0-.977.158q-.05.07-.115.168c-.261.39-.92 1.113-1.732 1.46c-.356.152-.503.45-.32.875c.151.356.733.503 1.088.35c1.246-.532 1.935-1.602 2.155-1.945q.038-.06.059-.088a.7.7 0 0 0-.157-.978");
}

.hzf9jo3eo {
  d: path("m10.763 12.583l.046-.002s-.112-.79-.205-1.33c-.02-.249.057-.554.245-.718l.138-.16c.233-.219.31-.524.286-.822l-.062-.793a.485.485 0 0 1 .36-.527c.587-.196 1.814-.542 3.609-.683s3.061.009 3.672.11a.54.54 0 0 1 .438.465l.062.793c.023.298.196.583.411.766c.493.29.478.473.47.861c-.011.5.005 1.347.005 1.347l.017-.002l.042 3.7c-.02 1.657-1.223 2.905-2.765 3.026l-2.985.235c-1.591.125-2.925-.924-3.204-2.557z");
}

.i2dy_3bdc {
  stop-color: var(--svg-color--d0a07f, #D0A07F);
}

.i44w2qbjz {
  d: path("M18.288 12.205a.8.8 0 0 0-.25-.413l-.22.284l.126.204z");
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i9k-0jbxt {
  stop-color: var(--svg-color--cd8b81, #CD8B81);
  stop-opacity: 0;
}

.i9x98ebrr {
  stop-color: var(--svg-color--cc936c, #CC936C);
}

.id9ofabvx {
  stop-color: var(--svg-color--925e6d, #925E6D);
}

.iyp7p_joe {
  d: path("M16.025 20.885c-1.104 0-2-.95-2-1.867V16.66c0-.918.896-1.662 2-1.662s2 .744 2 1.662v2.358c0 .917-.895 1.867-2 1.867");
}

.j2l239u6e {
  stop-color: var(--svg-color--c89678, #C89678);
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j3txnddmt {
  stop-color: var(--svg-color--3481c0, #3481C0);
  stop-opacity: 0;
}

.j61mf2btk {
  stop-color: var(--svg-color--9b7287, #9B7287);
}

.jbumt9bvj {
  stop-color: var(--svg-color--1f74b9, #1F74B9);
  stop-opacity: 0;
}

.jiqirubjz {
  d: path("M14.248 12.535c-.021-.268-.254-.43-.317-.479l-.247.28l.191.323z");
}

.jnwaoyb2q {
  stop-color: var(--svg-color--c69675, #C69675);
}

.jsiezd-_e {
  stop-color: var(--svg-color--eabc9e, #EABC9E);
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.k-no2b-rk {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m19.556 6.406l.414.167c.726.292 1.187 1.054 1.104 1.908l-.326 2.87c-.026.296-.204.507-.493.537l-.017.002s-.016-.847-.005-1.347c.008-.406-.072-.523-.47-.86a1.17 1.17 0 0 1-.411-.767l-.062-.793c-.02-.248-.235-.43-.438-.465c-.61-.101-1.877-.251-3.672-.11s-3.022.487-3.61.683a.485.485 0 0 0-.36.527l.063.793c.024.298-.053.603-.286.821l-.138.16c-.188.165-.264.47-.245.719c.093.541.205 1.33.205 1.33l-.046.003a.59.59 0 0 1-.591-.451L9.4 9.35c-.162-.786.174-1.61.845-2.013l.383-.23c.238-.168.472-.386.706-.604l.823-1.012a1.83 1.83 0 0 1 2.021-.459c.51.11 1.06.067 1.546-.121c.729-.307 1.592-.175 2.234.323l.806.685c.219.232.48.361.79.487");
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k20ytgb7v {
  stop-color: var(--svg-color--1f74b9, #1F74B9);
}

.k3un0nv9d {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.173 12.543l-.37 1.619a.503.503 0 0 0 .535.612l.731-.058a.504.504 0 0 0 .433-.688l-.618-1.541c-.133-.342-.627-.303-.71.056");
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.kzn56abzk {
  d: path("M17.445 11.723c.065.075-.05.18-.183.297c-.132.116-.23.198-.296.124s-.01-.23.121-.345c.133-.116.293-.15.358-.076");
}

.l2gakx84d {
  cx: 13.21px;
  cy: 12.237px;
  rx: 0.363px;
  ry: 0.184px;
}

.l6xrk1bwj {
  stop-color: var(--svg-color--28699c, #28699C);
  stop-opacity: 0;
}

.l7-82eghs {
  fill-rule: evenodd;
  d: path("M28.701 11.594a.7.7 0 0 0-.977.157a2 2 0 0 0-.115.183l-.006.01v.001a5 5 0 0 1-.106.175c-.076.12-.17.249-.293.37c-.233.227-.608.467-1.267.5a.7.7 0 0 0 .068 1.398c1.024-.05 1.718-.447 2.179-.899a3.5 3.5 0 0 0 .495-.618c.053-.084.097-.16.13-.215l.004-.007l.044-.075l.002-.003a.7.7 0 0 0-.158-.977");
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lii4b5bpn {
  fill-rule: evenodd;
  d: path("M29.773 12.933a.7.7 0 0 0-.98.141l-.086.119c-.302.42-.764 1.16-1.779 1.16c-.387 0-.7.215-.7.601a.7.7 0 0 0 .7.7c1.775 0 2.637-1.24 2.924-1.654q.037-.055.063-.088a.7.7 0 0 0-.142-.98");
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.ltkp3rbye {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.884 9.996c.394-.102 1.175-.143 1.748.234");
}

.mb-6y2bmd {
  stop-color: var(--svg-color--bc8f80, #BC8F80);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdcg8dd5q {
  stroke: var(--svg-color--4abeff, #4ABEFF);
  stroke-linecap: square;
  d: path("M26.134 18.22v3.99a1 1 0 0 1-1.567.824l-1.839-1.265");
}

.mh71_3bcu {
  cx: 19.98px;
  cy: 12.432px;
  r: 0.928px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.msi6qbbpq {
  stop-color: var(--svg-color--2d92df, #2D92DF);
}

.mskv0-bok {
  fill: var(--svg-color--c69675, #C69675);
  d: path("M6.013 11.402a.75.75 0 0 1 1.052.137l.804 1.047c.37.48.57 1.07.57 1.676v2.14H5.181v-2.447a.25.25 0 0 1 .25-.25h1.377a1.3 1.3 0 0 0-.128-.205l-.804-1.047a.75.75 0 0 1 .137-1.051");
}

.mtrk0zxts {
  stop-color: var(--svg-color--51aaff, #51AAFF);
  stop-opacity: 0;
}

.mx6r32s2r {
  stop-color: var(--svg-color--d19984, #D19984);
  stop-opacity: 0;
}

.nc5-uvlcd {
  stop-color: var(--svg-color--daa69a, #DAA69A);
}

.ne51g8a0v {
  stop-color: var(--svg-color--3990dd, #3990DD);
}

.nhxwftdxc {
  stop-color: var(--svg-color--eabca1, #EABCA1);
}

.o18y7cctk {
  stop-color: var(--svg-color--389bfa, #389BFA);
}

.o5kh6zbhk {
  d: path("M27.092 16.482a.25.25 0 0 0-.25-.25h-2.93a.25.25 0 0 0-.25.25V17.8h3.43z");
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.o9mwykjzf {
  fill-rule: evenodd;
  d: path("M2.494 11.91a.7.7 0 0 1 .977.158q.05.07.115.168c.261.39.703 1.051 1.515 1.399a.7.7 0 0 1-.55 1.287c-1.246-.533-1.935-1.603-2.156-1.946l-.058-.088a.7.7 0 0 1 .157-.978");
}

.ocrbm8rzk {
  stop-color: var(--svg-color--dda991, #DDA991);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_s6zb_u {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.22 11.625a1.3 1.3 0 0 0-1.182 1.083a.256.256 0 0 0 .274.297l2.074-.163a.215.215 0 0 0 .19-.269a1.306 1.306 0 0 0-1.356-.948");
}

.ok0pekb3m {
  stop-color: var(--svg-color--28699c, #28699C);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.opxc931wt {
  stop-color: var(--svg-color--3990dd, #3990DD);
  stop-opacity: 0;
}

.ou9iweytm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M3.212 14.322c.294.451 1.122 1.257 2.432 1.257");
}

.oxwoqzt3c {
  cx: 15.946px;
  cy: 16.089px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  rx: 0.734px;
  ry: 0.755px;
}

.p8zx0emkh {
  stop-color: var(--svg-color--389bfa, #389BFA);
  stop-opacity: 0;
}

.paumsgmxe {
  cx: 19.98px;
  cy: 12.432px;
  r: 1.557px;
}

.pg859nb_v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M2.914 13.27c.238.484.966 1.381 2.267 1.535");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmvuw6bxy {
  fill-rule: evenodd;
  d: path("M3.533 11.594a.7.7 0 0 1 .977.157a2 2 0 0 1 .121.193v.001c.035.058.067.114.106.175c.076.12.17.249.294.37c.232.227.607.467 1.266.5a.7.7 0 1 1-.068 1.398c-1.024-.05-1.718-.447-2.179-.899a3.5 3.5 0 0 1-.494-.618a6 6 0 0 1-.135-.222l-.044-.075l-.001-.003a.7.7 0 0 1 .157-.977");
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.q3u2-ob7j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M4.063 11.981c.196.502 1.017 1.387 2.052 1.539");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qx0aig_op {
  stop-color: var(--svg-color--e7b690, #E7B690);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r-mgr_bxp {
  fill: var(--svg-color--e7b690, #E7B690);
  d: path("M26.22 11.402a.75.75 0 0 0-1.05.137l-.805 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.258v-2.697h-1.627a1.3 1.3 0 0 1 .128-.205l.805-1.047a.75.75 0 0 0-.138-1.051");
}

.rfdt237zi {
  fill: var(--svg-color--000, #000);
  d: path("M13.973 12.655a.475.475 0 0 0-.513-.438a.475.475 0 0 0-.368.727l.841-.066a.5.5 0 0 0 .04-.223");
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s_o7_jesn {
  stop-color: var(--svg-color--d0a07f, #D0A07F);
  stop-opacity: 0;
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sesnm-bka {
  cx: 13.21px;
  cy: 12.237px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.363px;
  ry: 0.184px;
}

.sjzxdti2m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.86 25.482c.177-1.146.956-3.881 2.656-5.656");
}

.sp_au2bah {
  stop-color: var(--svg-color--43beff, #43BEFF);
  stop-opacity: 0;
}

.sv_dn8bha {
  stop-color: var(--svg-color--1e72ff, #1E72FF);
  stop-opacity: 0;
}

.svn8oxbdh {
  fill: var(--svg-color--000, #000);
  d: path("M17.082 12.41a.475.475 0 0 1 .438-.512a.475.475 0 0 1 .477.66l-.84.066a.43.43 0 0 1-.075-.214");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.u1__hxdnm {
  d: path("M6.013 11.402a.75.75 0 0 1 1.052.137l.804 1.047c.37.48.57 1.07.57 1.676v2.14H5.181v-2.447a.25.25 0 0 1 .25-.25h1.377a1.3 1.3 0 0 0-.128-.205l-.804-1.047a.75.75 0 0 1 .137-1.051");
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.u8buv18hy {
  d: path("M9.484 20.71a.25.25 0 0 1-.375-.216v-2.563a.6.6 0 0 0-.6-.6H5.224a.6.6 0 0 0-.6.6v4.286c-.005.849.112 2.507 1.485 3.383c1.148.733 2.5.57 3.213.347a.16.16 0 0 1 .208.148V29.8c0 .083.068.15.15.15h12.994a.15.15 0 0 0 .15-.15v-3.706c0-.106.108-.18.209-.148c.713.222 2.065.386 3.213-.347c1.373-.876 1.49-2.534 1.485-3.383V17.93a.6.6 0 0 0-.6-.6h-3.285a.6.6 0 0 0-.6.6v2.563a.25.25 0 0 1-.375.216l-6.694-3.931z");
}

.uvndg_buj {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m18.809 9.98l-.002-.001l-.002-.002l-.004-.003l-.012-.008a1 1 0 0 0-.152-.088a2.4 2.4 0 0 0-.405-.166a2.64 2.64 0 0 0-1.4-.038a.498.498 0 1 0 .232.969c.366-.088.667-.043.875.021a1.4 1.4 0 0 1 .291.126l.008.005a.498.498 0 0 0 .57-.815");
}

.uvwg3fmlf {
  d: path("m21.21 21.96l1.542 3.67c1.207.44 2.534.203 2.844 0z");
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vh9-3hb_g {
  stop-color: var(--svg-color--c48f75, #C48F75);
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vw_f_cbup {
  stop-color: var(--svg-color--227bc3, #227BC3);
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.wj8c2lbyu {
  stop-color: var(--svg-color--c27b54, #C27B54);
}

.wjksmgbzx {
  stop-color: var(--svg-color--308bdb, #308BDB);
}

.wr4xjslhr {
  stop-color: var(--svg-color--eabc9e, #EABC9E);
  stop-opacity: 0;
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.xbebtfb5z {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.445 11.723c.065.075-.05.18-.183.297c-.132.116-.23.198-.296.124s-.01-.23.121-.345c.133-.116.293-.15.358-.076");
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xjqh_ibco {
  stop-color: var(--svg-color--8e6f6b, #8E6F6B);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y-po_4ueh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.07 10.86c.282-.293.924-.629 1.758-.562");
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ye-2zryyr {
  stop-color: var(--svg-color--c78078, #C78078);
  stop-opacity: 0;
}

.yk15gqvvr {
  stop-color: var(--svg-color--cc936c, #CC936C);
  stop-opacity: 0;
}

.yn5ij1ffp {
  stop-color: var(--svg-color--c27b54, #C27B54);
  stop-opacity: 0;
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z1-d-2bfy {
  cx: 11.135px;
  cy: 13.127px;
  r: 0.928px;
}

.z108ppbpv {
  stop-color: var(--svg-color--1e72ff, #1E72FF);
}

.z53i_7bit {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.285 12.687l-.639 1.64c-.069.332.183.64.505.614l.685-.054c.322-.025.523-.373.403-.686l-.588-1.543c-.126-.342-.29-.33-.367.029");
}

.z96fdub7f {
  stop-color: var(--svg-color--3481c0, #3481C0);
}

.zap_rqapx {
  d: path("M5.158 16.482a.25.25 0 0 1 .25-.25h2.93a.25.25 0 0 1 .25.25v1.13h-3.43z");
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zis_ubcvg {
  cx: 15.946px;
  cy: 16.089px;
  fill: var(--svg-color--87004d, #87004D);
  rx: 0.734px;
  ry: 0.755px;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zt97zgsgs {
  d: path("M13.432 11.863a.832.832 0 0 0-.717 1.11l1.603-.125a1 1 0 0 0 .013-.222a.84.84 0 0 0-.899-.763");
}

.zuuvnac4f {
  stop-color: var(--svg-color--1a7ad4, #1A7AD4);
}

</style>
