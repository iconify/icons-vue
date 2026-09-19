<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#svgIDa)" transform="rotate(-23.31 19.316 9.209)" class="h766w6bjn"/><path fill="url(#svgIDb)" transform="scale(-1 1) rotate(-23.31 15.98 35.35)" class="dm4voe-la"/><path class="gpmekbc0a"/><g filter="url(#svgIDc)"><path class="ozwe4ruxe"/><path fill="url(#svgIDd)" class="d6q_8achq"/></g><g filter="url(#svgIDe)"><path class="cgmdsqbnw"/></g><path fill="url(#svgIDf)" class="cwns_hb1c"/><path fill="url(#svgIDg)" class="cwns_hb1c"/><path fill="url(#svgIDh)" class="cwns_hb1c"/><path fill="url(#svgIDi)" class="u9l1qpq9e"/><path fill="url(#svgIDj)" class="u9l1qpq9e"/><path fill="url(#svgIDk)" class="u9l1qpq9e"/><g filter="url(#svgIDl)"><path class="ufkgclbst"/></g><g filter="url(#svgIDm)"><path class="sdv86gbgg"/></g><g filter="url(#svgIDn)"><path class="ob3w450tf"/><path fill="url(#svgIDo)" class="rgr1pfeuu"/></g><path fill="url(#svgIDp)" class="b8z2shxnu"/><path fill="url(#svgIDq)" class="b8z2shxnu"/><g filter="url(#svgIDr)"><path class="rp2piebdz"/><path fill="url(#svgIDs)" class="pa2jxdc2t"/><path fill="url(#svgIDt)" class="pa2jxdc2t"/><path fill="url(#svgIDu)" class="pa2jxdc2t"/></g><g filter="url(#svgIDv)"><path class="dsekwy_sd"/></g><g filter="url(#svgIDw)"><path class="xabspufox"/><path fill="url(#svgIDx)" class="fue48-jmh"/><path fill="url(#svgIDy)" class="fue48-jmh"/><path fill="url(#svgIDz)" class="fue48-jmh"/></g><g filter="url(#svgIDA)"><path fill="url(#svgIDB)" class="lb6__zbop"/></g><g filter="url(#svgIDC)"><rect stroke="url(#svgIDD)" transform="rotate(45 8.633 10.187)" class="ogf6ef1iq"/></g><rect fill="url(#svgIDE)" transform="rotate(45 8.633 10.187)" class="zmlmhacwe"/><rect fill="url(#svgIDF)" transform="rotate(45 8.633 10.187)" class="zmlmhacwe"/><g filter="url(#svgIDG)"><path clip-rule="evenodd" class="bp63byb2o"/></g><path clip-rule="evenodd" class="obnmtelja"/><path fill="url(#svgIDH)" clip-rule="evenodd" class="m0c3_oaed"/><path clip-rule="evenodd" class="e9d9bj2lv"/><path fill="url(#svgIDI)" clip-rule="evenodd" class="ygv0piz0u"/><path clip-rule="evenodd" class="x9qbdbcpv"/><path fill="url(#svgIDJ)" clip-rule="evenodd" class="ymlznzbiw"/><path clip-rule="evenodd" class="bz0tvm-_e"/><path fill="url(#svgIDK)" clip-rule="evenodd" class="p6_6x2bgc"/><path clip-rule="evenodd" class="gvzw7_bgu"/><path fill="url(#svgIDL)" clip-rule="evenodd" class="jbkodbetk"/><path fill="url(#svgIDM)" clip-rule="evenodd" class="c9lu1s8rn"/><path fill="url(#svgIDN)" clip-rule="evenodd" class="c9lu1s8rn"/><path fill="url(#svgIDO)" clip-rule="evenodd" class="c9lu1s8rn"/><rect transform="rotate(-28.166 17.093 15.861)" class="w9jnu_bcu"/><path fill="url(#svgIDP)" class="lqb9_uf8b"/><path fill="url(#svgIDQ)" class="lqb9_uf8b"/><path fill="url(#svgIDR)" class="lqb9_uf8b"/><path fill="url(#svgIDS)" class="baf9mgbew"/><path fill="url(#svgIDT)" class="baf9mgbew"/><path fill="url(#svgIDU)" class="baf9mgbew"/><g filter="url(#svgIDV)"><path class="letyccc1q"/></g><g filter="url(#svgIDW)"><path class="wu90fi6zm"/></g><g filter="url(#svgIDX)"><path class="j3y9mvb-x"/><path fill="url(#svgIDY)" class="t3b1fti3m"/></g><path fill="url(#svgIDZ)" class="hgl82vasr"/><path fill="url(#svgIDaa)" class="hgl82vasr"/><g filter="url(#svgIDab)"><path class="zmz0e-b5i"/><path fill="url(#svgIDac)" class="r_8nwacar"/><path fill="url(#svgIDad)" class="r_8nwacar"/><path fill="url(#svgIDae)" class="r_8nwacar"/></g><g filter="url(#svgIDaf)"><path class="runtb-bmp"/></g><g filter="url(#svgIDag)"><path class="o4dph5bxr"/><path fill="url(#svgIDah)" class="sj-jxnbay"/><path fill="url(#svgIDai)" class="sj-jxnbay"/><path fill="url(#svgIDaj)" class="sj-jxnbay"/></g><g filter="url(#svgIDak)"><path fill="url(#svgIDal)" class="dfbdq2s9s"/></g><g filter="url(#svgIDam)"><rect stroke="url(#svgIDan)" transform="scale(-1 1) rotate(45 -23.961 -23.121)" class="gg2ehgbth"/></g><rect fill="url(#svgIDao)" transform="scale(-1 1) rotate(45 -23.961 -23.121)" class="pxj138bcc"/><rect fill="url(#svgIDap)" transform="scale(-1 1) rotate(45 -23.961 -23.121)" class="pxj138bcc"/><path clip-rule="evenodd" class="j175ldb2t"/><path fill="url(#svgIDaq)" clip-rule="evenodd" class="nsxb74-gl"/><path class="vwme3mblx"/><path fill="url(#svgIDar)" class="tahk4luhp"/><path class="rnxu2urvv"/><path fill="url(#svgIDas)" class="c1zeyrb4v"/><path class="n45ezsbxn"/><path fill="url(#svgIDat)" class="kjf54ac2g"/><path fill="url(#svgIDau)" class="kjf54ac2g"/><path class="lxrxf67aa"/><path fill="url(#svgIDav)" class="scn4k-3ks"/><g filter="url(#svgIDaw)"><path class="pkkx7l7dx"/></g><g filter="url(#svgIDax)"><path stroke="url(#svgIDay)" class="y6flt6btr"/></g><g filter="url(#svgIDaz)"><path fill="url(#svgIDaA)" class="b9zp3cb7v"/></g><path fill="url(#svgIDaB)" class="jkpjuyb8g"/><path fill="url(#svgIDaC)" class="jkpjuyb8g"/><path fill="url(#svgIDaD)" class="jkpjuyb8g"/><path fill="url(#svgIDaE)" class="c9evk8b4g"/><path fill="url(#svgIDaF)" class="c9evk8b4g"/><path fill="url(#svgIDaG)" class="c9evk8b4g"/><g filter="url(#svgIDaH)"><ellipse class="ngn1gjbbd"/></g><path fill="url(#svgIDaI)" class="nh6ki6yxn"/><path fill="url(#svgIDaJ)" class="nh6ki6yxn"/><path fill="url(#svgIDaK)" class="nh6ki6yxn"/><path fill="url(#svgIDaL)" class="h93043b3q"/><g filter="url(#svgIDaM)"><path fill="url(#svgIDaN)" class="qyzqptbtz"/><path fill="url(#svgIDaO)" class="qyzqptbtz"/><path fill="url(#svgIDaP)" class="qyzqptbtz"/><path fill="url(#svgIDaQ)" class="qyzqptbtz"/></g><g filter="url(#svgIDaR)"><path fill="url(#svgIDaS)" class="upqgllbnx"/><path fill="url(#svgIDaT)" class="upqgllbnx"/><path fill="url(#svgIDaU)" class="upqgllbnx"/><path fill="url(#svgIDaV)" class="upqgllbnx"/></g><path fill="url(#svgIDaW)" class="ptzuc934d"/><path fill="url(#svgIDaX)" class="ptzuc934d"/><path fill="url(#svgIDaY)" class="ptzuc934d"/><path class="i7ileabcr"/><path fill="url(#svgIDaZ)" class="pf3hjw22a"/><path fill="url(#svgIDba)" class="l31f_ibry"/><ellipse fill="url(#svgIDbb)" transform="scale(-1 1) rotate(24.61 -23.343 -28.476)" class="f6mg5tnmy"/><g filter="url(#svgIDbc)"><path fill="url(#svgIDbd)" class="melslfkyu"/></g><g filter="url(#svgIDbe)"><rect class="n6ssbjeul"/></g><path class="cyetwmoqk"/><path fill="url(#svgIDbf)" clip-rule="evenodd" class="zb_6s_bpc"/><path fill="url(#svgIDbg)" clip-rule="evenodd" class="zb_6s_bpc"/><path fill="url(#svgIDbh)" clip-rule="evenodd" class="zb_6s_bpc"/><path fill="url(#svgIDbi)" clip-rule="evenodd" class="ef5twcblb"/><path fill="url(#svgIDbj)" clip-rule="evenodd" class="ef5twcblb"/><circle fill="url(#svgIDbk)" class="bbavuynbz"/><circle fill="url(#svgIDbl)" class="bbavuynbz"/><circle fill="url(#svgIDbm)" class="bbavuynbz"/><path fill="url(#svgIDbn)" class="c_omudd1o"/><path fill="url(#svgIDbo)" class="c_omudd1o"/><path fill="url(#svgIDbp)" class="c_omudd1o"/><path fill="url(#svgIDbq)" class="z7i-v8_4m"/><path fill="url(#svgIDbr)" class="z7i-v8_4m"/><path fill="url(#svgIDbs)" class="z7i-v8_4m"/><path fill="url(#svgIDbt)" class="rvlghrb7s"/><path fill="url(#svgIDbu)" class="rvlghrb7s"/><path fill="url(#svgIDbv)" class="rvlghrb7s"/><path fill="url(#svgIDbw)" class="uv8peyboa"/><g filter="url(#svgIDbx)"><path fill="url(#svgIDby)" class="v-k4sbcir"/><path fill="url(#svgIDbz)" class="v-k4sbcir"/><path fill="url(#svgIDbA)" class="v-k4sbcir"/><path fill="url(#svgIDbB)" class="v-k4sbcir"/></g><g filter="url(#svgIDbC)"><path fill="url(#svgIDbD)" class="n59g-ccqw"/><path fill="url(#svgIDbE)" class="n59g-ccqw"/><path fill="url(#svgIDbF)" class="n59g-ccqw"/><path fill="url(#svgIDbG)" class="n59g-ccqw"/></g><path fill="url(#svgIDbH)" class="cipub5bsd"/><path fill="url(#svgIDbI)" class="cipub5bsd"/><path fill="url(#svgIDbJ)" class="cipub5bsd"/><path class="zbxmxiajz"/><path fill="url(#svgIDbK)" class="r0jvpemxj"/><path fill="url(#svgIDbL)" class="ewzjm5b_p"/><ellipse fill="url(#svgIDbM)" transform="rotate(24.61 18.243 7.134)" class="kf25dcb8a"/><g filter="url(#svgIDbN)"><path fill="url(#svgIDbO)" class="fxwbawq7j"/></g><g filter="url(#svgIDbP)"><rect transform="matrix(-1 0 0 1 19.272 6.554)" class="i2k7fbb6p"/></g><path class="euezxy_lx"/><path fill="url(#svgIDbQ)" clip-rule="evenodd" class="bet7h6b7t"/><path fill="url(#svgIDbR)" clip-rule="evenodd" class="bet7h6b7t"/><path fill="url(#svgIDbS)" clip-rule="evenodd" class="bet7h6b7t"/><path fill="url(#svgIDbT)" clip-rule="evenodd" class="r79c2xb9g"/><path fill="url(#svgIDbU)" clip-rule="evenodd" class="r79c2xb9g"/><circle fill="url(#svgIDbV)" transform="matrix(-1 0 0 1 21.225 7.804)" class="ms4f1oj7g"/><circle fill="url(#svgIDbW)" transform="matrix(-1 0 0 1 21.225 7.804)" class="ms4f1oj7g"/><circle fill="url(#svgIDbX)" transform="matrix(-1 0 0 1 21.225 7.804)" class="ms4f1oj7g"/><defs><radialGradient id="svgIDa" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 19.282 10.66)" gradientUnits="userSpaceOnUse"><stop class="pb8433y7i"/><stop offset=".919" class="qbalqpb4i"/></radialGradient><radialGradient id="svgIDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 -.033 1.45)" gradientUnits="userSpaceOnUse"><stop class="pb8433y7i"/><stop offset=".919" class="qbalqpb4i"/></radialGradient><radialGradient id="svgIDd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71095 2.35327 -5.20382 -5.99476 18.899 10.921)" gradientUnits="userSpaceOnUse"><stop class="jqlzdbc0v"/><stop offset="1" class="lsajvobnn"/></radialGradient><radialGradient id="svgIDf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 11.656 25.539)" gradientUnits="userSpaceOnUse"><stop class="rymggjbfw"/><stop offset="1" class="fftu-ub9g"/></radialGradient><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(2.14185 1.875 -.94292 1.07712 7.39 20.507)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="v3d4kibqu"/><stop offset="1" class="bhu6lxb-s"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(144.26 2.237 11.092) scale(1.23051 3.4979)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="zu500rbyn"/><stop offset="1" class="wp2ykebsl"/></radialGradient><radialGradient id="svgIDo" cx="0" cy="0" r="1" gradientTransform="rotate(-134.195 7.094 8.074) scale(2.212 .64075)" gradientUnits="userSpaceOnUse"><stop class="jjhblb54u"/><stop offset="1" class="bq0pg0bco"/></radialGradient><radialGradient id="svgIDp" cx="0" cy="0" r="1" gradientTransform="rotate(137.394 1.47 9.815) scale(7.8608 1.6626)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="t4m41vbgx"/><stop offset="1" class="hi6yszbkt"/></radialGradient><radialGradient id="svgIDq" cx="0" cy="0" r="1" gradientTransform="matrix(6.96877 -7.18752 5.67939 5.50654 3.781 17.82)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="qpejwlb8n"/><stop offset="1" class="p4686vbiy"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="rotate(-144.397 8.18 13.123) scale(2.17397 2.91043)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64636 -1.26563 1.72963 -2.24994 14.356 28.546)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 11.203 26.367)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="matrix(-.05524 1.73462 -1.20171 -.03827 10.37 11.465)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="j2u72qbdb"/><stop offset="1" class="wf9v9bcjq"/></radialGradient><radialGradient id="svgIDF" cx="0" cy="0" r="1" gradientTransform="rotate(45 -10.455 20.149) scale(2.38098 1.16175)" gradientUnits="userSpaceOnUse"><stop class="k-2pa1b9s"/><stop offset="1" class="thjbg0b5a"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="rotate(137.121 3.018 10.225) scale(3.58218 11.0839)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="ysxro3bqi"/><stop offset="1" class="f9ux2fb1w"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="rotate(105.3 .113 14.76) scale(1.05313 3.4094)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="ed8my-b7w"/><stop offset="1" class="xzfl_qbeq"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.30444 .89737 -2.62413 -.89026 14.56 19.22)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="ed8my-b7w"/><stop offset="1" class="xzfl_qbeq"/></radialGradient><radialGradient id="svgIDK" cx="0" cy="0" r="1" gradientTransform="matrix(-.28295 .92188 -2.48547 -.76287 14.252 19.539)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="ed8my-b7w"/><stop offset="1" class="xzfl_qbeq"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37499 1.625 -1.79466 -1.51854 29.313 10.632)" gradientUnits="userSpaceOnUse"><stop class="ps4x5-m-h"/><stop offset="1" class="k3ij_lbry"/></radialGradient><radialGradient id="svgIDN" cx="0" cy="0" r="1" gradientTransform="matrix(2.12183 -1.33219 1.13322 1.80492 26.394 12.84)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="opo7kb_te"/><stop offset="1" class="nconm6aiw"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 20.343 25.523)" gradientUnits="userSpaceOnUse"><stop class="rymggjbfw"/><stop offset="1" class="fftu-ub9g"/></radialGradient><radialGradient id="svgIDQ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14186 1.87499 -.94291 -1.07712 24.61 20.492)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="v3d4kibqu"/><stop offset="1" class="bhu6lxb-s"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="matrix(.99878 .71875 -2.04315 2.83916 21.468 18.773)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="zu500rbyn"/><stop offset="1" class="wp2ykebsl"/></radialGradient><radialGradient id="svgIDY" cx="0" cy="0" r="1" gradientTransform="matrix(1.542 -1.58594 .4594 .44667 25.75 18.773)" gradientUnits="userSpaceOnUse"><stop class="jjhblb54u"/><stop offset="1" class="bq0pg0bco"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="matrix(5.78575 5.3214 -1.1255 1.22372 22.803 16.028)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="t4m41vbgx"/><stop offset="1" class="hi6yszbkt"/></radialGradient><radialGradient id="svgIDaa" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9688 -7.18748 5.67936 -5.50657 28.218 17.804)" gradientUnits="userSpaceOnUse"><stop offset=".014" class="qpejwlb8n"/><stop offset=".93" class="qpejwlb8n"/><stop offset="1" class="p4686vbiy"/></radialGradient><radialGradient id="svgIDad" cx="0" cy="0" r="1" gradientTransform="matrix(1.76758 -1.26563 1.69437 2.36637 24.81 28.539)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(1.64636 -1.26562 1.72962 2.24995 17.644 28.53)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 20.797 26.351)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDao" cx="0" cy="0" r="1" gradientTransform="matrix(2.43827 .18437 -.24868 3.2888 .122 2.37)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="xrb79z_7h"/><stop offset=".865" class="dw97hraqr"/></radialGradient><radialGradient id="svgIDap" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 2.746 3.121)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="tujlabu3w"/><stop offset="1" class="emw_xvbar"/></radialGradient><radialGradient id="svgIDaq" cx="0" cy="0" r="1" gradientTransform="matrix(1.49685 3.75 -10.37919 4.14298 19.25 14.445)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="sbd7u9opr"/><stop offset=".969" class="d52l18b6g"/></radialGradient><radialGradient id="svgIDau" cx="0" cy="0" r="1" gradientTransform="matrix(0 .49784 -1.34351 0 16.64 17.838)" gradientUnits="userSpaceOnUse"><stop class="uam_jdzuf"/><stop offset="1" class="rczunoa_v"/></radialGradient><radialGradient id="svgIDaA" cx="0" cy="0" r="1" gradientTransform="rotate(123.38 11.47 13.273) scale(2.43251 2.70978)" gradientUnits="userSpaceOnUse"><stop class="cj62lbcet"/><stop offset="1" class="o410gcc4i"/><stop offset="1" class="bvxqh0kmv"/></radialGradient><radialGradient id="svgIDaB" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.275 2.829) scale(.82753 .4039)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDaC" cx="0" cy="0" r="1" gradientTransform="matrix(-.24716 1.2904 -1.34466 -.25755 11.478 6.965)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDaE" cx="0" cy="0" r="1" gradientTransform="matrix(-.79555 -.23096 .11273 -.3883 11.508 7.298)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDaF" cx="0" cy="0" r="1" gradientTransform="matrix(-.24742 1.29177 -1.34608 -.25783 11.474 6.969)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDaI" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.274 2.824) scale(.82748 .40388)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="svgIDaJ" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 2.864 8.222) scale(1.31379 1.36902)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="svgIDaL" cx="0" cy="0" r="1" gradientTransform="matrix(-.26135 .82578 -1.16563 -.3689 15.026 7.64)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="kjqpljl_q"/><stop offset=".875" class="kc3xlwepk"/></radialGradient><radialGradient id="svgIDaO" cx="0" cy="0" r="1" gradientTransform="matrix(.9224 -.05124 .06248 1.1246 11.282 7.415)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="svgIDaP" cx="0" cy="0" r="1" gradientTransform="matrix(-.30425 -5.2321 2.03296 -.11822 14.753 8.274)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="v0f7e6bpj"/><stop offset="1" class="ol6dtebhy"/></radialGradient><radialGradient id="svgIDaQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .42704 -.66598 0 13.544 7.466)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="rotate(-141.016 7.23 1.024) scale(3.38501 5.14583)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31235 -.95656 1.53893 -2.11133 14.684 4.716)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="matrix(.57223 .16228 -.07973 .28116 9.4 8.371)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="matrix(-.97365 -.23061 .61789 -2.60877 11.519 6.748)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="svgIDaW" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.282 2.823) scale(.82709 .40369)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="svgIDaX" cx="0" cy="0" r="1" gradientTransform="matrix(-.24703 1.28973 -1.34395 -.25742 11.494 6.958)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.29893 0 0 -.58077 13.866 7.496)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDba" cx="0" cy="0" r="1" gradientTransform="matrix(-.2733 0 0 -.59145 14.05 7.52)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbg" cx="0" cy="0" r="1" gradientTransform="rotate(14.265 -19.03 47.453) scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="matrix(-.52148 1.82813 -.23787 -.06785 12.149 4.414)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDbj" cx="0" cy="0" r="1" gradientTransform="matrix(-.35156 .1875 -.70184 -1.31597 11.985 9.43)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 12.031 7.32)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbl" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 9.715 7.804)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbm" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 12.063 8.695)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="matrix(.79471 -.23072 .11261 .38789 20.71 7.294)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDbo" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.159 16.03) scale(1.31386 1.3691)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDbq" cx="0" cy="0" r="1" gradientTransform="matrix(.79555 -.23097 .11273 .3883 20.714 7.298)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDbr" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.159 16.034) scale(1.31525 1.37055)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="matrix(.79467 -.23071 .1126 .38787 20.71 7.285)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="svgIDbu" cx="0" cy="0" r="1" gradientTransform="matrix(.24715 1.29033 -1.34458 .25754 20.744 6.955)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="svgIDbw" cx="0" cy="0" r="1" gradientTransform="matrix(.26135 .82578 -1.16563 .3689 17.196 7.64)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="kjqpljl_q"/><stop offset=".875" class="kc3xlwepk"/></radialGradient><radialGradient id="svgIDbz" cx="0" cy="0" r="1" gradientTransform="matrix(-.9224 -.05125 .06248 -1.1246 20.94 7.415)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="svgIDbA" cx="0" cy="0" r="1" gradientTransform="matrix(.30425 -5.2321 2.03296 .11822 17.469 8.274)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="v0f7e6bpj"/><stop offset="1" class="ol6dtebhy"/></radialGradient><radialGradient id="svgIDbB" cx="0" cy="0" r="1" gradientTransform="matrix(0 .42704 -.66598 0 18.678 7.466)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="svgIDbD" cx="0" cy="0" r="1" gradientTransform="matrix(2.63124 -2.12952 3.23726 3.99997 20.015 6.37)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="matrix(1.31235 -.95657 1.53894 2.11132 17.537 4.716)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="svgIDbF" cx="0" cy="0" r="1" gradientTransform="matrix(-.57223 .16227 -.07973 -.28116 22.821 8.371)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="svgIDbG" cx="0" cy="0" r="1" gradientTransform="matrix(.97365 -.2306 .61787 2.60878 20.703 6.748)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="svgIDbH" cx="0" cy="0" r="1" gradientTransform="matrix(.7943 -.2306 .11255 .38768 20.694 7.286)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="svgIDbI" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.156 16.016) scale(1.31317 1.36838)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="svgIDbK" cx="0" cy="0" r="1" gradientTransform="matrix(.29893 0 0 .58077 18.356 7.496)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDbL" cx="0" cy="0" r="1" gradientTransform="matrix(.2733 0 0 .59145 18.172 7.52)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbR" cx="0" cy="0" r="1" gradientTransform="rotate(165.735 10.173 4.397) scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbS" cx="0" cy="0" r="1" gradientTransform="matrix(.52148 1.82813 -.23787 .06785 20.073 4.414)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDbU" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .1875 -.70186 1.31595 20.238 9.43)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbV" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 2.316 .797)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbW" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 0 1.281)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbX" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 2.348 2.172)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><linearGradient id="svgIDi" x1="6.625" x2="8.406" y1="19.945" y2="18.257" gradientUnits="userSpaceOnUse"><stop class="xylxrh5lr"/><stop offset="1" class="dpng9pbvi"/></linearGradient><linearGradient id="svgIDj" x1="8.328" x2="8.153" y1="19.335" y2="19.152" gradientUnits="userSpaceOnUse"><stop class="o5qj3ac-m"/><stop offset="1" class="a151cabub"/></linearGradient><linearGradient id="svgIDk" x1="5.563" x2="6.844" y1="19.382" y2="19.445" gradientUnits="userSpaceOnUse"><stop offset=".28" class="azjp5ub3a"/><stop offset="1" class="yvalde4js"/></linearGradient><linearGradient id="svgIDs" x1="2.251" x2="2.836" y1="28.195" y2="28.328" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDu" x1="5.625" x2="5.625" y1="28.554" y2="28.23" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDx" x1="9.756" x2="10.3" y1="28.32" y2="28.303" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDz" x1="12.899" x2="12.899" y1="28.546" y2="28.222" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDD" x1="10.365" x2="10.365" y1="10.187" y2="14.761" gradientUnits="userSpaceOnUse"><stop class="d9dzcxb5n"/><stop offset="1" class="aqyl6fvtq"/></linearGradient><linearGradient id="svgIDL" x1="13.406" x2="13.641" y1="20.711" y2="20.281" gradientUnits="userSpaceOnUse"><stop offset=".245" class="h3cxb-1sg"/><stop offset="1" class="ly3i0vbsp"/></linearGradient><linearGradient id="svgIDO" x1="25.301" x2="25.832" y1="9.92" y2="11.164" gradientUnits="userSpaceOnUse"><stop class="jf8rttb1k"/><stop offset="1" class="ha9q0mbrk"/></linearGradient><linearGradient id="svgIDS" x1="25.375" x2="23.593" y1="19.929" y2="18.242" gradientUnits="userSpaceOnUse"><stop class="xylxrh5lr"/><stop offset="1" class="dpng9pbvi"/></linearGradient><linearGradient id="svgIDT" x1="23.672" x2="23.847" y1="19.32" y2="19.136" gradientUnits="userSpaceOnUse"><stop class="o5qj3ac-m"/><stop offset="1" class="a151cabub"/></linearGradient><linearGradient id="svgIDU" x1="26.437" x2="25.156" y1="19.367" y2="19.429" gradientUnits="userSpaceOnUse"><stop offset=".28" class="azjp5ub3a"/><stop offset="1" class="yvalde4js"/></linearGradient><linearGradient id="svgIDac" x1="29.749" x2="29.164" y1="28.179" y2="28.312" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDae" x1="26.375" x2="26.375" y1="28.539" y2="28.214" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDah" x1="22.244" x2="21.7" y1="28.304" y2="28.288" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDaj" x1="19.101" x2="19.101" y1="28.531" y2="28.206" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDan" x1="1.732" x2="1.732" y1="0" y2="4.574" gradientUnits="userSpaceOnUse"><stop class="d9dzcxb5n"/><stop offset="1" class="aqyl6fvtq"/></linearGradient><linearGradient id="svgIDar" x1="17.246" x2="17.246" y1="17.248" y2="16.767" gradientUnits="userSpaceOnUse"><stop class="qy_j5083o"/><stop offset="1" class="v9jntfbgm"/><stop offset="1" class="zfb2yrbdn"/></linearGradient><linearGradient id="svgIDas" x1="17.256" x2="17.256" y1="17.876" y2="17.394" gradientUnits="userSpaceOnUse"><stop class="qy_j5083o"/><stop offset="1" class="v9jntfbgm"/><stop offset="1" class="zfb2yrbdn"/></linearGradient><linearGradient id="svgIDat" x1="17.375" x2="17.375" y1="18.608" y2="18.132" gradientUnits="userSpaceOnUse"><stop class="qy_j5083o"/><stop offset="1" class="v9jntfbgm"/><stop offset="1" class="zfb2yrbdn"/></linearGradient><linearGradient id="svgIDav" x1="16.771" x2="16.951" y1="16.75" y2="16.097" gradientUnits="userSpaceOnUse"><stop class="qy_j5083o"/><stop offset="1" class="v9jntfbgm"/><stop offset="1" class="zfb2yrbdn"/></linearGradient><linearGradient id="svgIDay" x1="24.207" x2="19.801" y1="11.976" y2="18.007" gradientUnits="userSpaceOnUse"><stop class="qaebhoh2j"/><stop offset="1" class="udytdoxml"/></linearGradient><linearGradient id="svgIDaD" x1="11.623" x2="11.316" y1="7.333" y2="7.418" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDaG" x1="11.568" x2="11.405" y1="7.373" y2="7.386" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDaK" x1="11.572" x2="11.41" y1="7.36" y2="7.373" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="svgIDaN" x1="11.624" x2="14.753" y1="8.226" y2="8.414" gradientUnits="userSpaceOnUse"><stop class="pxjxg6ezh"/><stop offset="1" class="c18adox7s"/></linearGradient><linearGradient id="svgIDaY" x1="11.588" x2="11.425" y1="7.361" y2="7.374" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="svgIDbb" x1="-.007" x2=".195" y1=".054" y2=".12" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbd" x1="10.01" x2="9.524" y1="7.054" y2="3.884" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><linearGradient id="svgIDbf" x1="11.977" x2="10.903" y1="5.461" y2="6.367" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbi" x1="11.406" x2="12.758" y1="9.07" y2="10.898" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><linearGradient id="svgIDbp" x1="20.598" x2="20.906" y1="7.333" y2="7.418" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDbs" x1="20.654" x2="20.816" y1="7.373" y2="7.386" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDbv" x1="20.65" x2="20.812" y1="7.36" y2="7.373" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="svgIDby" x1="20.598" x2="17.468" y1="8.226" y2="8.414" gradientUnits="userSpaceOnUse"><stop class="pxjxg6ezh"/><stop offset="1" class="c18adox7s"/></linearGradient><linearGradient id="svgIDbJ" x1="20.634" x2="20.796" y1="7.361" y2="7.374" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="svgIDbM" x1="18.165" x2="18.368" y1="7.093" y2="7.159" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbO" x1="22.212" x2="22.698" y1="7.054" y2="3.884" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><linearGradient id="svgIDbQ" x1="20.245" x2="21.319" y1="5.461" y2="6.367" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbT" x1="20.815" x2="19.464" y1="9.07" y2="10.898" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><filter id="svgIDc" width="10.808" height="5.007" x="8.491" y="10.621" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.529412 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.552941 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_16856_3004" result="effect2_innerShadow_16856_3004"/></filter><filter id="svgIDe" width="7.106" height="3.139" x="10.204" y="11.711" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_16856_3004" stdDeviation=".2"/></filter><filter id="svgIDl" width="4.146" height="5.805" x="2.81" y="20.117" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.788235 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.654902 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_16856_3004" result="effect2_innerShadow_16856_3004"/></filter><filter id="svgIDm" width="9.426" height="8.574" x="2.717" y="9.932" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDn" width="5.878" height="6.781" x="2.144" y="13.812" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDr" width="5.139" height="3.208" x="2.051" y="25.546" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDv" width="2.686" height="1.05" x="2.698" y="25.546" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.670588 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDw" width="4.9" height="3.308" x="9.456" y="25.539" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDA" width="2.288" height="1.065" x="9.756" y="25.539" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDC" width="5.149" height="5.149" x="5.666" y="10.454" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_16856_3004" stdDeviation=".125"/></filter><filter id="svgIDG" width="1.796" height="1.427" x="13.37" y="17.871" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.603922 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDV" width="4.146" height="5.805" x="25.066" y="20.117" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.788235 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.654902 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_16856_3004" result="effect2_innerShadow_16856_3004"/></filter><filter id="svgIDW" width="9.426" height="8.574" x="19.857" y="9.916" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDX" width="5.878" height="6.781" x="23.978" y="13.796" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDab" width="5.139" height="3.208" x="24.61" y="25.531" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDaf" width="2.686" height="1.05" x="26.615" y="25.531" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.694118 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDag" width="4.9" height="3.308" x="17.344" y="25.523" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDak" width="2.288" height="1.065" x="20.156" y="25.523" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDam" width="5.149" height="5.149" x="21.185" y="10.438" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_16856_3004" stdDeviation=".125"/></filter><filter id="svgIDaw" width="5.984" height="7.891" x="7.785" y="11.554" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_16856_3004" stdDeviation=".25"/></filter><filter id="svgIDax" width="7.313" height="7.219" x="17.582" y="11.101" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_16856_3004" stdDeviation=".25"/></filter><filter id="svgIDaz" width="4.063" height="3.831" x="25.494" y="10.097" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_16856_3004" stdDeviation=".3"/></filter><filter id="svgIDaH" width="2.322" height="3.133" x="16.526" y="15.747" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_16856_3004" stdDeviation=".25"/></filter><filter id="svgIDaM" width="4.888" height="5.72" x="10.115" y="5.03" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.490196 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDaR" width="6.016" height="5.998" x="8.668" y="3.296" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDbc" width="2.555" height="4.117" x="8.443" y="4.254" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_16856_3004" stdDeviation=".25"/></filter><filter id="svgIDbe" width="1.258" height=".393" x="12.95" y="6.454" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.027451 0 0 0 0 0.0156863 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDbx" width="4.888" height="5.72" x="17.468" y="5.03" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.490196 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDbC" width="6.016" height="5.998" x="17.537" y="3.296" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter><filter id="svgIDbN" width="2.555" height="4.117" x="21.223" y="4.254" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_16856_3004" stdDeviation=".25"/></filter><filter id="svgIDbP" width="1.258" height=".393" x="18.014" y="6.454" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.027451 0 0 0 0 0.0156863 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_16856_3004"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-wrestling-light" /></template>
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

