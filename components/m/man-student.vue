<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="lqgktmetw"/><path fill="url(#i0ssoBc)" class="sqbx5-bjt"/><path fill="url(#iiN0cte)" class="sqbx5-bjt"/><path fill="url(#iwDW5hc)" class="zxisq0b_m"/><path fill="url(#iWu21Qb)" class="zxisq0b_m"/><path fill="url(#i2sJtZb)" class="zxisq0b_m"/><path fill="url(#i4jceMe)" class="zxisq0b_m"/><path fill="url(#iGZUHMe)" class="zxisq0b_m"/><path fill="url(#isJO9xR)" class="zxisq0b_m"/><path fill="url(#iUUjnMc)" class="zdpn-zbus"/><path fill="url(#izv7bQb)" class="aq5bf9ajg"/><path fill="url(#ivSHDxe)" class="aq5bf9ajg"/><path fill="url(#isyfNYb)" class="flni28b2z"/><path fill="url(#i2B6F5b)" class="flni28b2z"/><g filter="url(#i1yuMNb)"><path stroke="url(#i0iJDlc)" class="m-tij_b-t"/></g><path fill="url(#iYWTold)" class="m92q0sm-z"/><path fill="url(#i7Gk8oc)" class="m92q0sm-z"/><path fill="url(#iaK8Ybe)" class="m92q0sm-z"/><path fill="url(#iAAerKe)" class="m92q0sm-z"/><path fill="url(#i2Wx4kb)" class="m92q0sm-z"/><path fill="url(#iE2ztmb)" class="sfl9u3bfl"/><path fill="url(#ibB2wpb)" class="sfl9u3bfl"/><path fill="url(#itgxi2b)" class="sfl9u3bfl"/><path fill="url(#i4IC80c)" class="yymjxhb0t"/><path fill="url(#iL4Sc5d)" class="yymjxhb0t"/><g filter="url(#iC1cGUb)"><path fill="url(#iMNIfme)" class="jc_bjpdyk"/><path fill="url(#iMNIfme)" class="g6x4imulk"/><path fill="url(#iMNIfme)" class="cy9apvb-x"/></g><g filter="url(#iHhWuMb)"><path stroke="url(#iYqtwlY)" class="fhicmrbrr"/></g><circle fill="url(#iQgg8Zb)" class="hop8bmbam"/><g filter="url(#ixiAwnc)"><circle fill="url(#isSS5Ab)" class="v8nlr3bvu"/></g><g filter="url(#iaszMLe)"><circle fill="url(#itbFpkb)" class="b7ikvib_s"/><circle fill="url(#iJkEAbc)" class="b7ikvib_s"/></g><g filter="url(#iLq4kub)"><circle class="w8cq4acll"/><circle fill="url(#iYQAIrd)" class="h1qily0bw"/><circle fill="url(#iw5njCb)" class="h1qily0bw"/></g><path fill="url(#imCF5Mc)" class="jav6hkkdf"/><path fill="url(#iiLzekc)" class="jav6hkkdf"/><path fill="url(#iUdS7Zd)" class="jav6hkkdf"/><path fill="url(#i63iSFc)" class="jav6hkkdf"/><path fill="url(#i7qRKte)" class="jav6hkkdf"/><path fill="url(#iasJ2Pe)" class="jav6hkkdf"/><g filter="url(#ihHQtjd)"><path class="gcvohqbug"/><path fill="url(#iezWYNd)" class="b_5xlbb_u"/><path fill="url(#iZLQQCC)" class="b_5xlbb_u"/><path fill="url(#irPllUq)" class="b_5xlbb_u"/><path fill="url(#ipp4R7b)" class="b_5xlbb_u"/><path fill="url(#iZySJhe)" class="b_5xlbb_u"/><path fill="url(#ii1mIQd)" class="b_5xlbb_u"/></g><path fill="url(#iPKc36e)" class="xl_s9abom"/><path fill="url(#ibiwsId)" class="xl_s9abom"/><path fill="url(#iOhMARd)" class="xl_s9abom"/><g filter="url(#iIQaz3c)"><path class="dzg-1llaq"/></g><g filter="url(#iu6APPc)"><path class="wlhk7vb-e"/><path fill="url(#iu340Md)" class="fxm65gbla"/><path fill="url(#iH4IMzb)" class="fxm65gbla"/><path fill="url(#iZXvQAe)" class="fxm65gbla"/></g><path fill="url(#iRWULkc)" class="fxm65gbla"/><g filter="url(#itHVQhc)"><path stroke="url(#icL8wbk)" class="orvkk9b8c"/></g><path class="q-2a-qbgg"/><path class="i1f6qebjw"/><path fill="url(#ixEZaRc)" class="mvde6-bsq"/><path class="ev6marbqx"/><g filter="url(#iBOZSJc)"><path class="f3kb0zboa"/><path fill="url(#ilURN8b)" class="pz4y-ccsa"/></g><g filter="url(#iFq0jwb)"><path fill="url(#i6vZKhb)" class="r9p9e7qnq"/></g><path class="i3tug7bks"/><path fill="url(#i7vMlPe)" class="iv8bm9bvz"/><path class="vlk6h93pc"/><g filter="url(#iliFuHc)"><path fill="url(#iCw61DZ)" class="uvbgnb0_t"/></g><g filter="url(#iVfcNkf)"><ellipse transform="rotate(-27.914 13.623 9.681)" class="xsapf8f6e"/><ellipse fill="url(#iSnQ5we)" transform="rotate(-27.914 13.623 9.681)" class="m8gztdv8z"/></g><g filter="url(#iVgzu8d)"><path clip-rule="evenodd" class="o8u8jsboy"/></g><g filter="url(#iusRL9u)"><path class="gbxa0bckl"/></g><g filter="url(#igtNjjd)"><path clip-rule="evenodd" class="aqd110bff"/></g><g filter="url(#iDx04tc)"><path class="abkeg2_ef"/></g><path fill="url(#iZnNSHb)" class="usyqshb4b"/><path fill="url(#iRGi0Db)" class="zklzq-tli"/><path fill="url(#iPOXAoM)" class="zklzq-tli"/><path fill="url(#iNqZVze)" class="zklzq-tli"/><defs><radialGradient id="i0ssoBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.422 23.035)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="iiN0cte" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 8.828 21.38)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="iwDW5hc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.128 21.27)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="iWu21Qb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.12 16.816)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="i2sJtZb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 15.703 15.473)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="i4jceMe" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.453 15.238)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="iGZUHMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.12 23.535)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="isJO9xR" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.85937 -5.04205 0 16.12 15.238)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iUUjnMc" cx="0" cy="0" r="1" gradientTransform="rotate(-163.355 10.235 7.568)scale(1.58191 3.34381)" gradientUnits="userSpaceOnUse"><stop class="zy5hoab9j"/><stop offset="1" class="fdcdqxcao"/></radialGradient><radialGradient id="ivSHDxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 24.695 11.588)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="isyfNYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 24.953 11.96)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="i2B6F5b" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.616 12.352)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="i7Gk8oc" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.176 8.503)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iaK8Ybe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.453 13.027)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="i2Wx4kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.453 16.816)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="iE2ztmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.125 29.916)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="ibB2wpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 8.89 29.916)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="i4IC80c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.232 29.916)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iL4Sc5d" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.182 23.077)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iQgg8Zb" cx="0" cy="0" r="1" gradientTransform="matrix(1.76854 0 0 3.09496 9.63 10.465)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iJkEAbc" cx="0" cy="0" r="1" gradientTransform="matrix(.83315 -.60666 .69242 .95093 21.275 10.198)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iYQAIrd" cx="0" cy="0" r="1" gradientTransform="matrix(.82766 -1.5223 .89101 .48444 20.858 11.293)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iw5njCb" cx="0" cy="0" r="1" gradientTransform="matrix(.2613 .25866 -.33344 .33686 20.9 10.465)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iUdS7Zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.65254 -9.87962 0 16.592 8.862)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="q-w-jrbfr"/><stop offset="1" class="p94yzs4ht"/></radialGradient><radialGradient id="i63iSFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31727 1.62125 0 18.462 9.184)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="i7qRKte" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40171 1.74315 0 13.868 9.15)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iasJ2Pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.59698 -8.89048 0 15.15 3.601)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="r94d9d5nm"/><stop offset="1" class="pain93i6r"/></radialGradient><radialGradient id="iezWYNd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4634 4.46385 -7.59118 -5.8898 19.819 2.692)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="irPllUq" cx="0" cy="0" r="1" gradientTransform="matrix(-.18593 -2.00803 .9862 -.09131 11.93 6.799)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="ipp4R7b" cx="0" cy="0" r="1" gradientTransform="rotate(-66.4 16.837 -11.197)scale(2.16269 1.76384)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iZySJhe" cx="0" cy="0" r="1" gradientTransform="matrix(1.00052 1.24146 -1.09613 .8834 15.316 1.797)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="ii1mIQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4623 -3.0593 1.05703 .50524 20.319 6.213)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iPKc36e" cx="0" cy="0" r="1" gradientTransform="matrix(.2632 1.02282 -1.68156 .43272 16.798 1.797)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="ibiwsId" cx="0" cy="0" r="1" gradientTransform="matrix(1.11558 1.6114 -3.35328 2.3215 11.681 3.067)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="iOhMARd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.26364 3.27234 -4.09463 -9.08888 17.26 6.067)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="icL8wbk" cx="0" cy="0" r="1" gradientTransform="rotate(-87.754 15.55 -1.072)scale(.63265 1.89793)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="ixEZaRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9102 -1.077 0 18.293 10.114)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ilURN8b" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.447 .508)scale(.38075 .52421)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i7vMlPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91024 -1.07705 0 13.896 10.114)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iSnQ5we" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.725 -1.699)scale(.49737 .59785)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZnNSHb" cx="0" cy="0" r="1" gradientTransform="rotate(-102.428 11.877 -4.565)scale(3.92058 20.9164)" gradientUnits="userSpaceOnUse"><stop class="pok8-dbcp"/><stop offset="1" class="x49zttk2i"/></radialGradient><radialGradient id="iPOXAoM" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 21.86 2.316)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="iNqZVze" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 6.89 2.941)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><linearGradient id="izv7bQb" x1="23.81" x2="24.996" y1="8.862" y2="8.862" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="i0iJDlc" x1="25.056" x2="25.056" y1="3.629" y2="11.397" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="iYWTold" x1="25.605" x2="23.285" y1="14.727" y2="14.727" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iAAerKe" x1="23.404" x2="24.279" y1="14.406" y2="14.586" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="itgxi2b" x1="9.035" x2="8.609" y1="27.985" y2="27.985" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iMNIfme" x1="16.12" x2="16.12" y1="29.785" y2="23.352" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="iYqtwlY" x1="13.072" x2="13.644" y1="4.367" y2="5.704" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="isSS5Ab" x1="11.313" x2="10.667" y1="10.746" y2="10.746" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="itbFpkb" x1="21.995" x2="21.17" y1="9.365" y2="11.921" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="imCF5Mc" x1="20.165" x2="12.469" y1="10.858" y2="12.005" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iiLzekc" x1="10.66" x2="12.99" y1="13.575" y2="13.271" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iZLQQCC" x1="11.199" x2="14.123" y1="10.196" y2="5.001" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iu340Md" x1="15.227" x2="16.172" y1="11.522" y2="11.522" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iH4IMzb" x1="17.043" x2="16.01" y1="11.847" y2="11.832" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iZXvQAe" x1="16.294" x2="16.294" y1="12.595" y2="12.018" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iRWULkc" x1="16.224" x2="16.224" y1="12.637" y2="12.469" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="i6vZKhb" x1="19.077" x2="18.761" y1="9.832" y2="10.027" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCw61DZ" x1="14.645" x2="14.329" y1="9.832" y2="10.026" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRGi0Db" x1="17.89" x2="16.609" y1="3.879" y2="-.496" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient><filter id="i1yuMNb" width=".65" height="8.268" x="24.231" y="3.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".125"/></filter><filter id="iC1cGUb" width="8.964" height="6.734" x="11.638" y="23.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".075"/></filter><filter id="iHhWuMb" width="1.172" height="2.394" x="12.772" y="3.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".125"/></filter><filter id="ixiAwnc" width="3.005" height="3.005" x="9.81" y="8.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".25"/></filter><filter id="iaszMLe" width="3.615" height="3.615" x="19.218" y="8.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1581"/></filter><filter id="iLq4kub" width="3.005" height="3.005" x="19.398" y="8.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".25"/></filter><filter id="ihHQtjd" width="12.693" height="8.144" x="9.748" y="1.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1581"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1581" result="effect2_innerShadow_4002_1581"/></filter><filter id="iIQaz3c" width="3.274" height="4.202" x="14.22" y="9.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".375"/></filter><filter id="iu6APPc" width="2.391" height="3.202" x="14.902" y="9.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".125"/></filter><filter id="itHVQhc" width="3.643" height="1.481" x="14.276" y="13.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".05"/></filter><filter id="iBOZSJc" width=".791" height=".7" x="17.554" y="9.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".05"/></filter><filter id="iFq0jwb" width=".895" height=".917" x="18.402" y="9.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".1"/></filter><filter id="iliFuHc" width=".99" height="1.045" x="13.925" y="9.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".1"/></filter><filter id="iVfcNkf" width=".918" height=".708" x="13.164" y="9.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".05"/></filter><filter id="iVgzu8d" width="2.622" height="1.658" x="17.371" y="7.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.266667 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1581"/></filter><filter id="iusRL9u" width="2.32" height="1.106" x="17.522" y="7.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".125"/></filter><filter id="igtNjjd" width="2.622" height="1.658" x="12.202" y="7.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.266667 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1581"/></filter><filter id="iDx04tc" width="2.32" height="1.106" x="12.353" y="7.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1581" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-student" /></template>
<style>
.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.abkeg2_ef {
  stroke: var(--svg-color--b06552, #B06552);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.678 8.1c.21-.194.809-.524 1.67-.443");
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.aq5bf9ajg {
  d: path("M24.853 11.588V2.726h-.8v8.862z");
}

.aqd110bff {
  fill: var(--svg-color--a74c2f, #A74C2F);
  fill-rule: evenodd;
  d: path("M14.304 8.243c-.725-.068-1.19.215-1.303.319a.476.476 0 0 1-.645-.7c.308-.285 1.04-.66 2.037-.567a.476.476 0 0 1-.089.948");
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.b_5xlbb_u {
  d: path("m20.954 3.937l.289.223c.756.376 1.333 1.228 1.17 2.142l-.594 3.064c-.053.316-.262.53-.576.537c.036-.507.069-1.326.082-1.456c.044-.436-.025-.565-.425-.962c-.216-.215-.378-.538-.378-.86v-.86c0-.27-.217-.484-.433-.538c-.649-.161-2-.43-3.946-.43s-3.298.269-3.946.43a.524.524 0 0 0-.433.538v.86c0 .322-.108.645-.378.86l-.162.16c-.217.162-.326.499-.326.768c.015.156.036 1.06.06 1.435a.64.64 0 0 1-.6-.536l-.594-3.064c-.108-.86.325-1.72 1.081-2.096c1.022-.448 1.394-1.128 2.217-1.827c.594-.538 1.46-.302 2.216.074a2.95 2.95 0 0 0 1.676 0c.81-.268 1.73-.45 2.378.14l.811.807c.216.269.487.43.811.591");
}

.b7ikvib_s {
  cx: 20.9px;
  cy: 10.465px;
  r: 1.682px;
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clg68gimn {
  stop-color: var(--svg-color--f9b72a, #F9B72A);
}

.codehtz3g {
  stop-color: var(--svg-color--db9820, #DB9820);
  stop-opacity: 0;
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.cy9apvb-x {
  d: path("M19.76 23.692c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.691z");
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dzg-1llaq {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.82 10.342l-.827 1.713c-.102.352.144.705.492.705h.743c.349 0 .595-.358.492-.705l-.502-1.713c-.108-.38-.285-.38-.398 0");
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ev6marbqx {
  fill: var(--svg-color--000, #000);
  d: path("M17.78 10.197c0-.286.23-.515.515-.515a.513.513 0 0 1 .458.752h-.911a.47.47 0 0 1-.061-.237");
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f3kb0zboa {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.229 9.488c.064.085-.07.19-.222.303c-.152.114-.265.194-.33.109c-.063-.086.008-.248.16-.361c.152-.114.328-.137.392-.051");
}

.fdcdqxcao {
  stop-color: var(--svg-color--b57a1d, #B57A1D);
}

.fhicmrbrr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.072 4.006c.025.255.246 1.214.572 1.795");
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.flni28b2z {
  d: path("M24.053 11.565a.838.838 0 1 0 .8 0z");
}

.ft5dv1b6b {
  fill: none;
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.fxm65gbla {
  d: path("m15.712 10.178l-.535 1.712a.543.543 0 0 0 .524.705h.793a.545.545 0 0 0 .524-.705l-.535-1.712c-.115-.38-.65-.38-.77 0");
}

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.g6x4imulk {
  d: path("M15.774 23.692c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.692z");
}

.gbxa0bckl {
  stroke: var(--svg-color--b06552, #B06552);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.517 8.1c-.21-.194-.809-.524-1.67-.443");
}

.gcvohqbug {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m20.954 3.937l.289.223c.756.376 1.333 1.228 1.17 2.142l-.594 3.064c-.053.316-.262.53-.576.537c.036-.507.069-1.326.082-1.456c.044-.436-.025-.565-.425-.962c-.216-.215-.378-.538-.378-.86v-.86c0-.27-.217-.484-.433-.538c-.649-.161-2-.43-3.946-.43s-3.298.269-3.946.43a.524.524 0 0 0-.433.538v.86c0 .322-.108.645-.378.86l-.162.16c-.217.162-.326.499-.326.768c.015.156.036 1.06.06 1.435a.64.64 0 0 1-.6-.536l-.594-3.064c-.108-.86.325-1.72 1.081-2.096c1.022-.448 1.394-1.128 2.217-1.827c.594-.538 1.46-.302 2.216.074a2.95 2.95 0 0 0 1.676 0c.81-.268 1.73-.45 2.378.14l.811.807c.216.269.487.43.811.591");
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

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.h1qily0bw {
  cx: 20.9px;
  cy: 10.465px;
  r: 1.003px;
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hop8bmbam {
  cx: 11.313px;
  cy: 10.465px;
  r: 1.682px;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i1f6qebjw {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.504 9.023c.658 0 1.214.454 1.365 1.067a.276.276 0 0 1-.27.344h-2.248a.232.232 0 0 1-.229-.274a1.41 1.41 0 0 1 1.382-1.137");
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i3tug7bks {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.686 9.023c-.658 0-1.214.454-1.365 1.067a.276.276 0 0 0 .27.344h2.248a.232.232 0 0 0 .229-.274a1.41 1.41 0 0 0-1.382-1.137");
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.iv8bm9bvz {
  d: path("M13.894 9.297a.9.9 0 0 0-.866 1.137h1.737a1 1 0 0 0 .033-.237a.905.905 0 0 0-.904-.9");
}

.jav6hkkdf {
  d: path("M10.958 9.848a30 30 0 0 1-.059-1.45c0-.269.109-.591.325-.752l.162-.162c.27-.215.378-.537.378-.86v-.86c0-.268.163-.483.433-.537c.649-.161 2-.43 3.946-.43s3.297.269 3.946.43c.216.054.433.269.433.537v.86c0 .323.162.645.378.86c.506.355.475.55.433.968c-.013.13-.054 1.204-.09 1.45l-.268 3.99c-.162 1.784-1.564 3.027-3.236 3.027h-3.235c-1.726 0-3.074-1.243-3.235-3.027z");
}

.jc_bjpdyk {
  d: path("M11.788 23.692c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.69z");
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqgktmetw {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.125 15.416c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.m-tij_b-t {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.556 3.63v7.767");
}

.m8gztdv8z {
  cx: 13.623px;
  cy: 9.681px;
  rx: 0.392px;
  ry: 0.198px;
}

.m92q0sm-z {
  d: path("m23.6 13.526l-.517 2.238a.45.45 0 0 0 .445.552h1.863a.45.45 0 0 0 .43-.558l-.542-2.239a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
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

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mvde6-bsq {
  d: path("M18.296 9.297a.9.9 0 0 1 .866 1.137h-1.737a.903.903 0 0 1 .87-1.136");
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o8u8jsboy {
  fill: var(--svg-color--a74c2f, #A74C2F);
  fill-rule: evenodd;
  d: path("M17.891 8.243c.726-.068 1.19.215 1.304.319a.476.476 0 0 0 .645-.7c-.309-.285-1.04-.66-2.037-.567a.476.476 0 0 0 .088.948");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.orvkk9b8c {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.098 13.62c-.512 0-.992-.121-1.396-.332c-.138-.07-.287.086-.2.211c.338.511.926.852 1.596.852s1.257-.34 1.595-.852c.087-.13-.062-.28-.2-.21c-.403.21-.879.33-1.395.33Z");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.p94yzs4ht {
  stop-color: var(--svg-color--9d660d, #9D660D);
}

.pain93i6r {
  stop-color: var(--svg-color--fba929, #FBA929);
  stop-opacity: 0;
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pk_j5sfiy {
  stop-color: var(--svg-color--33203c, #33203C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.pok8-dbcp {
  stop-color: var(--svg-color--534d5b, #534D5B);
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.pz4y-ccsa {
  d: path("M18.229 9.488c.064.085-.07.19-.222.303c-.152.114-.265.194-.33.109c-.063-.086.008-.248.16-.361c.152-.114.328-.137.392-.051");
}

.q-2a-qbgg {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.098 13.62c-.512 0-.992-.121-1.396-.332c-.138-.07-.287.086-.2.211c.338.511.926.852 1.596.852s1.257-.34 1.595-.852c.087-.13-.062-.28-.2-.21c-.403.21-.879.33-1.395.33");
}

.q-w-jrbfr {
  stop-color: var(--svg-color--e09d29, #E09D29);
  stop-opacity: 0;
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r94d9d5nm {
  stop-color: var(--svg-color--b17012, #B17012);
}

.r9p9e7qnq {
  d: path("M19.097 10.078a.85.85 0 0 0-.234-.466l-.261.287l.118.23z");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
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

.sfl9u3bfl {
  d: path("M8.89 29.916V18.129a10.97 10.97 0 0 0-3.765 8.287v3.5z");
}

.sqbx5-bjt {
  d: path("M16.125 15.416c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.ud98q8dic {
  stop-color: var(--svg-color--c57e10, #C57E10);
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.usyqshb4b {
  d: path("m9.887 5.168l1.253-1.992l9.75-.11l1.36 2.063c-4.664 1.61-10.274.773-12.363.039");
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uvbgnb0_t {
  d: path("M14.715 10.09c0-.29-.236-.484-.3-.542l-.29.28l.179.364z");
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v8nlr3bvu {
  cx: 11.313px;
  cy: 10.465px;
  r: 1.003px;
}

.vlk6h93pc {
  fill: var(--svg-color--000, #000);
  d: path("M14.41 10.197a.513.513 0 0 0-.516-.515a.513.513 0 0 0-.457.752h.911a.5.5 0 0 0 .061-.237");
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.w8cq4acll {
  cx: 20.9px;
  cy: 10.465px;
  r: 1.003px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wlhk7vb-e {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.712 10.178l-.535 1.712a.543.543 0 0 0 .524.705h.793a.545.545 0 0 0 .524-.705l-.535-1.712c-.115-.38-.65-.38-.77 0");
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x49zttk2i {
  stop-color: var(--svg-color--2b2135, #2B2135);
}

.xl_s9abom {
  d: path("m20.954 3.937l.289.234c.756.376 1.333 1.217 1.17 2.13l-.594 3.064c-.053.317-.262.53-.576.538c.036-.508.069-1.327.082-1.456c.044-.436-.025-.565-.425-.963c-.216-.215-.378-.537-.378-.86v-.86c0-.269-.217-.484-.433-.537c-.649-.162-2-.43-3.946-.43s-3.298.268-3.946.43a.524.524 0 0 0-.433.537v.86c0 .323-.108.645-.378.86l-.162.161c-.217.162-.326.499-.326.767c.015.157.036 1.06.06 1.436a.64.64 0 0 1-.6-.536l-.594-3.064c-.108-.86.325-1.72 1.081-2.096c1.022-.448 1.394-1.128 2.217-1.828c.594-.537 1.46-.376 2.216 0a2.95 2.95 0 0 0 1.676 0c.81-.268 1.73-.376 2.378.215l.811.807c.216.268.487.43.811.59");
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xsapf8f6e {
  cx: 13.623px;
  cy: 9.681px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.392px;
  ry: 0.198px;
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yn026ikmt {
  stop-color: var(--svg-color--df8f14, #DF8F14);
  stop-opacity: 0;
}

.yymjxhb0t {
  d: path("M23.35 29.916V18.129a10.97 10.97 0 0 1 3.765 8.287v3.5z");
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zdpn-zbus {
  d: path("M15.826 18.786c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.764 1.89 1.78 2.587");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zklzq-tli {
  d: path("M24.063 3.526H8.093c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

.zxisq0b_m {
  d: path("M23.141 18.015a.24.24 0 0 0-.059-.29c-1.856-1.603-4.346-2.487-6.954-2.487s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.014 7.013-4.614");
}

.zy5hoab9j {
  stop-color: var(--svg-color--dcad1e, #DCAD1E);
}

</style>
