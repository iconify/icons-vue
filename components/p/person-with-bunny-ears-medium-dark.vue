<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#svgIDa)"><path fill="url(#svgIDb)" class="skdh8c8wf"/><path fill="url(#svgIDc)" class="skdh8c8wf"/></g><g filter="url(#svgIDd)"><path fill="url(#svgIDe)" class="b0c6xjbyb"/></g><g filter="url(#svgIDf)"><path class="l7791cb7a"/></g><path fill="url(#svgIDg)" class="g1-cakgjb"/><path fill="url(#svgIDh)" class="g1-cakgjb"/><path fill="url(#svgIDi)" class="tjubatb2f"/><path fill="url(#svgIDj)" class="tjubatb2f"/><circle class="jct6q3bgk"/><g filter="url(#svgIDk)"><path clip-rule="evenodd" class="dqz42kghw"/></g><circle fill="url(#svgIDl)" transform="matrix(-1 0 0 1 25.185 16.739)" class="kr_eiac3t"/><g filter="url(#svgIDm)"><path clip-rule="evenodd" class="rk3eawbja"/></g><path fill="url(#svgIDn)" class="ldd357aax"/><path fill="url(#svgIDo)" class="ldd357aax"/><g filter="url(#svgIDp)"><path class="yramohxcj"/></g><path class="mngobgbzy"/><path fill="url(#svgIDq)" class="j7sojhblo"/><g filter="url(#svgIDr)"><path class="g6a574b3m"/></g><path fill="url(#svgIDs)" class="nykqrqb8m"/><path fill="url(#svgIDt)" class="nykqrqb8m"/><path fill="url(#svgIDu)" class="nykqrqb8m"/><path fill="url(#svgIDv)" class="nykqrqb8m"/><path fill="url(#svgIDw)" class="nykqrqb8m"/><path fill="url(#svgIDx)" class="jaeg0gihu"/><g filter="url(#svgIDy)"><path class="dljw9bc0b"/></g><path fill="url(#svgIDz)" class="l01j3pbwi"/><path fill="url(#svgIDA)" class="qvlyoocen"/><g filter="url(#svgIDB)"><path fill="url(#svgIDC)" class="rq-cvac7p"/><path fill="url(#svgIDD)" class="rq-cvac7p"/></g><path fill="url(#svgIDE)" class="rq-cvac7p"/><path fill="url(#svgIDF)" class="rq-cvac7p"/><path fill="url(#svgIDG)" class="rq-cvac7p"/><path fill="url(#svgIDH)" class="rq-cvac7p"/><path fill="url(#svgIDI)" class="rq-cvac7p"/><path fill="url(#svgIDJ)" class="rq-cvac7p"/><path fill="url(#svgIDK)" class="rq-cvac7p"/><g filter="url(#svgIDL)"><path class="kdy9aobnt"/></g><g filter="url(#svgIDM)"><path class="c2d4a5g8l"/><path fill="url(#svgIDN)" class="sn_vbz34j"/><path fill="url(#svgIDO)" class="sn_vbz34j"/><path fill="url(#svgIDP)" class="sn_vbz34j"/><path fill="url(#svgIDQ)" class="sn_vbz34j"/><path fill="url(#svgIDR)" class="sn_vbz34j"/></g><g filter="url(#svgIDS)"><path stroke="url(#svgIDT)" class="fr658ly7x"/></g><path fill="url(#svgIDU)" class="t1dkn1b9a"/><g filter="url(#svgIDV)"><path fill="url(#svgIDW)" class="u_6vs988p"/><path fill="url(#svgIDX)" class="u_6vs988p"/><path fill="url(#svgIDY)" class="u_6vs988p"/><path fill="url(#svgIDZ)" class="u_6vs988p"/><path fill="url(#svgIDaa)" class="u_6vs988p"/></g><g filter="url(#svgIDab)"><path class="uf4taw41y"/></g><g filter="url(#svgIDac)"><path class="db11z6bdb"/></g><g filter="url(#svgIDad)"><path class="fj5yx3bkn"/><path fill="url(#svgIDae)" class="p_gmsk5sh"/><path fill="url(#svgIDaf)" class="p_gmsk5sh"/></g><g filter="url(#svgIDag)"><path class="z_3wb62rz"/><path fill="url(#svgIDah)" class="l9173fpsg"/><path fill="url(#svgIDai)" class="l9173fpsg"/></g><path class="mz2-1bfbk"/><path fill="url(#svgIDaj)" class="djrsqybxo"/><path class="hkkby1b0v"/><g filter="url(#svgIDak)"><path class="tagzx62qg"/><path fill="url(#svgIDal)" class="ok2_u5b_w"/></g><g filter="url(#svgIDam)"><path fill="url(#svgIDan)" class="th19h-bzp"/></g><path class="w0h64fbkw"/><path fill="url(#svgIDao)" class="dpxwbi0bi"/><path class="nr62m8bsb"/><g filter="url(#svgIDap)"><path fill="url(#svgIDaq)" class="dt8z2pq0g"/></g><g filter="url(#svgIDar)" transform="rotate(-27.914 20.795 7.476)"><ellipse class="ozea8lbrw"/><ellipse fill="url(#svgIDas)" class="g9r0e3b5l"/></g><path fill="url(#svgIDat)" class="w838mqvgb"/><path fill="url(#svgIDau)" class="w838mqvgb"/><path fill="url(#svgIDav)" class="w838mqvgb"/><path fill="url(#svgIDaw)" class="w838mqvgb"/><path fill="url(#svgIDax)" class="rei3gtbmc"/><path fill="url(#svgIDay)" class="rei3gtbmc"/><g filter="url(#svgIDaz)"><path fill="url(#svgIDaA)" class="f8pmzbbav"/></g><g filter="url(#svgIDaB)"><path fill="url(#svgIDaC)" class="f_grh3duv"/></g><g filter="url(#svgIDaD)"><path class="v5hncxoqr"/></g><g filter="url(#svgIDaE)"><path class="ipmv6inso"/></g><g filter="url(#svgIDaF)"><path class="q_um76bvk"/></g><g filter="url(#svgIDaG)"><path class="tfw8ds16k"/></g><g filter="url(#svgIDaH)"><path class="iyrh5w2dl"/></g><g filter="url(#svgIDaI)"><path fill="url(#svgIDaJ)" class="ecm9b1coi"/></g><g filter="url(#svgIDaK)"><path fill="url(#svgIDaL)" class="qut0ht_ps"/><path fill="url(#svgIDaM)" class="qut0ht_ps"/></g><g filter="url(#svgIDaN)"><path fill="url(#svgIDaO)" class="a_yyribev"/></g><g filter="url(#svgIDaP)"><path class="e73d4fbat"/></g><path fill="url(#svgIDaQ)" class="xbx983bqi"/><path fill="url(#svgIDaR)" class="xbx983bqi"/><path fill="url(#svgIDaS)" class="c65lz4_ey"/><path fill="url(#svgIDaT)" class="c65lz4_ey"/><circle class="zhc1u6iwi"/><g filter="url(#svgIDaU)"><path clip-rule="evenodd" class="j7fotkb8x"/></g><circle fill="url(#svgIDaV)" transform="matrix(-1 0 0 1 12.14 16.739)" class="kr_eiac3t"/><g filter="url(#svgIDaW)"><path clip-rule="evenodd" class="sun98kbdi"/></g><path fill="url(#svgIDaX)" class="c-ymhfbrh"/><path fill="url(#svgIDaY)" class="c-ymhfbrh"/><g filter="url(#svgIDaZ)"><path class="wjwqx9b6j"/></g><path class="y_jvuobbm"/><path fill="url(#svgIDba)" class="qy5kkb6yn"/><g filter="url(#svgIDbb)"><path class="yrn5k97fg"/></g><path fill="url(#svgIDbc)" class="zdbmkmbsu"/><path fill="url(#svgIDbd)" class="zdbmkmbsu"/><path fill="url(#svgIDbe)" class="zdbmkmbsu"/><path fill="url(#svgIDbf)" class="zdbmkmbsu"/><path fill="url(#svgIDbg)" class="zdbmkmbsu"/><path fill="url(#svgIDbh)" class="mh1m83zfh"/><g filter="url(#svgIDbi)"><path class="zpw-ewjkj"/></g><path fill="url(#svgIDbj)" class="toow9ybtl"/><path fill="url(#svgIDbk)" class="s458q141g"/><g filter="url(#svgIDbl)"><path fill="url(#svgIDbm)" class="sc85l_sex"/><path fill="url(#svgIDbn)" class="sc85l_sex"/></g><path fill="url(#svgIDbo)" class="sc85l_sex"/><path fill="url(#svgIDbp)" class="sc85l_sex"/><path fill="url(#svgIDbq)" class="sc85l_sex"/><path fill="url(#svgIDbr)" class="sc85l_sex"/><path fill="url(#svgIDbs)" class="sc85l_sex"/><path fill="url(#svgIDbt)" class="sc85l_sex"/><path fill="url(#svgIDbu)" class="sc85l_sex"/><g filter="url(#svgIDbv)"><path class="t_og1nq1i"/></g><g filter="url(#svgIDbw)"><path class="y7cgsg_0a"/><path fill="url(#svgIDbx)" class="hkqzqkyse"/><path fill="url(#svgIDby)" class="hkqzqkyse"/><path fill="url(#svgIDbz)" class="hkqzqkyse"/><path fill="url(#svgIDbA)" class="hkqzqkyse"/><path fill="url(#svgIDbB)" class="hkqzqkyse"/></g><g filter="url(#svgIDbC)"><path stroke="url(#svgIDbD)" class="hx8d32wqh"/></g><path fill="url(#svgIDbE)" class="cm_s6nwgj"/><g filter="url(#svgIDbF)"><path fill="url(#svgIDbG)" class="ztz0hbbde"/><path fill="url(#svgIDbH)" class="ztz0hbbde"/><path fill="url(#svgIDbI)" class="ztz0hbbde"/><path fill="url(#svgIDbJ)" class="ztz0hbbde"/><path fill="url(#svgIDbK)" class="ztz0hbbde"/></g><g filter="url(#svgIDbL)"><path class="bjqk3ybib"/></g><g filter="url(#svgIDbM)"><path class="ekh8kmb6c"/></g><g filter="url(#svgIDbN)"><path class="cdww-0ftb"/><path fill="url(#svgIDbO)" class="b7eiottje"/><path fill="url(#svgIDbP)" class="b7eiottje"/></g><g filter="url(#svgIDbQ)"><path class="yr9gg9sqz"/><path fill="url(#svgIDbR)" class="buc5bqbpv"/><path fill="url(#svgIDbS)" class="buc5bqbpv"/></g><path class="ux762w7ju"/><path fill="url(#svgIDbT)" class="xztkdyboz"/><path class="i5ql9gb3i"/><g filter="url(#svgIDbU)"><path class="i788gkhqs"/><path fill="url(#svgIDbV)" class="lrzbaebay"/></g><g filter="url(#svgIDbW)"><path fill="url(#svgIDbX)" class="td29hv1-v"/></g><path class="s82a0vb9b"/><path fill="url(#svgIDbY)" class="jl_ztgb8s"/><path class="glenf8tqo"/><g filter="url(#svgIDbZ)"><path fill="url(#svgIDca)" class="tt45jv37g"/></g><g filter="url(#svgIDcb)" transform="rotate(-27.914 7.75 7.476)"><ellipse class="npsf425vt"/><ellipse fill="url(#svgIDcc)" class="f3xwz3b3w"/></g><path fill="url(#svgIDcd)" class="b5-3-5bcr"/><path fill="url(#svgIDce)" class="b5-3-5bcr"/><path fill="url(#svgIDcf)" class="b5-3-5bcr"/><path fill="url(#svgIDcg)" class="b5-3-5bcr"/><path fill="url(#svgIDch)" class="nirysbb4z"/><path fill="url(#svgIDci)" class="nirysbb4z"/><g filter="url(#svgIDcj)"><path fill="url(#svgIDck)" class="k4_dm2buu"/></g><g filter="url(#svgIDcl)"><path fill="url(#svgIDcm)" class="dxd6mpize"/></g><g filter="url(#svgIDcn)"><path class="sa-nikbch"/></g><g filter="url(#svgIDco)"><path class="vc1b4cchs"/></g><g filter="url(#svgIDcp)"><path class="nf32uab-d"/></g><g filter="url(#svgIDcq)"><path class="e-c-ph2vh"/></g><g filter="url(#svgIDcr)"><path class="ui16d5_tg"/></g><g filter="url(#svgIDcs)"><path fill="url(#svgIDct)" class="h7h8n338b"/></g><defs><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.062 34.625) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.249 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDj" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDl" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="ya-pfekwl"/><stop offset="1" class="lr5tnibbk"/></radialGradient><radialGradient id="svgIDs" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 22.556 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDu" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 18.493 3.115) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDv" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 10.284 10.168) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDw" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 23.02 -2.037) scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDx" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 21.38 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="y2o07bc4o"/><stop offset=".902" class="m0vc0tb7f"/></radialGradient><radialGradient id="svgIDz" cx="0" cy="0" r="1" gradientTransform="matrix(.32475 .87588 -1.04048 .38577 23.921 8.323)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="svgIDA" cx="0" cy="0" r="1" gradientTransform="matrix(.64035 .20125 -.62088 1.97552 19.233 8.536)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="svgIDC" cx="0" cy="0" r="1" gradientTransform="matrix(-2.26734 0 0 -4.01091 23.078 7.915)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="svgIDD" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 9.833 9.339) scale(1.46114 1.20629)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="svgIDF" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.0625 4.45908 0 21.852 10.967)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="svgIDG" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49805 .61633 0 22.921 7.346)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="matrix(.0017 -.4746 .51647 .00186 20.862 7.366)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 11.543 4.54) scale(3.69208 9.43141)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(1.46843 -1.26489 .37363 .43375 18.914 6.73)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="svgIDK" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 9.105 14.37) scale(1.08792 .43489)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="svgIDO" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10587 -.33273 0 22.062 8.505)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="svgIDQ" cx="0" cy="0" r="1" gradientTransform="rotate(155.37 10.155 6.543) scale(.72576 1.16637)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="svgIDU" cx="0" cy="0" r="1" gradientTransform="matrix(.94634 -.46525 1.8718 3.80734 21.647 9.486)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="svgIDX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.51854 3.84021 0 19.592 6.66)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="svgIDY" cx="0" cy="0" r="1" gradientTransform="matrix(.04946 -1.0897 1.93073 .08763 23.968 7.229)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02303 -.67285 .4939 -.75096 23.64 4.507)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="svgIDaa" cx="0" cy="0" r="1" gradientTransform="matrix(.29131 .51967 -1.20332 .67454 21.467 3.816)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="svgIDae" cx="0" cy="0" r="1" gradientTransform="matrix(-.95464 0 0 -.3543 21.97 4.796)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="svgIDaf" cx="0" cy="0" r="1" gradientTransform="matrix(1.39575 -2.2099 2.44835 1.54635 19.504 6.506)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="svgIDah" cx="0" cy="0" r="1" gradientTransform="matrix(1.16178 -1.1069 2.02643 2.1269 23.002 6.45)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(1.40877 .16466 -.06894 .58982 22.618 5.81)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="svgIDaj" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35145 -.55903 0 22.806 7.518)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="matrix(-.10046 -.12946 .17824 -.13831 22.707 7.554)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDao" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35147 -.55905 0 20.913 7.518)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDas" cx="0" cy="0" r="1" gradientTransform="matrix(-.00335 -.21403 .25727 -.00403 20.789 7.612)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDau" cx="0" cy="0" r="1" gradientTransform="matrix(.2726 .97292 -.92824 .26009 23.863 7.524)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="svgIDav" cx="0" cy="0" r="1" gradientTransform="matrix(.34166 -.46888 .39301 .28638 24.019 7.76)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="svgIDaw" cx="0" cy="0" r="1" gradientTransform="matrix(.25458 -.67243 .89845 .34016 24.068 7.835)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="svgIDay" cx="0" cy="0" r="1" gradientTransform="matrix(-.7192 0 0 -.80308 19.728 7.802)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="svgIDaA" cx="0" cy="0" r="1" gradientTransform="matrix(-.397 .06813 -.06985 -.40706 19.727 7.804)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="svgIDaQ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDaR" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.585 21.054) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.203 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.494 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="ya-pfekwl"/><stop offset="1" class="lr5tnibbk"/></radialGradient><radialGradient id="svgIDbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 9.51 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDbe" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 11.97 7.278) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDbf" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 3.762 7.838) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDbg" cx="0" cy="0" r="1" gradientTransform="matrix(.45766 -2.68928 1.12443 .19135 8.12 21)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 8.334 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="y2o07bc4o"/><stop offset=".902" class="m0vc0tb7f"/></radialGradient><radialGradient id="svgIDbj" cx="0" cy="0" r="1" gradientTransform="matrix(.32475 .87588 -1.04048 .38577 10.876 8.323)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="matrix(.64035 .20125 -.62088 1.97552 6.188 8.536)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="svgIDbm" cx="0" cy="0" r="1" gradientTransform="matrix(-2.26734 0 0 -4.01091 10.032 7.915)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 3.31 5.66) scale(1.46114 1.20629)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="svgIDbp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.0625 4.45908 0 8.807 10.967)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="svgIDbq" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49805 .61633 0 9.876 7.346)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="svgIDbr" cx="0" cy="0" r="1" gradientTransform="matrix(.0017 -.4746 .51647 .00186 7.818 7.366)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="svgIDbs" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 5.02 4.334) scale(3.69208 9.43141)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="matrix(1.46843 -1.26489 .37363 .43375 5.869 6.73)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="svgIDbu" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 2.582 8.432) scale(1.08792 .43489)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="svgIDby" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10587 -.33273 0 9.017 8.505)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="svgIDbA" cx="0" cy="0" r="1" gradientTransform="rotate(155.37 3.632 5.119) scale(.72576 1.16637)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="matrix(.94634 -.46525 1.8718 3.80734 8.601 9.486)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="svgIDbH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.51854 3.84021 0 6.547 6.66)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="svgIDbI" cx="0" cy="0" r="1" gradientTransform="matrix(.04946 -1.0897 1.93073 .08764 10.923 7.23)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="svgIDbJ" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 5.972 .667) scale(1.22447 .89883)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="svgIDbK" cx="0" cy="0" r="1" gradientTransform="matrix(.29131 .51967 -1.20332 .67454 8.422 3.816)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="svgIDbO" cx="0" cy="0" r="1" gradientTransform="matrix(-.95464 0 0 -.3543 8.924 4.796)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="svgIDbP" cx="0" cy="0" r="1" gradientTransform="matrix(1.39575 -2.2099 2.44835 1.54635 6.46 6.506)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="svgIDbR" cx="0" cy="0" r="1" gradientTransform="matrix(1.16178 -1.1069 2.02643 2.1269 9.957 6.45)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="svgIDbS" cx="0" cy="0" r="1" gradientTransform="matrix(1.40877 .16466 -.06894 .58982 9.573 5.81)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="svgIDbT" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35145 -.55903 0 9.76 7.518)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDbV" cx="0" cy="0" r="1" gradientTransform="matrix(-.10046 -.12946 .17824 -.13831 9.662 7.554)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDbY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35147 -.55905 0 7.868 7.518)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDcc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00335 -.21403 .25727 -.00403 7.744 7.612)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDce" cx="0" cy="0" r="1" gradientTransform="matrix(.2726 .97292 -.92824 .26009 10.818 7.524)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="svgIDcf" cx="0" cy="0" r="1" gradientTransform="matrix(.34166 -.46888 .39301 .28638 10.974 7.76)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="svgIDcg" cx="0" cy="0" r="1" gradientTransform="matrix(.25458 -.67243 .89845 .34016 11.023 7.835)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="svgIDci" cx="0" cy="0" r="1" gradientTransform="matrix(-.7192 0 0 -.80308 6.683 7.802)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="svgIDck" cx="0" cy="0" r="1" gradientTransform="matrix(-.397 .06813 -.06985 -.40706 6.683 7.803)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><filter id="svgIDa" width="3.097" height="9.794" x="18.86" y="20.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.360784 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/></filter><filter id="svgIDd" width="6.578" height="10.091" x="23.071" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.282353 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/></filter><filter id="svgIDf" width="4.976" height="9.579" x="24.041" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".25"/></filter><filter id="svgIDk" width="5.896" height="7.11" x="15.796" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.290196 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.305882 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDm" width="5.996" height="6.96" x="22.312" y="10.306" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.266667 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.298039 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDp" width="2.703" height="2.68" x="25.244" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".2"/></filter><filter id="svgIDr" width="9.692" height="11.056" x="17.71" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDy" width="2.793" height="3.034" x="16.366" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".2"/></filter><filter id="svgIDB" width="5.433" height="5.553" x="19.664" y="5.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDL" width="2.758" height="3.258" x="20.419" y="6.558" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".5"/></filter><filter id="svgIDM" width=".914" height="1.358" x="21.403" y="7.423" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".025"/></filter><filter id="svgIDS" width="1.896" height=".965" x="20.912" y="8.771" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".05"/></filter><filter id="svgIDV" width="5.583" height="3.907" x="19.068" y="3.578" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDab" width="1.071" height=".63" x="22.549" y="6.204" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/></filter><filter id="svgIDac" width="1.071" height=".623" x="20.269" y="6.211" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/></filter><filter id="svgIDad" width="2.939" height="2.66" x="19.181" y="4.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feGaussianBlur result="effect2_foregroundBlur_4002_709" stdDeviation=".075"/></filter><filter id="svgIDag" width="2.753" height="2.518" x="21.82" y="4.529" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".075"/></filter><filter id="svgIDak" width=".454" height=".415" x="22.431" y="7.27" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".05"/></filter><filter id="svgIDam" width=".613" height=".622" x="22.739" y="7.246" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".1"/></filter><filter id="svgIDap" width=".654" height=".677" x="20.812" y="7.219" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".1"/></filter><filter id="svgIDar" width=".509" height=".419" x="20.541" y="7.267" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".05"/></filter><filter id="svgIDaz" width=".859" height="1.314" x="19.081" y="7.145" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".125"/></filter><filter id="svgIDaB" width="1.41" height="1.825" x="23.503" y="6.887" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".25"/></filter><filter id="svgIDaD" width="1.117" height=".578" x="20.197" y="6.319" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".075"/></filter><filter id="svgIDaE" width="1.117" height=".578" x="22.487" y="6.299" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".075"/></filter><filter id="svgIDaF" width="3.133" height="2.153" x="21.816" y="4.291" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".375"/></filter><filter id="svgIDaG" width="1.73" height="2.911" x="19.728" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDaH" width="1.73" height="2.911" x="22.439" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDaI" width="4.792" height="2.36" x="19.703" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDaK" width="3.097" height="9.794" x="5.815" y="20.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.360784 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/></filter><filter id="svgIDaN" width="6.578" height="10.091" x="10.026" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.282353 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/></filter><filter id="svgIDaP" width="4.976" height="9.579" x="10.996" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".25"/></filter><filter id="svgIDaU" width="5.896" height="7.11" x="2.751" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.290196 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.305882 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDaW" width="5.996" height="6.96" x="9.267" y="10.306" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.266667 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.298039 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDaZ" width="2.703" height="2.68" x="12.199" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".2"/></filter><filter id="svgIDbb" width="9.692" height="11.056" x="4.665" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDbi" width="2.793" height="3.034" x="3.321" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".2"/></filter><filter id="svgIDbl" width="5.433" height="5.553" x="6.618" y="5.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDbv" width="2.758" height="3.258" x="7.374" y="6.558" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".5"/></filter><filter id="svgIDbw" width=".914" height="1.358" x="8.357" y="7.423" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".025"/></filter><filter id="svgIDbC" width="1.896" height=".965" x="7.866" y="8.771" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".05"/></filter><filter id="svgIDbF" width="5.583" height="3.907" x="6.023" y="3.578" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDbL" width="1.071" height=".63" x="9.504" y="6.204" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/></filter><filter id="svgIDbM" width="1.071" height=".623" x="7.224" y="6.211" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/></filter><filter id="svgIDbN" width="2.939" height="2.66" x="6.136" y="4.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feGaussianBlur result="effect2_foregroundBlur_4002_709" stdDeviation=".075"/></filter><filter id="svgIDbQ" width="2.753" height="2.518" x="8.775" y="4.529" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".075"/></filter><filter id="svgIDbU" width=".454" height=".415" x="9.386" y="7.27" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".05"/></filter><filter id="svgIDbW" width=".613" height=".622" x="9.694" y="7.246" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".1"/></filter><filter id="svgIDbZ" width=".654" height=".677" x="7.767" y="7.219" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".1"/></filter><filter id="svgIDcb" width=".509" height=".419" x="7.496" y="7.267" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".05"/></filter><filter id="svgIDcj" width=".859" height="1.314" x="6.036" y="7.145" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".125"/></filter><filter id="svgIDcl" width="1.41" height="1.825" x="10.458" y="6.887" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".25"/></filter><filter id="svgIDcn" width="1.117" height=".578" x="7.152" y="6.319" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".075"/></filter><filter id="svgIDco" width="1.117" height=".578" x="9.442" y="6.299" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".075"/></filter><filter id="svgIDcp" width="3.133" height="2.153" x="8.771" y="4.291" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_709" stdDeviation=".375"/></filter><filter id="svgIDcq" width="1.73" height="2.911" x="6.683" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDcr" width="1.73" height="2.911" x="9.394" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><filter id="svgIDcs" width="4.792" height="2.36" x="6.658" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_709"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_709" result="effect2_innerShadow_4002_709"/></filter><linearGradient id="svgIDb" x1="18.96" x2="20.861" y1="24.13" y2="24.279" gradientUnits="userSpaceOnUse"><stop class="mch9zegwt"/><stop offset="1" class="x4y51kb4t"/></linearGradient><linearGradient id="svgIDc" x1="18.852" x2="19.399" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="w2ejlbckb"/><stop offset="1" class="s_plahh6j"/></linearGradient><linearGradient id="svgIDe" x1="25.173" x2="27.361" y1="24.154" y2="23.31" gradientUnits="userSpaceOnUse"><stop class="dx14qxbsv"/><stop offset="1" class="ce26eet6g"/></linearGradient><linearGradient id="svgIDn" x1="18.383" x2="19.305" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDo" x1="18.899" x2="18.539" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDq" x1="25.133" x2="25.571" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDt" x1="18.774" x2="19.446" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDE" x1="24.096" x2="23" y1="8.646" y2="8.646" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="svgIDN" x1="22.223" x2="21.86" y1="8.208" y2="8.223" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="svgIDP" x1="21.86" x2="21.86" y1="8.702" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="svgIDR" x1="21.86" x2="21.86" y1="7.529" y2="7.766" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="svgIDT" x1="21.338" x2="21.477" y1="9.383" y2="9.021" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="svgIDW" x1="24.832" x2="19.795" y1="5.459" y2="5.459" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="svgIDan" x1="23.143" x2="23.007" y1="7.541" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDaq" x1="21.236" x2="21.1" y1="7.541" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDat" x1="24.651" x2="24.128" y1="7.553" y2="8.496" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="svgIDax" x1="19.323" x2="19.955" y1="7.858" y2="7.803" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="svgIDaC" x1="24.208" x2="24.208" y1="7.387" y2="8.212" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="svgIDaJ" x1="23.743" x2="20.243" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient><linearGradient id="svgIDaL" x1="5.915" x2="7.815" y1="24.13" y2="24.279" gradientUnits="userSpaceOnUse"><stop class="mch9zegwt"/><stop offset="1" class="x4y51kb4t"/></linearGradient><linearGradient id="svgIDaM" x1="5.807" x2="6.354" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="w2ejlbckb"/><stop offset="1" class="s_plahh6j"/></linearGradient><linearGradient id="svgIDaO" x1="12.128" x2="14.315" y1="24.154" y2="23.31" gradientUnits="userSpaceOnUse"><stop class="dx14qxbsv"/><stop offset="1" class="ce26eet6g"/></linearGradient><linearGradient id="svgIDaX" x1="5.338" x2="6.26" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDaY" x1="5.854" x2="5.495" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDba" x1="12.088" x2="12.526" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDbd" x1="5.729" x2="6.401" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDbo" x1="11.051" x2="9.954" y1="8.646" y2="8.646" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="svgIDbx" x1="9.178" x2="8.815" y1="8.208" y2="8.223" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="svgIDbz" x1="8.815" x2="8.815" y1="8.702" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="svgIDbB" x1="8.815" x2="8.815" y1="7.529" y2="7.766" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="svgIDbD" x1="8.293" x2="8.431" y1="9.383" y2="9.021" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="svgIDbG" x1="11.786" x2="6.75" y1="5.459" y2="5.459" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="svgIDbX" x1="10.098" x2="9.962" y1="7.541" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDca" x1="8.19" x2="8.055" y1="7.541" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDcd" x1="11.606" x2="11.083" y1="7.553" y2="8.496" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="svgIDch" x1="6.278" x2="6.91" y1="7.858" y2="7.803" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="svgIDcm" x1="11.163" x2="11.163" y1="7.387" y2="8.212" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="svgIDct" x1="10.698" x2="7.198" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-bunny-ears-medium-dark" /></template>
<style>
.a_yyribev {
  d: path("m12.729 19.942l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.167-.234l-3.465-9.857Z");
}

