<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iXf4U4d)"><path fill="url(#i3a2isc)" clip-rule="evenodd" class="g541hpbla"/><path fill="url(#ikdDv5d)" clip-rule="evenodd" class="g541hpbla"/><path fill="url(#iuZs34Q)" clip-rule="evenodd" class="g541hpbla"/><path fill="url(#ibklSKd)" clip-rule="evenodd" class="g541hpbla"/><path fill="url(#iFNSO9c)" clip-rule="evenodd" class="g541hpbla"/><path fill="url(#iETEERw)" clip-rule="evenodd" class="g541hpbla"/><path fill="url(#iCBpOac)" clip-rule="evenodd" class="g541hpbla"/><path fill="url(#iXgxlte)" clip-rule="evenodd" class="g541hpbla"/><path fill="url(#idIBoIc)" clip-rule="evenodd" class="g541hpbla"/><path fill="url(#itppxRP)" clip-rule="evenodd" class="g541hpbla"/><path fill="url(#iWsY6ov)" clip-rule="evenodd" class="g541hpbla"/></g><path fill="url(#i3SMNpd)" class="sn35uyb8c"/><path fill="url(#ir97fad)" class="sn35uyb8c"/><path fill="url(#iT5rLZd)" class="sn35uyb8c"/><path fill="url(#is3fBkd)" class="sn35uyb8c"/><path fill="url(#i753wGb)" class="sn35uyb8c"/><path fill="url(#inY5mUc)" class="sn35uyb8c"/><path fill="url(#isZcZtd)" class="sn35uyb8c"/><path fill="url(#i4tLV6d)" class="qnbdzls5a"/><path fill="url(#iDmIAsd)" class="gn0kx7bnl"/><path fill="url(#iK3zH2d)" class="fvl1fqc7g"/><path fill="url(#iJHmxGc)" class="fvl1fqc7g"/><path fill="url(#iHeYPqe)" class="fvl1fqc7g"/><path fill="url(#iPWvnWd)" class="hiat-abhw"/><path fill="url(#i2g8IKc)" class="hiat-abhw"/><path fill="url(#iT5oCKc)" class="hiat-abhw"/><path fill="url(#iQ6o6cd)" class="gsaq2iyal"/><path fill="url(#iHtyLEd)" class="gsaq2iyal"/><path fill="url(#i4tLV6d)" class="qnbdzls5a"/><path fill="url(#iDmIAsd)" class="gn0kx7bnl"/><g filter="url(#ixA09ud)"><path class="a5uh0bcvv"/></g><g filter="url(#i0k5yBc)"><path fill="url(#iqomtNd)" class="uxvx7flip"/></g><path fill="url(#iea4jpe)" class="bfs80p08a"/><path fill="url(#iucKHvd)" class="bfs80p08a"/><path fill="url(#iwpWHqd)" class="bfs80p08a"/><path fill="url(#ishHRic)" class="bfs80p08a"/><path fill="url(#iyV6MIe)" class="bfs80p08a"/><path fill="url(#idy5Bic)" class="bfs80p08a"/><path fill="url(#iSOaJOd)" class="l1aa3accl"/><path fill="url(#ivEbWme)" class="l1aa3accl"/><path fill="url(#i9zQ5Ub)" class="l1aa3accl"/><path fill="url(#i1ZloLe)" class="l1aa3accl"/><path fill="url(#i6z41uc)" class="l1aa3accl"/><path fill="url(#iYhD8Bc)" class="l1aa3accl"/><path fill="url(#iDTcSHc)" class="a1fhrabip"/><path clip-rule="evenodd" class="tao0vt4cm"/><path fill="url(#iwcjOWc)" clip-rule="evenodd" class="cpjbygb3c"/><path fill="url(#iFs7KHd)" clip-rule="evenodd" class="cpjbygb3c"/><path fill="url(#iuW483c)" clip-rule="evenodd" class="cpjbygb3c"/><path fill="url(#i1VLk6b)" clip-rule="evenodd" class="cpjbygb3c"/><g filter="url(#iBk9U6d)"><path class="o5jgzgb8w"/></g><path fill="url(#it878Fh)" class="a6remvp_u"/><g filter="url(#iCaMyYb)"><path fill="url(#iAfHGjd)" class="v4wdc00_a"/></g><g filter="url(#irEcwps)"><path fill="url(#ikqAQCe)" clip-rule="evenodd" class="s6ywrhbas"/></g><g filter="url(#i6BT47c)"><path class="f_pmj42yd"/></g><path fill="url(#iE85LFc)" clip-rule="evenodd" class="azhxw4b2f"/><path fill="url(#iUBou9e)" clip-rule="evenodd" class="azhxw4b2f"/><path fill="url(#iTxPZNe)" clip-rule="evenodd" class="t_72ovrmd"/><path fill="url(#ig96Bwe)" clip-rule="evenodd" class="t_72ovrmd"/><g filter="url(#ij5Dyzc)"><path fill="url(#iCKqJkb)" class="igku9qbpc"/></g><g filter="url(#ixzbJyx)"><path fill="url(#i5FYQ8z)" class="fvq4yw_7a"/><path fill="url(#iqGJkWb)" class="fvq4yw_7a"/></g><g filter="url(#iX87PQb)"><path class="ye566r69w"/><path fill="url(#iaMAScd)" class="io5rsydxu"/></g><g filter="url(#ihrI4xd)"><path class="kn_m6gnti"/><path fill="url(#i6ux0fJ)" class="d3dumefvf"/></g><g filter="url(#i31KBKb)"><path fill="url(#iaENxec)" class="wt14hmjzh"/><path fill="url(#iwgOfFe)" class="wt14hmjzh"/><path fill="url(#iS4AHpe)" class="wt14hmjzh"/><path fill="url(#ihjRRme)" class="wt14hmjzh"/><path fill="url(#i4VWgOd)" class="wt14hmjzh"/><path fill="url(#i8WEcid)" class="wt14hmjzh"/><path fill="url(#iAZrNoc)" class="wt14hmjzh"/></g><path fill="url(#ic3Sudd)" class="wt14hmjzh"/><path fill="url(#iLPhfjc)" class="wt14hmjzh"/><g filter="url(#iVKFMbb)"><path class="o1s2-kxbb"/></g><g filter="url(#id0nKGb)"><path class="v-x2gy7zx"/><path fill="url(#ixWmbqb)" class="jc_zkob5p"/><path fill="url(#i5hq1Ib)" class="jc_zkob5p"/><path fill="url(#iZR8Ild)" class="jc_zkob5p"/><path fill="url(#i9fluCd)" class="jc_zkob5p"/></g><path fill="url(#imj5nbd)" class="jc_zkob5p"/><path fill="url(#inAntae)" class="jc_zkob5p"/><path stroke="url(#iiYIhqc)" class="t0pqsdbev"/><g filter="url(#i2vjA8b)"><path class="eassh49wf"/></g><g filter="url(#ievCPTb)"><path class="z_zy-9v1e"/></g><g filter="url(#iyqq9Vb)"><path class="mgvzxwm-f"/></g><g filter="url(#iTchCAe)"><path clip-rule="evenodd" class="rj1q7856u"/></g><path class="fof-vdbus"/><path fill="url(#i6qPS4c)" class="n8mmd7lbf"/><path class="ewqxj1w6h"/><g filter="url(#ikxZZ6d)"><path class="er_0j1vue"/><path fill="url(#iSa0cKd)" class="anz09ubfr"/></g><g filter="url(#ibK30bd)"><path fill="url(#ijHncrd)" class="xoa6ebbqb"/></g><path class="rpdo35xpz"/><path fill="url(#irZUzrc)" class="j6bls5b1m"/><path class="xtv6-ek0u"/><g filter="url(#i2K8mGd)"><path fill="url(#iupTyVc)" class="vqyw2ep7f"/></g><g filter="url(#iDcm0id)"><ellipse transform="rotate(-27.914 13.513 9.953)" class="zg14me12h"/><ellipse fill="url(#iVbDMyc)" transform="rotate(-27.914 13.513 9.953)" class="yln39lbdh"/></g><g filter="url(#ixrA3fN)"><path class="d_a3rwb_w"/></g><g filter="url(#iAMOmGb)"><path class="xlgvdfb1l"/></g><g filter="url(#iuZBTdc)"><path class="a40e5ybyj"/><path fill="url(#iNmvBOb)" class="lzu1_40wr"/></g><g filter="url(#i7pWNyh)"><path class="vnldxfimu"/><path fill="url(#ifNwIlN)" class="lfpuwzb6f"/><path fill="url(#iH4bgbe)" class="lfpuwzb6f"/></g><g filter="url(#i0cjBpG)"><path stroke="url(#iGJw3tZ)" class="e1iodhbxl"/></g><g filter="url(#iBmdRuc)"><path class="l4_p5vi2t"/></g><defs><radialGradient id="ikdDv5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 15.664 13.146)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iuZs34Q" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.848 13.414)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ibklSKd" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.876 8.181)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iFNSO9c" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.309 7.665)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iETEERw" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 12.446 2.587)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iCBpOac" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.933 6.847)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iXgxlte" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 23.475 9.794)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="idIBoIc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.622 8.014)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="itppxRP" cx="0" cy="0" r="1" gradientTransform="matrix(-.90444 -2.65026 2.0962 -.71536 20.699 7.36)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iWsY6ov" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.824 9.758)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i3SMNpd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.195 23.947)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="i753wGb" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.16 8.19)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="inY5mUc" cx="0" cy="0" r="1" gradientTransform="rotate(77.152 -6.338 23.57)scale(3.65398 4.0429)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="isZcZtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.966 30.015)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="iK3zH2d" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.332 24.728)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="iJHmxGc" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.719 12.342)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="iPWvnWd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.231 21.978)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="i2g8IKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.544 20.353)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="iQ6o6cd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 16 18.572)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="laxsilb3j"/><stop offset="1" class="k5_wf-bwi"/></radialGradient><radialGradient id="iHtyLEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.364 30.509)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="p5_0bzbaz"/><stop offset="1" class="iqq-d2brk"/></radialGradient><radialGradient id="ishHRic" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 19.139 18.134)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="iyV6MIe" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.447 26.576)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="idy5Bic" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.139 24.884)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="iSOaJOd" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.378 11.288)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="ivEbWme" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.13 24.939)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="i1ZloLe" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.302 19.51)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="i6z41uc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 12.098 18.337)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="iYhD8Bc" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -17.048 24.235)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="iDTcSHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.125 -2.67249 0 15.985 16.407)" gradientUnits="userSpaceOnUse"><stop class="tryk26dmw"/><stop offset=".47" class="vw7-hvvxw"/><stop offset=".858" class="diydvtbdx"/></radialGradient><radialGradient id="iFs7KHd" cx="0" cy="0" r="1" gradientTransform="matrix(.5209 2.3152 -1.36598 .30734 18.127 16.081)" gradientUnits="userSpaceOnUse"><stop class="w_gx_6l5c"/><stop offset="1" class="sruu51y8f"/></radialGradient><radialGradient id="iuW483c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.582 20.056)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="i1VLk6b" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.812 12.202)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="fv5w29bdg"/><stop offset="1" class="e6fuuiw3e"/></radialGradient><radialGradient id="it878Fh" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.15 18.074)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="iAfHGjd" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.248 25.923)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="iUBou9e" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.13 23.587)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="i5FYQ8z" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 23.256 -17.127)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iqGJkWb" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 21.036 8.964)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iaMAScd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.357 10.758)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="i6ux0fJ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.365 10.645)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iaENxec" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -4.01413 -8.70492 18.825 10.108)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iwgOfFe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 19.218 11.47)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iS4AHpe" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.586 17.437)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="ihjRRme" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -7.78405 0 15.966 9.89)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="i4VWgOd" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.313 6.783)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="i8WEcid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.267 9.69)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iAZrNoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.89 9.46)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ic3Sudd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.061 11.177)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iLPhfjc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 13.781 4.11)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="ixWmbqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.75 11.904)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="i9fluCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.51 12.115)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="inAntae" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.385 8.295)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="i6qPS4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.148 10.048)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iSa0cKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.92 10.133)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irZUzrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.784 10.048)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVbDMyc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.803 -1.51)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNmvBOb" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.33 -4.066)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ifNwIlN" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.083 6.98)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iH4bgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.21034 1.3672 -2.94144 -.45253 16.176 3.09)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><linearGradient id="i3a2isc" x1="20.659" x2="13.854" y1="3.693" y2="16.297" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="ir97fad" x1="23.309" x2="22.997" y1="24.626" y2="24.626" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iT5rLZd" x1="8.731" x2="9.067" y1="24.626" y2="24.626" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="is3fBkd" x1="16.176" x2="16.176" y1="30.978" y2="29.165" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="i4tLV6d" x1="8.815" x2="23.191" y1="15.455" y2="15.455" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iDmIAsd" x1="8.815" x2="23.191" y1="15.425" y2="15.425" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iHeYPqe" x1="6.995" x2="6.995" y1="30.79" y2="29.331" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iT5oCKc" x1="22.666" x2="23.445" y1="25.664" y2="25.664" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iqomtNd" x1="16.176" x2="23.801" y1="27.009" y2="19.415" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="iea4jpe" x1="21.89" x2="16.775" y1="18.405" y2="23.923" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="iucKHvd" x1="20.044" x2="19.887" y1="15.686" y2="17.748" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="iwpWHqd" x1="17.582" x2="18.739" y1="18.931" y2="19.415" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="i9zQ5Ub" x1="12.27" x2="12.598" y1="23.228" y2="22.869" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="iwcjOWc" x1="20.309" x2="19.637" y1="23.697" y2="23.712" gradientUnits="userSpaceOnUse"><stop offset=".294" class="nrx5bzr9s"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="ikqAQCe" x1="12.205" x2="12.205" y1="19.895" y2="28.478" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="iE85LFc" x1="9.514" x2="10.409" y1="25.294" y2="25.294" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iTxPZNe" x1="13.887" x2="14.559" y1="25.304" y2="25.304" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="ig96Bwe" x1="14.95" x2="14.707" y1="24.821" y2="24.821" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="iCKqJkb" x1="9.671" x2="12.631" y1="10.732" y2="10.732" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="i5hq1Ib" x1="15.027" x2="15.966" y1="11.976" y2="11.976" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iZR8Ild" x1="15.966" x2="15.966" y1="12.775" y2="12.165" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="imj5nbd" x1="16.044" x2="16.044" y1="12.749" y2="12.61" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="iiYIhqc" x1="14.902" x2="15.363" y1="14.185" y2="13.473" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="ijHncrd" x1="18.926" x2="18.612" y1="10.102" y2="10.295" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iupTyVc" x1="14.528" x2="14.214" y1="10.102" y2="10.296" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGJw3tZ" x1="13.075" x2="13.619" y1="4.447" y2="5.721" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><filter id="iXf4U4d" width="15.268" height="15.768" x="8.457" y="1.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/></filter><filter id="ixA09ud" width="7.147" height="11.557" x="9.03" y="15.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".5"/></filter><filter id="i0k5yBc" width="7.147" height="11.557" x="15.924" y="15.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".5"/></filter><filter id="iBk9U6d" width="3.699" height="3.699" x="16.995" y="24.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".375"/></filter><filter id="iCaMyYb" width="1.42" height="1.42" x="18.965" y="24.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/></filter><filter id="irEcwps" width="5.381" height="7.171" x="9.514" y="19.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/></filter><filter id="i6BT47c" width="5.3" height="6.89" x="9.58" y="19.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".15"/></filter><filter id="ij5Dyzc" width="3.368" height="3.218" x="9.671" y="9.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/></filter><filter id="ixzbJyx" width="3.218" height="3.468" x="19.184" y="8.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/></filter><filter id="iX87PQb" width="3.148" height="3.148" x="19.219" y="9.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".25"/></filter><filter id="ihrI4xd" width="2.948" height="2.948" x="9.825" y="9.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".2"/></filter><filter id="i31KBKb" width="10.191" height="11.277" x="10.87" y="5.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/></filter><filter id="iVKFMbb" width="2.877" height="3.682" x="14.365" y="9.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".25"/></filter><filter id="id0nKGb" width="2.377" height="3.182" x="14.777" y="9.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".125"/></filter><filter id="i2vjA8b" width="3.001" height="1.286" x="16.908" y="9.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/></filter><filter id="ievCPTb" width="3.001" height="1.286" x="12.023" y="9.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/></filter><filter id="iyqq9Vb" width="2.453" height="1.091" x="12.158" y="7.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/></filter><filter id="iTchCAe" width="2.453" height="1.091" x="17.575" y="7.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/></filter><filter id="ikxZZ6d" width=".787" height=".696" x="17.414" y="9.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".05"/></filter><filter id="ibK30bd" width=".891" height=".913" x="18.254" y="9.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".1"/></filter><filter id="i2K8mGd" width=".986" height="1.04" x="13.811" y="9.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".1"/></filter><filter id="iDcm0id" width=".913" height=".704" x="13.056" y="9.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".05"/></filter><filter id="ixrA3fN" width="2.261" height=".978" x="17.605" y="7.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".1"/></filter><filter id="iAMOmGb" width="2.261" height=".978" x="12.154" y="7.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".1"/></filter><filter id="iuZBTdc" width="4.212" height="4.513" x="9.712" y="3.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/><feGaussianBlur result="effect2_foregroundBlur_3987_24157" stdDeviation=".15"/></filter><filter id="i7pWNyh" width="8.767" height="5.782" x="12.796" y="2.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24157"/><feGaussianBlur result="effect2_foregroundBlur_3987_24157" stdDeviation=".125"/></filter><filter id="i0cjBpG" width="1.145" height="2.31" x="12.775" y="3.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".1"/></filter><filter id="iBmdRuc" width="6.427" height="3.372" x="15.384" y="4.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24157" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-health-worker-light" /></template>
<style>
.a1fhrabip {
  d: path("M15.985 18.735a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a40e5ybyj {
  fill: var(--svg-color--232121, #232121);
  d: path("M10.897 4.657c.566-.6 1.636-.6 2.13-.51l.396 1.29c-.252-.04-.478.05-.667.234c-.449 1.26-1.99 1.956-2.704 2.146c-.149-1.492.109-2.38.845-3.16");
}

.a5uh0bcvv {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.207 20.17l.732.13a.213.213 0 0 1 .12.351l-.704.77a.216.216 0 0 0 .01.297l4.505 4.599c.112.11.306.037.306-.12v-3.33c0-.037-.01-.064-.018-.102l-2.54-5.887a.15.15 0 0 0-.038-.065a9.7 9.7 0 0 0-2.364 1.122l-.186 2.003a.214.214 0 0 0 .177.231");
}

.a6remvp_u {
  d: path("M19.675 26.745a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.anz09ubfr {
  d: path("M18.084 9.76c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.azhxw4b2f {
  fill-rule: evenodd;
  d: path("M9.514 26.205v-2.47h.982v2.14h.249v.981h-.58c-.36 0-.65-.29-.65-.65");
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.bfs80p08a {
  d: path("M16.65 21.707c-.263.515-.263.941-.263 1.305v2.991c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.753-.83a.23.23 0 0 1 .129-.38l.783-.14a.23.23 0 0 0 .188-.25l-.187-2.059a.25.25 0 0 0-.113-.186a10.5 10.5 0 0 0-2.426-1.134a.3.3 0 0 0-.04.08z");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpjbygb3c {
  fill-rule: evenodd;
  d: path("M15.935 15.136a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 1 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.d_a3rwb_w {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.906 8.273c.322-.079 1.124-.04 1.66.344");
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d3dumefvf {
  d: path("M11.3 11.72a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.diydvtbdx {
  stop-color: var(--svg-color--96665a, #96665A);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
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

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1iodhbxl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.075 4.104c.023.243.234 1.156.544 1.71");
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e6fuuiw3e {
  stop-color: var(--svg-color--261943, #261943);
  stop-opacity: 0;
}

.eassh49wf {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.108 10.076c.265-.467.669-.835 1.537-.835c.38 0 .747.105 1.073.368c.269.218.233.496.025.6l-.556.317c-.652-.21-1.373-.24-2.079-.45");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.er_0j1vue {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.084 9.76c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.ewqxj1w6h {
  fill: var(--svg-color--000, #000);
  d: path("M17.639 10.464c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746H17.7a.46.46 0 0 1-.061-.235");
}

.f_pmj42yd {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.19 26.309h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.foe4l_bip {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
  stop-opacity: 0;
}

.fof-vdbus {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.357 9.3c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.fr_rdtj9g {
  stop-color: var(--svg-color--d4cae9, #D4CAE9);
}

.ft5dv1b6b {
  fill: none;
}

.fv5w29bdg {
  stop-color: var(--svg-color--261943, #261943);
}

.fvl1fqc7g {
  d: path("m5.926 22.785l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67v-11.75a10.56 10.56 0 0 0-2.85 4.52");
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fvq4yw_7a {
  d: path("M20.793 12.254a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.g541hpbla {
  fill-rule: evenodd;
  d: path("M23.151 12.055c.213-.435.324-.92.324-1.427c0-.467-.096-.906-.269-1.305h.006a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.232l-.085.001A3.3 3.3 0 0 0 9.53 7.025v.01a3.24 3.24 0 0 1-.527 1.772l-.002.003a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.121-.982-.324-1.406a.52.52 0 0 1 0-.456m-12.26-2.672h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.955-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.19 1.235l-.051.02l-.051.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gn0kx7bnl {
  d: path("M16.025 15.425h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.gsaq2iyal {
  d: path("M16.493 22.53c0-.04-.01-.204 0-.244l2.662-6.29c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.36c.01.03.055.05.055.09l.055 3.6h.01v3.97h.79v-3.97l.078-3.416z");
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.hiat-abhw {
  d: path("M26.826 27.985c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59v11.78h3.65z");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.igku9qbpc {
  d: path("M11.28 12.254a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.io5rsydxu {
  d: path("M20.793 11.72a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.iqq-d2brk {
  stop-color: var(--svg-color--574379, #574379);
  stop-opacity: 0;
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6bls5b1m {
  d: path("M13.782 9.571a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.jc_zkob5p {
  d: path("m15.584 10.284l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.k5_wf-bwi {
  stop-color: var(--svg-color--4b2f74, #4B2F74);
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kn_m6gnti {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.3 11.72a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv70nqbkg {
  stop-color: var(--svg-color--b49089, #B49089);
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l-etq6b9a {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l1aa3accl {
  d: path("M15.37 21.707c.263.515.263.941.263 1.305v2.991c0 .17-.209.26-.328.13l-4.817-4.96a.234.234 0 0 1-.01-.32l.753-.83c.119-.13.05-.35-.129-.38l-.783-.14a.23.23 0 0 1-.188-.25l.187-2.059a.25.25 0 0 1 .113-.186a10.5 10.5 0 0 1 2.426-1.134a.3.3 0 0 1 .04.08z");
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l4_p5vi2t {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.372 6.465l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.laxsilb3j {
  stop-color: var(--svg-color--755a97, #755A97);
}

.lfpuwzb6f {
  d: path("M15.363 2.855c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.541 1.877.888c0-3.933-3.344-4.671-5.922-5.24z");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
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

.lzu1_40wr {
  d: path("M10.897 4.657c.566-.6 1.636-.6 2.13-.51l.396 1.29c-.252-.04-.478.05-.667.234c-.449 1.26-1.99 1.956-2.704 2.146c-.149-1.492.109-2.38.845-3.16");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mgvzxwm-f {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.568 8.867l-.004.003a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 0 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.n8mmd7lbf {
  d: path("M18.15 9.571a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nrx5bzr9s {
  stop-color: var(--svg-color--756a93, #756A93);
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o1s2-kxbb {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.573 10.423l-.683 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o5jgzgb8w {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.844 26.974a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.2");
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

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p5_0bzbaz {
  stop-color: var(--svg-color--574379, #574379);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.qnbdzls5a {
  d: path("M16.355 15.425c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.rj1q7856u {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.698 8.41l-.138.23za.268.268 0 0 1-.276.46l-.005-.003l-.022-.012l-.09-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .558.238l.01.005l.003.002z");
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rpdo35xpz {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.575 9.3c-.653 0-1.205.45-1.355 1.058c-.045.175.09.34.268.34h2.23a.23.23 0 0 0 .228-.27a1.4 1.4 0 0 0-1.371-1.129");
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s6ywrhbas {
  fill-rule: evenodd;
  d: path("M12.205 20.876c-.94 0-1.71.761-1.71 1.71v3.299h.67a.49.49 0 0 1 0 .98h-1a.65.65 0 0 1-.65-.65v-3.63a2.69 2.69 0 0 1 5.38 0v3.63c0 .361-.289.65-.65.65h-.93a.49.49 0 0 1 0-.98h.6v-3.3c0-.94-.762-1.71-1.71-1.71");
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.sn35uyb8c {
  d: path("M15.986 15.425c-2.74 0-5.3 1.06-7.21 2.84v11.75h14.38v-11.78a10.54 10.54 0 0 0-7.17-2.81");
}

.sp4_sibjj {
  stop-color: var(--svg-color--5d4f77, #5D4F77);
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.sruu51y8f {
  stop-color: var(--svg-color--271b48, #271B48);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.t_72ovrmd {
  fill-rule: evenodd;
  d: path("M14.896 23.745v2.47c0 .361-.29.65-.651.65h-.58v-.98h.25v-2.14z");
}

.t0pqsdbev {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.568 13.168a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.021-.25a.205.205 0 0 0-.247-.041a3 3 0 0 1-1.399.339a3 3 0 0 1-1.398-.34Z");
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.tao0vt4cm {
  fill: var(--svg-color--564a7b, #564A7B);
  fill-rule: evenodd;
  d: path("M15.935 15.136a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 1 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tryk26dmw {
  stop-color: var(--svg-color--c1928e, #C1928E);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.uxvx7flip {
  d: path("m21.893 20.17l-.732.13a.213.213 0 0 0-.12.351l.704.77a.216.216 0 0 1-.01.297l-4.505 4.599c-.112.11-.306.037-.306-.12v-3.33c0-.037.009-.064.018-.102l2.54-5.887a.15.15 0 0 1 .038-.065a9.7 9.7 0 0 1 2.364 1.122l.186 2.003a.214.214 0 0 1-.177.231");
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v-x2gy7zx {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.584 10.284l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v4wdc00_a {
  d: path("M19.675 26.195a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.vnldxfimu {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.363 2.855c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.541 1.877.888c0-3.933-3.344-4.671-5.922-5.24z");
}

.vqyw2ep7f {
  d: path("M14.597 10.36c0-.29-.234-.482-.298-.54l-.288.28l.177.36z");
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vw7-hvvxw {
  stop-color: var(--svg-color--b98d82, #B98D82);
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.w_gx_6l5c {
  stop-color: var(--svg-color--271b48, #271B48);
}

.w-_6jxb_z {
  stop-color: var(--svg-color--efeafb, #EFEAFB);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w0rhj52ia {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
  stop-opacity: 0;
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wt14hmjzh {
  d: path("M10.879 9.382h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439q.024-.008.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.118 3.073c-.124 2.802-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
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

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xlgvdfb1l {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.115 8.273c-.323-.079-1.125-.04-1.661.344");
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xoa6ebbqb {
  d: path("M18.945 10.346a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.xtv6-ek0u {
  fill: var(--svg-color--000, #000);
  d: path("M14.293 10.464a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.ye566r69w {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.793 11.72a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.yln39lbdh {
  cx: 13.513px;
  cy: 9.953px;
  rx: 0.39px;
  ry: 0.197px;
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.z_zy-9v1e {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.824 10.076c-.265-.467-.669-.835-1.537-.835c-.38 0-.747.105-1.073.368c-.269.218-.233.496-.025.6l.556.317c.652-.21 1.373-.24 2.08-.45");
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zg14me12h {
  cx: 13.513px;
  cy: 9.953px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

</style>
