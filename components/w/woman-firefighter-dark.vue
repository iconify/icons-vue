<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iBreXtA)"><path fill="url(#iaUsmrb)" class="wow_zkb9s"/><path fill="url(#i1ptMxc)" class="wow_zkb9s"/></g><g filter="url(#iunq5qd)"><path fill="url(#iP57O3b)" clip-rule="evenodd" class="fe88u9-li"/><path fill="url(#iCzAxDb)" clip-rule="evenodd" class="fe88u9-li"/><path fill="url(#irxCdob)" clip-rule="evenodd" class="fe88u9-li"/><path fill="url(#i6ssShe)" clip-rule="evenodd" class="fe88u9-li"/></g><path class="b_qv5du4s"/><path fill="url(#i6KAjab)" class="faisxaclj"/><path fill="url(#iQYOIic)" class="faisxaclj"/><path fill="url(#iapQnke)" class="faisxaclj"/><path fill="url(#iiLw8Vb)" class="faisxaclj"/><path fill="url(#iAIO9Yd)" class="faisxaclj"/><path fill="url(#isZrtzc)" class="faisxaclj"/><path fill="url(#iJkm9gA)" class="cmsbox5av"/><path fill="url(#ih3vBxb)" class="cmsbox5av"/><path fill="url(#iov0n7a)" class="cmsbox5av"/><path fill="url(#inI3Unb)" class="vylrb5bvm"/><path fill="url(#iAOYtlU)" class="vylrb5bvm"/><path fill="url(#i0i1YkC)" class="dbj0sjb-p"/><path fill="url(#iI325ic)" class="ja-6i29rv"/><g filter="url(#ipKob3b)"><path fill="url(#i8TDppa)" class="f7v-_qrxa"/></g><g filter="url(#iOXekfd)"><path fill="url(#it2eVqe)" class="tu6xe187b"/><path fill="url(#i9AHr2g)" class="tu6xe187b"/></g><g filter="url(#inweV0d)"><path class="y4irb5jmc"/><path fill="url(#ibdPy7c)" class="sf4g77baj"/></g><g filter="url(#iyEFXWd)"><path class="o335lz_wi"/><path fill="url(#iWBi8ad)" class="l2h1y0bsh"/></g><g filter="url(#inWdrtc)"><path fill="url(#iG7Cv5b)" class="a39igobrw"/><path fill="url(#iGnzTad)" class="a39igobrw"/><path fill="url(#iUWZH9b)" class="a39igobrw"/><path fill="url(#imcOV2b)" class="a39igobrw"/><path fill="url(#iQdUUDc)" class="a39igobrw"/><path fill="url(#ii2xgoe)" class="a39igobrw"/><path fill="url(#iaeKezb)" class="a39igobrw"/><path fill="url(#iVshEEe)" class="a39igobrw"/></g><path fill="url(#ijJEHHc)" class="a39igobrw"/><path fill="url(#iGbj2Zd)" class="a39igobrw"/><path fill="url(#iklRv3d)" class="a39igobrw"/><g filter="url(#i321Ikd)"><path class="q11dcccbh"/></g><g filter="url(#ieR4GRd)"><path class="z2l-fybdu"/><path fill="url(#iLsHOtd)" class="xbmmeemnv"/><path fill="url(#iqrrlVV)" class="xbmmeemnv"/><path fill="url(#is2qrBb)" class="xbmmeemnv"/><path fill="url(#iXXlTnb)" class="xbmmeemnv"/></g><path fill="url(#iRroFxe)" class="xbmmeemnv"/><path fill="url(#iw2LNKd)" class="xbmmeemnv"/><g filter="url(#iyqFMfd)"><path stroke="url(#ibxMinc)" class="vgb0r57va"/></g><path class="sm2w2p14n"/><g filter="url(#iOQdjwX)"><path class="d92hnqf-p"/></g><g filter="url(#itk8uzb)"><path class="v7mipqb3g"/></g><g filter="url(#iWdolKc)"><path class="r0-7_1sfd"/></g><g filter="url(#iHI2SRc)"><path clip-rule="evenodd" class="g4cugubnr"/></g><path class="a-xew1b5b"/><path fill="url(#i3Ya7Dc)" class="oeezmt7lx"/><path class="pp8q_vbnw"/><g filter="url(#iBB31Vc)"><path class="g4xtu-bjd"/><path fill="url(#i5rdVre)" class="jcvt00bhw"/></g><g filter="url(#i8KCZne)"><path fill="url(#iktBkAc)" class="ydpdnpzdz"/></g><path class="ptvoekbcb"/><path fill="url(#itrCcte)" class="j7odj2xef"/><path class="t_e4-qyhf"/><g filter="url(#inaOrKe)"><path fill="url(#iG3BAjd)" class="ax-few44e"/></g><g filter="url(#ipGofmd)"><ellipse transform="rotate(-27.914 12.139 10.36)" class="gru8voc2a"/><ellipse fill="url(#iCtKCKt)" transform="rotate(-27.914 12.139 10.36)" class="kyv1t5xou"/></g><path fill="url(#iHZvJfc)" class="v5pkyqbhx"/><path fill="url(#ih5nvHe)" class="v5pkyqbhx"/><path fill="url(#izHz1gd)" class="v5pkyqbhx"/><path fill="url(#iEsU6Jd)" class="v5pkyqbhx"/><path fill="url(#ia6hdgb)" class="v5pkyqbhx"/><path class="e3e67-bvh"/><path fill="url(#inGX0Oc)" class="oyh5fnr6n"/><path fill="url(#i9mB5Mc)" class="oyh5fnr6n"/><path fill="url(#iUnDHVd)" class="oyh5fnr6n"/><path fill="url(#iKjUOTb)" class="oyh5fnr6n"/><path fill="url(#i1i1Lbq)" class="fw2o80b7i"/><path fill="url(#izpcbVd)" class="fw2o80b7i"/><path fill="url(#iZ6eZGb)" class="fw2o80b7i"/><path fill="url(#ibPujte)" class="fw2o80b7i"/><path fill="url(#i6qz0xW)" class="fw2o80b7i"/><path fill="url(#iMEPogb)" class="w_8w8wqmn"/><path fill="url(#iutMDkb)" class="w_8w8wqmn"/><path fill="url(#ih18itd)" class="w_8w8wqmn"/><g filter="url(#ij7uKdb)"><path fill="url(#iKGw4kt)" class="recb7tbvt"/><path fill="url(#iyoBo3i)" class="recb7tbvt"/></g><g filter="url(#iCfHkkb)"><path fill="url(#ibeddjd)" class="alecchcgl"/><path fill="url(#iQy6vPz)" class="alecchcgl"/></g><path fill="url(#iiVeO6c)" class="alecchcgl"/><path fill="url(#iZmNjZb)" class="alecchcgl"/><g filter="url(#in3TYgH)"><path fill="url(#ibalbKd)" class="kadtwtpmj"/><path fill="url(#ifSfzbe)" class="kadtwtpmj"/><path fill="url(#iIi68Gb)" class="kadtwtpmj"/></g><g filter="url(#iVPtEgl)"><path fill="url(#ibijqYb)" class="f_e3_1bje"/><path fill="url(#iyoK4Kd)" class="f_e3_1bje"/><path fill="url(#iJhoPse)" class="f_e3_1bje"/></g><g filter="url(#i9vWNdd)"><path fill="url(#iksW66c)" class="u-rryybno"/></g><g filter="url(#iV7eXWc)"><path stroke="url(#iJ67e8c)" class="cj_ualb6i"/></g><g filter="url(#i3Qy31d)"><path class="cd1yj8bur"/></g><g filter="url(#iHl3RAc)"><path class="n3iibdccw"/><path fill="url(#iIAi2Bd)" class="eg6wwebxo"/><path fill="url(#iuLQ4mb)" class="eg6wwebxo"/></g><g filter="url(#iZPt3ue)"><path fill="url(#icL13gd)" class="bgen5d6rb"/></g><path fill="url(#ib5u9Je)" class="bgen5d6rb"/><path fill="url(#iT9eoCe)" class="bgen5d6rb"/><defs><radialGradient id="iCzAxDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.95312 -4.20313 .66692 .3099 7.194 12.066)" gradientUnits="userSpaceOnUse"><stop class="niybxc2uq"/><stop offset="1" class="kyuvy4bbj"/></radialGradient><radialGradient id="irxCdob" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.55404 -9.91719 0 14.597 9.843)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="i8--_db9h"/><stop offset=".995" class="tw2yr-3fp"/></radialGradient><radialGradient id="i6ssShe" cx="0" cy="0" r="1" gradientTransform="rotate(173.648 10.7 6.981)scale(1.60475 1.63343)" gradientUnits="userSpaceOnUse"><stop class="nfcjmccxh"/><stop offset="1" class="h3fma_n5f"/></radialGradient><radialGradient id="i6KAjab" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.942)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="iQYOIic" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.253)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="iapQnke" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.128)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iiLw8Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.941)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="iAIO9Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.722)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="isZrtzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.26)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iJkm9gA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.864 29.754)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="iov0n7a" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 29.972)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="inI3Unb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 23.977)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="iAOYtlU" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 22.972)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="it2eVqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 18.631 11.492)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="i9AHr2g" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 19.662 9.372)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="ibdPy7c" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 18.983 11.165)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iWBi8ad" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 9.99 11.053)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iG7Cv5b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 17.451 10.515)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="iGnzTad" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 6.925 7.536)scale(2.25599 1.57104)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="iUWZH9b" cx="0" cy="0" r="1" gradientTransform="matrix(1.0735 -3.47607 4.41049 1.36207 12.412 17.298)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="imcOV2b" cx="0" cy="0" r="1" gradientTransform="scale(6.7993 6.76308)rotate(90 .306 1.84)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="dsze8fgpw"/><stop offset="1" class="gasc2abms"/></radialGradient><radialGradient id="iQdUUDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.56691 -6.60207 0 14.33 10.905)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="ii2xgoe" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 7.606 6.92)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iaeKezb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 16.893 10.097)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iVshEEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 12.515 9.868)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="ijJEHHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 19.687 11.584)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iGbj2Zd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.829 1.57435 -1.05517 -1.22584 18.513 15.631)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iklRv3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.84375 9.69619 0 14.592 14.16)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="kfc_5qbod"/><stop offset="1" class="xdjooob5j"/></radialGradient><radialGradient id="iLsHOtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 15.377 12.311)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iXXlTnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 15.137 12.523)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iw2LNKd" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 5.634 8.286)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="i3Ya7Dc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 16.774 10.456)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i5rdVre" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 16.546 10.54)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="itrCcte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 12.41 10.456)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iCtKCKt" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.316 -.63)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHZvJfc" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.04 7.094)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="izHz1gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.066)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iEsU6Jd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.097)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="ia6hdgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.191)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="inGX0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.816)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iKjUOTb" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.767 20.747)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="izpcbVd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.174)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iZ6eZGb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.144)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="ibPujte" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.129)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i6qz0xW" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.035)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="iutMDkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.755)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="ih18itd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.827)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iKGw4kt" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.463 3.484)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iyoBo3i" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.285)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iQy6vPz" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .526 19.636)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iiVeO6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.394)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="iZmNjZb" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.786 16.332)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="ifSfzbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.852 16.946)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="iIi68Gb" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.378)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="ibijqYb" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.028 15.777)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iyoK4Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.504)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="iJhoPse" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.063 12.55)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><radialGradient id="iIAi2Bd" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.156 16.067)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iuLQ4mb" cx="0" cy="0" r="1" gradientTransform="matrix(2.31645 1.18733 -.41625 .81209 12.19 16.066)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="icL13gd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.786 11.704)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="iT9eoCe" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.41506 13.993 16.033)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><filter id="iBreXtA" width="17.197" height="11.9" x="5.988" y="7.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><filter id="iunq5qd" width="15.118" height="14.561" x="6.988" y="2.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.254902 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><filter id="ipKob3b" width="3.368" height="3.218" x="8.297" y="9.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><filter id="iOXekfd" width="3.218" height="3.468" x="17.81" y="9.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><filter id="inweV0d" width="3.148" height="3.148" x="17.845" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2605" stdDeviation=".25"/></filter><filter id="iyEFXWd" width="2.648" height="2.648" x="8.601" y="9.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2605" stdDeviation=".125"/></filter><filter id="inWdrtc" width="10.191" height="11.027" x="9.497" y="6.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><filter id="i321Ikd" width="2.877" height="3.682" x="12.991" y="10.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2605" stdDeviation=".25"/></filter><filter id="ieR4GRd" width="2.377" height="3.182" x="13.403" y="10.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2605" stdDeviation=".125"/></filter><filter id="iyqFMfd" width="3.702" height="1.526" x="12.741" y="13.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2605" stdDeviation=".05"/></filter><filter id="iOQdjwX" width="3.001" height="1.285" x="15.534" y="9.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><filter id="itk8uzb" width="3.001" height="1.285" x="10.649" y="9.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><filter id="iWdolKc" width="2.453" height="1.091" x="10.784" y="7.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><filter id="iHI2SRc" width="2.453" height="1.091" x="16.201" y="7.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><filter id="iBB31Vc" width=".787" height=".696" x="16.04" y="10.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2605" stdDeviation=".05"/></filter><filter id="i8KCZne" width=".891" height=".913" x="16.88" y="10.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2605" stdDeviation=".1"/></filter><filter id="inaOrKe" width=".986" height="1.04" x="12.437" y="10.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2605" stdDeviation=".1"/></filter><filter id="ipGofmd" width=".913" height=".704" x="11.682" y="10.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2605" stdDeviation=".05"/></filter><filter id="ij7uKdb" width="5.52" height="4.05" x="11.827" y="3.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2605" result="effect2_innerShadow_4002_2605"/></filter><filter id="iCfHkkb" width="6.94" height="14.221" x="16.577" y="15.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2605" result="effect2_innerShadow_4002_2605"/></filter><filter id="in3TYgH" width="11.012" height="8.855" x="17.86" y="16.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2605" result="effect2_innerShadow_4002_2605"/></filter><filter id="iVPtEgl" width="4.557" height="7.476" x="23.816" y="17.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><filter id="i9vWNdd" width="2.509" height="3.213" x="13.154" y="3.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2605"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2605" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2605"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2605" result="effect3_innerShadow_4002_2605"/></filter><filter id="iV7eXWc" width="1.83" height="4.718" x="18.091" y="17.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2605" stdDeviation=".125"/></filter><filter id="i3Qy31d" width="2.769" height="7.081" x="18.396" y="23.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2605" stdDeviation=".2"/></filter><filter id="iHl3RAc" width="6.88" height="4.067" x="11.157" y="15.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><filter id="iZPt3ue" width="4.97" height="4.236" x="13.277" y="15.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2605"/></filter><linearGradient id="iaUsmrb" x1="14.587" x2="14.587" y1="7.972" y2="19.472" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="i1ptMxc" x1="14.587" x2="14.587" y1="7.249" y2="10.843" gradientUnits="userSpaceOnUse"><stop offset=".184" class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="iP57O3b" x1="14.597" x2="14.597" y1="8.004" y2="17.124" gradientUnits="userSpaceOnUse"><stop class="o2xqgmbjp"/><stop offset="1" class="v2ky7trsz"/></linearGradient><linearGradient id="ih3vBxb" x1="7.607" x2="6.489" y1="26.66" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="i0i1YkC" x1="7.407" x2="21.783" y1="15.862" y2="15.862" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iI325ic" x1="7.407" x2="21.783" y1="15.832" y2="15.832" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i8TDppa" x1="8.297" x2="11.257" y1="11.14" y2="11.14" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iqrrlVV" x1="13.653" x2="14.592" y1="12.384" y2="12.384" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="is2qrBb" x1="14.592" x2="14.592" y1="13.183" y2="12.573" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iRroFxe" x1="14.67" x2="14.67" y1="13.157" y2="13.017" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="ibxMinc" x1="13.528" x2="13.989" y1="14.593" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iktBkAc" x1="17.552" x2="17.238" y1="10.51" y2="10.703" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iG3BAjd" x1="13.154" x2="12.84" y1="10.509" y2="10.703" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ih5nvHe" x1="10.646" x2="16.989" y1="6.722" y2="6.722" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="i9mB5Mc" x1="14.592" x2="14.592" y1="30.316" y2="28.722" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iUnDHVd" x1="14.592" x2="14.592" y1="26.172" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="i1i1Lbq" x1="14.582" x2="14.582" y1="6.972" y2="11.754" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="iMEPogb" x1="14.582" x2="14.582" y1="19.605" y2="26.175" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="ibeddjd" x1="22.021" x2="18.333" y1="16.754" y2="29.972" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="ibalbKd" x1="20.021" x2="28.208" y1="22.191" y2="18.878" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="iksW66c" x1="14.458" x2="14.458" y1="4.22" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="iJ67e8c" x1="18.689" x2="20.192" y1="21.647" y2="16.457" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><linearGradient id="ib5u9Je" x1="13.277" x2="13.489" y1="18.084" y2="18.084" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-firefighter-dark" /></template>
<style>
.a-xew1b5b {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.983 9.707c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.a39igobrw {
  d: path("M9.505 9.79h.012l-.01-.265l-.01-.306c.02-.95.574-1.317.81-1.439l.05-.02q.029-.013.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051c.718 1.05 1.918 1.5 3.19 1.5h3.22c.346 0 1.082.26 1.135 1.505l-.118 3.073c-.124 2.803-2.312 4.685-4.984 4.685c-2.671 0-4.86-1.882-4.983-4.685z");
}

.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.alecchcgl {
  d: path("m22.636 16.137l-1.38-.369a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.211a.53.53 0 0 0-.368-.624");
}

.ax-few44e {
  d: path("M13.223 10.766c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b_qv5du4s {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bgen5d6rb {
  d: path("M13.277 16.798v1.834c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-2.005c-.898.826-2.116 1.3-3.457 1.3q-.683-.001-1.313-.16");
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.cd1yj8bur {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.921 29.629c0-.2 1.146-4.105 1.719-6.032");
}

.cj_ualb6i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.546 17.972l-1.08 3.968");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmsbox5av {
  d: path("M7.607 29.972V17.97a10.98 10.98 0 0 0-4.02 8.502v3.5z");
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cv6gnzbto {
  stop-color: var(--svg-color--fec852, #FEC852);
}

.cvnvm48dp {
  stop-color: var(--svg-color--a17d74, #A17D74);
  stop-opacity: 0;
}

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d7eq7sb9j {
  stop-color: var(--svg-color--bab3b6, #BAB3B6);
  stop-opacity: 0;
}

.d8vnolbdv {
  stop-color: var(--svg-color--ed2e7c, #ED2E7C);
  stop-opacity: 0;
}

.d92hnqf-p {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M15.734 10.484c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.27.217.233.495.025.599l-.556.318c-.652-.211-1.373-.24-2.079-.45");
}

.dbj0sjb-p {
  d: path("M14.947 15.833c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.deg-o6bbc {
  stop-color: var(--svg-color--f94d70, #F94D70);
}

.dinvdlb3p {
  stop-color: var(--svg-color--785253, #785253);
}

.dmxjdc_5c {
  stop-color: var(--svg-color--d0465e, #D0465E);
}

.dsze8fgpw {
  stop-color: var(--svg-color--401e26, #401E26);
  stop-opacity: 0;
}

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3e67-bvh {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.577 26.172H7.607v3.8h13.97z");
}

.eg6wwebxo {
  d: path("M11.157 15.678v1.974c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.986c-.896.82-2.111 1.29-3.447 1.29c-1.329 0-2.538-.465-3.433-1.278");
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.f_e3_1bje {
  d: path("M25.649 18.01q.435-.032.85-.171l.148-.055c.178-.062.401-.053.554.108c1.072 1.125 1.43 2.62.984 4.235c-.447 1.615-1.733 2.765-2.98 3.034c-.084.02-.348.045-.506-.158l-.141-.14a3.5 3.5 0 0 0-.642-.588c1.567-.052 2.817-1.084 3.203-2.53c.39-1.468-.236-3.002-1.472-3.735z");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f7v-_qrxa {
  d: path("M9.906 12.662a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.faisxaclj {
  d: path("M14.587 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.fe88u9-li {
  fill-rule: evenodd;
  d: path("M21.782 12.5c.213-.434.324-.92.324-1.426c0-.467-.096-.906-.269-1.306h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.77l-.167-.01c0-1.823-1.31-3.3-3.132-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001C9.592 4.218 8.49 5.688 8.49 7.481h-.33a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455c-.93 1.953.83 4.168 2.894 4.168h8.582c1.78 0 3.218-1.453 3.218-2.906c0-.506-.122-.837-.324-1.262a.52.52 0 0 1 0-.455M9.522 9.829H9.51l1.198 2.356c.124 2.802 1.217 0 3.889 0s3.836 3.12 3.96.317l1.087-3.19c-.054-1.245-.907-1.34-1.087-1.34h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.241 1.255l-.051.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.fw2o80b7i {
  d: path("M8.659 7.972h11.847c.948 0 1.988.485 1.988 2.68h.692V9.347c0-1.43-.848-2.375-2.457-2.375H8.435c-1.609 0-2.456.946-2.456 2.375v1.305h.69c0-2.195 1.04-2.68 1.99-2.68");
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.g4cugubnr {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m18.323 8.372l-.137.23za.268.268 0 0 1-.275.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.09.988 0 1.328.109a3.3 3.3 0 0 1 .558.239l.01.005z");
}

.g4xtu-bjd {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.71 10.167c.064.085-.069.189-.22.302s-.263.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.gasc2abms {
  stop-color: var(--svg-color--451521, #451521);
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.gru8voc2a {
  cx: 12.139px;
  cy: 10.36px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h3fma_n5f {
  stop-color: var(--svg-color--3f3c3d, #3F3C3D);
  stop-opacity: 0;
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.i8--_db9h {
  stop-color: var(--svg-color--483c3d, #483C3D);
  stop-opacity: 0;
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.ism0j8_fd {
  stop-color: var(--svg-color--675b70, #675B70);
}

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.j7odj2xef {
  d: path("M12.408 9.979a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.ja-6i29rv {
  d: path("M14.617 15.833h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jcvt00bhw {
  d: path("M16.71 10.167c.064.085-.069.189-.22.302s-.263.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.kadtwtpmj {
  d: path("m20.012 16.732l4.416 1.16a3.56 3.56 0 0 0 2.071-.053l.148-.055c.178-.062.401-.053.554.108c1.072 1.125 1.43 2.62.984 4.235c-.447 1.615-1.733 2.765-2.98 3.034c-.084.02-.348.045-.506-.158l-.141-.14a3.5 3.5 0 0 0-1.745-1.11L18.57 22.55a.61.61 0 0 1-.43-.78l1.25-4.674c.045-.22.37-.43.622-.364");
}

.kfc_5qbod {
  stop-color: var(--svg-color--2e1315, #2E1315);
  stop-opacity: 0;
}

.kiftlkrmt {
  stop-color: var(--svg-color--c75567, #C75567);
  stop-opacity: 0;
}

.kjxybmb-y {
  stop-color: var(--svg-color--fc5083, #FC5083);
  stop-opacity: 0;
}

.kmg6h4b5x {
  stop-color: var(--svg-color--bd585d, #BD585D);
  stop-opacity: 0;
}

.ko6eamtic {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
  stop-opacity: 0;
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.kpneurz6b {
  stop-color: var(--svg-color--c1415c, #C1415C);
  stop-opacity: 0;
}

.krttc8bap {
  stop-color: var(--svg-color--c1415c, #C1415C);
}

.ks1omcbjp {
  stop-color: var(--svg-color--be324c, #BE324C);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ku_tac4_z {
  stop-color: var(--svg-color--c93271, #C93271);
  stop-opacity: 0;
}

.kvhp_ip6r {
  stop-color: var(--svg-color--df3d67, #DF3D67);
}

.kx5tbm42q {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
}

.kyuvy4bbj {
  stop-color: var(--svg-color--3a312e, #3A312E);
  stop-opacity: 0;
}

.kyv1t5xou {
  cx: 12.139px;
  cy: 10.36px;
  rx: 0.39px;
  ry: 0.197px;
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l2h1y0bsh {
  d: path("M9.925 12.127a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.leotspfhb {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
}

.lf_6el-zz {
  stop-color: var(--svg-color--ee2f8c, #EE2F8C);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.n3iibdccw {
  fill: var(--svg-color--d53260, #D53260);
  d: path("M11.157 15.678v1.974c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.986c-.896.82-2.111 1.29-3.447 1.29c-1.329 0-2.538-.465-3.433-1.278");
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.nfcjmccxh {
  stop-color: var(--svg-color--3f3c3d, #3F3C3D);
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.niybxc2uq {
  stop-color: var(--svg-color--3a312e, #3A312E);
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.o2xqgmbjp {
  stop-color: var(--svg-color--1e0106, #1E0106);
}

.o335lz_wi {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M9.925 12.127a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oeezmt7lx {
  d: path("M16.776 9.979a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.oirct-bua {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
  stop-opacity: 0;
}

.ommdktbpj {
  stop-color: var(--svg-color--8f5b56, #8F5B56);
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.oyh5fnr6n {
  d: path("M21.577 26.172H7.607v3.8h13.97z");
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.pci0oxh-l {
  stop-color: var(--svg-color--a39ba9, #A39BA9);
}

.pfbpewb0p {
  stop-color: var(--svg-color--734145, #734145);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp8q_vbnw {
  fill: var(--svg-color--000, #000);
  d: path("M16.265 10.871c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.ptvoekbcb {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.201 9.707c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.q11dcccbh {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m14.2 10.83l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0-7_1sfd {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.194 8.83l-.004.002a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.01-.005a2 2 0 0 1 .147-.077a3 3 0 0 1 .41-.162c.34-.108.816-.2 1.329-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.recb7tbvt {
  d: path("M17.247 6.972h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rx-q5b7rc {
  stop-color: var(--svg-color--f1b244, #F1B244);
}

.rz-l4sb2t {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
}

.rzbfz4btw {
  stop-color: var(--svg-color--b3576b, #B3576B);
  stop-opacity: 0;
}

.s2qawgbpe {
  stop-color: var(--svg-color--b78426, #B78426);
}

.s7s75dkrn {
  stop-color: var(--svg-color--b93054, #B93054);
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.sf4g77baj {
  d: path("M19.42 12.127a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.sm2w2p14n {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M14.592 13.964c-.52 0-1.01-.125-1.422-.344c-.14-.073-.291.088-.203.219a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.t_e4-qyhf {
  fill: var(--svg-color--000, #000);
  d: path("M12.92 10.871a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.tbz0q_48a {
  stop-color: var(--svg-color--dd365e, #DD365E);
  stop-opacity: 0;
}

.tc4y5tbfa {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
}

.tcape2laf {
  stop-color: var(--svg-color--edb63d, #EDB63D);
}

.tu6xe187b {
  d: path("M19.42 12.662a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.tw2yr-3fp {
  stop-color: var(--svg-color--483c3d, #483C3D);
}

.u-rryybno {
  d: path("M13.304 4.91c0-.154.183-.232.293-.126l.155.149a.162.162 0 0 0 .274-.117v-.17c0-.345.178-.665.472-.847l.18-.111a.23.23 0 0 1 .35.195v1.194a.17.17 0 0 0 .278.132l.096-.078a.13.13 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.053z");
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.v2ky7trsz {
  stop-color: var(--svg-color--170810, #170810);
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v5pkyqbhx {
  d: path("M20.885 7.332H8.29v-.377c0-2.734 2.01-4.928 5.02-4.928h2.411c3.329 0 5.165 2.194 5.165 4.928z");
}

.v7mipqb3g {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.45 10.484c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.318c.652-.211 1.373-.24 2.08-.45");
}

.vgb0r57va {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.592 13.964c-.52 0-1.01-.125-1.422-.344c-.14-.073-.291.088-.203.219a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.vkwv3acem {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
  stop-opacity: 0;
}

.voemc8h9d {
  stop-color: var(--svg-color--d23b59, #D23B59);
}

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.vylrb5bvm {
  d: path("M21.577 17.982v11.99h4v-3.5a10.98 10.98 0 0 0-4-8.49");
}

.w_8w8wqmn {
  d: path("M15.167 19.605h-1.17v6.57h1.17z");
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wow_zkb9s {
  d: path("M22.174 7.972H7.152c-.395.32-.78 1.337-1.164 1.657v1.343c0 4.69 3.855 8.5 8.599 8.5s8.598-3.81 8.598-8.5V9.63c-.354-.42-.687-1.207-1.011-1.657");
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xbmmeemnv {
  d: path("m14.21 10.692l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xdjooob5j {
  stop-color: var(--svg-color--2e1315, #2E1315);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.y4irb5jmc {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M19.42 12.127a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.ydpdnpzdz {
  d: path("M17.57 10.754a.84.84 0 0 0-.23-.463l-.26.285l.117.228z");
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z2l-fybdu {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m14.21 10.692l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.ze-km1b7g {
  stop-color: var(--svg-color--c51b40, #C51B40);
}

.zhmn0cciw {
  stop-color: var(--svg-color--a11339, #A11339);
}

.zj8ulgbnv {
  stop-color: var(--svg-color--c71931, #C71931);
}

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
