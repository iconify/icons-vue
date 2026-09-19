<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iakT1uc)" class="v7gluqbxb"/><path fill="url(#iUracab)" class="su72xqoac"/><path fill="url(#iwluTVd)" class="su72xqoac"/><path fill="url(#iPbok2c)" class="xu2szrbjd"/><path fill="url(#izGmjCe)" class="xu2szrbjd"/><path fill="url(#iqL9usb)" class="xu2szrbjd"/><path fill="url(#inrblnc)" class="xu2szrbjd"/><path fill="url(#iGzNNFc)" class="r3q9_wiir"/><path fill="url(#iw7An0a)" class="r3q9_wiir"/><path fill="url(#iViGBMM)" class="r3q9_wiir"/><path fill="url(#iCFheld)" class="r3q9_wiir"/><g filter="url(#iYUdSwE)"><path fill="url(#iEc0Kbd)" class="ieftmabpg"/></g><g filter="url(#iNdnFJd)"><path fill="url(#iVg82Db)" class="zehc2bc2m"/></g><g filter="url(#ifVBiWc)"><path fill="url(#imzHW5c)" class="zrtk-0btq"/></g><path fill="url(#i4t7TWb)" class="ztn-0pg6n"/><path fill="url(#ivSDZvr)" class="ztn-0pg6n"/><path fill="url(#iD1HD5c)" class="ztn-0pg6n"/><path fill="url(#iDvpDpd)" class="ztn-0pg6n"/><path fill="url(#iXhEQSK)" class="ztn-0pg6n"/><path fill="url(#iM7SDhd)" class="mx0dy7bzm"/><path fill="url(#iQ7B0Vc)" class="mx0dy7bzm"/><path fill="url(#iw8F5Od)" class="mx0dy7bzm"/><path fill="url(#iItEm1T)" class="mx0dy7bzm"/><path fill="url(#i8MGWHb)" class="zehc2bc2m"/><path fill="url(#iC3KAHn)" class="qctpdhrvn"/><path fill="url(#iupneAV)" class="qctpdhrvn"/><path fill="url(#iakT1uc)" class="v7gluqbxb"/><path fill="url(#iriZyhb)" class="xazl-5b3q"/><path class="kua6vgb0k"/><path fill="url(#ic1k1Nb)" class="tq9nmh6wg"/><path fill="url(#i0SGEgs)" class="ci4199-6o"/><path fill="url(#inpq0bc)" class="ci4199-6o"/><path fill="url(#iXNJkLw)" class="niz9gsbpv"/><path fill="url(#i097Uvd)" class="niz9gsbpv"/><g filter="url(#iLSQn3d)"><path fill="url(#i1kURxp)" class="utok7kzjw"/></g><path fill="url(#iT4K4Kb)" class="utok7kzjw"/><path fill="url(#iR02oee)" class="utok7kzjw"/><path fill="url(#iszhGxe)" class="utok7kzjw"/><path fill="url(#il1Ezvb)" class="utok7kzjw"/><g filter="url(#iwdqdyR)"><path class="lsz3g_boc"/></g><g filter="url(#iLI8pFp)"><path fill="url(#iGHJeMd)" class="wd79rybqt"/><path fill="url(#ifalOob)" class="wd79rybqt"/><path fill="url(#iHRxbxe)" class="wd79rybqt"/><path fill="url(#iQ2rj4c)" class="wd79rybqt"/></g><g filter="url(#i6lQBgd)"><path stroke="url(#icpB9hb)" class="r8xr7ubth"/></g><path fill="url(#iDpLf0D)" class="gixq0acyw"/><g filter="url(#iJvQE6d)"><path fill="url(#i4x46jd)" class="k29z_pwdo"/><path fill="url(#ixBIyKe)" class="k29z_pwdo"/><path fill="url(#ipPEAcb)" class="k29z_pwdo"/><path fill="url(#iIQZKSc)" class="k29z_pwdo"/><path fill="url(#i1w2XIe)" class="k29z_pwdo"/></g><g filter="url(#i7nh7Xd)"><path class="srv_dzbby"/></g><g filter="url(#ilJyPid)"><path class="xz_p9i_ao"/></g><g filter="url(#icDasYd)"><path fill="url(#iOvoZ8c)" class="mrblk5hzh"/><path fill="url(#iQsAPqe)" class="mrblk5hzh"/></g><g filter="url(#iEU6jPc)"><path fill="url(#i3nHiCe)" class="yvvqshblb"/><path fill="url(#ix8uqAe)" class="yvvqshblb"/><path fill="url(#iR7xogc)" class="yvvqshblb"/><path fill="url(#iR5u25b)" class="yvvqshblb"/><path fill="url(#i5VL4se)" class="yvvqshblb"/></g><path class="c_uc_ybuu"/><path fill="url(#ie1czoc)" class="g_i4qq_dl"/><path class="ow2dorb-x"/><g filter="url(#ifwadPd)"><path class="cpf_yqbrx"/><path fill="url(#ilPMusc)" class="x7j0uibnq"/></g><g filter="url(#iAOwTHc)"><path fill="url(#iHkCScD)" class="f7z392_tk"/></g><path class="mju0ocm_e"/><path fill="url(#iZFtVVc)" class="etxvs89bh"/><path class="dx9m9rbas"/><g filter="url(#igaDdEU)"><path fill="url(#i6EoLke)" class="fify_f2yl"/></g><g filter="url(#i0BOqZd)"><ellipse transform="rotate(-27.914 12.987 10.112)" class="vga2iwqpu"/><ellipse fill="url(#iCX6pDc)" transform="rotate(-27.914 12.987 10.112)" class="qkpi96bvx"/></g><path fill="url(#iEt7sqh)" class="q0589cc1h"/><path fill="url(#ihde6eJ)" class="q0589cc1h"/><path fill="url(#i6gBD2c)" class="q0589cc1h"/><path fill="url(#ixdnTub)" class="iyn6cjh_v"/><path fill="url(#i44M8zc)" class="iyn6cjh_v"/><g filter="url(#iARvABd)"><path class="l4lz-0bhl"/></g><g filter="url(#i0eUyte)"><path class="m_gw8gbiz"/></g><path fill="url(#i3bRIbd)" class="w7mfp1z7m"/><g filter="url(#iVNTxRb)"><path clip-rule="evenodd" class="juteyac_n"/></g><path fill="url(#iKkFNtc)" class="briaz_b_b"/><path fill="url(#ijPMi1c)" class="briaz_b_b"/><path fill="url(#icTS2Zb)" class="briaz_b_b"/><g filter="url(#iswf3Bd)"><rect class="dpvsui56n"/><rect fill="url(#izniTAb)" class="i6tsuwbjp"/><rect fill="url(#iVSfw3d)" class="i6tsuwbjp"/><rect fill="url(#ieqcHub)" class="i6tsuwbjp"/></g><path fill="url(#i3VTKjc)" class="b7ptc5bto"/><path fill="url(#i5TJHOH)" class="b7ptc5bto"/><path fill="url(#iY8Nhve)" class="b7ptc5bto"/><path fill="url(#iy710pt)" class="b7ptc5bto"/><path fill="url(#ikHXSJd)" class="edip7dywy"/><path fill="url(#iMtf6md)" class="l2nok66dj"/><g filter="url(#iA5sOMc)"><path fill="url(#iAQa3Ee)" class="k-hxoxbhg"/><path fill="url(#iI61LIc)" class="k-hxoxbhg"/><path fill="url(#icj0iib)" class="k-hxoxbhg"/><path fill="url(#igLTHZc)" class="k-hxoxbhg"/><path fill="url(#imPVYdl)" class="k-hxoxbhg"/></g><g filter="url(#iMY80ve)"><path stroke="url(#iGgfLte)" class="oyvjs-x-y"/></g><g filter="url(#iIlEt8b)"><path stroke="url(#iGP1Yrb)" class="rnmqrkbhw"/></g><g filter="url(#i0wCPRl)"><path stroke="url(#iXOHnge)" class="rmgd8acpv"/></g><defs><radialGradient id="iUracab" cx="0" cy="0" r="1" gradientTransform="scale(3.29991 5.8125)rotate(90 .76 3.921)" gradientUnits="userSpaceOnUse"><stop class="k6cf6dbdc"/><stop offset="1" class="lolok3p7w"/></radialGradient><radialGradient id="iwluTVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.378)" gradientUnits="userSpaceOnUse"><stop class="yywqu2bti"/><stop offset="1" class="vhmloyszq"/></radialGradient><radialGradient id="iPbok2c" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.488 14.592)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="inrblnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.472)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="iGzNNFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.347)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="iw7An0a" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.597)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iVg82Db" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.972)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="i4t7TWb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.753)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="ivSDZvr" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.357 -.224)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="iD1HD5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.73439 2.1875 -3.93465 -1.32095 19.943 16.05)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="lwgxwcc9p"/><stop offset="1" class="brppywbtt"/></radialGradient><radialGradient id="iM7SDhd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.174)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iw8F5Od" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 29.03)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="i8MGWHb" cx="0" cy="0" r="1" gradientTransform="rotate(109.374 .564 12.51)scale(3.01445 6.53104)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="hxg13bqik"/><stop offset="1" class="k10lreb3f"/></radialGradient><radialGradient id="iC3KAHn" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.94)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="iriZyhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59837 5.09841 0 15.426 18.68)" gradientUnits="userSpaceOnUse"><stop class="yzv5f8bpf"/><stop offset=".621" class="p4jiy8bvo"/><stop offset="1" class="vj4_95wuu"/></radialGradient><radialGradient id="ic1k1Nb" cx="0" cy="0" r="1" gradientTransform="rotate(131.186 8.022 17.939)scale(.74743 .79607)" gradientUnits="userSpaceOnUse"><stop class="u7id6gble"/><stop offset="1" class="ydn9dmb6d"/></radialGradient><radialGradient id="i0SGEgs" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 5.84 14.192)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="inpq0bc" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -1.686 25.91)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iXNJkLw" cx="0" cy="0" r="1" gradientTransform="matrix(1.33305 3.92345 -1.7834 .60594 9.893 11.857)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="i097Uvd" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -2.833 13.149)scale(1.04691 .91836)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="i1kURxp" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24801 18.248 10.797)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iT4K4Kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.57022 9.99845 0 15.247 17.133)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="af5vl0bbt"/><stop offset="1" class="kb4zjc5yz"/></radialGradient><radialGradient id="iR02oee" cx="0" cy="0" r="1" gradientTransform="matrix(-.40256 6.10192 -2.24332 -.148 20.598 10.566)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iszhGxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.70221 0 13.35 9.617)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="il1Ezvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 1.99125 0 17.93 9.206)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="icpB9hb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.178 -5.172)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iDpLf0D" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.44 14.337)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ixBIyKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.71897 10.1329 0 10.211 9.216)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="ipPEAcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63265 6.43634 0 20.302 9.216)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iIQZKSc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10651 -1.44082 .76733 -2.187 19.547 2.94)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="i1w2XIe" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 14.536 1.346)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iOvoZ8c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80692 1.37358 -.3823 -1.05955 15.694 2.79)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iQsAPqe" cx="0" cy="0" r="1" gradientTransform="matrix(3.2182 -5.09542 5.6452 3.56544 10.01 7.549)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="i3nHiCe" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 .8008 -.44786 1.89357 19.06 3.95)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="ix8uqAe" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 12.748 -1.647)scale(4.28181 2.38793)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iR7xogc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.5774 -.9364 19.95 8.254)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iR5u25b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.235 3.833)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="i5VL4se" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 18.894 3.707)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="ie1czoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.623 10.208)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ilPMusc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.218 .886)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZFtVVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.258 10.208)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iCX6pDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.973 10.427)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihde6eJ" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.058 9.895)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="i6gBD2c" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.419 10.44)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="i44M8zc" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 .96 9.208)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="icTS2Zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.44)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="izniTAb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.128)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iVSfw3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.004 18.98)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="ieqcHub" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.34)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="iy710pt" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.284)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="iI61LIc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.454 24.644)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="icj0iib" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 23.323 26.02)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="igLTHZc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 23.137 27.347)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="imPVYdl" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 23.041 28.613)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><linearGradient id="iakT1uc" x1="8.23" x2="22.659" y1="15.358" y2="15.358" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="izGmjCe" x1="11.239" x2="11.239" y1="30.472" y2="29.159" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iqL9usb" x1="15.177" x2="14.208" y1="29.159" y2="29.159" gradientUnits="userSpaceOnUse"><stop offset=".129" class="dx1e6jb0z"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iViGBMM" x1="19.74" x2="19.74" y1="30.472" y2="29.159" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iCFheld" x1="15.802" x2="16.505" y1="28.034" y2="28.034" gradientUnits="userSpaceOnUse"><stop class="bx23o8bkx"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iEc0Kbd" x1="10.677" x2="12.896" y1="18.003" y2="24.691" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="imzHW5c" x1="20.45" x2="18.099" y1="19.032" y2="23.733" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="iDvpDpd" x1="18.958" x2="17.552" y1="24.159" y2="22.659" gradientUnits="userSpaceOnUse"><stop class="p2mir8bpk"/><stop offset="1" class="ifg4wbcuq"/></linearGradient><linearGradient id="iXhEQSK" x1="17.146" x2="17.974" y1="18.941" y2="19.284" gradientUnits="userSpaceOnUse"><stop offset=".081" class="ea_0ewlyw"/><stop offset="1" class="z_a2ribdx"/></linearGradient><linearGradient id="iQ7B0Vc" x1="6.567" x2="6.567" y1="30.414" y2="29.281" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iItEm1T" x1="8.38" x2="7.935" y1="29.448" y2="29.446" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="iupneAV" x1="22.753" x2="23.162" y1="27.722" y2="27.706" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="iGHJeMd" x1="15.441" x2="16.296" y1="11.828" y2="11.828" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="ifalOob" x1="14.368" x2="15.442" y1="11.673" y2="11.732" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iHRxbxe" x1="15.441" x2="15.441" y1="12.227" y2="13.079" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iQ2rj4c" x1="15.441" x2="15.441" y1="9.979" y2="10.399" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="i4x46jd" x1="20.804" x2="10.681" y1="5.135" y2="5.135" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iHkCScD" x1="18.401" x2="18.087" y1="10.262" y2="10.455" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6EoLke" x1="14.002" x2="13.689" y1="10.262" y2="10.455" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEt7sqh" x1="21.877" x2="20.67" y1="9.962" y2="12.138" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="ixdnTub" x1="9.591" x2="11.049" y1="10.666" y2="10.539" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="i3bRIbd" x1="10.917" x2="22.177" y1="9.789" y2="9.789" gradientUnits="userSpaceOnUse"><stop offset=".609" class="khdfr5bqk"/><stop offset="1" class="cey6-nbgg"/></linearGradient><linearGradient id="iKkFNtc" x1="23.825" x2="26.529" y1="20.909" y2="20.909" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="ijPMi1c" x1="26.529" x2="26.18" y1="20.894" y2="20.894" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="i3VTKjc" x1="26.529" x2="25.177" y1="23.222" y2="23.222" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="i5TJHOH" x1="26.529" x2="26.129" y1="23.37" y2="23.37" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="iY8Nhve" x1="23.696" x2="24.227" y1="23.37" y2="23.37" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="ikHXSJd" x1="24.782" x2="23.892" y1="21.863" y2="21.863" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iMtf6md" x1="24.782" x2="23.892" y1="23.644" y2="23.644" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iAQa3Ee" x1="27.165" x2="23.137" y1="28.112" y2="28.112" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="iGgfLte" x1="25.434" x2="23.599" y1="26.052" y2="26.052" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iGP1Yrb" x1="25.356" x2="23.52" y1="27.357" y2="27.357" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iXOHnge" x1="25.434" x2="23.599" y1="28.661" y2="28.661" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><filter id="iYUdSwE" width="7.023" height="11.703" x="8.591" y="15.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".375"/></filter><filter id="iNdnFJd" width="5.673" height="10.453" x="9.475" y="15.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2163"/></filter><filter id="ifVBiWc" width="6.388" height="10.529" x="15.499" y="16.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".375"/></filter><filter id="iLSQn3d" width="10.72" height="12.542" x="10.377" y="4.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2163" result="effect2_innerShadow_4002_2163"/></filter><filter id="iwdqdyR" width="3.877" height="4.9" x="13.295" y="9.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".5"/></filter><filter id="iLI8pFp" width="2.077" height="3.1" x="14.402" y="9.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".05"/></filter><filter id="i6lQBgd" width="3.718" height="1.573" x="13.581" y="13.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".05"/></filter><filter id="iJvQE6d" width="12.873" height="8.357" x="9.004" y="1.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2163" result="effect2_innerShadow_4002_2163"/></filter><filter id="i7nh7Xd" width="2.339" height="1.19" x="17.03" y="7.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2163"/></filter><filter id="ilJyPid" width="2.339" height="1.176" x="11.773" y="7.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2163"/></filter><filter id="icDasYd" width="6.584" height="5.992" x="9.36" y="2.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".125"/></filter><filter id="iEU6jPc" width="6.362" height="5.736" x="15.282" y="3.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".125"/></filter><filter id="ifwadPd" width=".787" height=".696" x="16.889" y="9.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".05"/></filter><filter id="iAOwTHc" width=".891" height=".913" x="17.729" y="9.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".1"/></filter><filter id="igaDdEU" width=".986" height="1.04" x="13.286" y="9.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".1"/></filter><filter id="i0BOqZd" width=".913" height=".705" x="12.531" y="9.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".05"/></filter><filter id="iARvABd" width="1.329" height="2.379" x="9.408" y="9.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".125"/></filter><filter id="i0eUyte" width="1.447" height="2.403" x="20.152" y="9.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".125"/></filter><filter id="iVNTxRb" width="11.479" height="6.324" x="9.611" y="6.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.529412 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.760784 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2163" result="effect2_innerShadow_4002_2163"/></filter><filter id="iswf3Bd" width="4.008" height=".781" x="23.173" y="18.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2163"/></filter><filter id="iA5sOMc" width="4.618" height="5.556" x="23.137" y="24.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2163"/></filter><filter id="iMY80ve" width="2.047" height=".25" x="23.629" y="25.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".05"/></filter><filter id="iIlEt8b" width="2.047" height=".25" x="23.551" y="27.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".05"/></filter><filter id="i0wCPRl" width="2.047" height=".25" x="23.629" y="28.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2163" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:scientist" /></template>
<style>
.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.af5vl0bbt {
  stop-color: var(--svg-color--e2814c, #E2814C);
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.b7ptc5bto {
  d: path("M26.529 21.284v4.172h-2.704v-4.172z");
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.briaz_b_b {
  d: path("M23.825 19.519h2.703v5.938h-2.703z");
}

.brppywbtt {
  stop-color: var(--svg-color--f7ddd3, #F7DDD3);
  stop-opacity: 0;
}

.bx23o8bkx {
  stop-color: var(--svg-color--b28598, #B28598);
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.bzewrsgmw {
  stop-color: var(--svg-color--df9728, #DF9728);
  stop-opacity: 0;
}

.c_uc_ybuu {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.832 9.459c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.cey6-nbgg {
  stop-color: var(--svg-color--c4c58e, #C4C58E);
  stop-opacity: 0.5;
}

.ci4199-6o {
  d: path("M20.302 12.047c.335-.01.65-.124.904-.308v.93c0 .894-.532 1.69-1.34 2.02q.256-.546.346-1.18z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.cpf_yqbrx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.56 9.92c.063.084-.07.188-.221.301s-.264.193-.327.107c-.064-.085.007-.245.158-.358s.325-.136.39-.05");
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dpvsui56n {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.738px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.dx1e6jb0z {
  stop-color: var(--svg-color--be9bb3, #BE9BB3);
}

.dx9m9rbas {
  fill: var(--svg-color--000, #000);
  d: path("M13.768 10.623a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.745h.905a.5.5 0 0 0 .06-.235");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.ea_0ewlyw {
  stop-color: var(--svg-color--c79f97, #C79F97);
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.edip7dywy {
  d: path("M23.825 22.097v-.469h.805a.234.234 0 1 1 0 .469z");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.etxvs89bh {
  d: path("M13.257 9.73a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.f7z392_tk {
  d: path("M18.42 10.506a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.fify_f2yl {
  d: path("M14.072 10.518c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.ft5dv1b6b {
  fill: none;
}

.g_i4qq_dl {
  d: path("M17.625 9.73a.892.892 0 0 1 .86 1.128H16.76a.896.896 0 0 1 .864-1.128");
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gixq0acyw {
  d: path("M15.44 13.694c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h97sosa1o {
  stop-color: var(--svg-color--df9728, #DF9728);
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hxg13bqik {
  stop-color: var(--svg-color--b7938b, #B7938B);
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i6tsuwbjp {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.738px;
  rx: 0.391px;
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ieftmabpg {
  d: path("m9.474 17.782l-.131 1.733a.6.6 0 0 0 .494.636l.479.085a.15.15 0 0 1 .085.248l-.626.691a.5.5 0 0 0 .014.687l4.733 4.808a.2.2 0 0 0 .342-.14v-3.38a2 2 0 0 0-.175-.82l-2.606-5.804a10.6 10.6 0 0 0-2.61 1.256");
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.iyn6cjh_v {
  d: path("M10.387 8.939a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.juteyac_n {
  fill: var(--svg-color--ac9faf, #AC9FAF);
  fill-rule: evenodd;
  d: path("M9.761 9.231c.011-1.676 1.389-3.005 3.047-3.005h5.275a3.01 3.01 0 0 1 3.007 3.04v.001c-.022 1.568-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.065-.09-.076-.112-.076s-.067.01-.112.076a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.017zm.6.003a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.608.34l.001.001a2.46 2.46 0 0 0 2.114 1.077c1.248-.044 2.31-1.133 2.328-2.381a2.41 2.41 0 0 0-2.407-2.433h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.k-hxoxbhg {
  d: path("M23.137 25.375c0-.4.325-.731.726-.731h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.406-.657");
}

.k10lreb3f {
  stop-color: var(--svg-color--d8c4c9, #D8C4C9);
  stop-opacity: 0;
}

.k29z_pwdo {
  d: path("M20.296 4.155c.514.177.976.536 1.267 1.05a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.079-1.606a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.384-1.11a2.326 2.326 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.912-.188c.843 0 1.58.456 1.99 1.132c.307.51.79.88 1.352 1.073");
}

.k6cf6dbdc {
  stop-color: var(--svg-color--f67625, #F67625);
}

.kb4zjc5yz {
  stop-color: var(--svg-color--f89e42, #F89E42);
  stop-opacity: 0;
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.khdfr5bqk {
  stop-color: var(--svg-color--c4c58e, #C4C58E);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kua6vgb0k {
  fill: var(--svg-color--ffd335, #FFD335);
  d: path("M26.434 23.02c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.l2nok66dj {
  d: path("M23.825 23.878v-.469h.805a.234.234 0 0 1 0 .47z");
}

.l4lz-0bhl {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.404 9.6a.956.956 0 0 0 .083 1.879a78 78 0 0 1-.083-1.88");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lolok3p7w {
  stop-color: var(--svg-color--bd461c, #BD461C);
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lsz3g_boc {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m14.955 10.48l-.636 1.84c-.108.377.152.755.521.755h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.542-.408-.662 0");
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.lwgxwcc9p {
  stop-color: var(--svg-color--ebd4c9, #EBD4C9);
}

.m_gw8gbiz {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.403 11.487q.057-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mju0ocm_e {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.05 9.459c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.mrblk5hzh {
  d: path("m15.673 5.182l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.179.33-.252l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892v1.485z");
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mx0dy7bzm {
  d: path("M8.226 30.05V18.26c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.niz9gsbpv {
  d: path("M10.58 12.047a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.ow2dorb-x {
  fill: var(--svg-color--000, #000);
  d: path("M17.114 10.623c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.745h-.905a.46.46 0 0 1-.06-.235");
}

.oyvjs-x-y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.754 26.052h1.797");
}

.p2mir8bpk {
  stop-color: var(--svg-color--d2b4ed, #D2B4ED);
}

.p4jiy8bvo {
  stop-color: var(--svg-color--d48028, #D48028);
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q-fl22tnr {
  stop-color: var(--svg-color--cfbce6, #CFBCE6);
}

.q0589cc1h {
  d: path("M20.363 12.138q.1-1.595.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.qctpdhrvn {
  d: path("M22.753 30.05V18.26c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.qkpi96bvx {
  cx: 12.987px;
  cy: 10.112px;
  rx: 0.39px;
  ry: 0.197px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r3q9_wiir {
  d: path("M19.865 16.343a10.5 10.5 0 0 1 2.878 1.917v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.52z");
}

.r8xr7ubth {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.09 13.3c.39.202.855.32 1.35.32c.502 0 .961-.118 1.351-.32l.001-.001a.23.23 0 0 1 .27.045a.214.214 0 0 1 .024.272M14.09 13.3l2.934.276M14.09 13.3a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27m.295-.317l-.233.276m3.23.041l-.063-.041m.063.041l-.063-.041m.063.041c-.349.528-.956.88-1.646.88s-1.297-.352-1.646-.88m3.229-.041a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.584-.846m-.062.042l.062-.042m-.062.042v-.001l.062-.041");
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
}

.rmgd8acpv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.754 28.661h1.797");
}

.rnmqrkbhw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.676 27.357h1.797");
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.srv_dzbby {
  fill: var(--svg-color--9d3f1e, #9D3F1E);
  d: path("M19.174 8.161a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.121-1.212-.057a.277.277 0 0 0 .067.55c.481-.058.776-.028.979.036c.198.063.332.164.49.3a.277.277 0 0 0 .364-.418");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.su72xqoac {
  d: path("M15.466 15.41c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.tq9nmh6wg {
  d: path("M26.434 23.02c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.u7id6gble {
  stop-color: var(--svg-color--ffe945, #FFE945);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.utok7kzjw {
  d: path("M10.616 13.563a3.916 3.916 0 0 0 3.885 3.405h1.887a3.916 3.916 0 0 0 3.886-3.405c.118-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.117 3.691.239 5.557");
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.v7gluqbxb {
  d: path("M15.466 15.36h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vga2iwqpu {
  cx: 12.987px;
  cy: 10.112px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.vhmloyszq {
  stop-color: var(--svg-color--ee5231, #EE5231);
  stop-opacity: 0;
}

.vj4_95wuu {
  stop-color: var(--svg-color--a15002, #A15002);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w7mfp1z7m {
  d: path("M18.083 6.526h-5.275c-1.497 0-2.737 1.2-2.747 2.707a2.72 2.72 0 0 0 2.717 2.717c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.269 2.618-2.677a2.71 2.71 0 0 0-2.707-2.737");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wd79rybqt {
  d: path("m15.058 10.285l-.531 1.838c-.109.378.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.645-.407-.765 0");
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x7j0uibnq {
  d: path("M17.56 9.92c.063.084-.07.188-.221.301s-.264.193-.327.107c-.064-.085.007-.245.158-.358s.325-.136.39-.05");
}

.xazl-5b3q {
  d: path("M15.426 18.68a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xu2szrbjd {
  d: path("M11.114 16.343a10.5 10.5 0 0 0-2.878 1.917v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.52z");
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.xz_p9i_ao {
  fill: var(--svg-color--9d3f1e, #9D3F1E);
  d: path("M12.03 8.053a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.55a2.22 2.22 0 0 0-1.386.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.ydn9dmb6d {
  stop-color: var(--svg-color--ffe945, #FFE945);
  stop-opacity: 0;
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.yvvqshblb {
  d: path("m20.653 8.554l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.367c-.256-.97.67-1.713 1.655-1.522c.974.189 2.083.517 2.903 1.052c1.744 1.138 1.439 3.188.52 4.154");
}

.yywqu2bti {
  stop-color: var(--svg-color--ee5231, #EE5231);
}

.yzv5f8bpf {
  stop-color: var(--svg-color--e69b19, #E69B19);
}

.z_a2ribdx {
  stop-color: var(--svg-color--e7d3df, #E7D3DF);
  stop-opacity: 0;
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zehc2bc2m {
  d: path("m9.608 17.174l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .084.248l-.626.691a.5.5 0 0 0 .015.687l4.732 4.807a.2.2 0 0 0 .343-.14v-3.38c0-.282-.06-.562-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.zrtk-0btq {
  d: path("m21.02 18.204l.115 1.533a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.076.22l.554.612a.44.44 0 0 1-.012.607l-4.188 4.254a.177.177 0 0 1-.303-.124v-2.99c0-.25.053-.498.155-.726l2.306-5.135a9.4 9.4 0 0 1 2.31 1.11");
}

.ztn-0pg6n {
  d: path("m21.37 17.174l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.248l.626.691a.5.5 0 0 1-.014.687l-4.732 4.807a.2.2 0 0 1-.343-.14v-3.38c0-.282.06-.562.175-.82l2.606-5.803c.929.299 1.807.723 2.61 1.256");
}

</style>
