<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iJrCKHO)" class="rgbkjoszo"/><path fill="url(#iAUl3Ge)" class="rgbkjoszo"/><path fill="url(#ijIhoqc)" class="rgbkjoszo"/><path fill="url(#ipQ5NMb)" class="rgbkjoszo"/><path fill="url(#iiwV82d)" class="rgbkjoszo"/><path fill="url(#i8rXvVc)" class="rgbkjoszo"/><path fill="url(#iBGIKee)" class="rgbkjoszo"/><path fill="url(#iTS35re)" class="u2-isd21s"/><path fill="url(#iisv4we)" class="d1d_ubb3a"/><path fill="url(#iwQ0RBe)" class="poxbdpd_y"/><path fill="url(#iZPCpEV)" class="poxbdpd_y"/><path fill="url(#iuuCRpQ)" class="poxbdpd_y"/><path fill="url(#iPVdyyd)" class="iy2m1tbkn"/><path fill="url(#iRVtLTv)" class="iy2m1tbkn"/><path fill="url(#itPSr4c)" class="iy2m1tbkn"/><path fill="url(#iAK8KpR)" class="rwlwafb9a"/><path fill="url(#i0dKUwc)" class="rwlwafb9a"/><path fill="url(#iTS35re)" class="u2-isd21s"/><path fill="url(#iisv4we)" class="d1d_ubb3a"/><g filter="url(#iOIcGsb)"><path class="s7d57ubpe"/></g><g filter="url(#iBoAe7p)"><path fill="url(#iSGfHnb)" class="bgvgsebrk"/></g><path fill="url(#isGCYIb)" class="j4ihnwt8k"/><path fill="url(#iEUguFc)" class="j4ihnwt8k"/><path fill="url(#iCUnuye)" class="j4ihnwt8k"/><path fill="url(#iFdEnnb)" class="j4ihnwt8k"/><path fill="url(#i9ppVec)" class="j4ihnwt8k"/><path fill="url(#iugVQdb)" class="j4ihnwt8k"/><path fill="url(#itXBFts)" class="dap6i3b6w"/><path fill="url(#ivH5hic)" class="dap6i3b6w"/><path fill="url(#iG3VIRc)" class="dap6i3b6w"/><path fill="url(#inNG5pb)" class="dap6i3b6w"/><path fill="url(#iUUiN0c)" class="dap6i3b6w"/><path fill="url(#iPOFEtj)" class="dap6i3b6w"/><path fill="url(#inDW3ld)" class="dj1fde44s"/><path clip-rule="evenodd" class="jrr-31bdb"/><path fill="url(#iDtygHb)" clip-rule="evenodd" class="v6un4nbff"/><path fill="url(#iOrCkHc)" clip-rule="evenodd" class="v6un4nbff"/><path fill="url(#i0i9dNb)" clip-rule="evenodd" class="v6un4nbff"/><path fill="url(#iZNnjPT)" clip-rule="evenodd" class="v6un4nbff"/><g filter="url(#ikUQJOy)"><path class="hr1mvxbss"/></g><path fill="url(#ixlrYod)" class="lwlcnvb_i"/><g filter="url(#iU25uMd)"><path fill="url(#ixOhefd)" class="sb6u0tpkd"/></g><g filter="url(#ij3z2rd)"><path fill="url(#ixWEuPe)" clip-rule="evenodd" class="wviklbcfj"/></g><g filter="url(#iWWLpGx)"><path class="bhnf0hx0r"/></g><path fill="url(#i5mT0wc)" clip-rule="evenodd" class="zj0w_34ts"/><path fill="url(#ik9dNTB)" clip-rule="evenodd" class="zj0w_34ts"/><path fill="url(#iGXiowe)" clip-rule="evenodd" class="swjm6kdny"/><path fill="url(#ijZYXiZ)" clip-rule="evenodd" class="swjm6kdny"/><g filter="url(#itALbmc)"><circle fill="url(#i1cqWIb)" class="vnd7-3bnr"/></g><g filter="url(#iMQbSPb)"><circle fill="url(#i1zcOje)" class="yvfl9ccng"/></g><g filter="url(#i9pIVad)"><circle fill="url(#im9xOyb)" class="fz9lzdbjg"/><circle fill="url(#iR4zF4b)" class="fz9lzdbjg"/></g><g filter="url(#iaaXCnb)"><circle class="pfd5q1bve"/><circle fill="url(#iduNZLb)" class="g2kl49blr"/><circle fill="url(#iFUgDOd)" class="g2kl49blr"/></g><g filter="url(#ieoBmpb)"><path fill="url(#iD9SfHe)" class="yn67kac_x"/><path fill="url(#iKRJzCc)" class="yn67kac_x"/><path fill="url(#iA6AuMd)" class="yn67kac_x"/><path fill="url(#iUbcbSb)" class="yn67kac_x"/><path fill="url(#ijilfSV)" class="yn67kac_x"/></g><g filter="url(#ilZJ2Uc)"><path class="ekx7_zbkg"/><path fill="url(#iZF8J1c)" class="s928k-bbr"/><path fill="url(#i9gPoae)" class="s928k-bbr"/><path fill="url(#iEfUUPZ)" class="s928k-bbr"/><path fill="url(#iyus1BD)" class="s928k-bbr"/><path fill="url(#iI2j2Wd)" class="s928k-bbr"/></g><path fill="url(#inYRBkc)" class="s928k-bbr"/><path fill="url(#iq5mUvc)" class="s928k-bbr"/><g filter="url(#ifnONqd)"><path class="vvcavacgl"/></g><g filter="url(#i4dTGEe)"><path class="mgryk5zcn"/><path fill="url(#iXNgone)" class="s92qf38vu"/><path fill="url(#iw4Mafd)" class="s92qf38vu"/><path fill="url(#if0YgOe)" class="s92qf38vu"/></g><path fill="url(#iboBfte)" class="s92qf38vu"/><path stroke="url(#iBNPIgc)" class="bpu3-mkae"/><g filter="url(#i7Rd0GT)"><path class="mbl32db4s"/></g><g filter="url(#i9TEkme)"><path class="ibiq491ju"/></g><path class="e5g237bpr"/><path fill="url(#i1zWIdg)" class="h8c0h4b4e"/><path class="y7oc3mbot"/><g filter="url(#iegxSKW)"><path class="y7le_2b4d"/><path fill="url(#imXScKe)" class="xcxepbb7v"/></g><g filter="url(#izo6wtd)"><path fill="url(#iO1HvIZ)" class="jktump1ii"/></g><path class="sgc17tz1m"/><path fill="url(#ixGLUvb)" class="sqo1tozkd"/><path class="lmp3tbc4i"/><g filter="url(#i5fCSHc)"><path fill="url(#iBRILTb)" class="villdybrj"/></g><g filter="url(#icLxEhd)"><ellipse transform="rotate(-27.914 13.562 10.01)" class="p4imrhb0o"/><ellipse fill="url(#ioTRjhb)" transform="rotate(-27.914 13.562 10.01)" class="avo80iuaw"/></g><g filter="url(#icdKCHe)"><path stroke="url(#iIGmLjb)" class="qm_h9_bff"/></g><g filter="url(#igbAJDc)"><path stroke="url(#iiRTKve)" class="rlmd0s9nt"/></g><defs><radialGradient id="iJrCKHO" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.22 24)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="iiwV82d" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.189 8.21)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="i8rXvVc" cx="0" cy="0" r="1" gradientTransform="rotate(77.152 -6.36 23.613)scale(3.65398 4.0429)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="iBGIKee" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.992 30.07)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="iwQ0RBe" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.358 24.782)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="iZPCpEV" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.726 12.38)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="iPVdyyd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.256 22.032)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="iRVtLTv" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.569 20.407)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="iAK8KpR" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 16.026 18.626)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="lc4rehg1n"/><stop offset="1" class="h1aoh3b9a"/></radialGradient><radialGradient id="i0dKUwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.39 30.563)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="stn4eib-z"/><stop offset="1" class="z99vy1qwj"/></radialGradient><radialGradient id="iFdEnnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 19.164 18.188)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="i9ppVec" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.472 26.63)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="iugVQdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.164 24.938)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="itXBFts" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.386 11.318)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="ivH5hic" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.155 24.993)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="inNG5pb" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.327 19.564)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="iUUiN0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 12.124 18.392)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="iPOFEtj" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -17.094 24.29)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="inDW3ld" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.72628 3.2225 0 16.01 18.79)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="n4z74fjlj"/><stop offset=".577" class="ksq8klecm"/><stop offset="1" class="r7ehj3y0y"/></radialGradient><radialGradient id="iOrCkHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.30438 0 18.53 16.454)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ad-0z61hw"/><stop offset="1" class="p6pfsuaja"/></radialGradient><radialGradient id="i0i9dNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.608 20.11)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="iZNnjPT" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.808 12.237)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="s96-1fbmn"/><stop offset="1" class="pvle9ybys"/></radialGradient><radialGradient id="ixlrYod" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.147 18.108)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="ixOhefd" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.274 25.978)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="ik9dNTB" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.155 23.641)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="i1cqWIb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 9.6 10.787)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iR4zF4b" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.154 10.523)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iduNZLb" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.74 11.609)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iFUgDOd" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 20.782 10.787)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iKRJzCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.6693 -10.1935 0 16.488 7.446)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="vpd4dcexx"/><stop offset="1" class="upbi0xbpg"/></radialGradient><radialGradient id="iUbcbSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 18.363 9.516)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="ijilfSV" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.805 9.483)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iZF8J1c" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.101 6.364)scale(5.6057 9.53299)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iEfUUPZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.06682 -1.86131 .91413 -.03282 11.826 7.333)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iyus1BD" cx="0" cy="0" r="1" gradientTransform="matrix(.85907 -1.96631 1.60368 .70064 20.243 9.05)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="iI2j2Wd" cx="0" cy="0" r="1" gradientTransform="matrix(.9927 1.23176 -1.08755 .87648 15.242 2.187)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="inYRBkc" cx="0" cy="0" r="1" gradientTransform="matrix(.18136 .78313 -1.28748 .29815 16.712 2.187)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iq5mUvc" cx="0" cy="0" r="1" gradientTransform="matrix(.72544 .89725 -2.0104 1.62544 11.672 3.915)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="i1zWIdg" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90308 -1.06858 0 18.195 10.44)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="imXScKe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.479 .695)scale(.37817 .52064)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixGLUvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90312 -1.06863 0 13.833 10.44)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ioTRjhb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.855 -1.506)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iAUl3Ge" x1="23.335" x2="23.022" y1="24.68" y2="24.68" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="ijIhoqc" x1="8.756" x2="9.092" y1="24.68" y2="24.68" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="ipQ5NMb" x1="16.202" x2="16.202" y1="31.032" y2="29.22" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iTS35re" x1="8.841" x2="23.217" y1="15.509" y2="15.509" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iisv4we" x1="8.841" x2="23.217" y1="15.479" y2="15.479" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iuuCRpQ" x1="7.02" x2="7.02" y1="30.845" y2="29.385" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="itPSr4c" x1="22.692" x2="23.47" y1="25.718" y2="25.718" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iSGfHnb" x1="16.202" x2="23.827" y1="27.064" y2="19.47" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="isGCYIb" x1="21.916" x2="16.8" y1="18.459" y2="23.977" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="iEUguFc" x1="20.07" x2="19.912" y1="15.74" y2="17.802" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="iCUnuye" x1="17.608" x2="18.764" y1="18.985" y2="19.47" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="iG3VIRc" x1="12.296" x2="12.624" y1="23.282" y2="22.923" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="iDtygHb" x1="20.335" x2="19.663" y1="23.751" y2="23.767" gradientUnits="userSpaceOnUse"><stop offset=".294" class="w_l8deb9l"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="ixWEuPe" x1="12.23" x2="12.23" y1="19.949" y2="28.532" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="i5mT0wc" x1="9.54" x2="10.434" y1="25.348" y2="25.348" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iGXiowe" x1="13.913" x2="14.585" y1="25.359" y2="25.359" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="ijZYXiZ" x1="14.975" x2="14.733" y1="24.876" y2="24.876" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="i1zcOje" x1="11.269" x2="10.629" y1="11.066" y2="11.066" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="im9xOyb" x1="21.868" x2="21.049" y1="9.696" y2="12.232" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iD9SfHe" x1="20.052" x2="12.416" y1="11.177" y2="12.315" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iA6AuMd" x1="10.621" x2="12.934" y1="13.873" y2="13.571" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="i9gPoae" x1="11.156" x2="14.058" y1="10.52" y2="5.366" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iXNgone" x1="15.153" x2="16.091" y1="11.836" y2="11.836" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iw4Mafd" x1="16.955" x2="15.93" y1="12.158" y2="12.144" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="if0YgOe" x1="16.211" x2="16.211" y1="12.901" y2="12.328" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iboBfte" x1="16.142" x2="16.142" y1="12.943" y2="12.775" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="iBNPIgc" x1="14.98" x2="15.415" y1="14.516" y2="13.829" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iO1HvIZ" x1="18.973" x2="18.66" y1="10.159" y2="10.353" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBRILTb" x1="14.576" x2="14.263" y1="10.159" y2="10.353" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIGmLjb" x1="18.989" x2="18.569" y1="8.02" y2="7.162" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iiRTKve" x1="13.685" x2="12.496" y1="7.892" y2="7.394" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><filter id="iOIcGsb" width="7.147" height="11.557" x="9.055" y="15.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".5"/></filter><filter id="iBoAe7p" width="7.147" height="11.557" x="15.949" y="15.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".5"/></filter><filter id="ikUQJOy" width="3.699" height="3.699" x="17.02" y="24.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".375"/></filter><filter id="iU25uMd" width="1.42" height="1.42" x="18.991" y="24.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24155"/></filter><filter id="ij3z2rd" width="5.381" height="7.171" x="9.54" y="19.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24155"/></filter><filter id="iWWLpGx" width="5.3" height="6.89" x="9.606" y="19.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".15"/></filter><filter id="itALbmc" width="3.539" height="3.339" x="9.6" y="9.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24155"/></filter><filter id="iMQbSPb" width="2.99" height="2.99" x="9.774" y="9.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".25"/></filter><filter id="i9pIVad" width="3.589" height="3.589" x="19.113" y="8.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24155"/></filter><filter id="iaaXCnb" width="2.99" height="2.99" x="19.287" y="9.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".25"/></filter><filter id="ieoBmpb" width="10.373" height="12.177" x="10.859" y="5.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24155"/></filter><filter id="ilZJ2Uc" width="12.601" height="8.543" x="9.716" y="1.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24155"/></filter><filter id="ifnONqd" width="3.26" height="4.181" x="14.148" y="9.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".375"/></filter><filter id="i4dTGEe" width="2.377" height="3.181" x="14.829" y="9.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".125"/></filter><filter id="i7Rd0GT" width="2.979" height="1.873" x="17.199" y="7.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24155"/></filter><filter id="i9TEkme" width="2.98" height="1.873" x="12.052" y="7.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24155"/></filter><filter id="iegxSKW" width=".787" height=".696" x="17.462" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".05"/></filter><filter id="izo6wtd" width=".891" height=".913" x="18.301" y="9.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".1"/></filter><filter id="i5fCSHc" width=".986" height="1.04" x="13.86" y="9.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".1"/></filter><filter id="icLxEhd" width=".913" height=".704" x="13.105" y="9.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".05"/></filter><filter id="icdKCHe" width="3.099" height="1.681" x="17.052" y="7.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".25"/></filter><filter id="igbAJDc" width="3.177" height="1.738" x="11.833" y="7.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24155" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-health-worker-medium-light" /></template>
<style>
.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.ad-0z61hw {
  stop-color: var(--svg-color--552e54, #552E54);
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.avo80iuaw {
  cx: 13.562px;
  cy: 10.01px;
  rx: 0.389px;
  ry: 0.197px;
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bgvgsebrk {
  d: path("m21.919 20.224l-.733.13a.213.213 0 0 0-.12.352l.704.77a.216.216 0 0 1-.009.297l-4.506 4.598c-.111.112-.306.037-.306-.12v-3.329c0-.037.01-.065.019-.102l2.54-5.887a.15.15 0 0 1 .037-.065a9.7 9.7 0 0 1 2.365 1.122l.185 2.002a.214.214 0 0 1-.176.232");
}

.bhnf0hx0r {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.216 26.363h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.bpu3-mkae {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.655 13.545c.393.205.862.322 1.362.322c.504 0 .968-.117 1.362-.322a.2.2 0 0 1 .241.04a.186.186 0 0 1 .021.24m-2.986-.28l2.945.253m-2.945-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.221.253m3.207.028l-.041-.028m.041.028l-.041-.028m.041.028a1.94 1.94 0 0 1-1.624.868c-.682 0-1.28-.347-1.624-.868m3.207-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.583-.846m-.041.028l.04-.028m-.04.028l.04-.028");
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

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d1d_ubb3a {
  d: path("M16.05 15.48h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.dap6i3b6w {
  d: path("M15.396 21.76c.262.516.262.942.262 1.306v2.992c0 .17-.208.26-.327.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.118-.13.05-.35-.13-.38l-.783-.14a.23.23 0 0 1-.188-.25l.187-2.06a.25.25 0 0 1 .113-.186a10.5 10.5 0 0 1 2.426-1.134a.3.3 0 0 1 .04.08z");
}

.dj1fde44s {
  d: path("M16.01 18.79a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.dxszyubmb {
  stop-color: var(--svg-color--d3cfda, #D3CFDA);
}

.e---z_byu {
  stop-color: var(--svg-color--ad9ec2, #AD9EC2);
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.e5g237bpr {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.404 9.357c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.227-.272c.125-.64.69-1.127 1.37-1.127");
}

.ekx7_zbkg {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m20.835 4.31l.43.214c.75.373 1.18 1.226 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.907.108-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.854c0-.266-.214-.48-.429-.533c-.643-.16-1.984-.426-3.915-.426s-3.272.266-3.916.426a.52.52 0 0 0-.429.533v.854c0 .32-.107.64-.375.853l-.161.16c-.215.16-.322.48-.322.747c.054.586.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.072-2.08l.43-.213c.268-.16.536-.373.804-.586l.966-1.014c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.662 0c.805-.266 1.717-.053 2.36.534l.805.8c.214.266.482.426.804.586");
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
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

.fz9lzdbjg {
  cx: 20.782px;
  cy: 10.787px;
  r: 1.669px;
}

.g2kl49blr {
  cx: 20.782px;
  cy: 10.787px;
  r: 0.995px;
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1aoh3b9a {
  stop-color: var(--svg-color--0a4b92, #0A4B92);
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.h8c0h4b4e {
  d: path("M18.198 9.629a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hr1mvxbss {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.87 27.028a1.1 1.1 0 1 0 0-2.198a1.1 1.1 0 0 0 0 2.198");
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.ibiq491ju {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m12.244 8.068l.002-.002l.005-.003l.011-.01a1.4 1.4 0 0 1 .155-.107c.1-.063.241-.14.42-.211a2.83 2.83 0 0 1 1.493-.158a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.679-.824");
}

.iy2m1tbkn {
  d: path("M26.852 28.04c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59v11.78h3.65z");
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j4ihnwt8k {
  d: path("M16.675 21.76c-.262.516-.262.942-.262 1.306v2.992c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.754-.83a.23.23 0 0 1 .13-.38l.782-.14a.23.23 0 0 0 .189-.25l-.188-2.06a.25.25 0 0 0-.113-.186a10.5 10.5 0 0 0-2.425-1.134a.3.3 0 0 0-.04.08z");
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jktump1ii {
  d: path("M18.992 10.404a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.jrr-31bdb {
  fill: var(--svg-color--5a4b7e, #5A4B7E);
  fill-rule: evenodd;
  d: path("M15.96 15.19a3.24 3.24 0 0 0-3.239 3.24v2.15h-.981v-2.15a4.22 4.22 0 0 1 8.441 0v7.12H19.2v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.ksq8klecm {
  stop-color: var(--svg-color--91675a, #91675A);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv70nqbkg {
  stop-color: var(--svg-color--b49089, #B49089);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l-etq6b9a {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
}

.lc4rehg1n {
  stop-color: var(--svg-color--3272ac, #3272AC);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll7oxmbau {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
  stop-opacity: 0;
}

.lmp3tbc4i {
  fill: var(--svg-color--000, #000);
  d: path("M14.342 10.52a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .06-.235");
}

.lnyefdcqm {
  stop-color: var(--svg-color--c8bfd6, #C8BFD6);
}

.lpc21p-wa {
  stop-color: var(--svg-color--553c83, #553C83);
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lwlcnvb_i {
  d: path("M19.7 26.8a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbl32db4s {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m19.736 8.068l-.001-.001l-.002-.002l-.005-.003l-.012-.01a2 2 0 0 0-.154-.107a2.6 2.6 0 0 0-.42-.211a2.83 2.83 0 0 0-1.493-.158a.534.534 0 1 0 .167 1.054c.398-.063.716.01.934.096a1.5 1.5 0 0 1 .3.16l.008.006a.534.534 0 0 0 .678-.824");
}

.mgryk5zcn {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.635 10.502l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.699c-.114-.376-.645-.376-.764 0");
}

.n4z74fjlj {
  stop-color: var(--svg-color--a77d70, #A77D70);
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
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

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.p4imrhb0o {
  cx: 13.562px;
  cy: 10.01px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.p6pfsuaja {
  stop-color: var(--svg-color--552e54, #552E54);
  stop-opacity: 0;
}

.pfd5q1bve {
  cx: 20.782px;
  cy: 10.787px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.poxbdpd_y {
  d: path("m5.952 22.84l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67V18.32a10.56 10.56 0 0 0-2.85 4.52");
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.pvle9ybys {
  stop-color: var(--svg-color--4a2657, #4A2657);
  stop-opacity: 0;
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.qm_h9_bff {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.677 7.923c.43-.075 1.269-.053 1.85.398");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r7ehj3y0y {
  stop-color: var(--svg-color--7b5047, #7B5047);
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.rgbkjoszo {
  d: path("M16.012 15.48c-2.74 0-5.3 1.06-7.21 2.84v11.75h14.38V18.29a10.54 10.54 0 0 0-7.17-2.81");
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rlmd0s9nt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.458 8.442c.327-.29 1.042-.594 1.927-.453");
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.rwlwafb9a {
  d: path("M16.518 22.584c0-.04-.01-.203 0-.243l2.663-6.292c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.362c.01.03.054.05.054.09l.056 3.598h.01v3.97h.79V26.1l.078-3.415z");
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s7d57ubpe {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.232 20.224l.732.13a.213.213 0 0 1 .121.352l-.705.77a.216.216 0 0 0 .01.297l4.506 4.598c.111.112.306.037.306-.12v-3.329c0-.037-.01-.065-.019-.102l-2.54-5.887a.15.15 0 0 0-.037-.065a9.7 9.7 0 0 0-2.365 1.122l-.185 2.002a.214.214 0 0 0 .176.232");
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.s928k-bbr {
  d: path("m20.835 4.31l.43.214c.75.373 1.18 1.226 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.907.108-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.854c0-.266-.214-.48-.429-.533c-.643-.16-1.984-.426-3.915-.426s-3.272.266-3.916.426a.52.52 0 0 0-.429.533v.854c0 .32-.107.64-.375.853l-.161.16c-.215.16-.322.48-.322.747c.054.586.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.072-2.08l.43-.213c.268-.16.536-.373.804-.586l.966-1.014c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.662 0c.805-.266 1.717-.053 2.36.534l.805.8c.214.266.482.426.804.586");
}

.s92qf38vu {
  d: path("m15.635 10.502l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.699c-.114-.376-.645-.376-.764 0");
}

.s96-1fbmn {
  stop-color: var(--svg-color--4a2657, #4A2657);
}

.sb6u0tpkd {
  d: path("M19.7 26.25a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sgc17tz1m {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.624 9.357c-.653 0-1.205.45-1.355 1.058a.275.275 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
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

.sqo1tozkd {
  d: path("M13.83 9.629a.892.892 0 0 0-.859 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.stn4eib-z {
  stop-color: var(--svg-color--3865b8, #3865B8);
}

.swjm6kdny {
  fill-rule: evenodd;
  d: path("M14.921 23.8v2.47c0 .36-.29.65-.65.65h-.58v-.98h.249V23.8z");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.u2-isd21s {
  d: path("M16.38 15.48c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.upbi0xbpg {
  stop-color: var(--svg-color--9f6e75, #9F6E75);
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6un4nbff {
  fill-rule: evenodd;
  d: path("M15.96 15.19a3.24 3.24 0 0 0-3.239 3.24v2.15h-.981v-2.15a4.22 4.22 0 0 1 8.441 0v7.12H19.2v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.villdybrj {
  d: path("M14.646 10.416c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.vnd7-3bnr {
  cx: 11.269px;
  cy: 10.787px;
  r: 1.669px;
}

.vpd4dcexx {
  stop-color: var(--svg-color--c88d87, #C88D87);
  stop-opacity: 0;
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vvcavacgl {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.742 10.665l-.82 1.7c-.103.35.142.699.487.699h.737c.346 0 .59-.355.488-.7l-.498-1.699c-.107-.376-.283-.376-.394 0");
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

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w0rhj52ia {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
  stop-opacity: 0;
}

.wviklbcfj {
  fill-rule: evenodd;
  d: path("M12.23 20.93a1.71 1.71 0 0 0-1.709 1.71v3.3h.67a.49.49 0 0 1 0 .98h-1a.65.65 0 0 1-.651-.65v-3.63a2.69 2.69 0 0 1 5.381 0v3.63c0 .36-.29.65-.65.65h-.93a.49.49 0 0 1 0-.98h.599v-3.3c0-.94-.762-1.71-1.71-1.71");
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
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

.xcxepbb7v {
  d: path("M18.132 9.817c.063.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.y7le_2b4d {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.132 9.817c.063.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.y7oc3mbot {
  fill: var(--svg-color--000, #000);
  d: path("M17.687 10.52c0-.283.227-.51.51-.51a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.yn67kac_x {
  d: path("m10.917 10.175l.05.002s-.054-.854-.108-1.44c0-.267.107-.587.322-.747l.16-.16c.27-.213.376-.533.376-.853v-.854a.52.52 0 0 1 .43-.533c.643-.16 1.984-.426 3.915-.426c1.93 0 3.271.266 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.545.429.96c-.054.533-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.002-3.21 3.002h-3.21c-1.713 0-3.05-1.233-3.21-3.002z");
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.yvfl9ccng {
  cx: 11.269px;
  cy: 10.787px;
  r: 0.995px;
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.z99vy1qwj {
  stop-color: var(--svg-color--3865b8, #3865B8);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zj0w_34ts {
  fill-rule: evenodd;
  d: path("M9.54 26.26v-2.47h.981v2.139h.25v.981h-.58a.65.65 0 0 1-.651-.65");
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

</style>
