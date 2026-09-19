<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iiAhbGz)" class="t7e9ekbly"/><path fill="url(#iqAcP4q)" class="t7e9ekbly"/><path fill="url(#iYaYOcc)" class="t7e9ekbly"/><path fill="url(#iXn7tsD)" class="t7e9ekbly"/><path fill="url(#iHgfLya)" class="t7e9ekbly"/><path fill="url(#ilD1Psd)" class="t7e9ekbly"/><path fill="url(#iiMJq3b)" class="t7e9ekbly"/><path fill="url(#i1DPc8d)" class="nm08ve9ry"/><path fill="url(#izWfgjb)" class="f2p5dfb8i"/><path fill="url(#iszbMtb)" class="q_1v6cmzc"/><path fill="url(#iO6dWLC)" class="q_1v6cmzc"/><path fill="url(#iH18ryU)" class="q_1v6cmzc"/><path fill="url(#i6Ykf8d)" class="osioyzhgj"/><path fill="url(#iwJG3xe)" class="osioyzhgj"/><path fill="url(#ia1wbgb)" class="osioyzhgj"/><path fill="url(#iMSVcxe)" class="a_303v8zt"/><path fill="url(#iqlnLzb)" class="a_303v8zt"/><path fill="url(#i1DPc8d)" class="nm08ve9ry"/><path fill="url(#izWfgjb)" class="f2p5dfb8i"/><g filter="url(#iVOsBXc)"><path class="y-u26bckg"/></g><g filter="url(#ixFDjyd)"><path fill="url(#iykr42d)" class="r10bjccqq"/></g><path fill="url(#iNwHKmc)" class="qsu575jak"/><path fill="url(#im99Eac)" class="qsu575jak"/><path fill="url(#idKTWjA)" class="qsu575jak"/><path fill="url(#itZF5Nb)" class="qsu575jak"/><path fill="url(#iu71slc)" class="qsu575jak"/><path fill="url(#iV3vUId)" class="qsu575jak"/><path fill="url(#iCf54Cb)" class="lkxa08fsn"/><path fill="url(#ihq1NHc)" class="lkxa08fsn"/><path fill="url(#iz03z7x)" class="lkxa08fsn"/><path fill="url(#iCLdqBc)" class="lkxa08fsn"/><path fill="url(#iHDS0ld)" class="lkxa08fsn"/><path fill="url(#ibv28Rd)" class="lkxa08fsn"/><path fill="url(#itG6hAu)" class="txkutm4dn"/><path clip-rule="evenodd" class="uy62st-sf"/><path fill="url(#ihxMcsd)" clip-rule="evenodd" class="croudib4q"/><path fill="url(#iZ3npSb)" clip-rule="evenodd" class="croudib4q"/><path fill="url(#iiDpxJe)" clip-rule="evenodd" class="croudib4q"/><path fill="url(#iHeGdRb)" clip-rule="evenodd" class="croudib4q"/><g filter="url(#i5J5Ytc)"><path class="jmlpl5bgc"/></g><path fill="url(#iY8W6rb)" class="surpzvbho"/><g filter="url(#iKruYwb)"><path fill="url(#iMYAgJc)" class="vr4zf-bal"/></g><g filter="url(#iuWKOUd)"><path fill="url(#icxguSd)" clip-rule="evenodd" class="qwqb54idq"/></g><g filter="url(#il8wG8W)"><path class="a5cimmcay"/></g><path fill="url(#izN4wHg)" clip-rule="evenodd" class="mfhraibrx"/><path fill="url(#ixDBxTd)" clip-rule="evenodd" class="mfhraibrx"/><path fill="url(#iw3E6TE)" clip-rule="evenodd" class="bqtd2db1r"/><path fill="url(#iiqqFJd)" clip-rule="evenodd" class="bqtd2db1r"/><circle fill="url(#idoRzPd)" class="t4zanezhp"/><g filter="url(#ivaP3Kc)"><circle fill="url(#it5hqLb)" class="qnxk-uh_d"/></g><g filter="url(#iIW7Olc)"><circle fill="url(#icSwAmb)" class="xkccmnbtk"/><circle fill="url(#imlxVNs)" class="xkccmnbtk"/></g><g filter="url(#i3m0bKf)"><circle class="tbe686bid"/><circle fill="url(#iHRThEl)" class="a-krpibql"/><circle fill="url(#iD3Iezc)" class="a-krpibql"/></g><path fill="url(#iTeQO2b)" class="r88pt3-1d"/><path fill="url(#iWIUzBd)" class="r88pt3-1d"/><path fill="url(#iTNryiR)" class="r88pt3-1d"/><path fill="url(#itZ5Tgd)" class="r88pt3-1d"/><path fill="url(#imCS69b)" class="r88pt3-1d"/><g filter="url(#i3rn1qe)"><path class="ag5djkb1n"/><path fill="url(#i4uk1qc)" class="b-xqu-b2l"/><path fill="url(#iz17B0r)" class="b-xqu-b2l"/><path fill="url(#ijpTQOb)" class="b-xqu-b2l"/><path fill="url(#iAhYS1c)" class="b-xqu-b2l"/><path fill="url(#iK9i9ac)" class="b-xqu-b2l"/><path fill="url(#i1eGymd)" class="b-xqu-b2l"/></g><path fill="url(#i3vYDwb)" class="b-xqu-b2l"/><path fill="url(#iLf0HJc)" class="b-xqu-b2l"/><path fill="url(#iiUlwnb)" class="b-xqu-b2l"/><g filter="url(#iCMoNHe)"><path class="v1aucqghh"/></g><g filter="url(#iDXbW0N)"><path class="m369bnbwd"/><path fill="url(#i040sId)" class="gvyg_zr8d"/><path fill="url(#iUYXTfR)" class="gvyg_zr8d"/><path fill="url(#iDE1BAb)" class="gvyg_zr8d"/></g><path fill="url(#iJ7zyvp)" class="gvyg_zr8d"/><g filter="url(#idYsHre)"><path stroke="url(#iWyzc8c)" class="plz0otbsl"/></g><path class="vdwk7_03s"/><path class="jq39pecwn"/><path fill="url(#iVyJfUb)" class="nrhaoqbsi"/><path class="z-47ucc0x"/><g filter="url(#iKTWdsb)"><path class="kr-kyac2d"/><path fill="url(#iMcmHTd)" class="hja354j7k"/></g><g filter="url(#iB6VGhe)"><path fill="url(#iYECljc)" class="qxs5b109y"/></g><path class="qwe_mpzxe"/><path fill="url(#iD1vuqc)" class="izqxwisuy"/><path class="h1i8lmbss"/><g filter="url(#iI3t5Db)"><path fill="url(#iXcWLZd)" class="i8kprjuqi"/></g><g filter="url(#iAy6nib)"><ellipse transform="rotate(-27.914 13.614 9.931)" class="jqa7y_bbp"/><ellipse fill="url(#ilphGLe)" transform="rotate(-27.914 13.614 9.931)" class="g_84brd8m"/></g><g filter="url(#inJtswe)"><path fill="url(#iNiFRKG)" clip-rule="evenodd" class="y5g5ghbee"/></g><g filter="url(#iUaiKue)"><path class="tlxahsbuk"/></g><g filter="url(#iez81Gb)"><path fill="url(#i0jrwub)" clip-rule="evenodd" class="lg93syf8c"/></g><g filter="url(#iqKCwqc)"><path class="r4d7tzbwc"/></g><defs><radialGradient id="iiAhbGz" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.34 23.93)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="iHgfLya" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.228 8.14)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="ilD1Psd" cx="0" cy="0" r="1" gradientTransform="rotate(77.152 -6.255 23.653)scale(3.65398 4.0429)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="iiMJq3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 16.111 29.998)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="iszbMtb" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.477 24.711)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="iO6dWLC" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.64 12.387)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="i6Ykf8d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.376 21.96)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="iwJG3xe" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.689 20.336)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="iMSVcxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 16.14 18.552)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="awb3nwd-w"/><stop offset="1" class="jxac2cboa"/></radialGradient><radialGradient id="iqlnLzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.509 30.492)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="stn4eib-z"/><stop offset="1" class="z99vy1qwj"/></radialGradient><radialGradient id="itZF5Nb" cx="0" cy="0" r="1" gradientTransform="rotate(90 .583 18.7)scale(6.1875 .84559)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="iu71slc" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.591 26.56)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="iV3vUId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.284 24.867)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="iCf54Cb" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.452 11.293)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="ihq1NHc" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.275 24.922)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="iCLdqBc" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.446 19.491)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="iHDS0ld" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 12.243 18.32)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="ibv28Rd" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -16.956 24.384)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="itG6hAu" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.72628 3.2225 0 16.13 18.718)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="hyxc06bgp"/><stop offset=".577" class="mjky57bjt"/><stop offset="1" class="gqtxsdait"/></radialGradient><radialGradient id="iZ3npSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.30438 0 18.65 16.383)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ad-0z61hw"/><stop offset="1" class="p6pfsuaja"/></radialGradient><radialGradient id="iiDpxJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.727 20.039)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="iHeGdRb" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.89 12.238)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="s96-1fbmn"/><stop offset="1" class="pvle9ybys"/></radialGradient><radialGradient id="iY8W6rb" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.227 18.106)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="iMYAgJc" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.393 25.906)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="ixDBxTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.275 23.57)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="idoRzPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.648 10.71)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="imlxVNs" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 26.65 -27.364)scale(1.02361 1.16832)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iHRThEl" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.8 11.532)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iD3Iezc" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.841 10.71)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iTNryiR" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.59375 -9.8125 0 16.563 9.117)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="itZ5Tgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.42 9.437)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="imCS69b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.857 9.404)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="i4uk1qc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43986 4.43352 -7.5396 -5.84979 19.767 2.99)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="ijpTQOb" cx="0" cy="0" r="1" gradientTransform="rotate(-95.29 9.188 -1.905)scale(2.00292 .98368)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iAhYS1c" cx="0" cy="0" r="1" gradientTransform="matrix(.85996 -1.96834 1.60534 .70136 20.302 8.971)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iK9i9ac" cx="0" cy="0" r="1" gradientTransform="matrix(.99373 1.23303 -1.08867 .87739 15.295 2.1)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="i1eGymd" cx="0" cy="0" r="1" gradientTransform="matrix(1.45237 -3.03851 1.04984 .50181 20.264 6.487)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="i3vYDwb" cx="0" cy="0" r="1" gradientTransform="matrix(.26142 1.01586 -1.67013 .42978 16.767 2.1)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iLf0HJc" cx="0" cy="0" r="1" gradientTransform="matrix(1.108 1.60044 -3.3305 2.30572 11.685 3.362)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="iiUlwnb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.21429 3.2501 -4.0668 -9.02713 17.225 6.342)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iWyzc8c" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 15.986 14.725)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iVyJfUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90401 -1.06968 0 18.252 10.361)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iMcmHTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 18.024 10.111)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iD1vuqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90406 -1.06973 0 13.885 10.36)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ilphGLe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.843 -1.57)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNiFRKG" cx="0" cy="0" r="1" gradientTransform="matrix(.19698 -.81253 1.78256 .43214 18.525 8.508)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="i0jrwub" cx="0" cy="0" r="1" gradientTransform="matrix(-.19698 -.81253 1.78256 -.43214 13.618 8.509)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><linearGradient id="iqAcP4q" x1="23.454" x2="23.142" y1="24.609" y2="24.609" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iYaYOcc" x1="8.876" x2="9.212" y1="24.609" y2="24.609" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="iXn7tsD" x1="16.321" x2="16.321" y1="30.961" y2="29.148" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="i1DPc8d" x1="8.96" x2="23.336" y1="15.438" y2="15.438" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="izWfgjb" x1="8.96" x2="23.336" y1="15.408" y2="15.408" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iH18ryU" x1="7.14" x2="7.14" y1="30.774" y2="29.314" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="ia1wbgb" x1="22.811" x2="23.59" y1="25.647" y2="25.647" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iykr42d" x1="16.321" x2="23.946" y1="26.992" y2="19.399" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="iNwHKmc" x1="22.035" x2="16.92" y1="18.388" y2="23.906" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="im99Eac" x1="20.189" x2="20.032" y1="15.669" y2="17.731" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="idKTWjA" x1="17.727" x2="18.884" y1="18.914" y2="19.398" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="iz03z7x" x1="12.415" x2="12.743" y1="23.211" y2="22.851" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="ihxMcsd" x1="20.454" x2="19.782" y1="23.68" y2="23.695" gradientUnits="userSpaceOnUse"><stop offset=".294" class="w_l8deb9l"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="icxguSd" x1="12.35" x2="12.35" y1="19.878" y2="28.461" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="izN4wHg" x1="9.659" x2="10.553" y1="25.277" y2="25.277" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iw3E6TE" x1="14.032" x2="14.704" y1="25.287" y2="25.287" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iiqqFJd" x1="15.095" x2="14.852" y1="24.805" y2="24.805" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="it5hqLb" x1="11.319" x2="10.678" y1="10.989" y2="10.989" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="icSwAmb" x1="21.929" x2="21.109" y1="9.617" y2="12.156" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iTeQO2b" x1="20.111" x2="12.467" y1="11.1" y2="12.239" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iWIUzBd" x1="10.67" x2="12.985" y1="13.798" y2="13.496" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iz17B0r" x1="11.206" x2="14.11" y1="10.443" y2="5.283" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="i040sId" x1="15.206" x2="16.145" y1="11.759" y2="11.759" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iUYXTfR" x1="17.011" x2="15.984" y1="12.082" y2="12.068" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iDE1BAb" x1="16.266" x2="16.266" y1="12.825" y2="12.252" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iJ7zyvp" x1="16.197" x2="16.197" y1="12.867" y2="12.7" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="iYECljc" x1="19.031" x2="18.717" y1="10.081" y2="10.275" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXcWLZd" x1="14.629" x2="14.315" y1="10.081" y2="10.275" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><filter id="iVOsBXc" width="7.147" height="11.557" x="9.175" y="15.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".5"/></filter><filter id="ixFDjyd" width="7.147" height="11.557" x="16.069" y="15.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".5"/></filter><filter id="i5J5Ytc" width="3.699" height="3.699" x="17.14" y="24.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".375"/></filter><filter id="iKruYwb" width="1.42" height="1.42" x="19.11" y="24.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24143"/></filter><filter id="iuWKOUd" width="5.381" height="7.171" x="9.659" y="19.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24143"/></filter><filter id="il8wG8W" width="5.3" height="6.89" x="9.725" y="19.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".15"/></filter><filter id="ivaP3Kc" width="2.992" height="2.992" x="9.823" y="9.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".25"/></filter><filter id="iIW7Olc" width="3.592" height="3.592" x="19.17" y="8.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24143"/></filter><filter id="i3m0bKf" width="2.992" height="2.992" x="19.345" y="9.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".25"/></filter><filter id="i3rn1qe" width="12.614" height="8.301" x="9.764" y="1.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24143"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24143" result="effect2_innerShadow_3987_24143"/></filter><filter id="iCMoNHe" width="3.262" height="4.184" x="14.201" y="9.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".375"/></filter><filter id="iDXbW0N" width="2.379" height="3.184" x="14.882" y="9.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".125"/></filter><filter id="idYsHre" width="3.621" height="1.473" x="14.261" y="13.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".05"/></filter><filter id="iKTWdsb" width=".787" height=".697" x="17.518" y="9.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".05"/></filter><filter id="iB6VGhe" width=".892" height=".914" x="18.358" y="9.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".1"/></filter><filter id="iI3t5Db" width=".987" height="1.041" x="13.912" y="9.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".1"/></filter><filter id="iAy6nib" width=".914" height=".705" x="13.157" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".05"/></filter><filter id="inJtswe" width="2.604" height="1.648" x="17.336" y="7.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24143"/></filter><filter id="iUaiKue" width="2.709" height="1.503" x="17.284" y="7.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".2"/></filter><filter id="iez81Gb" width="2.604" height="1.648" x="12.202" y="7.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24143"/></filter><filter id="iqKCwqc" width="2.709" height="1.503" x="12.15" y="7.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24143" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-health-worker" /></template>
<style>
.a_303v8zt {
  d: path("M16.638 22.512c0-.04-.01-.203 0-.243l2.662-6.29c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.36c.01.03.054.05.054.09l.056 3.6h.01v3.97h.79v-3.97l.078-3.416z");
}

.a-krpibql {
  cx: 20.841px;
  cy: 10.71px;
  r: 0.996px;
}

.a5cimmcay {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.335 26.292h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.ad-0z61hw {
  stop-color: var(--svg-color--552e54, #552E54);
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.ag5djkb1n {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m20.895 4.226l.43.214c.75.373 1.18 1.227 1.02 2.135l-.591 3.043c-.053.314-.26.526-.573.534c.036-.505.07-1.318.082-1.446c.044-.434-.025-.561-.422-.957c-.215-.213-.376-.533-.376-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.215.16-.324.495-.324.762c.014.156.036 1.053.06 1.426a.634.634 0 0 1-.596-.532l-.59-3.043c-.108-.855.322-1.709 1.073-2.082c1.015-.445 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.268 1.718-.054 2.362.533l.805.8c.215.268.484.428.806.588");
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.awb3nwd-w {
  stop-color: var(--svg-color--3774ab, #3774AB);
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.b-xqu-b2l {
  d: path("m20.895 4.226l.43.214c.75.373 1.18 1.227 1.02 2.135l-.591 3.043c-.053.314-.26.526-.573.534c.036-.505.07-1.318.082-1.446c.044-.434-.025-.561-.422-.957c-.215-.213-.376-.533-.376-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.215.16-.324.495-.324.762c.014.156.036 1.053.06 1.426a.634.634 0 0 1-.596-.532l-.59-3.043c-.108-.855.322-1.709 1.073-2.082c1.015-.445 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.268 1.718-.054 2.362.533l.805.8c.215.268.484.428.806.588");
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.bqtd2db1r {
  fill-rule: evenodd;
  d: path("M15.04 23.729v2.47c0 .36-.29.65-.65.65h-.58v-.981h.25v-2.14z");
}

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.croudib4q {
  fill-rule: evenodd;
  d: path("M16.08 15.119a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 1 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.dxszyubmb {
  stop-color: var(--svg-color--d3cfda, #D3CFDA);
}

.e---z_byu {
  stop-color: var(--svg-color--ad9ec2, #AD9EC2);
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f2p5dfb8i {
  d: path("M16.17 15.408h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.foe4l_bip {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
  stop-opacity: 0;
}

.fr_rdtj9g {
  stop-color: var(--svg-color--d4cae9, #D4CAE9);
}

.ft5dv1b6b {
  fill: none;
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.g_84brd8m {
  cx: 13.614px;
  cy: 9.931px;
  rx: 0.39px;
  ry: 0.197px;
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
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

.gqtxsdait {
  stop-color: var(--svg-color--964b08, #964B08);
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.gvyg_zr8d {
  d: path("m15.689 10.424l-.532 1.702a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.702c-.114-.377-.646-.377-.765 0");
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1i8lmbss {
  fill: var(--svg-color--000, #000);
  d: path("M14.395 10.443a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.235");
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hja354j7k {
  d: path("M18.189 9.739c.063.085-.07.189-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.135.389-.05");
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.hyxc06bgp {
  stop-color: var(--svg-color--d4892b, #D4892B);
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.i8kprjuqi {
  d: path("M14.699 10.338c0-.289-.235-.481-.298-.54l-.289.28l.178.362z");
}

.izqxwisuy {
  d: path("M13.883 9.55a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jmlpl5bgc {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.99 26.957a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.2");
}

.jq39pecwn {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.461 9.278c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.jqa7y_bbp {
  cx: 13.614px;
  cy: 9.931px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.jxac2cboa {
  stop-color: var(--svg-color--1651a0, #1651A0);
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.kr-kyac2d {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.189 9.739c.063.085-.07.189-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.135.389-.05");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv70nqbkg {
  stop-color: var(--svg-color--b49089, #B49089);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l-etq6b9a {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lg93syf8c {
  fill-rule: evenodd;
  d: path("M14.29 8.502c-.72-.067-1.183.214-1.295.317a.473.473 0 0 1-.64-.695c.306-.282 1.032-.656 2.023-.563a.473.473 0 1 1-.088.941");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkxa08fsn {
  d: path("M15.515 21.69c.262.515.262.941.262 1.305v2.991c0 .17-.208.26-.327.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.119-.13.05-.35-.129-.38l-.783-.14a.23.23 0 0 1-.189-.25l.188-2.059a.25.25 0 0 1 .113-.186a10.5 10.5 0 0 1 2.426-1.135a.3.3 0 0 1 .04.08z");
}

.ll7oxmbau {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
  stop-opacity: 0;
}

.lnyefdcqm {
  stop-color: var(--svg-color--c8bfd6, #C8BFD6);
}

.lpc21p-wa {
  stop-color: var(--svg-color--553c83, #553C83);
}

.m369bnbwd {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.689 10.424l-.532 1.702a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.702c-.114-.377-.646-.377-.765 0");
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

.mfhraibrx {
  fill-rule: evenodd;
  d: path("M9.66 26.188v-2.47h.98v2.14h.25v.98h-.58a.65.65 0 0 1-.65-.65");
}

.mjky57bjt {
  stop-color: var(--svg-color--bc6d29, #BC6D29);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.nm08ve9ry {
  d: path("M16.5 15.408c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.nrhaoqbsi {
  d: path("M18.254 9.55a.893.893 0 0 1 .86 1.128H17.39a.897.897 0 0 1 .865-1.129");
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o874sbcxz {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
}

.oc1bwblbr {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.osioyzhgj {
  d: path("M26.971 27.968c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59v11.78h3.65z");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p6pfsuaja {
  stop-color: var(--svg-color--552e54, #552E54);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plz0otbsl {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.071 13.843c-.508 0-.985-.12-1.386-.33c-.137-.069-.285.085-.198.21c.335.508.919.847 1.584.847s1.25-.339 1.585-.847c.086-.13-.061-.279-.198-.21c-.402.21-.874.33-1.387.33Z");
}

.pvle9ybys {
  stop-color: var(--svg-color--4a2657, #4A2657);
  stop-opacity: 0;
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q_1v6cmzc {
  d: path("m6.071 22.769l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67v-11.75a10.56 10.56 0 0 0-2.85 4.52");
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
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

.qnxk-uh_d {
  cx: 11.319px;
  cy: 10.71px;
  r: 0.996px;
}

.qsu575jak {
  d: path("M16.794 21.69c-.262.515-.262.941-.262 1.305v2.991c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.753-.83a.23.23 0 0 1 .129-.38l.783-.14a.23.23 0 0 0 .188-.25l-.187-2.059a.25.25 0 0 0-.113-.186a10.5 10.5 0 0 0-2.426-1.135a.3.3 0 0 0-.04.08z");
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwe_mpzxe {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.676 9.278c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.qwqb54idq {
  fill-rule: evenodd;
  d: path("M12.35 20.86c-.94 0-1.71.76-1.71 1.709v3.299h.67a.49.49 0 0 1 0 .981h-1c-.36 0-.65-.29-.65-.65v-3.63a2.69 2.69 0 0 1 5.38 0v3.63c0 .36-.289.65-.65.65h-.93a.49.49 0 0 1 0-.981h.6v-3.3a1.71 1.71 0 0 0-1.71-1.709");
}

.qxs5b109y {
  d: path("M19.05 10.325a.84.84 0 0 0-.232-.463l-.26.286l.117.228z");
}

.r10bjccqq {
  d: path("m22.038 20.153l-.732.13a.213.213 0 0 0-.12.352l.704.77a.216.216 0 0 1-.01.296l-4.505 4.6c-.112.11-.306.036-.306-.121v-3.33c0-.036.009-.064.018-.101l2.54-5.888a.15.15 0 0 1 .038-.065a9.7 9.7 0 0 1 2.364 1.122l.186 2.003a.214.214 0 0 1-.177.232");
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r4d7tzbwc {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.675 8.36c.21-.192.803-.52 1.659-.44");
}

.r88pt3-1d {
  d: path("M10.967 10.097a30 30 0 0 1-.059-1.44c0-.267.108-.587.322-.748l.162-.16c.268-.213.375-.534.375-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.054.43.267.43.534v.854c0 .32.16.64.375.854c.503.352.471.546.43.961c-.013.129-.054 1.196-.09 1.441l-.266 3.963c-.16 1.77-1.553 3.005-3.213 3.005h-3.214c-1.713 0-3.052-1.234-3.213-3.005z");
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
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

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.s96-1fbmn {
  stop-color: var(--svg-color--4a2657, #4A2657);
}

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.sp4_sibjj {
  stop-color: var(--svg-color--5d4f77, #5D4F77);
}

.stn4eib-z {
  stop-color: var(--svg-color--3865b8, #3865B8);
}

.surpzvbho {
  d: path("M19.82 26.729a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t4zanezhp {
  cx: 11.319px;
  cy: 10.71px;
  r: 1.671px;
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.t7e9ekbly {
  d: path("M16.131 15.408c-2.74 0-5.3 1.06-7.21 2.84v11.75h14.38v-11.78a10.54 10.54 0 0 0-7.17-2.81");
}

.tbe686bid {
  cx: 20.841px;
  cy: 10.71px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.tlxahsbuk {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.468 8.36c-.21-.192-.804-.52-1.66-.44");
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.txkutm4dn {
  d: path("M16.13 18.718a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.uy62st-sf {
  fill: var(--svg-color--5a4b7e, #5A4B7E);
  fill-rule: evenodd;
  d: path("M16.08 15.119a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 1 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.v1aucqghh {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.796 10.587l-.821 1.702c-.102.35.142.7.488.7h.738c.346 0 .59-.356.488-.7l-.498-1.702c-.107-.377-.283-.377-.395 0");
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.vdwk7_03s {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.071 13.843c-.508 0-.985-.12-1.386-.33c-.137-.069-.285.085-.198.21c.335.508.919.847 1.584.847s1.25-.339 1.585-.847c.086-.13-.061-.279-.198-.21c-.402.21-.874.33-1.387.33");
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.vr4zf-bal {
  d: path("M19.82 26.178a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.w_l8deb9l {
  stop-color: var(--svg-color--746992, #746992);
}

.w-_6jxb_z {
  stop-color: var(--svg-color--efeafb, #EFEAFB);
}

.w0rhj52ia {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
  stop-opacity: 0;
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x3e-lhbqh {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
  stop-opacity: 0;
}

.x7yaztbkk {
  stop-color: var(--svg-color--b3a299, #B3A299);
  stop-opacity: 0;
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xkccmnbtk {
  cx: 20.841px;
  cy: 10.71px;
  r: 1.671px;
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.y-u26bckg {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.352 20.153l.732.13a.213.213 0 0 1 .12.352l-.704.77a.216.216 0 0 0 .01.296l4.505 4.6c.111.11.306.036.306-.121v-3.33c0-.036-.009-.064-.018-.101l-2.54-5.888a.15.15 0 0 0-.038-.065a9.7 9.7 0 0 0-2.364 1.122l-.186 2.003a.214.214 0 0 0 .176.232");
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.y5g5ghbee {
  fill-rule: evenodd;
  d: path("M17.853 8.502c.72-.067 1.182.214 1.294.317a.473.473 0 1 0 .64-.695c-.306-.282-1.032-.656-2.022-.563a.473.473 0 1 0 .088.941");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.z-47ucc0x {
  fill: var(--svg-color--000, #000);
  d: path("M17.743 10.443a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
}

.z99vy1qwj {
  stop-color: var(--svg-color--3865b8, #3865B8);
  stop-opacity: 0;
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
