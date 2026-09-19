<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ij6KLlb)"><path fill="url(#iy8zHNA)" class="c2_b_zb7o"/><path fill="url(#iVUmgad)" class="c2_b_zb7o"/></g><g filter="url(#iLmVlmc)"><path fill="url(#iAVTsfl)" class="nx7ut7dpb"/></g><path fill="url(#i6AMIzb)" class="nx7ut7dpb"/><g filter="url(#iBCrEDe)"><path class="bnowt2j3c"/><path fill="url(#isCEx0G)" class="qfuy3yi6s"/></g><g filter="url(#iD6TGrK)"><path fill="url(#izUoSSc)" clip-rule="evenodd" class="zs-k_rb2u"/></g><g filter="url(#iVXMCVd)"><circle stroke="url(#iPFYiqd)" class="rt9q19y-s"/></g><path fill="url(#iy1v5JZ)" class="ovywicbuc"/><path class="bxgbudbcr"/><path fill="url(#iPq8Jpe)" class="r6zkmub4l"/><path fill="url(#ibJKvta)" class="r6zkmub4l"/><path fill="url(#iFou3gc)" clip-rule="evenodd" class="ije04-b7h"/><path fill="url(#is8T5Xb)" clip-rule="evenodd" class="ije04-b7h"/><path fill="url(#iKrGTkd)" clip-rule="evenodd" class="edz8uibsf"/><path fill="url(#iqVOACb)" clip-rule="evenodd" class="iph_kkmip"/><path fill="url(#itKHQud)" clip-rule="evenodd" class="iph_kkmip"/><g filter="url(#iTXNjPc)"><path fill="url(#im8ve9d)" clip-rule="evenodd" class="la0w_dqvx"/><path fill="url(#iYFBWrc)" clip-rule="evenodd" class="la0w_dqvx"/></g><path fill="url(#iNLvejd)" clip-rule="evenodd" class="by0r7kbns"/><path fill="url(#iNfRGGU)" clip-rule="evenodd" class="a320f_rgd"/><path fill="url(#iRInLDb)" clip-rule="evenodd" class="a320f_rgd"/><path fill="url(#iZLUQtb)" clip-rule="evenodd" class="a320f_rgd"/><path fill="url(#ikaV82t)" class="ssz-msb_q"/><path fill="url(#iVZfjcd)" class="ssz-msb_q"/><path fill="url(#iuYO0bb)" class="ssz-msb_q"/><path fill="url(#iykkr5X)" class="a7fv_bbss"/><path fill="url(#iZGHuPd)" class="a7fv_bbss"/><g filter="url(#ivIOVkc)"><path fill="url(#iyGn9Cc)" class="i-8cpebnm"/><path fill="url(#iZ0XFKd)" class="i-8cpebnm"/></g><circle fill="url(#i1TyOLb)" class="b8m85sj2j"/><circle fill="url(#iaHa9cb)" class="b8m85sj2j"/><g filter="url(#igMRWjb)"><path class="mk1dptbue"/><path fill="url(#iOlD9Gy)" class="droyqfbbm"/><path fill="url(#iqjntBe)" class="droyqfbbm"/></g><path fill="url(#iTOx0LT)" transform="rotate(-55.397 13.537 8.477)" class="gzx25ktal"/><path fill="url(#icsZ1sb)" transform="rotate(-55.397 13.537 8.477)" class="gzx25ktal"/><g filter="url(#iaNESMb)"><path fill="url(#iMMouCf)" class="hxud7dtld"/><path fill="url(#idGvmte)" class="hxud7dtld"/></g><g filter="url(#ir27nme)"><path fill="url(#iJHOOKd)" class="jg_z34btj"/><path fill="url(#iXXhHsd)" class="jg_z34btj"/></g><g filter="url(#i9OlCJd)"><path fill="url(#i9CFmld)" class="yaji4er8c"/></g><g filter="url(#iHS9irc)"><path class="v_8ci9b1m"/><path fill="url(#iUAW0mV)" class="h4b0j2n8s"/></g><g filter="url(#iCnaIGd)"><path clip-rule="evenodd" class="ljo36qb7d"/></g><g filter="url(#icGbHBd)"><path clip-rule="evenodd" class="uuzja3ftk"/><path fill="url(#iayMNWd)" clip-rule="evenodd" class="apu0rac8i"/></g><path fill="url(#ipVrziY)" clip-rule="evenodd" class="wwmuqrbfj"/><path fill="url(#iWFNdCe)" clip-rule="evenodd" class="wwmuqrbfj"/><g filter="url(#iHzwb3u)"><path fill="url(#iDdzZVc)" class="vo2v0rbyd"/></g><path fill="url(#iknM9lc)" clip-rule="evenodd" class="avwryhasq"/><path fill="url(#iI4wpld)" clip-rule="evenodd" class="avwryhasq"/><path fill="url(#iI4wpld)" clip-rule="evenodd" class="avwryhasq"/><path fill="url(#iX0L3fb)" clip-rule="evenodd" class="atpyom5wh"/><path fill="url(#iTR9iee)" clip-rule="evenodd" class="atpyom5wh"/><g filter="url(#ivCnjqe)"><circle class="papv_ew-o"/></g><path fill="url(#inx4RGb)" class="mbmmywbna"/><g filter="url(#ivvx04d)"><path fill="url(#i9ZtNIc)" class="wu3jqhr6h"/><path fill="url(#ijiACee)" class="wu3jqhr6h"/></g><path clip-rule="evenodd" class="p4c71nzax"/><path class="quv_qz-dd"/><path class="enryj2brc"/><path fill="url(#icL4ipe)" class="bk6o2vjhv"/><circle transform="rotate(-64.203 11.114 7.401)" class="mbffqlbvb"/><g filter="url(#iiEtoTb)"><path fill="url(#idBVrAe)" class="wjmtj7bxy"/></g><circle fill="url(#iXxkFPf)" transform="rotate(-64.203 13.442 6.354)" class="vcp_ytdsi"/><path clip-rule="evenodd" class="cwwogjbvo"/><path fill="url(#i6RGFLc)" clip-rule="evenodd" class="q8srf8b1c"/><path fill="url(#iZ1XGec)" clip-rule="evenodd" class="q8srf8b1c"/><path fill="url(#iXmUmqd)" clip-rule="evenodd" class="q8srf8b1c"/><g filter="url(#iyjCbRc)"><path fill="url(#iXFyx7b)" class="ipxb3gb1e"/></g><g filter="url(#i5lAMVz)"><path fill="url(#idb77Tb)" class="qfdaowbez"/></g><defs><radialGradient id="i6AMIzb" cx="0" cy="0" r="1" gradientTransform="rotate(150.331 11.738 6.305)scale(3.70975 8.36641)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="l4_q8ccja"/><stop offset="1" class="fy0gg3b4w"/></radialGradient><radialGradient id="isCEx0G" cx="0" cy="0" r="1" gradientTransform="matrix(4.42529 4.18325 -2.33905 2.47438 19.748 27.321)" gradientUnits="userSpaceOnUse"><stop class="qfj7itbso"/><stop offset="1" class="p1dkvx0ja"/></radialGradient><radialGradient id="izUoSSc" cx="0" cy="0" r="1" gradientTransform="rotate(126.943 -.25 13.383)scale(9.77501 9.43553)" gradientUnits="userSpaceOnUse"><stop class="y16t4y92n"/><stop offset="1" class="hqorccbwh"/></radialGradient><radialGradient id="ibJKvta" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53127 2.45312 -.44454 -.27749 20.328 21.517)" gradientUnits="userSpaceOnUse"><stop class="m3q9izqvj"/><stop offset="1" class="gxtng2bih"/></radialGradient><radialGradient id="is8T5Xb" cx="0" cy="0" r="1" gradientTransform="rotate(-68.026 18.017 .718)scale(2.88119 .32513)" gradientUnits="userSpaceOnUse"><stop class="f-r3ld20z"/><stop offset="1" class="qnv5cwbcc"/></radialGradient><radialGradient id="iqVOACb" cx="0" cy="0" r="1" gradientTransform="matrix(6.71875 4.82813 -1.31599 1.83131 10.203 19.08)" gradientUnits="userSpaceOnUse"><stop class="zo6cprbov"/><stop offset="1" class="cc9670aeb"/></radialGradient><radialGradient id="im8ve9d" cx="0" cy="0" r="1" gradientTransform="rotate(134.451 9.907 17.356)scale(9.80603 9.46548)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="msqk4cb8o"/><stop offset="1" class="wc0bxtmli"/></radialGradient><radialGradient id="iRInLDb" cx="0" cy="0" r="1" gradientTransform="rotate(103.707 3.007 16.902)scale(4.61583 .44083)" gradientUnits="userSpaceOnUse"><stop class="rgol9fpyb"/><stop offset="1" class="jk5eocp2v"/></radialGradient><radialGradient id="iZLUQtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.0625 1.65481 -.04867 18.484 24.314)" gradientUnits="userSpaceOnUse"><stop class="d-6jagb2y"/><stop offset="1" class="zd8v8x_xx"/></radialGradient><radialGradient id="ikaV82t" cx="0" cy="0" r="1" gradientTransform="matrix(2.1836 .4375 -.55377 2.76392 13.27 17.314)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="wh4cex3-p"/><stop offset="1" class="qt_-k0bbi"/></radialGradient><radialGradient id="iVZfjcd" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .45313 -.35 .94138 15.766 17.72)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="wup2ffb_k"/><stop offset="1" class="x13wlm6qn"/></radialGradient><radialGradient id="iykkr5X" cx="0" cy="0" r="1" gradientTransform="rotate(143.881 6.893 10.217)scale(2.86275 1.23215)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="o5ujuoler"/><stop offset="1" class="cvi6_hb_e"/></radialGradient><radialGradient id="iZ0XFKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.86719 0 0 -.96875 25.602 25.376)" gradientUnits="userSpaceOnUse"><stop class="nus19y6ts"/><stop offset="1" class="aiqsdtepb"/></radialGradient><radialGradient id="i1TyOLb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 -.65625 .66797 1.5904 17.703 25.736)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="v5ts0ibjo"/><stop offset="1" class="huz3s4d_a"/></radialGradient><radialGradient id="iaHa9cb" cx="0" cy="0" r="1" gradientTransform="rotate(151.189 6.208 15.062)scale(1.78324)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="da9xf6l5p"/><stop offset="1" class="cbgow0bwo"/></radialGradient><radialGradient id="iqjntBe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1094 -2 6.41983 -3.56106 16.281 26.08)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="egxex7b7c"/><stop offset=".943" class="hs-_dnasa"/></radialGradient><radialGradient id="icsZ1sb" cx="0" cy="0" r="1" gradientTransform="matrix(.03133 1.4211 -.52543 .01158 14.962 9.46)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="tet8rzrdg"/><stop offset="1" class="fkvb-pzhb"/></radialGradient><radialGradient id="iMMouCf" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 -8.78125 2.52881 -.21598 17.922 24.47)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="vy73m_-_t"/><stop offset="1" class="jmkgnh7bk"/></radialGradient><radialGradient id="idGvmte" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6875 .0625 -.11168 -3.01554 18.828 18.189)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="bggy0db3n"/><stop offset="1" class="jjbnuc1vv"/></radialGradient><radialGradient id="iJHOOKd" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -4.9297 2.6132 2.71672 16.797 16.095)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="zwrak1b2j"/><stop offset="1" class="zvme7yb8w"/></radialGradient><radialGradient id="iXXhHsd" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -.09375 .01804 .49916 18.219 14.376)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="aw4amab0f"/><stop offset="1" class="jqhw67baa"/></radialGradient><radialGradient id="i9CFmld" cx="0" cy="0" r="1" gradientTransform="matrix(-3.49999 -4.06251 1.70908 -1.47243 21.11 12.064)" gradientUnits="userSpaceOnUse"><stop class="ff0nxwb2o"/><stop offset="1" class="uakehioxk"/></radialGradient><radialGradient id="iUAW0mV" cx="0" cy="0" r="1" gradientTransform="matrix(3.25232 0 0 1.29925 10.06 13.501)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="qktpib9mi"/><stop offset="1" class="ms8ncfh9g"/></radialGradient><radialGradient id="iayMNWd" cx="0" cy="0" r="1" gradientTransform="rotate(158.559 7.909 6.321)scale(1.11134 1.23837)" gradientUnits="userSpaceOnUse"><stop class="q8q3z293b"/><stop offset="1" class="n_483ubxp"/></radialGradient><radialGradient id="ipVrziY" cx="0" cy="0" r="1" gradientTransform="rotate(-40.244 23.588 -2.801)scale(2.21381 1.97366)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="njm7ndb-g"/><stop offset="1" class="j2td23bjy"/></radialGradient><radialGradient id="iWFNdCe" cx="0" cy="0" r="1" gradientTransform="rotate(-169.577 4.87 6.837)scale(1.33255 2.06198)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ov28pkqzr"/><stop offset="1" class="g_ar82bkt"/></radialGradient><radialGradient id="iDdzZVc" cx="0" cy="0" r="1" gradientTransform="matrix(5.5 -1.4375 2.00475 7.67032 17.36 15.251)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f6rwhfb_k"/><stop offset=".905" class="aw8cj7bar"/></radialGradient><radialGradient id="iknM9lc" cx="0" cy="0" r="1" gradientTransform="rotate(-49.422 20.186 -.741)scale(1.68837 1.40322)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="njm7ndb-g"/><stop offset="1" class="j2td23bjy"/></radialGradient><radialGradient id="iI4wpld" cx="0" cy="0" r="1" gradientTransform="rotate(-167.973 4.92 7.029)scale(.83427 1.78585)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ov28pkqzr"/><stop offset="1" class="g_ar82bkt"/></radialGradient><radialGradient id="iX0L3fb" cx="0" cy="0" r="1" gradientTransform="matrix(.85938 -1.30714 1.0714 .7044 8.182 15.486)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="njm7ndb-g"/><stop offset="1" class="j2td23bjy"/></radialGradient><radialGradient id="iTR9iee" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 -.07814 .17335 -1.6638 8.752 15.285)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ov28pkqzr"/><stop offset="1" class="g_ar82bkt"/></radialGradient><radialGradient id="inx4RGb" cx="0" cy="0" r="1" gradientTransform="rotate(25.799 -12.91 27.7)scale(.75698 .95225)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="gbpc64bji"/><stop offset="1" class="ovz69fb_x"/></radialGradient><radialGradient id="i9ZtNIc" cx="0" cy="0" r="1" gradientTransform="matrix(3.08263 -1.12796 1.16987 3.19718 11.534 8.378)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="b8g00zlka"/><stop offset="1" class="z7m9rdbog"/></radialGradient><radialGradient id="ijiACee" cx="0" cy="0" r="1" gradientTransform="matrix(1.0831 1.55058 -1.2512 .87398 13.039 5.64)" gradientUnits="userSpaceOnUse"><stop class="iooxo1wql"/><stop offset="1" class="hlbcv5m7e"/></radialGradient><radialGradient id="idBVrAe" cx="0" cy="0" r="1" gradientTransform="matrix(.82408 1.58649 -1.03949 .53995 14.675 5.213)" gradientUnits="userSpaceOnUse"><stop class="ac50icc3e"/><stop offset="1" class="cztd2jqtm"/></radialGradient><radialGradient id="iXxkFPf" cx="0" cy="0" r="1" gradientTransform="matrix(-.52908 -.4815 .27858 -.30611 14 6.682)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="ht6ac_srn"/><stop offset="1" class="j1oidy4hh"/></radialGradient><radialGradient id="iXmUmqd" cx="0" cy="0" r="1" gradientTransform="matrix(.1874 -.08563 .50193 1.09841 13.385 6.966)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="iXFyx7b" cx="0" cy="0" r="1" gradientTransform="rotate(65.49 2.979 11.167)scale(2.3563 2.7695)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="idb77Tb" cx="0" cy="0" r="1" gradientTransform="matrix(-.28797 -.61245 1.57056 -.73848 12.39 5.568)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><linearGradient id="iy8zHNA" x1="9.65" x2="27.955" y1="21.567" y2="9.378" gradientUnits="userSpaceOnUse"><stop class="jk9sxjbtz"/><stop offset="1" class="bsmaek8tk"/></linearGradient><linearGradient id="iVUmgad" x1="29.363" x2="25.903" y1="12.556" y2="14.97" gradientUnits="userSpaceOnUse"><stop offset=".164" class="lc4-hmwkn"/><stop offset="1" class="jvv3w_k0n"/></linearGradient><linearGradient id="iAVTsfl" x1="21.156" x2="24.898" y1="7.567" y2="5.475" gradientUnits="userSpaceOnUse"><stop class="tw0q1w8vf"/><stop offset="1" class="icj8g3w8l"/></linearGradient><linearGradient id="iPFYiqd" x1="9.266" x2="3.234" y1="21.876" y2="28.907" gradientUnits="userSpaceOnUse"><stop class="aqhis8bfy"/><stop offset="1" class="dicaxrbsa"/></linearGradient><linearGradient id="iy1v5JZ" x1="17.734" x2="18.703" y1="21.079" y2="20.073" gradientUnits="userSpaceOnUse"><stop offset=".573" class="blqobpb3p"/><stop offset="1" class="e4_3u5fwf"/></linearGradient><linearGradient id="iPq8Jpe" x1="22.25" x2="17.656" y1="22.648" y2="22.189" gradientUnits="userSpaceOnUse"><stop offset=".891" class="eper2rg6p"/><stop offset="1" class="btv0f_swr"/></linearGradient><linearGradient id="iFou3gc" x1="11.531" x2="10.656" y1="15.47" y2="15.189" gradientUnits="userSpaceOnUse"><stop class="b32taybyq"/><stop offset="1" class="cq_k1jhvn"/></linearGradient><linearGradient id="iKrGTkd" x1="9.766" x2="8.484" y1="20.423" y2="19.939" gradientUnits="userSpaceOnUse"><stop offset=".146" class="l2qa6pp5f"/><stop offset="1" class="j4w4r7dqg"/></linearGradient><linearGradient id="itKHQud" x1="12.984" x2="13.375" y1="22.47" y2="21.97" gradientUnits="userSpaceOnUse"><stop class="xlcjgwbhs"/><stop offset="1" class="xdbcf5brc"/><stop offset="1" class="dkvvw7m1c"/></linearGradient><linearGradient id="iYFBWrc" x1="20.031" x2="27.786" y1="27.981" y2="25.54" gradientUnits="userSpaceOnUse"><stop class="qkrvzzbyd"/><stop offset="1" class="zaq2lsbln"/></linearGradient><linearGradient id="iNLvejd" x1="23.813" x2="22.75" y1="22.407" y2="23.157" gradientUnits="userSpaceOnUse"><stop class="ikszdii2u"/><stop offset="1" class="li38i4ecv"/></linearGradient><linearGradient id="iNfRGGU" x1="19.609" x2="18.594" y1="21.181" y2="21.032" gradientUnits="userSpaceOnUse"><stop class="wjlh8kb9f"/><stop offset="1" class="pf-dzrbda"/></linearGradient><linearGradient id="iuYO0bb" x1="14.547" x2="14.969" y1="15.439" y2="16.126" gradientUnits="userSpaceOnUse"><stop class="gsvusqzno"/><stop offset="1" class="jlmqg8bhb"/></linearGradient><linearGradient id="iZGHuPd" x1="16.617" x2="16.984" y1="14.306" y2="14.837" gradientUnits="userSpaceOnUse"><stop class="oqmso-c_s"/><stop offset="1" class="s2g06frqj"/></linearGradient><linearGradient id="iyGn9Cc" x1="25.328" x2="16.664" y1="25.54" y2="25.54" gradientUnits="userSpaceOnUse"><stop class="jk12cqb2p"/><stop offset="1" class="bjfaebcql"/></linearGradient><linearGradient id="iOlD9Gy" x1="17.461" x2="16.703" y1="25.407" y2="25.407" gradientUnits="userSpaceOnUse"><stop class="z_jgx_kqm"/><stop offset="1" class="ktkvjmbcj"/></linearGradient><linearGradient id="iTOx0LT" x1="15.547" x2="13.942" y1="9.939" y2="9.869" gradientUnits="userSpaceOnUse"><stop class="ml8gycbxr"/><stop offset="1" class="se-fwg5_y"/></linearGradient><linearGradient id="icL4ipe" x1="11.131" x2="11.368" y1="7.751" y2="7.612" gradientUnits="userSpaceOnUse"><stop offset=".242" class="qrd5snbhi"/><stop offset=".667" class="ywpul_b7i"/></linearGradient><linearGradient id="i6RGFLc" x1="13.75" x2="13.333" y1="7.153" y2="7.364" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="iZ1XGec" x1="13.594" x2="14.117" y1="8.95" y2="8.639" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><filter id="ij6KLlb" width="28.938" height="27.87" x="2.031" y="3.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.658824 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="iLmVlmc" width="8.378" height="5.198" x="17.771" y="3.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.705882 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="iBCrEDe" width="27.922" height="3.388" x="2.047" y="27.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.258824 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="iD6TGrK" width="9.938" height="9.938" x="2.086" y="20.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.156863 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="iVXMCVd" width="10.409" height="10.409" x="1.85" y="20.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23483" stdDeviation=".25"/></filter><filter id="iTXNjPc" width="10.037" height="10.037" x="20.031" y="20.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.0862745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="ivIOVkc" width="9.188" height="4.077" x="16.664" y="23.427" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.341176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.490196 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23483" result="effect2_innerShadow_3987_23483"/></filter><filter id="igMRWjb" width="4.034" height="2.181" x="13.527" y="23.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.188235 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="iaNESMb" width="3.572" height="8.62" x="15.2" y="16.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.262745 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="ir27nme" width="6.668" height="7.67" x="16.578" y="10.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.360784 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="i9OlCJd" width="7.971" height="5.869" x="15.037" y="7.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.411765 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="iHS9irc" width="6.005" height="4.259" x="6.933" y="11.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.505882 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="iCnaIGd" width="3.137" height="2.915" x="6.934" y="13.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.117647 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="icGbHBd" width="10.272" height="6.937" x="7.81" y="8.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.12549 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="iHzwb3u" width="5.496" height="6.372" x="17.724" y="11.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23483" stdDeviation=".3"/></filter><filter id="ivCnjqe" width="2.969" height="2.969" x="7.738" y="12.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23483" stdDeviation=".3"/></filter><filter id="ivvx04d" width="5.753" height="5.249" x="10.07" y="4.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.278431 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23483" result="effect2_innerShadow_3987_23483"/></filter><filter id="iiEtoTb" width="3.099" height="2.767" x="13.101" y="4.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0745098 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="iyjCbRc" width="5.871" height="4.983" x="9.308" y="2.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter><filter id="i5lAMVz" width="1.989" height="1.346" x="11.246" y="4.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23483"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-mountain-biking-dark" /></template>
<style>
.a320f_rgd {
  fill-rule: evenodd;
  d: path("M20.042 17.105a.55.55 0 0 1 .417.657L18.88 24.84a.55.55 0 1 1-1.074-.24l1.578-7.078a.55.55 0 0 1 .657-.417");
}

.a7fv_bbss {
  d: path("m15.277 15.208l2.641-1.61l1.207.63l-2.727 2.476c-.268-.23-.84-1.05-1.12-1.496");
}

.ac50icc3e {
  stop-color: var(--svg-color--231820, #231820);
}

.aiqsdtepb {
  stop-color: var(--svg-color--ffd359, #FFD359);
  stop-opacity: 0;
}

.apu0rac8i {
  fill-rule: evenodd;
  d: path("M17.124 8.838c.479.327.602.98.274 1.46c-.782 1.144-3.151 4.302-7.932 4.787c-.577.058-1.595-.32-1.653-.896s.864-1.135 1.44-1.193c3.845-.39 5.741-2.904 6.412-3.884a1.05 1.05 0 0 1 1.46-.274");
}

.aqhis8bfy {
  stop-color: var(--svg-color--302a5b, #302A5B);
}

.atpyom5wh {
  fill-rule: evenodd;
  d: path("M9.127 14.27a.33.33 0 0 1 0 .403c-.151.126-.342.39-.372.594a.35.35 0 1 1-.693-.101c.019-.129.077-.285.155-.43c.08-.147.196-.312.354-.442c.148-.124.433-.172.556-.023");
}

.avwryhasq {
  fill-rule: evenodd;
  d: path("M8.834 14.012a.35.35 0 0 1-.227.44a.6.6 0 0 0-.406.457a.35.35 0 0 1-.683-.152c.05-.223.235-.767.876-.972a.35.35 0 0 1 .44.227");
}

.aw4amab0f {
  stop-color: var(--svg-color--736e75, #736E75);
}

.aw8cj7bar {
  stop-color: var(--svg-color--afa6a9, #AFA6A9);
}

.b32taybyq {
  stop-color: var(--svg-color--bfa8c7, #BFA8C7);
}

.b8g00zlka {
  stop-color: var(--svg-color--402e2d, #402E2D);
}

.b8m85sj2j {
  cx: 18.371px;
  cy: 25.54px;
  r: 1.027px;
}

.bggy0db3n {
  stop-color: var(--svg-color--3f202e, #3F202E);
}

.bjfaebcql {
  stop-color: var(--svg-color--e8774d, #E8774D);
}

.bk6o2vjhv {
  d: path("M11.445 7.678a.5.5 0 0 0-.048-.091c-.088-.137-.218-.21-.29-.163s-.058.194.03.331a1 1 0 0 0 .056.073z");
}

.blqobpb3p {
  stop-color: var(--svg-color--381a27, #381A27);
}

.bnowt2j3c {
  fill: var(--svg-color--97595f, #97595F);
  d: path("m5.663 27.68l-3.616 2.157v.672h27.922v-.672l-3.532-2.15a2.4 2.4 0 0 0-2.429-.04l-.817.462a2 2 0 0 1-1.838.067l-1.319-.622a2.25 2.25 0 0 0-1.965.02l-1.176.587a2 2 0 0 1-1.823-.019l-1.126-.591a2 2 0 0 0-1.783-.04l-1.42.67a2 2 0 0 1-1.825-.062l-.855-.476a2.4 2.4 0 0 0-2.398.036");
}

.bsmaek8tk {
  stop-color: var(--svg-color--36c571, #36C571);
}

.btv0f_swr {
  stop-color: var(--svg-color--615f76, #615F76);
}

.bxgbudbcr {
  fill: var(--svg-color--413354, #413354);
  d: path("m17.88 21.43l-.3 1.98c-.066.476-.04.887.365 1.167c.101.07.237.031.306-.071l1.964-2.902a.2.2 0 0 0-.054-.277l-.952-.645z");
}

.by0r7kbns {
  fill-rule: evenodd;
  d: path("M19.738 17.185a.55.55 0 0 0-.172.758l4.719 7.477a.55.55 0 1 0 .93-.587l-4.719-7.477a.55.55 0 0 0-.758-.171");
}

.c2_b_zb7o {
  d: path("m3.898 17.275l-1.867 1.937v11.281H29.97v-16.53l-6.14-9.306a2.3 2.3 0 0 0-3.841.002l-8.916 13.55a.5.5 0 0 1-.715.126L8.31 16.818c-1.32-.98-3.2-.801-4.41.457");
}

.cbgow0bwo {
  stop-color: var(--svg-color--e2dfe5, #E2DFE5);
}

.cc9670aeb {
  stop-color: var(--svg-color--932145, #932145);
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.cq_k1jhvn {
  stop-color: var(--svg-color--908590, #908590);
}

.cvi6_hb_e {
  stop-color: var(--svg-color--564a5a, #564A5A);
}

.cwwogjbvo {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M12.687 5.647a.29.29 0 0 1 .384.144l1.496 3.29a.29.29 0 1 1-.528.241l-1.496-3.29a.29.29 0 0 1 .144-.385");
}

.cztd2jqtm {
  stop-color: var(--svg-color--151a31, #151A31);
}

.d-6jagb2y {
  stop-color: var(--svg-color--ac2735, #AC2735);
}

.da9xf6l5p {
  stop-color: var(--svg-color--e2dfe5, #E2DFE5);
  stop-opacity: 0;
}

.dicaxrbsa {
  stop-color: var(--svg-color--302a5b, #302A5B);
  stop-opacity: 0;
}

.dkvvw7m1c {
  stop-color: var(--svg-color--9c2649, #9C2649);
  stop-opacity: 0;
}

.droyqfbbm {
  d: path("m16.097 23.79l-1.808.86c-.432.213-.757.465-.762.957c-.002.123.107.214.23.214h3.504a.2.2 0 0 0 .2-.2v-1.15z");
}

.e4_3u5fwf {
  stop-color: var(--svg-color--4a3939, #4A3939);
}

.edz8uibsf {
  fill-rule: evenodd;
  d: path("M10.553 16.899a.55.55 0 0 1 .3.718l-3.29 8a.55.55 0 1 1-1.017-.419l3.29-8a.55.55 0 0 1 .717-.3");
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.egxex7b7c {
  stop-color: var(--svg-color--5c4f86, #5C4F86);
  stop-opacity: 0;
}

.enryj2brc {
  fill: var(--svg-color--634c48, #634C48);
  d: path("m11.632 7.566l-.029-.047c-.159-.246-.395-.376-.527-.29c-.133.085-.111.354.048.6q.009.015.02.029z");
}

.eper2rg6p {
  stop-color: var(--svg-color--615f76, #615F76);
  stop-opacity: 0;
}

.f-r3ld20z {
  stop-color: var(--svg-color--baa3b9, #BAA3B9);
}

.f6rwhfb_k {
  stop-color: var(--svg-color--afa6a9, #AFA6A9);
  stop-opacity: 0;
}

.ff0nxwb2o {
  stop-color: var(--svg-color--54a7f5, #54A7F5);
}

.fkvb-pzhb {
  stop-color: var(--svg-color--544241, #544241);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fy0gg3b4w {
  stop-color: var(--svg-color--d9d1df, #D9D1DF);
  stop-opacity: 0;
}

.g_ar82bkt {
  stop-color: var(--svg-color--584744, #584744);
}

.gbpc64bji {
  stop-color: var(--svg-color--463736, #463736);
}

.gsvusqzno {
  stop-color: var(--svg-color--41302f, #41302F);
}

.gxtng2bih {
  stop-color: var(--svg-color--5d5c7e, #5D5C7E);
  stop-opacity: 0;
}

.gzx25ktal {
  d: path("M13.537 8.477h2.154v2.668h-2.154z");
}

.h4b0j2n8s {
  d: path("M12.938 12.173a.575.575 0 0 0-.575-.575h-3.05a2.13 2.13 0 0 0 0 4.26h.182a.575.575 0 1 0 0-1.15h-.182a.98.98 0 1 1 0-1.96h3.05a.575.575 0 0 0 .575-.575");
}

.hlbcv5m7e {
  stop-color: var(--svg-color--2b1a25, #2B1A25);
  stop-opacity: 0;
}

.hqorccbwh {
  stop-color: var(--svg-color--3c2150, #3C2150);
}

.hs-_dnasa {
  stop-color: var(--svg-color--493b63, #493B63);
}

.ht6ac_srn {
  stop-color: var(--svg-color--615250, #615250);
}

.huz3s4d_a {
  stop-color: var(--svg-color--c5bfcb, #C5BFCB);
}

.hxud7dtld {
  d: path("m16.078 16.564l.554-.514l2.04 1.916c-.274.154-.887.463-1.031.582c-.11.09-.11.235-.11.328l-.046 5.594l-1.407-.672c-.138-.794-.42-2.708-.769-4.3c-.395-1.801.376-2.593.77-2.934");
}

.i-8cpebnm {
  d: path("M18.911 27.364q-.185.04-.384.04a1.863 1.863 0 1 1 .403-3.683l5.898.905a.927.927 0 0 1-.086 1.838z");
}

.icj8g3w8l {
  stop-color: var(--svg-color--e2dce7, #E2DCE7);
}

.ije04-b7h {
  fill-rule: evenodd;
  d: path("M12.487 12.164a.5.5 0 0 1 .272.653l-2.54 6.247a.5.5 0 0 1-.925-.382l2.54-6.246a.5.5 0 0 1 .653-.272");
}

.ikszdii2u {
  stop-color: var(--svg-color--fd5a60, #FD5A60);
}

.iooxo1wql {
  stop-color: var(--svg-color--2b1a25, #2B1A25);
}

.iph_kkmip {
  fill-rule: evenodd;
  d: path("M9.629 19.126c.102-.222.43-.465.673-.282l6.25 4.75a.55.55 0 0 1-.666.876l-6.081-4.61c-.242-.183-.305-.453-.176-.734");
}

.ipxb3gb1e {
  d: path("m15.028 4.98l-4.649 2.43a.257.257 0 0 1-.335-.076a5.6 5.6 0 0 1-.575-1.12c-.542-1.43.45-2.243.58-2.368c.189-.181.708-.63 1.827-1.05c1.314-.494 2.155.084 2.567.626c.26.34.544.853.71 1.198a.27.27 0 0 1-.125.36");
}

.j1oidy4hh {
  stop-color: var(--svg-color--40292e, #40292E);
}

.j2td23bjy {
  stop-color: var(--svg-color--492f31, #492F31);
}

.j4w4r7dqg {
  stop-color: var(--svg-color--973c50, #973C50);
}

.jg_z34btj {
  d: path("m18.362 14.341l-.635-.7l4.03-2.476c1.423 1.868 1.5 3.211.837 4.274c-.664 1.062-1.582 2.05-2.617 2.945c-.272.235-.803.362-1.36-.18c-.707-.687-1.578-1.578-2.039-2.113l1.777-1.609a.1.1 0 0 0 .007-.14");
}

.jjbnuc1vv {
  stop-color: var(--svg-color--3f202e, #3F202E);
  stop-opacity: 0;
}

.jk12cqb2p {
  stop-color: var(--svg-color--f7b14e, #F7B14E);
}

.jk5eocp2v {
  stop-color: var(--svg-color--e44354, #E44354);
  stop-opacity: 0;
}

.jk9sxjbtz {
  stop-color: var(--svg-color--37c173, #37C173);
}

.jlmqg8bhb {
  stop-color: var(--svg-color--41302f, #41302F);
  stop-opacity: 0;
}

.jmkgnh7bk {
  stop-color: var(--svg-color--442d2c, #442D2C);
}

.jqhw67baa {
  stop-color: var(--svg-color--736e75, #736E75);
  stop-opacity: 0;
}

.jvv3w_k0n {
  stop-color: var(--svg-color--36c871, #36C871);
  stop-opacity: 0;
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.ktkvjmbcj {
  stop-color: var(--svg-color--605c92, #605C92);
  stop-opacity: 0;
}

.l2qa6pp5f {
  stop-color: var(--svg-color--d4385b, #D4385B);
}

.l4_q8ccja {
  stop-color: var(--svg-color--ebeaed, #EBEAED);
}

.la0w_dqvx {
  fill-rule: evenodd;
  d: path("M25 21.572a3.969 3.969 0 1 0 0 7.937a3.969 3.969 0 0 0 0-7.937m-4.969 3.968a4.969 4.969 0 1 1 9.938 0a4.969 4.969 0 0 1-9.938 0");
}

.lc4-hmwkn {
  stop-color: var(--svg-color--4cdd80, #4CDD80);
}

.li38i4ecv {
  stop-color: var(--svg-color--af253c, #AF253C);
}

.ljo36qb7d {
  fill: var(--svg-color--2b174f, #2B174F);
  fill-rule: evenodd;
  d: path("M8.332 13.786v-.021a.572.572 0 1 0-1.145 0v.021h-.003a2.13 2.13 0 0 0 2.129 2.072h.182a.575.575 0 0 0 0-1.15h-.182a.98.98 0 0 1-.979-.922z");
}

.m3q9izqvj {
  stop-color: var(--svg-color--5d5c7e, #5D5C7E);
}

.mbffqlbvb {
  cx: 11.114px;
  cy: 7.401px;
  r: 0.083px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.mbmmywbna {
  d: path("M10.825 8.95c-.2-.136-.205-.294-.14-.646a.8.8 0 0 0-.064-.53l.807.98c-.106.22-.403.334-.603.197");
}

.mk1dptbue {
  fill: var(--svg-color--5b4e85, #5B4E85);
  d: path("m16.097 23.79l-1.808.86c-.432.213-.757.465-.762.957c-.002.123.107.214.23.214h3.504a.2.2 0 0 0 .2-.2v-1.15z");
}

.ml8gycbxr {
  stop-color: var(--svg-color--513b37, #513B37);
}

.ms8ncfh9g {
  stop-color: var(--svg-color--8c5ea8, #8C5EA8);
  stop-opacity: 0;
}

.msqk4cb8o {
  stop-color: var(--svg-color--373c67, #373C67);
}

.n_483ubxp {
  stop-color: var(--svg-color--604f4d, #604F4D);
  stop-opacity: 0;
}

.njm7ndb-g {
  stop-color: var(--svg-color--3c212e, #3C212E);
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nus19y6ts {
  stop-color: var(--svg-color--ffd359, #FFD359);
}

.nx7ut7dpb {
  d: path("m17.771 8.027l2.247-1.315a.4.4 0 0 1 .511.091l1.07 1.3a.6.6 0 0 0 .927 0l1.067-1.296a.4.4 0 0 1 .515-.089L25.9 7.795l-2.07-3.138a2.3 2.3 0 0 0-3.841.002z");
}

.o5ujuoler {
  stop-color: var(--svg-color--4f414e, #4F414E);
}

.oqmso-c_s {
  stop-color: var(--svg-color--72696b, #72696B);
}

.ov28pkqzr {
  stop-color: var(--svg-color--584744, #584744);
  stop-opacity: 0;
}

.ovywicbuc {
  d: path("m19.186 20.697l-1.827-1.989l-.423 2.059l1 .705z");
}

.ovz69fb_x {
  stop-color: var(--svg-color--483637, #483637);
}

.p1dkvx0ja {
  stop-color: var(--svg-color--8a4c56, #8A4C56);
  stop-opacity: 0;
}

.p4c71nzax {
  fill: var(--svg-color--290017, #290017);
  fill-rule: evenodd;
  d: path("M11.885 9.173a.116.116 0 0 1 .04-.159c.1-.06.233-.21.304-.522a.116.116 0 1 1 .227.051c-.082.358-.244.57-.412.67a.116.116 0 0 1-.16-.04");
}

.papv_ew-o {
  cx: 9.223px;
  cy: 13.988px;
  r: 0.885px;
  fill: var(--svg-color--493030, #493030);
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pf-dzrbda {
  stop-color: var(--svg-color--a62f2f, #A62F2F);
}

.q8q3z293b {
  stop-color: var(--svg-color--604f4d, #604F4D);
}

.q8srf8b1c {
  fill-rule: evenodd;
  d: path("M12.687 5.647a.29.29 0 0 1 .384.144l1.496 3.29a.29.29 0 1 1-.528.241l-1.496-3.29a.29.29 0 0 1 .144-.385");
}

.qfdaowbez {
  d: path("M11.283 5.746a.35.35 0 0 1 .156-.47l1.289-.646a.35.35 0 0 1 .313.626l-1.288.646a.35.35 0 0 1-.47-.156");
}

.qfj7itbso {
  stop-color: var(--svg-color--8a4c56, #8A4C56);
}

.qfuy3yi6s {
  d: path("m5.663 27.68l-3.616 2.157v.672h27.922v-.672l-3.532-2.15a2.4 2.4 0 0 0-2.429-.04l-.817.462a2 2 0 0 1-1.838.067l-1.319-.622a2.25 2.25 0 0 0-1.965.02l-1.176.587a2 2 0 0 1-1.823-.019l-1.126-.591a2 2 0 0 0-1.783-.04l-1.42.67a2 2 0 0 1-1.825-.062l-.855-.476a2.4 2.4 0 0 0-2.398.036");
}

.qkrvzzbyd {
  stop-color: var(--svg-color--352542, #352542);
}

.qktpib9mi {
  stop-color: var(--svg-color--8c5ea8, #8C5EA8);
}

.qnv5cwbcc {
  stop-color: var(--svg-color--baa3b9, #BAA3B9);
  stop-opacity: 0;
}

.qrd5snbhi {
  stop-color: var(--svg-color--5f5451, #5F5451);
}

.qt_-k0bbi {
  stop-color: var(--svg-color--2f1b1b, #2F1B1B);
}

.quv_qz-dd {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.001 7.294c-.069.226.067.452.14.566l.876-.523c-.523-.585-.923-.35-1.016-.043");
}

.r6zkmub4l {
  d: path("m17.88 21.43l-.3 1.98c-.066.476-.04.887.365 1.167c.101.07.237.031.306-.071l1.964-2.902a.2.2 0 0 0-.054-.277l-.952-.645z");
}

.rgol9fpyb {
  stop-color: var(--svg-color--e44354, #E44354);
}

.rt9q19y-s {
  cx: 7.055px;
  cy: 25.54px;
  r: 4.555px;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
}

.s2g06frqj {
  stop-color: var(--svg-color--72696b, #72696B);
  stop-opacity: 0;
}

.se-fwg5_y {
  stop-color: var(--svg-color--2f191c, #2F191C);
}

.ssz-msb_q {
  d: path("m13.997 16.009l1.34-.836l1.038 1.04l-.765 3.53a245 245 0 0 0-1.687-1.242c-.149-.101-.661-.543-.653-1.238c.008-.711.477-1.072.727-1.254");
}

.tet8rzrdg {
  stop-color: var(--svg-color--544241, #544241);
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tw0q1w8vf {
  stop-color: var(--svg-color--d7cfdf, #D7CFDF);
}

.uakehioxk {
  stop-color: var(--svg-color--3b79d4, #3B79D4);
}

.uuzja3ftk {
  fill: var(--svg-color--492f33, #492F33);
  fill-rule: evenodd;
  d: path("M17.124 8.838c.479.327.602.98.274 1.46c-.782 1.144-3.151 4.302-7.932 4.787c-.577.058-1.595-.32-1.653-.896s.864-1.135 1.44-1.193c3.845-.39 5.741-2.904 6.412-3.884a1.05 1.05 0 0 1 1.46-.274");
}

.v_8ci9b1m {
  fill: var(--svg-color--c0b9bc, #C0B9BC);
  d: path("M12.938 12.173a.575.575 0 0 0-.575-.575h-3.05a2.13 2.13 0 0 0 0 4.26h.182a.575.575 0 1 0 0-1.15h-.182a.98.98 0 1 1 0-1.96h3.05a.575.575 0 0 0 .575-.575");
}

.v5ts0ibjo {
  stop-color: var(--svg-color--d8cfe2, #D8CFE2);
}

.vcp_ytdsi {
  cx: 13.442px;
  cy: 6.354px;
  r: 0.648px;
}

.vo2v0rbyd {
  d: path("m20.988 13.459l-.523-.864l1.125-.656c.969 1.313 1.344 2.297.734 2.875c-.487.463-2.87 1.724-4 2.297l2.503-2.414a1 1 0 0 0 .161-1.238");
}

.vy73m_-_t {
  stop-color: var(--svg-color--513938, #513938);
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wc0bxtmli {
  stop-color: var(--svg-color--38144f, #38144F);
}

.wh4cex3-p {
  stop-color: var(--svg-color--4d3938, #4D3938);
}

.wjlh8kb9f {
  stop-color: var(--svg-color--e5435f, #E5435F);
}

.wjmtj7bxy {
  d: path("m14.283 7.131l-1.182-1.2l2.063-1.147c.196.33.665 1.347.634 1.629c-.042.39-.196.917-.645 1.022c-.359.084-.754-.172-.87-.304");
}

.wu3jqhr6h {
  d: path("M11.994 9.697c-.774-.731-1.416-1.91-1.674-2.37l3.415-2.085l1.838 1.654a5.2 5.2 0 0 1-.915 1.894c-.698.88-1.648 1.867-2.664.907");
}

.wup2ffb_k {
  stop-color: var(--svg-color--291618, #291618);
}

.wwmuqrbfj {
  fill-rule: evenodd;
  d: path("M9.319 13.486a.35.35 0 0 1-.35.35c-.173 0-.436.042-.663.15c-.226.106-.37.252-.415.438a.35.35 0 1 1-.68-.166c.114-.466.462-.748.797-.906c.333-.157.7-.216.96-.216a.35.35 0 0 1 .35.35");
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x13wlm6qn {
  stop-color: var(--svg-color--291618, #291618);
  stop-opacity: 0;
}

.xdbcf5brc {
  stop-color: var(--svg-color--96275e, #96275E);
  stop-opacity: 0;
}

.xlcjgwbhs {
  stop-color: var(--svg-color--96275e, #96275E);
}

.y16t4y92n {
  stop-color: var(--svg-color--32295b, #32295B);
}

.yaji4er8c {
  d: path("M16.094 11.72c.664.625 1.363 1.586 1.672 1.969l4.242-2.18c-.586-.976-2.07-2.531-3.54-3.36c-1.718-.812-2.672 0-3.304 1.071c-.414.852.258 1.781.93 2.5");
}

.ywpul_b7i {
  stop-color: var(--svg-color--383838, #383838);
}

.z_jgx_kqm {
  stop-color: var(--svg-color--605c92, #605C92);
}

.z7m9rdbog {
  stop-color: var(--svg-color--41292d, #41292D);
}

.zaq2lsbln {
  stop-color: var(--svg-color--352542, #352542);
  stop-opacity: 0;
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zd8v8x_xx {
  stop-color: var(--svg-color--ac2735, #AC2735);
  stop-opacity: 0;
}

.zo6cprbov {
  stop-color: var(--svg-color--ce3d5e, #CE3D5E);
}

.zs-k_rb2u {
  fill-rule: evenodd;
  d: path("M7.055 21.572a3.969 3.969 0 1 0 0 7.937a3.969 3.969 0 0 0 0-7.937m-4.97 3.968a4.969 4.969 0 1 1 9.938 0a4.969 4.969 0 0 1-9.937 0");
}

.zvme7yb8w {
  stop-color: var(--svg-color--a3a1a2, #A3A1A2);
}

.zwrak1b2j {
  stop-color: var(--svg-color--726b71, #726B71);
}

</style>
