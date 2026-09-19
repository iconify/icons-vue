<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iWqBBOb)" class="fgk-5hbhi"/><path fill="url(#i0bnV8d)" class="fgk-5hbhi"/><path fill="url(#iKSChfb)" class="fgk-5hbhi"/><path fill="url(#iOgV9Cc)" class="fgk-5hbhi"/><path fill="url(#iREYwin)" class="fgk-5hbhi"/><path fill="url(#iP7xtVK)" class="jockr5brf"/><path fill="url(#iKXZx0b)" class="jockr5brf"/><g filter="url(#iMQN6jR)"><path fill="url(#iSGtb3c)" class="vscmdxbrb"/><path fill="url(#iVQ1hjc)" class="vscmdxbrb"/></g><path fill="url(#iEQBJ3d)" class="k8ix0jbxx"/><g filter="url(#iucuS4K)"><path fill="url(#iviLTSb)" class="u9lnei4em"/><path fill="url(#ikaDLwc)" class="u9lnei4em"/></g><g filter="url(#iU3f45d)"><path clip-rule="evenodd" class="wwr4rtl1i"/></g><path fill="url(#ivWFWhb)" class="hlyur2f6y"/><path fill="url(#ikgV5Dc)" class="hlyur2f6y"/><path fill="url(#iuTRW6b)" class="hlyur2f6y"/><path fill="url(#iRSaCgd)" class="hlyur2f6y"/><path fill="url(#i5AU1ke)" class="nfw87zbhc"/><path fill="url(#iCIUKvd)" class="nfw87zbhc"/><path fill="url(#iv7Upid)" class="nfw87zbhc"/><path fill="url(#iqxFvob)" class="nfw87zbhc"/><g filter="url(#iDS3L6s)"><path fill="url(#iWg0yye)" class="ceclfgb0n"/></g><g filter="url(#iFX3Yee)"><path fill="url(#imi6qCe)" class="dqu3jukjk"/></g><path fill="url(#igjxDfb)" class="dqu3jukjk"/><path fill="url(#i6QxIpL)" class="dqu3jukjk"/><path fill="url(#iZVvX9d)" class="dqu3jukjk"/><g filter="url(#i6suumd)"><path class="sodf0pb6f"/></g><g filter="url(#iB9KRtb)"><circle class="dr-k41b2k"/></g><g filter="url(#izpJFDc)"><circle class="uy8ok031y"/></g><g filter="url(#iTYla6b)"><circle fill="url(#iQWVlgf)" class="smrxvvbzr"/></g><g filter="url(#inOEeBd)"><circle fill="url(#i1xsAGY)" class="cnk20mb3o"/></g><rect fill="url(#iNeOwHd)" class="cydfracdw"/><rect fill="url(#irGrard)" class="cydfracdw"/><rect fill="url(#iYYnGDc)" class="cydfracdw"/><g filter="url(#iQMyDYc)"><path fill="url(#iHrAMlb)" class="sujgtsb5e"/></g><path fill="url(#iDvp61c)" class="sujgtsb5e"/><g filter="url(#irZKxIc)"><path class="srqurnicl"/><path fill="url(#i0fii8l)" class="b-ob-9e0x"/><path fill="url(#iGetuAc)" class="b-ob-9e0x"/><path fill="url(#iQbtvjb)" class="b-ob-9e0x"/></g><g filter="url(#ivHFVge)"><circle fill="url(#in03t1b)" class="x5prydbjk"/><circle fill="url(#iHjr1Ec)" class="x5prydbjk"/></g><path fill="url(#i0STnub)" class="hvla99b4n"/><path fill="url(#ipNySMd)" class="whyjhmtwu"/><g filter="url(#i095ABb)"><path fill="url(#iDiyslb)" class="ggnl389th"/></g><path fill="url(#iiV1s3d)" class="ggnl389th"/><path fill="url(#ikSyjpd)" class="ggnl389th"/><path fill="url(#iFUTExU)" class="ggnl389th"/><path fill="url(#ilaZUOe)" class="ggnl389th"/><path fill="url(#if6VKQU)" class="ggnl389th"/><path fill="url(#i1x5BEc)" class="ggnl389th"/><path fill="url(#iGjAUAe)" class="ggnl389th"/><g filter="url(#iBawzid)"><path class="h993svbub"/></g><g filter="url(#iowxiPb)"><path class="pzs5ucc9d"/><path fill="url(#ijMvfyA)" class="vivg6622c"/><path fill="url(#imj99je)" class="vivg6622c"/><path fill="url(#irwOwHQ)" class="vivg6622c"/><path fill="url(#ioQJoLb)" class="vivg6622c"/><path fill="url(#iaXISyd)" class="vivg6622c"/></g><g filter="url(#iDoojOd)"><path stroke="url(#if3Eehx)" class="dd-rjcb3m"/></g><path fill="url(#iyI0Xub)" class="bzu7d-b2o"/><g filter="url(#i3BOeZb)"><path fill="url(#iTwSjzb)" class="rapslbcuf"/><path fill="url(#iRQO2nc)" class="rapslbcuf"/><path fill="url(#i5fTKHo)" class="rapslbcuf"/><path fill="url(#iDTgfmb)" class="rapslbcuf"/><path fill="url(#iJNJMjg)" class="rapslbcuf"/></g><g filter="url(#i2dq89c)"><path class="km2q8jbnl"/></g><g filter="url(#iK5zebc)"><path class="udv71t5fb"/></g><g filter="url(#iwnM1yh)"><path class="buwski-lk"/><path fill="url(#iV7CBtb)" class="nkmkwkb5q"/><path fill="url(#iZQRWza)" class="nkmkwkb5q"/></g><g filter="url(#iYla74b)"><path class="tg1fenblu"/><path fill="url(#iYc4cne)" class="qk5s3pb2v"/></g><path class="q9paf9bvv"/><path fill="url(#iXaQJje)" class="grka2nbmu"/><path class="uazsvlbfo"/><g filter="url(#icF5Hmd)"><path class="rhi0plbpf"/><path fill="url(#inrSUec)" class="os4yqzbpk"/></g><g filter="url(#i6jfw8d)"><path fill="url(#iiPSOkc)" class="sjbbsbb4g"/></g><path class="yiljtcckc"/><path fill="url(#iBR4xqe)" class="ubo_j_b3z"/><path class="a70igrbyu"/><g filter="url(#iPmv1id)"><path fill="url(#iWqtFFe)" class="nv25vabuh"/></g><g filter="url(#iMkpTAz)"><ellipse transform="rotate(-27.914 13.594 9.923)" class="mzu8nv6ac"/><ellipse fill="url(#ial8N1b)" transform="rotate(-27.914 13.594 9.923)" class="k7k6u_23v"/></g><path fill="url(#ii7y9TC)" class="r4h7b5b2v"/><path fill="url(#icR5thb)" class="r4h7b5b2v"/><path fill="url(#iscdRdd)" class="r4h7b5b2v"/><path fill="url(#itvV9Fe)" class="r4h7b5b2v"/><path fill="url(#i1MfU4c)" class="qots95bzt"/><path fill="url(#iobljwb)" class="qots95bzt"/><g filter="url(#ip982Kd)"><path fill="url(#iPK3fdd)" class="injovkbeh"/></g><g filter="url(#iDym3te)"><path fill="url(#idWMIPc)" class="pqbwwgr5d"/></g><g filter="url(#iEIUVRc)"><path class="vzvoq2b2c"/></g><g filter="url(#iy8Z47D)"><path class="nlpqniehc"/></g><g filter="url(#i9LH7ni)"><path class="gp90v0bxg"/></g><defs><radialGradient id="iWqBBOb" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.316)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="i0bnV8d" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.77 10.813)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="iKSChfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.226)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iP7xtVK" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.242 2.61)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iKXZx0b" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.127)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="iSGtb3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.383)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="iEQBJ3d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.539)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="iviLTSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.508)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="ikaDLwc" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.348 13.025)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="ikgV5Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.104 8.356)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="iuTRW6b" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.648)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="iCIUKvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 .34376 -1.28105 5.18228 17.174 18.742)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iv7Upid" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .35156 -1.56152 -1.21452 17.276 19.382)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="imi6qCe" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.075 11.856)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="igjxDfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91838 1.78314 -4.30906 -2.21931 13.135 16.264)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="i6QxIpL" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94239 -.4885 0 11.747 16.322)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="iZVvX9d" cx="0" cy="0" r="1" gradientTransform="matrix(.0919 1.7035 -.36222 .01954 10.659 20.617)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iQWVlgf" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.875 16.043)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="i1xsAGY" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.493 14.54)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="irGrard" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 6.249 11.68)scale(2.36263 1.82529)" gradientUnits="userSpaceOnUse"><stop class="m_h8nlt2c"/><stop offset="1" class="ry4ntn_xd"/></radialGradient><radialGradient id="iYYnGDc" cx="0" cy="0" r="1" gradientTransform="rotate(-114.513 13.24 4.325)scale(2.1466 .74211)" gradientUnits="userSpaceOnUse"><stop class="gf3qz39cu"/><stop offset="1" class="gycts7b7d"/></radialGradient><radialGradient id="iHrAMlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.73)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="iDvp61c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.105)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="iGetuAc" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.439 6.855)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="iQbtvjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 18.96)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="in03t1b" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.375 12.583)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iHjr1Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.32)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="i0STnub" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.866 20.886)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="ipNySMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.991 12.366)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iDiyslb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.855 10.935)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="ikSyjpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.1344 -13.5313 0 16.267 4.971)" gradientUnits="userSpaceOnUse"><stop offset=".855" class="efxvdb-sz"/><stop offset="1" class="na2h5yb2i"/></radialGradient><radialGradient id="iFUTExU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.495 9.622)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="ilaZUOe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.48 11.923)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="if6VKQU" cx="0" cy="0" r="1" gradientTransform="matrix(4.073 -2.6483 .96946 1.491 10.58 6.61)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="i1x5BEc" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.146 13.838)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iGjAUAe" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.558 8.187)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="imj99je" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.514 12.295)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="ioQJoLb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.63 11.726)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iyI0Xub" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16.047 14.474)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iRQO2nc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.818 8.042)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="i5fTKHo" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.347 -6.263)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iDTgfmb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.154 3.076)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iJNJMjg" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 15.142 1.484)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iV7CBtb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.3 3.743)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iZQRWza" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.28 -5.788)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iYc4cne" cx="0" cy="0" r="1" gradientTransform="matrix(3.24822 .37966 -.15896 1.35996 17.795 6.08)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iXaQJje" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.23 10.018)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="inrSUec" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.475 .643)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBR4xqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.865 10.019)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ial8N1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.579 10.238)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="icR5thb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.665 10.033)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iscdRdd" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.026 10.577)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="itvV9Fe" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.14 10.75)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iobljwb" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.206 9.525)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iPK3fdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.06938 -.40422 11.133 10.675)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><filter id="iMQN6jR" width="4.081" height="11.683" x="5.07" y="18.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/></filter><filter id="iucuS4K" width="5.909" height="14.117" x="12.858" y="15.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/></filter><filter id="iU3f45d" width="7.13" height="5.229" x="12.285" y="16.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".3"/></filter><filter id="iDS3L6s" width="7.239" height="14.645" x="9.195" y="15.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".5"/></filter><filter id="iFX3Yee" width="5.917" height="14.31" x="10.326" y="15.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3323" result="effect2_innerShadow_4002_3323"/></filter><filter id="i6suumd" width="6.504" height="14.261" x="15.345" y="15.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3323" result="effect2_innerShadow_4002_3323"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3323" result="effect3_innerShadow_4002_3323"/></filter><filter id="iB9KRtb" width="2" height="2" x="14.731" y="24.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".25"/></filter><filter id="izpJFDc" width="2" height="2" x="14.731" y="21.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".25"/></filter><filter id="iTYla6b" width="1.05" height="1.05" x="15.504" y="25.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/></filter><filter id="inOEeBd" width="1.05" height="1.05" x="15.504" y="22.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/></filter><filter id="iQMyDYc" width="2.465" height="2.95" x="16.029" y="17.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3323" result="effect2_innerShadow_4002_3323"/></filter><filter id="irZKxIc" width="2.365" height="2.9" x="13.731" y="17.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/></filter><filter id="ivHFVge" width="1.717" height="1.717" x="15.204" y="17.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/></filter><filter id="i095ABb" width="11.22" height="12.542" x="10.984" y="4.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3323" result="effect2_innerShadow_4002_3323"/></filter><filter id="iBawzid" width="3.747" height="4.9" x="14.032" y="9.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".5"/></filter><filter id="iowxiPb" width="2.277" height="3.3" x="14.909" y="9.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".1"/></filter><filter id="iDoojOd" width="3.718" height="1.573" x="14.188" y="13.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".05"/></filter><filter id="i3BOeZb" width="12.873" height="8.356" x="9.611" y="1.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3323" result="effect2_innerShadow_4002_3323"/></filter><filter id="i2dq89c" width="2.339" height="1.19" x="17.637" y="7.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/></filter><filter id="iK5zebc" width="2.339" height="1.176" x="12.38" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/></filter><filter id="iwnM1yh" width="6.734" height="5.992" x="9.966" y="2.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/><feGaussianBlur result="effect2_foregroundBlur_4002_3323" stdDeviation=".125"/></filter><filter id="iYla74b" width="6.362" height="5.736" x="15.888" y="3.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3323"/><feGaussianBlur result="effect2_foregroundBlur_4002_3323" stdDeviation=".125"/></filter><filter id="icF5Hmd" width=".787" height=".696" x="17.495" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".05"/></filter><filter id="i6jfw8d" width=".891" height=".913" x="18.335" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".1"/></filter><filter id="iPmv1id" width=".986" height="1.04" x="13.892" y="9.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".1"/></filter><filter id="iMkpTAz" width=".913" height=".705" x="13.137" y="9.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".05"/></filter><filter id="ip982Kd" width="1.329" height="2.379" x="9.966" y="9.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".125"/></filter><filter id="iDym3te" width="1.947" height="2.903" x="20.49" y="9.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".25"/></filter><filter id="iEIUVRc" width="2.405" height="1.16" x="12.299" y="7.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".125"/></filter><filter id="iy8Z47D" width="2.405" height="1.16" x="17.578" y="7.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".125"/></filter><filter id="i9LH7ni" width="5.266" height="3.005" x="16.927" y="3.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3323" stdDeviation=".375"/></filter><linearGradient id="iOgV9Cc" x1="23.131" x2="22.971" y1="29.906" y2="29.906" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iREYwin" x1="8.858" x2="9.061" y1="29.906" y2="29.906" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iVQ1hjc" x1="9.19" x2="7.596" y1="29.913" y2="29.913" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="ivWFWhb" x1="14.705" x2="13.268" y1="19.976" y2="16.851" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="iRSaCgd" x1="15.518" x2="15.209" y1="20.054" y2="19.937" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="i5AU1ke" x1="16.799" x2="18.471" y1="19.992" y2="17.117" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="iqxFvob" x1="16.486" x2="16.713" y1="19.793" y2="19.703" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="iWg0yye" x1="12.815" x2="12.815" y1="16.773" y2="29.418" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="iNeOwHd" x1="17.033" x2="14.075" y1="18.382" y2="17.757" gradientUnits="userSpaceOnUse"><stop class="f6zsa320n"/><stop offset="1" class="i35cqvtse"/></linearGradient><linearGradient id="i0fii8l" x1="15.205" x2="14.838" y1="19.429" y2="18.976" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="iiV1s3d" x1="21.205" x2="16.852" y1="12.62" y2="12.62" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="ijMvfyA" x1="16.986" x2="16.047" y1="11.596" y2="11.644" gradientUnits="userSpaceOnUse"><stop class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="irwOwHQ" x1="16.047" x2="16.047" y1="12.749" y2="12.284" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iaXISyd" x1="16.047" x2="16.047" y1="9.794" y2="10.59" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="if3Eehx" x1="14.846" x2="15.164" y1="14.32" y2="13.485" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iTwSjzb" x1="22.899" x2="11.287" y1="5.272" y2="5.272" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iiPSOkc" x1="19.008" x2="18.694" y1="10.073" y2="10.266" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWqtFFe" x1="14.609" x2="14.296" y1="10.073" y2="10.266" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ii7y9TC" x1="22.484" x2="21.277" y1="10.1" y2="12.276" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="i1MfU4c" x1="10.198" x2="11.656" y1="10.803" y2="10.676" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="idWMIPc" x1="21.464" x2="21.464" y1="9.718" y2="11.621" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-tuxedo-dark" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.a70igrbyu {
  fill: var(--svg-color--000, #000);
  d: path("M14.375 10.434a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b-ob-9e0x {
  d: path("m14.133 17.475l1.813 1.251l-1.795 1.259a.246.246 0 0 1-.389-.187c-.04-.792-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.buwski-lk {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.28 5.319l-.066-.137a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.34 1.512-3.34 3.379v.275c-.34-.259-.769-.804-.769-1.688c0-1.072.782-1.613 1.28-1.959c.142-.097.26-.18.332-.253l.1-.105c.349-.37.971-1.031 2.059-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.893v1.485z");
}

.bzu7d-b2o {
  d: path("M16.047 13.832c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.279-.198-.209a3 3 0 0 1-1.386.329");
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ceclfgb0n {
  d: path("M11.242 18.34c-.03-1.011.55-1.42.819-1.502l.617-.065v5.373c0 3.575.239 4.662 2.733 7.12l.011.015c.047.082-.05.176-.132.12c-2.75-1.881-4.776-3.354-5.094-8.18a.19.19 0 0 1 .174-.198c.297-.02.56-.044.747-.061a.19.19 0 0 0 .171-.191c-.01-.53-.02-1.532-.046-2.431");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cnk20mb3o {
  cx: 16.004px;
  cy: 22.567px;
  r: 0.5px;
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.cydfracdw {
  width: 3.875px;
  height: 4.5px;
  x: 14.075px;
  y: 14.281px;
  rx: 1.938px;
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dd-rjcb3m {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.697 13.437h-.001a.23.23 0 0 0-.271.046a.21.21 0 0 0-.023.271c.348.528.955.88 1.645.88s1.298-.353 1.646-.88a.214.214 0 0 0-.023-.273a.23.23 0 0 0-.271-.045c-.39.204-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dqu3jukjk {
  d: path("M11.709 17.543c-.032-1.094.595-1.537.886-1.625l.668-.07v5.815c0 3.873 1.453 6.261 2.712 8.087c.063.09-.047.2-.138.138c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.066c.107-.01.188-.1.186-.206c-.011-.575-.023-1.659-.05-2.632");
}

.dr-k41b2k {
  cx: 15.731px;
  cy: 25.848px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.efxvdb-sz {
  stop-color: var(--svg-color--3b1e2f, #3B1E2F);
  stop-opacity: 0;
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f6zsa320n {
  stop-color: var(--svg-color--3a2226, #3A2226);
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fgk-5hbhi {
  d: path("M5.07 26.41c0-5.797 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.823 10.5 10.62v3.496H5.07z");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gf3qz39cu {
  stop-color: var(--svg-color--3e292a, #3E292A);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ggnl389th {
  d: path("M11.223 13.7a3.916 3.916 0 0 0 3.885 3.406h1.887A3.916 3.916 0 0 0 20.88 13.7c.117-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.442a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.342 1.513-3.342 3.38c0 1.86.117 3.69.239 5.556");
}

.gp90v0bxg {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.24 5.336h-2.08a.483.483 0 1 1 .076-.96c.54.085 1.257.205 1.737.324c1.086.27 1.386.798 1.47 1.175a1.51 1.51 0 0 0-1.203-.539");
}

.grka2nbmu {
  d: path("M18.232 9.542a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.gycts7b7d {
  stop-color: var(--svg-color--3e292a, #3E292A);
  stop-opacity: 0;
}

.h993svbub {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.646 10.416l-.59 1.838c-.102.378.14.756.484.756h.731c.343 0 .586-.384.485-.756l-.495-1.838c-.106-.408-.504-.408-.615 0");
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hlyur2f6y {
  d: path("M14.41 20.277c-1.185-1.235-1.403-3.047-1.367-3.871h2.969l.035 2.222l-.773 1.52c-.148.308-.608.394-.863.129");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hvla99b4n {
  d: path("M20.909 12.185a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.019q.257-.546.345-1.18z");
}

.i35cqvtse {
  stop-color: var(--svg-color--2e161d, #2E161D);
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.injovkbeh {
  d: path("M10.962 9.736a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jockr5brf {
  d: path("M23.099 18.23a10.68 10.68 0 0 1 3.831 8.18v3.496H23.1z");
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.k7k6u_23v {
  cx: 13.594px;
  cy: 9.923px;
  rx: 0.39px;
  ry: 0.197px;
}

.k8ix0jbxx {
  d: path("M8.901 18.23a10.68 10.68 0 0 0-3.831 8.18v3.496H8.9z");
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.km2q8jbnl {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.78 7.955a1.85 1.85 0 0 0-.687-.411c-.305-.096-.686-.122-1.213-.057a.277.277 0 1 0 .068.55c.48-.059.776-.028.978.036c.199.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m_h8nlt2c {
  stop-color: var(--svg-color--412727, #412727);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mzu8nv6ac {
  cx: 13.594px;
  cy: 9.923px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.na2h5yb2i {
  stop-color: var(--svg-color--3c183d, #3C183D);
}

.nfw87zbhc {
  d: path("M17.598 20.277c1.186-1.235 1.404-3.047 1.367-3.871h-2.968l-.036 2.222l.774 1.52c.148.308.608.394.863.129");
}

.nkmkwkb5q {
  d: path("m16.28 5.319l-.066-.137a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.34 1.512-3.34 3.379v.275c-.34-.259-.769-.804-.769-1.688c0-1.072.782-1.613 1.28-1.959c.142-.097.26-.18.332-.253l.1-.105c.349-.37.971-1.031 2.059-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.893v1.485z");
}

.nlpqniehc {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.609 8.08c-.258-.185-.898-.51-1.656-.382");
}

.nv25vabuh {
  d: path("M14.679 10.33c0-.29-.235-.481-.298-.54l-.289.28l.178.36z");
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.os4yqzbpk {
  d: path("M18.166 9.73c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqbwwgr5d {
  d: path("M20.99 11.621q.059-.951.111-1.903a.956.956 0 0 1-.11 1.903");
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.pzs5ucc9d {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.665 10.22l-.531 1.838c-.109.379.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q9paf9bvv {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.438 9.27c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.341h-2.232a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.371-1.127");
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qk5s3pb2v {
  d: path("m21.26 8.586l-.029-.631c-.01-.764-.642-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
}

.qots95bzt {
  d: path("M10.993 9.076a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4h7b5b2v {
  d: path("M20.97 12.276q.1-1.595.184-3.192a1.61 1.61 0 0 1-.185 3.192");
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rapslbcuf {
  d: path("M20.902 4.292a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.875v1.188a1.7 1.7 0 0 0-.668-.268l.078-1.607a1.45 1.45 0 0 0-1.378-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.34 1.512-3.34 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.445a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.193 0c.282-.118.59-.188.913-.188c.843 0 1.58.456 1.989 1.132c.307.51.79.88 1.352 1.073");
}

.rhi0plbpf {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.166 9.73c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.ry4ntn_xd {
  stop-color: var(--svg-color--412727, #412727);
  stop-opacity: 0;
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sjbbsbb4g {
  d: path("M19.027 10.317a.84.84 0 0 0-.232-.463l-.26.285l.117.228z");
}

.smrxvvbzr {
  cx: 16.004px;
  cy: 25.575px;
  r: 0.5px;
}

.sodf0pb6f {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.316 17.543c.031-1.094-.595-1.537-.887-1.625l-.668-.07v5.815c0 3.873-1.388 6.263-2.648 8.089c-.062.091.047.2.139.138c2.976-2.036 4.851-4.005 5.196-9.228a.203.203 0 0 0-.188-.215c-.321-.02-.607-.047-.809-.066a.204.204 0 0 1-.185-.206c.011-.575.022-1.659.05-2.632");
}

.srqurnicl {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.475l1.813 1.251l-1.795 1.259a.246.246 0 0 1-.389-.187c-.04-.792-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.sujgtsb5e {
  d: path("m17.892 17.475l-1.813 1.251l1.795 1.259a.246.246 0 0 0 .388-.187c.041-.792.041-1.57.008-2.144a.239.239 0 0 0-.378-.179");
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tg1fenblu {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.26 8.586l-.029-.631c-.01-.764-.642-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.u9lnei4em {
  d: path("M18.767 16.057a10.3 10.3 0 0 0-2.337-.267h-.86a10.3 10.3 0 0 0-2.312.261v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.46 2.57-4.258 2.57-8.433z");
}

.uazsvlbfo {
  fill: var(--svg-color--000, #000);
  d: path("M17.72 10.434a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.ubo_j_b3z {
  d: path("M13.863 9.542a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.udv71t5fb {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.637 7.846a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uy8ok031y {
  cx: 15.731px;
  cy: 22.7px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vivg6622c {
  d: path("m15.665 10.22l-.531 1.838c-.109.379.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.vscmdxbrb {
  d: path("M8.901 18.23a10.69 10.69 0 0 0-3.831 8.185v3.498H8.9z");
}

.vzvoq2b2c {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.674 8.126c.257-.185.898-.51 1.655-.382");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.whyjhmtwu {
  d: path("M11.186 12.185a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wwr4rtl1i {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.68c-.037.825.18 2.636 1.367 3.871c.255.266.715.18.863-.129l.73-1.435l.731 1.435c.149.309.608.395.863.13c1.186-1.236 1.404-3.047 1.368-3.872z");
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x5prydbjk {
  cx: 16.012px;
  cy: 18.695px;
  r: 0.809px;
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.yiljtcckc {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.657 9.27c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341H14.8a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.372-1.127");
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
