<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iCpjimd)" class="qo6juab9h"/><path fill="url(#i9kE1ve)" class="qo6juab9h"/><path fill="url(#ig6IAzb)" class="qo6juab9h"/><path fill="url(#iTxIY0d)" class="kudttigsm"/><path fill="url(#i1xN6Lc)" class="kudttigsm"/><path fill="url(#ivk8RBb)" class="kudttigsm"/><path fill="url(#iiVj5xE)" class="kudttigsm"/><path fill="url(#iFEa8Ab)" class="kmyr74hbl"/><path fill="url(#iOXMMtb)" class="kmyr74hbl"/><g filter="url(#iethmCc)"><path fill="url(#iRIO9nd)" class="ee-beobwc"/><path fill="url(#iq8O1je)" class="ee-beobwc"/><path fill="url(#i8BCVEe)" class="ee-beobwc"/></g><path fill="url(#icHmQgy)" class="v718znckj"/><path fill="url(#ivpQBUb)" class="rrq1e5bez"/><path fill="url(#i0icwEc)" class="ar-s22brj"/><path fill="url(#iVDG01b)" class="ar-s22brj"/><path fill="url(#iKgenPc)" class="r_oyacbqw"/><path fill="url(#iCZMBmc)" class="r_oyacbqw"/><path fill="url(#iQeLfNg)" class="uva-dwpes"/><path fill="url(#i0W1ZGt)" class="uva-dwpes"/><path fill="url(#iRxSboc)" class="uva-dwpes"/><path fill="url(#iwZF3wl)" class="uva-dwpes"/><path fill="url(#iYI7cub)" class="uva-dwpes"/><path fill="url(#iZBNzVg)" class="r7-8oabxi"/><path fill="url(#ieawxRd)" class="r7-8oabxi"/><path fill="url(#i10I1ke)" class="r7-8oabxi"/><path fill="url(#iy2Npfc)" class="r7-8oabxi"/><path fill="url(#ietmK5b)" class="fgo6nzkpx"/><path fill="url(#i4ta13W)" class="fgo6nzkpx"/><path fill="url(#iBThopd)" class="fgo6nzkpx"/><path fill="url(#iFJoKAh)" class="e9r_yunao"/><path fill="url(#iLVxXzb)" class="e9r_yunao"/><g filter="url(#iHGRiub)"><path fill="url(#i95ndge)" class="ddqdjpb9d"/><path fill="url(#ijy0UNW)" class="ddqdjpb9d"/></g><rect fill="url(#i7Q3Fcc)" class="l6y6j1bti"/><rect fill="url(#i4C2rMe)" class="l6y6j1bti"/><g filter="url(#iRV1XAI)"><path fill="url(#iFKinfb)" class="ypj2-ccrf"/></g><g filter="url(#ifiEeDe)"><path fill="url(#ipQ0DQb)" class="frbtzdbff"/></g><g filter="url(#iXbbElb)"><path fill="url(#irZT0vc)" class="zh8xj40cc"/></g><g filter="url(#ir8mmmV)"><path stroke="url(#ibQaGgP)" class="ge1aofbxa"/></g><g filter="url(#irOtwse)"><path stroke="url(#iK4g35c)" class="bj5c0pbve"/></g><g filter="url(#iT1ilbd)"><path stroke="url(#ik60qMb)" class="pmhhlvwfw"/></g><circle fill="url(#iayoSPb)" class="mws39tffk"/><g filter="url(#i4uaVFb)"><circle fill="url(#iEeLTMb)" class="co7bdabez"/></g><g filter="url(#iARYNdd)"><circle fill="url(#i89r16d)" class="w325k2k4x"/><circle fill="url(#ixaWaqb)" class="w325k2k4x"/></g><g filter="url(#i7tCLOb)"><circle class="courtx0_q"/><circle fill="url(#iEr0rVd)" class="u-5jc1bbs"/><circle fill="url(#ieDjOZc)" class="u-5jc1bbs"/></g><path fill="url(#ibGUaDb)" class="yz57tkbzc"/><path fill="url(#iryyp8b)" class="yz57tkbzc"/><path fill="url(#i9ZBb3c)" class="yz57tkbzc"/><path fill="url(#iRL8vtc)" class="yz57tkbzc"/><path fill="url(#iqtbFue)" class="yz57tkbzc"/><path fill="url(#ie4tXze)" class="yz57tkbzc"/><g filter="url(#ip1wTqd)"><path class="n53ou2bxa"/><path fill="url(#iNg9TVc)" class="khxr7y7do"/><path fill="url(#iCf2Ujb)" class="khxr7y7do"/><path fill="url(#ieUwU1p)" class="khxr7y7do"/><path fill="url(#iCCdv1c)" class="khxr7y7do"/><path fill="url(#ipa6k4d)" class="khxr7y7do"/><path fill="url(#i8JtHvb)" class="khxr7y7do"/></g><path fill="url(#iQNoR7G)" class="khxr7y7do"/><path fill="url(#iMX5Kvc)" class="khxr7y7do"/><path fill="url(#ilbMWtd)" class="khxr7y7do"/><g filter="url(#ixqnxtt)"><path class="cenpdybqz"/></g><g filter="url(#i4bwQ7s)"><path class="gvm55eb0q"/><path fill="url(#iXTzsQa)" class="x255252kl"/><path fill="url(#i4fXkBe)" class="x255252kl"/><path fill="url(#iL3gfJD)" class="x255252kl"/></g><path fill="url(#is5Rkie)" class="x255252kl"/><g filter="url(#iRUA6De)"><path stroke="url(#iNlWtIe)" class="uerouv67z"/></g><path class="q8ny10bzr"/><path class="en9ze8b9b"/><path fill="url(#ildr63m)" class="itg75r1-w"/><path class="ux5vxebfi"/><g filter="url(#itWI2se)"><path class="fkgdhzacu"/><path fill="url(#iX6KwEc)" class="slex5bcbq"/></g><g filter="url(#ijdT95b)"><path fill="url(#ihxuMge)" class="j9_cebbrd"/></g><path class="a9ogefabk"/><path fill="url(#ix1eSwb)" class="zuwocg1tc"/><path class="gdl2obbnn"/><g filter="url(#iUxyKpe)"><path fill="url(#imVQXzb)" class="dx976ibou"/></g><g filter="url(#iuUHdBb)"><ellipse transform="rotate(-27.914 13.71 9.919)" class="ds4r60bbg"/><ellipse fill="url(#iFYRBFy)" transform="rotate(-27.914 13.71 9.919)" class="t-tjl2gfd"/></g><g filter="url(#i82pQpd)"><path fill="url(#iIagzne)" clip-rule="evenodd" class="oamypkk6h"/></g><g filter="url(#ib652we)"><path class="vt9u3mbdx"/></g><g filter="url(#iWHQykc)"><path fill="url(#ibkeywe)" clip-rule="evenodd" class="hj5kz9t0e"/></g><g filter="url(#iuL7WXd)"><path class="pvho5mb2d"/></g><defs><radialGradient id="iTxIY0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 5.105 29.906)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="i1xN6Lc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.953 29.906)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="ivk8RBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.953 22.957)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="iFEa8Ab" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 25.063 4.452)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iOXMMtb" cx="0" cy="0" r="1" gradientTransform="matrix(.55553 12.0481 -.71816 .03311 23.235 23.06)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iq8O1je" cx="0" cy="0" r="1" gradientTransform="matrix(5.96102 5.60934 -10.1311 10.76628 16.195 14.718)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="w-er2h93j"/><stop offset=".937" class="nbg9ac2nn"/></radialGradient><radialGradient id="i8BCVEe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.11642 0 0 -3.80242 16.195 16.297)" gradientUnits="userSpaceOnUse"><stop class="qbrho_b3d"/><stop offset="1" class="jxn3-wb7y"/></radialGradient><radialGradient id="ivpQBUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -2.76048 0 16.183 18.406)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="o5ej-52sf"/><stop offset="1" class="wyytu2b0o"/></radialGradient><radialGradient id="i0icwEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.82081 -1.38289 0 16.956 16.369)" gradientUnits="userSpaceOnUse"><stop class="zr1c6qbkd"/><stop offset="1" class="wsbgy6b7o"/><stop offset="1" class="zmx0ewbtm"/></radialGradient><radialGradient id="iVDG01b" cx="0" cy="0" r="1" gradientTransform="matrix(.11168 4.2505 -2.51652 .06612 16.185 15.28)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="hkmgjzqum"/><stop offset="1" class="wy0gh7bzd"/></radialGradient><radialGradient id="iKgenPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.157 .99606 -1.23158 -1.43058 27.928 23.503)" gradientUnits="userSpaceOnUse"><stop class="nv7ilcg1p"/><stop offset="1" class="mdj8rj_9y"/></radialGradient><radialGradient id="iCZMBmc" cx="0" cy="0" r="1" gradientTransform="matrix(.5 -.80469 .9445 .58687 26.32 24.633)" gradientUnits="userSpaceOnUse"><stop class="rloy1eb5h"/><stop offset="1" class="msvvb9k2w"/></radialGradient><radialGradient id="iRxSboc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.88 17.299)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="iy2Npfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.594 17.125)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="iBThopd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.36 17.375)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="iFJoKAh" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 26.282 24.19)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="ijy0UNW" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.93 24.5)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="i7Q3Fcc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.727 21.367)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="iayoSPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.744 10.697)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="ixaWaqb" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.31 10.432)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iEr0rVd" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.896 11.52)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="ieDjOZc" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.937 10.697)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="i9ZBb3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.20766 -9.37165 0 16.658 9.105)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="iRL8vtc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.515 9.425)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iqtbFue" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.953 9.391)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="ie4tXze" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.9688 -13.5084 0 16.196 5.688)" gradientUnits="userSpaceOnUse"><stop offset=".922" class="ckn8czb4k"/><stop offset=".979" class="gzp3-0bjb"/></radialGradient><radialGradient id="iNg9TVc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43986 4.43352 -7.5396 -5.84979 19.863 2.977)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="ieUwU1p" cx="0" cy="0" r="1" gradientTransform="rotate(-95.29 9.23 -1.955)scale(2.00292 .98368)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iCCdv1c" cx="0" cy="0" r="1" gradientTransform="matrix(.85996 -1.96834 1.60534 .70136 20.398 8.958)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="ipa6k4d" cx="0" cy="0" r="1" gradientTransform="matrix(.99373 1.23303 -1.08867 .87739 15.391 2.088)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="i8JtHvb" cx="0" cy="0" r="1" gradientTransform="matrix(1.45237 -3.03851 1.04984 .50181 20.36 6.474)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iQNoR7G" cx="0" cy="0" r="1" gradientTransform="matrix(.26142 1.01586 -1.67013 .42978 16.862 2.088)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iMX5Kvc" cx="0" cy="0" r="1" gradientTransform="matrix(1.108 1.60044 -3.3305 2.30573 11.78 3.35)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="ilbMWtd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.21429 3.2501 -4.0668 -9.02713 17.32 6.33)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iNlWtIe" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 16.082 14.713)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="ildr63m" cx="0" cy="0" r="1" gradientTransform="rotate(90 4 14.348)scale(.90401 1.06968)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iX6KwEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 18.12 10.099)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ix1eSwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90406 -1.06973 0 13.98 10.349)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iFYRBFy" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.885 -1.624)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIagzne" cx="0" cy="0" r="1" gradientTransform="matrix(.19698 -.81253 1.78257 .43214 18.62 8.496)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="ibkeywe" cx="0" cy="0" r="1" gradientTransform="matrix(-.19698 -.81253 1.78256 -.43214 13.713 8.496)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><linearGradient id="iCpjimd" x1="16.182" x2="16.182" y1="15.447" y2="30.331" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="i9kE1ve" x1="23.61" x2="21.078" y1="26.5" y2="26.531" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="ig6IAzb" x1="8.637" x2="10.853" y1="26.316" y2="26.316" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="iiVj5xE" x1="9.101" x2="8.666" y1="27.973" y2="27.973" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iRIO9nd" x1="22.922" x2="17.047" y1="18.406" y2="18.406" gradientUnits="userSpaceOnUse"><stop class="l4epxabbu"/><stop offset="1" class="mjg0akbde"/></linearGradient><linearGradient id="icHmQgy" x1="17.313" x2="16.016" y1="18.984" y2="19.906" gradientUnits="userSpaceOnUse"><stop offset=".048" class="iluzr5dja"/><stop offset="1" class="huftmtb3i"/></linearGradient><linearGradient id="iQeLfNg" x1="27.922" x2="24.547" y1="20.625" y2="20.25" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="i0W1ZGt" x1="25.642" x2="25.642" y1="20.891" y2="20.375" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="iwZF3wl" x1="25.642" x2="25.642" y1="16.745" y2="17.375" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="iYI7cub" x1="23.345" x2="24.087" y1="19.092" y2="19.092" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="iZBNzVg" x1="23.516" x2="22.219" y1="18.876" y2="18.876" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="ieawxRd" x1="23.766" x2="23.375" y1="19.156" y2="19.156" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="i10I1ke" x1="22.97" x2="22.97" y1="20.987" y2="20.324" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="ietmK5b" x1="29.217" x2="27.597" y1="19.323" y2="19.323" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="i4ta13W" x1="28.516" x2="28.516" y1="20.961" y2="20.437" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="iLVxXzb" x1="25.644" x2="25.672" y1="21.902" y2="22.258" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="i95ndge" x1="27.641" x2="23.613" y1="27.969" y2="27.969" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="i4C2rMe" x1="25.654" x2="25.654" y1="20.719" y2="21.18" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iFKinfb" x1="17.232" x2="17.232" y1="29.509" y2="22.833" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ipQ0DQb" x1="13.225" x2="13.225" y1="29.509" y2="22.833" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="irZT0vc" x1="21.219" x2="21.219" y1="29.509" y2="22.833" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ibQaGgP" x1="24.133" x2="25.842" y1="25.977" y2="25.977" gradientUnits="userSpaceOnUse"><stop class="ncgvd-jsx"/><stop offset="1" class="q2ji4cbak"/></linearGradient><linearGradient id="iK4g35c" x1="24.055" x2="25.764" y1="27.281" y2="27.281" gradientUnits="userSpaceOnUse"><stop class="ncgvd-jsx"/><stop offset="1" class="q2ji4cbak"/></linearGradient><linearGradient id="ik60qMb" x1="24.133" x2="25.842" y1="28.586" y2="28.586" gradientUnits="userSpaceOnUse"><stop class="ncgvd-jsx"/><stop offset="1" class="q2ji4cbak"/></linearGradient><linearGradient id="iEeLTMb" x1="11.415" x2="10.773" y1="10.976" y2="10.976" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="i89r16d" x1="22.024" x2="21.205" y1="9.605" y2="12.143" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="ibGUaDb" x1="20.207" x2="12.563" y1="11.087" y2="12.226" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iryyp8b" x1="10.766" x2="13.081" y1="13.786" y2="13.484" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iCf2Ujb" x1="11.301" x2="14.206" y1="10.43" y2="5.27" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iXTzsQa" x1="15.302" x2="16.241" y1="11.747" y2="11.747" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="i4fXkBe" x1="17.106" x2="16.08" y1="12.07" y2="12.055" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iL3gfJD" x1="16.362" x2="16.362" y1="12.813" y2="12.239" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="is5Rkie" x1="16.293" x2="16.293" y1="12.855" y2="12.687" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="ihxuMge" x1="19.127" x2="18.813" y1="10.069" y2="10.262" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imVQXzb" x1="14.725" x2="14.411" y1="10.069" y2="10.262" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><filter id="iethmCc" width="14.254" height="7.618" x="9.169" y="15.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.141176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1727"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.4 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1727" result="effect2_innerShadow_4002_1727"/></filter><filter id="iHGRiub" width="4.468" height="5.556" x="23.613" y="24.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.478431 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1727"/></filter><filter id="iRV1XAI" width="1.192" height="6.826" x="15.599" y="23.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".125"/></filter><filter id="ifiEeDe" width="1.192" height="6.826" x="11.593" y="23.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".125"/></filter><filter id="iXbbElb" width="1.192" height="6.826" x="19.586" y="23.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".125"/></filter><filter id="ir8mmmV" width="2.097" height=".3" x="23.983" y="25.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".05"/></filter><filter id="irOtwse" width="2.097" height=".3" x="23.905" y="27.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".05"/></filter><filter id="iT1ilbd" width="2.097" height=".3" x="23.983" y="28.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".05"/></filter><filter id="i4uaVFb" width="2.992" height="2.992" x="9.919" y="9.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".25"/></filter><filter id="iARYNdd" width="3.592" height="3.592" x="19.266" y="8.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1727"/></filter><filter id="i7tCLOb" width="2.992" height="2.992" x="19.441" y="9.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".25"/></filter><filter id="ip1wTqd" width="12.614" height="8.301" x="9.86" y="1.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1727"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1727" result="effect2_innerShadow_4002_1727"/></filter><filter id="ixqnxtt" width="3.262" height="4.184" x="14.297" y="9.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".375"/></filter><filter id="i4bwQ7s" width="2.379" height="3.184" x="14.978" y="9.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".125"/></filter><filter id="iRUA6De" width="3.621" height="1.474" x="14.357" y="13.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".05"/></filter><filter id="itWI2se" width=".787" height=".697" x="17.613" y="9.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".05"/></filter><filter id="ijdT95b" width=".892" height=".914" x="18.454" y="9.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".1"/></filter><filter id="iUxyKpe" width=".987" height="1.041" x="14.008" y="9.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".1"/></filter><filter id="iuUHdBb" width=".914" height=".705" x="13.252" y="9.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".05"/></filter><filter id="i82pQpd" width="2.604" height="1.648" x="17.432" y="7.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1727"/></filter><filter id="ib652we" width="2.709" height="1.502" x="17.379" y="7.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".2"/></filter><filter id="iWHQykc" width="2.604" height="1.648" x="12.298" y="7.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1727"/></filter><filter id="iuL7WXd" width="2.709" height="1.502" x="12.246" y="7.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1727" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-judge" /></template>
<style>
.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.a9ogefabk {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.772 9.265c-.654 0-1.206.451-1.356 1.06a.274.274 0 0 0 .268.341h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.129");
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.ar-s22brj {
  d: path("M16.185 18.64a2.07 2.07 0 0 1-2.075-2.075v-2.579a2.07 2.07 0 0 1 2.075-2.065c1.149 0 2.076.927 2.076 2.075v2.58a2.083 2.083 0 0 1-2.076 2.064");
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.bj5c0pbve {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.055 27.203h1.797");
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.cenpdybqz {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.891 10.575l-.82 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.378-.284-.378-.396 0");
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckn8czb4k {
  stop-color: var(--svg-color--f98e4d, #F98E4D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co7bdabez {
  cx: 11.415px;
  cy: 10.697px;
  r: 0.996px;
}

.courtx0_q {
  cx: 20.937px;
  cy: 10.697px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.ddqdjpb9d {
  d: path("M23.613 25.232c0-.401.325-.732.726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.ds4r60bbg {
  cx: 13.709px;
  cy: 9.919px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.dx976ibou {
  d: path("M14.795 10.326c0-.29-.235-.481-.299-.54l-.288.28l.178.361z");
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.e9r_yunao {
  d: path("M24.889 20.977v6.427h1.51v-6.427z");
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ee-beobwc {
  d: path("M9.256 17.775c1.974-1.647 4.386-2.423 6.94-2.423c2.553 0 4.965.776 6.939 2.422a.24.24 0 0 1 .061.296c-1.354 2.69-3.772 4.65-7 4.65c-3.23 0-5.647-1.96-7.001-4.65a.24.24 0 0 1 .06-.296");
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.en9ze8b9b {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.557 9.265c.654 0 1.206.451 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.fgo6nzkpx {
  d: path("M28.714 16.861H28.1a.505.505 0 0 0-.503.504v3.022c0 .272.221.504.503.504h.613a.505.505 0 0 0 .504-.504v-3.022a.51.51 0 0 0-.503-.504");
}

.fkgdhzacu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.284 9.726c.064.085-.07.189-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.05");
}

.frbtzdbff {
  d: path("M11.843 23.45h.692v6.326h-.692z");
}

.ft5dv1b6b {
  fill: none;
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.gdl2obbnn {
  fill: var(--svg-color--000, #000);
  d: path("M14.49 10.43a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.236");
}

.ge1aofbxa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.133 25.898h1.797");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gvm55eb0q {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.784 10.412l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.gzp3-0bjb {
  stop-color: var(--svg-color--f98e4d, #F98E4D);
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hj5kz9t0e {
  fill-rule: evenodd;
  d: path("M14.386 8.49c-.72-.068-1.183.214-1.295.317a.473.473 0 1 1-.64-.695c.306-.283 1.032-.656 2.023-.564a.473.473 0 0 1-.088.942");
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hkmgjzqum {
  stop-color: var(--svg-color--835005, #835005);
  stop-opacity: 0;
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.huftmtb3i {
  stop-color: var(--svg-color--ada3a2, #ADA3A2);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
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

.itg75r1-w {
  d: path("M18.35 9.537a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.j9_cebbrd {
  d: path("M19.146 10.313a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jxn3-wb7y {
  stop-color: var(--svg-color--3b2321, #3B2321);
  stop-opacity: 0;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.khxr7y7do {
  d: path("m20.99 4.213l.43.214c.752.374 1.181 1.228 1.02 2.135l-.59 3.043c-.053.314-.26.526-.573.534c.036-.504.069-1.317.082-1.446c.043-.434-.025-.561-.422-.956c-.215-.214-.376-.534-.376-.854v-.855c0-.266-.215-.48-.43-.533c-.644-.16-1.986-.427-3.919-.427s-3.275.266-3.92.427a.52.52 0 0 0-.429.533v.855c0 .32-.107.64-.376.854l-.16.16c-.216.16-.324.495-.324.762c.014.155.035 1.052.06 1.425a.634.634 0 0 1-.596-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082c1.015-.445 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.054 2.363.533l.805.801c.215.267.483.427.805.587");
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kmyr74hbl {
  d: path("M23.408 29.906v-11.8c2.355 2.01 3.848 4.986 3.848 8.31v2.49a1 1 0 0 1-1 1z");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kudttigsm {
  d: path("M8.953 29.906v-11.8c-2.356 2.01-3.848 4.986-3.848 8.31v3.49z");
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l4epxabbu {
  stop-color: var(--svg-color--564d5b, #564D5B);
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l6y6j1bti {
  width: 2.773px;
  height: 1.082px;
  x: 24.267px;
  y: 20.891px;
  rx: 0.541px;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mdj8rj_9y {
  stop-color: var(--svg-color--e4a217, #E4A217);
}

.mjg0akbde {
  stop-color: var(--svg-color--433945, #433945);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.msvvb9k2w {
  stop-color: var(--svg-color--cb831d, #CB831D);
  stop-opacity: 0;
}

.mws39tffk {
  cx: 11.415px;
  cy: 10.697px;
  r: 1.671px;
}

.n53ou2bxa {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m20.99 4.213l.43.214c.752.374 1.181 1.228 1.02 2.135l-.59 3.043c-.053.314-.26.526-.573.534c.036-.504.069-1.317.082-1.446c.043-.434-.025-.561-.422-.956c-.215-.214-.376-.534-.376-.854v-.855c0-.266-.215-.48-.43-.533c-.644-.16-1.986-.427-3.919-.427s-3.275.266-3.92.427a.52.52 0 0 0-.429.533v.855c0 .32-.107.64-.376.854l-.16.16c-.216.16-.324.495-.324.762c.014.155.035 1.052.06 1.425a.634.634 0 0 1-.596-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082c1.015-.445 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.054 2.363.533l.805.801c.215.267.483.427.805.587");
}

.nbg9ac2nn {
  stop-color: var(--svg-color--59545e, #59545E);
}

.ncgvd-jsx {
  stop-color: var(--svg-color--d99201, #D99201);
}

.nv7ilcg1p {
  stop-color: var(--svg-color--ffe049, #FFE049);
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o5ej-52sf {
  stop-color: var(--svg-color--d7cace, #D7CACE);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.oamypkk6h {
  fill-rule: evenodd;
  d: path("M17.949 8.49c.72-.068 1.182.214 1.294.317a.473.473 0 0 0 .64-.695c-.306-.283-1.032-.656-2.023-.564a.473.473 0 0 0 .088.942");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmhhlvwfw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.133 28.508h1.797");
}

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pvho5mb2d {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.77 8.348c.21-.193.804-.52 1.66-.44");
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q2ji4cbak {
  stop-color: var(--svg-color--d99201, #D99201);
  stop-opacity: 0;
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.q8ny10bzr {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.167 13.83c-.508 0-.985-.12-1.386-.328c-.138-.07-.285.084-.199.209c.336.508.92.846 1.585.846s1.25-.338 1.584-.846c.087-.13-.06-.28-.198-.21c-.4.21-.873.33-1.386.33");
}

.qbrho_b3d {
  stop-color: var(--svg-color--3b2321, #3B2321);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qo6juab9h {
  d: path("M16.185 15.447c-6.114 0-11.08 4.906-11.08 10.97v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.064-4.955-10.97-11.07-10.97");
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.r_oyacbqw {
  d: path("M26.969 22.84c.531 0 .959.426.959.958v2.188H26.02v-2.188a.94.94 0 0 1 .948-.959");
}

.r7-8oabxi {
  d: path("M23.188 16.861h-.613a.505.505 0 0 0-.504.504v3.022c0 .272.222.504.504.504h.613a.505.505 0 0 0 .504-.504v-3.022a.51.51 0 0 0-.504-.504");
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rloy1eb5h {
  stop-color: var(--svg-color--cb831d, #CB831D);
}

.rrq1e5bez {
  d: path("m16.976 19.789l.136-.122a3.5 3.5 0 0 0 1.148-2.548v-1.964h-4.15l-.005 1.911c0 .052.003.147 0 .2c.045.916.46 1.784 1.144 2.402l.16.143l.666-1.01a.13.13 0 0 1 .22 0z");
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.slex5bcbq {
  d: path("M18.284 9.726c.064.085-.07.189-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.05");
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.t-tjl2gfd {
  cx: 13.709px;
  cy: 9.919px;
  rx: 0.39px;
  ry: 0.197px;
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.u-5jc1bbs {
  cx: 20.937px;
  cy: 10.697px;
  r: 0.996px;
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.uerouv67z {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.167 13.83c-.508 0-.985-.12-1.386-.328c-.138-.07-.285.084-.199.209c.336.508.92.846 1.585.846s1.25-.338 1.584-.846c.087-.13-.06-.28-.198-.21c-.4.21-.873.33-1.386.33Z");
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.uva-dwpes {
  d: path("M27.093 16.861h-2.901a.505.505 0 0 0-.504.504v3.022c0 .272.222.504.504.504h2.901a.505.505 0 0 0 .504-.504v-3.022a.51.51 0 0 0-.504-.504");
}

.ux5vxebfi {
  fill: var(--svg-color--000, #000);
  d: path("M17.839 10.43a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.906a.46.46 0 0 1-.06-.236");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v718znckj {
  d: path("m17.112 19.668l-.655.584a.415.415 0 0 1-.554 0l-.654-.584a3.47 3.47 0 0 1-1.149-2.569v-3.113a2.085 2.085 0 0 1 2.086-2.065c1.148 0 2.075.927 2.075 2.075v3.113a3.5 3.5 0 0 1-1.149 2.559");
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vt9u3mbdx {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.563 8.348c-.209-.193-.803-.52-1.659-.44");
}

.w-er2h93j {
  stop-color: var(--svg-color--59545e, #59545E);
  stop-opacity: 0;
}

.w325k2k4x {
  cx: 20.937px;
  cy: 10.697px;
  r: 1.671px;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wsbgy6b7o {
  stop-color: var(--svg-color--ca9e1a, #CA9E1A);
}

.wy0gh7bzd {
  stop-color: var(--svg-color--835005, #835005);
}

.wyytu2b0o {
  stop-color: var(--svg-color--897576, #897576);
}

.x255252kl {
  d: path("m15.784 10.412l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ypj2-ccrf {
  d: path("M15.849 23.45h.692v6.326h-.692z");
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.yz57tkbzc {
  d: path("M11.062 10.084a30 30 0 0 1-.058-1.44c0-.267.107-.587.322-.747l.161-.16c.269-.214.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.918.427c.215.053.43.267.43.534v.854c0 .32.161.64.376.854c.502.352.471.546.43.96c-.014.13-.054 1.196-.09 1.442l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.714 0-3.053-1.235-3.213-3.006z");
}

.zh8xj40cc {
  d: path("M19.836 23.45h.692v6.326h-.692z");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zmx0ewbtm {
  stop-color: var(--svg-color--c69a19, #C69A19);
}

.zr1c6qbkd {
  stop-color: var(--svg-color--e58a1e, #E58A1E);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zuwocg1tc {
  d: path("M13.979 9.537a.893.893 0 0 0-.861 1.129h1.725a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.893");
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
