<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3LuAfb)" class="q12x_3brx"/><path fill="url(#iChOtcd)" class="q12x_3brx"/><path fill="url(#iWzqRxc)" class="q12x_3brx"/><path class="p182m5gpu"/><path fill="url(#iBWvSab)" class="r1iwhz8cc"/><path fill="url(#iptWF8E)" class="r1iwhz8cc"/><path class="k267p2izc"/><path fill="url(#ixKKdrs)" class="yao5ppb3n"/><path fill="url(#iKx9G5K)" class="yao5ppb3n"/><path fill="url(#ijqVH7d)" class="yao5ppb3n"/><path fill="url(#i7Gr6le)" class="yao5ppb3n"/><path fill="url(#iXLkHkd)" class="nq_abtman"/><path fill="url(#iHcv93c)" class="nq_abtman"/><path fill="url(#i2glQTb)" class="nq_abtman"/><path fill="url(#i08Dkub)" class="nq_abtman"/><g filter="url(#iJECNMd)"><path class="j6e1-xb1v"/><path fill="url(#i6AMUmc)" class="ogg8r_g2n"/></g><path clip-rule="evenodd" class="yxdy29x_q"/><path fill="url(#iCvUGgb)" clip-rule="evenodd" class="wa3g-ebdi"/><path fill="url(#ia4hqwe)" clip-rule="evenodd" class="wa3g-ebdi"/><path fill="url(#ixDvJKb)" clip-rule="evenodd" class="wa3g-ebdi"/><path fill="url(#ii3hw2c)" transform="rotate(-23.31 13.976 8.014)" class="d_6rbhb8w"/><path fill="url(#iFBHXPc)" class="pxp0e27si"/><g filter="url(#iGbRl4s)"><path fill="url(#iTJEbwb)" class="bbyll-b6i"/><path fill="url(#iG6G32b)" class="bbyll-b6i"/></g><g filter="url(#iNalAbd)"><path fill="url(#icOojCe)" class="rzhgzfbbl"/></g><path fill="url(#i2f7GTd)" class="mkr8zacge"/><path clip-rule="evenodd" class="j-zago3gb"/><g filter="url(#iwuob1c)"><path clip-rule="evenodd" class="g5m_1fh4a"/></g><path class="w4336u0em"/><path class="o926lbc_s"/><path fill="url(#iEVqMye)" class="gsw6ksbfa"/><path fill="url(#i8mpwGd)" class="kk33r_9lo"/><ellipse fill="url(#if53dFc)" transform="rotate(23.132 12.409 6.06)" class="tglzw5bgw"/><g filter="url(#izn3rCd)"><path class="e9_t29bue"/><path fill="url(#igv4lBc)" class="f1u8ijb3m"/><path fill="url(#ixFzlsC)" class="f1u8ijb3m"/><path fill="url(#iZLPaDc)" class="f1u8ijb3m"/><path fill="url(#i8dt67b)" class="f1u8ijb3m"/><path fill="url(#iz53cee)" class="f1u8ijb3m"/></g><path fill="url(#ipSnGqe)" class="dcvm_d-jy"/><path fill="url(#iAciTGb)" class="dcvm_d-jy"/><path fill="url(#iiDMUtc)" class="dcvm_d-jy"/><path fill="url(#iq6Q1Wl)" class="dcvm_d-jy"/><path class="ih46ceb1a"/><path fill="url(#im7C13b)" class="zciozgblx"/><path fill="url(#i21JStR)" class="zciozgblx"/><path fill="url(#itc1s5b)" class="zciozgblx"/><path class="kmd3qcb-j"/><path fill="url(#iiwTGEe)" class="e0lhu47_k"/><path fill="url(#izYIVRu)" class="e0lhu47_k"/><path fill="url(#iRYIdJc)" class="e0lhu47_k"/><path fill="url(#ij8yFZR)" class="e0lhu47_k"/><path fill="url(#idaGKtb)" class="e0lhu47_k"/><g filter="url(#ix8YnIb)"><path clip-rule="evenodd" class="zkrl1s-bn"/></g><path fill="url(#ib9rmoc)" clip-rule="evenodd" class="efuw_n2tj"/><path fill="url(#iEEge7d)" clip-rule="evenodd" class="efuw_n2tj"/><path class="pja1wzngm"/><path fill="url(#iZ4Xtkb)" class="kg928wbuf"/><path fill="url(#iFj3uCb)" class="kg928wbuf"/><path fill="url(#iePsxCb)" class="kg928wbuf"/><rect fill="url(#ijXMCuq)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><rect fill="url(#iDJCtue)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><path fill="url(#i5YfPwe)" class="mqryp-bup"/><path fill="url(#ibmT3kd)" class="vtxj36boz"/><path fill="url(#iUt9NIb)" class="vtxj36boz"/><path fill="url(#iUgfGgb)" class="t3ncs1j8m"/><path fill="url(#iVmU5Bc)" class="t3ncs1j8m"/><g filter="url(#ihQ20re)"><path fill="url(#iliIEGe)" class="pcwcq6ykk"/></g><path fill="url(#inqL0Pd)" class="afs2-ebiq"/><path fill="url(#ipDfQxd)" class="afs2-ebiq"/><path fill="url(#iFMDzle)" class="afs2-ebiq"/><path fill="url(#iVgiUxb)" class="afs2-ebiq"/><path fill="url(#iESVPYb)" class="afs2-ebiq"/><g filter="url(#iNCD6Ob)"><rect class="kxruteb2a"/></g><g filter="url(#i3WcdXd)"><rect class="l3_k17b7l"/></g><defs><radialGradient id="ixKKdrs" cx="0" cy="0" r="1" gradientTransform="matrix(.61864 2.14418 -1.49974 .4327 18.926 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="c4e5_obhh"/><stop offset="1" class="mw5xv5bly"/></radialGradient><radialGradient id="iKx9G5K" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 18.88 22.28)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="el1f73rff"/><stop offset="1" class="iasiczten"/></radialGradient><radialGradient id="ijqVH7d" cx="0" cy="0" r="1" gradientTransform="matrix(.80677 2.5012 -1.15566 .37276 16.338 22.544)" gradientUnits="userSpaceOnUse"><stop class="u_7vzbbil"/><stop offset="1" class="n4e7hibnk"/></radialGradient><radialGradient id="i7Gr6le" cx="0" cy="0" r="1" gradientTransform="rotate(71.565 -6.364 23.576)scale(.54352 3.09962)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="u07rntblp"/><stop offset="1" class="tbt6sb7pf"/></radialGradient><radialGradient id="iXLkHkd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 12.825 19.514)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b-r5tpb7o"/><stop offset="1" class="f8fx77o2h"/></radialGradient><radialGradient id="iHcv93c" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 10.934 8.218)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="smyxvjbxd"/><stop offset="1" class="k24mmwbna"/></radialGradient><radialGradient id="i2glQTb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.114 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="nvd1i1bng"/><stop offset="1" class="gwjk8-8_e"/></radialGradient><radialGradient id="i6AMUmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 16.614 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iCvUGgb" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.529 4.43)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="rs48o2blf"/><stop offset="1" class="kt4kpbc4c"/></radialGradient><radialGradient id="ia4hqwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 10.926 11.811)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="l7uszybpq"/><stop offset=".614" class="tga8kggao"/><stop offset=".952" class="ujog_hb2e"/></radialGradient><radialGradient id="ixDvJKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 10.63 11.764)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="p01fglb1l"/><stop offset="1" class="l_kbrikva"/></radialGradient><radialGradient id="ii3hw2c" cx="0" cy="0" r="1" gradientTransform="rotate(137.567 5.693 7.667)scale(1.38819 1.30186)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="wfhj11q5g"/><stop offset=".75" class="wqn0e3bvc"/></radialGradient><radialGradient id="iFBHXPc" cx="0" cy="0" r="1" gradientTransform="matrix(.36252 .66042 -.84108 .4617 11.393 6.83)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="iG6G32b" cx="0" cy="0" r="1" gradientTransform="rotate(-178.302 7.717 2.992)scale(.93393 1.13865)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="icOojCe" cx="0" cy="0" r="1" gradientTransform="rotate(-128.944 11.223 .102)scale(7.62278 6.42327)" gradientUnits="userSpaceOnUse"><stop class="dd76hfqny"/><stop offset=".648" class="h1zvawfkv"/></radialGradient><radialGradient id="i2f7GTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.47379 1.053 -1.71106 -.76988 15.366 6.067)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iEVqMye" cx="0" cy="0" r="1" gradientTransform="matrix(.3018 -.00779 .01513 .58636 12.532 6.42)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i8mpwGd" cx="0" cy="0" r="1" gradientTransform="matrix(.27564 -.00711 .0154 .5965 12.348 6.449)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="igv4lBc" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 8.954 7.552)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="j9k9ec-7q"/><stop offset="1" class="tqhat7z5r"/></radialGradient><radialGradient id="ixFzlsC" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.527 10.23)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="vrrbv9blf"/><stop offset="1" class="zs4p_mbda"/></radialGradient><radialGradient id="i8dt67b" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 16.91 11.233)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="vpqlu-bzk"/><stop offset="1" class="chgiqwu_c"/></radialGradient><radialGradient id="iz53cee" cx="0" cy="0" r="1" gradientTransform="rotate(168.111 7.835 8.235)scale(4.55199 6.32638)" gradientUnits="userSpaceOnUse"><stop offset=".635" class="p1be21okm"/><stop offset=".993" class="my6lpcbbn"/></radialGradient><radialGradient id="iAciTGb" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 6.675 29.938)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iq6Q1Wl" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.423 12.192)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iiwTGEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.124 17.331)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="izYIVRu" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.435 22.802)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iRYIdJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.173 18.126)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="idaGKtb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 13.704 17.342)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="iEEge7d" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.77 7.069)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="m3380hbjq"/><stop offset="1" class="wzizgcbzx"/></radialGradient><radialGradient id="iFj3uCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03998 -.1057 .17848 1.75613 14.893 10.831)" gradientUnits="userSpaceOnUse"><stop class="ocwrhdbmt"/><stop offset="1" class="v45x_gblz"/></radialGradient><radialGradient id="iePsxCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 19.656 9.918)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="rxuxfhbms"/><stop offset="1" class="w0jybqera"/></radialGradient><radialGradient id="iliIEGe" cx="0" cy="0" r="1" gradientTransform="rotate(-149.027 6.18 5.213)scale(1.15719 1.60341)" gradientUnits="userSpaceOnUse"><stop class="t6ld_bbob"/><stop offset="1" class="zlcet8bnw"/></radialGradient><radialGradient id="inqL0Pd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 11.86 .42)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ipDfQxd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.727 -9.355)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="iFMDzle" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 20.567 4.249)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iVgiUxb" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.05 4.184)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iESVPYb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.727 -3.655)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><linearGradient id="i3LuAfb" x1="11.364" x2="9.677" y1="26.108" y2="26.358" gradientUnits="userSpaceOnUse"><stop class="mlwsi7b0o"/><stop offset="1" class="a_09dwbav"/></linearGradient><linearGradient id="iChOtcd" x1="8.817" x2="9.536" y1="24.42" y2="24.358" gradientUnits="userSpaceOnUse"><stop class="bb6w2-xac"/><stop offset="1" class="tr-unjbvn"/></linearGradient><linearGradient id="iWzqRxc" x1="11.286" x2="10.856" y1="22.709" y2="22.811" gradientUnits="userSpaceOnUse"><stop class="cqxnxcb8s"/><stop offset="1" class="w8-xerjiz"/></linearGradient><linearGradient id="iBWvSab" x1="22.817" x2="22.7" y1="24.6" y2="23.623" gradientUnits="userSpaceOnUse"><stop class="lp2i-cd1a"/><stop offset="1" class="mtvp7bo5z"/></linearGradient><linearGradient id="iptWF8E" x1="22.196" x2="22.196" y1="22.451" y2="22.834" gradientUnits="userSpaceOnUse"><stop class="qjijibc8w"/><stop offset="1" class="er4fe2jqk"/><stop offset="1" class="y6so9rbtm"/></linearGradient><linearGradient id="i08Dkub" x1="10.659" x2="10.659" y1="18.631" y2="19.951" gradientUnits="userSpaceOnUse"><stop class="jtac7ua_e"/><stop offset="1" class="p3lmqxq4r"/></linearGradient><linearGradient id="iTJEbwb" x1="15.017" x2="11.859" y1="7.04" y2="7.311" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="if53dFc" x1="12.33" x2="12.536" y1="6.017" y2="6.084" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iZLPaDc" x1="15.451" x2="15.28" y1="16.799" y2="15.986" gradientUnits="userSpaceOnUse"><stop offset=".185" class="lkg-r5bvc"/><stop offset="1" class="pdj8m471t"/></linearGradient><linearGradient id="ipSnGqe" x1="9.864" x2="11.395" y1="28.921" y2="28.921" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iiDMUtc" x1="9.427" x2="9.427" y1="29.938" y2="29.616" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="im7C13b" x1="25.352" x2="25.949" y1="22.068" y2="23.186" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i21JStR" x1="25.602" x2="26.296" y1="25.019" y2="24.152" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="itc1s5b" x1="27.316" x2="26.923" y1="24.152" y2="24.327" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ij8yFZR" x1="13.336" x2="13.786" y1="17.398" y2="18.465" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="ib9rmoc" x1="21.364" x2="21.177" y1="11.03" y2="10.092" gradientUnits="userSpaceOnUse"><stop offset=".076" class="b-mglds6n"/><stop offset="1" class="pdikdebak"/></linearGradient><linearGradient id="iZ4Xtkb" x1="18.207" x2="17.448" y1="12.178" y2="9.468" gradientUnits="userSpaceOnUse"><stop class="nqy0qlkmp"/><stop offset="1" class="lvqtzth8g"/></linearGradient><linearGradient id="ijXMCuq" x1="25.013" x2="23.016" y1="6.218" y2="6.288" gradientUnits="userSpaceOnUse"><stop offset=".149" class="jjrmc66dk"/><stop offset="1" class="m0_of534w"/></linearGradient><linearGradient id="iDJCtue" x1="24.329" x2="24.328" y1="6.762" y2="6.575" gradientUnits="userSpaceOnUse"><stop class="d1use2f4c"/><stop offset="1" class="iiu2g6sey"/></linearGradient><linearGradient id="i5YfPwe" x1="4.942" x2="7.446" y1="11.421" y2="11.421" gradientUnits="userSpaceOnUse"><stop class="c3ji72h7e"/><stop offset=".78" class="f8z2jhb-c"/></linearGradient><linearGradient id="ibmT3kd" x1="4.324" x2="6.471" y1="11.86" y2="11.86" gradientUnits="userSpaceOnUse"><stop class="c3ji72h7e"/><stop offset=".78" class="i4zqqwbcb"/></linearGradient><linearGradient id="iUt9NIb" x1="5.154" x2="5.154" y1="12.509" y2="12.064" gradientUnits="userSpaceOnUse"><stop class="tjo7m0eif"/><stop offset="1" class="rn6fgc7ks"/></linearGradient><linearGradient id="iUgfGgb" x1="4.645" x2="6.739" y1="12.46" y2="12.46" gradientUnits="userSpaceOnUse"><stop class="c3ji72h7e"/><stop offset=".78" class="qtd36y-1r"/></linearGradient><linearGradient id="iVmU5Bc" x1="5.395" x2="5.395" y1="13.092" y2="12.647" gradientUnits="userSpaceOnUse"><stop class="tjo7m0eif"/><stop offset="1" class="rn6fgc7ks"/></linearGradient><filter id="iJECNMd" width="4.141" height="6.811" x="15.901" y="15.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23771"/></filter><filter id="iGbRl4s" width="4.968" height="6.057" x="11.586" y="3.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.592157 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23771"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.411765 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23771" result="effect2_innerShadow_3987_23771"/></filter><filter id="iNalAbd" width="7.601" height="8.01" x="10.987" y="2.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23771"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23771" result="effect2_innerShadow_3987_23771"/></filter><filter id="iwuob1c" width="1.113" height=".601" x="12.233" y="4.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23771"/></filter><filter id="izn3rCd" width="5.768" height="8.646" x="12.843" y="9.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.352941 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23771"/></filter><filter id="ix8YnIb" width="9.915" height="8.775" x="15.493" y="2.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.635294 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23771"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23771" result="effect2_innerShadow_3987_23771"/></filter><filter id="ihQ20re" width="2.43" height="2.867" x="6.814" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.313726 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23771"/></filter><filter id="iNCD6Ob" width="2.065" height=".866" x="4.564" y="11.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23771" stdDeviation=".15"/></filter><filter id="i3WcdXd" width="2.506" height=".866" x="4.08" y="11.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23771" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-playing-handball" /></template>
<style>
.a_09dwbav {
  stop-color: var(--svg-color--ffbe38, #FFBE38);
}

.a8jjc_bge {
  stop-color: var(--svg-color--5f5c95, #5F5C95);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.afs2-ebiq {
  d: path("M24.553 4.124a2.063 2.063 0 1 1-4.125 0a2.063 2.063 0 0 1 4.125 0");
}

.b-mglds6n {
  stop-color: var(--svg-color--ca7743, #CA7743);
}

.b-r5tpb7o {
  stop-color: var(--svg-color--8663d2, #8663D2);
}

.b6kb336ra {
  width: 2.533px;
  height: 1.362px;
  x: 22.49px;
  y: 5.391px;
  rx: 0.2px;
}

.bb6w2-xac {
  stop-color: var(--svg-color--ffcd54, #FFCD54);
}

.bbyll-b6i {
  d: path("M11.844 5.53c.02-.887.296-1.32.427-1.45l4.124-.106l.159 3.494c-.897 2.369-3.816 2.545-4.275 1.708c-.458-.837-.458-2.62-.435-3.647");
}

.bc_6ftbdd {
  stop-color: var(--svg-color--ddd9e2, #DDD9E2);
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.c2ukjabcr {
  stop-color: var(--svg-color--4d318d, #4D318D);
}

.c3ji72h7e {
  stop-color: var(--svg-color--ffc52a, #FFC52A);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
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

.cqxnxcb8s {
  stop-color: var(--svg-color--d39b39, #D39B39);
}

.d_6rbhb8w {
  d: path("M13.976 8.014h2.217v3.3h-2.217z");
}

.d1use2f4c {
  stop-color: var(--svg-color--764db5, #764DB5);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.dcvm_d-jy {
  d: path("m7.403 28.647l2.214-1.071l1.575.751l-.014 1.34a.253.253 0 0 1-.252.249l-3.854.022c-.221.001-.418-.15-.395-.37c.046-.452.333-.736.726-.921");
}

.dd76hfqny {
  stop-color: var(--svg-color--e39318, #E39318);
}

.e0lhu47_k {
  d: path("M18.3 15.613s-4.632 1.787-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.198.278c1.085-.572 2.045-1.031 3.183-1.726c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.492-1.322-.684-1.704");
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

.efuw_n2tj {
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.804.8 1.416l-.809 2.915a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.322l.809-2.916a1.15 1.15 0 0 1 1.416-.801");
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.el1f73rff {
  stop-color: var(--svg-color--7b46d0, #7B46D0);
  stop-opacity: 0;
}

.er4fe2jqk {
  stop-color: var(--svg-color--eab93e, #EAB93E);
  stop-opacity: 0;
}

.f1u8ijb3m {
  d: path("m15.493 9.4l.674-.168c.233-.059.476-.07.713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.f8fx77o2h {
  stop-color: var(--svg-color--845fcd, #845FCD);
}

.f8z2jhb-c {
  stop-color: var(--svg-color--fbac30, #FBAC30);
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.g5m_1fh4a {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M12.764 5.297a1 1 0 0 0-.24-.011a.166.166 0 0 1-.05-.328c.078-.012.206-.012.346.012c.141.025.308.077.456.18a.166.166 0 0 1-.19.271a.8.8 0 0 0-.322-.124");
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gsw6ksbfa {
  d: path("M12.895 6.435V6.43c-.009-.354-.168-.637-.355-.632s-.33.295-.322.649v.004z");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwjk8-8_e {
  stop-color: var(--svg-color--9277cc, #9277CC);
}

.h1zvawfkv {
  stop-color: var(--svg-color--ffac28, #FFAC28);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.i4zqqwbcb {
  stop-color: var(--svg-color--ffad2f, #FFAD2F);
}

.iasiczten {
  stop-color: var(--svg-color--7b46d0, #7B46D0);
}

.ih46ceb1a {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m25.947 22.035l-1.294.557l.035 1.711c.33.289 1.104 1.066 1.808 1.602c.46.35.894.355 1.192.295c.226-.045.287-.3.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.117");
}

.iiu2g6sey {
  stop-color: var(--svg-color--764db5, #764DB5);
  stop-opacity: 0;
}

.j-zago3gb {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M13.081 7.662c.055.053.056.14.004.195c-.257.265-.635.34-.756.356a.138.138 0 0 1-.035-.274c.103-.013.403-.078.592-.274a.14.14 0 0 1 .195-.003");
}

.j23k_cb2p {
  stop-color: var(--svg-color--9c959a, #9C959A);
  stop-opacity: 0;
}

.j2u_3dtev {
  stop-color: var(--svg-color--908582, #908582);
  stop-opacity: 0;
}

.j6e1-xb1v {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M16.55 22.745s-.464-1.231-.64-2.275s2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.983-3.133 1.16");
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

.k24mmwbna {
  stop-color: var(--svg-color--7745c0, #7745C0);
  stop-opacity: 0;
}

.k267p2izc {
  fill: var(--svg-color--7e50d4, #7E50D4);
  d: path("m16.942 23.975l-.398-1.297l2.906-1.383l.203 1.125h.258c.162.9.172 2.14.156 2.649c-.041.013-.301.056-.914.125c-1.412.225-2.062-.719-2.21-1.219");
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.kg928wbuf {
  d: path("m19.732 11.597l-.61-2.96l-3.005.596a1.483 1.483 0 0 0 .55 2.913z");
}

.kk33r_9lo {
  d: path("m12.68 6.44l.002-.08c-.006-.204-.097-.368-.204-.365s-.19.17-.184.375l.006.08z");
}

.kmd3qcb-j {
  fill: var(--svg-color--918996, #918996);
  d: path("M18.3 15.613s-4.632 1.787-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.198.278c1.085-.572 2.045-1.031 3.183-1.726c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.492-1.322-.684-1.704");
}

.kt4kpbc4c {
  stop-color: var(--svg-color--f58d21, #F58D21);
  stop-opacity: 0;
}

.kxruteb2a {
  width: 1.465px;
  height: 0.266px;
  x: 4.864px;
  y: 12.272px;
  fill: var(--svg-color--ffc635, #FFC635);
  rx: 0.133px;
}

.l_kbrikva {
  stop-color: var(--svg-color--dfa634, #DFA634);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l3_k17b7l {
  width: 1.906px;
  height: 0.266px;
  x: 4.38px;
  y: 11.674px;
  fill: var(--svg-color--ffc635, #FFC635);
  rx: 0.133px;
}

.l7uszybpq {
  stop-color: var(--svg-color--f99f2d, #F99F2D);
  stop-opacity: 0;
}

.lasxztb-e {
  stop-color: var(--svg-color--a580be, #A580BE);
}

.lkg-r5bvc {
  stop-color: var(--svg-color--705dac, #705DAC);
}

.lp2i-cd1a {
  stop-color: var(--svg-color--c67656, #C67656);
}

.lvqtzth8g {
  stop-color: var(--svg-color--7e55c7, #7E55C7);
  stop-opacity: 0;
}

.m0_of534w {
  stop-color: var(--svg-color--7a59ab, #7A59AB);
}

.m3380hbjq {
  stop-color: var(--svg-color--ffda3f, #FFDA3F);
}

.m5_tnryam {
  stop-color: var(--svg-color--66638b, #66638B);
  stop-opacity: 0;
}

.mge9r1s9g {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
  stop-opacity: 0;
}

.mkr8zacge {
  d: path("M14.74 7.124c-.055.002-.095-.049-.089-.104l.157-1.395c.006-.055.057-.096.11-.082a.803.803 0 0 1-.177 1.581");
}

.mlwsi7b0o {
  stop-color: var(--svg-color--ffd13d, #FFD13D);
}

.mqryp-bup {
  d: path("M4.624 11.557a.44.44 0 0 1 .44-.44h1.373c.113 0 .54.008.9.147l.109.34l-.403.393h-1.98a.44.44 0 0 1-.44-.44");
}

.mtvp7bo5z {
  stop-color: var(--svg-color--f3a935, #F3A935);
  stop-opacity: 0;
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

.nq_abtman {
  d: path("m10.2 19.077l1.016-.446l1.61 2.836l-1.563.469v.422l-2.68.258c-.073-.399-.2-1.252.102-2.016c.335-.848 1.148-1.362 1.515-1.524");
}

.nqy0qlkmp {
  stop-color: var(--svg-color--6540ac, #6540AC);
}

.nvd1i1bng {
  stop-color: var(--svg-color--9277cc, #9277CC);
  stop-opacity: 0;
}

.o926lbc_s {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.227 6.453l1.092-.029c-.011-.432-.265-.777-.566-.769c-.302.008-.537.365-.526.798");
}

.ocwrhdbmt {
  stop-color: var(--svg-color--9276c2, #9276C2);
}

.ogg8r_g2n {
  d: path("M16.55 22.745s-.464-1.231-.64-2.275s2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.983-3.133 1.16");
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.p01fglb1l {
  stop-color: var(--svg-color--dfa634, #DFA634);
}

.p182m5gpu {
  fill: var(--svg-color--ffc93b, #FFC93B);
  d: path("m24.747 24.295l-4.774.703l-.328-2.547l5.215.149z");
}

.p1be21okm {
  stop-color: var(--svg-color--755bb1, #755BB1);
  stop-opacity: 0;
}

.p3lmqxq4r {
  stop-color: var(--svg-color--7b61a3, #7B61A3);
  stop-opacity: 0;
}

.pcwcq6ykk {
  d: path("M7.828 11.587a.197.197 0 0 1 .257-.09c.244.112.695.325.974.496c.085.052.108.16.061.247l-1.028 1.906a.186.186 0 0 1-.223.091a4 4 0 0 1-.975-.495a.19.19 0 0 1-.057-.247z");
}

.pdikdebak {
  stop-color: var(--svg-color--f8a733, #F8A733);
  stop-opacity: 0;
}

.pdj8m471t {
  stop-color: var(--svg-color--705dac, #705DAC);
  stop-opacity: 0;
}

.pja1wzngm {
  fill: var(--svg-color--8060b2, #8060B2);
  d: path("m19.732 11.597l-.61-2.96l-3.005.596a1.483 1.483 0 0 0 .55 2.913z");
}

.pxp0e27si {
  d: path("M11.575 6.661a1.1 1.1 0 0 0 .271-.512l.199-.005l.032 1.243c-.233.157-.573.142-.68-.082c-.091-.192-.033-.435.178-.644");
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

.qjijibc8w {
  stop-color: var(--svg-color--eab93e, #EAB93E);
}

.qmcjcvbdo {
  stop-color: var(--svg-color--adaaad, #ADAAAD);
  stop-opacity: 0;
}

.qtd36y-1r {
  stop-color: var(--svg-color--feac30, #FEAC30);
}

.r1iwhz8cc {
  d: path("m24.747 24.295l-4.774.703l-.328-2.547l5.215.149z");
}

.rn6fgc7ks {
  stop-color: var(--svg-color--f0a135, #F0A135);
  stop-opacity: 0;
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rs48o2blf {
  stop-color: var(--svg-color--f58d21, #F58D21);
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.rxuxfhbms {
  stop-color: var(--svg-color--967acc, #967ACC);
}

.rzhgzfbbl {
  d: path("M11.474 4.105c-.201-.448-.005-.932.097-1.099c.386-.753 1.226-.823 1.716-.623c.576.236.75.365 1.664.078c.918-.287 2.06-.196 2.683.86c.623 1.054.007 2.275.17 2.927c.164.652.585.706.76 1.462c.156 1.05-.478 1.753-1.052 1.923s-1.77.046-2.183-.911c-.676-1.565-.264-2.325-.422-3.116c-.159-.79-.64-1.003-1.498-.808c-1.01.23-1.667-.096-1.935-.693");
}

.s-7nhybnh {
  stop-color: var(--svg-color--a5a3a3, #A5A3A3);
}

.sew1y7bbn {
  stop-color: var(--svg-color--514d8b, #514D8B);
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

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
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

.tga8kggao {
  stop-color: var(--svg-color--ed9635, #ED9635);
  stop-opacity: 0.236;
}

.tglzw5bgw {
  cx: 12.409px;
  cy: 6.059px;
  rx: 0.071px;
  ry: 0.097px;
}

.tjo7m0eif {
  stop-color: var(--svg-color--d88642, #D88642);
}

.tqhat7z5r {
  stop-color: var(--svg-color--8e7ec2, #8E7EC2);
  stop-opacity: 0;
}

.tr-unjbvn {
  stop-color: var(--svg-color--ffcd54, #FFCD54);
  stop-opacity: 0;
}

.u_7vzbbil {
  stop-color: var(--svg-color--886ac6, #886AC6);
}

.u07rntblp {
  stop-color: var(--svg-color--6e46c0, #6E46C0);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ujog_hb2e {
  stop-color: var(--svg-color--c87a51, #C87A51);
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

.w4336u0em {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.345 5.859c-.149-.142-.39-.168-.492-.164l.348.506c.162-.013.33-.166.144-.342");
}

.w8-xerjiz {
  stop-color: var(--svg-color--ffd23e, #FFD23E);
  stop-opacity: 0;
}

.wa3g-ebdi {
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.804-8.137-.702c-.512-.376-.471-.93-.095-1.442");
}

.wfhj11q5g {
  stop-color: var(--svg-color--7c4609, #7C4609);
}

.wqn0e3bvc {
  stop-color: var(--svg-color--e2ac45, #E2AC45);
}

.wzizgcbzx {
  stop-color: var(--svg-color--ffda3f, #FFDA3F);
  stop-opacity: 0;
}

.y6so9rbtm {
  stop-color: var(--svg-color--ffc93b, #FFC93B);
  stop-opacity: 0;
}

.yao5ppb3n {
  d: path("m16.942 23.975l-.398-1.297l2.906-1.383l.203 1.125h.258c.162.9.172 2.14.156 2.649c-.041.013-.301.056-.914.125c-1.412.225-2.062-.719-2.21-1.219");
}

.ycb1huo4n {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
}

.yxdy29x_q {
  fill: var(--svg-color--ffad2f, #FFAD2F);
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.804-8.137-.702c-.512-.376-.471-.93-.095-1.442");
}

.zciozgblx {
  d: path("m25.947 22.035l-1.294.557l.035 1.711c.33.289 1.104 1.066 1.808 1.602c.46.35.894.355 1.192.295c.226-.045.287-.3.188-.51l-1.594-3.538a.25.25 0 0 0-.335-.117");
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zkrl1s-bn {
  fill: var(--svg-color--ffc632, #FFC632);
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.804.8 1.416l-.809 2.915a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.322l.809-2.916a1.15 1.15 0 0 1 1.416-.801");
}

.zlcet8bnw {
  stop-color: var(--svg-color--6944a2, #6944A2);
}

.zs4p_mbda {
  stop-color: var(--svg-color--745fa7, #745FA7);
  stop-opacity: 0;
}

</style>
