<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iAtGm8V)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#iKn4JIK)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#ijohgZb)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#ilx8g8d)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#ijhvbUd)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#i4p5ckL)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iMUFE5c)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#istcbVc)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><g filter="url(#i2qX1cb)"><path fill="url(#iVAnGZb)" class="q1wg51bmi"/><path fill="url(#i0AhJLc)" class="q1wg51bmi"/><path fill="url(#i8igjWE)" class="q1wg51bmi"/><path fill="url(#il5AC0d)" class="q1wg51bmi"/></g><g filter="url(#iigaZMe)"><rect fill="url(#iE3hHec)" class="uywq_y1iv"/><rect fill="url(#i1HNLPr)" class="uywq_y1iv"/></g><g filter="url(#i59mf8c)"><path stroke="url(#ibRzype)" class="ijj045bhz"/></g><path fill="url(#iRVrkIe)" class="g4offrb0h"/><path fill="url(#iQ3Mx9b)" class="g4offrb0h"/><path fill="url(#iBNDPbb)" class="nm-q8ebbk"/><path fill="url(#igmQnNM)" class="nm-q8ebbk"/><path fill="url(#if5rUld)" class="z0ggixb3q"/><path fill="url(#iz3MF4A)" class="z0ggixb3q"/><path fill="url(#izRKeib)" class="tzfcre5-h"/><path fill="url(#iF6cLwb)" class="tzfcre5-h"/><circle fill="url(#iQawNoc)" class="gknucfb8h"/><circle fill="url(#iEFEqdb)" class="gknucfb8h"/><path fill="url(#iDQzX9b)" class="y0nqeezxq"/><path fill="url(#iHB7zpc)" class="y0nqeezxq"/><path fill="url(#iqRAT6e)" class="l2at7otgu"/><path fill="url(#i3LICSc)" class="l2at7otgu"/><path fill="url(#iXVyXFw)" class="ufmuzl7ni"/><path fill="url(#ieCk7td)" class="ufmuzl7ni"/><path fill="url(#iwnrHoc)" class="rh3jx3c9i"/><path fill="url(#iwLhEPc)" class="rh3jx3c9i"/><circle fill="url(#idBwAKb)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><circle fill="url(#icWCk4E)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><g filter="url(#iNy02ye)"><path fill="url(#ilmwlid)" class="em3ofwhyw"/><path fill="url(#iSuCE7b)" class="em3ofwhyw"/><path fill="url(#iTnerGc)" class="em3ofwhyw"/></g><g filter="url(#iOZHkUc)"><path fill="url(#ii9TU6b)" class="qno0gyhtd"/><path fill="url(#iAW9NPa)" class="qno0gyhtd"/><path fill="url(#irsbW7b)" class="qno0gyhtd"/></g><g filter="url(#iJ9KxIG)"><path fill="url(#iMd3cGY)" class="tphhgybtp"/><path fill="url(#iKoLy8d)" class="tphhgybtp"/></g><g filter="url(#iHVcmKd)"><path fill="url(#ipt2RNb)" class="x9t-2zb_r"/><path fill="url(#ijEmnZt)" class="x9t-2zb_r"/><path fill="url(#iqv6bwe)" class="x9t-2zb_r"/></g><g filter="url(#iD1RY3r)"><path fill="url(#i1fW1XY)" class="g5fg-5cgy"/><path fill="url(#iL5td6D)" class="g5fg-5cgy"/></g><g filter="url(#if01Iac)"><path fill="url(#iHyGpCc)" class="uv_bhvydh"/></g><g filter="url(#ik7KZ6d)"><path fill="url(#imrVfMc)" class="u6_y93pge"/><path fill="url(#iID6PAd)" class="u6_y93pge"/></g><g filter="url(#iHfhwEe)"><path fill="url(#iQ3Ldac)" class="qd4tofb7u"/></g><g filter="url(#iumeq2c)"><path fill="url(#iWMUMoR)" class="nvirpp9bq"/></g><g filter="url(#i2QgIvd)"><path fill="url(#ixKrPfb)" class="kv3enpo0a"/><path fill="url(#iIOJZDd)" class="kv3enpo0a"/></g><g filter="url(#i2iqCGc)"><path fill="url(#imGINwe)" class="fzjqedceo"/></g><g filter="url(#ipuxHub)"><path fill="url(#iUrfcyc)" class="wvmxhcn9h"/></g><g filter="url(#iBGAuKD)"><path clip-rule="evenodd" class="e3ekshbuk"/></g><path fill="url(#iK6pz8d)" class="e5o3emblx"/><path fill="url(#iFpZxcb)" class="m32e2_8tk"/><g filter="url(#ifY39Sd)"><path class="de8ueccwx"/></g><g filter="url(#iQQYICb)"><path class="uixp4tbqy"/></g><g filter="url(#iLBCRCc)"><path fill="url(#i1BCC1d)" class="l3q56jllz"/></g><path fill="url(#itNssue)" class="l3q56jllz"/><g filter="url(#isuKzqb)"><path class="woqyxdb2a"/></g><g filter="url(#iXeczgc)"><path class="klnn_kjkn"/><path fill="url(#iRBvESb)" class="udpehca1r"/><path fill="url(#iGz4W9J)" class="udpehca1r"/><path fill="url(#itMHvMc)" class="udpehca1r"/><path fill="url(#ihtQLdc)" class="udpehca1r"/></g><path class="a1lc6hzzk"/><g filter="url(#iSsNTVd)"><path class="uwa2r8bmj"/></g><g filter="url(#iWF24gs)"><path class="rsona7b8o"/></g><path class="pfdtyrvds"/><path fill="url(#idCEMtG)" class="vpqp6-_ll"/><path class="v5cgqrbmd"/><g filter="url(#imFWfDd)"><path class="dtzu0tber"/><path fill="url(#i3WLCoW)" class="fpz4pkb0n"/></g><g filter="url(#iFyMZms)"><path fill="url(#iSTxpeb)" class="pzbfed-2o"/></g><path class="zbzwr7bnt"/><path fill="url(#i552jXb)" class="qsxa21bvf"/><path class="autn18fuu"/><g filter="url(#ip19swc)"><path fill="url(#iQarmgd)" class="ofnof42ed"/></g><g filter="url(#i3rAdiJ)"><ellipse transform="rotate(-27.914 14.802 12.913)" class="e7agqcbws"/><ellipse fill="url(#ij1ySIR)" transform="rotate(-27.914 14.802 12.913)" class="jiuy1sqte"/></g><g filter="url(#iByrQfN)"><path fill="url(#ixAVVjd)" class="xh9tt-k8x"/></g><g filter="url(#iXd262b)"><path class="hnikazbjw"/><path fill="url(#iikBj8d)" class="s9xfdrbbz"/><path fill="url(#i5rHezp)" class="s9xfdrbbz"/></g><path class="ss5h4miuz"/><g filter="url(#ihH37sK)"><path class="wtwjh4bpw"/></g><path class="dtqzb6buh"/><g filter="url(#ijNeZdd)"><path class="i_-h0zmuj"/></g><defs><radialGradient id="iAtGm8V" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.557 10.368)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="nfiy_hbvi"/><stop offset="1" class="m844pcc9l"/></radialGradient><radialGradient id="ijohgZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81736 1.73031 -3.31873 -1.5677 10.181 7.328)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dms-h3b2e"/><stop offset="1" class="bx9frfb0m"/></radialGradient><radialGradient id="ilx8g8d" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.36 6.832)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="hwapycced"/><stop offset="1" class="g5p0-zbdt"/></radialGradient><radialGradient id="ijhvbUd" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.997 3.08)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="nfiy_hbvi"/><stop offset="1" class="m844pcc9l"/></radialGradient><radialGradient id="iMUFE5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.81736 1.73031 -3.31873 -1.5677 2.452 .476)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dms-h3b2e"/><stop offset="1" class="bx9frfb0m"/></radialGradient><radialGradient id="istcbVc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="hwapycced"/><stop offset="1" class="g5p0-zbdt"/></radialGradient><radialGradient id="iVAnGZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.375 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="il5AC0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 17.938 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="iE3hHec" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 17.781 5.695)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="i1HNLPr" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 8.96 6.273)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="iRVrkIe" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 3.991 3.074)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xmhbxgbvu"/><stop offset=".812" class="ve7x40mpw"/></radialGradient><radialGradient id="iQ3Mx9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.2132 .05173 -.03984 -.16419 8.083 6.282)" gradientUnits="userSpaceOnUse"><stop class="wl3r7lcsl"/><stop offset="1" class="i6vv_mv8s"/></radialGradient><radialGradient id="iBNDPbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 8.863 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xmhbxgbvu"/><stop offset=".812" class="ve7x40mpw"/></radialGradient><radialGradient id="igmQnNM" cx="0" cy="0" r="1" gradientTransform="matrix(-.2259 .05875 -.04809 -.18493 8.777 6.312)" gradientUnits="userSpaceOnUse"><stop class="wl3r7lcsl"/><stop offset="1" class="i6vv_mv8s"/></radialGradient><radialGradient id="if5rUld" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.03 3.12)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xmhbxgbvu"/><stop offset=".812" class="ve7x40mpw"/></radialGradient><radialGradient id="iz3MF4A" cx="0" cy="0" r="1" gradientTransform="matrix(-.21457 .05712 -.04771 -.17925 10.179 6.32)" gradientUnits="userSpaceOnUse"><stop class="wl3r7lcsl"/><stop offset="1" class="i6vv_mv8s"/></radialGradient><radialGradient id="izRKeib" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.687 3.116)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xmhbxgbvu"/><stop offset=".812" class="ve7x40mpw"/></radialGradient><radialGradient id="iF6cLwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.22656 .06252 -.05386 -.19519 9.496 6.362)" gradientUnits="userSpaceOnUse"><stop class="wl3r7lcsl"/><stop offset="1" class="i6vv_mv8s"/></radialGradient><radialGradient id="iQawNoc" cx="0" cy="0" r="1" gradientTransform="rotate(134.624 3.957 5.724)scale(.6044)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="hcub0sbsp"/><stop offset=".91" class="c7vbstbpd"/></radialGradient><radialGradient id="iEFEqdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .21094 -.20725 -.17654 10.827 6.85)" gradientUnits="userSpaceOnUse"><stop class="f4u_rabzt"/><stop offset="1" class="kqaolnnzx"/></radialGradient><radialGradient id="iDQzX9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.66762 0 0 -1.09544 24.218 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="v_irgab5s"/><stop offset="1" class="kfj3unbwb"/></radialGradient><radialGradient id="iHB7zpc" cx="0" cy="0" r="1" gradientTransform="rotate(117.929 10.237 10.362)scale(.21624 .19082)" gradientUnits="userSpaceOnUse"><stop class="a7a4ckbck"/><stop offset="1" class="n5n79mbfd"/></radialGradient><radialGradient id="iqRAT6e" cx="0" cy="0" r="1" gradientTransform="matrix(-.70736 0 0 -1.24403 23.543 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="v_irgab5s"/><stop offset="1" class="kfj3unbwb"/></radialGradient><radialGradient id="i3LICSc" cx="0" cy="0" r="1" gradientTransform="rotate(116.317 9.834 10.393)scale(.24205 .20513)" gradientUnits="userSpaceOnUse"><stop class="a7a4ckbck"/><stop offset="1" class="n5n79mbfd"/></radialGradient><radialGradient id="iXVyXFw" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 0 0 -1.20947 22.124 5.895)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="v_irgab5s"/><stop offset="1" class="kfj3unbwb"/></radialGradient><radialGradient id="ieCk7td" cx="0" cy="0" r="1" gradientTransform="matrix(-.10193 .21094 -.17622 -.08515 22.093 6.198)" gradientUnits="userSpaceOnUse"><stop class="a7a4ckbck"/><stop offset="1" class="n5n79mbfd"/></radialGradient><radialGradient id="iwnrHoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.70944 0 0 -1.32351 22.826 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="v_irgab5s"/><stop offset="1" class="kfj3unbwb"/></radialGradient><radialGradient id="iwLhEPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10762 .23083 -.18853 -.0879 22.792 6.229)" gradientUnits="userSpaceOnUse"><stop class="a7a4ckbck"/><stop offset="1" class="n5n79mbfd"/></radialGradient><radialGradient id="idBwAKb" cx="0" cy="0" r="1" gradientTransform="rotate(127.213 .238 .266)scale(.65236)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="yv16imbst"/><stop offset=".91" class="hqci1tzzd"/></radialGradient><radialGradient id="icWCk4E" cx="0" cy="0" r="1" gradientTransform="matrix(-.06323 .28125 -.28686 -.0645 .462 .182)" gradientUnits="userSpaceOnUse"><stop class="t72jz0b3q"/><stop offset="1" class="ov1n1eber"/></radialGradient><radialGradient id="ilmwlid" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.313 18.758)" gradientUnits="userSpaceOnUse"><stop class="cg05ombch"/><stop offset="1" class="i25jr6cdh"/></radialGradient><radialGradient id="iSuCE7b" cx="0" cy="0" r="1" gradientTransform="rotate(77.286 -1.694 16.51)scale(3.83375 5.43507)" gradientUnits="userSpaceOnUse"><stop offset=".102" class="v8rezjblq"/><stop offset="1" class="u1b9dcc6t"/></radialGradient><radialGradient id="iTnerGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 19.826 21.256)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="yyr7j8rnv"/><stop offset="1" class="ymbigdcyd"/></radialGradient><radialGradient id="ii9TU6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.5 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iMd3cGY" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.294 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="ipt2RNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.074 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="ijEmnZt" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 2.773 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i1fW1XY" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.438 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iL5td6D" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.188 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="iID6PAd" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.145 12.111)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iQ3Ldac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.406 27.992)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="iIOJZDd" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.729 15.316)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="imGINwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.719 28.54)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="iK6pz8d" cx="0" cy="0" r="1" gradientTransform="rotate(176.801 6.693 6.631)scale(.70031 .84071)" gradientUnits="userSpaceOnUse"><stop offset=".854" class="asc3twbme"/><stop offset="1" class="u7a4_41rw"/></radialGradient><radialGradient id="iFpZxcb" cx="0" cy="0" r="1" gradientTransform="rotate(102.937 4.21 13.572)scale(1.11341 1.65485)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="k1zfs4bht"/><stop offset=".311" class="oz9vowb0c"/></radialGradient><radialGradient id="i1BCC1d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65883 0 0 -2.57517 17.104 13.492)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="x9uj-ib0u"/><stop offset="1" class="s6yi5mbad"/></radialGradient><radialGradient id="itNssue" cx="0" cy="0" r="1" gradientTransform="matrix(-.00002 3.52409 -4.33659 -.00002 15.924 12.106)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="pjfqi1b3h"/><stop offset="1" class="nf854qblx"/></radialGradient><radialGradient id="iRBvESb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2082 -.93415 .2879 -.06416 16.282 13.773)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="ihtQLdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.3562 0 0 -.09958 16.173 13.87)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="idCEMtG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4167 -.66104 0 16.92 12.837)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="eijss2b4a"/><stop offset=".787" class="mj--szbch"/></radialGradient><radialGradient id="i3WLCoW" cx="0" cy="0" r="1" gradientTransform="matrix(-.10567 -.13617 .18747 -.14547 16.815 12.996)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i552jXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4167 -.66104 0 14.926 12.837)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="eijss2b4a"/><stop offset=".787" class="mj--szbch"/></radialGradient><radialGradient id="ij1ySIR" cx="0" cy="0" r="1" gradientTransform="matrix(-.00352 -.2251 .27059 -.00424 14.795 13.056)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixAVVjd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12349 1.33892 -.5517 -.46294 14.659 10.028)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iikBj8d" cx="0" cy="0" r="1" gradientTransform="matrix(.95313 -1.40625 3.25016 2.20289 16.371 11.117)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="cqgehjb7e"/><stop offset=".915" class="tg25gcbos"/></radialGradient><radialGradient id="i5rHezp" cx="0" cy="0" r="1" gradientTransform="matrix(1.77344 -.01562 .00498 .56499 16.754 11.078)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="dze8t3czh"/><stop offset="1" class="lejy49j7j"/></radialGradient><filter id="i2qX1cb" width="9.5" height="4.284" x="11.172" y="21.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="iigaZMe" width="27.875" height="1.225" x="2.063" y="5.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="i59mf8c" width="27.781" height=".75" x="2.023" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".125"/></filter><filter id="iNy02ye" width="10.708" height="10.353" x="10.803" y="11.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.196078 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="iOZHkUc" width="1.93" height="8.989" x="5.039" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="iJ9KxIG" width="1.93" height="8.989" x="24.992" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="iHVcmKd" width="1.93" height="5.973" x="3.109" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="iD1RY3r" width="1.93" height="5.973" x="26.922" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="if01Iac" width="3.719" height="6.065" x="8.891" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.690196 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.666667 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23321" result="effect2_innerShadow_3987_23321"/></filter><filter id="ik7KZ6d" width="4.477" height="4.023" x="8.516" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="iHfhwEe" width="4.833" height="2.114" x="7.039" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="iumeq2c" width="3.719" height="5.564" x="19.922" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.658824 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.639216 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23321" result="effect2_innerShadow_3987_23321"/></filter><filter id="i2QgIvd" width="4.477" height="4.023" x="19.539" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="i2iqCGc" width="4.833" height="2.114" x="20.159" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="ipuxHub" width=".636" height=".646" x="16.808" y="12.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".1"/></filter><filter id="iBGAuKD" width="6.864" height="7.364" x="12.492" y="8.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="ifY39Sd" width="1.282" height="1.282" x="17.489" y="12.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".075"/></filter><filter id="iQQYICb" width="1.282" height="1.282" x="13.15" y="12.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".075"/></filter><filter id="iLBCRCc" width="4.807" height="4.999" x="13.595" y="10.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.670588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="isuKzqb" width="1.358" height="1.726" x="15.171" y="12.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".125"/></filter><filter id="iXeczgc" width="1.058" height="1.426" x="15.395" y="12.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".05"/></filter><filter id="iSsNTVd" width="1.48" height=".587" x="16.246" y="12.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="iWF24gs" width="1.48" height=".587" x="14.122" y="12.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23321"/></filter><filter id="imFWfDd" width=".367" height=".326" x="16.581" y="12.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".025"/></filter><filter id="iFyMZms" width=".323" height=".333" x="17.011" y="12.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".025"/></filter><filter id="ip19swc" width=".367" height=".392" x="14.98" y="12.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".025"/></filter><filter id="i3rAdiJ" width=".425" height=".33" x="14.589" y="12.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".025"/></filter><filter id="iByrQfN" width="2.179" height="2.284" x="12.904" y="9.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".125"/></filter><filter id="iXd262b" width="4.546" height="3.437" x="14.185" y="8.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".125"/></filter><filter id="ihH37sK" width="1.024" height=".375" x="16.672" y="11.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".025"/></filter><filter id="ijNeZdd" width="1.024" height=".375" x="14.152" y="11.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23321" stdDeviation=".025"/></filter><linearGradient id="iKn4JIK" x1="7.383" x2="8.908" y1="7.933" y2="8.286" gradientUnits="userSpaceOnUse"><stop offset=".136" class="b8cveibhx"/><stop offset="1" class="f6hdy7bzf"/></linearGradient><linearGradient id="i4p5ckL" x1="-.347" x2="1.178" y1="1.081" y2="1.434" gradientUnits="userSpaceOnUse"><stop offset=".136" class="b8cveibhx"/><stop offset="1" class="f6hdy7bzf"/></linearGradient><linearGradient id="i0AhJLc" x1="20.313" x2="17.781" y1="25.258" y2="24.82" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="i8igjWE" x1="11.625" x2="14.438" y1="25.352" y2="24.258" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="ibRzype" x1="2.398" x2="29.867" y1="7.406" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="iAW9NPa" x1="5.039" x2="6.531" y1="7.477" y2="7.477" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="irsbW7b" x1="5.039" x2="5.313" y1="7.348" y2="7.348" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="iKoLy8d" x1="24.992" x2="26.188" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iqv6bwe" x1="2.958" x2="3.452" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="iHyGpCc" x1="12.28" x2="9.482" y1="24.627" y2="24.627" gradientUnits="userSpaceOnUse"><stop offset=".335" class="m3819-b2y"/><stop offset="1" class="z0dt5e0_f"/></linearGradient><linearGradient id="imrVfMc" x1="12.492" x2="8.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iWMUMoR" x1="23.686" x2="20.749" y1="25.206" y2="25.206" gradientUnits="userSpaceOnUse"><stop offset=".335" class="v4xj77b7s"/><stop offset="1" class="gjiuzgy3q"/></linearGradient><linearGradient id="ixKrPfb" x1="19.539" x2="23.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iUrfcyc" x1="17.234" x2="17.084" y1="13.014" y2="13.106" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGz4W9J" x1="15.495" x2="15.924" y1="13.806" y2="13.806" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="itMHvMc" x1="15.924" x2="15.924" y1="14.171" y2="13.892" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iSTxpeb" x1="17.275" x2="17.133" y1="12.981" y2="13.069" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQarmgd" x1="15.266" x2="15.123" y1="12.981" y2="13.069" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-lifting-weights-light" /></template>
<style>
.a1lc6hzzk {
  fill: var(--svg-color--89004e, #89004E);
  d: path("M15.913 14.572a1.4 1.4 0 0 1-.65-.157c-.064-.034-.133.04-.092.1a.883.883 0 0 0 1.485 0c.04-.062-.029-.134-.093-.1c-.188.1-.41.157-.65.157");
}

.a7a4ckbck {
  stop-color: var(--svg-color--ebbeaf, #EBBEAF);
}

.asc3twbme {
  stop-color: var(--svg-color--cc948c, #CC948C);
}

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.autn18fuu {
  fill: var(--svg-color--000, #000);
  d: path("M15.159 13.146a.23.23 0 0 0-.234-.233a.232.232 0 0 0-.207.34h.413a.23.23 0 0 0 .027-.107");
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.b8cveibhx {
  stop-color: var(--svg-color--906466, #906466);
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.bx9frfb0m {
  stop-color: var(--svg-color--c88f7e, #C88F7E);
  stop-opacity: 0;
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.c7vbstbpd {
  stop-color: var(--svg-color--d1998f, #D1998F);
}

.cg05ombch {
  stop-color: var(--svg-color--886fd9, #886FD9);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqgehjb7e {
  stop-color: var(--svg-color--474143, #474143);
  stop-opacity: 0;
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.de8ueccwx {
  fill: var(--svg-color--f1b9a3, #F1B9A3);
  d: path("M18.13 13.349a.49.49 0 1 0 0-.982a.49.49 0 0 0 0 .982");
}

.dms-h3b2e {
  stop-color: var(--svg-color--a37073, #A37073);
}

.dtqzb6buh {
  stroke: var(--svg-color--151515, #151515);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.076 12.16a1.3 1.3 0 0 0-.824-.166");
}

.dtzu0tber {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.891 12.825c.03.04-.031.086-.1.138c-.07.051-.12.088-.15.049c-.028-.039.004-.112.073-.164c.069-.051.148-.061.177-.023");
}

.dze8t3czh {
  stop-color: var(--svg-color--474144, #474144);
}

.e3ekshbuk {
  fill: var(--svg-color--32292f, #32292F);
  fill-rule: evenodd;
  d: path("M19.208 13.183a1.5 1.5 0 0 0 .025-1.249h.002a1.5 1.5 0 0 0-.128-.234l-.001-.001a1.5 1.5 0 0 1-.24-.81v-.004c0-.833-.676-1.508-1.508-1.508a.25.25 0 0 1-.208-.106a1.51 1.51 0 0 0-2.452 0a.26.26 0 0 1-.208.106h-.039a1.51 1.51 0 0 0-1.469 1.508v.004c0 .287-.083.57-.24.81l-.001.001a1.51 1.51 0 0 0-.1 1.483a.24.24 0 0 1 0 .209a1.47 1.47 0 0 0 1.323 2.114h3.921a1.47 1.47 0 0 0 1.323-2.114a.24.24 0 0 1 0-.209m-5.603-.886l.542.742c.056 1.28.556 0 1.777 0s1.753 1.425 1.81.144l.519-.937c-.025-.57-.437-.61-.52-.61h-1.471c-.581 0-1.13-.284-1.458-.764a.12.12 0 0 0-.21.024l-.038.088c-.257.716-.969.867-.951 1.313");
}

.e4y-1lbum {
  r: 0.398px;
}

.e5o3emblx {
  d: path("M13.782 13.593a.735.735 0 1 0 0-1.47a.735.735 0 0 0 0 1.47");
}

.e7agqcbws {
  cx: 14.802px;
  cy: 12.913px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.178px;
  ry: 0.09px;
}

.eijss2b4a {
  stop-color: var(--svg-color--8b6259, #8B6259);
}

.em3ofwhyw {
  d: path("m10.948 13.026l2.396-1.12l2.578 3.399l2.469-3.563l2.729 1.318a.25.25 0 0 1 .113.34l-1.194 2.303a1 1 0 0 0-.112.482l.12 5.76h-7.985v-5.788a1 1 0 0 0-.098-.433l-1.136-2.363a.25.25 0 0 1 .12-.335");
}

.f4u_rabzt {
  stop-color: var(--svg-color--fdd2c0, #FDD2C0);
}

.f6hdy7bzf {
  stop-color: var(--svg-color--c79990, #C79990);
  stop-opacity: 0;
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.fpz4pkb0n {
  d: path("M16.891 12.825c.03.04-.031.086-.1.138c-.07.051-.12.088-.15.049c-.028-.039.004-.112.073-.164c.069-.051.148-.061.177-.023");
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

.g5p0-zbdt {
  stop-color: var(--svg-color--eeb8a1, #EEB8A1);
  stop-opacity: 0;
}

.gjiuzgy3q {
  stop-color: var(--svg-color--e9b4a6, #E9B4A6);
}

.gknucfb8h {
  cx: 10.586px;
  cy: 7px;
  r: 0.398px;
}

.hcub0sbsp {
  stop-color: var(--svg-color--e8b7a2, #E8B7A2);
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.hnikazbjw {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.575 9.098c-.78 0-1.082.677-1.14.884c.761 1.788 1.762 1.536 3.228 1.536c.782 0 .752.346.818.518c-.215-2.004-1.375-2.938-2.906-2.938");
}

.hqci1tzzd {
  stop-color: var(--svg-color--ce978f, #CE978F);
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.hwapycced {
  stop-color: var(--svg-color--d89c7f, #D89C7F);
}

.i_-h0zmuj {
  stroke: var(--svg-color--2c2a2c, #2C2A2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.076 12.16a1.3 1.3 0 0 0-.824-.166");
}

.i25jr6cdh {
  stop-color: var(--svg-color--694cb1, #694CB1);
}

.i6vv_mv8s {
  stop-color: var(--svg-color--ffd6c1, #FFD6C1);
  stop-opacity: 0;
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
}

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.ijj045bhz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.398 6.406H29.43");
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.jiuy1sqte {
  cx: 14.802px;
  cy: 12.913px;
  rx: 0.178px;
  ry: 0.09px;
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.k1zfs4bht {
  stop-color: var(--svg-color--fbcbb6, #FBCBB6);
}

.kfj3unbwb {
  stop-color: var(--svg-color--d19c91, #D19C91);
}

.klnn_kjkn {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.749 13.033l-.243.777c-.05.16.07.32.238.32h.36a.247.247 0 0 0 .237-.32l-.243-.777c-.052-.172-.295-.172-.35 0");
}

.kqaolnnzx {
  stop-color: var(--svg-color--fdd2c0, #FDD2C0);
  stop-opacity: 0;
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

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l3q56jllz {
  d: path("M13.599 12.487h.006l-.005-.121l-.005-.14c.01-.434.263-.601.37-.657l.024-.01l.023-.009c.244-.112.44-.308.544-.564l.038-.13a.12.12 0 0 1 .21-.022c.328.48.877.776 1.458.776h1.471c.083 0 .495.069.52.637l-.054 1.243c-.056 1.28-1.057 2.14-2.277 2.14s-2.222-.86-2.278-2.14z");
}

.lejy49j7j {
  stop-color: var(--svg-color--474144, #474144);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m0j2adc3x {
  d: path("M7.73 6.851h2.46v7.269H7.73z");
}

.m32e2_8tk {
  d: path("M18.13 13.593a.735.735 0 1 0 0-1.47a.735.735 0 0 0 0 1.47");
}

.m3819-b2y {
  stop-color: var(--svg-color--ffd8c5, #FFD8C5);
}

.m844pcc9l {
  stop-color: var(--svg-color--dead9f, #DEAD9F);
}

.mj--szbch {
  stop-color: var(--svg-color--875b54, #875B54);
}

.n5n79mbfd {
  stop-color: var(--svg-color--ebbeaf, #EBBEAF);
  stop-opacity: 0;
}

.nf854qblx {
  stop-color: var(--svg-color--b97b9b, #B97B9B);
}

.nfiy_hbvi {
  stop-color: var(--svg-color--ffc8b2, #FFC8B2);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nm-q8ebbk {
  d: path("M8.16 5.627a.422.422 0 1 1 .844-.033v.584a.4.4 0 0 1-.798.031z");
}

.nvirpp9bq {
  d: path("m22.668 28.448l.473-5.464h-3.22l.479 5.464z");
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofnof42ed {
  d: path("M15.297 13.098c0-.131-.106-.219-.135-.246l-.132.128l.081.164z");
}

.ov1n1eber {
  stop-color: var(--svg-color--e7bdaf, #E7BDAF);
  stop-opacity: 0;
}

.oz9vowb0c {
  stop-color: var(--svg-color--e3afa2, #E3AFA2);
}

.pfdtyrvds {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.016 12.615a.64.64 0 0 1 .62.484a.125.125 0 0 1-.123.155h-1.02a.105.105 0 0 1-.103-.124a.64.64 0 0 1 .626-.515");
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pjfqi1b3h {
  stop-color: var(--svg-color--d49b9a, #D49B9A);
  stop-opacity: 0;
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

.pzbfed-2o {
  d: path("M17.284 13.092a.4.4 0 0 0-.105-.21l-.118.13l.053.103z");
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

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qd4tofb7u {
  d: path("M7.04 29.53v.376h4.632v-1.914H9.32c-.383.377-1.215.73-1.836.941c-.398.169-.445.442-.445.597");
}

.qno0gyhtd {
  d: path("M5.04 2.894a.8.8 0 0 1 .8-.8h.329a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qsxa21bvf {
  d: path("M14.925 12.739a.407.407 0 0 0-.393.515h.787a.41.41 0 0 0-.394-.515");
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rh3jx3c9i {
  d: path("M23.108 5.588a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.015z");
}

.rsona7b8o {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.402 12.97c-.121-.214-.306-.382-.703-.382a.76.76 0 0 0-.49.168c-.123.1-.106.227-.011.274l.254.145c.298-.096.627-.109.95-.205");
}

.s6yi5mbad {
  stop-color: var(--svg-color--dea59d, #DEA59D);
}

.s9xfdrbbz {
  d: path("M15.575 9.098c-.78 0-1.082.677-1.14.884c.761 1.788 1.762 1.536 3.228 1.536c.782 0 .752.346.818.518c-.215-2.004-1.375-2.938-2.906-2.938");
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.ss5h4miuz {
  stroke: var(--svg-color--151515, #151515);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.772 12.16c.116-.066.386-.21.823-.166");
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t72jz0b3q {
  stop-color: var(--svg-color--e7bdaf, #E7BDAF);
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tg25gcbos {
  stop-color: var(--svg-color--474143, #474143);
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
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

.u1b9dcc6t {
  stop-color: var(--svg-color--624ba3, #624BA3);
  stop-opacity: 0;
}

.u6_y93pge {
  d: path("M8.516 21.066a1.988 1.988 0 1 1 3.976 0v1.686a.35.35 0 0 1-.35.35H8.866a.35.35 0 0 1-.35-.35z");
}

.u7a4_41rw {
  stop-color: var(--svg-color--dea897, #DEA897);
}

.udpehca1r {
  d: path("m15.749 13.033l-.243.777c-.05.16.07.32.238.32h.36a.247.247 0 0 0 .237-.32l-.243-.777c-.052-.172-.295-.172-.35 0");
}

.ufmuzl7ni {
  d: path("M22.392 5.626a.401.401 0 1 0-.803-.014v.575a.391.391 0 0 0 .783.013z");
}

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.uixp4tbqy {
  fill: var(--svg-color--ca9182, #CA9182);
  d: path("M13.791 13.349a.49.49 0 1 0 0-.982a.49.49 0 0 0 0 .982");
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

.uwa2r8bmj {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.446 12.97c.121-.214.305-.382.702-.382c.174 0 .342.048.49.168c.123.1.107.227.012.274l-.254.145c-.298-.096-.628-.109-.95-.205");
}

.uywq_y1iv {
  width: 27.875px;
  height: 1.025px;
  x: 2.063px;
  y: 5.975px;
  rx: 0.2px;
}

.v_irgab5s {
  stop-color: var(--svg-color--edc2aa, #EDC2AA);
}

.v4xj77b7s {
  stop-color: var(--svg-color--ffd9c4, #FFD9C4);
}

.v5cgqrbmd {
  fill: var(--svg-color--000, #000);
  d: path("M16.688 13.146c0-.13.104-.233.233-.233a.232.232 0 0 1 .208.34h-.413a.2.2 0 0 1-.028-.107");
}

.v8rezjblq {
  stop-color: var(--svg-color--402b83, #402B83);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.ve7x40mpw {
  stop-color: var(--svg-color--f1c3a4, #F1C3A4);
}

.vpqp6-_ll {
  d: path("M16.921 12.739a.407.407 0 0 1 .393.515h-.787a.41.41 0 0 1 .394-.515");
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.wl3r7lcsl {
  stop-color: var(--svg-color--ffd6c1, #FFD6C1);
}

.woqyxdb2a {
  fill: var(--svg-color--db9d96, #DB9D96);
  d: path("m15.745 13.096l-.313.777c-.05.16.07.32.238.32h.36a.247.247 0 0 0 .237-.32l-.242-.777c-.052-.172-.226-.172-.28 0");
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.wtwjh4bpw {
  stroke: var(--svg-color--2c2a2c, #2C2A2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.772 12.16c.116-.066.386-.21.823-.166");
}

.wvmxhcn9h {
  d: path("M17.243 13.13a.4.4 0 0 0-.11-.221l-.125.136l.056.11z");
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.x9t-2zb_r {
  d: path("M3.11 4.402a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.x9uj-ib0u {
  stop-color: var(--svg-color--ffe0c4, #FFE0C4);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xh9tt-k8x {
  d: path("M13.727 10.207c.284-.253.693-.255.923-.214l.184.59a.36.36 0 0 0-.31.107c-.209.576-1.02.98-1.353 1.067c-.069-.682.066-1.113.556-1.55");
}

.xmhbxgbvu {
  stop-color: var(--svg-color--ffd9c0, #FFD9C0);
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y0nqeezxq {
  d: path("M24.483 5.71a.399.399 0 1 0-.796-.034v.46a.38.38 0 0 0 .758.032z");
}

.ymbigdcyd {
  stop-color: var(--svg-color--8263c1, #8263C1);
  stop-opacity: 0;
}

.yv16imbst {
  stop-color: var(--svg-color--d9aa99, #D9AA99);
}

.yyr7j8rnv {
  stop-color: var(--svg-color--5a3e9b, #5A3E9B);
}

.z0dt5e0_f {
  stop-color: var(--svg-color--edb7a7, #EDB7A7);
}

.z0ggixb3q {
  d: path("M9.592 5.626a.401.401 0 1 1 .803-.014v.575a.391.391 0 0 1-.783.013z");
}

.zbzwr7bnt {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.83 12.615a.64.64 0 0 0-.619.484c-.02.08.041.155.123.155h1.02a.105.105 0 0 0 .103-.124a.64.64 0 0 0-.626-.515");
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

</style>
