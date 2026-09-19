<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ioGa9Oe)" class="q12x_3brx"/><path fill="url(#iuk7NUc)" class="q12x_3brx"/><path fill="url(#iEE49db)" class="q12x_3brx"/><path class="ndsrk3fql"/><path fill="url(#iKGodqe)" class="zguchrbop"/><path fill="url(#iM0fJwe)" class="zguchrbop"/><path class="mr8h2bixv"/><path fill="url(#ixKKdrs)" class="g9d0ovbvp"/><path fill="url(#iKx9G5K)" class="g9d0ovbvp"/><path fill="url(#ijqVH7d)" class="g9d0ovbvp"/><path fill="url(#i7Gr6le)" class="g9d0ovbvp"/><path fill="url(#iXLkHkd)" class="qum9srb-r"/><path fill="url(#iHcv93c)" class="qum9srb-r"/><path fill="url(#i2glQTb)" class="qum9srb-r"/><path fill="url(#iSHdxeb)" class="qum9srb-r"/><g filter="url(#iIC4wTc)"><path class="amd51vbjg"/><path fill="url(#i6AMUmc)" class="mfs1vbcha"/></g><path clip-rule="evenodd" class="gxkjg_bzv"/><path fill="url(#iCgP0me)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#iD0fZCb)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#iJsS8td)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#igftqFe)" transform="rotate(-23.31 13.976 8.014)" class="d_6rbhb8w"/><path fill="url(#i4bVd5d)" class="yl5-z06iv"/><g filter="url(#iIcxEGb)"><path fill="url(#iymZIod)" class="h3um2wb_s"/><path fill="url(#iWkyl5k)" class="h3um2wb_s"/><path fill="url(#iV6IVfb)" class="h3um2wb_s"/><path fill="url(#iEy8wue)" class="h3um2wb_s"/></g><g filter="url(#i7yjoFc)"><path class="cvfifdc_c"/><path fill="url(#irUPueK)" class="vvbm3s71t"/></g><path fill="url(#ibviQue)" class="lbtowzzet"/><path fill="url(#i4HslBk)" class="lbtowzzet"/><path clip-rule="evenodd" class="dl2hbx40m"/><g filter="url(#iZPeCid)"><path clip-rule="evenodd" class="np4vetbdb"/></g><path class="uqvb40xso"/><path class="svo9k1svp"/><path fill="url(#iouvrrf)" class="nsr274b2n"/><path fill="url(#i1VkCwB)" class="hrip-ov8c"/><ellipse fill="url(#iyYUBkb)" transform="matrix(.92953 .36876 -.39167 .9201 12.623 5.943)" class="ln1i_4nqy"/><g filter="url(#iFwToTb)"><path class="e9_t29bue"/><path fill="url(#igv4lBc)" class="f1u8ijb3m"/><path fill="url(#ixFzlsC)" class="f1u8ijb3m"/><path fill="url(#iZLPaDc)" class="f1u8ijb3m"/><path fill="url(#i8dt67b)" class="f1u8ijb3m"/><path fill="url(#iz53cee)" class="f1u8ijb3m"/></g><path fill="url(#ipSnGqe)" class="vjh3yqznr"/><path fill="url(#iAciTGb)" class="vjh3yqznr"/><path fill="url(#iiDMUtc)" class="vjh3yqznr"/><path fill="url(#iq6Q1Wl)" class="vjh3yqznr"/><path class="ppv4posfy"/><path fill="url(#iYUt5rb)" class="ol51zcmaj"/><path fill="url(#i21JStR)" class="ol51zcmaj"/><path fill="url(#ikduqNe)" class="ol51zcmaj"/><path class="kmd3qcb-j"/><path fill="url(#iiwTGEe)" class="e0lhu47_k"/><path fill="url(#izYIVRu)" class="e0lhu47_k"/><path fill="url(#iRYIdJc)" class="e0lhu47_k"/><path fill="url(#ir7LSIc)" class="e0lhu47_k"/><path fill="url(#idaGKtb)" class="e0lhu47_k"/><g filter="url(#iJmBf6d)"><path clip-rule="evenodd" class="rfat3lb_o"/></g><path fill="url(#iPDnZpf)" clip-rule="evenodd" class="efuw_n2tj"/><path fill="url(#ilBnagI)" clip-rule="evenodd" class="efuw_n2tj"/><path class="npcei-brr"/><path fill="url(#iZ4Xtkb)" class="jmlii5bid"/><path fill="url(#iFj3uCb)" class="jmlii5bid"/><path fill="url(#iePsxCb)" class="jmlii5bid"/><rect fill="url(#ijXMCuq)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><rect fill="url(#iDJCtue)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><path fill="url(#iAtGHKc)" class="mqryp-bup"/><path fill="url(#ir8P1ee)" class="mqryp-bup"/><path fill="url(#ixw5dVd)" class="vtxj36boz"/><path fill="url(#iqniGgc)" class="vtxj36boz"/><path fill="url(#iXOmxIc)" class="t3ncs1j8m"/><path fill="url(#iIMhh4F)" class="t3ncs1j8m"/><g filter="url(#iJ30aFc)"><path fill="url(#iliIEGe)" class="pcwcq6ykk"/></g><path fill="url(#inqL0Pd)" class="afs2-ebiq"/><path fill="url(#ipDfQxd)" class="afs2-ebiq"/><path fill="url(#iFMDzle)" class="afs2-ebiq"/><path fill="url(#iVgiUxb)" class="afs2-ebiq"/><path fill="url(#iESVPYb)" class="afs2-ebiq"/><g filter="url(#is18noe)"><rect class="a18i0zbmv"/></g><g filter="url(#i5mXonv)"><rect class="iepxmux-c"/></g><defs><radialGradient id="ixKKdrs" cx="0" cy="0" r="1" gradientTransform="matrix(.61864 2.14418 -1.49974 .4327 18.926 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="c4e5_obhh"/><stop offset="1" class="mw5xv5bly"/></radialGradient><radialGradient id="iKx9G5K" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 18.88 22.28)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="el1f73rff"/><stop offset="1" class="iasiczten"/></radialGradient><radialGradient id="ijqVH7d" cx="0" cy="0" r="1" gradientTransform="matrix(.80677 2.5012 -1.15566 .37276 16.338 22.544)" gradientUnits="userSpaceOnUse"><stop class="u_7vzbbil"/><stop offset="1" class="n4e7hibnk"/></radialGradient><radialGradient id="i7Gr6le" cx="0" cy="0" r="1" gradientTransform="rotate(71.565 -6.364 23.576)scale(.54352 3.09962)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="u07rntblp"/><stop offset="1" class="tbt6sb7pf"/></radialGradient><radialGradient id="iXLkHkd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 12.825 19.514)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b-r5tpb7o"/><stop offset="1" class="f8fx77o2h"/></radialGradient><radialGradient id="iHcv93c" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 10.934 8.218)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="smyxvjbxd"/><stop offset="1" class="k24mmwbna"/></radialGradient><radialGradient id="i2glQTb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.114 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="nvd1i1bng"/><stop offset="1" class="gwjk8-8_e"/></radialGradient><radialGradient id="i6AMUmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 16.614 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iCgP0me" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.529 4.43)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="v27sfw_5y"/><stop offset="1" class="ob57ysbap"/></radialGradient><radialGradient id="iD0fZCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 10.926 11.811)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="a5v-ibbyp"/><stop offset=".952" class="dhzphmhhv"/></radialGradient><radialGradient id="iJsS8td" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 10.63 11.764)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="gioczw4ny"/><stop offset="1" class="vg-1agb5d"/></radialGradient><radialGradient id="igftqFe" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 14.966 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="lbh256w_i"/><stop offset=".75" class="ao5r4vunm"/></radialGradient><radialGradient id="i4bVd5d" cx="0" cy="0" r="1" gradientTransform="matrix(.52343 .24802 -.3425 .72281 11.38 6.988)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="iWkyl5k" cx="0" cy="0" r="1" gradientTransform="matrix(-.90928 -.01374 .01618 -1.07024 15.288 6.106)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="iV6IVfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.22114 -5.38497 1.51196 -.06209 12.222 7.46)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="iEy8wue" cx="0" cy="0" r="1" gradientTransform="matrix(.01665 .4055 -.65498 .0269 13.064 6.241)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="irUPueK" cx="0" cy="0" r="1" gradientTransform="matrix(1.63205 -.51128 1.06464 3.3984 11.832 3.916)" gradientUnits="userSpaceOnUse"><stop class="tzf255bgc"/><stop offset="1" class="ctuud_14h"/></radialGradient><radialGradient id="ibviQue" cx="0" cy="0" r="1" gradientTransform="matrix(.77228 -.24887 .11807 .36639 14.977 5.99)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="iouvrrf" cx="0" cy="0" r="1" gradientTransform="matrix(.2937 -.01124 .02108 .5509 12.748 6.281)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i1VkCwB" cx="0" cy="0" r="1" gradientTransform="matrix(.26732 -.01023 .02138 .55853 12.568 6.309)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="igv4lBc" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 8.954 7.552)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="j9k9ec-7q"/><stop offset="1" class="tqhat7z5r"/></radialGradient><radialGradient id="ixFzlsC" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.527 10.23)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="vrrbv9blf"/><stop offset="1" class="zs4p_mbda"/></radialGradient><radialGradient id="i8dt67b" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 16.91 11.233)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="vpqlu-bzk"/><stop offset="1" class="chgiqwu_c"/></radialGradient><radialGradient id="iz53cee" cx="0" cy="0" r="1" gradientTransform="rotate(168.111 7.835 8.235)scale(4.55199 6.32638)" gradientUnits="userSpaceOnUse"><stop offset=".635" class="p1be21okm"/><stop offset=".993" class="my6lpcbbn"/></radialGradient><radialGradient id="iAciTGb" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 6.675 29.938)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iq6Q1Wl" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.423 12.192)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iiwTGEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.124 17.331)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="izYIVRu" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.435 22.802)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iRYIdJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.173 18.126)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="idaGKtb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 13.704 17.342)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="ilBnagI" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.77 7.069)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="dbxn0ya4l"/><stop offset="1" class="u8e_1ft3u"/></radialGradient><radialGradient id="iFj3uCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03998 -.1057 .17848 1.75613 14.893 10.831)" gradientUnits="userSpaceOnUse"><stop class="ocwrhdbmt"/><stop offset="1" class="v45x_gblz"/></radialGradient><radialGradient id="iePsxCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 19.656 9.918)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="rxuxfhbms"/><stop offset="1" class="w0jybqera"/></radialGradient><radialGradient id="iliIEGe" cx="0" cy="0" r="1" gradientTransform="rotate(-149.027 6.18 5.213)scale(1.15719 1.60341)" gradientUnits="userSpaceOnUse"><stop class="t6ld_bbob"/><stop offset="1" class="zlcet8bnw"/></radialGradient><radialGradient id="inqL0Pd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 11.86 .42)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ipDfQxd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.727 -9.355)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="iFMDzle" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 20.567 4.249)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iVgiUxb" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.05 4.184)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iESVPYb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.727 -3.655)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><linearGradient id="ioGa9Oe" x1="11.364" x2="9.677" y1="26.108" y2="26.358" gradientUnits="userSpaceOnUse"><stop class="zsdj_cc5a"/><stop offset="1" class="cu51yf-7r"/></linearGradient><linearGradient id="iuk7NUc" x1="8.817" x2="9.536" y1="24.42" y2="24.358" gradientUnits="userSpaceOnUse"><stop class="ibzaseb-i"/><stop offset="1" class="xojzxxboq"/></linearGradient><linearGradient id="iEE49db" x1="11.286" x2="10.856" y1="22.709" y2="22.811" gradientUnits="userSpaceOnUse"><stop class="ljsluudhz"/><stop offset="1" class="b7qlthb7k"/></linearGradient><linearGradient id="iKGodqe" x1="22.817" x2="22.759" y1="24.6" y2="23.377" gradientUnits="userSpaceOnUse"><stop class="n-awbpg6m"/><stop offset="1" class="usr-62t-w"/></linearGradient><linearGradient id="iM0fJwe" x1="22.196" x2="22.196" y1="22.452" y2="23.361" gradientUnits="userSpaceOnUse"><stop class="ebb6qj3ko"/><stop offset="1" class="jw3sj5zvz"/></linearGradient><linearGradient id="iSHdxeb" x1="10.659" x2="10.659" y1="18.631" y2="19.952" gradientUnits="userSpaceOnUse"><stop class="jtac7ua_e"/><stop offset="1" class="p3lmqxq4r"/></linearGradient><linearGradient id="iymZIod" x1="14.982" x2="11.914" y1="6.891" y2="7.209" gradientUnits="userSpaceOnUse"><stop class="zpg97tbto"/><stop offset="1" class="l-3q2ti-u"/></linearGradient><linearGradient id="i4HslBk" x1="14.942" x2="15.064" y1="6.06" y2="6.072" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="iyYUBkb" x1="-.007" x2=".191" y1=".052" y2=".118" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iZLPaDc" x1="15.451" x2="15.28" y1="16.799" y2="15.986" gradientUnits="userSpaceOnUse"><stop offset=".185" class="lkg-r5bvc"/><stop offset="1" class="pdj8m471t"/></linearGradient><linearGradient id="ipSnGqe" x1="9.864" x2="11.395" y1="28.921" y2="28.921" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iiDMUtc" x1="9.427" x2="9.427" y1="29.938" y2="29.616" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="iYUt5rb" x1="25.352" x2="25.949" y1="22.069" y2="23.186" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i21JStR" x1="25.602" x2="26.296" y1="25.019" y2="24.152" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="ikduqNe" x1="27.316" x2="26.923" y1="24.153" y2="24.327" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ir7LSIc" x1="13.336" x2="13.786" y1="17.398" y2="18.466" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="iPDnZpf" x1="21.364" x2="21.177" y1="11.03" y2="10.092" gradientUnits="userSpaceOnUse"><stop offset=".076" class="t12v1gxuw"/><stop offset="1" class="r0caqn-8d"/></linearGradient><linearGradient id="iZ4Xtkb" x1="18.207" x2="17.448" y1="12.178" y2="9.468" gradientUnits="userSpaceOnUse"><stop class="nqy0qlkmp"/><stop offset="1" class="lvqtzth8g"/></linearGradient><linearGradient id="ijXMCuq" x1="25.013" x2="23.016" y1="6.218" y2="6.288" gradientUnits="userSpaceOnUse"><stop offset=".149" class="jjrmc66dk"/><stop offset="1" class="m0_of534w"/></linearGradient><linearGradient id="iDJCtue" x1="24.329" x2="24.328" y1="6.762" y2="6.575" gradientUnits="userSpaceOnUse"><stop class="d1use2f4c"/><stop offset="1" class="iiu2g6sey"/></linearGradient><linearGradient id="iAtGHKc" x1="4.839" x2="7.829" y1="11.436" y2="11.436" gradientUnits="userSpaceOnUse"><stop class="oj5k1ib6q"/><stop offset=".588" class="lvlod4-sl"/></linearGradient><linearGradient id="ir8P1ee" x1="5.91" x2="5.91" y1="12.069" y2="11.624" gradientUnits="userSpaceOnUse"><stop class="li_6k3bgy"/><stop offset="1" class="dradh66ej"/></linearGradient><linearGradient id="ixw5dVd" x1="4.236" x2="6.799" y1="11.876" y2="11.876" gradientUnits="userSpaceOnUse"><stop class="oj5k1ib6q"/><stop offset=".588" class="lvlod4-sl"/></linearGradient><linearGradient id="iqniGgc" x1="5.154" x2="5.154" y1="12.509" y2="12.064" gradientUnits="userSpaceOnUse"><stop class="li_6k3bgy"/><stop offset="1" class="dradh66ej"/></linearGradient><linearGradient id="iXOmxIc" x1="4.645" x2="6.739" y1="12.46" y2="12.46" gradientUnits="userSpaceOnUse"><stop class="oj5k1ib6q"/><stop offset=".588" class="lvlod4-sl"/></linearGradient><linearGradient id="iIMhh4F" x1="5.395" x2="5.395" y1="13.092" y2="12.647" gradientUnits="userSpaceOnUse"><stop class="li_6k3bgy"/><stop offset="1" class="dradh66ej"/></linearGradient><filter id="iIC4wTc" width="4.141" height="6.811" x="15.901" y="15.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23774"/></filter><filter id="iIcxEGb" width="4.813" height="5.556" x="11.671" y="3.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.239216 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23774"/></filter><filter id="i7yjoFc" width="7.47" height="7.518" x="11.195" y="2.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.266667 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23774"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0392157 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23774" result="effect2_innerShadow_3987_23774"/></filter><filter id="iZPeCid" width="1.089" height=".564" x="12.437" y="4.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23774"/></filter><filter id="iFwToTb" width="5.768" height="8.646" x="12.843" y="9.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.352941 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23774"/></filter><filter id="iJmBf6d" width="9.915" height="8.775" x="15.493" y="2.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.121569 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23774"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.176471 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23774" result="effect2_innerShadow_3987_23774"/></filter><filter id="iJ30aFc" width="2.43" height="2.868" x="6.814" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.313726 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23774"/></filter><filter id="is18noe" width="2.065" height=".799" x="4.564" y="11.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23774" stdDeviation=".15"/></filter><filter id="i5mXonv" width="2.506" height=".866" x="4.08" y="11.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23774" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-playing-handball-dark" /></template>
<style>
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

.amd51vbjg {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M16.55 22.745s-.464-1.232-.64-2.275c-.176-1.044 2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.982-3.133 1.16");
}

.ao5r4vunm {
  stop-color: var(--svg-color--584a48, #584A48);
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

.b7qlthb7k {
  stop-color: var(--svg-color--4c2e2e, #4C2E2E);
  stop-opacity: 0;
}

.bc_6ftbdd {
  stop-color: var(--svg-color--ddd9e2, #DDD9E2);
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

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.ctuud_14h {
  stop-color: var(--svg-color--534b49, #534B49);
  stop-opacity: 0;
}

.cu51yf-7r {
  stop-color: var(--svg-color--4f3838, #4F3838);
}

.cvfifdc_c {
  fill: var(--svg-color--241823, #241823);
  d: path("M11.686 4.12c-.202-.42-.018-.877.08-1.036c.366-.712 1.182-.79 1.662-.607c.564.214.734.332 1.622.051c.89-.281 2.002-.21 2.623.773c.621.984.037 2.139.206 2.75c.168.61.578.656.758 1.364c.167.984-.441 1.653-.998 1.821s-1.722.066-2.137-.828c-.68-1.462-.288-2.182-.453-2.923s-.636-.934-1.47-.74c-.98.229-1.623-.069-1.893-.626");
}

.d_6rbhb8w {
  d: path("M13.976 8.014h2.217v3.3h-2.217z");
}

.d1use2f4c {
  stop-color: var(--svg-color--764db5, #764DB5);
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

.dl2hbx40m {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M13.3 7.44c.054.05.057.132.006.184c-.246.253-.614.329-.731.345a.134.134 0 0 1-.153-.11a.13.13 0 0 1 .114-.147c.1-.014.392-.08.574-.266a.14.14 0 0 1 .19-.005");
}

.dradh66ej {
  stop-color: var(--svg-color--412232, #412232);
  stop-opacity: 0;
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

.ebb6qj3ko {
  stop-color: var(--svg-color--4c3431, #4C3431);
}

.efuw_n2tj {
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.804.8 1.416l-.809 2.915a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.322l.809-2.916a1.15 1.15 0 0 1 1.416-.801");
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

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
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

.gioczw4ny {
  stop-color: var(--svg-color--3f2b28, #3F2B28);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwjk8-8_e {
  stop-color: var(--svg-color--9277cc, #9277CC);
}

.gxkjg_bzv {
  fill: var(--svg-color--42292d, #42292D);
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.804-8.137-.703c-.512-.375-.471-.93-.095-1.441");
}

.h3um2wb_s {
  d: path("M11.873 5.512c.007-.833.27-1.244.396-1.367l4.013-.153l.203 3.281c-.842 2.238-3.682 2.442-4.14 1.661c-.457-.78-.48-2.457-.472-3.422");
}

.hrip-ov8c {
  d: path("M12.89 6.296v-.074c-.007-.192-.098-.344-.201-.34s-.182.162-.174.354q.002.038.007.074z");
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.iasiczten {
  stop-color: var(--svg-color--7b46d0, #7B46D0);
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

.jw3sj5zvz {
  stop-color: var(--svg-color--4c3431, #4C3431);
  stop-opacity: 0;
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

.lbtowzzet {
  d: path("M14.95 6.905c-.055.002-.095-.047-.09-.1l.134-1.305c.005-.055.055-.096.109-.083a.76.76 0 0 1 .596.703a.766.766 0 0 1-.75.785");
}

.li_6k3bgy {
  stop-color: var(--svg-color--412232, #412232);
}

.ljsluudhz {
  stop-color: var(--svg-color--4c2e2e, #4C2E2E);
}

.lkg-r5bvc {
  stop-color: var(--svg-color--705dac, #705DAC);
}

.ln1i_4nqy {
  rx: 0.069px;
  ry: 0.091px;
}

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.lvlod4-sl {
  stop-color: var(--svg-color--42292d, #42292D);
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

.n-awbpg6m {
  stop-color: var(--svg-color--42273f, #42273F);
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

.ndsrk3fql {
  fill: var(--svg-color--584444, #584444);
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.ne985-vqe {
  stop-color: var(--svg-color--c3b8c5, #C3B8C5);
  stop-opacity: 0;
}

.np4vetbdb {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M12.958 5.222a1 1 0 0 0-.233-.007a.16.16 0 0 1-.186-.128a.156.156 0 0 1 .133-.18c.076-.011.2-.013.337.008c.138.02.301.068.446.163a.153.153 0 0 1 .043.216a.165.165 0 0 1-.224.041a.8.8 0 0 0-.316-.113");
}

.npcei-brr {
  fill: var(--svg-color--8060b2, #8060B2);
  d: path("m19.732 11.598l-.61-2.962l-3.005.597a1.483 1.483 0 0 0 .55 2.914z");
}

.nqy0qlkmp {
  stop-color: var(--svg-color--6540ac, #6540AC);
}

.nsr274b2n {
  d: path("M13.101 6.29v-.004c-.014-.332-.172-.596-.354-.59c-.182.008-.319.283-.305.615v.004z");
}

.nvd1i1bng {
  stop-color: var(--svg-color--9277cc, #9277CC);
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

.ocwrhdbmt {
  stop-color: var(--svg-color--9276c2, #9276C2);
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

.pdj8m471t {
  stop-color: var(--svg-color--705dac, #705DAC);
  stop-opacity: 0;
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

.r0caqn-8d {
  stop-color: var(--svg-color--452931, #452931);
  stop-opacity: 0;
}

.rfat3lb_o {
  fill: var(--svg-color--493030, #493030);
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.804.8 1.416l-.809 2.915a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.322l.809-2.916a1.15 1.15 0 0 1 1.416-.801");
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
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

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.svo9k1svp {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.451 6.316l1.063-.041c-.017-.407-.268-.727-.561-.716s-.518.35-.502.757");
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

.u_7vzbbil {
  stop-color: var(--svg-color--886ac6, #886AC6);
}

.u07rntblp {
  stop-color: var(--svg-color--6e46c0, #6E46C0);
}

.u8e_1ft3u {
  stop-color: var(--svg-color--4d3432, #4D3432);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uqvb40xso {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.532 5.743c-.147-.13-.382-.153-.482-.148l.346.472c.157-.015.319-.16.136-.324");
}

.usr-62t-w {
  stop-color: var(--svg-color--472b33, #472B33);
  stop-opacity: 0;
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

.v45x_gblz {
  stop-color: var(--svg-color--8667c0, #8667C0);
  stop-opacity: 0;
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

.vvbm3s71t {
  d: path("M11.686 4.12c-.202-.42-.018-.877.08-1.036c.366-.712 1.182-.79 1.662-.607c.564.214.734.332 1.622.051c.89-.281 2.002-.21 2.623.773c.621.984.037 2.139.206 2.75c.168.61.578.656.758 1.364c.167.984-.441 1.653-.998 1.821s-1.722.066-2.137-.828c-.68-1.462-.288-2.182-.453-2.923s-.636-.934-1.47-.74c-.98.229-1.623-.069-1.893-.626");
}

.vx88q5bse {
  stop-color: var(--svg-color--484083, #484083);
  stop-opacity: 0;
}

.w0jybqera {
  stop-color: var(--svg-color--8264b7, #8264B7);
  stop-opacity: 0;
}

.xojzxxboq {
  stop-color: var(--svg-color--574241, #574241);
  stop-opacity: 0;
}

.ycb1huo4n {
  stop-color: var(--svg-color--c2aab6, #C2AAB6);
}

.yl5-z06iv {
  d: path("M11.673 6.522c.162-.159.24-.39.258-.485l.193-.007l.048 1.167c-.225.151-.556.141-.663-.068c-.092-.179-.038-.408.164-.607");
}

.zguchrbop {
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.zlcet8bnw {
  stop-color: var(--svg-color--6944a2, #6944A2);
}

.zpg97tbto {
  stop-color: var(--svg-color--432b2f, #432B2F);
}

.zs4p_mbda {
  stop-color: var(--svg-color--745fa7, #745FA7);
  stop-opacity: 0;
}

.zsdj_cc5a {
  stop-color: var(--svg-color--523939, #523939);
}

</style>
