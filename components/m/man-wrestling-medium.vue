<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#svgIDa)" transform="rotate(-23.31 19.316 9.068)" class="qcr3xcbrj"/><path fill="url(#svgIDb)" transform="scale(-1 1) rotate(-34.332 8.824 25.522)" class="dm4voe-la"/><path class="fniuksbbx"/><g filter="url(#svgIDc)"><path class="e1hyixrny"/><path fill="url(#svgIDd)" class="idjwbh6kk"/></g><g filter="url(#svgIDe)"><path class="xpassgbnv"/></g><path fill="url(#svgIDf)" class="mxco7gaxf"/><path fill="url(#svgIDg)" class="mxco7gaxf"/><path fill="url(#svgIDh)" class="mxco7gaxf"/><path fill="url(#svgIDi)" class="ij--3abxg"/><path fill="url(#svgIDj)" class="ij--3abxg"/><path fill="url(#svgIDk)" class="ij--3abxg"/><g filter="url(#svgIDl)"><path class="r9debcckm"/></g><g filter="url(#svgIDm)"><path class="a3ce-6b4m"/></g><g filter="url(#svgIDn)"><path class="wicb2kbvo"/><path fill="url(#svgIDo)" class="nrp5bhxwt"/></g><path fill="url(#svgIDp)" class="gawbh7bii"/><path fill="url(#svgIDq)" class="gawbh7bii"/><g filter="url(#svgIDr)"><path class="myma9ccll"/><path fill="url(#svgIDs)" class="f4dftzbyn"/><path fill="url(#svgIDt)" class="f4dftzbyn"/><path fill="url(#svgIDu)" class="f4dftzbyn"/></g><g filter="url(#svgIDv)"><path class="y57kfh6zq"/></g><g filter="url(#svgIDw)"><path class="ui4gszb6g"/><path fill="url(#svgIDx)" class="xfc-qx9ex"/><path fill="url(#svgIDy)" class="xfc-qx9ex"/><path fill="url(#svgIDz)" class="xfc-qx9ex"/></g><g filter="url(#svgIDA)"><path fill="url(#svgIDB)" class="kc2hp5b1b"/></g><g filter="url(#svgIDC)"><rect stroke="url(#svgIDD)" transform="rotate(45 8.633 10.046)" class="xvumooy0c"/></g><rect fill="url(#svgIDE)" transform="rotate(45 8.633 10.046)" class="puraqfb4y"/><rect fill="url(#svgIDF)" transform="rotate(45 8.633 10.046)" class="puraqfb4y"/><g filter="url(#svgIDG)"><path clip-rule="evenodd" class="psd98zbad"/></g><path clip-rule="evenodd" class="zj8amkhtl"/><path fill="url(#svgIDH)" clip-rule="evenodd" class="sqykkfq6i"/><path clip-rule="evenodd" class="qq1642b9j"/><path fill="url(#svgIDI)" clip-rule="evenodd" class="xfej-jbum"/><path clip-rule="evenodd" class="con5gggje"/><path fill="url(#svgIDJ)" clip-rule="evenodd" class="xexidbngb"/><path clip-rule="evenodd" class="ryafw47dj"/><path fill="url(#svgIDK)" clip-rule="evenodd" class="hb8modbps"/><path clip-rule="evenodd" class="hr3mxybxz"/><path fill="url(#svgIDL)" clip-rule="evenodd" class="v8d4ab1_b"/><path fill="url(#svgIDM)" clip-rule="evenodd" class="k56umfb4k"/><path fill="url(#svgIDN)" clip-rule="evenodd" class="k56umfb4k"/><path fill="url(#svgIDO)" clip-rule="evenodd" class="k56umfb4k"/><rect transform="rotate(-28.166 17.093 15.72)" class="yg6pzzb4x"/><path fill="url(#svgIDP)" class="nm5hd83mo"/><path fill="url(#svgIDQ)" class="nm5hd83mo"/><path fill="url(#svgIDR)" class="nm5hd83mo"/><path fill="url(#svgIDS)" class="e4nvf0jxv"/><path fill="url(#svgIDT)" class="e4nvf0jxv"/><path fill="url(#svgIDU)" class="e4nvf0jxv"/><g filter="url(#svgIDV)"><path class="y0z19fbvl"/></g><g filter="url(#svgIDW)"><path class="ndir12pxa"/></g><g filter="url(#svgIDX)"><path class="nbc6eks5j"/><path fill="url(#svgIDY)" class="bsuq0y52j"/></g><path fill="url(#svgIDZ)" class="th4vgcc8j"/><path fill="url(#svgIDaa)" class="th4vgcc8j"/><g filter="url(#svgIDab)"><path class="wbqgxvibx"/><path fill="url(#svgIDac)" class="r4i2vf4ry"/><path fill="url(#svgIDad)" class="r4i2vf4ry"/><path fill="url(#svgIDae)" class="r4i2vf4ry"/></g><g filter="url(#svgIDaf)"><path class="d5mpwjb6n"/></g><g filter="url(#svgIDag)"><path class="hfo25hbkn"/><path fill="url(#svgIDah)" class="chy2-3bdx"/><path fill="url(#svgIDai)" class="chy2-3bdx"/><path fill="url(#svgIDaj)" class="chy2-3bdx"/></g><g filter="url(#svgIDak)"><path fill="url(#svgIDal)" class="gyqgpnbjt"/></g><rect fill="url(#svgIDam)" transform="scale(-1 1) rotate(45 -23.792 -23.192)" class="pxj138bcc"/><rect fill="url(#svgIDan)" transform="scale(-1 1) rotate(45 -23.792 -23.192)" class="pxj138bcc"/><rect fill="url(#svgIDao)" transform="scale(-1 1) rotate(45 -23.792 -23.192)" class="pxj138bcc"/><rect fill="url(#svgIDap)" transform="scale(-1 1) rotate(45 -23.792 -23.192)" class="pxj138bcc"/><path clip-rule="evenodd" class="pxzeppb5u"/><path fill="url(#svgIDaq)" clip-rule="evenodd" class="qxca1sbyr"/><path class="deb_iib1u"/><path fill="url(#svgIDar)" class="u0hatmkqb"/><path fill="url(#svgIDas)" class="u0hatmkqb"/><path class="dhqfwlbde"/><path fill="url(#svgIDat)" class="dryamrx6b"/><path fill="url(#svgIDau)" class="dryamrx6b"/><path class="sgbzszd0s"/><path fill="url(#svgIDav)" class="wr624mrxa"/><path fill="url(#svgIDaw)" class="wr624mrxa"/><path class="ont54vbxw"/><path fill="url(#svgIDax)" class="fwkra3bhz"/><path fill="url(#svgIDay)" class="fwkra3bhz"/><g filter="url(#svgIDaz)"><path class="afg3zhs8x"/></g><g filter="url(#svgIDaA)"><path stroke="url(#svgIDaB)" class="rh5emhbls"/></g><g filter="url(#svgIDaC)"><path fill="url(#svgIDaD)" class="kwmheoo9h"/></g><g filter="url(#svgIDaE)"><ellipse class="krjt31z8n"/></g><path fill="url(#svgIDaF)" class="b-ce31bju"/><path fill="url(#svgIDaG)" class="b-ce31bju"/><g filter="url(#svgIDaH)"><path fill="url(#svgIDaI)" class="r4wrwpygj"/><path fill="url(#svgIDaJ)" class="r4wrwpygj"/><path fill="url(#svgIDaK)" class="r4wrwpygj"/><path fill="url(#svgIDaL)" class="r4wrwpygj"/></g><g filter="url(#svgIDaM)"><path fill="url(#svgIDaN)" class="fodk42bev"/><path fill="url(#svgIDaO)" class="fodk42bev"/><path fill="url(#svgIDaP)" class="fodk42bev"/></g><path fill="url(#svgIDaQ)" class="h-yw9d58o"/><path fill="url(#svgIDaR)" class="h-yw9d58o"/><path fill="url(#svgIDaS)" class="h-yw9d58o"/><path class="t06ea0i_l"/><path fill="url(#svgIDaT)" class="at2v7wy3p"/><path fill="url(#svgIDaU)" class="ba6qsgbyc"/><ellipse fill="url(#svgIDaV)" transform="scale(-1 1) rotate(24.61 -23.305 -28.308)" class="zhbm06bnu"/><path fill="url(#svgIDaW)" class="co_arab3u"/><path fill="url(#svgIDaX)" class="co_arab3u"/><path fill="url(#svgIDaY)" class="co_arab3u"/><path fill="url(#svgIDaZ)" class="c-hifvbsi"/><path fill="url(#svgIDba)" class="c-hifvbsi"/><path fill="url(#svgIDbb)" class="c-hifvbsi"/><path fill="url(#svgIDbc)" clip-rule="evenodd" class="v0z-u3bkw"/><path fill="url(#svgIDbd)" clip-rule="evenodd" class="v0z-u3bkw"/><path fill="url(#svgIDbe)" clip-rule="evenodd" class="v0z-u3bkw"/><path fill="url(#svgIDbf)" clip-rule="evenodd" class="git0cmp4l"/><path fill="url(#svgIDbg)" clip-rule="evenodd" class="git0cmp4l"/><circle fill="url(#svgIDbh)" class="dxcffjstc"/><circle fill="url(#svgIDbi)" class="dxcffjstc"/><circle fill="url(#svgIDbj)" class="dxcffjstc"/><g filter="url(#svgIDbk)"><rect class="qlvfu004i"/></g><path class="klgjqhl0b"/><path fill="url(#svgIDbl)" class="t6dpesbjd"/><g filter="url(#svgIDbm)"><path fill="url(#svgIDbn)" class="akc_f1bta"/><path fill="url(#svgIDbo)" class="akc_f1bta"/><path fill="url(#svgIDbp)" class="akc_f1bta"/><path fill="url(#svgIDbq)" class="akc_f1bta"/></g><g filter="url(#svgIDbr)"><path fill="url(#svgIDbs)" class="nxpmbrbcr"/><path fill="url(#svgIDbt)" class="nxpmbrbcr"/><path fill="url(#svgIDbu)" class="nxpmbrbcr"/></g><path fill="url(#svgIDbv)" class="q6i0w7bth"/><path fill="url(#svgIDbw)" class="q6i0w7bth"/><path fill="url(#svgIDbx)" class="q6i0w7bth"/><path class="k0w6g7gjm"/><path fill="url(#svgIDby)" class="tc3lebban"/><path fill="url(#svgIDbz)" class="ibq5kqeoi"/><ellipse fill="url(#svgIDbA)" transform="rotate(24.61 18.094 7.134)" class="hmmu3sb9r"/><path fill="url(#svgIDbB)" class="maizvoaza"/><path fill="url(#svgIDbC)" class="maizvoaza"/><path fill="url(#svgIDbD)" class="maizvoaza"/><path fill="url(#svgIDbE)" class="d2mxn66fm"/><path fill="url(#svgIDbF)" class="d2mxn66fm"/><path fill="url(#svgIDbG)" class="d2mxn66fm"/><path fill="url(#svgIDbH)" clip-rule="evenodd" class="y19hmi_4j"/><path fill="url(#svgIDbI)" clip-rule="evenodd" class="y19hmi_4j"/><path fill="url(#svgIDbJ)" clip-rule="evenodd" class="y19hmi_4j"/><path fill="url(#svgIDbK)" clip-rule="evenodd" class="gnbw28b_t"/><path fill="url(#svgIDbL)" clip-rule="evenodd" class="gnbw28b_t"/><circle fill="url(#svgIDbM)" transform="matrix(-1 0 0 1 21.003 7.664)" class="ms4f1oj7g"/><circle fill="url(#svgIDbN)" transform="matrix(-1 0 0 1 21.003 7.664)" class="ms4f1oj7g"/><circle fill="url(#svgIDbO)" transform="matrix(-1 0 0 1 21.003 7.664)" class="ms4f1oj7g"/><g filter="url(#svgIDbP)"><rect transform="matrix(-1 0 0 1 19.05 6.414)" class="kv-jd2a1k"/></g><path class="d5abxm6js"/><defs><radialGradient id="svgIDa" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 19.282 10.52)" gradientUnits="userSpaceOnUse"><stop class="i2p0hhbue"/><stop offset=".919" class="m6i64ob9s"/></radialGradient><radialGradient id="svgIDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 -.033 1.45)" gradientUnits="userSpaceOnUse"><stop class="i2p0hhbue"/><stop offset=".919" class="m6i64ob9s"/></radialGradient><radialGradient id="svgIDd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71095 2.35327 -5.20382 -5.99476 18.899 10.781)" gradientUnits="userSpaceOnUse"><stop class="ttoyfzbaw"/><stop offset="1" class="e1ueer7az"/></radialGradient><radialGradient id="svgIDf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 11.656 25.398)" gradientUnits="userSpaceOnUse"><stop class="mtqoh_bre"/><stop offset="1" class="n66bp_w4m"/></radialGradient><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(2.14185 1.875 -.94292 1.07712 7.39 20.367)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="igiy6tomy"/><stop offset="1" class="rpf2vrbvv"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(144.26 2.26 11.022) scale(1.23051 3.4979)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="gbitypbvx"/><stop offset="1" class="tx5lqdb2i"/></radialGradient><radialGradient id="svgIDo" cx="0" cy="0" r="1" gradientTransform="rotate(-134.195 7.064 8.004) scale(2.212 .64075)" gradientUnits="userSpaceOnUse"><stop class="hwnq5ubzm"/><stop offset="1" class="y9oqcminv"/></radialGradient><radialGradient id="svgIDp" cx="0" cy="0" r="1" gradientTransform="rotate(128.536 .685 10.203) scale(4.51441 1.8822)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="rlrqah7ok"/><stop offset="1" class="r-6du_zhr"/></radialGradient><radialGradient id="svgIDq" cx="0" cy="0" r="1" gradientTransform="matrix(6.96877 -7.18752 5.67939 5.50654 3.781 17.68)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="i1avtge0l"/><stop offset="1" class="ifp1_xbmc"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="rotate(-144.397 8.157 13.053) scale(2.17397 2.91043)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64636 -1.26563 1.72963 -2.24994 14.356 28.406)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 11.203 26.227)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="matrix(-.05524 1.73462 -1.20171 -.03827 10.37 11.325)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="u84rtio_o"/><stop offset="1" class="jj1uh6bhe"/></radialGradient><radialGradient id="svgIDF" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 11.379 13.168)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="jg31p_bkv"/><stop offset="1" class="ef2_oackn"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="rotate(137.121 3.046 10.155) scale(3.58218 11.0839)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="rwshkknje"/><stop offset="1" class="la3agyb1u"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="matrix(-.1607 .97723 -3.16368 -.52026 14.262 18.445)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="jony80okq"/><stop offset="1" class="e4agtf5yi"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.30444 .89737 -2.62413 -.89026 14.56 19.08)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="jony80okq"/><stop offset="1" class="e4agtf5yi"/></radialGradient><radialGradient id="svgIDK" cx="0" cy="0" r="1" gradientTransform="matrix(-.28295 .92188 -2.48547 -.76287 14.252 19.398)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="jony80okq"/><stop offset="1" class="e4agtf5yi"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37499 1.625 -1.79466 -1.51854 29.313 10.492)" gradientUnits="userSpaceOnUse"><stop class="em0115xht"/><stop offset="1" class="b-fys1r7u"/></radialGradient><radialGradient id="svgIDN" cx="0" cy="0" r="1" gradientTransform="matrix(2.12183 -1.33219 1.13322 1.80492 26.394 12.7)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="yxyrfz-2l"/><stop offset="1" class="tz_1rgbcq"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 20.343 25.383)" gradientUnits="userSpaceOnUse"><stop class="mtqoh_bre"/><stop offset="1" class="n66bp_w4m"/></radialGradient><radialGradient id="svgIDQ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14186 1.87499 -.94291 -1.07712 24.61 20.352)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="igiy6tomy"/><stop offset="1" class="rpf2vrbvv"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="matrix(.99878 .71875 -2.04315 2.83916 21.468 18.633)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="gbitypbvx"/><stop offset="1" class="tx5lqdb2i"/></radialGradient><radialGradient id="svgIDY" cx="0" cy="0" r="1" gradientTransform="matrix(1.542 -1.58594 .4594 .44667 25.75 18.633)" gradientUnits="userSpaceOnUse"><stop class="hwnq5ubzm"/><stop offset="1" class="y9oqcminv"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="rotate(51.464 -5.154 31.769) scale(4.51441 1.8822)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="rlrqah7ok"/><stop offset="1" class="r-6du_zhr"/></radialGradient><radialGradient id="svgIDaa" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9688 -7.18748 5.67936 -5.50657 28.218 17.664)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="i1avtge0l"/><stop offset="1" class="ifp1_xbmc"/></radialGradient><radialGradient id="svgIDad" cx="0" cy="0" r="1" gradientTransform="matrix(1.76758 -1.26563 1.69437 2.36637 24.81 28.398)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(1.64636 -1.26562 1.72962 2.24995 17.644 28.39)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 20.797 26.21)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDam" cx="0" cy="0" r="1" gradientTransform="matrix(-.05524 1.73462 -1.20171 -.03827 1.738 1.279)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="u84rtio_o"/><stop offset="1" class="jj1uh6bhe"/></radialGradient><radialGradient id="svgIDan" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 2.746 3.121)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="jg31p_bkv"/><stop offset="1" class="ef2_oackn"/></radialGradient><radialGradient id="svgIDao" cx="0" cy="0" r="1" gradientTransform="matrix(2.43827 .18437 -.24868 3.2888 .122 2.37)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="l5v3qe0jr"/><stop offset=".865" class="i_qwr-19p"/></radialGradient><radialGradient id="svgIDap" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 2.746 3.121)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="q5fkj53wg"/><stop offset="1" class="xvt5tsb3a"/></radialGradient><radialGradient id="svgIDaq" cx="0" cy="0" r="1" gradientTransform="matrix(1.49685 3.75 -10.37919 4.14298 19.25 14.304)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="zgtcnu2sf"/><stop offset=".969" class="o3t6sop5m"/></radialGradient><radialGradient id="svgIDas" cx="0" cy="0" r="1" gradientTransform="matrix(0 .50438 -1.56574 0 16.39 16.328)" gradientUnits="userSpaceOnUse"><stop class="kpw5jeb1t"/><stop offset="1" class="axl394b5i"/></radialGradient><radialGradient id="svgIDau" cx="0" cy="0" r="1" gradientTransform="matrix(0 .50438 -1.5408 0 16.414 16.955)" gradientUnits="userSpaceOnUse"><stop class="kpw5jeb1t"/><stop offset="1" class="axl394b5i"/></radialGradient><radialGradient id="svgIDaw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .49784 -1.34351 0 16.64 17.698)" gradientUnits="userSpaceOnUse"><stop class="kpw5jeb1t"/><stop offset="1" class="axl394b5i"/></radialGradient><radialGradient id="svgIDay" cx="0" cy="0" r="1" gradientTransform="matrix(0 .58024 -1.49592 0 16.587 15.43)" gradientUnits="userSpaceOnUse"><stop class="kpw5jeb1t"/><stop offset="1" class="axl394b5i"/></radialGradient><radialGradient id="svgIDaD" cx="0" cy="0" r="1" gradientTransform="rotate(123.38 11.508 13.203) scale(2.43251 2.70978)" gradientUnits="userSpaceOnUse"><stop class="w9zau2kqh"/><stop offset="1" class="abcsnnb1c"/></radialGradient><radialGradient id="svgIDaF" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 6.553 5.993) scale(.57244 .80803)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="svgIDaG" cx="0" cy="0" r="1" gradientTransform="matrix(.12684 -.30799 .46223 .19036 14.74 8.482)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="svgIDaJ" cx="0" cy="0" r="1" gradientTransform="matrix(.89142 -.04952 .06038 1.08682 11.3 7.404)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="svgIDaK" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.48059 2.12951 0 14.36 8.658)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="svgIDaL" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4127 -.6436 0 13.485 7.453)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="svgIDaN" cx="0" cy="0" r="1" gradientTransform="rotate(42.274 -1.278 14.347) scale(4.90812 5.5655)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="i2p5fqtly"/><stop offset="1" class="pw8a02b5q"/></radialGradient><radialGradient id="svgIDaO" cx="0" cy="0" r="1" gradientTransform="matrix(-.41681 2.8343 -1.2521 -.18413 9.43 5.383)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="ltxof3fvo"/><stop offset="1" class="nj0viubvx"/></radialGradient><radialGradient id="svgIDaP" cx="0" cy="0" r="1" gradientTransform="rotate(-176.424 7.54 2.388) scale(1.58784 3.11596)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="id9lp4hub"/><stop offset="1" class="fed4ggbgk"/></radialGradient><radialGradient id="svgIDaQ" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.286 2.82) scale(.79931 .39013)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDaR" cx="0" cy="0" r="1" gradientTransform="matrix(-.23873 1.2464 -1.2988 -.24877 11.504 6.962)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="matrix(-.28889 0 0 -.56127 13.797 7.482)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="matrix(-.26412 0 0 -.57158 13.974 7.505)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDaW" cx="0" cy="0" r="1" gradientTransform="rotate(-163.811 6.265 2.758) scale(.82753 .4039)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDaX" cx="0" cy="0" r="1" gradientTransform="matrix(-.24716 1.2904 -1.34466 -.25755 11.478 6.825)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.79555 -.23096 .11273 -.3883 11.508 7.158)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDba" cx="0" cy="0" r="1" gradientTransform="matrix(-.24742 1.29177 -1.34608 -.25783 11.474 6.829)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDbd" cx="0" cy="0" r="1" gradientTransform="rotate(14.265 -18.47 47.383) scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.52148 1.82813 -.23787 -.06785 12.149 4.274)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDbg" cx="0" cy="0" r="1" gradientTransform="matrix(-.35156 .1875 -.70184 -1.31597 11.985 9.29)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 12.031 7.18)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 9.715 7.664)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbj" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 12.063 8.555)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><radialGradient id="svgIDbl" cx="0" cy="0" r="1" gradientTransform="matrix(.50349 .27238 -.38447 .7107 16.83 8.147)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="har2clbwm"/><stop offset=".684" class="l7cj2r41q"/></radialGradient><radialGradient id="svgIDbo" cx="0" cy="0" r="1" gradientTransform="matrix(-.89142 -.0496 .06048 -1.08682 20.7 7.405)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="svgIDbp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.48059 2.12951 0 17.64 8.658)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="iy_62gb7c"/><stop offset="1" class="eotc9zblf"/></radialGradient><radialGradient id="svgIDbq" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4127 -.6436 0 18.515 7.453)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="svgIDbs" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6317 3.30158 -3.74378 -4.11812 22.681 4.591)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="i2p5fqtly"/><stop offset="1" class="pw8a02b5q"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="matrix(.4168 2.8343 -1.2521 .18413 22.569 5.383)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="ltxof3fvo"/><stop offset="1" class="nj0viubvx"/></radialGradient><radialGradient id="svgIDbu" cx="0" cy="0" r="1" gradientTransform="matrix(1.58475 -.09905 .19437 3.1099 17.085 5.241)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="id9lp4hub"/><stop offset="1" class="fed4ggbgk"/></radialGradient><radialGradient id="svgIDbv" cx="0" cy="0" r="1" gradientTransform="matrix(.76761 -.22286 .10877 .37466 20.463 7.28)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDbw" cx="0" cy="0" r="1" gradientTransform="matrix(.23873 1.2464 -1.2988 .24876 20.496 6.962)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDby" cx="0" cy="0" r="1" gradientTransform="matrix(.28889 0 0 .56127 18.203 7.482)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDbz" cx="0" cy="0" r="1" gradientTransform="matrix(.26412 0 0 .57158 18.025 7.505)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbB" cx="0" cy="0" r="1" gradientTransform="matrix(.79471 -.23072 .11261 .38789 20.487 7.154)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="svgIDbC" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.133 15.825) scale(1.31386 1.3691)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="matrix(.79555 -.23096 .11273 .3883 20.491 7.158)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="svgIDbF" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 6.133 15.83) scale(1.31525 1.37055)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="svgIDbI" cx="0" cy="0" r="1" gradientTransform="rotate(165.735 10.07 4.313) scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbJ" cx="0" cy="0" r="1" gradientTransform="matrix(.52148 1.82813 -.23787 .06785 19.85 4.274)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDbL" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .1875 -.70185 1.31597 20.015 9.29)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbM" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 2.316 .797)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDbN" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 0 1.281)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbO" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 2.348 2.172)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><linearGradient id="svgIDi" x1="6.625" x2="8.406" y1="19.805" y2="18.117" gradientUnits="userSpaceOnUse"><stop class="omfadubst"/><stop offset="1" class="qka3_sxpa"/></linearGradient><linearGradient id="svgIDj" x1="8.328" x2="8.116" y1="19.195" y2="18.984" gradientUnits="userSpaceOnUse"><stop class="w7fy1faaf"/><stop offset="1" class="yik88x48u"/></linearGradient><linearGradient id="svgIDk" x1="5.563" x2="6.844" y1="19.242" y2="19.305" gradientUnits="userSpaceOnUse"><stop offset=".28" class="a8j9w7nsg"/><stop offset="1" class="nmxkbkb2v"/></linearGradient><linearGradient id="svgIDs" x1="2.251" x2="2.836" y1="28.055" y2="28.188" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDu" x1="5.625" x2="5.625" y1="28.414" y2="28.09" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDx" x1="9.756" x2="10.3" y1="28.18" y2="28.163" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDz" x1="12.899" x2="12.899" y1="28.406" y2="28.082" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDD" x1="10.365" x2="10.365" y1="10.046" y2="14.62" gradientUnits="userSpaceOnUse"><stop class="cdk0jybbv"/><stop offset="1" class="sqoomfbpf"/></linearGradient><linearGradient id="svgIDL" x1="13.406" x2="13.641" y1="20.57" y2="20.141" gradientUnits="userSpaceOnUse"><stop offset=".245" class="fuqwctlqz"/><stop offset="1" class="a0aan_bfy"/></linearGradient><linearGradient id="svgIDO" x1="25.301" x2="25.832" y1="9.78" y2="11.023" gradientUnits="userSpaceOnUse"><stop class="yren7o-8v"/><stop offset="1" class="gn8dr-4uj"/></linearGradient><linearGradient id="svgIDS" x1="25.375" x2="23.593" y1="19.789" y2="18.102" gradientUnits="userSpaceOnUse"><stop class="omfadubst"/><stop offset="1" class="qka3_sxpa"/></linearGradient><linearGradient id="svgIDT" x1="23.672" x2="23.884" y1="19.18" y2="18.969" gradientUnits="userSpaceOnUse"><stop class="w7fy1faaf"/><stop offset="1" class="yik88x48u"/></linearGradient><linearGradient id="svgIDU" x1="26.437" x2="25.156" y1="19.227" y2="19.289" gradientUnits="userSpaceOnUse"><stop offset=".28" class="a8j9w7nsg"/><stop offset="1" class="nmxkbkb2v"/></linearGradient><linearGradient id="svgIDac" x1="29.749" x2="29.164" y1="28.039" y2="28.172" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDae" x1="26.375" x2="26.375" y1="28.398" y2="28.074" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDah" x1="22.244" x2="21.7" y1="28.164" y2="28.147" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDaj" x1="19.101" x2="19.101" y1="28.391" y2="28.066" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDar" x1="17.246" x2="17.246" y1="17.108" y2="16.627" gradientUnits="userSpaceOnUse"><stop class="jh_z6ab-a"/><stop offset="1" class="a-v94sblr"/></linearGradient><linearGradient id="svgIDat" x1="17.256" x2="17.256" y1="17.735" y2="17.254" gradientUnits="userSpaceOnUse"><stop class="jh_z6ab-a"/><stop offset="1" class="a-v94sblr"/></linearGradient><linearGradient id="svgIDav" x1="17.375" x2="17.375" y1="18.468" y2="17.992" gradientUnits="userSpaceOnUse"><stop class="jh_z6ab-a"/><stop offset="1" class="a-v94sblr"/></linearGradient><linearGradient id="svgIDax" x1="17.121" x2="17.582" y1="16.656" y2="15.765" gradientUnits="userSpaceOnUse"><stop class="jh_z6ab-a"/><stop offset=".891" class="a-v94sblr"/></linearGradient><linearGradient id="svgIDaB" x1="24.207" x2="19.801" y1="11.836" y2="17.867" gradientUnits="userSpaceOnUse"><stop class="auqu5kb-l"/><stop offset="1" class="pputyyb_m"/></linearGradient><linearGradient id="svgIDaI" x1="11.63" x2="14.654" y1="8.188" y2="8.37" gradientUnits="userSpaceOnUse"><stop class="o0r6oh8jt"/><stop offset="1" class="wyzmbm91v"/></linearGradient><linearGradient id="svgIDaS" x1="11.595" x2="11.438" y1="7.353" y2="7.365" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDaV" x1="-.007" x2=".19" y1=".052" y2=".117" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDaY" x1="11.623" x2="11.316" y1="7.193" y2="7.278" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDbb" x1="11.568" x2="11.405" y1="7.233" y2="7.246" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDbc" x1="11.977" x2="10.903" y1="5.32" y2="6.227" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbf" x1="11.406" x2="12.758" y1="8.93" y2="10.758" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><linearGradient id="svgIDbn" x1="20.37" x2="17.346" y1="8.188" y2="8.37" gradientUnits="userSpaceOnUse"><stop class="l7w6j-bmv"/><stop offset="1" class="o_ul3db6n"/></linearGradient><linearGradient id="svgIDbx" x1="20.405" x2="20.562" y1="7.353" y2="7.365" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDbA" x1="18.018" x2="18.215" y1="7.093" y2="7.157" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbD" x1="20.376" x2="20.684" y1="7.193" y2="7.278" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="svgIDbG" x1="20.432" x2="20.594" y1="7.233" y2="7.246" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="svgIDbH" x1="20.023" x2="21.097" y1="5.32" y2="6.227" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbK" x1="20.593" x2="19.241" y1="8.93" y2="10.758" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><filter id="svgIDc" width="10.808" height="5.007" x="8.491" y="10.481" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.403922 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.305882 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23635" result="effect2_innerShadow_3987_23635"/></filter><filter id="svgIDe" width="7.106" height="3.139" x="10.204" y="11.571" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23635" stdDeviation=".2"/></filter><filter id="svgIDl" width="4.146" height="5.805" x="2.788" y="19.992" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.560784 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23635" result="effect2_innerShadow_3987_23635"/></filter><filter id="svgIDm" width="9.426" height="8.574" x="2.717" y="9.792" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDn" width="5.878" height="6.781" x="2.144" y="13.672" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDr" width="5.139" height="3.208" x="2.051" y="25.406" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDv" width="2.686" height="1.05" x="2.698" y="25.406" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.670588 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDw" width="4.9" height="3.308" x="9.456" y="25.398" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDA" width="2.288" height="1.065" x="9.756" y="25.398" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDC" width="5.149" height="5.149" x="5.666" y="10.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23635" stdDeviation=".125"/></filter><filter id="svgIDG" width="1.796" height="1.427" x="13.37" y="17.731" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDV" width="4.146" height="5.805" x="25.066" y="19.977" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.560784 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23635" result="effect2_innerShadow_3987_23635"/></filter><filter id="svgIDW" width="9.426" height="8.574" x="19.857" y="9.776" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDX" width="5.878" height="6.781" x="23.978" y="13.656" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDab" width="5.139" height="3.208" x="24.61" y="25.391" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDaf" width="2.686" height="1.05" x="26.615" y="25.391" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.694118 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDag" width="4.9" height="3.308" x="17.344" y="25.383" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDak" width="2.288" height="1.065" x="20.156" y="25.383" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDaz" width="5.984" height="7.891" x="7.785" y="11.414" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23635" stdDeviation=".25"/></filter><filter id="svgIDaA" width="7.313" height="7.219" x="17.582" y="10.961" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23635" stdDeviation=".25"/></filter><filter id="svgIDaC" width="4.063" height="3.831" x="25.494" y="9.957" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23635" stdDeviation=".3"/></filter><filter id="svgIDaE" width="2.322" height="3.133" x="16.526" y="15.606" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23635" stdDeviation=".25"/></filter><filter id="svgIDaH" width="4.733" height="5.535" x="10.171" y="5.092" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.337255 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDaM" width="6.724" height="5.754" x="8.482" y="3.36" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.266667 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.137255 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23635" result="effect2_innerShadow_3987_23635"/></filter><filter id="svgIDbk" width="1.258" height=".393" x="12.95" y="6.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.121569 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDbm" width="4.733" height="5.535" x="17.346" y="5.092" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.376471 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter><filter id="svgIDbr" width="6.724" height="5.754" x="16.694" y="3.36" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.266667 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.137255 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23635" result="effect2_innerShadow_3987_23635"/></filter><filter id="svgIDbP" width="1.258" height=".393" x="17.792" y="6.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.121569 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23635"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-wrestling-medium" /></template>
<style>
.a-v94sblr {
  stop-color: var(--svg-color--9d7270, #9D7270);
  stop-opacity: 0;
}

.a0aan_bfy {
  stop-color: var(--svg-color--946466, #946466);
  stop-opacity: 0;
}

.a0q036gjd {
  stop-color: var(--svg-color--504d4e, #504D4E);
}

.a3ce-6b4m {
  fill: var(--svg-color--2797f6, #2797F6);
  d: path("M6.826 10.546a2.696 2.696 0 0 1 3.753 3.873l-3.262 3.178a2.71 2.71 0 1 1-3.77-3.891l3.28-3.16Z");
}

.a5dbyd6tf {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
}

.a8j9w7nsg {
  stop-color: var(--svg-color--194ec0, #194EC0);
}

.abcsnnb1c {
  stop-color: var(--svg-color--b68976, #B68976);
  stop-opacity: 0;
}

.afg3zhs8x {
  stroke: var(--svg-color--ba937f, #BA937F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.66 12.29c.073 1.374 2.032 4.874 4.235 6.14");
}

.ak32k0b7k {
  stop-color: var(--svg-color--695d73, #695D73);
}

.akc_f1bta {
  d: path("M17.375 6.666c.041-.846.315-1.254.444-1.374h3.943l.066 3.343c-.915 2.242-3.71 2.338-4.127 1.527c-.417-.811-.373-2.516-.326-3.496Z");
}

.al_auo8nl {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
  stop-opacity: 0;
}

.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.at2v7wy3p {
  d: path("M13.45 7.505V7.5c0-.339.145-.613.324-.613c.179 0 .324.274.324.613v.004h-.648Z");
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

.b-ce31bju {
  d: path("M14.861 7.685a1.06 1.06 0 0 1-.272-.483h-.19V8.39c.227.145.552.122.648-.095c.082-.185.02-.417-.186-.61Z");
}

.b-fys1r7u {
  stop-color: var(--svg-color--9e7c62, #9E7C62);
}

.b5skg8e-v {
  stop-color: var(--svg-color--522470, #522470);
}

.ba6qsgbyc {
  d: path("M13.657 7.505a.653.653 0 0 1-.005-.076c0-.196.083-.355.186-.355s.186.159.186.355a.676.676 0 0 1-.005.076h-.362Z");
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

.cdk0jybbv {
  stop-color: var(--svg-color--35aaf7, #35AAF7);
}

.chy2-3bdx {
  d: path("m22.156 26.328l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.262-.441.564-.438.802c.003.155.143.273.298.273h3.964a.25.25 0 0 0 .25-.25v-1.813Z");
}

.co_arab3u {
  d: path("m11.678 8.11l-.218-1.575a.795.795 0 0 0 .218 1.574Z");
}

.con5gggje {
  fill: var(--svg-color--ab8067, #AB8067);
  fill-rule: evenodd;
  d: path("M13.609 18.809a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.69l-1.215-.716a.4.4 0 0 1-.142-.547Z");
}

.ct6_m01bp {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
}

.d2mxn66fm {
  d: path("m20.325 8.114l.219-1.576a.796.796 0 0 1-.219 1.576Z");
}

.d5abxm6js {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M18.695 8.923a.124.124 0 0 0-.124-.124h-.608a.124.124 0 0 0 0 .248h.608a.124.124 0 0 0 .124-.124Z");
}

.d5mpwjb6n {
  fill: var(--svg-color--9d91a7, #9D91A7);
  d: path("m27.297 26.182l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075l.22.874l-2.004-.158Z");
}

.deb_iib1u {
  fill: var(--svg-color--a38069, #A38069);
  d: path("M15.464 16.718a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.dhqfwlbde {
  fill: var(--svg-color--a38069, #A38069);
  d: path("M15.503 17.345c0-.215.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.dm4voe-la {
  d: path("M0 0h2.371v3.351H0z");
}

.dryamrx6b {
  d: path("M15.503 17.345c0-.215.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.dxcffjstc {
  cx: 10.996px;
  cy: 7.664px;
  r: 1.281px;
}

.e1hyixrny {
  fill: var(--svg-color--a57c63, #A57C63);
  d: path("m16.074 11.629l.536-.516c.123-.11.461-.332.824-.332h.988a.477.477 0 1 1 0 .953h-.866a.224.224 0 0 0-.202.13l-.033.068a.344.344 0 0 0-.002.288l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.056-3.902 2.229c-2.386.057-3.712-1.182-4.258-1.691a9.14 9.14 0 0 0-.108-.1l-.103-.092a1.15 1.15 0 1 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.047.11.098.17.154c.497.454 1.236 1.131 2.533 1.131c.391 0 .884-.013 1.408-.336c.51-.314.937-.699 1.167-.95a.667.667 0 0 1 .124-.108Z");
}

.e1ueer7az {
  stop-color: var(--svg-color--845a4d, #845A4D);
  stop-opacity: 0;
}

.e4agtf5yi {
  stop-color: var(--svg-color--8c5772, #8C5772);
}

.e4nvf0jxv {
  d: path("m24.855 20.288l1.082-1.007l1.149-1.023l-3.133-1.906a78.474 78.474 0 0 1-1.4 1.66a.05.05 0 0 0 .003.068l2.23 2.207a.05.05 0 0 0 .07 0Z");
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

.f4dftzbyn {
  d: path("m2.919 25.482l-.66 2.621a.25.25 0 0 0 .242.311h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.865-.763-1.157a86.272 86.272 0 0 1-1.696-.9l.376-.719a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076Z");
}

.fed4ggbgk {
  stop-color: var(--svg-color--634d4a, #634D4A);
  stop-opacity: 0;
}

.fk4zrip8m {
  stop-color: var(--svg-color--483159, #483159);
}

.fniuksbbx {
  fill: var(--svg-color--714244, #714244);
  d: path("m16.47 11.457l-.59.57l.297 1.114l1.425-.505l-.08-.117a.316.316 0 0 1-.023-.311l.03-.064a.205.205 0 0 1 .185-.118h.42a.437.437 0 0 0 0-.874h-.907c-.333 0-.643.203-.756.305Z");
}

.fodk42bev {
  d: path("M13.95 5.87c.692 0 1.023-.392 1.056-.883c0-.693-.53-.84-.735-.862c-.231-.025-.322-.05-.644-.277a.954.954 0 0 0-.961-.103c-.157.074-.504.112-.752.037c-.412-.124-.734-.12-1.052.124c-.22.17-.383.17-.648.17c-.363 0-.671.162-.904.338c-.694.525-.614 2.331-.272 3.347c.328.97.821 1.085 1.234 1.048c.497-.045.623-.421.697-.735c.06-.25.212-1.046.281-1.307c.143-.066.456-.09.561-.5c.106-.41.52-.457.801-.43c.17.017.644.034 1.337.034Z");
}

.ft5dv1b6b {
  fill: none;
}

.fuqwctlqz {
  stop-color: var(--svg-color--946466, #946466);
}

.fwkra3bhz {
  d: path("M16.086 15.43a.384.384 0 1 0 0 .77h.518a.064.064 0 1 1 0 .128h1.158V16.2h.254l-.31-.31a1.568 1.568 0 0 0-1.108-.458h-.512Z");
}

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
}

.gawbh7bii {
  d: path("M10.647 10.626a2.697 2.697 0 0 0-3.821-.08l-3.234 3.126l-.045.034c-.067.064-.13.13-.188.2l-.43.43c-.373.325-1.069 1.252-.66 2.844c.372 1.447.778 2.733.938 3.239c.003.01.01.02.02.026a.052.052 0 0 0 .027.008h3.025a.05.05 0 0 0 .05-.055c-.074-.714-.268-1.757-.268-1.757l.876-.735c.133-.09.26-.193.38-.309l3.261-3.178a2.696 2.696 0 0 0 .069-3.793Z");
}

.gbitypbvx {
  stop-color: var(--svg-color--956c5a, #956C5A);
}

.git0cmp4l {
  fill-rule: evenodd;
  d: path("M11.102 8.354a.25.25 0 0 1 .325.138c.1.247.285.645.511 1.038c.23.399.488.767.732.975a.25.25 0 1 1-.324.38c-.312-.266-.606-.696-.841-1.105a9.538 9.538 0 0 1-.541-1.1a.25.25 0 0 1 .138-.326Z");
}

.gn8dr-4uj {
  stop-color: var(--svg-color--937861, #937861);
  stop-opacity: 0;
}

.gnbw28b_t {
  fill-rule: evenodd;
  d: path("M20.898 8.354a.25.25 0 0 0-.326.138a9.03 9.03 0 0 1-.51 1.038c-.23.399-.489.767-.733.975a.25.25 0 1 0 .325.38c.312-.266.605-.696.84-1.105a9.55 9.55 0 0 0 .541-1.1a.25.25 0 0 0-.137-.326Z");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gyqgpnbjt {
  d: path("M20.156 26.188v-.755a.05.05 0 0 1 .05-.05h1.989a.05.05 0 0 1 .05.055l-.089.89v.02l-2-.16Z");
}

.h-yw9d58o {
  d: path("m11.697 8.203l-.21-1.521a.768.768 0 0 0 .21 1.52Z");
}

.har2clbwm {
  stop-color: var(--svg-color--87625a, #87625A);
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

.hmmu3sb9r {
  cx: 18.094px;
  cy: 7.134px;
  rx: 0.068px;
  ry: 0.093px;
}

.hr3mxybxz {
  fill: var(--svg-color--a47c6e, #A47C6E);
  fill-rule: evenodd;
  d: path("M13.025 19.63a.4.4 0 0 1 .56-.085l.746.547a.4.4 0 1 1-.473.645l-.746-.547a.4.4 0 0 1-.087-.56Z");
}

.hwnq5ubzm {
  stop-color: var(--svg-color--2670da, #2670DA);
}

.i_emxkhmq {
  stop-color: var(--svg-color--442f88, #442F88);
}

.i_qwr-19p {
  stop-color: var(--svg-color--a07364, #A07364);
}

.i1avtge0l {
  stop-color: var(--svg-color--2f80be, #2F80BE);
  stop-opacity: 0;
}

.i2p0hhbue {
  stop-color: var(--svg-color--734548, #734548);
}

.i2p5fqtly {
  stop-color: var(--svg-color--52343b, #52343B);
}

.ibq5kqeoi {
  d: path("M18.343 7.505a.653.653 0 0 0 .004-.076c0-.196-.083-.355-.186-.355c-.102 0-.185.159-.185.355c0 .026.001.051.004.076h.363Z");
}

.id9lp4hub {
  stop-color: var(--svg-color--634d4a, #634D4A);
}

.idjwbh6kk {
  d: path("m16.074 11.629l.536-.516c.123-.11.461-.332.824-.332h.988a.477.477 0 1 1 0 .953h-.866a.224.224 0 0 0-.202.13l-.033.068a.344.344 0 0 0-.002.288l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.056-3.902 2.229c-2.386.057-3.712-1.182-4.258-1.691a9.14 9.14 0 0 0-.108-.1l-.103-.092a1.15 1.15 0 1 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.047.11.098.17.154c.497.454 1.236 1.131 2.533 1.131c.391 0 .884-.013 1.408-.336c.51-.314.937-.699 1.167-.95a.667.667 0 0 1 .124-.108Z");
}

.ifp1_xbmc {
  stop-color: var(--svg-color--2f80be, #2F80BE);
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.igiy6tomy {
  stop-color: var(--svg-color--90595f, #90595F);
}

.ij--3abxg {
  d: path("m7.145 20.303l-1.082-1.006l-1.149-1.024l3.133-1.906a77.83 77.83 0 0 0 1.4 1.66a.05.05 0 0 1-.003.068l-2.23 2.207a.05.05 0 0 1-.07.001Z");
}

.iy_62gb7c {
  stop-color: var(--svg-color--946660, #946660);
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

.k0w6g7gjm {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.91 7.505h1.044c0-.414-.233-.75-.521-.75c-.289 0-.523.336-.523.75Z");
}

.k56umfb4k {
  fill-rule: evenodd;
  d: path("M27.133 12.318a.1.1 0 0 0-.09-.14l-3.873-.058l.035-2.34l4.25.06c1.653.024 2.653 1.726 1.919 3.234l-1.186 2.545l-2.062-1.02l1.007-2.281Z");
}

.k8s01tfdv {
  stop-color: var(--svg-color--5e5663, #5E5663);
  stop-opacity: 0;
}

.kc2hp5b1b {
  d: path("M11.844 26.204v-.756a.05.05 0 0 0-.05-.05H9.805a.05.05 0 0 0-.05.055l.089.89v.02l2-.159Z");
}

.kgukkhbth {
  stop-color: var(--svg-color--5e5663, #5E5663);
}

.klgjqhl0b {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M13.305 8.923c0-.069.056-.124.124-.124h.607a.124.124 0 0 1 0 .248h-.607a.124.124 0 0 1-.124-.124Z");
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.kpw5jeb1t {
  stop-color: var(--svg-color--af8c7c, #AF8C7C);
}

.krjt31z8n {
  cx: 17.687px;
  cy: 17.173px;
  fill: var(--svg-color--a57f6a, #A57F6A);
  rx: 0.661px;
  ry: 1.066px;
}

.kv-jd2a1k {
  width: 1.258px;
  height: 0.293px;
  fill: var(--svg-color--4b3635, #4B3635);
  rx: 0.146px;
}

.kwmheoo9h {
  d: path("M26.406 10.557a.3.3 0 0 0-.024.6l.024-.6Zm1.29.354l.013-.3l-.012.3Zm.899 1.342l.282.103l-.282-.103Zm-.514.532a.3.3 0 0 0 .563.207l-.563-.207Zm-1.7-1.628l1.303.053l.025-.6l-1.303-.053l-.024.6Zm1.932.993l-.232.635l.563.207l.233-.636l-.564-.206Zm-.629-.94a.7.7 0 0 1 .63.94l.563.206a1.3 1.3 0 0 0-1.168-1.745l-.025.6Z");
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

.ltxof3fvo {
  stop-color: var(--svg-color--624646, #624646);
}

.m6i64ob9s {
  stop-color: var(--svg-color--8e6259, #8E6259);
}

.maizvoaza {
  d: path("m20.322 8.11l.218-1.575a.795.795 0 0 1-.218 1.574Z");
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

.mtqoh_bre {
  stop-color: var(--svg-color--ab8075, #AB8075);
}

.mxco7gaxf {
  d: path("m9.172 21.953l-2.039-1.805l2.156-2.187a68.14 68.14 0 0 0 1.903 2.277c.67.77.758 1.77.738 2.262l-.102 2.898H9.805c-.068-.734-.211-2.307-.242-2.726a.954.954 0 0 0-.39-.719Z");
}

.myma9ccll {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m2.919 25.482l-.66 2.621a.25.25 0 0 0 .242.311h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.865-.763-1.157a86.272 86.272 0 0 1-1.696-.9l.376-.719a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076Z");
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

.ng2hgzbhn {
  stop-color: var(--svg-color--bf9580, #BF9580);
}

.nj0viubvx {
  stop-color: var(--svg-color--624646, #624646);
  stop-opacity: 0;
}

.nm5hd83mo {
  d: path("m22.828 21.938l2.039-1.805l-2.156-2.188a69.097 69.097 0 0 1-1.903 2.278c-.67.77-.758 1.77-.738 2.261l.102 2.899h2.023c.068-.735.211-2.308.242-2.727a.954.954 0 0 1 .39-.718Z");
}

.nmxkbkb2v {
  stop-color: var(--svg-color--115ecc, #115ECC);
  stop-opacity: 0;
}

.nrp5bhxwt {
  d: path("m2.928 14.336l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.757a.05.05 0 0 1-.05.055H3.255a.05.05 0 0 1-.047-.034a63.154 63.154 0 0 1-.938-3.24c-.409-1.591.287-2.517.66-2.843Z");
}

.nxpmbrbcr {
  d: path("M18.05 5.87c-.692 0-1.023-.392-1.056-.883c0-.693.53-.84.735-.862c.231-.025.322-.05.644-.277a.954.954 0 0 1 .961-.103c.157.074.504.112.752.037c.412-.124.734-.12 1.052.124c.22.17.383.17.648.17c.363 0 .671.162.904.338c.694.525.614 2.331.272 3.347c-.328.97-.821 1.085-1.234 1.048c-.497-.045-.623-.421-.698-.735c-.059-.25-.211-1.046-.28-1.307c-.143-.066-.456-.09-.561-.5c-.106-.41-.52-.457-.801-.43c-.17.017-.644.034-1.337.034Z");
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

.o3t6sop5m {
  stop-color: var(--svg-color--834f6a, #834F6A);
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

.ont54vbxw {
  fill: var(--svg-color--a38069, #A38069);
  d: path("M16.086 15.43a.384.384 0 1 0 0 .77h.518a.064.064 0 1 1 0 .128h1.158V16.2h.254l-.31-.31a1.568 1.568 0 0 0-1.108-.458h-.512Z");
}

.oybn7vbqt {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
}

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.pputyyb_m {
  stop-color: var(--svg-color--b28e77, #B28E77);
  stop-opacity: 0;
}

.psd98zbad {
  fill: var(--svg-color--a8836c, #A8836C);
  fill-rule: evenodd;
  d: path("M15.127 18.109a.4.4 0 0 1-.188.533l-.996.477a.4.4 0 0 1-.346-.722l.996-.477a.4.4 0 0 1 .534.189Z");
}

.puraqfb4y {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.046px;
  rx: 1.732px;
}

.pw8a02b5q {
  stop-color: var(--svg-color--492b38, #492B38);
}

.pxj138bcc {
  width: 3.464px;
  height: 4.574px;
  rx: 1.732px;
}

.pxzeppb5u {
  fill: var(--svg-color--9f7a62, #9F7A62);
  fill-rule: evenodd;
  d: path("M23.727 11.603c.627.168 1 .811.833 1.438c-.25.938-.826 1.86-1.893 3.008c-1.075 1.158-2.67 2.249-4.615 2.414a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.833Z");
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.q2gydu3zd {
  stop-color: var(--svg-color--3e3a3f, #3E3A3F);
  stop-opacity: 0;
}

.q5fkj53wg {
  stop-color: var(--svg-color--a36968, #A36968);
}

.q6i0w7bth {
  d: path("m20.303 8.203l.21-1.521a.768.768 0 0 1-.21 1.52Z");
}

.qcr3xcbrj {
  d: path("M19.316 9.068h2.371v3.351h-2.371z");
}

.qihskpbeg {
  stop-color: var(--svg-color--524e8d, #524E8D);
  stop-opacity: 0;
}

.qka3_sxpa {
  stop-color: var(--svg-color--2b7ec4, #2B7EC4);
}

.qlvfu004i {
  width: 1.258px;
  height: 0.293px;
  x: 12.95px;
  y: 6.414px;
  fill: var(--svg-color--4b3635, #4B3635);
  rx: 0.146px;
}

.qq1642b9j {
  fill: var(--svg-color--ab8067, #AB8067);
  fill-rule: evenodd;
  d: path("M13.373 18.277a.4.4 0 0 1 .55-.135c.404.245.859.47 1.375.648a.4.4 0 1 1-.26.756a7.88 7.88 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549Z");
}

.qxca1sbyr {
  fill-rule: evenodd;
  d: path("M23.727 11.603c.627.168 1 .811.833 1.438c-.25.938-.826 1.86-1.893 3.008c-1.075 1.158-2.67 2.249-4.615 2.414a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.833Z");
}

.r-6du_zhr {
  stop-color: var(--svg-color--227be5, #227BE5);
  stop-opacity: 0;
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.r4i2vf4ry {
  d: path("m29.081 25.466l.66 2.621a.25.25 0 0 1-.242.311h-4.441c-.102 0-.196-.06-.22-.158c-.127-.504.196-.866.763-1.157a85.685 85.685 0 0 0 1.696-.901l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075Z");
}

.r4wrwpygj {
  d: path("M14.624 6.666c-.04-.846-.315-1.254-.444-1.374h-3.943l-.066 3.343c.915 2.242 3.71 2.338 4.127 1.527c.418-.811.373-2.516.326-3.496Z");
}

.r9debcckm {
  fill: var(--svg-color--a97e73, #A97E73);
  d: path("m3.89 22.11l-.57-1.727l2.876-.39c.013.093.071.51.203 1.429c.13.919-.125 1.664-.375 2.203l-1.22 2.172H2.939c.245-.771.843-2.77.93-3.031c.085-.262.085-.48.023-.657Z");
}

.rh5emhbls {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M24.02 11.836c-.26 1.312-1.738 4.244-5.563 5.469");
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
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

.rpf2vrbvv {
  stop-color: var(--svg-color--90595f, #90595F);
  stop-opacity: 0;
}

.rwshkknje {
  stop-color: var(--svg-color--9f6254, #9F6254);
  stop-opacity: 0;
}

.ryafw47dj {
  fill: var(--svg-color--ab8067, #AB8067);
  fill-rule: evenodd;
  d: path("M13.393 19.116a.45.45 0 0 1 .624-.122l.973.657a.45.45 0 0 1-.503.746l-.973-.657a.45.45 0 0 1-.121-.624Z");
}

.sgbzszd0s {
  fill: var(--svg-color--a38069, #A38069);
  d: path("M15.846 18.082c0-.212.173-.384.386-.384h1.385l.308.77H16.23a.385.385 0 0 1-.385-.386Z");
}

.shic-ydjf {
  stop-color: var(--svg-color--2e2d2f, #2E2D2F);
}

.sqoomfbpf {
  stop-color: var(--svg-color--39a2f4, #39A2F4);
}

.sqykkfq6i {
  fill-rule: evenodd;
  d: path("M8.23 11.343a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.161 4.242 5.911c.539.336.765 1.006.43 1.545a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t06ea0i_l {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.09 7.505h-1.044c0-.414.233-.75.522-.75c.288 0 .522.336.522.75Z");
}

.t6dpesbjd {
  d: path("M17.138 7.685a1.08 1.08 0 0 0 .273-.483h.19V8.39c-.227.145-.552.122-.648-.095c-.083-.185-.021-.417.185-.61Z");
}

.tc3lebban {
  d: path("M18.55 7.505V7.5c0-.339-.146-.613-.324-.613c-.18 0-.324.274-.324.613v.004h.647Z");
}

.th4vgcc8j {
  d: path("M21.353 10.61a2.697 2.697 0 0 1 3.821-.08l3.234 3.126l.045.034c.067.064.13.13.188.2l.43.43c.373.326 1.069 1.252.66 2.844a62.473 62.473 0 0 1-.938 3.24a.047.047 0 0 1-.02.025a.053.053 0 0 1-.027.009h-3.025a.05.05 0 0 1-.05-.055c.075-.715.268-1.758.268-1.758l-.876-.735a2.72 2.72 0 0 1-.38-.308l-3.261-3.178a2.696 2.696 0 0 1-.069-3.794Z");
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

.u0hatmkqb {
  d: path("M15.464 16.718a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.u84rtio_o {
  stop-color: var(--svg-color--bd9680, #BD9680);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ui4gszb6g {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m9.844 26.343l-.088-.89a.05.05 0 0 1 .05-.055h1.988a.05.05 0 0 1 .05.05v.767c.559.262 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.155-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.v0z-u3bkw {
  fill-rule: evenodd;
  d: path("M12.178 3.598a.25.25 0 0 1 .162.314l-.95 2.969a.25.25 0 0 1-.476-.152l.95-2.97a.25.25 0 0 1 .314-.161Z");
}

.v8d4ab1_b {
  fill-rule: evenodd;
  d: path("M13.025 19.63a.4.4 0 0 1 .56-.085l.746.547a.4.4 0 1 1-.473.645l-.746-.547a.4.4 0 0 1-.087-.56Z");
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w7fy1faaf {
  stop-color: var(--svg-color--245dc6, #245DC6);
}

.w9zau2kqh {
  stop-color: var(--svg-color--b68976, #B68976);
}

.wbqgxvibx {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m29.081 25.466l.66 2.621a.25.25 0 0 1-.242.311h-4.441c-.102 0-.196-.06-.22-.158c-.127-.504.196-.866.763-1.157a85.685 85.685 0 0 0 1.696-.901l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075Z");
}

.wicb2kbvo {
  fill: var(--svg-color--2797f6, #2797F6);
  d: path("m2.928 14.336l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.757a.05.05 0 0 1-.05.055H3.255a.05.05 0 0 1-.047-.034a63.154 63.154 0 0 1-.938-3.24c-.409-1.591.287-2.517.66-2.843Z");
}

.wr624mrxa {
  d: path("M15.846 18.082c0-.212.173-.384.386-.384h1.385l.308.77H16.23a.385.385 0 0 1-.385-.386Z");
}

.wyzmbm91v {
  stop-color: var(--svg-color--a1786f, #A1786F);
}

.xexidbngb {
  fill-rule: evenodd;
  d: path("M13.609 18.809a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.69l-1.215-.716a.4.4 0 0 1-.142-.547Z");
}

.xfc-qx9ex {
  d: path("m9.844 26.343l-.088-.89a.05.05 0 0 1 .05-.055h1.988a.05.05 0 0 1 .05.05v.767c.559.262 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.155-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25v-1.813Z");
}

.xfej-jbum {
  fill-rule: evenodd;
  d: path("M13.373 18.277a.4.4 0 0 1 .55-.135c.404.245.859.47 1.375.648a.4.4 0 1 1-.26.756a7.88 7.88 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549Z");
}

.xpassgbnv {
  stroke: var(--svg-color--b18472, #B18472);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.804 13.484c.38.25 1.469.722 2.781.61c1.64-.141 2.656-1.048 3.125-1.923");
}

.xvt5tsb3a {
  stop-color: var(--svg-color--a36968, #A36968);
  stop-opacity: 0;
}

.xvumooy0c {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.046px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.y0z19fbvl {
  fill: var(--svg-color--a97e73, #A97E73);
  d: path("m28.11 22.094l.57-1.727l-2.876-.39c-.013.093-.071.51-.203 1.43c-.13.918.125 1.663.375 2.202l1.22 2.172h1.866c-.245-.77-.844-2.77-.93-3.031c-.085-.262-.085-.48-.023-.656Z");
}

.y19hmi_4j {
  fill-rule: evenodd;
  d: path("M19.822 3.598a.25.25 0 0 0-.162.314l.949 2.969a.25.25 0 0 0 .476-.152l-.95-2.97a.25.25 0 0 0-.314-.161Z");
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

.yg6pzzb4x {
  width: 0.764px;
  height: 1.4px;
  x: 17.093px;
  y: 15.721px;
  fill: var(--svg-color--a6826a, #A6826A);
  rx: 0.382px;
}

.yik88x48u {
  stop-color: var(--svg-color--245dc6, #245DC6);
  stop-opacity: 0;
}

.yren7o-8v {
  stop-color: var(--svg-color--937861, #937861);
}

.yxyrfz-2l {
  stop-color: var(--svg-color--a75461, #A75461);
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.zgtcnu2sf {
  stop-color: var(--svg-color--a17471, #A17471);
  stop-opacity: 0;
}

.zhbm06bnu {
  rx: 0.068px;
  ry: 0.093px;
}

.zj8amkhtl {
  fill: var(--svg-color--ad8569, #AD8569);
  fill-rule: evenodd;
  d: path("M8.23 11.343a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.161 4.242 5.911c.539.336.765 1.006.43 1.545a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

.zjmmjyoar {
  stop-color: var(--svg-color--554f5c, #554F5C);
}

</style>
