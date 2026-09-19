<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iFa1h1d)"><path fill="url(#iDjm0Dc)" class="lsq62ob9b"/></g><path fill="url(#i1N5m2u)" class="nv-ho4bep"/><path fill="url(#i6nmKVJ)" class="nv-ho4bep"/><path fill="url(#i8Lelfe)" class="nv-ho4bep"/><g filter="url(#iLgX53c)"><path stroke="url(#i6ho09c)" class="c7u_0os5k"/></g><g filter="url(#iZFStNe)"><path fill="url(#i2i3Kjd)" class="o3ebqv6uh"/><path fill="url(#iezS7vb)" class="o3ebqv6uh"/><path fill="url(#iFjkfVb)" class="o3ebqv6uh"/></g><path fill="url(#ibJ7bUc)" class="ix5fazb3t"/><path fill="url(#icbFbSb)" class="ix5fazb3t"/><path fill="url(#igF8PHB)" class="ix5fazb3t"/><path fill="url(#iBiNgHd)" class="ut1w03l9j"/><path fill="url(#iZmUFEc)" class="ut1w03l9j"/><path fill="url(#ifMDrsb)" class="ut1w03l9j"/><path fill="url(#iQyr2we)" class="i2q5q2beh"/><path fill="url(#iZ7NjWc)" class="i2q5q2beh"/><path fill="url(#iNNFkpb)" class="jk30m-bwx"/><g filter="url(#iqciJGc)"><path fill="url(#iBhn4Ec)" class="cz3iytave"/><path fill="url(#ipwUz8c)" class="cz3iytave"/><path fill="url(#i5uPh4H)" class="cz3iytave"/><path fill="url(#ifwzu0d)" class="cz3iytave"/></g><g filter="url(#ioY211L)"><path fill="url(#iitMh4d)" class="ba7t6bc2j"/><path fill="url(#i3BULPb)" class="ba7t6bc2j"/><path fill="url(#iDZ7JYc)" class="ba7t6bc2j"/><path fill="url(#i5Gf9dd)" class="ba7t6bc2j"/></g><path fill="url(#idzyHJc)" class="c480l3jei"/><g filter="url(#icxGlpT)"><path fill="url(#iHfIyfb)" class="qxgg0f5pn"/><path fill="url(#i84cDhe)" class="qxgg0f5pn"/></g><g filter="url(#i3vQUdP)"><path fill="url(#ibsSjge)" class="m186mqaew"/></g><path fill="url(#i8wFuPe)" class="aw9fsxdes"/><path clip-rule="evenodd" class="xmn8bcbuh"/><path fill="url(#ixSKYXI)" clip-rule="evenodd" class="e-cyhlb8e"/><g filter="url(#irF4JGc)"><path fill="url(#ih5JrId)" class="t5acn1bmk"/><path fill="url(#iB8AUBA)" class="t5acn1bmk"/><path fill="url(#iRh2Kqd)" class="t5acn1bmk"/><path fill="url(#iYPAlPb)" class="t5acn1bmk"/><path fill="url(#i0wgRFe)" class="t5acn1bmk"/></g><g filter="url(#ig2xufc)"><path fill="url(#ioEY4wb)" class="w32pebg-b"/><path fill="url(#i0eXBAe)" class="w32pebg-b"/><path fill="url(#iuwS3cb)" class="w32pebg-b"/><path fill="url(#iEMsLCc)" class="w32pebg-b"/><path fill="url(#ienH1Zc)" class="w32pebg-b"/></g><path fill="url(#itvS4Xb)" class="dwmyn0k_k"/><path fill="url(#iVtD4Ad)" class="rejus4bhg"/><g filter="url(#i4RKrjd)"><path stroke="url(#iGRUQ6d)" class="qj2o0obna"/></g><g filter="url(#iuacgvc)"><path stroke="url(#iRYskDU)" class="q4sggw3zw"/></g><g filter="url(#imy6vCb)"><path stroke="url(#iK4Zboo)" class="embut7b2v"/></g><g filter="url(#itF7eac)"><path stroke="url(#ivQpNlh)" class="qbx2b9bsz"/></g><g filter="url(#iz8j2kf)"><path stroke="url(#i5E9kxc)" class="onnug0jly"/></g><g filter="url(#iE9skic)"><path stroke="url(#i3u0M4b)" class="q3m7mz1ko"/></g><g filter="url(#iMVlcKb)"><circle fill="url(#irj61eR)" class="a0utjybjk"/></g><g filter="url(#ipxAwXd)"><circle fill="url(#il4Cvfe)" class="f6-7-vb_g"/></g><g filter="url(#iPoKhSb)"><circle fill="url(#iCMpPge)" class="bgptuqbjn"/><circle fill="url(#iitRpKb)" class="bgptuqbjn"/></g><g filter="url(#iFFC0qb)"><circle class="ng7b7qbdm"/><circle fill="url(#ix8jqme)" class="sv2duxbev"/><circle fill="url(#iAtLIUB)" class="sv2duxbev"/></g><g filter="url(#i02wBhd)"><path fill="url(#i7Y7RRe)" class="b4tisqb0h"/><path fill="url(#iAZRKYc)" class="b4tisqb0h"/><path fill="url(#i0oJNYZ)" class="b4tisqb0h"/></g><path fill="url(#i2DSG9b)" class="lgv_euz3i"/><path fill="url(#iwp2zIc)" class="lgv_euz3i"/><path fill="url(#iZ5Z5Rw)" class="lgv_euz3i"/><path fill="url(#iHahgIi)" class="lgv_euz3i"/><path fill="url(#iTfJTIE)" class="lgv_euz3i"/><g filter="url(#iRed4Qb)"><path fill="url(#iQqGCpc)" class="zs3xtwb8v"/></g><g filter="url(#iWEF7Ec)"><path class="srescvb5j"/><path fill="url(#iqYj6Od)" class="fue2d4weg"/><path fill="url(#i0VCZLd)" class="fue2d4weg"/><path fill="url(#i8QyGcc)" class="fue2d4weg"/><path fill="url(#imCwpec)" class="fue2d4weg"/></g><g filter="url(#irPwA5F)"><path class="rag9kob-h"/></g><g filter="url(#i6Nsj1d)"><path class="xiop2xigt"/><path fill="url(#iqkVQ3Q)" class="ukmsama-k"/><path fill="url(#inV8Asb)" class="ukmsama-k"/><path fill="url(#iMp2dpb)" class="ukmsama-k"/><path fill="url(#iFc5VBe)" class="ukmsama-k"/></g><path fill="url(#ixlb9Hc)" class="ukmsama-k"/><path stroke="url(#iu7Jf2d)" class="gna3itbmn"/><g filter="url(#iKrDMMb)"><path class="btdv0r48q"/><path fill="url(#iFEvlpb)" class="vkgern59s"/></g><g filter="url(#irSyOlb)"><path class="zjyx6dbdf"/><path fill="url(#i2k0q0b)" class="deo0r1bkz"/></g><path class="gskanzb-x"/><path fill="url(#iVftOxd)" class="p941os1jk"/><path class="a4-ppbccr"/><g filter="url(#iVMjjcJ)"><path class="xxdh54bza"/><path fill="url(#iukFycd)" class="h1il61bsu"/></g><g filter="url(#ioPf3hc)"><path fill="url(#inpUQpb)" class="w42o3etxb"/></g><path class="o25db_ffh"/><path fill="url(#ixwOMHe)" class="vz-1cdczy"/><path class="ltlzyyvzf"/><g filter="url(#iLzmhxb)"><path fill="url(#ip1lGUb)" class="vo580yu-k"/></g><g filter="url(#ip5fhre)"><ellipse transform="rotate(-27.914 13.512 9.998)" class="lw6wi_bgn"/><ellipse fill="url(#ib8XoCb)" transform="rotate(-27.914 13.512 9.998)" class="nmvo9zpwd"/></g><g filter="url(#iidNqZd)"><path stroke="url(#iyyt1QJ)" class="qen7stbxp"/></g><g filter="url(#iCIufZb)"><path stroke="url(#iudZcYY)" class="ftlafvn2k"/></g><g filter="url(#iba8Bod)"><path stroke="url(#iDxtGZU)" class="z_uo_hbxt"/></g><g filter="url(#itfv8Ee)"><path fill="url(#iIimMvK)" class="psnc0zbqv"/><path fill="url(#iuywrgb)" class="psnc0zbqv"/></g><defs><radialGradient id="i6nmKVJ" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 26.998 6.86)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="i8Lelfe" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.582 25.425)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="iFjkfVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.024 4.26)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="ibJ7bUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.02 15.894)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="icbFbSb" cx="0" cy="0" r="1" gradientTransform="scale(2.9375 8.375)rotate(90 2.64 5.08)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="igF8PHB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.738 19.02)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="iBiNgHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27.014 28.175)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="iZ7NjWc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.478 29.723)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="iNNFkpb" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 11.7969 15.207 20.237)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="ipwUz8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.25 19.384)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="i5uPh4H" cx="0" cy="0" r="1" gradientTransform="rotate(-125.283 15.122 5.102)scale(1.63656 .29806)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="ifwzu0d" cx="0" cy="0" r="1" gradientTransform="rotate(69.677 -2.794 21.125)scale(.94974 1.77776)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="i3BULPb" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.535 20.3)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="i5Gf9dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 1 -1.87182 -.87742 14.05 16.409)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="idzyHJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.34375 -2.06 0 16.024 17.175)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="asdb3w9he"/><stop offset="1" class="zxm3y0btp"/></radialGradient><radialGradient id="iHfIyfb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.656 23.711)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="hkmqqzaeo"/><stop offset="1" class="vo92-0bqu"/></radialGradient><radialGradient id="i84cDhe" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.798 23.43)" gradientUnits="userSpaceOnUse"><stop class="wpeyy_b3b"/><stop offset="1" class="cs9siac0p"/></radialGradient><radialGradient id="ibsSjge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 -.29687 .9302 -5.77708 11.113 23.953)" gradientUnits="userSpaceOnUse"><stop class="jgy_mt60r"/><stop offset="1" class="esaylh6lg"/></radialGradient><radialGradient id="iB8AUBA" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.207 25.305)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="0" class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="iRh2Kqd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.223 26.586)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="iYPAlPb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.27 27.868)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="i0wgRFe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.34 29.227)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="i0eXBAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.27 25.305)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="iuwS3cb" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.207 26.586)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="iEMsLCc" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.113 27.868)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="ienH1Zc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.973 29.227)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="irj61eR" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.547 10.777)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iitRpKb" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.112 10.511)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="ix8jqme" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.698 11.599)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iAtLIUB" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.74 10.777)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iAZRKYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.318 9.504)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="i0oJNYZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 13.756 9.638)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iZ5Z5Rw" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8549 -12.0201 0 15.668 9)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset=".954" class="whxihzpaf"/></radialGradient><radialGradient id="iHahgIi" cx="0" cy="0" r="1" gradientTransform="rotate(-146.07 12.666 5.263)scale(2.07148 1.17905)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="iTfJTIE" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -.54454 .34491 1.64288 12.33 17.73)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="iqYj6Od" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.42495 .38451 20.32 6.666)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="i0VCZLd" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.675 4.905)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="i8QyGcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.97 2.167)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="imCwpec" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.515 8.992)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iFc5VBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.298 12.385)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iFEvlpb" cx="0" cy="0" r="1" gradientTransform="matrix(.1043 -.60384 1.78641 .30854 18.415 8.69)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="i2k0q0b" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.791 -3.53)scale(.61278 1.81296)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iVftOxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.151 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iukFycd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.923 10.178)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixwOMHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.784 10.094)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ib8XoCb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.825 -1.487)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuywrgb" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.385 10.533)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><linearGradient id="iDjm0Dc" x1="11.838" x2="31.281" y1="4.549" y2="22.785" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="i1N5m2u" x1="30.082" x2="9.145" y1="13.237" y2="13.237" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="i6ho09c" x1="13.457" x2="31.27" y1="3.49" y2="24.302" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="i2i3Kjd" x1="-4.887" x2="28.926" y1="25.581" y2="25.581" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="iezS7vb" x1="3.113" x2="3.113" y1="5.143" y2="23.581" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="iZmUFEc" x1="25.193" x2="25.193" y1="30.394" y2="26.578" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="ifMDrsb" x1="22.426" x2="23.238" y1="29.206" y2="29.19" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="iQyr2we" x1="7.154" x2="9.548" y1="28.087" y2="28.087" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="iBhn4Ec" x1="18.074" x2="20.87" y1="18.315" y2="18.315" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="iitMh4d" x1="13.964" x2="11.167" y1="18.315" y2="18.315" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="iDZ7JYc" x1="12.129" x2="12.691" y1="16.878" y2="17.096" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="i8wFuPe" x1="21.863" x2="17.488" y1="24.737" y2="24.737" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="ixSKYXI" x1="10.334" x2="10.762" y1="23.519" y2="23.519" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="ih5JrId" x1="12.52" x2="8.582" y1="27.956" y2="27.956" gradientUnits="userSpaceOnUse"><stop class="y7rb0nbsx"/><stop offset="1" class="j4pe32lse"/></linearGradient><linearGradient id="ioEY4wb" x1="22.488" x2="18.674" y1="27.55" y2="27.55" gradientUnits="userSpaceOnUse"><stop class="c1fnikbua"/><stop offset=".807" class="y9fu8v2us"/></linearGradient><linearGradient id="itvS4Xb" x1="10.801" x2="21.674" y1="21.893" y2="21.893" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="iVtD4Ad" x1="16.42" x2="16.42" y1="20.956" y2="22.128" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="iGRUQ6d" x1="19.043" x2="20.871" y1="26.058" y2="26.058" gradientUnits="userSpaceOnUse"><stop class="kn1yo7csr"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="gom2jbmdj"/></linearGradient><linearGradient id="iRYskDU" x1="12.952" x2="10.754" y1="26.058" y2="26.058" gradientUnits="userSpaceOnUse"><stop class="oh-_iua0g"/><stop offset="1" class="owl7p83et"/></linearGradient><linearGradient id="iK4Zboo" x1="19.043" x2="20.871" y1="27.323" y2="27.323" gradientUnits="userSpaceOnUse"><stop class="kn1yo7csr"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="gom2jbmdj"/></linearGradient><linearGradient id="ivQpNlh" x1="12.952" x2="10.754" y1="27.323" y2="27.323" gradientUnits="userSpaceOnUse"><stop class="oh-_iua0g"/><stop offset="1" class="owl7p83et"/></linearGradient><linearGradient id="i5E9kxc" x1="19.043" x2="20.871" y1="28.589" y2="28.589" gradientUnits="userSpaceOnUse"><stop class="kn1yo7csr"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="gom2jbmdj"/></linearGradient><linearGradient id="i3u0M4b" x1="12.952" x2="10.754" y1="28.589" y2="28.589" gradientUnits="userSpaceOnUse"><stop class="oh-_iua0g"/><stop offset="1" class="owl7p83et"/></linearGradient><linearGradient id="il4Cvfe" x1="11.218" x2="10.576" y1="11.056" y2="11.056" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iCMpPge" x1="21.827" x2="21.008" y1="9.684" y2="12.223" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="i7Y7RRe" x1="20.01" x2="12.366" y1="11.167" y2="12.306" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="i2DSG9b" x1="10.569" x2="12.452" y1="13.865" y2="13.798" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iwp2zIc" x1="20.839" x2="19.782" y1="13.027" y2="12.926" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iQqGCpc" x1="15.438" x2="23.59" y1="8.179" y2="5.26" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iqkVQ3Q" x1="15.105" x2="16.044" y1="11.826" y2="11.826" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="inV8Asb" x1="16.909" x2="15.883" y1="12.149" y2="12.134" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iMp2dpb" x1="16.165" x2="16.165" y1="12.892" y2="12.319" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="ixlb9Hc" x1="16.096" x2="16.096" y1="12.934" y2="12.766" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="iu7Jf2d" x1="14.932" x2="15.367" y1="14.509" y2="13.82" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="inpUQpb" x1="18.93" x2="18.616" y1="10.148" y2="10.341" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ip1lGUb" x1="14.528" x2="14.214" y1="10.148" y2="10.341" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyyt1QJ" x1="18.945" x2="18.525" y1="8.006" y2="7.147" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iudZcYY" x1="13.636" x2="12.445" y1="7.878" y2="7.379" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iDxtGZU" x1="11.304" x2="11.304" y1="5.862" y2="8.021" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="iIimMvK" x1="16.09" x2="16.09" y1="9.429" y2="13.21" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient><filter id="iFa1h1d" width="27.98" height="21.09" x="2.024" y="3.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="iLgX53c" width="27.413" height="20.785" x="2.688" y="3.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".2"/></filter><filter id="iZFStNe" width="27.91" height="20.96" x="2.024" y="3.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="iqciJGc" width="2.797" height="14.04" x="18.074" y="15.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="ioY211L" width="2.797" height="14.04" x="11.167" y="15.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="icxGlpT" width="2.1" height="3.39" x="20.967" y="23.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.478431 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="i3vQUdP" width="2.1" height="3.29" x="8.97" y="23.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.368627 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="irF4JGc" width="4.793" height="5.391" x="8.97" y="24.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.380392 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="ig2xufc" width="4.793" height="5.591" x="18.474" y="24.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.196078 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1660" result="effect2_innerShadow_4002_1660"/></filter><filter id="i4RKrjd" width="2.222" height=".3" x="18.893" y="25.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".05"/></filter><filter id="iuacgvc" width="2.222" height=".3" x="10.88" y="25.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".05"/></filter><filter id="imy6vCb" width="2.222" height=".3" x="18.893" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".05"/></filter><filter id="itF7eac" width="2.222" height=".3" x="10.88" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".05"/></filter><filter id="iz8j2kf" width="2.222" height=".3" x="18.893" y="28.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".05"/></filter><filter id="iE9skic" width="2.222" height=".3" x="10.88" y="28.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".05"/></filter><filter id="iMVlcKb" width="3.542" height="3.342" x="9.547" y="9.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="ipxAwXd" width="2.992" height="2.992" x="9.722" y="9.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".25"/></filter><filter id="iPoKhSb" width="3.592" height="3.592" x="19.069" y="8.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="iFFC0qb" width="2.992" height="2.992" x="19.244" y="9.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".25"/></filter><filter id="i02wBhd" width="10.383" height="12.189" x="10.807" y="5.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="iRed4Qb" width="8.25" height="7.07" x="14.14" y="3.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation="1"/></filter><filter id="iWEF7Ec" width="12.614" height="8.551" x="9.663" y="1.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="irPwA5F" width="3.262" height="4.184" x="14.1" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".375"/></filter><filter id="i6Nsj1d" width="2.379" height="3.184" x="14.781" y="9.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".125"/></filter><filter id="iKrDMMb" width="2.982" height="1.874" x="17.153" y="7.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="irSyOlb" width="2.982" height="1.874" x="12.001" y="7.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/></filter><filter id="iVMjjcJ" width=".787" height=".697" x="17.416" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".05"/></filter><filter id="ioPf3hc" width=".892" height=".914" x="18.257" y="9.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".1"/></filter><filter id="iLzmhxb" width=".987" height="1.041" x="13.811" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".1"/></filter><filter id="ip5fhre" width=".914" height=".705" x="13.056" y="9.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".05"/></filter><filter id="iidNqZd" width="3.101" height="1.681" x="17.007" y="7.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".25"/></filter><filter id="iCIufZb" width="3.179" height="1.739" x="11.783" y="7.315" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".25"/></filter><filter id="iba8Bod" width="1.008" height="2.271" x="10.799" y="5.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1660" stdDeviation=".125"/></filter><filter id="itfv8Ee" width="10.29" height="4.16" x="10.894" y="8.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1660"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1660" result="effect2_innerShadow_4002_1660"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-teacher-medium-dark" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a0utjybjk {
  cx: 11.218px;
  cy: 10.777px;
  r: 1.671px;
}

