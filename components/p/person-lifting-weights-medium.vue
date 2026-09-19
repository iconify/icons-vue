<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixv7lUK)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#ibh7zkc)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#ilPGyGb)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#igpeLEb)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#iZP7Azb)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iKvJh5W)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iyDDmMZ)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iLWRW9Q)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><g filter="url(#iFyaoLb)"><path fill="url(#iVAnGZb)" class="q1wg51bmi"/><path fill="url(#i0AhJLc)" class="q1wg51bmi"/><path fill="url(#i8igjWE)" class="q1wg51bmi"/><path fill="url(#il5AC0d)" class="q1wg51bmi"/></g><g filter="url(#iI1jdtd)"><rect fill="url(#iE3hHec)" class="uywq_y1iv"/><rect fill="url(#i1HNLPr)" class="uywq_y1iv"/></g><g filter="url(#iCsqOZf)"><path stroke="url(#ibRzype)" class="ijj045bhz"/></g><path fill="url(#i932lNb)" class="g4offrb0h"/><path fill="url(#iEtNZBc)" class="g4offrb0h"/><path fill="url(#iqtoKIb)" class="nm-q8ebbk"/><path fill="url(#iryO7ae)" class="nm-q8ebbk"/><path fill="url(#i3LYUMP)" class="z0ggixb3q"/><path fill="url(#i5vhkic)" class="z0ggixb3q"/><path fill="url(#ibt35DW)" class="tzfcre5-h"/><path fill="url(#iYPgz9b)" class="tzfcre5-h"/><circle fill="url(#idahUab)" class="gknucfb8h"/><circle fill="url(#i5AGEFd)" class="gknucfb8h"/><path fill="url(#iGqqmCd)" class="y0nqeezxq"/><path fill="url(#i9Wexoc)" class="y0nqeezxq"/><path fill="url(#iuHQnxe)" class="l2at7otgu"/><path fill="url(#ipB7uYb)" class="l2at7otgu"/><path fill="url(#iUSh68c)" class="ufmuzl7ni"/><path fill="url(#i07co6d)" class="ufmuzl7ni"/><path fill="url(#igNtrxc)" class="rh3jx3c9i"/><path fill="url(#iEain8Z)" class="rh3jx3c9i"/><circle fill="url(#ioBrRPd)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><circle fill="url(#i5G2Nwe)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><g filter="url(#igk9cre)"><path fill="url(#i7nMPid)" class="em3ofwhyw"/><path fill="url(#iuNDXud)" class="em3ofwhyw"/><path fill="url(#iFLqZSc)" class="em3ofwhyw"/></g><g filter="url(#i021DBe)"><path fill="url(#ii9TU6b)" class="qno0gyhtd"/><path fill="url(#iAW9NPa)" class="qno0gyhtd"/><path fill="url(#irsbW7b)" class="qno0gyhtd"/></g><g filter="url(#iQltiEe)"><path fill="url(#iMd3cGY)" class="tphhgybtp"/><path fill="url(#iKoLy8d)" class="tphhgybtp"/></g><g filter="url(#igUDKCc)"><path fill="url(#ipt2RNb)" class="x9t-2zb_r"/><path fill="url(#ijEmnZt)" class="x9t-2zb_r"/><path fill="url(#iqv6bwe)" class="x9t-2zb_r"/></g><g filter="url(#il15ikc)"><path fill="url(#i1fW1XY)" class="g5fg-5cgy"/><path fill="url(#iL5td6D)" class="g5fg-5cgy"/></g><g filter="url(#ispG5Gy)"><path fill="url(#iaaWRue)" class="uv_bhvydh"/></g><g filter="url(#i2whx4b)"><path fill="url(#imrVfMc)" class="u6_y93pge"/><path fill="url(#iID6PAd)" class="u6_y93pge"/></g><g filter="url(#iZAV6sY)"><path fill="url(#iQ3Ldac)" class="qd4tofb7u"/></g><g filter="url(#irFMAhe)"><path fill="url(#iibWUvb)" class="nvirpp9bq"/></g><g filter="url(#iFPsjke)"><path fill="url(#ixKrPfb)" class="kv3enpo0a"/><path fill="url(#iIOJZDd)" class="kv3enpo0a"/></g><g filter="url(#iN5RqUb)"><path fill="url(#imGINwe)" class="fzjqedceo"/></g><path fill="url(#i6zyDYc)" class="mehg4vb6h"/><path fill="url(#iHuEgJc)" class="p1s5w6b8b"/><g filter="url(#iXqzdWd)"><path fill="url(#iZRVjdd)" class="qaaagsblt"/><path fill="url(#iY9rdEe)" class="qaaagsblt"/></g><path fill="url(#iYZXcub)" class="qaaagsblt"/><path fill="url(#iTK7CIb)" class="qaaagsblt"/><path fill="url(#iLOeQ8d)" class="qaaagsblt"/><path fill="url(#i0Y0WGc)" class="qaaagsblt"/><path fill="url(#iwXccjn)" class="qaaagsblt"/><path fill="url(#iMeKxyb)" class="qaaagsblt"/><path fill="url(#iYacElc)" class="qaaagsblt"/><path fill="url(#iCwRmmi)" class="qaaagsblt"/><g filter="url(#isAuPMd)"><path class="vt6x72p3m"/></g><g filter="url(#iCrf6ob)"><path class="q0221omkp"/><path fill="url(#iKxgFHc)" class="bqz5m4lsi"/><path fill="url(#iCVTLuc)" class="bqz5m4lsi"/><path fill="url(#iaohMib)" class="bqz5m4lsi"/><path fill="url(#iyuFXjd)" class="bqz5m4lsi"/><path fill="url(#iNAtKsd)" class="bqz5m4lsi"/></g><path fill="url(#iPStYxb)" class="a240_8b9i"/><g filter="url(#i7iGhed)"><path fill="url(#ieZvW5c)" class="efjfajbds"/></g><path fill="url(#iseE6Pd)" class="efjfajbds"/><path fill="url(#iNw5cOT)" class="efjfajbds"/><path fill="url(#ibcLFPe)" class="efjfajbds"/><g filter="url(#iwtHFIc)"><path class="n8ki6dtye"/><path fill="url(#iMFrnYb)" class="z947cjb4p"/><path fill="url(#iAAmZze)" class="z947cjb4p"/></g><g filter="url(#ioMWYLe)"><path class="yik6dib-q"/><path fill="url(#iRSdvle)" class="y5g4fi-7m"/><path fill="url(#ieBIC1d)" class="y5g4fi-7m"/><path fill="url(#iu6lqRc)" class="y5g4fi-7m"/></g><path class="jv09c9ujg"/><path fill="url(#izccP9c)" class="aqix01bos"/><path class="nxsiigvrh"/><g filter="url(#i9xLh3c)"><path class="m8-j46_ik"/><path fill="url(#il3L4Sd)" class="j55vafb5i"/></g><g filter="url(#iUjtecd)"><path fill="url(#i1CdM9d)" class="g-ua5gbqg"/></g><path class="w5lvigb3l"/><path fill="url(#iDozGHe)" class="sg-v0chgg"/><path class="gcdnzlbcy"/><g filter="url(#iACXyHk)"><path fill="url(#i602HGb)" class="r07ze2bwd"/></g><g filter="url(#iZHgLBy)"><ellipse transform="rotate(-27.914 14.856 12.946)" class="qg0273bnd"/><ellipse fill="url(#iLOMYBd)" transform="rotate(-27.914 14.856 12.946)" class="pai81to7o"/></g><path fill="url(#iVYqsdN)" class="okdi51pbp"/><path fill="url(#iI7LSYb)" class="okdi51pbp"/><path fill="url(#iUA7Z8b)" class="okdi51pbp"/><path fill="url(#isEMwec)" class="okdi51pbp"/><path fill="url(#infolad)" class="ke-on0uco"/><path fill="url(#iIc5gld)" class="ke-on0uco"/><g filter="url(#iiUF4zc)"><path fill="url(#i8U36TC)" class="fiiipg6ln"/></g><g filter="url(#iRQIWSb)"><path fill="url(#iCHMrRc)" class="tea6mjrlo"/></g><g filter="url(#iSX88me)"><path class="nw9fyy51o"/></g><g filter="url(#iOEP8sb)"><path class="lgz36ub9r"/></g><g filter="url(#iHwIlxd)"><path class="e0w8fdc1i"/></g><g filter="url(#iNKzp4c)"><path class="zd-ht9b2r"/></g><g filter="url(#iy7gPpe)"><path class="ings5i9ey"/></g><defs><radialGradient id="ixv7lUK" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.557 10.368)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="vs6a_gbje"/><stop offset="1" class="p05v01y6n"/></radialGradient><radialGradient id="ilPGyGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 10.035 7.769)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="he0s_zrqe"/><stop offset="1" class="ngc6h6bst"/></radialGradient><radialGradient id="igpeLEb" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.36 6.832)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="q7pd18pxe"/><stop offset="1" class="ervi6uxri"/></radialGradient><radialGradient id="iZP7Azb" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.997 3.08)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="vs6a_gbje"/><stop offset="1" class="p05v01y6n"/></radialGradient><radialGradient id="iyDDmMZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 2.305 .918)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="he0s_zrqe"/><stop offset="1" class="ngc6h6bst"/></radialGradient><radialGradient id="iLWRW9Q" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="q7pd18pxe"/><stop offset="1" class="ervi6uxri"/></radialGradient><radialGradient id="iVAnGZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.375 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="il5AC0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 17.938 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="iE3hHec" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 17.781 5.695)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="i1HNLPr" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 8.96 6.273)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="i932lNb" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 3.991 3.074)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="gbg_o2brc"/><stop offset="1" class="ojtd-2bym"/></radialGradient><radialGradient id="iEtNZBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2132 .05173 -.03984 -.16419 8.083 6.282)" gradientUnits="userSpaceOnUse"><stop class="rinxg7b3w"/><stop offset="1" class="mr-9ywwkm"/></radialGradient><radialGradient id="iqtoKIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 8.863 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="gbg_o2brc"/><stop offset="1" class="ojtd-2bym"/></radialGradient><radialGradient id="iryO7ae" cx="0" cy="0" r="1" gradientTransform="matrix(-.2259 .05875 -.04809 -.18493 8.777 6.312)" gradientUnits="userSpaceOnUse"><stop class="rinxg7b3w"/><stop offset="1" class="mr-9ywwkm"/></radialGradient><radialGradient id="i3LYUMP" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.03 3.12)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="gbg_o2brc"/><stop offset="1" class="ojtd-2bym"/></radialGradient><radialGradient id="i5vhkic" cx="0" cy="0" r="1" gradientTransform="matrix(-.21457 .05712 -.04771 -.17925 10.179 6.32)" gradientUnits="userSpaceOnUse"><stop class="rinxg7b3w"/><stop offset="1" class="mr-9ywwkm"/></radialGradient><radialGradient id="ibt35DW" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.687 3.116)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="gbg_o2brc"/><stop offset="1" class="ojtd-2bym"/></radialGradient><radialGradient id="iYPgz9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.22656 .06252 -.05386 -.19519 9.496 6.362)" gradientUnits="userSpaceOnUse"><stop class="rinxg7b3w"/><stop offset="1" class="mr-9ywwkm"/></radialGradient><radialGradient id="idahUab" cx="0" cy="0" r="1" gradientTransform="rotate(134.624 3.957 5.724)scale(.6044)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="rg-2sfb_z"/><stop offset=".91" class="ta8v8mbic"/></radialGradient><radialGradient id="i5AGEFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .21094 -.20725 -.17654 10.827 6.85)" gradientUnits="userSpaceOnUse"><stop class="p_9wr0blz"/><stop offset="1" class="qjh6wtbsx"/></radialGradient><radialGradient id="iGqqmCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.66762 0 0 -1.09544 24.218 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="sbdyv6jmf"/><stop offset="1" class="tnhyi-bom"/></radialGradient><radialGradient id="i9Wexoc" cx="0" cy="0" r="1" gradientTransform="rotate(117.929 10.237 10.362)scale(.21624 .19082)" gradientUnits="userSpaceOnUse"><stop class="gflnmoosd"/><stop offset="1" class="j9d96zbhu"/></radialGradient><radialGradient id="iuHQnxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.70736 0 0 -1.24403 23.543 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="sbdyv6jmf"/><stop offset="1" class="tnhyi-bom"/></radialGradient><radialGradient id="ipB7uYb" cx="0" cy="0" r="1" gradientTransform="rotate(116.317 9.834 10.393)scale(.24205 .20513)" gradientUnits="userSpaceOnUse"><stop class="gflnmoosd"/><stop offset="1" class="j9d96zbhu"/></radialGradient><radialGradient id="iUSh68c" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 0 0 -1.20947 22.124 5.895)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="sbdyv6jmf"/><stop offset="1" class="tnhyi-bom"/></radialGradient><radialGradient id="i07co6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.10193 .21094 -.17622 -.08515 22.093 6.198)" gradientUnits="userSpaceOnUse"><stop class="gflnmoosd"/><stop offset="1" class="j9d96zbhu"/></radialGradient><radialGradient id="igNtrxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.70944 0 0 -1.32351 22.826 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="sbdyv6jmf"/><stop offset="1" class="tnhyi-bom"/></radialGradient><radialGradient id="iEain8Z" cx="0" cy="0" r="1" gradientTransform="matrix(-.10762 .23083 -.18853 -.0879 22.792 6.229)" gradientUnits="userSpaceOnUse"><stop class="gflnmoosd"/><stop offset="1" class="j9d96zbhu"/></radialGradient><radialGradient id="ioBrRPd" cx="0" cy="0" r="1" gradientTransform="rotate(127.213 .238 .266)scale(.65236)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="rg-2sfb_z"/><stop offset=".91" class="ta8v8mbic"/></radialGradient><radialGradient id="i5G2Nwe" cx="0" cy="0" r="1" gradientTransform="rotate(124.323 .276 .232)scale(.31867 .23988)" gradientUnits="userSpaceOnUse"><stop class="p_9wr0blz"/><stop offset="1" class="qjh6wtbsx"/></radialGradient><radialGradient id="i7nMPid" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.313 18.758)" gradientUnits="userSpaceOnUse"><stop class="vv2_9vbpq"/><stop offset="1" class="moznfwbra"/></radialGradient><radialGradient id="iuNDXud" cx="0" cy="0" r="1" gradientTransform="rotate(107.103 2.471 12.873)scale(2.4712 2.78644)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="riglhacpo"/><stop offset="1" class="w_5lt8b6v"/></radialGradient><radialGradient id="iFLqZSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 19.826 21.256)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="wx7ikuwun"/><stop offset="1" class="qljsz814e"/></radialGradient><radialGradient id="ii9TU6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.5 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iMd3cGY" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.294 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="ipt2RNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.074 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="ijEmnZt" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 2.773 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i1fW1XY" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.438 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iL5td6D" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.188 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="iID6PAd" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.145 12.111)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iQ3Ldac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.406 27.992)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="iIOJZDd" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.729 15.316)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="imGINwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.719 28.54)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="i6zyDYc" cx="0" cy="0" r="1" gradientTransform="matrix(.35913 .96863 -1.15066 .42662 18.312 13.666)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iHuEgJc" cx="0" cy="0" r="1" gradientTransform="matrix(.70815 .22256 -.68662 2.1847 13.127 13.901)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iZRVjdd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25667 0 0 -3.99203 17.379 13.215)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iY9rdEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.83607 1.38275 -1.14157 -.69024 17.196 10.827)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iTK7CIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.54859 -5.42302 0 16.3 9.789)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="a0k9robjy"/><stop offset="1" class="zhjq6u9wt"/></radialGradient><radialGradient id="iLOeQ8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.55078 .6816 0 17.206 12.585)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="i0Y0WGc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 13.79 -1.188)scale(.52485 .57116)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iwXccjn" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.624 7.123)scale(4.08303 10.4301)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iMeKxyb" cx="0" cy="0" r="1" gradientTransform="matrix(1.62392 -1.39882 .41319 .47968 12.775 11.904)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iYacElc" cx="0" cy="0" r="1" gradientTransform="matrix(-.11255 1.19784 -.47883 -.045 18.692 11.816)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iCwRmmi" cx="0" cy="0" r="1" gradientTransform="matrix(0 .41804 -.80251 0 14.97 12.977)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iCVTLuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .11708 -.36796 0 16.256 13.959)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iyuFXjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.81156 .35977 -.57818 -1.30424 16.312 13.686)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iPStYxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.04654 -.51451 2.07 4.2105 15.797 15.081)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iseE6Pd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3145 -3.42914 4.86591 1.86527 13.295 12.292)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iNw5cOT" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 14.272 -1.291)scale(3.22673 4.5787)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="ibcLFPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.54295 -1.14304 1.34939 -.64097 17.581 10.263)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iMFrnYb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05572 0 0 -.39182 16.154 9.766)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iAAmZze" cx="0" cy="0" r="1" gradientTransform="matrix(1.54353 -2.44392 2.70761 1.71007 13.428 11.656)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iRSdvle" cx="0" cy="0" r="1" gradientTransform="matrix(1.686 -1.35737 2.10362 2.61292 16.953 11.24)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="ieBIC1d" cx="0" cy="0" r="1" gradientTransform="rotate(-41.829 24.143 -16.707)scale(1.90455 3.48674)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iu6lqRc" cx="0" cy="0" r="1" gradientTransform="matrix(1.54693 .34732 -.14542 .64767 16.881 10.97)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="izccP9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38913 -.61896 0 17.079 12.992)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="il3L4Sd" cx="0" cy="0" r="1" gradientTransform="matrix(-.11124 -.14334 .19734 -.15314 16.97 13.031)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDozGHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38915 -.61899 0 14.986 12.992)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iLOMYBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00371 -.23698 .28486 -.00446 14.848 13.097)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iI7LSYb" cx="0" cy="0" r="1" gradientTransform="matrix(.30147 1.07594 -1.02653 .28763 18.247 12.782)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iUA7Z8b" cx="0" cy="0" r="1" gradientTransform="matrix(.37784 -.51853 .43463 .3167 18.42 13.043)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="isEMwec" cx="0" cy="0" r="1" gradientTransform="rotate(-69.263 18.74 -6.811)scale(.79514 1.06242)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iIc5gld" cx="0" cy="0" r="1" gradientTransform="matrix(-.79535 0 0 -.88812 13.675 13.09)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i8U36TC" cx="0" cy="0" r="1" gradientTransform="rotate(170.259 6.28 7.128)scale(.446 .45729)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><filter id="iFyaoLb" width="9.5" height="4.284" x="11.172" y="21.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="iI1jdtd" width="27.875" height="1.225" x="2.063" y="5.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="iCsqOZf" width="27.781" height=".75" x="2.023" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".125"/></filter><filter id="igk9cre" width="10.708" height="10.353" x="10.803" y="11.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.396078 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="i021DBe" width="1.93" height="8.989" x="5.039" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="iQltiEe" width="1.93" height="8.989" x="24.992" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="igUDKCc" width="1.93" height="5.973" x="3.109" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="il15ikc" width="1.93" height="5.973" x="26.922" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="ispG5Gy" width="3.719" height="6.065" x="8.891" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.4 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.435294 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23314" result="effect2_innerShadow_3987_23314"/></filter><filter id="i2whx4b" width="4.477" height="4.023" x="8.516" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="iZAV6sY" width="4.833" height="2.114" x="7.039" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="irFMAhe" width="3.719" height="5.564" x="19.922" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.4 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.435294 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23314" result="effect2_innerShadow_3987_23314"/></filter><filter id="iFPsjke" width="4.477" height="4.023" x="19.539" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="iN5RqUb" width="4.833" height="2.114" x="20.159" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="iXqzdWd" width="5.902" height="6.019" x="13.604" y="10.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23314" result="effect2_innerShadow_3987_23314"/></filter><filter id="isAuPMd" width="1.638" height="2.191" x="15.145" y="12.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".2"/></filter><filter id="iCrf6ob" width="1.1" height="1.591" x="15.482" y="12.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".05"/></filter><filter id="i7iGhed" width="6.174" height="4.268" x="12.945" y="8.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23314" result="effect2_innerShadow_3987_23314"/></filter><filter id="iwtHFIc" width="3.118" height="2.818" x="13.136" y="9.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/><feGaussianBlur result="effect2_foregroundBlur_3987_23314" stdDeviation=".05"/></filter><filter id="ioMWYLe" width="3.883" height="3.12" x="16.004" y="9.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/><feGaussianBlur result="effect2_foregroundBlur_3987_23314" stdDeviation=".075"/></filter><filter id="i9xLh3c" width=".481" height=".438" x="16.675" y="12.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".05"/></filter><filter id="iUjtecd" width=".636" height=".646" x="17.026" y="12.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".1"/></filter><filter id="iACXyHk" width=".681" height=".707" x="14.895" y="12.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".1"/></filter><filter id="iZHgLBy" width=".542" height=".442" x="14.585" y="12.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".05"/></filter><filter id="iiUF4zc" width=".898" height="1.401" x="12.986" y="12.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".125"/></filter><filter id="iRQIWSb" width="1.387" height="1.843" x="17.955" y="12.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".25"/></filter><filter id="iSX88me" width="2.355" height="1.242" x="16.629" y="10.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".125"/></filter><filter id="iOEP8sb" width="1.177" height=".659" x="14.261" y="11.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="iHwIlxd" width="1.177" height=".659" x="16.73" y="11.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23314"/></filter><filter id="iNKzp4c" width="1.094" height=".495" x="14.259" y="11.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".05"/></filter><filter id="iy7gPpe" width="1.094" height=".495" x="16.715" y="11.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23314" stdDeviation=".05"/></filter><linearGradient id="ibh7zkc" x1="7.158" x2="8.279" y1="7.95" y2="8.096" gradientUnits="userSpaceOnUse"><stop offset=".136" class="nx3rm_63e"/><stop offset="1" class="gem_9mbst"/></linearGradient><linearGradient id="iKvJh5W" x1="-.572" x2=".549" y1="1.099" y2="1.245" gradientUnits="userSpaceOnUse"><stop offset=".136" class="nx3rm_63e"/><stop offset="1" class="gem_9mbst"/></linearGradient><linearGradient id="i0AhJLc" x1="20.313" x2="17.781" y1="25.258" y2="24.82" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="i8igjWE" x1="11.625" x2="14.438" y1="25.352" y2="24.258" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="ibRzype" x1="2.398" x2="29.867" y1="7.406" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="iAW9NPa" x1="5.039" x2="6.531" y1="7.477" y2="7.477" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="irsbW7b" x1="5.039" x2="5.313" y1="7.348" y2="7.348" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="iKoLy8d" x1="24.992" x2="26.188" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iqv6bwe" x1="2.958" x2="3.452" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="iaaWRue" x1="8.345" x2="11.283" y1="25.409" y2="25.409" gradientUnits="userSpaceOnUse"><stop offset=".335" class="pkg_5ym1q"/><stop offset="1" class="b0jqb_u5u"/></linearGradient><linearGradient id="imrVfMc" x1="12.492" x2="8.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iibWUvb" x1="23.686" x2="20.749" y1="25.206" y2="25.206" gradientUnits="userSpaceOnUse"><stop offset=".335" class="pkg_5ym1q"/><stop offset="1" class="b0jqb_u5u"/></linearGradient><linearGradient id="ixKrPfb" x1="19.539" x2="23.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iYZXcub" x1="18.506" x2="17.293" y1="14.023" y2="14.023" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iKxgFHc" x1="16.434" x2="16.032" y1="13.63" y2="13.647" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iaohMib" x1="16.032" x2="16.032" y1="14.176" y2="13.953" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iNAtKsd" x1="16.032" x2="16.032" y1="12.879" y2="13.141" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="ieZvW5c" x1="19.319" x2="13.749" y1="10.499" y2="10.499" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="i1CdM9d" x1="17.452" x2="17.302" y1="13.018" y2="13.111" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i602HGb" x1="15.343" x2="15.192" y1="13.018" y2="13.111" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVYqsdN" x1="19.119" x2="18.54" y1="12.814" y2="13.858" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="infolad" x1="13.227" x2="13.926" y1="13.152" y2="13.091" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iCHMrRc" x1="18.648" x2="18.648" y1="12.666" y2="13.509" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-lifting-weights-medium" /></template>
<style>
.a0k9robjy {
  stop-color: var(--svg-color--a06f71, #A06F71);
  stop-opacity: 0;
}

.a240_8b9i {
  d: path("M16.032 14.733c-.243 0-.472-.058-.664-.158c-.066-.033-.136.04-.095.1c.16.244.44.406.76.406a.91.91 0 0 0 .759-.406c.041-.062-.03-.133-.095-.1c-.192.1-.419.158-.665.158");
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.aqix01bos {
  d: path("M17.08 12.763a.428.428 0 0 1 .412.541h-.826a.43.43 0 0 1 .414-.54");
}

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.b0jqb_u5u {
  stop-color: var(--svg-color--bc9480, #BC9480);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.bqz5m4lsi {
  d: path("m15.849 12.963l-.255.882c-.052.181.073.363.25.363h.377c.177 0 .302-.184.25-.363l-.255-.882c-.055-.195-.31-.195-.367 0");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0w8fdc1i {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M17.616 11.86a1.33 1.33 0 0 0-.825.21a.133.133 0 1 0 .144.224a1.07 1.07 0 0 1 .7-.163l.01.001h.002a.133.133 0 0 0 .054-.26z");
}

.e4y-1lbum {
  r: 0.398px;
}

.efjfajbds {
  d: path("M18.36 10.029c.248.085.469.257.609.504c.224.394.19.864-.051 1.212a.75.75 0 0 0-.13.419v.57a.8.8 0 0 0-.32-.129l.038-.77c-.005-.368-.295-.437-.662-.453h-.671a1.16 1.16 0 0 1-1.06-.692a.32.32 0 0 0-.296-.2h-.61c-.886 0-1.603.49-1.603 1.386l.015.737a.8.8 0 0 0-.346.127v-.576a.75.75 0 0 0-.13-.42a1.15 1.15 0 0 1-.068-1.172c.14-.265.366-.45.623-.54a1.3 1.3 0 0 0 .664-.533a1.115 1.115 0 0 1 1.386-.438c.184.08.39.08.573 0a1.115 1.115 0 0 1 1.392.453c.147.245.378.422.648.515");
}

.em3ofwhyw {
  d: path("m10.948 13.026l2.396-1.12l2.578 3.399l2.469-3.563l2.729 1.318a.25.25 0 0 1 .113.34l-1.194 2.303a1 1 0 0 0-.112.482l.12 5.76h-7.985v-5.788a1 1 0 0 0-.098-.433l-1.136-2.363a.25.25 0 0 1 .12-.335");
}

.ervi6uxri {
  stop-color: var(--svg-color--815440, #815440);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fiiipg6ln {
  d: path("M13.593 12.64a.458.458 0 0 0 .04.901q-.024-.45-.04-.901");
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.ft5dv1b6b {
  fill: none;
}

.fzjqedceo {
  d: path("M24.992 29.53v.376H20.36v-1.914h2.352c.383.377 1.215.73 1.836.941c.398.169.445.442.445.597");
}

.g-ua5gbqg {
  d: path("M17.461 13.135a.4.4 0 0 0-.11-.222l-.125.137l.056.11z");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g4offrb0h {
  d: path("M7.5 5.71a.399.399 0 1 1 .797-.034v.46a.38.38 0 0 1-.758.032z");
}

.g5fg-5cgy {
  d: path("M28.852 4.402a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gbg_o2brc {
  stop-color: var(--svg-color--bf9b81, #BF9B81);
}

.gcdnzlbcy {
  fill: var(--svg-color--000, #000);
  d: path("M15.23 13.192a.244.244 0 0 0-.245-.246a.244.244 0 0 0-.218.358h.434a.24.24 0 0 0 .03-.113");
}

.gem_9mbst {
  stop-color: var(--svg-color--7f575c, #7F575C);
  stop-opacity: 0;
}

.gflnmoosd {
  stop-color: var(--svg-color--b09083, #B09083);
}

.gknucfb8h {
  cx: 10.586px;
  cy: 7px;
  r: 0.398px;
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.he0s_zrqe {
  stop-color: var(--svg-color--6d3e3a, #6D3E3A);
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ijj045bhz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.398 6.406H29.43");
}

.ings5i9ey {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.659 11.99a1.1 1.1 0 0 0-.794.182");
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j55vafb5i {
  d: path("M17.048 12.854c.03.04-.033.09-.105.144c-.073.055-.127.093-.157.052c-.03-.04.003-.118.076-.172c.072-.054.156-.065.186-.024");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j9d96zbhu {
  stop-color: var(--svg-color--b09083, #B09083);
  stop-opacity: 0;
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.jv09c9ujg {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.179 12.633a.67.67 0 0 1 .65.508a.132.132 0 0 1-.128.163h-1.07a.11.11 0 0 1-.11-.13a.67.67 0 0 1 .658-.541");
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.ke-on0uco {
  d: path("M13.613 12.321a.772.772 0 0 0 .062 1.537a37 37 0 0 1-.062-1.537");
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kv3enpo0a {
  d: path("M23.516 21.066a1.988 1.988 0 0 0-3.977 0v1.686c0 .193.157.35.35.35h3.277a.35.35 0 0 0 .35-.35z");
}

.l097mcblv {
  stop-color: var(--svg-color--433f49, #433F49);
}

.l2at7otgu {
  d: path("M23.823 5.627a.422.422 0 1 0-.843-.033v.584a.4.4 0 0 0 .798.031z");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lgz36ub9r {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M14.452 11.86q.076-.007.204 0c.168.013.394.063.62.21a.133.133 0 1 1-.144.224a1.07 1.07 0 0 0-.7-.163l-.01.001h-.001a.133.133 0 0 1-.055-.26z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.m0j2adc3x {
  d: path("M7.73 6.851h2.46v7.269H7.73z");
}

.m8-j46_ik {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.048 12.854c.03.04-.033.09-.105.144c-.073.055-.127.093-.157.052c-.03-.04.003-.118.076-.172c.072-.054.156-.065.186-.024");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mehg4vb6h {
  d: path("M18.364 13.814a.8.8 0 0 0 .434-.148v.447c0 .428-.255.81-.643.968q.122-.261.166-.566z");
}

.moznfwbra {
  stop-color: var(--svg-color--ff6621, #FF6621);
}

.mr-9ywwkm {
  stop-color: var(--svg-color--c2a08d, #C2A08D);
  stop-opacity: 0;
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.n8ki6dtye {
  fill: var(--svg-color--533634, #533634);
  d: path("m16.144 10.521l-.032-.065a.32.32 0 0 0-.295-.2h-.61a1.61 1.61 0 0 0-1.603 1.62v.132c-.163-.124-.368-.386-.368-.81c0-.514.374-.774.614-.94c.067-.046.124-.085.158-.12l.048-.051c.168-.178.467-.495.988-.633q.152-.04.302-.058c.469-.06.808.356.808.829v.29z");
}

.ngc6h6bst {
  stop-color: var(--svg-color--8d625b, #8D625B);
  stop-opacity: 0;
}

.nm-q8ebbk {
  d: path("M8.16 5.627a.422.422 0 1 1 .844-.033v.584a.4.4 0 0 1-.798.031z");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nvirpp9bq {
  d: path("m22.668 28.448l.473-5.464h-3.22l.479 5.464z");
}

.nw9fyy51o {
  fill: var(--svg-color--725050, #725050);
  d: path("M18.142 10.77h-1.025a.238.238 0 1 1 .038-.473c.266.043.62.102.856.16c.534.133.682.393.723.58a.75.75 0 0 0-.592-.266");
}

.nx3rm_63e {
  stop-color: var(--svg-color--59343e, #59343E);
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.nxsiigvrh {
  fill: var(--svg-color--000, #000);
  d: path("M16.835 13.191c0-.136.109-.245.245-.245a.244.244 0 0 1 .218.358h-.434a.2.2 0 0 1-.03-.113");
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ojtd-2bym {
  stop-color: var(--svg-color--8f5c5f, #8F5C5F);
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.okdi51pbp {
  d: path("M18.393 13.858q.048-.765.088-1.53a.772.772 0 0 1-.088 1.53");
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p_9wr0blz {
  stop-color: var(--svg-color--ab8d80, #AB8D80);
}

.p05v01y6n {
  stop-color: var(--svg-color--9c6e68, #9C6E68);
}

.p1s5w6b8b {
  d: path("M13.7 13.814a.8.8 0 0 1-.433-.148v.447c0 .428.255.81.643.968a2 2 0 0 1-.166-.566z");
}

.pai81to7o {
  cx: 14.856px;
  cy: 12.946px;
  rx: 0.187px;
  ry: 0.095px;
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pkg_5ym1q {
  stop-color: var(--svg-color--c4958a, #C4958A);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.pty90zojz {
  stop-color: var(--svg-color--7b7784, #7B7784);
}

.q-vr2ac-v {
  stop-color: var(--svg-color--5c447a, #5C447A);
}

.q0221omkp {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.849 12.963l-.255.882c-.052.181.073.363.25.363h.377c.177 0 .302-.184.25-.363l-.255-.882c-.055-.195-.31-.195-.367 0");
}

.q1wg51bmi {
  d: path("M16 25.93c-2.363 0-4.203-.72-4.828-1.078v-2.907h9.5v3.016c-.573.323-2.31.969-4.672.969");
}

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q7pd18pxe {
  stop-color: var(--svg-color--815440, #815440);
}

.qaaagsblt {
  d: path("M13.718 14.541c.123.936.92 1.634 1.864 1.634h.905c.943 0 1.74-.698 1.863-1.634c.057-.904.114-1.803.156-2.706a.695.695 0 0 0-.662-.687h-.671c-.458 0-.873-.27-1.061-.692a.32.32 0 0 0-.295-.2h-.61a1.61 1.61 0 0 0-1.603 1.62c0 .892.056 1.77.114 2.665");
}

.qd4tofb7u {
  d: path("M7.04 29.53v.376h4.632v-1.914H9.32c-.383.377-1.215.73-1.836.941c-.398.169-.445.442-.445.597");
}

.qg0273bnd {
  cx: 14.856px;
  cy: 12.946px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.187px;
  ry: 0.095px;
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qjh6wtbsx {
  stop-color: var(--svg-color--ab8d80, #AB8D80);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qljsz814e {
  stop-color: var(--svg-color--ff8d41, #FF8D41);
  stop-opacity: 0;
}

.qno0gyhtd {
  d: path("M5.04 2.894a.8.8 0 0 1 .8-.8h.329a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r07ze2bwd {
  d: path("M15.376 13.141c0-.138-.112-.23-.143-.258l-.138.133l.085.174z");
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rg-2sfb_z {
  stop-color: var(--svg-color--957562, #957562);
}

.rh3jx3c9i {
  d: path("M23.108 5.588a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.015z");
}

.riglhacpo {
  stop-color: var(--svg-color--bd3f19, #BD3F19);
}

.rinxg7b3w {
  stop-color: var(--svg-color--c2a08d, #C2A08D);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.sbdyv6jmf {
  stop-color: var(--svg-color--a6876e, #A6876E);
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sg-v0chgg {
  d: path("M14.985 12.763a.428.428 0 0 0-.413.541h.827a.43.43 0 0 0-.415-.54");
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.ta8v8mbic {
  stop-color: var(--svg-color--97696d, #97696D);
}

.tea6mjrlo {
  d: path("m18.455 13.509l.045-.843c.192.026.341.204.341.42c0 .232-.173.42-.386.423");
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tnhyi-bom {
  stop-color: var(--svg-color--8f5d62, #8F5D62);
}

.tphhgybtp {
  d: path("M26.922 2.894a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.ty2qe1a3m {
  stop-color: var(--svg-color--97959c, #97959C);
}

.tzfcre5-h {
  d: path("M8.876 5.588a.424.424 0 1 1 .847-.016v.661a.411.411 0 0 1-.823.015z");
}

.u-rrnxf4y {
  stop-color: var(--svg-color--51435f, #51435F);
  stop-opacity: 0;
}

.u6_y93pge {
  d: path("M8.516 21.066a1.988 1.988 0 1 1 3.976 0v1.686a.35.35 0 0 1-.35.35H8.866a.35.35 0 0 1-.35-.35z");
}

.ufmuzl7ni {
  d: path("M22.392 5.626a.401.401 0 1 0-.803-.014v.575a.391.391 0 0 0 .783.013z");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.up_0b0b8w {
  stop-color: var(--svg-color--8d8c90, #8D8C90);
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.utuf8geyx {
  stop-color: var(--svg-color--cabed2, #CABED2);
  stop-opacity: 0;
}

.uv_bhvydh {
  d: path("m9.404 28.878l-.513-5.894h3.218l-.533 5.966z");
}

.uywq_y1iv {
  width: 27.875px;
  height: 1.025px;
  x: 2.063px;
  y: 5.975px;
  rx: 0.2px;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vs6a_gbje {
  stop-color: var(--svg-color--c69e8a, #C69E8A);
}

.vt6x72p3m {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.84 13.057l-.284.882c-.048.181.068.363.233.363h.35c.165 0 .281-.184.233-.363l-.237-.882c-.051-.195-.242-.195-.295 0");
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.vv2_9vbpq {
  stop-color: var(--svg-color--ff9347, #FF9347);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w_5lt8b6v {
  stop-color: var(--svg-color--de4f22, #DE4F22);
  stop-opacity: 0;
}

.w5lvigb3l {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.886 12.633a.67.67 0 0 0-.65.508a.13.13 0 0 0 .128.163h1.07a.11.11 0 0 0 .11-.13a.67.67 0 0 0-.659-.541");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.wx7ikuwun {
  stop-color: var(--svg-color--c04203, #C04203);
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.x9t-2zb_r {
  d: path("M3.11 4.402a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y0nqeezxq {
  d: path("M24.483 5.71a.399.399 0 1 0-.796-.034v.46a.38.38 0 0 0 .758.032z");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y5g4fi-7m {
  d: path("m18.532 12.337l.054-.345c.107-.41.008-.642-.742-.642h-.671c-.426 0-.815-.233-1.019-.604c0 0 .346-.997.919-.868c.418.094.867.242 1.21.466c.836.546.69 1.53.25 1.992");
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yik6dib-q {
  fill: var(--svg-color--563936, #563936);
  d: path("m18.532 12.337l.054-.345c.107-.41.008-.642-.742-.642h-.671c-.426 0-.815-.233-1.019-.604c0 0 .346-.997.919-.868c.418.094.867.242 1.21.466c.836.546.69 1.53.25 1.992");
}

.z0ggixb3q {
  d: path("M9.592 5.626a.401.401 0 1 1 .803-.014v.575a.391.391 0 0 1-.783.013z");
}

.z947cjb4p {
  d: path("m16.144 10.521l-.032-.065a.32.32 0 0 0-.295-.2h-.61a1.61 1.61 0 0 0-1.603 1.62v.132c-.163-.124-.368-.386-.368-.81c0-.514.374-.774.614-.94c.067-.046.124-.085.158-.12l.048-.051c.168-.178.467-.495.988-.633q.152-.04.302-.058c.469-.06.808.356.808.829v.29z");
}

.zd-ht9b2r {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.409 11.99c.15-.026.494-.032.794.182");
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

.zhjq6u9wt {
  stop-color: var(--svg-color--a4565f, #A4565F);
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
