<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iwe9HNc)"><path fill="url(#i46C1De)" class="shh3pobzz"/></g><path fill="url(#iUC1WLj)" class="va3mrqbij"/><path fill="url(#iQ1Iedb)" class="va3mrqbij"/><path fill="url(#iumkZbc)" class="va3mrqbij"/><g filter="url(#iKN9ije)"><path stroke="url(#iFo3bzb)" class="emj41xbgw"/></g><g filter="url(#iyxVibb)"><path fill="url(#iyULoNd)" class="xwft4kidb"/><path fill="url(#iRBH2Wv)" class="xwft4kidb"/><path fill="url(#iZ4gzwe)" class="xwft4kidb"/></g><path fill="url(#ilfG40B)" class="sywgf9b1r"/><path fill="url(#iEaju7c)" class="sywgf9b1r"/><path fill="url(#iKgrEhe)" class="sywgf9b1r"/><path fill="url(#iIsIFeb)" class="rkuwb3brg"/><path fill="url(#iGWz8Cd)" class="rkuwb3brg"/><path fill="url(#iym1hEx)" class="rkuwb3brg"/><path fill="url(#iWRh6qe)" class="lv2gkibab"/><path fill="url(#iALhPRl)" class="lv2gkibab"/><path fill="url(#i8IKXBc)" class="w7nnggeov"/><g filter="url(#iTYaS0d)"><path fill="url(#iJSgFCe)" class="ipubjpcdo"/><path fill="url(#iwKTz4b)" class="ipubjpcdo"/><path fill="url(#i7lhTNc)" class="ipubjpcdo"/><path fill="url(#iE0Inie)" class="ipubjpcdo"/></g><g filter="url(#i84x23h)"><path fill="url(#iBYbnId)" class="j64dyhblj"/><path fill="url(#iibhIrc)" class="j64dyhblj"/><path fill="url(#iR66gIc)" class="j64dyhblj"/><path fill="url(#ihSBS3c)" class="j64dyhblj"/></g><path fill="url(#iVbPhgc)" class="vcd2dsbig"/><g filter="url(#iiLfspb)"><path fill="url(#i5VdmDb)" class="ie-4wgb6h"/><path fill="url(#ie4UpSx)" class="ie-4wgb6h"/></g><g filter="url(#i6gpZ8b)"><path fill="url(#iJe2Qtd)" class="p5124lb-x"/></g><path fill="url(#i24HKoc)" class="xqkpf3bhk"/><path clip-rule="evenodd" class="ksq4irbhi"/><path fill="url(#iLEHsse)" clip-rule="evenodd" class="zd_xb-brh"/><g filter="url(#iIDyRCb)"><path fill="url(#itSRgfe)" class="yznyh2bbq"/><path fill="url(#it7YeYc)" class="yznyh2bbq"/><path fill="url(#iepRdxc)" class="yznyh2bbq"/><path fill="url(#i60XGcc)" class="yznyh2bbq"/><path fill="url(#iuuO8Ad)" class="yznyh2bbq"/></g><g filter="url(#i0oJ66b)"><path fill="url(#il8FDNe)" class="uq8i4tbrr"/><path fill="url(#ix75Fdb)" class="uq8i4tbrr"/><path fill="url(#ikolgmb)" class="uq8i4tbrr"/><path fill="url(#ix5ofid)" class="uq8i4tbrr"/><path fill="url(#i1AVBCb)" class="uq8i4tbrr"/></g><path fill="url(#ipLwKgb)" class="bfca8sb6i"/><path fill="url(#igxVwtc)" class="n5xd32bba"/><g filter="url(#iLMd0xe)"><path stroke="url(#igS7XUc)" class="t28c_-b3o"/></g><g filter="url(#irSCm4c)"><path stroke="url(#iWyGPcu)" class="ik7eqtbhg"/></g><g filter="url(#ixd4kbc)"><path stroke="url(#i1UpqEd)" class="jyi--k5rl"/></g><g filter="url(#irJdMAe)"><path stroke="url(#iEprgke)" class="bflrdnymp"/></g><g filter="url(#iyi8Zle)"><path stroke="url(#iS22jkd)" class="nlx2y1elu"/></g><g filter="url(#i7Wvmze)"><path stroke="url(#iqcl5DO)" class="ycra_99jz"/></g><g filter="url(#inm17ub)"><circle fill="url(#ifMaExL)" class="e31yjdb7y"/></g><g filter="url(#iCAwWJc)"><circle fill="url(#iN6bN4c)" class="isen2z7va"/></g><g filter="url(#iXWMFEc)"><circle fill="url(#iKXfQqz)" class="lh6xtyqlu"/><circle fill="url(#i9DiN7b)" class="lh6xtyqlu"/></g><g filter="url(#ivqym1m)"><circle class="wexr6jtej"/><circle fill="url(#ikSMFWb)" class="vx5kmin4y"/><circle fill="url(#i1j9IGb)" class="vx5kmin4y"/></g><g filter="url(#icNGXge)"><path fill="url(#iUmtXqe)" class="ijj8khz4b"/><path fill="url(#iRp6arc)" class="ijj8khz4b"/><path fill="url(#iymb1Gb)" class="ijj8khz4b"/><path fill="url(#iXygPmb)" class="ijj8khz4b"/><path fill="url(#iWCL2uN)" class="ijj8khz4b"/></g><g filter="url(#iVAjakb)"><path class="eb-j9_sfe"/><path fill="url(#iJso5Lc)" class="ivbeehj3f"/><path fill="url(#iW1B7uc)" class="ivbeehj3f"/><path fill="url(#ifLoBGb)" class="ivbeehj3f"/><path fill="url(#ise8Dge)" class="ivbeehj3f"/><path fill="url(#iy5mQPH)" class="ivbeehj3f"/></g><path fill="url(#i1sQQYd)" class="ivbeehj3f"/><path fill="url(#iIeZJie)" class="ivbeehj3f"/><g filter="url(#iR6NESc)"><path class="qb0swfwwv"/></g><g filter="url(#iQmdqyc)"><path class="c1q9k0uxh"/><path fill="url(#iBnq4xb)" class="klmuc4boz"/><path fill="url(#i3GXtOe)" class="klmuc4boz"/><path fill="url(#ion2jiY)" class="klmuc4boz"/></g><path fill="url(#i2OIwde)" class="klmuc4boz"/><path stroke="url(#ikrfMkc)" class="p1axjj2zk"/><g filter="url(#iYdsPzc)"><path class="l91o3_baa"/></g><g filter="url(#iWjYvMe)"><path class="o3rhcmbix"/></g><path class="bv5s3qxke"/><path fill="url(#i3Yhy8d)" class="b3k831b2t"/><path class="zldmt8bph"/><g filter="url(#i7Bxrme)"><path class="c5wh01b3e"/><path fill="url(#i0F5pCb)" class="l2vt5o7oc"/></g><g filter="url(#iD9tE3c)"><path fill="url(#iSSM2Ub)" class="bis1_sost"/></g><path class="gl5lc9gee"/><path fill="url(#itIAktd)" class="e3idwmvtr"/><path class="hi1zmhbhl"/><g filter="url(#iTL1Vpc)"><path fill="url(#iTL47Ie)" class="q0ubbqbnc"/></g><g filter="url(#iLL9Pzd)"><ellipse transform="rotate(-27.914 13.515 9.955)" class="anl-k5ncy"/><ellipse fill="url(#imY5oQx)" transform="rotate(-27.914 13.515 9.955)" class="u5wc358og"/></g><g filter="url(#ik2Hhse)"><path stroke="url(#iFAjpfe)" class="z4o42ufxk"/></g><g filter="url(#i3a7s7c)"><path stroke="url(#iXvCBwd)" class="vvj3csbha"/></g><g filter="url(#iRJKk6d)"><path fill="url(#i3BbLsb)" class="k4k_lggju"/><path fill="url(#ivQG06b)" class="k4k_lggju"/></g><defs><radialGradient id="iQ1Iedb" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 27.1 6.914)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="iumkZbc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.582 25.535)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="iZ4gzwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.024 4.37)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="ilfG40B" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.02 16.003)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="iEaju7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.676 20.535)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="iKgrEhe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.737 19.128)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="iIsIFeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27.014 28.285)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="iALhPRl" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.478 29.833)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="i8IKXBc" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 11.7969 15.207 20.347)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="iwKTz4b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.25 19.494)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="i7lhTNc" cx="0" cy="0" r="1" gradientTransform="rotate(-125.283 15.15 5.157)scale(1.63656 .29806)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="iE0Inie" cx="0" cy="0" r="1" gradientTransform="rotate(69.677 -2.874 21.18)scale(.94974 1.77776)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iibhIrc" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.535 20.41)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="ihSBS3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 1 -1.87182 -.87742 14.05 16.52)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iVbPhgc" cx="0" cy="0" r="1" gradientTransform="scale(2.05629 2.81101)rotate(90 .822 6.97)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="gcy2khpyp"/><stop offset="1" class="ns76nm5tj"/></radialGradient><radialGradient id="i5VdmDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.656 23.821)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="vh6yi_hgr"/><stop offset="1" class="e4t4y8vlz"/></radialGradient><radialGradient id="ie4UpSx" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.799 23.54)" gradientUnits="userSpaceOnUse"><stop class="vvq7hbbzt"/><stop offset="1" class="eb5hv9bjw"/></radialGradient><radialGradient id="iJe2Qtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 -.29687 .9302 -5.77708 11.113 24.063)" gradientUnits="userSpaceOnUse"><stop class="x109hm4su"/><stop offset="1" class="va5jmqb6u"/></radialGradient><radialGradient id="it7YeYc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.207 25.415)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="iepRdxc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.223 26.696)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="i60XGcc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.27 27.977)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="iuuO8Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.34 29.337)" gradientUnits="userSpaceOnUse"><stop class="g1nxbnbrj"/><stop offset="1" class="x_eyyzgvq"/></radialGradient><radialGradient id="ix75Fdb" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.27 25.415)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="ikolgmb" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.207 26.696)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="ix5ofid" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.113 27.977)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="i1AVBCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.973 29.337)" gradientUnits="userSpaceOnUse"><stop class="omd21jb4q"/><stop offset="1" class="qyaeouklz"/></radialGradient><radialGradient id="ifMaExL" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 9.553 10.733)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="i9DiN7b" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.107 10.468)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="ikSMFWb" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.694 11.554)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="i1j9IGb" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 20.736 10.733)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iRp6arc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.6693 -10.1935 0 16.44 7.391)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="vpd4dcexx"/><stop offset="1" class="upbi0xbpg"/></radialGradient><radialGradient id="iXygPmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 18.316 9.462)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iWCL2uN" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.758 9.428)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iJso5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.091 6.326)scale(5.6057 9.53299)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="ifLoBGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06682 -1.86131 .91413 -.03282 11.778 7.279)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="ise8Dge" cx="0" cy="0" r="1" gradientTransform="matrix(.85907 -1.96631 1.60368 .70064 20.197 8.996)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="iy5mQPH" cx="0" cy="0" r="1" gradientTransform="matrix(.9927 1.23176 -1.08755 .87648 15.195 2.132)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="i1sQQYd" cx="0" cy="0" r="1" gradientTransform="matrix(.18136 .78313 -1.28748 .29815 16.665 2.132)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iIeZJie" cx="0" cy="0" r="1" gradientTransform="matrix(.72544 .89725 -2.0104 1.62544 11.625 3.86)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="i3Yhy8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90308 -1.06858 0 18.149 10.384)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i0F5pCb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.442 .68)scale(.37817 .52064)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="itIAktd" cx="0" cy="0" r="1" gradientTransform="scale(1.06863 .90312)rotate(90 .701 12.2)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="imY5oQx" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.805 -1.51)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivQG06b" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.395 10.56)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><linearGradient id="i46C1De" x1="11.838" x2="31.281" y1="4.659" y2="22.895" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="iUC1WLj" x1="30.082" x2="9.145" y1="13.347" y2="13.347" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="iFo3bzb" x1="13.457" x2="31.27" y1="3.6" y2="24.412" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="iyULoNd" x1="-4.887" x2="28.926" y1="25.691" y2="25.691" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="iRBH2Wv" x1="3.113" x2="3.113" y1="5.253" y2="23.691" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="iGWz8Cd" x1="25.193" x2="25.193" y1="30.505" y2="26.688" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="iym1hEx" x1="22.426" x2="23.238" y1="29.316" y2="29.3" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="iWRh6qe" x1="7.154" x2="9.548" y1="28.198" y2="28.198" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="iJSgFCe" x1="18.074" x2="20.87" y1="18.425" y2="18.425" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="iBYbnId" x1="13.964" x2="11.167" y1="18.425" y2="18.425" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="iR66gIc" x1="12.129" x2="12.691" y1="16.988" y2="17.207" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="i24HKoc" x1="21.863" x2="17.488" y1="24.847" y2="24.847" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="iLEHsse" x1="10.334" x2="10.762" y1="23.628" y2="23.628" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="itSRgfe" x1="12.883" x2="8.582" y1="28.066" y2="28.066" gradientUnits="userSpaceOnUse"><stop class="oup8n6dpm"/><stop offset=".716" class="zw2whl-je"/></linearGradient><linearGradient id="il8FDNe" x1="22.488" x2="18.674" y1="27.66" y2="27.66" gradientUnits="userSpaceOnUse"><stop class="d1gud5zvw"/><stop offset=".807" class="bku9lhrph"/></linearGradient><linearGradient id="ipLwKgb" x1="10.801" x2="21.674" y1="22.003" y2="22.003" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="igxVwtc" x1="16.42" x2="16.42" y1="21.066" y2="22.238" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="igS7XUc" x1="19.043" x2="20.871" y1="26.168" y2="26.168" gradientUnits="userSpaceOnUse"><stop class="s9f5xlzkg"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="bi-ijln_l"/></linearGradient><linearGradient id="iWyGPcu" x1="12.952" x2="10.754" y1="26.168" y2="26.168" gradientUnits="userSpaceOnUse"><stop class="g8fj5qv-y"/><stop offset="1" class="n1yz-o_0e"/></linearGradient><linearGradient id="i1UpqEd" x1="19.043" x2="20.871" y1="27.433" y2="27.433" gradientUnits="userSpaceOnUse"><stop class="s9f5xlzkg"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="bi-ijln_l"/></linearGradient><linearGradient id="iEprgke" x1="12.952" x2="10.754" y1="27.433" y2="27.433" gradientUnits="userSpaceOnUse"><stop class="g8fj5qv-y"/><stop offset="1" class="n1yz-o_0e"/></linearGradient><linearGradient id="iS22jkd" x1="19.043" x2="20.871" y1="28.699" y2="28.699" gradientUnits="userSpaceOnUse"><stop class="s9f5xlzkg"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="bi-ijln_l"/></linearGradient><linearGradient id="iqcl5DO" x1="12.952" x2="10.754" y1="28.699" y2="28.699" gradientUnits="userSpaceOnUse"><stop class="g8fj5qv-y"/><stop offset="1" class="n1yz-o_0e"/></linearGradient><linearGradient id="iN6bN4c" x1="11.223" x2="10.582" y1="11.012" y2="11.012" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iKXfQqz" x1="21.821" x2="21.003" y1="9.641" y2="12.177" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iUmtXqe" x1="20.006" x2="12.369" y1="11.122" y2="12.26" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iymb1Gb" x1="10.575" x2="12.887" y1="13.818" y2="13.517" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iW1B7uc" x1="11.109" x2="14.011" y1="10.466" y2="5.311" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iBnq4xb" x1="15.106" x2="16.044" y1="11.781" y2="11.781" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="i3GXtOe" x1="16.908" x2="15.883" y1="12.104" y2="12.089" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="ion2jiY" x1="16.165" x2="16.165" y1="12.846" y2="12.273" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="i2OIwde" x1="16.096" x2="16.096" y1="12.888" y2="12.721" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="ikrfMkc" x1="14.933" x2="15.368" y1="14.461" y2="13.774" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iSSM2Ub" x1="18.927" x2="18.613" y1="10.105" y2="10.298" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iTL47Ie" x1="14.53" x2="14.216" y1="10.105" y2="10.298" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFAjpfe" x1="18.942" x2="18.522" y1="7.965" y2="7.107" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iXvCBwd" x1="13.638" x2="12.449" y1="7.837" y2="7.339" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="i3BbLsb" x1="16.099" x2="16.099" y1="9.455" y2="13.236" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient><filter id="iwe9HNc" width="27.98" height="21.09" x="2.024" y="4.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="iKN9ije" width="27.413" height="20.785" x="2.688" y="3.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".2"/></filter><filter id="iyxVibb" width="27.91" height="20.96" x="2.024" y="4.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="iTYaS0d" width="2.797" height="14.04" x="18.074" y="16.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="i84x23h" width="2.797" height="14.04" x="11.167" y="16.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="iiLfspb" width="2.1" height="3.39" x="20.967" y="23.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.752941 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="i6gpZ8b" width="2.1" height="3.29" x="8.97" y="23.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.611765 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="iIDyRCb" width="4.793" height="5.391" x="8.97" y="24.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.619608 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="i0oJ66b" width="4.793" height="5.591" x="18.474" y="24.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.435294 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.741176 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1666" result="effect2_innerShadow_4002_1666"/></filter><filter id="iLMd0xe" width="2.222" height=".3" x="18.893" y="25.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".05"/></filter><filter id="irSCm4c" width="2.222" height=".3" x="10.88" y="25.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".05"/></filter><filter id="ixd4kbc" width="2.222" height=".3" x="18.893" y="27.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".05"/></filter><filter id="irJdMAe" width="2.222" height=".3" x="10.88" y="27.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".05"/></filter><filter id="iyi8Zle" width="2.222" height=".3" x="18.893" y="28.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".05"/></filter><filter id="i7Wvmze" width="2.222" height=".3" x="10.88" y="28.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".05"/></filter><filter id="inm17ub" width="3.539" height="3.339" x="9.553" y="9.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="iCAwWJc" width="2.99" height="2.99" x="9.728" y="9.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".25"/></filter><filter id="iXWMFEc" width="3.589" height="3.589" x="19.066" y="8.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="ivqym1m" width="2.99" height="2.99" x="19.24" y="9.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".25"/></filter><filter id="icNGXge" width="10.373" height="12.177" x="10.812" y="5.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="iVAjakb" width="12.601" height="8.543" x="9.67" y="1.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="iR6NESc" width="3.26" height="4.181" x="14.101" y="9.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".375"/></filter><filter id="iQmdqyc" width="2.377" height="3.181" x="14.782" y="9.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".125"/></filter><filter id="iYdsPzc" width="2.979" height="1.873" x="17.152" y="7.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="iWjYvMe" width="2.98" height="1.873" x="12.005" y="7.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/></filter><filter id="i7Bxrme" width=".787" height=".696" x="17.415" y="9.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".05"/></filter><filter id="iD9tE3c" width=".891" height=".913" x="18.254" y="9.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".1"/></filter><filter id="iTL1Vpc" width=".986" height="1.04" x="13.813" y="9.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".1"/></filter><filter id="iLL9Pzd" width=".913" height=".704" x="13.058" y="9.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".05"/></filter><filter id="ik2Hhse" width="3.099" height="1.681" x="17.006" y="7.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".25"/></filter><filter id="i3a7s7c" width="3.177" height="1.738" x="11.787" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1666" stdDeviation=".25"/></filter><filter id="iRJKk6d" width="10.29" height="4.16" x="10.904" y="8.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1666"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1666" result="effect2_innerShadow_4002_1666"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-teacher-medium-light" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.anl-k5ncy {
  cx: 13.515px;
  cy: 9.955px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
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

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.b3k831b2t {
  d: path("M18.15 9.574a.892.892 0 0 1 .86 1.127h-1.723a.896.896 0 0 1 .864-1.127");
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bfca8sb6i {
  d: path("M21.674 23.035v-2.286c0-.388-.36-.699-.81-.699h-8.659c-1.041 0-1.871.73-1.871 1.622c0 .753.61 1.363 1.363 1.363z");
}

.bflrdnymp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 27.355H11.03");
}

.bi-ijln_l {
  stop-color: var(--svg-color--ab685c, #AB685C);
  stop-opacity: 0;
}

.bis1_sost {
  d: path("M18.946 10.349a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
}

.bku9lhrph {
  stop-color: var(--svg-color--b97a6f, #B97A6F);
}

.bv5s3qxke {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.358 9.302c.652 0 1.204.45 1.354 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.c1q9k0uxh {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.588 10.448l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.c5wh01b3e {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.085 9.763c.064.085-.07.188-.22.301c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
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

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d1gud5zvw {
  stop-color: var(--svg-color--f0c0a1, #F0C0A1);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e31yjdb7y {
  cx: 11.223px;
  cy: 10.733px;
  r: 1.669px;
}

.e3idwmvtr {
  d: path("M13.784 9.574a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.e4t4y8vlz {
  stop-color: var(--svg-color--c8926a, #C8926A);
}

.eb-j9_sfe {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m20.789 4.256l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853V6.07c0-.267-.214-.48-.429-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.747c.054.587.108 1.44.108 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.429-.213a8 8 0 0 0 .804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.054 2.36.533l.804.8c.214.267.483.427.804.587");
}

.eb5hv9bjw {
  stop-color: var(--svg-color--edc2a5, #EDC2A5);
  stop-opacity: 0;
}

.emj41xbgw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.238 4.444h26.213a.1.1 0 0 1 .1.1v19.584");
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
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

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g1nxbnbrj {
  stop-color: var(--svg-color--e4b8a5, #E4B8A5);
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.g8fj5qv-y {
  stop-color: var(--svg-color--d29c80, #D29C80);
}

.gcy2khpyp {
  stop-color: var(--svg-color--996759, #996759);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.gl5lc9gee {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.577 9.302c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gugba3b_v {
  stop-color: var(--svg-color--33141c, #33141C);
  stop-opacity: 0;
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.hi1zmhbhl {
  fill: var(--svg-color--000, #000);
  d: path("M14.295 10.466a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.745h.904a.5.5 0 0 0 .061-.235");
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.ie-4wgb6h {
  d: path("M22.067 23.158c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.ijj8khz4b {
  d: path("m10.87 10.12l.05.002s-.054-.853-.108-1.44c0-.267.108-.587.322-.747l.161-.16c.268-.213.376-.533.376-.853V6.07c0-.267.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.272.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003z");
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.ik7eqtbhg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 26.09H11.03");
}

.ipubjpcdo {
  d: path("m19.364 16.11l1.36 2.929c.09.19-.05.41-.26.41l-.964-.266c-.422-.105-.436.277-.276.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V16.11z");
}

.isen2z7va {
  cx: 11.223px;
  cy: 10.733px;
  r: 0.995px;
}

.ivbeehj3f {
  d: path("m20.789 4.256l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853V6.07c0-.267-.214-.48-.429-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.747c.054.587.108 1.44.108 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.429-.213a8 8 0 0 0 .804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.054 2.36.533l.804.8c.214.267.483.427.804.587");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j64dyhblj {
  d: path("m12.674 16.11l-1.36 2.929c-.09.19.05.41.26.41l.963-.266c.422-.105.437.277.277.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V16.11z");
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jyi--k5rl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 27.355h1.922");
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k4k_lggju {
  d: path("M20.854 9.05h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91V9.99c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34M15.394 11c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.klmuc4boz {
  d: path("m15.588 10.448l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.ksq4irbhi {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.428 30.05v-8.406h-2.094v8.406z");
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.l2vt5o7oc {
  d: path("M18.085 9.763c.064.085-.07.188-.22.301c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.l91o3_baa {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M19.69 8.013h-.002l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 1 0 .166 1.054c.398-.063.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lh6xtyqlu {
  cx: 20.735px;
  cy: 10.733px;
  r: 1.669px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lv2gkibab {
  d: path("M9.314 30.05V17.806a10.98 10.98 0 0 0-4.32 8.744v3.5z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.n1yz-o_0e {
  stop-color: var(--svg-color--d29c80, #D29C80);
  stop-opacity: 0;
}

.n5xd32bba {
  d: path("M11.167 21.543c0-.384.311-.696.695-.696h9.812v1.39h-9.812a.695.695 0 0 1-.695-.694");
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.nlx2y1elu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 28.62h1.922");
}

.ns76nm5tj {
  stop-color: var(--svg-color--794933, #794933);
}

.o3rhcmbix {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m12.197 8.014l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .154-.107c.1-.062.241-.14.42-.21a2.83 2.83 0 0 1 1.493-.159a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.68-.823");
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.omd21jb4q {
  stop-color: var(--svg-color--e8b8a6, #E8B8A6);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.oup8n6dpm {
  stop-color: var(--svg-color--d9a893, #D9A893);
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.p1axjj2zk {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.608 13.49c.393.205.862.322 1.362.322c.505 0 .969-.117 1.362-.322a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.24m-2.986-.28l2.945.253m-2.945-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.22.253m3.207.028l-.042-.028m.041.028l-.041-.028m.041.028a1.94 1.94 0 0 1-1.624.868c-.682 0-1.28-.347-1.624-.868m3.207-.028a1.9 1.9 0 0 1-1.583.846a1.89 1.89 0 0 1-1.583-.846m-.041.028l.041-.028m-.041.028l.041-.028");
}

.p5124lb-x {
  d: path("M9.97 23.15c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.q0ubbqbnc {
  d: path("M14.6 10.361c0-.288-.235-.48-.299-.538l-.288.279l.177.36z");
}

.qb0swfwwv {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.695 10.61l-.82 1.7c-.102.35.142.7.488.7h.737c.345 0 .59-.356.488-.7l-.498-1.7c-.107-.376-.284-.376-.395 0");
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

.qyaeouklz {
  stop-color: var(--svg-color--eebea0, #EEBEA0);
  stop-opacity: 0;
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rkuwb3brg {
  d: path("M22.694 30.05V17.806a10.98 10.98 0 0 1 4.32 8.744v3.5z");
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s9f5xlzkg {
  stop-color: var(--svg-color--ab685c, #AB685C);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.shh3pobzz {
  d: path("M29.394 25.04H2.644c-.34 0-.62-.28-.62-.62V4.67c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.sywgf9b1r {
  d: path("M16.024 15.55c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t28c_-b3o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 26.09h1.922");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.u5wc358og {
  cx: 13.515px;
  cy: 9.955px;
  rx: 0.389px;
  ry: 0.197px;
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.upbi0xbpg {
  stop-color: var(--svg-color--9f6e75, #9F6E75);
}

.uq8i4tbrr {
  d: path("M18.674 25.42a.81.81 0 0 0 .303.667a.8.8 0 0 0-.303.637c0 .267.116.503.303.636a.8.8 0 0 0-.303.637c0 .267.116.503.303.636a.84.84 0 0 0-.303.668c.01.42.32.75.685.75h2.935c.426 0 .773-.401.773-.894v-3.604c0-.493-.347-.893-.773-.893H19.45a.776.776 0 0 0-.777.76");
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
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

.va3mrqbij {
  d: path("M3.024 24.04V5.05h25.99v18.99z");
}

.va5jmqb6u {
  stop-color: var(--svg-color--bc8872, #BC8872);
}

.vcd2dsbig {
  d: path("M16.024 18.72c-1.14 0-2.06-.92-2.06-2.06V14.1c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.vh6yi_hgr {
  stop-color: var(--svg-color--e4b392, #E4B392);
}

.vpd4dcexx {
  stop-color: var(--svg-color--c88d87, #C88D87);
  stop-opacity: 0;
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.vvj3csbha {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.412 8.387c.327-.29 1.04-.594 1.926-.452");
}

.vvq7hbbzt {
  stop-color: var(--svg-color--edc2a5, #EDC2A5);
}

.vx5kmin4y {
  cx: 20.735px;
  cy: 10.733px;
  r: 0.995px;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w7nnggeov {
  d: path("M18.074 16.87h-4.11v13.18h4.11z");
}

.wexr6jtej {
  cx: 20.735px;
  cy: 10.733px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x_eyyzgvq {
  stop-color: var(--svg-color--daa594, #DAA594);
  stop-opacity: 0;
}

.x109hm4su {
  stop-color: var(--svg-color--a66d4a, #A66D4A);
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xqkpf3bhk {
  d: path("M10.334 21.93v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.xwft4kidb {
  d: path("M29.014 24.04H3.024V5.05l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.ycra_99jz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 28.62H11.03");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.yznyh2bbq {
  d: path("M13.363 25.42a.81.81 0 0 1-.302.667a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.636a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.636c.187.144.302.39.302.668c-.009.42-.32.75-.684.75H9.744c-.427 0-.774-.401-.774-.894v-3.604c0-.493.347-.893.774-.893h2.842c.475 0 .77.39.777.76");
}

.z4o42ufxk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.63 7.869c.43-.076 1.27-.054 1.85.398");
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.zd_xb-brh {
  fill-rule: evenodd;
  d: path("M12.428 30.05v-8.406h-2.094v8.406z");
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zldmt8bph {
  fill: var(--svg-color--000, #000);
  d: path("M17.64 10.466c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.745h-.904a.46.46 0 0 1-.061-.235");
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zw2whl-je {
  stop-color: var(--svg-color--c48b7e, #C48B7E);
}

</style>
