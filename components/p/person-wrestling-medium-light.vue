<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#svgIDa)" transform="rotate(-23.31 19.316 9.21)" class="x0vfftb6r"/><path fill="url(#svgIDb)" transform="scale(-1 1) rotate(-23.31 15.984 35.352)" class="dm4voe-la"/><path class="mqj76hbqm"/><g filter="url(#svgIDc)"><path class="tozx5obpz"/><path fill="url(#svgIDd)" class="fcsxqnbqr"/></g><g filter="url(#svgIDe)"><path class="olnp00bal"/></g><path fill="url(#svgIDf)" class="sln7mgqoj"/><path fill="url(#svgIDg)" class="sln7mgqoj"/><path fill="url(#svgIDh)" class="sln7mgqoj"/><path fill="url(#svgIDi)" class="ps7q97bxk"/><path fill="url(#svgIDj)" class="ps7q97bxk"/><path fill="url(#svgIDk)" class="ps7q97bxk"/><g filter="url(#svgIDl)"><path class="zt8u8ubth"/></g><g filter="url(#svgIDm)"><path class="c9vx4xx-e"/></g><g filter="url(#svgIDn)"><path class="c4o6i4gil"/><path fill="url(#svgIDo)" class="d1dcbyb2o"/></g><path fill="url(#svgIDp)" class="r1qdbacdf"/><path fill="url(#svgIDq)" class="r1qdbacdf"/><g filter="url(#svgIDr)"><path class="s9njfgb_y"/><path fill="url(#svgIDs)" class="rnt_ycbgu"/><path fill="url(#svgIDt)" class="rnt_ycbgu"/><path fill="url(#svgIDu)" class="rnt_ycbgu"/></g><g filter="url(#svgIDv)"><path class="xagwtmr2g"/></g><g filter="url(#svgIDw)"><path class="d-weszb8y"/><path fill="url(#svgIDx)" class="zcjltpb4i"/><path fill="url(#svgIDy)" class="zcjltpb4i"/><path fill="url(#svgIDz)" class="zcjltpb4i"/></g><g filter="url(#svgIDA)"><path fill="url(#svgIDB)" class="qfkd0ob_i"/></g><g filter="url(#svgIDC)"><rect stroke="url(#svgIDD)" transform="rotate(45 8.633 10.188)" class="qpafcfb4e"/></g><rect fill="url(#svgIDE)" transform="rotate(45 8.633 10.188)" class="gh-ifubji"/><rect fill="url(#svgIDF)" transform="rotate(45 8.633 10.188)" class="gh-ifubji"/><g filter="url(#svgIDG)"><path clip-rule="evenodd" class="wi3vdjbhe"/></g><path clip-rule="evenodd" class="zp759pfge"/><path fill="url(#svgIDH)" clip-rule="evenodd" class="rt_dddp6w"/><path clip-rule="evenodd" class="u0wlypb1d"/><path fill="url(#svgIDI)" clip-rule="evenodd" class="txvpahc1h"/><path clip-rule="evenodd" class="xqb1sxmbd"/><path fill="url(#svgIDJ)" clip-rule="evenodd" class="iv6ebfcln"/><path clip-rule="evenodd" class="l2ghe_s4e"/><path fill="url(#svgIDK)" clip-rule="evenodd" class="y-whk56hl"/><path clip-rule="evenodd" class="n04al3b3c"/><path fill="url(#svgIDL)" clip-rule="evenodd" class="yyaflybwa"/><path fill="url(#svgIDM)" clip-rule="evenodd" class="evxwq240k"/><path fill="url(#svgIDN)" clip-rule="evenodd" class="evxwq240k"/><path fill="url(#svgIDO)" clip-rule="evenodd" class="evxwq240k"/><rect transform="rotate(-28.166 17.093 15.863)" class="fwjng4bpx"/><path fill="url(#svgIDP)" class="lshqpgbqp"/><path fill="url(#svgIDQ)" class="lshqpgbqp"/><path fill="url(#svgIDR)" class="lshqpgbqp"/><path fill="url(#svgIDS)" class="oo2c8jblg"/><path fill="url(#svgIDT)" class="oo2c8jblg"/><path fill="url(#svgIDU)" class="oo2c8jblg"/><g filter="url(#svgIDV)"><path class="gkj8dyg7i"/></g><g filter="url(#svgIDW)"><path class="d5u-kgbfz"/></g><g filter="url(#svgIDX)"><path class="gs4mjcb0j"/><path fill="url(#svgIDY)" class="byasxzbbd"/></g><path fill="url(#svgIDZ)" class="gc63m4sma"/><path fill="url(#svgIDaa)" class="gc63m4sma"/><g filter="url(#svgIDab)"><path class="tu9tajbkl"/><path fill="url(#svgIDac)" class="bvyrbtq3r"/><path fill="url(#svgIDad)" class="bvyrbtq3r"/><path fill="url(#svgIDae)" class="bvyrbtq3r"/></g><g filter="url(#svgIDaf)"><path class="uj1cqbfji"/></g><g filter="url(#svgIDag)"><path class="se2cvmb9b"/><path fill="url(#svgIDah)" class="biii-5b1l"/><path fill="url(#svgIDai)" class="biii-5b1l"/><path fill="url(#svgIDaj)" class="biii-5b1l"/></g><g filter="url(#svgIDak)"><path fill="url(#svgIDal)" class="znbv98bgs"/></g><g filter="url(#svgIDam)"><rect stroke="url(#svgIDan)" transform="scale(-1 1) rotate(45 -23.963 -23.12)" class="gg2ehgbth"/></g><rect fill="url(#svgIDao)" transform="scale(-1 1) rotate(45 -23.963 -23.12)" class="pxj138bcc"/><rect fill="url(#svgIDap)" transform="scale(-1 1) rotate(45 -23.963 -23.12)" class="pxj138bcc"/><path clip-rule="evenodd" class="pb2gbr7kw"/><path fill="url(#svgIDaq)" clip-rule="evenodd" class="o3u3_rbmt"/><path class="d4rjt3rrs"/><path fill="url(#svgIDar)" class="w-okwbk4h"/><path class="gmw4iybjp"/><path fill="url(#svgIDas)" class="yrfae15se"/><path class="xk6m9ab-u"/><path fill="url(#svgIDat)" class="pekz8jb1t"/><path fill="url(#svgIDau)" class="pekz8jb1t"/><path class="rwnj23csn"/><path fill="url(#svgIDav)" class="kd8ah_bdi"/><g filter="url(#svgIDaw)"><path class="m4vchmg3s"/></g><g filter="url(#svgIDax)"><path stroke="url(#svgIDay)" class="hef8pn1do"/></g><g filter="url(#svgIDaz)"><path fill="url(#svgIDaA)" class="l4v-g_vax"/></g><path fill="url(#svgIDaB)" class="kq3eo2bwh"/><path fill="url(#svgIDaC)" class="kq3eo2bwh"/><path fill="url(#svgIDaD)" class="kq3eo2bwh"/><path fill="url(#svgIDaE)" class="tf3omaceq"/><path fill="url(#svgIDaF)" class="tf3omaceq"/><path fill="url(#svgIDaG)" class="tf3omaceq"/><g filter="url(#svgIDaH)"><ellipse class="gr47531og"/></g><path fill="url(#svgIDaI)" class="n4fw05ymv"/><g filter="url(#svgIDaJ)"><path fill="url(#svgIDaK)" class="eq14s50yt"/><path fill="url(#svgIDaL)" class="eq14s50yt"/><path fill="url(#svgIDaM)" class="eq14s50yt"/><path fill="url(#svgIDaN)" class="eq14s50yt"/></g><g filter="url(#svgIDaO)"><path fill="url(#svgIDaP)" class="ek67jac7r"/><path fill="url(#svgIDaQ)" class="ek67jac7r"/><path fill="url(#svgIDaR)" class="ek67jac7r"/><path fill="url(#svgIDaS)" class="ek67jac7r"/></g><path fill="url(#svgIDaT)" class="ca4tncnwn"/><path fill="url(#svgIDaU)" class="ca4tncnwn"/><path fill="url(#svgIDaV)" class="ca4tncnwn"/><path class="exc6wlshr"/><path fill="url(#svgIDaW)" class="em3zy1brs"/><path fill="url(#svgIDaX)" class="zll2ktbmo"/><ellipse fill="url(#svgIDaY)" transform="scale(-1 1) rotate(24.61 -23.337 -28.442)" class="f6mg5tnmy"/><g filter="url(#svgIDaZ)"><path fill="url(#svgIDba)" class="ol8ztc22n"/></g><path fill="url(#svgIDbb)" clip-rule="evenodd" class="p9w8m_bzp"/><path fill="url(#svgIDbc)" clip-rule="evenodd" class="p9w8m_bzp"/><path fill="url(#svgIDbd)" clip-rule="evenodd" class="p9w8m_bzp"/><path fill="url(#svgIDbe)" clip-rule="evenodd" class="v7wb7cclw"/><path fill="url(#svgIDbf)" clip-rule="evenodd" class="v7wb7cclw"/><circle fill="url(#svgIDbg)" class="hpo9rcg8j"/><circle fill="url(#svgIDbh)" class="hpo9rcg8j"/><circle fill="url(#svgIDbi)" class="hpo9rcg8j"/><g filter="url(#svgIDbj)"><rect class="z3_s1-bxc"/></g><path class="ljdquke8v"/><path fill="url(#svgIDbk)" class="d_2x8ab_w"/><path fill="url(#svgIDbl)" class="d_2x8ab_w"/><path fill="url(#svgIDbm)" class="d_2x8ab_w"/><path fill="url(#svgIDbn)" class="zn3ibrd7r"/><path fill="url(#svgIDbo)" class="zn3ibrd7r"/><path fill="url(#svgIDbp)" class="zn3ibrd7r"/><path fill="url(#svgIDbq)" class="rpqz5ojcj"/><g filter="url(#svgIDbr)"><path fill="url(#svgIDbs)" class="koojhabhx"/><path fill="url(#svgIDbt)" class="koojhabhx"/><path fill="url(#svgIDbu)" class="koojhabhx"/><path fill="url(#svgIDbv)" class="koojhabhx"/></g><g filter="url(#svgIDbw)"><path fill="url(#svgIDbx)" class="h3745i65f"/><path fill="url(#svgIDby)" class="h3745i65f"/><path fill="url(#svgIDbz)" class="h3745i65f"/><path fill="url(#svgIDbA)" class="h3745i65f"/></g><path fill="url(#svgIDbB)" class="gybwkccsq"/><path fill="url(#svgIDbC)" class="gybwkccsq"/><path fill="url(#svgIDbD)" class="gybwkccsq"/><path class="jth06oa-o"/><path fill="url(#svgIDbE)" class="hbnc11boo"/><path fill="url(#svgIDbF)" class="w16l4dbiv"/><ellipse fill="url(#svgIDbG)" transform="rotate(24.61 18.07 7.135)" class="tmmfhpbga"/><g filter="url(#svgIDbH)"><path fill="url(#svgIDbI)" class="w4vm-cb_s"/></g><path fill="url(#svgIDbJ)" clip-rule="evenodd" class="cp-562b3l"/><path fill="url(#svgIDbK)" clip-rule="evenodd" class="cp-562b3l"/><path fill="url(#svgIDbL)" clip-rule="evenodd" class="cp-562b3l"/><path fill="url(#svgIDbM)" clip-rule="evenodd" class="w2eqh57fa"/><path fill="url(#svgIDbN)" clip-rule="evenodd" class="w2eqh57fa"/><circle fill="url(#svgIDbO)" transform="matrix(-1 0 0 1 21.037 7.806)" class="ms4f1oj7g"/><circle fill="url(#svgIDbP)" transform="matrix(-1 0 0 1 21.037 7.806)" class="ms4f1oj7g"/><circle fill="url(#svgIDbQ)" transform="matrix(-1 0 0 1 21.037 7.806)" class="ms4f1oj7g"/><g filter="url(#svgIDbR)"><rect transform="matrix(-1 0 0 1 19.084 6.556)" class="biugcq6id"/></g><path class="yl7ausbxx"/><defs><radialGradient id="svgIDa" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 19.282 10.661)" gradientUnits="userSpaceOnUse"><stop class="u2n90vbun"/><stop offset="1" class="q1txceb2f"/></radialGradient><radialGradient id="svgIDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 -.033 1.45)" gradientUnits="userSpaceOnUse"><stop class="p5wg8876f"/><stop offset=".919" class="hy8b1ubxg"/></radialGradient><radialGradient id="svgIDd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71095 2.35327 -5.20382 -5.99476 18.899 10.923)" gradientUnits="userSpaceOnUse"><stop class="qy3mcrgdk"/><stop offset="1" class="gy1xmobvy"/></radialGradient><radialGradient id="svgIDf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 11.656 25.54)" gradientUnits="userSpaceOnUse"><stop class="uq4h3zxiv"/><stop offset="1" class="l3r47ffcx"/></radialGradient><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(2.14185 1.875 -.94292 1.07712 7.39 20.509)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="sgqr937ow"/><stop offset="1" class="icb-xabyb"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(144.26 2.237 11.093) scale(1.23051 3.4979)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="ammexac5i"/><stop offset="1" class="kik7_ob9t"/></radialGradient><radialGradient id="svgIDo" cx="0" cy="0" r="1" gradientTransform="rotate(-134.195 7.094 8.075) scale(2.212 .64075)" gradientUnits="userSpaceOnUse"><stop class="jjhblb54u"/><stop offset="1" class="bq0pg0bco"/></radialGradient><radialGradient id="svgIDp" cx="0" cy="0" r="1" gradientTransform="rotate(137.394 1.47 9.815) scale(7.8608 1.6626)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="t4m41vbgx"/><stop offset="1" class="hi6yszbkt"/></radialGradient><radialGradient id="svgIDq" cx="0" cy="0" r="1" gradientTransform="matrix(6.96877 -7.18752 5.67939 5.50654 3.781 17.822)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="qpejwlb8n"/><stop offset="1" class="p4686vbiy"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="rotate(-144.397 8.18 13.124) scale(2.17397 2.91043)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64636 -1.26563 1.72963 -2.24994 14.356 28.548)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 11.203 26.368)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="matrix(-.05524 1.73462 -1.20171 -.03827 10.37 11.467)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="bs9ct9blb"/><stop offset="1" class="uj_nqubgh"/></radialGradient><radialGradient id="svgIDF" cx="0" cy="0" r="1" gradientTransform="rotate(45 -10.457 20.15) scale(2.38098 1.16175)" gradientUnits="userSpaceOnUse"><stop class="cz--1m5fh"/><stop offset="1" class="b8hyhqehi"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="rotate(137.121 3.018 10.226) scale(3.58218 11.0839)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="wg-u6yb-o"/><stop offset="1" class="yic7b8bke"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="matrix(-.24218 1.08594 -3.51562 -.78403 14.395 18.573)" gradientUnits="userSpaceOnUse"><stop offset=".472" class="li5uyl08u"/><stop offset="1" class="m1j2mbbtp"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.30444 .89737 -2.62413 -.89026 14.56 19.222)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="li5uyl08u"/><stop offset="1" class="m1j2mbbtp"/></radialGradient><radialGradient id="svgIDK" cx="0" cy="0" r="1" gradientTransform="matrix(-.28295 .92188 -2.48547 -.76287 14.252 19.54)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="li5uyl08u"/><stop offset="1" class="m1j2mbbtp"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37499 1.625 -1.79466 -1.51854 29.313 10.634)" gradientUnits="userSpaceOnUse"><stop class="gjr9r-itc"/><stop offset="1" class="pafpa8b3r"/></radialGradient><radialGradient id="svgIDN" cx="0" cy="0" r="1" gradientTransform="matrix(2.12183 -1.33219 1.13322 1.80492 26.394 12.841)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="n7l1hg2af"/><stop offset="1" class="fd4bh7bhc"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 20.343 25.524)" gradientUnits="userSpaceOnUse"><stop class="uq4h3zxiv"/><stop offset="1" class="l3r47ffcx"/></radialGradient><radialGradient id="svgIDQ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14186 1.87499 -.94291 -1.07712 24.61 20.493)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="sgqr937ow"/><stop offset="1" class="icb-xabyb"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="matrix(.99878 .71875 -2.04315 2.83916 21.468 18.774)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="ammexac5i"/><stop offset="1" class="kik7_ob9t"/></radialGradient><radialGradient id="svgIDY" cx="0" cy="0" r="1" gradientTransform="matrix(1.542 -1.58594 .4594 .44667 25.75 18.774)" gradientUnits="userSpaceOnUse"><stop class="jjhblb54u"/><stop offset="1" class="bq0pg0bco"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="matrix(5.78575 5.3214 -1.1255 1.22372 22.803 16.029)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="t4m41vbgx"/><stop offset="1" class="hi6yszbkt"/></radialGradient><radialGradient id="svgIDaa" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9688 -7.18748 5.67936 -5.50657 28.218 17.806)" gradientUnits="userSpaceOnUse"><stop offset=".014" class="qpejwlb8n"/><stop offset=".93" class="qpejwlb8n"/><stop offset="1" class="p4686vbiy"/></radialGradient><radialGradient id="svgIDad" cx="0" cy="0" r="1" gradientTransform="matrix(1.76758 -1.26563 1.69437 2.36637 24.81 28.54)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(1.64636 -1.26562 1.72962 2.24995 17.644 28.532)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 20.797 26.353)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDao" cx="0" cy="0" r="1" gradientTransform="matrix(2.43827 .18437 -.24868 3.2888 .122 2.37)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="e31k1-bnl"/><stop offset=".865" class="tr9cr_bup"/></radialGradient><radialGradient id="svgIDap" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 2.746 3.121)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="xkrkjbk5z"/><stop offset="1" class="mvr01ib0c"/></radialGradient><radialGradient id="svgIDaq" cx="0" cy="0" r="1" gradientTransform="matrix(1.49685 3.75 -10.37919 4.14298 19.25 14.447)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="t5tj028fa"/><stop offset=".969" class="alhmdacdj"/></radialGradient><radialGradient id="svgIDau" cx="0" cy="0" r="1" gradientTransform="matrix(0 .49784 -1.34351 0 16.64 17.84)" gradientUnits="userSpaceOnUse"><stop class="kx97vubln"/><stop offset="1" class="qwnulubfe"/></radialGradient><radialGradient id="svgIDaA" cx="0" cy="0" r="1" gradientTransform="rotate(123.38 11.47 13.273) scale(2.43251 2.70978)" gradientUnits="userSpaceOnUse"><stop class="yyc9yuyiy"/><stop offset="1" class="o410gcc4i"/></radialGradient><radialGradient id="svgIDaB" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.275 2.83) scale(.82753 .4039)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDaC" cx="0" cy="0" r="1" gradientTransform="matrix(-.24716 1.2904 -1.34466 -.25755 11.478 6.967)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDaE" cx="0" cy="0" r="1" gradientTransform="matrix(-.79555 -.23096 .11273 -.3883 11.508 7.3)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDaF" cx="0" cy="0" r="1" gradientTransform="matrix(-.24742 1.29177 -1.34608 -.25783 11.474 6.97)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDaI" cx="0" cy="0" r="1" gradientTransform="matrix(-.52123 .28198 -.39803 -.73574 15.272 8.184)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="nx4bqnbvp"/><stop offset=".684" class="nkw7_sb2b"/></radialGradient><radialGradient id="svgIDaL" cx="0" cy="0" r="1" gradientTransform="matrix(.92284 -.05127 .0625 1.12513 11.267 7.415)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="svgIDaM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.67376 2.20456 0 14.435 8.713)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="s4vkc-bcm"/><stop offset="1" class="m4_ilibnz"/></radialGradient><radialGradient id="svgIDaN" cx="0" cy="0" r="1" gradientTransform="matrix(0 .42724 -.6663 0 13.529 7.466)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="svgIDaP" cx="0" cy="0" r="1" gradientTransform="matrix(-2.63249 -2.13053 3.23879 -4.00185 12.191 6.37)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="te4zz7dbn"/><stop offset="1" class="otf1z2b9l"/></radialGradient><radialGradient id="svgIDaQ" cx="0" cy="0" r="1" gradientTransform="rotate(-143.912 8.103 -.032) scale(1.62474 2.61389)" gradientUnits="userSpaceOnUse"><stop class="r-95cxbic"/><stop offset="1" class="efo8wovhu"/></radialGradient><radialGradient id="svgIDaR" cx="0" cy="0" r="1" gradientTransform="matrix(.5725 .16235 -.07977 .2813 9.384 8.372)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="cl2mrcsll"/><stop offset="1" class="hms2sfnpk"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.07471 -4.22189 0 11.661 3.163)" gradientUnits="userSpaceOnUse"><stop class="cnrrv2ghu"/><stop offset="1" class="qgurk7bxc"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.274 2.825) scale(.82748 .40388)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 2.863 8.223) scale(1.31379 1.36902)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="svgIDaW" cx="0" cy="0" r="1" gradientTransform="matrix(-.29907 0 0 -.58105 13.851 7.496)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDaX" cx="0" cy="0" r="1" gradientTransform="matrix(-.27343 0 0 -.59173 14.035 7.52)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbc" cx="0" cy="0" r="1" gradientTransform="matrix(.23047 .0586 -.60662 2.38602 11.106 6.154)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.52148 1.82813 -.23787 -.06785 12.149 4.415)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDbf" cx="0" cy="0" r="1" gradientTransform="matrix(-.35156 .1875 -.70184 -1.31597 11.985 9.43)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbg" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 12.031 7.321)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 9.715 7.806)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 12.063 8.696)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="matrix(.79471 -.23072 .11261 .38789 20.521 7.296)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDbl" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.064 15.917) scale(1.31386 1.3691)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="matrix(.79555 -.23097 .11273 .3883 20.526 7.3)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDbo" cx="0" cy="0" r="1" gradientTransform="matrix(.24742 1.29177 -1.34608 .25782 20.56 6.97)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDbq" cx="0" cy="0" r="1" gradientTransform="matrix(.52123 .28198 -.39803 .73574 16.871 8.184)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="nx4bqnbvp"/><stop offset=".684" class="nkw7_sb2b"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="matrix(-.92284 -.0512 .06243 -1.12513 20.908 7.414)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="svgIDbu" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.67376 2.20456 0 17.74 8.713)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="s4vkc-bcm"/><stop offset="1" class="m4_ilibnz"/></radialGradient><radialGradient id="svgIDbv" cx="0" cy="0" r="1" gradientTransform="matrix(0 .42724 -.6663 0 18.646 7.466)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="svgIDbx" cx="0" cy="0" r="1" gradientTransform="matrix(2.63249 -2.13053 3.23879 4.00185 19.842 6.37)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="te4zz7dbn"/><stop offset="1" class="otf1z2b9l"/></radialGradient><radialGradient id="svgIDby" cx="0" cy="0" r="1" gradientTransform="matrix(1.31297 -.95702 1.53966 2.11231 17.363 4.715)" gradientUnits="userSpaceOnUse"><stop class="r-95cxbic"/><stop offset="1" class="efo8wovhu"/></radialGradient><radialGradient id="svgIDbz" cx="0" cy="0" r="1" gradientTransform="matrix(-.5725 .16236 -.07977 -.2813 22.65 8.37)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="cl2mrcsll"/><stop offset="1" class="hms2sfnpk"/></radialGradient><radialGradient id="svgIDbA" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.07471 -4.22189 0 20.373 3.163)" gradientUnits="userSpaceOnUse"><stop class="cnrrv2ghu"/><stop offset="1" class="qgurk7bxc"/></radialGradient><radialGradient id="svgIDbB" cx="0" cy="0" r="1" gradientTransform="matrix(.79467 -.23071 .1126 .38787 20.521 7.287)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="svgIDbC" cx="0" cy="0" r="1" gradientTransform="matrix(.24715 1.29033 -1.34458 .25754 20.556 6.957)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="matrix(.29907 0 0 .58105 18.182 7.496)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDbF" cx="0" cy="0" r="1" gradientTransform="matrix(.27343 0 0 .59173 17.999 7.52)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbK" cx="0" cy="0" r="1" gradientTransform="rotate(165.735 10.079 4.386) scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbL" cx="0" cy="0" r="1" gradientTransform="matrix(.52148 1.82813 -.23787 .06785 19.885 4.415)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDbN" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .1875 -.70185 1.31597 20.05 9.43)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbO" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 2.316 .797)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbP" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 0 1.281)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 2.348 2.172)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><linearGradient id="svgIDi" x1="6.625" x2="8.406" y1="19.946" y2="18.259" gradientUnits="userSpaceOnUse"><stop class="xylxrh5lr"/><stop offset="1" class="dpng9pbvi"/></linearGradient><linearGradient id="svgIDj" x1="8.328" x2="8.153" y1="19.337" y2="19.153" gradientUnits="userSpaceOnUse"><stop class="o5qj3ac-m"/><stop offset="1" class="a151cabub"/></linearGradient><linearGradient id="svgIDk" x1="5.563" x2="6.844" y1="19.384" y2="19.446" gradientUnits="userSpaceOnUse"><stop offset=".28" class="azjp5ub3a"/><stop offset="1" class="yvalde4js"/></linearGradient><linearGradient id="svgIDs" x1="2.251" x2="2.836" y1="28.196" y2="28.329" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDu" x1="5.625" x2="5.625" y1="28.556" y2="28.232" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDx" x1="9.756" x2="10.3" y1="28.321" y2="28.305" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDz" x1="12.899" x2="12.899" y1="28.548" y2="28.224" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDD" x1="10.365" x2="10.365" y1="10.188" y2="14.762" gradientUnits="userSpaceOnUse"><stop class="d9dzcxb5n"/><stop offset="1" class="aqyl6fvtq"/></linearGradient><linearGradient id="svgIDL" x1="13.406" x2="13.641" y1="20.712" y2="20.282" gradientUnits="userSpaceOnUse"><stop offset=".245" class="bmw2gli7r"/><stop offset="1" class="r3qtxmtcb"/></linearGradient><linearGradient id="svgIDO" x1="25.301" x2="25.832" y1="9.922" y2="11.165" gradientUnits="userSpaceOnUse"><stop class="dr2k0bhek"/><stop offset="1" class="vvdzqypxx"/></linearGradient><linearGradient id="svgIDS" x1="25.375" x2="23.593" y1="19.931" y2="18.243" gradientUnits="userSpaceOnUse"><stop class="xylxrh5lr"/><stop offset="1" class="dpng9pbvi"/></linearGradient><linearGradient id="svgIDT" x1="23.672" x2="23.847" y1="19.321" y2="19.138" gradientUnits="userSpaceOnUse"><stop class="o5qj3ac-m"/><stop offset="1" class="a151cabub"/></linearGradient><linearGradient id="svgIDU" x1="26.437" x2="25.156" y1="19.368" y2="19.431" gradientUnits="userSpaceOnUse"><stop offset=".28" class="azjp5ub3a"/><stop offset="1" class="yvalde4js"/></linearGradient><linearGradient id="svgIDac" x1="29.749" x2="29.164" y1="28.181" y2="28.314" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDae" x1="26.375" x2="26.375" y1="28.54" y2="28.216" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDah" x1="22.244" x2="21.7" y1="28.306" y2="28.289" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDaj" x1="19.101" x2="19.101" y1="28.532" y2="28.208" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDan" x1="1.732" x2="1.732" y1="0" y2="4.574" gradientUnits="userSpaceOnUse"><stop class="d9dzcxb5n"/><stop offset="1" class="aqyl6fvtq"/></linearGradient><linearGradient id="svgIDar" x1="17.246" x2="17.246" y1="17.25" y2="16.769" gradientUnits="userSpaceOnUse"><stop class="fy3lw0vjf"/><stop offset="1" class="v9jntfbgm"/></linearGradient><linearGradient id="svgIDas" x1="17.256" x2="17.256" y1="17.878" y2="17.396" gradientUnits="userSpaceOnUse"><stop class="fy3lw0vjf"/><stop offset="1" class="v9jntfbgm"/></linearGradient><linearGradient id="svgIDat" x1="17.375" x2="17.375" y1="18.609" y2="18.134" gradientUnits="userSpaceOnUse"><stop class="fy3lw0vjf"/><stop offset="1" class="v9jntfbgm"/></linearGradient><linearGradient id="svgIDav" x1="16.582" x2="16.859" y1="16.628" y2="16.021" gradientUnits="userSpaceOnUse"><stop class="fy3lw0vjf"/><stop offset="1" class="v9jntfbgm"/></linearGradient><linearGradient id="svgIDay" x1="24.207" x2="19.801" y1="11.978" y2="18.009" gradientUnits="userSpaceOnUse"><stop class="aqj5eu0hn"/><stop offset="1" class="t2k92_bem"/></linearGradient><linearGradient id="svgIDaD" x1="11.623" x2="11.316" y1="7.334" y2="7.42" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDaG" x1="11.568" x2="11.405" y1="7.375" y2="7.388" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDaK" x1="11.608" x2="14.739" y1="8.226" y2="8.414" gradientUnits="userSpaceOnUse"><stop class="n2ets1bxw"/><stop offset="1" class="f6dcoc52h"/></linearGradient><linearGradient id="svgIDaV" x1="11.572" x2="11.41" y1="7.362" y2="7.374" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="svgIDaY" x1="-.007" x2=".196" y1=".054" y2=".121" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDba" x1="10.173" x2="9.687" y1="6.849" y2="3.678" gradientUnits="userSpaceOnUse"><stop offset=".421" class="esqjgpxir"/><stop offset="1" class="lj6qdgbam"/></linearGradient><linearGradient id="svgIDbb" x1="11.977" x2="10.903" y1="5.462" y2="6.368" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbe" x1="11.406" x2="12.758" y1="9.071" y2="10.9" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><linearGradient id="svgIDbm" x1="20.41" x2="20.718" y1="7.334" y2="7.42" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDbp" x1="20.466" x2="20.628" y1="7.375" y2="7.388" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDbs" x1="20.566" x2="17.436" y1="8.226" y2="8.414" gradientUnits="userSpaceOnUse"><stop class="n2ets1bxw"/><stop offset="1" class="f6dcoc52h"/></linearGradient><linearGradient id="svgIDbD" x1="20.462" x2="20.624" y1="7.362" y2="7.374" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="svgIDbG" x1="17.991" x2="18.195" y1="7.093" y2="7.16" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbI" x1="21.861" x2="22.347" y1="6.849" y2="3.678" gradientUnits="userSpaceOnUse"><stop offset=".421" class="esqjgpxir"/><stop offset="1" class="lj6qdgbam"/></linearGradient><linearGradient id="svgIDbJ" x1="20.057" x2="21.131" y1="5.462" y2="6.368" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbM" x1="20.627" x2="19.276" y1="9.071" y2="10.9" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><filter id="svgIDc" width="10.808" height="5.007" x="8.491" y="10.623" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.509804 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.411765 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23636" result="effect2_innerShadow_3987_23636"/></filter><filter id="svgIDe" width="7.106" height="3.139" x="10.204" y="11.713" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23636" stdDeviation=".2"/></filter><filter id="svgIDl" width="4.146" height="5.805" x="2.788" y="20.134" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.74902 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.576471 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23636" result="effect2_innerShadow_3987_23636"/></filter><filter id="svgIDm" width="9.426" height="8.574" x="2.717" y="9.933" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDn" width="5.878" height="6.781" x="2.144" y="13.814" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDr" width="5.139" height="3.208" x="2.051" y="25.548" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDv" width="2.686" height="1.05" x="2.698" y="25.548" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.670588 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDw" width="4.9" height="3.308" x="9.456" y="25.54" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDA" width="2.288" height="1.065" x="9.756" y="25.54" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDC" width="5.149" height="5.149" x="5.666" y="10.456" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23636" stdDeviation=".125"/></filter><filter id="svgIDG" width="1.796" height="1.427" x="13.37" y="17.873" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.552941 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDV" width="4.146" height="5.805" x="25.066" y="20.118" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.74902 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.576471 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23636" result="effect2_innerShadow_3987_23636"/></filter><filter id="svgIDW" width="9.426" height="8.574" x="19.857" y="9.918" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDX" width="5.878" height="6.781" x="23.978" y="13.798" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDab" width="5.139" height="3.208" x="24.61" y="25.532" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDaf" width="2.686" height="1.05" x="26.615" y="25.532" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.694118 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDag" width="4.9" height="3.308" x="17.344" y="25.524" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDak" width="2.288" height="1.065" x="20.156" y="25.524" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDam" width="5.149" height="5.149" x="21.185" y="10.44" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23636" stdDeviation=".125"/></filter><filter id="svgIDaw" width="5.984" height="7.891" x="7.785" y="11.556" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23636" stdDeviation=".25"/></filter><filter id="svgIDax" width="7.313" height="7.219" x="17.582" y="11.102" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23636" stdDeviation=".25"/></filter><filter id="svgIDaz" width="4.063" height="3.831" x="25.494" y="10.099" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23636" stdDeviation=".3"/></filter><filter id="svgIDaH" width="2.322" height="3.133" x="16.526" y="15.748" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23636" stdDeviation=".25"/></filter><filter id="svgIDaJ" width="4.891" height="5.723" x="10.098" y="5.029" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.396078 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDaO" width="6.019" height="6" x="8.652" y="3.294" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.682353 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDaZ" width="2.38" height="3.7" x="8.789" y="4.051" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23636" stdDeviation=".25"/></filter><filter id="svgIDbj" width="1.258" height=".393" x="12.95" y="6.456" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.231373 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDbr" width="4.891" height="5.723" x="17.186" y="5.029" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.396078 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDbw" width="6.019" height="6" x="17.363" y="3.294" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.682353 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter><filter id="svgIDbH" width="2.38" height="3.7" x="20.864" y="4.051" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23636" stdDeviation=".25"/></filter><filter id="svgIDbR" width="1.258" height=".393" x="17.826" y="6.456" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.231373 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23636"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-wrestling-medium-light" /></template>
<style>
.a0q036gjd {
  stop-color: var(--svg-color--504d4e, #504D4E);
}

.a151cabub {
  stop-color: var(--svg-color--fd5220, #FD5220);
  stop-opacity: 0;
}

.a5dbyd6tf {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
}

.ak32k0b7k {
  stop-color: var(--svg-color--695d73, #695D73);
}

.al_auo8nl {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
  stop-opacity: 0;
}

.alhmdacdj {
  stop-color: var(--svg-color--ac6684, #AC6684);
}

.ammexac5i {
  stop-color: var(--svg-color--c18b70, #C18B70);
}

.aqj5eu0hn {
  stop-color: var(--svg-color--e9b798, #E9B798);
}

.aqyl6fvtq {
  stop-color: var(--svg-color--ff7837, #FF7837);
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.azjp5ub3a {
  stop-color: var(--svg-color--ed3424, #ED3424);
}

.b5skg8e-v {
  stop-color: var(--svg-color--522470, #522470);
}

.b8hyhqehi {
  stop-color: var(--svg-color--c57872, #C57872);
  stop-opacity: 0;
}

.biii-5b1l {
  d: path("m22.156 26.47l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.261-.441.563-.438.801c.003.155.143.273.298.273h3.964a.25.25 0 0 0 .25-.25V26.47Z");
}

.biugcq6id {
  width: 1.258px;
  height: 0.293px;
  fill: var(--svg-color--8f5e36, #8F5E36);
  rx: 0.146px;
}

.bmw2gli7r {
  stop-color: var(--svg-color--be7d83, #BE7D83);
}

.bq0pg0bco {
  stop-color: var(--svg-color--ff5128, #FF5128);
  stop-opacity: 0;
}

.bs9ct9blb {
  stop-color: var(--svg-color--f7c09f, #F7C09F);
}

.bvyrbtq3r {
  d: path("m29.081 25.608l.66 2.621a.25.25 0 0 1-.242.311h-4.441c-.102 0-.196-.06-.22-.159c-.127-.503.196-.865.763-1.157a86.214 86.214 0 0 0 1.696-.9l-.376-.719a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.076Z");
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.byasxzbbd {
  d: path("m29.072 14.462l-.664-.664l-3.68 3.953l1.21 1.016s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.054h3.025a.05.05 0 0 0 .047-.034c.16-.506.565-1.792.938-3.24c.409-1.591-.287-2.517-.66-2.843Z");
}

.c-xbvquvy {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
}

.c4o6i4gil {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("m2.928 14.478l.664-.664l3.68 3.953l-1.21 1.015s.192 1.043.267 1.758a.05.05 0 0 1-.05.055H3.255a.05.05 0 0 1-.047-.035a63.198 63.198 0 0 1-.938-3.239c-.409-1.591.287-2.518.66-2.843Z");
}

.c9vx4xx-e {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("M6.826 10.688a2.696 2.696 0 0 1 3.753 3.873L7.316 17.74a2.71 2.71 0 1 1-3.77-3.892l3.28-3.159Z");
}

.ca4tncnwn {
  d: path("m11.678 8.242l-.218-1.575a.795.795 0 0 0 .218 1.575Z");
}

.ccv6f1brb {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
  stop-opacity: 0;
}

.cl2mrcsll {
  stop-color: var(--svg-color--ffdda9, #FFDDA9);
}

.cnrrv2ghu {
  stop-color: var(--svg-color--d9c388, #D9C388);
}

.cp-562b3l {
  fill-rule: evenodd;
  d: path("M19.856 3.74a.25.25 0 0 0-.162.314l.949 2.969a.25.25 0 0 0 .476-.153l-.95-2.968a.25.25 0 0 0-.313-.162Z");
}

.ct6_m01bp {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
}

.cz--1m5fh {
  stop-color: var(--svg-color--c57872, #C57872);
}

.d_2x8ab_w {
  d: path("m20.356 8.251l.218-1.574a.795.795 0 0 1-.218 1.574Z");
}

.d-weszb8y {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m9.844 26.485l-.088-.89a.05.05 0 0 1 .05-.055h1.988a.05.05 0 0 1 .05.05v.767c.559.261 1.627.807 2.074 1.117c.378.261.441.563.438.8c-.003.156-.143.274-.298.274h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.d1dcbyb2o {
  d: path("m2.928 14.478l.664-.664l3.68 3.953l-1.21 1.015s.192 1.043.267 1.758a.05.05 0 0 1-.05.055H3.255a.05.05 0 0 1-.047-.035a63.198 63.198 0 0 1-.938-3.239c-.409-1.591.287-2.518.66-2.843Z");
}

.d4rjt3rrs {
  fill: var(--svg-color--deac8c, #DEAC8C);
  d: path("M15.464 16.86a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.d5u-kgbfz {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("M25.174 10.672a2.696 2.696 0 0 0-3.752 3.873l3.261 3.178a2.71 2.71 0 1 0 3.77-3.891l-3.28-3.16Z");
}

.d9dzcxb5n {
  stop-color: var(--svg-color--ff772a, #FF772A);
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.dm4voe-la {
  d: path("M0 0h2.371v3.351H0z");
}

.dpng9pbvi {
  stop-color: var(--svg-color--fe5823, #FE5823);
}

.dr2k0bhek {
  stop-color: var(--svg-color--c79b78, #C79B78);
}

.e31k1-bnl {
  stop-color: var(--svg-color--ebb898, #EBB898);
}

.efo8wovhu {
  stop-color: var(--svg-color--ffeeb8, #FFEEB8);
  stop-opacity: 0;
}

.ek67jac7r {
  d: path("M14.543 4.078a1.121 1.121 0 0 0-1.076-.632c-.94.051-.878.67-1.729.495c-.898-.185-1.531-.426-1.916-.252l-.007.004c-.38.172-1.163.528-1.163 2.132c0 1.479.527 2.26.782 2.538l-.05.018c-.254.092-.358.361-.267.615c.078.216.352.34.697.286c.394-.062.683-.116.91-.161a.272.272 0 0 0 .218-.267V7.637c0-.513.361-.819.52-.91c.018-.53.18-.773.445-.902c.439-.212.575-.107 1.624-.17c1.055-.065 1.337-.91 1.012-1.577Z");
}

.em3zy1brs {
  d: path("M13.493 7.52v-.005c0-.35.15-.634.335-.634c.185 0 .335.284.335.634v.004h-.67Z");
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.eq14s50yt {
  d: path("M14.709 6.651c-.043-.876-.326-1.299-.46-1.422h-4.082l-.069 3.46c.948 2.32 3.841 2.42 4.273 1.58c.432-.839.386-2.603.338-3.618Z");
}

.esqjgpxir {
  stop-color: var(--svg-color--fff9bd, #FFF9BD);
}

.evxwq240k {
  fill-rule: evenodd;
  d: path("M27.133 12.46a.1.1 0 0 0-.09-.14l-3.873-.058l.035-2.34l4.25.06c1.653.024 2.653 1.726 1.919 3.234l-1.186 2.545l-2.062-1.02l1.007-2.281Z");
}

.exc6wlshr {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.155 7.52h-1.081c0-.429.242-.776.54-.776c.299 0 .54.347.54.775Z");
}

.f6dcoc52h {
  stop-color: var(--svg-color--cb947a, #CB947A);
}

.f6mg5tnmy {
  rx: 0.07px;
  ry: 0.096px;
}

.fcsxqnbqr {
  d: path("m16.074 11.77l.536-.515c.123-.11.461-.332.824-.332h.988a.476.476 0 1 1 0 .953h-.866a.224.224 0 0 0-.202.129l-.033.07a.344.344 0 0 0-.002.287l.557-.039a.516.516 0 0 1 .07 1.03l-.669.046c-.739 1.026-1.884 2.055-3.902 2.229c-2.386.056-3.712-1.183-4.258-1.692l-.108-.1l-.103-.091a1.15 1.15 0 1 1 1.47-1.769c.023.019.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.046.11.098.17.153c.497.455 1.236 1.132 2.533 1.132c.391 0 .884-.013 1.408-.336c.51-.314.937-.7 1.167-.95a.662.662 0 0 1 .124-.108Z");
}

.fd4bh7bhc {
  stop-color: var(--svg-color--f09c86, #F09C86);
  stop-opacity: 0;
}

.fk4zrip8m {
  stop-color: var(--svg-color--483159, #483159);
}

.ft5dv1b6b {
  fill: none;
}

.fwjng4bpx {
  width: 0.764px;
  height: 1.4px;
  x: 17.093px;
  y: 15.863px;
  fill: var(--svg-color--dea989, #DEA989);
  rx: 0.382px;
}

.fy3lw0vjf {
  stop-color: var(--svg-color--ba7682, #BA7682);
}

.gc63m4sma {
  d: path("M21.353 10.752a2.697 2.697 0 0 1 3.821-.08l3.234 3.126l.045.034c.067.064.13.13.188.2l.43.43c.373.326 1.069 1.252.66 2.844a62.491 62.491 0 0 1-.938 3.239a.047.047 0 0 1-.02.026a.052.052 0 0 1-.027.008h-3.025a.05.05 0 0 1-.05-.054c.075-.715.268-1.758.268-1.758l-.876-.735a2.72 2.72 0 0 1-.38-.309l-3.261-3.177a2.696 2.696 0 0 1-.069-3.794Z");
}

.gg2ehgbth {
  width: 3.464px;
  height: 4.574px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.gh-ifubji {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.188px;
  rx: 1.732px;
}

.gjr9r-itc {
  stop-color: var(--svg-color--e2b38e, #E2B38E);
}

.gkj8dyg7i {
  fill: var(--svg-color--e5a997, #E5A997);
  d: path("m28.11 22.235l.57-1.726l-2.876-.39c-.013.093-.071.51-.203 1.429c-.13.919.125 1.664.375 2.203l1.22 2.172h1.866c-.245-.77-.844-2.77-.93-3.031c-.085-.262-.085-.48-.023-.657Z");
}

.gmw4iybjp {
  fill: var(--svg-color--deac8c, #DEAC8C);
  d: path("M15.503 17.487c0-.215.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
}

.gr47531og {
  cx: 17.687px;
  cy: 17.315px;
  fill: var(--svg-color--deaa89, #DEAA89);
  rx: 0.661px;
  ry: 1.066px;
}

.gs4mjcb0j {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("m29.072 14.462l-.664-.664l-3.68 3.953l1.21 1.016s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.054h3.025a.05.05 0 0 0 .047-.034c.16-.506.565-1.792.938-3.24c.409-1.591-.287-2.517-.66-2.843Z");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gy1xmobvy {
  stop-color: var(--svg-color--c18066, #C18066);
  stop-opacity: 0;
}

.gybwkccsq {
  d: path("m20.356 8.242l.218-1.575a.795.795 0 0 1-.218 1.575Z");
}

.h3745i65f {
  d: path("M17.49 4.078c.26-.533.773-.649 1.077-.632c.94.051.878.67 1.728.495c.899-.185 1.532-.426 1.916-.252l.008.004c.379.172 1.163.528 1.163 2.132c0 1.479-.527 2.26-.782 2.538l.05.018c.253.092.358.361.266.615c-.078.216-.351.34-.696.286a22.567 22.567 0 0 1-.91-.161a.272.272 0 0 1-.218-.267V7.637a1.08 1.08 0 0 0-.521-.91c-.017-.53-.18-.773-.445-.902c-.438-.212-.575-.107-1.623-.17c-1.055-.065-1.337-.91-1.013-1.577Z");
}

.hbnc11boo {
  d: path("M18.541 7.52v-.005c0-.35-.15-.634-.335-.634c-.186 0-.336.284-.336.634v.004h.671Z");
}

.hef8pn1do {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M24.02 11.978c-.26 1.312-1.738 4.243-5.563 5.468");
}

.hh9ibwbje {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
  stop-opacity: 0;
}

.hi6yszbkt {
  stop-color: var(--svg-color--ff5c2b, #FF5C2B);
  stop-opacity: 0;
}

.hms2sfnpk {
  stop-color: var(--svg-color--ffdda9, #FFDDA9);
  stop-opacity: 0;
}

.hpo9rcg8j {
  cx: 10.996px;
  cy: 7.806px;
  r: 1.281px;
}

.hy8b1ubxg {
  stop-color: var(--svg-color--cc8778, #CC8778);
}

.i_emxkhmq {
  stop-color: var(--svg-color--442f88, #442F88);
}

.icb-xabyb {
  stop-color: var(--svg-color--c98181, #C98181);
  stop-opacity: 0;
}

.iv6ebfcln {
  fill-rule: evenodd;
  d: path("M13.609 18.95a.4.4 0 0 1 .547-.141l1.215.715a.4.4 0 1 1-.405.69l-1.215-.716a.4.4 0 0 1-.142-.547Z");
}

.jjhblb54u {
  stop-color: var(--svg-color--ff5128, #FF5128);
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jth06oa-o {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.88 7.52h1.08c0-.429-.242-.776-.54-.776c-.299 0-.54.347-.54.775Z");
}

.jv-vvdc2h {
  stop-color: var(--svg-color--433352, #433352);
  stop-opacity: 0;
}

.k8s01tfdv {
  stop-color: var(--svg-color--5e5663, #5E5663);
  stop-opacity: 0;
}

.kd8ah_bdi {
  d: path("M16.086 15.572a.384.384 0 1 0 0 .769h.518a.065.065 0 0 1 0 .129h1.158v-.13h.254l-.31-.308a1.568 1.568 0 0 0-1.108-.46h-.512Z");
}

.kgukkhbth {
  stop-color: var(--svg-color--5e5663, #5E5663);
}

.kik7_ob9t {
  stop-color: var(--svg-color--c18b70, #C18B70);
  stop-opacity: 0;
}

.koojhabhx {
  d: path("M17.466 6.651c.042-.876.326-1.299.46-1.422h4.082l.068 3.46c-.947 2.32-3.84 2.42-4.272 1.58c-.432-.839-.387-2.603-.338-3.618Z");
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.kq3eo2bwh {
  d: path("m11.678 8.251l-.218-1.574a.795.795 0 0 0 .218 1.574Z");
}

.ksl77bchk {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
  stop-opacity: 0;
}

.kx97vubln {
  stop-color: var(--svg-color--e2b09a, #E2B09A);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l2ghe_s4e {
  fill: var(--svg-color--e8b48e, #E8B48E);
  fill-rule: evenodd;
  d: path("M13.393 19.257a.45.45 0 0 1 .624-.121l.973.656a.45.45 0 0 1-.503.746l-.973-.656a.45.45 0 0 1-.121-.625Z");
}

.l3r47ffcx {
  stop-color: var(--svg-color--d1907d, #D1907D);
}

.l4v-g_vax {
  d: path("M26.406 10.7a.3.3 0 1 0-.024.599l.024-.6Zm1.29.353l.013-.3l-.012.3Zm.899 1.342l.282.103l-.282-.103Zm-.514.532a.3.3 0 0 0 .563.207l-.563-.207Zm-1.7-1.628l1.303.053l.025-.6l-1.303-.053l-.024.6Zm1.932.993l-.232.635l.563.207l.233-.636l-.564-.206Zm-.629-.94a.7.7 0 0 1 .63.94l.563.206a1.3 1.3 0 0 0-1.168-1.745l-.025.6Z");
}

.l6veklvwf {
  stop-color: var(--svg-color--9e94a2, #9E94A2);
}

.li5uyl08u {
  stop-color: var(--svg-color--bc7a83, #BC7A83);
  stop-opacity: 0;
}

.lj6qdgbam {
  stop-color: var(--svg-color--fff9bd, #FFF9BD);
  stop-opacity: 0;
}

.ljdquke8v {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M13.305 9.065c0-.069.056-.124.124-.124h.607a.124.124 0 0 1 0 .248h-.607a.124.124 0 0 1-.124-.124Z");
}

.lshqpgbqp {
  d: path("m22.828 22.08l2.039-1.805l-2.156-2.188a68.991 68.991 0 0 1-1.903 2.277c-.67.77-.758 1.77-.738 2.262l.102 2.898h2.023c.068-.734.211-2.307.242-2.726a.954.954 0 0 1 .39-.719Z");
}

.m1j2mbbtp {
  stop-color: var(--svg-color--bc7a83, #BC7A83);
}

.m4_ilibnz {
  stop-color: var(--svg-color--e4af8c, #E4AF8C);
  stop-opacity: 0;
}

.m4vchmg3s {
  stroke: var(--svg-color--f4bea0, #F4BEA0);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.66 12.43c.073 1.376 2.032 4.876 4.235 6.141");
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
  stop-opacity: 0;
}

.mqedtfb5e {
  stop-color: var(--svg-color--423948, #423948);
}

.mqj76hbqm {
  fill: var(--svg-color--a56061, #A56061);
  d: path("m16.47 11.598l-.59.57l.297 1.115l1.425-.506l-.08-.116a.316.316 0 0 1-.023-.311l.03-.064a.205.205 0 0 1 .185-.118h.42a.437.437 0 1 0 0-.874h-.907c-.333 0-.643.203-.756.304Z");
}

.ms4f1oj7g {
  r: 1.281px;
}

.mvr01ib0c {
  stop-color: var(--svg-color--dc877f, #DC877F);
  stop-opacity: 0;
}

.n04al3b3c {
  fill: var(--svg-color--dda691, #DDA691);
  fill-rule: evenodd;
  d: path("M13.025 19.773a.4.4 0 0 1 .56-.087l.746.547a.4.4 0 1 1-.473.645l-.746-.546a.4.4 0 0 1-.087-.56Z");
}

.n2ets1bxw {
  stop-color: var(--svg-color--d49d8d, #D49D8D);
}

.n4fw05ymv {
  d: path("M14.954 7.705c-.171-.16-.26-.4-.283-.5h-.196v1.23c.235.15.571.127.67-.097c.086-.193.022-.432-.191-.633Z");
}

.n7l1hg2af {
  stop-color: var(--svg-color--f37a76, #F37A76);
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

.nkw7_sb2b {
  stop-color: var(--svg-color--c27f74, #C27F74);
}

.nx4bqnbvp {
  stop-color: var(--svg-color--d6a183, #D6A183);
}

.o3u3_rbmt {
  fill-rule: evenodd;
  d: path("M23.727 11.745c.627.168 1 .811.833 1.438c-.25.938-.826 1.86-1.893 3.009c-1.075 1.157-2.67 2.248-4.615 2.413a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.833Z");
}

.o410gcc4i {
  stop-color: var(--svg-color--ecb596, #ECB596);
  stop-opacity: 0;
}

.o5qj3ac-m {
  stop-color: var(--svg-color--e73d40, #E73D40);
}

.ocru65npv {
  stop-color: var(--svg-color--3f3646, #3F3646);
}

.ol8ztc22n {
  d: path("M10.61 5.588c-.17.695-.269 1.361-.302 1.663a3.17 3.17 0 0 1-1.016-2.047c-.054-.545.63-.828 1.093-.536c.335.21.32.536.226.92Z");
}

.olnp00bal {
  stroke: var(--svg-color--ebac91, #EBAC91);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.804 13.626c.38.25 1.469.722 2.781.609c1.64-.14 2.656-1.047 3.125-1.922");
}

.on8sxx3yx {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
  stop-opacity: 0;
}

.oo2c8jblg {
  d: path("m24.855 20.43l1.082-1.007l1.149-1.023l-3.133-1.907a78.474 78.474 0 0 1-1.4 1.66a.05.05 0 0 0 .003.068l2.23 2.207a.05.05 0 0 0 .07.001Z");
}

.otf1z2b9l {
  stop-color: var(--svg-color--ffedae, #FFEDAE);
}

.oybn7vbqt {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
}

.p4686vbiy {
  stop-color: var(--svg-color--fb5d03, #FB5D03);
}

.p5wg8876f {
  stop-color: var(--svg-color--a6605e, #A6605E);
}

.p9w8m_bzp {
  fill-rule: evenodd;
  d: path("M12.178 3.74a.25.25 0 0 1 .162.314l-.95 2.969a.25.25 0 0 1-.476-.153l.95-2.968a.25.25 0 0 1 .314-.162Z");
}

.pafpa8b3r {
  stop-color: var(--svg-color--e3a984, #E3A984);
}

.pb2gbr7kw {
  fill: var(--svg-color--d7a180, #D7A180);
  fill-rule: evenodd;
  d: path("M23.727 11.745c.627.168 1 .811.833 1.438c-.25.938-.826 1.86-1.893 3.009c-1.075 1.157-2.67 2.248-4.615 2.413a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.833Z");
}

.pekz8jb1t {
  d: path("M15.846 18.224c0-.212.173-.385.386-.385h1.385l.308.77H16.23a.385.385 0 0 1-.385-.385Z");
}

.pfu46_y1s {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
}

.ps7q97bxk {
  d: path("m7.145 20.445l-1.082-1.006l-1.149-1.024l3.133-1.906a77.83 77.83 0 0 0 1.4 1.66a.05.05 0 0 1-.003.068l-2.23 2.207a.05.05 0 0 1-.07.001Z");
}

.pxj138bcc {
  width: 3.464px;
  height: 4.574px;
  rx: 1.732px;
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.q1txceb2f {
  stop-color: var(--svg-color--d99688, #D99688);
}

.q2gydu3zd {
  stop-color: var(--svg-color--3e3a3f, #3E3A3F);
  stop-opacity: 0;
}

.qdq-erb7u {
  stop-color: var(--svg-color--e5a88d, #E5A88D);
}

.qfkd0ob_i {
  d: path("M11.844 26.346v-.756a.05.05 0 0 0-.05-.05H9.805a.05.05 0 0 0-.05.055l.089.89v.02l2-.16Z");
}

.qgurk7bxc {
  stop-color: var(--svg-color--d9c388, #D9C388);
  stop-opacity: 0;
}

.qihskpbeg {
  stop-color: var(--svg-color--524e8d, #524E8D);
  stop-opacity: 0;
}

.qpafcfb4e {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.188px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.qpejwlb8n {
  stop-color: var(--svg-color--fb5d03, #FB5D03);
  stop-opacity: 0;
}

.qwnulubfe {
  stop-color: var(--svg-color--e2b09a, #E2B09A);
  stop-opacity: 0;
}

.qy3mcrgdk {
  stop-color: var(--svg-color--c18066, #C18066);
}

.r-95cxbic {
  stop-color: var(--svg-color--ffeeb8, #FFEEB8);
}

.r1qdbacdf {
  d: path("M10.647 10.767a2.697 2.697 0 0 0-3.821-.079l-3.234 3.126l-.045.034c-.067.064-.13.13-.188.2l-.43.43c-.373.325-1.069 1.252-.66 2.844c.372 1.447.778 2.733.938 3.238a.048.048 0 0 0 .047.035h3.025a.05.05 0 0 0 .05-.055c-.074-.714-.268-1.758-.268-1.758l.876-.734c.133-.09.26-.193.38-.309l3.261-3.178a2.696 2.696 0 0 0 .069-3.794Z");
}

.r3qtxmtcb {
  stop-color: var(--svg-color--be7d83, #BE7D83);
  stop-opacity: 0;
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.rdgulqvms {
  stop-color: var(--svg-color--e1a38b, #E1A38B);
  stop-opacity: 0;
}

.rknzqr02l {
  stop-color: var(--svg-color--695d73, #695D73);
  stop-opacity: 0;
}

.rnt_ycbgu {
  d: path("m2.919 25.623l-.66 2.622a.25.25 0 0 0 .242.31h4.441c.102 0 .196-.06.22-.158c.127-.503-.196-.866-.763-1.157a86.812 86.812 0 0 1-1.696-.9l.376-.719a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076Z");
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.rpqz5ojcj {
  d: path("M17.19 7.705c.17-.16.259-.4.282-.5h.196v1.23c-.235.15-.57.127-.67-.097c-.086-.193-.022-.432.192-.633Z");
}

.rt_dddp6w {
  fill-rule: evenodd;
  d: path("M8.23 11.485a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.161 4.242 5.911c.539.336.765 1.006.43 1.545a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

.rwnj23csn {
  fill: var(--svg-color--deac8c, #DEAC8C);
  d: path("M16.086 15.572a.384.384 0 1 0 0 .769h.518a.065.065 0 0 1 0 .129h1.158v-.13h.254l-.31-.308a1.568 1.568 0 0 0-1.108-.46h-.512Z");
}

.s4vkc-bcm {
  stop-color: var(--svg-color--e4af8c, #E4AF8C);
}

.s9njfgb_y {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m2.919 25.623l-.66 2.622a.25.25 0 0 0 .242.31h4.441c.102 0 .196-.06.22-.158c.127-.503-.196-.866-.763-1.157a86.812 86.812 0 0 1-1.696-.9l.376-.719a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076Z");
}

.se2cvmb9b {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m22.156 26.47l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.261-.441.563-.438.801c.003.155.143.273.298.273h3.964a.25.25 0 0 0 .25-.25V26.47Z");
}

.sgqr937ow {
  stop-color: var(--svg-color--c98181, #C98181);
}

.shic-ydjf {
  stop-color: var(--svg-color--2e2d2f, #2E2D2F);
}

.sln7mgqoj {
  d: path("M9.172 22.095L7.133 20.29l2.156-2.187a69.181 69.181 0 0 0 1.903 2.277c.67.77.758 1.77.738 2.262l-.102 2.898H9.805a295.62 295.62 0 0 1-.242-2.726a.954.954 0 0 0-.39-.72Z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t2k92_bem {
  stop-color: var(--svg-color--e9b798, #E9B798);
  stop-opacity: 0;
}

.t4m41vbgx {
  stop-color: var(--svg-color--e6473c, #E6473C);
}

.t5tj028fa {
  stop-color: var(--svg-color--cc8f8d, #CC8F8D);
  stop-opacity: 0;
}

.te4zz7dbn {
  stop-color: var(--svg-color--ffe2ad, #FFE2AD);
}

.tf3omaceq {
  d: path("m11.674 8.256l-.218-1.576a.796.796 0 0 0 .218 1.576Z");
}

.tmmfhpbga {
  cx: 18.069px;
  cy: 7.135px;
  rx: 0.07px;
  ry: 0.096px;
}

.tozx5obpz {
  fill: var(--svg-color--dda07b, #DDA07B);
  d: path("m16.074 11.77l.536-.515c.123-.11.461-.332.824-.332h.988a.476.476 0 1 1 0 .953h-.866a.224.224 0 0 0-.202.129l-.033.07a.344.344 0 0 0-.002.287l.557-.039a.516.516 0 0 1 .07 1.03l-.669.046c-.739 1.026-1.884 2.055-3.902 2.229c-2.386.056-3.712-1.183-4.258-1.692l-.108-.1l-.103-.091a1.15 1.15 0 1 1 1.47-1.769c.023.019.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.046.11.098.17.153c.497.455 1.236 1.132 2.533 1.132c.391 0 .884-.013 1.408-.336c.51-.314.937-.7 1.167-.95a.662.662 0 0 1 .124-.108Z");
}

.tr9cr_bup {
  stop-color: var(--svg-color--e09e8e, #E09E8E);
}

.tu9tajbkl {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m29.081 25.608l.66 2.621a.25.25 0 0 1-.242.311h-4.441c-.102 0-.196-.06-.22-.159c-.127-.503.196-.865.763-1.157a86.214 86.214 0 0 0 1.696-.9l-.376-.719a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.076Z");
}

.txvpahc1h {
  fill-rule: evenodd;
  d: path("M13.373 18.42a.4.4 0 0 1 .55-.136c.404.245.859.47 1.375.648a.4.4 0 1 1-.26.756a7.868 7.868 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549Z");
}

.u0wlypb1d {
  fill: var(--svg-color--e8b48e, #E8B48E);
  fill-rule: evenodd;
  d: path("M13.373 18.42a.4.4 0 0 1 .55-.136c.404.245.859.47 1.375.648a.4.4 0 1 1-.26.756a7.868 7.868 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549Z");
}

.u2n90vbun {
  stop-color: var(--svg-color--ad6361, #AD6361);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uj_nqubgh {
  stop-color: var(--svg-color--ecb297, #ECB297);
}

.uj1cqbfji {
  fill: var(--svg-color--9d91a7, #9D91A7);
  d: path("m27.297 26.323l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.076l.22.874l-2.004-.159Z");
}

.uq4h3zxiv {
  stop-color: var(--svg-color--dda595, #DDA595);
}

.v7wb7cclw {
  fill-rule: evenodd;
  d: path("M11.102 8.496a.25.25 0 0 1 .325.138c.1.247.285.645.511 1.038c.23.399.488.766.732.975a.25.25 0 1 1-.324.38c-.312-.266-.606-.697-.841-1.106a9.538 9.538 0 0 1-.541-1.1a.25.25 0 0 1 .138-.325Z");
}

.v9jntfbgm {
  stop-color: var(--svg-color--ba7682, #BA7682);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vvdzqypxx {
  stop-color: var(--svg-color--c79b78, #C79B78);
  stop-opacity: 0;
}

.w-okwbk4h {
  d: path("M15.464 16.86a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.w16l4dbiv {
  d: path("M18.328 7.52a.7.7 0 0 0 .004-.08c0-.203-.086-.367-.192-.367c-.106 0-.192.164-.192.367c0 .027.001.054.004.08h.376Z");
}

.w2eqh57fa {
  fill-rule: evenodd;
  d: path("M20.932 8.496a.25.25 0 0 0-.326.138a9.05 9.05 0 0 1-.51 1.038c-.23.399-.489.766-.733.975a.25.25 0 1 0 .325.38c.312-.266.605-.697.84-1.106c.24-.414.434-.833.542-1.1a.25.25 0 0 0-.138-.325Z");
}

.w4vm-cb_s {
  d: path("M21.423 5.588c.17.695.27 1.361.303 1.663a3.169 3.169 0 0 0 1.015-2.047c.055-.545-.629-.828-1.093-.536c-.334.21-.32.536-.225.92Z");
}

.wg-u6yb-o {
  stop-color: var(--svg-color--bc7a7b, #BC7A7B);
  stop-opacity: 0;
}

.wi3vdjbhe {
  fill: var(--svg-color--e8b396, #E8B396);
  fill-rule: evenodd;
  d: path("M15.127 18.25a.4.4 0 0 1-.188.534l-.996.477a.4.4 0 0 1-.346-.722l.996-.477a.4.4 0 0 1 .534.188Z");
}

.x0vfftb6r {
  d: path("M19.316 9.21h2.371v3.351h-2.371z");
}

.xagwtmr2g {
  fill: var(--svg-color--baa4c5, #BAA4C5);
  d: path("m4.703 26.34l.376-.719a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076l-.22.874l2.004-.159Z");
}

.xk6m9ab-u {
  fill: var(--svg-color--deac8c, #DEAC8C);
  d: path("M15.846 18.224c0-.212.173-.385.386-.385h1.385l.308.77H16.23a.385.385 0 0 1-.385-.385Z");
}

.xkrkjbk5z {
  stop-color: var(--svg-color--dc877f, #DC877F);
}

.xqb1sxmbd {
  fill: var(--svg-color--e8b48e, #E8B48E);
  fill-rule: evenodd;
  d: path("M13.609 18.95a.4.4 0 0 1 .547-.141l1.215.715a.4.4 0 1 1-.405.69l-1.215-.716a.4.4 0 0 1-.142-.547Z");
}

.xylxrh5lr {
  stop-color: var(--svg-color--f03814, #F03814);
}

.y-whk56hl {
  fill-rule: evenodd;
  d: path("M13.393 19.257a.45.45 0 0 1 .624-.121l.973.656a.45.45 0 0 1-.503.746l-.973-.656a.45.45 0 0 1-.121-.625Z");
}

.y4pe4ezsu {
  stop-color: var(--svg-color--271e2e, #271E2E);
}

.yfv3nqb2s {
  stop-color: var(--svg-color--e4a88b, #E4A88B);
  stop-opacity: 0;
}

.yic7b8bke {
  stop-color: var(--svg-color--bc7a7b, #BC7A7B);
}

.yl7ausbxx {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M18.729 9.065a.124.124 0 0 0-.124-.124h-.608a.124.124 0 0 0 0 .248h.608a.124.124 0 0 0 .124-.124Z");
}

.yrfae15se {
  d: path("M15.503 17.487c0-.215.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.yvalde4js {
  stop-color: var(--svg-color--ed3424, #ED3424);
  stop-opacity: 0;
}

.yyaflybwa {
  fill-rule: evenodd;
  d: path("M13.025 19.773a.4.4 0 0 1 .56-.087l.746.547a.4.4 0 1 1-.473.645l-.746-.546a.4.4 0 0 1-.087-.56Z");
}

.yyc9yuyiy {
  stop-color: var(--svg-color--ecb596, #ECB596);
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.z3_s1-bxc {
  width: 1.258px;
  height: 0.293px;
  x: 12.95px;
  y: 6.556px;
  fill: var(--svg-color--8f5e36, #8F5E36);
  rx: 0.146px;
}

.zcjltpb4i {
  d: path("m9.844 26.485l-.088-.89a.05.05 0 0 1 .05-.055h1.988a.05.05 0 0 1 .05.05v.767c.559.261 1.627.807 2.074 1.117c.378.261.441.563.438.8c-.003.156-.143.274-.298.274h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.zjmmjyoar {
  stop-color: var(--svg-color--554f5c, #554F5C);
}

.zll2ktbmo {
  d: path("M13.706 7.52a.7.7 0 0 1-.004-.08c0-.203.086-.367.192-.367c.106 0 .192.164.192.367a.699.699 0 0 1-.004.08h-.376Z");
}

.zn3ibrd7r {
  d: path("m20.36 8.256l.218-1.576a.796.796 0 0 1-.218 1.576Z");
}

.znbv98bgs {
  d: path("M20.156 26.33v-.755a.05.05 0 0 1 .05-.05h1.989a.05.05 0 0 1 .05.055l-.089.89v.02l-2-.16Z");
}

.zp759pfge {
  fill: var(--svg-color--e7b28b, #E7B28B);
  fill-rule: evenodd;
  d: path("M8.23 11.485a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.161 4.242 5.911c.539.336.765 1.006.43 1.545a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

.zt8u8ubth {
  fill: var(--svg-color--e5a997, #E5A997);
  d: path("m3.89 22.251l-.57-1.727l2.876-.39c.013.094.071.51.203 1.43c.13.918-.125 1.664-.375 2.203l-1.22 2.172H2.939c.245-.771.843-2.77.93-3.032c.085-.261.085-.48.023-.656Z");
}

</style>
