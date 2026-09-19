<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ihQrDwX)" class="ax3t7fbst"/><path fill="url(#iNXhUee)" class="ax3t7fbst"/><path class="jki7tzdcu"/><path fill="url(#ia3Jeib)" class="td7qnxbmr"/><path fill="url(#ixcotec)" class="td7qnxbmr"/><path fill="url(#inT0zab)" class="c5jm6bc5b"/><path fill="url(#iRI2yhd)" class="g3ux3cbys"/><path fill="url(#ihnjaeb)" class="ny9_xhbeh"/><path fill="url(#iqsf46c)" class="ykrihkbqd"/><path fill="url(#imTEBJe)" class="m0er3vbow"/><g filter="url(#iQFF6Xb)"><path fill="url(#i7NuAgJ)" class="pxaxwjbdw"/><path fill="url(#iNimoRb)" class="pxaxwjbdw"/></g><path fill="url(#iyfW9uc)" class="pxaxwjbdw"/><path fill="url(#iIKrwme)" class="pxaxwjbdw"/><path fill="url(#i32T9xH)" class="pxaxwjbdw"/><path fill="url(#iXJRi0d)" class="pxaxwjbdw"/><path fill="url(#ifUG9rl)" class="pxaxwjbdw"/><path fill="url(#i82OFgT)" class="pxaxwjbdw"/><path fill="url(#iL8kNde)" class="pxaxwjbdw"/><path fill="url(#i6u37Fe)" class="pxaxwjbdw"/><g filter="url(#iObuPsu)"><path class="nkt3d_82w"/></g><g filter="url(#iYg9Epd)"><path class="jj0hombrt"/><path fill="url(#iFocZvb)" class="e9ghhhbuh"/><path fill="url(#iUvDwbb)" class="e9ghhhbuh"/><path fill="url(#i8extge)" class="e9ghhhbuh"/><path fill="url(#iC7kcpd)" class="e9ghhhbuh"/><path fill="url(#icNvLcl)" class="e9ghhhbuh"/></g><path fill="url(#iaSvnIe)" class="e9ghhhbuh"/><path fill="url(#ilXGkac)" class="e9ghhhbuh"/><g filter="url(#i4OJwyP)"><path stroke="url(#i9IUjrc)" class="t2qt696ao"/></g><path fill="url(#iM9cLec)" class="ala848byj"/><g filter="url(#iD5TuLp)"><path fill="url(#iVqXjEd)" class="ua_qcxh-g"/></g><path fill="url(#ipdv82b)" class="ua_qcxh-g"/><path fill="url(#inpxMQs)" class="ua_qcxh-g"/><path fill="url(#iCJZc5c)" class="ua_qcxh-g"/><g filter="url(#iSjpFYD)"><path class="df134449s"/></g><g filter="url(#ibjsY6k)"><path class="anovjip2y"/></g><g filter="url(#i5nr0Uc)"><path class="iuwys0e8y"/><path fill="url(#iBRjixl)" class="whe1rqnxf"/><path fill="url(#iRcYWvd)" class="whe1rqnxf"/></g><g filter="url(#iSIJS1b)"><path class="yhartvh3t"/><path fill="url(#iWmbZzd)" class="z0n3w3f7w"/><path fill="url(#il1sb8d)" class="z0n3w3f7w"/><path fill="url(#iytWAtb)" class="z0n3w3f7w"/></g><path class="kx7ht60vn"/><path fill="url(#iSPWV3E)" class="y26jaac_x"/><path class="pw-i-nesf"/><g filter="url(#i1o9ICg)"><path class="udkr-um3k"/><path fill="url(#iPNAJNd)" class="g0smdzbso"/></g><g filter="url(#iTXcR4t)"><path fill="url(#iEhvGKc)" class="ty4dpab2g"/></g><path class="ieumhfb7o"/><path fill="url(#iVKjuKc)" class="yhrpqc-is"/><path class="xv861oxon"/><g filter="url(#is6onFc)"><path fill="url(#isftRge)" class="uf-eydb2k"/></g><g filter="url(#ikSs1rc)"><ellipse transform="rotate(-27.914 13.542 9.816)" class="cur91yz5h"/><ellipse fill="url(#i9HExNc)" transform="rotate(-27.914 13.542 9.816)" class="v1mb2vv6g"/></g><path fill="url(#ik9WUsd)" class="m6jz2xbwk"/><path fill="url(#i1emIBh)" class="m6jz2xbwk"/><path fill="url(#ieKxOhc)" class="m6jz2xbwk"/><path fill="url(#iJe4LIc)" class="m6jz2xbwk"/><path fill="url(#ihYyGHd)" class="une6icbfh"/><path fill="url(#inG1yzb)" class="une6icbfh"/><g filter="url(#iGAuodd)"><path fill="url(#i11uYYV)" class="brpuz_b9y"/></g><g filter="url(#iM5r2ee)"><path fill="url(#i8npTTD)" class="thh-62fwz"/></g><g filter="url(#ismAaEb)"><path class="tocgtiy7m"/></g><g filter="url(#i6UFFtc)"><path class="dioto3b0t"/></g><g filter="url(#iZnhYBc)"><path class="txsgb4b8v"/></g><g filter="url(#ipClWIe)"><path fill="url(#iHXaVce)" class="jsqgobbht"/><path fill="url(#i2BUj5L)" class="jsqgobbht"/><path fill="url(#iqtSqJd)" class="jsqgobbht"/><path fill="url(#iNN1SaK)" class="jsqgobbht"/><path fill="url(#irzSjbb)" class="jsqgobbht"/><path fill="url(#ihI2zKe)" class="jsqgobbht"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><radialGradient id="ihQrDwX" cx="0" cy="0" r="1" gradientTransform="matrix(2.80769 -1.3591 1.47615 3.04949 2.747 30.02)" gradientUnits="userSpaceOnUse"><stop offset=".406" class="mom0z_ble"/><stop offset="1" class="ofcsa759z"/></radialGradient><radialGradient id="iNXhUee" cx="0" cy="0" r="1" gradientTransform="rotate(177.157 2.332 14.994)scale(3.35044 4.79049)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="r0k1w-u4i"/><stop offset=".927" class="lmanndb2z"/></radialGradient><radialGradient id="ia3Jeib" cx="0" cy="0" r="1" gradientTransform="matrix(5.64062 -3.71875 1.03844 1.57511 27.091 30.119)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="purgp5b3s"/><stop offset="1" class="tizq1n0kf"/></radialGradient><radialGradient id="iqsf46c" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.917 20.796)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="imTEBJe" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.939 12.26)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="i7NuAgJ" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 18.803 10.828)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iNimoRb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.562 8.119)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iIKrwme" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05798 12.31303 -10.19663 -.87613 17.612 5.025)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="f0o-9fbtc"/><stop offset=".954" class="i6650-xam"/></radialGradient><radialGradient id="i32T9xH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.443 9.515)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iXJRi0d" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09428 1.19083 .00428 13.695 9.56)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="ifUG9rl" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.528 6.214)scale(8.51289 21.7462)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i82OFgT" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.204 8.095)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iL8kNde" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.17 13.76)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="i6u37Fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 13.78 10.332)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iUvDwbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.462 12.188)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iC7kcpd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 16.578 11.619)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="ilXGkac" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.945 8.955)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iM9cLec" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 15.504 14.45)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ipdv82b" cx="0" cy="0" r="1" gradientTransform="matrix(2.7406 -7.14959 10.14519 3.88889 10.289 8.903)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="inpxMQs" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 14.395 -4.128)scale(6.72756 9.54634)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iCJZc5c" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 11.09 -3.74)scale(2.63838 3.11466)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iBRjixl" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.249 3.636)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iRcYWvd" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.157 -5.795)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iWmbZzd" cx="0" cy="0" r="1" gradientTransform="rotate(-38.837 17.74 -22.313)scale(4.51284 6.99393)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="il1sb8d" cx="0" cy="0" r="1" gradientTransform="matrix(2.95886 -2.64821 4.8482 5.41692 18.629 7.45)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iytWAtb" cx="0" cy="0" r="1" gradientTransform="matrix(3.22527 .72415 -.30319 1.35036 17.766 5.63)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iSPWV3E" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.177 9.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iPNAJNd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.422 .602)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVKjuKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.813 9.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i9HExNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.527 10.13)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1emIBh" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.613 9.925)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="ieKxOhc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.974 10.47)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iJe4LIc" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.087 10.643)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="inG1yzb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.08 10.566)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i11uYYV" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.08 10.568)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="i2BUj5L" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 31.067)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="ihI2zKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.66)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><linearGradient id="ixcotec" x1="26.966" x2="27.302" y1="28.838" y2="28.838" gradientUnits="userSpaceOnUse"><stop class="l5rpyobus"/><stop offset="1" class="q1cl32x8o"/></linearGradient><linearGradient id="inT0zab" x1="16" x2="16" y1="6.703" y2="34.611" gradientUnits="userSpaceOnUse"><stop class="zaeth0b6d"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="iRI2yhd" x1="10.918" x2="1.428" y1="24.003" y2="24.044" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ihnjaeb" x1="22.998" x2="28.652" y1="24.02" y2="24.02" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="iyfW9uc" x1="21.153" x2="18.624" y1="12.513" y2="12.513" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iFocZvb" x1="16.834" x2="15.995" y1="11.502" y2="11.537" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="i8extge" x1="15.995" x2="15.995" y1="12.642" y2="12.177" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="icNvLcl" x1="15.995" x2="15.995" y1="9.937" y2="10.483" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iaSvnIe" x1="16.411" x2="16.411" y1="12.78" y2="12.587" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="i9IUjrc" x1="14.794" x2="15.112" y1="14.212" y2="13.378" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iVqXjEd" x1="22.848" x2="11.235" y1="5.165" y2="5.165" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iEhvGKc" x1="18.955" x2="18.642" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isftRge" x1="14.557" x2="14.243" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ik9WUsd" x1="22.432" x2="21.225" y1="9.992" y2="12.169" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="ihYyGHd" x1="10.146" x2="11.604" y1="10.696" y2="10.569" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="i8npTTD" x1="21.449" x2="21.449" y1="9.683" y2="11.441" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="iHXaVce" x1="7.493" x2="11.284" y1="19.754" y2="30.805" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="iqtSqJd" x1="16" x2="16" y1="16.02" y2="17.379" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="iNN1SaK" x1="5" x2="6.055" y1="24.254" y2="24.254" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="irzSjbb" x1="27" x2="25.524" y1="25.192" y2="25.192" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><filter id="iQFF6Xb" width="11.22" height="12.442" x="10.932" y="4.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1025"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3_1025" result="effect2_innerShadow_3_1025"/></filter><filter id="iObuPsu" width="3.747" height="4.9" x="13.98" y="9.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".5"/></filter><filter id="iYg9Epd" width="2.277" height="3.3" x="14.857" y="9.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".1"/></filter><filter id="i4OJwyP" width="3.718" height="1.573" x="14.136" y="13.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".05"/></filter><filter id="iD5TuLp" width="12.873" height="8.356" x="9.559" y="1.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1025"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3_1025" result="effect2_innerShadow_3_1025"/></filter><filter id="iSjpFYD" width="2.339" height="1.19" x="17.584" y="7.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1025"/></filter><filter id="ibjsY6k" width="2.339" height="1.176" x="12.328" y="7.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1025"/></filter><filter id="i5nr0Uc" width="6.584" height="5.992" x="9.914" y="2.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1025"/><feGaussianBlur result="effect2_foregroundBlur_3_1025" stdDeviation=".125"/></filter><filter id="iSIJS1b" width="7.111" height="5.986" x="15.836" y="2.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1025"/><feGaussianBlur result="effect2_foregroundBlur_3_1025" stdDeviation=".125"/></filter><filter id="i1o9ICg" width=".787" height=".696" x="17.443" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".05"/></filter><filter id="iTXcR4t" width=".891" height=".913" x="18.283" y="9.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".1"/></filter><filter id="is6onFc" width=".986" height="1.04" x="13.84" y="9.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".1"/></filter><filter id="ikSs1rc" width=".913" height=".705" x="13.086" y="9.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".05"/></filter><filter id="iGAuodd" width="1.329" height="2.379" x="9.914" y="9.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".125"/></filter><filter id="iM5r2ee" width="1.806" height="2.758" x="20.546" y="9.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".25"/></filter><filter id="ismAaEb" width="2.405" height="1.16" x="12.247" y="7.233" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".125"/></filter><filter id="i6UFFtc" width="2.405" height="1.16" x="17.563" y="7.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".125"/></filter><filter id="iZnhYBc" width="5.367" height="3.046" x="17.011" y="3.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1025" stdDeviation=".375"/></filter><filter id="ipClWIe" width="22" height="14.1" x="5" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1025"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:technologist-medium" /></template>
<style>
.a-otvg7dq {
  stop-color: var(--svg-color--806b97, #806B97);
}

.a61ap5b7j {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.ala848byj {
  d: path("M15.995 13.724c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.583.846c.665 0 1.249-.339 1.584-.846c.086-.13-.061-.279-.198-.21a3 3 0 0 1-1.386.33");
}

.anovjip2y {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.585 7.739a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.auud8yb7i {
  stop-color: var(--svg-color--4a3261, #4A3261);
  stop-opacity: 0;
}

.ax3t7fbst {
  d: path("M8.329 30.02q.004-.082.004-.163a3.138 3.138 0 1 0-6.271.162z");
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.bowxt9bwr {
  stop-color: var(--svg-color--6f5783, #6F5783);
}

.brpuz_b9y {
  d: path("M10.91 9.63a.956.956 0 0 0 .083 1.878a78 78 0 0 1-.083-1.879");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c5jm6bc5b {
  d: path("M16 15.52c-6.07 0-11 4.92-11 11v3.5h22v-3.5c0-6.08-4.93-11-11-11");
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cur91yz5h {
  cx: 13.542px;
  cy: 9.816px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d9m_15bme {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

.df134449s {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M19.728 7.848a1.85 1.85 0 0 0-.687-.411c-.305-.096-.686-.122-1.213-.057a.277.277 0 0 0 .068.55c.48-.059.776-.028.978.036c.198.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.dioto3b0t {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.594 7.963c-.257-.184-.898-.509-1.656-.381");
}

.dmu1fh1sq {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9ghhhbuh {
  d: path("m15.613 10.113l-.531 1.838c-.109.378.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0smdzbso {
  d: path("M18.114 9.623c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.051");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g3ux3cbys {
  d: path("M8.98 18.02a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

.g48yfbn9k {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzfhb8b1n {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i6650-xam {
  stop-color: var(--svg-color--8d526c, #8D526C);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ieumhfb7o {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.605 9.163c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.127");
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iuwys0e8y {
  fill: var(--svg-color--533634, #533634);
  d: path("m16.228 5.212l-.066-.137a.66.66 0 0 0-.616-.418h-1.272c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.142-.097.26-.18.332-.253l.1-.105c.349-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.012.806.42.806.893v1.485z");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jehi2ihjx {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

.jj0hombrt {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.613 10.113l-.531 1.838c-.109.378.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.jki7tzdcu {
  fill: var(--svg-color--bd977b, #BD977B);
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jsqgobbht {
  d: path("M26.03 16.02H5.97a.97.97 0 0 0-.97.97v13.03h22V16.99a.97.97 0 0 0-.97-.97");
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k71v6_7um {
  stop-color: var(--svg-color--51366c, #51366C);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kx7ht60vn {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.386 9.163c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.341h-2.232a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.371-1.127");
}

.l17xqebtl {
  stop-color: var(--svg-color--594170, #594170);
}

.l294t3zvi {
  stop-color: var(--svg-color--847498, #847498);
}

.l5rpyobus {
  stop-color: var(--svg-color--b38f78, #B38F78);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmanndb2z {
  stop-color: var(--svg-color--ba907d, #BA907D);
}

.m0er3vbow {
  d: path("M11.134 12.078a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.m6jz2xbwk {
  d: path("M20.917 12.169q.1-1.597.185-3.192a1.61 1.61 0 0 1-.185 3.192");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mom0z_ble {
  stop-color: var(--svg-color--b28a78, #B28A78);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nkt3d_82w {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.594 10.309l-.59 1.838c-.102.378.14.756.484.756h.731c.343 0 .586-.383.485-.756l-.495-1.838c-.106-.407-.504-.407-.615 0");
}

.nonrr22es {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.ny9_xhbeh {
  d: path("M23 18.03v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o1-qqkidl {
  stop-color: var(--svg-color--78698c, #78698C);
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofcsa759z {
  stop-color: var(--svg-color--8a6959, #8A6959);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ohv650iba {
  stop-color: var(--svg-color--52376c, #52376C);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p9llu9bpa {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.ppwrykbzp {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.purgp5b3s {
  stop-color: var(--svg-color--cca28f, #CCA28F);
}

.pw-i-nesf {
  fill: var(--svg-color--000, #000);
  d: path("M17.668 10.327c0-.284.227-.511.511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.pxaxwjbdw {
  d: path("M11.17 13.593a3.916 3.916 0 0 0 3.886 3.405h1.887a3.916 3.916 0 0 0 3.885-3.406c.118-1.883.237-3.76.325-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.116 3.691.239 5.557");
}

.q0dxfdmim {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

.q1cl32x8o {
  stop-color: var(--svg-color--b38f78, #B38F78);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qqk6g6zlh {
  stop-color: var(--svg-color--3d2555, #3D2555);
}

.qufyc6r7b {
  stop-color: var(--svg-color--56416b, #56416B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r0k1w-u4i {
  stop-color: var(--svg-color--ba907d, #BA907D);
  stop-opacity: 0;
}

.r1d3vkbxd {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.szjcm-w7x {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

.t_w5hobcp {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

.t2qt696ao {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m14.645 13.33l-.001-.001a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.023-.273a.23.23 0 0 0-.271-.044c-.39.203-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.td7qnxbmr {
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

.thh-62fwz {
  d: path("m21.046 11.441l.094-1.758c.401.054.712.426.712.876c0 .484-.36.878-.806.882");
}

.tizq1n0kf {
  stop-color: var(--svg-color--cca28f, #CCA28F);
  stop-opacity: 0;
}

.tocgtiy7m {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.622 8.019c.257-.185.898-.51 1.655-.382");
}

.txsgb4b8v {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.394 5.215h-2.137a.496.496 0 1 1 .08-.987c.554.088 1.29.211 1.783.334c1.115.276 1.423.819 1.509 1.206a1.55 1.55 0 0 0-1.235-.553");
}

.ty4dpab2g {
  d: path("M18.974 10.21a.84.84 0 0 0-.23-.463l-.26.285l.116.228z");
}

.ua_qcxh-g {
  d: path("M20.85 4.185a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.526c-.175.258-.27.564-.27.875v1.188a1.75 1.75 0 0 0-.668-.268l.079-1.607a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.445a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.188.912-.188c.843 0 1.58.456 1.989 1.132c.307.51.79.88 1.352 1.073");
}

.udkr-um3k {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.114 9.623c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.051");
}

.uem0lbchq {
  stop-color: var(--svg-color--4f3568, #4F3568);
}

.uf-eydb2k {
  d: path("M14.627 10.222c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.une6icbfh {
  d: path("M10.951 8.964a1.62 1.62 0 0 0-1.392 1.598c0 .86.673 1.561 1.521 1.607a78 78 0 0 1-.129-3.205");
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.ux-m5bn7d {
  stop-color: var(--svg-color--ab9cbe, #AB9CBE);
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v1mb2vv6g {
  cx: 13.542px;
  cy: 9.816px;
  rx: 0.39px;
  ry: 0.197px;
}

.v1n2dlbml {
  stop-color: var(--svg-color--3b2b50, #3B2B50);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w6exmsbsa {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.w9bfwpbnq {
  stop-color: var(--svg-color--60407f, #60407F);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.whe1rqnxf {
  d: path("m16.228 5.212l-.066-.137a.66.66 0 0 0-.616-.418h-1.272c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.142-.097.26-.18.332-.253l.1-.105c.349-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.012.806.42.806.893v1.485z");
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xqmtwwbyq {
  stop-color: var(--svg-color--614c77, #614C77);
}

.xv861oxon {
  fill: var(--svg-color--000, #000);
  d: path("M14.323 10.327a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y26jaac_x {
  d: path("M18.18 9.434a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yhartvh3t {
  fill: var(--svg-color--563936, #563936);
  d: path("m21.208 8.479l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
}

.yhrpqc-is {
  d: path("M13.811 9.434a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.ykrihkbqd {
  d: path("M20.857 12.078a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.019q.257-.546.345-1.18z");
}

.yr342ibfl {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

.z0n3w3f7w {
  d: path("m21.208 8.479l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zt_ualb3u {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
