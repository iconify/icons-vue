<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iGwOpxd)" class="q12x_3brx"/><path fill="url(#idZHjgc)" class="q12x_3brx"/><path fill="url(#isS8u3b)" class="q12x_3brx"/><path class="e_8ki4b8j"/><path fill="url(#iySypzb)" class="zguchrbop"/><path fill="url(#iJVlpmi)" class="zguchrbop"/><path class="mr8h2bixv"/><path fill="url(#ixKKdrs)" class="g9d0ovbvp"/><path fill="url(#iKx9G5K)" class="g9d0ovbvp"/><path fill="url(#ijqVH7d)" class="g9d0ovbvp"/><path fill="url(#i7Gr6le)" class="g9d0ovbvp"/><path fill="url(#iXLkHkd)" class="qum9srb-r"/><path fill="url(#iHcv93c)" class="qum9srb-r"/><path fill="url(#i2glQTb)" class="qum9srb-r"/><path fill="url(#iSHdxeb)" class="qum9srb-r"/><g filter="url(#iZQYP7c)"><path class="amd51vbjg"/><path fill="url(#i6AMUmc)" class="mfs1vbcha"/></g><path clip-rule="evenodd" class="yh_1i3b0p"/><path fill="url(#iZ1F9vd)" clip-rule="evenodd" class="qn7308bds"/><path fill="url(#iy2hizc)" clip-rule="evenodd" class="qn7308bds"/><path fill="url(#irLq2Eo)" clip-rule="evenodd" class="qn7308bds"/><path fill="url(#i3wPhXd)" transform="rotate(-23.31 13.976 8.014)" class="d_6rbhb8w"/><path fill="url(#iVf5m7p)" class="e30fqyb5i"/><path fill="url(#iqteI2d)" class="e30fqyb5i"/><g filter="url(#i3PQsbd)"><path fill="url(#iuAeDyD)" class="pmfh29bzg"/><path fill="url(#ijl4FSb)" class="pmfh29bzg"/><path fill="url(#i73BxmV)" class="pmfh29bzg"/><path fill="url(#iquagdc)" class="pmfh29bzg"/></g><g filter="url(#i7LoItc)"><path fill="url(#ikdYTte)" class="ew2h1abfn"/><path fill="url(#i0trfyO)" class="ew2h1abfn"/></g><path fill="url(#iQUjV2c)" class="b0w9lybld"/><path fill="url(#itaOJEb)" class="b0w9lybld"/><path fill="url(#iioSs8d)" class="b0w9lybld"/><path class="t_anc7bpf"/><path clip-rule="evenodd" class="bu1ey-bgu"/><g filter="url(#idtJocb)"><path clip-rule="evenodd" class="an62qbczb"/></g><path class="ft15z2byt"/><path fill="url(#iITaX0f)" class="red5ac8yl"/><path fill="url(#iEYCZ4Q)" class="sw9sb2brd"/><ellipse fill="url(#idaZGzd)" transform="rotate(22.056 12.795 6.098)" class="el7kllbbl"/><g filter="url(#iN03ufb)"><path class="ox_6cuw8l"/><path fill="url(#igv4lBc)" class="sld9yacoe"/><path fill="url(#ixFzlsC)" class="sld9yacoe"/><path fill="url(#iZLPaDc)" class="sld9yacoe"/><path fill="url(#i8dt67b)" class="sld9yacoe"/><path fill="url(#iz53cee)" class="sld9yacoe"/></g><path fill="url(#iD3yzkc)" class="edgroyb3v"/><path fill="url(#iAciTGb)" class="edgroyb3v"/><path fill="url(#iiDMUtc)" class="edgroyb3v"/><path fill="url(#iq6Q1Wl)" class="edgroyb3v"/><path class="rq_vxdcfr"/><path fill="url(#im7C13b)" class="c5snbbbrs"/><path fill="url(#i21JStR)" class="c5snbbbrs"/><path fill="url(#itc1s5b)" class="c5snbbbrs"/><path class="kmd3qcb-j"/><path fill="url(#iiwTGEe)" class="e0lhu47_k"/><path fill="url(#izYIVRu)" class="e0lhu47_k"/><path fill="url(#iRYIdJc)" class="e0lhu47_k"/><path fill="url(#ir7LSIc)" class="e0lhu47_k"/><path fill="url(#idaGKtb)" class="e0lhu47_k"/><g filter="url(#i2wElNd)"><path clip-rule="evenodd" class="sj-lltwha"/></g><path fill="url(#iSUeAtt)" clip-rule="evenodd" class="rrye52blb"/><path fill="url(#iRE3Qtc)" clip-rule="evenodd" class="rrye52blb"/><path class="ma2xobbat"/><path fill="url(#izJHzVI)" class="a_oyxelii"/><path fill="url(#iPCINJe)" class="a_oyxelii"/><path fill="url(#iePsxCb)" class="a_oyxelii"/><rect fill="url(#ijXMCuq)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><rect fill="url(#iDJCtue)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><path fill="url(#ifZbC7c)" class="mqryp-bup"/><path fill="url(#iWmhT4j)" class="vtxj36boz"/><path fill="url(#iZiHlOe)" class="vtxj36boz"/><path fill="url(#iQzraKd)" class="t3ncs1j8m"/><path fill="url(#iBmo3in)" class="t3ncs1j8m"/><g filter="url(#ifiJCqb)"><path fill="url(#iliIEGe)" class="pcwcq6ykk"/></g><path fill="url(#inqL0Pd)" class="pb93aprhh"/><path fill="url(#ipDfQxd)" class="pb93aprhh"/><path fill="url(#iFMDzle)" class="pb93aprhh"/><path fill="url(#iVgiUxb)" class="pb93aprhh"/><path fill="url(#iESVPYb)" class="pb93aprhh"/><g filter="url(#iVILjbc)"><rect class="wdluo8w4e"/></g><defs><radialGradient id="ixKKdrs" cx="0" cy="0" r="1" gradientTransform="matrix(.61864 2.14418 -1.49974 .4327 18.926 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="c4e5_obhh"/><stop offset="1" class="mw5xv5bly"/></radialGradient><radialGradient id="iKx9G5K" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 18.88 22.28)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="el1f73rff"/><stop offset="1" class="iasiczten"/></radialGradient><radialGradient id="ijqVH7d" cx="0" cy="0" r="1" gradientTransform="matrix(.80677 2.5012 -1.15566 .37276 16.338 22.544)" gradientUnits="userSpaceOnUse"><stop class="u_7vzbbil"/><stop offset="1" class="n4e7hibnk"/></radialGradient><radialGradient id="i7Gr6le" cx="0" cy="0" r="1" gradientTransform="rotate(71.565 -6.364 23.576)scale(.54352 3.09962)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="u07rntblp"/><stop offset="1" class="tbt6sb7pf"/></radialGradient><radialGradient id="iXLkHkd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 12.825 19.514)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b-r5tpb7o"/><stop offset="1" class="f8fx77o2h"/></radialGradient><radialGradient id="iHcv93c" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 10.934 8.218)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="smyxvjbxd"/><stop offset="1" class="k24mmwbna"/></radialGradient><radialGradient id="i2glQTb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.114 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="nvd1i1bng"/><stop offset="1" class="gwjk8-8_e"/></radialGradient><radialGradient id="i6AMUmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 16.614 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iZ1F9vd" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.529 4.431)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="swgsx6bpm"/><stop offset="1" class="wcx06_c5w"/></radialGradient><radialGradient id="iy2hizc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 10.926 11.811)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="so5pusb0b"/><stop offset=".952" class="ifv48cbic"/></radialGradient><radialGradient id="irLq2Eo" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 10.63 11.764)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="apa7qrbhd"/><stop offset="1" class="g7rslpl_w"/></radialGradient><radialGradient id="i3wPhXd" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 14.966 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="qik8kac6n"/><stop offset=".75" class="d8jx6bckt"/></radialGradient><radialGradient id="iVf5m7p" cx="0" cy="0" r="1" gradientTransform="matrix(.52353 .25374 -.35817 .73898 11.558 7.183)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="rcpmccbyc"/><stop offset=".684" class="wdglv_bwm"/></radialGradient><radialGradient id="iqteI2d" cx="0" cy="0" r="1" gradientTransform="rotate(-114.937 8.397 -.078)scale(.33852 .50804)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="ijl4FSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9073 -.01036 .01263 -1.10617 15.452 6.258)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="i73BxmV" cx="0" cy="0" r="1" gradientTransform="matrix(-.2482 -5.56443 2.16208 -.09644 12.403 7.666)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="nkfrpdbdq"/><stop offset="1" class="eqwiy2pxg"/></radialGradient><radialGradient id="iquagdc" cx="0" cy="0" r="1" gradientTransform="rotate(87.446 3.27 10.121)scale(.41942 .65411)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="ikdYTte" cx="0" cy="0" r="1" gradientTransform="matrix(.125 7.604 -9.44168 .15521 17.264 2.18)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="a5dpq-jqr"/><stop offset="1" class="xto4yk07k"/></radialGradient><radialGradient id="i0trfyO" cx="0" cy="0" r="1" gradientTransform="matrix(1.62576 -.5365 1.1497 3.48397 11.995 4.006)" gradientUnits="userSpaceOnUse"><stop class="k_urnmdao"/><stop offset="1" class="w7r1zi1yh"/></radialGradient><radialGradient id="iQUjV2c" cx="0" cy="0" r="1" gradientTransform="matrix(.76926 -.26103 .1274 .37547 15.123 6.151)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="itaOJEb" cx="0" cy="0" r="1" gradientTransform="matrix(.29883 1.25465 -1.3074 .3114 15.142 5.827)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="iITaX0f" cx="0" cy="0" r="1" gradientTransform="matrix(.2933 -.01308 .02542 .56985 12.921 6.447)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iEYCZ4Q" cx="0" cy="0" r="1" gradientTransform="matrix(.26875 -.01199 .02594 .5816 12.742 6.479)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="igv4lBc" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 8.954 7.552)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="j9k9ec-7q"/><stop offset="1" class="tqhat7z5r"/></radialGradient><radialGradient id="ixFzlsC" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.527 10.23)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="vrrbv9blf"/><stop offset="1" class="zs4p_mbda"/></radialGradient><radialGradient id="i8dt67b" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 16.91 11.233)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="vpqlu-bzk"/><stop offset="1" class="chgiqwu_c"/></radialGradient><radialGradient id="iz53cee" cx="0" cy="0" r="1" gradientTransform="rotate(168.111 7.835 8.235)scale(4.55199 6.32638)" gradientUnits="userSpaceOnUse"><stop offset=".635" class="p1be21okm"/><stop offset=".993" class="my6lpcbbn"/></radialGradient><radialGradient id="iAciTGb" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 6.675 29.938)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iq6Q1Wl" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.423 12.192)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iiwTGEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.124 17.331)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="izYIVRu" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.435 22.802)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iRYIdJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.173 18.126)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="idaGKtb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 13.704 17.342)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="iRE3Qtc" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.77 7.069)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="bg8bjl54k"/><stop offset="1" class="mdp6qlbos"/></radialGradient><radialGradient id="iPCINJe" cx="0" cy="0" r="1" gradientTransform="matrix(1.03998 -.1057 .17848 1.75613 14.893 10.83)" gradientUnits="userSpaceOnUse"><stop class="ocwrhdbmt"/><stop offset="1" class="v45x_gblz"/></radialGradient><radialGradient id="iePsxCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 19.656 9.918)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="rxuxfhbms"/><stop offset="1" class="w0jybqera"/></radialGradient><radialGradient id="iliIEGe" cx="0" cy="0" r="1" gradientTransform="rotate(-149.027 6.18 5.213)scale(1.15719 1.60341)" gradientUnits="userSpaceOnUse"><stop class="t6ld_bbob"/><stop offset="1" class="zlcet8bnw"/></radialGradient><radialGradient id="inqL0Pd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 11.86 .42)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ipDfQxd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.727 -9.355)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="iFMDzle" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 20.567 4.249)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iVgiUxb" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.05 4.184)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iESVPYb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.727 -3.655)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><linearGradient id="iGwOpxd" x1="11.364" x2="9.677" y1="26.108" y2="26.358" gradientUnits="userSpaceOnUse"><stop class="s0d_o1h9v"/><stop offset="1" class="q1-w0b0qt"/></linearGradient><linearGradient id="idZHjgc" x1="8.93" x2="9.665" y1="24.418" y2="24.277" gradientUnits="userSpaceOnUse"><stop offset=".237" class="l2quysbsq"/><stop offset="1" class="qibnn1bya"/></linearGradient><linearGradient id="isS8u3b" x1="11.286" x2="10.856" y1="22.709" y2="22.811" gradientUnits="userSpaceOnUse"><stop class="lyz1uln4w"/><stop offset="1" class="pvjw0ujzi"/></linearGradient><linearGradient id="iySypzb" x1="22.817" x2="22.759" y1="24.6" y2="23.377" gradientUnits="userSpaceOnUse"><stop class="afqpej-7d"/><stop offset="1" class="aft-xhbkd"/><stop offset="1" class="cll88gg-t"/></linearGradient><linearGradient id="iJVlpmi" x1="22.196" x2="22.196" y1="22.452" y2="23.361" gradientUnits="userSpaceOnUse"><stop class="okh6_pbqf"/><stop offset="1" class="u1j_tu46h"/></linearGradient><linearGradient id="iSHdxeb" x1="10.659" x2="10.659" y1="18.631" y2="19.952" gradientUnits="userSpaceOnUse"><stop class="jtac7ua_e"/><stop offset="1" class="p3lmqxq4r"/></linearGradient><linearGradient id="iuAeDyD" x1="15.153" x2="12.091" y1="7.065" y2="7.386" gradientUnits="userSpaceOnUse"><stop class="w6b0chbuk"/><stop offset="1" class="n3dqqoxxk"/></linearGradient><linearGradient id="iioSs8d" x1="15.068" x2="15.228" y1="6.227" y2="6.233" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="idaZGzd" x1="12.718" x2="12.918" y1="6.057" y2="6.122" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iZLPaDc" x1="15.451" x2="15.28" y1="16.799" y2="15.986" gradientUnits="userSpaceOnUse"><stop offset=".185" class="lkg-r5bvc"/><stop offset="1" class="pdj8m471t"/></linearGradient><linearGradient id="iD3yzkc" x1="9.864" x2="11.395" y1="28.92" y2="28.92" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iiDMUtc" x1="9.427" x2="9.427" y1="29.938" y2="29.616" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="im7C13b" x1="25.352" x2="25.949" y1="22.068" y2="23.186" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i21JStR" x1="25.602" x2="26.296" y1="25.019" y2="24.152" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="itc1s5b" x1="27.316" x2="26.923" y1="24.152" y2="24.327" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ir7LSIc" x1="13.336" x2="13.786" y1="17.398" y2="18.466" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="iSUeAtt" x1="21.364" x2="21.177" y1="11.03" y2="10.092" gradientUnits="userSpaceOnUse"><stop offset=".076" class="bf4ns_o8j"/><stop offset="1" class="oi5imboky"/></linearGradient><linearGradient id="izJHzVI" x1="18.207" x2="17.448" y1="12.177" y2="9.467" gradientUnits="userSpaceOnUse"><stop class="nqy0qlkmp"/><stop offset="1" class="lvqtzth8g"/></linearGradient><linearGradient id="ijXMCuq" x1="25.013" x2="23.016" y1="6.218" y2="6.288" gradientUnits="userSpaceOnUse"><stop offset=".149" class="jjrmc66dk"/><stop offset="1" class="m0_of534w"/></linearGradient><linearGradient id="iDJCtue" x1="24.329" x2="24.328" y1="6.762" y2="6.575" gradientUnits="userSpaceOnUse"><stop class="d1use2f4c"/><stop offset="1" class="iiu2g6sey"/></linearGradient><linearGradient id="ifZbC7c" x1="4.29" x2="7.829" y1="11.436" y2="11.436" gradientUnits="userSpaceOnUse"><stop class="dosa6sbas"/><stop offset=".588" class="gd67z4bal"/></linearGradient><linearGradient id="iWmhT4j" x1="4.236" x2="6.799" y1="11.876" y2="11.876" gradientUnits="userSpaceOnUse"><stop class="dosa6sbas"/><stop offset=".588" class="gd67z4bal"/></linearGradient><linearGradient id="iZiHlOe" x1="5.154" x2="5.154" y1="12.509" y2="12.064" gradientUnits="userSpaceOnUse"><stop class="x9uaycblj"/><stop offset="1" class="pnjqveb_u"/></linearGradient><linearGradient id="iQzraKd" x1="4.645" x2="6.739" y1="12.459" y2="12.459" gradientUnits="userSpaceOnUse"><stop class="lpv-lnbtt"/><stop offset=".588" class="gex5jb8qh"/></linearGradient><linearGradient id="iBmo3in" x1="5.395" x2="5.395" y1="13.092" y2="12.647" gradientUnits="userSpaceOnUse"><stop class="x3uyqiwdn"/><stop offset="1" class="l_u_tcbng"/></linearGradient><filter id="iZQYP7c" width="4.141" height="6.811" x="15.901" y="15.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23783"/></filter><filter id="i3PQsbd" width="4.811" height="5.75" x="11.843" y="3.862" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.521569 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23783"/></filter><filter id="i7LoItc" width="7.474" height="7.745" x="11.358" y="2.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23783"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.788235 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23783" result="effect2_innerShadow_3987_23783"/></filter><filter id="idtJocb" width="1.088" height=".576" x="12.604" y="5.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23783"/></filter><filter id="iN03ufb" width="5.768" height="8.646" x="12.843" y="9.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.352941 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23783"/></filter><filter id="i2wElNd" width="9.915" height="8.775" x="15.493" y="2.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.466667 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23783"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.603922 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23783" result="effect2_innerShadow_3987_23783"/></filter><filter id="ifiJCqb" width="2.43" height="2.868" x="6.814" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.313726 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23783"/></filter><filter id="iVILjbc" width="2.065" height=".799" x="4.564" y="11.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23783" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-playing-handball-medium-light" /></template>
<style>
.a_oyxelii {
  d: path("m19.732 11.597l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
}

.a5dpq-jqr {
  stop-color: var(--svg-color--ffd9ab, #FFD9AB);
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

.amd51vbjg {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M16.55 22.745s-.464-1.232-.64-2.275c-.176-1.044 2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.982-3.133 1.16");
}

.an62qbczb {
  fill: var(--svg-color--915d37, #915D37);
  fill-rule: evenodd;
  d: path("M13.126 5.35a.8.8 0 0 0-.234-.006a.161.161 0 0 1-.054-.318c.076-.012.2-.015.337.006s.3.069.446.166a.16.16 0 1 1-.18.268a.8.8 0 0 0-.315-.116");
}

.apa7qrbhd {
  stop-color: var(--svg-color--c8926f, #C8926F);
}

.b-r5tpb7o {
  stop-color: var(--svg-color--8663d2, #8663D2);
}

.b0w9lybld {
  d: path("m15.003 7.095l.145-1.554a.78.78 0 0 1-.146 1.554");
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

.bu1ey-bgu {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.478 7.642c.054.05.057.135.007.19c-.245.262-.611.342-.728.36a.134.134 0 0 1-.04-.266c.1-.015.39-.084.571-.277a.134.134 0 0 1 .19-.007");
}

.c-xbvquvy {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
}

.c2ukjabcr {
  stop-color: var(--svg-color--4d318d, #4D318D);
}

.c4e5_obhh {
  stop-color: var(--svg-color--9579d9, #9579D9);
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

.chgiqwu_c {
  stop-color: var(--svg-color--643cae, #643CAE);
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

.d1use2f4c {
  stop-color: var(--svg-color--764db5, #764DB5);
}

.d8jx6bckt {
  stop-color: var(--svg-color--cb9b80, #CB9B80);
}

.dosa6sbas {
  stop-color: var(--svg-color--f9be9f, #F9BE9F);
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

.e30fqyb5i {
  d: path("M11.85 6.7c.16-.165.236-.404.254-.502l.193-.009l.054 1.207c-.224.157-.555.148-.662-.067c-.092-.185-.04-.423.16-.629");
}

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.edgroyb3v {
  d: path("m7.403 28.647l2.214-1.072l1.575.752l-.014 1.34a.253.253 0 0 1-.252.249l-3.854.022c-.221.001-.418-.15-.395-.37c.046-.452.333-.736.726-.921");
}

.el1f73rff {
  stop-color: var(--svg-color--7b46d0, #7B46D0);
  stop-opacity: 0;
}

.el7kllbbl {
  cx: 12.795px;
  cy: 6.098px;
  rx: 0.069px;
  ry: 0.094px;
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.eqwiy2pxg {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
  stop-opacity: 0;
}

.ew2h1abfn {
  d: path("M11.85 4.216c-.203-.431-.022-.905.075-1.07c.361-.738 1.175-.822 1.655-.636c.564.219.735.34 1.619.046c.885-.296 1.996-.228 2.62.785c.626 1.014.05 2.21.22 2.841c.17.63.58.676.764 1.406c.171 1.017-.432 1.712-.987 1.887s-1.717.077-2.136-.845c-.686-1.508-.299-2.254-.467-3.019s-.64-.962-1.47-.757c-.978.241-1.62-.063-1.892-.638");
}

.f8fx77o2h {
  stop-color: var(--svg-color--845fcd, #845FCD);
}

.ft15z2byt {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.625 6.483l1.06-.047c-.019-.42-.271-.75-.564-.737s-.515.364-.496.784");
}

.ft5dv1b6b {
  fill: none;
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

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwjk8-8_e {
  stop-color: var(--svg-color--9277cc, #9277CC);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.iasiczten {
  stop-color: var(--svg-color--7b46d0, #7B46D0);
}

.ifv48cbic {
  stop-color: var(--svg-color--be7782, #BE7782);
}

.iiu2g6sey {
  stop-color: var(--svg-color--764db5, #764DB5);
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

.j9k9ec-7q {
  stop-color: var(--svg-color--8e7ec2, #8E7EC2);
}

.jjj62-byh {
  stop-color: var(--svg-color--66638b, #66638B);
}

.jjrmc66dk {
  stop-color: var(--svg-color--876bbc, #876BBC);
}

.jtac7ua_e {
  stop-color: var(--svg-color--7b61a3, #7B61A3);
}

.k_urnmdao {
  stop-color: var(--svg-color--ffecb8, #FFECB8);
}

.k24mmwbna {
  stop-color: var(--svg-color--7745c0, #7745C0);
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

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lkg-r5bvc {
  stop-color: var(--svg-color--705dac, #705DAC);
}

.lpv-lnbtt {
  stop-color: var(--svg-color--f8bea1, #F8BEA1);
}

.lvqtzth8g {
  stop-color: var(--svg-color--7e55c7, #7E55C7);
  stop-opacity: 0;
}

.lyz1uln4w {
  stop-color: var(--svg-color--ca907f, #CA907F);
}

.m0_of534w {
  stop-color: var(--svg-color--7a59ab, #7A59AB);
}

.m5_tnryam {
  stop-color: var(--svg-color--66638b, #66638B);
  stop-opacity: 0;
}

.ma2xobbat {
  fill: var(--svg-color--8060b2, #8060B2);
  d: path("m19.732 11.597l-.61-2.961l-3.005.596a1.483 1.483 0 0 0 .55 2.914z");
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

.mqryp-bup {
  d: path("M4.624 11.557a.44.44 0 0 1 .44-.44h1.373c.113 0 .54.008.9.147l.109.34l-.403.393h-1.98a.44.44 0 0 1-.44-.44");
}

.mr8h2bixv {
  fill: var(--svg-color--7e50d4, #7E50D4);
  d: path("m16.942 23.975l-.398-1.297l2.906-1.383l.203 1.125h.258c.162.9.172 2.141.156 2.649c-.041.013-.301.056-.914.125c-1.412.225-2.062-.719-2.21-1.219");
}

.mw5xv5bly {
  stop-color: var(--svg-color--8d6bda, #8D6BDA);
  stop-opacity: 0;
}

.my6lpcbbn {
  stop-color: var(--svg-color--8f76bd, #8F76BD);
}

.n3dqqoxxk {
  stop-color: var(--svg-color--f2b592, #F2B592);
}

.n4e7hibnk {
  stop-color: var(--svg-color--886ac6, #886AC6);
  stop-opacity: 0;
}

.n8gqlhnrc {
  stop-color: var(--svg-color--9583a6, #9583A6);
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

.nqy0qlkmp {
  stop-color: var(--svg-color--6540ac, #6540AC);
}

.nvd1i1bng {
  stop-color: var(--svg-color--9277cc, #9277CC);
  stop-opacity: 0;
}

.ocwrhdbmt {
  stop-color: var(--svg-color--9276c2, #9276C2);
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

.ox_6cuw8l {
  fill: var(--svg-color--745ab0, #745AB0);
  d: path("m15.493 9.4l.674-.168a1.75 1.75 0 0 1 .713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.p1be21okm {
  stop-color: var(--svg-color--755bb1, #755BB1);
  stop-opacity: 0;
}

.p3lmqxq4r {
  stop-color: var(--svg-color--7b61a3, #7B61A3);
  stop-opacity: 0;
}

.pb93aprhh {
  d: path("M24.553 4.125a2.063 2.063 0 1 1-4.125 0a2.063 2.063 0 0 1 4.125 0");
}

.pcwcq6ykk {
  d: path("M7.828 11.587a.197.197 0 0 1 .257-.09c.244.112.695.325.974.496c.085.052.108.16.061.247l-1.028 1.906a.186.186 0 0 1-.223.091a4 4 0 0 1-.975-.495a.19.19 0 0 1-.057-.247z");
}

.pdj8m471t {
  stop-color: var(--svg-color--705dac, #705DAC);
  stop-opacity: 0;
}

.pfu46_y1s {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
}

.pmfh29bzg {
  d: path("M12.044 5.655c.003-.86.262-1.287.388-1.414l4.004-.179l.218 3.39c-.828 2.318-3.66 2.542-4.121 1.738c-.46-.805-.493-2.537-.49-3.535");
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

.red5ac8yl {
  d: path("M13.274 6.454V6.45c-.015-.344-.175-.616-.356-.608c-.182.008-.317.294-.302.637v.004z");
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

.rxuxfhbms {
  stop-color: var(--svg-color--967acc, #967ACC);
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

.smyxvjbxd {
  stop-color: var(--svg-color--7745c0, #7745C0);
}

.so5pusb0b {
  stop-color: var(--svg-color--be7782, #BE7782);
  stop-opacity: 0;
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sw9sb2brd {
  d: path("M13.066 6.464v-.078c-.009-.2-.1-.357-.205-.352c-.104.004-.181.17-.173.37l.008.077z");
}

.swgsx6bpm {
  stop-color: var(--svg-color--c17560, #C17560);
}

.t_anc7bpf {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.679 5.887c-.147-.135-.382-.157-.482-.15l.348.486c.157-.017.318-.168.134-.336");
}

.t3ncs1j8m {
  d: path("M4.494 12.58a.44.44 0 0 1 .44-.44h1.537v.48a.4.4 0 0 1-.4.4H4.934a.44.44 0 0 1-.44-.44");
}

.t54cbcb-z {
  stop-color: var(--svg-color--bab6bd, #BAB6BD);
}

.t6ld_bbob {
  stop-color: var(--svg-color--735d9d, #735D9D);
}

.tbe0sc-ij {
  stop-color: var(--svg-color--4a4970, #4A4970);
}

.tbt6sb7pf {
  stop-color: var(--svg-color--6e46c0, #6E46C0);
  stop-opacity: 0;
}

.tqhat7z5r {
  stop-color: var(--svg-color--8e7ec2, #8E7EC2);
  stop-opacity: 0;
}

.u_7vzbbil {
  stop-color: var(--svg-color--886ac6, #886AC6);
}

.u07rntblp {
  stop-color: var(--svg-color--6e46c0, #6E46C0);
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

.v45x_gblz {
  stop-color: var(--svg-color--8667c0, #8667C0);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vpqlu-bzk {
  stop-color: var(--svg-color--643cae, #643CAE);
}

.vrrbv9blf {
  stop-color: var(--svg-color--745fa7, #745FA7);
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

.w0jybqera {
  stop-color: var(--svg-color--8264b7, #8264B7);
  stop-opacity: 0;
}

.w6b0chbuk {
  stop-color: var(--svg-color--dfa289, #DFA289);
}

.w7r1zi1yh {
  stop-color: var(--svg-color--ffecb8, #FFECB8);
  stop-opacity: 0;
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

.xto4yk07k {
  stop-color: var(--svg-color--d0af85, #D0AF85);
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

.zguchrbop {
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

.zlcet8bnw {
  stop-color: var(--svg-color--6944a2, #6944A2);
}

.zs4p_mbda {
  stop-color: var(--svg-color--745fa7, #745FA7);
  stop-opacity: 0;
}

</style>
