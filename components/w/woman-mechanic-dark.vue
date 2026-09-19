<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iQokmbr)"><path fill="url(#iRr56ee)" class="bscxqsbmf"/><path fill="url(#imJrkkd)" class="bscxqsbmf"/><path fill="url(#iwAClXq)" class="bscxqsbmf"/><path fill="url(#iDjhZFe)" class="bscxqsbmf"/><path fill="url(#iYqTZyk)" class="bscxqsbmf"/></g><path fill="url(#igtPXve)" class="m1i1rlbvk"/><g filter="url(#iOGGSJO)"><path class="xk18tyb3e"/></g><path class="zai0whbkr"/><path fill="url(#i4RHwye)" class="mp2n73xvx"/><path fill="url(#i86fP2c)" class="mp2n73xvx"/><path fill="url(#i23ntQe)" class="mp2n73xvx"/><path class="jse2phbtg"/><path fill="url(#i2nIhZb)" class="om0oq7b1v"/><path fill="url(#ivP9Jjb)" class="om0oq7b1v"/><path fill="url(#i77Ytid)" class="om0oq7b1v"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#iTdOGsd)" class="vqc4qgzhu"/><path fill="url(#iJIw8ya)" class="vqc4qgzhu"/><path fill="url(#ijcUagb)" class="dvr2s59yl"/><path fill="url(#iDoneVc)" class="dvr2s59yl"/><path fill="url(#idlbkMe)" class="rom2yrbwh"/><path fill="url(#iIvEVud)" class="rom2yrbwh"/><path fill="url(#iXRw9pd)" class="rom2yrbwh"/><path fill="url(#iz9xh1o)" class="rom2yrbwh"/><path fill="url(#i6G3R0c)" class="rom2yrbwh"/><g filter="url(#idhabee)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#iAh8f0c)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#iQCb1je)"><path fill="url(#iLfs8Lb)" class="dhpkw7buq"/></g><g filter="url(#if1jpeb)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#ixaGDYd)" class="u1e8ikbzb"/></g><g filter="url(#iakflEe)"><path class="z5g21op2e"/></g><g filter="url(#iaZYl9c)"><path fill="url(#iYwEt7d)" class="pv8cx5b7o"/><path fill="url(#iMR6TEe)" class="pv8cx5b7o"/><path fill="url(#iM4MnPm)" class="pv8cx5b7o"/><path fill="url(#iT7ND8b)" class="pv8cx5b7o"/><path fill="url(#if0BDQe)" class="pv8cx5b7o"/></g><g filter="url(#i1ZnySK)"><path stroke="url(#iTqOeXb)" class="cjq4b16bn"/></g><g filter="url(#iiWZiod)"><path stroke="url(#ipaGmae)" class="luyfkt2yj"/></g><g filter="url(#i8ppQZc)"><path stroke="url(#isoouNc)" class="eqaszhbhb"/></g><g filter="url(#iayBsiN)"><path fill="url(#iIGuJgd)" class="bjalqfbbc"/><path fill="url(#ioNj1hJ)" class="bjalqfbbc"/></g><g filter="url(#iq1XMii)"><path fill="url(#iGDYK7N)" class="d-pg7lh5k"/></g><g filter="url(#i0NkSCe)"><path class="g90274z1u"/><path fill="url(#iTDufKd)" class="zkhp-kbvb"/></g><g filter="url(#i5l8Cfd)"><path class="wlsxifa8t"/><path fill="url(#iHrLUie)" class="txy3zibho"/></g><g filter="url(#ioVbPyb)"><path fill="url(#ixJ04Mc)" class="l4g_lxbpt"/><path fill="url(#iQrtLYc)" class="l4g_lxbpt"/><path fill="url(#iiS74Ge)" class="l4g_lxbpt"/><path fill="url(#i0C894c)" class="l4g_lxbpt"/><path fill="url(#i1SkQOc)" class="l4g_lxbpt"/><path fill="url(#i1R5j3d)" class="l4g_lxbpt"/><path fill="url(#iBwr6dc)" class="l4g_lxbpt"/><path fill="url(#iyPMg8d)" class="l4g_lxbpt"/></g><path fill="url(#iaVN7nV)" class="l4g_lxbpt"/><path fill="url(#iBnXDHc)" class="l4g_lxbpt"/><path fill="url(#iA6eVpB)" class="l4g_lxbpt"/><path fill="url(#inpgnbe)" class="l4g_lxbpt"/><g filter="url(#i8HlYad)"><path class="oevy_qpah"/></g><g filter="url(#iSiehke)"><path class="m_095qbaq"/><path fill="url(#iGvosfd)" class="s1_lo0bus"/><path fill="url(#i1Q3lYd)" class="s1_lo0bus"/><path fill="url(#iv9YKhc)" class="s1_lo0bus"/><path fill="url(#iukSwCb)" class="s1_lo0bus"/></g><g filter="url(#inodNeF)"><path class="k8168g58h"/><path fill="url(#iSS0uTh)" class="jc6y0gvlk"/><path fill="url(#i0zMNFY)" class="jc6y0gvlk"/><path fill="url(#iYbTEzi)" class="jc6y0gvlk"/><path fill="url(#iHTbHTb)" class="jc6y0gvlk"/></g><path stroke="url(#iociNBb)" class="a3rexnbmq"/><g filter="url(#iI0gFuc)"><path class="np6lstirr"/></g><g filter="url(#iN04O4b)"><path class="vqu27xbcv"/></g><g filter="url(#i93p0Oc)"><path class="iwa_vu2vw"/></g><g filter="url(#ivTqa1b)"><path class="igheb1mpy"/></g><path class="cv8n7ghyf"/><path fill="url(#if8ZG4c)" class="q2n8nlb1h"/><path class="g566m-vyd"/><g filter="url(#iP6GFxb)"><path class="swixktbff"/><path fill="url(#izYcoGc)" class="nj-0hrbuu"/></g><g filter="url(#ibAG13c)"><path fill="url(#iePi2YS)" class="z5q3bcbqv"/></g><path class="uh9cevbxa"/><path fill="url(#iRDQ19b)" class="ekpl1qbqy"/><path class="c1btl550y"/><g filter="url(#ix8SnUb)"><path fill="url(#iwIfKCd)" class="wnvf0hy4j"/></g><g filter="url(#iOWCqCc)"><ellipse transform="rotate(-27.914 13.252 9.96)" class="m4sl5db0r"/><ellipse fill="url(#iExPcnL)" transform="rotate(-27.914 13.252 9.96)" class="qd_4q9b3f"/></g><g filter="url(#i5BNp2c)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#izdjblc)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="imJrkkd" cx="0" cy="0" r="1" gradientTransform="rotate(140.889 3.842 5.316)scale(4.24611 1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="yd_laccri"/><stop offset="1" class="dmf0acl5m"/></radialGradient><radialGradient id="iwAClXq" cx="0" cy="0" r="1" gradientTransform="matrix(2.11985 0 0 3.47579 20.212 7.694)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="w9txrw6kc"/><stop offset="1" class="h-4ghpb7u"/></radialGradient><radialGradient id="iDjhZFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90841 -5.85233 0 14.758 12.65)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="dc6jrkblm"/><stop offset="1" class="oy6n6fbyn"/></radialGradient><radialGradient id="iYqTZyk" cx="0" cy="0" r="1" gradientTransform="rotate(117.05 7.869 13.544)scale(2.23819 1.04512)" gradientUnits="userSpaceOnUse"><stop class="jsa0_reur"/><stop offset="1" class="j1xr6ccfb"/></radialGradient><radialGradient id="i23ntQe" cx="0" cy="0" r="1" gradientTransform="rotate(135.74 4.223 11.079)scale(3.58199 4.84976)" gradientUnits="userSpaceOnUse"><stop class="qunsngokg"/><stop offset="1" class="zsyglhsdv"/></radialGradient><radialGradient id="i77Ytid" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="f7vxzf2re"/><stop offset="1" class="bjz-35bmd"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="ijcUagb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7453 1.74043 -2.1505 -2.15651 27.338 23.373)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iDoneVc" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .3134 .41161 27.001 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="i6G3R0c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.553 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="iLfs8Lb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.875 -3.15122 0 15.915 16.444)" gradientUnits="userSpaceOnUse"><stop class="xas129mop"/><stop offset="1" class="g9p1h4bmd"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="ixaGDYd" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.839)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="iMR6TEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.364 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iM4MnPm" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.364 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iT7ND8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.364 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="if0BDQe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.364 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iIGuJgd" cx="0" cy="0" r="1" gradientTransform="rotate(-43.767 24.246 -20.64)scale(1.62195 2.626)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="ioNj1hJ" cx="0" cy="0" r="1" gradientTransform="matrix(.61918 .73134 -.23906 .2024 21.498 8.935)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iTDufKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.46565 0 0 -.83288 10.362 10.598)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iHrLUie" cx="0" cy="0" r="1" gradientTransform="matrix(.66527 -.09951 .15385 1.02855 20.948 10.694)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="ixJ04Mc" cx="0" cy="0" r="1" gradientTransform="rotate(155.407 8.266 7.021)scale(7.36936 9.81575)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="iQrtLYc" cx="0" cy="0" r="1" gradientTransform="rotate(154.68 7.605 7.395)scale(2.32122 1.60883)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="iiS74Ge" cx="0" cy="0" r="1" gradientTransform="matrix(1.10604 -3.5548 4.53832 1.41205 13.513 16.902)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="i0C894c" cx="0" cy="0" r="1" gradientTransform="rotate(96.777 3.66 12.309)scale(7.00292 7.09189)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="i1SkQOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.71561 -6.80233 0 15.49 10.364)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="i1R5j3d" cx="0" cy="0" r="1" gradientTransform="rotate(168.875 8.24 6.726)scale(7.10178 12.1425)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="jwznzqbnr"/><stop offset="1" class="fgjvektso"/></radialGradient><radialGradient id="iBwr6dc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17683 1.45515 0 18.13 9.538)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iyPMg8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34224 1.54986 0 13.62 9.304)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iaVN7nV" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32427 0 0 -6.59153 21.009 11.059)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iBnXDHc" cx="0" cy="0" r="1" gradientTransform="rotate(139.492 7.096 11.252)scale(2.47858 1.65931)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iA6eVpB" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.56254 -7.96563 0 15.759 7.19)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="k1yc-6bgn"/><stop offset="1" class="enui4qbiv"/></radialGradient><radialGradient id="inpgnbe" cx="0" cy="0" r="1" gradientTransform="rotate(78.393 5.948 17.016)scale(3.3615 2.11543)" gradientUnits="userSpaceOnUse"><stop class="rqvudbcva"/><stop offset="1" class="zdd_-i6yb"/></radialGradient><radialGradient id="iGvosfd" cx="0" cy="0" r="1" gradientTransform="rotate(-101.645 13.09 -.772)scale(2.25681 .64762)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iukSwCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.23563 16.25 12.122)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iSS0uTh" cx="0" cy="0" r="1" gradientTransform="matrix(-.7809 -.8176 .59278 -.56618 17.05 14.168)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iHTbHTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33612 0 0 -.08716 16.639 14.252)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="if8ZG4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.887 10.056)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="izYcoGc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.313 .746)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRDQ19b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.523 10.056)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iExPcnL" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.237 10.275)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><filter id="iQokmbr" width="15.95" height="13.5" x="7.71" y="4.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.101961 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.337255 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1948" result="effect2_innerShadow_4002_1948"/></filter><filter id="iOGGSJO" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".5"/></filter><filter id="idhabee" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1948"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1948" result="shape"/></filter><filter id="iAh8f0c" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="iQCb1je" width="4.352" height="2.789" x="13.564" y="15.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="if1jpeb" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="iakflEe" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".325"/></filter><filter id="iaZYl9c" width="4.468" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="i1ZnySK" width="2.097" height=".3" x="23.353" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".05"/></filter><filter id="iiWZiod" width="2.097" height=".3" x="23.275" y="27.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".05"/></filter><filter id="i8ppQZc" width="2.097" height=".3" x="23.353" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".05"/></filter><filter id="iayBsiN" width="1.514" height="3.441" x="20.627" y="8.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="iq1XMii" width="1.671" height="3.2" x="9.269" y="8.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="i0NkSCe" width="1.329" height="2.379" x="9.672" y="9.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".125"/></filter><filter id="i5l8Cfd" width="1.947" height="2.903" x="20.167" y="9.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".25"/></filter><filter id="ioVbPyb" width="10.5" height="11.373" x="10.509" y="5.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="i8HlYad" width="2.877" height="3.9" x="14.059" y="9.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".25"/></filter><filter id="iSiehke" width="2.377" height="3.4" x="14.516" y="9.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".125"/></filter><filter id="inodNeF" width="3.718" height="1.573" x="13.846" y="13.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".125"/></filter><filter id="iI0gFuc" width="2.439" height="1.19" x="17.294" y="7.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="iN04O4b" width="2.439" height="1.176" x="12.038" y="7.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="i93p0Oc" width="2.611" height="1.227" x="16.995" y="9.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="ivTqa1b" width="2.611" height="1.227" x="11.806" y="9.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="iP6GFxb" width=".787" height=".696" x="17.153" y="9.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".05"/></filter><filter id="ibAG13c" width=".891" height=".913" x="17.993" y="9.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".1"/></filter><filter id="ix8SnUb" width=".986" height="1.04" x="13.55" y="9.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".1"/></filter><filter id="iOWCqCc" width=".913" height=".705" x="12.795" y="9.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1948" stdDeviation=".05"/></filter><filter id="i5BNp2c" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><filter id="izdjblc" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1948"/></filter><linearGradient id="iRr56ee" x1="22.414" x2="14.931" y1="6.466" y2="18.664" gradientUnits="userSpaceOnUse"><stop class="oco3zrb8c"/><stop offset=".862" class="rgx7dt08r"/></linearGradient><linearGradient id="igtPXve" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="hzctbo64o"/><stop offset="1" class="ncpoyrbpw"/></linearGradient><linearGradient id="i4RHwye" x1="14.633" x2="13.974" y1="19.957" y2="19.239" gradientUnits="userSpaceOnUse"><stop class="ptx8-dg4d"/><stop offset="1" class="m1cydckkt"/></linearGradient><linearGradient id="i86fP2c" x1="11.699" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="zsyglhsdv"/></linearGradient><linearGradient id="i2nIhZb" x1="19.937" x2="18.312" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="ul2cu2h0c"/></linearGradient><linearGradient id="ivP9Jjb" x1="17" x2="17.937" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="iTdOGsd" x1="23.473" x2="23.473" y1="29.781" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="iYwEt7d" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iTqOeXb" x1="23.503" x2="25.212" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="ipaGmae" x1="23.425" x2="25.134" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="isoouNc" x1="23.503" x2="25.212" y1="28.68" y2="28.68" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iGDYK7N" x1="9.269" x2="10.667" y1="10.684" y2="10.684" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="i1Q3lYd" x1="14.766" x2="15.705" y1="11.972" y2="11.972" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iv9YKhc" x1="15.705" x2="15.705" y1="12.836" y2="12.176" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="i0zMNFY" x1="14.096" x2="15.705" y1="14.197" y2="14.197" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iYbTEzi" x1="15.705" x2="15.705" y1="14.517" y2="14.272" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iociNBb" x1="14.668" x2="15.103" y1="14.352" y2="13.664" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iePi2YS" x1="18.665" x2="18.351" y1="10.11" y2="10.303" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwIfKCd" x1="14.267" x2="13.953" y1="10.11" y2="10.303" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-mechanic-dark" /></template>
<style>
.a3rexnbmq {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.343 13.38c.393.205.862.323 1.362.323c.505 0 .969-.117 1.362-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.241m-2.986-.28l2.945.253m-2.945-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.208.027l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.625.869c-.682 0-1.28-.347-1.625-.868m3.208-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.583-.846m-.042.028l.042-.028m-.042.028l.042-.028");
}

.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.bjalqfbbc {
  d: path("M20.627 12.197q.1-1.596.184-3.19a1.61 1.61 0 0 1-.184 3.19");
}

.bjz-35bmd {
  stop-color: var(--svg-color--d6cbdf, #D6CBDF);
  stop-opacity: 0;
}

.bscxqsbmf {
  d: path("M23.51 10.724c0-1.722-2.299-2.453-2.299-3.474l-.14-.68c0-.92.252-1.39-.103-2.011H10.65c-.306.62-.394 1.784-.394 2.704v.01c0 1.048-2.247 1.352-2.247 3.45c0 .541.118 1.041.335 1.502c.069.15.069.33 0 .48a3.4 3.4 0 0 0-.335 1.481c0 1.862 1.488 3.373 3.32 3.373h8.86c1.832 0 3.32-1.511 3.32-3.373c0-.53-.118-1.03-.335-1.48a.58.58 0 0 1 0-.481c.217-.46.335-.971.335-1.501");
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c1btl550y {
  fill: var(--svg-color--000, #000);
  d: path("M14.032 10.471a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .061-.235");
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.cjq4b16bn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 25.992H25.3");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cv8n7ghyf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.096 9.307c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.d-pg7lh5k {
  d: path("M10.65 8.998a1.61 1.61 0 0 0 .14 3.2a78 78 0 0 1-.14-3.2");
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.dc6jrkblm {
  stop-color: var(--svg-color--160c19, #160C19);
}

.dhpkw7buq {
  d: path("M15.717 18.637c-1.523-.508-1.95-1.487-2.153-2.589h4.352c-.367 2.016-1.68 2.488-2.199 2.59");
}

.dmf0acl5m {
  stop-color: var(--svg-color--565252, #565252);
  stop-opacity: 0;
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ekpl1qbqy {
  d: path("M13.52 9.579a.893.893 0 0 0-.86 1.127h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.enui4qbiv {
  stop-color: var(--svg-color--362028, #362028);
  stop-opacity: 0;
}

.eqaszhbhb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 28.602H25.3");
}

.f7vxzf2re {
  stop-color: var(--svg-color--8e7f98, #8E7F98);
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fgjvektso {
  stop-color: var(--svg-color--644d4a, #644D4A);
}

.ft5dv1b6b {
  fill: none;
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.g566m-vyd {
  fill: var(--svg-color--000, #000);
  d: path("M17.378 10.471c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.g90274z1u {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M10.668 9.659a.956.956 0 0 0 .083 1.879a78 78 0 0 1-.083-1.88");
}

.g9p1h4bmd {
  stop-color: var(--svg-color--4c343a, #4C343A);
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.h-4ghpb7u {
  stop-color: var(--svg-color--150a0d, #150A0D);
  stop-opacity: 0;
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.hzctbo64o {
  stop-color: var(--svg-color--d6c6ed, #D6C6ED);
}

.igheb1mpy {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M13.199 9.241c.765.04 1.099.422 1.218.614l-2.011.46c-.141.008-.485-.085-.563-.245a.31.31 0 0 1 .05-.364c.177-.203.675-.497 1.306-.465");
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.iwa_vu2vw {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M18.214 9.241c-.766.04-1.1.422-1.22.614l2.012.46c.141.008.485-.085.563-.245a.31.31 0 0 0-.05-.364c-.177-.203-.675-.497-1.305-.465");
}

.j1xr6ccfb {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
  stop-opacity: 0;
}

.jc6y0gvlk {
  d: path("M15.705 13.753c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.197.209c.335.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jsa0_reur {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
}

.jse2phbtg {
  fill: var(--svg-color--f4e6ff, #F4E6FF);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.jwznzqbnr {
  stop-color: var(--svg-color--644d4a, #644D4A);
  stop-opacity: 0;
}

.k1yc-6bgn {
  stop-color: var(--svg-color--362028, #362028);
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.k8168g58h {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("M15.705 13.753c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.197.209c.335.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.l4g_lxbpt {
  d: path("M19.795 7.274H16.48c-1.314 0-2.509-.594-3.245-1.657a.272.272 0 0 0-.478.05l-.08.194a2.34 2.34 0 0 1-1.233 1.238a.4.4 0 0 1-.11.048c-.249.117-.816.488-.826 1.453l.14 3.235c.119 2.865 2.378 4.785 5.115 4.785s4.996-1.92 5.116-4.785l.129-3.08c-.02-1.354-1.025-1.48-1.214-1.48");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.luyfkt2yj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.425 27.297h1.797");
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.m_095qbaq {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.323 10.142l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.m1cydckkt {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
  stop-opacity: 0;
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.m4sl5db0r {
  cx: 13.252px;
  cy: 9.96px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.mp2n73xvx {
  d: path("M11.736 16.236v4.904c0 .434.418.668.813.38l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.609");
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.ncpoyrbpw {
  stop-color: var(--svg-color--cdb2d2, #CDB2D2);
}

.nj-0hrbuu {
  d: path("M17.823 9.767c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.np6lstirr {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M19.438 8.141a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 1 0 .364-.418");
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
}

.oco3zrb8c {
  stop-color: var(--svg-color--30282c, #30282C);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oevy_qpah {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.219 10.338l-.635 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.542-.408-.661 0");
}

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.om0oq7b1v {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.oy6n6fbyn {
  stop-color: var(--svg-color--160c19, #160C19);
  stop-opacity: 0;
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.ptx8-dg4d {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
}

.pv8cx5b7o {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.q2n8nlb1h {
  d: path("M17.889 9.579a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qd_4q9b3f {
  cx: 13.252px;
  cy: 9.96px;
  rx: 0.39px;
  ry: 0.197px;
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qunsngokg {
  stop-color: var(--svg-color--7c6987, #7C6987);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.rgx7dt08r {
  stop-color: var(--svg-color--18111a, #18111A);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rom2yrbwh {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.101-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.rqvudbcva {
  stop-color: var(--svg-color--5c4644, #5C4644);
}

.s1_lo0bus {
  d: path("m15.323 10.142l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.s2-xryl0i {
  d: path("M12.045 6.26c-.68.31-1.29.74-1.89 1.31l.41.51c.31.38.85.49 1.28.25c.76-.42 2.11-.99 3.9-.99s3.14.57 3.9.99a1 1 0 0 0 1.27-.25l.41-.51c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0");
}

.s8-qpgb5g {
  stop-color: var(--svg-color--3b71d9, #3B71D9);
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.sf2388bnl {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
}

.swixktbff {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.823 9.767c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.txy3zibho {
  d: path("M20.667 11.546q.058-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.uh9cevbxa {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.314 9.307c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.ul2cu2h0c {
  stop-color: var(--svg-color--f0e1ff, #F0E1FF);
  stop-opacity: 0;
}

.unsdl8pjp {
  stop-color: var(--svg-color--9b80b4, #9B80B4);
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.vqc4qgzhu {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.402-1.54-6.44-3.96-8.457");
}

.vqu27xbcv {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.294 8.025a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.067.55a2.22 2.22 0 0 0-1.387.286a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w9txrw6kc {
  stop-color: var(--svg-color--150a0d, #150A0D);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wlsxifa8t {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.667 11.546q.058-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.wnvf0hy4j {
  d: path("M14.336 10.366c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xas129mop {
  stop-color: var(--svg-color--4d2b41, #4D2B41);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xk18tyb3e {
  fill: var(--svg-color--caadc8, #CAADC8);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yd_laccri {
  stop-color: var(--svg-color--565252, #565252);
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

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z5q3bcbqv {
  d: path("M18.684 10.354a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zai0whbkr {
  fill: var(--svg-color--eddffd, #EDDFFD);
  d: path("M11.736 16.236v4.904c0 .434.418.668.813.38l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.609");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdd_-i6yb {
  stop-color: var(--svg-color--5c4644, #5C4644);
  stop-opacity: 0;
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zkhp-kbvb {
  d: path("M10.668 9.659a.956.956 0 0 0 .083 1.879a78 78 0 0 1-.083-1.88");
}

.zsyglhsdv {
  stop-color: var(--svg-color--eee0fe, #EEE0FE);
  stop-opacity: 0;
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
