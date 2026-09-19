<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ijyIksg)" class="k1c_mut_k"/><path fill="url(#ibuGeUu)" class="k1c_mut_k"/><path fill="url(#ijCZLEh)" class="k1c_mut_k"/><path fill="url(#i56yprc)" class="t0otnpbph"/><path fill="url(#iuBS1xd)" class="t0otnpbph"/><path fill="url(#iC30wEi)" class="t0otnpbph"/><path fill="url(#iGyGIGd)" class="t0otnpbph"/><path fill="url(#ituBHQc)" class="bf2p8qrmv"/><path fill="url(#ivKVSld)" class="bf2p8qrmv"/><g filter="url(#iW3aXDb)"><path fill="url(#ioy71Pe)" class="jblyftbwx"/><path fill="url(#iPHVker)" class="jblyftbwx"/><path fill="url(#i5gpUBR)" class="jblyftbwx"/></g><path fill="url(#icSATGb)" class="d40xj0bgm"/><path fill="url(#iMLpnhc)" class="naiftn6rp"/><path fill="url(#ikShnhe)" class="v41un0bib"/><path fill="url(#iEXvk5d)" class="v41un0bib"/><path fill="url(#iJvGDfe)" class="ra65k8bed"/><path fill="url(#iWozGic)" class="ra65k8bed"/><path fill="url(#i10cFie)" class="h27ixmbfg"/><path fill="url(#iPbqgJe)" class="h27ixmbfg"/><path fill="url(#igpAcNc)" class="h27ixmbfg"/><path fill="url(#iQEufHe)" class="h27ixmbfg"/><path fill="url(#iZAZlie)" class="h27ixmbfg"/><path fill="url(#irQlFUc)" class="gyufogbgx"/><path fill="url(#i0mcP8c)" class="gyufogbgx"/><path fill="url(#igGhbAc)" class="gyufogbgx"/><path fill="url(#iejJ2sT)" class="gyufogbgx"/><path fill="url(#iQPsu3j)" class="e5m04rbea"/><path fill="url(#iZgDuCd)" class="e5m04rbea"/><path fill="url(#iqo2DkC)" class="e5m04rbea"/><path fill="url(#iGkyRhb)" class="a1-p60bye"/><path fill="url(#i3PIGpe)" class="a1-p60bye"/><g filter="url(#i6ihZKc)"><path fill="url(#icST2oc)" class="glo0w59tc"/><path fill="url(#ioGSu5T)" class="glo0w59tc"/><path fill="url(#i2wNand)" class="glo0w59tc"/><path fill="url(#ioZHf6b)" class="glo0w59tc"/><path fill="url(#iwynEdb)" class="glo0w59tc"/></g><rect fill="url(#i0VgLSd)" class="t-kdopbnn"/><rect fill="url(#iFGHu4b)" class="t-kdopbnn"/><g filter="url(#iFIoNce)"><path fill="url(#irkvOfe)" class="j7hpvactu"/></g><g filter="url(#il7b0me)"><path fill="url(#iDE1Zce)" class="qjv_8h7bk"/></g><g filter="url(#ih3aGie)"><path fill="url(#iVnAD0Y)" class="h_p6rff6l"/></g><g filter="url(#ijbfq9Z)"><path stroke="url(#i99AfJe)" class="h3ol1ibzg"/></g><g filter="url(#iaCpucb)"><path stroke="url(#iUDjP4b)" class="zlr3xkbbk"/></g><g filter="url(#ix5fGHe)"><path stroke="url(#i0mVjud)" class="x3g1wyv3w"/></g><g filter="url(#io6Hokd)"><circle fill="url(#iBTo5sc)" class="konybcbdn"/></g><g filter="url(#ieeFr5b)"><circle fill="url(#iW2KkHc)" class="vk82q2b3m"/></g><g filter="url(#iWAbmDe)"><circle fill="url(#io2dj3b)" class="m7o7gr92l"/><circle fill="url(#iUvykLP)" class="m7o7gr92l"/></g><g filter="url(#iNXc95d)"><circle class="hz098o06l"/><circle fill="url(#iC9mc8W)" class="awy1snbgz"/><circle fill="url(#ipKFWjI)" class="awy1snbgz"/></g><g filter="url(#ijBulqd)"><path fill="url(#imSQazb)" class="n809gdbti"/><path fill="url(#iKZZfPb)" class="n809gdbti"/><path fill="url(#iUfkoCc)" class="n809gdbti"/><path fill="url(#irnDnnP)" class="n809gdbti"/><path fill="url(#i4Ao9jo)" class="n809gdbti"/><path fill="url(#iwefFfe)" class="n809gdbti"/></g><g filter="url(#iYJCnCe)"><path fill="url(#i1FHeGG)" class="zr7x98bwj"/></g><g filter="url(#ikPhZMc)"><path class="yr85eqbyy"/><path fill="url(#iZQ8qbe)" class="bs_gq8bwa"/><path fill="url(#ihV6A2b)" class="bs_gq8bwa"/><path fill="url(#ibytJIT)" class="bs_gq8bwa"/><path fill="url(#irZCoNb)" class="bs_gq8bwa"/></g><g filter="url(#idmREJe)"><path class="vtqdcub6k"/></g><g filter="url(#itAl7tb)"><path class="atoh56cdv"/><path fill="url(#ikLTAIc)" class="qoc2zrbpp"/><path fill="url(#iaP0Kpc)" class="qoc2zrbpp"/><path fill="url(#iu9kDtQ)" class="qoc2zrbpp"/><path fill="url(#iGrzM8c)" class="qoc2zrbpp"/></g><path fill="url(#ibbVGse)" class="qoc2zrbpp"/><path stroke="url(#intvaCb)" class="y2kx8_bhu"/><g filter="url(#iXxHxnc)"><path class="o8yzr5b5u"/></g><g filter="url(#ilk5cPc)"><path class="dl90_5gru"/></g><path class="ve01eqguc"/><path fill="url(#i4oXOTd)" class="y-h82gpoj"/><path class="ukb_p3b4y"/><g filter="url(#icf2WSc)"><path class="k830cdbua"/><path fill="url(#iZOVh3b)" class="ane_3f1ea"/></g><g filter="url(#iRTiK6d)"><path fill="url(#iAvN6Sc)" class="fy2aj1bnh"/></g><path class="w9jds5b2s"/><path fill="url(#i3PBmge)" class="za0_bbclk"/><path class="g5cv45a_p"/><g filter="url(#iEdsWNd)"><path fill="url(#iLw1rIe)" class="u31dumwsi"/></g><g filter="url(#iyhTBDb)"><ellipse transform="rotate(-27.914 13.71 9.799)" class="r7j91yb0b"/><ellipse fill="url(#itWNOSj)" transform="rotate(-27.914 13.71 9.799)" class="s7p93ljqr"/></g><g filter="url(#i4CtgYb)"><path stroke="url(#ioSpJDh)" class="jo39wtb1u"/></g><g filter="url(#iCOpLqe)"><path stroke="url(#i4O2RPP)" class="g15yr_biw"/></g><g filter="url(#iog21cc)"><path stroke="url(#iwgz9ob)" class="e4aqoybzs"/></g><defs><linearGradient id="ijyIksg" x1="16.182" x2="16.182" y1="15.572" y2="30.457" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="ibuGeUu" x1="23.61" x2="21.078" y1="26.625" y2="26.657" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="ijCZLEh" x1="8.637" x2="10.853" y1="26.441" y2="26.441" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="iGyGIGd" x1="9.101" x2="8.666" y1="28.098" y2="28.098" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="ioy71Pe" x1="22.922" x2="17.047" y1="18.532" y2="18.532" gradientUnits="userSpaceOnUse"><stop class="l4epxabbu"/><stop offset="1" class="mjg0akbde"/></linearGradient><linearGradient id="icSATGb" x1="17.313" x2="16.016" y1="19.11" y2="20.032" gradientUnits="userSpaceOnUse"><stop offset=".048" class="iluzr5dja"/><stop offset="1" class="huftmtb3i"/></linearGradient><linearGradient id="i10cFie" x1="27.922" x2="24.547" y1="20.751" y2="20.376" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="iPbqgJe" x1="25.642" x2="25.642" y1="21.016" y2="20.501" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="iQEufHe" x1="25.642" x2="25.642" y1="16.871" y2="17.501" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="iZAZlie" x1="23.345" x2="24.087" y1="19.218" y2="19.218" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="irQlFUc" x1="23.516" x2="22.219" y1="19.002" y2="19.002" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="i0mcP8c" x1="23.766" x2="23.375" y1="19.282" y2="19.282" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="igGhbAc" x1="22.97" x2="22.97" y1="21.112" y2="20.45" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="iQPsu3j" x1="29.217" x2="27.597" y1="19.449" y2="19.449" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="iZgDuCd" x1="28.516" x2="28.516" y1="21.087" y2="20.563" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="i3PIGpe" x1="25.644" x2="25.672" y1="22.028" y2="22.384" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="icST2oc" x1="27.641" x2="23.613" y1="28.095" y2="28.095" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iFGHu4b" x1="25.654" x2="25.654" y1="20.845" y2="21.305" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="irkvOfe" x1="17.232" x2="17.232" y1="29.635" y2="22.959" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iDE1Zce" x1="13.225" x2="13.225" y1="29.635" y2="22.959" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iVnAD0Y" x1="21.219" x2="21.219" y1="29.635" y2="22.959" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="i99AfJe" x1="24.133" x2="25.842" y1="26.102" y2="26.102" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iUDjP4b" x1="24.055" x2="25.764" y1="27.407" y2="27.407" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="i0mVjud" x1="24.133" x2="25.842" y1="28.712" y2="28.712" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iW2KkHc" x1="11.415" x2="10.773" y1="10.856" y2="10.856" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="io2dj3b" x1="22.024" x2="21.205" y1="9.485" y2="12.024" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="imSQazb" x1="20.207" x2="12.563" y1="10.967" y2="12.107" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iKZZfPb" x1="10.766" x2="13.033" y1="13.666" y2="13.524" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="i1FHeGG" x1="17.127" x2="25.752" y1="7.587" y2="4.618" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="ikLTAIc" x1="15.302" x2="16.241" y1="11.627" y2="11.627" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iaP0Kpc" x1="17.106" x2="16.08" y1="11.95" y2="11.935" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iu9kDtQ" x1="16.362" x2="16.362" y1="12.693" y2="12.119" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="ibbVGse" x1="16.293" x2="16.293" y1="12.735" y2="12.567" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="intvaCb" x1="15.129" x2="15.564" y1="14.31" y2="13.621" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iAvN6Sc" x1="19.127" x2="18.813" y1="9.949" y2="10.142" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLw1rIe" x1="14.725" x2="14.411" y1="9.949" y2="10.142" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ioSpJDh" x1="19.142" x2="18.722" y1="7.807" y2="6.948" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="i4O2RPP" x1="13.832" x2="12.642" y1="7.679" y2="7.18" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iwgz9ob" x1="11.501" x2="11.501" y1="5.663" y2="7.822" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><radialGradient id="i56yprc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 5.105 30.032)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iuBS1xd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.953 30.032)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iC30wEi" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.953 23.083)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="ituBHQc" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 25.115 4.515)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="ivKVSld" cx="0" cy="0" r="1" gradientTransform="matrix(.55553 12.0481 -.71816 .03311 23.235 23.185)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iPHVker" cx="0" cy="0" r="1" gradientTransform="matrix(5.96102 5.60934 -10.1311 10.76628 16.196 14.844)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="w-er2h93j"/><stop offset=".937" class="nbg9ac2nn"/></radialGradient><radialGradient id="i5gpUBR" cx="0" cy="0" r="1" gradientTransform="matrix(-5.11642 0 0 -3.80242 16.195 16.422)" gradientUnits="userSpaceOnUse"><stop class="qbrho_b3d"/><stop offset="1" class="jxn3-wb7y"/></radialGradient><radialGradient id="iMLpnhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -2.76048 0 16.183 18.532)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="o5ej-52sf"/><stop offset="1" class="wyytu2b0o"/></radialGradient><radialGradient id="ikShnhe" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 0 0 1.78006 14.969 17.631)" gradientUnits="userSpaceOnUse"><stop class="fj2wmmhxh"/><stop offset="1" class="r02a4rbbd"/></radialGradient><radialGradient id="iEXvk5d" cx="0" cy="0" r="1" gradientTransform="matrix(.11168 4.2505 -2.51652 .06612 16.185 15.406)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="bqze5bbxb"/><stop offset="1" class="oj0nu7ckq"/></radialGradient><radialGradient id="iJvGDfe" cx="0" cy="0" r="1" gradientTransform="rotate(141.307 9.816 16.717)scale(2.01873 2.49606)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="k7qyxzbsl"/><stop offset="1" class="zdypug-8z"/></radialGradient><radialGradient id="iWozGic" cx="0" cy="0" r="1" gradientTransform="matrix(.75156 -.57402 .30002 .3928 27.695 23.44)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="igpAcNc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.88 17.425)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="iejJ2sT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.594 17.25)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="iqo2DkC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.36 17.5)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="iGkyRhb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 26.282 24.316)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="ioGSu5T" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.05 25.337)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="i2wNand" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.05 26.631)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ioZHf6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.05 27.881)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iwynEdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.05 29.233)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="i0VgLSd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.727 21.493)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="iBTo5sc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.744 10.578)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iUvykLP" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.31 10.312)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iC9mc8W" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.896 11.4)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="ipKFWjI" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.938 10.578)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iUfkoCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.65399 0 15.865 10.378)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="irnDnnP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.515 9.305)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="i4Ao9jo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.953 9.271)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iwefFfe" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 11.217 7.154)scale(2.92567 1.71902)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iZQ8qbe" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.09745 .29614 20.516 6.467)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ihV6A2b" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.872 4.706)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ibytJIT" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 16.167 1.968)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="irZCoNb" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.712 8.793)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iGrzM8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.495 12.186)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="i4oXOTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.348 9.895)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iZOVh3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 18.12 9.979)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3PBmge" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.98 9.895)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="itWNOSj" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.826 -1.684)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iW3aXDb" width="14.254" height="7.618" x="9.169" y="15.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.141176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1730"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.4 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1730" result="effect2_innerShadow_4002_1730"/></filter><filter id="i6ihZKc" width="4.468" height="5.556" x="23.613" y="24.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1730"/></filter><filter id="iFIoNce" width="1.192" height="6.826" x="15.599" y="23.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".125"/></filter><filter id="il7b0me" width="1.192" height="6.826" x="11.593" y="23.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".125"/></filter><filter id="ih3aGie" width="1.192" height="6.826" x="19.586" y="23.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".125"/></filter><filter id="ijbfq9Z" width="2.097" height=".3" x="23.983" y="25.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".05"/></filter><filter id="iaCpucb" width="2.097" height=".3" x="23.905" y="27.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".05"/></filter><filter id="ix5fGHe" width="2.097" height=".3" x="23.983" y="28.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".05"/></filter><filter id="io6Hokd" width="3.542" height="3.342" x="9.744" y="8.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1730"/></filter><filter id="ieeFr5b" width="2.992" height="2.992" x="9.919" y="9.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".25"/></filter><filter id="iWAbmDe" width="3.592" height="3.592" x="19.266" y="8.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1730"/></filter><filter id="iNXc95d" width="2.992" height="2.992" x="19.441" y="9.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".25"/></filter><filter id="ijBulqd" width="10.383" height="12.189" x="11.004" y="4.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1730"/></filter><filter id="iYJCnCe" width="6.25" height="5.07" x="15.337" y="3.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".5"/></filter><filter id="ikPhZMc" width="12.614" height="8.551" x="9.86" y="1.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1730"/></filter><filter id="idmREJe" width="3.262" height="4.184" x="14.297" y="9.423" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".375"/></filter><filter id="itAl7tb" width="2.379" height="3.184" x="14.978" y="9.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".125"/></filter><filter id="iXxHxnc" width="2.982" height="1.874" x="17.35" y="6.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1730"/></filter><filter id="ilk5cPc" width="2.982" height="1.874" x="12.198" y="6.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1730"/></filter><filter id="icf2WSc" width=".787" height=".697" x="17.613" y="9.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".05"/></filter><filter id="iRTiK6d" width=".892" height=".914" x="18.454" y="9.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".1"/></filter><filter id="iEdsWNd" width=".987" height="1.041" x="14.008" y="9.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".1"/></filter><filter id="iyhTBDb" width=".914" height=".705" x="13.253" y="9.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".05"/></filter><filter id="i4CtgYb" width="2.701" height="1.281" x="17.404" y="7.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".15"/></filter><filter id="iCOpLqe" width="2.779" height="1.339" x="12.18" y="7.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".15"/></filter><filter id="iog21cc" width="1.008" height="2.271" x="10.996" y="5.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1730" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-judge-dark" /></template>
<style>
.a1-p60bye {
  d: path("M24.889 21.103v6.426h1.51v-6.426z");
}

.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.ane_3f1ea {
  d: path("M18.284 9.606c.064.086-.069.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.atoh56cdv {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.785 10.292l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.awy1snbgz {
  cx: 20.937px;
  cy: 10.578px;
  r: 0.996px;
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.bf2p8qrmv {
  d: path("M23.408 30.032v-11.8c2.355 2.01 3.848 4.986 3.848 8.31v2.49a1 1 0 0 1-1 1z");
}

.bqze5bbxb {
  stop-color: var(--svg-color--1b0a0c, #1B0A0C);
  stop-opacity: 0;
}

.bs_gq8bwa {
  d: path("m20.99 4.094l.43.213c.752.374 1.181 1.228 1.02 2.135l-.59 3.043c-.053.315-.26.526-.573.534h-.018s.054-.907.107-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.747c.054.588.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.213a8 8 0 0 0 .805-.588l.967-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.054 2.363.534l.805.8c.215.267.483.427.805.588");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d40xj0bgm {
  d: path("m17.112 19.793l-.655.585a.416.416 0 0 1-.554 0l-.654-.585a3.47 3.47 0 0 1-1.149-2.568v-3.113a2.085 2.085 0 0 1 2.086-2.065c1.148 0 2.075.927 2.075 2.075v3.113a3.5 3.5 0 0 1-1.149 2.558");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.dl90_5gru {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.39 7.855l.002-.001l.001-.002l.005-.003l.012-.01a2 2 0 0 1 .155-.107c.1-.063.241-.14.42-.211c.36-.142.872-.257 1.494-.159a.534.534 0 0 1-.167 1.056a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.309.166a.534.534 0 0 1-.68-.825");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.e4aqoybzs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.63 5.762v.898c-.008.149-.07.482-.259.623");
}

.e5m04rbea {
  d: path("M28.714 16.987H28.1a.505.505 0 0 0-.503.504v3.022c0 .272.221.503.503.503h.613a.505.505 0 0 0 .504-.503V17.49a.51.51 0 0 0-.503-.504");
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fj2wmmhxh {
  stop-color: var(--svg-color--483232, #483232);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fy2aj1bnh {
  d: path("M19.146 10.193a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g15yr_biw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.605 8.23c.327-.29 1.042-.595 1.929-.454");
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g5cv45a_p {
  fill: var(--svg-color--000, #000);
  d: path("M14.49 10.31a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .061-.235");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.glo0w59tc {
  d: path("M23.613 25.358a.73.73 0 0 1 .726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.gyufogbgx {
  d: path("M23.188 16.987h-.613a.505.505 0 0 0-.504.504v3.022c0 .272.222.503.504.503h.613a.505.505 0 0 0 .504-.503V17.49a.51.51 0 0 0-.504-.504");
}

.h_p6rff6l {
  d: path("M19.836 23.575h.692v6.326h-.692z");
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.h27ixmbfg {
  d: path("M27.093 16.987h-2.901a.505.505 0 0 0-.504.504v3.022c0 .272.222.503.504.503h2.9a.505.505 0 0 0 .505-.503V17.49a.51.51 0 0 0-.504-.504");
}

.h3ol1ibzg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.133 26.024h1.797");
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.huftmtb3i {
  stop-color: var(--svg-color--ada3a2, #ADA3A2);
}

.hz098o06l {
  cx: 20.937px;
  cy: 10.578px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.iluzr5dja {
  stop-color: var(--svg-color--978b8d, #978B8D);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.j7hpvactu {
  d: path("M15.849 23.575h.692v6.326h-.692z");
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jblyftbwx {
  d: path("M9.256 17.9c1.974-1.646 4.386-2.423 6.94-2.423c2.553 0 4.965.777 6.939 2.423a.24.24 0 0 1 .061.296c-1.354 2.69-3.772 4.65-7 4.65c-3.23 0-5.647-1.96-7.001-4.65a.24.24 0 0 1 .06-.296");
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.jo39wtb1u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.83 7.71c.43-.075 1.27-.054 1.85.398");
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jxn3-wb7y {
  stop-color: var(--svg-color--3b2321, #3B2321);
  stop-opacity: 0;
}

.k1c_mut_k {
  d: path("M16.185 15.573c-6.114 0-11.08 4.906-11.08 10.969v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.063-4.955-10.97-11.07-10.97");
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.k830cdbua {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.284 9.606c.064.086-.069.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.konybcbdn {
  cx: 11.415px;
  cy: 10.578px;
  r: 1.671px;
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.l4epxabbu {
  stop-color: var(--svg-color--564d5b, #564D5B);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m7o7gr92l {
  cx: 20.937px;
  cy: 10.578px;
  r: 1.671px;
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mjg0akbde {
  stop-color: var(--svg-color--433945, #433945);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n809gdbti {
  d: path("m11.062 9.964l.05.002s-.054-.854-.108-1.441c0-.267.107-.588.322-.748l.161-.16c.269-.214.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.918.427c.215.053.43.267.43.534v.854c0 .32.161.64.376.854c.502.352.471.546.43.96a46 46 0 0 0-.108 1.442h.018l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.714 0-3.053-1.234-3.213-3.006z");
}

.naiftn6rp {
  d: path("m16.976 19.915l.136-.122a3.5 3.5 0 0 0 1.148-2.549V15.28h-4.15l-.005 1.912c0 .052.003.147 0 .2c.045.916.46 1.784 1.144 2.401l.16.143l.666-1.009a.13.13 0 0 1 .22 0z");
}

.nbg9ac2nn {
  stop-color: var(--svg-color--59545e, #59545E);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o5ej-52sf {
  stop-color: var(--svg-color--d7cace, #D7CACE);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o8yzr5b5u {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m19.89 7.855l-.001-.001l-.002-.002l-.005-.003l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.063-.24-.14-.42-.211a2.84 2.84 0 0 0-1.494-.159a.534.534 0 1 0 .167 1.056c.398-.063.717.01.935.096a1.5 1.5 0 0 1 .308.166a.534.534 0 0 0 .68-.825");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.oj0nu7ckq {
  stop-color: var(--svg-color--1b0a0c, #1B0A0C);
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qbrho_b3d {
  stop-color: var(--svg-color--3b2321, #3B2321);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qjv_8h7bk {
  d: path("M11.843 23.575h.692v6.326h-.692z");
}

.qoc2zrbpp {
  d: path("m15.785 10.292l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.r02a4rbbd {
  stop-color: var(--svg-color--381f21, #381F21);
}

.r7j91yb0b {
  cx: 13.709px;
  cy: 9.799px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.ra65k8bed {
  d: path("M26.969 22.965c.531 0 .959.427.959.959v2.188H26.02v-2.188a.94.94 0 0 1 .948-.96");
}

.s7p93ljqr {
  cx: 13.709px;
  cy: 9.799px;
  rx: 0.39px;
  ry: 0.197px;
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.t-kdopbnn {
  width: 2.773px;
  height: 1.082px;
  x: 24.267px;
  y: 21.016px;
  rx: 0.541px;
}

.t0otnpbph {
  d: path("M8.953 30.032v-11.8c-2.356 2.01-3.848 4.986-3.848 8.31v3.49z");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.u31dumwsi {
  d: path("M14.795 10.206c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ukb_p3b4y {
  fill: var(--svg-color--000, #000);
  d: path("M17.839 10.31a.51.51 0 0 1 .511-.51a.51.51 0 0 1 .455.746h-.906a.46.46 0 0 1-.06-.235");
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.v41un0bib {
  d: path("M16.185 18.766a2.07 2.07 0 0 1-2.075-2.075v-2.579a2.07 2.07 0 0 1 2.075-2.065c1.149 0 2.076.927 2.076 2.075v2.579a2.083 2.083 0 0 1-2.076 2.065");
}

.ve01eqguc {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.557 9.146c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.341h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vk82q2b3m {
  cx: 11.415px;
  cy: 10.578px;
  r: 0.996px;
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vtqdcub6k {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.891 10.455l-.82 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.378-.284-.378-.396 0");
}

.w-er2h93j {
  stop-color: var(--svg-color--59545e, #59545E);
  stop-opacity: 0;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.w9jds5b2s {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.772 9.146c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wyytu2b0o {
  stop-color: var(--svg-color--897576, #897576);
}

.x3g1wyv3w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.133 28.634h1.797");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y-h82gpoj {
  d: path("M18.35 9.417a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.y2kx8_bhu {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.804 13.337c.393.206.863.323 1.363.323c.505 0 .97-.117 1.363-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .021.242m-2.99-.282l2.948.254m-2.947-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.222.254m3.211.028l-.041-.028m.041.028l-.041-.028m.041.028a1.95 1.95 0 0 1-1.626.869a1.95 1.95 0 0 1-1.626-.87m3.21-.027c-.335.508-.919.847-1.584.847s-1.25-.34-1.585-.847m-.04.028l.04-.028m-.04.028h-.001l.041-.028");
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yr85eqbyy {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m20.99 4.094l.43.213c.752.374 1.181 1.228 1.02 2.135l-.59 3.043c-.053.315-.26.526-.573.534h-.018s.054-.907.107-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.747c.054.588.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.213a8 8 0 0 0 .805-.588l.967-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.054 2.363.534l.805.8c.215.267.483.427.805.588");
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.za0_bbclk {
  d: path("M13.979 9.417a.893.893 0 0 0-.86 1.13h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.894");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zlr3xkbbk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.055 27.329h1.797");
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zr7x98bwj {
  d: path("m20.134 4.948l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
