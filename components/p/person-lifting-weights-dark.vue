<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irWaeBe)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#iPFCWte)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#iQLbRae)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#i9ok8Kd)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#iTwkA1t)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#ip4jPSd)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iCvQthb)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iJbZBWu)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><g filter="url(#iIfOtPc)"><path fill="url(#iVAnGZb)" class="q1wg51bmi"/><path fill="url(#i0AhJLc)" class="q1wg51bmi"/><path fill="url(#i8igjWE)" class="q1wg51bmi"/><path fill="url(#il5AC0d)" class="q1wg51bmi"/></g><g filter="url(#i3DyvEe)"><rect fill="url(#iE3hHec)" class="uywq_y1iv"/><rect fill="url(#i1HNLPr)" class="uywq_y1iv"/></g><g filter="url(#imwESPV)"><path stroke="url(#ibRzype)" class="ijj045bhz"/></g><path fill="url(#i24GUMc)" class="g4offrb0h"/><path fill="url(#ihhhJBc)" class="g4offrb0h"/><path fill="url(#iRYZuid)" class="nm-q8ebbk"/><path fill="url(#i0igTeN)" class="nm-q8ebbk"/><path fill="url(#iDijFNd)" class="z0ggixb3q"/><path fill="url(#iR7c7Tp)" class="z0ggixb3q"/><path fill="url(#i0ja9kp)" class="tzfcre5-h"/><path fill="url(#iR3r0Rg)" class="tzfcre5-h"/><circle fill="url(#iK5YMnd)" class="gknucfb8h"/><circle fill="url(#iBqyoDY)" class="gknucfb8h"/><path fill="url(#ir3DQid)" class="y0nqeezxq"/><path fill="url(#ix3RWdc)" class="y0nqeezxq"/><path fill="url(#iV90gIb)" class="l2at7otgu"/><path fill="url(#iBRnrnd)" class="l2at7otgu"/><path fill="url(#iQ6i6Ic)" class="ufmuzl7ni"/><path fill="url(#ikuftmc)" class="ufmuzl7ni"/><path fill="url(#iw6FXDu)" class="rh3jx3c9i"/><path fill="url(#iURUD2b)" class="rh3jx3c9i"/><circle fill="url(#iPAaaFe)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><circle fill="url(#izGUkQe)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><g filter="url(#iRlMO3b)"><path fill="url(#i7nMPid)" class="em3ofwhyw"/><path fill="url(#iuNDXud)" class="em3ofwhyw"/><path fill="url(#iFLqZSc)" class="em3ofwhyw"/></g><g filter="url(#ipYzByq)"><path fill="url(#ii9TU6b)" class="qno0gyhtd"/><path fill="url(#iAW9NPa)" class="qno0gyhtd"/><path fill="url(#irsbW7b)" class="qno0gyhtd"/></g><g filter="url(#i3hMuid)"><path fill="url(#iMd3cGY)" class="tphhgybtp"/><path fill="url(#iKoLy8d)" class="tphhgybtp"/></g><g filter="url(#iAAiRsc)"><path fill="url(#ipt2RNb)" class="x9t-2zb_r"/><path fill="url(#ijEmnZt)" class="x9t-2zb_r"/><path fill="url(#iqv6bwe)" class="x9t-2zb_r"/></g><g filter="url(#irccZIc)"><path fill="url(#i1fW1XY)" class="g5fg-5cgy"/><path fill="url(#iL5td6D)" class="g5fg-5cgy"/></g><g filter="url(#i2tpGeb)"><path fill="url(#iG2scoe)" class="uv_bhvydh"/></g><g filter="url(#idUIeFb)"><path fill="url(#imrVfMc)" class="u6_y93pge"/><path fill="url(#iID6PAd)" class="u6_y93pge"/></g><g filter="url(#i84o3xd)"><path fill="url(#iQ3Ldac)" class="qd4tofb7u"/></g><g filter="url(#iJxU5Oc)"><path fill="url(#iv2Ytfq)" class="nvirpp9bq"/></g><g filter="url(#idgH5qe)"><path fill="url(#ixKrPfb)" class="kv3enpo0a"/><path fill="url(#iIOJZDd)" class="kv3enpo0a"/></g><g filter="url(#iL9jxdb)"><path fill="url(#imGINwe)" class="fzjqedceo"/></g><path fill="url(#iFHRthb)" class="r99zj9b9i"/><path fill="url(#i7EBpRb)" class="twqjhifmu"/><g filter="url(#inHuHxN)"><path fill="url(#iugEUSb)" class="i7y6pl8px"/></g><path fill="url(#i3EMIBe)" class="i7y6pl8px"/><path fill="url(#i3KTyBc)" class="i7y6pl8px"/><path fill="url(#ilZRSyd)" class="i7y6pl8px"/><path fill="url(#iBcmo5d)" class="i7y6pl8px"/><path fill="url(#ioJMVtd)" class="i7y6pl8px"/><path fill="url(#iAEqyUb)" class="i7y6pl8px"/><path fill="url(#iyLASYb)" class="i7y6pl8px"/><path fill="url(#iP3o39C)" class="i7y6pl8px"/><path fill="url(#iZweCYu)" class="i7y6pl8px"/><g filter="url(#iIjwO9d)"><path class="bwl636dbk"/></g><g filter="url(#ijxsFbc)"><path class="ptvlj6b4b"/><path fill="url(#iglxDWd)" class="yi6f0ib8n"/><path fill="url(#iDLf6Ke)" class="yi6f0ib8n"/><path fill="url(#iOVdg4c)" class="yi6f0ib8n"/><path fill="url(#iBxD0eb)" class="yi6f0ib8n"/><path fill="url(#ikmjJBd)" class="yi6f0ib8n"/></g><path fill="url(#i5mhqoh)" class="z--9y0hnc"/><g filter="url(#iiQXmsb)"><path fill="url(#iZZAv2S)" class="vhhacgbon"/><path fill="url(#iOJslfd)" class="vhhacgbon"/><path fill="url(#iarChnJ)" class="vhhacgbon"/><path fill="url(#iuScYJe)" class="vhhacgbon"/><path fill="url(#iJ2Zztb)" class="vhhacgbon"/></g><g filter="url(#iJusJab)"><path class="p97l_-bcv"/><path fill="url(#iLRaRJe)" class="ol6tzlbff"/><path fill="url(#ivKFiDd)" class="ol6tzlbff"/></g><g filter="url(#im0Edbc)"><path class="vi_rht-6q"/><path fill="url(#iy63nbB)" class="lu6z4yj4u"/></g><path class="f-egx61tq"/><path fill="url(#iI0S7je)" class="s652backf"/><path class="p656mfb8u"/><g filter="url(#iImbWjb)"><path class="vwjtcebbh"/><path fill="url(#iZbKFwb)" class="a__51vsxw"/></g><g filter="url(#i0yR9pb)"><path fill="url(#i8Xs0Cc)" class="mfhw-cvum"/></g><path class="me_o8f2oz"/><path fill="url(#iS7iY8K)" class="wtd65-u2b"/><path class="j87swcchf"/><g filter="url(#iJs0mJe)"><path fill="url(#i3uPREc)" class="it22g_bbx"/></g><g filter="url(#i3PrcFe)"><ellipse transform="rotate(-27.914 14.746 12.942)" class="lu3hbwbqb"/><ellipse fill="url(#i3bVAMe)" transform="rotate(-27.914 14.746 12.942)" class="xhjtmplni"/></g><path fill="url(#i5ujDdc)" class="iitcneq-n"/><path fill="url(#iCyD53c)" class="iitcneq-n"/><path fill="url(#iSYd99G)" class="iitcneq-n"/><path fill="url(#iTGdNre)" class="iitcneq-n"/><path fill="url(#iBFL60c)" class="c7q0f6bmy"/><path fill="url(#izPkVTU)" class="c7q0f6bmy"/><g filter="url(#iS32O4d)"><path fill="url(#i3Smdcd)" class="iq9afacqp"/></g><g filter="url(#ih0pgdB)"><path fill="url(#iBvw9je)" class="o9b44abss"/></g><g filter="url(#i2368ee)"><path class="xl03acclh"/></g><g filter="url(#iPAPDQe)"><path class="i0t-a4bjn"/></g><g filter="url(#iTvKs5c)"><path class="ejsv7lh5h"/></g><g filter="url(#iUcrgbb)"><path class="a3qgf8bxy"/></g><g filter="url(#icX7p5R)"><path class="hfj0iub-z"/></g><defs><radialGradient id="irWaeBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00154 4.75464 -1.08171 -.00035 9.816 10.929)" gradientUnits="userSpaceOnUse"><stop class="qxt6awing"/><stop offset="1" class="fj6oqbblw"/></radialGradient><radialGradient id="iQLbRae" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 10.04 7.769)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="qylhzjbru"/><stop offset="1" class="h4dbuabjd"/></radialGradient><radialGradient id="i9ok8Kd" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.362 6.832)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="depaksbko"/><stop offset="1" class="vhfhqxbvt"/></radialGradient><radialGradient id="iTwkA1t" cx="0" cy="0" r="1" gradientTransform="rotate(87.787 -1.122 2.973)scale(4.85666 1.64346)" gradientUnits="userSpaceOnUse"><stop class="ak_zghmfq"/><stop offset="1" class="ev69acfdm"/></radialGradient><radialGradient id="iCvQthb" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 2.305 .918)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="x0brf5bzd"/><stop offset="1" class="hlgj40bxa"/></radialGradient><radialGradient id="iJbZBWu" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="we8qh66wy"/><stop offset="1" class="cypwky4hn"/></radialGradient><radialGradient id="iVAnGZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.375 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="il5AC0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 17.938 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="iE3hHec" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 17.781 5.695)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="i1HNLPr" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 8.96 6.273)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="i24GUMc" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 3.991 3.074)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="y043ag9kq"/><stop offset="1" class="ds648q_0f"/></radialGradient><radialGradient id="ihhhJBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2132 .05173 -.03984 -.16419 8.083 6.282)" gradientUnits="userSpaceOnUse"><stop class="bg0ve-bea"/><stop offset="1" class="d2pbendkj"/></radialGradient><radialGradient id="iRYZuid" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.08758 -1.32389 8.863 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tsah1w4pm"/><stop offset="1" class="ds648q_0f"/></radialGradient><radialGradient id="i0igTeN" cx="0" cy="0" r="1" gradientTransform="matrix(-.2259 .05875 -.04809 -.18493 8.777 6.312)" gradientUnits="userSpaceOnUse"><stop class="bg0ve-bea"/><stop offset="1" class="d2pbendkj"/></radialGradient><radialGradient id="iDijFNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.66879 .04529 -.08714 -1.28684 10.26 5.895)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tsah1w4pm"/><stop offset="1" class="ds648q_0f"/></radialGradient><radialGradient id="iR7c7Tp" cx="0" cy="0" r="1" gradientTransform="matrix(-.21457 .05712 -.04771 -.17925 10.179 6.32)" gradientUnits="userSpaceOnUse"><stop class="bg0ve-bea"/><stop offset="1" class="d2pbendkj"/></radialGradient><radialGradient id="i0ja9kp" cx="0" cy="0" r="1" gradientTransform="matrix(-.70618 .0496 -.09885 -1.40768 9.58 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tsah1w4pm"/><stop offset="1" class="ds648q_0f"/></radialGradient><radialGradient id="iR3r0Rg" cx="0" cy="0" r="1" gradientTransform="matrix(-.22656 .06252 -.05386 -.19519 9.496 6.362)" gradientUnits="userSpaceOnUse"><stop class="bg0ve-bea"/><stop offset="1" class="d2pbendkj"/></radialGradient><radialGradient id="iK5YMnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.39453 .51953 -.51953 -.39453 10.781 6.84)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="rmb17xpfy"/><stop offset=".91" class="aw3vee06o"/></radialGradient><radialGradient id="iBqyoDY" cx="0" cy="0" r="1" gradientTransform="rotate(124.323 3.627 6.223)scale(.31867 .23988)" gradientUnits="userSpaceOnUse"><stop class="bg0ve-bea"/><stop offset="1" class="d2pbendkj"/></radialGradient><radialGradient id="ir3DQid" cx="0" cy="0" r="1" gradientTransform="matrix(-.66762 0 0 -1.09544 24.218 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tsah1w4pm"/><stop offset="1" class="ds648q_0f"/></radialGradient><radialGradient id="ix3RWdc" cx="0" cy="0" r="1" gradientTransform="rotate(117.929 10.237 10.362)scale(.21624 .19082)" gradientUnits="userSpaceOnUse"><stop class="bg0ve-bea"/><stop offset="1" class="d2pbendkj"/></radialGradient><radialGradient id="iV90gIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.70736 0 0 -1.24403 23.543 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tsah1w4pm"/><stop offset="1" class="ds648q_0f"/></radialGradient><radialGradient id="iBRnrnd" cx="0" cy="0" r="1" gradientTransform="rotate(116.317 9.834 10.393)scale(.24205 .20513)" gradientUnits="userSpaceOnUse"><stop class="bg0ve-bea"/><stop offset="1" class="d2pbendkj"/></radialGradient><radialGradient id="iQ6i6Ic" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 0 0 -1.20947 22.124 5.895)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tsah1w4pm"/><stop offset="1" class="ds648q_0f"/></radialGradient><radialGradient id="ikuftmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10193 .21094 -.17622 -.08515 22.093 6.198)" gradientUnits="userSpaceOnUse"><stop class="bg0ve-bea"/><stop offset="1" class="d2pbendkj"/></radialGradient><radialGradient id="iw6FXDu" cx="0" cy="0" r="1" gradientTransform="matrix(-.70944 0 0 -1.32351 22.826 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tsah1w4pm"/><stop offset="1" class="ds648q_0f"/></radialGradient><radialGradient id="iURUD2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.10762 .23083 -.18853 -.0879 22.792 6.229)" gradientUnits="userSpaceOnUse"><stop class="bg0ve-bea"/><stop offset="1" class="d2pbendkj"/></radialGradient><radialGradient id="iPAaaFe" cx="0" cy="0" r="1" gradientTransform="rotate(127.213 .238 .266)scale(.65236)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="rmb17xpfy"/><stop offset=".91" class="aw3vee06o"/></radialGradient><radialGradient id="izGUkQe" cx="0" cy="0" r="1" gradientTransform="rotate(124.323 .276 .232)scale(.31867 .23988)" gradientUnits="userSpaceOnUse"><stop class="bg0ve-bea"/><stop offset="1" class="d2pbendkj"/></radialGradient><radialGradient id="i7nMPid" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.313 18.758)" gradientUnits="userSpaceOnUse"><stop class="vv2_9vbpq"/><stop offset="1" class="moznfwbra"/></radialGradient><radialGradient id="iuNDXud" cx="0" cy="0" r="1" gradientTransform="rotate(107.103 2.471 12.873)scale(2.4712 2.78644)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="riglhacpo"/><stop offset="1" class="w_5lt8b6v"/></radialGradient><radialGradient id="iFLqZSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 19.826 21.256)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="wx7ikuwun"/><stop offset="1" class="qljsz814e"/></radialGradient><radialGradient id="ii9TU6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.5 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iMd3cGY" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.294 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="ipt2RNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.074 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="ijEmnZt" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 2.773 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i1fW1XY" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.438 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iL5td6D" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.188 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="iID6PAd" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.145 12.111)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iQ3Ldac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.406 27.992)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="iIOJZDd" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.729 15.316)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="imGINwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.719 28.54)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="iFHRthb" cx="0" cy="0" r="1" gradientTransform="matrix(.35913 .96863 -1.15066 .42662 18.202 13.666)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="i7EBpRb" cx="0" cy="0" r="1" gradientTransform="matrix(.70815 .22255 -.68658 2.18473 13.016 13.9)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iugEUSb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50743 0 0 -4.43561 17.268 13.215)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="i3KTyBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.49029 5.95866 -4.93448 -.40602 16.68 10.378)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="ilZRSyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.55078 .6816 0 17.095 12.585)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iBcmo5d" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 13.736 -1.132)scale(.52485 .57116)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="ioJMVtd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.568 7.121)scale(4.08303 10.4301)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iAEqyUb" cx="0" cy="0" r="1" gradientTransform="matrix(1.95352 -1.2702 .46498 .71513 13.3 11.14)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iyLASYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.11255 1.19784 -.47883 -.045 18.581 11.815)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iP3o39C" cx="0" cy="0" r="1" gradientTransform="matrix(-.83607 1.38275 -1.14157 -.69024 17.086 10.827)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iDLf6Ke" cx="0" cy="0" r="1" gradientTransform="matrix(0 .11708 -.36796 0 16.145 14.05)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iBxD0eb" cx="0" cy="0" r="1" gradientTransform="matrix(-.72958 .3345 -.53758 -1.1725 16.201 13.777)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i5mhqoh" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.34569 1.39078 0 15.914 15.041)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iOJslfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.67933 4.24684 0 13.414 11.828)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iarChnJ" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.644 -3.322)scale(1.20633 2.13737)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iuScYJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.13136 -.7441 .5462 -.83048 17.891 9.446)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iJ2Zztb" cx="0" cy="0" r="1" gradientTransform="matrix(.43412 .70745 -1.63812 1.00521 15.488 8.682)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iLRaRJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 0 0 -.53443 16.108 10.128)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="ivKFiDd" cx="0" cy="0" r="1" gradientTransform="matrix(1.54353 -2.44392 2.70761 1.71007 13.317 11.79)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iy63nbB" cx="0" cy="0" r="1" gradientTransform="matrix(1.55793 .1821 -.07624 .65228 16.76 11.136)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iI0S7je" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38913 -.61896 0 16.97 12.988)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iZbKFwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.11123 -.14334 .19735 -.15314 16.86 13.028)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iS7iY8K" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38915 -.61899 0 14.877 12.988)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i3bVAMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00371 -.23698 .28486 -.00446 14.74 13.093)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iCyD53c" cx="0" cy="0" r="1" gradientTransform="matrix(.30147 1.07594 -1.02653 .28763 18.136 12.782)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iSYd99G" cx="0" cy="0" r="1" gradientTransform="matrix(.37784 -.51853 .43463 .3167 18.31 13.043)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iTGdNre" cx="0" cy="0" r="1" gradientTransform="matrix(.28154 -.74363 .9936 .37618 18.364 13.126)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="izPkVTU" cx="0" cy="0" r="1" gradientTransform="matrix(-.19802 .99572 -.97889 -.19468 13.397 12.863)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="i3Smdcd" cx="0" cy="0" r="1" gradientTransform="matrix(-.43957 .07545 -.03328 -.19387 13.565 13.09)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><filter id="iIfOtPc" width="9.5" height="4.284" x="11.172" y="21.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="i3DyvEe" width="27.875" height="1.225" x="2.063" y="5.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="imwESPV" width="27.781" height=".75" x="2.023" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".125"/></filter><filter id="iRlMO3b" width="10.708" height="10.353" x="10.803" y="11.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.396078 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="ipYzByq" width="1.93" height="8.989" x="5.039" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="i3hMuid" width="1.93" height="8.989" x="24.992" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="iAAiRsc" width="1.93" height="5.973" x="3.109" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="irccZIc" width="1.93" height="5.973" x="26.922" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="i2tpGeb" width="3.719" height="6.065" x="8.891" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.121569 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23308" result="effect2_innerShadow_3987_23308"/></filter><filter id="idUIeFb" width="4.477" height="4.023" x="8.516" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="i84o3xd" width="4.833" height="2.114" x="7.039" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="iJxU5Oc" width="3.719" height="5.564" x="19.922" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.121569 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23308" result="effect2_innerShadow_3987_23308"/></filter><filter id="idgH5qe" width="4.477" height="4.023" x="19.539" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="iL9jxdb" width="4.833" height="2.114" x="20.159" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="inHuHxN" width="5.902" height="6.119" x="13.493" y="10.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23308" result="effect2_innerShadow_3987_23308"/></filter><filter id="iIjwO9d" width="2.838" height="3.391" x="14.435" y="12.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".5"/></filter><filter id="ijxsFbc" width="1.1" height="1.591" x="15.372" y="12.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".05"/></filter><filter id="iiQXmsb" width="6.174" height="4.268" x="12.835" y="8.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23308" result="effect2_innerShadow_3987_23308"/></filter><filter id="iJusJab" width="3.118" height="2.818" x="13.025" y="9.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".05"/></filter><filter id="im0Edbc" width="3.033" height="2.77" x="15.893" y="9.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/><feGaussianBlur result="effect2_foregroundBlur_3987_23308" stdDeviation=".075"/></filter><filter id="iImbWjb" width=".481" height=".438" x="16.566" y="12.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".05"/></filter><filter id="i0yR9pb" width=".636" height=".646" x="16.916" y="12.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".1"/></filter><filter id="iJs0mJe" width=".681" height=".707" x="14.786" y="12.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".1"/></filter><filter id="i3PrcFe" width=".542" height=".442" x="14.476" y="12.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".05"/></filter><filter id="iS32O4d" width=".898" height="1.401" x="12.875" y="12.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".125"/></filter><filter id="ih0pgdB" width="1.454" height="1.913" x="17.793" y="12.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".25"/></filter><filter id="i2368ee" width="2.306" height="1.222" x="16.453" y="10.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".125"/></filter><filter id="iPAPDQe" width="1.177" height=".659" x="14.201" y="11.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="iTvKs5c" width="1.177" height=".659" x="16.67" y="11.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23308"/></filter><filter id="iUcrgbb" width="1.094" height=".495" x="14.2" y="11.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".05"/></filter><filter id="icX7p5R" width="1.094" height=".495" x="16.655" y="11.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23308" stdDeviation=".05"/></filter><linearGradient id="iPFCWte" x1="7.163" x2="8.284" y1="7.95" y2="8.096" gradientUnits="userSpaceOnUse"><stop offset=".136" class="kvjaxphqo"/><stop offset="1" class="t03-t4xfq"/></linearGradient><linearGradient id="ip4jPSd" x1="-.572" x2=".549" y1="1.099" y2="1.245" gradientUnits="userSpaceOnUse"><stop offset=".136" class="glbcn46mr"/><stop offset="1" class="p0aw3ab3v"/></linearGradient><linearGradient id="i0AhJLc" x1="20.313" x2="17.781" y1="25.258" y2="24.82" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="i8igjWE" x1="11.625" x2="14.438" y1="25.352" y2="24.258" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="ibRzype" x1="2.398" x2="29.867" y1="7.406" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="iAW9NPa" x1="5.039" x2="6.531" y1="7.477" y2="7.477" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="irsbW7b" x1="5.039" x2="5.313" y1="7.348" y2="7.348" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="iKoLy8d" x1="24.992" x2="26.188" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iqv6bwe" x1="2.958" x2="3.452" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="iG2scoe" x1="8.891" x2="12.501" y1="25.409" y2="25.409" gradientUnits="userSpaceOnUse"><stop offset=".335" class="e_69a7boy"/><stop offset="1" class="wbtwcwmoa"/></linearGradient><linearGradient id="imrVfMc" x1="12.492" x2="8.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iv2Ytfq" x1="23.141" x2="19.53" y1="25.206" y2="25.206" gradientUnits="userSpaceOnUse"><stop offset=".335" class="e_69a7boy"/><stop offset="1" class="wbtwcwmoa"/></linearGradient><linearGradient id="ixKrPfb" x1="19.539" x2="23.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="i3EMIBe" x1="18.395" x2="16.308" y1="14.023" y2="14.023" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iZweCYu" x1="15.944" x2="15.944" y1="16.213" y2="15.906" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="iglxDWd" x1="16.324" x2="15.922" y1="13.721" y2="13.738" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iOVdg4c" x1="15.922" x2="15.922" y1="14.268" y2="14.045" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="ikmjJBd" x1="15.922" x2="15.922" y1="12.851" y2="13.232" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iZZAv2S" x1="19.208" x2="13.639" y1="10.499" y2="10.499" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="i8Xs0Cc" x1="17.343" x2="17.192" y1="13.014" y2="13.106" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3uPREc" x1="15.233" x2="15.083" y1="13.014" y2="13.106" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5ujDdc" x1="19.009" x2="18.43" y1="12.814" y2="13.858" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iBFL60c" x1="13.116" x2="13.816" y1="13.152" y2="13.091" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iBvw9je" x1="18.52" x2="18.52" y1="12.631" y2="13.544" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-lifting-weights-dark" /></template>
<style>
.a__51vsxw {
  d: path("M16.94 12.85c.03.04-.034.09-.107.144c-.072.054-.126.092-.156.052c-.03-.041.003-.118.076-.172c.072-.055.156-.065.186-.025");
}

