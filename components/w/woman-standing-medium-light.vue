<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9LOVxK)"><path fill="url(#i6CG6nb)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iRLxwuc)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iBsaH4d)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iMgfodb)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iGkLI2c)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iPov8Fb)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iAntyUd)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iEUlLQd)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iar8npe)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iwj4WHc)" clip-rule="evenodd" class="zm9zkcl5b"/></g><path class="fg7h3c35y"/><path fill="url(#iRZvL5b)" class="uj1jiacmd"/><g filter="url(#ipEumwe)"><path class="zizok7rsa"/><path fill="url(#iDLK1eb)" class="o_hp5nbjg"/></g><path class="nmunwx3pv"/><path fill="url(#iTndpme)" class="o93ji_bej"/><path fill="url(#i5T6iCd)" class="o93ji_bej"/><g filter="url(#iZ1BaEb)"><path class="oljgxubcv"/></g><path class="pu1qalb0n"/><path fill="url(#ieyaRhd)" class="pcr8w9bct"/><path fill="url(#i9fb3ne)" class="pcr8w9bct"/><path fill="url(#iek6ihd)" class="pcr8w9bct"/><path fill="url(#izgSJzU)" class="pcr8w9bct"/><path class="myif5tbjr"/><path fill="url(#iNC83fb)" class="u1ssmd66p"/><path fill="url(#iBwD5cu)" class="u1ssmd66p"/><g filter="url(#iheGZpk)"><path class="xqme1t_en"/></g><path fill="url(#icWbAmd)" class="cge-036tr"/><path fill="url(#iJO9Dac)" class="cge-036tr"/><path fill="url(#iApyzzd)" class="cge-036tr"/><path fill="url(#ivzWvsb)" class="cge-036tr"/><g filter="url(#iTLO7qb)"><path fill="url(#iCEVb2b)" class="qr3eebgfz"/><path fill="url(#iS5fSJc)" class="qr3eebgfz"/></g><path fill="url(#iO1McLA)" class="qr3eebgfz"/><path fill="url(#iIFRdJe)" class="qr3eebgfz"/><path fill="url(#in5jdqp)" class="i0vp1so6w"/><path fill="url(#ipSNgvY)" class="i0vp1so6w"/><g filter="url(#ixhvjCc)"><path class="ise8hkbqb"/></g><path fill="url(#iiFwxIb)" class="ukvj5-vlj"/><path fill="url(#iNo9Upb)" class="ukvj5-vlj"/><g filter="url(#ikBJthd)"><path class="hm4ptbkef"/></g><path fill="url(#imXX7Fy)" class="r7p4z7bsm"/><path fill="url(#iFVyysb)" class="d8xf2ibmq"/><g filter="url(#igCFqmc)"><path fill="url(#inQdEHC)" class="qrmj1y8xw"/></g><g filter="url(#iQKwSvM)"><path fill="url(#iQkvjze)" class="ymsp3kbav"/><path fill="url(#iyuA1we)" class="ymsp3kbav"/></g><g filter="url(#ixDwYXp)"><path class="rdil0mgdd"/><path fill="url(#i2k70yd)" class="ojwkb-b4s"/></g><g filter="url(#i4TA2xd)"><path class="posvnzbmj"/><path fill="url(#i0FpKlc)" class="zjcs0bbar"/></g><g filter="url(#ivYvwWc)"><path fill="url(#iVKM2hc)" class="q6kh5xjeh"/><path fill="url(#iWI1Luc)" class="q6kh5xjeh"/><path fill="url(#iDIDddb)" class="q6kh5xjeh"/><path fill="url(#i6vzqze)" class="q6kh5xjeh"/><path fill="url(#i24HTEe)" class="q6kh5xjeh"/><path fill="url(#izfN6qc)" class="q6kh5xjeh"/><path fill="url(#im2FVAd)" class="q6kh5xjeh"/></g><path fill="url(#ima7WQd)" class="j1j51bc4m"/><path fill="url(#iBhpxgd)" class="j1j51bc4m"/><g filter="url(#i4fYcbe)"><path class="e69c9iqaq"/></g><g filter="url(#iOqqpob)"><path class="gdmddpdka"/><path fill="url(#iZgglIb)" class="xc4tawbvb"/><path fill="url(#iLhwosb)" class="xc4tawbvb"/><path fill="url(#ifkfGid)" class="xc4tawbvb"/></g><g filter="url(#iDa38SE)"><path stroke="url(#i6etODR)" class="vok70cb_d"/></g><path class="bcnnx6b_s"/><g filter="url(#i8FNSUb)"><path class="f7r_gn4es"/></g><g filter="url(#iUV3X9b)"><path class="f3fwesbvc"/></g><g filter="url(#ipMPAwe)"><path class="ehwsee08x"/></g><g filter="url(#inKBXDz)"><path clip-rule="evenodd" class="usg2e3xpf"/></g><path class="nv-tm3b_c"/><path fill="url(#i47knQe)" class="r0w13r7uj"/><path class="umgvlrbgn"/><g filter="url(#iM8Icab)"><path class="bmuzas5gv"/><path fill="url(#iSxL7AH)" class="ffhuevyci"/></g><g filter="url(#iI0YFYJ)"><path fill="url(#iGh2oyc)" class="vy3y1vbex"/></g><path class="hil4-np7l"/><path fill="url(#iOj68Lb)" class="t_70vht6h"/><path class="q3bc6bbmg"/><g filter="url(#ixyCMPm)"><path fill="url(#icnlnye)" class="tkifgyigj"/></g><g filter="url(#iZqYDgd)"><ellipse transform="rotate(-27.914 14.922 5.528)" class="u-feptipi"/><ellipse fill="url(#i8RfYrc)" transform="rotate(-27.914 14.922 5.528)" class="bmn6q0bjm"/></g><g filter="url(#i66BeCd)"><path fill="url(#izJuEQe)" class="rpcnqk_9o"/><path fill="url(#i3hTFLb)" class="rpcnqk_9o"/></g><g filter="url(#i0nZjld)"><path fill="url(#iEpHCJb)" class="aur7g7hae"/><path fill="url(#iyevGse)" class="aur7g7hae"/><path fill="url(#iN6J9td)" class="aur7g7hae"/></g><defs><radialGradient id="iRLxwuc" cx="0" cy="0" r="1" gradientTransform="matrix(.7657 -1.5903 3.626 1.74584 18.062 8.389)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iBsaH4d" cx="0" cy="0" r="1" gradientTransform="matrix(-.8295 2.39898 -2.2456 -.77647 15.706 6.607)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iMgfodb" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 6.108 6.031)scale(1.75252 2.15726)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iGkLI2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.44915 .64054 -.58222 -.40825 13.872 5.93)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iPov8Fb" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 7.344 1.86)scale(1.04853 1.54135)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iAntyUd" cx="0" cy="0" r="1" gradientTransform="matrix(.9498 1.39151 -2.42838 1.65753 14.314 2.506)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="iEUlLQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.48592 .5301 -.7408 -.67906 18.416 3.309)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iar8npe" cx="0" cy="0" r="1" gradientTransform="matrix(-.80984 .2356 -.51264 -1.7621 19.299 5.458)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iwj4WHc" cx="0" cy="0" r="1" gradientTransform="rotate(156.949 8.91 5.296)scale(1.50426 2.39674)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iRZvL5b" cx="0" cy="0" r="1" gradientTransform="matrix(.3711 -.3086 .27428 .32982 18.96 19.758)" gradientUnits="userSpaceOnUse"><stop class="icg_3vvcd"/><stop offset="1" class="uewaaqbzx"/></radialGradient><radialGradient id="iDLK1eb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.357 16.482)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="epjl3v-ou"/><stop offset="1" class="zn2dcd5yl"/></radialGradient><radialGradient id="iTndpme" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.872 16.482)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="dz8ufbuwb"/><stop offset="1" class="mysctvbqw"/></radialGradient><radialGradient id="i5T6iCd" cx="0" cy="0" r="1" gradientTransform="matrix(.1836 -.5625 .3991 .13026 19.319 18.877)" gradientUnits="userSpaceOnUse"><stop class="r7zi6ccbx"/><stop offset="1" class="n8x_xkbtc"/></radialGradient><radialGradient id="ieyaRhd" cx="0" cy="0" r="1" gradientTransform="rotate(107.067 2.409 10.603)scale(1.86331 .9169)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="mwlubcb3u"/><stop offset="1" class="sf6dqgv3q"/></radialGradient><radialGradient id="i9fb3ne" cx="0" cy="0" r="1" gradientTransform="matrix(-3.84619 0 0 -3.93164 15.377 12.374)" gradientUnits="userSpaceOnUse"><stop offset=".865" class="k359d0bjg"/><stop offset="1" class="zqan0v-dy"/></radialGradient><radialGradient id="iek6ihd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.562 8.683)" gradientUnits="userSpaceOnUse"><stop class="b9nndyb1o"/><stop offset="1" class="aslchbbcc"/></radialGradient><radialGradient id="iNC83fb" cx="0" cy="0" r="1" gradientTransform="matrix(1.08228 -.29102 1.20718 4.48944 18.794 11.828)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="a76ibt5dn"/><stop offset="1" class="s61flvbkc"/></radialGradient><radialGradient id="iJO9Dac" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 16 17.953)" gradientUnits="userSpaceOnUse"><stop class="kcjik5o6k"/><stop offset="1" class="j6ndfp4vo"/></radialGradient><radialGradient id="iApyzzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.075 28.316)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="ivzWvsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.794 28.406)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iS5fSJc" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.454 8.152)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="elt890uby"/><stop offset="1" class="r2rrbr4ji"/></radialGradient><radialGradient id="iIFRdJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.92188 -7.88477 10.52054 -1.23005 16.423 15.796)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="kqc1q6b3u"/><stop offset=".967" class="dpe-7hbaw"/></radialGradient><radialGradient id="in5jdqp" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.11133 -1.40894 0 16 8.337)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="c568tvbtf"/><stop offset="1" class="j1ko-f2yz"/></radialGradient><radialGradient id="ipSNgvY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89844 -.2837 0 15.129 8.138)" gradientUnits="userSpaceOnUse"><stop class="icicd0ugz"/><stop offset="1" class="o92-_-bxr"/></radialGradient><radialGradient id="iNo9Upb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.566 29.264)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><radialGradient id="iQkvjze" cx="0" cy="0" r="1" gradientTransform="matrix(1.09333 -.49697 .60678 1.3349 17.774 6.025)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iyuA1we" cx="0" cy="0" r="1" gradientTransform="matrix(.43807 .12516 -.0658 .23031 18.223 5.05)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="i2k70yd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 25.592 -47.359)scale(.57305)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="i0FpKlc" cx="0" cy="0" r="1" gradientTransform="matrix(-.53451 0 0 -.5113 13.95 5.832)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iVKM2hc" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.014 4.692)scale(3.14584 4.21065)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iWI1Luc" cx="0" cy="0" r="1" gradientTransform="matrix(-.92671 .49017 -.41588 -.78625 16.835 5.903)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iDIDddb" cx="0" cy="0" r="1" gradientTransform="matrix(.36762 -1.77685 2.2545 .46645 15.043 8.576)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="i6vzqze" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26697 -4.42857 0 16 5.47)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sgt5sn5oc"/><stop offset="1" class="gxm-dc6uw"/></radialGradient><radialGradient id="i24HTEe" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.918 3.856)scale(2.54065 4.37422)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="izfN6qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.50548 .72669 0 17.01 5.412)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="im2FVAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59739 .68465 0 15.157 5.45)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="ima7WQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.59166 0 0 -1.94775 18.238 6.066)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iBhpxgd" cx="0" cy="0" r="1" gradientTransform="matrix(.50789 1.85311 -3.82936 1.04953 14.902 3.178)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iZgglIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.30636 -1.07606 .61574 -.1753 16.345 6.385)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="i47knQe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35637 -.56685 0 16.958 5.57)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iSxL7AH" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 9.802 -1.325)scale(.16616 .22877)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOj68Lb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35638 -.56686 0 15.042 5.57)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i8RfYrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0034 -.21702 .26087 -.00408 14.916 5.666)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izJuEQe" cx="0" cy="0" r="1" gradientTransform="rotate(54.19 3.674 14.623)scale(1.45259 2.8863)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="i3hTFLb" cx="0" cy="0" r="1" gradientTransform="rotate(127.118 6.61 5.277)scale(1.36652 1.0717)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iEpHCJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92769 1.92897 -2.74291 -1.31913 16.84 2.351)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iyevGse" cx="0" cy="0" r="1" gradientTransform="rotate(104.957 7.407 7.967)scale(1.45819 2.60292)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iN6J9td" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5388 -2.7683 2.47803 -1.37744 16.567 5.267)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><filter id="i9LOVxK" width="6.847" height="7.347" x="12.702" y="1.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="ipEumwe" width="2.311" height="8.028" x="11.403" y="12.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.682353 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="iZ1BaEb" width="1.437" height="7.032" x="19.118" y="11.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".25"/></filter><filter id="iheGZpk" width="6.169" height="12.453" x="13.016" y="15.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.462745 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="iTLO7qb" width="6.517" height="7.694" x="12.941" y="8.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="ixhvjCc" width="3.316" height="1.848" x="12.434" y="28.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="ikBJthd" width="6.594" height="13.766" x="12.841" y="15.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".5"/></filter><filter id="igCFqmc" width="1.564" height="1.664" x="13.235" y="5.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="iQKwSvM" width="1.414" height="1.664" x="17.414" y="4.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="ixDwYXp" width="1.944" height="1.944" x="17.149" y="4.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".25"/></filter><filter id="i4TA2xd" width="1.744" height="1.744" x="13.079" y="4.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".2"/></filter><filter id="ivYvwWc" width="4.476" height="4.878" x="13.762" y="3.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="i4fYcbe" width="1.825" height="2.178" x="15.016" y="5.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".25"/></filter><filter id="iOqqpob" width="1.025" height="1.378" x="15.488" y="5.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".05"/></filter><filter id="iDa38SE" width="1.851" height=".895" x="15.075" y="6.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".05"/></filter><filter id="i8FNSUb" width="1.431" height=".565" x="16.302" y="5.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="iUV3X9b" width="1.431" height=".565" x="14.268" y="5.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="ipMPAwe" width="1.19" height=".591" x="14.327" y="4.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="inKBXDz" width="1.19" height=".591" x="16.707" y="4.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_180"/></filter><filter id="iM8Icab" width=".458" height=".418" x="16.58" y="5.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".05"/></filter><filter id="iI0YFYJ" width=".616" height=".625" x="16.893" y="5.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".1"/></filter><filter id="ixyCMPm" width=".658" height=".681" x="14.941" y="5.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".1"/></filter><filter id="iZqYDgd" width=".513" height=".422" x="14.666" y="5.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".05"/></filter><filter id="i66BeCd" width="1.844" height="2.267" x="13.27" y="2.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".1"/></filter><filter id="i0nZjld" width="3.896" height="2.519" x="14.553" y="2.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_180" stdDeviation=".05"/></filter><linearGradient id="i6CG6nb" x1="18.062" x2="15.072" y1="2.779" y2="8.315" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="izgSJzU" x1="12.466" x2="12.466" y1="12.632" y2="12.474" gradientUnits="userSpaceOnUse"><stop class="d8l0ribxz"/><stop offset="1" class="sgj6b5b-t"/></linearGradient><linearGradient id="iBwD5cu" x1="19.747" x2="19.747" y1="12.632" y2="12.394" gradientUnits="userSpaceOnUse"><stop class="w2wdskbew"/><stop offset="1" class="lj8hkjeee"/></linearGradient><linearGradient id="icWbAmd" x1="16" x2="16" y1="15.863" y2="16.296" gradientUnits="userSpaceOnUse"><stop class="sb3cb-bog"/><stop offset="1" class="hpe4_756h"/></linearGradient><linearGradient id="iCEVb2b" x1="16" x2="16" y1="8.953" y2="15.914" gradientUnits="userSpaceOnUse"><stop class="qb52yacny"/><stop offset="1" class="k3iqnbc3x"/></linearGradient><linearGradient id="iO1McLA" x1="17.173" x2="17.173" y1="15.914" y2="15.654" gradientUnits="userSpaceOnUse"><stop offset=".068" class="d10os3b5g"/><stop offset="1" class="tfix0o_9x"/></linearGradient><linearGradient id="iiFwxIb" x1="18.247" x2="16.5" y1="29.578" y2="29.375" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient><linearGradient id="imXX7Fy" x1="12.866" x2="19.137" y1="7.821" y2="7.821" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iFVyysb" x1="12.866" x2="19.137" y1="7.807" y2="7.807" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="inQdEHC" x1="13.235" x2="14.535" y1="5.871" y2="5.871" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iLhwosb" x1="15.54" x2="15.916" y1="6.393" y2="6.439" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="ifkfGid" x1="16" x2="16" y1="6.768" y2="6.5" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="i6etODR" x1="15.68" x2="15.879" y1="7.417" y2="7.034" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="iGh2oyc" x1="17.3" x2="17.162" y1="5.594" y2="5.679" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icnlnye" x1="15.368" x2="15.23" y1="5.594" y2="5.679" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-standing-medium-light" /></template>
<style>
.a76ibt5dn {
  stop-color: var(--svg-color--624da1, #624DA1);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aslchbbcc {
  stop-color: var(--svg-color--5e4f7e, #5E4F7E);
  stop-opacity: 0;
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.aur7g7hae {
  d: path("M15.735 2.41c-.498-.11-1.03.42-1.082.604c.677 1.59 1.717 1.439 2.871 1.31c.69-.076.766.239.825.39c-.192-1.78-1.48-2.053-2.614-2.304");
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b9nndyb1o {
  stop-color: var(--svg-color--5e4f7e, #5E4F7E);
}

.bcnnx6b_s {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16 7.111a1.3 1.3 0 0 1-.624-.151c-.062-.032-.129.039-.09.096a.848.848 0 0 0 1.428 0c.038-.06-.028-.128-.09-.096c-.18.096-.393.151-.624.151");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bmn6q0bjm {
  cx: 14.922px;
  cy: 5.528px;
  rx: 0.171px;
  ry: 0.087px;
}

.bmuzas5gv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.93 5.443c.029.038-.03.083-.096.133c-.067.05-.116.085-.144.047c-.028-.037.003-.108.07-.157c.066-.05.143-.06.17-.023");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.c568tvbtf {
  stop-color: var(--svg-color--d0958c, #D0958C);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.cge-036tr {
  d: path("m13.016 15.863l.484 12.453h2l.238-9.523c0-.329.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.d10os3b5g {
  stop-color: var(--svg-color--614699, #614699);
}

.d8l0ribxz {
  stop-color: var(--svg-color--482f7c, #482F7C);
}

.d8xf2ibmq {
  d: path("M16.01 7.808h-.017c.044 0 .083 0 .127.004q-.054-.005-.11-.004");
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dpe-7hbaw {
  stop-color: var(--svg-color--271a45, #271A45);
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

.dz8ufbuwb {
  stop-color: var(--svg-color--d27e6a, #D27E6A);
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.e69c9iqaq {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.828 5.735l-.3.746a.237.237 0 0 0 .228.307h.345a.238.238 0 0 0 .23-.307l-.234-.746c-.05-.166-.217-.166-.27 0");
}

.ehwsee08x {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m14.508 5.051l-.002.002a.118.118 0 0 1-.122-.202h.001l.001-.002l.005-.002l.014-.008l.05-.026a1.4 1.4 0 0 1 .18-.07c.15-.048.359-.089.584-.049a.118.118 0 1 1-.04.232a1 1 0 0 0-.472.04a1 1 0 0 0-.19.08z");
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.elt890uby {
  stop-color: var(--svg-color--9e85d7, #9E85D7);
}

.epjl3v-ou {
  stop-color: var(--svg-color--9c5f5c, #9C5F5C);
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.f3fwesbvc {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.498 5.582c-.116-.205-.293-.367-.675-.367a.73.73 0 0 0-.471.162c-.118.096-.103.218-.011.264l.244.14c.287-.093.603-.106.913-.199");
}

.f7r_gn4es {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.502 5.582c.116-.205.294-.367.675-.367c.167 0 .328.047.471.162c.118.096.102.218.011.264l-.244.14c-.287-.093-.603-.106-.913-.199");
}

.ffhuevyci {
  d: path("M16.93 5.443c.029.038-.03.083-.096.133c-.067.05-.116.085-.144.047c-.028-.037.003-.108.07-.157c.066-.05.143-.06.17-.023");
}

.fg7h3c35y {
  fill: var(--svg-color--aa6e62, #AA6E62);
  d: path("M12.668 19.011a.22.22 0 0 1-.043-.238h-.438l.32.996c.262.078.54.05.59-.113a.32.32 0 0 0-.074-.301a9 9 0 0 1-.355-.344");
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gdmddpdka {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.832 5.674l-.233.746a.237.237 0 0 0 .228.308h.346a.238.238 0 0 0 .228-.308l-.233-.746c-.05-.166-.284-.166-.336 0");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
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

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.hil4-np7l {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.95 5.241a.614.614 0 0 0-.595.465a.12.12 0 0 0 .117.15h.98a.1.1 0 0 0 .1-.12a.615.615 0 0 0-.602-.495");
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hm4ptbkef {
  fill: var(--svg-color--9d98a2, #9D98A2);
  d: path("M13.841 16.234L14.31 28h.812V17.39h2.203V28h.672l.438-11.766z");
}

.hpe4_756h {
  stop-color: var(--svg-color--856988, #856988);
  stop-opacity: 0;
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i0vp1so6w {
  d: path("M15.129 7.226h1.742v1.352a.871.871 0 0 1-1.742 0z");
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.icg_3vvcd {
  stop-color: var(--svg-color--c2807d, #C2807D);
}

.icicd0ugz {
  stop-color: var(--svg-color--d79d88, #D79D88);
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.ise8hkbqb {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.434 29.671v.243H15.5v-1.598h-1.992c-.102.367-.574.754-.817.914a.54.54 0 0 0-.257.441");
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j1j51bc4m {
  d: path("M13.765 5.278h.006l-.005-.117l-.004-.134c.009-.417.252-.578.356-.632l.022-.01l.023-.008c.234-.108.423-.296.522-.542l.036-.086a.116.116 0 0 1 .203-.022c.315.462.842.735 1.4.735h1.415c.08 0 .476.038.5.585l-.053 1.35c-.054 1.231-1.015 2.058-2.189 2.058c-1.173 0-2.135-.827-2.189-2.058z");
}

.j1ko-f2yz {
  stop-color: var(--svg-color--d69a8c, #D69A8C);
}

.j6ndfp4vo {
  stop-color: var(--svg-color--6a597b, #6A597B);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.k359d0bjg {
  stop-color: var(--svg-color--645b87, #645B87);
  stop-opacity: 0;
}

.k3iqnbc3x {
  stop-color: var(--svg-color--7759b9, #7759B9);
}

.kcjik5o6k {
  stop-color: var(--svg-color--6a597b, #6A597B);
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kqc1q6b3u {
  stop-color: var(--svg-color--4b3677, #4B3677);
  stop-opacity: 0;
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
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

.lj8hkjeee {
  stop-color: var(--svg-color--6c5ca2, #6C5CA2);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
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

.mwlubcb3u {
  stop-color: var(--svg-color--4a367d, #4A367D);
}

.myif5tbjr {
  fill: var(--svg-color--8b7dbc, #8B7DBC);
  d: path("M20.468 12.512c-.487-2.254-1.629-3.334-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.121");
}

.mysctvbqw {
  stop-color: var(--svg-color--d27e6a, #D27E6A);
  stop-opacity: 0;
}

.n8x_xkbtc {
  stop-color: var(--svg-color--c07874, #C07874);
  stop-opacity: 0;
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nmunwx3pv {
  fill: var(--svg-color--e3b495, #E3B495);
  d: path("M19.888 20.292c.938-1.982.769-6.259.487-7.824h-1.671c.071 2.426-.156 5.254-.294 6.522a.29.29 0 0 0 .555.15l.116-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.202c-.061.299-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.nv-tm3b_c {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.05 5.241c.287 0 .53.198.595.465a.12.12 0 0 1-.117.15h-.98a.1.1 0 0 1-.1-.12a.614.614 0 0 1 .602-.495");
}

.o_hp5nbjg {
  d: path("M12.112 20.292c-.938-1.982-.769-6.259-.488-7.824h1.672c-.071 2.426.04 5.243.178 6.512c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.263a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.202c.061.299.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.o92-_-bxr {
  stop-color: var(--svg-color--d79d88, #D79D88);
  stop-opacity: 0;
}

.o93ji_bej {
  d: path("M19.888 20.292c.938-1.982.769-6.259.487-7.824h-1.671c.071 2.426-.156 5.254-.294 6.522a.29.29 0 0 0 .555.15l.116-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.202c-.061.299-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojwkb-b4s {
  d: path("M18.12 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.oljgxubcv {
  stroke: var(--svg-color--f2ae96, #F2AE96);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.767 12.193c.104 1.156.25 3.975 0 6");
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pcr8w9bct {
  d: path("M11.533 12.512c.486-2.254 1.628-3.334 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.121");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.posvnzbmj {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M13.95 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pu1qalb0n {
  fill: var(--svg-color--64558f, #64558F);
  d: path("M11.533 12.512c.486-2.254 1.628-3.334 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.121");
}

.q3bc6bbmg {
  fill: var(--svg-color--000, #000);
  d: path("M15.265 5.753c0-.125-.1-.225-.224-.225a.224.224 0 0 0-.2.328h.398a.2.2 0 0 0 .026-.103");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.q6kh5xjeh {
  d: path("m13.766 5.161l-.004-.134c.009-.417.252-.578.356-.632l.022-.01l.023-.008c.234-.108.423-.296.522-.542l.036-.086a.116.116 0 0 1 .203-.022c.315.462.842.735 1.4.735h1.415c.08 0 .476.038.5.585l-.053 1.35c-.054 1.231-1.015 2.058-2.189 2.058c-1.173 0-2.135-.827-2.189-2.058z");
}

.qb52yacny {
  stop-color: var(--svg-color--8467c1, #8467C1);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
}

.qr3eebgfz {
  d: path("M12.941 11.378a3.059 3.059 0 0 1 6.118 0v4.442a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.094-.094z");
}

.qrmj1y8xw {
  d: path("M13.942 6.54a.707.707 0 1 0 0-1.414a.707.707 0 0 0 0 1.413");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r0w13r7uj {
  d: path("M16.96 5.36a.392.392 0 0 1 .377.496h-.757a.394.394 0 0 1 .38-.495");
}

.r2rrbr4ji {
  stop-color: var(--svg-color--886cc6, #886CC6);
  stop-opacity: 0;
}

.r7p4z7bsm {
  d: path("M16.155 7.808q.164.008.336.021c-.114-.008-.223-.017-.336-.021");
}

.r7zi6ccbx {
  stop-color: var(--svg-color--c07874, #C07874);
}

.rdil0mgdd {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M18.12 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rpcnqk_9o {
  d: path("M13.85 3.19c.273-.242.667-.245.887-.205l.177.567a.34.34 0 0 0-.298.103c-.199.736-.95.625-1.097 1.178c-.066-.656-.14-1.223.331-1.642");
}

.s61flvbkc {
  stop-color: var(--svg-color--7361ab, #7361AB);
  stop-opacity: 0;
}

.sb3cb-bog {
  stop-color: var(--svg-color--856988, #856988);
}

.sf6dqgv3q {
  stop-color: var(--svg-color--4a367d, #4A367D);
  stop-opacity: 0;
}

.sgj6b5b-t {
  stop-color: var(--svg-color--655690, #655690);
  stop-opacity: 0;
}

.sgt5sn5oc {
  stop-color: var(--svg-color--bd8381, #BD8381);
  stop-opacity: 0;
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.t_70vht6h {
  d: path("M15.04 5.36a.392.392 0 0 0-.377.496h.757a.395.395 0 0 0-.38-.495");
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tfix0o_9x {
  stop-color: var(--svg-color--7c63b5, #7C63B5);
  stop-opacity: 0;
}

.tkifgyigj {
  d: path("M15.399 5.707c0-.127-.103-.212-.131-.237l-.127.122l.078.16z");
}

.u-feptipi {
  cx: 14.922px;
  cy: 5.528px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.171px;
  ry: 0.087px;
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.u1ssmd66p {
  d: path("M20.468 12.512c-.487-2.254-1.629-3.334-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.121");
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.uewaaqbzx {
  stop-color: var(--svg-color--c6856b, #C6856B);
}

.uj1jiacmd {
  d: path("M19.333 19.011a.22.22 0 0 0 .043-.238h.437l-.32.996c-.262.078-.54.05-.59-.113a.32.32 0 0 1 .074-.301c.083-.077.271-.253.355-.344");
}

.ukvj5-vlj {
  d: path("M19.566 29.671v.243H16.5v-1.598h1.992c.102.367.574.754.817.914c.186.123.257.3.257.441");
}

.umgvlrbgn {
  fill: var(--svg-color--000, #000);
  d: path("M16.735 5.753c0-.125.1-.225.224-.225a.224.224 0 0 1 .2.328h-.397a.2.2 0 0 1-.027-.103");
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.usg2e3xpf {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m17.64 4.85l-.062.102za.118.118 0 0 1-.12.202h-.001l-.002-.002l-.05-.025a1 1 0 0 0-.15-.06a1 1 0 0 0-.47-.04a.118.118 0 0 1-.042-.232c.226-.04.434 0 .584.048a1.4 1.4 0 0 1 .245.105l.004.002z");
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

.vok70cb_d {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16 7.111a1.3 1.3 0 0 1-.624-.151c-.062-.032-.129.039-.09.096a.848.848 0 0 0 1.428 0c.038-.06-.028-.128-.09-.096c-.18.096-.393.151-.624.151Z");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vy3y1vbex {
  d: path("M17.309 5.701a.37.37 0 0 0-.102-.203l-.114.125l.051.1z");
}

.w2wdskbew {
  stop-color: var(--svg-color--503a89, #503A89);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.xc4tawbvb {
  d: path("m15.832 5.674l-.233.746a.237.237 0 0 0 .228.308h.346a.238.238 0 0 0 .228-.308l-.233-.746c-.05-.166-.284-.166-.336 0");
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xqme1t_en {
  fill: var(--svg-color--827a8a, #827A8A);
  d: path("m13.016 15.863l.484 12.453h2l.238-9.523c0-.329.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
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

.ymsp3kbav {
  d: path("M18.12 6.54a.707.707 0 1 0 0-1.414a.707.707 0 0 0 0 1.413");
}

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.zizok7rsa {
  fill: var(--svg-color--d19881, #D19881);
  d: path("M12.112 20.292c-.938-1.982-.769-6.259-.488-7.824h1.672c-.071 2.426.04 5.243.178 6.512c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.263a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.202c.061.299.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.zjcs0bbar {
  d: path("M13.95 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.zm9zkcl5b {
  fill-rule: evenodd;
  d: path("M19.156 6.452a1.44 1.44 0 0 0 .024-1.2h.003a1.4 1.4 0 0 0-.124-.226v-.001a1.4 1.4 0 0 1-.232-.778v-.005c0-.8-.649-1.449-1.449-1.449a.24.24 0 0 1-.2-.102a1.452 1.452 0 0 0-2.356 0a.25.25 0 0 1-.2.102h-.037a1.45 1.45 0 0 0-1.412 1.45v.004c0 .275-.08.547-.231.778l-.001.001a1.45 1.45 0 0 0-.097 1.426a.23.23 0 0 1 0 .2a1.41 1.41 0 0 0 1.271 2.032h3.77a1.412 1.412 0 0 0 1.271-2.032a.23.23 0 0 1 0-.2m-5.385-1.174h-.006l.527 1.035c.054 1.23.535 0 1.708 0s1.685 1.37 1.74.139l.498-1.405c-.023-.546-.42-.585-.499-.585h-1.414a1.7 1.7 0 0 1-1.401-.735a.116.116 0 0 0-.203.023l-.036.085a1 1 0 0 1-.522.542l-.023.009l-.022.009c-.104.054-.347.215-.356.632l.004.134z");
}

.zn2dcd5yl {
  stop-color: var(--svg-color--9c5f5c, #9C5F5C);
  stop-opacity: 0;
}

.zqan0v-dy {
  stop-color: var(--svg-color--645b87, #645B87);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
