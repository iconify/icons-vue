<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZLDGXU)"><path fill="url(#injMsxe)" clip-rule="evenodd" class="l5ywhsb5i"/><path fill="url(#iFU4Jnb)" clip-rule="evenodd" class="l5ywhsb5i"/><path fill="url(#iQMk7Ed)" clip-rule="evenodd" class="l5ywhsb5i"/><path fill="url(#iq6NzJe)" clip-rule="evenodd" class="l5ywhsb5i"/><path fill="url(#inNXKgb)" clip-rule="evenodd" class="l5ywhsb5i"/><path fill="url(#iRudOEb)" clip-rule="evenodd" class="l5ywhsb5i"/><path fill="url(#i5y0eNe)" clip-rule="evenodd" class="l5ywhsb5i"/><path fill="url(#isu070c)" clip-rule="evenodd" class="l5ywhsb5i"/><path fill="url(#iirQzkd)" clip-rule="evenodd" class="l5ywhsb5i"/><path fill="url(#iOQdR0c)" clip-rule="evenodd" class="l5ywhsb5i"/><path fill="url(#iEg84Hb)" clip-rule="evenodd" class="l5ywhsb5i"/><path fill="url(#igxWBac)" clip-rule="evenodd" class="l5ywhsb5i"/></g><path fill="url(#iHNqk0X)" class="evso7acss"/><path fill="url(#imqjm9c)" class="evso7acss"/><g filter="url(#iiGfkqd)"><path fill="url(#ia8zscL)" class="i9t6f2bxc"/></g><path fill="url(#ivjsgxd)" class="jcl-2hb7f"/><path fill="url(#iod3k0b)" class="jcl-2hb7f"/><path class="hmnycxx5w"/><path fill="url(#iyhUdBG)" class="cllop4bqc"/><path fill="url(#iyeCLFd)" class="cllop4bqc"/><path fill="url(#i20rlAd)" class="cllop4bqc"/><path fill="url(#iRJv8Rc)" class="cu21d24az"/><path fill="url(#iyAgBob)" class="cu21d24az"/><path fill="url(#iLKBWPD)" class="cu21d24az"/><path fill="url(#i92uFDa)" class="cu21d24az"/><g filter="url(#iHXsGce)"><path class="pbxi84b9i"/></g><g filter="url(#ibsOGne)"><path fill="url(#i5XOWcD)" class="z-t54tbit"/><path fill="url(#iIuGzte)" class="z-t54tbit"/></g><path fill="url(#iRR6nWc)" class="z-t54tbit"/><g filter="url(#ipLrdUY)"><ellipse class="ijlx-8buq"/></g><g filter="url(#i4arNKb)"><path fill="url(#ilz7GNd)" class="k7zk34bqa"/><path fill="url(#isFAYCe)" class="k7zk34bqa"/><path fill="url(#ioWJHub)" class="k7zk34bqa"/><path fill="url(#i9nPv5b)" class="k7zk34bqa"/></g><ellipse fill="url(#iKdWZUd)" class="skhx9acxb"/><ellipse fill="url(#iLpatmc)" class="skhx9acxb"/><rect fill="url(#iP4scOX)" class="qhe9mm7xm"/><rect fill="url(#ikd6jde)" class="qhe9mm7xm"/><path fill="url(#iCIUDTd)" class="oumjgbbsr"/><path fill="url(#i9EbKOc)" class="wdqycsape"/><g filter="url(#i0J7OlR)"><path fill="url(#iARTiEO)" class="u537au68g"/></g><path fill="url(#ifFIJMd)" class="u537au68g"/><g filter="url(#inxwn7d)"><path fill="url(#iFPrJEc)" class="q-rok850b"/><path fill="url(#iCP2Jdc)" class="q-rok850b"/></g><g filter="url(#iNt5b9d)"><path class="yke8_ji8i"/><path fill="url(#igqdydc)" class="em_l9-b0x"/></g><g filter="url(#iaD0IWU)"><path class="vu91b_bab"/><path fill="url(#iy8iXdj)" class="h8pkbf-mw"/></g><g filter="url(#i9pSDHd)"><path fill="url(#iQL5z5c)" class="wyd8-jybr"/><path fill="url(#i9VqLDe)" class="wyd8-jybr"/><path fill="url(#iXCVpjb)" class="wyd8-jybr"/><path fill="url(#itV7w6c)" class="wyd8-jybr"/><path fill="url(#i3qQagb)" class="wyd8-jybr"/><path fill="url(#ita5fTd)" class="wyd8-jybr"/><path fill="url(#ipg8A2m)" class="wyd8-jybr"/><path fill="url(#i0lPLGd)" class="wyd8-jybr"/></g><path fill="url(#iNUfXee)" class="wyd8-jybr"/><g filter="url(#iogGLad)"><path class="llknyj7oy"/></g><path fill="url(#iJFpGxc)" class="hq6zf8gvs"/><path fill="url(#iGgS9AJ)" class="hq6zf8gvs"/><g filter="url(#imTPpXH)"><path class="uhvj0teru"/><path fill="url(#iAOHbLd)" class="z2z0djz5p"/></g><g filter="url(#ivYChMe)"><path stroke="url(#iksSVob)" class="ei-19obta"/></g><path class="j2nudi6ts"/><g filter="url(#inXOfKc)"><path class="kpp92jb4t"/></g><g filter="url(#iOem53b)"><path class="oxh6elbes"/></g><path class="ehixcpwic"/><path fill="url(#iaVDaIc)" class="amod97zvr"/><path class="bxp5an-ep"/><g filter="url(#iYdm8Bd)"><path class="ss77apb-p"/><path fill="url(#iKvuZXb)" class="lgb__abit"/></g><g filter="url(#i9YGkFe)"><path fill="url(#iGeJ5ub)" class="hd3sn2b_v"/></g><path class="ini5q7bll"/><path fill="url(#iB2mZRb)" class="ypsqohbpg"/><path class="wl4qnubcg"/><g filter="url(#i7XDCNR)"><path fill="url(#iHMDvmb)" class="ou3345_0z"/></g><g filter="url(#iGgk2Xc)"><ellipse transform="rotate(-27.914 13.534 9.88)" class="wyl40hu4l"/><ellipse fill="url(#iRWf7zb)" transform="rotate(-27.914 13.534 9.88)" class="wz3qf_bdy"/></g><g filter="url(#ieGzEiu)"><path class="m56dj9hql"/><path fill="url(#iXCo0hd)" class="x45o8rbzg"/><path fill="url(#iseAaNe)" class="x45o8rbzg"/></g><g filter="url(#ivIVB6o)"><path class="ldxygzbam"/><path fill="url(#i5sgMIb)" class="kwsmp-_oy"/><path fill="url(#iKgfZFc)" class="kwsmp-_oy"/></g><g filter="url(#i1At8ld)"><path stroke="url(#iz3s8rh)" class="q1asfk6jl"/></g><g filter="url(#i2Y76tc)"><path class="pe0sounxj"/></g><defs><radialGradient id="iFU4Jnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.685 13.074)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iQMk7Ed" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.87 13.342)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iq6NzJe" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.905 8.15)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="inNXKgb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.34 7.635)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iRudOEb" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.153 11.576)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="i5y0eNe" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.959 6.816)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="isu070c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.496 9.722)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iirQzkd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.638 7.98)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iOQdR0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.90444 -2.65026 2.0962 -.71536 20.72 7.288)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="iEg84Hb" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.845 9.686)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="igxWBac" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.16 -3.912)scale(3.79787 1.37073)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iHNqk0X" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.5824 -20.8203 0 16 18.372)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="gawd5obvo"/><stop offset="1" class="rn540obxc"/></radialGradient><radialGradient id="imqjm9c" cx="0" cy="0" r="1" gradientTransform="rotate(124.924 1.228 11.052)scale(12.8824 12.131)" gradientUnits="userSpaceOnUse"><stop class="y9rlcreuk"/><stop offset="1" class="xd0kopb5v"/></radialGradient><radialGradient id="ivjsgxd" cx="0" cy="0" r="1" gradientTransform="rotate(123.174 5.837 15.598)scale(11.5365 12.2083)" gradientUnits="userSpaceOnUse"><stop class="r3949-bju"/><stop offset="1" class="s9sui_61e"/></radialGradient><radialGradient id="iod3k0b" cx="0" cy="0" r="1" gradientTransform="rotate(100.184 -.325 14.065)scale(5.30229 7.65346)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="t-ehpbubw"/><stop offset="1" class="h61yu9bmy"/></radialGradient><radialGradient id="iyeCLFd" cx="0" cy="0" r="1" gradientTransform="matrix(5.4375 0 0 14.5199 23.18 29.622)" gradientUnits="userSpaceOnUse"><stop offset=".698" class="oj7ch-bkx"/><stop offset="1" class="ce13789qs"/></radialGradient><radialGradient id="i20rlAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.1762 .21924 0 23.68 29.955)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="x8ej_jb7y"/><stop offset="1" class="mjbwacbml"/></radialGradient><radialGradient id="iyAgBob" cx="0" cy="0" r="1" gradientTransform="matrix(-5.6875 0 0 -13.3438 9.555 29.779)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="wx3vdcbzg"/><stop offset="1" class="jug-l4bwb"/></radialGradient><radialGradient id="iLKBWPD" cx="0" cy="0" r="1" gradientTransform="matrix(.14062 -1.5668 5.45335 .48945 5.71 29.955)" gradientUnits="userSpaceOnUse"><stop class="x_0jnxbib"/><stop offset="1" class="wn7157b9l"/></radialGradient><radialGradient id="i92uFDa" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 0 0 -15.1051 8.383 29.955)" gradientUnits="userSpaceOnUse"><stop class="ujtti6ofv"/><stop offset="1" class="gewmlvbcg"/></radialGradient><radialGradient id="iRR6nWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.70312 .54687 -.67794 -.87163 19.711 23.404)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="l56m45bvi"/><stop offset="1" class="v2ucwt3jq"/></radialGradient><radialGradient id="isFAYCe" cx="0" cy="0" r="1" gradientTransform="rotate(111.034 1.943 12.516)scale(3.13667 4.32041)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="t6s1vnb2t"/><stop offset="1" class="zi8t_0buy"/></radialGradient><radialGradient id="ioWJHub" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53125 -3 0 20.742 15.341)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="mzeokobes"/><stop offset="1" class="qhzdg_bmj"/></radialGradient><radialGradient id="i9nPv5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.79294 -6.37953 0 19.492 15.403)" gradientUnits="userSpaceOnUse"><stop class="kuordwbwu"/><stop offset="1" class="mt9_xyb2a"/></radialGradient><radialGradient id="iKdWZUd" cx="0" cy="0" r="1" gradientTransform="rotate(126.363 3.443 13.942)scale(1.76569 1.94865)" gradientUnits="userSpaceOnUse"><stop class="su-lx9b4e"/><stop offset="1" class="fh2jv1bsu"/></radialGradient><radialGradient id="iLpatmc" cx="0" cy="0" r="1" gradientTransform="rotate(111.306 1.436 15.466)scale(1.67712 2.10568)" gradientUnits="userSpaceOnUse"><stop offset=".511" class="otqjsqgnm"/><stop offset="1" class="cz6js0bhr"/></radialGradient><radialGradient id="iP4scOX" cx="0" cy="0" r="1" gradientTransform="rotate(61.841 -5.517 21.083)scale(4.17178 5.32057)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="yiu1llk6x"/><stop offset="1" class="zlgz1t7ky"/></radialGradient><radialGradient id="ikd6jde" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 .60936 -.75278 -3.39724 16.586 17.122)" gradientUnits="userSpaceOnUse"><stop offset=".555" class="d6g38pbok"/><stop offset="1" class="d_zjfgb1l"/></radialGradient><radialGradient id="ifFIJMd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6537 -1.20346 1.36368 -.74073 10.909 12.182)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iFPrJEc" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.027 11.012)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iCP2Jdc" cx="0" cy="0" r="1" gradientTransform="matrix(1.20681 0 0 .5196 20.932 8.867)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="igqdydc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.379 10.685)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="iy8iXdj" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.693 5.287)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iQL5z5c" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.322 7.086)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="i9VqLDe" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.834 7.333)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iXCVpjb" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.825 16.543)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="itV7w6c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28468 7.37319 -9.2164 -1.60583 17.01 9.62)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="i3qQagb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.327 6.748)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="ita5fTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.289 9.617)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="ipg8A2m" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.91 9.389)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="i0lPLGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.37 7.301)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iNUfXee" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.083 11.105)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iAOHbLd" cx="0" cy="0" r="1" gradientTransform="rotate(-97.263 13.79 -1.336)scale(3.46338 1.35463)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="if6g757kf"/><stop offset="1" class="h0bxkibiw"/></radialGradient><radialGradient id="iaVDaIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.17 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iKvuZXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.941 10.06)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iB2mZRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.805 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iRWf7zb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.778 -1.557)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXCo0hd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.284 -4.118)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="iseAaNe" cx="0" cy="0" r="1" gradientTransform="matrix(1.14952 -1.97524 1.06043 .61714 12.037 6.875)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="i5sgMIb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.117 6.95)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iKgfZFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.197 3.018)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="iZLDGXU" width="15.268" height="15.768" x="8.478" y="1.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_932"/></filter><filter id="iiGfkqd" width="25.813" height="14.219" x="3.094" y="15.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".125"/></filter><filter id="iHXsGce" width="9.1" height="7.705" x="10.989" y="22.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".5"/></filter><filter id="ibsOGne" width="7.926" height="6.427" x="12.029" y="22.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.670588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_932"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.407843 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_932" result="effect2_innerShadow_4002_932"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.317647 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_932" result="effect3_innerShadow_4002_932"/></filter><filter id="ipLrdUY" width="3.095" height="3.11" x="14.16" y="18.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".25"/></filter><filter id="i4arNKb" width="11.606" height="4.825" x="10.289" y="15.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.223529 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_932"/></filter><filter id="i0J7OlR" width="3.368" height="3.218" x="9.693" y="8.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_932"/></filter><filter id="inxwn7d" width="3.218" height="3.468" x="19.206" y="8.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_932"/></filter><filter id="iNt5b9d" width="3.148" height="3.148" x="19.241" y="8.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".25"/></filter><filter id="iaD0IWU" width="2.848" height="2.848" x="9.897" y="9.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".175"/></filter><filter id="i9pSDHd" width="10.191" height="11.027" x="10.892" y="5.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.337255 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_932"/></filter><filter id="iogGLad" width="2.877" height="3.682" x="14.386" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".25"/></filter><filter id="imTPpXH" width="2.044" height="2.691" x="15.116" y="10.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.34902 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_932"/></filter><filter id="ivYChMe" width="3.702" height="1.526" x="14.136" y="12.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".05"/></filter><filter id="inXOfKc" width="3.001" height="1.285" x="16.93" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_932"/></filter><filter id="iOem53b" width="3.001" height="1.285" x="12.044" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_932"/></filter><filter id="iYdm8Bd" width=".787" height=".696" x="17.435" y="9.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".05"/></filter><filter id="i9YGkFe" width=".891" height=".913" x="18.275" y="9.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".1"/></filter><filter id="i7XDCNR" width=".986" height="1.04" x="13.832" y="9.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".1"/></filter><filter id="iGgk2Xc" width=".913" height=".704" x="13.078" y="9.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".05"/></filter><filter id="ieGzEiu" width="4.312" height="4.613" x="9.633" y="3.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_932"/><feGaussianBlur result="effect2_foregroundBlur_4002_932" stdDeviation=".2"/></filter><filter id="ivIVB6o" width="8.767" height="5.782" x="12.817" y="2.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_932"/><feGaussianBlur result="effect2_foregroundBlur_4002_932" stdDeviation=".125"/></filter><filter id="i1At8ld" width="1.145" height="2.31" x="12.796" y="3.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".1"/></filter><filter id="i2Y76tc" width="6.427" height="3.372" x="15.405" y="4.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_932" stdDeviation=".375"/></filter><linearGradient id="injMsxe" x1="20.681" x2="14.546" y1="3.621" y2="14.381" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="ia8zscL" x1="16" x2="16" y1="16.236" y2="30.341" gradientUnits="userSpaceOnUse"><stop offset=".866" class="tyjpv6bnm"/><stop offset="1" class="xyu2htzlq"/></linearGradient><linearGradient id="iyhUdBG" x1="26.992" x2="26.773" y1="30.247" y2="27.497" gradientUnits="userSpaceOnUse"><stop class="pmf-vsdxp"/><stop offset="1" class="w6_8my7ls"/></linearGradient><linearGradient id="iRJv8Rc" x1="8.586" x2="5.336" y1="25.154" y2="25.154" gradientUnits="userSpaceOnUse"><stop offset=".183" class="annwmpbcg"/><stop offset="1" class="l85-jsb-f"/></linearGradient><linearGradient id="i5XOWcD" x1="18.555" x2="13.805" y1="23.966" y2="27.31" gradientUnits="userSpaceOnUse"><stop class="big423byp"/><stop offset="1" class="zbo4__e4e"/></linearGradient><linearGradient id="iIuGzte" x1="15.992" x2="15.992" y1="22.857" y2="24.201" gradientUnits="userSpaceOnUse"><stop class="ash9yfbkf"/><stop offset="1" class="k-dn1jb7a"/></linearGradient><linearGradient id="ilz7GNd" x1="14.773" x2="20.117" y1="19.06" y2="17.154" gradientUnits="userSpaceOnUse"><stop class="umjrh49bx"/><stop offset="1" class="d7r2s6row"/></linearGradient><linearGradient id="iCIUDTd" x1="8.847" x2="23.223" y1="15.383" y2="15.383" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i9EbKOc" x1="8.846" x2="23.222" y1="15.352" y2="15.352" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iARTiEO" x1="9.693" x2="11.55" y1="10.66" y2="10.66" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="iJFpGxc" x1="20.375" x2="12.995" y1="10.692" y2="10.692" gradientUnits="userSpaceOnUse"><stop class="z14dz9exi"/><stop offset="1" class="o1uobmugz"/></linearGradient><linearGradient id="iGgS9AJ" x1="10.892" x2="12.341" y1="10.38" y2="10.38" gradientUnits="userSpaceOnUse"><stop class="f6x3qhriw"/><stop offset="1" class="onbz4ubrj"/></linearGradient><linearGradient id="iksSVob" x1="14.923" x2="15.384" y1="14.113" y2="13.401" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iGeJ5ub" x1="18.947" x2="18.634" y1="10.03" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHMDvmb" x1="14.549" x2="14.235" y1="10.03" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iz3s8rh" x1="12.879" x2="13.368" y1="3.621" y2="4.886" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-superhero-medium" /></template>
<style>
.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.amod97zvr {
  d: path("M18.171 9.5a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.annwmpbcg {
  stop-color: var(--svg-color--3e80f0, #3E80F0);
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.ash9yfbkf {
  stop-color: var(--svg-color--40a0f8, #40A0F8);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.big423byp {
  stop-color: var(--svg-color--47a1ff, #47A1FF);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.bxp5an-ep {
  fill: var(--svg-color--000, #000);
  d: path("M17.66 10.392a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.235");
}

.ce13789qs {
  stop-color: var(--svg-color--528adb, #528ADB);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cllop4bqc {
  d: path("M23.68 18.468v11.487h4.343v-.036c-.22-5.447-1.881-9.174-4.343-11.451");
}

.cu21d24az {
  d: path("M8.383 18.468v11.487H4.039v-.036c.22-5.447 1.882-9.174 4.344-11.451");
}

.cz6js0bhr {
  stop-color: var(--svg-color--d79d4a, #D79D4A);
}

.d_zjfgb1l {
  stop-color: var(--svg-color--7c4747, #7C4747);
}

.d6g38pbok {
  stop-color: var(--svg-color--7c4747, #7C4747);
  stop-opacity: 0;
}

.d7r2s6row {
  stop-color: var(--svg-color--ff3656, #FF3656);
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.ehixcpwic {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.378 9.227c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.ei-19obta {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.987 13.485a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.249 0c.089-.136-.062-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.em_l9-b0x {
  d: path("M20.815 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.evso7acss {
  d: path("M2.063 29.955c0-1.969.39-6.76 3.216-9.86C8.81 16.222 13.793 15.643 16 15.643s7.19.579 10.721 4.454c2.826 3.1 3.217 7.89 3.217 9.859z");
}

.f6x3qhriw {
  stop-color: var(--svg-color--ab2d46, #AB2D46);
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fh2jv1bsu {
  stop-color: var(--svg-color--f2bb43, #F2BB43);
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.gawd5obvo {
  stop-color: var(--svg-color--ff3b9a, #FF3B9A);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gewmlvbcg {
  stop-color: var(--svg-color--2154ca, #2154CA);
  stop-opacity: 0;
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h0bxkibiw {
  stop-color: var(--svg-color--c69a80, #C69A80);
  stop-opacity: 0;
}

.h61yu9bmy {
  stop-color: var(--svg-color--3a7ad3, #3A7AD3);
  stop-opacity: 0;
}

.h8pkbf-mw {
  d: path("M11.32 11.647a1.074 1.074 0 1 0 .001-2.148a1.074 1.074 0 0 0 0 2.148");
}

.hd3sn2b_v {
  d: path("M18.966 10.274a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hmnycxx5w {
  fill: var(--svg-color--4e9eff, #4E9EFF);
  d: path("M23.68 18.468v11.487h4.343v-.036c-.22-5.447-1.881-9.174-4.343-11.451");
}

.hq6zf8gvs {
  d: path("M10.912 9.313H10.9l.077 2.01h.315q.282 0 .534.12l.247.12c.09.04.178.08.267.11l.218.07c.425.13.88.14 1.306.02l.277-.08c.108-.03.217-.07.316-.12l.228-.11q.252-.12.534-.12h.346l.165-.669c.118-.39.264-.39.382 0l.094.668h.467q.282 0 .534.12l.208.1c.109.05.227.1.346.13l.307.09c.425.12.89.11 1.305-.04l.178-.06l.238-.09l.267-.12q.252-.12.534-.12h.394l.099-2.554l-.007-.106h-.387c-.247-.02-.494-.1-.712-.24l-.05-.03a2.2 2.2 0 0 0-.553-.28a2.16 2.16 0 0 0-1.306-.04l-.129.03c-.237.07-.465.17-.672.32s-.456.22-.713.22h-1.226c-.258 0-.505-.08-.712-.22l-.01-.01a2.3 2.3 0 0 0-.643-.31l-.09-.03c-.425-.12-.88-.12-1.305.02l-.04.01c-.207.07-.405.17-.593.29l-.03.03c-.217.14-.465.22-.722.22h-.288l-.003.08l.01.306z");
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.i9t6f2bxc {
  d: path("M3.344 29.955c0-1.887.355-6.479 2.92-9.45c3.207-3.715 7.732-4.269 9.736-4.269s6.529.554 9.736 4.269c2.565 2.971 2.92 7.563 2.92 9.45z");
}

.if6g757kf {
  stop-color: var(--svg-color--c69a80, #C69A80);
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.ijlx-8buq {
  cx: 15.708px;
  cy: 20.263px;
  fill: var(--svg-color--2f62b7, #2F62B7);
  rx: 1.048px;
  ry: 1.055px;
}

.ini5q7bll {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.597 9.227c-.654 0-1.205.45-1.355 1.06a.274.274 0 0 0 .267.34h2.231a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2nudi6ts {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.987 13.485a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.249 0c.089-.136-.062-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jcl-2hb7f {
  d: path("M16.031 15.638c-6.228 0-11.584 4.188-11.992 14.281v.036h23.984v-.036c-.408-10.093-5.764-14.28-11.992-14.28");
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jug-l4bwb {
  stop-color: var(--svg-color--407dbe, #407DBE);
}

.k-dn1jb7a {
  stop-color: var(--svg-color--4392f9, #4392F9);
  stop-opacity: 0;
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k7zk34bqa {
  d: path("m15.992 20.435l-5.04-3.023c-.323-.2-.663-.512-.663-.98c0-.497.585-.533.885-.544l4.818-.078l4.819.078c.3.01.884.047.884.543c0 .469-.34.781-.663.98z");
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kpp92jb4t {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.13 10.004c.265-.467.668-.835 1.537-.835c.38 0 .747.105 1.073.368c.269.218.233.496.024.6l-.556.317c-.652-.21-1.372-.24-2.078-.45");
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kuordwbwu {
  stop-color: var(--svg-color--bb1135, #BB1135);
}

.kwsmp-_oy {
  d: path("M15.384 2.783c-1.133-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.541 1.877.888c0-3.933-3.344-4.671-5.921-5.24z");
}

.l56m45bvi {
  stop-color: var(--svg-color--53b7ff, #53B7FF);
}

.l5ywhsb5i {
  fill-rule: evenodd;
  d: path("M23.173 11.983a3.25 3.25 0 0 0 .323-1.427a3.3 3.3 0 0 0-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.004a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.003.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.3 3.3 0 0 0-.324 1.407a3.213 3.213 0 0 0 3.218 3.218h8.582a3.213 3.213 0 0 0 3.218-3.218a3.3 3.3 0 0 0-.323-1.407a.51.51 0 0 1 0-.455m-12.26-2.672H10.9l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.46.051l-.083.194c-.226.561-.656.99-1.19 1.235l-.05.02l-.052.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l85-jsb-f {
  stop-color: var(--svg-color--3e77d8, #3E77D8);
}

.ldxygzbam {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.384 2.783c-1.133-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.541 1.877.888c0-3.933-3.344-4.671-5.921-5.24z");
}

.lgb__abit {
  d: path("M18.106 9.688c.063.085-.07.189-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llknyj7oy {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.595 10.35l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.494-.376-.613 0");
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.m56dj9hql {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M10.918 4.585c.566-.6 1.637-.6 2.131-.51l.396 1.29c-.253-.04-.296-.002-.485.183c-.138 1.093-1.376 1.756-2.887 2.197c-.148-1.492.109-2.38.845-3.16");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjbwacbml {
  stop-color: var(--svg-color--286adf, #286ADF);
  stop-opacity: 0;
}

.mt9_xyb2a {
  stop-color: var(--svg-color--bb1135, #BB1135);
  stop-opacity: 0;
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.mzeokobes {
  stop-color: var(--svg-color--f04451, #F04451);
}

.o1uobmugz {
  stop-color: var(--svg-color--c31251, #C31251);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oj7ch-bkx {
  stop-color: var(--svg-color--528adb, #528ADB);
  stop-opacity: 0;
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.onbz4ubrj {
  stop-color: var(--svg-color--ba3950, #BA3950);
  stop-opacity: 0;
}

.otqjsqgnm {
  stop-color: var(--svg-color--f6c546, #F6C546);
  stop-opacity: 0;
}

.ou3345_0z {
  d: path("M14.619 10.287c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.oumjgbbsr {
  d: path("M16.386 15.353c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.oxh6elbes {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.845 10.004c-.265-.467-.669-.835-1.537-.835c-.38 0-.747.105-1.073.368c-.269.218-.233.496-.024.6l.556.317c.651-.21 1.372-.24 2.078-.45");
}

.pbxi84b9i {
  fill: var(--svg-color--2f63d5, #2F63D5);
  d: path("M12.875 23.42a.885.885 0 0 0-.763 1.333l2.143 3.638a1.49 1.49 0 0 0 2.568 0l2.142-3.638a.885.885 0 0 0-.762-1.334z");
}

.pe0sounxj {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m18.394 6.392l-1.426.262a.688.688 0 1 1-.125-1.364h2.341c1.384 0 1.843 1.395 1.899 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmf-vsdxp {
  stop-color: var(--svg-color--4d87f8, #4D87F8);
}

.q-rok850b {
  d: path("M20.815 12.182a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.q1asfk6jl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.096 4.031c.023.243.235 1.157.545 1.71");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qhe9mm7xm {
  width: 4.109px;
  height: 5.399px;
  x: 13.933px;
  y: 13.298px;
  rx: 2.055px;
}

.qhzdg_bmj {
  stop-color: var(--svg-color--f04451, #F04451);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3949-bju {
  stop-color: var(--svg-color--4690e6, #4690E6);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.rn540obxc {
  stop-color: var(--svg-color--ee344d, #EE344D);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.s9sui_61e {
  stop-color: var(--svg-color--3e75e1, #3E75E1);
}

.skhx9acxb {
  cx: 15.992px;
  cy: 20.17px;
  rx: 1.048px;
  ry: 1.055px;
}

.ss77apb-p {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.106 9.688c.063.085-.07.189-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.su-lx9b4e {
  stop-color: var(--svg-color--fff14e, #FFF14E);
}

.t-ehpbubw {
  stop-color: var(--svg-color--3062ac, #3062AC);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t6s1vnb2t {
  stop-color: var(--svg-color--780438, #780438);
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.tyjpv6bnm {
  stop-color: var(--svg-color--790b2c, #790B2C);
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u537au68g {
  d: path("M11.302 12.182a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.uhvj0teru {
  fill: var(--svg-color--997261, #997261);
  d: path("m15.632 10.516l-.493 1.58a.5.5 0 0 0 .483.649h.73c.343 0 .585-.33.484-.65l-.493-1.579c-.106-.35-.6-.35-.71 0");
}

.ujtti6ofv {
  stop-color: var(--svg-color--2154ca, #2154CA);
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.umjrh49bx {
  stop-color: var(--svg-color--ce1f66, #CE1F66);
}

.v2ucwt3jq {
  stop-color: var(--svg-color--49a3ff, #49A3FF);
  stop-opacity: 0;
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vu91b_bab {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.32 11.647a1.074 1.074 0 1 0 .001-2.148a1.074 1.074 0 0 0 0 2.148");
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w6_8my7ls {
  stop-color: var(--svg-color--4b99ff, #4B99FF);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wdqycsape {
  d: path("M16.056 15.353h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.wl4qnubcg {
  fill: var(--svg-color--000, #000);
  d: path("M14.314 10.392a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.904a.5.5 0 0 0 .061-.235");
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wn7157b9l {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
  stop-opacity: 0;
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wx3vdcbzg {
  stop-color: var(--svg-color--407dbe, #407DBE);
  stop-opacity: 0;
}

.wyd8-jybr {
  d: path("M10.9 9.31h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.438l.051-.02q.028-.013.052-.021a2.3 2.3 0 0 0 1.19-1.235l.081-.194a.264.264 0 0 1 .462-.05a3.86 3.86 0 0 0 3.189 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.119 3.073c-.123 2.802-2.312 4.684-4.983 4.684c-2.672 0-4.86-1.882-4.983-4.684z");
}

.wyl40hu4l {
  cx: 13.534px;
  cy: 9.88px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.wz3qf_bdy {
  cx: 13.534px;
  cy: 9.88px;
  rx: 0.39px;
  ry: 0.197px;
}

.x_0jnxbib {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
}

.x45o8rbzg {
  d: path("M10.918 4.585c.566-.6 1.637-.6 2.131-.51l.396 1.29c-.253-.04-.296-.002-.485.183c-.138 1.093-1.376 1.756-2.887 2.197c-.148-1.492.109-2.38.845-3.16");
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x8ej_jb7y {
  stop-color: var(--svg-color--286adf, #286ADF);
}

.xd0kopb5v {
  stop-color: var(--svg-color--bf2370, #BF2370);
  stop-opacity: 0;
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xyu2htzlq {
  stop-color: var(--svg-color--790b2c, #790B2C);
  stop-opacity: 0;
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y9rlcreuk {
  stop-color: var(--svg-color--bf2370, #BF2370);
}

.yiu1llk6x {
  stop-color: var(--svg-color--8d546a, #8D546A);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yke8_ji8i {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.815 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ypsqohbpg {
  d: path("M13.803 9.5a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.z-t54tbit {
  d: path("M13.13 22.998a.95.95 0 0 0-.818 1.432l2.302 3.907a1.6 1.6 0 0 0 2.757 0l2.301-3.907a.95.95 0 0 0-.819-1.433z");
}

.z14dz9exi {
  stop-color: var(--svg-color--ff1781, #FF1781);
}

.z2z0djz5p {
  d: path("m15.632 10.516l-.493 1.58a.5.5 0 0 0 .483.649h.73c.343 0 .585-.33.484-.65l-.493-1.579c-.106-.35-.6-.35-.71 0");
}

.zbo4__e4e {
  stop-color: var(--svg-color--3f83f1, #3F83F1);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zi8t_0buy {
  stop-color: var(--svg-color--780438, #780438);
  stop-opacity: 0;
}

.zlgz1t7ky {
  stop-color: var(--svg-color--b47f73, #B47F73);
}

</style>
