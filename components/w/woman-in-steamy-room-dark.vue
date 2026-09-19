<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iIR1gzd)" class="lci33sbas"/><circle fill="url(#iGl3jDb)" class="lci33sbas"/><circle fill="url(#iI1NFde)" class="tyonxd6hb"/><circle fill="url(#igczLIe)" transform="matrix(-1 0 0 1 21.326 16.14)" class="qnar36wle"/><circle fill="url(#iE9wJUA)" transform="matrix(-1 0 0 1 21.326 16.14)" class="qnar36wle"/><circle fill="url(#iiFjNse)" transform="matrix(-1 0 0 1 23.725 23.344)" class="n5l_opbqq"/><g filter="url(#iBfgxle)"><path fill="url(#i2GQTgb)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#iotyVxK)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#irhy5pd)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#iufgFUb)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#igaDIfd)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#iJzliFb)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#iPsbXwc)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#iORmZsc)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#isuT7rV)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#iX9sJYP)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#ig04ppd)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#iys4SOc)" clip-rule="evenodd" class="hysa-obih"/></g><path fill="url(#i0kcK7c)" class="hieissb8f"/><path fill="url(#iolH3vb)" class="hieissb8f"/><path fill="url(#iB3hoPT)" class="hieissb8f"/><path fill="url(#iusAoje)" class="jzdyl8vho"/><path fill="url(#il155vc)" class="jzdyl8vho"/><path class="r7qt7msxe"/><path fill="url(#iwk2VUb)" class="g82rs5bds"/><path fill="url(#i5JGmPe)" class="g82rs5bds"/><path fill="url(#ivaa0Tz)" class="g82rs5bds"/><path fill="url(#i4bO0ep)" class="g82rs5bds"/><path fill="url(#il8OUce)" class="g82rs5bds"/><path fill="url(#iEjsBbc)" class="g82rs5bds"/><path class="fuhh63zgj"/><path fill="url(#iMN29Ne)" class="kodm2eyrj"/><path fill="url(#iUzxEbL)" class="kodm2eyrj"/><path fill="url(#ihkZPvb)" class="kodm2eyrj"/><g filter="url(#i1Q0qJb)"><path fill="url(#iqTYp1g)" class="y6189wa3s"/><path fill="url(#ingjtVd)" class="y6189wa3s"/><path fill="url(#iu7iaLb)" class="y6189wa3s"/></g><path class="x584qub8p"/><g filter="url(#iEehCGb)"><path class="yo5rkx0ty"/></g><path fill="url(#itzCYmc)" class="jka0aeb3t"/><path fill="url(#i4Rqs2c)" class="rfe2cabsc"/><g filter="url(#im8G6de)"><path fill="url(#iyYkCuc)" class="mjvtp10ft"/></g><g filter="url(#iodBKbe)"><path fill="url(#isE8wjB)" class="jxhm1ib2i"/><path fill="url(#iPxHDPb)" class="jxhm1ib2i"/></g><g filter="url(#ieXa63b)"><path class="ruhbhkkus"/><path fill="url(#iVKZDud)" class="lkbw50g8u"/></g><g filter="url(#if15CQc)"><path class="qsd0a64ps"/><path fill="url(#i53SXPw)" class="n27uwn5ui"/></g><g filter="url(#int4Hld)"><path fill="url(#inaytrb)" class="ujmzz-8fx"/><path fill="url(#iwCtGrA)" class="ujmzz-8fx"/><path fill="url(#ixXOe1b)" class="ujmzz-8fx"/><path fill="url(#iKZwkOe)" class="ujmzz-8fx"/><path fill="url(#i6EdWTd)" class="ujmzz-8fx"/><path fill="url(#iNhcdMb)" class="ujmzz-8fx"/><path fill="url(#ikYR2ze)" class="ujmzz-8fx"/><path fill="url(#irxu12c)" class="ujmzz-8fx"/></g><path fill="url(#i7fut7c)" class="ujmzz-8fx"/><path fill="url(#isFDjPd)" class="ujmzz-8fx"/><g filter="url(#iTdBUSx)"><path class="vu75dna4z"/></g><g filter="url(#iY5qqde)"><path class="fco-z1cdl"/><path fill="url(#iiElm0d)" class="e7cczo7nf"/><path fill="url(#iIMsUSd)" class="e7cczo7nf"/><path fill="url(#iazU81t)" class="e7cczo7nf"/><path fill="url(#iXQxAHc)" class="e7cczo7nf"/></g><g filter="url(#i6GLxmb)"><path stroke="url(#inT9i8b)" class="ux1udsynf"/></g><path class="ztwx-ucga"/><g filter="url(#i0pwxpc)"><path class="n97j7f4oh"/></g><g filter="url(#iIe692Z)"><path class="xmikh_b7g"/></g><g filter="url(#i1ZdRSE)"><path class="pdktq5g-f"/></g><g filter="url(#iFhfHwd)"><path clip-rule="evenodd" class="qc_n6cavf"/></g><path class="g3dwi4b-d"/><path fill="url(#ioimzDb)" class="kdxd4jb8w"/><path class="usevvd_vg"/><g filter="url(#ioZRqPQ)"><path class="gqq70jouh"/><path fill="url(#iMCrcqb)" class="fxpizo1ic"/></g><g filter="url(#iqPf36c)"><path fill="url(#iPQ3lYd)" class="gmupt-bfb"/></g><path class="bg9a43hyt"/><path fill="url(#i9gRflv)" class="g-phrvb2c"/><path class="dnrth1wtg"/><g filter="url(#iVuDRAb)"><path fill="url(#ija1TNe)" class="hl9u90b9d"/></g><g filter="url(#icqSGCb)"><ellipse transform="rotate(-27.914 13.454 9.981)" class="arxs48xhc"/><ellipse fill="url(#iA4ntQd)" transform="rotate(-27.914 13.454 9.981)" class="a042a5b8x"/></g><g filter="url(#irUyq2c)"><path class="v9mvjzb1z"/></g><g filter="url(#i3aEQ3c)"><path class="e_5qakvun"/></g><g filter="url(#iE3qble)"><path class="wcgf0-brn"/><path fill="url(#imC6sEd)" class="fvc1igb4j"/></g><g filter="url(#iQ7ZuYk)"><path class="gv4beqbbo"/><path fill="url(#iskxCud)" class="ijwy94blt"/><path fill="url(#iQhMMre)" class="ijwy94blt"/></g><g filter="url(#iDxVlUd)"><path stroke="url(#iGBd6rY)" class="ddkad0blm"/></g><g filter="url(#in5mBnd)"><path class="s1sf7bc-d"/></g><defs><radialGradient id="iIR1gzd" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -2.4375 2.72822 4.02238 6.877 17.305)" gradientUnits="userSpaceOnUse"><stop class="dgu6o60tg"/><stop offset="1" class="n_p-4bbbu"/></radialGradient><radialGradient id="iGl3jDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 -1.76562 2.48224 -.02197 8.596 17.805)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="v6wds2dtn"/><stop offset="1" class="nz8ufunsm"/></radialGradient><radialGradient id="iI1NFde" cx="0" cy="0" r="1" gradientTransform="matrix(-5.47138 9.4622 -7.02133 -4.05998 10.46 19.244)" gradientUnits="userSpaceOnUse"><stop class="qc0o5_36v"/><stop offset="1" class="snymmbrnj"/></radialGradient><radialGradient id="igczLIe" cx="0" cy="0" r="1" gradientTransform="rotate(44.444 -1.585 1.225)scale(4.68833)" gradientUnits="userSpaceOnUse"><stop class="qc07hnbjk"/><stop offset=".836" class="b_5radckw"/></radialGradient><radialGradient id="iE9wJUA" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.59375 5.11385 -.10027 2.316 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vze8wny8i"/><stop offset="1" class="o4sg_vbnc"/></radialGradient><radialGradient id="iiFjNse" cx="0" cy="0" r="1" gradientTransform="matrix(4.95236 7.33803 -10.65664 7.19205 1.352 1.24)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="r8td-ob5s"/><stop offset=".819" class="eegxz98yy"/></radialGradient><radialGradient id="iotyVxK" cx="0" cy="0" r="1" gradientTransform="matrix(-.6092 4.60291 -5.74997 -.76102 15.627 13.205)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="irhy5pd" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.332 8.692)scale(3.51082 4.61294)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iufgFUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31994 1.7261 -1.3254 -1.01353 11.04 10.904)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="igaDIfd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30305 2.13222 -1.50197 -.91788 11.497 8.856)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iJzliFb" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.083 11.517)scale(2.98239 4.14001)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iPsbXwc" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.949 6.84)scale(2.05809 2.87615)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iORmZsc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86139 .54152 -1.1293 -3.88178 23.512 9.82)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="isuT7rV" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84289 .71076 -.9054 -3.62141 22.903 13.273)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iX9sJYP" cx="0" cy="0" r="1" gradientTransform="matrix(-.91314 -2.67575 2.11636 -.72224 20.71 7.363)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ig04ppd" cx="0" cy="0" r="1" gradientTransform="matrix(1.51838 .15927 -.25806 2.46021 9.73 9.784)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iys4SOc" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 2.674 7.097)scale(2.9478 2.71731)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="i0kcK7c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35939 5.78125 -6.81223 -1.6018 23.096 22.555)" gradientUnits="userSpaceOnUse"><stop class="ttp7yqb-m"/><stop offset="1" class="jletv-brl"/></radialGradient><radialGradient id="iusAoje" cx="0" cy="0" r="1" gradientTransform="matrix(6.87457 8.07189 -11.19707 9.5362 6.418 22.295)" gradientUnits="userSpaceOnUse"><stop class="wv2o2nbhk"/><stop offset="1" class="n44b27bdp"/></radialGradient><radialGradient id="iwk2VUb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.03127 -6.31539 -6.64086 13.752 16.367)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="epu6iq_fg"/><stop offset="1" class="q8d1l4bok"/></radialGradient><radialGradient id="ivaa0Tz" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82764 -11.66358 1.58185 -.65474 15.958 28.938)" gradientUnits="userSpaceOnUse"><stop class="x37sucbkr"/><stop offset="1" class="k796fybnd"/></radialGradient><radialGradient id="il8OUce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37282 -3.155 .92095 -.40073 16.346 27.555)" gradientUnits="userSpaceOnUse"><stop class="bp-uy2zsn"/><stop offset="1" class="dfpk_zbbl"/></radialGradient><radialGradient id="iEjsBbc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15863 -1.17796 1.62432 -1.59766 14.336 18.49)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="jhdqd89ez"/><stop offset="1" class="tbqxjbcmi"/></radialGradient><radialGradient id="iUzxEbL" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.67188 .83418 2.50254 17.502 18.305)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="x4p5bn7mz"/><stop offset="1" class="rz_1qnb6a"/></radialGradient><radialGradient id="ihkZPvb" cx="0" cy="0" r="1" gradientTransform="rotate(110.875 2.499 18.281)scale(11.8396 2.00952)" gradientUnits="userSpaceOnUse"><stop class="tqo-vnfob"/><stop offset="1" class="fqnn-rb2e"/></radialGradient><radialGradient id="ingjtVd" cx="0" cy="0" r="1" gradientTransform="matrix(1.81249 1.92626 -2.40788 2.26566 13.158 16.148)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="p2wvms-7r"/><stop offset="1" class="a0_4-ebgl"/></radialGradient><radialGradient id="iu7iaLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.31547 -.76307 0 16.64 15.065)" gradientUnits="userSpaceOnUse"><stop class="vjc5s1b0i"/><stop offset="1" class="htop0jbiy"/></radialGradient><radialGradient id="isE8wjB" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 35.682 -40.626)scale(2.76041 3.37034)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iPxHDPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.32842 .7446 -.2105 .37556 21.05 8.983)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iVKZDud" cx="0" cy="0" r="1" gradientTransform="matrix(1.5244 -.1134 .08864 1.19167 20.365 10.794)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="i53SXPw" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21842 0 0 -.96118 11.286 10.68)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="inaytrb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.56611 3.02785 -4.05273 -8.78862 18.818 10.138)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="iwCtGrA" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 7.645 7.504)scale(2.27768 1.58614)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="ixXOe1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.08382 -3.5095 4.4529 1.37516 13.731 16.986)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iKZwkOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.80978 6.86539 -6.90215 -.81411 16.477 10.296)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="i6EdWTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.63005 -6.66555 0 15.67 10.535)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="iNhcdMb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.302 6.806)scale(7.10505 12.2327)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="ikYR2ze" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16184 1.42589 0 18.255 9.715)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="irxu12c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.32513 1.51869 0 13.835 9.485)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="i7fut7c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29764 0 0 -6.50755 21.076 11.217)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="isFDjPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84658 1.58949 -1.06532 -1.23763 19.89 15.303)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iiElm0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.45992 -2.06366 .636 -.14174 16.723 11.951)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iXQxAHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7869 0 0 -.22 16.481 12.165)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="ioimzDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81912 -1.3029 0 18.134 10.078)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iMCrcqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23414 -.30173 .41541 -.32237 17.903 10.162)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9gRflv" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81912 -1.3029 0 13.728 10.078)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iA4ntQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00781 -.49881 .59959 -.00939 13.439 10.299)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imC6sEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.27416 -2.78192 1.42316 .65183 10.219 7.937)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iskxCud" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.088 6.954)scale(4.91976 8.04351)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iQhMMre" cx="0" cy="0" r="1" gradientTransform="matrix(-.21236 1.38034 -2.96973 -.45687 16.143 3.053)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iBfgxle" width="15.412" height="15.912" x="8.35" y="1.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_780"/></filter><filter id="i1Q0qJb" width="6.906" height="12.039" x="12.293" y="15.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0509804 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_780"/></filter><filter id="iEehCGb" width="3.076" height="1.977" x="15.245" y="17.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".3"/></filter><filter id="im8G6de" width="3.399" height="3.249" x="9.576" y="9.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_780"/></filter><filter id="iodBKbe" width="3.249" height="3.499" x="19.18" y="8.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_780"/></filter><filter id="ieXa63b" width="3.169" height="3.169" x="19.22" y="9.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".25"/></filter><filter id="if15CQc" width="2.669" height="2.669" x="9.885" y="9.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".125"/></filter><filter id="int4Hld" width="10.289" height="11.231" x="10.787" y="5.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_780"/></filter><filter id="iTdBUSx" width="2.895" height="3.708" x="14.32" y="9.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".25"/></filter><filter id="iY5qqde" width="2.395" height="3.208" x="14.733" y="9.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".125"/></filter><filter id="i6GLxmb" width="3.734" height="1.537" x="14.064" y="13.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".05"/></filter><filter id="i0pwxpc" width="3.028" height="1.298" x="16.884" y="9.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_780"/></filter><filter id="iIe692Z" width="3.028" height="1.298" x="11.95" y="9.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_780"/></filter><filter id="i1ZdRSE" width="2.474" height="1.1" x="12.086" y="7.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_780"/></filter><filter id="iFhfHwd" width="2.474" height="1.1" x="17.556" y="7.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_780"/></filter><filter id="ioZRqPQ" width=".792" height=".701" x="17.394" y="9.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".05"/></filter><filter id="iqPf36c" width=".896" height=".918" x="18.243" y="9.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".1"/></filter><filter id="iVuDRAb" width=".992" height="1.046" x="13.757" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".1"/></filter><filter id="icqSGCb" width=".92" height=".709" x="12.994" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".05"/></filter><filter id="irUyq2c" width="2.477" height="1.181" x="17.489" y="7.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".1"/></filter><filter id="i3aEQ3c" width="2.477" height="1.181" x="11.985" y="7.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".1"/></filter><filter id="iE3qble" width="4.445" height="4.749" x="9.419" y="3.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_780"/><feGaussianBlur result="effect2_foregroundBlur_4002_780" stdDeviation=".25"/></filter><filter id="iQ7ZuYk" width="8.846" height="5.833" x="12.733" y="2.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_780"/><feGaussianBlur result="effect2_foregroundBlur_4002_780" stdDeviation=".125"/></filter><filter id="iDxVlUd" width="1.15" height="2.326" x="12.712" y="3.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".1"/></filter><filter id="in5mBnd" width="6.475" height="3.39" x="15.351" y="4.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_780" stdDeviation=".375"/></filter><linearGradient id="i2GQTgb" x1="20.669" x2="13.799" y1="3.661" y2="16.387" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iolH3vb" x1="24.158" x2="24.189" y1="30.305" y2="26.648" gradientUnits="userSpaceOnUse"><stop offset=".078" class="y41hsabjm"/><stop offset="1" class="y-a_999zn"/></linearGradient><linearGradient id="iB3hoPT" x1="18.12" x2="19.472" y1="27.74" y2="28.127" gradientUnits="userSpaceOnUse"><stop class="mbuex5b5r"/><stop offset="1" class="ozroxmy8l"/></linearGradient><linearGradient id="il155vc" x1="13.658" x2="12.158" y1="28.711" y2="29.242" gradientUnits="userSpaceOnUse"><stop class="g82zxu-vf"/><stop offset="1" class="sv9br1byn"/></linearGradient><linearGradient id="i5JGmPe" x1="12.315" x2="13.69" y1="27.367" y2="26.805" gradientUnits="userSpaceOnUse"><stop offset=".223" class="zantcf-1d"/><stop offset="1" class="tkat5cdin"/></linearGradient><linearGradient id="i4bO0ep" x1="15.627" x2="14.221" y1="30.148" y2="29.461" gradientUnits="userSpaceOnUse"><stop offset=".208" class="roh2cebgd"/><stop offset="1" class="u44j7rbwl"/></linearGradient><linearGradient id="iMN29Ne" x1="16.002" x2="18.033" y1="24.805" y2="25.711" gradientUnits="userSpaceOnUse"><stop class="z0qi4zb3s"/><stop offset="1" class="nh4l3fbho"/></linearGradient><linearGradient id="iqTYp1g" x1="16.366" x2="16.366" y1="24.888" y2="14.402" gradientUnits="userSpaceOnUse"><stop class="rh4-2jbhq"/><stop offset="1" class="au_bk3bwb"/></linearGradient><linearGradient id="itzCYmc" x1="8.677" x2="23.191" y1="15.536" y2="15.536" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i4Rqs2c" x1="8.677" x2="23.191" y1="15.506" y2="15.506" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iyYkCuc" x1="9.576" x2="12.564" y1="10.768" y2="10.768" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iIMsUSd" x1="14.983" x2="15.931" y1="12.025" y2="12.025" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iazU81t" x1="15.931" x2="15.931" y1="12.831" y2="12.215" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="inT9i8b" x1="14.856" x2="15.322" y1="14.255" y2="13.535" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iPQ3lYd" x1="18.919" x2="18.603" y1="10.132" y2="10.327" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ija1TNe" x1="14.479" x2="14.162" y1="10.132" y2="10.327" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGBd6rY" x1="13.012" x2="13.562" y1="4.423" y2="5.709" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-steamy-room-dark" /></template>
<style>
.a0_4-ebgl {
  stop-color: var(--svg-color--381e1a, #381E1A);
  stop-opacity: 0;
}

.a042a5b8x {
  cx: 13.454px;
  cy: 9.981px;
  rx: 0.393px;
  ry: 0.199px;
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.arxs48xhc {
  cx: 13.454px;
  cy: 9.981px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.393px;
  ry: 0.199px;
}

.au_bk3bwb {
  stop-color: var(--svg-color--462a27, #462A27);
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b_5radckw {
  stop-color: var(--svg-color--f2e8f1, #F2E8F1);
}

.bg9a43hyt {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.517 9.322a1.41 1.41 0 0 0-1.368 1.069a.277.277 0 0 0 .27.344h2.253a.232.232 0 0 0 .23-.275a1.415 1.415 0 0 0-1.385-1.138");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bp-uy2zsn {
  stop-color: var(--svg-color--442d6d, #442D6D);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
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

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.ddkad0blm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.012 4.076c.024.245.237 1.167.55 1.726");
}

.dfpk_zbbl {
  stop-color: var(--svg-color--7c5fac, #7C5FAC);
  stop-opacity: 0;
}

.dgu6o60tg {
  stop-color: var(--svg-color--e1dae6, #E1DAE6);
}

.dnrth1wtg {
  fill: var(--svg-color--000, #000);
  d: path("M14.242 10.497a.514.514 0 0 0-.516-.516a.514.514 0 0 0-.459.754h.914a.5.5 0 0 0 .061-.238");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.e_5qakvun {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.062 8.285c-.326-.08-1.136-.04-1.677.348");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7cczo7nf {
  d: path("m15.545 10.316l-.537 1.716a.544.544 0 0 0 .526.706h.794a.546.546 0 0 0 .526-.706l-.537-1.716c-.115-.38-.652-.38-.772 0");
}

.eegxz98yy {
  stop-color: var(--svg-color--dac9f0, #DAC9F0);
}

.epu6iq_fg {
  stop-color: var(--svg-color--4f3466, #4F3466);
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fco-z1cdl {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.545 10.316l-.537 1.716a.544.544 0 0 0 .526.706h.794a.546.546 0 0 0 .526-.706l-.537-1.716c-.115-.38-.652-.38-.772 0");
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.fqnn-rb2e {
  stop-color: var(--svg-color--7b63b3, #7B63B3);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuhh63zgj {
  fill: var(--svg-color--7a60bc, #7A60BC);
  d: path("M21.82 17.328c-.642-1.312-1.821-1.75-2.595-1.75h-2.609v2.875h2.47c.168.303.002.85-.102 1.086l-3.94 10.39h3.177c1.067-2.583 2.995-7.816 3.383-8.741c.42-1.004.809-2.477.215-3.86");
}

.fvc1igb4j {
  d: path("M10.813 4.635c.571-.606 1.652-.606 2.152-.516l.399 1.303c-.255-.04-.483.05-.674.237c-.453 1.272-2.009 1.974-2.73 2.166c-.15-1.506.11-2.403.853-3.19");
}

.fxpizo1ic {
  d: path("M18.07 9.787c.064.085-.07.19-.223.304c-.152.114-.265.195-.33.109c-.064-.086.008-.248.16-.362c.153-.114.329-.137.393-.051");
}

.g-phrvb2c {
  d: path("M13.726 9.596a.9.9 0 0 0-.868 1.139h1.74a1 1 0 0 0 .033-.238a.907.907 0 0 0-.905-.901");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g3dwi4b-d {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.345 9.322c.66 0 1.216.454 1.368 1.069a.277.277 0 0 1-.27.344H17.19a.232.232 0 0 1-.23-.275a1.41 1.41 0 0 1 1.385-1.138");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g82rs5bds {
  d: path("M9.9 17.328c.641-1.312 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.816-3.68-8.741c-.42-1.004-.89-2.477-.297-3.86");
}

.g82zxu-vf {
  stop-color: var(--svg-color--5e40aa, #5E40AA);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gmupt-bfb {
  d: path("M18.939 10.379a.85.85 0 0 0-.234-.468l-.262.288l.118.23z");
}

.gqq70jouh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.07 9.787c.064.085-.07.19-.223.304c-.152.114-.265.195-.33.109c-.064-.086.008-.248.16-.362c.153-.114.329-.137.393-.051");
}

.gv4beqbbo {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.322 2.815c-1.144-.253-2.17.888-2.289 1.311c1.062 3.58 3.749 3.383 6.401 3.089c1.588-.177 1.76.547 1.895.897c0-3.97-3.376-4.716-5.978-5.29z");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hieissb8f {
  d: path("M26.947 29.914c0-7.96-4.617-9.875-5.375-10.383l-5.047 10.383z");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hl9u90b9d {
  d: path("M14.55 10.391c0-.291-.238-.485-.302-.544l-.29.282l.178.364z");
}

.htop0jbiy {
  stop-color: var(--svg-color--513f3e, #513F3E);
  stop-opacity: 0;
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hysa-obih {
  fill-rule: evenodd;
  d: path("M23.185 12.104c.215-.44.327-.93.327-1.44a3.3 3.3 0 0 0-.27-1.319h.005a3 3 0 0 0-.284-.518l-.002-.003a3.27 3.27 0 0 1-.532-1.788v-.01a3.33 3.33 0 0 0-3.33-3.331a.54.54 0 0 1-.46-.235a3.34 3.34 0 0 0-2.708-1.39a3.34 3.34 0 0 0-2.708 1.39a.57.57 0 0 1-.46.235l-.085.001a3.33 3.33 0 0 0-3.245 3.33v.01A3.27 3.27 0 0 1 8.9 8.824l-.002.004a3.33 3.33 0 0 0-.222 3.276a.52.52 0 0 1 0 .46a3.244 3.244 0 0 0 2.922 4.67h8.664a3.244 3.244 0 0 0 2.922-4.67a.52.52 0 0 1 0-.46M10.807 9.406h-.012l1.21 2.378c.125 2.83 1.229 0 3.926 0s3.873 3.15 3.998.32l1.147-3.228c-.055-1.257-.966-1.345-1.147-1.345h-3.251a3.9 3.9 0 0 1-3.22-1.69a.266.266 0 0 0-.466.052l-.083.196a2.33 2.33 0 0 1-1.2 1.246l-.053.02l-.051.021c-.239.124-.798.495-.818 1.453l.01.309z");
}

.ijwy94blt {
  d: path("M15.322 2.815c-1.144-.253-2.17.888-2.289 1.311c1.062 3.58 3.749 3.383 6.401 3.089c1.588-.177 1.76.547 1.895.897c0-3.97-3.376-4.716-5.978-5.29z");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jhdqd89ez {
  stop-color: var(--svg-color--342554, #342554);
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jka0aeb3t {
  d: path("M16.29 15.506c.252.01.514.03.777.05c-.263-.02-.515-.04-.778-.05");
}

.jletv-brl {
  stop-color: var(--svg-color--8067c6, #8067C6);
}

.jxhm1ib2i {
  d: path("M20.805 12.305a1.624 1.624 0 1 0 0-3.249a1.624 1.624 0 0 0 0 3.249");
}

.jzdyl8vho {
  d: path("M5.096 29.914c0-7.96 4.617-9.875 5.375-10.383l5.047 10.383z");
}

.k796fybnd {
  stop-color: var(--svg-color--8870c8, #8870C8);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kdxd4jb8w {
  d: path("M18.136 9.596a.9.9 0 0 1 .868 1.139h-1.74a.905.905 0 0 1 .872-1.139");
}

.kodm2eyrj {
  d: path("M21.82 17.328c-.642-1.312-1.821-1.75-2.595-1.75h-2.609v2.875h2.47c.168.303.002.85-.102 1.086l-3.94 10.39h3.177c1.067-2.583 2.995-7.816 3.383-8.741c.42-1.004.809-2.477.215-3.86");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lci33sbas {
  cx: 10.674px;
  cy: 16.141px;
  r: 4.086px;
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkbw50g8u {
  d: path("M20.805 11.765a1.084 1.084 0 1 0 0-2.169a1.084 1.084 0 0 0 0 2.169");
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbuex5b5r {
  stop-color: var(--svg-color--6b47bb, #6B47BB);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mjvtp10ft {
  d: path("M11.2 12.305a1.624 1.624 0 1 0 0-3.249a1.624 1.624 0 0 0 0 3.249");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n_p-4bbbu {
  stop-color: var(--svg-color--e6dee6, #E6DEE6);
}

.n27uwn5ui {
  d: path("M11.22 11.765a1.084 1.084 0 1 0 0-2.169a1.084 1.084 0 0 0 0 2.169");
}

.n44b27bdp {
  stop-color: var(--svg-color--7353bf, #7353BF);
}

.n5l_opbqq {
  r: 6.305px;
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.n97j7f4oh {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.084 10.106c.268-.471.675-.844 1.552-.844c.384 0 .754.107 1.083.373c.272.219.235.5.025.605l-.561.32c-.658-.213-1.386-.241-2.099-.454");
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nh4l3fbho {
  stop-color: var(--svg-color--684c87, #684C87);
  stop-opacity: 0;
}

.nz8ufunsm {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
  stop-opacity: 0;
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o4sg_vbnc {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
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

.p2wvms-7r {
  stop-color: var(--svg-color--340f0b, #340F0B);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pdktq5g-f {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.5 8.886l-.004.002a.27.27 0 0 1-.278-.464l.001-.001l.003-.002l.01-.006a2 2 0 0 1 .15-.077c.1-.048.241-.108.414-.163c.343-.11.823-.202 1.34-.11a.27.27 0 0 1-.093.533a2.3 2.3 0 0 0-1.082.092a3 3 0 0 0-.46.196");
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q8d1l4bok {
  stop-color: var(--svg-color--6d4f8c, #6D4F8C);
  stop-opacity: 0;
}

.qc_n6cavf {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.699 8.424l-.14.232za.271.271 0 0 1-.279.464l-.004-.002l-.022-.013l-.092-.046a3 3 0 0 0-.346-.136a2.3 2.3 0 0 0-1.082-.093a.27.27 0 0 1-.095-.534c.518-.091.998.001 1.341.11a3.3 3.3 0 0 1 .564.241l.01.006l.003.002z");
}

.qc07hnbjk {
  stop-color: var(--svg-color--fbf7ff, #FBF7FF);
}

.qc0o5_36v {
  stop-color: var(--svg-color--e0d6e3, #E0D6E3);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qnar36wle {
  r: 4.086px;
}

.qsd0a64ps {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.22 11.765a1.084 1.084 0 1 0 0-2.169a1.084 1.084 0 0 0 0 2.169");
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

.r7qt7msxe {
  fill: var(--svg-color--795cc2, #795CC2);
  d: path("M9.9 17.328c.641-1.312 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.816-3.68-8.741c-.42-1.004-.89-2.477-.297-3.86");
}

.r8td-ob5s {
  stop-color: var(--svg-color--f3ebfe, #F3EBFE);
}

.rfe2cabsc {
  d: path("M15.956 15.506h-.04c.1 0 .192 0 .293.01c-.081-.01-.172-.01-.253-.01");
}

.rh4-2jbhq {
  stop-color: var(--svg-color--4b3030, #4B3030);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.roh2cebgd {
  stop-color: var(--svg-color--6349aa, #6349AA);
}

.ruhbhkkus {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.805 11.765a1.084 1.084 0 1 0 0-2.169a1.084 1.084 0 0 0 0 2.169");
}

.rz_1qnb6a {
  stop-color: var(--svg-color--593d6e, #593D6E);
  stop-opacity: 0;
}

.s1sf7bc-d {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.36 6.46l-1.439.264a.695.695 0 1 1-.126-1.378h2.363c1.398 0 1.86 1.409 1.917 1.89a3.18 3.18 0 0 0-2.715-.777");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.snymmbrnj {
  stop-color: var(--svg-color--d5c4df, #D5C4DF);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sv9br1byn {
  stop-color: var(--svg-color--5e40aa, #5E40AA);
  stop-opacity: 0;
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.tbqxjbcmi {
  stop-color: var(--svg-color--614279, #614279);
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

.tyonxd6hb {
  cx: 8.275px;
  cy: 23.344px;
  r: 6.305px;
}

.u44j7rbwl {
  stop-color: var(--svg-color--7c60c4, #7C60C4);
  stop-opacity: 0;
}

.ujmzz-8fx {
  d: path("M10.795 9.406h.013l-.01-.268l-.011-.31c.02-.957.58-1.328.818-1.452l.052-.02q.028-.013.051-.02c.539-.248.973-.68 1.201-1.247l.083-.196a.266.266 0 0 1 .466-.051a3.9 3.9 0 0 0 3.22 1.689h3.25c.183 0 1.093.088 1.148 1.345l-.12 3.103c-.125 2.829-2.334 4.729-5.031 4.729s-4.907-1.9-5.032-4.73z");
}

.usevvd_vg {
  fill: var(--svg-color--000, #000);
  d: path("M17.62 10.497c0-.287.23-.516.516-.516a.514.514 0 0 1 .459.754h-.913a.47.47 0 0 1-.062-.238");
}

.ux1udsynf {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.93 13.62c-.525 0-1.02-.127-1.434-.348c-.142-.074-.295.09-.205.221a1.95 1.95 0 0 0 3.28 0c.09-.137-.063-.295-.205-.221a3.04 3.04 0 0 1-1.435.348Z");
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v6wds2dtn {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
}

.v9mvjzb1z {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.89 8.285c.325-.08 1.135-.04 1.676.348");
}

.vjc5s1b0i {
  stop-color: var(--svg-color--513f3e, #513F3E);
}

.vu75dna4z {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.535 10.456l-.69 1.716a.544.544 0 0 0 .525.706h.794a.546.546 0 0 0 .526-.706l-.537-1.716c-.115-.38-.498-.38-.618 0");
}

.vze8wny8i {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wcgf0-brn {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M10.813 4.635c.571-.606 1.652-.606 2.152-.516l.399 1.303c-.255-.04-.483.05-.674.237c-.453 1.272-2.009 1.974-2.73 2.166c-.15-1.506.11-2.403.853-3.19");
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wv2o2nbhk {
  stop-color: var(--svg-color--7a67ab, #7A67AB);
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x37sucbkr {
  stop-color: var(--svg-color--8870c8, #8870C8);
}

.x4p5bn7mz {
  stop-color: var(--svg-color--2c1c48, #2C1C48);
}

.x584qub8p {
  fill: var(--svg-color--e8d6ff, #E8D6FF);
  d: path("M1.97 23.992h3.298a5.94 5.94 0 0 1 5.937 5.938H1.971zm28.06 0h-3.298a5.937 5.937 0 0 0-5.937 5.938h9.234z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xmikh_b7g {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.778 10.106c-.268-.471-.675-.844-1.552-.844c-.384 0-.754.107-1.083.373c-.271.219-.235.5-.025.605l.562.32c.658-.213 1.385-.241 2.098-.454");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y-a_999zn {
  stop-color: var(--svg-color--7e64c5, #7E64C5);
  stop-opacity: 0;
}

.y41hsabjm {
  stop-color: var(--svg-color--704cc0, #704CC0);
}

.y6189wa3s {
  d: path("M14.01 15.39h4v1.99c.01.174.045.373.152.53a.8.8 0 0 0 .445.332l.465.164c.076.068.22.478.04.985c-.181.505-2.043 5.51-3.094 8.019v.02l-.005-.01q0 .004-.004.01v-.02c-1.052-2.51-3.186-7.515-3.366-8.02c-.182-.506-.076-.87 0-.937l.68-.191c.218-.063.373-.14.515-.348c.113-.165.158-.39.172-.572z");
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yo5rkx0ty {
  stroke: var(--svg-color--655554, #655554);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M16.145 18.313c.19.027.71.033 1.275-.163");
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z0qi4zb3s {
  stop-color: var(--svg-color--684c87, #684C87);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zantcf-1d {
  stop-color: var(--svg-color--775cbc, #775CBC);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.ztwx-ucga {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M15.93 13.62c-.525 0-1.02-.127-1.434-.348c-.142-.074-.295.09-.205.221a1.95 1.95 0 0 0 3.28 0c.09-.137-.063-.295-.205-.221a3.04 3.04 0 0 1-1.435.348");
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
