<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#svgIDa)" transform="rotate(-23.31 19.316 9.069)" class="iasq92bar"/><path fill="url(#svgIDb)" transform="scale(-1 1) rotate(-34.493 8.757 25.425)" class="dm4voe-la"/><path class="gepoezb-p"/><g filter="url(#svgIDc)"><path class="cyah9dbso"/><path fill="url(#svgIDd)" class="idjwbh6kk"/></g><g filter="url(#svgIDe)"><path class="u0yw4v3mc"/></g><path fill="url(#svgIDf)" class="mxco7gaxf"/><path fill="url(#svgIDg)" class="mxco7gaxf"/><path fill="url(#svgIDh)" class="mxco7gaxf"/><path fill="url(#svgIDi)" class="ij--3abxg"/><path fill="url(#svgIDj)" class="ij--3abxg"/><path fill="url(#svgIDk)" class="ij--3abxg"/><g filter="url(#svgIDl)"><path class="y3ldcubnb"/></g><g filter="url(#svgIDm)"><path class="a3ce-6b4m"/></g><g filter="url(#svgIDn)"><path class="wicb2kbvo"/><path fill="url(#svgIDo)" class="nrp5bhxwt"/></g><path fill="url(#svgIDp)" class="gawbh7bii"/><path fill="url(#svgIDq)" class="gawbh7bii"/><g filter="url(#svgIDr)"><path class="myma9ccll"/><path fill="url(#svgIDs)" class="f4dftzbyn"/><path fill="url(#svgIDt)" class="f4dftzbyn"/><path fill="url(#svgIDu)" class="f4dftzbyn"/></g><g filter="url(#svgIDv)"><path class="y57kfh6zq"/></g><g filter="url(#svgIDw)"><path class="ui4gszb6g"/><path fill="url(#svgIDx)" class="xfc-qx9ex"/><path fill="url(#svgIDy)" class="xfc-qx9ex"/><path fill="url(#svgIDz)" class="xfc-qx9ex"/></g><g filter="url(#svgIDA)"><path fill="url(#svgIDB)" class="kc2hp5b1b"/></g><g filter="url(#svgIDC)"><rect stroke="url(#svgIDD)" transform="rotate(45 8.633 10.047)" class="ps38e5bsm"/></g><rect fill="url(#svgIDE)" transform="rotate(45 8.633 10.047)" class="b2zb22byt"/><rect fill="url(#svgIDF)" transform="rotate(45 8.633 10.047)" class="b2zb22byt"/><g filter="url(#svgIDG)"><path clip-rule="evenodd" class="rjxx4vs3o"/></g><path clip-rule="evenodd" class="gqo2gi93k"/><path fill="url(#svgIDH)" clip-rule="evenodd" class="tp7btwbhq"/><path clip-rule="evenodd" class="dt4hg8bog"/><path fill="url(#svgIDI)" clip-rule="evenodd" class="afvxbrb6i"/><path clip-rule="evenodd" class="kadt4rbbe"/><path fill="url(#svgIDJ)" clip-rule="evenodd" class="o-9fab9od"/><path clip-rule="evenodd" class="sf9fznbjz"/><path fill="url(#svgIDK)" clip-rule="evenodd" class="hb8modbps"/><path clip-rule="evenodd" class="kvi4eqmnu"/><path fill="url(#svgIDL)" clip-rule="evenodd" class="v8d4ab1_b"/><path fill="url(#svgIDM)" clip-rule="evenodd" class="so-5pppws"/><path fill="url(#svgIDN)" clip-rule="evenodd" class="so-5pppws"/><path fill="url(#svgIDO)" clip-rule="evenodd" class="so-5pppws"/><rect transform="rotate(-28.166 17.093 15.721)" class="xs5quubmq"/><path fill="url(#svgIDP)" class="nm5hd83mo"/><path fill="url(#svgIDQ)" class="nm5hd83mo"/><path fill="url(#svgIDR)" class="nm5hd83mo"/><path fill="url(#svgIDS)" class="e4nvf0jxv"/><path fill="url(#svgIDT)" class="e4nvf0jxv"/><path fill="url(#svgIDU)" class="e4nvf0jxv"/><g filter="url(#svgIDV)"><path class="tob0y3box"/></g><g filter="url(#svgIDW)"><path class="ndir12pxa"/></g><g filter="url(#svgIDX)"><path class="nbc6eks5j"/><path fill="url(#svgIDY)" class="bsuq0y52j"/></g><path fill="url(#svgIDZ)" class="th4vgcc8j"/><path fill="url(#svgIDaa)" class="th4vgcc8j"/><g filter="url(#svgIDab)"><path class="wbqgxvibx"/><path fill="url(#svgIDac)" class="r4i2vf4ry"/><path fill="url(#svgIDad)" class="r4i2vf4ry"/><path fill="url(#svgIDae)" class="r4i2vf4ry"/></g><g filter="url(#svgIDaf)"><path class="d5mpwjb6n"/></g><g filter="url(#svgIDag)"><path class="hfo25hbkn"/><path fill="url(#svgIDah)" class="chy2-3bdx"/><path fill="url(#svgIDai)" class="chy2-3bdx"/><path fill="url(#svgIDaj)" class="chy2-3bdx"/></g><g filter="url(#svgIDak)"><path fill="url(#svgIDal)" class="gyqgpnbjt"/></g><g filter="url(#svgIDam)"><rect stroke="url(#svgIDan)" transform="scale(-1 1) rotate(45 -23.792 -23.191)" class="gg2ehgbth"/></g><rect fill="url(#svgIDao)" transform="scale(-1 1) rotate(45 -23.792 -23.191)" class="pxj138bcc"/><rect fill="url(#svgIDap)" transform="scale(-1 1) rotate(45 -23.792 -23.191)" class="pxj138bcc"/><path clip-rule="evenodd" class="ng6zjrf7b"/><path fill="url(#svgIDaq)" clip-rule="evenodd" class="pms-3nbqx"/><path class="sik08cc9l"/><path fill="url(#svgIDar)" class="u0hatmkqb"/><path class="or75t2brf"/><path fill="url(#svgIDas)" class="v203o78us"/><path class="wutgx970i"/><path fill="url(#svgIDat)" class="wr624mrxa"/><path fill="url(#svgIDau)" class="wr624mrxa"/><path class="l6m3twbxj"/><path fill="url(#svgIDav)" class="fwkra3bhz"/><g filter="url(#svgIDaw)"><path class="dnhfge9th"/></g><g filter="url(#svgIDax)"><path stroke="url(#svgIDay)" class="rh5emhbls"/></g><g filter="url(#svgIDaz)"><path fill="url(#svgIDaA)" class="sneyg9bdl"/></g><path fill="url(#svgIDaB)" class="co_arab3u"/><path fill="url(#svgIDaC)" class="co_arab3u"/><path fill="url(#svgIDaD)" class="co_arab3u"/><path fill="url(#svgIDaE)" class="c-hifvbsi"/><path fill="url(#svgIDaF)" class="c-hifvbsi"/><path fill="url(#svgIDaG)" class="c-hifvbsi"/><g filter="url(#svgIDaH)"><ellipse class="qabo_1v4b"/></g><path fill="url(#svgIDaI)" class="zsfek5b8q"/><path fill="url(#svgIDaJ)" class="zsfek5b8q"/><path fill="url(#svgIDaK)" class="zsfek5b8q"/><path fill="url(#svgIDaL)" class="ihifsjbzy"/><g filter="url(#svgIDaM)"><path fill="url(#svgIDaN)" class="euz565odm"/><path fill="url(#svgIDaO)" class="euz565odm"/><path fill="url(#svgIDaP)" class="euz565odm"/><path fill="url(#svgIDaQ)" class="euz565odm"/></g><g filter="url(#svgIDaR)"><path fill="url(#svgIDaS)" class="eyc0ghbbh"/><path fill="url(#svgIDaT)" class="eyc0ghbbh"/><path fill="url(#svgIDaU)" class="eyc0ghbbh"/></g><path fill="url(#svgIDaV)" class="dsw1fjbmj"/><path fill="url(#svgIDaW)" class="dsw1fjbmj"/><path fill="url(#svgIDaX)" class="dsw1fjbmj"/><path class="n3ys-0_iy"/><path fill="url(#svgIDaY)" class="im6n2fovl"/><path fill="url(#svgIDaZ)" class="ctpmd67aa"/><ellipse fill="url(#svgIDba)" transform="scale(-1 1) rotate(24.61 -23.307 -28.508)" class="zhbm06bnu"/><path fill="url(#svgIDbb)" clip-rule="evenodd" class="v0z-u3bkw"/><path fill="url(#svgIDbc)" clip-rule="evenodd" class="v0z-u3bkw"/><path fill="url(#svgIDbd)" clip-rule="evenodd" class="v0z-u3bkw"/><path fill="url(#svgIDbe)" clip-rule="evenodd" class="git0cmp4l"/><path fill="url(#svgIDbf)" clip-rule="evenodd" class="git0cmp4l"/><circle fill="url(#svgIDbg)" class="dxcffjstc"/><circle fill="url(#svgIDbh)" class="dxcffjstc"/><circle fill="url(#svgIDbi)" class="dxcffjstc"/><g filter="url(#svgIDbj)"><rect class="axex79n_z"/></g><path class="klgjqhl0b"/><path fill="url(#svgIDbk)" class="wirr61xwd"/><path fill="url(#svgIDbl)" class="wirr61xwd"/><path fill="url(#svgIDbm)" class="wirr61xwd"/><path fill="url(#svgIDbn)" class="mmwkogbxc"/><path fill="url(#svgIDbo)" class="mmwkogbxc"/><path fill="url(#svgIDbp)" class="mmwkogbxc"/><path fill="url(#svgIDbq)" class="h-vfp3yri"/><path fill="url(#svgIDbr)" class="h-vfp3yri"/><path fill="url(#svgIDbs)" class="h-vfp3yri"/><path fill="url(#svgIDbt)" class="nphgd6nhc"/><g filter="url(#svgIDbu)"><path fill="url(#svgIDbv)" class="v2vw7kyua"/><path fill="url(#svgIDbw)" class="v2vw7kyua"/><path fill="url(#svgIDbx)" class="v2vw7kyua"/><path fill="url(#svgIDby)" class="v2vw7kyua"/></g><g filter="url(#svgIDbz)"><path fill="url(#svgIDbA)" class="iwql0cvaa"/><path fill="url(#svgIDbB)" class="iwql0cvaa"/><path fill="url(#svgIDbC)" class="iwql0cvaa"/></g><path fill="url(#svgIDbD)" class="ftl_v55qt"/><path fill="url(#svgIDbE)" class="ftl_v55qt"/><path fill="url(#svgIDbF)" class="ftl_v55qt"/><path class="tazxosblz"/><path fill="url(#svgIDbG)" class="k4zv8rbbo"/><path fill="url(#svgIDbH)" class="puldk8xku"/><ellipse fill="url(#svgIDbI)" transform="rotate(24.61 18.402 7.323)" class="av2_52fbu"/><path fill="url(#svgIDbJ)" clip-rule="evenodd" class="a27ei3rio"/><path fill="url(#svgIDbK)" clip-rule="evenodd" class="a27ei3rio"/><path fill="url(#svgIDbL)" clip-rule="evenodd" class="a27ei3rio"/><path fill="url(#svgIDbM)" clip-rule="evenodd" class="r8n5q7b5r"/><path fill="url(#svgIDbN)" clip-rule="evenodd" class="r8n5q7b5r"/><circle fill="url(#svgIDbO)" transform="matrix(-1 0 0 1 21.395 7.87)" class="ms4f1oj7g"/><circle fill="url(#svgIDbP)" transform="matrix(-1 0 0 1 21.395 7.87)" class="ms4f1oj7g"/><circle fill="url(#svgIDbQ)" transform="matrix(-1 0 0 1 21.395 7.87)" class="ms4f1oj7g"/><g filter="url(#svgIDbR)"><rect transform="matrix(-1 0 0 1 19.442 6.62)" class="biugcq6id"/></g><path class="c31p4-hcd"/><defs><radialGradient id="svgIDa" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 19.282 10.52)" gradientUnits="userSpaceOnUse"><stop class="u2n90vbun"/><stop offset="1" class="q1txceb2f"/></radialGradient><radialGradient id="svgIDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 -.033 1.45)" gradientUnits="userSpaceOnUse"><stop class="p5wg8876f"/><stop offset=".919" class="hy8b1ubxg"/></radialGradient><radialGradient id="svgIDd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71095 2.35327 -5.20382 -5.99476 18.899 10.781)" gradientUnits="userSpaceOnUse"><stop class="qy3mcrgdk"/><stop offset="1" class="gy1xmobvy"/></radialGradient><radialGradient id="svgIDf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 11.656 25.398)" gradientUnits="userSpaceOnUse"><stop class="uq4h3zxiv"/><stop offset="1" class="l3r47ffcx"/></radialGradient><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(2.14185 1.875 -.94292 1.07712 7.39 20.367)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="sgqr937ow"/><stop offset="1" class="icb-xabyb"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(144.26 2.26 11.022) scale(1.23051 3.4979)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="ammexac5i"/><stop offset="1" class="kik7_ob9t"/></radialGradient><radialGradient id="svgIDo" cx="0" cy="0" r="1" gradientTransform="rotate(-134.195 7.064 8.004) scale(2.212 .64075)" gradientUnits="userSpaceOnUse"><stop class="hwnq5ubzm"/><stop offset="1" class="y9oqcminv"/></radialGradient><radialGradient id="svgIDp" cx="0" cy="0" r="1" gradientTransform="rotate(128.536 .685 10.203) scale(4.51441 1.8822)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="rlrqah7ok"/><stop offset="1" class="r-6du_zhr"/></radialGradient><radialGradient id="svgIDq" cx="0" cy="0" r="1" gradientTransform="matrix(6.96877 -7.18752 5.67939 5.50654 3.781 17.68)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="i1avtge0l"/><stop offset="1" class="ifp1_xbmc"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="rotate(-144.397 8.157 13.053) scale(2.17397 2.91043)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64636 -1.26563 1.72963 -2.24994 14.356 28.406)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 11.203 26.227)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="matrix(-.05524 1.73462 -1.20171 -.03827 10.37 11.325)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="bs9ct9blb"/><stop offset="1" class="uj_nqubgh"/></radialGradient><radialGradient id="svgIDF" cx="0" cy="0" r="1" gradientTransform="rotate(45 -10.286 20.079) scale(2.38098 1.16175)" gradientUnits="userSpaceOnUse"><stop class="cz--1m5fh"/><stop offset="1" class="b8hyhqehi"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="rotate(137.121 3.046 10.155) scale(3.58218 11.0839)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="wg-u6yb-o"/><stop offset="1" class="yic7b8bke"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="matrix(-.24218 1.08594 -3.51562 -.78403 14.395 18.432)" gradientUnits="userSpaceOnUse"><stop offset=".472" class="li5uyl08u"/><stop offset="1" class="m1j2mbbtp"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.30444 .89737 -2.62413 -.89026 14.56 19.08)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="li5uyl08u"/><stop offset="1" class="m1j2mbbtp"/></radialGradient><radialGradient id="svgIDK" cx="0" cy="0" r="1" gradientTransform="matrix(-.28295 .92188 -2.48547 -.76287 14.252 19.398)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="li5uyl08u"/><stop offset="1" class="m1j2mbbtp"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37499 1.625 -1.79466 -1.51854 29.313 10.492)" gradientUnits="userSpaceOnUse"><stop class="gjr9r-itc"/><stop offset="1" class="pafpa8b3r"/></radialGradient><radialGradient id="svgIDN" cx="0" cy="0" r="1" gradientTransform="matrix(2.12183 -1.33219 1.13322 1.80492 26.394 12.7)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="n7l1hg2af"/><stop offset="1" class="fd4bh7bhc"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 20.343 25.383)" gradientUnits="userSpaceOnUse"><stop class="uq4h3zxiv"/><stop offset="1" class="l3r47ffcx"/></radialGradient><radialGradient id="svgIDQ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14186 1.87499 -.94291 -1.07712 24.61 20.352)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="sgqr937ow"/><stop offset="1" class="icb-xabyb"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="matrix(.99878 .71875 -2.04315 2.83916 21.468 18.633)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="ammexac5i"/><stop offset="1" class="kik7_ob9t"/></radialGradient><radialGradient id="svgIDY" cx="0" cy="0" r="1" gradientTransform="matrix(1.542 -1.58594 .4594 .44667 25.75 18.633)" gradientUnits="userSpaceOnUse"><stop class="hwnq5ubzm"/><stop offset="1" class="y9oqcminv"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="rotate(51.464 -5.154 31.769) scale(4.51441 1.8822)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="rlrqah7ok"/><stop offset="1" class="r-6du_zhr"/></radialGradient><radialGradient id="svgIDaa" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9688 -7.18748 5.67936 -5.50657 28.218 17.664)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="i1avtge0l"/><stop offset="1" class="ifp1_xbmc"/></radialGradient><radialGradient id="svgIDad" cx="0" cy="0" r="1" gradientTransform="matrix(1.76758 -1.26563 1.69437 2.36637 24.81 28.398)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(1.64636 -1.26562 1.72962 2.24995 17.644 28.39)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 20.797 26.21)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDao" cx="0" cy="0" r="1" gradientTransform="matrix(2.43827 .18437 -.24868 3.2888 .122 2.37)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="e31k1-bnl"/><stop offset=".865" class="tr9cr_bup"/></radialGradient><radialGradient id="svgIDap" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 2.746 3.121)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="xkrkjbk5z"/><stop offset="1" class="mvr01ib0c"/></radialGradient><radialGradient id="svgIDaq" cx="0" cy="0" r="1" gradientTransform="matrix(1.49685 3.75 -10.37919 4.14298 19.25 14.304)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="t5tj028fa"/><stop offset=".969" class="alhmdacdj"/></radialGradient><radialGradient id="svgIDau" cx="0" cy="0" r="1" gradientTransform="matrix(0 .49784 -1.34351 0 16.64 17.698)" gradientUnits="userSpaceOnUse"><stop class="kx97vubln"/><stop offset="1" class="qwnulubfe"/></radialGradient><radialGradient id="svgIDaA" cx="0" cy="0" r="1" gradientTransform="rotate(123.38 11.507 13.203) scale(2.43251 2.70978)" gradientUnits="userSpaceOnUse"><stop class="yyc9yuyiy"/><stop offset="1" class="o410gcc4i"/></radialGradient><radialGradient id="svgIDaB" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.265 2.758) scale(.82753 .4039)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDaC" cx="0" cy="0" r="1" gradientTransform="matrix(-.24716 1.2904 -1.34466 -.25755 11.478 6.825)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDaE" cx="0" cy="0" r="1" gradientTransform="matrix(-.79555 -.23096 .11273 -.3883 11.508 7.158)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDaF" cx="0" cy="0" r="1" gradientTransform="matrix(-.24742 1.29177 -1.34608 -.25783 11.474 6.829)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDaI" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.264 2.754) scale(.82748 .40388)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="svgIDaJ" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 2.922 8.152) scale(1.31379 1.36902)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="svgIDaL" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 6.597 5.995) scale(.57244 .80803)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="nx4bqnbvp"/><stop offset=".684" class="nkw7_sb2b"/></radialGradient><radialGradient id="svgIDaO" cx="0" cy="0" r="1" gradientTransform="matrix(.89142 -.04952 .06038 1.08682 11.383 7.387)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="svgIDaP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.48059 2.12951 0 14.444 8.641)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="s4vkc-bcm"/><stop offset="1" class="m4_ilibnz"/></radialGradient><radialGradient id="svgIDaQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4127 -.6436 0 13.569 7.436)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="rotate(42.274 -1.214 14.448) scale(4.90812 5.5655)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="n03tmgbfr"/><stop offset="1" class="a7758ab4t"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="matrix(-.41681 2.8343 -1.2521 -.18413 9.515 5.366)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="pmcqb6bbe"/><stop offset="1" class="obdoohpwg"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="rotate(-176.424 7.58 2.378) scale(1.58784 3.11596)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ozwza9bad"/><stop offset="1" class="mok6a1b9k"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.327 2.805) scale(.79931 .39013)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="svgIDaW" cx="0" cy="0" r="1" gradientTransform="matrix(-.23873 1.2464 -1.2988 -.24877 11.588 6.945)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="svgIDaY" cx="0" cy="0" r="1" gradientTransform="matrix(-.28889 0 0 -.56127 13.88 7.465)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.26412 0 0 -.57158 14.058 7.488)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbc" cx="0" cy="0" r="1" gradientTransform="rotate(14.265 -18.47 47.383) scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.52148 1.82813 -.23787 -.06785 12.149 4.274)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDbf" cx="0" cy="0" r="1" gradientTransform="matrix(-.35156 .1875 -.70184 -1.31597 11.985 9.29)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbg" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 12.031 7.18)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 9.715 7.664)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 12.063 8.555)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="matrix(.79471 -.23072 .11261 .38789 20.879 7.36)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDbl" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.203 16.165) scale(1.31386 1.3691)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="matrix(.79555 -.23097 .11273 .3883 20.883 7.365)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDbo" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.203 16.17) scale(1.31525 1.37055)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDbq" cx="0" cy="0" r="1" gradientTransform="matrix(.79467 -.23071 .1126 .38787 20.879 7.351)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="svgIDbr" cx="0" cy="0" r="1" gradientTransform="matrix(.24715 1.29033 -1.34458 .25754 20.913 7.02)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="matrix(.50349 .27238 -.38447 .7107 17.138 8.336)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="nx4bqnbvp"/><stop offset=".684" class="nkw7_sb2b"/></radialGradient><radialGradient id="svgIDbw" cx="0" cy="0" r="1" gradientTransform="matrix(-.89142 -.0496 .06048 -1.08682 21.009 7.594)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="svgIDbx" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.48059 2.12951 0 17.948 8.848)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="s4vkc-bcm"/><stop offset="1" class="m4_ilibnz"/></radialGradient><radialGradient id="svgIDby" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4127 -.6436 0 18.823 7.643)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="svgIDbA" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6317 3.30158 -3.74378 -4.11812 22.988 4.78)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="n03tmgbfr"/><stop offset="1" class="a7758ab4t"/></radialGradient><radialGradient id="svgIDbB" cx="0" cy="0" r="1" gradientTransform="matrix(.4168 2.8343 -1.2521 .18413 22.876 5.572)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="pmcqb6bbe"/><stop offset="1" class="obdoohpwg"/></radialGradient><radialGradient id="svgIDbC" cx="0" cy="0" r="1" gradientTransform="matrix(1.58475 -.09905 .19437 3.1099 17.392 5.43)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ozwza9bad"/><stop offset="1" class="mok6a1b9k"/></radialGradient><radialGradient id="svgIDbD" cx="0" cy="0" r="1" gradientTransform="matrix(.76761 -.22286 .10877 .37466 20.77 7.47)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="matrix(.23873 1.2464 -1.2988 .24876 20.803 7.151)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="svgIDbG" cx="0" cy="0" r="1" gradientTransform="matrix(.28889 0 0 .56127 18.511 7.671)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDbH" cx="0" cy="0" r="1" gradientTransform="matrix(.26412 0 0 .57158 18.334 7.694)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbK" cx="0" cy="0" r="1" gradientTransform="rotate(165.735 10.254 4.44) scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbL" cx="0" cy="0" r="1" gradientTransform="matrix(.52148 1.82813 -.23787 .06785 20.242 4.48)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDbN" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .1875 -.70185 1.31597 20.407 9.496)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbO" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 2.316 .797)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbP" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 0 1.281)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 2.348 2.172)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><linearGradient id="svgIDi" x1="6.625" x2="8.406" y1="19.805" y2="18.117" gradientUnits="userSpaceOnUse"><stop class="omfadubst"/><stop offset="1" class="qka3_sxpa"/></linearGradient><linearGradient id="svgIDj" x1="8.328" x2="8.116" y1="19.195" y2="18.984" gradientUnits="userSpaceOnUse"><stop class="w7fy1faaf"/><stop offset="1" class="yik88x48u"/></linearGradient><linearGradient id="svgIDk" x1="5.563" x2="6.844" y1="19.242" y2="19.305" gradientUnits="userSpaceOnUse"><stop offset=".28" class="a8j9w7nsg"/><stop offset="1" class="nmxkbkb2v"/></linearGradient><linearGradient id="svgIDs" x1="2.251" x2="2.836" y1="28.055" y2="28.188" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDu" x1="5.625" x2="5.625" y1="28.414" y2="28.09" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDx" x1="9.756" x2="10.3" y1="28.18" y2="28.163" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDz" x1="12.899" x2="12.899" y1="28.406" y2="28.082" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDD" x1="10.365" x2="10.365" y1="10.047" y2="14.621" gradientUnits="userSpaceOnUse"><stop class="cdk0jybbv"/><stop offset="1" class="sqoomfbpf"/></linearGradient><linearGradient id="svgIDL" x1="13.406" x2="13.641" y1="20.57" y2="20.141" gradientUnits="userSpaceOnUse"><stop offset=".245" class="bmw2gli7r"/><stop offset="1" class="r3qtxmtcb"/></linearGradient><linearGradient id="svgIDO" x1="25.301" x2="25.832" y1="9.78" y2="11.024" gradientUnits="userSpaceOnUse"><stop class="dr2k0bhek"/><stop offset="1" class="vvdzqypxx"/></linearGradient><linearGradient id="svgIDS" x1="25.375" x2="23.593" y1="19.789" y2="18.102" gradientUnits="userSpaceOnUse"><stop class="omfadubst"/><stop offset="1" class="qka3_sxpa"/></linearGradient><linearGradient id="svgIDT" x1="23.672" x2="23.884" y1="19.18" y2="18.969" gradientUnits="userSpaceOnUse"><stop class="w7fy1faaf"/><stop offset="1" class="yik88x48u"/></linearGradient><linearGradient id="svgIDU" x1="26.437" x2="25.156" y1="19.227" y2="19.289" gradientUnits="userSpaceOnUse"><stop offset=".28" class="a8j9w7nsg"/><stop offset="1" class="nmxkbkb2v"/></linearGradient><linearGradient id="svgIDac" x1="29.749" x2="29.164" y1="28.039" y2="28.172" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDae" x1="26.375" x2="26.375" y1="28.398" y2="28.074" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDah" x1="22.244" x2="21.7" y1="28.164" y2="28.147" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDaj" x1="19.101" x2="19.101" y1="28.391" y2="28.066" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDan" x1="1.732" x2="1.732" y1="0" y2="4.574" gradientUnits="userSpaceOnUse"><stop class="cdk0jybbv"/><stop offset="1" class="sqoomfbpf"/></linearGradient><linearGradient id="svgIDar" x1="17.246" x2="17.246" y1="17.108" y2="16.627" gradientUnits="userSpaceOnUse"><stop class="fy3lw0vjf"/><stop offset="1" class="v9jntfbgm"/></linearGradient><linearGradient id="svgIDas" x1="17.256" x2="17.256" y1="17.736" y2="17.254" gradientUnits="userSpaceOnUse"><stop class="fy3lw0vjf"/><stop offset="1" class="v9jntfbgm"/></linearGradient><linearGradient id="svgIDat" x1="17.375" x2="17.375" y1="18.468" y2="17.992" gradientUnits="userSpaceOnUse"><stop class="fy3lw0vjf"/><stop offset="1" class="v9jntfbgm"/></linearGradient><linearGradient id="svgIDav" x1="16.582" x2="16.859" y1="16.486" y2="15.879" gradientUnits="userSpaceOnUse"><stop class="fy3lw0vjf"/><stop offset="1" class="v9jntfbgm"/></linearGradient><linearGradient id="svgIDay" x1="24.207" x2="19.801" y1="11.836" y2="17.867" gradientUnits="userSpaceOnUse"><stop class="aqj5eu0hn"/><stop offset="1" class="t2k92_bem"/></linearGradient><linearGradient id="svgIDaD" x1="11.623" x2="11.316" y1="7.193" y2="7.278" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDaG" x1="11.568" x2="11.405" y1="7.233" y2="7.246" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDaK" x1="11.572" x2="11.41" y1="7.22" y2="7.233" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="svgIDaN" x1="11.713" x2="14.738" y1="8.171" y2="8.352" gradientUnits="userSpaceOnUse"><stop class="n2ets1bxw"/><stop offset="1" class="f6dcoc52h"/></linearGradient><linearGradient id="svgIDaX" x1="11.679" x2="11.522" y1="7.335" y2="7.348" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="svgIDba" x1="-.007" x2=".19" y1=".052" y2=".117" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbb" x1="11.977" x2="10.903" y1="5.32" y2="6.227" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbe" x1="11.406" x2="12.758" y1="8.93" y2="10.758" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><linearGradient id="svgIDbm" x1="20.768" x2="21.076" y1="7.399" y2="7.485" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDbp" x1="20.823" x2="20.986" y1="7.44" y2="7.453" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDbs" x1="20.819" x2="20.982" y1="7.426" y2="7.439" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="svgIDbv" x1="20.678" x2="17.654" y1="8.377" y2="8.559" gradientUnits="userSpaceOnUse"><stop class="n2ets1bxw"/><stop offset="1" class="f6dcoc52h"/></linearGradient><linearGradient id="svgIDbF" x1="20.712" x2="20.869" y1="7.542" y2="7.554" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="svgIDbI" x1="18.327" x2="18.523" y1="7.282" y2="7.347" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbJ" x1="20.414" x2="21.488" y1="5.527" y2="6.433" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbM" x1="20.985" x2="19.633" y1="9.136" y2="10.964" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><filter id="svgIDc" width="10.808" height="5.007" x="8.491" y="10.481" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.509804 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.411765 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23638" result="effect2_innerShadow_3987_23638"/></filter><filter id="svgIDe" width="7.106" height="3.139" x="10.204" y="11.571" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23638" stdDeviation=".2"/></filter><filter id="svgIDl" width="4.146" height="5.805" x="2.788" y="19.992" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.74902 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.576471 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23638" result="effect2_innerShadow_3987_23638"/></filter><filter id="svgIDm" width="9.426" height="8.574" x="2.717" y="9.792" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDn" width="5.878" height="6.781" x="2.144" y="13.672" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDr" width="5.139" height="3.208" x="2.051" y="25.406" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDv" width="2.686" height="1.05" x="2.698" y="25.406" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.670588 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDw" width="4.9" height="3.308" x="9.456" y="25.398" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDA" width="2.288" height="1.065" x="9.756" y="25.398" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDC" width="5.149" height="5.149" x="5.666" y="10.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23638" stdDeviation=".125"/></filter><filter id="svgIDG" width="1.796" height="1.427" x="13.37" y="17.731" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.552941 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDV" width="4.146" height="5.805" x="25.066" y="19.977" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.74902 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.576471 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23638" result="effect2_innerShadow_3987_23638"/></filter><filter id="svgIDW" width="9.426" height="8.574" x="19.857" y="9.776" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDX" width="5.878" height="6.781" x="23.978" y="13.656" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDab" width="5.139" height="3.208" x="24.61" y="25.391" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDaf" width="2.686" height="1.05" x="26.615" y="25.391" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.694118 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDag" width="4.9" height="3.308" x="17.344" y="25.383" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDak" width="2.288" height="1.065" x="20.156" y="25.383" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDam" width="5.149" height="5.149" x="21.185" y="10.299" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23638" stdDeviation=".125"/></filter><filter id="svgIDaw" width="5.984" height="7.891" x="7.785" y="11.414" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23638" stdDeviation=".25"/></filter><filter id="svgIDax" width="7.313" height="7.219" x="17.582" y="10.961" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23638" stdDeviation=".25"/></filter><filter id="svgIDaz" width="4.063" height="3.831" x="25.494" y="9.957" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23638" stdDeviation=".3"/></filter><filter id="svgIDaH" width="2.322" height="3.133" x="16.526" y="15.606" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23638" stdDeviation=".25"/></filter><filter id="svgIDaM" width="4.733" height="5.535" x="10.255" y="5.075" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.396078 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDaR" width="6.724" height="5.754" x="8.566" y="3.343" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.94902 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.74902 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23638" result="effect2_innerShadow_3987_23638"/></filter><filter id="svgIDbj" width="1.258" height=".393" x="12.95" y="6.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.231373 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDbu" width="4.733" height="5.535" x="17.404" y="5.282" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.396078 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter><filter id="svgIDbz" width="6.724" height="5.754" x="17.002" y="3.55" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.94902 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.74902 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23638" result="effect2_innerShadow_3987_23638"/></filter><filter id="svgIDbR" width="1.258" height=".393" x="18.184" y="6.521" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.231373 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23638"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-wrestling-medium-light" /></template>
<style>
.a0q036gjd {
  stop-color: var(--svg-color--504d4e, #504D4E);
}

.a27ei3rio {
  fill-rule: evenodd;
  d: path("M20.213 3.804a.25.25 0 0 0-.162.315l.95 2.968a.25.25 0 0 0 .476-.152l-.95-2.969a.25.25 0 0 0-.314-.162Z");
}

.a3ce-6b4m {
  fill: var(--svg-color--2797f6, #2797F6);
  d: path("M6.826 10.546a2.696 2.696 0 0 1 3.753 3.873l-3.262 3.178a2.71 2.71 0 1 1-3.77-3.891l3.28-3.16Z");
}

.a5dbyd6tf {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
}

.a7758ab4t {
  stop-color: var(--svg-color--ffdaa9, #FFDAA9);
}

.a8j9w7nsg {
  stop-color: var(--svg-color--194ec0, #194EC0);
}

.afvxbrb6i {
  fill-rule: evenodd;
  d: path("M13.373 18.277a.4.4 0 0 1 .55-.135c.404.245.859.47 1.375.648a.4.4 0 0 1-.26.757a7.868 7.868 0 0 1-1.53-.72a.4.4 0 0 1-.135-.55Z");
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

.av2_52fbu {
  cx: 18.402px;
  cy: 7.323px;
  rx: 0.068px;
  ry: 0.093px;
}

.axex79n_z {
  width: 1.258px;
  height: 0.293px;
  x: 12.95px;
  y: 6.414px;
  fill: var(--svg-color--8f5e36, #8F5E36);
  rx: 0.146px;
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.b2zb22byt {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.047px;
  rx: 1.732px;
}

.b5skg8e-v {
  stop-color: var(--svg-color--522470, #522470);
}

.b8hyhqehi {
  stop-color: var(--svg-color--c57872, #C57872);
  stop-opacity: 0;
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

.bs9ct9blb {
  stop-color: var(--svg-color--f7c09f, #F7C09F);
}

.bsuq0y52j {
  d: path("m29.072 14.32l-.664-.664l-3.68 3.953l1.21 1.016s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.055h3.025a.05.05 0 0 0 .047-.035c.16-.505.565-1.792.938-3.239c.409-1.592-.287-2.518-.66-2.844Z");
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.c-hifvbsi {
  d: path("m11.674 8.114l-.218-1.576a.796.796 0 0 0 .218 1.576Z");
}

.c-xbvquvy {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
}

.c31p4-hcd {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M19.086 9.13a.124.124 0 0 0-.124-.125h-.607a.124.124 0 0 0 0 .248h.607a.124.124 0 0 0 .124-.124Z");
}

.ccv6f1brb {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
  stop-opacity: 0;
}

.cdk0jybbv {
  stop-color: var(--svg-color--35aaf7, #35AAF7);
}

.chy2-3bdx {
  d: path("m22.156 26.328l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.262-.441.564-.438.802c.003.155.143.273.298.273h3.964a.25.25 0 0 0 .25-.25v-1.813Z");
}

.co_arab3u {
  d: path("m11.678 8.11l-.218-1.575a.795.795 0 0 0 .218 1.574Z");
}

.ct6_m01bp {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
}

.ctpmd67aa {
  d: path("M13.74 7.488a.653.653 0 0 1-.004-.077c0-.196.083-.355.185-.355c.103 0 .186.16.186.355a.676.676 0 0 1-.004.077h-.363Z");
}

.cyah9dbso {
  fill: var(--svg-color--dda07b, #DDA07B);
  d: path("m16.074 11.629l.536-.516c.123-.11.461-.332.824-.332h.988a.477.477 0 1 1 0 .953h-.866a.224.224 0 0 0-.202.13l-.033.068a.344.344 0 0 0-.002.288l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.056-3.902 2.229c-2.386.057-3.712-1.182-4.258-1.691a9.14 9.14 0 0 0-.108-.1l-.103-.092a1.15 1.15 0 1 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.047.11.098.17.154c.497.454 1.236 1.131 2.533 1.131c.391 0 .884-.013 1.408-.336c.51-.314.937-.699 1.167-.95a.667.667 0 0 1 .124-.108Z");
}

.cz--1m5fh {
  stop-color: var(--svg-color--c57872, #C57872);
}

.d5mpwjb6n {
  fill: var(--svg-color--9d91a7, #9D91A7);
  d: path("m27.297 26.182l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075l.22.874l-2.004-.158Z");
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.dm4voe-la {
  d: path("M0 0h2.371v3.351H0z");
}

.dnhfge9th {
  stroke: var(--svg-color--f4bea0, #F4BEA0);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.66 12.29c.073 1.374 2.032 4.874 4.235 6.14");
}

.dr2k0bhek {
  stop-color: var(--svg-color--c79b78, #C79B78);
}

.dsw1fjbmj {
  d: path("m11.781 8.185l-.21-1.52a.768.768 0 0 0 .21 1.52Z");
}

.dt4hg8bog {
  fill: var(--svg-color--e8b48e, #E8B48E);
  fill-rule: evenodd;
  d: path("M13.373 18.277a.4.4 0 0 1 .55-.135c.404.245.859.47 1.375.648a.4.4 0 0 1-.26.757a7.868 7.868 0 0 1-1.53-.72a.4.4 0 0 1-.135-.55Z");
}

.dxcffjstc {
  cx: 10.996px;
  cy: 7.664px;
  r: 1.281px;
}

.e31k1-bnl {
  stop-color: var(--svg-color--ebb898, #EBB898);
}

.e4nvf0jxv {
  d: path("m24.855 20.288l1.082-1.007l1.149-1.023l-3.133-1.906a78.474 78.474 0 0 1-1.4 1.66a.05.05 0 0 0 .003.068l2.23 2.207a.05.05 0 0 0 .07 0Z");
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.euz565odm {
  d: path("M14.708 6.649c-.04-.847-.315-1.255-.444-1.374h-3.943l-.066 3.342c.915 2.242 3.71 2.338 4.127 1.527c.418-.81.373-2.515.326-3.495Z");
}

.eyc0ghbbh {
  d: path("M14.033 5.853c.693 0 1.024-.392 1.057-.883c0-.693-.53-.84-.735-.862c-.231-.025-.322-.05-.644-.277a.954.954 0 0 0-.961-.103c-.157.074-.504.111-.752.037c-.412-.124-.734-.12-1.052.124c-.22.17-.383.17-.648.17c-.363 0-.671.162-.904.338c-.694.525-.615 2.331-.272 3.347c.328.97.821 1.085 1.234 1.048c.497-.045.623-.421.697-.735c.06-.25.212-1.046.281-1.307c.143-.066.456-.091.561-.5c.106-.41.52-.457.801-.43c.17.017.644.033 1.337.033Z");
}

.f4dftzbyn {
  d: path("m2.919 25.482l-.66 2.621a.25.25 0 0 0 .242.311h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.865-.763-1.157a86.272 86.272 0 0 1-1.696-.9l.376-.719a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076Z");
}

.f6dcoc52h {
  stop-color: var(--svg-color--cb947a, #CB947A);
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

.ftl_v55qt {
  d: path("m20.61 8.392l.21-1.52a.768.768 0 0 1-.21 1.52Z");
}

.fwkra3bhz {
  d: path("M16.086 15.43a.384.384 0 1 0 0 .77h.518a.064.064 0 1 1 0 .128h1.158V16.2h.254l-.31-.31a1.568 1.568 0 0 0-1.108-.458h-.512Z");
}

.fy3lw0vjf {
  stop-color: var(--svg-color--ba7682, #BA7682);
}

.gawbh7bii {
  d: path("M10.647 10.626a2.697 2.697 0 0 0-3.821-.08l-3.234 3.126l-.045.034c-.067.064-.13.13-.188.2l-.43.43c-.373.325-1.069 1.252-.66 2.844c.372 1.447.778 2.733.938 3.239c.003.01.01.02.02.026a.052.052 0 0 0 .027.008h3.025a.05.05 0 0 0 .05-.055c-.074-.714-.268-1.757-.268-1.757l.876-.735c.133-.09.26-.193.38-.309l3.261-3.178a2.696 2.696 0 0 0 .069-3.793Z");
}

.gepoezb-p {
  fill: var(--svg-color--a56061, #A56061);
  d: path("m16.47 11.457l-.59.57l.297 1.114l1.425-.505l-.08-.117a.316.316 0 0 1-.023-.311l.03-.064a.205.205 0 0 1 .185-.118h.42a.437.437 0 0 0 0-.874h-.907c-.333 0-.643.203-.756.305Z");
}

.gg2ehgbth {
  width: 3.464px;
  height: 4.574px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.git0cmp4l {
  fill-rule: evenodd;
  d: path("M11.102 8.354a.25.25 0 0 1 .325.138c.1.247.285.645.511 1.038c.23.399.488.767.732.975a.25.25 0 1 1-.324.38c-.312-.266-.606-.696-.841-1.105a9.538 9.538 0 0 1-.541-1.1a.25.25 0 0 1 .138-.326Z");
}

.gjr9r-itc {
  stop-color: var(--svg-color--e2b38e, #E2B38E);
}

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
}

.gqo2gi93k {
  fill: var(--svg-color--e7b28b, #E7B28B);
  fill-rule: evenodd;
  d: path("M8.23 11.343a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.544a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gy1xmobvy {
  stop-color: var(--svg-color--c18066, #C18066);
  stop-opacity: 0;
}

.gyqgpnbjt {
  d: path("M20.156 26.188v-.755a.05.05 0 0 1 .05-.05h1.989a.05.05 0 0 1 .05.055l-.089.89v.02l-2-.16Z");
}

.h-vfp3yri {
  d: path("m20.713 8.306l.218-1.574a.795.795 0 0 1-.218 1.574Z");
}

.hb8modbps {
  fill-rule: evenodd;
  d: path("M13.393 19.116a.45.45 0 0 1 .624-.122l.973.657a.45.45 0 0 1-.503.746l-.973-.657a.45.45 0 0 1-.121-.624Z");
}

.hfo25hbkn {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m22.156 26.328l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.262-.441.564-.438.802c.003.155.143.273.298.273h3.964a.25.25 0 0 0 .25-.25v-1.813Z");
}

.hh9ibwbje {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
  stop-opacity: 0;
}

.hwnq5ubzm {
  stop-color: var(--svg-color--2670da, #2670DA);
}

.hy8b1ubxg {
  stop-color: var(--svg-color--cc8778, #CC8778);
}

.i_emxkhmq {
  stop-color: var(--svg-color--442f88, #442F88);
}

.i1avtge0l {
  stop-color: var(--svg-color--2f80be, #2F80BE);
  stop-opacity: 0;
}

.iasq92bar {
  d: path("M19.316 9.069h2.371v3.351h-2.371z");
}

.icb-xabyb {
  stop-color: var(--svg-color--c98181, #C98181);
  stop-opacity: 0;
}

.idjwbh6kk {
  d: path("m16.074 11.629l.536-.516c.123-.11.461-.332.824-.332h.988a.477.477 0 1 1 0 .953h-.866a.224.224 0 0 0-.202.13l-.033.068a.344.344 0 0 0-.002.288l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.056-3.902 2.229c-2.386.057-3.712-1.182-4.258-1.691a9.14 9.14 0 0 0-.108-.1l-.103-.092a1.15 1.15 0 1 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.047.11.098.17.154c.497.454 1.236 1.131 2.533 1.131c.391 0 .884-.013 1.408-.336c.51-.314.937-.699 1.167-.95a.667.667 0 0 1 .124-.108Z");
}

.ifp1_xbmc {
  stop-color: var(--svg-color--2f80be, #2F80BE);
}

.ihifsjbzy {
  d: path("M14.945 7.667a1.061 1.061 0 0 1-.272-.483h-.19v1.189c.227.144.551.122.648-.095c.082-.186.02-.417-.186-.61Z");
}

.ij--3abxg {
  d: path("m7.145 20.303l-1.082-1.006l-1.149-1.024l3.133-1.906a77.83 77.83 0 0 0 1.4 1.66a.05.05 0 0 1-.003.068l-2.23 2.207a.05.05 0 0 1-.07.001Z");
}

.im6n2fovl {
  d: path("M13.534 7.488v-.005c0-.338.144-.612.323-.612c.18 0 .324.274.324.612v.005h-.647Z");
}

.iwql0cvaa {
  d: path("M18.358 6.06c-.693 0-1.024-.392-1.056-.883c0-.694.529-.841.734-.863c.231-.025.322-.05.644-.276a.954.954 0 0 1 .962-.104c.156.075.503.112.75.037c.413-.123.735-.12 1.053.124c.22.17.383.17.648.17c.363 0 .671.162.904.338c.694.525.615 2.332.272 3.347c-.328.971-.821 1.085-1.234 1.048c-.497-.045-.623-.42-.697-.734c-.06-.251-.212-1.047-.281-1.308c-.143-.066-.456-.09-.561-.5c-.106-.41-.52-.456-.8-.43c-.171.017-.645.034-1.338.034Z");
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jv-vvdc2h {
  stop-color: var(--svg-color--433352, #433352);
  stop-opacity: 0;
}

.k4zv8rbbo {
  d: path("M18.858 7.694V7.69c0-.338-.145-.613-.324-.613c-.18 0-.324.275-.324.613v.004h.648Z");
}

.k8s01tfdv {
  stop-color: var(--svg-color--5e5663, #5E5663);
  stop-opacity: 0;
}

.kadt4rbbe {
  fill: var(--svg-color--e8b48e, #E8B48E);
  fill-rule: evenodd;
  d: path("M13.609 18.809a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.69l-1.215-.715a.4.4 0 0 1-.142-.548Z");
}

.kc2hp5b1b {
  d: path("M11.844 26.204v-.756a.05.05 0 0 0-.05-.05H9.805a.05.05 0 0 0-.05.055l.089.89v.02l2-.159Z");
}

.kgukkhbth {
  stop-color: var(--svg-color--5e5663, #5E5663);
}

.kik7_ob9t {
  stop-color: var(--svg-color--c18b70, #C18B70);
  stop-opacity: 0;
}

.klgjqhl0b {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M13.305 8.923c0-.069.056-.124.124-.124h.607a.124.124 0 0 1 0 .248h-.607a.124.124 0 0 1-.124-.124Z");
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.ksl77bchk {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
  stop-opacity: 0;
}

.kvi4eqmnu {
  fill: var(--svg-color--dda691, #DDA691);
  fill-rule: evenodd;
  d: path("M13.025 19.63a.4.4 0 0 1 .56-.085l.746.547a.4.4 0 1 1-.473.645l-.746-.547a.4.4 0 0 1-.087-.56Z");
}

.kx97vubln {
  stop-color: var(--svg-color--e2b09a, #E2B09A);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l3r47ffcx {
  stop-color: var(--svg-color--d1907d, #D1907D);
}

.l6m3twbxj {
  fill: var(--svg-color--deac8c, #DEAC8C);
  d: path("M16.086 15.43a.384.384 0 1 0 0 .77h.518a.064.064 0 1 1 0 .128h1.158V16.2h.254l-.31-.31a1.568 1.568 0 0 0-1.108-.458h-.512Z");
}

.l6veklvwf {
  stop-color: var(--svg-color--9e94a2, #9E94A2);
}

.li5uyl08u {
  stop-color: var(--svg-color--bc7a83, #BC7A83);
  stop-opacity: 0;
}

.m1j2mbbtp {
  stop-color: var(--svg-color--bc7a83, #BC7A83);
}

.m4_ilibnz {
  stop-color: var(--svg-color--e4af8c, #E4AF8C);
  stop-opacity: 0;
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
  stop-opacity: 0;
}

.mmwkogbxc {
  d: path("m20.717 8.321l.218-1.576a.796.796 0 0 1-.218 1.576Z");
}

.mok6a1b9k {
  stop-color: var(--svg-color--ffe8b5, #FFE8B5);
  stop-opacity: 0;
}

.mqedtfb5e {
  stop-color: var(--svg-color--423948, #423948);
}

.ms4f1oj7g {
  r: 1.281px;
}

.mvr01ib0c {
  stop-color: var(--svg-color--dc877f, #DC877F);
  stop-opacity: 0;
}

.mxco7gaxf {
  d: path("m9.172 21.953l-2.039-1.805l2.156-2.187a68.14 68.14 0 0 0 1.903 2.277c.67.77.758 1.77.738 2.262l-.102 2.898H9.805c-.068-.734-.211-2.307-.242-2.726a.954.954 0 0 0-.39-.719Z");
}

.myma9ccll {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m2.919 25.482l-.66 2.621a.25.25 0 0 0 .242.311h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.865-.763-1.157a86.272 86.272 0 0 1-1.696-.9l.376-.719a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076Z");
}

.n03tmgbfr {
  stop-color: var(--svg-color--ffe0af, #FFE0AF);
}

.n2ets1bxw {
  stop-color: var(--svg-color--d49d8d, #D49D8D);
}

.n3ys-0_iy {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.173 7.488H13.13c0-.414.234-.75.522-.75c.288 0 .522.336.522.75Z");
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

.nbc6eks5j {
  fill: var(--svg-color--2797f6, #2797F6);
  d: path("m29.072 14.32l-.664-.664l-3.68 3.953l1.21 1.016s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.055h3.025a.05.05 0 0 0 .047-.035c.16-.505.565-1.792.938-3.239c.409-1.592-.287-2.518-.66-2.844Z");
}

.ndir12pxa {
  fill: var(--svg-color--2797f6, #2797F6);
  d: path("M25.174 10.53a2.696 2.696 0 0 0-3.752 3.874l3.261 3.178a2.71 2.71 0 1 0 3.77-3.892l-3.28-3.16Z");
}

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.ng6zjrf7b {
  fill: var(--svg-color--d7a180, #D7A180);
  fill-rule: evenodd;
  d: path("M23.727 11.604c.627.167 1 .81.833 1.438c-.25.937-.826 1.86-1.893 3.008c-1.075 1.157-2.67 2.248-4.615 2.413a1.175 1.175 0 0 1-1.27-1.07c-.055-.648.363-1.163 1.01-1.218c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.832Z");
}

.nkw7_sb2b {
  stop-color: var(--svg-color--c27f74, #C27F74);
}

.nm5hd83mo {
  d: path("m22.828 21.938l2.039-1.805l-2.156-2.188a69.097 69.097 0 0 1-1.903 2.278c-.67.77-.758 1.77-.738 2.261l.102 2.899h2.023c.068-.735.211-2.308.242-2.727a.954.954 0 0 1 .39-.718Z");
}

.nmxkbkb2v {
  stop-color: var(--svg-color--115ecc, #115ECC);
  stop-opacity: 0;
}

.nphgd6nhc {
  d: path("M17.446 7.874a1.06 1.06 0 0 0 .272-.483h.19v1.188c-.227.145-.551.122-.648-.094c-.082-.186-.02-.417.186-.611Z");
}

.nrp5bhxwt {
  d: path("m2.928 14.336l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.757a.05.05 0 0 1-.05.055H3.255a.05.05 0 0 1-.047-.034a63.154 63.154 0 0 1-.938-3.24c-.409-1.591.287-2.517.66-2.843Z");
}

.nx4bqnbvp {
  stop-color: var(--svg-color--d6a183, #D6A183);
}

.o-9fab9od {
  fill-rule: evenodd;
  d: path("M13.609 18.809a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.69l-1.215-.715a.4.4 0 0 1-.142-.548Z");
}

.o410gcc4i {
  stop-color: var(--svg-color--ecb596, #ECB596);
  stop-opacity: 0;
}

.obdoohpwg {
  stop-color: var(--svg-color--fff4bb, #FFF4BB);
  stop-opacity: 0;
}

.ocru65npv {
  stop-color: var(--svg-color--3f3646, #3F3646);
}

.omfadubst {
  stop-color: var(--svg-color--205ac3, #205AC3);
}

.on8sxx3yx {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
  stop-opacity: 0;
}

.or75t2brf {
  fill: var(--svg-color--deac8c, #DEAC8C);
  d: path("M15.503 17.346c0-.216.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.oybn7vbqt {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
}

.ozwza9bad {
  stop-color: var(--svg-color--ffe8b5, #FFE8B5);
}

.p5wg8876f {
  stop-color: var(--svg-color--a6605e, #A6605E);
}

.pafpa8b3r {
  stop-color: var(--svg-color--e3a984, #E3A984);
}

.pfu46_y1s {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
}

.pmcqb6bbe {
  stop-color: var(--svg-color--fff4bb, #FFF4BB);
}

.pms-3nbqx {
  fill-rule: evenodd;
  d: path("M23.727 11.604c.627.167 1 .81.833 1.438c-.25.937-.826 1.86-1.893 3.008c-1.075 1.157-2.67 2.248-4.615 2.413a1.175 1.175 0 0 1-1.27-1.07c-.055-.648.363-1.163 1.01-1.218c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.832Z");
}

.ps38e5bsm {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.047px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.puldk8xku {
  d: path("M18.651 7.694a.676.676 0 0 0 .004-.076c0-.196-.083-.355-.185-.355c-.103 0-.186.159-.186.355c0 .026.001.052.004.076h.363Z");
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

.qabo_1v4b {
  cx: 17.687px;
  cy: 17.173px;
  fill: var(--svg-color--deaa89, #DEAA89);
  rx: 0.661px;
  ry: 1.066px;
}

.qdq-erb7u {
  stop-color: var(--svg-color--e5a88d, #E5A88D);
}

.qihskpbeg {
  stop-color: var(--svg-color--524e8d, #524E8D);
  stop-opacity: 0;
}

.qka3_sxpa {
  stop-color: var(--svg-color--2b7ec4, #2B7EC4);
}

.qwnulubfe {
  stop-color: var(--svg-color--e2b09a, #E2B09A);
  stop-opacity: 0;
}

.qy3mcrgdk {
  stop-color: var(--svg-color--c18066, #C18066);
}

.r-6du_zhr {
  stop-color: var(--svg-color--227be5, #227BE5);
  stop-opacity: 0;
}

.r3qtxmtcb {
  stop-color: var(--svg-color--be7d83, #BE7D83);
  stop-opacity: 0;
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.r4i2vf4ry {
  d: path("m29.081 25.466l.66 2.621a.25.25 0 0 1-.242.311h-4.441c-.102 0-.196-.06-.22-.158c-.127-.504.196-.866.763-1.157a85.685 85.685 0 0 0 1.696-.901l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075Z");
}

.r8n5q7b5r {
  fill-rule: evenodd;
  d: path("M21.29 8.56a.25.25 0 0 0-.326.138c-.1.248-.285.646-.51 1.039c-.23.398-.49.766-.733.975a.25.25 0 0 0 .324.38c.312-.267.606-.697.841-1.106a9.55 9.55 0 0 0 .541-1.1a.25.25 0 0 0-.137-.325Z");
}

.rdgulqvms {
  stop-color: var(--svg-color--e1a38b, #E1A38B);
  stop-opacity: 0;
}

.rh5emhbls {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M24.02 11.836c-.26 1.312-1.738 4.244-5.563 5.469");
}

.rjxx4vs3o {
  fill: var(--svg-color--e8b396, #E8B396);
  fill-rule: evenodd;
  d: path("M15.127 18.109a.4.4 0 0 1-.188.533l-.996.477a.4.4 0 1 1-.346-.722l.996-.476a.4.4 0 0 1 .534.188Z");
}

.rknzqr02l {
  stop-color: var(--svg-color--695d73, #695D73);
  stop-opacity: 0;
}

.rlrqah7ok {
  stop-color: var(--svg-color--225fc7, #225FC7);
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.s4vkc-bcm {
  stop-color: var(--svg-color--e4af8c, #E4AF8C);
}

.sf9fznbjz {
  fill: var(--svg-color--e8b48e, #E8B48E);
  fill-rule: evenodd;
  d: path("M13.393 19.116a.45.45 0 0 1 .624-.122l.973.657a.45.45 0 0 1-.503.746l-.973-.657a.45.45 0 0 1-.121-.624Z");
}

.sgqr937ow {
  stop-color: var(--svg-color--c98181, #C98181);
}

.shic-ydjf {
  stop-color: var(--svg-color--2e2d2f, #2E2D2F);
}

.sik08cc9l {
  fill: var(--svg-color--deac8c, #DEAC8C);
  d: path("M15.464 16.718a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.sneyg9bdl {
  d: path("M26.406 10.558a.3.3 0 1 0-.024.6l.024-.6Zm1.29.353l.013-.3l-.012.3Zm.899 1.343l.282.103l-.282-.103Zm-.514.532a.3.3 0 0 0 .563.206l-.563-.206Zm-1.7-1.629l1.303.053l.025-.599l-1.303-.053l-.024.6Zm1.932.993l-.232.636l.563.206l.233-.635l-.564-.207Zm-.629-.94a.7.7 0 0 1 .63.94l.563.207a1.3 1.3 0 0 0-1.168-1.746l-.025.6Z");
}

.so-5pppws {
  fill-rule: evenodd;
  d: path("M27.133 12.318a.1.1 0 0 0-.09-.14l-3.873-.058l.035-2.34l4.25.061c1.653.024 2.653 1.726 1.919 3.233l-1.186 2.545l-2.062-1.019l1.007-2.282Z");
}

.sqoomfbpf {
  stop-color: var(--svg-color--39a2f4, #39A2F4);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t2k92_bem {
  stop-color: var(--svg-color--e9b798, #E9B798);
  stop-opacity: 0;
}

.t5tj028fa {
  stop-color: var(--svg-color--cc8f8d, #CC8F8D);
  stop-opacity: 0;
}

.tazxosblz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.218 7.694h1.044c0-.414-.234-.749-.522-.749c-.288 0-.522.335-.522.75Z");
}

.th4vgcc8j {
  d: path("M21.353 10.61a2.697 2.697 0 0 1 3.821-.08l3.234 3.126l.045.034c.067.064.13.13.188.2l.43.43c.373.326 1.069 1.252.66 2.844a62.473 62.473 0 0 1-.938 3.24a.047.047 0 0 1-.02.025a.053.053 0 0 1-.027.009h-3.025a.05.05 0 0 1-.05-.055c.075-.715.268-1.758.268-1.758l-.876-.735a2.72 2.72 0 0 1-.38-.308l-3.261-3.178a2.696 2.696 0 0 1-.069-3.794Z");
}

.tob0y3box {
  fill: var(--svg-color--e5a997, #E5A997);
  d: path("m28.11 22.094l.57-1.727l-2.876-.39c-.013.093-.071.51-.203 1.43c-.13.918.125 1.663.375 2.202l1.22 2.172h1.866c-.245-.77-.844-2.77-.93-3.031c-.085-.262-.085-.48-.023-.656Z");
}

.tp7btwbhq {
  fill-rule: evenodd;
  d: path("M8.23 11.343a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.544a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

.tr9cr_bup {
  stop-color: var(--svg-color--e09e8e, #E09E8E);
}

.u0hatmkqb {
  d: path("M15.464 16.718a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.u0yw4v3mc {
  stroke: var(--svg-color--ebac91, #EBAC91);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.804 13.484c.38.25 1.469.722 2.781.61c1.64-.141 2.656-1.048 3.125-1.923");
}

.u2n90vbun {
  stop-color: var(--svg-color--ad6361, #AD6361);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ui4gszb6g {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m9.844 26.343l-.088-.89a.05.05 0 0 1 .05-.055h1.988a.05.05 0 0 1 .05.05v.767c.559.262 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.155-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.uj_nqubgh {
  stop-color: var(--svg-color--ecb297, #ECB297);
}

.uq4h3zxiv {
  stop-color: var(--svg-color--dda595, #DDA595);
}

.v0z-u3bkw {
  fill-rule: evenodd;
  d: path("M12.178 3.598a.25.25 0 0 1 .162.314l-.95 2.969a.25.25 0 0 1-.476-.152l.95-2.97a.25.25 0 0 1 .314-.161Z");
}

.v203o78us {
  d: path("M15.503 17.346c0-.216.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.v2vw7kyua {
  d: path("M17.683 6.855c.04-.846.315-1.254.444-1.373h3.943l.066 3.342c-.915 2.242-3.71 2.338-4.127 1.527c-.417-.81-.373-2.516-.326-3.496Z");
}

.v8d4ab1_b {
  fill-rule: evenodd;
  d: path("M13.025 19.63a.4.4 0 0 1 .56-.085l.746.547a.4.4 0 1 1-.473.645l-.746-.547a.4.4 0 0 1-.087-.56Z");
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

.w7fy1faaf {
  stop-color: var(--svg-color--245dc6, #245DC6);
}

.wbqgxvibx {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m29.081 25.466l.66 2.621a.25.25 0 0 1-.242.311h-4.441c-.102 0-.196-.06-.22-.158c-.127-.504.196-.866.763-1.157a85.685 85.685 0 0 0 1.696-.901l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075Z");
}

.wg-u6yb-o {
  stop-color: var(--svg-color--bc7a7b, #BC7A7B);
  stop-opacity: 0;
}

.wicb2kbvo {
  fill: var(--svg-color--2797f6, #2797F6);
  d: path("m2.928 14.336l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.757a.05.05 0 0 1-.05.055H3.255a.05.05 0 0 1-.047-.034a63.154 63.154 0 0 1-.938-3.24c-.409-1.591.287-2.517.66-2.843Z");
}

.wirr61xwd {
  d: path("m20.713 8.316l.218-1.575a.795.795 0 0 1-.218 1.575Z");
}

.wr624mrxa {
  d: path("M15.846 18.082c0-.212.173-.384.386-.384h1.385l.308.77H16.23a.385.385 0 0 1-.385-.386Z");
}

.wutgx970i {
  fill: var(--svg-color--deac8c, #DEAC8C);
  d: path("M15.846 18.082c0-.212.173-.384.386-.384h1.385l.308.77H16.23a.385.385 0 0 1-.385-.386Z");
}

.xfc-qx9ex {
  d: path("m9.844 26.343l-.088-.89a.05.05 0 0 1 .05-.055h1.988a.05.05 0 0 1 .05.05v.767c.559.262 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.155-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.xkrkjbk5z {
  stop-color: var(--svg-color--dc877f, #DC877F);
}

.xs5quubmq {
  width: 0.764px;
  height: 1.4px;
  x: 17.093px;
  y: 15.721px;
  fill: var(--svg-color--dea989, #DEA989);
  rx: 0.382px;
}

.y3ldcubnb {
  fill: var(--svg-color--e5a997, #E5A997);
  d: path("m3.89 22.11l-.57-1.727l2.876-.39c.013.093.071.51.203 1.429c.13.919-.125 1.664-.375 2.203l-1.22 2.172H2.939c.245-.771.843-2.77.93-3.031c.085-.262.085-.48.023-.657Z");
}

.y4pe4ezsu {
  stop-color: var(--svg-color--271e2e, #271E2E);
}

.y57kfh6zq {
  fill: var(--svg-color--baa4c5, #BAA4C5);
  d: path("m4.703 26.197l.376-.718a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076l-.22.874l2.004-.159Z");
}

.y9oqcminv {
  stop-color: var(--svg-color--2283f1, #2283F1);
  stop-opacity: 0;
}

.yfv3nqb2s {
  stop-color: var(--svg-color--e4a88b, #E4A88B);
  stop-opacity: 0;
}

.yic7b8bke {
  stop-color: var(--svg-color--bc7a7b, #BC7A7B);
}

.yik88x48u {
  stop-color: var(--svg-color--245dc6, #245DC6);
  stop-opacity: 0;
}

.yyc9yuyiy {
  stop-color: var(--svg-color--ecb596, #ECB596);
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.zhbm06bnu {
  rx: 0.068px;
  ry: 0.093px;
}

.zjmmjyoar {
  stop-color: var(--svg-color--554f5c, #554F5C);
}

.zsfek5b8q {
  d: path("m11.678 8.1l-.218-1.574a.795.795 0 0 0 .218 1.574Z");
}

</style>
