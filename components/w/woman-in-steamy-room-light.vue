<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iOokUYv)" class="r_bcr-ntk"/><circle fill="url(#ig6gRjd)" class="r_bcr-ntk"/><circle fill="url(#ifqCFkS)" class="iksuiqrgf"/><circle fill="url(#igczLIe)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iE9wJUA)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iiFjNse)" transform="matrix(-1 0 0 1 23.725 23.368)" class="n5l_opbqq"/><g filter="url(#i4O8v0b)"><path fill="url(#iYsbl2d)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iPAZN2v)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#i0BgLSb)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iNBcaJb)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iIavlFd)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iIzLnxe)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iYWlMkb)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iw4pTCc)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#i1YVsZb)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iylD86b)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iPsYZLc)" clip-rule="evenodd" class="xooo5lvln"/></g><path fill="url(#i8FGQFb)" class="w8e9izb-y"/><path fill="url(#iMKMyJG)" class="w8e9izb-y"/><path fill="url(#iZv1BFd)" class="w8e9izb-y"/><path fill="url(#iZmEtZd)" class="rgs-6fbpw"/><path fill="url(#iecyoYd)" class="rgs-6fbpw"/><path class="rw7u0kjxx"/><path fill="url(#iG5HNEd)" class="gt-y46nru"/><path fill="url(#iTiy4Yb)" class="gt-y46nru"/><path fill="url(#ivTeyXa)" class="gt-y46nru"/><path fill="url(#itptivw)" class="gt-y46nru"/><path fill="url(#im05I4b)" class="gt-y46nru"/><path fill="url(#iP7Xdge)" class="gt-y46nru"/><path class="qujrzvqgg"/><path fill="url(#iZUlthd)" class="zzsb9xb8w"/><path fill="url(#iwNqoRc)" class="zzsb9xb8w"/><path fill="url(#iE18CIh)" class="zzsb9xb8w"/><g filter="url(#iNI5a9b)"><path fill="url(#iY9iyMb)" class="h-i2t2w9q"/><path fill="url(#iYLhsSD)" class="h-i2t2w9q"/><path fill="url(#i21oEbd)" class="h-i2t2w9q"/></g><path class="wkmk90b2p"/><g filter="url(#iJfv0we)"><path class="mfuun6zqx"/></g><path fill="url(#ialH3pb)" class="zosz72acb"/><path fill="url(#iGusNfb)" class="ytvm2kbdn"/><g filter="url(#iKA1rie)"><path fill="url(#iickIve)" class="b787bwb8q"/></g><g filter="url(#iUMovnc)"><path fill="url(#if3asmc)" class="t_z9a_1_e"/><path fill="url(#i1Vgdpr)" class="t_z9a_1_e"/></g><g filter="url(#iWWN1gc)"><path class="xn4dl3btn"/><path fill="url(#idOe9Lc)" class="fqthm3lid"/></g><g filter="url(#iciE79j)"><path class="r8blt-bnx"/><path fill="url(#isvsAGe)" class="nj9ng6b5g"/></g><g filter="url(#injIZOb)"><path fill="url(#ipHMOpb)" class="urfu17b_m"/><path fill="url(#i1sK13X)" class="urfu17b_m"/><path fill="url(#iHeZrBc)" class="urfu17b_m"/><path fill="url(#iQFVZML)" class="urfu17b_m"/><path fill="url(#iZobJvc)" class="urfu17b_m"/><path fill="url(#iEK0zTG)" class="urfu17b_m"/><path fill="url(#i8JXM3b)" class="urfu17b_m"/></g><path fill="url(#i47fIPd)" class="urfu17b_m"/><path fill="url(#ilFkCtc)" class="urfu17b_m"/><g filter="url(#i9UB5rd)"><path class="gksxaqb9d"/></g><g filter="url(#iXGxEGd)"><path class="mxu1gt6vp"/><path fill="url(#iPOFRkd)" class="iq462cb3g"/><path fill="url(#iTss03U)" class="iq462cb3g"/><path fill="url(#iqS83qd)" class="iq462cb3g"/><path fill="url(#iN7tvsg)" class="iq462cb3g"/></g><g filter="url(#i6LJs8d)"><path stroke="url(#i7U2ATc)" class="z374e_6sn"/></g><path class="m88wbrbun"/><g filter="url(#iikbYsb)"><path class="rg4nauy9l"/></g><g filter="url(#iH8Wqob)"><path class="evm_o5oem"/></g><g filter="url(#iIy4SAd)"><path class="fs7ooej-m"/></g><g filter="url(#ixZYdHc)"><path clip-rule="evenodd" class="pgum8_8zk"/></g><path class="c4j9xf4yf"/><path fill="url(#is2qqRc)" class="g1lqsxc9b"/><path class="ucnajwbxu"/><g filter="url(#iErVOWb)"><path class="n2ia63biy"/><path fill="url(#iIM36fm)" class="choqsb0vk"/></g><g filter="url(#idaF6Me)"><path fill="url(#ilsyuIb)" class="s4fsmlbta"/></g><path class="grgmmmbpj"/><path fill="url(#i2hSEtc)" class="ho1vz9bmx"/><path class="wyw_zsaao"/><g filter="url(#iVP0nBd)"><path fill="url(#iEnZNnZ)" class="g10-b8nzg"/></g><g filter="url(#i7fzVud)"><ellipse transform="rotate(-27.914 13.446 9.982)" class="h84badbaf"/><ellipse fill="url(#itaGpVc)" transform="rotate(-27.914 13.446 9.982)" class="t9qyh6bmf"/></g><g filter="url(#iL3c19m)"><path class="k_wydox9f"/></g><g filter="url(#iUVOh9N)"><path class="l-cnygept"/></g><g filter="url(#i4M9Mje)"><path class="qy9hi7mpo"/><path fill="url(#i4AB5Me)" class="y_9p2zbzc"/></g><g filter="url(#i2hKgIb)"><path class="s4yx1cc8i"/><path fill="url(#iKl91ec)" class="upo930jwf"/><path fill="url(#iZiWBke)" class="upo930jwf"/></g><g filter="url(#iCE6vVc)"><path stroke="url(#i66K6Qd)" class="rzjfiqxaf"/></g><g filter="url(#iwBQUNc)"><path class="f_xmhtbgi"/></g><defs><radialGradient id="iOokUYv" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -2.4375 2.72822 4.02238 6.877 17.33)" gradientUnits="userSpaceOnUse"><stop class="dgu6o60tg"/><stop offset="1" class="n_p-4bbbu"/></radialGradient><radialGradient id="ig6gRjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 -1.76562 2.48224 -.02197 8.596 17.83)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="v6wds2dtn"/><stop offset="1" class="nz8ufunsm"/></radialGradient><radialGradient id="ifqCFkS" cx="0" cy="0" r="1" gradientTransform="matrix(-5.47138 9.4622 -7.02133 -4.05998 10.46 19.268)" gradientUnits="userSpaceOnUse"><stop class="qc0o5_36v"/><stop offset="1" class="snymmbrnj"/></radialGradient><radialGradient id="igczLIe" cx="0" cy="0" r="1" gradientTransform="rotate(44.444 -1.585 1.225)scale(4.68833)" gradientUnits="userSpaceOnUse"><stop class="qc07hnbjk"/><stop offset=".836" class="b_5radckw"/></radialGradient><radialGradient id="iE9wJUA" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.59375 5.11385 -.10027 2.316 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vze8wny8i"/><stop offset="1" class="o4sg_vbnc"/></radialGradient><radialGradient id="iiFjNse" cx="0" cy="0" r="1" gradientTransform="matrix(4.95236 7.33803 -10.65664 7.19205 1.352 1.24)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="r8td-ob5s"/><stop offset=".819" class="eegxz98yy"/></radialGradient><radialGradient id="iPAZN2v" cx="0" cy="0" r="1" gradientTransform="matrix(-.61119 4.6179 -5.7687 -.7635 15.626 13.217)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="i0BgLSb" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.325 8.697)scale(3.52225 4.62796)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iNBcaJb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.817 8.178)scale(2.18002 1.67395)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iIavlFd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.259 7.647)scale(2.507 1.76596)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iIzLnxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.39216 2.6485 -3.67653 1.93254 12.366 2.521)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iYWlMkb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.961 6.836)scale(2.0648 2.88552)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iw4pTCc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86745 .54329 -1.13298 -3.89442 23.537 9.821)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i1YVsZb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.85214 .71308 -.90835 -3.63321 22.926 13.285)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iylD86b" cx="0" cy="0" r="1" gradientTransform="matrix(-.91611 -2.68446 2.12325 -.7246 20.725 7.356)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iPsYZLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.52332 .15979 -.2589 2.46823 9.71 9.785)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i8FGQFb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35939 5.78125 -6.81223 -1.6018 23.096 22.58)" gradientUnits="userSpaceOnUse"><stop class="ttp7yqb-m"/><stop offset="1" class="jletv-brl"/></radialGradient><radialGradient id="iZmEtZd" cx="0" cy="0" r="1" gradientTransform="matrix(6.87457 8.07189 -11.19707 9.5362 6.418 22.32)" gradientUnits="userSpaceOnUse"><stop class="wv2o2nbhk"/><stop offset="1" class="n44b27bdp"/></radialGradient><radialGradient id="iG5HNEd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.03127 -6.31539 -6.64086 13.752 16.392)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="epu6iq_fg"/><stop offset="1" class="q8d1l4bok"/></radialGradient><radialGradient id="ivTeyXa" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82764 -11.66358 1.58185 -.65474 15.958 28.962)" gradientUnits="userSpaceOnUse"><stop class="x37sucbkr"/><stop offset="1" class="k796fybnd"/></radialGradient><radialGradient id="im05I4b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37282 -3.155 .92095 -.40073 16.346 27.58)" gradientUnits="userSpaceOnUse"><stop class="bp-uy2zsn"/><stop offset="1" class="dfpk_zbbl"/></radialGradient><radialGradient id="iP7Xdge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15863 -1.17796 1.62432 -1.59766 14.336 18.515)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="jhdqd89ez"/><stop offset="1" class="tbqxjbcmi"/></radialGradient><radialGradient id="iwNqoRc" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.67188 .83418 2.50254 17.502 18.33)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="x4p5bn7mz"/><stop offset="1" class="rz_1qnb6a"/></radialGradient><radialGradient id="iE18CIh" cx="0" cy="0" r="1" gradientTransform="rotate(110.875 2.49 18.294)scale(11.8396 2.00952)" gradientUnits="userSpaceOnUse"><stop class="tqo-vnfob"/><stop offset="1" class="fqnn-rb2e"/></radialGradient><radialGradient id="iYLhsSD" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.92625 -2.40786 2.26568 13.158 16.172)" gradientUnits="userSpaceOnUse"><stop class="gsf6qr7kp"/><stop offset="1" class="cg_mp-zjf"/></radialGradient><radialGradient id="i21oEbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10566 2.98991 -2.59501 -.0917 16.746 15.415)" gradientUnits="userSpaceOnUse"><stop class="gs0xjnbiw"/><stop offset="1" class="r9e33mbdc"/></radialGradient><radialGradient id="if3asmc" cx="0" cy="0" r="1" gradientTransform="matrix(1.85056 -2.06278 2.51855 2.25944 20.498 11.672)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="i1Vgdpr" cx="0" cy="0" r="1" gradientTransform="matrix(1.33274 .74702 -.2112 .37679 21.067 8.981)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="idOe9Lc" cx="0" cy="0" r="1" gradientTransform="matrix(1.52937 -.11376 .08893 1.19555 20.38 10.797)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="isvsAGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.22239 0 0 -.96431 11.27 10.684)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="ipHMOpb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.58749 3.03771 -4.06593 -8.81724 18.827 10.14)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="i1sK13X" cx="0" cy="0" r="1" gradientTransform="rotate(172.574 9.239 6.383)scale(3.53548 3.90254)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iHeZrBc" cx="0" cy="0" r="1" gradientTransform="matrix(1.32425 -3.83694 4.86836 1.68023 13.52 17.563)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iQFVZML" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.81144 -7.8845 0 15.931 9.92)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="iZobJvc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.99477 1.3727 -2.36336 -12.04279 17.765 11.893)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iEK0zTG" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16562 1.43053 0 18.262 9.715)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="i8JXM3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.32945 1.52364 0 13.828 9.484)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="i47fIPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30187 0 0 -6.52874 21.092 11.222)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="ilFkCtc" cx="0" cy="0" r="1" gradientTransform="rotate(71.834 4.054 11.501)scale(4.26415 7.42866)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="iPOFRkd" cx="0" cy="0" r="1" gradientTransform="matrix(-.46142 -2.07039 .63808 -.1422 16.725 11.958)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iN7tvsg" cx="0" cy="0" r="1" gradientTransform="matrix(-.78946 0 0 -.2207 16.483 12.173)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="is2qqRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82178 -1.30714 0 18.141 10.079)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iIM36fm" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.444 .696)scale(.38317 .52752)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2hSEtc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82179 -1.30715 0 13.721 10.079)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="itaGpVc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.786 -1.46)scale(.5005 .60161)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4AB5Me" cx="0" cy="0" r="1" gradientTransform="matrix(1.27831 -2.79098 1.4278 .65395 10.2 7.931)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iKl91ec" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1392 4.44812 -7.2724 -3.49747 17.867 2.657)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iZiWBke" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 6.772 8.44)scale(1.40113 3.01446)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="i4O8v0b" width="15.462" height="15.962" x="8.325" y="1.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_792"/></filter><filter id="iNI5a9b" width="6.906" height="12.039" x="12.293" y="15.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_792"/></filter><filter id="iJfv0we" width="3.076" height="1.977" x="15.245" y="17.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".3"/></filter><filter id="iKA1rie" width="3.41" height="3.26" x="9.555" y="9.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_792"/></filter><filter id="iUMovnc" width="3.26" height="3.51" x="19.191" y="8.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_792"/></filter><filter id="iWWN1gc" width="3.176" height="3.176" x="19.233" y="9.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".25"/></filter><filter id="iciE79j" width="2.976" height="2.976" x="9.716" y="9.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".2"/></filter><filter id="injIZOb" width="10.322" height="11.417" x="10.77" y="5.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_792"/></filter><filter id="i9UB5rd" width="2.901" height="3.716" x="14.316" y="9.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".25"/></filter><filter id="iXGxEGd" width="2.401" height="3.216" x="14.73" y="9.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".125"/></filter><filter id="i6LJs8d" width="3.745" height="1.54" x="14.059" y="13.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".05"/></filter><filter id="iikbYsb" width="3.038" height="1.302" x="16.888" y="9.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_792"/></filter><filter id="iH8Wqob" width="3.038" height="1.302" x="11.937" y="9.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_792"/></filter><filter id="iIy4SAd" width="2.482" height="1.102" x="12.074" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_792"/></filter><filter id="ixZYdHc" width="2.482" height="1.103" x="17.561" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_792"/></filter><filter id="iErVOWb" width=".794" height=".703" x="17.399" y="9.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".05"/></filter><filter id="idaF6Me" width=".898" height=".92" x="18.251" y="9.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".1"/></filter><filter id="iVP0nBd" width=".994" height="1.048" x="13.751" y="9.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".1"/></filter><filter id="i7fzVud" width=".922" height=".711" x="12.985" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".05"/></filter><filter id="iL3c19m" width="2.282" height=".983" x="17.596" y="7.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".1"/></filter><filter id="iUVOh9N" width="2.282" height=".983" x="12.074" y="7.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".1"/></filter><filter id="i4M9Mje" width="4.256" height="4.561" x="9.6" y="3.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_792"/><feGaussianBlur result="effect2_foregroundBlur_4002_792" stdDeviation=".15"/></filter><filter id="i2hKgIb" width="8.873" height="5.85" x="12.724" y="2.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_792"/><feGaussianBlur result="effect2_foregroundBlur_4002_792" stdDeviation=".125"/></filter><filter id="iCE6vVc" width="1.152" height="2.332" x="12.703" y="3.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".1"/></filter><filter id="iwBQUNc" width="6.491" height="3.396" x="15.352" y="4.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_792" stdDeviation=".375"/></filter><linearGradient id="iYsbl2d" x1="20.685" x2="13.792" y1="3.642" y2="16.409" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iMKMyJG" x1="24.158" x2="24.189" y1="30.329" y2="26.673" gradientUnits="userSpaceOnUse"><stop offset=".078" class="y41hsabjm"/><stop offset="1" class="y-a_999zn"/></linearGradient><linearGradient id="iZv1BFd" x1="18.12" x2="19.472" y1="27.765" y2="28.151" gradientUnits="userSpaceOnUse"><stop class="mbuex5b5r"/><stop offset="1" class="ozroxmy8l"/></linearGradient><linearGradient id="iecyoYd" x1="13.658" x2="12.158" y1="28.736" y2="29.267" gradientUnits="userSpaceOnUse"><stop class="g82zxu-vf"/><stop offset="1" class="sv9br1byn"/></linearGradient><linearGradient id="iTiy4Yb" x1="12.315" x2="13.69" y1="27.392" y2="26.829" gradientUnits="userSpaceOnUse"><stop offset=".223" class="zantcf-1d"/><stop offset="1" class="tkat5cdin"/></linearGradient><linearGradient id="itptivw" x1="15.627" x2="14.221" y1="30.173" y2="29.486" gradientUnits="userSpaceOnUse"><stop offset=".208" class="roh2cebgd"/><stop offset="1" class="u44j7rbwl"/></linearGradient><linearGradient id="iZUlthd" x1="16.002" x2="18.033" y1="24.829" y2="25.736" gradientUnits="userSpaceOnUse"><stop class="z0qi4zb3s"/><stop offset="1" class="nh4l3fbho"/></linearGradient><linearGradient id="iY9iyMb" x1="16.366" x2="16.366" y1="24.913" y2="14.427" gradientUnits="userSpaceOnUse"><stop class="qdcgkefpz"/><stop offset="1" class="v1nc78bgs"/></linearGradient><linearGradient id="ialH3pb" x1="8.677" x2="23.191" y1="15.561" y2="15.561" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iGusNfb" x1="8.677" x2="23.191" y1="15.53" y2="15.53" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iickIve" x1="9.555" x2="12.553" y1="10.772" y2="10.772" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iTss03U" x1="14.98" x2="15.931" y1="12.032" y2="12.032" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iqS83qd" x1="15.931" x2="15.931" y1="12.841" y2="12.223" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="i7U2ATc" x1="14.853" x2="15.32" y1="14.27" y2="13.548" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="ilsyuIb" x1="18.929" x2="18.611" y1="10.134" y2="10.329" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEnZNnZ" x1="14.474" x2="14.157" y1="10.134" y2="10.329" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i66K6Qd" x1="13.003" x2="13.555" y1="4.405" y2="5.696" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-steamy-room-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.b_5radckw {
  stop-color: var(--svg-color--f2e8f1, #F2E8F1);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.b787bwb8q {
  d: path("M11.185 12.314a1.63 1.63 0 1 0 0-3.26a1.63 1.63 0 0 0 0 3.26");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bp-uy2zsn {
  stop-color: var(--svg-color--442d6d, #442D6D);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.c4j9xf4yf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.353 9.32c.662 0 1.22.457 1.372 1.073a.278.278 0 0 1-.27.345h-2.26a.233.233 0 0 1-.23-.275a1.416 1.416 0 0 1 1.388-1.142");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cg_mp-zjf {
  stop-color: var(--svg-color--df9981, #DF9981);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.choqsb0vk {
  d: path("M18.077 9.787c.064.086-.07.191-.223.305c-.153.115-.267.195-.331.11c-.065-.087.007-.25.16-.364s.33-.137.394-.051");
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.dfpk_zbbl {
  stop-color: var(--svg-color--7c5fac, #7C5FAC);
  stop-opacity: 0;
}

.dgu6o60tg {
  stop-color: var(--svg-color--e1dae6, #E1DAE6);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.eegxz98yy {
  stop-color: var(--svg-color--dac9f0, #DAC9F0);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.epu6iq_fg {
  stop-color: var(--svg-color--4f3466, #4F3466);
}

.evm_o5oem {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.775 10.107c-.27-.473-.678-.846-1.558-.846a1.68 1.68 0 0 0-1.086.373c-.273.22-.236.502-.025.607l.563.322c.66-.213 1.39-.242 2.106-.456");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f_xmhtbgi {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.369 6.449l-1.444.266a.697.697 0 1 1-.127-1.383h2.371c1.403 0 1.867 1.413 1.924 1.896a3.19 3.19 0 0 0-2.724-.779");
}

.fqnn-rb2e {
  stop-color: var(--svg-color--7b63b3, #7B63B3);
  stop-opacity: 0;
}

.fqthm3lid {
  d: path("M20.82 11.772a1.088 1.088 0 1 0 0-2.176a1.088 1.088 0 0 0 0 2.176");
}

.fs7ooej-m {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.49 8.883l-.005.003a.272.272 0 0 1-.279-.466l.002-.001l.003-.002l.01-.006a2 2 0 0 1 .15-.077c.1-.048.242-.109.415-.164a2.84 2.84 0 0 1 1.345-.11a.272.272 0 1 1-.094.534a2.3 2.3 0 0 0-1.086.093a3 3 0 0 0-.461.196");
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g10-b8nzg {
  d: path("M14.545 10.394c0-.293-.238-.487-.302-.546l-.292.282l.18.366z");
}

.g1lqsxc9b {
  d: path("M18.143 9.596a.904.904 0 0 1 .872 1.142h-1.747a.907.907 0 0 1 .875-1.142");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g82zxu-vf {
  stop-color: var(--svg-color--5e40aa, #5E40AA);
}

.gksxaqb9d {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.534 10.458l-.693 1.722a.546.546 0 0 0 .528.709h.796c.374 0 .637-.36.527-.709l-.538-1.722c-.115-.381-.5-.381-.62 0");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.grgmmmbpj {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.51 9.32c-.662 0-1.221.457-1.373 1.073a.278.278 0 0 0 .271.345h2.26a.233.233 0 0 0 .23-.275A1.42 1.42 0 0 0 13.51 9.32");
}

.gs0xjnbiw {
  stop-color: var(--svg-color--f0af9e, #F0AF9E);
}

.gsf6qr7kp {
  stop-color: var(--svg-color--c3705c, #C3705C);
}

.gt-y46nru {
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-i2t2w9q {
  d: path("M14.01 15.415h4v1.99c.01.174.045.373.152.53a.8.8 0 0 0 .445.332l.465.164c.076.068.22.478.04.984c-.181.505-2.043 5.51-3.094 8.02v.02l-.005-.01q0 .004-.004.01v-.02c-1.052-2.51-3.186-7.515-3.366-8.02c-.182-.506-.076-.87 0-.937l.68-.192c.218-.062.373-.14.515-.347c.113-.166.158-.39.172-.572z");
}

.h84badbaf {
  cx: 13.446px;
  cy: 9.982px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.ho1vz9bmx {
  d: path("M13.719 9.596a.904.904 0 0 0-.871 1.142h1.746a1 1 0 0 0 .033-.238a.91.91 0 0 0-.908-.904");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.iksuiqrgf {
  cx: 8.275px;
  cy: 23.368px;
  r: 6.305px;
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iq462cb3g {
  d: path("m15.544 10.318l-.538 1.722a.546.546 0 0 0 .527.708h.797c.373 0 .637-.36.527-.708l-.538-1.722c-.116-.382-.654-.382-.775 0");
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jhdqd89ez {
  stop-color: var(--svg-color--342554, #342554);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jletv-brl {
  stop-color: var(--svg-color--8067c6, #8067C6);
}

.k_wydox9f {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.896 8.28c.326-.079 1.139-.04 1.682.35");
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k796fybnd {
  stop-color: var(--svg-color--8870c8, #8870C8);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l-cnygept {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.056 8.28c-.327-.079-1.14-.04-1.682.35");
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
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

.m88wbrbun {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.931 13.633a3.1 3.1 0 0 1-1.44-.35c-.142-.073-.295.09-.205.223a1.957 1.957 0 0 0 3.29 0c.09-.138-.062-.296-.205-.222a3.05 3.05 0 0 1-1.44.349");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbuex5b5r {
  stop-color: var(--svg-color--6b47bb, #6B47BB);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mfuun6zqx {
  stroke: var(--svg-color--fcc4b2, #FCC4B2);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M16.145 18.338c.19.027.71.032 1.275-.163");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mxu1gt6vp {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.544 10.318l-.538 1.722a.546.546 0 0 0 .527.708h.797c.373 0 .637-.36.527-.708l-.538-1.722c-.116-.382-.654-.382-.775 0");
}

.n_p-4bbbu {
  stop-color: var(--svg-color--e6dee6, #E6DEE6);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n2ia63biy {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.077 9.787c.064.086-.07.191-.223.305c-.153.115-.267.195-.331.11c-.065-.087.007-.25.16-.364s.33-.137.394-.051");
}

.n44b27bdp {
  stop-color: var(--svg-color--7353bf, #7353BF);
}

.n5l_opbqq {
  r: 6.305px;
}

.nh4l3fbho {
  stop-color: var(--svg-color--684c87, #684C87);
  stop-opacity: 0;
}

.nj9ng6b5g {
  d: path("M11.204 11.772a1.088 1.088 0 1 0 0-2.176a1.088 1.088 0 0 0 0 2.176");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.nz8ufunsm {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
  stop-opacity: 0;
}

.o4sg_vbnc {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ozroxmy8l {
  stop-color: var(--svg-color--6b47bb, #6B47BB);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pgum8_8zk {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.71 8.42l-.139.233za.272.272 0 0 1-.279.466l-.005-.003a1 1 0 0 0-.114-.059a3 3 0 0 0-.347-.137a2.3 2.3 0 0 0-1.086-.093a.272.272 0 0 1-.095-.535a2.84 2.84 0 0 1 1.346.11a3.3 3.3 0 0 1 .566.242l.01.006l.002.002z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.q8d1l4bok {
  stop-color: var(--svg-color--6d4f8c, #6D4F8C);
  stop-opacity: 0;
}

.qc07hnbjk {
  stop-color: var(--svg-color--fbf7ff, #FBF7FF);
}

.qc0o5_36v {
  stop-color: var(--svg-color--e0d6e3, #E0D6E3);
}

.qdcgkefpz {
  stop-color: var(--svg-color--f1b6a2, #F1B6A2);
}

.qnar36wle {
  r: 4.086px;
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qujrzvqgg {
  fill: var(--svg-color--7a60bc, #7A60BC);
  d: path("M21.82 17.353c-.642-1.313-1.821-1.75-2.595-1.75h-2.609v2.875h2.47c.168.303.002.85-.102 1.086l-3.94 10.39h3.177c1.067-2.583 2.995-7.817 3.383-8.742c.42-1.004.809-2.476.215-3.86");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qy9hi7mpo {
  fill: var(--svg-color--232121, #232121);
  d: path("M10.797 4.618c.573-.607 1.657-.608 2.158-.517l.401 1.307c-.256-.04-.484.051-.676.238c-.455 1.277-2.015 1.98-2.74 2.173c-.15-1.511.111-2.41.857-3.2");
}

.r_bcr-ntk {
  cx: 10.674px;
  cy: 16.165px;
  r: 4.086px;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r8blt-bnx {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.204 11.772a1.088 1.088 0 1 0 0-2.176a1.088 1.088 0 0 0 0 2.176");
}

.r8td-ob5s {
  stop-color: var(--svg-color--f3ebfe, #F3EBFE);
}

.r9e33mbdc {
  stop-color: var(--svg-color--e7a08d, #E7A08D);
  stop-opacity: 0;
}

.rg4nauy9l {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.088 10.107c.269-.473.677-.846 1.557-.846c.385 0 .757.107 1.087.373c.272.22.236.502.025.607l-.563.322c-.66-.213-1.39-.242-2.106-.456");
}

.rgs-6fbpw {
  d: path("M5.096 29.939c0-7.961 4.617-9.875 5.375-10.383l5.047 10.383z");
}

.roh2cebgd {
  stop-color: var(--svg-color--6349aa, #6349AA);
}

.rw7u0kjxx {
  fill: var(--svg-color--795cc2, #795CC2);
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.rz_1qnb6a {
  stop-color: var(--svg-color--593d6e, #593D6E);
  stop-opacity: 0;
}

.rzjfiqxaf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.003 4.057c.023.247.237 1.172.552 1.732");
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s4fsmlbta {
  d: path("M18.949 10.38a.85.85 0 0 0-.235-.468l-.263.289l.119.231z");
}

.s4yx1cc8i {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.32 2.793c-1.147-.254-2.177.89-2.296 1.315c1.065 3.591 3.76 3.394 6.422 3.099c1.592-.177 1.765.549 1.901.9c0-3.984-3.387-4.732-5.998-5.308z");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.snymmbrnj {
  stop-color: var(--svg-color--d5c4df, #D5C4DF);
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.sv9br1byn {
  stop-color: var(--svg-color--5e40aa, #5E40AA);
  stop-opacity: 0;
}

.t_z9a_1_e {
  d: path("M20.82 12.314a1.63 1.63 0 1 0 0-3.26a1.63 1.63 0 0 0 0 3.26");
}

.t9qyh6bmf {
  cx: 13.446px;
  cy: 9.982px;
  rx: 0.395px;
  ry: 0.2px;
}

.tbqxjbcmi {
  stop-color: var(--svg-color--614279, #614279);
  stop-opacity: 0;
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tkat5cdin {
  stop-color: var(--svg-color--795cc2, #795CC2);
  stop-opacity: 0;
}

.tqo-vnfob {
  stop-color: var(--svg-color--9078d3, #9078D3);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.ttp7yqb-m {
  stop-color: var(--svg-color--9279d5, #9279D5);
}

.u44j7rbwl {
  stop-color: var(--svg-color--7c60c4, #7C60C4);
  stop-opacity: 0;
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ucnajwbxu {
  fill: var(--svg-color--000, #000);
  d: path("M17.626 10.5c0-.288.23-.518.517-.518a.516.516 0 0 1 .46.756h-.916a.47.47 0 0 1-.061-.238");
}

.upo930jwf {
  d: path("M15.32 2.793c-1.147-.254-2.177.89-2.296 1.315c1.065 3.591 3.76 3.394 6.422 3.099c1.592-.177 1.765.549 1.901.9c0-3.984-3.387-4.732-5.998-5.308z");
}

.urfu17b_m {
  d: path("M10.778 9.405h.012l-.01-.269l-.01-.31c.02-.961.582-1.333.82-1.457l.052-.02q.029-.014.052-.021c.54-.248.977-.683 1.205-1.251l.083-.196a.267.267 0 0 1 .468-.052a3.91 3.91 0 0 0 3.23 1.695h3.262c.182 0 1.096.088 1.15 1.35l-.12 3.112c-.125 2.839-2.342 4.745-5.048 4.745s-4.922-1.906-5.047-4.745z");
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v1nc78bgs {
  stop-color: var(--svg-color--fabfa6, #FABFA6);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v6wds2dtn {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vze8wny8i {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w8e9izb-y {
  d: path("M26.947 29.939c0-7.961-4.617-9.875-5.375-10.383l-5.047 10.383z");
}

.wkmk90b2p {
  fill: var(--svg-color--e8d6ff, #E8D6FF);
  d: path("M1.97 24.017h3.298a5.94 5.94 0 0 1 5.937 5.937H1.971zm28.06 0h-3.298a5.94 5.94 0 0 0-5.937 5.937h9.234z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.wv2o2nbhk {
  stop-color: var(--svg-color--7a67ab, #7A67AB);
}

.wyw_zsaao {
  fill: var(--svg-color--000, #000);
  d: path("M14.237 10.5a.516.516 0 0 0-.518-.518a.516.516 0 0 0-.46.756h.916a.5.5 0 0 0 .062-.238");
}

.x37sucbkr {
  stop-color: var(--svg-color--8870c8, #8870C8);
}

.x4p5bn7mz {
  stop-color: var(--svg-color--2c1c48, #2C1C48);
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

.xn4dl3btn {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.82 11.772a1.088 1.088 0 1 0 0-2.176a1.088 1.088 0 0 0 0 2.176");
}

.xooo5lvln {
  fill-rule: evenodd;
  d: path("M23.21 12.112c.214-.441.327-.933.327-1.446a3.3 3.3 0 0 0-.272-1.322h.005a3 3 0 0 0-.284-.52l-.002-.003a3.3 3.3 0 0 1-.534-1.794v-.01a3.34 3.34 0 0 0-3.341-3.342a.55.55 0 0 1-.461-.235a3.35 3.35 0 0 0-2.717-1.394a3.35 3.35 0 0 0-2.716 1.394a.57.57 0 0 1-.462.236h-.086a3.34 3.34 0 0 0-3.255 3.341v.01c0 .636-.185 1.261-.533 1.794l-.003.004a3.34 3.34 0 0 0-.223 3.287a.52.52 0 0 1 0 .461c-.205.43-.328.912-.328 1.425a3.255 3.255 0 0 0 3.26 3.26h8.692a3.255 3.255 0 0 0 3.26-3.26c0-.513-.123-.994-.328-1.425a.52.52 0 0 1 0-.461M10.79 9.405h-.012l1.214 2.386c.125 2.839 1.233 0 3.939 0s3.886 3.16 4.01.32l1.151-3.238c-.054-1.26-.968-1.349-1.15-1.349H16.68a3.91 3.91 0 0 1-3.23-1.695a.267.267 0 0 0-.468.052l-.083.196a2.33 2.33 0 0 1-1.205 1.25l-.052.021q-.028.013-.051.021c-.24.124-.8.496-.821 1.457l.01.31z");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y_9p2zbzc {
  d: path("M10.797 4.618c.573-.607 1.657-.608 2.158-.517l.401 1.307c-.256-.04-.484.051-.676.238c-.455 1.277-2.015 1.98-2.74 2.173c-.15-1.511.111-2.41.857-3.2");
}

.y-a_999zn {
  stop-color: var(--svg-color--7e64c5, #7E64C5);
  stop-opacity: 0;
}

.y41hsabjm {
  stop-color: var(--svg-color--704cc0, #704CC0);
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.ytvm2kbdn {
  d: path("M15.956 15.531h-.04c.1 0 .192 0 .293.01c-.081-.01-.172-.01-.253-.01");
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z0qi4zb3s {
  stop-color: var(--svg-color--684c87, #684C87);
}

.z374e_6sn {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.931 13.633a3.1 3.1 0 0 1-1.44-.35c-.142-.073-.295.09-.205.223a1.957 1.957 0 0 0 3.29 0c.09-.138-.062-.296-.205-.222a3.05 3.05 0 0 1-1.44.349Z");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zantcf-1d {
  stop-color: var(--svg-color--775cbc, #775CBC);
}

.zosz72acb {
  d: path("M16.29 15.531c.252.01.514.03.777.05c-.263-.02-.515-.04-.778-.05");
}

.zzsb9xb8w {
  d: path("M21.82 17.353c-.642-1.313-1.821-1.75-2.595-1.75h-2.609v2.875h2.47c.168.303.002.85-.102 1.086l-3.94 10.39h3.177c1.067-2.583 2.995-7.817 3.383-8.742c.42-1.004.809-2.476.215-3.86");
}

</style>
