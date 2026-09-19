<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iPWvvdb)" class="q12x_3brx"/><path fill="url(#icFzNfo)" class="q12x_3brx"/><path fill="url(#iJS711c)" class="q12x_3brx"/><path class="krklkuugk"/><path fill="url(#imMcKNe)" class="zguchrbop"/><path fill="url(#isk84zh)" class="zguchrbop"/><path class="mr8h2bixv"/><path fill="url(#ixKKdrs)" class="g9d0ovbvp"/><path fill="url(#iKx9G5K)" class="g9d0ovbvp"/><path fill="url(#ijqVH7d)" class="g9d0ovbvp"/><path fill="url(#i7Gr6le)" class="g9d0ovbvp"/><path fill="url(#iXLkHkd)" class="qum9srb-r"/><path fill="url(#iHcv93c)" class="qum9srb-r"/><path fill="url(#i2glQTb)" class="qum9srb-r"/><path fill="url(#iSHdxeb)" class="qum9srb-r"/><g filter="url(#imm3eNc)"><path class="amd51vbjg"/><path fill="url(#i6AMUmc)" class="mfs1vbcha"/></g><path clip-rule="evenodd" class="q6syztocs"/><path fill="url(#in4dTWc)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#iYDw95c)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#i1od3rF)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#ixTYwrG)" transform="rotate(-23.31 13.976 8.014)" class="d_6rbhb8w"/><path fill="url(#ihKbXyb)" class="oy9qa8bxd"/><g filter="url(#im36Mtd)"><path fill="url(#ic6lpib)" class="u8zsuqbeq"/><path fill="url(#ikoJCOd)" class="u8zsuqbeq"/><path fill="url(#iwL3Due)" class="u8zsuqbeq"/><path fill="url(#iWB5nUc)" class="u8zsuqbeq"/></g><g filter="url(#igxF8Pd)"><path class="gltafjbxo"/><path fill="url(#iaXd5rc)" class="gu22ddcml"/></g><path fill="url(#iwLiZTb)" class="a0xgwiu5k"/><path fill="url(#iaCxCKd)" class="a0xgwiu5k"/><path fill="url(#itmqtMb)" class="a0xgwiu5k"/><path class="mx1qpr89o"/><path clip-rule="evenodd" class="bnmo08j6o"/><g filter="url(#iAfMmpd)"><path clip-rule="evenodd" class="pvtrczb-c"/></g><path class="rhof17bxr"/><path fill="url(#ikwkANe)" class="sthl0ob7j"/><path fill="url(#in8rtLd)" class="o9sywlb7f"/><ellipse fill="url(#ifIFlBc)" transform="rotate(21.837 12.792 5.994)" class="w-02ybczb"/><g filter="url(#iQPdKae)"><path class="e9_t29bue"/><path fill="url(#igv4lBc)" class="f1u8ijb3m"/><path fill="url(#ixFzlsC)" class="f1u8ijb3m"/><path fill="url(#iZLPaDc)" class="f1u8ijb3m"/><path fill="url(#i8dt67b)" class="f1u8ijb3m"/><path fill="url(#iz53cee)" class="f1u8ijb3m"/></g><path fill="url(#ipSnGqe)" class="vjh3yqznr"/><path fill="url(#iAciTGb)" class="vjh3yqznr"/><path fill="url(#iiDMUtc)" class="vjh3yqznr"/><path fill="url(#iq6Q1Wl)" class="vjh3yqznr"/><path class="ppv4posfy"/><path fill="url(#iYUt5rb)" class="ol51zcmaj"/><path fill="url(#i21JStR)" class="ol51zcmaj"/><path fill="url(#ikduqNe)" class="ol51zcmaj"/><path class="kmd3qcb-j"/><path fill="url(#iiwTGEe)" class="e0lhu47_k"/><path fill="url(#izYIVRu)" class="e0lhu47_k"/><path fill="url(#iRYIdJc)" class="e0lhu47_k"/><path fill="url(#ir7LSIc)" class="e0lhu47_k"/><path fill="url(#idaGKtb)" class="e0lhu47_k"/><g filter="url(#iBO1Mte)"><path clip-rule="evenodd" class="b54auy2xo"/></g><path fill="url(#iPsA89P)" clip-rule="evenodd" class="yzbfo0edn"/><path fill="url(#ij0A9jb)" clip-rule="evenodd" class="yzbfo0edn"/><path class="npcei-brr"/><path fill="url(#iZ4Xtkb)" class="jmlii5bid"/><path fill="url(#iFj3uCb)" class="jmlii5bid"/><path fill="url(#iePsxCb)" class="jmlii5bid"/><rect fill="url(#ijXMCuq)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><rect fill="url(#iDJCtue)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><path fill="url(#iu0hCqd)" class="mqryp-bup"/><path fill="url(#im1dzpd)" class="vtxj36boz"/><path fill="url(#im87iHe)" class="vtxj36boz"/><path fill="url(#iHIYK6c)" class="t3ncs1j8m"/><path fill="url(#iVikgyI)" class="t3ncs1j8m"/><g filter="url(#in4Jiwd)"><path fill="url(#iliIEGe)" class="pcwcq6ykk"/></g><path fill="url(#inqL0Pd)" class="pb93aprhh"/><path fill="url(#ipDfQxd)" class="pb93aprhh"/><path fill="url(#iFMDzle)" class="pb93aprhh"/><path fill="url(#iVgiUxb)" class="pb93aprhh"/><path fill="url(#iESVPYb)" class="pb93aprhh"/><g filter="url(#iUCA3bd)"><rect class="ef_m18fqw"/></g><g filter="url(#izQ9aWb)"><rect class="jygemf0dw"/></g><defs><radialGradient id="ixKKdrs" cx="0" cy="0" r="1" gradientTransform="matrix(.61864 2.14418 -1.49974 .4327 18.926 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="c4e5_obhh"/><stop offset="1" class="mw5xv5bly"/></radialGradient><radialGradient id="iKx9G5K" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 18.88 22.28)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="el1f73rff"/><stop offset="1" class="iasiczten"/></radialGradient><radialGradient id="ijqVH7d" cx="0" cy="0" r="1" gradientTransform="matrix(.80677 2.5012 -1.15566 .37276 16.338 22.544)" gradientUnits="userSpaceOnUse"><stop class="u_7vzbbil"/><stop offset="1" class="n4e7hibnk"/></radialGradient><radialGradient id="i7Gr6le" cx="0" cy="0" r="1" gradientTransform="rotate(71.565 -6.364 23.576)scale(.54352 3.09962)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="u07rntblp"/><stop offset="1" class="tbt6sb7pf"/></radialGradient><radialGradient id="iXLkHkd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 12.825 19.514)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b-r5tpb7o"/><stop offset="1" class="f8fx77o2h"/></radialGradient><radialGradient id="iHcv93c" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 10.934 8.218)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="smyxvjbxd"/><stop offset="1" class="k24mmwbna"/></radialGradient><radialGradient id="i2glQTb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.114 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="nvd1i1bng"/><stop offset="1" class="gwjk8-8_e"/></radialGradient><radialGradient id="i6AMUmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 16.614 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="in4dTWc" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.529 4.43)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="hllbrjbqi"/><stop offset="1" class="y8lqf67-a"/></radialGradient><radialGradient id="iYDw95c" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 10.926 11.811)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="mdfnq_gtj"/><stop offset=".952" class="bw4ryrbal"/></radialGradient><radialGradient id="i1od3rF" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 10.63 11.764)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="l011be-du"/><stop offset="1" class="widna0pfy"/></radialGradient><radialGradient id="ixTYwrG" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 14.966 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="o89cy-q7m"/><stop offset=".75" class="kw93z0bba"/></radialGradient><radialGradient id="ihKbXyb" cx="0" cy="0" r="1" gradientTransform="rotate(25.64 -9.78 28.946)scale(.58078 .81979)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="n304-r4kd"/><stop offset=".684" class="uk3jx7nau"/></radialGradient><radialGradient id="ikoJCOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.90577 -.00643 .00784 -1.10432 15.447 6.14)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="jijo4-b9s"/><stop offset="1" class="ni_rkbnps"/></radialGradient><radialGradient id="iwL3Due" cx="0" cy="0" r="1" gradientTransform="matrix(-.26902 -5.55389 1.50557 -.07293 12.407 7.562)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="dd9hd6bwg"/><stop offset="1" class="aw2d6h33n"/></radialGradient><radialGradient id="iWB5nUc" cx="0" cy="0" r="1" gradientTransform="matrix(.02026 .41821 -.65222 .0316 13.235 6.297)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="jynvl5b3k"/><stop offset="1" class="b-jom1b0d"/></radialGradient><radialGradient id="iaXd5rc" cx="0" cy="0" r="1" gradientTransform="matrix(1.6209 -.54177 1.16102 3.47358 11.986 3.909)" gradientUnits="userSpaceOnUse"><stop class="y_bf1qbke"/><stop offset="1" class="e8kph3xgf"/></radialGradient><radialGradient id="iwLiZTb" cx="0" cy="0" r="1" gradientTransform="rotate(-18.963 25.638 -42.24)scale(.81095 .39581)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="iaCxCKd" cx="0" cy="0" r="1" gradientTransform="rotate(76.384 3.935 12.477)scale(1.28754 1.34167)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="ikwkANe" cx="0" cy="0" r="1" gradientTransform="matrix(.29242 -.01416 .02752 .56813 12.92 6.341)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="in8rtLd" cx="0" cy="0" r="1" gradientTransform="rotate(-2.773 138 -260.012)scale(.26709 .578)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="igv4lBc" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 8.954 7.552)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="j9k9ec-7q"/><stop offset="1" class="tqhat7z5r"/></radialGradient><radialGradient id="ixFzlsC" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.527 10.23)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="vrrbv9blf"/><stop offset="1" class="zs4p_mbda"/></radialGradient><radialGradient id="i8dt67b" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 16.91 11.233)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="vpqlu-bzk"/><stop offset="1" class="chgiqwu_c"/></radialGradient><radialGradient id="iz53cee" cx="0" cy="0" r="1" gradientTransform="rotate(168.111 7.835 8.235)scale(4.55199 6.32638)" gradientUnits="userSpaceOnUse"><stop offset=".635" class="p1be21okm"/><stop offset=".993" class="my6lpcbbn"/></radialGradient><radialGradient id="iAciTGb" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 6.675 29.938)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iq6Q1Wl" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.423 12.192)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iiwTGEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.124 17.331)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="izYIVRu" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.435 22.802)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iRYIdJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.173 18.126)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="idaGKtb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 13.704 17.342)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="ij0A9jb" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.77 7.069)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="use5i75_z"/><stop offset="1" class="fl3j6mbvj"/></radialGradient><radialGradient id="iFj3uCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03998 -.1057 .17848 1.75613 14.893 10.831)" gradientUnits="userSpaceOnUse"><stop class="ocwrhdbmt"/><stop offset="1" class="v45x_gblz"/></radialGradient><radialGradient id="iePsxCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 19.656 9.918)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="rxuxfhbms"/><stop offset="1" class="w0jybqera"/></radialGradient><radialGradient id="iu0hCqd" cx="0" cy="0" r="1" gradientTransform="matrix(3.40685 0 0 1.20429 4.423 11.436)" gradientUnits="userSpaceOnUse"><stop class="rghujac2y"/><stop offset=".498" class="rsj257spn"/></radialGradient><radialGradient id="im1dzpd" cx="0" cy="0" r="1" gradientTransform="matrix(2.92344 0 0 10.9376 3.876 11.876)" gradientUnits="userSpaceOnUse"><stop class="rghujac2y"/><stop offset=".671" class="qrwwtp3cf"/></radialGradient><radialGradient id="iliIEGe" cx="0" cy="0" r="1" gradientTransform="rotate(-149.027 6.18 5.213)scale(1.15719 1.60341)" gradientUnits="userSpaceOnUse"><stop class="t6ld_bbob"/><stop offset="1" class="zlcet8bnw"/></radialGradient><radialGradient id="inqL0Pd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 11.86 .42)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ipDfQxd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.727 -9.355)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="iFMDzle" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 20.567 4.249)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iVgiUxb" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.05 4.184)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iESVPYb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.727 -3.655)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><linearGradient id="iPWvvdb" x1="11.364" x2="9.677" y1="26.108" y2="26.358" gradientUnits="userSpaceOnUse"><stop class="q4_mrj_zj"/><stop offset="1" class="afmf_bb8r"/></linearGradient><linearGradient id="icFzNfo" x1="8.817" x2="9.536" y1="24.42" y2="24.358" gradientUnits="userSpaceOnUse"><stop class="u3lolvdoh"/><stop offset="1" class="daujsygaa"/></linearGradient><linearGradient id="iJS711c" x1="11.286" x2="10.856" y1="22.709" y2="22.811" gradientUnits="userSpaceOnUse"><stop class="x3ycg2l0r"/><stop offset="1" class="bgzosm0kb"/></linearGradient><linearGradient id="imMcKNe" x1="22.817" x2="22.759" y1="24.6" y2="23.377" gradientUnits="userSpaceOnUse"><stop class="qrr4uxb4z"/><stop offset="1" class="s8mikn8pw"/></linearGradient><linearGradient id="isk84zh" x1="22.196" x2="22.196" y1="22.452" y2="23.361" gradientUnits="userSpaceOnUse"><stop class="pwx7w1tsv"/><stop offset="1" class="usmw8dbrh"/></linearGradient><linearGradient id="iSHdxeb" x1="10.659" x2="10.659" y1="18.631" y2="19.952" gradientUnits="userSpaceOnUse"><stop class="jtac7ua_e"/><stop offset="1" class="p3lmqxq4r"/></linearGradient><linearGradient id="ic6lpib" x1="15.15" x2="12.095" y1="6.951" y2="7.283" gradientUnits="userSpaceOnUse"><stop class="co18c5bwy"/><stop offset="1" class="kj_uw-bok"/></linearGradient><linearGradient id="itmqtMb" x1="15.01" x2="15.315" y1="6.082" y2="6.151" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="ifIFlBc" x1="12.716" x2="12.915" y1="5.953" y2="6.018" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iZLPaDc" x1="15.451" x2="15.28" y1="16.799" y2="15.986" gradientUnits="userSpaceOnUse"><stop offset=".185" class="lkg-r5bvc"/><stop offset="1" class="pdj8m471t"/></linearGradient><linearGradient id="ipSnGqe" x1="9.864" x2="11.395" y1="28.921" y2="28.921" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iiDMUtc" x1="9.427" x2="9.427" y1="29.938" y2="29.616" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="iYUt5rb" x1="25.352" x2="25.949" y1="22.069" y2="23.186" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i21JStR" x1="25.602" x2="26.296" y1="25.019" y2="24.152" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="ikduqNe" x1="27.316" x2="26.923" y1="24.153" y2="24.327" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ir7LSIc" x1="13.336" x2="13.786" y1="17.398" y2="18.466" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="iPsA89P" x1="21.364" x2="21.177" y1="11.03" y2="10.092" gradientUnits="userSpaceOnUse"><stop offset=".076" class="u-andmsxm"/><stop offset="1" class="zo4dljfdh"/></linearGradient><linearGradient id="iZ4Xtkb" x1="18.207" x2="17.448" y1="12.178" y2="9.468" gradientUnits="userSpaceOnUse"><stop class="nqy0qlkmp"/><stop offset="1" class="lvqtzth8g"/></linearGradient><linearGradient id="ijXMCuq" x1="25.013" x2="23.016" y1="6.218" y2="6.288" gradientUnits="userSpaceOnUse"><stop offset=".149" class="jjrmc66dk"/><stop offset="1" class="m0_of534w"/></linearGradient><linearGradient id="iDJCtue" x1="24.329" x2="24.328" y1="6.762" y2="6.575" gradientUnits="userSpaceOnUse"><stop class="d1use2f4c"/><stop offset="1" class="iiu2g6sey"/></linearGradient><linearGradient id="im87iHe" x1="5.154" x2="5.154" y1="12.509" y2="12.064" gradientUnits="userSpaceOnUse"><stop class="ks316abal"/><stop offset="1" class="yc0zi2bvg"/></linearGradient><linearGradient id="iHIYK6c" x1="4.645" x2="6.739" y1="12.46" y2="12.46" gradientUnits="userSpaceOnUse"><stop class="rghujac2y"/><stop offset=".588" class="b49rzbb9k"/></linearGradient><linearGradient id="iVikgyI" x1="5.395" x2="5.395" y1="13.092" y2="12.647" gradientUnits="userSpaceOnUse"><stop class="ks316abal"/><stop offset="1" class="yc0zi2bvg"/></linearGradient><filter id="imm3eNc" width="4.141" height="6.811" x="15.901" y="15.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23777"/></filter><filter id="im36Mtd" width="4.809" height="5.751" x="11.841" y="3.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23777"/></filter><filter id="igxF8Pd" width="7.478" height="7.728" x="11.348" y="2.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23777"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0588235 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23777" result="effect2_innerShadow_3987_23777"/></filter><filter id="iAfMmpd" width="1.087" height=".574" x="12.598" y="4.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23777"/></filter><filter id="iQPdKae" width="5.768" height="8.646" x="12.843" y="9.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.352941 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23777"/></filter><filter id="iBO1Mte" width="9.915" height="8.775" x="15.493" y="2.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.266667 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23777"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.313726 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23777" result="effect2_innerShadow_3987_23777"/></filter><filter id="in4Jiwd" width="2.43" height="2.868" x="6.814" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.313726 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23777"/></filter><filter id="iUCA3bd" width="2.065" height=".799" x="4.564" y="11.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23777" stdDeviation=".15"/></filter><filter id="izQ9aWb" width="2.506" height=".866" x="4.08" y="11.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23777" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-playing-handball-medium-dark" /></template>
<style>
.a0xgwiu5k {
  d: path("M15.098 6.983c-.054.002-.094-.045-.09-.099l.122-1.353c.005-.056.054-.097.108-.084a.78.78 0 0 1-.14 1.536");
}

.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.afmf_bb8r {
  stop-color: var(--svg-color--8a5a5a, #8A5A5A);
}

.amd51vbjg {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M16.55 22.745s-.464-1.232-.64-2.275c-.176-1.044 2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.982-3.133 1.16");
}

.aw2d6h33n {
  stop-color: var(--svg-color--9a7468, #9A7468);
  stop-opacity: 0;
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.b-jom1b0d {
  stop-color: var(--svg-color--845a4e, #845A4E);
  stop-opacity: 0;
}

.b-r5tpb7o {
  stop-color: var(--svg-color--8663d2, #8663D2);
}

.b49rzbb9k {
  stop-color: var(--svg-color--795050, #795050);
}

.b54auy2xo {
  fill: var(--svg-color--825c55, #825C55);
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.323l.809-2.915a1.15 1.15 0 0 1 1.416-.801");
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

.bgzosm0kb {
  stop-color: var(--svg-color--8b615e, #8B615E);
  stop-opacity: 0;
}

.bnmo08j6o {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.48 7.533c.054.05.058.135.007.19c-.242.262-.608.344-.725.362a.134.134 0 1 1-.04-.265c.1-.016.39-.086.569-.28a.134.134 0 0 1 .189-.007");
}

.bw4ryrbal {
  stop-color: var(--svg-color--7e4765, #7E4765);
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
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

.chgiqwu_c {
  stop-color: var(--svg-color--643cae, #643CAE);
  stop-opacity: 0;
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.co18c5bwy {
  stop-color: var(--svg-color--825756, #825756);
}

.d_6rbhb8w {
  d: path("M13.976 8.014h2.217v3.3h-2.217z");
}

.d1use2f4c {
  stop-color: var(--svg-color--764db5, #764DB5);
}

.daujsygaa {
  stop-color: var(--svg-color--936762, #936762);
  stop-opacity: 0;
}

.dd9hd6bwg {
  stop-color: var(--svg-color--9d726c, #9D726C);
}

.e0lhu47_k {
  d: path("M18.3 15.613s-4.632 1.787-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.198.278c1.085-.572 2.045-1.031 3.183-1.726c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.492-1.322-.684-1.704");
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.e8kph3xgf {
  stop-color: var(--svg-color--4b3e3e, #4B3E3E);
  stop-opacity: 0;
}

.e9_t29bue {
  fill: var(--svg-color--745ab0, #745AB0);
  d: path("m15.493 9.4l.674-.168c.233-.059.476-.07.713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.ef_m18fqw {
  width: 1.465px;
  height: 0.199px;
  x: 4.864px;
  y: 12.272px;
  fill: var(--svg-color--89635e, #89635E);
  rx: 0.099px;
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

.fl3j6mbvj {
  stop-color: var(--svg-color--825d52, #825D52);
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

.gltafjbxo {
  fill: var(--svg-color--2e1928, #2E1928);
  d: path("M11.843 4.12c-.205-.43-.026-.904.07-1.068c.358-.738 1.17-.825 1.65-.642c.563.216.734.337 1.615.04c.884-.3 1.993-.235 2.62.774c.628 1.009.057 2.206.23 2.835s.582.672.768 1.4c.175 1.015-.425 1.71-.978 1.888s-1.715.083-2.136-.835c-.69-1.503-.307-2.25-.478-3.012c-.171-.763-.642-.958-1.47-.75c-.975.244-1.618-.057-1.891-.63");
}

.gu22ddcml {
  d: path("M11.843 4.12c-.205-.43-.026-.904.07-1.068c.358-.738 1.17-.825 1.65-.642c.563.216.734.337 1.615.04c.884-.3 1.993-.235 2.62.774c.628 1.009.057 2.206.23 2.835s.582.672.768 1.4c.175 1.015-.425 1.71-.978 1.888s-1.715.083-2.136-.835c-.69-1.503-.307-2.25-.478-3.012c-.171-.763-.642-.958-1.47-.75c-.975.244-1.618-.057-1.891-.63");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwjk8-8_e {
  stop-color: var(--svg-color--9277cc, #9277CC);
}

.hllbrjbqi {
  stop-color: var(--svg-color--713839, #713839);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.iasiczten {
  stop-color: var(--svg-color--7b46d0, #7B46D0);
}

.iiu2g6sey {
  stop-color: var(--svg-color--764db5, #764DB5);
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

.jijo4-b9s {
  stop-color: var(--svg-color--794b40, #794B40);
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

.jygemf0dw {
  width: 1.906px;
  height: 0.266px;
  x: 4.38px;
  y: 11.674px;
  fill: var(--svg-color--89635e, #89635E);
  rx: 0.133px;
}

.jynvl5b3k {
  stop-color: var(--svg-color--845a4e, #845A4E);
}

.k24mmwbna {
  stop-color: var(--svg-color--7745c0, #7745C0);
  stop-opacity: 0;
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.kj_uw-bok {
  stop-color: var(--svg-color--875d51, #875D51);
}

.kmd3qcb-j {
  fill: var(--svg-color--918996, #918996);
  d: path("M18.3 15.613s-4.632 1.787-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.198.278c1.085-.572 2.045-1.031 3.183-1.726c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.492-1.322-.684-1.704");
}

.krklkuugk {
  fill: var(--svg-color--8e6863, #8E6863);
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.ks316abal {
  stop-color: var(--svg-color--824c5c, #824C5C);
}

.kw93z0bba {
  stop-color: var(--svg-color--7c645a, #7C645A);
}

.l011be-du {
  stop-color: var(--svg-color--704b3e, #704B3E);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lkg-r5bvc {
  stop-color: var(--svg-color--705dac, #705DAC);
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

.mdfnq_gtj {
  stop-color: var(--svg-color--7b4850, #7B4850);
  stop-opacity: 0;
}

.mfs1vbcha {
  d: path("M16.55 22.745s-.464-1.232-.64-2.275c-.176-1.044 2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.982-3.133 1.16");
}

.mge9r1s9g {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
  stop-opacity: 0;
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
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

.mx1qpr89o {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.673 5.78c-.147-.134-.381-.154-.48-.148l.348.483c.157-.016.316-.168.132-.335");
}

.my6lpcbbn {
  stop-color: var(--svg-color--8f76bd, #8F76BD);
}

.n304-r4kd {
  stop-color: var(--svg-color--9e746b, #9E746B);
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

.ni_rkbnps {
  stop-color: var(--svg-color--794b40, #794B40);
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

.o89cy-q7m {
  stop-color: var(--svg-color--60372d, #60372D);
}

.o9sywlb7f {
  d: path("M13.062 6.357v-.078c-.009-.198-.1-.354-.204-.35c-.104.006-.18.17-.17.368l.008.077z");
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

.oy9qa8bxd {
  d: path("M11.851 6.6a1.07 1.07 0 0 0 .252-.504l.193-.009l.058 1.205c-.223.157-.553.15-.661-.065c-.093-.184-.041-.421.158-.628");
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

.ppv4posfy {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m25.947 22.035l-1.294.558l.035 1.71c.33.289 1.104 1.066 1.808 1.602c.46.35.894.355 1.192.295c.226-.045.287-.3.188-.509l-1.594-3.539a.25.25 0 0 0-.335-.117");
}

.pvtrczb-c {
  fill: var(--svg-color--403235, #403235);
  fill-rule: evenodd;
  d: path("M13.12 5.247a.8.8 0 0 0-.233-.005a.16.16 0 1 1-.055-.317c.075-.013.2-.016.336.004c.137.02.3.068.446.164a.16.16 0 1 1-.179.268a.8.8 0 0 0-.315-.114");
}

.pwx7w1tsv {
  stop-color: var(--svg-color--865f52, #865F52);
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.q12x_3brx {
  d: path("m9.614 27.725l-1-5.18l2.57-.476v6.36z");
}

.q1yj_xkrc {
  stop-color: var(--svg-color--504b8a, #504B8A);
}

.q4_mrj_zj {
  stop-color: var(--svg-color--8e635c, #8E635C);
}

.q6syztocs {
  fill: var(--svg-color--79504f, #79504F);
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.804-8.137-.703c-.512-.375-.471-.93-.095-1.441");
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

.qrr4uxb4z {
  stop-color: var(--svg-color--7e446d, #7E446D);
}

.qrwwtp3cf {
  stop-color: var(--svg-color--78504c, #78504C);
}

.qum9srb-r {
  d: path("m10.2 19.077l1.016-.446l1.61 2.836l-1.563.469v.422l-2.68.258c-.073-.399-.2-1.251.102-2.016c.335-.848 1.148-1.362 1.515-1.523");
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.rghujac2y {
  stop-color: var(--svg-color--977269, #977269);
}

.rhof17bxr {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.624 6.38l1.058-.052c-.02-.42-.273-.748-.565-.734c-.293.015-.513.366-.493.785");
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.rsj257spn {
  stop-color: var(--svg-color--774f4b, #774F4B);
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

.s8mikn8pw {
  stop-color: var(--svg-color--85575e, #85575E);
  stop-opacity: 0;
}

.sew1y7bbn {
  stop-color: var(--svg-color--514d8b, #514D8B);
  stop-opacity: 0;
}

.smyxvjbxd {
  stop-color: var(--svg-color--7745c0, #7745C0);
}

.sp0u-8bbb {
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.804-8.137-.703c-.512-.375-.471-.93-.095-1.441");
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.sthl0ob7j {
  d: path("M13.272 6.347v-.004c-.017-.343-.177-.613-.358-.604c-.181.008-.315.293-.298.636v.004z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
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

.u_7vzbbil {
  stop-color: var(--svg-color--886ac6, #886AC6);
}

.u-andmsxm {
  stop-color: var(--svg-color--7b4565, #7B4565);
}

.u07rntblp {
  stop-color: var(--svg-color--6e46c0, #6E46C0);
}

.u3lolvdoh {
  stop-color: var(--svg-color--a37970, #A37970);
}

.u8zsuqbeq {
  d: path("M12.041 5.556c0-.86.258-1.287.383-1.414l3.995-.194l.231 3.384c-.817 2.317-3.644 2.551-4.107 1.75s-.502-2.53-.502-3.526");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uk3jx7nau {
  stop-color: var(--svg-color--8a5752, #8A5752);
}

.use5i75_z {
  stop-color: var(--svg-color--917063, #917063);
}

.usmw8dbrh {
  stop-color: var(--svg-color--865f52, #865F52);
  stop-opacity: 0;
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

.vjh3yqznr {
  d: path("m7.403 28.647l2.214-1.071l1.575.751l-.014 1.34a.253.253 0 0 1-.252.249l-3.854.022c-.221.002-.418-.15-.395-.369c.046-.453.333-.737.726-.922");
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

.w-02ybczb {
  cx: 12.792px;
  cy: 5.994px;
  rx: 0.069px;
  ry: 0.094px;
}

.w0jybqera {
  stop-color: var(--svg-color--8264b7, #8264B7);
  stop-opacity: 0;
}

.widna0pfy {
  stop-color: var(--svg-color--704b3e, #704B3E);
  stop-opacity: 0;
}

.x3ycg2l0r {
  stop-color: var(--svg-color--815350, #815350);
}

.y_bf1qbke {
  stop-color: var(--svg-color--4b3e3e, #4B3E3E);
}

.y8lqf67-a {
  stop-color: var(--svg-color--713839, #713839);
  stop-opacity: 0;
}

.yc0zi2bvg {
  stop-color: var(--svg-color--824c5c, #824C5C);
  stop-opacity: 0;
}

.ycb1huo4n {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
}

.yzbfo0edn {
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.323l.809-2.915a1.15 1.15 0 0 1 1.416-.801");
}

.zguchrbop {
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.zlcet8bnw {
  stop-color: var(--svg-color--6944a2, #6944A2);
}

.zo4dljfdh {
  stop-color: var(--svg-color--7b4565, #7B4565);
  stop-opacity: 0;
}

.zs4p_mbda {
  stop-color: var(--svg-color--745fa7, #745FA7);
  stop-opacity: 0;
}

</style>
