<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ioGa9Oe)" class="q12x_3brx"/><path fill="url(#iuk7NUc)" class="q12x_3brx"/><path fill="url(#iEE49db)" class="q12x_3brx"/><path class="ndsrk3fql"/><path fill="url(#iKGodqe)" class="zguchrbop"/><path fill="url(#iM0fJwe)" class="zguchrbop"/><path class="p8hed8p1i"/><path fill="url(#i8VQyhb)" class="g9d0ovbvp"/><path fill="url(#iTNgb2y)" class="g9d0ovbvp"/><path fill="url(#i6FwaDc)" class="g9d0ovbvp"/><path fill="url(#iAJMqce)" class="g9d0ovbvp"/><path fill="url(#izzU55b)" class="qum9srb-r"/><path fill="url(#ixh406b)" class="qum9srb-r"/><path fill="url(#iCfwbfb)" class="qum9srb-r"/><path fill="url(#i31pOtc)" class="qum9srb-r"/><g filter="url(#ifWZjCD)"><path class="amd51vbjg"/><path fill="url(#i6AMUmc)" class="mfs1vbcha"/></g><path clip-rule="evenodd" class="gxkjg_bzv"/><path fill="url(#iCgP0me)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#iD0fZCb)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#iJsS8td)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#igftqFe)" transform="rotate(-23.31 13.976 8.014)" class="d_6rbhb8w"/><g filter="url(#iQYCNPb)"><path class="seanbl9if"/><path fill="url(#ibJRlYd)" class="f1u8ijb3m"/><path fill="url(#iyIhfTP)" class="f1u8ijb3m"/><path fill="url(#iOHXHyc)" class="f1u8ijb3m"/><path fill="url(#iNwsQWc)" class="f1u8ijb3m"/><path fill="url(#irXgbHb)" class="f1u8ijb3m"/></g><path fill="url(#ipSnGqe)" class="vjh3yqznr"/><path fill="url(#iAciTGb)" class="vjh3yqznr"/><path fill="url(#iiDMUtc)" class="vjh3yqznr"/><path fill="url(#iq6Q1Wl)" class="vjh3yqznr"/><path class="ppv4posfy"/><path fill="url(#iYUt5rb)" class="ol51zcmaj"/><path fill="url(#i21JStR)" class="ol51zcmaj"/><path fill="url(#ikduqNe)" class="ol51zcmaj"/><path class="kmd3qcb-j"/><path fill="url(#iiwTGEe)" class="e0lhu47_k"/><path fill="url(#izYIVRu)" class="e0lhu47_k"/><path fill="url(#iRYIdJc)" class="e0lhu47_k"/><path fill="url(#ir7LSIc)" class="e0lhu47_k"/><path fill="url(#idaGKtb)" class="e0lhu47_k"/><g filter="url(#ieesKWc)"><path clip-rule="evenodd" class="rfat3lb_o"/></g><path fill="url(#iPDnZpf)" clip-rule="evenodd" class="efuw_n2tj"/><path fill="url(#ilBnagI)" clip-rule="evenodd" class="efuw_n2tj"/><path class="sc0n1hfuo"/><path fill="url(#iNc8Fic)" class="jmlii5bid"/><path fill="url(#iHCzuPb)" class="jmlii5bid"/><path fill="url(#iKcjUje)" class="jmlii5bid"/><rect fill="url(#iokKzGc)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><rect fill="url(#iFg3qDc)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><path fill="url(#iAtGHKc)" class="mqryp-bup"/><path fill="url(#ir8P1ee)" class="mqryp-bup"/><path fill="url(#ixw5dVd)" class="vtxj36boz"/><path fill="url(#iqniGgc)" class="vtxj36boz"/><path fill="url(#iXOmxIc)" class="t3ncs1j8m"/><path fill="url(#iIMhh4F)" class="t3ncs1j8m"/><g filter="url(#iybxfEe)"><path fill="url(#ibBvqNd)" class="pcwcq6ykk"/></g><path fill="url(#inqL0Pd)" class="afs2-ebiq"/><path fill="url(#ipDfQxd)" class="afs2-ebiq"/><path fill="url(#iFMDzle)" class="afs2-ebiq"/><path fill="url(#iVgiUxb)" class="afs2-ebiq"/><path fill="url(#iESVPYb)" class="afs2-ebiq"/><g filter="url(#iluCZvg)"><rect class="a18i0zbmv"/></g><g filter="url(#ieD29fy)"><rect class="iepxmux-c"/></g><path fill="url(#iIhwGvc)" class="jo_5u8xym"/><g filter="url(#iHNr7He)"><path fill="url(#ibfNK1g)" class="uxn5a8bke"/><path fill="url(#iODj4hc)" class="uxn5a8bke"/><path fill="url(#iMcS2hk)" class="uxn5a8bke"/><path fill="url(#iFijfwd)" class="uxn5a8bke"/></g><g filter="url(#i9U8zzb)"><path fill="url(#ipr9vZd)" class="uhopwn8ty"/><path fill="url(#iG6mcQc)" class="uhopwn8ty"/><path fill="url(#iiWA9KX)" class="uhopwn8ty"/></g><path fill="url(#idXEcqe)" class="r3c9c6tfm"/><path fill="url(#iTfPPhR)" class="r3c9c6tfm"/><path clip-rule="evenodd" class="ux8hz1b7z"/><path class="r6-e0za-u"/><path fill="url(#iqYuRcc)" class="g3-qtzb2n"/><path fill="url(#iF0ULle)" class="f3k2wzgtv"/><ellipse fill="url(#ijpUdCt)" transform="rotate(24.61 12.855 6.036)" class="tr58n2brv"/><g filter="url(#iUOb4ae)"><path clip-rule="evenodd" class="sis_hvect"/></g><defs><radialGradient id="i8VQyhb" cx="0" cy="0" r="1" gradientTransform="matrix(.61864 2.14418 -1.49974 .4327 18.926 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="q359-ccqt"/><stop offset="1" class="xezvpxvhe"/></radialGradient><radialGradient id="iTNgb2y" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 18.88 22.28)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="ez6yh-y9m"/><stop offset="1" class="g0lloqbmi"/></radialGradient><radialGradient id="i6FwaDc" cx="0" cy="0" r="1" gradientTransform="matrix(.80677 2.5012 -1.15566 .37276 16.338 22.544)" gradientUnits="userSpaceOnUse"><stop class="atwm-qoon"/><stop offset="1" class="ovos4t_7k"/></radialGradient><radialGradient id="iAJMqce" cx="0" cy="0" r="1" gradientTransform="rotate(71.565 -6.364 23.576)scale(.54352 3.09962)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="a_wk1gzgh"/><stop offset="1" class="spf2xjb6v"/></radialGradient><radialGradient id="izzU55b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 12.825 19.514)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="g_c95ob_h"/><stop offset="1" class="yb5t-ebeb"/></radialGradient><radialGradient id="ixh406b" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 10.934 8.218)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="aqx-_1b_m"/><stop offset="1" class="gn7z4wb2i"/></radialGradient><radialGradient id="iCfwbfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.114 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="s_sh9varo"/><stop offset=".979" class="b2logdb4l"/></radialGradient><radialGradient id="i6AMUmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 16.614 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iCgP0me" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.529 4.43)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="v27sfw_5y"/><stop offset="1" class="ob57ysbap"/></radialGradient><radialGradient id="iD0fZCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 10.926 11.811)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="a5v-ibbyp"/><stop offset=".952" class="dhzphmhhv"/></radialGradient><radialGradient id="iJsS8td" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 10.63 11.764)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="gioczw4ny"/><stop offset="1" class="vg-1agb5d"/></radialGradient><radialGradient id="igftqFe" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 14.966 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="lbh256w_i"/><stop offset=".75" class="ao5r4vunm"/></radialGradient><radialGradient id="ibJRlYd" cx="0" cy="0" r="1" gradientTransform="matrix(.0293 -5.32953 3.38376 .0186 14.815 17.47)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="dyygb2yxz"/><stop offset="1" class="jyyx2-bie"/></radialGradient><radialGradient id="iyIhfTP" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50773 .13384 -.33514 -6.2795 18.298 14.615)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="boe213jez"/><stop offset="1" class="n8m7rnb1b"/></radialGradient><radialGradient id="iOHXHyc" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.527 10.23)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="gkcpx30-s"/><stop offset="1" class="fxro0tyoi"/></radialGradient><radialGradient id="iNwsQWc" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 16.91 11.233)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="ekxdyp1yu"/><stop offset="1" class="zg01gt89b"/></radialGradient><radialGradient id="irXgbHb" cx="0" cy="0" r="1" gradientTransform="rotate(-170.407 9.956 6.194)scale(6.31116 10.4533)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="zbyobmbvc"/><stop offset=".957" class="rmf1gzb-v"/></radialGradient><radialGradient id="iAciTGb" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 6.675 29.938)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iq6Q1Wl" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.423 12.192)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iiwTGEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.124 17.331)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="izYIVRu" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.435 22.802)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iRYIdJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.173 18.126)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="idaGKtb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 13.704 17.342)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="ilBnagI" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.77 7.069)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="dbxn0ya4l"/><stop offset="1" class="u8e_1ft3u"/></radialGradient><radialGradient id="iHCzuPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.33186 -.12063 .2037 2.249 14.601 10.846)" gradientUnits="userSpaceOnUse"><stop class="y6bw3v3vv"/><stop offset="1" class="igyzmj7fv"/></radialGradient><radialGradient id="iKcjUje" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 19.656 9.918)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="mmjlr5d2n"/><stop offset="1" class="rh-0l3b-i"/></radialGradient><radialGradient id="ibBvqNd" cx="0" cy="0" r="1" gradientTransform="rotate(-149.027 6.18 5.213)scale(1.15719 1.60341)" gradientUnits="userSpaceOnUse"><stop class="zmktv7koj"/><stop offset="1" class="mnxdxy3jn"/></radialGradient><radialGradient id="inqL0Pd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 11.86 .42)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ipDfQxd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.727 -9.355)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="iFMDzle" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 20.567 4.249)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iVgiUxb" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.05 4.184)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iESVPYb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.727 -3.655)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><radialGradient id="iIhwGvc" cx="0" cy="0" r="1" gradientTransform="matrix(.50349 .27238 -.38447 .7107 11.592 7.05)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="iODj4hc" cx="0" cy="0" r="1" gradientTransform="matrix(-.89142 -.0496 .06048 -1.08682 15.46 6.308)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="iMcS2hk" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.48059 1.4857 0 12.4 7.561)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="iFijfwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4127 -.6436 0 13.276 6.356)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="ipr9vZd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6317 3.30158 -3.74378 -4.11812 17.442 3.494)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="sd2k4tbbl"/><stop offset="1" class="n3xu87-4f"/></radialGradient><radialGradient id="iG6mcQc" cx="0" cy="0" r="1" gradientTransform="matrix(.4168 2.8343 -1.2521 .18413 17.33 4.286)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="qvi3m-3ib"/><stop offset="1" class="sx_wpgngv"/></radialGradient><radialGradient id="iiWA9KX" cx="0" cy="0" r="1" gradientTransform="matrix(1.58475 -.09905 .19437 3.1099 11.846 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ehlb6fbrs"/><stop offset="1" class="xv-sacbws"/></radialGradient><radialGradient id="idXEcqe" cx="0" cy="0" r="1" gradientTransform="matrix(.76761 -.22286 .10877 .37466 15.224 6.183)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="iqYuRcc" cx="0" cy="0" r="1" gradientTransform="matrix(.28889 0 0 .56127 12.964 6.385)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iF0ULle" cx="0" cy="0" r="1" gradientTransform="matrix(.26412 0 0 .57158 12.787 6.408)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="ioGa9Oe" x1="11.364" x2="9.677" y1="26.108" y2="26.358" gradientUnits="userSpaceOnUse"><stop class="zsdj_cc5a"/><stop offset="1" class="cu51yf-7r"/></linearGradient><linearGradient id="iuk7NUc" x1="8.817" x2="9.536" y1="24.42" y2="24.358" gradientUnits="userSpaceOnUse"><stop class="ibzaseb-i"/><stop offset="1" class="xojzxxboq"/></linearGradient><linearGradient id="iEE49db" x1="11.286" x2="10.856" y1="22.709" y2="22.811" gradientUnits="userSpaceOnUse"><stop class="ljsluudhz"/><stop offset="1" class="b7qlthb7k"/></linearGradient><linearGradient id="iKGodqe" x1="22.817" x2="22.759" y1="24.6" y2="23.377" gradientUnits="userSpaceOnUse"><stop class="n-awbpg6m"/><stop offset="1" class="usr-62t-w"/></linearGradient><linearGradient id="iM0fJwe" x1="22.196" x2="22.196" y1="22.452" y2="23.361" gradientUnits="userSpaceOnUse"><stop class="ebb6qj3ko"/><stop offset="1" class="jw3sj5zvz"/></linearGradient><linearGradient id="i31pOtc" x1="10.659" x2="10.659" y1="18.631" y2="19.952" gradientUnits="userSpaceOnUse"><stop class="n0ztdwmxa"/><stop offset="1" class="ql2kv4b4e"/></linearGradient><linearGradient id="ipSnGqe" x1="9.864" x2="11.395" y1="28.921" y2="28.921" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iiDMUtc" x1="9.427" x2="9.427" y1="29.938" y2="29.616" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="iYUt5rb" x1="25.352" x2="25.949" y1="22.069" y2="23.186" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i21JStR" x1="25.602" x2="26.296" y1="25.019" y2="24.152" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="ikduqNe" x1="27.316" x2="26.923" y1="24.153" y2="24.327" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ir7LSIc" x1="13.336" x2="13.786" y1="17.398" y2="18.466" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="iPDnZpf" x1="21.364" x2="21.177" y1="11.03" y2="10.092" gradientUnits="userSpaceOnUse"><stop offset=".076" class="t12v1gxuw"/><stop offset="1" class="r0caqn-8d"/></linearGradient><linearGradient id="iNc8Fic" x1="18.207" x2="17.448" y1="12.178" y2="9.468" gradientUnits="userSpaceOnUse"><stop class="a_xmkojdq"/><stop offset="1" class="u_pd93bvm"/></linearGradient><linearGradient id="iokKzGc" x1="25.013" x2="23.016" y1="6.218" y2="6.288" gradientUnits="userSpaceOnUse"><stop offset=".149" class="zgff__bcr"/><stop offset="1" class="w-g7jabxf"/></linearGradient><linearGradient id="iFg3qDc" x1="24.329" x2="24.328" y1="6.762" y2="6.575" gradientUnits="userSpaceOnUse"><stop class="ah5butb7g"/><stop offset="1" class="m-22afbga"/></linearGradient><linearGradient id="iAtGHKc" x1="4.839" x2="7.829" y1="11.436" y2="11.436" gradientUnits="userSpaceOnUse"><stop class="oj5k1ib6q"/><stop offset=".588" class="lvlod4-sl"/></linearGradient><linearGradient id="ir8P1ee" x1="5.91" x2="5.91" y1="12.069" y2="11.624" gradientUnits="userSpaceOnUse"><stop class="li_6k3bgy"/><stop offset="1" class="dradh66ej"/></linearGradient><linearGradient id="ixw5dVd" x1="4.236" x2="6.799" y1="11.876" y2="11.876" gradientUnits="userSpaceOnUse"><stop class="oj5k1ib6q"/><stop offset=".588" class="lvlod4-sl"/></linearGradient><linearGradient id="iqniGgc" x1="5.154" x2="5.154" y1="12.509" y2="12.064" gradientUnits="userSpaceOnUse"><stop class="li_6k3bgy"/><stop offset="1" class="dradh66ej"/></linearGradient><linearGradient id="iXOmxIc" x1="4.645" x2="6.739" y1="12.46" y2="12.46" gradientUnits="userSpaceOnUse"><stop class="oj5k1ib6q"/><stop offset=".588" class="lvlod4-sl"/></linearGradient><linearGradient id="iIMhh4F" x1="5.395" x2="5.395" y1="13.092" y2="12.647" gradientUnits="userSpaceOnUse"><stop class="li_6k3bgy"/><stop offset="1" class="dradh66ej"/></linearGradient><linearGradient id="ibfNK1g" x1="15.131" x2="12.107" y1="7.091" y2="7.272" gradientUnits="userSpaceOnUse"><stop class="zpg97tbto"/><stop offset="1" class="l-3q2ti-u"/></linearGradient><linearGradient id="iTfPPhR" x1="15.187" x2="15.306" y1="6.253" y2="6.269" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="ijpUdCt" x1="12.78" x2="12.976" y1="5.996" y2="6.06" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="ifWZjCD" width="4.141" height="6.811" x="15.901" y="15.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23775"/></filter><filter id="iQYCNPb" width="5.768" height="8.746" x="12.843" y="8.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.443137 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23775"/></filter><filter id="ieesKWc" width="9.915" height="8.775" x="15.493" y="2.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.121569 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23775"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.176471 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23775" result="effect2_innerShadow_3987_23775"/></filter><filter id="iybxfEe" width="2.43" height="2.868" x="6.814" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.529412 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23775"/></filter><filter id="iluCZvg" width="2.065" height=".799" x="4.564" y="11.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23775" stdDeviation=".15"/></filter><filter id="ieD29fy" width="2.506" height=".866" x="4.08" y="11.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23775" stdDeviation=".15"/></filter><filter id="iHNr7He" width="4.683" height="5.535" x="11.907" y="3.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.239216 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23775"/></filter><filter id="i9U8zzb" width="6.724" height="5.754" x="11.455" y="2.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.262745 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23775"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.054902 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23775" result="effect2_innerShadow_3987_23775"/></filter><filter id="iUOb4ae" width="1.175" height=".679" x="12.644" y="4.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23775"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-playing-handball-dark" /></template>
<style>
.a_wk1gzgh {
  stop-color: var(--svg-color--2e7ef2, #2E7EF2);
}

.a_xmkojdq {
  stop-color: var(--svg-color--1a65dc, #1A65DC);
}

.a18i0zbmv {
  width: 1.465px;
  height: 0.199px;
  x: 4.864px;
  y: 12.272px;
  fill: var(--svg-color--574545, #574545);
  rx: 0.099px;
}

.a5v-ibbyp {
  stop-color: var(--svg-color--422229, #422229);
  stop-opacity: 0;
}

.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.afs2-ebiq {
  d: path("M24.553 4.124a2.063 2.063 0 1 1-4.125 0a2.063 2.063 0 0 1 4.125 0");
}

.ah5butb7g {
  stop-color: var(--svg-color--5c7ec9, #5C7EC9);
}

.amd51vbjg {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M16.55 22.745s-.464-1.232-.64-2.275c-.176-1.044 2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.982-3.133 1.16");
}

.ao5r4vunm {
  stop-color: var(--svg-color--584a48, #584A48);
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

.b7qlthb7k {
  stop-color: var(--svg-color--4c2e2e, #4C2E2E);
  stop-opacity: 0;
}

.bc_6ftbdd {
  stop-color: var(--svg-color--ddd9e2, #DDD9E2);
}

.boe213jez {
  stop-color: var(--svg-color--4990db, #4990DB);
}

.c2ukjabcr {
  stop-color: var(--svg-color--4d318d, #4D318D);
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.cu51yf-7r {
  stop-color: var(--svg-color--4f3838, #4F3838);
}

.d_6rbhb8w {
  d: path("M13.976 8.014h2.217v3.3h-2.217z");
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.dbxn0ya4l {
  stop-color: var(--svg-color--5d4846, #5D4846);
}

.dhzphmhhv {
  stop-color: var(--svg-color--44263d, #44263D);
}

.dradh66ej {
  stop-color: var(--svg-color--412232, #412232);
  stop-opacity: 0;
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

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.ebb6qj3ko {
  stop-color: var(--svg-color--4c3431, #4C3431);
}

.efuw_n2tj {
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.804.8 1.416l-.809 2.915a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.322l.809-2.916a1.15 1.15 0 0 1 1.416-.801");
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

.f3k2wzgtv {
  d: path("m13.104 6.408l.005-.077c0-.196-.084-.354-.186-.354c-.103 0-.186.158-.186.354q0 .04.004.077z");
}

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
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

.g3-qtzb2n {
  d: path("M13.31 6.408v-.005c0-.338-.144-.612-.323-.612s-.324.274-.324.612v.005z");
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

.gioczw4ny {
  stop-color: var(--svg-color--3f2b28, #3F2B28);
}

.gkcpx30-s {
  stop-color: var(--svg-color--4784cd, #4784CD);
}

.gn7z4wb2i {
  stop-color: var(--svg-color--3382fa, #3382FA);
  stop-opacity: 0;
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gxkjg_bzv {
  fill: var(--svg-color--42292d, #42292D);
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.804-8.137-.703c-.512-.375-.471-.93-.095-1.441");
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.ibzaseb-i {
  stop-color: var(--svg-color--6c5551, #6C5551);
}

.iepxmux-c {
  width: 1.906px;
  height: 0.266px;
  x: 4.38px;
  y: 11.674px;
  fill: var(--svg-color--574545, #574545);
  rx: 0.133px;
}

.igyzmj7fv {
  stop-color: var(--svg-color--59a5ed, #59A5ED);
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

.jo_5u8xym {
  d: path("M11.9 6.587a1.06 1.06 0 0 0 .272-.483h.19v1.189c-.227.144-.552.122-.648-.095c-.083-.186-.02-.417.186-.61");
}

.jw3sj5zvz {
  stop-color: var(--svg-color--4c3431, #4C3431);
  stop-opacity: 0;
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

.l-3q2ti-u {
  stop-color: var(--svg-color--48302f, #48302F);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lbh256w_i {
  stop-color: var(--svg-color--301d1c, #301D1C);
}

.li_6k3bgy {
  stop-color: var(--svg-color--412232, #412232);
}

.ljsluudhz {
  stop-color: var(--svg-color--4c2e2e, #4C2E2E);
}

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.lvlod4-sl {
  stop-color: var(--svg-color--42292d, #42292D);
}

.m-22afbga {
  stop-color: var(--svg-color--5c7ec9, #5C7EC9);
  stop-opacity: 0;
}

.m5_tnryam {
  stop-color: var(--svg-color--66638b, #66638B);
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

.mqryp-bup {
  d: path("M4.624 11.557a.44.44 0 0 1 .44-.44h1.373c.113 0 .54.008.9.147l.109.34l-.403.393h-1.98a.44.44 0 0 1-.44-.44");
}

.n-awbpg6m {
  stop-color: var(--svg-color--42273f, #42273F);
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

.ndsrk3fql {
  fill: var(--svg-color--584444, #584444);
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.ne985-vqe {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
}

.ob57ysbap {
  stop-color: var(--svg-color--443331, #443331);
  stop-opacity: 0;
}

.oj5k1ib6q {
  stop-color: var(--svg-color--594441, #594441);
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

.pcwcq6ykk {
  d: path("M7.828 11.587a.197.197 0 0 1 .257-.09c.244.112.695.325.974.496c.085.052.108.16.061.247l-1.028 1.906a.186.186 0 0 1-.223.091a4 4 0 0 1-.975-.495a.19.19 0 0 1-.057-.247z");
}

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
  stop-opacity: 0;
}

.ppv4posfy {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m25.947 22.035l-1.294.558l.035 1.71c.33.289 1.104 1.066 1.808 1.602c.46.35.894.355 1.192.295c.226-.045.287-.3.188-.509l-1.594-3.539a.25.25 0 0 0-.335-.117");
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

.r0caqn-8d {
  stop-color: var(--svg-color--452931, #452931);
  stop-opacity: 0;
}

.r3c9c6tfm {
  d: path("m15.064 7.105l.21-1.52a.768.768 0 0 1-.21 1.52");
}

.r6-e0za-u {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.67 6.408h1.045c0-.414-.234-.75-.522-.75s-.522.336-.522.75");
}

.rfat3lb_o {
  fill: var(--svg-color--493030, #493030);
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.804.8 1.416l-.809 2.915a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.322l.809-2.916a1.15 1.15 0 0 1 1.416-.801");
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

.sis_hvect {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M13.484 5.502c-.155-.111-.383-.117-.529-.117a.211.211 0 1 1 0-.422h.01c.136 0 .49-.001.766.196a.211.211 0 1 1-.247.343");
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

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sx_wpgngv {
  stop-color: var(--svg-color--464143, #464143);
  stop-opacity: 0;
}

.t12v1gxuw {
  stop-color: var(--svg-color--3c2031, #3C2031);
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

.tr58n2brv {
  cx: 12.855px;
  cy: 6.036px;
  rx: 0.068px;
  ry: 0.093px;
}

.u_pd93bvm {
  stop-color: var(--svg-color--3080f1, #3080F1);
  stop-opacity: 0;
}

.u8e_1ft3u {
  stop-color: var(--svg-color--4d3432, #4D3432);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uhopwn8ty {
  d: path("M12.811 4.773c-.693 0-1.023-.392-1.056-.883c0-.693.53-.84.734-.862c.232-.025.322-.05.644-.277a.95.95 0 0 1 .962-.103c.157.074.503.112.751.037c.413-.124.735-.12 1.052.124c.221.17.384.17.648.17c.363 0 .672.162.904.338c.695.525.615 2.331.273 3.347c-.328.97-.822 1.085-1.235 1.048c-.496-.045-.623-.421-.697-.735c-.06-.25-.212-1.046-.28-1.307c-.144-.066-.456-.09-.562-.5c-.105-.41-.52-.457-.8-.43c-.171.017-.644.033-1.338.033");
}

.usr-62t-w {
  stop-color: var(--svg-color--472b33, #472B33);
  stop-opacity: 0;
}

.ux8hz1b7z {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M13.459 7.585a.13.13 0 0 1-.002.186c-.252.247-.615.31-.731.322a.132.132 0 0 1-.027-.263c.099-.01.387-.065.573-.247a.13.13 0 0 1 .187.002");
}

.uxn5a8bke {
  d: path("M12.136 5.569c.04-.846.315-1.254.444-1.374h3.943l.066 3.343c-.915 2.241-3.71 2.337-4.127 1.527s-.373-2.516-.326-3.496");
}

.uysgu56cq {
  stop-color: var(--svg-color--48302c, #48302C);
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.v23x_cgsr {
  stop-color: var(--svg-color--482c2e, #482C2E);
}

.v27sfw_5y {
  stop-color: var(--svg-color--443331, #443331);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
}

.vg-1agb5d {
  stop-color: var(--svg-color--3f2b28, #3F2B28);
  stop-opacity: 0;
}

.vjh3yqznr {
  d: path("m7.403 28.647l2.214-1.071l1.575.751l-.014 1.34a.253.253 0 0 1-.252.249l-3.854.022c-.221.002-.418-.15-.395-.369c.046-.453.333-.737.726-.922");
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

.xezvpxvhe {
  stop-color: var(--svg-color--4fb3ff, #4FB3FF);
  stop-opacity: 0;
}

.xojzxxboq {
  stop-color: var(--svg-color--574241, #574241);
  stop-opacity: 0;
}

.xv-sacbws {
  stop-color: var(--svg-color--544b49, #544B49);
  stop-opacity: 0;
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

.zmktv7koj {
  stop-color: var(--svg-color--4589bd, #4589BD);
}

.zpg97tbto {
  stop-color: var(--svg-color--432b2f, #432B2F);
}

.zsdj_cc5a {
  stop-color: var(--svg-color--523939, #523939);
}

</style>
