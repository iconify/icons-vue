<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iIZoyQb)" class="q12x_3brx"/><path fill="url(#iQQzDfd)" class="q12x_3brx"/><path fill="url(#i9ztGhb)" class="q12x_3brx"/><path class="lv6qs4dqh"/><path fill="url(#i0eVsLe)" class="zguchrbop"/><path fill="url(#ismZuab)" class="zguchrbop"/><path class="mr8h2bixv"/><path fill="url(#ixKKdrs)" class="g9d0ovbvp"/><path fill="url(#iKx9G5K)" class="g9d0ovbvp"/><path fill="url(#ijqVH7d)" class="g9d0ovbvp"/><path fill="url(#i7Gr6le)" class="g9d0ovbvp"/><path fill="url(#iXLkHkd)" class="qum9srb-r"/><path fill="url(#iHcv93c)" class="qum9srb-r"/><path fill="url(#i2glQTb)" class="qum9srb-r"/><path fill="url(#iSHdxeb)" class="qum9srb-r"/><g filter="url(#iXhBkBb)"><path class="amd51vbjg"/><path fill="url(#i6AMUmc)" class="mfs1vbcha"/></g><path clip-rule="evenodd" class="i1put7zdc"/><path fill="url(#iyj9pId)" clip-rule="evenodd" class="cdgjtl8nk"/><path fill="url(#iD20xTc)" clip-rule="evenodd" class="cdgjtl8nk"/><path fill="url(#itKLaUk)" clip-rule="evenodd" class="cdgjtl8nk"/><path fill="url(#iuXm4Ob)" transform="rotate(-23.31 13.976 8.014)" class="d_6rbhb8w"/><path fill="url(#iyEjcDb)" class="iyxi2ittv"/><path fill="url(#iYcPnSw)" class="iyxi2ittv"/><g filter="url(#iAARJFb)"><path fill="url(#iteAhfU)" class="rtlg21b3x"/><path fill="url(#ixQb55q)" class="rtlg21b3x"/><path fill="url(#ioUctYA)" class="rtlg21b3x"/><path fill="url(#iCoLOAd)" class="rtlg21b3x"/></g><g filter="url(#iMi9kbd)"><path class="sfkqlwyif"/><path fill="url(#i0Nwa1c)" class="lh13n-8uj"/></g><path fill="url(#i0h1kQi)" class="egztfybxz"/><path fill="url(#iCB8mXb)" class="egztfybxz"/><path fill="url(#iTJl7Xd)" class="egztfybxz"/><path class="fmy8a7_8n"/><path clip-rule="evenodd" class="v7fhh3bko"/><g filter="url(#imsTnXb)"><path clip-rule="evenodd" class="u96a8nbjb"/></g><path class="e1l9c4nsl"/><path fill="url(#i4I71qU)" class="u_3a9bc_g"/><path fill="url(#ip2dT4C)" class="pooll-lgq"/><ellipse fill="url(#iqvDsAm)" transform="rotate(22.414 12.799 5.953)" class="adhpxrb6l"/><g filter="url(#iPvfAFp)"><path class="e9_t29bue"/><path fill="url(#igv4lBc)" class="f1u8ijb3m"/><path fill="url(#ixFzlsC)" class="f1u8ijb3m"/><path fill="url(#iZLPaDc)" class="f1u8ijb3m"/><path fill="url(#i8dt67b)" class="f1u8ijb3m"/><path fill="url(#iz53cee)" class="f1u8ijb3m"/></g><path fill="url(#ipSnGqe)" class="vjh3yqznr"/><path fill="url(#iAciTGb)" class="vjh3yqznr"/><path fill="url(#iiDMUtc)" class="vjh3yqznr"/><path fill="url(#iq6Q1Wl)" class="vjh3yqznr"/><path class="ppv4posfy"/><path fill="url(#iYUt5rb)" class="ol51zcmaj"/><path fill="url(#i21JStR)" class="ol51zcmaj"/><path fill="url(#ikduqNe)" class="ol51zcmaj"/><path class="kmd3qcb-j"/><path fill="url(#iiwTGEe)" class="e0lhu47_k"/><path fill="url(#izYIVRu)" class="e0lhu47_k"/><path fill="url(#iRYIdJc)" class="e0lhu47_k"/><path fill="url(#ir7LSIc)" class="e0lhu47_k"/><path fill="url(#idaGKtb)" class="e0lhu47_k"/><g filter="url(#im16WPm)"><path clip-rule="evenodd" class="avosl4bpd"/></g><path fill="url(#i84S0qc)" clip-rule="evenodd" class="yzbfo0edn"/><path fill="url(#ivI1A0b)" clip-rule="evenodd" class="yzbfo0edn"/><path class="npcei-brr"/><path fill="url(#iZ4Xtkb)" class="jmlii5bid"/><path fill="url(#iFj3uCb)" class="jmlii5bid"/><path fill="url(#iePsxCb)" class="jmlii5bid"/><rect fill="url(#ijXMCuq)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><rect fill="url(#iDJCtue)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><path fill="url(#iZKciLc)" class="mqryp-bup"/><path fill="url(#idBd4Ud)" class="vtxj36boz"/><path fill="url(#ikZhW9L)" class="vtxj36boz"/><path fill="url(#iCDjVke)" class="t3ncs1j8m"/><path fill="url(#igfEL3l)" class="t3ncs1j8m"/><g filter="url(#ia5Rxob)"><path fill="url(#iliIEGe)" class="pcwcq6ykk"/></g><path fill="url(#inqL0Pd)" class="pb93aprhh"/><path fill="url(#ipDfQxd)" class="pb93aprhh"/><path fill="url(#iFMDzle)" class="pb93aprhh"/><path fill="url(#iVgiUxb)" class="pb93aprhh"/><path fill="url(#iESVPYb)" class="pb93aprhh"/><g filter="url(#iq1tXEc)"><rect class="kk63hqbts"/></g><defs><radialGradient id="ixKKdrs" cx="0" cy="0" r="1" gradientTransform="matrix(.61864 2.14418 -1.49974 .4327 18.926 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="c4e5_obhh"/><stop offset="1" class="mw5xv5bly"/></radialGradient><radialGradient id="iKx9G5K" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 18.88 22.28)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="el1f73rff"/><stop offset="1" class="iasiczten"/></radialGradient><radialGradient id="ijqVH7d" cx="0" cy="0" r="1" gradientTransform="matrix(.80677 2.5012 -1.15566 .37276 16.338 22.544)" gradientUnits="userSpaceOnUse"><stop class="u_7vzbbil"/><stop offset="1" class="n4e7hibnk"/></radialGradient><radialGradient id="i7Gr6le" cx="0" cy="0" r="1" gradientTransform="rotate(71.565 -6.364 23.576)scale(.54352 3.09962)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="u07rntblp"/><stop offset="1" class="tbt6sb7pf"/></radialGradient><radialGradient id="iXLkHkd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 12.825 19.514)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b-r5tpb7o"/><stop offset="1" class="f8fx77o2h"/></radialGradient><radialGradient id="iHcv93c" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 10.934 8.218)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="smyxvjbxd"/><stop offset="1" class="k24mmwbna"/></radialGradient><radialGradient id="i2glQTb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.114 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="nvd1i1bng"/><stop offset="1" class="gwjk8-8_e"/></radialGradient><radialGradient id="i6AMUmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 16.614 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iyj9pId" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.529 4.431)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="pjqvhnbjs"/><stop offset="1" class="wcx06_c5w"/><stop offset="1" class="ffhvjce4r"/></radialGradient><radialGradient id="iD20xTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 10.926 11.811)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="zvwwfcbef"/><stop offset=".952" class="hiik07xes"/></radialGradient><radialGradient id="itKLaUk" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 10.63 11.764)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="wvbuym-2v"/><stop offset="1" class="w8z0zbc1w"/></radialGradient><radialGradient id="iuXm4Ob" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 14.966 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="c7ppc0bow"/><stop offset=".811" class="yia_fgb_n"/></radialGradient><radialGradient id="iyEjcDb" cx="0" cy="0" r="1" gradientTransform="matrix(.52339 .25772 -.3638 .7388 11.552 7.034)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="hymklqb8k"/><stop offset=".684" class="s2f2c_bct"/></radialGradient><radialGradient id="iYcPnSw" cx="0" cy="0" r="1" gradientTransform="matrix(-.1412 -.3087 .4633 -.21191 12.002 7.358)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="ixQb55q" cx="0" cy="0" r="1" gradientTransform="rotate(-179.031 7.758 2.997)scale(.90989 1.10934)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="ioUctYA" cx="0" cy="0" r="1" gradientTransform="matrix(-.21405 -5.58145 2.1687 -.08317 12.396 7.524)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="iCoLOAd" cx="0" cy="0" r="1" gradientTransform="matrix(.01612 .42029 -.65545 .02514 13.24 6.262)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="i0Nwa1c" cx="0" cy="0" r="1" gradientTransform="matrix(1.63363 -.5278 1.13107 3.50085 12.01 3.851)" gradientUnits="userSpaceOnUse"><stop class="tzf255bgc"/><stop offset="1" class="ctuud_14h"/></radialGradient><radialGradient id="i0h1kQi" cx="0" cy="0" r="1" gradientTransform="matrix(.77304 -.25694 .1254 .3773 15.133 6.021)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="iCB8mXb" cx="0" cy="0" r="1" gradientTransform="matrix(.2918 1.26001 -1.313 .30407 15.155 5.696)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="i4I71qU" cx="0" cy="0" r="1" gradientTransform="matrix(.2942 -.01128 .02192 .5716 12.924 6.304)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ip2dT4C" cx="0" cy="0" r="1" gradientTransform="matrix(.2684 -.0103 .02227 .58085 12.744 6.333)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="igv4lBc" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 8.954 7.552)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="j9k9ec-7q"/><stop offset="1" class="tqhat7z5r"/></radialGradient><radialGradient id="ixFzlsC" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.527 10.23)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="vrrbv9blf"/><stop offset="1" class="zs4p_mbda"/></radialGradient><radialGradient id="i8dt67b" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 16.91 11.233)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="vpqlu-bzk"/><stop offset="1" class="chgiqwu_c"/></radialGradient><radialGradient id="iz53cee" cx="0" cy="0" r="1" gradientTransform="rotate(168.111 7.835 8.235)scale(4.55199 6.32638)" gradientUnits="userSpaceOnUse"><stop offset=".635" class="p1be21okm"/><stop offset=".993" class="my6lpcbbn"/></radialGradient><radialGradient id="iAciTGb" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 6.675 29.938)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iq6Q1Wl" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.423 12.192)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iiwTGEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.124 17.331)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="izYIVRu" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.435 22.802)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iRYIdJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.173 18.126)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="idaGKtb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 13.704 17.342)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="ivI1A0b" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.77 7.069)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="aneywjt_w"/><stop offset="1" class="idx-0ob_q"/></radialGradient><radialGradient id="iFj3uCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03998 -.1057 .17848 1.75613 14.893 10.831)" gradientUnits="userSpaceOnUse"><stop class="ocwrhdbmt"/><stop offset="1" class="v45x_gblz"/></radialGradient><radialGradient id="iePsxCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 19.656 9.918)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="rxuxfhbms"/><stop offset="1" class="w0jybqera"/></radialGradient><radialGradient id="iliIEGe" cx="0" cy="0" r="1" gradientTransform="rotate(-149.027 6.18 5.213)scale(1.15719 1.60341)" gradientUnits="userSpaceOnUse"><stop class="t6ld_bbob"/><stop offset="1" class="zlcet8bnw"/></radialGradient><radialGradient id="inqL0Pd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 11.86 .42)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ipDfQxd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.727 -9.355)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="iFMDzle" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 20.567 4.249)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iVgiUxb" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.05 4.184)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iESVPYb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.727 -3.655)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><linearGradient id="iIZoyQb" x1="11.364" x2="9.677" y1="26.108" y2="26.358" gradientUnits="userSpaceOnUse"><stop class="pw3cm8ghn"/><stop offset="1" class="ebr2vqbrv"/></linearGradient><linearGradient id="iQQzDfd" x1="8.93" x2="9.665" y1="24.418" y2="24.277" gradientUnits="userSpaceOnUse"><stop offset=".237" class="hc9rgac9d"/><stop offset="1" class="ax0qocbyt"/></linearGradient><linearGradient id="i9ztGhb" x1="11.286" x2="10.856" y1="22.709" y2="22.811" gradientUnits="userSpaceOnUse"><stop class="m8_menbco"/><stop offset="1" class="t1w1jyb_t"/></linearGradient><linearGradient id="i0eVsLe" x1="22.817" x2="22.759" y1="24.6" y2="23.377" gradientUnits="userSpaceOnUse"><stop class="altl0jb1l"/><stop offset="1" class="frv3_c41o"/></linearGradient><linearGradient id="ismZuab" x1="22.196" x2="22.196" y1="22.452" y2="23.361" gradientUnits="userSpaceOnUse"><stop class="ucfba_b5g"/><stop offset="1" class="u745z8b-f"/></linearGradient><linearGradient id="iSHdxeb" x1="10.659" x2="10.659" y1="18.631" y2="19.952" gradientUnits="userSpaceOnUse"><stop class="jtac7ua_e"/><stop offset="1" class="p3lmqxq4r"/></linearGradient><linearGradient id="iteAhfU" x1="15.158" x2="12.085" y1="6.938" y2="7.241" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="iTJl7Xd" x1="15.077" x2="15.237" y1="6.097" y2="6.104" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="iqvDsAm" x1="12.722" x2="12.922" y1="5.912" y2="5.977" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iZLPaDc" x1="15.451" x2="15.28" y1="16.799" y2="15.986" gradientUnits="userSpaceOnUse"><stop offset=".185" class="lkg-r5bvc"/><stop offset="1" class="pdj8m471t"/></linearGradient><linearGradient id="ipSnGqe" x1="9.864" x2="11.395" y1="28.921" y2="28.921" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iiDMUtc" x1="9.427" x2="9.427" y1="29.938" y2="29.616" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="iYUt5rb" x1="25.352" x2="25.949" y1="22.069" y2="23.186" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i21JStR" x1="25.602" x2="26.296" y1="25.019" y2="24.152" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="ikduqNe" x1="27.316" x2="26.923" y1="24.153" y2="24.327" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ir7LSIc" x1="13.336" x2="13.786" y1="17.398" y2="18.466" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="i84S0qc" x1="21.364" x2="21.177" y1="11.03" y2="10.092" gradientUnits="userSpaceOnUse"><stop offset=".076" class="moe8lybvx"/><stop offset="1" class="gm-u32b5v"/></linearGradient><linearGradient id="iZ4Xtkb" x1="18.207" x2="17.448" y1="12.178" y2="9.468" gradientUnits="userSpaceOnUse"><stop class="nqy0qlkmp"/><stop offset="1" class="lvqtzth8g"/></linearGradient><linearGradient id="ijXMCuq" x1="25.013" x2="23.016" y1="6.218" y2="6.288" gradientUnits="userSpaceOnUse"><stop offset=".149" class="jjrmc66dk"/><stop offset="1" class="m0_of534w"/></linearGradient><linearGradient id="iDJCtue" x1="24.329" x2="24.328" y1="6.762" y2="6.575" gradientUnits="userSpaceOnUse"><stop class="d1use2f4c"/><stop offset="1" class="iiu2g6sey"/></linearGradient><linearGradient id="iZKciLc" x1="4.243" x2="7.829" y1="11.428" y2="11.436" gradientUnits="userSpaceOnUse"><stop class="d_zsx_qwu"/><stop offset=".588" class="bq8is6bem"/></linearGradient><linearGradient id="idBd4Ud" x1="4.236" x2="6.799" y1="11.876" y2="11.876" gradientUnits="userSpaceOnUse"><stop class="d_zsx_qwu"/><stop offset=".588" class="bq8is6bem"/></linearGradient><linearGradient id="ikZhW9L" x1="5.154" x2="5.154" y1="12.509" y2="12.064" gradientUnits="userSpaceOnUse"><stop class="uy_o1rblt"/><stop offset="1" class="sj9ku07pk"/></linearGradient><linearGradient id="iCDjVke" x1="4.645" x2="6.739" y1="12.46" y2="12.46" gradientUnits="userSpaceOnUse"><stop class="d_zsx_qwu"/><stop offset=".547" class="bq8is6bem"/></linearGradient><linearGradient id="igfEL3l" x1="5.395" x2="5.395" y1="13.092" y2="12.647" gradientUnits="userSpaceOnUse"><stop class="uy_o1rblt"/><stop offset="1" class="sj9ku07pk"/></linearGradient><filter id="iXhBkBb" width="4.141" height="6.811" x="15.901" y="15.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23786"/></filter><filter id="iAARJFb" width="4.814" height="5.748" x="11.847" y="3.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.596078 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23786"/></filter><filter id="iMi9kbd" width="7.468" height="7.772" x="11.374" y="2.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.266667 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23786"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0392157 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23786" result="effect2_innerShadow_3987_23786"/></filter><filter id="imsTnXb" width="1.09" height=".581" x="12.614" y="4.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23786"/></filter><filter id="iPvfAFp" width="5.768" height="8.646" x="12.843" y="9.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.352941 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23786"/></filter><filter id="im16WPm" width="9.915" height="8.775" x="15.493" y="2.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.533333 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23786"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.635294 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23786" result="effect2_innerShadow_3987_23786"/></filter><filter id="ia5Rxob" width="2.43" height="2.868" x="6.814" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.313726 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23786"/></filter><filter id="iq1tXEc" width="2.065" height=".799" x="4.564" y="11.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23786" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-playing-handball-light" /></template>
<style>
.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.adhpxrb6l {
  cx: 12.799px;
  cy: 5.953px;
  rx: 0.069px;
  ry: 0.094px;
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

.avosl4bpd {
  fill: var(--svg-color--e6b6a7, #E6B6A7);
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.323l.809-2.915a1.15 1.15 0 0 1 1.416-.801");
}

.ax0qocbyt {
  stop-color: var(--svg-color--fbc0ae, #FBC0AE);
  stop-opacity: 0;
}

.b-r5tpb7o {
  stop-color: var(--svg-color--8663d2, #8663D2);
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

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.bq8is6bem {
  stop-color: var(--svg-color--e2a493, #E2A493);
}

.c2ukjabcr {
  stop-color: var(--svg-color--4d318d, #4D318D);
}

.c4e5_obhh {
  stop-color: var(--svg-color--9579d9, #9579D9);
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.c7ppc0bow {
  stop-color: var(--svg-color--ce8868, #CE8868);
}

.cdgjtl8nk {
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.317a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.803-8.137-.703c-.512-.376-.471-.93-.095-1.442");
}

.chgiqwu_c {
  stop-color: var(--svg-color--643cae, #643CAE);
  stop-opacity: 0;
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.ctuud_14h {
  stop-color: var(--svg-color--534b49, #534B49);
  stop-opacity: 0;
}

.d_6rbhb8w {
  d: path("M13.976 8.014h2.217v3.3h-2.217z");
}

.d_zsx_qwu {
  stop-color: var(--svg-color--ffc5af, #FFC5AF);
}

.d1use2f4c {
  stop-color: var(--svg-color--764db5, #764DB5);
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxjajos_o {
  stop-color: var(--svg-color--f0b5a2, #F0B5A2);
}

.e0lhu47_k {
  d: path("M18.3 15.613s-4.632 1.787-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.198.278c1.085-.572 2.045-1.031 3.183-1.726c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.492-1.322-.684-1.704");
}

.e1l9c4nsl {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.626 6.339l1.064-.041c-.016-.422-.268-.754-.561-.743s-.519.362-.503.784");
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.e9_t29bue {
  fill: var(--svg-color--745ab0, #745AB0);
  d: path("m15.493 9.4l.674-.168c.233-.059.476-.07.713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.ebr2vqbrv {
  stop-color: var(--svg-color--f8bead, #F8BEAD);
}

.egztfybxz {
  d: path("m15.006 6.967l.155-1.557a.783.783 0 0 1-.155 1.557");
}

.el1f73rff {
  stop-color: var(--svg-color--7b46d0, #7B46D0);
  stop-opacity: 0;
}

.f1u8ijb3m {
  d: path("m15.493 9.4l.674-.168c.233-.059.476-.07.713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.f8fx77o2h {
  stop-color: var(--svg-color--845fcd, #845FCD);
}

.ffhvjce4r {
  stop-color: var(--svg-color--d78c77, #D78C77);
  stop-opacity: 0;
}

.fmy8a7_8n {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.687 5.748c-.147-.136-.383-.16-.482-.154l.345.49c.158-.016.32-.167.136-.336");
}

.frv3_c41o {
  stop-color: var(--svg-color--e0a8a5, #E0A8A5);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
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

.gm-u32b5v {
  stop-color: var(--svg-color--d79f9b, #D79F9B);
  stop-opacity: 0;
}

.gu4uskbqq {
  stop-color: var(--svg-color--fac1a8, #FAC1A8);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwjk8-8_e {
  stop-color: var(--svg-color--9277cc, #9277CC);
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

.hymklqb8k {
  stop-color: var(--svg-color--ffd4b7, #FFD4B7);
}

.i1put7zdc {
  fill: var(--svg-color--e2a493, #E2A493);
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.317a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.803-8.137-.703c-.512-.376-.471-.93-.095-1.442");
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.iasiczten {
  stop-color: var(--svg-color--7b46d0, #7B46D0);
}

.idx-0ob_q {
  stop-color: var(--svg-color--e4b3a0, #E4B3A0);
  stop-opacity: 0;
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.iiu2g6sey {
  stop-color: var(--svg-color--764db5, #764DB5);
  stop-opacity: 0;
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.iyxi2ittv {
  d: path("M11.847 6.551c.162-.164.24-.403.259-.502l.193-.007l.047 1.21c-.226.156-.557.146-.664-.071c-.091-.186-.037-.424.165-.63");
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

.jmlii5bid {
  d: path("m19.732 11.598l-.61-2.962l-3.005.597a1.483 1.483 0 0 0 .55 2.914z");
}

.jtac7ua_e {
  stop-color: var(--svg-color--7b61a3, #7B61A3);
}

.k24mmwbna {
  stop-color: var(--svg-color--7745c0, #7745C0);
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

.lh13n-8uj {
  d: path("M11.864 4.061c-.202-.434-.017-.908.08-1.072c.368-.738 1.185-.817 1.665-.628c.564.223.734.346 1.623.056c.89-.29 2.003-.216 2.623.804s.035 2.217.202 2.85c.168.634.578.681.757 1.415c.166 1.021-.443 1.714-1 1.886c-.558.173-1.724.067-2.138-.86c-.678-1.517-.285-2.262-.45-3.03c-.164-.769-.634-.97-1.469-.77c-.981.237-1.624-.073-1.893-.65");
}

.lkg-r5bvc {
  stop-color: var(--svg-color--705dac, #705DAC);
}

.lv6qs4dqh {
  fill: var(--svg-color--f1bcb0, #F1BCB0);
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.lvqtzth8g {
  stop-color: var(--svg-color--7e55c7, #7E55C7);
  stop-opacity: 0;
}

.m0_of534w {
  stop-color: var(--svg-color--7a59ab, #7A59AB);
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

.moe8lybvx {
  stop-color: var(--svg-color--c0858e, #C0858E);
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

.npcei-brr {
  fill: var(--svg-color--8060b2, #8060B2);
  d: path("m19.732 11.598l-.61-2.962l-3.005.597a1.483 1.483 0 0 0 .55 2.914z");
}

.nqy0qlkmp {
  stop-color: var(--svg-color--6540ac, #6540AC);
}

.nvd1i1bng {
  stop-color: var(--svg-color--9277cc, #9277CC);
  stop-opacity: 0;
}

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
}

.ocwrhdbmt {
  stop-color: var(--svg-color--9276c2, #9276C2);
}

.ol51zcmaj {
  d: path("m25.947 22.035l-1.294.558l.035 1.71c.33.289 1.104 1.066 1.808 1.602c.46.35.894.355 1.192.295c.226-.045.287-.3.188-.509l-1.594-3.539a.25.25 0 0 0-.335-.117");
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
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

.pjqvhnbjs {
  stop-color: var(--svg-color--d78c77, #D78C77);
}

.pooll-lgq {
  d: path("m13.067 6.32l.001-.077c-.008-.199-.098-.357-.202-.353s-.183.168-.175.368l.007.077z");
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

.q8c7r9fut {
  stop-color: var(--svg-color--4a4970, #4A4970);
  stop-opacity: 0;
}

.qh9tdvimg {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
}

.qmcjcvbdo {
  stop-color: var(--svg-color--adaaad, #ADAAAD);
  stop-opacity: 0;
}

.qum9srb-r {
  d: path("m10.2 19.077l1.016-.446l1.61 2.836l-1.563.469v.422l-2.68.258c-.073-.399-.2-1.251.102-2.016c.335-.848 1.148-1.362 1.515-1.523");
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rtlg21b3x {
  d: path("M12.049 5.505c.008-.863.271-1.29.398-1.416l4.016-.154l.198 3.401c-.845 2.319-3.687 2.526-4.144 1.716s-.478-2.547-.468-3.547");
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

.s2f2c_bct {
  stop-color: var(--svg-color--ffc4a7, #FFC4A7);
}

.sew1y7bbn {
  stop-color: var(--svg-color--514d8b, #514D8B);
  stop-opacity: 0;
}

.sfkqlwyif {
  fill: var(--svg-color--241823, #241823);
  d: path("M11.864 4.061c-.202-.434-.017-.908.08-1.072c.368-.738 1.185-.817 1.665-.628c.564.223.734.346 1.623.056c.89-.29 2.003-.216 2.623.804s.035 2.217.202 2.85c.168.634.578.681.757 1.415c.166 1.021-.443 1.714-1 1.886c-.558.173-1.724.067-2.138-.86c-.678-1.517-.285-2.262-.45-3.03c-.164-.769-.634-.97-1.469-.77c-.981.237-1.624-.073-1.893-.65");
}

.sj9ku07pk {
  stop-color: var(--svg-color--e7a79b, #E7A79B);
  stop-opacity: 0;
}

.smyxvjbxd {
  stop-color: var(--svg-color--7745c0, #7745C0);
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
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

.tzf255bgc {
  stop-color: var(--svg-color--534b49, #534B49);
}

.u_3a9bc_g {
  d: path("M13.277 6.314V6.31c-.013-.345-.171-.619-.354-.612s-.319.292-.306.637v.004z");
}

.u_7vzbbil {
  stop-color: var(--svg-color--886ac6, #886AC6);
}

.u07rntblp {
  stop-color: var(--svg-color--6e46c0, #6E46C0);
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.u745z8b-f {
  stop-color: var(--svg-color--e7b8a0, #E7B8A0);
  stop-opacity: 0;
}

.u96a8nbjb {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M13.135 5.207a.8.8 0 0 0-.234-.008a.162.162 0 0 1-.052-.32c.076-.012.2-.013.337.009c.138.022.302.07.447.169a.162.162 0 0 1-.182.267a.8.8 0 0 0-.316-.117");
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

.v45x_gblz {
  stop-color: var(--svg-color--8667c0, #8667C0);
  stop-opacity: 0;
}

.v7fhh3bko {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.475 7.506a.135.135 0 0 1 .005.19c-.247.261-.615.34-.732.357a.135.135 0 1 1-.038-.267c.1-.014.392-.082.574-.275a.135.135 0 0 1 .19-.005");
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

.zvwwfcbef {
  stop-color: var(--svg-color--db988d, #DB988D);
  stop-opacity: 0;
}

</style>
