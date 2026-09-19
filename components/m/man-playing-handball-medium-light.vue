<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iGwOpxd)" class="q12x_3brx"/><path fill="url(#idZHjgc)" class="q12x_3brx"/><path fill="url(#isS8u3b)" class="q12x_3brx"/><path class="e_8ki4b8j"/><path fill="url(#iySypzb)" class="zguchrbop"/><path fill="url(#iJVlpmi)" class="zguchrbop"/><path class="p8hed8p1i"/><path fill="url(#i8VQyhb)" class="g9d0ovbvp"/><path fill="url(#iTNgb2y)" class="g9d0ovbvp"/><path fill="url(#i6FwaDc)" class="g9d0ovbvp"/><path fill="url(#iAJMqce)" class="g9d0ovbvp"/><path fill="url(#izzU55b)" class="qum9srb-r"/><path fill="url(#ixh406b)" class="qum9srb-r"/><path fill="url(#iCfwbfb)" class="qum9srb-r"/><path fill="url(#i31pOtc)" class="qum9srb-r"/><g filter="url(#i8WZPwE)"><path class="amd51vbjg"/><path fill="url(#i6AMUmc)" class="mfs1vbcha"/></g><path clip-rule="evenodd" class="yh_1i3b0p"/><path fill="url(#iZ1F9vd)" clip-rule="evenodd" class="qn7308bds"/><path fill="url(#iy2hizc)" clip-rule="evenodd" class="qn7308bds"/><path fill="url(#irLq2Eo)" clip-rule="evenodd" class="qn7308bds"/><path fill="url(#i3wPhXd)" transform="rotate(-23.31 13.976 8.014)" class="d_6rbhb8w"/><g filter="url(#ikC549d)"><path class="aok2xze5b"/><path fill="url(#iGE9VWb)" class="sld9yacoe"/><path fill="url(#iyIhfTP)" class="sld9yacoe"/><path fill="url(#iOHXHyc)" class="sld9yacoe"/><path fill="url(#iNwsQWc)" class="sld9yacoe"/><path fill="url(#iG7xVec)" class="sld9yacoe"/></g><path fill="url(#iD3yzkc)" class="edgroyb3v"/><path fill="url(#iAciTGb)" class="edgroyb3v"/><path fill="url(#iiDMUtc)" class="edgroyb3v"/><path fill="url(#iq6Q1Wl)" class="edgroyb3v"/><path class="rq_vxdcfr"/><path fill="url(#im7C13b)" class="c5snbbbrs"/><path fill="url(#i21JStR)" class="c5snbbbrs"/><path fill="url(#itc1s5b)" class="c5snbbbrs"/><path class="kmd3qcb-j"/><path fill="url(#iiwTGEe)" class="e0lhu47_k"/><path fill="url(#izYIVRu)" class="e0lhu47_k"/><path fill="url(#iRYIdJc)" class="e0lhu47_k"/><path fill="url(#ir7LSIc)" class="e0lhu47_k"/><path fill="url(#idaGKtb)" class="e0lhu47_k"/><g filter="url(#i8a4Hwa)"><path clip-rule="evenodd" class="sj-lltwha"/></g><path fill="url(#iSUeAtt)" clip-rule="evenodd" class="rrye52blb"/><path fill="url(#iRE3Qtc)" clip-rule="evenodd" class="rrye52blb"/><path class="o9l97ibjl"/><path fill="url(#iEVRF8d)" class="a_oyxelii"/><path fill="url(#iHCzuPb)" class="a_oyxelii"/><path fill="url(#iKcjUje)" class="a_oyxelii"/><rect fill="url(#iokKzGc)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><rect fill="url(#iFg3qDc)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><path fill="url(#ifZbC7c)" class="mqryp-bup"/><path fill="url(#iWmhT4j)" class="vtxj36boz"/><path fill="url(#iZiHlOe)" class="vtxj36boz"/><path fill="url(#iQzraKd)" class="t3ncs1j8m"/><path fill="url(#iBmo3in)" class="t3ncs1j8m"/><g filter="url(#iHzgW8b)"><path fill="url(#ibBvqNd)" class="pcwcq6ykk"/></g><path fill="url(#inqL0Pd)" class="pb93aprhh"/><path fill="url(#ipDfQxd)" class="pb93aprhh"/><path fill="url(#iFMDzle)" class="pb93aprhh"/><path fill="url(#iVgiUxb)" class="pb93aprhh"/><path fill="url(#iESVPYb)" class="pb93aprhh"/><g filter="url(#i0aVr6d)"><rect class="wdluo8w4e"/></g><path fill="url(#isEh5Zc)" class="hamlfdble"/><path fill="url(#ipxz7Od)" class="hamlfdble"/><g filter="url(#iJVXlDb)"><path fill="url(#iAHYEcb)" class="f19yxrbij"/><path fill="url(#itkHerb)" class="f19yxrbij"/><path fill="url(#irxc9Jc)" class="f19yxrbij"/><path fill="url(#idbtPPb)" class="f19yxrbij"/></g><g filter="url(#ic5D4Be)"><path fill="url(#iBeD7Ku)" class="y05m73b2m"/><path fill="url(#ivM5jFc)" class="y05m73b2m"/><path fill="url(#iCLc8Qd)" class="y05m73b2m"/></g><path fill="url(#iO4Jnzq)" class="hdiy9b3sm"/><path fill="url(#i87zvkc)" class="hdiy9b3sm"/><path fill="url(#iyN1UFe)" class="hdiy9b3sm"/><path clip-rule="evenodd" class="drvdfsb5b"/><path class="jmg7nbbxx"/><path fill="url(#i06FvWd)" class="msttj0b6y"/><path fill="url(#i7OZ7se)" class="tio1oi0im"/><ellipse fill="url(#ilNQNte)" transform="rotate(24.61 12.846 6.044)" class="yuovwfb9j"/><g filter="url(#i4HaTSI)"><path clip-rule="evenodd" class="egwphlmdk"/></g><defs><radialGradient id="i8VQyhb" cx="0" cy="0" r="1" gradientTransform="matrix(.61864 2.14418 -1.49974 .4327 18.926 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="q359-ccqt"/><stop offset="1" class="xezvpxvhe"/></radialGradient><radialGradient id="iTNgb2y" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 18.88 22.28)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="ez6yh-y9m"/><stop offset="1" class="g0lloqbmi"/></radialGradient><radialGradient id="i6FwaDc" cx="0" cy="0" r="1" gradientTransform="matrix(.80677 2.5012 -1.15566 .37276 16.338 22.544)" gradientUnits="userSpaceOnUse"><stop class="atwm-qoon"/><stop offset="1" class="ovos4t_7k"/></radialGradient><radialGradient id="iAJMqce" cx="0" cy="0" r="1" gradientTransform="rotate(71.565 -6.364 23.576)scale(.54352 3.09962)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="a_wk1gzgh"/><stop offset="1" class="spf2xjb6v"/></radialGradient><radialGradient id="izzU55b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 12.825 19.514)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="g_c95ob_h"/><stop offset="1" class="yb5t-ebeb"/></radialGradient><radialGradient id="ixh406b" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 10.934 8.218)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="aqx-_1b_m"/><stop offset="1" class="gn7z4wb2i"/></radialGradient><radialGradient id="iCfwbfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.114 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="s_sh9varo"/><stop offset=".979" class="b2logdb4l"/></radialGradient><radialGradient id="i6AMUmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 16.614 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iZ1F9vd" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.529 4.431)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="swgsx6bpm"/><stop offset="1" class="wcx06_c5w"/></radialGradient><radialGradient id="iy2hizc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 10.926 11.811)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="so5pusb0b"/><stop offset=".952" class="ifv48cbic"/></radialGradient><radialGradient id="irLq2Eo" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 10.63 11.764)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="apa7qrbhd"/><stop offset="1" class="g7rslpl_w"/></radialGradient><radialGradient id="i3wPhXd" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 14.966 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="qik8kac6n"/><stop offset=".75" class="d8jx6bckt"/></radialGradient><radialGradient id="iGE9VWb" cx="0" cy="0" r="1" gradientTransform="matrix(.0293 -5.32953 3.38376 .0186 14.816 17.472)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="dyygb2yxz"/><stop offset="1" class="jyyx2-bie"/></radialGradient><radialGradient id="iyIhfTP" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50773 .13384 -.33514 -6.2795 18.298 14.615)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="boe213jez"/><stop offset="1" class="n8m7rnb1b"/></radialGradient><radialGradient id="iOHXHyc" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.527 10.23)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="gkcpx30-s"/><stop offset="1" class="fxro0tyoi"/></radialGradient><radialGradient id="iNwsQWc" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 16.91 11.233)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="ekxdyp1yu"/><stop offset="1" class="zg01gt89b"/></radialGradient><radialGradient id="iG7xVec" cx="0" cy="0" r="1" gradientTransform="rotate(-170.407 9.956 6.195)scale(6.31116 10.4533)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="zbyobmbvc"/><stop offset=".957" class="rmf1gzb-v"/></radialGradient><radialGradient id="iAciTGb" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 6.675 29.938)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iq6Q1Wl" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.423 12.192)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iiwTGEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.124 17.331)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="izYIVRu" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.435 22.802)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iRYIdJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.173 18.126)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="idaGKtb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 13.704 17.342)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="iRE3Qtc" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.77 7.069)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="bg8bjl54k"/><stop offset="1" class="mdp6qlbos"/></radialGradient><radialGradient id="iHCzuPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.33186 -.12063 .2037 2.249 14.601 10.846)" gradientUnits="userSpaceOnUse"><stop class="y6bw3v3vv"/><stop offset="1" class="igyzmj7fv"/></radialGradient><radialGradient id="iKcjUje" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 19.656 9.918)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="mmjlr5d2n"/><stop offset="1" class="rh-0l3b-i"/></radialGradient><radialGradient id="ibBvqNd" cx="0" cy="0" r="1" gradientTransform="rotate(-149.027 6.18 5.213)scale(1.15719 1.60341)" gradientUnits="userSpaceOnUse"><stop class="zmktv7koj"/><stop offset="1" class="mnxdxy3jn"/></radialGradient><radialGradient id="inqL0Pd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 11.86 .42)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ipDfQxd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.727 -9.355)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="iFMDzle" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 20.567 4.249)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iVgiUxb" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.05 4.184)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iESVPYb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.727 -3.655)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><radialGradient id="isEh5Zc" cx="0" cy="0" r="1" gradientTransform="matrix(.50349 .27238 -.38447 .7107 11.582 7.058)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="rcpmccbyc"/><stop offset=".684" class="wdglv_bwm"/></radialGradient><radialGradient id="ipxz7Od" cx="0" cy="0" r="1" gradientTransform="matrix(-.12684 -.308 .46222 -.19035 12.01 7.392)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="itkHerb" cx="0" cy="0" r="1" gradientTransform="matrix(-.89142 -.0496 .06048 -1.08682 15.452 6.316)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="irxc9Jc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.48059 2.12951 0 12.392 7.57)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="nkfrpdbdq"/><stop offset="1" class="eqwiy2pxg"/></radialGradient><radialGradient id="idbtPPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4127 -.6436 0 13.267 6.364)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="iBeD7Ku" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6317 3.30158 -3.74378 -4.11812 17.432 3.502)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="n03tmgbfr"/><stop offset="1" class="a7758ab4t"/></radialGradient><radialGradient id="ivM5jFc" cx="0" cy="0" r="1" gradientTransform="matrix(.4168 2.8343 -1.2521 .18413 17.32 4.294)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="pmcqb6bbe"/><stop offset="1" class="obdoohpwg"/></radialGradient><radialGradient id="iCLc8Qd" cx="0" cy="0" r="1" gradientTransform="matrix(1.58475 -.09905 .19437 3.1099 11.836 4.152)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ozwza9bad"/><stop offset="1" class="mok6a1b9k"/></radialGradient><radialGradient id="iO4Jnzq" cx="0" cy="0" r="1" gradientTransform="matrix(.76761 -.22286 .10877 .37466 15.214 6.19)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="i87zvkc" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 4.071 12.159)scale(1.26906 1.32241)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="i06FvWd" cx="0" cy="0" r="1" gradientTransform="matrix(.28889 0 0 .56127 12.955 6.393)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i7OZ7se" cx="0" cy="0" r="1" gradientTransform="matrix(.26412 0 0 .57158 12.778 6.416)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iGwOpxd" x1="11.364" x2="9.677" y1="26.108" y2="26.358" gradientUnits="userSpaceOnUse"><stop class="s0d_o1h9v"/><stop offset="1" class="q1-w0b0qt"/></linearGradient><linearGradient id="idZHjgc" x1="8.93" x2="9.665" y1="24.418" y2="24.277" gradientUnits="userSpaceOnUse"><stop offset=".237" class="l2quysbsq"/><stop offset="1" class="qibnn1bya"/></linearGradient><linearGradient id="isS8u3b" x1="11.286" x2="10.856" y1="22.709" y2="22.811" gradientUnits="userSpaceOnUse"><stop class="lyz1uln4w"/><stop offset="1" class="pvjw0ujzi"/></linearGradient><linearGradient id="iySypzb" x1="22.817" x2="22.759" y1="24.6" y2="23.377" gradientUnits="userSpaceOnUse"><stop class="afqpej-7d"/><stop offset="1" class="aft-xhbkd"/><stop offset="1" class="cll88gg-t"/></linearGradient><linearGradient id="iJVlpmi" x1="22.196" x2="22.196" y1="22.452" y2="23.361" gradientUnits="userSpaceOnUse"><stop class="okh6_pbqf"/><stop offset="1" class="u1j_tu46h"/></linearGradient><linearGradient id="i31pOtc" x1="10.659" x2="10.659" y1="18.631" y2="19.952" gradientUnits="userSpaceOnUse"><stop class="n0ztdwmxa"/><stop offset="1" class="ql2kv4b4e"/></linearGradient><linearGradient id="iD3yzkc" x1="9.864" x2="11.395" y1="28.92" y2="28.92" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iiDMUtc" x1="9.427" x2="9.427" y1="29.938" y2="29.616" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="im7C13b" x1="25.352" x2="25.949" y1="22.068" y2="23.186" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i21JStR" x1="25.602" x2="26.296" y1="25.019" y2="24.152" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="itc1s5b" x1="27.316" x2="26.923" y1="24.152" y2="24.327" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ir7LSIc" x1="13.336" x2="13.786" y1="17.398" y2="18.466" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="iSUeAtt" x1="21.364" x2="21.177" y1="11.03" y2="10.092" gradientUnits="userSpaceOnUse"><stop offset=".076" class="bf4ns_o8j"/><stop offset="1" class="oi5imboky"/></linearGradient><linearGradient id="iEVRF8d" x1="18.207" x2="17.448" y1="12.177" y2="9.467" gradientUnits="userSpaceOnUse"><stop class="a_xmkojdq"/><stop offset="1" class="u_pd93bvm"/></linearGradient><linearGradient id="iokKzGc" x1="25.013" x2="23.016" y1="6.218" y2="6.288" gradientUnits="userSpaceOnUse"><stop offset=".149" class="zgff__bcr"/><stop offset="1" class="w-g7jabxf"/></linearGradient><linearGradient id="iFg3qDc" x1="24.329" x2="24.328" y1="6.762" y2="6.575" gradientUnits="userSpaceOnUse"><stop class="ah5butb7g"/><stop offset="1" class="m-22afbga"/></linearGradient><linearGradient id="ifZbC7c" x1="4.29" x2="7.829" y1="11.436" y2="11.436" gradientUnits="userSpaceOnUse"><stop class="dosa6sbas"/><stop offset=".588" class="gd67z4bal"/></linearGradient><linearGradient id="iWmhT4j" x1="4.236" x2="6.799" y1="11.876" y2="11.876" gradientUnits="userSpaceOnUse"><stop class="dosa6sbas"/><stop offset=".588" class="gd67z4bal"/></linearGradient><linearGradient id="iZiHlOe" x1="5.154" x2="5.154" y1="12.509" y2="12.064" gradientUnits="userSpaceOnUse"><stop class="x9uaycblj"/><stop offset="1" class="pnjqveb_u"/></linearGradient><linearGradient id="iQzraKd" x1="4.645" x2="6.739" y1="12.459" y2="12.459" gradientUnits="userSpaceOnUse"><stop class="lpv-lnbtt"/><stop offset=".588" class="gex5jb8qh"/></linearGradient><linearGradient id="iBmo3in" x1="5.395" x2="5.395" y1="13.092" y2="12.647" gradientUnits="userSpaceOnUse"><stop class="x3uyqiwdn"/><stop offset="1" class="l_u_tcbng"/></linearGradient><linearGradient id="iAHYEcb" x1="15.122" x2="12.098" y1="7.099" y2="7.28" gradientUnits="userSpaceOnUse"><stop class="laomgc3gs"/><stop offset="1" class="eur0hut6l"/></linearGradient><linearGradient id="iyN1UFe" x1="15.156" x2="15.313" y1="6.263" y2="6.276" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="ilNQNte" x1="12.771" x2="12.967" y1="6.004" y2="6.068" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="i8WZPwE" width="4.141" height="6.811" x="15.901" y="15.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23784"/></filter><filter id="ikC549d" width="5.768" height="8.746" x="12.843" y="8.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.443137 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23784"/></filter><filter id="i8a4Hwa" width="9.915" height="8.775" x="15.493" y="2.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.466667 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23784"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.603922 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23784" result="effect2_innerShadow_3987_23784"/></filter><filter id="iHzgW8b" width="2.43" height="2.868" x="6.814" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.529412 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23784"/></filter><filter id="i0aVr6d" width="2.065" height=".799" x="4.564" y="11.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23784" stdDeviation=".15"/></filter><filter id="iJVXlDb" width="4.683" height="5.534" x="11.898" y="4.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.541176 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23784"/></filter><filter id="ic5D4Be" width="6.724" height="5.754" x="11.445" y="2.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.94902 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23784"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.74902 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23784" result="effect2_innerShadow_3987_23784"/></filter><filter id="i4HaTSI" width="1.175" height=".679" x="12.635" y="4.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.278431 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23784"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-playing-handball-medium-light" /></template>
<style>
.a_oyxelii {
  d: path("m19.732 11.597l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
}

.a_wk1gzgh {
  stop-color: var(--svg-color--2e7ef2, #2E7EF2);
}

.a_xmkojdq {
  stop-color: var(--svg-color--1a65dc, #1A65DC);
}

.a7758ab4t {
  stop-color: var(--svg-color--ffdaa9, #FFDAA9);
}

.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.afqpej-7d {
  stop-color: var(--svg-color--bb778c, #BB778C);
}

.aft-xhbkd {
  stop-color: var(--svg-color--ce918e, #CE918E);
  stop-opacity: 0;
}

.ah5butb7g {
  stop-color: var(--svg-color--5c7ec9, #5C7EC9);
}

.amd51vbjg {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M16.55 22.745s-.464-1.232-.64-2.275c-.176-1.044 2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.982-3.133 1.16");
}

.aok2xze5b {
  fill: var(--svg-color--3584e5, #3584E5);
  d: path("m15.493 9.4l.674-.168a1.75 1.75 0 0 1 .713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.apa7qrbhd {
  stop-color: var(--svg-color--c8926f, #C8926F);
}

.aqx-_1b_m {
  stop-color: var(--svg-color--4b67e4, #4B67E4);
}

.atwm-qoon {
  stop-color: var(--svg-color--529af1, #529AF1);
}

.b2logdb4l {
  stop-color: var(--svg-color--5daef5, #5DAEF5);
}

.b6kb336ra {
  width: 2.533px;
  height: 1.362px;
  x: 22.49px;
  y: 5.391px;
  rx: 0.2px;
}

.bc_6ftbdd {
  stop-color: var(--svg-color--ddd9e2, #DDD9E2);
}

.bf4ns_o8j {
  stop-color: var(--svg-color--b97782, #B97782);
}

.bg8bjl54k {
  stop-color: var(--svg-color--e1b898, #E1B898);
}

.boe213jez {
  stop-color: var(--svg-color--4990db, #4990DB);
}

.c-xbvquvy {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
}

.c2ukjabcr {
  stop-color: var(--svg-color--4d318d, #4D318D);
}

.c5snbbbrs {
  d: path("m25.947 22.035l-1.294.557l.035 1.711c.33.288 1.104 1.065 1.808 1.602c.46.35.894.355 1.192.295c.226-.045.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.117");
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.ccv6f1brb {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
  stop-opacity: 0;
}

.cll88gg-t {
  stop-color: var(--svg-color--ac787c, #AC787C);
  stop-opacity: 0;
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.d_6rbhb8w {
  d: path("M13.976 8.014h2.217v3.3h-2.217z");
}

.d8jx6bckt {
  stop-color: var(--svg-color--cb9b80, #CB9B80);
}

.dosa6sbas {
  stop-color: var(--svg-color--f9be9f, #F9BE9F);
}

.drvdfsb5b {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.45 7.592a.13.13 0 0 1-.002.187c-.252.247-.616.31-.731.322a.132.132 0 1 1-.027-.263c.099-.01.387-.065.573-.247a.13.13 0 0 1 .187.001");
}

.dyygb2yxz {
  stop-color: var(--svg-color--3369cc, #3369CC);
}

.e_8ki4b8j {
  fill: var(--svg-color--e1ac97, #E1AC97);
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.e0lhu47_k {
  d: path("M18.3 15.613s-4.632 1.787-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.198.278c1.085-.572 2.045-1.031 3.183-1.726c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.492-1.322-.684-1.704");
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.edgroyb3v {
  d: path("m7.403 28.647l2.214-1.072l1.575.752l-.014 1.34a.253.253 0 0 1-.252.249l-3.854.022c-.221.001-.418-.15-.395-.37c.046-.452.333-.736.726-.921");
}

.egwphlmdk {
  fill: var(--svg-color--945f3d, #945F3D);
  fill-rule: evenodd;
  d: path("M13.475 5.51c-.156-.111-.383-.117-.53-.117a.211.211 0 1 1 0-.423h.011c.136 0 .49 0 .765.197a.211.211 0 0 1-.246.343");
}

.ekxdyp1yu {
  stop-color: var(--svg-color--2a6ae2, #2A6AE2);
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.eqwiy2pxg {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
  stop-opacity: 0;
}

.eur0hut6l {
  stop-color: var(--svg-color--e3ab8e, #E3AB8E);
}

.ez6yh-y9m {
  stop-color: var(--svg-color--3083ff, #3083FF);
  stop-opacity: 0;
}

.f19yxrbij {
  d: path("M12.127 5.577c.04-.846.315-1.254.444-1.374h3.943l.066 3.343c-.915 2.241-3.71 2.337-4.127 1.527s-.373-2.516-.326-3.496");
}

.ft5dv1b6b {
  fill: none;
}

.fxro0tyoi {
  stop-color: var(--svg-color--4784cd, #4784CD);
  stop-opacity: 0;
}

.g_c95ob_h {
  stop-color: var(--svg-color--319eff, #319EFF);
}

.g0lloqbmi {
  stop-color: var(--svg-color--5872fa, #5872FA);
}

.g7rslpl_w {
  stop-color: var(--svg-color--c8926f, #C8926F);
  stop-opacity: 0;
}

.g9d0ovbvp {
  d: path("m16.942 23.975l-.398-1.297l2.906-1.383l.203 1.125h.258c.162.9.172 2.141.156 2.649c-.041.013-.301.056-.914.125c-1.412.225-2.062-.719-2.21-1.219");
}

.gd67z4bal {
  stop-color: var(--svg-color--d0937d, #D0937D);
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gex5jb8qh {
  stop-color: var(--svg-color--cf927e, #CF927E);
}

.gkcpx30-s {
  stop-color: var(--svg-color--4784cd, #4784CD);
}

.gn7z4wb2i {
  stop-color: var(--svg-color--3382fa, #3382FA);
  stop-opacity: 0;
}

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.hamlfdble {
  d: path("M11.89 6.595c.165-.155.25-.386.272-.482h.19V7.3c-.227.145-.551.122-.648-.095c-.082-.186-.02-.417.186-.61");
}

.hdiy9b3sm {
  d: path("m15.054 7.114l.21-1.521a.768.768 0 0 1-.21 1.52");
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.ifv48cbic {
  stop-color: var(--svg-color--be7782, #BE7782);
}

.igyzmj7fv {
  stop-color: var(--svg-color--59a5ed, #59A5ED);
  stop-opacity: 0;
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.j23k_cb2p {
  stop-color: var(--svg-color--9c959a, #9C959A);
  stop-opacity: 0;
}

.j2u_3dtev {
  stop-color: var(--svg-color--908582, #908582);
  stop-opacity: 0;
}

.j96xv6b5h {
  stop-color: var(--svg-color--917ea3, #917EA3);
  stop-opacity: 0;
}

.jjj62-byh {
  stop-color: var(--svg-color--66638b, #66638B);
}

.jmg7nbbxx {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.662 6.416h1.044c0-.414-.233-.75-.522-.75c-.288 0-.522.336-.522.75");
}

.jyyx2-bie {
  stop-color: var(--svg-color--3369cc, #3369CC);
  stop-opacity: 0;
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.kmd3qcb-j {
  fill: var(--svg-color--918996, #918996);
  d: path("M18.3 15.613s-4.632 1.787-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.198.278c1.085-.572 2.045-1.031 3.183-1.726c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.492-1.322-.684-1.704");
}

.ksl77bchk {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
  stop-opacity: 0;
}

.l_u_tcbng {
  stop-color: var(--svg-color--d38f87, #D38F87);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l2quysbsq {
  stop-color: var(--svg-color--ffc3a5, #FFC3A5);
}

.laomgc3gs {
  stop-color: var(--svg-color--db9f84, #DB9F84);
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lpv-lnbtt {
  stop-color: var(--svg-color--f8bea1, #F8BEA1);
}

.lyz1uln4w {
  stop-color: var(--svg-color--ca907f, #CA907F);
}

.m-22afbga {
  stop-color: var(--svg-color--5c7ec9, #5C7EC9);
  stop-opacity: 0;
}

.m5_tnryam {
  stop-color: var(--svg-color--66638b, #66638B);
  stop-opacity: 0;
}

.mdp6qlbos {
  stop-color: var(--svg-color--d3a387, #D3A387);
  stop-opacity: 0;
}

.mfs1vbcha {
  d: path("M16.55 22.745s-.464-1.232-.64-2.275c-.176-1.044 2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.982-3.133 1.16");
}

.mge9r1s9g {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
  stop-opacity: 0;
}

.mmjlr5d2n {
  stop-color: var(--svg-color--53adfd, #53ADFD);
}

.mnxdxy3jn {
  stop-color: var(--svg-color--3a6cbb, #3A6CBB);
}

.mok6a1b9k {
  stop-color: var(--svg-color--ffe8b5, #FFE8B5);
  stop-opacity: 0;
}

.mqryp-bup {
  d: path("M4.624 11.557a.44.44 0 0 1 .44-.44h1.373c.113 0 .54.008.9.147l.109.34l-.403.393h-1.98a.44.44 0 0 1-.44-.44");
}

.msttj0b6y {
  d: path("M13.302 6.416v-.004c0-.339-.145-.613-.324-.613s-.324.274-.324.613v.004z");
}

.n03tmgbfr {
  stop-color: var(--svg-color--ffe0af, #FFE0AF);
}

.n0ztdwmxa {
  stop-color: var(--svg-color--4493c4, #4493C4);
}

.n8gqlhnrc {
  stop-color: var(--svg-color--9583a6, #9583A6);
  stop-opacity: 0;
}

.n8m7rnb1b {
  stop-color: var(--svg-color--458fe6, #458FE6);
  stop-opacity: 0;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ne985-vqe {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
  stop-opacity: 0;
}

.nkfrpdbdq {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
}

.o9l97ibjl {
  fill: var(--svg-color--279fea, #279FEA);
  d: path("m19.732 11.597l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
}

.obdoohpwg {
  stop-color: var(--svg-color--fff4bb, #FFF4BB);
  stop-opacity: 0;
}

.oi5imboky {
  stop-color: var(--svg-color--cb9089, #CB9089);
  stop-opacity: 0;
}

.okh6_pbqf {
  stop-color: var(--svg-color--d5a887, #D5A887);
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.ovos4t_7k {
  stop-color: var(--svg-color--388dfb, #388DFB);
  stop-opacity: 0;
}

.ozwza9bad {
  stop-color: var(--svg-color--ffe8b5, #FFE8B5);
}

.p8hed8p1i {
  fill: var(--svg-color--2badff, #2BADFF);
  d: path("m16.942 23.975l-.398-1.297l2.906-1.383l.203 1.125h.258c.162.9.172 2.141.156 2.649c-.041.013-.301.056-.914.125c-1.412.225-2.062-.719-2.21-1.219");
}

.pb93aprhh {
  d: path("M24.553 4.125a2.063 2.063 0 1 1-4.125 0a2.063 2.063 0 0 1 4.125 0");
}

.pcwcq6ykk {
  d: path("M7.828 11.587a.197.197 0 0 1 .257-.09c.244.112.695.325.974.496c.085.052.108.16.061.247l-1.028 1.906a.186.186 0 0 1-.223.091a4 4 0 0 1-.975-.495a.19.19 0 0 1-.057-.247z");
}

.pfu46_y1s {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
}

.pmcqb6bbe {
  stop-color: var(--svg-color--fff4bb, #FFF4BB);
}

.pnjqveb_u {
  stop-color: var(--svg-color--de9d8a, #DE9D8A);
  stop-opacity: 0;
}

.pvjw0ujzi {
  stop-color: var(--svg-color--dba390, #DBA390);
  stop-opacity: 0;
}

.q1-w0b0qt {
  stop-color: var(--svg-color--e9ae95, #E9AE95);
}

.q12x_3brx {
  d: path("m9.614 27.725l-1-5.18l2.57-.476v6.36z");
}

.q1yj_xkrc {
  stop-color: var(--svg-color--504b8a, #504B8A);
}

.q359-ccqt {
  stop-color: var(--svg-color--4fbcff, #4FBCFF);
}

.q8c7r9fut {
  stop-color: var(--svg-color--4a4970, #4A4970);
  stop-opacity: 0;
}

.qdq-erb7u {
  stop-color: var(--svg-color--e5a88d, #E5A88D);
}

.qh9tdvimg {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
}

.qibnn1bya {
  stop-color: var(--svg-color--eeb096, #EEB096);
  stop-opacity: 0;
}

.qik8kac6n {
  stop-color: var(--svg-color--bb754f, #BB754F);
}

.ql2kv4b4e {
  stop-color: var(--svg-color--2ba8f5, #2BA8F5);
  stop-opacity: 0;
}

.qmcjcvbdo {
  stop-color: var(--svg-color--adaaad, #ADAAAD);
  stop-opacity: 0;
}

.qn7308bds {
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 0 1 .993 2.075c-3.032 1.451-6.188.804-8.137-.702c-.512-.376-.471-.93-.095-1.442");
}

.qum9srb-r {
  d: path("m10.2 19.077l1.016-.446l1.61 2.836l-1.563.469v.422l-2.68.258c-.073-.399-.2-1.251.102-2.016c.335-.848 1.148-1.362 1.515-1.523");
}

.rcpmccbyc {
  stop-color: var(--svg-color--fec19d, #FEC19D);
}

.rdgulqvms {
  stop-color: var(--svg-color--e1a38b, #E1A38B);
  stop-opacity: 0;
}

.rh-0l3b-i {
  stop-color: var(--svg-color--389df9, #389DF9);
  stop-opacity: 0;
}

.rmf1gzb-v {
  stop-color: var(--svg-color--599cdc, #599CDC);
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rq_vxdcfr {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m25.947 22.035l-1.294.557l.035 1.711c.33.288 1.104 1.065 1.808 1.602c.46.35.894.355 1.192.295c.226-.045.287-.301.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.117");
}

.rrye52blb {
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.804.8 1.416l-.809 2.916a4.15 4.15 0 0 1-3.214 2.965l-4.232.815a1.15 1.15 0 0 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.322l.809-2.916a1.15 1.15 0 0 1 1.416-.8");
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.s_sh9varo {
  stop-color: var(--svg-color--5daef5, #5DAEF5);
  stop-opacity: 0;
}

.s-7nhybnh {
  stop-color: var(--svg-color--a5a3a3, #A5A3A3);
}

.s0d_o1h9v {
  stop-color: var(--svg-color--e2ac95, #E2AC95);
}

.sew1y7bbn {
  stop-color: var(--svg-color--514d8b, #514D8B);
  stop-opacity: 0;
}

.sj-lltwha {
  fill: var(--svg-color--d9a68f, #D9A68F);
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.804.8 1.416l-.809 2.916a4.15 4.15 0 0 1-3.214 2.965l-4.232.815a1.15 1.15 0 0 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.322l.809-2.916a1.15 1.15 0 0 1 1.416-.8");
}

.sld9yacoe {
  d: path("m15.493 9.4l.674-.168a1.75 1.75 0 0 1 .713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.so5pusb0b {
  stop-color: var(--svg-color--be7782, #BE7782);
  stop-opacity: 0;
}

.spf2xjb6v {
  stop-color: var(--svg-color--2e7ef2, #2E7EF2);
  stop-opacity: 0;
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.swgsx6bpm {
  stop-color: var(--svg-color--c17560, #C17560);
}

.t3ncs1j8m {
  d: path("M4.494 12.58a.44.44 0 0 1 .44-.44h1.537v.48a.4.4 0 0 1-.4.4H4.934a.44.44 0 0 1-.44-.44");
}

.t54cbcb-z {
  stop-color: var(--svg-color--bab6bd, #BAB6BD);
}

.tbe0sc-ij {
  stop-color: var(--svg-color--4a4970, #4A4970);
}

.tio1oi0im {
  d: path("m13.095 6.416l.005-.076c0-.196-.084-.355-.186-.355c-.103 0-.186.159-.186.355q0 .039.004.076z");
}

.u_pd93bvm {
  stop-color: var(--svg-color--3080f1, #3080F1);
  stop-opacity: 0;
}

.u1j_tu46h {
  stop-color: var(--svg-color--d5a887, #D5A887);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vtxj36boz {
  d: path("M4.052 11.997a.44.44 0 0 1 .44-.44H6.47v.88H4.49a.44.44 0 0 1-.44-.44");
}

.vuvc8_ujh {
  stop-color: var(--svg-color--444367, #444367);
  stop-opacity: 0;
}

.vx88q5bse {
  stop-color: var(--svg-color--484083, #484083);
  stop-opacity: 0;
}

.w-g7jabxf {
  stop-color: var(--svg-color--428dca, #428DCA);
}

.wcx06_c5w {
  stop-color: var(--svg-color--ca8571, #CA8571);
  stop-opacity: 0;
}

.wdglv_bwm {
  stop-color: var(--svg-color--f2b08a, #F2B08A);
}

.wdluo8w4e {
  width: 1.465px;
  height: 0.199px;
  x: 4.864px;
  y: 12.272px;
  fill: var(--svg-color--e1a78f, #E1A78F);
  rx: 0.099px;
}

.x3uyqiwdn {
  stop-color: var(--svg-color--d38f87, #D38F87);
}

.x9uaycblj {
  stop-color: var(--svg-color--de9d8a, #DE9D8A);
}

.xezvpxvhe {
  stop-color: var(--svg-color--4fb3ff, #4FB3FF);
  stop-opacity: 0;
}

.y05m73b2m {
  d: path("M12.802 4.781c-.694 0-1.024-.392-1.057-.883c0-.693.53-.84.735-.862c.231-.025.322-.05.644-.277a.95.95 0 0 1 .961-.103c.157.074.504.111.751.037c.413-.124.735-.12 1.053.124c.22.17.383.17.648.17c.363 0 .671.162.904.338c.694.525.614 2.331.272 3.347c-.328.97-.821 1.085-1.234 1.048c-.497-.045-.623-.421-.697-.735c-.06-.25-.212-1.046-.281-1.307c-.143-.066-.456-.091-.561-.5s-.52-.457-.801-.43c-.17.017-.644.033-1.337.033");
}

.y6bw3v3vv {
  stop-color: var(--svg-color--59a5ed, #59A5ED);
}

.yb5t-ebeb {
  stop-color: var(--svg-color--2ca8f8, #2CA8F8);
}

.ycb1huo4n {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
}

.yfv3nqb2s {
  stop-color: var(--svg-color--e4a88b, #E4A88B);
  stop-opacity: 0;
}

.yh_1i3b0p {
  fill: var(--svg-color--d0937d, #D0937D);
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 0 1 .993 2.075c-3.032 1.451-6.188.804-8.137-.702c-.512-.376-.471-.93-.095-1.442");
}

.yuovwfb9j {
  cx: 12.846px;
  cy: 6.044px;
  rx: 0.068px;
  ry: 0.093px;
}

.zbyobmbvc {
  stop-color: var(--svg-color--599cdc, #599CDC);
  stop-opacity: 0;
}

.zg01gt89b {
  stop-color: var(--svg-color--2a6ae2, #2A6AE2);
  stop-opacity: 0;
}

.zgff__bcr {
  stop-color: var(--svg-color--34a0e5, #34A0E5);
}

.zguchrbop {
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

.zmktv7koj {
  stop-color: var(--svg-color--4589bd, #4589BD);
}

</style>