.b8z2shxnu {
  d: path("M10.647 10.766a2.697 2.697 0 0 0-3.821-.08l-3.234 3.126l-.045.034a2.79 2.79 0 0 0-.188.2l-.43.43c-.373.326-1.069 1.252-.66 2.844c.372 1.447.778 2.733.938 3.239a.048.048 0 0 0 .047.034h3.025a.05.05 0 0 0 .05-.054c-.074-.715-.268-1.758-.268-1.758l.876-.735c.133-.09.26-.192.38-.309l3.261-3.177a2.696 2.696 0 0 0 .069-3.794Z");
}

.b9zp3cb7v {
  d: path("M26.406 10.698a.3.3 0 1 0-.024.6l.024-.6Zm1.29.353l.013-.3l-.012.3Zm.899 1.342l.282.103l-.282-.103Zm-.514.532a.3.3 0 0 0 .563.207l-.563-.207Zm-1.7-1.628l1.303.053l.025-.6l-1.303-.052l-.024.6Zm1.932.993l-.232.636l.563.206l.233-.636l-.564-.206Zm-.629-.94a.7.7 0 0 1 .63.94l.563.207a1.3 1.3 0 0 0-1.168-1.746l-.025.6Z");
}

.baf9mgbew {
  d: path("m24.855 20.428l1.082-1.007l1.149-1.023l-3.133-1.906a77.97 77.97 0 0 1-1.4 1.66a.05.05 0 0 0 .003.068l2.23 2.207a.05.05 0 0 0 .07 0Z");
}

