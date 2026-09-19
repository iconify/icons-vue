<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ihhr8hd)" class="h-lv1ubvk"/><path fill="url(#isMxGVz)" class="h-lv1ubvk"/><path class="fgyy3cclr"/><path fill="url(#il4bdjb)" class="u43ch0b3o"/><path fill="url(#iW8yVeb)" class="u43ch0b3o"/><path fill="url(#ilwSyMe)" class="u43ch0b3o"/><path fill="url(#ipMQjDc)" class="u43ch0b3o"/><path fill="url(#ieEwfyb)" class="job-vz29n"/><path fill="url(#ibPlbGX)" class="job-vz29n"/><path fill="url(#i1LfFnc)" class="job-vz29n"/><path fill="url(#idbpoub)" class="zc_ep_0uq"/><path fill="url(#iXwlnbA)" class="zc_ep_0uq"/><path fill="url(#ibfF9pc)" class="g8oaksl8k"/><path fill="url(#iSVIuZb)" class="g8oaksl8k"/><path fill="url(#iyT5utc)" class="g8oaksl8k"/><path fill="url(#iwDqPAI)" class="g8oaksl8k"/><path fill="url(#ipFI5hc)" class="g8oaksl8k"/><path fill="url(#iqYNBEd)" class="g8oaksl8k"/><path fill="url(#iAsh0Wp)" class="g8oaksl8k"/><g filter="url(#izV1The)"><path class="edkhrwbqz"/><path fill="url(#iqTZBPc)" class="g43afac9g"/><path fill="url(#inhs3Gr)" class="g43afac9g"/><path fill="url(#iQdlE2c)" class="g43afac9g"/><path stroke="url(#iXHj40b)" class="xp31u8b0s"/></g><g filter="url(#ieQNwEd)"><path class="h5iei_ivh"/><path fill="url(#ihdS4Xd)" class="xr99hwbgq"/><path fill="url(#iiaVL3o)" class="xr99hwbgq"/></g><g filter="url(#i529zhb)"><path fill="url(#iOxWFad)" class="d86qxubue"/><path fill="url(#ir99qxd)" class="d86qxubue"/></g><path fill="url(#iDiuhqc)" class="zcpjvdbuo"/><path fill="url(#iDiuhqc)" class="zcpjvdbuo"/><path fill="url(#iDqN3pV)" class="p7xat6cnl"/><path fill="url(#iirSkZf)" class="p7xat6cnl"/><path fill="url(#iIjIJec)" class="p7xat6cnl"/><path fill="url(#ixovgFc)" class="w879bpb0e"/><path fill="url(#iAwNGNd)" class="w879bpb0e"/><path fill="url(#i4jnpHd)" class="w879bpb0e"/><path fill="url(#ighCgpe)" class="h-e6v32ai"/><path fill="url(#ix5gnYc)" class="h-e6v32ai"/><path fill="url(#iJEWtud)" class="h-e6v32ai"/><path fill="url(#i2e03Ec)" class="h-e6v32ai"/><path fill="url(#i7Hsxxd)" class="h-e6v32ai"/><path fill="url(#iuAwBNe)" class="h-e6v32ai"/><path fill="url(#isDXaed)" class="h-e6v32ai"/><g filter="url(#iFdvrBe)"><path fill="url(#iU7U3XT)" class="hbrxqdets"/><path fill="url(#isPRIKd)" class="hbrxqdets"/><path fill="url(#iJ9f8Uc)" class="hbrxqdets"/><path fill="url(#iGFMqWH)" class="hbrxqdets"/><path fill="url(#iRjmOQY)" class="hbrxqdets"/><path fill="url(#iheSTgO)" class="hbrxqdets"/><path stroke="url(#iGAAS2d)" class="lgnz4ib3a"/></g><g filter="url(#i9GbyfR)"><path fill="url(#i8ElAPc)" class="b43uiy30g"/><path fill="url(#ieaWAvd)" class="b43uiy30g"/><path fill="url(#ikytyIb)" class="b43uiy30g"/><path fill="url(#iW4kXJz)" class="b43uiy30g"/></g><path fill="url(#iUDojFc)" class="d-kfqjw9b"/><path fill="url(#iNZ1RrM)" class="d-kfqjw9b"/><path fill="url(#i63AZyd)" class="bn4p-sbtt"/><g filter="url(#iajjOOw)"><path stroke="url(#i2O0dbd)" class="lehnoh0zf"/></g><path fill="url(#i9PjRok)" class="vww-fqhwh"/><path fill="url(#i11YRMe)" class="vww-fqhwh"/><path fill="url(#iaiUvYc)" class="vj4jwbgtj"/><circle fill="url(#iDA8kBb)" class="haiup_bzr"/><circle fill="url(#iQBx3Zc)" class="l0dpenbvj"/><g filter="url(#isayadc)"><circle class="gv_675b8w"/></g><g filter="url(#iblXWuc)"><circle fill="url(#idkJ77c)" class="h79oecc1t"/></g><g filter="url(#ipO5and)"><path fill="url(#ivCiGge)" class="yj5dctbip"/><path fill="url(#iGgA2he)" class="yj5dctbip"/><path fill="url(#iIEFGdb)" class="yj5dctbip"/></g><path fill="url(#iSJRkGc)" class="yj5dctbip"/><g filter="url(#iCK2b2b)"><path stroke="url(#iiTH5ne)" class="vzg4cacsm"/></g><path class="g_yeoeb7z"/><g filter="url(#iTIwSsq)"><path class="bpqf_uv7t"/></g><path class="f0nb6xb4v"/><path fill="url(#iQh5hlb)" class="j_2ccnt5p"/><path fill="url(#iTCgt2b)" class="j_2ccnt5p"/><path fill="url(#iNgtIlf)" class="j_2ccnt5p"/><path fill="url(#ilu7A9c)" class="j_2ccnt5p"/><path class="qz94s4bip"/><path fill="url(#i59hpcb)" class="cedz8lbio"/><path class="a07exk92a"/><g filter="url(#i1e2nJl)"><path class="xo9yuc7kj"/><path fill="url(#ihfUwfd)" class="haktz9bdu"/></g><g filter="url(#ic14lRB)"><path fill="url(#ix5afEe)" class="a4o2qybrp"/></g><path class="x9uzmjbio"/><path fill="url(#isqlRBC)" class="etcccebor"/><path class="cfof8-eyu"/><g filter="url(#ifjHoie)"><path fill="url(#iKY1KDc)" class="uj99bl4ra"/></g><g filter="url(#iBGNSJc)"><ellipse transform="rotate(-27.914 13.293 14.206)" class="f_5qi3ocn"/><ellipse fill="url(#iHvtRfe)" transform="rotate(-27.914 13.293 14.206)" class="vjxojz0pl"/></g><path clip-rule="evenodd" class="llv8b_5gn"/><path clip-rule="evenodd" class="gs_ecdl4e"/><g filter="url(#iywQKed)"><path class="f4tj_uwsg"/></g><g filter="url(#i606Goc)"><path class="f-4jpbbcr"/></g><g filter="url(#iL8h91c)"><path fill="url(#iP3ZHLd)" clip-rule="evenodd" class="ouyjj2-hs"/></g><g filter="url(#iGzPhrc)"><path fill="url(#i3icBIe)" class="wx5i2acfu"/><path fill="url(#ieKgpEb)" class="wx5i2acfu"/><path fill="url(#iXpxY5c)" class="wx5i2acfu"/><path fill="url(#iqyM8Fd)" class="wx5i2acfu"/><path fill="url(#iwcE5mb)" class="wx5i2acfu"/></g><g filter="url(#iEmmEAd)"><path stroke="url(#ikdzT8X)" class="m52m3hl4m"/></g><g filter="url(#iSrpeUw)"><path stroke="url(#ieqS9Gd)" class="fdfbu9b0b"/></g><g filter="url(#iza7n3d)"><path stroke="url(#iY3AXue)" class="n2acyj-6i"/></g><defs><radialGradient id="ihhr8hd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68781 1.6831 -2.07966 -2.08548 28.143 23.303)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="isMxGVz" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .30308 .39805 27.817 23.52)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="il4bdjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.03125 7.18055 0 20.738 30.442)" gradientUnits="userSpaceOnUse"><stop class="xhqrsjbac"/><stop offset="1" class="ebcvm6lto"/></radialGradient><radialGradient id="iW8yVeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.6875 .78125 0 22.988 29.817)" gradientUnits="userSpaceOnUse"><stop class="wup_v_x-y"/><stop offset="1" class="rec-1hb8e"/></radialGradient><radialGradient id="ilwSyMe" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 0 0 19.1959 8.613 29.996)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="mr4lhnuux"/><stop offset="1" class="q-3947b0q"/></radialGradient><radialGradient id="ipMQjDc" cx="0" cy="0" r="1" gradientTransform="rotate(-136.837 16.423 12.118)scale(15.1664 18.2252)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="q-3947b0q"/><stop offset="1" class="dgbyghhck"/></radialGradient><radialGradient id="ieEwfyb" cx="0" cy="0" r="1" gradientTransform="matrix(.30005 -6.75 3.83344 .1704 8.594 29.88)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="e7_y1ioqg"/><stop offset="1" class="o8c2nzb0a"/></radialGradient><radialGradient id="ibPlbGX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.125 3.97458 0 6.734 30.192)" gradientUnits="userSpaceOnUse"><stop class="dn-ogvbjy"/><stop offset="1" class="inpzxhbwc"/></radialGradient><radialGradient id="i1LfFnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.63745 0 0 -7.24389 8.594 29.996)" gradientUnits="userSpaceOnUse"><stop class="a3c-8ubyu"/><stop offset="1" class="x9tw1mbfn"/></radialGradient><radialGradient id="idbpoub" cx="0" cy="0" r="1" gradientTransform="rotate(82.372 -.267 24.058)scale(8.94581 3.16756)" gradientUnits="userSpaceOnUse"><stop class="embu-7brp"/><stop offset="1" class="veybn72ma"/></radialGradient><radialGradient id="iXwlnbA" cx="0" cy="0" r="1" gradientTransform="matrix(.83557 0 0 8.41461 22.84 29.996)" gradientUnits="userSpaceOnUse"><stop class="rj_n-mbmd"/><stop offset=".85" class="sfuw4b7fs"/></radialGradient><radialGradient id="iSVIuZb" cx="0" cy="0" r="1" gradientTransform="rotate(124.902 .777 14.461)scale(1.63847 5.18259)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="dekz5-i5a"/><stop offset="1" class="takbm9boj"/></radialGradient><radialGradient id="iyT5utc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.625 -11.4392 0 15.709 19.723)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="tclwz7mny"/><stop offset="1" class="c5r226cip"/></radialGradient><radialGradient id="iwDqPAI" cx="0" cy="0" r="1" gradientTransform="matrix(4.9375 -2.78125 .65585 1.16432 19.27 21.973)" gradientUnits="userSpaceOnUse"><stop class="zm3svk-ip"/><stop offset="1" class="f-m4mzz6d"/></radialGradient><radialGradient id="ipFI5hc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75002 2.37497 -1.68941 -2.66754 10.738 18.16)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="d45gne0nz"/><stop offset="1" class="f283fd8-c"/></radialGradient><radialGradient id="iqYNBEd" cx="0" cy="0" r="1" gradientTransform="rotate(-69.233 29.08 .534)scale(10.4881 22.9861)" gradientUnits="userSpaceOnUse"><stop offset=".677" class="nypzj9bha"/><stop offset=".949" class="nvdrdzbmz"/></radialGradient><radialGradient id="iAsh0Wp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.88478 14.4983 0 15.709 24.613)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="bgqsi-bps"/><stop offset=".985" class="f-3q63keb"/></radialGradient><radialGradient id="iqTZBPc" cx="0" cy="0" r="1" gradientTransform="matrix(.76562 -.87496 3.20566 2.80509 14.77 24.473)" gradientUnits="userSpaceOnUse"><stop class="rdaygdbpu"/><stop offset="1" class="zajsytjse"/></radialGradient><radialGradient id="iQdlE2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.42187 -.46875 4.21008 -3.78904 19.441 22.223)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="i2wlb99xo"/><stop offset="1" class="l15dqlbvn"/></radialGradient><radialGradient id="iXHj40b" cx="0" cy="0" r="1" gradientTransform="matrix(.8298 -1.3125 2.13746 1.35137 14.879 24.238)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="fqpzwo9rb"/><stop offset="1" class="vyxwjf9nd"/></radialGradient><radialGradient id="ihdS4Xd" cx="0" cy="0" r="1" gradientTransform="matrix(2.15282 1.92743 -3.57495 3.993 14.056 21.223)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="kjht8876i"/><stop offset="1" class="m2k7t6jeu"/></radialGradient><radialGradient id="iiaVL3o" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48318 3.03117 -.28115 -.13757 17.117 21.223)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="a4bu2nb4b"/><stop offset="1" class="re9u_5b4n"/></radialGradient><radialGradient id="iOxWFad" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 .96875 -.2841 1.50295 17.082 3.16)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="s_1mw_rhq"/><stop offset="1" class="pql562bff"/></radialGradient><radialGradient id="iDqN3pV" cx="0" cy="0" r="1" gradientTransform="matrix(-4.62501 2.59374 -3.8683 -6.89775 17.988 3.817)" gradientUnits="userSpaceOnUse"><stop offset=".063" class="uhl03ccti"/><stop offset="1" class="uuh3gfbsu"/></radialGradient><radialGradient id="iIjIJec" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6875 -1.30125 2.428 -12.47818 18.77 7.535)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="tsk-k9bvn"/><stop offset="1" class="phlvo2b_b"/></radialGradient><radialGradient id="ighCgpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15156 -24.7184 0 15.75 9.333)" gradientUnits="userSpaceOnUse"><stop class="r-yilwbra"/><stop offset=".652" class="vxkgnhd4n"/></radialGradient><radialGradient id="ix5gnYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.64742 -17.2274 0 13.022 8.98)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="huu-ickwn"/><stop offset="1" class="t4ibp7bdp"/></radialGradient><radialGradient id="iJEWtud" cx="0" cy="0" r="1" gradientTransform="matrix(-8.68356 0 0 -2.80263 25.977 10.71)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="p5_1r5b0y"/><stop offset="1" class="bkffn87la"/></radialGradient><radialGradient id="i2e03Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-10.1661 0 0 -1.56292 25.094 9.554)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="zdk8j6bjz"/><stop offset="1" class="lmlq_xbrl"/></radialGradient><radialGradient id="i7Hsxxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.15365 1.28841 0 24.918 11.91)" gradientUnits="userSpaceOnUse"><stop offset=".051" class="o8p2_blib"/><stop offset="1" class="szwxs1ffj"/></radialGradient><radialGradient id="iuAwBNe" cx="0" cy="0" r="1" gradientTransform="rotate(-119.268 10.579 6.104)scale(3.2599 6.67388)" gradientUnits="userSpaceOnUse"><stop class="vmjr7rbhn"/><stop offset="1" class="zxip0bczk"/></radialGradient><radialGradient id="isDXaed" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 0 0 1.78125 21.332 18.192)" gradientUnits="userSpaceOnUse"><stop class="iusprebiv"/><stop offset="1" class="n4ma-nbis"/></radialGradient><radialGradient id="iU7U3XT" cx="0" cy="0" r="1" gradientTransform="matrix(-8.43067 -6.22495 7.88718 -10.6819 24.176 17.817)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="qxprq_b_n"/><stop offset="1" class="id0y_n31u"/></radialGradient><radialGradient id="isPRIKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.19531 0 0 .58033 20.863 13.285)" gradientUnits="userSpaceOnUse"><stop class="azeqcu15x"/><stop offset="1" class="sda7dac5x"/></radialGradient><radialGradient id="iJ9f8Uc" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 .70313 -.43994 .44972 20.066 11.723)" gradientUnits="userSpaceOnUse"><stop class="vnbqzxbma"/><stop offset="1" class="k10k6_baq"/></radialGradient><radialGradient id="iGFMqWH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60937 0 0 -.8125 10.926 13.473)" gradientUnits="userSpaceOnUse"><stop class="x9q-1ua-h"/><stop offset="1" class="d_y83zkbz"/></radialGradient><radialGradient id="iRjmOQY" cx="0" cy="0" r="1" gradientTransform="rotate(-177.049 5.42 8.54)scale(3.03527 4.59892)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="ftdzlkbpm"/><stop offset="1" class="iu-l6acky"/></radialGradient><radialGradient id="iheSTgO" cx="0" cy="0" r="1" gradientTransform="rotate(-50.886 21.06 3.067)scale(3.51696 3.66873)" gradientUnits="userSpaceOnUse"><stop class="ap_fa_bgx"/><stop offset="1" class="wnm2vg-zq"/></radialGradient><radialGradient id="ieaWAvd" cx="0" cy="0" r="1" gradientTransform="matrix(3 3.65625 -3.78158 3.10283 22.894 7.317)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="vas9tjbit"/><stop offset="1" class="ny-1wemya"/></radialGradient><radialGradient id="ikytyIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.61462 -2.0661 0 25.705 7.453)" gradientUnits="userSpaceOnUse"><stop offset=".759" class="viuzncbxq"/><stop offset="1" class="ej1v0hbca"/></radialGradient><radialGradient id="iW4kXJz" cx="0" cy="0" r="1" gradientTransform="rotate(145.359 13.401 8.53)scale(3.99771 2.68184)" gradientUnits="userSpaceOnUse"><stop class="uvv0p6btj"/><stop offset="1" class="elep40b9c"/></radialGradient><radialGradient id="iUDojFc" cx="0" cy="0" r="1" gradientTransform="rotate(144.673 12.844 7.022)scale(4.07349 4.5687)" gradientUnits="userSpaceOnUse"><stop class="a-lhjfbpa"/><stop offset="1" class="begh2ub5w"/></radialGradient><radialGradient id="iNZ1RrM" cx="0" cy="0" r="1" gradientTransform="rotate(-133.348 14.9 -2.216)scale(4.59811 4.64228)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="po1nyh2al"/><stop offset=".913" class="cjnv6q4jy"/></radialGradient><radialGradient id="i63AZyd" cx="0" cy="0" r="1" gradientTransform="rotate(-111.272 15.595 -6.12)scale(2.19652 2.90326)" gradientUnits="userSpaceOnUse"><stop offset=".052" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="i9PjRok" cx="0" cy="0" r="1" gradientTransform="rotate(169.078 4.613 9.242)scale(.86923 2.54329)" gradientUnits="userSpaceOnUse"><stop class="x8lzjv-mn"/><stop offset="1" class="ijlg4dfja"/></radialGradient><radialGradient id="i11YRMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 -1.35937 1.36127 -1.0327 11.347 19.38)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="b85todb1f"/><stop offset="1" class="vl6e3-baw"/></radialGradient><radialGradient id="iaiUvYc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32561 -.24315 .57714 -3.14644 21.566 17.606)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="a32mo4bai"/><stop offset="1" class="z3h5ugg6t"/></radialGradient><radialGradient id="iDA8kBb" cx="0" cy="0" r="1" gradientTransform="matrix(1.29688 0 0 3.51563 9.613 15.114)" gradientUnits="userSpaceOnUse"><stop class="mh2c_fbnn"/><stop offset="1" class="oluxj4fur"/></radialGradient><radialGradient id="iQBx3Zc" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -2.48438 1.26202 .84135 20.322 15.852)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="af7g4xwlv"/><stop offset="1" class="dq3narb_o"/></radialGradient><radialGradient id="idkJ77c" cx="0" cy="0" r="1" gradientTransform="matrix(1.22473 0 0 1.03239 20.322 14.712)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="kmiii3bcp"/><stop offset="1" class="tnz7odosx"/></radialGradient><radialGradient id="ivCiGge" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -5.34375 18.832 16.004)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="v_i9pobxh"/><stop offset="1" class="inzxmvq9c"/></radialGradient><radialGradient id="iGgA2he" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -1.0625 .84812 -.79823 13.8 13.91)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="abh2gabji"/><stop offset="1" class="z5_8k6fyg"/></radialGradient><radialGradient id="iIEFGdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.03906 1.50975 0 18.09 13.926)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="jm5m0jb3p"/><stop offset="1" class="fn1aitbjk"/></radialGradient><radialGradient id="iSJRkGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5 -9.72937 0 15.742 13.073)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="senuv6btm"/><stop offset="1" class="s56wdsbie"/></radialGradient><radialGradient id="iiTH5ne" cx="0" cy="0" r="1" gradientTransform="matrix(.25176 -.42297 1.41337 .84129 14.475 18.45)" gradientUnits="userSpaceOnUse"><stop class="ehk37q6kg"/><stop offset="1" class="shu6gjbob"/></radialGradient><radialGradient id="ilu7A9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .20695 -.61269 0 16.07 16.511)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="i59hpcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81359 -1.2941 0 17.941 14.302)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ihfUwfd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.379 2.856)scale(.37895 .52172)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isqlRBC" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81363 -1.29417 0 13.565 14.301)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iHvtRfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00775 -.49495 .59495 -.00931 13.277 14.52)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iP3ZHLd" cx="0" cy="0" r="1" gradientTransform="matrix(.06839 -.65954 5.09164 .52797 18.191 11.903)" gradientUnits="userSpaceOnUse"><stop class="ktr4-_bkr"/><stop offset=".899" class="yffndbb9h"/></radialGradient><radialGradient id="ieKgpEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.007 25.3)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iXpxY5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.007 26.595)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iqyM8Fd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.007 27.845)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iwcE5mb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.007 29.196)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><filter id="izV1The" width="12.098" height="6.858" x="9.659" y="17.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".1"/></filter><filter id="ieQNwEd" width="3.75" height="3.003" x="13.834" y="21.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.105882 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1071"/></filter><filter id="i529zhb" width="6.328" height="3.25" x="15.66" y="1.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.521569 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1071"/></filter><filter id="iFdvrBe" width="23.09" height="7.66" x="4.2" y="10.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".125"/></filter><filter id="i9GbyfR" width="5.46" height="21.857" x="23.1" y="5.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.45098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1071"/></filter><filter id="iajjOOw" width="1.8" height="17.408" x="25.202" y="9.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".325"/></filter><filter id="isayadc" width="2.625" height="2.625" x="9.703" y="13.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".125"/></filter><filter id="iblXWuc" width="2.425" height="2.425" x="19.272" y="13.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".075"/></filter><filter id="ipO5and" width="11.175" height="10.15" x="10.386" y="11.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.239216 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1071"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.133333 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1071" result="effect2_innerShadow_4002_1071"/></filter><filter id="iCK2b2b" width="3.813" height="1.561" x="13.842" y="17.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".05"/></filter><filter id="iTIwSsq" width="2.707" height="3.647" x="14.235" y="14.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".25"/></filter><filter id="i1e2nJl" width=".788" height=".697" x="17.205" y="13.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".05"/></filter><filter id="ic14lRB" width=".892" height=".914" x="18.048" y="13.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".1"/></filter><filter id="ifjHoie" width=".987" height="1.041" x="13.593" y="13.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".1"/></filter><filter id="iBGNSJc" width=".914" height=".705" x="12.835" y="13.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".05"/></filter><filter id="iywQKed" width="2.242" height="1.109" x="11.984" y="12.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.454902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1071"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.588235 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1071" result="effect2_innerShadow_4002_1071"/></filter><filter id="i606Goc" width="2.242" height="1.109" x="17.289" y="12.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.454902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1071"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.588235 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1071" result="effect2_innerShadow_4002_1071"/></filter><filter id="iL8h91c" width="4.368" height=".847" x="16.494" y="11.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.427451 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1071"/></filter><filter id="iGzPhrc" width="4.846" height="5.556" x="23.357" y="24.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1071"/></filter><filter id="iEmmEAd" width="2.097" height=".3" x="23.727" y="25.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".05"/></filter><filter id="iSrpeUw" width="2.097" height=".3" x="23.649" y="27.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".05"/></filter><filter id="iza7n3d" width="2.097" height=".3" x="23.727" y="28.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1071" stdDeviation=".05"/></filter><linearGradient id="ibfF9pc" x1="21.582" x2="10.613" y1="21.66" y2="21.66" gradientUnits="userSpaceOnUse"><stop class="q8c8skp1q"/><stop offset="1" class="n7c2bfbtc"/></linearGradient><linearGradient id="inhs3Gr" x1="16.175" x2="16.925" y1="19.567" y2="23.848" gradientUnits="userSpaceOnUse"><stop offset=".287" class="cvgk3kbak"/><stop offset="1" class="c6lp81bhp"/></linearGradient><linearGradient id="ir99qxd" x1="19.144" x2="19.472" y1="5.207" y2="3.848" gradientUnits="userSpaceOnUse"><stop class="guc8z7bij"/><stop offset="1" class="iov6rh-pq"/></linearGradient><linearGradient id="iDiuhqc" x1="7.907" x2="22.372" y1="19.98" y2="19.98" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kdl2hbbyb"/><stop offset="1" class="valdy-bly"/></linearGradient><linearGradient id="iirSkZf" x1="17.363" x2="17.363" y1="8.504" y2="7.317" gradientUnits="userSpaceOnUse"><stop class="u3wf8s8gl"/><stop offset="1" class="pt6842k6d"/></linearGradient><linearGradient id="ixovgFc" x1="14.176" x2="20.238" y1="9.91" y2="9.754" gradientUnits="userSpaceOnUse"><stop class="p-go_8bpa"/><stop offset="1" class="tp_ivrbui"/></linearGradient><linearGradient id="iAwNGNd" x1="21.863" x2="19.269" y1="9.285" y2="9.285" gradientUnits="userSpaceOnUse"><stop class="xrhcfrbuk"/><stop offset="1" class="psjmui2lw"/></linearGradient><linearGradient id="i4jnpHd" x1="9.738" x2="11.957" y1="9.519" y2="10.534" gradientUnits="userSpaceOnUse"><stop class="cvjhjoe1h"/><stop offset="1" class="wmajqfcti"/></linearGradient><linearGradient id="iGAAS2d" x1="15.745" x2="15.745" y1="11.364" y2="16.817" gradientUnits="userSpaceOnUse"><stop class="flda2eefx"/><stop offset="1" class="leei8_8-z"/></linearGradient><linearGradient id="i8ElAPc" x1="24.372" x2="28.31" y1="10.532" y2="10.532" gradientUnits="userSpaceOnUse"><stop class="kytdhlviv"/><stop offset="1" class="bf9jtobby"/></linearGradient><linearGradient id="i2O0dbd" x1="26.602" x2="26.602" y1="9.925" y2="25.533" gradientUnits="userSpaceOnUse"><stop class="pafpa8b3r"/><stop offset="1" class="irkpemyfq"/></linearGradient><linearGradient id="iQh5hlb" x1="14.916" x2="15.825" y1="15.925" y2="15.925" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iTCgt2b" x1="16.662" x2="15.669" y1="16.264" y2="16.251" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iNgtIlf" x1="15.942" x2="15.942" y1="17.044" y2="16.442" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="ix5afEe" x1="18.721" x2="18.407" y1="14.355" y2="14.549" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKY1KDc" x1="14.31" x2="13.996" y1="14.355" y2="14.549" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3icBIe" x1="27.738" x2="23.357" y1="28.058" y2="28.058" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="ikdzT8X" x1="23.877" x2="25.586" y1="26.052" y2="26.052" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="ieqS9Gd" x1="23.799" x2="25.508" y1="27.356" y2="27.356" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iY3AXue" x1="23.877" x2="25.586" y1="28.661" y2="28.661" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-mage-dark" /></template>
<style>
.a-lhjfbpa {
  stop-color: var(--svg-color--4ddcff, #4DDCFF);
}

.a07exk92a {
  fill: var(--svg-color--000, #000);
  d: path("M17.43 14.718a.51.51 0 0 1 .514-.513a.51.51 0 0 1 .455.749h-.907a.46.46 0 0 1-.061-.236");
}

.a32mo4bai {
  stop-color: var(--svg-color--dcdee8, #DCDEE8);
}

.a3c-8ubyu {
  stop-color: var(--svg-color--41a8ff, #41A8FF);
}

.a4bu2nb4b {
  stop-color: var(--svg-color--433a3c, #433A3C);
}

.a4o2qybrp {
  d: path("M18.74 14.6a.84.84 0 0 0-.232-.464l-.26.286l.117.228z");
}

.abh2gabji {
  stop-color: var(--svg-color--351e26, #351E26);
}

.af7g4xwlv {
  stop-color: var(--svg-color--3f292c, #3F292C);
}

.ap_fa_bgx {
  stop-color: var(--svg-color--3171db, #3171DB);
}

.azeqcu15x {
  stop-color: var(--svg-color--215a98, #215A98);
}

.b43uiy30g {
  d: path("M26.94 5.304c-.2-.11-.45.04-.45.27v1.62c0 .44-.36.81-.8.8a.786.786 0 0 1-.77-.78v-1.64c0-.23-.25-.38-.45-.27c-.81.44-1.36 1.29-1.37 2.27c-.01 1.01.58 1.9 1.43 2.34c.1.05.16.15.16.26v15.91c0 .57.47 1.04 1.04 1.04s1.04-.47 1.04-1.04v-15.93c0-.11.06-.21.16-.26a2.605 2.605 0 0 0 .01-4.59");
}

.b85todb1f {
  stop-color: var(--svg-color--717181, #717181);
}

.begh2ub5w {
  stop-color: var(--svg-color--2f85fe, #2F85FE);
}

.bf9jtobby {
  stop-color: var(--svg-color--e4a771, #E4A771);
}

.bgqsi-bps {
  stop-color: var(--svg-color--445e86, #445E86);
  stop-opacity: 0;
}

.bkffn87la {
  stop-color: var(--svg-color--3da9f9, #3DA9F9);
  stop-opacity: 0;
}

.bn4p-sbtt {
  d: path("M25.643 5.46a.876.876 0 1 1 1.575-.76l.122.297a.857.857 0 0 1-1.54.743z");
}

.bpqf_uv7t {
  fill: var(--svg-color--351a25, #351A25);
  d: path("m15.241 14.842l-.483 1.677c-.099.345.138.69.473.69h.715c.336 0 .572-.35.474-.69l-.484-1.677c-.103-.372-.586-.372-.695 0");
}

.c5r226cip {
  stop-color: var(--svg-color--2483f6, #2483F6);
}

.c6lp81bhp {
  stop-color: var(--svg-color--307099, #307099);
  stop-opacity: 0;
}

.cedz8lbio {
  d: path("M17.943 13.823a.895.895 0 0 1 .863 1.131h-1.729a.898.898 0 0 1 .866-1.13");
}

.cfof8-eyu {
  fill: var(--svg-color--000, #000);
  d: path("M14.076 14.718a.51.51 0 0 0-.513-.513a.51.51 0 0 0-.456.749h.907a.5.5 0 0 0 .062-.236");
}

.cjnv6q4jy {
  stop-color: var(--svg-color--4093be, #4093BE);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cvgk3kbak {
  stop-color: var(--svg-color--1c3b69, #1C3B69);
}

.cvjhjoe1h {
  stop-color: var(--svg-color--57515f, #57515F);
}

.d_y83zkbz {
  stop-color: var(--svg-color--14488d, #14488D);
  stop-opacity: 0;
}

.d-kfqjw9b {
  d: path("M25.71 8.674a2.6 2.6 0 1 0 0-5.2a2.6 2.6 0 0 0 0 5.2");
}

.d45gne0nz {
  stop-color: var(--svg-color--073880, #073880);
}

.d86qxubue {
  d: path("M15.66 2.004c2.84 0 4.71.95 5.81 1.77c.52.39.23 1.22-.42 1.22l-5.31.01z");
}

.dekz5-i5a {
  stop-color: var(--svg-color--3395e6, #3395E6);
}

.dgbyghhck {
  stop-color: var(--svg-color--2f79b8, #2F79B8);
}

.dn-ogvbjy {
  stop-color: var(--svg-color--2982ee, #2982EE);
}

.dq3narb_o {
  stop-color: var(--svg-color--251a2a, #251A2A);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7_y1ioqg {
  stop-color: var(--svg-color--2e99f4, #2E99F4);
}

.ebcvm6lto {
  stop-color: var(--svg-color--39a7ff, #39A7FF);
  stop-opacity: 0;
}

.edkhrwbqz {
  fill: var(--svg-color--3978a9, #3978A9);
  d: path("M15.708 24.473c-.183 0-.687-.155-1.405-.738a192 192 0 0 1-3.762-3.18c-.216-.187-.671-.668-.566-1.192c.164-.82 1.359-1.148 3.203-1.148h5.061c1.844 0 3.04.328 3.203 1.148c.105.524-.35 1.005-.566 1.192a194 194 0 0 1-3.762 3.18c-.718.583-1.155.738-1.405.738z");
}

.ehk37q6kg {
  stop-color: var(--svg-color--574949, #574949);
}

.ej1v0hbca {
  stop-color: var(--svg-color--ba795b, #BA795B);
  stop-opacity: 0;
}

.elep40b9c {
  stop-color: var(--svg-color--cc8c6f, #CC8C6F);
  stop-opacity: 0;
}

.embu-7brp {
  stop-color: var(--svg-color--4ab4f4, #4AB4F4);
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.etcccebor {
  d: path("M13.563 13.823a.895.895 0 0 0-.863 1.13h1.73a1 1 0 0 0 .032-.235a.9.9 0 0 0-.899-.895");
}

.f_5qi3ocn {
  cx: 13.293px;
  cy: 14.206px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.198px;
}

.f-3q63keb {
  stop-color: var(--svg-color--4a6a97, #4A6A97);
}

.f-4jpbbcr {
  stroke: var(--svg-color--a8a9b2, #A8A9B2);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.281 12.99c-.221-.17-.855-.52-1.742-.376");
}

.f-m4mzz6d {
  stop-color: var(--svg-color--3f9de9, #3F9DE9);
  stop-opacity: 0;
}

.f0nb6xb4v {
  fill: var(--svg-color--472f2f, #472F2F);
  d: path("m15.383 14.523l-.514 1.786c-.105.367.147.735.504.735h.761c.357 0 .61-.373.504-.735l-.514-1.786c-.11-.396-.625-.396-.74 0");
}

.f283fd8-c {
  stop-color: var(--svg-color--1b67ab, #1B67AB);
  stop-opacity: 0;
}

.f4tj_uwsg {
  stroke: var(--svg-color--a8a9b2, #A8A9B2);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.234 12.99c.222-.17.856-.52 1.742-.376");
}

.fdfbu9b0b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.799 27.278h1.797");
}

.fgyy3cclr {
  fill: var(--svg-color--39a7ff, #39A7FF);
  d: path("M4.875 29.996c0-2.883 2.987-9.76 10.777-9.76c7.791 0 10.628 6.396 10.868 9.76z");
}

.flda2eefx {
  stop-color: var(--svg-color--4478e6, #4478E6);
}

.fn1aitbjk {
  stop-color: var(--svg-color--3d2225, #3D2225);
  stop-opacity: 0;
}

.fqpzwo9rb {
  stop-color: var(--svg-color--43aaf7, #43AAF7);
}

.ft5dv1b6b {
  fill: none;
}

.ftdzlkbpm {
  stop-color: var(--svg-color--1956ae, #1956AE);
}

.g_yeoeb7z {
  fill: var(--svg-color--290118, #290118);
  d: path("M15.749 18.065c-.54 0-1.04-.13-1.47-.35c-.14-.08-.3.09-.21.23a2.006 2.006 0 0 0 3.36 0c.09-.14-.07-.3-.21-.23c-.43.22-.93.35-1.47.35");
}

.g43afac9g {
  d: path("M15.708 24.473c-.183 0-.687-.155-1.405-.738a192 192 0 0 1-3.762-3.18c-.216-.187-.671-.668-.566-1.192c.164-.82 1.359-1.148 3.203-1.148h5.061c1.844 0 3.04.328 3.203 1.148c.105.524-.35 1.005-.566 1.192a194 194 0 0 1-3.762 3.18c-.718.583-1.155.738-1.405.738z");
}

.g8oaksl8k {
  d: path("M15.694 24.614c-.395 0-1.172-.032-2.446-.477l-.078-.036c-1.438-.657-4.997-2.284-4.851-4.363c0-2.15 3.458-2.156 5.187-1.89h4.405c1.73-.266 5.188-.26 5.188 1.89c.145 2.08-3.414 3.706-4.852 4.363l-.078.036c-1.274.445-2.05.476-2.476.476");
}

.gs_ecdl4e {
  fill: var(--svg-color--402726, #402726);
  fill-rule: evenodd;
  d: path("M17.235 15.409a.3.3 0 0 0 .013.424c.253.238.573.387.854.478s.55.133.718.142a.3.3 0 1 0 .033-.6a2.4 2.4 0 0 1-.566-.113a1.7 1.7 0 0 1-.628-.344a.3.3 0 0 0-.424.013");
}

.guc8z7bij {
  stop-color: var(--svg-color--2caafc, #2CAAFC);
}

.gv_675b8w {
  cx: 11.015px;
  cy: 14.942px;
  r: 1.063px;
  fill: var(--svg-color--26161e, #26161E);
}

.h-e6v32ai {
  d: path("m23.34 18.484l-15.2-.01c-2.45 0-4.45-2-4.45-4.46s2-4.46 4.46-4.46l15.2.01c2.46 0 4.46 2 4.46 4.46a4.48 4.48 0 0 1-4.47 4.46");
}

.h-lv1ubvk {
  d: path("M27.086 23.04a.97.97 0 0 1 .967.967v2.214h-1.934v-2.214a.976.976 0 0 1 .967-.967");
}

.h5iei_ivh {
  fill: var(--svg-color--311d20, #311D20);
  d: path("m15.45 23.977l-1.616-2.754h3.75l-1.617 2.754a.3.3 0 0 1-.517 0");
}

.h79oecc1t {
  cx: 20.484px;
  cy: 14.942px;
  r: 1.063px;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.haiup_bzr {
  cx: 11.015px;
  cy: 14.942px;
  r: 1.672px;
}

.haktz9bdu {
  d: path("M17.877 14.013c.064.085-.07.189-.22.302c-.152.113-.265.193-.328.107c-.064-.085.007-.246.159-.359c.15-.113.325-.136.389-.05");
}

.hbrxqdets {
  d: path("M22.74 18.124H8.75c-2.27 0-4.1-1.51-4.1-3.38s1.84-3.38 4.1-3.38l13.99.01c2.27 0 4.1 1.51 4.1 3.38c0 1.86-1.84 3.37-4.1 3.37");
}

.huu-ickwn {
  stop-color: var(--svg-color--2fb4f5, #2FB4F5);
}

.i2wlb99xo {
  stop-color: var(--svg-color--3e6082, #3E6082);
}

.id0y_n31u {
  stop-color: var(--svg-color--2e65d4, #2E65D4);
}

.ijlg4dfja {
  stop-color: var(--svg-color--85848e, #85848E);
}

.inpzxhbwc {
  stop-color: var(--svg-color--2982ee, #2982EE);
  stop-opacity: 0;
}

.inzxmvq9c {
  stop-color: var(--svg-color--3b2729, #3B2729);
}

.iov6rh-pq {
  stop-color: var(--svg-color--2caafc, #2CAAFC);
  stop-opacity: 0;
}

.irkpemyfq {
  stop-color: var(--svg-color--e3a984, #E3A984);
  stop-opacity: 0;
}

.iu-l6acky {
  stop-color: var(--svg-color--1956ae, #1956AE);
  stop-opacity: 0;
}

.iusprebiv {
  stop-color: var(--svg-color--1868c3, #1868C3);
}

.j_2ccnt5p {
  d: path("m15.383 14.523l-.514 1.786c-.105.367.147.735.504.735h.761c.357 0 .61-.373.504-.735l-.514-1.786c-.11-.396-.625-.396-.74 0");
}

.jm5m0jb3p {
  stop-color: var(--svg-color--3d2225, #3D2225);
}

.job-vz29n {
  d: path("M8.594 22.752c-2.616 2.263-3.72 5.491-3.72 7.244h3.72z");
}

.k10k6_baq {
  stop-color: var(--svg-color--0d50a5, #0D50A5);
  stop-opacity: 0;
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.kdl2hbbyb {
  stop-color: var(--svg-color--cacaca, #CACACA);
}

.kjht8876i {
  stop-color: var(--svg-color--1b0d13, #1B0D13);
}

.kmiii3bcp {
  stop-color: var(--svg-color--3e3031, #3E3031);
}

.ktr4-_bkr {
  stop-color: var(--svg-color--97979c, #97979C);
}

.kytdhlviv {
  stop-color: var(--svg-color--d98350, #D98350);
}

.l0dpenbvj {
  cx: 20.484px;
  cy: 14.942px;
  r: 1.672px;
}

.l15dqlbvn {
  stop-color: var(--svg-color--3e6082, #3E6082);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.leei8_8-z {
  stop-color: var(--svg-color--4478e6, #4478E6);
  stop-opacity: 0;
}

.lehnoh0zf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M26.102 9.925v15.608");
}

.lgnz4ib3a {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m8.75 11.264l13.99.01m-13.99-.01v.1c-2.26 0-4.1 1.51-4.1 3.38s1.83 3.38 4.1 3.38h13.99c2.26 0 4.1-1.51 4.1-3.37c0-1.87-1.83-3.38-4.1-3.38v-.1m-13.99-.01c-2.296 0-4.2 1.538-4.2 3.48s1.894 3.48 4.2 3.48h13.99c2.296 0 4.2-1.537 4.2-3.47c0-1.942-1.894-3.48-4.2-3.48m-13.99-.01l13.99.01");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llv8b_5gn {
  fill: var(--svg-color--332121, #332121);
  fill-rule: evenodd;
  d: path("M14.278 15.409a.3.3 0 0 1-.013.424a2.3 2.3 0 0 1-.854.478a3 3 0 0 1-.718.142a.3.3 0 0 1-.033-.6c.118-.006.333-.037.566-.113c.234-.076.462-.189.628-.344a.3.3 0 0 1 .424.013");
}

.lmlq_xbrl {
  stop-color: var(--svg-color--2fa3f0, #2FA3F0);
  stop-opacity: 0;
}

.m2k7t6jeu {
  stop-color: var(--svg-color--1b0d13, #1B0D13);
  stop-opacity: 0;
}

.m52m3hl4m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.877 25.974h1.797");
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mh2c_fbnn {
  stop-color: var(--svg-color--271d34, #271D34);
}

.mr4lhnuux {
  stop-color: var(--svg-color--2787f2, #2787F2);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n2acyj-6i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.877 28.583h1.797");
}

.n4ma-nbis {
  stop-color: var(--svg-color--1868c3, #1868C3);
  stop-opacity: 0;
}

.n7c2bfbtc {
  stop-color: var(--svg-color--3f7ec7, #3F7EC7);
}

.nvdrdzbmz {
  stop-color: var(--svg-color--12529b, #12529B);
}

.ny-1wemya {
  stop-color: var(--svg-color--ba756c, #BA756C);
  stop-opacity: 0;
}

.nypzj9bha {
  stop-color: var(--svg-color--4394db, #4394DB);
  stop-opacity: 0;
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o8c2nzb0a {
  stop-color: var(--svg-color--307fc2, #307FC2);
}

.o8p2_blib {
  stop-color: var(--svg-color--2e74cb, #2E74CB);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oluxj4fur {
  stop-color: var(--svg-color--32222b, #32222B);
}

.ouyjj2-hs {
  fill-rule: evenodd;
  d: path("M16.494 11.364c.235.226.754.535 1.6.64c.785.099 1.908.114 2.668.105a1.9 1.9 0 0 0-.384-.425c-.293-.218-.523-.32-1.365-.32z");
}

.p-go_8bpa {
  stop-color: var(--svg-color--423851, #423851);
}

.p5_1r5b0y {
  stop-color: var(--svg-color--3da9f9, #3DA9F9);
}

.p7xat6cnl {
  d: path("M21.61 10.464H9.71l.18-.35c1.12-2.16 3.34-8.11 5.77-8.11c2.44 0 4.67 5.96 5.78 8.13z");
}

.pafpa8b3r {
  stop-color: var(--svg-color--e3a984, #E3A984);
}

.phlvo2b_b {
  stop-color: var(--svg-color--4991bb, #4991BB);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po1nyh2al {
  stop-color: var(--svg-color--39a1ff, #39A1FF);
  stop-opacity: 0;
}

.pql562bff {
  stop-color: var(--svg-color--2bbbff, #2BBBFF);
}

.psjmui2lw {
  stop-color: var(--svg-color--665d70, #665D70);
  stop-opacity: 0;
}

.pt6842k6d {
  stop-color: var(--svg-color--50b2e2, #50B2E2);
  stop-opacity: 0;
}

.q-3947b0q {
  stop-color: var(--svg-color--39a8ff, #39A8FF);
  stop-opacity: 0;
}

.q8c8skp1q {
  stop-color: var(--svg-color--3291c8, #3291C8);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.qxprq_b_n {
  stop-color: var(--svg-color--257bd2, #257BD2);
}

.qz94s4bip {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.151 13.55a1.4 1.4 0 0 1 1.359 1.062a.275.275 0 0 1-.269.342h-2.237a.23.23 0 0 1-.228-.273a1.4 1.4 0 0 1 1.375-1.13");
}

.r-yilwbra {
  stop-color: var(--svg-color--35acfa, #35ACFA);
}

.rdaygdbpu {
  stop-color: var(--svg-color--3aa4e9, #3AA4E9);
}

.re9u_5b4n {
  stop-color: var(--svg-color--433a3c, #433A3C);
  stop-opacity: 0;
}

.rec-1hb8e {
  stop-color: var(--svg-color--3797f8, #3797F8);
  stop-opacity: 0;
}

.rj_n-mbmd {
  stop-color: var(--svg-color--267adb, #267ADB);
}

.s_1mw_rhq {
  stop-color: var(--svg-color--4cdbff, #4CDBFF);
}

.s56wdsbie {
  stop-color: var(--svg-color--3b2d56, #3B2D56);
}

.sda7dac5x {
  stop-color: var(--svg-color--215a98, #215A98);
  stop-opacity: 0;
}

.senuv6btm {
  stop-color: var(--svg-color--3b2d56, #3B2D56);
  stop-opacity: 0;
}

.sfuw4b7fs {
  stop-color: var(--svg-color--267adb, #267ADB);
  stop-opacity: 0;
}

.shu6gjbob {
  stop-color: var(--svg-color--574949, #574949);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.szwxs1ffj {
  stop-color: var(--svg-color--2e74cb, #2E74CB);
  stop-opacity: 0;
}

.t4ibp7bdp {
  stop-color: var(--svg-color--359cf2, #359CF2);
  stop-opacity: 0;
}

.takbm9boj {
  stop-color: var(--svg-color--3395e6, #3395E6);
  stop-opacity: 0;
}

.tclwz7mny {
  stop-color: var(--svg-color--2483f6, #2483F6);
  stop-opacity: 0;
}

.tnz7odosx {
  stop-color: var(--svg-color--30191d, #30191D);
}

.tp_ivrbui {
  stop-color: var(--svg-color--584d65, #584D65);
}

.tsk-k9bvn {
  stop-color: var(--svg-color--2fa9e7, #2FA9E7);
  stop-opacity: 0;
}

.u3wf8s8gl {
  stop-color: var(--svg-color--50b2e2, #50B2E2);
}

.u43ch0b3o {
  d: path("M4.875 29.996c0-2.883 2.987-9.76 10.777-9.76c7.791 0 10.628 6.396 10.868 9.76z");
}

.uhl03ccti {
  stop-color: var(--svg-color--4bdaff, #4BDAFF);
}

.uj99bl4ra {
  d: path("M14.38 14.612c0-.289-.235-.481-.298-.54l-.29.28l.178.362z");
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.uuh3gfbsu {
  stop-color: var(--svg-color--2cb1f7, #2CB1F7);
}

.uvv0p6btj {
  stop-color: var(--svg-color--cc8c6f, #CC8C6F);
}

.v_i9pobxh {
  stop-color: var(--svg-color--4b2f2e, #4B2F2E);
}

.valdy-bly {
  stop-color: var(--svg-color--e4e4e4, #E4E4E4);
}

.vas9tjbit {
  stop-color: var(--svg-color--ba756c, #BA756C);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.veybn72ma {
  stop-color: var(--svg-color--2d82d6, #2D82D6);
}

.viuzncbxq {
  stop-color: var(--svg-color--ba795b, #BA795B);
}

.vj4jwbgtj {
  d: path("M21.226 18.153c.318-.587.356-1.65.335-2.11H20.07v3.126c.253-.094.838-.428 1.157-1.016");
}

.vjxojz0pl {
  cx: 13.293px;
  cy: 14.206px;
  rx: 0.39px;
  ry: 0.198px;
}

.vl6e3-baw {
  stop-color: var(--svg-color--a49296, #A49296);
  stop-opacity: 0;
}

.vmjr7rbhn {
  stop-color: var(--svg-color--104e9b, #104E9B);
}

.vnbqzxbma {
  stop-color: var(--svg-color--0d50a5, #0D50A5);
}

.vww-fqhwh {
  d: path("M10.294 18.153c-.32-.587-.357-1.65-.336-2.11h1.492v3.126c-.253-.094-.838-.428-1.156-1.016");
}

.vxkgnhd4n {
  stop-color: var(--svg-color--3171da, #3171DA);
}

.vyxwjf9nd {
  stop-color: var(--svg-color--43aaf7, #43AAF7);
  stop-opacity: 0;
}

.vzg4cacsm {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.749 18.065c-.54 0-1.04-.13-1.47-.35c-.14-.08-.3.09-.21.23a2.006 2.006 0 0 0 3.36 0c.09-.14-.07-.3-.21-.23c-.43.22-.93.35-1.47.35Z");
}

.w879bpb0e {
  d: path("m9.48 10.154l-.19.38h12.74l-.18-.36a7.1 7.1 0 0 0-1.19-1.67h-10a7.5 7.5 0 0 0-1.18 1.65");
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wmajqfcti {
  stop-color: var(--svg-color--423952, #423952);
  stop-opacity: 0;
}

.wnm2vg-zq {
  stop-color: var(--svg-color--3171db, #3171DB);
  stop-opacity: 0;
}

.wup_v_x-y {
  stop-color: var(--svg-color--46a7ed, #46A7ED);
}

.wx5i2acfu {
  d: path("M23.357 25.321c0-.4.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.319-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.407-.657");
}

.x8lzjv-mn {
  stop-color: var(--svg-color--6f7282, #6F7282);
}

.x9q-1ua-h {
  stop-color: var(--svg-color--14488d, #14488D);
}

.x9tw1mbfn {
  stop-color: var(--svg-color--41a8ff, #41A8FF);
  stop-opacity: 0;
}

.x9uzmjbio {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.356 13.55a1.4 1.4 0 0 0-1.359 1.062a.275.275 0 0 0 .268.342h2.238a.23.23 0 0 0 .228-.273a1.405 1.405 0 0 0-1.375-1.13");
}

.xhqrsjbac {
  stop-color: var(--svg-color--3180ec, #3180EC);
}

.xo9yuc7kj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.877 14.013c.064.085-.07.189-.22.302c-.152.113-.265.193-.328.107c-.064-.085.007-.246.159-.359c.15-.113.325-.136.389-.05");
}

.xp31u8b0s {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.271 23.773c.362.294.67.481.914.595c.241.113.421.155.523.155h.001c.268 0 .717-.165 1.437-.75c1.024-.832 2.795-2.34 3.763-3.18c.11-.096.282-.267.413-.482c.13-.214.225-.479.17-.757c-.088-.436-.448-.733-1.006-.92c-.557-.187-1.323-.269-2.247-.269h-5.061c-.924 0-1.69.082-2.248.27c-.557.186-.917.483-1.004.919c-.056.279.038.543.169.757c.131.215.303.386.413.482c.968.84 2.74 2.348 3.763 3.18Z");
}

.xr99hwbgq {
  d: path("m15.45 23.977l-1.616-2.754h3.75l-1.617 2.754a.3.3 0 0 1-.517 0");
}

.xrhcfrbuk {
  stop-color: var(--svg-color--665d70, #665D70);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.yffndbb9h {
  stop-color: var(--svg-color--757bab, #757BAB);
}

.yj5dctbip {
  d: path("M20.955 13.26q0-.015 0 0c.026-.695 0-1.087-.577-1.576c-.293-.218-.523-.32-1.365-.32H12.59c-.82 0-1.466.304-1.727.598c-.26.293-.367.574-.312 1.298l.27 4.69c.265 1.958 1.952 3.414 3.955 3.414h1.92c2.003 0 3.69-1.466 3.955-3.414z");
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z3h5ugg6t {
  stop-color: var(--svg-color--9a9fab, #9A9FAB);
}

.z5_8k6fyg {
  stop-color: var(--svg-color--351e26, #351E26);
  stop-opacity: 0;
}

.zajsytjse {
  stop-color: var(--svg-color--3979aa, #3979AA);
  stop-opacity: 0;
}

.zc_ep_0uq {
  d: path("M22.84 22.759c2.476 2.162 3.537 5.236 3.68 7.237h-3.68z");
}

.zcpjvdbuo {
  d: path("M15.16 19.974h-.04c.1 0 .2 0 .3.01c-.09 0-.18-.01-.26-.01");
}

.zdk8j6bjz {
  stop-color: var(--svg-color--2d6ba6, #2D6BA6);
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zm3svk-ip {
  stop-color: var(--svg-color--4ab3f9, #4AB3F9);
}

.zxip0bczk {
  stop-color: var(--svg-color--104e9b, #104E9B);
  stop-opacity: 0;
}

</style>
