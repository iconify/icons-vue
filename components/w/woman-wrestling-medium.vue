<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#svgIDa)" transform="rotate(-23.31 19.316 9.27)" class="ichkr_bpe"/><path fill="url(#svgIDb)" transform="scale(-1 1) rotate(-37.969 7.719 23.62)" class="dm4voe-la"/><path class="pg63y9b5y"/><g filter="url(#svgIDc)"><path class="z63k8kqqf"/><path fill="url(#svgIDd)" class="rbrbnox1k"/></g><g filter="url(#svgIDe)"><path class="u3tp_1b4z"/></g><path fill="url(#svgIDf)" class="qu7wy3byg"/><path fill="url(#svgIDg)" class="qu7wy3byg"/><path fill="url(#svgIDh)" class="qu7wy3byg"/><path fill="url(#svgIDi)" class="rvn6dnbeu"/><path fill="url(#svgIDj)" class="rvn6dnbeu"/><path fill="url(#svgIDk)" class="rvn6dnbeu"/><g filter="url(#svgIDl)"><path class="h8s3t1bxb"/></g><g filter="url(#svgIDm)"><path class="h44vs32ne"/></g><g filter="url(#svgIDn)"><path class="ms8d88bde"/><path fill="url(#svgIDo)" class="i7saq21uo"/></g><path fill="url(#svgIDp)" class="jnesarx4u"/><path fill="url(#svgIDq)" class="jnesarx4u"/><g filter="url(#svgIDr)"><path class="s94uheblk"/><path fill="url(#svgIDs)" class="nkxdn3yzn"/><path fill="url(#svgIDt)" class="nkxdn3yzn"/><path fill="url(#svgIDu)" class="nkxdn3yzn"/></g><g filter="url(#svgIDv)"><path class="dyerczfxv"/></g><g filter="url(#svgIDw)"><path class="ljdchwceu"/><path fill="url(#svgIDx)" class="zp0b4-bhz"/><path fill="url(#svgIDy)" class="zp0b4-bhz"/><path fill="url(#svgIDz)" class="zp0b4-bhz"/></g><g filter="url(#svgIDA)"><path fill="url(#svgIDB)" class="xh1g2eduz"/></g><g filter="url(#svgIDC)"><rect stroke="url(#svgIDD)" transform="rotate(45 8.633 10.248)" class="r7qeq_bxt"/></g><rect fill="url(#svgIDE)" transform="rotate(45 8.633 10.248)" class="ye_szro2v"/><rect fill="url(#svgIDF)" transform="rotate(45 8.633 10.248)" class="ye_szro2v"/><g filter="url(#svgIDG)"><path clip-rule="evenodd" class="it-j5xbsh"/></g><path clip-rule="evenodd" class="wzgbz6ynl"/><path fill="url(#svgIDH)" clip-rule="evenodd" class="kzvt00ajy"/><path clip-rule="evenodd" class="vvr97nuie"/><path fill="url(#svgIDI)" clip-rule="evenodd" class="hse6h5b7p"/><path clip-rule="evenodd" class="cs3hmqbia"/><path fill="url(#svgIDJ)" clip-rule="evenodd" class="pccgwb5sy"/><path clip-rule="evenodd" class="oqdmutx9v"/><path fill="url(#svgIDK)" clip-rule="evenodd" class="dd34qhijr"/><path clip-rule="evenodd" class="uh2quobbn"/><path fill="url(#svgIDL)" clip-rule="evenodd" class="ut_jylbhb"/><path fill="url(#svgIDM)" clip-rule="evenodd" class="hu6qrb-cx"/><path fill="url(#svgIDN)" clip-rule="evenodd" class="hu6qrb-cx"/><path fill="url(#svgIDO)" clip-rule="evenodd" class="hu6qrb-cx"/><rect transform="rotate(-28.166 17.093 15.922)" class="oeay3te4a"/><path fill="url(#svgIDP)" class="uzo1bebwx"/><path fill="url(#svgIDQ)" class="uzo1bebwx"/><path fill="url(#svgIDR)" class="uzo1bebwx"/><path fill="url(#svgIDS)" class="f8y-tl9do"/><path fill="url(#svgIDT)" class="f8y-tl9do"/><path fill="url(#svgIDU)" class="f8y-tl9do"/><g filter="url(#svgIDV)"><path class="co6n89prj"/></g><g filter="url(#svgIDW)"><path class="kjvqytpae"/></g><g filter="url(#svgIDX)"><path class="f8s-ypx6s"/><path fill="url(#svgIDY)" class="yq97qkmjj"/></g><path fill="url(#svgIDZ)" class="voxhk3bis"/><path fill="url(#svgIDaa)" class="voxhk3bis"/><g filter="url(#svgIDab)"><path class="f0fnh4o-w"/><path fill="url(#svgIDac)" class="a0mvafb9r"/><path fill="url(#svgIDad)" class="a0mvafb9r"/><path fill="url(#svgIDae)" class="a0mvafb9r"/></g><g filter="url(#svgIDaf)"><path class="iwvg1ab2u"/></g><g filter="url(#svgIDag)"><path class="qx3t-styr"/><path fill="url(#svgIDah)" class="op3dsib_z"/><path fill="url(#svgIDai)" class="op3dsib_z"/><path fill="url(#svgIDaj)" class="op3dsib_z"/></g><g filter="url(#svgIDak)"><path fill="url(#svgIDal)" class="yudrekboq"/></g><rect fill="url(#svgIDam)" transform="scale(-1 1) rotate(45 -24.035 -23.09)" class="pxj138bcc"/><rect fill="url(#svgIDan)" transform="scale(-1 1) rotate(45 -24.035 -23.09)" class="pxj138bcc"/><rect fill="url(#svgIDao)" transform="scale(-1 1) rotate(45 -24.035 -23.09)" class="pxj138bcc"/><rect fill="url(#svgIDap)" transform="scale(-1 1) rotate(45 -24.035 -23.09)" class="pxj138bcc"/><path clip-rule="evenodd" class="vc4p3ibvk"/><path fill="url(#svgIDaq)" clip-rule="evenodd" class="a-bzdtyfb"/><path class="b99x64bax"/><path fill="url(#svgIDar)" class="clfu6abgw"/><path fill="url(#svgIDas)" class="clfu6abgw"/><path class="mf6irgsiu"/><path fill="url(#svgIDat)" class="q2i415kkt"/><path fill="url(#svgIDau)" class="q2i415kkt"/><path class="kk51k_biz"/><path fill="url(#svgIDav)" class="oelvtcc5o"/><path fill="url(#svgIDaw)" class="oelvtcc5o"/><path class="pxqsryxea"/><path fill="url(#svgIDax)" class="jf74cfb1u"/><path fill="url(#svgIDay)" class="jf74cfb1u"/><g filter="url(#svgIDaz)"><path class="z8pr35bty"/></g><g filter="url(#svgIDaA)"><path stroke="url(#svgIDaB)" class="iuayy_bud"/></g><g filter="url(#svgIDaC)"><path fill="url(#svgIDaD)" class="bvg8qvbwx"/></g><g filter="url(#svgIDaE)"><ellipse class="qyp-c9u-k"/></g><path fill="url(#svgIDaF)" class="tee9rqeex"/><path fill="url(#svgIDaG)" class="tee9rqeex"/><path fill="url(#svgIDaH)" class="xf26kynrw"/><g filter="url(#svgIDaI)"><path fill="url(#svgIDaJ)" class="i18dd_bid"/><path fill="url(#svgIDaK)" class="i18dd_bid"/><path fill="url(#svgIDaL)" class="i18dd_bid"/><path fill="url(#svgIDaM)" class="i18dd_bid"/></g><g filter="url(#svgIDaN)"><path fill="url(#svgIDaO)" class="lz46tfbxe"/><path fill="url(#svgIDaP)" class="lz46tfbxe"/><path fill="url(#svgIDaQ)" class="lz46tfbxe"/><path fill="url(#svgIDaR)" class="lz46tfbxe"/></g><g filter="url(#svgIDaS)"><path class="ez2eb00jb"/><path fill="url(#svgIDaT)" class="xqn0te1rl"/></g><g filter="url(#svgIDaU)"><path class="mwu89jbtt"/><path fill="url(#svgIDaV)" class="w9s72m9ak"/></g><path fill="url(#svgIDaW)" class="gnc23j6vq"/><path fill="url(#svgIDaX)" class="gnc23j6vq"/><path fill="url(#svgIDaY)" class="gnc23j6vq"/><path fill="url(#svgIDaZ)" class="a4c-nqbcj"/><path fill="url(#svgIDba)" class="a4c-nqbcj"/><path fill="url(#svgIDbb)" class="a4c-nqbcj"/><path class="bt0u1i0ea"/><path class="u86qg0qzt"/><path fill="url(#svgIDbc)" class="wjxjx823k"/><path fill="url(#svgIDbd)" class="n1l9tez0b"/><path fill="url(#svgIDbe)" class="z8v1d3bmk"/><path fill="url(#svgIDbf)" class="d9bzuiwfi"/><ellipse fill="url(#svgIDbg)" transform="scale(-1 1) rotate(22.002 -25.956 -32.068)" class="pa0scmbsx"/><ellipse fill="url(#svgIDbh)" transform="rotate(22.002 18.247 7.389)" class="x1x-5bk_s"/><path fill="url(#svgIDbi)" class="x7ihk88zx"/><path fill="url(#svgIDbj)" class="x7ihk88zx"/><path fill="url(#svgIDbk)" class="x7ihk88zx"/><path fill="url(#svgIDbl)" class="k_gxsyo3c"/><path fill="url(#svgIDbm)" class="k_gxsyo3c"/><path fill="url(#svgIDbn)" class="k_gxsyo3c"/><path fill="url(#svgIDbo)" class="ha7m41bdf"/><path fill="url(#svgIDbp)" class="ha7m41bdf"/><path fill="url(#svgIDbq)" class="ha7m41bdf"/><path fill="url(#svgIDbr)" class="nxndz826k"/><path fill="url(#svgIDbs)" class="nxndz826k"/><path fill="url(#svgIDbt)" class="nxndz826k"/><path fill="url(#svgIDbu)" clip-rule="evenodd" class="hq4v5hb0q"/><path fill="url(#svgIDbv)" clip-rule="evenodd" class="hq4v5hb0q"/><path fill="url(#svgIDbw)" clip-rule="evenodd" class="hq4v5hb0q"/><path fill="url(#svgIDbx)" clip-rule="evenodd" class="yfa5ic60r"/><path fill="url(#svgIDby)" clip-rule="evenodd" class="yfa5ic60r"/><path fill="url(#svgIDbz)" clip-rule="evenodd" class="yfa5ic60r"/><path fill="url(#svgIDbA)" clip-rule="evenodd" class="tmqabdcjp"/><path fill="url(#svgIDbB)" clip-rule="evenodd" class="tmqabdcjp"/><path fill="url(#svgIDbC)" clip-rule="evenodd" class="arjuas_nk"/><path fill="url(#svgIDbD)" clip-rule="evenodd" class="arjuas_nk"/><circle fill="url(#svgIDbE)" class="wfbebvbje"/><circle fill="url(#svgIDbF)" class="wfbebvbje"/><circle fill="url(#svgIDbG)" class="wfbebvbje"/><circle fill="url(#svgIDbH)" transform="matrix(-1 0 0 1 21.154 7.865)" class="ms4f1oj7g"/><circle fill="url(#svgIDbI)" transform="matrix(-1 0 0 1 21.154 7.865)" class="ms4f1oj7g"/><circle fill="url(#svgIDbJ)" transform="matrix(-1 0 0 1 21.154 7.865)" class="ms4f1oj7g"/><g filter="url(#svgIDbK)"><rect class="cagpkq_ou"/></g><g filter="url(#svgIDbL)"><rect transform="matrix(-1 0 0 1 19.201 6.615)" class="kv-jd2a1k"/></g><path class="sasdif2nd"/><defs><radialGradient id="svgIDa" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 19.282 10.72)" gradientUnits="userSpaceOnUse"><stop class="i2p0hhbue"/><stop offset=".919" class="m6i64ob9s"/></radialGradient><radialGradient id="svgIDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 -.033 1.45)" gradientUnits="userSpaceOnUse"><stop class="i2p0hhbue"/><stop offset=".919" class="m6i64ob9s"/></radialGradient><radialGradient id="svgIDd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71095 2.35327 -5.20382 -5.99476 18.899 10.983)" gradientUnits="userSpaceOnUse"><stop class="ttoyfzbaw"/><stop offset="1" class="e1ueer7az"/></radialGradient><radialGradient id="svgIDf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 11.656 25.6)" gradientUnits="userSpaceOnUse"><stop class="mtqoh_bre"/><stop offset="1" class="n66bp_w4m"/></radialGradient><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(2.14185 1.875 -.94292 1.07712 7.39 20.569)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="igiy6tomy"/><stop offset="1" class="rpf2vrbvv"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(144.26 2.227 11.123) scale(1.23051 3.4979)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="gbitypbvx"/><stop offset="1" class="tx5lqdb2i"/></radialGradient><radialGradient id="svgIDo" cx="0" cy="0" r="1" gradientTransform="rotate(-134.195 7.107 8.105) scale(2.212 .64075)" gradientUnits="userSpaceOnUse"><stop class="sf5518bjn"/><stop offset="1" class="t77q9um-l"/></radialGradient><radialGradient id="svgIDp" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6084 4.12475 -1.56989 -1.37337 8.893 16.53)" gradientUnits="userSpaceOnUse"><stop class="r7-2aybwm"/><stop offset="1" class="kuufpibxl"/></radialGradient><radialGradient id="svgIDq" cx="0" cy="0" r="1" gradientTransform="matrix(6.96877 -7.18752 5.67939 5.50654 3.781 17.881)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="qn4r5dznz"/><stop offset="1" class="qpxjwkb-f"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="rotate(-144.397 8.189 13.153) scale(2.17397 2.91043)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64636 -1.26563 1.72963 -2.24994 14.356 28.608)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 11.203 26.428)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="matrix(-.05524 1.73462 -1.20171 -.03827 10.37 11.527)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="u84rtio_o"/><stop offset="1" class="jj1uh6bhe"/></radialGradient><radialGradient id="svgIDF" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 11.379 13.369)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="jg31p_bkv"/><stop offset="1" class="ef2_oackn"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="rotate(137.121 3.006 10.255) scale(3.58218 11.0839)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="rwshkknje"/><stop offset="1" class="la3agyb1u"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="matrix(-.1607 .97723 -3.16368 -.52026 14.262 18.646)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="jony80okq"/><stop offset="1" class="e4agtf5yi"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.30444 .89737 -2.62413 -.89026 14.56 19.282)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="jony80okq"/><stop offset="1" class="e4agtf5yi"/></radialGradient><radialGradient id="svgIDK" cx="0" cy="0" r="1" gradientTransform="matrix(-.28295 .92188 -2.48547 -.76287 14.252 19.6)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="jony80okq"/><stop offset="1" class="e4agtf5yi"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37499 1.625 -1.79466 -1.51854 29.313 10.694)" gradientUnits="userSpaceOnUse"><stop class="em0115xht"/><stop offset="1" class="b-fys1r7u"/></radialGradient><radialGradient id="svgIDN" cx="0" cy="0" r="1" gradientTransform="matrix(2.12183 -1.33219 1.13322 1.80492 26.394 12.9)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="yxyrfz-2l"/><stop offset="1" class="tz_1rgbcq"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 20.343 25.584)" gradientUnits="userSpaceOnUse"><stop class="mtqoh_bre"/><stop offset="1" class="n66bp_w4m"/></radialGradient><radialGradient id="svgIDQ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14186 1.87499 -.94291 -1.07712 24.61 20.553)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="igiy6tomy"/><stop offset="1" class="rpf2vrbvv"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="matrix(.99878 .71875 -2.04315 2.83916 21.468 18.834)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="gbitypbvx"/><stop offset="1" class="tx5lqdb2i"/></radialGradient><radialGradient id="svgIDY" cx="0" cy="0" r="1" gradientTransform="matrix(1.542 -1.58594 .4594 .44667 25.75 18.834)" gradientUnits="userSpaceOnUse"><stop class="sf5518bjn"/><stop offset="1" class="t77q9um-l"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="matrix(3.6084 4.12476 -1.5699 1.37336 23.107 16.514)" gradientUnits="userSpaceOnUse"><stop class="r7-2aybwm"/><stop offset="1" class="kuufpibxl"/></radialGradient><radialGradient id="svgIDaa" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9688 -7.18748 5.67936 -5.50657 28.218 17.866)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="qn4r5dznz"/><stop offset="1" class="qpxjwkb-f"/></radialGradient><radialGradient id="svgIDad" cx="0" cy="0" r="1" gradientTransform="matrix(1.76758 -1.26563 1.69437 2.36637 24.81 28.6)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(1.64636 -1.26562 1.72962 2.24995 17.644 28.592)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 20.797 26.412)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDam" cx="0" cy="0" r="1" gradientTransform="matrix(-.05524 1.73462 -1.20171 -.03827 1.738 1.279)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="d_emxobmg"/><stop offset="1" class="zhjbr8yrc"/></radialGradient><radialGradient id="svgIDan" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 2.746 3.121)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="sspda2v0w"/><stop offset="1" class="vwbmp8jnk"/></radialGradient><radialGradient id="svgIDao" cx="0" cy="0" r="1" gradientTransform="matrix(2.43827 .18437 -.24868 3.2888 .122 2.37)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="l5v3qe0jr"/><stop offset=".865" class="i_qwr-19p"/></radialGradient><radialGradient id="svgIDap" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 2.746 3.121)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="q5fkj53wg"/><stop offset="1" class="xvt5tsb3a"/></radialGradient><radialGradient id="svgIDaq" cx="0" cy="0" r="1" gradientTransform="matrix(1.49685 3.75 -10.37919 4.14298 19.25 14.506)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="zgtcnu2sf"/><stop offset=".969" class="o3t6sop5m"/></radialGradient><radialGradient id="svgIDas" cx="0" cy="0" r="1" gradientTransform="matrix(0 .50438 -1.56574 0 16.39 16.53)" gradientUnits="userSpaceOnUse"><stop class="kpw5jeb1t"/><stop offset="1" class="axl394b5i"/></radialGradient><radialGradient id="svgIDau" cx="0" cy="0" r="1" gradientTransform="matrix(0 .50438 -1.5408 0 16.414 17.157)" gradientUnits="userSpaceOnUse"><stop class="kpw5jeb1t"/><stop offset="1" class="axl394b5i"/></radialGradient><radialGradient id="svgIDaw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .49784 -1.34351 0 16.64 17.899)" gradientUnits="userSpaceOnUse"><stop class="kpw5jeb1t"/><stop offset="1" class="axl394b5i"/></radialGradient><radialGradient id="svgIDay" cx="0" cy="0" r="1" gradientTransform="matrix(0 .58024 -1.49592 0 16.587 15.632)" gradientUnits="userSpaceOnUse"><stop class="kpw5jeb1t"/><stop offset="1" class="axl394b5i"/></radialGradient><radialGradient id="svgIDaD" cx="0" cy="0" r="1" gradientTransform="rotate(123.38 11.453 13.303) scale(2.43251 2.70978)" gradientUnits="userSpaceOnUse"><stop class="w9zau2kqh"/><stop offset="1" class="abcsnnb1c"/></radialGradient><radialGradient id="svgIDaF" cx="0" cy="0" r="1" gradientTransform="matrix(-.5347 .25854 -.36494 -.75475 15.166 8.498)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="svgIDaG" cx="0" cy="0" r="1" gradientTransform="matrix(.146 -.31323 .47009 .21912 14.706 8.826)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="svgIDaH" cx="0" cy="0" r="1" gradientTransform="matrix(.5347 .25854 -.36494 .75475 16.985 8.498)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="har2clbwm"/><stop offset=".684" class="l7cj2r41q"/></radialGradient><radialGradient id="svgIDaK" cx="0" cy="0" r="1" gradientTransform="matrix(.92625 -.00925 .01127 1.1293 11.191 7.546)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="svgIDaL" cx="0" cy="0" r="1" gradientTransform="matrix(.25873 -5.68037 2.20713 .10053 14.304 8.99)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="svgIDaM" cx="0" cy="0" r="1" gradientTransform="rotate(92.608 3.048 10.278) scale(.42818 .66776)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="svgIDaP" cx="0" cy="0" r="1" gradientTransform="rotate(-179.428 10.499 3.72) scale(.9263 1.12935)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="svgIDaQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.25873 -5.68037 2.20713 -.10053 17.847 8.99)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="iy_62gb7c"/><stop offset="1" class="eotc9zblf"/></radialGradient><radialGradient id="svgIDaR" cx="0" cy="0" r="1" gradientTransform="matrix(.01948 .42774 -.66707 .03038 18.697 7.7)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65918 -.54927 1.17707 -3.5556 14.723 5.254)" gradientUnits="userSpaceOnUse"><stop class="zy9nvz9pf"/><stop offset="1" class="xfcyplbyz"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="matrix(1.65918 -.54925 1.17705 3.5556 17.427 5.254)" gradientUnits="userSpaceOnUse"><stop class="zy9nvz9pf"/><stop offset="1" class="xfcyplbyz"/></radialGradient><radialGradient id="svgIDaW" cx="0" cy="0" r="1" gradientTransform="matrix(-.78507 -.26722 .13042 -.38318 11.529 7.441)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDaX" cx="0" cy="0" r="1" gradientTransform="rotate(103.451 2.95 8.096) scale(1.31668 1.37204)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(.78507 -.26722 .13042 .38318 20.622 7.441)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDba" cx="0" cy="0" r="1" gradientTransform="matrix(.30627 1.28056 -1.3344 .31915 20.641 7.11)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.29942 -.01364 .0265 -.58172 13.775 7.745)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDbd" cx="0" cy="0" r="1" gradientTransform="matrix(.29942 -.01364 .0265 .58172 18.376 7.745)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.27375 -.01247 .02698 -.59242 13.958 7.777)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbf" cx="0" cy="0" r="1" gradientTransform="matrix(.27375 -.01247 .02698 .59242 18.193 7.777)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.28 2.86) scale(.82753 .4039)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDbj" cx="0" cy="0" r="1" gradientTransform="matrix(-.24716 1.2904 -1.34466 -.25755 11.478 7.027)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDbl" cx="0" cy="0" r="1" gradientTransform="matrix(.79471 -.23072 .11261 .38789 20.639 7.356)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDbm" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.086 16.017) scale(1.31386 1.3691)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDbo" cx="0" cy="0" r="1" gradientTransform="matrix(-.79555 -.23096 .11273 -.3883 11.508 7.36)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDbp" cx="0" cy="0" r="1" gradientTransform="matrix(-.24742 1.29177 -1.34608 -.25783 11.474 7.03)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDbr" cx="0" cy="0" r="1" gradientTransform="matrix(.79555 -.23097 .11273 .3883 20.643 7.36)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDbs" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.086 16.022) scale(1.31525 1.37055)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDbv" cx="0" cy="0" r="1" gradientTransform="matrix(.23047 .0586 -.60662 2.38602 11.106 6.213)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbw" cx="0" cy="0" r="1" gradientTransform="matrix(-.52148 1.82813 -.23787 -.06785 12.149 4.475)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDby" cx="0" cy="0" r="1" gradientTransform="rotate(165.735 10.134 4.423) scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbz" cx="0" cy="0" r="1" gradientTransform="matrix(.52148 1.82813 -.23787 .06785 20.002 4.475)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDbB" cx="0" cy="0" r="1" gradientTransform="matrix(-.35156 .1875 -.70184 -1.31597 11.985 9.49)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbD" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .1875 -.70185 1.31597 20.166 9.49)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 12.031 7.381)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbF" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 9.715 7.865)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbG" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 12.063 8.756)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><radialGradient id="svgIDbH" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 2.316 .797)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbI" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 0 1.281)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 2.348 2.172)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><linearGradient id="svgIDi" x1="6.625" x2="8.406" y1="20.006" y2="18.319" gradientUnits="userSpaceOnUse"><stop class="xoi0djbjo"/><stop offset="1" class="gl6qqfkzm"/></linearGradient><linearGradient id="svgIDj" x1="8.328" x2="8.153" y1="19.397" y2="19.213" gradientUnits="userSpaceOnUse"><stop class="j3zvk_bdt"/><stop offset="1" class="k78l4l0qb"/></linearGradient><linearGradient id="svgIDk" x1="5.563" x2="6.844" y1="19.444" y2="19.506" gradientUnits="userSpaceOnUse"><stop offset=".28" class="o22_o0bcf"/><stop offset="1" class="gfdvmwbxq"/></linearGradient><linearGradient id="svgIDs" x1="2.251" x2="2.836" y1="28.256" y2="28.389" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDu" x1="5.625" x2="5.625" y1="28.616" y2="28.291" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDx" x1="9.756" x2="10.3" y1="28.381" y2="28.364" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDz" x1="12.899" x2="12.899" y1="28.608" y2="28.283" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDD" x1="10.365" x2="10.365" y1="10.248" y2="14.822" gradientUnits="userSpaceOnUse"><stop class="pyu7r8zmo"/><stop offset="1" class="mq17zybfl"/></linearGradient><linearGradient id="svgIDL" x1="13.406" x2="13.641" y1="20.772" y2="20.342" gradientUnits="userSpaceOnUse"><stop offset=".245" class="fuqwctlqz"/><stop offset="1" class="a0aan_bfy"/></linearGradient><linearGradient id="svgIDO" x1="25.301" x2="25.832" y1="9.981" y2="11.225" gradientUnits="userSpaceOnUse"><stop class="yren7o-8v"/><stop offset="1" class="gn8dr-4uj"/></linearGradient><linearGradient id="svgIDS" x1="25.375" x2="23.593" y1="19.991" y2="18.303" gradientUnits="userSpaceOnUse"><stop class="xoi0djbjo"/><stop offset="1" class="gl6qqfkzm"/></linearGradient><linearGradient id="svgIDT" x1="23.672" x2="23.847" y1="19.381" y2="19.198" gradientUnits="userSpaceOnUse"><stop class="j3zvk_bdt"/><stop offset="1" class="k78l4l0qb"/></linearGradient><linearGradient id="svgIDU" x1="26.437" x2="25.156" y1="19.428" y2="19.491" gradientUnits="userSpaceOnUse"><stop offset=".28" class="o22_o0bcf"/><stop offset="1" class="gfdvmwbxq"/></linearGradient><linearGradient id="svgIDac" x1="29.749" x2="29.164" y1="28.241" y2="28.373" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDae" x1="26.375" x2="26.375" y1="28.6" y2="28.276" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDah" x1="22.244" x2="21.7" y1="28.366" y2="28.349" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDaj" x1="19.101" x2="19.101" y1="28.592" y2="28.268" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDar" x1="17.246" x2="17.246" y1="17.31" y2="16.828" gradientUnits="userSpaceOnUse"><stop class="jh_z6ab-a"/><stop offset="1" class="a-v94sblr"/></linearGradient><linearGradient id="svgIDat" x1="17.256" x2="17.256" y1="17.937" y2="17.455" gradientUnits="userSpaceOnUse"><stop class="jh_z6ab-a"/><stop offset="1" class="a-v94sblr"/></linearGradient><linearGradient id="svgIDav" x1="17.375" x2="17.375" y1="18.669" y2="18.194" gradientUnits="userSpaceOnUse"><stop class="jh_z6ab-a"/><stop offset="1" class="a-v94sblr"/></linearGradient><linearGradient id="svgIDax" x1="17.121" x2="17.582" y1="16.857" y2="15.967" gradientUnits="userSpaceOnUse"><stop class="jh_z6ab-a"/><stop offset=".891" class="a-v94sblr"/></linearGradient><linearGradient id="svgIDaB" x1="24.207" x2="19.801" y1="12.037" y2="18.069" gradientUnits="userSpaceOnUse"><stop class="auqu5kb-l"/><stop offset="1" class="pputyyb_m"/></linearGradient><linearGradient id="svgIDaJ" x1="11.496" x2="14.622" y1="8.374" y2="8.705" gradientUnits="userSpaceOnUse"><stop class="o0r6oh8jt"/><stop offset="1" class="wyzmbm91v"/></linearGradient><linearGradient id="svgIDaO" x1="20.654" x2="17.529" y1="8.374" y2="8.705" gradientUnits="userSpaceOnUse"><stop class="l7w6j-bmv"/><stop offset="1" class="o_ul3db6n"/></linearGradient><linearGradient id="svgIDaY" x1="11.585" x2="11.422" y1="7.519" y2="7.524" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDbb" x1="20.566" x2="20.729" y1="7.519" y2="7.524" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDbg" x1="-.007" x2=".197" y1=".054" y2=".121" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbh" x1="18.168" x2="18.372" y1="7.347" y2="7.413" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbk" x1="11.623" x2="11.316" y1="7.394" y2="7.479" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDbn" x1="20.528" x2="20.835" y1="7.394" y2="7.479" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDbq" x1="11.568" x2="11.405" y1="7.435" y2="7.447" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDbt" x1="20.583" x2="20.745" y1="7.435" y2="7.447" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDbu" x1="11.977" x2="10.903" y1="5.522" y2="6.428" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbx" x1="20.174" x2="21.248" y1="5.522" y2="6.428" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbA" x1="11.406" x2="12.758" y1="9.131" y2="10.959" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><linearGradient id="svgIDbC" x1="20.744" x2="19.393" y1="9.131" y2="10.959" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><filter id="svgIDc" width="10.808" height="5.007" x="8.491" y="10.683" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.403922 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.305882 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23634" result="effect2_innerShadow_3987_23634"/></filter><filter id="svgIDe" width="7.106" height="3.139" x="10.204" y="11.773" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23634" stdDeviation=".2"/></filter><filter id="svgIDl" width="4.146" height="5.805" x="2.788" y="20.194" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.560784 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23634" result="effect2_innerShadow_3987_23634"/></filter><filter id="svgIDm" width="9.426" height="8.574" x="2.717" y="9.993" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.470588 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDn" width="5.878" height="6.781" x="2.144" y="13.873" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.470588 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDr" width="5.139" height="3.208" x="2.051" y="25.608" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDv" width="2.686" height="1.05" x="2.698" y="25.608" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.670588 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDw" width="4.9" height="3.308" x="9.456" y="25.6" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDA" width="2.288" height="1.065" x="9.756" y="25.6" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDC" width="5.149" height="5.149" x="5.666" y="10.515" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23634" stdDeviation=".125"/></filter><filter id="svgIDG" width="1.796" height="1.427" x="13.37" y="17.933" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDV" width="4.146" height="5.805" x="25.066" y="20.178" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.560784 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23634" result="effect2_innerShadow_3987_23634"/></filter><filter id="svgIDW" width="9.426" height="8.574" x="19.857" y="9.978" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.470588 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDX" width="5.878" height="6.781" x="23.978" y="13.858" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.470588 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDab" width="5.139" height="3.208" x="24.61" y="25.592" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDaf" width="2.686" height="1.05" x="26.615" y="25.592" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.694118 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDag" width="4.9" height="3.308" x="17.344" y="25.584" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDak" width="2.288" height="1.065" x="20.156" y="25.584" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDaz" width="5.984" height="7.891" x="7.785" y="11.616" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23634" stdDeviation=".25"/></filter><filter id="svgIDaA" width="7.313" height="7.219" x="17.582" y="11.162" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23634" stdDeviation=".25"/></filter><filter id="svgIDaC" width="4.063" height="3.831" x="25.494" y="10.159" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23634" stdDeviation=".3"/></filter><filter id="svgIDaE" width="2.322" height="3.133" x="16.526" y="15.808" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23634" stdDeviation=".25"/></filter><filter id="svgIDaI" width="4.959" height="5.868" x="9.964" y="5.107" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.337255 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDaN" width="4.959" height="5.868" x="17.479" y="5.107" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.376471 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDaS" width="7.626" height="7.893" x="7.339" y="3.414" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.294118 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.172549 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23634" result="effect2_innerShadow_3987_23634"/></filter><filter id="svgIDaU" width="7.626" height="7.893" x="16.785" y="3.414" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.294118 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.172549 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23634" result="effect2_innerShadow_3987_23634"/></filter><filter id="svgIDbK" width="1.258" height=".393" x="12.95" y="6.515" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.121569 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter><filter id="svgIDbL" width="1.258" height=".393" x="17.944" y="6.515" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.121569 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23634"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-wrestling-medium" /></template>
<style>
.a-bzdtyfb {
  fill-rule: evenodd;
  d: path("M23.727 11.805c.627.167 1 .81.833 1.438c-.25.937-.826 1.86-1.893 3.008c-1.075 1.158-2.67 2.248-4.615 2.414a1.175 1.175 0 0 1-1.27-1.072c-.055-.646.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.998c.167-.627.811-1 1.438-.833Z");
}

