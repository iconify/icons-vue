<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i0eMgUI)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#iOjek6c)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#i8IhE7b)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#ia0ozfc)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#imdZvZc)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iev7Igb)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iJSh9Rd)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#icTlMSc)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><g filter="url(#ihew9zc)"><path fill="url(#iVAnGZb)" class="q1wg51bmi"/><path fill="url(#i0AhJLc)" class="q1wg51bmi"/><path fill="url(#i8igjWE)" class="q1wg51bmi"/><path fill="url(#il5AC0d)" class="q1wg51bmi"/></g><g filter="url(#iTQyArb)"><rect fill="url(#iE3hHec)" class="uywq_y1iv"/><rect fill="url(#i1HNLPr)" class="uywq_y1iv"/></g><g filter="url(#icts8Zc)"><path stroke="url(#ibRzype)" class="ijj045bhz"/></g><path fill="url(#i6eHjnx)" class="g4offrb0h"/><path fill="url(#ihrMxQQ)" class="g4offrb0h"/><path fill="url(#igYlFZb)" class="nm-q8ebbk"/><path fill="url(#iA39zBd)" class="nm-q8ebbk"/><path fill="url(#icomEIe)" class="z0ggixb3q"/><path fill="url(#iKUvYXc)" class="z0ggixb3q"/><path fill="url(#i2lb2vb)" class="tzfcre5-h"/><path fill="url(#irtIY9Z)" class="tzfcre5-h"/><circle fill="url(#ihUH0Ge)" class="gknucfb8h"/><circle fill="url(#igSWh8b)" class="gknucfb8h"/><path fill="url(#iuoWORd)" class="y0nqeezxq"/><path fill="url(#i1gUcVd)" class="y0nqeezxq"/><path fill="url(#i2g6S5b)" class="l2at7otgu"/><path fill="url(#itN5bFe)" class="l2at7otgu"/><path fill="url(#ilQeege)" class="ufmuzl7ni"/><path fill="url(#iBbOMSb)" class="ufmuzl7ni"/><path fill="url(#ivMLBmb)" class="rh3jx3c9i"/><path fill="url(#inblcIb)" class="rh3jx3c9i"/><circle fill="url(#ibvUIjc)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><circle fill="url(#iLZeLcY)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><g filter="url(#isRCJUr)"><path fill="url(#i7nMPid)" class="em3ofwhyw"/><path fill="url(#iuNDXud)" class="em3ofwhyw"/><path fill="url(#iFLqZSc)" class="em3ofwhyw"/></g><g filter="url(#iuUgO1e)"><path fill="url(#ii9TU6b)" class="qno0gyhtd"/><path fill="url(#iAW9NPa)" class="qno0gyhtd"/><path fill="url(#irsbW7b)" class="qno0gyhtd"/></g><g filter="url(#ib3k0Ic)"><path fill="url(#iMd3cGY)" class="tphhgybtp"/><path fill="url(#iKoLy8d)" class="tphhgybtp"/></g><g filter="url(#iilHhTC)"><path fill="url(#ipt2RNb)" class="x9t-2zb_r"/><path fill="url(#ijEmnZt)" class="x9t-2zb_r"/><path fill="url(#iqv6bwe)" class="x9t-2zb_r"/></g><g filter="url(#ic2dkZc)"><path fill="url(#i1fW1XY)" class="g5fg-5cgy"/><path fill="url(#iL5td6D)" class="g5fg-5cgy"/></g><g filter="url(#itcfTEc)"><path fill="url(#i9g91Cd)" class="uv_bhvydh"/></g><g filter="url(#iSYUqvd)"><path fill="url(#imrVfMc)" class="u6_y93pge"/><path fill="url(#iID6PAd)" class="u6_y93pge"/></g><g filter="url(#iOhz5sb)"><path fill="url(#iQ3Ldac)" class="qd4tofb7u"/></g><g filter="url(#i8dkrmb)"><path fill="url(#iHOi0qc)" class="nvirpp9bq"/></g><g filter="url(#ipeNOkb)"><path fill="url(#ixKrPfb)" class="kv3enpo0a"/><path fill="url(#iIOJZDd)" class="kv3enpo0a"/></g><g filter="url(#ibIcLue)"><path fill="url(#imGINwe)" class="fzjqedceo"/></g><path fill="url(#i0MC05c)" class="r99zj9b9i"/><path fill="url(#iPdL0Wc)" class="twqjhifmu"/><g filter="url(#iSBecvb)"><path fill="url(#iVrVsub)" class="i7y6pl8px"/><path fill="url(#iFsjsdc)" class="i7y6pl8px"/></g><path fill="url(#ip8u89d)" class="i7y6pl8px"/><path fill="url(#iFsjsdc)" class="i7y6pl8px"/><path fill="url(#ijaFLNe)" class="i7y6pl8px"/><path fill="url(#iBHmyce)" class="i7y6pl8px"/><path fill="url(#ib8udxw)" class="i7y6pl8px"/><path fill="url(#ikY3Fjd)" class="i7y6pl8px"/><g filter="url(#iM4jhte)"><path class="t31_vej7y"/></g><g filter="url(#i9FZYcd)"><path class="etpioe5tg"/><path fill="url(#ilFe0ng)" class="yi6f0ib8n"/><path fill="url(#i742MKY)" class="yi6f0ib8n"/><path fill="url(#iMboHxb)" class="yi6f0ib8n"/><path fill="url(#iRrNy5b)" class="yi6f0ib8n"/><path fill="url(#iNY20fb)" class="yi6f0ib8n"/></g><path class="rmv72gx_s"/><g filter="url(#iivOTFd)"><path fill="url(#ibSifLb)" class="vhhacgbon"/><path fill="url(#iOJslfd)" class="vhhacgbon"/><path fill="url(#iarChnJ)" class="vhhacgbon"/><path fill="url(#isDQ70c)" class="vhhacgbon"/><path fill="url(#iDk5VHd)" class="vhhacgbon"/></g><g filter="url(#iBmFWLd)"><path class="eyeh733jt"/><path fill="url(#iecd4xI)" class="ol6tzlbff"/><path fill="url(#ivKFiDd)" class="ol6tzlbff"/></g><g filter="url(#iFxwGpd)"><path class="t01v63bal"/><path fill="url(#iPq4Qyc)" class="lu6z4yj4u"/><path fill="url(#ir5CvVb)" class="lu6z4yj4u"/></g><path class="f-egx61tq"/><path fill="url(#iI0S7je)" class="s652backf"/><path class="p656mfb8u"/><g filter="url(#incXPxB)"><path class="vwjtcebbh"/><path fill="url(#iZbKFwb)" class="a__51vsxw"/></g><g filter="url(#iQtv1ze)"><path fill="url(#i8Xs0Cc)" class="mfhw-cvum"/></g><path class="me_o8f2oz"/><path fill="url(#iS7iY8K)" class="wtd65-u2b"/><path class="j87swcchf"/><g filter="url(#ig5TJxd)"><path fill="url(#i3uPREc)" class="qin2n4b9v"/></g><g filter="url(#iLKYxUu)"><ellipse transform="rotate(-27.914 14.746 12.942)" class="lu3hbwbqb"/><ellipse fill="url(#i3bVAMe)" transform="rotate(-27.914 14.746 12.942)" class="xhjtmplni"/></g><path fill="url(#iP0Gkib)" class="iitcneq-n"/><path fill="url(#i3n4gVb)" class="iitcneq-n"/><path fill="url(#iQLVWXd)" class="iitcneq-n"/><path fill="url(#iKmuiic)" class="iitcneq-n"/><path fill="url(#i7U8VKH)" class="c7q0f6bmy"/><path fill="url(#ixdZWpb)" class="c7q0f6bmy"/><g filter="url(#i3iL7PU)"><path fill="url(#iNPqCKc)" class="iq9afacqp"/></g><g filter="url(#iPQgrEe)"><path fill="url(#iPPz30b)" class="o9b44abss"/></g><g filter="url(#ipkjCkT)"><path class="mcwlni1od"/></g><g filter="url(#irRKQvs)"><path class="xsiyblbna"/></g><g filter="url(#iOr1Tcd)"><path class="r2dhuywbj"/></g><g filter="url(#i4LkWSd)"><path class="o556eqbvx"/></g><g filter="url(#izdwFAe)"><path class="hfj0iub-z"/></g><defs><radialGradient id="i0eMgUI" cx="0" cy="0" r="1" gradientTransform="matrix(-.00154 4.75464 -1.08171 -.00035 9.816 10.929)" gradientUnits="userSpaceOnUse"><stop class="qc5umhbsx"/><stop offset="1" class="ps5p_xb2b"/></radialGradient><radialGradient id="i8IhE7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 10.04 7.769)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="tuvsor_7r"/><stop offset="1" class="s_t4keb-b"/></radialGradient><radialGradient id="ia0ozfc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.362 6.832)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="dlijzhe6z"/><stop offset="1" class="rcswokzqh"/></radialGradient><radialGradient id="imdZvZc" cx="0" cy="0" r="1" gradientTransform="rotate(87.787 -1.122 2.973)scale(4.85666 1.64346)" gradientUnits="userSpaceOnUse"><stop class="xz64_6yvi"/><stop offset="1" class="y8dp0hbvk"/></radialGradient><radialGradient id="iJSh9Rd" cx="0" cy="0" r="1" gradientTransform="rotate(127.793 1.116 1.093)scale(1.67845 1.54056)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="suv_43jhc"/><stop offset="1" class="lqtoipbqj"/></radialGradient><radialGradient id="icTlMSc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="ghoayzsjh"/><stop offset="1" class="iglonxb_v"/></radialGradient><radialGradient id="iVAnGZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.375 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="il5AC0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 17.938 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="iE3hHec" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 17.781 5.695)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="i1HNLPr" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 8.96 6.273)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="i6eHjnx" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 3.991 3.074)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="ihrMxQQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.2132 .05173 -.03984 -.16419 8.083 6.282)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="igYlFZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 8.863 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="iA39zBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2259 .05875 -.04809 -.18493 8.777 6.312)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="icomEIe" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.03 3.12)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="iKUvYXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21457 .05712 -.04771 -.17925 10.179 6.32)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="i2lb2vb" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.687 3.116)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="irtIY9Z" cx="0" cy="0" r="1" gradientTransform="matrix(-.22656 .06252 -.05386 -.19519 9.496 6.362)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="ihUH0Ge" cx="0" cy="0" r="1" gradientTransform="matrix(-.39453 .51953 -.51953 -.39453 10.781 6.84)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="cvatkobbr"/><stop offset=".91" class="ydv5mwxxd"/></radialGradient><radialGradient id="igSWh8b" cx="0" cy="0" r="1" gradientTransform="rotate(124.323 3.627 6.223)scale(.31867 .23988)" gradientUnits="userSpaceOnUse"><stop class="op745bcjt"/><stop offset="1" class="n5tde31zi"/></radialGradient><radialGradient id="iuoWORd" cx="0" cy="0" r="1" gradientTransform="matrix(-.66762 0 0 -1.09544 24.218 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="i1gUcVd" cx="0" cy="0" r="1" gradientTransform="rotate(117.929 10.237 10.362)scale(.21624 .19082)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="i2g6S5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.70736 0 0 -1.24403 23.543 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="itN5bFe" cx="0" cy="0" r="1" gradientTransform="rotate(116.317 9.834 10.393)scale(.24205 .20513)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="ilQeege" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 0 0 -1.20947 22.124 5.895)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="iBbOMSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10193 .21094 -.17622 -.08515 22.093 6.198)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="ivMLBmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.70944 0 0 -1.32351 22.826 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="inblcIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10762 .23083 -.18853 -.0879 22.792 6.229)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="ibvUIjc" cx="0" cy="0" r="1" gradientTransform="rotate(127.213 .238 .266)scale(.65236)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="bmte3bbwj"/><stop offset=".91" class="wvhi0ab5z"/></radialGradient><radialGradient id="iLZeLcY" cx="0" cy="0" r="1" gradientTransform="rotate(124.323 .276 .232)scale(.31867 .23988)" gradientUnits="userSpaceOnUse"><stop class="kk6l23w0e"/><stop offset="1" class="sh5_80x3i"/></radialGradient><radialGradient id="i7nMPid" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.313 18.758)" gradientUnits="userSpaceOnUse"><stop class="vv2_9vbpq"/><stop offset="1" class="moznfwbra"/></radialGradient><radialGradient id="iuNDXud" cx="0" cy="0" r="1" gradientTransform="rotate(107.103 2.471 12.873)scale(2.4712 2.78644)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="riglhacpo"/><stop offset="1" class="w_5lt8b6v"/></radialGradient><radialGradient id="iFLqZSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 19.826 21.256)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="wx7ikuwun"/><stop offset="1" class="qljsz814e"/></radialGradient><radialGradient id="ii9TU6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.5 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iMd3cGY" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.294 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="ipt2RNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.074 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="ijEmnZt" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 2.773 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i1fW1XY" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.438 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iL5td6D" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.188 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="iID6PAd" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.145 12.111)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iQ3Ldac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.406 27.992)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="iIOJZDd" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.729 15.316)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="imGINwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.719 28.54)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="i0MC05c" cx="0" cy="0" r="1" gradientTransform="matrix(.35913 .96863 -1.15066 .42662 18.202 13.666)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iPdL0Wc" cx="0" cy="0" r="1" gradientTransform="matrix(.70815 .22255 -.68658 2.18473 13.016 13.9)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iVrVsub" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50743 0 0 -4.43561 17.268 13.215)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iFsjsdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.83607 1.38275 -1.14157 -.69024 17.086 10.827)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="ip8u89d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50743 0 0 -4.43561 17.268 13.215)" gradientUnits="userSpaceOnUse"><stop class="xgs1acvga"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="z1wntgb3x"/></radialGradient><radialGradient id="ijaFLNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.84375 .97852 0 14.936 12.778)" gradientUnits="userSpaceOnUse"><stop class="gu-v0xbtk"/><stop offset="1" class="fn0kk_f4l"/></radialGradient><radialGradient id="iBHmyce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72656 .84262 0 17.007 12.747)" gradientUnits="userSpaceOnUse"><stop class="gu-v0xbtk"/><stop offset="1" class="fn0kk_f4l"/></radialGradient><radialGradient id="ib8udxw" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.8649 -5.39687 0 15.944 12.31)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="rkm8-8bne"/><stop offset="1" class="t4cvdnfct"/></radialGradient><radialGradient id="ikY3Fjd" cx="0" cy="0" r="1" gradientTransform="rotate(-178.949 8.39 6.782)scale(3.40682 8.52924)" gradientUnits="userSpaceOnUse"><stop offset=".749" class="rxv7l7zto"/><stop offset="1" class="rkrbzc5cz"/></radialGradient><radialGradient id="i742MKY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .11708 -.36796 0 16.145 14.05)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iRrNy5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.72958 .3345 -.53758 -1.1725 16.201 13.777)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iOJslfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.67933 4.24684 0 13.414 11.828)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iarChnJ" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.644 -3.322)scale(1.20633 2.13737)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="isDQ70c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.13136 -.7441 .5462 -.83048 17.891 9.446)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iDk5VHd" cx="0" cy="0" r="1" gradientTransform="matrix(.32215 .5747 -1.33074 .74595 15.488 8.682)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iecd4xI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05572 0 0 -.39182 16.044 9.9)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="ivKFiDd" cx="0" cy="0" r="1" gradientTransform="matrix(1.54353 -2.44392 2.70761 1.71007 13.317 11.79)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iPq4Qyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.29392 -1.2241 2.24018 2.36796 17.194 11.843)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="ir5CvVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.569 .1821 -.07572 .6524 16.766 11.135)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iI0S7je" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38913 -.61896 0 16.97 12.988)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iZbKFwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.11123 -.14334 .19735 -.15314 16.86 13.028)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iS7iY8K" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38915 -.61899 0 14.877 12.988)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i3bVAMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00371 -.23698 .28486 -.00446 14.74 13.093)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3n4gVb" cx="0" cy="0" r="1" gradientTransform="matrix(.30147 1.07594 -1.02653 .28763 18.136 12.782)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iQLVWXd" cx="0" cy="0" r="1" gradientTransform="matrix(.37784 -.51853 .43463 .3167 18.31 13.043)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iKmuiic" cx="0" cy="0" r="1" gradientTransform="matrix(.28154 -.74363 .9936 .37618 18.364 13.126)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="ixdZWpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79534 0 0 -.8868 13.564 13.09)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iNPqCKc" cx="0" cy="0" r="1" gradientTransform="rotate(170.259 6.225 7.123)scale(.446 .45729)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><filter id="ihew9zc" width="9.5" height="4.284" x="11.172" y="21.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="iTQyArb" width="27.875" height="1.225" x="2.063" y="5.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="icts8Zc" width="27.781" height=".75" x="2.023" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".125"/></filter><filter id="isRCJUr" width="10.708" height="10.353" x="10.803" y="11.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.396078 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="iuUgO1e" width="1.93" height="8.989" x="5.039" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="ib3k0Ic" width="1.93" height="8.989" x="24.992" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="iilHhTC" width="1.93" height="5.973" x="3.109" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="ic2dkZc" width="1.93" height="5.973" x="26.922" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="itcfTEc" width="3.719" height="6.065" x="8.891" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.313726 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.25098 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23311" result="effect2_innerShadow_3987_23311"/></filter><filter id="iSYUqvd" width="4.477" height="4.023" x="8.516" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="iOhz5sb" width="4.833" height="2.114" x="7.039" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="i8dkrmb" width="3.719" height="5.564" x="19.922" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.313726 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.25098 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23311" result="effect2_innerShadow_3987_23311"/></filter><filter id="ipeNOkb" width="4.477" height="4.023" x="19.539" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="ibIcLue" width="4.833" height="2.114" x="20.159" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="iSBecvb" width="5.902" height="6.119" x="13.493" y="10.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23311" result="effect2_innerShadow_3987_23311"/></filter><filter id="iM4jhte" width="1.338" height="1.891" x="15.185" y="12.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".125"/></filter><filter id="i9FZYcd" width="1.1" height="1.591" x="15.372" y="12.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".05"/></filter><filter id="iivOTFd" width="6.174" height="4.268" x="12.835" y="8.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23311" result="effect2_innerShadow_3987_23311"/></filter><filter id="iBmFWLd" width="3.218" height="2.918" x="12.975" y="9.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/><feGaussianBlur result="effect2_foregroundBlur_3987_23311" stdDeviation=".075"/></filter><filter id="iFxwGpd" width="3.033" height="2.77" x="15.893" y="9.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".075"/></filter><filter id="incXPxB" width=".481" height=".438" x="16.566" y="12.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".05"/></filter><filter id="iQtv1ze" width=".636" height=".646" x="16.916" y="12.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".1"/></filter><filter id="ig5TJxd" width=".681" height=".707" x="14.786" y="12.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".1"/></filter><filter id="iLKYxUu" width=".542" height=".442" x="14.476" y="12.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".05"/></filter><filter id="i3iL7PU" width=".598" height="1.101" x="13.025" y="12.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".05"/></filter><filter id="iPQgrEe" width=".654" height="1.113" x="18.192" y="12.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".05"/></filter><filter id="ipkjCkT" width="2.306" height="1.222" x="16.453" y="10.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".125"/></filter><filter id="irRKQvs" width="1.177" height=".659" x="14.201" y="11.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="iOr1Tcd" width="1.177" height=".659" x="16.67" y="11.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23311"/></filter><filter id="i4LkWSd" width="1.094" height=".495" x="14.2" y="11.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".05"/></filter><filter id="izdwFAe" width="1.094" height=".495" x="16.655" y="11.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23311" stdDeviation=".05"/></filter><linearGradient id="iOjek6c" x1="7.163" x2="8.284" y1="7.95" y2="8.096" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ord38lb5d"/><stop offset="1" class="lagcd8brb"/></linearGradient><linearGradient id="iev7Igb" x1="-.572" x2=".549" y1="1.099" y2="1.245" gradientUnits="userSpaceOnUse"><stop offset=".136" class="pdrq0-vxx"/><stop offset="1" class="tldk1ryzb"/></linearGradient><linearGradient id="i0AhJLc" x1="20.313" x2="17.781" y1="25.258" y2="24.82" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="i8igjWE" x1="11.625" x2="14.438" y1="25.352" y2="24.258" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="ibRzype" x1="2.398" x2="29.867" y1="7.406" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="iAW9NPa" x1="5.039" x2="6.531" y1="7.477" y2="7.477" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="irsbW7b" x1="5.039" x2="5.313" y1="7.348" y2="7.348" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="iKoLy8d" x1="24.992" x2="26.188" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iqv6bwe" x1="2.958" x2="3.452" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="i9g91Cd" x1="11.874" x2="9.452" y1="25.825" y2="25.825" gradientUnits="userSpaceOnUse"><stop offset=".335" class="ykol_yz-a"/><stop offset="1" class="d19y5jbcp"/></linearGradient><linearGradient id="imrVfMc" x1="12.492" x2="8.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iHOi0qc" x1="23.141" x2="20.749" y1="25.206" y2="25.206" gradientUnits="userSpaceOnUse"><stop offset=".335" class="ykol_yz-a"/><stop offset="1" class="d19y5jbcp"/></linearGradient><linearGradient id="ixKrPfb" x1="19.539" x2="23.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="ilFe0ng" x1="16.324" x2="15.922" y1="13.721" y2="13.738" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iMboHxb" x1="15.922" x2="15.922" y1="14.268" y2="14.045" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iNY20fb" x1="15.922" x2="15.922" y1="12.97" y2="13.232" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="ibSifLb" x1="19.208" x2="13.639" y1="10.499" y2="10.499" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="i8Xs0Cc" x1="17.343" x2="17.192" y1="13.014" y2="13.106" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3uPREc" x1="15.233" x2="15.083" y1="13.014" y2="13.106" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iP0Gkib" x1="19.009" x2="18.43" y1="12.814" y2="13.858" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="i7U8VKH" x1="13.116" x2="13.816" y1="13.153" y2="13.092" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iPPz30b" x1="18.52" x2="18.52" y1="12.631" y2="13.544" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-lifting-weights-medium-dark" /></template>
<style>
.a__51vsxw {
  d: path("M16.94 12.85c.03.04-.034.09-.107.144c-.072.054-.126.092-.156.052c-.03-.041.003-.118.076-.172c.072-.055.156-.065.186-.025");
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bmte3bbwj {
  stop-color: var(--svg-color--75574d, #75574D);
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.c7q0f6bmy {
  d: path("M13.498 12.323a.772.772 0 0 0 .066 1.535a37 37 0 0 1-.066-1.535");
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cvatkobbr {
  stop-color: var(--svg-color--826255, #826255);
}

.d19y5jbcp {
  stop-color: var(--svg-color--855958, #855958);
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.d9_0_ybyb {
  stop-color: var(--svg-color--8e7570, #8E7570);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dlijzhe6z {
  stop-color: var(--svg-color--623c31, #623C31);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e4y-1lbum {
  r: 0.398px;
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.em3ofwhyw {
  d: path("m10.948 13.026l2.396-1.12l2.578 3.399l2.469-3.563l2.729 1.318a.25.25 0 0 1 .113.34l-1.194 2.303a1 1 0 0 0-.112.482l.12 5.76h-7.985v-5.788a1 1 0 0 0-.098-.433l-1.136-2.363a.25.25 0 0 1 .12-.335");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etpioe5tg {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.739 13.055l-.255.882c-.052.181.072.362.25.362h.376c.177 0 .302-.184.25-.362l-.255-.882c-.054-.195-.31-.195-.367 0");
}

.eyeh733jt {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.033 10.656l-.031-.066a.32.32 0 0 0-.295-.2h-.611c-.885 0-1.603.725-1.603 1.62v.132c-.163-.124-.368-.386-.368-.81c0-.514.375-.774.614-.94c.068-.046.125-.085.159-.12l.048-.051c.167-.178.466-.495.988-.633q.152-.04.302-.058c.469-.06.808.356.808.829v.29z");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f-egx61tq {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.07 12.629a.67.67 0 0 1 .65.507a.13.13 0 0 1-.129.164h-1.07a.11.11 0 0 1-.109-.13a.67.67 0 0 1 .658-.541");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.fn0kk_f4l {
  stop-color: var(--svg-color--76444b, #76444B);
  stop-opacity: 0;
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fzjqedceo {
  d: path("M24.992 29.53v.376H20.36v-1.914h2.352c.383.377 1.215.73 1.836.941c.398.169.445.442.445.597");
}

.g4offrb0h {
  d: path("M7.5 5.71a.399.399 0 1 1 .797-.034v.46a.38.38 0 0 1-.758.032z");
}

.g5fg-5cgy {
  d: path("M28.852 4.402a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.ghoayzsjh {
  stop-color: var(--svg-color--754c3c, #754C3C);
}

.gknucfb8h {
  cx: 10.586px;
  cy: 7px;
  r: 0.398px;
}

.gu-v0xbtk {
  stop-color: var(--svg-color--76444b, #76444B);
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
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

.hg2aihb7u {
  stop-color: var(--svg-color--6a3f41, #6A3F41);
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
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

.iglonxb_v {
  stop-color: var(--svg-color--754c3c, #754C3C);
  stop-opacity: 0;
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

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.j87swcchf {
  fill: var(--svg-color--000, #000);
  d: path("M15.12 13.187a.244.244 0 0 0-.244-.245a.244.244 0 0 0-.218.358h.434a.24.24 0 0 0 .029-.113");
}

.jpyi06dtg {
  stop-color: var(--svg-color--8e7570, #8E7570);
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kk6l23w0e {
  stop-color: var(--svg-color--886f6a, #886F6A);
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

.lagcd8brb {
  stop-color: var(--svg-color--562f3a, #562F3A);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqtoipbqj {
  stop-color: var(--svg-color--68423f, #68423F);
  stop-opacity: 0;
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
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

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcwlni1od {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M17.933 10.778h-.998a.232.232 0 1 1 .037-.461c.259.041.602.099.833.156c.52.129.664.382.704.563a.73.73 0 0 0-.576-.258");
}

.me_o8f2oz {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.776 12.629a.67.67 0 0 0-.65.507a.13.13 0 0 0 .129.164h1.07a.11.11 0 0 0 .109-.13a.67.67 0 0 0-.658-.541");
}

.mfhw-cvum {
  d: path("M17.352 13.13a.4.4 0 0 0-.11-.221l-.126.136l.057.11z");
}

.moznfwbra {
  stop-color: var(--svg-color--ff6621, #FF6621);
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n5tde31zi {
  stop-color: var(--svg-color--947870, #947870);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nm-q8ebbk {
  d: path("M8.16 5.627a.422.422 0 1 1 .844-.033v.584a.4.4 0 0 1-.798.031z");
}

.nvirpp9bq {
  d: path("m22.668 28.448l.473-5.464h-3.22l.479 5.464z");
}

.o556eqbvx {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.35 11.99a1.1 1.1 0 0 1 .793.182");
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.o9b44abss {
  d: path("m18.293 13.544l.053-.913a.458.458 0 0 1-.053.913");
}

.ob61f_0qn {
  stop-color: var(--svg-color--886b66, #886B66);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ol6tzlbff {
  d: path("m16.033 10.656l-.031-.066a.32.32 0 0 0-.295-.2h-.611c-.885 0-1.603.725-1.603 1.62v.132c-.163-.124-.368-.386-.368-.81c0-.514.375-.774.614-.94c.068-.046.125-.085.159-.12l.048-.051c.167-.178.466-.495.988-.633q.152-.04.302-.058c.469-.06.808.356.808.829v.29z");
}

.op745bcjt {
  stop-color: var(--svg-color--947870, #947870);
}

.ord38lb5d {
  stop-color: var(--svg-color--49252f, #49252F);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p656mfb8u {
  fill: var(--svg-color--000, #000);
  d: path("M16.726 13.187c0-.136.108-.245.245-.245a.244.244 0 0 1 .218.358h-.434a.2.2 0 0 1-.03-.113");
}

.pdrq0-vxx {
  stop-color: var(--svg-color--46212d, #46212D);
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.ps5p_xb2b {
  stop-color: var(--svg-color--7c4f4e, #7C4F4E);
}

.psru50bbi {
  d: path("M7.735 6.851h2.46v7.269h-2.46z");
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

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.qc5umhbsx {
  stop-color: var(--svg-color--9e7970, #9E7970);
}

.qd4tofb7u {
  d: path("M7.04 29.53v.376h4.632v-1.914H9.32c-.383.377-1.215.73-1.836.941c-.398.169-.445.442-.445.597");
}

.qin2n4b9v {
  d: path("M15.267 13.137c0-.139-.113-.231-.143-.259l-.138.134l.085.173z");
}

.qljsz814e {
  stop-color: var(--svg-color--ff8d41, #FF8D41);
  stop-opacity: 0;
}

.qno0gyhtd {
  d: path("M5.04 2.894a.8.8 0 0 1 .8-.8h.329a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r2dhuywbj {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M17.557 11.86a1.33 1.33 0 0 0-.825.21a.133.133 0 1 0 .144.224a1.07 1.07 0 0 1 .7-.163l.01.001h.001a.133.133 0 0 0 .055-.26z");
}

.r99zj9b9i {
  d: path("M18.253 13.814a.8.8 0 0 0 .434-.148v.447c0 .428-.255.81-.643.968q.123-.261.166-.566z");
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rcswokzqh {
  stop-color: var(--svg-color--623c31, #623C31);
  stop-opacity: 0;
}

.rh3jx3c9i {
  d: path("M23.108 5.588a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.015z");
}

.riglhacpo {
  stop-color: var(--svg-color--bd3f19, #BD3F19);
}

.rkm8-8bne {
  stop-color: var(--svg-color--804f5a, #804F5A);
  stop-opacity: 0;
}

.rkrbzc5cz {
  stop-color: var(--svg-color--825c56, #825C56);
}

.rmv72gx_s {
  fill: var(--svg-color--881452, #881452);
  d: path("M15.914 14.733c-.243 0-.472-.058-.664-.158c-.066-.033-.137.04-.095.1c.16.244.44.406.76.406a.91.91 0 0 0 .759-.406c.04-.062-.03-.133-.095-.1c-.193.1-.42.158-.665.158");
}

.rxv7l7zto {
  stop-color: var(--svg-color--825c56, #825C56);
  stop-opacity: 0;
}

.s_t4keb-b {
  stop-color: var(--svg-color--795a5b, #795A5B);
  stop-opacity: 0;
}

.s0g9yis6b {
  stop-color: var(--svg-color--62383a, #62383A);
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.s652backf {
  d: path("M16.97 12.759a.428.428 0 0 1 .413.54h-.827a.43.43 0 0 1 .415-.54");
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.sh5_80x3i {
  stop-color: var(--svg-color--886f6a, #886F6A);
  stop-opacity: 0;
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.suv_43jhc {
  stop-color: var(--svg-color--532a2a, #532A2A);
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t01v63bal {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m18.422 12.337l-.014-.303c.09-.446-.042-.684-.674-.684h-.672a1.16 1.16 0 0 1-1.018-.604s.345-.997.918-.868c.419.094.867.242 1.21.466c.837.546.69 1.53.25 1.992");
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t31_vej7y {
  fill: var(--svg-color--814e59, #814E59);
  d: path("m15.73 13.149l-.284.882c-.048.18.068.362.232.362h.351c.165 0 .28-.184.233-.363l-.238-.881c-.05-.195-.242-.195-.295 0");
}

.t4cvdnfct {
  stop-color: var(--svg-color--8d3f43, #8D3F43);
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.tldk1ryzb {
  stop-color: var(--svg-color--613e45, #613E45);
  stop-opacity: 0;
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tox4m5q8h {
  stop-color: var(--svg-color--816457, #816457);
}

.tphhgybtp {
  d: path("M26.922 2.894a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tuvsor_7r {
  stop-color: var(--svg-color--5a2e30, #5A2E30);
}

.twqjhifmu {
  d: path("M13.59 13.814a.8.8 0 0 1-.434-.148v.447c0 .428.255.81.643.968a2 2 0 0 1-.165-.566z");
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

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.ujo-xtz9c {
  stop-color: var(--svg-color--82665a, #82665A);
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

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vhhacgbon {
  d: path("M18.25 10.029c.247.085.468.257.608.504c.224.393.191.864-.05 1.212a.75.75 0 0 0-.13.419v.57a.8.8 0 0 0-.32-.129l.037-.77c-.005-.368-.295-.434-.661-.45h-.672a1.16 1.16 0 0 1-1.06-.692a.32.32 0 0 0-.295-.2h-.611c-.885 0-1.603.487-1.603 1.383l.015.737a.8.8 0 0 0-.345.127v-.576a.75.75 0 0 0-.13-.42a1.15 1.15 0 0 1-.069-1.173c.14-.264.367-.45.623-.54c.275-.098.51-.283.664-.532a1.115 1.115 0 0 1 1.387-.438c.183.08.389.08.572 0a1.115 1.115 0 0 1 1.392.453c.147.245.379.422.648.515");
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

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.wtd65-u2b {
  d: path("M14.876 12.759a.428.428 0 0 0-.413.54h.827a.43.43 0 0 0-.415-.54");
}

.wvhi0ab5z {
  stop-color: var(--svg-color--6d3e45, #6D3E45);
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

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xgs1acvga {
  stop-color: var(--svg-color--99695e, #99695E);
}

.xhjtmplni {
  cx: 14.746px;
  cy: 12.942px;
  rx: 0.187px;
  ry: 0.095px;
}

.xr8cplx4f {
  stop-color: var(--svg-color--886b66, #886B66);
  stop-opacity: 0;
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xsiyblbna {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M14.392 11.86q.076-.008.205 0c.168.014.393.063.62.21a.133.133 0 0 1-.144.224a1.07 1.07 0 0 0-.7-.163l-.01.001h-.002a.133.133 0 0 1-.054-.26z");
}

.xz64_6yvi {
  stop-color: var(--svg-color--845e5b, #845E5B);
}

.y0nqeezxq {
  d: path("M24.483 5.71a.399.399 0 1 0-.796-.034v.46a.38.38 0 0 0 .758.032z");
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y8dp0hbvk {
  stop-color: var(--svg-color--815651, #815651);
}

.ydv5mwxxd {
  stop-color: var(--svg-color--683842, #683842);
}

.yi6f0ib8n {
  d: path("m15.739 13.055l-.255.882c-.052.181.072.362.25.362h.376c.177 0 .302-.184.25-.362l-.255-.882c-.054-.195-.31-.195-.367 0");
}

.ykol_yz-a {
  stop-color: var(--svg-color--9d6f6b, #9D6F6B);
}

.z0ggixb3q {
  d: path("M9.592 5.626a.401.401 0 1 1 .803-.014v.575a.391.391 0 0 1-.783.013z");
}

.z1wntgb3x {
  stop-color: var(--svg-color--7c5150, #7C5150);
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
