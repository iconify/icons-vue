<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ibTjxvc)" class="q12x_3brx"/><path fill="url(#iO9SMcd)" class="q12x_3brx"/><path fill="url(#iBzBIDb)" class="q12x_3brx"/><path class="cnnnte2db"/><path fill="url(#iEzhBge)" class="zguchrbop"/><path fill="url(#iu3zVQd)" class="zguchrbop"/><path class="mr8h2bixv"/><path fill="url(#ixKKdrs)" class="g9d0ovbvp"/><path fill="url(#iKx9G5K)" class="g9d0ovbvp"/><path fill="url(#ijqVH7d)" class="g9d0ovbvp"/><path fill="url(#i7Gr6le)" class="g9d0ovbvp"/><path fill="url(#iXLkHkd)" class="qum9srb-r"/><path fill="url(#iHcv93c)" class="qum9srb-r"/><path fill="url(#i2glQTb)" class="qum9srb-r"/><path fill="url(#iSHdxeb)" class="qum9srb-r"/><g filter="url(#i8OChLe)"><path class="amd51vbjg"/><path fill="url(#i6AMUmc)" class="mfs1vbcha"/></g><path clip-rule="evenodd" class="oayv1_mln"/><path fill="url(#iWNidyb)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#i7LrMkc)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#ikrBelc)" clip-rule="evenodd" class="sp0u-8bbb"/><path fill="url(#ipyLVvc)" transform="rotate(-23.31 13.976 8.014)" class="d_6rbhb8w"/><path fill="url(#icz7T9u)" class="ndqhgqbwr"/><path fill="url(#iA3qaKb)" class="ndqhgqbwr"/><g filter="url(#iEvwBRb)"><path fill="url(#ixOZQzv)" class="z7mpm4bjw"/><path fill="url(#if60Dae)" class="z7mpm4bjw"/><path fill="url(#itzDGJc)" class="z7mpm4bjw"/><path fill="url(#iuuLy4c)" class="z7mpm4bjw"/></g><g filter="url(#iLEZpqc)"><path class="qerv3s3qb"/><path fill="url(#iy5GX4c)" class="xpqfewb9n"/></g><path fill="url(#iC1JqPc)" class="o303cub3q"/><path fill="url(#imV52Je)" class="o303cub3q"/><path fill="url(#iLDiCxc)" class="o303cub3q"/><path class="zql73c_7j"/><path clip-rule="evenodd" class="afu1v3buw"/><g filter="url(#iOUkrvU)"><path clip-rule="evenodd" class="z5tk927wo"/></g><path class="f5fz9cc3l"/><path fill="url(#iOAsfWn)" class="pex38ubkr"/><path fill="url(#ig0Fvtc)" class="niwch6bsi"/><ellipse fill="url(#i8KUiDs)" transform="rotate(22.002 12.794 6.1)" class="sb9y6n21t"/><g filter="url(#imkbHQb)"><path class="e9_t29bue"/><path fill="url(#igv4lBc)" class="f1u8ijb3m"/><path fill="url(#ixFzlsC)" class="f1u8ijb3m"/><path fill="url(#iZLPaDc)" class="f1u8ijb3m"/><path fill="url(#i8dt67b)" class="f1u8ijb3m"/><path fill="url(#iz53cee)" class="f1u8ijb3m"/></g><path fill="url(#ipSnGqe)" class="vjh3yqznr"/><path fill="url(#iAciTGb)" class="vjh3yqznr"/><path fill="url(#iiDMUtc)" class="vjh3yqznr"/><path fill="url(#iq6Q1Wl)" class="vjh3yqznr"/><path class="ppv4posfy"/><path fill="url(#iYUt5rb)" class="ol51zcmaj"/><path fill="url(#i21JStR)" class="ol51zcmaj"/><path fill="url(#ikduqNe)" class="ol51zcmaj"/><path class="kmd3qcb-j"/><path fill="url(#iiwTGEe)" class="e0lhu47_k"/><path fill="url(#izYIVRu)" class="e0lhu47_k"/><path fill="url(#iRYIdJc)" class="e0lhu47_k"/><path fill="url(#ir7LSIc)" class="e0lhu47_k"/><path fill="url(#idaGKtb)" class="e0lhu47_k"/><g filter="url(#in4neUb)"><path clip-rule="evenodd" class="f_lldv3no"/></g><path fill="url(#isuRvQb)" clip-rule="evenodd" class="yzbfo0edn"/><path fill="url(#i1cHlFe)" clip-rule="evenodd" class="yzbfo0edn"/><path class="npcei-brr"/><path fill="url(#iZ4Xtkb)" class="jmlii5bid"/><path fill="url(#iFj3uCb)" class="jmlii5bid"/><path fill="url(#iePsxCb)" class="jmlii5bid"/><rect fill="url(#ijXMCuq)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><rect fill="url(#iDJCtue)" transform="rotate(16.21 22.49 5.391)" class="b6kb336ra"/><path fill="url(#itKrLed)" class="mqryp-bup"/><path fill="url(#iAenrxd)" class="vtxj36boz"/><path fill="url(#iUkHZld)" class="vtxj36boz"/><path fill="url(#ieEkc9c)" class="t3ncs1j8m"/><path fill="url(#iPBfHBe)" class="t3ncs1j8m"/><g filter="url(#iZ8zooE)"><path fill="url(#iliIEGe)" class="pcwcq6ykk"/></g><path fill="url(#inqL0Pd)" class="pb93aprhh"/><path fill="url(#ipDfQxd)" class="pb93aprhh"/><path fill="url(#iFMDzle)" class="pb93aprhh"/><path fill="url(#iVgiUxb)" class="pb93aprhh"/><path fill="url(#iESVPYb)" class="pb93aprhh"/><g filter="url(#itEg1yd)"><rect class="n54evmbvw"/></g><g filter="url(#iUq0Skd)"><rect class="t3-in9w4l"/></g><defs><radialGradient id="ixKKdrs" cx="0" cy="0" r="1" gradientTransform="matrix(.61864 2.14418 -1.49974 .4327 18.926 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="c4e5_obhh"/><stop offset="1" class="mw5xv5bly"/></radialGradient><radialGradient id="iKx9G5K" cx="0" cy="0" r="1" gradientTransform="matrix(-.57157 2.94815 -3.2663 -.63325 18.88 22.28)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="el1f73rff"/><stop offset="1" class="iasiczten"/></radialGradient><radialGradient id="ijqVH7d" cx="0" cy="0" r="1" gradientTransform="matrix(.80677 2.5012 -1.15566 .37276 16.338 22.544)" gradientUnits="userSpaceOnUse"><stop class="u_7vzbbil"/><stop offset="1" class="n4e7hibnk"/></radialGradient><radialGradient id="i7Gr6le" cx="0" cy="0" r="1" gradientTransform="rotate(71.565 -6.364 23.576)scale(.54352 3.09962)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="u07rntblp"/><stop offset="1" class="tbt6sb7pf"/></radialGradient><radialGradient id="iXLkHkd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80517 2.25001 -1.4808 -2.5043 12.825 19.514)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b-r5tpb7o"/><stop offset="1" class="f8fx77o2h"/></radialGradient><radialGradient id="iHcv93c" cx="0" cy="0" r="1" gradientTransform="rotate(-134.88 10.934 8.218)scale(2.4697 2.5678)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="smyxvjbxd"/><stop offset="1" class="k24mmwbna"/></radialGradient><radialGradient id="i2glQTb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62085 -1.17187 1.5004 -4.6359 12.114 21.795)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="nvd1i1bng"/><stop offset="1" class="gwjk8-8_e"/></radialGradient><radialGradient id="i6AMUmc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 16.614 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iWNidyb" cx="0" cy="0" r="1" gradientTransform="rotate(-137.447 9.529 4.43)scale(2.58772 3.67383)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="cw_dmv8-u"/><stop offset="1" class="yo2o8qb-v"/></radialGradient><radialGradient id="i7LrMkc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 3.04688 -8.2061 -.08422 10.926 11.811)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="j12jqkbuh"/><stop offset=".952" class="ihyx1abhg"/></radialGradient><radialGradient id="ikrBelc" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 1.15597 -4.12712 -.44629 10.63 11.764)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="a1lnoq-qe"/><stop offset="1" class="v-83r_bol"/></radialGradient><radialGradient id="ipyLVvc" cx="0" cy="0" r="1" gradientTransform="matrix(.11892 1.97106 -1.84849 .11153 14.966 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="oxw2g-jck"/><stop offset=".75" class="i0vk4ibxw"/></radialGradient><radialGradient id="icz7T9u" cx="0" cy="0" r="1" gradientTransform="rotate(25.806 -9.904 28.824)scale(.58152 .82083)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="iA3qaKb" cx="0" cy="0" r="1" gradientTransform="rotate(-114.991 8.396 -.073)scale(.33837 .50781)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="if60Dae" cx="0" cy="0" r="1" gradientTransform="matrix(-.9069 -.00905 .01104 -1.1057 15.451 6.253)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="itzDGJc" cx="0" cy="0" r="1" gradientTransform="rotate(-92.608 9.865 -2.092)scale(5.56746 2.16326)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="iuuLy4c" cx="0" cy="0" r="1" gradientTransform="matrix(.01908 .4188 -.65312 .02975 13.236 6.404)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="iy5GX4c" cx="0" cy="0" r="1" gradientTransform="matrix(1.62452 -.5378 1.15248 3.48132 11.993 4.01)" gradientUnits="userSpaceOnUse"><stop class="zy9nvz9pf"/><stop offset="1" class="xfcyplbyz"/></radialGradient><radialGradient id="iC1JqPc" cx="0" cy="0" r="1" gradientTransform="matrix(.76867 -.26163 .1277 .37518 15.121 6.15)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="imV52Je" cx="0" cy="0" r="1" gradientTransform="matrix(.29987 1.2538 -1.30652 .31248 15.14 5.827)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="iOAsfWn" cx="0" cy="0" r="1" gradientTransform="matrix(.29316 -.01335 .02594 .56957 12.921 6.448)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ig0Fvtc" cx="0" cy="0" r="1" gradientTransform="matrix(.26803 -.0122 .02642 .58004 12.742 6.48)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="igv4lBc" cx="0" cy="0" r="1" gradientTransform="rotate(176.945 8.954 7.552)scale(2.5113 5.07652)" gradientUnits="userSpaceOnUse"><stop class="j9k9ec-7q"/><stop offset="1" class="tqhat7z5r"/></radialGradient><radialGradient id="ixFzlsC" cx="0" cy="0" r="1" gradientTransform="rotate(128.721 6.527 10.23)scale(1.69155 2.05757)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="vrrbv9blf"/><stop offset="1" class="zs4p_mbda"/></radialGradient><radialGradient id="i8dt67b" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 -.9375 .73922 1.40453 16.91 11.233)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="vpqlu-bzk"/><stop offset="1" class="chgiqwu_c"/></radialGradient><radialGradient id="iz53cee" cx="0" cy="0" r="1" gradientTransform="rotate(168.111 7.835 8.235)scale(4.55199 6.32638)" gradientUnits="userSpaceOnUse"><stop offset=".635" class="p1be21okm"/><stop offset=".993" class="my6lpcbbn"/></radialGradient><radialGradient id="iAciTGb" cx="0" cy="0" r="1" gradientTransform="matrix(.79858 0 0 1.52692 6.675 29.938)" gradientUnits="userSpaceOnUse"><stop class="jjj62-byh"/><stop offset="1" class="m5_tnryam"/></radialGradient><radialGradient id="iq6Q1Wl" cx="0" cy="0" r="1" gradientTransform="rotate(-120.376 13.423 12.192)scale(2.19385 8.43682)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="q8c7r9fut"/><stop offset="1" class="tbe0sc-ij"/></radialGradient><radialGradient id="iiwTGEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.9511 4.1682 -15.86338 7.42555 14.124 17.331)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="izYIVRu" cx="0" cy="0" r="1" gradientTransform="matrix(1.49503 -1.88245 6.26212 4.97335 13.435 22.802)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iRYIdJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31612 .83934 -.79838 -2.2031 18.173 18.126)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="idaGKtb" cx="0" cy="0" r="1" gradientTransform="matrix(2.06572 -.43346 .05445 .25947 13.704 17.342)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="i1cHlFe" cx="0" cy="0" r="1" gradientTransform="rotate(136.224 11.77 7.069)scale(1.98747 1.74972)" gradientUnits="userSpaceOnUse"><stop class="brfm5ympt"/><stop offset="1" class="tf96tsg_a"/></radialGradient><radialGradient id="iFj3uCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03998 -.1057 .17848 1.75613 14.893 10.831)" gradientUnits="userSpaceOnUse"><stop class="ocwrhdbmt"/><stop offset="1" class="v45x_gblz"/></radialGradient><radialGradient id="iePsxCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95223 .19197 -.29995 -1.48786 19.656 9.918)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="rxuxfhbms"/><stop offset="1" class="w0jybqera"/></radialGradient><radialGradient id="itKrLed" cx="0" cy="0" r="1" gradientTransform="matrix(3.40685 0 0 1.20429 4.423 11.436)" gradientUnits="userSpaceOnUse"><stop class="gym_2j3rc"/><stop offset=".498" class="qzpft6b_x"/></radialGradient><radialGradient id="iliIEGe" cx="0" cy="0" r="1" gradientTransform="rotate(-149.027 6.18 5.213)scale(1.15719 1.60341)" gradientUnits="userSpaceOnUse"><stop class="t6ld_bbob"/><stop offset="1" class="zlcet8bnw"/></radialGradient><radialGradient id="inqL0Pd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.229 11.86 .42)scale(2.4032 2.78155)" gradientUnits="userSpaceOnUse"><stop class="bc_6ftbdd"/><stop offset="1" class="t54cbcb-z"/></radialGradient><radialGradient id="ipDfQxd" cx="0" cy="0" r="1" gradientTransform="rotate(-82.624 14.727 -9.355)scale(2.9305 5.10486)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lasxztb-e"/><stop offset="1" class="ea0c68b1a"/></radialGradient><radialGradient id="iFMDzle" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.12411 .12476 1.63348 20.567 4.249)" gradientUnits="userSpaceOnUse"><stop class="qh9tdvimg"/><stop offset="1" class="ne985-vqe"/></radialGradient><radialGradient id="iVgiUxb" cx="0" cy="0" r="1" gradientTransform="rotate(158.971 11.05 4.184)scale(2.61012)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mge9r1s9g"/><stop offset=".992" class="ycb1huo4n"/></radialGradient><radialGradient id="iESVPYb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.144 12.727 -3.655)scale(3.34058)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="qmcjcvbdo"/><stop offset="1" class="s-7nhybnh"/></radialGradient><linearGradient id="ibTjxvc" x1="11.364" x2="9.677" y1="26.108" y2="26.358" gradientUnits="userSpaceOnUse"><stop class="d3738qb8u"/><stop offset="1" class="ttypkojrk"/></linearGradient><linearGradient id="iO9SMcd" x1="8.817" x2="9.536" y1="24.42" y2="24.358" gradientUnits="userSpaceOnUse"><stop class="jha-984sk"/><stop offset="1" class="strkjwbkt"/></linearGradient><linearGradient id="iBzBIDb" x1="11.286" x2="10.856" y1="22.709" y2="22.811" gradientUnits="userSpaceOnUse"><stop class="e4gncgnqd"/><stop offset="1" class="divg9r_of"/></linearGradient><linearGradient id="iEzhBge" x1="22.817" x2="22.759" y1="24.6" y2="23.377" gradientUnits="userSpaceOnUse"><stop class="il9cx6b8o"/><stop offset="1" class="cll88gg-t"/></linearGradient><linearGradient id="iu3zVQd" x1="22.196" x2="22.196" y1="22.452" y2="23.361" gradientUnits="userSpaceOnUse"><stop class="cror3zfgh"/><stop offset="1" class="odrq36bum"/></linearGradient><linearGradient id="iSHdxeb" x1="10.659" x2="10.659" y1="18.631" y2="19.952" gradientUnits="userSpaceOnUse"><stop class="jtac7ua_e"/><stop offset="1" class="p3lmqxq4r"/></linearGradient><linearGradient id="ixOZQzv" x1="15.152" x2="12.092" y1="7.064" y2="7.388" gradientUnits="userSpaceOnUse"><stop class="xwzzv0ryq"/><stop offset="1" class="l3_0v7cyw"/></linearGradient><linearGradient id="iLDiCxc" x1="15.066" x2="15.226" y1="6.227" y2="6.232" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="i8KUiDs" x1="12.718" x2="12.918" y1="6.058" y2="6.123" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iZLPaDc" x1="15.451" x2="15.28" y1="16.799" y2="15.986" gradientUnits="userSpaceOnUse"><stop offset=".185" class="lkg-r5bvc"/><stop offset="1" class="pdj8m471t"/></linearGradient><linearGradient id="ipSnGqe" x1="9.864" x2="11.395" y1="28.921" y2="28.921" gradientUnits="userSpaceOnUse"><stop class="q1yj_xkrc"/><stop offset="1" class="a8jjc_bge"/></linearGradient><linearGradient id="iiDMUtc" x1="9.427" x2="9.427" y1="29.938" y2="29.616" gradientUnits="userSpaceOnUse"><stop class="c2ukjabcr"/><stop offset="1" class="sew1y7bbn"/></linearGradient><linearGradient id="iYUt5rb" x1="25.352" x2="25.949" y1="22.069" y2="23.186" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i21JStR" x1="25.602" x2="26.296" y1="25.019" y2="24.152" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="ikduqNe" x1="27.316" x2="26.923" y1="24.153" y2="24.327" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ir7LSIc" x1="13.336" x2="13.786" y1="17.398" y2="18.466" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="isuRvQb" x1="21.364" x2="21.177" y1="11.03" y2="10.092" gradientUnits="userSpaceOnUse"><stop offset=".076" class="t2um5owbu"/><stop offset="1" class="co5izhbpm"/></linearGradient><linearGradient id="iZ4Xtkb" x1="18.207" x2="17.448" y1="12.178" y2="9.468" gradientUnits="userSpaceOnUse"><stop class="nqy0qlkmp"/><stop offset="1" class="lvqtzth8g"/></linearGradient><linearGradient id="ijXMCuq" x1="25.013" x2="23.016" y1="6.218" y2="6.288" gradientUnits="userSpaceOnUse"><stop offset=".149" class="jjrmc66dk"/><stop offset="1" class="m0_of534w"/></linearGradient><linearGradient id="iDJCtue" x1="24.329" x2="24.328" y1="6.762" y2="6.575" gradientUnits="userSpaceOnUse"><stop class="d1use2f4c"/><stop offset="1" class="iiu2g6sey"/></linearGradient><linearGradient id="iAenrxd" x1="4.236" x2="6.799" y1="11.876" y2="11.876" gradientUnits="userSpaceOnUse"><stop class="wxhwgwbkv"/><stop offset=".588" class="j8i1teydm"/></linearGradient><linearGradient id="iUkHZld" x1="5.154" x2="5.154" y1="12.509" y2="12.064" gradientUnits="userSpaceOnUse"><stop class="b46w5gb0s"/><stop offset="1" class="a6qwprbav"/></linearGradient><linearGradient id="ieEkc9c" x1="4.645" x2="6.739" y1="12.46" y2="12.46" gradientUnits="userSpaceOnUse"><stop class="wxhwgwbkv"/><stop offset=".588" class="j8i1teydm"/></linearGradient><linearGradient id="iPBfHBe" x1="5.395" x2="5.395" y1="13.092" y2="12.647" gradientUnits="userSpaceOnUse"><stop class="b46w5gb0s"/><stop offset="1" class="a6qwprbav"/></linearGradient><filter id="i8OChLe" width="4.141" height="6.811" x="15.901" y="15.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23780"/></filter><filter id="iEvwBRb" width="4.81" height="5.75" x="11.843" y="3.862" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.329412 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23780"/></filter><filter id="iLEZpqc" width="7.475" height="7.74" x="11.356" y="2.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.294118 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23780"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.172549 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23780" result="effect2_innerShadow_3987_23780"/></filter><filter id="iOUkrvU" width="1.088" height=".576" x="12.603" y="5.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23780"/></filter><filter id="imkbHQb" width="5.768" height="8.646" x="12.843" y="9.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.352941 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23780"/></filter><filter id="in4neUb" width="9.915" height="8.775" x="15.493" y="2.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.34902 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23780"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.435294 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23780" result="effect2_innerShadow_3987_23780"/></filter><filter id="iZ8zooE" width="2.43" height="2.868" x="6.814" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.313726 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23780"/></filter><filter id="itEg1yd" width="2.065" height=".799" x="4.564" y="11.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23780" stdDeviation=".15"/></filter><filter id="iUq0Skd" width="2.506" height=".866" x="4.08" y="11.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23780" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-playing-handball-medium" /></template>
<style>
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

.afu1v3buw {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.478 7.642c.054.05.058.135.007.19c-.244.262-.61.343-.727.36a.134.134 0 0 1-.04-.265c.1-.015.39-.084.57-.278a.134.134 0 0 1 .19-.007");
}

.amd51vbjg {
  fill: var(--svg-color--97919e, #97919E);
  d: path("M16.55 22.745s-.464-1.232-.64-2.275c-.176-1.044 2.336-4.437 2.336-4.437c.95 1.49 1.296 2.635 1.641 4.012c.209.833.264 1.08-.204 1.539c-.637.569-2.49.982-3.133 1.16");
}

.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.b-r5tpb7o {
  stop-color: var(--svg-color--8663d2, #8663D2);
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

.brfm5ympt {
  stop-color: var(--svg-color--c09b80, #C09B80);
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

.d1use2f4c {
  stop-color: var(--svg-color--764db5, #764DB5);
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

.e0lhu47_k {
  d: path("M18.3 15.613s-4.632 1.787-7.165 3.046a17.6 17.6 0 0 0 1.804 3.37a.92.92 0 0 0 1.198.278c1.085-.572 2.045-1.031 3.183-1.726c2.04-1.244 1.784-2.567 1.663-3.264c-.105-.604-.492-1.322-.684-1.704");
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.e4gncgnqd {
  stop-color: var(--svg-color--a1736a, #A1736A);
}

.e9_t29bue {
  fill: var(--svg-color--745ab0, #745AB0);
  d: path("m15.493 9.4l.674-.168c.233-.059.476-.07.713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.ea0c68b1a {
  stop-color: var(--svg-color--b9b1c0, #B9B1C0);
  stop-opacity: 0;
}

.el1f73rff {
  stop-color: var(--svg-color--7b46d0, #7B46D0);
  stop-opacity: 0;
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.f_lldv3no {
  fill: var(--svg-color--a8816c, #A8816C);
  fill-rule: evenodd;
  d: path("M24.316 3.473c.611.17.97.803.8 1.415l-.809 2.916a4.15 4.15 0 0 1-3.214 2.966l-4.232.815a1.15 1.15 0 1 1-.435-2.259l4.232-.814a1.85 1.85 0 0 0 1.433-1.323l.809-2.915a1.15 1.15 0 0 1 1.416-.801");
}

.f1u8ijb3m {
  d: path("m15.493 9.4l.674-.168c.233-.059.476-.07.713-.03l1.53 2.194c-.642 1.685-.594 3.034-.097 4.255l-4.898 2.074c-.855-2.918-.665-5.398 0-6.555c.597-1.12 1.426-1.582 2.078-1.77");
}

.f5fz9cc3l {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.625 6.485l1.06-.049c-.02-.42-.273-.749-.565-.736c-.293.014-.514.365-.495.785");
}

.f8fx77o2h {
  stop-color: var(--svg-color--845fcd, #845FCD);
}

.ft5dv1b6b {
  fill: none;
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

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwjk8-8_e {
  stop-color: var(--svg-color--9277cc, #9277CC);
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

.iasiczten {
  stop-color: var(--svg-color--7b46d0, #7B46D0);
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.ihyx1abhg {
  stop-color: var(--svg-color--995b7a, #995B7A);
}

.iiu2g6sey {
  stop-color: var(--svg-color--764db5, #764DB5);
  stop-opacity: 0;
}

.il9cx6b8o {
  stop-color: var(--svg-color--985b84, #985B84);
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

.j9k9ec-7q {
  stop-color: var(--svg-color--8e7ec2, #8E7EC2);
}

.jha-984sk {
  stop-color: var(--svg-color--c59685, #C59685);
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

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
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

.n4e7hibnk {
  stop-color: var(--svg-color--886ac6, #886AC6);
  stop-opacity: 0;
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

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ndqhgqbwr {
  d: path("M11.85 6.702c.16-.165.236-.403.254-.502l.193-.009l.055 1.206c-.224.157-.554.15-.662-.066c-.093-.185-.04-.422.16-.629");
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

.niwch6bsi {
  d: path("m13.064 6.465l.001-.078c-.009-.199-.1-.356-.205-.352s-.18.17-.172.37l.008.076z");
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

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.o303cub3q {
  d: path("m15.001 7.095l.144-1.553A.78.78 0 0 1 15 7.095");
}

.oayv1_mln {
  fill: var(--svg-color--a27368, #A27368);
  fill-rule: evenodd;
  d: path("M6.035 11.676a1.15 1.15 0 0 1 1.607-.247c1.178.864 3.405 1.382 5.632.316a1.15 1.15 0 1 1 .993 2.075c-3.032 1.45-6.188.804-8.137-.703c-.512-.375-.471-.93-.095-1.441");
}

.ocwrhdbmt {
  stop-color: var(--svg-color--9276c2, #9276C2);
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

.oxw2g-jck {
  stop-color: var(--svg-color--7a4e3a, #7A4E3A);
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

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.pex38ubkr {
  d: path("M13.274 6.455v-.004c-.016-.344-.176-.615-.357-.607c-.182.008-.316.293-.3.637v.004z");
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

.qerv3s3qb {
  fill: var(--svg-color--52333b, #52333B);
  d: path("M11.85 4.22c-.205-.431-.024-.905.072-1.069c.36-.738 1.174-.823 1.654-.638c.564.218.734.34 1.618.044s1.995-.23 2.62.783c.626 1.012.05 2.21.222 2.84s.581.674.765 1.404c.172 1.016-.43 1.711-.984 1.887c-.555.177-1.717.079-2.137-.842c-.687-1.507-.3-2.253-.47-3.017c-.169-.765-.64-.962-1.47-.756c-.976.242-1.62-.062-1.89-.636");
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

.qzpft6b_x {
  stop-color: var(--svg-color--9d7163, #9D7163);
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
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

.sb9y6n21t {
  cx: 12.794px;
  cy: 6.099px;
  rx: 0.069px;
  ry: 0.094px;
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

.tf96tsg_a {
  stop-color: var(--svg-color--b48a76, #B48A76);
  stop-opacity: 0;
}

.tqhat7z5r {
  stop-color: var(--svg-color--8e7ec2, #8E7EC2);
  stop-opacity: 0;
}

.ttypkojrk {
  stop-color: var(--svg-color--b07d78, #B07D78);
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

.v-83r_bol {
  stop-color: var(--svg-color--906b55, #906B55);
  stop-opacity: 0;
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.v45x_gblz {
  stop-color: var(--svg-color--8667c0, #8667C0);
  stop-opacity: 0;
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

.wxhwgwbkv {
  stop-color: var(--svg-color--bf9482, #BF9482);
}

.xfcyplbyz {
  stop-color: var(--svg-color--654e4b, #654E4B);
  stop-opacity: 0;
}

.xpqfewb9n {
  d: path("M11.85 4.22c-.205-.431-.024-.905.072-1.069c.36-.738 1.174-.823 1.654-.638c.564.218.734.34 1.618.044s1.995-.23 2.62.783c.626 1.012.05 2.21.222 2.84s.581.674.765 1.404c.172 1.016-.43 1.711-.984 1.887c-.555.177-1.717.079-2.137-.842c-.687-1.507-.3-2.253-.47-3.017c-.169-.765-.64-.962-1.47-.756c-.976.242-1.62-.062-1.89-.636");
}

.xwzzv0ryq {
  stop-color: var(--svg-color--a87a72, #A87A72);
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

.z5tk927wo {
  fill: var(--svg-color--513a3c, #513A3C);
  fill-rule: evenodd;
  d: path("M13.124 5.352a.8.8 0 0 0-.233-.006a.16.16 0 1 1-.055-.317c.076-.013.2-.016.337.005s.3.068.446.166a.161.161 0 0 1-.18.267a.8.8 0 0 0-.315-.115");
}

.z7mpm4bjw {
  d: path("M12.043 5.658c.002-.86.262-1.287.387-1.414l4.002-.183l.221 3.39c-.825 2.316-3.657 2.543-4.118 1.74c-.46-.804-.495-2.536-.492-3.533");
}

.zguchrbop {
  d: path("m24.747 24.295l-4.774.703l-.328-2.546l5.215.148z");
}

.zlcet8bnw {
  stop-color: var(--svg-color--6944a2, #6944A2);
}

.zql73c_7j {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.678 5.888c-.148-.135-.383-.156-.482-.15l.348.485c.157-.016.317-.168.133-.335");
}

.zs4p_mbda {
  stop-color: var(--svg-color--745fa7, #745FA7);
  stop-opacity: 0;
}

.zy9nvz9pf {
  stop-color: var(--svg-color--654e4b, #654E4B);
}

</style>
