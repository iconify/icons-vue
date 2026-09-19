<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ib6wMeb)" class="nxua_f4_x"/><path fill="url(#iQYE5Vd)" class="nxua_f4_x"/><path fill="url(#ig6T4TV)" class="nxua_f4_x"/><path fill="url(#ieZhbTF)" class="nxua_f4_x"/><path fill="url(#i9nkage)" class="nxua_f4_x"/><path fill="url(#iXP0yed)" class="nxua_f4_x"/><path fill="url(#iU53mke)" class="nxua_f4_x"/><path fill="url(#iz5mzzb)" class="nxua_f4_x"/><path fill="url(#i05CM9c)" class="nxua_f4_x"/><path fill="url(#i8cff8c)" class="nxua_f4_x"/><path fill="url(#i1j5hqe)" class="nxua_f4_x"/><path fill="url(#iZxOZFc)" class="axschur8l"/><path fill="url(#i8cVBrb)" class="axschur8l"/><path class="y-2q9rb0t"/><path fill="url(#iErERRK)" class="iv9zqpbet"/><path fill="url(#isjJ6Kb)" class="iv9zqpbet"/><path fill="url(#iE2nPAd)" class="pbii7_bty"/><path fill="url(#ibFB1LQ)" class="pbii7_bty"/><path fill="url(#icS8P6u)" class="pbii7_bty"/><path fill="url(#iPtlhCc)" class="pbii7_bty"/><path fill="url(#ijWYvZd)" class="iv9zqpbet"/><path fill="url(#iH1dbZd)" class="u0nta8sqa"/><path fill="url(#i2hrVWd)" class="u0nta8sqa"/><g filter="url(#iQ1269b)"><path stroke="url(#iFi7o0c)" class="ah3x-vc6h"/></g><g filter="url(#iytxzle)"><path stroke="url(#i1YjJye)" class="nhv4sxnyk"/></g><g filter="url(#i477aRf)"><path stroke="url(#iQTfFgd)" class="qqgo0qblt"/></g><g filter="url(#i6oPtyc)"><path stroke="url(#i8BgxEH)" class="wc4yoe1cm"/></g><g filter="url(#iBNZnQm)"><path stroke="url(#iRWPkvb)" class="dehel_b5n"/></g><g filter="url(#icLuCHe)"><path stroke="url(#iWpImGd)" class="h8omb2b8w"/></g><g filter="url(#ihUHt2c)"><path stroke="url(#iaQlUWc)" class="hk6ysobgg"/></g><g filter="url(#iRoWdrm)"><path stroke="url(#i5Dxnbb)" class="yecivi0wh"/></g><g filter="url(#iTCph2N)"><path stroke="url(#iJ908Lc)" class="fr81f4bug"/></g><g filter="url(#ilpfZsb)"><path stroke="url(#iWbAGvb)" class="q3dsuwb-s"/></g><g filter="url(#i7QEldb)"><path stroke="url(#iFB4GVd)" class="u-bujtbll"/></g><path fill="url(#iSBqA4d)" class="u_dqezktl"/><path fill="url(#i4OviUc)" class="sb0d27qfu"/><g filter="url(#icFuSqe)"><path fill="url(#iWTjZ3c)" class="adpwv9fyc"/><path fill="url(#inHcWbc)" class="adpwv9fyc"/></g><path fill="url(#iduWV0b)" class="adpwv9fyc"/><path fill="url(#irbF2sc)" class="adpwv9fyc"/><path fill="url(#iZ3yBMe)" class="adpwv9fyc"/><path fill="url(#iwMVvsb)" class="adpwv9fyc"/><path fill="url(#iz1CfSl)" class="adpwv9fyc"/><path fill="url(#io38GGc)" class="adpwv9fyc"/><path fill="url(#igMINsb)" class="adpwv9fyc"/><g filter="url(#iIKFzMd)"><path class="t5j04cb_m"/></g><g filter="url(#incZZHe)"><path class="yzcdtkbjq"/><path fill="url(#ik8cFQe)" class="ptcv1djxr"/><path fill="url(#iTxcVAc)" class="ptcv1djxr"/><path fill="url(#iB4mkze)" class="ptcv1djxr"/><path fill="url(#iPXFf9b)" class="ptcv1djxr"/><path fill="url(#iEwu69Z)" class="ptcv1djxr"/></g><path fill="url(#i7NtHZc)" class="ptcv1djxr"/><path fill="url(#imdMLNd)" class="ptcv1djxr"/><g filter="url(#iXNqxne)"><path stroke="url(#iwL7sxc)" class="m8fjaubhi"/></g><path fill="url(#iGXhSdc)" class="md-v7ib7j"/><g filter="url(#icf2Mdb)"><path fill="url(#i2xKpkb)" class="iedexoy6o"/><path fill="url(#id8pskd)" class="iedexoy6o"/><path fill="url(#i8pfbqd)" class="iedexoy6o"/><path fill="url(#isvXTbe)" class="iedexoy6o"/><path fill="url(#iZTappd)" class="iedexoy6o"/></g><g filter="url(#i1NWWvd)"><path class="ermwcyb0i"/></g><g filter="url(#iDNL1xa)"><path class="v9m6mufix"/></g><g filter="url(#i13AnBb)"><path class="lj4eu7bxk"/><path fill="url(#icX6mxc)" class="czyribbpw"/><path fill="url(#iWxEqkc)" class="czyribbpw"/></g><g filter="url(#iwBzTLd)"><path class="nwhtltdqd"/><path fill="url(#iX8Y80b)" class="m9entvb6m"/><path fill="url(#i41ofFe)" class="m9entvb6m"/></g><path class="dzvn8lb4g"/><path fill="url(#i6ewwHb)" class="q8h9rabnk"/><path class="hm8ezbcid"/><g filter="url(#i1ITNJz)"><path class="fumg9gzux"/><path fill="url(#iAGYVJd)" class="yp0dscc5o"/></g><g filter="url(#iXgWTCd)"><path fill="url(#iTYjAkd)" class="qk4glw74i"/></g><path class="z780zkb0h"/><path fill="url(#iLu2Bye)" class="xfyzhiubb"/><path class="gdv6sqblu"/><g filter="url(#iRpESab)"><path fill="url(#iFBAIJb)" class="mhv89pbbq"/></g><g filter="url(#iGi6DVd)"><ellipse transform="rotate(-27.914 16.109 12.977)" class="an6hvgv8j"/><ellipse fill="url(#idhsEgd)" transform="rotate(-27.914 16.109 12.977)" class="p2wqo_bck"/></g><path fill="url(#i1cSIbc)" class="p2mr7sbov"/><path fill="url(#inRO3ee)" class="p2mr7sbov"/><path fill="url(#iFMF21c)" class="p2mr7sbov"/><path fill="url(#ii5Bmwc)" class="p2mr7sbov"/><path fill="url(#iO5Rnmd)" class="zmi22ab_n"/><path fill="url(#i1xAkTd)" class="zmi22ab_n"/><g filter="url(#igw0Sud)"><path fill="url(#iMp8D8c)" class="ir7rnkbkd"/></g><g filter="url(#iGKMCmc)"><path fill="url(#iv4EOfb)" class="s6fofcbba"/></g><g filter="url(#ipLx2Lc)"><path class="e197srbrw"/></g><g filter="url(#inETfZc)"><path class="fp8f84b7r"/></g><g filter="url(#i5E6evk)"><path class="ith5l9r9j"/></g><defs><radialGradient id="ib6wMeb" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 5.871 11.857)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="o-iirh5hj"/><stop offset="1" class="b4grpcbtk"/></radialGradient><radialGradient id="iQYE5Vd" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 2.783 7.307)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="nui0_5bvt"/><stop offset="1" class="aijb2v7yw"/></radialGradient><radialGradient id="ieZhbTF" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 4.596 5.044)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="tvgnczn8r"/><stop offset="1" class="fj2hmbbmv"/></radialGradient><radialGradient id="i9nkage" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 6.245 3.88)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="tvgnczn8r"/><stop offset="1" class="fj2hmbbmv"/></radialGradient><radialGradient id="iXP0yed" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 3.96875 -.56716 -.09602 8.213 3.114)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="tvgnczn8r"/><stop offset="1" class="fj2hmbbmv"/></radialGradient><radialGradient id="iU53mke" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 9.712 3.475)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="iz5mzzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 7.785 2.448)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="i05CM9c" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.583 3.926)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="i8cff8c" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 3.97 4.262)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="i1j5hqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.88951 .77545 -.60682 -.69608 11.752 7.115)" gradientUnits="userSpaceOnUse"><stop class="bq0xhibbj"/><stop offset="1" class="khbnhvbup"/></radialGradient><radialGradient id="iErERRK" cx="0" cy="0" r="1" gradientTransform="matrix(-8.71543 2.79839 -2.98394 -9.29332 26.183 27.175)" gradientUnits="userSpaceOnUse"><stop class="ip469ff8c"/><stop offset="1" class="v0q_-i93u"/></radialGradient><radialGradient id="isjJ6Kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.62502 2.66619 0 10.916 29.974)" gradientUnits="userSpaceOnUse"><stop class="xjv40os-m"/><stop offset="1" class="yrxkt-bta"/></radialGradient><radialGradient id="ibFB1LQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -5.4375 0 2.979 12.974)" gradientUnits="userSpaceOnUse"><stop class="ya78f26qa"/><stop offset="1" class="jfma4ebms"/></radialGradient><radialGradient id="icS8P6u" cx="0" cy="0" r="1" gradientTransform="matrix(-7.94466 -1.83797 .619 -2.67566 16.993 21.276)" gradientUnits="userSpaceOnUse"><stop class="q2kyq2xrt"/><stop offset="1" class="wogt4ot2h"/></radialGradient><radialGradient id="ijWYvZd" cx="0" cy="0" r="1" gradientTransform="rotate(101.634 -.2 15.88)scale(4.33914 9.98002)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="l24x8zb-x"/><stop offset="1" class="chnw0fb8n"/></radialGradient><radialGradient id="i2hrVWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92844 -1.58228 0 19.011 21.161)" gradientUnits="userSpaceOnUse"><stop class="no8c23uva"/><stop offset="1" class="g60jnfzma"/></radialGradient><radialGradient id="iSBqA4d" cx="0" cy="0" r="1" gradientTransform="matrix(.88576 2.38902 -2.83797 1.05222 24.634 15.288)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="i4OviUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.7466 .54892 -1.69346 5.38834 11.846 15.867)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iWTjZ3c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.18431 0 0 -10.94 22.332 14.174)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="inHcWbc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 8.605 10.312)scale(3.98535 3.29023)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="irbF2sc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.68882 8.71742 0 18.99 21.733)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="iZ3yBMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.35845 1.68108 0 21.906 12.62)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iwMVvsb" cx="0" cy="0" r="1" gradientTransform="matrix(.00465 -1.29448 1.4087 .00506 16.29 12.676)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iz1CfSl" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 11.294 8.035)scale(10.0704 25.7247)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="io38GGc" cx="0" cy="0" r="1" gradientTransform="matrix(4.00524 -3.45004 1.01909 1.18308 10.976 10.94)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="igMINsb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2776 2.95435 -1.18098 -.11097 25.57 10.723)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iTxcVAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .28876 -.90754 0 19.563 15.784)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iPXFf9b" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 8.2 9.705)scale(1.97957 3.18132)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="imdMLNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51683 1.44744 -2.089 -2.18915 19.523 14.768)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="iGXhSdc" cx="0" cy="0" r="1" gradientTransform="matrix(2.58118 -1.26898 5.10546 10.38476 18.43 18.46)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="id8pskd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.14191 10.4744 0 12.825 10.752)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="i8pfbqd" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 18.817 -6.804)scale(2.97528 5.27161)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="isvXTbe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.79039 -1.83524 1.34716 -2.04829 23.869 4.878)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iZTappd" cx="0" cy="0" r="1" gradientTransform="matrix(.79455 1.41744 -3.28214 1.83982 17.94 2.994)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="icX6mxc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.60383 0 0 -.96638 19.311 5.667)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iWxEqkc" cx="0" cy="0" r="1" gradientTransform="matrix(3.80699 -6.02764 6.678 4.21775 12.587 10.33)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iX8Y80b" cx="0" cy="0" r="1" gradientTransform="matrix(3.1688 -3.0191 5.5272 5.80128 22.127 10.179)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="i41ofFe" cx="0" cy="0" r="1" gradientTransform="matrix(3.8425 .44912 -.18804 1.60878 21.079 8.432)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i6ewwHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .95975 -1.5266 0 21.593 13.09)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iAGYVJd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.891 1.373)scale(.4475 .61609)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLu2Bye" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9598 -1.52667 0 16.43 13.09)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="idhsEgd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00915 -.58448 .70257 -.011 16.091 13.35)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="inRO3ee" cx="0" cy="0" r="1" gradientTransform="matrix(.74355 2.65369 -2.53182 .7094 24.474 13.106)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iFMF21c" cx="0" cy="0" r="1" gradientTransform="matrix(.9319 -1.2789 1.07197 .78113 24.9 13.75)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="ii5Bmwc" cx="0" cy="0" r="1" gradientTransform="matrix(.6944 -1.83408 2.45058 .9278 25.035 13.955)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="i1xAkTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96164 0 0 -2.19045 13.196 13.865)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iMp8D8c" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 6.008 7.496)scale(1.10001 1.12785)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><linearGradient id="ig6T4TV" x1="6.354" x2="6.354" y1="12.518" y2="10.815" gradientUnits="userSpaceOnUse"><stop class="yt_0wt3yl"/><stop offset="1" class="eujvqlb2y"/></linearGradient><linearGradient id="iZxOZFc" x1="4.197" x2="8.572" y1="12.536" y2="12.536" gradientUnits="userSpaceOnUse"><stop class="zmcsd8b9p"/><stop offset=".743" class="zdo6gqojl"/></linearGradient><linearGradient id="i8cVBrb" x1="6.467" x2="6.467" y1="11.95" y2="12.208" gradientUnits="userSpaceOnUse"><stop class="p4ezwj49r"/><stop offset="1" class="q3td6tqwm"/></linearGradient><linearGradient id="iE2nPAd" x1="9.464" x2="11.42" y1="26.642" y2="20.357" gradientUnits="userSpaceOnUse"><stop class="b05_udben"/><stop offset="1" class="a91fxs_hx"/></linearGradient><linearGradient id="iPtlhCc" x1="13.703" x2="13.313" y1="24.418" y2="23.808" gradientUnits="userSpaceOnUse"><stop offset=".312" class="b2wdmyb-l"/><stop offset="1" class="pmtca2xis"/></linearGradient><linearGradient id="iH1dbZd" x1="17.281" x2="20.688" y1="21.058" y2="23.974" gradientUnits="userSpaceOnUse"><stop class="w5wis0b3d"/><stop offset="1" class="vthu1ccss"/></linearGradient><linearGradient id="iFi7o0c" x1="7.01" x2="12.76" y1="15.255" y2="23.536" gradientUnits="userSpaceOnUse"><stop class="gokcfhb1a"/><stop offset="1" class="sq9q63bos"/></linearGradient><linearGradient id="i1YjJye" x1="4.844" x2="4.853" y1="5.211" y2="7.213" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="iQTfFgd" x1="6.264" x2="6.291" y1="4.782" y2="7.146" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="i8BgxEH" x1="8.023" x2="8.026" y1="5.382" y2="6.829" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="iRWPkvb" x1="3.609" x2="4.029" y1="5.324" y2="7.931" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="iWpImGd" x1="4.754" x2="4.966" y1="4.451" y2="7.574" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="iaQlUWc" x1="6.903" x2="8.006" y1="3.694" y2="7.371" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="i5Dxnbb" x1="7.858" x2="8.174" y1="4.644" y2="8.075" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="iJ908Lc" x1="4.904" x2="3.812" y1="7.191" y2="7.123" gradientUnits="userSpaceOnUse"><stop class="s6abn5boy"/><stop offset="1" class="q7h19xvvk"/></linearGradient><linearGradient id="iWbAGvb" x1="6.176" x2="5.612" y1="7.019" y2="6.878" gradientUnits="userSpaceOnUse"><stop class="s6abn5boy"/><stop offset="1" class="q7h19xvvk"/></linearGradient><linearGradient id="iFB4GVd" x1="7.677" x2="6.874" y1="6.832" y2="6.619" gradientUnits="userSpaceOnUse"><stop class="s6abn5boy"/><stop offset="1" class="q7h19xvvk"/></linearGradient><linearGradient id="iduWV0b" x1="25.112" x2="22.12" y1="16.168" y2="16.168" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="ik8cFQe" x1="20.003" x2="19.011" y1="14.972" y2="15.013" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iB4mkze" x1="19.011" x2="19.011" y1="16.32" y2="15.77" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iEwu69Z" x1="19.011" x2="19.011" y1="13.12" y2="13.766" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="i7NtHZc" x1="19.503" x2="19.503" y1="16.483" y2="16.255" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="iwL7sxc" x1="17.59" x2="17.966" y1="18.178" y2="17.191" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="i2xKpkb" x1="27.117" x2="13.38" y1="7.475" y2="7.475" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iTYjAkd" x1="22.513" x2="22.142" y1="13.154" y2="13.383" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFBAIJb" x1="17.31" x2="16.939" y1="13.154" y2="13.383" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1cSIbc" x1="26.625" x2="25.197" y1="13.186" y2="15.76" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iO5Rnmd" x1="12.091" x2="13.816" y1="14.018" y2="13.868" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iv4EOfb" x1="25.418" x2="25.418" y1="12.734" y2="14.986" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><filter id="iQ1269b" width="9.217" height="12.757" x="5.354" y="12.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".75"/></filter><filter id="iytxzle" width=".423" height="2.22" x="4.45" y="5.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".05"/></filter><filter id="i477aRf" width=".345" height="2.572" x="6.005" y="4.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".05"/></filter><filter id="i6oPtyc" width=".509" height="1.681" x="7.482" y="5.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".05"/></filter><filter id="iBNZnQm" width="1.556" height="3.487" x="3.316" y="4.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".2"/></filter><filter id="icLuCHe" width="1.2" height="3.889" x="5.002" y="3.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".2"/></filter><filter id="ihUHt2c" width="1.488" height="4.773" x="6.549" y="2.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".2"/></filter><filter id="iRoWdrm" width="2.002" height="4.299" x="7.952" y="3.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".2"/></filter><filter id="iTCph2N" width="1.413" height="1.358" x="3.606" y="6.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".1"/></filter><filter id="ilpfZsb" width="1.118" height=".999" x="5.255" y="6.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".1"/></filter><filter id="i7QEldb" width="1.312" height="1.023" x="6.52" y="6.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".1"/></filter><filter id="icFuSqe" width="13.09" height="14.8" x="13.021" y="6.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3865"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3865" result="effect2_innerShadow_4002_3865"/></filter><filter id="iIKFzMd" width="4.066" height="5.431" x="16.81" y="12.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".5"/></filter><filter id="incZZHe" width="2.621" height="3.831" x="17.701" y="12.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".1"/></filter><filter id="iXNqxne" width="4.307" height="1.769" x="16.858" y="16.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".05"/></filter><filter id="icf2Mdb" width="15.228" height="9.794" x="11.397" y="3.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3865"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3865" result="effect2_innerShadow_4002_3865"/></filter><filter id="i1NWWvd" width="2.748" height="1.372" x="20.891" y="9.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3865"/></filter><filter id="iDNL1xa" width="2.748" height="1.354" x="14.673" y="9.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3865"/></filter><filter id="i13AnBb" width="8.198" height="7.497" x="11.614" y="4.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3865"/><feGaussianBlur result="effect2_foregroundBlur_4002_3865" stdDeviation=".25"/></filter><filter id="iwBzTLd" width="7.93" height="7.218" x="18.573" y="4.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".25"/></filter><filter id="i1ITNJz" width=".894" height=".787" x="20.742" y="12.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".05"/></filter><filter id="iXgWTCd" width=".981" height="1.007" x="21.754" y="12.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".1"/></filter><filter id="iRpESab" width="1.094" height="1.157" x="16.499" y="12.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".1"/></filter><filter id="iGi6DVd" width="1.044" height=".797" x="15.587" y="12.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".05"/></filter><filter id="igw0Sud" width="1.481" height="2.723" x="11.864" y="12.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".125"/></filter><filter id="iGKMCmc" width="2.12" height="3.252" x="24.358" y="12.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".25"/></filter><filter id="ipLx2Lc" width="2.708" height="1.235" x="14.646" y="9.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".125"/></filter><filter id="inETfZc" width="2.708" height="1.235" x="20.891" y="9.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".125"/></filter><filter id="i5E6evk" width="6.455" height="3.781" x="19.939" y="5.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3865" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-raising-hand-medium-dark" /></template>
<style>
.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.a91fxs_hx {
  stop-color: var(--svg-color--ff4b54, #FF4B54);
  stop-opacity: 0;
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.adpwv9fyc {
  d: path("M13.303 17.445a4.63 4.63 0 0 0 4.597 4.029h2.232a4.63 4.63 0 0 0 4.596-4.03c.14-2.228.28-4.447.384-6.674a1.715 1.715 0 0 0-1.631-1.694h-1.657a2.87 2.87 0 0 1-2.616-1.707a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.953 1.79-3.953 3.997c0 2.201.138 4.367.282 6.574");
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ah3x-vc6h {
  d: path("M7.354 13.63v6.017a2 2 0 0 0 1.38 1.902l4.182 1.362");
}

.aijb2v7yw {
  stop-color: var(--svg-color--6a413b, #6A413B);
  stop-opacity: 0;
}

.an6hvgv8j {
  cx: 16.109px;
  cy: 12.977px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.461px;
  ry: 0.233px;
}

.axschur8l {
  d: path("M4.361 12.15c0-.11.09-.2.2-.2h3.811c.11 0 .2.09.2.2v1.714h-4.21z");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b05_udben {
  stop-color: var(--svg-color--ff4b54, #FF4B54);
}

.b2wdmyb-l {
  stop-color: var(--svg-color--ff611d, #FF611D);
}

.b4grpcbtk {
  stop-color: var(--svg-color--7a544a, #7A544A);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bq0xhibbj {
  stop-color: var(--svg-color--866a60, #866A60);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.chnw0fb8n {
  stop-color: var(--svg-color--b64318, #B64318);
  stop-opacity: 0;
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ct57ro4xv {
  stop-color: var(--svg-color--95766f, #95766F);
  stop-opacity: 0;
}

.czyribbpw {
  d: path("M19.286 7.53a3 3 0 0 1-.078-.161a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.952 1.79-3.952 3.997v.326c-.403-.306-.909-.952-.909-1.997c0-1.268.925-1.909 1.515-2.317c.167-.116.306-.213.391-.3l.118-.124c.414-.438 1.15-1.22 2.437-1.561a6.6 6.6 0 0 1 1.932-.19c.472.02.805.429.805.902v1.905z");
}

.dehel_b5n {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m3.914 4.847l.36 2.633");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dzvn8lb4g {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.84 12.204c.772 0 1.425.533 1.602 1.253a.324.324 0 0 1-.316.403h-2.64a.272.272 0 0 1-.268-.322a1.654 1.654 0 0 1 1.622-1.334");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e197srbrw {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.02 10.851c.305-.218 1.063-.602 1.959-.451");
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.ermwcyb0i {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M23.427 10.649c-.207-.18-.448-.372-.813-.487c-.36-.113-.811-.143-1.435-.067a.328.328 0 0 0 .08.651c.57-.07.918-.033 1.158.042c.234.074.393.194.579.356a.328.328 0 1 0 .43-.495");
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.eujvqlb2y {
  stop-color: var(--svg-color--724130, #724130);
  stop-opacity: 0;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fj2hmbbmv {
  stop-color: var(--svg-color--714131, #714131);
  stop-opacity: 0;
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.fp8f84b7r {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.224 10.796c-.304-.218-1.062-.601-1.958-.45");
}

.fr81f4bug {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M3.906 7.996c.11-.063.617-.379.813-.758");
}

.ft5dv1b6b {
  fill: none;
}

.fumg9gzux {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.517 12.749c.076.1-.082.223-.26.357c-.18.133-.312.228-.387.127c-.075-.1.009-.29.187-.424c.18-.134.385-.16.46-.06");
}

.g60jnfzma {
  stop-color: var(--svg-color--703a49, #703A49);
  stop-opacity: 0;
}

.gdv6sqblu {
  fill: var(--svg-color--000, #000);
  d: path("M17.032 13.582a.6.6 0 0 0-.604-.605a.602.602 0 0 0-.538.883h1.07a.6.6 0 0 0 .072-.278");
}

.gokcfhb1a {
  stop-color: var(--svg-color--ff7636, #FF7636);
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h8omb2b8w {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.602 3.892V6.98");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
}

.hk6ysobgg {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.438 2.98l-.29 3.944");
}

.hm8ezbcid {
  fill: var(--svg-color--000, #000);
  d: path("M20.99 13.582c0-.336.269-.605.605-.605a.602.602 0 0 1 .537.883h-1.07a.55.55 0 0 1-.072-.278");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.i3e9u7gak {
  stop-color: var(--svg-color--997a6f, #997A6F);
  stop-opacity: 0;
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iedexoy6o {
  d: path("M24.754 6.316c.609.21 1.155.634 1.5 1.243c.552.971.47 2.132-.126 2.989c-.207.304-.32.666-.32 1.034v1.405a2.1 2.1 0 0 0-.789-.317l.093-1.9a1.715 1.715 0 0 0-1.631-1.694h-1.657a2.87 2.87 0 0 1-2.616-1.707a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.952 1.79-3.952 3.997l.036 1.819c-.3.044-.614.145-.852.312v-1.42c0-.368-.113-.73-.32-1.034a2.83 2.83 0 0 1-.17-2.894a2.77 2.77 0 0 1 1.538-1.332A3.17 3.17 0 0 0 14.89 5.01a2.75 2.75 0 0 1 3.42-1.079c.451.197.96.197 1.411 0a2.8 2.8 0 0 1 1.08-.222c.997 0 1.87.54 2.352 1.339a3 3 0 0 0 1.6 1.269");
}

.ip469ff8c {
  stop-color: var(--svg-color--ff8045, #FF8045);
}

.ir7rnkbkd {
  d: path("M12.995 12.756a1.13 1.13 0 0 0 .1 2.223a92 92 0 0 1-.1-2.223");
}

.ith5l9r9j {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M23.971 7.478H21.51a.57.57 0 1 1 .092-1.137c.639.102 1.487.244 2.055.385c1.284.318 1.638.943 1.737 1.389a1.79 1.79 0 0 0-1.422-.637");
}

.iv9zqpbet {
  d: path("M20.038 20.974h.973c2.5 0 7.5 3.5 7.5 9h-18v-3.5a.67.67 0 0 0-.416-.625l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.198v-5.288c0-.563.425-1.014.936-1.014h4.129c.52 0 .935.46.935 1.014v3.986c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.jfma4ebms {
  stop-color: var(--svg-color--ff7c1f, #FF7C1F);
  stop-opacity: 0;
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.jx7ffbcje {
  stop-color: var(--svg-color--997a6f, #997A6F);
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.khbnhvbup {
  stop-color: var(--svg-color--866a60, #866A60);
  stop-opacity: 0;
}

.l24x8zb-x {
  stop-color: var(--svg-color--b64318, #B64318);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l7n7uk6bh {
  stop-color: var(--svg-color--331c1a, #331C1A);
  stop-opacity: 0;
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj4eu7bxk {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("M19.286 7.53a3 3 0 0 1-.078-.161a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.952 1.79-3.952 3.997v.326c-.403-.306-.909-.952-.909-1.997c0-1.268.925-1.909 1.515-2.317c.167-.116.306-.213.391-.3l.118-.124c.414-.438 1.15-1.22 2.437-1.561a6.6 6.6 0 0 1 1.932-.19c.472.02.805.429.805.902v1.905z");
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m8fjaubhi {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.407 17.145a3.5 3.5 0 0 0 1.604.38c.595 0 1.141-.138 1.604-.38h.001a.26.26 0 0 1 .304.05a.24.24 0 0 1 .027.306l-.063-.042c-.396.6-1.087 1-1.873 1a2.24 2.24 0 0 1-1.873-1zm0 0a.26.26 0 0 0-.305.053a.24.24 0 0 0-.026.303z");
}

.m9entvb6m {
  d: path("m25.178 11.395l-.035-.746C25.13 9.745 24.384 9 23.48 8.962h-1.657a2.87 2.87 0 0 1-2.512-1.49s-.124-.286-.214-.748c-.192-.984.727-1.711 1.71-1.514c1.184.236 2.593.667 3.644 1.353c2.064 1.346 1.812 3.69.725 4.832");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.md-v7ib7j {
  d: path("M19.011 17.6c-.6 0-1.165-.14-1.639-.388c-.162-.082-.336.1-.234.247c.396.6 1.087 1 1.873 1c.787 0 1.477-.4 1.873-1c.102-.153-.072-.33-.234-.247a3.54 3.54 0 0 1-1.639.388");
}

.mhv89pbbq {
  d: path("M17.392 13.457c0-.34-.277-.568-.352-.637l-.341.33l.21.427z");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nhv4sxnyk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m4.588 5.208l.148 1.945");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.no8c23uva {
  stop-color: var(--svg-color--703a49, #703A49);
}

.nui0_5bvt {
  stop-color: var(--svg-color--67383d, #67383D);
}

.nwhtltdqd {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m25.178 11.395l-.035-.746C25.13 9.745 24.384 9 23.48 8.962h-1.657a2.87 2.87 0 0 1-2.512-1.49s-.124-.286-.214-.748c-.192-.984.727-1.711 1.71-1.514c1.184.236 2.593.667 3.644 1.353c2.064 1.346 1.812 3.69.725 4.832");
}

.nxua_f4_x {
  d: path("M3.291 9.221c-.125-1.922-.281-2.958-.328-3.64c-.035-.513.024-1.067.711-1.192c.598-.074.883.452.906.66c-.002-.2 0-.68 0-.805c0-.21.008-.976.86-.976c.601 0 .816.587.8.863c.01-.101.023-.413.036-.707c.018-.433.251-.989.945-.976c.598.039.793.613.766.976l-.118 1.867c.024-.187.103-.665.278-1.34s.701-.72.957-.683c.326.046.88.36.648 1.273c-.275 1.157-.462 2.645-.527 3.286c.324-.133.642-.413 1.002-.788c.359-.375.886-.383 1.183-.16c.34.293.522.967.12 1.37c-.463.424-2.13 2.404-2.957 3.394c-.23.292-.997.875-2.235.875c-2.203-.094-2.941-1.676-3.047-3.297");
}

.o-iirh5hj {
  stop-color: var(--svg-color--815854, #815854);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p2mr7sbov {
  d: path("M24.834 15.76q.117-1.888.218-3.775a1.904 1.904 0 0 1-.218 3.775");
}

.p2wqo_bck {
  cx: 16.109px;
  cy: 12.977px;
  rx: 0.461px;
  ry: 0.233px;
}

.p4ezwj49r {
  stop-color: var(--svg-color--dd6422, #DD6422);
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pbii7_bty {
  d: path("m18.37 21.083l-7.875 5.246a.66.66 0 0 0-.4-.48l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.198v-5.288c0-.563.425-1.014.936-1.014h4.129c.52 0 .935.46.935 1.014v3.986c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pmtca2xis {
  stop-color: var(--svg-color--ff611d, #FF611D);
  stop-opacity: 0;
}

.ptcv1djxr {
  d: path("m18.559 13.329l-.629 2.174c-.128.447.18.895.616.895h.93c.437 0 .744-.454.616-.895l-.629-2.174c-.134-.482-.763-.482-.904 0");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q2kyq2xrt {
  stop-color: var(--svg-color--d93f13, #D93F13);
}

.q3dsuwb-s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.073 7.03c-.13.165-.332.3-.518.4");
}

.q3td6tqwm {
  stop-color: var(--svg-color--dd6422, #DD6422);
  stop-opacity: 0;
}

.q7h19xvvk {
  stop-color: var(--svg-color--8e6e66, #8E6E66);
  stop-opacity: 0;
}

.q8h9rabnk {
  d: path("M21.595 12.526a1.056 1.056 0 0 1 1.017 1.334h-2.04a1.06 1.06 0 0 1 1.022-1.334");
}

.qk4glw74i {
  d: path("M22.535 13.443a1 1 0 0 0-.273-.548l-.308.338l.139.27z");
}

.qqgo0qblt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m6.213 4.778l-.07 2.297");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.s6abn5boy {
  stop-color: var(--svg-color--8e6e66, #8E6E66);
}

.s6fofcbba {
  d: path("M24.859 14.986q.069-1.126.13-2.252a1.13 1.13 0 0 1-.13 2.252");
}

.sb0d27qfu {
  d: path("M13.26 15.653a1.94 1.94 0 0 1-1.07-.366v1.102a2.57 2.57 0 0 0 1.587 2.388a4.8 4.8 0 0 1-.41-1.396z");
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sq9q63bos {
  stop-color: var(--svg-color--ff7636, #FF7636);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t5j04cb_m {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m18.536 13.56l-.699 2.175c-.119.447.168.894.573.894h.866c.406 0 .692-.454.573-.894l-.585-2.175c-.125-.482-.596-.482-.728 0");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tvgnczn8r {
  stop-color: var(--svg-color--714131, #714131);
}

.u_dqezktl {
  d: path("M24.762 15.653a1.94 1.94 0 0 0 1.07-.366v1.102a2.57 2.57 0 0 1-1.586 2.388q.303-.645.409-1.396z");
}

.u-bujtbll {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.532 6.839c-.13.164-.5.36-.712.423");
}

.u0nta8sqa {
  d: path("M19.011 23.974c-1.268 0-2.296-.986-2.296-2.2v-2.6c0-1.215 1.028-2.2 2.296-2.2s2.296.985 2.296 2.2v2.6c0 1.214-1.028 2.2-2.296 2.2");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.v0q_-i93u {
  stop-color: var(--svg-color--ff8045, #FF8045);
  stop-opacity: 0;
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.v9m6mufix {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M14.976 10.52a3.3 3.3 0 0 1 2.057-.425a.328.328 0 0 1-.08.651a2.63 2.63 0 0 0-1.64.337a2 2 0 0 0-.108.07l-.004.003a.328.328 0 0 1-.401-.519z");
}

.vthu1ccss {
  stop-color: var(--svg-color--926257, #926257);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w5wis0b3d {
  stop-color: var(--svg-color--643239, #643239);
}

.wc4yoe1cm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m7.854 5.38l-.235 1.406");
}

.wogt4ot2h {
  stop-color: var(--svg-color--d93f13, #D93F13);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wug9f7p2x {
  stop-color: var(--svg-color--95766f, #95766F);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xfyzhiubb {
  d: path("M16.428 12.526a1.056 1.056 0 0 0-1.018 1.334h2.04q.037-.135.038-.278a1.063 1.063 0 0 0-1.06-1.056");
}

.xjv40os-m {
  stop-color: var(--svg-color--ff6e45, #FF6E45);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.y-2q9rb0t {
  fill: var(--svg-color--ff611d, #FF611D);
  d: path("M20.038 20.974h.973c2.5 0 7.5 3.5 7.5 9h-18v-3.5a.67.67 0 0 0-.416-.625l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.198v-5.288c0-.563.425-1.014.936-1.014h4.129c.52 0 .935.46.935 1.014v3.986c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.ya78f26qa {
  stop-color: var(--svg-color--ff7c1f, #FF7C1F);
}

.yecivi0wh {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m9.36 4.027l-.813 3.406");
}

.yp0dscc5o {
  d: path("M21.517 12.749c.076.1-.082.223-.26.357c-.18.133-.312.228-.387.127c-.075-.1.009-.29.187-.424c.18-.134.385-.16.46-.06");
}

.yrxkt-bta {
  stop-color: var(--svg-color--ff6e45, #FF6E45);
  stop-opacity: 0;
}

.yt_0wt3yl {
  stop-color: var(--svg-color--724130, #724130);
}

.yzcdtkbjq {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m18.559 13.329l-.629 2.174c-.128.447.18.895.616.895h.93c.437 0 .744-.454.616-.895l-.629-2.174c-.134-.482-.763-.482-.904 0");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z0iyhs38d {
  stop-color: var(--svg-color--331c1a, #331C1A);
}

.z780zkb0h {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.183 12.204c-.773 0-1.425.533-1.603 1.253a.324.324 0 0 0 .317.403h2.64a.272.272 0 0 0 .268-.322a1.66 1.66 0 0 0-1.622-1.334");
}

.zdo6gqojl {
  stop-color: var(--svg-color--d64d18, #D64D18);
}

.zmcsd8b9p {
  stop-color: var(--svg-color--e6724b, #E6724B);
}

.zmi22ab_n {
  d: path("M13.044 11.97a1.92 1.92 0 0 0-1.647 1.89c0 1.016.797 1.846 1.8 1.9a93 93 0 0 1-.153-3.79");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
