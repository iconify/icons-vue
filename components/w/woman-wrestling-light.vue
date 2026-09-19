<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#svgIDa)" transform="rotate(-23.31 19.316 9.24)" class="u1vg6cbkb"/><path fill="url(#svgIDb)" transform="scale(-1 1) rotate(-42.293 6.288 21.658)" class="dm4voe-la"/><path class="ejoi2zbrf"/><g filter="url(#svgIDc)"><path class="b_oylolin"/><path fill="url(#svgIDd)" class="lc3kphb9y"/></g><g filter="url(#svgIDe)"><path class="ah1oyhzoj"/></g><path fill="url(#svgIDf)" class="if5szbclz"/><path fill="url(#svgIDg)" class="if5szbclz"/><path fill="url(#svgIDh)" class="if5szbclz"/><path fill="url(#svgIDi)" class="bda-r-b4i"/><path fill="url(#svgIDj)" class="bda-r-b4i"/><path fill="url(#svgIDk)" class="bda-r-b4i"/><g filter="url(#svgIDl)"><path class="w4s8s2bsv"/></g><g filter="url(#svgIDm)"><path class="g44e0lb3a"/></g><g filter="url(#svgIDn)"><path class="idymw2beg"/><path fill="url(#svgIDo)" class="l5_7ncbeh"/></g><path fill="url(#svgIDp)" class="x_hb57blb"/><path fill="url(#svgIDq)" class="x_hb57blb"/><g filter="url(#svgIDr)"><path class="vzt-qqbid"/><path fill="url(#svgIDs)" class="f1bhxmb2c"/><path fill="url(#svgIDt)" class="f1bhxmb2c"/><path fill="url(#svgIDu)" class="f1bhxmb2c"/></g><g filter="url(#svgIDv)"><path class="rpz882bvf"/></g><g filter="url(#svgIDw)"><path class="fznb35_mw"/><path fill="url(#svgIDx)" class="kwnu21bnt"/><path fill="url(#svgIDy)" class="kwnu21bnt"/><path fill="url(#svgIDz)" class="kwnu21bnt"/></g><g filter="url(#svgIDA)"><path fill="url(#svgIDB)" class="ntik_nbhi"/></g><g filter="url(#svgIDC)"><rect stroke="url(#svgIDD)" transform="rotate(45 8.633 10.219)" class="mfirrnbby"/></g><rect fill="url(#svgIDE)" transform="rotate(45 8.633 10.219)" class="exu2vfb4p"/><rect fill="url(#svgIDF)" transform="rotate(45 8.633 10.219)" class="exu2vfb4p"/><g filter="url(#svgIDG)"><path clip-rule="evenodd" class="dzb306qaf"/></g><path clip-rule="evenodd" class="t7ng9kbhh"/><path fill="url(#svgIDH)" clip-rule="evenodd" class="gamjl0bim"/><path clip-rule="evenodd" class="yh639zbgi"/><path fill="url(#svgIDI)" clip-rule="evenodd" class="jtr87tg1h"/><path clip-rule="evenodd" class="y1knbmbwz"/><path fill="url(#svgIDJ)" clip-rule="evenodd" class="t70trsbww"/><path clip-rule="evenodd" class="xbnmohbay"/><path fill="url(#svgIDK)" clip-rule="evenodd" class="ppcls7ioo"/><path clip-rule="evenodd" class="g897u4bcy"/><path fill="url(#svgIDL)" clip-rule="evenodd" class="nsjv5mb4g"/><path fill="url(#svgIDM)" clip-rule="evenodd" class="ysccakbur"/><path fill="url(#svgIDN)" clip-rule="evenodd" class="ysccakbur"/><path fill="url(#svgIDO)" clip-rule="evenodd" class="ysccakbur"/><rect transform="rotate(-28.166 17.093 15.893)" class="wxd-omf2a"/><path fill="url(#svgIDP)" class="gejkf9n9i"/><path fill="url(#svgIDQ)" class="gejkf9n9i"/><path fill="url(#svgIDR)" class="gejkf9n9i"/><path fill="url(#svgIDS)" class="vizjbkbik"/><path fill="url(#svgIDT)" class="vizjbkbik"/><path fill="url(#svgIDU)" class="vizjbkbik"/><g filter="url(#svgIDV)"><path class="rz8a4x2ve"/></g><g filter="url(#svgIDW)"><path class="qkyy4yb4k"/><path fill="url(#svgIDX)" class="f5vfl_b6x"/></g><g filter="url(#svgIDY)"><path class="t7-mpru2g"/><path fill="url(#svgIDZ)" class="ur4alabfa"/></g><path fill="url(#svgIDaa)" class="atu01ibbw"/><path fill="url(#svgIDab)" class="atu01ibbw"/><g filter="url(#svgIDac)"><path class="e0b0fkm9f"/><path fill="url(#svgIDad)" class="kj8vq-bmb"/><path fill="url(#svgIDae)" class="kj8vq-bmb"/><path fill="url(#svgIDaf)" class="kj8vq-bmb"/></g><g filter="url(#svgIDag)"><path class="ruvtttgun"/></g><g filter="url(#svgIDah)"><path class="g65f0ubpf"/><path fill="url(#svgIDai)" class="e4hz009dr"/><path fill="url(#svgIDaj)" class="e4hz009dr"/><path fill="url(#svgIDak)" class="e4hz009dr"/></g><g filter="url(#svgIDal)"><path fill="url(#svgIDam)" class="wf-ixsb0z"/></g><g filter="url(#svgIDan)"><rect stroke="url(#svgIDao)" transform="scale(-1 1) rotate(45 -24 -23.105)" class="gg2ehgbth"/></g><rect fill="url(#svgIDap)" transform="scale(-1 1) rotate(45 -24 -23.105)" class="pxj138bcc"/><rect fill="url(#svgIDaq)" transform="scale(-1 1) rotate(45 -24 -23.105)" class="pxj138bcc"/><path clip-rule="evenodd" class="bv_xr1btk"/><path fill="url(#svgIDar)" clip-rule="evenodd" class="ue5h9-fhx"/><path class="eb9tfl2op"/><path fill="url(#svgIDas)" class="frolqqh9d"/><path class="s4-7dmb-e"/><path fill="url(#svgIDat)" class="k6dy1v0mq"/><path class="vdgfppb6q"/><path fill="url(#svgIDau)" class="q8o5hvb9j"/><path fill="url(#svgIDav)" class="q8o5hvb9j"/><path class="b82uibb_j"/><path fill="url(#svgIDaw)" class="f543rsa1t"/><g filter="url(#svgIDax)"><path class="ec6bpst3z"/></g><g filter="url(#svgIDay)"><path stroke="url(#svgIDaz)" class="iitldjupn"/></g><g filter="url(#svgIDaA)"><path fill="url(#svgIDaB)" class="w3nxk5b5c"/></g><path fill="url(#svgIDaC)" class="py9zg4b1k"/><path fill="url(#svgIDaD)" class="py9zg4b1k"/><path fill="url(#svgIDaE)" class="py9zg4b1k"/><path fill="url(#svgIDaF)" class="u0u3fxb4v"/><path fill="url(#svgIDaG)" class="u0u3fxb4v"/><path fill="url(#svgIDaH)" class="u0u3fxb4v"/><g filter="url(#svgIDaI)"><ellipse class="amtkixbbt"/></g><path fill="url(#svgIDaJ)" class="ktitqk87w"/><path fill="url(#svgIDaK)" class="ktitqk87w"/><path fill="url(#svgIDaL)" class="ktitqk87w"/><path fill="url(#svgIDaM)" class="tw_a5_m2v"/><path fill="url(#svgIDaN)" class="tw_a5_m2v"/><path fill="url(#svgIDaO)" class="tw_a5_m2v"/><path class="l7fhg9boh"/><path fill="url(#svgIDaP)" class="llfrtjbtl"/><path fill="url(#svgIDaQ)" class="q5_1ldb2m"/><ellipse fill="url(#svgIDaR)" transform="scale(-1 1) rotate(24.61 -23.416 -28.46)" class="f6mg5tnmy"/><path fill="url(#svgIDaS)" class="atnjv4bvz"/><g filter="url(#svgIDaT)"><path fill="url(#svgIDaU)" class="l-yj001re"/><path fill="url(#svgIDaV)" class="l-yj001re"/><path fill="url(#svgIDaW)" class="l-yj001re"/><path fill="url(#svgIDaX)" class="l-yj001re"/></g><g filter="url(#svgIDaY)"><path class="kjrf-wbwh"/><path fill="url(#svgIDaZ)" class="kr4hkszwv"/></g><path fill="url(#svgIDba)" class="e-5d1q48i"/><path fill="url(#svgIDbb)" class="e-5d1q48i"/><path fill="url(#svgIDbc)" class="e-5d1q48i"/><path class="ru37_nz_z"/><path class="oxsco296q"/><path fill="url(#svgIDbd)" class="sg_mzvbjo"/><path fill="url(#svgIDbe)" class="issi09x9i"/><ellipse fill="url(#svgIDbf)" transform="scale(-1 1) rotate(25.583 -22.789 -27.047)" class="y7_fahboe"/><circle fill="url(#svgIDbg)" class="como7ddxy"/><circle fill="url(#svgIDbh)" class="como7ddxy"/><circle fill="url(#svgIDbi)" class="como7ddxy"/><g filter="url(#svgIDbj)"><rect class="af0ckx5jc"/></g><path class="bnc6nbb7m"/><path fill="url(#svgIDbk)" clip-rule="evenodd" class="qabi1jb_x"/><path fill="url(#svgIDbl)" clip-rule="evenodd" class="qabi1jb_x"/><path fill="url(#svgIDbm)" clip-rule="evenodd" class="qabi1jb_x"/><path fill="url(#svgIDbn)" clip-rule="evenodd" class="aps-jonfe"/><path fill="url(#svgIDbo)" clip-rule="evenodd" class="aps-jonfe"/><path fill="url(#svgIDbp)" class="hm962tptp"/><path fill="url(#svgIDbq)" class="hm962tptp"/><path fill="url(#svgIDbr)" class="hm962tptp"/><path fill="url(#svgIDbs)" class="zsy9bdw9u"/><path fill="url(#svgIDbt)" class="zsy9bdw9u"/><path fill="url(#svgIDbu)" class="zsy9bdw9u"/><path fill="url(#svgIDbv)" class="pjqt20gbi"/><path fill="url(#svgIDbw)" class="pjqt20gbi"/><path fill="url(#svgIDbx)" class="pjqt20gbi"/><path fill="url(#svgIDby)" class="flj8nzo2q"/><path fill="url(#svgIDbz)" class="flj8nzo2q"/><path fill="url(#svgIDbA)" class="flj8nzo2q"/><path class="vnpn-sbga"/><path fill="url(#svgIDbB)" class="zqa2bhb_d"/><path fill="url(#svgIDbC)" class="guac_1e6k"/><ellipse fill="url(#svgIDbD)" transform="rotate(24.61 18.073 7.166)" class="ud8eo6bjs"/><path fill="url(#svgIDbE)" class="edi_s6uxc"/><g filter="url(#svgIDbF)"><path fill="url(#svgIDbG)" class="dxnns8bwz"/><path fill="url(#svgIDbH)" class="dxnns8bwz"/><path fill="url(#svgIDbI)" class="dxnns8bwz"/><path fill="url(#svgIDbJ)" class="dxnns8bwz"/></g><g filter="url(#svgIDbK)"><path class="jlfuqjzvr"/><path fill="url(#svgIDbL)" class="u9kl9xb7o"/></g><path fill="url(#svgIDbM)" class="lx4g3m1rx"/><path fill="url(#svgIDbN)" class="lx4g3m1rx"/><path fill="url(#svgIDbO)" class="lx4g3m1rx"/><path class="zfi5gyb6q"/><path class="se3x0fpgw"/><path fill="url(#svgIDbP)" class="y527_ubzz"/><path fill="url(#svgIDbQ)" class="n36-u1vxv"/><ellipse fill="url(#svgIDbR)" transform="rotate(25.583 18.138 7.189)" class="dt2tox52b"/><circle fill="url(#svgIDbS)" transform="matrix(-1 0 0 1 21.055 7.836)" class="ms4f1oj7g"/><circle fill="url(#svgIDbT)" transform="matrix(-1 0 0 1 21.055 7.836)" class="ms4f1oj7g"/><circle fill="url(#svgIDbU)" transform="matrix(-1 0 0 1 21.055 7.836)" class="ms4f1oj7g"/><g filter="url(#svgIDbV)"><rect transform="matrix(-1 0 0 1 19.157 6.499)" class="i2k7fbb6p"/></g><path class="f58ia5y4u"/><path fill="url(#svgIDbW)" clip-rule="evenodd" class="ro_82sbvp"/><path fill="url(#svgIDbX)" clip-rule="evenodd" class="ro_82sbvp"/><path fill="url(#svgIDbY)" clip-rule="evenodd" class="ro_82sbvp"/><path fill="url(#svgIDbZ)" clip-rule="evenodd" class="m0ovwfbvo"/><path fill="url(#svgIDca)" clip-rule="evenodd" class="m0ovwfbvo"/><defs><radialGradient id="svgIDa" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 19.282 10.691)" gradientUnits="userSpaceOnUse"><stop class="pb8433y7i"/><stop offset=".919" class="qbalqpb4i"/></radialGradient><radialGradient id="svgIDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 -.033 1.45)" gradientUnits="userSpaceOnUse"><stop class="pb8433y7i"/><stop offset=".919" class="qbalqpb4i"/></radialGradient><radialGradient id="svgIDd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71095 2.35327 -5.20382 -5.99476 18.899 10.953)" gradientUnits="userSpaceOnUse"><stop class="jqlzdbc0v"/><stop offset="1" class="lsajvobnn"/></radialGradient><radialGradient id="svgIDf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 11.656 25.57)" gradientUnits="userSpaceOnUse"><stop class="rymggjbfw"/><stop offset="1" class="fftu-ub9g"/></radialGradient><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(2.14185 1.875 -.94292 1.07712 7.39 20.54)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="v3d4kibqu"/><stop offset="1" class="bhu6lxb-s"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(144.26 2.232 11.108) scale(1.23051 3.4979)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="zu500rbyn"/><stop offset="1" class="wp2ykebsl"/></radialGradient><radialGradient id="svgIDo" cx="0" cy="0" r="1" gradientTransform="rotate(-134.195 7.1 8.09) scale(2.212 .64075)" gradientUnits="userSpaceOnUse"><stop class="sf5518bjn"/><stop offset="1" class="t77q9um-l"/></radialGradient><radialGradient id="svgIDp" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6084 4.12475 -1.56989 -1.37337 8.893 16.5)" gradientUnits="userSpaceOnUse"><stop class="r7-2aybwm"/><stop offset="1" class="kuufpibxl"/></radialGradient><radialGradient id="svgIDq" cx="0" cy="0" r="1" gradientTransform="matrix(6.96877 -7.18752 5.67939 5.50654 3.781 17.852)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="qn4r5dznz"/><stop offset="1" class="qpxjwkb-f"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="rotate(-144.397 8.184 13.139) scale(2.17397 2.91043)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64636 -1.26563 1.72963 -2.24994 14.356 28.578)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 11.203 26.399)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="matrix(-.05524 1.73462 -1.20171 -.03827 10.37 11.497)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="j2u72qbdb"/><stop offset="1" class="wf9v9bcjq"/></radialGradient><radialGradient id="svgIDF" cx="0" cy="0" r="1" gradientTransform="rotate(45 -10.493 20.165) scale(2.38098 1.16175)" gradientUnits="userSpaceOnUse"><stop class="k-2pa1b9s"/><stop offset="1" class="thjbg0b5a"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="rotate(137.121 3.012 10.24) scale(3.58218 11.0839)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="ysxro3bqi"/><stop offset="1" class="f9ux2fb1w"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="rotate(105.3 .1 14.776) scale(1.05313 3.4094)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="ed8my-b7w"/><stop offset="1" class="xzfl_qbeq"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.30444 .89737 -2.62413 -.89026 14.56 19.252)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="ed8my-b7w"/><stop offset="1" class="xzfl_qbeq"/></radialGradient><radialGradient id="svgIDK" cx="0" cy="0" r="1" gradientTransform="matrix(-.28295 .92188 -2.48547 -.76287 14.252 19.57)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="ed8my-b7w"/><stop offset="1" class="xzfl_qbeq"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37499 1.625 -1.79466 -1.51854 29.313 10.664)" gradientUnits="userSpaceOnUse"><stop class="ps4x5-m-h"/><stop offset="1" class="k3ij_lbry"/></radialGradient><radialGradient id="svgIDN" cx="0" cy="0" r="1" gradientTransform="matrix(2.12183 -1.33219 1.13322 1.80492 26.394 12.871)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="opo7kb_te"/><stop offset="1" class="nconm6aiw"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 20.343 25.555)" gradientUnits="userSpaceOnUse"><stop class="rymggjbfw"/><stop offset="1" class="fftu-ub9g"/></radialGradient><radialGradient id="svgIDQ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14186 1.87499 -.94291 -1.07712 24.61 20.524)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="v3d4kibqu"/><stop offset="1" class="bhu6lxb-s"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="matrix(.99878 .71875 -2.04315 2.83916 21.468 18.805)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="zu500rbyn"/><stop offset="1" class="wp2ykebsl"/></radialGradient><radialGradient id="svgIDX" cx="0" cy="0" r="1" gradientTransform="matrix(2.60893 -2.00527 .56154 .73058 22.336 16.24)" gradientUnits="userSpaceOnUse"><stop class="sf5518bjn"/><stop offset="1" class="t77q9um-l"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.542 -1.58594 .4594 .44667 25.75 18.805)" gradientUnits="userSpaceOnUse"><stop class="sf5518bjn"/><stop offset="1" class="t77q9um-l"/></radialGradient><radialGradient id="svgIDaa" cx="0" cy="0" r="1" gradientTransform="matrix(3.6084 4.12476 -1.5699 1.37336 23.107 16.485)" gradientUnits="userSpaceOnUse"><stop class="r7-2aybwm"/><stop offset="1" class="kuufpibxl"/></radialGradient><radialGradient id="svgIDab" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9688 -7.18748 5.67936 -5.50657 28.218 17.836)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="qn4r5dznz"/><stop offset="1" class="qpxjwkb-f"/></radialGradient><radialGradient id="svgIDae" cx="0" cy="0" r="1" gradientTransform="matrix(1.76758 -1.26563 1.69437 2.36637 24.81 28.57)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDaj" cx="0" cy="0" r="1" gradientTransform="matrix(1.64636 -1.26562 1.72962 2.24995 17.644 28.563)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDam" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 20.797 26.383)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDap" cx="0" cy="0" r="1" gradientTransform="matrix(2.43827 .18437 -.24868 3.2888 .122 2.37)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="xrb79z_7h"/><stop offset=".865" class="dw97hraqr"/></radialGradient><radialGradient id="svgIDaq" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 2.746 3.121)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="tujlabu3w"/><stop offset="1" class="emw_xvbar"/></radialGradient><radialGradient id="svgIDar" cx="0" cy="0" r="1" gradientTransform="matrix(1.49685 3.75 -10.37919 4.14298 19.25 14.477)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="sbd7u9opr"/><stop offset=".969" class="d52l18b6g"/></radialGradient><radialGradient id="svgIDav" cx="0" cy="0" r="1" gradientTransform="matrix(0 .49784 -1.34351 0 16.64 17.87)" gradientUnits="userSpaceOnUse"><stop class="uam_jdzuf"/><stop offset="1" class="rczunoa_v"/></radialGradient><radialGradient id="svgIDaB" cx="0" cy="0" r="1" gradientTransform="rotate(123.38 11.461 13.289) scale(2.43251 2.70978)" gradientUnits="userSpaceOnUse"><stop class="cj62lbcet"/><stop offset="1" class="o410gcc4i"/><stop offset="1" class="bvxqh0kmv"/></radialGradient><radialGradient id="svgIDaC" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.277 2.844) scale(.82753 .4039)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDaD" cx="0" cy="0" r="1" gradientTransform="matrix(-.24716 1.2904 -1.34466 -.25755 11.478 6.997)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDaF" cx="0" cy="0" r="1" gradientTransform="matrix(-.79555 -.23096 .11273 -.3883 11.508 7.33)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDaG" cx="0" cy="0" r="1" gradientTransform="matrix(-.24742 1.29177 -1.34608 -.25783 11.474 7)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDaJ" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.276 2.84) scale(.82748 .40388)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="svgIDaK" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 2.85 8.238) scale(1.31379 1.36902)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="svgIDaM" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.284 2.84) scale(.82709 .40369)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="svgIDaN" cx="0" cy="0" r="1" gradientTransform="matrix(-.24703 1.28973 -1.34395 -.25742 11.494 6.99)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="svgIDaP" cx="0" cy="0" r="1" gradientTransform="matrix(-.29893 0 0 -.58077 13.866 7.528)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDaQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.2733 0 0 -.59145 14.05 7.551)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="rotate(106.589 4.626 9.424) scale(.87506 1.23518)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="kjqpljl_q"/><stop offset=".875" class="kc3xlwepk"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="matrix(.93088 -.06759 .0824 1.13492 11.194 7.518)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="svgIDaW" cx="0" cy="0" r="1" gradientTransform="matrix(-.3971 -5.2799 2.05154 -.1543 14.715 8.327)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="v0f7e6bpj"/><stop offset="1" class="ol6dtebhy"/></radialGradient><radialGradient id="svgIDaX" cx="0" cy="0" r="1" gradientTransform="matrix(.00733 .43137 -.67273 .01142 13.479 7.531)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.70307 -.44794 .95992 -3.64966 14.601 4.991)" gradientUnits="userSpaceOnUse"><stop class="tzf255bgc"/><stop offset="1" class="ctuud_14h"/></radialGradient><radialGradient id="svgIDba" cx="0" cy="0" r="1" gradientTransform="rotate(-164.783 6.257 2.926) scale(.8356 .40784)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="svgIDbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2274 1.30703 -1.36199 -.23697 11.486 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="svgIDbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.30196 .005 -.00973 -.58667 13.803 7.56)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.27548 .00468 -.01012 -.59615 13.99 7.575)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbg" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 12.031 7.352)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 9.715 7.836)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 12.063 8.727)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><radialGradient id="svgIDbl" cx="0" cy="0" r="1" gradientTransform="matrix(.23047 .0586 -.60662 2.38602 11.106 6.184)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbm" cx="0" cy="0" r="1" gradientTransform="matrix(-.52148 1.82813 -.23787 -.06785 12.149 4.446)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDbo" cx="0" cy="0" r="1" gradientTransform="matrix(-.35156 .1875 -.70184 -1.31597 11.985 9.461)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbp" cx="0" cy="0" r="1" gradientTransform="matrix(.79471 -.23072 .11261 .38789 20.54 7.326)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDbq" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.055 15.943) scale(1.31386 1.3691)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDbs" cx="0" cy="0" r="1" gradientTransform="matrix(.79555 -.23097 .11273 .3883 20.544 7.33)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="matrix(.24742 1.29177 -1.34608 .25782 20.578 7)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDbv" cx="0" cy="0" r="1" gradientTransform="matrix(.79467 -.23071 .1126 .38787 20.54 7.317)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="svgIDbw" cx="0" cy="0" r="1" gradientTransform="matrix(.24715 1.29033 -1.34458 .25754 20.573 6.988)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="svgIDby" cx="0" cy="0" r="1" gradientTransform="matrix(.7943 -.2306 .11255 .38768 20.524 7.318)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="svgIDbz" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.051 15.93) scale(1.31317 1.36838)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="svgIDbB" cx="0" cy="0" r="1" gradientTransform="matrix(.29893 0 0 .58077 18.186 7.528)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDbC" cx="0" cy="0" r="1" gradientTransform="matrix(.2733 0 0 .59145 18.002 7.551)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="rotate(73.411 3.385 15.29) scale(.87506 1.23518)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="kjqpljl_q"/><stop offset=".875" class="kc3xlwepk"/></radialGradient><radialGradient id="svgIDbH" cx="0" cy="0" r="1" gradientTransform="matrix(-.93088 -.0676 .0824 -1.13492 20.858 7.518)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="svgIDbI" cx="0" cy="0" r="1" gradientTransform="matrix(.3971 -5.2799 2.05154 .1543 17.337 8.327)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="v0f7e6bpj"/><stop offset="1" class="ol6dtebhy"/></radialGradient><radialGradient id="svgIDbJ" cx="0" cy="0" r="1" gradientTransform="rotate(90.973 5.584 12.896) scale(.43143 .67283)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="svgIDbL" cx="0" cy="0" r="1" gradientTransform="matrix(1.70307 -.44793 .95991 3.64967 17.45 4.991)" gradientUnits="userSpaceOnUse"><stop class="tzf255bgc"/><stop offset="1" class="ctuud_14h"/></radialGradient><radialGradient id="svgIDbM" cx="0" cy="0" r="1" gradientTransform="matrix(.8063 -.21931 .10704 .39354 20.526 7.392)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="svgIDbN" cx="0" cy="0" r="1" gradientTransform="matrix(.2274 1.30703 -1.36199 .23697 20.566 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="svgIDbP" cx="0" cy="0" r="1" gradientTransform="matrix(.30196 .00513 -.00996 .58666 18.247 7.556)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDbQ" cx="0" cy="0" r="1" gradientTransform="matrix(.27548 .00468 -.01012 .59616 18.061 7.575)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbS" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 2.316 .797)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbT" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 0 1.281)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbU" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 2.348 2.172)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><radialGradient id="svgIDbX" cx="0" cy="0" r="1" gradientTransform="rotate(165.735 10.086 4.402) scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbY" cx="0" cy="0" r="1" gradientTransform="matrix(.52148 1.82813 -.23787 .06785 19.903 4.446)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDca" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .1875 -.70185 1.31597 20.067 9.461)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><linearGradient id="svgIDi" x1="6.625" x2="8.406" y1="19.977" y2="18.289" gradientUnits="userSpaceOnUse"><stop class="xoi0djbjo"/><stop offset="1" class="gl6qqfkzm"/></linearGradient><linearGradient id="svgIDj" x1="8.328" x2="8.153" y1="19.367" y2="19.184" gradientUnits="userSpaceOnUse"><stop class="j3zvk_bdt"/><stop offset="1" class="k78l4l0qb"/></linearGradient><linearGradient id="svgIDk" x1="5.563" x2="6.844" y1="19.414" y2="19.477" gradientUnits="userSpaceOnUse"><stop offset=".28" class="o22_o0bcf"/><stop offset="1" class="gfdvmwbxq"/></linearGradient><linearGradient id="svgIDs" x1="2.251" x2="2.836" y1="28.227" y2="28.36" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDu" x1="5.625" x2="5.625" y1="28.586" y2="28.262" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDx" x1="9.756" x2="10.3" y1="28.352" y2="28.335" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDz" x1="12.899" x2="12.899" y1="28.578" y2="28.254" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDD" x1="10.365" x2="10.365" y1="10.219" y2="14.793" gradientUnits="userSpaceOnUse"><stop class="pyu7r8zmo"/><stop offset="1" class="mq17zybfl"/></linearGradient><linearGradient id="svgIDL" x1="13.406" x2="13.641" y1="20.743" y2="20.313" gradientUnits="userSpaceOnUse"><stop offset=".245" class="h3cxb-1sg"/><stop offset="1" class="ly3i0vbsp"/></linearGradient><linearGradient id="svgIDO" x1="25.301" x2="25.832" y1="9.952" y2="11.195" gradientUnits="userSpaceOnUse"><stop class="jf8rttb1k"/><stop offset="1" class="ha9q0mbrk"/></linearGradient><linearGradient id="svgIDS" x1="25.375" x2="23.593" y1="19.961" y2="18.274" gradientUnits="userSpaceOnUse"><stop class="xoi0djbjo"/><stop offset="1" class="gl6qqfkzm"/></linearGradient><linearGradient id="svgIDT" x1="23.672" x2="23.847" y1="19.352" y2="19.168" gradientUnits="userSpaceOnUse"><stop class="j3zvk_bdt"/><stop offset="1" class="k78l4l0qb"/></linearGradient><linearGradient id="svgIDU" x1="26.437" x2="25.156" y1="19.399" y2="19.461" gradientUnits="userSpaceOnUse"><stop offset=".28" class="o22_o0bcf"/><stop offset="1" class="gfdvmwbxq"/></linearGradient><linearGradient id="svgIDad" x1="29.749" x2="29.164" y1="28.211" y2="28.344" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDaf" x1="26.375" x2="26.375" y1="28.571" y2="28.246" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDai" x1="22.244" x2="21.7" y1="28.336" y2="28.32" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDak" x1="19.101" x2="19.101" y1="28.563" y2="28.238" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDao" x1="1.732" x2="1.732" y1="0" y2="4.574" gradientUnits="userSpaceOnUse"><stop class="pyu7r8zmo"/><stop offset="1" class="mq17zybfl"/></linearGradient><linearGradient id="svgIDas" x1="17.246" x2="17.246" y1="17.28" y2="16.799" gradientUnits="userSpaceOnUse"><stop class="qy_j5083o"/><stop offset="1" class="v9jntfbgm"/><stop offset="1" class="zfb2yrbdn"/></linearGradient><linearGradient id="svgIDat" x1="17.256" x2="17.256" y1="17.908" y2="17.426" gradientUnits="userSpaceOnUse"><stop class="qy_j5083o"/><stop offset="1" class="v9jntfbgm"/><stop offset="1" class="zfb2yrbdn"/></linearGradient><linearGradient id="svgIDau" x1="17.375" x2="17.375" y1="18.64" y2="18.164" gradientUnits="userSpaceOnUse"><stop class="qy_j5083o"/><stop offset="1" class="v9jntfbgm"/><stop offset="1" class="zfb2yrbdn"/></linearGradient><linearGradient id="svgIDaw" x1="16.771" x2="16.951" y1="16.782" y2="16.129" gradientUnits="userSpaceOnUse"><stop class="qy_j5083o"/><stop offset="1" class="v9jntfbgm"/><stop offset="1" class="zfb2yrbdn"/></linearGradient><linearGradient id="svgIDaz" x1="24.207" x2="19.801" y1="12.008" y2="18.039" gradientUnits="userSpaceOnUse"><stop class="qaebhoh2j"/><stop offset="1" class="udytdoxml"/></linearGradient><linearGradient id="svgIDaE" x1="11.623" x2="11.316" y1="7.365" y2="7.45" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDaH" x1="11.568" x2="11.405" y1="7.405" y2="7.418" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDaL" x1="11.572" x2="11.41" y1="7.392" y2="7.405" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="svgIDaO" x1="11.588" x2="11.425" y1="7.393" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="svgIDaR" x1="-.007" x2=".195" y1=".054" y2=".12" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDaU" x1="11.553" x2="14.717" y1="8.332" y2="8.468" gradientUnits="userSpaceOnUse"><stop class="pxjxg6ezh"/><stop offset="1" class="c18adox7s"/></linearGradient><linearGradient id="svgIDbc" x1="11.588" x2="11.424" y1="7.466" y2="7.482" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="svgIDbf" x1="-.007" x2=".197" y1=".055" y2=".121" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbk" x1="11.977" x2="10.903" y1="5.492" y2="6.399" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbn" x1="11.406" x2="12.758" y1="9.102" y2="10.93" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><linearGradient id="svgIDbr" x1="20.428" x2="20.736" y1="7.365" y2="7.45" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDbu" x1="20.484" x2="20.646" y1="7.405" y2="7.418" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDbx" x1="20.48" x2="20.642" y1="7.392" y2="7.405" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="svgIDbA" x1="20.464" x2="20.626" y1="7.393" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="svgIDbD" x1="17.995" x2="18.198" y1="7.125" y2="7.191" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbG" x1="20.499" x2="17.335" y1="8.332" y2="8.468" gradientUnits="userSpaceOnUse"><stop class="pxjxg6ezh"/><stop offset="1" class="c18adox7s"/></linearGradient><linearGradient id="svgIDbO" x1="20.464" x2="20.628" y1="7.466" y2="7.482" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="svgIDbR" x1="18.06" x2="18.265" y1="7.147" y2="7.214" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbW" x1="20.075" x2="21.149" y1="5.492" y2="6.399" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbZ" x1="20.645" x2="19.294" y1="9.102" y2="10.93" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><filter id="svgIDc" width="10.808" height="5.007" x="8.491" y="10.653" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.529412 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.552941 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23640" result="effect2_innerShadow_3987_23640"/></filter><filter id="svgIDe" width="7.106" height="3.139" x="10.204" y="11.743" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23640" stdDeviation=".2"/></filter><filter id="svgIDl" width="4.146" height="5.805" x="2.81" y="20.149" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.788235 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.654902 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23640" result="effect2_innerShadow_3987_23640"/></filter><filter id="svgIDm" width="9.426" height="8.574" x="2.717" y="9.964" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.470588 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDn" width="5.878" height="6.781" x="2.144" y="13.844" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.470588 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDr" width="5.139" height="3.208" x="2.051" y="25.578" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDv" width="2.686" height="1.05" x="2.698" y="25.578" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.670588 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDw" width="4.9" height="3.308" x="9.456" y="25.571" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDA" width="2.288" height="1.065" x="9.756" y="25.571" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDC" width="5.149" height="5.149" x="5.666" y="10.486" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23640" stdDeviation=".125"/></filter><filter id="svgIDG" width="1.796" height="1.427" x="13.37" y="17.903" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.603922 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDV" width="4.146" height="5.805" x="25.066" y="20.149" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.788235 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.654902 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23640" result="effect2_innerShadow_3987_23640"/></filter><filter id="svgIDW" width="9.426" height="8.574" x="19.857" y="9.948" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.470588 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDY" width="5.878" height="6.781" x="23.978" y="13.828" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.470588 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDac" width="5.139" height="3.208" x="24.61" y="25.563" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDag" width="2.686" height="1.05" x="26.615" y="25.563" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.694118 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDah" width="4.9" height="3.308" x="17.344" y="25.555" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDal" width="2.288" height="1.065" x="20.156" y="25.555" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDan" width="5.149" height="5.149" x="21.185" y="10.47" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23640" stdDeviation=".125"/></filter><filter id="svgIDax" width="5.984" height="7.891" x="7.785" y="11.586" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23640" stdDeviation=".25"/></filter><filter id="svgIDay" width="7.313" height="7.219" x="17.582" y="11.133" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23640" stdDeviation=".25"/></filter><filter id="svgIDaA" width="4.063" height="3.831" x="25.494" y="10.129" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23640" stdDeviation=".3"/></filter><filter id="svgIDaI" width="2.322" height="3.133" x="16.526" y="15.779" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23640" stdDeviation=".25"/></filter><filter id="svgIDaT" width="4.922" height="5.795" x="10.036" y="5.06" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.490196 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDaY" width="7.407" height="8.183" x="7.426" y="3.237" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.266667 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0392157 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23640" result="effect2_innerShadow_3987_23640"/></filter><filter id="svgIDbj" width="1.258" height=".393" x="12.895" y="6.399" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.027451 0 0 0 0 0.0156863 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDbF" width="4.922" height="5.795" x="17.343" y="5.06" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.490196 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter><filter id="svgIDbK" width="7.407" height="8.183" x="16.819" y="3.237" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.266667 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0392157 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23640" result="effect2_innerShadow_3987_23640"/></filter><filter id="svgIDbV" width="1.258" height=".393" x="17.899" y="6.399" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.027451 0 0 0 0 0.0156863 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23640"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-wrestling-light" /></template>
<style>
.a0q036gjd {
  stop-color: var(--svg-color--504d4e, #504D4E);
}

.a5dbyd6tf {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
}

.af0ckx5jc {
  width: 1.258px;
  height: 0.293px;
  x: 12.895px;
  y: 6.499px;
  fill: var(--svg-color--222, #222);
  rx: 0.146px;
}

.ah1oyhzoj {
  stroke: var(--svg-color--ffbca6, #FFBCA6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.804 13.656c.38.25 1.469.722 2.781.61c1.64-.141 2.656-1.047 3.125-1.922");
}

.ak32k0b7k {
  stop-color: var(--svg-color--695d73, #695D73);
}

.al_auo8nl {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
  stop-opacity: 0;
}

.amtkixbbt {
  cx: 17.687px;
  cy: 17.345px;
  fill: var(--svg-color--e9b59d, #E9B59D);
  rx: 0.661px;
  ry: 1.066px;
}

.aps-jonfe {
  fill-rule: evenodd;
  d: path("M11.102 8.526a.25.25 0 0 1 .325.138c.1.247.285.645.511 1.038c.23.399.488.767.732.975a.25.25 0 1 1-.324.38c-.312-.266-.606-.696-.841-1.105a9.537 9.537 0 0 1-.541-1.1a.25.25 0 0 1 .138-.326Z");
}

.atnjv4bvz {
  d: path("M14.92 7.748a1.114 1.114 0 0 1-.293-.5l-.198.004l.021 1.242c.24.147.579.118.676-.11c.083-.196.014-.437-.205-.636Z");
}

.atu01ibbw {
  d: path("M21.353 10.782a2.697 2.697 0 0 1 3.821-.08l3.234 3.126l.045.034c.067.064.13.131.188.2l.43.43c.373.326 1.069 1.252.66 2.844a62.491 62.491 0 0 1-.938 3.24a.047.047 0 0 1-.02.026a.052.052 0 0 1-.027.008h-3.025a.05.05 0 0 1-.05-.055c.075-.715.268-1.758.268-1.758l-.876-.735a2.72 2.72 0 0 1-.38-.308l-3.261-3.178a2.696 2.696 0 0 1-.069-3.794Z");
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.b_oylolin {
  fill: var(--svg-color--f3b497, #F3B497);
  d: path("m16.074 11.801l.536-.516c.123-.11.461-.332.824-.332h.988a.476.476 0 1 1 0 .954h-.866a.224.224 0 0 0-.202.128l-.033.07a.344.344 0 0 0-.002.287l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.056-3.902 2.23c-2.386.056-3.712-1.183-4.258-1.692a9.14 9.14 0 0 0-.108-.1l-.103-.092a1.15 1.15 0 1 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.047.11.099.17.154c.497.454 1.236 1.132 2.533 1.132c.391 0 .884-.014 1.408-.337c.51-.314.937-.699 1.167-.95a.662.662 0 0 1 .124-.108Z");
}

.b5skg8e-v {
  stop-color: var(--svg-color--522470, #522470);
}

.b82uibb_j {
  fill: var(--svg-color--efbda9, #EFBDA9);
  d: path("M16.086 15.603a.384.384 0 1 0 0 .768h.518a.065.065 0 0 1 0 .13h1.158v-.13h.254l-.31-.309a1.568 1.568 0 0 0-1.108-.46h-.512Z");
}

.bda-r-b4i {
  d: path("M7.145 20.475L6.063 19.47l-1.149-1.023l3.133-1.907a77.83 77.83 0 0 0 1.4 1.66a.05.05 0 0 1-.003.068l-2.23 2.207a.05.05 0 0 1-.07.001Z");
}

.bhu6lxb-s {
  stop-color: var(--svg-color--d7918f, #D7918F);
  stop-opacity: 0;
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.bnc6nbb7m {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M13.305 9.095c0-.069.056-.124.124-.124h.607a.124.124 0 1 1 0 .248h-.607a.124.124 0 0 1-.124-.124Z");
}

.bv_xr1btk {
  fill: var(--svg-color--ebb69c, #EBB69C);
  fill-rule: evenodd;
  d: path("M23.727 11.775c.627.168 1 .811.833 1.438c-.25.938-.826 1.86-1.893 3.009c-1.075 1.157-2.67 2.248-4.615 2.413a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.833Z");
}

.bvxqh0kmv {
  stop-color: var(--svg-color--fdc8b1, #FDC8B1);
  stop-opacity: 0;
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.c18adox7s {
  stop-color: var(--svg-color--dfa494, #DFA494);
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
}

.cj62lbcet {
  stop-color: var(--svg-color--fdc8b1, #FDC8B1);
}

.como7ddxy {
  cx: 10.996px;
  cy: 7.836px;
  r: 1.281px;
}

.ct6_m01bp {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
}

.ctuud_14h {
  stop-color: var(--svg-color--534b49, #534B49);
  stop-opacity: 0;
}

.d52l18b6g {
  stop-color: var(--svg-color--b57889, #B57889);
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.dm4voe-la {
  d: path("M0 0h2.371v3.351H0z");
}

.dt2tox52b {
  cx: 18.138px;
  cy: 7.189px;
  rx: 0.071px;
  ry: 0.097px;
}

.dw97hraqr {
  stop-color: var(--svg-color--f6bcac, #F6BCAC);
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxnns8bwz {
  d: path("M17.396 6.688c.057-.884.351-1.305.488-1.428l4.122.07l.01 3.495c-.997 2.327-3.92 2.378-4.342 1.523c-.421-.855-.345-2.636-.278-3.66Z");
}

.dzb306qaf {
  fill: var(--svg-color--fec6b0, #FEC6B0);
  fill-rule: evenodd;
  d: path("M15.127 18.28a.4.4 0 0 1-.188.534l-.996.477a.4.4 0 0 1-.346-.722l.996-.476a.4.4 0 0 1 .534.188Z");
}

.e-5d1q48i {
  d: path("m11.71 8.353l-.247-1.586a.803.803 0 0 0 .247 1.586Z");
}

.e0b0fkm9f {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m29.081 25.638l.66 2.621a.25.25 0 0 1-.242.312h-4.441c-.102 0-.196-.06-.22-.16c-.127-.503.196-.865.763-1.156a86.214 86.214 0 0 0 1.696-.901l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075Z");
}

.e4hz009dr {
  d: path("m22.156 26.5l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.262-.441.564-.438.802c.003.155.143.273.298.273h3.964a.25.25 0 0 0 .25-.25V26.5Z");
}

.eb9tfl2op {
  fill: var(--svg-color--efbda9, #EFBDA9);
  d: path("M15.464 16.89a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.ec6bpst3z {
  stroke: var(--svg-color--ffd4ba, #FFD4BA);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.66 12.461c.073 1.375 2.032 4.875 4.235 6.14");
}

.ed8my-b7w {
  stop-color: var(--svg-color--e5aea6, #E5AEA6);
  stop-opacity: 0;
}

.edi_s6uxc {
  d: path("M17.131 7.748c.175-.159.269-.4.293-.5l.199.004l-.021 1.242c-.24.147-.58.118-.676-.11c-.083-.196-.014-.437.205-.636Z");
}

.ejoi2zbrf {
  fill: var(--svg-color--bb7263, #BB7263);
  d: path("m16.47 11.629l-.59.57l.297 1.114l1.425-.505l-.08-.117a.316.316 0 0 1-.023-.31l.03-.065a.205.205 0 0 1 .185-.118h.42a.437.437 0 1 0 0-.874h-.907c-.333 0-.643.203-.756.305Z");
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

.exu2vfb4p {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.219px;
  rx: 1.732px;
}

.f1bhxmb2c {
  d: path("m2.919 25.654l-.66 2.621a.25.25 0 0 0 .242.311h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.865-.763-1.157a86.812 86.812 0 0 1-1.696-.9l.376-.718a.05.05 0 0 0-.044-.074h-2.02a.1.1 0 0 0-.096.076Z");
}

.f543rsa1t {
  d: path("M16.086 15.603a.384.384 0 1 0 0 .768h.518a.065.065 0 0 1 0 .13h1.158v-.13h.254l-.31-.309a1.568 1.568 0 0 0-1.108-.46h-.512Z");
}

.f58ia5y4u {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M18.747 9.095a.124.124 0 0 0-.124-.124h-.608a.124.124 0 1 0 0 .248h.608a.124.124 0 0 0 .124-.124Z");
}

.f5vfl_b6x {
  d: path("M25.174 10.703a2.696 2.696 0 0 0-3.752 3.873l3.261 3.178a2.71 2.71 0 1 0 3.77-3.892l-3.28-3.16Z");
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

.flj8nzo2q {
  d: path("m20.358 8.273l.218-1.574a.794.794 0 0 1-.218 1.574Z");
}

.frolqqh9d {
  d: path("M15.464 16.89a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.ft5dv1b6b {
  fill: none;
}

.fznb35_mw {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m9.844 26.515l-.088-.89a.05.05 0 0 1 .05-.054h1.988a.05.05 0 0 1 .05.05v.766c.559.262 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.156-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.g44e0lb3a {
  fill: var(--svg-color--8261c4, #8261C4);
  d: path("M6.826 10.718a2.696 2.696 0 0 1 3.753 3.874l-3.262 3.177a2.71 2.71 0 1 1-3.77-3.891l3.28-3.16Z");
}

.g65f0ubpf {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m22.156 26.5l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.262-.441.564-.438.802c.003.155.143.273.298.273h3.964a.25.25 0 0 0 .25-.25V26.5Z");
}

.g897u4bcy {
  fill: var(--svg-color--f1bead, #F1BEAD);
  fill-rule: evenodd;
  d: path("M13.025 19.803a.4.4 0 0 1 .56-.086l.746.547a.4.4 0 1 1-.473.645l-.746-.547a.4.4 0 0 1-.087-.559Z");
}

.gamjl0bim {
  fill-rule: evenodd;
  d: path("M8.23 11.515a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.544a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

.gejkf9n9i {
  d: path("m22.828 22.11l2.039-1.805l-2.156-2.188a68.991 68.991 0 0 1-1.903 2.278c-.67.77-.758 1.77-.738 2.262l.102 2.898h2.023c.068-.734.211-2.308.242-2.727a.954.954 0 0 1 .39-.718Z");
}

.gfdvmwbxq {
  stop-color: var(--svg-color--4c2c8f, #4C2C8F);
  stop-opacity: 0;
}

.gg2ehgbth {
  width: 3.464px;
  height: 4.574px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.gl6qqfkzm {
  stop-color: var(--svg-color--6f529a, #6F529A);
}

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
}

.guac_1e6k {
  d: path("M18.33 7.551a.698.698 0 0 0 .005-.079c0-.203-.086-.367-.192-.367c-.106 0-.192.164-.192.367c0 .027.002.054.004.08h.376Z");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h3cxb-1sg {
  stop-color: var(--svg-color--d29795, #D29795);
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.ha9q0mbrk {
  stop-color: var(--svg-color--d2a990, #D2A990);
  stop-opacity: 0;
}

.hh9ibwbje {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
  stop-opacity: 0;
}

.hm962tptp {
  d: path("m20.374 8.281l.218-1.574a.795.795 0 0 1-.218 1.574Z");
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

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.idymw2beg {
  fill: var(--svg-color--8261c5, #8261C5);
  d: path("m2.928 14.508l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.758a.05.05 0 0 1-.05.054H3.255a.05.05 0 0 1-.047-.034a63.154 63.154 0 0 1-.938-3.24c-.409-1.591.287-2.517.66-2.843Z");
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.if5szbclz {
  d: path("m9.172 22.125l-2.039-1.804l2.156-2.188a68.14 68.14 0 0 0 1.903 2.277c.67.77.758 1.77.738 2.262l-.102 2.899H9.805a295.62 295.62 0 0 1-.242-2.727a.954.954 0 0 0-.39-.719Z");
}

.iitldjupn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M24.02 12.008c-.26 1.313-1.738 4.244-5.563 5.469");
}

.issi09x9i {
  d: path("M13.66 7.581a.703.703 0 0 1-.007-.08c-.003-.204.08-.371.188-.373c.107-.002.196.162.2.367c0 .027 0 .054-.003.08l-.379.006Z");
}

.j2u72qbdb {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
}

.j3zvk_bdt {
  stop-color: var(--svg-color--633ea0, #633EA0);
}

.jf8rttb1k {
  stop-color: var(--svg-color--d2a990, #D2A990);
}

.jlfuqjzvr {
  fill: var(--svg-color--241823, #241823);
  d: path("M17.289 5.199c-.182-.457.034-.932.143-1.094c.418-.735 1.26-.77 1.74-.549c.566.26.733.396 1.66.15c.927-.248 2.063-.108 2.64.972c.578 1.08-.09 2.272.046 2.93c.135.659.553.73.695 1.492c.112 1.055-.551 1.73-1.132 1.875c-.58.146-1.769-.03-2.14-1.002c-.609-1.592-.164-2.333-.289-3.13c-.124-.795-.595-1.028-1.46-.87c-1.02.186-1.66-.167-1.903-.774Z");
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jqlzdbc0v {
  stop-color: var(--svg-color--d38f7d, #D38F7D);
}

.jtr87tg1h {
  fill-rule: evenodd;
  d: path("M13.373 18.45a.4.4 0 0 1 .55-.136c.404.245.859.47 1.375.648a.4.4 0 1 1-.26.756a7.88 7.88 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549Z");
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

.k6dy1v0mq {
  d: path("M15.503 17.517c0-.215.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.k78l4l0qb {
  stop-color: var(--svg-color--633ea0, #633EA0);
  stop-opacity: 0;
}

.k8s01tfdv {
  stop-color: var(--svg-color--5e5663, #5E5663);
  stop-opacity: 0;
}

.kc3xlwepk {
  stop-color: var(--svg-color--cd8a81, #CD8A81);
}

.kgukkhbth {
  stop-color: var(--svg-color--5e5663, #5E5663);
}

.kj8vq-bmb {
  d: path("m29.081 25.638l.66 2.621a.25.25 0 0 1-.242.312h-4.441c-.102 0-.196-.06-.22-.16c-.127-.503.196-.865.763-1.156a86.214 86.214 0 0 0 1.696-.901l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075Z");
}

.kjqpljl_q {
  stop-color: var(--svg-color--e6b19b, #E6B19B);
}

.kjrf-wbwh {
  fill: var(--svg-color--241823, #241823);
  d: path("M14.763 5.199c.182-.457-.034-.932-.144-1.094c-.418-.735-1.259-.77-1.74-.549c-.565.26-.732.396-1.658.15c-.929-.248-2.065-.108-2.642.972s.09 2.272-.045 2.93c-.136.659-.553.73-.695 1.492c-.112 1.055.551 1.73 1.132 1.875c.58.146 1.768-.03 2.14-1.002c.609-1.592.164-2.333.289-3.13c.124-.795.595-1.028 1.46-.87c1.02.186 1.66-.167 1.903-.774Z");
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.kr4hkszwv {
  d: path("M14.763 5.199c.182-.457-.034-.932-.144-1.094c-.418-.735-1.259-.77-1.74-.549c-.565.26-.732.396-1.658.15c-.929-.248-2.065-.108-2.642.972s.09 2.272-.045 2.93c-.136.659-.553.73-.695 1.492c-.112 1.055.551 1.73 1.132 1.875c.58.146 1.768-.03 2.14-1.002c.609-1.592.164-2.333.289-3.13c.124-.795.595-1.028 1.46-.87c1.02.186 1.66-.167 1.903-.774Z");
}

.ktitqk87w {
  d: path("m11.678 8.272l-.218-1.574a.795.795 0 0 0 .218 1.574Z");
}

.kuufpibxl {
  stop-color: var(--svg-color--8362c5, #8362C5);
  stop-opacity: 0;
}

.kwnu21bnt {
  d: path("m9.844 26.515l-.088-.89a.05.05 0 0 1 .05-.054h1.988a.05.05 0 0 1 .05.05v.766c.559.262 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.156-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.l-yj001re {
  d: path("M14.656 6.688c-.058-.884-.351-1.305-.488-1.428l-4.122.07l-.01 3.495c.997 2.327 3.92 2.378 4.341 1.523c.422-.855.346-2.636.28-3.66Z");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l5_7ncbeh {
  d: path("m2.928 14.508l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.758a.05.05 0 0 1-.05.054H3.255a.05.05 0 0 1-.047-.034a63.154 63.154 0 0 1-.938-3.24c-.409-1.591.287-2.517.66-2.843Z");
}

.l6veklvwf {
  stop-color: var(--svg-color--9e94a2, #9E94A2);
}

.l7fhg9boh {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.17 7.551h-1.081c0-.428.242-.775.54-.775c.298 0 .54.347.54.775Z");
}

.l7mbhnbzh {
  stop-color: var(--svg-color--eeb298, #EEB298);
}

.lc3kphb9y {
  d: path("m16.074 11.801l.536-.516c.123-.11.461-.332.824-.332h.988a.476.476 0 1 1 0 .954h-.866a.224.224 0 0 0-.202.128l-.033.07a.344.344 0 0 0-.002.287l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.056-3.902 2.23c-2.386.056-3.712-1.183-4.258-1.692a9.14 9.14 0 0 0-.108-.1l-.103-.092a1.15 1.15 0 1 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.047.11.099.17.154c.497.454 1.236 1.132 2.533 1.132c.391 0 .884-.014 1.408-.337c.51-.314.937-.699 1.167-.95a.662.662 0 0 1 .124-.108Z");
}

.llfrtjbtl {
  d: path("M13.507 7.551v-.004c0-.35.15-.634.335-.634c.185 0 .335.284.335.634v.004h-.67Z");
}

.lsajvobnn {
  stop-color: var(--svg-color--d38f7d, #D38F7D);
  stop-opacity: 0;
}

.lx4g3m1rx {
  d: path("m20.342 8.353l.247-1.586a.803.803 0 0 1-.247 1.586Z");
}

.ly3i0vbsp {
  stop-color: var(--svg-color--d29795, #D29795);
  stop-opacity: 0;
}

.m0ovwfbvo {
  fill-rule: evenodd;
  d: path("M20.95 8.526a.25.25 0 0 0-.325.138a9.05 9.05 0 0 1-.511 1.038c-.23.399-.489.767-.733.975a.25.25 0 1 0 .325.38c.312-.266.605-.696.841-1.105c.239-.415.433-.834.54-1.1a.25.25 0 0 0-.137-.326Z");
}

.mfirrnbby {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.219px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
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

.n36-u1vxv {
  d: path("M18.393 7.581a.68.68 0 0 0 .005-.08c.004-.204-.08-.371-.187-.373c-.107-.002-.196.162-.2.367c0 .027 0 .054.003.08l.379.006Z");
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

.nsjv5mb4g {
  fill-rule: evenodd;
  d: path("M13.025 19.803a.4.4 0 0 1 .56-.086l.746.547a.4.4 0 1 1-.473.645l-.746-.547a.4.4 0 0 1-.087-.559Z");
}

.ntik_nbhi {
  d: path("M11.844 26.376v-.755a.05.05 0 0 0-.05-.05H9.805a.05.05 0 0 0-.05.054l.089.89v.02l2-.159Z");
}

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
}

.o22_o0bcf {
  stop-color: var(--svg-color--4c2c8f, #4C2C8F);
}

.o410gcc4i {
  stop-color: var(--svg-color--ecb596, #ECB596);
  stop-opacity: 0;
}

.ocru65npv {
  stop-color: var(--svg-color--3f3646, #3F3646);
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

.oxsco296q {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.11 7.574l-1.09.019c-.008-.432.23-.787.532-.792c.301-.005.551.341.559.773Z");
}

.oybn7vbqt {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
}

.pb8433y7i {
  stop-color: var(--svg-color--be716e, #BE716E);
}

.pjqt20gbi {
  d: path("m20.374 8.272l.218-1.574a.795.795 0 0 1-.218 1.574Z");
}

.ppcls7ioo {
  fill-rule: evenodd;
  d: path("M13.393 19.288a.45.45 0 0 1 .624-.122l.973.657a.45.45 0 0 1-.503.746l-.973-.657a.45.45 0 0 1-.121-.624Z");
}

.ps4x5-m-h {
  stop-color: var(--svg-color--f7c8ae, #F7C8AE);
}

.pxj138bcc {
  width: 3.464px;
  height: 4.574px;
  rx: 1.732px;
}

.pxjxg6ezh {
  stop-color: var(--svg-color--dea69d, #DEA69D);
}

.py9zg4b1k {
  d: path("m11.678 8.281l-.218-1.574a.795.795 0 0 0 .218 1.574Z");
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

.q5_1ldb2m {
  d: path("M13.721 7.551a.676.676 0 0 1-.005-.079c0-.203.087-.367.193-.367c.106 0 .192.164.192.367a.699.699 0 0 1-.005.08h-.375Z");
}

.q8o5hvb9j {
  d: path("M15.846 18.255c0-.213.173-.385.386-.385h1.385l.308.77H16.23a.385.385 0 0 1-.385-.385Z");
}

.qabi1jb_x {
  fill-rule: evenodd;
  d: path("M12.178 3.77a.25.25 0 0 1 .162.314l-.95 2.969a.25.25 0 0 1-.476-.152l.95-2.969a.25.25 0 0 1 .314-.162Z");
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

.qkyy4yb4k {
  fill: var(--svg-color--8261c5, #8261C5);
  d: path("M25.174 10.703a2.696 2.696 0 0 0-3.752 3.873l3.261 3.178a2.71 2.71 0 1 0 3.77-3.892l-3.28-3.16Z");
}

.qn4r5dznz {
  stop-color: var(--svg-color--774f8d, #774F8D);
  stop-opacity: 0;
}

.qpxjwkb-f {
  stop-color: var(--svg-color--774f8d, #774F8D);
}

.qy_j5083o {
  stop-color: var(--svg-color--c2848e, #C2848E);
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.r7-2aybwm {
  stop-color: var(--svg-color--653d99, #653D99);
}

.rczunoa_v {
  stop-color: var(--svg-color--f2c1b1, #F2C1B1);
  stop-opacity: 0;
}

.rdgulqvms {
  stop-color: var(--svg-color--e1a38b, #E1A38B);
  stop-opacity: 0;
}

.rknzqr02l {
  stop-color: var(--svg-color--695d73, #695D73);
  stop-opacity: 0;
}

.ro_82sbvp {
  fill-rule: evenodd;
  d: path("M19.874 3.77a.25.25 0 0 0-.162.314l.949 2.969a.25.25 0 1 0 .476-.152l-.949-2.969a.25.25 0 0 0-.314-.162Z");
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.rpz882bvf {
  fill: var(--svg-color--baa4c5, #BAA4C5);
  d: path("m4.703 26.37l.376-.718a.05.05 0 0 0-.044-.074h-2.02a.1.1 0 0 0-.096.076l-.22.874l2.004-.159Z");
}

.ru37_nz_z {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M12.992 7.029c.142-.147.382-.185.484-.185l-.325.521c-.163-.006-.337-.152-.16-.336Z");
}

.ruvtttgun {
  fill: var(--svg-color--9d91a7, #9D91A7);
  d: path("m27.297 26.354l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075l.22.874l-2.004-.158Z");
}

.rymggjbfw {
  stop-color: var(--svg-color--eab6aa, #EAB6AA);
}

.rz8a4x2ve {
  fill: var(--svg-color--f4bcaf, #F4BCAF);
  d: path("m28.11 22.266l.57-1.727l-2.876-.39c-.013.093-.071.51-.203 1.43c-.13.918.125 1.663.375 2.203l1.22 2.171h1.866c-.245-.77-.844-2.77-.93-3.03c-.085-.263-.085-.481-.023-.657Z");
}

.s4-7dmb-e {
  fill: var(--svg-color--efbda9, #EFBDA9);
  d: path("M15.503 17.517c0-.215.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.sbd7u9opr {
  stop-color: var(--svg-color--dea7a3, #DEA7A3);
  stop-opacity: 0;
}

.se3x0fpgw {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.941 7.574l1.091.019c.008-.432-.23-.787-.532-.792c-.301-.005-.552.341-.559.773Z");
}

.sf5518bjn {
  stop-color: var(--svg-color--744fbd, #744FBD);
}

.sg_mzvbjo {
  d: path("M13.442 7.586v-.004c-.006-.354.141-.644.328-.647c.187-.003.344.281.35.635v.004l-.678.012Z");
}

.shic-ydjf {
  stop-color: var(--svg-color--2e2d2f, #2E2D2F);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t7-mpru2g {
  fill: var(--svg-color--8261c5, #8261C5);
  d: path("m29.072 14.492l-.664-.664l-3.68 3.954l1.21 1.015s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.055h3.025a.05.05 0 0 0 .047-.035c.16-.505.565-1.792.938-3.239c.409-1.592-.287-2.518-.66-2.844Z");
}

.t70trsbww {
  fill-rule: evenodd;
  d: path("M13.609 18.98a.4.4 0 0 1 .547-.141l1.215.715a.4.4 0 1 1-.405.69l-1.215-.715a.4.4 0 0 1-.142-.548Z");
}

.t77q9um-l {
  stop-color: var(--svg-color--744fbd, #744FBD);
  stop-opacity: 0;
}

.t7ng9kbhh {
  fill: var(--svg-color--fbc4a8, #FBC4A8);
  fill-rule: evenodd;
  d: path("M8.23 11.515a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.544a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

.thjbg0b5a {
  stop-color: var(--svg-color--d98783, #D98783);
  stop-opacity: 0;
}

.tujlabu3w {
  stop-color: var(--svg-color--eea79d, #EEA79D);
}

.tw_a5_m2v {
  d: path("M11.694 8.273L11.475 6.7a.795.795 0 0 0 .219 1.574Z");
}

.tzf255bgc {
  stop-color: var(--svg-color--534b49, #534B49);
}

.u0u3fxb4v {
  d: path("m11.674 8.286l-.218-1.576a.796.796 0 0 0 .218 1.576Z");
}

.u1vg6cbkb {
  d: path("M19.316 9.24h2.371v3.351h-2.371z");
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.u9kl9xb7o {
  d: path("M17.289 5.199c-.182-.457.034-.932.143-1.094c.418-.735 1.26-.77 1.74-.549c.566.26.733.396 1.66.15c.927-.248 2.063-.108 2.64.972c.578 1.08-.09 2.272.046 2.93c.135.659.553.73.695 1.492c.112 1.055-.551 1.73-1.132 1.875c-.58.146-1.769-.03-2.14-1.002c-.609-1.592-.164-2.333-.289-3.13c-.124-.795-.595-1.028-1.46-.87c-1.02.186-1.66-.167-1.903-.774Z");
}

.uam_jdzuf {
  stop-color: var(--svg-color--f2c1b1, #F2C1B1);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ud8eo6bjs {
  cx: 18.073px;
  cy: 7.166px;
  rx: 0.07px;
  ry: 0.096px;
}

.udytdoxml {
  stop-color: var(--svg-color--fbcab4, #FBCAB4);
  stop-opacity: 0;
}

.ue5h9-fhx {
  fill-rule: evenodd;
  d: path("M23.727 11.775c.627.168 1 .811.833 1.438c-.25.938-.826 1.86-1.893 3.009c-1.075 1.157-2.67 2.248-4.615 2.413a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.833Z");
}

.ur4alabfa {
  d: path("m29.072 14.492l-.664-.664l-3.68 3.954l1.21 1.015s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.055h3.025a.05.05 0 0 0 .047-.035c.16-.505.565-1.792.938-3.239c.409-1.592-.287-2.518-.66-2.844Z");
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

.vdgfppb6q {
  fill: var(--svg-color--efbda9, #EFBDA9);
  d: path("M15.846 18.255c0-.213.173-.385.386-.385h1.385l.308.77H16.23a.385.385 0 0 1-.385-.385Z");
}

.vizjbkbik {
  d: path("m24.855 20.46l1.082-1.007l1.149-1.023l-3.133-1.906a78.474 78.474 0 0 1-1.4 1.66a.05.05 0 0 0 .003.068l2.23 2.207a.05.05 0 0 0 .07 0Z");
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vnpn-sbga {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.883 7.551h1.08c0-.428-.242-.775-.54-.775c-.299 0-.54.347-.54.775Z");
}

.vzt-qqbid {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m2.919 25.654l-.66 2.621a.25.25 0 0 0 .242.311h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.865-.763-1.157a86.812 86.812 0 0 1-1.696-.9l.376-.718a.05.05 0 0 0-.044-.074h-2.02a.1.1 0 0 0-.096.076Z");
}

.w3nxk5b5c {
  d: path("M26.406 10.73a.3.3 0 0 0-.024.599l.024-.6Zm1.29.353l.013-.3l-.012.3Zm.899 1.342l.282.103l-.282-.103Zm-.514.532a.3.3 0 0 0 .563.207l-.563-.207Zm-1.7-1.628l1.303.053l.025-.6l-1.303-.053l-.024.6Zm1.932.993l-.232.636l.563.206l.233-.636l-.564-.206Zm-.629-.94a.7.7 0 0 1 .63.94l.563.207a1.3 1.3 0 0 0-1.168-1.746l-.025.6Z");
}

.w4s8s2bsv {
  fill: var(--svg-color--f4bcaf, #F4BCAF);
  d: path("m3.913 22.266l-.57-1.727l2.875-.39l.203 1.43c.131.918-.125 1.663-.375 2.203l-1.219 2.171H2.96c.245-.77.844-2.77.93-3.03c.086-.263.086-.481.023-.657Z");
}

.wf-ixsb0z {
  d: path("M20.156 26.36v-.755a.05.05 0 0 1 .05-.05h1.989a.05.05 0 0 1 .05.055l-.089.89v.02l-2-.16Z");
}

.wf9v9bcjq {
  stop-color: var(--svg-color--ffc9b0, #FFC9B0);
}

.wp2ykebsl {
  stop-color: var(--svg-color--d59c86, #D59C86);
  stop-opacity: 0;
}

.wxd-omf2a {
  width: 0.764px;
  height: 1.4px;
  x: 17.093px;
  y: 15.893px;
  fill: var(--svg-color--f1bca2, #F1BCA2);
  rx: 0.382px;
}

.x_hb57blb {
  d: path("M10.647 10.798a2.697 2.697 0 0 0-3.821-.08l-3.234 3.126l-.045.034c-.067.064-.13.13-.188.2l-.43.43c-.373.326-1.069 1.252-.66 2.844c.372 1.447.778 2.733.938 3.239a.048.048 0 0 0 .047.034h3.025a.05.05 0 0 0 .05-.054c-.074-.715-.268-1.758-.268-1.758l.876-.735c.133-.09.26-.192.38-.309l3.261-3.177a2.696 2.696 0 0 0 .069-3.794Z");
}

.xbnmohbay {
  fill: var(--svg-color--fbc5a9, #FBC5A9);
  fill-rule: evenodd;
  d: path("M13.393 19.288a.45.45 0 0 1 .624-.122l.973.657a.45.45 0 0 1-.503.746l-.973-.657a.45.45 0 0 1-.121-.624Z");
}

.xoi0djbjo {
  stop-color: var(--svg-color--5f4099, #5F4099);
}

.xrb79z_7h {
  stop-color: var(--svg-color--fdccb4, #FDCCB4);
}

.xzfl_qbeq {
  stop-color: var(--svg-color--c88c92, #C88C92);
}

.y1knbmbwz {
  fill: var(--svg-color--fbc5a9, #FBC5A9);
  fill-rule: evenodd;
  d: path("M13.609 18.98a.4.4 0 0 1 .547-.141l1.215.715a.4.4 0 1 1-.405.69l-1.215-.715a.4.4 0 0 1-.142-.548Z");
}

.y4pe4ezsu {
  stop-color: var(--svg-color--271e2e, #271E2E);
}

.y527_ubzz {
  d: path("M18.61 7.586v-.004c.006-.354-.141-.644-.328-.647c-.187-.003-.344.281-.35.635v.004l.677.012Z");
}

.y7_fahboe {
  rx: 0.071px;
  ry: 0.097px;
}

.yfv3nqb2s {
  stop-color: var(--svg-color--e4a88b, #E4A88B);
  stop-opacity: 0;
}

.yh639zbgi {
  fill: var(--svg-color--fbc5a9, #FBC5A9);
  fill-rule: evenodd;
  d: path("M13.373 18.45a.4.4 0 0 1 .55-.136c.404.245.859.47 1.375.648a.4.4 0 1 1-.26.756a7.88 7.88 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549Z");
}

.ysccakbur {
  fill-rule: evenodd;
  d: path("M27.133 12.49a.1.1 0 0 0-.09-.14l-3.873-.058l.035-2.34l4.25.06c1.653.025 2.653 1.726 1.919 3.234l-1.186 2.545l-2.062-1.02l1.007-2.281Z");
}

.ysxro3bqi {
  stop-color: var(--svg-color--d8968e, #D8968E);
  stop-opacity: 0;
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.zfb2yrbdn {
  stop-color: var(--svg-color--c2848e, #C2848E);
  stop-opacity: 0;
}

.zfi5gyb6q {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M19.06 7.029c-.142-.147-.382-.185-.485-.185l.326.521c.163-.006.337-.152.159-.336Z");
}

.zjmmjyoar {
  stop-color: var(--svg-color--554f5c, #554F5C);
}

.zqa2bhb_d {
  d: path("M18.545 7.551v-.004c0-.35-.15-.634-.336-.634c-.185 0-.335.284-.335.634v.004h.67Z");
}

.zsy9bdw9u {
  d: path("m20.378 8.286l.218-1.576a.796.796 0 0 1-.218 1.576Z");
}

.zu500rbyn {
  stop-color: var(--svg-color--d59c86, #D59C86);
}

</style>
