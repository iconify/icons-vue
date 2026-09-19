<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iicL1gc)" class="xxsefzpdq"/><path fill="url(#imzeprd)" class="xxsefzpdq"/><path fill="url(#iKkwVod)" class="b072x2aii"/><path fill="url(#iqdGPbc)" class="b072x2aii"/><path fill="url(#iYnd6Rc)" class="c-tja9bpr"/><path fill="url(#il3aafd)" class="c-tja9bpr"/><path fill="url(#iZQubKe)" class="c-tja9bpr"/><path fill="url(#ir2HP9d)" class="mspkabc6v"/><path fill="url(#ipOd9Xc)" class="mspkabc6v"/><path fill="url(#iVWGzDb)" class="mspkabc6v"/><path fill="url(#i6l3kGc)" class="mspkabc6v"/><g filter="url(#ivaPbPd)"><path class="fs1ufx2tc"/></g><path fill="url(#iLaes2w)" class="q9zrzf44o"/><g filter="url(#iA3Gvnc)"><path class="zvdkucbqp"/></g><g filter="url(#iIr1x9c)"><path fill="url(#iMm4Ddd)" class="u0ana6wkh"/><path fill="url(#ideVytc)" class="u0ana6wkh"/><path fill="url(#iNjTTxJ)" class="u0ana6wkh"/></g><path fill="url(#iXFEZTd)" class="u0ana6wkh"/><g filter="url(#iqf9iud)"><path class="l7xshgban"/></g><g filter="url(#iQOBq5g)"><path fill="url(#itFU7Nd)" class="vvnobeb4d"/><path fill="url(#ipIpBme)" class="vvnobeb4d"/></g><path fill="url(#ix1PWyN)" class="gael-ox4b"/><path fill="url(#iCZ4BTb)" class="gael-ox4b"/><path fill="url(#iqUNw9c)" class="gael-ox4b"/><path fill="url(#iDW3OSc)" class="gael-ox4b"/><g filter="url(#ivoUSQR)"><path fill="url(#iMNODVc)" class="xbtyokbyc"/></g><g filter="url(#iCkUQLb)"><path fill="url(#iX5Wgzd)" class="gt17cd57p"/></g><g filter="url(#i7XcFkc)"><path class="z-ivtrlcx"/></g><path fill="url(#i8mGLyd)" class="uw4z-ubyi"/><path fill="url(#inoQOkd)" class="j3xgdbbcc"/><path fill="url(#iYBw5Vd)" class="j3xgdbbcc"/><path fill="url(#inoQOkd)" class="j3xgdbbcc"/><path fill="url(#iYBw5Vd)" class="j3xgdbbcc"/><path fill="url(#ieVKrcd)" class="p_c3lrfef"/><path fill="url(#in0v6AT)" class="p1mpdub5r"/><g filter="url(#i2vazhd)"><path fill="url(#iuVlrlb)" class="pf6qr6y3m"/></g><path fill="url(#ietz3Be)" class="pf6qr6y3m"/><path fill="url(#iCK3jIe)" class="pf6qr6y3m"/><path fill="url(#i4vCjTc)" class="pf6qr6y3m"/><path fill="url(#inyNkpb)" class="pf6qr6y3m"/><path fill="url(#i0KG40c)" class="pf6qr6y3m"/><path fill="url(#iikczqb)" class="pf6qr6y3m"/><path fill="url(#igCke5B)" class="pf6qr6y3m"/><path fill="url(#iekkQzc)" class="pf6qr6y3m"/><path fill="url(#itWvk2b)" class="pf6qr6y3m"/><g filter="url(#im4mYNc)"><path class="s6s1pfbjl"/></g><g filter="url(#iRpjHsc)"><path fill="url(#iZyG7nT)" class="jmy-b40jz"/><path fill="url(#izVEXpb)" class="jmy-b40jz"/><path fill="url(#ih1aXsC)" class="jmy-b40jz"/><path fill="url(#iIjE0ee)" class="jmy-b40jz"/></g><path fill="url(#i28haCc)" class="jmy-b40jz"/><path fill="url(#ic2uMqd)" class="jmy-b40jz"/><g filter="url(#iz562gA)"><path stroke="url(#izdZCHb)" class="n002sbczo"/></g><path fill="url(#iZQEEBD)" class="omfferb1w"/><path class="qg8-h0e9x"/><path fill="url(#iSD3RMc)" class="a0w6a0s5g"/><path class="r04j8tbxx"/><g filter="url(#ii54O2d)"><path class="yn6gvix2b"/><path fill="url(#ionD8te)" class="iwa_0rbgm"/></g><g filter="url(#iVJHgbc)"><path fill="url(#iTTzYnM)" class="f8fccv_oj"/></g><path class="yups7qb8u"/><path fill="url(#iV1LS3c)" class="ykp9hfsoy"/><path class="dm4vdp19e"/><g filter="url(#i9k1wae)"><path fill="url(#iDrV6ov)" class="g54dqvbmy"/></g><g filter="url(#iDfj8ob)"><ellipse transform="rotate(-27.914 13.552 9.835)" class="wm5g_5b5g"/><ellipse fill="url(#iBDgiDb)" transform="rotate(-27.914 13.552 9.835)" class="yryltcjsm"/></g><path fill="url(#iUJm1me)" class="v-ux3r46l"/><path fill="url(#iynbD2b)" class="v-ux3r46l"/><path fill="url(#iLHGHwd)" class="v-ux3r46l"/><path fill="url(#ipntDDe)" class="hyg4lzbrv"/><path fill="url(#iTUt2Fb)" class="hyg4lzbrv"/><g filter="url(#i5jWD0b)"><path class="tct3dub4z"/></g><g filter="url(#i06bpbc)"><path class="uu243iyzk"/></g><g filter="url(#iQ0Hx1d)"><path fill="url(#iyNkKHc)" class="te18_qled"/></g><path fill="url(#iMe0HZc)" class="qvivknb0c"/><path fill="url(#iLreRab)" class="qvivknb0c"/><path fill="url(#iLN7jod)" class="qvivknb0c"/><g filter="url(#ikA3XAb)"><path fill="url(#iUWHaRL)" class="gio200bup"/></g><path fill="url(#iX4wzpc)" class="mr7tpbbng"/><path fill="url(#iKu0fib)" class="mr7tpbbng"/><path fill="url(#iMJWaPd)" class="mr7tpbbng"/><g filter="url(#iJIATDd)"><path class="fgsk7lbfw"/></g><g filter="url(#il6eS4d)"><path fill="url(#ima9okd)" class="u82_zobtn"/><path fill="url(#iIwwRze)" class="u82_zobtn"/></g><g filter="url(#iYe5n5b)"><path fill="url(#iYx447d)" class="h4jgozbmm"/></g><g filter="url(#iei3rcg)"><path fill="url(#iGflDkc)" class="ll6v6sbuj"/></g><path fill="url(#ioY443d)" class="ll6v6sbuj"/><defs><radialGradient id="imzeprd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.03125 0 0 -12.2293 23.224 24.404)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="s59tlt20i"/><stop offset="1" class="dimomr5au"/></radialGradient><radialGradient id="iKkwVod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4916 2.16348 0 25.063 30)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="izw19gb1b"/><stop offset="1" class="pk_fxjb0k"/></radialGradient><radialGradient id="iqdGPbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.6896 .7187 0 23.13 30)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v7hn87gdb"/><stop offset="1" class="yfv60kbve"/></radialGradient><radialGradient id="iYnd6Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.94746 4.23507 0 6.615 30)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="ydmi_gbdg"/><stop offset="1" class="j_s_0lsgx"/></radialGradient><radialGradient id="iZQubKe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70333 0 0 -15.6939 8.708 29.637)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kolzjh1uk"/><stop offset="1" class="oqr8hmbdg"/></radialGradient><radialGradient id="ir2HP9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91012 -3.40129 0 16 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="w4yfy3zsx"/><stop offset="1" class="b0hon_b8a"/></radialGradient><radialGradient id="i6l3kGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1875 .46252 0 18.255 30.216)" gradientUnits="userSpaceOnUse"><stop class="zj0khrbgv"/><stop offset="1" class="rndoiibli"/></radialGradient><radialGradient id="iLaes2w" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.70312 -1.55313 0 15.991 21.044)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="g-uemq__p"/><stop offset=".907" class="ny-qt-bge"/></radialGradient><radialGradient id="ideVytc" cx="0" cy="0" r="1" gradientTransform="rotate(122.782 2.494 11.9)scale(3.60548 4.04568)" gradientUnits="userSpaceOnUse"><stop class="hqfmlmg6f"/><stop offset="1" class="oyco1db5g"/></radialGradient><radialGradient id="iNjTTxJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08638 -1.3984 0 13.295 23.22)" gradientUnits="userSpaceOnUse"><stop class="n-1p2p9pr"/><stop offset="1" class="v-e2dxczh"/></radialGradient><radialGradient id="ipIpBme" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.37956 -1.6894 .99499 19.036 15.868)" gradientUnits="userSpaceOnUse"><stop class="mgj3nfyon"/><stop offset="1" class="e6sjkybst"/></radialGradient><radialGradient id="ix1PWyN" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15625 -4.85106 0 16.005 18.69)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="dsfnryq2l"/><stop offset="1" class="e3skdu--u"/></radialGradient><radialGradient id="iCZ4BTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.96876 2.18983 -2.26044 15.24 19.685)" gradientUnits="userSpaceOnUse"><stop class="ng9k9ab_a"/><stop offset="1" class="o-y5a1rmp"/></radialGradient><radialGradient id="iX5Wgzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.41287 -1.9196 0 16.005 17.154)" gradientUnits="userSpaceOnUse"><stop class="ve_rbw--l"/><stop offset="1" class="cvte-zb6w"/></radialGradient><radialGradient id="i8mGLyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 21.464 11.622)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="inoQOkd" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 10.457 11.905)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iYBw5Vd" cx="0" cy="0" r="1" gradientTransform="matrix(.1793 1.19363 -1.04706 .15728 11.258 11.7)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="in0v6AT" cx="0" cy="0" r="1" gradientTransform="matrix(-.2415 1.95344 -.67327 -.08323 21.726 7.242)" gradientUnits="userSpaceOnUse"><stop class="rq4errj1n"/><stop offset="1" class="uv6sh1a6t"/></radialGradient><radialGradient id="iuVlrlb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.813 10.847)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iCK3jIe" cx="0" cy="0" r="1" gradientTransform="scale(10.5735 12.7681)rotate(90 .594 .96)" gradientUnits="userSpaceOnUse"><stop offset=".785" class="b57kj8b5a"/><stop offset="1" class="qyflzgbrp"/></radialGradient><radialGradient id="i4vCjTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 18.452 9.726)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="inyNkpb" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 11.432 -1.736)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="i0KG40c" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 11.124 11.231)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iikczqb" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 10.152 7.845)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="igCke5B" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 15.851 14.919)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iekkQzc" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 17.963 5.465)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="itWvk2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -5.48959 0 16.052 8.62)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="nv9cu8u0l"/><stop offset="1" class="kr5wicmfk"/></radialGradient><radialGradient id="ic2uMqd" cx="0" cy="0" r="1" gradientTransform="rotate(135.131 6.289 8.9)scale(2.59561 1.64977)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="izdZCHb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.502 -5.63)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="wm9r96bky"/><stop offset="1" class="al7wq0b-a"/></radialGradient><radialGradient id="iZQEEBD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16.005 14.386)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iSD3RMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.187 9.93)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ionD8te" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 17.959 10.014)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iV1LS3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.823 9.93)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iBDgiDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.536 10.15)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iynbD2b" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.623 9.944)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iLHGHwd" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.983 10.489)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iTUt2Fb" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.93 4.89)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="iMe0HZc" cx="0" cy="0" r="1" gradientTransform="matrix(-.31252 4.2792 -11.47135 -.83777 16.475 2)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ucx7riblp"/><stop offset="1" class="fxe3zh8pp"/></radialGradient><radialGradient id="iLreRab" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -1.29228 20.788 4.31)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="x6mjrexfr"/><stop offset="1" class="pj095ubna"/></radialGradient><radialGradient id="iLN7jod" cx="0" cy="0" r="1" gradientTransform="matrix(1.75085 0 0 2.31943 9.37 4.747)" gradientUnits="userSpaceOnUse"><stop class="a21-6lr8n"/><stop offset="1" class="ln2o6octk"/></radialGradient><radialGradient id="iUWHaRL" cx="0" cy="0" r="1" gradientTransform="matrix(-.40626 -3.49726 14.5441 -1.6895 18.59 8.9)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="q6gdl1i5d"/><stop offset=".47" class="i99yksbww"/><stop offset="1" class="viu_-ol9y"/></radialGradient><radialGradient id="iKu0fib" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.53896 .06546 -.53895 21.089 6.06)" gradientUnits="userSpaceOnUse"><stop class="qk2jzhbua"/><stop offset="1" class="nklj5u79d"/></radialGradient><radialGradient id="iMJWaPd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 -.5948 .09009 -.59163 21.089 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="rgck1cbbg"/><stop offset="1" class="k3jqbac6c"/></radialGradient><radialGradient id="iIwwRze" cx="0" cy="0" r="1" gradientTransform="rotate(-135 8.67 -1.204)scale(.62166 .97779)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="hm8qkhptt"/><stop offset="1" class="xy9hyobea"/></radialGradient><radialGradient id="iGflDkc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .96874 -1.00462 -.97222 16.573 4.044)" gradientUnits="userSpaceOnUse"><stop class="qga7xqb8q"/><stop offset="1" class="pp0fzgbhc"/></radialGradient><radialGradient id="ioY443d" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.65625 1.11 1.48 15.87 4.544)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="jsljpd_vj"/><stop offset="1" class="qga7xqb8q"/></radialGradient><linearGradient id="iicL1gc" x1="16" x2="16" y1="15.501" y2="30.001" gradientUnits="userSpaceOnUse"><stop class="ka-y4km4d"/><stop offset="1" class="odfguq8mk"/></linearGradient><linearGradient id="il3aafd" x1="9.135" x2="6.943" y1="27.817" y2="27.817" gradientUnits="userSpaceOnUse"><stop offset=".124" class="m9kzfz-8h"/><stop offset="1" class="h_4try76x"/></linearGradient><linearGradient id="ipOd9Xc" x1="16.505" x2="16.505" y1="30.466" y2="28.997" gradientUnits="userSpaceOnUse"><stop class="cuwamcc7w"/><stop offset="1" class="e9vdenjit"/></linearGradient><linearGradient id="iVWGzDb" x1="19.067" x2="17.161" y1="26.56" y2="26.56" gradientUnits="userSpaceOnUse"><stop class="hi4tb8d4g"/><stop offset="1" class="l6siijbzt"/></linearGradient><linearGradient id="iMm4Ddd" x1="13.295" x2="13.295" y1="29.372" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="gxm502ben"/><stop offset="1" class="qg2z49_rr"/></linearGradient><linearGradient id="iXFEZTd" x1="13.295" x2="13.295" y1="29.69" y2="23.356" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ke9tt_b-u"/><stop offset="1" class="w784rnm9d"/></linearGradient><linearGradient id="itFU7Nd" x1="18.715" x2="19.724" y1="20.747" y2="20.747" gradientUnits="userSpaceOnUse"><stop class="olptj6tus"/><stop offset="1" class="d-3cltoww"/></linearGradient><linearGradient id="iqUNw9c" x1="13.583" x2="15.177" y1="16.56" y2="18.607" gradientUnits="userSpaceOnUse"><stop class="sv13rb7yi"/><stop offset="1" class="k5-d0pb7l"/></linearGradient><linearGradient id="iDW3OSc" x1="18.442" x2="17.099" y1="16.497" y2="18.247" gradientUnits="userSpaceOnUse"><stop class="sv13rb7yi"/><stop offset="1" class="k5-d0pb7l"/></linearGradient><linearGradient id="iMNODVc" x1="15.991" x2="15.991" y1="19.225" y2="20.922" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bf4zukp8q"/><stop offset="1" class="i_g168btd"/></linearGradient><linearGradient id="ieVKrcd" x1="10.347" x2="11.067" y1="7.888" y2="7.888" gradientUnits="userSpaceOnUse"><stop class="rz8yfnbhx"/><stop offset="1" class="su24cbhww"/></linearGradient><linearGradient id="ietz3Be" x1="21.162" x2="16.81" y1="12.532" y2="12.532" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iZyG7nT" x1="16.005" x2="16.86" y1="11.675" y2="11.675" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="izVEXpb" x1="14.932" x2="16.006" y1="11.52" y2="11.579" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ih1aXsC" x1="16.005" x2="16.005" y1="12.074" y2="12.926" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iIjE0ee" x1="16.005" x2="16.005" y1="9.826" y2="10.246" gradientUnits="userSpaceOnUse"><stop class="e9vsg-b6g"/><stop offset="1" class="tn83mykri"/></linearGradient><linearGradient id="i28haCc" x1="16.136" x2="16.136" y1="12.748" y2="12.689" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="iTTzYnM" x1="18.965" x2="18.651" y1="9.984" y2="10.178" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDrV6ov" x1="14.567" x2="14.253" y1="9.984" y2="10.178" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUJm1me" x1="22.441" x2="21.235" y1="10.011" y2="12.187" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="ipntDDe" x1="10.155" x2="11.614" y1="10.715" y2="10.588" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="iyNkKHc" x1="21.084" x2="22.88" y1="20.076" y2="20.711" gradientUnits="userSpaceOnUse"><stop class="uns_kgbkm"/><stop offset="1" class="vglr3ibxi"/></linearGradient><linearGradient id="iX4wzpc" x1="17.339" x2="11.12" y1="6.841" y2="6.841" gradientUnits="userSpaceOnUse"><stop class="a_cf-ibqz"/><stop offset="1" class="ayzgumbov"/></linearGradient><linearGradient id="ima9okd" x1="16.081" x2="14.503" y1="4.161" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="whje1li3v"/><stop offset="1" class="u3hfg3htm"/></linearGradient><linearGradient id="iYx447d" x1="18.073" x2="16.587" y1="3.169" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="xgphulxrx"/><stop offset="1" class="cit_-lbel"/></linearGradient><filter id="ivaPbPd" width="7.031" height="7.114" x="12.489" y="14.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".5"/></filter><filter id="iA3Gvnc" width="4.951" height="14.36" x="9.117" y="15.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".5"/></filter><filter id="iIr1x9c" width="3.097" height="14.304" x="10.348" y="15.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2467"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.290196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2467" result="effect2_innerShadow_4002_2467"/></filter><filter id="iqf9iud" width="4.081" height="12.629" x="18.162" y="15.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".5"/></filter><filter id="iQOBq5g" width="3.042" height="14.123" x="18.465" y="15.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.372549 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2467"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2467" result="effect2_innerShadow_4002_2467"/></filter><filter id="ivoUSQR" width="2.735" height="2.58" x="14.632" y="18.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2467"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2467" result="effect2_innerShadow_4002_2467"/></filter><filter id="iCkUQLb" width="3.989" height="1.699" x="13.935" y="16.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.360784 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2467"/></filter><filter id="i7XcFkc" width="3.151" height="1.346" x="20.534" y="19.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".1"/></filter><filter id="i2vazhd" width="10.97" height="12.542" x="10.942" y="4.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2467"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2467" result="effect2_innerShadow_4002_2467"/></filter><filter id="im4mYNc" width="3.754" height="4.824" x="13.859" y="9.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".5"/></filter><filter id="iRpjHsc" width="2.077" height="3.1" x="14.966" y="9.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".05"/></filter><filter id="iz562gA" width="3.718" height="1.573" x="14.146" y="13.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".05"/></filter><filter id="ii54O2d" width=".787" height=".696" x="17.453" y="9.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".05"/></filter><filter id="iVJHgbc" width=".891" height=".913" x="18.293" y="9.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".1"/></filter><filter id="i9k1wae" width=".986" height="1.04" x="13.85" y="9.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".1"/></filter><filter id="iDfj8ob" width=".913" height=".704" x="13.095" y="9.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".05"/></filter><filter id="i5jWD0b" width="1.329" height="2.379" x="9.972" y="9.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".125"/></filter><filter id="i06bpbc" width="1.447" height="2.403" x="20.717" y="9.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".125"/></filter><filter id="iQ0Hx1d" width="2.881" height="1.03" x="20.734" y="19.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.529412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2467"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.760784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2467" result="effect2_innerShadow_4002_2467"/></filter><filter id="ikA3XAb" width="10.9" height="2.77" x="10.545" y="6.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2467"/></filter><filter id="iJIATDd" width="4.831" height="2.64" x="13.58" y="2.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2467" stdDeviation=".125"/></filter><filter id="il6eS4d" width="2.293" height="1.21" x="13.851" y="3.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.65098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2467"/></filter><filter id="iYe5n5b" width="2.298" height="1.22" x="15.933" y="3.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2467"/></filter><filter id="iei3rcg" width="1.63" height="1.63" x="15.285" y="3.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.4 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2467"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pilot-medium-light" /></template>
<style>
.a_cf-ibqz {
  stop-color: var(--svg-color--e3ac3f, #E3AC3F);
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a0w6a0s5g {
  d: path("M18.19 9.453a.893.893 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.a21-6lr8n {
  stop-color: var(--svg-color--5d5a62, #5D5A62);
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.al7wq0b-a {
  stop-color: var(--svg-color--d6a092, #D6A092);
  stop-opacity: 0;
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.ayzgumbov {
  stop-color: var(--svg-color--b88538, #B88538);
}

.b072x2aii {
  d: path("M23.13 18.124V30h3.865v-3.5c0-3.357-1.5-6.36-3.865-8.378");
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.b57kj8b5a {
  stop-color: var(--svg-color--c7848e, #C7848E);
  stop-opacity: 0;
}

.bf4zukp8q {
  stop-color: var(--svg-color--543555, #543555);
}

.c-tja9bpr {
  d: path("M8.88 30V18.12a10.97 10.97 0 0 0-3.875 8.38V30z");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cit_-lbel {
  stop-color: var(--svg-color--e09037, #E09037);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuwamcc7w {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
}

.cvte-zb6w {
  stop-color: var(--svg-color--b97a87, #B97A87);
}

.d-3cltoww {
  stop-color: var(--svg-color--625990, #625990);
}

.dimomr5au {
  stop-color: var(--svg-color--6b629a, #6B629A);
  stop-opacity: 0;
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm4vdp19e {
  fill: var(--svg-color--000, #000);
  d: path("M14.332 10.346a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dsfnryq2l {
  stop-color: var(--svg-color--c0aac0, #C0AAC0);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e3skdu--u {
  stop-color: var(--svg-color--928392, #928392);
}

.e6sjkybst {
  stop-color: var(--svg-color--504069, #504069);
  stop-opacity: 0;
}

.e9vdenjit {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
  stop-opacity: 0;
}

.e9vsg-b6g {
  stop-color: var(--svg-color--c99080, #C99080);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f8fccv_oj {
  d: path("M18.984 10.228a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.fgsk7lbfw {
  fill: var(--svg-color--382534, #382534);
  d: path("M16.783 4.352h.633a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.275.475a.8.8 0 0 0-.415.005l-.272-.47a.2.2 0 0 0-.18-.11h-1.4c-.08 0-.13.09-.09.16l.54.94c.04.07.1.11.18.11h.66a.79.79 0 1 0 1.559 0");
}

.fs1ufx2tc {
  fill: var(--svg-color--8f809c, #8F809C);
  d: path("M16.005 15.348H13.49v4.74c0 .31.334.49.566.29l1.95-1.67l1.948 1.67c.232.2.567.02.567-.29v-4.74z");
}

.ft5dv1b6b {
  fill: none;
}

.fxe3zh8pp {
  stop-color: var(--svg-color--3b3541, #3B3541);
}

.g-uemq__p {
  stop-color: var(--svg-color--59416c, #59416C);
}

.g54dqvbmy {
  d: path("M14.636 10.24c0-.287-.234-.48-.297-.538l-.289.279l.177.361z");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gael-ox4b {
  d: path("M16.005 15.284h-2.71v4.74c0 .31.36.49.61.29l2.1-1.67l2.1 1.67c.25.2.61.02.61-.29v-4.74z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gio200bup {
  d: path("M15.995 6.33s-2.53-.03-5.45.73l.4.47c.73.87 1.81 1.37 2.95 1.37h4.19c1.14 0 2.22-.5 2.96-1.37l.4-.47c-2.92-.76-5.45-.73-5.45-.73");
}

.gt17cd57p {
  d: path("M16.005 18.445c1.789-.788 1.932-1.316 1.919-1.7h-3.838c-.013.384.224.971 1.919 1.7");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gxm502ben {
  stop-color: var(--svg-color--605388, #605388);
}

.h_4try76x {
  stop-color: var(--svg-color--524c6a, #524C6A);
  stop-opacity: 0;
}

.h4jgozbmm {
  d: path("M16.087 4.24h1.4a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.55.95c-.04.07.01.16.09.16");
}

.hi4tb8d4g {
  stop-color: var(--svg-color--80728b, #80728B);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hm8qkhptt {
  stop-color: var(--svg-color--c47c25, #C47C25);
}

.hqfmlmg6f {
  stop-color: var(--svg-color--483555, #483555);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.hyg4lzbrv {
  d: path("M10.951 8.988a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.i_g168btd {
  stop-color: var(--svg-color--483a53, #483A53);
}

.i99yksbww {
  stop-color: var(--svg-color--4f3e5f, #4F3E5F);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.iwa_0rbgm {
  d: path("M18.124 9.642c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

.izw19gb1b {
  stop-color: var(--svg-color--7d72a2, #7D72A2);
}

.j_s_0lsgx {
  stop-color: var(--svg-color--524a68, #524A68);
}

.j3xgdbbcc {
  d: path("M11.144 12.096a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.jmy-b40jz {
  d: path("m15.623 10.132l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.jsljpd_vj {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
  stop-opacity: 0;
}

.k3jqbac6c {
  stop-color: var(--svg-color--eba026, #EBA026);
  stop-opacity: 0;
}

.k5-d0pb7l {
  stop-color: var(--svg-color--987a8d, #987A8D);
  stop-opacity: 0;
}

.ka-y4km4d {
  stop-color: var(--svg-color--584c78, #584C78);
}

.ke9tt_b-u {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kolzjh1uk {
  stop-color: var(--svg-color--6e638c, #6E638C);
  stop-opacity: 0;
}

.kr5wicmfk {
  stop-color: var(--svg-color--af7473, #AF7473);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l6siijbzt {
  stop-color: var(--svg-color--80728b, #80728B);
  stop-opacity: 0;
}

.l7xshgban {
  fill: var(--svg-color--44375d, #44375D);
  d: path("m20.055 20.479l.444 1.05c.202.26.272.65.178 1.01l-1.295 4.646l-.22-10.446l.09-.183q.507.173.989.423l.98 2.64c.07.19-.04.41-.202.41h-.816c-.187 0-.28.28-.148.45");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll6v6sbuj {
  d: path("M16.075 5.16a.79.79 0 1 0 0-1.58a.79.79 0 0 0 0 1.58");
}

.ln2o6octk {
  stop-color: var(--svg-color--3a3340, #3A3340);
  stop-opacity: 0;
}

.m9kzfz-8h {
  stop-color: var(--svg-color--443a60, #443A60);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgj3nfyon {
  stop-color: var(--svg-color--504069, #504069);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mr7tpbbng {
  d: path("M15.945 5.52h.1c.39 0 2.27.02 4.56.51c.49.1.84.53.84 1.03c-2.92-.76-5.45-.73-5.45-.73s-2.53-.03-5.45.73c0-.5.35-.93.84-1.03c2.29-.48 4.16-.51 4.56-.51");
}

.mspkabc6v {
  d: path("M18.705 16.11h-5.41V30h5.41z");
}

.n-1p2p9pr {
  stop-color: var(--svg-color--615589, #615589);
}

.n002sbczo {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.654 13.348a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.645.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.352-.32Z");
}

.ng9k9ab_a {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
}

.nklj5u79d {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
  stop-opacity: 0;
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nv9cu8u0l {
  stop-color: var(--svg-color--af7473, #AF7473);
}

.ny-qt-bge {
  stop-color: var(--svg-color--3a3045, #3A3045);
}

.o-y5a1rmp {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
  stop-opacity: 0;
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odfguq8mk {
  stop-color: var(--svg-color--5a4b85, #5A4B85);
}

.olptj6tus {
  stop-color: var(--svg-color--56466e, #56466E);
}

.omfferb1w {
  d: path("M16.005 13.743c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.918.846 1.583.846s1.249-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.oqr8hmbdg {
  stop-color: var(--svg-color--6e638c, #6E638C);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.oyco1db5g {
  stop-color: var(--svg-color--483555, #483555);
  stop-opacity: 0;
}

.p_c3lrfef {
  d: path("M10.347 6.319h.719v3.752h-.719z");
}

.p1mpdub5r {
  d: path("M21.007 6.29h.72v3.752H20.68z");
}

.pf6qr6y3m {
  d: path("M11.18 13.612a3.916 3.916 0 0 0 3.886 3.405h1.886a3.916 3.916 0 0 0 3.886-3.405c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.pj095ubna {
  stop-color: var(--svg-color--635870, #635870);
  stop-opacity: 0;
}

.pk_fxjb0k {
  stop-color: var(--svg-color--6e658c, #6E658C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp0fzgbhc {
  stop-color: var(--svg-color--ce8634, #CE8634);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q6gdl1i5d {
  stop-color: var(--svg-color--695978, #695978);
}

.q9zrzf44o {
  d: path("M15.517 21.044a.25.25 0 0 0-.247.212l-1.335 8.745h4.12l-1.33-8.745a.25.25 0 0 0-.247-.212z");
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qg2z49_rr {
  stop-color: var(--svg-color--564973, #564973);
}

.qg8-h0e9x {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.396 9.182c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.127");
}

.qga7xqb8q {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
}

.qk2jzhbua {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
}

.qvivknb0c {
  d: path("M21.737 3.55c-2.66-1.66-5.7-1.55-5.74-1.55s-3.14-.01-5.74 1.54c-1 .6-1.19 1.96-.39 2.8l.68.72h10.9l.68-.72c.8-.83.6-2.18-.39-2.79");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyflzgbrp {
  stop-color: var(--svg-color--b36590, #B36590);
}

.r04j8tbxx {
  fill: var(--svg-color--000, #000);
  d: path("M17.678 10.346c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.rgck1cbbg {
  stop-color: var(--svg-color--eba026, #EBA026);
}

.rndoiibli {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
  stop-opacity: 0;
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rq4errj1n {
  stop-color: var(--svg-color--ffebb7, #FFEBB7);
}

.rz8yfnbhx {
  stop-color: var(--svg-color--f0bf96, #F0BF96);
}

.s59tlt20i {
  stop-color: var(--svg-color--7d77a7, #7D77A7);
}

.s6s1pfbjl {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.574 10.51l-.691 1.656c-.102.378.141.756.486.756h.735c.345 0 .588-.384.486-.756l-.496-1.838c-.107-.408-.408-.225-.52.182");
}

.su24cbhww {
  stop-color: var(--svg-color--e9b887, #E9B887);
}

.sv13rb7yi {
  stop-color: var(--svg-color--68565a, #68565A);
}

.tct3dub4z {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.968 9.649a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.te18_qled {
  d: path("M23.365 19.78h-.64c-.23 0-.44.13-.54.33c-.01.02-.04.02-.04 0c-.1-.2-.31-.33-.54-.33h-.62c-.13 0-.24.09-.25.22s.1.25.23.25h.16c.04 0 .08.02.1.06l.09.2c.06.12.18.2.32.2h1.07c.14 0 .26-.08.32-.2l.09-.2a.11.11 0 0 1 .1-.06h.15c.13 0 .24-.09.25-.22c-.01-.14-.12-.25-.25-.25");
}

.tn83mykri {
  stop-color: var(--svg-color--c99080, #C99080);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0ana6wkh {
  d: path("M13.295 15.837q-.691.176-1.345.436l-.035.018l-1.27 2.69c-.09.19.05.41.26.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01z");
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u3hfg3htm {
  stop-color: var(--svg-color--e2a23d, #E2A23D);
}

.u82_zobtn {
  d: path("M16.035 4.24h-1.4a.2.2 0 0 1-.18-.11l-.54-.94c-.04-.07.01-.16.09-.16h1.4a.2.2 0 0 1 .18.11l.55.95c.03.06-.02.15-.1.15");
}

.ucx7riblp {
  stop-color: var(--svg-color--5d4c6d, #5D4C6D);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uns_kgbkm {
  stop-color: var(--svg-color--e3ab3f, #E3AB3F);
}

.uu243iyzk {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.967 11.536q.059-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.uv6sh1a6t {
  stop-color: var(--svg-color--fcd89f, #FCD89F);
}

.uw4z-ubyi {
  d: path("M20.866 12.096c.335-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.341 2.02q.256-.546.346-1.18z");
}

.v-e2dxczh {
  stop-color: var(--svg-color--615589, #615589);
  stop-opacity: 0;
}

.v-ux3r46l {
  d: path("M20.927 12.187q.1-1.596.185-3.19a1.61 1.61 0 0 1-.185 3.19");
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v7hn87gdb {
  stop-color: var(--svg-color--4f4175, #4F4175);
}

.ve_rbw--l {
  stop-color: var(--svg-color--b46982, #B46982);
}

.vglr3ibxi {
  stop-color: var(--svg-color--ecac40, #ECAC40);
}

.viu_-ol9y {
  stop-color: var(--svg-color--362c38, #362C38);
}

.vvnobeb4d {
  d: path("m19.865 19.79l1.36 1.33c.26.26.35.65.23 1.01l-2.74 7.86V16.05l.117-.182q.653.173 1.272.423l1.261 2.64c.09.19-.05.41-.26.41h-1.05c-.24 0-.36.28-.19.45");
}

.w4yfy3zsx {
  stop-color: var(--svg-color--c7bbd0, #C7BBD0);
}

.w784rnm9d {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
  stop-opacity: 0;
}

.whje1li3v {
  stop-color: var(--svg-color--d19b3e, #D19B3E);
}

.wm5g_5b5g {
  cx: 13.552px;
  cy: 9.835px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.wm9r96bky {
  stop-color: var(--svg-color--d6a092, #D6A092);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x6mjrexfr {
  stop-color: var(--svg-color--635870, #635870);
}

.xbtyokbyc {
  d: path("m14.732 19.661l1.267-1.098l1.268 1.075l-.546 1.265a.24.24 0 0 1-.216.14h-1.022a.24.24 0 0 1-.216-.14z");
}

.xgphulxrx {
  stop-color: var(--svg-color--e6ac3e, #E6AC3E);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.xxsefzpdq {
  d: path("M16.005 15.5c-6.07 0-11 4.92-11 11V30h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xy9hyobea {
  stop-color: var(--svg-color--c47c25, #C47C25);
  stop-opacity: 0;
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.ydmi_gbdg {
  stop-color: var(--svg-color--5a4b81, #5A4B81);
}

.yfv60kbve {
  stop-color: var(--svg-color--514476, #514476);
  stop-opacity: 0;
}

.ykp9hfsoy {
  d: path("M13.821 9.453a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yn6gvix2b {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.124 9.642c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

.yryltcjsm {
  cx: 13.552px;
  cy: 9.835px;
  rx: 0.39px;
  ry: 0.197px;
}

.yups7qb8u {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.614 9.181c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.128");
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z-ivtrlcx {
  fill: var(--svg-color--473a60, #473A60);
  d: path("M23.247 19.836h-.611c-.22 0-.42.13-.516.329c-.01.02-.038.02-.038 0a.57.57 0 0 0-.516-.33h-.592c-.124 0-.23.09-.239.22c-.01.13.096.25.22.25h.152c.18 0 .18.079.213.15a.34.34 0 0 0 .306.198h.238l.54.13c.133 0 .46-.1.518-.22l.086-.199c.02-.04.057-.06.096-.06h.143c.124 0 .229-.09.238-.219c-.01-.14-.114-.25-.238-.25");
}

.zj0khrbgv {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zvdkucbqp {
  fill: var(--svg-color--44375d, #44375D);
  d: path("M12.795 16.462c-.46.117-.364.098-.8.271c-.54.783-1.546 2.199-1.85 2.873c-.09.19.05.41.26.41l1.18-.174c.24 0 .35.29.19.45l-1.37 1.196c-.26.26-.36.65-.23 1l2.893 6.334z");
}

</style>
