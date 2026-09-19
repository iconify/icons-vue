<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iIZoyQb)" class="q12x_3brx"/><path fill="url(#iQQzDfd)" class="q12x_3brx"/><path fill="url(#i9ztGhb)" class="q12x_3brx"/><path class="lv6qs4dqh"/><path fill="url(#i0eVsLe)" class="zguchrbop"/><path fill="url(#ismZuab)" class="zguchrbop"/><path class="p8hed8p1i"/><path fill="url(#i8VQyhb)" class="g9d0ovbvp"/><path fill="url(#iTNgb2y)" class="g9d0ovbvp"/><path fill="url(#i6FwaDc)" class="g9d0ovbvp"/><path fill="url(#iAJMqce)" class="g9d0ovbvp"/><path fill="url(#izzU55b)" class="qum9srb-r"/><path fill="url(#ixh406b)" class="qum9srb-r"/><path fill="url(#iCfwbfb)" class="qum9srb-r"/><path fill="url(#i31pOtc)" class="qum9srb-r"/><g filter="url(#iOx70vy)"><path class="amd51vbjg"/><path fill="url(#i6AMUmc)" class="mfs1vbcha"/></g><path clip-rule="evenodd" class="yah45qy7o"/><path fill="url(#iBkz7Fe)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#iD20xTc)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#itKLaUk)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#iuXm4Ob)" transform="rotate(-23.31 13.976 8.014)" class="d_6rbhb8w"/><g filter="url(#ibEx4PC)"><path class="seanbl9if"/><path fill="url(#ibJRlYd)" class="f1u8ijb3m"/><path fill="url(#iyIhfTP)" class="f1u8ijb3m"/><path fill="url(#iOHXHyc)" class="f1u8ijb3m"/><path fill="url(#iNwsQWc)" class="f1u8ijb3m"/><path fill="url(#irXgbHb)" class="f1u8ijb3m"/></g><path fill="url(#ipSnGqe)" class="vjh3yqznr"/><path fill="url(#iAciTGb)" class="vjh3yqznr"/><path fill="url(#iiDMUtc)" class="vjh3yqznr"/><path fill="url(#iq6Q1Wl)" class="vjh3yqznr"/><path class="ppv4posfy"/><path fill="url(#iYUt5rb)" class="ol51zcmaj"/><path fill="url(#i21JStR)" class="ol51zcmaj"/><path fill="url(#ikduqNe)" class="ol51zcmaj"/><path class="kmd3qcb-j"/><path fill="url(#iiwTGEe)" class="e0lhu47_k"/><path fill="url(#izYIVRu)" class="e0lhu47_k"/><path fill="url(#iRYIdJc)" class="e0lhu47_k"/><path fill="url(#ir7LSIc)" class="e0lhu47_k"/><path fill="url(#idaGKtb)" class="e0lhu47_k"/><g filter="url(#imuZgQc)"><path clip-rule="evenodd" class="avosl4bpd"/></g><path fill="url(#i84S0qc)" clip-rule="evenodd" class="yzbfo0edn"/><path fill="url(#ivI1A0b)" clip-rule="evenodd" class="yzbfo0edn"/><path class="sc0n1hfuo"/><path fill="url(#iNc8Fic)" class="jmlii5bid"/><path fill="url(#iHCzuPb)" class="jmlii5bid"/><path fill="url(#iKcjUje)" class="jmlii5bid"/><rect fill="url(#iokKzGc)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><rect fill="url(#iFg3qDc)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><path fill="url(#iZKciLc)" class="mqryp-bup"/><path fill="url(#idBd4Ud)" class="vtxj36boz"/><path fill="url(#ikZhW9L)" class="vtxj36boz"/><path fill="url(#iCDjVke)" class="t3ncs1j8m"/><path fill="url(#igfEL3l)" class="t3ncs1j8m"/><g filter="url(#iw1Nype)"><path fill="url(#ibBvqNd)" class="pcwcq6ykk"/></g><path fill="url(#inqL0Pd)" class="pb93aprhh"/><path fill="url(#ipDfQxd)" class="pb93aprhh"/><path fill="url(#iFMDzle)" class="pb93aprhh"/><path fill="url(#iVgiUxb)" class="pb93aprhh"/><path fill="url(#iESVPYb)" class="pb93aprhh"/><g filter="url(#iFcZNPe)"><rect class="kk63hqbts"/></g><path fill="url(#iUsf7Xc)" class="beizedb0m"/><path fill="url(#iSl4f9c)" class="beizedb0m"/><g filter="url(#iEujj1b)"><path fill="url(#iAFtV5c)" class="lsbzy9b1t"/><path fill="url(#iieF9we)" class="lsbzy9b1t"/><path fill="url(#it6HIKq)" class="lsbzy9b1t"/><path fill="url(#i031j7d)" class="lsbzy9b1t"/></g><g filter="url(#iv4tx9T)"><path fill="url(#iswnxSd)" class="h4ty29b1n"/><path fill="url(#i3D6wyc)" class="h4ty29b1n"/><path fill="url(#iq6WTjd)" class="h4ty29b1n"/></g><path fill="url(#iIuYsJL)" class="hv3zbqb8e"/><path fill="url(#iIrJx9b)" class="hv3zbqb8e"/><path fill="url(#is2VMMb)" class="hv3zbqb8e"/><path clip-rule="evenodd" class="e4ujb6_vs"/><path class="ax_uj2bfc"/><path fill="url(#ibHnN8b)" class="z1qci3b_y"/><path fill="url(#iEL7mxe)" class="ie5f7acdc"/><ellipse fill="url(#irA4FOe)" transform="rotate(24.61 12.848 6.044)" class="zqid8cblv"/><g filter="url(#igyXise)"><path clip-rule="evenodd" class="il83mg0ji"/></g><defs><radialGradient id="i8VQyhb" cx="0" cy="0" r="1" gradientTransform="matrix(.61864 2.14418 -1.49974 .4327 18.926 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="q359-ccqt"/><stop offset="1" class="xezvpxvhe"/></radialGradient><radialGradient id="iTNgb2y" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 18.88 22.28)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="ez6yh-y9m"/><stop offset="1" class="g0lloqbmi"/></radialGradient><radialGradient id="i6FwaDc" cx="0" cy="0" r="1" gradientTransform="matrix(.80677 2.5012 -1.15566 .37276 16.338 22.544)" gradientUnits="userSpaceOnUse"><stop class="atwm-qoon"/><stop offset="1" class="ovos4t_7k"/></radialGradient><radialGradient id="iAJMqce" cx="0" cy="0" r="1" gradientTransform="rotate(71.565 -6.364 23.576)scale(.54352 3.09962)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="a_wk1gzgh"/><stop offset="1" class="spf2xjb6v"/></radialGradient><radialGradient id="izzU55b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 12.825 19.514)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="g_c95ob_h"/><stop offset="1" class="yb5t-ebeb"/></radialGradient><radialGradient id="ixh406b" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 10.934 8.218)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="aqx-_1b_m"/><stop offset="1" class="gn7z4wb2i"/></radialGradient><radialGradient id="iCfwbfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.114 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="s_sh9varo"/><stop offset=".979" class="b2logdb4l"/></radialGradient><radialGradient id="i6AMUmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 16.614 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iBkz7Fe" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.529 4.43)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="pjqvhnbjs"/><stop offset="1" class="wcx06_c5w"/><stop offset="1" class="ffhvjce4r"/></radialGradient><radialGradient id="iD20xTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 10.926 11.811)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="zvwwfcbef"/><stop offset=".952" class="hiik07xes"/></radialGradient><radialGradient id="itKLaUk" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 10.63 11.764)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="wvbuym-2v"/><stop offset="1" class="w8z0zbc1w"/></radialGradient><radialGradient id="iuXm4Ob" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 14.966 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="c7ppc0bow"/><stop offset=".811" class="yia_fgb_n"/></radialGradient><radialGradient id="ibJRlYd" cx="0" cy="0" r="1" gradientTransform="matrix(.0293 -5.32953 3.38376 .0186 14.815 17.47)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="dyygb2yxz"/><stop offset="1" class="jyyx2-bie"/></radialGradient><radialGradient id="iyIhfTP" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50773 .13384 -.33514 -6.2795 18.298 14.615)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="boe213jez"/><stop offset="1" class="n8m7rnb1b"/></radialGradient><radialGradient id="iOHXHyc" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.527 10.23)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="gkcpx30-s"/><stop offset="1" class="fxro0tyoi"/></radialGradient><radialGradient id="iNwsQWc" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 16.91 11.233)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="ekxdyp1yu"/><stop offset="1" class="zg01gt89b"/></radialGradient><radialGradient id="irXgbHb" cx="0" cy="0" r="1" gradientTransform="rotate(-170.407 9.956 6.194)scale(6.31116 10.4533)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="zbyobmbvc"/><stop offset=".957" class="rmf1gzb-v"/></radialGradient><radialGradient id="iAciTGb" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 6.675 29.938)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iq6Q1Wl" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.423 12.192)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iiwTGEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.124 17.331)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="izYIVRu" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.435 22.802)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iRYIdJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.173 18.126)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="idaGKtb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 13.704 17.342)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="ivI1A0b" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.77 7.069)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="aneywjt_w"/><stop offset="1" class="idx-0ob_q"/></radialGradient><radialGradient id="iHCzuPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.33186 -.12063 .2037 2.249 14.601 10.846)" gradientUnits="userSpaceOnUse"><stop class="y6bw3v3vv"/><stop offset="1" class="igyzmj7fv"/></radialGradient><radialGradient id="iKcjUje" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 19.656 9.918)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="mmjlr5d2n"/><stop offset="1" class="rh-0l3b-i"/></radialGradient><radialGradient id="ibBvqNd" cx="0" cy="0" r="1" gradientTransform="rotate(-149.027 6.18 5.213)scale(1.15719 1.60341)" gradientUnits="userSpaceOnUse"><stop class="zmktv7koj"/><stop offset="1" class="mnxdxy3jn"/></radialGradient><radialGradient id="inqL0Pd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 11.86 .42)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ipDfQxd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.727 -9.355)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="iFMDzle" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 20.567 4.249)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iVgiUxb" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.05 4.184)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iESVPYb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.727 -3.655)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><radialGradient id="iUsf7Xc" cx="0" cy="0" r="1" gradientTransform="matrix(.50349 .27238 -.38447 .7107 11.585 7.057)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="hymklqb8k"/><stop offset=".684" class="s2f2c_bct"/></radialGradient><radialGradient id="iSl4f9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.12684 -.308 .46222 -.19035 12.013 7.393)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="iieF9we" cx="0" cy="0" r="1" gradientTransform="matrix(-.89142 -.0496 .06048 -1.08682 15.454 6.316)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="it6HIKq" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.48059 2.12951 0 12.394 7.57)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="i031j7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4127 -.6436 0 13.27 6.364)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="iswnxSd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6317 3.30158 -3.74378 -4.11812 17.435 3.502)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="sd2k4tbbl"/><stop offset="1" class="n3xu87-4f"/></radialGradient><radialGradient id="i3D6wyc" cx="0" cy="0" r="1" gradientTransform="matrix(.4168 2.8343 -1.2521 .18413 17.322 4.294)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="qvi3m-3ib"/><stop offset="1" class="sx_wpgngv"/></radialGradient><radialGradient id="iq6WTjd" cx="0" cy="0" r="1" gradientTransform="matrix(1.58475 -.09905 .19437 3.1099 11.839 4.152)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ehlb6fbrs"/><stop offset="1" class="xv-sacbws"/></radialGradient><radialGradient id="iIuYsJL" cx="0" cy="0" r="1" gradientTransform="matrix(.76761 -.22286 .10877 .37466 15.217 6.19)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="iIrJx9b" cx="0" cy="0" r="1" gradientTransform="rotate(79.157 4.073 12.16)scale(1.26906 1.32241)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="ibHnN8b" cx="0" cy="0" r="1" gradientTransform="matrix(.28889 0 0 .56127 12.958 6.393)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iEL7mxe" cx="0" cy="0" r="1" gradientTransform="matrix(.26412 0 0 .57158 12.78 6.416)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iIZoyQb" x1="11.364" x2="9.677" y1="26.108" y2="26.358" gradientUnits="userSpaceOnUse"><stop class="pw3cm8ghn"/><stop offset="1" class="ebr2vqbrv"/></linearGradient><linearGradient id="iQQzDfd" x1="8.93" x2="9.665" y1="24.418" y2="24.277" gradientUnits="userSpaceOnUse"><stop offset=".237" class="hc9rgac9d"/><stop offset="1" class="ax0qocbyt"/></linearGradient><linearGradient id="i9ztGhb" x1="11.286" x2="10.856" y1="22.709" y2="22.811" gradientUnits="userSpaceOnUse"><stop class="m8_menbco"/><stop offset="1" class="t1w1jyb_t"/></linearGradient><linearGradient id="i0eVsLe" x1="22.817" x2="22.759" y1="24.6" y2="23.377" gradientUnits="userSpaceOnUse"><stop class="altl0jb1l"/><stop offset="1" class="frv3_c41o"/></linearGradient><linearGradient id="ismZuab" x1="22.196" x2="22.196" y1="22.452" y2="23.361" gradientUnits="userSpaceOnUse"><stop class="ucfba_b5g"/><stop offset="1" class="u745z8b-f"/></linearGradient><linearGradient id="i31pOtc" x1="10.659" x2="10.659" y1="18.631" y2="19.952" gradientUnits="userSpaceOnUse"><stop class="n0ztdwmxa"/><stop offset="1" class="ql2kv4b4e"/></linearGradient><linearGradient id="ipSnGqe" x1="9.864" x2="11.395" y1="28.921" y2="28.921" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iiDMUtc" x1="9.427" x2="9.427" y1="29.938" y2="29.616" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="iYUt5rb" x1="25.352" x2="25.949" y1="22.069" y2="23.186" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i21JStR" x1="25.602" x2="26.296" y1="25.019" y2="24.152" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="ikduqNe" x1="27.316" x2="26.923" y1="24.153" y2="24.327" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ir7LSIc" x1="13.336" x2="13.786" y1="17.398" y2="18.466" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="i84S0qc" x1="21.364" x2="21.177" y1="11.03" y2="10.092" gradientUnits="userSpaceOnUse"><stop offset=".076" class="moe8lybvx"/><stop offset="1" class="gm-u32b5v"/></linearGradient><linearGradient id="iNc8Fic" x1="18.207" x2="17.448" y1="12.178" y2="9.468" gradientUnits="userSpaceOnUse"><stop class="a_xmkojdq"/><stop offset="1" class="u_pd93bvm"/></linearGradient><linearGradient id="iokKzGc" x1="25.013" x2="23.016" y1="6.218" y2="6.288" gradientUnits="userSpaceOnUse"><stop offset=".149" class="zgff__bcr"/><stop offset="1" class="w-g7jabxf"/></linearGradient><linearGradient id="iFg3qDc" x1="24.329" x2="24.328" y1="6.762" y2="6.575" gradientUnits="userSpaceOnUse"><stop class="ah5butb7g"/><stop offset="1" class="m-22afbga"/></linearGradient><linearGradient id="iZKciLc" x1="4.243" x2="7.829" y1="11.428" y2="11.436" gradientUnits="userSpaceOnUse"><stop class="d_zsx_qwu"/><stop offset=".588" class="bq8is6bem"/></linearGradient><linearGradient id="idBd4Ud" x1="4.236" x2="6.799" y1="11.876" y2="11.876" gradientUnits="userSpaceOnUse"><stop class="d_zsx_qwu"/><stop offset=".588" class="bq8is6bem"/></linearGradient><linearGradient id="ikZhW9L" x1="5.154" x2="5.154" y1="12.509" y2="12.064" gradientUnits="userSpaceOnUse"><stop class="uy_o1rblt"/><stop offset="1" class="sj9ku07pk"/></linearGradient><linearGradient id="iCDjVke" x1="4.645" x2="6.739" y1="12.46" y2="12.46" gradientUnits="userSpaceOnUse"><stop class="d_zsx_qwu"/><stop offset=".547" class="bq8is6bem"/></linearGradient><linearGradient id="igfEL3l" x1="5.395" x2="5.395" y1="13.092" y2="12.647" gradientUnits="userSpaceOnUse"><stop class="uy_o1rblt"/><stop offset="1" class="sj9ku07pk"/></linearGradient><linearGradient id="iAFtV5c" x1="15.124" x2="12.1" y1="7.099" y2="7.28" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="is2VMMb" x1="15.159" x2="15.316" y1="6.263" y2="6.276" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="irA4FOe" x1="12.773" x2="12.97" y1="6.004" y2="6.068" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="iOx70vy" width="4.141" height="6.811" x="15.901" y="15.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23787"/></filter><filter id="ibEx4PC" width="5.768" height="8.746" x="12.843" y="8.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.443137 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23787"/></filter><filter id="imuZgQc" width="9.915" height="8.775" x="15.493" y="2.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.533333 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23787"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.635294 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23787" result="effect2_innerShadow_3987_23787"/></filter><filter id="iw1Nype" width="2.43" height="2.868" x="6.814" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.529412 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23787"/></filter><filter id="iFcZNPe" width="2.065" height=".799" x="4.564" y="11.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23787" stdDeviation=".15"/></filter><filter id="iEujj1b" width="4.683" height="5.534" x="11.9" y="4.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.596078 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23787"/></filter><filter id="iv4tx9T" width="6.724" height="5.754" x="11.448" y="2.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.262745 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23787"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.054902 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23787" result="effect2_innerShadow_3987_23787"/></filter><filter id="igyXise" width="1.175" height=".679" x="12.637" y="4.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23787"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-playing-handball-light" /></template>
<style>
.a_wk1gzgh {
  stop-color: var(--svg-color--2e7ef2, #2E7EF2);
}

.a_xmkojdq {
  stop-color: var(--svg-color--1a65dc, #1A65DC);
}

.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.ah5butb7g {
  stop-color: var(--svg-color--5c7ec9, #5C7EC9);
}

.altl0jb1l {
  stop-color: var(--svg-color--c38697, #C38697);
}

.amd51vbjg {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M16.55 22.745s-.464-1.232-.64-2.275c-.176-1.044 2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.982-3.133 1.16");
}

.aneywjt_w {
  stop-color: var(--svg-color--f2c9b3, #F2C9B3);
}

.aqx-_1b_m {
  stop-color: var(--svg-color--4b67e4, #4B67E4);
}

.atwm-qoon {
  stop-color: var(--svg-color--529af1, #529AF1);
}

.avosl4bpd {
  fill: var(--svg-color--e6b6a7, #E6B6A7);
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.323l.809-2.915a1.15 1.15 0 0 1 1.416-.801");
}

.ax_uj2bfc {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.665 6.416h1.044c0-.414-.234-.749-.522-.749s-.522.335-.522.749");
}

.ax0qocbyt {
  stop-color: var(--svg-color--fbc0ae, #FBC0AE);
  stop-opacity: 0;
}

.b2logdb4l {
  stop-color: var(--svg-color--5daef5, #5DAEF5);
}

.b3jcjo1jv {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
  stop-opacity: 0;
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

.beizedb0m {
  d: path("M11.893 6.595c.165-.155.25-.386.272-.483h.19v1.189c-.227.144-.552.122-.648-.095c-.083-.186-.02-.417.186-.61");
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.boe213jez {
  stop-color: var(--svg-color--4990db, #4990DB);
}

.bq8is6bem {
  stop-color: var(--svg-color--e2a493, #E2A493);
}

.c2ukjabcr {
  stop-color: var(--svg-color--4d318d, #4D318D);
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.c7ppc0bow {
  stop-color: var(--svg-color--ce8868, #CE8868);
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.d_6rbhb8w {
  d: path("M13.976 8.014h2.217v3.3h-2.217z");
}

.d_zsx_qwu {
  stop-color: var(--svg-color--ffc5af, #FFC5AF);
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxjajos_o {
  stop-color: var(--svg-color--f0b5a2, #F0B5A2);
}

.dyygb2yxz {
  stop-color: var(--svg-color--3369cc, #3369CC);
}

.e0lhu47_k {
  d: path("M18.3 15.613s-4.632 1.787-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.198.278c1.085-.572 2.045-1.031 3.183-1.726c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.492-1.322-.684-1.704");
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.e4ujb6_vs {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.452 7.592a.13.13 0 0 1-.001.187c-.252.247-.616.31-.732.322a.132.132 0 1 1-.026-.263c.098-.01.387-.065.573-.247a.13.13 0 0 1 .186.001");
}

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.ebr2vqbrv {
  stop-color: var(--svg-color--f8bead, #F8BEAD);
}

.ehlb6fbrs {
  stop-color: var(--svg-color--544b49, #544B49);
}

.ekxdyp1yu {
  stop-color: var(--svg-color--2a6ae2, #2A6AE2);
}

.ez6yh-y9m {
  stop-color: var(--svg-color--3083ff, #3083FF);
  stop-opacity: 0;
}

.f1u8ijb3m {
  d: path("m15.493 9.4l.674-.168c.233-.059.476-.07.713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.ffhvjce4r {
  stop-color: var(--svg-color--d78c77, #D78C77);
  stop-opacity: 0;
}

.frv3_c41o {
  stop-color: var(--svg-color--e0a8a5, #E0A8A5);
  stop-opacity: 0;
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

.g9d0ovbvp {
  d: path("m16.942 23.975l-.398-1.297l2.906-1.383l.203 1.125h.258c.162.9.172 2.141.156 2.649c-.041.013-.301.056-.914.125c-1.412.225-2.062-.719-2.21-1.219");
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gkcpx30-s {
  stop-color: var(--svg-color--4784cd, #4784CD);
}

.gm-u32b5v {
  stop-color: var(--svg-color--d79f9b, #D79F9B);
  stop-opacity: 0;
}

.gn7z4wb2i {
  stop-color: var(--svg-color--3382fa, #3382FA);
  stop-opacity: 0;
}

.gu4uskbqq {
  stop-color: var(--svg-color--fac1a8, #FAC1A8);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h4ty29b1n {
  d: path("M12.805 4.781c-.694 0-1.024-.392-1.057-.883c0-.693.53-.84.735-.862c.23-.025.322-.05.643-.277a.95.95 0 0 1 .962-.103c.157.074.504.111.751.037c.413-.124.735-.12 1.053.124c.22.17.383.17.647.17c.364 0 .672.162.904.338c.695.525.615 2.331.273 3.347c-.328.97-.822 1.085-1.234 1.048c-.497-.045-.623-.421-.698-.735c-.06-.25-.212-1.046-.28-1.307c-.143-.066-.456-.091-.562-.5c-.105-.41-.52-.457-.8-.43c-.17.017-.644.033-1.337.033");
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.hc9rgac9d {
  stop-color: var(--svg-color--ffd2bc, #FFD2BC);
}

.hiik07xes {
  stop-color: var(--svg-color--c9878b, #C9878B);
}

.hq1ekobkc {
  stop-color: var(--svg-color--e7a792, #E7A792);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.hv3zbqb8e {
  d: path("m15.057 7.114l.21-1.521a.768.768 0 0 1-.21 1.52");
}

.hymklqb8k {
  stop-color: var(--svg-color--ffd4b7, #FFD4B7);
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.idx-0ob_q {
  stop-color: var(--svg-color--e4b3a0, #E4B3A0);
  stop-opacity: 0;
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.ie5f7acdc {
  d: path("m13.098 6.416l.004-.077c0-.196-.083-.355-.186-.355c-.102 0-.185.16-.185.355q0 .04.004.077z");
}

.igyzmj7fv {
  stop-color: var(--svg-color--59a5ed, #59A5ED);
  stop-opacity: 0;
}

.il83mg0ji {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M13.478 5.51c-.156-.111-.384-.117-.53-.117a.211.211 0 1 1 0-.422h.01c.136 0 .491 0 .766.196a.211.211 0 0 1-.247.344");
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

.jmlii5bid {
  d: path("m19.732 11.598l-.61-2.962l-3.005.597a1.483 1.483 0 0 0 .55 2.914z");
}

.jyyx2-bie {
  stop-color: var(--svg-color--3369cc, #3369CC);
  stop-opacity: 0;
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.kk63hqbts {
  width: 1.465px;
  height: 0.199px;
  x: 4.864px;
  y: 12.272px;
  fill: var(--svg-color--f3baa7, #F3BAA7);
  rx: 0.099px;
}

.kmd3qcb-j {
  fill: var(--svg-color--918996, #918996);
  d: path("M18.3 15.613s-4.632 1.787-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.198.278c1.085-.572 2.045-1.031 3.183-1.726c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.492-1.322-.684-1.704");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l7mbhnbzh {
  stop-color: var(--svg-color--eeb298, #EEB298);
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lsbzy9b1t {
  d: path("M12.13 5.577c.04-.847.314-1.255.444-1.374h3.943l.066 3.342c-.916 2.242-3.71 2.338-4.127 1.527c-.418-.81-.373-2.515-.326-3.495");
}

.lv6qs4dqh {
  fill: var(--svg-color--f1bcb0, #F1BCB0);
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.m-22afbga {
  stop-color: var(--svg-color--5c7ec9, #5C7EC9);
  stop-opacity: 0;
}

.m5_tnryam {
  stop-color: var(--svg-color--66638b, #66638B);
  stop-opacity: 0;
}

.m8_menbco {
  stop-color: var(--svg-color--d99f98, #D99F98);
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

.moe8lybvx {
  stop-color: var(--svg-color--c0858e, #C0858E);
}

.mqryp-bup {
  d: path("M4.624 11.557a.44.44 0 0 1 .44-.44h1.373c.113 0 .54.008.9.147l.109.34l-.403.393h-1.98a.44.44 0 0 1-.44-.44");
}

.n0ztdwmxa {
  stop-color: var(--svg-color--4493c4, #4493C4);
}

.n3xu87-4f {
  stop-color: var(--svg-color--1d0d23, #1D0D23);
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

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
}

.ol51zcmaj {
  d: path("m25.947 22.035l-1.294.558l.035 1.71c.33.289 1.104 1.066 1.808 1.602c.46.35.894.355 1.192.295c.226-.045.287-.3.188-.509l-1.594-3.539a.25.25 0 0 0-.335-.117");
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.ovos4t_7k {
  stop-color: var(--svg-color--388dfb, #388DFB);
  stop-opacity: 0;
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

.pjqvhnbjs {
  stop-color: var(--svg-color--d78c77, #D78C77);
}

.ppv4posfy {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m25.947 22.035l-1.294.558l.035 1.71c.33.289 1.104 1.066 1.808 1.602c.46.35.894.355 1.192.295c.226-.045.287-.3.188-.509l-1.594-3.539a.25.25 0 0 0-.335-.117");
}

.pw3cm8ghn {
  stop-color: var(--svg-color--efbaab, #EFBAAB);
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

.qh9tdvimg {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
}

.ql2kv4b4e {
  stop-color: var(--svg-color--2ba8f5, #2BA8F5);
  stop-opacity: 0;
}

.qmcjcvbdo {
  stop-color: var(--svg-color--adaaad, #ADAAAD);
  stop-opacity: 0;
}

.qum9srb-r {
  d: path("m10.2 19.077l1.016-.446l1.61 2.836l-1.563.469v.422l-2.68.258c-.073-.399-.2-1.251.102-2.016c.335-.848 1.148-1.362 1.515-1.523");
}

.qvi3m-3ib {
  stop-color: var(--svg-color--464143, #464143);
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

.s2f2c_bct {
  stop-color: var(--svg-color--ffc4a7, #FFC4A7);
}

.sc0n1hfuo {
  fill: var(--svg-color--279fea, #279FEA);
  d: path("m19.732 11.598l-.61-2.962l-3.005.597a1.483 1.483 0 0 0 .55 2.914z");
}

.sd2k4tbbl {
  stop-color: var(--svg-color--251a23, #251A23);
}

.seanbl9if {
  fill: var(--svg-color--3584e5, #3584E5);
  d: path("m15.493 9.4l.674-.168c.233-.059.476-.07.713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.sew1y7bbn {
  stop-color: var(--svg-color--514d8b, #514D8B);
  stop-opacity: 0;
}

.sj9ku07pk {
  stop-color: var(--svg-color--e7a79b, #E7A79B);
  stop-opacity: 0;
}

.sp0u-8bbb {
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.804-8.137-.703c-.512-.375-.471-.93-.095-1.441");
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

.sx_wpgngv {
  stop-color: var(--svg-color--464143, #464143);
  stop-opacity: 0;
}

.t1w1jyb_t {
  stop-color: var(--svg-color--ebb3a8, #EBB3A8);
  stop-opacity: 0;
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

.u_pd93bvm {
  stop-color: var(--svg-color--3080f1, #3080F1);
  stop-opacity: 0;
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.u745z8b-f {
  stop-color: var(--svg-color--e7b8a0, #E7B8A0);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ucfba_b5g {
  stop-color: var(--svg-color--e7b8a0, #E7B8A0);
}

.uy_o1rblt {
  stop-color: var(--svg-color--e7a79b, #E7A79B);
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vjh3yqznr {
  d: path("m7.403 28.647l2.214-1.071l1.575.751l-.014 1.34a.253.253 0 0 1-.252.249l-3.854.022c-.221.002-.418-.15-.395-.369c.046-.453.333-.737.726-.922");
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

.w8z0zbc1w {
  stop-color: var(--svg-color--dca489, #DCA489);
  stop-opacity: 0;
}

.wcectbccf {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
}

.wcx06_c5w {
  stop-color: var(--svg-color--ca8571, #CA8571);
  stop-opacity: 0;
}

.wvbuym-2v {
  stop-color: var(--svg-color--dca489, #DCA489);
}

.xezvpxvhe {
  stop-color: var(--svg-color--4fb3ff, #4FB3FF);
  stop-opacity: 0;
}

.xv-sacbws {
  stop-color: var(--svg-color--544b49, #544B49);
  stop-opacity: 0;
}

.y6bw3v3vv {
  stop-color: var(--svg-color--59a5ed, #59A5ED);
}

.yah45qy7o {
  fill: var(--svg-color--e2a493, #E2A493);
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.804-8.137-.703c-.512-.375-.471-.93-.095-1.441");
}

.yb5t-ebeb {
  stop-color: var(--svg-color--2ca8f8, #2CA8F8);
}

.ycb1huo4n {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
}

.yia_fgb_n {
  stop-color: var(--svg-color--daaa94, #DAAA94);
}

.yzbfo0edn {
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.323l.809-2.915a1.15 1.15 0 0 1 1.416-.801");
}

.z1qci3b_y {
  d: path("M13.304 6.416v-.004c0-.339-.145-.613-.324-.613c-.178 0-.324.274-.324.613v.004z");
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

.zqid8cblv {
  cx: 12.848px;
  cy: 6.044px;
  rx: 0.068px;
  ry: 0.093px;
}

.zvwwfcbef {
  stop-color: var(--svg-color--db988d, #DB988D);
  stop-opacity: 0;
}

</style>