.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b0c6xjbyb {
  d: path("m25.774 19.942l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.398 1.534c.121 0 .206-.12.166-.234l-3.465-9.857Z");
}

.b1pd8upnt {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
}

.b5-3-5bcr {
  d: path("M10.95 8.496c.028-.461.056-.922.08-1.384a.698.698 0 0 1-.08 1.384Z");
}

.b7eiottje {
  d: path("M8.915 5.48c-.01-.02-.02-.04-.028-.06a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.732c0-.465.339-.7.555-.85c.061-.042.112-.078.143-.11l.044-.045c.151-.161.421-.448.893-.573c.065-.017.131-.03.196-.041c.467-.076.807.343.807.816v.185l-.009.006Z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bjqk3ybib {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M10.433 6.623a.805.805 0 0 0-.298-.179c-.132-.041-.297-.052-.526-.024a.12.12 0 1 0 .03.238c.208-.025.336-.012.424.016c.086.027.144.07.212.13a.12.12 0 0 0 .158-.181Z");
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.bqhl8ltyr {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
}

.buc5bqbpv {
  d: path("m11.075 6.896l-.012-.273a.637.637 0 0 0-.61-.619h-.607a1.05 1.05 0 0 1-.921-.546s.313-.898.827-.766c.364.093.752.233 1.057.433a1.15 1.15 0 0 1 .266 1.771Z");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c-ymhfbrh {
  d: path("m5.26 13.39l2.828-1.586a.8.8 0 0 0-.781-1.396l-2.86 1.612l.814 1.37Z");
}

.c2d4a5g8l {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m21.694 7.605l-.23.798c-.048.164.065.328.225.328h.341c.16 0 .273-.167.226-.328l-.23-.798c-.05-.176-.28-.176-.332 0Z");
}

.c65lz4_ey {
  d: path("M15.63 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.166-.234l-.563-1.607Z");
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cdww-0ftb {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("M8.915 5.48c-.01-.02-.02-.04-.028-.06a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.732c0-.465.339-.7.555-.85c.061-.042.112-.078.143-.11l.044-.045c.151-.161.421-.448.893-.573c.065-.017.131-.03.196-.041c.467-.076.807.343.807.816v.185l-.009.006Z");
}

.ce26eet6g {
  stop-color: var(--svg-color--967267, #967267);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm_s6nwgj {
  d: path("M8.814 9.171c-.22 0-.427-.052-.6-.142c-.06-.03-.124.037-.086.09a.82.82 0 0 0 .686.367a.821.821 0 0 0 .687-.367c.037-.056-.026-.12-.086-.09c-.174.09-.378.142-.6.142Z");
}

.db11z6bdb {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M20.38 6.575a1.203 1.203 0 0 1 .754-.156a.12.12 0 0 1-.029.24a.963.963 0 0 0-.634.144l-.007.005h-.001a.12.12 0 0 1-.147-.19l.064-.043Z");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.djrsqybxo {
  d: path("M22.807 7.31a.387.387 0 0 1 .372.49h-.747a.388.388 0 0 1 .374-.489Z");
}

.dljw9bc0b {
  stroke: var(--svg-color--866a64, #866A64);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.985 13.917c-.088.073-.193.29.094.57a70.98 70.98 0 0 0 1.555 1.415");
}

.dpxwbi0bi {
  d: path("M20.912 7.31a.387.387 0 0 0-.373.49h.747a.39.39 0 0 0-.374-.489Z");
}

.dqz42kghw {
  fill: var(--svg-color--745249, #745249);
  fill-rule: evenodd;
  d: path("M21.44 10.716a.8.8 0 0 1-.307 1.088l-3.527 1.978a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 1 1-1.069 1.19l-1.973-1.72c-.93-.82-.855-2.148.348-2.917l3.574-2.015a.8.8 0 0 1 1.089.308Z");
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.dt8z2pq0g {
  d: path("M21.266 7.652c0-.125-.102-.208-.13-.233l-.124.12l.077.157l.177-.044Z");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dx14qxbsv {
  stop-color: var(--svg-color--84565a, #84565A);
}

.dxd6mpize {
  d: path("m10.958 8.212l.048-.825a.414.414 0 0 1-.048.825Z");
}

.e-c-ph2vh {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M6.936 3.273c.222.71.522 1.166.645 1.305l.632-.242c-.013-.183-.096-.709-.324-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e73d4fbat {
  fill: var(--svg-color--9c7870, #9C7870);
  d: path("m11.496 20.164l.823-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.ecm9b1coi {
  d: path("M24.093 5.75c.019.097-.102.145-.167.071c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.034 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.ekh8kmb6c {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M7.335 6.575a1.203 1.203 0 0 1 .754-.156a.12.12 0 1 1-.029.24a.963.963 0 0 0-.634.144l-.007.005h-.001a.12.12 0 0 1-.148-.19l.065-.043Z");
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f_grh3duv {
  d: path("m24.003 8.212l.048-.825a.414.414 0 0 1-.048.825Z");
}

.f3xwz3b3w {
  cx: 7.75px;
  cy: 7.476px;
  rx: 0.169px;
  ry: 0.085px;
}

.f8pmzbbav {
  d: path("M19.654 7.395a.414.414 0 0 0 .036.815a34.081 34.081 0 0 1-.036-.815Z");
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fj5yx3bkn {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("M21.96 5.48c-.01-.02-.02-.04-.028-.06a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.732c0-.465.339-.7.555-.85c.061-.042.112-.078.143-.11l.044-.045c.151-.161.421-.448.893-.573c.066-.017.131-.03.196-.041c.467-.076.808.343.808.816v.185l-.01.006Z");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.fr658ly7x {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m22.546 9.12l.063.041a.135.135 0 0 0-.015-.171a.142.142 0 0 0-.167-.028h-.001a1.222 1.222 0 0 1-.566.134c-.209 0-.404-.049-.566-.134h-.001a.141.141 0 0 0-.168.029a.134.134 0 0 0-.014.17c.159.24.435.4.749.4s.59-.16.749-.4l-.063-.042Zm0 0a.821.821 0 0 1-.686.366a.821.821 0 0 1-.687-.367c-.037-.053.026-.12.086-.09c.174.09.38.142.6.142c.223 0 .428-.052.602-.142c.059-.03.123.034.085.09Z");
}

.ft5dv1b6b {
  fill: none;
}

.g1-cakgjb {
  d: path("m20.928 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.g6a574b3m {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M21.832 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.22 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.g9r0e3b5l {
  cx: 20.795px;
  cy: 7.476px;
  rx: 0.169px;
  ry: 0.085px;
}

.glenf8tqo {
  fill: var(--svg-color--000, #000);
  d: path("M8.089 7.698a.22.22 0 0 0-.222-.222a.22.22 0 0 0-.197.324h.392a.22.22 0 0 0 .027-.102Z");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h7h8n338b {
  d: path("M11.048 5.75c.019.097-.101.145-.167.071c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.034 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
}

.hkkby1b0v {
  fill: var(--svg-color--000, #000);
  d: path("M22.585 7.698a.22.22 0 0 1 .222-.222a.22.22 0 0 1 .196.324h-.391a.2.2 0 0 1-.027-.102Z");
}

.hkqzqkyse {
  d: path("m8.649 7.605l-.23.798c-.048.164.065.328.225.328h.341c.16 0 .273-.167.226-.328l-.23-.798c-.05-.176-.28-.176-.332 0Z");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hx8d32wqh {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m9.501 9.12l.062.041a.135.135 0 0 0-.015-.171a.142.142 0 0 0-.167-.028a1.222 1.222 0 0 1-.567.134c-.208 0-.403-.049-.566-.134a.141.141 0 0 0-.168.029a.134.134 0 0 0-.015.17c.16.24.435.4.75.4c.314 0 .59-.16.749-.4L9.5 9.119Zm0 0a.821.821 0 0 1-.687.366a.821.821 0 0 1-.686-.367c-.038-.053.026-.12.085-.09c.174.09.381.142.601.142c.223 0 .427-.052.601-.142c.06-.03.123.034.086.09Z");
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i5ql9gb3i {
  fill: var(--svg-color--000, #000);
  d: path("M9.54 7.698a.22.22 0 0 1 .222-.222a.22.22 0 0 1 .197.324h-.392a.2.2 0 0 1-.027-.102Z");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i788gkhqs {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.733 7.393c.028.037-.03.082-.096.13c-.065.05-.114.084-.141.047c-.028-.037.003-.106.069-.155c.065-.05.14-.06.168-.022Z");
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ipmv6inso {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.404 6.677a1.003 1.003 0 0 0-.717-.166");
}

.iyrh5w2dl {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M23.816 3.273c-.221.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.403.078 1.29Z");
}

.j7fotkb8x {
  fill: var(--svg-color--745249, #745249);
  fill-rule: evenodd;
  d: path("M8.395 10.716a.8.8 0 0 1-.307 1.088L4.56 13.782a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.973-1.72c-.93-.82-.855-2.148.347-2.917l3.575-2.015a.8.8 0 0 1 1.088.308Z");
}

.j7sojhblo {
  d: path("m25.549 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.jaeg0gihu {
  d: path("m21.662 11.775l-.865-1.505h2.125l-.824 1.5a.25.25 0 0 1-.436.005Z");
}

.jct6q3bgk {
  cx: 18.559px;
  cy: 16.61px;
  r: 0.766px;
  fill: var(--svg-color--693a42, #693A42);
}

.jdxsh3blt {
  stop-color: var(--svg-color--221630, #221630);
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.jj65vhdzq {
  stop-color: var(--svg-color--635a6d, #635A6D);
}

.jl_ztgb8s {
  d: path("M7.867 7.31a.387.387 0 0 0-.373.49h.747a.39.39 0 0 0-.374-.489Z");
}

.jum30v1nu {
  stop-color: var(--svg-color--42384b, #42384B);
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.k4_dm2buu {
  d: path("M6.609 7.395a.414.414 0 0 0 .036.815a33.77 33.77 0 0 1-.036-.815Z");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kdy9aobnt {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m21.686 7.69l-.256.797c-.044.164.06.328.21.328h.317c.149 0 .254-.166.21-.328l-.215-.797c-.046-.177-.218-.177-.266 0Z");
}

.kr_eiac3t {
  r: 0.766px;
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.l01j3pbwi {
  d: path("M23.968 8.457a.712.712 0 0 0 .392-.134v.404c0 .387-.23.733-.581.876c.074-.158.124-.329.15-.512l.039-.634Z");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l7791cb7a {
  fill: var(--svg-color--9c7870, #9C7870);
  d: path("m24.54 20.164l.824-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.l9173fpsg {
  d: path("m24.12 6.896l-.012-.273a.637.637 0 0 0-.61-.619h-.607a1.05 1.05 0 0 1-.921-.546s.313-.898.827-.766c.364.093.752.233 1.058.433a1.15 1.15 0 0 1 .265 1.771Z");
}

.ldd357aax {
  d: path("m18.305 13.39l2.828-1.586a.8.8 0 0 0-.781-1.396l-2.86 1.612l.813 1.37Z");
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lr5tnibbk {
  stop-color: var(--svg-color--744160, #744160);
}

.lrzbaebay {
  d: path("M9.733 7.393c.028.037-.03.082-.096.13c-.065.05-.114.084-.141.047c-.028-.037.003-.106.069-.155c.065-.05.14-.06.168-.022Z");
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m0vc0tb7f {
  stop-color: var(--svg-color--825f59, #825F59);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mch9zegwt {
  stop-color: var(--svg-color--7b504e, #7B504E);
}

.mh1m83zfh {
  d: path("m8.617 11.775l-.865-1.505h2.125l-.825 1.5a.25.25 0 0 1-.435.005Z");
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.mngobgbzy {
  fill: var(--svg-color--605071, #605071);
  d: path("m25.549 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.mz2-1bfbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.897 7.193c.283 0 .522.195.587.46a.119.119 0 0 1-.116.147h-.967a.1.1 0 0 1-.1-.118a.608.608 0 0 1 .596-.489Z");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n366y7b2s {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nf32uab-d {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M10.633 5.46h-.902a.21.21 0 1 1 .033-.417c.234.038.545.09.753.141c.471.117.601.346.638.51a.657.657 0 0 0-.522-.234Z");
}

.nirysbb4z {
  d: path("M6.627 7.107a.698.698 0 0 0 .056 1.39a33.93 33.93 0 0 1-.056-1.39Z");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.npsf425vt {
  cx: 7.75px;
  cy: 7.476px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.085px;
}

.nr62m8bsb {
  fill: var(--svg-color--000, #000);
  d: path("M21.134 7.698a.22.22 0 0 0-.222-.222a.22.22 0 0 0-.197.324h.392a.22.22 0 0 0 .027-.102Z");
}

.nykqrqb8m {
  d: path("M21.832 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.22 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ok2_u5b_w {
  d: path("M22.778 7.393c.027.037-.03.082-.096.13c-.065.05-.114.084-.141.047c-.028-.037.003-.106.069-.155c.065-.05.14-.06.168-.022Z");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.ozea8lbrw {
  cx: 20.795px;
  cy: 7.476px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.085px;
}

.p_gmsk5sh {
  d: path("M21.96 5.48c-.01-.02-.02-.04-.028-.06a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.732c0-.465.339-.7.555-.85c.061-.042.112-.078.143-.11l.044-.045c.151-.161.421-.448.893-.573c.066-.017.131-.03.196-.041c.467-.076.808.343.808.816v.185l-.01.006Z");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q_um76bvk {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M23.678 5.46h-.902a.21.21 0 1 1 .033-.417c.234.038.545.09.753.141c.471.117.601.346.637.51a.657.657 0 0 0-.521-.234Z");
}

.qgz62l2ld {
  stop-color: var(--svg-color--443553, #443553);
}

.qhg47wyku {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
  stop-opacity: 0;
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qut0ht_ps {
  d: path("m5.915 20.239l2.997.27l-1.063 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V20.24Z");
}

.qvlyoocen {
  d: path("M19.751 8.457a.711.711 0 0 1-.392-.134v.404c0 .387.23.733.581.876a1.775 1.775 0 0 1-.15-.512l-.039-.634Z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.qy5kkb6yn {
  d: path("m12.504 13.39l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.rei3gtbmc {
  d: path("M19.672 7.107a.698.698 0 0 0 .056 1.39a33.967 33.967 0 0 1-.056-1.39Z");
}

.rk3eawbja {
  fill: var(--svg-color--815a5c, #815A5C);
  fill-rule: evenodd;
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.974-1.72c.93-.82.855-2.148-.348-2.917l-3.574-2.015a.8.8 0 0 0-1.089.308Z");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rq-cvac7p {
  d: path("M19.767 9.114a1.698 1.698 0 0 0 1.685 1.477h.819c.853 0 1.573-.63 1.685-1.477c.051-.817.102-1.63.14-2.447a.629.629 0 0 0-.598-.62h-.607a1.05 1.05 0 0 1-.96-.627a.288.288 0 0 0-.266-.181h-.552c-.8 0-1.45.656-1.45 1.465c0 .807.051 1.601.104 2.41Z");
}

.s_plahh6j {
  stop-color: var(--svg-color--774d4a, #774D4A);
  stop-opacity: 0;
}

.s458q141g {
  d: path("M6.706 8.457a.711.711 0 0 1-.392-.134v.404c0 .387.23.733.581.876a1.773 1.773 0 0 1-.15-.512l-.039-.634Z");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.s82a0vb9b {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.778 7.193a.606.606 0 0 0-.588.46a.119.119 0 0 0 .116.147h.968a.1.1 0 0 0 .098-.118a.608.608 0 0 0-.594-.489Z");
}

.sa-nikbch {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.352 6.697c.11-.08.388-.22.717-.166");
}

.sc85l_sex {
  d: path("M6.722 9.114a1.698 1.698 0 0 0 1.685 1.477h.818a1.7 1.7 0 0 0 1.686-1.477c.05-.817.102-1.63.14-2.447a.629.629 0 0 0-.598-.62h-.607a1.05 1.05 0 0 1-.96-.627a.288.288 0 0 0-.266-.181h-.552c-.8 0-1.45.656-1.45 1.465c0 .807.05 1.601.104 2.41Z");
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.skdh8c8wf {
  d: path("m18.96 20.239l2.997.27l-1.063 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V20.24Z");
}

.sn_vbz34j {
  d: path("m21.694 7.605l-.23.798c-.048.164.065.328.225.328h.341c.16 0 .273-.167.226-.328l-.23-.798c-.05-.176-.28-.176-.332 0Z");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sun98kbdi {
  fill: var(--svg-color--815a5c, #815A5C);
  fill-rule: evenodd;
  d: path("M9.369 10.716a.8.8 0 0 0 .307 1.088l3.527 1.978a.2.2 0 0 1 .035.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.575-2.015a.8.8 0 0 0-1.088.308Z");
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t_og1nq1i {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m8.64 7.69l-.256.797c-.043.164.062.328.21.328h.318c.149 0 .254-.166.21-.328l-.215-.797c-.046-.177-.218-.177-.266 0Z");
}

.t1dkn1b9a {
  d: path("M21.86 9.171c-.22 0-.427-.052-.601-.142c-.06-.03-.123.037-.086.09a.82.82 0 0 0 .687.367a.821.821 0 0 0 .686-.367c.038-.056-.026-.12-.085-.09c-.174.09-.379.142-.601.142Z");
}

.tagzx62qg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.778 7.393c.027.037-.03.082-.096.13c-.065.05-.114.084-.141.047c-.028-.037.003-.106.069-.155c.065-.05.14-.06.168-.022Z");
}

.td29hv1-v {
  d: path("M10.106 7.647a.363.363 0 0 0-.1-.2l-.112.123l.05.099l.162-.022Z");
}

.tfw8ds16k {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M19.982 3.273c.221.71.522 1.166.644 1.305l.633-.242c-.013-.183-.096-.709-.324-1.356c-.286-.808-.579-1.09-.875-.996c-.211.086-.356.403-.078 1.29Z");
}

.th19h-bzp {
  d: path("M23.151 7.647a.364.364 0 0 0-.1-.2l-.112.123l.05.099l.162-.022Z");
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.tjubatb2f {
  d: path("M28.675 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.398 1.534c.12 0 .206-.12.166-.234l-.564-1.607Z");
}

.toow9ybtl {
  d: path("M10.923 8.457a.711.711 0 0 0 .392-.134v.404c0 .387-.23.733-.581.876a1.83 1.83 0 0 0 .15-.512l.039-.634Z");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tt45jv37g {
  d: path("M8.22 7.652c0-.125-.101-.208-.129-.233l-.124.12l.076.157l.178-.044Z");
}

.u_6vs988p {
  d: path("M23.965 5.034a1.028 1.028 0 0 1 .504 1.552a.676.676 0 0 0-.117.379v.515a.756.756 0 0 0-.29-.116l.034-.697a.629.629 0 0 0-.598-.621h-.607a1.05 1.05 0 0 1-.959-.626a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465l.014.667a.741.741 0 0 0-.312.114v-.52a.676.676 0 0 0-.117-.38a1.037 1.037 0 0 1-.063-1.06c.127-.24.332-.407.564-.489c.248-.088.46-.255.6-.481a1.008 1.008 0 0 1 1.254-.396a.646.646 0 0 0 .518 0a1.008 1.008 0 0 1 1.258.41a1.1 1.1 0 0 0 .586.465Z");
}

.uf4taw41y {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M23.479 6.623a.805.805 0 0 0-.298-.179c-.132-.041-.298-.052-.526-.024a.12.12 0 1 0 .029.238c.209-.025.336-.012.424.016a.56.56 0 0 1 .213.13a.12.12 0 0 0 .158-.181Z");
}

.ui16d5_tg {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M10.771 3.273c-.221.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.286-.808.579-1.09.875-.996c.211.086.356.403.079 1.29Z");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.ux762w7ju {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.851 7.193c.284 0 .523.195.588.46a.119.119 0 0 1-.116.147h-.968a.1.1 0 0 1-.098-.118a.605.605 0 0 1 .594-.489Z");
}

.v5hncxoqr {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M20.397 6.697c.111-.08.389-.22.717-.166");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vc1b4cchs {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.359 6.677a1.003 1.003 0 0 0-.717-.166");
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w0h64fbkw {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.823 7.193a.606.606 0 0 0-.588.46a.119.119 0 0 0 .116.147h.968a.1.1 0 0 0 .098-.118a.608.608 0 0 0-.594-.489Z");
}

.w2ejlbckb {
  stop-color: var(--svg-color--876058, #876058);
}

.w838mqvgb {
  d: path("M23.994 8.496c.029-.461.056-.922.08-1.384a.698.698 0 0 1-.08 1.384Z");
}

.wjwqx9b6j {
  stroke: var(--svg-color--8d6d67, #8D6D67);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m12.724 12.31l1.083.627c.194.1.579.44.57 1.002");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x4y51kb4t {
  stop-color: var(--svg-color--906665, #906665);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xbx983bqi {
  d: path("m7.883 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xztkdyboz {
  d: path("M9.761 7.31a.387.387 0 0 1 .373.49h-.747a.388.388 0 0 1 .374-.489Z");
}

.y_jvuobbm {
  fill: var(--svg-color--605071, #605071);
  d: path("m12.504 13.39l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.y2o07bc4o {
  stop-color: var(--svg-color--5d302d, #5D302D);
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7cgsg_0a {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m8.649 7.605l-.23.798c-.048.164.065.328.225.328h.341c.16 0 .273-.167.226-.328l-.23-.798c-.05-.176-.28-.176-.332 0Z");
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.ya-pfekwl {
  stop-color: var(--svg-color--7b575a, #7B575A);
}

.yr9gg9sqz {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m11.075 6.896l-.012-.273a.637.637 0 0 0-.61-.619h-.607a1.05 1.05 0 0 1-.921-.546s.313-.898.827-.766c.364.093.752.233 1.057.433a1.15 1.15 0 0 1 .266 1.771Z");
}

.yramohxcj {
  stroke: var(--svg-color--8d6d67, #8D6D67);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m25.77 12.31l1.083.627c.193.1.578.44.569 1.002");
}

.yrn5k97fg {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M8.787 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.z_3wb62rz {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m24.12 6.896l-.012-.273a.637.637 0 0 0-.61-.619h-.607a1.05 1.05 0 0 1-.921-.546s.313-.898.827-.766c.364.093.752.233 1.058.433a1.15 1.15 0 0 1 .265 1.771Z");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zdbmkmbsu {
  d: path("M8.787 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.zhc1u6iwi {
  cx: 5.514px;
  cy: 16.61px;
  r: 0.766px;
  fill: var(--svg-color--693a42, #693A42);
}

.zoz3lmrqj {
  stop-color: var(--svg-color--453457, #453457);
}

.zpw-ewjkj {
  stroke: var(--svg-color--866a64, #866A64);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.94 13.917c-.088.073-.193.29.094.57a70.94 70.94 0 0 0 1.555 1.415");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.ztz0hbbde {
  d: path("M10.92 5.034a1.028 1.028 0 0 1 .504 1.552a.676.676 0 0 0-.117.379v.515a.757.757 0 0 0-.29-.116l.034-.697a.629.629 0 0 0-.598-.621h-.607a1.05 1.05 0 0 1-.96-.626a.288.288 0 0 0-.266-.181h-.552c-.8 0-1.45.656-1.45 1.465l.014.667a.742.742 0 0 0-.312.114v-.52a.676.676 0 0 0-.118-.38a1.037 1.037 0 0 1-.062-1.06c.127-.24.332-.407.564-.489c.248-.088.46-.255.6-.481a1.009 1.009 0 0 1 1.254-.396a.646.646 0 0 0 .517 0a1.009 1.009 0 0 1 1.258.41c.134.22.343.381.587.465Z");
}

</style>