.a3qgf8bxy {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.35 11.99a1.1 1.1 0 0 1 .793.182");
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ak_zghmfq {
  stop-color: var(--svg-color--4d3636, #4D3636);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.aw3vee06o {
  stop-color: var(--svg-color--321921, #321921);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bg0ve-bea {
  stop-color: var(--svg-color--645553, #645553);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.bwl636dbk {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.73 13.149l-.284.882c-.048.18.068.362.232.362h.351c.165 0 .28-.184.233-.363l-.238-.881c-.05-.195-.242-.195-.295 0");
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c7q0f6bmy {
  d: path("M13.498 12.323a.772.772 0 0 0 .066 1.535a37 37 0 0 1-.066-1.535");
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cypwky4hn {
  stop-color: var(--svg-color--3e2420, #3E2420);
  stop-opacity: 0;
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.d2pbendkj {
  stop-color: var(--svg-color--645553, #645553);
  stop-opacity: 0;
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.depaksbko {
  stop-color: var(--svg-color--382524, #382524);
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.ds648q_0f {
  stop-color: var(--svg-color--30181b, #30181B);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e_69a7boy {
  stop-color: var(--svg-color--573d40, #573D40);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4y-1lbum {
  r: 0.398px;
}

.ejsv7lh5h {
  fill: var(--svg-color--202020, #202020);
  d: path("M17.557 11.86a1.33 1.33 0 0 0-.825.21a.133.133 0 1 0 .144.224a1.07 1.07 0 0 1 .7-.163l.01.001h.001a.133.133 0 0 0 .055-.26z");
}

.em3ofwhyw {
  d: path("m10.948 13.026l2.396-1.12l2.578 3.399l2.469-3.563l2.729 1.318a.25.25 0 0 1 .113.34l-1.194 2.303a1 1 0 0 0-.112.482l.12 5.76h-7.985v-5.788a1 1 0 0 0-.098-.433l-1.136-2.363a.25.25 0 0 1 .12-.335");
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ev69acfdm {
  stop-color: var(--svg-color--321c1e, #321C1E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f-egx61tq {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.07 12.629a.67.67 0 0 1 .65.507a.13.13 0 0 1-.129.164h-1.07a.11.11 0 0 1-.109-.13a.67.67 0 0 1 .658-.541");
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fj6oqbblw {
  stop-color: var(--svg-color--462a29, #462A29);
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

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g4offrb0h {
  d: path("M7.5 5.71a.399.399 0 1 1 .797-.034v.46a.38.38 0 0 1-.758.032z");
}

.g5fg-5cgy {
  d: path("M28.852 4.402a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gknucfb8h {
  cx: 10.586px;
  cy: 7px;
  r: 0.398px;
}

.glbcn46mr {
  stop-color: var(--svg-color--231116, #231116);
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h4dbuabjd {
  stop-color: var(--svg-color--271215, #271215);
  stop-opacity: 0;
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.hfj0iub-z {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.6 11.99a1.1 1.1 0 0 0-.795.182");
}

.hlgj40bxa {
  stop-color: var(--svg-color--271315, #271315);
  stop-opacity: 0;
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.i0t-a4bjn {
  fill: var(--svg-color--202020, #202020);
  d: path("M14.392 11.86q.076-.008.205 0c.168.014.393.063.62.21a.133.133 0 0 1-.144.224a1.07 1.07 0 0 0-.7-.163l-.01.001h-.002a.133.133 0 0 1-.054-.26z");
}

.i7y6pl8px {
  d: path("M13.608 14.54c.123.937.92 1.634 1.863 1.634h.905a1.88 1.88 0 0 0 1.864-1.633c.056-.904.113-1.803.155-2.706a.695.695 0 0 0-.661-.687h-.672a1.16 1.16 0 0 1-1.06-.692a.32.32 0 0 0-.296-.201h-.61a1.61 1.61 0 0 0-1.603 1.62c0 .893.056 1.771.114 2.666");
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.iitcneq-n {
  d: path("M18.282 13.858q.048-.765.089-1.53a.772.772 0 0 1-.089 1.53");
}

.ijj045bhz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.398 6.406H29.43");
}

.iq9afacqp {
  d: path("M13.483 12.64a.458.458 0 0 0 .04.901q-.025-.45-.04-.901");
}

.it22g_bbx {
  d: path("M15.267 13.137c0-.139-.113-.23-.143-.259l-.138.134l.085.173z");
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j87swcchf {
  fill: var(--svg-color--000, #000);
  d: path("M15.12 13.187a.244.244 0 0 0-.244-.245a.244.244 0 0 0-.218.358h.434a.24.24 0 0 0 .029-.113");
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kv3enpo0a {
  d: path("M23.516 21.066a1.988 1.988 0 0 0-3.977 0v1.686c0 .193.157.35.35.35h3.277a.35.35 0 0 0 .35-.35z");
}

.kvjaxphqo {
  stop-color: var(--svg-color--200f15, #200F15);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l097mcblv {
  stop-color: var(--svg-color--433f49, #433F49);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2at7otgu {
  d: path("M23.823 5.627a.422.422 0 1 0-.843-.033v.584a.4.4 0 0 0 .798.031z");
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.lu3hbwbqb {
  cx: 14.746px;
  cy: 12.942px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.187px;
  ry: 0.095px;
}

.lu6z4yj4u {
  d: path("m18.422 12.337l-.014-.303c.09-.446-.042-.684-.674-.684h-.672a1.16 1.16 0 0 1-1.018-.604s.345-.997.918-.868c.419.094.867.242 1.21.466c.837.546.69 1.53.25 1.992");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me_o8f2oz {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.776 12.629a.67.67 0 0 0-.65.507a.13.13 0 0 0 .129.164h1.07a.11.11 0 0 0 .109-.13a.67.67 0 0 0-.658-.541");
}

.mfhw-cvum {
  d: path("M17.352 13.13a.4.4 0 0 0-.11-.221l-.126.136l.057.11z");
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.moznfwbra {
  stop-color: var(--svg-color--ff6621, #FF6621);
}

.nm-q8ebbk {
  d: path("M8.16 5.627a.422.422 0 1 1 .844-.033v.584a.4.4 0 0 1-.798.031z");
}

.nvirpp9bq {
  d: path("m22.668 28.448l.473-5.464h-3.22l.479 5.464z");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.o9b44abss {
  d: path("m18.293 13.544l.053-.913a.458.458 0 0 1-.053.913");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ol6tzlbff {
  d: path("m16.033 10.656l-.031-.066a.32.32 0 0 0-.295-.2h-.611c-.885 0-1.603.725-1.603 1.62v.132c-.163-.124-.368-.386-.368-.81c0-.514.375-.774.614-.94c.068-.046.125-.085.159-.12l.048-.051c.167-.178.466-.495.988-.633q.152-.04.302-.058c.469-.06.808.356.808.829v.29z");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p0aw3ab3v {
  stop-color: var(--svg-color--231116, #231116);
  stop-opacity: 0;
}

.p656mfb8u {
  fill: var(--svg-color--000, #000);
  d: path("M16.726 13.187c0-.136.108-.245.245-.245a.244.244 0 0 1 .218.358h-.434a.2.2 0 0 1-.03-.113");
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.p97l_-bcv {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.033 10.656l-.031-.066a.32.32 0 0 0-.295-.2h-.611c-.885 0-1.603.725-1.603 1.62v.132c-.163-.124-.368-.386-.368-.81c0-.514.375-.774.614-.94c.068-.046.125-.085.159-.12l.048-.051c.167-.178.466-.495.988-.633q.152-.04.302-.058c.469-.06.808.356.808.829v.29z");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.psru50bbi {
  d: path("M7.735 6.851h2.46v7.269h-2.46z");
}

.ptvlj6b4b {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.739 13.055l-.255.882c-.052.181.072.362.25.362h.376c.177 0 .302-.184.25-.362l-.255-.882c-.054-.195-.31-.195-.367 0");
}

.pty90zojz {
  stop-color: var(--svg-color--7b7784, #7B7784);
}

.q-vr2ac-v {
  stop-color: var(--svg-color--5c447a, #5C447A);
}

.q1wg51bmi {
  d: path("M16 25.93c-2.363 0-4.203-.72-4.828-1.078v-2.907h9.5v3.016c-.573.323-2.31.969-4.672.969");
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qd4tofb7u {
  d: path("M7.04 29.53v.376h4.632v-1.914H9.32c-.383.377-1.215.73-1.836.941c-.398.169-.445.442-.445.597");
}

.qljsz814e {
  stop-color: var(--svg-color--ff8d41, #FF8D41);
  stop-opacity: 0;
}

.qno0gyhtd {
  d: path("M5.04 2.894a.8.8 0 0 1 .8-.8h.329a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxt6awing {
  stop-color: var(--svg-color--665453, #665453);
}

.qylhzjbru {
  stop-color: var(--svg-color--271215, #271215);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.r99zj9b9i {
  d: path("M18.253 13.814a.8.8 0 0 0 .434-.148v.447c0 .428-.255.81-.643.968q.123-.261.166-.566z");
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rh3jx3c9i {
  d: path("M23.108 5.588a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.015z");
}

.riglhacpo {
  stop-color: var(--svg-color--bd3f19, #BD3F19);
}

.rmb17xpfy {
  stop-color: var(--svg-color--513c38, #513C38);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.s652backf {
  d: path("M16.97 12.759a.428.428 0 0 1 .413.54h-.827a.43.43 0 0 1 .415-.54");
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t03-t4xfq {
  stop-color: var(--svg-color--402829, #402829);
  stop-opacity: 0;
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tphhgybtp {
  d: path("M26.922 2.894a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.tsah1w4pm {
  stop-color: var(--svg-color--564441, #564441);
}

.twqjhifmu {
  d: path("M13.59 13.814a.8.8 0 0 1-.434-.148v.447c0 .428.255.81.643.968a2 2 0 0 1-.165-.566z");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.ty2qe1a3m {
  stop-color: var(--svg-color--97959c, #97959C);
}

.tzfcre5-h {
  d: path("M8.876 5.588a.424.424 0 1 1 .847-.016v.661a.411.411 0 0 1-.823.015z");
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
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

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.up_0b0b8w {
  stop-color: var(--svg-color--8d8c90, #8D8C90);
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

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vhfhqxbvt {
  stop-color: var(--svg-color--382524, #382524);
  stop-opacity: 0;
}

.vhhacgbon {
  d: path("M18.25 10.029c.247.085.468.257.608.504c.224.393.191.864-.05 1.212a.75.75 0 0 0-.13.419v.57a.8.8 0 0 0-.32-.129l.037-.77c-.005-.368-.295-.434-.661-.45h-.672a1.16 1.16 0 0 1-1.06-.692a.32.32 0 0 0-.295-.2h-.611c-.885 0-1.603.487-1.603 1.383l.015.737a.8.8 0 0 0-.345.127v-.576a.75.75 0 0 0-.13-.42a1.15 1.15 0 0 1-.069-1.173c.14-.264.367-.45.623-.54c.275-.098.51-.283.664-.532a1.115 1.115 0 0 1 1.387-.438c.183.08.389.08.572 0a1.115 1.115 0 0 1 1.392.453c.147.245.379.422.648.515");
}

.vi_rht-6q {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m18.422 12.337l-.014-.303c.09-.446-.042-.684-.674-.684h-.672a1.16 1.16 0 0 1-1.018-.604s.345-.997.918-.868c.419.094.867.242 1.21.466c.837.546.69 1.53.25 1.992");
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.vv2_9vbpq {
  stop-color: var(--svg-color--ff9347, #FF9347);
}

.vwjtcebbh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.94 12.85c.03.04-.034.09-.107.144c-.072.054-.126.092-.156.052c-.03-.041.003-.118.076-.172c.072-.055.156-.065.186-.025");
}

.w_5lt8b6v {
  stop-color: var(--svg-color--de4f22, #DE4F22);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.wbtwcwmoa {
  stop-color: var(--svg-color--472a2a, #472A2A);
}

.we8qh66wy {
  stop-color: var(--svg-color--3e2420, #3E2420);
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.wtd65-u2b {
  d: path("M14.876 12.759a.428.428 0 0 0-.413.54h.827a.43.43 0 0 0-.415-.54");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wx7ikuwun {
  stop-color: var(--svg-color--c04203, #C04203);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.x0brf5bzd {
  stop-color: var(--svg-color--271315, #271315);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x9t-2zb_r {
  d: path("M3.11 4.402a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xhjtmplni {
  cx: 14.746px;
  cy: 12.942px;
  rx: 0.187px;
  ry: 0.095px;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xl03acclh {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M17.933 10.778h-.998a.231.231 0 1 1 .037-.461c.258.041.602.099.833.156c.52.129.664.382.704.563a.73.73 0 0 0-.576-.258");
}

.y043ag9kq {
  stop-color: var(--svg-color--4d3936, #4D3936);
}

.y0nqeezxq {
  d: path("M24.483 5.71a.399.399 0 1 0-.796-.034v.46a.38.38 0 0 0 .758.032z");
}

.yi6f0ib8n {
  d: path("m15.739 13.055l-.255.882c-.052.181.072.362.25.362h.376c.177 0 .302-.184.25-.362l-.255-.882c-.054-.195-.31-.195-.367 0");
}

.z--9y0hnc {
  d: path("M15.914 14.733c-.243 0-.472-.058-.664-.158c-.066-.033-.137.04-.095.1c.16.244.44.406.76.406a.91.91 0 0 0 .759-.406c.04-.062-.03-.133-.095-.1c-.193.1-.42.158-.665.158");
}

.z0ggixb3q {
  d: path("M9.592 5.626a.401.401 0 1 1 .803-.014v.575a.391.391 0 0 1-.783.013z");
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
