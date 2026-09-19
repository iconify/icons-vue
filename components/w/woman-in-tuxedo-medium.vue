<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#imMxrDc)"><path fill="url(#ikiZnFN)" clip-rule="evenodd" class="tint2qbqx"/><path fill="url(#igckEwc)" clip-rule="evenodd" class="tint2qbqx"/><path fill="url(#i2bQgac)" clip-rule="evenodd" class="tint2qbqx"/><path fill="url(#i3lPNIc)" clip-rule="evenodd" class="tint2qbqx"/><path fill="url(#iD5ekVR)" clip-rule="evenodd" class="tint2qbqx"/><path fill="url(#iFvSqyc)" clip-rule="evenodd" class="tint2qbqx"/><path fill="url(#iNASNMb)" clip-rule="evenodd" class="tint2qbqx"/><path fill="url(#ii9Wgud)" clip-rule="evenodd" class="tint2qbqx"/><path fill="url(#iFhgQ5b)" clip-rule="evenodd" class="tint2qbqx"/><path fill="url(#itQvI7d)" clip-rule="evenodd" class="tint2qbqx"/><path fill="url(#iFvWMxc)" clip-rule="evenodd" class="tint2qbqx"/><path fill="url(#iH83w3d)" clip-rule="evenodd" class="tint2qbqx"/></g><path fill="url(#iOTSjsd)" class="iwijhb8cc"/><path fill="url(#iVt7Kmd)" class="iwijhb8cc"/><path fill="url(#ijJWFGd)" class="iwijhb8cc"/><path fill="url(#iuyr1tn)" class="iwijhb8cc"/><path fill="url(#iwTkvTT)" class="iwijhb8cc"/><path fill="url(#iGY3pLe)" class="z77pc-39f"/><path fill="url(#iOmSTFf)" class="z77pc-39f"/><g filter="url(#iYlGLsc)"><path fill="url(#iHafYHb)" class="uoh3u9bsv"/><path fill="url(#irRAuOe)" class="uoh3u9bsv"/></g><path fill="url(#iosNevc)" class="bv7-wxb3q"/><g filter="url(#iXfXYFd)"><path fill="url(#i0qUINb)" class="wsuqc2bol"/><path fill="url(#iDSTCFe)" class="wsuqc2bol"/></g><g filter="url(#i8xi8Yo)"><path clip-rule="evenodd" class="nzd5pi4db"/></g><path fill="url(#iQD9ace)" class="pwzf73bct"/><path fill="url(#iulJYbe)" class="pwzf73bct"/><path fill="url(#i4qDnic)" class="pwzf73bct"/><path fill="url(#ig0Fqhd)" class="pwzf73bct"/><path fill="url(#i3hbZ4w)" class="d0ocvmu4d"/><path fill="url(#ivP7kqb)" class="d0ocvmu4d"/><path fill="url(#iwDR1wV)" class="d0ocvmu4d"/><path fill="url(#i1L7Mpd)" class="d0ocvmu4d"/><g filter="url(#iz10bAc)"><path fill="url(#i6XAUBd)" class="d60lbkuym"/></g><g filter="url(#iCkEKgc)"><path fill="url(#iLOUAXd)" class="dj5l2yqzg"/></g><path fill="url(#iHd26xe)" class="dj5l2yqzg"/><path fill="url(#iZCJqXd)" class="dj5l2yqzg"/><path fill="url(#ixvOk5d)" class="dj5l2yqzg"/><g filter="url(#ixkMEhb)"><path class="wga2pr3ix"/></g><g filter="url(#iLEqJOe)"><circle class="mvlg1lb-a"/></g><g filter="url(#igBi5sb)"><circle class="tao08pzef"/></g><g filter="url(#iRAWfxe)"><circle fill="url(#iGv238b)" class="qsy44ybab"/></g><g filter="url(#iyLnJMc)"><circle fill="url(#iUdTZPc)" class="zgcak206m"/></g><rect fill="url(#ii62Mrk)" class="epgmjx2er"/><rect fill="url(#i3NUdZc)" class="epgmjx2er"/><rect fill="url(#iEUF6Mc)" class="epgmjx2er"/><rect fill="url(#i7Xz5wb)" class="epgmjx2er"/><g filter="url(#i9YEYIe)"><path fill="url(#i7lfzIe)" class="o-ok2ibcd"/></g><path fill="url(#iBWIq2c)" class="o-ok2ibcd"/><g filter="url(#izmFu6R)"><path class="ku2lh6uuy"/><path fill="url(#isKdouB)" class="pbpjm1bhy"/><path fill="url(#iXYh5ub)" class="pbpjm1bhy"/><path fill="url(#ipN7wmd)" class="pbpjm1bhy"/></g><g filter="url(#il6n8ad)"><circle fill="url(#icPlPbd)" class="wui8nqfgb"/><circle fill="url(#iAsT4et)" class="wui8nqfgb"/></g><path fill="url(#if4vDlY)" class="lmkyvq38o"/><path fill="url(#iZ5HQbe)" class="dc_z0_bxw"/><g filter="url(#iakVaEy)"><path fill="url(#i8KqZZM)" class="jrtmrs0np"/></g><path fill="url(#itDJIRd)" class="jrtmrs0np"/><g filter="url(#iLyFMac)"><path fill="url(#ijNaNyd)" class="houfji2bh"/><path fill="url(#itjR49c)" class="houfji2bh"/></g><g filter="url(#iBwUZWd)"><path class="qfl6_gbdv"/><path fill="url(#ibp61ye)" class="x7qb6jv9m"/></g><g filter="url(#ixXaxlc)"><path class="pe2dttu3s"/><path fill="url(#i3aDMFb)" class="tmzj3tblv"/></g><g filter="url(#i05rSCd)"><path fill="url(#iDPPKZd)" class="s76wahyla"/><path fill="url(#itSkxse)" class="s76wahyla"/><path fill="url(#iD2OVkc)" class="s76wahyla"/><path fill="url(#iTLPvYh)" class="s76wahyla"/><path fill="url(#ixvATXD)" class="s76wahyla"/><path fill="url(#igTSOpd)" class="s76wahyla"/><path fill="url(#iUVca7d)" class="s76wahyla"/><path fill="url(#iFMQGEc)" class="s76wahyla"/></g><path fill="url(#iklsDIc)" class="s76wahyla"/><g filter="url(#itFn9gd)"><path class="gealwgbpb"/></g><g filter="url(#i7IAH0a)"><path class="d22uk9b1z"/><path fill="url(#iy2Pbbe)" class="kzfo1kqfu"/><path fill="url(#iPdMedc)" class="kzfo1kqfu"/><path fill="url(#iS09dsb)" class="kzfo1kqfu"/><path fill="url(#iWwbriX)" class="kzfo1kqfu"/></g><g filter="url(#ityylwv)"><path stroke="url(#ikZu3Np)" class="huaycxbmm"/></g><path class="j8cr-ub1e"/><g filter="url(#iVPL2Px)"><path class="au0ieex0a"/></g><g filter="url(#i9Httke)"><path class="brc_i4brl"/></g><g filter="url(#iUy4HYE)"><path class="gg5t8ab9x"/></g><g filter="url(#iJFdeSd)"><path clip-rule="evenodd" class="k7b007bvi"/></g><path class="gtv1wwfmn"/><path fill="url(#icRIRud)" class="pee7z8bbo"/><path class="v8vbew4_g"/><g filter="url(#iQhtIkb)"><path class="mnd5zcc-c"/><path fill="url(#iyVP5Gb)" class="vh3uzfb2k"/></g><g filter="url(#it7eAPd)"><path fill="url(#ihk4Q0b)" class="pxehlrooi"/></g><path class="n_ddxdbzc"/><path fill="url(#iZqUeob)" class="acv0-54tn"/><path class="lij47b-vj"/><g filter="url(#ivFwFFd)"><path fill="url(#ic0v1Vc)" class="xzv69vbgz"/></g><g filter="url(#iPIwuwy)"><ellipse transform="rotate(-27.914 13.594 9.862)" class="v_27a5b7h"/><ellipse fill="url(#i88IAcd)" transform="rotate(-27.914 13.594 9.862)" class="sa32mmbla"/></g><g filter="url(#iHX6snX)"><path class="b71vjdbnr"/></g><g filter="url(#iRiEttc)"><path class="bo-7t2vcz"/></g><g filter="url(#iK5FQic)"><path class="ovsgk5bgw"/><path fill="url(#idnUljd)" class="rvf49obnj"/><path fill="url(#ikGdu5c)" class="rvf49obnj"/></g><g filter="url(#ivs4Goe)"><path class="m95ojfb9w"/><path fill="url(#isN7bBF)" class="pi6jtfb-k"/><path fill="url(#iCmrVbb)" class="pi6jtfb-k"/></g><g filter="url(#ib9nDbb)"><path stroke="url(#iZnWb7j)" class="n_qk5go9m"/></g><g filter="url(#ivWn9Ne)"><path class="fpjy3ccwl"/></g><defs><radialGradient id="igckEwc" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.746 13.056)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="i2bQgac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.93 13.324)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="i3lPNIc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.94 8.157)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iD5ekVR" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.375 7.643)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iFvSqyc" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.198 11.617)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="iNASNMb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.993 6.82)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="ii9Wgud" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.557 9.704)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iFhgQ5b" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.669 7.974)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="itQvI7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.90444 -2.65026 2.0962 -.71536 20.78 7.27)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="iFvWMxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.906 9.668)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iH83w3d" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.182 -3.945)scale(3.79787 1.37073)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iOTSjsd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.376)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="iVt7Kmd" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.756 10.843)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="ijJWFGd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.287)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iGY3pLe" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.271 2.64)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iOmSTFf" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.187)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="iHafYHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.443)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="iosNevc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.599)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="i0qUINb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.568)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iDSTCFe" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.33 13.055)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="iulJYbe" cx="0" cy="0" r="1" gradientTransform="rotate(-148.052 10.537 8.072)scale(1.21384 4.09383)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="i4qDnic" cx="0" cy="0" r="1" gradientTransform="matrix(.7959 -.2721 .77398 2.26394 13.24 18.359)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="ivP7kqb" cx="0" cy="0" r="1" gradientTransform="rotate(16.487 -55.161 68.502)scale(1.44847 6.30545)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iwDR1wV" cx="0" cy="0" r="1" gradientTransform="matrix(-.2731 .4204 -1.76025 -1.14347 17.274 19.237)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="iLOUAXd" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.073 11.886)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="iHd26xe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91837 1.77673 -4.30254 -2.22394 13.135 16.373)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="iZCJqXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.92462 -.4885 0 11.747 16.431)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="ixvOk5d" cx="0" cy="0" r="1" gradientTransform="rotate(86.901 -5.602 15.98)scale(1.69986 .36274)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iGv238b" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.862 16.074)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iUdTZPc" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.48 14.57)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="i3NUdZc" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.54688 1.51805 2.0819 14.294 18.047)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="vau5mebxn"/><stop offset="1" class="tz6_frehs"/></radialGradient><radialGradient id="iEUF6Mc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.74927 .5625 -.2661 -1.30057 16.012 15.917)" gradientUnits="userSpaceOnUse"><stop offset=".389" class="fac_1yexe"/><stop offset="1" class="i-laxlbsd"/></radialGradient><radialGradient id="i7Xz5wb" cx="0" cy="0" r="1" gradientTransform="matrix(2.82813 .3069 -.49372 4.54966 15.497 17.266)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="p14jg0bhe"/><stop offset="1" class="dec65me-m"/></radialGradient><radialGradient id="i7lfzIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.79)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="iBWIq2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.166)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="iXYh5ub" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.448 6.885)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="ipN7wmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 19.021)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="icPlPbd" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.362 12.614)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iAsT4et" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.38)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="itDJIRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6537 -1.20346 1.36368 -.74073 10.969 12.164)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="ijNaNyd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.087 10.994)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="itjR49c" cx="0" cy="0" r="1" gradientTransform="matrix(1.20681 0 0 .5196 20.992 8.849)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="ibp61ye" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.439 10.668)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="i3aDMFb" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.723 5.278)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iDPPKZd" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.354 7.083)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="itSkxse" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.866 7.33)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iD2OVkc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.885 16.525)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iTLPvYh" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.49535 -9.29389 0 15.786 9.48)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="r07konbna"/><stop offset=".95" class="h0k4mmrtw"/></radialGradient><radialGradient id="ixvATXD" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.358 6.742)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="igTSOpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.349 9.6)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iUVca7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.971 9.37)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iFMQGEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.43 7.283)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iklsDIc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.143 11.087)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iy2Pbbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.832 11.813)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iWwbriX" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.592 12.025)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="icRIRud" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.23 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iyVP5Gb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.001 10.042)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZqUeob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.865 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i88IAcd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.8 -1.596)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idnUljd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.3 -4.174)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="ikGdu5c" cx="0" cy="0" r="1" gradientTransform="matrix(1.14952 -1.97524 1.06043 .61714 12.097 6.857)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="isN7bBF" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.152 6.96)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iCmrVbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.258 3)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="imMxrDc" width="15.268" height="15.768" x="8.538" y="1.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="iYlGLsc" width="4.081" height="11.683" x="5.07" y="18.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="iXfXYFd" width="5.909" height="14.117" x="12.858" y="15.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="i8xi8Yo" width="7.13" height="5.229" x="12.285" y="16.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".3"/></filter><filter id="iz10bAc" width="7.239" height="14.645" x="9.195" y="15.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".5"/></filter><filter id="iCkEKgc" width="5.917" height="14.259" x="10.326" y="15.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3330" result="effect2_innerShadow_4002_3330"/></filter><filter id="ixkMEhb" width="6.567" height="14.209" x="15.297" y="15.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3330" result="effect2_innerShadow_4002_3330"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3330" result="effect3_innerShadow_4002_3330"/></filter><filter id="iLEqJOe" width="2" height="2" x="14.731" y="24.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".25"/></filter><filter id="igBi5sb" width="2" height="2" x="14.731" y="21.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".25"/></filter><filter id="iRAWfxe" width="1.05" height="1.05" x="15.504" y="25.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="iyLnJMc" width="1.05" height="1.05" x="15.504" y="22.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="i9YEYIe" width="2.465" height="2.95" x="16.029" y="17.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3330" result="effect2_innerShadow_4002_3330"/></filter><filter id="izmFu6R" width="2.365" height="2.9" x="13.731" y="17.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="il6n8ad" width="1.717" height="1.717" x="15.204" y="17.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="iakVaEy" width="3.368" height="3.218" x="9.753" y="8.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="iLyFMac" width="3.218" height="3.468" x="19.265" y="8.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="iBwUZWd" width="3.148" height="3.148" x="19.301" y="8.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".25"/></filter><filter id="ixXaxlc" width="2.848" height="2.848" x="9.957" y="9.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".175"/></filter><filter id="i05rSCd" width="10.191" height="11.127" x="10.952" y="5.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="itFn9gd" width="2.877" height="3.682" x="14.446" y="9.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".25"/></filter><filter id="i7IAH0a" width="2.377" height="3.182" x="14.859" y="9.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".125"/></filter><filter id="ityylwv" width="3.702" height="1.526" x="14.196" y="12.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".05"/></filter><filter id="iVPL2Px" width="3.001" height="1.285" x="16.989" y="9.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="i9Httke" width="3.001" height="1.285" x="12.104" y="9.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="iUy4HYE" width="2.453" height="1.091" x="12.239" y="7.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="iJFdeSd" width="2.453" height="1.091" x="17.657" y="7.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/></filter><filter id="iQhtIkb" width=".787" height=".696" x="17.495" y="9.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".05"/></filter><filter id="it7eAPd" width=".891" height=".913" x="18.335" y="9.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".1"/></filter><filter id="ivFwFFd" width=".986" height="1.04" x="13.892" y="9.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".1"/></filter><filter id="iPIwuwy" width=".913" height=".705" x="13.138" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".05"/></filter><filter id="iHX6snX" width="2.261" height=".978" x="17.687" y="7.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".1"/></filter><filter id="iRiEttc" width="2.261" height=".978" x="12.235" y="7.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".1"/></filter><filter id="iK5FQic" width="4.312" height="4.613" x="9.693" y="3.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/><feGaussianBlur result="effect2_foregroundBlur_4002_3330" stdDeviation=".2"/></filter><filter id="ivs4Goe" width="8.767" height="5.782" x="12.877" y="2.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3330"/><feGaussianBlur result="effect2_foregroundBlur_4002_3330" stdDeviation=".125"/></filter><filter id="ib9nDbb" width="1.145" height="2.31" x="12.856" y="3.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".1"/></filter><filter id="ivWn9Ne" width="6.427" height="3.372" x="15.466" y="4.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3330" stdDeviation=".375"/></filter><linearGradient id="ikiZnFN" x1="20.741" x2="14.606" y1="3.603" y2="14.363" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iuyr1tn" x1="23.131" x2="22.971" y1="29.966" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iwTkvTT" x1="8.858" x2="9.061" y1="29.966" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="irRAuOe" x1="9.19" x2="7.596" y1="29.973" y2="29.973" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="iQD9ace" x1="14.707" x2="12.794" y1="19.947" y2="16.473" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="ig0Fqhd" x1="15.518" x2="15.198" y1="20.04" y2="19.939" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="i3hbZ4w" x1="16.798" x2="18.955" y1="19.966" y2="16.867" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="i1L7Mpd" x1="16.486" x2="16.722" y1="19.727" y2="19.649" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="i6XAUBd" x1="12.815" x2="12.815" y1="16.834" y2="29.479" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="ii62Mrk" x1="17.576" x2="14.433" y1="18.506" y2="18.124" gradientUnits="userSpaceOnUse"><stop class="nnmitvbqy"/><stop offset="1" class="x9o0-0bsl"/></linearGradient><linearGradient id="isKdouB" x1="15.205" x2="14.838" y1="19.49" y2="19.037" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="if4vDlY" x1="8.894" x2="23.27" y1="15.42" y2="15.42" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iZ5HQbe" x1="8.894" x2="23.27" y1="15.39" y2="15.39" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i8KqZZM" x1="9.753" x2="11.61" y1="10.642" y2="10.642" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="iPdMedc" x1="15.109" x2="16.047" y1="11.886" y2="11.886" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iS09dsb" x1="16.047" x2="16.047" y1="12.593" y2="11.966" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="ikZu3Np" x1="14.983" x2="15.444" y1="14.095" y2="13.383" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ihk4Q0b" x1="19.008" x2="18.694" y1="10.012" y2="10.205" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ic0v1Vc" x1="14.609" x2="14.296" y1="10.012" y2="10.205" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZnWb7j" x1="12.939" x2="13.428" y1="3.603" y2="4.868" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-tuxedo-medium" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.acv0-54tn {
  d: path("M13.863 9.481a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.au0ieex0a {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.19 9.986c.265-.467.668-.835 1.537-.835c.38 0 .747.105 1.073.368c.268.218.232.495.024.6l-.556.317c-.652-.21-1.372-.24-2.079-.45");
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.b71vjdbnr {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.987 8.183c.323-.079 1.125-.04 1.66.344");
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.bo-7t2vcz {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.196 8.183c-.322-.079-1.124-.04-1.66.344");
}

.brc_i4brl {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.906 9.986c-.266-.467-.67-.835-1.538-.835c-.38 0-.747.105-1.073.368c-.268.218-.232.495-.024.6l.556.317c.652-.21 1.372-.24 2.079-.45");
}

.bv7-wxb3q {
  d: path("M8.901 18.29a10.68 10.68 0 0 0-3.831 8.18v3.496H8.9z");
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d0ocvmu4d {
  d: path("M17.598 20.338c1.186-1.235 1.368-4.254 1.368-4.254c-.681-.36-1.548-.406-1.548-.406l-1.421.789l-.036 2.222l.774 1.52c.148.308.608.394.863.129");
}

.d22uk9b1z {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.665 10.194l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.d60lbkuym {
  d: path("M11.242 18.4c-.03-1.01.55-1.42.819-1.501l.617-.065v5.372c0 3.575.239 4.663 2.733 7.12l.011.016c.047.082-.05.176-.132.12c-2.75-1.881-4.776-3.355-5.094-8.18a.19.19 0 0 1 .174-.198c.297-.02.56-.044.747-.061a.19.19 0 0 0 .171-.191c-.01-.531-.02-1.533-.046-2.431");
}

.dc_z0_bxw {
  d: path("M16.104 15.39h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.dec65me-m {
  stop-color: var(--svg-color--b78c7d, #B78C7D);
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dj5l2yqzg {
  d: path("M11.709 17.604c0-1.278.933-1.774 1.554-1.618v5.737c0 3.873 1.453 6.262 2.712 8.087c.063.091-.047.201-.138.139c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.048.808-.066c.107-.01.188-.1.186-.207c-.011-.574-.023-1.658-.05-2.631");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.epgmjx2er {
  width: 3.875px;
  height: 6.133px;
  x: 14.075px;
  y: 12.709px;
  rx: 1.938px;
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fac_1yexe {
  stop-color: var(--svg-color--864e61, #864E61);
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fpjy3ccwl {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m18.454 6.374l-1.426.263a.688.688 0 1 1-.125-1.365h2.341c1.384 0 1.843 1.395 1.899 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gealwgbpb {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.655 10.333l-.684 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.494-.376-.613 0");
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gg5t8ab9x {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.65 8.777l-.005.003a.268.268 0 0 1-.275-.46l.001-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.815-.2 1.329-.11a.268.268 0 1 1-.094.53a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.455.193");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gtv1wwfmn {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.438 9.21c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.34h-2.232a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h0k4mmrtw {
  stop-color: var(--svg-color--8e506f, #8E506F);
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.houfji2bh {
  d: path("M20.875 12.164a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.huaycxbmm {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.047 13.467a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.422.345Z");
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i-laxlbsd {
  stop-color: var(--svg-color--864e61, #864E61);
  stop-opacity: 0;
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iwijhb8cc {
  d: path("M5.07 26.47c0-5.796 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.824 10.5 10.62v3.496H5.07z");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j8cr-ub1e {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.047 13.467a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.422.345");
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jrtmrs0np {
  d: path("M11.362 12.164a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.k7b007bvi {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m19.779 8.32l-.138.23za.268.268 0 0 1-.275.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.09.989 0 1.328.11a3.3 3.3 0 0 1 .56.238l.009.005l.002.002z");
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.ku2lh6uuy {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.535l1.813 1.252l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.791-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.kzfo1kqfu {
  d: path("m15.665 10.194l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lij47b-vj {
  fill: var(--svg-color--000, #000);
  d: path("M14.374 10.374a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.lmkyvq38o {
  d: path("M16.434 15.39c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.m95ojfb9w {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.444 2.764c-1.133-.25-2.15.88-2.267 1.3c1.052 3.545 3.713 3.35 6.34 3.058c1.573-.174 1.743.542 1.877.889c0-3.933-3.344-4.671-5.921-5.24z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mnd5zcc-c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.166 9.67c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.mvlg1lb-a {
  cx: 15.731px;
  cy: 25.909px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.n_ddxdbzc {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.656 9.21c-.653 0-1.204.45-1.354 1.058a.273.273 0 0 0 .267.34H14.8a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.n_qk5go9m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.156 4.013c.023.243.235 1.157.545 1.71");
}

.nnmitvbqy {
  stop-color: var(--svg-color--9b6a6d, #9B6A6D);
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.nzd5pi4db {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.741c-.037.825.18 2.636 1.367 3.871c.255.266.715.18.863-.129l.73-1.435l.731 1.435c.149.309.608.395.863.13c1.186-1.236 1.404-3.047 1.368-3.872z");
}

.o-ok2ibcd {
  d: path("m17.892 17.535l-1.813 1.252l1.795 1.258a.246.246 0 0 0 .388-.187c.041-.791.041-1.57.008-2.144a.239.239 0 0 0-.378-.179");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.ovsgk5bgw {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M10.978 4.567c.566-.6 1.637-.6 2.131-.51l.396 1.29c-.253-.04-.296-.002-.485.183c-.138 1.092-1.376 1.756-2.887 2.197c-.148-1.492.11-2.38.845-3.16");
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p14jg0bhe {
  stop-color: var(--svg-color--b78c7d, #B78C7D);
  stop-opacity: 0;
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.pbpjm1bhy {
  d: path("m14.133 17.535l1.813 1.252l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.791-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.pe2dttu3s {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.381 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.pee7z8bbo {
  d: path("M18.232 9.481a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.pi6jtfb-k {
  d: path("M15.444 2.764c-1.133-.25-2.15.88-2.267 1.3c1.052 3.545 3.713 3.35 6.34 3.058c1.573-.174 1.743.542 1.877.889c0-3.933-3.344-4.671-5.921-5.24z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pwzf73bct {
  d: path("M14.41 20.338c-1.185-1.235-1.367-4.254-1.367-4.254c.681-.36 1.548-.406 1.548-.406l1.421.789l.035 2.222l-.773 1.52c-.148.308-.608.394-.863.129");
}

.pxehlrooi {
  d: path("M19.027 10.256a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.qfl6_gbdv {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.875 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qsy44ybab {
  cx: 16.004px;
  cy: 25.636px;
  r: 0.5px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r07konbna {
  stop-color: var(--svg-color--965e72, #965E72);
  stop-opacity: 0;
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.rvf49obnj {
  d: path("M10.978 4.567c.566-.6 1.637-.6 2.131-.51l.396 1.29c-.253-.04-.296-.002-.485.183c-.138 1.092-1.376 1.756-2.887 2.197c-.148-1.492.11-2.38.845-3.16");
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.s76wahyla {
  d: path("M10.96 9.292h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439l.051-.02q.027-.012.052-.02a2.3 2.3 0 0 0 1.19-1.235l.081-.194a.264.264 0 0 1 .462-.05a3.86 3.86 0 0 0 3.189 1.672h3.22c.18 0 1.082.088 1.136 1.333l-.119 3.073c-.123 2.802-2.312 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.sa32mmbla {
  cx: 13.594px;
  cy: 9.862px;
  rx: 0.39px;
  ry: 0.197px;
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tao08pzef {
  cx: 15.731px;
  cy: 22.761px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tint2qbqx {
  fill-rule: evenodd;
  d: path("M23.233 11.965c.212-.435.324-.92.324-1.427c0-.467-.097-.906-.269-1.305h.005a3 3 0 0 0-.28-.513l-.003-.004a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.681 1.376a.56.56 0 0 1-.456.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.581a3.213 3.213 0 0 0 2.895-4.625a.52.52 0 0 1 0-.455m-12.26-2.672h-.013l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.46.051l-.083.194a2.3 2.3 0 0 1-1.24 1.255q-.027.012-.052.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.tmzj3tblv {
  d: path("M11.381 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.tz6_frehs {
  stop-color: var(--svg-color--8e6262, #8E6262);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.uoh3u9bsv {
  d: path("M8.901 18.29a10.69 10.69 0 0 0-3.831 8.185v3.498H8.9z");
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v_27a5b7h {
  cx: 13.594px;
  cy: 9.862px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.v8vbew4_g {
  fill: var(--svg-color--000, #000);
  d: path("M17.72 10.374a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.vau5mebxn {
  stop-color: var(--svg-color--8e6262, #8E6262);
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vh3uzfb2k {
  d: path("M18.166 9.67c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wga2pr3ix {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.332 17.604c0-1.278-.933-1.774-1.555-1.618v5.737c0 3.873-1.452 6.262-2.711 8.087c-.063.091.047.201.138.139c2.976-2.036 4.915-4.003 5.26-9.226a.203.203 0 0 0-.188-.215c-.321-.02-.606-.048-.809-.066a.204.204 0 0 1-.185-.207c.011-.574.023-1.658.05-2.631");
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wsuqc2bol {
  d: path("M18.767 16.117a10.3 10.3 0 0 0-2.337-.267h-.86a10.3 10.3 0 0 0-2.312.261v5.423c0 4.175 1.065 5.971 2.654 8.432h.285c1.59-2.46 2.57-4.257 2.57-8.432z");
}

.wui8nqfgb {
  cx: 16.012px;
  cy: 18.756px;
  r: 0.809px;
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x7qb6jv9m {
  d: path("M20.875 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.x9o0-0bsl {
  stop-color: var(--svg-color--845158, #845158);
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xzv69vbgz {
  d: path("M14.679 10.269c0-.289-.235-.481-.298-.54l-.289.28l.178.36z");
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z77pc-39f {
  d: path("M23.099 18.29a10.68 10.68 0 0 1 3.831 8.18v3.496H23.1z");
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zgcak206m {
  cx: 16.004px;
  cy: 22.628px;
  r: 0.5px;
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

</style>
