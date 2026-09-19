<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNJFlOd)" class="if-0u_k3d"/><path fill="url(#iU98LfO)" class="if-0u_k3d"/><path fill="url(#i83eApe)" class="if-0u_k3d"/><path fill="url(#ivnDNFd)" class="if-0u_k3d"/><path fill="url(#iktcDPe)" class="if-0u_k3d"/><path fill="url(#iUOv0cc)" class="if-0u_k3d"/><path fill="url(#idkpVzl)" class="if-0u_k3d"/><path fill="url(#iLI8I4b)" class="vf8rvhbeo"/><path fill="url(#iQb0aOb)" class="kl-fs7b7s"/><path fill="url(#iN4Zboe)" class="csnhp8bwf"/><path fill="url(#irxZE6c)" class="csnhp8bwf"/><path fill="url(#ire3wOc)" class="csnhp8bwf"/><path fill="url(#iGZPLmb)" class="dfd47wpsr"/><path fill="url(#i7oCbiE)" class="dfd47wpsr"/><path fill="url(#i8MryuM)" class="dfd47wpsr"/><path fill="url(#idXo5xb)" class="gumu6bgam"/><path fill="url(#iPmCLfb)" class="gumu6bgam"/><path fill="url(#iLI8I4b)" class="vf8rvhbeo"/><path fill="url(#iQb0aOb)" class="kl-fs7b7s"/><g filter="url(#iVxygHK)"><path class="uzulhd38a"/></g><g filter="url(#igFpwvb)"><path fill="url(#ieEAkZg)" class="txm9fnhen"/></g><path fill="url(#iBCk49d)" class="uvfjeibim"/><path fill="url(#iueI61y)" class="uvfjeibim"/><path fill="url(#iNrsydV)" class="uvfjeibim"/><path fill="url(#iK79jIb)" class="uvfjeibim"/><path fill="url(#iI8q5Mc)" class="uvfjeibim"/><path fill="url(#i6jMHsc)" class="uvfjeibim"/><path fill="url(#iaT7u0b)" class="yvmcg0bop"/><path fill="url(#i0TPOhd)" class="yvmcg0bop"/><path fill="url(#ibFLL7c)" class="yvmcg0bop"/><path fill="url(#iwxOF6c)" class="yvmcg0bop"/><path fill="url(#i1ePs0e)" class="yvmcg0bop"/><path fill="url(#iG3iuVd)" class="yvmcg0bop"/><path fill="url(#iJjl5rb)" class="wylb3y7qp"/><path clip-rule="evenodd" class="umc7xqbzf"/><path fill="url(#iQrV9gW)" clip-rule="evenodd" class="u5rff1bsn"/><path fill="url(#ifXf4ld)" clip-rule="evenodd" class="u5rff1bsn"/><path fill="url(#ijcq4Jd)" clip-rule="evenodd" class="u5rff1bsn"/><path fill="url(#iBa68hc)" clip-rule="evenodd" class="u5rff1bsn"/><g filter="url(#izuydSd)"><path class="q9lj33lko"/></g><path fill="url(#iDeO7Cc)" class="z3sz94blu"/><g filter="url(#i8EtkBe)"><path fill="url(#iW6AAJS)" class="smwepnd8m"/></g><g filter="url(#iUPQ94d)"><path fill="url(#iRo1Ioe)" clip-rule="evenodd" class="pgcq1y0dj"/></g><g filter="url(#id0Thvc)"><path class="agc1kybmm"/></g><path fill="url(#iRRHzCm)" clip-rule="evenodd" class="pwktw8qyn"/><path fill="url(#isn6voV)" clip-rule="evenodd" class="pwktw8qyn"/><path fill="url(#iVE0uPd)" clip-rule="evenodd" class="wo2o_-bra"/><path fill="url(#ifbvp3d)" clip-rule="evenodd" class="wo2o_-bra"/><g filter="url(#i6o0DCq)"><circle fill="url(#i2qSzub)" class="cqvoy-l_h"/></g><circle fill="url(#iLXs2Px)" class="cqvoy-l_h"/><g filter="url(#iB6VB4d)"><circle fill="url(#iwiTobe)" class="zntydvbsi"/></g><g filter="url(#iPmnAxe)"><circle fill="url(#i66AMsc)" class="kla98tnqi"/><circle fill="url(#iJHRTUb)" class="kla98tnqi"/></g><g filter="url(#ig9Qvwa)"><circle class="nb8_fiz-q"/><circle fill="url(#inmwW8c)" class="q-4ds2blc"/><circle fill="url(#iZNhXre)" class="q-4ds2blc"/></g><g filter="url(#iLaLJec)"><path fill="url(#iiIW4md)" class="zu-avmbgd"/><path fill="url(#i8jTTpd)" class="zu-avmbgd"/><path fill="url(#ijgDCae)" class="zu-avmbgd"/></g><path fill="url(#iiUIh2b)" class="e0g2_53ia"/><path fill="url(#igOqJze)" class="e0g2_53ia"/><path fill="url(#iHFlCWb)" class="e0g2_53ia"/><g filter="url(#idvPfpe)"><path fill="url(#idt0cSb)" class="v2w_41gvb"/></g><g filter="url(#iNCtICe)"><path class="hhl-yjd4h"/><path fill="url(#i8pCgbe)" class="lthcxqb3e"/><path fill="url(#idxOuGd)" class="lthcxqb3e"/><path fill="url(#ixNs8sc)" class="lthcxqb3e"/><path fill="url(#iu49BAb)" class="lthcxqb3e"/></g><g filter="url(#ieNtcje)"><path class="cp4zt9b0o"/></g><g filter="url(#iJnOUib)"><path class="ccbwacbvx"/><path fill="url(#i8LFxIJ)" class="ld4khjjek"/><path fill="url(#iopjUDb)" class="ld4khjjek"/><path fill="url(#iKTgu7F)" class="ld4khjjek"/><path fill="url(#imuKree)" class="ld4khjjek"/></g><path fill="url(#ili4kab)" class="ld4khjjek"/><path stroke="url(#iVuvVve)" class="raw0s2iug"/><g filter="url(#ijY9EWb)"><path class="k32tosmic"/><path fill="url(#iTr7xqb)" class="zp1qdzbre"/></g><g filter="url(#iH2Koab)"><path class="jc11ehb6h"/><path fill="url(#ilXRSrb)" class="qz903vb7g"/></g><path class="v1v5dlbai"/><path fill="url(#ig1TFoe)" class="d93ugcbep"/><path class="i36nmybyw"/><g filter="url(#ikVFRLb)"><path class="gcl044b_z"/><path fill="url(#iwjwsIe)" class="a_e7oqseo"/></g><g filter="url(#ioIPxTb)"><path fill="url(#i7tErub)" class="svjyqwbml"/></g><path class="q2y3xnnbt"/><path fill="url(#iKsp1Hb)" class="m2xkqcbxw"/><path class="zc6j4ac_b"/><g filter="url(#iclseMb)"><path fill="url(#i2kUlPZ)" class="hayvbunzw"/></g><g filter="url(#i8yb9Cd)"><ellipse transform="rotate(-27.914 13.527 9.94)" class="quc1tob3z"/><ellipse fill="url(#ikJTq7w)" transform="rotate(-27.914 13.527 9.94)" class="x3ib1_bop"/></g><g filter="url(#iUmTSAc)"><path stroke="url(#ilJ9X6d)" class="biuc1mbbx"/></g><g filter="url(#iVFDHFb)"><path stroke="url(#iTD0Imb)" class="cb0-fytsp"/></g><g filter="url(#itlPz3b)"><path stroke="url(#irMSW3b)" class="o6jgiab6u"/></g><defs><radialGradient id="iNJFlOd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.22 23.93)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="iktcDPe" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.169 8.175)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="iUOv0cc" cx="0" cy="0" r="1" gradientTransform="rotate(77.152 -6.316 23.578)scale(3.65398 4.0429)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="idkpVzl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.992 30)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="iN4Zboe" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.358 24.712)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="irxZE6c" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.7 12.344)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="iGZPLmb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.256 21.962)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="i7oCbiE" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.569 20.337)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="idXo5xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 16.026 18.555)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="lc4rehg1n"/><stop offset="1" class="h1aoh3b9a"/></radialGradient><radialGradient id="iPmCLfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.39 30.493)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="stn4eib-z"/><stop offset="1" class="z99vy1qwj"/></radialGradient><radialGradient id="iK79jIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 19.164 18.118)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="iI8q5Mc" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.472 26.56)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="i6jMHsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.164 24.868)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="iaT7u0b" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.392 11.283)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="i0TPOhd" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.155 24.923)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="iwxOF6c" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.326 19.493)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="i1ePs0e" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 12.124 18.321)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="iG3iuVd" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -17.017 24.254)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="iJjl5rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.72628 3.2225 0 16.01 18.72)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="bhcvbibep"/><stop offset=".577" class="b6u0tac-v"/><stop offset="1" class="zf0l_-i4f"/></radialGradient><radialGradient id="ifXf4ld" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.30438 0 18.53 16.384)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ad-0z61hw"/><stop offset="1" class="p6pfsuaja"/></radialGradient><radialGradient id="ijcq4Jd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.608 20.04)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="iBa68hc" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.83 12.202)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="s96-1fbmn"/><stop offset="1" class="pvle9ybys"/></radialGradient><radialGradient id="iDeO7Cc" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.167 18.073)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="iW6AAJS" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.274 25.907)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="isn6voV" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.155 23.571)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="i2qSzub" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 9.566 10.717)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iLXs2Px" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.843 3.268)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iJHRTUb" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.12 10.452)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="inmwW8c" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.706 11.538)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iZNhXre" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.657 30.585)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="i8jTTpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.329 9.445)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="ijgDCae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 13.771 9.58)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iHFlCWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.32774 -10.3217 0 15.855 9.183)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="dcym8repk"/><stop offset=".884" class="fkee40m0y"/><stop offset="1" class="an_-aznlj"/></radialGradient><radialGradient id="i8pCgbe" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.48 -9.964)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="idxOuGd" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -43.484 205.9)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="ixNs8sc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.983 2.116)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iu49BAb" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 9.534 8.934)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="imuKree" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.31 12.323)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iTr7xqb" cx="0" cy="0" r="1" gradientTransform="matrix(.10418 -.60322 1.78457 .30822 18.425 8.633)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="ilXRSrb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.765 -3.568)scale(.61215 1.81109)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="ig1TFoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.162 10.035)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iwjwsIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.933 10.12)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKsp1Hb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.799 10.035)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ikJTq7w" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.804 -1.524)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iU98LfO" x1="23.335" x2="23.022" y1="24.61" y2="24.61" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="i83eApe" x1="8.756" x2="9.092" y1="24.61" y2="24.61" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="ivnDNFd" x1="16.202" x2="16.202" y1="30.962" y2="29.149" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iLI8I4b" x1="8.841" x2="23.217" y1="15.439" y2="15.439" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iQb0aOb" x1="8.841" x2="23.217" y1="15.409" y2="15.409" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ire3wOc" x1="7.02" x2="7.02" y1="30.774" y2="29.314" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="i8MryuM" x1="22.692" x2="23.47" y1="25.648" y2="25.648" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="ieEAkZg" x1="16.202" x2="23.827" y1="26.993" y2="19.399" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="iBCk49d" x1="21.916" x2="16.8" y1="18.389" y2="23.907" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="iueI61y" x1="20.07" x2="19.912" y1="15.67" y2="17.732" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="iNrsydV" x1="17.608" x2="18.764" y1="18.915" y2="19.399" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="ibFLL7c" x1="12.296" x2="12.624" y1="23.212" y2="22.852" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="iQrV9gW" x1="20.335" x2="19.663" y1="23.68" y2="23.696" gradientUnits="userSpaceOnUse"><stop offset=".294" class="w_l8deb9l"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="iRo1Ioe" x1="12.23" x2="12.23" y1="19.878" y2="28.462" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="iRRHzCm" x1="9.54" x2="10.434" y1="25.278" y2="25.278" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iVE0uPd" x1="13.913" x2="14.585" y1="25.288" y2="25.288" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="ifbvp3d" x1="14.975" x2="14.733" y1="24.805" y2="24.805" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="iwiTobe" x1="11.235" x2="10.595" y1="10.996" y2="10.996" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="i66AMsc" x1="21.834" x2="21.015" y1="9.626" y2="12.162" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iiIW4md" x1="20.018" x2="12.382" y1="11.106" y2="12.244" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iiUIh2b" x1="10.587" x2="12.469" y1="13.802" y2="13.735" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="igOqJze" x1="20.903" x2="19.791" y1="12.961" y2="12.864" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="idt0cSb" x1="15.451" x2="23.595" y1="8.122" y2="5.206" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="i8LFxIJ" x1="15.119" x2="16.057" y1="11.766" y2="11.766" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iopjUDb" x1="16.921" x2="15.896" y1="12.088" y2="12.073" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iKTgu7F" x1="16.177" x2="16.177" y1="12.83" y2="12.257" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="ili4kab" x1="16.108" x2="16.108" y1="12.872" y2="12.705" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="iVuvVve" x1="14.946" x2="15.381" y1="14.445" y2="13.758" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="i7tErub" x1="18.939" x2="18.626" y1="10.089" y2="10.282" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2kUlPZ" x1="14.542" x2="14.229" y1="10.089" y2="10.282" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilJ9X6d" x1="18.955" x2="18.535" y1="7.949" y2="7.091" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iTD0Imb" x1="13.651" x2="12.462" y1="7.822" y2="7.323" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="irMSW3b" x1="11.321" x2="11.321" y1="5.808" y2="7.964" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><filter id="iVxygHK" width="7.147" height="11.557" x="9.055" y="15.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".5"/></filter><filter id="igFpwvb" width="7.147" height="11.557" x="15.949" y="15.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".5"/></filter><filter id="izuydSd" width="3.699" height="3.699" x="17.02" y="24.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".375"/></filter><filter id="i8EtkBe" width="1.42" height="1.42" x="18.991" y="24.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24152"/></filter><filter id="iUPQ94d" width="5.381" height="7.171" x="9.54" y="19.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24152"/></filter><filter id="id0Thvc" width="5.3" height="6.89" x="9.606" y="19.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".15"/></filter><filter id="i6o0DCq" width="3.539" height="3.339" x="9.566" y="9.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24152"/></filter><filter id="iB6VB4d" width="2.99" height="2.99" x="9.74" y="9.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".25"/></filter><filter id="iPmnAxe" width="3.589" height="3.589" x="19.078" y="8.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24152"/></filter><filter id="ig9Qvwa" width="2.99" height="2.99" x="19.253" y="9.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".25"/></filter><filter id="iLaLJec" width="10.373" height="12.177" x="10.825" y="5.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24152"/></filter><filter id="idvPfpe" width="8.246" height="7.066" x="14.153" y="3.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation="1"/></filter><filter id="iNCtICe" width="12.601" height="8.543" x="9.682" y="1.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24152"/></filter><filter id="ieNtcje" width="3.26" height="4.181" x="14.114" y="9.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".375"/></filter><filter id="iJnOUib" width="2.377" height="3.181" x="14.794" y="9.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".125"/></filter><filter id="ijY9EWb" width="2.979" height="1.873" x="17.165" y="7.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24152"/></filter><filter id="iH2Koab" width="2.98" height="1.873" x="12.018" y="7.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24152"/></filter><filter id="ikVFRLb" width=".787" height=".696" x="17.428" y="9.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".05"/></filter><filter id="ioIPxTb" width=".891" height=".913" x="18.267" y="9.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".1"/></filter><filter id="iclseMb" width=".986" height="1.04" x="13.826" y="9.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".1"/></filter><filter id="i8yb9Cd" width=".913" height=".704" x="13.071" y="9.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".05"/></filter><filter id="iUmTSAc" width="3.099" height="1.681" x="17.018" y="7.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".25"/></filter><filter id="iVFDHFb" width="3.177" height="1.738" x="11.799" y="7.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".25"/></filter><filter id="itlPz3b" width="1.008" height="2.269" x="10.817" y="5.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24152" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-health-worker-medium" /></template>
<style>
.a_e7oqseo {
  d: path("M18.098 9.747c.064.085-.07.189-.22.302c-.151.112-.264.192-.327.107c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.ad-0z61hw {
  stop-color: var(--svg-color--552e54, #552E54);
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.agc1kybmm {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.216 26.293h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.an_-aznlj {
  stop-color: var(--svg-color--7c5267, #7C5267);
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.b6u0tac-v {
  stop-color: var(--svg-color--6a4749, #6A4749);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bhcvbibep {
  stop-color: var(--svg-color--815c59, #815C59);
}

.biuc1mbbx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.643 7.853c.43-.076 1.269-.054 1.85.397");
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.cb0-fytsp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.424 8.371c.327-.289 1.042-.593 1.927-.452");
}

.ccbwacbvx {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.6 10.432l-.53 1.7a.537.537 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.531-1.7c-.114-.376-.645-.376-.764 0");
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cp4zt9b0o {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.707 10.595l-.82 1.7c-.101.349.143.698.488.698h.737c.346 0 .59-.354.488-.699l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.cqvoy-l_h {
  cx: 11.235px;
  cy: 10.717px;
  r: 1.669px;
}

.csnhp8bwf {
  d: path("m5.951 22.769l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67v-11.75a10.56 10.56 0 0 0-2.85 4.52");
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d93ugcbep {
  d: path("M18.164 9.558a.892.892 0 0 1 .86 1.127H17.3a.896.896 0 0 1 .864-1.127");
}

.dcym8repk {
  stop-color: var(--svg-color--9b7168, #9B7168);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dfd47wpsr {
  d: path("M26.852 27.97c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59V30h3.65z");
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
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

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0g2_53ia {
  d: path("M10.825 8.666c0-.267.107-.587.322-.747l.16-.16c.27-.213.376-.533.376-.853v-.853c0-.267.161-.48.43-.534c.643-.16 1.984-.426 3.915-.426c1.93 0 3.271.266 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.533-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.234-3.21-3.003c-.14-1.816-.201-3.638-.367-5.451");
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.fkee40m0y {
  stop-color: var(--svg-color--8f5d78, #8F5D78);
}

.foe4l_bip {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
  stop-opacity: 0;
}

.fr_rdtj9g {
  stop-color: var(--svg-color--d4cae9, #D4CAE9);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.gcl044b_z {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.098 9.747c.064.085-.07.189-.22.302c-.151.112-.264.192-.327.107c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.gumu6bgam {
  d: path("M16.518 22.513c0-.04-.01-.203 0-.243l2.663-6.29c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.36c.01.03.054.05.054.09l.056 3.6h.01V30h.79v-3.97l.078-3.416z");
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

.hayvbunzw {
  d: path("M14.612 10.345c0-.288-.235-.48-.298-.538l-.288.278l.177.362z");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hhl-yjd4h {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m20.801 4.24l.43.213c.75.373 1.18 1.226 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.907.108-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.534c-.644-.16-1.984-.426-3.915-.426s-3.272.266-3.916.426a.52.52 0 0 0-.429.534v.853c0 .32-.107.64-.375.853l-.161.16c-.215.16-.322.48-.322.747c.054.586.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.072-2.08l.43-.212c.268-.16.536-.374.804-.587l.965-1.013c.59-.534 1.449-.694 2.2-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.054 2.36.533l.805.8c.214.267.482.427.804.587");
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.i36nmybyw {
  fill: var(--svg-color--000, #000);
  d: path("M17.653 10.45c0-.283.227-.51.51-.51a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.236");
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.if-0u_k3d {
  d: path("M16.012 15.41c-2.74 0-5.3 1.06-7.21 2.84V30h14.38V18.22a10.54 10.54 0 0 0-7.17-2.81");
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.jc11ehb6h {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m12.21 7.997l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.063.241-.14.42-.21a2.83 2.83 0 0 1 1.492-.16a.534.534 0 1 1-.166 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.678-.824");
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k32tosmic {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M19.702 7.997h-.001l-.002-.002l-.005-.004l-.012-.01a1.4 1.4 0 0 0-.154-.107c-.1-.063-.241-.14-.42-.21a2.83 2.83 0 0 0-1.493-.16a.534.534 0 0 0 .167 1.055c.398-.063.716.01.933.097a1.5 1.5 0 0 1 .309.165a.534.534 0 0 0 .678-.824");
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kl-fs7b7s {
  d: path("M16.05 15.41h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.kla98tnqi {
  cx: 20.748px;
  cy: 10.717px;
  r: 1.669px;
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
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

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lc4rehg1n {
  stop-color: var(--svg-color--3272ac, #3272AC);
}

.ld4khjjek {
  d: path("m15.6 10.432l-.53 1.7a.537.537 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.531-1.7c-.114-.376-.645-.376-.764 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
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

.lthcxqb3e {
  d: path("m20.801 4.24l.43.213c.75.373 1.18 1.226 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.907.108-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.534c-.644-.16-1.984-.426-3.915-.426s-3.272.266-3.916.426a.52.52 0 0 0-.429.534v.853c0 .32-.107.64-.375.853l-.161.16c-.215.16-.322.48-.322.747c.054.586.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.072-2.08l.43-.212c.268-.16.536-.374.804-.587l.965-1.013c.59-.534 1.449-.694 2.2-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.054 2.36.533l.805.8c.214.267.482.427.804.587");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m2xkqcbxw {
  d: path("M13.797 9.558a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nb8_fiz-q {
  cx: 20.748px;
  cy: 10.717px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o6jgiab6u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.45 5.906v.898c-.008.148-.07.48-.258.621");
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

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.p6pfsuaja {
  stop-color: var(--svg-color--552e54, #552E54);
  stop-opacity: 0;
}

.pgcq1y0dj {
  fill-rule: evenodd;
  d: path("M12.23 20.86c-.94 0-1.709.761-1.709 1.709v3.3h.67a.49.49 0 0 1 0 .98h-1a.65.65 0 0 1-.651-.65v-3.63a2.69 2.69 0 0 1 5.381 0v3.63c0 .361-.29.65-.65.65h-.93a.49.49 0 0 1 0-.98h.599v-3.3c0-.94-.762-1.71-1.71-1.71");
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pvle9ybys {
  stop-color: var(--svg-color--4a2657, #4A2657);
  stop-opacity: 0;
}

.pwktw8qyn {
  fill-rule: evenodd;
  d: path("M9.54 26.19v-2.47h.981v2.139h.25v.98h-.58a.65.65 0 0 1-.651-.65");
}

.q-4ds2blc {
  cx: 20.748px;
  cy: 10.717px;
  r: 0.995px;
}

.q2y3xnnbt {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.59 9.286c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.q9lj33lko {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.87 26.958a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.quc1tob3z {
  cx: 13.527px;
  cy: 9.939px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.qz903vb7g {
  d: path("m12.21 7.997l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.063.241-.14.42-.21a2.83 2.83 0 0 1 1.492-.16a.534.534 0 1 1-.166 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.678-.824");
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.raw0s2iug {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.62 13.474a.2.2 0 0 0-.241.041a.19.19 0 0 0-.02.24c.343.52.942.868 1.624.868s1.28-.347 1.624-.868a.19.19 0 0 0-.02-.242a.2.2 0 0 0-.242-.04a2.94 2.94 0 0 1-1.362.324c-.5 0-.969-.118-1.362-.323Z");
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

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.s96-1fbmn {
  stop-color: var(--svg-color--4a2657, #4A2657);
}

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.smwepnd8m {
  d: path("M19.7 26.179a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.sp4_sibjj {
  stop-color: var(--svg-color--5d4f77, #5D4F77);
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.stn4eib-z {
  stop-color: var(--svg-color--3865b8, #3865B8);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.svjyqwbml {
  d: path("M18.958 10.333a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.txm9fnhen {
  d: path("m21.919 20.153l-.733.13a.213.213 0 0 0-.12.352l.704.77a.216.216 0 0 1-.009.297L17.255 26.3c-.111.112-.306.038-.306-.12v-3.329c0-.037.01-.064.019-.102l2.54-5.887a.15.15 0 0 1 .037-.065a9.7 9.7 0 0 1 2.365 1.122l.185 2.003a.214.214 0 0 1-.176.231");
}

.u5rff1bsn {
  fill-rule: evenodd;
  d: path("M15.96 15.12a3.24 3.24 0 0 0-3.239 3.24v2.15h-.981v-2.15a4.22 4.22 0 1 1 8.441 0v7.12H19.2v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.umc7xqbzf {
  fill: var(--svg-color--5a4b7e, #5A4B7E);
  fill-rule: evenodd;
  d: path("M15.96 15.12a3.24 3.24 0 0 0-3.239 3.24v2.15h-.981v-2.15a4.22 4.22 0 1 1 8.441 0v7.12H19.2v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.uvfjeibim {
  d: path("M16.675 21.69c-.262.516-.262.942-.262 1.306v2.991c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.754-.83a.23.23 0 0 1 .13-.38l.782-.14a.23.23 0 0 0 .189-.25l-.188-2.059a.25.25 0 0 0-.113-.186a10.5 10.5 0 0 0-2.425-1.135a.3.3 0 0 0-.04.08z");
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.uzulhd38a {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.232 20.153l.733.13a.213.213 0 0 1 .12.352l-.705.77a.216.216 0 0 0 .01.297l4.506 4.598c.111.112.306.038.306-.12v-3.329c0-.037-.01-.064-.019-.102l-2.54-5.887a.15.15 0 0 0-.037-.065a9.7 9.7 0 0 0-2.365 1.122l-.185 2.003a.214.214 0 0 0 .176.231");
}

.v1v5dlbai {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.37 9.287c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.127");
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v2w_41gvb {
  d: path("m19.946 5.093l-3.077 1.026a1.047 1.047 0 0 0 .47 2.03l3.06-.409z");
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.vf8rvhbeo {
  d: path("M16.38 15.41c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
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

.wo2o_-bra {
  fill-rule: evenodd;
  d: path("M14.921 23.729v2.47c0 .361-.29.65-.65.65h-.58v-.98h.249v-2.14z");
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
}

.wylb3y7qp {
  d: path("M16.01 18.72a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.x3e-lhbqh {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
  stop-opacity: 0;
}

.x3ib1_bop {
  cx: 13.527px;
  cy: 9.939px;
  rx: 0.389px;
  ry: 0.197px;
}

.x7yaztbkk {
  stop-color: var(--svg-color--b3a299, #B3A299);
  stop-opacity: 0;
}

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.yvmcg0bop {
  d: path("M15.396 21.69c.262.516.262.942.262 1.306v2.991c0 .17-.208.26-.327.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.118-.13.05-.35-.13-.38l-.783-.14a.23.23 0 0 1-.188-.25l.187-2.059a.25.25 0 0 1 .113-.186a10.5 10.5 0 0 1 2.426-1.135a.3.3 0 0 1 .04.08z");
}

.z3sz94blu {
  d: path("M19.7 26.729a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.z99vy1qwj {
  stop-color: var(--svg-color--3865b8, #3865B8);
  stop-opacity: 0;
}

.zc6j4ac_b {
  fill: var(--svg-color--000, #000);
  d: path("M14.308 10.45a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .06-.236");
}

.zf0l_-i4f {
  stop-color: var(--svg-color--46323c, #46323C);
}

.zntydvbsi {
  cx: 11.235px;
  cy: 10.717px;
  r: 0.995px;
}

.zp1qdzbre {
  d: path("M19.702 7.997h-.001l-.002-.002l-.005-.004l-.012-.01a1.4 1.4 0 0 0-.154-.107c-.1-.063-.241-.14-.42-.21a2.83 2.83 0 0 0-1.493-.16a.534.534 0 0 0 .167 1.055c.398-.063.716.01.933.097a1.5 1.5 0 0 1 .309.165a.534.534 0 0 0 .678-.824");
}

.zu-avmbgd {
  d: path("m10.883 10.104l.05.002s-.054-.854-.108-1.44c0-.267.107-.587.322-.747l.16-.16c.27-.213.376-.533.376-.853v-.853c0-.267.161-.48.43-.534c.643-.16 1.984-.426 3.915-.426c1.93 0 3.271.266 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.533-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.234-3.21-3.003z");
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