.a4-ppbccr {
  fill: var(--svg-color--000, #000);
  d: path("M17.642 10.51a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.asdb3w9he {
  stop-color: var(--svg-color--533, #533);
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.avo9uebvh {
  stop-color: var(--svg-color--544b50, #544B50);
}

.aw9fsxdes {
  d: path("M10.334 21.82v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.b4tisqb0h {
  d: path("m10.865 10.163l.05.002s-.054-.854-.108-1.441c0-.267.107-.588.322-.748l.161-.16c.269-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.053.429.267.429.534v.854c0 .32.161.64.376.854c.502.352.471.546.43.961a47 47 0 0 0-.108 1.442h.018l-.266 3.962c-.16 1.77-1.553 3.005-3.213 3.005h-3.214c-1.714 0-3.053-1.234-3.213-3.005z");
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.ba7t6bc2j {
  d: path("m12.674 16l-1.36 2.929c-.09.19.05.41.26.41l.963-.266c.422-.105.437.277.277.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V16z");
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bgptuqbjn {
  cx: 20.74px;
  cy: 10.777px;
  r: 1.671px;
}

.btdv0r48q {
  fill: var(--svg-color--352827, #352827);
  d: path("m19.693 8.054l-.001-.001l-.002-.002l-.005-.003l-.011-.01l-.037-.027a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.493-.159a.534.534 0 0 0 .167 1.056c.398-.063.717.01.935.096a1.5 1.5 0 0 1 .308.166a.534.534 0 0 0 .68-.825");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c1fnikbua {
  stop-color: var(--svg-color--997266, #997266);
}

.c480l3jei {
  d: path("M16.024 18.61c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c7u_0os5k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.238 4.334h26.213a.1.1 0 0 1 .1.1v19.585");
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cr9drwbam {
  stop-color: var(--svg-color--9a7469, #9A7469);
  stop-opacity: 0;
}

.cs9siac0p {
  stop-color: var(--svg-color--9c7c74, #9C7C74);
  stop-opacity: 0;
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.cz3iytave {
  d: path("m19.364 16l1.36 2.929c.09.19-.05.41-.26.41l-.964-.266c-.422-.105-.436.277-.276.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V16z");
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.deo0r1bkz {
  d: path("m12.193 8.054l.002-.002l.005-.003l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.063.241-.14.42-.211c.36-.142.872-.257 1.494-.159a.534.534 0 1 1-.167 1.056a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.309.166a.534.534 0 0 1-.68-.825");
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dwmyn0k_k {
  d: path("M21.674 22.925v-2.286c0-.388-.36-.699-.81-.699h-8.659c-1.041 0-1.871.73-1.871 1.622c0 .752.61 1.363 1.363 1.363z");
}

.e-cyhlb8e {
  fill-rule: evenodd;
  d: path("M12.428 29.94v-8.406h-2.094v8.406z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.embut7b2v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 27.245h1.922");
}

.eo578gbro {
  stop-color: var(--svg-color--9c7b74, #9C7B74);
}

.esaylh6lg {
  stop-color: var(--svg-color--684844, #684844);
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.f6-7-vb_g {
  cx: 11.218px;
  cy: 10.777px;
  r: 0.996px;
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.foz7ccc1o {
  stop-color: var(--svg-color--251732, #251732);
}

.fqkeoivtf {
  stop-color: var(--svg-color--aba5a8, #ABA5A8);
}

.ft5dv1b6b {
  fill: none;
}

.ftlafvn2k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.408 8.428c.327-.289 1.042-.594 1.929-.452");
}

.fue2d4weg {
  d: path("m20.793 4.293l.43.213c.752.374 1.181 1.228 1.02 2.136l-.59 3.043c-.053.314-.26.525-.573.533h-.018s.054-.907.107-1.441c.044-.434-.032-.566-.43-.96c-.214-.214-.375-.535-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.748c.054.587.107 1.441.107 1.441l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.213a8 8 0 0 0 .805-.587l.967-1.015c.59-.534 1.45-.694 2.2-.32c.538.16 1.128.16 1.665 0c.806-.267 1.718-.053 2.363.534l.805.8c.215.267.483.428.805.588");
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.gna3itbmn {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.607 13.536c.394.206.863.323 1.363.323c.505 0 .97-.117 1.363-.323a.204.204 0 0 1 .242.04c.058.06.079.155.021.242m-2.99-.282l2.949.254m-2.948-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.21.028l-.041-.028m.041.028l-.041-.028m.041.028a1.95 1.95 0 0 1-1.626.869a1.95 1.95 0 0 1-1.626-.87m3.21-.027c-.335.508-.919.847-1.584.847s-1.25-.34-1.585-.847m-.04.028l.04-.028m-.04.028h-.001l.042-.028");
}

.gom2jbmdj {
  stop-color: var(--svg-color--643037, #643037);
  stop-opacity: 0;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gskanzb-x {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.36 9.345c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.gugba3b_v {
  stop-color: var(--svg-color--33141c, #33141C);
  stop-opacity: 0;
}

.h1il61bsu {
  d: path("M18.087 9.805c.064.086-.069.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
}

.hkmqqzaeo {
  stop-color: var(--svg-color--8b625a, #8B625A);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.i2q5q2beh {
  d: path("M9.314 29.94V17.696a10.98 10.98 0 0 0-4.32 8.744v3.5z");
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.ix5fazb3t {
  d: path("M16.024 15.44c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.j4pe32lse {
  stop-color: var(--svg-color--744c4b, #744C4B);
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jgy_mt60r {
  stop-color: var(--svg-color--512a20, #512A20);
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jk30m-bwx {
  d: path("M18.074 16.76h-4.11v13.18h4.11z");
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.kn1yo7csr {
  stop-color: var(--svg-color--643037, #643037);
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzk-_ccou {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgv_euz3i {
  d: path("M10.807 8.724c0-.267.107-.588.322-.748l.161-.16c.269-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.053.429.267.429.534v.854c0 .32.161.64.376.854c.502.352.471.546.43.961a47 47 0 0 0-.108 1.442h.018l-.266 3.962c-.16 1.77-1.553 3.005-3.213 3.005h-3.214c-1.714 0-3.053-1.234-3.213-3.005c-.14-1.819-.2-3.642-.367-5.457");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lsq62ob9b {
  d: path("M29.394 24.93H2.644c-.34 0-.62-.28-.62-.62V4.56c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62V24.3a.61.61 0 0 1-.61.63");
}

.ltlzyyvzf {
  fill: var(--svg-color--000, #000);
  d: path("M14.293 10.51a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.235");
}

.lw6wi_bgn {
  cx: 13.512px;
  cy: 9.998px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m13zyzbuk {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
}

.m186mqaew {
  d: path("M9.97 23.04c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.ng7b7qbdm {
  cx: 20.74px;
  cy: 10.777px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nmvo9zpwd {
  cx: 13.512px;
  cy: 9.998px;
  rx: 0.39px;
  ry: 0.197px;
}

.nv-ho4bep {
  d: path("M3.024 23.93V4.94h25.99v18.99z");
}

.o25db_ffh {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.575 9.344c-.654 0-1.206.451-1.356 1.06a.274.274 0 0 0 .268.341h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.129");
}

.o3ebqv6uh {
  d: path("M29.014 23.93H3.024V4.94l-.92-.68c-.05.09-.08.2-.08.3V24.3c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.oh-_iua0g {
  stop-color: var(--svg-color--7a4f45, #7A4F45);
}

.onnug0jly {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 28.51h1.922");
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.owl7p83et {
  stop-color: var(--svg-color--7a4f45, #7A4F45);
  stop-opacity: 0;
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.p941os1jk {
  d: path("M18.153 9.617a.893.893 0 0 1 .86 1.128h-1.725a.897.897 0 0 1 .865-1.129");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.psnc0zbqv {
  d: path("M20.844 9.023h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-1.11c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q3m7mz1ko {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 28.51H11.03");
}

.q4sggw3zw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 25.98H11.03");
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qbx2b9bsz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 27.245H11.03");
}

.qen7stbxp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.632 7.91c.43-.076 1.27-.054 1.851.398");
}

.qj2o0obna {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 25.98h1.922");
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxgg0f5pn {
  d: path("M22.067 23.048c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.rag9kob-h {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.694 10.654l-.82 1.701c-.103.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.378-.284-.378-.396 0");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rejus4bhg {
  d: path("M11.167 21.432c0-.384.311-.695.695-.695h9.812v1.39h-9.812a.695.695 0 0 1-.695-.695");
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.srescvb5j {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m20.793 4.293l.43.213c.752.374 1.181 1.228 1.02 2.136l-.59 3.043c-.053.314-.26.525-.573.533h-.018s.054-.907.107-1.441c.044-.434-.032-.566-.43-.96c-.214-.214-.375-.535-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.748c.054.587.107 1.441.107 1.441l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.213a8 8 0 0 0 .805-.587l.967-1.015c.59-.534 1.45-.694 2.2-.32c.538.16 1.128.16 1.665 0c.806-.267 1.718-.053 2.363.534l.805.8c.215.267.483.428.805.588");
}

.sv2duxbev {
  cx: 20.74px;
  cy: 10.777px;
  r: 0.996px;
}

.t5acn1bmk {
  d: path("M13.363 25.31a.81.81 0 0 1-.302.667a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.636a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.636c.187.144.302.39.302.668c-.009.42-.32.75-.684.75H9.744c-.427 0-.774-.401-.774-.894v-3.604c0-.493.347-.893.774-.893h2.842c.475 0 .77.39.777.76");
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.u9ogn5shy {
  stop-color: var(--svg-color--967973, #967973);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.ud7n83bkt {
  stop-color: var(--svg-color--815f55, #815F55);
  stop-opacity: 0;
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ukmsama-k {
  d: path("m15.588 10.491l-.532 1.701a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.378-.646-.378-.766 0");
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.ut1w03l9j {
  d: path("M22.694 29.94V17.696a10.98 10.98 0 0 1 4.32 8.744v3.5z");
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vkgern59s {
  d: path("m19.693 8.054l-.001-.001l-.002-.002l-.005-.003l-.011-.01l-.037-.027a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.493-.159a.534.534 0 0 0 .167 1.056c.398-.063.717.01.935.096a1.5 1.5 0 0 1 .308.166a.534.534 0 0 0 .68-.825");
}

.vo580yu-k {
  d: path("M14.598 10.405c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.vo92-0bqu {
  stop-color: var(--svg-color--724838, #724838);
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.vz-1cdczy {
  d: path("M13.782 9.617a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w32pebg-b {
  d: path("M18.674 25.31a.81.81 0 0 0 .303.667a.8.8 0 0 0-.303.637c0 .267.116.503.303.636a.8.8 0 0 0-.303.637c0 .267.116.503.303.636a.84.84 0 0 0-.303.668c.01.42.32.75.685.75h2.935c.426 0 .773-.401.773-.894v-3.604c0-.493-.347-.893-.773-.893H19.45a.776.776 0 0 0-.777.76");
}

.w42o3etxb {
  d: path("M18.949 10.392a.84.84 0 0 0-.232-.463l-.26.286l.117.228z");
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.whxihzpaf {
  stop-color: var(--svg-color--5f3e52, #5F3E52);
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wpeyy_b3b {
  stop-color: var(--svg-color--9c7c74, #9C7C74);
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xiop2xigt {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.588 10.491l-.532 1.701a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.378-.646-.378-.766 0");
}

.xmn8bcbuh {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.428 29.94v-8.406h-2.094v8.406z");
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.xxdh54bza {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.087 9.805c.064.086-.069.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.y7rb0nbsx {
  stop-color: var(--svg-color--895b5e, #895B5E);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.y9fu8v2us {
  stop-color: var(--svg-color--6f4446, #6F4446);
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z_uo_hbxt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.433 5.96v.9c-.008.148-.07.48-.259.621");
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zjyx6dbdf {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.193 8.054l.002-.002l.005-.003l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.063.241-.14.42-.211c.36-.142.872-.257 1.494-.159a.534.534 0 1 1-.167 1.056a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.309.166a.534.534 0 0 1-.68-.825");
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zs3xtwb8v {
  d: path("m19.937 5.147l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zxm3y0btp {
  stop-color: var(--svg-color--3e201c, #3E201C);
}

</style>