.a-v94sblr {
  stop-color: var(--svg-color--9d7270, #9D7270);
  stop-opacity: 0;
}

.a0aan_bfy {
  stop-color: var(--svg-color--946466, #946466);
  stop-opacity: 0;
}

.a0mvafb9r {
  d: path("m29.081 25.668l.66 2.62a.25.25 0 0 1-.242.312h-4.441c-.102 0-.196-.06-.22-.159c-.127-.503.196-.866.763-1.157a86.214 86.214 0 0 0 1.696-.9l-.376-.719a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.076Z");
}

.a0q036gjd {
  stop-color: var(--svg-color--504d4e, #504D4E);
}

.a4c-nqbcj {
  d: path("m20.5 8.405l.146-1.586a.797.797 0 0 1-.146 1.586Z");
}

.a5dbyd6tf {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
}

.abcsnnb1c {
  stop-color: var(--svg-color--b68976, #B68976);
  stop-opacity: 0;
}

.ak32k0b7k {
  stop-color: var(--svg-color--695d73, #695D73);
}

.al_auo8nl {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
  stop-opacity: 0;
}

.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.arjuas_nk {
  fill-rule: evenodd;
  d: path("M21.05 8.556a.25.25 0 0 0-.326.137a9.05 9.05 0 0 1-.511 1.039c-.23.398-.488.766-.733.975a.25.25 0 1 0 .325.38c.312-.267.606-.697.841-1.106c.239-.415.433-.834.54-1.1a.25.25 0 0 0-.137-.325Z");
}

.auqu5kb-l {
  stop-color: var(--svg-color--b28e77, #B28E77);
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.axl394b5i {
  stop-color: var(--svg-color--af8c7c, #AF8C7C);
  stop-opacity: 0;
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.b-fys1r7u {
  stop-color: var(--svg-color--9e7c62, #9E7C62);
}

.b5skg8e-v {
  stop-color: var(--svg-color--522470, #522470);
}

.b99x64bax {
  fill: var(--svg-color--a38069, #A38069);
  d: path("M15.464 16.92a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.bt0u1i0ea {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.002 7.173c.15-.138.39-.16.492-.153l-.355.496c-.16-.017-.324-.172-.137-.343Zm6.146 0c-.15-.138-.39-.16-.491-.153l.355.496c.16-.017.324-.172.136-.343Z");
}

.bvg8qvbwx {
  d: path("M26.406 10.759a.3.3 0 0 0-.024.6l.024-.6Zm1.29.353l.013-.3l-.012.3Zm.899 1.343l.282.103l-.282-.103Zm-.514.532a.3.3 0 0 0 .563.206l-.563-.206Zm-1.7-1.629l1.303.054l.025-.6l-1.303-.053l-.024.6Zm1.932.994l-.232.635l.563.206l.233-.635l-.564-.206Zm-.629-.94a.7.7 0 0 1 .63.94l.563.206a1.3 1.3 0 0 0-1.168-1.746l-.025.6Z");
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.cagpkq_ou {
  width: 1.258px;
  height: 0.293px;
  x: 12.95px;
  y: 6.615px;
  fill: var(--svg-color--4b3635, #4B3635);
  rx: 0.146px;
}

.clfu6abgw {
  d: path("M15.464 16.92a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.co6n89prj {
  fill: var(--svg-color--a97e73, #A97E73);
  d: path("m28.11 22.295l.57-1.726l-2.876-.391c-.013.094-.071.51-.203 1.43c-.13.918.125 1.664.375 2.203l1.22 2.172h1.866c-.245-.771-.844-2.77-.93-3.032c-.085-.261-.085-.48-.023-.656Z");
}

.cs3hmqbia {
  fill: var(--svg-color--ab8067, #AB8067);
  fill-rule: evenodd;
  d: path("M13.609 19.01a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.69l-1.215-.715a.4.4 0 0 1-.142-.548Z");
}

.ct6_m01bp {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
}

.d_emxobmg {
  stop-color: var(--svg-color--977266, #977266);
}

.d9bzuiwfi {
  d: path("M18.522 7.762a.696.696 0 0 0 .001-.08c-.01-.203-.103-.363-.21-.358c-.105.004-.184.173-.175.376a.684.684 0 0 0 .008.08l.376-.018Z");
}

.dd34qhijr {
  fill-rule: evenodd;
  d: path("M13.393 19.317a.45.45 0 0 1 .624-.121l.973.656a.45.45 0 0 1-.503.746l-.973-.656a.45.45 0 0 1-.121-.625Z");
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.dm4voe-la {
  d: path("M0 0h2.371v3.351H0z");
}

.dyerczfxv {
  fill: var(--svg-color--baa4c5, #BAA4C5);
  d: path("m4.703 26.399l.376-.718a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.075l-.22.874l2.004-.158Z");
}

.e1ueer7az {
  stop-color: var(--svg-color--845a4d, #845A4D);
  stop-opacity: 0;
}

.e4agtf5yi {
  stop-color: var(--svg-color--8c5772, #8C5772);
}

.ef2_oackn {
  stop-color: var(--svg-color--8e5756, #8E5756);
  stop-opacity: 0;
}

.em0115xht {
  stop-color: var(--svg-color--b38f75, #B38F75);
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.eotc9zblf {
  stop-color: var(--svg-color--946660, #946660);
  stop-opacity: 0;
}

.ez2eb00jb {
  fill: var(--svg-color--52333b, #52333B);
  d: path("M14.87 5.47c.209-.441.024-.925-.074-1.093c-.368-.754-1.2-.84-1.69-.651c-.575.222-.75.347-1.652.045c-.904-.303-2.038-.235-2.676.8c-.64 1.033-.052 2.256-.227 2.9c-.175.643-.593.688-.781 1.434c-.176 1.038.439 1.747 1.005 1.928c.566.18 1.754.08 2.182-.861c.702-1.54.307-2.3.48-3.082c.173-.78.653-.981 1.501-.771c.998.247 1.655-.063 1.932-.65Z");
}

.f0fnh4o-w {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m29.081 25.668l.66 2.62a.25.25 0 0 1-.242.312h-4.441c-.102 0-.196-.06-.22-.159c-.127-.503.196-.866.763-1.157a86.214 86.214 0 0 0 1.696-.9l-.376-.719a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.076Z");
}

.f8s-ypx6s {
  fill: var(--svg-color--8261c5, #8261C5);
  d: path("m29.072 14.522l-.664-.664l-3.68 3.953l1.21 1.015s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.055h3.025a.05.05 0 0 0 .047-.035c.16-.505.565-1.791.938-3.238c.409-1.592-.287-2.519-.66-2.844Z");
}

.f8y-tl9do {
  d: path("m24.855 20.49l1.082-1.007l1.149-1.024l-3.133-1.906a78.474 78.474 0 0 1-1.4 1.66a.05.05 0 0 0 .003.068l2.23 2.207a.05.05 0 0 0 .07.001Z");
}

.fk4zrip8m {
  stop-color: var(--svg-color--483159, #483159);
}

.ft5dv1b6b {
  fill: none;
}

.fuqwctlqz {
  stop-color: var(--svg-color--946466, #946466);
}

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
}

.gbitypbvx {
  stop-color: var(--svg-color--956c5a, #956C5A);
}

.gfdvmwbxq {
  stop-color: var(--svg-color--4c2c8f, #4C2C8F);
  stop-opacity: 0;
}

.gl6qqfkzm {
  stop-color: var(--svg-color--6f529a, #6F529A);
}

.gn8dr-4uj {
  stop-color: var(--svg-color--937861, #937861);
  stop-opacity: 0;
}

.gnc23j6vq {
  d: path("m11.651 8.405l-.146-1.586a.797.797 0 0 0 .146 1.586Z");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h44vs32ne {
  fill: var(--svg-color--8261c4, #8261C4);
  d: path("M6.826 10.748a2.696 2.696 0 0 1 3.753 3.873l-3.262 3.178a2.71 2.71 0 1 1-3.77-3.892l3.28-3.16Z");
}

.h8s3t1bxb {
  fill: var(--svg-color--a97e73, #A97E73);
  d: path("m3.89 22.31l-.57-1.726l2.876-.39c.013.093.071.51.203 1.43c.13.918-.125 1.663-.375 2.202l-1.22 2.172H2.939c.245-.77.843-2.77.93-3.031c.085-.262.085-.48.023-.656Z");
}

.ha7m41bdf {
  d: path("m11.674 8.316l-.218-1.577a.796.796 0 0 0 .218 1.577Z");
}

.har2clbwm {
  stop-color: var(--svg-color--87625a, #87625A);
}

.hh9ibwbje {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
  stop-opacity: 0;
}

.hq4v5hb0q {
  fill-rule: evenodd;
  d: path("M12.178 3.8a.25.25 0 0 1 .162.314l-.95 2.968a.25.25 0 0 1-.476-.152l.95-2.969a.25.25 0 0 1 .314-.162Z");
}

.hse6h5b7p {
  fill-rule: evenodd;
  d: path("M13.373 18.479a.4.4 0 0 1 .55-.136c.404.246.859.47 1.375.648a.4.4 0 1 1-.26.757a7.88 7.88 0 0 1-1.53-.72a.4.4 0 0 1-.135-.55Z");
}

.hu6qrb-cx {
  fill-rule: evenodd;
  d: path("M27.133 12.52a.1.1 0 0 0-.09-.141l-3.873-.058l.035-2.34l4.25.061c1.653.024 2.653 1.726 1.919 3.234l-1.186 2.544l-2.062-1.019l1.007-2.282Z");
}

.i_emxkhmq {
  stop-color: var(--svg-color--442f88, #442F88);
}

.i_qwr-19p {
  stop-color: var(--svg-color--a07364, #A07364);
}

.i18dd_bid {
  d: path("M14.672 6.938c-.002-.879-.267-1.315-.395-1.444l-4.087-.187l-.226 3.461c.843 2.367 3.734 2.598 4.205 1.778c.471-.82.506-2.59.503-3.608Z");
}

.i2p0hhbue {
  stop-color: var(--svg-color--734548, #734548);
}

.i7saq21uo {
  d: path("m2.928 14.537l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.758a.05.05 0 0 1-.05.054H3.255a.05.05 0 0 1-.047-.034a63.154 63.154 0 0 1-.938-3.239c-.409-1.592.287-2.518.66-2.844Z");
}

.ichkr_bpe {
  d: path("M19.316 9.27h2.371v3.351h-2.371z");
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.igiy6tomy {
  stop-color: var(--svg-color--90595f, #90595F);
}

.it-j5xbsh {
  fill: var(--svg-color--a8836c, #A8836C);
  fill-rule: evenodd;
  d: path("M15.127 18.31a.4.4 0 0 1-.188.533l-.996.477a.4.4 0 0 1-.346-.722l.996-.476a.4.4 0 0 1 .534.188Z");
}

.iuayy_bud {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M24.02 12.037c-.26 1.313-1.738 4.244-5.563 5.47");
}

.iwvg1ab2u {
  fill: var(--svg-color--9d91a7, #9D91A7);
  d: path("m27.297 26.383l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.076l.22.874l-2.004-.159Z");
}

.iy_62gb7c {
  stop-color: var(--svg-color--946660, #946660);
}

.j3zvk_bdt {
  stop-color: var(--svg-color--633ea0, #633EA0);
}

.jf74cfb1u {
  d: path("M16.086 15.632a.384.384 0 1 0 0 .769h.518a.065.065 0 0 1 0 .129h1.158v-.13h.254l-.31-.309a1.568 1.568 0 0 0-1.108-.459h-.512Z");
}

.jg31p_bkv {
  stop-color: var(--svg-color--8e5756, #8E5756);
}

.jh_z6ab-a {
  stop-color: var(--svg-color--8d5a69, #8D5A69);
}

.jj1uh6bhe {
  stop-color: var(--svg-color--b0866f, #B0866F);
}

.jnesarx4u {
  d: path("M10.647 10.827a2.697 2.697 0 0 0-3.821-.08l-3.234 3.126l-.045.034c-.067.064-.13.13-.188.2l-.43.43c-.373.326-1.069 1.252-.66 2.844c.372 1.447.778 2.734.938 3.24c.003.01.01.02.02.025a.052.052 0 0 0 .027.009h3.025a.05.05 0 0 0 .05-.055c-.074-.715-.268-1.758-.268-1.758l.876-.735c.133-.09.26-.192.38-.308l3.261-3.178a2.696 2.696 0 0 0 .069-3.794Z");
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jony80okq {
  stop-color: var(--svg-color--8c5772, #8C5772);
  stop-opacity: 0;
}

.jv-vvdc2h {
  stop-color: var(--svg-color--433352, #433352);
  stop-opacity: 0;
}

.k_gxsyo3c {
  d: path("m20.473 8.31l.218-1.574a.795.795 0 0 1-.218 1.575Z");
}

.k78l4l0qb {
  stop-color: var(--svg-color--633ea0, #633EA0);
  stop-opacity: 0;
}

.k8s01tfdv {
  stop-color: var(--svg-color--5e5663, #5E5663);
  stop-opacity: 0;
}

.kgukkhbth {
  stop-color: var(--svg-color--5e5663, #5E5663);
}

.kjvqytpae {
  fill: var(--svg-color--8261c4, #8261C4);
  d: path("M25.174 10.732a2.696 2.696 0 0 0-3.752 3.873l3.261 3.178a2.71 2.71 0 1 0 3.77-3.891l-3.28-3.16Z");
}

.kk51k_biz {
  fill: var(--svg-color--a38069, #A38069);
  d: path("M15.846 18.284c0-.213.173-.385.386-.385h1.385l.308.77H16.23a.385.385 0 0 1-.385-.385Z");
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.kpw5jeb1t {
  stop-color: var(--svg-color--af8c7c, #AF8C7C);
}

.kuufpibxl {
  stop-color: var(--svg-color--8362c5, #8362C5);
  stop-opacity: 0;
}

.kv-jd2a1k {
  width: 1.258px;
  height: 0.293px;
  fill: var(--svg-color--4b3635, #4B3635);
  rx: 0.146px;
}

.kzvt00ajy {
  fill-rule: evenodd;
  d: path("M8.23 11.545a1.15 1.15 0 0 1 1.388.846c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.545a1.15 1.15 0 0 1-1.585.369c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.388Z");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l5v3qe0jr {
  stop-color: var(--svg-color--b6917c, #B6917C);
}

.l6veklvwf {
  stop-color: var(--svg-color--9e94a2, #9E94A2);
}

.l7cj2r41q {
  stop-color: var(--svg-color--7e4c54, #7E4C54);
}

.l7w6j-bmv {
  stop-color: var(--svg-color--937166, #937166);
}

.la3agyb1u {
  stop-color: var(--svg-color--8f5d60, #8F5D60);
}

.lhhdsccyq {
  stop-color: var(--svg-color--a66d75, #A66D75);
  stop-opacity: 0;
}

.ljdchwceu {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m9.844 26.545l-.088-.89a.05.05 0 0 1 .05-.055h1.988a.05.05 0 0 1 .05.05v.766c.559.262 1.627.807 2.074 1.117c.378.262.441.564.438.802c-.003.155-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.lz46tfbxe {
  d: path("M17.479 6.938c.002-.879.267-1.315.395-1.444l4.087-.187l.226 3.461c-.843 2.367-3.735 2.598-4.205 1.778c-.471-.82-.506-2.59-.503-3.608Z");
}

.m6i64ob9s {
  stop-color: var(--svg-color--8e6259, #8E6259);
}

.mf6irgsiu {
  fill: var(--svg-color--a38069, #A38069);
  d: path("M15.503 17.547c0-.216.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
  stop-opacity: 0;
}

.mq17zybfl {
  stop-color: var(--svg-color--8d6dc3, #8D6DC3);
}

.mqedtfb5e {
  stop-color: var(--svg-color--423948, #423948);
}

.ms4f1oj7g {
  r: 1.281px;
}

.ms8d88bde {
  fill: var(--svg-color--8261c5, #8261C5);
  d: path("m2.928 14.537l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.758a.05.05 0 0 1-.05.054H3.255a.05.05 0 0 1-.047-.034a63.154 63.154 0 0 1-.938-3.239c-.409-1.592.287-2.518.66-2.844Z");
}

.mtqoh_bre {
  stop-color: var(--svg-color--ab8075, #AB8075);
}

.mwu89jbtt {
  fill: var(--svg-color--52333b, #52333B);
  d: path("M17.28 5.47c-.208-.441-.023-.925.075-1.093c.368-.754 1.2-.84 1.69-.651c.575.222.75.347 1.652.045c.904-.303 2.038-.235 2.676.8c.639 1.033.052 2.256.227 2.9c.175.643.593.688.78 1.434c.177 1.038-.438 1.747-1.004 1.928c-.567.18-1.754.08-2.183-.861c-.7-1.54-.306-2.3-.48-3.082c-.172-.78-.653-.981-1.5-.771c-.998.247-1.655-.063-1.932-.65Z");
}

.n1l9tez0b {
  d: path("M18.736 7.752v-.004c-.016-.35-.18-.628-.365-.62c-.185.008-.323.3-.307.65v.005l.672-.03Z");
}

.n66bp_w4m {
  stop-color: var(--svg-color--986c61, #986C61);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nb7sh9bzw {
  stop-color: var(--svg-color--b1aab6, #B1AAB6);
}

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.ng2hgzbhn {
  stop-color: var(--svg-color--bf9580, #BF9580);
}

.nkxdn3yzn {
  d: path("m2.919 25.683l-.66 2.621a.25.25 0 0 0 .242.312h4.441c.102 0 .196-.061.22-.16c.127-.503-.196-.865-.763-1.156a86.812 86.812 0 0 1-1.696-.901l.376-.718a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.075Z");
}

.nxndz826k {
  d: path("m20.477 8.316l.218-1.577a.796.796 0 0 1-.218 1.577Z");
}

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.o_ul3db6n {
  stop-color: var(--svg-color--8a6252, #8A6252);
}

.o0r6oh8jt {
  stop-color: var(--svg-color--a37c68, #A37C68);
}

.o22_o0bcf {
  stop-color: var(--svg-color--4c2c8f, #4C2C8F);
}

.o3t6sop5m {
  stop-color: var(--svg-color--834f6a, #834F6A);
}

.ocru65npv {
  stop-color: var(--svg-color--3f3646, #3F3646);
}

.oeay3te4a {
  width: 0.764px;
  height: 1.4px;
  x: 17.093px;
  y: 15.922px;
  fill: var(--svg-color--a6826a, #A6826A);
  rx: 0.382px;
}

.oelvtcc5o {
  d: path("M15.846 18.284c0-.213.173-.385.386-.385h1.385l.308.77H16.23a.385.385 0 0 1-.385-.385Z");
}

.on8sxx3yx {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
  stop-opacity: 0;
}

.op3dsib_z {
  d: path("m22.156 26.53l.088-.89a.05.05 0 0 0-.05-.056h-1.988a.05.05 0 0 0-.05.05v.767c-.559.261-1.627.807-2.074 1.117c-.378.261-.441.563-.438.801c.003.155.143.273.298.273h3.964a.25.25 0 0 0 .25-.25v-1.813Z");
}

.oqdmutx9v {
  fill: var(--svg-color--ab8067, #AB8067);
  fill-rule: evenodd;
  d: path("M13.393 19.317a.45.45 0 0 1 .624-.121l.973.656a.45.45 0 0 1-.503.746l-.973-.656a.45.45 0 0 1-.121-.625Z");
}

.oybn7vbqt {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
}

.pa0scmbsx {
  rx: 0.071px;
  ry: 0.096px;
}

.pccgwb5sy {
  fill-rule: evenodd;
  d: path("M13.609 19.01a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.69l-1.215-.715a.4.4 0 0 1-.142-.548Z");
}

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.pg63y9b5y {
  fill: var(--svg-color--714244, #714244);
  d: path("m16.47 11.658l-.59.57l.297 1.114l1.425-.505l-.08-.117a.316.316 0 0 1-.023-.31l.03-.064a.205.205 0 0 1 .185-.118h.42a.437.437 0 1 0 0-.875h-.907c-.333 0-.643.203-.756.305Z");
}

.pputyyb_m {
  stop-color: var(--svg-color--b28e77, #B28E77);
  stop-opacity: 0;
}

.pxj138bcc {
  width: 3.464px;
  height: 4.574px;
  rx: 1.732px;
}

.pxqsryxea {
  fill: var(--svg-color--a38069, #A38069);
  d: path("M16.086 15.632a.384.384 0 1 0 0 .769h.518a.065.065 0 0 1 0 .129h1.158v-.13h.254l-.31-.309a1.568 1.568 0 0 0-1.108-.459h-.512Z");
}

.pyu7r8zmo {
  stop-color: var(--svg-color--9170c6, #9170C6);
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.q2gydu3zd {
  stop-color: var(--svg-color--3e3a3f, #3E3A3F);
  stop-opacity: 0;
}

.q2i415kkt {
  d: path("M15.503 17.547c0-.216.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.q5fkj53wg {
  stop-color: var(--svg-color--a36968, #A36968);
}

.qihskpbeg {
  stop-color: var(--svg-color--524e8d, #524E8D);
  stop-opacity: 0;
}

.qn4r5dznz {
  stop-color: var(--svg-color--774f8d, #774F8D);
  stop-opacity: 0;
}

.qpxjwkb-f {
  stop-color: var(--svg-color--774f8d, #774F8D);
}

.qu7wy3byg {
  d: path("M9.172 22.154L7.133 20.35l2.156-2.188a69.05 69.05 0 0 0 1.903 2.278c.67.77.758 1.77.738 2.261l-.102 2.899H9.805a295.62 295.62 0 0 1-.242-2.727a.954.954 0 0 0-.39-.719Z");
}

.qx3t-styr {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m22.156 26.53l.088-.89a.05.05 0 0 0-.05-.056h-1.988a.05.05 0 0 0-.05.05v.767c-.559.261-1.627.807-2.074 1.117c-.378.261-.441.563-.438.801c.003.155.143.273.298.273h3.964a.25.25 0 0 0 .25-.25v-1.813Z");
}

.qyp-c9u-k {
  cx: 17.687px;
  cy: 17.374px;
  fill: var(--svg-color--a57f6a, #A57F6A);
  rx: 0.661px;
  ry: 1.066px;
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.r7-2aybwm {
  stop-color: var(--svg-color--653d99, #653D99);
}

.r7qeq_bxt {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.248px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.rbrbnox1k {
  d: path("m16.074 11.83l.536-.515c.123-.111.461-.332.824-.332h.988a.476.476 0 1 1 0 .953h-.866a.224.224 0 0 0-.202.129l-.033.069a.344.344 0 0 0-.002.288l.557-.039a.516.516 0 0 1 .07 1.03l-.669.046c-.739 1.025-1.884 2.055-3.902 2.228c-2.386.057-3.712-1.182-4.258-1.69a9.14 9.14 0 0 0-.108-.101l-.103-.091a1.15 1.15 0 1 1 1.47-1.77c.023.02.077-.012.133-.046c.064-.038.132-.078.163-.05c.054.047.11.099.17.154c.497.455 1.236 1.132 2.533 1.132c.391 0 .884-.013 1.408-.336c.51-.315.937-.7 1.167-.95a.662.662 0 0 1 .124-.108Z");
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
}

.rknzqr02l {
  stop-color: var(--svg-color--695d73, #695D73);
  stop-opacity: 0;
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.rpf2vrbvv {
  stop-color: var(--svg-color--90595f, #90595F);
  stop-opacity: 0;
}

.rvn6dnbeu {
  d: path("m7.145 20.505l-1.082-1.007l-1.149-1.023l3.133-1.906c.244.31 1.015 1.213 1.4 1.66a.05.05 0 0 1-.003.068l-2.23 2.207a.05.05 0 0 1-.07 0Z");
}

.rwshkknje {
  stop-color: var(--svg-color--9f6254, #9F6254);
  stop-opacity: 0;
}

.s94uheblk {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m2.919 25.683l-.66 2.621a.25.25 0 0 0 .242.312h4.441c.102 0 .196-.061.22-.16c.127-.503-.196-.865-.763-1.156a86.812 86.812 0 0 1-1.696-.901l.376-.718a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.075Z");
}

.sasdif2nd {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M13.305 9.124c0-.068.056-.124.124-.124h.607a.124.124 0 0 1 0 .248h-.607a.124.124 0 0 1-.124-.124Zm5.541 0A.124.124 0 0 0 18.722 9h-.608a.124.124 0 0 0 0 .248h.608a.124.124 0 0 0 .124-.124Z");
}

.sf5518bjn {
  stop-color: var(--svg-color--744fbd, #744FBD);
}

.shic-ydjf {
  stop-color: var(--svg-color--2e2d2f, #2E2D2F);
}

.sspda2v0w {
  stop-color: var(--svg-color--6e3c45, #6E3C45);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t77q9um-l {
  stop-color: var(--svg-color--744fbd, #744FBD);
  stop-opacity: 0;
}

.tee9rqeex {
  d: path("M14.869 8.005a1.1 1.1 0 0 1-.26-.513l-.196-.01l-.056 1.233c.228.16.565.152.676-.068c.094-.189.04-.431-.164-.642Z");
}

.tmqabdcjp {
  fill-rule: evenodd;
  d: path("M11.102 8.556a.25.25 0 0 1 .325.137c.1.247.285.646.511 1.039c.23.398.488.766.732.975a.25.25 0 1 1-.324.38c-.312-.267-.606-.697-.841-1.106a9.538 9.538 0 0 1-.541-1.1a.25.25 0 0 1 .138-.325Z");
}

.ttoyfzbaw {
  stop-color: var(--svg-color--845a4d, #845A4D);
}

.tx5lqdb2i {
  stop-color: var(--svg-color--956c5a, #956C5A);
  stop-opacity: 0;
}

.tz_1rgbcq {
  stop-color: var(--svg-color--b27468, #B27468);
  stop-opacity: 0;
}

.u3tp_1b4z {
  stroke: var(--svg-color--b18472, #B18472);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.804 13.685c.38.25 1.469.722 2.781.61c1.64-.14 2.656-1.047 3.125-1.922");
}

.u84rtio_o {
  stop-color: var(--svg-color--bd9680, #BD9680);
}

.u86qg0qzt {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.078 7.782l-1.082-.05c.02-.428.278-.764.576-.75c.3.013.526.371.506.8Zm3.995 0l1.082-.05c-.02-.428-.278-.764-.577-.75c-.298.013-.525.371-.505.8Z");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uh2quobbn {
  fill: var(--svg-color--a47c6e, #A47C6E);
  fill-rule: evenodd;
  d: path("M13.025 19.832a.4.4 0 0 1 .56-.086l.746.547a.4.4 0 1 1-.473.645l-.746-.547a.4.4 0 0 1-.087-.559Z");
}

.ut_jylbhb {
  fill-rule: evenodd;
  d: path("M13.025 19.832a.4.4 0 0 1 .56-.086l.746.547a.4.4 0 1 1-.473.645l-.746-.547a.4.4 0 0 1-.087-.559Z");
}

.uzo1bebwx {
  d: path("m22.828 22.139l2.039-1.805l-2.156-2.187a69.097 69.097 0 0 1-1.903 2.277c-.67.77-.758 1.77-.738 2.262l.102 2.898h2.023c.068-.734.211-2.308.242-2.726a.954.954 0 0 1 .39-.72Z");
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vc4p3ibvk {
  fill: var(--svg-color--9f7a62, #9F7A62);
  fill-rule: evenodd;
  d: path("M23.727 11.805c.627.167 1 .81.833 1.438c-.25.937-.826 1.86-1.893 3.008c-1.075 1.158-2.67 2.248-4.615 2.414a1.175 1.175 0 0 1-1.27-1.072c-.055-.646.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.998c.167-.627.811-1 1.438-.833Z");
}

.voxhk3bis {
  d: path("M21.353 10.811a2.697 2.697 0 0 1 3.821-.079l3.234 3.126l.045.034c.067.064.13.13.188.2l.43.43c.373.325 1.069 1.252.66 2.844a62.491 62.491 0 0 1-.938 3.239a.047.047 0 0 1-.02.026a.052.052 0 0 1-.027.008h-3.025a.05.05 0 0 1-.05-.055c.075-.714.268-1.758.268-1.758l-.876-.734a2.72 2.72 0 0 1-.38-.309l-3.261-3.178a2.696 2.696 0 0 1-.069-3.794Z");
}

.vvr97nuie {
  fill: var(--svg-color--ab8067, #AB8067);
  fill-rule: evenodd;
  d: path("M13.373 18.479a.4.4 0 0 1 .55-.136c.404.246.859.47 1.375.648a.4.4 0 1 1-.26.757a7.88 7.88 0 0 1-1.53-.72a.4.4 0 0 1-.135-.55Z");
}

.vwbmp8jnk {
  stop-color: var(--svg-color--7e5253, #7E5253);
  stop-opacity: 0;
}

.w9s72m9ak {
  d: path("M17.28 5.47c-.208-.441-.023-.925.075-1.093c.368-.754 1.2-.84 1.69-.651c.575.222.75.347 1.652.045c.904-.303 2.038-.235 2.676.8c.639 1.033.052 2.256.227 2.9c.175.643.593.688.78 1.434c.177 1.038-.438 1.747-1.004 1.928c-.567.18-1.754.08-2.183-.861c-.7-1.54-.306-2.3-.48-3.082c-.172-.78-.653-.981-1.5-.771c-.998.247-1.655-.063-1.932-.65Z");
}

.w9zau2kqh {
  stop-color: var(--svg-color--b68976, #B68976);
}

.wfbebvbje {
  cx: 10.996px;
  cy: 7.865px;
  r: 1.281px;
}

.wjxjx823k {
  d: path("M13.415 7.752v-.004c.016-.35.18-.628.365-.62c.185.008.322.3.306.65v.005l-.671-.03Z");
}

.wyzmbm91v {
  stop-color: var(--svg-color--a1786f, #A1786F);
}

.wzgbz6ynl {
  fill: var(--svg-color--ad8569, #AD8569);
  fill-rule: evenodd;
  d: path("M8.23 11.545a1.15 1.15 0 0 1 1.388.846c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.545a1.15 1.15 0 0 1-1.585.369c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.388Z");
}

.x1x-5bk_s {
  cx: 18.247px;
  cy: 7.389px;
  rx: 0.071px;
  ry: 0.096px;
}

.x7ihk88zx {
  d: path("m11.678 8.31l-.218-1.574a.795.795 0 0 0 .218 1.575Z");
}

.xf26kynrw {
  d: path("M17.282 8.005a1.1 1.1 0 0 0 .26-.513l.196-.01l.056 1.233c-.228.16-.566.152-.676-.068c-.094-.189-.04-.431.164-.642Z");
}

.xfcyplbyz {
  stop-color: var(--svg-color--654e4b, #654E4B);
  stop-opacity: 0;
}

.xh1g2eduz {
  d: path("M11.844 26.405v-.755a.05.05 0 0 0-.05-.05H9.805a.05.05 0 0 0-.05.055l.089.89v.02l2-.16Z");
}

.xoi0djbjo {
  stop-color: var(--svg-color--5f4099, #5F4099);
}

.xqn0te1rl {
  d: path("M14.87 5.47c.209-.441.024-.925-.074-1.093c-.368-.754-1.2-.84-1.69-.651c-.575.222-.75.347-1.652.045c-.904-.303-2.038-.235-2.676.8c-.64 1.033-.052 2.256-.227 2.9c-.175.643-.593.688-.781 1.434c-.176 1.038.439 1.747 1.005 1.928c.566.18 1.754.08 2.182-.861c.702-1.54.307-2.3.48-3.082c.173-.78.653-.981 1.501-.771c.998.247 1.655-.063 1.932-.65Z");
}

.xvt5tsb3a {
  stop-color: var(--svg-color--a36968, #A36968);
  stop-opacity: 0;
}

.y4pe4ezsu {
  stop-color: var(--svg-color--271e2e, #271E2E);
}

.ye_szro2v {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.248px;
  rx: 1.732px;
}

.yfa5ic60r {
  fill-rule: evenodd;
  d: path("M19.973 3.8a.25.25 0 0 0-.162.314l.95 2.968a.25.25 0 1 0 .475-.152l-.949-2.969a.25.25 0 0 0-.314-.162Z");
}

.yq97qkmjj {
  d: path("m29.072 14.522l-.664-.664l-3.68 3.953l1.21 1.015s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.055h3.025a.05.05 0 0 0 .047-.035c.16-.505.565-1.791.938-3.238c.409-1.592-.287-2.519-.66-2.844Z");
}

.yren7o-8v {
  stop-color: var(--svg-color--937861, #937861);
}

.yudrekboq {
  d: path("M20.156 26.39v-.756a.05.05 0 0 1 .05-.05h1.989a.05.05 0 0 1 .05.055l-.089.89v.02l-2-.16Z");
}

.yxyrfz-2l {
  stop-color: var(--svg-color--a75461, #A75461);
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.z63k8kqqf {
  fill: var(--svg-color--a57c63, #A57C63);
  d: path("m16.074 11.83l.536-.515c.123-.111.461-.332.824-.332h.988a.476.476 0 1 1 0 .953h-.866a.224.224 0 0 0-.202.129l-.033.069a.344.344 0 0 0-.002.288l.557-.039a.516.516 0 0 1 .07 1.03l-.669.046c-.739 1.025-1.884 2.055-3.902 2.228c-2.386.057-3.712-1.182-4.258-1.69a9.14 9.14 0 0 0-.108-.101l-.103-.091a1.15 1.15 0 1 1 1.47-1.77c.023.02.077-.012.133-.046c.064-.038.132-.078.163-.05c.054.047.11.099.17.154c.497.455 1.236 1.132 2.533 1.132c.391 0 .884-.013 1.408-.336c.51-.315.937-.7 1.167-.95a.662.662 0 0 1 .124-.108Z");
}

.z8pr35bty {
  stroke: var(--svg-color--ba937f, #BA937F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.66 12.49c.073 1.376 2.032 4.876 4.235 6.141");
}

.z8v1d3bmk {
  d: path("M13.629 7.762a.696.696 0 0 1-.001-.08c.01-.203.103-.363.21-.358c.105.004.184.173.175.376a.707.707 0 0 1-.008.08l-.376-.018Z");
}

.zgtcnu2sf {
  stop-color: var(--svg-color--a17471, #A17471);
  stop-opacity: 0;
}

.zhjbr8yrc {
  stop-color: var(--svg-color--896056, #896056);
}

.zjmmjyoar {
  stop-color: var(--svg-color--554f5c, #554F5C);
}

.zp0b4-bhz {
  d: path("m9.844 26.545l-.088-.89a.05.05 0 0 1 .05-.055h1.988a.05.05 0 0 1 .05.05v.766c.559.262 1.627.807 2.074 1.117c.378.262.441.564.438.802c-.003.155-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.zy9nvz9pf {
  stop-color: var(--svg-color--654e4b, #654E4B);
}

</style>