.bbavuynbz {
  cx: 10.996px;
  cy: 7.804px;
  r: 1.281px;
}

.bet7h6b7t {
  fill-rule: evenodd;
  d: path("M20.044 3.738a.25.25 0 0 0-.162.314l.949 2.969a.25.25 0 1 0 .476-.152l-.95-2.969a.25.25 0 0 0-.313-.162Z");
}

.bhu6lxb-s {
  stop-color: var(--svg-color--d7918f, #D7918F);
  stop-opacity: 0;
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.bp63byb2o {
  fill: var(--svg-color--fec6b0, #FEC6B0);
  fill-rule: evenodd;
  d: path("M15.127 18.249a.4.4 0 0 1-.188.533l-.996.477a.4.4 0 1 1-.346-.722l.996-.476a.4.4 0 0 1 .534.188Z");
}

.bq0pg0bco {
  stop-color: var(--svg-color--ff5128, #FF5128);
  stop-opacity: 0;
}

.bvxqh0kmv {
  stop-color: var(--svg-color--fdc8b1, #FDC8B1);
  stop-opacity: 0;
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.bz0tvm-_e {
  fill: var(--svg-color--fbc5a9, #FBC5A9);
  fill-rule: evenodd;
  d: path("M13.393 19.256a.45.45 0 0 1 .624-.122l.973.657a.45.45 0 0 1-.503.746l-.973-.656a.45.45 0 0 1-.121-.625Z");
}

.c_omudd1o {
  d: path("m20.544 8.25l.218-1.575a.795.795 0 0 1-.218 1.575Z");
}

.c18adox7s {
  stop-color: var(--svg-color--dfa494, #DFA494);
}

.c1zeyrb4v {
  d: path("M15.503 17.485c0-.215.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.c9evk8b4g {
  d: path("m11.674 8.254l-.218-1.576a.796.796 0 0 0 .218 1.576Z");
}

.c9lu1s8rn {
  fill-rule: evenodd;
  d: path("M27.133 12.458a.1.1 0 0 0-.09-.14l-3.873-.058l.035-2.34l4.25.06c1.653.025 2.653 1.726 1.919 3.234l-1.186 2.545l-2.062-1.02l1.007-2.281Z");
}

.cgmdsqbnw {
  stroke: var(--svg-color--ffbca6, #FFBCA6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.804 13.624c.38.25 1.469.722 2.781.61c1.64-.141 2.656-1.047 3.125-1.922");
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
}

.cipub5bsd {
  d: path("m20.528 8.241l.218-1.574a.794.794 0 0 1-.218 1.574Z");
}

.cj62lbcet {
  stop-color: var(--svg-color--fdc8b1, #FDC8B1);
}

.ct6_m01bp {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
}

.cwns_hb1c {
  d: path("M9.172 22.093L7.133 20.29L9.29 18.1a68.14 68.14 0 0 0 1.903 2.277c.67.77.758 1.77.738 2.262l-.102 2.899H9.805a295.31 295.31 0 0 1-.242-2.727a.954.954 0 0 0-.39-.719Z");
}

.cyetwmoqk {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M13.305 9.063c0-.069.056-.124.124-.124h.607a.124.124 0 0 1 0 .248h-.607a.124.124 0 0 1-.124-.124Z");
}

.d52l18b6g {
  stop-color: var(--svg-color--b57889, #B57889);
}

.d6q_8achq {
  d: path("m16.074 11.77l.536-.517c.123-.11.461-.332.824-.332h.988a.477.477 0 1 1 0 .954h-.866a.224.224 0 0 0-.202.128l-.033.07a.344.344 0 0 0-.002.287l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.056-3.902 2.23c-2.386.056-3.712-1.183-4.258-1.692a10.17 10.17 0 0 0-.108-.1l-.103-.092a1.15 1.15 0 0 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.047.11.099.17.154c.497.454 1.236 1.132 2.533 1.132c.391 0 .884-.014 1.408-.337c.51-.314.937-.699 1.167-.95a.666.666 0 0 1 .124-.108Z");
}

.d9dzcxb5n {
  stop-color: var(--svg-color--ff772a, #FF772A);
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.dfbdq2s9s {
  d: path("M20.156 26.328v-.755a.05.05 0 0 1 .05-.05h1.989a.05.05 0 0 1 .05.055l-.089.89v.02l-2-.16Z");
}

.dm4voe-la {
  d: path("M0 0h2.371v3.351H0z");
}

.dpng9pbvi {
  stop-color: var(--svg-color--fe5823, #FE5823);
}

.dsekwy_sd {
  fill: var(--svg-color--baa4c5, #BAA4C5);
  d: path("m4.703 26.337l.376-.717a.05.05 0 0 0-.044-.074h-2.02a.1.1 0 0 0-.096.076l-.22.874l2.004-.159Z");
}

.dw97hraqr {
  stop-color: var(--svg-color--f6bcac, #F6BCAC);
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.e9d9bj2lv {
  fill: var(--svg-color--fbc5a9, #FBC5A9);
  fill-rule: evenodd;
  d: path("M13.373 18.417a.4.4 0 0 1 .55-.135c.404.245.859.47 1.375.648a.4.4 0 1 1-.26.756a7.874 7.874 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549Z");
}

.ed8my-b7w {
  stop-color: var(--svg-color--e5aea6, #E5AEA6);
  stop-opacity: 0;
}

.ef5twcblb {
  fill-rule: evenodd;
  d: path("M11.102 8.495a.25.25 0 0 1 .325.137c.1.247.285.645.511 1.038c.23.399.488.767.732.975a.25.25 0 0 1-.324.38c-.312-.266-.606-.696-.841-1.105a9.537 9.537 0 0 1-.541-1.1a.25.25 0 0 1 .138-.325Z");
}

.emw_xvbar {
  stop-color: var(--svg-color--eea79d, #EEA79D);
  stop-opacity: 0;
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.euezxy_lx {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M18.917 9.063a.124.124 0 0 0-.124-.124h-.608a.124.124 0 0 0 0 .248h.608a.124.124 0 0 0 .124-.124Z");
}

.ewzjm5b_p {
  d: path("M18.5 7.52a.698.698 0 0 0 .005-.08c0-.203-.086-.367-.192-.367c-.106 0-.192.164-.192.367c0 .027.001.054.004.08h.376Z");
}

.f6mg5tnmy {
  rx: 0.07px;
  ry: 0.096px;
}

.f9ux2fb1w {
  stop-color: var(--svg-color--d8968e, #D8968E);
}

.fftu-ub9g {
  stop-color: var(--svg-color--e1a49c, #E1A49C);
}

.fk4zrip8m {
  stop-color: var(--svg-color--483159, #483159);
}

.ft5dv1b6b {
  fill: none;
}

.fue48-jmh {
  d: path("m9.844 26.483l-.088-.89a.05.05 0 0 1 .05-.054h1.988a.05.05 0 0 1 .05.05v.766c.559.262 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.156-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.fxwbawq7j {
  d: path("M21.814 5.78c.307.825.717 1.78.75 2.091c.738-.675.775-1.692.672-2.476c-.072-.543-.773-.813-1.237-.521c-.334.21-.323.536-.185.906Z");
}

.gg2ehgbth {
  width: 3.464px;
  height: 4.574px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
}

.gpmekbc0a {
  fill: var(--svg-color--bb7263, #BB7263);
  d: path("m16.47 11.597l-.59.57l.297 1.114l1.425-.505l-.08-.117a.316.316 0 0 1-.023-.31l.03-.064a.205.205 0 0 1 .185-.119h.42a.437.437 0 1 0 0-.874h-.907c-.333 0-.643.203-.756.305Z");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gvzw7_bgu {
  fill: var(--svg-color--f1bead, #F1BEAD);
  fill-rule: evenodd;
  d: path("M13.025 19.771a.4.4 0 0 1 .56-.086l.746.547a.4.4 0 1 1-.473.645l-.746-.547a.4.4 0 0 1-.087-.559Z");
}

.h-bh2_bpf {
  stop-color: var(--svg-color--454143, #454143);
}

.h3cxb-1sg {
  stop-color: var(--svg-color--d29795, #D29795);
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.h766w6bjn {
  d: path("M19.316 9.209h2.371v3.351h-2.371z");
}

.h93043b3q {
  d: path("M14.967 7.705c-.17-.16-.259-.4-.282-.5h-.196v1.23c.235.15.57.126.67-.098c.086-.192.022-.431-.192-.632Z");
}

.ha9q0mbrk {
  stop-color: var(--svg-color--d2a990, #D2A990);
  stop-opacity: 0;
}

.hgl82vasr {
  d: path("M21.353 10.75a2.697 2.697 0 0 1 3.821-.08l3.234 3.127l.045.033c.067.064.13.131.188.2l.43.43c.373.326 1.069 1.252.66 2.844a62.46 62.46 0 0 1-.938 3.24a.047.047 0 0 1-.02.026a.052.052 0 0 1-.027.008h-3.025a.05.05 0 0 1-.05-.055c.075-.715.268-1.758.268-1.758l-.876-.735a2.713 2.713 0 0 1-.38-.308l-3.261-3.178a2.696 2.696 0 0 1-.069-3.794Z");
}

.hh9ibwbje {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
  stop-opacity: 0;
}

.hi6yszbkt {
  stop-color: var(--svg-color--ff5c2b, #FF5C2B);
  stop-opacity: 0;
}

.hq1ekobkc {
  stop-color: var(--svg-color--e7a792, #E7A792);
}

.i_emxkhmq {
  stop-color: var(--svg-color--442f88, #442F88);
}

.i2k7fbb6p {
  width: 1.258px;
  height: 0.293px;
  fill: var(--svg-color--222, #222);
  rx: 0.146px;
}

.i7ileabcr {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.17 7.52h-1.081c0-.429.242-.776.54-.776c.298 0 .54.347.54.775Z");
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.j175ldb2t {
  fill: var(--svg-color--ebb69c, #EBB69C);
  fill-rule: evenodd;
  d: path("M23.727 11.743c.627.168 1 .812.833 1.438c-.25.938-.826 1.86-1.893 3.009c-1.075 1.157-2.67 2.248-4.615 2.413a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.833Z");
}

.j2u72qbdb {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
}

.j3y9mvb-x {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("m29.072 14.46l-.664-.664l-3.68 3.954l1.21 1.015s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.055h3.025a.05.05 0 0 0 .047-.035c.16-.505.565-1.792.938-3.239c.409-1.592-.287-2.518-.66-2.844Z");
}

.jbkodbetk {
  fill-rule: evenodd;
  d: path("M13.025 19.771a.4.4 0 0 1 .56-.086l.746.547a.4.4 0 1 1-.473.645l-.746-.547a.4.4 0 0 1-.087-.559Z");
}

.jf8rttb1k {
  stop-color: var(--svg-color--d2a990, #D2A990);
}

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
}

.jjhblb54u {
  stop-color: var(--svg-color--ff5128, #FF5128);
}

.jkpjuyb8g {
  d: path("m11.678 8.25l-.218-1.575a.795.795 0 0 0 .218 1.575Z");
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jqlzdbc0v {
  stop-color: var(--svg-color--d38f7d, #D38F7D);
}

.jv-vvdc2h {
  stop-color: var(--svg-color--433352, #433352);
  stop-opacity: 0;
}

.k-2pa1b9s {
  stop-color: var(--svg-color--d98783, #D98783);
}

.k3ij_lbry {
  stop-color: var(--svg-color--fdbca4, #FDBCA4);
}

.k8s01tfdv {
  stop-color: var(--svg-color--5e5663, #5E5663);
  stop-opacity: 0;
}

.kc3xlwepk {
  stop-color: var(--svg-color--cd8a81, #CD8A81);
}

.kf25dcb8a {
  cx: 18.243px;
  cy: 7.134px;
  rx: 0.07px;
  ry: 0.096px;
}

.kgukkhbth {
  stop-color: var(--svg-color--5e5663, #5E5663);
}

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
}

.kjf54ac2g {
  d: path("M15.846 18.223c0-.213.173-.385.386-.385h1.385l.308.77H16.23a.385.385 0 0 1-.385-.385Z");
}

.kjqpljl_q {
  stop-color: var(--svg-color--e6b19b, #E6B19B);
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l31f_ibry {
  d: path("M13.721 7.52a.676.676 0 0 1-.005-.08c0-.203.087-.367.193-.367c.106 0 .192.164.192.367a.699.699 0 0 1-.005.08h-.375Z");
}

.l6veklvwf {
  stop-color: var(--svg-color--9e94a2, #9E94A2);
}

.l7mbhnbzh {
  stop-color: var(--svg-color--eeb298, #EEB298);
}

.lb6__zbop {
  d: path("M11.844 26.344v-.755a.05.05 0 0 0-.05-.05H9.805a.05.05 0 0 0-.05.054l.089.89v.02l2-.159Z");
}

.letyccc1q {
  fill: var(--svg-color--f4bcaf, #F4BCAF);
  d: path("m28.11 22.234l.57-1.727l-2.876-.39c-.013.093-.071.51-.203 1.43c-.13.918.125 1.663.375 2.203l1.22 2.171h1.866c-.245-.77-.844-2.77-.93-3.03c-.085-.263-.085-.481-.023-.657Z");
}

.lqb9_uf8b {
  d: path("m22.828 22.078l2.039-1.805l-2.156-2.188a68.991 68.991 0 0 1-1.903 2.278c-.67.77-.758 1.77-.738 2.262l.102 2.898h2.023c.068-.734.211-2.308.242-2.727a.954.954 0 0 1 .39-.718Z");
}

.lsajvobnn {
  stop-color: var(--svg-color--d38f7d, #D38F7D);
  stop-opacity: 0;
}

.lxrxf67aa {
  fill: var(--svg-color--efbda9, #EFBDA9);
  d: path("M16.086 15.57a.384.384 0 1 0 0 .77h.518a.065.065 0 0 1 0 .128h1.158v-.129h.254l-.31-.309a1.568 1.568 0 0 0-1.108-.46h-.512Z");
}

.ly3i0vbsp {
  stop-color: var(--svg-color--d29795, #D29795);
  stop-opacity: 0;
}

.m0c3_oaed {
  fill-rule: evenodd;
  d: path("M8.23 11.483a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.544a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

.melslfkyu {
  d: path("M10.408 5.78c-.307.825-.717 1.78-.751 2.091c-.737-.675-.775-1.692-.671-2.476c.071-.543.773-.813 1.236-.521c.335.21.324.536.186.906Z");
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
  stop-opacity: 0;
}

.mqedtfb5e {
  stop-color: var(--svg-color--423948, #423948);
}

.ms4f1oj7g {
  r: 1.281px;
}

.n45ezsbxn {
  fill: var(--svg-color--efbda9, #EFBDA9);
  d: path("M15.846 18.223c0-.213.173-.385.386-.385h1.385l.308.77H16.23a.385.385 0 0 1-.385-.385Z");
}

.n59g-ccqw {
  d: path("M17.665 4.08a1.12 1.12 0 0 1 1.076-.633c.94.052 1.067.376 1.917.201c.898-.185 1.341-.132 1.725.043l.008.003c.379.172 1.163.528 1.163 2.132c0 1.477-.527 2.258-.782 2.537l.05.018c.253.091.357.36.266.614c-.078.215-.352.34-.696.286a22.597 22.597 0 0 1-.91-.161a.272.272 0 0 1-.218-.267V7.637a1.08 1.08 0 0 0-.52-.91c-.017-.53-.18-.773-.445-.901c-.438-.212-.574-.107-1.622-.17c-1.055-.065-1.337-.91-1.012-1.577Z");
}

.n6ssbjeul {
  width: 1.258px;
  height: 0.293px;
  x: 12.95px;
  y: 6.554px;
  fill: var(--svg-color--222, #222);
  rx: 0.146px;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nb7sh9bzw {
  stop-color: var(--svg-color--b1aab6, #B1AAB6);
}

.nconm6aiw {
  stop-color: var(--svg-color--ffa898, #FFA898);
  stop-opacity: 0;
}

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.ngn1gjbbd {
  cx: 17.687px;
  cy: 17.313px;
  fill: var(--svg-color--e9b59d, #E9B59D);
  rx: 0.661px;
  ry: 1.066px;
}

.nh6ki6yxn {
  d: path("m11.678 8.24l-.218-1.574a.795.795 0 0 0 .218 1.574Z");
}

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
}

.nsxb74-gl {
  fill-rule: evenodd;
  d: path("M23.727 11.743c.627.168 1 .812.833 1.438c-.25.938-.826 1.86-1.893 3.009c-1.075 1.157-2.67 2.248-4.615 2.413a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.833Z");
}

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
}

.o410gcc4i {
  stop-color: var(--svg-color--ecb596, #ECB596);
  stop-opacity: 0;
}

.o4dph5bxr {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m22.156 26.468l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.262-.441.564-.438.802c.003.155.143.273.298.273h3.964a.25.25 0 0 0 .25-.25v-1.813Z");
}

.o5qj3ac-m {
  stop-color: var(--svg-color--e73d40, #E73D40);
}

.ob3w450tf {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("m2.928 14.476l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.758a.05.05 0 0 1-.05.054H3.255a.05.05 0 0 1-.047-.034a63.198 63.198 0 0 1-.938-3.24c-.409-1.591.287-2.517.66-2.843Z");
}

.obnmtelja {
  fill: var(--svg-color--fbc4a8, #FBC4A8);
  fill-rule: evenodd;
  d: path("M8.23 11.483a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.544a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

.ocru65npv {
  stop-color: var(--svg-color--3f3646, #3F3646);
}

.ogf6ef1iq {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.187px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.ol6dtebhy {
  stop-color: var(--svg-color--f2beaa, #F2BEAA);
  stop-opacity: 0;
}

.on8sxx3yx {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
  stop-opacity: 0;
}

.opo7kb_te {
  stop-color: var(--svg-color--ff8b82, #FF8B82);
}

.oybn7vbqt {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
}

.ozwe4ruxe {
  fill: var(--svg-color--f3b497, #F3B497);
  d: path("m16.074 11.77l.536-.517c.123-.11.461-.332.824-.332h.988a.477.477 0 1 1 0 .954h-.866a.224.224 0 0 0-.202.128l-.033.07a.344.344 0 0 0-.002.287l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.056-3.902 2.23c-2.386.056-3.712-1.183-4.258-1.692a10.17 10.17 0 0 0-.108-.1l-.103-.092a1.15 1.15 0 0 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.047.11.099.17.154c.497.454 1.236 1.132 2.533 1.132c.391 0 .884-.014 1.408-.337c.51-.314.937-.699 1.167-.95a.666.666 0 0 1 .124-.108Z");
}

.p4686vbiy {
  stop-color: var(--svg-color--fb5d03, #FB5D03);
}

.p6_6x2bgc {
  fill-rule: evenodd;
  d: path("M13.393 19.256a.45.45 0 0 1 .624-.122l.973.657a.45.45 0 0 1-.503.746l-.973-.656a.45.45 0 0 1-.121-.625Z");
}

.pa2jxdc2t {
  d: path("m2.919 25.622l-.66 2.621a.25.25 0 0 0 .242.311h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.865-.763-1.157a86.273 86.273 0 0 1-1.696-.9l.376-.718a.05.05 0 0 0-.044-.074h-2.02a.1.1 0 0 0-.096.076Z");
}

.pb8433y7i {
  stop-color: var(--svg-color--be716e, #BE716E);
}

.pf-fc7btu {
  stop-color: var(--svg-color--454143, #454143);
  stop-opacity: 0;
}

.pf3hjw22a {
  d: path("M13.507 7.52v-.005c0-.35.15-.634.335-.634c.185 0 .335.284.335.634v.004h-.67Z");
}

.pkkx7l7dx {
  stroke: var(--svg-color--ffd4ba, #FFD4BA);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.66 12.43c.073 1.374 2.032 4.874 4.235 6.14");
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.ps4x5-m-h {
  stop-color: var(--svg-color--f7c8ae, #F7C8AE);
}

.ptzuc934d {
  d: path("m11.694 8.241l-.219-1.574a.795.795 0 0 0 .219 1.574Z");
}

.pxj138bcc {
  width: 3.464px;
  height: 4.574px;
  rx: 1.732px;
}

.pxjxg6ezh {
  stop-color: var(--svg-color--dea69d, #DEA69D);
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.q2gydu3zd {
  stop-color: var(--svg-color--3e3a3f, #3E3A3F);
  stop-opacity: 0;
}

.qaebhoh2j {
  stop-color: var(--svg-color--fbcab4, #FBCAB4);
}

.qbalqpb4i {
  stop-color: var(--svg-color--da9483, #DA9483);
}

.qdq-erb7u {
  stop-color: var(--svg-color--e5a88d, #E5A88D);
}

.qihskpbeg {
  stop-color: var(--svg-color--524e8d, #524E8D);
  stop-opacity: 0;
}

.qpejwlb8n {
  stop-color: var(--svg-color--fb5d03, #FB5D03);
  stop-opacity: 0;
}

.qy_j5083o {
  stop-color: var(--svg-color--c2848e, #C2848E);
}

.qyzqptbtz {
  d: path("M14.723 6.651c-.042-.876-.326-1.298-.46-1.421h-4.08l-.068 3.458c.947 2.32 3.839 2.42 4.27 1.58c.432-.839.387-2.603.338-3.617Z");
}

.r_8nwacar {
  d: path("m29.081 25.606l.66 2.621a.25.25 0 0 1-.242.312h-4.441c-.102 0-.196-.06-.22-.16c-.127-.503.196-.865.763-1.156a86.753 86.753 0 0 0 1.696-.901l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075Z");
}

.r0jvpemxj {
  d: path("M18.715 7.52v-.005c0-.35-.15-.634-.336-.634c-.185 0-.335.284-.335.634v.004h.67Z");
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.r79c2xb9g {
  fill-rule: evenodd;
  d: path("M21.12 8.495a.25.25 0 0 0-.326.137a9.05 9.05 0 0 1-.51 1.038c-.23.399-.489.767-.733.975a.25.25 0 0 0 .325.38c.312-.266.605-.696.84-1.105c.24-.415.434-.834.542-1.1a.25.25 0 0 0-.138-.325Z");
}

.rczunoa_v {
  stop-color: var(--svg-color--f2c1b1, #F2C1B1);
  stop-opacity: 0;
}

.rdgulqvms {
  stop-color: var(--svg-color--e1a38b, #E1A38B);
  stop-opacity: 0;
}

.rgr1pfeuu {
  d: path("m2.928 14.476l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.758a.05.05 0 0 1-.05.054H3.255a.05.05 0 0 1-.047-.034a63.198 63.198 0 0 1-.938-3.24c-.409-1.591.287-2.517.66-2.843Z");
}

.rknzqr02l {
  stop-color: var(--svg-color--695d73, #695D73);
  stop-opacity: 0;
}

.rnxu2urvv {
  fill: var(--svg-color--efbda9, #EFBDA9);
  d: path("M15.503 17.485c0-.215.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.rp2piebdz {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m2.919 25.622l-.66 2.621a.25.25 0 0 0 .242.311h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.865-.763-1.157a86.273 86.273 0 0 1-1.696-.9l.376-.718a.05.05 0 0 0-.044-.074h-2.02a.1.1 0 0 0-.096.076Z");
}

.runtb-bmp {
  fill: var(--svg-color--9d91a7, #9D91A7);
  d: path("m27.297 26.322l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075l.22.874l-2.004-.158Z");
}

.rvlghrb7s {
  d: path("m20.544 8.24l.218-1.574a.795.795 0 0 1-.218 1.574Z");
}

.rymggjbfw {
  stop-color: var(--svg-color--eab6aa, #EAB6AA);
}

.sbd7u9opr {
  stop-color: var(--svg-color--dea7a3, #DEA7A3);
  stop-opacity: 0;
}

.scn4k-3ks {
  d: path("M16.086 15.57a.384.384 0 1 0 0 .77h.518a.065.065 0 0 1 0 .128h1.158v-.129h.254l-.31-.309a1.568 1.568 0 0 0-1.108-.46h-.512Z");
}

.sdv86gbgg {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("M6.826 10.686a2.696 2.696 0 0 1 3.753 3.874l-3.262 3.177a2.71 2.71 0 1 1-3.77-3.891l3.28-3.16Z");
}

.shic-ydjf {
  stop-color: var(--svg-color--2e2d2f, #2E2D2F);
}

.sj-jxnbay {
  d: path("m22.156 26.468l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.262-.441.564-.438.802c.003.155.143.273.298.273h3.964a.25.25 0 0 0 .25-.25v-1.813Z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t3b1fti3m {
  d: path("m29.072 14.46l-.664-.664l-3.68 3.954l1.21 1.015s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.055h3.025a.05.05 0 0 0 .047-.035c.16-.505.565-1.792.938-3.239c.409-1.592-.287-2.518-.66-2.844Z");
}

.t4m41vbgx {
  stop-color: var(--svg-color--e6473c, #E6473C);
}

.tahk4luhp {
  d: path("M15.464 16.858a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.thjbg0b5a {
  stop-color: var(--svg-color--d98783, #D98783);
  stop-opacity: 0;
}

.tujlabu3w {
  stop-color: var(--svg-color--eea79d, #EEA79D);
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.u9l1qpq9e {
  d: path("m7.145 20.443l-1.082-1.006l-1.149-1.023l3.133-1.907a77.83 77.83 0 0 0 1.4 1.66a.05.05 0 0 1-.003.068l-2.23 2.207a.05.05 0 0 1-.07.001Z");
}

.uam_jdzuf {
  stop-color: var(--svg-color--f2c1b1, #F2C1B1);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.udytdoxml {
  stop-color: var(--svg-color--fbcab4, #FBCAB4);
  stop-opacity: 0;
}

.ufkgclbst {
  fill: var(--svg-color--f4bcaf, #F4BCAF);
  d: path("m3.913 22.234l-.57-1.727l2.875-.39l.203 1.43c.131.918-.125 1.663-.375 2.203l-1.219 2.17H2.96c.245-.77.844-2.77.93-3.03c.086-.263.086-.481.023-.657Z");
}

.upqgllbnx {
  d: path("M14.557 4.08a1.121 1.121 0 0 0-1.076-.633c-.94.052-1.068.376-1.918.201c-.898-.185-1.34-.132-1.725.043l-.007.003c-.38.172-1.163.528-1.163 2.132c0 1.477.527 2.258.782 2.537l-.05.018c-.253.091-.358.36-.266.614c.078.215.351.34.696.286c.393-.062.682-.116.91-.161a.272.272 0 0 0 .217-.267V7.637c0-.513.362-.819.521-.91c.017-.53.18-.773.444-.901c.439-.212.575-.107 1.623-.17c1.055-.065 1.337-.91 1.012-1.577Z");
}

.uv8peyboa {
  d: path("M17.254 7.705c.171-.16.26-.4.282-.5h.197v1.23c-.235.15-.571.126-.67-.098c-.086-.192-.022-.431.191-.632Z");
}

.v-k4sbcir {
  d: path("M17.499 6.651c.042-.876.326-1.298.46-1.421h4.08l.068 3.458c-.947 2.32-3.839 2.42-4.27 1.58c-.433-.839-.387-2.603-.338-3.617Z");
}

.v0f7e6bpj {
  stop-color: var(--svg-color--f2beaa, #F2BEAA);
}

.v3d4kibqu {
  stop-color: var(--svg-color--d7918f, #D7918F);
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

.vwme3mblx {
  fill: var(--svg-color--efbda9, #EFBDA9);
  d: path("M15.464 16.858a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.w9jnu_bcu {
  width: 0.764px;
  height: 1.4px;
  x: 17.093px;
  y: 15.861px;
  fill: var(--svg-color--f1bca2, #F1BCA2);
  rx: 0.382px;
}

.wf9v9bcjq {
  stop-color: var(--svg-color--ffc9b0, #FFC9B0);
}

.wp2ykebsl {
  stop-color: var(--svg-color--d59c86, #D59C86);
  stop-opacity: 0;
}

.wu90fi6zm {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("M25.174 10.67a2.696 2.696 0 0 0-3.752 3.874l3.261 3.178a2.71 2.71 0 1 0 3.77-3.892l-3.28-3.16Z");
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
}

.x9qbdbcpv {
  fill: var(--svg-color--fbc5a9, #FBC5A9);
  fill-rule: evenodd;
  d: path("M13.609 18.949a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.69l-1.215-.715a.4.4 0 0 1-.142-.548Z");
}

.xabspufox {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m9.844 26.483l-.088-.89a.05.05 0 0 1 .05-.054h1.988a.05.05 0 0 1 .05.05v.766c.559.262 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.156-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.xktf9pbat {
  stop-color: var(--svg-color--564c49, #564C49);
  stop-opacity: 0;
}

.xrb79z_7h {
  stop-color: var(--svg-color--fdccb4, #FDCCB4);
}

.xylxrh5lr {
  stop-color: var(--svg-color--f03814, #F03814);
}

.xzfl_qbeq {
  stop-color: var(--svg-color--c88c92, #C88C92);
}

.y4pe4ezsu {
  stop-color: var(--svg-color--271e2e, #271E2E);
}

.y6flt6btr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M24.02 11.976c-.26 1.313-1.738 4.244-5.563 5.469");
}

.yfv3nqb2s {
  stop-color: var(--svg-color--e4a88b, #E4A88B);
  stop-opacity: 0;
}

.ygv0piz0u {
  fill-rule: evenodd;
  d: path("M13.373 18.417a.4.4 0 0 1 .55-.135c.404.245.859.47 1.375.648a.4.4 0 1 1-.26.756a7.874 7.874 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549Z");
}

.ymlznzbiw {
  fill-rule: evenodd;
  d: path("M13.609 18.949a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.69l-1.215-.715a.4.4 0 0 1-.142-.548Z");
}

.ysxro3bqi {
  stop-color: var(--svg-color--d8968e, #D8968E);
  stop-opacity: 0;
}

.yvalde4js {
  stop-color: var(--svg-color--ed3424, #ED3424);
  stop-opacity: 0;
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.z7i-v8_4m {
  d: path("m20.548 8.254l.218-1.576a.796.796 0 0 1-.218 1.576Z");
}

.zb_6s_bpc {
  fill-rule: evenodd;
  d: path("M12.178 3.738a.25.25 0 0 1 .162.314l-.95 2.969a.25.25 0 0 1-.476-.152l.95-2.969a.25.25 0 0 1 .314-.162Z");
}

.zbxmxiajz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.052 7.52h1.08c0-.429-.241-.776-.54-.776c-.298 0-.54.347-.54.775Z");
}

.zfb2yrbdn {
  stop-color: var(--svg-color--c2848e, #C2848E);
  stop-opacity: 0;
}

.zjmmjyoar {
  stop-color: var(--svg-color--554f5c, #554F5C);
}

.zmlmhacwe {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.187px;
  rx: 1.732px;
}

.zmz0e-b5i {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m29.081 25.606l.66 2.621a.25.25 0 0 1-.242.312h-4.441c-.102 0-.196-.06-.22-.16c-.127-.503.196-.865.763-1.156a86.753 86.753 0 0 0 1.696-.901l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075Z");
}

.zu500rbyn {
  stop-color: var(--svg-color--d59c86, #D59C86);
}

</style>
