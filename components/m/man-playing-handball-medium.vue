<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ibTjxvc)" class="q12x_3brx"/><path fill="url(#iO9SMcd)" class="q12x_3brx"/><path fill="url(#iBzBIDb)" class="q12x_3brx"/><path class="cnnnte2db"/><path fill="url(#iEzhBge)" class="zguchrbop"/><path fill="url(#iu3zVQd)" class="zguchrbop"/><path class="p8hed8p1i"/><path fill="url(#i8VQyhb)" class="g9d0ovbvp"/><path fill="url(#iTNgb2y)" class="g9d0ovbvp"/><path fill="url(#i6FwaDc)" class="g9d0ovbvp"/><path fill="url(#iAJMqce)" class="g9d0ovbvp"/><path fill="url(#izzU55b)" class="qum9srb-r"/><path fill="url(#ixh406b)" class="qum9srb-r"/><path fill="url(#iCfwbfb)" class="qum9srb-r"/><path fill="url(#i31pOtc)" class="qum9srb-r"/><g filter="url(#iG8Luke)"><path class="amd51vbjg"/><path fill="url(#i6AMUmc)" class="mfs1vbcha"/></g><path clip-rule="evenodd" class="oayv1_mln"/><path fill="url(#iWNidyb)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#i7LrMkc)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#ikrBelc)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#ipyLVvc)" transform="rotate(-23.31 13.976 8.014)" class="d_6rbhb8w"/><g filter="url(#itemSld)"><path class="seanbl9if"/><path fill="url(#ibJRlYd)" class="f1u8ijb3m"/><path fill="url(#iyIhfTP)" class="f1u8ijb3m"/><path fill="url(#iOHXHyc)" class="f1u8ijb3m"/><path fill="url(#iNwsQWc)" class="f1u8ijb3m"/><path fill="url(#irXgbHb)" class="f1u8ijb3m"/></g><path fill="url(#ipSnGqe)" class="vjh3yqznr"/><path fill="url(#iAciTGb)" class="vjh3yqznr"/><path fill="url(#iiDMUtc)" class="vjh3yqznr"/><path fill="url(#iq6Q1Wl)" class="vjh3yqznr"/><path class="ppv4posfy"/><path fill="url(#iYUt5rb)" class="ol51zcmaj"/><path fill="url(#i21JStR)" class="ol51zcmaj"/><path fill="url(#ikduqNe)" class="ol51zcmaj"/><path class="kmd3qcb-j"/><path fill="url(#iiwTGEe)" class="e0lhu47_k"/><path fill="url(#izYIVRu)" class="e0lhu47_k"/><path fill="url(#iRYIdJc)" class="e0lhu47_k"/><path fill="url(#ir7LSIc)" class="e0lhu47_k"/><path fill="url(#idaGKtb)" class="e0lhu47_k"/><g filter="url(#ivrKwtb)"><path clip-rule="evenodd" class="f_lldv3no"/></g><path fill="url(#isuRvQb)" clip-rule="evenodd" class="yzbfo0edn"/><path fill="url(#i1cHlFe)" clip-rule="evenodd" class="yzbfo0edn"/><path class="sc0n1hfuo"/><path fill="url(#iNc8Fic)" class="jmlii5bid"/><path fill="url(#iHCzuPb)" class="jmlii5bid"/><path fill="url(#iKcjUje)" class="jmlii5bid"/><rect fill="url(#iokKzGc)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><rect fill="url(#iFg3qDc)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><path fill="url(#itKrLed)" class="mqryp-bup"/><path fill="url(#iAenrxd)" class="vtxj36boz"/><path fill="url(#iUkHZld)" class="vtxj36boz"/><path fill="url(#ieEkc9c)" class="t3ncs1j8m"/><path fill="url(#iPBfHBe)" class="t3ncs1j8m"/><g filter="url(#ilFiDbT)"><path fill="url(#ibBvqNd)" class="pcwcq6ykk"/></g><path fill="url(#inqL0Pd)" class="pb93aprhh"/><path fill="url(#ipDfQxd)" class="pb93aprhh"/><path fill="url(#iFMDzle)" class="pb93aprhh"/><path fill="url(#iVgiUxb)" class="pb93aprhh"/><path fill="url(#iESVPYb)" class="pb93aprhh"/><g filter="url(#ilotTkd)"><rect class="n54evmbvw"/></g><g filter="url(#ijCOwQb)"><rect class="t3-in9w4l"/></g><path fill="url(#i2IEFBy)" class="azctd0boy"/><path fill="url(#iHgtBsd)" class="azctd0boy"/><g filter="url(#iDd3YlU)"><path fill="url(#icVP7Kd)" class="ak_rnjbbl"/><path fill="url(#iAFr5Ud)" class="ak_rnjbbl"/><path fill="url(#i2FV3xd)" class="ak_rnjbbl"/><path fill="url(#i9h31Lb)" class="ak_rnjbbl"/></g><g filter="url(#iiGTPEe)"><path fill="url(#igYJ4eP)" class="j_ls7xkgr"/><path fill="url(#iMNwbwb)" class="j_ls7xkgr"/><path fill="url(#ilRlwCc)" class="j_ls7xkgr"/></g><path fill="url(#igZbpec)" class="rd9ec5bwk"/><path fill="url(#iOyFLTc)" class="rd9ec5bwk"/><path fill="url(#i43V8wb)" class="rd9ec5bwk"/><path clip-rule="evenodd" class="adhp6qb6l"/><path class="s_emm696q"/><path fill="url(#iacwqcc)" class="bqfijrb7w"/><path fill="url(#iJIeXIe)" class="rn3pavbgw"/><ellipse fill="url(#i9Pypqa)" transform="rotate(24.61 12.848 6.036)" class="am9q6qb_o"/><g filter="url(#ig0bj4M)"><path clip-rule="evenodd" class="sjr__jbme"/></g><defs><radialGradient id="i8VQyhb" cx="0" cy="0" r="1" gradientTransform="matrix(.61864 2.14418 -1.49974 .4327 18.926 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="q359-ccqt"/><stop offset="1" class="xezvpxvhe"/></radialGradient><radialGradient id="iTNgb2y" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 18.88 22.28)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="ez6yh-y9m"/><stop offset="1" class="g0lloqbmi"/></radialGradient><radialGradient id="i6FwaDc" cx="0" cy="0" r="1" gradientTransform="matrix(.80677 2.5012 -1.15566 .37276 16.338 22.544)" gradientUnits="userSpaceOnUse"><stop class="atwm-qoon"/><stop offset="1" class="ovos4t_7k"/></radialGradient><radialGradient id="iAJMqce" cx="0" cy="0" r="1" gradientTransform="rotate(71.565 -6.364 23.576)scale(.54352 3.09962)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="a_wk1gzgh"/><stop offset="1" class="spf2xjb6v"/></radialGradient><radialGradient id="izzU55b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 12.825 19.514)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="g_c95ob_h"/><stop offset="1" class="yb5t-ebeb"/></radialGradient><radialGradient id="ixh406b" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 10.934 8.218)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="aqx-_1b_m"/><stop offset="1" class="gn7z4wb2i"/></radialGradient><radialGradient id="iCfwbfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.114 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="s_sh9varo"/><stop offset=".979" class="b2logdb4l"/></radialGradient><radialGradient id="i6AMUmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 16.614 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iWNidyb" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.529 4.43)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="cw_dmv8-u"/><stop offset="1" class="yo2o8qb-v"/></radialGradient><radialGradient id="i7LrMkc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 10.926 11.811)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="j12jqkbuh"/><stop offset=".952" class="ihyx1abhg"/></radialGradient><radialGradient id="ikrBelc" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 10.63 11.764)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="a1lnoq-qe"/><stop offset="1" class="v-83r_bol"/></radialGradient><radialGradient id="ipyLVvc" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 14.966 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="oxw2g-jck"/><stop offset=".75" class="i0vk4ibxw"/></radialGradient><radialGradient id="ibJRlYd" cx="0" cy="0" r="1" gradientTransform="matrix(.0293 -5.32953 3.38376 .0186 14.815 17.47)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="dyygb2yxz"/><stop offset="1" class="jyyx2-bie"/></radialGradient><radialGradient id="iyIhfTP" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50773 .13384 -.33514 -6.2795 18.298 14.615)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="boe213jez"/><stop offset="1" class="n8m7rnb1b"/></radialGradient><radialGradient id="iOHXHyc" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.527 10.23)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="gkcpx30-s"/><stop offset="1" class="fxro0tyoi"/></radialGradient><radialGradient id="iNwsQWc" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 16.91 11.233)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="ekxdyp1yu"/><stop offset="1" class="zg01gt89b"/></radialGradient><radialGradient id="irXgbHb" cx="0" cy="0" r="1" gradientTransform="rotate(-170.407 9.956 6.194)scale(6.31116 10.4533)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="zbyobmbvc"/><stop offset=".957" class="rmf1gzb-v"/></radialGradient><radialGradient id="iAciTGb" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 6.675 29.938)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iq6Q1Wl" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.423 12.192)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iiwTGEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.124 17.331)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="izYIVRu" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.435 22.802)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iRYIdJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.173 18.126)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="idaGKtb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 13.704 17.342)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="i1cHlFe" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.77 7.069)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="brfm5ympt"/><stop offset="1" class="tf96tsg_a"/></radialGradient><radialGradient id="iHCzuPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.33186 -.12063 .2037 2.249 14.601 10.846)" gradientUnits="userSpaceOnUse"><stop class="y6bw3v3vv"/><stop offset="1" class="igyzmj7fv"/></radialGradient><radialGradient id="iKcjUje" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 19.656 9.918)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="mmjlr5d2n"/><stop offset="1" class="rh-0l3b-i"/></radialGradient><radialGradient id="itKrLed" cx="0" cy="0" r="1" gradientTransform="matrix(3.40685 0 0 1.20429 4.423 11.436)" gradientUnits="userSpaceOnUse"><stop class="gym_2j3rc"/><stop offset=".498" class="qzpft6b_x"/></radialGradient><radialGradient id="ibBvqNd" cx="0" cy="0" r="1" gradientTransform="rotate(-149.027 6.18 5.213)scale(1.15719 1.60341)" gradientUnits="userSpaceOnUse"><stop class="zmktv7koj"/><stop offset="1" class="mnxdxy3jn"/></radialGradient><radialGradient id="inqL0Pd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 11.86 .42)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ipDfQxd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.727 -9.355)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="iFMDzle" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 20.567 4.249)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iVgiUxb" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.05 4.184)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iESVPYb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.727 -3.655)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><radialGradient id="i2IEFBy" cx="0" cy="0" r="1" gradientTransform="matrix(.50349 .27238 -.38447 .7107 11.585 7.05)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="iHgtBsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.12684 -.308 .46222 -.19035 12.013 7.385)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="iAFr5Ud" cx="0" cy="0" r="1" gradientTransform="matrix(-.89142 -.0496 .06048 -1.08682 15.453 6.308)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="i2FV3xd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.48059 2.12951 0 12.393 7.561)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="i9h31Lb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4127 -.6436 0 13.268 6.356)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="igYJ4eP" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6317 3.30158 -3.74378 -4.11812 17.434 3.494)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="i2p5fqtly"/><stop offset="1" class="pw8a02b5q"/></radialGradient><radialGradient id="iMNwbwb" cx="0" cy="0" r="1" gradientTransform="rotate(81.634 6.18 12.17)scale(2.86478 1.26556)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="ltxof3fvo"/><stop offset="1" class="nj0viubvx"/></radialGradient><radialGradient id="ilRlwCc" cx="0" cy="0" r="1" gradientTransform="matrix(1.58475 -.09905 .19437 3.1099 11.838 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="id9lp4hub"/><stop offset="1" class="fed4ggbgk"/></radialGradient><radialGradient id="igZbpec" cx="0" cy="0" r="1" gradientTransform="matrix(.76761 -.22286 .10877 .37466 15.216 6.183)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="iOyFLTc" cx="0" cy="0" r="1" gradientTransform="matrix(.23873 1.2464 -1.2988 .24876 15.25 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="iacwqcc" cx="0" cy="0" r="1" gradientTransform="matrix(.28889 0 0 .56127 12.957 6.385)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iJIeXIe" cx="0" cy="0" r="1" gradientTransform="matrix(.26412 0 0 .57158 12.78 6.408)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="ibTjxvc" x1="11.364" x2="9.677" y1="26.108" y2="26.358" gradientUnits="userSpaceOnUse"><stop class="d3738qb8u"/><stop offset="1" class="ttypkojrk"/></linearGradient><linearGradient id="iO9SMcd" x1="8.817" x2="9.536" y1="24.42" y2="24.358" gradientUnits="userSpaceOnUse"><stop class="jha-984sk"/><stop offset="1" class="strkjwbkt"/></linearGradient><linearGradient id="iBzBIDb" x1="11.286" x2="10.856" y1="22.709" y2="22.811" gradientUnits="userSpaceOnUse"><stop class="e4gncgnqd"/><stop offset="1" class="divg9r_of"/></linearGradient><linearGradient id="iEzhBge" x1="22.817" x2="22.759" y1="24.6" y2="23.377" gradientUnits="userSpaceOnUse"><stop class="il9cx6b8o"/><stop offset="1" class="cll88gg-t"/></linearGradient><linearGradient id="iu3zVQd" x1="22.196" x2="22.196" y1="22.452" y2="23.361" gradientUnits="userSpaceOnUse"><stop class="cror3zfgh"/><stop offset="1" class="odrq36bum"/></linearGradient><linearGradient id="i31pOtc" x1="10.659" x2="10.659" y1="18.631" y2="19.952" gradientUnits="userSpaceOnUse"><stop class="n0ztdwmxa"/><stop offset="1" class="ql2kv4b4e"/></linearGradient><linearGradient id="ipSnGqe" x1="9.864" x2="11.395" y1="28.921" y2="28.921" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iiDMUtc" x1="9.427" x2="9.427" y1="29.938" y2="29.616" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="iYUt5rb" x1="25.352" x2="25.949" y1="22.069" y2="23.186" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i21JStR" x1="25.602" x2="26.296" y1="25.019" y2="24.152" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="ikduqNe" x1="27.316" x2="26.923" y1="24.153" y2="24.327" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ir7LSIc" x1="13.336" x2="13.786" y1="17.398" y2="18.466" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="isuRvQb" x1="21.364" x2="21.177" y1="11.03" y2="10.092" gradientUnits="userSpaceOnUse"><stop offset=".076" class="t2um5owbu"/><stop offset="1" class="co5izhbpm"/></linearGradient><linearGradient id="iNc8Fic" x1="18.207" x2="17.448" y1="12.178" y2="9.468" gradientUnits="userSpaceOnUse"><stop class="a_xmkojdq"/><stop offset="1" class="u_pd93bvm"/></linearGradient><linearGradient id="iokKzGc" x1="25.013" x2="23.016" y1="6.218" y2="6.288" gradientUnits="userSpaceOnUse"><stop offset=".149" class="zgff__bcr"/><stop offset="1" class="w-g7jabxf"/></linearGradient><linearGradient id="iFg3qDc" x1="24.329" x2="24.328" y1="6.762" y2="6.575" gradientUnits="userSpaceOnUse"><stop class="ah5butb7g"/><stop offset="1" class="m-22afbga"/></linearGradient><linearGradient id="iAenrxd" x1="4.236" x2="6.799" y1="11.876" y2="11.876" gradientUnits="userSpaceOnUse"><stop class="wxhwgwbkv"/><stop offset=".588" class="j8i1teydm"/></linearGradient><linearGradient id="iUkHZld" x1="5.154" x2="5.154" y1="12.509" y2="12.064" gradientUnits="userSpaceOnUse"><stop class="b46w5gb0s"/><stop offset="1" class="a6qwprbav"/></linearGradient><linearGradient id="ieEkc9c" x1="4.645" x2="6.739" y1="12.46" y2="12.46" gradientUnits="userSpaceOnUse"><stop class="wxhwgwbkv"/><stop offset=".588" class="j8i1teydm"/></linearGradient><linearGradient id="iPBfHBe" x1="5.395" x2="5.395" y1="13.092" y2="12.647" gradientUnits="userSpaceOnUse"><stop class="b46w5gb0s"/><stop offset="1" class="a6qwprbav"/></linearGradient><linearGradient id="icVP7Kd" x1="15.123" x2="12.099" y1="7.091" y2="7.272" gradientUnits="userSpaceOnUse"><stop class="xwzzv0ryq"/><stop offset="1" class="l3_0v7cyw"/></linearGradient><linearGradient id="i43V8wb" x1="15.159" x2="15.315" y1="6.255" y2="6.267" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="i9Pypqa" x1="12.772" x2="12.969" y1="5.996" y2="6.06" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="iG8Luke" width="4.141" height="6.811" x="15.901" y="15.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23781"/></filter><filter id="itemSld" width="5.768" height="8.746" x="12.843" y="8.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.443137 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23781"/></filter><filter id="ivrKwtb" width="9.915" height="8.775" x="15.493" y="2.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.34902 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23781"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.435294 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23781" result="effect2_innerShadow_3987_23781"/></filter><filter id="ilFiDbT" width="2.43" height="2.868" x="6.814" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.529412 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23781"/></filter><filter id="ilotTkd" width="2.065" height=".799" x="4.564" y="11.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23781" stdDeviation=".15"/></filter><filter id="ijCOwQb" width="2.506" height=".866" x="4.08" y="11.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23781" stdDeviation=".15"/></filter><filter id="iDd3YlU" width="4.683" height="5.534" x="11.899" y="3.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.329412 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23781"/></filter><filter id="iiGTPEe" width="6.724" height="5.754" x="11.448" y="2.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.266667 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23781"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.137255 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23781" result="effect2_innerShadow_3987_23781"/></filter><filter id="ig0bj4M" width="1.175" height=".679" x="12.637" y="4.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23781"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-playing-handball-medium" /></template>
<style>
.a_wk1gzgh {
  stop-color: var(--svg-color--2e7ef2, #2E7EF2);
}

.a_xmkojdq {
  stop-color: var(--svg-color--1a65dc, #1A65DC);
}

.a1lnoq-qe {
  stop-color: var(--svg-color--906b55, #906B55);
}

.a6qwprbav {
  stop-color: var(--svg-color--a77273, #A77273);
  stop-opacity: 0;
}

.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.adhp6qb6l {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.451 7.585a.13.13 0 0 1-.001.186c-.252.247-.616.31-.731.322a.132.132 0 1 1-.027-.263c.098-.01.387-.065.573-.247a.13.13 0 0 1 .186.002");
}

.ah5butb7g {
  stop-color: var(--svg-color--5c7ec9, #5C7EC9);
}

.ak_rnjbbl {
  d: path("M12.129 5.57c.04-.847.315-1.255.444-1.375h3.943l.066 3.343c-.916 2.241-3.71 2.337-4.127 1.527c-.418-.811-.373-2.516-.326-3.496");
}

.am9q6qb_o {
  cx: 12.848px;
  cy: 6.036px;
  rx: 0.068px;
  ry: 0.093px;
}

.amd51vbjg {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M16.55 22.745s-.464-1.232-.64-2.275c-.176-1.044 2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.982-3.133 1.16");
}

.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.aqx-_1b_m {
  stop-color: var(--svg-color--4b67e4, #4B67E4);
}

.atwm-qoon {
  stop-color: var(--svg-color--529af1, #529AF1);
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.azctd0boy {
  d: path("M11.892 6.587a1.07 1.07 0 0 0 .273-.483h.19v1.189c-.228.144-.552.122-.649-.095c-.082-.186-.02-.417.186-.61");
}

.b2logdb4l {
  stop-color: var(--svg-color--5daef5, #5DAEF5);
}

.b46w5gb0s {
  stop-color: var(--svg-color--9f6177, #9F6177);
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

.boe213jez {
  stop-color: var(--svg-color--4990db, #4990DB);
}

.bqfijrb7w {
  d: path("M13.303 6.408v-.004c0-.339-.145-.613-.324-.613c-.178 0-.323.274-.323.613v.004z");
}

.brfm5ympt {
  stop-color: var(--svg-color--c09b80, #C09B80);
}

.c2ukjabcr {
  stop-color: var(--svg-color--4d318d, #4D318D);
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.cll88gg-t {
  stop-color: var(--svg-color--ac787c, #AC787C);
  stop-opacity: 0;
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.cnnnte2db {
  fill: var(--svg-color--b68b7e, #B68B7E);
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.co5izhbpm {
  stop-color: var(--svg-color--a47277, #A47277);
  stop-opacity: 0;
}

.cror3zfgh {
  stop-color: var(--svg-color--a7856e, #A7856E);
}

.cw_dmv8-u {
  stop-color: var(--svg-color--92504d, #92504D);
}

.d_6rbhb8w {
  d: path("M13.976 8.014h2.217v3.3h-2.217z");
}

.d3738qb8u {
  stop-color: var(--svg-color--b98b7a, #B98B7A);
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.divg9r_of {
  stop-color: var(--svg-color--af8175, #AF8175);
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

.e4gncgnqd {
  stop-color: var(--svg-color--a1736a, #A1736A);
}

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.ekxdyp1yu {
  stop-color: var(--svg-color--2a6ae2, #2A6AE2);
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.ez6yh-y9m {
  stop-color: var(--svg-color--3083ff, #3083FF);
  stop-opacity: 0;
}

.f_lldv3no {
  fill: var(--svg-color--a8816c, #A8816C);
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.323l.809-2.915a1.15 1.15 0 0 1 1.416-.801");
}

.f1u8ijb3m {
  d: path("m15.493 9.4l.674-.168c.233-.059.476-.07.713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.fed4ggbgk {
  stop-color: var(--svg-color--634d4a, #634D4A);
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

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
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

.gn7z4wb2i {
  stop-color: var(--svg-color--3382fa, #3382FA);
  stop-opacity: 0;
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gym_2j3rc {
  stop-color: var(--svg-color--ba9379, #BA9379);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.i0vk4ibxw {
  stop-color: var(--svg-color--a78770, #A78770);
}

.i2p5fqtly {
  stop-color: var(--svg-color--52343b, #52343B);
}

.id9lp4hub {
  stop-color: var(--svg-color--634d4a, #634D4A);
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.igyzmj7fv {
  stop-color: var(--svg-color--59a5ed, #59A5ED);
  stop-opacity: 0;
}

.ihyx1abhg {
  stop-color: var(--svg-color--995b7a, #995B7A);
}

.il9cx6b8o {
  stop-color: var(--svg-color--985b84, #985B84);
}

.j_ls7xkgr {
  d: path("M12.804 4.774c-.693 0-1.023-.392-1.056-.884c0-.693.529-.84.734-.862c.231-.025.322-.05.644-.277a.95.95 0 0 1 .962-.103c.156.075.503.112.75.037c.413-.123.735-.12 1.053.124c.22.17.383.17.648.17c.363 0 .671.162.904.338c.694.525.615 2.332.272 3.347c-.328.971-.821 1.085-1.234 1.048c-.497-.045-.623-.421-.697-.735c-.06-.25-.212-1.046-.28-1.307c-.144-.066-.457-.09-.562-.5s-.52-.457-.8-.43c-.171.017-.645.034-1.338.034");
}

.j12jqkbuh {
  stop-color: var(--svg-color--9d6364, #9D6364);
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

.j8i1teydm {
  stop-color: var(--svg-color--a27368, #A27368);
}

.j96xv6b5h {
  stop-color: var(--svg-color--917ea3, #917EA3);
  stop-opacity: 0;
}

.jha-984sk {
  stop-color: var(--svg-color--c59685, #C59685);
}

.jjj62-byh {
  stop-color: var(--svg-color--66638b, #66638B);
}

.jmlii5bid {
  d: path("m19.732 11.598l-.61-2.962l-3.005.597a1.483 1.483 0 0 0 .55 2.914z");
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
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

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l3_0v7cyw {
  stop-color: var(--svg-color--ab826c, #AB826C);
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lhhdsccyq {
  stop-color: var(--svg-color--a66d75, #A66D75);
  stop-opacity: 0;
}

.ltxof3fvo {
  stop-color: var(--svg-color--624646, #624646);
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

.n0ztdwmxa {
  stop-color: var(--svg-color--4493c4, #4493C4);
}

.n54evmbvw {
  width: 1.465px;
  height: 0.199px;
  x: 4.864px;
  y: 12.272px;
  fill: var(--svg-color--b08679, #B08679);
  rx: 0.099px;
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

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.ng2hgzbhn {
  stop-color: var(--svg-color--bf9580, #BF9580);
}

.nj0viubvx {
  stop-color: var(--svg-color--624646, #624646);
  stop-opacity: 0;
}

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.oayv1_mln {
  fill: var(--svg-color--a27368, #A27368);
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.804-8.137-.703c-.512-.375-.471-.93-.095-1.441");
}

.odrq36bum {
  stop-color: var(--svg-color--a7856e, #A7856E);
  stop-opacity: 0;
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

.oxw2g-jck {
  stop-color: var(--svg-color--7a4e3a, #7A4E3A);
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

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.ppv4posfy {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m25.947 22.035l-1.294.558l.035 1.71c.33.289 1.104 1.066 1.808 1.602c.46.35.894.355 1.192.295c.226-.045.287-.3.188-.509l-1.594-3.539a.25.25 0 0 0-.335-.117");
}

.pw8a02b5q {
  stop-color: var(--svg-color--492b38, #492B38);
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

.qzpft6b_x {
  stop-color: var(--svg-color--9d7163, #9D7163);
}

.rd9ec5bwk {
  d: path("m15.056 7.105l.21-1.52a.768.768 0 0 1-.21 1.52");
}

.rh-0l3b-i {
  stop-color: var(--svg-color--389df9, #389DF9);
  stop-opacity: 0;
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
}

.rmf1gzb-v {
  stop-color: var(--svg-color--599cdc, #599CDC);
}

.rn3pavbgw {
  d: path("m13.097 6.408l.004-.077c0-.196-.083-.354-.186-.354c-.102 0-.185.158-.185.354q0 .04.004.077z");
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.s_emm696q {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.664 6.408h1.044c0-.414-.234-.75-.522-.75s-.522.336-.522.75");
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

.seanbl9if {
  fill: var(--svg-color--3584e5, #3584E5);
  d: path("m15.493 9.4l.674-.168c.233-.059.476-.07.713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.sew1y7bbn {
  stop-color: var(--svg-color--514d8b, #514D8B);
  stop-opacity: 0;
}

.sjr__jbme {
  fill: var(--svg-color--513a3c, #513A3C);
  fill-rule: evenodd;
  d: path("M13.477 5.502c-.156-.111-.383-.117-.529-.117a.211.211 0 1 1 0-.423h.01c.136 0 .49 0 .765.197a.211.211 0 0 1-.246.343");
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

.strkjwbkt {
  stop-color: var(--svg-color--af7f77, #AF7F77);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t2um5owbu {
  stop-color: var(--svg-color--935878, #935878);
}

.t3-in9w4l {
  width: 1.906px;
  height: 0.266px;
  x: 4.38px;
  y: 11.674px;
  fill: var(--svg-color--b08679, #B08679);
  rx: 0.133px;
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

.tf96tsg_a {
  stop-color: var(--svg-color--b48a76, #B48A76);
  stop-opacity: 0;
}

.ttypkojrk {
  stop-color: var(--svg-color--b07d78, #B07D78);
}

.u_pd93bvm {
  stop-color: var(--svg-color--3080f1, #3080F1);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.v-83r_bol {
  stop-color: var(--svg-color--906b55, #906B55);
  stop-opacity: 0;
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
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

.wxhwgwbkv {
  stop-color: var(--svg-color--bf9482, #BF9482);
}

.xezvpxvhe {
  stop-color: var(--svg-color--4fb3ff, #4FB3FF);
  stop-opacity: 0;
}

.xwzzv0ryq {
  stop-color: var(--svg-color--a87a72, #A87A72);
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

.yo2o8qb-v {
  stop-color: var(--svg-color--92504d, #92504D);
  stop-opacity: 0;
}

.yzbfo0edn {
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.323l.809-2.915a1.15 1.15 0 0 1 1.416-.801");
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
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

</style>
