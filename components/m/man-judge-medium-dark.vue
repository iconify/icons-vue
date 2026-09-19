<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iLlVbQd)" class="z-h6nw1-s"/><path fill="url(#ioxKjjb)" class="z-h6nw1-s"/><path fill="url(#iRYf25b)" class="z-h6nw1-s"/><path fill="url(#iAtpLsb)" class="hfmpo9b_u"/><path fill="url(#i1k9eYc)" class="hfmpo9b_u"/><path fill="url(#ilLFWWu)" class="hfmpo9b_u"/><path fill="url(#idlXfoe)" class="hfmpo9b_u"/><path fill="url(#iTfxsjb)" class="t81ggubje"/><path fill="url(#iyqXSde)" class="t81ggubje"/><g filter="url(#ie5Vwed)"><path fill="url(#iMQhscb)" class="mn9ru5b4q"/><path fill="url(#ij0jsne)" class="mn9ru5b4q"/><path fill="url(#id8ulIe)" class="mn9ru5b4q"/></g><path fill="url(#it2Y9ld)" class="l6ashw9ni"/><path fill="url(#igJ7Gdu)" class="xy872qbut"/><path fill="url(#iU4Re8d)" class="r8edv_xca"/><path fill="url(#iEbwXTd)" class="r8edv_xca"/><path fill="url(#isOz5sb)" class="r8edv_xca"/><path fill="url(#iRnUqxc)" class="q9osfabse"/><path fill="url(#iN16RHd)" class="q9osfabse"/><path fill="url(#it8ahIz)" class="ng_fdkb2h"/><path fill="url(#iSdBOWb)" class="ng_fdkb2h"/><path fill="url(#iD00IUb)" class="ng_fdkb2h"/><path fill="url(#iyfoC0N)" class="ng_fdkb2h"/><path fill="url(#iO8Ir7c)" class="ng_fdkb2h"/><path fill="url(#i9F0CWd)" class="as5tmxfyu"/><path fill="url(#i2lS2tB)" class="as5tmxfyu"/><path fill="url(#iZtEnrG)" class="as5tmxfyu"/><path fill="url(#iXmAY8d)" class="as5tmxfyu"/><path fill="url(#iIOLygd)" class="xc2sa2hkn"/><path fill="url(#ieXIvzd)" class="xc2sa2hkn"/><path fill="url(#igwB1nb)" class="xc2sa2hkn"/><path fill="url(#io6Ngcb)" class="l2ma45b1n"/><path fill="url(#ixUP6De)" class="l2ma45b1n"/><g filter="url(#it2RSkb)"><path fill="url(#ito3NQd)" class="omrh9bh8l"/><path fill="url(#iScBLdc)" class="omrh9bh8l"/><path fill="url(#iki1rZo)" class="omrh9bh8l"/><path fill="url(#iEQPwOc)" class="omrh9bh8l"/><path fill="url(#ifuBdWc)" class="omrh9bh8l"/></g><rect fill="url(#iwyrtab)" class="c7sh1acso"/><rect fill="url(#iRyRG3b)" class="c7sh1acso"/><g filter="url(#iWJJ5Ec)"><path fill="url(#iaF58Ub)" class="uqiue6t_b"/></g><g filter="url(#iNlkfgd)"><path fill="url(#iJUwUqe)" class="wwzvxlb-q"/></g><g filter="url(#i545vPe)"><path fill="url(#i3iMuud)" class="f36g284ki"/></g><g filter="url(#iIJnluc)"><path stroke="url(#ipQzKId)" class="ncj6tac7p"/></g><g filter="url(#imvbtWb)"><path stroke="url(#iyvK90d)" class="pyobejbsx"/></g><g filter="url(#iLRPfxe)"><path stroke="url(#iwyw9Oe)" class="e0n028cjd"/></g><g filter="url(#iBEpY2d)"><circle fill="url(#iWdKJFb)" class="ulonu-bqn"/></g><g filter="url(#iwSC9De)"><circle fill="url(#iVgLSdb)" class="wts2f8bwo"/></g><g filter="url(#iwxWjdc)"><circle fill="url(#iJud0qe)" class="e55eugbqv"/><circle fill="url(#i9kwWgd)" class="e55eugbqv"/></g><g filter="url(#iGmGS2d)"><circle class="kuoykms-t"/><circle fill="url(#iS8D3Ke)" class="zpond1brl"/><circle fill="url(#ixcqhed)" class="zpond1brl"/></g><g filter="url(#ixlCDwe)"><path fill="url(#i4tllab)" class="hi8gi_24b"/><path fill="url(#iVuP3be)" class="hi8gi_24b"/><path fill="url(#iuaergj)" class="hi8gi_24b"/></g><path fill="url(#iqSRg9b)" class="l_3ne62yf"/><path fill="url(#i6cjwsy)" class="l_3ne62yf"/><path fill="url(#i5bsiNe)" class="l_3ne62yf"/><path fill="url(#ict4Kke)" class="l_3ne62yf"/><path fill="url(#imBLoCe)" class="l_3ne62yf"/><g filter="url(#izuEbKb)"><path fill="url(#iwO2eCe)" class="bim-cnbfr"/></g><g filter="url(#iI0GIZb)"><path class="md9y5liwv"/><path fill="url(#i08MVUd)" class="x5-qk2fly"/><path fill="url(#itetcVV)" class="x5-qk2fly"/><path fill="url(#ik8D1Lm)" class="x5-qk2fly"/><path fill="url(#iKFMz2c)" class="x5-qk2fly"/></g><g filter="url(#iemnJSb)"><path class="apj_c-a6u"/></g><g filter="url(#irb235c)"><path class="ic7m8nmtn"/><path fill="url(#iXyW7Bc)" class="rgvc-hdys"/><path fill="url(#iqYWIyO)" class="rgvc-hdys"/><path fill="url(#iV4Fuod)" class="rgvc-hdys"/><path fill="url(#iunHMPe)" class="rgvc-hdys"/></g><path fill="url(#id9Arxb)" class="rgvc-hdys"/><path stroke="url(#iBhixrE)" class="dgzbw1-9s"/><g filter="url(#iIksU8I)"><path class="uzvu7zbua"/><path fill="url(#iImdnSc)" class="g-iu7ij5z"/></g><g filter="url(#iXLx9te)"><path class="j37j0-brg"/><path fill="url(#isheIje)" class="j2bf1cbhp"/></g><path class="l9nvz40cx"/><path fill="url(#iA2GKAb)" class="jr7rlzp4p"/><path class="ahvkpu67y"/><g filter="url(#iNaPkSc)"><path class="ukp831szg"/><path fill="url(#ibt69MO)" class="te17y1b8z"/></g><g filter="url(#iniqPjb)"><path fill="url(#iGVv30d)" class="ylca8fu7u"/></g><path class="zgxigs5us"/><path fill="url(#iNjrUXc)" class="hq4_ibcaf"/><path class="x4jvzigyq"/><g filter="url(#iYoxMvb)"><path fill="url(#iZUYvrd)" class="qgynz_bto"/></g><g filter="url(#irOjgqc)"><ellipse transform="rotate(-27.914 13.355 9.711)" class="hvtaxxqni"/><ellipse fill="url(#iRmD7Zd)" transform="rotate(-27.914 13.355 9.711)" class="gpp-4c70a"/></g><g filter="url(#ihWLZad)"><path stroke="url(#iLlwVKb)" class="ijac4foxz"/></g><g filter="url(#ieMzvOe)"><path stroke="url(#iUIe97b)" class="x6lkzh3et"/></g><g filter="url(#iF2wF4d)"><path stroke="url(#ieye8TL)" class="ao64hscir"/></g><defs><radialGradient id="iAtpLsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 4.731 30.004)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="i1k9eYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.58 30.004)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="ilLFWWu" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.58 23.055)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="iTfxsjb" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 24.917 4.656)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iyqXSde" cx="0" cy="0" r="1" gradientTransform="matrix(.55555 12.0481 -1.01912 .047 22.862 23.157)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="ij0jsne" cx="0" cy="0" r="1" gradientTransform="matrix(5.96102 5.60934 -10.1311 10.76628 15.822 14.816)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="w-er2h93j"/><stop offset=".937" class="nbg9ac2nn"/></radialGradient><radialGradient id="id8ulIe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.11642 0 0 -3.80242 15.822 16.394)" gradientUnits="userSpaceOnUse"><stop class="qbrho_b3d"/><stop offset="1" class="jxn3-wb7y"/></radialGradient><radialGradient id="igJ7Gdu" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -2.76048 0 15.809 18.504)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="o5ej-52sf"/><stop offset="1" class="wyytu2b0o"/></radialGradient><radialGradient id="iU4Re8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.82081 -2.84518 0 16.582 16.467)" gradientUnits="userSpaceOnUse"><stop class="ig14nderp"/><stop offset="1" class="tcdzfs0as"/></radialGradient><radialGradient id="iEbwXTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.42297 -2.45165 0 15.812 15.379)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="ispcapbgm"/><stop offset=".975" class="c5reugbnm"/></radialGradient><radialGradient id="isOz5sb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42187 -.53125 0 14.5 16.224)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="ox076faqk"/><stop offset="1" class="zqgbv4b6r"/></radialGradient><radialGradient id="iRnUqxc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57562 1.29893 -1.2769 -1.54888 27.554 23.564)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="iN16RHd" cx="0" cy="0" r="1" gradientTransform="matrix(.75156 -.57402 .30002 .3928 27.322 23.413)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="iD00IUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.507 17.397)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="iXmAY8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.22 17.223)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="igwB1nb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 28.986 17.473)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="io6Ngcb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 25.908 24.288)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="iScBLdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.676 25.309)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iki1rZo" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.676 26.603)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iEQPwOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.676 27.853)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ifuBdWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.676 29.205)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iwyrtab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.353 21.465)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="iWdKJFb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.39 10.49)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="i9kwWgd" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 20.956 10.225)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iS8D3Ke" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.542 11.312)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="ixcqhed" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.583 10.49)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iVuP3be" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.161 9.217)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iuaergj" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 13.599 9.351)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="i5bsiNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.52064 -11.5663 0 15.511 8.714)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="qzvao6brn"/><stop offset="1" class="vmy6jjibx"/></radialGradient><radialGradient id="ict4Kke" cx="0" cy="0" r="1" gradientTransform="rotate(-146.07 12.543 5.143)scale(2.07148 1.17905)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="imBLoCe" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -.54454 .34491 1.64288 12.174 17.444)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="i08MVUd" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.42495 .38451 20.162 6.38)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="itetcVV" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.518 4.618)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="ik8D1Lm" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.813 1.88)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iKFMz2c" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.358 8.704)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iunHMPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.14 12.098)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iImdnSc" cx="0" cy="0" r="1" gradientTransform="matrix(.10429 -.60384 1.7864 .30853 18.26 8.403)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="isheIje" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.543 -3.58)scale(.61278 1.81296)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iA2GKAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 17.994 9.807)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ibt69MO" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.766 9.891)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNjrUXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.627 9.807)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iRmD7Zd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.605 -1.553)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iLlVbQd" x1="15.808" x2="15.808" y1="15.545" y2="30.429" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="ioxKjjb" x1="23.236" x2="20.705" y1="26.598" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="iRYf25b" x1="8.264" x2="10.48" y1="26.414" y2="26.414" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="idlXfoe" x1="8.727" x2="8.292" y1="28.07" y2="28.07" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iMQhscb" x1="22.549" x2="16.674" y1="18.504" y2="18.504" gradientUnits="userSpaceOnUse"><stop class="l4epxabbu"/><stop offset="1" class="mjg0akbde"/></linearGradient><linearGradient id="it2Y9ld" x1="16.939" x2="15.642" y1="19.082" y2="20.004" gradientUnits="userSpaceOnUse"><stop offset=".048" class="iluzr5dja"/><stop offset="1" class="huftmtb3i"/></linearGradient><linearGradient id="it8ahIz" x1="27.549" x2="24.174" y1="20.723" y2="20.348" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="iSdBOWb" x1="25.269" x2="25.269" y1="20.988" y2="20.473" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="iyfoC0N" x1="25.269" x2="25.269" y1="16.843" y2="17.473" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="iO8Ir7c" x1="22.972" x2="23.713" y1="19.19" y2="19.19" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="i9F0CWd" x1="23.142" x2="21.845" y1="18.974" y2="18.974" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="i2lS2tB" x1="23.392" x2="23.002" y1="19.254" y2="19.254" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="iZtEnrG" x1="22.597" x2="22.597" y1="21.085" y2="20.422" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="iIOLygd" x1="28.844" x2="27.223" y1="19.421" y2="19.421" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="ieXIvzd" x1="28.142" x2="28.142" y1="21.059" y2="20.535" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="ixUP6De" x1="25.271" x2="25.299" y1="22" y2="22.356" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="ito3NQd" x1="27.267" x2="23.239" y1="28.067" y2="28.067" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="iRyRG3b" x1="25.281" x2="25.281" y1="20.817" y2="21.278" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iaF58Ub" x1="16.858" x2="16.858" y1="29.607" y2="22.931" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iJUwUqe" x1="12.852" x2="12.852" y1="29.607" y2="22.931" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="i3iMuud" x1="20.845" x2="20.845" y1="29.607" y2="22.931" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ipQzKId" x1="23.759" x2="25.469" y1="26.075" y2="26.075" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iyvK90d" x1="23.681" x2="25.391" y1="27.379" y2="27.379" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iwyw9Oe" x1="23.759" x2="25.469" y1="28.684" y2="28.684" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iVgLSdb" x1="11.061" x2="10.42" y1="10.768" y2="10.768" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iJud0qe" x1="21.671" x2="20.851" y1="9.397" y2="11.936" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="i4tllab" x1="19.853" x2="12.209" y1="10.88" y2="12.019" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iqSRg9b" x1="10.412" x2="12.295" y1="13.578" y2="13.511" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="i6cjwsy" x1="20.682" x2="19.625" y1="12.739" y2="12.639" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iwO2eCe" x1="15.281" x2="23.433" y1="7.892" y2="4.973" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iXyW7Bc" x1="14.948" x2="15.887" y1="11.539" y2="11.539" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iqYWIyO" x1="16.752" x2="15.726" y1="11.862" y2="11.847" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iV4Fuod" x1="16.008" x2="16.008" y1="12.605" y2="12.031" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="id9Arxb" x1="15.939" x2="15.939" y1="12.647" y2="12.479" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="iBhixrE" x1="14.775" x2="15.21" y1="14.222" y2="13.534" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iGVv30d" x1="18.773" x2="18.459" y1="9.861" y2="10.054" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZUYvrd" x1="14.371" x2="14.057" y1="9.861" y2="10.054" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLlwVKb" x1="18.788" x2="18.368" y1="7.719" y2="6.86" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iUIe97b" x1="13.479" x2="12.288" y1="7.591" y2="7.092" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ieye8TL" x1="11.147" x2="11.147" y1="5.575" y2="7.734" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><filter id="ie5Vwed" width="14.254" height="7.618" x="8.795" y="15.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.141176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1733"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.4 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1733" result="effect2_innerShadow_4002_1733"/></filter><filter id="it2RSkb" width="4.468" height="5.556" x="23.239" y="24.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1733"/></filter><filter id="iWJJ5Ec" width="1.192" height="6.826" x="15.226" y="23.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".125"/></filter><filter id="iNlkfgd" width="1.192" height="6.826" x="11.219" y="23.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".125"/></filter><filter id="i545vPe" width="1.192" height="6.826" x="19.213" y="23.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".125"/></filter><filter id="iIJnluc" width="2.097" height=".3" x="23.61" y="25.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".05"/></filter><filter id="imvbtWb" width="2.097" height=".3" x="23.531" y="27.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".05"/></filter><filter id="iLRPfxe" width="2.097" height=".3" x="23.61" y="28.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".05"/></filter><filter id="iBEpY2d" width="3.542" height="3.342" x="9.39" y="8.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1733"/></filter><filter id="iwSC9De" width="2.992" height="2.992" x="9.565" y="8.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".25"/></filter><filter id="iwxWjdc" width="3.592" height="3.592" x="18.912" y="8.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1733"/></filter><filter id="iGmGS2d" width="2.992" height="2.992" x="19.087" y="8.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".25"/></filter><filter id="ixlCDwe" width="10.383" height="12.189" x="10.65" y="4.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1733"/></filter><filter id="izuEbKb" width="8.25" height="7.07" x="13.983" y="2.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation="1"/></filter><filter id="iI0GIZb" width="12.614" height="8.551" x="9.506" y="1.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1733"/></filter><filter id="iemnJSb" width="3.262" height="4.184" x="13.943" y="9.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".375"/></filter><filter id="irb235c" width="2.379" height="3.184" x="14.624" y="9.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".125"/></filter><filter id="iIksU8I" width="2.982" height="1.874" x="16.996" y="6.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1733"/></filter><filter id="iXLx9te" width="2.982" height="1.874" x="11.844" y="6.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1733"/></filter><filter id="iNaPkSc" width=".787" height=".697" x="17.259" y="9.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".05"/></filter><filter id="iniqPjb" width=".892" height=".914" x="18.1" y="9.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".1"/></filter><filter id="iYoxMvb" width=".987" height="1.041" x="13.654" y="9.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".1"/></filter><filter id="irOjgqc" width=".914" height=".705" x="12.899" y="9.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".05"/></filter><filter id="ihWLZad" width="3.101" height="1.681" x="16.85" y="6.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".25"/></filter><filter id="ieMzvOe" width="3.179" height="1.739" x="11.626" y="7.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".25"/></filter><filter id="iF2wF4d" width="1.008" height="2.271" x="10.643" y="5.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1733" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-judge-medium-dark" /></template>
<style>
.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahvkpu67y {
  fill: var(--svg-color--000, #000);
  d: path("M17.485 10.223a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.ao64hscir {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.276 5.674v.898c-.008.149-.07.482-.258.623");
}

.apj_c-a6u {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.538 10.367l-.822 1.702c-.101.35.143.7.489.7h.738c.346 0 .59-.356.488-.7l-.498-1.702c-.107-.377-.284-.377-.396 0");
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.as5tmxfyu {
  d: path("M22.814 16.96h-.613a.505.505 0 0 0-.503.503v3.022c0 .272.221.503.503.503h.613a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.bim-cnbfr {
  d: path("M19.78 4.86L16.7 5.887a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c5reugbnm {
  stop-color: var(--svg-color--5a3124, #5A3124);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c7sh1acso {
  width: 2.773px;
  height: 1.082px;
  x: 23.894px;
  y: 20.988px;
  rx: 0.541px;
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
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

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dgzbw1-9s {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.45 13.25a2.96 2.96 0 0 0 1.363.322c.505 0 .97-.117 1.363-.322a.2.2 0 0 1 .242.04a.19.19 0 0 1 .021.24m-2.99-.28l2.949.253m-2.948-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.21.028l-.041-.028m.041.028l-.041-.028m.041.028a1.95 1.95 0 0 1-1.626.869a1.95 1.95 0 0 1-1.626-.869m3.21-.028c-.335.508-.919.847-1.584.847s-1.25-.339-1.584-.847m-.042.028l.042-.028m-.042.028l.042-.028");
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0n028cjd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.76 28.606h1.796");
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.e55eugbqv {
  cx: 20.583px;
  cy: 10.49px;
  r: 1.671px;
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f36g284ki {
  d: path("M19.463 23.548h.692v6.326h-.692z");
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.ft5dv1b6b {
  fill: none;
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g-iu7ij5z {
  d: path("M19.536 7.767h-.001l-.002-.002l-.005-.004l-.011-.01a1.4 1.4 0 0 0-.155-.107c-.1-.063-.242-.14-.42-.211a2.84 2.84 0 0 0-1.495-.159a.534.534 0 1 0 .167 1.056c.398-.063.717.01.935.096a1.5 1.5 0 0 1 .3.16l.008.006a.534.534 0 0 0 .68-.825");
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gpp-4c70a {
  cx: 13.355px;
  cy: 9.711px;
  rx: 0.39px;
  ry: 0.197px;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.hfmpo9b_u {
  d: path("M8.58 30.004v-11.8c-2.356 2.01-3.849 4.986-3.849 8.31v3.49z");
}

.hi8gi_24b {
  d: path("m10.708 9.876l.05.002s-.054-.854-.108-1.441c0-.267.107-.588.322-.748l.161-.16c.269-.213.376-.534.376-.854V5.82a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.053.429.267.429.534v.854c0 .32.161.64.376.854c.502.352.471.546.43.961a46 46 0 0 0-.108 1.441h.018l-.266 3.962c-.16 1.772-1.553 3.006-3.213 3.006H14.23c-1.714 0-3.053-1.234-3.213-3.006z");
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hq4_ibcaf {
  d: path("M13.625 9.33a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.huftmtb3i {
  stop-color: var(--svg-color--ada3a2, #ADA3A2);
}

.hvtaxxqni {
  cx: 13.355px;
  cy: 9.711px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ic7m8nmtn {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.43 10.204l-.531 1.701a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .521-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.ig14nderp {
  stop-color: var(--svg-color--7b5653, #7B5653);
}

.ijac4foxz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.475 7.622c.43-.075 1.27-.053 1.851.399");
}

.iluzr5dja {
  stop-color: var(--svg-color--978b8d, #978B8D);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.ispcapbgm {
  stop-color: var(--svg-color--5a3124, #5A3124);
  stop-opacity: 0;
}

.j2bf1cbhp {
  d: path("M12.036 7.767h.002l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.063.241-.14.42-.211c.36-.142.873-.257 1.494-.159a.534.534 0 0 1-.166 1.056a1.77 1.77 0 0 0-.935.096a1.5 1.5 0 0 0-.309.166a.534.534 0 0 1-.679-.825");
}

.j37j0-brg {
  fill: var(--svg-color--352827, #352827);
  d: path("M12.036 7.767h.002l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.063.241-.14.42-.211c.36-.142.873-.257 1.494-.159a.534.534 0 0 1-.166 1.056a1.77 1.77 0 0 0-.935.096a1.5 1.5 0 0 0-.309.166a.534.534 0 0 1-.679-.825");
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.jr7rlzp4p {
  d: path("M17.996 9.33a.893.893 0 0 1 .86 1.128h-1.725a.897.897 0 0 1 .865-1.129");
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jxn3-wb7y {
  stop-color: var(--svg-color--3b2321, #3B2321);
  stop-opacity: 0;
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kuoykms-t {
  cx: 20.583px;
  cy: 10.49px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzk-_ccou {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
  stop-opacity: 0;
}

.l_3ne62yf {
  d: path("M10.65 8.437c0-.267.107-.588.322-.748l.161-.16c.269-.213.376-.534.376-.854V5.82a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.053.429.267.429.534v.854c0 .32.161.64.376.854c.502.352.471.546.43.961a46 46 0 0 0-.108 1.441h.018l-.266 3.962c-.16 1.772-1.553 3.006-3.213 3.006H14.23c-1.714 0-3.053-1.234-3.213-3.006c-.14-1.818-.2-3.641-.367-5.456");
}

.l2ma45b1n {
  d: path("M24.515 21.075v6.427h1.511v-6.427z");
}

.l4epxabbu {
  stop-color: var(--svg-color--564d5b, #564D5B);
}

.l6ashw9ni {
  d: path("m16.739 19.766l-.655.584a.415.415 0 0 1-.554 0l-.655-.585a3.47 3.47 0 0 1-1.148-2.568v-3.113a2.085 2.085 0 0 1 2.085-2.065c1.148 0 2.075.927 2.075 2.075v3.113a3.5 3.5 0 0 1-1.148 2.558");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9nvz40cx {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.203 9.058c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m13zyzbuk {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.md9y5liwv {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m20.637 4.006l.43.213c.75.374 1.18 1.228 1.02 2.136l-.591 3.042c-.053.315-.26.526-.573.534h-.018s.054-.907.107-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854V5.82c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.215.16-.323.48-.323.748c.054.587.108 1.44.108 1.44h-.05a.634.634 0 0 1-.595-.533L9.523 6.3c-.108-.854.322-1.708 1.074-2.082l.429-.213a8 8 0 0 0 .805-.588l.967-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.128.16 1.664 0c.806-.267 1.719-.054 2.363.534l.805.8c.215.267.483.427.806.588");
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mjg0akbde {
  stop-color: var(--svg-color--433945, #433945);
}

.mn9ru5b4q {
  d: path("M8.882 17.872c1.975-1.646 4.386-2.422 6.94-2.422c2.553 0 4.965.776 6.94 2.422a.24.24 0 0 1 .06.296c-1.354 2.69-3.771 4.65-7 4.65s-5.646-1.96-7.001-4.65a.24.24 0 0 1 .061-.296");
}

.nbg9ac2nn {
  stop-color: var(--svg-color--59545e, #59545E);
}

.ncj6tac7p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.76 25.996h1.796");
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.ng_fdkb2h {
  d: path("M26.72 16.96h-2.902a.505.505 0 0 0-.503.503v3.022c0 .272.221.503.503.503h2.901a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o5ej-52sf {
  stop-color: var(--svg-color--d7cace, #D7CACE);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.omrh9bh8l {
  d: path("M23.24 25.33c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.ox076faqk {
  stop-color: var(--svg-color--6e504f, #6E504F);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.pyobejbsx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.681 27.301h1.797");
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.q9osfabse {
  d: path("M26.596 22.937c.53 0 .958.427.958.959v2.188h-1.907v-2.188a.94.94 0 0 1 .949-.959");
}

.qbrho_b3d {
  stop-color: var(--svg-color--3b2321, #3B2321);
}

.qgynz_bto {
  d: path("M14.44 10.118c0-.289-.234-.481-.297-.54l-.289.28l.178.361z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.qzvao6brn {
  stop-color: var(--svg-color--784758, #784758);
  stop-opacity: 0;
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.r8edv_xca {
  d: path("M15.812 18.738a2.07 2.07 0 0 1-2.075-2.075v-2.579a2.07 2.07 0 0 1 2.075-2.065c1.148 0 2.075.927 2.075 2.075v2.58a2.083 2.083 0 0 1-2.075 2.064");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rgvc-hdys {
  d: path("m15.43 10.204l-.531 1.701a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .521-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.t81ggubje {
  d: path("M23.034 30.004v-11.8c2.356 2.01 3.848 4.986 3.848 8.31v2.49a1 1 0 0 1-1 1z");
}

.tcdzfs0as {
  stop-color: var(--svg-color--704539, #704539);
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.te17y1b8z {
  d: path("M17.93 9.518c.064.085-.069.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
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

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ukp831szg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.93 9.518c.064.085-.069.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
}

.ulonu-bqn {
  cx: 11.061px;
  cy: 10.49px;
  r: 1.671px;
}

.uqiue6t_b {
  d: path("M15.476 23.548h.692v6.326h-.692z");
}

.uzvu7zbua {
  fill: var(--svg-color--352827, #352827);
  d: path("M19.536 7.767h-.001l-.002-.002l-.005-.004l-.011-.01a1.4 1.4 0 0 0-.155-.107c-.1-.063-.242-.14-.42-.211a2.84 2.84 0 0 0-1.495-.159a.534.534 0 1 0 .167 1.056c.398-.063.717.01.935.096a1.5 1.5 0 0 1 .3.16l.008.006a.534.534 0 0 0 .68-.825");
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

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vmy6jjibx {
  stop-color: var(--svg-color--64343f, #64343F);
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w-er2h93j {
  stop-color: var(--svg-color--59545e, #59545E);
  stop-opacity: 0;
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wts2f8bwo {
  cx: 11.061px;
  cy: 10.49px;
  r: 0.996px;
}

.wwzvxlb-q {
  d: path("M11.469 23.548h.692v6.326h-.692z");
}

.wyytu2b0o {
  stop-color: var(--svg-color--897576, #897576);
}

.x4jvzigyq {
  fill: var(--svg-color--000, #000);
  d: path("M14.136 10.223a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.235");
}

.x5-qk2fly {
  d: path("m20.637 4.006l.43.213c.75.374 1.18 1.228 1.02 2.136l-.591 3.042c-.053.315-.26.526-.573.534h-.018s.054-.907.107-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854V5.82c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.215.16-.323.48-.323.748c.054.587.108 1.44.108 1.44h-.05a.634.634 0 0 1-.595-.533L9.523 6.3c-.108-.854.322-1.708 1.074-2.082l.429-.213a8 8 0 0 0 .805-.588l.967-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.128.16 1.664 0c.806-.267 1.719-.054 2.363.534l.805.8c.215.267.483.427.806.588");
}

.x6lkzh3et {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.25 8.141c.328-.29 1.043-.594 1.93-.453");
}

.xc2sa2hkn {
  d: path("M28.34 16.96h-.613a.505.505 0 0 0-.504.503v3.022c0 .272.222.503.504.503h.613a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xy872qbut {
  d: path("m16.603 19.887l.136-.122a3.5 3.5 0 0 0 1.148-2.548v-1.964h-4.15l-.006 1.911c0 .052.004.147 0 .2c.045.916.46 1.784 1.144 2.401l.16.144l.666-1.01a.13.13 0 0 1 .221 0z");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ylca8fu7u {
  d: path("M18.792 10.105a.84.84 0 0 0-.232-.463l-.26.286l.117.228z");
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z-h6nw1-s {
  d: path("M15.812 15.545c-6.115 0-11.08 4.906-11.08 10.969v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.063-4.956-10.97-11.07-10.97");
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zgxigs5us {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.418 9.058c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zpond1brl {
  cx: 20.583px;
  cy: 10.49px;
  r: 0.996px;
}

.zqgbv4b6r {
  stop-color: var(--svg-color--6e504f, #6E504F);
  stop-opacity: 0;
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
