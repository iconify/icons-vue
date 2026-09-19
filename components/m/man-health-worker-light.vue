<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNJFlOd)" class="if-0u_k3d"/><path fill="url(#i1zbkLd)" class="if-0u_k3d"/><path fill="url(#i0cYvBC)" class="if-0u_k3d"/><path fill="url(#iuxXPuc)" class="if-0u_k3d"/><path fill="url(#iktcDPe)" class="if-0u_k3d"/><path fill="url(#izWNrrd)" class="if-0u_k3d"/><path fill="url(#idkpVzl)" class="if-0u_k3d"/><path fill="url(#iLI8I4b)" class="vf8rvhbeo"/><path fill="url(#iQb0aOb)" class="kl-fs7b7s"/><path fill="url(#iN4Zboe)" class="fcnboaczg"/><path fill="url(#irxZE6c)" class="fcnboaczg"/><path fill="url(#ibgpVoe)" class="fcnboaczg"/><path fill="url(#iGZPLmb)" class="dfd47wpsr"/><path fill="url(#i7oCbiE)" class="dfd47wpsr"/><path fill="url(#iAG1YOc)" class="dfd47wpsr"/><path fill="url(#ip0VPrb)" class="uz-5p3brt"/><path fill="url(#iPmCLfb)" class="uz-5p3brt"/><path fill="url(#iLI8I4b)" class="vf8rvhbeo"/><path fill="url(#iQb0aOb)" class="kl-fs7b7s"/><g filter="url(#i0UCMye)"><path class="uym3t3_cm"/></g><g filter="url(#ifJr3yg)"><path fill="url(#ieEAkZg)" class="eice-8vfk"/></g><path fill="url(#iBCk49d)" class="kefej8vtn"/><path fill="url(#ik2At4b)" class="kefej8vtn"/><path fill="url(#itv4SBd)" class="kefej8vtn"/><path fill="url(#ikZwzVb)" class="kefej8vtn"/><path fill="url(#iI8q5Mc)" class="kefej8vtn"/><path fill="url(#ie3XUrB)" class="kefej8vtn"/><path fill="url(#iaT7u0b)" class="svdxo1bqv"/><path fill="url(#i0TPOhd)" class="svdxo1bqv"/><path fill="url(#iU1jYLc)" class="svdxo1bqv"/><path fill="url(#i4XpPsO)" class="svdxo1bqv"/><path fill="url(#iukTkJd)" class="svdxo1bqv"/><path fill="url(#iuO5Kyc)" class="svdxo1bqv"/><path fill="url(#iyggv0c)" class="wylb3y7qp"/><path clip-rule="evenodd" class="umc7xqbzf"/><path fill="url(#ixxOc7F)" clip-rule="evenodd" class="u5rff1bsn"/><path fill="url(#ifXf4ld)" clip-rule="evenodd" class="u5rff1bsn"/><path fill="url(#ijcq4Jd)" clip-rule="evenodd" class="u5rff1bsn"/><path fill="url(#iBa68hc)" clip-rule="evenodd" class="u5rff1bsn"/><g filter="url(#iTZeOsc)"><path class="siisnldcq"/></g><path fill="url(#iDeO7Cc)" class="mqnc-gk7c"/><g filter="url(#iXAhTLe)"><path fill="url(#iW6AAJS)" class="fbebuk9mv"/></g><g filter="url(#i6Dldbb)"><path fill="url(#iFFojJd)" clip-rule="evenodd" class="j8v1on6tk"/></g><g filter="url(#iSQ5Ied)"><path class="agc1kybmm"/></g><path fill="url(#i0Gt5Pb)" clip-rule="evenodd" class="ri-551b-j"/><path fill="url(#i2RnCLy)" clip-rule="evenodd" class="ri-551b-j"/><path fill="url(#iVE0uPd)" clip-rule="evenodd" class="b_h3fffug"/><path fill="url(#i0CWRte)" clip-rule="evenodd" class="b_h3fffug"/><g filter="url(#iptWAQq)"><circle fill="url(#i7MNr9d)" class="v-m55sadd"/></g><g filter="url(#iBnmCPL)"><circle fill="url(#ifdM0Gd)" class="zntydvbsi"/></g><g filter="url(#iEa8ZYt)"><circle fill="url(#iRnEHAc)" class="n4l4dm6eu"/><circle fill="url(#igyQqWd)" class="n4l4dm6eu"/></g><g filter="url(#ixsptMd)"><circle class="x1_e4bclv"/><circle fill="url(#iRvnwXd)" class="q-4ds2blc"/><circle fill="url(#i0L36ue)" class="q-4ds2blc"/></g><g filter="url(#iIJbAec)"><path fill="url(#izBNC9N)" class="b929ufslf"/><path fill="url(#ipjmENd)" class="b929ufslf"/><path fill="url(#idKT7je)" class="b929ufslf"/><path fill="url(#iPQuFkb)" class="b929ufslf"/><path fill="url(#iGzQNfd)" class="b929ufslf"/><path fill="url(#iRIcIgF)" class="b929ufslf"/></g><g filter="url(#iwihezb)"><path fill="url(#iEwUX4d)" class="h7ehn3bev"/></g><g filter="url(#iqKRqGd)"><path class="yvkfynbqt"/><path fill="url(#iSpW4hk)" class="k8fk6zb7u"/><path fill="url(#izjuqCc)" class="k8fk6zb7u"/><path fill="url(#iF1x6vd)" class="k8fk6zb7u"/><path fill="url(#iWKVHSb)" class="k8fk6zb7u"/></g><g filter="url(#izfavyn)"><path class="n2cthhbof"/></g><g filter="url(#iKisPGb)"><path class="je-r74s5a"/><path fill="url(#iXhEaFe)" class="ed4xrgv3p"/><path fill="url(#i9ZVopb)" class="ed4xrgv3p"/><path fill="url(#iPuw4Be)" class="ed4xrgv3p"/><path fill="url(#iKp5jlx)" class="ed4xrgv3p"/></g><path fill="url(#ifutWed)" class="ed4xrgv3p"/><path stroke="url(#ij87fVf)" class="dndj8bbnq"/><g filter="url(#iHBJY9c)"><path class="d5gwnjbqm"/></g><g filter="url(#i5NA2Yd)"><path class="ibs-t0k-c"/></g><path class="yduaf7biz"/><path fill="url(#iBIygAC)" class="a4q8cacay"/><path class="vm6ik5b_m"/><g filter="url(#inloIMe)"><path class="sup06_dqn"/><path fill="url(#iwjwsIe)" class="etci5wbfw"/></g><g filter="url(#iwAPHrd)"><path fill="url(#itmf5Ud)" class="donwzib0w"/></g><path class="yyi1obbig"/><path fill="url(#icst1rF)" class="kg90cqo3p"/><path class="e6umu-btg"/><g filter="url(#iawwCld)"><path fill="url(#i8tK2He)" class="l2s124gju"/></g><g filter="url(#izIQWYb)"><ellipse transform="rotate(-27.914 13.527 9.94)" class="vhpxi0-re"/><ellipse fill="url(#ikJTq7w)" transform="rotate(-27.914 13.527 9.94)" class="q6x8lbcoq"/></g><g filter="url(#in5FWHc)"><path stroke="url(#iBFBZKc)" class="b6p8-dbex"/></g><g filter="url(#ixAS2gd)"><path stroke="url(#ijIZHVd)" class="b1hk_ebow"/></g><g filter="url(#iitRukd)"><path stroke="url(#iTUb1Vs)" class="g6xtd0cdr"/></g><defs><radialGradient id="iNJFlOd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.22 23.93)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="iktcDPe" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.169 8.175)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="izWNrrd" cx="0" cy="0" r="1" gradientTransform="rotate(77.152 -6.316 23.579)scale(3.65398 4.0429)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="idkpVzl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.992 30)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="iN4Zboe" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.358 24.712)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="irxZE6c" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.7 12.344)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="iGZPLmb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.256 21.962)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="i7oCbiE" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.569 20.337)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="ip0VPrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 16.026 18.556)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="lc4rehg1n"/><stop offset="1" class="h1aoh3b9a"/></radialGradient><radialGradient id="iPmCLfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.39 30.493)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="stn4eib-z"/><stop offset="1" class="z99vy1qwj"/></radialGradient><radialGradient id="ikZwzVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 19.164 18.119)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="iI8q5Mc" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.472 26.56)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="ie3XUrB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.164 24.869)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="iaT7u0b" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.392 11.283)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="i0TPOhd" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.155 24.923)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="i4XpPsO" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.327 19.494)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="iukTkJd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 12.124 18.322)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="iuO5Kyc" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -17.018 24.255)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="iyggv0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14159 3.71341 0 16.01 18.72)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="jgm7cft5u"/><stop offset=".577" class="u11lq5y6c"/><stop offset="1" class="ahk2xyb4u"/></radialGradient><radialGradient id="ifXf4ld" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.30438 0 18.53 16.384)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ad-0z61hw"/><stop offset="1" class="p6pfsuaja"/></radialGradient><radialGradient id="ijcq4Jd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.608 20.04)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="iBa68hc" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.83 12.202)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="s96-1fbmn"/><stop offset="1" class="pvle9ybys"/></radialGradient><radialGradient id="iDeO7Cc" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.167 18.073)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="iW6AAJS" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.274 25.907)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="i2RnCLy" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.155 23.572)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="i7MNr9d" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07077 9.566 10.718)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="igyQqWd" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.12 10.453)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iRvnwXd" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.706 11.539)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="i0L36ue" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.657 30.585)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="ipjmENd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.43448 -12.8068 0 16.012 8.793)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="p7jmmxb2h"/><stop offset="1" class="uzkpn5btf"/></radialGradient><radialGradient id="iGzQNfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.329 9.446)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iRIcIgF" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.771 9.413)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iSpW4hk" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.48 -9.964)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="izjuqCc" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -43.495 205.9)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iF1x6vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.983 2.117)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iWKVHSb" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 9.535 8.935)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iKp5jlx" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.31 12.324)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="iBIygAC" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.162 10.036)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iwjwsIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.933 10.12)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="icst1rF" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.799 10.036)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ikJTq7w" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.804 -1.524)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="i1zbkLd" x1="23.335" x2="23.022" y1="24.611" y2="24.611" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="i0cYvBC" x1="8.756" x2="9.092" y1="24.611" y2="24.611" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="iuxXPuc" x1="16.202" x2="16.202" y1="30.962" y2="29.15" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iLI8I4b" x1="8.841" x2="23.217" y1="15.439" y2="15.439" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iQb0aOb" x1="8.841" x2="23.217" y1="15.409" y2="15.409" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ibgpVoe" x1="7.02" x2="7.02" y1="30.775" y2="29.315" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iAG1YOc" x1="22.692" x2="23.47" y1="25.649" y2="25.649" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="ieEAkZg" x1="16.202" x2="23.827" y1="26.993" y2="19.399" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="iBCk49d" x1="21.916" x2="16.8" y1="18.389" y2="23.907" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="ik2At4b" x1="20.07" x2="19.912" y1="15.67" y2="17.733" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="itv4SBd" x1="17.608" x2="18.764" y1="18.915" y2="19.4" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="iU1jYLc" x1="12.296" x2="12.624" y1="23.212" y2="22.853" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="ixxOc7F" x1="20.335" x2="19.663" y1="23.681" y2="23.697" gradientUnits="userSpaceOnUse"><stop offset=".294" class="w_l8deb9l"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="iFFojJd" x1="12.23" x2="12.23" y1="19.879" y2="28.462" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="i0Gt5Pb" x1="9.54" x2="10.434" y1="25.279" y2="25.279" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iVE0uPd" x1="13.913" x2="14.585" y1="25.288" y2="25.288" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="i0CWRte" x1="14.975" x2="14.733" y1="24.806" y2="24.806" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="ifdM0Gd" x1="11.235" x2="10.595" y1="10.996" y2="10.996" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iRnEHAc" x1="21.834" x2="21.015" y1="9.626" y2="12.162" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="izBNC9N" x1="20.018" x2="12.382" y1="11.107" y2="12.245" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="idKT7je" x1="10.341" x2="13.699" y1="12.634" y2="12.748" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iPQuFkb" x1="10.587" x2="12.469" y1="13.803" y2="13.736" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iEwUX4d" x1="15.451" x2="23.595" y1="8.123" y2="5.207" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iXhEaFe" x1="15.119" x2="16.057" y1="11.766" y2="11.766" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="i9ZVopb" x1="16.921" x2="15.896" y1="12.089" y2="12.074" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iPuw4Be" x1="16.177" x2="16.177" y1="12.831" y2="12.258" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="ifutWed" x1="16.108" x2="16.108" y1="12.873" y2="12.705" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="ij87fVf" x1="14.946" x2="15.381" y1="14.446" y2="13.758" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="itmf5Ud" x1="18.939" x2="18.626" y1="10.09" y2="10.283" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8tK2He" x1="14.542" x2="14.229" y1="10.09" y2="10.283" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBFBZKc" x1="18.955" x2="18.535" y1="7.95" y2="7.091" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ijIZHVd" x1="13.651" x2="12.462" y1="7.822" y2="7.323" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iTUb1Vs" x1="11.321" x2="11.321" y1="5.808" y2="7.965" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><filter id="i0UCMye" width="7.147" height="11.557" x="9.055" y="15.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".5"/></filter><filter id="ifJr3yg" width="7.147" height="11.557" x="15.949" y="15.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".5"/></filter><filter id="iTZeOsc" width="3.699" height="3.699" x="17.02" y="24.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".375"/></filter><filter id="iXAhTLe" width="1.42" height="1.42" x="18.991" y="24.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24158"/></filter><filter id="i6Dldbb" width="5.381" height="7.171" x="9.54" y="19.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24158"/></filter><filter id="iSQ5Ied" width="5.3" height="6.89" x="9.606" y="19.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".15"/></filter><filter id="iptWAQq" width="3.539" height="3.339" x="9.566" y="9.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24158"/></filter><filter id="iBnmCPL" width="2.99" height="2.99" x="9.74" y="9.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".25"/></filter><filter id="iEa8ZYt" width="3.589" height="3.589" x="19.078" y="8.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24158"/></filter><filter id="ixsptMd" width="2.99" height="2.99" x="19.253" y="9.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".25"/></filter><filter id="iIJbAec" width="10.373" height="12.277" x="10.825" y="5.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24158"/></filter><filter id="iwihezb" width="8.246" height="7.066" x="14.153" y="3.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation="1"/></filter><filter id="iqKRqGd" width="12.601" height="8.543" x="9.682" y="1.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24158"/></filter><filter id="izfavyn" width="3.26" height="4.181" x="14.114" y="9.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".375"/></filter><filter id="iKisPGb" width="2.377" height="3.181" x="14.794" y="9.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".125"/></filter><filter id="iHBJY9c" width="2.979" height="1.873" x="17.165" y="7.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24158"/></filter><filter id="i5NA2Yd" width="2.98" height="1.873" x="12.018" y="7.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24158"/></filter><filter id="inloIMe" width=".787" height=".696" x="17.428" y="9.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".05"/></filter><filter id="iwAPHrd" width=".891" height=".913" x="18.267" y="9.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".1"/></filter><filter id="iawwCld" width=".986" height="1.04" x="13.826" y="9.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".1"/></filter><filter id="izIQWYb" width=".913" height=".704" x="13.071" y="9.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".05"/></filter><filter id="in5FWHc" width="3.099" height="1.681" x="17.018" y="7.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".25"/></filter><filter id="ixAS2gd" width="3.177" height="1.738" x="11.799" y="7.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".25"/></filter><filter id="iitRukd" width="1.008" height="2.269" x="10.817" y="5.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24158" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-health-worker-light" /></template>
<style>
.a4q8cacay {
  d: path("M18.164 9.559a.892.892 0 0 1 .86 1.127H17.3a.896.896 0 0 1 .864-1.127");
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.ad-0z61hw {
  stop-color: var(--svg-color--552e54, #552E54);
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.agc1kybmm {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.216 26.293h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.ahk2xyb4u {
  stop-color: var(--svg-color--8c6157, #8C6157);
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.b_h3fffug {
  fill-rule: evenodd;
  d: path("M14.921 23.73v2.47c0 .36-.29.65-.65.65h-.58v-.981h.249v-2.14z");
}

.b1hk_ebow {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.424 8.372c.327-.29 1.042-.594 1.927-.453");
}

.b6p8-dbex {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.643 7.853c.43-.075 1.269-.054 1.85.398");
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.b929ufslf {
  d: path("M10.825 8.667c0-.267.107-.587.322-.747l.16-.16c.27-.213.376-.533.376-.853v-.853c0-.267.161-.48.43-.534c.643-.16 1.984-.426 3.915-.426c1.93 0 3.271.266 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.533-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.234-3.21-3.003c-.14-1.816-.201-3.638-.367-5.451");
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
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

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d5gwnjbqm {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m19.702 7.998l-.001-.001l-.002-.002l-.005-.004l-.012-.01a1.4 1.4 0 0 0-.154-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.493-.159a.534.534 0 0 0 .167 1.055c.398-.063.716.01.933.096a1.5 1.5 0 0 1 .309.166a.534.534 0 0 0 .678-.824");
}

.dfd47wpsr {
  d: path("M26.852 27.97c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59V30h3.65z");
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.dndj8bbnq {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.62 13.474c.394.206.863.323 1.363.323c.504 0 .968-.117 1.362-.323a.2.2 0 0 1 .241.04c.058.06.079.155.021.241m-2.986-.28l2.945.253m-2.945-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.207.027l-.041-.027m.041.027l-.041-.027m.041.027a1.94 1.94 0 0 1-1.624.868c-.682 0-1.28-.347-1.625-.867m3.208-.028a1.9 1.9 0 0 1-1.583.845a1.9 1.9 0 0 1-1.583-.845m-.042.028l.042-.028m-.042.028l.042-.028");
}

.donwzib0w {
  d: path("M18.958 10.334a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
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

.e6umu-btg {
  fill: var(--svg-color--000, #000);
  d: path("M14.308 10.45a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .06-.235");
}

.ed4xrgv3p {
  d: path("m15.6 10.432l-.53 1.7c-.11.35.151.699.52.699h.786a.54.54 0 0 0 .52-.7l-.531-1.699c-.114-.376-.645-.376-.764 0");
}

.eice-8vfk {
  d: path("m21.919 20.154l-.733.13a.213.213 0 0 0-.12.352l.704.77a.216.216 0 0 1-.009.296l-4.506 4.599c-.111.111-.306.037-.306-.12v-3.33c0-.036.01-.064.019-.101l2.54-5.888a.15.15 0 0 1 .037-.065a9.7 9.7 0 0 1 2.365 1.122l.185 2.003a.214.214 0 0 1-.176.232");
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.etci5wbfw {
  d: path("M18.098 9.747c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fbebuk9mv {
  d: path("M19.7 26.18a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.fcnboaczg {
  d: path("m5.951 22.77l-.03.08c-.52 1.65-.79 3.36-.79 5.09V30h3.67V18.25a10.56 10.56 0 0 0-2.85 4.52");
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

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.g6xtd0cdr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.45 5.907v.897c-.008.149-.07.481-.258.622");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
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

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.h7ehn3bev {
  d: path("M19.946 5.094L16.869 6.12a1.047 1.047 0 0 0 .47 2.03l3.06-.409z");
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.ibs-t0k-c {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.21 7.998l.001-.001l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.062.241-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 1 1-.166 1.055a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.678-.824");
}

.if-0u_k3d {
  d: path("M16.012 15.41c-2.74 0-5.3 1.06-7.21 2.84V30h14.38V18.22a10.54 10.54 0 0 0-7.17-2.81");
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.j8v1on6tk {
  fill-rule: evenodd;
  d: path("M12.23 20.86a1.71 1.71 0 0 0-1.709 1.71v3.299h.67a.49.49 0 0 1 0 .981h-1a.65.65 0 0 1-.651-.65v-3.63a2.69 2.69 0 0 1 5.381 0v3.63c0 .36-.29.65-.65.65h-.93a.49.49 0 0 1 0-.981h.599v-3.3a1.71 1.71 0 0 0-1.71-1.709");
}

.je-r74s5a {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.6 10.432l-.53 1.7c-.11.35.151.699.52.699h.786a.54.54 0 0 0 .52-.7l-.531-1.699c-.114-.376-.645-.376-.764 0");
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jgm7cft5u {
  stop-color: var(--svg-color--b58c86, #B58C86);
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.k8fk6zb7u {
  d: path("m20.801 4.24l.43.214c.75.373 1.18 1.226 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.907.108-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.534c-.644-.16-1.984-.426-3.915-.426s-3.272.266-3.916.426a.52.52 0 0 0-.429.534v.853c0 .32-.107.64-.375.853l-.161.16c-.215.16-.322.48-.322.747c.054.586.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.072-2.08l.43-.213c.268-.16.536-.373.804-.586l.965-1.013c.59-.534 1.449-.694 2.2-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.054 2.36.533l.805.8c.214.267.482.427.804.587");
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.kefej8vtn {
  d: path("M16.675 21.691c-.262.516-.262.942-.262 1.306v2.99c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.754-.83a.23.23 0 0 1 .13-.38l.782-.14a.23.23 0 0 0 .189-.25l-.188-2.058a.25.25 0 0 0-.113-.187a10.5 10.5 0 0 0-2.425-1.134a.3.3 0 0 0-.04.08z");
}

.kg90cqo3p {
  d: path("M13.797 9.559a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.kl-fs7b7s {
  d: path("M16.05 15.41h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
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

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l2s124gju {
  d: path("M14.612 10.346c0-.288-.235-.48-.298-.538l-.288.278l.177.362z");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lc4rehg1n {
  stop-color: var(--svg-color--3272ac, #3272AC);
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

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mqnc-gk7c {
  d: path("M19.7 26.73a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.n2cthhbof {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.707 10.595l-.82 1.7c-.101.35.143.699.488.699h.737c.346 0 .59-.355.488-.7l-.498-1.699c-.107-.376-.283-.376-.395 0");
}

.n4l4dm6eu {
  cx: 20.748px;
  cy: 10.718px;
  r: 1.669px;
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
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

.p6pfsuaja {
  stop-color: var(--svg-color--552e54, #552E54);
  stop-opacity: 0;
}

.p7jmmxb2h {
  stop-color: var(--svg-color--d7a09d, #D7A09D);
  stop-opacity: 0;
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

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q-4ds2blc {
  cx: 20.748px;
  cy: 10.717px;
  r: 0.995px;
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.q6x8lbcoq {
  cx: 13.527px;
  cy: 9.94px;
  rx: 0.389px;
  ry: 0.197px;
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.ri-551b-j {
  fill-rule: evenodd;
  d: path("M9.54 26.19v-2.47h.981v2.14h.25v.98h-.58a.65.65 0 0 1-.651-.65");
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.s96-1fbmn {
  stop-color: var(--svg-color--4a2657, #4A2657);
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.siisnldcq {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.87 26.959a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
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

.sup06_dqn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.098 9.747c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.svdxo1bqv {
  d: path("M15.396 21.691c.262.516.262.942.262 1.306v2.99c0 .17-.208.26-.327.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.118-.13.05-.35-.13-.38l-.783-.14a.23.23 0 0 1-.188-.25l.187-2.058a.25.25 0 0 1 .113-.187a10.5 10.5 0 0 1 2.426-1.134a.3.3 0 0 1 .04.08z");
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.u11lq5y6c {
  stop-color: var(--svg-color--a47779, #A47779);
}

.u5rff1bsn {
  fill-rule: evenodd;
  d: path("M15.96 15.12a3.24 3.24 0 0 0-3.239 3.24v2.15h-.981v-2.15a4.22 4.22 0 1 1 8.441 0v7.12H19.2v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.umc7xqbzf {
  fill: var(--svg-color--5a4b7e, #5A4B7E);
  fill-rule: evenodd;
  d: path("M15.96 15.12a3.24 3.24 0 0 0-3.239 3.24v2.15h-.981v-2.15a4.22 4.22 0 1 1 8.441 0v7.12H19.2v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.uym3t3_cm {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.232 20.154l.733.13a.213.213 0 0 1 .12.352l-.705.77a.216.216 0 0 0 .01.296l4.506 4.599c.111.111.306.037.306-.12v-3.33c0-.036-.01-.064-.019-.101l-2.54-5.888a.15.15 0 0 0-.037-.065a9.7 9.7 0 0 0-2.365 1.122l-.185 2.003a.214.214 0 0 0 .176.232");
}

.uz-5p3brt {
  d: path("M16.518 22.514c0-.04-.01-.203 0-.243l2.663-6.291c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.361c.01.03.054.05.054.09l.056 3.599h.01V30h.79v-3.97l.078-3.416z");
}

.uzkpn5btf {
  stop-color: var(--svg-color--b07f87, #B07F87);
}

.v-m55sadd {
  cx: 11.235px;
  cy: 10.718px;
  r: 1.669px;
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
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

.vhpxi0-re {
  cx: 13.527px;
  cy: 9.94px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.vm6ik5b_m {
  fill: var(--svg-color--000, #000);
  d: path("M17.653 10.45c0-.283.227-.51.51-.51a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
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

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
}

.wylb3y7qp {
  d: path("M16.01 18.72a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.x1_e4bclv {
  cx: 20.748px;
  cy: 10.717px;
  r: 0.995px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.x3e-lhbqh {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
  stop-opacity: 0;
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x7yaztbkk {
  stop-color: var(--svg-color--b3a299, #B3A299);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.yduaf7biz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.37 9.287c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.yvkfynbqt {
  fill: var(--svg-color--242324, #242324);
  d: path("m20.801 4.24l.43.214c.75.373 1.18 1.226 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.907.108-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.534c-.644-.16-1.984-.426-3.915-.426s-3.272.266-3.916.426a.52.52 0 0 0-.429.534v.853c0 .32-.107.64-.375.853l-.161.16c-.215.16-.322.48-.322.747c.054.586.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.072-2.08l.43-.213c.268-.16.536-.373.804-.586l.965-1.013c.59-.534 1.449-.694 2.2-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.054 2.36.533l.805.8c.214.267.482.427.804.587");
}

.yyi1obbig {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.59 9.287c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.z99vy1qwj {
  stop-color: var(--svg-color--3865b8, #3865B8);
  stop-opacity: 0;
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zntydvbsi {
  cx: 11.235px;
  cy: 10.717px;
  r: 0.995px;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
