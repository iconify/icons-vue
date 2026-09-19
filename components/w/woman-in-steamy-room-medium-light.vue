<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iOokUYv)" class="r_bcr-ntk"/><circle fill="url(#ig6gRjd)" class="r_bcr-ntk"/><circle fill="url(#ifqCFkS)" class="iksuiqrgf"/><circle fill="url(#igczLIe)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iE9wJUA)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iiFjNse)" transform="matrix(-1 0 0 1 23.725 23.368)" class="n5l_opbqq"/><g filter="url(#iy3U4wV)"><path fill="url(#ix9JRqe)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iIc7xud)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iCOF7Vc)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iiKIdze)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iBlyIxe)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#izxgtRb)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iBBuReb)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iGMCo5W)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#iyRTvqc)" clip-rule="evenodd" class="xooo5lvln"/><path fill="url(#ic9q9cc)" clip-rule="evenodd" class="xooo5lvln"/></g><path fill="url(#i8FGQFb)" class="w8e9izb-y"/><path fill="url(#iMKMyJG)" class="w8e9izb-y"/><path fill="url(#iZv1BFd)" class="w8e9izb-y"/><path fill="url(#iZmEtZd)" class="rgs-6fbpw"/><path fill="url(#iecyoYd)" class="rgs-6fbpw"/><path class="rw7u0kjxx"/><path fill="url(#iG5HNEd)" class="gt-y46nru"/><path fill="url(#iTiy4Yb)" class="gt-y46nru"/><path fill="url(#ivTeyXa)" class="gt-y46nru"/><path fill="url(#itptivw)" class="gt-y46nru"/><path fill="url(#im05I4b)" class="gt-y46nru"/><path fill="url(#iP7Xdge)" class="gt-y46nru"/><path class="qujrzvqgg"/><path fill="url(#iZUlthd)" class="zzsb9xb8w"/><path fill="url(#iwNqoRc)" class="zzsb9xb8w"/><path fill="url(#iE18CIh)" class="zzsb9xb8w"/><g filter="url(#iIIePmd)"><path fill="url(#iapbyyc)" class="h-i2t2w9q"/><path fill="url(#iqlT8bb)" class="h-i2t2w9q"/><path fill="url(#iOvx8Xb)" class="h-i2t2w9q"/></g><path class="wkmk90b2p"/><g filter="url(#iMS0kGs)"><path class="cltrgwbqp"/></g><path fill="url(#ialH3pb)" class="zosz72acb"/><path fill="url(#iGusNfb)" class="ytvm2kbdn"/><g filter="url(#iB1Pruc)"><path fill="url(#iTc89rb)" class="b787bwb8q"/></g><g filter="url(#id2GPFd)"><path fill="url(#iQXkhYb)" class="t_z9a_1_e"/><path fill="url(#iORHKhd)" class="t_z9a_1_e"/></g><g filter="url(#i6reDQe)"><path class="ywntirb0t"/><path fill="url(#izWTWAc)" class="fqthm3lid"/></g><g filter="url(#iWIU59B)"><path class="hx28jmuyp"/><path fill="url(#iNZ2TVC)" class="nj9ng6b5g"/></g><g filter="url(#ig8Eu6d)"><path fill="url(#ixztbre)" class="tbhraqbpn"/><path fill="url(#iZLGhjb)" class="tbhraqbpn"/><path fill="url(#idGh70b)" class="tbhraqbpn"/><path fill="url(#iQ59lcb)" class="tbhraqbpn"/><path fill="url(#i0FzBIf)" class="tbhraqbpn"/><path fill="url(#iFOQvub)" class="tbhraqbpn"/><path fill="url(#ixnHMie)" class="tbhraqbpn"/></g><path fill="url(#igTxufc)" class="hy3hk-bua"/><path fill="url(#i9Apgsb)" class="hy3hk-bua"/><g filter="url(#iBhG0wu)"><path class="w7-b5yb2r"/></g><g filter="url(#iG1glPU)"><path class="w5sd-_b9c"/><path fill="url(#ibuFlob)" class="iq462cb3g"/><path fill="url(#iyP70tc)" class="iq462cb3g"/><path fill="url(#i7NHj4L)" class="iq462cb3g"/></g><g filter="url(#itNYpme)"><path stroke="url(#iuUBGOb)" class="z374e_6sn"/></g><path class="t5z_7dbfr"/><g filter="url(#iM2iJee)"><path class="cienxd__m"/></g><g filter="url(#iCljDPb)"><path class="uwmu3cc9g"/></g><g filter="url(#iER766V)"><path class="xzz55zd1w"/></g><g filter="url(#i4uPg4d)"><path clip-rule="evenodd" class="d_nl_80dp"/></g><path class="c4j9xf4yf"/><path fill="url(#i6P4wgb)" class="g1lqsxc9b"/><path class="ucnajwbxu"/><g filter="url(#ihf1oOe)"><path class="n2ia63biy"/><path fill="url(#iIM36fm)" class="choqsb0vk"/></g><g filter="url(#iXmIsVc)"><path fill="url(#ilsyuIb)" class="s4fsmlbta"/></g><path class="grgmmmbpj"/><path fill="url(#ibtK0pb)" class="ho1vz9bmx"/><path class="wyw_zsaao"/><g filter="url(#inONDGe)"><path fill="url(#iEnZNnZ)" class="g10-b8nzg"/></g><g filter="url(#ikCtGgd)"><ellipse transform="rotate(-27.914 13.446 9.982)" class="h84badbaf"/><ellipse fill="url(#itaGpVc)" transform="rotate(-27.914 13.446 9.982)" class="t9qyh6bmf"/></g><g filter="url(#iEnHI2d)"><path class="xselxsm5r"/></g><g filter="url(#iDKDxCd)"><path class="vrmj7bc_a"/></g><g filter="url(#iIuFDAb)"><path fill="url(#iNisxOd)" class="mp0hp9eei"/><path fill="url(#i64qfZc)" class="mp0hp9eei"/></g><g filter="url(#isyQKAb)"><path fill="url(#i8hjxWc)" class="ee-_iybad"/><path fill="url(#i9oyqTc)" class="ee-_iybad"/><path fill="url(#i4J1oab)" class="ee-_iybad"/></g><g filter="url(#ifxbVvd)"><path stroke="url(#iVhSoBc)" class="rzjfiqxaf"/></g><defs><radialGradient id="iOokUYv" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -2.4375 2.72822 4.02238 6.877 17.33)" gradientUnits="userSpaceOnUse"><stop class="dgu6o60tg"/><stop offset="1" class="n_p-4bbbu"/></radialGradient><radialGradient id="ig6gRjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 -1.76562 2.48224 -.02197 8.596 17.83)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="v6wds2dtn"/><stop offset="1" class="nz8ufunsm"/></radialGradient><radialGradient id="ifqCFkS" cx="0" cy="0" r="1" gradientTransform="matrix(-5.47138 9.4622 -7.02133 -4.05998 10.46 19.268)" gradientUnits="userSpaceOnUse"><stop class="qc0o5_36v"/><stop offset="1" class="snymmbrnj"/></radialGradient><radialGradient id="igczLIe" cx="0" cy="0" r="1" gradientTransform="rotate(44.444 -1.585 1.225)scale(4.68833)" gradientUnits="userSpaceOnUse"><stop class="qc07hnbjk"/><stop offset=".836" class="b_5radckw"/></radialGradient><radialGradient id="iE9wJUA" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.59375 5.11385 -.10027 2.316 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vze8wny8i"/><stop offset="1" class="o4sg_vbnc"/></radialGradient><radialGradient id="iiFjNse" cx="0" cy="0" r="1" gradientTransform="matrix(4.95236 7.33803 -10.65664 7.19205 1.352 1.24)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="r8td-ob5s"/><stop offset=".819" class="eegxz98yy"/></radialGradient><radialGradient id="iIc7xud" cx="0" cy="0" r="1" gradientTransform="matrix(1.76567 -3.66716 8.36137 4.02584 20.685 16.578)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iCOF7Vc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9128 5.53194 -5.17824 -1.7905 15.252 12.47)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iiKIdze" cx="0" cy="0" r="1" gradientTransform="matrix(-3.19177 2.47874 -3.0512 -3.9289 12.773 13.489)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iBlyIxe" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.675 8.321)scale(1.80399 1.63975)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="izxgtRb" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.302 4.061)scale(2.41786 3.55427)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iBBuReb" cx="0" cy="0" r="1" gradientTransform="matrix(2.19018 3.20876 -5.59973 3.82217 12.044 3.014)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="iGMCo5W" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.68 7.16)scale(1.65825 2.31738)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iyRTvqc" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.069 6.588)scale(1.94487 4.23178)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="ic9q9cc" cx="0" cy="0" r="1" gradientTransform="rotate(156.949 10.344 8.692)scale(3.46875 5.52677)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="i8FGQFb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35939 5.78125 -6.81223 -1.6018 23.096 22.58)" gradientUnits="userSpaceOnUse"><stop class="ttp7yqb-m"/><stop offset="1" class="jletv-brl"/></radialGradient><radialGradient id="iZmEtZd" cx="0" cy="0" r="1" gradientTransform="matrix(6.87457 8.07189 -11.19707 9.5362 6.418 22.32)" gradientUnits="userSpaceOnUse"><stop class="wv2o2nbhk"/><stop offset="1" class="n44b27bdp"/></radialGradient><radialGradient id="iG5HNEd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.03127 -6.31539 -6.64086 13.752 16.392)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="epu6iq_fg"/><stop offset="1" class="q8d1l4bok"/></radialGradient><radialGradient id="ivTeyXa" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82764 -11.66358 1.58185 -.65474 15.958 28.962)" gradientUnits="userSpaceOnUse"><stop class="x37sucbkr"/><stop offset="1" class="k796fybnd"/></radialGradient><radialGradient id="im05I4b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37282 -3.155 .92095 -.40073 16.346 27.58)" gradientUnits="userSpaceOnUse"><stop class="bp-uy2zsn"/><stop offset="1" class="dfpk_zbbl"/></radialGradient><radialGradient id="iP7Xdge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15863 -1.17796 1.62432 -1.59766 14.336 18.515)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="jhdqd89ez"/><stop offset="1" class="tbqxjbcmi"/></radialGradient><radialGradient id="iwNqoRc" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.67188 .83418 2.50254 17.502 18.33)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="x4p5bn7mz"/><stop offset="1" class="rz_1qnb6a"/></radialGradient><radialGradient id="iE18CIh" cx="0" cy="0" r="1" gradientTransform="rotate(110.875 2.49 18.294)scale(11.8396 2.00952)" gradientUnits="userSpaceOnUse"><stop class="tqo-vnfob"/><stop offset="1" class="fqnn-rb2e"/></radialGradient><radialGradient id="iqlT8bb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.92625 -2.40786 2.26568 13.158 16.172)" gradientUnits="userSpaceOnUse"><stop offset=".047" class="ps_f7cbop"/><stop offset="1" class="dggv0hbyd"/></radialGradient><radialGradient id="iOvx8Xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.31547 -.76307 0 16.64 15.09)" gradientUnits="userSpaceOnUse"><stop class="nxgp0pbvn"/><stop offset="1" class="qc1uy5bzw"/><stop offset="1" class="qc1uy5bzw"/></radialGradient><radialGradient id="iQXkhYb" cx="0" cy="0" r="1" gradientTransform="matrix(2.52117 -1.14599 1.3992 3.07823 20.023 11.129)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iORHKhd" cx="0" cy="0" r="1" gradientTransform="matrix(1.01017 .28862 -.15174 .53108 21.058 8.88)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="izWTWAc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.807 -52.03)scale(1.32142)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iNZ2TVC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23256 0 0 -1.17902 11.204 10.684)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="ixztbre" cx="0" cy="0" r="1" gradientTransform="matrix(-6.58749 3.03771 -4.06593 -8.81724 18.827 10.14)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iZLGhjb" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 7.582 7.639)scale(2.41748 2.05106)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="idGh70b" cx="0" cy="0" r="1" gradientTransform="matrix(.84772 -4.09732 5.19875 1.0756 13.723 17.01)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iQ59lcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.53347 -10.2121 0 15.931 9.848)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sgt5sn5oc"/><stop offset="1" class="gxm-dc6uw"/></radialGradient><radialGradient id="i0FzBIf" cx="0" cy="0" r="1" gradientTransform="matrix(-5.80634 .78092 -1.3445 -9.9967 16.576 12.504)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iFOQvub" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16562 1.67571 0 18.262 9.715)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="ixnHMie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37755 1.57876 0 13.988 9.804)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="igTxufc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.36433 0 0 -4.49142 21.092 11.222)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="i9Apgsb" cx="0" cy="0" r="1" gradientTransform="rotate(74.673 3.709 11.064)scale(4.43077 9.15597)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="ibuFlob" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 12.877 -.335)scale(2.57996 1.47628)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="i6P4wgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82178 -1.30714 0 18.141 10.08)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iIM36fm" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.444 .696)scale(.38317 .52752)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibtK0pb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82179 -1.30715 0 13.721 10.079)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="itaGpVc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.786 -1.46)scale(.5005 .60161)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNisxOd" cx="0" cy="0" r="1" gradientTransform="matrix(1.95983 2.71641 -5.39751 3.89418 9.897 4.355)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="i64qfZc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90157 2.51269 -1.9706 -1.49133 13.18 4.592)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="i8hjxWc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1392 4.44812 -6.32503 -3.04186 17.867 2.657)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="i9oyqTc" cx="0" cy="0" r="1" gradientTransform="rotate(104.957 7.66 8.94)scale(3.36253 6.0022)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="i4J1oab" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.378 -.38)scale(7.3035 6.53768)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><filter id="iy3U4wV" width="15.462" height="15.962" x="8.325" y="1.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_789"/></filter><filter id="iIIePmd" width="6.906" height="12.039" x="12.293" y="15.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.458824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_789"/></filter><filter id="iMS0kGs" width="3.076" height="1.977" x="15.245" y="17.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".3"/></filter><filter id="iB1Pruc" width="3.41" height="3.51" x="9.555" y="9.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_789"/></filter><filter id="id2GPFd" width="3.26" height="3.51" x="19.191" y="8.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_789"/></filter><filter id="i6reDQe" width="3.176" height="3.176" x="19.233" y="9.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".25"/></filter><filter id="iWIU59B" width="2.976" height="2.976" x="9.716" y="9.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".2"/></filter><filter id="ig8Eu6d" width="10.322" height="11.267" x="10.77" y="5.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_789"/></filter><filter id="iBhG0wu" width="2.901" height="3.716" x="14.316" y="9.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".25"/></filter><filter id="iG1glPU" width="2.401" height="3.216" x="14.73" y="9.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".125"/></filter><filter id="itNYpme" width="3.745" height="1.54" x="14.059" y="13.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".05"/></filter><filter id="iM2iJee" width="3.038" height="1.302" x="16.888" y="9.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_789"/></filter><filter id="iCljDPb" width="3.038" height="1.302" x="11.937" y="9.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_789"/></filter><filter id="iER766V" width="2.482" height="1.102" x="12.074" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_789"/></filter><filter id="i4uPg4d" width="2.482" height="1.103" x="17.561" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_789"/></filter><filter id="ihf1oOe" width=".794" height=".703" x="17.399" y="9.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".05"/></filter><filter id="iXmIsVc" width=".898" height=".92" x="18.251" y="9.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".1"/></filter><filter id="inONDGe" width=".994" height="1.048" x="13.751" y="9.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".1"/></filter><filter id="ikCtGgd" width=".922" height=".711" x="12.985" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".05"/></filter><filter id="iEnHI2d" width="2.282" height=".983" x="17.596" y="7.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".1"/></filter><filter id="iDKDxCd" width="2.282" height=".983" x="12.074" y="7.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".1"/></filter><filter id="iIuFDAb" width="4.33" height="5.305" x="9.597" y="3.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".25"/></filter><filter id="isyQKAb" width="9.023" height="5.848" x="12.575" y="2.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".125"/></filter><filter id="ifxbVvd" width="1.152" height="2.332" x="12.703" y="3.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_789" stdDeviation=".1"/></filter><linearGradient id="ix9JRqe" x1="20.685" x2="13.792" y1="3.642" y2="16.409" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iMKMyJG" x1="24.158" x2="24.189" y1="30.329" y2="26.673" gradientUnits="userSpaceOnUse"><stop offset=".078" class="y41hsabjm"/><stop offset="1" class="y-a_999zn"/></linearGradient><linearGradient id="iZv1BFd" x1="18.12" x2="19.472" y1="27.765" y2="28.151" gradientUnits="userSpaceOnUse"><stop class="mbuex5b5r"/><stop offset="1" class="ozroxmy8l"/></linearGradient><linearGradient id="iecyoYd" x1="13.658" x2="12.158" y1="28.736" y2="29.267" gradientUnits="userSpaceOnUse"><stop class="g82zxu-vf"/><stop offset="1" class="sv9br1byn"/></linearGradient><linearGradient id="iTiy4Yb" x1="12.315" x2="13.69" y1="27.392" y2="26.829" gradientUnits="userSpaceOnUse"><stop offset=".223" class="zantcf-1d"/><stop offset="1" class="tkat5cdin"/></linearGradient><linearGradient id="itptivw" x1="15.627" x2="14.221" y1="30.173" y2="29.486" gradientUnits="userSpaceOnUse"><stop offset=".208" class="roh2cebgd"/><stop offset="1" class="u44j7rbwl"/></linearGradient><linearGradient id="iZUlthd" x1="16.002" x2="18.033" y1="24.829" y2="25.736" gradientUnits="userSpaceOnUse"><stop class="z0qi4zb3s"/><stop offset="1" class="nh4l3fbho"/></linearGradient><linearGradient id="iapbyyc" x1="16.366" x2="16.366" y1="24.913" y2="14.427" gradientUnits="userSpaceOnUse"><stop class="kqw3-db6l"/><stop offset="1" class="mnloc2nlg"/></linearGradient><linearGradient id="ialH3pb" x1="8.677" x2="23.191" y1="15.561" y2="15.561" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iGusNfb" x1="8.677" x2="23.191" y1="15.53" y2="15.53" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iTc89rb" x1="9.555" x2="12.553" y1="10.772" y2="10.772" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iyP70tc" x1="14.871" x2="15.737" y1="11.976" y2="12.082" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="i7NHj4L" x1="15.931" x2="15.931" y1="12.841" y2="12.223" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iuUBGOb" x1="15.193" x2="15.651" y1="14.337" y2="13.454" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="ilsyuIb" x1="18.929" x2="18.611" y1="10.134" y2="10.329" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEnZNnZ" x1="14.474" x2="14.157" y1="10.134" y2="10.329" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVhSoBc" x1="13.003" x2="13.555" y1="4.405" y2="5.696" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-steamy-room-medium-light" /></template>
<style>
.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.b_5radckw {
  stop-color: var(--svg-color--f2e8f1, #F2E8F1);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b787bwb8q {
  d: path("M11.185 12.314a1.63 1.63 0 1 0 0-3.26a1.63 1.63 0 0 0 0 3.26");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bp-uy2zsn {
  stop-color: var(--svg-color--442d6d, #442D6D);
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c4j9xf4yf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.353 9.32c.662 0 1.22.457 1.372 1.073a.278.278 0 0 1-.27.345h-2.26a.233.233 0 0 1-.23-.275a1.416 1.416 0 0 1 1.388-1.142");
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.choqsb0vk {
  d: path("M18.077 9.787c.064.086-.07.191-.223.305c-.153.115-.267.195-.331.11c-.065-.087.007-.25.16-.364s.33-.137.394-.051");
}

.cienxd__m {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.088 10.107c.269-.473.677-.846 1.557-.846c.385 0 .757.107 1.087.373c.272.22.236.502.025.607l-.563.322c-.66-.213-1.39-.242-2.106-.456");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cltrgwbqp {
  stroke: var(--svg-color--e7b39a, #E7B39A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M16.145 18.338c.19.027.71.032 1.275-.163");
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.d_nl_80dp {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m19.71 8.42l-.139.233za.272.272 0 0 1-.279.466l-.005-.003a1 1 0 0 0-.114-.059a3 3 0 0 0-.347-.137a2.3 2.3 0 0 0-1.086-.093a.272.272 0 0 1-.095-.535a2.84 2.84 0 0 1 1.346.11a3.3 3.3 0 0 1 .566.242l.01.006l.002.002z");
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.dfpk_zbbl {
  stop-color: var(--svg-color--7c5fac, #7C5FAC);
  stop-opacity: 0;
}

.dggv0hbyd {
  stop-color: var(--svg-color--c38266, #C38266);
  stop-opacity: 0;
}

.dgu6o60tg {
  stop-color: var(--svg-color--e1dae6, #E1DAE6);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.ee-_iybad {
  d: path("M15.32 2.793c-1.147-.254-2.377.967-2.495 1.392c1.561 3.667 3.96 3.317 6.62 3.022c1.594-.177 1.766.549 1.902.9c-.441-4.109-3.412-4.737-6.027-5.314");
}

.eegxz98yy {
  stop-color: var(--svg-color--dac9f0, #DAC9F0);
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epu6iq_fg {
  stop-color: var(--svg-color--4f3466, #4F3466);
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.fqnn-rb2e {
  stop-color: var(--svg-color--7b63b3, #7B63B3);
  stop-opacity: 0;
}

.fqthm3lid {
  d: path("M20.82 11.772a1.088 1.088 0 1 0 0-2.176a1.088 1.088 0 0 0 0 2.176");
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g10-b8nzg {
  d: path("M14.545 10.394c0-.293-.238-.487-.302-.546l-.292.282l.18.366z");
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g1lqsxc9b {
  d: path("M18.143 9.596a.904.904 0 0 1 .872 1.142h-1.747a.907.907 0 0 1 .875-1.142");
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.g82zxu-vf {
  stop-color: var(--svg-color--5e40aa, #5E40AA);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.grgmmmbpj {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.51 9.32c-.662 0-1.221.457-1.373 1.073a.278.278 0 0 0 .271.345h2.26a.233.233 0 0 0 .23-.275A1.42 1.42 0 0 0 13.51 9.32");
}

.gt-y46nru {
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gxm-dc6uw {
  stop-color: var(--svg-color--a46e69, #A46E69);
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

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.ho1vz9bmx {
  d: path("M13.719 9.596a.904.904 0 0 0-.871 1.142h1.746a1 1 0 0 0 .033-.238a.91.91 0 0 0-.908-.904");
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hx28jmuyp {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.204 11.772a1.088 1.088 0 1 0 0-2.176a1.088 1.088 0 0 0 0 2.176");
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.hy3hk-bua {
  d: path("M10.778 9.405h.013l-.01-.269l-.011-.31c.02-.961.582-1.333.82-1.457l.053-.02q.028-.014.051-.021c.54-.248.977-.683 1.205-1.251l.084-.196a.267.267 0 0 1 .467-.052a3.91 3.91 0 0 0 3.23 1.695h3.262c.182 0 1.096.088 1.15 1.35l-.12 3.112c-.125 2.839-2.341 4.745-5.047 4.745s-4.923-1.906-5.048-4.745z");
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.iksuiqrgf {
  cx: 8.275px;
  cy: 23.368px;
  r: 6.305px;
}

.iq462cb3g {
  d: path("m15.544 10.318l-.538 1.722a.546.546 0 0 0 .527.708h.797c.373 0 .637-.36.527-.708l-.538-1.722c-.116-.382-.654-.382-.775 0");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jhdqd89ez {
  stop-color: var(--svg-color--342554, #342554);
}

.jletv-brl {
  stop-color: var(--svg-color--8067c6, #8067C6);
}

.k796fybnd {
  stop-color: var(--svg-color--8870c8, #8870C8);
  stop-opacity: 0;
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.kqw3-db6l {
  stop-color: var(--svg-color--dea48a, #DEA48A);
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbuex5b5r {
  stop-color: var(--svg-color--6b47bb, #6B47BB);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mnloc2nlg {
  stop-color: var(--svg-color--e6ae8a, #E6AE8A);
}

.mp0hp9eei {
  d: path("M10.974 4.592c.629-.56 1.536-.566 2.046-.475l.407 1.307c-.26-.04-.492.051-.688.238c-.458 1.698-2.19 1.443-2.53 2.716c-.152-1.51-.322-2.818.765-3.786");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n_p-4bbbu {
  stop-color: var(--svg-color--e6dee6, #E6DEE6);
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

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nxgp0pbvn {
  stop-color: var(--svg-color--e2aa93, #E2AA93);
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

.ozroxmy8l {
  stop-color: var(--svg-color--6b47bb, #6B47BB);
  stop-opacity: 0;
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.ps_f7cbop {
  stop-color: var(--svg-color--ab5e45, #AB5E45);
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
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

.qc1uy5bzw {
  stop-color: var(--svg-color--e2aa93, #E2AA93);
  stop-opacity: 0;
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qnar36wle {
  r: 4.086px;
}

.qujrzvqgg {
  fill: var(--svg-color--7a60bc, #7A60BC);
  d: path("M21.82 17.353c-.642-1.313-1.821-1.75-2.595-1.75h-2.609v2.875h2.47c.168.303.002.85-.102 1.086l-3.94 10.39h3.177c1.067-2.583 2.995-7.817 3.383-8.742c.42-1.004.809-2.476.215-3.86");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_bcr-ntk {
  cx: 10.674px;
  cy: 16.165px;
  r: 4.086px;
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r8td-ob5s {
  stop-color: var(--svg-color--f3ebfe, #F3EBFE);
}

.rgs-6fbpw {
  d: path("M5.096 29.939c0-7.961 4.617-9.875 5.375-10.383l5.047 10.383z");
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
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

.s4fsmlbta {
  d: path("M18.949 10.38a.85.85 0 0 0-.235-.468l-.263.289l.119.231z");
}

.sgt5sn5oc {
  stop-color: var(--svg-color--bd8381, #BD8381);
  stop-opacity: 0;
}

.snymmbrnj {
  stop-color: var(--svg-color--d5c4df, #D5C4DF);
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.sv9br1byn {
  stop-color: var(--svg-color--5e40aa, #5E40AA);
  stop-opacity: 0;
}

.t_z9a_1_e {
  d: path("M20.82 12.314a1.63 1.63 0 1 0 0-3.26a1.63 1.63 0 0 0 0 3.26");
}

.t5z_7dbfr {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M15.931 13.633a3.1 3.1 0 0 1-1.44-.35c-.142-.073-.295.09-.205.223a1.957 1.957 0 0 0 3.29 0c.09-.138-.062-.296-.205-.222a3.05 3.05 0 0 1-1.44.349");
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.t9qyh6bmf {
  cx: 13.446px;
  cy: 9.982px;
  rx: 0.395px;
  ry: 0.2px;
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tbhraqbpn {
  d: path("m10.78 9.136l-.01-.31c.02-.961.582-1.333.82-1.457l.053-.02q.028-.014.051-.021c.54-.248.977-.683 1.205-1.251l.084-.196a.267.267 0 0 1 .467-.052a3.91 3.91 0 0 0 3.23 1.695h3.262c.182 0 1.096.088 1.15 1.35l-.12 3.112c-.125 2.839-2.341 4.745-5.047 4.745s-4.923-1.906-5.048-4.745z");
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

.ttp7yqb-m {
  stop-color: var(--svg-color--9279d5, #9279D5);
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.u44j7rbwl {
  stop-color: var(--svg-color--7c60c4, #7C60C4);
  stop-opacity: 0;
}

.ucnajwbxu {
  fill: var(--svg-color--000, #000);
  d: path("M17.626 10.5c0-.288.23-.518.517-.518a.516.516 0 0 1 .46.756h-.916a.47.47 0 0 1-.061-.238");
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uwmu3cc9g {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.775 10.107c-.27-.473-.678-.846-1.558-.846a1.68 1.68 0 0 0-1.086.373c-.273.22-.236.502-.025.607l.563.322c.66-.213 1.39-.242 2.106-.456");
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6wds2dtn {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
}

.vrmj7bc_a {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.056 8.28c-.327-.079-1.14-.04-1.682.35");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vze8wny8i {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w5sd-_b9c {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.544 10.318l-.538 1.722a.546.546 0 0 0 .527.708h.797c.373 0 .637-.36.527-.708l-.538-1.722c-.116-.382-.654-.382-.775 0");
}

.w7-b5yb2r {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.534 10.458l-.693 1.722a.546.546 0 0 0 .528.709h.796c.374 0 .637-.36.527-.709l-.538-1.722c-.115-.381-.5-.381-.62 0");
}

.w8e9izb-y {
  d: path("M26.947 29.939c0-7.961-4.617-9.875-5.375-10.383l-5.047 10.383z");
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wkmk90b2p {
  fill: var(--svg-color--e8d6ff, #E8D6FF);
  d: path("M1.97 24.017h3.298a5.94 5.94 0 0 1 5.937 5.937H1.971zm28.06 0h-3.298a5.94 5.94 0 0 0-5.937 5.937h9.234z");
  opacity: var(--svg-opacity--0-5, 0.5);
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

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xooo5lvln {
  fill-rule: evenodd;
  d: path("M23.21 12.112c.214-.441.327-.933.327-1.446a3.3 3.3 0 0 0-.272-1.322h.005a3 3 0 0 0-.284-.52l-.002-.003a3.3 3.3 0 0 1-.534-1.794v-.01a3.34 3.34 0 0 0-3.341-3.342a.55.55 0 0 1-.461-.235a3.35 3.35 0 0 0-2.717-1.394a3.35 3.35 0 0 0-2.716 1.394a.57.57 0 0 1-.462.236h-.086a3.34 3.34 0 0 0-3.255 3.341v.01c0 .636-.185 1.261-.533 1.794l-.003.004a3.34 3.34 0 0 0-.223 3.287a.52.52 0 0 1 0 .461c-.205.43-.328.912-.328 1.425a3.255 3.255 0 0 0 3.26 3.26h8.692a3.255 3.255 0 0 0 3.26-3.26c0-.513-.123-.994-.328-1.425a.52.52 0 0 1 0-.461M10.79 9.405h-.012l1.214 2.386c.125 2.839 1.233 0 3.939 0s3.886 3.16 4.01.32l1.151-3.238c-.054-1.26-.968-1.349-1.15-1.349H16.68a3.91 3.91 0 0 1-3.23-1.695a.267.267 0 0 0-.468.052l-.083.196a2.33 2.33 0 0 1-1.205 1.25l-.052.021q-.028.013-.051.021c-.24.124-.8.496-.821 1.457l.01.31z");
}

.xselxsm5r {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.896 8.28c.326-.079 1.139-.04 1.682.35");
}

.xzz55zd1w {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.49 8.883l-.005.003a.272.272 0 0 1-.279-.466l.002-.001l.003-.002l.01-.006a2 2 0 0 1 .15-.077c.1-.048.242-.109.415-.164a2.84 2.84 0 0 1 1.345-.11a.272.272 0 1 1-.094.534a2.3 2.3 0 0 0-1.086.093a3 3 0 0 0-.461.196");
}

.y-a_999zn {
  stop-color: var(--svg-color--7e64c5, #7E64C5);
  stop-opacity: 0;
}

.y41hsabjm {
  stop-color: var(--svg-color--704cc0, #704CC0);
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.ytvm2kbdn {
  d: path("M15.956 15.531h-.04c.1 0 .192 0 .293.01c-.081-.01-.172-.01-.253-.01");
}

.ywntirb0t {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.82 11.772a1.088 1.088 0 1 0 0-2.176a1.088 1.088 0 0 0 0 2.176");
}

.z0qi4zb3s {
  stop-color: var(--svg-color--684c87, #684C87);
}

.z374e_6sn {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.931 13.633a3.1 3.1 0 0 1-1.44-.35c-.142-.073-.295.09-.205.223a1.957 1.957 0 0 0 3.29 0c.09-.138-.062-.296-.205-.222a3.05 3.05 0 0 1-1.44.349Z");
}

.zantcf-1d {
  stop-color: var(--svg-color--775cbc, #775CBC);
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zosz72acb {
  d: path("M16.29 15.531c.252.01.514.03.777.05c-.263-.02-.515-.04-.778-.05");
}

.zzsb9xb8w {
  d: path("M21.82 17.353c-.642-1.313-1.821-1.75-2.595-1.75h-2.609v2.875h2.47c.168.303.002.85-.102 1.086l-3.94 10.39h3.177c1.067-2.583 2.995-7.817 3.383-8.742c.42-1.004.809-2.476.215-3.86");
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
